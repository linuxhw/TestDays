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

Total: 226

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | S550CA                      | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| MSI        | GL65 Leopard 10SEK          | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| ASUSTek    | S550CA                      | [93807824df](https://linux-hardware.org/?probe=93807824df) | Jun 28, 2022 |
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
| ASUSTek    | S550CA                      | [c87c7a989a](https://linux-hardware.org/?probe=c87c7a989a) | Jun 09, 2022 |
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
| Ubuntu 20.04                 | 32        | 19.16%  |
| Ubuntu 18.04                 | 9         | 5.39%   |
| Zorin 15                     | 6         | 3.59%   |
| Ubuntu 19.10                 | 5         | 2.99%   |
| Arch                         | 5         | 2.99%   |
| Xubuntu 20.04                | 4         | 2.4%    |
| Ubuntu 21.04                 | 4         | 2.4%    |
| Pop!_OS 21.10                | 4         | 2.4%    |
| OpenMandriva 4.3             | 4         | 2.4%    |
| Manjaro                      | 4         | 2.4%    |
| Linux Mint 20.3              | 4         | 2.4%    |
| Debian 11                    | 4         | 2.4%    |
| Ubuntu 22.04                 | 3         | 1.8%    |
| Ubuntu 19.04                 | 3         | 1.8%    |
| Pop!_OS 20.10                | 3         | 1.8%    |
| OpenMandriva 4.2             | 3         | 1.8%    |
| Manjaro 20.1                 | 3         | 1.8%    |
| KDE neon 20.04               | 3         | 1.8%    |
| Elementary 5.1.7             | 3         | 1.8%    |
| Debian 10                    | 3         | 1.8%    |
| Arch Rolling                 | 3         | 1.8%    |
| ROSA R9                      | 2         | 1.2%    |
| ROSA R10                     | 2         | 1.2%    |
| Pop!_OS 22.04                | 2         | 1.2%    |
| Pop!_OS 20.04                | 2         | 1.2%    |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.2%    |
| Linux Mint 20                | 2         | 1.2%    |
| Kubuntu 20.04                | 2         | 1.2%    |
| Fedora 35                    | 2         | 1.2%    |
| Fedora 34                    | 2         | 1.2%    |
| Fedora 33                    | 2         | 1.2%    |
| Fedora 32                    | 2         | 1.2%    |
| CentOS 8                     | 2         | 1.2%    |
| Zorin 16                     | 1         | 0.6%    |
| Void Linux                   | 1         | 0.6%    |
| Ubuntu MATE 20.04            | 1         | 0.6%    |
| Ubuntu MATE 18.04            | 1         | 0.6%    |
| Ubuntu 21.10                 | 1         | 0.6%    |
| Ubuntu 18.10                 | 1         | 0.6%    |
| ROSA R11.1                   | 1         | 0.6%    |
| ROSA R11                     | 1         | 0.6%    |
| Pop!_OS 21.04                | 1         | 0.6%    |
| Peppermint 10                | 1         | 0.6%    |
| Parrot 5.0                   | 1         | 0.6%    |
| MX 21                        | 1         | 0.6%    |
| Manjaro 21.2rc               | 1         | 0.6%    |
| Manjaro 21.2.6               | 1         | 0.6%    |
| Manjaro 20.2                 | 1         | 0.6%    |
| Lubuntu 19.10                | 1         | 0.6%    |
| Lubuntu 18.04                | 1         | 0.6%    |
| LMDE 5                       | 1         | 0.6%    |
| Linux Mint 20.2              | 1         | 0.6%    |
| Linux Mint 20.1              | 1         | 0.6%    |
| Linux Mint 19.1              | 1         | 0.6%    |
| Laxer OS V0.2                | 1         | 0.6%    |
| Kali 2021.4                  | 1         | 0.6%    |
| Fedora 36                    | 1         | 0.6%    |
| Endless 3.7.4                | 1         | 0.6%    |
| Endless 3.6.1                | 1         | 0.6%    |
| Endless 3.4.3-nexthw1        | 1         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 58        | 35.15%  |
| Pop!_OS      | 12        | 7.27%   |
| Manjaro      | 10        | 6.06%   |
| Linux Mint   | 9         | 5.45%   |
| Fedora       | 9         | 5.45%   |
| Arch         | 9         | 5.45%   |
| Zorin        | 7         | 4.24%   |
| OpenMandriva | 7         | 4.24%   |
| Debian       | 7         | 4.24%   |
| ROSA         | 5         | 3.03%   |
| Xubuntu      | 4         | 2.42%   |
| Elementary   | 4         | 2.42%   |
| KDE neon     | 3         | 1.82%   |
| Endless      | 3         | 1.82%   |
| Ubuntu MATE  | 2         | 1.21%   |
| openSUSE     | 2         | 1.21%   |
| Lubuntu      | 2         | 1.21%   |
| Kubuntu      | 2         | 1.21%   |
| CentOS       | 2         | 1.21%   |
| Void Linux   | 1         | 0.61%   |
| Peppermint   | 1         | 0.61%   |
| Parrot       | 1         | 0.61%   |
| MX           | 1         | 0.61%   |
| LMDE         | 1         | 0.61%   |
| Laxer OS     | 1         | 0.61%   |
| Kali         | 1         | 0.61%   |
| ArcoLinux    | 1         | 0.61%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.13.0-40-generic               | 5         | 2.82%   |
| 5.4.0-42-generic                | 4         | 2.26%   |
| 5.16.7-desktop-1omv4003         | 4         | 2.26%   |
| 5.4.0-26-generic                | 3         | 1.69%   |
| 5.3.0-40-generic                | 3         | 1.69%   |
| 5.13.0-51-generic               | 3         | 1.69%   |
| 5.11.0-25-generic               | 3         | 1.69%   |
| 5.10.0-13-amd64                 | 3         | 1.69%   |
| 5.8.0-44-generic                | 2         | 1.13%   |
| 5.4.0-7642-generic              | 2         | 1.13%   |
| 5.4.0-66-generic                | 2         | 1.13%   |
| 5.4.0-65-generic                | 2         | 1.13%   |
| 5.4.0-58-generic                | 2         | 1.13%   |
| 5.4.0-54-generic                | 2         | 1.13%   |
| 5.4.0-39-generic                | 2         | 1.13%   |
| 5.4.0-33-generic                | 2         | 1.13%   |
| 5.4.0-28-generic                | 2         | 1.13%   |
| 5.4.0-109-generic               | 2         | 1.13%   |
| 5.3.0-42-generic                | 2         | 1.13%   |
| 5.3.0-23-generic                | 2         | 1.13%   |
| 5.17.5-arch1-1                  | 2         | 1.13%   |
| 5.16.19-76051619-generic        | 2         | 1.13%   |
| 5.15.49-1-lts                   | 2         | 1.13%   |
| 5.15.0-25-generic               | 2         | 1.13%   |
| 5.13.0-30-generic               | 2         | 1.13%   |
| 5.11.0-7614-generic             | 2         | 1.13%   |
| 5.10.14-desktop-1omv4002        | 2         | 1.13%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 1.13%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 1.13%   |
| 5.9.16-1-MANJARO                | 1         | 0.56%   |
| 5.9.11-3-MANJARO                | 1         | 0.56%   |
| 5.8.6-1-MANJARO                 | 1         | 0.56%   |
| 5.8.4-200.fc32.x86_64           | 1         | 0.56%   |
| 5.8.11-1-MANJARO                | 1         | 0.56%   |
| 5.8.0-63-generic                | 1         | 0.56%   |
| 5.8.0-55-generic                | 1         | 0.56%   |
| 5.8.0-50-generic                | 1         | 0.56%   |
| 5.8.0-43-generic                | 1         | 0.56%   |
| 5.8.0-33-generic                | 1         | 0.56%   |
| 5.7.4-arch1-1                   | 1         | 0.56%   |
| 5.7.17-2-MANJARO                | 1         | 0.56%   |
| 5.6.6-300.fc32.x86_64           | 1         | 0.56%   |
| 5.6.14-arch1-1                  | 1         | 0.56%   |
| 5.4.64-1-MANJARO                | 1         | 0.56%   |
| 5.4.61-1-lts                    | 1         | 0.56%   |
| 5.4.0-96-generic                | 1         | 0.56%   |
| 5.4.0-81-generic                | 1         | 0.56%   |
| 5.4.0-73-generic                | 1         | 0.56%   |
| 5.4.0-72-generic                | 1         | 0.56%   |
| 5.4.0-70-generic                | 1         | 0.56%   |
| 5.4.0-48-generic                | 1         | 0.56%   |
| 5.4.0-47-generic                | 1         | 0.56%   |
| 5.4.0-40-generic                | 1         | 0.56%   |
| 5.4.0-37-generic                | 1         | 0.56%   |
| 5.4.0-31-generic                | 1         | 0.56%   |
| 5.4.0-14-generic                | 1         | 0.56%   |
| 5.4.0-117-generic               | 1         | 0.56%   |
| 5.4.0-105-generic               | 1         | 0.56%   |
| 5.3.0-46-generic                | 1         | 0.56%   |
| 5.3.0-45-generic                | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 21.05%  |
| 5.11.0  | 14        | 8.19%   |
| 5.3.0   | 12        | 7.02%   |
| 5.13.0  | 12        | 7.02%   |
| 5.8.0   | 7         | 4.09%   |
| 5.0.0   | 7         | 4.09%   |
| 4.15.0  | 7         | 4.09%   |
| 5.10.0  | 6         | 3.51%   |
| 4.18.0  | 6         | 3.51%   |
| 5.16.7  | 4         | 2.34%   |
| 5.15.0  | 4         | 2.34%   |
| 5.17.5  | 3         | 1.75%   |
| 4.9.60  | 3         | 1.75%   |
| 5.16.19 | 2         | 1.17%   |
| 5.15.49 | 2         | 1.17%   |
| 5.12.10 | 2         | 1.17%   |
| 5.10.14 | 2         | 1.17%   |
| 4.9.20  | 2         | 1.17%   |
| 4.19.0  | 2         | 1.17%   |
| 5.9.16  | 1         | 0.58%   |
| 5.9.11  | 1         | 0.58%   |
| 5.8.6   | 1         | 0.58%   |
| 5.8.4   | 1         | 0.58%   |
| 5.8.11  | 1         | 0.58%   |
| 5.7.4   | 1         | 0.58%   |
| 5.7.17  | 1         | 0.58%   |
| 5.6.6   | 1         | 0.58%   |
| 5.6.14  | 1         | 0.58%   |
| 5.4.64  | 1         | 0.58%   |
| 5.4.61  | 1         | 0.58%   |
| 5.18.6  | 1         | 0.58%   |
| 5.17.9  | 1         | 0.58%   |
| 5.17.7  | 1         | 0.58%   |
| 5.17.6  | 1         | 0.58%   |
| 5.17.1  | 1         | 0.58%   |
| 5.16.0  | 1         | 0.58%   |
| 5.15.8  | 1         | 0.58%   |
| 5.15.6  | 1         | 0.58%   |
| 5.15.33 | 1         | 0.58%   |
| 5.15.2  | 1         | 0.58%   |
| 5.15.18 | 1         | 0.58%   |
| 5.15.16 | 1         | 0.58%   |
| 5.15.15 | 1         | 0.58%   |
| 5.15.11 | 1         | 0.58%   |
| 5.14.9  | 1         | 0.58%   |
| 5.14.13 | 1         | 0.58%   |
| 5.14.11 | 1         | 0.58%   |
| 5.14.0  | 1         | 0.58%   |
| 5.13.19 | 1         | 0.58%   |
| 5.12.7  | 1         | 0.58%   |
| 5.12.4  | 1         | 0.58%   |
| 5.11.12 | 1         | 0.58%   |
| 5.10.7  | 1         | 0.58%   |
| 5.10.17 | 1         | 0.58%   |
| 5.1.3   | 1         | 0.58%   |
| 4.9.76  | 1         | 0.58%   |
| 4.16.0  | 1         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 38        | 22.62%  |
| 5.11    | 15        | 8.93%   |
| 5.15    | 14        | 8.33%   |
| 5.13    | 13        | 7.74%   |
| 5.3     | 12        | 7.14%   |
| 5.8     | 10        | 5.95%   |
| 5.10    | 10        | 5.95%   |
| 5.17    | 7         | 4.17%   |
| 5.16    | 7         | 4.17%   |
| 5.0     | 7         | 4.17%   |
| 4.15    | 7         | 4.17%   |
| 4.18    | 6         | 3.57%   |
| 5.12    | 4         | 2.38%   |
| 4.9     | 4         | 2.38%   |
| 5.14    | 3         | 1.79%   |
| 5.9     | 2         | 1.19%   |
| 5.7     | 2         | 1.19%   |
| 5.6     | 2         | 1.19%   |
| 4.19    | 2         | 1.19%   |
| 5.18    | 1         | 0.6%    |
| 5.1     | 1         | 0.6%    |
| 4.16    | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 151       | 94.97%  |
| i686   | 8         | 5.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 83        | 50.61%  |
| KDE5            | 16        | 9.76%   |
| XFCE            | 15        | 9.15%   |
| Unknown         | 15        | 9.15%   |
| X-Cinnamon      | 7         | 4.27%   |
| KDE             | 6         | 3.66%   |
| MATE            | 5         | 3.05%   |
| Pantheon        | 4         | 2.44%   |
| KDE4            | 4         | 2.44%   |
| LXDE            | 2         | 1.22%   |
| i3              | 2         | 1.22%   |
| Unity           | 1         | 0.61%   |
| spectrwm        | 1         | 0.61%   |
| LXQt            | 1         | 0.61%   |
| GNOME Flashback | 1         | 0.61%   |
| Budgie          | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 126       | 77.78%  |
| Wayland | 22        | 13.58%  |
| Unknown | 13        | 8.02%   |
| Tty     | 1         | 0.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 82        | 50%     |
| GDM     | 32        | 19.51%  |
| LightDM | 18        | 10.98%  |
| SDDM    | 15        | 9.15%   |
| GDM3    | 10        | 6.1%    |
| KDM     | 4         | 2.44%   |
| TDM     | 2         | 1.22%   |
| XDM     | 1         | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_PE   | 78        | 47.85%  |
| en_US   | 41        | 25.15%  |
| es_ES   | 17        | 10.43%  |
| Unknown | 16        | 9.82%   |
| C       | 3         | 1.84%   |
| it_IT   | 2         | 1.23%   |
| en_GB   | 2         | 1.23%   |
| fr_FR   | 1         | 0.61%   |
| es_CO   | 1         | 0.61%   |
| Default | 1         | 0.61%   |
| ca_ES   | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 90        | 55.9%   |
| BIOS | 71        | 44.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 133       | 82.1%   |
| Overlay | 9         | 5.56%   |
| Btrfs   | 7         | 4.32%   |
| Unknown | 7         | 4.32%   |
| Xfs     | 5         | 3.09%   |
| Ext3    | 1         | 0.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 94        | 58.02%  |
| GPT     | 55        | 33.95%  |
| MBR     | 13        | 8.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 142       | 89.31%  |
| Yes       | 17        | 10.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 92        | 57.86%  |
| Yes       | 67        | 42.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 45        | 28.48%  |
| Hewlett-Packard     | 42        | 26.58%  |
| Dell                | 18        | 11.39%  |
| ASUSTek Computer    | 17        | 10.76%  |
| Toshiba             | 12        | 7.59%   |
| Acer                | 9         | 5.7%    |
| Sony                | 4         | 2.53%   |
| MSI                 | 2         | 1.27%   |
| Samsung Electronics | 1         | 0.63%   |
| Razer               | 1         | 0.63%   |
| HUAWEI              | 1         | 0.63%   |
| efirstview          | 1         | 0.63%   |
| Compal              | 1         | 0.63%   |
| Chuwi               | 1         | 0.63%   |
| Apple               | 1         | 0.63%   |
| Advance             | 1         | 0.63%   |
| Unknown             | 1         | 0.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo V330-15IKB 81AX                                | 3         | 1.9%    |
| Lenovo V310-15ISK 80SY                                | 3         | 1.9%    |
| HP Pavilion Laptop 15-cw1xxx                          | 3         | 1.9%    |
| Lenovo IdeaPad S540-14API 81NH                        | 2         | 1.27%   |
| Lenovo IdeaPad S145-15IWL 81MV                        | 2         | 1.27%   |
| Lenovo IdeaPad 330S-14IKB 81F4                        | 2         | 1.27%   |
| Lenovo IdeaPad 3 14ADA05 81W0                         | 2         | 1.27%   |
| HP ProBook 645 G4                                     | 2         | 1.27%   |
| HP Laptop 15-ef1xxx                                   | 2         | 1.27%   |
| HP 450                                                | 2         | 1.27%   |
| HP 14                                                 | 2         | 1.27%   |
| Dell XPS 13 9360                                      | 2         | 1.27%   |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV              | 2         | 1.27%   |
| Toshiba Satellite P755                                | 1         | 0.63%   |
| Toshiba Satellite L855                                | 1         | 0.63%   |
| Toshiba Satellite L45-B                               | 1         | 0.63%   |
| Toshiba Satellite L35                                 | 1         | 0.63%   |
| Toshiba Satellite E205                                | 1         | 0.63%   |
| Toshiba Satellite C845                                | 1         | 0.63%   |
| Toshiba Satellite C655D                               | 1         | 0.63%   |
| Toshiba Satellite C645                                | 1         | 0.63%   |
| Toshiba Satellite C55-B                               | 1         | 0.63%   |
| Toshiba Satellite A665                                | 1         | 0.63%   |
| Toshiba QOSMIO X775                                   | 1         | 0.63%   |
| Toshiba NB505                                         | 1         | 0.63%   |
| Sony VPCEC2JFX                                        | 1         | 0.63%   |
| Sony VGN-FW56M                                        | 1         | 0.63%   |
| Sony VGN-FW170J                                       | 1         | 0.63%   |
| Sony SVF15A17CLB                                      | 1         | 0.63%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.63%   |
| Razer Blade                                           | 1         | 0.63%   |
| MSI Prestige 14 A10SC                                 | 1         | 0.63%   |
| MSI GL65 Leopard 10SEK                                | 1         | 0.63%   |
| Lenovo Yoga 2 11 20332                                | 1         | 0.63%   |
| Lenovo Y70-70 Touch 80DU                              | 1         | 0.63%   |
| Lenovo V310-14ISK 80SX                                | 1         | 0.63%   |
| Lenovo V15-IIL 82C5                                   | 1         | 0.63%   |
| Lenovo V14-ARE 82DQ                                   | 1         | 0.63%   |
| Lenovo ThinkPad X140e 20BLA00C00                      | 1         | 0.63%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9005MUS            | 1         | 0.63%   |
| Lenovo ThinkPad T60 1953D9U                           | 1         | 0.63%   |
| Lenovo ThinkPad T580 20LAS0XD00                       | 1         | 0.63%   |
| Lenovo ThinkPad T530 24296G9                          | 1         | 0.63%   |
| Lenovo ThinkPad T470 20HES0JQ00                       | 1         | 0.63%   |
| Lenovo ThinkPad T440 20B7A08500                       | 1         | 0.63%   |
| Lenovo ThinkPad T430s 23539KU                         | 1         | 0.63%   |
| Lenovo ThinkPad T430 2349LRS                          | 1         | 0.63%   |
| Lenovo ThinkPad P52 20MAS3X200                        | 1         | 0.63%   |
| Lenovo ThinkPad P50 20EQA09900                        | 1         | 0.63%   |
| Lenovo ThinkPad L460 20FVA0G400                       | 1         | 0.63%   |
| Lenovo ThinkPad L15 Gen 1 20U3S0AK00                  | 1         | 0.63%   |
| Lenovo ThinkPad E15 Gen 2 20TES2MF00                  | 1         | 0.63%   |
| Lenovo Legion Y540-15IRH-PG0 81SY                     | 1         | 0.63%   |
| Lenovo Legion Y540-15IRH 81SX                         | 1         | 0.63%   |
| Lenovo Legion 5 17ITH6H 82JM                          | 1         | 0.63%   |
| Lenovo IdeaPad S340-15IML 81NA                        | 1         | 0.63%   |
| Lenovo IdeaPad S340-15API 81NC                        | 1         | 0.63%   |
| Lenovo IdeaPad S145-14IWL 81MU                        | 1         | 0.63%   |
| Lenovo IdeaPad 330-15ARR 81D2                         | 1         | 0.63%   |
| Lenovo G50-70 20351                                   | 1         | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 14        | 8.86%   |
| HP Pavilion       | 13        | 8.23%   |
| Lenovo IdeaPad    | 12        | 7.59%   |
| Toshiba Satellite | 10        | 6.33%   |
| Acer Aspire       | 7         | 4.43%   |
| HP ProBook        | 6         | 3.8%    |
| Dell Latitude     | 6         | 3.8%    |
| Dell Inspiron     | 6         | 3.8%    |
| HP Laptop         | 5         | 3.16%   |
| ASUS VivoBook     | 5         | 3.16%   |
| Lenovo V330-15IKB | 3         | 1.9%    |
| Lenovo V310-15ISK | 3         | 1.9%    |
| Lenovo Legion     | 3         | 1.9%    |
| HP ZBook          | 2         | 1.27%   |
| HP ENVY           | 2         | 1.27%   |
| HP 450            | 2         | 1.27%   |
| HP 240            | 2         | 1.27%   |
| HP 14             | 2         | 1.27%   |
| Dell XPS          | 2         | 1.27%   |
| ASUS ROG          | 2         | 1.27%   |
| ASUS ASUS         | 2         | 1.27%   |
| Toshiba QOSMIO    | 1         | 0.63%   |
| Toshiba NB505     | 1         | 0.63%   |
| Sony VPCEC2JFX    | 1         | 0.63%   |
| Sony VGN-FW56M    | 1         | 0.63%   |
| Sony VGN-FW170J   | 1         | 0.63%   |
| Sony SVF15A17CLB  | 1         | 0.63%   |
| Samsung 300E5EV   | 1         | 0.63%   |
| Razer Blade       | 1         | 0.63%   |
| MSI Prestige      | 1         | 0.63%   |
| MSI GL65          | 1         | 0.63%   |
| Lenovo Yoga       | 1         | 0.63%   |
| Lenovo Y70-70     | 1         | 0.63%   |
| Lenovo V310-14ISK | 1         | 0.63%   |
| Lenovo V15-IIL    | 1         | 0.63%   |
| Lenovo V14-ARE    | 1         | 0.63%   |
| Lenovo G50-70     | 1         | 0.63%   |
| Lenovo G480       | 1         | 0.63%   |
| Lenovo G475       | 1         | 0.63%   |
| Lenovo G400       | 1         | 0.63%   |
| Lenovo B50-80     | 1         | 0.63%   |
| HUAWEI NBLB-WAX9N | 1         | 0.63%   |
| HP Stream         | 1         | 0.63%   |
| HP Notebook       | 1         | 0.63%   |
| HP EliteBook      | 1         | 0.63%   |
| HP Compaq         | 1         | 0.63%   |
| HP 340            | 1         | 0.63%   |
| HP 250            | 1         | 0.63%   |
| HP 245            | 1         | 0.63%   |
| HP 1000           | 1         | 0.63%   |
| efirstview v01099 | 1         | 0.63%   |
| Dell Vostro       | 1         | 0.63%   |
| Dell System       | 1         | 0.63%   |
| Dell Precision    | 1         | 0.63%   |
| Dell G5           | 1         | 0.63%   |
| Compal QAQXX      | 1         | 0.63%   |
| Chuwi GemiBook    | 1         | 0.63%   |
| ASUS X556UR       | 1         | 0.63%   |
| ASUS X555UQ       | 1         | 0.63%   |
| ASUS X550LD       | 1         | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 21        | 13.29%  |
| 2019 | 20        | 12.66%  |
| 2018 | 17        | 10.76%  |
| 2012 | 16        | 10.13%  |
| 2016 | 15        | 9.49%   |
| 2011 | 13        | 8.23%   |
| 2017 | 12        | 7.59%   |
| 2014 | 12        | 7.59%   |
| 2013 | 11        | 6.96%   |
| 2021 | 4         | 2.53%   |
| 2015 | 4         | 2.53%   |
| 2010 | 4         | 2.53%   |
| 2009 | 3         | 1.9%    |
| 2008 | 3         | 1.9%    |
| 2007 | 2         | 1.27%   |
| 2006 | 1         | 0.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 158       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 141       | 89.24%  |
| Enabled  | 17        | 10.76%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 158       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 47        | 29.38%  |
| 8.01-16.0   | 40        | 25%     |
| 3.01-4.0    | 35        | 21.88%  |
| 16.01-24.0  | 26        | 16.25%  |
| 2.01-3.0    | 4         | 2.5%    |
| 1.01-2.0    | 3         | 1.88%   |
| 0.51-1.0    | 2         | 1.25%   |
| 32.01-64.0  | 1         | 0.63%   |
| 24.01-32.0  | 1         | 0.63%   |
| 64.01-256.0 | 1         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 53        | 30.81%  |
| 1.01-2.0  | 52        | 30.23%  |
| 4.01-8.0  | 25        | 14.53%  |
| 3.01-4.0  | 22        | 12.79%  |
| 0.51-1.0  | 14        | 8.14%   |
| 8.01-16.0 | 5         | 2.91%   |
| 0.01-0.5  | 1         | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 118       | 74.21%  |
| 2      | 38        | 23.9%   |
| 3      | 2         | 1.26%   |
| 0      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 96        | 60.76%  |
| Yes       | 62        | 39.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 86.79%  |
| No        | 21        | 13.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 99.37%  |
| No        | 1         | 0.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 82.28%  |
| No        | 28        | 17.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Peru    | 158       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lima                  | 108       | 66.26%  |
| Arequipa              | 16        | 9.82%   |
| Trujillo              | 12        | 7.36%   |
| Cusco                 | 4         | 2.45%   |
| Piura                 | 3         | 1.84%   |
| Chiclayo              | 3         | 1.84%   |
| Huancayo              | 2         | 1.23%   |
| Callao                | 2         | 1.23%   |
| Tacna                 | 1         | 0.61%   |
| San Vicente de Canete | 1         | 0.61%   |
| San Isidro            | 1         | 0.61%   |
| San Borja             | 1         | 0.61%   |
| Punta Colorada        | 1         | 0.61%   |
| Oxapampa              | 1         | 0.61%   |
| Moquegua              | 1         | 0.61%   |
| Juliaca               | 1         | 0.61%   |
| Iquitos               | 1         | 0.61%   |
| Ica                   | 1         | 0.61%   |
| Distrito de Lima      | 1         | 0.61%   |
| Barranco              | 1         | 0.61%   |
| Abancay               | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba                        | 38        | 45     | 19.69%  |
| WDC                            | 34        | 40     | 17.62%  |
| Seagate                        | 27        | 31     | 13.99%  |
| Kingston                       | 20        | 25     | 10.36%  |
| SanDisk                        | 10        | 11     | 5.18%   |
| Samsung Electronics            | 10        | 13     | 5.18%   |
| SK hynix                       | 5         | 6      | 2.59%   |
| Crucial                        | 5         | 6      | 2.59%   |
| KIOXIA                         | 4         | 4      | 2.07%   |
| Hitachi                        | 4         | 5      | 2.07%   |
| HGST                           | 4         | 4      | 2.07%   |
| Unknown                        | 3         | 3      | 1.55%   |
| Micron Technology              | 3         | 3      | 1.55%   |
| LITEON                         | 3         | 3      | 1.55%   |
| Intel                          | 3         | 3      | 1.55%   |
| Hewlett-Packard                | 2         | 2      | 1.04%   |
| China                          | 2         | 2      | 1.04%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.52%   |
| UMIS                           | 1         | 1      | 0.52%   |
| TO Exter                       | 1         | 1      | 0.52%   |
| Solid State Storage Technology | 1         | 1      | 0.52%   |
| Silicon Motion                 | 1         | 1      | 0.52%   |
| Phison                         | 1         | 1      | 0.52%   |
| Netac                          | 1         | 1      | 0.52%   |
| KingSpec                       | 1         | 1      | 0.52%   |
| ITHOO                          | 1         | 1      | 0.52%   |
| GLOWAY                         | 1         | 1      | 0.52%   |
| Gigabyte Technology            | 1         | 1      | 0.52%   |
| Fujitsu                        | 1         | 1      | 0.52%   |
| Dogfish                        | 1         | 1      | 0.52%   |
| Apple                          | 1         | 1      | 0.52%   |
| A-DATA Technology              | 1         | 1      | 0.52%   |
| Unknown                        | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 13        | 6.57%   |
| Toshiba MQ01ABD100 1TB                       | 9         | 4.55%   |
| Toshiba MQ04ABF100 1TB                       | 8         | 4.04%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 6         | 3.03%   |
| Kingston SA400S37240G 240GB SSD              | 6         | 3.03%   |
| Toshiba MQ01ABF050 500GB                     | 5         | 2.53%   |
| WDC WD10SPZX-24Z10 1TB                       | 3         | 1.52%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 3         | 1.52%   |
| Seagate ST1000LM049-2GH172 1TB               | 3         | 1.52%   |
| Kingston SA400S37480G 480GB SSD              | 3         | 1.52%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 2         | 1.01%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 2         | 1.01%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB         | 2         | 1.01%   |
| Toshiba MQ01ABD075 752GB                     | 2         | 1.01%   |
| Toshiba MK2565GSXN 250GB                     | 2         | 1.01%   |
| Seagate ST500LT012-9WS142 500GB              | 2         | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 1.01%   |
| SanDisk NVMe SSD Drive 1TB                   | 2         | 1.01%   |
| Kingston SA400S37120G 120GB SSD              | 2         | 1.01%   |
| HGST HTS721010A9E630 1TB                     | 2         | 1.01%   |
| HP SSD S700 500GB                            | 2         | 1.01%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 0.51%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD             | 1         | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 0.51%   |
| WDC WDS200T2B0A-00SM50 2TB SSD               | 1         | 0.51%   |
| WDC WDS100T2G0A-00JH30 1TB SSD               | 1         | 0.51%   |
| WDC WD6400BPVT-60HXZT1 640GB                 | 1         | 0.51%   |
| WDC WD5000LPVT-24G33T1 500GB                 | 1         | 0.51%   |
| WDC WD5000BEVT-22A0RT0 500GB                 | 1         | 0.51%   |
| WDC WD3200BPVT-24JJ5T0 320GB                 | 1         | 0.51%   |
| WDC WD3200BEVT-00A0RT0 320GB                 | 1         | 0.51%   |
| WDC WD2500BEVS-00UST0 250GB                  | 1         | 0.51%   |
| WDC WD10SPCX-60KHST0 1TB                     | 1         | 0.51%   |
| WDC WD10SPCX-08S8TT0 1TB                     | 1         | 0.51%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 1         | 0.51%   |
| WDC WD10JPVX-00JC3T0 1TB                     | 1         | 0.51%   |
| WDC WD10JPLX-00MBPT0 1TB                     | 1         | 0.51%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB         | 1         | 0.51%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB         | 1         | 0.51%   |
| Unknown SA16G  16GB                          | 1         | 0.51%   |
| Unknown NVMe SSD Drive 256GB                 | 1         | 0.51%   |
| Unknown MMC Card  32GB                       | 1         | 0.51%   |
| Union Memory (Shenzhen) NVMe SSD Drive 256GB | 1         | 0.51%   |
| UMIS RPFTJ256PDD2MWX 256GB                   | 1         | 0.51%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 0.51%   |
| Toshiba MQ04ABF1 1TB                         | 1         | 0.51%   |
| Toshiba MQ02ABD100H 1TB                      | 1         | 0.51%   |
| Toshiba MQ01ABD100H 1TB                      | 1         | 0.51%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 0.51%   |
| Toshiba MK6475GSX 640GB                      | 1         | 0.51%   |
| Toshiba MK5065GSX 500GB                      | 1         | 0.51%   |
| Toshiba MK3265GSXN 320GB                     | 1         | 0.51%   |
| Toshiba MK3252GSX 320GB                      | 1         | 0.51%   |
| Toshiba MK2035GSS 200GB                      | 1         | 0.51%   |
| Toshiba MK1646GSX 160GB                      | 1         | 0.51%   |
| Toshiba MK1637GSX 160GB                      | 1         | 0.51%   |
| Toshiba HDWJ110 1TB                          | 1         | 0.51%   |
| TO Exter nal USB 3.0 256GB                   | 1         | 0.51%   |
| Solid State Storage NVMe SSD Drive 512GB     | 1         | 0.51%   |
| SK hynix SC308 SATA 512GB SSD                | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 37        | 44     | 39.78%  |
| Seagate | 27        | 30     | 29.03%  |
| WDC     | 19        | 22     | 20.43%  |
| Hitachi | 4         | 5      | 4.3%    |
| HGST    | 4         | 4      | 4.3%    |
| Fujitsu | 1         | 1      | 1.08%   |
| Apple   | 1         | 1      | 1.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 17        | 21     | 29.31%  |
| WDC                 | 13        | 14     | 22.41%  |
| SanDisk             | 5         | 6      | 8.62%   |
| Crucial             | 5         | 6      | 8.62%   |
| Samsung Electronics | 3         | 3      | 5.17%   |
| LITEON              | 3         | 3      | 5.17%   |
| Hewlett-Packard     | 2         | 2      | 3.45%   |
| China               | 2         | 2      | 3.45%   |
| TO Exter            | 1         | 1      | 1.72%   |
| SK hynix            | 1         | 2      | 1.72%   |
| Seagate             | 1         | 1      | 1.72%   |
| Netac               | 1         | 1      | 1.72%   |
| KingSpec            | 1         | 1      | 1.72%   |
| GLOWAY              | 1         | 1      | 1.72%   |
| Dogfish             | 1         | 1      | 1.72%   |
| A-DATA Technology   | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 92        | 107    | 49.2%   |
| SSD     | 54        | 66     | 28.88%  |
| NVMe    | 37        | 45     | 19.79%  |
| MMC     | 3         | 3      | 1.6%    |
| Unknown | 1         | 1      | 0.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 127       | 172    | 75.15%  |
| NVMe | 37        | 45     | 21.89%  |
| MMC  | 3         | 3      | 1.78%   |
| SAS  | 2         | 2      | 1.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 73        | 94     | 51.77%  |
| 0.51-1.0   | 67        | 78     | 47.52%  |
| 1.01-2.0   | 1         | 1      | 0.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 48        | 29.81%  |
| 251-500        | 36        | 22.36%  |
| 501-1000       | 35        | 21.74%  |
| 51-100         | 12        | 7.45%   |
| 21-50          | 11        | 6.83%   |
| 1-20           | 7         | 4.35%   |
| 1001-2000      | 6         | 3.73%   |
| More than 3000 | 2         | 1.24%   |
| 2001-3000      | 2         | 1.24%   |
| Unknown        | 2         | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 64        | 39.51%  |
| 21-50     | 43        | 26.54%  |
| 101-250   | 18        | 11.11%  |
| 51-100    | 15        | 9.26%   |
| 251-500   | 10        | 6.17%   |
| 501-1000  | 7         | 4.32%   |
| 1001-2000 | 2         | 1.23%   |
| Unknown   | 2         | 1.23%   |
| 2001-3000 | 1         | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 1      | 7.69%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 1      | 7.69%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 1      | 7.69%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 7.69%   |
| Toshiba MQ01ABF050 500GB         | 1         | 1      | 7.69%   |
| Toshiba MK2035GSS 200GB          | 1         | 1      | 7.69%   |
| Seagate ST9500325AS 500GB        | 1         | 1      | 7.69%   |
| Seagate ST1000LM014-1EJ164 1TB   | 1         | 1      | 7.69%   |
| Kingston SA400S37480G 480GB SSD  | 1         | 1      | 7.69%   |
| Hitachi HTS545050B9A300 500GB    | 1         | 1      | 7.69%   |
| Hitachi HTS545050A7E380 500GB    | 1         | 2      | 7.69%   |
| Hitachi HTS545032B9A302 320GB    | 1         | 1      | 7.69%   |
| HGST HTS721010A9E630 1TB         | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 3         | 3      | 23.08%  |
| Toshiba  | 3         | 3      | 23.08%  |
| Hitachi  | 3         | 4      | 23.08%  |
| Seagate  | 2         | 2      | 15.38%  |
| Kingston | 1         | 1      | 7.69%   |
| HGST     | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 30%     |
| Hitachi | 3         | 4      | 30%     |
| Seagate | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |
| HGST    | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 11     | 76.92%  |
| SSD  | 3         | 3      | 23.08%  |

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
| Detected | 101       | 140    | 60.48%  |
| Works    | 53        | 66     | 31.74%  |
| Malfunc  | 12        | 14     | 7.19%   |
| Failed   | 1         | 2      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 115       | 65.71%  |
| AMD                              | 23        | 13.14%  |
| SanDisk                          | 9         | 5.14%   |
| Samsung Electronics              | 7         | 4%      |
| SK hynix                         | 4         | 2.29%   |
| KIOXIA                           | 4         | 2.29%   |
| Micron Technology                | 3         | 1.71%   |
| Kingston Technology Company      | 3         | 1.71%   |
| Unknown                          | 1         | 0.57%   |
| Union Memory (Shenzhen)          | 1         | 0.57%   |
| Toshiba America Info Systems     | 1         | 0.57%   |
| Solid State Storage Technology   | 1         | 0.57%   |
| Silicon Motion                   | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] | 1         | 0.57%   |
| Phison Electronics               | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 22        | 12.15%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 20        | 11.05%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 8.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 14        | 7.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 5.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 4.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 3.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.21%   |
| KIOXIA Non-Volatile memory controller                                          | 4         | 2.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.21%   |
| SK hynix BC511                                                                 | 3         | 1.66%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 1.66%   |
| Micron Non-Volatile memory controller                                          | 3         | 1.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.1%    |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 1.1%    |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.1%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.1%    |
| Unknown Non-Volatile memory controller                                         | 1         | 0.55%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.55%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.55%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.55%   |
| SK hynix Gold P31 SSD                                                          | 1         | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.55%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.55%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.55%   |
| Phison NVMe Storage Controller                                                 | 1         | 0.55%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.55%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.55%   |
| Kingston Company KC2000 NVMe SSD                                               | 1         | 0.55%   |
| Intel SSD 660P Series                                                          | 1         | 0.55%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 0.55%   |
| Intel NVMe Optane Memory Series                                                | 1         | 0.55%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.55%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 0.55%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.55%   |
| Intel Comet Lake PCH-H RAID                                                    | 1         | 0.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 0.55%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 0.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 0.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 0.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 0.55%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 0.55%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 0.55%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 0.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 0.55%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 0.55%   |
| AMD IXP SB4x0 Serial ATA Controller                                            | 1         | 0.55%   |
| AMD IXP SB4x0 IDE Controller                                                   | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 117       | 66.86%  |
| NVMe | 37        | 21.14%  |
| RAID | 16        | 9.14%   |
| IDE  | 5         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 126       | 79.75%  |
| AMD    | 32        | 20.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 7         | 4.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 6         | 3.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz               | 6         | 3.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 6         | 3.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz              | 4         | 2.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 4         | 2.53%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 4         | 2.53%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 3         | 1.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz               | 3         | 1.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 1.9%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 3         | 1.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.27%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 2         | 1.27%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 1.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 1.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 2         | 1.27%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 1.27%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 2         | 1.27%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 1.27%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 1.27%   |
| Intel Core i3-2328M CPU @ 2.20GHz               | 2         | 1.27%   |
| Intel Celeron CPU 550 @ 2.00GHz                 | 2         | 1.27%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 2         | 1.27%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.27%   |
| AMD Ryzen 5 4500U with Radeon Graphics          | 2         | 1.27%   |
| AMD Athlon Silver 3050U with Radeon Graphics    | 2         | 1.27%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.63%   |
| Intel Genuine CPU T2300 @ 1.66GHz               | 1         | 0.63%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.63%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 0.63%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 0.63%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz              | 1         | 0.63%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 0.63%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 1         | 0.63%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1         | 0.63%   |
| Intel Core i7-4500U CPU @ 1.80GHz               | 1         | 0.63%   |
| Intel Core i7-3740QM CPU @ 2.70GHz              | 1         | 0.63%   |
| Intel Core i7-3537U CPU @ 2.00GHz               | 1         | 0.63%   |
| Intel Core i7-2860QM CPU @ 2.50GHz              | 1         | 0.63%   |
| Intel Core i7-2630QM CPU @ 2.00GHz              | 1         | 0.63%   |
| Intel Core i7-10875H CPU @ 2.30GHz              | 1         | 0.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 0.63%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 0.63%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz               | 1         | 0.63%   |
| Intel Core i7 CPU M 640 @ 2.80GHz               | 1         | 0.63%   |
| Intel Core i5-9300HF CPU @ 2.40GHz              | 1         | 0.63%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 1         | 0.63%   |
| Intel Core i5-7440HQ CPU @ 2.80GHz              | 1         | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 0.63%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 1         | 0.63%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 0.63%   |
| Intel Core i5-4200M CPU @ 2.50GHz               | 1         | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 0.63%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 1         | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 52        | 32.91%  |
| Intel Core i5    | 37        | 23.42%  |
| Intel Core i3    | 22        | 13.92%  |
| AMD Ryzen 5      | 10        | 6.33%   |
| AMD Ryzen 7      | 6         | 3.8%    |
| Intel Celeron    | 5         | 3.16%   |
| Other            | 4         | 2.53%   |
| Intel Atom       | 3         | 1.9%    |
| Intel Core 2 Duo | 2         | 1.27%   |
| AMD Ryzen 9      | 2         | 1.27%   |
| AMD Ryzen 7 PRO  | 2         | 1.27%   |
| AMD E1           | 2         | 1.27%   |
| AMD Athlon       | 2         | 1.27%   |
| AMD A8           | 2         | 1.27%   |
| Intel Pentium    | 1         | 0.63%   |
| Intel Genuine    | 1         | 0.63%   |
| Intel Celeron M  | 1         | 0.63%   |
| AMD Ryzen 3      | 1         | 0.63%   |
| AMD E            | 1         | 0.63%   |
| AMD C-50         | 1         | 0.63%   |
| AMD A12          | 1         | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 78        | 49.37%  |
| 4       | 59        | 37.34%  |
| 8       | 7         | 4.43%   |
| 6       | 7         | 4.43%   |
| 1       | 6         | 3.8%    |
| Unknown | 1         | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 158       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 134       | 84.81%  |
| 1       | 23        | 14.56%  |
| Unknown | 1         | 0.63%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 152       | 95%     |
| 64-bit         | 3         | 1.88%   |
| 32-bit         | 3         | 1.88%   |
| Unknown        | 2         | 1.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 14.38%  |
| 0x206a7    | 13        | 8.13%   |
| 0x306a9    | 11        | 6.88%   |
| 0x40651    | 10        | 6.25%   |
| 0x406e3    | 9         | 5.63%   |
| 0x806ec    | 8         | 5%      |
| 0x806e9    | 8         | 5%      |
| 0x806ea    | 7         | 4.38%   |
| 0x306d4    | 6         | 3.75%   |
| 0x08108109 | 6         | 3.75%   |
| 0x906ea    | 5         | 3.13%   |
| 0x08108102 | 5         | 3.13%   |
| 0x306c3    | 4         | 2.5%    |
| 0x806eb    | 3         | 1.88%   |
| 0x20655    | 3         | 1.88%   |
| 0xa0652    | 2         | 1.25%   |
| 0x906e9    | 2         | 1.25%   |
| 0x706e5    | 2         | 1.25%   |
| 0x30678    | 2         | 1.25%   |
| 0x20652    | 2         | 1.25%   |
| 0x10661    | 2         | 1.25%   |
| 0x08600106 | 2         | 1.25%   |
| 0x08600104 | 2         | 1.25%   |
| 0x05000029 | 2         | 1.25%   |
| 0x806c1    | 1         | 0.63%   |
| 0x706a1    | 1         | 0.63%   |
| 0x6e8      | 1         | 0.63%   |
| 0x6d8      | 1         | 0.63%   |
| 0x506e3    | 1         | 0.63%   |
| 0x406c4    | 1         | 0.63%   |
| 0x106ca    | 1         | 0.63%   |
| 0x106c2    | 1         | 0.63%   |
| 0x1067a    | 1         | 0.63%   |
| 0x10676    | 1         | 0.63%   |
| 0x0a50000c | 1         | 0.63%   |
| 0x08600102 | 1         | 0.63%   |
| 0x08101016 | 1         | 0.63%   |
| 0x0810100b | 1         | 0.63%   |
| 0x08101007 | 1         | 0.63%   |
| 0x07030106 | 1         | 0.63%   |
| 0x07030105 | 1         | 0.63%   |
| 0x07000110 | 1         | 0.63%   |
| 0x06006704 | 1         | 0.63%   |
| 0x0600611a | 1         | 0.63%   |
| 0x06001119 | 1         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 41        | 25.95%  |
| Haswell       | 15        | 9.49%   |
| IvyBridge     | 14        | 8.86%   |
| SandyBridge   | 13        | 8.23%   |
| Zen+          | 12        | 7.59%   |
| Skylake       | 10        | 6.33%   |
| Zen 2         | 6         | 3.8%    |
| Westmere      | 6         | 3.8%    |
| Broadwell     | 6         | 3.8%    |
| Zen           | 4         | 2.53%   |
| Silvermont    | 3         | 1.9%    |
| IceLake       | 3         | 1.9%    |
| Excavator     | 3         | 1.9%    |
| CometLake     | 3         | 1.9%    |
| Puma          | 2         | 1.27%   |
| Penryn        | 2         | 1.27%   |
| P6            | 2         | 1.27%   |
| Core          | 2         | 1.27%   |
| Bonnell       | 2         | 1.27%   |
| Bobcat        | 2         | 1.27%   |
| Zen 3         | 1         | 0.63%   |
| TigerLake     | 1         | 0.63%   |
| Piledriver    | 1         | 0.63%   |
| Nehalem       | 1         | 0.63%   |
| Jaguar        | 1         | 0.63%   |
| Goldmont plus | 1         | 0.63%   |
| Unknown       | 1         | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 117       | 56.25%  |
| AMD                              | 52        | 25%     |
| Nvidia                           | 38        | 18.27%  |
| Silicon Integrated Systems [SiS] | 1         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 14        | 6.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 12        | 5.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 12        | 5.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 11        | 5.09%   |
| Intel UHD Graphics 620                                                                | 10        | 4.63%   |
| Intel HD Graphics 620                                                                 | 10        | 4.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 9         | 4.17%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 3.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 3.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 6         | 2.78%   |
| Intel HD Graphics 5500                                                                | 6         | 2.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 6         | 2.78%   |
| AMD Renoir                                                                            | 6         | 2.78%   |
| Intel Core Processor Integrated Graphics Controller                                   | 5         | 2.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 2.31%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 4         | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 4         | 1.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 1.39%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 3         | 1.39%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 3         | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 1.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 1.39%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.93%   |
| Nvidia GM108M [GeForce MX110]                                                         | 2         | 0.93%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 0.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 0.93%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 2         | 0.93%   |
| Intel HD Graphics 630                                                                 | 2         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 0.93%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 2         | 0.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 2         | 0.93%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                     | 1         | 0.46%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.46%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.46%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                               | 1         | 0.46%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 0.46%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 0.46%   |
| Nvidia GP108GLM [Quadro P520]                                                         | 1         | 0.46%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.46%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 1         | 0.46%   |
| Nvidia GM108M [GeForce MX130]                                                         | 1         | 0.46%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 0.46%   |
| Nvidia GM107M [GeForce GTX 860M]                                                      | 1         | 0.46%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 0.46%   |
| Nvidia GK208M [GeForce GT 735M]                                                       | 1         | 0.46%   |
| Nvidia GK208GLM [Quadro K610M]                                                        | 1         | 0.46%   |
| Nvidia GK107M [GeForce GT 650M]                                                       | 1         | 0.46%   |
| Nvidia GF108M [NVS 5400M]                                                             | 1         | 0.46%   |
| Nvidia GF108M [GeForce GT 540M]                                                       | 1         | 0.46%   |
| Nvidia GF108GLM [Quadro 1000M]                                                        | 1         | 0.46%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 0.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 0.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 1         | 0.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 1         | 0.46%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                            | 1         | 0.46%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 0.46%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 0.46%   |
| Intel Iris Plus Graphics G7                                                           | 1         | 0.46%   |
| Intel HD Graphics 530                                                                 | 1         | 0.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 69        | 43.67%  |
| Intel + Nvidia | 32        | 20.25%  |
| 1 x AMD        | 29        | 18.35%  |
| Intel + AMD    | 16        | 10.13%  |
| 2 x AMD        | 5         | 3.16%   |
| 1 x Nvidia     | 4         | 2.53%   |
| AMD + Nvidia   | 2         | 1.27%   |
| 1 x SiS        | 1         | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 137       | 85.63%  |
| Proprietary | 20        | 12.5%   |
| Unknown     | 3         | 1.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 50.31%  |
| 1.01-2.0   | 36        | 22.36%  |
| 0.01-0.5   | 21        | 13.04%  |
| 3.01-4.0   | 10        | 6.21%   |
| 0.51-1.0   | 7         | 4.35%   |
| 5.01-6.0   | 4         | 2.48%   |
| 7.01-8.0   | 1         | 0.62%   |
| 8.01-16.0  | 1         | 0.62%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 39        | 21.67%  |
| BOE                 | 34        | 18.89%  |
| AU Optronics        | 29        | 16.11%  |
| Samsung Electronics | 23        | 12.78%  |
| LG Display          | 17        | 9.44%   |
| Goldstar            | 5         | 2.78%   |
| Sharp               | 3         | 1.67%   |
| PANDA               | 3         | 1.67%   |
| Hewlett-Packard     | 3         | 1.67%   |
| Sony                | 2         | 1.11%   |
| Lenovo              | 2         | 1.11%   |
| JRY                 | 2         | 1.11%   |
| HannStar            | 2         | 1.11%   |
| Dell                | 2         | 1.11%   |
| AOC                 | 2         | 1.11%   |
| Unknown (XXX)       | 1         | 0.56%   |
| TMX                 | 1         | 0.56%   |
| Mi                  | 1         | 0.56%   |
| LGD                 | 1         | 0.56%   |
| InnoLux Display     | 1         | 0.56%   |
| InfoVision          | 1         | 0.56%   |
| Hitachi             | 1         | 0.56%   |
| EXP                 | 1         | 0.56%   |
| DZX                 | 1         | 0.56%   |
| Apple               | 1         | 0.56%   |
| AGO                 | 1         | 0.56%   |
| Unknown             | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 8         | 4.44%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 6         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch        | 3         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch        | 3         | 1.67%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                   | 3         | 1.67%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 3         | 1.67%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 2         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 2         | 1.11%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 1.11%   |
| JRY HDMI JRY2380 1920x1080 527x296mm 23.8-inch                         | 2         | 1.11%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 2         | 1.11%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 1.11%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 2         | 1.11%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch        | 2         | 1.11%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 2         | 1.11%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                   | 2         | 1.11%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                   | 2         | 1.11%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                   | 2         | 1.11%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                   | 2         | 1.11%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                   | 2         | 1.11%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch          | 2         | 1.11%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch          | 2         | 1.11%   |
| Unknown (XXX) MS82PV XXX001A 1360x768 330x210mm 15.4-inch              | 1         | 0.56%   |
| TMX TL156MDMP01-1 TMX1560 3200x2000 336x210mm 15.6-inch                | 1         | 0.56%   |
| Sony TV SNYEF03 1600x900                                               | 1         | 0.56%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch   | 1         | 0.56%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch                | 1         | 0.56%   |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 443x249mm 20.0-inch   | 1         | 0.56%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch      | 1         | 0.56%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch      | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4B45 1280x800 331x207mm 15.4-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3641 1366x768 353x198mm 15.9-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4742 1366x768 309x174mm 14.0-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch  | 1         | 0.56%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch                | 1         | 0.56%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                       | 1         | 0.56%   |
| LGD LCD Monitor 1920x1080                                              | 1         | 0.56%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD054F 1920x1080 344x194mm 15.5-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch            | 1         | 0.56%   |
| LG Display LCD Monitor LGD04F2 1366x768 309x174mm 14.0-inch            | 1         | 0.56%   |
| LG Display LCD Monitor LGD047B 1366x768 344x194mm 15.5-inch            | 1         | 0.56%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch           | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 99        | 56.9%   |
| 1920x1080 (FHD)   | 47        | 27.01%  |
| 1600x900 (HD+)    | 5         | 2.87%   |
| 1360x768          | 4         | 2.3%    |
| 3840x2160 (4K)    | 3         | 1.72%   |
| 1280x800 (WXGA)   | 3         | 1.72%   |
| 3200x1800 (QHD+)  | 2         | 1.15%   |
| 1024x600          | 2         | 1.15%   |
| Unknown           | 2         | 1.15%   |
| 3840x1080         | 1         | 0.57%   |
| 3200x2000         | 1         | 0.57%   |
| 2160x1440         | 1         | 0.57%   |
| 1920x1200 (WUXGA) | 1         | 0.57%   |
| 1440x900 (WXGA+)  | 1         | 0.57%   |
| 1280x720 (HD)     | 1         | 0.57%   |
| 1024x768 (XGA)    | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 82        | 46.07%  |
| 13      | 36        | 20.22%  |
| 14      | 23        | 12.92%  |
| 23      | 7         | 3.93%   |
| 17      | 5         | 2.81%   |
| 21      | 3         | 1.69%   |
| 18      | 3         | 1.69%   |
| 72      | 2         | 1.12%   |
| 12      | 2         | 1.12%   |
| 11      | 2         | 1.12%   |
| 10      | 2         | 1.12%   |
| Unknown | 2         | 1.12%   |
| 84      | 1         | 0.56%   |
| 60      | 1         | 0.56%   |
| 54      | 1         | 0.56%   |
| 46      | 1         | 0.56%   |
| 39      | 1         | 0.56%   |
| 27      | 1         | 0.56%   |
| 24      | 1         | 0.56%   |
| 20      | 1         | 0.56%   |
| 19      | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 131       | 74.43%  |
| 201-300     | 12        | 6.82%   |
| 501-600     | 9         | 5.11%   |
| 401-500     | 8         | 4.55%   |
| 351-400     | 7         | 3.98%   |
| 1501-2000   | 3         | 1.7%    |
| 1001-1500   | 3         | 1.7%    |
| Unknown     | 2         | 1.14%   |
| 801-900     | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 141       | 90.38%  |
| 16/10   | 9         | 5.77%   |
| 4/3     | 3         | 1.92%   |
| Unknown | 2         | 1.28%   |
| 3/2     | 1         | 0.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 82        | 46.07%  |
| 81-90          | 53        | 29.78%  |
| 201-250        | 10        | 5.62%   |
| 71-80          | 6         | 3.37%   |
| More than 1000 | 5         | 2.81%   |
| 121-130        | 4         | 2.25%   |
| 151-200        | 3         | 1.69%   |
| 141-150        | 3         | 1.69%   |
| 51-60          | 2         | 1.12%   |
| 41-50          | 2         | 1.12%   |
| 501-1000       | 2         | 1.12%   |
| Unknown        | 2         | 1.12%   |
| 61-70          | 1         | 0.56%   |
| 301-350        | 1         | 0.56%   |
| 131-140        | 1         | 0.56%   |
| 91-100         | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 100       | 57.47%  |
| 121-160       | 39        | 22.41%  |
| 51-100        | 22        | 12.64%  |
| 1-50          | 5         | 2.87%   |
| More than 240 | 3         | 1.72%   |
| 161-240       | 3         | 1.72%   |
| Unknown       | 2         | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 129       | 80.12%  |
| 2     | 27        | 16.77%  |
| 0     | 4         | 2.48%   |
| 3     | 1         | 0.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 105       | 41.5%   |
| Intel                            | 56        | 22.13%  |
| Qualcomm Atheros                 | 49        | 19.37%  |
| Broadcom                         | 12        | 4.74%   |
| TP-Link                          | 6         | 2.37%   |
| Ralink                           | 5         | 1.98%   |
| Marvell Technology Group         | 3         | 1.19%   |
| Xiaomi                           | 2         | 0.79%   |
| Ralink Technology                | 2         | 0.79%   |
| Motorola PCS                     | 2         | 0.79%   |
| ICS Advent                       | 2         | 0.79%   |
| ASIX Electronics                 | 2         | 0.79%   |
| T & A Mobile Phones              | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |
| Samsung Electronics              | 1         | 0.4%    |
| MediaTek                         | 1         | 0.4%    |
| Lenovo                           | 1         | 0.4%    |
| Broadcom Limited                 | 1         | 0.4%    |
| Apple                            | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68        | 22.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 17        | 5.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 3.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 3.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.95%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.62%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 4         | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.3%    |
| Intel Wireless 8265 / 8275                                        | 4         | 1.3%    |
| Intel Wireless 8260                                               | 4         | 1.3%    |
| Intel Wireless 7260                                               | 4         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.97%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.65%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2         | 0.65%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.65%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.65%   |
| Motorola PCS moto g stylus                                        | 2         | 0.65%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.65%   |
| Intel Wireless 7265                                               | 2         | 0.65%   |
| Intel WiFi Link 5100                                              | 2         | 0.65%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.65%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.65%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 2         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.65%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.32%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                           | 1         | 0.32%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                      | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.32%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.32%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.32%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.32%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.32%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.32%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.32%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.32%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 54        | 32.93%  |
| Qualcomm Atheros      | 44        | 26.83%  |
| Realtek Semiconductor | 42        | 25.61%  |
| Broadcom              | 10        | 6.1%    |
| TP-Link               | 5         | 3.05%   |
| Ralink                | 5         | 3.05%   |
| Ralink Technology     | 2         | 1.22%   |
| MediaTek              | 1         | 0.61%   |
| Broadcom Limited      | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 17        | 10.37%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 12        | 7.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 10        | 6.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 8         | 4.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 6         | 3.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 6         | 3.66%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 6         | 3.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 5         | 3.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5         | 3.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 5         | 3.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 5         | 3.05%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 4         | 2.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 4         | 2.44%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 2.44%   |
| Intel Wireless 8260                                                           | 4         | 2.44%   |
| Intel Wireless 7260                                                           | 4         | 2.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 4         | 2.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 3         | 1.83%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 1.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 1.83%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2         | 1.22%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2         | 1.22%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 2         | 1.22%   |
| Intel Wireless 7265                                                           | 2         | 1.22%   |
| Intel WiFi Link 5100                                                          | 2         | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 1.22%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 1.22%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                       | 1         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 0.61%   |
| Realtek RTL8187 Wireless Adapter                                              | 1         | 0.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.61%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.61%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 0.61%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 1         | 0.61%   |
| Intel Wireless-AC 9260                                                        | 1         | 0.61%   |
| Intel Wireless 3165                                                           | 1         | 0.61%   |
| Intel Wireless 3160                                                           | 1         | 0.61%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 0.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 0.61%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 0.61%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 0.61%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 0.61%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.61%   |
| Intel Centrino Advanced-N 6200                                                | 1         | 0.61%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 1         | 0.61%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 1         | 0.61%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 1         | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 0.61%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 94        | 65.73%  |
| Intel                            | 20        | 13.99%  |
| Qualcomm Atheros                 | 9         | 6.29%   |
| Marvell Technology Group         | 3         | 2.1%    |
| Broadcom                         | 3         | 2.1%    |
| Xiaomi                           | 2         | 1.4%    |
| Motorola PCS                     | 2         | 1.4%    |
| ICS Advent                       | 2         | 1.4%    |
| ASIX Electronics                 | 2         | 1.4%    |
| TP-Link                          | 1         | 0.7%    |
| T & A Mobile Phones              | 1         | 0.7%    |
| Silicon Integrated Systems [SiS] | 1         | 0.7%    |
| Samsung Electronics              | 1         | 0.7%    |
| Lenovo                           | 1         | 0.7%    |
| Apple                            | 1         | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 68        | 47.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 22        | 15.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 3.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 2.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 1.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 1.39%   |
| Motorola PCS moto g stylus                                                     | 2         | 1.39%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.39%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.39%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.39%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.39%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 2         | 1.39%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.39%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.69%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                                   | 1         | 0.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.69%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.69%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.69%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.69%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.69%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.69%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.69%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.69%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.69%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.69%   |
| Apple iPad 4/Mini1                                                             | 1         | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 157       | 53.22%  |
| Ethernet | 138       | 46.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 125       | 73.53%  |
| Ethernet | 45        | 26.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 125       | 79.11%  |
| 1     | 32        | 20.25%  |
| 0     | 1         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 135       | 84.38%  |
| Yes  | 25        | 15.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 29.23%  |
| Realtek Semiconductor           | 30        | 23.08%  |
| Qualcomm Atheros Communications | 28        | 21.54%  |
| Lite-On Technology              | 7         | 5.38%   |
| IMC Networks                    | 7         | 5.38%   |
| Toshiba                         | 4         | 3.08%   |
| Ralink                          | 4         | 3.08%   |
| Broadcom                        | 3         | 2.31%   |
| Hewlett-Packard                 | 2         | 1.54%   |
| Cambridge Silicon Radio         | 2         | 1.54%   |
| Foxconn International           | 1         | 0.77%   |
| Foxconn / Hon Hai               | 1         | 0.77%   |
| Dell                            | 1         | 0.77%   |
| Apple                           | 1         | 0.77%   |
| Alps Electric                   | 1         | 0.77%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 16        | 12.31%  |
| Realtek  Bluetooth 4.2 Adapter                      | 14        | 10.77%  |
| Realtek Bluetooth Radio                             | 14        | 10.77%  |
| Intel Bluetooth wireless interface                  | 14        | 10.77%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 6.15%   |
| Intel Bluetooth Device                              | 7         | 5.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 3.85%   |
| Ralink RT3290 Bluetooth                             | 4         | 3.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 2.31%   |
| Lite-On Bluetooth Device                            | 3         | 2.31%   |
| Intel AX200 Bluetooth                               | 3         | 2.31%   |
| IMC Networks Bluetooth Device                       | 3         | 2.31%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.54%   |
| Lite-On Bluetooth Radio                             | 2         | 1.54%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.54%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.54%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.77%   |
| Toshiba Bluetooth Device                            | 1         | 0.77%   |
| Toshiba BCM43142A0                                  | 1         | 0.77%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.77%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.77%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.77%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.77%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.77%   |
| IMC Networks Wireless_Device                        | 1         | 0.77%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.77%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.77%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.77%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.77%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.77%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.77%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.77%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 0.77%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 123       | 67.96%  |
| AMD                              | 36        | 19.89%  |
| Nvidia                           | 17        | 9.39%   |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| Razer USA                        | 1         | 0.55%   |
| Pixart Imaging                   | 1         | 0.55%   |
| Hewlett-Packard                  | 1         | 0.55%   |
| C-Media Electronics              | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 29        | 12.5%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 23        | 9.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 7.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 16        | 6.9%    |
| Intel 8 Series HD Audio Controller                                                                | 11        | 4.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 4.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 3.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 3.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 3.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.59%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.59%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.72%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.72%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.29%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.29%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.29%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.86%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.86%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.86%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.43%   |
| Razer USA RZ19-0229 Gaming Microphone                                                             | 1         | 0.43%   |
| Pixart Imaging Multimedia audio controller                                                        | 1         | 0.43%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.43%   |
| Nvidia Audio device                                                                               | 1         | 0.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.43%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.43%   |
| Hewlett-Packard USB Audio                                                                         | 1         | 0.43%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.43%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.43%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.43%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.43%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 0.43%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.43%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 1         | 0.43%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 29.66%  |
| SK hynix            | 29        | 24.58%  |
| Micron Technology   | 20        | 16.95%  |
| Kingston            | 12        | 10.17%  |
| Unknown             | 7         | 5.93%   |
| Ramaxel Technology  | 6         | 5.08%   |
| Crucial             | 2         | 1.69%   |
| Unknown (ABCD)      | 1         | 0.85%   |
| Team                | 1         | 0.85%   |
| Patriot             | 1         | 0.85%   |
| Hewlett-Packard     | 1         | 0.85%   |
| Goldkey             | 1         | 0.85%   |
| CSX                 | 1         | 0.85%   |
| Corsair             | 1         | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 4.07%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 5         | 4.07%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 4         | 3.25%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 2.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 2.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 2.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 2         | 1.63%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.63%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 2         | 1.63%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 1.63%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 1.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.63%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 1.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.63%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 1.63%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.63%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 2         | 1.63%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 2         | 1.63%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s             | 2         | 1.63%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 1         | 0.81%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.81%   |
| Unknown RAM Module 512MB SODIMM DDR2                                | 1         | 0.81%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 0.81%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                              | 1         | 0.81%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                         | 1         | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.81%   |
| Team RAM TEAMGROUP-SD3-1600 4GB SODIMM DDR3 1600MT/s                | 1         | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.81%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.81%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.81%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.81%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 0.81%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 1         | 0.81%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 0.81%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.81%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.81%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.81%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 1         | 0.81%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 0.81%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s               | 1         | 0.81%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 0.81%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 0.81%   |
| Samsung RAM M378B5273BH1-CK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.81%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 0.81%   |
| Ramaxel RAM RMSA3310MJ86H9F-3200 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.81%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 1         | 0.81%   |
| Ramaxel RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 1         | 0.81%   |
| Patriot RAM PSD48G266681S 8GB SODIMM DDR4 2667MT/s                  | 1         | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 42        | 49.41%  |
| DDR3   | 32        | 37.65%  |
| LPDDR4 | 5         | 5.88%   |
| LPDDR3 | 3         | 3.53%   |
| DDR2   | 2         | 2.35%   |
| SDRAM  | 1         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 81        | 95.29%  |
| Row Of Chips | 4         | 4.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 47        | 46.08%  |
| 8192  | 42        | 41.18%  |
| 2048  | 7         | 6.86%   |
| 16384 | 4         | 3.92%   |
| 1024  | 1         | 0.98%   |
| 512   | 1         | 0.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 36        | 36%     |
| 1600    | 25        | 25%     |
| 3200    | 12        | 12%     |
| 3266    | 5         | 5%      |
| 2400    | 5         | 5%      |
| 1333    | 5         | 5%      |
| 2133    | 3         | 3%      |
| 1334    | 3         | 3%      |
| Unknown | 3         | 3%      |
| 1867    | 2         | 2%      |
| 1067    | 1         | 1%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson L3150 Series         | 1         | 33.33%  |
| HP LaserJet Professional P 1102w | 1         | 33.33%  |
| Brother DCP-T300                 | 1         | 33.33%  |

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
| Chicony Electronics                    | 32        | 20.92%  |
| IMC Networks                           | 17        | 11.11%  |
| Acer                                   | 13        | 8.5%    |
| Realtek Semiconductor                  | 12        | 7.84%   |
| Microdia                               | 11        | 7.19%   |
| Syntek                                 | 10        | 6.54%   |
| Sunplus Innovation Technology          | 9         | 5.88%   |
| Quanta                                 | 9         | 5.88%   |
| Lite-On Technology                     | 9         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.88%   |
| Suyin                                  | 7         | 4.58%   |
| Importek                               | 4         | 2.61%   |
| Samsung Electronics                    | 2         | 1.31%   |
| Ricoh                                  | 2         | 1.31%   |
| Alcor Micro                            | 2         | 1.31%   |
| Sonix Technology                       | 1         | 0.65%   |
| Luxvisions Innotech Limited            | 1         | 0.65%   |
| Logitech                               | 1         | 0.65%   |
| Apple                                  | 1         | 0.65%   |
| ANYKA                                  | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 8         | 5.19%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 6         | 3.9%    |
| Lite-On Integrated Camera                                                  | 4         | 2.6%    |
| IMC Networks Integrated Camera                                             | 4         | 2.6%    |
| Chicony Integrated Camera                                                  | 4         | 2.6%    |
| Chicony EasyCamera                                                         | 4         | 2.6%    |
| Acer Integrated Camera                                                     | 4         | 2.6%    |
| Sunplus Integrated_Webcam_HD                                               | 3         | 1.95%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 1.95%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 1.95%   |
| Lite-On HP HD Camera                                                       | 3         | 1.95%   |
| Chicony HP Truevision HD                                                   | 3         | 1.95%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.95%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 1.3%    |
| Sunplus Integrated Webcam                                                  | 2         | 1.3%    |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 1.3%    |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 1.3%    |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 1.3%    |
| Realtek Integrated Webcam                                                  | 2         | 1.3%    |
| Quanta HP Webcam                                                           | 2         | 1.3%    |
| Quanta HP TrueVision HD Camera                                             | 2         | 1.3%    |
| IMC Networks HP TrueVision HD Camera                                       | 2         | 1.3%    |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 1.3%    |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.3%    |
| Chicony Lenovo EasyCamera                                                  | 2         | 1.3%    |
| Chicony HP TrueVision HD Camera                                            | 2         | 1.3%    |
| Chicony HP HD Camera                                                       | 2         | 1.3%    |
| Chicony HD Webcam                                                          | 2         | 1.3%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 1.3%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.3%    |
| Alcor Micro TOSHIBA Web Camera - MP                                        | 2         | 1.3%    |
| Syntek USB Video Device                                                    | 1         | 0.65%   |
| Syntek USB Camera Device                                                   | 1         | 0.65%   |
| Suyin USB 2.0 Camera                                                       | 1         | 0.65%   |
| Suyin TOSHIBA Web Camera - HD                                              | 1         | 0.65%   |
| Suyin HP Truevision HD                                                     | 1         | 0.65%   |
| Suyin HD WebCam                                                            | 1         | 0.65%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 0.65%   |
| Sunplus SPCA2087 PC Camera                                                 | 1         | 0.65%   |
| Sunplus Lenovo EasyCamera                                                  | 1         | 0.65%   |
| Sunplus Laptop Integrated Webcam FHD                                       | 1         | 0.65%   |
| Sunplus HP Wide Vision HD                                                  | 1         | 0.65%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 0.65%   |
| Realtek USB Camera                                                         | 1         | 0.65%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 0.65%   |
| Realtek HP Wide Vision HD Camera                                           | 1         | 0.65%   |
| Realtek HP Truevision HD                                                   | 1         | 0.65%   |
| Realtek Front Camera                                                       | 1         | 0.65%   |
| Quanta VGA WebCam                                                          | 1         | 0.65%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                       | 1         | 0.65%   |
| Quanta HP HD Camera                                                        | 1         | 0.65%   |
| Quanta HD Webcam                                                           | 1         | 0.65%   |
| Quanta HD User Facing                                                      | 1         | 0.65%   |
| Microdia Webcam Vitade AF                                                  | 1         | 0.65%   |
| Microdia Webcam SC-10HDD12636P                                             | 1         | 0.65%   |
| Microdia Webcam                                                            | 1         | 0.65%   |
| Microdia USB 2.0 Camera                                                    | 1         | 0.65%   |
| Microdia Lenovo EasyCamera                                                 | 1         | 0.65%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 0.65%   |
| Microdia Integrated Webcam HD                                              | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 51.35%  |
| Synaptics                  | 10        | 27.03%  |
| Shenzhen Goodix Technology | 3         | 8.11%   |
| Elan Microelectronics      | 3         | 8.11%   |
| STMicroelectronics         | 1         | 2.7%    |
| AuthenTec                  | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 6         | 16.22%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 16.22%  |
| Synaptics  WBDI                                            | 3         | 8.11%   |
| Validity Sensors Fingerprint scanner                       | 2         | 5.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 5.41%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 5.41%   |
| Elan ELAN:Fingerprint                                      | 2         | 5.41%   |
| Unknown                                                    | 2         | 5.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.7%    |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.7%    |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.7%    |
| Validity Sensors Synaptics WBDI                            | 1         | 2.7%    |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 2.7%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.7%    |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.7%    |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 2.7%    |
| Elan ELAN:ARM-M4                                           | 1         | 2.7%    |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.7%    |

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
| 0     | 95        | 59.01%  |
| 1     | 57        | 35.4%   |
| 2     | 8         | 4.97%   |
| 3     | 1         | 0.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 37        | 48.68%  |
| Graphics card         | 10        | 13.16%  |
| Net/wireless          | 9         | 11.84%  |
| Chipcard              | 9         | 11.84%  |
| Bluetooth             | 5         | 6.58%   |
| Multimedia controller | 2         | 2.63%   |
| Card reader           | 2         | 2.63%   |
| Storage               | 1         | 1.32%   |
| Camera                | 1         | 1.32%   |

