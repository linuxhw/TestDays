Linux in Peru - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Peru.

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

Total: 303

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | T100TA                      | [5be9a0230e](https://linux-hardware.org/?probe=5be9a0230e) | Apr 01, 2023 |
| ASUSTek    | T100TA                      | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Acer       | Aspire ES1-531              | [aedba72f70](https://linux-hardware.org/?probe=aedba72f70) | Mar 31, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [0d7e6b4a80](https://linux-hardware.org/?probe=0d7e6b4a80) | Mar 12, 2023 |
| Lenovo     | ThinkPad T450 20BUA05K00    | [a496755d7a](https://linux-hardware.org/?probe=a496755d7a) | Mar 10, 2023 |
| HP         | Laptop 15-gw0xxx            | [e05606240c](https://linux-hardware.org/?probe=e05606240c) | Feb 28, 2023 |
| HP         | EliteBook 8540p             | [9f543932d2](https://linux-hardware.org/?probe=9f543932d2) | Feb 26, 2023 |
| HP         | Notebook                    | [b929a8ff3c](https://linux-hardware.org/?probe=b929a8ff3c) | Feb 24, 2023 |
| MSI        | Modern 15 A5M               | [f6c80ff7a9](https://linux-hardware.org/?probe=f6c80ff7a9) | Feb 20, 2023 |
| HP         | 14                          | [0244e880e1](https://linux-hardware.org/?probe=0244e880e1) | Feb 19, 2023 |
| HP         | Laptop 15-gw0xxx            | [4bcd17d5a6](https://linux-hardware.org/?probe=4bcd17d5a6) | Feb 17, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Dell       | Inspiron 13 5310            | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| Lenovo     | ThinkPad L15 Gen 1 20U3S... | [ad0b876d84](https://linux-hardware.org/?probe=ad0b876d84) | Feb 10, 2023 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [8d0a0a0422](https://linux-hardware.org/?probe=8d0a0a0422) | Feb 06, 2023 |
| HP         | Pavilion Laptop 15-cc1xx    | [d693442f27](https://linux-hardware.org/?probe=d693442f27) | Feb 03, 2023 |
| Lenovo     | IdeaPad 320-15IKB 80XL      | [5dbc5260b2](https://linux-hardware.org/?probe=5dbc5260b2) | Jan 29, 2023 |
| Lenovo     | IdeaPad 320-15IKB 80XL      | [7c0c804a3e](https://linux-hardware.org/?probe=7c0c804a3e) | Jan 29, 2023 |
| HP         | ProBook 640 G2              | [7b08eeb50c](https://linux-hardware.org/?probe=7b08eeb50c) | Jan 29, 2023 |
| HP         | Compaq Presario C700        | [d2ec58874c](https://linux-hardware.org/?probe=d2ec58874c) | Jan 21, 2023 |
| Lenovo     | IdeaPad 3 15IML05 81WR      | [07b3eb6453](https://linux-hardware.org/?probe=07b3eb6453) | Jan 20, 2023 |
| Toshiba    | Satellite C45-A             | [16f5bae11f](https://linux-hardware.org/?probe=16f5bae11f) | Jan 20, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| HP         | ProBook 655 G1              | [1e3f42b7d1](https://linux-hardware.org/?probe=1e3f42b7d1) | Jan 10, 2023 |
| Toshiba    | Satellite P300              | [d35d765c2f](https://linux-hardware.org/?probe=d35d765c2f) | Jan 09, 2023 |
| Acer       | Aspire VN7-571G             | [88e5718807](https://linux-hardware.org/?probe=88e5718807) | Jan 03, 2023 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [a30f96dea4](https://linux-hardware.org/?probe=a30f96dea4) | Dec 31, 2022 |
| HP         | Laptop 15-dy5xxx            | [d7daff3ed1](https://linux-hardware.org/?probe=d7daff3ed1) | Dec 27, 2022 |
| HP         | Compaq Mini CQ10-100        | [8b34b357bb](https://linux-hardware.org/?probe=8b34b357bb) | Dec 27, 2022 |
| HP         | 255 G8 Notebook PC          | [08800ce691](https://linux-hardware.org/?probe=08800ce691) | Dec 19, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [36a0b6f8d9](https://linux-hardware.org/?probe=36a0b6f8d9) | Dec 16, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [61dd034d23](https://linux-hardware.org/?probe=61dd034d23) | Dec 16, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [17cbc91488](https://linux-hardware.org/?probe=17cbc91488) | Dec 10, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [4b9eb9fcab](https://linux-hardware.org/?probe=4b9eb9fcab) | Dec 10, 2022 |
| Lenovo     | IdeaPad U400 099342G        | [9ecbde32ab](https://linux-hardware.org/?probe=9ecbde32ab) | Dec 06, 2022 |
| HUAWEI     | CREM-WXX9                   | [2436f4cf5e](https://linux-hardware.org/?probe=2436f4cf5e) | Nov 30, 2022 |
| HP         | 255 G7 Notebook PC          | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| HP         | 250 G7 Notebook PC          | [10b5bb5eab](https://linux-hardware.org/?probe=10b5bb5eab) | Nov 17, 2022 |
| HP         | 250 G7 Notebook PC          | [c765249482](https://linux-hardware.org/?probe=c765249482) | Nov 17, 2022 |
| Lenovo     | Legion 7 16ITHg6 82K6       | [eebc3537d1](https://linux-hardware.org/?probe=eebc3537d1) | Nov 09, 2022 |
| HP         | Pavilion Laptop 15-cw1xx... | [b4d22497e8](https://linux-hardware.org/?probe=b4d22497e8) | Nov 08, 2022 |
| HP         | Pavilion Laptop 15-cc1xx    | [b97ba1d3f0](https://linux-hardware.org/?probe=b97ba1d3f0) | Nov 07, 2022 |
| Lenovo     | Legion 7 16ITHg6 82K6       | [88a69a9a20](https://linux-hardware.org/?probe=88a69a9a20) | Nov 05, 2022 |
| Dell       | Latitude E5470              | [4de6b7bdb8](https://linux-hardware.org/?probe=4de6b7bdb8) | Nov 04, 2022 |
| Dell       | Latitude 5420               | [717e0e6d40](https://linux-hardware.org/?probe=717e0e6d40) | Nov 03, 2022 |
| Lenovo     | ThinkPad E15 Gen 2 20TES... | [209e99f964](https://linux-hardware.org/?probe=209e99f964) | Nov 02, 2022 |
| Lenovo     | ThinkPad E15 Gen 2 20TES... | [f12fc289fa](https://linux-hardware.org/?probe=f12fc289fa) | Nov 02, 2022 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [dca18dced0](https://linux-hardware.org/?probe=dca18dced0) | Oct 30, 2022 |
| Acer       | Aspire 5745                 | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| HP         | Pavilion Laptop 15-cc1xx    | [a977f9c3e9](https://linux-hardware.org/?probe=a977f9c3e9) | Oct 26, 2022 |
| ASUSTek    | X205TA                      | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| ADVANCE    | PS5077                      | [998e544711](https://linux-hardware.org/?probe=998e544711) | Oct 22, 2022 |
| ADVANCE    | PS5077                      | [97bfff0fc6](https://linux-hardware.org/?probe=97bfff0fc6) | Oct 22, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [07acd27a70](https://linux-hardware.org/?probe=07acd27a70) | Oct 21, 2022 |
| Dell       | Latitude E5470              | [11ad7cd084](https://linux-hardware.org/?probe=11ad7cd084) | Oct 20, 2022 |
| ASUSTek    | VivoBook 15_ASUS Laptop ... | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop M350... | [f15acdf9d4](https://linux-hardware.org/?probe=f15acdf9d4) | Oct 09, 2022 |
| HUAWEI     | BOHB-WAX9                   | [6fec6456bc](https://linux-hardware.org/?probe=6fec6456bc) | Oct 07, 2022 |
| HUAWEI     | BOHB-WAX9                   | [fb954f84b4](https://linux-hardware.org/?probe=fb954f84b4) | Oct 07, 2022 |
| HUAWEI     | BOHB-WAX9                   | [d56cf9868c](https://linux-hardware.org/?probe=d56cf9868c) | Oct 07, 2022 |
| Lenovo     | IdeaPad 320-15ISK 80XH      | [44afa82c4a](https://linux-hardware.org/?probe=44afa82c4a) | Sep 19, 2022 |
| ASUSTek    | S550CA                      | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| HP         | Laptop 15-ef1xxx            | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Lenovo     | V330-15IKB 81AX             | [0a91582802](https://linux-hardware.org/?probe=0a91582802) | Sep 14, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [2267f01dee](https://linux-hardware.org/?probe=2267f01dee) | Aug 27, 2022 |
| Lenovo     | G570 4334                   | [7bea18122c](https://linux-hardware.org/?probe=7bea18122c) | Aug 27, 2022 |
| HP         | 255 G7 Notebook PC          | [c001653a5a](https://linux-hardware.org/?probe=c001653a5a) | Aug 20, 2022 |
| Dell       | Vostro 3405                 | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Dell       | Latitude E6430              | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell       | Latitude E6430              | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| Lenovo     | ThinkPad T60 1953D9U        | [1c31cb6b44](https://linux-hardware.org/?probe=1c31cb6b44) | Jul 21, 2022 |
| Acer       | Aspire A515-51G             | [4414dd4c1b](https://linux-hardware.org/?probe=4414dd4c1b) | Jul 19, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [b511d2883b](https://linux-hardware.org/?probe=b511d2883b) | Jul 16, 2022 |
| Lenovo     | ThinkPad X140e 20BLA00C0... | [8c160ae192](https://linux-hardware.org/?probe=8c160ae192) | Jul 12, 2022 |
| Acer       | Aspire ES1-512              | [aa2ad87835](https://linux-hardware.org/?probe=aa2ad87835) | Jul 08, 2022 |
| Acer       | Aspire V3-471               | [75664ddf0f](https://linux-hardware.org/?probe=75664ddf0f) | Jul 07, 2022 |
| ASUSTek    | S550CA                      | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| MSI        | GL65 Leopard 10SEK          | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| Lenovo     | ThinkPad X140e 20BLA00C0... | [01fbfc98f8](https://linux-hardware.org/?probe=01fbfc98f8) | Jun 27, 2022 |
| Lenovo     | V15-IIL 82C5                | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| HP         | Laptop 15-ef1xxx            | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell       | Inspiron 15-3567            | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Dell       | Inspiron 15 7000 Gaming     | [fac01563a9](https://linux-hardware.org/?probe=fac01563a9) | Jun 24, 2022 |
| HP         | Laptop 15-ef1xxx            | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell       | Inspiron 5570               | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| ASUSTek    | S550CA                      | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Dell       | Inspiron 15-3567            | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| Lenovo     | V15-IIL 82C5                | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
| HUAWEI     | NBLB-WAX9N                  | [e24239a843](https://linux-hardware.org/?probe=e24239a843) | Jun 09, 2022 |
| ASUSTek    | S550CA                      | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| Dell       | Latitude E7450              | [29219339b2](https://linux-hardware.org/?probe=29219339b2) | Jun 05, 2022 |
| ASUSTek    | ROG Strix G513QY_G513QY     | [49c400d1f7](https://linux-hardware.org/?probe=49c400d1f7) | May 31, 2022 |
| HP         | Pavilion Laptop 15-cw1xx... | [be0f84abb3](https://linux-hardware.org/?probe=be0f84abb3) | May 30, 2022 |
| ASUSTek    | X555UQ                      | [c266f3d070](https://linux-hardware.org/?probe=c266f3d070) | May 30, 2022 |
| Lenovo     | ThinkPad P52 20MAS3X200     | [da2a67f904](https://linux-hardware.org/?probe=da2a67f904) | May 28, 2022 |
| Acer       | TravelMate 5320             | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| Lenovo     | ThinkPad P52 20MAS3X200     | [7f0fc0c72e](https://linux-hardware.org/?probe=7f0fc0c72e) | May 19, 2022 |
| ASUSTek    | ROG Strix G513QY_G513QY     | [2ee4916960](https://linux-hardware.org/?probe=2ee4916960) | May 18, 2022 |
| Dell       | Vostro 3405                 | [fcec5f1cdd](https://linux-hardware.org/?probe=fcec5f1cdd) | May 17, 2022 |
| ASUSTek    | ROG Strix G513QY_G513QY     | [21f3f7368f](https://linux-hardware.org/?probe=21f3f7368f) | May 17, 2022 |
| Dell       | Vostro 3405                 | [3c8e334d43](https://linux-hardware.org/?probe=3c8e334d43) | May 12, 2022 |
| Lenovo     | Legion 5 17ITH6H 82JM       | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| Lenovo     | ThinkPad T530 24296G9       | [934e13a24c](https://linux-hardware.org/?probe=934e13a24c) | May 08, 2022 |
| HP         | ZBook 15                    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| Compal     | QAQXX                       | [d3211e6bc6](https://linux-hardware.org/?probe=d3211e6bc6) | May 05, 2022 |
| HP         | Laptop 15-ef1xxx            | [d2eb5ae290](https://linux-hardware.org/?probe=d2eb5ae290) | May 05, 2022 |
| Lenovo     | V310-15ISK 80SY             | [1a791b0fd5](https://linux-hardware.org/?probe=1a791b0fd5) | May 04, 2022 |
| Lenovo     | V310-15ISK 80SY             | [3846d07c7f](https://linux-hardware.org/?probe=3846d07c7f) | May 04, 2022 |
| HP         | ENVY dv6                    | [23ad3290c2](https://linux-hardware.org/?probe=23ad3290c2) | May 03, 2022 |
| Lenovo     | ThinkPad L15 Gen 1 20U3S... | [74eec8c684](https://linux-hardware.org/?probe=74eec8c684) | May 01, 2022 |
| Lenovo     | V330-15IKB 81AX             | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Lenovo     | IdeaPad S145-15IWL 81MV     | [05db30a69b](https://linux-hardware.org/?probe=05db30a69b) | Apr 30, 2022 |
| Acer       | Aspire E5-571               | [ebdc8b1380](https://linux-hardware.org/?probe=ebdc8b1380) | Apr 30, 2022 |
| Acer       | Aspire A315-23              | [865091bbc1](https://linux-hardware.org/?probe=865091bbc1) | Apr 30, 2022 |
| Acer       | Aspire A315-23              | [5ee29c3982](https://linux-hardware.org/?probe=5ee29c3982) | Apr 30, 2022 |
| ASUSTek    | X556UR                      | [3f920954f7](https://linux-hardware.org/?probe=3f920954f7) | Apr 30, 2022 |
| HP         | Pavilion Sleekbook 15       | [0003f9342e](https://linux-hardware.org/?probe=0003f9342e) | Apr 30, 2022 |
| HP         | Laptop 14-dq1xxx            | [7c9e2f4d8f](https://linux-hardware.org/?probe=7c9e2f4d8f) | Apr 30, 2022 |
| HP         | Notebook                    | [94f0ce7610](https://linux-hardware.org/?probe=94f0ce7610) | Apr 26, 2022 |
| Dell       | Vostro 3405                 | [2d5bae0eeb](https://linux-hardware.org/?probe=2d5bae0eeb) | Apr 24, 2022 |
| HP         | Pavilion Laptop 15-cw1xx... | [a33d067e62](https://linux-hardware.org/?probe=a33d067e62) | Apr 18, 2022 |
| HP         | Compaq Mini CQ10-100        | [89c92e2cf7](https://linux-hardware.org/?probe=89c92e2cf7) | Apr 15, 2022 |
| Dell       | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| HP         | ZBook Firefly 15 G7 Mobi... | [0e9e99acae](https://linux-hardware.org/?probe=0e9e99acae) | Apr 13, 2022 |
| Lenovo     | ThinkPad X140e 20BLA00C0... | [9cad677222](https://linux-hardware.org/?probe=9cad677222) | Mar 24, 2022 |
| HP         | Stream Laptop 14-ax0XX      | [9b99145008](https://linux-hardware.org/?probe=9b99145008) | Mar 21, 2022 |
| HP         | Laptop 14-ck0xxx            | [92c7141f37](https://linux-hardware.org/?probe=92c7141f37) | Mar 12, 2022 |
| HP         | 340 G2                      | [c4f663b37b](https://linux-hardware.org/?probe=c4f663b37b) | Mar 04, 2022 |
| HP         | Pavilion Laptop 15-cd0xx    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Acer       | Aspire 4750                 | [b8f02b07fb](https://linux-hardware.org/?probe=b8f02b07fb) | Feb 18, 2022 |
| Acer       | Aspire 4750                 | [3269f565c4](https://linux-hardware.org/?probe=3269f565c4) | Feb 18, 2022 |
| HP         | 240 G7 Notebook PC          | [03f63a3789](https://linux-hardware.org/?probe=03f63a3789) | Feb 09, 2022 |
| efirstview | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Toshiba    | Satellite C645              | [d552c9b132](https://linux-hardware.org/?probe=d552c9b132) | Feb 04, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [b7cb93aff2](https://linux-hardware.org/?probe=b7cb93aff2) | Jan 25, 2022 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| Lenovo     | IdeaPad S340-15API 81NC     | [1f065ea4dd](https://linux-hardware.org/?probe=1f065ea4dd) | Jan 12, 2022 |
| Sony       | VGN-FW56M                   | [9fb3fa0f32](https://linux-hardware.org/?probe=9fb3fa0f32) | Jan 09, 2022 |
| Lenovo     | IdeaPad S540-14API 81NH     | [eb23bd590c](https://linux-hardware.org/?probe=eb23bd590c) | Jan 07, 2022 |
| Toshiba    | Satellite E205              | [92431da366](https://linux-hardware.org/?probe=92431da366) | Dec 24, 2021 |
| Lenovo     | G400 20235                  | [c2bb5d0010](https://linux-hardware.org/?probe=c2bb5d0010) | Dec 18, 2021 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [020b7460a1](https://linux-hardware.org/?probe=020b7460a1) | Dec 11, 2021 |
| HP         | Pavilion Gaming Laptop 1... | [fefa594281](https://linux-hardware.org/?probe=fefa594281) | Dec 10, 2021 |
| HP         | 250 G5 Notebook PC          | [3cd230924a](https://linux-hardware.org/?probe=3cd230924a) | Dec 04, 2021 |
| Lenovo     | ThinkPad X1 Carbon Gen 8... | [54f954491a](https://linux-hardware.org/?probe=54f954491a) | Nov 21, 2021 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [e085c7e42a](https://linux-hardware.org/?probe=e085c7e42a) | Nov 09, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [90fbcc38c3](https://linux-hardware.org/?probe=90fbcc38c3) | Nov 08, 2021 |
| Dell       | XPS 13 9360                 | [61db5bc9b5](https://linux-hardware.org/?probe=61db5bc9b5) | Nov 04, 2021 |
| Lenovo     | ThinkPad E15 Gen 2 20TES... | [df2d173d7c](https://linux-hardware.org/?probe=df2d173d7c) | Nov 01, 2021 |
| Lenovo     | V14-ARE 82DQ                | [8948989999](https://linux-hardware.org/?probe=8948989999) | Oct 31, 2021 |
| HP         | Laptop 15-db0xxx            | [f4d2f1104e](https://linux-hardware.org/?probe=f4d2f1104e) | Oct 28, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [849c03d63c](https://linux-hardware.org/?probe=849c03d63c) | Oct 21, 2021 |
| Lenovo     | IdeaPad 3 14ADA05 81W0      | [87d959803d](https://linux-hardware.org/?probe=87d959803d) | Oct 15, 2021 |
| Dell       | XPS 13 9360                 | [8bb0307157](https://linux-hardware.org/?probe=8bb0307157) | Sep 25, 2021 |
| HP         | Notebook                    | [36fd24364d](https://linux-hardware.org/?probe=36fd24364d) | Sep 24, 2021 |
| Advance    | AN-5431                     | [d48465a943](https://linux-hardware.org/?probe=d48465a943) | Sep 14, 2021 |
| HP         | Notebook                    | [2a564798fd](https://linux-hardware.org/?probe=2a564798fd) | Sep 11, 2021 |
| Lenovo     | ThinkPad T440 20B7A08500    | [b7e859020c](https://linux-hardware.org/?probe=b7e859020c) | Aug 26, 2021 |
| HP         | 450                         | [9f5d03c478](https://linux-hardware.org/?probe=9f5d03c478) | Aug 19, 2021 |
| Chuwi      | GemiBook Pro                | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| Lenovo     | IdeaPad 3 14ADA05 81W0      | [392df1ef2b](https://linux-hardware.org/?probe=392df1ef2b) | Aug 13, 2021 |
| ASUSTek    | X542UQ                      | [63d2276d55](https://linux-hardware.org/?probe=63d2276d55) | Aug 03, 2021 |
| Advance    | AN-5431                     | [06409d8637](https://linux-hardware.org/?probe=06409d8637) | Aug 01, 2021 |
| Lenovo     | ThinkPad T580 20LAS0XD00    | [36f1b3eb94](https://linux-hardware.org/?probe=36f1b3eb94) | Jul 31, 2021 |
| Dell       | Latitude E5540              | [44b8f3a781](https://linux-hardware.org/?probe=44b8f3a781) | Jul 23, 2021 |
| HP         | Pavilion dv6                | [3e69858907](https://linux-hardware.org/?probe=3e69858907) | Jul 09, 2021 |
| Lenovo     | ThinkPad L460 20FVA0G400    | [378021c178](https://linux-hardware.org/?probe=378021c178) | Jul 06, 2021 |
| ASUSTek    | ROG Strix G532LW_G532LWI    | [b36be47753](https://linux-hardware.org/?probe=b36be47753) | Jun 27, 2021 |
| HP         | Pavilion Notebook           | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Lenovo     | IdeaPad S540-14API 81NH     | [003f0d1c2a](https://linux-hardware.org/?probe=003f0d1c2a) | Jun 21, 2021 |
| ASUSTek    | ROG Strix G532LW_G532LWI    | [1344b72b26](https://linux-hardware.org/?probe=1344b72b26) | Jun 20, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [6670e1c145](https://linux-hardware.org/?probe=6670e1c145) | Jun 01, 2021 |
| ASUSTek    | VivoBook_ASUSLaptop X509... | [af8045a7b3](https://linux-hardware.org/?probe=af8045a7b3) | May 31, 2021 |
| ASUSTek    | X550LD                      | [89bed4ca0a](https://linux-hardware.org/?probe=89bed4ca0a) | May 28, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [ee9233be38](https://linux-hardware.org/?probe=ee9233be38) | May 26, 2021 |
| HP         | ProBook 450 G1              | [6d64546949](https://linux-hardware.org/?probe=6d64546949) | May 23, 2021 |
| HP         | ProBook 450 G1              | [1b52ac3979](https://linux-hardware.org/?probe=1b52ac3979) | May 23, 2021 |
| HP         | 240 G7                      | [9fff9c48ab](https://linux-hardware.org/?probe=9fff9c48ab) | May 16, 2021 |
| ASUSTek    | X550LC                      | [23a000c11b](https://linux-hardware.org/?probe=23a000c11b) | May 05, 2021 |
| ASUSTek    | X550LC                      | [d50b1f77d7](https://linux-hardware.org/?probe=d50b1f77d7) | May 05, 2021 |
| Toshiba    | Satellite L35               | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| HP         | 14                          | [9d65301476](https://linux-hardware.org/?probe=9d65301476) | Apr 09, 2021 |
| Lenovo     | IdeaPad S145-15IWL 81MV     | [14e58f968d](https://linux-hardware.org/?probe=14e58f968d) | Apr 07, 2021 |
| Toshiba    | Satellite C655D             | [1959880e8f](https://linux-hardware.org/?probe=1959880e8f) | Mar 28, 2021 |
| Dell       | Latitude E5470              | [6ade45ee37](https://linux-hardware.org/?probe=6ade45ee37) | Mar 21, 2021 |
| Lenovo     | V310-14ISK 80SX             | [529bb59872](https://linux-hardware.org/?probe=529bb59872) | Mar 12, 2021 |
| Toshiba    | Satellite A665              | [23143ad7ae](https://linux-hardware.org/?probe=23143ad7ae) | Mar 07, 2021 |
| Lenovo     | IdeaPad S145-14IWL 81MU     | [b2e0735680](https://linux-hardware.org/?probe=b2e0735680) | Feb 28, 2021 |
| MSI        | Prestige 14 A10SC           | [26f40cdcba](https://linux-hardware.org/?probe=26f40cdcba) | Feb 25, 2021 |
| HP         | ProBook 5330m               | [4a66a57a41](https://linux-hardware.org/?probe=4a66a57a41) | Feb 23, 2021 |
| Razer      | Blade                       | [58fcda1ac4](https://linux-hardware.org/?probe=58fcda1ac4) | Feb 18, 2021 |
| ASUSTek    | N56JN                       | [02008fdd48](https://linux-hardware.org/?probe=02008fdd48) | Jan 31, 2021 |
| Acer       | Aspire V5-471               | [3c0bc82dde](https://linux-hardware.org/?probe=3c0bc82dde) | Jan 16, 2021 |
| Lenovo     | V330-15IKB 81AX             | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| HP         | Pavilion dv7                | [7591424ea2](https://linux-hardware.org/?probe=7591424ea2) | Jan 06, 2021 |
| HP         | Pavilion dv7                | [d660b968a4](https://linux-hardware.org/?probe=d660b968a4) | Jan 06, 2021 |
| Dell       | Inspiron 14-3467            | [fe678ae6f5](https://linux-hardware.org/?probe=fe678ae6f5) | Jan 04, 2021 |
| Dell       | G5 5505                     | [156236cc47](https://linux-hardware.org/?probe=156236cc47) | Dec 30, 2020 |
| Dell       | Latitude E5470              | [f6a3bc1097](https://linux-hardware.org/?probe=f6a3bc1097) | Dec 28, 2020 |
| HP         | Pavilion Notebook           | [033a1ff3cd](https://linux-hardware.org/?probe=033a1ff3cd) | Dec 07, 2020 |
| ASUSTek    | N56JN                       | [776cb81132](https://linux-hardware.org/?probe=776cb81132) | Nov 25, 2020 |
| ASUSTek    | N56JN                       | [e14774acd5](https://linux-hardware.org/?probe=e14774acd5) | Nov 25, 2020 |
| HP         | 14                          | [918fb071c2](https://linux-hardware.org/?probe=918fb071c2) | Nov 22, 2020 |
| Dell       | Latitude 3440               | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP         | ProBook 440 G5              | [07ac3c5495](https://linux-hardware.org/?probe=07ac3c5495) | Oct 07, 2020 |
| HP         | ProBook 440 G5              | [123eb500e2](https://linux-hardware.org/?probe=123eb500e2) | Oct 06, 2020 |
| Lenovo     | IdeaPad S540-14API 81NH     | [735aea26c5](https://linux-hardware.org/?probe=735aea26c5) | Sep 28, 2020 |
| HP         | 240 G7                      | [2507cc1bc7](https://linux-hardware.org/?probe=2507cc1bc7) | Sep 28, 2020 |
| Lenovo     | ThinkPad T470 20HES0JQ00    | [4235f1fc42](https://linux-hardware.org/?probe=4235f1fc42) | Sep 20, 2020 |
| Acer       | Nitro AN515-54              | [60efe004ff](https://linux-hardware.org/?probe=60efe004ff) | Sep 19, 2020 |
| Lenovo     | Legion Y540-15IRH 81SX      | [123ba2dd21](https://linux-hardware.org/?probe=123ba2dd21) | Sep 15, 2020 |
| Lenovo     | Legion Y540-15IRH-PG0 81... | [e193207a8f](https://linux-hardware.org/?probe=e193207a8f) | Sep 14, 2020 |
| Lenovo     | IdeaPad S540-14API 81NH     | [d043bf1b42](https://linux-hardware.org/?probe=d043bf1b42) | Sep 06, 2020 |
| Lenovo     | ThinkPad T430 2349LRS       | [d886cd5c31](https://linux-hardware.org/?probe=d886cd5c31) | Sep 05, 2020 |
| Lenovo     | ThinkPad T430 2349LRS       | [38284d9848](https://linux-hardware.org/?probe=38284d9848) | Sep 05, 2020 |
| Lenovo     | V310-15ISK 80SY             | [fc06b19016](https://linux-hardware.org/?probe=fc06b19016) | Sep 05, 2020 |
| Lenovo     | IdeaPad S540-14API 81NH     | [395b3e9836](https://linux-hardware.org/?probe=395b3e9836) | Sep 05, 2020 |
| Lenovo     | ThinkPad T430s 23539KU      | [2f700d4f41](https://linux-hardware.org/?probe=2f700d4f41) | Sep 03, 2020 |
| Lenovo     | G475 20080                  | [c97ad59308](https://linux-hardware.org/?probe=c97ad59308) | Aug 26, 2020 |
| Acer       | Aspire A515-52G             | [86a890eb18](https://linux-hardware.org/?probe=86a890eb18) | Aug 23, 2020 |
| Acer       | Aspire A515-52G             | [5034bf6bc3](https://linux-hardware.org/?probe=5034bf6bc3) | Aug 23, 2020 |
| Toshiba    | Satellite C845              | [7e218cb089](https://linux-hardware.org/?probe=7e218cb089) | Aug 22, 2020 |
| ASUSTek    | VivoBook_ASUS Laptop X50... | [26fe839699](https://linux-hardware.org/?probe=26fe839699) | Aug 14, 2020 |
| ASUSTek    | VivoBook_ASUS Laptop X50... | [55d2d92173](https://linux-hardware.org/?probe=55d2d92173) | Aug 14, 2020 |
| Lenovo     | ThinkPad P50 20EQA09900     | [4360f8c6a6](https://linux-hardware.org/?probe=4360f8c6a6) | Aug 12, 2020 |
| Lenovo     | ThinkPad P50 20EQA09900     | [76f4cf6487](https://linux-hardware.org/?probe=76f4cf6487) | Aug 12, 2020 |
| Toshiba    | Satellite L45-B             | [ce51a04f5d](https://linux-hardware.org/?probe=ce51a04f5d) | Aug 01, 2020 |
| Lenovo     | ThinkPad T60 1953D9U        | [45c01e0aca](https://linux-hardware.org/?probe=45c01e0aca) | Jul 30, 2020 |
| HP         | 245 G3                      | [044b206096](https://linux-hardware.org/?probe=044b206096) | Jul 26, 2020 |
| Lenovo     | G480 20149                  | [7fdfad1fc4](https://linux-hardware.org/?probe=7fdfad1fc4) | Jul 11, 2020 |
| ASUSTek    | VivoBook 15_ASUS Laptop ... | [f0ed82358a](https://linux-hardware.org/?probe=f0ed82358a) | Jul 05, 2020 |
| Lenovo     | G480 20149                  | [c9d75e29d3](https://linux-hardware.org/?probe=c9d75e29d3) | Jun 30, 2020 |
| HP         | ProBook 645 G4              | [2fb2b6ad63](https://linux-hardware.org/?probe=2fb2b6ad63) | Jun 22, 2020 |
| HP         | Pavilion Laptop 15-cw1xx... | [844f7b115e](https://linux-hardware.org/?probe=844f7b115e) | Jun 21, 2020 |
| HP         | ProBook 645 G4              | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| ASUSTek    | X540LA                      | [333139a886](https://linux-hardware.org/?probe=333139a886) | Jun 17, 2020 |
| HP         | ProBook 645 G4              | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| Toshiba    | Satellite L855              | [adbdc1e191](https://linux-hardware.org/?probe=adbdc1e191) | Jun 13, 2020 |
| ASUSTek    | VivoBook 15_ASUS Laptop ... | [97237c08ac](https://linux-hardware.org/?probe=97237c08ac) | Jun 11, 2020 |
| Apple      | MacBookPro9,2               | [371c5ccd5a](https://linux-hardware.org/?probe=371c5ccd5a) | May 31, 2020 |
| HP         | ENVY 15                     | [9075368552](https://linux-hardware.org/?probe=9075368552) | May 29, 2020 |
| Lenovo     | G50-70 20351                | [fb33cd7cef](https://linux-hardware.org/?probe=fb33cd7cef) | May 26, 2020 |
| HP         | EliteBook 840 G6            | [07829f089a](https://linux-hardware.org/?probe=07829f089a) | May 24, 2020 |
| HP         | ENVY 15                     | [afcc7af453](https://linux-hardware.org/?probe=afcc7af453) | May 23, 2020 |
| Unknown    | Unknown                     | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Unknown    | Unknown                     | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Dell       | Precision M4600             | [7060267281](https://linux-hardware.org/?probe=7060267281) | May 08, 2020 |
| HP         | Pavilion Sleekbook 14 PC    | [c513103ac9](https://linux-hardware.org/?probe=c513103ac9) | May 05, 2020 |
| HP         | 450                         | [22b90eb634](https://linux-hardware.org/?probe=22b90eb634) | May 02, 2020 |
| HP         | 450                         | [0da93b6fce](https://linux-hardware.org/?probe=0da93b6fce) | May 02, 2020 |
| Dell       | System XPS L502X            | [939683d725](https://linux-hardware.org/?probe=939683d725) | Apr 27, 2020 |
| Dell       | System XPS L502X            | [c893f3f105](https://linux-hardware.org/?probe=c893f3f105) | Apr 24, 2020 |
| HP         | Pavilion Laptop 15-cs0xx... | [97261529e7](https://linux-hardware.org/?probe=97261529e7) | Apr 21, 2020 |
| HP         | Pavilion Laptop 15-cs0xx... | [babdfebf40](https://linux-hardware.org/?probe=babdfebf40) | Apr 17, 2020 |
| Lenovo     | Yoga 2 11 20332             | [bbd3b573e1](https://linux-hardware.org/?probe=bbd3b573e1) | Apr 05, 2020 |
| Lenovo     | Yoga 2 11 20332             | [51c0fd8c5c](https://linux-hardware.org/?probe=51c0fd8c5c) | Apr 05, 2020 |
| Toshiba    | NB505                       | [934ebfe06b](https://linux-hardware.org/?probe=934ebfe06b) | Apr 05, 2020 |
| Samsung    | 300E5EV/300E4EV/270E5EV/... | [b112c2d6c6](https://linux-hardware.org/?probe=b112c2d6c6) | Mar 30, 2020 |
| Samsung    | 300E5EV/300E4EV/270E5EV/... | [7dee8ed61e](https://linux-hardware.org/?probe=7dee8ed61e) | Mar 26, 2020 |
| Samsung    | 300E5EV/300E4EV/270E5EV/... | [e274c73209](https://linux-hardware.org/?probe=e274c73209) | Mar 23, 2020 |
| Sony       | SVF15A17CLB                 | [6f9e42f276](https://linux-hardware.org/?probe=6f9e42f276) | Mar 22, 2020 |
| Lenovo     | V310-15ISK 80SY             | [88cf0450ac](https://linux-hardware.org/?probe=88cf0450ac) | Mar 15, 2020 |
| Dell       | Inspiron 5567               | [e598212cee](https://linux-hardware.org/?probe=e598212cee) | Feb 28, 2020 |
| HP         | Pavilion Gaming Laptop 1... | [2eebfcd5e9](https://linux-hardware.org/?probe=2eebfcd5e9) | Feb 27, 2020 |
| HP         | Pavilion Gaming Laptop 1... | [1335c3693b](https://linux-hardware.org/?probe=1335c3693b) | Feb 27, 2020 |
| Lenovo     | IdeaPad 330-15ARR 81D2      | [9344a74aa9](https://linux-hardware.org/?probe=9344a74aa9) | Feb 26, 2020 |
| Lenovo     | IdeaPad 330-15ARR 81D2      | [b253180703](https://linux-hardware.org/?probe=b253180703) | Feb 20, 2020 |
| Lenovo     | IdeaPad 330-15ARR 81D2      | [ad43873fae](https://linux-hardware.org/?probe=ad43873fae) | Feb 19, 2020 |
| Toshiba    | QOSMIO X775                 | [6abcb623e3](https://linux-hardware.org/?probe=6abcb623e3) | Feb 02, 2020 |
| Toshiba    | QOSMIO X775                 | [a2cf60ec44](https://linux-hardware.org/?probe=a2cf60ec44) | Feb 02, 2020 |
| Acer       | Aspire ES1-572              | [8bc74bd7fb](https://linux-hardware.org/?probe=8bc74bd7fb) | Dec 06, 2019 |
| Unknown    | Unknown                     | [cd4af41624](https://linux-hardware.org/?probe=cd4af41624) | Nov 30, 2019 |
| HP         | Pavilion g4                 | [cb1f2e06e7](https://linux-hardware.org/?probe=cb1f2e06e7) | Nov 28, 2019 |
| Dell       | Latitude 5580               | [7abf5fbce7](https://linux-hardware.org/?probe=7abf5fbce7) | Nov 21, 2019 |
| Dell       | Latitude 5580               | [521a1d30b6](https://linux-hardware.org/?probe=521a1d30b6) | Nov 21, 2019 |
| Lenovo     | Y70-70 Touch 80DU           | [dfa431bef9](https://linux-hardware.org/?probe=dfa431bef9) | Nov 13, 2019 |
| Toshiba    | Satellite C55-B             | [ef97116a29](https://linux-hardware.org/?probe=ef97116a29) | Nov 12, 2019 |
| Lenovo     | V330-15IKB 81AX             | [d0612d575f](https://linux-hardware.org/?probe=d0612d575f) | Nov 04, 2019 |
| Dell       | Inspiron 3443               | [daa04d519c](https://linux-hardware.org/?probe=daa04d519c) | Oct 15, 2019 |
| Sony       | VPCEC2JFX                   | [ad30a52539](https://linux-hardware.org/?probe=ad30a52539) | Oct 03, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [e486c2c05f](https://linux-hardware.org/?probe=e486c2c05f) | Sep 12, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [b09160e7cf](https://linux-hardware.org/?probe=b09160e7cf) | Sep 10, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [333fbc5a3b](https://linux-hardware.org/?probe=333fbc5a3b) | Aug 16, 2019 |
| Sony       | VPCEC2JFX                   | [f28ba85f16](https://linux-hardware.org/?probe=f28ba85f16) | Aug 04, 2019 |
| Acer       | Aspire ES1-572              | [432212e4c9](https://linux-hardware.org/?probe=432212e4c9) | Jul 31, 2019 |
| Acer       | Aspire ES1-572              | [8783b0d26c](https://linux-hardware.org/?probe=8783b0d26c) | Jul 31, 2019 |
| HP         | ProBook 440 G4              | [b0ae12ca81](https://linux-hardware.org/?probe=b0ae12ca81) | Jun 27, 2019 |
| Toshiba    | Satellite P755              | [8eaca3c3df](https://linux-hardware.org/?probe=8eaca3c3df) | Jun 13, 2019 |
| HP         | ProBook 645 G4              | [f2f88aaa9d](https://linux-hardware.org/?probe=f2f88aaa9d) | May 24, 2019 |
| HP         | ProBook 645 G4              | [049bd45822](https://linux-hardware.org/?probe=049bd45822) | May 24, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [cdf8203e8f](https://linux-hardware.org/?probe=cdf8203e8f) | Apr 24, 2019 |
| Lenovo     | B50-80 80EW                 | [275d0c887d](https://linux-hardware.org/?probe=275d0c887d) | Dec 28, 2018 |
| Lenovo     | B50-80 80EW                 | [603e6d3da4](https://linux-hardware.org/?probe=603e6d3da4) | Dec 28, 2018 |
| HP         | 1000                        | [9bf9fc957a](https://linux-hardware.org/?probe=9bf9fc957a) | Sep 04, 2018 |
| HP         | 1000                        | [684f6b1db8](https://linux-hardware.org/?probe=684f6b1db8) | Jan 30, 2018 |
| Sony       | VGN-FW170J                  | [2ac505bc7b](https://linux-hardware.org/?probe=2ac505bc7b) | Jan 04, 2018 |
| HP         | 1000                        | [0e00b75fea](https://linux-hardware.org/?probe=0e00b75fea) | Dec 19, 2017 |
| Sony       | VGN-FW170J                  | [d2b4cdb291](https://linux-hardware.org/?probe=d2b4cdb291) | Nov 21, 2017 |
| Acer       | Aspire S3                   | [db53fb01bd](https://linux-hardware.org/?probe=db53fb01bd) | May 26, 2017 |
| Acer       | Aspire S3                   | [a3cfad5de1](https://linux-hardware.org/?probe=a3cfad5de1) | May 26, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 32        | 14.68%  |
| OpenMandriva 4.3             | 10        | 4.59%   |
| Ubuntu 18.04                 | 9         | 4.13%   |
| Ubuntu 22.04                 | 8         | 3.67%   |
| Arch Rolling                 | 7         | 3.21%   |
| Zorin 15                     | 6         | 2.75%   |
| Linux Mint 20.3              | 6         | 2.75%   |
| Ubuntu 19.10                 | 5         | 2.29%   |
| Manjaro                      | 5         | 2.29%   |
| Fedora 37                    | 5         | 2.29%   |
| Arch                         | 5         | 2.29%   |
| Xubuntu 20.04                | 4         | 1.83%   |
| Ubuntu 21.04                 | 4         | 1.83%   |
| Pop!_OS 21.10                | 4         | 1.83%   |
| OpenMandriva 23.01           | 4         | 1.83%   |
| Debian 11                    | 4         | 1.83%   |
| Ubuntu 19.04                 | 3         | 1.38%   |
| Pop!_OS 20.10                | 3         | 1.38%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.38%   |
| OpenMandriva 4.2             | 3         | 1.38%   |
| Manjaro 20.1                 | 3         | 1.38%   |
| Linux Mint 21.1              | 3         | 1.38%   |
| KDE neon 20.04               | 3         | 1.38%   |
| Elementary 5.1.7             | 3         | 1.38%   |
| Debian 10                    | 3         | 1.38%   |
| ROSA R9                      | 2         | 0.92%   |
| ROSA R10                     | 2         | 0.92%   |
| ROSA 12.3                    | 2         | 0.92%   |
| ROSA 12.2                    | 2         | 0.92%   |
| Pop!_OS 22.04                | 2         | 0.92%   |
| Pop!_OS 20.04                | 2         | 0.92%   |
| OpenMandriva 4.90            | 2         | 0.92%   |
| OpenMandriva 23.03           | 2         | 0.92%   |
| Linux Mint 20                | 2         | 0.92%   |
| Kubuntu 20.04                | 2         | 0.92%   |
| Fedora 35                    | 2         | 0.92%   |
| Fedora 34                    | 2         | 0.92%   |
| Fedora 33                    | 2         | 0.92%   |
| Fedora 32                    | 2         | 0.92%   |
| Debian                       | 2         | 0.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 61        | 28.64%  |
| OpenMandriva  | 21        | 9.86%   |
| Linux Mint    | 14        | 6.57%   |
| Fedora        | 14        | 6.57%   |
| Arch          | 13        | 6.1%    |
| Pop!_OS       | 12        | 5.63%   |
| Manjaro       | 12        | 5.63%   |
| Debian        | 10        | 4.69%   |
| ROSA          | 8         | 3.76%   |
| Zorin         | 7         | 3.29%   |
| Xubuntu       | 4         | 1.88%   |
| KDE neon      | 4         | 1.88%   |
| Elementary    | 4         | 1.88%   |
| openSUSE      | 3         | 1.41%   |
| Endless       | 3         | 1.41%   |
| Ubuntu MATE   | 2         | 0.94%   |
| Lubuntu       | 2         | 0.94%   |
| Kubuntu       | 2         | 0.94%   |
| Kali          | 2         | 0.94%   |
| CentOS        | 2         | 0.94%   |
| ArcoLinux     | 2         | 0.94%   |
| Void Linux    | 1         | 0.47%   |
| Ubuntu Unity  | 1         | 0.47%   |
| Ubuntu Budgie | 1         | 0.47%   |
| SteamOS       | 1         | 0.47%   |
| Peppermint    | 1         | 0.47%   |
| Parrot        | 1         | 0.47%   |
| MX            | 1         | 0.47%   |
| LMDE          | 1         | 0.47%   |
| Laxer OS      | 1         | 0.47%   |
| Clear Linux   | 1         | 0.47%   |
| Artix         | 1         | 0.47%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 10        | 4.22%   |
| 5.13.0-40-generic               | 5         | 2.11%   |
| 5.4.0-42-generic                | 4         | 1.69%   |
| 5.4.0-26-generic                | 3         | 1.27%   |
| 5.3.0-40-generic                | 3         | 1.27%   |
| 5.13.0-51-generic               | 3         | 1.27%   |
| 5.11.0-25-generic               | 3         | 1.27%   |
| 5.10.0-13-amd64                 | 3         | 1.27%   |
| 6.1.4-desktop-1omv2301          | 2         | 0.84%   |
| 6.1.1-desktop-1omv2290          | 2         | 0.84%   |
| 5.8.0-44-generic                | 2         | 0.84%   |
| 5.4.0-7642-generic              | 2         | 0.84%   |
| 5.4.0-66-generic                | 2         | 0.84%   |
| 5.4.0-65-generic                | 2         | 0.84%   |
| 5.4.0-58-generic                | 2         | 0.84%   |
| 5.4.0-54-generic                | 2         | 0.84%   |
| 5.4.0-39-generic                | 2         | 0.84%   |
| 5.4.0-33-generic                | 2         | 0.84%   |
| 5.4.0-28-generic                | 2         | 0.84%   |
| 5.4.0-109-generic               | 2         | 0.84%   |
| 5.3.0-42-generic                | 2         | 0.84%   |
| 5.3.0-23-generic                | 2         | 0.84%   |
| 5.18.12-desktop-3omv4090        | 2         | 0.84%   |
| 5.17.5-arch1-1                  | 2         | 0.84%   |
| 5.16.19-76051619-generic        | 2         | 0.84%   |
| 5.15.49-1-lts                   | 2         | 0.84%   |
| 5.15.0-58-generic               | 2         | 0.84%   |
| 5.15.0-57-generic               | 2         | 0.84%   |
| 5.15.0-52-generic               | 2         | 0.84%   |
| 5.15.0-25-generic               | 2         | 0.84%   |
| 5.13.0-30-generic               | 2         | 0.84%   |
| 5.11.0-7614-generic             | 2         | 0.84%   |
| 5.10.14-desktop-1omv4002        | 2         | 0.84%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.84%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 0.84%   |
| 6.2.6-desktop-1omv2390          | 1         | 0.42%   |
| 6.2.2-desktop-1omv2390          | 1         | 0.42%   |
| 6.1.9-zen1-1-zen                | 1         | 0.42%   |
| 6.1.9-1-MANJARO                 | 1         | 0.42%   |
| 6.1.8-1252.native               | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 16.67%  |
| 5.15.0  | 16        | 7.02%   |
| 5.11.0  | 14        | 6.14%   |
| 5.13.0  | 13        | 5.7%    |
| 5.3.0   | 12        | 5.26%   |
| 5.16.7  | 10        | 4.39%   |
| 5.8.0   | 7         | 3.07%   |
| 5.0.0   | 7         | 3.07%   |
| 4.15.0  | 7         | 3.07%   |
| 5.10.0  | 6         | 2.63%   |
| 4.18.0  | 6         | 2.63%   |
| 6.0.0   | 3         | 1.32%   |
| 5.19.0  | 3         | 1.32%   |
| 5.17.5  | 3         | 1.32%   |
| 4.9.60  | 3         | 1.32%   |
| 6.1.9   | 2         | 0.88%   |
| 6.1.4   | 2         | 0.88%   |
| 6.1.11  | 2         | 0.88%   |
| 6.1.1   | 2         | 0.88%   |
| 6.0.7   | 2         | 0.88%   |
| 6.0.15  | 2         | 0.88%   |
| 5.18.12 | 2         | 0.88%   |
| 5.16.19 | 2         | 0.88%   |
| 5.15.49 | 2         | 0.88%   |
| 5.12.10 | 2         | 0.88%   |
| 5.10.14 | 2         | 0.88%   |
| 4.9.20  | 2         | 0.88%   |
| 4.19.0  | 2         | 0.88%   |
| 6.2.6   | 1         | 0.44%   |
| 6.2.2   | 1         | 0.44%   |
| 6.1.8   | 1         | 0.44%   |
| 6.1.12  | 1         | 0.44%   |
| 6.0.8   | 1         | 0.44%   |
| 6.0.6   | 1         | 0.44%   |
| 6.0.2   | 1         | 0.44%   |
| 6.0.11  | 1         | 0.44%   |
| 6.0.10  | 1         | 0.44%   |
| 5.9.16  | 1         | 0.44%   |
| 5.9.11  | 1         | 0.44%   |
| 5.8.6   | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 18.3%   |
| 5.15    | 27        | 12.05%  |
| 5.11    | 15        | 6.7%    |
| 5.13    | 14        | 6.25%   |
| 5.16    | 13        | 5.8%    |
| 5.10    | 13        | 5.8%    |
| 5.3     | 12        | 5.36%   |
| 6.0     | 11        | 4.91%   |
| 6.1     | 10        | 4.46%   |
| 5.8     | 10        | 4.46%   |
| 5.17    | 7         | 3.13%   |
| 5.0     | 7         | 3.13%   |
| 4.15    | 7         | 3.13%   |
| 4.18    | 6         | 2.68%   |
| 5.19    | 5         | 2.23%   |
| 5.12    | 4         | 1.79%   |
| 4.9     | 4         | 1.79%   |
| 5.18    | 3         | 1.34%   |
| 5.14    | 3         | 1.34%   |
| 6.2     | 2         | 0.89%   |
| 5.9     | 2         | 0.89%   |
| 5.7     | 2         | 0.89%   |
| 5.6     | 2         | 0.89%   |
| 4.19    | 2         | 0.89%   |
| 5.1     | 1         | 0.45%   |
| 4.16    | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 196       | 96.08%  |
| i686   | 8         | 3.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 98        | 46.45%  |
| KDE5            | 36        | 17.06%  |
| XFCE            | 18        | 8.53%   |
| Unknown         | 15        | 7.11%   |
| X-Cinnamon      | 11        | 5.21%   |
| MATE            | 6         | 2.84%   |
| KDE             | 6         | 2.84%   |
| Pantheon        | 4         | 1.9%    |
| KDE4            | 4         | 1.9%    |
| LXQt            | 3         | 1.42%   |
| i3              | 3         | 1.42%   |
| LXDE            | 2         | 0.95%   |
| Budgie          | 2         | 0.95%   |
| Unity           | 1         | 0.47%   |
| spectrwm        | 1         | 0.47%   |
| GNOME Flashback | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 159       | 75%     |
| Wayland | 38        | 17.92%  |
| Unknown | 14        | 6.6%    |
| Tty     | 1         | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 97        | 45.97%  |
| GDM     | 38        | 18.01%  |
| SDDM    | 31        | 14.69%  |
| LightDM | 23        | 10.9%   |
| GDM3    | 15        | 7.11%   |
| KDM     | 4         | 1.9%    |
| TDM     | 2         | 0.95%   |
| XDM     | 1         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_PE   | 100       | 47.85%  |
| en_US   | 55        | 26.32%  |
| es_ES   | 18        | 8.61%   |
| Unknown | 16        | 7.66%   |
| es_MX   | 5         | 2.39%   |
| C       | 3         | 1.44%   |
| it_IT   | 2         | 0.96%   |
| fr_FR   | 2         | 0.96%   |
| en_GB   | 2         | 0.96%   |
| ca_ES   | 2         | 0.96%   |
| es_VE   | 1         | 0.48%   |
| es_CO   | 1         | 0.48%   |
| en_NZ   | 1         | 0.48%   |
| Default | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 114       | 55.07%  |
| BIOS | 93        | 44.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 160       | 76.56%  |
| Overlay | 19        | 9.09%   |
| Btrfs   | 16        | 7.66%   |
| Unknown | 7         | 3.35%   |
| Xfs     | 6         | 2.87%   |
| Ext3    | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 109       | 52.66%  |
| GPT     | 78        | 37.68%  |
| MBR     | 20        | 9.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 182       | 87.92%  |
| Yes       | 25        | 12.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 58.17%  |
| Yes       | 87        | 41.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 55        | 27.09%  |
| Hewlett-Packard     | 55        | 27.09%  |
| ASUSTek Computer    | 24        | 11.82%  |
| Dell                | 21        | 10.34%  |
| Acer                | 15        | 7.39%   |
| Toshiba             | 14        | 6.9%    |
| Sony                | 4         | 1.97%   |
| MSI                 | 3         | 1.48%   |
| HUAWEI              | 3         | 1.48%   |
| Advance             | 2         | 0.99%   |
| Samsung Electronics | 1         | 0.49%   |
| Razer               | 1         | 0.49%   |
| efirstview          | 1         | 0.49%   |
| Compal              | 1         | 0.49%   |
| Chuwi               | 1         | 0.49%   |
| Apple               | 1         | 0.49%   |
| Unknown             | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo V330-15IKB 81AX                                | 4         | 1.97%   |
| HP Pavilion Laptop 15-cw1xxx                          | 4         | 1.97%   |
| Lenovo V310-15ISK 80SY                                | 3         | 1.48%   |
| HP 14                                                 | 3         | 1.48%   |
| Lenovo IdeaPad S540-14API 81NH                        | 2         | 0.99%   |
| Lenovo IdeaPad S145-15IWL 81MV                        | 2         | 0.99%   |
| Lenovo IdeaPad 330S-14IKB 81F4                        | 2         | 0.99%   |
| Lenovo IdeaPad 3 14ADA05 81W0                         | 2         | 0.99%   |
| HP ProBook 645 G4                                     | 2         | 0.99%   |
| HP Notebook                                           | 2         | 0.99%   |
| HP Laptop 15-ef1xxx                                   | 2         | 0.99%   |
| HP 450                                                | 2         | 0.99%   |
| Dell XPS 13 9360                                      | 2         | 0.99%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA                | 2         | 0.99%   |
| ASUS VivoBook 15_ASUS Laptop X507UBR                  | 2         | 0.99%   |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV              | 2         | 0.99%   |
| Toshiba Satellite P755                                | 1         | 0.49%   |
| Toshiba Satellite P300                                | 1         | 0.49%   |
| Toshiba Satellite L855                                | 1         | 0.49%   |
| Toshiba Satellite L45-B                               | 1         | 0.49%   |
| Toshiba Satellite L35                                 | 1         | 0.49%   |
| Toshiba Satellite E205                                | 1         | 0.49%   |
| Toshiba Satellite C845                                | 1         | 0.49%   |
| Toshiba Satellite C655D                               | 1         | 0.49%   |
| Toshiba Satellite C645                                | 1         | 0.49%   |
| Toshiba Satellite C55-B                               | 1         | 0.49%   |
| Toshiba Satellite C45-A                               | 1         | 0.49%   |
| Toshiba Satellite A665                                | 1         | 0.49%   |
| Toshiba QOSMIO X775                                   | 1         | 0.49%   |
| Toshiba NB505                                         | 1         | 0.49%   |
| Sony VPCEC2JFX                                        | 1         | 0.49%   |
| Sony VGN-FW56M                                        | 1         | 0.49%   |
| Sony VGN-FW170J                                       | 1         | 0.49%   |
| Sony SVF15A17CLB                                      | 1         | 0.49%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.49%   |
| Razer Blade                                           | 1         | 0.49%   |
| MSI Prestige 14 A10SC                                 | 1         | 0.49%   |
| MSI Modern 15 A5M                                     | 1         | 0.49%   |
| MSI GL65 Leopard 10SEK                                | 1         | 0.49%   |
| Lenovo Yoga 2 11 20332                                | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 16        | 7.88%   |
| Lenovo IdeaPad    | 16        | 7.88%   |
| HP Pavilion       | 15        | 7.39%   |
| Acer Aspire       | 13        | 6.4%    |
| Toshiba Satellite | 12        | 5.91%   |
| ASUS VivoBook     | 9         | 4.43%   |
| HP ProBook        | 8         | 3.94%   |
| Dell Latitude     | 8         | 3.94%   |
| HP Laptop         | 7         | 3.45%   |
| Dell Inspiron     | 7         | 3.45%   |
| Lenovo V330-15IKB | 4         | 1.97%   |
| Lenovo Legion     | 4         | 1.97%   |
| Lenovo V310-15ISK | 3         | 1.48%   |
| HP 14             | 3         | 1.48%   |
| ASUS ASUS         | 3         | 1.48%   |
| HP ZBook          | 2         | 0.99%   |
| HP Notebook       | 2         | 0.99%   |
| HP ENVY           | 2         | 0.99%   |
| HP EliteBook      | 2         | 0.99%   |
| HP Compaq         | 2         | 0.99%   |
| HP 450            | 2         | 0.99%   |
| HP 255            | 2         | 0.99%   |
| HP 250            | 2         | 0.99%   |
| HP 240            | 2         | 0.99%   |
| Dell XPS          | 2         | 0.99%   |
| ASUS ROG          | 2         | 0.99%   |
| Toshiba QOSMIO    | 1         | 0.49%   |
| Toshiba NB505     | 1         | 0.49%   |
| Sony VPCEC2JFX    | 1         | 0.49%   |
| Sony VGN-FW56M    | 1         | 0.49%   |
| Sony VGN-FW170J   | 1         | 0.49%   |
| Sony SVF15A17CLB  | 1         | 0.49%   |
| Samsung 300E5EV   | 1         | 0.49%   |
| Razer Blade       | 1         | 0.49%   |
| MSI Prestige      | 1         | 0.49%   |
| MSI Modern        | 1         | 0.49%   |
| MSI GL65          | 1         | 0.49%   |
| Lenovo Yoga       | 1         | 0.49%   |
| Lenovo Y70-70     | 1         | 0.49%   |
| Lenovo V310-14ISK | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 25        | 12.32%  |
| 2019 | 22        | 10.84%  |
| 2018 | 20        | 9.85%   |
| 2017 | 18        | 8.87%   |
| 2012 | 18        | 8.87%   |
| 2016 | 17        | 8.37%   |
| 2014 | 17        | 8.37%   |
| 2011 | 15        | 7.39%   |
| 2021 | 14        | 6.9%    |
| 2013 | 13        | 6.4%    |
| 2015 | 6         | 2.96%   |
| 2010 | 6         | 2.96%   |
| 2008 | 4         | 1.97%   |
| 2009 | 3         | 1.48%   |
| 2007 | 3         | 1.48%   |
| 2022 | 1         | 0.49%   |
| 2006 | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 203       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 184       | 90.2%   |
| Enabled  | 20        | 9.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 203       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 63        | 30.14%  |
| 8.01-16.0   | 58        | 27.75%  |
| 3.01-4.0    | 39        | 18.66%  |
| 16.01-24.0  | 29        | 13.88%  |
| 1.01-2.0    | 8         | 3.83%   |
| 2.01-3.0    | 5         | 2.39%   |
| 32.01-64.0  | 3         | 1.44%   |
| 0.51-1.0    | 2         | 0.96%   |
| 24.01-32.0  | 1         | 0.48%   |
| 64.01-256.0 | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 73        | 32.59%  |
| 2.01-3.0  | 69        | 30.8%   |
| 4.01-8.0  | 32        | 14.29%  |
| 3.01-4.0  | 27        | 12.05%  |
| 0.51-1.0  | 14        | 6.25%   |
| 8.01-16.0 | 8         | 3.57%   |
| 0.01-0.5  | 1         | 0.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 150       | 73.17%  |
| 2      | 52        | 25.37%  |
| 3      | 2         | 0.98%   |
| 0      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 126       | 62.07%  |
| Yes       | 77        | 37.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 85.29%  |
| No        | 30        | 14.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 200       | 98.52%  |
| No        | 3         | 1.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 169       | 82.84%  |
| No        | 35        | 17.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Peru    | 203       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lima                  | 136       | 64.45%  |
| Arequipa              | 21        | 9.95%   |
| Trujillo              | 13        | 6.16%   |
| Piura                 | 6         | 2.84%   |
| Cusco                 | 5         | 2.37%   |
| Huancayo              | 4         | 1.9%    |
| Chiclayo              | 3         | 1.42%   |
| Tacna                 | 2         | 0.95%   |
| La Victoria           | 2         | 0.95%   |
| Ica                   | 2         | 0.95%   |
| Callao                | 2         | 0.95%   |
| San Vicente de Canete | 1         | 0.47%   |
| San Isidro            | 1         | 0.47%   |
| San Borja             | 1         | 0.47%   |
| Punta Colorada        | 1         | 0.47%   |
| Pisco                 | 1         | 0.47%   |
| Oxapampa              | 1         | 0.47%   |
| Moquegua              | 1         | 0.47%   |
| Juliaca               | 1         | 0.47%   |
| Iquitos               | 1         | 0.47%   |
| Distrito de Lima      | 1         | 0.47%   |
| Chincha Alta          | 1         | 0.47%   |
| Cajamarca             | 1         | 0.47%   |
| Barranco              | 1         | 0.47%   |
| Ayacucho              | 1         | 0.47%   |
| Abancay               | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba                        | 42        | 51     | 16.73%  |
| WDC                            | 41        | 47     | 16.33%  |
| Seagate                        | 36        | 42     | 14.34%  |
| Kingston                       | 27        | 33     | 10.76%  |
| Samsung Electronics            | 14        | 21     | 5.58%   |
| Sandisk                        | 11        | 14     | 4.38%   |
| Crucial                        | 9         | 11     | 3.59%   |
| Intel                          | 6         | 8      | 2.39%   |
| Unknown                        | 5         | 5      | 1.99%   |
| SK hynix                       | 5         | 8      | 1.99%   |
| Micron Technology              | 5         | 5      | 1.99%   |
| KIOXIA                         | 5         | 6      | 1.99%   |
| Hitachi                        | 5         | 7      | 1.99%   |
| HGST                           | 4         | 4      | 1.59%   |
| Hewlett-Packard                | 4         | 4      | 1.59%   |
| TO Exter                       | 3         | 6      | 1.2%    |
| LITEON                         | 3         | 3      | 1.2%    |
| Kingston Technology Company    | 2         | 2      | 0.8%    |
| Gigabyte Technology            | 2         | 2      | 0.8%    |
| China                          | 2         | 2      | 0.8%    |
| Unknown                        | 2         | 2      | 0.8%    |
| Union Memory (Shenzhen)        | 1         | 1      | 0.4%    |
| UMIS                           | 1         | 1      | 0.4%    |
| SSSTC                          | 1         | 1      | 0.4%    |
| Solid State Storage Technology | 1         | 1      | 0.4%    |
| Silicon Motion                 | 1         | 1      | 0.4%    |
| Phison Electronics             | 1         | 1      | 0.4%    |
| Phison                         | 1         | 1      | 0.4%    |
| Netac                          | 1         | 1      | 0.4%    |
| Micron/Crucial Technology      | 1         | 1      | 0.4%    |
| KingSpec                       | 1         | 1      | 0.4%    |
| ITHOO                          | 1         | 1      | 0.4%    |
| GLOWAY                         | 1         | 1      | 0.4%    |
| Fujitsu                        | 1         | 1      | 0.4%    |
| Dogfish                        | 1         | 1      | 0.4%    |
| Biwin Storage Technology       | 1         | 3      | 0.4%    |
| Apple                          | 1         | 1      | 0.4%    |
| ACASIS                         | 1         | 1      | 0.4%    |
| A-DATA Technology              | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 15        | 5.79%   |
| Kingston SA400S37240G 240GB SSD      | 11        | 4.25%   |
| Toshiba MQ04ABF100 1TB               | 9         | 3.47%   |
| Toshiba MQ01ABD100 1TB               | 9         | 3.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 6         | 2.32%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.93%   |
| WDC WD10JPCX-24UE4T0 1TB             | 4         | 1.54%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 1.54%   |
| Intel SSDPEKNU512GZ 512GB            | 4         | 1.54%   |
| WDC WD10SPZX-24Z10 1TB               | 3         | 1.16%   |
| TO Exter nal USB 3.0 1TB             | 3         | 1.16%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.16%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.16%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.16%   |
| HP SSD S700 500GB                    | 3         | 1.16%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.77%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.77%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.77%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.77%   |
| Unknown MMC Card  32GB               | 2         | 0.77%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.77%   |
| Toshiba MK2565GSXN 250GB             | 2         | 0.77%   |
| Toshiba HDWJ110 1TB                  | 2         | 0.77%   |
| Seagate ST9500325AS 500GB            | 2         | 0.77%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.77%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.77%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.77%   |
| SanDisk NVMe SSD Drive 1TB           | 2         | 0.77%   |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 2         | 0.77%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.77%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.77%   |
| Unknown                              | 2         | 0.77%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.39%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD     | 1         | 0.39%   |
| WDC WDS200T2B0A-00SM50 2TB SSD       | 1         | 0.39%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.39%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.39%   |
| WDC WD5000LPVT-24G33T1 500GB         | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 40        | 49     | 36.04%  |
| Seagate | 36        | 41     | 32.43%  |
| WDC     | 23        | 26     | 20.72%  |
| Hitachi | 5         | 7      | 4.5%    |
| HGST    | 4         | 4      | 3.6%    |
| Fujitsu | 1         | 1      | 0.9%    |
| Apple   | 1         | 1      | 0.9%    |
| ACASIS  | 1         | 1      | 0.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 24        | 28     | 30.77%  |
| WDC                 | 14        | 15     | 17.95%  |
| Crucial             | 8         | 9      | 10.26%  |
| SanDisk             | 5         | 7      | 6.41%   |
| Samsung Electronics | 4         | 4      | 5.13%   |
| Hewlett-Packard     | 4         | 4      | 5.13%   |
| TO Exter            | 3         | 6      | 3.85%   |
| LITEON              | 3         | 3      | 3.85%   |
| China               | 2         | 2      | 2.56%   |
| Toshiba             | 1         | 1      | 1.28%   |
| SSSTC               | 1         | 1      | 1.28%   |
| SK hynix            | 1         | 4      | 1.28%   |
| Seagate             | 1         | 1      | 1.28%   |
| Netac               | 1         | 1      | 1.28%   |
| KingSpec            | 1         | 1      | 1.28%   |
| GLOWAY              | 1         | 1      | 1.28%   |
| Gigabyte Technology | 1         | 1      | 1.28%   |
| Dogfish             | 1         | 1      | 1.28%   |
| A-DATA Technology   | 1         | 1      | 1.28%   |
| Unknown             | 1         | 1      | 1.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 110       | 130    | 45.64%  |
| SSD     | 70        | 92     | 29.05%  |
| NVMe    | 55        | 75     | 22.82%  |
| MMC     | 5         | 5      | 2.07%   |
| Unknown | 1         | 1      | 0.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 155       | 215    | 70.45%  |
| NVMe | 55        | 75     | 25%     |
| SAS  | 5         | 8      | 2.27%   |
| MMC  | 5         | 5      | 2.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 92        | 122    | 52.57%  |
| 0.51-1.0   | 81        | 98     | 46.29%  |
| 1.01-2.0   | 2         | 2      | 1.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 60        | 28.3%   |
| 501-1000       | 45        | 21.23%  |
| 251-500        | 44        | 20.75%  |
| 51-100         | 17        | 8.02%   |
| 21-50          | 15        | 7.08%   |
| 1-20           | 12        | 5.66%   |
| 1001-2000      | 11        | 5.19%   |
| More than 3000 | 3         | 1.42%   |
| 2001-3000      | 3         | 1.42%   |
| Unknown        | 2         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 82        | 37.96%  |
| 21-50          | 50        | 23.15%  |
| 101-250        | 27        | 12.5%   |
| 51-100         | 25        | 11.57%  |
| 251-500        | 15        | 6.94%   |
| 501-1000       | 11        | 5.09%   |
| 1001-2000      | 2         | 0.93%   |
| Unknown        | 2         | 0.93%   |
| More than 3000 | 1         | 0.46%   |
| 2001-3000      | 1         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD10JPCX-24UE4T0 1TB         | 2         | 2      | 9.09%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 1      | 4.55%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 1      | 4.55%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 4.55%   |
| Toshiba MQ01ABF050 500GB         | 1         | 1      | 4.55%   |
| Toshiba MK5065GSXN 500GB         | 1         | 1      | 4.55%   |
| Toshiba MK4058GSX 400GB          | 1         | 1      | 4.55%   |
| Toshiba MK2035GSS 200GB          | 1         | 1      | 4.55%   |
| Toshiba HDWJ110 1TB              | 1         | 1      | 4.55%   |
| SSSTC CVB-8D128-HP 128GB         | 1         | 1      | 4.55%   |
| Seagate ST9500325AS 500GB        | 1         | 1      | 4.55%   |
| Seagate ST9250315AS 250GB        | 1         | 1      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB  | 1         | 1      | 4.55%   |
| Seagate ST1000LM014-1EJ164 1TB   | 1         | 1      | 4.55%   |
| Kingston SA400S37480G 480GB SSD  | 1         | 1      | 4.55%   |
| Hitachi HTS725050A7E630 500GB    | 1         | 1      | 4.55%   |
| Hitachi HTS545050B9A300 500GB    | 1         | 1      | 4.55%   |
| Hitachi HTS545050A7E380 500GB    | 1         | 3      | 4.55%   |
| Hitachi HTS545032B9A302 320GB    | 1         | 1      | 4.55%   |
| HGST HTS721010A9E630 1TB         | 1         | 1      | 4.55%   |
| Hewlett-Packard SSD S700 500GB   | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| Toshiba         | 5         | 6      | 23.81%  |
| WDC             | 4         | 4      | 19.05%  |
| Seagate         | 4         | 4      | 19.05%  |
| Hitachi         | 4         | 6      | 19.05%  |
| SSSTC           | 1         | 1      | 4.76%   |
| Kingston        | 1         | 1      | 4.76%   |
| HGST            | 1         | 1      | 4.76%   |
| Hewlett-Packard | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 6      | 31.25%  |
| Seagate | 4         | 4      | 25%     |
| Hitachi | 4         | 6      | 25%     |
| WDC     | 2         | 2      | 12.5%   |
| HGST    | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 19     | 76.19%  |
| SSD  | 5         | 5      | 23.81%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK3252GSX 320GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 121       | 176    | 55.76%  |
| Works    | 75        | 101    | 34.56%  |
| Malfunc  | 20        | 24     | 9.22%   |
| Failed   | 1         | 2      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 148       | 64.63%  |
| AMD                              | 29        | 12.66%  |
| SanDisk                          | 12        | 5.24%   |
| Samsung Electronics              | 10        | 4.37%   |
| Micron Technology                | 5         | 2.18%   |
| KIOXIA                           | 5         | 2.18%   |
| Kingston Technology Company      | 5         | 2.18%   |
| SK hynix                         | 4         | 1.75%   |
| Phison Electronics               | 2         | 0.87%   |
| Micron/Crucial Technology        | 2         | 0.87%   |
| Union Memory (Shenzhen)          | 1         | 0.44%   |
| Toshiba America Info Systems     | 1         | 0.44%   |
| Solid State Storage Technology   | 1         | 0.44%   |
| Silicon Motion                   | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] | 1         | 0.44%   |
| INNOGRIT                         | 1         | 0.44%   |
| Biwin Storage Technology         | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 28        | 11.57%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 26        | 10.74%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 7.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 6.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 4.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 3.31%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 2.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 2.48%   |
| Micron NVMe Storage Controller                                                 | 5         | 2.07%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 2.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 1.65%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.65%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.65%   |
| Intel Non-Volatile memory controller                                           | 4         | 1.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.65%   |
| SK hynix BC511                                                                 | 3         | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.24%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.83%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.83%   |
| SanDisk NVMe Controller                                                        | 2         | 0.83%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.83%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.83%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.83%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.41%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.41%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.41%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 150       | 63.83%  |
| NVMe | 55        | 23.4%   |
| RAID | 23        | 9.79%   |
| IDE  | 7         | 2.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 162       | 79.8%   |
| AMD    | 41        | 20.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 9         | 4.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 6         | 2.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 6         | 2.96%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 6         | 2.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 2.46%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 5         | 2.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 4         | 1.97%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 4         | 1.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 4         | 1.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 4         | 1.97%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 4         | 1.97%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 3         | 1.48%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 3         | 1.48%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 3         | 1.48%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 3         | 1.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 0.99%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 0.99%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 2         | 0.99%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 0.99%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 2         | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 0.99%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 0.99%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 0.99%   |
| Intel Core i5-4200M CPU @ 2.50GHz               | 2         | 0.99%   |
| Intel Core i5-2450M CPU @ 2.50GHz               | 2         | 0.99%   |
| Intel Core i5 CPU M 480 @ 2.67GHz               | 2         | 0.99%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 2         | 0.99%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 2         | 0.99%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 0.99%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 0.99%   |
| Intel Core i3-2328M CPU @ 2.20GHz               | 2         | 0.99%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 0.99%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 2         | 0.99%   |
| Intel Celeron CPU 550 @ 2.00GHz                 | 2         | 0.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 0.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 0.99%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 2         | 0.99%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 2         | 0.99%   |
| AMD Ryzen 5 4500U with Radeon Graphics          | 2         | 0.99%   |
| AMD Athlon Silver 3050U with Radeon Graphics    | 2         | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 57        | 28.08%  |
| Intel Core i5      | 52        | 25.62%  |
| Intel Core i3      | 24        | 11.82%  |
| AMD Ryzen 5        | 13        | 6.4%    |
| Other              | 10        | 4.93%   |
| AMD Ryzen 7        | 10        | 4.93%   |
| Intel Celeron      | 7         | 3.45%   |
| Intel Atom         | 5         | 2.46%   |
| Intel Core 2 Duo   | 3         | 1.48%   |
| AMD A8             | 3         | 1.48%   |
| Intel Pentium      | 2         | 0.99%   |
| AMD Ryzen 9        | 2         | 0.99%   |
| AMD Ryzen 7 PRO    | 2         | 0.99%   |
| AMD Ryzen 3        | 2         | 0.99%   |
| AMD E1             | 2         | 0.99%   |
| AMD Athlon         | 2         | 0.99%   |
| Intel Xeon         | 1         | 0.49%   |
| Intel Pentium Dual | 1         | 0.49%   |
| Intel Genuine      | 1         | 0.49%   |
| Intel Celeron M    | 1         | 0.49%   |
| AMD E              | 1         | 0.49%   |
| AMD C-50           | 1         | 0.49%   |
| AMD A12            | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 99        | 48.77%  |
| 4       | 76        | 37.44%  |
| 8       | 10        | 4.93%   |
| 6       | 10        | 4.93%   |
| 1       | 6         | 2.96%   |
| 10      | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 203       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 172       | 84.73%  |
| 1       | 30        | 14.78%  |
| Unknown | 1         | 0.49%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 197       | 96.1%   |
| 64-bit         | 3         | 1.46%   |
| 32-bit         | 3         | 1.46%   |
| Unknown        | 2         | 0.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 18.66%  |
| 0x206a7    | 15        | 7.18%   |
| 0x306a9    | 12        | 5.74%   |
| 0x40651    | 11        | 5.26%   |
| 0x806ec    | 10        | 4.78%   |
| 0x806ea    | 10        | 4.78%   |
| 0x406e3    | 10        | 4.78%   |
| 0x806e9    | 8         | 3.83%   |
| 0x306d4    | 8         | 3.83%   |
| 0x08108109 | 8         | 3.83%   |
| 0x906ea    | 5         | 2.39%   |
| 0x806c1    | 5         | 2.39%   |
| 0x306c3    | 5         | 2.39%   |
| 0x08108102 | 5         | 2.39%   |
| 0x706e5    | 4         | 1.91%   |
| 0x20655    | 4         | 1.91%   |
| 0x806eb    | 3         | 1.44%   |
| 0x30678    | 3         | 1.44%   |
| 0x20652    | 3         | 1.44%   |
| 0x0a50000c | 3         | 1.44%   |
| 0xa0652    | 2         | 0.96%   |
| 0x906e9    | 2         | 0.96%   |
| 0x1067a    | 2         | 0.96%   |
| 0x10661    | 2         | 0.96%   |
| 0x08608103 | 2         | 0.96%   |
| 0x08600106 | 2         | 0.96%   |
| 0x08600104 | 2         | 0.96%   |
| 0x05000029 | 2         | 0.96%   |
| 0x906a4    | 1         | 0.48%   |
| 0x806d1    | 1         | 0.48%   |
| 0x706a1    | 1         | 0.48%   |
| 0x6fd      | 1         | 0.48%   |
| 0x6e8      | 1         | 0.48%   |
| 0x6d8      | 1         | 0.48%   |
| 0x506e3    | 1         | 0.48%   |
| 0x406c4    | 1         | 0.48%   |
| 0x30673    | 1         | 0.48%   |
| 0x106ca    | 1         | 0.48%   |
| 0x106c2    | 1         | 0.48%   |
| 0x10676    | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 50        | 24.63%  |
| Haswell          | 17        | 8.37%   |
| SandyBridge      | 16        | 7.88%   |
| Zen+             | 15        | 7.39%   |
| IvyBridge        | 15        | 7.39%   |
| Skylake          | 12        | 5.91%   |
| Broadwell        | 9         | 4.43%   |
| Westmere         | 8         | 3.94%   |
| Zen 2            | 7         | 3.45%   |
| Silvermont       | 7         | 3.45%   |
| IceLake          | 6         | 2.96%   |
| TigerLake        | 5         | 2.46%   |
| Zen              | 4         | 1.97%   |
| Zen 3            | 3         | 1.48%   |
| Penryn           | 3         | 1.48%   |
| Excavator        | 3         | 1.48%   |
| Core             | 3         | 1.48%   |
| CometLake        | 3         | 1.48%   |
| Unknown          | 3         | 1.48%   |
| Puma             | 2         | 0.99%   |
| Piledriver       | 2         | 0.99%   |
| P6               | 2         | 0.99%   |
| Bonnell          | 2         | 0.99%   |
| Bobcat           | 2         | 0.99%   |
| Nehalem          | 1         | 0.49%   |
| Jaguar           | 1         | 0.49%   |
| Goldmont plus    | 1         | 0.49%   |
| Alderlake Hybrid | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 150       | 56.6%   |
| AMD                              | 64        | 24.15%  |
| Nvidia                           | 50        | 18.87%  |
| Silicon Integrated Systems [SiS] | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 5.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 5.47%   |
| Intel UHD Graphics 620                                                                   | 14        | 5.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 5.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 4.38%   |
| Intel HD Graphics 620                                                                    | 11        | 4.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 3.65%   |
| Intel HD Graphics 5500                                                                   | 9         | 3.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 3.28%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 3.28%   |
| AMD Renoir                                                                               | 7         | 2.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 2.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.19%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 2.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.82%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.46%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.46%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.09%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 1.09%   |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 1.09%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.09%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.73%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.73%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.73%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.73%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.73%   |
| Intel HD Graphics 630                                                                    | 2         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.73%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 0.73%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.73%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 91        | 44.83%  |
| Intel + Nvidia | 40        | 19.7%   |
| 1 x AMD        | 37        | 18.23%  |
| Intel + AMD    | 18        | 8.87%   |
| 1 x Nvidia     | 6         | 2.96%   |
| 2 x AMD        | 5         | 2.46%   |
| AMD + Nvidia   | 4         | 1.97%   |
| 2 x Intel      | 1         | 0.49%   |
| 1 x SiS        | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 175       | 84.95%  |
| Proprietary | 26        | 12.62%  |
| Unknown     | 5         | 2.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 118       | 56.46%  |
| 1.01-2.0   | 39        | 18.66%  |
| 0.01-0.5   | 26        | 12.44%  |
| 3.01-4.0   | 11        | 5.26%   |
| 0.51-1.0   | 9         | 4.31%   |
| 5.01-6.0   | 4         | 1.91%   |
| 7.01-8.0   | 1         | 0.48%   |
| 8.01-16.0  | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 51        | 22.08%  |
| BOE                 | 44        | 19.05%  |
| AU Optronics        | 36        | 15.58%  |
| Samsung Electronics | 31        | 13.42%  |
| LG Display          | 24        | 10.39%  |
| Goldstar            | 5         | 2.16%   |
| PANDA               | 4         | 1.73%   |
| Sharp               | 3         | 1.3%    |
| Hewlett-Packard     | 3         | 1.3%    |
| AOC                 | 3         | 1.3%    |
| Sony                | 2         | 0.87%   |
| Lenovo              | 2         | 0.87%   |
| JRY                 | 2         | 0.87%   |
| HannStar            | 2         | 0.87%   |
| Dell                | 2         | 0.87%   |
| Unknown             | 2         | 0.87%   |
| ViewSonic           | 1         | 0.43%   |
| Unknown (XXX)       | 1         | 0.43%   |
| TMX                 | 1         | 0.43%   |
| Panasonic           | 1         | 0.43%   |
| Mi                  | 1         | 0.43%   |
| LGD                 | 1         | 0.43%   |
| LG Philips          | 1         | 0.43%   |
| InnoLux Display     | 1         | 0.43%   |
| InfoVision          | 1         | 0.43%   |
| Hitachi             | 1         | 0.43%   |
| EXP                 | 1         | 0.43%   |
| DZX                 | 1         | 0.43%   |
| Apple               | 1         | 0.43%   |
| AGO                 | 1         | 0.43%   |
| Acer                | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 11        | 4.76%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 6         | 2.6%    |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 1.3%    |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 3         | 1.3%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 3         | 1.3%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 1.3%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 2         | 0.87%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 2         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.87%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2         | 0.87%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.87%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch         | 2         | 0.87%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.87%   |
| JRY HDMI JRY2380 1920x1080 530x290mm 23.8-inch                       | 2         | 0.87%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch      | 2         | 0.87%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.87%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                 | 2         | 0.87%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 2         | 0.87%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 2         | 0.87%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 2         | 0.87%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.87%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 2         | 0.87%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                 | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch        | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch        | 2         | 0.87%   |
| Unknown                                                              | 2         | 0.87%   |
| ViewSonic VX2257 VSCB731 1920x1080 477x268mm 21.5-inch               | 1         | 0.43%   |
| Unknown (XXX) MS82PV XXX001A 1360x768 330x210mm 15.4-inch            | 1         | 0.43%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                | 1         | 0.43%   |
| Sony TV SNYEF03 1600x900                                             | 1         | 0.43%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch | 1         | 0.43%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch              | 1         | 0.43%   |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 443x249mm 20.0-inch | 1         | 0.43%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch    | 1         | 0.43%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch    | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 119       | 53.6%   |
| 1920x1080 (FHD)   | 67        | 30.18%  |
| 1600x900 (HD+)    | 7         | 3.15%   |
| 1360x768          | 4         | 1.8%    |
| 1280x800 (WXGA)   | 4         | 1.8%    |
| 3840x2160 (4K)    | 3         | 1.35%   |
| 1440x900 (WXGA+)  | 3         | 1.35%   |
| 3200x1800 (QHD+)  | 2         | 0.9%    |
| 1024x600          | 2         | 0.9%    |
| Unknown           | 2         | 0.9%    |
| 640x480           | 1         | 0.45%   |
| 3840x1080         | 1         | 0.45%   |
| 3200x2000         | 1         | 0.45%   |
| 2560x1600         | 1         | 0.45%   |
| 2520x1680         | 1         | 0.45%   |
| 2160x1440         | 1         | 0.45%   |
| 1920x1200 (WUXGA) | 1         | 0.45%   |
| 1280x720 (HD)     | 1         | 0.45%   |
| 1024x768 (XGA)    | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 112       | 48.91%  |
| 13      | 39        | 17.03%  |
| 14      | 29        | 12.66%  |
| 23      | 11        | 4.8%    |
| 17      | 6         | 2.62%   |
| 21      | 4         | 1.75%   |
| 18      | 4         | 1.75%   |
| 11      | 3         | 1.31%   |
| Unknown | 3         | 1.31%   |
| 72      | 2         | 0.87%   |
| 12      | 2         | 0.87%   |
| 10      | 2         | 0.87%   |
| 84      | 1         | 0.44%   |
| 60      | 1         | 0.44%   |
| 54      | 1         | 0.44%   |
| 48      | 1         | 0.44%   |
| 46      | 1         | 0.44%   |
| 39      | 1         | 0.44%   |
| 31      | 1         | 0.44%   |
| 27      | 1         | 0.44%   |
| 24      | 1         | 0.44%   |
| 20      | 1         | 0.44%   |
| 19      | 1         | 0.44%   |
| 16      | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 170       | 74.89%  |
| 201-300     | 14        | 6.17%   |
| 501-600     | 13        | 5.73%   |
| 401-500     | 10        | 4.41%   |
| 351-400     | 8         | 3.52%   |
| 1001-1500   | 4         | 1.76%   |
| 1501-2000   | 3         | 1.32%   |
| Unknown     | 3         | 1.32%   |
| 801-900     | 1         | 0.44%   |
| 601-700     | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 181       | 89.6%   |
| 16/10   | 13        | 6.44%   |
| 4/3     | 3         | 1.49%   |
| Unknown | 3         | 1.49%   |
| 3/2     | 2         | 0.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 112       | 48.91%  |
| 81-90          | 62        | 27.07%  |
| 201-250        | 14        | 6.11%   |
| More than 1000 | 6         | 2.62%   |
| 71-80          | 6         | 2.62%   |
| 151-200        | 5         | 2.18%   |
| 121-130        | 4         | 1.75%   |
| 51-60          | 3         | 1.31%   |
| 141-150        | 3         | 1.31%   |
| Unknown        | 3         | 1.31%   |
| 41-50          | 2         | 0.87%   |
| 131-140        | 2         | 0.87%   |
| 501-1000       | 2         | 0.87%   |
| 61-70          | 1         | 0.44%   |
| 351-500        | 1         | 0.44%   |
| 301-350        | 1         | 0.44%   |
| 111-120        | 1         | 0.44%   |
| 91-100         | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 119       | 52.89%  |
| 121-160       | 59        | 26.22%  |
| 51-100        | 29        | 12.89%  |
| 1-50          | 7         | 3.11%   |
| 161-240       | 5         | 2.22%   |
| More than 240 | 3         | 1.33%   |
| Unknown       | 3         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 166       | 79.81%  |
| 2     | 33        | 15.87%  |
| 0     | 7         | 3.37%   |
| 3     | 2         | 0.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 131       | 41.19%  |
| Intel                            | 75        | 23.58%  |
| Qualcomm Atheros                 | 60        | 18.87%  |
| Broadcom                         | 13        | 4.09%   |
| TP-Link                          | 7         | 2.2%    |
| Ralink                           | 5         | 1.57%   |
| Marvell Technology Group         | 4         | 1.26%   |
| Xiaomi                           | 3         | 0.94%   |
| MediaTek                         | 3         | 0.94%   |
| ASIX Electronics                 | 3         | 0.94%   |
| Samsung Electronics              | 2         | 0.63%   |
| Ralink Technology                | 2         | 0.63%   |
| Motorola PCS                     | 2         | 0.63%   |
| ICS Advent                       | 2         | 0.63%   |
| T & A Mobile Phones              | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Microsoft                        | 1         | 0.31%   |
| Lenovo                           | 1         | 0.31%   |
| Broadcom Limited                 | 1         | 0.31%   |
| Apple                            | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 87        | 22.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 24        | 6.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 5.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 3.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 3.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.54%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 1.28%   |
| Intel Wireless 8260                                                     | 5         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.28%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 1.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 1.03%   |
| Intel Wireless 7260                                                     | 4         | 1.03%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 3         | 0.77%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 3         | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.77%   |
| Intel Wireless 7265                                                     | 3         | 0.77%   |
| Intel WiFi Link 5100                                                    | 3         | 0.77%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.77%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.51%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.51%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 2         | 0.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 35.1%   |
| Qualcomm Atheros      | 54        | 25.96%  |
| Realtek Semiconductor | 53        | 25.48%  |
| Broadcom              | 11        | 5.29%   |
| TP-Link               | 6         | 2.88%   |
| Ralink                | 5         | 2.4%    |
| MediaTek              | 3         | 1.44%   |
| Ralink Technology     | 2         | 0.96%   |
| Broadcom Limited      | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 11.06%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 6.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 6.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 3.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 3.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.88%   |
| Intel Wireless 8265 / 8275                                              | 6         | 2.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 2.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.88%   |
| Intel Wireless 8260                                                     | 5         | 2.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.4%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 1.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.92%   |
| Intel Wireless 7260                                                     | 4         | 1.92%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.92%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 3         | 1.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.44%   |
| Intel Wireless 7265                                                     | 3         | 1.44%   |
| Intel WiFi Link 5100                                                    | 3         | 1.44%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.96%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.96%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.96%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.96%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.96%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                 | 1         | 0.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 117       | 64.64%  |
| Intel                            | 27        | 14.92%  |
| Qualcomm Atheros                 | 12        | 6.63%   |
| Marvell Technology Group         | 4         | 2.21%   |
| Xiaomi                           | 3         | 1.66%   |
| Broadcom                         | 3         | 1.66%   |
| ASIX Electronics                 | 3         | 1.66%   |
| Samsung Electronics              | 2         | 1.1%    |
| Motorola PCS                     | 2         | 1.1%    |
| ICS Advent                       | 2         | 1.1%    |
| TP-Link                          | 1         | 0.55%   |
| T & A Mobile Phones              | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| Microsoft                        | 1         | 0.55%   |
| Lenovo                           | 1         | 0.55%   |
| Apple                            | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 87        | 47.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 24        | 13.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 3.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 2.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.1%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.1%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 1.1%    |
| Motorola PCS moto g pure                                                       | 2         | 1.1%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.1%    |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.1%    |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.1%    |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.1%    |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.1%    |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.1%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 2         | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.1%    |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.55%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                                   | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.55%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.55%   |
| Microsoft Ethernet Adapter                                                     | 1         | 0.55%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.55%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.55%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.55%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.55%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.55%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.55%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.55%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 200       | 53.48%  |
| Ethernet | 174       | 46.52%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 158       | 73.15%  |
| Ethernet | 58        | 26.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 157       | 77.34%  |
| 1     | 43        | 21.18%  |
| 0     | 3         | 1.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 168       | 80.77%  |
| Yes  | 40        | 19.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 32.54%  |
| Realtek Semiconductor           | 35        | 20.71%  |
| Qualcomm Atheros Communications | 30        | 17.75%  |
| Lite-On Technology              | 11        | 6.51%   |
| IMC Networks                    | 11        | 6.51%   |
| Toshiba                         | 5         | 2.96%   |
| Ralink                          | 4         | 2.37%   |
| Broadcom                        | 4         | 2.37%   |
| Hewlett-Packard                 | 3         | 1.78%   |
| Foxconn / Hon Hai               | 3         | 1.78%   |
| Dell                            | 2         | 1.18%   |
| Cambridge Silicon Radio         | 2         | 1.18%   |
| Realtek                         | 1         | 0.59%   |
| Foxconn International           | 1         | 0.59%   |
| Apple                           | 1         | 0.59%   |
| Alps Electric                   | 1         | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 12.43%  |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 10.65%  |
| Qualcomm Atheros  Bluetooth Device                  | 18        | 10.65%  |
| Realtek Bluetooth Radio                             | 15        | 8.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 6.51%   |
| Intel AX201 Bluetooth                               | 10        | 5.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 2.96%   |
| Ralink RT3290 Bluetooth                             | 4         | 2.37%   |
| Intel AX200 Bluetooth                               | 4         | 2.37%   |
| IMC Networks Bluetooth Radio                        | 4         | 2.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.78%   |
| Lite-On Bluetooth Radio                             | 3         | 1.78%   |
| Lite-On Bluetooth Device                            | 3         | 1.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.78%   |
| IMC Networks Wireless_Device                        | 3         | 1.78%   |
| IMC Networks Bluetooth Device                       | 3         | 1.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.78%   |
| Toshiba Bluetooth Device                            | 2         | 1.18%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.18%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.18%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.18%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.18%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.59%   |
| Toshiba BCM43142A0                                  | 1         | 0.59%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.59%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.59%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.59%   |
| Realtek Bluetooth Radio                             | 1         | 0.59%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.59%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.59%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.59%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.59%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.59%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.59%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.59%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 157       | 67.09%  |
| AMD                              | 46        | 19.66%  |
| Nvidia                           | 22        | 9.4%    |
| C-Media Electronics              | 3         | 1.28%   |
| Generalplus Technology           | 2         | 0.85%   |
| Silicon Integrated Systems [SiS] | 1         | 0.43%   |
| Razer USA                        | 1         | 0.43%   |
| Pixart Imaging                   | 1         | 0.43%   |
| Hewlett-Packard                  | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 36        | 12.04%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 31        | 10.37%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 6.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 6.35%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 4.01%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 4.01%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 3.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 3.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 3.01%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 3.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.67%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.34%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.34%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1%      |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.67%   |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.67%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.67%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.67%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.67%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.33%   |
| Razer USA RZ19-0229 Gaming Microphone                                                             | 1         | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 31.61%  |
| SK hynix            | 30        | 19.35%  |
| Micron Technology   | 25        | 16.13%  |
| Kingston            | 20        | 12.9%   |
| Unknown             | 10        | 6.45%   |
| Ramaxel Technology  | 8         | 5.16%   |
| Team                | 3         | 1.94%   |
| Hewlett-Packard     | 2         | 1.29%   |
| Crucial             | 2         | 1.29%   |
| Unknown (ABCD)      | 1         | 0.65%   |
| Patriot             | 1         | 0.65%   |
| Goldkey             | 1         | 0.65%   |
| Elpida              | 1         | 0.65%   |
| CSX                 | 1         | 0.65%   |
| Corsair             | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 6         | 3.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 5         | 3.03%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 5         | 3.03%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 2.42%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 1.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 3         | 1.82%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 3         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 1.82%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s       | 3         | 1.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 3         | 1.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 3         | 1.82%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 3         | 1.82%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s     | 3         | 1.82%   |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 2         | 1.21%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s        | 2         | 1.21%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.21%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.21%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 1.21%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 1.21%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 2         | 1.21%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s | 2         | 1.21%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 1.21%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s       | 2         | 1.21%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 2         | 1.21%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 1.21%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 1.21%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 2         | 1.21%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 2         | 1.21%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 2         | 1.21%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s         | 1         | 0.61%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s              | 1         | 0.61%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 0.61%   |
| Unknown RAM Module 512MB SODIMM DDR2                        | 1         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s              | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM SDRAM                         | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                      | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                 | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                 | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM 800MT/s                       | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 57        | 49.57%  |
| DDR3    | 42        | 36.52%  |
| LPDDR4  | 7         | 6.09%   |
| LPDDR3  | 3         | 2.61%   |
| DDR2    | 3         | 2.61%   |
| SDRAM   | 2         | 1.74%   |
| Unknown | 1         | 0.87%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 108       | 93.91%  |
| Row Of Chips | 7         | 6.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 55        | 40.74%  |
| 4096  | 54        | 40%     |
| 2048  | 11        | 8.15%   |
| 16384 | 9         | 6.67%   |
| 1024  | 3         | 2.22%   |
| 32768 | 2         | 1.48%   |
| 512   | 1         | 0.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 41        | 30.37%  |
| 1600    | 33        | 24.44%  |
| 3200    | 23        | 17.04%  |
| 2400    | 7         | 5.19%   |
| 3266    | 6         | 4.44%   |
| 1333    | 5         | 3.7%    |
| 1334    | 4         | 2.96%   |
| 2133    | 3         | 2.22%   |
| Unknown | 3         | 2.22%   |
| 1867    | 2         | 1.48%   |
| 1067    | 2         | 1.48%   |
| 4267    | 1         | 0.74%   |
| 4199    | 1         | 0.74%   |
| 2933    | 1         | 0.74%   |
| 1066    | 1         | 0.74%   |
| 800     | 1         | 0.74%   |
| 533     | 1         | 0.74%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 2         | 33.33%  |
| Seiko Epson         | 1         | 16.67%  |
| Prolific Technology | 1         | 16.67%  |
| Hewlett-Packard     | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series       | 1         | 16.67%  |
| Prolific PL2305 Parallel Port    | 1         | 16.67%  |
| HP LaserJet Professional P 1102w | 1         | 16.67%  |
| Canon G2010 series               | 1         | 16.67%  |
| Canon E400 series                | 1         | 16.67%  |
| Brother DCP-T300                 | 1         | 16.67%  |

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
| Chicony Electronics                    | 45        | 22.96%  |
| IMC Networks                           | 22        | 11.22%  |
| Realtek Semiconductor                  | 15        | 7.65%   |
| Acer                                   | 14        | 7.14%   |
| Microdia                               | 13        | 6.63%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 6.12%   |
| Syntek                                 | 11        | 5.61%   |
| Sunplus Innovation Technology          | 11        | 5.61%   |
| Lite-On Technology                     | 11        | 5.61%   |
| Quanta                                 | 10        | 5.1%    |
| Suyin                                  | 8         | 4.08%   |
| Bison Electronics                      | 6         | 3.06%   |
| Importek                               | 4         | 2.04%   |
| Sonix Technology                       | 3         | 1.53%   |
| Samsung Electronics                    | 2         | 1.02%   |
| Ricoh                                  | 2         | 1.02%   |
| Luxvisions Innotech Limited            | 2         | 1.02%   |
| Alcor Micro                            | 2         | 1.02%   |
| Logitech                               | 1         | 0.51%   |
| Apple                                  | 1         | 0.51%   |
| ANYKA                                  | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 8         | 4.06%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 7         | 3.55%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 2.54%   |
| Lite-On Integrated Camera                                                  | 5         | 2.54%   |
| Chicony Integrated Camera                                                  | 5         | 2.54%   |
| Chicony EasyCamera                                                         | 5         | 2.54%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 2.03%   |
| IMC Networks Integrated Camera                                             | 4         | 2.03%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 2.03%   |
| Chicony HP Truevision HD                                                   | 4         | 2.03%   |
| Chicony HD WebCam                                                          | 4         | 2.03%   |
| Bison Integrated Camera                                                    | 4         | 2.03%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 3         | 1.52%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 1.52%   |
| Lite-On HP HD Camera                                                       | 3         | 1.52%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 1.52%   |
| IMC Networks HP TrueVision HD Camera                                       | 3         | 1.52%   |
| Chicony TOSHIBA Web Camera - HD                                            | 3         | 1.52%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.52%   |
| Acer Integrated Camera                                                     | 3         | 1.52%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 1.02%   |
| Sunplus Integrated Webcam                                                  | 2         | 1.02%   |
| Samsung Galaxy A5 (MTP)                                                    | 2         | 1.02%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 1.02%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 1.02%   |
| Realtek Integrated Webcam                                                  | 2         | 1.02%   |
| Realtek HP Wide Vision HD Camera                                           | 2         | 1.02%   |
| Quanta HP Webcam                                                           | 2         | 1.02%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 1.02%   |
| IMC Networks HD Camera                                                     | 2         | 1.02%   |
| Chicony VGA Webcam                                                         | 2         | 1.02%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 1.02%   |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 1.02%   |
| Chicony HP Webcam                                                          | 2         | 1.02%   |
| Chicony HP HD Camera                                                       | 2         | 1.02%   |
| Alcor Micro TOSHIBA Web Camera - MP                                        | 2         | 1.02%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 1.02%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 22        | 51.16%  |
| Synaptics                  | 11        | 25.58%  |
| Shenzhen Goodix Technology | 5         | 11.63%  |
| Elan Microelectronics      | 3         | 6.98%   |
| STMicroelectronics         | 1         | 2.33%   |
| AuthenTec                  | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 7         | 16.28%  |
| Validity Sensors VFS5011 Fingerprint Reader                | 6         | 13.95%  |
| Synaptics  WBDI                                            | 4         | 9.3%    |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 6.98%   |
| Validity Sensors Synaptics WBDI                            | 2         | 4.65%   |
| Validity Sensors Fingerprint scanner                       | 2         | 4.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.65%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 4.65%   |
| Elan ELAN:Fingerprint                                      | 2         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.33%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.33%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2.33%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 2.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                  | 1         | 2.33%   |
| Synaptics WBDI                                             | 1         | 2.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.33%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.33%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.33%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Upek        | 3         | 30%     |
| Broadcom    | 3         | 30%     |
| Alcor Micro | 3         | 30%     |
| O2 Micro    | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 30%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 30%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 125       | 60.1%   |
| 1     | 68        | 32.69%  |
| 2     | 13        | 6.25%   |
| 3     | 2         | 0.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 44.79%  |
| Graphics card            | 18        | 18.75%  |
| Net/wireless             | 10        | 10.42%  |
| Chipcard                 | 10        | 10.42%  |
| Bluetooth                | 5         | 5.21%   |
| Multimedia controller    | 3         | 3.13%   |
| Storage                  | 2         | 2.08%   |
| Card reader              | 2         | 2.08%   |
| Camera                   | 2         | 2.08%   |
| Communication controller | 1         | 1.04%   |

