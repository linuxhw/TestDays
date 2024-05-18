Linux in Finland - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Finland.

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

Total: 1279

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad Edge E530c 3366... | [d4d583a573](https://linux-hardware.org/?probe=d4d583a573) | May 07, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C70... | [701d936a1c](https://linux-hardware.org/?probe=701d936a1c) | May 07, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C70... | [6d05bc6b3d](https://linux-hardware.org/?probe=6d05bc6b3d) | May 07, 2024 |
| Dell          | XPS 13 9310                 | [868dd4d0bd](https://linux-hardware.org/?probe=868dd4d0bd) | May 03, 2024 |
| Gigabyte      | P2542                       | [1520cc00e6](https://linux-hardware.org/?probe=1520cc00e6) | May 01, 2024 |
| Acer          | Aspire E5-573               | [1060cb82e8](https://linux-hardware.org/?probe=1060cb82e8) | May 01, 2024 |
| Dell          | Latitude 5490               | [0b0c0eb973](https://linux-hardware.org/?probe=0b0c0eb973) | Apr 29, 2024 |
| Dell          | Inspiron 1011               | [3952627b7f](https://linux-hardware.org/?probe=3952627b7f) | Apr 29, 2024 |
| Valve         | Jupiter                     | [2b383bd91e](https://linux-hardware.org/?probe=2b383bd91e) | Apr 27, 2024 |
| ASUSTek       | K53BY                       | [6f6c4b9d68](https://linux-hardware.org/?probe=6f6c4b9d68) | Apr 26, 2024 |
| HP            | ProBook 450 G0              | [5945f4d2d5](https://linux-hardware.org/?probe=5945f4d2d5) | Apr 26, 2024 |
| HP            | ProBook 450 G0              | [e161f58e8e](https://linux-hardware.org/?probe=e161f58e8e) | Apr 19, 2024 |
| Packard Be... | EasyNote TE69KB             | [ae940fd7b0](https://linux-hardware.org/?probe=ae940fd7b0) | Apr 18, 2024 |
| Packard Be... | EasyNote TE69KB             | [4d615a62ea](https://linux-hardware.org/?probe=4d615a62ea) | Apr 18, 2024 |
| HP            | EliteBook 840 G1            | [a810237e8f](https://linux-hardware.org/?probe=a810237e8f) | Apr 16, 2024 |
| ASUSTek       | UX305CA                     | [e25d8c8e00](https://linux-hardware.org/?probe=e25d8c8e00) | Apr 16, 2024 |
| HP            | EliteBook 640 14 inch G9... | [20fe73c7f9](https://linux-hardware.org/?probe=20fe73c7f9) | Apr 11, 2024 |
| ASUSTek       | N751JK                      | [1d678d0a58](https://linux-hardware.org/?probe=1d678d0a58) | Apr 09, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [d2ba76970a](https://linux-hardware.org/?probe=d2ba76970a) | Apr 04, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [16c1d7aa41](https://linux-hardware.org/?probe=16c1d7aa41) | Apr 04, 2024 |
| Acer          | Aspire 3000                 | [1d2fad06c8](https://linux-hardware.org/?probe=1d2fad06c8) | Apr 02, 2024 |
| Fujitsu       | LIFEBOOK E746               | [0eda4797d3](https://linux-hardware.org/?probe=0eda4797d3) | Apr 01, 2024 |
| HP            | EliteBook 850 G6            | [eb4d7e2521](https://linux-hardware.org/?probe=eb4d7e2521) | Apr 01, 2024 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [3cd31b8ad2](https://linux-hardware.org/?probe=3cd31b8ad2) | Mar 31, 2024 |
| HP            | EliteBook 840 G4            | [b4724cc6b0](https://linux-hardware.org/?probe=b4724cc6b0) | Mar 31, 2024 |
| HP            | Compaq 8510p                | [c57e175a01](https://linux-hardware.org/?probe=c57e175a01) | Mar 29, 2024 |
| Dell          | Latitude E7440              | [8046c24f21](https://linux-hardware.org/?probe=8046c24f21) | Mar 27, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e5e4d98f62](https://linux-hardware.org/?probe=e5e4d98f62) | Mar 25, 2024 |
| Lenovo        | ThinkPad T530 24297XG       | [4935048c5f](https://linux-hardware.org/?probe=4935048c5f) | Mar 25, 2024 |
| Lenovo        | ThinkPad T410 253725G       | [33a07105de](https://linux-hardware.org/?probe=33a07105de) | Mar 24, 2024 |
| Fujitsu       | LIFEBOOK E734               | [1da01e0e94](https://linux-hardware.org/?probe=1da01e0e94) | Mar 24, 2024 |
| HP            | Laptop 14s-fq0xxx           | [5f50d8654a](https://linux-hardware.org/?probe=5f50d8654a) | Mar 23, 2024 |
| Lenovo        | ThinkPad X395 20NMS13801    | [bf71f2099b](https://linux-hardware.org/?probe=bf71f2099b) | Mar 21, 2024 |
| Lenovo        | ThinkPad T480s 20L8002UM... | [b912e786a3](https://linux-hardware.org/?probe=b912e786a3) | Mar 20, 2024 |
| HP            | Pavilion 15                 | [6901a5764b](https://linux-hardware.org/?probe=6901a5764b) | Mar 20, 2024 |
| Apple         | MacBookPro14,1              | [621ae3ca60](https://linux-hardware.org/?probe=621ae3ca60) | Mar 16, 2024 |
| Lenovo        | Yoga 700-11ISK 80QE         | [a0a622a966](https://linux-hardware.org/?probe=a0a622a966) | Mar 14, 2024 |
| eMachines     | E727                        | [af56e195f8](https://linux-hardware.org/?probe=af56e195f8) | Mar 13, 2024 |
| ASUSTek       | UX31E                       | [94fc346288](https://linux-hardware.org/?probe=94fc346288) | Mar 10, 2024 |
| HONOR         | BOHK-WAX9X                  | [d7892c8c29](https://linux-hardware.org/?probe=d7892c8c29) | Mar 10, 2024 |
| Lenovo        | ThinkPad T495 20NKS1RQ01    | [5c00b6631a](https://linux-hardware.org/?probe=5c00b6631a) | Mar 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1dda71290f](https://linux-hardware.org/?probe=1dda71290f) | Mar 08, 2024 |
| ASUSTek       | X555LJ                      | [9e67d96b3f](https://linux-hardware.org/?probe=9e67d96b3f) | Mar 04, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [792fce7b20](https://linux-hardware.org/?probe=792fce7b20) | Feb 29, 2024 |
| Unknown       | WY133A                      | [ac6776d5fc](https://linux-hardware.org/?probe=ac6776d5fc) | Feb 29, 2024 |
| ASUSTek       | T100HAN                     | [1dcbcd018e](https://linux-hardware.org/?probe=1dcbcd018e) | Feb 26, 2024 |
| Acer          | Extensa 215-55              | [14c23eee9c](https://linux-hardware.org/?probe=14c23eee9c) | Feb 26, 2024 |
| Lenovo        | ThinkPad W520 42844ZG       | [6731541710](https://linux-hardware.org/?probe=6731541710) | Feb 24, 2024 |
| Valve         | Galileo                     | [222802e961](https://linux-hardware.org/?probe=222802e961) | Feb 24, 2024 |
| Apple         | MacBookAir7,2               | [2afbc3922a](https://linux-hardware.org/?probe=2afbc3922a) | Feb 23, 2024 |
| Apple         | MacBookPro11,3              | [88448eac7a](https://linux-hardware.org/?probe=88448eac7a) | Feb 23, 2024 |
| Apple         | MacBookPro13,1              | [cc881016ff](https://linux-hardware.org/?probe=cc881016ff) | Feb 22, 2024 |
| Apple         | MacBookPro8,1               | [f8d09630be](https://linux-hardware.org/?probe=f8d09630be) | Feb 20, 2024 |
| Apple         | MacBookPro8,1               | [5eb44e20c3](https://linux-hardware.org/?probe=5eb44e20c3) | Feb 20, 2024 |
| Apple         | MacBookPro13,1              | [6436d22d55](https://linux-hardware.org/?probe=6436d22d55) | Feb 19, 2024 |
| Acer          | Extensa 215-55              | [36eaeb4ef3](https://linux-hardware.org/?probe=36eaeb4ef3) | Feb 16, 2024 |
| HP            | EliteBook 840 G6            | [b3ffbe3673](https://linux-hardware.org/?probe=b3ffbe3673) | Feb 14, 2024 |
| Acer          | Extensa 215-55              | [84309010d3](https://linux-hardware.org/?probe=84309010d3) | Feb 14, 2024 |
| HP            | EliteBook 850 G3            | [35174dcd36](https://linux-hardware.org/?probe=35174dcd36) | Feb 12, 2024 |
| Lenovo        | ThinkPad E495 20NE000JMX    | [efcec1dc1e](https://linux-hardware.org/?probe=efcec1dc1e) | Feb 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [a22b67cf36](https://linux-hardware.org/?probe=a22b67cf36) | Feb 11, 2024 |
| HP            | Pavilion g7                 | [fb9d5315c4](https://linux-hardware.org/?probe=fb9d5315c4) | Feb 11, 2024 |
| HP            | Pavilion g7                 | [d93edf4e50](https://linux-hardware.org/?probe=d93edf4e50) | Feb 11, 2024 |
| HP            | Pavilion Notebook           | [7da16fe9d7](https://linux-hardware.org/?probe=7da16fe9d7) | Feb 09, 2024 |
| Toshiba       | Satellite L40               | [b798661cd0](https://linux-hardware.org/?probe=b798661cd0) | Feb 09, 2024 |
| Dell          | Latitude 5440               | [f1a8f212e3](https://linux-hardware.org/?probe=f1a8f212e3) | Feb 08, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [55b8176dfd](https://linux-hardware.org/?probe=55b8176dfd) | Feb 07, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2bdeaafbb9](https://linux-hardware.org/?probe=2bdeaafbb9) | Feb 06, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a654b497ec](https://linux-hardware.org/?probe=a654b497ec) | Feb 05, 2024 |
| Lenovo        | ThinkPad X13 Gen 2a 20XJ... | [d9db0185ec](https://linux-hardware.org/?probe=d9db0185ec) | Feb 05, 2024 |
| HP            | Pavilion 15                 | [066b0cf774](https://linux-hardware.org/?probe=066b0cf774) | Feb 05, 2024 |
| Panasonic     | CF-54-2                     | [7758f322a6](https://linux-hardware.org/?probe=7758f322a6) | Feb 01, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [02d7b129fc](https://linux-hardware.org/?probe=02d7b129fc) | Jan 31, 2024 |
| Fujitsu       | LIFEBOOK E734               | [7b3a60ae2d](https://linux-hardware.org/?probe=7b3a60ae2d) | Jan 30, 2024 |
| Lenovo        | ThinkPad P52 20M9001MMX     | [0270f75e12](https://linux-hardware.org/?probe=0270f75e12) | Jan 29, 2024 |
| HP            | Laptop 14s-fq0xxx           | [a0eeda1d5a](https://linux-hardware.org/?probe=a0eeda1d5a) | Jan 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [54f3192aa0](https://linux-hardware.org/?probe=54f3192aa0) | Jan 25, 2024 |
| ASUSTek       | X541UV                      | [7df0d2b4af](https://linux-hardware.org/?probe=7df0d2b4af) | Jan 24, 2024 |
| Lenovo        | ThinkPad T530 24297XG       | [9b6f11b3a9](https://linux-hardware.org/?probe=9b6f11b3a9) | Jan 24, 2024 |
| ASUSTek       | T100HAN                     | [66829eb63f](https://linux-hardware.org/?probe=66829eb63f) | Jan 23, 2024 |
| Lenovo        | ThinkPad T480s 20L8S0SA0... | [5f60d47122](https://linux-hardware.org/?probe=5f60d47122) | Jan 21, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1b5e7e0d38](https://linux-hardware.org/?probe=1b5e7e0d38) | Jan 20, 2024 |
| HP            | ProBook 430 G3              | [ed36d7cd8f](https://linux-hardware.org/?probe=ed36d7cd8f) | Jan 20, 2024 |
| Lenovo        | G50-30 80G0                 | [469e8ffc49](https://linux-hardware.org/?probe=469e8ffc49) | Jan 16, 2024 |
| Lenovo        | ThinkPad W520 42844ZG       | [6c360c2400](https://linux-hardware.org/?probe=6c360c2400) | Jan 15, 2024 |
| Acer          | Aspire V5-552G              | [88a4824eac](https://linux-hardware.org/?probe=88a4824eac) | Jan 15, 2024 |
| Acer          | Aspire V5-552G              | [9b2eb6e626](https://linux-hardware.org/?probe=9b2eb6e626) | Jan 15, 2024 |
| HP            | ProBook 445 14 inch G10 ... | [cc219f9e8e](https://linux-hardware.org/?probe=cc219f9e8e) | Jan 13, 2024 |
| HP            | ProBook 445 14 inch G10 ... | [5d10765449](https://linux-hardware.org/?probe=5d10765449) | Jan 13, 2024 |
| Lenovo        | ThinkPad W520 42844ZG       | [e085204d13](https://linux-hardware.org/?probe=e085204d13) | Jan 12, 2024 |
| Lenovo        | ThinkPad T530 24297XG       | [3ca4357d99](https://linux-hardware.org/?probe=3ca4357d99) | Jan 12, 2024 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | [61e9830d84](https://linux-hardware.org/?probe=61e9830d84) | Jan 12, 2024 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | [c74c1758a4](https://linux-hardware.org/?probe=c74c1758a4) | Jan 12, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [a127ed2c69](https://linux-hardware.org/?probe=a127ed2c69) | Jan 11, 2024 |
| Lenovo        | ThinkPad T480s 20L7001HM... | [9663b055e8](https://linux-hardware.org/?probe=9663b055e8) | Jan 10, 2024 |
| HP            | EliteBook 745 G6            | [e7c4951a31](https://linux-hardware.org/?probe=e7c4951a31) | Jan 10, 2024 |
| HP            | EliteBook 645 14 inch G9... | [f56d1e88ba](https://linux-hardware.org/?probe=f56d1e88ba) | Jan 07, 2024 |
| HP            | Pavilion 13 x360 PC         | [52fea1e890](https://linux-hardware.org/?probe=52fea1e890) | Jan 06, 2024 |
| Apple         | MacBookPro8,1               | [a620a3be8d](https://linux-hardware.org/?probe=a620a3be8d) | Jan 06, 2024 |
| Dell          | Latitude E6440              | [4c184aed54](https://linux-hardware.org/?probe=4c184aed54) | Jan 05, 2024 |
| Apple         | MacBookPro8,1               | [1593858ec2](https://linux-hardware.org/?probe=1593858ec2) | Jan 04, 2024 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [23c30ee5a3](https://linux-hardware.org/?probe=23c30ee5a3) | Jan 03, 2024 |
| ASUSTek       | VivoBook E14 E402YA_R417... | [47112e4c46](https://linux-hardware.org/?probe=47112e4c46) | Dec 31, 2023 |
| Dell          | Latitude E6440              | [f4ba63ff52](https://linux-hardware.org/?probe=f4ba63ff52) | Dec 30, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [f3af16ad5d](https://linux-hardware.org/?probe=f3af16ad5d) | Dec 29, 2023 |
| Lenovo        | ThinkPad E480 20KN0065MX    | [14018f1aec](https://linux-hardware.org/?probe=14018f1aec) | Dec 27, 2023 |
| HP            | Laptop 15-db1xxx            | [692cf22259](https://linux-hardware.org/?probe=692cf22259) | Dec 25, 2023 |
| Lenovo        | ThinkPad X270 20HN005NMX    | [aeb2dccb91](https://linux-hardware.org/?probe=aeb2dccb91) | Dec 25, 2023 |
| Lenovo        | ThinkPad X280 20KES63G00    | [a5688cc794](https://linux-hardware.org/?probe=a5688cc794) | Dec 24, 2023 |
| Apple         | MacBookPro8,1               | [24ff90d774](https://linux-hardware.org/?probe=24ff90d774) | Dec 20, 2023 |
| Acer          | Aspire E5-573               | [91c6527140](https://linux-hardware.org/?probe=91c6527140) | Dec 19, 2023 |
| Fujitsu       | LIFEBOOK U728               | [381f2ea08d](https://linux-hardware.org/?probe=381f2ea08d) | Dec 16, 2023 |
| Lenovo        | B50-10 80QR                 | [f44fe4ce19](https://linux-hardware.org/?probe=f44fe4ce19) | Dec 11, 2023 |
| Samsung       | RF511/RF411/RF711           | [59846b1d85](https://linux-hardware.org/?probe=59846b1d85) | Dec 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [949de6a6a9](https://linux-hardware.org/?probe=949de6a6a9) | Dec 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [96a56fd534](https://linux-hardware.org/?probe=96a56fd534) | Dec 09, 2023 |
| Acer          | Aspire E5-573               | [c23042b293](https://linux-hardware.org/?probe=c23042b293) | Dec 08, 2023 |
| Lenovo        | ThinkPad X270 20HN005NMX    | [23d9249c5e](https://linux-hardware.org/?probe=23d9249c5e) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [2d483d736b](https://linux-hardware.org/?probe=2d483d736b) | Dec 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [70394fdace](https://linux-hardware.org/?probe=70394fdace) | Dec 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [9e1d0f5fdc](https://linux-hardware.org/?probe=9e1d0f5fdc) | Dec 03, 2023 |
| Acer          | Aspire E5-573               | [c265401f64](https://linux-hardware.org/?probe=c265401f64) | Dec 03, 2023 |
| HP            | Pavilion dv7                | [42ddf2c00c](https://linux-hardware.org/?probe=42ddf2c00c) | Dec 03, 2023 |
| Lenovo        | ThinkPad T420 4180PBG       | [7922226a1c](https://linux-hardware.org/?probe=7922226a1c) | Dec 02, 2023 |
| Lenovo        | ThinkPad T420 4180PBG       | [cb2b5c10a7](https://linux-hardware.org/?probe=cb2b5c10a7) | Dec 02, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [d923b4bdf8](https://linux-hardware.org/?probe=d923b4bdf8) | Dec 02, 2023 |
| HP            | Laptop 14-dk0xxx            | [eae202e5f1](https://linux-hardware.org/?probe=eae202e5f1) | Nov 28, 2023 |
| HP            | Laptop 15s-eq1xxx           | [0769357573](https://linux-hardware.org/?probe=0769357573) | Nov 27, 2023 |
| Acer          | Swift SFE16-43              | [849f368635](https://linux-hardware.org/?probe=849f368635) | Nov 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [956dbda516](https://linux-hardware.org/?probe=956dbda516) | Nov 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [5289268737](https://linux-hardware.org/?probe=5289268737) | Nov 24, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [bd428a8490](https://linux-hardware.org/?probe=bd428a8490) | Nov 22, 2023 |
| Fujitsu       | LIFEBOOK S710               | [a0453d2f05](https://linux-hardware.org/?probe=a0453d2f05) | Nov 20, 2023 |
| Unknown       | M17                         | [1708365bec](https://linux-hardware.org/?probe=1708365bec) | Nov 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d0549c695d](https://linux-hardware.org/?probe=d0549c695d) | Nov 13, 2023 |
| HP            | Unknown                     | [c22e23b2f8](https://linux-hardware.org/?probe=c22e23b2f8) | Nov 12, 2023 |
| Dell          | Latitude E5430 non-vPro     | [518492850b](https://linux-hardware.org/?probe=518492850b) | Nov 10, 2023 |
| Lenovo        | ThinkPad T490 20N3S7AA00    | [b4fd9fd045](https://linux-hardware.org/?probe=b4fd9fd045) | Nov 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [39e2c7584e](https://linux-hardware.org/?probe=39e2c7584e) | Nov 08, 2023 |
| Fujitsu Si... | AMILO Li 1818               | [ab74cc1cc6](https://linux-hardware.org/?probe=ab74cc1cc6) | Nov 07, 2023 |
| HP            | EliteBook 840 G3            | [1bb894cf19](https://linux-hardware.org/?probe=1bb894cf19) | Nov 04, 2023 |
| MSI           | GF75 Thin 9SC               | [2aceaf7016](https://linux-hardware.org/?probe=2aceaf7016) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [2bdd27dc18](https://linux-hardware.org/?probe=2bdd27dc18) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [cb35a8d8f6](https://linux-hardware.org/?probe=cb35a8d8f6) | Oct 31, 2023 |
| ASUSTek       | X507UA                      | [c52aa98c38](https://linux-hardware.org/?probe=c52aa98c38) | Oct 31, 2023 |
| Lenovo        | ThinkPad T60 1952WUV        | [4ecf9f7f50](https://linux-hardware.org/?probe=4ecf9f7f50) | Oct 30, 2023 |
| HP            | EliteBook 8460p             | [7d6972297f](https://linux-hardware.org/?probe=7d6972297f) | Oct 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ecab2bb9fe](https://linux-hardware.org/?probe=ecab2bb9fe) | Oct 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f9adbc34d](https://linux-hardware.org/?probe=0f9adbc34d) | Oct 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [a3355c6898](https://linux-hardware.org/?probe=a3355c6898) | Oct 27, 2023 |
| Lenovo        | G580 2189                   | [18dc8e53d9](https://linux-hardware.org/?probe=18dc8e53d9) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | [0fb2b25961](https://linux-hardware.org/?probe=0fb2b25961) | Oct 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8754714bce](https://linux-hardware.org/?probe=8754714bce) | Oct 23, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [f2b15bc2f1](https://linux-hardware.org/?probe=f2b15bc2f1) | Oct 23, 2023 |
| HP            | Pavilion g7                 | [11f3136e05](https://linux-hardware.org/?probe=11f3136e05) | Oct 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0504910ad7](https://linux-hardware.org/?probe=0504910ad7) | Oct 16, 2023 |
| ASUSTek       | N551ZU                      | [e56a6c7957](https://linux-hardware.org/?probe=e56a6c7957) | Oct 16, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [2956823009](https://linux-hardware.org/?probe=2956823009) | Oct 14, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [d268453669](https://linux-hardware.org/?probe=d268453669) | Oct 13, 2023 |
| ASUSTek       | GR8                         | [5b509d021c](https://linux-hardware.org/?probe=5b509d021c) | Oct 13, 2023 |
| ASUSTek       | GR8                         | [e381fff6d8](https://linux-hardware.org/?probe=e381fff6d8) | Oct 13, 2023 |
| Lenovo        | ThinkPad T400 27658JG       | [3b3b7832c9](https://linux-hardware.org/?probe=3b3b7832c9) | Oct 11, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [afff949494](https://linux-hardware.org/?probe=afff949494) | Oct 08, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9dc2fd3247](https://linux-hardware.org/?probe=9dc2fd3247) | Oct 06, 2023 |
| Apple         | MacBookPro16,3              | [9ca487f2cf](https://linux-hardware.org/?probe=9ca487f2cf) | Oct 02, 2023 |
| HP            | Pavilion 11 x360 PC         | [b3eb082c5e](https://linux-hardware.org/?probe=b3eb082c5e) | Oct 01, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [dc762f9ae6](https://linux-hardware.org/?probe=dc762f9ae6) | Sep 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [2cf86f7f12](https://linux-hardware.org/?probe=2cf86f7f12) | Sep 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [9a24a19f6e](https://linux-hardware.org/?probe=9a24a19f6e) | Sep 25, 2023 |
| Acer          | Aspire 7730G                | [e21c91c34c](https://linux-hardware.org/?probe=e21c91c34c) | Sep 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eb276947f2](https://linux-hardware.org/?probe=eb276947f2) | Sep 23, 2023 |
| HP            | EliteBook 8570p             | [ca346761d3](https://linux-hardware.org/?probe=ca346761d3) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [e75a2a8b71](https://linux-hardware.org/?probe=e75a2a8b71) | Sep 22, 2023 |
| HP            | EliteBook 840 G3            | [b6379ef77c](https://linux-hardware.org/?probe=b6379ef77c) | Sep 22, 2023 |
| Acer          | Aspire 5741G                | [b79d8aec76](https://linux-hardware.org/?probe=b79d8aec76) | Sep 21, 2023 |
| Lenovo        | ThinkPad W520 4284W1D       | [c634509519](https://linux-hardware.org/?probe=c634509519) | Sep 18, 2023 |
| ASUSTek       | N73SM                       | [d4ce8f336d](https://linux-hardware.org/?probe=d4ce8f336d) | Sep 17, 2023 |
| Toshiba       | QOSMIO X770                 | [84fc7ea45e](https://linux-hardware.org/?probe=84fc7ea45e) | Sep 17, 2023 |
| Fujitsu       | LIFEBOOK E733               | [0613157456](https://linux-hardware.org/?probe=0613157456) | Sep 15, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [3b71101d09](https://linux-hardware.org/?probe=3b71101d09) | Sep 14, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [ef5a6433f3](https://linux-hardware.org/?probe=ef5a6433f3) | Sep 13, 2023 |
| HP            | Pavilion dv7                | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| HP            | Pavilion Laptop 14-bf1xx    | [fe3ed738a1](https://linux-hardware.org/?probe=fe3ed738a1) | Sep 11, 2023 |
| Apple         | MacBookPro8,2               | [f23bb97453](https://linux-hardware.org/?probe=f23bb97453) | Sep 11, 2023 |
| Acer          | Aspire V5-472               | [198d33eff6](https://linux-hardware.org/?probe=198d33eff6) | Sep 09, 2023 |
| Lenovo        | ThinkPad P43s 20RH001UMX    | [0fdff74089](https://linux-hardware.org/?probe=0fdff74089) | Sep 07, 2023 |
| Lenovo        | ThinkPad T450 20BUS3L502    | [cb8de94658](https://linux-hardware.org/?probe=cb8de94658) | Sep 05, 2023 |
| Apple         | MacBookPro11,1              | [d8efe50ca5](https://linux-hardware.org/?probe=d8efe50ca5) | Sep 04, 2023 |
| Fujitsu       | LIFEBOOK E734               | [1b89968327](https://linux-hardware.org/?probe=1b89968327) | Sep 03, 2023 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [0a55847393](https://linux-hardware.org/?probe=0a55847393) | Aug 30, 2023 |
| ASUSTek       | X541UAK                     | [c75a044974](https://linux-hardware.org/?probe=c75a044974) | Aug 30, 2023 |
| Lenovo        | Y50-70 20378                | [5a20b8cd20](https://linux-hardware.org/?probe=5a20b8cd20) | Aug 29, 2023 |
| HP            | 630                         | [4a94779668](https://linux-hardware.org/?probe=4a94779668) | Aug 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 4 21H5C... | [96b559d5d6](https://linux-hardware.org/?probe=96b559d5d6) | Aug 27, 2023 |
| ASUSTek       | TP300LA                     | [7588e955e3](https://linux-hardware.org/?probe=7588e955e3) | Aug 27, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [9b94ab3887](https://linux-hardware.org/?probe=9b94ab3887) | Aug 27, 2023 |
| HP            | EliteBook 840 G3            | [d3c6faac81](https://linux-hardware.org/?probe=d3c6faac81) | Aug 25, 2023 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | [1a86753f1c](https://linux-hardware.org/?probe=1a86753f1c) | Aug 20, 2023 |
| ASUSTek       | X541UAK                     | [048ca1ce02](https://linux-hardware.org/?probe=048ca1ce02) | Aug 20, 2023 |
| Valve         | Jupiter                     | [0a6ed7bae4](https://linux-hardware.org/?probe=0a6ed7bae4) | Aug 19, 2023 |
| Apple         | MacBookAir6,2               | [76dda9cde6](https://linux-hardware.org/?probe=76dda9cde6) | Aug 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [da5582d4bf](https://linux-hardware.org/?probe=da5582d4bf) | Aug 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [63f2bc3a80](https://linux-hardware.org/?probe=63f2bc3a80) | Aug 16, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MN    | [c853746c1f](https://linux-hardware.org/?probe=c853746c1f) | Aug 16, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MN    | [a460ba57d2](https://linux-hardware.org/?probe=a460ba57d2) | Aug 16, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [6cbef2a38d](https://linux-hardware.org/?probe=6cbef2a38d) | Aug 13, 2023 |
| Dell          | Latitude E6330              | [b3081e041e](https://linux-hardware.org/?probe=b3081e041e) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [2980681052](https://linux-hardware.org/?probe=2980681052) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8b84e48f4c](https://linux-hardware.org/?probe=8b84e48f4c) | Aug 04, 2023 |
| Lenovo        | Yoga 2 13 20344             | [767b492aa4](https://linux-hardware.org/?probe=767b492aa4) | Aug 03, 2023 |
| Lenovo        | Yoga 2 13 20344             | [47ca08e0d1](https://linux-hardware.org/?probe=47ca08e0d1) | Aug 03, 2023 |
| HP            | Unknown                     | [f7ffb3c085](https://linux-hardware.org/?probe=f7ffb3c085) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | [f84a39b436](https://linux-hardware.org/?probe=f84a39b436) | Jul 31, 2023 |
| Lenovo        | V145-15AST 81MT             | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| Lenovo        | ThinkPad T520 4243JA1       | [410cebaba3](https://linux-hardware.org/?probe=410cebaba3) | Jul 28, 2023 |
| Lenovo        | ThinkPad W500 4063WPV       | [d750cddcb0](https://linux-hardware.org/?probe=d750cddcb0) | Jul 26, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [6750fae080](https://linux-hardware.org/?probe=6750fae080) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [a61cd014ac](https://linux-hardware.org/?probe=a61cd014ac) | Jul 23, 2023 |
| HP            | EliteBook 6930p (NG813UP... | [4c6736fd14](https://linux-hardware.org/?probe=4c6736fd14) | Jul 17, 2023 |
| HP            | EliteBook 6930p (NG813UP... | [33b2f9227b](https://linux-hardware.org/?probe=33b2f9227b) | Jul 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9e037f08e1](https://linux-hardware.org/?probe=9e037f08e1) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [b592c5b551](https://linux-hardware.org/?probe=b592c5b551) | Jul 15, 2023 |
| HP            | Pavilion dv7                | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [151cc29e31](https://linux-hardware.org/?probe=151cc29e31) | Jul 12, 2023 |
| ASUSTek       | TP300LA                     | [7821a5e0e6](https://linux-hardware.org/?probe=7821a5e0e6) | Jul 05, 2023 |
| HP            | ProBook 650 G1              | [8805bd2666](https://linux-hardware.org/?probe=8805bd2666) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [c1a241c0a5](https://linux-hardware.org/?probe=c1a241c0a5) | Jul 03, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [728d4edecd](https://linux-hardware.org/?probe=728d4edecd) | Jul 01, 2023 |
| HP            | ProBook 650 G1              | [593959e6f3](https://linux-hardware.org/?probe=593959e6f3) | Jun 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| HP            | 250 G3                      | [90647a4b33](https://linux-hardware.org/?probe=90647a4b33) | Jun 28, 2023 |
| Apple         | MacBookPro8,2               | [3e5baaaa01](https://linux-hardware.org/?probe=3e5baaaa01) | Jun 27, 2023 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [0defa5c92d](https://linux-hardware.org/?probe=0defa5c92d) | Jun 27, 2023 |
| Acer          | Nitro AN515-55              | [2153f80362](https://linux-hardware.org/?probe=2153f80362) | Jun 25, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4429a0f659](https://linux-hardware.org/?probe=4429a0f659) | Jun 23, 2023 |
| Lenovo        | B5400 80B6QB0               | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [017f0476b0](https://linux-hardware.org/?probe=017f0476b0) | Jun 21, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [4af402b7c9](https://linux-hardware.org/?probe=4af402b7c9) | Jun 21, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| Toshiba       | Satellite C850-1DV          | [eb574aab3b](https://linux-hardware.org/?probe=eb574aab3b) | Jun 19, 2023 |
| ASUSTek       | UX530UQ                     | [c952ec8390](https://linux-hardware.org/?probe=c952ec8390) | Jun 13, 2023 |
| Fujitsu       | LIFEBOOK A514               | [45b16c1cdf](https://linux-hardware.org/?probe=45b16c1cdf) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | [1da963b3f4](https://linux-hardware.org/?probe=1da963b3f4) | Jun 12, 2023 |
| Lenovo        | Yoga 2 13 20344             | [eab5787d6a](https://linux-hardware.org/?probe=eab5787d6a) | Jun 11, 2023 |
| ASUSTek       | UX530UQ                     | [71d0ddd2f0](https://linux-hardware.org/?probe=71d0ddd2f0) | Jun 09, 2023 |
| Gigabyte      | P2542                       | [12a2415432](https://linux-hardware.org/?probe=12a2415432) | Jun 08, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [281be42f34](https://linux-hardware.org/?probe=281be42f34) | Jun 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [f9b3588ff3](https://linux-hardware.org/?probe=f9b3588ff3) | Jun 07, 2023 |
| Lenovo        | ThinkPad T495 20NKS10K00    | [f205c52b8f](https://linux-hardware.org/?probe=f205c52b8f) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [16aa33fdfe](https://linux-hardware.org/?probe=16aa33fdfe) | Jun 06, 2023 |
| HP            | Laptop 17-ak0xx             | [a0430d6f0c](https://linux-hardware.org/?probe=a0430d6f0c) | Jun 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [9a1c9022af](https://linux-hardware.org/?probe=9a1c9022af) | Jun 05, 2023 |
| HP            | EliteBook 840 G1            | [4840dda2e3](https://linux-hardware.org/?probe=4840dda2e3) | Jun 04, 2023 |
| HP            | EliteBook 8440p             | [7f95f275b3](https://linux-hardware.org/?probe=7f95f275b3) | Jun 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| Gigabyte      | P2542                       | [b1064cae7a](https://linux-hardware.org/?probe=b1064cae7a) | May 30, 2023 |
| Gigabyte      | P2542                       | [7cded000f2](https://linux-hardware.org/?probe=7cded000f2) | May 30, 2023 |
| Toshiba       | Satellite L500              | [b1213efe40](https://linux-hardware.org/?probe=b1213efe40) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [cb238efd5e](https://linux-hardware.org/?probe=cb238efd5e) | May 27, 2023 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [a81e627367](https://linux-hardware.org/?probe=a81e627367) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [0197aaf79a](https://linux-hardware.org/?probe=0197aaf79a) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [bb39617225](https://linux-hardware.org/?probe=bb39617225) | May 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [f811501691](https://linux-hardware.org/?probe=f811501691) | May 18, 2023 |
| HP            | EliteBook 745 G4            | [7c6154717b](https://linux-hardware.org/?probe=7c6154717b) | May 18, 2023 |
| HP            | Stream Notebook PC 14       | [835c46e8e2](https://linux-hardware.org/?probe=835c46e8e2) | May 18, 2023 |
| ASUSTek       | K73SV                       | [d1d5700b2c](https://linux-hardware.org/?probe=d1d5700b2c) | May 18, 2023 |
| Lenovo        | ThinkPad T400 276522G       | [dc8b38dd37](https://linux-hardware.org/?probe=dc8b38dd37) | May 17, 2023 |
| ASUSTek       | G750JM                      | [2a93ec6ed8](https://linux-hardware.org/?probe=2a93ec6ed8) | May 17, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [de0485927b](https://linux-hardware.org/?probe=de0485927b) | May 17, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f5ef3c16c5](https://linux-hardware.org/?probe=f5ef3c16c5) | May 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b788039ba1](https://linux-hardware.org/?probe=b788039ba1) | May 15, 2023 |
| HP            | EliteBook 2560p             | [2a50b288f8](https://linux-hardware.org/?probe=2a50b288f8) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23205XG       | [dede8cf401](https://linux-hardware.org/?probe=dede8cf401) | May 14, 2023 |
| Lenovo        | ThinkPad X230 23205XG       | [9fd366eba6](https://linux-hardware.org/?probe=9fd366eba6) | May 14, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b81c403545](https://linux-hardware.org/?probe=b81c403545) | May 09, 2023 |
| HP            | 655                         | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Lenovo        | ThinkPad Edge E320 12988... | [5d3d3fb42e](https://linux-hardware.org/?probe=5d3d3fb42e) | May 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [3e42d222a0](https://linux-hardware.org/?probe=3e42d222a0) | May 02, 2023 |
| Dell          | Latitude 7370               | [c984360af7](https://linux-hardware.org/?probe=c984360af7) | May 02, 2023 |
| Dell          | Latitude 7370               | [295b50d5b2](https://linux-hardware.org/?probe=295b50d5b2) | May 02, 2023 |
| HP            | Pavilion dv7                | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [1e7a947d41](https://linux-hardware.org/?probe=1e7a947d41) | Apr 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | [9a7a15dae3](https://linux-hardware.org/?probe=9a7a15dae3) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | [754fc44526](https://linux-hardware.org/?probe=754fc44526) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | [379a1710e5](https://linux-hardware.org/?probe=379a1710e5) | Apr 25, 2023 |
| Dell          | Latitude 5420               | [8c1a7992c0](https://linux-hardware.org/?probe=8c1a7992c0) | Apr 25, 2023 |
| Lenovo        | ThinkPad A285 20MXS0NJ00    | [f155ad2bf4](https://linux-hardware.org/?probe=f155ad2bf4) | Apr 24, 2023 |
| Dell          | Latitude E5470              | [bc1dca3c78](https://linux-hardware.org/?probe=bc1dca3c78) | Apr 24, 2023 |
| HP            | EliteBook 830 G5            | [6090be709d](https://linux-hardware.org/?probe=6090be709d) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [f9415c65e9](https://linux-hardware.org/?probe=f9415c65e9) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [fc27cf4b3e](https://linux-hardware.org/?probe=fc27cf4b3e) | Apr 19, 2023 |
| ASUSTek       | UX305CA                     | [0ff08e0727](https://linux-hardware.org/?probe=0ff08e0727) | Apr 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3ea28c33c9](https://linux-hardware.org/?probe=3ea28c33c9) | Apr 16, 2023 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [6c711c5197](https://linux-hardware.org/?probe=6c711c5197) | Apr 15, 2023 |
| HP            | EliteBook 850 G4            | [984cf8fd47](https://linux-hardware.org/?probe=984cf8fd47) | Apr 14, 2023 |
| Notebook      | N7x0WU                      | [5d37070bf0](https://linux-hardware.org/?probe=5d37070bf0) | Apr 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9ce743560b](https://linux-hardware.org/?probe=9ce743560b) | Apr 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [91da873411](https://linux-hardware.org/?probe=91da873411) | Apr 14, 2023 |
| Dell          | Latitude E7440              | [4cfe81f687](https://linux-hardware.org/?probe=4cfe81f687) | Apr 12, 2023 |
| Lenovo        | ThinkPad L580 20LW000VMX    | [7b2e3794c9](https://linux-hardware.org/?probe=7b2e3794c9) | Apr 11, 2023 |
| Google        | Lindar rev3                 | [e6dd3f6805](https://linux-hardware.org/?probe=e6dd3f6805) | Apr 09, 2023 |
| Acer          | Enduro EUN314-51WG          | [7f73117dba](https://linux-hardware.org/?probe=7f73117dba) | Apr 09, 2023 |
| Lenovo        | ThinkPad T470s 20HF0001M... | [8c6105e5be](https://linux-hardware.org/?probe=8c6105e5be) | Apr 06, 2023 |
| Lenovo        | ThinkPad T410 2537WB7       | [d68ffd9d0f](https://linux-hardware.org/?probe=d68ffd9d0f) | Apr 04, 2023 |
| MSI           | GL63 8RC                    | [8c90ec7da1](https://linux-hardware.org/?probe=8c90ec7da1) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | [cd18ce0a96](https://linux-hardware.org/?probe=cd18ce0a96) | Apr 03, 2023 |
| MSI           | GS66 Stealth 11UH           | [43a7d8f578](https://linux-hardware.org/?probe=43a7d8f578) | Apr 03, 2023 |
| Acer          | Aspire A515-51              | [c9245a7032](https://linux-hardware.org/?probe=c9245a7032) | Apr 03, 2023 |
| HP            | EliteBook 840 G3            | [20e885eb0b](https://linux-hardware.org/?probe=20e885eb0b) | Apr 02, 2023 |
| Motion Com... | J3600                       | [0980fe0a37](https://linux-hardware.org/?probe=0980fe0a37) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d74490158e](https://linux-hardware.org/?probe=d74490158e) | Mar 29, 2023 |
| Lenovo        | IdeaPad S145-14IWL          | [91f36f67a4](https://linux-hardware.org/?probe=91f36f67a4) | Mar 28, 2023 |
| Dell          | Latitude E5250              | [7d9e678484](https://linux-hardware.org/?probe=7d9e678484) | Mar 27, 2023 |
| MSI           | GL63 8RC                    | [935b78c3da](https://linux-hardware.org/?probe=935b78c3da) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E744               | [f32cce4c6f](https://linux-hardware.org/?probe=f32cce4c6f) | Mar 26, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [d77c81e9e3](https://linux-hardware.org/?probe=d77c81e9e3) | Mar 24, 2023 |
| Valve         | Jupiter                     | [f2fed76f66](https://linux-hardware.org/?probe=f2fed76f66) | Mar 23, 2023 |
| Dell          | Latitude E6430              | [7eafa653dc](https://linux-hardware.org/?probe=7eafa653dc) | Mar 20, 2023 |
| HP            | EliteBook 840 G3            | [8a2a9a9e75](https://linux-hardware.org/?probe=8a2a9a9e75) | Mar 18, 2023 |
| Dell          | Latitude E5470              | [6565aa43e3](https://linux-hardware.org/?probe=6565aa43e3) | Mar 18, 2023 |
| HP            | EliteBook 6930p             | [c9ba614358](https://linux-hardware.org/?probe=c9ba614358) | Mar 18, 2023 |
| Alienware     | 15 R3                       | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| HP            | EliteBook 850 G2            | [f2b9853f35](https://linux-hardware.org/?probe=f2b9853f35) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [57f2de5da4](https://linux-hardware.org/?probe=57f2de5da4) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [2a316e6d03](https://linux-hardware.org/?probe=2a316e6d03) | Mar 16, 2023 |
| HP            | EliteBook 830 G5            | [c6aa050dd1](https://linux-hardware.org/?probe=c6aa050dd1) | Mar 16, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [ae9acbc4ef](https://linux-hardware.org/?probe=ae9acbc4ef) | Mar 15, 2023 |
| HP            | EliteBook 840 G3            | [e111e27012](https://linux-hardware.org/?probe=e111e27012) | Mar 13, 2023 |
| Dell          | Precision M4500             | [b61053a0de](https://linux-hardware.org/?probe=b61053a0de) | Mar 13, 2023 |
| ASUSTek       | UX430UAR                    | [a2b1839fd1](https://linux-hardware.org/?probe=a2b1839fd1) | Mar 11, 2023 |
| HP            | ZBook 17                    | [a775bc33c5](https://linux-hardware.org/?probe=a775bc33c5) | Mar 11, 2023 |
| Lenovo        | G580 2189                   | [5e2c4e9a1c](https://linux-hardware.org/?probe=5e2c4e9a1c) | Mar 09, 2023 |
| HP            | ZBook 17                    | [e3fb994c04](https://linux-hardware.org/?probe=e3fb994c04) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | [5a9c11da8a](https://linux-hardware.org/?probe=5a9c11da8a) | Mar 07, 2023 |
| HP            | Laptop 14-cm0xxx            | [e24f683971](https://linux-hardware.org/?probe=e24f683971) | Mar 06, 2023 |
| Acer          | Aspire A315-54              | [cadbbe841e](https://linux-hardware.org/?probe=cadbbe841e) | Mar 05, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [d49f7315d3](https://linux-hardware.org/?probe=d49f7315d3) | Mar 04, 2023 |
| Lenovo        | ThinkPad X240 20AMS2EH00    | [11d225cddb](https://linux-hardware.org/?probe=11d225cddb) | Mar 03, 2023 |
| HP            | Compaq Presario CQ60        | [5ad0c4c383](https://linux-hardware.org/?probe=5ad0c4c383) | Mar 03, 2023 |
| Lenovo        | ThinkPad X260 20F5S1MN00    | [db0d3b74bd](https://linux-hardware.org/?probe=db0d3b74bd) | Feb 27, 2023 |
| HP            | ProBook 470 G1              | [8044704386](https://linux-hardware.org/?probe=8044704386) | Feb 26, 2023 |
| Lenovo        | ThinkPad L412 0585A38       | [da6493ef82](https://linux-hardware.org/?probe=da6493ef82) | Feb 25, 2023 |
| Alienware     | 15 R3                       | [72543030d5](https://linux-hardware.org/?probe=72543030d5) | Feb 25, 2023 |
| Acer          | Aspire A315-54              | [ff08a846b0](https://linux-hardware.org/?probe=ff08a846b0) | Feb 25, 2023 |
| HP            | ProBook 4530s               | [305f79455e](https://linux-hardware.org/?probe=305f79455e) | Feb 24, 2023 |
| Fujitsu       | LIFEBOOK A530               | [9035e056b4](https://linux-hardware.org/?probe=9035e056b4) | Feb 24, 2023 |
| HP            | Compaq CQ58                 | [cfff7e8c96](https://linux-hardware.org/?probe=cfff7e8c96) | Feb 24, 2023 |
| Dell          | Latitude D620               | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| ASUSTek       | X550LB                      | [736bb83bb8](https://linux-hardware.org/?probe=736bb83bb8) | Feb 23, 2023 |
| Dell          | Latitude E5470              | [12a8a55fca](https://linux-hardware.org/?probe=12a8a55fca) | Feb 23, 2023 |
| Apple         | MacBookPro8,2               | [fd4b8d6419](https://linux-hardware.org/?probe=fd4b8d6419) | Feb 22, 2023 |
| Fujitsu       | LIFEBOOK E753               | [8fa3315cca](https://linux-hardware.org/?probe=8fa3315cca) | Feb 22, 2023 |
| Acer          | Aspire A315-54              | [7cf8754a48](https://linux-hardware.org/?probe=7cf8754a48) | Feb 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Acer          | Aspire 6530G                | [c1d73e8ceb](https://linux-hardware.org/?probe=c1d73e8ceb) | Feb 20, 2023 |
| HP            | EliteBook 830 G5            | [0cb773d407](https://linux-hardware.org/?probe=0cb773d407) | Feb 20, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [47e6250a37](https://linux-hardware.org/?probe=47e6250a37) | Feb 19, 2023 |
| Chuwi         | GemiBook Pro                | [7af4d238e8](https://linux-hardware.org/?probe=7af4d238e8) | Feb 18, 2023 |
| ASUSTek       | K54C                        | [ea944628df](https://linux-hardware.org/?probe=ea944628df) | Feb 17, 2023 |
| Valve         | Jupiter                     | [9f63fbafbe](https://linux-hardware.org/?probe=9f63fbafbe) | Feb 16, 2023 |
| Acer          | Predator G9-793             | [8c11736bf0](https://linux-hardware.org/?probe=8c11736bf0) | Feb 11, 2023 |
| Fujitsu       | LIFEBOOK U748               | [2a189f2497](https://linux-hardware.org/?probe=2a189f2497) | Feb 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8d2e488f38](https://linux-hardware.org/?probe=8d2e488f38) | Feb 09, 2023 |
| Dell          | Latitude E7440              | [ac0e96d86c](https://linux-hardware.org/?probe=ac0e96d86c) | Feb 08, 2023 |
| HP            | ZBook 15 G4                 | [f2a6af1f7e](https://linux-hardware.org/?probe=f2a6af1f7e) | Feb 06, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d9401dac6d](https://linux-hardware.org/?probe=d9401dac6d) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK E736               | [a8fea59f32](https://linux-hardware.org/?probe=a8fea59f32) | Feb 04, 2023 |
| Fujitsu       | LIFEBOOK E736               | [67c2139481](https://linux-hardware.org/?probe=67c2139481) | Feb 04, 2023 |
| ASUSTek       | X550JK                      | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| HP            | EliteBook 840 G1            | [b6f1c93413](https://linux-hardware.org/?probe=b6f1c93413) | Feb 02, 2023 |
| HP            | ZBook 15 G4                 | [e523dbd162](https://linux-hardware.org/?probe=e523dbd162) | Feb 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [29660bbd04](https://linux-hardware.org/?probe=29660bbd04) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [3fc59532b8](https://linux-hardware.org/?probe=3fc59532b8) | Feb 01, 2023 |
| Dell          | Precision 5560              | [c994bfa3a7](https://linux-hardware.org/?probe=c994bfa3a7) | Jan 30, 2023 |
| HP            | ZBook 15 G4                 | [3e957e185d](https://linux-hardware.org/?probe=3e957e185d) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | [849d901314](https://linux-hardware.org/?probe=849d901314) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a4ded61661](https://linux-hardware.org/?probe=a4ded61661) | Jan 27, 2023 |
| Lenovo        | ThinkPad R500 2718WA3       | [2bb86279a8](https://linux-hardware.org/?probe=2bb86279a8) | Jan 27, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [0065b33518](https://linux-hardware.org/?probe=0065b33518) | Jan 26, 2023 |
| Dell          | Inspiron 7577               | [4dded574d3](https://linux-hardware.org/?probe=4dded574d3) | Jan 25, 2023 |
| Fujitsu Si... | AMILO Notebook Xa 3530      | [e8384494a3](https://linux-hardware.org/?probe=e8384494a3) | Jan 25, 2023 |
| Lenovo        | ThinkPad T430s 2356GRG      | [cd81d567a2](https://linux-hardware.org/?probe=cd81d567a2) | Jan 24, 2023 |
| HP            | EliteBook 840 G1            | [08d8bb84c4](https://linux-hardware.org/?probe=08d8bb84c4) | Jan 24, 2023 |
| Packard Be... | EasyNote TE69KB             | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| HP            | Pavilion 17                 | [0ba46e91d2](https://linux-hardware.org/?probe=0ba46e91d2) | Jan 22, 2023 |
| ASUSTek       | GL753VE                     | [10796ad8f6](https://linux-hardware.org/?probe=10796ad8f6) | Jan 21, 2023 |
| Acer          | Predator G9-591             | [0544a1b07c](https://linux-hardware.org/?probe=0544a1b07c) | Jan 21, 2023 |
| Lenovo        | ThinkPad E470 20H1004SMX    | [0d8528f0d2](https://linux-hardware.org/?probe=0d8528f0d2) | Jan 19, 2023 |
| Valve         | Jupiter                     | [bd55cae677](https://linux-hardware.org/?probe=bd55cae677) | Jan 17, 2023 |
| Lenovo        | ThinkPad T490s 20NX001KM... | [e24691c830](https://linux-hardware.org/?probe=e24691c830) | Jan 15, 2023 |
| Dell          | Precision M4700             | [64bd9a7627](https://linux-hardware.org/?probe=64bd9a7627) | Jan 14, 2023 |
| ASUSTek       | N53SM                       | [fdf56c0639](https://linux-hardware.org/?probe=fdf56c0639) | Jan 13, 2023 |
| Acer          | Aspire 7730G                | [ba1e942da3](https://linux-hardware.org/?probe=ba1e942da3) | Jan 12, 2023 |
| TUXEDO        | Unknown                     | [ae60044fa6](https://linux-hardware.org/?probe=ae60044fa6) | Jan 12, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [7a2cdcb0ab](https://linux-hardware.org/?probe=7a2cdcb0ab) | Jan 12, 2023 |
| ASUSTek       | X550LN                      | [791cd47247](https://linux-hardware.org/?probe=791cd47247) | Jan 12, 2023 |
| HP            | Unknown                     | [604bea5ac6](https://linux-hardware.org/?probe=604bea5ac6) | Jan 11, 2023 |
| Acer          | Predator G9-591             | [aa9794813e](https://linux-hardware.org/?probe=aa9794813e) | Jan 11, 2023 |
| Apple         | MacBookAir5,1               | [ce911686b3](https://linux-hardware.org/?probe=ce911686b3) | Jan 10, 2023 |
| HP            | 255 G4                      | [1893637142](https://linux-hardware.org/?probe=1893637142) | Jan 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6e756926b8](https://linux-hardware.org/?probe=6e756926b8) | Jan 09, 2023 |
| Dell          | XPS 13 7390                 | [7a89ea18a0](https://linux-hardware.org/?probe=7a89ea18a0) | Jan 06, 2023 |
| ASUSTek       | X501A1                      | [f88e88d88d](https://linux-hardware.org/?probe=f88e88d88d) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [729d97d43a](https://linux-hardware.org/?probe=729d97d43a) | Jan 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [4b951f8c2a](https://linux-hardware.org/?probe=4b951f8c2a) | Jan 02, 2023 |
| Acer          | Aspire 5732Z                | [86b79bce9e](https://linux-hardware.org/?probe=86b79bce9e) | Jan 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [347dc56d43](https://linux-hardware.org/?probe=347dc56d43) | Dec 30, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ad4be7f0fa](https://linux-hardware.org/?probe=ad4be7f0fa) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a70ba97a7a](https://linux-hardware.org/?probe=a70ba97a7a) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [3cfcfad4ba](https://linux-hardware.org/?probe=3cfcfad4ba) | Dec 22, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [9e860431a0](https://linux-hardware.org/?probe=9e860431a0) | Dec 20, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [8e689417f3](https://linux-hardware.org/?probe=8e689417f3) | Dec 16, 2022 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | [bed7f6d44e](https://linux-hardware.org/?probe=bed7f6d44e) | Dec 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [66b2e8e737](https://linux-hardware.org/?probe=66b2e8e737) | Dec 14, 2022 |
| Acer          | Predator G9-591             | [838b0e0f8c](https://linux-hardware.org/?probe=838b0e0f8c) | Dec 13, 2022 |
| Acer          | Aspire A315-43              | [6d77f1e173](https://linux-hardware.org/?probe=6d77f1e173) | Dec 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| Acer          | Predator G9-591             | [6e8fe2e030](https://linux-hardware.org/?probe=6e8fe2e030) | Dec 06, 2022 |
| Dell          | Latitude E6440              | [425331326b](https://linux-hardware.org/?probe=425331326b) | Dec 06, 2022 |
| Valve         | Jupiter                     | [19f5d58b52](https://linux-hardware.org/?probe=19f5d58b52) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [504a0286fb](https://linux-hardware.org/?probe=504a0286fb) | Dec 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [4a2e796be8](https://linux-hardware.org/?probe=4a2e796be8) | Dec 04, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [89e97c7099](https://linux-hardware.org/?probe=89e97c7099) | Nov 29, 2022 |
| HP            | 250 G6 Notebook PC          | [95b1694080](https://linux-hardware.org/?probe=95b1694080) | Nov 28, 2022 |
| HP            | Pavilion Laptop 14-ce3xx... | [ccc431ef2e](https://linux-hardware.org/?probe=ccc431ef2e) | Nov 28, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | [028c06fcdc](https://linux-hardware.org/?probe=028c06fcdc) | Nov 27, 2022 |
| ASUSTek       | E402SA                      | [05983f8566](https://linux-hardware.org/?probe=05983f8566) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ab6ce548bc](https://linux-hardware.org/?probe=ab6ce548bc) | Nov 26, 2022 |
| Dell          | Latitude 5410               | [1eeb98c3b0](https://linux-hardware.org/?probe=1eeb98c3b0) | Nov 25, 2022 |
| Acer          | Aspire A315-54              | [b7269b7617](https://linux-hardware.org/?probe=b7269b7617) | Nov 24, 2022 |
| Dell          | Latitude 5410               | [a9b8b4208d](https://linux-hardware.org/?probe=a9b8b4208d) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | [0200afcfb3](https://linux-hardware.org/?probe=0200afcfb3) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | [077cd77583](https://linux-hardware.org/?probe=077cd77583) | Nov 24, 2022 |
| Samsung       | RF511/RF411/RF711           | [db9c9330b7](https://linux-hardware.org/?probe=db9c9330b7) | Nov 23, 2022 |
| ASUSTek       | PRIME Z690-P                | [436bd74a38](https://linux-hardware.org/?probe=436bd74a38) | Nov 22, 2022 |
| HP            | EliteBook 850 G2            | [dd13c1df3f](https://linux-hardware.org/?probe=dd13c1df3f) | Nov 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [6a4c697203](https://linux-hardware.org/?probe=6a4c697203) | Nov 15, 2022 |
| HP            | Compaq 6830s                | [074c3a8b43](https://linux-hardware.org/?probe=074c3a8b43) | Nov 14, 2022 |
| HP            | Notebook                    | [b0d1cd283f](https://linux-hardware.org/?probe=b0d1cd283f) | Nov 14, 2022 |
| HP            | Notebook                    | [95ecccf4c7](https://linux-hardware.org/?probe=95ecccf4c7) | Nov 14, 2022 |
| Lenovo        | G50-30 80G0                 | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HP            | 250 G6 Notebook PC          | [0d8609e1ed](https://linux-hardware.org/?probe=0d8609e1ed) | Nov 13, 2022 |
| Acer          | TravelMate 5730             | [cee6d10d17](https://linux-hardware.org/?probe=cee6d10d17) | Nov 13, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| MSI           | GP66 Leopard 11UG           | [0dab96ade2](https://linux-hardware.org/?probe=0dab96ade2) | Nov 06, 2022 |
| Acer          | Aspire 5520                 | [6e6b76588b](https://linux-hardware.org/?probe=6e6b76588b) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9af713ef6e](https://linux-hardware.org/?probe=9af713ef6e) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dae32fcba7](https://linux-hardware.org/?probe=dae32fcba7) | Nov 04, 2022 |
| Acer          | Predator G9-591             | [ca65bba88a](https://linux-hardware.org/?probe=ca65bba88a) | Nov 03, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| Dell          | Latitude E6330              | [51ded2feb1](https://linux-hardware.org/?probe=51ded2feb1) | Oct 31, 2022 |
| Packard Be... | EasyNote TE69KB             | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [cbdfd56f05](https://linux-hardware.org/?probe=cbdfd56f05) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [031a5998a5](https://linux-hardware.org/?probe=031a5998a5) | Oct 30, 2022 |
| HP            | ZBook 15                    | [b2d2352668](https://linux-hardware.org/?probe=b2d2352668) | Oct 25, 2022 |
| Lenovo        | ThinkPad T470 20HES21434    | [39ff1846e3](https://linux-hardware.org/?probe=39ff1846e3) | Oct 23, 2022 |
| Apple         | MacBookPro10,1              | [9380dfc8b7](https://linux-hardware.org/?probe=9380dfc8b7) | Oct 23, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [f81a40a71c](https://linux-hardware.org/?probe=f81a40a71c) | Oct 20, 2022 |
| Acer          | Aspire A315-33              | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [682dcf0b87](https://linux-hardware.org/?probe=682dcf0b87) | Oct 12, 2022 |
| Alienware     | 15 R3                       | [bfdbf12cbb](https://linux-hardware.org/?probe=bfdbf12cbb) | Oct 11, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [60b02deb7f](https://linux-hardware.org/?probe=60b02deb7f) | Oct 11, 2022 |
| Apple         | MacBookAir7,2               | [703ab6caa2](https://linux-hardware.org/?probe=703ab6caa2) | Oct 10, 2022 |
| Acer          | Aspire A315-33              | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | [29f7444a6e](https://linux-hardware.org/?probe=29f7444a6e) | Oct 10, 2022 |
| HUAWEI        | BOD-WXX9                    | [49fff6123f](https://linux-hardware.org/?probe=49fff6123f) | Oct 10, 2022 |
| Acer          | Aspire 5742G                | [0272592d8e](https://linux-hardware.org/?probe=0272592d8e) | Oct 08, 2022 |
| Acer          | Aspire 5520                 | [05e6a5cb26](https://linux-hardware.org/?probe=05e6a5cb26) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Google        | Banon                       | [269a819905](https://linux-hardware.org/?probe=269a819905) | Oct 03, 2022 |
| Alienware     | 15 R3                       | [28e4e84fb1](https://linux-hardware.org/?probe=28e4e84fb1) | Oct 02, 2022 |
| Dell          | Latitude 5480               | [ec9593f051](https://linux-hardware.org/?probe=ec9593f051) | Oct 01, 2022 |
| ASUSTek       | GL753VE                     | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [a64f339e70](https://linux-hardware.org/?probe=a64f339e70) | Sep 28, 2022 |
| HP            | EliteBook Revolve 810 G3    | [03ac8c5daa](https://linux-hardware.org/?probe=03ac8c5daa) | Sep 26, 2022 |
| HP            | EliteBook 840 G3            | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Dell          | Latitude E6420              | [e46ce42e90](https://linux-hardware.org/?probe=e46ce42e90) | Sep 20, 2022 |
| Acer          | Aspire E1-570G              | [2293724ae2](https://linux-hardware.org/?probe=2293724ae2) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| Acer          | Aspire E1-570G              | [09db514840](https://linux-hardware.org/?probe=09db514840) | Sep 19, 2022 |
| Valve         | Jupiter                     | [b2a1aea8e2](https://linux-hardware.org/?probe=b2a1aea8e2) | Sep 17, 2022 |
| HP            | EliteBook 8470p             | [337ccff161](https://linux-hardware.org/?probe=337ccff161) | Sep 15, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| Dell          | Inspiron 3543               | [bb1af3736f](https://linux-hardware.org/?probe=bb1af3736f) | Sep 10, 2022 |
| Dell          | Inspiron 3543               | [40ad505314](https://linux-hardware.org/?probe=40ad505314) | Sep 10, 2022 |
| Dell          | Latitude E6220              | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| HP            | ProBook 4730s               | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| Dell          | XPS 15 9500                 | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| HP            | Compaq 6735s                | [4e52bb6ecb](https://linux-hardware.org/?probe=4e52bb6ecb) | Aug 23, 2022 |
| HP            | EliteBook 820 G1            | [1231c2fabe](https://linux-hardware.org/?probe=1231c2fabe) | Aug 23, 2022 |
| Acer          | Enduro EUN314-51WG          | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| Alienware     | 15 R3                       | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [8834646a81](https://linux-hardware.org/?probe=8834646a81) | Aug 19, 2022 |
| Packard Be... | EasyNote TS11HR             | [9d82dca288](https://linux-hardware.org/?probe=9d82dca288) | Aug 17, 2022 |
| Packard Be... | EasyNote TE11BZ             | [2a8e801b4e](https://linux-hardware.org/?probe=2a8e801b4e) | Aug 16, 2022 |
| Packard Be... | EasyNote TE69KB             | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | X501A1                      | [d021969767](https://linux-hardware.org/?probe=d021969767) | Aug 15, 2022 |
| Acer          | Aspire VN7-571G             | [0d6dfdd6e0](https://linux-hardware.org/?probe=0d6dfdd6e0) | Aug 14, 2022 |
| HP            | Pavilion 15                 | [a5ef05aaff](https://linux-hardware.org/?probe=a5ef05aaff) | Aug 13, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| HP            | EliteBook 8460p             | [fe464db60d](https://linux-hardware.org/?probe=fe464db60d) | Aug 10, 2022 |
| HP            | EliteBook 840 G1            | [2539e9f908](https://linux-hardware.org/?probe=2539e9f908) | Aug 08, 2022 |
| Packard Be... | EasyNote LS11HR             | [0f1a9e4af2](https://linux-hardware.org/?probe=0f1a9e4af2) | Aug 06, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [fa0a089121](https://linux-hardware.org/?probe=fa0a089121) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a284074100](https://linux-hardware.org/?probe=a284074100) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| HP            | Laptop 14-dg0xxx            | [365fe3e266](https://linux-hardware.org/?probe=365fe3e266) | Aug 03, 2022 |
| HP            | ProBook 650 G1              | [da1731c1d2](https://linux-hardware.org/?probe=da1731c1d2) | Aug 03, 2022 |
| Packard Be... | EasyNote TE69KB             | [968a5f757f](https://linux-hardware.org/?probe=968a5f757f) | Aug 02, 2022 |
| HP            | EliteBook 840 G1            | [09cd376e43](https://linux-hardware.org/?probe=09cd376e43) | Aug 02, 2022 |
| HP            | Compaq 2510p                | [b61ccedd14](https://linux-hardware.org/?probe=b61ccedd14) | Jul 31, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| HP            | Laptop 14-dg0xxx            | [fa46d23eda](https://linux-hardware.org/?probe=fa46d23eda) | Jul 27, 2022 |
| HP            | ProBook 450 G3              | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| HP            | G62                         | [bc85466c3f](https://linux-hardware.org/?probe=bc85466c3f) | Jul 19, 2022 |
| HP            | ProBook 450 G3              | [96c65556bb](https://linux-hardware.org/?probe=96c65556bb) | Jul 18, 2022 |
| HP            | ProBook 650 G1              | [e540c6e30d](https://linux-hardware.org/?probe=e540c6e30d) | Jul 18, 2022 |
| Acer          | Aspire 5520                 | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [27f79db974](https://linux-hardware.org/?probe=27f79db974) | Jul 13, 2022 |
| MSI           | GF63 Thin 10SC              | [f4f2c80cdd](https://linux-hardware.org/?probe=f4f2c80cdd) | Jul 09, 2022 |
| HP            | EliteBook 840 G1            | [57517e2dc2](https://linux-hardware.org/?probe=57517e2dc2) | Jul 09, 2022 |
| Dell          | Precision 7560              | [3a5fc098c4](https://linux-hardware.org/?probe=3a5fc098c4) | Jul 08, 2022 |
| ASUSTek       | GL753VE                     | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| HUAWEI        | VLT-WX0                     | [9467db0d89](https://linux-hardware.org/?probe=9467db0d89) | Jul 06, 2022 |
| Acer          | Aspire R3-131T              | [f525b5f3b0](https://linux-hardware.org/?probe=f525b5f3b0) | Jul 04, 2022 |
| HP            | EliteBook 840 G1            | [9705c40e85](https://linux-hardware.org/?probe=9705c40e85) | Jul 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7004NM... | [716bd7e41f](https://linux-hardware.org/?probe=716bd7e41f) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [6904140540](https://linux-hardware.org/?probe=6904140540) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [abebd5c659](https://linux-hardware.org/?probe=abebd5c659) | Jun 30, 2022 |
| Dell          | XPS 13 9300                 | [8ecea7fce7](https://linux-hardware.org/?probe=8ecea7fce7) | Jun 28, 2022 |
| Lenovo        | ThinkPad T480 20L60034MX    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Dell          | Latitude E7440              | [41acc5e2ba](https://linux-hardware.org/?probe=41acc5e2ba) | Jun 17, 2022 |
| ASUSTek       | G752VSK                     | [16e086c77f](https://linux-hardware.org/?probe=16e086c77f) | Jun 16, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [d4bfcc2d6d](https://linux-hardware.org/?probe=d4bfcc2d6d) | Jun 12, 2022 |
| Dell          | Latitude E7440              | [d2861687ff](https://linux-hardware.org/?probe=d2861687ff) | Jun 12, 2022 |
| HP            | EliteBook 840 G6            | [f2351bb361](https://linux-hardware.org/?probe=f2351bb361) | Jun 11, 2022 |
| HP            | G62                         | [de2464c378](https://linux-hardware.org/?probe=de2464c378) | Jun 08, 2022 |
| ASUSTek       | GL753VE                     | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [4b11a98b62](https://linux-hardware.org/?probe=4b11a98b62) | May 31, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [6e41ef26bf](https://linux-hardware.org/?probe=6e41ef26bf) | May 29, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | [3a472b96d3](https://linux-hardware.org/?probe=3a472b96d3) | May 27, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | [7f3e3aada0](https://linux-hardware.org/?probe=7f3e3aada0) | May 27, 2022 |
| HP            | 255 G8 Notebook PC          | [9430147fab](https://linux-hardware.org/?probe=9430147fab) | May 27, 2022 |
| Dell          | Latitude 3520               | [6c5618416d](https://linux-hardware.org/?probe=6c5618416d) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | [018e2a8bff](https://linux-hardware.org/?probe=018e2a8bff) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | [6d4ab67cb8](https://linux-hardware.org/?probe=6d4ab67cb8) | May 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [7a1059d5cc](https://linux-hardware.org/?probe=7a1059d5cc) | May 25, 2022 |
| MSI           | GF75 Thin 9SC               | [49b7f895e9](https://linux-hardware.org/?probe=49b7f895e9) | May 24, 2022 |
| Lenovo        | V14-IIL 82C4                | [1ca9184b98](https://linux-hardware.org/?probe=1ca9184b98) | May 22, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [d52e9e2938](https://linux-hardware.org/?probe=d52e9e2938) | May 17, 2022 |
| HP            | EliteBook 820 G1            | [f06eee580b](https://linux-hardware.org/?probe=f06eee580b) | May 16, 2022 |
| Dell          | Latitude E6330              | [0065ab0681](https://linux-hardware.org/?probe=0065ab0681) | May 12, 2022 |
| Dell          | Latitude 7490               | [0069680215](https://linux-hardware.org/?probe=0069680215) | May 10, 2022 |
| Acer          | Aspire E1-571               | [65d7984ad4](https://linux-hardware.org/?probe=65d7984ad4) | May 09, 2022 |
| HP            | EliteBook 840 G2            | [df57c0ad60](https://linux-hardware.org/?probe=df57c0ad60) | May 09, 2022 |
| Lenovo        | G50-80 80E5                 | [8ecadc1bad](https://linux-hardware.org/?probe=8ecadc1bad) | May 05, 2022 |
| Lenovo        | Yoga 2 13 20344             | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [a90e6b2be7](https://linux-hardware.org/?probe=a90e6b2be7) | Apr 30, 2022 |
| Dell          | Latitude E6330              | [c78066bc19](https://linux-hardware.org/?probe=c78066bc19) | Apr 29, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | [31bc958302](https://linux-hardware.org/?probe=31bc958302) | Apr 26, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | [8446691cb3](https://linux-hardware.org/?probe=8446691cb3) | Apr 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| Lenovo        | ThinkPad X230 2324GA7       | [a5138b511d](https://linux-hardware.org/?probe=a5138b511d) | Apr 25, 2022 |
| HP            | Laptop 15-bw0xx             | [e83ffcb04f](https://linux-hardware.org/?probe=e83ffcb04f) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | [25e6181500](https://linux-hardware.org/?probe=25e6181500) | Apr 24, 2022 |
| MSI           | Stealth GS77 12UGS          | [cd1bc2095f](https://linux-hardware.org/?probe=cd1bc2095f) | Apr 22, 2022 |
| MSI           | Stealth GS77 12UGS          | [33afc70a54](https://linux-hardware.org/?probe=33afc70a54) | Apr 22, 2022 |
| Acer          | Aspire 7530G                | [710b429d94](https://linux-hardware.org/?probe=710b429d94) | Apr 21, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [5a93c8e68c](https://linux-hardware.org/?probe=5a93c8e68c) | Apr 14, 2022 |
| Lenovo        | ThinkPad T480 20L6S93F00    | [b8c57e6b8a](https://linux-hardware.org/?probe=b8c57e6b8a) | Apr 14, 2022 |
| HP            | Notebook                    | [24faf4835d](https://linux-hardware.org/?probe=24faf4835d) | Apr 10, 2022 |
| MSI           | GV62 8RD                    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [07efb6a561](https://linux-hardware.org/?probe=07efb6a561) | Apr 01, 2022 |
| Dell          | Latitude 5480               | [2d431aae25](https://linux-hardware.org/?probe=2d431aae25) | Mar 29, 2022 |
| Lenovo        | ThinkPad X230 2325BN8       | [3ad2d0f3ee](https://linux-hardware.org/?probe=3ad2d0f3ee) | Mar 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04T0P    | [d5b5eeffc8](https://linux-hardware.org/?probe=d5b5eeffc8) | Mar 25, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | [bf87e829d7](https://linux-hardware.org/?probe=bf87e829d7) | Mar 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [78ae0419a3](https://linux-hardware.org/?probe=78ae0419a3) | Mar 14, 2022 |
| Lenovo        | V145-15AST 81MT             | [ba2686174e](https://linux-hardware.org/?probe=ba2686174e) | Mar 13, 2022 |
| Acer          | AO725                       | [70febdd28f](https://linux-hardware.org/?probe=70febdd28f) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S1MN00    | [0f20b300ec](https://linux-hardware.org/?probe=0f20b300ec) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| HP            | G62                         | [67bc301ee6](https://linux-hardware.org/?probe=67bc301ee6) | Mar 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f351d9839b](https://linux-hardware.org/?probe=f351d9839b) | Mar 09, 2022 |
| ASUSTek       | G751JT                      | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| Lenovo        | ThinkPad 13 20GJ0048MS      | [6590a539cf](https://linux-hardware.org/?probe=6590a539cf) | Mar 02, 2022 |
| Fujitsu       | AMILO Pi 3560               | [ea68b8ed21](https://linux-hardware.org/?probe=ea68b8ed21) | Mar 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0278765ef8](https://linux-hardware.org/?probe=0278765ef8) | Feb 28, 2022 |
| Apple         | MacBook4,1                  | [c08be74242](https://linux-hardware.org/?probe=c08be74242) | Feb 27, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [02ac351573](https://linux-hardware.org/?probe=02ac351573) | Feb 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [fa5d4846df](https://linux-hardware.org/?probe=fa5d4846df) | Feb 23, 2022 |
| HP            | G62                         | [337afde8c1](https://linux-hardware.org/?probe=337afde8c1) | Feb 21, 2022 |
| HP            | G62                         | [a175af3dd6](https://linux-hardware.org/?probe=a175af3dd6) | Feb 21, 2022 |
| powerinter... | Cepter N510-03              | [cd6804144d](https://linux-hardware.org/?probe=cd6804144d) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Lenovo        | ThinkPad E14 20RA001LMX     | [19edff5659](https://linux-hardware.org/?probe=19edff5659) | Feb 17, 2022 |
| HP            | Compaq 6910p (GB951EA#AK... | [b136dd5def](https://linux-hardware.org/?probe=b136dd5def) | Feb 15, 2022 |
| Acer          | Aspire ES1-512              | [deb108070d](https://linux-hardware.org/?probe=deb108070d) | Feb 15, 2022 |
| ASUSTek       | T200TAC                     | [87db259935](https://linux-hardware.org/?probe=87db259935) | Feb 15, 2022 |
| Lenovo        | ThinkPad X230 23252SG       | [a5179b9681](https://linux-hardware.org/?probe=a5179b9681) | Feb 15, 2022 |
| HP            | 250 G5 Notebook PC          | [7cdffcccb7](https://linux-hardware.org/?probe=7cdffcccb7) | Feb 13, 2022 |
| Fujitsu       | LIFEBOOK E780               | [0ba38c6605](https://linux-hardware.org/?probe=0ba38c6605) | Feb 13, 2022 |
| Dell          | Latitude E5420              | [f016e9f3ad](https://linux-hardware.org/?probe=f016e9f3ad) | Feb 12, 2022 |
| Dell          | Latitude E5420              | [8843a735a0](https://linux-hardware.org/?probe=8843a735a0) | Feb 12, 2022 |
| Lenovo        | G50-80 80E5                 | [61e1bce7ae](https://linux-hardware.org/?probe=61e1bce7ae) | Feb 12, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [766e937263](https://linux-hardware.org/?probe=766e937263) | Feb 10, 2022 |
| Lenovo        | ThinkPad E590 20NB0012MX    | [92a33a8f31](https://linux-hardware.org/?probe=92a33a8f31) | Feb 10, 2022 |
| Lenovo        | G50-80 80E5                 | [72b880911a](https://linux-hardware.org/?probe=72b880911a) | Feb 08, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [e0765c9f5a](https://linux-hardware.org/?probe=e0765c9f5a) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [6160f71e77](https://linux-hardware.org/?probe=6160f71e77) | Feb 05, 2022 |
| ASUSTek       | UX303UB                     | [cba6a6b5a6](https://linux-hardware.org/?probe=cba6a6b5a6) | Feb 02, 2022 |
| Lenovo        | ThinkPad X390 20Q00057MX    | [326cb714f0](https://linux-hardware.org/?probe=326cb714f0) | Jan 27, 2022 |
| HP            | Compaq Presario CQ70        | [a31ae712c0](https://linux-hardware.org/?probe=a31ae712c0) | Jan 26, 2022 |
| HP            | Compaq Presario CQ70        | [82a45a6067](https://linux-hardware.org/?probe=82a45a6067) | Jan 26, 2022 |
| HP            | Compaq 6830s                | [f82216de53](https://linux-hardware.org/?probe=f82216de53) | Jan 26, 2022 |
| HP            | Compaq 6830s                | [fe7ef8a290](https://linux-hardware.org/?probe=fe7ef8a290) | Jan 26, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [7078a1a373](https://linux-hardware.org/?probe=7078a1a373) | Jan 25, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| ASUSTek       | S551LN                      | [f6beec1048](https://linux-hardware.org/?probe=f6beec1048) | Jan 18, 2022 |
| HP            | EliteBook 820 G1            | [39b90ab9c3](https://linux-hardware.org/?probe=39b90ab9c3) | Jan 17, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| Dell          | XPS 17 9710                 | [3417abe371](https://linux-hardware.org/?probe=3417abe371) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Dell          | XPS 17 9710                 | [3d2a67265f](https://linux-hardware.org/?probe=3d2a67265f) | Jan 15, 2022 |
| ASUSTek       | UL30A                       | [c2406eee73](https://linux-hardware.org/?probe=c2406eee73) | Jan 13, 2022 |
| HP            | Laptop 14-dk0xxx            | [4bbc688f9d](https://linux-hardware.org/?probe=4bbc688f9d) | Jan 13, 2022 |
| Toshiba       | Satellite P870              | [e046040d73](https://linux-hardware.org/?probe=e046040d73) | Jan 11, 2022 |
| HP            | Notebook                    | [0667124a5f](https://linux-hardware.org/?probe=0667124a5f) | Jan 10, 2022 |
| Sony          | VGN-FZ21Z                   | [6291085e58](https://linux-hardware.org/?probe=6291085e58) | Jan 09, 2022 |
| ASUSTek       | X553MA                      | [cdf5230fdb](https://linux-hardware.org/?probe=cdf5230fdb) | Jan 09, 2022 |
| Sony          | VGN-FZ21Z                   | [c4ac286105](https://linux-hardware.org/?probe=c4ac286105) | Jan 08, 2022 |
| HP            | ProBook 450 G3              | [1644301279](https://linux-hardware.org/?probe=1644301279) | Jan 07, 2022 |
| ASUSTek       | UL30A                       | [b2682cb5fe](https://linux-hardware.org/?probe=b2682cb5fe) | Jan 06, 2022 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | [e9170a81fe](https://linux-hardware.org/?probe=e9170a81fe) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 20RA001BMX     | [b34ccf2c06](https://linux-hardware.org/?probe=b34ccf2c06) | Jan 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [5dd20e2872](https://linux-hardware.org/?probe=5dd20e2872) | Jan 03, 2022 |
| Lenovo        | ThinkPad X61 7674CT0        | [25a59e69c1](https://linux-hardware.org/?probe=25a59e69c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | [a5b0d0a06a](https://linux-hardware.org/?probe=a5b0d0a06a) | Dec 25, 2021 |
| Acer          | Swift SF314-52              | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| MSI           | GE72 6QC                    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| HP            | EliteBook 2570p             | [462b93b05b](https://linux-hardware.org/?probe=462b93b05b) | Dec 20, 2021 |
| MSI           | GE72 6QC                    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| ASUSTek       | E200HA                      | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Dell          | Latitude 5490               | [a9261b4529](https://linux-hardware.org/?probe=a9261b4529) | Dec 16, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [81873c2912](https://linux-hardware.org/?probe=81873c2912) | Dec 14, 2021 |
| Dell          | Precision 7510              | [59a0d1a314](https://linux-hardware.org/?probe=59a0d1a314) | Dec 13, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| HP            | Pavilion 15                 | [9b61f8e080](https://linux-hardware.org/?probe=9b61f8e080) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Samsung       | 750XDA                      | [30d61197a1](https://linux-hardware.org/?probe=30d61197a1) | Dec 09, 2021 |
| HP            | 340 G5                      | [8ed2eec9b4](https://linux-hardware.org/?probe=8ed2eec9b4) | Dec 07, 2021 |
| Dell          | Latitude E6400              | [b8e56749b8](https://linux-hardware.org/?probe=b8e56749b8) | Dec 03, 2021 |
| Lenovo        | ThinkPad W540 20BH002NMS    | [52d66e95f4](https://linux-hardware.org/?probe=52d66e95f4) | Dec 01, 2021 |
| ASUSTek       | T100TA                      | [493153bf7c](https://linux-hardware.org/?probe=493153bf7c) | Nov 30, 2021 |
| ASUSTek       | T100TA                      | [b98f644a91](https://linux-hardware.org/?probe=b98f644a91) | Nov 30, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [9ae82b251b](https://linux-hardware.org/?probe=9ae82b251b) | Nov 26, 2021 |
| Apple         | MacBookAir6,2               | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| HP            | Laptop 15-bw0xx             | [9b0bfd9c19](https://linux-hardware.org/?probe=9b0bfd9c19) | Nov 24, 2021 |
| Lenovo        | B50-70 80EU                 | [9476bb5e05](https://linux-hardware.org/?probe=9476bb5e05) | Nov 24, 2021 |
| HP            | EliteBook 835 G7 Noteboo... | [cdf3297bef](https://linux-hardware.org/?probe=cdf3297bef) | Nov 21, 2021 |
| Google        | Relm                        | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| Dell          | Inspiron 1545               | [11710ca51d](https://linux-hardware.org/?probe=11710ca51d) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Dell          | Latitude E6420              | [2e2b68b190](https://linux-hardware.org/?probe=2e2b68b190) | Nov 20, 2021 |
| HP            | Pavilion 17                 | [a633bbd978](https://linux-hardware.org/?probe=a633bbd978) | Nov 20, 2021 |
| Acer          | Aspire A715-42G             | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| Lenovo        | ThinkPad T530 24341G0       | [0dcfa8bdc7](https://linux-hardware.org/?probe=0dcfa8bdc7) | Nov 17, 2021 |
| Dell          | Latitude 7420               | [52bd94ce90](https://linux-hardware.org/?probe=52bd94ce90) | Nov 17, 2021 |
| HP            | EliteBook 8560w             | [5bed28d52e](https://linux-hardware.org/?probe=5bed28d52e) | Nov 15, 2021 |
| HP            | ProBook 430 G1              | [da8846a5fd](https://linux-hardware.org/?probe=da8846a5fd) | Nov 14, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| ASUSTek       | N53SN                       | [438a1236fb](https://linux-hardware.org/?probe=438a1236fb) | Nov 11, 2021 |
| ASUSTek       | VivoBook E14 E402YA_R417... | [7a1824b26a](https://linux-hardware.org/?probe=7a1824b26a) | Nov 11, 2021 |
| Acer          | Nitro AN515-55              | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| ASUSTek       | G751JT                      | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [536b4200f8](https://linux-hardware.org/?probe=536b4200f8) | Nov 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [33a5ffbf9a](https://linux-hardware.org/?probe=33a5ffbf9a) | Nov 07, 2021 |
| Dell          | XPS 15 9510                 | [ae1af68eae](https://linux-hardware.org/?probe=ae1af68eae) | Nov 03, 2021 |
| Samsung       | R530/R730                   | [a62fb59972](https://linux-hardware.org/?probe=a62fb59972) | Nov 03, 2021 |
| ASUSTek       | G751JT                      | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| Packard Be... | EasyNote TS11HR             | [1217a94f61](https://linux-hardware.org/?probe=1217a94f61) | Oct 26, 2021 |
| ASUSTek       | 1001PX                      | [e74dc83f0a](https://linux-hardware.org/?probe=e74dc83f0a) | Oct 24, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| HP            | Compaq 6735s                | [25c73d7c4d](https://linux-hardware.org/?probe=25c73d7c4d) | Oct 20, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [594815bb9d](https://linux-hardware.org/?probe=594815bb9d) | Oct 17, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [d89008ef64](https://linux-hardware.org/?probe=d89008ef64) | Oct 16, 2021 |
| Acer          | Aspire 7530G                | [09694e2816](https://linux-hardware.org/?probe=09694e2816) | Oct 15, 2021 |
| HP            | ProBook 655 G1              | [5a67ea75fe](https://linux-hardware.org/?probe=5a67ea75fe) | Oct 14, 2021 |
| ASUSTek       | G751JT                      | [072dab3e8c](https://linux-hardware.org/?probe=072dab3e8c) | Oct 14, 2021 |
| Timi          | RedmiBook 13 R              | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | [cf747bee4e](https://linux-hardware.org/?probe=cf747bee4e) | Oct 13, 2021 |
| Lenovo        | Yoga 2 13 20344             | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| Dixonsxp      | Unknown                     | [a9d87f6d4e](https://linux-hardware.org/?probe=a9d87f6d4e) | Oct 08, 2021 |
| Lenovo        | ThinkPad T490 20N2000KGE    | [cb7f37874e](https://linux-hardware.org/?probe=cb7f37874e) | Oct 07, 2021 |
| Dixonsxp      | Unknown                     | [2fe4152b53](https://linux-hardware.org/?probe=2fe4152b53) | Oct 07, 2021 |
| Acer          | Swift SF314-54              | [26501031e8](https://linux-hardware.org/?probe=26501031e8) | Oct 07, 2021 |
| Lenovo        | G50-80 80E5                 | [31df81c76d](https://linux-hardware.org/?probe=31df81c76d) | Sep 30, 2021 |
| ASUSTek       | G751JT                      | [ba4f1bda7d](https://linux-hardware.org/?probe=ba4f1bda7d) | Sep 30, 2021 |
| Acer          | Aspire 5738                 | [171fc1cb46](https://linux-hardware.org/?probe=171fc1cb46) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | [f9373d8ba5](https://linux-hardware.org/?probe=f9373d8ba5) | Sep 27, 2021 |
| Toshiba       | Satellite C50-B             | [0914aeed54](https://linux-hardware.org/?probe=0914aeed54) | Sep 25, 2021 |
| Acer          | Aspire 5750G                | [89783ad217](https://linux-hardware.org/?probe=89783ad217) | Sep 24, 2021 |
| Acer          | Aspire 5750G                | [867138c338](https://linux-hardware.org/?probe=867138c338) | Sep 22, 2021 |
| Lenovo        | ThinkPad X230 204016Z1ZS    | [eb1d7abffc](https://linux-hardware.org/?probe=eb1d7abffc) | Sep 21, 2021 |
| HP            | EliteBook 2570p             | [a4488fd2fe](https://linux-hardware.org/?probe=a4488fd2fe) | Sep 19, 2021 |
| HP            | EliteBook 8540p             | [f9509414bc](https://linux-hardware.org/?probe=f9509414bc) | Sep 18, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [6b7410fa5c](https://linux-hardware.org/?probe=6b7410fa5c) | Sep 16, 2021 |
| Lenovo        | B50-10 80QR                 | [506a3682b9](https://linux-hardware.org/?probe=506a3682b9) | Sep 15, 2021 |
| Lenovo        | G50-80 80E5                 | [badf707f13](https://linux-hardware.org/?probe=badf707f13) | Sep 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e606ccc75f](https://linux-hardware.org/?probe=e606ccc75f) | Sep 14, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c8e465fcb0](https://linux-hardware.org/?probe=c8e465fcb0) | Sep 14, 2021 |
| HP            | Pavilion 11 x360 PC         | [6670bba1d8](https://linux-hardware.org/?probe=6670bba1d8) | Sep 13, 2021 |
| HP            | Pavilion 11 x360 PC         | [94e64b5b30](https://linux-hardware.org/?probe=94e64b5b30) | Sep 13, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [0a2430ae78](https://linux-hardware.org/?probe=0a2430ae78) | Sep 10, 2021 |
| Dell          | Latitude 7420               | [225b6a0d52](https://linux-hardware.org/?probe=225b6a0d52) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | [1dcfa059c1](https://linux-hardware.org/?probe=1dcfa059c1) | Sep 07, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | [d05cb87743](https://linux-hardware.org/?probe=d05cb87743) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [55f595b53f](https://linux-hardware.org/?probe=55f595b53f) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [00e399c8d4](https://linux-hardware.org/?probe=00e399c8d4) | Sep 07, 2021 |
| Dell          | Latitude E6430              | [e02c871576](https://linux-hardware.org/?probe=e02c871576) | Sep 06, 2021 |
| Dell          | Latitude E6430              | [5d2627b08e](https://linux-hardware.org/?probe=5d2627b08e) | Sep 06, 2021 |
| Fujitsu       | LIFEBOOK U9310              | [48113d6636](https://linux-hardware.org/?probe=48113d6636) | Sep 02, 2021 |
| Lenovo        | B50-10 80QR                 | [08ad3775b8](https://linux-hardware.org/?probe=08ad3775b8) | Aug 31, 2021 |
| Lenovo        | ThinkPad T420 4180WDN       | [8e46956f05](https://linux-hardware.org/?probe=8e46956f05) | Aug 31, 2021 |
| Acer          | Nitro AN517-52              | [d534aba928](https://linux-hardware.org/?probe=d534aba928) | Aug 31, 2021 |
| Lenovo        | ThinkPad T420 4180WDN       | [8512904445](https://linux-hardware.org/?probe=8512904445) | Aug 29, 2021 |
| HP            | EliteBook 2560p             | [93e2baa57a](https://linux-hardware.org/?probe=93e2baa57a) | Aug 29, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [f15a7392b9](https://linux-hardware.org/?probe=f15a7392b9) | Aug 27, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [cf76a62cf4](https://linux-hardware.org/?probe=cf76a62cf4) | Aug 26, 2021 |
| Fujitsu Si... | AMILO Li3910                | [4198aeb0a0](https://linux-hardware.org/?probe=4198aeb0a0) | Aug 26, 2021 |
| Dell          | Latitude 5480               | [3374e57369](https://linux-hardware.org/?probe=3374e57369) | Aug 25, 2021 |
| Acer          | Aspire SW5-012              | [fe8aa54fcd](https://linux-hardware.org/?probe=fe8aa54fcd) | Aug 25, 2021 |
| HP            | Compaq 8710w (GC124EA#AK... | [d7475c57ca](https://linux-hardware.org/?probe=d7475c57ca) | Aug 24, 2021 |
| HP            | ProBook 6360b               | [f8a9a512b2](https://linux-hardware.org/?probe=f8a9a512b2) | Aug 24, 2021 |
| HP            | ProBook 6360b               | [beb76e16b5](https://linux-hardware.org/?probe=beb76e16b5) | Aug 24, 2021 |
| Dell          | Vostro 5568                 | [bf921c6ff6](https://linux-hardware.org/?probe=bf921c6ff6) | Aug 23, 2021 |
| Dell          | Latitude 7490               | [b4759deb9a](https://linux-hardware.org/?probe=b4759deb9a) | Aug 21, 2021 |
| HP            | EliteBook 8560p             | [97a8f28916](https://linux-hardware.org/?probe=97a8f28916) | Aug 21, 2021 |
| HP            | 255 G1                      | [4998946adc](https://linux-hardware.org/?probe=4998946adc) | Aug 18, 2021 |
| Lenovo        | IdeaPad S145-14API 81UV     | [78377f3635](https://linux-hardware.org/?probe=78377f3635) | Aug 17, 2021 |
| Lenovo        | IdeaPad S145-14API 81UV     | [e91d03b0c4](https://linux-hardware.org/?probe=e91d03b0c4) | Aug 17, 2021 |
| Dell          | Latitude E6430              | [afe966ff62](https://linux-hardware.org/?probe=afe966ff62) | Aug 17, 2021 |
| Dell          | Latitude E6500              | [a707e64d52](https://linux-hardware.org/?probe=a707e64d52) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [8bf626f6b3](https://linux-hardware.org/?probe=8bf626f6b3) | Aug 15, 2021 |
| Dell          | XPS 15 7590                 | [b656e3aec4](https://linux-hardware.org/?probe=b656e3aec4) | Aug 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [11f9ccb3ad](https://linux-hardware.org/?probe=11f9ccb3ad) | Aug 13, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [8d464633db](https://linux-hardware.org/?probe=8d464633db) | Aug 08, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [bd3d1ed844](https://linux-hardware.org/?probe=bd3d1ed844) | Aug 08, 2021 |
| Lenovo        | ThinkPad X270 20HMS70400    | [6b647baf7c](https://linux-hardware.org/?probe=6b647baf7c) | Aug 07, 2021 |
| Lenovo        | ThinkPad T410 253725G       | [779374b300](https://linux-hardware.org/?probe=779374b300) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | [47fca1c82c](https://linux-hardware.org/?probe=47fca1c82c) | Aug 05, 2021 |
| ASUSTek       | 1001PX                      | [a5d694843c](https://linux-hardware.org/?probe=a5d694843c) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 2518A3G       | [0297e70b90](https://linux-hardware.org/?probe=0297e70b90) | Aug 04, 2021 |
| Lenovo        | ThinkPad T440p 20AN007FM... | [ba75506849](https://linux-hardware.org/?probe=ba75506849) | Aug 02, 2021 |
| Apple         | MacBookPro9,2               | [abb1e8ea82](https://linux-hardware.org/?probe=abb1e8ea82) | Jul 31, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| HP            | Pavilion 11 x360 PC         | [6e097e987f](https://linux-hardware.org/?probe=6e097e987f) | Jul 29, 2021 |
| Fujitsu       | LIFEBOOK A530               | [643094a68a](https://linux-hardware.org/?probe=643094a68a) | Jul 26, 2021 |
| Acer          | AO725                       | [4e27f519f7](https://linux-hardware.org/?probe=4e27f519f7) | Jul 25, 2021 |
| Sony          | VPCEH3D0E                   | [2d04f2e0e8](https://linux-hardware.org/?probe=2d04f2e0e8) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| ASUSTek       | G751JT                      | [2c81844355](https://linux-hardware.org/?probe=2c81844355) | Jul 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QTS0... | [550f9db7cd](https://linux-hardware.org/?probe=550f9db7cd) | Jul 22, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| MSI           | GS60 2PC Ghost              | [cf537038dd](https://linux-hardware.org/?probe=cf537038dd) | Jul 17, 2021 |
| Dell          | Latitude E7470              | [8c32d73d55](https://linux-hardware.org/?probe=8c32d73d55) | Jul 16, 2021 |
| Dell          | Latitude E7470              | [22583cadb6](https://linux-hardware.org/?probe=22583cadb6) | Jul 14, 2021 |
| ASUSTek       | G751JT                      | [532e266dcb](https://linux-hardware.org/?probe=532e266dcb) | Jul 13, 2021 |
| Acer          | Swift SF515-51T             | [f5ec156890](https://linux-hardware.org/?probe=f5ec156890) | Jul 12, 2021 |
| Samsung       | R530/R730                   | [103edb36d2](https://linux-hardware.org/?probe=103edb36d2) | Jul 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d52de582e8](https://linux-hardware.org/?probe=d52de582e8) | Jul 10, 2021 |
| HP            | ZBook 17 G5                 | [9f1b7a37f2](https://linux-hardware.org/?probe=9f1b7a37f2) | Jul 07, 2021 |
| Dell          | G7 7700                     | [6fc41408bf](https://linux-hardware.org/?probe=6fc41408bf) | Jul 07, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [def9f42f6c](https://linux-hardware.org/?probe=def9f42f6c) | Jul 02, 2021 |
| Apple         | MacBook4,1                  | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [cbb60edb8c](https://linux-hardware.org/?probe=cbb60edb8c) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [26a655c4b4](https://linux-hardware.org/?probe=26a655c4b4) | Jul 02, 2021 |
| Dell          | Precision 5540              | [a685a9c5bb](https://linux-hardware.org/?probe=a685a9c5bb) | Jun 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | [e2743844ad](https://linux-hardware.org/?probe=e2743844ad) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [39f8c7f885](https://linux-hardware.org/?probe=39f8c7f885) | Jun 26, 2021 |
| ASUSTek       | VivoBook E14 E402YA_R417... | [110b313bc0](https://linux-hardware.org/?probe=110b313bc0) | Jun 25, 2021 |
| Lenovo        | ThinkPad X220 42912XG       | [52199864f7](https://linux-hardware.org/?probe=52199864f7) | Jun 24, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [e966d318da](https://linux-hardware.org/?probe=e966d318da) | Jun 23, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [7767a1cde7](https://linux-hardware.org/?probe=7767a1cde7) | Jun 23, 2021 |
| Dell          | Precision 5550              | [646d84cc95](https://linux-hardware.org/?probe=646d84cc95) | Jun 23, 2021 |
| IBM           | ThinkPad T43 2668F7G        | [93c8e53b04](https://linux-hardware.org/?probe=93c8e53b04) | Jun 15, 2021 |
| Timi          | RedmiBook 13 R              | [ce648ba480](https://linux-hardware.org/?probe=ce648ba480) | Jun 12, 2021 |
| HP            | Compaq 8510p                | [c371bbdff4](https://linux-hardware.org/?probe=c371bbdff4) | Jun 09, 2021 |
| Dell          | XPS 13 7390                 | [54b62ad499](https://linux-hardware.org/?probe=54b62ad499) | Jun 08, 2021 |
| ASUSTek       | K53U                        | [3acb45024a](https://linux-hardware.org/?probe=3acb45024a) | Jun 08, 2021 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [3764e87d16](https://linux-hardware.org/?probe=3764e87d16) | Jun 07, 2021 |
| Dell          | Latitude E7470              | [6be76778ae](https://linux-hardware.org/?probe=6be76778ae) | Jun 03, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | V145-15AST 81MT             | [30e8995988](https://linux-hardware.org/?probe=30e8995988) | May 27, 2021 |
| HP            | Compaq 8510p                | [7e17cf2706](https://linux-hardware.org/?probe=7e17cf2706) | May 26, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [541b3e9cba](https://linux-hardware.org/?probe=541b3e9cba) | May 25, 2021 |
| Acer          | Aspire 8950G                | [d65fb86955](https://linux-hardware.org/?probe=d65fb86955) | May 22, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | [1b1a173884](https://linux-hardware.org/?probe=1b1a173884) | May 22, 2021 |
| HP            | 350 G1                      | [949ae1ce88](https://linux-hardware.org/?probe=949ae1ce88) | May 20, 2021 |
| Toshiba       | Satellite C660              | [60eb674c8f](https://linux-hardware.org/?probe=60eb674c8f) | May 19, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | [09351c4654](https://linux-hardware.org/?probe=09351c4654) | May 18, 2021 |
| Lenovo        | Yoga 2 13 20344             | [d75aff5a0a](https://linux-hardware.org/?probe=d75aff5a0a) | May 16, 2021 |
| Apple         | MacBookAir3,2               | [8b2100d9ad](https://linux-hardware.org/?probe=8b2100d9ad) | May 14, 2021 |
| HP            | EliteBook 2170p             | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| HP            | Pavilion g6                 | [ab2366fd14](https://linux-hardware.org/?probe=ab2366fd14) | May 11, 2021 |
| Dell          | Latitude 7400               | [a32714d409](https://linux-hardware.org/?probe=a32714d409) | May 05, 2021 |
| Dell          | Latitude 7400               | [eb8ca2d9d2](https://linux-hardware.org/?probe=eb8ca2d9d2) | May 05, 2021 |
| Dell          | Latitude E7270              | [6708f53385](https://linux-hardware.org/?probe=6708f53385) | May 04, 2021 |
| ASUSTek       | G751JT                      | [93eb4a6a39](https://linux-hardware.org/?probe=93eb4a6a39) | Apr 24, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [c586a3a771](https://linux-hardware.org/?probe=c586a3a771) | Apr 20, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [7e5ffea0b6](https://linux-hardware.org/?probe=7e5ffea0b6) | Apr 20, 2021 |
| Lenovo        | B70-80 80MR                 | [edef8dfd8b](https://linux-hardware.org/?probe=edef8dfd8b) | Apr 19, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [d01dac7a8f](https://linux-hardware.org/?probe=d01dac7a8f) | Apr 16, 2021 |
| Lenovo        | B50-45 80F0                 | [0558c9e99e](https://linux-hardware.org/?probe=0558c9e99e) | Apr 16, 2021 |
| ASUSTek       | G751JT                      | [7ca0cd3696](https://linux-hardware.org/?probe=7ca0cd3696) | Apr 15, 2021 |
| HP            | Compaq CQ58                 | [3274addf89](https://linux-hardware.org/?probe=3274addf89) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9776a806ac](https://linux-hardware.org/?probe=9776a806ac) | Apr 14, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [8a8adf8790](https://linux-hardware.org/?probe=8a8adf8790) | Apr 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [12fb9fd662](https://linux-hardware.org/?probe=12fb9fd662) | Apr 12, 2021 |
| MSI           | GL62M 7REX                  | [8ee2678b38](https://linux-hardware.org/?probe=8ee2678b38) | Apr 10, 2021 |
| ASUSTek       | X75VD                       | [258fbf86ed](https://linux-hardware.org/?probe=258fbf86ed) | Apr 09, 2021 |
| ASUSTek       | G751JT                      | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [c480530d42](https://linux-hardware.org/?probe=c480530d42) | Apr 07, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [ecae2e7ad8](https://linux-hardware.org/?probe=ecae2e7ad8) | Apr 06, 2021 |
| Samsung       | R530/R730                   | [0085bebd03](https://linux-hardware.org/?probe=0085bebd03) | Apr 05, 2021 |
| Lenovo        | B50-70 80EU                 | [6534232c53](https://linux-hardware.org/?probe=6534232c53) | Apr 04, 2021 |
| HP            | EliteBook 755 G2            | [12cd60c247](https://linux-hardware.org/?probe=12cd60c247) | Mar 31, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | [d8f1bccb78](https://linux-hardware.org/?probe=d8f1bccb78) | Mar 29, 2021 |
| Lenovo        | ThinkPad T430 2349UWT       | [d6edf7c2df](https://linux-hardware.org/?probe=d6edf7c2df) | Mar 28, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | [54845ca16f](https://linux-hardware.org/?probe=54845ca16f) | Mar 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | [1f11381bfb](https://linux-hardware.org/?probe=1f11381bfb) | Mar 27, 2021 |
| HP            | ZBook 15 G4                 | [4d3778017f](https://linux-hardware.org/?probe=4d3778017f) | Mar 25, 2021 |
| Samsung       | SF311/SF411/SF511           | [fb1261d331](https://linux-hardware.org/?probe=fb1261d331) | Mar 25, 2021 |
| Acer          | Aspire SW5-012              | [91409f3c71](https://linux-hardware.org/?probe=91409f3c71) | Mar 23, 2021 |
| Lenovo        | B50-45 80F0                 | [9af2b46c0a](https://linux-hardware.org/?probe=9af2b46c0a) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [50b82af935](https://linux-hardware.org/?probe=50b82af935) | Mar 18, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [3c98763834](https://linux-hardware.org/?probe=3c98763834) | Mar 17, 2021 |
| ASUSTek       | X541NA                      | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [ad7470fc89](https://linux-hardware.org/?probe=ad7470fc89) | Mar 15, 2021 |
| Acer          | Aspire SW5-012              | [2417d2d1b5](https://linux-hardware.org/?probe=2417d2d1b5) | Mar 14, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [c6866f0d34](https://linux-hardware.org/?probe=c6866f0d34) | Mar 10, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [112bdb4e2a](https://linux-hardware.org/?probe=112bdb4e2a) | Mar 09, 2021 |
| Lenovo        | ThinkPad T450 20BV001YMS    | [57449243ca](https://linux-hardware.org/?probe=57449243ca) | Mar 07, 2021 |
| Dell          | Inspiron 1564               | [c4548cb133](https://linux-hardware.org/?probe=c4548cb133) | Mar 04, 2021 |
| ASUSTek       | X551CAP                     | [857a1c6e52](https://linux-hardware.org/?probe=857a1c6e52) | Mar 04, 2021 |
| ASUSTek       | X551CAP                     | [3e423c7d87](https://linux-hardware.org/?probe=3e423c7d87) | Mar 03, 2021 |
| ASUSTek       | UX32A                       | [7debc0a27d](https://linux-hardware.org/?probe=7debc0a27d) | Mar 02, 2021 |
| Lenovo        | ThinkPad E580 20KS001RMX    | [5bcb97d47f](https://linux-hardware.org/?probe=5bcb97d47f) | Feb 28, 2021 |
| ASUSTek       | X551CAP                     | [987d795cb7](https://linux-hardware.org/?probe=987d795cb7) | Feb 27, 2021 |
| ASUSTek       | K54C                        | [467c86ad9a](https://linux-hardware.org/?probe=467c86ad9a) | Feb 26, 2021 |
| Dell          | Latitude E7470              | [93cf5a0e8b](https://linux-hardware.org/?probe=93cf5a0e8b) | Feb 26, 2021 |
| Acer          | Aspire A315-42              | [9a68092d87](https://linux-hardware.org/?probe=9a68092d87) | Feb 25, 2021 |
| ASUSTek       | K70IO                       | [49623c33e1](https://linux-hardware.org/?probe=49623c33e1) | Feb 25, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [5af628a455](https://linux-hardware.org/?probe=5af628a455) | Feb 25, 2021 |
| Lenovo        | ThinkPad T410 2518A3G       | [8a3e6146db](https://linux-hardware.org/?probe=8a3e6146db) | Feb 23, 2021 |
| Acer          | Swift SF315-52              | [50065d2efb](https://linux-hardware.org/?probe=50065d2efb) | Feb 20, 2021 |
| HP            | Presario CQ56               | [54f5681a51](https://linux-hardware.org/?probe=54f5681a51) | Feb 20, 2021 |
| HP            | EliteBook 745 G3            | [544e6bde0b](https://linux-hardware.org/?probe=544e6bde0b) | Feb 17, 2021 |
| Lenovo        | ThinkPad L490 20Q50020MX    | [24fb34852c](https://linux-hardware.org/?probe=24fb34852c) | Feb 16, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | [d91ab98cb0](https://linux-hardware.org/?probe=d91ab98cb0) | Feb 16, 2021 |
| Dell          | Vostro 5568                 | [33e13fb990](https://linux-hardware.org/?probe=33e13fb990) | Feb 14, 2021 |
| HP            | EliteBook 2560p             | [573a6ae3c7](https://linux-hardware.org/?probe=573a6ae3c7) | Feb 14, 2021 |
| HP            | EliteBook 6930p             | [2941ebcde6](https://linux-hardware.org/?probe=2941ebcde6) | Feb 13, 2021 |
| Fujitsu       | LIFEBOOK E744               | [21e0385b49](https://linux-hardware.org/?probe=21e0385b49) | Feb 13, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [d87dd2f698](https://linux-hardware.org/?probe=d87dd2f698) | Feb 12, 2021 |
| Dell          | Latitude E5470              | [562dbbdcdd](https://linux-hardware.org/?probe=562dbbdcdd) | Feb 07, 2021 |
| Acer          | TravelMate 5744             | [78690829c5](https://linux-hardware.org/?probe=78690829c5) | Feb 06, 2021 |
| HP            | Pavilion 11 x360 PC         | [8370d569ed](https://linux-hardware.org/?probe=8370d569ed) | Feb 06, 2021 |
| Dell          | Precision 3520              | [1e72fdbddc](https://linux-hardware.org/?probe=1e72fdbddc) | Feb 05, 2021 |
| Dell          | Precision 3520              | [fb3da7ea03](https://linux-hardware.org/?probe=fb3da7ea03) | Feb 04, 2021 |
| Samsung       | R530/R730                   | [9b9a4ce82c](https://linux-hardware.org/?probe=9b9a4ce82c) | Jan 31, 2021 |
| ASUSTek       | K73TA                       | [2b15e899ed](https://linux-hardware.org/?probe=2b15e899ed) | Jan 30, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [20789a4459](https://linux-hardware.org/?probe=20789a4459) | Jan 30, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [c0c66476fe](https://linux-hardware.org/?probe=c0c66476fe) | Jan 30, 2021 |
| ASUSTek       | K73TA                       | [0e4b16a1c5](https://linux-hardware.org/?probe=0e4b16a1c5) | Jan 30, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3d1daadbf9](https://linux-hardware.org/?probe=3d1daadbf9) | Jan 28, 2021 |
| HP            | ProBook 430 G1              | [bc43832b9f](https://linux-hardware.org/?probe=bc43832b9f) | Jan 27, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | [2d3b61aa15](https://linux-hardware.org/?probe=2d3b61aa15) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | [07c16b45cb](https://linux-hardware.org/?probe=07c16b45cb) | Jan 26, 2021 |
| Lenovo        | ThinkPad T430 2349W2P       | [58c2f66dd6](https://linux-hardware.org/?probe=58c2f66dd6) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| Acer          | Aspire SW5-012              | [0903507e18](https://linux-hardware.org/?probe=0903507e18) | Jan 25, 2021 |
| Acer          | Extensa 5220                | [5d121bc112](https://linux-hardware.org/?probe=5d121bc112) | Jan 25, 2021 |
| Dell          | Vostro 5568                 | [aaedd808e4](https://linux-hardware.org/?probe=aaedd808e4) | Jan 25, 2021 |
| Acer          | Nitro AN515-54              | [e6dcbd8319](https://linux-hardware.org/?probe=e6dcbd8319) | Jan 24, 2021 |
| Acer          | Nitro AN515-54              | [7718bb2939](https://linux-hardware.org/?probe=7718bb2939) | Jan 24, 2021 |
| Acer          | Extensa 5220                | [138ec8e43b](https://linux-hardware.org/?probe=138ec8e43b) | Jan 24, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [c50f23fd8b](https://linux-hardware.org/?probe=c50f23fd8b) | Jan 23, 2021 |
| ASUSTek       | X75VD                       | [6a6277a771](https://linux-hardware.org/?probe=6a6277a771) | Jan 22, 2021 |
| Dell          | Latitude 7400               | [0ecb2cacfe](https://linux-hardware.org/?probe=0ecb2cacfe) | Jan 22, 2021 |
| Dell          | XPS 13 9380                 | [40e24ed53c](https://linux-hardware.org/?probe=40e24ed53c) | Jan 21, 2021 |
| Lenovo        | G40-45 80E1                 | [40dbe0488c](https://linux-hardware.org/?probe=40dbe0488c) | Jan 21, 2021 |
| Lenovo        | ThinkPad L490 20Q50020MX    | [d442be2460](https://linux-hardware.org/?probe=d442be2460) | Jan 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [3d3987411f](https://linux-hardware.org/?probe=3d3987411f) | Jan 18, 2021 |
| HP            | Compaq 6735b                | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| HP            | EliteBook 1040 G4           | [b7ba6238f6](https://linux-hardware.org/?probe=b7ba6238f6) | Jan 17, 2021 |
| Fujitsu       | LIFEBOOK A530               | [5d2f2486eb](https://linux-hardware.org/?probe=5d2f2486eb) | Jan 17, 2021 |
| Lenovo        | ThinkPad T420 4236WUL       | [7fcf14c600](https://linux-hardware.org/?probe=7fcf14c600) | Jan 16, 2021 |
| Dell          | Latitude 5480               | [de414e3763](https://linux-hardware.org/?probe=de414e3763) | Jan 16, 2021 |
| Dell          | Vostro 5581                 | [b706435c71](https://linux-hardware.org/?probe=b706435c71) | Jan 15, 2021 |
| HP            | Compaq Presario CQ71        | [47744c734e](https://linux-hardware.org/?probe=47744c734e) | Jan 13, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| ASUSTek       | G751JT                      | [4b8c49c0dd](https://linux-hardware.org/?probe=4b8c49c0dd) | Jan 10, 2021 |
| ASUSTek       | E502SA                      | [f234ba69b3](https://linux-hardware.org/?probe=f234ba69b3) | Jan 09, 2021 |
| Dell          | Latitude 5410               | [dcbd8fa748](https://linux-hardware.org/?probe=dcbd8fa748) | Jan 09, 2021 |
| ASUSTek       | X75VD                       | [9dafe213ae](https://linux-hardware.org/?probe=9dafe213ae) | Jan 08, 2021 |
| Dell          | XPS 13 9380                 | [750bd00cb1](https://linux-hardware.org/?probe=750bd00cb1) | Jan 05, 2021 |
| ASUSTek       | G751JT                      | [ed6d998571](https://linux-hardware.org/?probe=ed6d998571) | Jan 04, 2021 |
| Dell          | XPS 15 9500                 | [48b31af6f7](https://linux-hardware.org/?probe=48b31af6f7) | Jan 04, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [f254fc1794](https://linux-hardware.org/?probe=f254fc1794) | Dec 31, 2020 |
| Lenovo        | ThinkPad W510 431924G       | [e5b63a5115](https://linux-hardware.org/?probe=e5b63a5115) | Dec 29, 2020 |
| HP            | EliteBook 8460p             | [7308662eff](https://linux-hardware.org/?probe=7308662eff) | Dec 28, 2020 |
| Dell          | Latitude 7390               | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| Dell          | Latitude E6540              | [f5a9ac4cec](https://linux-hardware.org/?probe=f5a9ac4cec) | Dec 27, 2020 |
| Apple         | MacBookAir5,2               | [7db2c6e8e1](https://linux-hardware.org/?probe=7db2c6e8e1) | Dec 27, 2020 |
| Apple         | MacBook10,1                 | [ab77e34c6e](https://linux-hardware.org/?probe=ab77e34c6e) | Dec 26, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY007... | [92e373f93e](https://linux-hardware.org/?probe=92e373f93e) | Dec 25, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [d3a90166ed](https://linux-hardware.org/?probe=d3a90166ed) | Dec 23, 2020 |
| Dell          | Latitude E6500              | [2745d38e45](https://linux-hardware.org/?probe=2745d38e45) | Dec 22, 2020 |
| Lenovo        | G505s 20255                 | [88c214adee](https://linux-hardware.org/?probe=88c214adee) | Dec 22, 2020 |
| HP            | EliteBook 8760w             | [36d7439921](https://linux-hardware.org/?probe=36d7439921) | Dec 20, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [21eff471d2](https://linux-hardware.org/?probe=21eff471d2) | Dec 19, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [864204221a](https://linux-hardware.org/?probe=864204221a) | Dec 18, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [48b96a1eb2](https://linux-hardware.org/?probe=48b96a1eb2) | Dec 18, 2020 |
| ASUSTek       | G751JT                      | [dc87c4f0ee](https://linux-hardware.org/?probe=dc87c4f0ee) | Dec 14, 2020 |
| Lenovo        | ThinkPad X301 4057W3A       | [ca140372c9](https://linux-hardware.org/?probe=ca140372c9) | Dec 13, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [7aea4d859f](https://linux-hardware.org/?probe=7aea4d859f) | Dec 12, 2020 |
| Apple         | MacBookAir3,2               | [da600a761d](https://linux-hardware.org/?probe=da600a761d) | Dec 10, 2020 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [37b50cd4d6](https://linux-hardware.org/?probe=37b50cd4d6) | Dec 09, 2020 |
| HP            | Pavilion dv2000 (RN081EA... | [efffe561da](https://linux-hardware.org/?probe=efffe561da) | Dec 07, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [0347053bb5](https://linux-hardware.org/?probe=0347053bb5) | Dec 06, 2020 |
| Unknown       | Unknown                     | [32c7f47910](https://linux-hardware.org/?probe=32c7f47910) | Dec 06, 2020 |
| ASUSTek       | E502SA                      | [8b9e3a522e](https://linux-hardware.org/?probe=8b9e3a522e) | Dec 05, 2020 |
| ASUSTek       | E502SA                      | [19ad2b41f0](https://linux-hardware.org/?probe=19ad2b41f0) | Dec 02, 2020 |
| ASUSTek       | E502SA                      | [5fcb11c8cc](https://linux-hardware.org/?probe=5fcb11c8cc) | Dec 02, 2020 |
| ASUSTek       | E502SA                      | [17a41f14d5](https://linux-hardware.org/?probe=17a41f14d5) | Dec 02, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [c60a02a67d](https://linux-hardware.org/?probe=c60a02a67d) | Dec 01, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [48c0620183](https://linux-hardware.org/?probe=48c0620183) | Dec 01, 2020 |
| Unknown       | Unknown                     | [d3ce335695](https://linux-hardware.org/?probe=d3ce335695) | Dec 01, 2020 |
| Dell          | Vostro 5568                 | [fdfdbf71f3](https://linux-hardware.org/?probe=fdfdbf71f3) | Nov 29, 2020 |
| HP            | 350 G2                      | [c36419b264](https://linux-hardware.org/?probe=c36419b264) | Nov 28, 2020 |
| HP            | 350 G2                      | [e075d2aae9](https://linux-hardware.org/?probe=e075d2aae9) | Nov 28, 2020 |
| Acer          | Aspire A315-42              | [cc791659ec](https://linux-hardware.org/?probe=cc791659ec) | Nov 25, 2020 |
| Dell          | XPS 15 9500                 | [97c1978e12](https://linux-hardware.org/?probe=97c1978e12) | Nov 24, 2020 |
| Dell          | XPS 15 9500                 | [3b0c917efa](https://linux-hardware.org/?probe=3b0c917efa) | Nov 24, 2020 |
| Acer          | Aspire A315-42              | [63ba982c79](https://linux-hardware.org/?probe=63ba982c79) | Nov 23, 2020 |
| Acer          | NG-VX5-591G-52AT            | [304a828df3](https://linux-hardware.org/?probe=304a828df3) | Nov 20, 2020 |
| Fujitsu       | LIFEBOOK A530               | [fcfb9d1f17](https://linux-hardware.org/?probe=fcfb9d1f17) | Nov 19, 2020 |
| Lenovo        | ThinkPad X250 20CM004VMS    | [c4b4e94df8](https://linux-hardware.org/?probe=c4b4e94df8) | Nov 18, 2020 |
| Lenovo        | ThinkPad X250 20CM004VMS    | [7b4d4bf272](https://linux-hardware.org/?probe=7b4d4bf272) | Nov 18, 2020 |
| Lenovo        | Yoga 2 13 20344             | [5d53e48607](https://linux-hardware.org/?probe=5d53e48607) | Nov 15, 2020 |
| Lenovo        | Yoga 2 13 20344             | [a3a3bd1c26](https://linux-hardware.org/?probe=a3a3bd1c26) | Nov 14, 2020 |
| Lenovo        | ThinkPad L490 20Q50020MX    | [4d72b1a3cc](https://linux-hardware.org/?probe=4d72b1a3cc) | Nov 13, 2020 |
| Lenovo        | G50-45 80E3                 | [1fe2eda7db](https://linux-hardware.org/?probe=1fe2eda7db) | Nov 11, 2020 |
| Lenovo        | ThinkPad L450 20DSS0VJ00    | [680974d12f](https://linux-hardware.org/?probe=680974d12f) | Nov 09, 2020 |
| ASUSTek       | E402NA                      | [22f631fe63](https://linux-hardware.org/?probe=22f631fe63) | Nov 08, 2020 |
| ASUSTek       | E402NA                      | [8f7f5ad515](https://linux-hardware.org/?probe=8f7f5ad515) | Nov 08, 2020 |
| Notebook      | P64_HJ,HK1                  | [9881503776](https://linux-hardware.org/?probe=9881503776) | Nov 07, 2020 |
| Lenovo        | ThinkPad X301 4057AL1       | [b52207277d](https://linux-hardware.org/?probe=b52207277d) | Nov 04, 2020 |
| Lenovo        | B50-30 80ES                 | [fd647f5ce9](https://linux-hardware.org/?probe=fd647f5ce9) | Nov 04, 2020 |
| Lenovo        | ThinkPad X60 1707YF8        | [bcdd451de1](https://linux-hardware.org/?probe=bcdd451de1) | Oct 31, 2020 |
| Lenovo        | ThinkPad T460s 20F9005CM... | [5e5eff0a90](https://linux-hardware.org/?probe=5e5eff0a90) | Oct 31, 2020 |
| Fujitsu       | LIFEBOOK A530               | [cd6162b529](https://linux-hardware.org/?probe=cd6162b529) | Oct 29, 2020 |
| Fujitsu       | LIFEBOOK A530               | [16ed8e04d9](https://linux-hardware.org/?probe=16ed8e04d9) | Oct 27, 2020 |
| HP            | Pavilion dv2000 (RN081EA... | [f5ad331463](https://linux-hardware.org/?probe=f5ad331463) | Oct 27, 2020 |
| Acer          | Aspire 5741G                | [cbea8a1179](https://linux-hardware.org/?probe=cbea8a1179) | Oct 26, 2020 |
| ASUSTek       | G751JT                      | [b3f953e40a](https://linux-hardware.org/?probe=b3f953e40a) | Oct 26, 2020 |
| Toshiba       | Satellite P50t-B-113        | [6c087ce8ea](https://linux-hardware.org/?probe=6c087ce8ea) | Oct 24, 2020 |
| Apple         | MacBookPro8,2               | [0d6f83e3ac](https://linux-hardware.org/?probe=0d6f83e3ac) | Oct 24, 2020 |
| Dell          | Latitude E6400              | [7716757d6d](https://linux-hardware.org/?probe=7716757d6d) | Oct 24, 2020 |
| Apple         | MacBookPro5,1               | [501b6aa7d4](https://linux-hardware.org/?probe=501b6aa7d4) | Oct 24, 2020 |
| Apple         | MacBookPro5,1               | [2b2e87b194](https://linux-hardware.org/?probe=2b2e87b194) | Oct 24, 2020 |
| Lenovo        | ThinkPad S5-S540 20B3005... | [cbdcb52cbd](https://linux-hardware.org/?probe=cbdcb52cbd) | Oct 23, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [6b9c08674b](https://linux-hardware.org/?probe=6b9c08674b) | Oct 23, 2020 |
| HP            | Notebook                    | [2609b2ee57](https://linux-hardware.org/?probe=2609b2ee57) | Oct 22, 2020 |
| HP            | Notebook                    | [a2dc7c3048](https://linux-hardware.org/?probe=a2dc7c3048) | Oct 22, 2020 |
| Lenovo        | ThinkPad E560 20EV0013MS    | [6a0824824b](https://linux-hardware.org/?probe=6a0824824b) | Oct 20, 2020 |
| ASUSTek       | G751JT                      | [5dcc1e72b6](https://linux-hardware.org/?probe=5dcc1e72b6) | Oct 20, 2020 |
| Lenovo        | ThinkPad W510 431967G       | [8471a7bc92](https://linux-hardware.org/?probe=8471a7bc92) | Oct 20, 2020 |
| ASUSTek       | X705UDR                     | [f2924b4bc4](https://linux-hardware.org/?probe=f2924b4bc4) | Oct 19, 2020 |
| Lenovo        | ThinkPad T420 4236WUL       | [fa50e94e7f](https://linux-hardware.org/?probe=fa50e94e7f) | Oct 18, 2020 |
| MSI           | GE66 Raider 10SF            | [ecadf6d10a](https://linux-hardware.org/?probe=ecadf6d10a) | Oct 15, 2020 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [c7d58d3075](https://linux-hardware.org/?probe=c7d58d3075) | Oct 14, 2020 |
| Samsung       | 400B4B/400B5B/200B4B/200... | [64e01927a8](https://linux-hardware.org/?probe=64e01927a8) | Oct 14, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Finland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 103       | 10.95%  |
| Ubuntu 18.04                 | 60        | 6.38%   |
| Ubuntu 22.04                 | 56        | 5.95%   |
| OpenMandriva 23.01           | 29        | 3.08%   |
| Debian 11                    | 25        | 2.66%   |
| Pop!_OS 22.04                | 21        | 2.23%   |
| Linux Mint 21.1              | 20        | 2.13%   |
| Ubuntu 21.04                 | 16        | 1.7%    |
| OpenMandriva 4.3             | 16        | 1.7%    |
| OpenMandriva 4.2             | 14        | 1.49%   |
| Fedora 39                    | 14        | 1.49%   |
| EndeavourOS Rolling          | 14        | 1.49%   |
| Arch Rolling                 | 14        | 1.49%   |
| OpenMandriva 23.03           | 13        | 1.38%   |
| Manjaro                      | 13        | 1.38%   |
| Linux Mint 20                | 13        | 1.38%   |
| Fedora 38                    | 12        | 1.28%   |
| Arch                         | 12        | 1.28%   |
| Linux Mint 20.2              | 11        | 1.17%   |
| Linux Mint 19.3              | 11        | 1.17%   |
| Fedora 33                    | 11        | 1.17%   |
| ArcoLinux Rolling            | 11        | 1.17%   |
| Zorin 16                     | 10        | 1.06%   |
| Xubuntu 20.04                | 10        | 1.06%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 1.06%   |
| Fedora 34                    | 10        | 1.06%   |
| Ubuntu 21.10                 | 9         | 0.96%   |
| Pop!_OS 21.04                | 9         | 0.96%   |
| Fedora 37                    | 9         | 0.96%   |
| Debian 12                    | 9         | 0.96%   |
| Ubuntu 20.10                 | 8         | 0.85%   |
| Linux Mint 20.1              | 8         | 0.85%   |
| Fedora 32                    | 8         | 0.85%   |
| Ubuntu 19.10                 | 7         | 0.74%   |
| Pop!_OS 21.10                | 7         | 0.74%   |
| Pop!_OS 20.04                | 7         | 0.74%   |
| Linux Mint 21.2              | 7         | 0.74%   |
| Linux Mint 20.3              | 7         | 0.74%   |
| Fedora 36                    | 7         | 0.74%   |
| Fedora 35                    | 7         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 272       | 30.77%  |
| OpenMandriva     | 81        | 9.16%   |
| Linux Mint       | 81        | 9.16%   |
| Fedora           | 78        | 8.82%   |
| Pop!_OS          | 46        | 5.2%    |
| Debian           | 45        | 5.09%   |
| Manjaro          | 28        | 3.17%   |
| Arch             | 26        | 2.94%   |
| Xubuntu          | 23        | 2.6%    |
| Kubuntu          | 18        | 2.04%   |
| Zorin            | 16        | 1.81%   |
| EndeavourOS      | 16        | 1.81%   |
| ROSA             | 15        | 1.7%    |
| openSUSE         | 13        | 1.47%   |
| Ubuntu MATE      | 11        | 1.24%   |
| ArcoLinux        | 11        | 1.24%   |
| Kali             | 10        | 1.13%   |
| Lubuntu          | 8         | 0.9%    |
| KDE neon         | 8         | 0.9%    |
| Gentoo           | 8         | 0.9%    |
| SteamOS          | 5         | 0.57%   |
| Elementary       | 5         | 0.57%   |
| Ubuntu Budgie    | 4         | 0.45%   |
| MX               | 4         | 0.45%   |
| Endless          | 4         | 0.45%   |
| Parrot           | 3         | 0.34%   |
| LMDE             | 3         | 0.34%   |
| Garuda Linux     | 3         | 0.34%   |
| Devuan           | 3         | 0.34%   |
| CentOS           | 3         | 0.34%   |
| BlackPanther     | 3         | 0.34%   |
| Ubuntu Unity     | 2         | 0.23%   |
| Solus            | 2         | 0.23%   |
| RHEL             | 2         | 0.23%   |
| Peppermint       | 2         | 0.23%   |
| org.kde.Platform | 2         | 0.23%   |
| Nobara           | 2         | 0.23%   |
| Lilidog          | 2         | 0.23%   |
| Clear Linux      | 2         | 0.23%   |
| Xero             | 1         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.1.1-desktop-1omv2290   | 28        | 2.7%    |
| 5.4.0-42-generic         | 20        | 1.93%   |
| 5.4.0-58-generic         | 13        | 1.25%   |
| 5.16.7-desktop-1omv4003  | 13        | 1.25%   |
| 5.10.14-desktop-1omv4002 | 13        | 1.25%   |
| 6.2.6-desktop-1omv2390   | 12        | 1.16%   |
| 5.4.0-48-generic         | 10        | 0.96%   |
| 5.3.0-40-generic         | 8         | 0.77%   |
| 5.4.0-47-generic         | 7         | 0.67%   |
| 5.15.0-58-generic        | 7         | 0.67%   |
| 5.11.0-7620-generic      | 7         | 0.67%   |
| 6.5.0-14-generic         | 6         | 0.58%   |
| 6.4.11-desktop-1omv2390  | 6         | 0.58%   |
| 6.2.0-39-generic         | 6         | 0.58%   |
| 6.2.0-26-generic         | 6         | 0.58%   |
| 6.2.0-20-generic         | 6         | 0.58%   |
| 5.4.0-52-generic         | 6         | 0.58%   |
| 5.3.0-42-generic         | 6         | 0.58%   |
| 5.15.0-91-generic        | 6         | 0.58%   |
| 5.15.0-71-generic        | 6         | 0.58%   |
| 5.15.0-52-generic        | 6         | 0.58%   |
| 5.11.0-41-generic        | 6         | 0.58%   |
| 6.5.0-26-generic         | 5         | 0.48%   |
| 6.5.0-15-generic         | 5         | 0.48%   |
| 6.2.0-32-generic         | 5         | 0.48%   |
| 5.15.0-67-generic        | 5         | 0.48%   |
| 5.15.0-48-generic        | 5         | 0.48%   |
| 5.13.0-22-generic        | 5         | 0.48%   |
| 5.10.0-21-amd64          | 5         | 0.48%   |
| 6.6.2-desktop-1omv2390   | 4         | 0.39%   |
| 6.2.0-37-generic         | 4         | 0.39%   |
| 6.1.0-13-amd64           | 4         | 0.39%   |
| 5.8.0-50-generic         | 4         | 0.39%   |
| 5.8.0-44-generic         | 4         | 0.39%   |
| 5.8.0-41-generic         | 4         | 0.39%   |
| 5.4.0-92-generic         | 4         | 0.39%   |
| 5.4.0-81-generic         | 4         | 0.39%   |
| 5.4.0-7634-generic       | 4         | 0.39%   |
| 5.4.0-56-generic         | 4         | 0.39%   |
| 5.4.0-45-generic         | 4         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 133       | 13.61%  |
| 5.15.0  | 81        | 8.29%   |
| 5.11.0  | 44        | 4.5%    |
| 4.15.0  | 43        | 4.4%    |
| 5.8.0   | 39        | 3.99%   |
| 5.3.0   | 35        | 3.58%   |
| 6.2.0   | 34        | 3.48%   |
| 6.5.0   | 31        | 3.17%   |
| 5.10.0  | 30        | 3.07%   |
| 6.1.1   | 29        | 2.97%   |
| 5.13.0  | 24        | 2.46%   |
| 5.19.0  | 21        | 2.15%   |
| 6.2.6   | 15        | 1.54%   |
| 5.0.0   | 15        | 1.54%   |
| 5.16.7  | 13        | 1.33%   |
| 5.10.14 | 13        | 1.33%   |
| 6.1.0   | 11        | 1.13%   |
| 4.18.0  | 10        | 1.02%   |
| 4.19.0  | 8         | 0.82%   |
| 6.4.11  | 7         | 0.72%   |
| 6.0.0   | 5         | 0.51%   |
| 5.16.13 | 5         | 0.51%   |
| 5.14.0  | 5         | 0.51%   |
| 6.8.0   | 4         | 0.41%   |
| 6.6.2   | 4         | 0.41%   |
| 6.5.6   | 4         | 0.41%   |
| 6.0.8   | 4         | 0.41%   |
| 5.17.5  | 4         | 0.41%   |
| 5.15.15 | 4         | 0.41%   |
| 4.18.16 | 4         | 0.41%   |
| 6.7.3   | 3         | 0.31%   |
| 6.6.10  | 3         | 0.31%   |
| 6.5.4   | 3         | 0.31%   |
| 6.5.12  | 3         | 0.31%   |
| 6.3.1   | 3         | 0.31%   |
| 6.2.9   | 3         | 0.31%   |
| 6.1.7   | 3         | 0.31%   |
| 6.0.5   | 3         | 0.31%   |
| 5.9.11  | 3         | 0.31%   |
| 5.9.0   | 3         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 143       | 14.9%   |
| 5.15    | 109       | 11.35%  |
| 5.10    | 63        | 6.56%   |
| 6.2     | 58        | 6.04%   |
| 6.1     | 58        | 6.04%   |
| 5.11    | 54        | 5.63%   |
| 5.8     | 51        | 5.31%   |
| 6.5     | 49        | 5.1%    |
| 4.15    | 43        | 4.48%   |
| 5.3     | 40        | 4.17%   |
| 5.13    | 33        | 3.44%   |
| 5.19    | 30        | 3.13%   |
| 5.16    | 29        | 3.02%   |
| 6.0     | 19        | 1.98%   |
| 6.6     | 15        | 1.56%   |
| 6.4     | 15        | 1.56%   |
| 5.0     | 15        | 1.56%   |
| 4.18    | 14        | 1.46%   |
| 5.14    | 13        | 1.35%   |
| 5.17    | 11        | 1.15%   |
| 4.19    | 10        | 1.04%   |
| 6.7     | 9         | 0.94%   |
| 6.3     | 9         | 0.94%   |
| 5.12    | 9         | 0.94%   |
| 6.8     | 8         | 0.83%   |
| 5.9     | 8         | 0.83%   |
| 5.7     | 7         | 0.73%   |
| 5.5     | 7         | 0.73%   |
| 4.9     | 7         | 0.73%   |
| 5.18    | 6         | 0.63%   |
| 5.6     | 5         | 0.52%   |
| 5.2     | 2         | 0.21%   |
| 4.4     | 2         | 0.21%   |
| 4.1     | 2         | 0.21%   |
| 3.10    | 2         | 0.21%   |
| 5.1     | 1         | 0.1%    |
| 4.17    | 1         | 0.1%    |
| 4.14    | 1         | 0.1%    |
| 4.13    | 1         | 0.1%    |
| 4.10    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 834       | 97.2%   |
| i686   | 24        | 2.8%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 395       | 44.43%  |
| KDE5             | 179       | 20.13%  |
| Unknown          | 76        | 8.55%   |
| XFCE             | 71        | 7.99%   |
| X-Cinnamon       | 56        | 6.3%    |
| MATE             | 21        | 2.36%   |
| i3               | 10        | 1.12%   |
| Cinnamon         | 10        | 1.12%   |
| LXQt             | 9         | 1.01%   |
| KDE4             | 9         | 1.01%   |
| GNOME Flashback  | 9         | 1.01%   |
| LXDE             | 6         | 0.67%   |
| KDE              | 6         | 0.67%   |
| Budgie           | 6         | 0.67%   |
| Pantheon         | 5         | 0.56%   |
| lightdm-xsession | 4         | 0.45%   |
| Unity            | 2         | 0.22%   |
| openbox          | 2         | 0.22%   |
| LeftWM           | 2         | 0.22%   |
| Hyprland         | 2         | 0.22%   |
| xubuntu          | 1         | 0.11%   |
| xmonad           | 1         | 0.11%   |
| sway             | 1         | 0.11%   |
| KDE6             | 1         | 0.11%   |
| Enlightenment    | 1         | 0.11%   |
| DWM              | 1         | 0.11%   |
| Deepin           | 1         | 0.11%   |
| BunsenLabs       | 1         | 0.11%   |
| bspwm            | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 628       | 70.88%  |
| Wayland | 206       | 23.25%  |
| Unknown | 40        | 4.51%   |
| Tty     | 12        | 1.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 373       | 41.82%  |
| SDDM          | 157       | 17.6%   |
| GDM           | 121       | 13.57%  |
| LightDM       | 99        | 11.1%   |
| GDM3          | 96        | 10.76%  |
| TDM           | 33        | 3.7%    |
| KDM           | 9         | 1.01%   |
| XDM           | 1         | 0.11%   |
| Ly            | 1         | 0.11%   |
| LXDM          | 1         | 0.11%   |
| DARKDM_ON_TTY | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 391       | 44.74%  |
| fi_FI       | 279       | 31.92%  |
| Unknown     | 72        | 8.24%   |
| en_GB       | 66        | 7.55%   |
| ru_RU       | 17        | 1.95%   |
| C           | 16        | 1.83%   |
| et_EE       | 4         | 0.46%   |
| fr_FR       | 3         | 0.34%   |
| en_DK       | 3         | 0.34%   |
| en_AG       | 3         | 0.34%   |
| zh_CN       | 2         | 0.23%   |
| sv_FI       | 2         | 0.23%   |
| POSIX       | 2         | 0.23%   |
| pl_PL       | 2         | 0.23%   |
| en_FI       | 2         | 0.23%   |
| UTF-8       | 1         | 0.11%   |
| ja_JP       | 1         | 0.11%   |
| it_IT       | 1         | 0.11%   |
| is_IS       | 1         | 0.11%   |
| hu_HU       | 1         | 0.11%   |
| en_US.utf-8 | 1         | 0.11%   |
| en_NG       | 1         | 0.11%   |
| en_IE       | 1         | 0.11%   |
| de_DE       | 1         | 0.11%   |
| C.UTF8      | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 447       | 51.32%  |
| BIOS | 424       | 48.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 621       | 70.25%  |
| Btrfs   | 110       | 12.44%  |
| Overlay | 72        | 8.14%   |
| Tmpfs   | 41        | 4.64%   |
| Unknown | 19        | 2.15%   |
| Xfs     | 10        | 1.13%   |
| Zfs     | 7         | 0.79%   |
| Ext2    | 3         | 0.34%   |
| Ext3    | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 382       | 43.71%  |
| GPT     | 379       | 43.36%  |
| MBR     | 113       | 12.93%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 783       | 89.69%  |
| Yes       | 90        | 10.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 684       | 79.17%  |
| Yes       | 180       | 20.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 269       | 31.35%  |
| Hewlett-Packard     | 182       | 21.21%  |
| ASUSTek Computer    | 108       | 12.59%  |
| Dell                | 87        | 10.14%  |
| Acer                | 61        | 7.11%   |
| Fujitsu             | 26        | 3.03%   |
| Apple               | 26        | 3.03%   |
| Samsung Electronics | 20        | 2.33%   |
| MSI                 | 13        | 1.52%   |
| Fujitsu Siemens     | 12        | 1.4%    |
| Toshiba             | 9         | 1.05%   |
| Valve               | 5         | 0.58%   |
| HUAWEI              | 5         | 0.58%   |
| Sony                | 4         | 0.47%   |
| Packard Bell        | 4         | 0.47%   |
| Google              | 3         | 0.35%   |
| Unknown             | 3         | 0.35%   |
| Timi                | 2         | 0.23%   |
| Notebook            | 2         | 0.23%   |
| TUXEDO              | 1         | 0.12%   |
| TrekStor            | 1         | 0.12%   |
| Seco                | 1         | 0.12%   |
| Schenker            | 1         | 0.12%   |
| powerinternational  | 1         | 0.12%   |
| Panasonic           | 1         | 0.12%   |
| Motion Computing    | 1         | 0.12%   |
| Intel               | 1         | 0.12%   |
| IBM                 | 1         | 0.12%   |
| HONOR               | 1         | 0.12%   |
| Gigabyte Technology | 1         | 0.12%   |
| Framework           | 1         | 0.12%   |
| eMachines           | 1         | 0.12%   |
| Dixonsxp            | 1         | 0.12%   |
| Chuwi               | 1         | 0.12%   |
| Bluechip Computer   | 1         | 0.12%   |
| Alienware           | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 7         | 0.82%   |
| HP EliteBook 840 G3                    | 6         | 0.7%    |
| Valve Jupiter                          | 4         | 0.47%   |
| Lenovo Yoga Slim 7 14ARE05 82A2        | 4         | 0.47%   |
| Lenovo V145-15AST 81MT                 | 4         | 0.47%   |
| Lenovo ThinkPad T420 4180PBG           | 4         | 0.47%   |
| HP EliteBook 8460p                     | 4         | 0.47%   |
| HP EliteBook 840 G6                    | 4         | 0.47%   |
| HP EliteBook 840 G1                    | 4         | 0.47%   |
| HP EliteBook 2560p                     | 4         | 0.47%   |
| Fujitsu LIFEBOOK A530                  | 4         | 0.47%   |
| ASUS TUF Gaming FX505DT_FX505DT        | 4         | 0.47%   |
| Samsung R530/R730                      | 3         | 0.35%   |
| Samsung 300E4A/300E5A/300E7A           | 3         | 0.35%   |
| Lenovo ThinkPad T480 20L5000BMX        | 3         | 0.35%   |
| Lenovo ThinkPad P14s Gen 2a 21A00004MX | 3         | 0.35%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY   | 3         | 0.35%   |
| Lenovo G50-30 80G0                     | 3         | 0.35%   |
| HP ZBook 15 G4                         | 3         | 0.35%   |
| HP ProBook 650 G1                      | 3         | 0.35%   |
| HP Pavilion dv6                        | 3         | 0.35%   |
| HP Pavilion 17                         | 3         | 0.35%   |
| HP Pavilion 15                         | 3         | 0.35%   |
| HP EliteBook 840 G7 Notebook PC        | 3         | 0.35%   |
| HP EliteBook 820 G1                    | 3         | 0.35%   |
| Fujitsu Siemens ESPRIMO Mobile D9500   | 3         | 0.35%   |
| Dell XPS 13 9380                       | 3         | 0.35%   |
| Dell Precision M4700                   | 3         | 0.35%   |
| Dell Latitude E7440                    | 3         | 0.35%   |
| Dell Latitude E6430                    | 3         | 0.35%   |
| Dell Latitude E5470                    | 3         | 0.35%   |
| Dell Latitude 7490                     | 3         | 0.35%   |
| ASUS E402NA                            | 3         | 0.35%   |
| Apple MacBookPro8,2                    | 3         | 0.35%   |
| Acer Aspire 5741G                      | 3         | 0.35%   |
| Toshiba Satellite C660                 | 2         | 0.23%   |
| Samsung R610                           | 2         | 0.23%   |
| Samsung 355V4C/356V4C/3445VC/3545VC    | 2         | 0.23%   |
| Lenovo Yoga 2 Pro 20266                | 2         | 0.23%   |
| Lenovo Yoga 2 13 20344                 | 2         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 190       | 22.14%  |
| HP EliteBook            | 64        | 7.46%   |
| Dell Latitude           | 48        | 5.59%   |
| Acer Aspire             | 41        | 4.78%   |
| HP Pavilion             | 34        | 3.96%   |
| Lenovo IdeaPad          | 28        | 3.26%   |
| Fujitsu LIFEBOOK        | 25        | 2.91%   |
| HP ProBook              | 17        | 1.98%   |
| HP Compaq               | 16        | 1.86%   |
| Dell XPS                | 16        | 1.86%   |
| ASUS VivoBook           | 15        | 1.75%   |
| HP Laptop               | 14        | 1.63%   |
| Dell Precision          | 12        | 1.4%    |
| Lenovo Yoga             | 11        | 1.28%   |
| HP ZBook                | 9         | 1.05%   |
| Toshiba Satellite       | 8         | 0.93%   |
| Lenovo Legion           | 8         | 0.93%   |
| ASUS TUF                | 8         | 0.93%   |
| Dell Inspiron           | 7         | 0.82%   |
| ASUS ASUS               | 7         | 0.82%   |
| Unknown                 | 7         | 0.82%   |
| Fujitsu Siemens ESPRIMO | 6         | 0.7%    |
| ASUS ZenBook            | 6         | 0.7%    |
| ASUS ROG                | 6         | 0.7%    |
| Acer Swift              | 6         | 0.7%    |
| Fujitsu Siemens AMILO   | 5         | 0.58%   |
| Valve Jupiter           | 4         | 0.47%   |
| Samsung 300E4A          | 4         | 0.47%   |
| Packard Bell EasyNote   | 4         | 0.47%   |
| Lenovo V145-15AST       | 4         | 0.47%   |
| HP 255                  | 4         | 0.47%   |
| HP 250                  | 4         | 0.47%   |
| Apple MacBookPro8       | 4         | 0.47%   |
| Samsung R530            | 3         | 0.35%   |
| Lenovo G50-30           | 3         | 0.35%   |
| Dell Vostro             | 3         | 0.35%   |
| ASUS E402NA             | 3         | 0.35%   |
| Acer Nitro              | 3         | 0.35%   |
| Samsung R610            | 2         | 0.23%   |
| Samsung 355V4C          | 2         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 82        | 9.56%   |
| 2011 | 76        | 8.86%   |
| 2018 | 67        | 7.81%   |
| 2013 | 66        | 7.69%   |
| 2012 | 65        | 7.58%   |
| 2014 | 62        | 7.23%   |
| 2017 | 58        | 6.76%   |
| 2020 | 57        | 6.64%   |
| 2008 | 53        | 6.18%   |
| 2021 | 51        | 5.94%   |
| 2015 | 50        | 5.83%   |
| 2016 | 42        | 4.9%    |
| 2010 | 34        | 3.96%   |
| 2007 | 24        | 2.8%    |
| 2009 | 23        | 2.68%   |
| 2022 | 21        | 2.45%   |
| 2023 | 15        | 1.75%   |
| 2006 | 8         | 0.93%   |
| 2005 | 3         | 0.35%   |
| 2024 | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 858       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 782       | 90.3%   |
| Enabled  | 84        | 9.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 854       | 99.53%  |
| Yes  | 4         | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 273       | 31.34%  |
| 3.01-4.0    | 187       | 21.47%  |
| 16.01-24.0  | 139       | 15.96%  |
| 8.01-16.0   | 136       | 15.61%  |
| 32.01-64.0  | 63        | 7.23%   |
| 1.01-2.0    | 31        | 3.56%   |
| 2.01-3.0    | 15        | 1.72%   |
| 24.01-32.0  | 12        | 1.38%   |
| 0.51-1.0    | 8         | 0.92%   |
| 64.01-256.0 | 7         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 361       | 38.28%  |
| 2.01-3.0   | 225       | 23.86%  |
| 4.01-8.0   | 124       | 13.15%  |
| 3.01-4.0   | 112       | 11.88%  |
| 0.51-1.0   | 70        | 7.42%   |
| 8.01-16.0  | 34        | 3.61%   |
| 0.01-0.5   | 10        | 1.06%   |
| 16.01-24.0 | 6         | 0.64%   |
| 24.01-32.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 706       | 81.24%  |
| 2      | 136       | 15.65%  |
| 3      | 14        | 1.61%   |
| 0      | 8         | 0.92%   |
| 4      | 3         | 0.35%   |
| 7      | 1         | 0.12%   |
| 6      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 560       | 64.74%  |
| Yes       | 305       | 35.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 718       | 83.29%  |
| No        | 144       | 16.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 841       | 97.79%  |
| No        | 19        | 2.21%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 686       | 79.03%  |
| No        | 182       | 20.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Finland | 858       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Helsinki     | 429       | 47.09%  |
| Tampere      | 72        | 7.9%    |
| Turku        | 66        | 7.24%   |
| Espoo        | 43        | 4.72%   |
| Oulu         | 35        | 3.84%   |
| Vantaa       | 27        | 2.96%   |
| Jyväskylä  | 25        | 2.74%   |
| Lahti        | 20        | 2.2%    |
| Kuopio       | 19        | 2.09%   |
| Vaasa        | 9         | 0.99%   |
| Raisio       | 8         | 0.88%   |
| Joensuu      | 6         | 0.66%   |
| Hyvinkaeae   | 6         | 0.66%   |
| Tuusula      | 5         | 0.55%   |
| Rovaniemi    | 5         | 0.55%   |
| Kouvola      | 5         | 0.55%   |
| Kokkola      | 5         | 0.55%   |
| Järvenpää | 5         | 0.55%   |
| Seinäjoki   | 4         | 0.44%   |
| Salo         | 4         | 0.44%   |
| Pori         | 4         | 0.44%   |
| Lohja        | 4         | 0.44%   |
| Lappeenranta | 4         | 0.44%   |
| Kotka        | 4         | 0.44%   |
| Hämeenlinna | 4         | 0.44%   |
| Forssa       | 4         | 0.44%   |
| Rusko        | 3         | 0.33%   |
| Raahe        | 3         | 0.33%   |
| Porvoo       | 3         | 0.33%   |
| Mäntsälä  | 3         | 0.33%   |
| Halikko      | 3         | 0.33%   |
| Ylöjärvi   | 2         | 0.22%   |
| Valkeakoski  | 2         | 0.22%   |
| Urjala       | 2         | 0.22%   |
| Tenala       | 2         | 0.22%   |
| Solv         | 2         | 0.22%   |
| Riihimäki   | 2         | 0.22%   |
| Rauma        | 2         | 0.22%   |
| Pirkkala     | 2         | 0.22%   |
| Mikkeli      | 2         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 204       | 281    | 20.46%  |
| Kingston                    | 88        | 103    | 8.83%   |
| Seagate                     | 82        | 96     | 8.22%   |
| WDC                         | 70        | 95     | 7.02%   |
| Toshiba                     | 63        | 71     | 6.32%   |
| SK hynix                    | 62        | 80     | 6.22%   |
| SanDisk                     | 55        | 67     | 5.52%   |
| Unknown                     | 52        | 72     | 5.22%   |
| Intel                       | 48        | 57     | 4.81%   |
| Hitachi                     | 42        | 58     | 4.21%   |
| Micron Technology           | 34        | 42     | 3.41%   |
| HGST                        | 23        | 39     | 2.31%   |
| Crucial                     | 18        | 20     | 1.81%   |
| Apple                       | 18        | 25     | 1.81%   |
| KIOXIA                      | 12        | 12     | 1.2%    |
| A-DATA Technology           | 12        | 13     | 1.2%    |
| Transcend                   | 11        | 11     | 1.1%    |
| Fujitsu                     | 10        | 13     | 1%      |
| Kingston Technology Company | 9         | 11     | 0.9%    |
| OCZ                         | 6         | 10     | 0.6%    |
| Corsair                     | 6         | 6      | 0.6%    |
| PNY                         | 5         | 5      | 0.5%    |
| LITEONIT                    | 5         | 10     | 0.5%    |
| LITEON                      | 5         | 9      | 0.5%    |
| BHT                         | 5         | 7      | 0.5%    |
| Lenovo                      | 4         | 4      | 0.4%    |
| Intenso                     | 3         | 3      | 0.3%    |
| China                       | 3         | 4      | 0.3%    |
| ASMT                        | 3         | 3      | 0.3%    |
| Union Memory (Shenzhen)     | 2         | 4      | 0.2%    |
| UMIS                        | 2         | 4      | 0.2%    |
| Phison                      | 2         | 2      | 0.2%    |
| Patriot                     | 2         | 2      | 0.2%    |
| JMicron Technology          | 2         | 5      | 0.2%    |
| Gigabyte Technology         | 2         | 2      | 0.2%    |
| ASMedia                     | 2         | 2      | 0.2%    |
| Unknown                     | 2         | 2      | 0.2%    |
| YMTC                        | 1         | 1      | 0.1%    |
| XPG                         | 1         | 1      | 0.1%    |
| WALRAM                      | 1         | 2      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 18        | 1.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 13        | 1.26%   |
| Unknown MMC Card  64GB                             | 12        | 1.17%   |
| Seagate ST9500325AS 500GB                          | 12        | 1.17%   |
| Samsung SSD 850 EVO 500GB                          | 11        | 1.07%   |
| Kingston SA400S37120G 120GB SSD                    | 10        | 0.97%   |
| Unknown MMC Card  32GB                             | 9         | 0.87%   |
| Seagate ST500LT012-1DG142 500GB                    | 8         | 0.78%   |
| Samsung NVMe SSD Drive 512GB                       | 8         | 0.78%   |
| HGST HTS721010A9E630 1TB                           | 8         | 0.78%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 7         | 0.68%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD               | 7         | 0.68%   |
| Kingston SA400S37480G 480GB SSD                    | 7         | 0.68%   |
| Unknown MMC Card  128GB                            | 6         | 0.58%   |
| SK hynix NVMe SSD Drive 512GB                      | 6         | 0.58%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD                | 6         | 0.58%   |
| Samsung MZ7LN256HAJQ-000L2 256GB SSD               | 6         | 0.58%   |
| Kingston SV300S37A240G 240GB SSD                   | 6         | 0.58%   |
| Intel SSDSC2BW180A3L 180GB                         | 6         | 0.58%   |
| Toshiba MQ01ABD100 1TB                             | 5         | 0.49%   |
| Seagate ST1000LM035-1RK172 1TB                     | 5         | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                       | 5         | 0.49%   |
| Samsung SSD 850 EVO 250GB                          | 5         | 0.49%   |
| HGST HTS725050A7E630 500GB                         | 5         | 0.49%   |
| Toshiba THNSNF128GCSS 128GB SSD                    | 4         | 0.39%   |
| Toshiba NVMe SSD Drive 256GB                       | 4         | 0.39%   |
| Toshiba MQ01ABF050 500GB                           | 4         | 0.39%   |
| Toshiba MQ01ABD075 752GB                           | 4         | 0.39%   |
| SK hynix NVMe SSD Drive 256GB                      | 4         | 0.39%   |
| SK hynix HFS256G39TND-N210A 256GB SSD              | 4         | 0.39%   |
| SK hynix BC511 256GB                               | 4         | 0.39%   |
| Seagate ST500LT012-9WS142 500GB                    | 4         | 0.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 4         | 0.39%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 4         | 0.39%   |
| SanDisk DF4064  64GB                               | 4         | 0.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 4         | 0.39%   |
| Samsung MZVLQ512HBLU-00B00 512GB                   | 4         | 0.39%   |
| Samsung MZVLB512HAJQ-000L7 512GB                   | 4         | 0.39%   |
| PNY CS900 120GB SSD                                | 4         | 0.39%   |
| Micron 2210_MTFDHBA512QFD 512GB                    | 4         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 80        | 94     | 32.26%  |
| WDC                 | 44        | 60     | 17.74%  |
| Hitachi             | 42        | 58     | 16.94%  |
| Toshiba             | 32        | 37     | 12.9%   |
| HGST                | 23        | 39     | 9.27%   |
| Fujitsu             | 10        | 13     | 4.03%   |
| Samsung Electronics | 7         | 7      | 2.82%   |
| JMicron Technology  | 2         | 5      | 0.81%   |
| Intenso             | 2         | 2      | 0.81%   |
| ASMedia             | 2         | 2      | 0.81%   |
| Unknown             | 1         | 1      | 0.4%    |
| RSH-339             | 1         | 1      | 0.4%    |
| ASMT                | 1         | 1      | 0.4%    |
| Apple               | 1         | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 112       | 168    | 28.64%  |
| Kingston            | 76        | 89     | 19.44%  |
| SanDisk             | 32        | 40     | 8.18%   |
| Intel               | 24        | 29     | 6.14%   |
| Crucial             | 17        | 19     | 4.35%   |
| WDC                 | 14        | 18     | 3.58%   |
| Micron Technology   | 14        | 16     | 3.58%   |
| SK hynix            | 13        | 21     | 3.32%   |
| Apple               | 12        | 13     | 3.07%   |
| Transcend           | 11        | 11     | 2.81%   |
| Toshiba             | 10        | 11     | 2.56%   |
| A-DATA Technology   | 9         | 10     | 2.3%    |
| OCZ                 | 6         | 10     | 1.53%   |
| PNY                 | 5         | 5      | 1.28%   |
| LITEONIT            | 5         | 10     | 1.28%   |
| LITEON              | 5         | 9      | 1.28%   |
| BHT                 | 4         | 6      | 1.02%   |
| China               | 3         | 4      | 0.77%   |
| Patriot             | 2         | 2      | 0.51%   |
| Corsair             | 2         | 2      | 0.51%   |
| ASMT                | 2         | 2      | 0.51%   |
| WALRAM              | 1         | 1      | 0.26%   |
| Verbatim            | 1         | 1      | 0.26%   |
| Vaseky              | 1         | 1      | 0.26%   |
| Ramsta              | 1         | 1      | 0.26%   |
| OCZ-VERTEX          | 1         | 1      | 0.26%   |
| Netac               | 1         | 1      | 0.26%   |
| Kolink              | 1         | 1      | 0.26%   |
| Intenso             | 1         | 1      | 0.26%   |
| Hewlett-Packard     | 1         | 1      | 0.26%   |
| GOODRAM             | 1         | 1      | 0.26%   |
| CF400               | 1         | 1      | 0.26%   |
| ATP                 | 1         | 1      | 0.26%   |
| Unknown             | 1         | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 374       | 508    | 39.08%  |
| NVMe    | 284       | 362    | 29.68%  |
| HDD     | 238       | 321    | 24.87%  |
| MMC     | 55        | 77     | 5.75%   |
| Unknown | 6         | 7      | 0.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 565       | 805    | 61.02%  |
| NVMe | 284       | 362    | 30.67%  |
| MMC  | 55        | 77     | 5.94%   |
| SAS  | 22        | 31     | 2.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 485       | 664    | 80.03%  |
| 0.51-1.0   | 107       | 145    | 17.66%  |
| 1.01-2.0   | 8         | 9      | 1.32%   |
| 3.01-4.0   | 3         | 4      | 0.5%    |
| 4.01-10.0  | 2         | 6      | 0.33%   |
| 2.01-3.0   | 1         | 1      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 316       | 35.31%  |
| 251-500        | 202       | 22.57%  |
| 501-1000       | 107       | 11.96%  |
| 51-100         | 73        | 8.16%   |
| 1-20           | 65        | 7.26%   |
| 21-50          | 40        | 4.47%   |
| Unknown        | 37        | 4.13%   |
| 1001-2000      | 34        | 3.8%    |
| More than 3000 | 15        | 1.68%   |
| 2001-3000      | 6         | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 404       | 43.07%  |
| 21-50          | 195       | 20.79%  |
| 51-100         | 103       | 10.98%  |
| 101-250        | 99        | 10.55%  |
| 251-500        | 56        | 5.97%   |
| Unknown        | 37        | 3.94%   |
| 501-1000       | 30        | 3.2%    |
| More than 3000 | 5         | 0.53%   |
| 1001-2000      | 5         | 0.53%   |
| 2001-3000      | 4         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                        | 4         | 5      | 7.69%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 3      | 3.85%   |
| Intel SSDSC2BF240A5L 240GB                       | 2         | 3      | 3.85%   |
| WDC WD1600BJKT-75F4T0 160GB                      | 1         | 1      | 1.92%   |
| WDC WD10JUCT-63CYNY0 1TB                         | 1         | 1      | 1.92%   |
| Vaseky V800/60G 64GB                             | 1         | 1      | 1.92%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.92%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 1.92%   |
| Toshiba MK8052GSX 80GB                           | 1         | 1      | 1.92%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 1.92%   |
| Toshiba MK1652GSX 160GB                          | 1         | 1      | 1.92%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD          | 1         | 1      | 1.92%   |
| SK hynix PC401 NVMe 512GB                        | 1         | 1      | 1.92%   |
| SK hynix HFS256G39TND-N210A 256GB SSD            | 1         | 1      | 1.92%   |
| SK hynix BC711 HFM256GD3JX013N 256GB             | 1         | 1      | 1.92%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.92%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 1.92%   |
| Seagate ST9250827AS 250GB                        | 1         | 1      | 1.92%   |
| Seagate ST9250320AS 250GB                        | 1         | 1      | 1.92%   |
| Seagate ST9160412AS 160GB                        | 1         | 1      | 1.92%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB             | 1         | 1      | 1.92%   |
| Seagate ST2000LM015-2E8174 2TB                   | 1         | 1      | 1.92%   |
| SanDisk SD9TN8W-256G-1006 256GB SSD              | 1         | 1      | 1.92%   |
| Samsung Electronics MZNLN256HAJQ-000H1 256GB SSD | 1         | 1      | 1.92%   |
| Samsung Electronics MZMTD512HAGL-000L1 512GB SSD | 1         | 1      | 1.92%   |
| Samsung Electronics HM060HI 64GB                 | 1         | 1      | 1.92%   |
| OCZ TRION100 120GB SSD                           | 1         | 1      | 1.92%   |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 1.92%   |
| Kingston RBUSC180DS37128GH 128GB SSD             | 1         | 1      | 1.92%   |
| Kingston RBU-SNS8100S3128GD 128GB SSD            | 1         | 1      | 1.92%   |
| Intel SSDSC2BW240H6 240GB                        | 1         | 1      | 1.92%   |
| Intel SSDSC2BW180A3L 180GB                       | 1         | 1      | 1.92%   |
| Intel SSDSA2M080G2GC 80GB                        | 1         | 1      | 1.92%   |
| Hitachi HTS721010G9SA00 100GB                    | 1         | 4      | 1.92%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 1.92%   |
| Hitachi HTS545050B9A300 500GB                    | 1         | 4      | 1.92%   |
| Hitachi HTS543232L9A300 320GB                    | 1         | 2      | 1.92%   |
| Hitachi HTS543216L9SA02 160GB                    | 1         | 1      | 1.92%   |
| Hitachi HTS541680J9SA00 80GB                     | 1         | 1      | 1.92%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 25%     |
| Toshiba             | 6         | 6      | 11.54%  |
| Hitachi             | 6         | 13     | 11.54%  |
| Intel               | 5         | 6      | 9.62%   |
| HGST                | 4         | 4      | 7.69%   |
| SK hynix            | 3         | 3      | 5.77%   |
| Samsung Electronics | 3         | 3      | 5.77%   |
| Kingston            | 3         | 3      | 5.77%   |
| WDC                 | 2         | 2      | 3.85%   |
| Fujitsu             | 2         | 3      | 3.85%   |
| Vaseky              | 1         | 1      | 1.92%   |
| SanDisk             | 1         | 1      | 1.92%   |
| OCZ                 | 1         | 1      | 1.92%   |
| ATP                 | 1         | 1      | 1.92%   |
| Apple               | 1         | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 39.39%  |
| Hitachi             | 6         | 13     | 18.18%  |
| Toshiba             | 5         | 5      | 15.15%  |
| HGST                | 4         | 4      | 12.12%  |
| WDC                 | 2         | 2      | 6.06%   |
| Fujitsu             | 2         | 3      | 6.06%   |
| Samsung Electronics | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 43     | 63.46%  |
| SSD  | 17        | 18     | 32.69%  |
| NVMe | 2         | 2      | 3.85%   |

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
| Detected | 460       | 712    | 51%     |
| Works    | 390       | 500    | 43.24%  |
| Malfunc  | 52        | 63     | 5.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 562       | 59.35%  |
| Samsung Electronics              | 90        | 9.5%    |
| AMD                              | 90        | 9.5%    |
| SK hynix                         | 48        | 5.07%   |
| SanDisk                          | 29        | 3.06%   |
| Toshiba America Info Systems     | 21        | 2.22%   |
| Micron Technology                | 20        | 2.11%   |
| Kingston Technology Company      | 19        | 2.01%   |
| Nvidia                           | 12        | 1.27%   |
| KIOXIA                           | 12        | 1.27%   |
| Phison Electronics               | 8         | 0.84%   |
| Union Memory (Shenzhen)          | 5         | 0.53%   |
| Apple                            | 5         | 0.53%   |
| ADATA Technology                 | 5         | 0.53%   |
| Silicon Integrated Systems [SiS] | 4         | 0.42%   |
| Lenovo                           | 4         | 0.42%   |
| Solid State Storage Technology   | 2         | 0.21%   |
| Seagate Technology               | 2         | 0.21%   |
| Marvell Technology Group         | 2         | 0.21%   |
| Yangtze Memory Technologies      | 1         | 0.11%   |
| VIA Technologies                 | 1         | 0.11%   |
| Silicon Motion                   | 1         | 0.11%   |
| O2 Micro                         | 1         | 0.11%   |
| Micron/Crucial Technology        | 1         | 0.11%   |
| Lite-On Technology               | 1         | 0.11%   |
| JMicron Technology               | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 79        | 7.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 73        | 7.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 63        | 6.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 61        | 5.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 47        | 4.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 41        | 3.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 36        | 3.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 33        | 3.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 28        | 2.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 22        | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 20        | 1.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 20        | 1.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 18        | 1.74%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 15        | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller                              | 15        | 1.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 15        | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 14        | 1.35%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 12        | 1.16%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 12        | 1.16%   |
| Intel SSD 660P Series                                                            | 12        | 1.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 12        | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 12        | 1.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 10        | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10        | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 9         | 0.87%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 9         | 0.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 0.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 0.87%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 9         | 0.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 9         | 0.87%   |
| SK hynix BC511 NVMe SSD                                                          | 8         | 0.77%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 8         | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 7         | 0.68%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 6         | 0.58%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 6         | 0.58%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 6         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 582       | 58.43%  |
| NVMe | 284       | 28.51%  |
| IDE  | 77        | 7.73%   |
| RAID | 53        | 5.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 690       | 80.42%  |
| AMD          | 167       | 19.46%  |
| CentaurHauls | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz           | 20        | 2.33%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 20        | 2.33%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 17        | 1.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 15        | 1.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 15        | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 13        | 1.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 13        | 1.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 13        | 1.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 13        | 1.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 9         | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 8         | 0.93%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 8         | 0.93%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 8         | 0.93%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 8         | 0.93%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 8         | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 8         | 0.93%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 7         | 0.82%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 7         | 0.82%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 7         | 0.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 7         | 0.82%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 7         | 0.82%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 6         | 0.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz          | 6         | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 6         | 0.7%    |
| AMD Ryzen 5 5600H with Radeon Graphics      | 6         | 0.7%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 5         | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 5         | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 5         | 0.58%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 5         | 0.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 5         | 0.58%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 5         | 0.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 5         | 0.58%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 5         | 0.58%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 5         | 0.58%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 5         | 0.58%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 5         | 0.58%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 5         | 0.58%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 5         | 0.58%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 5         | 0.58%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 5         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 257       | 29.95%  |
| Intel Core i7                  | 173       | 20.16%  |
| Other                          | 51        | 5.94%   |
| Intel Celeron                  | 48        | 5.59%   |
| Intel Core 2 Duo               | 47        | 5.48%   |
| Intel Core i3                  | 45        | 5.24%   |
| AMD Ryzen 5                    | 34        | 3.96%   |
| AMD Ryzen 7                    | 22        | 2.56%   |
| Intel Pentium                  | 20        | 2.33%   |
| Intel Atom                     | 13        | 1.52%   |
| Intel Pentium Dual-Core        | 12        | 1.4%    |
| AMD Ryzen 7 PRO                | 10        | 1.17%   |
| AMD E1                         | 9         | 1.05%   |
| AMD Ryzen 5 PRO                | 8         | 0.93%   |
| AMD A8                         | 8         | 0.93%   |
| Intel Genuine                  | 7         | 0.82%   |
| AMD Ryzen 9                    | 7         | 0.82%   |
| AMD Ryzen 3                    | 7         | 0.82%   |
| AMD A4                         | 7         | 0.82%   |
| AMD A10                        | 7         | 0.82%   |
| AMD E2                         | 6         | 0.7%    |
| AMD A6                         | 5         | 0.58%   |
| Intel Pentium Dual             | 4         | 0.47%   |
| Intel Core 2                   | 4         | 0.47%   |
| Intel Core i9                  | 3         | 0.35%   |
| Intel Celeron Dual-Core        | 3         | 0.35%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.35%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.35%   |
| AMD Athlon                     | 3         | 0.35%   |
| Intel Core m7                  | 2         | 0.23%   |
| Intel Core m5                  | 2         | 0.23%   |
| Intel Core Duo                 | 2         | 0.23%   |
| Intel Celeron M                | 2         | 0.23%   |
| AMD Turion                     | 2         | 0.23%   |
| AMD Ryzen 3 PRO                | 2         | 0.23%   |
| AMD Mobile Sempron             | 2         | 0.23%   |
| AMD E                          | 2         | 0.23%   |
| AMD Athlon II Dual-Core        | 2         | 0.23%   |
| AMD A12                        | 2         | 0.23%   |
| Intel Xeon                     | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 476       | 55.41%  |
| 4      | 269       | 31.32%  |
| 8      | 45        | 5.24%   |
| 6      | 40        | 4.66%   |
| 1      | 15        | 1.75%   |
| 10     | 7         | 0.81%   |
| 14     | 2         | 0.23%   |
| 12     | 2         | 0.23%   |
| 24     | 1         | 0.12%   |
| 16     | 1         | 0.12%   |
| 5      | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 858       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 623       | 72.53%  |
| 1      | 236       | 27.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 842       | 98.02%  |
| 32-bit         | 12        | 1.4%    |
| Unknown        | 5         | 0.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 281       | 31.57%  |
| 0x206a7    | 51        | 5.73%   |
| 0x306a9    | 42        | 4.72%   |
| 0x806ec    | 34        | 3.82%   |
| 0x40651    | 31        | 3.48%   |
| 0x406e3    | 30        | 3.37%   |
| 0x1067a    | 26        | 2.92%   |
| 0x806ea    | 25        | 2.81%   |
| 0x806e9    | 17        | 1.91%   |
| 0x306d4    | 17        | 1.91%   |
| 0x306c3    | 17        | 1.91%   |
| 0x30678    | 16        | 1.8%    |
| 0x10676    | 15        | 1.69%   |
| 0x906e9    | 14        | 1.57%   |
| 0x806c1    | 13        | 1.46%   |
| 0x20655    | 13        | 1.46%   |
| 0x6fd      | 10        | 1.12%   |
| 0x506e3    | 10        | 1.12%   |
| 0x20652    | 10        | 1.12%   |
| 0x08600106 | 10        | 1.12%   |
| 0xa0652    | 9         | 1.01%   |
| 0x406c4    | 9         | 1.01%   |
| 0x906ea    | 8         | 0.9%    |
| 0x806eb    | 8         | 0.9%    |
| 0x706e5    | 8         | 0.9%    |
| 0x6fb      | 8         | 0.9%    |
| 0x08108102 | 8         | 0.9%    |
| 0x506c9    | 7         | 0.79%   |
| 0x06001119 | 7         | 0.79%   |
| 0x0a50000d | 6         | 0.67%   |
| 0x0a50000c | 6         | 0.67%   |
| 0x08108109 | 6         | 0.67%   |
| 0x06006705 | 6         | 0.67%   |
| 0x05000119 | 6         | 0.67%   |
| 0x806d1    | 5         | 0.56%   |
| 0x0a50000b | 5         | 0.56%   |
| 0x0810100b | 5         | 0.56%   |
| 0x706a1    | 4         | 0.45%   |
| 0x6e8      | 4         | 0.45%   |
| 0x406c3    | 4         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 158       | 18.41%  |
| SandyBridge      | 76        | 8.86%   |
| Haswell          | 76        | 8.86%   |
| IvyBridge        | 61        | 7.11%   |
| Skylake          | 59        | 6.88%   |
| Penryn           | 48        | 5.59%   |
| Silvermont       | 35        | 4.08%   |
| Core             | 30        | 3.5%    |
| Unknown          | 29        | 3.38%   |
| Westmere         | 28        | 3.26%   |
| Zen+             | 24        | 2.8%    |
| Broadwell        | 24        | 2.8%    |
| Zen 3            | 23        | 2.68%   |
| Zen 2            | 23        | 2.68%   |
| TigerLake        | 22        | 2.56%   |
| Icelake          | 15        | 1.75%   |
| Puma             | 12        | 1.4%    |
| Excavator        | 12        | 1.4%    |
| CometLake        | 12        | 1.4%    |
| Piledriver       | 10        | 1.17%   |
| Goldmont plus    | 9         | 1.05%   |
| Bobcat           | 9         | 1.05%   |
| Alderlake Hybrid | 9         | 1.05%   |
| K8 Hammer        | 8         | 0.93%   |
| P6               | 7         | 0.82%   |
| K8 & K10 hybrid  | 7         | 0.82%   |
| Goldmont         | 7         | 0.82%   |
| Zen              | 6         | 0.7%    |
| Bonnell          | 5         | 0.58%   |
| Jaguar           | 4         | 0.47%   |
| Steamroller      | 3         | 0.35%   |
| K10              | 3         | 0.35%   |
| Nehalem          | 2         | 0.23%   |
| K10 Llano        | 2         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 628       | 60.44%  |
| Nvidia                           | 207       | 19.92%  |
| AMD                              | 199       | 19.15%  |
| Silicon Integrated Systems [SiS] | 4         | 0.38%   |
| VIA Technologies                 | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 68        | 6.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 58        | 5.34%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 46        | 4.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 40        | 3.68%   |
| Intel UHD Graphics 620                                                                   | 38        | 3.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 3.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 2.58%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 27        | 2.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 26        | 2.39%   |
| Intel HD Graphics 620                                                                    | 24        | 2.21%   |
| Intel HD Graphics 5500                                                                   | 22        | 2.03%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 22        | 2.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 21        | 1.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 19        | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 1.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 1.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 1.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 1.47%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 1.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 1.38%   |
| Intel HD Graphics 630                                                                    | 12        | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 1.01%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 10        | 0.92%   |
| Intel HD Graphics 530                                                                    | 10        | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.83%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 0.83%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 9         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 0.64%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 7         | 0.64%   |
| AMD Lucienne                                                                             | 7         | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.55%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 0.55%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 5         | 0.46%   |
| Intel HD Graphics 515                                                                    | 5         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 467       | 54.3%   |
| Intel + Nvidia | 136       | 15.81%  |
| 1 x AMD        | 133       | 15.47%  |
| 1 x Nvidia     | 47        | 5.47%   |
| AMD + Nvidia   | 24        | 2.79%   |
| Intel + AMD    | 23        | 2.67%   |
| 2 x AMD        | 18        | 2.09%   |
| 2 x Intel      | 5         | 0.58%   |
| 1 x SiS        | 4         | 0.47%   |
| 2 x Nvidia     | 2         | 0.23%   |
| 1 x VIA        | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 731       | 84.31%  |
| Proprietary | 112       | 12.92%  |
| Unknown     | 24        | 2.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 589       | 67.78%  |
| 0.01-0.5   | 103       | 11.85%  |
| 1.01-2.0   | 76        | 8.75%   |
| 0.51-1.0   | 51        | 5.87%   |
| 3.01-4.0   | 36        | 4.14%   |
| 7.01-8.0   | 6         | 0.69%   |
| 5.01-6.0   | 5         | 0.58%   |
| 2.01-3.0   | 2         | 0.23%   |
| 16.01-24.0 | 1         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 192       | 19.98%  |
| LG Display              | 159       | 16.55%  |
| Samsung Electronics     | 127       | 13.22%  |
| Chimei Innolux          | 108       | 11.24%  |
| BOE                     | 80        | 8.32%   |
| Lenovo                  | 47        | 4.89%   |
| Apple                   | 27        | 2.81%   |
| Sharp                   | 21        | 2.19%   |
| Dell                    | 19        | 1.98%   |
| InfoVision              | 18        | 1.87%   |
| Hewlett-Packard         | 18        | 1.87%   |
| Acer                    | 13        | 1.35%   |
| BenQ                    | 12        | 1.25%   |
| CSO                     | 11        | 1.14%   |
| Chi Mei Optoelectronics | 11        | 1.14%   |
| PANDA                   | 10        | 1.04%   |
| LG Philips              | 10        | 1.04%   |
| Ancor Communications    | 8         | 0.83%   |
| Vestel Elektronik       | 7         | 0.73%   |
| Goldstar                | 6         | 0.62%   |
| Valve                   | 5         | 0.52%   |
| Sony                    | 4         | 0.42%   |
| IBM                     | 4         | 0.42%   |
| CPT                     | 4         | 0.42%   |
| ASUSTek Computer        | 4         | 0.42%   |
| ViewSonic               | 3         | 0.31%   |
| Toshiba                 | 3         | 0.31%   |
| LGD                     | 3         | 0.31%   |
| TMX                     | 2         | 0.21%   |
| Pixio                   | 2         | 0.21%   |
| Panasonic               | 2         | 0.21%   |
| Mi                      | 2         | 0.21%   |
| Fujitsu Siemens         | 2         | 0.21%   |
| YTH                     | 1         | 0.1%    |
| STA                     | 1         | 0.1%    |
| Quanta Display          | 1         | 0.1%    |
| Philips                 | 1         | 0.1%    |
| OEM                     | 1         | 0.1%    |
| MSI                     | 1         | 0.1%    |
| Marantz                 | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.82%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 8         | 0.82%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 7         | 0.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.72%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 6         | 0.62%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.62%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 6         | 0.62%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 5         | 0.51%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 5         | 0.51%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 4         | 0.41%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 4         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 4         | 0.41%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.41%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 4         | 0.41%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.41%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 4         | 0.41%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 4         | 0.41%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.41%   |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch           | 4         | 0.41%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 4         | 0.41%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                 | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch         | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 4         | 0.41%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 3         | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch  | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 3         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 398       | 43.31%  |
| 1366x768 (WXGA)    | 209       | 22.74%  |
| 1600x900 (HD+)     | 68        | 7.4%    |
| 3840x2160 (4K)     | 37        | 4.03%   |
| 2560x1440 (QHD)    | 33        | 3.59%   |
| 1440x900 (WXGA+)   | 32        | 3.48%   |
| 1280x800 (WXGA)    | 31        | 3.37%   |
| 1920x1200 (WUXGA)  | 25        | 2.72%   |
| 1680x1050 (WSXGA+) | 15        | 1.63%   |
| 2560x1600          | 13        | 1.41%   |
| 2880x1800          | 11        | 1.2%    |
| 3440x1440          | 8         | 0.87%   |
| 3840x2400          | 6         | 0.65%   |
| 800x1280           | 5         | 0.54%   |
| 1280x1024 (SXGA)   | 5         | 0.54%   |
| 1024x600           | 5         | 0.54%   |
| 3200x1800 (QHD+)   | 3         | 0.33%   |
| 1600x1200          | 2         | 0.22%   |
| 1360x768           | 2         | 0.22%   |
| 3840x1200          | 1         | 0.11%   |
| 3200x2000          | 1         | 0.11%   |
| 3000x2000          | 1         | 0.11%   |
| 2304x1440          | 1         | 0.11%   |
| 2256x1504          | 1         | 0.11%   |
| 2160x1440          | 1         | 0.11%   |
| 1920x540           | 1         | 0.11%   |
| 1920x1280          | 1         | 0.11%   |
| 1680x945           | 1         | 0.11%   |
| 1400x1050          | 1         | 0.11%   |
| 1280x720 (HD)      | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 322       | 33.3%   |
| 14      | 157       | 16.24%  |
| 13      | 155       | 16.03%  |
| 17      | 73        | 7.55%   |
| 12      | 41        | 4.24%   |
| 27      | 40        | 4.14%   |
| 24      | 28        | 2.9%    |
| 23      | 27        | 2.79%   |
| 11      | 16        | 1.65%   |
| 31      | 11        | 1.14%   |
| 21      | 11        | 1.14%   |
| 16      | 10        | 1.03%   |
| Unknown | 9         | 0.93%   |
| 84      | 8         | 0.83%   |
| 34      | 8         | 0.83%   |
| 18      | 8         | 0.83%   |
| 10      | 5         | 0.52%   |
| 7       | 5         | 0.52%   |
| 54      | 3         | 0.31%   |
| 40      | 3         | 0.31%   |
| 32      | 3         | 0.31%   |
| 28      | 3         | 0.31%   |
| 22      | 3         | 0.31%   |
| 72      | 2         | 0.21%   |
| 55      | 2         | 0.21%   |
| 43      | 2         | 0.21%   |
| 20      | 2         | 0.21%   |
| 19      | 2         | 0.21%   |
| 86      | 1         | 0.1%    |
| 58      | 1         | 0.1%    |
| 57      | 1         | 0.1%    |
| 49      | 1         | 0.1%    |
| 48      | 1         | 0.1%    |
| 29      | 1         | 0.1%    |
| 26      | 1         | 0.1%    |
| 25      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 556       | 57.92%  |
| 201-300     | 139       | 14.48%  |
| 501-600     | 88        | 9.17%   |
| 351-400     | 87        | 9.06%   |
| 601-700     | 20        | 2.08%   |
| 401-500     | 20        | 2.08%   |
| 701-800     | 11        | 1.15%   |
| 1001-1500   | 11        | 1.15%   |
| 1501-2000   | 10        | 1.04%   |
| Unknown     | 9         | 0.94%   |
| 1-100       | 5         | 0.52%   |
| 801-900     | 3         | 0.31%   |
| 901-1000    | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 682       | 79.77%  |
| 16/10   | 133       | 15.56%  |
| 21/9    | 8         | 0.94%   |
| 5/4     | 7         | 0.82%   |
| Unknown | 7         | 0.82%   |
| 3/2     | 6         | 0.7%    |
| 0.67    | 4         | 0.47%   |
| 4/3     | 3         | 0.35%   |
| 32/9    | 2         | 0.23%   |
| 3.20    | 1         | 0.12%   |
| 0.62    | 1         | 0.12%   |
| 0.56    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 319       | 33.13%  |
| 81-90          | 251       | 26.06%  |
| 121-130        | 61        | 6.33%   |
| 71-80          | 60        | 6.23%   |
| 201-250        | 50        | 5.19%   |
| 301-350        | 43        | 4.47%   |
| 61-70          | 41        | 4.26%   |
| 351-500        | 24        | 2.49%   |
| More than 1000 | 18        | 1.87%   |
| 51-60          | 16        | 1.66%   |
| 251-300        | 14        | 1.45%   |
| 111-120        | 12        | 1.25%   |
| 131-140        | 10        | 1.04%   |
| 151-200        | 9         | 0.93%   |
| Unknown        | 9         | 0.93%   |
| 141-150        | 8         | 0.83%   |
| 501-1000       | 7         | 0.73%   |
| 41-50          | 5         | 0.52%   |
| 1-40           | 5         | 0.52%   |
| 91-100         | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 411       | 43.31%  |
| 101-120       | 260       | 27.4%   |
| 51-100        | 146       | 15.38%  |
| 161-240       | 80        | 8.43%   |
| More than 240 | 29        | 3.06%   |
| 1-50          | 14        | 1.48%   |
| Unknown       | 9         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 692       | 78.64%  |
| 2     | 146       | 16.59%  |
| 0     | 28        | 3.18%   |
| 3     | 14        | 1.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 492       | 36.55%  |
| Realtek Semiconductor                  | 352       | 26.15%  |
| Qualcomm Atheros                       | 157       | 11.66%  |
| Broadcom                               | 79        | 5.87%   |
| MediaTek                               | 31        | 2.3%    |
| Ericsson Business Mobile Networks      | 26        | 1.93%   |
| Hewlett-Packard                        | 22        | 1.63%   |
| Sierra Wireless                        | 18        | 1.34%   |
| Broadcom Limited                       | 18        | 1.34%   |
| Marvell Technology Group               | 16        | 1.19%   |
| Ralink                                 | 15        | 1.11%   |
| Huawei Technologies                    | 13        | 0.97%   |
| Dell                                   | 11        | 0.82%   |
| TP-Link                                | 9         | 0.67%   |
| Lenovo                                 | 9         | 0.67%   |
| FIBOCOM                                | 9         | 0.67%   |
| Nvidia                                 | 8         | 0.59%   |
| DisplayLink                            | 6         | 0.45%   |
| Samsung Electronics                    | 5         | 0.37%   |
| OPPO Electronics                       | 5         | 0.37%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.37%   |
| ASUSTek Computer                       | 5         | 0.37%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.3%    |
| Qualcomm                               | 4         | 0.3%    |
| ASIX Electronics                       | 4         | 0.3%    |
| Ralink Technology                      | 3         | 0.22%   |
| ZyXEL Communications                   | 2         | 0.15%   |
| Xiaomi                                 | 1         | 0.07%   |
| Van Ooijen Technische Informatica      | 1         | 0.07%   |
| Texas Instruments                      | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| SEGGER                                 | 1         | 0.07%   |
| Research In Motion                     | 1         | 0.07%   |
| Qualcomm Atheros Communications        | 1         | 0.07%   |
| Primax Electronics                     | 1         | 0.07%   |
| Motorola PCS                           | 1         | 0.07%   |
| Microsoft                              | 1         | 0.07%   |
| Microchip Technology                   | 1         | 0.07%   |
| Linksys                                | 1         | 0.07%   |
| ICS Advent                             | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 235       | 13.54%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 66        | 3.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 54        | 3.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 47        | 2.71%   |
| Intel Wireless 8265 / 8275                                              | 46        | 2.65%   |
| Intel Wireless 8260                                                     | 38        | 2.19%   |
| Intel Wireless 7260                                                     | 36        | 2.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 35        | 2.02%   |
| Intel Wireless 7265                                                     | 32        | 1.84%   |
| Intel Wi-Fi 6 AX200                                                     | 29        | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 1.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 24        | 1.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 21        | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 20        | 1.15%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 0.98%   |
| Intel Ethernet Connection I219-LM                                       | 17        | 0.98%   |
| Intel Ethernet Connection I218-LM                                       | 17        | 0.98%   |
| Intel Ethernet Connection (4) I219-V                                    | 17        | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                                   | 16        | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 0.86%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 15        | 0.86%   |
| Intel Ethernet Connection (6) I219-V                                    | 15        | 0.86%   |
| Intel 82577LM Gigabit Network Connection                                | 15        | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 13        | 0.75%   |
| Intel Ethernet Connection I219-V                                        | 13        | 0.75%   |
| Intel Ethernet Connection I217-LM                                       | 13        | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                   | 13        | 0.75%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 0.69%   |
| Intel Centrino Advanced-N 6235                                          | 12        | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 11        | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 0.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 11        | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 11        | 0.63%   |
| Intel Centrino Advanced-N 6200                                          | 11        | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 473       | 52.38%  |
| Qualcomm Atheros                | 140       | 15.5%   |
| Realtek Semiconductor           | 111       | 12.29%  |
| Broadcom                        | 61        | 6.76%   |
| MediaTek                        | 28        | 3.1%    |
| Sierra Wireless                 | 18        | 1.99%   |
| Ralink                          | 15        | 1.66%   |
| Broadcom Limited                | 12        | 1.33%   |
| FIBOCOM                         | 9         | 1%      |
| TP-Link                         | 8         | 0.89%   |
| Hewlett-Packard                 | 6         | 0.66%   |
| Dell                            | 6         | 0.66%   |
| ASUSTek Computer                | 5         | 0.55%   |
| Ralink Technology               | 3         | 0.33%   |
| Qualcomm                        | 3         | 0.33%   |
| ZyXEL Communications            | 2         | 0.22%   |
| Qualcomm Atheros Communications | 1         | 0.11%   |
| Microsoft                       | 1         | 0.11%   |
| Linksys                         | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 47        | 5.2%    |
| Intel Wireless 8265 / 8275                                              | 46        | 5.09%   |
| Intel Wireless 8260                                                     | 38        | 4.2%    |
| Intel Wireless 7260                                                     | 36        | 3.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 35        | 3.87%   |
| Intel Wireless 7265                                                     | 32        | 3.54%   |
| Intel Wi-Fi 6 AX200                                                     | 29        | 3.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 2.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 2.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 21        | 2.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 20        | 2.21%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 2.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 1.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 1.66%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 15        | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 1.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 13        | 1.44%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.33%   |
| Intel Centrino Advanced-N 6235                                          | 12        | 1.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 11        | 1.22%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 1.22%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 11        | 1.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 11        | 1.22%   |
| Intel Centrino Advanced-N 6200                                          | 11        | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 1.22%   |
| Intel Wireless 3165                                                     | 10        | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 9         | 1%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 9         | 1%      |
| Intel Wireless 3160                                                     | 9         | 1%      |
| FIBOCOM L830-EB-00                                                      | 9         | 1%      |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 8         | 0.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 325       | 42.43%  |
| Intel                                  | 280       | 36.55%  |
| Broadcom                               | 34        | 4.44%   |
| Qualcomm Atheros                       | 33        | 4.31%   |
| Marvell Technology Group               | 16        | 2.09%   |
| Huawei Technologies                    | 10        | 1.31%   |
| Lenovo                                 | 9         | 1.17%   |
| Nvidia                                 | 8         | 1.04%   |
| DisplayLink                            | 6         | 0.78%   |
| Broadcom Limited                       | 6         | 0.78%   |
| Samsung Electronics                    | 5         | 0.65%   |
| OPPO Electronics                       | 5         | 0.65%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.52%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.52%   |
| Hewlett-Packard                        | 4         | 0.52%   |
| ASIX Electronics                       | 4         | 0.52%   |
| MediaTek                               | 3         | 0.39%   |
| TP-Link                                | 2         | 0.26%   |
| Xiaomi                                 | 1         | 0.13%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.13%   |
| Research In Motion                     | 1         | 0.13%   |
| Qualcomm                               | 1         | 0.13%   |
| ICS Advent                             | 1         | 0.13%   |
| HMD Global                             | 1         | 0.13%   |
| Foxconn / Hon Hai                      | 1         | 0.13%   |
| Attansic Technology                    | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 235       | 30.48%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 66        | 8.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 54        | 7%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 24        | 3.11%   |
| Intel Ethernet Connection I219-LM                                      | 17        | 2.2%    |
| Intel Ethernet Connection I218-LM                                      | 17        | 2.2%    |
| Intel Ethernet Connection (4) I219-V                                   | 17        | 2.2%    |
| Intel Ethernet Connection (4) I219-LM                                  | 16        | 2.08%   |
| Intel Ethernet Connection (6) I219-V                                   | 15        | 1.95%   |
| Intel 82577LM Gigabit Network Connection                               | 15        | 1.95%   |
| Intel Ethernet Connection I219-V                                       | 13        | 1.69%   |
| Intel Ethernet Connection I217-LM                                      | 13        | 1.69%   |
| Intel Ethernet Connection (3) I218-LM                                  | 13        | 1.69%   |
| Intel 82567LM Gigabit Network Connection                               | 11        | 1.43%   |
| Intel 82566MM Gigabit Network Connection                               | 10        | 1.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 8         | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 0.91%   |
| Huawei VTR-L09                                                         | 6         | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 6         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.65%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 5         | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 5         | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                  | 5         | 0.65%   |
| Intel Ethernet Connection (6) I219-LM                                  | 5         | 0.65%   |
| Intel 82573L Gigabit Ethernet Controller                               | 5         | 0.65%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 5         | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 5         | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 0.52%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 4         | 0.52%   |
| OnePlus (Shenzhen) OnePlus                                             | 4         | 0.52%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.52%   |
| HP lt4120 Snapdragon X5 LTE                                            | 4         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.39%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 0.39%   |
| MediaTek RMX3085                                                       | 3         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 841       | 52.07%  |
| Ethernet | 716       | 44.33%  |
| Modem    | 54        | 3.34%   |
| Unknown  | 4         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 683       | 76.48%  |
| Ethernet | 210       | 23.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 661       | 76.68%  |
| 1     | 183       | 21.23%  |
| 3     | 9         | 1.04%   |
| 0     | 9         | 1.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 684       | 77.64%  |
| Yes  | 197       | 22.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 327       | 47.05%  |
| Broadcom                        | 68        | 9.78%   |
| Realtek Semiconductor           | 64        | 9.21%   |
| Qualcomm Atheros Communications | 47        | 6.76%   |
| IMC Networks                    | 41        | 5.9%    |
| Foxconn / Hon Hai               | 33        | 4.75%   |
| Apple                           | 20        | 2.88%   |
| Lite-On Technology              | 17        | 2.45%   |
| Hewlett-Packard                 | 17        | 2.45%   |
| Dell                            | 12        | 1.73%   |
| Cambridge Silicon Radio         | 12        | 1.73%   |
| Ralink                          | 11        | 1.58%   |
| Askey Computer                  | 9         | 1.29%   |
| Foxconn International           | 4         | 0.58%   |
| ASUSTek Computer                | 3         | 0.43%   |
| Toshiba                         | 2         | 0.29%   |
| Realtek                         | 2         | 0.29%   |
| Chicony Electronics             | 2         | 0.29%   |
| USI                             | 1         | 0.14%   |
| Taiyo Yuden                     | 1         | 0.14%   |
| Fujitsu                         | 1         | 0.14%   |
| Alps Electric                   | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 87        | 12.52%  |
| Intel Bluetooth Device                              | 76        | 10.94%  |
| Intel AX201 Bluetooth                               | 51        | 7.34%   |
| Realtek Bluetooth Radio                             | 39        | 5.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 4.6%    |
| Intel AX200 Bluetooth                               | 30        | 4.32%   |
| Qualcomm Atheros  Bluetooth Device                  | 18        | 2.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 17        | 2.45%   |
| IMC Networks Bluetooth Radio                        | 16        | 2.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 15        | 2.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 1.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 1.73%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 1.73%   |
| Ralink RT3290 Bluetooth                             | 11        | 1.58%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 1.58%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 1.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 1.44%   |
| IMC Networks Wireless_Device                        | 9         | 1.29%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 1.29%   |
| Askey Bluetooth Device                              | 9         | 1.29%   |
| Realtek RTL8723B Bluetooth                          | 8         | 1.15%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 1.15%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 1.15%   |
| Intel AX211 Bluetooth                               | 8         | 1.15%   |
| IMC Networks Bluetooth Device                       | 8         | 1.15%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 1.15%   |
| Apple Bluetooth Host Controller                     | 8         | 1.15%   |
| Broadcom HP Portable Bumble Bee                     | 7         | 1.01%   |
| Apple Bluetooth USB Host Controller                 | 7         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.86%   |
| Lite-On Bluetooth Device                            | 6         | 0.86%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 0.86%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 0.86%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 6         | 0.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.72%   |
| Intel AX210 Bluetooth                               | 5         | 0.72%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.72%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.72%   |
| Broadcom HP Portable SoftSailing                    | 5         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 673       | 64.9%   |
| AMD                              | 172       | 16.59%  |
| Nvidia                           | 121       | 11.67%  |
| Realtek Semiconductor            | 6         | 0.58%   |
| Lenovo                           | 6         | 0.58%   |
| GN Netcom                        | 6         | 0.58%   |
| Silicon Integrated Systems [SiS] | 4         | 0.39%   |
| Logitech                         | 4         | 0.39%   |
| C-Media Electronics              | 4         | 0.39%   |
| Kingston Technology              | 3         | 0.29%   |
| Hewlett-Packard                  | 3         | 0.29%   |
| Turtle Beach                     | 2         | 0.19%   |
| RODE Microphones                 | 2         | 0.19%   |
| Plantronics                      | 2         | 0.19%   |
| Microsoft                        | 2         | 0.19%   |
| Focusrite-Novation               | 2         | 0.19%   |
| Creative Technology              | 2         | 0.19%   |
| Apple                            | 2         | 0.19%   |
| ZOOM                             | 1         | 0.1%    |
| Yamaha                           | 1         | 0.1%    |
| VIA Technologies                 | 1         | 0.1%    |
| Texas Instruments                | 1         | 0.1%    |
| Sony                             | 1         | 0.1%    |
| ROCCAT                           | 1         | 0.1%    |
| OnePlus Technology (Shenzhen)    | 1         | 0.1%    |
| Numark                           | 1         | 0.1%    |
| No brand                         | 1         | 0.1%    |
| Native Instruments               | 1         | 0.1%    |
| Micro Star International         | 1         | 0.1%    |
| Huawei Technologies              | 1         | 0.1%    |
| GYROCOM C&C                      | 1         | 0.1%    |
| Generalplus Technology           | 1         | 0.1%    |
| DSEA A/S                         | 1         | 0.1%    |
| DigiTech                         | 1         | 0.1%    |
| Dell                             | 1         | 0.1%    |
| Corsair                          | 1         | 0.1%    |
| Cambridge Audio                  | 1         | 0.1%    |
| ASUSTek Computer                 | 1         | 0.1%    |
| Antlion Audio                    | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 115       | 9.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 91        | 7.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 70        | 5.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 67        | 5.28%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 45        | 3.55%   |
| Intel 8 Series HD Audio Controller                                                                | 45        | 3.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 44        | 3.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 41        | 3.23%   |
| AMD FCH Azalia Controller                                                                         | 38        | 3%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 37        | 2.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 30        | 2.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 30        | 2.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 26        | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 25        | 1.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 25        | 1.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 1.89%   |
| Intel Broadwell-U Audio Controller                                                                | 24        | 1.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 21        | 1.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 21        | 1.66%   |
| AMD Kabini HDMI/DP Audio                                                                          | 20        | 1.58%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 17        | 1.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16        | 1.26%   |
| Intel CM238 HD Audio Controller                                                                   | 16        | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 15        | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 1.03%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 12        | 0.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 0.95%   |
| Nvidia Audio device                                                                               | 11        | 0.87%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 0.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 0.87%   |
| AMD Trinity HDMI Audio Controller                                                                 | 10        | 0.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 9         | 0.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 0.71%   |
| AMD Wrestler HDMI Audio                                                                           | 9         | 0.71%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 8         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 203       | 34.47%  |
| SK hynix            | 149       | 25.3%   |
| Micron Technology   | 70        | 11.88%  |
| Kingston            | 50        | 8.49%   |
| Unknown             | 45        | 7.64%   |
| Elpida              | 16        | 2.72%   |
| Ramaxel Technology  | 12        | 2.04%   |
| A-DATA Technology   | 10        | 1.7%    |
| Crucial             | 8         | 1.36%   |
| Corsair             | 8         | 1.36%   |
| Nanya Technology    | 6         | 1.02%   |
| G.Skill             | 3         | 0.51%   |
| Qimonda             | 2         | 0.34%   |
| Unknown (ABCD)      | 1         | 0.17%   |
| Unknown (0E97)      | 1         | 0.17%   |
| Toshiba             | 1         | 0.17%   |
| PUSKILL             | 1         | 0.17%   |
| pqi                 | 1         | 0.17%   |
| ChangXin Memory     | 1         | 0.17%   |
| 48spaces            | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 13        | 2.03%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 11        | 1.72%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s  | 11        | 1.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 10        | 1.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 10        | 1.56%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s     | 10        | 1.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 9         | 1.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 9         | 1.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 7         | 1.09%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 6         | 0.94%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 6         | 0.94%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s               | 6         | 0.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 6         | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 5         | 0.78%   |
| Unknown RAM Module 1024MB SODIMM DDR2                     | 5         | 0.78%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s | 5         | 0.78%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 5         | 0.78%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s    | 5         | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 5         | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 5         | 0.78%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s     | 5         | 0.78%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 5         | 0.78%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 4         | 0.63%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s  | 4         | 0.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 0.63%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s    | 4         | 0.63%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 3200MT/s     | 4         | 0.63%   |
| Kingston RAM 9905295-045.A01LF 2GB SODIMM DDR2 667MT/s    | 4         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s               | 3         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                        | 3         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 3         | 0.47%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s              | 3         | 0.47%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 3         | 0.47%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s             | 3         | 0.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 3         | 0.47%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s   | 3         | 0.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 3         | 0.47%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 3         | 0.47%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 3         | 0.47%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 3         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 211       | 41.21%  |
| DDR3    | 184       | 35.94%  |
| DDR2    | 43        | 8.4%    |
| LPDDR3  | 22        | 4.3%    |
| LPDDR4  | 21        | 4.1%    |
| SDRAM   | 13        | 2.54%   |
| DDR5    | 6         | 1.17%   |
| Unknown | 4         | 0.78%   |
| LPDDR5  | 3         | 0.59%   |
| DDR     | 3         | 0.59%   |
| DRAM    | 2         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 465       | 91.54%  |
| Row Of Chips | 36        | 7.09%   |
| Chip         | 5         | 0.98%   |
| Unknown      | 2         | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 198       | 35.55%  |
| 4096  | 159       | 28.55%  |
| 16384 | 87        | 15.62%  |
| 2048  | 76        | 13.64%  |
| 1024  | 22        | 3.95%   |
| 32768 | 13        | 2.33%   |
| 512   | 1         | 0.18%   |
| 256   | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 126       | 22.91%  |
| 2667    | 97        | 17.64%  |
| 3200    | 80        | 14.55%  |
| 1334    | 36        | 6.55%   |
| 2400    | 33        | 6%      |
| 2133    | 33        | 6%      |
| 667     | 28        | 5.09%   |
| 1333    | 17        | 3.09%   |
| Unknown | 15        | 2.73%   |
| 1067    | 11        | 2%      |
| 800     | 10        | 1.82%   |
| 4267    | 9         | 1.64%   |
| 1867    | 8         | 1.45%   |
| 4199    | 7         | 1.27%   |
| 3266    | 6         | 1.09%   |
| 2048    | 5         | 0.91%   |
| 4800    | 4         | 0.73%   |
| 4266    | 4         | 0.73%   |
| 5600    | 3         | 0.55%   |
| 1066    | 3         | 0.55%   |
| 975     | 3         | 0.55%   |
| 8400    | 2         | 0.36%   |
| 3733    | 2         | 0.36%   |
| 533     | 2         | 0.36%   |
| 7500    | 1         | 0.18%   |
| 7467    | 1         | 0.18%   |
| 6400    | 1         | 0.18%   |
| 2933    | 1         | 0.18%   |
| 1639    | 1         | 0.18%   |
| 333     | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 4         | 30.77%  |
| Samsung Electronics   | 2         | 15.38%  |
| Canon                 | 2         | 15.38%  |
| Seiko Epson           | 1         | 7.69%   |
| Pantum                | 1         | 7.69%   |
| Lexmark International | 1         | 7.69%   |
| Dell                  | 1         | 7.69%   |
| Brother Industries    | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson XP-510 Series         | 1         | 7.69%   |
| Samsung M2020 Series              | 1         | 7.69%   |
| Samsung C43x Series               | 1         | 7.69%   |
| Pantum P2500W series              | 1         | 7.69%   |
| Lexmark International 2400 series | 1         | 7.69%   |
| HP OfficeJet Pro 6970             | 1         | 7.69%   |
| HP LaserJet P2055 series          | 1         | 7.69%   |
| HP LaserJet 1018                  | 1         | 7.69%   |
| HP DeskJet 2130 series            | 1         | 7.69%   |
| Dell Laser Printer 1720           | 1         | 7.69%   |
| Canon PIXMA MG3100 Series         | 1         | 7.69%   |
| Canon LBP6000                     | 1         | 7.69%   |
| Brother DCP-7055 scanner/printer  | 1         | 7.69%   |

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
| Chicony Electronics                    | 249       | 33.51%  |
| IMC Networks                           | 77        | 10.36%  |
| Realtek Semiconductor                  | 47        | 6.33%   |
| Microdia                               | 47        | 6.33%   |
| Cheng Uei Precision Industry (Foxlink) | 34        | 4.58%   |
| Bison Electronics                      | 32        | 4.31%   |
| Quanta                                 | 31        | 4.17%   |
| Sunplus Innovation Technology          | 30        | 4.04%   |
| Suyin                                  | 28        | 3.77%   |
| Acer                                   | 25        | 3.36%   |
| Lite-On Technology                     | 21        | 2.83%   |
| Syntek                                 | 17        | 2.29%   |
| Apple                                  | 15        | 2.02%   |
| Logitech                               | 14        | 1.88%   |
| Silicon Motion                         | 11        | 1.48%   |
| Lenovo                                 | 11        | 1.48%   |
| Luxvisions Innotech Limited            | 8         | 1.08%   |
| Sonix Technology                       | 6         | 0.81%   |
| Alcor Micro                            | 6         | 0.81%   |
| Samsung Electronics                    | 5         | 0.67%   |
| Primax Electronics                     | 5         | 0.67%   |
| Z-Star Microelectronics                | 4         | 0.54%   |
| ALi                                    | 4         | 0.54%   |
| Ricoh                                  | 3         | 0.4%    |
| ShineTech                              | 2         | 0.27%   |
| Microsoft                              | 2         | 0.27%   |
| Importek                               | 2         | 0.27%   |
| DigiTech                               | 2         | 0.27%   |
| STEREOLABS                             | 1         | 0.13%   |
| OPPO Electronics                       | 1         | 0.13%   |
| Omnivision                             | 1         | 0.13%   |
| LG Electronics                         | 1         | 0.13%   |
| Anker PowerConf C200                   | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 65        | 8.67%   |
| IMC Networks Integrated Camera           | 24        | 3.2%    |
| Microdia Integrated_Webcam_HD            | 21        | 2.8%    |
| IMC Networks USB2.0 HD UVC WebCam        | 17        | 2.27%   |
| Chicony HP HD Camera                     | 16        | 2.13%   |
| Chicony FJ Camera                        | 15        | 2%      |
| Chicony HD WebCam                        | 14        | 1.87%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 13        | 1.73%   |
| Realtek Integrated_Webcam_HD             | 12        | 1.6%    |
| Chicony HP HD Webcam                     | 12        | 1.6%    |
| Bison Integrated Camera                  | 12        | 1.6%    |
| Chicony Integrated Camera (1280x720@30)  | 10        | 1.33%   |
| Acer Integrated Camera                   | 10        | 1.33%   |
| Syntek Integrated Camera                 | 9         | 1.2%    |
| Chicony Lenovo Integrated Camera (0.3MP) | 9         | 1.2%    |
| Lite-On HP HD Camera                     | 8         | 1.07%   |
| Bison SunplusIT Integrated Camera        | 8         | 1.07%   |
| Sunplus Integrated_Webcam_HD             | 7         | 0.93%   |
| Lite-On Integrated Camera                | 7         | 0.93%   |
| Chicony ThinkPad T490 Webcam             | 7         | 0.93%   |
| Chicony Integrated Camera [ThinkPad]     | 7         | 0.93%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 6         | 0.8%    |
| Sunplus HD WebCam                        | 6         | 0.8%    |
| Realtek USB Camera                       | 6         | 0.8%    |
| Microdia Integrated Webcam               | 6         | 0.8%    |
| Chicony USB2.0 VGA UVC WebCam            | 6         | 0.8%    |
| Chicony USB2.0 HD UVC WebCam             | 6         | 0.8%    |
| Chicony Lenovo EasyCamera                | 6         | 0.8%    |
| Chicony Integrated HP HD Webcam          | 6         | 0.8%    |
| Chicony HP Truevision HD camera          | 6         | 0.8%    |
| Acer Lenovo EasyCamera                   | 6         | 0.8%    |
| Sonix USB2.0 HD UVC WebCam               | 5         | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)  | 5         | 0.67%   |
| Realtek USB2.0 HD UVC WebCam             | 5         | 0.67%   |
| Realtek Lenovo EasyCamera                | 5         | 0.67%   |
| Quanta USB Webcam                        | 5         | 0.67%   |
| Quanta HP Webcam                         | 5         | 0.67%   |
| Quanta HP HD Camera                      | 5         | 0.67%   |
| Primax HP HD Webcam [Fixed]              | 5         | 0.67%   |
| Lenovo UVC Camera                        | 5         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 81        | 40.3%   |
| Synaptics                  | 49        | 24.38%  |
| AuthenTec                  | 22        | 10.95%  |
| Upek                       | 15        | 7.46%   |
| Shenzhen Goodix Technology | 15        | 7.46%   |
| STMicroelectronics         | 9         | 4.48%   |
| LighTuning Technology      | 6         | 2.99%   |
| Elan Microelectronics      | 4         | 1.99%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 29        | 14.43%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 11.94%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 15        | 7.46%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 6.47%   |
| AuthenTec AES2810                                                          | 12        | 5.97%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 5.47%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 4.48%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 3.98%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 3.98%   |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 3.98%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.99%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 2.99%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 2.49%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 2.49%   |
| Validity Sensors VFS491                                                    | 4         | 1.99%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.99%   |
| Synaptics UWP WBDI Device                                                  | 3         | 1.49%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.49%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.49%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.49%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 1.49%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.5%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.5%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.5%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.5%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.5%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.5%    |
| Elan ELAN:ARM-M4                                                           | 1         | 0.5%    |
| AuthenTec AES1600                                                          | 1         | 0.5%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Alcor Micro      | 71        | 50.35%  |
| Broadcom         | 38        | 26.95%  |
| O2 Micro         | 11        | 7.8%    |
| Lenovo           | 11        | 7.8%    |
| Upek             | 8         | 5.67%   |
| SCM Microsystems | 2         | 1.42%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 71        | 50.35%  |
| Broadcom 5880                                                                | 13        | 9.22%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 7.8%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 7.8%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 7.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 5.67%   |
| Broadcom 58200                                                               | 8         | 5.67%   |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 3.55%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.71%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.71%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.71%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.71%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 470       | 53.47%  |
| 1     | 289       | 32.88%  |
| 2     | 100       | 11.38%  |
| 3     | 13        | 1.48%   |
| 5     | 4         | 0.46%   |
| 4     | 2         | 0.23%   |
| 6     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 200       | 36.56%  |
| Chipcard                 | 124       | 22.67%  |
| Graphics card            | 80        | 14.63%  |
| Net/wireless             | 42        | 7.68%   |
| Multimedia controller    | 24        | 4.39%   |
| Bluetooth                | 19        | 3.47%   |
| Camera                   | 17        | 3.11%   |
| Storage                  | 10        | 1.83%   |
| Net/ethernet             | 6         | 1.1%    |
| Communication controller | 6         | 1.1%    |
| Card reader              | 6         | 1.1%    |
| Sound                    | 4         | 0.73%   |
| Modem                    | 4         | 0.73%   |
| Storage/raid             | 1         | 0.18%   |
| Network                  | 1         | 0.18%   |
| Flash memory             | 1         | 0.18%   |
| Firewire controller      | 1         | 0.18%   |
| Dvb card                 | 1         | 0.18%   |

