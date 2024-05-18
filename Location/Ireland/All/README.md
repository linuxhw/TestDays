Linux in Ireland - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ireland/Desktop/README.md) and [notebooks](/Location/Ireland/Notebook/README.md).

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

Total: 1140

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 15 3530            | Notebook    | [a71239f845](https://linux-hardware.org/?probe=a71239f845) | May 05, 2024 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [8bc6786d26](https://linux-hardware.org/?probe=8bc6786d26) | May 04, 2024 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [5a7379a961](https://linux-hardware.org/?probe=5a7379a961) | May 04, 2024 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [239aa09252](https://linux-hardware.org/?probe=239aa09252) | May 04, 2024 |
| HP            | Notebook                    | Notebook    | [3719fa55d8](https://linux-hardware.org/?probe=3719fa55d8) | May 02, 2024 |
| Dell          | Precision 3551              | Notebook    | [1dc964b6fb](https://linux-hardware.org/?probe=1dc964b6fb) | Apr 30, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [43fd55c47a](https://linux-hardware.org/?probe=43fd55c47a) | Apr 30, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [d480d08c5e](https://linux-hardware.org/?probe=d480d08c5e) | Apr 30, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [2349cf6da5](https://linux-hardware.org/?probe=2349cf6da5) | Apr 26, 2024 |
| Toshiba       | Satellite Pro A200          | Notebook    | [305f0f136a](https://linux-hardware.org/?probe=305f0f136a) | Apr 23, 2024 |
| Google        | Morphius                    | Notebook    | [a8361bc931](https://linux-hardware.org/?probe=a8361bc931) | Apr 19, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [d297fd582e](https://linux-hardware.org/?probe=d297fd582e) | Apr 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [46fe84935f](https://linux-hardware.org/?probe=46fe84935f) | Apr 18, 2024 |
| MSI           | PRO B650M-P                 | Desktop     | [90165c7480](https://linux-hardware.org/?probe=90165c7480) | Apr 18, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [24acebde2b](https://linux-hardware.org/?probe=24acebde2b) | Apr 18, 2024 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [c0e482caa4](https://linux-hardware.org/?probe=c0e482caa4) | Apr 16, 2024 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [7beaf3fb93](https://linux-hardware.org/?probe=7beaf3fb93) | Apr 14, 2024 |
| Dell          | Latitude E6410              | Notebook    | [af5738b699](https://linux-hardware.org/?probe=af5738b699) | Apr 07, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [36cae1df97](https://linux-hardware.org/?probe=36cae1df97) | Apr 06, 2024 |
| Alienware     | 0TYR0X A01                  | Desktop     | [ef1d3c4e97](https://linux-hardware.org/?probe=ef1d3c4e97) | Apr 04, 2024 |
| HP            | 21D0                        | Desktop     | [8097b780d4](https://linux-hardware.org/?probe=8097b780d4) | Apr 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3bc12b2fdc](https://linux-hardware.org/?probe=3bc12b2fdc) | Mar 31, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e04b94ae7b](https://linux-hardware.org/?probe=e04b94ae7b) | Mar 30, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [69432492b9](https://linux-hardware.org/?probe=69432492b9) | Mar 28, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [45c0437f91](https://linux-hardware.org/?probe=45c0437f91) | Mar 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2f1279e5f4](https://linux-hardware.org/?probe=2f1279e5f4) | Mar 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [96e93279ce](https://linux-hardware.org/?probe=96e93279ce) | Mar 21, 2024 |
| Dell          | Latitude E7240              | Notebook    | [bac4c4e0b9](https://linux-hardware.org/?probe=bac4c4e0b9) | Mar 21, 2024 |
| Dell          | Latitude E7240              | Notebook    | [4b2cf432cb](https://linux-hardware.org/?probe=4b2cf432cb) | Mar 19, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [9275a0aa01](https://linux-hardware.org/?probe=9275a0aa01) | Mar 18, 2024 |
| Dell          | Precision 7780              | Notebook    | [0cea91e90e](https://linux-hardware.org/?probe=0cea91e90e) | Mar 13, 2024 |
| Dell          | Precision 3551              | Notebook    | [ac0c79297b](https://linux-hardware.org/?probe=ac0c79297b) | Mar 12, 2024 |
| Dell          | Latitude 7490               | Notebook    | [af0f098b77](https://linux-hardware.org/?probe=af0f098b77) | Mar 10, 2024 |
| Lenovo        | ThinkPad X230 2325AEG       | Notebook    | [8e4dbd3b9a](https://linux-hardware.org/?probe=8e4dbd3b9a) | Mar 10, 2024 |
| ASUSTek       | GL753VD                     | Notebook    | [10302c2e00](https://linux-hardware.org/?probe=10302c2e00) | Mar 04, 2024 |
| Linx          | LINX1010B                   | Notebook    | [185483454f](https://linux-hardware.org/?probe=185483454f) | Mar 03, 2024 |
| Notebook      | N15_17RD                    | Notebook    | [efc829810d](https://linux-hardware.org/?probe=efc829810d) | Feb 28, 2024 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [bc6b844872](https://linux-hardware.org/?probe=bc6b844872) | Feb 22, 2024 |
| ASUSTek       | GL753VD                     | Notebook    | [5f363c641f](https://linux-hardware.org/?probe=5f363c641f) | Feb 22, 2024 |
| ASUSTek       | PRIME B760M-A               | Desktop     | [df41ae1364](https://linux-hardware.org/?probe=df41ae1364) | Feb 20, 2024 |
| HP            | 21D0                        | Desktop     | [a19cdbd10a](https://linux-hardware.org/?probe=a19cdbd10a) | Feb 20, 2024 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [656953e587](https://linux-hardware.org/?probe=656953e587) | Feb 20, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [13aee4c968](https://linux-hardware.org/?probe=13aee4c968) | Feb 19, 2024 |
| Valve         | Jupiter                     | Notebook    | [51257484fe](https://linux-hardware.org/?probe=51257484fe) | Feb 17, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [4a65dda0f2](https://linux-hardware.org/?probe=4a65dda0f2) | Feb 10, 2024 |
| Dell          | Studio XPS 1645             | Notebook    | [cb868b4ea2](https://linux-hardware.org/?probe=cb868b4ea2) | Feb 09, 2024 |
| Google        | Reks                        | Notebook    | [5e667c40ed](https://linux-hardware.org/?probe=5e667c40ed) | Feb 09, 2024 |
| Lenovo        | ThinkPad L13 Gen 2a 21AC... | Notebook    | [a07cdee250](https://linux-hardware.org/?probe=a07cdee250) | Feb 08, 2024 |
| Dell          | XPS 13 9350                 | Notebook    | [24d22f38e9](https://linux-hardware.org/?probe=24d22f38e9) | Feb 08, 2024 |
| Dell          | 051FJ8 A00                  | Desktop     | [abce3a8f48](https://linux-hardware.org/?probe=abce3a8f48) | Feb 06, 2024 |
| Lenovo        | ThinkPad P50 20EQS57700     | Notebook    | [39735c6cd2](https://linux-hardware.org/?probe=39735c6cd2) | Feb 03, 2024 |
| HP            | 21D0                        | Desktop     | [b9cb80ae88](https://linux-hardware.org/?probe=b9cb80ae88) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c8e849a73](https://linux-hardware.org/?probe=0c8e849a73) | Jan 15, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [3717e058ac](https://linux-hardware.org/?probe=3717e058ac) | Jan 13, 2024 |
| Gigabyte      | GA-MA790X-UD4P              | Desktop     | [4e5951814a](https://linux-hardware.org/?probe=4e5951814a) | Jan 09, 2024 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [8101d22b4a](https://linux-hardware.org/?probe=8101d22b4a) | Jan 09, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [999111d4e5](https://linux-hardware.org/?probe=999111d4e5) | Jan 09, 2024 |
| Acer          | Aspire ES1-533              | Notebook    | [68d1525855](https://linux-hardware.org/?probe=68d1525855) | Jan 08, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e2b86aade4](https://linux-hardware.org/?probe=e2b86aade4) | Jan 07, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e9337be795](https://linux-hardware.org/?probe=e9337be795) | Jan 07, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [1198f24836](https://linux-hardware.org/?probe=1198f24836) | Jan 04, 2024 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [0781004009](https://linux-hardware.org/?probe=0781004009) | Jan 02, 2024 |
| Medion        | Akoya E6239                 | Notebook    | [757858a876](https://linux-hardware.org/?probe=757858a876) | Dec 31, 2023 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [a06265dd1e](https://linux-hardware.org/?probe=a06265dd1e) | Dec 30, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [02163b04b7](https://linux-hardware.org/?probe=02163b04b7) | Dec 30, 2023 |
| Dell          | Inspiron 3482               | Notebook    | [bbcb062420](https://linux-hardware.org/?probe=bbcb062420) | Dec 29, 2023 |
| AVITA         | NS14A6                      | Notebook    | [adf732b1b6](https://linux-hardware.org/?probe=adf732b1b6) | Dec 23, 2023 |
| Toshiba       | Satellite A660              | Notebook    | [d0415e05d3](https://linux-hardware.org/?probe=d0415e05d3) | Dec 23, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [bbdb2204d8](https://linux-hardware.org/?probe=bbdb2204d8) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [03ddd69e34](https://linux-hardware.org/?probe=03ddd69e34) | Dec 22, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1dd35fdb02](https://linux-hardware.org/?probe=1dd35fdb02) | Dec 19, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [18f1d4c5d0](https://linux-hardware.org/?probe=18f1d4c5d0) | Dec 18, 2023 |
| Dell          | Latitude 5400               | Notebook    | [9ae128faf4](https://linux-hardware.org/?probe=9ae128faf4) | Dec 16, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | Notebook    | [91fd392ea3](https://linux-hardware.org/?probe=91fd392ea3) | Dec 14, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | Notebook    | [2dc1349392](https://linux-hardware.org/?probe=2dc1349392) | Dec 10, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [e8383035b9](https://linux-hardware.org/?probe=e8383035b9) | Dec 10, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [647f96ad2c](https://linux-hardware.org/?probe=647f96ad2c) | Dec 08, 2023 |
| Samsung       | 750XED                      | Notebook    | [5263f7ebc0](https://linux-hardware.org/?probe=5263f7ebc0) | Dec 07, 2023 |
| Acer          | Swift SFG14-71              | Notebook    | [a84f25d406](https://linux-hardware.org/?probe=a84f25d406) | Dec 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [6a95e96b1b](https://linux-hardware.org/?probe=6a95e96b1b) | Dec 02, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [ec402bfe2f](https://linux-hardware.org/?probe=ec402bfe2f) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | Desktop     | [8425b9dc62](https://linux-hardware.org/?probe=8425b9dc62) | Nov 30, 2023 |
| Dynabook      | Satellite Pro C50-H-11G     | Notebook    | [438812dbd7](https://linux-hardware.org/?probe=438812dbd7) | Nov 27, 2023 |
| Samsung       | 965QFG                      | Convertible | [8769cfd663](https://linux-hardware.org/?probe=8769cfd663) | Nov 27, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [9a5c924695](https://linux-hardware.org/?probe=9a5c924695) | Nov 26, 2023 |
| AZW           | Green G3                    | Desktop     | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [2c7d8106d0](https://linux-hardware.org/?probe=2c7d8106d0) | Nov 24, 2023 |
| Dell          | 0X4H68 A00                  | Desktop     | [9fe4290fb6](https://linux-hardware.org/?probe=9fe4290fb6) | Nov 21, 2023 |
| Dell          | 0X4H68 A00                  | Desktop     | [93d573033d](https://linux-hardware.org/?probe=93d573033d) | Nov 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0af175a9d7](https://linux-hardware.org/?probe=0af175a9d7) | Nov 19, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [d0f4cc3a98](https://linux-hardware.org/?probe=d0f4cc3a98) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [a76432f7df](https://linux-hardware.org/?probe=a76432f7df) | Nov 16, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [1d3516385d](https://linux-hardware.org/?probe=1d3516385d) | Nov 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [80774e2d18](https://linux-hardware.org/?probe=80774e2d18) | Nov 14, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e45684a89b](https://linux-hardware.org/?probe=e45684a89b) | Nov 13, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [242621dab3](https://linux-hardware.org/?probe=242621dab3) | Nov 13, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [7736f94150](https://linux-hardware.org/?probe=7736f94150) | Nov 13, 2023 |
| Alienware     | m18 R1                      | Notebook    | [f4c5c9d2ec](https://linux-hardware.org/?probe=f4c5c9d2ec) | Nov 13, 2023 |
| HP            | Pavilion m6                 | Notebook    | [60a4921f94](https://linux-hardware.org/?probe=60a4921f94) | Nov 13, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [5ad5316ab5](https://linux-hardware.org/?probe=5ad5316ab5) | Nov 11, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [94186792b2](https://linux-hardware.org/?probe=94186792b2) | Nov 08, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [e275461ffe](https://linux-hardware.org/?probe=e275461ffe) | Nov 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [680fae0bef](https://linux-hardware.org/?probe=680fae0bef) | Nov 07, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [d743b33cc7](https://linux-hardware.org/?probe=d743b33cc7) | Nov 05, 2023 |
| System76      | Lemur Pro                   | Notebook    | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [3ba4126936](https://linux-hardware.org/?probe=3ba4126936) | Nov 04, 2023 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [440d52f445](https://linux-hardware.org/?probe=440d52f445) | Nov 04, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fc6336fedd](https://linux-hardware.org/?probe=fc6336fedd) | Nov 02, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Dell          | Latitude 5421               | Notebook    | [670d635ddc](https://linux-hardware.org/?probe=670d635ddc) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1a7844f56d](https://linux-hardware.org/?probe=1a7844f56d) | Oct 30, 2023 |
| Acer          | Swift SFG14-71              | Notebook    | [1a28398320](https://linux-hardware.org/?probe=1a28398320) | Oct 26, 2023 |
| HP            | 3399                        | Desktop     | [3dca1c2950](https://linux-hardware.org/?probe=3dca1c2950) | Oct 22, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [86fca6aaf4](https://linux-hardware.org/?probe=86fca6aaf4) | Oct 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [390f0188b4](https://linux-hardware.org/?probe=390f0188b4) | Oct 19, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [c9ab502087](https://linux-hardware.org/?probe=c9ab502087) | Oct 17, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [88057db3aa](https://linux-hardware.org/?probe=88057db3aa) | Oct 11, 2023 |
| Dell          | Latitude E6430              | Notebook    | [45d51130b0](https://linux-hardware.org/?probe=45d51130b0) | Oct 08, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [446c6847c3](https://linux-hardware.org/?probe=446c6847c3) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da869ee2ba](https://linux-hardware.org/?probe=da869ee2ba) | Oct 04, 2023 |
| Dell          | Latitude 5580               | Notebook    | [cf79594d59](https://linux-hardware.org/?probe=cf79594d59) | Oct 02, 2023 |
| Dell          | Latitude 5580               | Notebook    | [9cb7ac852c](https://linux-hardware.org/?probe=9cb7ac852c) | Oct 02, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [93e66c7d47](https://linux-hardware.org/?probe=93e66c7d47) | Oct 02, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ffd2e0d99d](https://linux-hardware.org/?probe=ffd2e0d99d) | Oct 01, 2023 |
| Dell          | Latitude 5410               | Notebook    | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [27b01f468d](https://linux-hardware.org/?probe=27b01f468d) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [86d39b72d6](https://linux-hardware.org/?probe=86d39b72d6) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| Dell          | Latitude 5410               | Notebook    | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [0e12b69b96](https://linux-hardware.org/?probe=0e12b69b96) | Sep 29, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Dell          | Latitude 7320               | Notebook    | [2549020a4e](https://linux-hardware.org/?probe=2549020a4e) | Sep 26, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [20e0572ade](https://linux-hardware.org/?probe=20e0572ade) | Sep 21, 2023 |
| MSI           | Katana GF76 12UG            | Notebook    | [ee50afcf85](https://linux-hardware.org/?probe=ee50afcf85) | Sep 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [8bf4c79f98](https://linux-hardware.org/?probe=8bf4c79f98) | Sep 17, 2023 |
| HP            | 0B54h D                     | Desktop     | [f5259ad0b1](https://linux-hardware.org/?probe=f5259ad0b1) | Sep 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| Dell          | Latitude E6400              | Notebook    | [b0943a149a](https://linux-hardware.org/?probe=b0943a149a) | Sep 10, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [8f6631088b](https://linux-hardware.org/?probe=8f6631088b) | Sep 08, 2023 |
| ASUSTek       | TALAS                       | Desktop     | [094153c6f4](https://linux-hardware.org/?probe=094153c6f4) | Sep 04, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [e335c8210f](https://linux-hardware.org/?probe=e335c8210f) | Sep 03, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [0f98d77b72](https://linux-hardware.org/?probe=0f98d77b72) | Sep 01, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [17802d53e7](https://linux-hardware.org/?probe=17802d53e7) | Aug 30, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [12b48399ac](https://linux-hardware.org/?probe=12b48399ac) | Aug 30, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [9d47465c31](https://linux-hardware.org/?probe=9d47465c31) | Aug 29, 2023 |
| Lenovo        | ThinkPad X200 7459ED2       | Notebook    | [4885ef4597](https://linux-hardware.org/?probe=4885ef4597) | Aug 27, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [db091802b1](https://linux-hardware.org/?probe=db091802b1) | Aug 26, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [8f51778271](https://linux-hardware.org/?probe=8f51778271) | Aug 25, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7e397373d8](https://linux-hardware.org/?probe=7e397373d8) | Aug 25, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [82be53cac0](https://linux-hardware.org/?probe=82be53cac0) | Aug 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [2970428ad3](https://linux-hardware.org/?probe=2970428ad3) | Aug 23, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [546610fecb](https://linux-hardware.org/?probe=546610fecb) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [692bd3fa37](https://linux-hardware.org/?probe=692bd3fa37) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [6313b3f69e](https://linux-hardware.org/?probe=6313b3f69e) | Aug 20, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [0182dad759](https://linux-hardware.org/?probe=0182dad759) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [23d9892448](https://linux-hardware.org/?probe=23d9892448) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [e280c00c8b](https://linux-hardware.org/?probe=e280c00c8b) | Aug 12, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [8b0d028b37](https://linux-hardware.org/?probe=8b0d028b37) | Aug 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [2e4e848552](https://linux-hardware.org/?probe=2e4e848552) | Aug 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [179beade50](https://linux-hardware.org/?probe=179beade50) | Aug 08, 2023 |
| Dell          | Precision M2800             | Notebook    | [7d1afe9d42](https://linux-hardware.org/?probe=7d1afe9d42) | Aug 05, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ea4d9240fb](https://linux-hardware.org/?probe=ea4d9240fb) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [76662ba2c9](https://linux-hardware.org/?probe=76662ba2c9) | Aug 05, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [6c13f7a1f0](https://linux-hardware.org/?probe=6c13f7a1f0) | Aug 04, 2023 |
| HP            | 21D0                        | Desktop     | [44e0cbb52e](https://linux-hardware.org/?probe=44e0cbb52e) | Aug 03, 2023 |
| HP            | 21D0                        | Desktop     | [099fea9193](https://linux-hardware.org/?probe=099fea9193) | Aug 02, 2023 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [30354c1f38](https://linux-hardware.org/?probe=30354c1f38) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | Notebook    | [928fd8c7cb](https://linux-hardware.org/?probe=928fd8c7cb) | Jul 29, 2023 |
| HP            | 829A                        | Mini pc     | [5bd4fdc8d1](https://linux-hardware.org/?probe=5bd4fdc8d1) | Jul 28, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [8e05eceeef](https://linux-hardware.org/?probe=8e05eceeef) | Jul 26, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [5457b19b2b](https://linux-hardware.org/?probe=5457b19b2b) | Jul 26, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [08fd0fea6a](https://linux-hardware.org/?probe=08fd0fea6a) | Jul 26, 2023 |
| HP            | 21D0                        | Desktop     | [774375de1f](https://linux-hardware.org/?probe=774375de1f) | Jul 22, 2023 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [8b128357b4](https://linux-hardware.org/?probe=8b128357b4) | Jul 19, 2023 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [7733080cef](https://linux-hardware.org/?probe=7733080cef) | Jul 19, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [f47d2eaa8e](https://linux-hardware.org/?probe=f47d2eaa8e) | Jul 16, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [99b59160a1](https://linux-hardware.org/?probe=99b59160a1) | Jul 16, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [a505a2e91f](https://linux-hardware.org/?probe=a505a2e91f) | Jul 15, 2023 |
| HP            | Pavilion m6                 | Notebook    | [8566e9607f](https://linux-hardware.org/?probe=8566e9607f) | Jul 14, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [0e9916f3e3](https://linux-hardware.org/?probe=0e9916f3e3) | Jul 13, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [a72d009fab](https://linux-hardware.org/?probe=a72d009fab) | Jul 13, 2023 |
| HP            | 21D0                        | Desktop     | [a6d51a414c](https://linux-hardware.org/?probe=a6d51a414c) | Jul 11, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [9dee0fcab9](https://linux-hardware.org/?probe=9dee0fcab9) | Jul 09, 2023 |
| Samsung       | 750XED                      | Notebook    | [412a36c3f1](https://linux-hardware.org/?probe=412a36c3f1) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [aa8cfd7d60](https://linux-hardware.org/?probe=aa8cfd7d60) | Jul 07, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | Desktop     | [2bb5ca7ea2](https://linux-hardware.org/?probe=2bb5ca7ea2) | Jul 05, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | Desktop     | [b24c1d471d](https://linux-hardware.org/?probe=b24c1d471d) | Jul 04, 2023 |
| Dell          | Latitude 3410               | Notebook    | [da609df435](https://linux-hardware.org/?probe=da609df435) | Jul 03, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| Shenzhen W... | AERO 5 Lite Mini PC         | Mini pc     | [7375ced625](https://linux-hardware.org/?probe=7375ced625) | Jun 30, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [bfa03ecd27](https://linux-hardware.org/?probe=bfa03ecd27) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [58d1b3da16](https://linux-hardware.org/?probe=58d1b3da16) | Jun 25, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [3fbef5ec38](https://linux-hardware.org/?probe=3fbef5ec38) | Jun 25, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [3e2928fe9d](https://linux-hardware.org/?probe=3e2928fe9d) | Jun 23, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [ae5f4be943](https://linux-hardware.org/?probe=ae5f4be943) | Jun 20, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [8bf2dd01d7](https://linux-hardware.org/?probe=8bf2dd01d7) | Jun 18, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [913d8d26b9](https://linux-hardware.org/?probe=913d8d26b9) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC0F    | Notebook    | [581602e921](https://linux-hardware.org/?probe=581602e921) | Jun 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [476a44deee](https://linux-hardware.org/?probe=476a44deee) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3d29012888](https://linux-hardware.org/?probe=3d29012888) | Jun 04, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [8678eeac9b](https://linux-hardware.org/?probe=8678eeac9b) | Jun 03, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9e1fe43cf9](https://linux-hardware.org/?probe=9e1fe43cf9) | Jun 03, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Notebook    | [e462733019](https://linux-hardware.org/?probe=e462733019) | May 29, 2023 |
| HP            | 0AECh D                     | Desktop     | [30868178ea](https://linux-hardware.org/?probe=30868178ea) | May 26, 2023 |
| HP            | ZBook 15                    | Notebook    | [def4482b86](https://linux-hardware.org/?probe=def4482b86) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [a3798147d9](https://linux-hardware.org/?probe=a3798147d9) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | Notebook    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [f2655b5798](https://linux-hardware.org/?probe=f2655b5798) | May 24, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [2bed616680](https://linux-hardware.org/?probe=2bed616680) | May 23, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [785f4bad86](https://linux-hardware.org/?probe=785f4bad86) | May 23, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63c991635f](https://linux-hardware.org/?probe=63c991635f) | May 17, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [46b31c9243](https://linux-hardware.org/?probe=46b31c9243) | May 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e21cdf9e37](https://linux-hardware.org/?probe=e21cdf9e37) | May 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed810bd154](https://linux-hardware.org/?probe=ed810bd154) | May 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [d6598957ff](https://linux-hardware.org/?probe=d6598957ff) | May 12, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [af31929040](https://linux-hardware.org/?probe=af31929040) | May 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [51eba04846](https://linux-hardware.org/?probe=51eba04846) | May 08, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [b4e9bb9147](https://linux-hardware.org/?probe=b4e9bb9147) | May 07, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [c223c83063](https://linux-hardware.org/?probe=c223c83063) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [983ec204ab](https://linux-hardware.org/?probe=983ec204ab) | May 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [8a7ed180c0](https://linux-hardware.org/?probe=8a7ed180c0) | May 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3ba3358e4d](https://linux-hardware.org/?probe=3ba3358e4d) | May 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Dell          | Latitude E5520              | Notebook    | [43e2d970b5](https://linux-hardware.org/?probe=43e2d970b5) | Apr 30, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [f543ce6c65](https://linux-hardware.org/?probe=f543ce6c65) | Apr 29, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [261c116001](https://linux-hardware.org/?probe=261c116001) | Apr 28, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [f2b702b631](https://linux-hardware.org/?probe=f2b702b631) | Apr 28, 2023 |
| Dell          | Latitude 7420               | Notebook    | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| Dell          | 040DDP A00                  | Desktop     | [8595139862](https://linux-hardware.org/?probe=8595139862) | Apr 25, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [84ae892fb4](https://linux-hardware.org/?probe=84ae892fb4) | Apr 19, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [030eff02bb](https://linux-hardware.org/?probe=030eff02bb) | Apr 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [88b9080a8c](https://linux-hardware.org/?probe=88b9080a8c) | Apr 17, 2023 |
| Dell          | Latitude 7420               | Notebook    | [1b2360944e](https://linux-hardware.org/?probe=1b2360944e) | Apr 17, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [690ed7960a](https://linux-hardware.org/?probe=690ed7960a) | Apr 13, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [12f634cf42](https://linux-hardware.org/?probe=12f634cf42) | Apr 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63574c5adf](https://linux-hardware.org/?probe=63574c5adf) | Apr 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [beeb850c3b](https://linux-hardware.org/?probe=beeb850c3b) | Apr 09, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f2d5671ba5](https://linux-hardware.org/?probe=f2d5671ba5) | Apr 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e04829aef9](https://linux-hardware.org/?probe=e04829aef9) | Apr 06, 2023 |
| HP            | 21D0                        | Desktop     | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| ASUSTek       | G752VM                      | Notebook    | [13d6602e92](https://linux-hardware.org/?probe=13d6602e92) | Apr 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ab9916feea](https://linux-hardware.org/?probe=ab9916feea) | Apr 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7e97eb6308](https://linux-hardware.org/?probe=7e97eb6308) | Apr 01, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8e927ead89](https://linux-hardware.org/?probe=8e927ead89) | Mar 30, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [889ef05f86](https://linux-hardware.org/?probe=889ef05f86) | Mar 30, 2023 |
| Dell          | 0TP412                      | Desktop     | [f9f3e5cc04](https://linux-hardware.org/?probe=f9f3e5cc04) | Mar 29, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [2aff972d11](https://linux-hardware.org/?probe=2aff972d11) | Mar 27, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [4f8515b9ed](https://linux-hardware.org/?probe=4f8515b9ed) | Mar 27, 2023 |
| HP            | 0B54h D                     | Desktop     | [3edc678017](https://linux-hardware.org/?probe=3edc678017) | Mar 26, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [b49dbdfa77](https://linux-hardware.org/?probe=b49dbdfa77) | Mar 25, 2023 |
| Timi          | A35S                        | Notebook    | [92022a5fa2](https://linux-hardware.org/?probe=92022a5fa2) | Mar 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5cbf68e6d](https://linux-hardware.org/?probe=f5cbf68e6d) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| HP            | 8715                        | Mini pc     | [9ce704a4b9](https://linux-hardware.org/?probe=9ce704a4b9) | Mar 23, 2023 |
| MSI           | GP72 7RE                    | Notebook    | [729f2297cb](https://linux-hardware.org/?probe=729f2297cb) | Mar 23, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [dab7a6edbc](https://linux-hardware.org/?probe=dab7a6edbc) | Mar 22, 2023 |
| Dell          | Latitude 7420               | Notebook    | [ac9a26d11c](https://linux-hardware.org/?probe=ac9a26d11c) | Mar 20, 2023 |
| HP            | 83E9                        | Desktop     | [a93c800fa1](https://linux-hardware.org/?probe=a93c800fa1) | Mar 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c462ccc41a](https://linux-hardware.org/?probe=c462ccc41a) | Mar 19, 2023 |
| Samsung       | 940XFG                      | Notebook    | [566a4046f6](https://linux-hardware.org/?probe=566a4046f6) | Mar 18, 2023 |
| Dell          | 0JP3NX A00                  | Desktop     | [9d0ac027df](https://linux-hardware.org/?probe=9d0ac027df) | Mar 14, 2023 |
| Google        | Reks                        | Notebook    | [56296236c5](https://linux-hardware.org/?probe=56296236c5) | Mar 12, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [f6da200721](https://linux-hardware.org/?probe=f6da200721) | Mar 11, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [56e5783575](https://linux-hardware.org/?probe=56e5783575) | Mar 11, 2023 |
| HP            | ProBook 4330s               | Notebook    | [00d887061a](https://linux-hardware.org/?probe=00d887061a) | Mar 10, 2023 |
| Google        | Reks                        | Notebook    | [f877db79d3](https://linux-hardware.org/?probe=f877db79d3) | Mar 09, 2023 |
| Intel         | ArcherCity                  | Server      | [3ddb00da94](https://linux-hardware.org/?probe=3ddb00da94) | Mar 08, 2023 |
| ASRock        | X99 Extreme4                | Desktop     | [a541fe5881](https://linux-hardware.org/?probe=a541fe5881) | Mar 07, 2023 |
| Dell          | Latitude 7420               | Notebook    | [00ef839a27](https://linux-hardware.org/?probe=00ef839a27) | Mar 06, 2023 |
| Dell          | Latitude 7420               | Notebook    | [18b4bfe200](https://linux-hardware.org/?probe=18b4bfe200) | Mar 06, 2023 |
| Dell          | 0JC474                      | Desktop     | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| Intel         | NUC7i5BNB J31144-313        | Mini pc     | [8078d7ca28](https://linux-hardware.org/?probe=8078d7ca28) | Mar 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [d70aeca173](https://linux-hardware.org/?probe=d70aeca173) | Mar 04, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a23a00a71e](https://linux-hardware.org/?probe=a23a00a71e) | Mar 02, 2023 |
| Dell          | Latitude 7420               | Notebook    | [49bdd8711f](https://linux-hardware.org/?probe=49bdd8711f) | Mar 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [2b007293f7](https://linux-hardware.org/?probe=2b007293f7) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bd415a086a](https://linux-hardware.org/?probe=bd415a086a) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [dcaa80ec62](https://linux-hardware.org/?probe=dcaa80ec62) | Mar 01, 2023 |
| HP            | EliteBook 755 G5            | Notebook    | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Intel         | NUC7i5BNB J31144-313        | Mini pc     | [91405b88cc](https://linux-hardware.org/?probe=91405b88cc) | Feb 27, 2023 |
| Dell          | Latitude 7420               | Notebook    | [d3af27a0ac](https://linux-hardware.org/?probe=d3af27a0ac) | Feb 27, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d032f0a547](https://linux-hardware.org/?probe=d032f0a547) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [b6f7c77e33](https://linux-hardware.org/?probe=b6f7c77e33) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | Notebook    | [bb18722cf2](https://linux-hardware.org/?probe=bb18722cf2) | Feb 21, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [1d62ae4e43](https://linux-hardware.org/?probe=1d62ae4e43) | Feb 20, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [813066eda5](https://linux-hardware.org/?probe=813066eda5) | Feb 19, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [0496d0bbcf](https://linux-hardware.org/?probe=0496d0bbcf) | Feb 18, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [ba5a46ec10](https://linux-hardware.org/?probe=ba5a46ec10) | Feb 18, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [fdab522500](https://linux-hardware.org/?probe=fdab522500) | Feb 17, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [dd863b4bdf](https://linux-hardware.org/?probe=dd863b4bdf) | Feb 17, 2023 |
| Foxconn       | H67M-S/H67M-V/H67M          | Desktop     | [78dc1c5856](https://linux-hardware.org/?probe=78dc1c5856) | Feb 17, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [8de835c5da](https://linux-hardware.org/?probe=8de835c5da) | Feb 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fb6daef60c](https://linux-hardware.org/?probe=fb6daef60c) | Feb 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3206e7be82](https://linux-hardware.org/?probe=3206e7be82) | Feb 16, 2023 |
| Lenovo        | Larne CRB 31900058 WIN 2... | All in one  | [4891d8306b](https://linux-hardware.org/?probe=4891d8306b) | Feb 15, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [73f7fb3f85](https://linux-hardware.org/?probe=73f7fb3f85) | Feb 15, 2023 |
| Dell          | G15 5520                    | Notebook    | [a5966eaac0](https://linux-hardware.org/?probe=a5966eaac0) | Feb 15, 2023 |
| Dell          | G3 3779                     | Notebook    | [cc77f75f3d](https://linux-hardware.org/?probe=cc77f75f3d) | Feb 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [011e8929fa](https://linux-hardware.org/?probe=011e8929fa) | Feb 15, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [e689bce0ca](https://linux-hardware.org/?probe=e689bce0ca) | Feb 14, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [bc1c7ec97f](https://linux-hardware.org/?probe=bc1c7ec97f) | Feb 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7e81f35584](https://linux-hardware.org/?probe=7e81f35584) | Feb 13, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [b1b8672218](https://linux-hardware.org/?probe=b1b8672218) | Feb 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [537d29b0d5](https://linux-hardware.org/?probe=537d29b0d5) | Feb 12, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [08820689e8](https://linux-hardware.org/?probe=08820689e8) | Feb 11, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c17ac89917](https://linux-hardware.org/?probe=c17ac89917) | Feb 11, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [a53ab3e915](https://linux-hardware.org/?probe=a53ab3e915) | Feb 10, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [181833b556](https://linux-hardware.org/?probe=181833b556) | Feb 09, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [6a589cafec](https://linux-hardware.org/?probe=6a589cafec) | Feb 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [43b52ad56f](https://linux-hardware.org/?probe=43b52ad56f) | Feb 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [275ce1a7fc](https://linux-hardware.org/?probe=275ce1a7fc) | Feb 08, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef988ae85](https://linux-hardware.org/?probe=aef988ae85) | Feb 07, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0f24e9c32c](https://linux-hardware.org/?probe=0f24e9c32c) | Feb 04, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a838bfb720](https://linux-hardware.org/?probe=a838bfb720) | Feb 04, 2023 |
| Shenzhen W... | AERO 5 Lite Mini PC         | Mini pc     | [cd8f74acd2](https://linux-hardware.org/?probe=cd8f74acd2) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [e07858d71e](https://linux-hardware.org/?probe=e07858d71e) | Feb 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [50727dbbde](https://linux-hardware.org/?probe=50727dbbde) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0b0eaa5c48](https://linux-hardware.org/?probe=0b0eaa5c48) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe2d2d279](https://linux-hardware.org/?probe=2fe2d2d279) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [995da6b474](https://linux-hardware.org/?probe=995da6b474) | Jan 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [0323a2bd47](https://linux-hardware.org/?probe=0323a2bd47) | Jan 27, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [a0493c6731](https://linux-hardware.org/?probe=a0493c6731) | Jan 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [06f87714b0](https://linux-hardware.org/?probe=06f87714b0) | Jan 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe7cc7865](https://linux-hardware.org/?probe=2fe7cc7865) | Jan 25, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [8ae5c7adec](https://linux-hardware.org/?probe=8ae5c7adec) | Jan 25, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [b87a9b3447](https://linux-hardware.org/?probe=b87a9b3447) | Jan 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c7c957ccb3](https://linux-hardware.org/?probe=c7c957ccb3) | Jan 25, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [7b23698a1e](https://linux-hardware.org/?probe=7b23698a1e) | Jan 24, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [09735072af](https://linux-hardware.org/?probe=09735072af) | Jan 23, 2023 |
| Dell          | Latitude 7420               | Notebook    | [dc99eb6c92](https://linux-hardware.org/?probe=dc99eb6c92) | Jan 23, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4f65820da4](https://linux-hardware.org/?probe=4f65820da4) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [01e83b7640](https://linux-hardware.org/?probe=01e83b7640) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [70b4ca8de7](https://linux-hardware.org/?probe=70b4ca8de7) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [7fb655b498](https://linux-hardware.org/?probe=7fb655b498) | Jan 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [397b4da9ab](https://linux-hardware.org/?probe=397b4da9ab) | Jan 21, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [93932bdc92](https://linux-hardware.org/?probe=93932bdc92) | Jan 20, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2ad3ad8258](https://linux-hardware.org/?probe=2ad3ad8258) | Jan 20, 2023 |
| Dell          | G5 5590                     | Notebook    | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude 5510               | Notebook    | [c9738f8691](https://linux-hardware.org/?probe=c9738f8691) | Jan 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [b5b4cde08e](https://linux-hardware.org/?probe=b5b4cde08e) | Jan 18, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [fa1a881ee9](https://linux-hardware.org/?probe=fa1a881ee9) | Jan 17, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [6941e3520e](https://linux-hardware.org/?probe=6941e3520e) | Jan 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [24d62d6974](https://linux-hardware.org/?probe=24d62d6974) | Jan 17, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [5905971b70](https://linux-hardware.org/?probe=5905971b70) | Jan 16, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [389b01b49a](https://linux-hardware.org/?probe=389b01b49a) | Jan 14, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4c3d300ccc](https://linux-hardware.org/?probe=4c3d300ccc) | Jan 14, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1ad37ae4cc](https://linux-hardware.org/?probe=1ad37ae4cc) | Jan 13, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [dc468fd3a8](https://linux-hardware.org/?probe=dc468fd3a8) | Jan 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [d390e11930](https://linux-hardware.org/?probe=d390e11930) | Jan 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [a181d83115](https://linux-hardware.org/?probe=a181d83115) | Jan 11, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4ce659b05d](https://linux-hardware.org/?probe=4ce659b05d) | Jan 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| Dell          | Latitude E7240              | Notebook    | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| Star Labs     | Lite                        | Notebook    | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef797585c](https://linux-hardware.org/?probe=aef797585c) | Jan 09, 2023 |
| Dell          | Latitude 7420               | Notebook    | [cd159088a3](https://linux-hardware.org/?probe=cd159088a3) | Jan 09, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [ec306ce0f9](https://linux-hardware.org/?probe=ec306ce0f9) | Jan 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [81269f2363](https://linux-hardware.org/?probe=81269f2363) | Jan 04, 2023 |
| Dell          | 0JP3NX A00                  | Desktop     | [21b5ec2d81](https://linux-hardware.org/?probe=21b5ec2d81) | Jan 03, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [1b8d741ea3](https://linux-hardware.org/?probe=1b8d741ea3) | Jan 03, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a51048ad0a](https://linux-hardware.org/?probe=a51048ad0a) | Jan 01, 2023 |
| Samsung       | 940XFG                      | Notebook    | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e7ac43e8c3](https://linux-hardware.org/?probe=e7ac43e8c3) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4d613961a4](https://linux-hardware.org/?probe=4d613961a4) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1780cf9c13](https://linux-hardware.org/?probe=1780cf9c13) | Dec 29, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c93684da4d](https://linux-hardware.org/?probe=c93684da4d) | Dec 29, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5c9cadd190](https://linux-hardware.org/?probe=5c9cadd190) | Dec 28, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5ea84f62cb](https://linux-hardware.org/?probe=5ea84f62cb) | Dec 25, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3fc3ad1b46](https://linux-hardware.org/?probe=3fc3ad1b46) | Dec 25, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [afb738446f](https://linux-hardware.org/?probe=afb738446f) | Dec 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [91a9d07c9f](https://linux-hardware.org/?probe=91a9d07c9f) | Dec 22, 2022 |
| Intel         | DQ77CP AAG67261-300         | Desktop     | [908f619aa7](https://linux-hardware.org/?probe=908f619aa7) | Dec 21, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0b63acf3b2](https://linux-hardware.org/?probe=0b63acf3b2) | Dec 20, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [660c9e5023](https://linux-hardware.org/?probe=660c9e5023) | Dec 20, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [54fbda3732](https://linux-hardware.org/?probe=54fbda3732) | Dec 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [da494e2be3](https://linux-hardware.org/?probe=da494e2be3) | Dec 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1bd00059e2](https://linux-hardware.org/?probe=1bd00059e2) | Dec 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7236ad8a5d](https://linux-hardware.org/?probe=7236ad8a5d) | Dec 17, 2022 |
| Dell          | Latitude 7420               | Notebook    | [60f07d5a45](https://linux-hardware.org/?probe=60f07d5a45) | Dec 16, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2991f8736b](https://linux-hardware.org/?probe=2991f8736b) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [69776fdb13](https://linux-hardware.org/?probe=69776fdb13) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [09c89a9bef](https://linux-hardware.org/?probe=09c89a9bef) | Dec 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed707b6698](https://linux-hardware.org/?probe=ed707b6698) | Dec 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c91212b8ed](https://linux-hardware.org/?probe=c91212b8ed) | Dec 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [88196a712d](https://linux-hardware.org/?probe=88196a712d) | Dec 07, 2022 |
| Dynabook      | Satellite Pro C50-H-11G     | Notebook    | [57e8e4ab79](https://linux-hardware.org/?probe=57e8e4ab79) | Dec 06, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |
| Dell          | Latitude 7290               | Notebook    | [3f0e476980](https://linux-hardware.org/?probe=3f0e476980) | Dec 04, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Toshiba       | Satellite C50D-A-138        | Notebook    | [ccda846d5e](https://linux-hardware.org/?probe=ccda846d5e) | Dec 03, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [9887f68589](https://linux-hardware.org/?probe=9887f68589) | Dec 03, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [7bdc87a5cc](https://linux-hardware.org/?probe=7bdc87a5cc) | Dec 02, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [d17ff52554](https://linux-hardware.org/?probe=d17ff52554) | Dec 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [080e04d17d](https://linux-hardware.org/?probe=080e04d17d) | Dec 02, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c4ae439087](https://linux-hardware.org/?probe=c4ae439087) | Nov 30, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5c395ef8a4](https://linux-hardware.org/?probe=5c395ef8a4) | Nov 26, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [0c97f1e481](https://linux-hardware.org/?probe=0c97f1e481) | Nov 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [90fcc2d8d5](https://linux-hardware.org/?probe=90fcc2d8d5) | Nov 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [2c077b8cde](https://linux-hardware.org/?probe=2c077b8cde) | Nov 23, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [587e23a674](https://linux-hardware.org/?probe=587e23a674) | Nov 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f58f70b732](https://linux-hardware.org/?probe=f58f70b732) | Nov 19, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [7bf0186e00](https://linux-hardware.org/?probe=7bf0186e00) | Nov 18, 2022 |
| Chuwi         | X312B                       | Notebook    | [b0c9263212](https://linux-hardware.org/?probe=b0c9263212) | Nov 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4ac6dbf9b](https://linux-hardware.org/?probe=a4ac6dbf9b) | Nov 17, 2022 |
| Chuwi         | X312B                       | Notebook    | [7583d01bd8](https://linux-hardware.org/?probe=7583d01bd8) | Nov 15, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c3cacc3ed6](https://linux-hardware.org/?probe=c3cacc3ed6) | Nov 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [11dbbdfcc1](https://linux-hardware.org/?probe=11dbbdfcc1) | Nov 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [02aab6ab70](https://linux-hardware.org/?probe=02aab6ab70) | Nov 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [a174d2b2b3](https://linux-hardware.org/?probe=a174d2b2b3) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [ed3f6fb61d](https://linux-hardware.org/?probe=ed3f6fb61d) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [c1805091ef](https://linux-hardware.org/?probe=c1805091ef) | Nov 12, 2022 |
| Chuwi         | X312B                       | Notebook    | [0e6a368329](https://linux-hardware.org/?probe=0e6a368329) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5d2ae18b0a](https://linux-hardware.org/?probe=5d2ae18b0a) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [51a3c87183](https://linux-hardware.org/?probe=51a3c87183) | Nov 10, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [74a1e6875a](https://linux-hardware.org/?probe=74a1e6875a) | Nov 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c03daa3621](https://linux-hardware.org/?probe=c03daa3621) | Nov 08, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | Notebook    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [bf3996f87d](https://linux-hardware.org/?probe=bf3996f87d) | Nov 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a5700bebdf](https://linux-hardware.org/?probe=a5700bebdf) | Nov 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5d89464b05](https://linux-hardware.org/?probe=5d89464b05) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4354f496c](https://linux-hardware.org/?probe=a4354f496c) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5cf615d5b2](https://linux-hardware.org/?probe=5cf615d5b2) | Nov 02, 2022 |
| MSI           | Z170M MORTAR                | Desktop     | [041dbc2c18](https://linux-hardware.org/?probe=041dbc2c18) | Oct 31, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1d4a6dc6dc](https://linux-hardware.org/?probe=1d4a6dc6dc) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [a1694d3adc](https://linux-hardware.org/?probe=a1694d3adc) | Oct 29, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [ae536fa220](https://linux-hardware.org/?probe=ae536fa220) | Oct 27, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [8b457c11e8](https://linux-hardware.org/?probe=8b457c11e8) | Oct 23, 2022 |
| Dell          | Latitude E6440              | Notebook    | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| Dell          | Latitude 7400               | Notebook    | [3b340aa7d4](https://linux-hardware.org/?probe=3b340aa7d4) | Oct 12, 2022 |
| Dell          | Latitude 7400               | Notebook    | [159021ed29](https://linux-hardware.org/?probe=159021ed29) | Oct 12, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [e464adc2d9](https://linux-hardware.org/?probe=e464adc2d9) | Oct 11, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [ffda659565](https://linux-hardware.org/?probe=ffda659565) | Oct 11, 2022 |
| MSI           | MS-7A34                     | Notebook    | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| HP            | 21D0                        | Desktop     | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [26df10ca7d](https://linux-hardware.org/?probe=26df10ca7d) | Oct 02, 2022 |
| Timi          | TM1709                      | Notebook    | [33022811a8](https://linux-hardware.org/?probe=33022811a8) | Oct 01, 2022 |
| Dell          | Latitude 7420               | Notebook    | [0834411088](https://linux-hardware.org/?probe=0834411088) | Sep 26, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [59d0400171](https://linux-hardware.org/?probe=59d0400171) | Sep 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [172fd1874d](https://linux-hardware.org/?probe=172fd1874d) | Sep 20, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [da0b586e04](https://linux-hardware.org/?probe=da0b586e04) | Sep 20, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b389a760a8](https://linux-hardware.org/?probe=b389a760a8) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| Dell          | 0TP412                      | Desktop     | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| HP            | Pavilion m6                 | Notebook    | [83b6eb0119](https://linux-hardware.org/?probe=83b6eb0119) | Sep 01, 2022 |
| Medion        | E6227                       | Notebook    | [e6ca2257e7](https://linux-hardware.org/?probe=e6ca2257e7) | Sep 01, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Apple         | Mac-F2218FA9                | All in one  | [296fc14c83](https://linux-hardware.org/?probe=296fc14c83) | Aug 26, 2022 |
| Framework     | Laptop                      | Notebook    | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| Framework     | Laptop                      | Notebook    | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ae65121050](https://linux-hardware.org/?probe=ae65121050) | Aug 23, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [caf9167ca7](https://linux-hardware.org/?probe=caf9167ca7) | Aug 16, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [6d1b561c11](https://linux-hardware.org/?probe=6d1b561c11) | Aug 16, 2022 |
| HP            | EliteBook 755 G5            | Notebook    | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 9320                    | Notebook    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| Dell          | XPS 9320                    | Notebook    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3f462439ed](https://linux-hardware.org/?probe=3f462439ed) | Aug 11, 2022 |
| Samsung       | 935XDB                      | Notebook    | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [531e4340a6](https://linux-hardware.org/?probe=531e4340a6) | Aug 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bd2dbeaa0e](https://linux-hardware.org/?probe=bd2dbeaa0e) | Aug 02, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d83f785b08](https://linux-hardware.org/?probe=d83f785b08) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Samsung       | 935XDB                      | Notebook    | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Dell          | 0V8WGR A01                  | Desktop     | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [033c284273](https://linux-hardware.org/?probe=033c284273) | Jul 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8d0399bc8d](https://linux-hardware.org/?probe=8d0399bc8d) | Jul 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ef61582503](https://linux-hardware.org/?probe=ef61582503) | Jul 16, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| Jumper        | EZbook                      | Notebook    | [5e7336ee93](https://linux-hardware.org/?probe=5e7336ee93) | Jul 02, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ca7efa311a](https://linux-hardware.org/?probe=ca7efa311a) | Jul 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [282d2ad16b](https://linux-hardware.org/?probe=282d2ad16b) | Jun 29, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [d4543f64dc](https://linux-hardware.org/?probe=d4543f64dc) | Jun 24, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [57e0198d3a](https://linux-hardware.org/?probe=57e0198d3a) | Jun 23, 2022 |
| Samsung       | 935XDB                      | Notebook    | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [5caa4002f1](https://linux-hardware.org/?probe=5caa4002f1) | Jun 17, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [028b64776a](https://linux-hardware.org/?probe=028b64776a) | Jun 15, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [eef8a87283](https://linux-hardware.org/?probe=eef8a87283) | Jun 15, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [674cb88747](https://linux-hardware.org/?probe=674cb88747) | Jun 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c1bde29740](https://linux-hardware.org/?probe=c1bde29740) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| Samsung       | 935XDB                      | Notebook    | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | Notebook    | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| Dell          | Latitude 9420               | Notebook    | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| ASUSTek       | Maximus VII IMPACT          | Desktop     | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [522da9476b](https://linux-hardware.org/?probe=522da9476b) | May 29, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [07b116767e](https://linux-hardware.org/?probe=07b116767e) | May 27, 2022 |
| Dell          | Latitude D520               | Notebook    | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| ASUSTek       | UX330UAK                    | Notebook    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [8471800bb3](https://linux-hardware.org/?probe=8471800bb3) | May 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [373e009d3b](https://linux-hardware.org/?probe=373e009d3b) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [6836f79bdf](https://linux-hardware.org/?probe=6836f79bdf) | May 08, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [41cc4d30d4](https://linux-hardware.org/?probe=41cc4d30d4) | May 08, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | H55M-E23                    | Desktop     | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5e1b40c8b5](https://linux-hardware.org/?probe=5e1b40c8b5) | Apr 25, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | Notebook    | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | Notebook    | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [346c9b6c59](https://linux-hardware.org/?probe=346c9b6c59) | Apr 14, 2022 |
| Dell          | Latitude E6520              | Notebook    | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Lenovo        | 312A SDK0J40700 WIN 3258... | Desktop     | [a645768047](https://linux-hardware.org/?probe=a645768047) | Apr 05, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | Notebook    | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0f98a36a43](https://linux-hardware.org/?probe=0f98a36a43) | Mar 30, 2022 |
| Dell          | Latitude E5440              | Notebook    | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [c185ef78b1](https://linux-hardware.org/?probe=c185ef78b1) | Mar 22, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [45c6461d6c](https://linux-hardware.org/?probe=45c6461d6c) | Mar 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| Rockchip      | Unknown                     | Soc         | [fcef507e8e](https://linux-hardware.org/?probe=fcef507e8e) | Mar 18, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5723ec8b7](https://linux-hardware.org/?probe=f5723ec8b7) | Mar 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [27548876c6](https://linux-hardware.org/?probe=27548876c6) | Mar 11, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4c4afb883e](https://linux-hardware.org/?probe=4c4afb883e) | Mar 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0eaf02ff7d](https://linux-hardware.org/?probe=0eaf02ff7d) | Mar 07, 2022 |
| Dell          | Latitude 9420               | Notebook    | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [34b97f062b](https://linux-hardware.org/?probe=34b97f062b) | Mar 01, 2022 |
| HP            | 21D0                        | Desktop     | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [6dd3795cad](https://linux-hardware.org/?probe=6dd3795cad) | Feb 24, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Dell          | Precision M4600             | Notebook    | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Acer          | Predator PH317-54           | Notebook    | [8fb9ac25be](https://linux-hardware.org/?probe=8fb9ac25be) | Feb 11, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ace22bd471](https://linux-hardware.org/?probe=ace22bd471) | Feb 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb5bd32928](https://linux-hardware.org/?probe=bb5bd32928) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2c93e69093](https://linux-hardware.org/?probe=2c93e69093) | Feb 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [45922e4586](https://linux-hardware.org/?probe=45922e4586) | Feb 04, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480s 20L7S0VJ0... | Notebook    | [7535369bb0](https://linux-hardware.org/?probe=7535369bb0) | Jan 31, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4cdd6daf44](https://linux-hardware.org/?probe=4cdd6daf44) | Jan 19, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c8932dbfd0](https://linux-hardware.org/?probe=c8932dbfd0) | Jan 15, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [ab40e8dd7d](https://linux-hardware.org/?probe=ab40e8dd7d) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8c319cd6fc](https://linux-hardware.org/?probe=8c319cd6fc) | Jan 11, 2022 |
| Notebook      | P15SM                       | Notebook    | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4fad903d2a](https://linux-hardware.org/?probe=4fad903d2a) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| Dell          | Latitude 5411               | Notebook    | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [4894e2c956](https://linux-hardware.org/?probe=4894e2c956) | Jan 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aea80bda1f](https://linux-hardware.org/?probe=aea80bda1f) | Jan 01, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4161b37157](https://linux-hardware.org/?probe=4161b37157) | Dec 30, 2021 |
| Lenovo        | ThinkPad X220 4291W99       | Notebook    | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [296af779e4](https://linux-hardware.org/?probe=296af779e4) | Dec 20, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7230ad27b7](https://linux-hardware.org/?probe=7230ad27b7) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7b6327d329](https://linux-hardware.org/?probe=7b6327d329) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| AVITA         | NS14A8                      | Notebook    | [0ae2523309](https://linux-hardware.org/?probe=0ae2523309) | Dec 18, 2021 |
| Nvidia        | Tegra                       | Soc         | [30c09e0585](https://linux-hardware.org/?probe=30c09e0585) | Dec 17, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| HP            | 1495                        | Desktop     | [489e740957](https://linux-hardware.org/?probe=489e740957) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [69b4695e8d](https://linux-hardware.org/?probe=69b4695e8d) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| Acer          | AOD255                      | Notebook    | [eae98753db](https://linux-hardware.org/?probe=eae98753db) | Dec 03, 2021 |
| Acer          | AOD255                      | Notebook    | [d2e31c1441](https://linux-hardware.org/?probe=d2e31c1441) | Dec 02, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [291a2a17e2](https://linux-hardware.org/?probe=291a2a17e2) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bb51358294](https://linux-hardware.org/?probe=bb51358294) | Nov 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [0424bd331e](https://linux-hardware.org/?probe=0424bd331e) | Nov 10, 2021 |
| HP            | Notebook                    | Notebook    | [65c122fe69](https://linux-hardware.org/?probe=65c122fe69) | Oct 31, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [00ac329183](https://linux-hardware.org/?probe=00ac329183) | Oct 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [22bc284f45](https://linux-hardware.org/?probe=22bc284f45) | Oct 27, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [3e574fa012](https://linux-hardware.org/?probe=3e574fa012) | Oct 25, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4add26ac8c](https://linux-hardware.org/?probe=4add26ac8c) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| HP            | 21D0                        | Desktop     | [1dbb2b4a2d](https://linux-hardware.org/?probe=1dbb2b4a2d) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| ASUSTek       | X501A1                      | Notebook    | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [74cbbcac9f](https://linux-hardware.org/?probe=74cbbcac9f) | Oct 07, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [f564d05797](https://linux-hardware.org/?probe=f564d05797) | Oct 05, 2021 |
| MSI           | MS-7270                     | Desktop     | [4281e009bb](https://linux-hardware.org/?probe=4281e009bb) | Oct 05, 2021 |
| HP            | 1998                        | Desktop     | [74a28b051a](https://linux-hardware.org/?probe=74a28b051a) | Oct 03, 2021 |
| Apple         | MacBookPro5,3               | Notebook    | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| Timi          | TM1607                      | Notebook    | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [5acbf68626](https://linux-hardware.org/?probe=5acbf68626) | Sep 25, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| HP            | Notebook                    | Notebook    | [9c7d616423](https://linux-hardware.org/?probe=9c7d616423) | Sep 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [7500e17316](https://linux-hardware.org/?probe=7500e17316) | Sep 11, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [3a55618aee](https://linux-hardware.org/?probe=3a55618aee) | Sep 10, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [feec038877](https://linux-hardware.org/?probe=feec038877) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c5fbf3298a](https://linux-hardware.org/?probe=c5fbf3298a) | Sep 06, 2021 |
| Lenovo        | ThinkPad E15 20RD0015FR     | Notebook    | [8a229968ef](https://linux-hardware.org/?probe=8a229968ef) | Sep 06, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c483c45fc4](https://linux-hardware.org/?probe=c483c45fc4) | Sep 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f1b601400c](https://linux-hardware.org/?probe=f1b601400c) | Sep 01, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [88012fdf33](https://linux-hardware.org/?probe=88012fdf33) | Aug 30, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Dell          | Precision 5550              | Notebook    | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Medion        | Akoya E6239                 | Notebook    | [e22d5c4b21](https://linux-hardware.org/?probe=e22d5c4b21) | Aug 20, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [f5d2b51d19](https://linux-hardware.org/?probe=f5d2b51d19) | Aug 16, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Dell          | 0X9M3X A01                  | Desktop     | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1ea279df08](https://linux-hardware.org/?probe=1ea279df08) | Aug 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [32e0ae8af0](https://linux-hardware.org/?probe=32e0ae8af0) | Aug 03, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [f8c48b22e6](https://linux-hardware.org/?probe=f8c48b22e6) | Aug 02, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | Notebook    | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [69869dec40](https://linux-hardware.org/?probe=69869dec40) | Jul 27, 2021 |
| Dell          | Studio XPS 1640             | Notebook    | [00d5936a25](https://linux-hardware.org/?probe=00d5936a25) | Jul 22, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [77ab0c578d](https://linux-hardware.org/?probe=77ab0c578d) | Jul 17, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [06ba47ee9a](https://linux-hardware.org/?probe=06ba47ee9a) | Jul 17, 2021 |
| ASRock        | J4105M                      | Desktop     | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | Desktop     | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| Dell          | Latitude 7370               | Notebook    | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | Notebook    | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| ASRock        | Z77 Extreme3                | Desktop     | [ecd7ec8f36](https://linux-hardware.org/?probe=ecd7ec8f36) | Jul 02, 2021 |
| Entroware     | Apollo                      | Notebook    | [3cbf412b11](https://linux-hardware.org/?probe=3cbf412b11) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fff9c1a758](https://linux-hardware.org/?probe=fff9c1a758) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [3980434b64](https://linux-hardware.org/?probe=3980434b64) | Jun 19, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [27fea5c8cb](https://linux-hardware.org/?probe=27fea5c8cb) | Jun 12, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [1ccc05a479](https://linux-hardware.org/?probe=1ccc05a479) | Jun 09, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f8241fa3ce](https://linux-hardware.org/?probe=f8241fa3ce) | Jun 08, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| Dell          | Latitude C810               | Notebook    | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [62b30f282d](https://linux-hardware.org/?probe=62b30f282d) | Jun 04, 2021 |
| Dell          | Latitude C810               | Notebook    | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [6c770833c9](https://linux-hardware.org/?probe=6c770833c9) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | Notebook    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [6fff0f3407](https://linux-hardware.org/?probe=6fff0f3407) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [cfa1b1a4fd](https://linux-hardware.org/?probe=cfa1b1a4fd) | Jun 03, 2021 |
| Dell          | 07F37C A01                  | Desktop     | [baba8a29ac](https://linux-hardware.org/?probe=baba8a29ac) | Jun 02, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [a41c941365](https://linux-hardware.org/?probe=a41c941365) | Jun 02, 2021 |
| Entroware     | Proteus                     | Notebook    | [0ecc547a14](https://linux-hardware.org/?probe=0ecc547a14) | May 31, 2021 |
| MSI           | MS-7270                     | Desktop     | [7cc66e3a90](https://linux-hardware.org/?probe=7cc66e3a90) | May 29, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3c83289b45](https://linux-hardware.org/?probe=3c83289b45) | May 28, 2021 |
| HP            | Pavilion 15                 | Notebook    | [14128860c2](https://linux-hardware.org/?probe=14128860c2) | May 27, 2021 |
| HP            | ProBook 6550b               | Notebook    | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [e7292a5491](https://linux-hardware.org/?probe=e7292a5491) | May 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 3397                        | Desktop     | [ae9a8581c5](https://linux-hardware.org/?probe=ae9a8581c5) | May 23, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [f7c5833c2a](https://linux-hardware.org/?probe=f7c5833c2a) | May 23, 2021 |
| HP            | 15                          | Notebook    | [ab211b6ad8](https://linux-hardware.org/?probe=ab211b6ad8) | May 21, 2021 |
| HP            | 15                          | Notebook    | [d285154a2b](https://linux-hardware.org/?probe=d285154a2b) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| HP            | 18E5                        | Desktop     | [6cbae0f799](https://linux-hardware.org/?probe=6cbae0f799) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ea97f7d05d](https://linux-hardware.org/?probe=ea97f7d05d) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [824ec14630](https://linux-hardware.org/?probe=824ec14630) | May 20, 2021 |
| Entroware     | Proteus                     | Notebook    | [98be1903c4](https://linux-hardware.org/?probe=98be1903c4) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | Latitude 5520               | Notebook    | [34c3dc01e9](https://linux-hardware.org/?probe=34c3dc01e9) | May 07, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [452f706571](https://linux-hardware.org/?probe=452f706571) | May 07, 2021 |
| HP            | HDX 18                      | Notebook    | [dead2b5b56](https://linux-hardware.org/?probe=dead2b5b56) | May 07, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [d1d4f84e0a](https://linux-hardware.org/?probe=d1d4f84e0a) | May 03, 2021 |
| HP            | EliteBook Folio G1          | Notebook    | [f3bdc3e991](https://linux-hardware.org/?probe=f3bdc3e991) | Apr 24, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [fe576d54b4](https://linux-hardware.org/?probe=fe576d54b4) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [e651f5da2c](https://linux-hardware.org/?probe=e651f5da2c) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [be651d63a0](https://linux-hardware.org/?probe=be651d63a0) | Apr 19, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9c0bbd0e0c](https://linux-hardware.org/?probe=9c0bbd0e0c) | Apr 18, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [0ceacbca21](https://linux-hardware.org/?probe=0ceacbca21) | Apr 17, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [8253ac8502](https://linux-hardware.org/?probe=8253ac8502) | Apr 10, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [2e946e600e](https://linux-hardware.org/?probe=2e946e600e) | Apr 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [51b67b480d](https://linux-hardware.org/?probe=51b67b480d) | Apr 05, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [93033ed87e](https://linux-hardware.org/?probe=93033ed87e) | Apr 04, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [6b926d1195](https://linux-hardware.org/?probe=6b926d1195) | Apr 04, 2021 |
| HP            | Pavilion g6                 | Notebook    | [726040b78b](https://linux-hardware.org/?probe=726040b78b) | Apr 03, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [6917221b5b](https://linux-hardware.org/?probe=6917221b5b) | Apr 02, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [9e21f67ab7](https://linux-hardware.org/?probe=9e21f67ab7) | Mar 28, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [9976792f0f](https://linux-hardware.org/?probe=9976792f0f) | Mar 26, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | Notebook    | [31a4336d63](https://linux-hardware.org/?probe=31a4336d63) | Mar 25, 2021 |
| Microtech     | e-book Lite                 | Notebook    | [85b6d19466](https://linux-hardware.org/?probe=85b6d19466) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [488904f6d8](https://linux-hardware.org/?probe=488904f6d8) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [7fbf31af63](https://linux-hardware.org/?probe=7fbf31af63) | Mar 18, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [1b571fd1c4](https://linux-hardware.org/?probe=1b571fd1c4) | Mar 18, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [e5a6c9dcb9](https://linux-hardware.org/?probe=e5a6c9dcb9) | Mar 17, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [8b0145ff0c](https://linux-hardware.org/?probe=8b0145ff0c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f2f15e9ef1](https://linux-hardware.org/?probe=f2f15e9ef1) | Mar 10, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [b035a149a3](https://linux-hardware.org/?probe=b035a149a3) | Mar 02, 2021 |
| Medion        | MS-7646                     | Desktop     | [5ca2e128b6](https://linux-hardware.org/?probe=5ca2e128b6) | Feb 24, 2021 |
| HP            | Pavilion m6                 | Notebook    | [578aad5ad5](https://linux-hardware.org/?probe=578aad5ad5) | Feb 24, 2021 |
| HP            | Notebook                    | Notebook    | [21ead6ec52](https://linux-hardware.org/?probe=21ead6ec52) | Feb 22, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [7dbba6ee59](https://linux-hardware.org/?probe=7dbba6ee59) | Feb 21, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8f2450a3b0](https://linux-hardware.org/?probe=8f2450a3b0) | Feb 20, 2021 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [2812d098fd](https://linux-hardware.org/?probe=2812d098fd) | Feb 20, 2021 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [ce0aecd52b](https://linux-hardware.org/?probe=ce0aecd52b) | Feb 20, 2021 |
| Dell          | 0WR7PY A03                  | Desktop     | [878e82f1a3](https://linux-hardware.org/?probe=878e82f1a3) | Feb 19, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [3bf39bac3e](https://linux-hardware.org/?probe=3bf39bac3e) | Feb 19, 2021 |
| Apple         | MacBookPro2,2               | Notebook    | [52f24b3228](https://linux-hardware.org/?probe=52f24b3228) | Feb 19, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [6fad2f0ade](https://linux-hardware.org/?probe=6fad2f0ade) | Feb 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [46556ad380](https://linux-hardware.org/?probe=46556ad380) | Feb 14, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [78c7860103](https://linux-hardware.org/?probe=78c7860103) | Feb 10, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [8647ccdbef](https://linux-hardware.org/?probe=8647ccdbef) | Feb 10, 2021 |
| MSI           | 2AE0                        | Desktop     | [374ff27ab8](https://linux-hardware.org/?probe=374ff27ab8) | Feb 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6ef4606f95](https://linux-hardware.org/?probe=6ef4606f95) | Feb 09, 2021 |
| HP            | 1495                        | Desktop     | [d8d36f4b2b](https://linux-hardware.org/?probe=d8d36f4b2b) | Feb 08, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [51ede3687a](https://linux-hardware.org/?probe=51ede3687a) | Feb 05, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [ec083139fc](https://linux-hardware.org/?probe=ec083139fc) | Feb 05, 2021 |
| Samsung       | Galaxy TabPro S             | Tablet      | [4e4ef907a0](https://linux-hardware.org/?probe=4e4ef907a0) | Feb 05, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [6c4261b08f](https://linux-hardware.org/?probe=6c4261b08f) | Feb 05, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b1ed72b941](https://linux-hardware.org/?probe=b1ed72b941) | Feb 04, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4502d7365](https://linux-hardware.org/?probe=d4502d7365) | Jan 28, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2c59be484e](https://linux-hardware.org/?probe=2c59be484e) | Jan 22, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [1dbf9cced7](https://linux-hardware.org/?probe=1dbf9cced7) | Jan 22, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [9ce5eab595](https://linux-hardware.org/?probe=9ce5eab595) | Jan 16, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [192f01dd70](https://linux-hardware.org/?probe=192f01dd70) | Jan 16, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | System XPS L502X            | Notebook    | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | Notebook    | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [54b2f4c522](https://linux-hardware.org/?probe=54b2f4c522) | Jan 11, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [d7528e4806](https://linux-hardware.org/?probe=d7528e4806) | Jan 09, 2021 |
| HUAWEI        | BOHL-WXX9                   | Notebook    | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | Notebook    | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [59440917d2](https://linux-hardware.org/?probe=59440917d2) | Jan 01, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [b6ffae8f7a](https://linux-hardware.org/?probe=b6ffae8f7a) | Dec 27, 2020 |
| HP            | 3032h                       | Desktop     | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| Dell          | System XPS L502X            | Notebook    | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [d1e772d769](https://linux-hardware.org/?probe=d1e772d769) | Dec 11, 2020 |
| Acer          | Aspire 5551                 | Notebook    | [cb35dac70b](https://linux-hardware.org/?probe=cb35dac70b) | Dec 09, 2020 |
| HP            | Notebook                    | Notebook    | [2564f14d0b](https://linux-hardware.org/?probe=2564f14d0b) | Dec 06, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [325dd21da3](https://linux-hardware.org/?probe=325dd21da3) | Nov 27, 2020 |
| MSI           | MS-7270                     | Desktop     | [b4e45eae99](https://linux-hardware.org/?probe=b4e45eae99) | Nov 26, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [703167df7b](https://linux-hardware.org/?probe=703167df7b) | Nov 24, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [04e06f0e3b](https://linux-hardware.org/?probe=04e06f0e3b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [f30611840c](https://linux-hardware.org/?probe=f30611840c) | Nov 23, 2020 |
| PC Special... | PCX0DX                      | Notebook    | [b4498047ef](https://linux-hardware.org/?probe=b4498047ef) | Nov 22, 2020 |
| Apple         | MacBookPro5,4               | Notebook    | [a7492067f0](https://linux-hardware.org/?probe=a7492067f0) | Nov 21, 2020 |
| HP            | EliteBook 820 G1            | Notebook    | [4db5c39f50](https://linux-hardware.org/?probe=4db5c39f50) | Nov 21, 2020 |
| Lenovo        | ThinkPad T400 64754G7       | Notebook    | [770660037c](https://linux-hardware.org/?probe=770660037c) | Nov 21, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [072b557a79](https://linux-hardware.org/?probe=072b557a79) | Nov 20, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [58fc01c757](https://linux-hardware.org/?probe=58fc01c757) | Nov 19, 2020 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [d8379e8abb](https://linux-hardware.org/?probe=d8379e8abb) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [578d1badca](https://linux-hardware.org/?probe=578d1badca) | Nov 18, 2020 |
| Alienware     | 17 R4                       | Notebook    | [8b7402a4e7](https://linux-hardware.org/?probe=8b7402a4e7) | Nov 16, 2020 |
| Alienware     | 17 R4                       | Notebook    | [62e5ac4fd3](https://linux-hardware.org/?probe=62e5ac4fd3) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| MSI           | MS-7270                     | Desktop     | [c70e52b025](https://linux-hardware.org/?probe=c70e52b025) | Nov 13, 2020 |
| Dell          | Latitude E6420              | Notebook    | [f542aafd19](https://linux-hardware.org/?probe=f542aafd19) | Nov 13, 2020 |
| HP            | 1495                        | Desktop     | [a250ea93d5](https://linux-hardware.org/?probe=a250ea93d5) | Nov 10, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [893477956d](https://linux-hardware.org/?probe=893477956d) | Nov 10, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [418e9ce805](https://linux-hardware.org/?probe=418e9ce805) | Nov 06, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [7780f8f320](https://linux-hardware.org/?probe=7780f8f320) | Nov 06, 2020 |
| MSI           | MS-7270                     | Desktop     | [97556dedc3](https://linux-hardware.org/?probe=97556dedc3) | Nov 05, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eac2b32ee0](https://linux-hardware.org/?probe=eac2b32ee0) | Nov 04, 2020 |
| System76      | Galago Pro                  | Notebook    | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| Dell          | XPS M1530                   | Notebook    | [bc52d9b9a4](https://linux-hardware.org/?probe=bc52d9b9a4) | Nov 03, 2020 |
| Dell          | Dimension 5100              | Desktop     | [f18393d9aa](https://linux-hardware.org/?probe=f18393d9aa) | Nov 03, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3be1cd15b1](https://linux-hardware.org/?probe=3be1cd15b1) | Oct 30, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [2496b738ac](https://linux-hardware.org/?probe=2496b738ac) | Oct 29, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [f875a122f9](https://linux-hardware.org/?probe=f875a122f9) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [e651ccb88e](https://linux-hardware.org/?probe=e651ccb88e) | Oct 29, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [0b113f8315](https://linux-hardware.org/?probe=0b113f8315) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [ba278ca133](https://linux-hardware.org/?probe=ba278ca133) | Oct 29, 2020 |
| Apple         | Mac-F2238AC8                | All in one  | [e9e4822309](https://linux-hardware.org/?probe=e9e4822309) | Oct 28, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0e16f54971](https://linux-hardware.org/?probe=0e16f54971) | Oct 28, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [0edec7c57f](https://linux-hardware.org/?probe=0edec7c57f) | Oct 27, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [21e26c80bc](https://linux-hardware.org/?probe=21e26c80bc) | Oct 27, 2020 |
| Dell          | Vostro 3700                 | Notebook    | [5493bcf45a](https://linux-hardware.org/?probe=5493bcf45a) | Oct 26, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [2db5bc3b28](https://linux-hardware.org/?probe=2db5bc3b28) | Oct 23, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [acc7a651ac](https://linux-hardware.org/?probe=acc7a651ac) | Oct 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [6aea9a482c](https://linux-hardware.org/?probe=6aea9a482c) | Oct 20, 2020 |
| HP            | 1497                        | Desktop     | [dea5079fad](https://linux-hardware.org/?probe=dea5079fad) | Oct 19, 2020 |
| Dell          | 0RY206                      | Desktop     | [4e0283b4c8](https://linux-hardware.org/?probe=4e0283b4c8) | Oct 18, 2020 |
| Dell          | 0RY206                      | Desktop     | [5d45dd253e](https://linux-hardware.org/?probe=5d45dd253e) | Oct 18, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [96ff229c4c](https://linux-hardware.org/?probe=96ff229c4c) | Oct 17, 2020 |
| HP            | 1497                        | Desktop     | [8dd5fc52bd](https://linux-hardware.org/?probe=8dd5fc52bd) | Oct 15, 2020 |
| Nvidia        | Tegra                       | Soc         | [9b157b83a5](https://linux-hardware.org/?probe=9b157b83a5) | Oct 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [bd7a8f0f96](https://linux-hardware.org/?probe=bd7a8f0f96) | Oct 15, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| Dell          | Dimension 5100              | Desktop     | [5b80714363](https://linux-hardware.org/?probe=5b80714363) | Oct 14, 2020 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ab8c149b9f](https://linux-hardware.org/?probe=ab8c149b9f) | Oct 14, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [08619ece44](https://linux-hardware.org/?probe=08619ece44) | Oct 14, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [598a9af3a1](https://linux-hardware.org/?probe=598a9af3a1) | Oct 12, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [d245d1c5a5](https://linux-hardware.org/?probe=d245d1c5a5) | Oct 06, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [1554f3d77d](https://linux-hardware.org/?probe=1554f3d77d) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [d1cf757d40](https://linux-hardware.org/?probe=d1cf757d40) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [2389a49dc0](https://linux-hardware.org/?probe=2389a49dc0) | Oct 05, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [1e8497692d](https://linux-hardware.org/?probe=1e8497692d) | Oct 02, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [c2148ec054](https://linux-hardware.org/?probe=c2148ec054) | Oct 01, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [c22330bac3](https://linux-hardware.org/?probe=c22330bac3) | Sep 26, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [58ce88778b](https://linux-hardware.org/?probe=58ce88778b) | Sep 23, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a2c5c1ea67](https://linux-hardware.org/?probe=a2c5c1ea67) | Sep 18, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [3eba500997](https://linux-hardware.org/?probe=3eba500997) | Sep 15, 2020 |
| HP            | G70                         | Notebook    | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [20c0d6785b](https://linux-hardware.org/?probe=20c0d6785b) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| HP            | 255 G2                      | Notebook    | [5d06b6eeff](https://linux-hardware.org/?probe=5d06b6eeff) | Sep 04, 2020 |
| Lenovo        | U410                        | Notebook    | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| Unknown       | RS780-SB700 Unknox          | Desktop     | [a084e40027](https://linux-hardware.org/?probe=a084e40027) | Aug 30, 2020 |
| Gigabyte      | GA-MA790X-UD3P              | Desktop     | [f5a642ebbb](https://linux-hardware.org/?probe=f5a642ebbb) | Aug 28, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [f710d270fe](https://linux-hardware.org/?probe=f710d270fe) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [f25aa5934e](https://linux-hardware.org/?probe=f25aa5934e) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [ebb3d9d7aa](https://linux-hardware.org/?probe=ebb3d9d7aa) | Aug 15, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [8d1bc7ce18](https://linux-hardware.org/?probe=8d1bc7ce18) | Aug 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [e1529e585d](https://linux-hardware.org/?probe=e1529e585d) | Aug 14, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASUSTek       | ZN241IC                     | All in one  | [46c001d058](https://linux-hardware.org/?probe=46c001d058) | Aug 10, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [92a135b7d2](https://linux-hardware.org/?probe=92a135b7d2) | Aug 09, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [c3fbdc22c8](https://linux-hardware.org/?probe=c3fbdc22c8) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [4a551e8c6b](https://linux-hardware.org/?probe=4a551e8c6b) | Aug 09, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [0c80b9688e](https://linux-hardware.org/?probe=0c80b9688e) | Aug 08, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | Notebook    | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| Dell          | 0T568R A00                  | Desktop     | [fb620a31fc](https://linux-hardware.org/?probe=fb620a31fc) | Aug 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [5101109869](https://linux-hardware.org/?probe=5101109869) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [28a4ff7761](https://linux-hardware.org/?probe=28a4ff7761) | Aug 07, 2020 |
| Acer          | Aspire 5349                 | Notebook    | [fdae61b8d4](https://linux-hardware.org/?probe=fdae61b8d4) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [d702543fbb](https://linux-hardware.org/?probe=d702543fbb) | Aug 06, 2020 |
| HP            | 8648                        | Desktop     | [e034f483fc](https://linux-hardware.org/?probe=e034f483fc) | Aug 06, 2020 |
| Dell          | 0P4T42 A00                  | All in one  | [4924eefd27](https://linux-hardware.org/?probe=4924eefd27) | Aug 03, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [b5911c66d7](https://linux-hardware.org/?probe=b5911c66d7) | Aug 02, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | Notebook    | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| PC Special... | N150CU                      | Notebook    | [6d19fc4569](https://linux-hardware.org/?probe=6d19fc4569) | Aug 01, 2020 |
| Lenovo        | ThinkPad T430 2349KB4       | Notebook    | [291151dae1](https://linux-hardware.org/?probe=291151dae1) | Jul 31, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [0e300aa2a8](https://linux-hardware.org/?probe=0e300aa2a8) | Jul 30, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [e9feed814f](https://linux-hardware.org/?probe=e9feed814f) | Jul 29, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [b296acb26a](https://linux-hardware.org/?probe=b296acb26a) | Jul 29, 2020 |
| HP            | Pavilion dm1                | Notebook    | [cc8ed632dc](https://linux-hardware.org/?probe=cc8ed632dc) | Jul 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9b5d494924](https://linux-hardware.org/?probe=9b5d494924) | Jul 25, 2020 |
| Dell          | Latitude 5480               | Notebook    | [e06096d959](https://linux-hardware.org/?probe=e06096d959) | Jul 24, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [4615574555](https://linux-hardware.org/?probe=4615574555) | Jul 24, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [a8709e5362](https://linux-hardware.org/?probe=a8709e5362) | Jul 23, 2020 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [bdf2ff973b](https://linux-hardware.org/?probe=bdf2ff973b) | Jul 20, 2020 |
| Dell          | Latitude 5400               | Notebook    | [11473792e0](https://linux-hardware.org/?probe=11473792e0) | Jul 19, 2020 |
| HP            | 8425                        | Desktop     | [25fd18c4f7](https://linux-hardware.org/?probe=25fd18c4f7) | Jul 19, 2020 |
| HP            | 255 G2                      | Notebook    | [6801725bae](https://linux-hardware.org/?probe=6801725bae) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [7319f8f1b3](https://linux-hardware.org/?probe=7319f8f1b3) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [d1dea15553](https://linux-hardware.org/?probe=d1dea15553) | Jul 16, 2020 |
| Lenovo        | G500 VIWGP                  | Notebook    | [37286d3145](https://linux-hardware.org/?probe=37286d3145) | Jul 08, 2020 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [f504426c40](https://linux-hardware.org/?probe=f504426c40) | Jul 04, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [332ba4769f](https://linux-hardware.org/?probe=332ba4769f) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [2a16561ffa](https://linux-hardware.org/?probe=2a16561ffa) | Jun 28, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [8ba0fcfe7c](https://linux-hardware.org/?probe=8ba0fcfe7c) | Jun 28, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [0c0f90ba39](https://linux-hardware.org/?probe=0c0f90ba39) | Jun 27, 2020 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [124cdbcc52](https://linux-hardware.org/?probe=124cdbcc52) | Jun 27, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [92adc3c517](https://linux-hardware.org/?probe=92adc3c517) | Jun 25, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [60c99711b8](https://linux-hardware.org/?probe=60c99711b8) | Jun 23, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [a36f83366b](https://linux-hardware.org/?probe=a36f83366b) | Jun 21, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d79300ba76](https://linux-hardware.org/?probe=d79300ba76) | Jun 18, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [168dcc66c7](https://linux-hardware.org/?probe=168dcc66c7) | Jun 17, 2020 |
| Timi          | TM1703                      | Notebook    | [d3d89dc21d](https://linux-hardware.org/?probe=d3d89dc21d) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [1cfb078c4e](https://linux-hardware.org/?probe=1cfb078c4e) | Jun 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [18230e354a](https://linux-hardware.org/?probe=18230e354a) | Jun 13, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [89214de087](https://linux-hardware.org/?probe=89214de087) | Jun 12, 2020 |
| SLIMBOOK      | PROX15                      | Notebook    | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| ASUSTek       | G750JW                      | Notebook    | [cc02e1e15c](https://linux-hardware.org/?probe=cc02e1e15c) | Jun 10, 2020 |
| Lenovo        | ThinkCentre M58 7373BVU     | Desktop     | [5c40e26f41](https://linux-hardware.org/?probe=5c40e26f41) | Jun 09, 2020 |
| Dell          | Latitude E5420              | Notebook    | [eb3a4e918a](https://linux-hardware.org/?probe=eb3a4e918a) | Jun 08, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a1615f709d](https://linux-hardware.org/?probe=a1615f709d) | Jun 07, 2020 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [7b570e8172](https://linux-hardware.org/?probe=7b570e8172) | Jun 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34431... | Notebook    | [c5d45645b7](https://linux-hardware.org/?probe=c5d45645b7) | Jun 01, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [fbef0c90d4](https://linux-hardware.org/?probe=fbef0c90d4) | May 28, 2020 |
| Lenovo        | ThinkPad T410s 2904HDU      | Notebook    | [b1eb7716ed](https://linux-hardware.org/?probe=b1eb7716ed) | May 26, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [1538853c0c](https://linux-hardware.org/?probe=1538853c0c) | May 26, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| HP            | Presario CQ61               | Notebook    | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| Chuwi         | LapBook SE                  | Notebook    | [c144d3a1bc](https://linux-hardware.org/?probe=c144d3a1bc) | May 24, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [cdcb59b3fb](https://linux-hardware.org/?probe=cdcb59b3fb) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [495a29d64c](https://linux-hardware.org/?probe=495a29d64c) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [1c2ca9c7de](https://linux-hardware.org/?probe=1c2ca9c7de) | May 22, 2020 |
| Dell          | Vostro 5490                 | Notebook    | [9000fa541e](https://linux-hardware.org/?probe=9000fa541e) | May 18, 2020 |
| Dell          | Latitude E5420              | Notebook    | [5519dbffbc](https://linux-hardware.org/?probe=5519dbffbc) | May 18, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [932b22c52a](https://linux-hardware.org/?probe=932b22c52a) | May 16, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [02b85cc578](https://linux-hardware.org/?probe=02b85cc578) | May 16, 2020 |
| Lenovo        | ThinkPad T520 424329U       | Notebook    | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| System76      | Galago Pro                  | Notebook    | [3ae6d02922](https://linux-hardware.org/?probe=3ae6d02922) | May 14, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [deca13654e](https://linux-hardware.org/?probe=deca13654e) | May 13, 2020 |
| Intel         | DQ57TM AAE92694-401         | Desktop     | [c2abb26814](https://linux-hardware.org/?probe=c2abb26814) | May 11, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [f05f9404d0](https://linux-hardware.org/?probe=f05f9404d0) | May 11, 2020 |
| Gigabyte      | P15FV7                      | Notebook    | [a7031c2684](https://linux-hardware.org/?probe=a7031c2684) | May 09, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [db25140369](https://linux-hardware.org/?probe=db25140369) | May 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Sony UK       | Raspberry Pi 3 Model B      | Soc         | [52f0b7d3fa](https://linux-hardware.org/?probe=52f0b7d3fa) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [6f9d4efc51](https://linux-hardware.org/?probe=6f9d4efc51) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [9e5819a0bc](https://linux-hardware.org/?probe=9e5819a0bc) | May 06, 2020 |
| Acer          | Okinawa                     | Notebook    | [9e22849a3a](https://linux-hardware.org/?probe=9e22849a3a) | May 03, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e356fece67](https://linux-hardware.org/?probe=e356fece67) | May 01, 2020 |
| Dell          | 0FH884                      | Desktop     | [1f7976ed89](https://linux-hardware.org/?probe=1f7976ed89) | Apr 30, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [473467f488](https://linux-hardware.org/?probe=473467f488) | Apr 29, 2020 |
| Dell          | XPS M1530                   | Notebook    | [ef2ddf50e9](https://linux-hardware.org/?probe=ef2ddf50e9) | Apr 28, 2020 |
| Dell          | XPS M1530                   | Notebook    | [9d8053a9f5](https://linux-hardware.org/?probe=9d8053a9f5) | Apr 28, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | Notebook    | [e6010acabe](https://linux-hardware.org/?probe=e6010acabe) | Apr 28, 2020 |
| Dell          | Precision 7510              | Notebook    | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Dell          | Latitude E5570              | Notebook    | [4c46b3c18d](https://linux-hardware.org/?probe=4c46b3c18d) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [306c5d73fb](https://linux-hardware.org/?probe=306c5d73fb) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [9fd393aab9](https://linux-hardware.org/?probe=9fd393aab9) | Apr 27, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [9b6c98e396](https://linux-hardware.org/?probe=9b6c98e396) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [0d9716a2e8](https://linux-hardware.org/?probe=0d9716a2e8) | Apr 26, 2020 |
| ABIT          | KN9                         | Desktop     | [6254e80aba](https://linux-hardware.org/?probe=6254e80aba) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [951197ee19](https://linux-hardware.org/?probe=951197ee19) | Apr 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ireland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 86        | 10.97%  |
| Ubuntu 22.04       | 44        | 5.61%   |
| Ubuntu 18.04       | 44        | 5.61%   |
| Debian 11          | 28        | 3.57%   |
| Pop!_OS 22.04      | 20        | 2.55%   |
| Zorin 16           | 14        | 1.79%   |
| Manjaro            | 13        | 1.66%   |
| Arch Rolling       | 13        | 1.66%   |
| OpenMandriva 4.2   | 12        | 1.53%   |
| Fedora 38          | 12        | 1.53%   |
| ArcoLinux Rolling  | 12        | 1.53%   |
| Linux Mint 21.1    | 11        | 1.4%    |
| Linux Mint 20.2    | 11        | 1.4%    |
| Arch               | 11        | 1.4%    |
| Ubuntu 22.10       | 10        | 1.28%   |
| Linux Mint 20.3    | 10        | 1.28%   |
| Linux Mint 20      | 10        | 1.28%   |
| Fedora 37          | 10        | 1.28%   |
| Fedora 36          | 10        | 1.28%   |
| Debian 10          | 10        | 1.28%   |
| Ubuntu 19.04       | 9         | 1.15%   |
| Pop!_OS 21.10      | 9         | 1.15%   |
| OpenMandriva 23.01 | 9         | 1.15%   |
| Debian 12          | 9         | 1.15%   |
| Ubuntu 23.04       | 8         | 1.02%   |
| Pop!_OS 20.10      | 8         | 1.02%   |
| Linux Mint 21.2    | 8         | 1.02%   |
| Pop!_OS 20.04      | 7         | 0.89%   |
| OpenMandriva 4.3   | 7         | 0.89%   |
| Linux Mint 21      | 7         | 0.89%   |
| KDE neon 20.04     | 7         | 0.89%   |
| Fedora 39          | 7         | 0.89%   |
| BlackPanther 18.1  | 7         | 0.89%   |
| Ubuntu 19.10       | 6         | 0.77%   |
| Gentoo 2.14        | 6         | 0.77%   |
| Ubuntu 21.10       | 5         | 0.64%   |
| ROSA R11           | 5         | 0.64%   |
| ROSA R10           | 5         | 0.64%   |
| OpenMandriva 23.08 | 5         | 0.64%   |
| OpenMandriva 23.03 | 5         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 218       | 29.66%  |
| Linux Mint    | 76        | 10.34%  |
| Fedora        | 55        | 7.48%   |
| Debian        | 54        | 7.35%   |
| Pop!_OS       | 44        | 5.99%   |
| OpenMandriva  | 39        | 5.31%   |
| Manjaro       | 28        | 3.81%   |
| Arch          | 24        | 3.27%   |
| Zorin         | 21        | 2.86%   |
| Kubuntu       | 17        | 2.31%   |
| ROSA          | 14        | 1.9%    |
| KDE neon      | 13        | 1.77%   |
| ArcoLinux     | 12        | 1.63%   |
| Elementary    | 10        | 1.36%   |
| SteamOS       | 9         | 1.22%   |
| Gentoo        | 9         | 1.22%   |
| Xubuntu       | 8         | 1.09%   |
| Lubuntu       | 8         | 1.09%   |
| BlackPanther  | 8         | 1.09%   |
| openSUSE      | 7         | 0.95%   |
| Ubuntu Unity  | 5         | 0.68%   |
| Ubuntu MATE   | 5         | 0.68%   |
| Endless       | 5         | 0.68%   |
| Ubuntu Budgie | 4         | 0.54%   |
| MX            | 4         | 0.54%   |
| Kali          | 4         | 0.54%   |
| Parrot        | 3         | 0.41%   |
| Clear Linux   | 3         | 0.41%   |
| Rocky Linux   | 2         | 0.27%   |
| Peppermint    | 2         | 0.27%   |
| Nobara        | 2         | 0.27%   |
| LMDE          | 2         | 0.27%   |
| Linux Lite    | 2         | 0.27%   |
| Garuda Linux  | 2         | 0.27%   |
| CentOS        | 2         | 0.27%   |
| CachyOS       | 2         | 0.27%   |
| Xero          | 1         | 0.14%   |
| Ubuntu Studio | 1         | 0.14%   |
| Trisquel      | 1         | 0.14%   |
| Solus         | 1         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 1.72%   |
| 5.10.14-desktop-1omv4002 | 12        | 1.38%   |
| 5.3.0-46-generic         | 10        | 1.15%   |
| 6.1.1-desktop-1omv2290   | 8         | 0.92%   |
| 5.15.0-56-generic        | 8         | 0.92%   |
| 5.15.0-46-generic        | 8         | 0.92%   |
| 5.19.0-35-generic        | 7         | 0.8%    |
| 5.16.7-desktop-1omv4003  | 7         | 0.8%    |
| 5.10.0-23-amd64          | 7         | 0.8%    |
| 6.5.0-26-generic         | 6         | 0.69%   |
| 6.4.11-desktop-1omv2390  | 6         | 0.69%   |
| 6.2.0-26-generic         | 6         | 0.69%   |
| 5.4.0-52-generic         | 6         | 0.69%   |
| 5.15.0-91-generic        | 6         | 0.69%   |
| 5.15.0-67-generic        | 6         | 0.69%   |
| 5.15.0-52-generic        | 6         | 0.69%   |
| 4.18.16-desktop-1bP      | 6         | 0.69%   |
| 6.2.6-desktop-1omv2390   | 5         | 0.57%   |
| 6.2.0-39-generic         | 5         | 0.57%   |
| 6.2.0-20-generic         | 5         | 0.57%   |
| 5.4.0-91-generic         | 5         | 0.57%   |
| 5.4.0-72-generic         | 5         | 0.57%   |
| 5.4.0-48-generic         | 5         | 0.57%   |
| 5.19.0-29-generic        | 5         | 0.57%   |
| 5.11.0-27-generic        | 5         | 0.57%   |
| 6.2.6-76060206-generic   | 4         | 0.46%   |
| 6.2.0-36-generic         | 4         | 0.46%   |
| 5.8.0-7630-generic       | 4         | 0.46%   |
| 5.8.0-43-generic         | 4         | 0.46%   |
| 5.4.0-47-generic         | 4         | 0.46%   |
| 5.4.0-31-generic         | 4         | 0.46%   |
| 5.4.0-29-generic         | 4         | 0.46%   |
| 5.4.0-26-generic         | 4         | 0.46%   |
| 5.3.0-28-generic         | 4         | 0.46%   |
| 5.19.0-38-generic        | 4         | 0.46%   |
| 5.15.0-60-generic        | 4         | 0.46%   |
| 5.15.0-48-generic        | 4         | 0.46%   |
| 5.10.0-8-amd64           | 4         | 0.46%   |
| 4.18.0-15-generic        | 4         | 0.46%   |
| 6.5.0-28-generic         | 3         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 117       | 14.37%  |
| 5.15.0  | 68        | 8.35%   |
| 5.19.0  | 37        | 4.55%   |
| 4.15.0  | 37        | 4.55%   |
| 6.2.0   | 28        | 3.44%   |
| 5.8.0   | 28        | 3.44%   |
| 5.11.0  | 28        | 3.44%   |
| 5.10.0  | 28        | 3.44%   |
| 5.3.0   | 26        | 3.19%   |
| 5.13.0  | 22        | 2.7%    |
| 6.5.0   | 20        | 2.46%   |
| 5.0.0   | 15        | 1.84%   |
| 6.1.0   | 13        | 1.6%    |
| 5.10.14 | 12        | 1.47%   |
| 4.19.0  | 11        | 1.35%   |
| 4.18.0  | 11        | 1.35%   |
| 6.2.6   | 9         | 1.11%   |
| 6.1.1   | 8         | 0.98%   |
| 5.17.5  | 8         | 0.98%   |
| 5.16.7  | 7         | 0.86%   |
| 6.4.11  | 6         | 0.74%   |
| 4.18.16 | 6         | 0.74%   |
| 6.3.8   | 5         | 0.61%   |
| 6.5.6   | 4         | 0.49%   |
| 6.0.6   | 4         | 0.49%   |
| 5.18.0  | 4         | 0.49%   |
| 5.16.11 | 4         | 0.49%   |
| 4.9.60  | 4         | 0.49%   |
| 6.6.4   | 3         | 0.37%   |
| 6.5.5   | 3         | 0.37%   |
| 6.2.9   | 3         | 0.37%   |
| 6.2.8   | 3         | 0.37%   |
| 6.1.9   | 3         | 0.37%   |
| 6.1.52  | 3         | 0.37%   |
| 6.0.9   | 3         | 0.37%   |
| 6.0.12  | 3         | 0.37%   |
| 6.0.0   | 3         | 0.37%   |
| 5.8.14  | 3         | 0.37%   |
| 5.6.0   | 3         | 0.37%   |
| 5.16.15 | 3         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 123       | 15.39%  |
| 5.15    | 86        | 10.76%  |
| 5.10    | 54        | 6.76%   |
| 6.2     | 45        | 5.63%   |
| 5.19    | 44        | 5.51%   |
| 6.1     | 37        | 4.63%   |
| 4.15    | 37        | 4.63%   |
| 5.8     | 35        | 4.38%   |
| 5.11    | 34        | 4.26%   |
| 6.5     | 28        | 3.5%    |
| 5.13    | 28        | 3.5%    |
| 5.3     | 27        | 3.38%   |
| 6.0     | 20        | 2.5%    |
| 5.16    | 17        | 2.13%   |
| 4.18    | 17        | 2.13%   |
| 5.17    | 15        | 1.88%   |
| 5.0     | 15        | 1.88%   |
| 6.6     | 12        | 1.5%    |
| 6.4     | 12        | 1.5%    |
| 4.19    | 12        | 1.5%    |
| 6.3     | 11        | 1.38%   |
| 5.18    | 11        | 1.38%   |
| 4.9     | 11        | 1.38%   |
| 5.6     | 10        | 1.25%   |
| 5.14    | 9         | 1.13%   |
| 5.12    | 9         | 1.13%   |
| 5.7     | 7         | 0.88%   |
| 6.8     | 5         | 0.63%   |
| 6.7     | 5         | 0.63%   |
| 5.9     | 5         | 0.63%   |
| 4.4     | 3         | 0.38%   |
| 4.10    | 3         | 0.38%   |
| 4.13    | 2         | 0.25%   |
| 4.12    | 2         | 0.25%   |
| 3.10    | 2         | 0.25%   |
| 5.5     | 1         | 0.13%   |
| 5.2     | 1         | 0.13%   |
| 5       | 1         | 0.13%   |
| 4.20    | 1         | 0.13%   |
| 4.14    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 676       | 96.57%  |
| i686    | 16        | 2.29%   |
| aarch64 | 8         | 1.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 325       | 43.86%  |
| KDE5            | 130       | 17.54%  |
| Unknown         | 77        | 10.39%  |
| XFCE            | 59        | 7.96%   |
| X-Cinnamon      | 55        | 7.42%   |
| KDE             | 19        | 2.56%   |
| MATE            | 17        | 2.29%   |
| Pantheon        | 9         | 1.21%   |
| LXQt            | 9         | 1.21%   |
| Cinnamon        | 9         | 1.21%   |
| KDE4            | 7         | 0.94%   |
| Unity           | 5         | 0.67%   |
| i3              | 4         | 0.54%   |
| Budgie          | 4         | 0.54%   |
| GNOME Flashback | 3         | 0.4%    |
| LXDE            | 2         | 0.27%   |
| GNOME Classic   | 2         | 0.27%   |
| X-Generic       | 1         | 0.13%   |
| LeftWM          | 1         | 0.13%   |
| Enlightenment   | 1         | 0.13%   |
| DWM             | 1         | 0.13%   |
| BunsenLabs      | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 535       | 74.31%  |
| Wayland | 130       | 18.06%  |
| Unknown | 41        | 5.69%   |
| Tty     | 14        | 1.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 354       | 48.1%   |
| SDDM    | 110       | 14.95%  |
| GDM     | 82        | 11.14%  |
| LightDM | 80        | 10.87%  |
| GDM3    | 80        | 10.87%  |
| TDM     | 19        | 2.58%   |
| KDM     | 7         | 0.95%   |
| LXDM    | 2         | 0.27%   |
| SLiM    | 1         | 0.14%   |
| MDM     | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_IE   | 348       | 47.54%  |
| en_GB   | 137       | 18.72%  |
| en_US   | 128       | 17.49%  |
| Unknown | 69        | 9.43%   |
| pl_PL   | 14        | 1.91%   |
| C       | 9         | 1.23%   |
| es_ES   | 3         | 0.41%   |
| ru_RU   | 2         | 0.27%   |
| en_IN   | 2         | 0.27%   |
| en_CA   | 2         | 0.27%   |
| bg_BG   | 2         | 0.27%   |
| zh_CN   | 1         | 0.14%   |
| pt_PT   | 1         | 0.14%   |
| pt_BR   | 1         | 0.14%   |
| lt_LT   | 1         | 0.14%   |
| it_IT   | 1         | 0.14%   |
| hu_HU   | 1         | 0.14%   |
| ga_IE   | 1         | 0.14%   |
| fr_FR   | 1         | 0.14%   |
| fr_BE   | 1         | 0.14%   |
| es_SV   | 1         | 0.14%   |
| en_ZA   | 1         | 0.14%   |
| en_DE   | 1         | 0.14%   |
| en_BW   | 1         | 0.14%   |
| en_AU   | 1         | 0.14%   |
| de_DE   | 1         | 0.14%   |
| C.UTF8  | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 364       | 50.84%  |
| EFI  | 352       | 49.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 519       | 71.98%  |
| Btrfs               | 84        | 11.65%  |
| Overlay             | 46        | 6.38%   |
| Tmpfs               | 23        | 3.19%   |
| Unknown             | 23        | 3.19%   |
| Xfs                 | 15        | 2.08%   |
| Zfs                 | 6         | 0.83%   |
| Ext3                | 2         | 0.28%   |
| Fuse.fuse-overlayfs | 1         | 0.14%   |
| Fake                | 1         | 0.14%   |
| F2fs                | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 356       | 48.97%  |
| GPT     | 295       | 40.58%  |
| MBR     | 76        | 10.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 604       | 84.83%  |
| Yes       | 108       | 15.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 541       | 75.56%  |
| Yes       | 175       | 24.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Dell                                 | 151       | 21.63%  |
| Lenovo                               | 122       | 17.48%  |
| ASUSTek Computer                     | 85        | 12.18%  |
| Hewlett-Packard                      | 78        | 11.17%  |
| Gigabyte Technology                  | 34        | 4.87%   |
| Acer                                 | 31        | 4.44%   |
| MSI                                  | 24        | 3.44%   |
| Apple                                | 22        | 3.15%   |
| Toshiba                              | 14        | 2.01%   |
| ASRock                               | 14        | 2.01%   |
| Intel                                | 11        | 1.58%   |
| Samsung Electronics                  | 10        | 1.43%   |
| Valve                                | 6         | 0.86%   |
| Medion                               | 6         | 0.86%   |
| Foxconn                              | 5         | 0.72%   |
| Chuwi                                | 5         | 0.72%   |
| TUXEDO                               | 4         | 0.57%   |
| Timi                                 | 4         | 0.57%   |
| PC Specialist                        | 4         | 0.57%   |
| Packard Bell                         | 4         | 0.57%   |
| Notebook                             | 4         | 0.57%   |
| System76                             | 3         | 0.43%   |
| Raspberry Pi Foundation              | 3         | 0.43%   |
| HUAWEI                               | 3         | 0.43%   |
| Google                               | 3         | 0.43%   |
| Fujitsu                              | 3         | 0.43%   |
| AZW                                  | 3         | 0.43%   |
| Alienware                            | 3         | 0.43%   |
| Shuttle                              | 2         | 0.29%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.29%   |
| Seco                                 | 2         | 0.29%   |
| Nvidia                               | 2         | 0.29%   |
| Fujitsu Siemens                      | 2         | 0.29%   |
| Entroware                            | 2         | 0.29%   |
| eMachines                            | 2         | 0.29%   |
| AVITA                                | 2         | 0.29%   |
| Unknown                              | 2         | 0.29%   |
| Star Labs                            | 1         | 0.14%   |
| Sony UK                              | 1         | 0.14%   |
| Sony                                 | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Dell OptiPlex 7010                         | 8         | 1.15%   |
| Dell Latitude 7420                         | 8         | 1.15%   |
| ASUS All Series                            | 7         | 1%      |
| Valve Jupiter                              | 6         | 0.86%   |
| Lenovo Yoga 6 13ALC7 82UD                  | 5         | 0.72%   |
| Gigabyte B450M DS3H                        | 5         | 0.72%   |
| Dell OptiPlex 790                          | 4         | 0.57%   |
| Dell OptiPlex 780                          | 4         | 0.57%   |
| Dell Latitude E7240                        | 4         | 0.57%   |
| Lenovo V145-15AST 81MT                     | 3         | 0.43%   |
| HP Notebook                                | 3         | 0.43%   |
| HP Compaq 8200 Elite SFF PC                | 3         | 0.43%   |
| Dell OptiPlex 7020                         | 3         | 0.43%   |
| Dell Inspiron 13-5378                      | 3         | 0.43%   |
| ASUS ROG STRIX B450-F GAMING               | 3         | 0.43%   |
| ASUS P8P67 PRO                             | 3         | 0.43%   |
| Unknown                                    | 3         | 0.43%   |
| TUXEDO Pulse 15 Gen1                       | 2         | 0.29%   |
| Shenzhen Meigao Electronic Equipment UM690 | 2         | 0.29%   |
| Seco C40                                   | 2         | 0.29%   |
| Samsung 750XED                             | 2         | 0.29%   |
| RPi Raspberry Pi                           | 2         | 0.29%   |
| Nvidia Tegra                               | 2         | 0.29%   |
| MSI MS-7C37                                | 2         | 0.29%   |
| MSI MS-7B86                                | 2         | 0.29%   |
| MSI MS-7B79                                | 2         | 0.29%   |
| Medion Akoya E6239                         | 2         | 0.29%   |
| Lenovo ThinkStation D20 415892G            | 2         | 0.29%   |
| Lenovo ThinkPad X1 Carbon 3443CTO          | 2         | 0.29%   |
| Lenovo ThinkCentre E73 10DS000TUK          | 2         | 0.29%   |
| Lenovo IdeaPad S340-15API 81NC             | 2         | 0.29%   |
| Lenovo IdeaPad 510-15ISK 80SR              | 2         | 0.29%   |
| HUAWEI NBLK-WAX9X                          | 2         | 0.29%   |
| HP Pavilion Laptop 15-eh0xxx               | 2         | 0.29%   |
| HP Pavilion g6                             | 2         | 0.29%   |
| HP OMEN by Laptop 15-dc0xxx                | 2         | 0.29%   |
| HP EliteDesk 800 G1 SFF                    | 2         | 0.29%   |
| HP EliteBook 830 G6                        | 2         | 0.29%   |
| Google Reks                                | 2         | 0.29%   |
| Gigabyte X570 AORUS ULTRA                  | 2         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 54        | 7.74%   |
| Dell Latitude         | 50        | 7.16%   |
| Dell OptiPlex         | 28        | 4.01%   |
| Dell Inspiron         | 26        | 3.72%   |
| Lenovo IdeaPad        | 23        | 3.3%    |
| Acer Aspire           | 21        | 3.01%   |
| Dell XPS              | 18        | 2.58%   |
| HP EliteBook          | 16        | 2.29%   |
| HP Pavilion           | 15        | 2.15%   |
| Dell Precision        | 14        | 2.01%   |
| Toshiba Satellite     | 11        | 1.58%   |
| Lenovo ThinkCentre    | 11        | 1.58%   |
| Lenovo Yoga           | 10        | 1.43%   |
| HP Compaq             | 10        | 1.43%   |
| ASUS TUF              | 9         | 1.29%   |
| ASUS PRIME            | 9         | 1.29%   |
| ASUS ROG              | 7         | 1%      |
| ASUS All              | 7         | 1%      |
| Valve Jupiter         | 6         | 0.86%   |
| ASUS Zenbook          | 6         | 0.86%   |
| HP EliteDesk          | 5         | 0.72%   |
| Gigabyte B450M        | 5         | 0.72%   |
| ASUS VivoBook         | 5         | 0.72%   |
| Dell Vostro           | 4         | 0.57%   |
| RPi Raspberry         | 3         | 0.43%   |
| Packard Bell EasyNote | 3         | 0.43%   |
| Lenovo V145-15AST     | 3         | 0.43%   |
| Lenovo ThinkBook      | 3         | 0.43%   |
| HP ProBook            | 3         | 0.43%   |
| HP Presario           | 3         | 0.43%   |
| HP OMEN               | 3         | 0.43%   |
| HP Notebook           | 3         | 0.43%   |
| HP Laptop             | 3         | 0.43%   |
| Fujitsu LIFEBOOK      | 3         | 0.43%   |
| Foxconn Pro           | 3         | 0.43%   |
| Dell Studio           | 3         | 0.43%   |
| ASUS P8P67            | 3         | 0.43%   |
| Apple MacBookPro5     | 3         | 0.43%   |
| Acer Swift            | 3         | 0.43%   |
| Acer Nitro            | 3         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 70        | 10.03%  |
| 2019    | 63        | 9.03%   |
| 2018    | 61        | 8.74%   |
| 2012    | 55        | 7.88%   |
| 2013    | 53        | 7.59%   |
| 2017    | 47        | 6.73%   |
| 2011    | 45        | 6.45%   |
| 2022    | 40        | 5.73%   |
| 2021    | 40        | 5.73%   |
| 2010    | 34        | 4.87%   |
| 2015    | 33        | 4.73%   |
| 2008    | 32        | 4.58%   |
| 2014    | 27        | 3.87%   |
| 2016    | 25        | 3.58%   |
| 2009    | 21        | 3.01%   |
| 2023    | 20        | 2.87%   |
| 2007    | 11        | 1.58%   |
| 2006    | 8         | 1.15%   |
| Unknown | 8         | 1.15%   |
| 2005    | 3         | 0.43%   |
| 2024    | 1         | 0.14%   |
| 2003    | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 428       | 61.32%  |
| Desktop        | 213       | 30.52%  |
| Mini pc        | 17        | 2.44%   |
| Convertible    | 15        | 2.15%   |
| All in one     | 12        | 1.72%   |
| System on chip | 7         | 1%      |
| Tablet         | 4         | 0.57%   |
| Phone          | 1         | 0.14%   |
| Server         | 1         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 639       | 90.9%   |
| Enabled  | 64        | 9.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 692       | 99.14%  |
| Yes  | 6         | 0.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 164       | 23%     |
| 16.01-24.0      | 154       | 21.6%   |
| 8.01-16.0       | 135       | 18.93%  |
| 3.01-4.0        | 117       | 16.41%  |
| 32.01-64.0      | 72        | 10.1%   |
| 64.01-256.0     | 22        | 3.09%   |
| 1.01-2.0        | 22        | 3.09%   |
| 24.01-32.0      | 14        | 1.96%   |
| 2.01-3.0        | 6         | 0.84%   |
| 0.51-1.0        | 5         | 0.7%    |
| More than 256.0 | 1         | 0.14%   |
| 0.01-0.5        | 1         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 237       | 30.04%  |
| 2.01-3.0   | 203       | 25.73%  |
| 4.01-8.0   | 138       | 17.49%  |
| 3.01-4.0   | 121       | 15.34%  |
| 0.51-1.0   | 41        | 5.2%    |
| 8.01-16.0  | 35        | 4.44%   |
| 0.01-0.5   | 7         | 0.89%   |
| 16.01-24.0 | 5         | 0.63%   |
| 32.01-64.0 | 1         | 0.13%   |
| Unknown    | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 445       | 60.46%  |
| 2      | 172       | 23.37%  |
| 3      | 49        | 6.66%   |
| 4      | 30        | 4.08%   |
| 5      | 15        | 2.04%   |
| 0      | 8         | 1.09%   |
| 7      | 6         | 0.82%   |
| 6      | 5         | 0.68%   |
| 10     | 3         | 0.41%   |
| 11     | 1         | 0.14%   |
| 9      | 1         | 0.14%   |
| 8      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 457       | 64.37%  |
| Yes       | 253       | 35.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 588       | 83.64%  |
| No        | 115       | 16.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 600       | 84.63%  |
| No        | 109       | 15.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 474       | 66.67%  |
| No        | 237       | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ireland | 698       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Dublin         | 423       | 57.39%  |
| Cork           | 46        | 6.24%   |
| Limerick       | 24        | 3.26%   |
| Galway         | 21        | 2.85%   |
| Naas           | 14        | 1.9%    |
| Ennis          | 10        | 1.36%   |
| Drogheda       | 8         | 1.09%   |
| Enniscorthy    | 7         | 0.95%   |
| Sligo          | 6         | 0.81%   |
| Portlaoise     | 6         | 0.81%   |
| Kenmare        | 6         | 0.81%   |
| Gorey          | 6         | 0.81%   |
| Athlone        | 6         | 0.81%   |
| Nenagh         | 5         | 0.68%   |
| Navan          | 5         | 0.68%   |
| Wexford        | 4         | 0.54%   |
| Tuam           | 4         | 0.54%   |
| Lucan          | 4         | 0.54%   |
| Loughrea       | 4         | 0.54%   |
| Kilkenny       | 4         | 0.54%   |
| Dún Laoghaire | 4         | 0.54%   |
| Westport       | 3         | 0.41%   |
| Waterford      | 3         | 0.41%   |
| Tullamore      | 3         | 0.41%   |
| Maynooth       | 3         | 0.41%   |
| Letterkenny    | 3         | 0.41%   |
| Cobh           | 3         | 0.41%   |
| Cavan          | 3         | 0.41%   |
| Bray           | 3         | 0.41%   |
| Blackrock      | 3         | 0.41%   |
| Ballina        | 3         | 0.41%   |
| Tobercurry     | 2         | 0.27%   |
| Swords         | 2         | 0.27%   |
| Oranmore       | 2         | 0.27%   |
| Mallow         | 2         | 0.27%   |
| Longford       | 2         | 0.27%   |
| Killorglin     | 2         | 0.27%   |
| Kilkelly       | 2         | 0.27%   |
| Kildare        | 2         | 0.27%   |
| Edenderry      | 2         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 172       | 259    | 16.81%  |
| WDC                         | 147       | 253    | 14.37%  |
| Seagate                     | 126       | 206    | 12.32%  |
| SanDisk                     | 59        | 79     | 5.77%   |
| Unknown                     | 54        | 73     | 5.28%   |
| Toshiba                     | 53        | 74     | 5.18%   |
| Crucial                     | 48        | 63     | 4.69%   |
| Hitachi                     | 41        | 57     | 4.01%   |
| Kingston                    | 33        | 54     | 3.23%   |
| Intel                       | 26        | 31     | 2.54%   |
| SK hynix                    | 24        | 26     | 2.35%   |
| Micron Technology           | 24        | 27     | 2.35%   |
| KIOXIA                      | 17        | 20     | 1.66%   |
| HGST                        | 17        | 21     | 1.66%   |
| A-DATA Technology           | 11        | 18     | 1.08%   |
| China                       | 9         | 15     | 0.88%   |
| Apple                       | 9         | 11     | 0.88%   |
| Micron/Crucial Technology   | 8         | 12     | 0.78%   |
| Fujitsu                     | 8         | 11     | 0.78%   |
| Phison                      | 7         | 12     | 0.68%   |
| LITEON                      | 7         | 8      | 0.68%   |
| OCZ                         | 6         | 6      | 0.59%   |
| Kingston Technology Company | 6         | 6      | 0.59%   |
| Verbatim                    | 5         | 5      | 0.49%   |
| Transcend                   | 5         | 5      | 0.49%   |
| PNY                         | 5         | 5      | 0.49%   |
| Netac                       | 5         | 5      | 0.49%   |
| Silicon Motion              | 4         | 14     | 0.39%   |
| KingSpec                    | 4         | 4      | 0.39%   |
| Patriot                     | 3         | 4      | 0.29%   |
| LITEONIT                    | 3         | 3      | 0.29%   |
| KingDian                    | 3         | 14     | 0.29%   |
| FORESEE                     | 3         | 4      | 0.29%   |
| ASMT                        | 3         | 5      | 0.29%   |
| ADATA Technology            | 3         | 4      | 0.29%   |
| Unknown                     | 3         | 3      | 0.29%   |
| Union Memory                | 2         | 2      | 0.2%    |
| Team                        | 2         | 2      | 0.2%    |
| SSSTC                       | 2         | 2      | 0.2%    |
| SABRENT                     | 2         | 3      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 12        | 1.06%   |
| Unknown MMC Card  32GB                             | 9         | 0.79%   |
| Crucial CT1000MX500SSD1 1TB                        | 9         | 0.79%   |
| Unknown MMC Card  64GB                             | 8         | 0.7%    |
| KIOXIA KBG40ZNS512G NVMe 512GB                     | 8         | 0.7%    |
| Kingston SA400S37240G 240GB SSD                    | 8         | 0.7%    |
| Seagate ST500DM002-1BD142 500GB                    | 7         | 0.62%   |
| Seagate ST2000DL003-9VT166 2TB                     | 7         | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB                     | 7         | 0.62%   |
| SanDisk NVMe SSD Drive 512GB                       | 7         | 0.62%   |
| Samsung SSD 860 EVO 500GB                          | 7         | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 7         | 0.62%   |
| Crucial CT500MX500SSD1 500GB                       | 7         | 0.62%   |
| Toshiba MQ01ABD100 1TB                             | 6         | 0.53%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB             | 6         | 0.53%   |
| Seagate ST8000DM004-2CX188 8TB                     | 6         | 0.53%   |
| Samsung SSD 970 EVO Plus 500GB                     | 6         | 0.53%   |
| Samsung SSD 850 EVO 250GB                          | 6         | 0.53%   |
| Samsung SSD 840 EVO 250GB                          | 6         | 0.53%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 6         | 0.53%   |
| Samsung NVMe SSD Drive 500GB                       | 6         | 0.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 6         | 0.53%   |
| Kingston SA400S37480G 480GB SSD                    | 6         | 0.53%   |
| HGST HTS721010A9E630 1TB                           | 6         | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 5         | 0.44%   |
| WDC WD10EURX-83UY4Y0 1TB                           | 5         | 0.44%   |
| Verbatim Vi550 S3 SSD 256GB                        | 5         | 0.44%   |
| Unknown MMC Card  128GB                            | 5         | 0.44%   |
| Samsung SSD 850 EVO 500GB                          | 5         | 0.44%   |
| HGST HTS545050A7E680 500GB                         | 5         | 0.44%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                   | 4         | 0.35%   |
| WDC WD10EALX-009BA0 1TB                            | 4         | 0.35%   |
| Unknown MMC Card  16GB                             | 4         | 0.35%   |
| Seagate ST3500312CS 500GB                          | 4         | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB                     | 4         | 0.35%   |
| Seagate Expansion+ Desk 4TB                        | 4         | 0.35%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 4         | 0.35%   |
| SanDisk SSD PLUS 240GB                             | 4         | 0.35%   |
| Samsung SSD 870 QVO 1TB                            | 4         | 0.35%   |
| Samsung SSD 870 EVO 1TB                            | 4         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 124       | 203    | 32.98%  |
| WDC                 | 117       | 211    | 31.12%  |
| Hitachi             | 41        | 57     | 10.9%   |
| Toshiba             | 35        | 49     | 9.31%   |
| HGST                | 17        | 21     | 4.52%   |
| Samsung Electronics | 12        | 17     | 3.19%   |
| Fujitsu             | 8         | 11     | 2.13%   |
| Apple               | 4         | 4      | 1.06%   |
| Unknown             | 3         | 3      | 0.8%    |
| SABRENT             | 2         | 3      | 0.53%   |
| QNAP                | 2         | 18     | 0.53%   |
| Maxtor              | 2         | 2      | 0.53%   |
| USB                 | 1         | 1      | 0.27%   |
| LaCie               | 1         | 1      | 0.27%   |
| KESU                | 1         | 1      | 0.27%   |
| JMicron Technology  | 1         | 1      | 0.27%   |
| Inateck             | 1         | 1      | 0.27%   |
| FNK TECH            | 1         | 1      | 0.27%   |
| ExcelStor           | 1         | 2      | 0.27%   |
| DAS                 | 1         | 4      | 0.27%   |
| ASMT                | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 82        | 119    | 25.71%  |
| Crucial             | 44        | 59     | 13.79%  |
| SanDisk             | 32        | 37     | 10.03%  |
| Kingston            | 29        | 49     | 9.09%   |
| WDC                 | 13        | 19     | 4.08%   |
| China               | 9         | 15     | 2.82%   |
| Intel               | 8         | 8      | 2.51%   |
| A-DATA Technology   | 8         | 14     | 2.51%   |
| OCZ                 | 6         | 6      | 1.88%   |
| Micron Technology   | 6         | 6      | 1.88%   |
| LITEON              | 6         | 7      | 1.88%   |
| Verbatim            | 5         | 5      | 1.57%   |
| PNY                 | 5         | 5      | 1.57%   |
| Netac               | 5         | 5      | 1.57%   |
| Toshiba             | 4         | 6      | 1.25%   |
| SK hynix            | 4         | 4      | 1.25%   |
| KingSpec            | 4         | 4      | 1.25%   |
| Apple               | 4         | 4      | 1.25%   |
| Transcend           | 3         | 3      | 0.94%   |
| Patriot             | 3         | 4      | 0.94%   |
| LITEONIT            | 3         | 3      | 0.94%   |
| KingDian            | 3         | 14     | 0.94%   |
| FORESEE             | 3         | 4      | 0.94%   |
| Team                | 2         | 2      | 0.63%   |
| Integral            | 2         | 2      | 0.63%   |
| Fanxiang            | 2         | 2      | 0.63%   |
| ASMT                | 2         | 4      | 0.63%   |
| Unknown             | 2         | 2      | 0.63%   |
| Zheino              | 1         | 1      | 0.31%   |
| Wibtek              | 1         | 2      | 0.31%   |
| W800S               | 1         | 2      | 0.31%   |
| USB3.0              | 1         | 1      | 0.31%   |
| Union Memory        | 1         | 1      | 0.31%   |
| TCSUNBOW            | 1         | 1      | 0.31%   |
| StoreJet            | 1         | 2      | 0.31%   |
| Star                | 1         | 1      | 0.31%   |
| SPCC                | 1         | 1      | 0.31%   |
| Plextor             | 1         | 1      | 0.31%   |
| Palit               | 1         | 1      | 0.31%   |
| Hikvision           | 1         | 1      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 301       | 612    | 33.19%  |
| SSD     | 283       | 438    | 31.2%   |
| NVMe    | 259       | 373    | 28.56%  |
| MMC     | 51        | 73     | 5.62%   |
| Unknown | 13        | 13     | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 479       | 1015   | 58.06%  |
| NVMe | 259       | 372    | 31.39%  |
| MMC  | 51        | 73     | 6.18%   |
| SAS  | 36        | 49     | 4.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 358       | 599    | 57.65%  |
| 0.51-1.0   | 173       | 287    | 27.86%  |
| 1.01-2.0   | 47        | 71     | 7.57%   |
| 3.01-4.0   | 20        | 40     | 3.22%   |
| 4.01-10.0  | 11        | 35     | 1.77%   |
| 2.01-3.0   | 10        | 15     | 1.61%   |
| 10.01-20.0 | 2         | 3      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 192       | 25.53%  |
| 251-500        | 187       | 24.87%  |
| 501-1000       | 99        | 13.16%  |
| 1-20           | 58        | 7.71%   |
| 51-100         | 57        | 7.58%   |
| 1001-2000      | 52        | 6.91%   |
| More than 3000 | 41        | 5.45%   |
| 21-50          | 24        | 3.19%   |
| Unknown        | 24        | 3.19%   |
| 2001-3000      | 18        | 2.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 289       | 36.82%  |
| 21-50          | 123       | 15.67%  |
| 101-250        | 104       | 13.25%  |
| 51-100         | 102       | 12.99%  |
| 251-500        | 51        | 6.5%    |
| 501-1000       | 47        | 5.99%   |
| Unknown        | 24        | 3.06%   |
| More than 3000 | 20        | 2.55%   |
| 1001-2000      | 16        | 2.04%   |
| 2001-3000      | 9         | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST2000DL003-9VT166 2TB      | 5         | 7      | 6.49%   |
| WDC WD10EALX-009BA0 1TB             | 4         | 10     | 5.19%   |
| WDC WD3200AVJS-63B6A0 320GB         | 2         | 2      | 2.6%    |
| WDC WD2500AAKX-753CA1 250GB         | 2         | 4      | 2.6%    |
| Hitachi HTS723232A7A364 320GB       | 2         | 2      | 2.6%    |
| Hitachi HDS721010CLA330 1TB         | 2         | 2      | 2.6%    |
| Western Digital SN730 500GB         | 1         | 2      | 1.3%    |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 1      | 1.3%    |
| WDC WD5000LPCX-24VHAT0 500GB        | 1         | 1      | 1.3%    |
| WDC WD5000HHTZ-04N21V0 500GB        | 1         | 3      | 1.3%    |
| WDC WD5000BEVT-35A0RT0 500GB        | 1         | 1      | 1.3%    |
| WDC WD5000AAKX-001CA0 500GB         | 1         | 2      | 1.3%    |
| WDC WD400JB-00FMA0 40GB             | 1         | 2      | 1.3%    |
| WDC WD2500BEVT-22A23T0 250GB        | 1         | 1      | 1.3%    |
| WDC WD2500BEKT-75A25T0 250GB        | 1         | 1      | 1.3%    |
| WDC WD2500AAKX-603CA0 250GB         | 1         | 1      | 1.3%    |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1         | 2      | 1.3%    |
| WDC WD10EZEX-00BN5A0 1TB            | 1         | 1      | 1.3%    |
| WDC WD1001FALS-00E8B0 1TB           | 1         | 2      | 1.3%    |
| Toshiba MQ01ABF050H 500GB           | 1         | 1      | 1.3%    |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 1.3%    |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.3%    |
| Toshiba MK1652GSX 160GB             | 1         | 1      | 1.3%    |
| Toshiba MK1059GSM 1TB               | 1         | 1      | 1.3%    |
| Toshiba DT01ACA050 500GB            | 1         | 3      | 1.3%    |
| SK hynix SC308 SATA 256GB SSD       | 1         | 1      | 1.3%    |
| Seagate ST9320325AS 320GB           | 1         | 1      | 1.3%    |
| Seagate ST910021AS 100GB            | 1         | 1      | 1.3%    |
| Seagate ST500LM030-2E717D 500GB     | 1         | 1      | 1.3%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 1.3%    |
| Seagate ST4000DX001-1CE168 4TB      | 1         | 1      | 1.3%    |
| Seagate ST3500418AS 500GB           | 1         | 3      | 1.3%    |
| Seagate ST320LT009-9WC142 320GB     | 1         | 1      | 1.3%    |
| Seagate ST31500541AS 1TB            | 1         | 1      | 1.3%    |
| Seagate ST3120026A 120GB            | 1         | 1      | 1.3%    |
| Seagate ST31000333AS 1TB            | 1         | 2      | 1.3%    |
| Seagate ST3000DM001-1ER166 3TB      | 1         | 1      | 1.3%    |
| Seagate ST3000DM001-1CH166 3TB      | 1         | 1      | 1.3%    |
| SanDisk SSD PLUS 480GB              | 1         | 1      | 1.3%    |
| SanDisk SSD PLUS 240GB              | 1         | 1      | 1.3%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 34     | 22.97%  |
| Seagate             | 17        | 22     | 22.97%  |
| Hitachi             | 12        | 16     | 16.22%  |
| Toshiba             | 6         | 8      | 8.11%   |
| Samsung Electronics | 3         | 3      | 4.05%   |
| Micron Technology   | 3         | 3      | 4.05%   |
| SanDisk             | 2         | 2      | 2.7%    |
| HGST                | 2         | 2      | 2.7%    |
| Western Digital     | 1         | 2      | 1.35%   |
| SK hynix            | 1         | 1      | 1.35%   |
| Netac               | 1         | 1      | 1.35%   |
| Maxtor              | 1         | 1      | 1.35%   |
| JMicron Technology  | 1         | 1      | 1.35%   |
| Intel               | 1         | 1      | 1.35%   |
| Inateck             | 1         | 1      | 1.35%   |
| Fujitsu             | 1         | 1      | 1.35%   |
| DRVEO               | 1         | 1      | 1.35%   |
| China               | 1         | 1      | 1.35%   |
| Apple               | 1         | 1      | 1.35%   |
| A-DATA Technology   | 1         | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 34     | 27.87%  |
| Seagate             | 17        | 22     | 27.87%  |
| Hitachi             | 12        | 16     | 19.67%  |
| Toshiba             | 6         | 8      | 9.84%   |
| Samsung Electronics | 2         | 2      | 3.28%   |
| HGST                | 2         | 2      | 3.28%   |
| Maxtor              | 1         | 1      | 1.64%   |
| JMicron Technology  | 1         | 1      | 1.64%   |
| Inateck             | 1         | 1      | 1.64%   |
| Fujitsu             | 1         | 1      | 1.64%   |
| Apple               | 1         | 1      | 1.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 89     | 78.33%  |
| SSD  | 10        | 10     | 16.67%  |
| NVMe | 3         | 4      | 5%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD1200BEVS-22UST0 120GB     | 1         | 1      | 33.33%  |
| Sandisk PC SN520 NVMe SSD 512GB | 1         | 1      | 33.33%  |
| KingDian S400 120GB SSD         | 1         | 4      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 33.33%  |
| Sandisk  | 1         | 1      | 33.33%  |
| KingDian | 1         | 4      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 416       | 829    | 54.1%   |
| Works    | 291       | 571    | 37.84%  |
| Malfunc  | 59        | 103    | 7.67%   |
| Failed   | 3         | 6      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 440       | 50.29%  |
| AMD                            | 123       | 14.06%  |
| Samsung Electronics            | 89        | 10.17%  |
| SanDisk                        | 45        | 5.14%   |
| SK hynix                       | 20        | 2.29%   |
| Micron Technology              | 18        | 2.06%   |
| Toshiba America Info Systems   | 16        | 1.83%   |
| KIOXIA                         | 16        | 1.83%   |
| Nvidia                         | 15        | 1.71%   |
| Micron/Crucial Technology      | 12        | 1.37%   |
| Marvell Technology Group       | 11        | 1.26%   |
| ASMedia Technology             | 11        | 1.26%   |
| Kingston Technology Company    | 10        | 1.14%   |
| Phison Electronics             | 9         | 1.03%   |
| JMicron Technology             | 7         | 0.8%    |
| Union Memory (Shenzhen)        | 5         | 0.57%   |
| Silicon Motion                 | 4         | 0.46%   |
| LSI Logic / Symbios Logic      | 4         | 0.46%   |
| ADATA Technology               | 4         | 0.46%   |
| Transcend                      | 2         | 0.23%   |
| Solid State Storage Technology | 2         | 0.23%   |
| Realtek Semiconductor          | 2         | 0.23%   |
| O2 Micro                       | 2         | 0.23%   |
| ULi Electronics                | 1         | 0.11%   |
| Silicon Image                  | 1         | 0.11%   |
| Seagate Technology             | 1         | 0.11%   |
| Lite-On Technology             | 1         | 0.11%   |
| Lenovo                         | 1         | 0.11%   |
| Broadcom / LSI                 | 1         | 0.11%   |
| Apple                          | 1         | 0.11%   |
| Adaptec                        | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 93        | 9.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 48        | 4.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 40        | 3.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 30        | 2.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 26        | 2.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25        | 2.49%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 20        | 1.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19        | 1.89%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 18        | 1.79%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 17        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17        | 1.69%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 15        | 1.5%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 15        | 1.5%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 14        | 1.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 14        | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13        | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 12        | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 12        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 1.2%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 11        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11        | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10        | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 10        | 1%      |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 9         | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 9         | 0.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 0.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 8         | 0.8%    |
| Intel SATA Controller [RAID mode]                                                       | 8         | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8         | 0.8%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8         | 0.8%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 7         | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 7         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 7         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 0.7%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 7         | 0.7%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 475       | 53.25%  |
| NVMe | 260       | 29.15%  |
| IDE  | 84        | 9.42%   |
| RAID | 69        | 7.74%   |
| SCSI | 4         | 0.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 520       | 74.39%  |
| AMD    | 170       | 24.32%  |
| ARM    | 8         | 1.14%   |
| iSH    | 1         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 14        | 1.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 1.42%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 1.14%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 8         | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 1.14%   |
| ARM Processor                                 | 8         | 1.14%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 1.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1%      |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1%      |
| Intel Core i7-3770 CPU @ 3.40GHz              | 7         | 1%      |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1%      |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 1%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 0.85%   |
| AMD Custom APU 0405                           | 6         | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 5         | 0.71%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.71%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.71%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.57%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 4         | 0.57%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.57%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.57%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 4         | 0.57%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 4         | 0.57%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 4         | 0.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 0.57%   |
| Intel 13th Gen Core i5-1340P                  | 4         | 0.57%   |
| Intel 12th Gen Core i5-1235U                  | 4         | 0.57%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 0.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.57%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.57%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 4         | 0.57%   |
| Intel Pentium 4 CPU 3.00GHz                   | 3         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 139       | 19.77%  |
| Intel Core i7           | 138       | 19.63%  |
| Other                   | 81        | 11.52%  |
| Intel Core i3           | 48        | 6.83%   |
| AMD Ryzen 5             | 40        | 5.69%   |
| Intel Celeron           | 34        | 4.84%   |
| AMD Ryzen 7             | 33        | 4.69%   |
| Intel Core 2 Duo        | 29        | 4.13%   |
| AMD Ryzen 9             | 15        | 2.13%   |
| Intel Atom              | 12        | 1.71%   |
| Intel Pentium           | 11        | 1.56%   |
| Intel Xeon              | 10        | 1.42%   |
| Intel Core 2 Quad       | 8         | 1.14%   |
| AMD Ryzen 3             | 6         | 0.85%   |
| AMD FX                  | 6         | 0.85%   |
| AMD Athlon 64 X2        | 6         | 0.85%   |
| Intel Pentium Dual-Core | 5         | 0.71%   |
| AMD A8                  | 5         | 0.71%   |
| AMD A6                  | 5         | 0.71%   |
| Intel Pentium 4         | 4         | 0.57%   |
| AMD Ryzen 5 PRO         | 4         | 0.57%   |
| AMD E1                  | 4         | 0.57%   |
| Intel Pentium Silver    | 3         | 0.43%   |
| Intel Core i9           | 3         | 0.43%   |
| Intel Core 2            | 3         | 0.43%   |
| AMD Ryzen Threadripper  | 3         | 0.43%   |
| AMD Ryzen 7 PRO         | 3         | 0.43%   |
| AMD Phenom II X4        | 3         | 0.43%   |
| AMD Athlon II X4        | 3         | 0.43%   |
| Intel Pentium Dual      | 2         | 0.28%   |
| Intel Core m3           | 2         | 0.28%   |
| Intel Celeron Dual-Core | 2         | 0.28%   |
| AMD Sempron             | 2         | 0.28%   |
| AMD Ryzen Embedded      | 2         | 0.28%   |
| AMD Ryzen 3 PRO         | 2         | 0.28%   |
| AMD PRO A10             | 2         | 0.28%   |
| AMD Phenom II X6        | 2         | 0.28%   |
| AMD E2                  | 2         | 0.28%   |
| AMD A4                  | 2         | 0.28%   |
| AMD A10                 | 2         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 289       | 41.23%  |
| 2       | 241       | 34.38%  |
| 6       | 56        | 7.99%   |
| 8       | 45        | 6.42%   |
| 12      | 22        | 3.14%   |
| 1       | 21        | 3%      |
| 14      | 8         | 1.14%   |
| 10      | 7         | 1%      |
| 24      | 3         | 0.43%   |
| 3       | 3         | 0.43%   |
| 16      | 2         | 0.29%   |
| Unknown | 2         | 0.29%   |
| 96      | 1         | 0.14%   |
| 32      | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 691       | 99%     |
| 2       | 6         | 0.86%   |
| Unknown | 1         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 475       | 67.57%  |
| 1       | 226       | 32.15%  |
| Unknown | 2         | 0.28%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 680       | 97%     |
| Unknown        | 18        | 2.57%   |
| 32-bit         | 3         | 0.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 257       | 35.16%  |
| 0x306a9    | 39        | 5.34%   |
| 0x206a7    | 31        | 4.24%   |
| 0x1067a    | 24        | 3.28%   |
| 0x306c3    | 23        | 3.15%   |
| 0x806ec    | 22        | 3.01%   |
| 0x806e9    | 18        | 2.46%   |
| 0x806c1    | 18        | 2.46%   |
| 0x806ea    | 14        | 1.92%   |
| 0x406e3    | 13        | 1.78%   |
| 0x906ea    | 10        | 1.37%   |
| 0x906e9    | 10        | 1.37%   |
| 0x40651    | 10        | 1.37%   |
| 0x08108109 | 10        | 1.37%   |
| 0x406c4    | 9         | 1.23%   |
| 0x0a50000c | 9         | 1.23%   |
| 0x10676    | 8         | 1.09%   |
| 0xa0652    | 7         | 0.96%   |
| 0x506e3    | 7         | 0.96%   |
| 0x30678    | 7         | 0.96%   |
| 0x08701021 | 7         | 0.96%   |
| 0x306d4    | 6         | 0.82%   |
| 0x20655    | 6         | 0.82%   |
| 0x0810100b | 6         | 0.82%   |
| 0x08108102 | 5         | 0.68%   |
| 0x0800820d | 5         | 0.68%   |
| 0x06006705 | 5         | 0.68%   |
| 0xa0653    | 4         | 0.55%   |
| 0x906a3    | 4         | 0.55%   |
| 0x706a8    | 4         | 0.55%   |
| 0x6fd      | 4         | 0.55%   |
| 0x6fb      | 4         | 0.55%   |
| 0x206c2    | 4         | 0.55%   |
| 0x0600611a | 4         | 0.55%   |
| 0xf43      | 3         | 0.41%   |
| 0x906ed    | 3         | 0.41%   |
| 0x806d1    | 3         | 0.41%   |
| 0x706e5    | 3         | 0.41%   |
| 0x706a1    | 3         | 0.41%   |
| 0x106e5    | 3         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 107       | 15.29%  |
| IvyBridge        | 57        | 8.14%   |
| SandyBridge      | 48        | 6.86%   |
| Haswell          | 48        | 6.86%   |
| Unknown          | 48        | 6.86%   |
| Penryn           | 36        | 5.14%   |
| Skylake          | 34        | 4.86%   |
| TigerLake        | 32        | 4.57%   |
| Zen 2            | 30        | 4.29%   |
| Zen+             | 29        | 4.14%   |
| Silvermont       | 23        | 3.29%   |
| Westmere         | 20        | 2.86%   |
| Zen 3            | 18        | 2.57%   |
| Core             | 16        | 2.29%   |
| CometLake        | 15        | 2.14%   |
| Zen              | 13        | 1.86%   |
| Alderlake Hybrid | 13        | 1.86%   |
| Goldmont plus    | 12        | 1.71%   |
| K10              | 11        | 1.57%   |
| Excavator        | 11        | 1.57%   |
| Icelake          | 10        | 1.43%   |
| Piledriver       | 9         | 1.29%   |
| K8 Hammer        | 9         | 1.29%   |
| Broadwell        | 9         | 1.29%   |
| Nehalem          | 7         | 1%      |
| NetBurst         | 5         | 0.71%   |
| Bonnell          | 5         | 0.71%   |
| Puma             | 4         | 0.57%   |
| P6               | 4         | 0.57%   |
| Jaguar           | 4         | 0.57%   |
| Goldmont         | 4         | 0.57%   |
| Bobcat           | 4         | 0.57%   |
| Steamroller      | 2         | 0.29%   |
| Tremont          | 1         | 0.14%   |
| K8 & K10 hybrid  | 1         | 0.14%   |
| Bulldozer        | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 405       | 50.19%  |
| Nvidia            | 203       | 25.15%  |
| AMD               | 198       | 24.54%  |
| ASPEED Technology | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 3.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 29        | 3.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 3.35%   |
| Intel UHD Graphics 620                                                                   | 19        | 2.27%   |
| Intel HD Graphics 620                                                                    | 19        | 2.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 18        | 2.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 1.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 1.56%   |
| Intel HD Graphics 630                                                                    | 13        | 1.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 1.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 1.32%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 11        | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 1.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 1.08%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 9         | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 8         | 0.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 0.96%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 8         | 0.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 0.96%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 8         | 0.96%   |
| AMD Lucienne                                                                             | 8         | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 0.72%   |
| Intel HD Graphics 5500                                                                   | 6         | 0.72%   |
| Intel HD Graphics 530                                                                    | 6         | 0.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6         | 0.72%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 0.72%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 6         | 0.72%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.6%    |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 306       | 43.16%  |
| 1 x AMD        | 161       | 22.71%  |
| 1 x Nvidia     | 110       | 15.51%  |
| Intel + Nvidia | 80        | 11.28%  |
| 2 x AMD        | 16        | 2.26%   |
| AMD + Nvidia   | 12        | 1.69%   |
| Other          | 9         | 1.27%   |
| Intel + AMD    | 9         | 1.27%   |
| 2 x Intel      | 3         | 0.42%   |
| 2 x Nvidia     | 2         | 0.28%   |
| 1 x ASPEED     | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 570       | 80.28%  |
| Proprietary | 105       | 14.79%  |
| Unknown     | 35        | 4.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 428       | 58.71%  |
| 0.01-0.5   | 72        | 9.88%   |
| 1.01-2.0   | 68        | 9.33%   |
| 3.01-4.0   | 50        | 6.86%   |
| 0.51-1.0   | 50        | 6.86%   |
| 7.01-8.0   | 31        | 4.25%   |
| 5.01-6.0   | 18        | 2.47%   |
| 2.01-3.0   | 5         | 0.69%   |
| 8.01-16.0  | 5         | 0.69%   |
| 16.01-24.0 | 2         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 87        | 11.17%  |
| Dell                    | 84        | 10.78%  |
| AU Optronics            | 84        | 10.78%  |
| LG Display              | 74        | 9.5%    |
| Samsung Electronics     | 66        | 8.47%   |
| Chimei Innolux          | 55        | 7.06%   |
| Acer                    | 26        | 3.34%   |
| Hewlett-Packard         | 24        | 3.08%   |
| BenQ                    | 24        | 3.08%   |
| Sharp                   | 23        | 2.95%   |
| Apple                   | 20        | 2.57%   |
| Philips                 | 19        | 2.44%   |
| Goldstar                | 19        | 2.44%   |
| AOC                     | 18        | 2.31%   |
| Lenovo                  | 17        | 2.18%   |
| ViewSonic               | 13        | 1.67%   |
| Iiyama                  | 13        | 1.67%   |
| PANDA                   | 9         | 1.16%   |
| Chi Mei Optoelectronics | 8         | 1.03%   |
| LG Philips              | 6         | 0.77%   |
| Valve                   | 5         | 0.64%   |
| Sony                    | 5         | 0.64%   |
| InfoVision              | 5         | 0.64%   |
| Ancor Communications    | 5         | 0.64%   |
| Vestel Elektronik       | 4         | 0.51%   |
| MSI                     | 4         | 0.51%   |
| ASUSTek Computer        | 4         | 0.51%   |
| ___                     | 3         | 0.39%   |
| Unknown                 | 3         | 0.39%   |
| Toshiba                 | 3         | 0.39%   |
| HKC                     | 3         | 0.39%   |
| HannStar                | 3         | 0.39%   |
| CSO                     | 3         | 0.39%   |
| OEM                     | 2         | 0.26%   |
| NEC Computers           | 2         | 0.26%   |
| MiTAC                   | 2         | 0.26%   |
| KDB                     | 2         | 0.26%   |
| HUAWEI                  | 2         | 0.26%   |
| HannStar Display        | 2         | 0.26%   |
| CPT                     | 2         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                | 9         | 1.1%    |
| ViewSonic VP2756-2K VSCE63B 2560x1440 597x336mm 27.0-inch            | 8         | 0.98%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                    | 8         | 0.98%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 5         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 5         | 0.61%   |
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                 | 5         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 5         | 0.61%   |
| BOE LCD Monitor BOE0964 1920x1200 286x179mm 13.3-inch                | 5         | 0.61%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch              | 5         | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 5         | 0.61%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 5         | 0.61%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                        | 4         | 0.49%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch | 4         | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 4         | 0.49%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 4         | 0.49%   |
| ___ LCDTV16 ___9000 1360x768                                         | 3         | 0.37%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 3         | 0.37%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 3         | 0.37%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 3         | 0.37%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 3         | 0.37%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 3         | 0.37%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 3         | 0.37%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 3         | 0.37%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 0.37%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 3         | 0.37%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch              | 3         | 0.37%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                     | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch     | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 0.37%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 0.37%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 3         | 0.37%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch              | 2         | 0.24%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 2         | 0.24%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch              | 2         | 0.24%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch              | 2         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 343       | 46.41%  |
| 1366x768 (WXGA)    | 119       | 16.1%   |
| 3840x2160 (4K)     | 44        | 5.95%   |
| 2560x1440 (QHD)    | 43        | 5.82%   |
| 1920x1200 (WUXGA)  | 24        | 3.25%   |
| 1600x900 (HD+)     | 23        | 3.11%   |
| 1280x1024 (SXGA)   | 22        | 2.98%   |
| 1440x900 (WXGA+)   | 19        | 2.57%   |
| 1280x800 (WXGA)    | 15        | 2.03%   |
| 3440x1440          | 13        | 1.76%   |
| 1360x768           | 8         | 1.08%   |
| Unknown            | 8         | 1.08%   |
| 2560x1600          | 7         | 0.95%   |
| 1680x1050 (WSXGA+) | 7         | 0.95%   |
| 800x1280           | 6         | 0.81%   |
| 2880x1800          | 6         | 0.81%   |
| 3840x1080          | 4         | 0.54%   |
| 3840x2400          | 3         | 0.41%   |
| 3456x2160          | 3         | 0.41%   |
| 3200x1800 (QHD+)   | 3         | 0.41%   |
| 1600x1200          | 3         | 0.41%   |
| 1024x600           | 3         | 0.41%   |
| 2560x1080          | 2         | 0.27%   |
| 2160x1440          | 2         | 0.27%   |
| 1920x540           | 2         | 0.27%   |
| 1024x768 (XGA)     | 2         | 0.27%   |
| 6400x2160          | 1         | 0.14%   |
| 5280x2560          | 1         | 0.14%   |
| 4480x1440          | 1         | 0.14%   |
| 3600x1080          | 1         | 0.14%   |
| 2256x1504          | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 201       | 25.77%  |
| 14      | 77        | 9.87%   |
| 13      | 74        | 9.49%   |
| 27      | 71        | 9.1%    |
| 24      | 58        | 7.44%   |
| 21      | 49        | 6.28%   |
| 23      | 45        | 5.77%   |
| 17      | 36        | 4.62%   |
| Unknown | 28        | 3.59%   |
| 12      | 20        | 2.56%   |
| 19      | 18        | 2.31%   |
| 34      | 14        | 1.79%   |
| 31      | 12        | 1.54%   |
| 84      | 7         | 0.9%    |
| 18      | 7         | 0.9%    |
| 11      | 7         | 0.9%    |
| 16      | 6         | 0.77%   |
| 72      | 5         | 0.64%   |
| 33      | 5         | 0.64%   |
| 32      | 5         | 0.64%   |
| 22      | 5         | 0.64%   |
| 20      | 5         | 0.64%   |
| 7       | 5         | 0.64%   |
| 40      | 3         | 0.38%   |
| 25      | 3         | 0.38%   |
| 10      | 3         | 0.38%   |
| 49      | 2         | 0.26%   |
| 29      | 2         | 0.26%   |
| 65      | 1         | 0.13%   |
| 46      | 1         | 0.13%   |
| 39      | 1         | 0.13%   |
| 35      | 1         | 0.13%   |
| 28      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |
| 3       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 307       | 40.13%  |
| 501-600     | 159       | 20.78%  |
| 201-300     | 80        | 10.46%  |
| 401-500     | 74        | 9.67%   |
| 351-400     | 43        | 5.62%   |
| Unknown     | 28        | 3.66%   |
| 701-800     | 24        | 3.14%   |
| 601-700     | 23        | 3.01%   |
| 1501-2000   | 12        | 1.57%   |
| 1-100       | 6         | 0.78%   |
| 801-900     | 4         | 0.52%   |
| 1001-1500   | 4         | 0.52%   |
| 901-1000    | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 521       | 76.39%  |
| 16/10   | 82        | 12.02%  |
| Unknown | 23        | 3.37%   |
| 5/4     | 21        | 3.08%   |
| 21/9    | 16        | 2.35%   |
| 4/3     | 7         | 1.03%   |
| 3/2     | 5         | 0.73%   |
| 0.67    | 5         | 0.73%   |
| 6/5     | 1         | 0.15%   |
| 32/9    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 198       | 25.42%  |
| 201-250        | 127       | 16.3%   |
| 81-90          | 110       | 14.12%  |
| 301-350        | 73        | 9.37%   |
| 71-80          | 43        | 5.52%   |
| 351-500        | 37        | 4.75%   |
| 151-200        | 34        | 4.36%   |
| Unknown        | 28        | 3.59%   |
| 251-300        | 25        | 3.21%   |
| 121-130        | 20        | 2.57%   |
| 61-70          | 18        | 2.31%   |
| 141-150        | 17        | 2.18%   |
| More than 1000 | 13        | 1.67%   |
| 111-120        | 8         | 1.03%   |
| 51-60          | 7         | 0.9%    |
| 501-1000       | 7         | 0.9%    |
| 1-40           | 6         | 0.77%   |
| 131-140        | 4         | 0.51%   |
| 41-50          | 3         | 0.39%   |
| 91-100         | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 233       | 31.03%  |
| 51-100        | 214       | 28.5%   |
| 101-120       | 178       | 23.7%   |
| 161-240       | 62        | 8.26%   |
| Unknown       | 28        | 3.73%   |
| More than 240 | 22        | 2.93%   |
| 1-50          | 14        | 1.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 553       | 76.49%  |
| 2     | 114       | 15.77%  |
| 0     | 31        | 4.29%   |
| 3     | 24        | 3.32%   |
| 4     | 1         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 382       | 34.79%  |
| Realtek Semiconductor             | 347       | 31.6%   |
| Qualcomm Atheros                  | 99        | 9.02%   |
| Broadcom                          | 69        | 6.28%   |
| Ralink Technology                 | 22        | 2%      |
| MediaTek                          | 22        | 2%      |
| TP-Link                           | 19        | 1.73%   |
| Nvidia                            | 14        | 1.28%   |
| Broadcom Limited                  | 14        | 1.28%   |
| Marvell Technology Group          | 12        | 1.09%   |
| Ralink                            | 11        | 1%      |
| Microsoft                         | 9         | 0.82%   |
| ASIX Electronics                  | 8         | 0.73%   |
| Samsung Electronics               | 6         | 0.55%   |
| Lenovo                            | 6         | 0.55%   |
| OPPO Electronics                  | 5         | 0.46%   |
| Ericsson Business Mobile Networks | 5         | 0.46%   |
| DisplayLink                       | 5         | 0.46%   |
| Xiaomi                            | 3         | 0.27%   |
| NetGear                           | 3         | 0.27%   |
| Dell                              | 3         | 0.27%   |
| Qualcomm Atheros Communications   | 2         | 0.18%   |
| Qualcomm                          | 2         | 0.18%   |
| Microchip Technology              | 2         | 0.18%   |
| ICS Advent                        | 2         | 0.18%   |
| Huawei Technologies               | 2         | 0.18%   |
| Belkin Components                 | 2         | 0.18%   |
| Xilinx                            | 1         | 0.09%   |
| Van Ooijen Technische Informatica | 1         | 0.09%   |
| ULi Electronics                   | 1         | 0.09%   |
| Toshiba                           | 1         | 0.09%   |
| T & A Mobile Phones               | 1         | 0.09%   |
| Standard Microsystems             | 1         | 0.09%   |
| Sierra Wireless                   | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.09%   |
| NetXen Incorporated               | 1         | 0.09%   |
| LSI                               | 1         | 0.09%   |
| LG Electronics                    | 1         | 0.09%   |
| JMicron Technology                | 1         | 0.09%   |
| IMC Networks                      | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 210       | 16.25%  |
| Intel Wi-Fi 6 AX200                                                    | 45        | 3.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 45        | 3.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 39        | 3.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 32        | 2.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 25        | 1.93%   |
| Intel Wi-Fi 6 AX201                                                    | 23        | 1.78%   |
| Intel Wireless 8265 / 8275                                             | 20        | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 20        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 18        | 1.39%   |
| Intel Wireless 7260                                                    | 16        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 15        | 1.16%   |
| Intel Wireless 8260                                                    | 15        | 1.16%   |
| Intel Wireless 7265                                                    | 14        | 1.08%   |
| Intel Ethernet Connection I217-LM                                      | 14        | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 13        | 1.01%   |
| Realtek 802.11ac NIC                                                   | 13        | 1.01%   |
| Ralink MT7601U Wireless Adapter                                        | 12        | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11        | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 0.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 11        | 0.85%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 11        | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 11        | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 10        | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 10        | 0.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 9         | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 9         | 0.7%    |
| Intel Wireless 3165                                                    | 9         | 0.7%    |
| Intel Ethernet Connection I218-LM                                      | 9         | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 9         | 0.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 8         | 0.62%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 8         | 0.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 8         | 0.62%   |
| Ralink RT5370 Wireless Adapter                                         | 7         | 0.54%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 0.54%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 7         | 0.54%   |
| Intel Ethernet Connection (4) I219-V                                   | 7         | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 7         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 301       | 47.18%  |
| Realtek Semiconductor           | 97        | 15.2%   |
| Qualcomm Atheros                | 89        | 13.95%  |
| Broadcom                        | 48        | 7.52%   |
| Ralink Technology               | 22        | 3.45%   |
| TP-Link                         | 19        | 2.98%   |
| MediaTek                        | 19        | 2.98%   |
| Ralink                          | 11        | 1.72%   |
| Microsoft                       | 8         | 1.25%   |
| Broadcom Limited                | 6         | 0.94%   |
| NetGear                         | 3         | 0.47%   |
| Dell                            | 3         | 0.47%   |
| Qualcomm Atheros Communications | 2         | 0.31%   |
| Qualcomm                        | 2         | 0.31%   |
| Belkin Components               | 2         | 0.31%   |
| Sierra Wireless                 | 1         | 0.16%   |
| Marvell Technology Group        | 1         | 0.16%   |
| LG Electronics                  | 1         | 0.16%   |
| IMC Networks                    | 1         | 0.16%   |
| ASUSTek Computer                | 1         | 0.16%   |
| Apple                           | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 45        | 6.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 25        | 3.88%   |
| Intel Wi-Fi 6 AX201                                                     | 23        | 3.57%   |
| Intel Wireless 8265 / 8275                                              | 20        | 3.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 3.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 2.8%    |
| Intel Wireless 7260                                                     | 16        | 2.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 2.33%   |
| Intel Wireless 8260                                                     | 15        | 2.33%   |
| Intel Wireless 7265                                                     | 14        | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 2.02%   |
| Realtek 802.11ac NIC                                                    | 13        | 2.02%   |
| Ralink MT7601U Wireless Adapter                                         | 12        | 1.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 1.71%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 11        | 1.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 1.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 1.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 1.55%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 9         | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.4%    |
| Intel Wireless 3165                                                     | 9         | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.24%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 8         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.24%   |
| Ralink RT5370 Wireless Adapter                                          | 7         | 1.09%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 7         | 1.09%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 7         | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.93%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 6         | 0.93%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 0.93%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 5         | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.78%   |
| Intel Wireless 3160                                                     | 5         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 297       | 47.75%  |
| Intel                         | 190       | 30.55%  |
| Broadcom                      | 31        | 4.98%   |
| Qualcomm Atheros              | 19        | 3.05%   |
| Nvidia                        | 14        | 2.25%   |
| Marvell Technology Group      | 11        | 1.77%   |
| Broadcom Limited              | 9         | 1.45%   |
| ASIX Electronics              | 8         | 1.29%   |
| Samsung Electronics           | 6         | 0.96%   |
| Lenovo                        | 6         | 0.96%   |
| OPPO Electronics              | 5         | 0.8%    |
| DisplayLink                   | 5         | 0.8%    |
| Xiaomi                        | 3         | 0.48%   |
| MediaTek                      | 2         | 0.32%   |
| ICS Advent                    | 2         | 0.32%   |
| Xilinx                        | 1         | 0.16%   |
| ULi Electronics               | 1         | 0.16%   |
| T & A Mobile Phones           | 1         | 0.16%   |
| Standard Microsystems         | 1         | 0.16%   |
| OnePlus Technology (Shenzhen) | 1         | 0.16%   |
| NetXen Incorporated           | 1         | 0.16%   |
| Microsoft                     | 1         | 0.16%   |
| Microchip Technology          | 1         | 0.16%   |
| JMicron Technology            | 1         | 0.16%   |
| Huawei Technologies           | 1         | 0.16%   |
| HMD Global                    | 1         | 0.16%   |
| Aquantia                      | 1         | 0.16%   |
| ADMtek                        | 1         | 0.16%   |
| 3Com                          | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 210       | 33.23%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 45        | 7.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 39        | 6.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 32        | 5.06%   |
| Intel Ethernet Connection I217-LM                                      | 14        | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11        | 1.74%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 1.74%   |
| Intel Ethernet Connection I218-LM                                      | 9         | 1.42%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 1.11%   |
| Intel Ethernet Connection (4) I219-V                                   | 7         | 1.11%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 7         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 0.95%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 5         | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.79%   |
| Intel Ethernet Connection (2) I218-V                                   | 5         | 0.79%   |
| Intel Ethernet Connection (10) I219-V                                  | 5         | 0.79%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 5         | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.63%   |
| Realtek Killer E2600 GbE Controller                                    | 4         | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 4         | 0.63%   |
| Intel Ethernet Controller I225-V                                       | 4         | 0.63%   |
| Intel Ethernet Connection I219-V                                       | 4         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 0.63%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.63%   |
| Intel Ethernet Connection (11) I219-LM                                 | 4         | 0.63%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.63%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 3         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.47%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 3         | 0.47%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.47%   |
| Intel Ethernet Controller I225-LM                                      | 3         | 0.47%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.47%   |
| Intel Ethernet Connection I217-V                                       | 3         | 0.47%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 597       | 49.75%  |
| Ethernet | 587       | 48.92%  |
| Modem    | 16        | 1.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 448       | 60.87%  |
| Ethernet | 288       | 39.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 395       | 56.19%  |
| 1     | 276       | 39.26%  |
| 0     | 17        | 2.42%   |
| 3     | 13        | 1.85%   |
| 6     | 1         | 0.14%   |
| 4     | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 599       | 84.25%  |
| Yes  | 112       | 15.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 244       | 50.73%  |
| Realtek Semiconductor           | 44        | 9.15%   |
| Qualcomm Atheros Communications | 27        | 5.61%   |
| IMC Networks                    | 27        | 5.61%   |
| Cambridge Silicon Radio         | 27        | 5.61%   |
| Broadcom                        | 26        | 5.41%   |
| Apple                           | 18        | 3.74%   |
| Lite-On Technology              | 17        | 3.53%   |
| Foxconn / Hon Hai               | 11        | 2.29%   |
| Dell                            | 8         | 1.66%   |
| ASUSTek Computer                | 7         | 1.46%   |
| Hewlett-Packard                 | 5         | 1.04%   |
| Toshiba                         | 4         | 0.83%   |
| Realtek                         | 4         | 0.83%   |
| TP-Link                         | 2         | 0.42%   |
| MediaTek                        | 2         | 0.42%   |
| Foxconn International           | 2         | 0.42%   |
| Belkin Components               | 2         | 0.42%   |
| SiW                             | 1         | 0.21%   |
| Ralink                          | 1         | 0.21%   |
| Edimax Technology               | 1         | 0.21%   |
| Conwise Technology              | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 51        | 10.56%  |
| Intel Bluetooth wireless interface                  | 49        | 10.14%  |
| Intel AX200 Bluetooth                               | 42        | 8.7%    |
| Intel Bluetooth Device                              | 34        | 7.04%   |
| Realtek Bluetooth Radio                             | 32        | 6.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 27        | 5.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 16        | 3.31%   |
| Intel AX211 Bluetooth                               | 16        | 3.31%   |
| IMC Networks Bluetooth Radio                        | 14        | 2.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 2.07%   |
| Apple Bluetooth Host Controller                     | 9         | 1.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 1.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 1.24%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 1.24%   |
| Intel AX210 Bluetooth                               | 6         | 1.24%   |
| IMC Networks Wireless_Device                        | 6         | 1.24%   |
| IMC Networks Bluetooth Device                       | 5         | 1.04%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.83%   |
| Realtek Bluetooth Radio                             | 4         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 0.83%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 0.83%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.83%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 0.83%   |
| Apple Bluetooth HCI                                 | 4         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.62%   |
| Lite-On Wireless_Device                             | 3         | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.62%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.62%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.62%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.62%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.62%   |
| TP-Link UB500 Adapter                               | 2         | 0.41%   |
| Toshiba Bluetooth Device                            | 2         | 0.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.41%   |
| MediaTek Wireless_Device                            | 2         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 498       | 50.87%  |
| AMD                                             | 212       | 21.65%  |
| Nvidia                                          | 156       | 15.93%  |
| Realtek Semiconductor                           | 12        | 1.23%   |
| Plantronics                                     | 11        | 1.12%   |
| C-Media Electronics                             | 10        | 1.02%   |
| Creative Labs                                   | 7         | 0.72%   |
| Logitech                                        | 6         | 0.61%   |
| Kingston Technology                             | 6         | 0.61%   |
| GN Netcom                                       | 6         | 0.61%   |
| Creative Technology                             | 5         | 0.51%   |
| Lenovo                                          | 4         | 0.41%   |
| Texas Instruments                               | 3         | 0.31%   |
| RODE Microphones                                | 3         | 0.31%   |
| Sony                                            | 2         | 0.2%    |
| Micronas                                        | 2         | 0.2%    |
| JMTek                                           | 2         | 0.2%    |
| Giga-Byte Technology                            | 2         | 0.2%    |
| Generalplus Technology                          | 2         | 0.2%    |
| Ensoniq                                         | 2         | 0.2%    |
| Dell                                            | 2         | 0.2%    |
| Blue Microphones                                | 2         | 0.2%    |
| VIA Technologies                                | 1         | 0.1%    |
| ULi Electronics                                 | 1         | 0.1%    |
| Turtle Beach                                    | 1         | 0.1%    |
| Thesycon Systemsoftware & Consulting            | 1         | 0.1%    |
| SAVITECH                                        | 1         | 0.1%    |
| Razer USA                                       | 1         | 0.1%    |
| No brand                                        | 1         | 0.1%    |
| Native Instruments                              | 1         | 0.1%    |
| M-Audio                                         | 1         | 0.1%    |
| Licensed by Sony Computer Entertainment America | 1         | 0.1%    |
| KTMicro                                         | 1         | 0.1%    |
| Huawei Technologies                             | 1         | 0.1%    |
| Focusrite-Novation                              | 1         | 0.1%    |
| FiiO Electronics Technology                     | 1         | 0.1%    |
| ESS Technology                                  | 1         | 0.1%    |
| DSEA A/S                                        | 1         | 0.1%    |
| Corsair                                         | 1         | 0.1%    |
| Conexant Systems                                | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 72        | 6.22%   |
| Intel Sunrise Point-LP HD Audio                                            | 62        | 5.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 55        | 4.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 48        | 4.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 30        | 2.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 30        | 2.59%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 30        | 2.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 24        | 2.07%   |
| AMD Starship/Matisse HD Audio Controller                                   | 23        | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20        | 1.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 19        | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 19        | 1.64%   |
| Intel Comet Lake PCH-LP cAVS                                               | 18        | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 18        | 1.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 18        | 1.56%   |
| AMD FCH Azalia Controller                                                  | 18        | 1.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 18        | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 16        | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15        | 1.3%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 15        | 1.3%    |
| Nvidia GP106 High Definition Audio Controller                              | 14        | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 14        | 1.21%   |
| AMD Kabini HDMI/DP Audio                                                   | 14        | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13        | 1.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 1.12%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 1.12%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 1.12%   |
| Realtek Semiconductor USB Audio                                            | 12        | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 12        | 1.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 12        | 1.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12        | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 11        | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 11        | 0.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 11        | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                              | 10        | 0.86%   |
| Nvidia GM204 High Definition Audio Controller                              | 9         | 0.78%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 9         | 0.78%   |
| Intel CM238 HD Audio Controller                                            | 9         | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 9         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 94        | 21.32%  |
| SK hynix            | 86        | 19.5%   |
| Micron Technology   | 46        | 10.43%  |
| Kingston            | 41        | 9.3%    |
| Crucial             | 39        | 8.84%   |
| Unknown             | 38        | 8.62%   |
| Corsair             | 37        | 8.39%   |
| Ramaxel Technology  | 12        | 2.72%   |
| G.Skill             | 9         | 2.04%   |
| Elpida              | 6         | 1.36%   |
| Nanya Technology    | 5         | 1.13%   |
| Unknown (ABCD)      | 4         | 0.91%   |
| Team                | 3         | 0.68%   |
| Patriot             | 3         | 0.68%   |
| Apacer              | 3         | 0.68%   |
| A-DATA Technology   | 3         | 0.68%   |
| A Force             | 2         | 0.45%   |
| Transcend           | 1         | 0.23%   |
| Toshiba             | 1         | 0.23%   |
| Silicon Power       | 1         | 0.23%   |
| SHARETRONIC         | 1         | 0.23%   |
| OSV                 | 1         | 0.23%   |
| Infineon            | 1         | 0.23%   |
| CSX                 | 1         | 0.23%   |
| BiNFUL              | 1         | 0.23%   |
| 4ea5                | 1         | 0.23%   |
| Unknown             | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.91%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 1.27%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.27%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 6         | 1.27%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.85%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.64%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.64%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.64%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.64%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 3         | 0.64%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.64%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s             | 3         | 0.64%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 3         | 0.64%   |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s          | 3         | 0.64%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.42%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.42%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 0.42%   |
| Team RAM Elite-1333 2GB DIMM DDR3 1333MT/s                       | 2         | 0.42%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.42%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.42%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.42%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.42%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s             | 2         | 0.42%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.42%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.42%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.42%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.42%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.42%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.42%   |
| SK hynix RAM H54G56CYRBX247N 2GB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.42%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 177       | 46.46%  |
| DDR3    | 111       | 29.13%  |
| LPDDR4  | 21        | 5.51%   |
| DDR2    | 16        | 4.2%    |
| Unknown | 15        | 3.94%   |
| SDRAM   | 11        | 2.89%   |
| LPDDR3  | 10        | 2.62%   |
| DDR5    | 10        | 2.62%   |
| LPDDR5  | 4         | 1.05%   |
| DRAM    | 3         | 0.79%   |
| DDR     | 3         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 228       | 59.69%  |
| DIMM         | 114       | 29.84%  |
| Row Of Chips | 31        | 8.12%   |
| Chip         | 5         | 1.31%   |
| Unknown      | 4         | 1.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 160       | 38.46%  |
| 4096  | 110       | 26.44%  |
| 16384 | 66        | 15.87%  |
| 2048  | 44        | 10.58%  |
| 32768 | 18        | 4.33%   |
| 1024  | 14        | 3.37%   |
| 128   | 2         | 0.48%   |
| 512   | 1         | 0.24%   |
| 256   | 1         | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 73        | 17.51%  |
| 3200    | 61        | 14.63%  |
| 2667    | 55        | 13.19%  |
| 2400    | 30        | 7.19%   |
| 2133    | 25        | 6%      |
| 1333    | 22        | 5.28%   |
| 800     | 16        | 3.84%   |
| 4267    | 12        | 2.88%   |
| 3600    | 12        | 2.88%   |
| 667     | 12        | 2.88%   |
| 1334    | 11        | 2.64%   |
| 3266    | 10        | 2.4%    |
| 1867    | 9         | 2.16%   |
| 4800    | 7         | 1.68%   |
| 1067    | 6         | 1.44%   |
| Unknown | 5         | 1.2%    |
| 1866    | 4         | 0.96%   |
| 8400    | 3         | 0.72%   |
| 6400    | 3         | 0.72%   |
| 4266    | 3         | 0.72%   |
| 3800    | 3         | 0.72%   |
| 1800    | 3         | 0.72%   |
| 1066    | 3         | 0.72%   |
| 533     | 3         | 0.72%   |
| 5600    | 2         | 0.48%   |
| 4199    | 2         | 0.48%   |
| 3400    | 2         | 0.48%   |
| 2666    | 2         | 0.48%   |
| 2048    | 2         | 0.48%   |
| 1648    | 2         | 0.48%   |
| 975     | 2         | 0.48%   |
| 7500    | 1         | 0.24%   |
| 6000    | 1         | 0.24%   |
| 5200    | 1         | 0.24%   |
| 3866    | 1         | 0.24%   |
| 3733    | 1         | 0.24%   |
| 3467    | 1         | 0.24%   |
| 3000    | 1         | 0.24%   |
| 2933    | 1         | 0.24%   |
| 2733    | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 3         | 33.33%  |
| STMicroelectronics  | 2         | 22.22%  |
| Brother Industries  | 2         | 22.22%  |
| Samsung Electronics | 1         | 11.11%  |
| Hewlett-Packard     | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 22.22%  |
| Samsung M2070 Series                                      | 1         | 11.11%  |
| HP Officejet 4500 G510g-m                                 | 1         | 11.11%  |
| Canon TS5300 series                                       | 1         | 11.11%  |
| Canon PIXMA MG3600 Series                                 | 1         | 11.11%  |
| Canon PIXMA MG2500 Series                                 | 1         | 11.11%  |
| Brother MFC-L2700DW                                       | 1         | 11.11%  |
| Brother HL-L2340D series                                  | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 105       | 22.88%  |
| Microdia                               | 47        | 10.24%  |
| Realtek Semiconductor                  | 46        | 10.02%  |
| IMC Networks                           | 42        | 9.15%   |
| Sunplus Innovation Technology          | 29        | 6.32%   |
| Logitech                               | 29        | 6.32%   |
| Bison Electronics                      | 24        | 5.23%   |
| Quanta                                 | 22        | 4.79%   |
| Apple                                  | 18        | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 2.4%    |
| Acer                                   | 11        | 2.4%    |
| Samsung Electronics                    | 7         | 1.53%   |
| Suyin                                  | 6         | 1.31%   |
| Microsoft                              | 6         | 1.31%   |
| Lite-On Technology                     | 6         | 1.31%   |
| Sonix Technology                       | 5         | 1.09%   |
| Ricoh                                  | 5         | 1.09%   |
| ALi                                    | 5         | 1.09%   |
| Syntek                                 | 4         | 0.87%   |
| Silicon Motion                         | 4         | 0.87%   |
| SunplusIT                              | 3         | 0.65%   |
| Lenovo                                 | 2         | 0.44%   |
| Generalplus Technology                 | 2         | 0.44%   |
| Creative Technology                    | 2         | 0.44%   |
| Alcor Micro                            | 2         | 0.44%   |
| Z-Star Microelectronics                | 1         | 0.22%   |
| Y Media                                | 1         | 0.22%   |
| WaveRider Communications               | 1         | 0.22%   |
| USB3.0 HD Audio Capture                | 1         | 0.22%   |
| Trust                                  | 1         | 0.22%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.22%   |
| Razer USA                              | 1         | 0.22%   |
| Nokia Mobile Phones                    | 1         | 0.22%   |
| Nikon                                  | 1         | 0.22%   |
| MacroSilicon                           | 1         | 0.22%   |
| Luxvisions Innotech Limited            | 1         | 0.22%   |
| GenesysLogic Technology                | 1         | 0.22%   |
| GEMBIRD                                | 1         | 0.22%   |
| DigiTech                               | 1         | 0.22%   |
| ARC International                      | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 26        | 5.6%    |
| Microdia Integrated_Webcam_HD           | 21        | 4.53%   |
| Realtek Integrated_Webcam_HD            | 16        | 3.45%   |
| IMC Networks Integrated Camera          | 15        | 3.23%   |
| Logitech HD Pro Webcam C920             | 12        | 2.59%   |
| Apple Built-in iSight                   | 10        | 2.16%   |
| IMC Networks USB2.0 HD UVC WebCam       | 9         | 1.94%   |
| Bison Integrated Camera                 | 9         | 1.94%   |
| Sunplus Integrated_Webcam_HD            | 8         | 1.72%   |
| Sunplus Integrated_Webcam_FHD           | 8         | 1.72%   |
| Chicony USB2.0 Camera                   | 8         | 1.72%   |
| Chicony HD WebCam                       | 8         | 1.72%   |
| Samsung Galaxy series, misc. (MTP mode) | 7         | 1.51%   |
| Microdia Integrated Webcam              | 6         | 1.29%   |
| Microsoft LifeCam HD-3000               | 5         | 1.08%   |
| Lite-On HP HD Camera                    | 5         | 1.08%   |
| Chicony HP Wide Vision HD Camera        | 5         | 1.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 5         | 1.08%   |
| Realtek USB Camera                      | 4         | 0.86%   |
| Realtek Integrated Webcam HD            | 4         | 0.86%   |
| Microdia Webcam Vitade AF               | 4         | 0.86%   |
| Microdia USB 2.0 Camera                 | 4         | 0.86%   |
| Logitech Webcam C270                    | 4         | 0.86%   |
| Chicony USB2.0 HD UVC WebCam            | 4         | 0.86%   |
| Bison EasyCamera                        | 4         | 0.86%   |
| Apple FaceTime HD Camera (Built-in)     | 4         | 0.86%   |
| Acer Integrated Camera                  | 4         | 0.86%   |
| Sonix USB2.0 FHD UVC WebCam             | 3         | 0.65%   |
| Realtek USB2.0 HD UVC WebCam            | 3         | 0.65%   |
| Realtek EasyCamera                      | 3         | 0.65%   |
| Quanta HP HD Camera                     | 3         | 0.65%   |
| Quanta HD User Facing                   | 3         | 0.65%   |
| Quanta ACER HD User Facing              | 3         | 0.65%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 3         | 0.65%   |
| IMC Networks EasyCamera                 | 3         | 0.65%   |
| Chicony VGA Webcam                      | 3         | 0.65%   |
| Chicony thinkpad t430s camera           | 3         | 0.65%   |
| Chicony Lenovo EasyCamera               | 3         | 0.65%   |
| Chicony Integrated Camera (1280x720@30) | 3         | 0.65%   |
| Chicony HP HD Camera                    | 3         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 31        | 34.83%  |
| Validity Sensors           | 23        | 25.84%  |
| Shenzhen Goodix Technology | 18        | 20.22%  |
| Upek                       | 4         | 4.49%   |
| Elan Microelectronics      | 4         | 4.49%   |
| AuthenTec                  | 4         | 4.49%   |
| LighTuning Technology      | 3         | 3.37%   |
| STMicroelectronics         | 1         | 1.12%   |
| Focal-systems.Corp         | 1         | 1.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                        | 8         | 8.99%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 7         | 7.87%   |
| Validity Sensors VFS495 Fingerprint Reader                | 6         | 6.74%   |
| Shenzhen Goodix FingerPrint                               | 6         | 6.74%   |
| Unknown                                                   | 5         | 5.62%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 4         | 4.49%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 4         | 4.49%   |
| Synaptics Fingerprint reader [HP G6]                      | 4         | 4.49%   |
| Shenzhen Goodix  Fingerprint Device                       | 4         | 4.49%   |
| Synaptics  WBDI                                           | 3         | 3.37%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 3         | 3.37%   |
| AuthenTec Fingerprint Sensor                              | 3         | 3.37%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 2         | 2.25%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 2.25%   |
| Validity Sensors VFS471 Fingerprint Reader                | 2         | 2.25%   |
| Validity Sensors VFS451 Fingerprint Reader                | 2         | 2.25%   |
| Validity Sensors VFS101 Fingerprint Reader                | 2         | 2.25%   |
| Validity Sensors Synaptics WBDI                           | 2         | 2.25%   |
| Synaptics WBDI Fingerprint Reader USB 086                 | 2         | 2.25%   |
| Elan ELAN:Fingerprint                                     | 2         | 2.25%   |
| Elan ELAN:ARM-M4                                          | 2         | 2.25%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 1.12%   |
| Validity Sensors VFS300 Fingerprint Reader                | 1         | 1.12%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 1.12%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 1.12%   |
| Validity Sensors Fingerprint scanner                      | 1         | 1.12%   |
| Synaptics WBDI                                            | 1         | 1.12%   |
| Synaptics UWP WBDI Device                                 | 1         | 1.12%   |
| Synaptics UWP WBDI                                        | 1         | 1.12%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.12%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 1         | 1.12%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 1.12%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 1.12%   |
| Focal-systems.Corp FT9201Fingerprint.                     | 1         | 1.12%   |
| AuthenTec AES2810                                         | 1         | 1.12%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 37        | 61.67%  |
| Alcor Micro                       | 9         | 15%     |
| Upek                              | 6         | 10%     |
| O2 Micro                          | 5         | 8.33%   |
| Lenovo                            | 2         | 3.33%   |
| Free Software Initiative of Japan | 1         | 1.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 17        | 28.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 15%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 15%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 10%     |
| Broadcom 5880                                                                | 6         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 6.67%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.67%   |
| Free Software Initiative of Japan Gnuk Token                                 | 1         | 1.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 462       | 63.99%  |
| 1     | 201       | 27.84%  |
| 2     | 49        | 6.79%   |
| 3     | 8         | 1.11%   |
| 5     | 1         | 0.14%   |
| 4     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 88        | 28.3%   |
| Net/wireless             | 64        | 20.58%  |
| Graphics card            | 56        | 18.01%  |
| Chipcard                 | 53        | 17.04%  |
| Multimedia controller    | 14        | 4.5%    |
| Camera                   | 9         | 2.89%   |
| Communication controller | 8         | 2.57%   |
| Storage                  | 5         | 1.61%   |
| Card reader              | 3         | 0.96%   |
| Bluetooth                | 3         | 0.96%   |
| Net/ethernet             | 2         | 0.64%   |
| Unassigned class         | 1         | 0.32%   |
| Storage/raid             | 1         | 0.32%   |
| Storage/ata              | 1         | 0.32%   |
| Sound                    | 1         | 0.32%   |
| Modem                    | 1         | 0.32%   |
| Firewire controller      | 1         | 0.32%   |

