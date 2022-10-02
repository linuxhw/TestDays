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

Total: 242

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 32        | 18.08%  |
| Ubuntu 18.04                 | 9         | 5.08%   |
| OpenMandriva 4.3             | 8         | 4.52%   |
| Zorin 15                     | 6         | 3.39%   |
| Ubuntu 19.10                 | 5         | 2.82%   |
| Arch                         | 5         | 2.82%   |
| Xubuntu 20.04                | 4         | 2.26%   |
| Ubuntu 22.04                 | 4         | 2.26%   |
| Ubuntu 21.04                 | 4         | 2.26%   |
| Pop!_OS 21.10                | 4         | 2.26%   |
| Manjaro                      | 4         | 2.26%   |
| Linux Mint 20.3              | 4         | 2.26%   |
| Debian 11                    | 4         | 2.26%   |
| Ubuntu 19.04                 | 3         | 1.69%   |
| Pop!_OS 20.10                | 3         | 1.69%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.69%   |
| OpenMandriva 4.2             | 3         | 1.69%   |
| Manjaro 20.1                 | 3         | 1.69%   |
| KDE neon 20.04               | 3         | 1.69%   |
| Elementary 5.1.7             | 3         | 1.69%   |
| Debian 10                    | 3         | 1.69%   |
| Arch Rolling                 | 3         | 1.69%   |
| ROSA R9                      | 2         | 1.13%   |
| ROSA R10                     | 2         | 1.13%   |
| ROSA 12.2                    | 2         | 1.13%   |
| Pop!_OS 22.04                | 2         | 1.13%   |
| Pop!_OS 20.04                | 2         | 1.13%   |
| OpenMandriva 4.90            | 2         | 1.13%   |
| Linux Mint 20                | 2         | 1.13%   |
| Kubuntu 20.04                | 2         | 1.13%   |
| Fedora 35                    | 2         | 1.13%   |
| Fedora 34                    | 2         | 1.13%   |
| Fedora 33                    | 2         | 1.13%   |
| Fedora 32                    | 2         | 1.13%   |
| CentOS 8                     | 2         | 1.13%   |
| Zorin 16                     | 1         | 0.56%   |
| Void Linux                   | 1         | 0.56%   |
| Ubuntu Unity 18.10           | 1         | 0.56%   |
| Ubuntu MATE 20.04            | 1         | 0.56%   |
| Ubuntu MATE 18.04            | 1         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 58        | 33.14%  |
| OpenMandriva | 13        | 7.43%   |
| Pop!_OS      | 12        | 6.86%   |
| Manjaro      | 10        | 5.71%   |
| Linux Mint   | 9         | 5.14%   |
| Fedora       | 9         | 5.14%   |
| Arch         | 9         | 5.14%   |
| Zorin        | 7         | 4%      |
| ROSA         | 7         | 4%      |
| Debian       | 7         | 4%      |
| Xubuntu      | 4         | 2.29%   |
| Elementary   | 4         | 2.29%   |
| openSUSE     | 3         | 1.71%   |
| KDE neon     | 3         | 1.71%   |
| Endless      | 3         | 1.71%   |
| Ubuntu MATE  | 2         | 1.14%   |
| Lubuntu      | 2         | 1.14%   |
| Kubuntu      | 2         | 1.14%   |
| CentOS       | 2         | 1.14%   |
| Void Linux   | 1         | 0.57%   |
| Ubuntu Unity | 1         | 0.57%   |
| Peppermint   | 1         | 0.57%   |
| Parrot       | 1         | 0.57%   |
| MX           | 1         | 0.57%   |
| LMDE         | 1         | 0.57%   |
| Laxer OS     | 1         | 0.57%   |
| Kali         | 1         | 0.57%   |
| ArcoLinux    | 1         | 0.57%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 8         | 4.17%   |
| 5.13.0-40-generic               | 5         | 2.6%    |
| 5.4.0-42-generic                | 4         | 2.08%   |
| 5.4.0-26-generic                | 3         | 1.56%   |
| 5.3.0-40-generic                | 3         | 1.56%   |
| 5.13.0-51-generic               | 3         | 1.56%   |
| 5.11.0-25-generic               | 3         | 1.56%   |
| 5.10.0-13-amd64                 | 3         | 1.56%   |
| 5.8.0-44-generic                | 2         | 1.04%   |
| 5.4.0-7642-generic              | 2         | 1.04%   |
| 5.4.0-66-generic                | 2         | 1.04%   |
| 5.4.0-65-generic                | 2         | 1.04%   |
| 5.4.0-58-generic                | 2         | 1.04%   |
| 5.4.0-54-generic                | 2         | 1.04%   |
| 5.4.0-39-generic                | 2         | 1.04%   |
| 5.4.0-33-generic                | 2         | 1.04%   |
| 5.4.0-28-generic                | 2         | 1.04%   |
| 5.4.0-109-generic               | 2         | 1.04%   |
| 5.3.0-42-generic                | 2         | 1.04%   |
| 5.3.0-23-generic                | 2         | 1.04%   |
| 5.18.12-desktop-3omv4090        | 2         | 1.04%   |
| 5.17.5-arch1-1                  | 2         | 1.04%   |
| 5.16.19-76051619-generic        | 2         | 1.04%   |
| 5.15.49-1-lts                   | 2         | 1.04%   |
| 5.15.0-25-generic               | 2         | 1.04%   |
| 5.13.0-30-generic               | 2         | 1.04%   |
| 5.11.0-7614-generic             | 2         | 1.04%   |
| 5.10.14-desktop-1omv4002        | 2         | 1.04%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 1.04%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 1.04%   |
| 5.9.16-1-MANJARO                | 1         | 0.52%   |
| 5.9.11-3-MANJARO                | 1         | 0.52%   |
| 5.8.6-1-MANJARO                 | 1         | 0.52%   |
| 5.8.4-200.fc32.x86_64           | 1         | 0.52%   |
| 5.8.11-1-MANJARO                | 1         | 0.52%   |
| 5.8.0-63-generic                | 1         | 0.52%   |
| 5.8.0-55-generic                | 1         | 0.52%   |
| 5.8.0-50-generic                | 1         | 0.52%   |
| 5.8.0-43-generic                | 1         | 0.52%   |
| 5.8.0-33-generic                | 1         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 19.57%  |
| 5.11.0  | 14        | 7.61%   |
| 5.3.0   | 12        | 6.52%   |
| 5.13.0  | 12        | 6.52%   |
| 5.16.7  | 8         | 4.35%   |
| 5.8.0   | 7         | 3.8%    |
| 5.0.0   | 7         | 3.8%    |
| 4.15.0  | 7         | 3.8%    |
| 5.15.0  | 6         | 3.26%   |
| 5.10.0  | 6         | 3.26%   |
| 4.18.0  | 6         | 3.26%   |
| 5.17.5  | 3         | 1.63%   |
| 4.9.60  | 3         | 1.63%   |
| 5.19.0  | 2         | 1.09%   |
| 5.18.12 | 2         | 1.09%   |
| 5.16.19 | 2         | 1.09%   |
| 5.15.49 | 2         | 1.09%   |
| 5.12.10 | 2         | 1.09%   |
| 5.10.14 | 2         | 1.09%   |
| 4.9.20  | 2         | 1.09%   |
| 4.19.0  | 2         | 1.09%   |
| 5.9.16  | 1         | 0.54%   |
| 5.9.11  | 1         | 0.54%   |
| 5.8.6   | 1         | 0.54%   |
| 5.8.4   | 1         | 0.54%   |
| 5.8.11  | 1         | 0.54%   |
| 5.7.4   | 1         | 0.54%   |
| 5.7.17  | 1         | 0.54%   |
| 5.6.6   | 1         | 0.54%   |
| 5.6.14  | 1         | 0.54%   |
| 5.4.83  | 1         | 0.54%   |
| 5.4.64  | 1         | 0.54%   |
| 5.4.61  | 1         | 0.54%   |
| 5.18.6  | 1         | 0.54%   |
| 5.17.9  | 1         | 0.54%   |
| 5.17.7  | 1         | 0.54%   |
| 5.17.6  | 1         | 0.54%   |
| 5.17.1  | 1         | 0.54%   |
| 5.16.0  | 1         | 0.54%   |
| 5.15.8  | 1         | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 39        | 21.55%  |
| 5.15    | 16        | 8.84%   |
| 5.11    | 15        | 8.29%   |
| 5.13    | 13        | 7.18%   |
| 5.3     | 12        | 6.63%   |
| 5.10    | 12        | 6.63%   |
| 5.16    | 11        | 6.08%   |
| 5.8     | 10        | 5.52%   |
| 5.17    | 7         | 3.87%   |
| 5.0     | 7         | 3.87%   |
| 4.15    | 7         | 3.87%   |
| 4.18    | 6         | 3.31%   |
| 5.12    | 4         | 2.21%   |
| 4.9     | 4         | 2.21%   |
| 5.18    | 3         | 1.66%   |
| 5.14    | 3         | 1.66%   |
| 5.9     | 2         | 1.1%    |
| 5.7     | 2         | 1.1%    |
| 5.6     | 2         | 1.1%    |
| 5.19    | 2         | 1.1%    |
| 4.19    | 2         | 1.1%    |
| 5.1     | 1         | 0.55%   |
| 4.16    | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 160       | 95.24%  |
| i686   | 8         | 4.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 84        | 48.55%  |
| KDE5            | 24        | 13.87%  |
| XFCE            | 15        | 8.67%   |
| Unknown         | 15        | 8.67%   |
| X-Cinnamon      | 7         | 4.05%   |
| KDE             | 6         | 3.47%   |
| MATE            | 5         | 2.89%   |
| Pantheon        | 4         | 2.31%   |
| KDE4            | 4         | 2.31%   |
| LXDE            | 2         | 1.16%   |
| i3              | 2         | 1.16%   |
| Unity           | 1         | 0.58%   |
| spectrwm        | 1         | 0.58%   |
| LXQt            | 1         | 0.58%   |
| GNOME Flashback | 1         | 0.58%   |
| Budgie          | 1         | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 134       | 77.91%  |
| Wayland | 24        | 13.95%  |
| Unknown | 13        | 7.56%   |
| Tty     | 1         | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 84        | 48.55%  |
| GDM     | 32        | 18.5%   |
| SDDM    | 22        | 12.72%  |
| LightDM | 18        | 10.4%   |
| GDM3    | 10        | 5.78%   |
| KDM     | 4         | 2.31%   |
| TDM     | 2         | 1.16%   |
| XDM     | 1         | 0.58%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_PE   | 81        | 47.09%  |
| en_US   | 45        | 26.16%  |
| es_ES   | 18        | 10.47%  |
| Unknown | 16        | 9.3%    |
| C       | 3         | 1.74%   |
| it_IT   | 2         | 1.16%   |
| en_GB   | 2         | 1.16%   |
| fr_FR   | 1         | 0.58%   |
| es_MX   | 1         | 0.58%   |
| es_CO   | 1         | 0.58%   |
| Default | 1         | 0.58%   |
| ca_ES   | 1         | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 93        | 54.71%  |
| BIOS | 77        | 45.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 136       | 79.07%  |
| Overlay | 15        | 8.72%   |
| Btrfs   | 8         | 4.65%   |
| Unknown | 7         | 4.07%   |
| Xfs     | 5         | 2.91%   |
| Ext3    | 1         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 96        | 56.14%  |
| GPT     | 57        | 33.33%  |
| MBR     | 18        | 10.53%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 149       | 88.17%  |
| Yes       | 20        | 11.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 57.4%   |
| Yes       | 72        | 42.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 48        | 28.74%  |
| Hewlett-Packard     | 43        | 25.75%  |
| Dell                | 19        | 11.38%  |
| ASUSTek Computer    | 18        | 10.78%  |
| Toshiba             | 12        | 7.19%   |
| Acer                | 12        | 7.19%   |
| Sony                | 4         | 2.4%    |
| MSI                 | 2         | 1.2%    |
| Samsung Electronics | 1         | 0.6%    |
| Razer               | 1         | 0.6%    |
| HUAWEI              | 1         | 0.6%    |
| efirstview          | 1         | 0.6%    |
| Compal              | 1         | 0.6%    |
| Chuwi               | 1         | 0.6%    |
| Apple               | 1         | 0.6%    |
| Advance             | 1         | 0.6%    |
| Unknown             | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo V330-15IKB 81AX                                | 4         | 2.4%    |
| Lenovo V310-15ISK 80SY                                | 3         | 1.8%    |
| HP Pavilion Laptop 15-cw1xxx                          | 3         | 1.8%    |
| Lenovo IdeaPad S540-14API 81NH                        | 2         | 1.2%    |
| Lenovo IdeaPad S145-15IWL 81MV                        | 2         | 1.2%    |
| Lenovo IdeaPad 330S-14IKB 81F4                        | 2         | 1.2%    |
| Lenovo IdeaPad 3 14ADA05 81W0                         | 2         | 1.2%    |
| HP ProBook 645 G4                                     | 2         | 1.2%    |
| HP Laptop 15-ef1xxx                                   | 2         | 1.2%    |
| HP 450                                                | 2         | 1.2%    |
| HP 14                                                 | 2         | 1.2%    |
| Dell XPS 13 9360                                      | 2         | 1.2%    |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV              | 2         | 1.2%    |
| Toshiba Satellite P755                                | 1         | 0.6%    |
| Toshiba Satellite L855                                | 1         | 0.6%    |
| Toshiba Satellite L45-B                               | 1         | 0.6%    |
| Toshiba Satellite L35                                 | 1         | 0.6%    |
| Toshiba Satellite E205                                | 1         | 0.6%    |
| Toshiba Satellite C845                                | 1         | 0.6%    |
| Toshiba Satellite C655D                               | 1         | 0.6%    |
| Toshiba Satellite C645                                | 1         | 0.6%    |
| Toshiba Satellite C55-B                               | 1         | 0.6%    |
| Toshiba Satellite A665                                | 1         | 0.6%    |
| Toshiba QOSMIO X775                                   | 1         | 0.6%    |
| Toshiba NB505                                         | 1         | 0.6%    |
| Sony VPCEC2JFX                                        | 1         | 0.6%    |
| Sony VGN-FW56M                                        | 1         | 0.6%    |
| Sony VGN-FW170J                                       | 1         | 0.6%    |
| Sony SVF15A17CLB                                      | 1         | 0.6%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.6%    |
| Razer Blade                                           | 1         | 0.6%    |
| MSI Prestige 14 A10SC                                 | 1         | 0.6%    |
| MSI GL65 Leopard 10SEK                                | 1         | 0.6%    |
| Lenovo Yoga 2 11 20332                                | 1         | 0.6%    |
| Lenovo Y70-70 Touch 80DU                              | 1         | 0.6%    |
| Lenovo V310-14ISK 80SX                                | 1         | 0.6%    |
| Lenovo V15-IIL 82C5                                   | 1         | 0.6%    |
| Lenovo V14-ARE 82DQ                                   | 1         | 0.6%    |
| Lenovo ThinkPad X140e 20BLA00C00                      | 1         | 0.6%    |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9005MUS            | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 14        | 8.38%   |
| Lenovo IdeaPad    | 13        | 7.78%   |
| HP Pavilion       | 13        | 7.78%   |
| Toshiba Satellite | 10        | 5.99%   |
| Acer Aspire       | 10        | 5.99%   |
| Dell Latitude     | 7         | 4.19%   |
| HP ProBook        | 6         | 3.59%   |
| Dell Inspiron     | 6         | 3.59%   |
| ASUS VivoBook     | 6         | 3.59%   |
| HP Laptop         | 5         | 2.99%   |
| Lenovo V330-15IKB | 4         | 2.4%    |
| Lenovo V310-15ISK | 3         | 1.8%    |
| Lenovo Legion     | 3         | 1.8%    |
| HP ZBook          | 2         | 1.2%    |
| HP ENVY           | 2         | 1.2%    |
| HP 450            | 2         | 1.2%    |
| HP 240            | 2         | 1.2%    |
| HP 14             | 2         | 1.2%    |
| Dell XPS          | 2         | 1.2%    |
| ASUS ROG          | 2         | 1.2%    |
| ASUS ASUS         | 2         | 1.2%    |
| Toshiba QOSMIO    | 1         | 0.6%    |
| Toshiba NB505     | 1         | 0.6%    |
| Sony VPCEC2JFX    | 1         | 0.6%    |
| Sony VGN-FW56M    | 1         | 0.6%    |
| Sony VGN-FW170J   | 1         | 0.6%    |
| Sony SVF15A17CLB  | 1         | 0.6%    |
| Samsung 300E5EV   | 1         | 0.6%    |
| Razer Blade       | 1         | 0.6%    |
| MSI Prestige      | 1         | 0.6%    |
| MSI GL65          | 1         | 0.6%    |
| Lenovo Yoga       | 1         | 0.6%    |
| Lenovo Y70-70     | 1         | 0.6%    |
| Lenovo V310-14ISK | 1         | 0.6%    |
| Lenovo V15-IIL    | 1         | 0.6%    |
| Lenovo V14-ARE    | 1         | 0.6%    |
| Lenovo G570       | 1         | 0.6%    |
| Lenovo G50-70     | 1         | 0.6%    |
| Lenovo G480       | 1         | 0.6%    |
| Lenovo G475       | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 21        | 12.57%  |
| 2019 | 20        | 11.98%  |
| 2018 | 18        | 10.78%  |
| 2012 | 18        | 10.78%  |
| 2017 | 15        | 8.98%   |
| 2016 | 15        | 8.98%   |
| 2011 | 14        | 8.38%   |
| 2014 | 13        | 7.78%   |
| 2013 | 11        | 6.59%   |
| 2021 | 5         | 2.99%   |
| 2015 | 4         | 2.4%    |
| 2010 | 4         | 2.4%    |
| 2009 | 3         | 1.8%    |
| 2008 | 3         | 1.8%    |
| 2007 | 2         | 1.2%    |
| 2006 | 1         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 167       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 150       | 89.82%  |
| Enabled  | 17        | 10.18%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 167       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 51        | 29.65%  |
| 8.01-16.0   | 44        | 25.58%  |
| 3.01-4.0    | 36        | 20.93%  |
| 16.01-24.0  | 28        | 16.28%  |
| 2.01-3.0    | 4         | 2.33%   |
| 1.01-2.0    | 4         | 2.33%   |
| 0.51-1.0    | 2         | 1.16%   |
| 32.01-64.0  | 1         | 0.58%   |
| 24.01-32.0  | 1         | 0.58%   |
| 64.01-256.0 | 1         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 59        | 32.07%  |
| 2.01-3.0  | 56        | 30.43%  |
| 4.01-8.0  | 26        | 14.13%  |
| 3.01-4.0  | 22        | 11.96%  |
| 0.51-1.0  | 14        | 7.61%   |
| 8.01-16.0 | 6         | 3.26%   |
| 0.01-0.5  | 1         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 126       | 75%     |
| 2      | 39        | 23.21%  |
| 3      | 2         | 1.19%   |
| 0      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 59.88%  |
| Yes       | 67        | 40.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 86.9%   |
| No        | 22        | 13.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 99.4%   |
| No        | 1         | 0.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 82.63%  |
| No        | 29        | 17.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Peru    | 167       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lima                  | 115       | 66.86%  |
| Arequipa              | 17        | 9.88%   |
| Trujillo              | 12        | 6.98%   |
| Cusco                 | 4         | 2.33%   |
| Piura                 | 3         | 1.74%   |
| Chiclayo              | 3         | 1.74%   |
| Tacna                 | 2         | 1.16%   |
| Huancayo              | 2         | 1.16%   |
| Callao                | 2         | 1.16%   |
| San Vicente de Canete | 1         | 0.58%   |
| San Isidro            | 1         | 0.58%   |
| San Borja             | 1         | 0.58%   |
| Punta Colorada        | 1         | 0.58%   |
| Oxapampa              | 1         | 0.58%   |
| Moquegua              | 1         | 0.58%   |
| Juliaca               | 1         | 0.58%   |
| Iquitos               | 1         | 0.58%   |
| Ica                   | 1         | 0.58%   |
| Distrito de Lima      | 1         | 0.58%   |
| Barranco              | 1         | 0.58%   |
| Abancay               | 1         | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba                        | 39        | 47     | 19.12%  |
| WDC                            | 35        | 41     | 17.16%  |
| Seagate                        | 30        | 34     | 14.71%  |
| Kingston                       | 22        | 28     | 10.78%  |
| SanDisk                        | 10        | 12     | 4.9%    |
| Samsung Electronics            | 10        | 13     | 4.9%    |
| Crucial                        | 7         | 8      | 3.43%   |
| SK hynix                       | 5         | 6      | 2.45%   |
| Hitachi                        | 5         | 7      | 2.45%   |
| KIOXIA                         | 4         | 5      | 1.96%   |
| Intel                          | 4         | 5      | 1.96%   |
| HGST                           | 4         | 4      | 1.96%   |
| Unknown                        | 3         | 3      | 1.47%   |
| Micron Technology              | 3         | 3      | 1.47%   |
| LITEON                         | 3         | 3      | 1.47%   |
| Hewlett-Packard                | 2         | 2      | 0.98%   |
| China                          | 2         | 2      | 0.98%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.49%   |
| UMIS                           | 1         | 1      | 0.49%   |
| TO Exter                       | 1         | 2      | 0.49%   |
| Solid State Storage Technology | 1         | 1      | 0.49%   |
| Silicon Motion                 | 1         | 1      | 0.49%   |
| Phison                         | 1         | 1      | 0.49%   |
| Netac                          | 1         | 1      | 0.49%   |
| KingSpec                       | 1         | 1      | 0.49%   |
| ITHOO                          | 1         | 1      | 0.49%   |
| GLOWAY                         | 1         | 1      | 0.49%   |
| Gigabyte Technology            | 1         | 1      | 0.49%   |
| Fujitsu                        | 1         | 1      | 0.49%   |
| Dogfish                        | 1         | 1      | 0.49%   |
| Apple                          | 1         | 1      | 0.49%   |
| A-DATA Technology              | 1         | 1      | 0.49%   |
| Unknown                        | 1         | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 14        | 6.7%    |
| Toshiba MQ01ABD100 1TB               | 9         | 4.31%   |
| Toshiba MQ04ABF100 1TB               | 8         | 3.83%   |
| Kingston SA400S37240G 240GB SSD      | 8         | 3.83%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 6         | 2.87%   |
| Toshiba MQ01ABF050 500GB             | 5         | 2.39%   |
| WDC WD10SPZX-24Z10 1TB               | 3         | 1.44%   |
| WDC WD10JPCX-24UE4T0 1TB             | 3         | 1.44%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.44%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.96%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.96%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.96%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.96%   |
| Toshiba MK2565GSXN 250GB             | 2         | 0.96%   |
| Toshiba HDWJ110 1TB                  | 2         | 0.96%   |
| Seagate ST9500325AS 500GB            | 2         | 0.96%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.96%   |
| SanDisk NVMe SSD Drive 1TB           | 2         | 0.96%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.96%   |
| Intel SSDPEKNU512GZ 512GB            | 2         | 0.96%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.96%   |
| HP SSD S700 500GB                    | 2         | 0.96%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.96%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.48%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD     | 1         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.48%   |
| WDC WDS200T2B0A-00SM50 2TB SSD       | 1         | 0.48%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.48%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.48%   |
| WDC WD5000LPVT-24G33T1 500GB         | 1         | 0.48%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 0.48%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 0.48%   |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 0.48%   |
| WDC WD2500BEVS-00UST0 250GB          | 1         | 0.48%   |
| WDC WD10SPCX-60KHST0 1TB             | 1         | 0.48%   |
| WDC WD10SPCX-08S8TT0 1TB             | 1         | 0.48%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 38        | 46     | 38.38%  |
| Seagate | 30        | 33     | 30.3%   |
| WDC     | 20        | 23     | 20.2%   |
| Hitachi | 5         | 7      | 5.05%   |
| HGST    | 4         | 4      | 4.04%   |
| Fujitsu | 1         | 1      | 1.01%   |
| Apple   | 1         | 1      | 1.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 19        | 23     | 31.15%  |
| WDC                 | 13        | 14     | 21.31%  |
| Crucial             | 6         | 7      | 9.84%   |
| SanDisk             | 5         | 7      | 8.2%    |
| Samsung Electronics | 3         | 3      | 4.92%   |
| LITEON              | 3         | 3      | 4.92%   |
| Hewlett-Packard     | 2         | 2      | 3.28%   |
| China               | 2         | 2      | 3.28%   |
| TO Exter            | 1         | 2      | 1.64%   |
| SK hynix            | 1         | 2      | 1.64%   |
| Seagate             | 1         | 1      | 1.64%   |
| Netac               | 1         | 1      | 1.64%   |
| KingSpec            | 1         | 1      | 1.64%   |
| GLOWAY              | 1         | 1      | 1.64%   |
| Dogfish             | 1         | 1      | 1.64%   |
| A-DATA Technology   | 1         | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 98        | 115    | 49.75%  |
| SSD     | 56        | 71     | 28.43%  |
| NVMe    | 39        | 50     | 19.8%   |
| MMC     | 3         | 3      | 1.52%   |
| Unknown | 1         | 1      | 0.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 135       | 184    | 75.42%  |
| NVMe | 39        | 50     | 21.79%  |
| MMC  | 3         | 3      | 1.68%   |
| SAS  | 2         | 3      | 1.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 103    | 51.68%  |
| 0.51-1.0   | 71        | 82     | 47.65%  |
| 1.01-2.0   | 1         | 1      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 50        | 28.9%   |
| 251-500        | 38        | 21.97%  |
| 501-1000       | 37        | 21.39%  |
| 21-50          | 12        | 6.94%   |
| 51-100         | 12        | 6.94%   |
| 1-20           | 10        | 5.78%   |
| 1001-2000      | 8         | 4.62%   |
| More than 3000 | 2         | 1.16%   |
| 2001-3000      | 2         | 1.16%   |
| Unknown        | 2         | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 69        | 39.43%  |
| 21-50     | 43        | 24.57%  |
| 101-250   | 22        | 12.57%  |
| 51-100    | 15        | 8.57%   |
| 251-500   | 12        | 6.86%   |
| 501-1000  | 9         | 5.14%   |
| 1001-2000 | 2         | 1.14%   |
| Unknown   | 2         | 1.14%   |
| 2001-3000 | 1         | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 1      | 6.67%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 1      | 6.67%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 1      | 6.67%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 6.67%   |
| Toshiba MQ01ABF050 500GB         | 1         | 1      | 6.67%   |
| Toshiba MK2035GSS 200GB          | 1         | 1      | 6.67%   |
| Toshiba HDWJ110 1TB              | 1         | 1      | 6.67%   |
| Seagate ST9500325AS 500GB        | 1         | 1      | 6.67%   |
| Seagate ST1000LM014-1EJ164 1TB   | 1         | 1      | 6.67%   |
| Kingston SA400S37480G 480GB SSD  | 1         | 1      | 6.67%   |
| Hitachi HTS725050A7E630 500GB    | 1         | 1      | 6.67%   |
| Hitachi HTS545050B9A300 500GB    | 1         | 1      | 6.67%   |
| Hitachi HTS545050A7E380 500GB    | 1         | 3      | 6.67%   |
| Hitachi HTS545032B9A302 320GB    | 1         | 1      | 6.67%   |
| HGST HTS721010A9E630 1TB         | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 4         | 4      | 26.67%  |
| Hitachi  | 4         | 6      | 26.67%  |
| WDC      | 3         | 3      | 20%     |
| Seagate  | 2         | 2      | 13.33%  |
| Kingston | 1         | 1      | 6.67%   |
| HGST     | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 33.33%  |
| Hitachi | 4         | 6      | 33.33%  |
| Seagate | 2         | 2      | 16.67%  |
| WDC     | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 14     | 80%     |
| SSD  | 3         | 3      | 20%     |

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
| Detected | 103       | 146    | 58.52%  |
| Works    | 58        | 75     | 32.95%  |
| Malfunc  | 14        | 17     | 7.95%   |
| Failed   | 1         | 2      | 0.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 123       | 66.49%  |
| AMD                              | 24        | 12.97%  |
| SanDisk                          | 9         | 4.86%   |
| Samsung Electronics              | 7         | 3.78%   |
| SK hynix                         | 4         | 2.16%   |
| KIOXIA                           | 4         | 2.16%   |
| Micron Technology                | 3         | 1.62%   |
| Kingston Technology Company      | 3         | 1.62%   |
| Unknown                          | 1         | 0.54%   |
| Union Memory (Shenzhen)          | 1         | 0.54%   |
| Toshiba America Info Systems     | 1         | 0.54%   |
| Solid State Storage Technology   | 1         | 0.54%   |
| Silicon Motion                   | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] | 1         | 0.54%   |
| Phison Electronics               | 1         | 0.54%   |
| Micron/Crucial Technology        | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 25        | 12.95%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 10.88%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 8.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 15        | 7.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 5.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 4.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 3.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.07%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 2.07%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 2.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.07%   |
| SK hynix BC511                                                                 | 3         | 1.55%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 1.55%   |
| Micron Non-Volatile memory controller                                          | 3         | 1.55%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.04%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 1.04%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.04%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.04%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.04%   |
| Unknown Non-Volatile memory controller                                         | 1         | 0.52%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.52%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.52%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.52%   |
| SK hynix Gold P31 SSD                                                          | 1         | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.52%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.52%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.52%   |
| Phison NVMe Storage Controller                                                 | 1         | 0.52%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.52%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.52%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 125       | 66.84%  |
| NVMe | 39        | 20.86%  |
| RAID | 18        | 9.63%   |
| IDE  | 5         | 2.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 134       | 80.24%  |
| AMD    | 33        | 19.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 7         | 4.19%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 6         | 3.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 6         | 3.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 6         | 3.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 4         | 2.4%    |
| Intel Core i5-8265U CPU @ 1.60GHz               | 4         | 2.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz               | 4         | 2.4%    |
| Intel Core i3-4005U CPU @ 1.70GHz               | 4         | 2.4%    |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 3         | 1.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz               | 3         | 1.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 1.8%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 3         | 1.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.2%    |
| Intel Core i7-5500U CPU @ 2.40GHz               | 2         | 1.2%    |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 1.2%    |
| Intel Core i5-4210U CPU @ 1.70GHz               | 2         | 1.2%    |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 1.2%    |
| Intel Core i5-2450M CPU @ 2.50GHz               | 2         | 1.2%    |
| Intel Core i3-7020U CPU @ 2.30GHz               | 2         | 1.2%    |
| Intel Core i3-6006U CPU @ 2.00GHz               | 2         | 1.2%    |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 1.2%    |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 1.2%    |
| Intel Core i3-2328M CPU @ 2.20GHz               | 2         | 1.2%    |
| Intel Celeron CPU 550 @ 2.00GHz                 | 2         | 1.2%    |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 2         | 1.2%    |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.2%    |
| AMD Ryzen 5 4500U with Radeon Graphics          | 2         | 1.2%    |
| AMD Athlon Silver 3050U with Radeon Graphics    | 2         | 1.2%    |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.6%    |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.6%    |
| Intel Genuine CPU T2300 @ 1.66GHz               | 1         | 0.6%    |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 0.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 0.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.6%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 0.6%    |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 0.6%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz              | 1         | 0.6%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 52        | 31.14%  |
| Intel Core i5    | 41        | 24.55%  |
| Intel Core i3    | 23        | 13.77%  |
| AMD Ryzen 5      | 10        | 5.99%   |
| Intel Celeron    | 6         | 3.59%   |
| AMD Ryzen 7      | 6         | 3.59%   |
| Other            | 5         | 2.99%   |
| Intel Atom       | 3         | 1.8%    |
| Intel Pentium    | 2         | 1.2%    |
| Intel Core 2 Duo | 2         | 1.2%    |
| AMD Ryzen 9      | 2         | 1.2%    |
| AMD Ryzen 7 PRO  | 2         | 1.2%    |
| AMD Ryzen 3      | 2         | 1.2%    |
| AMD E1           | 2         | 1.2%    |
| AMD Athlon       | 2         | 1.2%    |
| AMD A8           | 2         | 1.2%    |
| Intel Genuine    | 1         | 0.6%    |
| Intel Celeron M  | 1         | 0.6%    |
| AMD E            | 1         | 0.6%    |
| AMD C-50         | 1         | 0.6%    |
| AMD A12          | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 84        | 50.3%   |
| 4       | 62        | 37.13%  |
| 8       | 7         | 4.19%   |
| 6       | 7         | 4.19%   |
| 1       | 6         | 3.59%   |
| Unknown | 1         | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 167       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 141       | 84.43%  |
| 1       | 25        | 14.97%  |
| Unknown | 1         | 0.6%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 161       | 95.27%  |
| 64-bit         | 3         | 1.78%   |
| 32-bit         | 3         | 1.78%   |
| Unknown        | 2         | 1.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 14.2%   |
| 0x206a7    | 15        | 8.88%   |
| 0x306a9    | 12        | 7.1%    |
| 0x40651    | 10        | 5.92%   |
| 0x806ea    | 9         | 5.33%   |
| 0x406e3    | 9         | 5.33%   |
| 0x806ec    | 8         | 4.73%   |
| 0x806e9    | 8         | 4.73%   |
| 0x08108109 | 7         | 4.14%   |
| 0x306d4    | 6         | 3.55%   |
| 0x906ea    | 5         | 2.96%   |
| 0x08108102 | 5         | 2.96%   |
| 0x306c3    | 4         | 2.37%   |
| 0x806eb    | 3         | 1.78%   |
| 0x30678    | 3         | 1.78%   |
| 0x20655    | 3         | 1.78%   |
| 0xa0652    | 2         | 1.18%   |
| 0x906e9    | 2         | 1.18%   |
| 0x806c1    | 2         | 1.18%   |
| 0x706e5    | 2         | 1.18%   |
| 0x20652    | 2         | 1.18%   |
| 0x10661    | 2         | 1.18%   |
| 0x08600106 | 2         | 1.18%   |
| 0x08600104 | 2         | 1.18%   |
| 0x05000029 | 2         | 1.18%   |
| 0x706a1    | 1         | 0.59%   |
| 0x6e8      | 1         | 0.59%   |
| 0x6d8      | 1         | 0.59%   |
| 0x506e3    | 1         | 0.59%   |
| 0x406c4    | 1         | 0.59%   |
| 0x106ca    | 1         | 0.59%   |
| 0x106c2    | 1         | 0.59%   |
| 0x1067a    | 1         | 0.59%   |
| 0x10676    | 1         | 0.59%   |
| 0x0a50000c | 1         | 0.59%   |
| 0x08600102 | 1         | 0.59%   |
| 0x08101016 | 1         | 0.59%   |
| 0x0810100b | 1         | 0.59%   |
| 0x08101007 | 1         | 0.59%   |
| 0x07030106 | 1         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 43        | 25.75%  |
| SandyBridge   | 15        | 8.98%   |
| IvyBridge     | 15        | 8.98%   |
| Haswell       | 15        | 8.98%   |
| Zen+          | 13        | 7.78%   |
| Skylake       | 11        | 6.59%   |
| Zen 2         | 6         | 3.59%   |
| Westmere      | 6         | 3.59%   |
| Broadwell     | 6         | 3.59%   |
| Zen           | 4         | 2.4%    |
| Silvermont    | 4         | 2.4%    |
| IceLake       | 3         | 1.8%    |
| Excavator     | 3         | 1.8%    |
| CometLake     | 3         | 1.8%    |
| TigerLake     | 2         | 1.2%    |
| Puma          | 2         | 1.2%    |
| Penryn        | 2         | 1.2%    |
| P6            | 2         | 1.2%    |
| Core          | 2         | 1.2%    |
| Bonnell       | 2         | 1.2%    |
| Bobcat        | 2         | 1.2%    |
| Zen 3         | 1         | 0.6%    |
| Piledriver    | 1         | 0.6%    |
| Nehalem       | 1         | 0.6%    |
| Jaguar        | 1         | 0.6%    |
| Goldmont plus | 1         | 0.6%    |
| Unknown       | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 124       | 56.62%  |
| AMD                              | 54        | 24.66%  |
| Nvidia                           | 40        | 18.26%  |
| Silicon Integrated Systems [SiS] | 1         | 0.46%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 14        | 6.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 14        | 6.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 13        | 5.73%   |
| Intel UHD Graphics 620                                                                | 12        | 5.29%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 11        | 4.85%   |
| Intel HD Graphics 620                                                                 | 10        | 4.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 9         | 3.96%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 9         | 3.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 3.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 6         | 2.64%   |
| Intel HD Graphics 5500                                                                | 6         | 2.64%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 6         | 2.64%   |
| AMD Renoir                                                                            | 6         | 2.64%   |
| Intel Core Processor Integrated Graphics Controller                                   | 5         | 2.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 2.2%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 4         | 1.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 4         | 1.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 1.32%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 3         | 1.32%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 3         | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 3         | 1.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.88%   |
| Nvidia GM108M [GeForce MX130]                                                         | 2         | 0.88%   |
| Nvidia GM108M [GeForce MX110]                                                         | 2         | 0.88%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 0.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 2         | 0.88%   |
| Intel HD Graphics 630                                                                 | 2         | 0.88%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 2         | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 2         | 0.88%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                     | 1         | 0.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.44%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.44%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                               | 1         | 0.44%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 0.44%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 0.44%   |
| Nvidia GP108GLM [Quadro P520]                                                         | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 74        | 44.31%  |
| Intel + Nvidia | 33        | 19.76%  |
| 1 x AMD        | 30        | 17.96%  |
| Intel + AMD    | 17        | 10.18%  |
| 2 x AMD        | 5         | 2.99%   |
| 1 x Nvidia     | 5         | 2.99%   |
| AMD + Nvidia   | 2         | 1.2%    |
| 1 x SiS        | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 146       | 85.88%  |
| Proprietary | 20        | 11.76%  |
| Unknown     | 4         | 2.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 51.16%  |
| 1.01-2.0   | 39        | 22.67%  |
| 0.01-0.5   | 21        | 12.21%  |
| 3.01-4.0   | 10        | 5.81%   |
| 0.51-1.0   | 8         | 4.65%   |
| 5.01-6.0   | 4         | 2.33%   |
| 7.01-8.0   | 1         | 0.58%   |
| 8.01-16.0  | 1         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 44        | 23.16%  |
| BOE                 | 34        | 17.89%  |
| AU Optronics        | 30        | 15.79%  |
| Samsung Electronics | 24        | 12.63%  |
| LG Display          | 20        | 10.53%  |
| Goldstar            | 5         | 2.63%   |
| Sharp               | 3         | 1.58%   |
| PANDA               | 3         | 1.58%   |
| Hewlett-Packard     | 3         | 1.58%   |
| Sony                | 2         | 1.05%   |
| Lenovo              | 2         | 1.05%   |
| JRY                 | 2         | 1.05%   |
| HannStar            | 2         | 1.05%   |
| Dell                | 2         | 1.05%   |
| AOC                 | 2         | 1.05%   |
| Unknown (XXX)       | 1         | 0.53%   |
| TMX                 | 1         | 0.53%   |
| Mi                  | 1         | 0.53%   |
| LGD                 | 1         | 0.53%   |
| InnoLux Display     | 1         | 0.53%   |
| InfoVision          | 1         | 0.53%   |
| Hitachi             | 1         | 0.53%   |
| EXP                 | 1         | 0.53%   |
| DZX                 | 1         | 0.53%   |
| Apple               | 1         | 0.53%   |
| AGO                 | 1         | 0.53%   |
| Unknown             | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 10        | 5.26%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 6         | 3.16%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 1.58%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 3         | 1.58%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 3         | 1.58%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 1.58%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 2         | 1.05%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 1.05%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 1.05%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 1.05%   |
| JRY HDMI JRY2380 1920x1080 527x296mm 23.8-inch                       | 2         | 1.05%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 2         | 1.05%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 1.05%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                 | 2         | 1.05%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 2         | 1.05%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 1.05%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 2         | 1.05%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                 | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch        | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch        | 2         | 1.05%   |
| Unknown (XXX) MS82PV XXX001A 1360x768 330x210mm 15.4-inch            | 1         | 0.53%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch              | 1         | 0.53%   |
| Sony TV SNYEF03 1600x900                                             | 1         | 0.53%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                        | 1         | 0.53%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch              | 1         | 0.53%   |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 443x249mm 20.0-inch | 1         | 0.53%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch    | 1         | 0.53%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 480x270mm 21.7-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4B45 1366x768 309x174mm 14.0-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 105       | 57.07%  |
| 1920x1080 (FHD)   | 50        | 27.17%  |
| 1600x900 (HD+)    | 6         | 3.26%   |
| 1360x768          | 4         | 2.17%   |
| 3840x2160 (4K)    | 3         | 1.63%   |
| 1280x800 (WXGA)   | 3         | 1.63%   |
| 3200x1800 (QHD+)  | 2         | 1.09%   |
| 1024x600          | 2         | 1.09%   |
| Unknown           | 2         | 1.09%   |
| 3840x1080         | 1         | 0.54%   |
| 3200x2000         | 1         | 0.54%   |
| 2160x1440         | 1         | 0.54%   |
| 1920x1200 (WUXGA) | 1         | 0.54%   |
| 1440x900 (WXGA+)  | 1         | 0.54%   |
| 1280x720 (HD)     | 1         | 0.54%   |
| 1024x768 (XGA)    | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 89        | 47.34%  |
| 13      | 36        | 19.15%  |
| 14      | 25        | 13.3%   |
| 23      | 7         | 3.72%   |
| 17      | 5         | 2.66%   |
| 21      | 3         | 1.6%    |
| 18      | 3         | 1.6%    |
| 72      | 2         | 1.06%   |
| 12      | 2         | 1.06%   |
| 11      | 2         | 1.06%   |
| 10      | 2         | 1.06%   |
| Unknown | 2         | 1.06%   |
| 84      | 1         | 0.53%   |
| 60      | 1         | 0.53%   |
| 54      | 1         | 0.53%   |
| 48      | 1         | 0.53%   |
| 46      | 1         | 0.53%   |
| 39      | 1         | 0.53%   |
| 27      | 1         | 0.53%   |
| 24      | 1         | 0.53%   |
| 20      | 1         | 0.53%   |
| 19      | 1         | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 140       | 75.27%  |
| 201-300     | 12        | 6.45%   |
| 501-600     | 9         | 4.84%   |
| 401-500     | 8         | 4.3%    |
| 351-400     | 7         | 3.76%   |
| 1001-1500   | 4         | 2.15%   |
| 1501-2000   | 3         | 1.61%   |
| Unknown     | 2         | 1.08%   |
| 801-900     | 1         | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 150       | 90.91%  |
| 16/10   | 9         | 5.45%   |
| 4/3     | 3         | 1.82%   |
| Unknown | 2         | 1.21%   |
| 3/2     | 1         | 0.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 89        | 47.34%  |
| 81-90          | 55        | 29.26%  |
| 201-250        | 10        | 5.32%   |
| More than 1000 | 6         | 3.19%   |
| 71-80          | 6         | 3.19%   |
| 121-130        | 4         | 2.13%   |
| 151-200        | 3         | 1.6%    |
| 141-150        | 3         | 1.6%    |
| 51-60          | 2         | 1.06%   |
| 41-50          | 2         | 1.06%   |
| 501-1000       | 2         | 1.06%   |
| Unknown        | 2         | 1.06%   |
| 61-70          | 1         | 0.53%   |
| 301-350        | 1         | 0.53%   |
| 131-140        | 1         | 0.53%   |
| 91-100         | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 106       | 57.61%  |
| 121-160       | 42        | 22.83%  |
| 51-100        | 22        | 11.96%  |
| 1-50          | 6         | 3.26%   |
| More than 240 | 3         | 1.63%   |
| 161-240       | 3         | 1.63%   |
| Unknown       | 2         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 137       | 80.12%  |
| 2     | 28        | 16.37%  |
| 0     | 5         | 2.92%   |
| 3     | 1         | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 112       | 41.79%  |
| Intel                            | 59        | 22.01%  |
| Qualcomm Atheros                 | 53        | 19.78%  |
| Broadcom                         | 12        | 4.48%   |
| TP-Link                          | 7         | 2.61%   |
| Ralink                           | 5         | 1.87%   |
| Marvell Technology Group         | 3         | 1.12%   |
| Xiaomi                           | 2         | 0.75%   |
| Ralink Technology                | 2         | 0.75%   |
| Motorola PCS                     | 2         | 0.75%   |
| ICS Advent                       | 2         | 0.75%   |
| ASIX Electronics                 | 2         | 0.75%   |
| T & A Mobile Phones              | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| Samsung Electronics              | 1         | 0.37%   |
| MediaTek                         | 1         | 0.37%   |
| Lenovo                           | 1         | 0.37%   |
| Broadcom Limited                 | 1         | 0.37%   |
| Apple                            | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 74        | 22.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 6.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 19        | 5.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 13        | 3.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 3.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.84%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.53%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 4         | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.23%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.23%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.23%   |
| Intel Wireless 8260                                               | 4         | 1.23%   |
| Intel Wireless 7260                                               | 4         | 1.23%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 3         | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.92%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.61%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.61%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.61%   |
| Motorola PCS Moto G (5) Plus                                      | 2         | 0.61%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.61%   |
| Intel Wireless 7265                                               | 2         | 0.61%   |
| Intel WiFi Link 5100                                              | 2         | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.61%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 57        | 32.76%  |
| Qualcomm Atheros      | 48        | 27.59%  |
| Realtek Semiconductor | 44        | 25.29%  |
| Broadcom              | 10        | 5.75%   |
| TP-Link               | 6         | 3.45%   |
| Ralink                | 5         | 2.87%   |
| Ralink Technology     | 2         | 1.15%   |
| MediaTek              | 1         | 0.57%   |
| Broadcom Limited      | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 10.92%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 7.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 6.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 4.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 3.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 3.45%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 2.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.87%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 2.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 2.3%    |
| Intel Wireless 8265 / 8275                                              | 4         | 2.3%    |
| Intel Wireless 8260                                                     | 4         | 2.3%    |
| Intel Wireless 7260                                                     | 4         | 2.3%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 3         | 1.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.72%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.15%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.15%   |
| Intel Wireless 7265                                                     | 2         | 1.15%   |
| Intel WiFi Link 5100                                                    | 2         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.15%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.15%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                 | 1         | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.57%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.57%   |
| Realtek RTL8187 Wireless Adapter                                        | 1         | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.57%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.57%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 100       | 66.23%  |
| Intel                            | 21        | 13.91%  |
| Qualcomm Atheros                 | 10        | 6.62%   |
| Marvell Technology Group         | 3         | 1.99%   |
| Broadcom                         | 3         | 1.99%   |
| Xiaomi                           | 2         | 1.32%   |
| Motorola PCS                     | 2         | 1.32%   |
| ICS Advent                       | 2         | 1.32%   |
| ASIX Electronics                 | 2         | 1.32%   |
| TP-Link                          | 1         | 0.66%   |
| T & A Mobile Phones              | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] | 1         | 0.66%   |
| Samsung Electronics              | 1         | 0.66%   |
| Lenovo                           | 1         | 0.66%   |
| Apple                            | 1         | 0.66%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 74        | 48.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 22        | 14.47%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 3.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 2.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 1.32%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 1.32%   |
| Motorola PCS Moto G (5) Plus                                                   | 2         | 1.32%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.32%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.32%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.32%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.32%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 2         | 1.32%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.32%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.66%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                                   | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.66%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.66%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.66%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.66%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.66%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.66%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.66%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.66%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.66%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.66%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.66%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.66%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.66%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.66%   |
| Apple iPad 4/Mini1                                                             | 1         | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 166       | 53.21%  |
| Ethernet | 146       | 46.79%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 131       | 73.18%  |
| Ethernet | 48        | 26.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 133       | 79.64%  |
| 1     | 33        | 19.76%  |
| 0     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 143       | 84.12%  |
| Yes  | 27        | 15.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 28.99%  |
| Realtek Semiconductor           | 31        | 22.46%  |
| Qualcomm Atheros Communications | 28        | 20.29%  |
| Lite-On Technology              | 9         | 6.52%   |
| IMC Networks                    | 8         | 5.8%    |
| Toshiba                         | 4         | 2.9%    |
| Ralink                          | 4         | 2.9%    |
| Broadcom                        | 3         | 2.17%   |
| Hewlett-Packard                 | 2         | 1.45%   |
| Foxconn / Hon Hai               | 2         | 1.45%   |
| Dell                            | 2         | 1.45%   |
| Cambridge Silicon Radio         | 2         | 1.45%   |
| Foxconn International           | 1         | 0.72%   |
| Apple                           | 1         | 0.72%   |
| Alps Electric                   | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 16        | 11.59%  |
| Intel Bluetooth wireless interface                  | 16        | 11.59%  |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 10.87%  |
| Realtek Bluetooth Radio                             | 15        | 10.87%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 5.8%    |
| Intel AX201 Bluetooth                               | 7         | 5.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 3.62%   |
| Ralink RT3290 Bluetooth                             | 4         | 2.9%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 2.17%   |
| Lite-On Bluetooth Device                            | 3         | 2.17%   |
| Intel AX200 Bluetooth                               | 3         | 2.17%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.17%   |
| IMC Networks Bluetooth Device                       | 3         | 2.17%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.45%   |
| Lite-On Bluetooth Radio                             | 2         | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.45%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.72%   |
| Toshiba Bluetooth Device                            | 1         | 0.72%   |
| Toshiba BCM43142A0                                  | 1         | 0.72%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.72%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.72%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.72%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.72%   |
| IMC Networks Wireless_Device                        | 1         | 0.72%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.72%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.72%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.72%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.72%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.72%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.72%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 131       | 68.23%  |
| AMD                              | 37        | 19.27%  |
| Nvidia                           | 18        | 9.38%   |
| Silicon Integrated Systems [SiS] | 1         | 0.52%   |
| Razer USA                        | 1         | 0.52%   |
| Pixart Imaging                   | 1         | 0.52%   |
| Hewlett-Packard                  | 1         | 0.52%   |
| Generalplus Technology           | 1         | 0.52%   |
| C-Media Electronics              | 1         | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 32        | 13.11%  |
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 9.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 8.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 17        | 6.97%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 4.51%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 4.1%    |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 2.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 2.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 2.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 2.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.46%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 2.46%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.64%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.64%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.23%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.23%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 0.82%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.82%   |
| AMD High Definition Audio Controller                                       | 2         | 0.82%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.41%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1         | 0.41%   |
| Pixart Imaging Multimedia audio controller                                 | 1         | 0.41%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.41%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.41%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.41%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 30.77%  |
| SK hynix            | 30        | 23.08%  |
| Micron Technology   | 20        | 15.38%  |
| Kingston            | 17        | 13.08%  |
| Unknown             | 7         | 5.38%   |
| Ramaxel Technology  | 6         | 4.62%   |
| Hewlett-Packard     | 2         | 1.54%   |
| Crucial             | 2         | 1.54%   |
| Unknown (ABCD)      | 1         | 0.77%   |
| Team                | 1         | 0.77%   |
| Patriot             | 1         | 0.77%   |
| Goldkey             | 1         | 0.77%   |
| CSX                 | 1         | 0.77%   |
| Corsair             | 1         | 0.77%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 4.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 3.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 3.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.21%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 2.21%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.21%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.21%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 2.21%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 1.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.47%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.47%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.47%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.47%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 1.47%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 1.47%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s          | 2         | 1.47%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 0.74%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.74%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.74%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 0.74%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.74%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 45        | 48.91%  |
| DDR3   | 35        | 38.04%  |
| LPDDR4 | 6         | 6.52%   |
| LPDDR3 | 3         | 3.26%   |
| DDR2   | 2         | 2.17%   |
| SDRAM  | 1         | 1.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 88        | 95.65%  |
| Row Of Chips | 4         | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 48        | 42.48%  |
| 8192  | 47        | 41.59%  |
| 2048  | 9         | 7.96%   |
| 16384 | 7         | 6.19%   |
| 1024  | 1         | 0.88%   |
| 512   | 1         | 0.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 39        | 35.14%  |
| 1600    | 28        | 25.23%  |
| 3200    | 13        | 11.71%  |
| 2400    | 7         | 6.31%   |
| 3266    | 6         | 5.41%   |
| 1333    | 5         | 4.5%    |
| 2133    | 3         | 2.7%    |
| 1334    | 3         | 2.7%    |
| Unknown | 3         | 2.7%    |
| 1867    | 2         | 1.8%    |
| 1067    | 2         | 1.8%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 25%     |
| Hewlett-Packard    | 1         | 25%     |
| Canon              | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series       | 1         | 25%     |
| HP LaserJet Professional P 1102w | 1         | 25%     |
| Canon E400 series                | 1         | 25%     |
| Brother DCP-T300                 | 1         | 25%     |

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
| Chicony Electronics                    | 35        | 21.6%   |
| IMC Networks                           | 17        | 10.49%  |
| Acer                                   | 15        | 9.26%   |
| Realtek Semiconductor                  | 13        | 8.02%   |
| Microdia                               | 12        | 7.41%   |
| Syntek                                 | 10        | 6.17%   |
| Sunplus Innovation Technology          | 10        | 6.17%   |
| Quanta                                 | 9         | 5.56%   |
| Lite-On Technology                     | 9         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.56%   |
| Suyin                                  | 7         | 4.32%   |
| Importek                               | 4         | 2.47%   |
| Sonix Technology                       | 2         | 1.23%   |
| Samsung Electronics                    | 2         | 1.23%   |
| Ricoh                                  | 2         | 1.23%   |
| Alcor Micro                            | 2         | 1.23%   |
| Luxvisions Innotech Limited            | 1         | 0.62%   |
| Logitech                               | 1         | 0.62%   |
| Apple                                  | 1         | 0.62%   |
| ANYKA                                  | 1         | 0.62%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 8         | 4.91%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 6         | 3.68%   |
| Lite-On Integrated Camera                                                  | 4         | 2.45%   |
| IMC Networks Integrated Camera                                             | 4         | 2.45%   |
| Chicony Integrated Camera                                                  | 4         | 2.45%   |
| Chicony EasyCamera                                                         | 4         | 2.45%   |
| Acer Integrated Camera                                                     | 4         | 2.45%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 1.84%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 1.84%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 1.84%   |
| Lite-On HP HD Camera                                                       | 3         | 1.84%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.84%   |
| Chicony HP Truevision HD                                                   | 3         | 1.84%   |
| Chicony HD WebCam                                                          | 3         | 1.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.84%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 1.23%   |
| Sunplus Integrated Webcam                                                  | 2         | 1.23%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 2         | 1.23%   |
| Samsung Galaxy A5 (MTP)                                                    | 2         | 1.23%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 1.23%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 1.23%   |
| Realtek Integrated Webcam                                                  | 2         | 1.23%   |
| Quanta HP Webcam                                                           | 2         | 1.23%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 1.23%   |
| IMC Networks HP TrueVision HD Camera                                       | 2         | 1.23%   |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 1.23%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.23%   |
| Chicony HP Webcam                                                          | 2         | 1.23%   |
| Chicony HP TrueVision HD Camera                                            | 2         | 1.23%   |
| Chicony HP HD Camera                                                       | 2         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.23%   |
| Alcor Micro TOSHIBA Web Camera - MP                                        | 2         | 1.23%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 1.23%   |
| Acer EasyCamera                                                            | 2         | 1.23%   |
| Syntek USB Video Device                                                    | 1         | 0.61%   |
| Syntek USB Camera Device                                                   | 1         | 0.61%   |
| Suyin USB 2.0 Camera                                                       | 1         | 0.61%   |
| Suyin TOSHIBA Web Camera - HD                                              | 1         | 0.61%   |
| Suyin HP Truevision HD                                                     | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 50%     |
| Synaptics                  | 11        | 28.95%  |
| Shenzhen Goodix Technology | 3         | 7.89%   |
| Elan Microelectronics      | 3         | 7.89%   |
| STMicroelectronics         | 1         | 2.63%   |
| AuthenTec                  | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 6         | 15.79%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 15.79%  |
| Synaptics  WBDI                                            | 4         | 10.53%  |
| Validity Sensors Fingerprint scanner                       | 2         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 5.26%   |
| Elan ELAN:Fingerprint                                      | 2         | 5.26%   |
| Unknown                                                    | 2         | 5.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.63%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.63%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.63%   |
| Validity Sensors Synaptics WBDI                            | 1         | 2.63%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 2.63%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.63%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.63%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.63%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 2.63%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.63%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.63%   |

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
| 0     | 103       | 60.23%  |
| 1     | 59        | 34.5%   |
| 2     | 8         | 4.68%   |
| 3     | 1         | 0.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 38        | 48.72%  |
| Graphics card         | 11        | 14.1%   |
| Net/wireless          | 9         | 11.54%  |
| Chipcard              | 9         | 11.54%  |
| Bluetooth             | 5         | 6.41%   |
| Multimedia controller | 2         | 2.56%   |
| Card reader           | 2         | 2.56%   |
| Storage               | 1         | 1.28%   |
| Camera                | 1         | 1.28%   |

