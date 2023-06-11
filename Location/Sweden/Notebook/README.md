Linux in Sweden - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

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

Total: 1516

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [8fa2e2acc9](https://linux-hardware.org/?probe=8fa2e2acc9) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6a98d856ee](https://linux-hardware.org/?probe=6a98d856ee) | Jun 07, 2023 |
| Dell          | Latitude 3340               | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| ASUSTek       | X505BP                      | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| Timi          | RedmiBook 14 II             | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| MSI           | Katana GF76 12UD            | [b1b1816b59](https://linux-hardware.org/?probe=b1b1816b59) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| ASUSTek       | G75VW                       | [32fee60a54](https://linux-hardware.org/?probe=32fee60a54) | May 28, 2023 |
| ASUSTek       | G75VW                       | [ec91d28c95](https://linux-hardware.org/?probe=ec91d28c95) | May 28, 2023 |
| HP            | Compaq 6730s                | [fe2b8b63ac](https://linux-hardware.org/?probe=fe2b8b63ac) | May 28, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [dbfc9be02f](https://linux-hardware.org/?probe=dbfc9be02f) | May 26, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [25f6dcaefc](https://linux-hardware.org/?probe=25f6dcaefc) | May 25, 2023 |
| HP            | Laptop 14s-fq1xxx           | [73d0ff64b6](https://linux-hardware.org/?probe=73d0ff64b6) | May 23, 2023 |
| Lenovo        | ThinkPad T550 20CJS1V900    | [9bc275ef54](https://linux-hardware.org/?probe=9bc275ef54) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [117bc29848](https://linux-hardware.org/?probe=117bc29848) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [e3af81180a](https://linux-hardware.org/?probe=e3af81180a) | May 22, 2023 |
| Acer          | Aspire E1-571               | [cce6eaa028](https://linux-hardware.org/?probe=cce6eaa028) | May 20, 2023 |
| HP            | Compaq 6730s                | [632961079b](https://linux-hardware.org/?probe=632961079b) | May 20, 2023 |
| Notebook      | NLx0MU                      | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [7d818512b8](https://linux-hardware.org/?probe=7d818512b8) | May 17, 2023 |
| Packard Be... | EasyNote TV43CM             | [66dbc844c7](https://linux-hardware.org/?probe=66dbc844c7) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [7d44c65f86](https://linux-hardware.org/?probe=7d44c65f86) | May 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [36df0e0f57](https://linux-hardware.org/?probe=36df0e0f57) | May 14, 2023 |
| HP            | EliteBook 850 G6            | [df19e8413c](https://linux-hardware.org/?probe=df19e8413c) | May 14, 2023 |
| HP            | EliteBook 840 G5            | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | ProBook 6470b               | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| MSI           | Stealth 16Studio A13VG      | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| HP            | EliteBook 840 G6            | [bd7c97ad54](https://linux-hardware.org/?probe=bd7c97ad54) | May 11, 2023 |
| HP            | EliteBook 840 G6            | [483f4bbb5d](https://linux-hardware.org/?probe=483f4bbb5d) | May 10, 2023 |
| Dynabook      | Satellite Pro C50-J         | [535cc48341](https://linux-hardware.org/?probe=535cc48341) | May 08, 2023 |
| Dell          | Vostro 3360                 | [13a1e30b53](https://linux-hardware.org/?probe=13a1e30b53) | May 06, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Dell          | Latitude 5430               | [644e44f95a](https://linux-hardware.org/?probe=644e44f95a) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | [07572e6599](https://linux-hardware.org/?probe=07572e6599) | Apr 27, 2023 |
| ASUSTek       | G75VW                       | [ff439c208a](https://linux-hardware.org/?probe=ff439c208a) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | [69f1753783](https://linux-hardware.org/?probe=69f1753783) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | [067bc49888](https://linux-hardware.org/?probe=067bc49888) | Apr 26, 2023 |
| Acer          | Aspire E1-571               | [c6a1179816](https://linux-hardware.org/?probe=c6a1179816) | Apr 25, 2023 |
| Acer          | Aspire ES1-311              | [4fcb9881b2](https://linux-hardware.org/?probe=4fcb9881b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| ASUSTek       | G75VW                       | [21c872ac1c](https://linux-hardware.org/?probe=21c872ac1c) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [99e0054492](https://linux-hardware.org/?probe=99e0054492) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [86b56d3e69](https://linux-hardware.org/?probe=86b56d3e69) | Apr 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [adab9d9f6b](https://linux-hardware.org/?probe=adab9d9f6b) | Apr 22, 2023 |
| HP            | Laptop 17-cp0xxx            | [17c955a974](https://linux-hardware.org/?probe=17c955a974) | Apr 21, 2023 |
| Dell          | Latitude 7490               | [57a719ce62](https://linux-hardware.org/?probe=57a719ce62) | Apr 20, 2023 |
| Unknown       | Unknown                     | [83c6b6137d](https://linux-hardware.org/?probe=83c6b6137d) | Apr 20, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6SV0... | [8f05b53b93](https://linux-hardware.org/?probe=8f05b53b93) | Apr 17, 2023 |
| Acer          | Aspire E1-571               | [4278a9f497](https://linux-hardware.org/?probe=4278a9f497) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | [a9f8183365](https://linux-hardware.org/?probe=a9f8183365) | Apr 16, 2023 |
| ASUSTek       | G75VW                       | [a51c500b65](https://linux-hardware.org/?probe=a51c500b65) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| HP            | EliteBook 8570p             | [b259f47200](https://linux-hardware.org/?probe=b259f47200) | Apr 15, 2023 |
| HP            | EliteBook 8570p             | [ec6dc0883b](https://linux-hardware.org/?probe=ec6dc0883b) | Apr 13, 2023 |
| Dell          | XPS 13 9370                 | [66924704d2](https://linux-hardware.org/?probe=66924704d2) | Apr 12, 2023 |
| Acer          | Aspire ES1-311              | [810aed46d0](https://linux-hardware.org/?probe=810aed46d0) | Apr 11, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| HP            | ProBook 4530s               | [efd084d9d5](https://linux-hardware.org/?probe=efd084d9d5) | Apr 07, 2023 |
| LG Electro... | Kabylake Platform           | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | [0f4a907d19](https://linux-hardware.org/?probe=0f4a907d19) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | [d337edfd9a](https://linux-hardware.org/?probe=d337edfd9a) | Apr 05, 2023 |
| HP            | ProBook 450 G1              | [f49ec499ed](https://linux-hardware.org/?probe=f49ec499ed) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Dell          | Precision 5530              | [bf568860cb](https://linux-hardware.org/?probe=bf568860cb) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [550f1d522d](https://linux-hardware.org/?probe=550f1d522d) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d57f6cb4c6](https://linux-hardware.org/?probe=d57f6cb4c6) | Apr 03, 2023 |
| Acer          | Swift SF113-31              | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| HP            | ENVY TS Sleekbook 4         | [f897573506](https://linux-hardware.org/?probe=f897573506) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK U938               | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| HP            | ProBook 450 G3              | [f0e6089a6e](https://linux-hardware.org/?probe=f0e6089a6e) | Mar 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Dell          | XPS 15 9530                 | [c5a3b374a7](https://linux-hardware.org/?probe=c5a3b374a7) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | [f403538019](https://linux-hardware.org/?probe=f403538019) | Mar 26, 2023 |
| Gigabyte      | AORUS 15G KC                | [d87e89d84f](https://linux-hardware.org/?probe=d87e89d84f) | Mar 26, 2023 |
| ASUSTek       | G75VW                       | [6f9300474f](https://linux-hardware.org/?probe=6f9300474f) | Mar 26, 2023 |
| HP            | ProBook 650 G1              | [d1baffa910](https://linux-hardware.org/?probe=d1baffa910) | Mar 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [883d4de906](https://linux-hardware.org/?probe=883d4de906) | Mar 21, 2023 |
| Acer          | Aspire M3-581T              | [a9a586ef2d](https://linux-hardware.org/?probe=a9a586ef2d) | Mar 20, 2023 |
| Acer          | Aspire M3-581T              | [51e5415bb0](https://linux-hardware.org/?probe=51e5415bb0) | Mar 19, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [c88d5f831a](https://linux-hardware.org/?probe=c88d5f831a) | Mar 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| Acer          | Aspire M3-581T              | [dfb8518fa9](https://linux-hardware.org/?probe=dfb8518fa9) | Mar 16, 2023 |
| Acer          | Aspire M3-581T              | [bb4f0202b7](https://linux-hardware.org/?probe=bb4f0202b7) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Google        | Rabbid                      | [621762ceec](https://linux-hardware.org/?probe=621762ceec) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| HP            | Laptop 17-ca0xxx            | [016f5cd3be](https://linux-hardware.org/?probe=016f5cd3be) | Mar 14, 2023 |
| GPD           | P2 MAX                      | [dd958bf28e](https://linux-hardware.org/?probe=dd958bf28e) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [1169593829](https://linux-hardware.org/?probe=1169593829) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [76e4cc71f5](https://linux-hardware.org/?probe=76e4cc71f5) | Mar 12, 2023 |
| HP            | Laptop 17-ca0xxx            | [c22a046fc6](https://linux-hardware.org/?probe=c22a046fc6) | Mar 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [0555c85a89](https://linux-hardware.org/?probe=0555c85a89) | Mar 11, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| HP            | Presario CQ57               | [33b1812664](https://linux-hardware.org/?probe=33b1812664) | Mar 06, 2023 |
| HP            | Presario CQ57               | [26ec55c2cb](https://linux-hardware.org/?probe=26ec55c2cb) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| HP            | EliteBook 840 G3            | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [19bd4c1e4e](https://linux-hardware.org/?probe=19bd4c1e4e) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Dell          | Precision 3551              | [7c1bc8355a](https://linux-hardware.org/?probe=7c1bc8355a) | Mar 03, 2023 |
| Clevo         | W25xHNx                     | [5227127f81](https://linux-hardware.org/?probe=5227127f81) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| HP            | EliteBook Folio 9470m       | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0AE0... | [7f8c9de1aa](https://linux-hardware.org/?probe=7f8c9de1aa) | Feb 24, 2023 |
| ASUSTek       | G75VW                       | [de328ac1ad](https://linux-hardware.org/?probe=de328ac1ad) | Feb 22, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [da461191e8](https://linux-hardware.org/?probe=da461191e8) | Feb 21, 2023 |
| Dell          | Precision M4800             | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| ASUSTek       | G501VW                      | [6e014311b2](https://linux-hardware.org/?probe=6e014311b2) | Feb 20, 2023 |
| Acer          | Aspire A317-33              | [7427fa6886](https://linux-hardware.org/?probe=7427fa6886) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | [96b350db9f](https://linux-hardware.org/?probe=96b350db9f) | Feb 18, 2023 |
| GPD           | P2 MAX                      | [9a623b2196](https://linux-hardware.org/?probe=9a623b2196) | Feb 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [eac9c046ac](https://linux-hardware.org/?probe=eac9c046ac) | Feb 15, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [3717c2476f](https://linux-hardware.org/?probe=3717c2476f) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [eb40144624](https://linux-hardware.org/?probe=eb40144624) | Feb 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| HP            | EliteBook 820 G3            | [c1ac37fee3](https://linux-hardware.org/?probe=c1ac37fee3) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| HP            | EliteBook 840 G4            | [a60a4191b8](https://linux-hardware.org/?probe=a60a4191b8) | Feb 10, 2023 |
| Dell          | Latitude E7250              | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| Apple         | MacBookPro10,1              | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| Dell          | Latitude E7250              | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [3797cf0990](https://linux-hardware.org/?probe=3797cf0990) | Feb 07, 2023 |
| HP            | Laptop 15-dw1xxx            | [452216b5ed](https://linux-hardware.org/?probe=452216b5ed) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | [bbe182e4c2](https://linux-hardware.org/?probe=bbe182e4c2) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | [f265a0e81e](https://linux-hardware.org/?probe=f265a0e81e) | Feb 04, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [1752779e0c](https://linux-hardware.org/?probe=1752779e0c) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [ef707954b8](https://linux-hardware.org/?probe=ef707954b8) | Feb 02, 2023 |
| Apple         | MacBookPro12,1              | [6e089e22b1](https://linux-hardware.org/?probe=6e089e22b1) | Feb 01, 2023 |
| Dell          | Latitude 7420               | [f0b8816283](https://linux-hardware.org/?probe=f0b8816283) | Feb 01, 2023 |
| Dell          | Latitude 7420               | [55f81648a1](https://linux-hardware.org/?probe=55f81648a1) | Jan 31, 2023 |
| Dell          | Latitude 7480               | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| Dell          | Latitude D630C              | [401357bc99](https://linux-hardware.org/?probe=401357bc99) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Valve         | Jupiter                     | [c4a13a66ed](https://linux-hardware.org/?probe=c4a13a66ed) | Jan 25, 2023 |
| HP            | EliteBook 8470p             | [cb00a3e89d](https://linux-hardware.org/?probe=cb00a3e89d) | Jan 24, 2023 |
| Google        | Link                        | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Valve         | Jupiter                     | [1a9bed0cf3](https://linux-hardware.org/?probe=1a9bed0cf3) | Jan 23, 2023 |
| AMI           | Intel                       | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Apple         | MacBookPro8,1               | [fa1f3d8e3b](https://linux-hardware.org/?probe=fa1f3d8e3b) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [1d10977303](https://linux-hardware.org/?probe=1d10977303) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [fdbbb4a832](https://linux-hardware.org/?probe=fdbbb4a832) | Jan 21, 2023 |
| Acer          | Aspire V3-571               | [d7e7799006](https://linux-hardware.org/?probe=d7e7799006) | Jan 20, 2023 |
| Star Labs     | StarBook                    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Dell          | XPS 13 9370                 | [5b26575c52](https://linux-hardware.org/?probe=5b26575c52) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [b0308f4270](https://linux-hardware.org/?probe=b0308f4270) | Jan 13, 2023 |
| Dell          | Studio 1749                 | [28a19b2c03](https://linux-hardware.org/?probe=28a19b2c03) | Jan 11, 2023 |
| ASUSTek       | N552VX                      | [7697ff8cb4](https://linux-hardware.org/?probe=7697ff8cb4) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| Acer          | Nitro AN515-44              | [aacfe1b351](https://linux-hardware.org/?probe=aacfe1b351) | Jan 11, 2023 |
| Toshiba       | Satellite L50D-B            | [5cfaf7d715](https://linux-hardware.org/?probe=5cfaf7d715) | Jan 10, 2023 |
| ASUSTek       | N552VX                      | [59155b3092](https://linux-hardware.org/?probe=59155b3092) | Jan 10, 2023 |
| Dell          | XPS 13 9343                 | [ac85316fc2](https://linux-hardware.org/?probe=ac85316fc2) | Jan 09, 2023 |
| MSI           | GP60 2PE                    | [e1506ca6f6](https://linux-hardware.org/?probe=e1506ca6f6) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Samsung       | R530/R730                   | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Samsung       | R530/R730                   | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Precision M90               | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | Pavilion g6                 | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Valve         | Jupiter                     | [77cc17c28c](https://linux-hardware.org/?probe=77cc17c28c) | Jan 02, 2023 |
| Acer          | Aspire V3-571G              | [273f6722e0](https://linux-hardware.org/?probe=273f6722e0) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Lenovo        | Z70-80 80FG                 | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Valve         | Jupiter                     | [15c60654b3](https://linux-hardware.org/?probe=15c60654b3) | Dec 30, 2022 |
| Apple         | MacBookPro11,3              | [87d0f67d84](https://linux-hardware.org/?probe=87d0f67d84) | Dec 30, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| Dell          | Latitude 3380               | [e4847d5b1f](https://linux-hardware.org/?probe=e4847d5b1f) | Dec 24, 2022 |
| HP            | EliteBook 840 G5            | [92f12e3ec7](https://linux-hardware.org/?probe=92f12e3ec7) | Dec 24, 2022 |
| MSI           | Katana GF66 11UE            | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92515d8a95](https://linux-hardware.org/?probe=92515d8a95) | Dec 21, 2022 |
| Schenker      | XMG APEX 15 MAX (E22)       | [6b46538fea](https://linux-hardware.org/?probe=6b46538fea) | Dec 21, 2022 |
| Dell          | Latitude 3380               | [808c693271](https://linux-hardware.org/?probe=808c693271) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4fbc0ddbd5](https://linux-hardware.org/?probe=4fbc0ddbd5) | Dec 20, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ffa7e28596](https://linux-hardware.org/?probe=ffa7e28596) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [888e6092a6](https://linux-hardware.org/?probe=888e6092a6) | Dec 15, 2022 |
| HP            | EliteBook 830 G6            | [5248ee7dbe](https://linux-hardware.org/?probe=5248ee7dbe) | Dec 15, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [3403282c8c](https://linux-hardware.org/?probe=3403282c8c) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Dell          | Latitude E7240              | [c47fc4fadf](https://linux-hardware.org/?probe=c47fc4fadf) | Dec 14, 2022 |
| Insyde        | G0975                       | [1f4823542d](https://linux-hardware.org/?probe=1f4823542d) | Dec 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| Dell          | Latitude 5430               | [b439d1e1a4](https://linux-hardware.org/?probe=b439d1e1a4) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| Google        | Orco                        | [40acd3207e](https://linux-hardware.org/?probe=40acd3207e) | Dec 10, 2022 |
| Google        | Orco                        | [9c369b40b3](https://linux-hardware.org/?probe=9c369b40b3) | Dec 10, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | [d01d1e9652](https://linux-hardware.org/?probe=d01d1e9652) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | [ff90421b87](https://linux-hardware.org/?probe=ff90421b87) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | [3bc6ea9cfa](https://linux-hardware.org/?probe=3bc6ea9cfa) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | [aaed16d626](https://linux-hardware.org/?probe=aaed16d626) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | [cd63efdbd4](https://linux-hardware.org/?probe=cd63efdbd4) | Dec 05, 2022 |
| Sony          | VPCEB1M1E                   | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | [d8d5459ad6](https://linux-hardware.org/?probe=d8d5459ad6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | [1dddd99280](https://linux-hardware.org/?probe=1dddd99280) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F10034MX    | [34842eb8d9](https://linux-hardware.org/?probe=34842eb8d9) | Dec 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [258c074e40](https://linux-hardware.org/?probe=258c074e40) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [29ec19d38e](https://linux-hardware.org/?probe=29ec19d38e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | [97fda88c7b](https://linux-hardware.org/?probe=97fda88c7b) | Nov 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [7121172cc6](https://linux-hardware.org/?probe=7121172cc6) | Nov 22, 2022 |
| Dell          | XPS 9320                    | [52b55ea024](https://linux-hardware.org/?probe=52b55ea024) | Nov 21, 2022 |
| Dell          | XPS 9320                    | [7ea2296eaf](https://linux-hardware.org/?probe=7ea2296eaf) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [3534f07f4a](https://linux-hardware.org/?probe=3534f07f4a) | Nov 18, 2022 |
| ASUSTek       | N550JK                      | [86a2f7caea](https://linux-hardware.org/?probe=86a2f7caea) | Nov 18, 2022 |
| Dell          | Latitude 5310               | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| HP            | ZBook 15u G6                | [e6600fae5a](https://linux-hardware.org/?probe=e6600fae5a) | Nov 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| Apple         | MacBook5,1                  | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [48f127b453](https://linux-hardware.org/?probe=48f127b453) | Nov 11, 2022 |
| ASUSTek       | U36SD                       | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| Acer          | Aspire A515-52              | [ed07b564ec](https://linux-hardware.org/?probe=ed07b564ec) | Nov 07, 2022 |
| HP            | EliteBook 830 G5            | [92c837ff5a](https://linux-hardware.org/?probe=92c837ff5a) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | [298819594a](https://linux-hardware.org/?probe=298819594a) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| HP            | ZBook 15u G6                | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| Apple         | MacBookPro16,2              | [ad1ae18c98](https://linux-hardware.org/?probe=ad1ae18c98) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [9d1ba43c71](https://linux-hardware.org/?probe=9d1ba43c71) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [dac055fa29](https://linux-hardware.org/?probe=dac055fa29) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [063675c104](https://linux-hardware.org/?probe=063675c104) | Oct 29, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [f95081e76e](https://linux-hardware.org/?probe=f95081e76e) | Oct 27, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [0fcfd33f95](https://linux-hardware.org/?probe=0fcfd33f95) | Oct 27, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| Valve         | Jupiter                     | [302efb993a](https://linux-hardware.org/?probe=302efb993a) | Oct 22, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | [8f3fdb4d9c](https://linux-hardware.org/?probe=8f3fdb4d9c) | Oct 22, 2022 |
| Valve         | Jupiter                     | [024fdc987b](https://linux-hardware.org/?probe=024fdc987b) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| Valve         | Jupiter                     | [6249475f24](https://linux-hardware.org/?probe=6249475f24) | Oct 20, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Apple         | MacBookAir6,1               | [2438851671](https://linux-hardware.org/?probe=2438851671) | Oct 16, 2022 |
| Acer          | Aspire V3-571               | [8457aa21e7](https://linux-hardware.org/?probe=8457aa21e7) | Oct 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [689281cab0](https://linux-hardware.org/?probe=689281cab0) | Oct 15, 2022 |
| Dell          | XPS 13 9360                 | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Acer          | Aspire 8950G                | [8888f23e03](https://linux-hardware.org/?probe=8888f23e03) | Oct 14, 2022 |
| Lenovo        | ThinkPad E595 20NF001HMX    | [1ae4e8967a](https://linux-hardware.org/?probe=1ae4e8967a) | Oct 14, 2022 |
| Gigabyte      | P65Q                        | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [10ea852e71](https://linux-hardware.org/?probe=10ea852e71) | Oct 12, 2022 |
| Dell          | XPS 15 9560                 | [ef1a363500](https://linux-hardware.org/?probe=ef1a363500) | Oct 11, 2022 |
| Apple         | MacBookPro9,2               | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| HP            | Pavilion dv7                | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Dell          | XPS 13 7390                 | [c52e60caae](https://linux-hardware.org/?probe=c52e60caae) | Oct 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [28d49251c7](https://linux-hardware.org/?probe=28d49251c7) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| ASUSTek       | UX303UB                     | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | Latitude E6320              | [69290cc372](https://linux-hardware.org/?probe=69290cc372) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| Dell          | XPS 13 9310                 | [6f9bc0cdba](https://linux-hardware.org/?probe=6f9bc0cdba) | Sep 26, 2022 |
| Dell          | XPS 13 9310                 | [d65cd8309b](https://linux-hardware.org/?probe=d65cd8309b) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [8f29c3dc10](https://linux-hardware.org/?probe=8f29c3dc10) | Sep 24, 2022 |
| TUXEDO        | Unknown                     | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| Valve         | Jupiter                     | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Lenovo        | Yoga 13sACN 2021 82CY       | [d374a74e0d](https://linux-hardware.org/?probe=d374a74e0d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| HP            | Pavilion g7                 | [a5f3f12174](https://linux-hardware.org/?probe=a5f3f12174) | Sep 20, 2022 |
| ASUSTek       | GL553VE                     | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| Dell          | Latitude E6320              | [4995ae034f](https://linux-hardware.org/?probe=4995ae034f) | Sep 19, 2022 |
| Dell          | Latitude E6320              | [4bf59d7938](https://linux-hardware.org/?probe=4bf59d7938) | Sep 19, 2022 |
| ASUSTek       | GL553VE                     | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4c33a54701](https://linux-hardware.org/?probe=4c33a54701) | Sep 16, 2022 |
| Dell          | Latitude 7300               | [9802315270](https://linux-hardware.org/?probe=9802315270) | Sep 14, 2022 |
| Dell          | Latitude 7300               | [5d82c4da95](https://linux-hardware.org/?probe=5d82c4da95) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| HP            | ProBook 440 G7              | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| HP            | Compaq Presario CQ60        | [f6981692e0](https://linux-hardware.org/?probe=f6981692e0) | Sep 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [308047a7cb](https://linux-hardware.org/?probe=308047a7cb) | Sep 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b1edd48233](https://linux-hardware.org/?probe=b1edd48233) | Sep 05, 2022 |
| Acer          | Aspire V3-571G              | [3f17eeffec](https://linux-hardware.org/?probe=3f17eeffec) | Sep 03, 2022 |
| Dell          | Latitude 7300               | [30994e1857](https://linux-hardware.org/?probe=30994e1857) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| Purism        | Librem 14                   | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| HP            | Pavilion 15                 | [19c7cae23c](https://linux-hardware.org/?probe=19c7cae23c) | Aug 31, 2022 |
| Acer          | Predator PT516-51s          | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | [ce2bb0938b](https://linux-hardware.org/?probe=ce2bb0938b) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | [61b05137a7](https://linux-hardware.org/?probe=61b05137a7) | Aug 26, 2022 |
| ASUSTek       | T100HAN                     | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [6fcc3e058d](https://linux-hardware.org/?probe=6fcc3e058d) | Aug 22, 2022 |
| Samsung       | 935XDB                      | [a8d4f5e6a0](https://linux-hardware.org/?probe=a8d4f5e6a0) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [87fcf5d702](https://linux-hardware.org/?probe=87fcf5d702) | Aug 19, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | [0271f9018f](https://linux-hardware.org/?probe=0271f9018f) | Aug 19, 2022 |
| HP            | Pavilion g6                 | [ddc9a7396e](https://linux-hardware.org/?probe=ddc9a7396e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | [ef1cbed5a4](https://linux-hardware.org/?probe=ef1cbed5a4) | Aug 16, 2022 |
| Acer          | Aspire ES1-512              | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| Packard Be... | EasyNote TS11HR             | [837159c07a](https://linux-hardware.org/?probe=837159c07a) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| Apple         | MacBookPro11,3              | [1091d27582](https://linux-hardware.org/?probe=1091d27582) | Aug 11, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | [34938e0949](https://linux-hardware.org/?probe=34938e0949) | Aug 11, 2022 |
| Valve         | Jupiter                     | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| Apple         | MacBookPro11,3              | [c530c6e2cb](https://linux-hardware.org/?probe=c530c6e2cb) | Aug 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | [091235281e](https://linux-hardware.org/?probe=091235281e) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | [431684d65c](https://linux-hardware.org/?probe=431684d65c) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [a2733a0f87](https://linux-hardware.org/?probe=a2733a0f87) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Samsung       | 700G7C                      | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| Dell          | Precision 14 5470           | [089d1a151f](https://linux-hardware.org/?probe=089d1a151f) | Aug 03, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [249d407b66](https://linux-hardware.org/?probe=249d407b66) | Jul 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [4fa56bac04](https://linux-hardware.org/?probe=4fa56bac04) | Jul 29, 2022 |
| HP            | ZBook 15 G2                 | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b3df887fe1](https://linux-hardware.org/?probe=b3df887fe1) | Jul 27, 2022 |
| ASUSTek       | ZenBook UX325UA             | [587ea51239](https://linux-hardware.org/?probe=587ea51239) | Jul 26, 2022 |
| Dell          | Precision 7560              | [2fdcece648](https://linux-hardware.org/?probe=2fdcece648) | Jul 25, 2022 |
| Dell          | Precision 7560              | [02fb353f1e](https://linux-hardware.org/?probe=02fb353f1e) | Jul 25, 2022 |
| MSI           | Raider GE76 12UGS           | [65c50de21a](https://linux-hardware.org/?probe=65c50de21a) | Jul 22, 2022 |
| MSI           | Raider GE76 12UGS           | [6dba304ba4](https://linux-hardware.org/?probe=6dba304ba4) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Toshiba       | BLB                         | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Latitude E5450              | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | Precision 7760              | [742cb747ef](https://linux-hardware.org/?probe=742cb747ef) | Jul 20, 2022 |
| ASUSTek       | K52Dr                       | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| Dell          | Precision 3561              | [7dfa6ede1e](https://linux-hardware.org/?probe=7dfa6ede1e) | Jul 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [fb9a47e37f](https://linux-hardware.org/?probe=fb9a47e37f) | Jul 17, 2022 |
| Star Labs     | StarBook                    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| HP            | EliteBook 830 G5            | [235fc9b289](https://linux-hardware.org/?probe=235fc9b289) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [a42efbead1](https://linux-hardware.org/?probe=a42efbead1) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | [8d8610ee4f](https://linux-hardware.org/?probe=8d8610ee4f) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | [4dba0dc5ab](https://linux-hardware.org/?probe=4dba0dc5ab) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [0e13eaa824](https://linux-hardware.org/?probe=0e13eaa824) | Jul 10, 2022 |
| Dell          | Precision 5570              | [e4409961fd](https://linux-hardware.org/?probe=e4409961fd) | Jul 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Valve         | Jupiter                     | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Acer          | Predator PT516-51s          | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [498f4edafb](https://linux-hardware.org/?probe=498f4edafb) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [1264fab131](https://linux-hardware.org/?probe=1264fab131) | Jul 05, 2022 |
| Dell          | Precision M4700             | [fad2fe7297](https://linux-hardware.org/?probe=fad2fe7297) | Jul 04, 2022 |
| Dell          | XPS 15 9520                 | [0cb6549f23](https://linux-hardware.org/?probe=0cb6549f23) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [27343a622f](https://linux-hardware.org/?probe=27343a622f) | Jun 25, 2022 |
| HP            | Pavilion dv7                | [5dd67bc68a](https://linux-hardware.org/?probe=5dd67bc68a) | Jun 25, 2022 |
| ASUSTek       | N61Vn                       | [72d62f755d](https://linux-hardware.org/?probe=72d62f755d) | Jun 24, 2022 |
| HP            | ZBook 15 G2                 | [cfa8a05299](https://linux-hardware.org/?probe=cfa8a05299) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [5188bfb9d3](https://linux-hardware.org/?probe=5188bfb9d3) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [f76be8391b](https://linux-hardware.org/?probe=f76be8391b) | Jun 18, 2022 |
| Apple         | MacBookAir6,2               | [f75b5004f9](https://linux-hardware.org/?probe=f75b5004f9) | Jun 17, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [8153e1c68e](https://linux-hardware.org/?probe=8153e1c68e) | Jun 13, 2022 |
| HP            | EliteBook 830 G6            | [12fb5f93c9](https://linux-hardware.org/?probe=12fb5f93c9) | Jun 13, 2022 |
| Dell          | Precision 7520              | [002f7ce017](https://linux-hardware.org/?probe=002f7ce017) | Jun 12, 2022 |
| HP            | Pavilion g6                 | [63dcba0c57](https://linux-hardware.org/?probe=63dcba0c57) | Jun 10, 2022 |
| Dell          | Vostro 2520                 | [884806d49f](https://linux-hardware.org/?probe=884806d49f) | Jun 09, 2022 |
| Acer          | Aspire 5749Z                | [d7020510e2](https://linux-hardware.org/?probe=d7020510e2) | Jun 08, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [685df41f04](https://linux-hardware.org/?probe=685df41f04) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| Dell          | Latitude D630               | [fb28805860](https://linux-hardware.org/?probe=fb28805860) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | ProBook 6450b               | [52467822a6](https://linux-hardware.org/?probe=52467822a6) | Jun 03, 2022 |
| HP            | ProBook 6450b               | [26bce40d20](https://linux-hardware.org/?probe=26bce40d20) | Jun 01, 2022 |
| Dell          | Latitude E7240              | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Swift SF314-42              | [f4906f3799](https://linux-hardware.org/?probe=f4906f3799) | Jun 01, 2022 |
| Toshiba       | Satellite L50D-B            | [860be26e14](https://linux-hardware.org/?probe=860be26e14) | May 29, 2022 |
| Lenovo        | ThinkPad W500 4061W8H       | [db9160e089](https://linux-hardware.org/?probe=db9160e089) | May 29, 2022 |
| HP            | ProBook 650 G1              | [b32a949b01](https://linux-hardware.org/?probe=b32a949b01) | May 28, 2022 |
| ASUSTek       | U31Jg                       | [b761173e5e](https://linux-hardware.org/?probe=b761173e5e) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| HP            | EliteBook 850 G6            | [25e4d08ac2](https://linux-hardware.org/?probe=25e4d08ac2) | May 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [2d28231751](https://linux-hardware.org/?probe=2d28231751) | May 25, 2022 |
| Apple         | MacBook6,1                  | [683ff3ab1a](https://linux-hardware.org/?probe=683ff3ab1a) | May 24, 2022 |
| Apple         | MacBookAir7,2               | [b620a51628](https://linux-hardware.org/?probe=b620a51628) | May 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| HP            | 635                         | [2421582549](https://linux-hardware.org/?probe=2421582549) | May 21, 2022 |
| Apple         | MacBook6,1                  | [97e7c3fd74](https://linux-hardware.org/?probe=97e7c3fd74) | May 19, 2022 |
| HP            | EliteBook 8460p             | [a1cbc8b911](https://linux-hardware.org/?probe=a1cbc8b911) | May 19, 2022 |
| HP            | EliteBook Folio 1040 G3     | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [736bd1ab68](https://linux-hardware.org/?probe=736bd1ab68) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [6c41f73e8a](https://linux-hardware.org/?probe=6c41f73e8a) | May 18, 2022 |
| HP            | 635                         | [3168b50a90](https://linux-hardware.org/?probe=3168b50a90) | May 18, 2022 |
| Apple         | MacBookPro16,2              | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| MSI           | GS73VR 7RG                  | [3815425b08](https://linux-hardware.org/?probe=3815425b08) | May 15, 2022 |
| Notebook      | NS50_70MU                   | [cff8de13ce](https://linux-hardware.org/?probe=cff8de13ce) | May 12, 2022 |
| Notebook      | NS50_70MU                   | [ebf71be1f5](https://linux-hardware.org/?probe=ebf71be1f5) | May 12, 2022 |
| MSI           | GF63 Thin 9SCSR             | [a80ef1636d](https://linux-hardware.org/?probe=a80ef1636d) | May 12, 2022 |
| ASUSTek       | A6U                         | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [38bc924977](https://linux-hardware.org/?probe=38bc924977) | May 12, 2022 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | [615d6650a0](https://linux-hardware.org/?probe=615d6650a0) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| ASUSTek       | E200HA                      | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| Samsung       | 750XDA                      | [466689475e](https://linux-hardware.org/?probe=466689475e) | May 07, 2022 |
| ASUSTek       | E200HA                      | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Dell          | Precision M4700             | [81cc8ba45c](https://linux-hardware.org/?probe=81cc8ba45c) | May 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [64eb136705](https://linux-hardware.org/?probe=64eb136705) | May 03, 2022 |
| Acer          | Aspire A315-41              | [1bd7f7cd93](https://linux-hardware.org/?probe=1bd7f7cd93) | May 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [f6cc5e2ad5](https://linux-hardware.org/?probe=f6cc5e2ad5) | May 01, 2022 |
| HP            | Pavilion Notebook           | [995ea9538b](https://linux-hardware.org/?probe=995ea9538b) | Apr 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [58076aa8e9](https://linux-hardware.org/?probe=58076aa8e9) | Apr 28, 2022 |
| Dell          | XPS 13 7390                 | [37b195945a](https://linux-hardware.org/?probe=37b195945a) | Apr 28, 2022 |
| Dell          | Latitude 7420               | [8e3bcab404](https://linux-hardware.org/?probe=8e3bcab404) | Apr 28, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [3b4a331875](https://linux-hardware.org/?probe=3b4a331875) | Apr 26, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo        | ThinkPad T450s 20BWS3FX0... | [00d3556f08](https://linux-hardware.org/?probe=00d3556f08) | Apr 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [7988499108](https://linux-hardware.org/?probe=7988499108) | Apr 23, 2022 |
| HP            | EliteBook Folio 9470m       | [cd369fb3e3](https://linux-hardware.org/?probe=cd369fb3e3) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [4548a301f8](https://linux-hardware.org/?probe=4548a301f8) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | [ca406cf975](https://linux-hardware.org/?probe=ca406cf975) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | [32d9d8c8df](https://linux-hardware.org/?probe=32d9d8c8df) | Apr 21, 2022 |
| ASUSTek       | G551JW                      | [b0d7f099f5](https://linux-hardware.org/?probe=b0d7f099f5) | Apr 18, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [7855e19861](https://linux-hardware.org/?probe=7855e19861) | Apr 17, 2022 |
| Acer          | Aspire V3-571               | [5bd64f9988](https://linux-hardware.org/?probe=5bd64f9988) | Apr 17, 2022 |
| Toshiba       | BLB                         | [903779c2b2](https://linux-hardware.org/?probe=903779c2b2) | Apr 16, 2022 |
| Toshiba       | BLB                         | [1dffc347dd](https://linux-hardware.org/?probe=1dffc347dd) | Apr 16, 2022 |
| HP            | ProBook 430 G1              | [c42de00504](https://linux-hardware.org/?probe=c42de00504) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| Dell          | Latitude E7450              | [9af0006104](https://linux-hardware.org/?probe=9af0006104) | Apr 15, 2022 |
| Apple         | MacBookPro11,3              | [b2fdf48a7f](https://linux-hardware.org/?probe=b2fdf48a7f) | Apr 14, 2022 |
| Apple         | MacBookPro11,3              | [ca14d0eb57](https://linux-hardware.org/?probe=ca14d0eb57) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [d9f1aff70a](https://linux-hardware.org/?probe=d9f1aff70a) | Apr 13, 2022 |
| Packard Be... | EasyNote ENTG71BM           | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| ASUSTek       | N56DY                       | [8fdcef45a9](https://linux-hardware.org/?probe=8fdcef45a9) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ce0316a106](https://linux-hardware.org/?probe=ce0316a106) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Apple         | MacBookPro11,3              | [16fa67b6c1](https://linux-hardware.org/?probe=16fa67b6c1) | Apr 07, 2022 |
| Apple         | MacBookPro11,3              | [fca3b357c3](https://linux-hardware.org/?probe=fca3b357c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f4c5281aa9](https://linux-hardware.org/?probe=f4c5281aa9) | Apr 07, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [1c62a4c421](https://linux-hardware.org/?probe=1c62a4c421) | Apr 07, 2022 |
| HP            | EliteBook 8760w             | [e3a9cdfd95](https://linux-hardware.org/?probe=e3a9cdfd95) | Apr 05, 2022 |
| ASUSTek       | UX32VD                      | [31836fcaa9](https://linux-hardware.org/?probe=31836fcaa9) | Apr 05, 2022 |
| Gigabyte      | P65Q                        | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [0b247aa185](https://linux-hardware.org/?probe=0b247aa185) | Mar 30, 2022 |
| Dell          | Precision 5540              | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| Apple         | MacBookPro11,3              | [4e534bb83a](https://linux-hardware.org/?probe=4e534bb83a) | Mar 26, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| HP            | ProBook 430 G1              | [9f295312dc](https://linux-hardware.org/?probe=9f295312dc) | Mar 21, 2022 |
| Dell          | Latitude 7300               | [751dc53e2b](https://linux-hardware.org/?probe=751dc53e2b) | Mar 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| HP            | EliteBook 850 G5            | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| Dell          | Inspiron MP061              | [2b46add19f](https://linux-hardware.org/?probe=2b46add19f) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK E546               | [247dd3e47c](https://linux-hardware.org/?probe=247dd3e47c) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| Lenovo        | Flex 2-15 20405             | [3e4ac3a045](https://linux-hardware.org/?probe=3e4ac3a045) | Mar 07, 2022 |
| HP            | ENVY 15                     | [a4f5eedd3c](https://linux-hardware.org/?probe=a4f5eedd3c) | Mar 06, 2022 |
| ASUSTek       | E205SA                      | [4c896c9379](https://linux-hardware.org/?probe=4c896c9379) | Mar 05, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | [af4563cb12](https://linux-hardware.org/?probe=af4563cb12) | Mar 04, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [88a973e27f](https://linux-hardware.org/?probe=88a973e27f) | Mar 02, 2022 |
| Google        | Rammus                      | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| HP            | ProBook 640 G2              | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| Acer          | Aspire V3-571               | [ff2de5c1da](https://linux-hardware.org/?probe=ff2de5c1da) | Feb 27, 2022 |
| Sony          | VPCEB36FG                   | [d46f784fbb](https://linux-hardware.org/?probe=d46f784fbb) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [cfd0806662](https://linux-hardware.org/?probe=cfd0806662) | Feb 25, 2022 |
| Acer          | Swift SF314-43              | [1434453fc0](https://linux-hardware.org/?probe=1434453fc0) | Feb 24, 2022 |
| Acer          | Swift SF514-52T             | [3bfa40a4c8](https://linux-hardware.org/?probe=3bfa40a4c8) | Feb 24, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| ASUSTek       | G75VW                       | [d31201b74c](https://linux-hardware.org/?probe=d31201b74c) | Feb 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [672f08c769](https://linux-hardware.org/?probe=672f08c769) | Feb 22, 2022 |
| Dell          | Precision 3510              | [3956ab645b](https://linux-hardware.org/?probe=3956ab645b) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [d2119e4516](https://linux-hardware.org/?probe=d2119e4516) | Feb 21, 2022 |
| Unknown       | Unknown                     | [129c8a24d9](https://linux-hardware.org/?probe=129c8a24d9) | Feb 20, 2022 |
| ZEPTO         | ZNOTE                       | [5ff5c2b966](https://linux-hardware.org/?probe=5ff5c2b966) | Feb 20, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7b9e4b097d](https://linux-hardware.org/?probe=7b9e4b097d) | Feb 18, 2022 |
| HP            | Pavilion Gaming Notebook    | [b0cf9aa220](https://linux-hardware.org/?probe=b0cf9aa220) | Feb 18, 2022 |
| HP            | Pavilion dv6                | [012e2b5d56](https://linux-hardware.org/?probe=012e2b5d56) | Feb 15, 2022 |
| Dell          | Latitude 5480               | [62ab6cb2c3](https://linux-hardware.org/?probe=62ab6cb2c3) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| Dell          | Latitude E6430              | [4b91478aaa](https://linux-hardware.org/?probe=4b91478aaa) | Feb 11, 2022 |
| Dell          | Latitude D620               | [dfbcd57dc6](https://linux-hardware.org/?probe=dfbcd57dc6) | Feb 10, 2022 |
| HP            | ENVY 15                     | [91c40a9559](https://linux-hardware.org/?probe=91c40a9559) | Feb 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | [8f36d1baac](https://linux-hardware.org/?probe=8f36d1baac) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | [accf5c8a43](https://linux-hardware.org/?probe=accf5c8a43) | Feb 08, 2022 |
| Lenovo        | E31-70 80KX                 | [d4fe754aa4](https://linux-hardware.org/?probe=d4fe754aa4) | Feb 07, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [2427f8c1da](https://linux-hardware.org/?probe=2427f8c1da) | Feb 07, 2022 |
| Acer          | Swift SF314-43              | [386053c3ce](https://linux-hardware.org/?probe=386053c3ce) | Feb 07, 2022 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [15419beff9](https://linux-hardware.org/?probe=15419beff9) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | [108d91c953](https://linux-hardware.org/?probe=108d91c953) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | [d866cabd88](https://linux-hardware.org/?probe=d866cabd88) | Feb 02, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| ASUSTek       | GR8                         | [1d8f5be27c](https://linux-hardware.org/?probe=1d8f5be27c) | Jan 30, 2022 |
| Apple         | MacBook3,1                  | [a59b4aa98d](https://linux-hardware.org/?probe=a59b4aa98d) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [b584b0b69a](https://linux-hardware.org/?probe=b584b0b69a) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6b771832b8](https://linux-hardware.org/?probe=6b771832b8) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | [1d8bb5fbe6](https://linux-hardware.org/?probe=1d8bb5fbe6) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | [87aa03d881](https://linux-hardware.org/?probe=87aa03d881) | Jan 27, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | [c5c764ccd7](https://linux-hardware.org/?probe=c5c764ccd7) | Jan 24, 2022 |
| Dell          | Latitude E7440              | [74aa958191](https://linux-hardware.org/?probe=74aa958191) | Jan 23, 2022 |
| Notebook      | N13xWU                      | [0d615c6812](https://linux-hardware.org/?probe=0d615c6812) | Jan 22, 2022 |
| Acer          | Swift SF315-41              | [95afa35615](https://linux-hardware.org/?probe=95afa35615) | Jan 22, 2022 |
| Dell          | Inspiron 5721               | [5310b893aa](https://linux-hardware.org/?probe=5310b893aa) | Jan 19, 2022 |
| Dell          | Latitude 7480               | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| Acer          | Aspire ES1-111              | [2dfe5563ef](https://linux-hardware.org/?probe=2dfe5563ef) | Jan 17, 2022 |
| HP            | EliteBook 850 G3            | [35b6de7b5d](https://linux-hardware.org/?probe=35b6de7b5d) | Jan 16, 2022 |
| Dell          | Precision 3561              | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [2e8135c20d](https://linux-hardware.org/?probe=2e8135c20d) | Jan 15, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| Lenovo        | ThinkPad X240 20AMS6170H    | [03fc719875](https://linux-hardware.org/?probe=03fc719875) | Jan 14, 2022 |
| Dell          | Latitude 5290               | [f1c632a454](https://linux-hardware.org/?probe=f1c632a454) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| ASUSTek       | UX310UQ                     | [a9b40e5f8c](https://linux-hardware.org/?probe=a9b40e5f8c) | Jan 10, 2022 |
| Sony          | VPCEB3S1E                   | [6f78e2d423](https://linux-hardware.org/?probe=6f78e2d423) | Jan 07, 2022 |
| Lenovo        | B50-30 80ES                 | [42db32249d](https://linux-hardware.org/?probe=42db32249d) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| HP            | EliteBook 1040 G2           | [ca6f52fbeb](https://linux-hardware.org/?probe=ca6f52fbeb) | Jan 06, 2022 |
| Samsung       | 935XDB                      | [1bb7122515](https://linux-hardware.org/?probe=1bb7122515) | Jan 06, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | B50-30 80ES                 | [649be03cf4](https://linux-hardware.org/?probe=649be03cf4) | Jan 06, 2022 |
| Packard Be... | EasyNote TE69BM             | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| Dell          | XPS 13 9350                 | [492d47c1fa](https://linux-hardware.org/?probe=492d47c1fa) | Jan 04, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| Apple         | MacBookPro11,3              | [4a20cd5429](https://linux-hardware.org/?probe=4a20cd5429) | Jan 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [fbc9c7ad1a](https://linux-hardware.org/?probe=fbc9c7ad1a) | Jan 01, 2022 |
| Samsung       | 905S3G/906S3G/915S3G        | [7a756782d8](https://linux-hardware.org/?probe=7a756782d8) | Dec 31, 2021 |
| ZEPTO         | ZNOTE                       | [f81a927e9b](https://linux-hardware.org/?probe=f81a927e9b) | Dec 31, 2021 |
| Dell          | Precision 5540              | [ba4fef27b9](https://linux-hardware.org/?probe=ba4fef27b9) | Dec 30, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [51d4addbb3](https://linux-hardware.org/?probe=51d4addbb3) | Dec 29, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DM... | [e1ba67fc0f](https://linux-hardware.org/?probe=e1ba67fc0f) | Dec 28, 2021 |
| eMachines     | E525                        | [fd80580005](https://linux-hardware.org/?probe=fd80580005) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| Acer          | AOHAPPY                     | [3a8a8f6b8e](https://linux-hardware.org/?probe=3a8a8f6b8e) | Dec 27, 2021 |
| Acer          | Swift SF314-511             | [3a201fd936](https://linux-hardware.org/?probe=3a201fd936) | Dec 27, 2021 |
| Apple         | MacBook3,1                  | [705810cc40](https://linux-hardware.org/?probe=705810cc40) | Dec 25, 2021 |
| eMachines     | E525                        | [fcc3b2a5e3](https://linux-hardware.org/?probe=fcc3b2a5e3) | Dec 25, 2021 |
| eMachines     | E525                        | [e5853e5629](https://linux-hardware.org/?probe=e5853e5629) | Dec 25, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | [edad019098](https://linux-hardware.org/?probe=edad019098) | Dec 23, 2021 |
| HP            | EliteBook Folio 9470m       | [9dd62bbf73](https://linux-hardware.org/?probe=9dd62bbf73) | Dec 23, 2021 |
| Toshiba       | Satellite L50D-B            | [b5a9d0b1dc](https://linux-hardware.org/?probe=b5a9d0b1dc) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Packard Be... | EasyNote TE69HW             | [c6876b9023](https://linux-hardware.org/?probe=c6876b9023) | Dec 20, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [3fea1de018](https://linux-hardware.org/?probe=3fea1de018) | Dec 20, 2021 |
| eMachines     | E525                        | [bcb03ff38c](https://linux-hardware.org/?probe=bcb03ff38c) | Dec 20, 2021 |
| MSI           | Katana GF66 11UE            | [36aea8dc19](https://linux-hardware.org/?probe=36aea8dc19) | Dec 18, 2021 |
| Dell          | Precision 5540              | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| MSI           | Katana GF66 11UE            | [56be528067](https://linux-hardware.org/?probe=56be528067) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | [38d349f99c](https://linux-hardware.org/?probe=38d349f99c) | Dec 15, 2021 |
| Dell          | Latitude E6400              | [2936dcb6ab](https://linux-hardware.org/?probe=2936dcb6ab) | Dec 14, 2021 |
| Acer          | Nitro AN515-45              | [d4bed6e3e7](https://linux-hardware.org/?probe=d4bed6e3e7) | Dec 14, 2021 |
| Dell          | Latitude E7450              | [f5f9fd93f9](https://linux-hardware.org/?probe=f5f9fd93f9) | Dec 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0V400    | [77c3ba8640](https://linux-hardware.org/?probe=77c3ba8640) | Dec 09, 2021 |
| Dell          | Precision 5560              | [2af841d052](https://linux-hardware.org/?probe=2af841d052) | Dec 07, 2021 |
| Dell          | Precision 5560              | [aeba66f4d6](https://linux-hardware.org/?probe=aeba66f4d6) | Dec 07, 2021 |
| HP            | Pavilion dv6                | [479a9e57d5](https://linux-hardware.org/?probe=479a9e57d5) | Dec 07, 2021 |
| HP            | Pavilion dv6                | [98ad56ddcc](https://linux-hardware.org/?probe=98ad56ddcc) | Dec 07, 2021 |
| Lenovo        | B50-70 80EU                 | [80d04f078e](https://linux-hardware.org/?probe=80d04f078e) | Dec 07, 2021 |
| HP            | Compaq CQ58                 | [a859413f86](https://linux-hardware.org/?probe=a859413f86) | Dec 05, 2021 |
| Apple         | MacBookPro14,3              | [b08702eb1e](https://linux-hardware.org/?probe=b08702eb1e) | Dec 05, 2021 |
| HUAWEI        | VLT-WX0                     | [3e01a8673d](https://linux-hardware.org/?probe=3e01a8673d) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| Dell          | XPS 13 9310                 | [fa0051b73b](https://linux-hardware.org/?probe=fa0051b73b) | Dec 02, 2021 |
| Apple         | MacBookPro14,3              | [a7366c8449](https://linux-hardware.org/?probe=a7366c8449) | Dec 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | [fa59cc1ea9](https://linux-hardware.org/?probe=fa59cc1ea9) | Dec 01, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [5f2264a472](https://linux-hardware.org/?probe=5f2264a472) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [af8104b01a](https://linux-hardware.org/?probe=af8104b01a) | Nov 30, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | [66f2018614](https://linux-hardware.org/?probe=66f2018614) | Nov 30, 2021 |
| Toshiba       | Satellite C50-A-19U         | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Acer          | Predator PT315-51           | [b37881e828](https://linux-hardware.org/?probe=b37881e828) | Nov 29, 2021 |
| HP            | EliteBook 8460p             | [56f6b7ec0a](https://linux-hardware.org/?probe=56f6b7ec0a) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a74aec830e](https://linux-hardware.org/?probe=a74aec830e) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [af530bb7c7](https://linux-hardware.org/?probe=af530bb7c7) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [19f2a1dd2f](https://linux-hardware.org/?probe=19f2a1dd2f) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [90f2d59148](https://linux-hardware.org/?probe=90f2d59148) | Nov 26, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7ac3b720be](https://linux-hardware.org/?probe=7ac3b720be) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Apple         | MacBookPro10,1              | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| HP            | Pavilion Notebook           | [ee309c7776](https://linux-hardware.org/?probe=ee309c7776) | Nov 23, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [0f39f8f706](https://linux-hardware.org/?probe=0f39f8f706) | Nov 22, 2021 |
| Dell          | XPS 13 9370                 | [9f8a07614e](https://linux-hardware.org/?probe=9f8a07614e) | Nov 21, 2021 |
| ASUSTek       | K53U                        | [12136b1cbd](https://linux-hardware.org/?probe=12136b1cbd) | Nov 20, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [2c0279ade5](https://linux-hardware.org/?probe=2c0279ade5) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [5a5b8c420f](https://linux-hardware.org/?probe=5a5b8c420f) | Nov 20, 2021 |
| Dell          | Latitude E5570              | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Google        | Edgar                       | [0c4bb072e0](https://linux-hardware.org/?probe=0c4bb072e0) | Nov 16, 2021 |
| HP            | ProBook 6450b               | [943ef75a8b](https://linux-hardware.org/?probe=943ef75a8b) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| Lenovo        | B50-10 80QR                 | [cb474c37e6](https://linux-hardware.org/?probe=cb474c37e6) | Nov 15, 2021 |
| Lenovo        | ThinkPad 25 20K70000MX      | [86d3ea8b6a](https://linux-hardware.org/?probe=86d3ea8b6a) | Nov 15, 2021 |
| Google        | Edgar                       | [9cb0616971](https://linux-hardware.org/?probe=9cb0616971) | Nov 15, 2021 |
| HP            | Pavilion g7                 | [dbdeebfe86](https://linux-hardware.org/?probe=dbdeebfe86) | Nov 14, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| ASUSTek       | N550JK                      | [23fd9d7d0d](https://linux-hardware.org/?probe=23fd9d7d0d) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Sony          | VPCCA2S1E                   | [2ce8a8295b](https://linux-hardware.org/?probe=2ce8a8295b) | Nov 05, 2021 |
| HP            | ProBook 640 G1              | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| Google        | Grunt                       | [e6c7c07304](https://linux-hardware.org/?probe=e6c7c07304) | Nov 04, 2021 |
| HP            | ZBook 15 G6                 | [36b8c3bedd](https://linux-hardware.org/?probe=36b8c3bedd) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480 20L50009MX    | [349faf5242](https://linux-hardware.org/?probe=349faf5242) | Nov 03, 2021 |
| On by NetO... | LT1.1 BRZ                   | [a520593d47](https://linux-hardware.org/?probe=a520593d47) | Nov 02, 2021 |
| On by NetO... | LT1.1 BRZ                   | [f9312f99c7](https://linux-hardware.org/?probe=f9312f99c7) | Nov 02, 2021 |
| Unknown       | Unknown                     | [ae9e2708e9](https://linux-hardware.org/?probe=ae9e2708e9) | Nov 02, 2021 |
| HP            | Laptop 15-bw0xx             | [1869db225e](https://linux-hardware.org/?probe=1869db225e) | Nov 02, 2021 |
| HP            | ZBook 14 G2                 | [ffb40f821b](https://linux-hardware.org/?probe=ffb40f821b) | Oct 30, 2021 |
| Sony          | VGN-CS31S_W                 | [13451dd6c5](https://linux-hardware.org/?probe=13451dd6c5) | Oct 30, 2021 |
| HP            | ProBook 430 G1              | [15d9329bd3](https://linux-hardware.org/?probe=15d9329bd3) | Oct 28, 2021 |
| ASUSTek       | T100HAN                     | [c518746ece](https://linux-hardware.org/?probe=c518746ece) | Oct 25, 2021 |
| ASUSTek       | T100HAN                     | [5f27dd2f45](https://linux-hardware.org/?probe=5f27dd2f45) | Oct 25, 2021 |
| Acer          | Nitro AN515-45              | [f6ddc3a2da](https://linux-hardware.org/?probe=f6ddc3a2da) | Oct 24, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e9991e486b](https://linux-hardware.org/?probe=e9991e486b) | Oct 23, 2021 |
| Unknown       | Unknown                     | [470c0932ae](https://linux-hardware.org/?probe=470c0932ae) | Oct 23, 2021 |
| Acer          | Aspire V3-772G              | [10e7ffc71d](https://linux-hardware.org/?probe=10e7ffc71d) | Oct 19, 2021 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [2e44d637e3](https://linux-hardware.org/?probe=2e44d637e3) | Oct 16, 2021 |
| Dell          | Latitude E5250              | [793091ac6a](https://linux-hardware.org/?probe=793091ac6a) | Oct 14, 2021 |
| Google        | Treeya                      | [82b0964b6d](https://linux-hardware.org/?probe=82b0964b6d) | Oct 14, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [c3cdfe0336](https://linux-hardware.org/?probe=c3cdfe0336) | Oct 14, 2021 |
| HP            | EliteBook 830 G6            | [66a9b21300](https://linux-hardware.org/?probe=66a9b21300) | Oct 14, 2021 |
| Google        | Treeya                      | [6c10b9bcb3](https://linux-hardware.org/?probe=6c10b9bcb3) | Oct 14, 2021 |
| ASUSTek       | TP201SA                     | [504956d2e9](https://linux-hardware.org/?probe=504956d2e9) | Oct 13, 2021 |
| eMachines     | G730                        | [6450ba7397](https://linux-hardware.org/?probe=6450ba7397) | Oct 12, 2021 |
| eMachines     | G730                        | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| Apple         | MacBookAir7,2               | [31ae42bc51](https://linux-hardware.org/?probe=31ae42bc51) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | [5b47e8efcb](https://linux-hardware.org/?probe=5b47e8efcb) | Oct 09, 2021 |
| ASUSTek       | X550LB                      | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| HP            | EliteBook 830 G6            | [28ecb03df2](https://linux-hardware.org/?probe=28ecb03df2) | Oct 05, 2021 |
| Dell          | Latitude 5290               | [e3afd1ef97](https://linux-hardware.org/?probe=e3afd1ef97) | Oct 04, 2021 |
| HP            | ProBook 430 G1              | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Dell          | Precision M6800             | [b85ad62146](https://linux-hardware.org/?probe=b85ad62146) | Oct 03, 2021 |
| Dell          | Precision M6800             | [61a932607b](https://linux-hardware.org/?probe=61a932607b) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [46db33820d](https://linux-hardware.org/?probe=46db33820d) | Oct 03, 2021 |
| Lenovo        | G50-80 80E5                 | [133b546e7f](https://linux-hardware.org/?probe=133b546e7f) | Oct 03, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [9c3c1f9a85](https://linux-hardware.org/?probe=9c3c1f9a85) | Oct 01, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6876f0e86d](https://linux-hardware.org/?probe=6876f0e86d) | Sep 29, 2021 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [4a91c75662](https://linux-hardware.org/?probe=4a91c75662) | Sep 28, 2021 |
| HP            | EliteBook 830 G6            | [72c41f4a85](https://linux-hardware.org/?probe=72c41f4a85) | Sep 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [560598d6fb](https://linux-hardware.org/?probe=560598d6fb) | Sep 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | [2460060920](https://linux-hardware.org/?probe=2460060920) | Sep 25, 2021 |
| HP            | Laptop 15s-eq2xxx           | [639131ddd5](https://linux-hardware.org/?probe=639131ddd5) | Sep 25, 2021 |
| ASUSTek       | GL553VE                     | [c55708bb3f](https://linux-hardware.org/?probe=c55708bb3f) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [df7ff85482](https://linux-hardware.org/?probe=df7ff85482) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [36c78f1667](https://linux-hardware.org/?probe=36c78f1667) | Sep 23, 2021 |
| HP            | Presario CQ62               | [dc91fe3b30](https://linux-hardware.org/?probe=dc91fe3b30) | Sep 22, 2021 |
| Apple         | MacBookAir7,2               | [83f3d6df86](https://linux-hardware.org/?probe=83f3d6df86) | Sep 21, 2021 |
| Apple         | MacBookPro8,1               | [5b337fdb0a](https://linux-hardware.org/?probe=5b337fdb0a) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | [439f4b690a](https://linux-hardware.org/?probe=439f4b690a) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | [a9edf67742](https://linux-hardware.org/?probe=a9edf67742) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [7c806aa7c5](https://linux-hardware.org/?probe=7c806aa7c5) | Sep 19, 2021 |
| Dell          | Latitude E7450              | [f5963dc359](https://linux-hardware.org/?probe=f5963dc359) | Sep 18, 2021 |
| Dell          | Precision 7720              | [80f3d1e3b0](https://linux-hardware.org/?probe=80f3d1e3b0) | Sep 17, 2021 |
| Dell          | Latitude 5290               | [baae3812d5](https://linux-hardware.org/?probe=baae3812d5) | Sep 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [dc1b85b8c9](https://linux-hardware.org/?probe=dc1b85b8c9) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| HP            | EliteBook 820 G1            | [9631d6f9e1](https://linux-hardware.org/?probe=9631d6f9e1) | Sep 14, 2021 |
| Acer          | Swift SF314-511             | [4286a4710c](https://linux-hardware.org/?probe=4286a4710c) | Sep 11, 2021 |
| Acer          | Swift SF114-33              | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Toshiba       | Satellite L50D-B            | [6eb7be93e9](https://linux-hardware.org/?probe=6eb7be93e9) | Sep 10, 2021 |
| HP            | ProBook 6460b               | [b0f0eaf216](https://linux-hardware.org/?probe=b0f0eaf216) | Sep 09, 2021 |
| HP            | ZBook 17 G3                 | [7e85c2791f](https://linux-hardware.org/?probe=7e85c2791f) | Sep 07, 2021 |
| HP            | ProBook 4540s               | [41d764faaf](https://linux-hardware.org/?probe=41d764faaf) | Sep 06, 2021 |
| PC Special... | N150CU                      | [2fd6f4b53c](https://linux-hardware.org/?probe=2fd6f4b53c) | Sep 05, 2021 |
| HP            | ProBook 6450b               | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d40a00437d](https://linux-hardware.org/?probe=d40a00437d) | Aug 30, 2021 |
| Lenovo        | B51-80 80LM                 | [a81c83bd1c](https://linux-hardware.org/?probe=a81c83bd1c) | Aug 30, 2021 |
| Acer          | Aspire E5-573G              | [78ad2b6854](https://linux-hardware.org/?probe=78ad2b6854) | Aug 27, 2021 |
| Lenovo        | ThinkPad T420s 4174FM9      | [12fd92046e](https://linux-hardware.org/?probe=12fd92046e) | Aug 27, 2021 |
| ASUSTek       | X510UAR                     | [cd238d180b](https://linux-hardware.org/?probe=cd238d180b) | Aug 23, 2021 |
| Toshiba       | Satellite L50D-B            | [1e514cb947](https://linux-hardware.org/?probe=1e514cb947) | Aug 23, 2021 |
| Dell          | Inspiron 7520               | [a8e8ae384a](https://linux-hardware.org/?probe=a8e8ae384a) | Aug 20, 2021 |
| Dell          | XPS 15 9500                 | [6d76e9c22e](https://linux-hardware.org/?probe=6d76e9c22e) | Aug 18, 2021 |
| PC Special... | Standard                    | [b7baa43d24](https://linux-hardware.org/?probe=b7baa43d24) | Aug 18, 2021 |
| MSI           | GP63 Leopard 8RE            | [40a8ec3a95](https://linux-hardware.org/?probe=40a8ec3a95) | Aug 16, 2021 |
| Razer         | Blade                       | [b6bad1f725](https://linux-hardware.org/?probe=b6bad1f725) | Aug 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [77c51b6b7b](https://linux-hardware.org/?probe=77c51b6b7b) | Aug 15, 2021 |
| HP            | Pavilion 17                 | [b628f70687](https://linux-hardware.org/?probe=b628f70687) | Aug 15, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3DK1... | [695ac6427d](https://linux-hardware.org/?probe=695ac6427d) | Aug 15, 2021 |
| HP            | Compaq nc6320 (EV073AV)     | [bf6050f750](https://linux-hardware.org/?probe=bf6050f750) | Aug 14, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Lenovo        | Z50-70 20354                | [1eba114602](https://linux-hardware.org/?probe=1eba114602) | Aug 11, 2021 |
| Lenovo        | Z50-70 20354                | [a31c1f0fda](https://linux-hardware.org/?probe=a31c1f0fda) | Aug 11, 2021 |
| Dell          | Inspiron ME051              | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| Lenovo        | Z50-70 20354                | [c1209f4d40](https://linux-hardware.org/?probe=c1209f4d40) | Aug 09, 2021 |
| Dell          | Precision M4500             | [d7b650fecf](https://linux-hardware.org/?probe=d7b650fecf) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| Dell          | XPS 15 7590                 | [1778263a70](https://linux-hardware.org/?probe=1778263a70) | Aug 08, 2021 |
| Lenovo        | Z50-70 20354                | [9e08265168](https://linux-hardware.org/?probe=9e08265168) | Aug 08, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| Dell          | Latitude E6400              | [dea83da57d](https://linux-hardware.org/?probe=dea83da57d) | Aug 04, 2021 |
| Packard Be... | EasyNote TS11SB             | [aa9468a3de](https://linux-hardware.org/?probe=aa9468a3de) | Aug 03, 2021 |
| Packard Be... | EasyNote TS11SB             | [57fbaedb1e](https://linux-hardware.org/?probe=57fbaedb1e) | Aug 03, 2021 |
| HP            | Elite x2 1012 G1            | [7c2abb5f03](https://linux-hardware.org/?probe=7c2abb5f03) | Aug 02, 2021 |
| HP            | Pavilion 15                 | [08bd4b9549](https://linux-hardware.org/?probe=08bd4b9549) | Aug 02, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [5cacc2c659](https://linux-hardware.org/?probe=5cacc2c659) | Jul 29, 2021 |
| Toshiba       | Satellite L750              | [822adc34c6](https://linux-hardware.org/?probe=822adc34c6) | Jul 28, 2021 |
| HP            | ProBook 6460b               | [ad2986d747](https://linux-hardware.org/?probe=ad2986d747) | Jul 26, 2021 |
| HP            | Pavilion dv6500             | [896e1bc2a0](https://linux-hardware.org/?probe=896e1bc2a0) | Jul 25, 2021 |
| HP            | Pavilion dv6500             | [1325b6d6c2](https://linux-hardware.org/?probe=1325b6d6c2) | Jul 25, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [ed51414a9d](https://linux-hardware.org/?probe=ed51414a9d) | Jul 22, 2021 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | [64c8fe4e52](https://linux-hardware.org/?probe=64c8fe4e52) | Jul 20, 2021 |
| Dell          | Vostro 3500                 | [2e8c9fa212](https://linux-hardware.org/?probe=2e8c9fa212) | Jul 18, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Intel Clie... | LAPBC710                    | [49a2ccdeee](https://linux-hardware.org/?probe=49a2ccdeee) | Jul 12, 2021 |
| HP            | Pavilion 15                 | [b4eeb3105e](https://linux-hardware.org/?probe=b4eeb3105e) | Jul 12, 2021 |
| HP            | Pavilion dv6                | [bb0f20f7a9](https://linux-hardware.org/?probe=bb0f20f7a9) | Jul 10, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [8845d0216e](https://linux-hardware.org/?probe=8845d0216e) | Jul 09, 2021 |
| HP            | Elite x2 1012 G1            | [4d5cea91ad](https://linux-hardware.org/?probe=4d5cea91ad) | Jul 07, 2021 |
| HP            | EliteBook 8470p             | [505684a737](https://linux-hardware.org/?probe=505684a737) | Jul 07, 2021 |
| Apple         | MacBookPro11,5              | [43d77edd56](https://linux-hardware.org/?probe=43d77edd56) | Jul 01, 2021 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | [c0ba9a0437](https://linux-hardware.org/?probe=c0ba9a0437) | Jun 30, 2021 |
| Apple         | MacBookPro11,5              | [103c0edcbd](https://linux-hardware.org/?probe=103c0edcbd) | Jun 30, 2021 |
| Lenovo        | ThinkPad T460 20FMS06105    | [242cf25827](https://linux-hardware.org/?probe=242cf25827) | Jun 29, 2021 |
| Lenovo        | ThinkPad X201 3626FAG       | [259908557b](https://linux-hardware.org/?probe=259908557b) | Jun 28, 2021 |
| Toshiba       | Satellite L855              | [45df91892a](https://linux-hardware.org/?probe=45df91892a) | Jun 27, 2021 |
| Toshiba       | Satellite L855              | [5fc995dac3](https://linux-hardware.org/?probe=5fc995dac3) | Jun 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [392be37a79](https://linux-hardware.org/?probe=392be37a79) | Jun 25, 2021 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [6995133402](https://linux-hardware.org/?probe=6995133402) | Jun 24, 2021 |
| Lenovo        | B50-30 80ES                 | [b9d0b5be2d](https://linux-hardware.org/?probe=b9d0b5be2d) | Jun 23, 2021 |
| ASUSTek       | ROG Strix G731GW_G731GW     | [85a0c7c512](https://linux-hardware.org/?probe=85a0c7c512) | Jun 23, 2021 |
| Lenovo        | B50-30 80ES                 | [e2b40afe3c](https://linux-hardware.org/?probe=e2b40afe3c) | Jun 23, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [e4ba771332](https://linux-hardware.org/?probe=e4ba771332) | Jun 22, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [495c04a536](https://linux-hardware.org/?probe=495c04a536) | Jun 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c1abf6c844](https://linux-hardware.org/?probe=c1abf6c844) | Jun 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [aa95a9d75f](https://linux-hardware.org/?probe=aa95a9d75f) | Jun 20, 2021 |
| Lenovo        | IdeaPadFlex 15 20309        | [7a60f78b32](https://linux-hardware.org/?probe=7a60f78b32) | Jun 17, 2021 |
| HP            | ZBook 17 G2                 | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP            | EliteBook 725 G3            | [f57f7d1e53](https://linux-hardware.org/?probe=f57f7d1e53) | Jun 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [0e1e07507e](https://linux-hardware.org/?probe=0e1e07507e) | Jun 15, 2021 |
| Dell          | Latitude 3350               | [7fe0552d03](https://linux-hardware.org/?probe=7fe0552d03) | Jun 14, 2021 |
| Dell          | XPS 17 9700                 | [293537d794](https://linux-hardware.org/?probe=293537d794) | Jun 11, 2021 |
| HP            | ZBook 17 G2                 | [05a2ecf3ec](https://linux-hardware.org/?probe=05a2ecf3ec) | Jun 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [48bda0fbd3](https://linux-hardware.org/?probe=48bda0fbd3) | Jun 09, 2021 |
| Lenovo        | ThinkPad X201 4492W36       | [f309552e6e](https://linux-hardware.org/?probe=f309552e6e) | Jun 07, 2021 |
| Sony          | VPCCA2S1E                   | [6b20cf032f](https://linux-hardware.org/?probe=6b20cf032f) | Jun 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [117372a8ff](https://linux-hardware.org/?probe=117372a8ff) | Jun 05, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [6946ffb375](https://linux-hardware.org/?probe=6946ffb375) | Jun 03, 2021 |
| Dell          | Latitude 9520               | [10a4c770cf](https://linux-hardware.org/?probe=10a4c770cf) | Jun 02, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [d8507e3c64](https://linux-hardware.org/?probe=d8507e3c64) | Jun 01, 2021 |
| Apple         | MacBookPro12,1              | [f7f5736b13](https://linux-hardware.org/?probe=f7f5736b13) | Jun 01, 2021 |
| HP            | EliteBook Revolve 810       | [24758ed5b3](https://linux-hardware.org/?probe=24758ed5b3) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cad013a6a5](https://linux-hardware.org/?probe=cad013a6a5) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [af407b12e2](https://linux-hardware.org/?probe=af407b12e2) | May 29, 2021 |
| HP            | EliteBook Folio 9470m       | [8c36612ff4](https://linux-hardware.org/?probe=8c36612ff4) | May 26, 2021 |
| HP            | ZBook 17 G2                 | [5e10971a64](https://linux-hardware.org/?probe=5e10971a64) | May 25, 2021 |
| Apple         | MacBookPro6,1               | [a0012821b7](https://linux-hardware.org/?probe=a0012821b7) | May 25, 2021 |
| Dell          | Latitude D520               | [7a817a0426](https://linux-hardware.org/?probe=7a817a0426) | May 25, 2021 |
| HP            | EliteBook Revolve 810 G3    | [e0068ae9b7](https://linux-hardware.org/?probe=e0068ae9b7) | May 23, 2021 |
| PC Special... | N150CU                      | [eebe654729](https://linux-hardware.org/?probe=eebe654729) | May 22, 2021 |
| PC Special... | N150CU                      | [99d75e799f](https://linux-hardware.org/?probe=99d75e799f) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [d5ea76578b](https://linux-hardware.org/?probe=d5ea76578b) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [0ccd96a39e](https://linux-hardware.org/?probe=0ccd96a39e) | May 21, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [828f345230](https://linux-hardware.org/?probe=828f345230) | May 19, 2021 |
| Dell          | Precision 5540              | [91e4aff19e](https://linux-hardware.org/?probe=91e4aff19e) | May 17, 2021 |
| Dell          | Latitude 3350               | [f4e6b7cf7f](https://linux-hardware.org/?probe=f4e6b7cf7f) | May 15, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ae6af1c7e1](https://linux-hardware.org/?probe=ae6af1c7e1) | May 14, 2021 |
| HP            | EliteBook 850 G3            | [cb589a4d2c](https://linux-hardware.org/?probe=cb589a4d2c) | May 14, 2021 |
| HP            | EliteBook 850 G3            | [00a23f1149](https://linux-hardware.org/?probe=00a23f1149) | May 14, 2021 |
| Dell          | Latitude 3350               | [bb64b2df5c](https://linux-hardware.org/?probe=bb64b2df5c) | May 13, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [461ae5a890](https://linux-hardware.org/?probe=461ae5a890) | May 08, 2021 |
| HP            | EliteBook 850 G3            | [85a71e335a](https://linux-hardware.org/?probe=85a71e335a) | May 06, 2021 |
| Dell          | XPS 13 9310                 | [5103d9a329](https://linux-hardware.org/?probe=5103d9a329) | May 06, 2021 |
| Dell          | XPS 13 9310                 | [951fb73d61](https://linux-hardware.org/?probe=951fb73d61) | May 06, 2021 |
| Apple         | MacBookPro14,1              | [f1b3020464](https://linux-hardware.org/?probe=f1b3020464) | May 03, 2021 |
| ASUSTek       | X502CA                      | [6763e02e82](https://linux-hardware.org/?probe=6763e02e82) | Apr 30, 2021 |
| Dell          | XPS 17 9700                 | [02dae8d8ba](https://linux-hardware.org/?probe=02dae8d8ba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | [0d0db8039c](https://linux-hardware.org/?probe=0d0db8039c) | Apr 24, 2021 |
| HP            | Compaq 6730s                | [31fa38668e](https://linux-hardware.org/?probe=31fa38668e) | Apr 23, 2021 |
| HP            | Compaq 6730s                | [ad60afcbe6](https://linux-hardware.org/?probe=ad60afcbe6) | Apr 23, 2021 |
| HP            | ProBook 430 G2              | [03a0b4cf9d](https://linux-hardware.org/?probe=03a0b4cf9d) | Apr 22, 2021 |
| HP            | ProBook 430 G2              | [9f9065affa](https://linux-hardware.org/?probe=9f9065affa) | Apr 22, 2021 |
| HP            | Pavilion dv8000 (EW858EA... | [b64833b0b1](https://linux-hardware.org/?probe=b64833b0b1) | Apr 21, 2021 |
| HP            | Pavilion dv8000 (EW858EA... | [e378a38500](https://linux-hardware.org/?probe=e378a38500) | Apr 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9f3189e59c](https://linux-hardware.org/?probe=9f3189e59c) | Apr 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [644309ff4c](https://linux-hardware.org/?probe=644309ff4c) | Apr 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2e1606428e](https://linux-hardware.org/?probe=2e1606428e) | Apr 19, 2021 |
| Dell          | XPS 13 9343                 | [fd2c114081](https://linux-hardware.org/?probe=fd2c114081) | Apr 19, 2021 |
| Dell          | XPS 13 9343                 | [2d99520074](https://linux-hardware.org/?probe=2d99520074) | Apr 19, 2021 |
| Dell          | XPS 17 9700                 | [84387a75f7](https://linux-hardware.org/?probe=84387a75f7) | Apr 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [5d66639b00](https://linux-hardware.org/?probe=5d66639b00) | Apr 17, 2021 |
| Toshiba       | Satellite A300              | [37b42247f5](https://linux-hardware.org/?probe=37b42247f5) | Apr 17, 2021 |
| Toshiba       | Satellite A300              | [d0c0ba115d](https://linux-hardware.org/?probe=d0c0ba115d) | Apr 17, 2021 |
| Dell          | Latitude D520               | [4e8b58ab28](https://linux-hardware.org/?probe=4e8b58ab28) | Apr 16, 2021 |
| ASUSTek       | N53SN                       | [97b4a56f7d](https://linux-hardware.org/?probe=97b4a56f7d) | Apr 16, 2021 |
| Dell          | Precision 3551              | [4e9b5b097e](https://linux-hardware.org/?probe=4e9b5b097e) | Apr 15, 2021 |
| Dell          | Precision 5540              | [a171f512e1](https://linux-hardware.org/?probe=a171f512e1) | Apr 14, 2021 |
| ASUSTek       | G751JY                      | [914c959acf](https://linux-hardware.org/?probe=914c959acf) | Apr 13, 2021 |
| Acer          | Aspire 5560                 | [bc4d7942f2](https://linux-hardware.org/?probe=bc4d7942f2) | Apr 13, 2021 |
| Acer          | Aspire 5560                 | [c01ef90ff1](https://linux-hardware.org/?probe=c01ef90ff1) | Apr 13, 2021 |
| Lenovo        | ThinkPad X390 20Q00056MX    | [377be16b54](https://linux-hardware.org/?probe=377be16b54) | Apr 13, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [8ed94ed92f](https://linux-hardware.org/?probe=8ed94ed92f) | Apr 12, 2021 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | [6a307c820d](https://linux-hardware.org/?probe=6a307c820d) | Apr 12, 2021 |
| Dell          | XPS 15 9560                 | [6dd46ebb68](https://linux-hardware.org/?probe=6dd46ebb68) | Apr 11, 2021 |
| Dell          | Latitude 3350               | [347c1e4246](https://linux-hardware.org/?probe=347c1e4246) | Apr 11, 2021 |
| Lenovo        | ThinkPad W541 20EF000UMN    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| Dell          | Precision 7740              | [e00242182c](https://linux-hardware.org/?probe=e00242182c) | Apr 10, 2021 |
| Dell          | Precision 7740              | [5b18086d86](https://linux-hardware.org/?probe=5b18086d86) | Apr 10, 2021 |
| ASUSTek       | 1008HA                      | [efa68e1607](https://linux-hardware.org/?probe=efa68e1607) | Apr 09, 2021 |
| Apple         | MacBookPro9,2               | [8fe0fefb60](https://linux-hardware.org/?probe=8fe0fefb60) | Apr 09, 2021 |
| HP            | EliteBook 2740p             | [6604ebcf44](https://linux-hardware.org/?probe=6604ebcf44) | Apr 09, 2021 |
| HP            | Compaq 6730b (NN204ET#AK... | [3d9460ecd7](https://linux-hardware.org/?probe=3d9460ecd7) | Apr 08, 2021 |
| Lenovo        | B575e 36852EG               | [494789235b](https://linux-hardware.org/?probe=494789235b) | Apr 08, 2021 |
| Acer          | Aspire VN7-793G             | [881e9bb0dd](https://linux-hardware.org/?probe=881e9bb0dd) | Apr 06, 2021 |
| Acer          | Aspire VN7-793G             | [cd805ae4e6](https://linux-hardware.org/?probe=cd805ae4e6) | Apr 06, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [9c7afa6f8c](https://linux-hardware.org/?probe=9c7afa6f8c) | Apr 06, 2021 |
| ASUSTek       | 1008HA                      | [8819e810d5](https://linux-hardware.org/?probe=8819e810d5) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | [9bb8d87d34](https://linux-hardware.org/?probe=9bb8d87d34) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | [1e04362858](https://linux-hardware.org/?probe=1e04362858) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | [4c92681db0](https://linux-hardware.org/?probe=4c92681db0) | Apr 05, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [6a799a77de](https://linux-hardware.org/?probe=6a799a77de) | Apr 05, 2021 |
| Dell          | Latitude E6430              | [cef48a7c98](https://linux-hardware.org/?probe=cef48a7c98) | Apr 05, 2021 |
| Lenovo        | ThinkPad 11e 3rd Gen 20G... | [d8320bacb4](https://linux-hardware.org/?probe=d8320bacb4) | Apr 05, 2021 |
| Dell          | Latitude E6430              | [8e76a74a21](https://linux-hardware.org/?probe=8e76a74a21) | Apr 04, 2021 |
| ASUSTek       | 1008HA                      | [1045f8543a](https://linux-hardware.org/?probe=1045f8543a) | Apr 04, 2021 |
| Lenovo        | ThinkPad E580 20KS001QMX    | [28b80e551f](https://linux-hardware.org/?probe=28b80e551f) | Apr 04, 2021 |
| HP            | Laptop 17-ca1xxx            | [e21ac181a5](https://linux-hardware.org/?probe=e21ac181a5) | Apr 03, 2021 |
| Dell          | Precision 7540              | [9ad15db73f](https://linux-hardware.org/?probe=9ad15db73f) | Apr 02, 2021 |
| Apple         | MacBookPro8,1               | [6632391038](https://linux-hardware.org/?probe=6632391038) | Apr 02, 2021 |
| Dell          | XPS 15 9560                 | [dd4081dc68](https://linux-hardware.org/?probe=dd4081dc68) | Apr 02, 2021 |
| ASUSTek       | U32U                        | [2842f61fc9](https://linux-hardware.org/?probe=2842f61fc9) | Apr 02, 2021 |
| PC Special... | N150CU                      | [f0729cc9bf](https://linux-hardware.org/?probe=f0729cc9bf) | Apr 01, 2021 |
| PC Special... | N150CU                      | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| Dell          | Latitude 3350               | [9e3b1f256c](https://linux-hardware.org/?probe=9e3b1f256c) | Apr 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS1WW0X    | [1f98cf2913](https://linux-hardware.org/?probe=1f98cf2913) | Mar 31, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [286287736b](https://linux-hardware.org/?probe=286287736b) | Mar 31, 2021 |
| Gigabyte      | AERO 15-SA                  | [26957c118d](https://linux-hardware.org/?probe=26957c118d) | Mar 30, 2021 |
| Dell          | Latitude E6430              | [5989458f51](https://linux-hardware.org/?probe=5989458f51) | Mar 29, 2021 |
| HP            | ProBook 4540s               | [6999b29045](https://linux-hardware.org/?probe=6999b29045) | Mar 29, 2021 |
| HP            | ProBook 440 G5              | [6c5ee38371](https://linux-hardware.org/?probe=6c5ee38371) | Mar 27, 2021 |
| Acer          | Aspire E5-575G              | [d96f9a5cd5](https://linux-hardware.org/?probe=d96f9a5cd5) | Mar 27, 2021 |
| Lenovo        | ThinkPad T430s 2356DH2      | [86d756fb89](https://linux-hardware.org/?probe=86d756fb89) | Mar 27, 2021 |
| HP            | ProBook 440 G5              | [46ffef3efa](https://linux-hardware.org/?probe=46ffef3efa) | Mar 27, 2021 |
| Dell          | XPS 15 7590                 | [6727afc25e](https://linux-hardware.org/?probe=6727afc25e) | Mar 25, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [57162c4f3e](https://linux-hardware.org/?probe=57162c4f3e) | Mar 24, 2021 |
| Lenovo        | ThinkPad T420 4180AZ5       | [4b39173927](https://linux-hardware.org/?probe=4b39173927) | Mar 23, 2021 |
| HP            | ProBook 4540s               | [3eebedc4c6](https://linux-hardware.org/?probe=3eebedc4c6) | Mar 23, 2021 |
| HP            | ProBook 4540s               | [96a4aad39a](https://linux-hardware.org/?probe=96a4aad39a) | Mar 23, 2021 |
| HP            | Laptop 15-da1xxx            | [3a2dc8930d](https://linux-hardware.org/?probe=3a2dc8930d) | Mar 22, 2021 |
| Dell          | Precision 7540              | [b5273482f4](https://linux-hardware.org/?probe=b5273482f4) | Mar 21, 2021 |
| Dell          | Vostro 15-3568              | [2c8acbf86c](https://linux-hardware.org/?probe=2c8acbf86c) | Mar 21, 2021 |
| ASUSTek       | X555LD                      | [90646a2169](https://linux-hardware.org/?probe=90646a2169) | Mar 20, 2021 |
| Acer          | Aspire 5742G                | [da8880b543](https://linux-hardware.org/?probe=da8880b543) | Mar 19, 2021 |
| Acer          | Aspire 5742G                | [047a34bb2c](https://linux-hardware.org/?probe=047a34bb2c) | Mar 19, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f991500c35](https://linux-hardware.org/?probe=f991500c35) | Mar 18, 2021 |
| Dell          | Latitude E4310              | [edbe42639c](https://linux-hardware.org/?probe=edbe42639c) | Mar 17, 2021 |
| HP            | EliteBook Folio 9470m       | [30efdef045](https://linux-hardware.org/?probe=30efdef045) | Mar 15, 2021 |
| HP            | EliteBook 2570p             | [3bf2664982](https://linux-hardware.org/?probe=3bf2664982) | Mar 14, 2021 |
| ASUSTek       | X580VD                      | [968d9a1d18](https://linux-hardware.org/?probe=968d9a1d18) | Mar 14, 2021 |
| ASUSTek       | X580VD                      | [e10f767f8d](https://linux-hardware.org/?probe=e10f767f8d) | Mar 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [44775f7ea2](https://linux-hardware.org/?probe=44775f7ea2) | Mar 12, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [5d7090421a](https://linux-hardware.org/?probe=5d7090421a) | Mar 12, 2021 |
| MSI           | GX60 1AC                    | [774db4f685](https://linux-hardware.org/?probe=774db4f685) | Mar 12, 2021 |
| HP            | EliteBook 840 G2            | [e90e4463c7](https://linux-hardware.org/?probe=e90e4463c7) | Mar 11, 2021 |
| HP            | Compaq 8710w                | [2b1ffee1d7](https://linux-hardware.org/?probe=2b1ffee1d7) | Mar 11, 2021 |
| Acer          | AOD255E                     | [cacd668025](https://linux-hardware.org/?probe=cacd668025) | Mar 10, 2021 |
| PC Special... | N150CU                      | [50a23abcf2](https://linux-hardware.org/?probe=50a23abcf2) | Mar 09, 2021 |
| Dell          | Precision 5540              | [e3aca0cdf9](https://linux-hardware.org/?probe=e3aca0cdf9) | Mar 09, 2021 |
| Dell          | Latitude E7250              | [76aeabfc6d](https://linux-hardware.org/?probe=76aeabfc6d) | Mar 07, 2021 |
| Dell          | XPS 13 9310                 | [5754ce9311](https://linux-hardware.org/?probe=5754ce9311) | Mar 02, 2021 |
| HP            | Laptop 17-ca1xxx            | [a8a82ba1b9](https://linux-hardware.org/?probe=a8a82ba1b9) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK U745               | [2acf51105b](https://linux-hardware.org/?probe=2acf51105b) | Feb 28, 2021 |
| Intel         | SLIMBOOK                    | [36bbd7056a](https://linux-hardware.org/?probe=36bbd7056a) | Feb 28, 2021 |
| Dell          | Latitude E7450              | [dfb4275179](https://linux-hardware.org/?probe=dfb4275179) | Feb 28, 2021 |
| HP            | EliteBook Folio 9470m       | [b9cfaac7a6](https://linux-hardware.org/?probe=b9cfaac7a6) | Feb 27, 2021 |
| ASUSTek       | X202EV                      | [1c1369ff15](https://linux-hardware.org/?probe=1c1369ff15) | Feb 25, 2021 |
| HP            | EliteBook 830 G5            | [65135f4810](https://linux-hardware.org/?probe=65135f4810) | Feb 24, 2021 |
| HP            | EliteBook 820 G2            | [50dcf0521d](https://linux-hardware.org/?probe=50dcf0521d) | Feb 24, 2021 |
| Lenovo        | ThinkPad L590 20Q8S75F01    | [ae827c1e6b](https://linux-hardware.org/?probe=ae827c1e6b) | Feb 24, 2021 |
| Dell          | Precision M4800             | [744b7bc3a5](https://linux-hardware.org/?probe=744b7bc3a5) | Feb 23, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [a05ca7a665](https://linux-hardware.org/?probe=a05ca7a665) | Feb 23, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [2009ef0f7f](https://linux-hardware.org/?probe=2009ef0f7f) | Feb 23, 2021 |
| HP            | EliteBook 2570p             | [f3e1294a65](https://linux-hardware.org/?probe=f3e1294a65) | Feb 23, 2021 |
| Dell          | Latitude E6540              | [550d35b65b](https://linux-hardware.org/?probe=550d35b65b) | Feb 20, 2021 |
| HP            | ProBook 4330s               | [01954b26a9](https://linux-hardware.org/?probe=01954b26a9) | Feb 20, 2021 |
| ASUSTek       | UX430UQ                     | [3dce65d104](https://linux-hardware.org/?probe=3dce65d104) | Feb 19, 2021 |
| ASUSTek       | UX430UQ                     | [11cebb071c](https://linux-hardware.org/?probe=11cebb071c) | Feb 19, 2021 |
| Sony          | VPCF23C5E                   | [fdfa46f36e](https://linux-hardware.org/?probe=fdfa46f36e) | Feb 19, 2021 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [fe2c72978e](https://linux-hardware.org/?probe=fe2c72978e) | Feb 19, 2021 |
| Lenovo        | ThinkPad L590 20Q8S75F01    | [39d098054a](https://linux-hardware.org/?probe=39d098054a) | Feb 18, 2021 |
| Dell          | Vostro 3500                 | [bd2b4fae3a](https://linux-hardware.org/?probe=bd2b4fae3a) | Feb 18, 2021 |
| Dell          | Latitude 5480               | [41472dbe02](https://linux-hardware.org/?probe=41472dbe02) | Feb 18, 2021 |
| HP            | Compaq 6510b (GB867ET#AK... | [c9c18dfdeb](https://linux-hardware.org/?probe=c9c18dfdeb) | Feb 16, 2021 |
| Acer          | Aspire 5750G                | [84855d9ab6](https://linux-hardware.org/?probe=84855d9ab6) | Feb 14, 2021 |
| BOX           | W54_W94_W955TU,-T,-C        | [45730a0879](https://linux-hardware.org/?probe=45730a0879) | Feb 14, 2021 |
| HP            | Pavilion Notebook           | [065510eb37](https://linux-hardware.org/?probe=065510eb37) | Feb 13, 2021 |
| Lenovo        | ThinkPad Edge E530c 3366... | [e34430353c](https://linux-hardware.org/?probe=e34430353c) | Feb 13, 2021 |
| ASUSTek       | K70IO                       | [4912792c07](https://linux-hardware.org/?probe=4912792c07) | Feb 13, 2021 |
| PC Special... | N150CU                      | [9400902b39](https://linux-hardware.org/?probe=9400902b39) | Feb 13, 2021 |
| HP            | ProBook 640 G1              | [3b37587b81](https://linux-hardware.org/?probe=3b37587b81) | Feb 12, 2021 |
| HP            | ZBook 15                    | [dc1d23b1c6](https://linux-hardware.org/?probe=dc1d23b1c6) | Feb 12, 2021 |
| Acer          | Aspire 5750G                | [4d8c753a43](https://linux-hardware.org/?probe=4d8c753a43) | Feb 09, 2021 |
| HP            | ENVY Notebook               | [c951e2abbd](https://linux-hardware.org/?probe=c951e2abbd) | Feb 07, 2021 |
| Notebook      | N2x0WU                      | [e660e0f0da](https://linux-hardware.org/?probe=e660e0f0da) | Feb 05, 2021 |
| ASUSTek       | G75VW                       | [9fc5da433d](https://linux-hardware.org/?probe=9fc5da433d) | Feb 05, 2021 |
| ASUSTek       | ZenBook 13 UX331UAL         | [918139e56e](https://linux-hardware.org/?probe=918139e56e) | Feb 05, 2021 |
| Lenovo        | ThinkPad E520 11438NG       | [3dcd713cd1](https://linux-hardware.org/?probe=3dcd713cd1) | Feb 05, 2021 |
| Dell          | XPS 13 9310                 | [948271ba61](https://linux-hardware.org/?probe=948271ba61) | Feb 05, 2021 |
| ASUSTek       | UX430UAR                    | [65e796cdaf](https://linux-hardware.org/?probe=65e796cdaf) | Feb 04, 2021 |
| HP            | EliteBook 8440p             | [024180fc49](https://linux-hardware.org/?probe=024180fc49) | Feb 03, 2021 |
| System76      | Galago UltraPro             | [ba1c44690a](https://linux-hardware.org/?probe=ba1c44690a) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e746534229](https://linux-hardware.org/?probe=e746534229) | Feb 01, 2021 |
| HP            | EliteBook 8440p             | [32ea31202d](https://linux-hardware.org/?probe=32ea31202d) | Feb 01, 2021 |
| Dell          | Precision 5550              | [61de611018](https://linux-hardware.org/?probe=61de611018) | Jan 29, 2021 |
| Dell          | Precision 7720              | [c99e4945f6](https://linux-hardware.org/?probe=c99e4945f6) | Jan 29, 2021 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | [19aa307625](https://linux-hardware.org/?probe=19aa307625) | Jan 29, 2021 |
| Notebook      | N350TW                      | [8f873c01cb](https://linux-hardware.org/?probe=8f873c01cb) | Jan 28, 2021 |
| Apple         | MacBookAir7,2               | [cf6599a35b](https://linux-hardware.org/?probe=cf6599a35b) | Jan 27, 2021 |
| ASUSTek       | X550LB                      | [427d6af239](https://linux-hardware.org/?probe=427d6af239) | Jan 25, 2021 |
| ASUSTek       | X550LB                      | [a6a84e8eb2](https://linux-hardware.org/?probe=a6a84e8eb2) | Jan 24, 2021 |
| HP            | EliteBook 8570p             | [a2536bd6fe](https://linux-hardware.org/?probe=a2536bd6fe) | Jan 23, 2021 |
| ASUSTek       | TP300LA                     | [890339ddee](https://linux-hardware.org/?probe=890339ddee) | Jan 22, 2021 |
| Toshiba       | Satellite Pro C50-A-1EK     | [b2b20ad037](https://linux-hardware.org/?probe=b2b20ad037) | Jan 21, 2021 |
| Toshiba       | Satellite Pro C50-A-1EK     | [8718991f34](https://linux-hardware.org/?probe=8718991f34) | Jan 21, 2021 |
| Toshiba       | Satellite Pro C50-A-1EK     | [67a92e99d9](https://linux-hardware.org/?probe=67a92e99d9) | Jan 21, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [fa99318483](https://linux-hardware.org/?probe=fa99318483) | Jan 21, 2021 |
| Acer          | Aspire V5-561G              | [41a988bc1c](https://linux-hardware.org/?probe=41a988bc1c) | Jan 17, 2021 |
| HP            | EliteBook 2560p             | [92cd0842ee](https://linux-hardware.org/?probe=92cd0842ee) | Jan 15, 2021 |
| Dell          | Vostro 3500                 | [efa4546342](https://linux-hardware.org/?probe=efa4546342) | Jan 14, 2021 |
| ASUSTek       | N53SN                       | [a0fd8f8b91](https://linux-hardware.org/?probe=a0fd8f8b91) | Jan 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [929b0edb33](https://linux-hardware.org/?probe=929b0edb33) | Jan 11, 2021 |
| HP            | EliteBook 2570p             | [731a3aef2a](https://linux-hardware.org/?probe=731a3aef2a) | Jan 10, 2021 |
| Lenovo        | ThinkPad T460 20FN004CMX    | [0f6a89ef2c](https://linux-hardware.org/?probe=0f6a89ef2c) | Jan 10, 2021 |
| Alienware     | 13 R3                       | [d3e331e671](https://linux-hardware.org/?probe=d3e331e671) | Jan 10, 2021 |
| ASUSTek       | TP300LA                     | [67fa6528dc](https://linux-hardware.org/?probe=67fa6528dc) | Jan 09, 2021 |
| HP            | EliteBook 2570p             | [68910248cd](https://linux-hardware.org/?probe=68910248cd) | Jan 09, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Sweden/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 141       | 12.94%  |
| Ubuntu 18.04                 | 74        | 6.79%   |
| Ubuntu 22.04                 | 66        | 6.06%   |
| Debian 11                    | 32        | 2.94%   |
| Pop!_OS 22.04                | 24        | 2.2%    |
| Pop!_OS 21.04                | 22        | 2.02%   |
| OpenMandriva 4.3             | 21        | 1.93%   |
| OpenMandriva 4.2             | 21        | 1.93%   |
| Manjaro                      | 21        | 1.93%   |
| Arch                         | 21        | 1.93%   |
| Arch Rolling                 | 20        | 1.83%   |
| Ubuntu 19.04                 | 19        | 1.74%   |
| Fedora 35                    | 19        | 1.74%   |
| Zorin 16                     | 18        | 1.65%   |
| Linux Mint 21.1              | 17        | 1.56%   |
| Debian 12                    | 17        | 1.56%   |
| Ubuntu 21.10                 | 16        | 1.47%   |
| Pop!_OS 20.10                | 16        | 1.47%   |
| Pop!_OS 20.04                | 16        | 1.47%   |
| Zorin 15                     | 15        | 1.38%   |
| KDE neon 20.04               | 15        | 1.38%   |
| Linux Mint 20.2              | 14        | 1.28%   |
| Fedora 37                    | 14        | 1.28%   |
| Ubuntu 19.10                 | 13        | 1.19%   |
| Linux Mint 20.3              | 13        | 1.19%   |
| ArcoLinux Rolling            | 13        | 1.19%   |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 1.1%    |
| Linux Mint 20.1              | 12        | 1.1%    |
| Fedora 34                    | 12        | 1.1%    |
| Ubuntu 21.04                 | 11        | 1.01%   |
| Ubuntu 20.10                 | 10        | 0.92%   |
| Fedora 36                    | 10        | 0.92%   |
| Pop!_OS 21.10                | 9         | 0.83%   |
| Fedora 33                    | 9         | 0.83%   |
| Linux Mint 20                | 8         | 0.73%   |
| Linux Mint 19.3              | 8         | 0.73%   |
| Xubuntu 20.04                | 7         | 0.64%   |
| Ubuntu 18.10                 | 7         | 0.64%   |
| Fedora 32                    | 7         | 0.64%   |
| Ubuntu 22.10                 | 6         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 352       | 33.65%  |
| Pop!_OS       | 84        | 8.03%   |
| Linux Mint    | 84        | 8.03%   |
| Fedora        | 84        | 8.03%   |
| Debian        | 61        | 5.83%   |
| OpenMandriva  | 55        | 5.26%   |
| Manjaro       | 40        | 3.82%   |
| Arch          | 40        | 3.82%   |
| Zorin         | 33        | 3.15%   |
| KDE neon      | 21        | 2.01%   |
| Xubuntu       | 18        | 1.72%   |
| ArcoLinux     | 16        | 1.53%   |
| Kubuntu       | 15        | 1.43%   |
| openSUSE      | 13        | 1.24%   |
| Kali          | 12        | 1.15%   |
| Gentoo        | 11        | 1.05%   |
| Endless       | 9         | 0.86%   |
| Ubuntu MATE   | 8         | 0.76%   |
| ROSA          | 7         | 0.67%   |
| EndeavourOS   | 7         | 0.67%   |
| SteamOS       | 6         | 0.57%   |
| Elementary    | 6         | 0.57%   |
| CentOS        | 6         | 0.57%   |
| Peppermint    | 4         | 0.38%   |
| Parrot        | 4         | 0.38%   |
| LMDE          | 4         | 0.38%   |
| BunsenLabs    | 4         | 0.38%   |
| BlackPanther  | 4         | 0.38%   |
| Ubuntu Unity  | 3         | 0.29%   |
| Ubuntu Budgie | 3         | 0.29%   |
| Nobara        | 3         | 0.29%   |
| Lubuntu       | 3         | 0.29%   |
| Slackware     | 2         | 0.19%   |
| MX            | 2         | 0.19%   |
| Garuda Linux  | 2         | 0.19%   |
| Clear Linux   | 2         | 0.19%   |
| Chrome OS     | 2         | 0.19%   |
| Xero          | 1         | 0.1%    |
| Solus         | 1         | 0.1%    |
| Siduction     | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 21        | 1.77%   |
| 5.16.7-desktop-1omv4003  | 20        | 1.69%   |
| 5.15.0-56-generic        | 19        | 1.6%    |
| 5.4.0-42-generic         | 18        | 1.52%   |
| 5.4.0-58-generic         | 12        | 1.01%   |
| 5.4.0-48-generic         | 12        | 1.01%   |
| 5.15.0-52-generic        | 12        | 1.01%   |
| 5.3.0-40-generic         | 10        | 0.84%   |
| 5.13.0-30-generic        | 10        | 0.84%   |
| 6.1.0-7-amd64            | 9         | 0.76%   |
| 5.4.0-52-generic         | 9         | 0.76%   |
| 5.4.0-40-generic         | 9         | 0.76%   |
| 5.15.0-60-generic        | 9         | 0.76%   |
| 5.11.0-37-generic        | 9         | 0.76%   |
| 5.8.0-48-generic         | 8         | 0.67%   |
| 5.15.0-48-generic        | 8         | 0.67%   |
| 5.13.0-7614-generic      | 8         | 0.67%   |
| 5.4.0-70-generic         | 7         | 0.59%   |
| 5.4.0-65-generic         | 7         | 0.59%   |
| 5.19.0-35-generic        | 7         | 0.59%   |
| 5.13.0-39-generic        | 7         | 0.59%   |
| 5.10.0-8-amd64           | 7         | 0.59%   |
| 5.10.0-21-amd64          | 7         | 0.59%   |
| 4.15.0-47-generic        | 7         | 0.59%   |
| 6.1.0-9-amd64            | 6         | 0.51%   |
| 5.8.0-7630-generic       | 6         | 0.51%   |
| 5.4.0-7634-generic       | 6         | 0.51%   |
| 5.4.0-66-generic         | 6         | 0.51%   |
| 5.4.0-54-generic         | 6         | 0.51%   |
| 5.4.0-33-generic         | 6         | 0.51%   |
| 5.3.0-51-generic         | 6         | 0.51%   |
| 5.3.0-28-generic         | 6         | 0.51%   |
| 5.15.0-50-generic        | 6         | 0.51%   |
| 5.11.0-41-generic        | 6         | 0.51%   |
| 6.0.12-76060006-generic  | 5         | 0.42%   |
| 5.4.0-56-generic         | 5         | 0.42%   |
| 5.4.0-37-generic         | 5         | 0.42%   |
| 5.4.0-29-generic         | 5         | 0.42%   |
| 5.15.0-58-generic        | 5         | 0.42%   |
| 5.15.0-47-generic        | 5         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 174       | 15.54%  |
| 5.15.0  | 100       | 8.93%   |
| 5.11.0  | 66        | 5.89%   |
| 5.13.0  | 63        | 5.63%   |
| 5.8.0   | 51        | 4.55%   |
| 5.3.0   | 46        | 4.11%   |
| 5.10.0  | 45        | 4.02%   |
| 4.15.0  | 45        | 4.02%   |
| 5.0.0   | 34        | 3.04%   |
| 5.19.0  | 26        | 2.32%   |
| 6.1.0   | 25        | 2.23%   |
| 4.18.0  | 23        | 2.05%   |
| 5.16.7  | 21        | 1.88%   |
| 5.10.14 | 21        | 1.88%   |
| 5.17.5  | 7         | 0.63%   |
| 5.14.0  | 7         | 0.63%   |
| 6.2.6   | 6         | 0.54%   |
| 6.2.0   | 6         | 0.54%   |
| 6.1.1   | 6         | 0.54%   |
| 6.0.12  | 6         | 0.54%   |
| 5.16.0  | 6         | 0.54%   |
| 5.7.0   | 5         | 0.45%   |
| 5.18.0  | 5         | 0.45%   |
| 6.2.8   | 4         | 0.36%   |
| 6.2.7   | 4         | 0.36%   |
| 6.1.9   | 4         | 0.36%   |
| 6.0.8   | 4         | 0.36%   |
| 5.17.1  | 4         | 0.36%   |
| 5.16.2  | 4         | 0.36%   |
| 5.16.15 | 4         | 0.36%   |
| 5.15.5  | 4         | 0.36%   |
| 5.15.15 | 4         | 0.36%   |
| 4.18.16 | 4         | 0.36%   |
| 6.2.9   | 3         | 0.27%   |
| 6.2.11  | 3         | 0.27%   |
| 6.1.11  | 3         | 0.27%   |
| 6.0.6   | 3         | 0.27%   |
| 6.0.15  | 3         | 0.27%   |
| 5.9.14  | 3         | 0.27%   |
| 5.5.8   | 3         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 181       | 16.42%  |
| 5.15    | 131       | 11.89%  |
| 5.10    | 82        | 7.44%   |
| 5.11    | 78        | 7.08%   |
| 5.13    | 73        | 6.62%   |
| 5.8     | 63        | 5.72%   |
| 5.3     | 52        | 4.72%   |
| 6.1     | 47        | 4.26%   |
| 5.16    | 47        | 4.26%   |
| 4.15    | 45        | 4.08%   |
| 5.0     | 36        | 3.27%   |
| 5.19    | 33        | 2.99%   |
| 6.2     | 31        | 2.81%   |
| 4.18    | 29        | 2.63%   |
| 6.0     | 25        | 2.27%   |
| 5.18    | 20        | 1.81%   |
| 5.17    | 20        | 1.81%   |
| 5.14    | 18        | 1.63%   |
| 5.9     | 14        | 1.27%   |
| 5.12    | 14        | 1.27%   |
| 5.7     | 11        | 1%      |
| 5.6     | 11        | 1%      |
| 4.19    | 8         | 0.73%   |
| 5.5     | 7         | 0.64%   |
| 5.2     | 6         | 0.54%   |
| 6.3     | 5         | 0.45%   |
| 4.9     | 5         | 0.45%   |
| 5.1     | 4         | 0.36%   |
| 4.1     | 2         | 0.18%   |
| 6.4     | 1         | 0.09%   |
| 4.20    | 1         | 0.09%   |
| 4.14    | 1         | 0.09%   |
| 3.10    | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 990       | 98.61%  |
| i686   | 14        | 1.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 525       | 50.05%  |
| KDE5            | 131       | 12.49%  |
| Unknown         | 129       | 12.3%   |
| XFCE            | 73        | 6.96%   |
| X-Cinnamon      | 71        | 6.77%   |
| KDE             | 29        | 2.76%   |
| MATE            | 24        | 2.29%   |
| i3              | 11        | 1.05%   |
| Cinnamon        | 10        | 0.95%   |
| LXQt            | 7         | 0.67%   |
| Pantheon        | 6         | 0.57%   |
| LXDE            | 5         | 0.48%   |
| Unity           | 3         | 0.29%   |
| sway            | 3         | 0.29%   |
| KDE4            | 3         | 0.29%   |
| Budgie          | 3         | 0.29%   |
| awesome         | 3         | 0.29%   |
| qtile           | 2         | 0.19%   |
| GNOME Flashback | 2         | 0.19%   |
| DWM             | 2         | 0.19%   |
| Deepin          | 2         | 0.19%   |
| Trinity         | 1         | 0.1%    |
| spectrwm        | 1         | 0.1%    |
| LeftWM          | 1         | 0.1%    |
| BunsenLabs      | 1         | 0.1%    |
| bspwm           | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 747       | 72.38%  |
| Wayland | 194       | 18.8%   |
| Unknown | 73        | 7.07%   |
| Tty     | 18        | 1.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 538       | 51.48%  |
| GDM3    | 131       | 12.54%  |
| GDM     | 129       | 12.34%  |
| SDDM    | 122       | 11.67%  |
| LightDM | 88        | 8.42%   |
| TDM     | 28        | 2.68%   |
| XDM     | 3         | 0.29%   |
| KDM     | 3         | 0.29%   |
| LXDM    | 2         | 0.19%   |
| Ly      | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 502       | 48.64%  |
| sv_SE      | 282       | 27.33%  |
| Unknown    | 119       | 11.53%  |
| en_GB      | 61        | 5.91%   |
| C          | 12        | 1.16%   |
| de_DE      | 8         | 0.78%   |
| ru_RU      | 7         | 0.68%   |
| pl_PL      | 6         | 0.58%   |
| en_SE      | 5         | 0.48%   |
| fr_FR      | 3         | 0.29%   |
| en_DK      | 3         | 0.29%   |
| lt_LT      | 2         | 0.19%   |
| it_IT      | 2         | 0.19%   |
| en_CA      | 2         | 0.19%   |
| el_GR      | 2         | 0.19%   |
| zh_CN      | 1         | 0.1%    |
| uk_UA      | 1         | 0.1%    |
| sv_SE.UTF8 | 1         | 0.1%    |
| sv_FI      | 1         | 0.1%    |
| POSIX      | 1         | 0.1%    |
| nn_NO      | 1         | 0.1%    |
| nb_NO      | 1         | 0.1%    |
| hu_HU      | 1         | 0.1%    |
| gl_ES      | 1         | 0.1%    |
| fi_FI      | 1         | 0.1%    |
| es_ES      | 1         | 0.1%    |
| en_IE      | 1         | 0.1%    |
| en_AU      | 1         | 0.1%    |
| en_AG      | 1         | 0.1%    |
| C.UTF8     | 1         | 0.1%    |
| bg_BG      | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 551       | 53.5%   |
| BIOS | 479       | 46.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 784       | 76.19%  |
| Btrfs   | 102       | 9.91%   |
| Overlay | 64        | 6.22%   |
| Unknown | 31        | 3.01%   |
| Xfs     | 13        | 1.26%   |
| Zfs     | 12        | 1.17%   |
| Tmpfs   | 12        | 1.17%   |
| Ext2    | 6         | 0.58%   |
| F2fs    | 3         | 0.29%   |
| XXXXXXX | 1         | 0.1%    |
| Ext3    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 554       | 53.89%  |
| GPT     | 390       | 37.94%  |
| MBR     | 84        | 8.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 925       | 91.04%  |
| Yes       | 91        | 8.96%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 823       | 81.08%  |
| Yes       | 192       | 18.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 238       | 23.71%  |
| Hewlett-Packard      | 211       | 21.02%  |
| Dell                 | 156       | 15.54%  |
| ASUSTek Computer     | 129       | 12.85%  |
| Acer                 | 69        | 6.87%   |
| Apple                | 42        | 4.18%   |
| MSI                  | 21        | 2.09%   |
| Toshiba              | 16        | 1.59%   |
| Sony                 | 15        | 1.49%   |
| Samsung Electronics  | 10        | 1%      |
| Packard Bell         | 10        | 1%      |
| Google               | 9         | 0.9%    |
| Notebook             | 8         | 0.8%    |
| Fujitsu              | 8         | 0.8%    |
| Valve                | 6         | 0.6%    |
| Unknown              | 6         | 0.6%    |
| HUAWEI               | 4         | 0.4%    |
| Fujitsu Siemens      | 4         | 0.4%    |
| TUXEDO               | 3         | 0.3%    |
| Star Labs            | 3         | 0.3%    |
| Timi                 | 2         | 0.2%    |
| Schenker             | 2         | 0.2%    |
| Razer                | 2         | 0.2%    |
| PC Specialist        | 2         | 0.2%    |
| LG Electronics       | 2         | 0.2%    |
| Gigabyte Technology  | 2         | 0.2%    |
| eMachines            | 2         | 0.2%    |
| Dynabook             | 2         | 0.2%    |
| Clevo                | 2         | 0.2%    |
| Alienware            | 2         | 0.2%    |
| ZEPTO                | 1         | 0.1%    |
| YJKC                 | 1         | 0.1%    |
| System76             | 1         | 0.1%    |
| SLIMBOOK             | 1         | 0.1%    |
| Purism               | 1         | 0.1%    |
| On by NetOnNet       | 1         | 0.1%    |
| Intel Client Systems | 1         | 0.1%    |
| Intel                | 1         | 0.1%    |
| Insyde               | 1         | 0.1%    |
| GPD                  | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 8         | 0.8%    |
| Dell XPS 13 9370                           | 7         | 0.7%    |
| Valve Jupiter                              | 6         | 0.6%    |
| HP EliteBook Folio 9470m                   | 6         | 0.6%    |
| Dell Precision 5540                        | 6         | 0.6%    |
| Apple MacBookPro9,2                        | 6         | 0.6%    |
| HP ProBook 640 G1                          | 5         | 0.5%    |
| HP Pavilion dv7                            | 5         | 0.5%    |
| HP Pavilion 15                             | 5         | 0.5%    |
| HP EliteBook 840 G3                        | 5         | 0.5%    |
| HP EliteBook 840 G2                        | 5         | 0.5%    |
| Dell XPS 13 9310                           | 5         | 0.5%    |
| Apple MacBookPro11,3                       | 5         | 0.5%    |
| Acer Aspire V3-571                         | 5         | 0.5%    |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX       | 4         | 0.4%    |
| Lenovo ThinkPad L13 Gen 2 20VJS6RY00       | 4         | 0.4%    |
| HP EliteBook 840 G6                        | 4         | 0.4%    |
| HP EliteBook 830 G6                        | 4         | 0.4%    |
| Dell XPS 15 9570                           | 4         | 0.4%    |
| Dell XPS 15 9500                           | 4         | 0.4%    |
| Apple MacBookPro8,1                        | 4         | 0.4%    |
| Apple MacBookPro12,1                       | 4         | 0.4%    |
| Apple MacBookAir7,2                        | 4         | 0.4%    |
| Lenovo Z50-70 20354                        | 3         | 0.3%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW005NMX | 3         | 0.3%    |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5           | 3         | 0.3%    |
| HUAWEI KLVL-WXX9                           | 3         | 0.3%    |
| HP ZBook 15 G2                             | 3         | 0.3%    |
| HP ProBook 430 G1                          | 3         | 0.3%    |
| HP Pavilion Notebook                       | 3         | 0.3%    |
| HP Pavilion g6                             | 3         | 0.3%    |
| HP Pavilion dv6                            | 3         | 0.3%    |
| HP Pavilion 17                             | 3         | 0.3%    |
| HP Laptop 15-db0xxx                        | 3         | 0.3%    |
| HP ENVY 15                                 | 3         | 0.3%    |
| HP EliteBook 8570p                         | 3         | 0.3%    |
| HP EliteBook 8440p                         | 3         | 0.3%    |
| HP EliteBook 840 G1                        | 3         | 0.3%    |
| Dell XPS 15 9560                           | 3         | 0.3%    |
| Dell XPS 15 7590                           | 3         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 156       | 15.54%  |
| HP EliteBook          | 79        | 7.87%   |
| Dell Latitude         | 59        | 5.88%   |
| Acer Aspire           | 47        | 4.68%   |
| Dell XPS              | 43        | 4.28%   |
| Dell Precision        | 38        | 3.78%   |
| HP ProBook            | 35        | 3.49%   |
| Lenovo IdeaPad        | 34        | 3.39%   |
| HP Pavilion           | 34        | 3.39%   |
| ASUS VivoBook         | 17        | 1.69%   |
| HP ZBook              | 16        | 1.59%   |
| ASUS ROG              | 16        | 1.59%   |
| HP Laptop             | 15        | 1.49%   |
| Toshiba Satellite     | 14        | 1.39%   |
| HP Compaq             | 12        | 1.2%    |
| ASUS ZenBook          | 11        | 1.1%    |
| Acer Swift            | 10        | 1%      |
| Packard Bell EasyNote | 9         | 0.9%    |
| Lenovo Legion         | 9         | 0.9%    |
| Lenovo Yoga           | 8         | 0.8%    |
| Dell Inspiron         | 8         | 0.8%    |
| Unknown               | 8         | 0.8%    |
| HP ENVY               | 7         | 0.7%    |
| Fujitsu LIFEBOOK      | 7         | 0.7%    |
| Dell Vostro           | 7         | 0.7%    |
| Valve Jupiter         | 6         | 0.6%    |
| Apple MacBookPro9     | 6         | 0.6%    |
| Apple MacBookPro11    | 6         | 0.6%    |
| ASUS ASUS             | 5         | 0.5%    |
| Acer Nitro            | 5         | 0.5%    |
| ASUS TUF              | 4         | 0.4%    |
| Apple MacBookPro8     | 4         | 0.4%    |
| Apple MacBookPro12    | 4         | 0.4%    |
| Apple MacBookAir7     | 4         | 0.4%    |
| Acer Predator         | 4         | 0.4%    |
| MSI Katana            | 3         | 0.3%    |
| MSI GF63              | 3         | 0.3%    |
| Lenovo Z50-70         | 3         | 0.3%    |
| HUAWEI KLVL-WXX9      | 3         | 0.3%    |
| HP Presario           | 3         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 92        | 9.16%   |
| 2019 | 92        | 9.16%   |
| 2013 | 90        | 8.96%   |
| 2018 | 88        | 8.76%   |
| 2020 | 82        | 8.17%   |
| 2012 | 76        | 7.57%   |
| 2011 | 69        | 6.87%   |
| 2015 | 67        | 6.67%   |
| 2017 | 66        | 6.57%   |
| 2014 | 57        | 5.68%   |
| 2016 | 55        | 5.48%   |
| 2010 | 49        | 4.88%   |
| 2022 | 36        | 3.59%   |
| 2008 | 30        | 2.99%   |
| 2007 | 20        | 1.99%   |
| 2009 | 19        | 1.89%   |
| 2006 | 7         | 0.7%    |
| 2005 | 5         | 0.5%    |
| 2023 | 4         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1004      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 877       | 86.66%  |
| Enabled  | 135       | 13.34%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 992       | 98.8%   |
| Yes  | 12        | 1.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 288       | 28.4%   |
| 16.01-24.0  | 201       | 19.82%  |
| 8.01-16.0   | 182       | 17.95%  |
| 3.01-4.0    | 169       | 16.67%  |
| 32.01-64.0  | 109       | 10.75%  |
| 1.01-2.0    | 31        | 3.06%   |
| 24.01-32.0  | 13        | 1.28%   |
| 2.01-3.0    | 8         | 0.79%   |
| 64.01-256.0 | 8         | 0.79%   |
| 0.51-1.0    | 5         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 380       | 34.45%  |
| 2.01-3.0   | 285       | 25.84%  |
| 4.01-8.0   | 175       | 15.87%  |
| 3.01-4.0   | 151       | 13.69%  |
| 0.51-1.0   | 51        | 4.62%   |
| 8.01-16.0  | 40        | 3.63%   |
| 0.01-0.5   | 11        | 1%      |
| 16.01-24.0 | 9         | 0.82%   |
| 24.01-32.0 | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 818       | 80.2%   |
| 2      | 177       | 17.35%  |
| 3      | 16        | 1.57%   |
| 0      | 5         | 0.49%   |
| 4      | 4         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 714       | 70.83%  |
| Yes       | 294       | 29.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 814       | 80.67%  |
| No        | 195       | 19.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 994       | 99%     |
| No        | 10        | 1%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 831       | 81.95%  |
| No        | 183       | 18.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 1004      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Stockholm         | 200       | 18.43%  |
| Gothenburg        | 108       | 9.95%   |
| Malmo             | 47        | 4.33%   |
| Uppsala           | 27        | 2.49%   |
| Linköping        | 18        | 1.66%   |
| Saltsjoe-Boo      | 17        | 1.57%   |
| Bromma            | 16        | 1.47%   |
| Örebro           | 15        | 1.38%   |
| Lund              | 15        | 1.38%   |
| Vaxjo             | 12        | 1.11%   |
| Solna             | 12        | 1.11%   |
| Sollentuna        | 12        | 1.11%   |
| Huddinge          | 12        | 1.11%   |
| Vaestra Froelunda | 11        | 1.01%   |
| Norrköping       | 11        | 1.01%   |
| Bandhagen         | 10        | 0.92%   |
| Västerås        | 9         | 0.83%   |
| Umeå             | 9         | 0.83%   |
| Sundbyberg        | 9         | 0.83%   |
| Kista             | 9         | 0.83%   |
| Karlskrona        | 9         | 0.83%   |
| Haegersten        | 9         | 0.83%   |
| Södertälje      | 8         | 0.74%   |
| Landskrona        | 8         | 0.74%   |
| Halmstad          | 8         | 0.74%   |
| Taby              | 7         | 0.65%   |
| Sundsvall         | 7         | 0.65%   |
| Staffanstorp      | 7         | 0.65%   |
| Norsborg          | 7         | 0.65%   |
| Mjoelby           | 7         | 0.65%   |
| Katrineholm       | 7         | 0.65%   |
| Karlstad          | 7         | 0.65%   |
| Helsingborg       | 7         | 0.65%   |
| Gävle            | 7         | 0.65%   |
| Moelndal          | 6         | 0.55%   |
| Jönköping       | 6         | 0.55%   |
| Handen            | 6         | 0.55%   |
| Alvsjo            | 6         | 0.55%   |
| Upplands Vasby    | 5         | 0.46%   |
| Spanga            | 5         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 254       | 333    | 21.29%  |
| WDC                            | 112       | 138    | 9.39%   |
| Toshiba                        | 89        | 110    | 7.46%   |
| Seagate                        | 89        | 101    | 7.46%   |
| Intel                          | 80        | 91     | 6.71%   |
| SanDisk                        | 77        | 97     | 6.45%   |
| Kingston                       | 76        | 97     | 6.37%   |
| Unknown                        | 63        | 78     | 5.28%   |
| SK hynix                       | 62        | 68     | 5.2%    |
| Micron Technology              | 45        | 51     | 3.77%   |
| Hitachi                        | 34        | 39     | 2.85%   |
| HGST                           | 28        | 33     | 2.35%   |
| Apple                          | 25        | 32     | 2.1%    |
| Crucial                        | 19        | 26     | 1.59%   |
| LITEON                         | 16        | 20     | 1.34%   |
| KIOXIA                         | 10        | 10     | 0.84%   |
| OCZ                            | 9         | 9      | 0.75%   |
| LITEONIT                       | 7         | 11     | 0.59%   |
| Kingston Technology Company    | 7         | 7      | 0.59%   |
| A-DATA Technology              | 7         | 7      | 0.59%   |
| Intenso                        | 6         | 6      | 0.5%    |
| Phison                         | 5         | 5      | 0.42%   |
| Phison Electronics             | 4         | 4      | 0.34%   |
| Fujitsu                        | 4         | 6      | 0.34%   |
| China                          | 4         | 4      | 0.34%   |
| Union Memory                   | 3         | 3      | 0.25%   |
| Transcend                      | 3         | 3      | 0.25%   |
| Silicon Motion                 | 3         | 14     | 0.25%   |
| Lenovo                         | 3         | 3      | 0.25%   |
| Star Drive                     | 2         | 2      | 0.17%   |
| Solid State Storage Technology | 2         | 2      | 0.17%   |
| ROG                            | 2         | 2      | 0.17%   |
| PNY                            | 2         | 2      | 0.17%   |
| M4-CT128                       | 2         | 2      | 0.17%   |
| Lite-On                        | 2         | 2      | 0.17%   |
| KingSpec                       | 2         | 2      | 0.17%   |
| JMicron Technology             | 2         | 2      | 0.17%   |
| Hewlett-Packard                | 2         | 2      | 0.17%   |
| GOODRAM                        | 2         | 2      | 0.17%   |
| Corsair                        | 2         | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba NVMe SSD Drive 512GB                        | 12        | 0.98%   |
| SK hynix NVMe SSD Drive 512GB                       | 11        | 0.9%    |
| Samsung NVMe SSD Drive 512GB                        | 11        | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 11        | 0.9%    |
| Unknown MMC Card  32GB                              | 10        | 0.81%   |
| SanDisk NVMe SSD Drive 512GB                        | 10        | 0.81%   |
| Kingston SA400S37480G 480GB SSD                     | 10        | 0.81%   |
| Samsung NVMe SSD Drive 256GB                        | 9         | 0.73%   |
| Samsung NVMe SSD Drive 1024GB                       | 9         | 0.73%   |
| Unknown MMC Card  16GB                              | 8         | 0.65%   |
| Seagate ST9500325AS 500GB                           | 8         | 0.65%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 8         | 0.65%   |
| Kingston SA400S37120G 120GB SSD                     | 8         | 0.65%   |
| HGST HTS721010A9E630 1TB                            | 8         | 0.65%   |
| Unknown MMC Card  64GB                              | 7         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 7         | 0.57%   |
| Samsung SSD 850 EVO 500GB                           | 7         | 0.57%   |
| Samsung SSD 850 EVO 250GB                           | 7         | 0.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 7         | 0.57%   |
| Intel NVMe SSD Drive 256GB                          | 7         | 0.57%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 6         | 0.49%   |
| Toshiba NVMe SSD Drive 256GB                        | 6         | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6         | 0.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 6         | 0.49%   |
| Kingston SUV400S37120G 120GB SSD                    | 6         | 0.49%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 0.49%   |
| Intel SSDPEKNW010T8 1TB                             | 6         | 0.49%   |
| Unknown MMC Card  128GB                             | 5         | 0.41%   |
| Seagate ST320LT007-9ZV142 320GB                     | 5         | 0.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 5         | 0.41%   |
| SanDisk NVMe SSD Drive 256GB                        | 5         | 0.41%   |
| Samsung SSD 860 EVO 500GB                           | 5         | 0.41%   |
| Micron NVMe SSD Drive 512GB                         | 5         | 0.41%   |
| HGST HTS545050A7E680 500GB                          | 5         | 0.41%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 4         | 0.33%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 4         | 0.33%   |
| Toshiba XG4 NVMe SSD Controller 256GB               | 4         | 0.33%   |
| Toshiba MQ04ABF100 1TB                              | 4         | 0.33%   |
| Toshiba MQ01ACF032 320GB                            | 4         | 0.33%   |
| Toshiba MQ01ABD100 1TB                              | 4         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 86        | 97     | 33.08%  |
| WDC                 | 60        | 76     | 23.08%  |
| Toshiba             | 35        | 42     | 13.46%  |
| Hitachi             | 34        | 39     | 13.08%  |
| HGST                | 28        | 33     | 10.77%  |
| Samsung Electronics | 5         | 5      | 1.92%   |
| Fujitsu             | 4         | 6      | 1.54%   |
| Apple               | 4         | 4      | 1.54%   |
| Unknown             | 2         | 2      | 0.77%   |
| Intenso             | 1         | 1      | 0.38%   |
| ASMT                | 1         | 1      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 123       | 170    | 27.09%  |
| Kingston            | 61        | 79     | 13.44%  |
| SanDisk             | 44        | 54     | 9.69%   |
| Intel               | 43        | 48     | 9.47%   |
| Micron Technology   | 24        | 28     | 5.29%   |
| WDC                 | 23        | 28     | 5.07%   |
| Crucial             | 18        | 25     | 3.96%   |
| Apple               | 18        | 24     | 3.96%   |
| SK hynix            | 17        | 19     | 3.74%   |
| LITEON              | 15        | 19     | 3.3%    |
| Toshiba             | 13        | 20     | 2.86%   |
| OCZ                 | 9         | 9      | 1.98%   |
| LITEONIT            | 7         | 11     | 1.54%   |
| Intenso             | 4         | 4      | 0.88%   |
| China               | 4         | 4      | 0.88%   |
| Transcend           | 3         | 3      | 0.66%   |
| A-DATA Technology   | 3         | 3      | 0.66%   |
| PNY                 | 2         | 2      | 0.44%   |
| M4-CT128            | 2         | 2      | 0.44%   |
| KingSpec            | 2         | 2      | 0.44%   |
| Corsair             | 2         | 2      | 0.44%   |
| Unknown             | 1         | 1      | 0.22%   |
| TO Exter            | 1         | 1      | 0.22%   |
| Team                | 1         | 1      | 0.22%   |
| Star                | 1         | 1      | 0.22%   |
| SSSTC               | 1         | 2      | 0.22%   |
| Seagate             | 1         | 1      | 0.22%   |
| Radeon              | 1         | 2      | 0.22%   |
| OCZ-VERTEX3         | 1         | 1      | 0.22%   |
| MyDigitalSSD        | 1         | 1      | 0.22%   |
| Maxtor              | 1         | 1      | 0.22%   |
| Lexar               | 1         | 1      | 0.22%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.22%   |
| KingFast            | 1         | 1      | 0.22%   |
| JMicron Technology  | 1         | 1      | 0.22%   |
| GOODRAM             | 1         | 1      | 0.22%   |
| FORESEE             | 1         | 1      | 0.22%   |
| ASMT                | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 418       | 575    | 37.09%  |
| NVMe    | 384       | 494    | 34.07%  |
| HDD     | 253       | 306    | 22.45%  |
| MMC     | 62        | 76     | 5.5%    |
| Unknown | 10        | 9      | 0.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 616       | 862    | 56.46%  |
| NVMe | 383       | 491    | 35.11%  |
| MMC  | 62        | 76     | 5.68%   |
| SAS  | 30        | 31     | 2.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 516       | 700    | 77.59%  |
| 0.51-1.0   | 140       | 171    | 21.05%  |
| 1.01-2.0   | 5         | 6      | 0.75%   |
| 3.01-4.0   | 3         | 3      | 0.45%   |
| 4.01-10.0  | 1         | 1      | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 345       | 32.76%  |
| 251-500        | 278       | 26.4%   |
| 501-1000       | 136       | 12.92%  |
| 1-20           | 83        | 7.88%   |
| 1001-2000      | 58        | 5.51%   |
| 51-100         | 57        | 5.41%   |
| Unknown        | 42        | 3.99%   |
| 21-50          | 36        | 3.42%   |
| More than 3000 | 9         | 0.85%   |
| 2001-3000      | 9         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 467       | 43%     |
| 21-50          | 177       | 16.3%   |
| 101-250        | 158       | 14.55%  |
| 51-100         | 119       | 10.96%  |
| 251-500        | 68        | 6.26%   |
| Unknown        | 42        | 3.87%   |
| 501-1000       | 38        | 3.5%    |
| 1001-2000      | 14        | 1.29%   |
| More than 3000 | 1         | 0.09%   |
| 2001-3000      | 1         | 0.09%   |
| 0              | 1         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 4         | 4      | 8.16%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 3         | 4      | 6.12%   |
| Seagate ST9250410AS 250GB                           | 2         | 3      | 4.08%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 4.08%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 2.04%   |
| Union Memory UMIS RPJTJ128MED1MWX 128GB             | 1         | 1      | 2.04%   |
| Transcend TS240GMTS420S 240GB SSD                   | 1         | 1      | 2.04%   |
| Toshiba MK1633GSG 160GB                             | 1         | 1      | 2.04%   |
| Toshiba MK1237GSX 120GB                             | 1         | 1      | 2.04%   |
| Team L5 LITE SSD 240GB                              | 1         | 1      | 2.04%   |
| SK hynix SH920 mSATA 128GB SSD                      | 1         | 1      | 2.04%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD               | 1         | 1      | 2.04%   |
| Seagate ST980817AS 80GB                             | 1         | 1      | 2.04%   |
| Seagate ST96812A 64GB                               | 1         | 1      | 2.04%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 2.04%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 2.04%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 2.04%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 2.04%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 2.04%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD                 | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 2.04%   |
| Samsung Electronics MZ7PA128HMCD-010L1 128GB SSD    | 1         | 1      | 2.04%   |
| OCZ AGILITY3 120GB SSD                              | 1         | 1      | 2.04%   |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 2.04%   |
| LITEONIT LMT-256M6M-HP 256GB SSD                    | 1         | 1      | 2.04%   |
| Intel SSDSCKJF180A5H RSED 180GB                     | 1         | 1      | 2.04%   |
| Intel SSDSC2BW480A4 480GB                           | 1         | 1      | 2.04%   |
| Intel SSDSC2BW240A4 240GB                           | 1         | 2      | 2.04%   |
| Intel SSDSA2BW160G3H 160GB                          | 1         | 1      | 2.04%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 2.04%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 2.04%   |
| Hitachi HTS543216L9A300 160GB                       | 1         | 1      | 2.04%   |
| Hitachi HTS542525K9SA00 250GB                       | 1         | 1      | 2.04%   |
| Hitachi HTS541616J9AT00 160GB                       | 1         | 1      | 2.04%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 2.04%   |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 2.04%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 2.04%   |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 2.04%   |
| Corsair Force 3 SSD 240GB                           | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 15     | 28.57%  |
| HGST                | 6         | 6      | 12.24%  |
| Hitachi             | 5         | 5      | 10.2%   |
| Micron Technology   | 4         | 5      | 8.16%   |
| Intel               | 4         | 5      | 8.16%   |
| Toshiba             | 2         | 2      | 4.08%   |
| SK hynix            | 2         | 2      | 4.08%   |
| Samsung Electronics | 2         | 2      | 4.08%   |
| WDC                 | 1         | 1      | 2.04%   |
| Union Memory        | 1         | 1      | 2.04%   |
| Transcend           | 1         | 1      | 2.04%   |
| Team                | 1         | 1      | 2.04%   |
| SanDisk             | 1         | 1      | 2.04%   |
| OCZ                 | 1         | 1      | 2.04%   |
| LITEONIT            | 1         | 1      | 2.04%   |
| Corsair             | 1         | 1      | 2.04%   |
| China               | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 15     | 48.28%  |
| HGST    | 6         | 6      | 20.69%  |
| Hitachi | 5         | 5      | 17.24%  |
| Toshiba | 2         | 2      | 6.9%    |
| WDC     | 1         | 1      | 3.45%   |
| Apple   | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 30     | 59.18%  |
| SSD  | 19        | 21     | 38.78%  |
| NVMe | 1         | 1      | 2.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 100%    |

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
| Detected | 632       | 926    | 59.62%  |
| Works    | 379       | 481    | 35.75%  |
| Malfunc  | 48        | 52     | 4.53%   |
| Failed   | 1         | 1      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 652       | 56.84%  |
| Samsung Electronics              | 143       | 12.47%  |
| AMD                              | 101       | 8.81%   |
| SanDisk                          | 59        | 5.14%   |
| SK hynix                         | 44        | 3.84%   |
| Toshiba America Info Systems     | 43        | 3.75%   |
| Micron Technology                | 21        | 1.83%   |
| Kingston Technology Company      | 20        | 1.74%   |
| Phison Electronics               | 11        | 0.96%   |
| KIOXIA                           | 9         | 0.78%   |
| Nvidia                           | 7         | 0.61%   |
| Silicon Motion                   | 5         | 0.44%   |
| ADATA Technology                 | 5         | 0.44%   |
| Union Memory (Shenzhen)          | 4         | 0.35%   |
| Lite-On Technology               | 4         | 0.35%   |
| Apple                            | 4         | 0.35%   |
| Solid State Storage Technology   | 3         | 0.26%   |
| Silicon Integrated Systems [SiS] | 3         | 0.26%   |
| Marvell Technology Group         | 3         | 0.26%   |
| Lenovo                           | 3         | 0.26%   |
| Seagate Technology               | 1         | 0.09%   |
| Realtek Semiconductor            | 1         | 0.09%   |
| Micron/Crucial Technology        | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 83        | 6.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 80        | 6.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 73        | 5.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 68        | 5.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 55        | 4.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 51        | 4.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 47        | 3.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 40        | 3.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 33        | 2.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 33        | 2.71%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 28        | 2.3%    |
| Samsung NVMe SSD Controller 980                                                | 26        | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 23        | 1.89%   |
| Micron NVMe Storage Controller                                                 | 21        | 1.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 21        | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 21        | 1.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 17        | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 17        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 17        | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 16        | 1.31%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 15        | 1.23%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 15        | 1.23%   |
| Intel SSD 660P Series                                                          | 15        | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 15        | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 14        | 1.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 13        | 1.07%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 11        | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 11        | 0.9%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 10        | 0.82%   |
| SK hynix Non-Volatile memory controller                                        | 9         | 0.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 0.74%   |
| Samsung Electronics SATA controller                                            | 9         | 0.74%   |
| Intel SSD 600P Series                                                          | 9         | 0.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 0.74%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 8         | 0.66%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 8         | 0.66%   |
| Kingston Company Company Non-Volatile memory controller                        | 8         | 0.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 8         | 0.66%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 7         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 639       | 54.29%  |
| NVMe | 386       | 32.8%   |
| RAID | 82        | 6.97%   |
| IDE  | 70        | 5.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 835       | 83.17%  |
| AMD    | 169       | 16.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 24        | 2.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 23        | 2.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 19        | 1.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 15        | 1.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 14        | 1.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 12        | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 12        | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 11        | 1.1%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 11        | 1.1%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 11        | 1.1%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 10        | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 1%      |
| Intel Core i7-7500U CPU @ 2.70GHz       | 9         | 0.9%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.9%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 9         | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 9         | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz       | 9         | 0.9%    |
| Intel Celeron CPU N2840 @ 2.16GHz       | 9         | 0.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 8         | 0.8%    |
| Intel Core i7-5500U CPU @ 2.40GHz       | 8         | 0.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz      | 8         | 0.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 0.8%    |
| Intel Core i5-4300U CPU @ 1.90GHz       | 8         | 0.8%    |
| AMD Ryzen 7 5700U with Radeon Graphics  | 8         | 0.8%    |
| Intel Core i7-5600U CPU @ 2.60GHz       | 7         | 0.7%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 7         | 0.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz       | 7         | 0.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz       | 7         | 0.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz       | 7         | 0.7%    |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 7         | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics  | 7         | 0.7%    |
| Intel Core i7-8850H CPU @ 2.60GHz       | 6         | 0.6%    |
| Intel Core i7-8650U CPU @ 1.90GHz       | 6         | 0.6%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 6         | 0.6%    |
| Intel Core i7-4510U CPU @ 2.00GHz       | 6         | 0.6%    |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 6         | 0.6%    |
| Intel Core i5-8365U CPU @ 1.60GHz       | 6         | 0.6%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 6         | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 6         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 289       | 28.78%  |
| Intel Core i5                  | 263       | 26.2%   |
| Other                          | 90        | 8.96%   |
| Intel Core i3                  | 52        | 5.18%   |
| Intel Core 2 Duo               | 42        | 4.18%   |
| AMD Ryzen 7                    | 40        | 3.98%   |
| Intel Celeron                  | 39        | 3.88%   |
| AMD Ryzen 5                    | 29        | 2.89%   |
| Intel Pentium                  | 15        | 1.49%   |
| Intel Atom                     | 13        | 1.29%   |
| AMD Ryzen 9                    | 10        | 1%      |
| Intel Genuine                  | 9         | 0.9%    |
| AMD Ryzen 3                    | 9         | 0.9%    |
| AMD A6                         | 9         | 0.9%    |
| Intel Core 2                   | 7         | 0.7%    |
| AMD Ryzen 7 PRO                | 7         | 0.7%    |
| AMD A8                         | 7         | 0.7%    |
| AMD A4                         | 7         | 0.7%    |
| Intel Xeon                     | 6         | 0.6%    |
| Intel Core i9                  | 6         | 0.6%    |
| AMD E1                         | 6         | 0.6%    |
| AMD Ryzen 5 PRO                | 5         | 0.5%    |
| AMD E                          | 5         | 0.5%    |
| AMD A10                        | 5         | 0.5%    |
| Intel Pentium Silver           | 3         | 0.3%    |
| Intel Pentium Dual             | 3         | 0.3%    |
| Intel Core m3                  | 3         | 0.3%    |
| Intel Celeron Dual-Core        | 3         | 0.3%    |
| Intel Pentium M                | 2         | 0.2%    |
| AMD Turion 64 X2 Mobile        | 2         | 0.2%    |
| AMD Athlon 64 X2               | 2         | 0.2%    |
| Intel Pentium Dual-Core        | 1         | 0.1%    |
| Intel Core m5                  | 1         | 0.1%    |
| Intel Celeron M                | 1         | 0.1%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.1%    |
| AMD Turion II Dual-Core        | 1         | 0.1%    |
| AMD Turion 64 Mobile           | 1         | 0.1%    |
| AMD Sempron                    | 1         | 0.1%    |
| AMD Quad-Core                  | 1         | 0.1%    |
| AMD PRO A10                    | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 497       | 49.5%   |
| 4      | 334       | 33.27%  |
| 6      | 73        | 7.27%   |
| 8      | 68        | 6.77%   |
| 1      | 14        | 1.39%   |
| 14     | 9         | 0.9%    |
| 12     | 5         | 0.5%    |
| 10     | 4         | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1004      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 799       | 79.5%   |
| 1      | 206       | 20.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 984       | 97.72%  |
| Unknown        | 16        | 1.59%   |
| 32-bit         | 7         | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 254       | 24.47%  |
| 0x306a9    | 57        | 5.49%   |
| 0x206a7    | 47        | 4.53%   |
| 0x40651    | 46        | 4.43%   |
| 0x306c3    | 40        | 3.85%   |
| 0x806c1    | 39        | 3.76%   |
| 0x306d4    | 39        | 3.76%   |
| 0x406e3    | 37        | 3.56%   |
| 0x806ec    | 34        | 3.28%   |
| 0x806ea    | 33        | 3.18%   |
| 0x806e9    | 32        | 3.08%   |
| 0x20655    | 23        | 2.22%   |
| 0x1067a    | 23        | 2.22%   |
| 0x906ea    | 22        | 2.12%   |
| 0x906e9    | 22        | 2.12%   |
| 0x0a50000c | 15        | 1.45%   |
| 0x08600106 | 13        | 1.25%   |
| 0xa0652    | 12        | 1.16%   |
| 0x806eb    | 11        | 1.06%   |
| 0x6fd      | 11        | 1.06%   |
| 0x406c4    | 10        | 0.96%   |
| 0x906a3    | 9         | 0.87%   |
| 0x806d1    | 9         | 0.87%   |
| 0x506e3    | 9         | 0.87%   |
| 0x30678    | 9         | 0.87%   |
| 0x08108109 | 9         | 0.87%   |
| 0x0700010f | 9         | 0.87%   |
| 0x20652    | 8         | 0.77%   |
| 0x08608103 | 8         | 0.77%   |
| 0x0810100b | 8         | 0.77%   |
| 0x6fb      | 7         | 0.67%   |
| 0x6f6      | 7         | 0.67%   |
| 0x08108102 | 7         | 0.67%   |
| 0x05000119 | 7         | 0.67%   |
| 0x906ed    | 6         | 0.58%   |
| 0x10676    | 6         | 0.58%   |
| 0x06001119 | 6         | 0.58%   |
| 0x706e5    | 5         | 0.48%   |
| 0x40661    | 5         | 0.48%   |
| 0x06006705 | 5         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 217       | 21.61%  |
| Haswell          | 107       | 10.66%  |
| IvyBridge        | 77        | 7.67%   |
| SandyBridge      | 65        | 6.47%   |
| Skylake          | 59        | 5.88%   |
| TigerLake        | 48        | 4.78%   |
| Broadwell        | 45        | 4.48%   |
| Unknown          | 40        | 3.98%   |
| Westmere         | 36        | 3.59%   |
| Penryn           | 34        | 3.39%   |
| Silvermont       | 33        | 3.29%   |
| Core             | 32        | 3.19%   |
| Zen 3            | 28        | 2.79%   |
| Zen 2            | 23        | 2.29%   |
| CometLake        | 20        | 1.99%   |
| Zen+             | 18        | 1.79%   |
| Excavator        | 14        | 1.39%   |
| Icelake          | 13        | 1.29%   |
| Alderlake Hybrid | 12        | 1.2%    |
| Zen              | 10        | 1%      |
| Jaguar           | 9         | 0.9%    |
| Goldmont plus    | 9         | 0.9%    |
| Piledriver       | 8         | 0.8%    |
| Bobcat           | 7         | 0.7%    |
| K8 Hammer        | 6         | 0.6%    |
| K10 Llano        | 6         | 0.6%    |
| Puma             | 5         | 0.5%    |
| Bonnell          | 5         | 0.5%    |
| P6               | 4         | 0.4%    |
| K10              | 4         | 0.4%    |
| Goldmont         | 4         | 0.4%    |
| Nehalem          | 3         | 0.3%    |
| K8 & K10 hybrid  | 2         | 0.2%    |
| Tremont          | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 748       | 59.37%  |
| Nvidia                           | 297       | 23.57%  |
| AMD                              | 212       | 16.83%  |
| Silicon Integrated Systems [SiS] | 3         | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 67        | 5.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 58        | 4.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 56        | 4.29%   |
| Intel UHD Graphics 620                                                                   | 47        | 3.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 44        | 3.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 3.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 40        | 3.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 3.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 38        | 2.91%   |
| Intel HD Graphics 5500                                                                   | 35        | 2.68%   |
| Intel HD Graphics 620                                                                    | 32        | 2.45%   |
| Intel HD Graphics 630                                                                    | 25        | 1.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 25        | 1.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 24        | 1.84%   |
| AMD Renoir                                                                               | 23        | 1.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 1.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 1.15%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 1.07%   |
| AMD Lucienne                                                                             | 14        | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 13        | 1%      |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 11        | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 0.77%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 10        | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.69%   |
| Nvidia GM108M [GeForce 840M]                                                             | 9         | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 0.69%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 0.61%   |
| Intel HD Graphics 530                                                                    | 8         | 0.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 0.61%   |
| AMD Rembrandt [Radeon 680M]                                                              | 8         | 0.61%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 7         | 0.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 7         | 0.54%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 7         | 0.54%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 521       | 51.74%  |
| Intel + Nvidia | 201       | 19.96%  |
| 1 x AMD        | 138       | 13.7%   |
| 1 x Nvidia     | 68        | 6.75%   |
| AMD + Nvidia   | 28        | 2.78%   |
| Intel + AMD    | 26        | 2.58%   |
| 2 x AMD        | 21        | 2.09%   |
| 1 x SiS        | 3         | 0.3%    |
| Other          | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 832       | 81.97%  |
| Proprietary | 164       | 16.16%  |
| Unknown     | 19        | 1.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 669       | 65.27%  |
| 0.01-0.5   | 119       | 11.61%  |
| 1.01-2.0   | 111       | 10.83%  |
| 0.51-1.0   | 50        | 4.88%   |
| 3.01-4.0   | 49        | 4.78%   |
| 5.01-6.0   | 13        | 1.27%   |
| 7.01-8.0   | 10        | 0.98%   |
| 2.01-3.0   | 4         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 262       | 22.37%  |
| LG Display              | 153       | 13.07%  |
| Chimei Innolux          | 141       | 12.04%  |
| Samsung Electronics     | 119       | 10.16%  |
| BOE                     | 88        | 7.51%   |
| Sharp                   | 58        | 4.95%   |
| Apple                   | 42        | 3.59%   |
| Dell                    | 35        | 2.99%   |
| Lenovo                  | 28        | 2.39%   |
| Chi Mei Optoelectronics | 24        | 2.05%   |
| Philips                 | 22        | 1.88%   |
| InfoVision              | 20        | 1.71%   |
| LG Philips              | 17        | 1.45%   |
| Hewlett-Packard         | 16        | 1.37%   |
| AOC                     | 12        | 1.02%   |
| CSO                     | 11        | 0.94%   |
| BenQ                    | 11        | 0.94%   |
| ASUSTek Computer        | 10        | 0.85%   |
| PANDA                   | 9         | 0.77%   |
| Ancor Communications    | 9         | 0.77%   |
| Goldstar                | 8         | 0.68%   |
| Acer                    | 8         | 0.68%   |
| Sony                    | 5         | 0.43%   |
| Panasonic               | 5         | 0.43%   |
| BOE Technology Group    | 5         | 0.43%   |
| Quanta Display          | 4         | 0.34%   |
| LGD                     | 4         | 0.34%   |
| Vestel Elektronik       | 3         | 0.26%   |
| Toshiba                 | 3         | 0.26%   |
| Eizo                    | 3         | 0.26%   |
| Analogix                | 3         | 0.26%   |
| Valve                   | 2         | 0.17%   |
| Unknown                 | 2         | 0.17%   |
| Nvidia                  | 2         | 0.17%   |
| Fujitsu Siemens         | 2         | 0.17%   |
| CPT                     | 2         | 0.17%   |
| VOXICON                 | 1         | 0.09%   |
| ViewSonic               | 1         | 0.09%   |
| TMX                     | 1         | 0.09%   |
| TCL                     | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 13        | 1.1%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 12        | 1.01%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 9         | 0.76%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 8         | 0.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.67%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 8         | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.59%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 0.59%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 6         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 6         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 6         | 0.51%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 6         | 0.51%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 5         | 0.42%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 5         | 0.42%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 5         | 0.42%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 4         | 0.34%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 4         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 4         | 0.34%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch          | 4         | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.34%   |
| InfoVision LCD Monitor IVO857F 1920x1080 294x165mm 13.3-inch          | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 4         | 0.34%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 0.34%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch        | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO332C 1366x768 293x165mm 13.2-inch         | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 4         | 0.34%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 4         | 0.34%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch  | 3         | 0.25%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.25%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 3         | 0.25%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 3         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 488       | 43.57%  |
| 1366x768 (WXGA)    | 242       | 21.61%  |
| 3840x2160 (4K)     | 69        | 6.16%   |
| 2560x1440 (QHD)    | 52        | 4.64%   |
| 1280x800 (WXGA)    | 44        | 3.93%   |
| 1600x900 (HD+)     | 42        | 3.75%   |
| 1920x1200 (WUXGA)  | 31        | 2.77%   |
| 2560x1600          | 23        | 2.05%   |
| 1440x900 (WXGA+)   | 18        | 1.61%   |
| 2880x1800          | 17        | 1.52%   |
| 3840x2400          | 15        | 1.34%   |
| 1680x1050 (WSXGA+) | 15        | 1.34%   |
| 3440x1440          | 11        | 0.98%   |
| 3200x1800 (QHD+)   | 6         | 0.54%   |
| 1280x1024 (SXGA)   | 6         | 0.54%   |
| 1024x768 (XGA)     | 6         | 0.54%   |
| 800x1280           | 5         | 0.45%   |
| 1024x600           | 5         | 0.45%   |
| 1920x540           | 4         | 0.36%   |
| Unknown            | 4         | 0.36%   |
| 2160x1440          | 3         | 0.27%   |
| 1360x768           | 3         | 0.27%   |
| 3840x1080          | 2         | 0.18%   |
| 2288x1287          | 2         | 0.18%   |
| 3840x1600          | 1         | 0.09%   |
| 3840x1100          | 1         | 0.09%   |
| 2880x1920          | 1         | 0.09%   |
| 2560x1700          | 1         | 0.09%   |
| 2560x1080          | 1         | 0.09%   |
| 1920x1280          | 1         | 0.09%   |
| 1400x1050          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 380       | 32.4%   |
| 13      | 227       | 19.35%  |
| 14      | 150       | 12.79%  |
| 17      | 73        | 6.22%   |
| 27      | 56        | 4.77%   |
| 12      | 52        | 4.43%   |
| 24      | 44        | 3.75%   |
| 23      | 23        | 1.96%   |
| 11      | 23        | 1.96%   |
| Unknown | 23        | 1.96%   |
| 31      | 15        | 1.28%   |
| 16      | 14        | 1.19%   |
| 34      | 9         | 0.77%   |
| 21      | 8         | 0.68%   |
| 22      | 7         | 0.6%    |
| 18      | 7         | 0.6%    |
| 84      | 6         | 0.51%   |
| 32      | 5         | 0.43%   |
| 19      | 5         | 0.43%   |
| 10      | 5         | 0.43%   |
| 65      | 4         | 0.34%   |
| 54      | 3         | 0.26%   |
| 29      | 3         | 0.26%   |
| 3       | 3         | 0.26%   |
| 72      | 2         | 0.17%   |
| 47      | 2         | 0.17%   |
| 42      | 2         | 0.17%   |
| 40      | 2         | 0.17%   |
| 39      | 2         | 0.17%   |
| 37      | 2         | 0.17%   |
| 35      | 2         | 0.17%   |
| 33      | 2         | 0.17%   |
| 26      | 2         | 0.17%   |
| 7       | 2         | 0.17%   |
| 142     | 1         | 0.09%   |
| 75      | 1         | 0.09%   |
| 74      | 1         | 0.09%   |
| 60      | 1         | 0.09%   |
| 48      | 1         | 0.09%   |
| 25      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 635       | 54.6%   |
| 201-300        | 206       | 17.71%  |
| 501-600        | 114       | 9.8%    |
| 351-400        | 83        | 7.14%   |
| 601-700        | 24        | 2.06%   |
| 401-500        | 24        | 2.06%   |
| Unknown        | 23        | 1.98%   |
| 701-800        | 16        | 1.38%   |
| 1001-1500      | 11        | 0.95%   |
| 1501-2000      | 10        | 0.86%   |
| 801-900        | 7         | 0.6%    |
| 1-100          | 5         | 0.43%   |
| 901-1000       | 3         | 0.26%   |
| More than 2000 | 1         | 0.09%   |
| 101-200        | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 810       | 78.03%  |
| 16/10   | 162       | 15.61%  |
| Unknown | 21        | 2.02%   |
| 21/9    | 13        | 1.25%   |
| 3/2     | 9         | 0.87%   |
| 4/3     | 8         | 0.77%   |
| 5/4     | 6         | 0.58%   |
| 6/5     | 4         | 0.39%   |
| 0.67    | 2         | 0.19%   |
| 32/9    | 1         | 0.1%    |
| 3.40    | 1         | 0.1%    |
| 1.00    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 375       | 32.05%  |
| 81-90          | 274       | 23.42%  |
| 71-80          | 102       | 8.72%   |
| 121-130        | 62        | 5.3%    |
| 201-250        | 59        | 5.04%   |
| 301-350        | 58        | 4.96%   |
| 61-70          | 49        | 4.19%   |
| 351-500        | 34        | 2.91%   |
| 51-60          | 24        | 2.05%   |
| Unknown        | 23        | 1.97%   |
| 251-300        | 22        | 1.88%   |
| More than 1000 | 20        | 1.71%   |
| 111-120        | 16        | 1.37%   |
| 131-140        | 12        | 1.03%   |
| 501-1000       | 10        | 0.85%   |
| 151-200        | 8         | 0.68%   |
| 141-150        | 7         | 0.6%    |
| 41-50          | 6         | 0.51%   |
| 1-40           | 5         | 0.43%   |
| 91-100         | 4         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 482       | 42.02%  |
| 101-120       | 273       | 23.8%   |
| 51-100        | 161       | 14.04%  |
| 161-240       | 124       | 10.81%  |
| More than 240 | 66        | 5.75%   |
| Unknown       | 23        | 2.01%   |
| 1-50          | 18        | 1.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 805       | 78.38%  |
| 2     | 179       | 17.43%  |
| 3     | 23        | 2.24%   |
| 0     | 20        | 1.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 610       | 39.56%  |
| Realtek Semiconductor                  | 402       | 26.07%  |
| Qualcomm Atheros                       | 183       | 11.87%  |
| Broadcom                               | 110       | 7.13%   |
| Broadcom Limited                       | 35        | 2.27%   |
| MediaTek                               | 27        | 1.75%   |
| Hewlett-Packard                        | 18        | 1.17%   |
| Ralink                                 | 13        | 0.84%   |
| Marvell Technology Group               | 13        | 0.84%   |
| Dell                                   | 13        | 0.84%   |
| ASIX Electronics                       | 13        | 0.84%   |
| Sierra Wireless                        | 11        | 0.71%   |
| Lenovo                                 | 11        | 0.71%   |
| Ericsson Business Mobile Networks      | 7         | 0.45%   |
| DisplayLink                            | 7         | 0.45%   |
| Nvidia                                 | 6         | 0.39%   |
| Huawei Technologies                    | 6         | 0.39%   |
| Fibocom                                | 5         | 0.32%   |
| ASUSTek Computer                       | 5         | 0.32%   |
| Qualcomm                               | 4         | 0.26%   |
| NetGear                                | 4         | 0.26%   |
| TP-Link                                | 3         | 0.19%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.19%   |
| Samsung Electronics                    | 3         | 0.19%   |
| D-Link                                 | 3         | 0.19%   |
| Texas Instruments                      | 2         | 0.13%   |
| Ralink Technology                      | 2         | 0.13%   |
| Microsoft                              | 2         | 0.13%   |
| JMicron Technology                     | 2         | 0.13%   |
| Xiaomi                                 | 1         | 0.06%   |
| Wacom                                  | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| SEGGER                                 | 1         | 0.06%   |
| Qualcomm Atheros Communications        | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| Novatek Microelectronics               | 1         | 0.06%   |
| Linksys                                | 1         | 0.06%   |
| IMC Networks                           | 1         | 0.06%   |
| ICS Advent                             | 1         | 0.06%   |
| Gemtek                                 | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 246       | 12.63%  |
| Intel Wireless 8265 / 8275                                        | 72        | 3.7%    |
| Intel Wireless 7260                                               | 56        | 2.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54        | 2.77%   |
| Intel Wi-Fi 6 AX200                                               | 51        | 2.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45        | 2.31%   |
| Intel Wireless 7265                                               | 44        | 2.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 2.21%   |
| Intel Wireless 8260                                               | 39        | 2%      |
| Intel Wi-Fi 6 AX201                                               | 37        | 1.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 30        | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 27        | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 26        | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 24        | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 22        | 1.13%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 1.08%   |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 1.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 20        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 19        | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 17        | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 17        | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 17        | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 17        | 0.87%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 16        | 0.82%   |
| Intel Wireless 3160                                               | 15        | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 15        | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.77%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 15        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 14        | 0.72%   |
| Intel Wireless-AC 9260                                            | 14        | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 0.72%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 0.72%   |
| Intel Centrino Advanced-N 6200                                    | 14        | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 13        | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 581       | 55.23%  |
| Qualcomm Atheros                | 154       | 14.64%  |
| Realtek Semiconductor           | 120       | 11.41%  |
| Broadcom                        | 83        | 7.89%   |
| MediaTek                        | 27        | 2.57%   |
| Broadcom Limited                | 21        | 2%      |
| Ralink                          | 13        | 1.24%   |
| Sierra Wireless                 | 11        | 1.05%   |
| Dell                            | 7         | 0.67%   |
| Fibocom                         | 5         | 0.48%   |
| ASUSTek Computer                | 5         | 0.48%   |
| NetGear                         | 4         | 0.38%   |
| Hewlett-Packard                 | 4         | 0.38%   |
| Qualcomm                        | 3         | 0.29%   |
| Ralink Technology               | 2         | 0.19%   |
| D-Link                          | 2         | 0.19%   |
| Wacom                           | 1         | 0.1%    |
| TP-Link                         | 1         | 0.1%    |
| Qualcomm Atheros Communications | 1         | 0.1%    |
| Microsoft                       | 1         | 0.1%    |
| Linksys                         | 1         | 0.1%    |
| IMC Networks                    | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |
| D-Link System                   | 1         | 0.1%    |
| Chu Yuen Enterprise             | 1         | 0.1%    |
| Belkin Components               | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 72        | 6.81%   |
| Intel Wireless 7260                                            | 56        | 5.29%   |
| Intel Wi-Fi 6 AX200                                            | 51        | 4.82%   |
| Intel Wireless 7265                                            | 44        | 4.16%   |
| Intel Wireless 8260                                            | 39        | 3.69%   |
| Intel Wi-Fi 6 AX201                                            | 37        | 3.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 30        | 2.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 28        | 2.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 27        | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 26        | 2.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 24        | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 22        | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 20        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 19        | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 17        | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 17        | 1.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 17        | 1.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 16        | 1.51%   |
| Intel Wireless 3160                                            | 15        | 1.42%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 15        | 1.42%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 15        | 1.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 14        | 1.32%   |
| Intel Wireless-AC 9260                                         | 14        | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 1.32%   |
| Intel Centrino Advanced-N 6200                                 | 14        | 1.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 13        | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 13        | 1.23%   |
| Intel Centrino Advanced-N 6235                                 | 12        | 1.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 10        | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 0.95%   |
| Intel Centrino Wireless-N 2230                                 | 9         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                 | 9         | 0.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 9         | 0.85%   |
| Sierra Wireless EM7455                                         | 8         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8         | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 8         | 0.76%   |
| Realtek 802.11ac WLAN Adapter                                  | 7         | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 7         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 355       | 42.01%  |
| Intel                            | 293       | 34.67%  |
| Qualcomm Atheros                 | 59        | 6.98%   |
| Broadcom                         | 48        | 5.68%   |
| Broadcom Limited                 | 15        | 1.78%   |
| Marvell Technology Group         | 13        | 1.54%   |
| ASIX Electronics                 | 13        | 1.54%   |
| Lenovo                           | 11        | 1.3%    |
| DisplayLink                      | 7         | 0.83%   |
| Nvidia                           | 6         | 0.71%   |
| Huawei Technologies              | 5         | 0.59%   |
| Hewlett-Packard                  | 5         | 0.59%   |
| TP-Link                          | 2         | 0.24%   |
| Silicon Integrated Systems [SiS] | 2         | 0.24%   |
| Samsung Electronics              | 2         | 0.24%   |
| JMicron Technology               | 2         | 0.24%   |
| Xiaomi                           | 1         | 0.12%   |
| Qualcomm                         | 1         | 0.12%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.12%   |
| Microsoft                        | 1         | 0.12%   |
| ICS Advent                       | 1         | 0.12%   |
| Gemtek                           | 1         | 0.12%   |
| D-Link                           | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 246       | 28.84%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54        | 6.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45        | 5.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 5.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 2.58%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 2.46%   |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 2.46%   |
| Intel Ethernet Connection I219-LM                                 | 17        | 1.99%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 1.99%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 1.76%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 1.64%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 1.64%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 1.64%   |
| Intel Ethernet Connection I219-V                                  | 12        | 1.41%   |
| Intel Ethernet Connection (13) I219-V                             | 12        | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 1.29%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 1.29%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 1.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 1.06%   |
| Intel Ethernet Connection I217-V                                  | 9         | 1.06%   |
| Intel Ethernet Connection (6) I219-LM                             | 8         | 0.94%   |
| Intel 82566MM Gigabit Network Connection                          | 8         | 0.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.82%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.82%   |
| Intel Ethernet Connection (14) I219-LM                            | 6         | 0.7%    |
| DisplayLink Dell Universal Dock D6000                             | 6         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.59%   |
| Intel Ethernet Connection (5) I219-LM                             | 5         | 0.59%   |
| Huawei ANE-LX1                                                    | 5         | 0.59%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 5         | 0.59%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 5         | 0.59%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 5         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.47%   |
| Intel Ethernet Connection I218-V                                  | 4         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 993       | 53.94%  |
| Ethernet | 811       | 44.05%  |
| Modem    | 33        | 1.79%   |
| Unknown  | 4         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 815       | 75.88%  |
| Ethernet | 258       | 24.02%  |
| Unknown  | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 720       | 71.71%  |
| 1     | 267       | 26.59%  |
| 3     | 10        | 1%      |
| 0     | 7         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 952       | 94.07%  |
| Yes  | 60        | 5.93%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 446       | 53.48%  |
| Realtek Semiconductor           | 64        | 7.67%   |
| Qualcomm Atheros Communications | 56        | 6.71%   |
| Broadcom                        | 48        | 5.76%   |
| IMC Networks                    | 44        | 5.28%   |
| Foxconn / Hon Hai               | 38        | 4.56%   |
| Apple                           | 36        | 4.32%   |
| Lite-On Technology              | 28        | 3.36%   |
| Hewlett-Packard                 | 16        | 1.92%   |
| Dell                            | 16        | 1.92%   |
| ASUSTek Computer                | 10        | 1.2%    |
| Ralink                          | 7         | 0.84%   |
| Cambridge Silicon Radio         | 6         | 0.72%   |
| Toshiba                         | 5         | 0.6%    |
| Realtek                         | 3         | 0.36%   |
| MediaTek                        | 3         | 0.36%   |
| Ralink Technology               | 2         | 0.24%   |
| Chicony Electronics             | 2         | 0.24%   |
| USI                             | 1         | 0.12%   |
| Fujitsu                         | 1         | 0.12%   |
| Creative Technology             | 1         | 0.12%   |
| Alps Electric                   | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 213       | 25.45%  |
| Intel AX201 Bluetooth                               | 69        | 8.24%   |
| Intel AX200 Bluetooth                               | 50        | 5.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 49        | 5.85%   |
| Realtek Bluetooth Radio                             | 45        | 5.38%   |
| Apple Bluetooth Host Controller                     | 23        | 2.75%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 2.39%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 2.39%   |
| IMC Networks Bluetooth Radio                        | 19        | 2.27%   |
| Intel Bluetooth Device                              | 18        | 2.15%   |
| Qualcomm Atheros  Bluetooth Device                  | 15        | 1.79%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 1.79%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 1.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 12        | 1.43%   |
| Apple Bluetooth USB Host Controller                 | 12        | 1.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 11        | 1.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 1.31%   |
| Intel AX210 Bluetooth                               | 10        | 1.19%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 1.08%   |
| IMC Networks Wireless_Device                        | 9         | 1.08%   |
| Lite-On Bluetooth Device                            | 8         | 0.96%   |
| IMC Networks Bluetooth Device                       | 8         | 0.96%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.96%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.84%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.84%   |
| Broadcom HP Portable SoftSailing                    | 7         | 0.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 0.72%   |
| Broadcom HP Portable Bumble Bee                     | 6         | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.72%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.6%    |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.6%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 0.6%    |
| Dell DW375 Bluetooth Module                         | 5         | 0.6%    |
| Realtek RTL8723B Bluetooth                          | 4         | 0.48%   |
| Lite-On Wireless_Device                             | 4         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.48%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.48%   |
| Broadcom BCM20702A0                                 | 4         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 817       | 64.84%  |
| AMD                              | 188       | 14.92%  |
| Nvidia                           | 153       | 12.14%  |
| C-Media Electronics              | 14        | 1.11%   |
| Realtek Semiconductor            | 11        | 0.87%   |
| Logitech                         | 9         | 0.71%   |
| Lenovo                           | 8         | 0.63%   |
| Plantronics                      | 6         | 0.48%   |
| Kingston Technology              | 5         | 0.4%    |
| GN Netcom                        | 5         | 0.4%    |
| Hewlett-Packard                  | 4         | 0.32%   |
| Silicon Integrated Systems [SiS] | 3         | 0.24%   |
| SAVITECH                         | 3         | 0.24%   |
| RODE Microphones                 | 3         | 0.24%   |
| Apple                            | 3         | 0.24%   |
| Texas Instruments                | 2         | 0.16%   |
| SteelSeries ApS                  | 2         | 0.16%   |
| DSEA A/S                         | 2         | 0.16%   |
| Creative Technology              | 2         | 0.16%   |
| XMOS                             | 1         | 0.08%   |
| Unknown                          | 1         | 0.08%   |
| SlrTek                           | 1         | 0.08%   |
| Samson Technologies              | 1         | 0.08%   |
| QinHeng Electronics              | 1         | 0.08%   |
| PreSonus Audio Electronics       | 1         | 0.08%   |
| No brand                         | 1         | 0.08%   |
| Line6                            | 1         | 0.08%   |
| LG Electronics                   | 1         | 0.08%   |
| JMTek                            | 1         | 0.08%   |
| JBL                              | 1         | 0.08%   |
| GYROCOM C&C                      | 1         | 0.08%   |
| Generalplus Technology           | 1         | 0.08%   |
| Focusrite-Novation               | 1         | 0.08%   |
| Elite Silicon                    | 1         | 0.08%   |
| Digidesign                       | 1         | 0.08%   |
| Corsair                          | 1         | 0.08%   |
| Conexant Systems                 | 1         | 0.08%   |
| ASUSTek Computer                 | 1         | 0.08%   |
| Asahi Kasei Microsystems         | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 131       | 8.55%   |
| AMD Family 17h/19h HD Audio Controller                                     | 96        | 6.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 83        | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 58        | 3.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 56        | 3.65%   |
| Intel 8 Series HD Audio Controller                                         | 56        | 3.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 54        | 3.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 50        | 3.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 48        | 3.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 45        | 2.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 45        | 2.94%   |
| Intel Broadwell-U Audio Controller                                         | 45        | 2.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 40        | 2.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 39        | 2.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 34        | 2.22%   |
| AMD FCH Azalia Controller                                                  | 30        | 1.96%   |
| Intel CM238 HD Audio Controller                                            | 28        | 1.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 28        | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 1.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 23        | 1.5%    |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                   | 20        | 1.3%    |
| Intel Comet Lake PCH cAVS                                                  | 18        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 16        | 1.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 16        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 15        | 0.98%   |
| Nvidia GK107 HDMI Audio Controller                                         | 15        | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                              | 15        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 13        | 0.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 0.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13        | 0.85%   |
| Nvidia High Definition Audio Controller                                    | 12        | 0.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 12        | 0.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 12        | 0.78%   |
| Realtek Semiconductor USB Audio                                            | 11        | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                              | 11        | 0.72%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 11        | 0.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 9         | 0.59%   |
| Nvidia GA106 High Definition Audio Controller                              | 9         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 192       | 31.58%  |
| SK hynix            | 139       | 22.86%  |
| Micron Technology   | 97        | 15.95%  |
| Kingston            | 45        | 7.4%    |
| Unknown             | 37        | 6.09%   |
| Corsair             | 22        | 3.62%   |
| Crucial             | 17        | 2.8%    |
| Ramaxel Technology  | 13        | 2.14%   |
| Elpida              | 10        | 1.64%   |
| A-DATA Technology   | 10        | 1.64%   |
| Unknown             | 5         | 0.82%   |
| Nanya Technology    | 4         | 0.66%   |
| Unknown (ABCD)      | 2         | 0.33%   |
| Team                | 2         | 0.33%   |
| Patriot             | 2         | 0.33%   |
| GSkill              | 2         | 0.33%   |
| TEXTORM             | 1         | 0.16%   |
| Qimonda             | 1         | 0.16%   |
| Netlist             | 1         | 0.16%   |
| GOODRAM             | 1         | 0.16%   |
| G.Skill             | 1         | 0.16%   |
| fef5                | 1         | 0.16%   |
| Avant               | 1         | 0.16%   |
| ASint Technology    | 1         | 0.16%   |
| Apacer              | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 1.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 1.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 1.54%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 1.39%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 7         | 1.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 1.08%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 1.08%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.92%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.92%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.77%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.77%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 5         | 0.77%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 5         | 0.77%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 5         | 0.77%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.77%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 5         | 0.77%   |
| Unknown                                                          | 5         | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 4         | 0.62%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.62%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.62%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 4         | 0.62%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.62%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.62%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.62%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.62%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 4         | 0.62%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 4         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 3         | 0.46%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.46%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.46%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 3         | 0.46%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1334MT/s        | 3         | 0.46%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 231       | 42.78%  |
| DDR3    | 188       | 34.81%  |
| LPDDR4  | 41        | 7.59%   |
| LPDDR3  | 30        | 5.56%   |
| DDR2    | 20        | 3.7%    |
| SDRAM   | 9         | 1.67%   |
| DDR5    | 9         | 1.67%   |
| LPDDR5  | 5         | 0.93%   |
| Unknown | 3         | 0.56%   |
| DRAM    | 2         | 0.37%   |
| DDR     | 2         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 464       | 84.98%  |
| Row Of Chips | 69        | 12.64%  |
| Chip         | 9         | 1.65%   |
| Unknown      | 3         | 0.55%   |
| DIMM         | 1         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 227       | 38.94%  |
| 4096  | 141       | 24.19%  |
| 16384 | 116       | 19.9%   |
| 2048  | 76        | 13.04%  |
| 32768 | 12        | 2.06%   |
| 1024  | 9         | 1.54%   |
| 512   | 2         | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 138       | 23.96%  |
| 3200    | 96        | 16.67%  |
| 2667    | 96        | 16.67%  |
| 2133    | 43        | 7.47%   |
| 2400    | 38        | 6.6%    |
| 1334    | 24        | 4.17%   |
| 4267    | 23        | 3.99%   |
| 1333    | 18        | 3.13%   |
| 667     | 13        | 2.26%   |
| 1867    | 12        | 2.08%   |
| Unknown | 12        | 2.08%   |
| 4266    | 10        | 1.74%   |
| 4800    | 8         | 1.39%   |
| 3266    | 7         | 1.22%   |
| 1067    | 7         | 1.22%   |
| 6400    | 6         | 1.04%   |
| 4199    | 5         | 0.87%   |
| 800     | 4         | 0.69%   |
| 8400    | 3         | 0.52%   |
| 3733    | 2         | 0.35%   |
| 2048    | 2         | 0.35%   |
| 1066    | 2         | 0.35%   |
| 975     | 2         | 0.35%   |
| 5600    | 1         | 0.17%   |
| 1639    | 1         | 0.17%   |
| 533     | 1         | 0.17%   |
| 333     | 1         | 0.17%   |
| 266     | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 50%     |
| Samsung Electronics | 2         | 25%     |
| Oki Data            | 1         | 12.5%   |
| Brother Industries  | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung SCX-3200 Series      | 1         | 12.5%   |
| Samsung M2070 Series         | 1         | 12.5%   |
| Oki Data USB Device          | 1         | 12.5%   |
| HP LaserJet P2035            | 1         | 12.5%   |
| HP ENVY 4520 series          | 1         | 12.5%   |
| HP DeskJet 5650c             | 1         | 12.5%   |
| HP DeskJet 2700 series       | 1         | 12.5%   |
| Brother QL-500 label printer | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP ScanJet 2200c        | 1         | 33.33%  |
| Canon CanoScan LiDE 100 | 1         | 33.33%  |
| Canon CanoScan 4400F    | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 234       | 26.56%  |
| Microdia                               | 93        | 10.56%  |
| IMC Networks                           | 83        | 9.42%   |
| Realtek Semiconductor                  | 67        | 7.6%    |
| Bison Electronics                      | 51        | 5.79%   |
| Sunplus Innovation Technology          | 43        | 4.88%   |
| Cheng Uei Precision Industry (Foxlink) | 41        | 4.65%   |
| Lite-On Technology                     | 35        | 3.97%   |
| Quanta                                 | 34        | 3.86%   |
| Acer                                   | 31        | 3.52%   |
| Apple                                  | 30        | 3.41%   |
| Suyin                                  | 24        | 2.72%   |
| Syntek                                 | 21        | 2.38%   |
| Logitech                               | 14        | 1.59%   |
| Ricoh                                  | 10        | 1.14%   |
| Luxvisions Innotech Limited            | 10        | 1.14%   |
| Lenovo                                 | 9         | 1.02%   |
| Alcor Micro                            | 8         | 0.91%   |
| Silicon Motion                         | 6         | 0.68%   |
| ALi                                    | 6         | 0.68%   |
| Samsung Electronics                    | 5         | 0.57%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.34%   |
| Primax Electronics                     | 3         | 0.34%   |
| DigiTech                               | 3         | 0.34%   |
| Sunplus Technology                     | 2         | 0.23%   |
| Sonix Technology                       | 2         | 0.23%   |
| Importek                               | 2         | 0.23%   |
| Creative Technology                    | 2         | 0.23%   |
| Z-Star Microelectronics                | 1         | 0.11%   |
| SunplusIT                              | 1         | 0.11%   |
| Polycom                                | 1         | 0.11%   |
| Microsoft                              | 1         | 0.11%   |
| LG Electronics                         | 1         | 0.11%   |
| Intel                                  | 1         | 0.11%   |
| Generalplus Technology                 | 1         | 0.11%   |
| Etron Technology                       | 1         | 0.11%   |
| BRS 2Mp Camera                         | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 57        | 6.43%   |
| Microdia Integrated_Webcam_HD                                            | 45        | 5.08%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 33        | 3.72%   |
| Realtek Integrated_Webcam_HD                                             | 25        | 2.82%   |
| IMC Networks Integrated Camera                                           | 24        | 2.71%   |
| Chicony HP HD Camera                                                     | 19        | 2.14%   |
| Chicony HD WebCam                                                        | 19        | 2.14%   |
| Lite-On HP HD Camera                                                     | 16        | 1.81%   |
| Bison Integrated Camera                                                  | 16        | 1.81%   |
| Syntek Integrated Camera                                                 | 14        | 1.58%   |
| Sunplus HD WebCam                                                        | 12        | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 12        | 1.35%   |
| Sunplus Integrated_Webcam_HD                                             | 11        | 1.24%   |
| Bison Lenovo EasyCamera                                                  | 11        | 1.24%   |
| Quanta HP HD Camera                                                      | 10        | 1.13%   |
| Lite-On Integrated Camera                                                | 10        | 1.13%   |
| Bison SunplusIT Integrated Camera                                        | 10        | 1.13%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                          | 10        | 1.13%   |
| Chicony HP HD Webcam                                                     | 9         | 1.02%   |
| Apple FaceTime HD Camera                                                 | 9         | 1.02%   |
| Quanta HD User Facing                                                    | 8         | 0.9%    |
| Chicony HP HD Webcam [Fixed]                                             | 8         | 0.9%    |
| Syntek Lenovo EasyCamera                                                 | 7         | 0.79%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 7         | 0.79%   |
| Chicony Integrated HP HD Webcam                                          | 7         | 0.79%   |
| Chicony HP Truevision HD                                                 | 7         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 7         | 0.79%   |
| Realtek USB2.0 HD UVC WebCam                                             | 6         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 6         | 0.68%   |
| Chicony USB2.0 HD UVC WebCam                                             | 6         | 0.68%   |
| Chicony USB2.0 Camera                                                    | 6         | 0.68%   |
| Chicony HD User Facing                                                   | 6         | 0.68%   |
| Acer Integrated Camera                                                   | 6         | 0.68%   |
| Suyin HP TrueVision HD                                                   | 5         | 0.56%   |
| Sunplus Laptop Integrated WebCam HD                                      | 5         | 0.56%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 5         | 0.56%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 5         | 0.56%   |
| Realtek USB Camera                                                       | 5         | 0.56%   |
| Realtek Integrated Webcam_HD                                             | 5         | 0.56%   |
| Quanta HP TrueVision HD Camera                                           | 5         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 115       | 47.13%  |
| Synaptics                  | 65        | 26.64%  |
| Shenzhen Goodix Technology | 20        | 8.2%    |
| Upek                       | 11        | 4.51%   |
| Elan Microelectronics      | 11        | 4.51%   |
| AuthenTec                  | 11        | 4.51%   |
| STMicroelectronics         | 6         | 2.46%   |
| LighTuning Technology      | 5         | 2.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 17.21%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 6.97%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 6.15%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 6.15%   |
| Shenzhen Goodix FingerPrint                                                | 13        | 5.33%   |
| Validity Sensors VFS491                                                    | 11        | 4.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 4.1%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 3.69%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 3.28%   |
| Elan ELAN:Fingerprint                                                      | 8         | 3.28%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.87%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 2.87%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.46%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.05%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 2.05%   |
| AuthenTec AES2810                                                          | 5         | 2.05%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 2.05%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.64%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.64%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 1.64%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.23%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.23%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.23%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.82%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.82%   |
| Synaptics WBDI                                                             | 2         | 0.82%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.82%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 0.82%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.82%   |
| Unknown                                                                    | 2         | 0.82%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.41%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.41%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.41%   |
| Synaptics WBDI Device                                                      | 1         | 0.41%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.41%   |
| Synaptics  WBDI                                                            | 1         | 0.41%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 59        | 43.07%  |
| Broadcom    | 57        | 41.61%  |
| O2 Micro    | 11        | 8.03%   |
| Lenovo      | 5         | 3.65%   |
| Upek        | 4         | 2.92%   |
| Yubico.com  | 1         | 0.73%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 59        | 43.07%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 12.41%  |
| Broadcom 58200                                                               | 16        | 11.68%  |
| Broadcom 5880                                                                | 12        | 8.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 8.03%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 6.57%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.65%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.92%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.46%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.73%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.73%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 543       | 52.72%  |
| 1     | 368       | 35.73%  |
| 2     | 105       | 10.19%  |
| 3     | 10        | 0.97%   |
| 4     | 3         | 0.29%   |
| 7     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 244       | 40.13%  |
| Chipcard                 | 125       | 20.56%  |
| Graphics card            | 79        | 12.99%  |
| Net/wireless             | 47        | 7.73%   |
| Multimedia controller    | 36        | 5.92%   |
| Camera                   | 20        | 3.29%   |
| Bluetooth                | 18        | 2.96%   |
| Communication controller | 13        | 2.14%   |
| Sound                    | 6         | 0.99%   |
| Card reader              | 5         | 0.82%   |
| Storage                  | 4         | 0.66%   |
| Net/ethernet             | 4         | 0.66%   |
| Modem                    | 2         | 0.33%   |
| Flash memory             | 2         | 0.33%   |
| Storage/nvme             | 1         | 0.16%   |
| Storage/ide              | 1         | 0.16%   |
| Storage/ata              | 1         | 0.16%   |

