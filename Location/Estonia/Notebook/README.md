Linux in Estonia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Estonia.

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

Total: 334

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8470p             | [7a5df9412c](https://linux-hardware.org/?probe=7a5df9412c) | Dec 31, 2024 |
| Dell          | Latitude 7640               | [931523acc9](https://linux-hardware.org/?probe=931523acc9) | Dec 28, 2024 |
| Dell          | System XPS 15Z              | [9e7fc2d36e](https://linux-hardware.org/?probe=9e7fc2d36e) | Dec 20, 2024 |
| Lenovo        | ThinkPad T60 1951FDG        | [9c3c2fb92b](https://linux-hardware.org/?probe=9c3c2fb92b) | Dec 13, 2024 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [b3ea15c92e](https://linux-hardware.org/?probe=b3ea15c92e) | Dec 12, 2024 |
| Lenovo        | ThinkPad T460s 20F9003RM... | [5092bec86b](https://linux-hardware.org/?probe=5092bec86b) | Dec 07, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [e51903f612](https://linux-hardware.org/?probe=e51903f612) | Dec 05, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4e0782715d](https://linux-hardware.org/?probe=4e0782715d) | Dec 02, 2024 |
| HP            | Laptop 15-db0xxx            | [469069638e](https://linux-hardware.org/?probe=469069638e) | Dec 01, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [458a67a9e4](https://linux-hardware.org/?probe=458a67a9e4) | Nov 30, 2024 |
| HP            | EliteBook 8470p             | [f03062334f](https://linux-hardware.org/?probe=f03062334f) | Nov 29, 2024 |
| Dell          | XPS 13 9310                 | [5a464dff99](https://linux-hardware.org/?probe=5a464dff99) | Nov 27, 2024 |
| Toshiba       | Satellite L870-120          | [44263921b6](https://linux-hardware.org/?probe=44263921b6) | Nov 26, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MCS... | [2d30a85677](https://linux-hardware.org/?probe=2d30a85677) | Nov 18, 2024 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [ccf9df80ca](https://linux-hardware.org/?probe=ccf9df80ca) | Nov 11, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [7b749bf585](https://linux-hardware.org/?probe=7b749bf585) | Nov 11, 2024 |
| Dell          | Latitude 7640               | [f092c8cc9f](https://linux-hardware.org/?probe=f092c8cc9f) | Oct 27, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | [25a5b7315a](https://linux-hardware.org/?probe=25a5b7315a) | Oct 21, 2024 |
| HP            | Compaq 6910p                | [2d33276514](https://linux-hardware.org/?probe=2d33276514) | Oct 17, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | [676dd2d194](https://linux-hardware.org/?probe=676dd2d194) | Oct 14, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [ec688a0cae](https://linux-hardware.org/?probe=ec688a0cae) | Oct 13, 2024 |
| Dell          | XPS L322X                   | [ebe83a8923](https://linux-hardware.org/?probe=ebe83a8923) | Oct 07, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | [d55aedf9d2](https://linux-hardware.org/?probe=d55aedf9d2) | Oct 06, 2024 |
| HP            | Laptop 14s-dq3xxx           | [e93a1db49f](https://linux-hardware.org/?probe=e93a1db49f) | Oct 06, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [76e2b2a322](https://linux-hardware.org/?probe=76e2b2a322) | Sep 22, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a8bb2af7ad](https://linux-hardware.org/?probe=a8bb2af7ad) | Sep 20, 2024 |
| HP            | EliteBook 835 G8 Noteboo... | [7b97957b7a](https://linux-hardware.org/?probe=7b97957b7a) | Sep 10, 2024 |
| HP            | Laptop 14s-dq3xxx           | [c107b751c7](https://linux-hardware.org/?probe=c107b751c7) | Sep 03, 2024 |
| HP            | Laptop 14s-dq3xxx           | [d05b98ac9f](https://linux-hardware.org/?probe=d05b98ac9f) | Sep 01, 2024 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [b3dd1179a9](https://linux-hardware.org/?probe=b3dd1179a9) | Aug 05, 2024 |
| Dell          | Latitude 3340               | [533fe2ea9d](https://linux-hardware.org/?probe=533fe2ea9d) | Aug 04, 2024 |
| Dell          | XPS L322X                   | [8b14979f7c](https://linux-hardware.org/?probe=8b14979f7c) | Jul 30, 2024 |
| Dell          | XPS L322X                   | [bf4c97865c](https://linux-hardware.org/?probe=bf4c97865c) | Jul 30, 2024 |
| Dell          | Latitude E7450              | [ba9d36e59d](https://linux-hardware.org/?probe=ba9d36e59d) | Jul 25, 2024 |
| Apple         | MacBookPro9,2               | [4f3c1e544b](https://linux-hardware.org/?probe=4f3c1e544b) | Jul 15, 2024 |
| Valve         | Jupiter                     | [c83514f0ef](https://linux-hardware.org/?probe=c83514f0ef) | Jul 13, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [8bc58488a8](https://linux-hardware.org/?probe=8bc58488a8) | Jul 09, 2024 |
| Acer          | Aspire 5755G                | [9d85820d8a](https://linux-hardware.org/?probe=9d85820d8a) | Jul 06, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8046341f97](https://linux-hardware.org/?probe=8046341f97) | Jul 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a4411a1a03](https://linux-hardware.org/?probe=a4411a1a03) | Jul 03, 2024 |
| Notebook      | PE60RNE_RND_RNC             | [82b61a10fa](https://linux-hardware.org/?probe=82b61a10fa) | Jul 03, 2024 |
| Valve         | Jupiter                     | [64bd09dae7](https://linux-hardware.org/?probe=64bd09dae7) | Jul 02, 2024 |
| Lenovo        | ThinkPad T470 20HES00300    | [a311daa558](https://linux-hardware.org/?probe=a311daa558) | Jul 01, 2024 |
| Lenovo        | ThinkPad T470 20HES00300    | [8df67624a1](https://linux-hardware.org/?probe=8df67624a1) | Jul 01, 2024 |
| Valve         | Jupiter                     | [7cb4543c27](https://linux-hardware.org/?probe=7cb4543c27) | Jun 30, 2024 |
| Dell          | Latitude 5431               | [b945bd0e46](https://linux-hardware.org/?probe=b945bd0e46) | Jun 21, 2024 |
| Dell          | XPS L322X                   | [1af333c86d](https://linux-hardware.org/?probe=1af333c86d) | Jun 18, 2024 |
| Dell          | XPS L322X                   | [34bcf0a790](https://linux-hardware.org/?probe=34bcf0a790) | Jun 18, 2024 |
| Dell          | Latitude 5431               | [7469c5f44a](https://linux-hardware.org/?probe=7469c5f44a) | Jun 17, 2024 |
| Lenovo        | V15-ADA 82C7                | [161e412652](https://linux-hardware.org/?probe=161e412652) | Jun 09, 2024 |
| Acer          | Aspire A315-24P             | [f265233665](https://linux-hardware.org/?probe=f265233665) | Jun 05, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | [8534f873cf](https://linux-hardware.org/?probe=8534f873cf) | May 24, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [548c48e57a](https://linux-hardware.org/?probe=548c48e57a) | May 21, 2024 |
| Dell          | XPS 13 9360                 | [536f8ed319](https://linux-hardware.org/?probe=536f8ed319) | May 09, 2024 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [ed0902f81c](https://linux-hardware.org/?probe=ed0902f81c) | May 08, 2024 |
| HP            | Laptop 14-ck0xxx            | [2dee9df53a](https://linux-hardware.org/?probe=2dee9df53a) | May 02, 2024 |
| Dell          | Latitude 3300               | [639fb8097f](https://linux-hardware.org/?probe=639fb8097f) | May 02, 2024 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [eefd534cd5](https://linux-hardware.org/?probe=eefd534cd5) | May 01, 2024 |
| Acer          | Extensa 5620                | [4150199b68](https://linux-hardware.org/?probe=4150199b68) | Apr 29, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [fad4840965](https://linux-hardware.org/?probe=fad4840965) | Apr 26, 2024 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | [01d705d92b](https://linux-hardware.org/?probe=01d705d92b) | Apr 25, 2024 |
| Apple         | MacBookPro5,3               | [4661f5b412](https://linux-hardware.org/?probe=4661f5b412) | Apr 08, 2024 |
| Lenovo        | ThinkPad T490s 20NX006HM... | [52e2e29f44](https://linux-hardware.org/?probe=52e2e29f44) | Mar 22, 2024 |
| Dell          | Inspiron 5558               | [2202cb6328](https://linux-hardware.org/?probe=2202cb6328) | Mar 21, 2024 |
| HP            | 650                         | [d58bfc527e](https://linux-hardware.org/?probe=d58bfc527e) | Mar 17, 2024 |
| Lenovo        | ThinkPad P50 20EN0007MS     | [8c9bcaf098](https://linux-hardware.org/?probe=8c9bcaf098) | Mar 14, 2024 |
| HP            | EliteBook 840 G5            | [16dee4c095](https://linux-hardware.org/?probe=16dee4c095) | Mar 13, 2024 |
| Dell          | Latitude 5420 Rugged        | [f9c7c915c9](https://linux-hardware.org/?probe=f9c7c915c9) | Mar 08, 2024 |
| Lenovo        | ThinkPad T470 20HDS01L00    | [d3de9797e5](https://linux-hardware.org/?probe=d3de9797e5) | Mar 07, 2024 |
| Lenovo        | ThinkPad T470 20HDS01L00    | [48c9ed444c](https://linux-hardware.org/?probe=48c9ed444c) | Mar 06, 2024 |
| Lenovo        | ThinkPad T480s 20L8002UM... | [a8c23be08a](https://linux-hardware.org/?probe=a8c23be08a) | Mar 05, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c2b5dc013f](https://linux-hardware.org/?probe=c2b5dc013f) | Mar 03, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7c8e1659f2](https://linux-hardware.org/?probe=7c8e1659f2) | Feb 24, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [b1c2e786ed](https://linux-hardware.org/?probe=b1c2e786ed) | Feb 17, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0ea90e3ee0](https://linux-hardware.org/?probe=0ea90e3ee0) | Feb 17, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [50746a2234](https://linux-hardware.org/?probe=50746a2234) | Feb 09, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [07deb1efe3](https://linux-hardware.org/?probe=07deb1efe3) | Feb 04, 2024 |
| Valve         | Jupiter                     | [ff59f7877a](https://linux-hardware.org/?probe=ff59f7877a) | Feb 02, 2024 |
| Dell          | Latitude 7490               | [d2085f3674](https://linux-hardware.org/?probe=d2085f3674) | Jan 24, 2024 |
| Dell          | Inspiron N5010              | [ab07a9741b](https://linux-hardware.org/?probe=ab07a9741b) | Jan 13, 2024 |
| MSI           | Pulse GL66 11UDK            | [fdb748bed5](https://linux-hardware.org/?probe=fdb748bed5) | Jan 13, 2024 |
| Dell          | Inspiron N5010              | [8991ffeadc](https://linux-hardware.org/?probe=8991ffeadc) | Jan 04, 2024 |
| Acer          | Nitro AN517-55              | [f3e3de235b](https://linux-hardware.org/?probe=f3e3de235b) | Dec 23, 2023 |
| HP            | ProBook 6570b               | [7dbd0f9be1](https://linux-hardware.org/?probe=7dbd0f9be1) | Dec 21, 2023 |
| HP            | ProBook 6570b               | [7a4a6018b6](https://linux-hardware.org/?probe=7a4a6018b6) | Dec 21, 2023 |
| TUXEDO        | Polaris AMD Gen5            | [84a93dbb91](https://linux-hardware.org/?probe=84a93dbb91) | Dec 19, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [646c403e2f](https://linux-hardware.org/?probe=646c403e2f) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [7fc71d8954](https://linux-hardware.org/?probe=7fc71d8954) | Dec 16, 2023 |
| Apple         | MacBookAir6,2               | [62734db5de](https://linux-hardware.org/?probe=62734db5de) | Dec 10, 2023 |
| HP            | ProBook 4530s               | [5743a3e441](https://linux-hardware.org/?probe=5743a3e441) | Nov 28, 2023 |
| Dell          | Precision M4600             | [864f0c5cfe](https://linux-hardware.org/?probe=864f0c5cfe) | Nov 22, 2023 |
| Dell          | Precision M4600             | [af124219eb](https://linux-hardware.org/?probe=af124219eb) | Nov 18, 2023 |
| Acer          | Predator PH317-53           | [84650e7d6f](https://linux-hardware.org/?probe=84650e7d6f) | Nov 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [0d9316dbcf](https://linux-hardware.org/?probe=0d9316dbcf) | Oct 31, 2023 |
| HP            | 250 G5 Notebook PC          | [bc710e10c6](https://linux-hardware.org/?probe=bc710e10c6) | Oct 27, 2023 |
| Lenovo        | ThinkPad T440p 20AWS49Q0... | [65fa77246e](https://linux-hardware.org/?probe=65fa77246e) | Sep 21, 2023 |
| Dell          | Latitude E5550              | [9044f3b345](https://linux-hardware.org/?probe=9044f3b345) | Sep 12, 2023 |
| HP            | 250 G5 Notebook PC          | [773143cf61](https://linux-hardware.org/?probe=773143cf61) | Sep 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | [3d7ba31c2a](https://linux-hardware.org/?probe=3d7ba31c2a) | Aug 24, 2023 |
| Lenovo        | ThinkPad P50 20EQS4XN00     | [a517cc57b8](https://linux-hardware.org/?probe=a517cc57b8) | Aug 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | [cb5346a558](https://linux-hardware.org/?probe=cb5346a558) | Aug 17, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | [4bfb2c68ca](https://linux-hardware.org/?probe=4bfb2c68ca) | Aug 17, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| Dell          | Vostro 3700                 | [96e4579b7b](https://linux-hardware.org/?probe=96e4579b7b) | Aug 01, 2023 |
| Intel         | powered classmate PC        | [ccbb0cb45a](https://linux-hardware.org/?probe=ccbb0cb45a) | Jul 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00bda81c25](https://linux-hardware.org/?probe=00bda81c25) | Jul 19, 2023 |
| HP            | ProBook 640 G1              | [8c2fd03132](https://linux-hardware.org/?probe=8c2fd03132) | Jul 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| Lenovo        | ThinkPad L480 20LTSAK70R    | [551d238ad3](https://linux-hardware.org/?probe=551d238ad3) | May 16, 2023 |
| Notebook      | N150SD/N155SD               | [55f219bc3f](https://linux-hardware.org/?probe=55f219bc3f) | May 11, 2023 |
| ASUSTek       | N550JK                      | [a799667521](https://linux-hardware.org/?probe=a799667521) | May 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [fdaef83d1e](https://linux-hardware.org/?probe=fdaef83d1e) | Apr 23, 2023 |
| MSI           | GF63 Thin 10SCXR            | [33e5d369a7](https://linux-hardware.org/?probe=33e5d369a7) | Apr 04, 2023 |
| Apple         | MacBookPro5,1               | [b06257fd9c](https://linux-hardware.org/?probe=b06257fd9c) | Mar 28, 2023 |
| Apple         | MacBookPro5,1               | [3a0d77d195](https://linux-hardware.org/?probe=3a0d77d195) | Mar 28, 2023 |
| Gigabyte      | G5 KD                       | [32afc6a4cf](https://linux-hardware.org/?probe=32afc6a4cf) | Mar 23, 2023 |
| Apple         | MacBookPro9,2               | [4efbf8be88](https://linux-hardware.org/?probe=4efbf8be88) | Mar 23, 2023 |
| GPD           | G1619-04                    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [c87313bdd4](https://linux-hardware.org/?probe=c87313bdd4) | Mar 20, 2023 |
| Lenovo        | ThinkPad T540p 20BFS3BR0... | [6218acf76f](https://linux-hardware.org/?probe=6218acf76f) | Mar 12, 2023 |
| Packard Be... | EasyNote TK87               | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| Packard Be... | EasyNote TK87               | [f1c4c8b89e](https://linux-hardware.org/?probe=f1c4c8b89e) | Jan 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [ff12fe840d](https://linux-hardware.org/?probe=ff12fe840d) | Jan 12, 2023 |
| HP            | EliteBook 840 G2            | [4a85ebbc33](https://linux-hardware.org/?probe=4a85ebbc33) | Dec 26, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [d8b614d1ca](https://linux-hardware.org/?probe=d8b614d1ca) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1f904e68af](https://linux-hardware.org/?probe=1f904e68af) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| ASUSTek       | N53Jf                       | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [b792955af6](https://linux-hardware.org/?probe=b792955af6) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [033e206fab](https://linux-hardware.org/?probe=033e206fab) | Nov 25, 2022 |
| Valve         | Jupiter                     | [0e77de9dba](https://linux-hardware.org/?probe=0e77de9dba) | Nov 20, 2022 |
| Acer          | Swift SF114-34              | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Alienware     | 17                          | [91358a0bec](https://linux-hardware.org/?probe=91358a0bec) | Nov 09, 2022 |
| Fujitsu       | LIFEBOOK A512               | [c479fc2cea](https://linux-hardware.org/?probe=c479fc2cea) | Nov 06, 2022 |
| HP            | Unknown                     | [aa28b92716](https://linux-hardware.org/?probe=aa28b92716) | Nov 06, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [36d7199821](https://linux-hardware.org/?probe=36d7199821) | Nov 01, 2022 |
| MSI           | GL72 6QD                    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| HUAWEI        | BOM-WXX9                    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Dell          | Latitude 7390               | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| Chuwi         | HeroBook Pro                | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| ASUSTek       | 1225C                       | [91f049c977](https://linux-hardware.org/?probe=91f049c977) | Sep 09, 2022 |
| Fujitsu       | LIFEBOOK S760               | [d805aa67b2](https://linux-hardware.org/?probe=d805aa67b2) | Sep 09, 2022 |
| Apple         | MacBookPro11,1              | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Valve         | Jupiter                     | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| ASUSTek       | E502NA                      | [d65dd8fc52](https://linux-hardware.org/?probe=d65dd8fc52) | Jun 09, 2022 |
| ASUSTek       | E502NA                      | [d3d64dcb5b](https://linux-hardware.org/?probe=d3d64dcb5b) | Jun 09, 2022 |
| HP            | Presario CQ57               | [9f87592293](https://linux-hardware.org/?probe=9f87592293) | Jun 02, 2022 |
| Dell          | Latitude 5520               | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| HP            | EliteBook 8470p             | [0773b6244e](https://linux-hardware.org/?probe=0773b6244e) | May 11, 2022 |
| Lenovo        | ThinkPad T490s 20NX000AM... | [f07b38c5f9](https://linux-hardware.org/?probe=f07b38c5f9) | May 10, 2022 |
| Apple         | MacBookPro8,1               | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| mPTech        | ARC 11.6 128GB HD           | [aafa7cb1cb](https://linux-hardware.org/?probe=aafa7cb1cb) | May 07, 2022 |
| Dell          | Precision 7540              | [8b1b7dd8da](https://linux-hardware.org/?probe=8b1b7dd8da) | Apr 30, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | [a10fb9fe10](https://linux-hardware.org/?probe=a10fb9fe10) | Apr 23, 2022 |
| HP            | EliteBook 840 G2            | [b963507390](https://linux-hardware.org/?probe=b963507390) | Apr 19, 2022 |
| HP            | EliteBook 840 G2            | [fff8ad361e](https://linux-hardware.org/?probe=fff8ad361e) | Apr 19, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | [d948d987b4](https://linux-hardware.org/?probe=d948d987b4) | Apr 18, 2022 |
| Framework     | Laptop                      | [d4a02dfec9](https://linux-hardware.org/?probe=d4a02dfec9) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Dell          | Latitude 5520               | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | [7fb04e6c7d](https://linux-hardware.org/?probe=7fb04e6c7d) | Mar 03, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | [0f27bdf5a8](https://linux-hardware.org/?probe=0f27bdf5a8) | Mar 02, 2022 |
| Lenovo        | ThinkPad X220 429136G       | [324d66c0fc](https://linux-hardware.org/?probe=324d66c0fc) | Feb 23, 2022 |
| HP            | EliteBook Folio 1040 G2     | [5f3cd9e8d5](https://linux-hardware.org/?probe=5f3cd9e8d5) | Feb 16, 2022 |
| Dell          | XPS 15 7590                 | [96f97ed2d6](https://linux-hardware.org/?probe=96f97ed2d6) | Jan 23, 2022 |
| HP            | EliteBook 8460p             | [ca26ae6ff8](https://linux-hardware.org/?probe=ca26ae6ff8) | Dec 22, 2021 |
| ASUSTek       | K52Jc                       | [f6789bc7ac](https://linux-hardware.org/?probe=f6789bc7ac) | Dec 18, 2021 |
| HP            | EliteBook 820 G1            | [dbbe56da66](https://linux-hardware.org/?probe=dbbe56da66) | Dec 01, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [dc981a1604](https://linux-hardware.org/?probe=dc981a1604) | Nov 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [362a840c47](https://linux-hardware.org/?probe=362a840c47) | Nov 20, 2021 |
| Alienware     | 17                          | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Dell          | Precision 5550              | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Getac         | B300G4                      | [78b2fab1e0](https://linux-hardware.org/?probe=78b2fab1e0) | Oct 17, 2021 |
| HP            | Pavilion dv7                | [6c14033e55](https://linux-hardware.org/?probe=6c14033e55) | Oct 16, 2021 |
| HP            | Pavilion dv7                | [f93789f29a](https://linux-hardware.org/?probe=f93789f29a) | Oct 16, 2021 |
| Acer          | Extensa 5620                | [5cae4fe0fa](https://linux-hardware.org/?probe=5cae4fe0fa) | Oct 11, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Alienware     | 17                          | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4f393c5347](https://linux-hardware.org/?probe=4f393c5347) | Sep 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| ASUSTek       | UX530UX                     | [c713dcf9e2](https://linux-hardware.org/?probe=c713dcf9e2) | Sep 08, 2021 |
| ASUSTek       | X510UA                      | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| ASUSTek       | X550ZA                      | [210ca88228](https://linux-hardware.org/?probe=210ca88228) | Aug 30, 2021 |
| Lenovo        | ThinkPad X201 3680CG7       | [9565bae9c3](https://linux-hardware.org/?probe=9565bae9c3) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [75619baa6e](https://linux-hardware.org/?probe=75619baa6e) | Aug 29, 2021 |
| ASUSTek       | X550ZA                      | [0a21d3b326](https://linux-hardware.org/?probe=0a21d3b326) | Aug 27, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Dell          | XPS 15 9500                 | [f21459caa1](https://linux-hardware.org/?probe=f21459caa1) | Aug 19, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [5f9d1cd1a6](https://linux-hardware.org/?probe=5f9d1cd1a6) | Aug 18, 2021 |
| HP            | EliteBook 8460p             | [0ce69e02fa](https://linux-hardware.org/?probe=0ce69e02fa) | Aug 17, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [fcd91a58e2](https://linux-hardware.org/?probe=fcd91a58e2) | Aug 13, 2021 |
| HP            | Pavilion dv7                | [a56935a751](https://linux-hardware.org/?probe=a56935a751) | Aug 09, 2021 |
| MSI           | GP62M 7RDX                  | [f02c96473f](https://linux-hardware.org/?probe=f02c96473f) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [7207e6aa0f](https://linux-hardware.org/?probe=7207e6aa0f) | Jul 08, 2021 |
| Dell          | XPS 15 9500                 | [a47fb764b4](https://linux-hardware.org/?probe=a47fb764b4) | Jul 01, 2021 |
| Lenovo        | IdeaPadFlex 10 20324        | [d96aea9f90](https://linux-hardware.org/?probe=d96aea9f90) | Jun 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [cb4242a344](https://linux-hardware.org/?probe=cb4242a344) | Jun 15, 2021 |
| HP            | EliteBook 8460p             | [7bf0e678ea](https://linux-hardware.org/?probe=7bf0e678ea) | Jun 13, 2021 |
| Lenovo        | ThinkPad T450s 20BWS1RG0... | [79d386a567](https://linux-hardware.org/?probe=79d386a567) | Jun 08, 2021 |
| Dell          | Latitude 5511               | [933fb253d4](https://linux-hardware.org/?probe=933fb253d4) | Jun 07, 2021 |
| Dell          | Latitude 5511               | [7b5e6276c0](https://linux-hardware.org/?probe=7b5e6276c0) | Jun 07, 2021 |
| HP            | EliteBook 8460p             | [6a7fe6469a](https://linux-hardware.org/?probe=6a7fe6469a) | Jun 06, 2021 |
| Timi          | RedmiBook 14 II             | [8700a7eaed](https://linux-hardware.org/?probe=8700a7eaed) | May 31, 2021 |
| Dell          | XPS 15 9500                 | [1ba665b0b3](https://linux-hardware.org/?probe=1ba665b0b3) | May 24, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [3ae2f83c9f](https://linux-hardware.org/?probe=3ae2f83c9f) | May 23, 2021 |
| Dell          | G5 5587                     | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| Dell          | Precision 5530              | [aa0aa77e62](https://linux-hardware.org/?probe=aa0aa77e62) | May 16, 2021 |
| HP            | EliteBook 8460p             | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| Dell          | Vostro V131                 | [43fe3f190f](https://linux-hardware.org/?probe=43fe3f190f) | May 14, 2021 |
| HP            | EliteBook 8460p             | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Lenovo        | Y50-70 20378                | [fe95dd9355](https://linux-hardware.org/?probe=fe95dd9355) | May 11, 2021 |
| Dell          | System Inspiron N7110       | [f5f418c337](https://linux-hardware.org/?probe=f5f418c337) | May 02, 2021 |
| Dell          | XPS 15 9500                 | [1bbe4079c5](https://linux-hardware.org/?probe=1bbe4079c5) | Apr 27, 2021 |
| HP            | Compaq nx6120 (PV170PA#U... | [5f105dda68](https://linux-hardware.org/?probe=5f105dda68) | Apr 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f84cf26650](https://linux-hardware.org/?probe=f84cf26650) | Apr 10, 2021 |
| Dell          | Inspiron N5110              | [a677fe0972](https://linux-hardware.org/?probe=a677fe0972) | Apr 08, 2021 |
| Dell          | Latitude E5430 non-vPro     | [ed6b3b5754](https://linux-hardware.org/?probe=ed6b3b5754) | Apr 04, 2021 |
| Dell          | Latitude E5430 non-vPro     | [218092e59f](https://linux-hardware.org/?probe=218092e59f) | Apr 03, 2021 |
| Lenovo        | Y50-70 20378                | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Dell          | XPS 15 7590                 | [6e6dc77b21](https://linux-hardware.org/?probe=6e6dc77b21) | Mar 29, 2021 |
| Samsung       | R410                        | [331d909654](https://linux-hardware.org/?probe=331d909654) | Mar 27, 2021 |
| Samsung       | R410                        | [5aa6fee818](https://linux-hardware.org/?probe=5aa6fee818) | Mar 25, 2021 |
| Samsung       | R410                        | [d3f94bcc8c](https://linux-hardware.org/?probe=d3f94bcc8c) | Mar 24, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [fb33c2e9b9](https://linux-hardware.org/?probe=fb33c2e9b9) | Mar 17, 2021 |
| Notebook      | W35xSS_370SS                | [0e98472f08](https://linux-hardware.org/?probe=0e98472f08) | Mar 02, 2021 |
| Lenovo        | ThinkPad T61 766112G        | [04ec7d5efd](https://linux-hardware.org/?probe=04ec7d5efd) | Feb 25, 2021 |
| Acer          | Aspire V5-572P              | [61834c786c](https://linux-hardware.org/?probe=61834c786c) | Feb 24, 2021 |
| HP            | EliteBook 850 G2            | [4c935ce981](https://linux-hardware.org/?probe=4c935ce981) | Feb 18, 2021 |
| HP            | EliteBook 850 G2            | [69090d5f4c](https://linux-hardware.org/?probe=69090d5f4c) | Feb 17, 2021 |
| Dell          | XPS 15 9500                 | [8652b51903](https://linux-hardware.org/?probe=8652b51903) | Jan 20, 2021 |
| Dell          | XPS 15 9500                 | [77be7c1164](https://linux-hardware.org/?probe=77be7c1164) | Jan 18, 2021 |
| HP            | EliteBook 840 G5            | [59aaeda6a9](https://linux-hardware.org/?probe=59aaeda6a9) | Dec 28, 2020 |
| Fujitsu       | LIFEBOOK E744               | [81daeffb49](https://linux-hardware.org/?probe=81daeffb49) | Dec 28, 2020 |
| Timi          | RedmiBook 16                | [34bc3ceb48](https://linux-hardware.org/?probe=34bc3ceb48) | Dec 24, 2020 |
| MSI           | GT70 2OC/2OD                | [e52bbc40aa](https://linux-hardware.org/?probe=e52bbc40aa) | Dec 19, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | [95355fcff6](https://linux-hardware.org/?probe=95355fcff6) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | [3ee030e6ac](https://linux-hardware.org/?probe=3ee030e6ac) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 765912G        | [9651814a46](https://linux-hardware.org/?probe=9651814a46) | Dec 08, 2020 |
| Lenovo        | Y50-70 20378                | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [4defcea6f8](https://linux-hardware.org/?probe=4defcea6f8) | Nov 24, 2020 |
| Notebook      | W35xSS_370SS                | [ed0e6634d4](https://linux-hardware.org/?probe=ed0e6634d4) | Sep 29, 2020 |
| HP            | EliteBook 745 G5            | [e9d2889a6d](https://linux-hardware.org/?probe=e9d2889a6d) | Sep 28, 2020 |
| Dell          | Latitude 7490               | [cfd6c8dcc4](https://linux-hardware.org/?probe=cfd6c8dcc4) | Sep 28, 2020 |
| TUXEDO        | Book BA1510                 | [d89436074e](https://linux-hardware.org/?probe=d89436074e) | Sep 23, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [3399940dd9](https://linux-hardware.org/?probe=3399940dd9) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [5bd6ca5aba](https://linux-hardware.org/?probe=5bd6ca5aba) | Sep 15, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [83263681eb](https://linux-hardware.org/?probe=83263681eb) | Sep 15, 2020 |
| Notebook      | W35xSS_370SS                | [5b35813fca](https://linux-hardware.org/?probe=5b35813fca) | Sep 10, 2020 |
| HP            | ZBook 17                    | [605dfd3279](https://linux-hardware.org/?probe=605dfd3279) | Sep 08, 2020 |
| HP            | ZBook 17                    | [09e5bd8eb6](https://linux-hardware.org/?probe=09e5bd8eb6) | Sep 08, 2020 |
| ASUSTek       | X542UQR                     | [7782f01f3c](https://linux-hardware.org/?probe=7782f01f3c) | Sep 04, 2020 |
| ASUSTek       | E502MA                      | [1eb9e7db73](https://linux-hardware.org/?probe=1eb9e7db73) | Sep 01, 2020 |
| ASUSTek       | X501U                       | [006dc7a8d6](https://linux-hardware.org/?probe=006dc7a8d6) | Aug 15, 2020 |
| Lenovo        | ThinkPad X220 4291R30       | [bdf2c40591](https://linux-hardware.org/?probe=bdf2c40591) | Aug 06, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Acer          | Extensa 5620                | [dba48971a3](https://linux-hardware.org/?probe=dba48971a3) | Jul 24, 2020 |
| Lenovo        | ThinkPad T480s 20L7001VU... | [03bcc8865c](https://linux-hardware.org/?probe=03bcc8865c) | Jul 23, 2020 |
| HP            | Presario CQ56               | [f668bc59f5](https://linux-hardware.org/?probe=f668bc59f5) | Jun 23, 2020 |
| HP            | Presario CQ56               | [b8db4c3694](https://linux-hardware.org/?probe=b8db4c3694) | Jun 23, 2020 |
| Dell          | XPS 15 9560                 | [867ca870fd](https://linux-hardware.org/?probe=867ca870fd) | Jun 14, 2020 |
| Samsung       | 535U3C                      | [e7bc13b354](https://linux-hardware.org/?probe=e7bc13b354) | May 30, 2020 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | [26c8949a0a](https://linux-hardware.org/?probe=26c8949a0a) | May 29, 2020 |
| Lenovo        | ThinkPad T540p 20BFS4510... | [6c5bf8bfbe](https://linux-hardware.org/?probe=6c5bf8bfbe) | May 05, 2020 |
| HP            | EliteBook 840 G2            | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [a1a1ce6e00](https://linux-hardware.org/?probe=a1a1ce6e00) | May 02, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [e3321de949](https://linux-hardware.org/?probe=e3321de949) | May 02, 2020 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [35b95432ac](https://linux-hardware.org/?probe=35b95432ac) | Apr 30, 2020 |
| Dell          | XPS 15 9560                 | [eea0fa4941](https://linux-hardware.org/?probe=eea0fa4941) | Apr 25, 2020 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [91770bcd78](https://linux-hardware.org/?probe=91770bcd78) | Apr 22, 2020 |
| MSI           | GS75 Stealth 8SE            | [1c50333136](https://linux-hardware.org/?probe=1c50333136) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | [cdca82a043](https://linux-hardware.org/?probe=cdca82a043) | Apr 05, 2020 |
| Samsung       | 275E4E/275E5E               | [6b624f1079](https://linux-hardware.org/?probe=6b624f1079) | Mar 12, 2020 |
| Lenovo        | ThinkPad A285 20MXS0BG00    | [4dabcb8d3f](https://linux-hardware.org/?probe=4dabcb8d3f) | Mar 11, 2020 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [c71def9148](https://linux-hardware.org/?probe=c71def9148) | Feb 18, 2020 |
| HP            | EliteBook 8470p             | [ed5efcdf48](https://linux-hardware.org/?probe=ed5efcdf48) | Feb 03, 2020 |
| Dell          | Precision 5510              | [68c56e0ab4](https://linux-hardware.org/?probe=68c56e0ab4) | Dec 02, 2019 |
| HP            | Pavilion Gaming Notebook    | [c4917de06e](https://linux-hardware.org/?probe=c4917de06e) | Oct 17, 2019 |
| HP            | Pavilion Gaming Notebook    | [9f867b307a](https://linux-hardware.org/?probe=9f867b307a) | Oct 12, 2019 |
| HP            | Pavilion Gaming Notebook    | [f3f1a208c1](https://linux-hardware.org/?probe=f3f1a208c1) | Sep 26, 2019 |
| HP            | Pavilion Gaming Notebook    | [0639ef182a](https://linux-hardware.org/?probe=0639ef182a) | Sep 20, 2019 |
| HP            | Pavilion Gaming Notebook    | [3b99dff2c2](https://linux-hardware.org/?probe=3b99dff2c2) | Sep 19, 2019 |
| Dell          | Inspiron 5748               | [75647e5457](https://linux-hardware.org/?probe=75647e5457) | Sep 03, 2019 |
| Acer          | Aspire V3-771               | [335c3fea78](https://linux-hardware.org/?probe=335c3fea78) | Aug 10, 2019 |
| Quanta        | TWH                         | [b6c3554305](https://linux-hardware.org/?probe=b6c3554305) | Aug 05, 2019 |
| Quanta        | TWH                         | [243be58298](https://linux-hardware.org/?probe=243be58298) | Aug 05, 2019 |
| HP            | OMEN by Laptop              | [4a247c1234](https://linux-hardware.org/?probe=4a247c1234) | Aug 03, 2019 |
| Lenovo        | V110-15ISK 80TL             | [15bfdc0f25](https://linux-hardware.org/?probe=15bfdc0f25) | Aug 03, 2019 |
| HP            | OMEN by Laptop              | [cd37f24ff8](https://linux-hardware.org/?probe=cd37f24ff8) | Aug 01, 2019 |
| Dell          | Inspiron 5558               | [f26b9a5e36](https://linux-hardware.org/?probe=f26b9a5e36) | Jun 29, 2019 |
| ASUSTek       | N56VZ                       | [02928f6b1e](https://linux-hardware.org/?probe=02928f6b1e) | Jun 25, 2019 |
| Lenovo        | IdeaPad U330p 20267         | [1edb7b5f96](https://linux-hardware.org/?probe=1edb7b5f96) | May 25, 2019 |
| HP            | Pavilion dv4000 (EK980EA... | [837230178b](https://linux-hardware.org/?probe=837230178b) | May 23, 2019 |
| Lenovo        | G50-70 20351                | [84c3544bb2](https://linux-hardware.org/?probe=84c3544bb2) | May 20, 2019 |
| Samsung       | 275E4E/275E5E               | [60cb87eeb6](https://linux-hardware.org/?probe=60cb87eeb6) | May 11, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | [cfcb3e3b82](https://linux-hardware.org/?probe=cfcb3e3b82) | May 02, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | [c577dfbf17](https://linux-hardware.org/?probe=c577dfbf17) | May 02, 2019 |
| Samsung       | 770Z5E/780Z5E               | [e07529a7fc](https://linux-hardware.org/?probe=e07529a7fc) | Apr 14, 2019 |
| Fujitsu Si... | AMILO La1703                | [4530891733](https://linux-hardware.org/?probe=4530891733) | Apr 01, 2019 |
| Dell          | Inspiron 3543               | [e411551975](https://linux-hardware.org/?probe=e411551975) | Mar 21, 2019 |
| Dell          | Inspiron 3543               | [f85fec55bb](https://linux-hardware.org/?probe=f85fec55bb) | Mar 19, 2019 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [bee48cd1c5](https://linux-hardware.org/?probe=bee48cd1c5) | Mar 09, 2019 |
| Lenovo        | ThinkPad T580 20L90026MX    | [14afd9ea12](https://linux-hardware.org/?probe=14afd9ea12) | Feb 27, 2019 |
| HP            | ProBook 470 G1              | [268414d1b5](https://linux-hardware.org/?probe=268414d1b5) | Feb 07, 2019 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [5357d8ad3a](https://linux-hardware.org/?probe=5357d8ad3a) | Dec 04, 2018 |
| Lenovo        | Y520-15IKBN 80WK            | [a075fc73d3](https://linux-hardware.org/?probe=a075fc73d3) | Oct 09, 2018 |
| ASUSTek       | X55A                        | [403b1aa1d7](https://linux-hardware.org/?probe=403b1aa1d7) | May 08, 2018 |
| ASUSTek       | K40IJ                       | [24366329c2](https://linux-hardware.org/?probe=24366329c2) | May 07, 2018 |
| Dell          | Inspiron N5110              | [d7b2f7f719](https://linux-hardware.org/?probe=d7b2f7f719) | Oct 05, 2017 |
| Acer          | Aspire 6530G                | [2f88dba791](https://linux-hardware.org/?probe=2f88dba791) | Aug 13, 2017 |
| HP            | Compaq nx7400 (RH387EA#A... | [116c8bc9de](https://linux-hardware.org/?probe=116c8bc9de) | Jun 03, 2017 |
| Toshiba       | Satellite L855              | [de2e163003](https://linux-hardware.org/?probe=de2e163003) | May 17, 2017 |
| HP            | Pavilion dv5                | [3191678465](https://linux-hardware.org/?probe=3191678465) | May 04, 2017 |
| HP            | Pavilion dv5                | [1f21f421ed](https://linux-hardware.org/?probe=1f21f421ed) | May 02, 2017 |
| Quanta        | TWH                         | [4807bd6702](https://linux-hardware.org/?probe=4807bd6702) | Apr 28, 2017 |
| Quanta        | TWH                         | [0105619fb7](https://linux-hardware.org/?probe=0105619fb7) | Apr 27, 2017 |
| Acer          | Aspire 5541                 | [efa45ad21c](https://linux-hardware.org/?probe=efa45ad21c) | Nov 14, 2016 |
| Acer          | Aspire 5541                 | [b61eb7bcb0](https://linux-hardware.org/?probe=b61eb7bcb0) | Nov 13, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 22.04        | 24        | 9.34%   |
| Ubuntu 20.04        | 20        | 7.78%   |
| Ubuntu 18.04        | 14        | 5.45%   |
| Arch Rolling        | 10        | 3.89%   |
| ArcoLinux Rolling   | 9         | 3.5%    |
| Arch                | 7         | 2.72%   |
| Ubuntu 19.04        | 6         | 2.33%   |
| Ubuntu MATE 22.04   | 5         | 1.95%   |
| Linux Mint 20.1     | 5         | 1.95%   |
| Ubuntu 24.04        | 4         | 1.56%   |
| Pop!_OS 22.04       | 4         | 1.56%   |
| Kubuntu 22.04       | 4         | 1.56%   |
| Fedora 34           | 4         | 1.56%   |
| Debian 11           | 4         | 1.56%   |
| ROSA R9             | 3         | 1.17%   |
| ROSA R8.1           | 3         | 1.17%   |
| ROSA R11            | 3         | 1.17%   |
| Pop!_OS 20.04       | 3         | 1.17%   |
| OpenMandriva 4.3    | 3         | 1.17%   |
| OpenMandriva 4.2    | 3         | 1.17%   |
| Manjaro             | 3         | 1.17%   |
| Linux Mint 21.2     | 3         | 1.17%   |
| Kubuntu 20.04       | 3         | 1.17%   |
| Fedora 41           | 3         | 1.17%   |
| Fedora 36           | 3         | 1.17%   |
| EndeavourOS Rolling | 3         | 1.17%   |
| Debian 12           | 3         | 1.17%   |
| Zorin 17            | 2         | 0.78%   |
| Zorin 16            | 2         | 0.78%   |
| Xubuntu 20.04       | 2         | 0.78%   |
| Ubuntu 20.10        | 2         | 0.78%   |
| Ubuntu 19.10        | 2         | 0.78%   |
| ROSA 12.2           | 2         | 0.78%   |
| Reborn OS           | 2         | 0.78%   |
| Methaneos Stable    | 2         | 0.78%   |
| Manjaro 20.1        | 2         | 0.78%   |
| Linux Mint 22       | 2         | 0.78%   |
| Linux Mint 21.3     | 2         | 0.78%   |
| Linux Mint 20.3     | 2         | 0.78%   |
| Linux Mint 20.2     | 2         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 72        | 28.8%   |
| Linux Mint   | 21        | 8.4%    |
| Arch         | 17        | 6.8%    |
| Fedora       | 16        | 6.4%    |
| ROSA         | 15        | 6%      |
| Pop!_OS      | 9         | 3.6%    |
| Manjaro      | 9         | 3.6%    |
| Debian       | 9         | 3.6%    |
| ArcoLinux    | 9         | 3.6%    |
| OpenMandriva | 7         | 2.8%    |
| Kubuntu      | 7         | 2.8%    |
| Xubuntu      | 6         | 2.4%    |
| Ubuntu MATE  | 6         | 2.4%    |
| Zorin        | 5         | 2%      |
| KDE neon     | 4         | 1.6%    |
| Endless      | 4         | 1.6%    |
| Elementary   | 4         | 1.6%    |
| SteamOS      | 3         | 1.2%    |
| Lubuntu      | 3         | 1.2%    |
| Kali         | 3         | 1.2%    |
| EndeavourOS  | 3         | 1.2%    |
| Reborn OS    | 2         | 0.8%    |
| Nobara       | 2         | 0.8%    |
| Methaneos    | 2         | 0.8%    |
| Clear Linux  | 2         | 0.8%    |
| Xero         | 1         | 0.4%    |
| Ubuntu Unity | 1         | 0.4%    |
| TUXEDO OS    | 1         | 0.4%    |
| Parrot       | 1         | 0.4%    |
| NixOS        | 1         | 0.4%    |
| MX           | 1         | 0.4%    |
| LMDE         | 1         | 0.4%    |
| Devuan       | 1         | 0.4%    |
| ChimeraOS    | 1         | 0.4%    |
| ALT Linux    | 1         | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 6         | 2.18%   |
| 6.2.0-26-generic                   | 4         | 1.45%   |
| 5.15.0-52-generic                  | 4         | 1.45%   |
| 6.8.0-49-generic                   | 3         | 1.09%   |
| 5.4.0-47-generic                   | 3         | 1.09%   |
| 5.4.0-28-generic                   | 3         | 1.09%   |
| 5.16.7-desktop-1omv4003            | 3         | 1.09%   |
| 5.15.0-53-generic                  | 3         | 1.09%   |
| 5.10.14-desktop-1omv4002           | 3         | 1.09%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 1.09%   |
| 6.9.6-methane-jn27                 | 2         | 0.73%   |
| 6.9.3-76060903-generic             | 2         | 0.73%   |
| 6.8.0-45-generic                   | 2         | 0.73%   |
| 6.8.0-31-generic                   | 2         | 0.73%   |
| 6.5.0-9-generic                    | 2         | 0.73%   |
| 6.5.0-45-generic                   | 2         | 0.73%   |
| 6.2.0-39-generic                   | 2         | 0.73%   |
| 6.1.0-kali7-amd64                  | 2         | 0.73%   |
| 6.1.0-18-amd64                     | 2         | 0.73%   |
| 5.8.0-53-generic                   | 2         | 0.73%   |
| 5.4.0-88-generic                   | 2         | 0.73%   |
| 5.4.0-65-generic                   | 2         | 0.73%   |
| 5.15.2-arch1-1                     | 2         | 0.73%   |
| 5.15.0-56-generic                  | 2         | 0.73%   |
| 5.13.10-arch1-1                    | 2         | 0.73%   |
| 5.13.0-39-generic                  | 2         | 0.73%   |
| 5.11.0-27-generic                  | 2         | 0.73%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 0.73%   |
| 5.10.0-28-amd64                    | 2         | 0.73%   |
| 5.0.0-23-generic                   | 2         | 0.73%   |
| 4.18.0-15-generic                  | 2         | 0.73%   |
| 4.15.0-45-generic                  | 2         | 0.73%   |
| 6.9.3-arch1-1                      | 1         | 0.36%   |
| 6.9.0-rc2                          | 1         | 0.36%   |
| 6.8.8-arch1-1                      | 1         | 0.36%   |
| 6.8.7-200.fc39.x86_64              | 1         | 0.36%   |
| 6.8.0-41-generic                   | 1         | 0.36%   |
| 6.8.0-36-generic                   | 1         | 0.36%   |
| 6.8.0-35-generic                   | 1         | 0.36%   |
| 6.7.9-zen1-1-zen                   | 1         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 32        | 11.94%  |
| 5.15.0  | 23        | 8.58%   |
| 6.5.0   | 13        | 4.85%   |
| 4.15.0  | 13        | 4.85%   |
| 6.8.0   | 10        | 3.73%   |
| 6.2.0   | 9         | 3.36%   |
| 5.8.0   | 9         | 3.36%   |
| 5.11.0  | 8         | 2.99%   |
| 5.13.0  | 7         | 2.61%   |
| 5.0.0   | 7         | 2.61%   |
| 6.1.0   | 5         | 1.87%   |
| 4.18.0  | 5         | 1.87%   |
| 5.10.0  | 4         | 1.49%   |
| 4.9.20  | 4         | 1.49%   |
| 6.9.3   | 3         | 1.12%   |
| 5.3.0   | 3         | 1.12%   |
| 5.19.0  | 3         | 1.12%   |
| 5.16.7  | 3         | 1.12%   |
| 5.10.14 | 3         | 1.12%   |
| 6.9.6   | 2         | 0.75%   |
| 6.6.10  | 2         | 0.75%   |
| 6.0.9   | 2         | 0.75%   |
| 5.17.1  | 2         | 0.75%   |
| 5.15.2  | 2         | 0.75%   |
| 5.13.13 | 2         | 0.75%   |
| 5.13.12 | 2         | 0.75%   |
| 5.13.10 | 2         | 0.75%   |
| 5.11.12 | 2         | 0.75%   |
| 5.10.74 | 2         | 0.75%   |
| 6.9.0   | 1         | 0.37%   |
| 6.8.8   | 1         | 0.37%   |
| 6.8.7   | 1         | 0.37%   |
| 6.7.9   | 1         | 0.37%   |
| 6.7.6   | 1         | 0.37%   |
| 6.6.7   | 1         | 0.37%   |
| 6.6.65  | 1         | 0.37%   |
| 6.6.30  | 1         | 0.37%   |
| 6.6.18  | 1         | 0.37%   |
| 6.6.16  | 1         | 0.37%   |
| 6.6.13  | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 33        | 12.36%  |
| 5.15    | 28        | 10.49%  |
| 5.13    | 16        | 5.99%   |
| 6.5     | 15        | 5.62%   |
| 5.10    | 14        | 5.24%   |
| 4.15    | 13        | 4.87%   |
| 6.8     | 12        | 4.49%   |
| 6.1     | 12        | 4.49%   |
| 6.2     | 11        | 4.12%   |
| 5.11    | 11        | 4.12%   |
| 5.8     | 10        | 3.75%   |
| 6.6     | 9         | 3.37%   |
| 6.11    | 8         | 3%      |
| 5.0     | 8         | 3%      |
| 4.9     | 7         | 2.62%   |
| 6.9     | 6         | 2.25%   |
| 5.16    | 6         | 2.25%   |
| 6.0     | 5         | 1.87%   |
| 4.18    | 5         | 1.87%   |
| 5.9     | 4         | 1.5%    |
| 5.19    | 4         | 1.5%    |
| 5.17    | 4         | 1.5%    |
| 5.3     | 3         | 1.12%   |
| 5.14    | 3         | 1.12%   |
| 5.12    | 3         | 1.12%   |
| 6.7     | 2         | 0.75%   |
| 6.3     | 2         | 0.75%   |
| 6.12    | 2         | 0.75%   |
| 6.10    | 2         | 0.75%   |
| 4.19    | 2         | 0.75%   |
| 6.4     | 1         | 0.37%   |
| 5.6     | 1         | 0.37%   |
| 5.5     | 1         | 0.37%   |
| 4.4     | 1         | 0.37%   |
| 4.10    | 1         | 0.37%   |
| 4.1     | 1         | 0.37%   |
| 3.16    | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 240       | 97.96%  |
| i686   | 5         | 2.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 92        | 36.51%  |
| KDE5       | 38        | 15.08%  |
| Unknown    | 27        | 10.71%  |
| XFCE       | 21        | 8.33%   |
| X-Cinnamon | 16        | 6.35%   |
| MATE       | 12        | 4.76%   |
| KDE6       | 9         | 3.57%   |
| KDE4       | 8         | 3.17%   |
| KDE        | 6         | 2.38%   |
| Pantheon   | 4         | 1.59%   |
| LXQt       | 4         | 1.59%   |
| i3         | 3         | 1.19%   |
| Unity      | 2         | 0.79%   |
| LXDE       | 2         | 0.79%   |
| Budgie     | 2         | 0.79%   |
| awesome    | 2         | 0.79%   |
| Yoyo       | 1         | 0.4%    |
| openbox    | 1         | 0.4%    |
| Hyprland   | 1         | 0.4%    |
| Cinnamon   | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 178       | 71.49%  |
| Wayland | 60        | 24.1%   |
| Unknown | 10        | 4.02%   |
| Tty     | 1         | 0.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 102       | 40.64%  |
| SDDM    | 49        | 19.52%  |
| GDM3    | 33        | 13.15%  |
| LightDM | 26        | 10.36%  |
| GDM     | 24        | 9.56%   |
| TDM     | 9         | 3.59%   |
| KDM     | 8         | 3.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 127       | 51.21%  |
| et_EE           | 38        | 15.32%  |
| Unknown         | 33        | 13.31%  |
| ru_RU           | 20        | 8.06%   |
| en_GB           | 12        | 4.84%   |
| C               | 7         | 2.82%   |
| de_DE           | 3         | 1.21%   |
| uk_UA           | 1         | 0.4%    |
| ru_UA           | 1         | 0.4%    |
| fr_FR           | 1         | 0.4%    |
| es_MX           | 1         | 0.4%    |
| en_US.utf-8     | 1         | 0.4%    |
| en_US.iso885915 | 1         | 0.4%    |
| en_DK           | 1         | 0.4%    |
| en_AU           | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 126       | 50.2%   |
| BIOS | 125       | 49.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 167       | 67.34%  |
| Btrfs   | 32        | 12.9%   |
| Tmpfs   | 16        | 6.45%   |
| Unknown | 12        | 4.84%   |
| Overlay | 11        | 4.44%   |
| Zfs     | 5         | 2.02%   |
| Xfs     | 3         | 1.21%   |
| Ext3    | 2         | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 117       | 46.99%  |
| Unknown | 107       | 42.97%  |
| MBR     | 25        | 10.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 222       | 89.88%  |
| Yes       | 25        | 10.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 179       | 71.89%  |
| Yes       | 70        | 28.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 78        | 31.84%  |
| Hewlett-Packard     | 43        | 17.55%  |
| Dell                | 37        | 15.1%   |
| ASUSTek Computer    | 26        | 10.61%  |
| Acer                | 10        | 4.08%   |
| Samsung Electronics | 8         | 3.27%   |
| Apple               | 7         | 2.86%   |
| MSI                 | 6         | 2.45%   |
| Valve               | 4         | 1.63%   |
| Notebook            | 3         | 1.22%   |
| Fujitsu             | 3         | 1.22%   |
| TUXEDO              | 2         | 0.82%   |
| Toshiba             | 2         | 0.82%   |
| Timi                | 2         | 0.82%   |
| Quanta              | 2         | 0.82%   |
| Alienware           | 2         | 0.82%   |
| Packard Bell        | 1         | 0.41%   |
| mPTech              | 1         | 0.41%   |
| Intel               | 1         | 0.41%   |
| HUAWEI              | 1         | 0.41%   |
| GPD                 | 1         | 0.41%   |
| Gigabyte Technology | 1         | 0.41%   |
| Getac               | 1         | 0.41%   |
| Fujitsu Siemens     | 1         | 0.41%   |
| Framework           | 1         | 0.41%   |
| Chuwi               | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 4         | 1.63%   |
| HP EliteBook 8470p                                    | 3         | 1.22%   |
| Quanta TWH                                            | 2         | 0.82%   |
| Lenovo Y50-70 20378                                   | 2         | 0.82%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 0.82%   |
| HP Pavilion dv7                                       | 2         | 0.82%   |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 0.82%   |
| HP EliteBook 8460p                                    | 2         | 0.82%   |
| HP EliteBook 840 G5                                   | 2         | 0.82%   |
| HP EliteBook 840 G2                                   | 2         | 0.82%   |
| Dell Latitude 7490                                    | 2         | 0.82%   |
| Dell Inspiron N5110                                   | 2         | 0.82%   |
| Dell Inspiron 5558                                    | 2         | 0.82%   |
| ASUS ZenBook UX325EA_UX325EA                          | 2         | 0.82%   |
| Apple MacBookPro9,2                                   | 2         | 0.82%   |
| Alienware 17                                          | 2         | 0.82%   |
| TUXEDO Polaris AMD Gen5                               | 1         | 0.41%   |
| TUXEDO Book BA1510                                    | 1         | 0.41%   |
| Toshiba Satellite L870-120                            | 1         | 0.41%   |
| Toshiba Satellite L855                                | 1         | 0.41%   |
| Timi RedmiBook 16                                     | 1         | 0.41%   |
| Timi RedmiBook 14 II                                  | 1         | 0.41%   |
| Samsung R410                                          | 1         | 0.41%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.41%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.41%   |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.41%   |
| Samsung 535U3C                                        | 1         | 0.41%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.41%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.41%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.41%   |
| Packard Bell EasyNote TK87                            | 1         | 0.41%   |
| Notebook W35xSS_370SS                                 | 1         | 0.41%   |
| Notebook PE60RNE_RND_RNC                              | 1         | 0.41%   |
| Notebook N150SD/N155SD                                | 1         | 0.41%   |
| MSI Pulse GL66 11UDK                                  | 1         | 0.41%   |
| MSI GT70 2OC/2OD                                      | 1         | 0.41%   |
| MSI GS75 Stealth 8SE                                  | 1         | 0.41%   |
| MSI GP62M 7RDX                                        | 1         | 0.41%   |
| MSI GL72 6QD                                          | 1         | 0.41%   |
| MSI GF63 Thin 10SCXR                                  | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 56        | 22.86%  |
| HP EliteBook      | 16        | 6.53%   |
| Dell Latitude     | 13        | 5.31%   |
| Dell Inspiron     | 8         | 3.27%   |
| Lenovo IdeaPad    | 7         | 2.86%   |
| HP Pavilion       | 7         | 2.86%   |
| Dell XPS          | 6         | 2.45%   |
| Acer Aspire       | 6         | 2.45%   |
| Dell Precision    | 5         | 2.04%   |
| Valve Jupiter     | 4         | 1.63%   |
| Lenovo Legion     | 4         | 1.63%   |
| HP ProBook        | 4         | 1.63%   |
| ASUS Zenbook      | 4         | 1.63%   |
| ASUS VivoBook     | 4         | 1.63%   |
| HP Laptop         | 3         | 1.22%   |
| HP Compaq         | 3         | 1.22%   |
| Fujitsu LIFEBOOK  | 3         | 1.22%   |
| ASUS ASUS         | 3         | 1.22%   |
| Toshiba Satellite | 2         | 0.82%   |
| Timi RedmiBook    | 2         | 0.82%   |
| Samsung 900X3C    | 2         | 0.82%   |
| Quanta TWH        | 2         | 0.82%   |
| Lenovo Yoga       | 2         | 0.82%   |
| Lenovo Y50-70     | 2         | 0.82%   |
| HP Presario       | 2         | 0.82%   |
| HP OMEN           | 2         | 0.82%   |
| HP ENVY           | 2         | 0.82%   |
| Dell Vostro       | 2         | 0.82%   |
| Dell System       | 2         | 0.82%   |
| Apple MacBookPro9 | 2         | 0.82%   |
| Apple MacBookPro5 | 2         | 0.82%   |
| Alienware 17      | 2         | 0.82%   |
| TUXEDO Polaris    | 1         | 0.41%   |
| TUXEDO Book       | 1         | 0.41%   |
| Samsung R410      | 1         | 0.41%   |
| Samsung 770Z5E    | 1         | 0.41%   |
| Samsung 535U3C    | 1         | 0.41%   |
| Samsung 350V5C    | 1         | 0.41%   |
| Samsung 300E5EV   | 1         | 0.41%   |
| Samsung 275E4E    | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 26        | 10.61%  |
| 2013 | 25        | 10.2%   |
| 2011 | 23        | 9.39%   |
| 2018 | 22        | 8.98%   |
| 2019 | 20        | 8.16%   |
| 2014 | 16        | 6.53%   |
| 2021 | 15        | 6.12%   |
| 2012 | 14        | 5.71%   |
| 2015 | 13        | 5.31%   |
| 2022 | 11        | 4.49%   |
| 2017 | 11        | 4.49%   |
| 2023 | 9         | 3.67%   |
| 2010 | 9         | 3.67%   |
| 2016 | 8         | 3.27%   |
| 2007 | 8         | 3.27%   |
| 2008 | 7         | 2.86%   |
| 2024 | 3         | 1.22%   |
| 2009 | 3         | 1.22%   |
| 2006 | 2         | 0.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 245       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 227       | 91.53%  |
| Enabled  | 21        | 8.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 245       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 57        | 22.98%  |
| 8.01-16.0   | 55        | 22.18%  |
| 16.01-24.0  | 50        | 20.16%  |
| 3.01-4.0    | 37        | 14.92%  |
| 32.01-64.0  | 18        | 7.26%   |
| 24.01-32.0  | 11        | 4.44%   |
| 2.01-3.0    | 10        | 4.03%   |
| 1.01-2.0    | 6         | 2.42%   |
| 64.01-256.0 | 4         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 74        | 28.35%  |
| 2.01-3.0   | 63        | 24.14%  |
| 4.01-8.0   | 58        | 22.22%  |
| 3.01-4.0   | 36        | 13.79%  |
| 8.01-16.0  | 15        | 5.75%   |
| 0.51-1.0   | 11        | 4.21%   |
| 16.01-24.0 | 3         | 1.15%   |
| 24.01-32.0 | 1         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 189       | 75.9%   |
| 2      | 49        | 19.68%  |
| 3      | 8         | 3.21%   |
| 5      | 1         | 0.4%    |
| 4      | 1         | 0.4%    |
| 0      | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 169       | 67.87%  |
| Yes       | 80        | 32.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 82.93%  |
| No        | 42        | 17.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 242       | 98.78%  |
| No        | 3         | 1.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 201       | 81.38%  |
| No        | 46        | 18.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Estonia | 245       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Tallinn           | 160       | 63.49%  |
| Tartu             | 28        | 11.11%  |
| Pärnu            | 9         | 3.57%   |
| Narva             | 6         | 2.38%   |
| Rapla             | 5         | 1.98%   |
| Rakvere           | 5         | 1.98%   |
| Tabasalu          | 4         | 1.59%   |
| Vinni             | 2         | 0.79%   |
| Viljandi          | 2         | 0.79%   |
| Valga             | 2         | 0.79%   |
| Saku              | 2         | 0.79%   |
| Otepaeae          | 2         | 0.79%   |
| Maardu            | 2         | 0.79%   |
| Laagri            | 2         | 0.79%   |
| Keila             | 2         | 0.79%   |
| Võru             | 1         | 0.4%    |
| Viimsi            | 1         | 0.4%    |
| Vatla             | 1         | 0.4%    |
| Sillamäe         | 1         | 0.4%    |
| Sauga             | 1         | 0.4%    |
| Reiu              | 1         | 0.4%    |
| Rae Parish        | 1         | 0.4%    |
| Põlva            | 1         | 0.4%    |
| Pohja-Sakala vald | 1         | 0.4%    |
| Palamuse          | 1         | 0.4%    |
| Muraste           | 1         | 0.4%    |
| Kupu              | 1         | 0.4%    |
| Kose              | 1         | 0.4%    |
| Kärdla           | 1         | 0.4%    |
| Kaeina            | 1         | 0.4%    |
| Jüri             | 1         | 0.4%    |
| Jõhvi            | 1         | 0.4%    |
| Jõgeva           | 1         | 0.4%    |
| AEaesmaee         | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 69        | 81     | 22.62%  |
| Seagate                     | 34        | 37     | 11.15%  |
| Kingston                    | 22        | 24     | 7.21%   |
| Toshiba                     | 21        | 21     | 6.89%   |
| SK hynix                    | 19        | 23     | 6.23%   |
| Sandisk                     | 18        | 21     | 5.9%    |
| WDC                         | 17        | 20     | 5.57%   |
| Intel                       | 11        | 12     | 3.61%   |
| Unknown                     | 10        | 11     | 3.28%   |
| Micron Technology           | 7         | 7      | 2.3%    |
| HGST                        | 7         | 8      | 2.3%    |
| Patriot                     | 6         | 7      | 1.97%   |
| KIOXIA                      | 5         | 6      | 1.64%   |
| Hitachi                     | 5         | 5      | 1.64%   |
| Crucial                     | 5         | 5      | 1.64%   |
| Lenovo                      | 3         | 3      | 0.98%   |
| Kingston Technology Company | 3         | 4      | 0.98%   |
| China                       | 3         | 3      | 0.98%   |
| Apacer                      | 3         | 3      | 0.98%   |
| A-DATA Technology           | 3         | 3      | 0.98%   |
| Unknown                     | 3         | 3      | 0.98%   |
| Transcend                   | 2         | 5      | 0.66%   |
| SPCC                        | 2         | 4      | 0.66%   |
| Phison Electronics          | 2         | 2      | 0.66%   |
| LITEONIT                    | 2         | 2      | 0.66%   |
| KingSpec                    | 2         | 3      | 0.66%   |
| Gigabyte Technology         | 2         | 3      | 0.66%   |
| Fujitsu                     | 2         | 2      | 0.66%   |
| Apple                       | 2         | 2      | 0.66%   |
| ADATA Technology            | 2         | 2      | 0.66%   |
| XPG                         | 1         | 1      | 0.33%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.33%   |
| UMIS                        | 1         | 1      | 0.33%   |
| Team                        | 1         | 1      | 0.33%   |
| PNY                         | 1         | 1      | 0.33%   |
| Phison                      | 1         | 1      | 0.33%   |
| Netac                       | 1         | 1      | 0.33%   |
| Micron/Crucial Technology   | 1         | 2      | 0.33%   |
| Lexar                       | 1         | 1      | 0.33%   |
| Intenso                     | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 5         | 1.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 4         | 1.27%   |
| Seagate ST500LM021-1KJ152 500GB                      | 3         | 0.96%   |
| Samsung SSD 860 EVO 250GB                            | 3         | 0.96%   |
| Samsung SSD 850 EVO 500GB                            | 3         | 0.96%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB              | 3         | 0.96%   |
| Kingston SA400S37960G 960GB SSD                      | 3         | 0.96%   |
| Kingston SA400S37240G 240GB SSD                      | 3         | 0.96%   |
| Kingston SA400S37120G 120GB SSD                      | 3         | 0.96%   |
| HGST HTS721010A9E630 1TB                             | 3         | 0.96%   |
| Unknown                                              | 3         | 0.96%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                 | 2         | 0.64%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB                 | 2         | 0.64%   |
| Unknown MMC Card  512GB                              | 2         | 0.64%   |
| Unknown MMC Card  16GB                               | 2         | 0.64%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 2         | 0.64%   |
| Toshiba NVMe SSD Drive 512GB                         | 2         | 0.64%   |
| Toshiba MQ01ABD100 1TB                               | 2         | 0.64%   |
| SK hynix PC601 NVMe 512GB                            | 2         | 0.64%   |
| SK hynix NVMe SSD Drive 512GB                        | 2         | 0.64%   |
| SK hynix NVMe SSD Drive 256GB                        | 2         | 0.64%   |
| Seagate ST500LT012-1DG142 500GB                      | 2         | 0.64%   |
| Seagate ST1000LM049-2GH172 1TB                       | 2         | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 2         | 0.64%   |
| Seagate BUP Portable 5TB                             | 2         | 0.64%   |
| SanDisk SD8SBAT256G1122 256GB SSD                    | 2         | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                         | 2         | 0.64%   |
| Samsung SSD 970 EVO Plus 500GB                       | 2         | 0.64%   |
| Samsung SSD 970 EVO Plus 1TB                         | 2         | 0.64%   |
| Samsung SSD 870 QVO 1TB                              | 2         | 0.64%   |
| Samsung SSD 850 EVO M.2 500GB                        | 2         | 0.64%   |
| Samsung NVMe SSD Drive 512GB                         | 2         | 0.64%   |
| Samsung NVMe SSD Drive 1TB                           | 2         | 0.64%   |
| Samsung NVMe SSD Drive 1024GB                        | 2         | 0.64%   |
| Samsung MZVLQ256HAJD-000H1 256GB                     | 2         | 0.64%   |
| Samsung MZVLB512HBJQ-000L7 512GB                     | 2         | 0.64%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD                 | 2         | 0.64%   |
| Patriot Burst 480GB SSD                              | 2         | 0.64%   |
| Patriot Burst 240GB SSD                              | 2         | 0.64%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                  | 2         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 31        | 34     | 51.67%  |
| Toshiba  | 8         | 8      | 13.33%  |
| HGST     | 7         | 8      | 11.67%  |
| WDC      | 6         | 7      | 10%     |
| Hitachi  | 5         | 5      | 8.33%   |
| Fujitsu  | 2         | 2      | 3.33%   |
| External | 1         | 1      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 46     | 34.21%  |
| Kingston            | 18        | 20     | 15.79%  |
| SanDisk             | 7         | 9      | 6.14%   |
| Patriot             | 5         | 6      | 4.39%   |
| SK hynix            | 4         | 4      | 3.51%   |
| Micron Technology   | 4         | 4      | 3.51%   |
| Crucial             | 4         | 4      | 3.51%   |
| WDC                 | 3         | 5      | 2.63%   |
| Intel               | 3         | 4      | 2.63%   |
| China               | 3         | 3      | 2.63%   |
| Apacer              | 3         | 3      | 2.63%   |
| A-DATA Technology   | 3         | 3      | 2.63%   |
| Transcend           | 2         | 5      | 1.75%   |
| Toshiba             | 2         | 2      | 1.75%   |
| LITEONIT            | 2         | 2      | 1.75%   |
| KingSpec            | 2         | 3      | 1.75%   |
| Apple               | 2         | 2      | 1.75%   |
| XPG                 | 1         | 1      | 0.88%   |
| Team                | 1         | 1      | 0.88%   |
| SPCC                | 1         | 3      | 0.88%   |
| Netac               | 1         | 1      | 0.88%   |
| Lexar               | 1         | 1      | 0.88%   |
| Intenso             | 1         | 1      | 0.88%   |
| Gigabyte Technology | 1         | 2      | 0.88%   |
| Unknown             | 1         | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 102       | 136    | 36.82%  |
| NVMe    | 101       | 128    | 36.46%  |
| HDD     | 58        | 65     | 20.94%  |
| MMC     | 11        | 12     | 3.97%   |
| Unknown | 5         | 6      | 1.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 147       | 196    | 54.04%  |
| NVMe | 101       | 126    | 37.13%  |
| SAS  | 13        | 13     | 4.78%   |
| MMC  | 11        | 12     | 4.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 117       | 145    | 70.06%  |
| 0.51-1.0   | 41        | 47     | 24.55%  |
| 1.01-2.0   | 6         | 6      | 3.59%   |
| 4.01-10.0  | 2         | 2      | 1.2%    |
| 3.01-4.0   | 1         | 1      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 85        | 33.86%  |
| 251-500        | 50        | 19.92%  |
| 501-1000       | 36        | 14.34%  |
| 1-20           | 25        | 9.96%   |
| 51-100         | 17        | 6.77%   |
| 1001-2000      | 13        | 5.18%   |
| Unknown        | 10        | 3.98%   |
| More than 3000 | 8         | 3.19%   |
| 21-50          | 5         | 1.99%   |
| 2001-3000      | 2         | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 96        | 36.78%  |
| 21-50          | 46        | 17.62%  |
| 101-250        | 39        | 14.94%  |
| 51-100         | 35        | 13.41%  |
| 251-500        | 19        | 7.28%   |
| 501-1000       | 11        | 4.21%   |
| Unknown        | 10        | 3.83%   |
| More than 3000 | 3         | 1.15%   |
| 2001-3000      | 1         | 0.38%   |
| 1001-2000      | 1         | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB                         | 1         | 1      | 5.56%   |
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 5.56%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 5.56%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 5.56%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 5.56%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 5.56%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 5.56%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 5.56%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 5.56%   |
| Netac SSD 720GB                                     | 1         | 1      | 5.56%   |
| Micron Technology MTFDDAK256TDL-1AW15ABHA 256GB SSD | 1         | 1      | 5.56%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 5.56%   |
| Kingston SA400S37960G 960GB SSD                     | 1         | 1      | 5.56%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 5.56%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 5.56%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 5.56%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 5.56%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 7         | 7      | 38.89%  |
| WDC               | 2         | 2      | 11.11%  |
| Micron Technology | 2         | 2      | 11.11%  |
| Kingston          | 2         | 2      | 11.11%  |
| Netac             | 1         | 1      | 5.56%   |
| Hitachi           | 1         | 1      | 5.56%   |
| HGST              | 1         | 1      | 5.56%   |
| Fujitsu           | 1         | 1      | 5.56%   |
| Crucial           | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 58.33%  |
| WDC     | 2         | 2      | 16.67%  |
| Hitachi | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 66.67%  |
| SSD  | 6         | 6      | 33.33%  |

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
| Detected | 133       | 200    | 52.36%  |
| Works    | 104       | 129    | 40.94%  |
| Malfunc  | 17        | 18     | 6.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 157       | 54.14%  |
| Samsung Electronics          | 32        | 11.03%  |
| AMD                          | 26        | 8.97%   |
| SanDisk                      | 17        | 5.86%   |
| SK hynix                     | 15        | 5.17%   |
| Toshiba America Info Systems | 10        | 3.45%   |
| Kingston Technology Company  | 6         | 2.07%   |
| KIOXIA                       | 5         | 1.72%   |
| Phison Electronics           | 4         | 1.38%   |
| Micron Technology            | 3         | 1.03%   |
| Lenovo                       | 3         | 1.03%   |
| Nvidia                       | 2         | 0.69%   |
| Micron/Crucial Technology    | 2         | 0.69%   |
| Marvell Technology Group     | 2         | 0.69%   |
| ADATA Technology             | 2         | 0.69%   |
| VIA Technologies             | 1         | 0.34%   |
| Union Memory (Shenzhen)      | 1         | 0.34%   |
| Realtek Semiconductor        | 1         | 0.34%   |
| Hosin Global Electronics     | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 22        | 7.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 6.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 5.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 17        | 5.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 5.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 11        | 3.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 3.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 2.58%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 2.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 2.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 2.26%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 1.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 1.94%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.61%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 1.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 1.61%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.61%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.29%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.29%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 4         | 1.29%   |
| Intel SSD 660P Series                                                          | 4         | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.29%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 3         | 0.97%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 3         | 0.97%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 0.97%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 2         | 0.65%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 2         | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.65%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.65%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                 | 2         | 0.65%   |
| Sandisk WD Blue SN580 NVMe SSD (DRAM-less)                                     | 2         | 0.65%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2         | 0.65%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.65%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 167       | 56.04%  |
| NVMe | 102       | 34.23%  |
| IDE  | 16        | 5.37%   |
| RAID | 13        | 4.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 192       | 78.37%  |
| AMD    | 53        | 21.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 8         | 3.27%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 5         | 2.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 2.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.63%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 4         | 1.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 1.63%   |
| AMD Custom APU 0405                     | 4         | 1.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 1.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 1.22%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 3         | 1.22%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz      | 3         | 1.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 1.22%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.22%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 3         | 1.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 1.22%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 3         | 1.22%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 1.22%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 2         | 0.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.82%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 2         | 0.82%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.82%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 2         | 0.82%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 2         | 0.82%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 2         | 0.82%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 2         | 0.82%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 0.82%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 2         | 0.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 0.82%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.82%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.82%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 2         | 0.82%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 2         | 0.82%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 2         | 0.82%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 0.82%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 2         | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 64        | 26.12%  |
| Intel Core i7                  | 61        | 24.9%   |
| Other                          | 24        | 9.8%    |
| AMD Ryzen 7                    | 15        | 6.12%   |
| AMD Ryzen 5                    | 12        | 4.9%    |
| Intel Core i3                  | 11        | 4.49%   |
| Intel Core 2 Duo               | 10        | 4.08%   |
| Intel Celeron                  | 10        | 4.08%   |
| AMD Ryzen 7 PRO                | 5         | 2.04%   |
| Intel Pentium                  | 3         | 1.22%   |
| Intel Pentium Silver           | 2         | 0.82%   |
| Intel Pentium M                | 2         | 0.82%   |
| Intel Core 2                   | 2         | 0.82%   |
| Intel Celeron Dual-Core        | 2         | 0.82%   |
| Intel Atom                     | 2         | 0.82%   |
| AMD Ryzen 5 PRO                | 2         | 0.82%   |
| AMD Ryzen 3 PRO                | 2         | 0.82%   |
| AMD Ryzen 3                    | 2         | 0.82%   |
| AMD A4                         | 2         | 0.82%   |
| Intel Xeon                     | 1         | 0.41%   |
| Intel Pentium Dual             | 1         | 0.41%   |
| Intel Core i9                  | 1         | 0.41%   |
| Intel Celeron M                | 1         | 0.41%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.41%   |
| AMD E2                         | 1         | 0.41%   |
| AMD E                          | 1         | 0.41%   |
| AMD C-60                       | 1         | 0.41%   |
| AMD Athlon II Dual-Core        | 1         | 0.41%   |
| AMD Athlon 64 X2               | 1         | 0.41%   |
| AMD A8                         | 1         | 0.41%   |
| AMD A6                         | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 112       | 45.71%  |
| 4       | 73        | 29.8%   |
| 6       | 23        | 9.39%   |
| 8       | 19        | 7.76%   |
| 1       | 7         | 2.86%   |
| 14      | 3         | 1.22%   |
| 12      | 3         | 1.22%   |
| 10      | 3         | 1.22%   |
| Unknown | 2         | 0.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 245       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 192       | 78.05%  |
| 1       | 52        | 21.14%  |
| Unknown | 2         | 0.81%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 242       | 98.78%  |
| 32-bit         | 2         | 0.82%   |
| Unknown        | 1         | 0.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 38.25%  |
| 0x206a7    | 14        | 5.58%   |
| 0x306a9    | 13        | 5.18%   |
| 0x306c3    | 12        | 4.78%   |
| 0x806ea    | 9         | 3.59%   |
| 0x40651    | 8         | 3.19%   |
| 0x08600106 | 7         | 2.79%   |
| 0x306d4    | 6         | 2.39%   |
| 0x906e9    | 5         | 1.99%   |
| 0x806ec    | 5         | 1.99%   |
| 0x806c1    | 5         | 1.99%   |
| 0x20655    | 5         | 1.99%   |
| 0x1067a    | 5         | 1.99%   |
| 0xa0652    | 4         | 1.59%   |
| 0x6fb      | 4         | 1.59%   |
| 0x506e3    | 4         | 1.59%   |
| 0x906ea    | 3         | 1.2%    |
| 0x806e9    | 3         | 1.2%    |
| 0x6fd      | 3         | 1.2%    |
| 0x406e3    | 3         | 1.2%    |
| 0x08108102 | 3         | 1.2%    |
| 0x05000119 | 3         | 1.2%    |
| 0x706a1    | 2         | 0.8%    |
| 0x6d8      | 2         | 0.8%    |
| 0x30678    | 2         | 0.8%    |
| 0x0a50000d | 2         | 0.8%    |
| 0x0a50000c | 2         | 0.8%    |
| 0x08600104 | 2         | 0.8%    |
| 0x906ed    | 1         | 0.4%    |
| 0x806eb    | 1         | 0.4%    |
| 0x806d1    | 1         | 0.4%    |
| 0x706a8    | 1         | 0.4%    |
| 0x6fa      | 1         | 0.4%    |
| 0x6f6      | 1         | 0.4%    |
| 0x30661    | 1         | 0.4%    |
| 0x106ca    | 1         | 0.4%    |
| 0x10676    | 1         | 0.4%    |
| 0x0b204019 | 1         | 0.4%    |
| 0x0a704103 | 1         | 0.4%    |
| 0x0a50000f | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 43        | 17.55%  |
| Haswell          | 27        | 11.02%  |
| SandyBridge      | 21        | 8.57%   |
| Unknown          | 21        | 8.57%   |
| IvyBridge        | 20        | 8.16%   |
| Zen 2            | 14        | 5.71%   |
| Broadwell        | 11        | 4.49%   |
| Skylake          | 10        | 4.08%   |
| Core             | 10        | 4.08%   |
| TigerLake        | 9         | 3.67%   |
| Zen 3            | 8         | 3.27%   |
| Westmere         | 8         | 3.27%   |
| Penryn           | 6         | 2.45%   |
| Zen+             | 5         | 2.04%   |
| Goldmont plus    | 4         | 1.63%   |
| CometLake        | 4         | 1.63%   |
| Bobcat           | 3         | 1.22%   |
| Alderlake Hybrid | 3         | 1.22%   |
| Zen              | 2         | 0.82%   |
| Silvermont       | 2         | 0.82%   |
| P6               | 2         | 0.82%   |
| Excavator        | 2         | 0.82%   |
| Bonnell          | 2         | 0.82%   |
| Tremont          | 1         | 0.41%   |
| Steamroller      | 1         | 0.41%   |
| Piledriver       | 1         | 0.41%   |
| K8 Hammer        | 1         | 0.41%   |
| K8 & K10 hybrid  | 1         | 0.41%   |
| K10              | 1         | 0.41%   |
| Icelake          | 1         | 0.41%   |
| Goldmont         | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 180       | 54.55%  |
| Nvidia           | 89        | 26.97%  |
| AMD              | 60        | 18.18%  |
| VIA Technologies | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 19        | 5.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 19        | 5.57%   |
| Intel UHD Graphics 620                                                        | 15        | 4.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 14        | 4.11%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 13        | 3.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 10        | 2.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 9         | 2.64%   |
| Intel HD Graphics 5500                                                        | 9         | 2.64%   |
| Intel Core Processor Integrated Graphics Controller                           | 8         | 2.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 8         | 2.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 6         | 1.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 6         | 1.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 6         | 1.76%   |
| Intel HD Graphics 620                                                         | 6         | 1.76%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 1.47%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 1.47%   |
| Intel HD Graphics 630                                                         | 5         | 1.47%   |
| Intel HD Graphics 530                                                         | 5         | 1.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 1.47%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 5         | 1.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 4         | 1.17%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 4         | 1.17%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 4         | 1.17%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 4         | 1.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.17%   |
| AMD VanGogh [AMD Custom GPU 0405]                                             | 4         | 1.17%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 3         | 0.88%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 0.88%   |
| Nvidia GM107GLM [Quadro M2000M]                                               | 3         | 0.88%   |
| Nvidia GK208M [GeForce GT 730M]                                               | 3         | 0.88%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 3         | 0.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 3         | 0.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 0.88%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 0.88%   |
| AMD Phoenix1                                                                  | 3         | 0.88%   |
| Nvidia TU117M [GeForce MX550]                                                 | 2         | 0.59%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.59%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 0.59%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 103       | 42.04%  |
| Intel + Nvidia | 69        | 28.16%  |
| 1 x AMD        | 43        | 17.55%  |
| AMD + Nvidia   | 10        | 4.08%   |
| 1 x Nvidia     | 8         | 3.27%   |
| Intel + AMD    | 6         | 2.45%   |
| 2 x Nvidia     | 2         | 0.82%   |
| 2 x Intel      | 2         | 0.82%   |
| 2 x AMD        | 1         | 0.41%   |
| 1 x VIA        | 1         | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 189       | 76.21%  |
| Proprietary | 51        | 20.56%  |
| Unknown     | 8         | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 146       | 59.11%  |
| 1.01-2.0   | 36        | 14.57%  |
| 0.01-0.5   | 27        | 10.93%  |
| 0.51-1.0   | 16        | 6.48%   |
| 3.01-4.0   | 15        | 6.07%   |
| 5.01-6.0   | 4         | 1.62%   |
| 7.01-8.0   | 1         | 0.4%    |
| 2.01-3.0   | 1         | 0.4%    |
| 8.01-16.0  | 1         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 52        | 17.57%  |
| Chimei Innolux          | 42        | 14.19%  |
| LG Display              | 33        | 11.15%  |
| BOE                     | 33        | 11.15%  |
| Dell                    | 26        | 8.78%   |
| Samsung Electronics     | 25        | 8.45%   |
| Sharp                   | 11        | 3.72%   |
| Chi Mei Optoelectronics | 11        | 3.72%   |
| Lenovo                  | 7         | 2.36%   |
| Apple                   | 7         | 2.36%   |
| Hewlett-Packard         | 6         | 2.03%   |
| Goldstar                | 6         | 2.03%   |
| PANDA                   | 5         | 1.69%   |
| LG Philips              | 4         | 1.35%   |
| Sony                    | 3         | 1.01%   |
| CSO                     | 3         | 1.01%   |
| Valve                   | 2         | 0.68%   |
| CPT                     | 2         | 0.68%   |
| AOC                     | 2         | 0.68%   |
| ViewSonic               | 1         | 0.34%   |
| Vestel Elektronik       | 1         | 0.34%   |
| Toshiba                 | 1         | 0.34%   |
| Sun                     | 1         | 0.34%   |
| Seiko/Epson             | 1         | 0.34%   |
| Philips                 | 1         | 0.34%   |
| Panasonic               | 1         | 0.34%   |
| Mi                      | 1         | 0.34%   |
| Lenovo Group Limited    | 1         | 0.34%   |
| KDB                     | 1         | 0.34%   |
| JDI                     | 1         | 0.34%   |
| InfoVision              | 1         | 0.34%   |
| CTO                     | 1         | 0.34%   |
| ASUSTek Computer        | 1         | 0.34%   |
| Analogix                | 1         | 0.34%   |
| Acer                    | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 5         | 1.65%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 4         | 1.32%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 4         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 3         | 0.99%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 3         | 0.99%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 0.99%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 3         | 0.99%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 3         | 0.99%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 2         | 0.66%   |
| Sony TV SNYDB01 1920x1080                                                 | 2         | 0.66%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.66%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                   | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 0.66%   |
| LG Philips LCD Monitor LPL0133 1280x800 304x190mm 14.1-inch               | 2         | 0.66%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.66%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 2         | 0.66%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch                  | 2         | 0.66%   |
| Dell P3421W DELA1A8 3440x1440 800x335mm 34.1-inch                         | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 350x190mm 15.7-inch  | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 0.66%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO7AA7 2560x1600 312x195mm 14.5-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 2         | 0.66%   |
| ViewSonic VP2030 SERIES VSC131C 1600x1200 408x306mm 20.1-inch             | 1         | 0.33%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch     | 1         | 0.33%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                     | 1         | 0.33%   |
| Sun X7200A SUN0596 1600x1200 408x306mm 20.1-inch                          | 1         | 0.33%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.33%   |
| Sharp LQ133M1JW40 SHP10CD 1920x1080 294x165mm 13.3-inch                   | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 122       | 43.42%  |
| 1366x768 (WXGA)    | 52        | 18.51%  |
| 1600x900 (HD+)     | 18        | 6.41%   |
| 3840x2160 (4K)     | 17        | 6.05%   |
| 1920x1200 (WUXGA)  | 16        | 5.69%   |
| 1280x800 (WXGA)    | 13        | 4.63%   |
| 2560x1600          | 10        | 3.56%   |
| 2560x1440 (QHD)    | 6         | 2.14%   |
| 3440x1440          | 5         | 1.78%   |
| 1680x1050 (WSXGA+) | 5         | 1.78%   |
| 1440x900 (WXGA+)   | 4         | 1.42%   |
| 800x1280           | 3         | 1.07%   |
| 1600x1200          | 2         | 0.71%   |
| 1280x1024 (SXGA)   | 2         | 0.71%   |
| 3840x2400          | 1         | 0.36%   |
| 3200x1800 (QHD+)   | 1         | 0.36%   |
| 2880x1800          | 1         | 0.36%   |
| 2560x1080          | 1         | 0.36%   |
| 2256x1504          | 1         | 0.36%   |
| 1024x768 (XGA)     | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 104       | 34.67%  |
| 14      | 48        | 16%     |
| 13      | 40        | 13.33%  |
| 24      | 19        | 6.33%   |
| 17      | 18        | 6%      |
| 27      | 10        | 3.33%   |
| 12      | 8         | 2.67%   |
| 16      | 7         | 2.33%   |
| 34      | 6         | 2%      |
| 21      | 4         | 1.33%   |
| Unknown | 4         | 1.33%   |
| 72      | 3         | 1%      |
| 31      | 3         | 1%      |
| 23      | 3         | 1%      |
| 22      | 3         | 1%      |
| 84      | 2         | 0.67%   |
| 40      | 2         | 0.67%   |
| 20      | 2         | 0.67%   |
| 7       | 2         | 0.67%   |
| 86      | 1         | 0.33%   |
| 65      | 1         | 0.33%   |
| 54      | 1         | 0.33%   |
| 43      | 1         | 0.33%   |
| 38      | 1         | 0.33%   |
| 29      | 1         | 0.33%   |
| 19      | 1         | 0.33%   |
| 18      | 1         | 0.33%   |
| 11      | 1         | 0.33%   |
| 10      | 1         | 0.33%   |
| 9       | 1         | 0.33%   |
| 3       | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 172       | 57.91%  |
| 201-300     | 35        | 11.78%  |
| 501-600     | 30        | 10.1%   |
| 351-400     | 20        | 6.73%   |
| 401-500     | 10        | 3.37%   |
| 701-800     | 6         | 2.02%   |
| 601-700     | 5         | 1.68%   |
| 1501-2000   | 5         | 1.68%   |
| Unknown     | 4         | 1.35%   |
| 801-900     | 3         | 1.01%   |
| 1001-1500   | 3         | 1.01%   |
| 1-100       | 3         | 1.01%   |
| 901-1000    | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 200       | 74.91%  |
| 16/10   | 46        | 17.23%  |
| 21/9    | 6         | 2.25%   |
| 4/3     | 3         | 1.12%   |
| 3/2     | 3         | 1.12%   |
| Unknown | 3         | 1.12%   |
| 5/4     | 2         | 0.75%   |
| 0.67    | 2         | 0.75%   |
| 6/5     | 1         | 0.37%   |
| 0.56    | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 101       | 33.78%  |
| 81-90          | 66        | 22.07%  |
| 71-80          | 19        | 6.35%   |
| 201-250        | 17        | 5.69%   |
| 121-130        | 16        | 5.35%   |
| 351-500        | 10        | 3.34%   |
| 301-350        | 10        | 3.34%   |
| 251-300        | 10        | 3.34%   |
| 111-120        | 10        | 3.34%   |
| More than 1000 | 8         | 2.68%   |
| 61-70          | 8         | 2.68%   |
| 151-200        | 4         | 1.34%   |
| 501-1000       | 4         | 1.34%   |
| Unknown        | 4         | 1.34%   |
| 1-40           | 3         | 1%      |
| 91-100         | 3         | 1%      |
| 41-50          | 2         | 0.67%   |
| 141-150        | 2         | 0.67%   |
| 51-60          | 1         | 0.33%   |
| 131-140        | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 121       | 41.16%  |
| 101-120       | 71        | 24.15%  |
| 51-100        | 50        | 17.01%  |
| 161-240       | 31        | 10.54%  |
| More than 240 | 11        | 3.74%   |
| 1-50          | 6         | 2.04%   |
| Unknown       | 4         | 1.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 186       | 74.4%   |
| 2     | 53        | 21.2%   |
| 3     | 8         | 3.2%    |
| 0     | 3         | 1.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 141       | 36.15%  |
| Realtek Semiconductor             | 110       | 28.21%  |
| Qualcomm Atheros                  | 48        | 12.31%  |
| Broadcom                          | 23        | 5.9%    |
| MediaTek                          | 14        | 3.59%   |
| ASIX Electronics                  | 7         | 1.79%   |
| Ralink                            | 5         | 1.28%   |
| Ericsson Business Mobile Networks | 5         | 1.28%   |
| Sierra Wireless                   | 4         | 1.03%   |
| Lenovo                            | 4         | 1.03%   |
| Fibocom                           | 4         | 1.03%   |
| Broadcom Limited                  | 4         | 1.03%   |
| TP-Link                           | 3         | 0.77%   |
| Nvidia                            | 2         | 0.51%   |
| JMicron Technology                | 2         | 0.51%   |
| Huawei Technologies               | 2         | 0.51%   |
| Hewlett-Packard                   | 2         | 0.51%   |
| VIA Technologies                  | 1         | 0.26%   |
| Van Ooijen Technische Informatica | 1         | 0.26%   |
| Samsung Electronics               | 1         | 0.26%   |
| Qualcomm Technologies             | 1         | 0.26%   |
| Qualcomm                          | 1         | 0.26%   |
| QinHeng Electronics               | 1         | 0.26%   |
| OPPO Electronics                  | 1         | 0.26%   |
| Marvell Technology Group          | 1         | 0.26%   |
| DisplayLink                       | 1         | 0.26%   |
| ASUSTek Computer                  | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 62        | 12.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 19        | 3.9%    |
| Intel Wireless 8265 / 8275                                             | 15        | 3.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 14        | 2.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 12        | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 2.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 2.26%   |
| Intel Wireless 7260                                                    | 11        | 2.26%   |
| Intel Wi-Fi 6 AX200                                                    | 11        | 2.26%   |
| Intel Wireless 7265                                                    | 10        | 2.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 8         | 1.64%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 1.44%   |
| Intel Wireless 8260                                                    | 7         | 1.44%   |
| Intel Wi-Fi 6 AX201                                                    | 7         | 1.44%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 6         | 1.23%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 6         | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 1.23%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 5         | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 1.03%   |
| Intel 82566MM Gigabit Network Connection                               | 5         | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.82%   |
| Intel Wireless 3160                                                    | 4         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                                   | 4         | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 0.82%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                      | 4         | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 3         | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 0.62%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 133       | 52.36%  |
| Qualcomm Atheros      | 36        | 14.17%  |
| Realtek Semiconductor | 33        | 12.99%  |
| Broadcom              | 20        | 7.87%   |
| MediaTek              | 11        | 4.33%   |
| Ralink                | 5         | 1.97%   |
| Sierra Wireless       | 4         | 1.57%   |
| Fibocom               | 4         | 1.57%   |
| Broadcom Limited      | 3         | 1.18%   |
| TP-Link               | 2         | 0.79%   |
| Qualcomm Technologies | 1         | 0.39%   |
| Qualcomm              | 1         | 0.39%   |
| Hewlett-Packard       | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 15        | 5.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 14        | 5.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 4.72%   |
| Intel Wireless 7260                                                     | 11        | 4.33%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 4.33%   |
| Intel Wireless 7265                                                     | 10        | 3.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 3.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 2.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.76%   |
| Intel Wireless 8260                                                     | 7         | 2.76%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 2.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 2.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 2.36%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 5         | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.57%   |
| Intel Wireless 3160                                                     | 4         | 1.57%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.57%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 4         | 1.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.18%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.18%   |
| Intel Wireless 3165                                                     | 3         | 1.18%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.18%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.18%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.18%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 2         | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.79%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.79%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 95        | 43.58%  |
| Intel                    | 72        | 33.03%  |
| Qualcomm Atheros         | 19        | 8.72%   |
| Broadcom                 | 8         | 3.67%   |
| ASIX Electronics         | 7         | 3.21%   |
| MediaTek                 | 3         | 1.38%   |
| Lenovo                   | 3         | 1.38%   |
| Nvidia                   | 2         | 0.92%   |
| JMicron Technology       | 2         | 0.92%   |
| VIA Technologies         | 1         | 0.46%   |
| TP-Link                  | 1         | 0.46%   |
| OPPO Electronics         | 1         | 0.46%   |
| Marvell Technology Group | 1         | 0.46%   |
| DisplayLink              | 1         | 0.46%   |
| Broadcom Limited         | 1         | 0.46%   |
| ASUSTek Computer         | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 62        | 28.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 19        | 8.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 5.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 5.02%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 3.65%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 3.2%    |
| Intel Ethernet Connection I217-LM                                      | 6         | 2.74%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 2.74%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 2.28%   |
| Intel 82566MM Gigabit Network Connection                               | 5         | 2.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 1.83%   |
| Intel Ethernet Connection (6) I219-V                                   | 4         | 1.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 1.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.37%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 1.37%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.91%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.91%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.91%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 0.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.91%   |
| Lenovo ThinkPad TBT3 LAN                                               | 2         | 0.91%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.91%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.91%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.46%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.46%   |
| OPPO OnePlus Nord 4                                                    | 1         | 0.46%   |
| MediaTek Infinix SMART 5                                               | 1         | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.46%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 0.46%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 1         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.46%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 242       | 52.72%  |
| Ethernet | 204       | 44.44%  |
| Modem    | 13        | 2.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 195       | 75%     |
| Ethernet | 65        | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 187       | 76.33%  |
| 1     | 54        | 22.04%  |
| 3     | 2         | 0.82%   |
| 0     | 2         | 0.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 207       | 82.47%  |
| Yes  | 44        | 17.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 48.77%  |
| Realtek Semiconductor           | 16        | 7.88%   |
| Qualcomm Atheros Communications | 16        | 7.88%   |
| Broadcom                        | 15        | 7.39%   |
| IMC Networks                    | 14        | 6.9%    |
| Foxconn / Hon Hai               | 11        | 5.42%   |
| Apple                           | 7         | 3.45%   |
| Cambridge Silicon Radio         | 6         | 2.96%   |
| Hewlett-Packard                 | 5         | 2.46%   |
| Realtek                         | 4         | 1.97%   |
| Toshiba                         | 2         | 0.99%   |
| Lite-On Technology              | 2         | 0.99%   |
| Dell                            | 2         | 0.99%   |
| TP-Link                         | 1         | 0.49%   |
| Ralink                          | 1         | 0.49%   |
| MediaTek                        | 1         | 0.49%   |
| Askey Computer                  | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 46        | 22.66%  |
| Intel AX201 Bluetooth                               | 17        | 8.37%   |
| Intel AX200 Bluetooth                               | 9         | 4.43%   |
| Realtek Bluetooth Radio                             | 8         | 3.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 3.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 3.94%   |
| Intel AX211 Bluetooth                               | 7         | 3.45%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.96%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 2.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 2.96%   |
| IMC Networks Bluetooth Device                       | 5         | 2.46%   |
| Realtek Bluetooth Radio                             | 4         | 1.97%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 4         | 1.97%   |
| Apple Bluetooth Host Controller                     | 4         | 1.97%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 1.48%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.48%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.48%   |
| Intel AX210 Bluetooth                               | 3         | 1.48%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.48%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.48%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.48%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.48%   |
| Toshiba Bluetooth USB Host Controller               | 2         | 0.99%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.99%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.99%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.99%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.99%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.99%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 0.99%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.99%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 1         | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.49%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.49%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.49%   |
| MediaTek Wireless_Device                            | 1         | 0.49%   |
| Lite-On Wireless_Device                             | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 189       | 62.38%  |
| AMD                   | 56        | 18.48%  |
| Nvidia                | 39        | 12.87%  |
| Lenovo                | 5         | 1.65%   |
| Realtek Semiconductor | 2         | 0.66%   |
| Logitech              | 2         | 0.66%   |
| VIA Technologies      | 1         | 0.33%   |
| Texas Instruments     | 1         | 0.33%   |
| TerraTec Electronic   | 1         | 0.33%   |
| Sony                  | 1         | 0.33%   |
| Roland                | 1         | 0.33%   |
| Micronas              | 1         | 0.33%   |
| Mark of the Unicorn   | 1         | 0.33%   |
| JMTek                 | 1         | 0.33%   |
| GN Netcom             | 1         | 0.33%   |
| C-Media Electronics   | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 38        | 10.13%  |
| Intel Sunrise Point-LP HD Audio                                            | 25        | 6.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 22        | 5.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19        | 5.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 4.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 4.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 3.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 2.93%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 2.93%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 2.67%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 2.67%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10        | 2.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 2.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 1.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.33%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 5         | 1.33%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.07%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.07%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.07%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.8%    |
| Nvidia AD107 High Definition Audio Controller                              | 3         | 0.8%    |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.8%    |
| Realtek Semiconductor USB Audio                                            | 2         | 0.53%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.53%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.53%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.53%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 62        | 35.43%  |
| SK hynix            | 39        | 22.29%  |
| Micron Technology   | 24        | 13.71%  |
| Kingston            | 17        | 9.71%   |
| Unknown             | 6         | 3.43%   |
| Crucial             | 6         | 3.43%   |
| Ramaxel Technology  | 3         | 1.71%   |
| Nanya Technology    | 3         | 1.71%   |
| G.Skill             | 3         | 1.71%   |
| Unknown (ABCD)      | 2         | 1.14%   |
| Elpida              | 2         | 1.14%   |
| ASint Technology    | 2         | 1.14%   |
| A-DATA Technology   | 2         | 1.14%   |
| Unifosa             | 1         | 0.57%   |
| Qimonda             | 1         | 0.57%   |
| Lexar               | 1         | 0.57%   |
| Kllisre             | 1         | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 2.13%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 2.13%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.6%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 3         | 1.6%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 1.06%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 1.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.06%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 1.06%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.06%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.06%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.06%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 1.06%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.06%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.06%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.06%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.06%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.06%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.06%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.06%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.06%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 1.06%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.06%   |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s          | 2         | 1.06%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.06%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.53%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.53%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.53%   |
| Unifosa RAM GU332G0AJEPR8H2L.. 2GB SODIMM DDR2 667MT/s           | 1         | 0.53%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 0.53%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 63        | 44.37%  |
| DDR3   | 49        | 34.51%  |
| DDR2   | 9         | 6.34%   |
| LPDDR4 | 7         | 4.93%   |
| LPDDR5 | 5         | 3.52%   |
| DDR5   | 5         | 3.52%   |
| LPDDR3 | 2         | 1.41%   |
| SDRAM  | 1         | 0.7%    |
| DDR    | 1         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 130       | 94.2%   |
| Row Of Chips | 7         | 5.07%   |
| DIMM         | 1         | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 60        | 37.5%   |
| 4096  | 43        | 26.88%  |
| 16384 | 28        | 17.5%   |
| 2048  | 16        | 10%     |
| 1024  | 7         | 4.38%   |
| 32768 | 5         | 3.13%   |
| 512   | 1         | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 31        | 19.38%  |
| 1600    | 31        | 19.38%  |
| 3200    | 25        | 15.63%  |
| 1333    | 12        | 7.5%    |
| 2400    | 11        | 6.88%   |
| 1334    | 10        | 6.25%   |
| 2133    | 5         | 3.13%   |
| 667     | 5         | 3.13%   |
| 5600    | 4         | 2.5%    |
| 4267    | 4         | 2.5%    |
| 1067    | 4         | 2.5%    |
| 6400    | 3         | 1.88%   |
| 4266    | 2         | 1.25%   |
| 3266    | 2         | 1.25%   |
| Unknown | 2         | 1.25%   |
| 8400    | 1         | 0.63%   |
| 7500    | 1         | 0.63%   |
| 4800    | 1         | 0.63%   |
| 4199    | 1         | 0.63%   |
| 1867    | 1         | 0.63%   |
| 975     | 1         | 0.63%   |
| 800     | 1         | 0.63%   |
| 533     | 1         | 0.63%   |
| 400     | 1         | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung Electronics             | 1         | 25%     |
| QinHeng Electronics             | 1         | 25%     |
| cab Produkttechnik GmbH & Co KG | 1         | 25%     |
| Brother Industries              | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung ML-1670 Series                   | 1         | 25%     |
| QinHeng CH340S                           | 1         | 25%     |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 25%     |
| Brother DCP-L2510D series                | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 52        | 24.53%  |
| IMC Networks                           | 22        | 10.38%  |
| Microdia                               | 20        | 9.43%   |
| Bison Electronics                      | 17        | 8.02%   |
| Sunplus Innovation Technology          | 16        | 7.55%   |
| Realtek Semiconductor                  | 16        | 7.55%   |
| Lite-On Technology                     | 9         | 4.25%   |
| Luxvisions Innotech Limited            | 8         | 3.77%   |
| Suyin                                  | 6         | 2.83%   |
| Silicon Motion                         | 6         | 2.83%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.83%   |
| Apple                                  | 6         | 2.83%   |
| Acer                                   | 6         | 2.83%   |
| Syntek                                 | 5         | 2.36%   |
| Quanta                                 | 4         | 1.89%   |
| Logitech                               | 3         | 1.42%   |
| Sonix Technology                       | 2         | 0.94%   |
| Xiaomi                                 | 1         | 0.47%   |
| Tripath Technology                     | 1         | 0.47%   |
| Shinetech                              | 1         | 0.47%   |
| LG Electronics                         | 1         | 0.47%   |
| Lenovo                                 | 1         | 0.47%   |
| Importek                               | 1         | 0.47%   |
| Huddly                                 | 1         | 0.47%   |
| Alcor Micro                            | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 14        | 6.54%   |
| Microdia Integrated_Webcam_HD                           | 10        | 4.67%   |
| Bison Integrated Camera                                 | 8         | 3.74%   |
| Lite-On Integrated Camera                               | 7         | 3.27%   |
| IMC Networks Integrated Camera                          | 7         | 3.27%   |
| Sunplus Integrated_Webcam_HD                            | 4         | 1.87%   |
| Realtek USB Camera                                      | 4         | 1.87%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 1.87%   |
| Syntek Integrated Camera                                | 3         | 1.4%    |
| Realtek Integrated_Webcam_HD                            | 3         | 1.4%    |
| Luxvisions Innotech Limited Integrated RGB Camera       | 3         | 1.4%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.4%    |
| Chicony ThinkPad T490 Webcam                            | 3         | 1.4%    |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 1.4%    |
| Chicony Integrated HP HD Webcam                         | 3         | 1.4%    |
| Chicony HP HD Webcam                                    | 3         | 1.4%    |
| Chicony FJ Camera                                       | 3         | 1.4%    |
| Apple FaceTime HD Camera                                | 3         | 1.4%    |
| Sunplus Asus Webcam                                     | 2         | 0.93%   |
| Sonix USB2.0 FHD UVC WebCam                             | 2         | 0.93%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 0.93%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.93%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.93%   |
| Quanta HP HD Camera                                     | 2         | 0.93%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 0.93%   |
| Luxvisions Innotech Limited Integrated Camera           | 2         | 0.93%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 0.93%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 0.93%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 0.93%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 0.93%   |
| Chicony HD Webcam                                       | 2         | 0.93%   |
| Chicony HD User Facing                                  | 2         | 0.93%   |
| Bison SunplusIT Integrated Camera                       | 2         | 0.93%   |
| Bison SunplusIT INC. Integrated Camera                  | 2         | 0.93%   |
| Apple Built-in iSight                                   | 2         | 0.93%   |
| Xiaomi MI 9                                             | 1         | 0.47%   |
| Tripath USB Camera                                      | 1         | 0.47%   |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.47%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.47%   |
| Suyin USB Webcam                                        | 1         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 25        | 40.32%  |
| Synaptics                          | 18        | 29.03%  |
| STMicroelectronics                 | 5         | 8.06%   |
| Shenzhen Goodix Technology         | 5         | 8.06%   |
| Upek                               | 4         | 6.45%   |
| AuthenTec                          | 2         | 3.23%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.61%   |
| LighTuning Technology              | 1         | 1.61%   |
| Elan Microelectronics              | 1         | 1.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 9         | 14.52%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 9.68%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 6         | 9.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 8.06%   |
| STMicroelectronics Fingerprint Reader                           | 5         | 8.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 4         | 6.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 6.45%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 4.84%   |
| Shenzhen Goodix FingerPrint                                     | 3         | 4.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 3.23%   |
| Validity Sensors VFS491                                         | 2         | 3.23%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 3.23%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 1.61%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 1.61%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.61%   |
| Synaptics WBDI                                                  | 1         | 1.61%   |
| Synaptics Prometheus Fingerprint Reader                         | 1         | 1.61%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.61%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.61%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.61%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.61%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 1.61%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 1.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 33        | 58.93%  |
| Broadcom              | 9         | 16.07%  |
| OmniKey               | 6         | 10.71%  |
| Lenovo                | 4         | 7.14%   |
| Gemalto (was Gemplus) | 3         | 5.36%   |
| O2 Micro              | 1         | 1.79%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 33        | 58.93%  |
| Broadcom 58200                                                               | 5         | 8.93%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 7.14%   |
| OmniKey CardMan 4321                                                         | 3         | 5.36%   |
| OmniKey CardMan 1021                                                         | 3         | 5.36%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 3.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.57%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.79%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.79%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 1.79%   |
| Broadcom 5880                                                                | 1         | 1.79%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 131       | 52.61%  |
| 1     | 85        | 34.14%  |
| 2     | 29        | 11.65%  |
| 3     | 3         | 1.2%    |
| 4     | 1         | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 62        | 41.33%  |
| Graphics card            | 33        | 22%     |
| Chipcard                 | 31        | 20.67%  |
| Multimedia controller    | 6         | 4%      |
| Camera                   | 5         | 3.33%   |
| Net/wireless             | 4         | 2.67%   |
| Card reader              | 3         | 2%      |
| Net/ethernet             | 2         | 1.33%   |
| Storage                  | 1         | 0.67%   |
| Modem                    | 1         | 0.67%   |
| Communication controller | 1         | 0.67%   |
| Bluetooth                | 1         | 0.67%   |

