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

Total: 1945

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 440 14 inch G9 N... | [6ac93f82e9](https://linux-hardware.org/?probe=6ac93f82e9) | May 08, 2024 |
| MSI           | GF63 Thin 10SC              | [d419afc35f](https://linux-hardware.org/?probe=d419afc35f) | May 08, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [276faea129](https://linux-hardware.org/?probe=276faea129) | May 06, 2024 |
| MSI           | Alpha 17 B5EEK              | [8f78e61ba3](https://linux-hardware.org/?probe=8f78e61ba3) | May 06, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [d73bdd4b76](https://linux-hardware.org/?probe=d73bdd4b76) | May 06, 2024 |
| MSI           | Alpha 17 B5EEK              | [38d719b3cc](https://linux-hardware.org/?probe=38d719b3cc) | May 05, 2024 |
| Fujitsu       | LIFEBOOK T900               | [d396d19b06](https://linux-hardware.org/?probe=d396d19b06) | May 05, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [b950303950](https://linux-hardware.org/?probe=b950303950) | May 04, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [f4e6daf83f](https://linux-hardware.org/?probe=f4e6daf83f) | May 04, 2024 |
| HP            | EliteBook 820 G3            | [73f06a8daf](https://linux-hardware.org/?probe=73f06a8daf) | May 03, 2024 |
| ASUSTek       | G75VW                       | [151ab0d8e9](https://linux-hardware.org/?probe=151ab0d8e9) | May 01, 2024 |
| HP            | EliteBook 8570p             | [03f63c8caf](https://linux-hardware.org/?probe=03f63c8caf) | Apr 29, 2024 |
| HP            | EliteBook 8570p             | [5c699c7770](https://linux-hardware.org/?probe=5c699c7770) | Apr 29, 2024 |
| Dell          | Latitude 5540               | [71894c9703](https://linux-hardware.org/?probe=71894c9703) | Apr 29, 2024 |
| ASUSTek       | UX32VD                      | [1377417777](https://linux-hardware.org/?probe=1377417777) | Apr 29, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [40c7e6e4a3](https://linux-hardware.org/?probe=40c7e6e4a3) | Apr 28, 2024 |
| Acer          | Swift SF314-41              | [240aeeb256](https://linux-hardware.org/?probe=240aeeb256) | Apr 28, 2024 |
| Acer          | Nitro AN16-41               | [4cfb726ac6](https://linux-hardware.org/?probe=4cfb726ac6) | Apr 23, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [72b47f3d18](https://linux-hardware.org/?probe=72b47f3d18) | Apr 23, 2024 |
| Lenovo        | Legion 7 16IAX7 82TD        | [7c88cac728](https://linux-hardware.org/?probe=7c88cac728) | Apr 22, 2024 |
| Dell          | XPS 15 9530                 | [500ffeec7b](https://linux-hardware.org/?probe=500ffeec7b) | Apr 22, 2024 |
| Samsung       | N150/N210/N220              | [73f5edc5e5](https://linux-hardware.org/?probe=73f5edc5e5) | Apr 22, 2024 |
| Dell          | XPS 9320                    | [162d7ddcd3](https://linux-hardware.org/?probe=162d7ddcd3) | Apr 22, 2024 |
| Lenovo        | Z50-75 80EC                 | [62fb9d9789](https://linux-hardware.org/?probe=62fb9d9789) | Apr 21, 2024 |
| Acer          | Swift SF514-52T             | [d89f8a89a9](https://linux-hardware.org/?probe=d89f8a89a9) | Apr 20, 2024 |
| Lenovo        | ThinkPad X270 20HN0016MX    | [cd5fff4dcd](https://linux-hardware.org/?probe=cd5fff4dcd) | Apr 20, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [3c9edd18cd](https://linux-hardware.org/?probe=3c9edd18cd) | Apr 19, 2024 |
| Acer          | Swift SF314-71              | [4dbbe8a263](https://linux-hardware.org/?probe=4dbbe8a263) | Apr 18, 2024 |
| HP            | OMEN by Laptop 17-cb0xxx    | [50987e4554](https://linux-hardware.org/?probe=50987e4554) | Apr 18, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [3d43cbd697](https://linux-hardware.org/?probe=3d43cbd697) | Apr 17, 2024 |
| MSI           | GL75 9SEK                   | [3d679e4ec2](https://linux-hardware.org/?probe=3d679e4ec2) | Apr 17, 2024 |
| MSI           | GL75 9SEK                   | [b2d528d9b4](https://linux-hardware.org/?probe=b2d528d9b4) | Apr 16, 2024 |
| ASUSTek       | G75VW                       | [21e80243e1](https://linux-hardware.org/?probe=21e80243e1) | Apr 11, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1450416558](https://linux-hardware.org/?probe=1450416558) | Apr 11, 2024 |
| Acer          | Aspire ES1-311              | [cd38e8b3bd](https://linux-hardware.org/?probe=cd38e8b3bd) | Apr 09, 2024 |
| HP            | ProBook 430 G3              | [2dff62b8e0](https://linux-hardware.org/?probe=2dff62b8e0) | Apr 09, 2024 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [543136ea4b](https://linux-hardware.org/?probe=543136ea4b) | Apr 08, 2024 |
| Apple         | MacBookPro5,4               | [3ab1d66e10](https://linux-hardware.org/?probe=3ab1d66e10) | Apr 08, 2024 |
| ASUSTek       | G752VSK                     | [49116bb834](https://linux-hardware.org/?probe=49116bb834) | Apr 08, 2024 |
| Dell          | Latitude E7450              | [80c9756b52](https://linux-hardware.org/?probe=80c9756b52) | Apr 08, 2024 |
| Acer          | Predator PH315-54           | [23dae5c2e2](https://linux-hardware.org/?probe=23dae5c2e2) | Apr 07, 2024 |
| Dell          | Latitude 5401               | [50c9a92ed4](https://linux-hardware.org/?probe=50c9a92ed4) | Apr 07, 2024 |
| Apple         | MacBookPro12,1              | [50c4a83180](https://linux-hardware.org/?probe=50c4a83180) | Apr 07, 2024 |
| Lenovo        | ThinkPad T490s 20NX0056M... | [3945b47d9b](https://linux-hardware.org/?probe=3945b47d9b) | Apr 07, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [b743bdc5b7](https://linux-hardware.org/?probe=b743bdc5b7) | Apr 06, 2024 |
| Acer          | Aspire ES1-311              | [9a68d90ab7](https://linux-hardware.org/?probe=9a68d90ab7) | Apr 05, 2024 |
| HP            | ZBook Studio 15.6 inch G... | [eb1f637530](https://linux-hardware.org/?probe=eb1f637530) | Apr 04, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [91906af7e3](https://linux-hardware.org/?probe=91906af7e3) | Apr 03, 2024 |
| HP            | EliteBook 840 G3            | [3ddde931c2](https://linux-hardware.org/?probe=3ddde931c2) | Apr 03, 2024 |
| HP            | Laptop 15-db0xxx            | [86bf1e5346](https://linux-hardware.org/?probe=86bf1e5346) | Apr 03, 2024 |
| Lenovo        | ThinkPad X280 20KF001RMX    | [0caddb11a4](https://linux-hardware.org/?probe=0caddb11a4) | Apr 02, 2024 |
| Apple         | MacBookPro15,2              | [fb59e4c861](https://linux-hardware.org/?probe=fb59e4c861) | Apr 01, 2024 |
| Apple         | MacBookPro11,2              | [7ccfbb7054](https://linux-hardware.org/?probe=7ccfbb7054) | Mar 31, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [63f04a080c](https://linux-hardware.org/?probe=63f04a080c) | Mar 31, 2024 |
| ASUSTek       | G75VW                       | [cff197ffbf](https://linux-hardware.org/?probe=cff197ffbf) | Mar 30, 2024 |
| Lenovo        | ThinkPad R400 7440WWQ       | [7c62efd0a5](https://linux-hardware.org/?probe=7c62efd0a5) | Mar 29, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [400955763a](https://linux-hardware.org/?probe=400955763a) | Mar 28, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [eb09797dad](https://linux-hardware.org/?probe=eb09797dad) | Mar 25, 2024 |
| MSI           | Bravo 15 C7UDX              | [6fb8db02b9](https://linux-hardware.org/?probe=6fb8db02b9) | Mar 25, 2024 |
| Lenovo        | VIWGQ                       | [881674c100](https://linux-hardware.org/?probe=881674c100) | Mar 24, 2024 |
| HP            | 15                          | [139e556699](https://linux-hardware.org/?probe=139e556699) | Mar 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [4d1bc02be0](https://linux-hardware.org/?probe=4d1bc02be0) | Mar 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [0f6120fef2](https://linux-hardware.org/?probe=0f6120fef2) | Mar 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a20d8894bd](https://linux-hardware.org/?probe=a20d8894bd) | Mar 23, 2024 |
| HP            | ZBook 15 G2                 | [2ba706d8c9](https://linux-hardware.org/?probe=2ba706d8c9) | Mar 21, 2024 |
| Dell          | Precision M4600             | [ae97b86b04](https://linux-hardware.org/?probe=ae97b86b04) | Mar 20, 2024 |
| HP            | ZBook 15 G4                 | [1752ff36c3](https://linux-hardware.org/?probe=1752ff36c3) | Mar 20, 2024 |
| Dell          | Precision M4800             | [a6e69c7950](https://linux-hardware.org/?probe=a6e69c7950) | Mar 20, 2024 |
| HP            | EliteBook 840 G4            | [d6c0c2ac98](https://linux-hardware.org/?probe=d6c0c2ac98) | Mar 20, 2024 |
| eMachines     | eME642G                     | [8759a11aca](https://linux-hardware.org/?probe=8759a11aca) | Mar 20, 2024 |
| HP            | ProBook 440 G6              | [15167e6cda](https://linux-hardware.org/?probe=15167e6cda) | Mar 19, 2024 |
| Dell          | XPS 13 7390                 | [bd22d0e0ca](https://linux-hardware.org/?probe=bd22d0e0ca) | Mar 18, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [4ade0c63a8](https://linux-hardware.org/?probe=4ade0c63a8) | Mar 17, 2024 |
| Lenovo        | Legion 9 16IRX8 83AG        | [ca665b8165](https://linux-hardware.org/?probe=ca665b8165) | Mar 16, 2024 |
| System76      | Gazelle                     | [e4a975b366](https://linux-hardware.org/?probe=e4a975b366) | Mar 16, 2024 |
| eMachines     | eME642G                     | [7d7230a747](https://linux-hardware.org/?probe=7d7230a747) | Mar 16, 2024 |
| HP            | Pavilion Laptop 14-bf0xx    | [7ded8b5e80](https://linux-hardware.org/?probe=7ded8b5e80) | Mar 15, 2024 |
| MSI           | Bravo 15 C7UDX              | [4441dff3bf](https://linux-hardware.org/?probe=4441dff3bf) | Mar 15, 2024 |
| Unknown       | Unknown                     | [a4e49121d0](https://linux-hardware.org/?probe=a4e49121d0) | Mar 15, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [2d1ccd0458](https://linux-hardware.org/?probe=2d1ccd0458) | Mar 15, 2024 |
| Samsung       | 940XFG                      | [b60ac199c7](https://linux-hardware.org/?probe=b60ac199c7) | Mar 15, 2024 |
| Samsung       | 940XFG                      | [2698d3e097](https://linux-hardware.org/?probe=2698d3e097) | Mar 15, 2024 |
| HP            | Pavilion 15                 | [520fd1241e](https://linux-hardware.org/?probe=520fd1241e) | Mar 14, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [944358baac](https://linux-hardware.org/?probe=944358baac) | Mar 11, 2024 |
| Apple         | MacBookAir7,2               | [89b268f1f8](https://linux-hardware.org/?probe=89b268f1f8) | Mar 11, 2024 |
| Valve         | Jupiter                     | [0a31a36586](https://linux-hardware.org/?probe=0a31a36586) | Mar 10, 2024 |
| ASUSTek       | G75VW                       | [c22c7f9510](https://linux-hardware.org/?probe=c22c7f9510) | Mar 10, 2024 |
| Toshiba       | Satellite L650              | [46a8d42eaa](https://linux-hardware.org/?probe=46a8d42eaa) | Mar 10, 2024 |
| Dell          | Latitude E6420              | [7ae5cc22b0](https://linux-hardware.org/?probe=7ae5cc22b0) | Mar 09, 2024 |
| Dell          | XPS 13 9370                 | [96e1e8d964](https://linux-hardware.org/?probe=96e1e8d964) | Mar 07, 2024 |
| Dell          | Latitude 7390               | [7eed1415ba](https://linux-hardware.org/?probe=7eed1415ba) | Mar 05, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | [6fd9429f1c](https://linux-hardware.org/?probe=6fd9429f1c) | Mar 05, 2024 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [dee02a2e0f](https://linux-hardware.org/?probe=dee02a2e0f) | Mar 04, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [78090262bb](https://linux-hardware.org/?probe=78090262bb) | Mar 02, 2024 |
| Acer          | Predator PT516-51s          | [f3e05a8ef2](https://linux-hardware.org/?probe=f3e05a8ef2) | Feb 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [88e7a5c628](https://linux-hardware.org/?probe=88e7a5c628) | Feb 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a387b3439f](https://linux-hardware.org/?probe=a387b3439f) | Feb 29, 2024 |
| HP            | Pavilion Laptop 14-bf0xx    | [7a9345dd2c](https://linux-hardware.org/?probe=7a9345dd2c) | Feb 28, 2024 |
| LG Electro... | 15Z980-A.AAS7U1             | [845caa9a4d](https://linux-hardware.org/?probe=845caa9a4d) | Feb 28, 2024 |
| IBM           | ThinkPad T43 18714AG        | [ac4a5c44a6](https://linux-hardware.org/?probe=ac4a5c44a6) | Feb 28, 2024 |
| Dell          | Latitude E6430              | [1121d113bf](https://linux-hardware.org/?probe=1121d113bf) | Feb 26, 2024 |
| Dell          | Latitude E6430              | [860bbdc112](https://linux-hardware.org/?probe=860bbdc112) | Feb 26, 2024 |
| Lenovo        | ThinkPad X260 20F6009SMS    | [027f3ceeb3](https://linux-hardware.org/?probe=027f3ceeb3) | Feb 26, 2024 |
| Lenovo        | ThinkPad L412 44034KG       | [93c5498399](https://linux-hardware.org/?probe=93c5498399) | Feb 25, 2024 |
| HP            | EliteBook 850 G6            | [7ed2cffcae](https://linux-hardware.org/?probe=7ed2cffcae) | Feb 23, 2024 |
| HP            | Laptop 15-db0xxx            | [8808c41478](https://linux-hardware.org/?probe=8808c41478) | Feb 22, 2024 |
| Dell          | Latitude E5420              | [910bc98f57](https://linux-hardware.org/?probe=910bc98f57) | Feb 21, 2024 |
| HP            | EliteBook 840 G3            | [aef715ec84](https://linux-hardware.org/?probe=aef715ec84) | Feb 20, 2024 |
| HP            | EliteBook 840 G3            | [8287dc23bb](https://linux-hardware.org/?probe=8287dc23bb) | Feb 20, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | [760267fc7e](https://linux-hardware.org/?probe=760267fc7e) | Feb 20, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [78587a5ad4](https://linux-hardware.org/?probe=78587a5ad4) | Feb 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [b5e81cd1b4](https://linux-hardware.org/?probe=b5e81cd1b4) | Feb 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [04c342c7e3](https://linux-hardware.org/?probe=04c342c7e3) | Feb 20, 2024 |
| Dell          | Latitude E7250              | [4dbb95d349](https://linux-hardware.org/?probe=4dbb95d349) | Feb 19, 2024 |
| HP            | Compaq nx7400 (RU427ET#A... | [3eb06482d0](https://linux-hardware.org/?probe=3eb06482d0) | Feb 19, 2024 |
| Acer          | Swift SFG14-72              | [24e5b8861c](https://linux-hardware.org/?probe=24e5b8861c) | Feb 19, 2024 |
| HP            | Compaq nx7400 (RU427ET#A... | [c00066136f](https://linux-hardware.org/?probe=c00066136f) | Feb 19, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | [5b768d1518](https://linux-hardware.org/?probe=5b768d1518) | Feb 18, 2024 |
| ASUSTek       | G75VW                       | [ff0a6068a5](https://linux-hardware.org/?probe=ff0a6068a5) | Feb 17, 2024 |
| ASUSTek       | G75VW                       | [5ad9c09f49](https://linux-hardware.org/?probe=5ad9c09f49) | Feb 16, 2024 |
| Acer          | Aspire S3                   | [015a6bdb09](https://linux-hardware.org/?probe=015a6bdb09) | Feb 16, 2024 |
| HP            | EliteBook 820 G3            | [c9895bde68](https://linux-hardware.org/?probe=c9895bde68) | Feb 14, 2024 |
| HP            | EliteBook 820 G3            | [7fe1594df6](https://linux-hardware.org/?probe=7fe1594df6) | Feb 14, 2024 |
| ASUSTek       | G75VW                       | [a829d5fb44](https://linux-hardware.org/?probe=a829d5fb44) | Feb 14, 2024 |
| Lenovo        | ThinkPad X280 20KF001JMX    | [d370fcec49](https://linux-hardware.org/?probe=d370fcec49) | Feb 13, 2024 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [908b0efb23](https://linux-hardware.org/?probe=908b0efb23) | Feb 11, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [166c275408](https://linux-hardware.org/?probe=166c275408) | Feb 10, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | [8e506a8c7e](https://linux-hardware.org/?probe=8e506a8c7e) | Feb 09, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [1c4b5365af](https://linux-hardware.org/?probe=1c4b5365af) | Feb 07, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [63843cbf43](https://linux-hardware.org/?probe=63843cbf43) | Feb 07, 2024 |
| Dell          | XPS 13 9370                 | [d29438d6d7](https://linux-hardware.org/?probe=d29438d6d7) | Feb 06, 2024 |
| HP            | EliteBook 8570w             | [4a1938d727](https://linux-hardware.org/?probe=4a1938d727) | Feb 06, 2024 |
| HP            | ZBook 15u G2                | [28b76e7488](https://linux-hardware.org/?probe=28b76e7488) | Feb 06, 2024 |
| Apple         | MacBookPro8,2               | [69a19c7a1d](https://linux-hardware.org/?probe=69a19c7a1d) | Feb 06, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [72e1aa0f99](https://linux-hardware.org/?probe=72e1aa0f99) | Feb 06, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [34e9a5b730](https://linux-hardware.org/?probe=34e9a5b730) | Feb 04, 2024 |
| HP            | EliteBook 8570w             | [57f28e0095](https://linux-hardware.org/?probe=57f28e0095) | Feb 04, 2024 |
| ASUSTek       | UX430UAR                    | [cc89a20253](https://linux-hardware.org/?probe=cc89a20253) | Feb 04, 2024 |
| Fujitsu Si... | AMILO Li3910                | [ecde56e2bb](https://linux-hardware.org/?probe=ecde56e2bb) | Feb 04, 2024 |
| Unknown       | Apple MacBook Air (M1, 2... | [c16e6118de](https://linux-hardware.org/?probe=c16e6118de) | Feb 03, 2024 |
| Apple         | MacBookPro8,2               | [47c6ea83ea](https://linux-hardware.org/?probe=47c6ea83ea) | Feb 03, 2024 |
| HP            | ZBook 15 G4                 | [72ea56fdbe](https://linux-hardware.org/?probe=72ea56fdbe) | Feb 03, 2024 |
| Schenker      | XMG APEX 15 MAX (E22)       | [cf8a09526d](https://linux-hardware.org/?probe=cf8a09526d) | Jan 30, 2024 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [aecdf1facc](https://linux-hardware.org/?probe=aecdf1facc) | Jan 30, 2024 |
| Gigabyte      | AORUS 15P XD                | [72e109e02a](https://linux-hardware.org/?probe=72e109e02a) | Jan 30, 2024 |
| Dell          | G3 3590                     | [7fb3fcb32c](https://linux-hardware.org/?probe=7fb3fcb32c) | Jan 28, 2024 |
| Dell          | Inspiron 13-5378            | [a742fdf96d](https://linux-hardware.org/?probe=a742fdf96d) | Jan 27, 2024 |
| Gigabyte      | AORUS 15P XD                | [fc6193b5bf](https://linux-hardware.org/?probe=fc6193b5bf) | Jan 26, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c2be9790ea](https://linux-hardware.org/?probe=c2be9790ea) | Jan 25, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [362ad8ae7e](https://linux-hardware.org/?probe=362ad8ae7e) | Jan 24, 2024 |
| Lenovo        | ThinkPad X270 20HN0012MX    | [ac867529fa](https://linux-hardware.org/?probe=ac867529fa) | Jan 24, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [15666b6776](https://linux-hardware.org/?probe=15666b6776) | Jan 23, 2024 |
| Acer          | Aspire E5-551G              | [c4bd469e8d](https://linux-hardware.org/?probe=c4bd469e8d) | Jan 19, 2024 |
| HP            | Pavilion g6                 | [bac27c78e2](https://linux-hardware.org/?probe=bac27c78e2) | Jan 19, 2024 |
| HP            | Pavilion g6                 | [30da02f122](https://linux-hardware.org/?probe=30da02f122) | Jan 19, 2024 |
| Apple         | MacBookPro6,2               | [d39ea787aa](https://linux-hardware.org/?probe=d39ea787aa) | Jan 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [187a8a84af](https://linux-hardware.org/?probe=187a8a84af) | Jan 18, 2024 |
| Dell          | Precision 5680              | [f52bddf877](https://linux-hardware.org/?probe=f52bddf877) | Jan 18, 2024 |
| Dell          | Precision 5680              | [2585a4f840](https://linux-hardware.org/?probe=2585a4f840) | Jan 18, 2024 |
| Lenovo        | ThinkPad X260 20F5S0NV00    | [cda7600532](https://linux-hardware.org/?probe=cda7600532) | Jan 18, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [694f38f139](https://linux-hardware.org/?probe=694f38f139) | Jan 16, 2024 |
| Unknown       | A70M                        | [b6a6c2e947](https://linux-hardware.org/?probe=b6a6c2e947) | Jan 14, 2024 |
| Apple         | MacBookAir3,1               | [043258f53d](https://linux-hardware.org/?probe=043258f53d) | Jan 14, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | [d2db433ab2](https://linux-hardware.org/?probe=d2db433ab2) | Jan 12, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [0d7230b853](https://linux-hardware.org/?probe=0d7230b853) | Jan 11, 2024 |
| Valve         | Jupiter                     | [ab13227de0](https://linux-hardware.org/?probe=ab13227de0) | Jan 10, 2024 |
| Acer          | Aspire 6530G                | [184836d752](https://linux-hardware.org/?probe=184836d752) | Jan 09, 2024 |
| HP            | ZBook 17 G4                 | [5dc1550956](https://linux-hardware.org/?probe=5dc1550956) | Jan 09, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [96d648fbd8](https://linux-hardware.org/?probe=96d648fbd8) | Jan 07, 2024 |
| Acer          | Aspire ES1-512              | [c24ea3ef71](https://linux-hardware.org/?probe=c24ea3ef71) | Jan 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [4c5cb3c1d4](https://linux-hardware.org/?probe=4c5cb3c1d4) | Jan 05, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [36f9070500](https://linux-hardware.org/?probe=36f9070500) | Jan 04, 2024 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [a37ab2b577](https://linux-hardware.org/?probe=a37ab2b577) | Jan 04, 2024 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [8d22dafe25](https://linux-hardware.org/?probe=8d22dafe25) | Jan 03, 2024 |
| Acer          | Aspire ES1-523              | [6b5ef78cce](https://linux-hardware.org/?probe=6b5ef78cce) | Jan 02, 2024 |
| HP            | Laptop 15-db0xxx            | [dc302f3b3e](https://linux-hardware.org/?probe=dc302f3b3e) | Jan 02, 2024 |
| Dell          | Latitude 7490               | [efab03db5f](https://linux-hardware.org/?probe=efab03db5f) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | [65fb7df562](https://linux-hardware.org/?probe=65fb7df562) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | [e270ce7266](https://linux-hardware.org/?probe=e270ce7266) | Jan 01, 2024 |
| ASUSTek       | UX550VE                     | [90014cac84](https://linux-hardware.org/?probe=90014cac84) | Dec 31, 2023 |
| ASUSTek       | G75VW                       | [763233abcb](https://linux-hardware.org/?probe=763233abcb) | Dec 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [2a7878eaed](https://linux-hardware.org/?probe=2a7878eaed) | Dec 28, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [424a79de6b](https://linux-hardware.org/?probe=424a79de6b) | Dec 28, 2023 |
| Dell          | Latitude 5420               | [769ba1b68c](https://linux-hardware.org/?probe=769ba1b68c) | Dec 27, 2023 |
| PC Special... | N150CU                      | [5697f18262](https://linux-hardware.org/?probe=5697f18262) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1RS0... | [5c4efd5165](https://linux-hardware.org/?probe=5c4efd5165) | Dec 24, 2023 |
| Apple         | MacBookAir7,2               | [18ef14b687](https://linux-hardware.org/?probe=18ef14b687) | Dec 23, 2023 |
| HP            | ProBook 445 14 inch G10 ... | [5b3a77bd87](https://linux-hardware.org/?probe=5b3a77bd87) | Dec 20, 2023 |
| HP            | ProBook 650 G1              | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | ThinkPad X270 20HMS0B60H    | [059545a4ad](https://linux-hardware.org/?probe=059545a4ad) | Dec 17, 2023 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | [c95903375b](https://linux-hardware.org/?probe=c95903375b) | Dec 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3324746751](https://linux-hardware.org/?probe=3324746751) | Dec 16, 2023 |
| PC Special... | N150CU                      | [92a4f7a5a4](https://linux-hardware.org/?probe=92a4f7a5a4) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [984c55c6a2](https://linux-hardware.org/?probe=984c55c6a2) | Dec 16, 2023 |
| PC Special... | N150CU                      | [07686d110e](https://linux-hardware.org/?probe=07686d110e) | Dec 16, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [92b42d7c3e](https://linux-hardware.org/?probe=92b42d7c3e) | Dec 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [49278a194a](https://linux-hardware.org/?probe=49278a194a) | Dec 14, 2023 |
| HP            | Unknown                     | [6a46b87d41](https://linux-hardware.org/?probe=6a46b87d41) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | [05c8fb1ded](https://linux-hardware.org/?probe=05c8fb1ded) | Dec 13, 2023 |
| Acer          | Swift SF314-57              | [5a796a43bd](https://linux-hardware.org/?probe=5a796a43bd) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| Acer          | Extensa 2509                | [ee00581b3a](https://linux-hardware.org/?probe=ee00581b3a) | Dec 11, 2023 |
| Dell          | XPS 9320                    | [91f9b06d7f](https://linux-hardware.org/?probe=91f9b06d7f) | Dec 10, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [bb7ea992e6](https://linux-hardware.org/?probe=bb7ea992e6) | Dec 09, 2023 |
| Acer          | Swift SFE16-43              | [e31c4454c6](https://linux-hardware.org/?probe=e31c4454c6) | Dec 04, 2023 |
| Acer          | Aspire V3-571               | [90e07856e4](https://linux-hardware.org/?probe=90e07856e4) | Dec 01, 2023 |
| HUAWEI        | KLVC-WXX9                   | [dd49d338b4](https://linux-hardware.org/?probe=dd49d338b4) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| HP            | Laptop 14-em0xxx            | [9530bb80db](https://linux-hardware.org/?probe=9530bb80db) | Nov 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [24e86fc568](https://linux-hardware.org/?probe=24e86fc568) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [288151e67d](https://linux-hardware.org/?probe=288151e67d) | Nov 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [2715c8329f](https://linux-hardware.org/?probe=2715c8329f) | Nov 27, 2023 |
| Acer          | Predator PH315-53           | [8139afea1a](https://linux-hardware.org/?probe=8139afea1a) | Nov 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [94927ee986](https://linux-hardware.org/?probe=94927ee986) | Nov 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8cb9c3b0a7](https://linux-hardware.org/?probe=8cb9c3b0a7) | Nov 24, 2023 |
| HP            | Presario CQ61               | [5c7a775c76](https://linux-hardware.org/?probe=5c7a775c76) | Nov 24, 2023 |
| HP            | EliteBook 6930p             | [6bc9169e34](https://linux-hardware.org/?probe=6bc9169e34) | Nov 23, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [e0d3e7cba3](https://linux-hardware.org/?probe=e0d3e7cba3) | Nov 19, 2023 |
| Acer          | Aspire V3-571G              | [63c8984ac3](https://linux-hardware.org/?probe=63c8984ac3) | Nov 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [e42bab7bfa](https://linux-hardware.org/?probe=e42bab7bfa) | Nov 15, 2023 |
| System76      | Adder WS                    | [7135955eda](https://linux-hardware.org/?probe=7135955eda) | Nov 13, 2023 |
| Lenovo        | G50-30 80G0                 | [36d24b7c8b](https://linux-hardware.org/?probe=36d24b7c8b) | Nov 11, 2023 |
| Valve         | Jupiter                     | [040bcdd741](https://linux-hardware.org/?probe=040bcdd741) | Nov 10, 2023 |
| Apple         | MacBookPro11,1              | [224a0992ae](https://linux-hardware.org/?probe=224a0992ae) | Nov 08, 2023 |
| Apple         | MacBookPro11,1              | [9a3d616dad](https://linux-hardware.org/?probe=9a3d616dad) | Nov 08, 2023 |
| HP            | EliteBook 2570p             | [de38771bec](https://linux-hardware.org/?probe=de38771bec) | Nov 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [da7463eff8](https://linux-hardware.org/?probe=da7463eff8) | Nov 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [5191c2b469](https://linux-hardware.org/?probe=5191c2b469) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | [4caad7b0d1](https://linux-hardware.org/?probe=4caad7b0d1) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | [1d0638865e](https://linux-hardware.org/?probe=1d0638865e) | Nov 07, 2023 |
| Dell          | Latitude 3190               | [309f968d10](https://linux-hardware.org/?probe=309f968d10) | Nov 07, 2023 |
| Acer          | Nitro AN515-55              | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| Acer          | Swift SF113-31              | [a6fbe4af41](https://linux-hardware.org/?probe=a6fbe4af41) | Nov 05, 2023 |
| HP            | Unknown                     | [c8cff9e339](https://linux-hardware.org/?probe=c8cff9e339) | Nov 05, 2023 |
| Dell          | XPS 13 9310                 | [5ff7f9b284](https://linux-hardware.org/?probe=5ff7f9b284) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d0f3cf43b7](https://linux-hardware.org/?probe=d0f3cf43b7) | Nov 04, 2023 |
| Lenovo        | ThinkPad X220 4293A25       | [95a5125a73](https://linux-hardware.org/?probe=95a5125a73) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [7b64212148](https://linux-hardware.org/?probe=7b64212148) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [0e71b912ec](https://linux-hardware.org/?probe=0e71b912ec) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A532               | [b596813aeb](https://linux-hardware.org/?probe=b596813aeb) | Nov 02, 2023 |
| Panasonic     | CF-54-1                     | [b7d7cde99a](https://linux-hardware.org/?probe=b7d7cde99a) | Nov 01, 2023 |
| Dell          | Precision 5570              | [fb83199260](https://linux-hardware.org/?probe=fb83199260) | Oct 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [9dd62a1bb2](https://linux-hardware.org/?probe=9dd62a1bb2) | Oct 31, 2023 |
| Dell          | Latitude 7370               | [f47b42c0b0](https://linux-hardware.org/?probe=f47b42c0b0) | Oct 30, 2023 |
| HP            | Unknown                     | [3aadbc5c33](https://linux-hardware.org/?probe=3aadbc5c33) | Oct 30, 2023 |
| HP            | Laptop 15-bw0xx             | [b61ad8059a](https://linux-hardware.org/?probe=b61ad8059a) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| HP            | G62                         | [bd714e9671](https://linux-hardware.org/?probe=bd714e9671) | Oct 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [4aceca5660](https://linux-hardware.org/?probe=4aceca5660) | Oct 28, 2023 |
| ASUSTek       | G75VW                       | [e3bde6ede0](https://linux-hardware.org/?probe=e3bde6ede0) | Oct 28, 2023 |
| HP            | EliteBook 850 G4            | [68da315076](https://linux-hardware.org/?probe=68da315076) | Oct 28, 2023 |
| Lenovo        | ThinkPad X230 2325SDE       | [cbdbd4a156](https://linux-hardware.org/?probe=cbdbd4a156) | Oct 27, 2023 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [a20c6e2c77](https://linux-hardware.org/?probe=a20c6e2c77) | Oct 26, 2023 |
| Fujitsu       | LIFEBOOK E752               | [c1078c11fb](https://linux-hardware.org/?probe=c1078c11fb) | Oct 26, 2023 |
| HP            | ProBook 650 G1              | [b05283573c](https://linux-hardware.org/?probe=b05283573c) | Oct 26, 2023 |
| HP            | EliteBook 8560p             | [101037a3e1](https://linux-hardware.org/?probe=101037a3e1) | Oct 25, 2023 |
| Acer          | Aspire ES1-311              | [b98bc11e71](https://linux-hardware.org/?probe=b98bc11e71) | Oct 25, 2023 |
| Acer          | Aspire ES1-311              | [c505d21099](https://linux-hardware.org/?probe=c505d21099) | Oct 25, 2023 |
| Notebook      | NS5x_NS7xAU                 | [ad7033d138](https://linux-hardware.org/?probe=ad7033d138) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | [51f3725a80](https://linux-hardware.org/?probe=51f3725a80) | Oct 24, 2023 |
| Dell          | Latitude 3190               | [a26f69cb33](https://linux-hardware.org/?probe=a26f69cb33) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [88e833ab8a](https://linux-hardware.org/?probe=88e833ab8a) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [62ca050eaf](https://linux-hardware.org/?probe=62ca050eaf) | Oct 24, 2023 |
| Dixonsxp      | Unknown                     | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 13 9310                 | [cceff4e3b1](https://linux-hardware.org/?probe=cceff4e3b1) | Oct 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0feec3b3ab](https://linux-hardware.org/?probe=0feec3b3ab) | Oct 19, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [0815767d1d](https://linux-hardware.org/?probe=0815767d1d) | Oct 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0b4065c185](https://linux-hardware.org/?probe=0b4065c185) | Oct 17, 2023 |
| HP            | EliteBook 8760w             | [d5febd2212](https://linux-hardware.org/?probe=d5febd2212) | Oct 17, 2023 |
| HP            | EliteBook 8570p             | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Notebook      | NS5x_NS7xAU                 | [1568dbcf9b](https://linux-hardware.org/?probe=1568dbcf9b) | Oct 15, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [80bd4e2684](https://linux-hardware.org/?probe=80bd4e2684) | Oct 15, 2023 |
| Apple         | MacBookPro6,2               | [1df7e29365](https://linux-hardware.org/?probe=1df7e29365) | Oct 15, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [7901d1df27](https://linux-hardware.org/?probe=7901d1df27) | Oct 12, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| HP            | ProBook 640 G1              | [f6fbcbf614](https://linux-hardware.org/?probe=f6fbcbf614) | Oct 11, 2023 |
| Dell          | Latitude 7420               | [4071bd53ce](https://linux-hardware.org/?probe=4071bd53ce) | Oct 10, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [c360c7552a](https://linux-hardware.org/?probe=c360c7552a) | Oct 08, 2023 |
| Dell          | Vostro 3550                 | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| Apple         | MacBook4,1                  | [e5b3d089e8](https://linux-hardware.org/?probe=e5b3d089e8) | Oct 06, 2023 |
| Apple         | MacBook4,1                  | [11497e61f8](https://linux-hardware.org/?probe=11497e61f8) | Oct 06, 2023 |
| HP            | ZBook 14u G4                | [1d14da7190](https://linux-hardware.org/?probe=1d14da7190) | Oct 05, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [071eee1057](https://linux-hardware.org/?probe=071eee1057) | Oct 03, 2023 |
| Lenovo        | ThinkPad T420s 4170CTO      | [f141fc2bd7](https://linux-hardware.org/?probe=f141fc2bd7) | Oct 02, 2023 |
| Apple         | MacBookPro7,1               | [d88817f79c](https://linux-hardware.org/?probe=d88817f79c) | Oct 02, 2023 |
| HP            | ZBook Studio G5             | [3f96bd2883](https://linux-hardware.org/?probe=3f96bd2883) | Sep 30, 2023 |
| HP            | ENVY TS Sleekbook 4         | [545098d0d2](https://linux-hardware.org/?probe=545098d0d2) | Sep 29, 2023 |
| HP            | ZBook Studio G5             | [239b5a3fd5](https://linux-hardware.org/?probe=239b5a3fd5) | Sep 29, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [c61d70bcfa](https://linux-hardware.org/?probe=c61d70bcfa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [be49c167d0](https://linux-hardware.org/?probe=be49c167d0) | Sep 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8c585051a3](https://linux-hardware.org/?probe=8c585051a3) | Sep 27, 2023 |
| Dell          | Vostro 3550                 | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Latitude E7270              | [98dd5eefb6](https://linux-hardware.org/?probe=98dd5eefb6) | Sep 25, 2023 |
| Dell          | Latitude E5270              | [d091c4fa0e](https://linux-hardware.org/?probe=d091c4fa0e) | Sep 24, 2023 |
| Dell          | Inspiron 3541               | [da796376e1](https://linux-hardware.org/?probe=da796376e1) | Sep 23, 2023 |
| Valve         | Jupiter                     | [3889f9ca9d](https://linux-hardware.org/?probe=3889f9ca9d) | Sep 23, 2023 |
| Acer          | Aspire ES1-520              | [22ce921c1e](https://linux-hardware.org/?probe=22ce921c1e) | Sep 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [1893bb3992](https://linux-hardware.org/?probe=1893bb3992) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4d1743c405](https://linux-hardware.org/?probe=4d1743c405) | Sep 20, 2023 |
| Dell          | XPS 13 9370                 | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [79142d7f53](https://linux-hardware.org/?probe=79142d7f53) | Sep 17, 2023 |
| ASUSTek       | K55DR                       | [f3b7f92416](https://linux-hardware.org/?probe=f3b7f92416) | Sep 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0cdeaab8be](https://linux-hardware.org/?probe=0cdeaab8be) | Sep 13, 2023 |
| Samsung       | R530/R730/P590              | [d9bd973c79](https://linux-hardware.org/?probe=d9bd973c79) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [58b852c7cb](https://linux-hardware.org/?probe=58b852c7cb) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [10ff64dcf5](https://linux-hardware.org/?probe=10ff64dcf5) | Sep 12, 2023 |
| MSI           | Stealth 15M B12UE           | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Apple         | MacBookPro8,1               | [d3b821a061](https://linux-hardware.org/?probe=d3b821a061) | Sep 10, 2023 |
| Dell          | Precision M4800             | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| ASUSTek       | G75VW                       | [98ba75a25b](https://linux-hardware.org/?probe=98ba75a25b) | Sep 09, 2023 |
| ASUSTek       | X453MA                      | [b73ef6339a](https://linux-hardware.org/?probe=b73ef6339a) | Sep 08, 2023 |
| ASUSTek       | X453MA                      | [e71f333094](https://linux-hardware.org/?probe=e71f333094) | Sep 07, 2023 |
| ASUSTek       | X453MA                      | [c48759c297](https://linux-hardware.org/?probe=c48759c297) | Sep 07, 2023 |
| Dell          | Latitude 7440               | [47f28d7b00](https://linux-hardware.org/?probe=47f28d7b00) | Sep 04, 2023 |
| Dell          | Latitude 7440               | [27b2ae9d5b](https://linux-hardware.org/?probe=27b2ae9d5b) | Sep 04, 2023 |
| Lenovo        | ThinkPad T440 20B7S0RD00    | [af57fd1655](https://linux-hardware.org/?probe=af57fd1655) | Sep 03, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [806eed53dc](https://linux-hardware.org/?probe=806eed53dc) | Sep 02, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [377d5352d8](https://linux-hardware.org/?probe=377d5352d8) | Sep 02, 2023 |
| HP            | EliteBook 8460p             | [b6f6192ef9](https://linux-hardware.org/?probe=b6f6192ef9) | Sep 02, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [e4a45bf853](https://linux-hardware.org/?probe=e4a45bf853) | Sep 02, 2023 |
| Acer          | Aspire 5755G                | [b938dc8500](https://linux-hardware.org/?probe=b938dc8500) | Aug 31, 2023 |
| HP            | ProBook 6360b               | [0dbff9ebb3](https://linux-hardware.org/?probe=0dbff9ebb3) | Aug 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [44e7ba057b](https://linux-hardware.org/?probe=44e7ba057b) | Aug 30, 2023 |
| Apple         | MacBookAir6,2               | [7c208705e5](https://linux-hardware.org/?probe=7c208705e5) | Aug 29, 2023 |
| Lenovo        | B50-30 80ES                 | [96aa7b5683](https://linux-hardware.org/?probe=96aa7b5683) | Aug 29, 2023 |
| Acer          | Aspire ES1-311              | [f0a3b05a99](https://linux-hardware.org/?probe=f0a3b05a99) | Aug 25, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [f8f097e135](https://linux-hardware.org/?probe=f8f097e135) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [aa3157f519](https://linux-hardware.org/?probe=aa3157f519) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [8d3738c790](https://linux-hardware.org/?probe=8d3738c790) | Aug 24, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [3231dcefb4](https://linux-hardware.org/?probe=3231dcefb4) | Aug 22, 2023 |
| Dell          | Latitude 3350               | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [d989b68c65](https://linux-hardware.org/?probe=d989b68c65) | Aug 19, 2023 |
| ASUSTek       | M3N                         | [7c4b9386db](https://linux-hardware.org/?probe=7c4b9386db) | Aug 18, 2023 |
| ASUSTek       | U38N                        | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| Dell          | XPS 15 9570                 | [91b8c2a5eb](https://linux-hardware.org/?probe=91b8c2a5eb) | Aug 17, 2023 |
| Acer          | Aspire ES1-520              | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Dell          | Inspiron 5559               | [f3e1bb3812](https://linux-hardware.org/?probe=f3e1bb3812) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [0a1e2a7f23](https://linux-hardware.org/?probe=0a1e2a7f23) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [742b085257](https://linux-hardware.org/?probe=742b085257) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [836fcda626](https://linux-hardware.org/?probe=836fcda626) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [3e208faa6e](https://linux-hardware.org/?probe=3e208faa6e) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [f20a32551b](https://linux-hardware.org/?probe=f20a32551b) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [e323e9cd7e](https://linux-hardware.org/?probe=e323e9cd7e) | Aug 10, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [a3b9be2f56](https://linux-hardware.org/?probe=a3b9be2f56) | Aug 10, 2023 |
| HP            | Unknown                     | [567a10ceb2](https://linux-hardware.org/?probe=567a10ceb2) | Aug 08, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| Acer          | Aspire 4810T                | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [3d49205e68](https://linux-hardware.org/?probe=3d49205e68) | Aug 06, 2023 |
| Toshiba       | Satellite C670D-11P         | [a5c49672d6](https://linux-hardware.org/?probe=a5c49672d6) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| ASUSTek       | G75VW                       | [f420f3e1e6](https://linux-hardware.org/?probe=f420f3e1e6) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNP           | [508c18e563](https://linux-hardware.org/?probe=508c18e563) | Aug 03, 2023 |
| Dell          | Latitude E7240              | [87a0310cf0](https://linux-hardware.org/?probe=87a0310cf0) | Aug 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3190               | [c88a2ad597](https://linux-hardware.org/?probe=c88a2ad597) | Aug 01, 2023 |
| HP            | Unknown                     | [a4d8377dfa](https://linux-hardware.org/?probe=a4d8377dfa) | Aug 01, 2023 |
| Apple         | MacBookPro6,2               | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| HP            | EliteBook 745 G6            | [d8272e8eeb](https://linux-hardware.org/?probe=d8272e8eeb) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| win elemen... | MoreFine S500+              | [7d5b443b84](https://linux-hardware.org/?probe=7d5b443b84) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S55L00    | [5b3742984b](https://linux-hardware.org/?probe=5b3742984b) | Jul 27, 2023 |
| ASUSTek       | K55DR                       | [47e831a79a](https://linux-hardware.org/?probe=47e831a79a) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [a060c0999b](https://linux-hardware.org/?probe=a060c0999b) | Jul 26, 2023 |
| Lenovo        | ThinkPad E480 20KN001QMX    | [1ff9753d17](https://linux-hardware.org/?probe=1ff9753d17) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9fa1cd70a3](https://linux-hardware.org/?probe=9fa1cd70a3) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [1e169f0ba8](https://linux-hardware.org/?probe=1e169f0ba8) | Jul 23, 2023 |
| Acer          | Aspire ES1-311              | [52541ec1ed](https://linux-hardware.org/?probe=52541ec1ed) | Jul 23, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [bbd3181f1f](https://linux-hardware.org/?probe=bbd3181f1f) | Jul 22, 2023 |
| HP            | Compaq Presario CQ50        | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| HP            | ProBook 4530s               | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| HP            | 15                          | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| HP            | EliteBook 2570p             | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| MSI           | GF65 Thin 10SER             | [27966135e2](https://linux-hardware.org/?probe=27966135e2) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [801eb1eb3c](https://linux-hardware.org/?probe=801eb1eb3c) | Jul 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Alienware     | x15 R1                      | [a72051a57e](https://linux-hardware.org/?probe=a72051a57e) | Jul 13, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [161a78ce7d](https://linux-hardware.org/?probe=161a78ce7d) | Jul 11, 2023 |
| ASUSTek       | G75VW                       | [cfc5e42de6](https://linux-hardware.org/?probe=cfc5e42de6) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [4b33cf2e09](https://linux-hardware.org/?probe=4b33cf2e09) | Jul 09, 2023 |
| IBM           | ThinkPad T43 18714AG        | [c7d3e6a151](https://linux-hardware.org/?probe=c7d3e6a151) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | [ecd8f6cdd2](https://linux-hardware.org/?probe=ecd8f6cdd2) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | [0ea27ea171](https://linux-hardware.org/?probe=0ea27ea171) | Jul 09, 2023 |
| Dell          | XPS 13 9370                 | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| Medion        | ML-210007                   | [192b83694f](https://linux-hardware.org/?probe=192b83694f) | Jul 06, 2023 |
| Medion        | ML-210007                   | [8bc97d58d2](https://linux-hardware.org/?probe=8bc97d58d2) | Jul 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | [b6d0f85342](https://linux-hardware.org/?probe=b6d0f85342) | Jul 04, 2023 |
| Acer          | Aspire ES1-311              | [50b65edbc0](https://linux-hardware.org/?probe=50b65edbc0) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [e0fc7e357f](https://linux-hardware.org/?probe=e0fc7e357f) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [0ca36f92b8](https://linux-hardware.org/?probe=0ca36f92b8) | Jul 03, 2023 |
| Acer          | Aspire ES1-311              | [066d1a2fa8](https://linux-hardware.org/?probe=066d1a2fa8) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [80810e133e](https://linux-hardware.org/?probe=80810e133e) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [48df5942cf](https://linux-hardware.org/?probe=48df5942cf) | Jul 02, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [f91dbee23b](https://linux-hardware.org/?probe=f91dbee23b) | Jul 02, 2023 |
| Acer          | Predator G9-593             | [127df9999f](https://linux-hardware.org/?probe=127df9999f) | Jul 01, 2023 |
| Acer          | Predator G9-593             | [d4dca39223](https://linux-hardware.org/?probe=d4dca39223) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [7f9164d1e0](https://linux-hardware.org/?probe=7f9164d1e0) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [e10aa58dda](https://linux-hardware.org/?probe=e10aa58dda) | Jun 24, 2023 |
| MSI           | GX60 1AC                    | [8e15fea8cd](https://linux-hardware.org/?probe=8e15fea8cd) | Jun 22, 2023 |
| MSI           | Katana GF76 12UD            | [1897f5f0cb](https://linux-hardware.org/?probe=1897f5f0cb) | Jun 20, 2023 |
| Acer          | Aspire ES1-311              | [b0361fedbc](https://linux-hardware.org/?probe=b0361fedbc) | Jun 16, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [74a69e5cca](https://linux-hardware.org/?probe=74a69e5cca) | Jun 15, 2023 |
| Acer          | Aspire ES1-311              | [a0e0ea6aa1](https://linux-hardware.org/?probe=a0e0ea6aa1) | Jun 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [91af63490c](https://linux-hardware.org/?probe=91af63490c) | Jun 15, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [e9aeb26aeb](https://linux-hardware.org/?probe=e9aeb26aeb) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [f675b70f23](https://linux-hardware.org/?probe=f675b70f23) | Jun 14, 2023 |
| Dell          | Latitude 7480               | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [3a8338d906](https://linux-hardware.org/?probe=3a8338d906) | Jun 13, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [93cd1fd89c](https://linux-hardware.org/?probe=93cd1fd89c) | Jun 13, 2023 |
| Dell          | Latitude 3320               | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [88fc978934](https://linux-hardware.org/?probe=88fc978934) | Jun 12, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [0b737be0c6](https://linux-hardware.org/?probe=0b737be0c6) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [5f4978fc61](https://linux-hardware.org/?probe=5f4978fc61) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8a3bd0a576](https://linux-hardware.org/?probe=8a3bd0a576) | Jun 11, 2023 |
| Acer          | Aspire A515-47              | [2838a84809](https://linux-hardware.org/?probe=2838a84809) | Jun 11, 2023 |
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
| Ubuntu 20.04                 | 148       | 10.49%  |
| Ubuntu 22.04                 | 108       | 7.65%   |
| Ubuntu 18.04                 | 74        | 5.24%   |
| Debian 12                    | 43        | 3.05%   |
| Pop!_OS 22.04                | 42        | 2.98%   |
| Arch Rolling                 | 34        | 2.41%   |
| Debian 11                    | 32        | 2.27%   |
| Zorin 16                     | 29        | 2.06%   |
| Manjaro                      | 26        | 1.84%   |
| ArcoLinux Rolling            | 23        | 1.63%   |
| Pop!_OS 21.04                | 21        | 1.49%   |
| OpenMandriva 4.3             | 21        | 1.49%   |
| OpenMandriva 4.2             | 21        | 1.49%   |
| Arch                         | 21        | 1.49%   |
| Fedora 35                    | 20        | 1.42%   |
| Ubuntu 23.10                 | 19        | 1.35%   |
| Ubuntu 19.04                 | 19        | 1.35%   |
| Linux Mint 21.1              | 18        | 1.28%   |
| openSUSE Tumbleweed-XXXXXXXX | 17        | 1.2%    |
| Zorin 15                     | 16        | 1.13%   |
| Ubuntu 21.10                 | 16        | 1.13%   |
| Pop!_OS 20.10                | 16        | 1.13%   |
| Pop!_OS 20.04                | 16        | 1.13%   |
| Linux Mint 20.3              | 15        | 1.06%   |
| KDE neon 20.04               | 15        | 1.06%   |
| Linux Mint 20.2              | 14        | 0.99%   |
| Fedora 39                    | 14        | 0.99%   |
| Fedora 38                    | 14        | 0.99%   |
| Fedora 37                    | 14        | 0.99%   |
| Ubuntu 19.10                 | 13        | 0.92%   |
| Linux Mint 21.2              | 13        | 0.92%   |
| Linux Mint 20.1              | 12        | 0.85%   |
| Fedora 34                    | 12        | 0.85%   |
| Ubuntu 21.04                 | 11        | 0.78%   |
| Xubuntu 22.04                | 10        | 0.71%   |
| Ubuntu 20.10                 | 10        | 0.71%   |
| Linux Mint 21.3              | 10        | 0.71%   |
| KDE neon 22.04               | 10        | 0.71%   |
| Fedora 36                    | 10        | 0.71%   |
| EndeavourOS Rolling          | 10        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 423       | 31.38%  |
| Fedora        | 111       | 8.23%   |
| Linux Mint    | 110       | 8.16%   |
| Pop!_OS       | 100       | 7.42%   |
| Debian        | 87        | 6.45%   |
| OpenMandriva  | 65        | 4.82%   |
| Arch          | 54        | 4.01%   |
| Manjaro       | 52        | 3.86%   |
| Zorin         | 50        | 3.71%   |
| KDE neon      | 26        | 1.93%   |
| ArcoLinux     | 26        | 1.93%   |
| Xubuntu       | 25        | 1.85%   |
| openSUSE      | 19        | 1.41%   |
| Kubuntu       | 18        | 1.34%   |
| Kali          | 16        | 1.19%   |
| Gentoo        | 13        | 0.96%   |
| EndeavourOS   | 13        | 0.96%   |
| SteamOS       | 11        | 0.82%   |
| Elementary    | 10        | 0.74%   |
| Ubuntu MATE   | 9         | 0.67%   |
| Endless       | 9         | 0.67%   |
| ROSA          | 8         | 0.59%   |
| Parrot        | 7         | 0.52%   |
| LMDE          | 6         | 0.45%   |
| CentOS        | 6         | 0.45%   |
| BunsenLabs    | 6         | 0.45%   |
| NixOS         | 5         | 0.37%   |
| Garuda Linux  | 5         | 0.37%   |
| Peppermint    | 4         | 0.3%    |
| MX            | 4         | 0.3%    |
| Lubuntu       | 4         | 0.3%    |
| Clear Linux   | 4         | 0.3%    |
| BlackPanther  | 4         | 0.3%    |
| Ubuntu Unity  | 3         | 0.22%   |
| Ubuntu Budgie | 3         | 0.22%   |
| Nobara        | 3         | 0.22%   |
| GNOME OS      | 3         | 0.22%   |
| Slackware     | 2         | 0.15%   |
| Deepin        | 2         | 0.15%   |
| Chrome OS     | 2         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 21        | 1.36%   |
| 5.16.7-desktop-1omv4003  | 20        | 1.3%    |
| 5.15.0-56-generic        | 19        | 1.23%   |
| 5.4.0-42-generic         | 18        | 1.17%   |
| 5.4.0-58-generic         | 12        | 0.78%   |
| 5.4.0-48-generic         | 12        | 0.78%   |
| 5.15.0-52-generic        | 12        | 0.78%   |
| 6.1.0-7-amd64            | 10        | 0.65%   |
| 5.3.0-40-generic         | 10        | 0.65%   |
| 5.15.0-91-generic        | 10        | 0.65%   |
| 5.15.0-60-generic        | 10        | 0.65%   |
| 5.13.0-30-generic        | 10        | 0.65%   |
| 6.4.11-desktop-1omv2390  | 9         | 0.58%   |
| 6.1.0-9-amd64            | 9         | 0.58%   |
| 5.4.0-52-generic         | 9         | 0.58%   |
| 5.4.0-40-generic         | 9         | 0.58%   |
| 5.15.0-78-generic        | 9         | 0.58%   |
| 5.11.0-37-generic        | 9         | 0.58%   |
| 6.5.0-26-generic         | 8         | 0.52%   |
| 6.1.0-18-amd64           | 8         | 0.52%   |
| 5.8.0-48-generic         | 8         | 0.52%   |
| 5.15.0-48-generic        | 8         | 0.52%   |
| 5.13.0-7614-generic      | 8         | 0.52%   |
| 6.6.10-76060610-generic  | 7         | 0.45%   |
| 5.4.0-70-generic         | 7         | 0.45%   |
| 5.4.0-65-generic         | 7         | 0.45%   |
| 5.19.0-35-generic        | 7         | 0.45%   |
| 5.15.0-76-generic        | 7         | 0.45%   |
| 5.13.0-39-generic        | 7         | 0.45%   |
| 5.10.0-8-amd64           | 7         | 0.45%   |
| 5.10.0-21-amd64          | 7         | 0.45%   |
| 4.15.0-47-generic        | 7         | 0.45%   |
| 6.5.0-14-generic         | 6         | 0.39%   |
| 6.1.0-13-amd64           | 6         | 0.39%   |
| 5.8.0-7630-generic       | 6         | 0.39%   |
| 5.4.0-7634-generic       | 6         | 0.39%   |
| 5.4.0-66-generic         | 6         | 0.39%   |
| 5.4.0-54-generic         | 6         | 0.39%   |
| 5.4.0-33-generic         | 6         | 0.39%   |
| 5.3.0-51-generic         | 6         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 178       | 12.17%  |
| 5.15.0  | 145       | 9.91%   |
| 5.13.0  | 66        | 4.51%   |
| 5.11.0  | 66        | 4.51%   |
| 6.1.0   | 60        | 4.1%    |
| 5.8.0   | 51        | 3.49%   |
| 6.5.0   | 47        | 3.21%   |
| 5.3.0   | 46        | 3.14%   |
| 4.15.0  | 46        | 3.14%   |
| 5.10.0  | 45        | 3.08%   |
| 5.19.0  | 40        | 2.73%   |
| 6.2.0   | 37        | 2.53%   |
| 5.0.0   | 34        | 2.32%   |
| 4.18.0  | 23        | 1.57%   |
| 5.16.7  | 21        | 1.44%   |
| 5.10.14 | 21        | 1.44%   |
| 6.4.11  | 10        | 0.68%   |
| 6.6.10  | 9         | 0.62%   |
| 6.2.6   | 9         | 0.62%   |
| 5.14.0  | 9         | 0.62%   |
| 6.5.6   | 7         | 0.48%   |
| 6.0.12  | 7         | 0.48%   |
| 5.17.5  | 7         | 0.48%   |
| 6.1.1   | 6         | 0.41%   |
| 5.16.0  | 6         | 0.41%   |
| 6.5.7   | 5         | 0.34%   |
| 5.7.0   | 5         | 0.34%   |
| 5.18.0  | 5         | 0.34%   |
| 6.8.4   | 4         | 0.27%   |
| 6.8.0   | 4         | 0.27%   |
| 6.7.9   | 4         | 0.27%   |
| 6.7.6   | 4         | 0.27%   |
| 6.7.0   | 4         | 0.27%   |
| 6.6.7   | 4         | 0.27%   |
| 6.6.6   | 4         | 0.27%   |
| 6.5.5   | 4         | 0.27%   |
| 6.4.0   | 4         | 0.27%   |
| 6.3.0   | 4         | 0.27%   |
| 6.2.9   | 4         | 0.27%   |
| 6.2.8   | 4         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 185       | 12.87%  |
| 5.15    | 176       | 12.25%  |
| 6.1     | 95        | 6.61%   |
| 5.10    | 83        | 5.78%   |
| 5.11    | 78        | 5.43%   |
| 5.13    | 76        | 5.29%   |
| 6.5     | 68        | 4.73%   |
| 6.2     | 65        | 4.52%   |
| 5.8     | 63        | 4.38%   |
| 5.3     | 52        | 3.62%   |
| 5.19    | 47        | 3.27%   |
| 5.16    | 47        | 3.27%   |
| 4.15    | 46        | 3.2%    |
| 5.0     | 36        | 2.51%   |
| 6.6     | 32        | 2.23%   |
| 6.4     | 31        | 2.16%   |
| 4.18    | 29        | 2.02%   |
| 6.0     | 26        | 1.81%   |
| 5.14    | 21        | 1.46%   |
| 6.8     | 20        | 1.39%   |
| 5.18    | 20        | 1.39%   |
| 5.17    | 20        | 1.39%   |
| 6.7     | 19        | 1.32%   |
| 6.3     | 16        | 1.11%   |
| 5.9     | 14        | 0.97%   |
| 5.12    | 14        | 0.97%   |
| 5.7     | 11        | 0.77%   |
| 5.6     | 11        | 0.77%   |
| 4.19    | 8         | 0.56%   |
| 5.5     | 7         | 0.49%   |
| 5.2     | 6         | 0.42%   |
| 4.9     | 5         | 0.35%   |
| 5.1     | 4         | 0.28%   |
| 4.14    | 2         | 0.14%   |
| 4.1     | 2         | 0.14%   |
| 4.20    | 1         | 0.07%   |
| 3.10    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1273      | 98.61%  |
| i686    | 17        | 1.32%   |
| aarch64 | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 671       | 49.48%  |
| KDE5            | 179       | 13.2%   |
| Unknown         | 144       | 10.62%  |
| XFCE            | 106       | 7.82%   |
| X-Cinnamon      | 94        | 6.93%   |
| MATE            | 33        | 2.43%   |
| KDE             | 31        | 2.29%   |
| i3              | 15        | 1.11%   |
| Cinnamon        | 12        | 0.88%   |
| Pantheon        | 10        | 0.74%   |
| LXQt            | 9         | 0.66%   |
| sway            | 5         | 0.37%   |
| LXDE            | 5         | 0.37%   |
| KDE6            | 5         | 0.37%   |
| GNOME Flashback | 5         | 0.37%   |
| BunsenLabs      | 4         | 0.29%   |
| Budgie          | 4         | 0.29%   |
| Unity           | 3         | 0.22%   |
| KDE4            | 3         | 0.22%   |
| awesome         | 3         | 0.22%   |
| qtile           | 2         | 0.15%   |
| DWM             | 2         | 0.15%   |
| Deepin          | 2         | 0.15%   |
| Trinity         | 1         | 0.07%   |
| spectrwm        | 1         | 0.07%   |
| none+i3         | 1         | 0.07%   |
| none+awesome    | 1         | 0.07%   |
| niri            | 1         | 0.07%   |
| LeftWM          | 1         | 0.07%   |
| Hyprland        | 1         | 0.07%   |
| DDE             | 1         | 0.07%   |
| bspwm           | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 913       | 68.34%  |
| Wayland | 317       | 23.73%  |
| Unknown | 83        | 6.21%   |
| Tty     | 23        | 1.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 633       | 46.89%  |
| GDM3    | 208       | 15.41%  |
| SDDM    | 167       | 12.37%  |
| GDM     | 155       | 11.48%  |
| LightDM | 147       | 10.89%  |
| TDM     | 28        | 2.07%   |
| LXDM    | 4         | 0.3%    |
| XDM     | 3         | 0.22%   |
| KDM     | 3         | 0.22%   |
| Ly      | 2         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 666       | 50.19%  |
| sv_SE      | 359       | 27.05%  |
| Unknown    | 127       | 9.57%   |
| en_GB      | 81        | 6.1%    |
| C          | 21        | 1.58%   |
| ru_RU      | 11        | 0.83%   |
| de_DE      | 9         | 0.68%   |
| pl_PL      | 8         | 0.6%    |
| en_SE      | 5         | 0.38%   |
| en_CA      | 4         | 0.3%    |
| it_IT      | 3         | 0.23%   |
| fr_FR      | 3         | 0.23%   |
| en_DK      | 3         | 0.23%   |
| el_GR      | 3         | 0.23%   |
| zh_CN      | 2         | 0.15%   |
| uk_UA      | 2         | 0.15%   |
| sv_FI      | 2         | 0.15%   |
| lt_LT      | 2         | 0.15%   |
| fi_FI      | 2         | 0.15%   |
| en_AG      | 2         | 0.15%   |
| tr_TR      | 1         | 0.08%   |
| sv_SE.UTF8 | 1         | 0.08%   |
| POSIX      | 1         | 0.08%   |
| nn_NO      | 1         | 0.08%   |
| nb_NO      | 1         | 0.08%   |
| hu_HU      | 1         | 0.08%   |
| gl_ES      | 1         | 0.08%   |
| es_ES      | 1         | 0.08%   |
| en_IE      | 1         | 0.08%   |
| en_AU      | 1         | 0.08%   |
| C.UTF8     | 1         | 0.08%   |
| bg_BG      | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 718       | 54.11%  |
| BIOS | 609       | 45.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 961       | 72.09%  |
| Btrfs   | 160       | 12%     |
| Overlay | 73        | 5.48%   |
| Tmpfs   | 66        | 4.95%   |
| Unknown | 32        | 2.4%    |
| Xfs     | 15        | 1.13%   |
| Zfs     | 14        | 1.05%   |
| Ext2    | 6         | 0.45%   |
| F2fs    | 4         | 0.3%    |
| XXXXXXX | 1         | 0.08%   |
| Ext3    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 636       | 48.07%  |
| GPT     | 571       | 43.16%  |
| MBR     | 116       | 8.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1197      | 91.44%  |
| Yes       | 112       | 8.56%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1056      | 81.11%  |
| Yes       | 246       | 18.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 315       | 24.4%   |
| Hewlett-Packard      | 271       | 20.99%  |
| Dell                 | 192       | 14.87%  |
| ASUSTek Computer     | 162       | 12.55%  |
| Acer                 | 95        | 7.36%   |
| Apple                | 57        | 4.42%   |
| MSI                  | 29        | 2.25%   |
| Toshiba              | 17        | 1.32%   |
| Sony                 | 15        | 1.16%   |
| Samsung Electronics  | 13        | 1.01%   |
| Fujitsu              | 11        | 0.85%   |
| Valve                | 10        | 0.77%   |
| Packard Bell         | 10        | 0.77%   |
| Notebook             | 10        | 0.77%   |
| Google               | 9         | 0.7%    |
| Unknown              | 9         | 0.7%    |
| Fujitsu Siemens      | 7         | 0.54%   |
| HUAWEI               | 5         | 0.39%   |
| TUXEDO               | 3         | 0.23%   |
| System76             | 3         | 0.23%   |
| Star Labs            | 3         | 0.23%   |
| LG Electronics       | 3         | 0.23%   |
| Gigabyte Technology  | 3         | 0.23%   |
| eMachines            | 3         | 0.23%   |
| Clevo                | 3         | 0.23%   |
| Alienware            | 3         | 0.23%   |
| Timi                 | 2         | 0.15%   |
| Schenker             | 2         | 0.15%   |
| Razer                | 2         | 0.15%   |
| PC Specialist        | 2         | 0.15%   |
| Dynabook             | 2         | 0.15%   |
| ZEPTO                | 1         | 0.08%   |
| YJKC                 | 1         | 0.08%   |
| win element          | 1         | 0.08%   |
| SLIMBOOK             | 1         | 0.08%   |
| Purism               | 1         | 0.08%   |
| Panasonic            | 1         | 0.08%   |
| On by NetOnNet       | 1         | 0.08%   |
| Medion               | 1         | 0.08%   |
| Intel Client Systems | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 13        | 1.01%   |
| Valve Jupiter                              | 10        | 0.77%   |
| Dell XPS 13 9370                           | 8         | 0.62%   |
| HP EliteBook 840 G3                        | 7         | 0.54%   |
| Dell XPS 13 9310                           | 7         | 0.54%   |
| Apple MacBookAir7,2                        | 7         | 0.54%   |
| HP Pavilion 15                             | 6         | 0.46%   |
| HP EliteBook Folio 9470m                   | 6         | 0.46%   |
| Dell Precision 5540                        | 6         | 0.46%   |
| Apple MacBookPro9,2                        | 6         | 0.46%   |
| Acer Aspire V3-571                         | 6         | 0.46%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5           | 5         | 0.39%   |
| HP ProBook 640 G1                          | 5         | 0.39%   |
| HP Pavilion dv7                            | 5         | 0.39%   |
| HP EliteBook 840 G2                        | 5         | 0.39%   |
| HP EliteBook 820 G3                        | 5         | 0.39%   |
| Dell XPS 15 9570                           | 5         | 0.39%   |
| Apple MacBookPro8,1                        | 5         | 0.39%   |
| Apple MacBookPro12,1                       | 5         | 0.39%   |
| Apple MacBookPro11,3                       | 5         | 0.39%   |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX       | 4         | 0.31%   |
| Lenovo ThinkPad L13 Gen 2 20VJS6RY00       | 4         | 0.31%   |
| HP ZBook 15 G2                             | 4         | 0.31%   |
| HP Pavilion g6                             | 4         | 0.31%   |
| HP Laptop 15-db0xxx                        | 4         | 0.31%   |
| HP EliteBook 8570p                         | 4         | 0.31%   |
| HP EliteBook 8440p                         | 4         | 0.31%   |
| HP EliteBook 840 G6                        | 4         | 0.31%   |
| HP EliteBook 830 G6                        | 4         | 0.31%   |
| Dell XPS 15 9500                           | 4         | 0.31%   |
| Dell Precision M4800                       | 4         | 0.31%   |
| Dell Latitude E7240                        | 4         | 0.31%   |
| Dell Latitude E6430                        | 4         | 0.31%   |
| Dell Latitude 7490                         | 4         | 0.31%   |
| ASUS G75VW                                 | 4         | 0.31%   |
| Lenovo Z50-70 20354                        | 3         | 0.23%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS         | 3         | 0.23%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW005NMX | 3         | 0.23%   |
| Lenovo IdeaPad 1 14ADA05 82GW              | 3         | 0.23%   |
| Lenovo G50-30 80G0                         | 3         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 201       | 15.57%  |
| HP EliteBook          | 99        | 7.67%   |
| Dell Latitude         | 78        | 6.04%   |
| Acer Aspire           | 59        | 4.57%   |
| Lenovo IdeaPad        | 52        | 4.03%   |
| Dell XPS              | 50        | 3.87%   |
| HP ProBook            | 44        | 3.41%   |
| Dell Precision        | 43        | 3.33%   |
| HP Pavilion           | 41        | 3.18%   |
| HP ZBook              | 27        | 2.09%   |
| ASUS ROG              | 24        | 1.86%   |
| ASUS VivoBook         | 23        | 1.78%   |
| HP Laptop             | 19        | 1.47%   |
| Acer Swift            | 17        | 1.32%   |
| ASUS ZenBook          | 16        | 1.24%   |
| Toshiba Satellite     | 15        | 1.16%   |
| HP Compaq             | 14        | 1.08%   |
| Lenovo Yoga           | 13        | 1.01%   |
| Unknown               | 13        | 1.01%   |
| Lenovo Legion         | 12        | 0.93%   |
| Dell Inspiron         | 11        | 0.85%   |
| Valve Jupiter         | 10        | 0.77%   |
| Fujitsu LIFEBOOK      | 10        | 0.77%   |
| Packard Bell EasyNote | 9         | 0.7%    |
| ASUS ASUS             | 9         | 0.7%    |
| Dell Vostro           | 8         | 0.62%   |
| Apple MacBookPro11    | 8         | 0.62%   |
| Acer Nitro            | 8         | 0.62%   |
| HP ENVY               | 7         | 0.54%   |
| Apple MacBookAir7     | 7         | 0.54%   |
| Acer Predator         | 7         | 0.54%   |
| Apple MacBookPro9     | 6         | 0.46%   |
| Apple MacBookPro8     | 6         | 0.46%   |
| Apple MacBookPro12    | 5         | 0.39%   |
| Apple MacBookAir6     | 5         | 0.39%   |
| MSI Katana            | 4         | 0.31%   |
| MSI GF63              | 4         | 0.31%   |
| HP Presario           | 4         | 0.31%   |
| HP OMEN               | 4         | 0.31%   |
| ASUS TUF              | 4         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 128       | 9.91%   |
| 2019    | 106       | 8.21%   |
| 2018    | 106       | 8.21%   |
| 2020    | 104       | 8.06%   |
| 2013    | 104       | 8.06%   |
| 2012    | 94        | 7.28%   |
| 2017    | 86        | 6.66%   |
| 2011    | 84        | 6.51%   |
| 2014    | 83        | 6.43%   |
| 2015    | 70        | 5.42%   |
| 2016    | 64        | 4.96%   |
| 2010    | 61        | 4.73%   |
| 2022    | 57        | 4.42%   |
| 2008    | 42        | 3.25%   |
| 2023    | 32        | 2.48%   |
| 2007    | 28        | 2.17%   |
| 2009    | 23        | 1.78%   |
| 2006    | 9         | 0.7%    |
| 2005    | 6         | 0.46%   |
| 2024    | 2         | 0.15%   |
| 2004    | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1291      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1134      | 87.16%  |
| Enabled  | 167       | 12.84%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1278      | 98.99%  |
| Yes  | 13        | 1.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 372       | 28.53%  |
| 16.01-24.0  | 254       | 19.48%  |
| 8.01-16.0   | 235       | 18.02%  |
| 3.01-4.0    | 206       | 15.8%   |
| 32.01-64.0  | 152       | 11.66%  |
| 1.01-2.0    | 40        | 3.07%   |
| 24.01-32.0  | 19        | 1.46%   |
| 64.01-256.0 | 12        | 0.92%   |
| 2.01-3.0    | 9         | 0.69%   |
| 0.51-1.0    | 5         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 456       | 32.2%   |
| 2.01-3.0   | 354       | 25%     |
| 4.01-8.0   | 248       | 17.51%  |
| 3.01-4.0   | 216       | 15.25%  |
| 0.51-1.0   | 60        | 4.24%   |
| 8.01-16.0  | 55        | 3.88%   |
| 16.01-24.0 | 13        | 0.92%   |
| 0.01-0.5   | 11        | 0.78%   |
| 24.01-32.0 | 2         | 0.14%   |
| 32.01-64.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1049      | 79.95%  |
| 2      | 226       | 17.23%  |
| 3      | 24        | 1.83%   |
| 0      | 8         | 0.61%   |
| 4      | 4         | 0.3%    |
| 5      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 936       | 72.28%  |
| Yes       | 359       | 27.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1023      | 78.87%  |
| No        | 274       | 21.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1279      | 99.07%  |
| No        | 12        | 0.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1087      | 83.1%   |
| No        | 221       | 16.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 1291      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Stockholm         | 275       | 19.66%  |
| Gothenburg        | 137       | 9.79%   |
| Malmo             | 66        | 4.72%   |
| Uppsala           | 35        | 2.5%    |
| Lund              | 20        | 1.43%   |
| Bromma            | 20        | 1.43%   |
| Linköping        | 19        | 1.36%   |
| Västerås        | 18        | 1.29%   |
| Solna             | 17        | 1.22%   |
| Saltsjoe-Boo      | 17        | 1.22%   |
| Örebro           | 17        | 1.22%   |
| Sollentuna        | 16        | 1.14%   |
| Huddinge          | 15        | 1.07%   |
| Vaxjo             | 14        | 1%      |
| Umeå             | 14        | 1%      |
| Norrköping       | 13        | 0.93%   |
| Sundsvall         | 12        | 0.86%   |
| Bandhagen         | 12        | 0.86%   |
| Vaestra Froelunda | 11        | 0.79%   |
| Sundbyberg        | 11        | 0.79%   |
| Karlskrona        | 11        | 0.79%   |
| Helsingborg       | 10        | 0.71%   |
| Halmstad          | 10        | 0.71%   |
| Gävle            | 10        | 0.71%   |
| Taby              | 9         | 0.64%   |
| Södertälje      | 9         | 0.64%   |
| Norsborg          | 9         | 0.64%   |
| Kista             | 9         | 0.64%   |
| Karlstad          | 9         | 0.64%   |
| Jönköping       | 9         | 0.64%   |
| Haegersten        | 9         | 0.64%   |
| Spanga            | 8         | 0.57%   |
| Landskrona        | 8         | 0.57%   |
| Staffanstorp      | 7         | 0.5%    |
| Moelndal          | 7         | 0.5%    |
| Mjoelby           | 7         | 0.5%    |
| Luleå            | 7         | 0.5%    |
| Katrineholm       | 7         | 0.5%    |
| Borlänge         | 7         | 0.5%    |
| Akersberga        | 7         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 337       | 456    | 21.98%  |
| WDC                            | 131       | 160    | 8.55%   |
| Seagate                        | 105       | 126    | 6.85%   |
| SanDisk                        | 104       | 133    | 6.78%   |
| Kingston                       | 104       | 136    | 6.78%   |
| Toshiba                        | 101       | 128    | 6.59%   |
| Intel                          | 97        | 109    | 6.33%   |
| SK hynix                       | 91        | 100    | 5.94%   |
| Unknown                        | 76        | 93     | 4.96%   |
| Micron Technology              | 63        | 70     | 4.11%   |
| Hitachi                        | 41        | 48     | 2.67%   |
| Apple                          | 37        | 46     | 2.41%   |
| HGST                           | 33        | 39     | 2.15%   |
| Crucial                        | 27        | 36     | 1.76%   |
| LITEON                         | 18        | 23     | 1.17%   |
| KIOXIA                         | 18        | 19     | 1.17%   |
| Kingston Technology Company    | 15        | 15     | 0.98%   |
| OCZ                            | 9         | 9      | 0.59%   |
| A-DATA Technology              | 9         | 9      | 0.59%   |
| LITEONIT                       | 8         | 13     | 0.52%   |
| Phison Electronics             | 6         | 6      | 0.39%   |
| Intenso                        | 6         | 6      | 0.39%   |
| Phison                         | 5         | 5      | 0.33%   |
| Fujitsu                        | 5         | 7      | 0.33%   |
| Transcend                      | 4         | 4      | 0.26%   |
| Lenovo                         | 4         | 4      | 0.26%   |
| China                          | 4         | 4      | 0.26%   |
| Unknown                        | 4         | 4      | 0.26%   |
| Union Memory                   | 3         | 3      | 0.2%    |
| Silicon Motion                 | 3         | 15     | 0.2%    |
| PNY                            | 3         | 3      | 0.2%    |
| Micron/Crucial Technology      | 3         | 4      | 0.2%    |
| JMicron Technology             | 3         | 3      | 0.2%    |
| Star Drive                     | 2         | 2      | 0.13%   |
| SSSTC                          | 2         | 3      | 0.13%   |
| SSK                            | 2         | 2      | 0.13%   |
| Solid State Storage Technology | 2         | 2      | 0.13%   |
| ROG                            | 2         | 2      | 0.13%   |
| O2 Micro                       | 2         | 2      | 0.13%   |
| M4-CT128                       | 2         | 2      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 20        | 1.26%   |
| Kingston SA400S37480G 480GB SSD                    | 14        | 0.88%   |
| Kingston SA400S37120G 120GB SSD                    | 13        | 0.82%   |
| Toshiba NVMe SSD Drive 512GB                       | 12        | 0.76%   |
| SanDisk NVMe SSD Drive 512GB                       | 12        | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB  | 12        | 0.76%   |
| Unknown MMC Card  32GB                             | 11        | 0.69%   |
| SK hynix NVMe SSD Drive 512GB                      | 11        | 0.69%   |
| Samsung SSD 850 EVO 250GB                          | 11        | 0.69%   |
| Samsung NVMe SSD Drive 512GB                       | 11        | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 11        | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 10        | 0.63%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 10        | 0.63%   |
| Kingston SA400S37240G 240GB SSD                    | 10        | 0.63%   |
| Unknown MMC Card  64GB                             | 9         | 0.57%   |
| Seagate ST9500325AS 500GB                          | 9         | 0.57%   |
| Samsung SSD 860 EVO 500GB                          | 9         | 0.57%   |
| Samsung SSD 850 EVO 500GB                          | 9         | 0.57%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 9         | 0.57%   |
| Samsung NVMe SSD Drive 1024GB                      | 9         | 0.57%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                | 9         | 0.57%   |
| HGST HTS721010A9E630 1TB                           | 9         | 0.57%   |
| Unknown MMC Card  16GB                             | 8         | 0.5%    |
| Toshiba XG6 NVMe SSD Controller 1024GB             | 8         | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB                           | 7         | 0.44%   |
| Unknown MMC Card  128GB                            | 7         | 0.44%   |
| Seagate ST500LT012-1DG142 500GB                    | 7         | 0.44%   |
| Intel NVMe SSD Drive 256GB                         | 7         | 0.44%   |
| Toshiba XG4 NVMe SSD Controller 512GB              | 6         | 0.38%   |
| Toshiba NVMe SSD Drive 256GB                       | 6         | 0.38%   |
| Seagate ST320LT007-9ZV142 320GB                    | 6         | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB                       | 6         | 0.38%   |
| Kingston SUV400S37120G 120GB SSD                   | 6         | 0.38%   |
| Intel SSDPEKNW010T8 1TB                            | 6         | 0.38%   |
| Intel SSDPEKNU512GZ 512GB                          | 6         | 0.38%   |
| Apple SSD SM0256G 256GB                            | 6         | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 5         | 0.32%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB             | 5         | 0.32%   |
| SK hynix SC311 SATA 256GB SSD                      | 5         | 0.32%   |
| Seagate ST1000LM035-1RK172 1TB                     | 5         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 101       | 120    | 32.37%  |
| WDC                 | 71        | 88     | 22.76%  |
| Hitachi             | 41        | 48     | 13.14%  |
| Toshiba             | 39        | 48     | 12.5%   |
| HGST                | 33        | 39     | 10.58%  |
| Samsung Electronics | 8         | 8      | 2.56%   |
| Fujitsu             | 5         | 7      | 1.6%    |
| Apple               | 4         | 4      | 1.28%   |
| Unknown             | 3         | 4      | 0.96%   |
| JMicron Technology  | 2         | 2      | 0.64%   |
| TO Exter            | 1         | 1      | 0.32%   |
| Intenso             | 1         | 1      | 0.32%   |
| HGST HTS            | 1         | 1      | 0.32%   |
| ASMT                | 1         | 1      | 0.32%   |
| Unknown             | 1         | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 155       | 225    | 27.43%  |
| Kingston            | 82        | 111    | 14.51%  |
| SanDisk             | 54        | 67     | 9.56%   |
| Intel               | 49        | 55     | 8.67%   |
| Micron Technology   | 30        | 34     | 5.31%   |
| Apple               | 28        | 34     | 4.96%   |
| WDC                 | 26        | 32     | 4.6%    |
| Crucial             | 26        | 35     | 4.6%    |
| SK hynix            | 21        | 23     | 3.72%   |
| LITEON              | 17        | 22     | 3.01%   |
| Toshiba             | 14        | 22     | 2.48%   |
| OCZ                 | 9         | 9      | 1.59%   |
| LITEONIT            | 8         | 13     | 1.42%   |
| A-DATA Technology   | 5         | 5      | 0.88%   |
| Transcend           | 4         | 4      | 0.71%   |
| Intenso             | 4         | 4      | 0.71%   |
| China               | 4         | 4      | 0.71%   |
| PNY                 | 3         | 3      | 0.53%   |
| M4-CT128            | 2         | 2      | 0.35%   |
| KingSpec            | 2         | 2      | 0.35%   |
| Corsair             | 2         | 2      | 0.35%   |
| Verbatim            | 1         | 4      | 0.18%   |
| Unknown             | 1         | 1      | 0.18%   |
| Team                | 1         | 1      | 0.18%   |
| Star                | 1         | 1      | 0.18%   |
| SSSTC               | 1         | 2      | 0.18%   |
| Seagate             | 1         | 1      | 0.18%   |
| Radeon              | 1         | 2      | 0.18%   |
| OCZ-VERTEX3         | 1         | 1      | 0.18%   |
| Netac               | 1         | 1      | 0.18%   |
| Neo                 | 1         | 1      | 0.18%   |
| MyDigitalSSD        | 1         | 1      | 0.18%   |
| Maxtor              | 1         | 1      | 0.18%   |
| Lexar               | 1         | 1      | 0.18%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.18%   |
| KingFast            | 1         | 1      | 0.18%   |
| JD                  | 1         | 1      | 0.18%   |
| GOODRAM             | 1         | 1      | 0.18%   |
| FORESEE             | 1         | 1      | 0.18%   |
| Colorful            | 1         | 1      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 538       | 692    | 37.13%  |
| SSD     | 521       | 733    | 35.96%  |
| HDD     | 303       | 373    | 20.91%  |
| MMC     | 75        | 90     | 5.18%   |
| Unknown | 12        | 12     | 0.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 752       | 1080   | 53.6%   |
| NVMe | 536       | 687    | 38.2%   |
| MMC  | 75        | 90     | 5.35%   |
| SAS  | 40        | 43     | 2.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 635       | 884    | 78.11%  |
| 0.51-1.0   | 158       | 200    | 19.43%  |
| 1.01-2.0   | 14        | 16     | 1.72%   |
| 3.01-4.0   | 3         | 3      | 0.37%   |
| 4.01-10.0  | 2         | 2      | 0.25%   |
| 10.01-20.0 | 1         | 1      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 446       | 32.92%  |
| 251-500        | 344       | 25.39%  |
| 501-1000       | 190       | 14.02%  |
| 1-20           | 96        | 7.08%   |
| 1001-2000      | 80        | 5.9%    |
| 51-100         | 74        | 5.46%   |
| Unknown        | 59        | 4.35%   |
| 21-50          | 38        | 2.8%    |
| More than 3000 | 16        | 1.18%   |
| 2001-3000      | 12        | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 559       | 39.96%  |
| 21-50          | 245       | 17.51%  |
| 101-250        | 213       | 15.23%  |
| 51-100         | 165       | 11.79%  |
| 251-500        | 80        | 5.72%   |
| Unknown        | 59        | 4.22%   |
| 501-1000       | 56        | 4%      |
| 1001-2000      | 17        | 1.22%   |
| More than 3000 | 2         | 0.14%   |
| 2001-3000      | 2         | 0.14%   |
| 0              | 1         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 4         | 4      | 6.35%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 3         | 4      | 4.76%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 2      | 3.17%   |
| Seagate ST9250410AS 250GB                           | 2         | 3      | 3.17%   |
| Intel SSDSC2BW240A4 240GB                           | 2         | 3      | 3.17%   |
| HGST HTS725032A7E630 320GB                          | 2         | 2      | 3.17%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 3.17%   |
| Union Memory UMIS RPJTJ128MED1MWX 128GB             | 1         | 1      | 1.59%   |
| Transcend TS240GMTS420S 240GB SSD                   | 1         | 1      | 1.59%   |
| Toshiba MK6465GSX 640GB                             | 1         | 1      | 1.59%   |
| Toshiba MK4026GAX RoHS 40GB                         | 1         | 2      | 1.59%   |
| Toshiba MK1633GSG 160GB                             | 1         | 1      | 1.59%   |
| Toshiba MK1237GSX 120GB                             | 1         | 1      | 1.59%   |
| Team L5 LITE SSD 240GB                              | 1         | 1      | 1.59%   |
| SK hynix SH920 mSATA 128GB SSD                      | 1         | 1      | 1.59%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD               | 1         | 1      | 1.59%   |
| Silicon Motion 1TB PCS PCIe M.2 SSD                 | 1         | 1      | 1.59%   |
| Seagate ST980817AS 80GB                             | 1         | 1      | 1.59%   |
| Seagate ST96812A 64GB                               | 1         | 1      | 1.59%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 1.59%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 1.59%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 1.59%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 1.59%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 2      | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 1.59%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD                 | 1         | 1      | 1.59%   |
| Samsung Electronics SSD PM810 2.5 7mm 256GB         | 1         | 1      | 1.59%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 1.59%   |
| Samsung Electronics MZ7PA128HMCD-010L1 128GB SSD    | 1         | 1      | 1.59%   |
| OCZ AGILITY3 120GB SSD                              | 1         | 1      | 1.59%   |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 1.59%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD      | 1         | 1      | 1.59%   |
| LITEONIT LMT-256M6M-HP 256GB SSD                    | 1         | 1      | 1.59%   |
| Intel SSDSCKJF180A5H RSED 180GB                     | 1         | 1      | 1.59%   |
| Intel SSDSC2BW480A4 480GB                           | 1         | 1      | 1.59%   |
| Intel SSDSA2BW160G3H 160GB                          | 1         | 1      | 1.59%   |
| Hitachi HTS727550A9E364 500GB                       | 1         | 1      | 1.59%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 1.59%   |
| Hitachi HTS545050B9SA02 500GB                       | 1         | 3      | 1.59%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 1.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 16     | 22.22%  |
| Hitachi             | 8         | 10     | 12.7%   |
| HGST                | 8         | 9      | 12.7%   |
| Micron Technology   | 5         | 6      | 7.94%   |
| Intel               | 5         | 6      | 7.94%   |
| Toshiba             | 4         | 5      | 6.35%   |
| Samsung Electronics | 3         | 3      | 4.76%   |
| WDC                 | 2         | 2      | 3.17%   |
| SK hynix            | 2         | 2      | 3.17%   |
| Union Memory        | 1         | 1      | 1.59%   |
| Transcend           | 1         | 1      | 1.59%   |
| Team                | 1         | 1      | 1.59%   |
| Silicon Motion      | 1         | 1      | 1.59%   |
| SanDisk             | 1         | 1      | 1.59%   |
| OCZ                 | 1         | 1      | 1.59%   |
| LITEONIT            | 1         | 1      | 1.59%   |
| Crucial             | 1         | 2      | 1.59%   |
| Corsair             | 1         | 1      | 1.59%   |
| China               | 1         | 1      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |
| ADATA Technology    | 1         | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 16     | 37.84%  |
| Hitachi | 8         | 10     | 21.62%  |
| HGST    | 8         | 9      | 21.62%  |
| Toshiba | 4         | 5      | 10.81%  |
| WDC     | 2         | 2      | 5.41%   |
| Apple   | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 43     | 58.73%  |
| SSD  | 23        | 26     | 36.51%  |
| NVMe | 3         | 3      | 4.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                         | Notebooks | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 1TB | 1         | 1      | 50%     |
| Hitachi HTS727575A9E364 752GB                                 | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Hitachi             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 782       | 1162   | 57.54%  |
| Works    | 514       | 664    | 37.82%  |
| Malfunc  | 61        | 72     | 4.49%   |
| Failed   | 2         | 2      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 801       | 53.65%  |
| Samsung Electronics              | 196       | 13.13%  |
| AMD                              | 135       | 9.04%   |
| SanDisk                          | 81        | 5.43%   |
| SK hynix                         | 69        | 4.62%   |
| Toshiba America Info Systems     | 52        | 3.48%   |
| Kingston Technology Company      | 36        | 2.41%   |
| Micron Technology                | 33        | 2.21%   |
| KIOXIA                           | 15        | 1%      |
| Phison Electronics               | 13        | 0.87%   |
| Nvidia                           | 12        | 0.8%    |
| Marvell Technology Group         | 7         | 0.47%   |
| ADATA Technology                 | 6         | 0.4%    |
| Silicon Motion                   | 5         | 0.33%   |
| Apple                            | 5         | 0.33%   |
| Union Memory (Shenzhen)          | 4         | 0.27%   |
| Solid State Storage Technology   | 4         | 0.27%   |
| Lite-On Technology               | 4         | 0.27%   |
| Lenovo                           | 4         | 0.27%   |
| Silicon Integrated Systems [SiS] | 3         | 0.2%    |
| Micron/Crucial Technology        | 3         | 0.2%    |
| Realtek Semiconductor            | 2         | 0.13%   |
| O2 Micro                         | 2         | 0.13%   |
| Seagate Technology               | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 113       | 7.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 102       | 6.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 87        | 5.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 86        | 5.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 64        | 4.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 64        | 4.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 51        | 3.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 46        | 2.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 40        | 2.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 38        | 2.4%    |
| Intel Volume Management Device NVMe RAID Controller                            | 34        | 2.15%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 33        | 2.08%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 33        | 2.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 27        | 1.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 25        | 1.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 25        | 1.58%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 24        | 1.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 22        | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 22        | 1.39%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 21        | 1.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 20        | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 18        | 1.14%   |
| Intel SSD 660P Series                                                          | 17        | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 16        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 16        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 14        | 0.88%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 13        | 0.82%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 13        | 0.82%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 13        | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13        | 0.82%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 11        | 0.69%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 11        | 0.69%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 10        | 0.63%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 10        | 0.63%   |
| Intel SSD 600P Series                                                          | 10        | 0.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 0.63%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 9         | 0.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 9         | 0.57%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 8         | 0.51%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 8         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 794       | 51.96%  |
| NVMe | 538       | 35.21%  |
| RAID | 110       | 7.2%    |
| IDE  | 86        | 5.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1047      | 81.1%   |
| AMD     | 243       | 18.82%  |
| Unknown | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 28        | 2.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 28        | 2.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 22        | 1.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 19        | 1.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 19        | 1.47%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 17        | 1.32%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 16        | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 14        | 1.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 14        | 1.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 13        | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 12        | 0.93%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 12        | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 11        | 0.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 11        | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 11        | 0.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 11        | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 11        | 0.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 10        | 0.77%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 10        | 0.77%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 10        | 0.77%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 10        | 0.77%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 10        | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 10        | 0.77%   |
| AMD Custom APU 0405                     | 10        | 0.77%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz       | 9         | 0.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz      | 9         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 9         | 0.7%    |
| Intel Core i7-5600U CPU @ 2.60GHz       | 8         | 0.62%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 8         | 0.62%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 8         | 0.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 8         | 0.62%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 8         | 0.62%   |
| Intel 12th Gen Core i7-12700H           | 8         | 0.62%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 8         | 0.62%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 8         | 0.62%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 7         | 0.54%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 7         | 0.54%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 7         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i7                        | 346       | 26.8%   |
| Intel Core i5                        | 325       | 25.17%  |
| Other                                | 152       | 11.77%  |
| Intel Core i3                        | 66        | 5.11%   |
| AMD Ryzen 7                          | 60        | 4.65%   |
| Intel Core 2 Duo                     | 48        | 3.72%   |
| Intel Celeron                        | 46        | 3.56%   |
| AMD Ryzen 5                          | 43        | 3.33%   |
| AMD Ryzen 9                          | 18        | 1.39%   |
| Intel Pentium                        | 16        | 1.24%   |
| Intel Atom                           | 14        | 1.08%   |
| AMD A8                               | 14        | 1.08%   |
| Intel Genuine                        | 11        | 0.85%   |
| AMD Ryzen 3                          | 11        | 0.85%   |
| AMD A6                               | 11        | 0.85%   |
| Intel Core 2                         | 10        | 0.77%   |
| AMD Ryzen 7 PRO                      | 10        | 0.77%   |
| AMD E1                               | 8         | 0.62%   |
| AMD A4                               | 7         | 0.54%   |
| AMD A10                              | 7         | 0.54%   |
| Intel Xeon                           | 6         | 0.46%   |
| Intel Core i9                        | 6         | 0.46%   |
| AMD Ryzen 5 PRO                      | 6         | 0.46%   |
| AMD E                                | 5         | 0.39%   |
| Intel Pentium Silver                 | 4         | 0.31%   |
| Intel Pentium M                      | 4         | 0.31%   |
| Intel Pentium Dual                   | 4         | 0.31%   |
| Intel Core m3                        | 3         | 0.23%   |
| Intel Celeron Dual-Core              | 3         | 0.23%   |
| AMD Turion 64 X2 Mobile              | 3         | 0.23%   |
| AMD Sempron                          | 2         | 0.15%   |
| AMD Athlon II Dual-Core              | 2         | 0.15%   |
| AMD Athlon II                        | 2         | 0.15%   |
| AMD Athlon 64 X2                     | 2         | 0.15%   |
| Intel Pentium Dual-Core              | 1         | 0.08%   |
| Intel Core m7                        | 1         | 0.08%   |
| Intel Core m5                        | 1         | 0.08%   |
| Intel Core                           | 1         | 0.08%   |
| Intel Celeron M                      | 1         | 0.08%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 606       | 46.94%  |
| 4      | 417       | 32.3%   |
| 8      | 105       | 8.13%   |
| 6      | 95        | 7.36%   |
| 14     | 19        | 1.47%   |
| 1      | 19        | 1.47%   |
| 10     | 14        | 1.08%   |
| 12     | 12        | 0.93%   |
| 24     | 2         | 0.15%   |
| 16     | 2         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1291      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1036      | 80.06%  |
| 1      | 258       | 19.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1268      | 97.99%  |
| Unknown        | 16        | 1.24%   |
| 32-bit         | 9         | 0.7%    |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 444       | 33.04%  |
| 0x306a9    | 63        | 4.69%   |
| 0x206a7    | 52        | 3.87%   |
| 0x40651    | 48        | 3.57%   |
| 0x806c1    | 47        | 3.5%    |
| 0x306d4    | 45        | 3.35%   |
| 0x306c3    | 44        | 3.27%   |
| 0x406e3    | 43        | 3.2%    |
| 0x806ea    | 40        | 2.98%   |
| 0x806ec    | 38        | 2.83%   |
| 0x806e9    | 35        | 2.6%    |
| 0x906ea    | 26        | 1.93%   |
| 0x906e9    | 25        | 1.86%   |
| 0x20655    | 25        | 1.86%   |
| 0x1067a    | 24        | 1.79%   |
| 0x0a50000c | 19        | 1.41%   |
| 0xa0652    | 13        | 0.97%   |
| 0x08600106 | 13        | 0.97%   |
| 0x806eb    | 12        | 0.89%   |
| 0x6fd      | 12        | 0.89%   |
| 0x08608103 | 11        | 0.82%   |
| 0x0700010f | 11        | 0.82%   |
| 0x906a3    | 10        | 0.74%   |
| 0x806d1    | 10        | 0.74%   |
| 0x406c4    | 10        | 0.74%   |
| 0x08108109 | 10        | 0.74%   |
| 0x506e3    | 9         | 0.67%   |
| 0x30678    | 9         | 0.67%   |
| 0x20652    | 8         | 0.6%    |
| 0x0810100b | 8         | 0.6%    |
| 0x706e5    | 7         | 0.52%   |
| 0x6fb      | 7         | 0.52%   |
| 0x6f6      | 7         | 0.52%   |
| 0x0a404102 | 7         | 0.52%   |
| 0x08108102 | 7         | 0.52%   |
| 0x06001119 | 7         | 0.52%   |
| 0x05000119 | 7         | 0.52%   |
| 0x906ed    | 6         | 0.45%   |
| 0x10676    | 6         | 0.45%   |
| 0x0a50000d | 6         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 267       | 20.67%  |
| Haswell           | 122       | 9.44%   |
| IvyBridge         | 90        | 6.97%   |
| SandyBridge       | 82        | 6.35%   |
| Unknown           | 81        | 6.27%   |
| Skylake           | 73        | 5.65%   |
| TigerLake         | 63        | 4.88%   |
| Broadwell         | 55        | 4.26%   |
| Zen 3             | 46        | 3.56%   |
| Westmere          | 43        | 3.33%   |
| Penryn            | 41        | 3.17%   |
| Silvermont        | 39        | 3.02%   |
| Core              | 37        | 2.86%   |
| Zen 2             | 30        | 2.32%   |
| Alderlake Hybrid  | 30        | 2.32%   |
| CometLake         | 24        | 1.86%   |
| Icelake           | 22        | 1.7%    |
| Zen+              | 20        | 1.55%   |
| Excavator         | 15        | 1.16%   |
| Zen               | 14        | 1.08%   |
| Piledriver        | 12        | 0.93%   |
| Jaguar            | 11        | 0.85%   |
| Puma              | 10        | 0.77%   |
| Goldmont plus     | 10        | 0.77%   |
| K8 Hammer         | 7         | 0.54%   |
| Bobcat            | 7         | 0.54%   |
| P6                | 6         | 0.46%   |
| K10 Llano         | 6         | 0.46%   |
| K10               | 6         | 0.46%   |
| Bonnell           | 6         | 0.46%   |
| Goldmont          | 5         | 0.39%   |
| Nehalem           | 4         | 0.31%   |
| K8 & K10 hybrid   | 4         | 0.31%   |
| Steamroller       | 2         | 0.15%   |
| Tremont           | 1         | 0.08%   |
| Meteorlake Hybrid | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 945       | 58.62%  |
| Nvidia                           | 372       | 23.08%  |
| AMD                              | 292       | 18.11%  |
| Silicon Integrated Systems [SiS] | 3         | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 77        | 4.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 74        | 4.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 63        | 3.78%   |
| Intel UHD Graphics 620                                                                   | 60        | 3.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 57        | 3.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 55        | 3.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 48        | 2.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 47        | 2.82%   |
| Intel HD Graphics 620                                                                    | 42        | 2.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 42        | 2.52%   |
| Intel HD Graphics 5500                                                                   | 40        | 2.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 36        | 2.16%   |
| Intel HD Graphics 630                                                                    | 30        | 1.8%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 30        | 1.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 29        | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 1.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 24        | 1.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 21        | 1.26%   |
| AMD Lucienne                                                                             | 21        | 1.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 1.2%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 1.08%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 18        | 1.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 1.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 16        | 0.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 16        | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 0.9%    |
| AMD Rembrandt [Radeon 680M]                                                              | 14        | 0.84%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 13        | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.66%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 10        | 0.6%    |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 10        | 0.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 0.6%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 10        | 0.6%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 9         | 0.54%   |
| Nvidia GM108M [GeForce 840M]                                                             | 9         | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 0.48%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 8         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 662       | 51.12%  |
| Intel + Nvidia | 247       | 19.07%  |
| 1 x AMD        | 189       | 14.59%  |
| 1 x Nvidia     | 84        | 6.49%   |
| AMD + Nvidia   | 41        | 3.17%   |
| Intel + AMD    | 33        | 2.55%   |
| 2 x AMD        | 29        | 2.24%   |
| 2 x Intel      | 5         | 0.39%   |
| 1 x SiS        | 3         | 0.23%   |
| Other          | 2         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1066      | 81.5%   |
| Proprietary | 209       | 15.98%  |
| Unknown     | 33        | 2.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 891       | 67.55%  |
| 0.01-0.5   | 145       | 10.99%  |
| 1.01-2.0   | 128       | 9.7%    |
| 0.51-1.0   | 61        | 4.62%   |
| 3.01-4.0   | 57        | 4.32%   |
| 7.01-8.0   | 17        | 1.29%   |
| 5.01-6.0   | 14        | 1.06%   |
| 2.01-3.0   | 5         | 0.38%   |
| 8.01-16.0  | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 325       | 21.64%  |
| LG Display              | 195       | 12.98%  |
| Chimei Innolux          | 186       | 12.38%  |
| Samsung Electronics     | 156       | 10.39%  |
| BOE                     | 121       | 8.06%   |
| Sharp                   | 67        | 4.46%   |
| Apple                   | 57        | 3.79%   |
| Dell                    | 47        | 3.13%   |
| Lenovo                  | 37        | 2.46%   |
| Philips                 | 25        | 1.66%   |
| Chi Mei Optoelectronics | 25        | 1.66%   |
| Hewlett-Packard         | 24        | 1.6%    |
| InfoVision              | 23        | 1.53%   |
| CSO                     | 21        | 1.4%    |
| LG Philips              | 18        | 1.2%    |
| BenQ                    | 16        | 1.07%   |
| PANDA                   | 14        | 0.93%   |
| Goldstar                | 14        | 0.93%   |
| ASUSTek Computer        | 14        | 0.93%   |
| AOC                     | 12        | 0.8%    |
| Ancor Communications    | 12        | 0.8%    |
| Acer                    | 12        | 0.8%    |
| Panasonic               | 7         | 0.47%   |
| Valve                   | 6         | 0.4%    |
| Sony                    | 6         | 0.4%    |
| LGD                     | 5         | 0.33%   |
| BOE Technology Group    | 5         | 0.33%   |
| Vestel Elektronik       | 4         | 0.27%   |
| Quanta Display          | 4         | 0.27%   |
| Unknown                 | 3         | 0.2%    |
| Toshiba                 | 3         | 0.2%    |
| Eizo                    | 3         | 0.2%    |
| Analogix                | 3         | 0.2%    |
| TMX                     | 2         | 0.13%   |
| Nvidia                  | 2         | 0.13%   |
| Fujitsu Siemens         | 2         | 0.13%   |
| CPT                     | 2         | 0.13%   |
| VOXICON                 | 1         | 0.07%   |
| ViewSonic               | 1         | 0.07%   |
| TCL                     | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 17        | 1.12%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 13        | 0.85%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 12        | 0.79%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 12        | 0.79%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 9         | 0.59%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 8         | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.53%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 0.46%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 6         | 0.39%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 6         | 0.39%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 6         | 0.39%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 6         | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 6         | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 6         | 0.39%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 6         | 0.39%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 5         | 0.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 5         | 0.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5         | 0.33%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                 | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.33%   |
| AU Optronics LCD Monitor AUOA48F 1920x1080 309x174mm 14.0-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 5         | 0.33%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 5         | 0.33%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 4         | 0.26%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 4         | 0.26%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 4         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 4         | 0.26%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch          | 4         | 0.26%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 4         | 0.26%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 4         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 624       | 43.58%  |
| 1366x768 (WXGA)    | 299       | 20.88%  |
| 3840x2160 (4K)     | 89        | 6.22%   |
| 2560x1440 (QHD)    | 65        | 4.54%   |
| 1280x800 (WXGA)    | 51        | 3.56%   |
| 1920x1200 (WUXGA)  | 49        | 3.42%   |
| 1600x900 (HD+)     | 48        | 3.35%   |
| 2560x1600          | 34        | 2.37%   |
| 2880x1800          | 27        | 1.89%   |
| 1440x900 (WXGA+)   | 26        | 1.82%   |
| 1680x1050 (WSXGA+) | 18        | 1.26%   |
| 3840x2400          | 17        | 1.19%   |
| 3440x1440          | 15        | 1.05%   |
| 800x1280           | 9         | 0.63%   |
| 3200x1800 (QHD+)   | 8         | 0.56%   |
| 1024x768 (XGA)     | 6         | 0.42%   |
| 1280x1024 (SXGA)   | 5         | 0.35%   |
| 1024x600           | 5         | 0.35%   |
| 3200x2000          | 4         | 0.28%   |
| 2160x1440          | 4         | 0.28%   |
| 1920x540           | 4         | 0.28%   |
| 1360x768           | 4         | 0.28%   |
| Unknown            | 4         | 0.28%   |
| 2288x1287          | 3         | 0.21%   |
| 3840x1080          | 2         | 0.14%   |
| 2560x1080          | 2         | 0.14%   |
| 1920x1280          | 2         | 0.14%   |
| 3840x1600          | 1         | 0.07%   |
| 3840x1100          | 1         | 0.07%   |
| 3456x2160          | 1         | 0.07%   |
| 2880x1920          | 1         | 0.07%   |
| 2560x1700          | 1         | 0.07%   |
| 2240x1400          | 1         | 0.07%   |
| 1680x945           | 1         | 0.07%   |
| 1400x1050          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 474       | 31.52%  |
| 13      | 289       | 19.22%  |
| 14      | 205       | 13.63%  |
| 17      | 86        | 5.72%   |
| 27      | 73        | 4.85%   |
| 12      | 73        | 4.85%   |
| 24      | 57        | 3.79%   |
| 16      | 30        | 1.99%   |
| 23      | 28        | 1.86%   |
| 11      | 25        | 1.66%   |
| Unknown | 25        | 1.66%   |
| 31      | 23        | 1.53%   |
| 34      | 13        | 0.86%   |
| 22      | 9         | 0.6%    |
| 21      | 9         | 0.6%    |
| 84      | 8         | 0.53%   |
| 18      | 8         | 0.53%   |
| 32      | 6         | 0.4%    |
| 7       | 6         | 0.4%    |
| 19      | 5         | 0.33%   |
| 10      | 5         | 0.33%   |
| 65      | 4         | 0.27%   |
| 54      | 4         | 0.27%   |
| 39      | 4         | 0.27%   |
| 29      | 3         | 0.2%    |
| 25      | 3         | 0.2%    |
| 3       | 3         | 0.2%    |
| 142     | 2         | 0.13%   |
| 72      | 2         | 0.13%   |
| 42      | 2         | 0.13%   |
| 40      | 2         | 0.13%   |
| 37      | 2         | 0.13%   |
| 35      | 2         | 0.13%   |
| 33      | 2         | 0.13%   |
| 26      | 2         | 0.13%   |
| 20      | 2         | 0.13%   |
| 86      | 1         | 0.07%   |
| 85      | 1         | 0.07%   |
| 75      | 1         | 0.07%   |
| 74      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 823       | 55.38%  |
| 201-300        | 265       | 17.83%  |
| 501-600        | 143       | 9.62%   |
| 351-400        | 98        | 6.59%   |
| 601-700        | 33        | 2.22%   |
| 401-500        | 29        | 1.95%   |
| Unknown        | 25        | 1.68%   |
| 701-800        | 20        | 1.35%   |
| 1501-2000      | 13        | 0.87%   |
| 1001-1500      | 12        | 0.81%   |
| 1-100          | 9         | 0.61%   |
| 801-900        | 8         | 0.54%   |
| 901-1000       | 5         | 0.34%   |
| More than 2000 | 2         | 0.13%   |
| 101-200        | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1023      | 76.69%  |
| 16/10   | 231       | 17.32%  |
| Unknown | 22        | 1.65%   |
| 21/9    | 19        | 1.42%   |
| 3/2     | 11        | 0.82%   |
| 4/3     | 7         | 0.52%   |
| 5/4     | 6         | 0.45%   |
| 0.67    | 6         | 0.45%   |
| 6/5     | 4         | 0.3%    |
| 1.00    | 2         | 0.15%   |
| 32/9    | 1         | 0.07%   |
| 3.40    | 1         | 0.07%   |
| 0.56    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 468       | 31.2%   |
| 81-90          | 364       | 24.27%  |
| 71-80          | 129       | 8.6%    |
| 121-130        | 75        | 5%      |
| 301-350        | 74        | 4.93%   |
| 201-250        | 72        | 4.8%    |
| 61-70          | 69        | 4.6%    |
| 351-500        | 47        | 3.13%   |
| 251-300        | 32        | 2.13%   |
| 111-120        | 31        | 2.07%   |
| More than 1000 | 26        | 1.73%   |
| 51-60          | 26        | 1.73%   |
| Unknown        | 25        | 1.67%   |
| 131-140        | 14        | 0.93%   |
| 501-1000       | 11        | 0.73%   |
| 1-40           | 9         | 0.6%    |
| 151-200        | 9         | 0.6%    |
| 141-150        | 8         | 0.53%   |
| 41-50          | 6         | 0.4%    |
| 91-100         | 5         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 624       | 42.51%  |
| 101-120       | 337       | 22.96%  |
| 51-100        | 199       | 13.56%  |
| 161-240       | 179       | 12.19%  |
| More than 240 | 82        | 5.59%   |
| Unknown       | 25        | 1.7%    |
| 1-50          | 22        | 1.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1036      | 78.66%  |
| 2     | 222       | 16.86%  |
| 3     | 28        | 2.13%   |
| 0     | 28        | 2.13%   |
| 4     | 2         | 0.15%   |
| 5     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 779       | 39.44%  |
| Realtek Semiconductor                  | 514       | 26.03%  |
| Qualcomm Atheros                       | 217       | 10.99%  |
| Broadcom                               | 137       | 6.94%   |
| MediaTek                               | 49        | 2.48%   |
| Broadcom Limited                       | 44        | 2.23%   |
| Hewlett-Packard                        | 21        | 1.06%   |
| ASIX Electronics                       | 20        | 1.01%   |
| Sierra Wireless                        | 17        | 0.86%   |
| Marvell Technology Group               | 17        | 0.86%   |
| Lenovo                                 | 14        | 0.71%   |
| Dell                                   | 14        | 0.71%   |
| Ralink                                 | 13        | 0.66%   |
| Nvidia                                 | 9         | 0.46%   |
| Ericsson Business Mobile Networks      | 9         | 0.46%   |
| Qualcomm                               | 8         | 0.41%   |
| DisplayLink                            | 8         | 0.41%   |
| TP-Link                                | 7         | 0.35%   |
| FIBOCOM                                | 7         | 0.35%   |
| Huawei Technologies                    | 6         | 0.3%    |
| ASUSTek Computer                       | 6         | 0.3%    |
| Ralink Technology                      | 5         | 0.25%   |
| Samsung Electronics                    | 4         | 0.2%    |
| NetGear                                | 4         | 0.2%    |
| D-Link                                 | 4         | 0.2%    |
| Xiaomi                                 | 3         | 0.15%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.15%   |
| Texas Instruments                      | 2         | 0.1%    |
| STMicroelectronics                     | 2         | 0.1%    |
| Qualcomm Atheros Communications        | 2         | 0.1%    |
| Microsoft                              | 2         | 0.1%    |
| JMicron Technology                     | 2         | 0.1%    |
| Arduino SA                             | 2         | 0.1%    |
| ZyXEL Communications                   | 1         | 0.05%   |
| Wacom                                  | 1         | 0.05%   |
| U-Blox                                 | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| SEGGER                                 | 1         | 0.05%   |
| QinHeng Electronics                    | 1         | 0.05%   |
| Qcom                                   | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 309       | 12.42%  |
| Intel Wireless 8265 / 8275                                             | 96        | 3.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 70        | 2.81%   |
| Intel Wireless 7260                                                    | 62        | 2.49%   |
| Intel Wi-Fi 6 AX200                                                    | 62        | 2.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 56        | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 56        | 2.25%   |
| Intel Wireless 8260                                                    | 52        | 2.09%   |
| Intel Wireless 7265                                                    | 50        | 2.01%   |
| Intel Wi-Fi 6 AX201                                                    | 49        | 1.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 38        | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 35        | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 33        | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 33        | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 32        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 29        | 1.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 28        | 1.13%   |
| Intel Ethernet Connection (4) I219-V                                   | 27        | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                                  | 27        | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 26        | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 26        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 25        | 1%      |
| Intel Ethernet Connection I218-LM                                      | 25        | 1%      |
| Intel Ethernet Connection (3) I218-LM                                  | 25        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 23        | 0.92%   |
| Intel Ethernet Connection I219-LM                                      | 22        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 19        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19        | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 19        | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 18        | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 18        | 0.72%   |
| Intel Ethernet Connection I219-V                                       | 18        | 0.72%   |
| Intel Wireless 3160                                                    | 17        | 0.68%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 17        | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 17        | 0.68%   |
| Intel 82577LM Gigabit Network Connection                               | 17        | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 17        | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                          | 17        | 0.68%   |
| Intel Ethernet Connection I217-LM                                      | 16        | 0.64%   |
| Intel Ethernet Connection (6) I219-V                                   | 16        | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 746       | 54.93%  |
| Qualcomm Atheros                | 184       | 13.55%  |
| Realtek Semiconductor           | 150       | 11.05%  |
| Broadcom                        | 107       | 7.88%   |
| MediaTek                        | 49        | 3.61%   |
| Broadcom Limited                | 29        | 2.14%   |
| Sierra Wireless                 | 17        | 1.25%   |
| Ralink                          | 13        | 0.96%   |
| Dell                            | 8         | 0.59%   |
| Qualcomm                        | 7         | 0.52%   |
| FIBOCOM                         | 7         | 0.52%   |
| ASUSTek Computer                | 6         | 0.44%   |
| TP-Link                         | 5         | 0.37%   |
| Ralink Technology               | 5         | 0.37%   |
| NetGear                         | 4         | 0.29%   |
| Hewlett-Packard                 | 4         | 0.29%   |
| D-Link                          | 3         | 0.22%   |
| Qualcomm Atheros Communications | 2         | 0.15%   |
| ZyXEL Communications            | 1         | 0.07%   |
| Wacom                           | 1         | 0.07%   |
| Qcom                            | 1         | 0.07%   |
| Microsoft                       | 1         | 0.07%   |
| Micro Star International        | 1         | 0.07%   |
| Linksys                         | 1         | 0.07%   |
| IMC Networks                    | 1         | 0.07%   |
| Fujitsu Siemens Computers       | 1         | 0.07%   |
| Edimax Technology               | 1         | 0.07%   |
| D-Link System                   | 1         | 0.07%   |
| Chu Yuen Enterprise             | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 96        | 7.02%   |
| Intel Wireless 7260                                                  | 62        | 4.54%   |
| Intel Wi-Fi 6 AX200                                                  | 62        | 4.54%   |
| Intel Wireless 8260                                                  | 52        | 3.8%    |
| Intel Wireless 7265                                                  | 50        | 3.66%   |
| Intel Wi-Fi 6 AX201                                                  | 49        | 3.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 38        | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 35        | 2.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 33        | 2.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 33        | 2.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 32        | 2.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 29        | 2.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 28        | 2.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 26        | 1.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 26        | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 25        | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 23        | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 19        | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 19        | 1.39%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 19        | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 18        | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 18        | 1.32%   |
| Intel Wireless 3160                                                  | 17        | 1.24%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 17        | 1.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 17        | 1.24%   |
| Intel Centrino Advanced-N 6200                                       | 16        | 1.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 15        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 15        | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 14        | 1.02%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 14        | 1.02%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 14        | 1.02%   |
| Intel Centrino Ultimate-N 6300                                       | 13        | 0.95%   |
| Intel Centrino Advanced-N 6235                                       | 13        | 0.95%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 13        | 0.95%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 12        | 0.88%   |
| Sierra Wireless EM7455                                               | 11        | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                       | 11        | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 10        | 0.73%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 10        | 0.73%   |
| Intel Centrino Wireless-N 2230                                       | 10        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 450       | 42.33%  |
| Intel                                  | 370       | 34.81%  |
| Qualcomm Atheros                       | 67        | 6.3%    |
| Broadcom                               | 58        | 5.46%   |
| ASIX Electronics                       | 20        | 1.88%   |
| Marvell Technology Group               | 17        | 1.6%    |
| Broadcom Limited                       | 16        | 1.51%   |
| Lenovo                                 | 14        | 1.32%   |
| Nvidia                                 | 9         | 0.85%   |
| Hewlett-Packard                        | 8         | 0.75%   |
| DisplayLink                            | 8         | 0.75%   |
| Huawei Technologies                    | 5         | 0.47%   |
| Samsung Electronics                    | 4         | 0.38%   |
| Xiaomi                                 | 3         | 0.28%   |
| TP-Link                                | 2         | 0.19%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.19%   |
| JMicron Technology                     | 2         | 0.19%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| Qualcomm                               | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.09%   |
| Microsoft                              | 1         | 0.09%   |
| ICS Advent                             | 1         | 0.09%   |
| Google                                 | 1         | 0.09%   |
| Gemtek                                 | 1         | 0.09%   |
| D-Link                                 | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 309       | 28.72%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 70        | 6.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 56        | 5.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 56        | 5.2%    |
| Intel Ethernet Connection (4) I219-V                                   | 27        | 2.51%   |
| Intel Ethernet Connection (4) I219-LM                                  | 27        | 2.51%   |
| Intel Ethernet Connection I218-LM                                      | 25        | 2.32%   |
| Intel Ethernet Connection (3) I218-LM                                  | 25        | 2.32%   |
| Intel Ethernet Connection I219-LM                                      | 22        | 2.04%   |
| Intel Ethernet Connection I219-V                                       | 18        | 1.67%   |
| Intel 82577LM Gigabit Network Connection                               | 17        | 1.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 17        | 1.58%   |
| ASIX AX88179 Gigabit Ethernet                                          | 17        | 1.58%   |
| Intel Ethernet Connection I217-LM                                      | 16        | 1.49%   |
| Intel Ethernet Connection (6) I219-V                                   | 16        | 1.49%   |
| Intel Ethernet Connection (13) I219-V                                  | 15        | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 12        | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 12        | 1.12%   |
| Intel Ethernet Connection I217-V                                       | 10        | 0.93%   |
| Intel Ethernet Connection (6) I219-LM                                  | 10        | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 9         | 0.84%   |
| Intel 82579V Gigabit Network Connection                                | 9         | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 8         | 0.74%   |
| Intel 82567LM Gigabit Network Connection                               | 8         | 0.74%   |
| Intel 82566MM Gigabit Network Connection                               | 8         | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                      | 7         | 0.65%   |
| HP lt4120 Snapdragon X5 LTE                                            | 7         | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 0.56%   |
| Intel Ethernet Connection (14) I219-LM                                 | 6         | 0.56%   |
| DisplayLink Dell Universal Dock D6000                                  | 6         | 0.56%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 6         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5         | 0.46%   |
| Realtek Killer E2600 GbE Controller                                    | 5         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 5         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.46%   |
| Lenovo Thinkpad LAN                                                    | 5         | 0.46%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                                  | 5         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1279      | 54.61%  |
| Ethernet | 1018      | 43.47%  |
| Modem    | 41        | 1.75%   |
| Unknown  | 4         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1055      | 76.67%  |
| Ethernet | 320       | 23.26%  |
| Unknown  | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 898       | 69.45%  |
| 1     | 376       | 29.08%  |
| 3     | 11        | 0.85%   |
| 0     | 8         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1210      | 92.93%  |
| Yes  | 92        | 7.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 586       | 53.81%  |
| Realtek Semiconductor           | 85        | 7.81%   |
| Qualcomm Atheros Communications | 66        | 6.06%   |
| IMC Networks                    | 60        | 5.51%   |
| Broadcom                        | 58        | 5.33%   |
| Foxconn / Hon Hai               | 57        | 5.23%   |
| Apple                           | 51        | 4.68%   |
| Lite-On Technology              | 35        | 3.21%   |
| Hewlett-Packard                 | 21        | 1.93%   |
| Dell                            | 18        | 1.65%   |
| ASUSTek Computer                | 11        | 1.01%   |
| Ralink                          | 7         | 0.64%   |
| Cambridge Silicon Radio         | 7         | 0.64%   |
| Toshiba                         | 6         | 0.55%   |
| MediaTek                        | 5         | 0.46%   |
| USI                             | 3         | 0.28%   |
| Realtek                         | 3         | 0.28%   |
| Taiyo Yuden                     | 2         | 0.18%   |
| Ralink Technology               | 2         | 0.18%   |
| Chicony Electronics             | 2         | 0.18%   |
| Fujitsu                         | 1         | 0.09%   |
| Foxconn International           | 1         | 0.09%   |
| Creative Technology             | 1         | 0.09%   |
| Alps Electric                   | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 134       | 12.24%  |
| Intel Bluetooth Device                              | 132       | 12.05%  |
| Intel AX201 Bluetooth                               | 98        | 8.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 65        | 5.94%   |
| Intel AX200 Bluetooth                               | 61        | 5.57%   |
| Realtek Bluetooth Radio                             | 58        | 5.3%    |
| Intel AX211 Bluetooth                               | 36        | 3.29%   |
| Apple Bluetooth Host Controller                     | 31        | 2.83%   |
| IMC Networks Bluetooth Radio                        | 24        | 2.19%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 2.01%   |
| Foxconn / Hon Hai Bluetooth Device                  | 22        | 2.01%   |
| Qualcomm Atheros  Bluetooth Device                  | 18        | 1.64%   |
| Apple Bluetooth USB Host Controller                 | 18        | 1.64%   |
| IMC Networks Wireless_Device                        | 16        | 1.46%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 1.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 1.37%   |
| Intel AX210 Bluetooth                               | 14        | 1.28%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 13        | 1.19%   |
| Lite-On Atheros AR3012 Bluetooth                    | 11        | 1%      |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 1%      |
| Foxconn / Hon Hai Wireless_Device                   | 11        | 1%      |
| Broadcom HP Portable SoftSailing                    | 11        | 1%      |
| Lite-On Bluetooth Device                            | 10        | 0.91%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.91%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 10        | 0.91%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 0.73%   |
| IMC Networks Bluetooth Device                       | 8         | 0.73%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.64%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 7         | 0.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.64%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.55%   |
| Realtek 802.11ac WLAN Adapter                       | 6         | 0.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 6         | 0.55%   |
| Broadcom HP Portable Bumble Bee                     | 6         | 0.55%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1026      | 62.94%  |
| AMD                              | 263       | 16.13%  |
| Nvidia                           | 211       | 12.94%  |
| C-Media Electronics              | 18        | 1.1%    |
| Realtek Semiconductor            | 12        | 0.74%   |
| GN Netcom                        | 12        | 0.74%   |
| Logitech                         | 11        | 0.67%   |
| Lenovo                           | 9         | 0.55%   |
| Plantronics                      | 6         | 0.37%   |
| Hewlett-Packard                  | 6         | 0.37%   |
| Kingston Technology              | 5         | 0.31%   |
| ASUSTek Computer                 | 4         | 0.25%   |
| Apple                            | 4         | 0.25%   |
| Texas Instruments                | 3         | 0.18%   |
| Silicon Integrated Systems [SiS] | 3         | 0.18%   |
| SAVITECH                         | 3         | 0.18%   |
| RODE Microphones                 | 3         | 0.18%   |
| DSEA A/S                         | 3         | 0.18%   |
| SteelSeries ApS                  | 2         | 0.12%   |
| Creative Technology              | 2         | 0.12%   |
| Corsair                          | 2         | 0.12%   |
| XMOS                             | 1         | 0.06%   |
| Unknown                          | 1         | 0.06%   |
| SlrTek                           | 1         | 0.06%   |
| Samson Technologies              | 1         | 0.06%   |
| QinHeng Electronics              | 1         | 0.06%   |
| PreSonus Audio Electronics       | 1         | 0.06%   |
| No brand                         | 1         | 0.06%   |
| Line6                            | 1         | 0.06%   |
| LG Electronics                   | 1         | 0.06%   |
| JMTek                            | 1         | 0.06%   |
| JBL                              | 1         | 0.06%   |
| GYROCOM C&C                      | 1         | 0.06%   |
| Generalplus Technology           | 1         | 0.06%   |
| Focusrite-Novation               | 1         | 0.06%   |
| FiiO Electronics Technology      | 1         | 0.06%   |
| Elite Silicon                    | 1         | 0.06%   |
| Digidesign                       | 1         | 0.06%   |
| Conexant Systems                 | 1         | 0.06%   |
| Audio-Technica                   | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 169       | 8.49%   |
| AMD Family 17h/19h HD Audio Controller                                     | 146       | 7.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 97        | 4.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 83        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 74        | 3.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 63        | 3.16%   |
| Intel Haswell-ULT HD Audio Controller                                      | 63        | 3.16%   |
| Intel 8 Series HD Audio Controller                                         | 63        | 3.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 57        | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 55        | 2.76%   |
| Intel Broadwell-U Audio Controller                                         | 55        | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 54        | 2.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 48        | 2.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 47        | 2.36%   |
| AMD FCH Azalia Controller                                                  | 43        | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 39        | 1.96%   |
| Intel CM238 HD Audio Controller                                            | 35        | 1.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 32        | 1.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 32        | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 31        | 1.56%   |
| AMD Kabini HDMI/DP Audio                                                   | 28        | 1.41%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 27        | 1.36%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 25        | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                               | 23        | 1.16%   |
| Intel Comet Lake PCH cAVS                                                  | 22        | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 22        | 1.1%    |
| Nvidia GK107 HDMI Audio Controller                                         | 18        | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 18        | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 18        | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                              | 17        | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 0.85%   |
| Nvidia GA104 High Definition Audio Controller                              | 17        | 0.85%   |
| Nvidia Audio device                                                        | 17        | 0.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 16        | 0.8%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 16        | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                              | 15        | 0.75%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 14        | 0.7%    |
| Nvidia High Definition Audio Controller                                    | 13        | 0.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 13        | 0.65%   |
| Realtek Semiconductor USB Audio                                            | 12        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 255       | 31.64%  |
| SK hynix            | 188       | 23.33%  |
| Micron Technology   | 133       | 16.5%   |
| Kingston            | 54        | 6.7%    |
| Unknown             | 53        | 6.58%   |
| Corsair             | 23        | 2.85%   |
| Crucial             | 21        | 2.61%   |
| Elpida              | 16        | 1.99%   |
| Ramaxel Technology  | 15        | 1.86%   |
| A-DATA Technology   | 13        | 1.61%   |
| Unknown             | 8         | 0.99%   |
| Nanya Technology    | 5         | 0.62%   |
| Unknown (ABCD)      | 2         | 0.25%   |
| Team                | 2         | 0.25%   |
| Patriot             | 2         | 0.25%   |
| GSkill              | 2         | 0.25%   |
| G.Skill             | 2         | 0.25%   |
| Unknown (83DA)      | 1         | 0.12%   |
| TEXTORM             | 1         | 0.12%   |
| Qimonda             | 1         | 0.12%   |
| Netlist             | 1         | 0.12%   |
| Neo Forza           | 1         | 0.12%   |
| GOODRAM             | 1         | 0.12%   |
| fef5                | 1         | 0.12%   |
| Avant               | 1         | 0.12%   |
| ASint Technology    | 1         | 0.12%   |
| Apacer              | 1         | 0.12%   |
| 8CB900000080        | 1         | 0.12%   |
| 48spaces            | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 14        | 1.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 12        | 1.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 12        | 1.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 12        | 1.4%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s      | 12        | 1.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 10        | 1.17%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s      | 9         | 1.05%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 8         | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 8         | 0.93%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 8         | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 8         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 8         | 0.93%   |
| Unknown                                                       | 8         | 0.93%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s         | 7         | 0.82%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 7         | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 6         | 0.7%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 6         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 6         | 0.7%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 6         | 0.7%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s           | 5         | 0.58%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                 | 5         | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 5         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM 1334MT/s          | 5         | 0.58%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s        | 5         | 0.58%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 5         | 0.58%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                  | 5         | 0.58%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s      | 5         | 0.58%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 5         | 0.58%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s         | 5         | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 5         | 0.58%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 5         | 0.58%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 5         | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 5         | 0.58%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s         | 5         | 0.58%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s   | 5         | 0.58%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s         | 5         | 0.58%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s         | 5         | 0.58%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 5         | 0.58%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s        | 4         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 4         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 310       | 43.79%  |
| DDR3    | 229       | 32.34%  |
| LPDDR4  | 49        | 6.92%   |
| LPDDR3  | 36        | 5.08%   |
| LPDDR5  | 25        | 3.53%   |
| DDR2    | 23        | 3.25%   |
| DDR5    | 17        | 2.4%    |
| SDRAM   | 10        | 1.41%   |
| DRAM    | 3         | 0.42%   |
| DDR     | 3         | 0.42%   |
| Unknown | 3         | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 596       | 83.36%  |
| Row Of Chips | 104       | 14.55%  |
| Chip         | 10        | 1.4%    |
| Unknown      | 3         | 0.42%   |
| DIMM         | 2         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 306       | 39.53%  |
| 4096  | 186       | 24.03%  |
| 16384 | 158       | 20.41%  |
| 2048  | 92        | 11.89%  |
| 32768 | 15        | 1.94%   |
| 1024  | 14        | 1.81%   |
| 512   | 3         | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 166       | 21.9%   |
| 3200    | 137       | 18.07%  |
| 2667    | 122       | 16.09%  |
| 2133    | 53        | 6.99%   |
| 2400    | 49        | 6.46%   |
| 1334    | 36        | 4.75%   |
| 4267    | 30        | 3.96%   |
| 1333    | 21        | 2.77%   |
| 6400    | 19        | 2.51%   |
| 667     | 15        | 1.98%   |
| Unknown | 15        | 1.98%   |
| 4800    | 14        | 1.85%   |
| 1867    | 14        | 1.85%   |
| 4266    | 11        | 1.45%   |
| 1067    | 11        | 1.45%   |
| 3266    | 8         | 1.06%   |
| 4199    | 5         | 0.66%   |
| 800     | 5         | 0.66%   |
| 7500    | 4         | 0.53%   |
| 8400    | 3         | 0.4%    |
| 5600    | 3         | 0.4%    |
| 7467    | 2         | 0.26%   |
| 3733    | 2         | 0.26%   |
| 2048    | 2         | 0.26%   |
| 1066    | 2         | 0.26%   |
| 975     | 2         | 0.26%   |
| 533     | 2         | 0.26%   |
| 333     | 2         | 0.26%   |
| 5500    | 1         | 0.13%   |
| 1639    | 1         | 0.13%   |
| 266     | 1         | 0.13%   |

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
| HP HP LaserJet P2035         | 1         | 12.5%   |
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
| Canon           | 2         | 50%     |
| Seiko Epson     | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 25%     |
| HP ScanJet 2200c                            | 1         | 25%     |
| Canon CanoScan LiDE 100                     | 1         | 25%     |
| Canon CanoScan 4400F                        | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 299       | 26.7%   |
| IMC Networks                           | 110       | 9.82%   |
| Microdia                               | 102       | 9.11%   |
| Realtek Semiconductor                  | 84        | 7.5%    |
| Bison Electronics                      | 74        | 6.61%   |
| Sunplus Innovation Technology          | 57        | 5.09%   |
| Cheng Uei Precision Industry (Foxlink) | 54        | 4.82%   |
| Quanta                                 | 46        | 4.11%   |
| Lite-On Technology                     | 43        | 3.84%   |
| Apple                                  | 40        | 3.57%   |
| Suyin                                  | 32        | 2.86%   |
| Syntek                                 | 28        | 2.5%    |
| Acer                                   | 27        | 2.41%   |
| Luxvisions Innotech Limited            | 19        | 1.7%    |
| Logitech                               | 19        | 1.7%    |
| Ricoh                                  | 11        | 0.98%   |
| Lenovo                                 | 10        | 0.89%   |
| Alcor Micro                            | 8         | 0.71%   |
| Samsung Electronics                    | 7         | 0.63%   |
| Sonix Technology                       | 6         | 0.54%   |
| Silicon Motion                         | 6         | 0.54%   |
| ALi                                    | 6         | 0.54%   |
| DigiTech                               | 4         | 0.36%   |
| ShineTech                              | 3         | 0.27%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.27%   |
| Primax Electronics                     | 3         | 0.27%   |
| Importek                               | 3         | 0.27%   |
| Z-Star Microelectronics                | 2         | 0.18%   |
| SunplusIT                              | 2         | 0.18%   |
| Sunplus Technology                     | 2         | 0.18%   |
| Microsoft                              | 2         | 0.18%   |
| Creative Technology                    | 2         | 0.18%   |
| Polycom                                | 1         | 0.09%   |
| LG Electronics                         | 1         | 0.09%   |
| Intel                                  | 1         | 0.09%   |
| Generalplus Technology                 | 1         | 0.09%   |
| Etron Technology                       | 1         | 0.09%   |
| BRS-ZW-230825                          | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 78        | 6.91%   |
| Microdia Integrated_Webcam_HD                                            | 48        | 4.25%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 43        | 3.81%   |
| IMC Networks Integrated Camera                                           | 35        | 3.1%    |
| Realtek Integrated_Webcam_HD                                             | 31        | 2.75%   |
| Chicony HD WebCam                                                        | 25        | 2.21%   |
| Chicony HP HD Camera                                                     | 23        | 2.04%   |
| Bison Integrated Camera                                                  | 23        | 2.04%   |
| Syntek Integrated Camera                                                 | 19        | 1.68%   |
| Lite-On HP HD Camera                                                     | 16        | 1.42%   |
| Quanta HP HD Camera                                                      | 14        | 1.24%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                          | 14        | 1.24%   |
| Sunplus Integrated_Webcam_HD                                             | 13        | 1.15%   |
| Sunplus HD WebCam                                                        | 13        | 1.15%   |
| Lite-On Integrated Camera                                                | 12        | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 12        | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 12        | 1.06%   |
| Bison SunplusIT Integrated Camera                                        | 12        | 1.06%   |
| Chicony HP HD Webcam [Fixed]                                             | 11        | 0.97%   |
| Apple FaceTime HD Camera                                                 | 11        | 0.97%   |
| Realtek USB Camera                                                       | 10        | 0.89%   |
| Quanta HD User Facing                                                    | 10        | 0.89%   |
| Lite-On HP HD Webcam                                                     | 10        | 0.89%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 10        | 0.89%   |
| Bison Lenovo EasyCamera                                                  | 10        | 0.89%   |
| Chicony USB2.0 Camera                                                    | 9         | 0.8%    |
| Chicony HP HD Webcam                                                     | 9         | 0.8%    |
| Realtek USB2.0 HD UVC WebCam                                             | 8         | 0.71%   |
| Quanta HP TrueVision HD Camera                                           | 8         | 0.71%   |
| Luxvisions Innotech Limited HP HD Camera                                 | 8         | 0.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 8         | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                                             | 8         | 0.71%   |
| Chicony Integrated HP HD Webcam                                          | 8         | 0.71%   |
| Apple Built-in iSight                                                    | 8         | 0.71%   |
| Syntek Lenovo EasyCamera                                                 | 7         | 0.62%   |
| Sunplus Laptop Integrated WebCam HD                                      | 7         | 0.62%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 7         | 0.62%   |
| Chicony Integrated Camera (1280x720@30)                                  | 7         | 0.62%   |
| Chicony HP Truevision HD                                                 | 7         | 0.62%   |
| Bison HD Webcam                                                          | 7         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 136       | 45.33%  |
| Synaptics                  | 84        | 28%     |
| Shenzhen Goodix Technology | 24        | 8%      |
| Elan Microelectronics      | 15        | 5%      |
| Upek                       | 14        | 4.67%   |
| AuthenTec                  | 12        | 4%      |
| LighTuning Technology      | 9         | 3%      |
| STMicroelectronics         | 6         | 2%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 50        | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 8%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 6.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 6%      |
| Shenzhen Goodix FingerPrint                                                | 14        | 4.67%   |
| Validity Sensors VFS491                                                    | 13        | 4.33%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 4.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 4%      |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 3.33%   |
| Elan ELAN:Fingerprint                                                      | 10        | 3.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.67%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 2.67%   |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 2.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 2.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 2%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2%      |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.67%   |
| AuthenTec AES2810                                                          | 5         | 1.67%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.67%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1%      |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1%      |
| Validity Sensors Fingerprint scanner                                       | 3         | 1%      |
| Synaptics UWP WBDI Device                                                  | 3         | 1%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1%      |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.67%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.67%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.67%   |
| Synaptics WBDI                                                             | 2         | 0.67%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 0.67%   |
| Unknown                                                                    | 2         | 0.67%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.33%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.33%   |
| Synaptics WBDI Device                                                      | 1         | 0.33%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.33%   |
| Synaptics  WBDI                                                            | 1         | 0.33%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 83        | 46.37%  |
| Broadcom    | 69        | 38.55%  |
| O2 Micro    | 13        | 7.26%   |
| Lenovo      | 7         | 3.91%   |
| Upek        | 5         | 2.79%   |
| Yubico.com  | 2         | 1.12%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 83        | 46.37%  |
| Broadcom 58200                                                               | 21        | 11.73%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 11.17%  |
| Broadcom 5880                                                                | 14        | 7.82%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 7.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 6.15%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 3.91%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 2.79%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.12%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.12%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 705       | 53.13%  |
| 1     | 463       | 34.89%  |
| 2     | 141       | 10.63%  |
| 3     | 14        | 1.06%   |
| 4     | 3         | 0.23%   |
| 7     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 300       | 38.36%  |
| Chipcard                 | 161       | 20.59%  |
| Graphics card            | 106       | 13.55%  |
| Net/wireless             | 61        | 7.8%    |
| Multimedia controller    | 56        | 7.16%   |
| Camera                   | 26        | 3.32%   |
| Bluetooth                | 21        | 2.69%   |
| Communication controller | 18        | 2.3%    |
| Storage                  | 9         | 1.15%   |
| Sound                    | 7         | 0.9%    |
| Card reader              | 6         | 0.77%   |
| Net/ethernet             | 4         | 0.51%   |
| Modem                    | 2         | 0.26%   |
| Flash memory             | 2         | 0.26%   |
| Storage/nvme             | 1         | 0.13%   |
| Storage/ide              | 1         | 0.13%   |
| Storage/ata              | 1         | 0.13%   |

