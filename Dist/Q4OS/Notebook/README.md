Q4OS - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Q4OS.

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

Total: 134

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 6550b               | [9d53f3e9e1](https://linux-hardware.org/?probe=9d53f3e9e1) | Dec 28, 2025 |
| Google        | Edgar                       | [791ca1750a](https://linux-hardware.org/?probe=791ca1750a) | Dec 27, 2025 |
| Acer          | AO722                       | [833a100a47](https://linux-hardware.org/?probe=833a100a47) | Dec 26, 2025 |
| MSI           | U90/U100                    | [8579ded174](https://linux-hardware.org/?probe=8579ded174) | Dec 12, 2025 |
| Dynabook      | S73/HU                      | [338c6b8206](https://linux-hardware.org/?probe=338c6b8206) | Dec 03, 2025 |
| HP            | ProBook 6550b               | [815a18b290](https://linux-hardware.org/?probe=815a18b290) | Nov 22, 2025 |
| HP            | 2000                        | [ad45c8b4ee](https://linux-hardware.org/?probe=ad45c8b4ee) | Nov 21, 2025 |
| Toshiba       | Satellite L515              | [af00e3616b](https://linux-hardware.org/?probe=af00e3616b) | Nov 21, 2025 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c3a05f441c](https://linux-hardware.org/?probe=c3a05f441c) | Nov 21, 2025 |
| Acer          | Aspire E1-470G              | [d2b2ca9361](https://linux-hardware.org/?probe=d2b2ca9361) | Nov 21, 2025 |
| AMI           | PC1068                      | [9ea8b0768e](https://linux-hardware.org/?probe=9ea8b0768e) | Nov 20, 2025 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [da0250c1d6](https://linux-hardware.org/?probe=da0250c1d6) | Nov 20, 2025 |
| HP            | Stream Notebook PC 11       | [92e9f02594](https://linux-hardware.org/?probe=92e9f02594) | Nov 20, 2025 |
| Apple         | MacBookAir5,1               | [1d0e8a1c20](https://linux-hardware.org/?probe=1d0e8a1c20) | Nov 20, 2025 |
| Acer          | Aspire A515-56              | [0bc26a94b0](https://linux-hardware.org/?probe=0bc26a94b0) | Nov 06, 2025 |
| HP            | Laptop 15-dy2xxx            | [d10dca729a](https://linux-hardware.org/?probe=d10dca729a) | Nov 01, 2025 |
| Toshiba       | Satellite L455D             | [039f0cf97b](https://linux-hardware.org/?probe=039f0cf97b) | Sep 27, 2025 |
| Dynabook      | S73/HU                      | [6f49ad2a15](https://linux-hardware.org/?probe=6f49ad2a15) | Sep 23, 2025 |
| Acer          | Aspire E1-470G              | [0e7549043f](https://linux-hardware.org/?probe=0e7549043f) | Aug 31, 2025 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [56727ecaab](https://linux-hardware.org/?probe=56727ecaab) | Aug 28, 2025 |
| AMI           | PC1068                      | [5d640d67e3](https://linux-hardware.org/?probe=5d640d67e3) | Aug 17, 2025 |
| HP            | Laptop 15-da0xxx            | [c06c83ddab](https://linux-hardware.org/?probe=c06c83ddab) | Aug 15, 2025 |
| Google        | Bluebird                    | [88a8d60efa](https://linux-hardware.org/?probe=88a8d60efa) | Aug 14, 2025 |
| Acer          | Aspire 1700                 | [111cc0786f](https://linux-hardware.org/?probe=111cc0786f) | Jul 28, 2025 |
| Acer          | Aspire 1700                 | [8f5b28722d](https://linux-hardware.org/?probe=8f5b28722d) | Jul 28, 2025 |
| HP            | Pavilion dv6                | [f1651a6a0f](https://linux-hardware.org/?probe=f1651a6a0f) | Jul 27, 2025 |
| Clevo         | W150HRM                     | [c6dc45a36d](https://linux-hardware.org/?probe=c6dc45a36d) | Jun 19, 2025 |
| Dynabook      | S73/HU                      | [2a3342d9e6](https://linux-hardware.org/?probe=2a3342d9e6) | Jun 01, 2025 |
| HP            | Laptop 17-by0xxx            | [39c1b73a27](https://linux-hardware.org/?probe=39c1b73a27) | May 17, 2025 |
| HP            | 2000                        | [3e1efd2019](https://linux-hardware.org/?probe=3e1efd2019) | May 10, 2025 |
| ASUSTek       | N56VB                       | [02299c26c8](https://linux-hardware.org/?probe=02299c26c8) | May 06, 2025 |
| Clevo         | W760SUN                     | [21e2a5923e](https://linux-hardware.org/?probe=21e2a5923e) | May 05, 2025 |
| HP            | 15                          | [9b77b395e9](https://linux-hardware.org/?probe=9b77b395e9) | Apr 29, 2025 |
| Acer          | Aspire 5715Z                | [2c4e3dab04](https://linux-hardware.org/?probe=2c4e3dab04) | Apr 29, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [77141cdee8](https://linux-hardware.org/?probe=77141cdee8) | Apr 11, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1955f7f7ce](https://linux-hardware.org/?probe=1955f7f7ce) | Apr 11, 2025 |
| HP            | ProBook x360 11 G1 EE       | [625da3def6](https://linux-hardware.org/?probe=625da3def6) | Mar 25, 2025 |
| Google        | Bluebird                    | [27ce586cc7](https://linux-hardware.org/?probe=27ce586cc7) | Mar 08, 2025 |
| Google        | Lars                        | [45becad3e6](https://linux-hardware.org/?probe=45becad3e6) | Mar 05, 2025 |
| Acer          | Extensa 215-55              | [6528290358](https://linux-hardware.org/?probe=6528290358) | Feb 19, 2025 |
| HP            | ProBook 6550b               | [ef2a7af613](https://linux-hardware.org/?probe=ef2a7af613) | Feb 14, 2025 |
| HP            | Compaq nx6125 (PY421ET#A... | [ac379df62b](https://linux-hardware.org/?probe=ac379df62b) | Jan 30, 2025 |
| Acer          | AOD257                      | [cd57ba84bc](https://linux-hardware.org/?probe=cd57ba84bc) | Jan 03, 2025 |
| Apple         | MacBookAir5,1               | [3e859a02ef](https://linux-hardware.org/?probe=3e859a02ef) | Dec 26, 2024 |
| HP            | Stream Notebook PC 11       | [104ee26be6](https://linux-hardware.org/?probe=104ee26be6) | Dec 25, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [341dc448fb](https://linux-hardware.org/?probe=341dc448fb) | Dec 25, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [bbc531ab55](https://linux-hardware.org/?probe=bbc531ab55) | Nov 29, 2024 |
| Toshiba       | Satellite M100              | [5e91fe5751](https://linux-hardware.org/?probe=5e91fe5751) | Nov 11, 2024 |
| Acer          | AOD270                      | [59b2793787](https://linux-hardware.org/?probe=59b2793787) | Nov 10, 2024 |
| Unknown       | E142                        | [e652a7e6d8](https://linux-hardware.org/?probe=e652a7e6d8) | Oct 31, 2024 |
| Dell          | Latitude E5540              | [a59dfdcd62](https://linux-hardware.org/?probe=a59dfdcd62) | Oct 03, 2024 |
| Dell          | Latitude E5540              | [44955d2b3b](https://linux-hardware.org/?probe=44955d2b3b) | Oct 03, 2024 |
| MicroByte     | ezbook                      | [79104622de](https://linux-hardware.org/?probe=79104622de) | Sep 24, 2024 |
| Lenovo        | ThinkPad X201 3249MJJ       | [04987f2d0e](https://linux-hardware.org/?probe=04987f2d0e) | Sep 23, 2024 |
| Toshiba       | Satellite L515              | [aa75424421](https://linux-hardware.org/?probe=aa75424421) | Sep 19, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [8c7a3cb9ec](https://linux-hardware.org/?probe=8c7a3cb9ec) | Sep 16, 2024 |
| Acer          | Aspire 5920G                | [611ba26507](https://linux-hardware.org/?probe=611ba26507) | Sep 04, 2024 |
| Acer          | Aspire E1-470G              | [fd457f673c](https://linux-hardware.org/?probe=fd457f673c) | Aug 25, 2024 |
| HP            | 2000                        | [28e8a84a4a](https://linux-hardware.org/?probe=28e8a84a4a) | Aug 18, 2024 |
| HP            | Notebook                    | [a1f1e83afe](https://linux-hardware.org/?probe=a1f1e83afe) | Jul 23, 2024 |
| HP            | Notebook                    | [1df59c0265](https://linux-hardware.org/?probe=1df59c0265) | Jul 23, 2024 |
| Toshiba       | NB100                       | [3ca4d2b945](https://linux-hardware.org/?probe=3ca4d2b945) | Jun 16, 2024 |
| Apple         | MacBookAir6,2               | [396846baeb](https://linux-hardware.org/?probe=396846baeb) | May 31, 2024 |
| GFAST         | N-140                       | [43195fd09f](https://linux-hardware.org/?probe=43195fd09f) | May 16, 2024 |
| Acer          | Aspire V5-121               | [ee7af6bc3d](https://linux-hardware.org/?probe=ee7af6bc3d) | May 09, 2024 |
| Samsung       | N150P/N210P/N220P           | [d6fca9f7f5](https://linux-hardware.org/?probe=d6fca9f7f5) | Apr 13, 2024 |
| HP            | ProBook 650 G1              | [d81b4ee2e3](https://linux-hardware.org/?probe=d81b4ee2e3) | Apr 03, 2024 |
| Panasonic     | CF-S10CWHDS                 | [a4c273ab7b](https://linux-hardware.org/?probe=a4c273ab7b) | Mar 19, 2024 |
| MSI           | Alpha 17 C7VF               | [d22dedc33d](https://linux-hardware.org/?probe=d22dedc33d) | Mar 12, 2024 |
| Dell          | Latitude D530               | [0885268edd](https://linux-hardware.org/?probe=0885268edd) | Feb 20, 2024 |
| Dell          | Latitude D530               | [e4d1a73b6e](https://linux-hardware.org/?probe=e4d1a73b6e) | Feb 20, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c246a6b564](https://linux-hardware.org/?probe=c246a6b564) | Jan 30, 2024 |
| HP            | Pavilion dv1000 (EW489EA... | [ea4b49f529](https://linux-hardware.org/?probe=ea4b49f529) | Jan 17, 2024 |
| Matsushita... | CF-29LAQGZBM                | [433fd9b78e](https://linux-hardware.org/?probe=433fd9b78e) | Jan 11, 2024 |
| Toshiba       | Satellite L515              | [a7ec902190](https://linux-hardware.org/?probe=a7ec902190) | Jan 10, 2024 |
| Irbis         | NB264                       | [b7da9b39c3](https://linux-hardware.org/?probe=b7da9b39c3) | Dec 31, 2023 |
| IBM           | ThinkPad T43 1875DMU        | [a33e9f7b0d](https://linux-hardware.org/?probe=a33e9f7b0d) | Dec 31, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [f526bc07cf](https://linux-hardware.org/?probe=f526bc07cf) | Nov 25, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [7b53c24f1e](https://linux-hardware.org/?probe=7b53c24f1e) | Nov 25, 2023 |
| Dell          | Latitude E6430              | [ac45698de6](https://linux-hardware.org/?probe=ac45698de6) | Nov 13, 2023 |
| Apple         | MacBook4,1                  | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Acer          | Aspire one                  | [d040844540](https://linux-hardware.org/?probe=d040844540) | Sep 27, 2023 |
| Acer          | Aspire 1700                 | [a76fb24570](https://linux-hardware.org/?probe=a76fb24570) | Aug 31, 2023 |
| MSI           | U90/U100                    | [015b95ba2a](https://linux-hardware.org/?probe=015b95ba2a) | Jul 31, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [8424587178](https://linux-hardware.org/?probe=8424587178) | Jul 27, 2023 |
| ASUSTek       | K53SJ                       | [922c017262](https://linux-hardware.org/?probe=922c017262) | Jun 26, 2023 |
| Dell          | Latitude D630               | [ead768adbd](https://linux-hardware.org/?probe=ead768adbd) | May 27, 2023 |
| Sony          | VGN-FW21Z                   | [aac218a1e0](https://linux-hardware.org/?probe=aac218a1e0) | May 20, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| Google        | Reks                        | [be1a98408d](https://linux-hardware.org/?probe=be1a98408d) | Feb 28, 2023 |
| HP            | ProBook 650 G1              | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | [cd5e470881](https://linux-hardware.org/?probe=cd5e470881) | Feb 17, 2023 |
| IBM           | ThinkPad T42 2378FVU        | [ce2f3fb897](https://linux-hardware.org/?probe=ce2f3fb897) | Dec 21, 2022 |
| IBM           | ThinkPad T42 2378FVU        | [50f1d0a765](https://linux-hardware.org/?probe=50f1d0a765) | Dec 19, 2022 |
| IBM           | ThinkPad T42 2378FVU        | [fe6bdea3fd](https://linux-hardware.org/?probe=fe6bdea3fd) | Dec 19, 2022 |
| Google        | Cave                        | [ce7f60e0ee](https://linux-hardware.org/?probe=ce7f60e0ee) | Nov 06, 2022 |
| Google        | Cave                        | [63e06049da](https://linux-hardware.org/?probe=63e06049da) | Nov 06, 2022 |
| Medion        | P6620                       | [e5db2a930b](https://linux-hardware.org/?probe=e5db2a930b) | Aug 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [ee35a21db4](https://linux-hardware.org/?probe=ee35a21db4) | Jun 30, 2022 |
| Sony          | VGN-P11Z_Q                  | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Toshiba       | Satellite M70               | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| HP            | 250 G5 Notebook PC          | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASUSTek       | A6U                         | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Toshiba       | Satellite Pro L500          | [5b72ea9a47](https://linux-hardware.org/?probe=5b72ea9a47) | May 02, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| Acer          | AO751h                      | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| AMI           | Intel                       | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | X540YA                      | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Visual Lan... | Premier 10                  | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56               | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56               | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| MSI           | U210                        | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660              | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660              | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                       | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660              | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660              | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Phoenix/Si... | M720SR                      | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx           | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx           | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro                | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| HP            | ProBook 450 G2              | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                         | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| HP            | ProBook 6550b               | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                        | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASUSTek       | A6JC                        | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                        | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00     | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81               | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP                 | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC                 | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Medion        | Unknown                     | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| Philco        | 14I                         | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Q4OS 5 | 48        | 44.04%  |
| Q4OS 4 | 29        | 26.61%  |
| Q4OS 6 | 18        | 16.51%  |
| Q4OS 3 | 11        | 10.09%  |
| Q4OS 2 | 3         | 2.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Q4OS | 98        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 6.12.57+deb13-amd64   | 13        | 11.4%   |
| 6.1.0-23-amd64        | 5         | 4.39%   |
| 6.1.0-34-amd64        | 4         | 3.51%   |
| 6.1.0-32-amd64        | 4         | 3.51%   |
| 6.1.0-27-amd64        | 4         | 3.51%   |
| 6.1.0-18-amd64        | 4         | 3.51%   |
| 5.10.0-23-amd64       | 4         | 3.51%   |
| 6.12.48+deb13-amd64   | 3         | 2.63%   |
| 6.1.0-38-amd64        | 3         | 2.63%   |
| 6.1.0-37-amd64        | 3         | 2.63%   |
| 6.1.0-31-amd64        | 3         | 2.63%   |
| 6.1.0-25-amd64        | 3         | 2.63%   |
| 5.10.0-21-amd64       | 3         | 2.63%   |
| 5.10.0-12-amd64       | 3         | 2.63%   |
| 4.19.0-17-amd64       | 3         | 2.63%   |
| 6.1.0-21-amd64        | 2         | 1.75%   |
| 6.1.0-17-686-pae      | 2         | 1.75%   |
| 6.1.0-13-amd64        | 2         | 1.75%   |
| 5.10.0-8-amd64        | 2         | 1.75%   |
| 5.10.0-14-686-pae     | 2         | 1.75%   |
| 6.6.8-x64v1-xanmod1   | 1         | 0.88%   |
| 6.5.0-4-amd64         | 1         | 0.88%   |
| 6.12.43+deb13-amd64   | 1         | 0.88%   |
| 6.12.41+deb13-amd64   | 1         | 0.88%   |
| 6.12.17-x64v2-xanmod1 | 1         | 0.88%   |
| 6.1.0-41-686-pae      | 1         | 0.88%   |
| 6.1.0-37-686-pae      | 1         | 0.88%   |
| 6.1.0-30-686-pae      | 1         | 0.88%   |
| 6.1.0-26-amd64        | 1         | 0.88%   |
| 6.1.0-26-686-pae      | 1         | 0.88%   |
| 6.1.0-17-amd64        | 1         | 0.88%   |
| 6.1.0-16-686-pae      | 1         | 0.88%   |
| 6.1.0-12-amd64        | 1         | 0.88%   |
| 6.1.0-12-686-pae      | 1         | 0.88%   |
| 6.1.0-11-686-pae      | 1         | 0.88%   |
| 6.1.0-10-686-pae      | 1         | 0.88%   |
| 5.9.0-5-amd64         | 1         | 0.88%   |
| 5.6.0-1-amd64         | 1         | 0.88%   |
| 5.18.0-0.bpo.1-amd64  | 1         | 0.88%   |
| 5.10.0-9-amd64        | 1         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 45        | 41.28%  |
| 5.10.0  | 26        | 23.85%  |
| 6.12.57 | 13        | 11.93%  |
| 4.19.0  | 11        | 10.09%  |
| 6.12.48 | 3         | 2.75%   |
| 4.9.0   | 3         | 2.75%   |
| 6.6.8   | 1         | 0.92%   |
| 6.5.0   | 1         | 0.92%   |
| 6.12.43 | 1         | 0.92%   |
| 6.12.41 | 1         | 0.92%   |
| 6.12.17 | 1         | 0.92%   |
| 5.9.0   | 1         | 0.92%   |
| 5.6.0   | 1         | 0.92%   |
| 5.18.0  | 1         | 0.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 45        | 41.67%  |
| 5.10    | 26        | 24.07%  |
| 6.12    | 18        | 16.67%  |
| 4.19    | 11        | 10.19%  |
| 4.9     | 3         | 2.78%   |
| 6.6     | 1         | 0.93%   |
| 6.5     | 1         | 0.93%   |
| 5.9     | 1         | 0.93%   |
| 5.6     | 1         | 0.93%   |
| 5.18    | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 76        | 77.55%  |
| i686   | 22        | 22.45%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Trinity    | 52        | 52%     |
| KDE5       | 40        | 40%     |
| KDE6       | 4         | 4%      |
| X-Cinnamon | 1         | 1%      |
| MATE       | 1         | 1%      |
| KDE        | 1         | 1%      |
| Cinnamon   | 1         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 93        | 93%     |
| Wayland | 5         | 5%      |
| Tty     | 2         | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| TDM  | 54        | 55.1%   |
| SDDM | 44        | 44.9%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 49        | 50%     |
| en_GB   | 8         | 8.16%   |
| ru_RU   | 6         | 6.12%   |
| de_DE   | 6         | 6.12%   |
| it_IT   | 5         | 5.1%    |
| fr_FR   | 5         | 5.1%    |
| ja_JP   | 3         | 3.06%   |
| hu_HU   | 3         | 3.06%   |
| es_ES   | 3         | 3.06%   |
| sv_SE   | 1         | 1.02%   |
| sl_SI   | 1         | 1.02%   |
| pl_PL   | 1         | 1.02%   |
| hr_HR   | 1         | 1.02%   |
| es_VE   | 1         | 1.02%   |
| en_ZA   | 1         | 1.02%   |
| en_SG   | 1         | 1.02%   |
| de_CH   | 1         | 1.02%   |
| C       | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 55        | 55.56%  |
| EFI  | 44        | 44.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 95        | 96.94%  |
| Overlay | 3         | 3.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 54        | 55.1%   |
| GPT     | 43        | 43.88%  |
| Unknown | 1         | 1.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 89        | 90.82%  |
| Yes       | 9         | 9.18%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 76        | 77.55%  |
| Yes       | 22        | 22.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 23        | 23.47%  |
| Acer                           | 11        | 11.22%  |
| ASUSTek Computer               | 9         | 9.18%   |
| Toshiba                        | 7         | 7.14%   |
| Lenovo                         | 7         | 7.14%   |
| Google                         | 5         | 5.1%    |
| MSI                            | 4         | 4.08%   |
| Dell                           | 4         | 4.08%   |
| Apple                          | 3         | 3.06%   |
| Sony                           | 2         | 2.04%   |
| Medion                         | 2         | 2.04%   |
| IBM                            | 2         | 2.04%   |
| Dynabook                       | 2         | 2.04%   |
| Clevo                          | 2         | 2.04%   |
| AMI                            | 2         | 2.04%   |
| Visual Land                    | 1         | 1.02%   |
| Qilive                         | 1         | 1.02%   |
| Phoenix/SiS                    | 1         | 1.02%   |
| Philco                         | 1         | 1.02%   |
| Panasonic                      | 1         | 1.02%   |
| Packard Bell                   | 1         | 1.02%   |
| Matsushita Electric Industrial | 1         | 1.02%   |
| JVC                            | 1         | 1.02%   |
| Irbis                          | 1         | 1.02%   |
| Fujitsu Siemens                | 1         | 1.02%   |
| Framework                      | 1         | 1.02%   |
| Chuwi                          | 1         | 1.02%   |
| Unknown                        | 1         | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP ProBook 6550b                            | 3         | 3.06%   |
| HP 2000                                     | 3         | 3.06%   |
| Toshiba Satellite C660                      | 2         | 2.04%   |
| MSI U90/U100                                | 2         | 2.04%   |
| HP ProBook 650 G1                           | 2         | 2.04%   |
| Dynabook S73/HU                             | 2         | 2.04%   |
| Unknown                                     | 2         | 2.04%   |
| Visual Land Premier 10                      | 1         | 1.02%   |
| Toshiba Satellite Pro L500                  | 1         | 1.02%   |
| Toshiba Satellite M70                       | 1         | 1.02%   |
| Toshiba Satellite L515                      | 1         | 1.02%   |
| Toshiba Satellite L455D                     | 1         | 1.02%   |
| Toshiba NB100                               | 1         | 1.02%   |
| Sony VGN-P11Z_Q                             | 1         | 1.02%   |
| Sony VGN-FW21Z                              | 1         | 1.02%   |
| Qilive QW19141AMSP                          | 1         | 1.02%   |
| Phoenix/SiS M720SR                          | 1         | 1.02%   |
| Philco 14I                                  | 1         | 1.02%   |
| Panasonic CF-S10CWHDS                       | 1         | 1.02%   |
| Packard Bell EasyNote LM81                  | 1         | 1.02%   |
| MSI U210                                    | 1         | 1.02%   |
| MSI Alpha 17 C7VF                           | 1         | 1.02%   |
| Medion P6620                                | 1         | 1.02%   |
| Matsushita Electric Industrial CF-29LAQGZBM | 1         | 1.02%   |
| Lenovo ThinkPad X201 3249MJJ                | 1         | 1.02%   |
| Lenovo ThinkPad T495 20NKS0PG00             | 1         | 1.02%   |
| Lenovo ThinkPad 11e 20DAS0PS00              | 1         | 1.02%   |
| Lenovo IdeaPad S145-15AST 81N3              | 1         | 1.02%   |
| Lenovo IdeaPad 5 14IAL7 82SD                | 1         | 1.02%   |
| Lenovo IdeaPad 330S-14IKB 81F4              | 1         | 1.02%   |
| Lenovo IdeaPad 330-15IGM 81D1               | 1         | 1.02%   |
| JVC J3N                                     | 1         | 1.02%   |
| Irbis NB264                                 | 1         | 1.02%   |
| IBM ThinkPad T43 1875DMU                    | 1         | 1.02%   |
| IBM ThinkPad T42 2378FVU                    | 1         | 1.02%   |
| HP Stream Notebook PC 11                    | 1         | 1.02%   |
| HP ProBook x360 11 G1 EE                    | 1         | 1.02%   |
| HP ProBook 450 G2                           | 1         | 1.02%   |
| HP Presario CQ56                            | 1         | 1.02%   |
| HP Pavilion dv6                             | 1         | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP ProBook                                  | 7         | 7.14%   |
| Acer Aspire                                 | 7         | 7.14%   |
| Toshiba Satellite                           | 6         | 6.12%   |
| Lenovo IdeaPad                              | 4         | 4.08%   |
| HP Laptop                                   | 4         | 4.08%   |
| Dell Latitude                               | 4         | 4.08%   |
| Lenovo ThinkPad                             | 3         | 3.06%   |
| HP 2000                                     | 3         | 3.06%   |
| ASUS VivoBook                               | 3         | 3.06%   |
| MSI U90                                     | 2         | 2.04%   |
| IBM ThinkPad                                | 2         | 2.04%   |
| HP Pavilion                                 | 2         | 2.04%   |
| Dynabook S73                                | 2         | 2.04%   |
| Unknown                                     | 2         | 2.04%   |
| Visual Land Premier                         | 1         | 1.02%   |
| Toshiba NB100                               | 1         | 1.02%   |
| Sony VGN-P11Z                               | 1         | 1.02%   |
| Sony VGN-FW21Z                              | 1         | 1.02%   |
| Qilive QW19141AMSP                          | 1         | 1.02%   |
| Phoenix/SiS M720SR                          | 1         | 1.02%   |
| Philco 14I                                  | 1         | 1.02%   |
| Panasonic CF-S10CWHDS                       | 1         | 1.02%   |
| Packard Bell EasyNote                       | 1         | 1.02%   |
| MSI U210                                    | 1         | 1.02%   |
| MSI Alpha                                   | 1         | 1.02%   |
| Medion P6620                                | 1         | 1.02%   |
| Matsushita Electric Industrial CF-29LAQGZBM | 1         | 1.02%   |
| JVC J3N                                     | 1         | 1.02%   |
| Irbis NB264                                 | 1         | 1.02%   |
| HP Stream                                   | 1         | 1.02%   |
| HP Presario                                 | 1         | 1.02%   |
| HP OmniBook                                 | 1         | 1.02%   |
| HP Notebook                                 | 1         | 1.02%   |
| HP Compaq                                   | 1         | 1.02%   |
| HP 250                                      | 1         | 1.02%   |
| HP 15                                       | 1         | 1.02%   |
| Google Reks                                 | 1         | 1.02%   |
| Google Lars                                 | 1         | 1.02%   |
| Google Edgar                                | 1         | 1.02%   |
| Google Cave                                 | 1         | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 10        | 10.2%   |
| 2020    | 8         | 8.16%   |
| 2010    | 8         | 8.16%   |
| 2013    | 7         | 7.14%   |
| 2011    | 6         | 6.12%   |
| 2008    | 6         | 6.12%   |
| 2023    | 5         | 5.1%    |
| 2018    | 5         | 5.1%    |
| 2012    | 5         | 5.1%    |
| 2007    | 5         | 5.1%    |
| 2005    | 5         | 5.1%    |
| 2024    | 3         | 3.06%   |
| 2022    | 3         | 3.06%   |
| 2019    | 3         | 3.06%   |
| 2017    | 3         | 3.06%   |
| 2014    | 3         | 3.06%   |
| 2021    | 2         | 2.04%   |
| 2016    | 2         | 2.04%   |
| 2006    | 2         | 2.04%   |
| 2004    | 2         | 2.04%   |
| Unknown | 2         | 2.04%   |
| 2025    | 1         | 1.02%   |
| 2015    | 1         | 1.02%   |
| 2003    | 1         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 98        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 93        | 93.94%  |
| Enabled  | 6         | 6.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 93        | 94.9%   |
| Yes  | 5         | 5.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 35        | 35.71%  |
| 4.01-8.0   | 19        | 19.39%  |
| 1.01-2.0   | 14        | 14.29%  |
| 2.01-3.0   | 10        | 10.2%   |
| 8.01-16.0  | 7         | 7.14%   |
| 0.51-1.0   | 5         | 5.1%    |
| 0.01-0.5   | 4         | 4.08%   |
| 16.01-24.0 | 3         | 3.06%   |
| 24.01-32.0 | 1         | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 44        | 42.31%  |
| 0.51-1.0 | 21        | 20.19%  |
| 2.01-3.0 | 20        | 19.23%  |
| 0.01-0.5 | 8         | 7.69%   |
| 4.01-8.0 | 6         | 5.77%   |
| 3.01-4.0 | 5         | 4.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 79        | 79.8%   |
| 2      | 15        | 15.15%  |
| 7      | 2         | 2.02%   |
| 3      | 2         | 2.02%   |
| 4      | 1         | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 51.02%  |
| Yes       | 48        | 48.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 78.57%  |
| No        | 21        | 21.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 94.9%   |
| No        | 5         | 5.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 50%     |
| No        | 49        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 29        | 29.59%  |
| Italy        | 8         | 8.16%   |
| UK           | 7         | 7.14%   |
| Russia       | 6         | 6.12%   |
| Germany      | 6         | 6.12%   |
| France       | 4         | 4.08%   |
| Spain        | 3         | 3.06%   |
| Kenya        | 3         | 3.06%   |
| Japan        | 3         | 3.06%   |
| Hungary      | 3         | 3.06%   |
| Switzerland  | 2         | 2.04%   |
| Slovenia     | 2         | 2.04%   |
| Romania      | 2         | 2.04%   |
| Poland       | 2         | 2.04%   |
| Croatia      | 2         | 2.04%   |
| Algeria      | 2         | 2.04%   |
| Venezuela    | 1         | 1.02%   |
| Turkey       | 1         | 1.02%   |
| Sweden       | 1         | 1.02%   |
| South Africa | 1         | 1.02%   |
| Singapore    | 1         | 1.02%   |
| Saudi Arabia | 1         | 1.02%   |
| Qatar        | 1         | 1.02%   |
| Mexico       | 1         | 1.02%   |
| Egypt        | 1         | 1.02%   |
| Canada       | 1         | 1.02%   |
| Brazil       | 1         | 1.02%   |
| Belgium      | 1         | 1.02%   |
| Belarus      | 1         | 1.02%   |
| Argentina    | 1         | 1.02%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Jacksonville          | 15        | 14.85%  |
| Nairobi               | 3         | 2.97%   |
| Swindon               | 2         | 1.98%   |
| Pittsburgh            | 2         | 1.98%   |
| Mesa                  | 2         | 1.98%   |
| Ljubljana             | 2         | 1.98%   |
| Lake City             | 2         | 1.98%   |
| Drobeta-Turnu Severin | 2         | 1.98%   |
| Budapest              | 2         | 1.98%   |
| Zweidlen-Dorf         | 1         | 0.99%   |
| Zagreb                | 1         | 0.99%   |
| Wrexham               | 1         | 0.99%   |
| West Corinth          | 1         | 0.99%   |
| Volgograd             | 1         | 0.99%   |
| Turin                 | 1         | 0.99%   |
| Toledo                | 1         | 0.99%   |
| Tokyo                 | 1         | 0.99%   |
| Tenbury Wells         | 1         | 0.99%   |
| Tellico Plains        | 1         | 0.99%   |
| Sosnowiec             | 1         | 0.99%   |
| Siziano               | 1         | 0.99%   |
| Sint-Pieters-Leeuw    | 1         | 0.99%   |
| Singapore             | 1         | 0.99%   |
| Shizuoka              | 1         | 0.99%   |
| Shadrinsk             | 1         | 0.99%   |
| Sétif                | 1         | 0.99%   |
| Schermbeck            | 1         | 0.99%   |
| Salsomaggiore Terme   | 1         | 0.99%   |
| Rostov-on-Don         | 1         | 0.99%   |
| Rostock               | 1         | 0.99%   |
| Rijeka                | 1         | 0.99%   |
| Puerto Cumarebo       | 1         | 0.99%   |
| Presezzo              | 1         | 0.99%   |
| Port Elizabeth        | 1         | 0.99%   |
| Paris                 | 1         | 0.99%   |
| Palermo               | 1         | 0.99%   |
| Oran                  | 1         | 0.99%   |
| Neckarsulm            | 1         | 0.99%   |
| Nasr                  | 1         | 0.99%   |
| Moscow                | 1         | 0.99%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 16        | 25     | 13.91%  |
| WDC                 | 11        | 13     | 9.57%   |
| Seagate             | 11        | 15     | 9.57%   |
| Samsung Electronics | 11        | 12     | 9.57%   |
| Toshiba             | 10        | 12     | 8.7%    |
| Hitachi             | 8         | 11     | 6.96%   |
| SanDisk             | 6         | 6      | 5.22%   |
| Kingston            | 5         | 5      | 4.35%   |
| HGST                | 4         | 4      | 3.48%   |
| Fujitsu             | 4         | 4      | 3.48%   |
| PASOUL 2            | 2         | 2      | 1.74%   |
| KESU                | 2         | 2      | 1.74%   |
| CUSU                | 2         | 3      | 1.74%   |
| China               | 2         | 2      | 1.74%   |
| Apple               | 2         | 3      | 1.74%   |
| A-DATA Technology   | 2         | 2      | 1.74%   |
| Unknown             | 2         | 2      | 1.74%   |
| SUNEAST             | 1         | 1      | 0.87%   |
| SK hynix            | 1         | 1      | 0.87%   |
| Silicon Motion      | 1         | 1      | 0.87%   |
| PNY                 | 1         | 1      | 0.87%   |
| Plextor             | 1         | 1      | 0.87%   |
| Phison              | 1         | 1      | 0.87%   |
| Micron Technology   | 1         | 1      | 0.87%   |
| Lexar               | 1         | 1      | 0.87%   |
| KingSpec            | 1         | 1      | 0.87%   |
| KBG40ZNV            | 1         | 1      | 0.87%   |
| JMicron Technology  | 1         | 1      | 0.87%   |
| Intel               | 1         | 1      | 0.87%   |
| HEYGATE             | 1         | 1      | 0.87%   |
| Gigabyte Technology | 1         | 1      | 0.87%   |
| Crucial             | 1         | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 1.68%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 1.68%   |
| Unknown S0J59X  128GB                | 2         | 1.68%   |
| Unknown G1J38E  64GB                 | 2         | 1.68%   |
| Unknown Externa 1TB                  | 2         | 1.68%   |
| Unknown 1 250GB                      | 2         | 1.68%   |
| Toshiba MQ01ABF032 320GB             | 2         | 1.68%   |
| Seagate ST9500325AS 500GB            | 2         | 1.68%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.68%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.68%   |
| PASOUL 2 56GB                        | 2         | 1.68%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 1.68%   |
| KESU USB 3.1 256GB                   | 2         | 1.68%   |
| Hitachi HTS541080G9SA00 80GB         | 2         | 1.68%   |
| Fujitsu MHY2080BH 80GB               | 2         | 1.68%   |
| CUSU CV3500Q 512GB                   | 2         | 1.68%   |
| A-DATA SU630 240GB SSD               | 2         | 1.68%   |
| Unknown                              | 2         | 1.68%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.84%   |
| WDC WD3200BPVT-00ZEST0 320GB         | 1         | 0.84%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.84%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.84%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.84%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 0.84%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.84%   |
| Unknown USDU1  32GB                  | 1         | 0.84%   |
| Unknown SLD64G  64GB                 | 1         | 0.84%   |
| Unknown SD/MMC/MS PRO 2GB            | 1         | 0.84%   |
| Unknown SCA32G  32GB                 | 1         | 0.84%   |
| Unknown MMC Card  64GB               | 1         | 0.84%   |
| Unknown MBG4GC  32GB                 | 1         | 0.84%   |
| Unknown HBG4a2  32GB                 | 1         | 0.84%   |
| Unknown HAG2e  16GB                  | 1         | 0.84%   |
| Unknown BJTD4R  32GB                 | 1         | 0.84%   |
| Unknown 064G38  64GB                 | 1         | 0.84%   |
| Unknown 0 Device 0 500GB             | 1         | 0.84%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.84%   |
| Toshiba MK8032GAX 80GB               | 1         | 0.84%   |
| Toshiba MK8025GAS 80GB               | 1         | 0.84%   |
| Toshiba MK6028GAL 64GB               | 1         | 0.84%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 12     | 19.61%  |
| Toshiba             | 10        | 12     | 19.61%  |
| Seagate             | 10        | 14     | 19.61%  |
| Hitachi             | 8         | 11     | 15.69%  |
| HGST                | 4         | 4      | 7.84%   |
| Fujitsu             | 4         | 4      | 7.84%   |
| PASOUL 2            | 2         | 2      | 3.92%   |
| Unknown             | 1         | 1      | 1.96%   |
| Samsung Electronics | 1         | 1      | 1.96%   |
| Unknown             | 1         | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 17.86%  |
| Samsung Electronics | 4         | 4      | 14.29%  |
| SanDisk             | 3         | 3      | 10.71%  |
| China               | 2         | 2      | 7.14%   |
| Apple               | 2         | 3      | 7.14%   |
| A-DATA Technology   | 2         | 2      | 7.14%   |
| SUNEAST             | 1         | 1      | 3.57%   |
| PNY                 | 1         | 1      | 3.57%   |
| Plextor             | 1         | 1      | 3.57%   |
| Lexar               | 1         | 1      | 3.57%   |
| KingSpec            | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| HEYGATE             | 1         | 1      | 3.57%   |
| Gigabyte Technology | 1         | 1      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |
| Unknown             | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 47        | 62     | 43.52%  |
| SSD     | 28        | 29     | 25.93%  |
| MMC     | 16        | 21     | 14.81%  |
| NVMe    | 12        | 16     | 11.11%  |
| Unknown | 5         | 10     | 4.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 69        | 82     | 65.71%  |
| MMC  | 16        | 21     | 15.24%  |
| NVMe | 12        | 15     | 11.43%  |
| SAS  | 8         | 20     | 7.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 66        | 81     | 89.19%  |
| 0.51-1.0   | 6         | 8      | 8.11%   |
| 3.01-4.0   | 1         | 1      | 1.35%   |
| 1.01-2.0   | 1         | 1      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 28        | 28%     |
| 251-500    | 21        | 21%     |
| 51-100     | 21        | 21%     |
| 21-50      | 10        | 10%     |
| 1-20       | 7         | 7%      |
| 501-1000   | 6         | 6%      |
| 1001-2000  | 3         | 3%      |
| 2001-3000  | 2         | 2%      |
| Unknown    | 2         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 71        | 68.93%  |
| 21-50     | 15        | 14.56%  |
| 51-100    | 7         | 6.8%    |
| 251-500   | 3         | 2.91%   |
| 1001-2000 | 2         | 1.94%   |
| 501-1000  | 2         | 1.94%   |
| Unknown   | 2         | 1.94%   |
| 101-250   | 1         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Fujitsu MHY2080BH 80GB               | 2         | 2      | 7.41%   |
| CUSU CV3500Q 512GB                   | 2         | 3      | 7.41%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 3      | 3.7%    |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1      | 3.7%    |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 1      | 3.7%    |
| Toshiba MK3252GSX 320GB              | 1         | 1      | 3.7%    |
| Toshiba MK1252GSX 120GB              | 1         | 1      | 3.7%    |
| SK hynix BC711 HFM256GD3JX013N 256GB | 1         | 1      | 3.7%    |
| Seagate ST95005620AS 500GB           | 1         | 1      | 3.7%    |
| Seagate ST9500325AS 500GB            | 1         | 1      | 3.7%    |
| Seagate ST9120822AS 120GB            | 1         | 1      | 3.7%    |
| Samsung Electronics HM080GC 80GB     | 1         | 1      | 3.7%    |
| PNY 1TB SATA SSD                     | 1         | 1      | 3.7%    |
| Intel SSDSC2CW120A3 120GB            | 1         | 1      | 3.7%    |
| Hitachi HTS725025A9A364 250GB        | 1         | 1      | 3.7%    |
| Hitachi HTS723232L9A360 320GB        | 1         | 1      | 3.7%    |
| Hitachi HTS545032B9A300 320GB        | 1         | 1      | 3.7%    |
| Hitachi HTS543225L9SA00 250GB        | 1         | 1      | 3.7%    |
| Hitachi HTS541080G9SA00 80GB         | 1         | 1      | 3.7%    |
| Hitachi DK23CA-20 20GB               | 1         | 1      | 3.7%    |
| HGST HTS725050A7E630 500GB           | 1         | 1      | 3.7%    |
| HGST HTS545050A7E680 500GB           | 1         | 1      | 3.7%    |
| HGST HTS545032A7E380 320GB           | 1         | 1      | 3.7%    |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 3.7%    |
| Fujitsu MHZ2160BH G2 160GB           | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 6      | 19.23%  |
| HGST                | 4         | 4      | 15.38%  |
| WDC                 | 3         | 5      | 11.54%  |
| Seagate             | 3         | 3      | 11.54%  |
| Fujitsu             | 3         | 3      | 11.54%  |
| Toshiba             | 2         | 2      | 7.69%   |
| CUSU                | 2         | 3      | 7.69%   |
| SK hynix            | 1         | 1      | 3.85%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| PNY                 | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 6      | 23.81%  |
| HGST                | 4         | 4      | 19.05%  |
| WDC                 | 3         | 5      | 14.29%  |
| Seagate             | 3         | 3      | 14.29%  |
| Fujitsu             | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 24     | 80.77%  |
| NVMe | 3         | 4      | 11.54%  |
| SSD  | 2         | 2      | 7.69%   |

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
| Works    | 56        | 71     | 53.85%  |
| Malfunc  | 26        | 30     | 25%     |
| Detected | 22        | 37     | 21.15%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 65        | 67.71%  |
| AMD                              | 13        | 13.54%  |
| Silicon Integrated Systems [SiS] | 4         | 4.17%   |
| Samsung Electronics              | 4         | 4.17%   |
| SanDisk                          | 3         | 3.13%   |
| MAXIO Technology (Hangzhou)      | 2         | 2.08%   |
| SK hynix                         | 1         | 1.04%   |
| Silicon Motion                   | 1         | 1.04%   |
| Phison Electronics               | 1         | 1.04%   |
| Micron Technology                | 1         | 1.04%   |
| Marvell Technology Group         | 1         | 1.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 6.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 5.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 5.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 5.36%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 4.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 4.46%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 4.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 3.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 3.57%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 2.68%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 3         | 2.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 2.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 2.68%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 1.79%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 2         | 1.79%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 2         | 1.79%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 2         | 1.79%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 1.79%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.79%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 1.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 1.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.89%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                     | 1         | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 0.89%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.89%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 1         | 0.89%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 0.89%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.89%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 1         | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 0.89%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 61        | 56.48%  |
| IDE  | 26        | 24.07%  |
| NVMe | 12        | 11.11%  |
| RAID | 9         | 8.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 81        | 82.65%  |
| AMD    | 17        | 17.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron N4020 CPU @ 1.10GHz           | 4         | 4.08%   |
| Intel Atom CPU N270 @ 1.60GHz               | 4         | 4.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 4.08%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 3.06%   |
| Intel Pentium M processor 1.70GHz           | 2         | 2.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 2.04%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 2         | 2.04%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 2.04%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 2.04%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 2.04%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 2.04%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 2         | 2.04%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 2.04%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 2.04%   |
| AMD E-300 APU with Radeon HD Graphics       | 2         | 2.04%   |
| AMD C-70 APU with Radeon HD Graphics        | 2         | 2.04%   |
| Intel Pentium M processor 1000MHz           | 1         | 1.02%   |
| Intel Pentium M processor 1.73GHz           | 1         | 1.02%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.02%   |
| Intel Pentium III (Coppermine)              | 1         | 1.02%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.02%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.02%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.02%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz      | 1         | 1.02%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.02%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 1         | 1.02%   |
| Intel Pentium 4 CPU 2.66GHz                 | 1         | 1.02%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 1.02%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 1.02%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 1.02%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 1.02%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 1.02%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.02%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.02%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 1         | 1.02%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.02%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.02%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz        | 1         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 15        | 15.31%  |
| Intel Core i5           | 12        | 12.24%  |
| Intel Core 2 Duo        | 10        | 10.2%   |
| Intel Atom              | 10        | 10.2%   |
| Other                   | 8         | 8.16%   |
| Intel Core i3           | 8         | 8.16%   |
| Intel Pentium M         | 5         | 5.1%    |
| Intel Pentium Dual-Core | 3         | 3.06%   |
| Intel Pentium           | 2         | 2.04%   |
| Intel Genuine           | 2         | 2.04%   |
| AMD Mobile Sempron      | 2         | 2.04%   |
| AMD E                   | 2         | 2.04%   |
| AMD C-70                | 2         | 2.04%   |
| Intel Pentium III       | 1         | 1.02%   |
| Intel Pentium Dual      | 1         | 1.02%   |
| Intel Pentium 4         | 1         | 1.02%   |
| Intel Core m3           | 1         | 1.02%   |
| Intel Core i7           | 1         | 1.02%   |
| Intel Core 2            | 1         | 1.02%   |
| AMD V120                | 1         | 1.02%   |
| AMD Sempron             | 1         | 1.02%   |
| AMD Ryzen 9             | 1         | 1.02%   |
| AMD Ryzen 7 PRO         | 1         | 1.02%   |
| AMD Ryzen 7             | 1         | 1.02%   |
| AMD E1                  | 1         | 1.02%   |
| AMD C-60                | 1         | 1.02%   |
| AMD Athlon Neo          | 1         | 1.02%   |
| AMD A8                  | 1         | 1.02%   |
| AMD A6                  | 1         | 1.02%   |
| AMD A4                  | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 60        | 61.22%  |
| 1      | 19        | 19.39%  |
| 4      | 15        | 15.31%  |
| 16     | 1         | 1.02%   |
| 12     | 1         | 1.02%   |
| 8      | 1         | 1.02%   |
| 6      | 1         | 1.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 98        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 60.2%   |
| 2      | 39        | 39.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 81        | 82.65%  |
| 32-bit         | 17        | 17.35%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 24.07%  |
| 0x1067a    | 6         | 5.56%   |
| 0x6fd      | 5         | 4.63%   |
| 0x206a7    | 5         | 4.63%   |
| 0x106c2    | 5         | 4.63%   |
| 0x406c4    | 4         | 3.7%    |
| 0x306a9    | 4         | 3.7%    |
| 0x20655    | 4         | 3.7%    |
| 0x806e9    | 3         | 2.78%   |
| 0x806c1    | 3         | 2.78%   |
| 0x706a8    | 3         | 2.78%   |
| 0x40651    | 3         | 2.78%   |
| 0x30678    | 3         | 2.78%   |
| 0x05000119 | 3         | 2.78%   |
| 0x706a1    | 2         | 1.85%   |
| 0x6e8      | 2         | 1.85%   |
| 0x506c9    | 2         | 1.85%   |
| 0x406e3    | 2         | 1.85%   |
| 0x306c3    | 2         | 1.85%   |
| 0x10676    | 2         | 1.85%   |
| 0x06006705 | 2         | 1.85%   |
| 0xf27      | 1         | 0.93%   |
| 0x906a4    | 1         | 0.93%   |
| 0x906a3    | 1         | 0.93%   |
| 0x6fb      | 1         | 0.93%   |
| 0x6f6      | 1         | 0.93%   |
| 0x6d8      | 1         | 0.93%   |
| 0x6d6      | 1         | 0.93%   |
| 0x695      | 1         | 0.93%   |
| 0x68a      | 1         | 0.93%   |
| 0x30661    | 1         | 0.93%   |
| 0x0a704103 | 1         | 0.93%   |
| 0x0a601203 | 1         | 0.93%   |
| 0x08108102 | 1         | 0.93%   |
| 0x07030106 | 1         | 0.93%   |
| 0x0700010f | 1         | 0.93%   |
| 0x0500010d | 1         | 0.93%   |
| 0x010000c8 | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Silvermont       | 9         | 9.18%   |
| Penryn           | 8         | 8.16%   |
| P6               | 8         | 8.16%   |
| Goldmont plus    | 7         | 7.14%   |
| Core             | 7         | 7.14%   |
| Bonnell          | 7         | 7.14%   |
| TigerLake        | 6         | 6.12%   |
| Westmere         | 5         | 5.1%    |
| SandyBridge      | 5         | 5.1%    |
| Haswell          | 5         | 5.1%    |
| Bobcat           | 5         | 5.1%    |
| IvyBridge        | 4         | 4.08%   |
| KabyLake         | 3         | 3.06%   |
| K8 Hammer        | 3         | 3.06%   |
| Unknown          | 3         | 3.06%   |
| Skylake          | 2         | 2.04%   |
| Goldmont         | 2         | 2.04%   |
| Excavator        | 2         | 2.04%   |
| Zen+             | 1         | 1.02%   |
| Puma             | 1         | 1.02%   |
| NetBurst         | 1         | 1.02%   |
| K8 & K10 hybrid  | 1         | 1.02%   |
| K10              | 1         | 1.02%   |
| Jaguar           | 1         | 1.02%   |
| Alderlake Hybrid | 1         | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 69        | 66.99%  |
| AMD                              | 23        | 22.33%  |
| Nvidia                           | 7         | 6.8%    |
| Silicon Integrated Systems [SiS] | 3         | 2.91%   |
| S3 Graphics                      | 1         | 0.97%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                        | 7         | 6.14%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 6         | 5.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 6         | 5.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 5         | 4.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 5         | 4.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 5         | 4.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 4         | 3.51%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 4         | 3.51%   |
| Intel Core Processor Integrated Graphics Controller                                        | 4         | 3.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                           | 4         | 3.51%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 3         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 3         | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 3         | 2.63%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 1.75%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                  | 2         | 1.75%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 2         | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 2         | 1.75%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                    | 2         | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 2         | 1.75%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 2         | 1.75%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 2         | 1.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 2         | 1.75%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                           | 2         | 1.75%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                  | 1         | 0.88%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 0.88%   |
| Nvidia GK107M [GeForce GT 740M]                                                            | 1         | 0.88%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 0.88%   |
| Nvidia GF106M [GeForce GT 555M]                                                            | 1         | 0.88%   |
| Nvidia G98M [GeForce G 105M]                                                               | 1         | 0.88%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 0.88%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 0.88%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                            | 1         | 0.88%   |
| Intel Skylake-Y GT2 [HD Graphics 515]                                                      | 1         | 0.88%   |
| Intel Skylake-U GT1 [HD Graphics 510]                                                      | 1         | 0.88%   |
| Intel Kaby Lake-U GT1 [HD Graphics 610]                                                    | 1         | 0.88%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                            | 1         | 0.88%   |
| Intel Apollo Lake [HD Graphics 505]                                                        | 1         | 0.88%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                    | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 54        | 55.1%   |
| 1 x AMD         | 21        | 21.43%  |
| 2 x Intel       | 10        | 10.2%   |
| 1 x SiS         | 3         | 3.06%   |
| 1 x Nvidia      | 3         | 3.06%   |
| Intel + Nvidia  | 3         | 3.06%   |
| Other           | 1         | 1.02%   |
| 1 x S3 Graphics | 1         | 1.02%   |
| Intel + AMD     | 1         | 1.02%   |
| AMD + Nvidia    | 1         | 1.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 87        | 87.88%  |
| Unknown     | 9         | 9.09%   |
| Proprietary | 3         | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 72.73%  |
| 0.01-0.5   | 24        | 24.24%  |
| 1.01-2.0   | 3         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 23.26%  |
| Chimei Innolux          | 14        | 16.28%  |
| Samsung Electronics     | 11        | 12.79%  |
| LG Display              | 9         | 10.47%  |
| BOE                     | 9         | 10.47%  |
| Chi Mei Optoelectronics | 4         | 4.65%   |
| HannStar                | 3         | 3.49%   |
| Apple                   | 3         | 3.49%   |
| Sharp                   | 2         | 2.33%   |
| Dell                    | 2         | 2.33%   |
| CPT                     | 2         | 2.33%   |
| MQP                     | 1         | 1.16%   |
| LG Philips              | 1         | 1.16%   |
| Lenovo                  | 1         | 1.16%   |
| InnoLux Display         | 1         | 1.16%   |
| InfoVision              | 1         | 1.16%   |
| Hewlett-Packard         | 1         | 1.16%   |
| CSO                     | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP1562 1920x1080 294x165mm 13.3-inch                  | 2         | 2.33%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 2         | 2.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 2.33%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 2.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 2.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 2.33%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch            | 2         | 2.33%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch            | 2         | 2.33%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch      | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch    | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 890x500mm 40.2-inch    | 1         | 1.16%   |
| MQP MultiQ MQ212 MQP0212 800x600 246x185mm 12.1-inch                     | 1         | 1.16%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD03DD 1366x768 344x194mm 15.5-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD027B 1600x900 382x215mm 17.3-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD01E6 1366x768 309x174mm 14.0-inch              | 1         | 1.16%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.16%   |
| InnoLux Display LCD Monitor INL0005 1366x768 344x194mm 15.5-inch         | 1         | 1.16%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 1         | 1.16%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 520x320mm 24.0-inch               | 1         | 1.16%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 1         | 1.16%   |
| Dell UP2715K DEL40B6 2560x2880 597x336mm 27.0-inch                       | 1         | 1.16%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                         | 1         | 1.16%   |
| CSO MNH301CA3-1 CSO1702 2560x1440 380x210mm 17.1-inch                    | 1         | 1.16%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                     | 1         | 1.16%   |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                     | 1         | 1.16%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch         | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 40        | 47.06%  |
| 1920x1080 (FHD)   | 18        | 21.18%  |
| 1280x800 (WXGA)   | 9         | 10.59%  |
| 1600x900 (HD+)    | 5         | 5.88%   |
| 1024x600          | 5         | 5.88%   |
| 1920x1200 (WUXGA) | 2         | 2.35%   |
| 800x600           | 1         | 1.18%   |
| 2560x1440 (QHD)   | 1         | 1.18%   |
| 2256x1504         | 1         | 1.18%   |
| 2160x1440         | 1         | 1.18%   |
| 1440x900 (WXGA+)  | 1         | 1.18%   |
| 1024x768 (XGA)    | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 37        | 43.02%  |
| 11     | 12        | 13.95%  |
| 13     | 11        | 12.79%  |
| 14     | 7         | 8.14%   |
| 17     | 4         | 4.65%   |
| 12     | 4         | 4.65%   |
| 10     | 4         | 4.65%   |
| 24     | 2         | 2.33%   |
| 46     | 1         | 1.16%   |
| 40     | 1         | 1.16%   |
| 27     | 1         | 1.16%   |
| 18     | 1         | 1.16%   |
| 8      | 1         | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 56.47%  |
| 201-300     | 25        | 29.41%  |
| 351-400     | 6         | 7.06%   |
| 501-600     | 3         | 3.53%   |
| 801-900     | 1         | 1.18%   |
| 101-200     | 1         | 1.18%   |
| 1001-1500   | 1         | 1.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 68        | 81.93%  |
| 16/10 | 10        | 12.05%  |
| 3/2   | 3         | 3.61%   |
| 4/3   | 2         | 2.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 37        | 43.02%  |
| 81-90          | 16        | 18.6%   |
| 51-60          | 12        | 13.95%  |
| 41-50          | 4         | 4.65%   |
| 121-130        | 4         | 4.65%   |
| 71-80          | 3         | 3.49%   |
| 61-70          | 3         | 3.49%   |
| 501-1000       | 2         | 2.33%   |
| 1-40           | 1         | 1.16%   |
| 301-350        | 1         | 1.16%   |
| 251-300        | 1         | 1.16%   |
| 201-250        | 1         | 1.16%   |
| 141-150        | 1         | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 38        | 44.19%  |
| 121-160 | 24        | 27.91%  |
| 51-100  | 15        | 17.44%  |
| 161-240 | 7         | 8.14%   |
| 1-50    | 2         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 89        | 90.82%  |
| 2     | 5         | 5.1%    |
| 0     | 4         | 4.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 54        | 34.62%  |
| Intel                            | 34        | 21.79%  |
| Qualcomm Atheros                 | 23        | 14.74%  |
| Broadcom                         | 15        | 9.62%   |
| Marvell Technology Group         | 5         | 3.21%   |
| Silicon Integrated Systems [SiS] | 4         | 2.56%   |
| Broadcom Limited                 | 4         | 2.56%   |
| MediaTek                         | 3         | 1.92%   |
| Xiaomi                           | 2         | 1.28%   |
| Ralink Technology                | 2         | 1.28%   |
| JMicron Technology               | 2         | 1.28%   |
| TP-Link                          | 1         | 0.64%   |
| Qualcomm Technologies            | 1         | 0.64%   |
| Motorola PCS                     | 1         | 0.64%   |
| LG Electronics                   | 1         | 0.64%   |
| D-Link System                    | 1         | 0.64%   |
| ASIX Electronics                 | 1         | 0.64%   |
| AMD                              | 1         | 0.64%   |
| Accton Technology                | 1         | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 19        | 10.22%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 15        | 8.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.69%   |
| Intel Wireless 7265                                                     | 5         | 2.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.15%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 2.15%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 3         | 1.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 1.61%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 3         | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 1.08%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 1.08%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 1.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.08%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 1.08%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 1.08%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.08%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.08%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.08%   |
| Intel Ethernet Connection I217-V                                        | 2         | 1.08%   |
| Intel Ethernet Connection (13) I219-V                                   | 2         | 1.08%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.08%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 1.08%   |
| Intel 82577LC Gigabit Network Connection                                | 2         | 1.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.08%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 0.54%   |
| Realtek USB 10/100/1G/2.5 LAN                                           | 1         | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 31.25%  |
| Realtek Semiconductor | 25        | 26.04%  |
| Qualcomm Atheros      | 21        | 21.88%  |
| Broadcom              | 10        | 10.42%  |
| MediaTek              | 3         | 3.13%   |
| Broadcom Limited      | 3         | 3.13%   |
| Ralink Technology     | 2         | 2.08%   |
| TP-Link               | 1         | 1.04%   |
| D-Link System         | 1         | 1.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 8.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 6.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 5.21%   |
| Intel Wireless 7265                                                     | 5         | 5.21%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 5.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 4.17%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 4.17%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 3         | 3.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 3.13%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 2.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.08%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 2.08%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.08%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 2.08%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 2.08%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.04%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.04%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.04%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 1.04%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.04%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.04%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 1.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.04%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 1         | 1.04%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 1         | 1.04%   |
| Intel Wireless 7260                                                     | 1         | 1.04%   |
| Intel Wireless 3165                                                     | 1         | 1.04%   |
| Intel WiFi Link 5100                                                    | 1         | 1.04%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.04%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.04%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 1         | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 41        | 50%     |
| Intel                            | 14        | 17.07%  |
| Broadcom                         | 6         | 7.32%   |
| Marvell Technology Group         | 5         | 6.1%    |
| Silicon Integrated Systems [SiS] | 3         | 3.66%   |
| Qualcomm Atheros                 | 3         | 3.66%   |
| Xiaomi                           | 2         | 2.44%   |
| JMicron Technology               | 2         | 2.44%   |
| Qualcomm Technologies            | 1         | 1.22%   |
| Motorola PCS                     | 1         | 1.22%   |
| LG Electronics                   | 1         | 1.22%   |
| Broadcom Limited                 | 1         | 1.22%   |
| ASIX Electronics                 | 1         | 1.22%   |
| Accton Technology                | 1         | 1.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 19        | 23.17%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 15        | 18.29%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 3.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 2.44%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 2         | 2.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 2.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 2.44%   |
| Intel Ethernet Connection I217-V                                       | 2         | 2.44%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 2.44%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 2.44%   |
| Intel 82577LC Gigabit Network Connection                               | 2         | 2.44%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 1         | 1.22%   |
| Realtek USB 10/100/1G/2.5 LAN                                          | 1         | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.22%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1         | 1.22%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]       | 1         | 1.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 1.22%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.22%   |
| Motorola PCS motorola one 5G ace                                       | 1         | 1.22%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 1.22%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 1.22%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.22%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                    | 1         | 1.22%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 1.22%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1         | 1.22%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                     | 1         | 1.22%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                            | 1         | 1.22%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 1.22%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 1         | 1.22%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.22%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 1.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.22%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express       | 1         | 1.22%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 1.22%   |
| Accton EN-1216 Ethernet Adapter                                        | 1         | 1.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 93        | 52.25%  |
| Ethernet | 77        | 43.26%  |
| Modem    | 8         | 4.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 77.55%  |
| Ethernet | 22        | 22.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 66        | 67.35%  |
| 1     | 27        | 27.55%  |
| 0     | 4         | 4.08%   |
| 3     | 1         | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 71        | 71.72%  |
| Yes  | 28        | 28.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 23.08%  |
| Realtek Semiconductor           | 10        | 19.23%  |
| Qualcomm Atheros Communications | 7         | 13.46%  |
| IMC Networks                    | 5         | 9.62%   |
| MediaTek                        | 3         | 5.77%   |
| Apple                           | 3         | 5.77%   |
| Lite-On Technology              | 2         | 3.85%   |
| Hewlett-Packard                 | 2         | 3.85%   |
| Alps Electric                   | 2         | 3.85%   |
| Toshiba                         | 1         | 1.92%   |
| Foxconn / Hon Hai               | 1         | 1.92%   |
| Dell                            | 1         | 1.92%   |
| Cambridge Silicon Radio         | 1         | 1.92%   |
| Broadcom                        | 1         | 1.92%   |
| ASUSTek Computer                | 1         | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 8         | 15.38%  |
| Intel Bluetooth wireless interface                  | 6         | 11.54%  |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 9.62%   |
| MediaTek Wireless_Device                            | 3         | 5.77%   |
| IMC Networks Bluetooth Radio                        | 3         | 5.77%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 3.85%   |
| Intel AX201 Bluetooth                               | 2         | 3.85%   |
| Intel AX200 Bluetooth                               | 2         | 3.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 3.85%   |
| Alps Electric BCM2046 Bluetooth Device              | 2         | 3.85%   |
| Toshiba Askey for Toshiba                           | 1         | 1.92%   |
| Lite-On Wireless_Device                             | 1         | 1.92%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.92%   |
| IMC Networks Wireless_Device                        | 1         | 1.92%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.92%   |
| Dell Wireless 360 Bluetooth                         | 1         | 1.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.92%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.92%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 1.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.92%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.92%   |
| Apple Bluetooth HCI                                 | 1         | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 73        | 71.57%  |
| AMD                              | 21        | 20.59%  |
| Silicon Integrated Systems [SiS] | 4         | 3.92%   |
| Nvidia                           | 3         | 2.94%   |
| ESS Technology                   | 1         | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 6.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 5.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 4.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 4.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 4.96%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 4.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.13%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 4.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 4.13%   |
| AMD FCH Azalia Controller                                                                         | 5         | 4.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 3.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 3.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.48%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 2.48%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.48%   |
| AMD Ryzen HD Audio Controller                                                                     | 3         | 2.48%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 2.48%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 1.65%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.65%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 1.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.65%   |
| AMD Radeon High Definition Audio Controller                                                       | 2         | 1.65%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.65%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.83%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.83%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 0.83%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 0.83%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.83%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.83%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 0.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 26        | 23.64%  |
| Samsung Electronics | 24        | 21.82%  |
| SK hynix            | 15        | 13.64%  |
| Kingston            | 9         | 8.18%   |
| Elpida              | 7         | 6.36%   |
| Micron Technology   | 6         | 5.45%   |
| Unknown (ABCD)      | 5         | 4.55%   |
| Unknown (0x0DEC)    | 2         | 1.82%   |
| Team                | 2         | 1.82%   |
| Ramaxel Technology  | 2         | 1.82%   |
| Corsair             | 2         | 1.82%   |
| A-DATA Technology   | 2         | 1.82%   |
| Veineda             | 1         | 0.91%   |
| Toshiba             | 1         | 0.91%   |
| PNY                 | 1         | 0.91%   |
| Nanya Technology    | 1         | 0.91%   |
| Infineon            | 1         | 0.91%   |
| Crucial             | 1         | 0.91%   |
| 4ea5                | 1         | 0.91%   |
| Unknown             | 1         | 0.91%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 5.13%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 4.27%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 3         | 2.56%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 2         | 1.71%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 2         | 1.71%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 2         | 1.71%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.71%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 2         | 1.71%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 1.71%   |
| Unknown (0x0DEC) RAM D4N3200CS-8G 8GB SODIMM DDR4 3200MT/s       | 2         | 1.71%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.71%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 2         | 1.71%   |
| Veineda RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.85%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 0.85%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.85%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DRAM                               | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 0.85%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 0.85%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 0.85%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 0.85%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 0.85%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 0.85%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 0.85%   |
| Team RAM Elite-800 2GB SODIMM SDRAM                              | 1         | 0.85%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1334MT/s                     | 1         | 0.85%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 0.85%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 0.85%   |
| SK hynix RAM Module 1GB DIMM DDR2 533MT/s                        | 1         | 0.85%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.85%   |
| SK hynix RAM HMT851S6CMR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 35        | 35.71%  |
| DDR2   | 18        | 18.37%  |
| DDR4   | 17        | 17.35%  |
| DDR    | 7         | 7.14%   |
| SDRAM  | 6         | 6.12%   |
| LPDDR4 | 6         | 6.12%   |
| LPDDR3 | 4         | 4.08%   |
| DRAM   | 3         | 3.06%   |
| DDR5   | 2         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 88        | 90.72%  |
| Unknown      | 5         | 5.15%   |
| DIMM         | 3         | 3.09%   |
| Row Of Chips | 1         | 1.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 31        | 28.7%   |
| 2048  | 31        | 28.7%   |
| 8192  | 20        | 18.52%  |
| 1024  | 15        | 13.89%  |
| 512   | 5         | 4.63%   |
| 32768 | 2         | 1.85%   |
| 16384 | 2         | 1.85%   |
| 256   | 2         | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 23        | 22.55%  |
| Unknown | 17        | 16.67%  |
| 3200    | 10        | 9.8%    |
| 2400    | 9         | 8.82%   |
| 667     | 7         | 6.86%   |
| 1334    | 5         | 4.9%    |
| 2667    | 4         | 3.92%   |
| 1867    | 4         | 3.92%   |
| 1067    | 4         | 3.92%   |
| 1333    | 3         | 2.94%   |
| 533     | 3         | 2.94%   |
| 5600    | 2         | 1.96%   |
| 4199    | 2         | 1.96%   |
| 3266    | 2         | 1.96%   |
| 1066    | 2         | 1.96%   |
| 2048    | 1         | 0.98%   |
| 800     | 1         | 0.98%   |
| 400     | 1         | 0.98%   |
| 333     | 1         | 0.98%   |
| 266     | 1         | 0.98%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 13        | 20%     |
| IMC Networks                           | 7         | 10.77%  |
| Cheng Uei Precision Industry (Foxlink) | 7         | 10.77%  |
| Suyin                                  | 6         | 9.23%   |
| Microdia                               | 5         | 7.69%   |
| Quanta                                 | 4         | 6.15%   |
| Bison Electronics                      | 4         | 6.15%   |
| Ricoh                                  | 3         | 4.62%   |
| Sunplus Innovation Technology          | 2         | 3.08%   |
| Realtek Semiconductor                  | 2         | 3.08%   |
| Luxvisions Innotech Limited            | 2         | 3.08%   |
| Apple                                  | 2         | 3.08%   |
| Acer                                   | 2         | 3.08%   |
| USB Camera CS                          | 1         | 1.54%   |
| Silicon Motion                         | 1         | 1.54%   |
| GEMBIRD                                | 1         | 1.54%   |
| Cubeternet                             | 1         | 1.54%   |
| ALi                                    | 1         | 1.54%   |
| Alcor Micro                            | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin HP Truevision HD                                      | 2         | 3.03%   |
| Microdia Sonix USB 2.0 Camera                               | 2         | 3.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 3.03%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 3.03%   |
| USB Camera CS USB Camera CS                                 | 1         | 1.52%   |
| Suyin WebCam                                                | 1         | 1.52%   |
| Suyin HD WebCam                                             | 1         | 1.52%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 1.52%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.52%   |
| Sunplus HD WebCam                                           | 1         | 1.52%   |
| Sunplus Asus Webcam                                         | 1         | 1.52%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 1.52%   |
| Ricoh Webcam 1000                                           | 1         | 1.52%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 1.52%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 1.52%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 1.52%   |
| Realtek HD WebCam                                           | 1         | 1.52%   |
| Quanta HP Webcam                                            | 1         | 1.52%   |
| Quanta HP TrueVision HD Camera                              | 1         | 1.52%   |
| Quanta HD Webcam                                            | 1         | 1.52%   |
| Quanta Chromebook HD Camera                                 | 1         | 1.52%   |
| Microdia Webcam Vitade AF                                   | 1         | 1.52%   |
| Microdia Laptop_Integrated_Webcam_E4HD                      | 1         | 1.52%   |
| Microdia Integrated Webcam                                  | 1         | 1.52%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 1.52%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 1         | 1.52%   |
| IMC Networks USB 2.0 Camera                                 | 1         | 1.52%   |
| IMC Networks Integrated Camera                              | 1         | 1.52%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 1.52%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]           | 1         | 1.52%   |
| Cubeternet USB2.0 Camera                                    | 1         | 1.52%   |
| Chicony WebCam                                              | 1         | 1.52%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 1.52%   |
| Chicony Integrated Camera                                   | 1         | 1.52%   |
| Chicony HP Wide Vision HD                                   | 1         | 1.52%   |
| Chicony HP Webcam                                           | 1         | 1.52%   |
| Chicony HP Truevision HD camera                             | 1         | 1.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 42.86%  |
| Synaptics                  | 1         | 14.29%  |
| STMicroelectronics         | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |
| AuthenTec                  | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS451 Fingerprint Reader        | 2         | 28.57%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader             | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device               | 1         | 14.29%  |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| O2 Micro              | 1         | 33.33%  |
| Alcor Micro           | 1         | 33.33%  |
| Advanced Card Systems | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 33.33%  |
| Advanced Card Systems ACR122U        | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 74        | 75.51%  |
| 1     | 15        | 15.31%  |
| 2     | 7         | 7.14%   |
| 4     | 1         | 1.02%   |
| 3     | 1         | 1.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 15        | 42.86%  |
| Fingerprint reader       | 7         | 20%     |
| Net/wireless             | 4         | 11.43%  |
| Camera                   | 3         | 8.57%   |
| Flash memory             | 2         | 5.71%   |
| Communication controller | 2         | 5.71%   |
| Chipcard                 | 2         | 5.71%   |

