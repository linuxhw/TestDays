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

Total: 285

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 32        | 15.53%  |
| OpenMandriva 4.3             | 10        | 4.85%   |
| Ubuntu 18.04                 | 9         | 4.37%   |
| Ubuntu 22.04                 | 7         | 3.4%    |
| Zorin 15                     | 6         | 2.91%   |
| Arch Rolling                 | 6         | 2.91%   |
| Ubuntu 19.10                 | 5         | 2.43%   |
| Linux Mint 20.3              | 5         | 2.43%   |
| Arch                         | 5         | 2.43%   |
| Xubuntu 20.04                | 4         | 1.94%   |
| Ubuntu 21.04                 | 4         | 1.94%   |
| Pop!_OS 21.10                | 4         | 1.94%   |
| Manjaro                      | 4         | 1.94%   |
| Debian 11                    | 4         | 1.94%   |
| Ubuntu 19.04                 | 3         | 1.46%   |
| Pop!_OS 20.10                | 3         | 1.46%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.46%   |
| OpenMandriva 4.2             | 3         | 1.46%   |
| Manjaro 20.1                 | 3         | 1.46%   |
| Linux Mint 21.1              | 3         | 1.46%   |
| KDE neon 20.04               | 3         | 1.46%   |
| Fedora 37                    | 3         | 1.46%   |
| Elementary 5.1.7             | 3         | 1.46%   |
| Debian 10                    | 3         | 1.46%   |
| ROSA R9                      | 2         | 0.97%   |
| ROSA R10                     | 2         | 0.97%   |
| ROSA 12.2                    | 2         | 0.97%   |
| Pop!_OS 22.04                | 2         | 0.97%   |
| Pop!_OS 20.04                | 2         | 0.97%   |
| OpenMandriva 4.90            | 2         | 0.97%   |
| OpenMandriva 23.01           | 2         | 0.97%   |
| Linux Mint 20                | 2         | 0.97%   |
| Kubuntu 20.04                | 2         | 0.97%   |
| Fedora 35                    | 2         | 0.97%   |
| Fedora 34                    | 2         | 0.97%   |
| Fedora 33                    | 2         | 0.97%   |
| Fedora 32                    | 2         | 0.97%   |
| Debian                       | 2         | 0.97%   |
| CentOS 8                     | 2         | 0.97%   |
| ArcoLinux Rolling            | 2         | 0.97%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 61        | 30.05%  |
| OpenMandriva  | 18        | 8.87%   |
| Linux Mint    | 13        | 6.4%    |
| Pop!_OS       | 12        | 5.91%   |
| Fedora        | 12        | 5.91%   |
| Arch          | 12        | 5.91%   |
| Manjaro       | 10        | 4.93%   |
| Debian        | 10        | 4.93%   |
| Zorin         | 7         | 3.45%   |
| ROSA          | 7         | 3.45%   |
| Xubuntu       | 4         | 1.97%   |
| KDE neon      | 4         | 1.97%   |
| Elementary    | 4         | 1.97%   |
| openSUSE      | 3         | 1.48%   |
| Endless       | 3         | 1.48%   |
| Ubuntu MATE   | 2         | 0.99%   |
| Lubuntu       | 2         | 0.99%   |
| Kubuntu       | 2         | 0.99%   |
| Kali          | 2         | 0.99%   |
| CentOS        | 2         | 0.99%   |
| ArcoLinux     | 2         | 0.99%   |
| Void Linux    | 1         | 0.49%   |
| Ubuntu Unity  | 1         | 0.49%   |
| Ubuntu Budgie | 1         | 0.49%   |
| SteamOS       | 1         | 0.49%   |
| Peppermint    | 1         | 0.49%   |
| Parrot        | 1         | 0.49%   |
| MX            | 1         | 0.49%   |
| LMDE          | 1         | 0.49%   |
| Laxer OS      | 1         | 0.49%   |
| Clear Linux   | 1         | 0.49%   |
| Artix         | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 10        | 4.48%   |
| 5.13.0-40-generic               | 5         | 2.24%   |
| 5.4.0-42-generic                | 4         | 1.79%   |
| 5.4.0-26-generic                | 3         | 1.35%   |
| 5.3.0-40-generic                | 3         | 1.35%   |
| 5.13.0-51-generic               | 3         | 1.35%   |
| 5.11.0-25-generic               | 3         | 1.35%   |
| 5.10.0-13-amd64                 | 3         | 1.35%   |
| 6.1.1-desktop-1omv2290          | 2         | 0.9%    |
| 5.8.0-44-generic                | 2         | 0.9%    |
| 5.4.0-7642-generic              | 2         | 0.9%    |
| 5.4.0-66-generic                | 2         | 0.9%    |
| 5.4.0-65-generic                | 2         | 0.9%    |
| 5.4.0-58-generic                | 2         | 0.9%    |
| 5.4.0-54-generic                | 2         | 0.9%    |
| 5.4.0-39-generic                | 2         | 0.9%    |
| 5.4.0-33-generic                | 2         | 0.9%    |
| 5.4.0-28-generic                | 2         | 0.9%    |
| 5.4.0-109-generic               | 2         | 0.9%    |
| 5.3.0-42-generic                | 2         | 0.9%    |
| 5.3.0-23-generic                | 2         | 0.9%    |
| 5.18.12-desktop-3omv4090        | 2         | 0.9%    |
| 5.17.5-arch1-1                  | 2         | 0.9%    |
| 5.16.19-76051619-generic        | 2         | 0.9%    |
| 5.15.49-1-lts                   | 2         | 0.9%    |
| 5.15.0-57-generic               | 2         | 0.9%    |
| 5.15.0-52-generic               | 2         | 0.9%    |
| 5.15.0-25-generic               | 2         | 0.9%    |
| 5.13.0-30-generic               | 2         | 0.9%    |
| 5.11.0-7614-generic             | 2         | 0.9%    |
| 5.10.14-desktop-1omv4002        | 2         | 0.9%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.9%    |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 0.9%    |
| 6.1.8-1252.native               | 1         | 0.45%   |
| 6.0.8-arch1-1                   | 1         | 0.45%   |
| 6.0.7-arch1-1                   | 1         | 0.45%   |
| 6.0.6-arch1-1                   | 1         | 0.45%   |
| 6.0.2-zen1-1-zen                | 1         | 0.45%   |
| 6.0.15-300.rog.fc37.x86_64      | 1         | 0.45%   |
| 6.0.15-300.fc37.x86_64          | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 37        | 17.21%  |
| 5.15.0  | 15        | 6.98%   |
| 5.11.0  | 14        | 6.51%   |
| 5.13.0  | 13        | 6.05%   |
| 5.3.0   | 12        | 5.58%   |
| 5.16.7  | 10        | 4.65%   |
| 5.8.0   | 7         | 3.26%   |
| 5.0.0   | 7         | 3.26%   |
| 4.15.0  | 7         | 3.26%   |
| 5.10.0  | 6         | 2.79%   |
| 4.18.0  | 6         | 2.79%   |
| 6.0.0   | 3         | 1.4%    |
| 5.19.0  | 3         | 1.4%    |
| 5.17.5  | 3         | 1.4%    |
| 4.9.60  | 3         | 1.4%    |
| 6.1.1   | 2         | 0.93%   |
| 6.0.15  | 2         | 0.93%   |
| 5.18.12 | 2         | 0.93%   |
| 5.16.19 | 2         | 0.93%   |
| 5.15.49 | 2         | 0.93%   |
| 5.12.10 | 2         | 0.93%   |
| 5.10.14 | 2         | 0.93%   |
| 4.9.20  | 2         | 0.93%   |
| 4.19.0  | 2         | 0.93%   |
| 6.1.8   | 1         | 0.47%   |
| 6.0.8   | 1         | 0.47%   |
| 6.0.7   | 1         | 0.47%   |
| 6.0.6   | 1         | 0.47%   |
| 6.0.2   | 1         | 0.47%   |
| 6.0.11  | 1         | 0.47%   |
| 6.0.10  | 1         | 0.47%   |
| 5.9.16  | 1         | 0.47%   |
| 5.9.11  | 1         | 0.47%   |
| 5.8.6   | 1         | 0.47%   |
| 5.8.4   | 1         | 0.47%   |
| 5.8.11  | 1         | 0.47%   |
| 5.7.4   | 1         | 0.47%   |
| 5.7.17  | 1         | 0.47%   |
| 5.6.6   | 1         | 0.47%   |
| 5.6.14  | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 40        | 18.96%  |
| 5.15    | 26        | 12.32%  |
| 5.11    | 15        | 7.11%   |
| 5.13    | 14        | 6.64%   |
| 5.16    | 13        | 6.16%   |
| 5.3     | 12        | 5.69%   |
| 5.10    | 12        | 5.69%   |
| 6.0     | 10        | 4.74%   |
| 5.8     | 10        | 4.74%   |
| 5.17    | 7         | 3.32%   |
| 5.0     | 7         | 3.32%   |
| 4.15    | 7         | 3.32%   |
| 4.18    | 6         | 2.84%   |
| 5.19    | 5         | 2.37%   |
| 5.12    | 4         | 1.9%    |
| 4.9     | 4         | 1.9%    |
| 6.1     | 3         | 1.42%   |
| 5.18    | 3         | 1.42%   |
| 5.14    | 3         | 1.42%   |
| 5.9     | 2         | 0.95%   |
| 5.7     | 2         | 0.95%   |
| 5.6     | 2         | 0.95%   |
| 4.19    | 2         | 0.95%   |
| 5.1     | 1         | 0.47%   |
| 4.16    | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 186       | 95.88%  |
| i686   | 8         | 4.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 94        | 46.77%  |
| KDE5            | 31        | 15.42%  |
| XFCE            | 18        | 8.96%   |
| Unknown         | 15        | 7.46%   |
| X-Cinnamon      | 10        | 4.98%   |
| MATE            | 6         | 2.99%   |
| KDE             | 6         | 2.99%   |
| Pantheon        | 4         | 1.99%   |
| KDE4            | 4         | 1.99%   |
| LXQt            | 3         | 1.49%   |
| i3              | 3         | 1.49%   |
| LXDE            | 2         | 1%      |
| Budgie          | 2         | 1%      |
| Unity           | 1         | 0.5%    |
| spectrwm        | 1         | 0.5%    |
| GNOME Flashback | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 153       | 76.12%  |
| Wayland | 33        | 16.42%  |
| Unknown | 14        | 6.97%   |
| Tty     | 1         | 0.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 93        | 46.5%   |
| GDM     | 35        | 17.5%   |
| SDDM    | 28        | 14%     |
| LightDM | 23        | 11.5%   |
| GDM3    | 14        | 7%      |
| KDM     | 4         | 2%      |
| TDM     | 2         | 1%      |
| XDM     | 1         | 0.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_PE   | 94        | 47.24%  |
| en_US   | 54        | 27.14%  |
| es_ES   | 18        | 9.05%   |
| Unknown | 16        | 8.04%   |
| es_MX   | 3         | 1.51%   |
| C       | 3         | 1.51%   |
| it_IT   | 2         | 1.01%   |
| fr_FR   | 2         | 1.01%   |
| en_GB   | 2         | 1.01%   |
| ca_ES   | 2         | 1.01%   |
| es_CO   | 1         | 0.5%    |
| en_NZ   | 1         | 0.5%    |
| Default | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 108       | 54.82%  |
| BIOS | 89        | 45.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 154       | 77.39%  |
| Overlay | 19        | 9.55%   |
| Btrfs   | 12        | 6.03%   |
| Unknown | 7         | 3.52%   |
| Xfs     | 6         | 3.02%   |
| Ext3    | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 105       | 53.3%   |
| GPT     | 72        | 36.55%  |
| MBR     | 20        | 10.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 171       | 87.24%  |
| Yes       | 25        | 12.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 113       | 57.65%  |
| Yes       | 83        | 42.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 53        | 27.46%  |
| Hewlett-Packard     | 51        | 26.42%  |
| ASUSTek Computer    | 23        | 11.92%  |
| Dell                | 20        | 10.36%  |
| Toshiba             | 14        | 7.25%   |
| Acer                | 14        | 7.25%   |
| Sony                | 4         | 2.07%   |
| HUAWEI              | 3         | 1.55%   |
| MSI                 | 2         | 1.04%   |
| ADVANCE             | 2         | 1.04%   |
| Samsung Electronics | 1         | 0.52%   |
| Razer               | 1         | 0.52%   |
| efirstview          | 1         | 0.52%   |
| Compal              | 1         | 0.52%   |
| Chuwi               | 1         | 0.52%   |
| Apple               | 1         | 0.52%   |
| Unknown             | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo V330-15IKB 81AX                                | 4         | 2.07%   |
| HP Pavilion Laptop 15-cw1xxx                          | 4         | 2.07%   |
| Lenovo V310-15ISK 80SY                                | 3         | 1.55%   |
| Lenovo IdeaPad S540-14API 81NH                        | 2         | 1.04%   |
| Lenovo IdeaPad S145-15IWL 81MV                        | 2         | 1.04%   |
| Lenovo IdeaPad 330S-14IKB 81F4                        | 2         | 1.04%   |
| Lenovo IdeaPad 3 14ADA05 81W0                         | 2         | 1.04%   |
| HP ProBook 645 G4                                     | 2         | 1.04%   |
| HP Laptop 15-ef1xxx                                   | 2         | 1.04%   |
| HP 450                                                | 2         | 1.04%   |
| HP 14                                                 | 2         | 1.04%   |
| Dell XPS 13 9360                                      | 2         | 1.04%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA                | 2         | 1.04%   |
| ASUS VivoBook 15_ASUS Laptop X507UBR                  | 2         | 1.04%   |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV              | 2         | 1.04%   |
| Toshiba Satellite P755                                | 1         | 0.52%   |
| Toshiba Satellite P300                                | 1         | 0.52%   |
| Toshiba Satellite L855                                | 1         | 0.52%   |
| Toshiba Satellite L45-B                               | 1         | 0.52%   |
| Toshiba Satellite L35                                 | 1         | 0.52%   |
| Toshiba Satellite E205                                | 1         | 0.52%   |
| Toshiba Satellite C845                                | 1         | 0.52%   |
| Toshiba Satellite C655D                               | 1         | 0.52%   |
| Toshiba Satellite C645                                | 1         | 0.52%   |
| Toshiba Satellite C55-B                               | 1         | 0.52%   |
| Toshiba Satellite C45-A                               | 1         | 0.52%   |
| Toshiba Satellite A665                                | 1         | 0.52%   |
| Toshiba QOSMIO X775                                   | 1         | 0.52%   |
| Toshiba NB505                                         | 1         | 0.52%   |
| Sony VPCEC2JFX                                        | 1         | 0.52%   |
| Sony VGN-FW56M                                        | 1         | 0.52%   |
| Sony VGN-FW170J                                       | 1         | 0.52%   |
| Sony SVF15A17CLB                                      | 1         | 0.52%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.52%   |
| Razer Blade                                           | 1         | 0.52%   |
| MSI Prestige 14 A10SC                                 | 1         | 0.52%   |
| MSI GL65 Leopard 10SEK                                | 1         | 0.52%   |
| Lenovo Yoga 2 11 20332                                | 1         | 0.52%   |
| Lenovo Y70-70 Touch 80DU                              | 1         | 0.52%   |
| Lenovo V310-14ISK 80SX                                | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 16        | 8.29%   |
| HP Pavilion       | 15        | 7.77%   |
| Lenovo ThinkPad   | 14        | 7.25%   |
| Toshiba Satellite | 12        | 6.22%   |
| Acer Aspire       | 12        | 6.22%   |
| ASUS VivoBook     | 9         | 4.66%   |
| HP ProBook        | 8         | 4.15%   |
| Dell Latitude     | 8         | 4.15%   |
| HP Laptop         | 6         | 3.11%   |
| Dell Inspiron     | 6         | 3.11%   |
| Lenovo V330-15IKB | 4         | 2.07%   |
| Lenovo Legion     | 4         | 2.07%   |
| Lenovo V310-15ISK | 3         | 1.55%   |
| ASUS ASUS         | 3         | 1.55%   |
| HP ZBook          | 2         | 1.04%   |
| HP ENVY           | 2         | 1.04%   |
| HP Compaq         | 2         | 1.04%   |
| HP 450            | 2         | 1.04%   |
| HP 255            | 2         | 1.04%   |
| HP 250            | 2         | 1.04%   |
| HP 240            | 2         | 1.04%   |
| HP 14             | 2         | 1.04%   |
| Dell XPS          | 2         | 1.04%   |
| ASUS ROG          | 2         | 1.04%   |
| Toshiba QOSMIO    | 1         | 0.52%   |
| Toshiba NB505     | 1         | 0.52%   |
| Sony VPCEC2JFX    | 1         | 0.52%   |
| Sony VGN-FW56M    | 1         | 0.52%   |
| Sony VGN-FW170J   | 1         | 0.52%   |
| Sony SVF15A17CLB  | 1         | 0.52%   |
| Samsung 300E5EV   | 1         | 0.52%   |
| Razer Blade       | 1         | 0.52%   |
| MSI Prestige      | 1         | 0.52%   |
| MSI GL65          | 1         | 0.52%   |
| Lenovo Yoga       | 1         | 0.52%   |
| Lenovo Y70-70     | 1         | 0.52%   |
| Lenovo V310-14ISK | 1         | 0.52%   |
| Lenovo V15-IIL    | 1         | 0.52%   |
| Lenovo V14-ARE    | 1         | 0.52%   |
| Lenovo ThinkBook  | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 24        | 12.44%  |
| 2019 | 22        | 11.4%   |
| 2018 | 20        | 10.36%  |
| 2012 | 18        | 9.33%   |
| 2017 | 17        | 8.81%   |
| 2016 | 16        | 8.29%   |
| 2014 | 16        | 8.29%   |
| 2011 | 15        | 7.77%   |
| 2021 | 12        | 6.22%   |
| 2013 | 12        | 6.22%   |
| 2010 | 5         | 2.59%   |
| 2015 | 4         | 2.07%   |
| 2008 | 4         | 2.07%   |
| 2009 | 3         | 1.55%   |
| 2007 | 3         | 1.55%   |
| 2022 | 1         | 0.52%   |
| 2006 | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 193       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 174       | 89.69%  |
| Enabled  | 20        | 10.31%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 193       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 61        | 30.65%  |
| 8.01-16.0   | 54        | 27.14%  |
| 3.01-4.0    | 38        | 19.1%   |
| 16.01-24.0  | 28        | 14.07%  |
| 1.01-2.0    | 7         | 3.52%   |
| 2.01-3.0    | 5         | 2.51%   |
| 32.01-64.0  | 2         | 1.01%   |
| 0.51-1.0    | 2         | 1.01%   |
| 24.01-32.0  | 1         | 0.5%    |
| 64.01-256.0 | 1         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 68        | 32.23%  |
| 2.01-3.0  | 66        | 31.28%  |
| 4.01-8.0  | 30        | 14.22%  |
| 3.01-4.0  | 25        | 11.85%  |
| 0.51-1.0  | 14        | 6.64%   |
| 8.01-16.0 | 7         | 3.32%   |
| 0.01-0.5  | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 142       | 73.2%   |
| 2      | 49        | 25.26%  |
| 3      | 2         | 1.03%   |
| 0      | 1         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 62.69%  |
| Yes       | 72        | 37.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 85.57%  |
| No        | 28        | 14.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 98.96%  |
| No        | 2         | 1.04%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 161       | 82.99%  |
| No        | 33        | 17.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Peru    | 193       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lima                  | 131       | 65.5%   |
| Arequipa              | 20        | 10%     |
| Trujillo              | 13        | 6.5%    |
| Cusco                 | 5         | 2.5%    |
| Piura                 | 4         | 2%      |
| Huancayo              | 3         | 1.5%    |
| Chiclayo              | 3         | 1.5%    |
| Tacna                 | 2         | 1%      |
| Ica                   | 2         | 1%      |
| Callao                | 2         | 1%      |
| San Vicente de Canete | 1         | 0.5%    |
| San Isidro            | 1         | 0.5%    |
| San Borja             | 1         | 0.5%    |
| Punta Colorada        | 1         | 0.5%    |
| Pisco                 | 1         | 0.5%    |
| Oxapampa              | 1         | 0.5%    |
| Moquegua              | 1         | 0.5%    |
| La Victoria           | 1         | 0.5%    |
| Juliaca               | 1         | 0.5%    |
| Iquitos               | 1         | 0.5%    |
| Distrito de Lima      | 1         | 0.5%    |
| Cajamarca             | 1         | 0.5%    |
| Barranco              | 1         | 0.5%    |
| Ayacucho              | 1         | 0.5%    |
| Abancay               | 1         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba                        | 42        | 51     | 17.72%  |
| WDC                            | 39        | 45     | 16.46%  |
| Seagate                        | 34        | 40     | 14.35%  |
| Kingston                       | 26        | 32     | 10.97%  |
| Samsung Electronics            | 14        | 20     | 5.91%   |
| SanDisk                        | 11        | 14     | 4.64%   |
| Crucial                        | 7         | 9      | 2.95%   |
| Intel                          | 6         | 7      | 2.53%   |
| SK hynix                       | 5         | 8      | 2.11%   |
| Micron Technology              | 5         | 5      | 2.11%   |
| Hitachi                        | 5         | 7      | 2.11%   |
| Unknown                        | 4         | 4      | 1.69%   |
| KIOXIA                         | 4         | 5      | 1.69%   |
| HGST                           | 4         | 4      | 1.69%   |
| LITEON                         | 3         | 3      | 1.27%   |
| Hewlett-Packard                | 3         | 3      | 1.27%   |
| TO Exter                       | 2         | 4      | 0.84%   |
| Gigabyte Technology            | 2         | 2      | 0.84%   |
| China                          | 2         | 2      | 0.84%   |
| Unknown                        | 2         | 2      | 0.84%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.42%   |
| UMIS                           | 1         | 1      | 0.42%   |
| SSSTC                          | 1         | 1      | 0.42%   |
| Solid State Storage Technology | 1         | 1      | 0.42%   |
| Silicon Motion                 | 1         | 1      | 0.42%   |
| Phison Electronics             | 1         | 1      | 0.42%   |
| Phison                         | 1         | 1      | 0.42%   |
| Netac                          | 1         | 1      | 0.42%   |
| KingSpec                       | 1         | 1      | 0.42%   |
| ITHOO                          | 1         | 1      | 0.42%   |
| GLOWAY                         | 1         | 1      | 0.42%   |
| Fujitsu                        | 1         | 1      | 0.42%   |
| Dogfish                        | 1         | 1      | 0.42%   |
| Biwin Storage Technology       | 1         | 2      | 0.42%   |
| Apple                          | 1         | 1      | 0.42%   |
| ACASIS                         | 1         | 1      | 0.42%   |
| A-DATA Technology              | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 15        | 6.12%   |
| Kingston SA400S37240G 240GB SSD      | 10        | 4.08%   |
| Toshiba MQ04ABF100 1TB               | 9         | 3.67%   |
| Toshiba MQ01ABD100 1TB               | 9         | 3.67%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 6         | 2.45%   |
| Toshiba MQ01ABF050 500GB             | 5         | 2.04%   |
| WDC WD10JPCX-24UE4T0 1TB             | 4         | 1.63%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 1.63%   |
| Intel SSDPEKNU512GZ 512GB            | 4         | 1.63%   |
| WDC WD10SPZX-24Z10 1TB               | 3         | 1.22%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.22%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.22%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.82%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.82%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.82%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.82%   |
| Toshiba MK2565GSXN 250GB             | 2         | 0.82%   |
| Toshiba HDWJ110 1TB                  | 2         | 0.82%   |
| TO Exter nal USB 3.0 500GB           | 2         | 0.82%   |
| Seagate ST9500325AS 500GB            | 2         | 0.82%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.82%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.82%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.82%   |
| SanDisk NVMe SSD Drive 1TB           | 2         | 0.82%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.82%   |
| HP SSD S700 500GB                    | 2         | 0.82%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.82%   |
| Unknown                              | 2         | 0.82%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.41%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD     | 1         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.41%   |
| WDC WDS200T2B0A-00SM50 2TB SSD       | 1         | 0.41%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.41%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.41%   |
| WDC WD5000LPVT-24G33T1 500GB         | 1         | 0.41%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 0.41%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 0.41%   |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 40        | 49     | 37.04%  |
| Seagate | 34        | 39     | 31.48%  |
| WDC     | 22        | 25     | 20.37%  |
| Hitachi | 5         | 7      | 4.63%   |
| HGST    | 4         | 4      | 3.7%    |
| Fujitsu | 1         | 1      | 0.93%   |
| Apple   | 1         | 1      | 0.93%   |
| ACASIS  | 1         | 1      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 23        | 27     | 32.39%  |
| WDC                 | 13        | 14     | 18.31%  |
| Crucial             | 6         | 7      | 8.45%   |
| SanDisk             | 5         | 7      | 7.04%   |
| Samsung Electronics | 4         | 4      | 5.63%   |
| LITEON              | 3         | 3      | 4.23%   |
| Hewlett-Packard     | 3         | 3      | 4.23%   |
| TO Exter            | 2         | 4      | 2.82%   |
| China               | 2         | 2      | 2.82%   |
| Toshiba             | 1         | 1      | 1.41%   |
| SSSTC               | 1         | 1      | 1.41%   |
| SK hynix            | 1         | 4      | 1.41%   |
| Seagate             | 1         | 1      | 1.41%   |
| Netac               | 1         | 1      | 1.41%   |
| KingSpec            | 1         | 1      | 1.41%   |
| GLOWAY              | 1         | 1      | 1.41%   |
| Gigabyte Technology | 1         | 1      | 1.41%   |
| Dogfish             | 1         | 1      | 1.41%   |
| A-DATA Technology   | 1         | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 107       | 127    | 46.72%  |
| SSD     | 65        | 84     | 28.38%  |
| NVMe    | 51        | 68     | 22.27%  |
| MMC     | 4         | 4      | 1.75%   |
| Unknown | 2         | 2      | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 148       | 207    | 71.5%   |
| NVMe | 51        | 68     | 24.64%  |
| SAS  | 4         | 6      | 1.93%   |
| MMC  | 4         | 4      | 1.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 119    | 52.73%  |
| 0.51-1.0   | 77        | 91     | 46.67%  |
| 1.01-2.0   | 1         | 1      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 58        | 28.86%  |
| 501-1000       | 44        | 21.89%  |
| 251-500        | 42        | 20.9%   |
| 21-50          | 15        | 7.46%   |
| 51-100         | 14        | 6.97%   |
| 1-20           | 12        | 5.97%   |
| 1001-2000      | 10        | 4.98%   |
| More than 3000 | 2         | 1%      |
| 2001-3000      | 2         | 1%      |
| Unknown        | 2         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 77        | 37.93%  |
| 21-50     | 50        | 24.63%  |
| 101-250   | 24        | 11.82%  |
| 51-100    | 24        | 11.82%  |
| 251-500   | 14        | 6.9%    |
| 501-1000  | 9         | 4.43%   |
| 1001-2000 | 2         | 0.99%   |
| Unknown   | 2         | 0.99%   |
| 2001-3000 | 1         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD10JPCX-24UE4T0 1TB         | 2         | 2      | 10%     |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 1      | 5%      |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 1      | 5%      |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 5%      |
| Toshiba MQ01ABF050 500GB         | 1         | 1      | 5%      |
| Toshiba MK5065GSXN 500GB         | 1         | 1      | 5%      |
| Toshiba MK4058GSX 400GB          | 1         | 1      | 5%      |
| Toshiba MK2035GSS 200GB          | 1         | 1      | 5%      |
| Toshiba HDWJ110 1TB              | 1         | 1      | 5%      |
| SSSTC CVB-8D128-HP 128GB         | 1         | 1      | 5%      |
| Seagate ST9500325AS 500GB        | 1         | 1      | 5%      |
| Seagate ST9250315AS 250GB        | 1         | 1      | 5%      |
| Seagate ST1000LM014-1EJ164 1TB   | 1         | 1      | 5%      |
| Kingston SA400S37480G 480GB SSD  | 1         | 1      | 5%      |
| Hitachi HTS725050A7E630 500GB    | 1         | 1      | 5%      |
| Hitachi HTS545050B9A300 500GB    | 1         | 1      | 5%      |
| Hitachi HTS545050A7E380 500GB    | 1         | 3      | 5%      |
| Hitachi HTS545032B9A302 320GB    | 1         | 1      | 5%      |
| HGST HTS721010A9E630 1TB         | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 5         | 6      | 26.32%  |
| WDC      | 4         | 4      | 21.05%  |
| Hitachi  | 4         | 6      | 21.05%  |
| Seagate  | 3         | 3      | 15.79%  |
| SSSTC    | 1         | 1      | 5.26%   |
| Kingston | 1         | 1      | 5.26%   |
| HGST     | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 6      | 33.33%  |
| Hitachi | 4         | 6      | 26.67%  |
| Seagate | 3         | 3      | 20%     |
| WDC     | 2         | 2      | 13.33%  |
| HGST    | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 78.95%  |
| SSD  | 4         | 4      | 21.05%  |

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
| Detected | 115       | 166    | 55.83%  |
| Works    | 72        | 95     | 34.95%  |
| Malfunc  | 18        | 22     | 8.74%   |
| Failed   | 1         | 2      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 142       | 64.84%  |
| AMD                              | 29        | 13.24%  |
| SanDisk                          | 12        | 5.48%   |
| Samsung Electronics              | 10        | 4.57%   |
| Micron Technology                | 5         | 2.28%   |
| SK hynix                         | 4         | 1.83%   |
| KIOXIA                           | 4         | 1.83%   |
| Kingston Technology Company      | 3         | 1.37%   |
| Phison Electronics               | 2         | 0.91%   |
| Union Memory (Shenzhen)          | 1         | 0.46%   |
| Toshiba America Info Systems     | 1         | 0.46%   |
| Solid State Storage Technology   | 1         | 0.46%   |
| Silicon Motion                   | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] | 1         | 0.46%   |
| Micron/Crucial Technology        | 1         | 0.46%   |
| INNOGRIT                         | 1         | 0.46%   |
| Biwin Storage Technology         | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 28        | 12.07%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 26        | 11.21%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 7.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 6.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 4.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 4.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 2.59%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 2.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 2.59%   |
| Micron Non-Volatile memory controller                                          | 5         | 2.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.16%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 1.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 1.72%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.72%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 1.72%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.72%   |
| Intel Non-Volatile memory controller                                           | 4         | 1.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.72%   |
| SK hynix BC511                                                                 | 3         | 1.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.86%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.86%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.86%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 0.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.86%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.43%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.43%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.43%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 0.43%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.43%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.43%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 144       | 64%     |
| NVMe | 51        | 22.67%  |
| RAID | 23        | 10.22%  |
| IDE  | 7         | 3.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 154       | 79.79%  |
| AMD    | 39        | 20.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 9         | 4.66%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 6         | 3.11%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 6         | 3.11%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 6         | 3.11%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 2.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 4         | 2.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 4         | 2.07%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 4         | 2.07%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 4         | 2.07%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 4         | 2.07%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 3         | 1.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 3         | 1.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 3         | 1.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 3         | 1.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.04%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 1.04%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 2         | 1.04%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 1.04%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 2         | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 2         | 1.04%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 1.04%   |
| Intel Core i5-4200M CPU @ 2.50GHz               | 2         | 1.04%   |
| Intel Core i5-2450M CPU @ 2.50GHz               | 2         | 1.04%   |
| Intel Core i5 CPU M 480 @ 2.67GHz               | 2         | 1.04%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 2         | 1.04%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 2         | 1.04%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 1.04%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 1.04%   |
| Intel Core i3-2328M CPU @ 2.20GHz               | 2         | 1.04%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 1.04%   |
| Intel Celeron CPU 550 @ 2.00GHz                 | 2         | 1.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 1.04%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 2         | 1.04%   |
| AMD Ryzen 5 4500U with Radeon Graphics          | 2         | 1.04%   |
| AMD Athlon Silver 3050U with Radeon Graphics    | 2         | 1.04%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz          | 1         | 0.52%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.52%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 57        | 29.53%  |
| Intel Core i5      | 48        | 24.87%  |
| Intel Core i3      | 24        | 12.44%  |
| AMD Ryzen 5        | 12        | 6.22%   |
| Other              | 9         | 4.66%   |
| AMD Ryzen 7        | 9         | 4.66%   |
| Intel Celeron      | 6         | 3.11%   |
| Intel Atom         | 4         | 2.07%   |
| Intel Core 2 Duo   | 3         | 1.55%   |
| AMD A8             | 3         | 1.55%   |
| Intel Pentium      | 2         | 1.04%   |
| AMD Ryzen 9        | 2         | 1.04%   |
| AMD Ryzen 7 PRO    | 2         | 1.04%   |
| AMD Ryzen 3        | 2         | 1.04%   |
| AMD E1             | 2         | 1.04%   |
| AMD Athlon         | 2         | 1.04%   |
| Intel Pentium Dual | 1         | 0.52%   |
| Intel Genuine      | 1         | 0.52%   |
| Intel Celeron M    | 1         | 0.52%   |
| AMD E              | 1         | 0.52%   |
| AMD C-50           | 1         | 0.52%   |
| AMD A12            | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 94        | 48.7%   |
| 4       | 72        | 37.31%  |
| 8       | 10        | 5.18%   |
| 6       | 9         | 4.66%   |
| 1       | 6         | 3.11%   |
| 10      | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 193       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 164       | 84.97%  |
| 1       | 28        | 14.51%  |
| Unknown | 1         | 0.52%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 187       | 95.9%   |
| 64-bit         | 3         | 1.54%   |
| 32-bit         | 3         | 1.54%   |
| Unknown        | 2         | 1.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 17.26%  |
| 0x206a7    | 15        | 7.61%   |
| 0x306a9    | 12        | 6.09%   |
| 0x806ec    | 10        | 5.08%   |
| 0x806ea    | 10        | 5.08%   |
| 0x406e3    | 10        | 5.08%   |
| 0x40651    | 10        | 5.08%   |
| 0x806e9    | 8         | 4.06%   |
| 0x306d4    | 7         | 3.55%   |
| 0x08108109 | 7         | 3.55%   |
| 0x906ea    | 5         | 2.54%   |
| 0x306c3    | 5         | 2.54%   |
| 0x08108102 | 5         | 2.54%   |
| 0x806c1    | 4         | 2.03%   |
| 0x706e5    | 4         | 2.03%   |
| 0x20655    | 4         | 2.03%   |
| 0x806eb    | 3         | 1.52%   |
| 0x30678    | 3         | 1.52%   |
| 0x0a50000c | 3         | 1.52%   |
| 0xa0652    | 2         | 1.02%   |
| 0x906e9    | 2         | 1.02%   |
| 0x20652    | 2         | 1.02%   |
| 0x1067a    | 2         | 1.02%   |
| 0x10661    | 2         | 1.02%   |
| 0x08600106 | 2         | 1.02%   |
| 0x08600104 | 2         | 1.02%   |
| 0x05000029 | 2         | 1.02%   |
| 0x906a4    | 1         | 0.51%   |
| 0x806d1    | 1         | 0.51%   |
| 0x706a1    | 1         | 0.51%   |
| 0x6fd      | 1         | 0.51%   |
| 0x6e8      | 1         | 0.51%   |
| 0x6d8      | 1         | 0.51%   |
| 0x506e3    | 1         | 0.51%   |
| 0x406c4    | 1         | 0.51%   |
| 0x106ca    | 1         | 0.51%   |
| 0x106c2    | 1         | 0.51%   |
| 0x10676    | 1         | 0.51%   |
| 0x08608103 | 1         | 0.51%   |
| 0x08600102 | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 49        | 25.39%  |
| SandyBridge      | 16        | 8.29%   |
| Haswell          | 16        | 8.29%   |
| IvyBridge        | 15        | 7.77%   |
| Zen+             | 14        | 7.25%   |
| Skylake          | 12        | 6.22%   |
| Zen 2            | 7         | 3.63%   |
| Westmere         | 7         | 3.63%   |
| Broadwell        | 7         | 3.63%   |
| IceLake          | 6         | 3.11%   |
| Silvermont       | 5         | 2.59%   |
| Zen              | 4         | 2.07%   |
| TigerLake        | 4         | 2.07%   |
| Zen 3            | 3         | 1.55%   |
| Penryn           | 3         | 1.55%   |
| Excavator        | 3         | 1.55%   |
| Core             | 3         | 1.55%   |
| CometLake        | 3         | 1.55%   |
| Puma             | 2         | 1.04%   |
| Piledriver       | 2         | 1.04%   |
| P6               | 2         | 1.04%   |
| Bonnell          | 2         | 1.04%   |
| Bobcat           | 2         | 1.04%   |
| Unknown          | 2         | 1.04%   |
| Nehalem          | 1         | 0.52%   |
| Jaguar           | 1         | 0.52%   |
| Goldmont plus    | 1         | 0.52%   |
| Alderlake Hybrid | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 143       | 56.52%  |
| AMD                              | 62        | 24.51%  |
| Nvidia                           | 47        | 18.58%  |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 15        | 5.73%   |
| Intel UHD Graphics 620                                                                | 14        | 5.34%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 14        | 5.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 14        | 5.34%   |
| Intel HD Graphics 620                                                                 | 11        | 4.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 11        | 4.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 10        | 3.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 9         | 3.44%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 9         | 3.44%   |
| Intel HD Graphics 5500                                                                | 7         | 2.67%   |
| AMD Renoir                                                                            | 7         | 2.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 6         | 2.29%   |
| Intel Core Processor Integrated Graphics Controller                                   | 6         | 2.29%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 6         | 2.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 1.91%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 4         | 1.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 4         | 1.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 4         | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 4         | 1.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 1.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 4         | 1.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 1.15%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 3         | 1.15%   |
| Nvidia GM108M [GeForce MX110]                                                         | 3         | 1.15%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 3         | 1.15%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 3         | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 2         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.76%   |
| Nvidia GM108M [GeForce MX130]                                                         | 2         | 0.76%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 0.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 0.76%   |
| Intel Iris Plus Graphics G7                                                           | 2         | 0.76%   |
| Intel HD Graphics 630                                                                 | 2         | 0.76%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 2         | 0.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 2         | 0.76%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 2         | 0.76%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                     | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 86        | 44.56%  |
| Intel + Nvidia | 38        | 19.69%  |
| 1 x AMD        | 35        | 18.13%  |
| Intel + AMD    | 18        | 9.33%   |
| 2 x AMD        | 5         | 2.59%   |
| 1 x Nvidia     | 5         | 2.59%   |
| AMD + Nvidia   | 4         | 2.07%   |
| 2 x Intel      | 1         | 0.52%   |
| 1 x SiS        | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 166       | 84.69%  |
| Proprietary | 25        | 12.76%  |
| Unknown     | 5         | 2.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 55.28%  |
| 1.01-2.0   | 39        | 19.6%   |
| 0.01-0.5   | 25        | 12.56%  |
| 3.01-4.0   | 11        | 5.53%   |
| 0.51-1.0   | 8         | 4.02%   |
| 5.01-6.0   | 4         | 2.01%   |
| 7.01-8.0   | 1         | 0.5%    |
| 8.01-16.0  | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 46        | 20.91%  |
| BOE                 | 43        | 19.55%  |
| AU Optronics        | 35        | 15.91%  |
| Samsung Electronics | 30        | 13.64%  |
| LG Display          | 22        | 10%     |
| Goldstar            | 5         | 2.27%   |
| PANDA               | 4         | 1.82%   |
| Sharp               | 3         | 1.36%   |
| Hewlett-Packard     | 3         | 1.36%   |
| Sony                | 2         | 0.91%   |
| Lenovo              | 2         | 0.91%   |
| JRY                 | 2         | 0.91%   |
| HannStar            | 2         | 0.91%   |
| Dell                | 2         | 0.91%   |
| AOC                 | 2         | 0.91%   |
| Unknown             | 2         | 0.91%   |
| ViewSonic           | 1         | 0.45%   |
| Unknown (XXX)       | 1         | 0.45%   |
| TMX                 | 1         | 0.45%   |
| Panasonic           | 1         | 0.45%   |
| Mi                  | 1         | 0.45%   |
| LGD                 | 1         | 0.45%   |
| LG Philips          | 1         | 0.45%   |
| InnoLux Display     | 1         | 0.45%   |
| InfoVision          | 1         | 0.45%   |
| Hitachi             | 1         | 0.45%   |
| EXP                 | 1         | 0.45%   |
| DZX                 | 1         | 0.45%   |
| Apple               | 1         | 0.45%   |
| AGO                 | 1         | 0.45%   |
| Acer                | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 11        | 5%      |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 6         | 2.73%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 1.36%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 3         | 1.36%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 3         | 1.36%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 1.36%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.91%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.91%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch         | 2         | 0.91%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.91%   |
| JRY 236 FHD 165Hz JRY2380 1920x1080 522x294mm 23.6-inch              | 2         | 0.91%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 2         | 0.91%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.91%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                 | 2         | 0.91%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 2         | 0.91%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 2         | 0.91%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 2         | 0.91%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.91%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 2         | 0.91%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                 | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch        | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch        | 2         | 0.91%   |
| Unknown                                                              | 2         | 0.91%   |
| ViewSonic VX2257 VSCB731 1920x1080 477x268mm 21.5-inch               | 1         | 0.45%   |
| Unknown (XXX) MS82PV XXX001A 1360x768 330x210mm 15.4-inch            | 1         | 0.45%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch              | 1         | 0.45%   |
| Sony TV SNYEF03 1600x900                                             | 1         | 0.45%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch | 1         | 0.45%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch              | 1         | 0.45%   |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 443x249mm 20.0-inch | 1         | 0.45%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch    | 1         | 0.45%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch    | 1         | 0.45%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 115       | 54.25%  |
| 1920x1080 (FHD)   | 63        | 29.72%  |
| 1600x900 (HD+)    | 6         | 2.83%   |
| 1360x768          | 4         | 1.89%   |
| 1280x800 (WXGA)   | 4         | 1.89%   |
| 3840x2160 (4K)    | 3         | 1.42%   |
| 1440x900 (WXGA+)  | 3         | 1.42%   |
| 3200x1800 (QHD+)  | 2         | 0.94%   |
| 1024x600          | 2         | 0.94%   |
| Unknown           | 2         | 0.94%   |
| 640x480           | 1         | 0.47%   |
| 3840x1080         | 1         | 0.47%   |
| 3200x2000         | 1         | 0.47%   |
| 2520x1680         | 1         | 0.47%   |
| 2160x1440         | 1         | 0.47%   |
| 1920x1200 (WUXGA) | 1         | 0.47%   |
| 1280x720 (HD)     | 1         | 0.47%   |
| 1024x768 (XGA)    | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 107       | 49.08%  |
| 13      | 37        | 16.97%  |
| 14      | 27        | 12.39%  |
| 23      | 10        | 4.59%   |
| 17      | 6         | 2.75%   |
| 18      | 4         | 1.83%   |
| 21      | 3         | 1.38%   |
| 11      | 3         | 1.38%   |
| Unknown | 3         | 1.38%   |
| 72      | 2         | 0.92%   |
| 12      | 2         | 0.92%   |
| 10      | 2         | 0.92%   |
| 84      | 1         | 0.46%   |
| 60      | 1         | 0.46%   |
| 54      | 1         | 0.46%   |
| 48      | 1         | 0.46%   |
| 46      | 1         | 0.46%   |
| 39      | 1         | 0.46%   |
| 31      | 1         | 0.46%   |
| 27      | 1         | 0.46%   |
| 24      | 1         | 0.46%   |
| 20      | 1         | 0.46%   |
| 19      | 1         | 0.46%   |
| 16      | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 162       | 75%     |
| 201-300     | 13        | 6.02%   |
| 501-600     | 12        | 5.56%   |
| 401-500     | 9         | 4.17%   |
| 351-400     | 8         | 3.7%    |
| 1001-1500   | 4         | 1.85%   |
| 1501-2000   | 3         | 1.39%   |
| Unknown     | 3         | 1.39%   |
| 801-900     | 1         | 0.46%   |
| 601-700     | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 172       | 89.58%  |
| 16/10   | 12        | 6.25%   |
| 4/3     | 3         | 1.56%   |
| Unknown | 3         | 1.56%   |
| 3/2     | 2         | 1.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 107       | 49.08%  |
| 81-90          | 58        | 26.61%  |
| 201-250        | 13        | 5.96%   |
| More than 1000 | 6         | 2.75%   |
| 71-80          | 6         | 2.75%   |
| 151-200        | 4         | 1.83%   |
| 121-130        | 4         | 1.83%   |
| 51-60          | 3         | 1.38%   |
| 141-150        | 3         | 1.38%   |
| Unknown        | 3         | 1.38%   |
| 41-50          | 2         | 0.92%   |
| 131-140        | 2         | 0.92%   |
| 501-1000       | 2         | 0.92%   |
| 61-70          | 1         | 0.46%   |
| 351-500        | 1         | 0.46%   |
| 301-350        | 1         | 0.46%   |
| 111-120        | 1         | 0.46%   |
| 91-100         | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 114       | 53.27%  |
| 121-160       | 55        | 25.7%   |
| 51-100        | 28        | 13.08%  |
| 1-50          | 7         | 3.27%   |
| 161-240       | 4         | 1.87%   |
| More than 240 | 3         | 1.4%    |
| Unknown       | 3         | 1.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 158       | 79.8%   |
| 2     | 33        | 16.67%  |
| 0     | 6         | 3.03%   |
| 3     | 1         | 0.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 126       | 41.31%  |
| Intel                            | 70        | 22.95%  |
| Qualcomm Atheros                 | 58        | 19.02%  |
| Broadcom                         | 13        | 4.26%   |
| TP-Link                          | 7         | 2.3%    |
| Ralink                           | 5         | 1.64%   |
| Marvell Technology Group         | 4         | 1.31%   |
| MediaTek                         | 3         | 0.98%   |
| ASIX Electronics                 | 3         | 0.98%   |
| Xiaomi                           | 2         | 0.66%   |
| Samsung Electronics              | 2         | 0.66%   |
| Ralink Technology                | 2         | 0.66%   |
| Motorola PCS                     | 2         | 0.66%   |
| ICS Advent                       | 2         | 0.66%   |
| T & A Mobile Phones              | 1         | 0.33%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Microsoft                        | 1         | 0.33%   |
| Lenovo                           | 1         | 0.33%   |
| Broadcom Limited                 | 1         | 0.33%   |
| Apple                            | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 85        | 22.85%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 5.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 22        | 5.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 3.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 2.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.61%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.34%   |
| Intel Wireless 8260                                                     | 5         | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.34%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 1.08%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 1.08%   |
| Intel Wireless 7260                                                     | 4         | 1.08%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 3         | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.81%   |
| Intel WiFi Link 5100                                                    | 3         | 0.81%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.54%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 2         | 0.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.54%   |
| Motorola PCS motorola one 5G ace                                        | 2         | 0.54%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 0.54%   |
| Intel Wireless 7265                                                     | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 68        | 34.17%  |
| Qualcomm Atheros      | 52        | 26.13%  |
| Realtek Semiconductor | 51        | 25.63%  |
| Broadcom              | 11        | 5.53%   |
| TP-Link               | 6         | 3.02%   |
| Ralink                | 5         | 2.51%   |
| MediaTek              | 3         | 1.51%   |
| Ralink Technology     | 2         | 1.01%   |
| Broadcom Limited      | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 11.06%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 7.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 6.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 4.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 3.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 3.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 3.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 3.02%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 3.02%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.51%   |
| Intel Wireless 8260                                                     | 5         | 2.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.51%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 2.01%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 2.01%   |
| Intel Wireless 7260                                                     | 4         | 2.01%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 3         | 1.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.51%   |
| Intel WiFi Link 5100                                                    | 3         | 1.51%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.01%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.01%   |
| Intel Wireless 7265                                                     | 2         | 1.01%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.01%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.01%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.01%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.01%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                 | 1         | 0.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 112       | 65.12%  |
| Intel                            | 24        | 13.95%  |
| Qualcomm Atheros                 | 12        | 6.98%   |
| Marvell Technology Group         | 4         | 2.33%   |
| Broadcom                         | 3         | 1.74%   |
| ASIX Electronics                 | 3         | 1.74%   |
| Xiaomi                           | 2         | 1.16%   |
| Samsung Electronics              | 2         | 1.16%   |
| Motorola PCS                     | 2         | 1.16%   |
| ICS Advent                       | 2         | 1.16%   |
| TP-Link                          | 1         | 0.58%   |
| T & A Mobile Phones              | 1         | 0.58%   |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |
| Microsoft                        | 1         | 0.58%   |
| Lenovo                           | 1         | 0.58%   |
| Apple                            | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 85        | 49.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 22        | 12.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 3.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.31%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 2.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.16%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.16%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 1.16%   |
| Motorola PCS motorola one 5G ace                                               | 2         | 1.16%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.16%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.16%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.16%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.16%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.16%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 2         | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.16%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.58%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                                   | 1         | 0.58%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.58%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.58%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.58%   |
| Microsoft Ethernet Adapter                                                     | 1         | 0.58%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.58%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.58%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.58%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.58%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.58%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.58%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.58%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.58%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.58%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 191       | 53.5%   |
| Ethernet | 166       | 46.5%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 150       | 72.82%  |
| Ethernet | 56        | 27.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 150       | 77.72%  |
| 1     | 41        | 21.24%  |
| 0     | 2         | 1.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 161       | 81.31%  |
| Yes  | 37        | 18.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 31.68%  |
| Realtek Semiconductor           | 34        | 21.12%  |
| Qualcomm Atheros Communications | 29        | 18.01%  |
| IMC Networks                    | 11        | 6.83%   |
| Lite-On Technology              | 10        | 6.21%   |
| Toshiba                         | 5         | 3.11%   |
| Ralink                          | 4         | 2.48%   |
| Broadcom                        | 4         | 2.48%   |
| Foxconn / Hon Hai               | 3         | 1.86%   |
| Hewlett-Packard                 | 2         | 1.24%   |
| Dell                            | 2         | 1.24%   |
| Cambridge Silicon Radio         | 2         | 1.24%   |
| Realtek                         | 1         | 0.62%   |
| Foxconn International           | 1         | 0.62%   |
| Apple                           | 1         | 0.62%   |
| Alps Electric                   | 1         | 0.62%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 19        | 11.8%   |
| Realtek  Bluetooth 4.2 Adapter                      | 17        | 10.56%  |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 10.56%  |
| Realtek Bluetooth Radio                             | 15        | 9.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 6.83%   |
| Intel Bluetooth Device                              | 9         | 5.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 3.11%   |
| Lite-On Bluetooth Device                            | 5         | 3.11%   |
| Ralink RT3290 Bluetooth                             | 4         | 2.48%   |
| IMC Networks Bluetooth Radio                        | 4         | 2.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.86%   |
| Lite-On Bluetooth Radio                             | 3         | 1.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.86%   |
| Intel AX200 Bluetooth                               | 3         | 1.86%   |
| IMC Networks Wireless_Device                        | 3         | 1.86%   |
| IMC Networks Bluetooth Device                       | 3         | 1.86%   |
| Toshiba Bluetooth Device                            | 2         | 1.24%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.24%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.24%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.24%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.24%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.24%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.62%   |
| Toshiba BCM43142A0                                  | 1         | 0.62%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.62%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.62%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.62%   |
| Realtek Bluetooth Radio                             | 1         | 0.62%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.62%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.62%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.62%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.62%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.62%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.62%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.62%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 150       | 67.57%  |
| AMD                              | 44        | 19.82%  |
| Nvidia                           | 20        | 9.01%   |
| Generalplus Technology           | 2         | 0.9%    |
| C-Media Electronics              | 2         | 0.9%    |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Razer USA                        | 1         | 0.45%   |
| Pixart Imaging                   | 1         | 0.45%   |
| Hewlett-Packard                  | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 36        | 12.77%  |
| AMD Family 17h/19h HD Audio Controller                                     | 29        | 10.28%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 7.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 18        | 6.38%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 3.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 3.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 3.9%    |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 3.55%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 3.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 2.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 2.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 2.48%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.77%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.42%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.06%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.71%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.71%   |
| Generalplus Technology USB Audio Device                                    | 2         | 0.71%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.71%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.71%   |
| AMD High Definition Audio Controller                                       | 2         | 0.71%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.35%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1         | 0.35%   |
| Pixart Imaging Multimedia audio controller                                 | 1         | 0.35%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 48        | 32.65%  |
| SK hynix            | 30        | 20.41%  |
| Micron Technology   | 24        | 16.33%  |
| Kingston            | 18        | 12.24%  |
| Unknown             | 8         | 5.44%   |
| Ramaxel Technology  | 7         | 4.76%   |
| Team                | 3         | 2.04%   |
| Hewlett-Packard     | 2         | 1.36%   |
| Crucial             | 2         | 1.36%   |
| Unknown (ABCD)      | 1         | 0.68%   |
| Patriot             | 1         | 0.68%   |
| Goldkey             | 1         | 0.68%   |
| CSX                 | 1         | 0.68%   |
| Corsair             | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 3.82%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 3.18%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 3.18%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.55%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.91%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 1.91%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.91%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.91%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 1.91%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.91%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.91%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 1.91%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 1.27%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 1.27%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.27%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.27%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.27%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.27%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.27%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.27%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.27%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.27%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.27%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.27%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 1.27%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.27%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s          | 2         | 1.27%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 0.64%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.64%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.64%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.64%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.64%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 1         | 0.64%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 0.64%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 0.64%   |
| Unknown RAM Module 1GB SODIMM 800MT/s                            | 1         | 0.64%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.64%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 57        | 52.29%  |
| DDR3    | 37        | 33.94%  |
| LPDDR4  | 6         | 5.5%    |
| LPDDR3  | 3         | 2.75%   |
| DDR2    | 3         | 2.75%   |
| SDRAM   | 2         | 1.83%   |
| Unknown | 1         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 103       | 94.5%   |
| Row Of Chips | 6         | 5.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 54        | 41.86%  |
| 4096  | 50        | 38.76%  |
| 2048  | 11        | 8.53%   |
| 16384 | 9         | 6.98%   |
| 32768 | 2         | 1.55%   |
| 1024  | 2         | 1.55%   |
| 512   | 1         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 41        | 31.78%  |
| 1600    | 29        | 22.48%  |
| 3200    | 23        | 17.83%  |
| 2400    | 7         | 5.43%   |
| 3266    | 6         | 4.65%   |
| 1333    | 5         | 3.88%   |
| 1334    | 4         | 3.1%    |
| 2133    | 3         | 2.33%   |
| Unknown | 3         | 2.33%   |
| 1867    | 2         | 1.55%   |
| 1067    | 2         | 1.55%   |
| 4199    | 1         | 0.78%   |
| 2933    | 1         | 0.78%   |
| 800     | 1         | 0.78%   |
| 533     | 1         | 0.78%   |

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
| Chicony Electronics                    | 42        | 22.34%  |
| IMC Networks                           | 21        | 11.17%  |
| Acer                                   | 19        | 10.11%  |
| Realtek Semiconductor                  | 15        | 7.98%   |
| Microdia                               | 13        | 6.91%   |
| Syntek                                 | 11        | 5.85%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 5.85%   |
| Sunplus Innovation Technology          | 10        | 5.32%   |
| Quanta                                 | 10        | 5.32%   |
| Lite-On Technology                     | 10        | 5.32%   |
| Suyin                                  | 8         | 4.26%   |
| Importek                               | 4         | 2.13%   |
| Sonix Technology                       | 3         | 1.6%    |
| Samsung Electronics                    | 2         | 1.06%   |
| Ricoh                                  | 2         | 1.06%   |
| Luxvisions Innotech Limited            | 2         | 1.06%   |
| Alcor Micro                            | 2         | 1.06%   |
| Logitech                               | 1         | 0.53%   |
| Apple                                  | 1         | 0.53%   |
| ANYKA                                  | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 8         | 4.23%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 7         | 3.7%    |
| Acer Integrated Camera                                                     | 7         | 3.7%    |
| Microdia Integrated_Webcam_HD                                              | 5         | 2.65%   |
| Chicony EasyCamera                                                         | 5         | 2.65%   |
| Lite-On Integrated Camera                                                  | 4         | 2.12%   |
| IMC Networks Integrated Camera                                             | 4         | 2.12%   |
| Chicony Integrated Camera                                                  | 4         | 2.12%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 2.12%   |
| Chicony HD WebCam                                                          | 4         | 2.12%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 1.59%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 3         | 1.59%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 1.59%   |
| Lite-On HP HD Camera                                                       | 3         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 1.59%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.59%   |
| Chicony HP Truevision HD                                                   | 3         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.59%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 1.06%   |
| Sunplus Integrated Webcam                                                  | 2         | 1.06%   |
| Samsung Galaxy A5 (MTP)                                                    | 2         | 1.06%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 1.06%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 1.06%   |
| Realtek Integrated Webcam                                                  | 2         | 1.06%   |
| Realtek HP Wide Vision HD Camera                                           | 2         | 1.06%   |
| Quanta HP Webcam                                                           | 2         | 1.06%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 1.06%   |
| IMC Networks HP TrueVision HD Camera                                       | 2         | 1.06%   |
| IMC Networks HD Camera                                                     | 2         | 1.06%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 1.06%   |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 1.06%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.06%   |
| Chicony HP Webcam                                                          | 2         | 1.06%   |
| Chicony HP HD Camera                                                       | 2         | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 1.06%   |
| Alcor Micro USB 2.0 Camera                                                 | 2         | 1.06%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 1.06%   |
| Acer EasyCamera                                                            | 2         | 1.06%   |
| Syntek USB Video Device                                                    | 1         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 48.78%  |
| Synaptics                  | 11        | 26.83%  |
| Shenzhen Goodix Technology | 5         | 12.2%   |
| Elan Microelectronics      | 3         | 7.32%   |
| STMicroelectronics         | 1         | 2.44%   |
| AuthenTec                  | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 7         | 17.07%  |
| Validity Sensors VFS5011 Fingerprint Reader                | 6         | 14.63%  |
| Synaptics  WBDI                                            | 4         | 9.76%   |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 7.32%   |
| Validity Sensors Fingerprint scanner                       | 2         | 4.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.88%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 4.88%   |
| Elan ELAN:Fingerprint                                      | 2         | 4.88%   |
| Unknown                                                    | 2         | 4.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.44%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.44%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.44%   |
| Validity Sensors Synaptics WBDI                            | 1         | 2.44%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 2.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.44%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.44%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.44%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.44%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Upek        | 3         | 33.33%  |
| Broadcom    | 3         | 33.33%  |
| Alcor Micro | 2         | 22.22%  |
| O2 Micro    | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 22.22%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |
| Broadcom 5880                                                                | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 120       | 60.61%  |
| 1     | 65        | 32.83%  |
| 2     | 11        | 5.56%   |
| 3     | 2         | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 41        | 46.07%  |
| Graphics card            | 16        | 17.98%  |
| Net/wireless             | 9         | 10.11%  |
| Chipcard                 | 9         | 10.11%  |
| Bluetooth                | 5         | 5.62%   |
| Storage                  | 2         | 2.25%   |
| Multimedia controller    | 2         | 2.25%   |
| Card reader              | 2         | 2.25%   |
| Camera                   | 2         | 2.25%   |
| Communication controller | 1         | 1.12%   |

