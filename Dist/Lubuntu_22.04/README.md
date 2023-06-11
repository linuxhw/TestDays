Lubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Lubuntu_22.04/Notebook/README.md).

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

Total: 354

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| HP            | 3646h                       | Desktop     | [046f5d1a5b](https://linux-hardware.org/?probe=046f5d1a5b) | Jun 09, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | Notebook    | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| HP            | 3646h                       | Desktop     | [02353b5e9f](https://linux-hardware.org/?probe=02353b5e9f) | Jun 06, 2023 |
| HP            | 240 G3                      | Notebook    | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [88c6b12404](https://linux-hardware.org/?probe=88c6b12404) | May 27, 2023 |
| Dell          | Latitude E6430              | Notebook    | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbab0f6dd8](https://linux-hardware.org/?probe=cbab0f6dd8) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [20c80a45a8](https://linux-hardware.org/?probe=20c80a45a8) | May 22, 2023 |
| Foxconn       | G41MXE-V                    | Desktop     | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [eea6382d39](https://linux-hardware.org/?probe=eea6382d39) | May 19, 2023 |
| ZOTAC         | NM10                        | Desktop     | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| Google        | Snappy                      | Notebook    | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | Notebook    | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | Notebook    | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Acer          | EQ45M                       | Desktop     | [57fa86c8dc](https://linux-hardware.org/?probe=57fa86c8dc) | May 11, 2023 |
| libre-comp... | roc-rk3328-cc               | Soc         | [9709c9cf35](https://linux-hardware.org/?probe=9709c9cf35) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | Notebook    | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | Notebook    | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6976f884e6](https://linux-hardware.org/?probe=6976f884e6) | Apr 29, 2023 |
| HP            | Laptop 15-bs2xx             | Notebook    | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| Dell          | Latitude 5290               | Notebook    | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | Notebook    | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| GPU Compan... | GWTN116-3                   | Notebook    | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | Notebook    | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | Notebook    | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| Toshiba       | Satellite P70-A             | Notebook    | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b16afcac8b](https://linux-hardware.org/?probe=b16afcac8b) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| YANYU         | ITX-S192                    | Desktop     | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4ce0966b14](https://linux-hardware.org/?probe=4ce0966b14) | Mar 26, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4faa2a52d3](https://linux-hardware.org/?probe=4faa2a52d3) | Mar 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | Notebook    | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| Dell          | Latitude 5290               | Notebook    | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| Dell          | Latitude 7480               | Notebook    | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | Desktop     | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| BANGHO        | LITE E34                    | Desktop     | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Intel         | W7650                       | Notebook    | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Intel         | X79 V2.72A                  | Desktop     | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Google        | Celes                       | Notebook    | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | Notebook    | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Getac         | V200-X                      | Notebook    | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| HP            | Pavilion 17                 | Notebook    | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| Positivo      | Q232A                       | Notebook    | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| HP            | Notebook                    | Notebook    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Getac         | V200-X                      | Notebook    | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | Notebook    | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| MSI           | MS-7267                     | Desktop     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [1fbc4cea88](https://linux-hardware.org/?probe=1fbc4cea88) | Feb 16, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| ECS           | G41T-M7                     | Desktop     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Dell          | 0FPP7F A00                  | Desktop     | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| Acer          | AO756                       | Notebook    | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | Notebook    | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| MSI           | MS-7032                     | Desktop     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | Desktop     | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| ASRock        | ION3D-HT                    | Desktop     | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | Notebook    | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [6ef8fba020](https://linux-hardware.org/?probe=6ef8fba020) | Jan 06, 2023 |
| ASUSTek       | F50SV                       | Notebook    | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | Notebook    | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Google        | Candy                       | Notebook    | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [fd1cdfc132](https://linux-hardware.org/?probe=fd1cdfc132) | Dec 28, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| HP            | 2000                        | Notebook    | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | Notebook    | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Intel         | BTC-T37                     | Desktop     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [2574454ebe](https://linux-hardware.org/?probe=2574454ebe) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3b7077c5ab](https://linux-hardware.org/?probe=3b7077c5ab) | Nov 19, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a922f68180](https://linux-hardware.org/?probe=a922f68180) | Nov 03, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | Notebook    | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | Notebook    | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | Desktop     | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Dell          | 0R849J A00                  | Desktop     | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| ASUSTek       | UX360CAK                    | Convertible | [015df11bc4](https://linux-hardware.org/?probe=015df11bc4) | Sep 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c45724d6d3](https://linux-hardware.org/?probe=c45724d6d3) | Sep 20, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2f9ab4273a](https://linux-hardware.org/?probe=2f9ab4273a) | Sep 20, 2022 |
| Gateway       | NE46R                       | Notebook    | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | Notebook    | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Dell          | 0J584C A00                  | Desktop     | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | Notebook    | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | Notebook    | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| OEM           | Unknown                     | Notebook    | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 8768 A                      | Desktop     | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | Desktop     | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | Desktop     | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | Notebook    | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| Dell          | 0X8582                      | Desktop     | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| Sony          | VPCEB15FM                   | Notebook    | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | Desktop     | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | Desktop     | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| HP            | 1495                        | Desktop     | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| HP            | 1495                        | Desktop     | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Gateway       | Sonic-C                     | Notebook    | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| Dell          | Latitude XT                 | Notebook    | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Intel         | W7650                       | Notebook    | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63ccee44b1](https://linux-hardware.org/?probe=63ccee44b1) | May 28, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | Notebook    | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.15.0-43-generic          | 36        | 12.5%   |
| 5.15.0-56-generic          | 19        | 6.6%    |
| 5.15.0-25-generic          | 16        | 5.56%   |
| 5.15.0-60-generic          | 14        | 4.86%   |
| 5.15.0-58-generic          | 12        | 4.17%   |
| 5.15.0-47-generic          | 12        | 4.17%   |
| 5.15.0-30-generic          | 10        | 3.47%   |
| 5.19.0-41-generic          | 9         | 3.13%   |
| 5.15.0-52-generic          | 9         | 3.13%   |
| 5.15.0-46-generic          | 9         | 3.13%   |
| 5.15.0-41-generic          | 9         | 3.13%   |
| 5.15.0-27-generic          | 9         | 3.13%   |
| 5.19.0-35-generic          | 8         | 2.78%   |
| 5.19.0-32-generic          | 8         | 2.78%   |
| 5.15.0-53-generic          | 8         | 2.78%   |
| 5.15.0-67-generic          | 6         | 2.08%   |
| 5.15.0-50-generic          | 6         | 2.08%   |
| 5.15.0-48-generic          | 6         | 2.08%   |
| 5.15.0-40-generic          | 6         | 2.08%   |
| 5.19.0-43-generic          | 5         | 1.74%   |
| 5.15.0-71-generic          | 5         | 1.74%   |
| 5.15.0-57-generic          | 5         | 1.74%   |
| 5.19.0-40-generic          | 4         | 1.39%   |
| 5.19.0-38-generic          | 4         | 1.39%   |
| 5.15.0-39-generic          | 4         | 1.39%   |
| 5.15.0-35-generic          | 4         | 1.39%   |
| 5.15.0-33-generic          | 4         | 1.39%   |
| 5.19.0-42-generic          | 3         | 1.04%   |
| 5.15.0-73-generic          | 2         | 0.69%   |
| 5.15.0-72-generic          | 2         | 0.69%   |
| 5.15.0-70-generic          | 2         | 0.69%   |
| 5.15.0-37-generic          | 2         | 0.69%   |
| 5.15.0-23-generic          | 2         | 0.69%   |
| 5.15.0-18-generic          | 2         | 0.69%   |
| 6.3.3-custom               | 1         | 0.35%   |
| 6.2.8-x64v3-xanmod1        | 1         | 0.35%   |
| 6.1.26-05272-g26c406245a2c | 1         | 0.35%   |
| 6.1.12-060112-generic      | 1         | 0.35%   |
| 6.1.0-custom               | 1         | 0.35%   |
| 6.0.8-060008-generic       | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 210       | 78.65%  |
| 5.19.0  | 43        | 16.1%   |
| 6.3.3   | 1         | 0.37%   |
| 6.2.8   | 1         | 0.37%   |
| 6.1.26  | 1         | 0.37%   |
| 6.1.12  | 1         | 0.37%   |
| 6.1.0   | 1         | 0.37%   |
| 6.0.8   | 1         | 0.37%   |
| 6.0.14  | 1         | 0.37%   |
| 6.0.12  | 1         | 0.37%   |
| 6.0.10  | 1         | 0.37%   |
| 5.4.0   | 1         | 0.37%   |
| 5.19.8  | 1         | 0.37%   |
| 5.19.11 | 1         | 0.37%   |
| 5.18.0  | 1         | 0.37%   |
| 5.14.0  | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 210       | 78.65%  |
| 5.19    | 45        | 16.85%  |
| 6.0     | 4         | 1.5%    |
| 6.1     | 3         | 1.12%   |
| 6.3     | 1         | 0.37%   |
| 6.2     | 1         | 0.37%   |
| 5.4     | 1         | 0.37%   |
| 5.18    | 1         | 0.37%   |
| 5.14    | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 257       | 98.85%  |
| aarch64 | 3         | 1.15%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 250       | 95.79%  |
| LXDE       | 6         | 2.3%    |
| X-Cinnamon | 2         | 0.77%   |
| GNOME      | 2         | 0.77%   |
| XFCE       | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 251       | 95.8%   |
| Tty         | 8         | 3.05%   |
| Wayland     | 2         | 0.76%   |
| Unspecified | 1         | 0.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 225       | 85.88%  |
| LightDM | 15        | 5.73%   |
| Unknown | 14        | 5.34%   |
| GDM3    | 5         | 1.91%   |
| XDM     | 1         | 0.38%   |
| SLiM    | 1         | 0.38%   |
| LXDM    | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 80        | 30.65%  |
| fr_FR  | 25        | 9.58%   |
| de_DE  | 19        | 7.28%   |
| it_IT  | 18        | 6.9%    |
| C      | 14        | 5.36%   |
| en_GB  | 12        | 4.6%    |
| pt_BR  | 10        | 3.83%   |
| pl_PL  | 8         | 3.07%   |
| en_AG  | 8         | 3.07%   |
| ru_RU  | 7         | 2.68%   |
| es_ES  | 7         | 2.68%   |
| en_AU  | 6         | 2.3%    |
| es_MX  | 5         | 1.92%   |
| es_AR  | 5         | 1.92%   |
| nl_BE  | 4         | 1.53%   |
| es_CR  | 4         | 1.53%   |
| tr_TR  | 3         | 1.15%   |
| es_CO  | 3         | 1.15%   |
| en_CA  | 2         | 0.77%   |
| el_GR  | 2         | 0.77%   |
| sv_SE  | 1         | 0.38%   |
| sk_SK  | 1         | 0.38%   |
| ru_UA  | 1         | 0.38%   |
| nl_NL  | 1         | 0.38%   |
| lzh_TW | 1         | 0.38%   |
| ja_JP  | 1         | 0.38%   |
| hu_HU  | 1         | 0.38%   |
| fr_CA  | 1         | 0.38%   |
| fi_FI  | 1         | 0.38%   |
| es_PE  | 1         | 0.38%   |
| es_EC  | 1         | 0.38%   |
| es_CL  | 1         | 0.38%   |
| en_ZA  | 1         | 0.38%   |
| en_PH  | 1         | 0.38%   |
| en_DE  | 1         | 0.38%   |
| de_CH  | 1         | 0.38%   |
| cv_RU  | 1         | 0.38%   |
| cs_CZ  | 1         | 0.38%   |
| aa_DJ  | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 165       | 63.22%  |
| EFI  | 96        | 36.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 234       | 88.64%  |
| Overlay | 16        | 6.06%   |
| Tmpfs   | 7         | 2.65%   |
| Btrfs   | 4         | 1.52%   |
| XXX4    | 1         | 0.38%   |
| Xfs     | 1         | 0.38%   |
| Ext2    | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 132       | 50.19%  |
| MBR     | 80        | 30.42%  |
| Unknown | 51        | 19.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 228       | 87.02%  |
| Yes       | 34        | 12.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 69.85%  |
| Yes       | 79        | 30.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 42        | 16.15%  |
| Hewlett-Packard         | 30        | 11.54%  |
| Dell                    | 28        | 10.77%  |
| ASUSTek Computer        | 25        | 9.62%   |
| Acer                    | 19        | 7.31%   |
| MSI                     | 14        | 5.38%   |
| Apple                   | 9         | 3.46%   |
| Unknown                 | 9         | 3.46%   |
| Google                  | 7         | 2.69%   |
| ASRock                  | 6         | 2.31%   |
| Toshiba                 | 5         | 1.92%   |
| Intel                   | 5         | 1.92%   |
| Gigabyte Technology     | 5         | 1.92%   |
| Fujitsu                 | 5         | 1.92%   |
| Sony                    | 4         | 1.54%   |
| Positivo                | 4         | 1.54%   |
| AMI                     | 4         | 1.54%   |
| Pegatron                | 3         | 1.15%   |
| Mediacom                | 3         | 1.15%   |
| Samsung Electronics     | 2         | 0.77%   |
| OEM                     | 2         | 0.77%   |
| HUAWEI                  | 2         | 0.77%   |
| GPU Company             | 2         | 0.77%   |
| Gateway                 | 2         | 0.77%   |
| ZOTAC                   | 1         | 0.38%   |
| YANYU                   | 1         | 0.38%   |
| Thomson                 | 1         | 0.38%   |
| SGIN                    | 1         | 0.38%   |
| Rockchip                | 1         | 0.38%   |
| Raspberry Pi Foundation | 1         | 0.38%   |
| Pretech                 | 1         | 0.38%   |
| Prestigio               | 1         | 0.38%   |
| Packard Bell            | 1         | 0.38%   |
| NEC Computers           | 1         | 0.38%   |
| libre-computer          | 1         | 0.38%   |
| Kiano                   | 1         | 0.38%   |
| IFSA                    | 1         | 0.38%   |
| Hampoo                  | 1         | 0.38%   |
| Getac                   | 1         | 0.38%   |
| Fujitsu Siemens         | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 10        | 3.85%   |
| Apple MacBookPro8,1                        | 3         | 1.15%   |
| MSI MS-7C37                                | 2         | 0.77%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 0.77%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 0.77%   |
| Lenovo G50-30 80G0                         | 2         | 0.77%   |
| HP Pavilion g6                             | 2         | 0.77%   |
| HP Pavilion 15                             | 2         | 0.77%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 0.77%   |
| Dell Dimension 9100                        | 2         | 0.77%   |
| Apple MacBook4,1                           | 2         | 0.77%   |
| ZOTAC NM10                                 | 1         | 0.38%   |
| YANYU ITX-S192                             | 1         | 0.38%   |
| Toshiba Satellite Radius P55W-B            | 1         | 0.38%   |
| Toshiba Satellite Pro S500                 | 1         | 0.38%   |
| Toshiba Satellite P70-A                    | 1         | 0.38%   |
| Toshiba Satellite L40                      | 1         | 0.38%   |
| Toshiba Satellite C660                     | 1         | 0.38%   |
| Thomson N14C4WH64                          | 1         | 0.38%   |
| Sony VPCEH2E1R                             | 1         | 0.38%   |
| Sony VPCEB15FM                             | 1         | 0.38%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.38%   |
| Sony SVE14A2V1EW                           | 1         | 0.38%   |
| SGIN laptop                                | 1         | 0.38%   |
| Samsung N150/N210/N220                     | 1         | 0.38%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.38%   |
| Rockchip RK3318 BOX                        | 1         | 0.38%   |
| RPi Raspberry Pi                           | 1         | 0.38%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.38%   |
| Prestigio PSB141C01BFH                     | 1         | 0.38%   |
| Positivo Q232A                             | 1         | 0.38%   |
| Positivo POS-AG31AP                        | 1         | 0.38%   |
| Positivo P5VD2-MX                          | 1         | 0.38%   |
| Positivo i500pro                           | 1         | 0.38%   |
| Pegatron NC689AA-ABA s3700y                | 1         | 0.38%   |
| Pegatron h8-1350ef                         | 1         | 0.38%   |
| Pegatron AY748AA-ABA p6320y                | 1         | 0.38%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.38%   |
| OEM M882CWP                                | 1         | 0.38%   |
| NEC Computers ECS-945G                     | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 14        | 5.38%   |
| Lenovo ThinkPad        | 13        | 5%      |
| Acer Aspire            | 12        | 4.62%   |
| Dell Latitude          | 10        | 3.85%   |
| Unknown                | 10        | 3.85%   |
| HP Pavilion            | 7         | 2.69%   |
| Toshiba Satellite      | 5         | 1.92%   |
| Fujitsu LIFEBOOK       | 4         | 1.54%   |
| HP ProBook             | 3         | 1.15%   |
| HP Laptop              | 3         | 1.15%   |
| HP Compaq              | 3         | 1.15%   |
| Dell XPS               | 3         | 1.15%   |
| Dell Vostro            | 3         | 1.15%   |
| Dell Precision         | 3         | 1.15%   |
| Dell OptiPlex          | 3         | 1.15%   |
| Apple MacBookPro8      | 3         | 1.15%   |
| MSI MS-7C37            | 2         | 0.77%   |
| Mediacom WinPad        | 2         | 0.77%   |
| Lenovo ThinkCentre     | 2         | 0.77%   |
| Lenovo G50-30          | 2         | 0.77%   |
| Dell Studio            | 2         | 0.77%   |
| Dell Dimension         | 2         | 0.77%   |
| ASUS PRIME             | 2         | 0.77%   |
| Apple MacBook4         | 2         | 0.77%   |
| ZOTAC NM10             | 1         | 0.38%   |
| YANYU ITX-S192         | 1         | 0.38%   |
| Thomson N14C4WH64      | 1         | 0.38%   |
| Sony VPCEH2E1R         | 1         | 0.38%   |
| Sony VPCEB15FM         | 1         | 0.38%   |
| Sony VGN-SZ71WN        | 1         | 0.38%   |
| Sony SVE14A2V1EW       | 1         | 0.38%   |
| SGIN laptop            | 1         | 0.38%   |
| Samsung N150           | 1         | 0.38%   |
| Samsung 300V3A         | 1         | 0.38%   |
| Rockchip RK3318        | 1         | 0.38%   |
| RPi Raspberry          | 1         | 0.38%   |
| Pretech EVE            | 1         | 0.38%   |
| Prestigio PSB141C01BFH | 1         | 0.38%   |
| Positivo Q232A         | 1         | 0.38%   |
| Positivo POS-AG31AP    | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 24        | 9.23%   |
| 2013    | 22        | 8.46%   |
| 2021    | 20        | 7.69%   |
| 2015    | 19        | 7.31%   |
| 2010    | 19        | 7.31%   |
| 2012    | 18        | 6.92%   |
| 2019    | 17        | 6.54%   |
| 2008    | 17        | 6.54%   |
| 2014    | 16        | 6.15%   |
| 2020    | 14        | 5.38%   |
| 2016    | 14        | 5.38%   |
| 2022    | 12        | 4.62%   |
| 2009    | 12        | 4.62%   |
| 2017    | 11        | 4.23%   |
| 2018    | 10        | 3.85%   |
| 2007    | 9         | 3.46%   |
| 2006    | 2         | 0.77%   |
| Unknown | 2         | 0.77%   |
| 2023    | 1         | 0.38%   |
| 2001    | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 166       | 63.85%  |
| Desktop        | 76        | 29.23%  |
| Convertible    | 6         | 2.31%   |
| Mini pc        | 4         | 1.54%   |
| System on chip | 3         | 1.15%   |
| Tablet         | 3         | 1.15%   |
| All in one     | 2         | 0.77%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 251       | 95.44%  |
| Enabled  | 12        | 4.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 252       | 96.92%  |
| Yes  | 8         | 3.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 82        | 31.3%   |
| 4.01-8.0    | 65        | 24.81%  |
| 1.01-2.0    | 32        | 12.21%  |
| 8.01-16.0   | 30        | 11.45%  |
| 16.01-24.0  | 26        | 9.92%   |
| 32.01-64.0  | 10        | 3.82%   |
| 2.01-3.0    | 10        | 3.82%   |
| 0.51-1.0    | 3         | 1.15%   |
| 24.01-32.0  | 2         | 0.76%   |
| 64.01-256.0 | 2         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 132       | 47.83%  |
| 0.51-1.0  | 61        | 22.1%   |
| 2.01-3.0  | 55        | 19.93%  |
| 4.01-8.0  | 15        | 5.43%   |
| 3.01-4.0  | 10        | 3.62%   |
| 0.01-0.5  | 2         | 0.72%   |
| 8.01-16.0 | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 184       | 69.96%  |
| 2      | 58        | 22.05%  |
| 3      | 10        | 3.8%    |
| 0      | 4         | 1.52%   |
| 5      | 2         | 0.76%   |
| 4      | 2         | 0.76%   |
| 12     | 1         | 0.38%   |
| 7      | 1         | 0.38%   |
| 6      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 157       | 60.15%  |
| Yes       | 104       | 39.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 208       | 79.69%  |
| No        | 53        | 20.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 195       | 75%     |
| No        | 65        | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 52.45%  |
| No        | 126       | 47.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 48        | 18.46%  |
| Germany      | 30        | 11.54%  |
| France       | 26        | 10%     |
| Italy        | 20        | 7.69%   |
| Poland       | 12        | 4.62%   |
| Brazil       | 11        | 4.23%   |
| Russia       | 10        | 3.85%   |
| Spain        | 9         | 3.46%   |
| UK           | 8         | 3.08%   |
| Belgium      | 6         | 2.31%   |
| Costa Rica   | 5         | 1.92%   |
| Australia    | 5         | 1.92%   |
| Argentina    | 5         | 1.92%   |
| Ukraine      | 4         | 1.54%   |
| Turkey       | 4         | 1.54%   |
| Mexico       | 4         | 1.54%   |
| Indonesia    | 4         | 1.54%   |
| Canada       | 4         | 1.54%   |
| Sweden       | 3         | 1.15%   |
| Colombia     | 3         | 1.15%   |
| Vietnam      | 2         | 0.77%   |
| UAE          | 2         | 0.77%   |
| Portugal     | 2         | 0.77%   |
| Netherlands  | 2         | 0.77%   |
| Latvia       | 2         | 0.77%   |
| Hungary      | 2         | 0.77%   |
| Greece       | 2         | 0.77%   |
| Finland      | 2         | 0.77%   |
| Venezuela    | 1         | 0.38%   |
| Thailand     | 1         | 0.38%   |
| Taiwan       | 1         | 0.38%   |
| Switzerland  | 1         | 0.38%   |
| South Africa | 1         | 0.38%   |
| Slovakia     | 1         | 0.38%   |
| Saudi Arabia | 1         | 0.38%   |
| Romania      | 1         | 0.38%   |
| Philippines  | 1         | 0.38%   |
| Peru         | 1         | 0.38%   |
| Pakistan     | 1         | 0.38%   |
| Kenya        | 1         | 0.38%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 8         | 2.95%   |
| Heredia          | 4         | 1.48%   |
| Moscow           | 3         | 1.11%   |
| Melbourne        | 3         | 1.11%   |
| Kyiv             | 3         | 1.11%   |
| Ghent            | 3         | 1.11%   |
| Bruhl            | 3         | 1.11%   |
| Warsaw           | 2         | 0.74%   |
| Sarospatak       | 2         | 0.74%   |
| Sao Paulo        | 2         | 0.74%   |
| Porto Alegre     | 2         | 0.74%   |
| Novo Gama        | 2         | 0.74%   |
| Monheim am Rhein | 2         | 0.74%   |
| Milan            | 2         | 0.74%   |
| Madrid           | 2         | 0.74%   |
| Largo            | 2         | 0.74%   |
| Lansing          | 2         | 0.74%   |
| Jakarta          | 2         | 0.74%   |
| Eugene           | 2         | 0.74%   |
| Dubai            | 2         | 0.74%   |
| Columbus         | 2         | 0.74%   |
| Chicago          | 2         | 0.74%   |
| Bogotá          | 2         | 0.74%   |
| Zizur Mayor      | 1         | 0.37%   |
| Zawiercie        | 1         | 0.37%   |
| Zaragoza         | 1         | 0.37%   |
| Zagreb           | 1         | 0.37%   |
| Yoshkar-Ola      | 1         | 0.37%   |
| Yorkville        | 1         | 0.37%   |
| Yerevan          | 1         | 0.37%   |
| Yekaterinburg    | 1         | 0.37%   |
| Wolfhagen        | 1         | 0.37%   |
| Wetteren         | 1         | 0.37%   |
| West Stockbridge | 1         | 0.37%   |
| Waterlooville    | 1         | 0.37%   |
| Washington       | 1         | 0.37%   |
| Warendorf        | 1         | 0.37%   |
| Vrbov            | 1         | 0.37%   |
| Volzhskiy        | 1         | 0.37%   |
| Versailles       | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 47        | 60     | 14.37%  |
| WDC                       | 43        | 58     | 13.15%  |
| Unknown                   | 36        | 51     | 11.01%  |
| Samsung Electronics       | 32        | 46     | 9.79%   |
| Hitachi                   | 19        | 25     | 5.81%   |
| Toshiba                   | 17        | 18     | 5.2%    |
| SanDisk                   | 15        | 15     | 4.59%   |
| Kingston                  | 15        | 16     | 4.59%   |
| Crucial                   | 9         | 9      | 2.75%   |
| HGST                      | 7         | 7      | 2.14%   |
| A-DATA Technology         | 6         | 6      | 1.83%   |
| Micron Technology         | 5         | 6      | 1.53%   |
| Intel                     | 5         | 6      | 1.53%   |
| GOODRAM                   | 4         | 4      | 1.22%   |
| Transcend                 | 3         | 5      | 0.92%   |
| SPCC                      | 3         | 4      | 0.92%   |
| SK hynix                  | 3         | 3      | 0.92%   |
| China                     | 3         | 3      | 0.92%   |
| Apacer                    | 3         | 3      | 0.92%   |
| Unknown                   | 3         | 3      | 0.92%   |
| UMIS                      | 2         | 2      | 0.61%   |
| Silicon Motion            | 2         | 2      | 0.61%   |
| PNY                       | 2         | 2      | 0.61%   |
| Patriot                   | 2         | 2      | 0.61%   |
| Micron/Crucial Technology | 2         | 3      | 0.61%   |
| Maxtor                    | 2         | 2      | 0.61%   |
| Fujitsu                   | 2         | 2      | 0.61%   |
| WDC WDS2                  | 1         | 1      | 0.31%   |
| WD MediaMax               | 1         | 1      | 0.31%   |
| W800S                     | 1         | 1      | 0.31%   |
| TO Exter                  | 1         | 1      | 0.31%   |
| Teclast                   | 1         | 1      | 0.31%   |
| Team                      | 1         | 1      | 0.31%   |
| T-FORCE                   | 1         | 1      | 0.31%   |
| RSH-319                   | 1         | 1      | 0.31%   |
| Rogueware                 | 1         | 1      | 0.31%   |
| Plextor                   | 1         | 1      | 0.31%   |
| Phison                    | 1         | 1      | 0.31%   |
| NGFF                      | 1         | 1      | 0.31%   |
| Netac                     | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 8         | 2.22%   |
| Unknown MMC Card  32GB             | 6         | 1.66%   |
| Seagate ST500DM002-1BD142 500GB    | 6         | 1.66%   |
| Kingston SA400S37240G 240GB SSD    | 6         | 1.66%   |
| Seagate ST9500325AS 500GB          | 5         | 1.39%   |
| SanDisk DF4032  32GB               | 5         | 1.39%   |
| Unknown NCard  32GB                | 4         | 1.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 1.11%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 0.83%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 0.83%   |
| Unknown                            | 3         | 0.83%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.55%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 2         | 0.55%   |
| WDC WD10SPZX-24Z10 1TB             | 2         | 0.55%   |
| Unknown SD/MMC/MS PRO 64GB         | 2         | 0.55%   |
| Unknown SC64G  64GB                | 2         | 0.55%   |
| Unknown SC256  256GB               | 2         | 0.55%   |
| Unknown MMC64G  64GB               | 2         | 0.55%   |
| Unknown MMC Card  16GB             | 2         | 0.55%   |
| Unknown DA4064  64GB               | 2         | 0.55%   |
| Unknown DA4032  32GB               | 2         | 0.55%   |
| Toshiba MQ01ABF050 500GB           | 2         | 0.55%   |
| Toshiba MQ01ABD075 752GB           | 2         | 0.55%   |
| Toshiba MQ01ABD050 500GB           | 2         | 0.55%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.55%   |
| SPCC Solid State Disk 120GB        | 2         | 0.55%   |
| Seagate ST3120213AS 120GB          | 2         | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 0.55%   |
| SanDisk SDSSDA480G 480GB           | 2         | 0.55%   |
| SanDisk DF4064  64GB               | 2         | 0.55%   |
| Samsung SSD 870 EVO 500GB          | 2         | 0.55%   |
| Samsung SSD 860 EVO 500GB          | 2         | 0.55%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.55%   |
| Samsung MZVLQ256HAJD-000H1 256GB   | 2         | 0.55%   |
| Samsung HD502HJ 500GB              | 2         | 0.55%   |
| HGST HTS545050A7E680 500GB         | 2         | 0.55%   |
| Crucial CT500P3SSD8 500GB          | 2         | 0.55%   |
| Crucial CT240BX500SSD1 240GB       | 2         | 0.55%   |
| Apacer 16GB SATA Flash Drive SSD   | 2         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 59     | 33.57%  |
| WDC                 | 35        | 44     | 25%     |
| Hitachi             | 19        | 25     | 13.57%  |
| Toshiba             | 15        | 16     | 10.71%  |
| Samsung Electronics | 7         | 13     | 5%      |
| HGST                | 7         | 7      | 5%      |
| Unknown             | 2         | 2      | 1.43%   |
| Maxtor              | 2         | 2      | 1.43%   |
| Fujitsu             | 2         | 2      | 1.43%   |
| WD MediaMax         | 1         | 1      | 0.71%   |
| RSH-319             | 1         | 1      | 0.71%   |
| External            | 1         | 1      | 0.71%   |
| Apricorn            | 1         | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 24     | 17.92%  |
| Kingston            | 13        | 14     | 12.26%  |
| SanDisk             | 7         | 7      | 6.6%    |
| WDC                 | 6         | 7      | 5.66%   |
| A-DATA Technology   | 6         | 6      | 5.66%   |
| Crucial             | 5         | 5      | 4.72%   |
| Intel               | 4         | 4      | 3.77%   |
| GOODRAM             | 4         | 4      | 3.77%   |
| Transcend           | 3         | 5      | 2.83%   |
| SPCC                | 3         | 4      | 2.83%   |
| Micron Technology   | 3         | 3      | 2.83%   |
| Apacer              | 3         | 3      | 2.83%   |
| Toshiba             | 2         | 2      | 1.89%   |
| PNY                 | 2         | 2      | 1.89%   |
| Patriot             | 2         | 2      | 1.89%   |
| WDC WDS2            | 1         | 1      | 0.94%   |
| W800S               | 1         | 1      | 0.94%   |
| TO Exter            | 1         | 1      | 0.94%   |
| Teclast             | 1         | 1      | 0.94%   |
| Team                | 1         | 1      | 0.94%   |
| Rogueware           | 1         | 1      | 0.94%   |
| Plextor             | 1         | 1      | 0.94%   |
| NGFF                | 1         | 1      | 0.94%   |
| Netac               | 1         | 1      | 0.94%   |
| LITEONIT            | 1         | 1      | 0.94%   |
| LITEON              | 1         | 1      | 0.94%   |
| Lexar               | 1         | 1      | 0.94%   |
| Leqixiang           | 1         | 1      | 0.94%   |
| Lenovo              | 1         | 1      | 0.94%   |
| Kston               | 1         | 3      | 0.94%   |
| KINGPOWER           | 1         | 1      | 0.94%   |
| HUSKY               | 1         | 1      | 0.94%   |
| Hewlett-Packard     | 1         | 1      | 0.94%   |
| Gigabyte Technology | 1         | 1      | 0.94%   |
| Emtec               | 1         | 1      | 0.94%   |
| China               | 1         | 1      | 0.94%   |
| BR                  | 1         | 1      | 0.94%   |
| BAITITON            | 1         | 1      | 0.94%   |
| 2.5"                | 1         | 2      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 121       | 174    | 39.54%  |
| SSD     | 100       | 119    | 32.68%  |
| MMC     | 45        | 61     | 14.71%  |
| NVMe    | 35        | 42     | 11.44%  |
| Unknown | 5         | 8      | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 198       | 288    | 68.75%  |
| MMC  | 45        | 61     | 15.63%  |
| NVMe | 35        | 42     | 12.15%  |
| SAS  | 10        | 13     | 3.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 161       | 205    | 71.24%  |
| 0.51-1.0   | 45        | 59     | 19.91%  |
| 1.01-2.0   | 12        | 17     | 5.31%   |
| 4.01-10.0  | 4         | 7      | 1.77%   |
| 2.01-3.0   | 3         | 4      | 1.33%   |
| 3.01-4.0   | 1         | 1      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 85        | 32.2%   |
| 251-500        | 60        | 22.73%  |
| 51-100         | 30        | 11.36%  |
| 21-50          | 23        | 8.71%   |
| 1-20           | 23        | 8.71%   |
| 501-1000       | 21        | 7.95%   |
| 1001-2000      | 10        | 3.79%   |
| More than 3000 | 6         | 2.27%   |
| 2001-3000      | 5         | 1.89%   |
| Unknown        | 1         | 0.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 136       | 50.37%  |
| 21-50          | 51        | 18.89%  |
| 51-100         | 33        | 12.22%  |
| 101-250        | 23        | 8.52%   |
| 251-500        | 8         | 2.96%   |
| 501-1000       | 8         | 2.96%   |
| 1001-2000      | 5         | 1.85%   |
| More than 3000 | 4         | 1.48%   |
| 2001-3000      | 1         | 0.37%   |
| Unknown        | 1         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB        | 4         | 5      | 8.89%   |
| Seagate ST9500325AS 500GB                 | 2         | 2      | 4.44%   |
| Seagate ST500LT012-1DG142 500GB           | 2         | 2      | 4.44%   |
| Apacer 16GB SATA Flash Drive SSD          | 2         | 2      | 4.44%   |
| WDC WD60EFRX-68L0BN1 6TB                  | 1         | 2      | 2.22%   |
| WDC WD5000LPCX-60VHAT1 500GB              | 1         | 1      | 2.22%   |
| WDC WD3200BPVT-22JJ5T0 320GB              | 1         | 1      | 2.22%   |
| WDC WD3200AACS-00M6B0 320GB               | 1         | 1      | 2.22%   |
| WDC WD2003FYYS-02W0B0 2TB                 | 1         | 1      | 2.22%   |
| WDC WD10SPZX-24Z10T0 1TB                  | 1         | 1      | 2.22%   |
| WDC WD10SPZX-08Z10 1TB                    | 1         | 1      | 2.22%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 2.22%   |
| WDC WD10EZEX-60WN4A1 1TB                  | 1         | 1      | 2.22%   |
| WDC WD10EACS-00D6B1 1TB                   | 1         | 1      | 2.22%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 2.22%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 1      | 2.22%   |
| Toshiba MK6465GSX 640GB                   | 1         | 1      | 2.22%   |
| Seagate ST9320325AS 320GB                 | 1         | 1      | 2.22%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 2.22%   |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 1      | 2.22%   |
| Seagate ST320LT020-9YG142 320GB           | 1         | 1      | 2.22%   |
| Seagate ST320LT012-9WS14C 320GB           | 1         | 1      | 2.22%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 2.22%   |
| Seagate ST1000DM003-1SB102 1TB            | 1         | 1      | 2.22%   |
| Samsung Electronics HM121HI 120GB         | 1         | 6      | 2.22%   |
| Samsung Electronics HD161HJ 160GB         | 1         | 1      | 2.22%   |
| Plextor PX-128M6M 128GB SSD               | 1         | 1      | 2.22%   |
| NGFF 2280 512GB SSD                       | 1         | 1      | 2.22%   |
| Micron Technology MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.22%   |
| Maxtor 6L200M0 208GB                      | 1         | 1      | 2.22%   |
| Intel SSDSC2KW512G8 512GB                 | 1         | 1      | 2.22%   |
| Intel SSDSA2M080G2LE 80GB                 | 1         | 1      | 2.22%   |
| Hitachi HTS722080K9SA00 80GB              | 1         | 1      | 2.22%   |
| Hitachi HTS545050A7E380 500GB             | 1         | 1      | 2.22%   |
| Hitachi HTS543216L9A300 160GB             | 1         | 1      | 2.22%   |
| Hitachi HTE545050B9A300 500GB             | 1         | 1      | 2.22%   |
| HGST HTS725032A7E630 320GB                | 1         | 1      | 2.22%   |
| Fujitsu MHY2120BH 120GB                   | 1         | 1      | 2.22%   |
| A-DATA Technology SP920SS 256GB SSD       | 1         | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 34.88%  |
| WDC                 | 8         | 11     | 18.6%   |
| Hitachi             | 4         | 4      | 9.3%    |
| Toshiba             | 3         | 3      | 6.98%   |
| Samsung Electronics | 2         | 7      | 4.65%   |
| Intel               | 2         | 2      | 4.65%   |
| Apacer              | 2         | 2      | 4.65%   |
| Plextor             | 1         | 1      | 2.33%   |
| NGFF                | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| Maxtor              | 1         | 1      | 2.33%   |
| HGST                | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 42.86%  |
| WDC                 | 8         | 11     | 22.86%  |
| Hitachi             | 4         | 4      | 11.43%  |
| Toshiba             | 3         | 3      | 8.57%   |
| Samsung Electronics | 2         | 7      | 5.71%   |
| Maxtor              | 1         | 1      | 2.86%   |
| HGST                | 1         | 1      | 2.86%   |
| Fujitsu             | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 44     | 80.95%  |
| SSD  | 8         | 8      | 19.05%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB       | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 980 1TB | 1         | 1      | 33.33%  |
| HGST HTS725025A7 250GB          | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| HGST                | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 140       | 213    | 50%     |
| Works    | 95        | 136    | 33.93%  |
| Malfunc  | 42        | 52     | 15%     |
| Failed   | 3         | 3      | 1.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 169       | 63.53%  |
| AMD                              | 43        | 16.17%  |
| Samsung Electronics              | 8         | 3.01%   |
| Nvidia                           | 7         | 2.63%   |
| SanDisk                          | 6         | 2.26%   |
| Micron/Crucial Technology        | 6         | 2.26%   |
| Micron Technology                | 3         | 1.13%   |
| JMicron Technology               | 3         | 1.13%   |
| ASMedia Technology               | 3         | 1.13%   |
| VIA Technologies                 | 2         | 0.75%   |
| Union Memory (Shenzhen)          | 2         | 0.75%   |
| SK hynix                         | 2         | 0.75%   |
| Silicon Motion                   | 2         | 0.75%   |
| Marvell Technology Group         | 2         | 0.75%   |
| Kingston Technology Company      | 2         | 0.75%   |
| Silicon Integrated Systems [SiS] | 1         | 0.38%   |
| Silicon Image                    | 1         | 0.38%   |
| Seagate Technology               | 1         | 0.38%   |
| Phison Electronics               | 1         | 0.38%   |
| LSI Logic / Symbios Logic        | 1         | 0.38%   |
| KIOXIA                           | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 26        | 8.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 5.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 12        | 3.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 11        | 3.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 11        | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 3.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 3.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 2.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 2.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 2.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 2.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 2.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 7         | 2.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 1.89%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 1.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 1.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 1.58%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 4         | 1.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.26%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.26%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.26%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 0.95%   |
| Micron NVMe Storage Controller                                                   | 3         | 0.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.95%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 3         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 0.95%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 3         | 0.95%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 0.95%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2         | 0.63%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.63%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 0.63%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.63%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.63%   |
| Nvidia MCP61 IDE                                                                 | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 185       | 65.84%  |
| IDE  | 49        | 17.44%  |
| NVMe | 34        | 12.1%   |
| RAID | 12        | 4.27%   |
| SAS  | 1         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 206       | 79.23%  |
| AMD    | 51        | 19.62%  |
| ARM    | 3         | 1.15%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz       | 6         | 2.31%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 6         | 2.31%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz       | 6         | 2.31%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 5         | 1.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 4         | 1.54%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 3         | 1.15%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 3         | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 1.15%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 3         | 1.15%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 3         | 1.15%   |
| Intel Celeron CPU N2830 @ 2.16GHz       | 3         | 1.15%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 3         | 1.15%   |
| Intel Atom CPU D525 @ 1.80GHz           | 3         | 1.15%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 1.15%   |
| ARM Processor                           | 3         | 1.15%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz  | 2         | 0.77%   |
| Intel Pentium D CPU 2.80GHz             | 2         | 0.77%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.77%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 2         | 0.77%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 2         | 0.77%   |
| Intel Core i5-9300HF CPU @ 2.40GHz      | 2         | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 0.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 0.77%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.77%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 0.77%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 2         | 0.77%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 2         | 0.77%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 0.77%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz    | 2         | 0.77%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz    | 2         | 0.77%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 0.77%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 2         | 0.77%   |
| Intel Celeron CPU N2940 @ 1.83GHz       | 2         | 0.77%   |
| Intel Celeron CPU B815 @ 1.60GHz        | 2         | 0.77%   |
| Intel Atom CPU N450 @ 1.66GHz           | 2         | 0.77%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 0.77%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 0.77%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 2         | 0.77%   |
| AMD E1-2100 APU with Radeon HD Graphics | 2         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 45        | 17.31%  |
| Intel Celeron           | 43        | 16.54%  |
| Intel Atom              | 24        | 9.23%   |
| Intel Core i7           | 23        | 8.85%   |
| Intel Core 2 Duo        | 22        | 8.46%   |
| Intel Core i3           | 18        | 6.92%   |
| Intel Pentium           | 9         | 3.46%   |
| AMD Ryzen 7             | 8         | 3.08%   |
| Other                   | 7         | 2.69%   |
| AMD Ryzen 5             | 6         | 2.31%   |
| Intel Pentium Dual      | 5         | 1.92%   |
| AMD A6                  | 4         | 1.54%   |
| Intel Xeon              | 3         | 1.15%   |
| AMD FX                  | 3         | 1.15%   |
| AMD E1                  | 3         | 1.15%   |
| AMD Athlon 64 X2        | 3         | 1.15%   |
| AMD A8                  | 3         | 1.15%   |
| Intel Pentium Dual-Core | 2         | 0.77%   |
| Intel Pentium D         | 2         | 0.77%   |
| Intel Core 2 Quad       | 2         | 0.77%   |
| Intel Core 2            | 2         | 0.77%   |
| AMD Phenom II X4        | 2         | 0.77%   |
| AMD E2                  | 2         | 0.77%   |
| AMD E                   | 2         | 0.77%   |
| AMD Athlon              | 2         | 0.77%   |
| AMD A10                 | 2         | 0.77%   |
| Intel Core m3           | 1         | 0.38%   |
| Intel Core i9           | 1         | 0.38%   |
| Intel Celeron Dual-Core | 1         | 0.38%   |
| AMD Ryzen 9             | 1         | 0.38%   |
| AMD Ryzen 7 PRO         | 1         | 0.38%   |
| AMD Ryzen 5 PRO         | 1         | 0.38%   |
| AMD Phenom II X6        | 1         | 0.38%   |
| AMD GX                  | 1         | 0.38%   |
| AMD G                   | 1         | 0.38%   |
| AMD C-60                | 1         | 0.38%   |
| AMD Athlon II X3        | 1         | 0.38%   |
| AMD Athlon II X2        | 1         | 0.38%   |
| AMD A4                  | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 150       | 57.69%  |
| 4       | 77        | 29.62%  |
| 8       | 10        | 3.85%   |
| 6       | 10        | 3.85%   |
| 1       | 7         | 2.69%   |
| 3       | 3         | 1.15%   |
| Unknown | 2         | 0.77%   |
| 10      | 1         | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 258       | 99.23%  |
| Unknown | 2         | 0.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 143       | 55%     |
| 2       | 115       | 44.23%  |
| Unknown | 2         | 0.77%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 259       | 99.62%  |
| 64-bit         | 1         | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 105       | 39.77%  |
| 0x306a9    | 12        | 4.55%   |
| 0x206a7    | 12        | 4.55%   |
| 0x406c4    | 10        | 3.79%   |
| 0x1067a    | 10        | 3.79%   |
| 0x406c3    | 7         | 2.65%   |
| 0x706a8    | 6         | 2.27%   |
| 0x6fd      | 5         | 1.89%   |
| 0x806ec    | 4         | 1.52%   |
| 0x706e5    | 4         | 1.52%   |
| 0x40651    | 4         | 1.52%   |
| 0x306c3    | 4         | 1.52%   |
| 0x30678    | 4         | 1.52%   |
| 0x20655    | 4         | 1.52%   |
| 0x106ca    | 4         | 1.52%   |
| 0x0a50000c | 4         | 1.52%   |
| 0x906ea    | 3         | 1.14%   |
| 0x906c0    | 3         | 1.14%   |
| 0x806ea    | 3         | 1.14%   |
| 0x806c1    | 3         | 1.14%   |
| 0x706a1    | 3         | 1.14%   |
| 0x0700010f | 3         | 1.14%   |
| 0x06006705 | 3         | 1.14%   |
| 0x05000119 | 3         | 1.14%   |
| 0x806e9    | 2         | 0.76%   |
| 0x6fb      | 2         | 0.76%   |
| 0x506e3    | 2         | 0.76%   |
| 0x506c9    | 2         | 0.76%   |
| 0x406e3    | 2         | 0.76%   |
| 0x30679    | 2         | 0.76%   |
| 0x06003106 | 2         | 0.76%   |
| 0x06001119 | 2         | 0.76%   |
| 0x010000db | 2         | 0.76%   |
| 0xa0653    | 1         | 0.38%   |
| 0x906ed    | 1         | 0.38%   |
| 0x806eb    | 1         | 0.38%   |
| 0x6fa      | 1         | 0.38%   |
| 0x6f6      | 1         | 0.38%   |
| 0x306e4    | 1         | 0.38%   |
| 0x306d4    | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 39        | 15%     |
| SandyBridge   | 20        | 7.69%   |
| Penryn        | 20        | 7.69%   |
| IvyBridge     | 19        | 7.31%   |
| Haswell       | 17        | 6.54%   |
| KabyLake      | 16        | 6.15%   |
| Core          | 15        | 5.77%   |
| Goldmont plus | 13        | 5%      |
| Westmere      | 10        | 3.85%   |
| Zen 3         | 8         | 3.08%   |
| Bonnell       | 7         | 2.69%   |
| Skylake       | 6         | 2.31%   |
| Piledriver    | 6         | 2.31%   |
| Unknown       | 6         | 2.31%   |
| K10           | 5         | 1.92%   |
| K8 Hammer     | 4         | 1.54%   |
| Jaguar        | 4         | 1.54%   |
| IceLake       | 4         | 1.54%   |
| Goldmont      | 4         | 1.54%   |
| Excavator     | 4         | 1.54%   |
| Broadwell     | 4         | 1.54%   |
| Bobcat        | 4         | 1.54%   |
| Zen+          | 3         | 1.15%   |
| Zen           | 3         | 1.15%   |
| Tremont       | 3         | 1.15%   |
| TigerLake     | 3         | 1.15%   |
| Zen 2         | 2         | 0.77%   |
| Steamroller   | 2         | 0.77%   |
| NetBurst      | 2         | 0.77%   |
| Nehalem       | 2         | 0.77%   |
| CometLake     | 2         | 0.77%   |
| Puma          | 1         | 0.38%   |
| K10 Llano     | 1         | 0.38%   |
| Bulldozer     | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 170       | 60.71%  |
| AMD    | 62        | 22.14%  |
| Nvidia | 48        | 17.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 8.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 6.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 5.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 4.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 4.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 3.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 2.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 2.68%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 2.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 2.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.34%   |
| Intel HD Graphics 500                                                                    | 4         | 1.34%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.34%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.34%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.34%   |
| Nvidia GT218 [ION]                                                                       | 3         | 1.01%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.01%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.01%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.01%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 1.01%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.01%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.01%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.67%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 2         | 0.67%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 0.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.67%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.67%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.67%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 0.67%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 2         | 0.67%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 148       | 56.92%  |
| 1 x AMD            | 44        | 16.92%  |
| 1 x Nvidia         | 35        | 13.46%  |
| Intel + Nvidia     | 9         | 3.46%   |
| 2 x AMD            | 7         | 2.69%   |
| Intel + AMD        | 7         | 2.69%   |
| Other              | 5         | 1.92%   |
| AMD + Nvidia       | 3         | 1.15%   |
| Intel + 2 x Nvidia | 1         | 0.38%   |
| Intel + 2 x AMD    | 1         | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 232       | 89.23%  |
| Proprietary | 17        | 6.54%   |
| Unknown     | 11        | 4.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 202       | 77.1%   |
| 0.01-0.5   | 23        | 8.78%   |
| 1.01-2.0   | 12        | 4.58%   |
| 0.51-1.0   | 11        | 4.2%    |
| 7.01-8.0   | 5         | 1.91%   |
| 3.01-4.0   | 3         | 1.15%   |
| 2.01-3.0   | 3         | 1.15%   |
| 8.01-16.0  | 2         | 0.76%   |
| 5.01-6.0   | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 35        | 13.94%  |
| Samsung Electronics     | 29        | 11.55%  |
| LG Display              | 28        | 11.16%  |
| BOE                     | 26        | 10.36%  |
| Chimei Innolux          | 22        | 8.76%   |
| Hewlett-Packard         | 10        | 3.98%   |
| Goldstar                | 10        | 3.98%   |
| Dell                    | 9         | 3.59%   |
| Apple                   | 9         | 3.59%   |
| Lenovo                  | 5         | 1.99%   |
| CPT                     | 5         | 1.99%   |
| Acer                    | 5         | 1.99%   |
| Sharp                   | 4         | 1.59%   |
| Philips                 | 4         | 1.59%   |
| Chi Mei Optoelectronics | 4         | 1.59%   |
| Ancor Communications    | 4         | 1.59%   |
| Toshiba                 | 3         | 1.2%    |
| Eizo                    | 3         | 1.2%    |
| ViewSonic               | 2         | 0.8%    |
| Sony                    | 2         | 0.8%    |
| LG Philips              | 2         | 0.8%    |
| InfoVision              | 2         | 0.8%    |
| Iiyama                  | 2         | 0.8%    |
| HannStar                | 2         | 0.8%    |
| BenQ                    | 2         | 0.8%    |
| Westinghouse            | 1         | 0.4%    |
| Vizio                   | 1         | 0.4%    |
| VHT                     | 1         | 0.4%    |
| Unknown (ADA)           | 1         | 0.4%    |
| Unknown                 | 1         | 0.4%    |
| SNC                     | 1         | 0.4%    |
| Sampo                   | 1         | 0.4%    |
| Positivo                | 1         | 0.4%    |
| MSI                     | 1         | 0.4%    |
| LLL                     | 1         | 0.4%    |
| LG Electronics          | 1         | 0.4%    |
| JVC                     | 1         | 0.4%    |
| Jean                    | 1         | 0.4%    |
| JDI                     | 1         | 0.4%    |
| Insignia                | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 5         | 1.98%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 3         | 1.19%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 2         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 2         | 0.79%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch          | 2         | 0.79%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.79%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 2         | 0.79%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 2         | 0.79%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                 | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 2         | 0.79%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                 | 2         | 0.79%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                 | 2         | 0.79%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch        | 2         | 0.79%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 2         | 0.79%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 2         | 0.79%   |
| Westinghouse LCM-22w2 WDE2202 1680x1050 473x296mm 22.0-inch          | 1         | 0.4%    |
| Vizio VOJ320F1A VIZ0050 1920x1080 700x390mm 31.5-inch                | 1         | 0.4%    |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1         | 0.4%    |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch        | 1         | 0.4%    |
| VHT Monitor VHTDDDD 1024x768                                         | 1         | 0.4%    |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                          | 1         | 0.4%    |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch        | 1         | 0.4%    |
| Toshiba TV TSB0108 1920x540                                          | 1         | 0.4%    |
| Toshiba LCD Monitor LCD5860 1280x800 261x163mm 12.1-inch             | 1         | 0.4%    |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch             | 1         | 0.4%    |
| Sony TV SNY9C01 1360x768                                             | 1         | 0.4%    |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                   | 1         | 0.4%    |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 1         | 0.4%    |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch              | 1         | 0.4%    |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch              | 1         | 0.4%    |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch              | 1         | 0.4%    |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch             | 1         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 91        | 36.69%  |
| 1920x1080 (FHD)    | 68        | 27.42%  |
| 1280x800 (WXGA)    | 21        | 8.47%   |
| 1600x900 (HD+)     | 15        | 6.05%   |
| 1680x1050 (WSXGA+) | 9         | 3.63%   |
| 1280x1024 (SXGA)   | 9         | 3.63%   |
| 2560x1440 (QHD)    | 6         | 2.42%   |
| 1440x900 (WXGA+)   | 6         | 2.42%   |
| 3840x2160 (4K)     | 4         | 1.61%   |
| 1360x768           | 4         | 1.61%   |
| 3200x1800 (QHD+)   | 2         | 0.81%   |
| 2160x1440          | 2         | 0.81%   |
| 800x600            | 1         | 0.4%    |
| 3000x2000          | 1         | 0.4%    |
| 2560x1600          | 1         | 0.4%    |
| 2560x1080          | 1         | 0.4%    |
| 1920x540           | 1         | 0.4%    |
| 1920x1200 (WUXGA)  | 1         | 0.4%    |
| 1528x1222          | 1         | 0.4%    |
| 1280x768           | 1         | 0.4%    |
| 1280x720 (HD)      | 1         | 0.4%    |
| 1024x768 (XGA)     | 1         | 0.4%    |
| 1024x600           | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 58        | 23.2%   |
| 14      | 31        | 12.4%   |
| 13      | 29        | 11.6%   |
| 11      | 17        | 6.8%    |
| 17      | 12        | 4.8%    |
| 23      | 11        | 4.4%    |
| 18      | 10        | 4%      |
| 12      | 10        | 4%      |
| 27      | 9         | 3.6%    |
| 24      | 9         | 3.6%    |
| 19      | 9         | 3.6%    |
| 22      | 8         | 3.2%    |
| 21      | 8         | 3.2%    |
| Unknown | 8         | 3.2%    |
| 20      | 4         | 1.6%    |
| 10      | 3         | 1.2%    |
| 72      | 2         | 0.8%    |
| 84      | 1         | 0.4%    |
| 52      | 1         | 0.4%    |
| 49      | 1         | 0.4%    |
| 47      | 1         | 0.4%    |
| 44      | 1         | 0.4%    |
| 43      | 1         | 0.4%    |
| 34      | 1         | 0.4%    |
| 28      | 1         | 0.4%    |
| 16      | 1         | 0.4%    |
| 9       | 1         | 0.4%    |
| 8       | 1         | 0.4%    |
| 7       | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 103       | 41.2%   |
| 201-300     | 48        | 19.2%   |
| 401-500     | 35        | 14%     |
| 501-600     | 28        | 11.2%   |
| 351-400     | 14        | 5.6%    |
| Unknown     | 8         | 3.2%    |
| 1501-2000   | 3         | 1.2%    |
| 101-200     | 3         | 1.2%    |
| 1001-1500   | 3         | 1.2%    |
| 601-700     | 2         | 0.8%    |
| 901-1000    | 2         | 0.8%    |
| 701-800     | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 177       | 74.68%  |
| 16/10   | 36        | 15.19%  |
| 5/4     | 7         | 2.95%   |
| 3/2     | 6         | 2.53%   |
| Unknown | 6         | 2.53%   |
| 4/3     | 4         | 1.69%   |
| 21/9    | 1         | 0.42%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 57        | 22.89%  |
| 81-90          | 52        | 20.88%  |
| 201-250        | 30        | 12.05%  |
| 51-60          | 17        | 6.83%   |
| 151-200        | 16        | 6.43%   |
| 141-150        | 11        | 4.42%   |
| 61-70          | 10        | 4.02%   |
| 301-350        | 9         | 3.61%   |
| 71-80          | 8         | 3.21%   |
| 121-130        | 8         | 3.21%   |
| Unknown        | 8         | 3.21%   |
| More than 1000 | 5         | 2.01%   |
| 251-300        | 5         | 2.01%   |
| 41-50          | 4         | 1.61%   |
| 501-1000       | 4         | 1.61%   |
| 1-40           | 2         | 0.8%    |
| 131-140        | 2         | 0.8%    |
| 111-120        | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 90        | 36.73%  |
| 51-100        | 66        | 26.94%  |
| 121-160       | 55        | 22.45%  |
| 161-240       | 16        | 6.53%   |
| 1-50          | 8         | 3.27%   |
| Unknown       | 8         | 3.27%   |
| More than 240 | 2         | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 231       | 88.85%  |
| 2     | 19        | 7.31%   |
| 0     | 9         | 3.46%   |
| 3     | 1         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 130       | 34.57%  |
| Intel                             | 94        | 25%     |
| Qualcomm Atheros                  | 54        | 14.36%  |
| Broadcom                          | 22        | 5.85%   |
| Marvell Technology Group          | 9         | 2.39%   |
| TP-Link                           | 7         | 1.86%   |
| Ralink                            | 6         | 1.6%    |
| Samsung Electronics               | 5         | 1.33%   |
| Nvidia                            | 5         | 1.33%   |
| Broadcom Limited                  | 5         | 1.33%   |
| Qualcomm Atheros Communications   | 4         | 1.06%   |
| MediaTek                          | 4         | 1.06%   |
| NetGear                           | 3         | 0.8%    |
| ASIX Electronics                  | 3         | 0.8%    |
| Xiaomi                            | 2         | 0.53%   |
| VIA Technologies                  | 2         | 0.53%   |
| Ralink Technology                 | 2         | 0.53%   |
| Qualcomm                          | 2         | 0.53%   |
| ICS Advent                        | 2         | 0.53%   |
| Belkin Components                 | 2         | 0.53%   |
| ASUSTek Computer                  | 2         | 0.53%   |
| Trident Microsystems              | 1         | 0.27%   |
| Texas Instruments                 | 1         | 0.27%   |
| Sierra Wireless                   | 1         | 0.27%   |
| OPPO Electronics                  | 1         | 0.27%   |
| Motorola PCS                      | 1         | 0.27%   |
| Microsoft                         | 1         | 0.27%   |
| JMicron Technology                | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| Dresden Elektronik                | 1         | 0.27%   |
| Dell                              | 1         | 0.27%   |
| Accton Technology                 | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 17.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 4.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.71%   |
| Intel Wireless 7260                                               | 10        | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9         | 2.04%   |
| Intel Wireless 7265                                               | 9         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 5         | 1.13%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.13%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 0.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.9%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.68%   |
| NetGear A6210                                                     | 3         | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.68%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.68%   |
| Intel Wireless 3160                                               | 3         | 0.68%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.68%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.68%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.68%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.68%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.68%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.68%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 34.27%  |
| Qualcomm Atheros                | 46        | 21.6%   |
| Realtek Semiconductor           | 45        | 21.13%  |
| Broadcom                        | 14        | 6.57%   |
| TP-Link                         | 6         | 2.82%   |
| Ralink                          | 6         | 2.82%   |
| Qualcomm Atheros Communications | 4         | 1.88%   |
| MediaTek                        | 4         | 1.88%   |
| NetGear                         | 3         | 1.41%   |
| Broadcom Limited                | 3         | 1.41%   |
| Ralink Technology               | 2         | 0.94%   |
| Belkin Components               | 2         | 0.94%   |
| ASUSTek Computer                | 2         | 0.94%   |
| Sierra Wireless                 | 1         | 0.47%   |
| Microsoft                       | 1         | 0.47%   |
| Dell                            | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 10        | 4.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 4.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 4.21%   |
| Intel Wireless 7265                                            | 9         | 4.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 3.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 2.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.34%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5         | 2.34%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 1.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.87%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 1.4%    |
| NetGear A6210                                                  | 3         | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.4%    |
| Intel Wireless 3160                                            | 3         | 1.4%    |
| Intel Wi-Fi 6 AX200                                            | 3         | 1.4%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 1.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.4%    |
| Intel Centrino Wireless-N 2230                                 | 3         | 1.4%    |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.4%    |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.4%    |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.4%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.93%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.93%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.93%   |
| Intel Wireless 8265 / 8275                                     | 2         | 0.93%   |
| Intel Wireless 8260                                            | 2         | 0.93%   |
| Intel Wireless 3165                                            | 2         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 111       | 50.23%  |
| Intel                    | 44        | 19.91%  |
| Qualcomm Atheros         | 17        | 7.69%   |
| Broadcom                 | 13        | 5.88%   |
| Marvell Technology Group | 9         | 4.07%   |
| Nvidia                   | 5         | 2.26%   |
| Samsung Electronics      | 3         | 1.36%   |
| ASIX Electronics         | 3         | 1.36%   |
| Xiaomi                   | 2         | 0.9%    |
| VIA Technologies         | 2         | 0.9%    |
| Qualcomm                 | 2         | 0.9%    |
| ICS Advent               | 2         | 0.9%    |
| Broadcom Limited         | 2         | 0.9%    |
| Trident Microsystems     | 1         | 0.45%   |
| TP-Link                  | 1         | 0.45%   |
| OPPO Electronics         | 1         | 0.45%   |
| Motorola PCS             | 1         | 0.45%   |
| JMicron Technology       | 1         | 0.45%   |
| Accton Technology        | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 35.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 8.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 5.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 2.69%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.24%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.35%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 1.35%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.35%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.35%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.35%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.35%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.9%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.9%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.9%    |
| Nvidia MCP77 Ethernet                                             | 2         | 0.9%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.9%    |
| Intel NM10/ICH7 Family LAN Controller                             | 2         | 0.9%    |
| Intel I211 Gigabit Network Connection                             | 2         | 0.9%    |
| Intel Ethernet Connection I217-V                                  | 2         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.9%    |
| Trident Microsystems 4DWave DX                                    | 1         | 0.45%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.45%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.45%   |
| Qualcomm Redmi Note 9 Pro                                         | 1         | 0.45%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.45%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.45%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 208       | 50.98%  |
| WiFi     | 195       | 47.79%  |
| Modem    | 5         | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 149       | 58.2%   |
| Ethernet | 107       | 41.8%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 129       | 49.62%  |
| 1     | 101       | 38.85%  |
| 0     | 25        | 9.62%   |
| 3     | 4         | 1.54%   |
| 4     | 1         | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 196       | 74.81%  |
| Yes  | 66        | 25.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 35.97%  |
| Realtek Semiconductor           | 20        | 14.39%  |
| Qualcomm Atheros Communications | 14        | 10.07%  |
| Broadcom                        | 9         | 6.47%   |
| Apple                           | 8         | 5.76%   |
| Foxconn / Hon Hai               | 6         | 4.32%   |
| IMC Networks                    | 5         | 3.6%    |
| Cambridge Silicon Radio         | 5         | 3.6%    |
| Ralink                          | 4         | 2.88%   |
| Lite-On Technology              | 4         | 2.88%   |
| Dell                            | 3         | 2.16%   |
| Toshiba                         | 2         | 1.44%   |
| MediaTek                        | 2         | 1.44%   |
| Hewlett-Packard                 | 2         | 1.44%   |
| TP-Link                         | 1         | 0.72%   |
| Syntek                          | 1         | 0.72%   |
| Logitech                        | 1         | 0.72%   |
| ASUSTek Computer                | 1         | 0.72%   |
| Alps Electric                   | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 29        | 20.71%  |
| Realtek Bluetooth Radio                                                             | 12        | 8.57%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 4.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 3.57%   |
| Intel AX201 Bluetooth                                                               | 5         | 3.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 3.57%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 3.57%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 2.86%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 2.86%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.86%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.14%   |
| Intel AX200 Bluetooth                                                               | 3         | 2.14%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 2.14%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.43%   |
| MediaTek Wireless_Device                                                            | 2         | 1.43%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.43%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.43%   |
| Apple Bluetooth HCI                                                                 | 2         | 1.43%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.71%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.71%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.71%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 0.71%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.71%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.71%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 0.71%   |
| Lite-On Wireless_Device                                                             | 1         | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.71%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.71%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.71%   |
| Intel Bluetooth Device                                                              | 1         | 0.71%   |
| IMC Networks Bluetooth                                                              | 1         | 0.71%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.71%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.71%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.71%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.71%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.71%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 183       | 62.03%  |
| AMD                                          | 57        | 19.32%  |
| Nvidia                                       | 35        | 11.86%  |
| C-Media Electronics                          | 5         | 1.69%   |
| VIA Technologies                             | 3         | 1.02%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.34%   |
| Sony                                         | 1         | 0.34%   |
| Razer USA                                    | 1         | 0.34%   |
| MosArt Semiconductor                         | 1         | 0.34%   |
| Logitech                                     | 1         | 0.34%   |
| JMTek                                        | 1         | 0.34%   |
| GN Netcom                                    | 1         | 0.34%   |
| Focusrite-Novation                           | 1         | 0.34%   |
| Ensoniq                                      | 1         | 0.34%   |
| EGO SYStems                                  | 1         | 0.34%   |
| Creative Labs                                | 1         | 0.34%   |
| ASUSTek Computer                             | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 6.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 19        | 5.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 3.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 3.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 3.71%   |
| AMD FCH Azalia Controller                                                                         | 12        | 3.43%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 3.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 3.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 3.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 2.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.57%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.57%   |
| Nvidia High Definition Audio Controller                                                           | 8         | 2.29%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 2.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.71%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.43%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.14%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.14%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.14%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 4         | 1.14%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.86%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.86%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3         | 0.86%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.86%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.86%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 18.38%  |
| SK hynix            | 33        | 17.84%  |
| Unknown             | 29        | 15.68%  |
| Micron Technology   | 24        | 12.97%  |
| Kingston            | 10        | 5.41%   |
| Elpida              | 7         | 3.78%   |
| Unknown (ABCD)      | 6         | 3.24%   |
| Nanya Technology    | 6         | 3.24%   |
| Corsair             | 6         | 3.24%   |
| Unknown             | 6         | 3.24%   |
| G.Skill             | 5         | 2.7%    |
| Crucial             | 3         | 1.62%   |
| Smart               | 2         | 1.08%   |
| Ramaxel Technology  | 2         | 1.08%   |
| A-DATA Technology   | 2         | 1.08%   |
| Transcend           | 1         | 0.54%   |
| Toshiba             | 1         | 0.54%   |
| Patriot             | 1         | 0.54%   |
| Novatech            | 1         | 0.54%   |
| Kllisre             | 1         | 0.54%   |
| Kingmax             | 1         | 0.54%   |
| HMD                 | 1         | 0.54%   |
| GOODRAM             | 1         | 0.54%   |
| Apacer              | 1         | 0.54%   |
| AMD                 | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 6         | 2.99%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 2.49%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.99%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 1.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 3         | 1.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 1%      |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1%      |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 1%      |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 2         | 1%      |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1%      |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1%      |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 2         | 1%      |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 1%      |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 1%      |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 1%      |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s             | 2         | 1%      |
| Elpida RAM EBJ20UF8BDU0-GN-F 2GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 0.5%    |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM                                      | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.5%    |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.5%    |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s         | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 81        | 48.5%   |
| DDR4    | 46        | 27.54%  |
| DDR2    | 14        | 8.38%   |
| LPDDR4  | 12        | 7.19%   |
| SDRAM   | 6         | 3.59%   |
| Unknown | 4         | 2.4%    |
| LPDDR3  | 3         | 1.8%    |
| LPDDR5  | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 111       | 66.87%  |
| DIMM         | 39        | 23.49%  |
| Row Of Chips | 13        | 7.83%   |
| Unknown      | 3         | 1.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 59        | 32.24%  |
| 2048  | 52        | 28.42%  |
| 8192  | 50        | 27.32%  |
| 16384 | 11        | 6.01%   |
| 1024  | 8         | 4.37%   |
| 32768 | 2         | 1.09%   |
| 512   | 1         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 54        | 30.68%  |
| 3200    | 21        | 11.93%  |
| 1333    | 13        | 7.39%   |
| 2400    | 11        | 6.25%   |
| 2667    | 8         | 4.55%   |
| 1334    | 8         | 4.55%   |
| 667     | 8         | 4.55%   |
| 1066    | 7         | 3.98%   |
| Unknown | 6         | 3.41%   |
| 1866    | 5         | 2.84%   |
| 3266    | 4         | 2.27%   |
| 1067    | 4         | 2.27%   |
| 4267    | 3         | 1.7%    |
| 2133    | 3         | 1.7%    |
| 800     | 3         | 1.7%    |
| 3400    | 2         | 1.14%   |
| 2800    | 2         | 1.14%   |
| 2048    | 2         | 1.14%   |
| 1867    | 2         | 1.14%   |
| 975     | 2         | 1.14%   |
| 5500    | 1         | 0.57%   |
| 4199    | 1         | 0.57%   |
| 3933    | 1         | 0.57%   |
| 3733    | 1         | 0.57%   |
| 3666    | 1         | 0.57%   |
| 3066    | 1         | 0.57%   |
| 533     | 1         | 0.57%   |
| 333     | 1         | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 3         | 50%     |
| Samsung Electronics | 1         | 16.67%  |
| Hewlett-Packard     | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4200 series | 1         | 16.67%  |
| HP LaserJet P1102       | 1         | 16.67%  |
| Canon PIXMA MP250       | 1         | 16.67%  |
| Canon MF3110            | 1         | 16.67%  |
| Canon LiDE 300          | 1         | 16.67%  |
| Brother DCP-7055W       | 1         | 16.67%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 37        | 24.5%   |
| Realtek Semiconductor                  | 15        | 9.93%   |
| Microdia                               | 15        | 9.93%   |
| Sunplus Innovation Technology          | 8         | 5.3%    |
| Syntek                                 | 7         | 4.64%   |
| Apple                                  | 7         | 4.64%   |
| Bison Electronics                      | 6         | 3.97%   |
| Quanta                                 | 5         | 3.31%   |
| Logitech                               | 5         | 3.31%   |
| IMC Networks                           | 5         | 3.31%   |
| Alcor Micro                            | 5         | 3.31%   |
| Suyin                                  | 4         | 2.65%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.65%   |
| Lenovo                                 | 3         | 1.99%   |
| ALi                                    | 3         | 1.99%   |
| Acer                                   | 3         | 1.99%   |
| Silicon Motion                         | 2         | 1.32%   |
| Lite-On Technology                     | 2         | 1.32%   |
| icSpring                               | 2         | 1.32%   |
| Z-Star Microelectronics                | 1         | 0.66%   |
| Y Media                                | 1         | 0.66%   |
| WaveRider Communications               | 1         | 0.66%   |
| USB Camera CS                          | 1         | 0.66%   |
| SunplusIT                              | 1         | 0.66%   |
| Ricoh                                  | 1         | 0.66%   |
| Pixart Imaging                         | 1         | 0.66%   |
| Microsoft                              | 1         | 0.66%   |
| Generalplus Technology                 | 1         | 0.66%   |
| GEMBIRD                                | 1         | 0.66%   |
| Cubeternet                             | 1         | 0.66%   |
| BKX-Usb2.0 2MP Camera                  | 1         | 0.66%   |
| AVerMedia Technologies                 | 1         | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Chicony Integrated Camera         | 9         | 5.92%   |
| Alcor Micro USB 2.0 Camera        | 5         | 3.29%   |
| Microdia Integrated Webcam        | 4         | 2.63%   |
| Chicony HP Truevision HD camera   | 4         | 2.63%   |
| Chicony HD WebCam                 | 4         | 2.63%   |
| Sunplus HD WebCam                 | 3         | 1.97%   |
| Realtek Integrated_Webcam_HD      | 3         | 1.97%   |
| Microdia Integrated_Webcam_HD     | 3         | 1.97%   |
| Apple FaceTime HD Camera          | 3         | 1.97%   |
| Syntek Integrated Camera          | 2         | 1.32%   |
| Realtek USB Camera                | 2         | 1.32%   |
| Realtek Lenovo EasyCamera         | 2         | 1.32%   |
| Realtek Integrated Webcam HD      | 2         | 1.32%   |
| Microdia Lenovo EasyCamera        | 2         | 1.32%   |
| Microdia HP Webcam-50             | 2         | 1.32%   |
| Logitech Webcam C270              | 2         | 1.32%   |
| Lenovo Integrated Webcam          | 2         | 1.32%   |
| IMC Networks USB2.0 HD UVC WebCam | 2         | 1.32%   |
| icSpring camera                   | 2         | 1.32%   |
| Chicony VGA Webcam                | 2         | 1.32%   |
| Chicony HP Truevision HD          | 2         | 1.32%   |
| Chicony FJ Camera                 | 2         | 1.32%   |
| Chicony EasyCamera                | 2         | 1.32%   |
| Chicony 2.0M UVC Webcam / CNF7129 | 2         | 1.32%   |
| Bison Lenovo EasyCamera           | 2         | 1.32%   |
| Bison Integrated Camera           | 2         | 1.32%   |
| ALi WebCam                        | 2         | 1.32%   |
| Acer Lenovo EasyCamera            | 2         | 1.32%   |
| Z-Star Webcam                     | 1         | 0.66%   |
| Y Media USB Camera                | 1         | 0.66%   |
| WaveRider USB 2.0 Camera          | 1         | 0.66%   |
| USB Camera CS USB Camera CS       | 1         | 0.66%   |
| Syntek USB2.0 Camera              | 1         | 0.66%   |
| Syntek USB Camera Device          | 1         | 0.66%   |
| Syntek Sonix USB 2.0 Camera       | 1         | 0.66%   |
| Syntek Lenovo EasyCamera          | 1         | 0.66%   |
| Syntek HD WebCam                  | 1         | 0.66%   |
| Suyin VGA Webcam                  | 1         | 0.66%   |
| Suyin Intel Webcam                | 1         | 0.66%   |
| Suyin HP Webcam-101               | 1         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 22.73%  |
| Upek                       | 5         | 22.73%  |
| AuthenTec                  | 4         | 18.18%  |
| Synaptics                  | 2         | 9.09%   |
| STMicroelectronics         | 2         | 9.09%   |
| Shenzhen Goodix Technology | 2         | 9.09%   |
| LighTuning Technology      | 1         | 4.55%   |
| Elan Microelectronics      | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 22.73%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.55%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4.55%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 4.55%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.55%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.55%   |
| Synaptics WBDI                                         | 1         | 4.55%   |
| Synaptics UWP WBDI                                     | 1         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.55%   |
| AuthenTec Fingerprint Sensor                           | 1         | 4.55%   |
| AuthenTec AES2810                                      | 1         | 4.55%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.55%   |
| AuthenTec AES1600                                      | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 41.67%  |
| Alcor Micro           | 3         | 25%     |
| O2 Micro              | 1         | 8.33%   |
| Lenovo                | 1         | 8.33%   |
| Gemalto (was Gemplus) | 1         | 8.33%   |
| Cherry                | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Broadcom 5880                                    | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor   | 2         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader              | 2         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader             | 1         | 8.33%   |
| Lenovo Integrated Smart Card Reader              | 1         | 8.33%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader | 1         | 8.33%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC      | 1         | 8.33%   |
| Alcor Micro Watchdata W 1981                     | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 199       | 76.25%  |
| 1     | 51        | 19.54%  |
| 2     | 8         | 3.07%   |
| 3     | 2         | 0.77%   |
| 4     | 1         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 29.17%  |
| Graphics card            | 14        | 19.44%  |
| Chipcard                 | 10        | 13.89%  |
| Net/wireless             | 7         | 9.72%   |
| Bluetooth                | 6         | 8.33%   |
| Camera                   | 5         | 6.94%   |
| Network                  | 2         | 2.78%   |
| Dvb card                 | 2         | 2.78%   |
| Storage                  | 1         | 1.39%   |
| Sound                    | 1         | 1.39%   |
| Net/ethernet             | 1         | 1.39%   |
| Multimedia controller    | 1         | 1.39%   |
| Communication controller | 1         | 1.39%   |

