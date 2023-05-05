Pop!_OS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 7044

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P52s 20LCS1H100    | [34b877bcb5](https://linux-hardware.org/?probe=34b877bcb5) | May 01, 2023 |
| ASUSTek       | X455LJ                      | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [9df1b688c0](https://linux-hardware.org/?probe=9df1b688c0) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [875ae124a1](https://linux-hardware.org/?probe=875ae124a1) | Apr 30, 2023 |
| Dell          | Latitude E6430              | [4c20239367](https://linux-hardware.org/?probe=4c20239367) | Apr 30, 2023 |
| Apple         | MacBookPro11,3              | [3feeeb3341](https://linux-hardware.org/?probe=3feeeb3341) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | [8e0692ebe3](https://linux-hardware.org/?probe=8e0692ebe3) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | [39644ab1d4](https://linux-hardware.org/?probe=39644ab1d4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [a2cbf65767](https://linux-hardware.org/?probe=a2cbf65767) | Apr 28, 2023 |
| HP            | ENVY 15                     | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Dell          | Latitude D520               | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| System76      | Gazelle                     | [ca2e23db8d](https://linux-hardware.org/?probe=ca2e23db8d) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| HP            | ENVY 15                     | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [05d2b26ee6](https://linux-hardware.org/?probe=05d2b26ee6) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [0ef0676073](https://linux-hardware.org/?probe=0ef0676073) | Apr 25, 2023 |
| HP            | ENVY 15                     | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| Apple         | MacBookPro8,1               | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| Alienware     | 13 R2                       | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [1259bb0006](https://linux-hardware.org/?probe=1259bb0006) | Apr 24, 2023 |
| Alienware     | 13 R3                       | [f04b34f41d](https://linux-hardware.org/?probe=f04b34f41d) | Apr 23, 2023 |
| ASUSTek       | X551MA                      | [44ca7e29c0](https://linux-hardware.org/?probe=44ca7e29c0) | Apr 23, 2023 |
| Dell          | Inspiron 7737               | [50b75a71d3](https://linux-hardware.org/?probe=50b75a71d3) | Apr 23, 2023 |
| HP            | ZBook 15                    | [c7ae51efcd](https://linux-hardware.org/?probe=c7ae51efcd) | Apr 22, 2023 |
| Dell          | Inspiron 5567               | [f639b8e21a](https://linux-hardware.org/?probe=f639b8e21a) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [332fdb5298](https://linux-hardware.org/?probe=332fdb5298) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| GPU Compan... | GWTC116-2                   | [8f7df56d73](https://linux-hardware.org/?probe=8f7df56d73) | Apr 21, 2023 |
| HP            | ProBook 640 G1              | [b5022d8a2f](https://linux-hardware.org/?probe=b5022d8a2f) | Apr 21, 2023 |
| Dell          | Precision M6600             | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [4c78af0e05](https://linux-hardware.org/?probe=4c78af0e05) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [f9415c65e9](https://linux-hardware.org/?probe=f9415c65e9) | Apr 20, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [6222d9b2b0](https://linux-hardware.org/?probe=6222d9b2b0) | Apr 19, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | [fc27cf4b3e](https://linux-hardware.org/?probe=fc27cf4b3e) | Apr 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0187ac7a0c](https://linux-hardware.org/?probe=0187ac7a0c) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| American M... | XA133PR110                  | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [0f058078c9](https://linux-hardware.org/?probe=0f058078c9) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| Acer          | Aspire AV15-52              | [e1044f40e2](https://linux-hardware.org/?probe=e1044f40e2) | Apr 18, 2023 |
| Acer          | Aspire E5-575               | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [e779a9606f](https://linux-hardware.org/?probe=e779a9606f) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| MSI           | PS42 Modern 8RC             | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| American M... | XA133PR110                  | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| Toshiba       | Satellite E45-B             | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| Lenovo        | Legion 7 16IAX7 82TD        | [8f0188b2a1](https://linux-hardware.org/?probe=8f0188b2a1) | Apr 17, 2023 |
| Dell          | Inspiron 3541               | [dd409790ad](https://linux-hardware.org/?probe=dd409790ad) | Apr 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [55325c372c](https://linux-hardware.org/?probe=55325c372c) | Apr 17, 2023 |
| HP            | ENVY 17                     | [ba2c1aae76](https://linux-hardware.org/?probe=ba2c1aae76) | Apr 17, 2023 |
| HP            | Dev One Notebook PC         | [5e3f0907fa](https://linux-hardware.org/?probe=5e3f0907fa) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [beac478abb](https://linux-hardware.org/?probe=beac478abb) | Apr 16, 2023 |
| Dell          | XPS 13 9310                 | [3a7d52ef90](https://linux-hardware.org/?probe=3a7d52ef90) | Apr 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [6b126883e9](https://linux-hardware.org/?probe=6b126883e9) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [9ac7ca1a63](https://linux-hardware.org/?probe=9ac7ca1a63) | Apr 16, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [762ad80f82](https://linux-hardware.org/?probe=762ad80f82) | Apr 16, 2023 |
| Dell          | Inspiron 1525               | [3b20856ccc](https://linux-hardware.org/?probe=3b20856ccc) | Apr 16, 2023 |
| Acer          | Swift SFX14-41G             | [a0f08c4442](https://linux-hardware.org/?probe=a0f08c4442) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [f7ce1b2ab5](https://linux-hardware.org/?probe=f7ce1b2ab5) | Apr 15, 2023 |
| Medion        | E15415                      | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1d253a4901](https://linux-hardware.org/?probe=1d253a4901) | Apr 15, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [f45051411c](https://linux-hardware.org/?probe=f45051411c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | Pavilion g6                 | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Dell          | XPS 15 9560                 | [5ab7cc057f](https://linux-hardware.org/?probe=5ab7cc057f) | Apr 14, 2023 |
| Dell          | Precision 5550              | [1546772c9f](https://linux-hardware.org/?probe=1546772c9f) | Apr 14, 2023 |
| Dell          | Latitude E5440              | [a827218c2e](https://linux-hardware.org/?probe=a827218c2e) | Apr 14, 2023 |
| ASUSTek       | X551MA                      | [871fd53afd](https://linux-hardware.org/?probe=871fd53afd) | Apr 14, 2023 |
| HP            | Laptop 15z-fc000            | [df47336192](https://linux-hardware.org/?probe=df47336192) | Apr 14, 2023 |
| HP            | Notebook                    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Toshiba       | IS 1413G                    | [f57cf8ddf4](https://linux-hardware.org/?probe=f57cf8ddf4) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| System76      | Pangolin                    | [1750f20c8d](https://linux-hardware.org/?probe=1750f20c8d) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [1f12146974](https://linux-hardware.org/?probe=1f12146974) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9aadb88a2d](https://linux-hardware.org/?probe=9aadb88a2d) | Apr 12, 2023 |
| Apple         | MacBookPro8,1               | [94372e3520](https://linux-hardware.org/?probe=94372e3520) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0120f0db62](https://linux-hardware.org/?probe=0120f0db62) | Apr 12, 2023 |
| Dell          | G3 3579                     | [24d10a8497](https://linux-hardware.org/?probe=24d10a8497) | Apr 12, 2023 |
| Timi          | TM1707                      | [0e015e68ec](https://linux-hardware.org/?probe=0e015e68ec) | Apr 12, 2023 |
| Timi          | TM1707                      | [b611ba24ed](https://linux-hardware.org/?probe=b611ba24ed) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| Samsung       | 760XDA                      | [bdc1648c05](https://linux-hardware.org/?probe=bdc1648c05) | Apr 11, 2023 |
| Dell          | Latitude 5590               | [f8f0f0125f](https://linux-hardware.org/?probe=f8f0f0125f) | Apr 11, 2023 |
| MSI           | GF63 Thin 9RCX              | [c48286f8a2](https://linux-hardware.org/?probe=c48286f8a2) | Apr 10, 2023 |
| Apple         | MacBookPro11,4              | [85a39124f3](https://linux-hardware.org/?probe=85a39124f3) | Apr 09, 2023 |
| Apple         | MacBookPro12,1              | [0844c71fd0](https://linux-hardware.org/?probe=0844c71fd0) | Apr 07, 2023 |
| System76      | Oryx Pro                    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| HP            | ProBook 640 G1              | [769d886cc9](https://linux-hardware.org/?probe=769d886cc9) | Apr 05, 2023 |
| HP            | ProBook 640 G1              | [de7d3ba0c0](https://linux-hardware.org/?probe=de7d3ba0c0) | Apr 05, 2023 |
| Razer         | Blade                       | [351fe907cb](https://linux-hardware.org/?probe=351fe907cb) | Apr 05, 2023 |
| Apple         | MacBookPro12,1              | [c77ef60bcc](https://linux-hardware.org/?probe=c77ef60bcc) | Apr 05, 2023 |
| HP            | Laptop 14-dq0xxx            | [ba87782532](https://linux-hardware.org/?probe=ba87782532) | Apr 05, 2023 |
| Lenovo        | Edge 15 80K9                | [911d261c1b](https://linux-hardware.org/?probe=911d261c1b) | Apr 05, 2023 |
| ASUSTek       | N76VZ                       | [d87006e429](https://linux-hardware.org/?probe=d87006e429) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [58f5904dec](https://linux-hardware.org/?probe=58f5904dec) | Apr 04, 2023 |
| Dell          | Inspiron 7375               | [0d8465f75c](https://linux-hardware.org/?probe=0d8465f75c) | Apr 04, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [d56565f374](https://linux-hardware.org/?probe=d56565f374) | Apr 04, 2023 |
| Dell          | XPS 15 9500                 | [84f877fde3](https://linux-hardware.org/?probe=84f877fde3) | Apr 04, 2023 |
| ASUSTek       | E201NA                      | [098fb721f8](https://linux-hardware.org/?probe=098fb721f8) | Apr 04, 2023 |
| Acer          | Swift SF314-43              | [a964b0aa55](https://linux-hardware.org/?probe=a964b0aa55) | Apr 04, 2023 |
| Razer         | Blade Stealth               | [2cf4a53eb5](https://linux-hardware.org/?probe=2cf4a53eb5) | Apr 04, 2023 |
| Dell          | Latitude E7240              | [fce3da8380](https://linux-hardware.org/?probe=fce3da8380) | Apr 04, 2023 |
| Unknown       | Unknown                     | [190b5364e1](https://linux-hardware.org/?probe=190b5364e1) | Apr 03, 2023 |
| Unknown       | Unknown                     | [a6a766a40a](https://linux-hardware.org/?probe=a6a766a40a) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9880810adc](https://linux-hardware.org/?probe=9880810adc) | Apr 03, 2023 |
| MSI           | GV62 7RE                    | [5d441311f4](https://linux-hardware.org/?probe=5d441311f4) | Apr 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [777f7d0fc4](https://linux-hardware.org/?probe=777f7d0fc4) | Apr 03, 2023 |
| MSI           | GL63 8RC                    | [8c90ec7da1](https://linux-hardware.org/?probe=8c90ec7da1) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | [edb2f4188e](https://linux-hardware.org/?probe=edb2f4188e) | Apr 03, 2023 |
| HP            | 650                         | [bcb4e8d60a](https://linux-hardware.org/?probe=bcb4e8d60a) | Apr 03, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [7274c8222b](https://linux-hardware.org/?probe=7274c8222b) | Apr 02, 2023 |
| Lenovo        | ThinkPad T460p 20FXS08N0... | [ffcf174547](https://linux-hardware.org/?probe=ffcf174547) | Apr 02, 2023 |
| Apple         | MacBook3,1                  | [44f31f3094](https://linux-hardware.org/?probe=44f31f3094) | Apr 02, 2023 |
| System76      | Kudu                        | [2baafe374c](https://linux-hardware.org/?probe=2baafe374c) | Apr 02, 2023 |
| Toshiba       | IS 1413G                    | [76a94d8c87](https://linux-hardware.org/?probe=76a94d8c87) | Apr 02, 2023 |
| Sony          | VPCSC1AFM                   | [854b8bfa02](https://linux-hardware.org/?probe=854b8bfa02) | Apr 01, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [51c7ed9156](https://linux-hardware.org/?probe=51c7ed9156) | Apr 01, 2023 |
| Lenovo        | Slim 7 16ARH7 82UX          | [cca7093e15](https://linux-hardware.org/?probe=cca7093e15) | Apr 01, 2023 |
| Lenovo        | IdeaPad U310                | [6add75e18c](https://linux-hardware.org/?probe=6add75e18c) | Apr 01, 2023 |
| Toshiba       | Satellite L45-B             | [6d4878cdbf](https://linux-hardware.org/?probe=6d4878cdbf) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| System76      | Lemur Pro                   | [5d57a3397e](https://linux-hardware.org/?probe=5d57a3397e) | Mar 31, 2023 |
| ASUSTek       | X751LD                      | [2ef82331de](https://linux-hardware.org/?probe=2ef82331de) | Mar 31, 2023 |
| Acer          | Aspire A515-56              | [bf846cebb9](https://linux-hardware.org/?probe=bf846cebb9) | Mar 30, 2023 |
| Acer          | Nitro AN515-58              | [27befad01f](https://linux-hardware.org/?probe=27befad01f) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [21515b7373](https://linux-hardware.org/?probe=21515b7373) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [080e22fdb2](https://linux-hardware.org/?probe=080e22fdb2) | Mar 30, 2023 |
| Toshiba       | IS 1413G                    | [13f35137bd](https://linux-hardware.org/?probe=13f35137bd) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [7ee1845d96](https://linux-hardware.org/?probe=7ee1845d96) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [bb80f561a2](https://linux-hardware.org/?probe=bb80f561a2) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [854490056d](https://linux-hardware.org/?probe=854490056d) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [af48722867](https://linux-hardware.org/?probe=af48722867) | Mar 28, 2023 |
| Dell          | G3 3590                     | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0667374075](https://linux-hardware.org/?probe=0667374075) | Mar 28, 2023 |
| Acer          | Nitro AN515-45              | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [7939320fa4](https://linux-hardware.org/?probe=7939320fa4) | Mar 28, 2023 |
| Positivo      | Mobile                      | [60fd382fbf](https://linux-hardware.org/?probe=60fd382fbf) | Mar 28, 2023 |
| Positivo      | Mobile                      | [b08c430903](https://linux-hardware.org/?probe=b08c430903) | Mar 28, 2023 |
| Razer         | Blade                       | [ffa791eb4a](https://linux-hardware.org/?probe=ffa791eb4a) | Mar 28, 2023 |
| ASUSTek       | X751LD                      | [61382d0bd8](https://linux-hardware.org/?probe=61382d0bd8) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Toshiba       | IS 1413G                    | [635309aff4](https://linux-hardware.org/?probe=635309aff4) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T400     | [5b4466c085](https://linux-hardware.org/?probe=5b4466c085) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [8ddee342c9](https://linux-hardware.org/?probe=8ddee342c9) | Mar 28, 2023 |
| Dell          | XPS 15 9570                 | [5be538736f](https://linux-hardware.org/?probe=5be538736f) | Mar 27, 2023 |
| Toshiba       | Satellite C55-C             | [d7ec0eb4b1](https://linux-hardware.org/?probe=d7ec0eb4b1) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | [a5c200217f](https://linux-hardware.org/?probe=a5c200217f) | Mar 26, 2023 |
| MSI           | GL63 8RC                    | [935b78c3da](https://linux-hardware.org/?probe=935b78c3da) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [905078c7b9](https://linux-hardware.org/?probe=905078c7b9) | Mar 26, 2023 |
| Dell          | Latitude E7240              | [3d91b46fda](https://linux-hardware.org/?probe=3d91b46fda) | Mar 26, 2023 |
| Dell          | XPS 13 9370                 | [3f3967267f](https://linux-hardware.org/?probe=3f3967267f) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| HP            | Spectre Laptop 13-af0xx     | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | [21c3ce9508](https://linux-hardware.org/?probe=21c3ce9508) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ac415822b8](https://linux-hardware.org/?probe=ac415822b8) | Mar 24, 2023 |
| HP            | Laptop 15-db0xxx            | [ad0e5c0483](https://linux-hardware.org/?probe=ad0e5c0483) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [e6afbbee47](https://linux-hardware.org/?probe=e6afbbee47) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| Alienware     | 17 R4                       | [3c456dc309](https://linux-hardware.org/?probe=3c456dc309) | Mar 24, 2023 |
| GPU Compan... | GWTN141-10                  | [9007c1d23f](https://linux-hardware.org/?probe=9007c1d23f) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| Dell          | Precision 7710              | [25a4797475](https://linux-hardware.org/?probe=25a4797475) | Mar 23, 2023 |
| Toshiba       | IS 1413G                    | [3a75d7fb8d](https://linux-hardware.org/?probe=3a75d7fb8d) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [f6580b20d3](https://linux-hardware.org/?probe=f6580b20d3) | Mar 22, 2023 |
| Apple         | MacBook5,1                  | [bc6e3fa274](https://linux-hardware.org/?probe=bc6e3fa274) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | [627590f38c](https://linux-hardware.org/?probe=627590f38c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [a49ece0e6c](https://linux-hardware.org/?probe=a49ece0e6c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [315f2256c6](https://linux-hardware.org/?probe=315f2256c6) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | [aff8d829e0](https://linux-hardware.org/?probe=aff8d829e0) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | [af60ed4cde](https://linux-hardware.org/?probe=af60ed4cde) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | [3b3376e72c](https://linux-hardware.org/?probe=3b3376e72c) | Mar 21, 2023 |
| HUAWEI        | KPL-W0X                     | [afc1ff125b](https://linux-hardware.org/?probe=afc1ff125b) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [3c100c55be](https://linux-hardware.org/?probe=3c100c55be) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [039724e2c2](https://linux-hardware.org/?probe=039724e2c2) | Mar 21, 2023 |
| Dell          | G15 5511                    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | XPS L421X                   | [fd54af9534](https://linux-hardware.org/?probe=fd54af9534) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [afe8ca841c](https://linux-hardware.org/?probe=afe8ca841c) | Mar 21, 2023 |
| Acer          | Aspire 5349                 | [c0f5810e5c](https://linux-hardware.org/?probe=c0f5810e5c) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | [d6ff521952](https://linux-hardware.org/?probe=d6ff521952) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | [d6393f5710](https://linux-hardware.org/?probe=d6393f5710) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | [404c84b0ea](https://linux-hardware.org/?probe=404c84b0ea) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | [edf722e245](https://linux-hardware.org/?probe=edf722e245) | Mar 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [2ff2eab844](https://linux-hardware.org/?probe=2ff2eab844) | Mar 21, 2023 |
| ASUSTek       | G74Sx                       | [d2b90b7d2f](https://linux-hardware.org/?probe=d2b90b7d2f) | Mar 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [afcac034a9](https://linux-hardware.org/?probe=afcac034a9) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c9b4e3cf00](https://linux-hardware.org/?probe=c9b4e3cf00) | Mar 20, 2023 |
| Dell          | Latitude 5590               | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| MSI           | PS42 8M                     | [aad18852f4](https://linux-hardware.org/?probe=aad18852f4) | Mar 19, 2023 |
| ASUSTek       | G74Sx                       | [f7f92408dc](https://linux-hardware.org/?probe=f7f92408dc) | Mar 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6b6ceb1a1a](https://linux-hardware.org/?probe=6b6ceb1a1a) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e3410282c5](https://linux-hardware.org/?probe=e3410282c5) | Mar 19, 2023 |
| ASUSTek       | S551LB                      | [7d4485326f](https://linux-hardware.org/?probe=7d4485326f) | Mar 18, 2023 |
| GPU Compan... | GWTN141-10                  | [ff8db61ccf](https://linux-hardware.org/?probe=ff8db61ccf) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [dd296a8801](https://linux-hardware.org/?probe=dd296a8801) | Mar 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S11N00    | [60d80937ea](https://linux-hardware.org/?probe=60d80937ea) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| Dell          | Latitude E7240              | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| Positivo      | N1250                       | [e5ee22876a](https://linux-hardware.org/?probe=e5ee22876a) | Mar 17, 2023 |
| HP            | ProBook 4530s               | [f0abd32fe4](https://linux-hardware.org/?probe=f0abd32fe4) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [a7a6cc1ab5](https://linux-hardware.org/?probe=a7a6cc1ab5) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [204994be7f](https://linux-hardware.org/?probe=204994be7f) | Mar 17, 2023 |
| TUXEDO        | Pulse 14 Gen1               | [525b267c31](https://linux-hardware.org/?probe=525b267c31) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| Unknown       | Unknown                     | [3eb0bf05b4](https://linux-hardware.org/?probe=3eb0bf05b4) | Mar 17, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0RP0... | [f901058202](https://linux-hardware.org/?probe=f901058202) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d6f5cd9505](https://linux-hardware.org/?probe=d6f5cd9505) | Mar 16, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [5f48c46d68](https://linux-hardware.org/?probe=5f48c46d68) | Mar 16, 2023 |
| HP            | Laptop 15s-eq1xxx           | [59a304e790](https://linux-hardware.org/?probe=59a304e790) | Mar 15, 2023 |
| Acer          | Aspire A715-42G             | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| Razer         | Blade Stealth 13 (Early ... | [eb1d71edb4](https://linux-hardware.org/?probe=eb1d71edb4) | Mar 15, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [af254fca4d](https://linux-hardware.org/?probe=af254fca4d) | Mar 15, 2023 |
| SAGER         | X8100                       | [90aaefeb9e](https://linux-hardware.org/?probe=90aaefeb9e) | Mar 15, 2023 |
| System76      | Pangolin                    | [4f39796131](https://linux-hardware.org/?probe=4f39796131) | Mar 15, 2023 |
| Dell          | Latitude E7240              | [d4ed345a47](https://linux-hardware.org/?probe=d4ed345a47) | Mar 14, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | [1161c07721](https://linux-hardware.org/?probe=1161c07721) | Mar 14, 2023 |
| Sony          | VPCZ12V9R                   | [28be5f7f2b](https://linux-hardware.org/?probe=28be5f7f2b) | Mar 14, 2023 |
| Dell          | Latitude E7240              | [4a7d442938](https://linux-hardware.org/?probe=4a7d442938) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | [44d9ce8acb](https://linux-hardware.org/?probe=44d9ce8acb) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | [986fe8c418](https://linux-hardware.org/?probe=986fe8c418) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| HP            | EliteBook 840 G6            | [874706952d](https://linux-hardware.org/?probe=874706952d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [de22b8a7e6](https://linux-hardware.org/?probe=de22b8a7e6) | Mar 14, 2023 |
| Dell          | Inspiron 7348               | [7459d24035](https://linux-hardware.org/?probe=7459d24035) | Mar 13, 2023 |
| Apple         | MacBookPro9,1               | [f85095c103](https://linux-hardware.org/?probe=f85095c103) | Mar 13, 2023 |
| Toshiba       | IS 1413G                    | [b93a4bdcbb](https://linux-hardware.org/?probe=b93a4bdcbb) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| Acer          | Nitro AN515-58              | [7f2ecd927d](https://linux-hardware.org/?probe=7f2ecd927d) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | [663f73a08e](https://linux-hardware.org/?probe=663f73a08e) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | [5d1a30091e](https://linux-hardware.org/?probe=5d1a30091e) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| HUAWEI        | NBM-WXX9                    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Google        | Kefka                       | [4a54e34e44](https://linux-hardware.org/?probe=4a54e34e44) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| Dell          | Inspiron 5452               | [2c8ca0e296](https://linux-hardware.org/?probe=2c8ca0e296) | Mar 12, 2023 |
| Positivo B... | VJFE41F11X-XXXXXX           | [99f410d801](https://linux-hardware.org/?probe=99f410d801) | Mar 11, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [e101a1c94c](https://linux-hardware.org/?probe=e101a1c94c) | Mar 11, 2023 |
| HONOR         | NMH-WCX9                    | [d8cf10f11d](https://linux-hardware.org/?probe=d8cf10f11d) | Mar 11, 2023 |
| HP            | ZBook 17                    | [a775bc33c5](https://linux-hardware.org/?probe=a775bc33c5) | Mar 11, 2023 |
| Maibenben     | P748                        | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Toshiba       | IS 1413G                    | [39cc207ce7](https://linux-hardware.org/?probe=39cc207ce7) | Mar 11, 2023 |
| Lenovo        | ThinkPad L440 20ASS0ET00    | [2ac6dfff4f](https://linux-hardware.org/?probe=2ac6dfff4f) | Mar 11, 2023 |
| GPD           | G1619-04                    | [302ff30130](https://linux-hardware.org/?probe=302ff30130) | Mar 11, 2023 |
| GPD           | G1619-04                    | [d8f5b9eec9](https://linux-hardware.org/?probe=d8f5b9eec9) | Mar 11, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [969ab4279f](https://linux-hardware.org/?probe=969ab4279f) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [c44f0eab3e](https://linux-hardware.org/?probe=c44f0eab3e) | Mar 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [50dd87563b](https://linux-hardware.org/?probe=50dd87563b) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [410a5a70f3](https://linux-hardware.org/?probe=410a5a70f3) | Mar 10, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [eac4ae85a4](https://linux-hardware.org/?probe=eac4ae85a4) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [baffc24bef](https://linux-hardware.org/?probe=baffc24bef) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [187761b57d](https://linux-hardware.org/?probe=187761b57d) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4e1196658a](https://linux-hardware.org/?probe=4e1196658a) | Mar 09, 2023 |
| HP            | ENVY Notebook               | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [a8d1bd3e81](https://linux-hardware.org/?probe=a8d1bd3e81) | Mar 09, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [7805fe229d](https://linux-hardware.org/?probe=7805fe229d) | Mar 08, 2023 |
| HP            | EliteBook 8570w             | [dfd9b7a9b9](https://linux-hardware.org/?probe=dfd9b7a9b9) | Mar 08, 2023 |
| Razer         | Blade 15 Advanced Model ... | [46fa9eab7d](https://linux-hardware.org/?probe=46fa9eab7d) | Mar 08, 2023 |
| Google        | Bobba                       | [01d8f57c7e](https://linux-hardware.org/?probe=01d8f57c7e) | Mar 08, 2023 |
| Lenovo        | IdeaPad U310                | [f666446ecb](https://linux-hardware.org/?probe=f666446ecb) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3ff5ff8f2d](https://linux-hardware.org/?probe=3ff5ff8f2d) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | [4a698cb3eb](https://linux-hardware.org/?probe=4a698cb3eb) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| Toshiba       | IS 1413G                    | [12954ccbdb](https://linux-hardware.org/?probe=12954ccbdb) | Mar 07, 2023 |
| Google        | Lillipup                    | [b924f92de8](https://linux-hardware.org/?probe=b924f92de8) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | [5a03b7e11e](https://linux-hardware.org/?probe=5a03b7e11e) | Mar 07, 2023 |
| Apple         | MacBookPro8,1               | [bef545e821](https://linux-hardware.org/?probe=bef545e821) | Mar 07, 2023 |
| Dell          | Inspiron 16 7610            | [625691c490](https://linux-hardware.org/?probe=625691c490) | Mar 06, 2023 |
| Dell          | Inspiron 16 7610            | [66b4f88fb7](https://linux-hardware.org/?probe=66b4f88fb7) | Mar 06, 2023 |
| HP            | 3115m                       | [87abd0ac9d](https://linux-hardware.org/?probe=87abd0ac9d) | Mar 06, 2023 |
| Dell          | G7 7588                     | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| HUAWEI        | KPL-W0X                     | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Apple         | MacBookAir7,2               | [ae4d8e9128](https://linux-hardware.org/?probe=ae4d8e9128) | Mar 06, 2023 |
| MSI           | Vector GP76 12UHSO          | [e82fbd8c0a](https://linux-hardware.org/?probe=e82fbd8c0a) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | [a6c8ba1040](https://linux-hardware.org/?probe=a6c8ba1040) | Mar 05, 2023 |
| Apple         | MacBookAir7,2               | [fef18d1795](https://linux-hardware.org/?probe=fef18d1795) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [779113ef3c](https://linux-hardware.org/?probe=779113ef3c) | Mar 05, 2023 |
| HP            | Pavilion 15                 | [0c4050d1ef](https://linux-hardware.org/?probe=0c4050d1ef) | Mar 05, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [ff4621a345](https://linux-hardware.org/?probe=ff4621a345) | Mar 05, 2023 |
| Dell          | Latitude 5420               | [ea5ac72a44](https://linux-hardware.org/?probe=ea5ac72a44) | Mar 05, 2023 |
| Toshiba       | IS 1413G                    | [a655c49d8b](https://linux-hardware.org/?probe=a655c49d8b) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | [ca5a019457](https://linux-hardware.org/?probe=ca5a019457) | Mar 04, 2023 |
| Apple         | MacBookPro9,2               | [ba908d3339](https://linux-hardware.org/?probe=ba908d3339) | Mar 04, 2023 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [26ca476e1a](https://linux-hardware.org/?probe=26ca476e1a) | Mar 04, 2023 |
| Dell          | System XPS L321X            | [24d0d12eca](https://linux-hardware.org/?probe=24d0d12eca) | Mar 04, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | [ccda7b2155](https://linux-hardware.org/?probe=ccda7b2155) | Mar 04, 2023 |
| Gigabyte      | AORUS 17 XE4                | [6f6750ee73](https://linux-hardware.org/?probe=6f6750ee73) | Mar 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [db92a5f137](https://linux-hardware.org/?probe=db92a5f137) | Mar 03, 2023 |
| HP            | EliteBook 8440p             | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | [756ac6782b](https://linux-hardware.org/?probe=756ac6782b) | Mar 03, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Acer          | Swift SF314-54              | [62defb89e3](https://linux-hardware.org/?probe=62defb89e3) | Mar 02, 2023 |
| System76      | Lemur Pro                   | [e7ed83aaf7](https://linux-hardware.org/?probe=e7ed83aaf7) | Mar 01, 2023 |
| HP            | 15                          | [97985ac192](https://linux-hardware.org/?probe=97985ac192) | Mar 01, 2023 |
| HP            | EliteBook 830 G5            | [9abfe7631c](https://linux-hardware.org/?probe=9abfe7631c) | Mar 01, 2023 |
| ASUSTek       | X751LD                      | [46eecb2678](https://linux-hardware.org/?probe=46eecb2678) | Mar 01, 2023 |
| Dell          | Precision 3571              | [40348190de](https://linux-hardware.org/?probe=40348190de) | Mar 01, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [571d426262](https://linux-hardware.org/?probe=571d426262) | Mar 01, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [78ee2e145b](https://linux-hardware.org/?probe=78ee2e145b) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [bd4fd4080d](https://linux-hardware.org/?probe=bd4fd4080d) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [90d8927f0a](https://linux-hardware.org/?probe=90d8927f0a) | Mar 01, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [5aad25779a](https://linux-hardware.org/?probe=5aad25779a) | Feb 28, 2023 |
| Acer          | Aspire A515-57              | [6c511739eb](https://linux-hardware.org/?probe=6c511739eb) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | [ff84200b75](https://linux-hardware.org/?probe=ff84200b75) | Feb 28, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [88745e1f03](https://linux-hardware.org/?probe=88745e1f03) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [357c1abb1d](https://linux-hardware.org/?probe=357c1abb1d) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [82a40f1881](https://linux-hardware.org/?probe=82a40f1881) | Feb 27, 2023 |
| Acer          | Aspire A515-56              | [97e3001416](https://linux-hardware.org/?probe=97e3001416) | Feb 26, 2023 |
| Dell          | XPS 13 7390                 | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Acer          | Nitro AN515-58              | [1c93095718](https://linux-hardware.org/?probe=1c93095718) | Feb 26, 2023 |
| Sony          | VPCZ12V9R                   | [3014067c24](https://linux-hardware.org/?probe=3014067c24) | Feb 26, 2023 |
| GPU Compan... | GWTN141-10                  | [1550bec17e](https://linux-hardware.org/?probe=1550bec17e) | Feb 25, 2023 |
| GPU Compan... | GWTN141-10                  | [aa535b0731](https://linux-hardware.org/?probe=aa535b0731) | Feb 25, 2023 |
| Dell          | G7 7588                     | [82f1398a69](https://linux-hardware.org/?probe=82f1398a69) | Feb 25, 2023 |
| Alienware     | 15 R3                       | [72543030d5](https://linux-hardware.org/?probe=72543030d5) | Feb 25, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [42b9d60137](https://linux-hardware.org/?probe=42b9d60137) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| System76      | Galago Pro                  | [3e4391562b](https://linux-hardware.org/?probe=3e4391562b) | Feb 25, 2023 |
| Packard Be... | EasyNote TS11HR             | [0a63352761](https://linux-hardware.org/?probe=0a63352761) | Feb 25, 2023 |
| Dell          | XPS 15 9500                 | [96e6c2c201](https://linux-hardware.org/?probe=96e6c2c201) | Feb 25, 2023 |
| Dell          | Latitude 3310               | [d989647d9d](https://linux-hardware.org/?probe=d989647d9d) | Feb 25, 2023 |
| Acer          | Aspire A515-56              | [517a6211c9](https://linux-hardware.org/?probe=517a6211c9) | Feb 24, 2023 |
| HP            | ProBook 450 G1              | [f7c4b009f1](https://linux-hardware.org/?probe=f7c4b009f1) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [2f561a23c3](https://linux-hardware.org/?probe=2f561a23c3) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [041c57ebe6](https://linux-hardware.org/?probe=041c57ebe6) | Feb 24, 2023 |
| Apple         | MacBookPro9,2               | [c591acd5d6](https://linux-hardware.org/?probe=c591acd5d6) | Feb 24, 2023 |
| Dell          | Inspiron 5423               | [7cf47f3118](https://linux-hardware.org/?probe=7cf47f3118) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [bb0d8e868d](https://linux-hardware.org/?probe=bb0d8e868d) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| System76      | Gazelle                     | [609f452af9](https://linux-hardware.org/?probe=609f452af9) | Feb 23, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | [33a4731a5e](https://linux-hardware.org/?probe=33a4731a5e) | Feb 23, 2023 |
| Dell          | Latitude E7240              | [7f8278ff44](https://linux-hardware.org/?probe=7f8278ff44) | Feb 23, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [34016a67d9](https://linux-hardware.org/?probe=34016a67d9) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [6ab727e8c0](https://linux-hardware.org/?probe=6ab727e8c0) | Feb 22, 2023 |
| Apple         | MacBookPro11,4              | [c4eab564b3](https://linux-hardware.org/?probe=c4eab564b3) | Feb 22, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| HP            | EliteBook Folio 1040 G2     | [265018acd3](https://linux-hardware.org/?probe=265018acd3) | Feb 21, 2023 |
| Apple         | MacBookPro16,1              | [a5cff07fd8](https://linux-hardware.org/?probe=a5cff07fd8) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| Dell          | G15 5525                    | [63bd2ac7b9](https://linux-hardware.org/?probe=63bd2ac7b9) | Feb 21, 2023 |
| Acer          | Swift SF114-34              | [e9f5a9d293](https://linux-hardware.org/?probe=e9f5a9d293) | Feb 21, 2023 |
| Dell          | Precision M4800             | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| HP            | Laptop 14s-fq0xxx           | [0bc03f3b39](https://linux-hardware.org/?probe=0bc03f3b39) | Feb 20, 2023 |
| HP            | ProBook 450 G1              | [b5e8826f8c](https://linux-hardware.org/?probe=b5e8826f8c) | Feb 20, 2023 |
| Dell          | XPS 15 7590                 | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Apple         | MacBook4,1                  | [2011c2060b](https://linux-hardware.org/?probe=2011c2060b) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Dell          | Latitude E7240              | [461873da2d](https://linux-hardware.org/?probe=461873da2d) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [5cc4ff8271](https://linux-hardware.org/?probe=5cc4ff8271) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [75f9e575b3](https://linux-hardware.org/?probe=75f9e575b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f120e182a1](https://linux-hardware.org/?probe=f120e182a1) | Feb 17, 2023 |
| HUAWEI        | BOD-WXX9                    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| HP            | EliteBook 830 G5            | [7ef47e7131](https://linux-hardware.org/?probe=7ef47e7131) | Feb 17, 2023 |
| HONOR         | NBR-WAX9                    | [b16ea0055d](https://linux-hardware.org/?probe=b16ea0055d) | Feb 17, 2023 |
| Dell          | Latitude E4200              | [18868db8a1](https://linux-hardware.org/?probe=18868db8a1) | Feb 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [91c566ccc9](https://linux-hardware.org/?probe=91c566ccc9) | Feb 16, 2023 |
| Apple         | MacBookPro9,2               | [e67f600749](https://linux-hardware.org/?probe=e67f600749) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| Lenovo        | G50-80 80E5                 | [64c385ee36](https://linux-hardware.org/?probe=64c385ee36) | Feb 16, 2023 |
| OriginPC      | Voyager a1600               | [9608c5afd5](https://linux-hardware.org/?probe=9608c5afd5) | Feb 16, 2023 |
| Google        | Blorb                       | [286353731c](https://linux-hardware.org/?probe=286353731c) | Feb 16, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [1b89c43b58](https://linux-hardware.org/?probe=1b89c43b58) | Feb 16, 2023 |
| HP            | EliteBook 850 G2            | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Apple         | MacBookPro12,1              | [bdb6e585b0](https://linux-hardware.org/?probe=bdb6e585b0) | Feb 15, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | [5c4a26ada0](https://linux-hardware.org/?probe=5c4a26ada0) | Feb 14, 2023 |
| Dell          | Precision M3800             | [98b54858cb](https://linux-hardware.org/?probe=98b54858cb) | Feb 14, 2023 |
| Dell          | Inspiron 15 3511            | [1028ef9686](https://linux-hardware.org/?probe=1028ef9686) | Feb 14, 2023 |
| MSI           | Prestige 14Evo A11M         | [abeebd4312](https://linux-hardware.org/?probe=abeebd4312) | Feb 13, 2023 |
| Sony          | VPCEG27FM                   | [748a67669f](https://linux-hardware.org/?probe=748a67669f) | Feb 13, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [a6af7624cd](https://linux-hardware.org/?probe=a6af7624cd) | Feb 13, 2023 |
| Samsung       | 730U3E/740U3E               | [91ac69dfa1](https://linux-hardware.org/?probe=91ac69dfa1) | Feb 13, 2023 |
| Lenovo        | ThinkPad T410 2522G76       | [b15d4051cd](https://linux-hardware.org/?probe=b15d4051cd) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [d38212ee96](https://linux-hardware.org/?probe=d38212ee96) | Feb 13, 2023 |
| Apple         | MacBookPro11,2              | [2314b98760](https://linux-hardware.org/?probe=2314b98760) | Feb 12, 2023 |
| Apple         | MacBookPro12,1              | [139b92595a](https://linux-hardware.org/?probe=139b92595a) | Feb 12, 2023 |
| Haier         | GG1500A                     | [4c4598157f](https://linux-hardware.org/?probe=4c4598157f) | Feb 12, 2023 |
| Dell          | Latitude XT2                | [9b98bf4722](https://linux-hardware.org/?probe=9b98bf4722) | Feb 12, 2023 |
| Dell          | Precision M4700             | [1a44cb5ef9](https://linux-hardware.org/?probe=1a44cb5ef9) | Feb 11, 2023 |
| Apple         | MacBookPro11,1              | [fb407bfc13](https://linux-hardware.org/?probe=fb407bfc13) | Feb 11, 2023 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | [322a9d340e](https://linux-hardware.org/?probe=322a9d340e) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | [ab07f075d8](https://linux-hardware.org/?probe=ab07f075d8) | Feb 11, 2023 |
| Apple         | MacBook8,1                  | [2f1c5b90a8](https://linux-hardware.org/?probe=2f1c5b90a8) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | [24cb179c5a](https://linux-hardware.org/?probe=24cb179c5a) | Feb 11, 2023 |
| MSI           | GF63 Thin 9RCX              | [9cbcfdd748](https://linux-hardware.org/?probe=9cbcfdd748) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | G15 5520                    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [d0cc5f80fc](https://linux-hardware.org/?probe=d0cc5f80fc) | Feb 09, 2023 |
| HP            | EliteBook 840 G5            | [39dbdb0fa9](https://linux-hardware.org/?probe=39dbdb0fa9) | Feb 09, 2023 |
| Lenovo        | ThinkPad T450 20BUA0PNUK    | [8837c33007](https://linux-hardware.org/?probe=8837c33007) | Feb 09, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [74dd2176ff](https://linux-hardware.org/?probe=74dd2176ff) | Feb 09, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [93afe9ddeb](https://linux-hardware.org/?probe=93afe9ddeb) | Feb 09, 2023 |
| Dell          | Inspiron 3576               | [a025641dfc](https://linux-hardware.org/?probe=a025641dfc) | Feb 09, 2023 |
| Acer          | Aspire A315-59              | [edc6b0a3af](https://linux-hardware.org/?probe=edc6b0a3af) | Feb 09, 2023 |
| Dell          | XPS 13 9360                 | [db7e89340f](https://linux-hardware.org/?probe=db7e89340f) | Feb 09, 2023 |
| System76      | Lemur Pro                   | [94cf78a9d9](https://linux-hardware.org/?probe=94cf78a9d9) | Feb 08, 2023 |
| Dell          | G15 5520                    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| HP            | EliteBook 830 G5            | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Dell          | System XPS L702X            | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| Alienware     | m15 R7                      | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [f6c24b1ea8](https://linux-hardware.org/?probe=f6c24b1ea8) | Feb 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [50af8c9fe6](https://linux-hardware.org/?probe=50af8c9fe6) | Feb 06, 2023 |
| ASUSTek       | UX430UNR                    | [96d7a1938a](https://linux-hardware.org/?probe=96d7a1938a) | Feb 06, 2023 |
| Acer          | Swift SF114-34              | [28aad1fae5](https://linux-hardware.org/?probe=28aad1fae5) | Feb 06, 2023 |
| ASUSTek       | X751LD                      | [12d5592082](https://linux-hardware.org/?probe=12d5592082) | Feb 06, 2023 |
| Notebook      | NJ50_70CU                   | [c0c9951f8d](https://linux-hardware.org/?probe=c0c9951f8d) | Feb 05, 2023 |
| Dell          | Latitude 7380               | [7b9d4ef8b4](https://linux-hardware.org/?probe=7b9d4ef8b4) | Feb 05, 2023 |
| Acer          | Swift SF114-34              | [ea8a0e0617](https://linux-hardware.org/?probe=ea8a0e0617) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Alienware     | 17 R5                       | [7f5f8bdb1f](https://linux-hardware.org/?probe=7f5f8bdb1f) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK T902               | [9c92a1772d](https://linux-hardware.org/?probe=9c92a1772d) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d95f28d447](https://linux-hardware.org/?probe=d95f28d447) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | [a705eb3101](https://linux-hardware.org/?probe=a705eb3101) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | [7a80b2d6d7](https://linux-hardware.org/?probe=7a80b2d6d7) | Feb 05, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [e5e8537cef](https://linux-hardware.org/?probe=e5e8537cef) | Feb 05, 2023 |
| HP            | Laptop 15-bw0xx             | [0cb9ba3cf9](https://linux-hardware.org/?probe=0cb9ba3cf9) | Feb 05, 2023 |
| ASUSTek       | X751LD                      | [13948b75ae](https://linux-hardware.org/?probe=13948b75ae) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| HP            | Notebook                    | [0ad701667d](https://linux-hardware.org/?probe=0ad701667d) | Feb 05, 2023 |
| HP            | Notebook                    | [37f601798c](https://linux-hardware.org/?probe=37f601798c) | Feb 05, 2023 |
| Dell          | G15 5515                    | [7418ca82c1](https://linux-hardware.org/?probe=7418ca82c1) | Feb 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| Dell          | Latitude 3520               | [ce594f431c](https://linux-hardware.org/?probe=ce594f431c) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | [149465f225](https://linux-hardware.org/?probe=149465f225) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [448d3800ac](https://linux-hardware.org/?probe=448d3800ac) | Feb 04, 2023 |
| Toshiba       | Satellite C855-233          | [8fc7835588](https://linux-hardware.org/?probe=8fc7835588) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0017US     | [43c5ab14ec](https://linux-hardware.org/?probe=43c5ab14ec) | Feb 03, 2023 |
| Dell          | Latitude E7240              | [da54499919](https://linux-hardware.org/?probe=da54499919) | Feb 03, 2023 |
| Haier         | GG1500A                     | [b54ce000d3](https://linux-hardware.org/?probe=b54ce000d3) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [98ad1bcab4](https://linux-hardware.org/?probe=98ad1bcab4) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [5fe174bdd1](https://linux-hardware.org/?probe=5fe174bdd1) | Feb 03, 2023 |
| Acer          | Aspire A315-59              | [704c6e370c](https://linux-hardware.org/?probe=704c6e370c) | Feb 03, 2023 |
| Timi          | RedmiBook Pro 15S           | [8a1c423c67](https://linux-hardware.org/?probe=8a1c423c67) | Feb 03, 2023 |
| Apple         | MacBookPro8,1               | [c441c159c1](https://linux-hardware.org/?probe=c441c159c1) | Feb 03, 2023 |
| HP            | Laptop 15-db1xxx            | [8944f22b68](https://linux-hardware.org/?probe=8944f22b68) | Feb 02, 2023 |
| Acer          | Swift SF114-32              | [96b48bebd2](https://linux-hardware.org/?probe=96b48bebd2) | Feb 02, 2023 |
| Dell          | Inspiron 3584               | [4bfcbe7c13](https://linux-hardware.org/?probe=4bfcbe7c13) | Feb 02, 2023 |
| Dell          | Precision 3571              | [8ee8f6f768](https://linux-hardware.org/?probe=8ee8f6f768) | Feb 02, 2023 |
| Dell          | Precision 3571              | [9453f26568](https://linux-hardware.org/?probe=9453f26568) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [8db619716a](https://linux-hardware.org/?probe=8db619716a) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [7019bd88e0](https://linux-hardware.org/?probe=7019bd88e0) | Feb 01, 2023 |
| HP            | Pavilion 15                 | [946fec8f7d](https://linux-hardware.org/?probe=946fec8f7d) | Feb 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6294616fc6](https://linux-hardware.org/?probe=6294616fc6) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Timi          | Mi NoteBook Ultra           | [d897ec0114](https://linux-hardware.org/?probe=d897ec0114) | Feb 01, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [c4869ecf2c](https://linux-hardware.org/?probe=c4869ecf2c) | Feb 01, 2023 |
| Acer          | Predator PH517-61           | [b16ddc31d8](https://linux-hardware.org/?probe=b16ddc31d8) | Feb 01, 2023 |
| Dell          | Latitude E7240              | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| Apple         | MacBookPro12,1              | [228ab40738](https://linux-hardware.org/?probe=228ab40738) | Jan 31, 2023 |
| HP            | Notebook                    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| HP            | ZBook Studio G3             | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | [7636aeaacc](https://linux-hardware.org/?probe=7636aeaacc) | Jan 31, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [230b38f8e6](https://linux-hardware.org/?probe=230b38f8e6) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | [82d317899e](https://linux-hardware.org/?probe=82d317899e) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| GPU Compan... | GWTN141-10                  | [f012d6d71c](https://linux-hardware.org/?probe=f012d6d71c) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Acer          | Swift SF114-32              | [1228d6d0f7](https://linux-hardware.org/?probe=1228d6d0f7) | Jan 30, 2023 |
| Dell          | G15 5511                    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| Dell          | Latitude E7240              | [a1f713f6e3](https://linux-hardware.org/?probe=a1f713f6e3) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| HP            | Pavilion dv6                | [0966ae419c](https://linux-hardware.org/?probe=0966ae419c) | Jan 30, 2023 |
| ASUSTek       | X555LD                      | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| Dell          | G15 5515                    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [ff3381fe1a](https://linux-hardware.org/?probe=ff3381fe1a) | Jan 28, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [c6770f3828](https://linux-hardware.org/?probe=c6770f3828) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| ASUSTek       | ET2321I                     | [dbb162975e](https://linux-hardware.org/?probe=dbb162975e) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | [549b690251](https://linux-hardware.org/?probe=549b690251) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | [cbbd1d3e3e](https://linux-hardware.org/?probe=cbbd1d3e3e) | Jan 28, 2023 |
| Dell          | XPS 13 9305                 | [684b829dbb](https://linux-hardware.org/?probe=684b829dbb) | Jan 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ce2955973a](https://linux-hardware.org/?probe=ce2955973a) | Jan 27, 2023 |
| System76      | Lemur Pro                   | [40c5731c48](https://linux-hardware.org/?probe=40c5731c48) | Jan 27, 2023 |
| Clevo         | W150HNM/W170HN              | [63709a14ca](https://linux-hardware.org/?probe=63709a14ca) | Jan 27, 2023 |
| Dell          | Latitude E7240              | [d88cdedff3](https://linux-hardware.org/?probe=d88cdedff3) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [df04ffbd50](https://linux-hardware.org/?probe=df04ffbd50) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [b2ffc58bb1](https://linux-hardware.org/?probe=b2ffc58bb1) | Jan 26, 2023 |
| Dell          | G3 3590                     | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| System76      | Lemur Pro                   | [097cd4c9f8](https://linux-hardware.org/?probe=097cd4c9f8) | Jan 26, 2023 |
| Gigabyte      | A5 K1                       | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| HP            | ProBook 6550b               | [c7983e417c](https://linux-hardware.org/?probe=c7983e417c) | Jan 25, 2023 |
| Timi          | RedmiBook Pro 15S           | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [bc56140257](https://linux-hardware.org/?probe=bc56140257) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | [f201c986f0](https://linux-hardware.org/?probe=f201c986f0) | Jan 25, 2023 |
| Dell          | Inspiron 13-7353            | [5ebcba8c52](https://linux-hardware.org/?probe=5ebcba8c52) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| Dell          | System Inspiron N7110       | [935a295b28](https://linux-hardware.org/?probe=935a295b28) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| Acer          | Swift SFA16-41              | [1c05334105](https://linux-hardware.org/?probe=1c05334105) | Jan 24, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | [73a0023203](https://linux-hardware.org/?probe=73a0023203) | Jan 24, 2023 |
| Google        | Link                        | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [f6e09cc9fb](https://linux-hardware.org/?probe=f6e09cc9fb) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [306e6ae925](https://linux-hardware.org/?probe=306e6ae925) | Jan 23, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [821e7b4330](https://linux-hardware.org/?probe=821e7b4330) | Jan 22, 2023 |
| Purism        | Librem 15 v3                | [fcb1d44df6](https://linux-hardware.org/?probe=fcb1d44df6) | Jan 22, 2023 |
| Dell          | Latitude E5470              | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| HP            | Notebook                    | [57bf6826ef](https://linux-hardware.org/?probe=57bf6826ef) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| Dell          | XPS 13 9350                 | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [22d9f43ef5](https://linux-hardware.org/?probe=22d9f43ef5) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Dell          | Latitude 5300               | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | [1da6722b35](https://linux-hardware.org/?probe=1da6722b35) | Jan 21, 2023 |
| Dell          | Inspiron 5505               | [9a17165647](https://linux-hardware.org/?probe=9a17165647) | Jan 20, 2023 |
| Dell          | Inspiron 5505               | [e1003a85c9](https://linux-hardware.org/?probe=e1003a85c9) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Dell          | Latitude E7240              | [a4e01b187f](https://linux-hardware.org/?probe=a4e01b187f) | Jan 20, 2023 |
| HP            | Laptop 15-bw0xx             | [0bf7ea6726](https://linux-hardware.org/?probe=0bf7ea6726) | Jan 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c1169d55de](https://linux-hardware.org/?probe=c1169d55de) | Jan 19, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | [641654df50](https://linux-hardware.org/?probe=641654df50) | Jan 19, 2023 |
| Dell          | Latitude E7240              | [475187029d](https://linux-hardware.org/?probe=475187029d) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [edc36777f0](https://linux-hardware.org/?probe=edc36777f0) | Jan 19, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [b318baed4f](https://linux-hardware.org/?probe=b318baed4f) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| Razer         | Blade                       | [b3f154ac11](https://linux-hardware.org/?probe=b3f154ac11) | Jan 19, 2023 |
| Dell          | G5 5590                     | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude E6540              | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | [933f67b6b5](https://linux-hardware.org/?probe=933f67b6b5) | Jan 18, 2023 |
| Dell          | Precision 7670              | [5c70243651](https://linux-hardware.org/?probe=5c70243651) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | [48a56bd8c2](https://linux-hardware.org/?probe=48a56bd8c2) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [ac28c1fba4](https://linux-hardware.org/?probe=ac28c1fba4) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [45e2d0fb2d](https://linux-hardware.org/?probe=45e2d0fb2d) | Jan 18, 2023 |
| Dell          | Latitude E5440              | [eb945eac4e](https://linux-hardware.org/?probe=eb945eac4e) | Jan 18, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [8bf0f8c8fe](https://linux-hardware.org/?probe=8bf0f8c8fe) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [18d3c84771](https://linux-hardware.org/?probe=18d3c84771) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [bd0bc47120](https://linux-hardware.org/?probe=bd0bc47120) | Jan 17, 2023 |
| Framework     | Laptop                      | [e94774a411](https://linux-hardware.org/?probe=e94774a411) | Jan 17, 2023 |
| Acer          | Aspire 5625G                | [244d8473fc](https://linux-hardware.org/?probe=244d8473fc) | Jan 16, 2023 |
| Dell          | Latitude E7240              | [dc47f005d6](https://linux-hardware.org/?probe=dc47f005d6) | Jan 16, 2023 |
| Lenovo        | IdeaPad Y570 0862           | [8c43e56714](https://linux-hardware.org/?probe=8c43e56714) | Jan 16, 2023 |
| Chuwi         | GemiBook Pro                | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| System76      | Lemur Pro                   | [fde9d32359](https://linux-hardware.org/?probe=fde9d32359) | Jan 16, 2023 |
| Apple         | MacBook8,1                  | [64b089dfb7](https://linux-hardware.org/?probe=64b089dfb7) | Jan 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [db57593b81](https://linux-hardware.org/?probe=db57593b81) | Jan 14, 2023 |
| MSI           | Bravo 15 B5DD               | [ffb8653d34](https://linux-hardware.org/?probe=ffb8653d34) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [76f54ae84c](https://linux-hardware.org/?probe=76f54ae84c) | Jan 14, 2023 |
| Dell          | Precision 3571              | [c71e32c6ea](https://linux-hardware.org/?probe=c71e32c6ea) | Jan 14, 2023 |
| Acer          | Predator PT315-52           | [149941b52c](https://linux-hardware.org/?probe=149941b52c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [9eed89d744](https://linux-hardware.org/?probe=9eed89d744) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| System76      | Oryx Pro                    | [da1374fa1c](https://linux-hardware.org/?probe=da1374fa1c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [ed7ff7569c](https://linux-hardware.org/?probe=ed7ff7569c) | Jan 14, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [2860788f11](https://linux-hardware.org/?probe=2860788f11) | Jan 14, 2023 |
| HONOR         | NMH-WCX9                    | [10a9c33aed](https://linux-hardware.org/?probe=10a9c33aed) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Dell          | Latitude 5300               | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | [96a079dbf8](https://linux-hardware.org/?probe=96a079dbf8) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | [53b39e47e9](https://linux-hardware.org/?probe=53b39e47e9) | Jan 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS2BM00    | [afefa18c04](https://linux-hardware.org/?probe=afefa18c04) | Jan 12, 2023 |
| HP            | Dev One Notebook PC         | [f7304c0af2](https://linux-hardware.org/?probe=f7304c0af2) | Jan 12, 2023 |
| Samsung       | 270E5J/2570EJ               | [22f9a03d68](https://linux-hardware.org/?probe=22f9a03d68) | Jan 12, 2023 |
| HP            | EliteBook 840 G5            | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| Dell          | Latitude E7240              | [93d832d08f](https://linux-hardware.org/?probe=93d832d08f) | Jan 11, 2023 |
| Lenovo        | IdeaPad Y570 20091          | [3538dd1b8a](https://linux-hardware.org/?probe=3538dd1b8a) | Jan 11, 2023 |
| Acer          | TravelMate P245-M           | [1722e41c8d](https://linux-hardware.org/?probe=1722e41c8d) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [0f1f6b2662](https://linux-hardware.org/?probe=0f1f6b2662) | Jan 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a2363c6939](https://linux-hardware.org/?probe=a2363c6939) | Jan 11, 2023 |
| Acer          | Swift SF314-56              | [456445a93c](https://linux-hardware.org/?probe=456445a93c) | Jan 10, 2023 |
| Dell          | Latitude E7240              | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| HP            | EliteBook 840 G5            | [0eb6418a53](https://linux-hardware.org/?probe=0eb6418a53) | Jan 10, 2023 |
| HP            | OMEN by Laptop              | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| Razer x La... | TensorBook (late 2021)      | [d798473e75](https://linux-hardware.org/?probe=d798473e75) | Jan 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e384aea51e](https://linux-hardware.org/?probe=e384aea51e) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1829eed17a](https://linux-hardware.org/?probe=1829eed17a) | Jan 09, 2023 |
| Dell          | Latitude E7240              | [c191d76ac2](https://linux-hardware.org/?probe=c191d76ac2) | Jan 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [07cc23f1cd](https://linux-hardware.org/?probe=07cc23f1cd) | Jan 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d784655474](https://linux-hardware.org/?probe=d784655474) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [7e17526b20](https://linux-hardware.org/?probe=7e17526b20) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [698649c9ae](https://linux-hardware.org/?probe=698649c9ae) | Jan 08, 2023 |
| Dell          | Latitude E7240              | [c7cf2afdd9](https://linux-hardware.org/?probe=c7cf2afdd9) | Jan 07, 2023 |
| HP            | ENVY dv6                    | [2a01900cb1](https://linux-hardware.org/?probe=2a01900cb1) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [f191d63ace](https://linux-hardware.org/?probe=f191d63ace) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [7018e90a09](https://linux-hardware.org/?probe=7018e90a09) | Jan 07, 2023 |
| System76      | Bonobo WS                   | [afb9abd3c6](https://linux-hardware.org/?probe=afb9abd3c6) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [d4dc080444](https://linux-hardware.org/?probe=d4dc080444) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [ab9f1d1812](https://linux-hardware.org/?probe=ab9f1d1812) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [bf425a41f8](https://linux-hardware.org/?probe=bf425a41f8) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | [63bc1e725c](https://linux-hardware.org/?probe=63bc1e725c) | Jan 07, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Dell          | Latitude 7520               | [f4f253a52b](https://linux-hardware.org/?probe=f4f253a52b) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| Dell          | Precision M4700             | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| Dell          | Latitude E7240              | [b00208bba7](https://linux-hardware.org/?probe=b00208bba7) | Jan 06, 2023 |
| Dell          | Latitude E7240              | [6eae9dc932](https://linux-hardware.org/?probe=6eae9dc932) | Jan 05, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [7acb37a2f5](https://linux-hardware.org/?probe=7acb37a2f5) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | [1178b43f82](https://linux-hardware.org/?probe=1178b43f82) | Jan 05, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | [4f54cd1f61](https://linux-hardware.org/?probe=4f54cd1f61) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | [0393900e99](https://linux-hardware.org/?probe=0393900e99) | Jan 05, 2023 |
| System76      | Gazelle                     | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Datto         | Unknown                     | [e8c9c2e91f](https://linux-hardware.org/?probe=e8c9c2e91f) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [f6d1d35842](https://linux-hardware.org/?probe=f6d1d35842) | Jan 02, 2023 |
| Panasonic     | FZ55-1                      | [b09d64c936](https://linux-hardware.org/?probe=b09d64c936) | Jan 02, 2023 |
| Fujitsu       | FMVNS6C3                    | [49d8591166](https://linux-hardware.org/?probe=49d8591166) | Jan 02, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [1490ccc480](https://linux-hardware.org/?probe=1490ccc480) | Jan 02, 2023 |
| Dell          | Latitude E7240              | [ccf48432e0](https://linux-hardware.org/?probe=ccf48432e0) | Jan 02, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [5e52308407](https://linux-hardware.org/?probe=5e52308407) | Jan 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d841c27fe1](https://linux-hardware.org/?probe=d841c27fe1) | Jan 02, 2023 |
| ASUSTek       | UX310UQK                    | [79baf6f82a](https://linux-hardware.org/?probe=79baf6f82a) | Jan 01, 2023 |
| Dell          | Latitude E7270              | [09f72d101d](https://linux-hardware.org/?probe=09f72d101d) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [28342f1b5c](https://linux-hardware.org/?probe=28342f1b5c) | Jan 01, 2023 |
| HP            | ZBook 15 G3                 | [a53517f382](https://linux-hardware.org/?probe=a53517f382) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [4ef3eb6975](https://linux-hardware.org/?probe=4ef3eb6975) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| HP            | EliteBook 8740w (WH274UT... | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| MSI           | GE60 2OC\2OE                | [c307379c36](https://linux-hardware.org/?probe=c307379c36) | Dec 30, 2022 |
| Dell          | G3 3500                     | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Lenovo        | Z50-70 20354                | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| Apple         | MacBookPro7,1               | [db4379ed1e](https://linux-hardware.org/?probe=db4379ed1e) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Dell          | Latitude E7240              | [5f83c8f4ad](https://linux-hardware.org/?probe=5f83c8f4ad) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [d048930c78](https://linux-hardware.org/?probe=d048930c78) | Dec 30, 2022 |
| Dell          | G5 5590                     | [dada63bf04](https://linux-hardware.org/?probe=dada63bf04) | Dec 30, 2022 |
| HP            | Pavilion 15                 | [956866bbdd](https://linux-hardware.org/?probe=956866bbdd) | Dec 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| Lenovo        | ThinkPad W510 4389W14       | [c83a9ac8a9](https://linux-hardware.org/?probe=c83a9ac8a9) | Dec 29, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [467a749806](https://linux-hardware.org/?probe=467a749806) | Dec 29, 2022 |
| System76      | Lemur Pro                   | [0a61e4fe8d](https://linux-hardware.org/?probe=0a61e4fe8d) | Dec 29, 2022 |
| HP            | ENVY dv7                    | [97e029af78](https://linux-hardware.org/?probe=97e029af78) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [2bd4899c8a](https://linux-hardware.org/?probe=2bd4899c8a) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [919cfc2c9c](https://linux-hardware.org/?probe=919cfc2c9c) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| ASUSTek       | P453UA                      | [0bf89f0f8f](https://linux-hardware.org/?probe=0bf89f0f8f) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Alienware     | M11x R2                     | [a0da72bec0](https://linux-hardware.org/?probe=a0da72bec0) | Dec 28, 2022 |
| Dell          | Inspiron 5505               | [ba2d75cfa7](https://linux-hardware.org/?probe=ba2d75cfa7) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| HUAWEI        | HVY-WXX9                    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Apple         | MacBookPro8,2               | [e4255e8ed7](https://linux-hardware.org/?probe=e4255e8ed7) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [470c8d54ba](https://linux-hardware.org/?probe=470c8d54ba) | Dec 27, 2022 |
| Apple         | MacBookPro8,2               | [c62b37d15c](https://linux-hardware.org/?probe=c62b37d15c) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [c0a659dbb1](https://linux-hardware.org/?probe=c0a659dbb1) | Dec 27, 2022 |
| Dell          | XPS 15 9500                 | [d1d8257c05](https://linux-hardware.org/?probe=d1d8257c05) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| HP            | Pavilion dv6                | [d759125511](https://linux-hardware.org/?probe=d759125511) | Dec 26, 2022 |
| Acer          | Swift SF314-511             | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| Apple         | MacBookPro14,1              | [eb6c6ee49e](https://linux-hardware.org/?probe=eb6c6ee49e) | Dec 26, 2022 |
| ASUSTek       | N550JV                      | [748284a21e](https://linux-hardware.org/?probe=748284a21e) | Dec 26, 2022 |
| Dell          | XPS 13 9360                 | [bddcc1503f](https://linux-hardware.org/?probe=bddcc1503f) | Dec 26, 2022 |
| Acer          | Aspire A114-32              | [593969da1f](https://linux-hardware.org/?probe=593969da1f) | Dec 26, 2022 |
| Avell High... | C62 MOB                     | [658f34e70d](https://linux-hardware.org/?probe=658f34e70d) | Dec 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [46687a6be3](https://linux-hardware.org/?probe=46687a6be3) | Dec 26, 2022 |
| Sony          | SVF15213CBB                 | [f8a95f249c](https://linux-hardware.org/?probe=f8a95f249c) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| GPD           | G1621-02                    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [576fb3852f](https://linux-hardware.org/?probe=576fb3852f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| HP            | 255 G8 Notebook PC          | [3f72d88324](https://linux-hardware.org/?probe=3f72d88324) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [de111c3be5](https://linux-hardware.org/?probe=de111c3be5) | Dec 24, 2022 |
| HP            | EliteBook 865 16 inch G9... | [857cb922f9](https://linux-hardware.org/?probe=857cb922f9) | Dec 24, 2022 |
| Dell          | Latitude E7470              | [8e6bdc1809](https://linux-hardware.org/?probe=8e6bdc1809) | Dec 24, 2022 |
| System76      | Pangolin                    | [2ee273cbcf](https://linux-hardware.org/?probe=2ee273cbcf) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [214b2a3235](https://linux-hardware.org/?probe=214b2a3235) | Dec 23, 2022 |
| HP            | Laptop 14s-dk0xxx           | [53aa474cf5](https://linux-hardware.org/?probe=53aa474cf5) | Dec 23, 2022 |
| Timi          | TM1703                      | [5e25655f36](https://linux-hardware.org/?probe=5e25655f36) | Dec 23, 2022 |
| Toshiba       | Satellite Pro C50-A-1MX     | [78487975ce](https://linux-hardware.org/?probe=78487975ce) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [918223cece](https://linux-hardware.org/?probe=918223cece) | Dec 23, 2022 |
| Medion        | X6816                       | [bafbf1ea90](https://linux-hardware.org/?probe=bafbf1ea90) | Dec 23, 2022 |
| Medion        | X6816                       | [ac9627e5d4](https://linux-hardware.org/?probe=ac9627e5d4) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [7bd2309063](https://linux-hardware.org/?probe=7bd2309063) | Dec 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d7b8ef01e2](https://linux-hardware.org/?probe=d7b8ef01e2) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [db7dc4fa25](https://linux-hardware.org/?probe=db7dc4fa25) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [e8ac233c29](https://linux-hardware.org/?probe=e8ac233c29) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [341becfd8a](https://linux-hardware.org/?probe=341becfd8a) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ad4be7f0fa](https://linux-hardware.org/?probe=ad4be7f0fa) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a70ba97a7a](https://linux-hardware.org/?probe=a70ba97a7a) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [e60df2d8ba](https://linux-hardware.org/?probe=e60df2d8ba) | Dec 22, 2022 |
| Acer          | Swift SF314-512             | [505ab3f60a](https://linux-hardware.org/?probe=505ab3f60a) | Dec 22, 2022 |
| Dell          | Latitude E7240              | [d81efafde1](https://linux-hardware.org/?probe=d81efafde1) | Dec 22, 2022 |
| System76      | Lemur Pro                   | [ed549bfe74](https://linux-hardware.org/?probe=ed549bfe74) | Dec 21, 2022 |
| System76      | Lemur Pro                   | [30be17e71c](https://linux-hardware.org/?probe=30be17e71c) | Dec 21, 2022 |
| Dell          | Precision 3520              | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [0377cc3170](https://linux-hardware.org/?probe=0377cc3170) | Dec 21, 2022 |
| Dell          | Latitude E7240              | [545294a23a](https://linux-hardware.org/?probe=545294a23a) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7d5914dcb2](https://linux-hardware.org/?probe=7d5914dcb2) | Dec 21, 2022 |
| Dell          | Latitude E7240              | [a368a7be00](https://linux-hardware.org/?probe=a368a7be00) | Dec 21, 2022 |
| ASUSTek       | VivoBook S14 X411UF         | [894f0ab5df](https://linux-hardware.org/?probe=894f0ab5df) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [d5a877b2c6](https://linux-hardware.org/?probe=d5a877b2c6) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [b7999f8a61](https://linux-hardware.org/?probe=b7999f8a61) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [04b9163920](https://linux-hardware.org/?probe=04b9163920) | Dec 19, 2022 |
| Lenovo        | IdeaPad Z410 20292          | [e46710b0cf](https://linux-hardware.org/?probe=e46710b0cf) | Dec 19, 2022 |
| Dell          | Vostro 15 3510              | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
| Dell          | Inspiron 7572               | [418178c3ca](https://linux-hardware.org/?probe=418178c3ca) | Dec 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1QX0... | [76771fa0aa](https://linux-hardware.org/?probe=76771fa0aa) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | [b34ce3474d](https://linux-hardware.org/?probe=b34ce3474d) | Dec 19, 2022 |
| System76      | Gazelle                     | [da46fb926a](https://linux-hardware.org/?probe=da46fb926a) | Dec 19, 2022 |
| Dell          | Inspiron 15-3567            | [f58039213b](https://linux-hardware.org/?probe=f58039213b) | Dec 18, 2022 |
| GPU Compan... | GWNR71517                   | [e680612eb4](https://linux-hardware.org/?probe=e680612eb4) | Dec 18, 2022 |
| Lenovo        | ThinkPad Edge E430 62718... | [92fede3d5a](https://linux-hardware.org/?probe=92fede3d5a) | Dec 18, 2022 |
| Avell High... | B.ON                        | [9661ece374](https://linux-hardware.org/?probe=9661ece374) | Dec 17, 2022 |
| Dell          | XPS 15 9510                 | [1641d91910](https://linux-hardware.org/?probe=1641d91910) | Dec 17, 2022 |
| Dell          | Inspiron 5458               | [8ed4687f2f](https://linux-hardware.org/?probe=8ed4687f2f) | Dec 16, 2022 |
| System76      | Gazelle                     | [b5ef8cec53](https://linux-hardware.org/?probe=b5ef8cec53) | Dec 16, 2022 |
| Acer          | Aspire V5-571G              | [575a61802b](https://linux-hardware.org/?probe=575a61802b) | Dec 16, 2022 |
| Dell          | Latitude 3310               | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [544e464dab](https://linux-hardware.org/?probe=544e464dab) | Dec 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [18d67ba2ab](https://linux-hardware.org/?probe=18d67ba2ab) | Dec 15, 2022 |
| ALLDOCUBE     | i1405C                      | [10d8101488](https://linux-hardware.org/?probe=10d8101488) | Dec 15, 2022 |
| Fujitsu       | FMVNS6C3                    | [d7a6961431](https://linux-hardware.org/?probe=d7a6961431) | Dec 15, 2022 |
| Apple         | MacBookPro10,1              | [a22dd35e04](https://linux-hardware.org/?probe=a22dd35e04) | Dec 14, 2022 |
| Apple         | MacBookPro11,3              | [d0c2bf600a](https://linux-hardware.org/?probe=d0c2bf600a) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Lenovo        | G505 20240                  | [e6777c2fbc](https://linux-hardware.org/?probe=e6777c2fbc) | Dec 13, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| Lenovo        | ThinkPad T530 23943J8       | [e5d69d9f81](https://linux-hardware.org/?probe=e5d69d9f81) | Dec 13, 2022 |
| Apple         | MacBookPro9,2               | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| Toshiba       | Satellite C55-C             | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| System76      | Gazelle                     | [8498636db6](https://linux-hardware.org/?probe=8498636db6) | Dec 12, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [d438f3f50a](https://linux-hardware.org/?probe=d438f3f50a) | Dec 12, 2022 |
| Apple         | MacBookPro13,3              | [10b29f88c5](https://linux-hardware.org/?probe=10b29f88c5) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | [7ffd00681b](https://linux-hardware.org/?probe=7ffd00681b) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6de2a0ad33](https://linux-hardware.org/?probe=6de2a0ad33) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| Dell          | Latitude E7240              | [d6dddd9632](https://linux-hardware.org/?probe=d6dddd9632) | Dec 11, 2022 |
| Acer          | Aspire A515-44G             | [b85a211b25](https://linux-hardware.org/?probe=b85a211b25) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| System76      | Gazelle                     | [8b0297b19e](https://linux-hardware.org/?probe=8b0297b19e) | Dec 11, 2022 |
| Lenovo        | G470 20078                  | [65264ef208](https://linux-hardware.org/?probe=65264ef208) | Dec 11, 2022 |
| Fujitsu       | FMVNS6C3                    | [2cdacbc923](https://linux-hardware.org/?probe=2cdacbc923) | Dec 11, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [040652df3d](https://linux-hardware.org/?probe=040652df3d) | Dec 10, 2022 |
| Lenovo        | G470 20078                  | [ea75ebf831](https://linux-hardware.org/?probe=ea75ebf831) | Dec 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2dc32e31b3](https://linux-hardware.org/?probe=2dc32e31b3) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [e8fe4392be](https://linux-hardware.org/?probe=e8fe4392be) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [cf32d7158c](https://linux-hardware.org/?probe=cf32d7158c) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | [ef20df1d4f](https://linux-hardware.org/?probe=ef20df1d4f) | Dec 09, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [8ce314db56](https://linux-hardware.org/?probe=8ce314db56) | Dec 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [858f06f0e5](https://linux-hardware.org/?probe=858f06f0e5) | Dec 08, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [30cc472125](https://linux-hardware.org/?probe=30cc472125) | Dec 08, 2022 |
| Acer          | TravelMate P214-41-G2       | [cb52e49fa2](https://linux-hardware.org/?probe=cb52e49fa2) | Dec 08, 2022 |
| Dell          | G15 5515                    | [861bd0cabf](https://linux-hardware.org/?probe=861bd0cabf) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [ca25d43c56](https://linux-hardware.org/?probe=ca25d43c56) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [104e0e02d1](https://linux-hardware.org/?probe=104e0e02d1) | Dec 08, 2022 |
| LG Electro... | 16Z90P-K.AA78A1             | [1646f1763d](https://linux-hardware.org/?probe=1646f1763d) | Dec 08, 2022 |
| Avell High... | A62 LIV                     | [a4f96694c4](https://linux-hardware.org/?probe=a4f96694c4) | Dec 07, 2022 |
| Acer          | Aspire A515-45              | [7eebb7f601](https://linux-hardware.org/?probe=7eebb7f601) | Dec 07, 2022 |
| Dell          | Latitude E7240              | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| HP            | ENVY 17                     | [a19d90a89f](https://linux-hardware.org/?probe=a19d90a89f) | Dec 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Dell          | Inspiron 1750               | [e369c14198](https://linux-hardware.org/?probe=e369c14198) | Dec 07, 2022 |
| Lenovo        | IdeaPad Y560                | [64abd8c6fe](https://linux-hardware.org/?probe=64abd8c6fe) | Dec 06, 2022 |
| Fujitsu       | FMVNS6C3                    | [5b60c9dfd0](https://linux-hardware.org/?probe=5b60c9dfd0) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [05f4b7d7cf](https://linux-hardware.org/?probe=05f4b7d7cf) | Dec 06, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [86cd634760](https://linux-hardware.org/?probe=86cd634760) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [6f0ceb7a46](https://linux-hardware.org/?probe=6f0ceb7a46) | Dec 05, 2022 |
| Dell          | G5 5505                     | [f19a76c344](https://linux-hardware.org/?probe=f19a76c344) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | UL50VT                      | [ff4edb7010](https://linux-hardware.org/?probe=ff4edb7010) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [f602f6c0bc](https://linux-hardware.org/?probe=f602f6c0bc) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [de39c86a4c](https://linux-hardware.org/?probe=de39c86a4c) | Dec 05, 2022 |
| System76      | Gazelle                     | [deb2c9b6c9](https://linux-hardware.org/?probe=deb2c9b6c9) | Dec 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7687bdc111](https://linux-hardware.org/?probe=7687bdc111) | Dec 04, 2022 |
| Acer          | Nitro AN515-54              | [33f26cca4f](https://linux-hardware.org/?probe=33f26cca4f) | Dec 04, 2022 |
| HP            | Notebook                    | [610cea9ebc](https://linux-hardware.org/?probe=610cea9ebc) | Dec 04, 2022 |
| Dell          | Latitude E7240              | [6f34110d45](https://linux-hardware.org/?probe=6f34110d45) | Dec 04, 2022 |
| Unknown       | Unknown                     | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| Unknown       | Unknown                     | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| HP            | EliteBook 820 G3            | [6913ec89c8](https://linux-hardware.org/?probe=6913ec89c8) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4f36906529](https://linux-hardware.org/?probe=4f36906529) | Dec 02, 2022 |
| HP            | ProBook 450 G7 HP NOTEBO... | [2fe5c76c3c](https://linux-hardware.org/?probe=2fe5c76c3c) | Dec 02, 2022 |
| HP            | Notebook                    | [4184c8fa06](https://linux-hardware.org/?probe=4184c8fa06) | Dec 02, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [9c5bc7ca10](https://linux-hardware.org/?probe=9c5bc7ca10) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [562e1f4b92](https://linux-hardware.org/?probe=562e1f4b92) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c8ef49d294](https://linux-hardware.org/?probe=c8ef49d294) | Dec 01, 2022 |
| HP            | Pavilion dv7                | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [62ae8cb7dc](https://linux-hardware.org/?probe=62ae8cb7dc) | Dec 01, 2022 |
| Dell          | Inspiron 13-5378            | [9d25b2f6e0](https://linux-hardware.org/?probe=9d25b2f6e0) | Dec 01, 2022 |
| Dell          | XPS 13 9310                 | [aadf1c39a0](https://linux-hardware.org/?probe=aadf1c39a0) | Dec 01, 2022 |
| Google        | Cyan                        | [4aa7125981](https://linux-hardware.org/?probe=4aa7125981) | Nov 30, 2022 |
| HP            | ZBook 14 G2                 | [b2bba919b2](https://linux-hardware.org/?probe=b2bba919b2) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [66b6e49eb5](https://linux-hardware.org/?probe=66b6e49eb5) | Nov 30, 2022 |
| Acer          | Nitro AN515-43              | [b315e85bda](https://linux-hardware.org/?probe=b315e85bda) | Nov 30, 2022 |
| MSI           | Modern 14 B5M               | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [53ee9a8fb9](https://linux-hardware.org/?probe=53ee9a8fb9) | Nov 30, 2022 |
| HP            | Laptop 14-dq1xxx            | [b12534f13d](https://linux-hardware.org/?probe=b12534f13d) | Nov 30, 2022 |
| Dell          | Latitude E7240              | [8b0b984870](https://linux-hardware.org/?probe=8b0b984870) | Nov 29, 2022 |
| HP            | ProBook 450 G8              | [eec30c7857](https://linux-hardware.org/?probe=eec30c7857) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [e9932df850](https://linux-hardware.org/?probe=e9932df850) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [179ff76e75](https://linux-hardware.org/?probe=179ff76e75) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Dell          | Latitude 5411               | [122facad78](https://linux-hardware.org/?probe=122facad78) | Nov 28, 2022 |
| HP            | Pavilion dv7                | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | [c0c2f77cdb](https://linux-hardware.org/?probe=c0c2f77cdb) | Nov 28, 2022 |
| Lenovo        | IdeaPad Y560                | [4918810cd1](https://linux-hardware.org/?probe=4918810cd1) | Nov 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [16705fe86c](https://linux-hardware.org/?probe=16705fe86c) | Nov 28, 2022 |
| Dell          | Inspiron 15 5510            | [5ec5306c0f](https://linux-hardware.org/?probe=5ec5306c0f) | Nov 28, 2022 |
| Clevo         | W55xEU                      | [5ed799ba64](https://linux-hardware.org/?probe=5ed799ba64) | Nov 28, 2022 |
| MSI           | GP72 7RDX                   | [648eb6d88a](https://linux-hardware.org/?probe=648eb6d88a) | Nov 28, 2022 |
| Acer          | Aspire A515-57              | [984e01118e](https://linux-hardware.org/?probe=984e01118e) | Nov 28, 2022 |
| HP            | Laptop 14-fq1xxx            | [7837242848](https://linux-hardware.org/?probe=7837242848) | Nov 27, 2022 |
| Toshiba       | Satellite L775D             | [bf6fc6fd49](https://linux-hardware.org/?probe=bf6fc6fd49) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [f3536b80de](https://linux-hardware.org/?probe=f3536b80de) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [dbaae2beb7](https://linux-hardware.org/?probe=dbaae2beb7) | Nov 27, 2022 |
| Apple         | MacBookPro6,2               | [409c3edc19](https://linux-hardware.org/?probe=409c3edc19) | Nov 27, 2022 |
| Alienware     | 17                          | [08ebf1e9a2](https://linux-hardware.org/?probe=08ebf1e9a2) | Nov 27, 2022 |
| HP            | Laptop 14-fq1xxx            | [49dc64dc76](https://linux-hardware.org/?probe=49dc64dc76) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Dell          | Inspiron 3521               | [015854e59a](https://linux-hardware.org/?probe=015854e59a) | Nov 26, 2022 |
| HP            | ZBook 15                    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [e784cdc15d](https://linux-hardware.org/?probe=e784cdc15d) | Nov 26, 2022 |
| Gigabyte      | AORUS 5 SE                  | [d9e1ceb3c1](https://linux-hardware.org/?probe=d9e1ceb3c1) | Nov 26, 2022 |
| HUAWEI        | MRGF-XX                     | [f60090b407](https://linux-hardware.org/?probe=f60090b407) | Nov 26, 2022 |
| Apple         | MacBookPro7,1               | [8268fc2c12](https://linux-hardware.org/?probe=8268fc2c12) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [32ab0a36a4](https://linux-hardware.org/?probe=32ab0a36a4) | Nov 25, 2022 |
| Acer          | Aspire A315-54              | [b7269b7617](https://linux-hardware.org/?probe=b7269b7617) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [770e9d413e](https://linux-hardware.org/?probe=770e9d413e) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f0bebe7a20](https://linux-hardware.org/?probe=f0bebe7a20) | Nov 24, 2022 |
| Dell          | Inspiron 7720               | [a75b9a21f9](https://linux-hardware.org/?probe=a75b9a21f9) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Dell          | Inspiron 7720               | [ae4fc56cb3](https://linux-hardware.org/?probe=ae4fc56cb3) | Nov 23, 2022 |
| Lenovo        | IdeaPad Y560                | [154702cbc6](https://linux-hardware.org/?probe=154702cbc6) | Nov 23, 2022 |
| Dell          | XPS 15 7590                 | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| HP            | G62                         | [754a471519](https://linux-hardware.org/?probe=754a471519) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Dell          | Latitude E7470              | [03725ebee3](https://linux-hardware.org/?probe=03725ebee3) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [4692ce22fb](https://linux-hardware.org/?probe=4692ce22fb) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [cb82f6d418](https://linux-hardware.org/?probe=cb82f6d418) | Nov 22, 2022 |
| Dell          | Latitude E6540              | [9a3ff03cbb](https://linux-hardware.org/?probe=9a3ff03cbb) | Nov 22, 2022 |
| Gigabyte      | AORUS 5 SE                  | [c88614e7f3](https://linux-hardware.org/?probe=c88614e7f3) | Nov 22, 2022 |
| MSI           | Katana GF76 11UG            | [e29dda268c](https://linux-hardware.org/?probe=e29dda268c) | Nov 21, 2022 |
| MSI           | Katana GF76 11UG            | [9627a23b1f](https://linux-hardware.org/?probe=9627a23b1f) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [b0b972f8ef](https://linux-hardware.org/?probe=b0b972f8ef) | Nov 21, 2022 |
| Dell          | Precision 7670              | [93f14c8b55](https://linux-hardware.org/?probe=93f14c8b55) | Nov 21, 2022 |
| Alienware     | 17                          | [16b37ce649](https://linux-hardware.org/?probe=16b37ce649) | Nov 21, 2022 |
| Acer          | Swift SF314-42              | [5ec428f8b3](https://linux-hardware.org/?probe=5ec428f8b3) | Nov 21, 2022 |
| Unknown       | Unknown                     | [5a06cde126](https://linux-hardware.org/?probe=5a06cde126) | Nov 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [6355251bd6](https://linux-hardware.org/?probe=6355251bd6) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [18f301f8c5](https://linux-hardware.org/?probe=18f301f8c5) | Nov 20, 2022 |
| Dell          | Vostro 3458                 | [9f05e54f99](https://linux-hardware.org/?probe=9f05e54f99) | Nov 20, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [cba7abe277](https://linux-hardware.org/?probe=cba7abe277) | Nov 20, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | [6eb57e34de](https://linux-hardware.org/?probe=6eb57e34de) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d4bb2f3867](https://linux-hardware.org/?probe=d4bb2f3867) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| HP            | ProBook 6450b               | [10c8ec5d4c](https://linux-hardware.org/?probe=10c8ec5d4c) | Nov 19, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [41ffb4e75f](https://linux-hardware.org/?probe=41ffb4e75f) | Nov 19, 2022 |
| Dell          | XPS 13 9360                 | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Valve         | Jupiter                     | [afdcde154a](https://linux-hardware.org/?probe=afdcde154a) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [ceac47decc](https://linux-hardware.org/?probe=ceac47decc) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [5abeec1752](https://linux-hardware.org/?probe=5abeec1752) | Nov 18, 2022 |
| Dell          | Precision M4400             | [715efc61ae](https://linux-hardware.org/?probe=715efc61ae) | Nov 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [8f4df3bbda](https://linux-hardware.org/?probe=8f4df3bbda) | Nov 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [dee1a4e29e](https://linux-hardware.org/?probe=dee1a4e29e) | Nov 17, 2022 |
| Lenovo        | ThinkPad T550 20CJS18S00    | [ba94994594](https://linux-hardware.org/?probe=ba94994594) | Nov 17, 2022 |
| Dell          | G15 5515                    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Toshiba       | Satellite L500              | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [5c49c7037b](https://linux-hardware.org/?probe=5c49c7037b) | Nov 16, 2022 |
| Razer x La... | TensorBook (late 2021)      | [b7fff356a7](https://linux-hardware.org/?probe=b7fff356a7) | Nov 16, 2022 |
| HP            | ZBook 14 G2                 | [8ce9402aad](https://linux-hardware.org/?probe=8ce9402aad) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| Acer          | Aspire A114-32              | [5a76aee400](https://linux-hardware.org/?probe=5a76aee400) | Nov 16, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1f2e05b205](https://linux-hardware.org/?probe=1f2e05b205) | Nov 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [809e86d562](https://linux-hardware.org/?probe=809e86d562) | Nov 15, 2022 |
| Acer          | Swift SF314-43              | [bc5218c5da](https://linux-hardware.org/?probe=bc5218c5da) | Nov 15, 2022 |
| OEGStone      | NOTCHA-322                  | [a5f28e095e](https://linux-hardware.org/?probe=a5f28e095e) | Nov 15, 2022 |
| System76      | Oryx Pro                    | [3ea0d459e1](https://linux-hardware.org/?probe=3ea0d459e1) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [426dec8739](https://linux-hardware.org/?probe=426dec8739) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [f55f35c2fe](https://linux-hardware.org/?probe=f55f35c2fe) | Nov 15, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [0d39dde901](https://linux-hardware.org/?probe=0d39dde901) | Nov 14, 2022 |
| Dell          | Inspiron 7560               | [45474958e5](https://linux-hardware.org/?probe=45474958e5) | Nov 14, 2022 |
| Dell          | Inspiron 15 3511            | [43214de971](https://linux-hardware.org/?probe=43214de971) | Nov 13, 2022 |
| Timi          | TM1613                      | [d038ff5636](https://linux-hardware.org/?probe=d038ff5636) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | [25b89592e0](https://linux-hardware.org/?probe=25b89592e0) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | [1e4f22395f](https://linux-hardware.org/?probe=1e4f22395f) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | [7325cce71f](https://linux-hardware.org/?probe=7325cce71f) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | [86b0a359fa](https://linux-hardware.org/?probe=86b0a359fa) | Nov 13, 2022 |
| Apple         | MacBookPro10,1              | [d433817b4f](https://linux-hardware.org/?probe=d433817b4f) | Nov 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3e75f5aa87](https://linux-hardware.org/?probe=3e75f5aa87) | Nov 12, 2022 |
| Dell          | Latitude E7270              | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Apple         | MacBookAir6,2               | [c6b54c443e](https://linux-hardware.org/?probe=c6b54c443e) | Nov 12, 2022 |
| Google        | Shyvana                     | [2df69a0782](https://linux-hardware.org/?probe=2df69a0782) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [aec286073d](https://linux-hardware.org/?probe=aec286073d) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [3884507df6](https://linux-hardware.org/?probe=3884507df6) | Nov 11, 2022 |
| Dell          | Precision M4700             | [4fc304d429](https://linux-hardware.org/?probe=4fc304d429) | Nov 11, 2022 |
| HP            | EliteBook 840 G1            | [4ed347e186](https://linux-hardware.org/?probe=4ed347e186) | Nov 11, 2022 |
| System76      | Lemur Pro                   | [7df985e36a](https://linux-hardware.org/?probe=7df985e36a) | Nov 10, 2022 |
| Acer          | Aspire A114-32              | [a06fb78621](https://linux-hardware.org/?probe=a06fb78621) | Nov 10, 2022 |
| HP            | EliteBook 840 G5            | [e281a0277b](https://linux-hardware.org/?probe=e281a0277b) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| MSI           | MS-1688                     | [d8c76d2264](https://linux-hardware.org/?probe=d8c76d2264) | Nov 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [9979d8a6b6](https://linux-hardware.org/?probe=9979d8a6b6) | Nov 08, 2022 |
| Apple         | MacBookAir7,2               | [c4afe62f3b](https://linux-hardware.org/?probe=c4afe62f3b) | Nov 08, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1918990398](https://linux-hardware.org/?probe=1918990398) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [44e88f2879](https://linux-hardware.org/?probe=44e88f2879) | Nov 07, 2022 |
| HP            | ENVY NOTEBOOK PC            | [ba3abf3883](https://linux-hardware.org/?probe=ba3abf3883) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [61756efe8c](https://linux-hardware.org/?probe=61756efe8c) | Nov 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [ca4bb217ab](https://linux-hardware.org/?probe=ca4bb217ab) | Nov 07, 2022 |
| Dell          | Latitude E7240              | [2db569e056](https://linux-hardware.org/?probe=2db569e056) | Nov 06, 2022 |
| Dell          | Inspiron 1525               | [f28061e4da](https://linux-hardware.org/?probe=f28061e4da) | Nov 06, 2022 |
| Dell          | G7 7700                     | [ba3a89822a](https://linux-hardware.org/?probe=ba3a89822a) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [2a2464e0a3](https://linux-hardware.org/?probe=2a2464e0a3) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [eded2f5469](https://linux-hardware.org/?probe=eded2f5469) | Nov 06, 2022 |
| Acer          | Swift SF314-42              | [c4c5bd2515](https://linux-hardware.org/?probe=c4c5bd2515) | Nov 06, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [1f4a1244b3](https://linux-hardware.org/?probe=1f4a1244b3) | Nov 06, 2022 |
| HP            | 15 Notebook PC              | [ba76e04444](https://linux-hardware.org/?probe=ba76e04444) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1cc6297ab8](https://linux-hardware.org/?probe=1cc6297ab8) | Nov 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Acer          | Aspire 5520                 | [6e6b76588b](https://linux-hardware.org/?probe=6e6b76588b) | Nov 06, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [d10e0ce942](https://linux-hardware.org/?probe=d10e0ce942) | Nov 05, 2022 |
| System76      | Galago Pro                  | [8728b448e9](https://linux-hardware.org/?probe=8728b448e9) | Nov 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a26a719002](https://linux-hardware.org/?probe=a26a719002) | Nov 05, 2022 |
| HP            | ENVY NOTEBOOK PC            | [b0600fe299](https://linux-hardware.org/?probe=b0600fe299) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2eb5db395b](https://linux-hardware.org/?probe=2eb5db395b) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f078009dc8](https://linux-hardware.org/?probe=f078009dc8) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [58989ea140](https://linux-hardware.org/?probe=58989ea140) | Nov 04, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pop!_OS 22.04 | 1476      | 29.01%  |
| Pop!_OS 20.04 | 1150      | 22.6%   |
| Pop!_OS 21.04 | 959       | 18.85%  |
| Pop!_OS 20.10 | 856       | 16.82%  |
| Pop!_OS 21.10 | 600       | 11.79%  |
| Pop!_OS 19.10 | 30        | 0.59%   |
| Pop!_OS 18.04 | 7         | 0.14%   |
| Pop!_OS 19.04 | 6         | 0.12%   |
| Pop!_OS 18.10 | 4         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Pop!_OS | 4837      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 442       | 8.13%   |
| 5.8.0-7630-generic       | 381       | 7.01%   |
| 5.4.0-7634-generic       | 346       | 6.36%   |
| 5.19.0-76051900-generic  | 272       | 5%      |
| 5.13.0-7614-generic      | 262       | 4.82%   |
| 6.0.12-76060006-generic  | 257       | 4.73%   |
| 5.4.0-7642-generic       | 256       | 4.71%   |
| 5.17.5-76051705-generic  | 248       | 4.56%   |
| 5.8.0-7642-generic       | 242       | 4.45%   |
| 5.11.0-7614-generic      | 227       | 4.18%   |
| 5.13.0-7620-generic      | 218       | 4.01%   |
| 6.0.6-76060006-generic   | 162       | 2.98%   |
| 5.15.15-76051515-generic | 154       | 2.83%   |
| 5.16.11-76051611-generic | 138       | 2.54%   |
| 6.2.6-76060206-generic   | 129       | 2.37%   |
| 5.11.0-7612-generic      | 127       | 2.34%   |
| 5.15.5-76051505-generic  | 123       | 2.26%   |
| 5.18.10-76051810-generic | 120       | 2.21%   |
| 5.8.0-7625-generic       | 105       | 1.93%   |
| 5.17.15-76051715-generic | 105       | 1.93%   |
| 5.11.0-7633-generic      | 99        | 1.82%   |
| 5.15.8-76051508-generic  | 98        | 1.8%    |
| 5.16.19-76051619-generic | 95        | 1.75%   |
| 5.16.15-76051615-generic | 92        | 1.69%   |
| 5.4.0-7626-generic       | 84        | 1.55%   |
| 6.2.0-76060200-generic   | 73        | 1.34%   |
| 5.15.11-76051511-generic | 63        | 1.16%   |
| 6.0.2-76060002-generic   | 59        | 1.09%   |
| 5.15.23-76051523-generic | 56        | 1.03%   |
| 6.1.11-76060111-generic  | 53        | 0.97%   |
| 5.4.0-7625-generic       | 44        | 0.81%   |
| 5.4.0-7629-generic       | 35        | 0.64%   |
| 6.0.3-76060003-generic   | 23        | 0.42%   |
| 5.19.16-76051916-generic | 21        | 0.39%   |
| 5.3.0-7625-generic       | 10        | 0.18%   |
| 5.3.0-7648-generic       | 6         | 0.11%   |
| 5.11.0-051100-generic    | 6         | 0.11%   |
| 5.3.0-7642-generic       | 4         | 0.07%   |
| 5.3.0-7629-generic       | 4         | 0.07%   |
| 5.3.0-20-generic         | 4         | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 873       | 16.37%  |
| 5.4.0   | 744       | 13.95%  |
| 5.8.0   | 698       | 13.09%  |
| 5.13.0  | 467       | 8.76%   |
| 5.19.0  | 274       | 5.14%   |
| 6.0.12  | 258       | 4.84%   |
| 5.17.5  | 251       | 4.71%   |
| 6.0.6   | 162       | 3.04%   |
| 5.15.15 | 154       | 2.89%   |
| 5.16.11 | 138       | 2.59%   |
| 6.2.6   | 130       | 2.44%   |
| 5.15.5  | 123       | 2.31%   |
| 5.18.10 | 120       | 2.25%   |
| 5.17.15 | 105       | 1.97%   |
| 5.15.8  | 98        | 1.84%   |
| 5.16.19 | 95        | 1.78%   |
| 5.16.15 | 92        | 1.73%   |
| 6.2.0   | 73        | 1.37%   |
| 5.15.11 | 63        | 1.18%   |
| 6.0.2   | 60        | 1.13%   |
| 5.15.23 | 56        | 1.05%   |
| 6.1.11  | 53        | 0.99%   |
| 5.3.0   | 32        | 0.6%    |
| 6.0.3   | 23        | 0.43%   |
| 5.19.16 | 21        | 0.39%   |
| 5.0.0   | 6         | 0.11%   |
| 4.18.0  | 6         | 0.11%   |
| 5.7.0   | 4         | 0.08%   |
| 5.15.0  | 4         | 0.08%   |
| 5.8.6   | 3         | 0.06%   |
| 5.8.11  | 3         | 0.06%   |
| 5.7.1   | 3         | 0.06%   |
| 5.14.0  | 3         | 0.06%   |
| 5.12.14 | 3         | 0.06%   |
| 5.10.0  | 3         | 0.06%   |
| 6.2.11  | 2         | 0.04%   |
| 6.1.9   | 2         | 0.04%   |
| 6.1.0   | 2         | 0.04%   |
| 6.0.9   | 2         | 0.04%   |
| 6.0.0   | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 879       | 16.65%  |
| 5.4     | 745       | 14.11%  |
| 5.8     | 712       | 13.48%  |
| 5.15    | 494       | 9.36%   |
| 6.0     | 489       | 9.26%   |
| 5.13    | 478       | 9.05%   |
| 5.17    | 356       | 6.74%   |
| 5.16    | 323       | 6.12%   |
| 5.19    | 297       | 5.63%   |
| 6.2     | 206       | 3.9%    |
| 5.18    | 124       | 2.35%   |
| 6.1     | 60        | 1.14%   |
| 5.3     | 32        | 0.61%   |
| 5.10    | 18        | 0.34%   |
| 5.12    | 13        | 0.25%   |
| 5.7     | 11        | 0.21%   |
| 5.14    | 11        | 0.21%   |
| 5.9     | 9         | 0.17%   |
| 5.6     | 7         | 0.13%   |
| 4.18    | 7         | 0.13%   |
| 5.0     | 6         | 0.11%   |
| 4.15    | 2         | 0.04%   |
| 4.9     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 4837      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 4689      | 96.44%  |
| KDE5            | 42        | 0.86%   |
| Unknown         | 38        | 0.78%   |
| KDE             | 25        | 0.51%   |
| X-Cinnamon      | 16        | 0.33%   |
| GNOME Flashback | 10        | 0.21%   |
| XFCE            | 9         | 0.19%   |
| MATE            | 8         | 0.16%   |
| LXQt            | 8         | 0.16%   |
| Cinnamon        | 6         | 0.12%   |
| Unity           | 5         | 0.1%    |
| Budgie          | 4         | 0.08%   |
| Deepin          | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 4682      | 96.32%  |
| Wayland | 156       | 3.21%   |
| Unknown | 16        | 0.33%   |
| Tty     | 7         | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3689      | 75.42%  |
| GDM     | 774       | 15.82%  |
| GDM3    | 413       | 8.44%   |
| SDDM    | 8         | 0.16%   |
| TDM     | 5         | 0.1%    |
| LightDM | 2         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2815      | 57.84%  |
| pt_BR   | 357       | 7.34%   |
| en_GB   | 345       | 7.09%   |
| de_DE   | 204       | 4.19%   |
| C       | 122       | 2.51%   |
| it_IT   | 102       | 2.1%    |
| en_AU   | 97        | 1.99%   |
| fr_FR   | 96        | 1.97%   |
| es_ES   | 95        | 1.95%   |
| en_CA   | 84        | 1.73%   |
| ru_RU   | 65        | 1.34%   |
| Unknown | 50        | 1.03%   |
| pt_PT   | 42        | 0.86%   |
| pl_PL   | 42        | 0.86%   |
| sv_SE   | 33        | 0.68%   |
| en_IN   | 29        | 0.6%    |
| nb_NO   | 22        | 0.45%   |
| nl_NL   | 21        | 0.43%   |
| en_ZA   | 19        | 0.39%   |
| es_MX   | 18        | 0.37%   |
| fi_FI   | 17        | 0.35%   |
| tr_TR   | 13        | 0.27%   |
| en_NZ   | 13        | 0.27%   |
| fr_CA   | 11        | 0.23%   |
| es_AR   | 11        | 0.23%   |
| en_IE   | 10        | 0.21%   |
| en_DK   | 9         | 0.18%   |
| cs_CZ   | 9         | 0.18%   |
| hu_HU   | 8         | 0.16%   |
| hr_HR   | 8         | 0.16%   |
| es_CL   | 8         | 0.16%   |
| da_DK   | 7         | 0.14%   |
| ro_RO   | 6         | 0.12%   |
| de_CH   | 6         | 0.12%   |
| sk_SK   | 5         | 0.1%    |
| es_CO   | 5         | 0.1%    |
| zh_CN   | 4         | 0.08%   |
| nl_BE   | 4         | 0.08%   |
| en_IL   | 4         | 0.08%   |
| de_AT   | 4         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3423      | 69.7%   |
| EFI  | 1488      | 30.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4632      | 95.45%  |
| Btrfs   | 122       | 2.51%   |
| Overlay | 72        | 1.48%   |
| Xfs     | 19        | 0.39%   |
| Unknown | 7         | 0.14%   |
| Zfs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3659      | 74.95%  |
| GPT     | 1115      | 22.84%  |
| MBR     | 108       | 2.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4736      | 97.63%  |
| Yes       | 115       | 2.37%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4414      | 90.86%  |
| Yes       | 444       | 9.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 948       | 19.6%   |
| Dell                   | 856       | 17.7%   |
| Hewlett-Packard        | 660       | 13.64%  |
| ASUSTek Computer       | 553       | 11.43%  |
| Acer                   | 381       | 7.88%   |
| Apple                  | 278       | 5.75%   |
| System76               | 174       | 3.6%    |
| MSI                    | 158       | 3.27%   |
| Toshiba                | 96        | 1.98%   |
| Samsung Electronics    | 87        | 1.8%    |
| HUAWEI                 | 58        | 1.2%    |
| Sony                   | 48        | 0.99%   |
| Notebook               | 43        | 0.89%   |
| Google                 | 38        | 0.79%   |
| Alienware              | 38        | 0.79%   |
| Fujitsu                | 29        | 0.6%    |
| Positivo               | 26        | 0.54%   |
| Razer                  | 25        | 0.52%   |
| Gigabyte Technology    | 19        | 0.39%   |
| Timi                   | 18        | 0.37%   |
| PC Specialist          | 16        | 0.33%   |
| TUXEDO                 | 14        | 0.29%   |
| LG Electronics         | 13        | 0.27%   |
| Unknown                | 13        | 0.27%   |
| Medion                 | 12        | 0.25%   |
| GPU Company            | 12        | 0.25%   |
| Framework              | 12        | 0.25%   |
| Packard Bell           | 10        | 0.21%   |
| Avell High Performance | 10        | 0.21%   |
| Eluktronics            | 7         | 0.14%   |
| Teclast                | 6         | 0.12%   |
| Panasonic              | 6         | 0.12%   |
| Intel                  | 6         | 0.12%   |
| Gateway                | 6         | 0.12%   |
| Clevo                  | 6         | 0.12%   |
| HONOR                  | 5         | 0.1%    |
| Chuwi                  | 5         | 0.1%    |
| SLIMBOOK               | 4         | 0.08%   |
| Schenker               | 4         | 0.08%   |
| Quanta                 | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| System76 Oryx Pro                         | 42        | 0.87%   |
| System76 Lemur Pro                        | 38        | 0.79%   |
| Dell XPS 15 7590                          | 30        | 0.62%   |
| Apple MacBookPro9,2                       | 25        | 0.52%   |
| Unknown                                   | 25        | 0.52%   |
| System76 Gazelle                          | 24        | 0.5%    |
| Dell XPS 15 9500                          | 22        | 0.45%   |
| Apple MacBookPro12,1                      | 22        | 0.45%   |
| System76 Galago Pro                       | 21        | 0.43%   |
| Apple MacBookPro8,1                       | 20        | 0.41%   |
| HP Pavilion Notebook                      | 19        | 0.39%   |
| HP Notebook                               | 19        | 0.39%   |
| HP Pavilion 15                            | 17        | 0.35%   |
| System76 Darter Pro                       | 16        | 0.33%   |
| Apple MacBookAir7,2                       | 16        | 0.33%   |
| HP Pavilion dv6                           | 15        | 0.31%   |
| Dell XPS 15 9560                          | 15        | 0.31%   |
| Apple MacBookAir6,2                       | 14        | 0.29%   |
| Lenovo IdeaPad S145-15API 81V7            | 13        | 0.27%   |
| Dell XPS 15 9570                          | 13        | 0.27%   |
| Dell Latitude E6420                       | 13        | 0.27%   |
| Apple MacBookPro7,1                       | 13        | 0.27%   |
| HP Pavilion g6                            | 11        | 0.23%   |
| Dell XPS 17 9700                          | 11        | 0.23%   |
| Dell XPS 13 9380                          | 11        | 0.23%   |
| Dell Latitude E7240                       | 11        | 0.23%   |
| Apple MacBookPro5,5                       | 11        | 0.23%   |
| Acer Aspire E5-575G                       | 11        | 0.23%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 10        | 0.21%   |
| Lenovo IdeaPad 330-15IKB 81FE             | 10        | 0.21%   |
| HP Pavilion Laptop 15-cw1xxx              | 10        | 0.21%   |
| Framework Laptop                          | 10        | 0.21%   |
| Dell XPS 13 9310                          | 10        | 0.21%   |
| Dell Inspiron N5110                       | 10        | 0.21%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 10        | 0.21%   |
| Apple MacBookPro11,3                      | 10        | 0.21%   |
| Apple MacBook5,1                          | 10        | 0.21%   |
| Samsung 340XAA/350XAA/550XAA              | 9         | 0.19%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY      | 9         | 0.19%   |
| Lenovo IdeaPad 330-15IKB 81DE             | 9         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 466       | 9.63%   |
| Dell Inspiron      | 277       | 5.73%   |
| Lenovo IdeaPad     | 260       | 5.38%   |
| Acer Aspire        | 258       | 5.33%   |
| Dell Latitude      | 204       | 4.22%   |
| Dell XPS           | 186       | 3.85%   |
| HP Pavilion        | 160       | 3.31%   |
| HP EliteBook       | 103       | 2.13%   |
| HP Laptop          | 94        | 1.94%   |
| ASUS VivoBook      | 87        | 1.8%    |
| Toshiba Satellite  | 84        | 1.74%   |
| ASUS ROG           | 77        | 1.59%   |
| HP ProBook         | 76        | 1.57%   |
| Lenovo Legion      | 73        | 1.51%   |
| Dell Precision     | 60        | 1.24%   |
| Acer Nitro         | 47        | 0.97%   |
| Dell Vostro        | 46        | 0.95%   |
| ASUS ASUS          | 45        | 0.93%   |
| System76 Oryx      | 42        | 0.87%   |
| System76 Lemur     | 41        | 0.85%   |
| Acer Swift         | 37        | 0.76%   |
| HP ENVY            | 35        | 0.72%   |
| Apple MacBookPro11 | 35        | 0.72%   |
| ASUS ZenBook       | 32        | 0.66%   |
| Apple MacBookPro9  | 32        | 0.66%   |
| ASUS TUF           | 30        | 0.62%   |
| Apple MacBookPro8  | 28        | 0.58%   |
| HP OMEN            | 27        | 0.56%   |
| System76 Gazelle   | 26        | 0.54%   |
| Razer Blade        | 25        | 0.52%   |
| Lenovo ThinkBook   | 25        | 0.52%   |
| HP ZBook           | 25        | 0.52%   |
| Unknown            | 25        | 0.52%   |
| System76 Galago    | 24        | 0.5%    |
| Apple MacBookPro5  | 24        | 0.5%    |
| Fujitsu LIFEBOOK   | 22        | 0.45%   |
| Apple MacBookPro12 | 22        | 0.45%   |
| HP Notebook        | 19        | 0.39%   |
| Lenovo Yoga        | 18        | 0.37%   |
| Dell G3            | 18        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 619       | 12.8%   |
| 2020    | 576       | 11.91%  |
| 2021    | 492       | 10.17%  |
| 2018    | 462       | 9.55%   |
| 2012    | 354       | 7.32%   |
| 2013    | 317       | 6.55%   |
| 2017    | 301       | 6.22%   |
| 2015    | 293       | 6.06%   |
| 2011    | 291       | 6.02%   |
| 2016    | 262       | 5.42%   |
| 2014    | 225       | 4.65%   |
| 2010    | 191       | 3.95%   |
| 2022    | 167       | 3.45%   |
| 2009    | 120       | 2.48%   |
| 2008    | 111       | 2.29%   |
| 2007    | 36        | 0.74%   |
| 2006    | 10        | 0.21%   |
| 2023    | 5         | 0.1%    |
| Unknown | 3         | 0.06%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4837      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4834      | 99.94%  |
| Enabled  | 3         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4690      | 96.96%  |
| Yes  | 147       | 3.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1434      | 29.39%  |
| 16.01-24.0  | 1100      | 22.55%  |
| 8.01-16.0   | 897       | 18.38%  |
| 3.01-4.0    | 733       | 15.02%  |
| 32.01-64.0  | 447       | 9.16%   |
| 64.01-256.0 | 95        | 1.95%   |
| 1.01-2.0    | 69        | 1.41%   |
| 24.01-32.0  | 68        | 1.39%   |
| 2.01-3.0    | 36        | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1687      | 32.03%  |
| 1.01-2.0   | 1312      | 24.91%  |
| 4.01-8.0   | 1011      | 19.19%  |
| 3.01-4.0   | 979       | 18.59%  |
| 8.01-16.0  | 234       | 4.44%   |
| 16.01-24.0 | 25        | 0.47%   |
| 0.51-1.0   | 11        | 0.21%   |
| 24.01-32.0 | 7         | 0.13%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3426      | 69.61%  |
| 2      | 1281      | 26.03%  |
| 3      | 159       | 3.23%   |
| 0      | 24        | 0.49%   |
| 4      | 23        | 0.47%   |
| 5      | 7         | 0.14%   |
| 7      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3479      | 71.72%  |
| Yes       | 1372      | 28.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3842      | 79.02%  |
| No        | 1020      | 20.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4778      | 98.72%  |
| No        | 62        | 1.28%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4086      | 83.73%  |
| No        | 794       | 16.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1305      | 26.85%  |
| Brazil       | 497       | 10.23%  |
| Germany      | 294       | 6.05%   |
| UK           | 218       | 4.49%   |
| India        | 206       | 4.24%   |
| Canada       | 168       | 3.46%   |
| Italy        | 159       | 3.27%   |
| France       | 143       | 2.94%   |
| Australia    | 110       | 2.26%   |
| Netherlands  | 99        | 2.04%   |
| Russia       | 86        | 1.77%   |
| Sweden       | 82        | 1.69%   |
| Spain        | 77        | 1.58%   |
| Poland       | 73        | 1.5%    |
| Mexico       | 70        | 1.44%   |
| Portugal     | 69        | 1.42%   |
| Romania      | 54        | 1.11%   |
| Norway       | 53        | 1.09%   |
| Switzerland  | 49        | 1.01%   |
| South Africa | 48        | 0.99%   |
| Turkey       | 42        | 0.86%   |
| Finland      | 39        | 0.8%    |
| Philippines  | 38        | 0.78%   |
| Indonesia    | 38        | 0.78%   |
| Greece       | 38        | 0.78%   |
| Belgium      | 37        | 0.76%   |
| Argentina    | 36        | 0.74%   |
| Austria      | 33        | 0.68%   |
| New Zealand  | 32        | 0.66%   |
| Denmark      | 32        | 0.66%   |
| Chile        | 28        | 0.58%   |
| Czechia      | 24        | 0.49%   |
| Croatia      | 23        | 0.47%   |
| Hungary      | 22        | 0.45%   |
| Vietnam      | 21        | 0.43%   |
| Malaysia     | 21        | 0.43%   |
| Ireland      | 21        | 0.43%   |
| Colombia     | 21        | 0.43%   |
| Bulgaria     | 21        | 0.43%   |
| Japan        | 19        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 53        | 1.04%   |
| Bengaluru      | 33        | 0.65%   |
| Milan          | 30        | 0.59%   |
| Sydney         | 27        | 0.53%   |
| Brisbane       | 27        | 0.53%   |
| London         | 25        | 0.49%   |
| Dallas         | 25        | 0.49%   |
| Rio de Janeiro | 24        | 0.47%   |
| Vienna         | 23        | 0.45%   |
| Paris          | 23        | 0.45%   |
| New York       | 23        | 0.45%   |
| Moscow         | 22        | 0.43%   |
| Berlin         | 22        | 0.43%   |
| Melbourne      | 21        | 0.41%   |
| Helsinki       | 21        | 0.41%   |
| Bucharest      | 21        | 0.41%   |
| Athens         | 21        | 0.41%   |
| Amsterdam      | 20        | 0.39%   |
| Rome           | 19        | 0.37%   |
| Istanbul       | 19        | 0.37%   |
| Madrid         | 18        | 0.35%   |
| Johannesburg   | 18        | 0.35%   |
| Chicago        | 18        | 0.35%   |
| Zagreb         | 17        | 0.33%   |
| Warsaw         | 17        | 0.33%   |
| Los Angeles    | 17        | 0.33%   |
| Auckland       | 17        | 0.33%   |
| St Petersburg  | 16        | 0.32%   |
| Zurich         | 15        | 0.3%    |
| Toronto        | 15        | 0.3%    |
| Sofia          | 15        | 0.3%    |
| Oslo           | 15        | 0.3%    |
| Mexico City    | 15        | 0.3%    |
| Fortaleza      | 15        | 0.3%    |
| Calgary        | 15        | 0.3%    |
| Brasília      | 15        | 0.3%    |
| Stockholm      | 14        | 0.28%   |
| Seattle        | 14        | 0.28%   |
| Lisbon         | 14        | 0.28%   |
| Denver         | 14        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1135      | 1529   | 18.23%  |
| WDC                            | 663       | 757    | 10.65%  |
| Seagate                        | 606       | 717    | 9.73%   |
| SanDisk                        | 445       | 580    | 7.15%   |
| Toshiba                        | 398       | 467    | 6.39%   |
| Kingston                       | 330       | 391    | 5.3%    |
| SK hynix                       | 300       | 386    | 4.82%   |
| Unknown                        | 289       | 352    | 4.64%   |
| Crucial                        | 219       | 257    | 3.52%   |
| Intel                          | 201       | 251    | 3.23%   |
| HGST                           | 183       | 211    | 2.94%   |
| Micron Technology              | 168       | 188    | 2.7%    |
| Apple                          | 136       | 146    | 2.18%   |
| Hitachi                        | 100       | 110    | 1.61%   |
| A-DATA Technology              | 92        | 111    | 1.48%   |
| Phison                         | 76        | 93     | 1.22%   |
| China                          | 51        | 57     | 0.82%   |
| PNY                            | 49        | 59     | 0.79%   |
| LITEON                         | 43        | 49     | 0.69%   |
| KIOXIA                         | 42        | 51     | 0.67%   |
| Micron/Crucial Technology      | 40        | 55     | 0.64%   |
| Silicon Motion                 | 39        | 47     | 0.63%   |
| Transcend                      | 34        | 39     | 0.55%   |
| LITEONIT                       | 30        | 40     | 0.48%   |
| ADATA Technology               | 22        | 31     | 0.35%   |
| SPCC                           | 20        | 21     | 0.32%   |
| Fujitsu                        | 18        | 19     | 0.29%   |
| Team                           | 17        | 21     | 0.27%   |
| Phison Electronics             | 17        | 19     | 0.27%   |
| KingSpec                       | 17        | 19     | 0.27%   |
| JMicron Technology             | 17        | 23     | 0.27%   |
| Union Memory (Shenzhen)        | 15        | 18     | 0.24%   |
| Patriot                        | 14        | 16     | 0.22%   |
| Solid State Storage Technology | 13        | 16     | 0.21%   |
| OCZ                            | 13        | 13     | 0.21%   |
| Hewlett-Packard                | 13        | 15     | 0.21%   |
| Unknown                        | 13        | 15     | 0.21%   |
| Netac                          | 12        | 13     | 0.19%   |
| Corsair                        | 12        | 14     | 0.19%   |
| Kingston Technology Company    | 11        | 11     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB                  | 104       | 1.59%   |
| Kingston SA400S37240G 240GB SSD                   | 87        | 1.33%   |
| Samsung NVMe SSD Drive 512GB                      | 80        | 1.23%   |
| HGST HTS721010A9E630 1TB                          | 77        | 1.18%   |
| Unknown MMC Card  64GB                            | 70        | 1.07%   |
| Samsung NVMe SSD Drive 1TB                        | 64        | 0.98%   |
| SK hynix NVMe SSD Drive 512GB                     | 59        | 0.9%    |
| Toshiba MQ01ABD100 1TB                            | 58        | 0.89%   |
| Samsung NVMe SSD Drive 256GB                      | 57        | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 56        | 0.86%   |
| SanDisk NVMe SSD Drive 512GB                      | 53        | 0.81%   |
| Samsung NVMe SSD Drive 500GB                      | 52        | 0.8%    |
| Unknown MMC Card  32GB                            | 49        | 0.75%   |
| Intel NVMe SSD Drive 512GB                        | 47        | 0.72%   |
| Toshiba MQ04ABF100 1TB                            | 46        | 0.71%   |
| WDC WD10SPZX-24Z10 1TB                            | 41        | 0.63%   |
| SanDisk NVMe SSD Drive 1TB                        | 40        | 0.61%   |
| Samsung NVMe SSD Drive 1024GB                     | 40        | 0.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 37        | 0.57%   |
| Seagate ST9500325AS 500GB                         | 36        | 0.55%   |
| Samsung SSD 860 EVO 500GB                         | 36        | 0.55%   |
| Seagate ST1000LM049-2GH172 1TB                    | 35        | 0.54%   |
| SanDisk NVMe SSD Drive 256GB                      | 35        | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 33        | 0.51%   |
| Kingston SA400S37480G 480GB SSD                   | 32        | 0.49%   |
| SK hynix NVMe SSD Drive 1024GB                    | 31        | 0.48%   |
| Seagate ST500LT012-1DG142 500GB                   | 31        | 0.48%   |
| Samsung SSD 850 EVO 250GB                         | 31        | 0.48%   |
| Crucial CT240BX500SSD1 240GB                      | 31        | 0.48%   |
| Unknown MMC Card  128GB                           | 30        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                      | 30        | 0.46%   |
| SK hynix NVMe SSD Drive 256GB                     | 29        | 0.44%   |
| SanDisk NVMe SSD Drive 500GB                      | 29        | 0.44%   |
| Kingston SA400S37120G 120GB SSD                   | 29        | 0.44%   |
| Toshiba NVMe SSD Drive 512GB                      | 28        | 0.43%   |
| HGST HTS541010A9E680 1TB                          | 28        | 0.43%   |
| Seagate Expansion 4TB                             | 26        | 0.4%    |
| Samsung SSD 860 EVO 1TB                           | 26        | 0.4%    |
| Samsung NVMe SSD Drive 2TB                        | 26        | 0.4%    |
| Micron NVMe SSD Drive 512GB                       | 26        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 580       | 675    | 35.52%  |
| WDC                 | 411       | 452    | 25.17%  |
| Toshiba             | 243       | 274    | 14.88%  |
| HGST                | 183       | 211    | 11.21%  |
| Hitachi             | 100       | 110    | 6.12%   |
| Samsung Electronics | 30        | 31     | 1.84%   |
| Unknown             | 26        | 28     | 1.59%   |
| Fujitsu             | 18        | 19     | 1.1%    |
| Apple               | 16        | 18     | 0.98%   |
| JMicron Technology  | 11        | 16     | 0.67%   |
| Intenso             | 3         | 5      | 0.18%   |
| ASMT                | 3         | 5      | 0.18%   |
| PHD 3.0             | 2         | 2      | 0.12%   |
| USB3.0              | 1         | 1      | 0.06%   |
| SABRENT             | 1         | 2      | 0.06%   |
| RSH-339             | 1         | 1      | 0.06%   |
| Inateck             | 1         | 1      | 0.06%   |
| HGST HDN            | 1         | 1      | 0.06%   |
| DAS                 | 1         | 4      | 0.06%   |
| Asm                 | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 457       | 606    | 21.64%  |
| Kingston            | 254       | 287    | 12.03%  |
| SanDisk             | 212       | 261    | 10.04%  |
| Crucial             | 203       | 241    | 9.61%   |
| WDC                 | 132       | 161    | 6.25%   |
| Apple               | 101       | 106    | 4.78%   |
| A-DATA Technology   | 61        | 72     | 2.89%   |
| SK hynix            | 55        | 64     | 2.6%    |
| Micron Technology   | 54        | 57     | 2.56%   |
| Toshiba             | 51        | 61     | 2.41%   |
| China               | 51        | 57     | 2.41%   |
| PNY                 | 48        | 58     | 2.27%   |
| Intel               | 42        | 46     | 1.99%   |
| LITEON              | 40        | 46     | 1.89%   |
| Transcend           | 33        | 38     | 1.56%   |
| LITEONIT            | 30        | 40     | 1.42%   |
| SPCC                | 18        | 19     | 0.85%   |
| KingSpec            | 17        | 19     | 0.8%    |
| Seagate             | 14        | 15     | 0.66%   |
| Patriot             | 14        | 16     | 0.66%   |
| OCZ                 | 13        | 13     | 0.62%   |
| Team                | 11        | 15     | 0.52%   |
| Netac               | 10        | 11     | 0.47%   |
| Hewlett-Packard     | 10        | 12     | 0.47%   |
| Lexar               | 9         | 9      | 0.43%   |
| Corsair             | 9         | 10     | 0.43%   |
| KingDian            | 7         | 8      | 0.33%   |
| Dogfish             | 7         | 10     | 0.33%   |
| Apacer              | 7         | 12     | 0.33%   |
| Intenso             | 6         | 6      | 0.28%   |
| BHT                 | 6         | 6      | 0.28%   |
| TO Exter            | 5         | 5      | 0.24%   |
| Plextor             | 5         | 7      | 0.24%   |
| Mushkin             | 5         | 6      | 0.24%   |
| GOODRAM             | 5         | 6      | 0.24%   |
| ASMT                | 5         | 5      | 0.24%   |
| Maxtor              | 4         | 4      | 0.19%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.19%   |
| Gigabyte Technology | 4         | 6      | 0.19%   |
| FORESEE             | 4         | 5      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2021      | 2817   | 34.42%  |
| SSD     | 1956      | 2523   | 33.32%  |
| HDD     | 1579      | 1857   | 26.89%  |
| MMC     | 237       | 287    | 4.04%   |
| Unknown | 78        | 105    | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3091      | 4204   | 55.5%   |
| NVMe | 2018      | 2805   | 36.24%  |
| MMC  | 237       | 287    | 4.26%   |
| SAS  | 223       | 293    | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2217      | 2854   | 63.43%  |
| 0.51-1.0   | 1130      | 1338   | 32.33%  |
| 1.01-2.0   | 108       | 135    | 3.09%   |
| 3.01-4.0   | 28        | 33     | 0.8%    |
| 4.01-10.0  | 8         | 15     | 0.23%   |
| 10.01-20.0 | 3         | 4      | 0.09%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1672      | 33.51%  |
| 251-500        | 1414      | 28.34%  |
| 501-1000       | 924       | 18.52%  |
| 1001-2000      | 336       | 6.73%   |
| 51-100         | 252       | 5.05%   |
| 21-50          | 117       | 2.35%   |
| 1-20           | 116       | 2.33%   |
| 2001-3000      | 71        | 1.42%   |
| More than 3000 | 57        | 1.14%   |
| Unknown        | 30        | 0.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2054      | 39.22%  |
| 21-50          | 1153      | 22.02%  |
| 51-100         | 683       | 13.04%  |
| 101-250        | 681       | 13%     |
| 251-500        | 351       | 6.7%    |
| 501-1000       | 189       | 3.61%   |
| 1001-2000      | 61        | 1.16%   |
| Unknown        | 30        | 0.57%   |
| More than 3000 | 18        | 0.34%   |
| 2001-3000      | 17        | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB               | 5         | 8      | 4.35%   |
| Seagate ST1000LM035-1RK172 970GB         | 4         | 4      | 3.48%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 3.48%   |
| SK hynix PC711 HFS001TDE9X073N 1TB       | 3         | 3      | 2.61%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 2.61%   |
| Seagate ST1000LX015-1U7172 1TB           | 3         | 3      | 2.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 3         | 3      | 2.61%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 2.61%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.61%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 2         | 2      | 1.74%   |
| Seagate ST9500325AS 500GB                | 2         | 3      | 1.74%   |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 1.74%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.74%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 1.74%   |
| Kingston SUV400S37120G 120GB SSD         | 2         | 2      | 1.74%   |
| Crucial CT1000P1SSD8 1TB                 | 2         | 2      | 1.74%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.87%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.87%   |
| WDC WD5000LPCX-21VHAT0 500GB             | 1         | 1      | 0.87%   |
| WDC WD5000BPVT-22HXZT3 500GB             | 1         | 1      | 0.87%   |
| WDC WD5000BPVT-08HXZT3 500GB             | 1         | 1      | 0.87%   |
| WDC WD3200BEKT-60PVMT0 320GB             | 1         | 1      | 0.87%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 1      | 0.87%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.87%   |
| WDC WD10SPZX-75Z10T1 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10SPZX-24Z10 1TB                   | 1         | 1      | 0.87%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10SPCX-24HWST1 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10JPVX-60JC3T0 1TB                 | 1         | 1      | 0.87%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB     | 1         | 1      | 0.87%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.87%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 2      | 0.87%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 0.87%   |
| Toshiba MQ02ABD100H 1TB                  | 1         | 1      | 0.87%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.87%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.87%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 0.87%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 1      | 0.87%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 26     | 21.74%  |
| WDC                 | 18        | 18     | 15.65%  |
| HGST                | 14        | 17     | 12.17%  |
| Toshiba             | 11        | 12     | 9.57%   |
| SK hynix            | 8         | 10     | 6.96%   |
| Samsung Electronics | 6         | 6      | 5.22%   |
| Hitachi             | 6         | 8      | 5.22%   |
| Crucial             | 5         | 5      | 4.35%   |
| A-DATA Technology   | 5         | 5      | 4.35%   |
| Micron Technology   | 4         | 4      | 3.48%   |
| Kingston            | 4         | 4      | 3.48%   |
| Intel               | 3         | 3      | 2.61%   |
| SanDisk             | 2         | 2      | 1.74%   |
| Team                | 1         | 1      | 0.87%   |
| Lexar               | 1         | 1      | 0.87%   |
| Leven               | 1         | 1      | 0.87%   |
| China               | 1         | 1      | 0.87%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 25        | 26     | 36.23%  |
| WDC     | 16        | 16     | 23.19%  |
| HGST    | 14        | 17     | 20.29%  |
| Toshiba | 8         | 8      | 11.59%  |
| Hitachi | 6         | 8      | 8.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 69        | 75     | 60%     |
| SSD  | 29        | 32     | 25.22%  |
| NVMe | 17        | 17     | 14.78%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 100%    |

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
| Detected | 3746      | 5847   | 73.97%  |
| Works    | 1202      | 1617   | 23.74%  |
| Malfunc  | 115       | 124    | 2.27%   |
| Failed   | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3238      | 53.49%  |
| Samsung Electronics              | 750       | 12.39%  |
| AMD                              | 610       | 10.08%  |
| SanDisk                          | 344       | 5.68%   |
| SK hynix                         | 244       | 4.03%   |
| Toshiba America Info Systems     | 114       | 1.88%   |
| Micron Technology                | 114       | 1.88%   |
| Phison Electronics               | 97        | 1.6%    |
| Kingston Technology Company      | 86        | 1.42%   |
| Nvidia                           | 76        | 1.26%   |
| ADATA Technology                 | 55        | 0.91%   |
| Micron/Crucial Technology        | 52        | 0.86%   |
| Silicon Motion                   | 47        | 0.78%   |
| KIOXIA                           | 44        | 0.73%   |
| Solid State Storage Technology   | 36        | 0.59%   |
| Union Memory (Shenzhen)          | 30        | 0.5%    |
| Apple                            | 19        | 0.31%   |
| Realtek Semiconductor            | 18        | 0.3%    |
| Marvell Technology Group         | 18        | 0.3%    |
| Seagate Technology               | 12        | 0.2%    |
| Silicon Integrated Systems [SiS] | 8         | 0.13%   |
| Shenzhen Longsys Electronics     | 8         | 0.13%   |
| Lite-On Technology               | 7         | 0.12%   |
| Lenovo                           | 6         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 5         | 0.08%   |
| JMicron Technology               | 4         | 0.07%   |
| ASMedia Technology               | 3         | 0.05%   |
| INNOGRIT                         | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 579       | 9.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 401       | 6.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 387       | 6.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 333       | 5.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 306       | 4.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 270       | 4.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 242       | 3.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 193       | 3.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 150       | 2.36%   |
| Intel Volume Management Device NVMe RAID Controller                            | 144       | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 141       | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 125       | 1.97%   |
| Samsung NVMe SSD Controller 980                                                | 117       | 1.84%   |
| Micron NVMe Storage Controller                                                 | 113       | 1.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 97        | 1.53%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 96        | 1.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 95        | 1.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 92        | 1.45%   |
| Intel SSD 660P Series                                                          | 91        | 1.43%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 86        | 1.35%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 85        | 1.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 81        | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                          | 81        | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 78        | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 65        | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 54        | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 52        | 0.82%   |
| Phison E12 NVMe Controller                                                     | 50        | 0.79%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 49        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 49        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 49        | 0.77%   |
| Intel Tiger Lake-LP SATA Controller                                            | 48        | 0.76%   |
| Samsung Electronics SATA controller                                            | 46        | 0.72%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 44        | 0.69%   |
| Nvidia MCP79 AHCI Controller                                                   | 44        | 0.69%   |
| SK hynix Non-Volatile memory controller                                        | 42        | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 40        | 0.63%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 40        | 0.63%   |
| SanDisk Non-Volatile memory controller                                         | 38        | 0.6%    |
| Solid State Storage Non-Volatile memory controller                             | 36        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3422      | 56.31%  |
| NVMe | 2014      | 33.14%  |
| RAID | 478       | 7.87%   |
| IDE  | 163       | 2.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3927      | 81.19%  |
| AMD    | 910       | 18.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 122       | 2.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 95        | 1.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 95        | 1.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 87        | 1.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 86        | 1.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 74        | 1.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 73        | 1.51%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 70        | 1.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 68        | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 67        | 1.38%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 63        | 1.3%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 61        | 1.26%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 59        | 1.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 56        | 1.16%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 53        | 1.1%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 52        | 1.07%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 52        | 1.07%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 48        | 0.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 46        | 0.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 44        | 0.91%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 43        | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 42        | 0.87%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 40        | 0.83%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 38        | 0.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 38        | 0.79%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 38        | 0.79%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 36        | 0.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 35        | 0.72%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 34        | 0.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 34        | 0.7%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 33        | 0.68%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 33        | 0.68%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 33        | 0.68%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 32        | 0.66%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 31        | 0.64%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 30        | 0.62%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 30        | 0.62%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 30        | 0.62%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 29        | 0.6%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 27        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1432      | 29.61%  |
| Intel Core i5           | 1232      | 25.47%  |
| Other                   | 400       | 8.27%   |
| Intel Core i3           | 302       | 6.24%   |
| AMD Ryzen 7             | 257       | 5.31%   |
| AMD Ryzen 5             | 254       | 5.25%   |
| Intel Core 2 Duo        | 174       | 3.6%    |
| Intel Celeron           | 160       | 3.31%   |
| Intel Pentium           | 56        | 1.16%   |
| AMD Ryzen 9             | 56        | 1.16%   |
| AMD Ryzen 3             | 55        | 1.14%   |
| AMD A6                  | 50        | 1.03%   |
| Intel Core i9           | 49        | 1.01%   |
| AMD A8                  | 35        | 0.72%   |
| AMD Ryzen 7 PRO         | 33        | 0.68%   |
| Intel Pentium Dual-Core | 31        | 0.64%   |
| AMD A10                 | 30        | 0.62%   |
| AMD A4                  | 24        | 0.5%    |
| Intel Atom              | 19        | 0.39%   |
| Intel Core 2            | 17        | 0.35%   |
| Intel Xeon              | 13        | 0.27%   |
| Intel Pentium Dual      | 13        | 0.27%   |
| Intel Genuine           | 13        | 0.27%   |
| Intel Core m3           | 12        | 0.25%   |
| AMD Athlon              | 12        | 0.25%   |
| AMD E1                  | 11        | 0.23%   |
| AMD Ryzen 5 PRO         | 10        | 0.21%   |
| AMD E                   | 9         | 0.19%   |
| Intel Pentium Silver    | 7         | 0.14%   |
| AMD E2                  | 7         | 0.14%   |
| Intel Core M            | 6         | 0.12%   |
| AMD Turion 64 X2 Mobile | 6         | 0.12%   |
| AMD FX                  | 6         | 0.12%   |
| AMD A12                 | 6         | 0.12%   |
| Intel Celeron Dual-Core | 4         | 0.08%   |
| AMD C-60                | 4         | 0.08%   |
| AMD Athlon X2           | 4         | 0.08%   |
| Intel Core m5           | 3         | 0.06%   |
| AMD Phenom II           | 3         | 0.06%   |
| AMD V120                | 2         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2088      | 43.17%  |
| 4      | 1691      | 34.96%  |
| 6      | 496       | 10.25%  |
| 8      | 444       | 9.18%   |
| 14     | 42        | 0.87%   |
| 12     | 26        | 0.54%   |
| 1      | 24        | 0.5%    |
| 10     | 20        | 0.41%   |
| 16     | 3         | 0.06%   |
| 7      | 1         | 0.02%   |
| 5      | 1         | 0.02%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4837      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4052      | 83.7%   |
| 1      | 789       | 16.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4830      | 99.86%  |
| Unknown        | 7         | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3154      | 63.59%  |
| 0x906ea    | 151       | 3.04%   |
| 0x806ea    | 108       | 2.18%   |
| 0x306a9    | 101       | 2.04%   |
| 0x806ec    | 98        | 1.98%   |
| 0x806c1    | 93        | 1.88%   |
| 0x206a7    | 91        | 1.83%   |
| 0x406e3    | 86        | 1.73%   |
| 0x40651    | 80        | 1.61%   |
| 0xa0652    | 74        | 1.49%   |
| 0x806e9    | 60        | 1.21%   |
| 0x306c3    | 56        | 1.13%   |
| 0x906e9    | 53        | 1.07%   |
| 0x0a50000c | 50        | 1.01%   |
| 0x08108102 | 44        | 0.89%   |
| 0x306d4    | 40        | 0.81%   |
| 0x806d1    | 37        | 0.75%   |
| 0x1067a    | 35        | 0.71%   |
| 0x806eb    | 34        | 0.69%   |
| 0x506e3    | 34        | 0.69%   |
| 0x08600106 | 33        | 0.67%   |
| 0x08108109 | 29        | 0.58%   |
| 0x906ed    | 28        | 0.56%   |
| 0x906a3    | 24        | 0.48%   |
| 0x08600104 | 23        | 0.46%   |
| 0x20655    | 22        | 0.44%   |
| 0x08608103 | 21        | 0.42%   |
| 0x706e5    | 20        | 0.4%    |
| 0x08600103 | 18        | 0.36%   |
| 0x06006705 | 17        | 0.34%   |
| 0x0810100b | 15        | 0.3%    |
| 0x706a1    | 13        | 0.26%   |
| 0x0a404101 | 12        | 0.24%   |
| 0x40661    | 11        | 0.22%   |
| 0x10676    | 11        | 0.22%   |
| 0x07030105 | 10        | 0.2%    |
| 0xa0660    | 9         | 0.18%   |
| 0x906a4    | 8         | 0.16%   |
| 0x0a404102 | 8         | 0.16%   |
| 0x08600102 | 8         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1144      | 23.63%  |
| Haswell          | 427       | 8.82%   |
| SandyBridge      | 348       | 7.19%   |
| IvyBridge        | 336       | 6.94%   |
| Skylake          | 276       | 5.7%    |
| TigerLake        | 223       | 4.61%   |
| Unknown          | 198       | 4.09%   |
| Zen+             | 197       | 4.07%   |
| CometLake        | 189       | 3.9%    |
| Penryn           | 186       | 3.84%   |
| Broadwell        | 181       | 3.74%   |
| Zen 2            | 180       | 3.72%   |
| Zen 3            | 152       | 3.14%   |
| Westmere         | 143       | 2.95%   |
| IceLake          | 90        | 1.86%   |
| Silvermont       | 78        | 1.61%   |
| Core             | 74        | 1.53%   |
| Excavator        | 65        | 1.34%   |
| Goldmont plus    | 57        | 1.18%   |
| Zen              | 50        | 1.03%   |
| Puma             | 43        | 0.89%   |
| Alderlake Hybrid | 36        | 0.74%   |
| Piledriver       | 35        | 0.72%   |
| Bobcat           | 22        | 0.45%   |
| Goldmont         | 21        | 0.43%   |
| Nehalem          | 17        | 0.35%   |
| Steamroller      | 13        | 0.27%   |
| Jaguar           | 13        | 0.27%   |
| K10 Llano        | 12        | 0.25%   |
| K8 Hammer        | 11        | 0.23%   |
| K10              | 9         | 0.19%   |
| K8 & K10 hybrid  | 8         | 0.17%   |
| Bonnell          | 4         | 0.08%   |
| Tremont          | 3         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3568      | 55.22%  |
| Nvidia                           | 1744      | 26.99%  |
| AMD                              | 1142      | 17.68%  |
| Silicon Integrated Systems [SiS] | 6         | 0.09%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 322       | 4.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 317       | 4.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 309       | 4.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 233       | 3.52%   |
| Intel UHD Graphics 620                                                                   | 209       | 3.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 208       | 3.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 197       | 2.98%   |
| AMD Renoir                                                                               | 171       | 2.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 169       | 2.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 158       | 2.39%   |
| Intel HD Graphics 620                                                                    | 147       | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 143       | 2.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 140       | 2.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 133       | 2.01%   |
| Intel HD Graphics 5500                                                                   | 127       | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 122       | 1.84%   |
| Intel HD Graphics 630                                                                    | 117       | 1.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 116       | 1.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 109       | 1.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 82        | 1.24%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 80        | 1.21%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 79        | 1.19%   |
| Intel HD Graphics 530                                                                    | 72        | 1.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 71        | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 66        | 1%      |
| AMD Lucienne                                                                             | 66        | 1%      |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 64        | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 58        | 0.88%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 58        | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 56        | 0.85%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 54        | 0.82%   |
| Nvidia GP108M [GeForce MX150]                                                            | 52        | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 52        | 0.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 50        | 0.76%   |
| Nvidia TU117M                                                                            | 49        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 47        | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 45        | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 45        | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 41        | 0.62%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 37        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2198      | 45.12%  |
| Intel + Nvidia     | 1196      | 24.55%  |
| 1 x AMD            | 653       | 13.41%  |
| 1 x Nvidia         | 314       | 6.45%   |
| AMD + Nvidia       | 212       | 4.35%   |
| Intel + AMD        | 183       | 3.76%   |
| 2 x AMD            | 95        | 1.95%   |
| 2 x Nvidia         | 9         | 0.18%   |
| 1 x SiS            | 6         | 0.12%   |
| Other              | 2         | 0.04%   |
| Intel + 2 x Nvidia | 2         | 0.04%   |
| 1 x S3 Graphics    | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3368      | 68.97%  |
| Proprietary | 1386      | 28.38%  |
| Unknown     | 129       | 2.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3669      | 74.5%   |
| 1.01-2.0   | 333       | 6.76%   |
| 3.01-4.0   | 310       | 6.29%   |
| 0.01-0.5   | 192       | 3.9%    |
| 5.01-6.0   | 185       | 3.76%   |
| 7.01-8.0   | 101       | 2.05%   |
| 0.51-1.0   | 93        | 1.89%   |
| 2.01-3.0   | 29        | 0.59%   |
| 8.01-16.0  | 13        | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 991       | 17.71%  |
| Chimei Innolux          | 820       | 14.65%  |
| LG Display              | 784       | 14.01%  |
| BOE                     | 719       | 12.85%  |
| Samsung Electronics     | 514       | 9.18%   |
| Apple                   | 231       | 4.13%   |
| Sharp                   | 207       | 3.7%    |
| Goldstar                | 169       | 3.02%   |
| Dell                    | 163       | 2.91%   |
| PANDA                   | 142       | 2.54%   |
| Chi Mei Optoelectronics | 87        | 1.55%   |
| Lenovo                  | 73        | 1.3%    |
| Acer                    | 59        | 1.05%   |
| AOC                     | 57        | 1.02%   |
| Hewlett-Packard         | 56        | 1%      |
| InfoVision              | 47        | 0.84%   |
| Philips                 | 44        | 0.79%   |
| BenQ                    | 43        | 0.77%   |
| CSO                     | 33        | 0.59%   |
| Ancor Communications    | 32        | 0.57%   |
| ASUSTek Computer        | 31        | 0.55%   |
| ViewSonic               | 19        | 0.34%   |
| TMX                     | 14        | 0.25%   |
| Sony                    | 14        | 0.25%   |
| LG Philips              | 14        | 0.25%   |
| Panasonic               | 12        | 0.21%   |
| Vizio                   | 11        | 0.2%    |
| InnoLux Display         | 10        | 0.18%   |
| Sceptre Tech            | 9         | 0.16%   |
| Toshiba                 | 8         | 0.14%   |
| JDI                     | 8         | 0.14%   |
| Iiyama                  | 8         | 0.14%   |
| Vestel Elektronik       | 6         | 0.11%   |
| MSI                     | 6         | 0.11%   |
| LGD                     | 5         | 0.09%   |
| Hitachi                 | 5         | 0.09%   |
| HannStar                | 5         | 0.09%   |
| TCL                     | 4         | 0.07%   |
| NEC Computers           | 4         | 0.07%   |
| Insignia                | 4         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 55        | 0.97%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 52        | 0.92%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 48        | 0.85%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 47        | 0.83%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 43        | 0.76%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 42        | 0.74%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 35        | 0.62%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 33        | 0.58%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 31        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 27        | 0.48%   |
| Samsung Electronics LCD Monitor SDCA029 2560x1440 294x165mm 13.3-inch     | 26        | 0.46%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 26        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 26        | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 24        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 24        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 23        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 23        | 0.41%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 22        | 0.39%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 21        | 0.37%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 20        | 0.35%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 20        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 19        | 0.34%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 18        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 18        | 0.32%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 18        | 0.32%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 17        | 0.3%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 17        | 0.3%    |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 17        | 0.3%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 16        | 0.28%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch          | 16        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 16        | 0.28%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 16        | 0.28%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 15        | 0.27%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 15        | 0.27%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 15        | 0.27%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 15        | 0.27%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 14        | 0.25%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                   | 14        | 0.25%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 14        | 0.25%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 14        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2475      | 47.21%  |
| 1366x768 (WXGA)    | 1338      | 25.52%  |
| 3840x2160 (4K)     | 270       | 5.15%   |
| 1600x900 (HD+)     | 217       | 4.14%   |
| 2560x1440 (QHD)    | 168       | 3.2%    |
| 1280x800 (WXGA)    | 130       | 2.48%   |
| 1920x1200 (WUXGA)  | 97        | 1.85%   |
| 1440x900 (WXGA+)   | 93        | 1.77%   |
| 2560x1600          | 78        | 1.49%   |
| 2880x1800          | 63        | 1.2%    |
| 2560x1080          | 44        | 0.84%   |
| 3840x2400          | 32        | 0.61%   |
| 3440x1440          | 31        | 0.59%   |
| 1680x1050 (WSXGA+) | 29        | 0.55%   |
| 3200x1800 (QHD+)   | 18        | 0.34%   |
| 2160x1440          | 18        | 0.34%   |
| 1360x768           | 18        | 0.34%   |
| 2256x1504          | 14        | 0.27%   |
| 1280x1024 (SXGA)   | 14        | 0.27%   |
| 1920x540           | 13        | 0.25%   |
| 3000x2000          | 10        | 0.19%   |
| 3840x1080          | 9         | 0.17%   |
| 3456x2160          | 6         | 0.11%   |
| 3200x2000          | 6         | 0.11%   |
| 3072x1920          | 6         | 0.11%   |
| Unknown            | 6         | 0.11%   |
| 3840x1100          | 3         | 0.06%   |
| 2560x1700          | 3         | 0.06%   |
| 2304x1440          | 3         | 0.06%   |
| 800x1280           | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |
| 3840x1200          | 2         | 0.04%   |
| 2288x1287          | 2         | 0.04%   |
| 1920x515           | 2         | 0.04%   |
| 1920x1280          | 2         | 0.04%   |
| 1680x945           | 2         | 0.04%   |
| 1280x720 (HD)      | 2         | 0.04%   |
| 1024x768 (XGA)     | 2         | 0.04%   |
| 1024x600           | 2         | 0.04%   |
| 7680x2160          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2360      | 42.2%   |
| 13      | 866       | 15.49%  |
| 14      | 633       | 11.32%  |
| 17      | 407       | 7.28%   |
| 27      | 189       | 3.38%   |
| 24      | 158       | 2.83%   |
| 23      | 141       | 2.52%   |
| 12      | 121       | 2.16%   |
| 21      | 103       | 1.84%   |
| 31      | 80        | 1.43%   |
| 16      | 74        | 1.32%   |
| 11      | 68        | 1.22%   |
| 34      | 65        | 1.16%   |
| 18      | 47        | 0.84%   |
| Unknown | 42        | 0.75%   |
| 19      | 32        | 0.57%   |
| 84      | 21        | 0.38%   |
| 32      | 21        | 0.38%   |
| 40      | 20        | 0.36%   |
| 20      | 17        | 0.3%    |
| 72      | 15        | 0.27%   |
| 22      | 14        | 0.25%   |
| 48      | 10        | 0.18%   |
| 54      | 9         | 0.16%   |
| 25      | 9         | 0.16%   |
| 52      | 6         | 0.11%   |
| 35      | 5         | 0.09%   |
| 33      | 5         | 0.09%   |
| 28      | 5         | 0.09%   |
| 26      | 5         | 0.09%   |
| 10      | 5         | 0.09%   |
| 65      | 4         | 0.07%   |
| 49      | 4         | 0.07%   |
| 46      | 4         | 0.07%   |
| 39      | 4         | 0.07%   |
| 29      | 4         | 0.07%   |
| 47      | 3         | 0.05%   |
| 37      | 3         | 0.05%   |
| 8       | 2         | 0.04%   |
| 99      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3429      | 61.77%  |
| 201-300        | 616       | 11.1%   |
| 351-400        | 490       | 8.83%   |
| 501-600        | 446       | 8.03%   |
| 401-500        | 204       | 3.68%   |
| 601-700        | 113       | 2.04%   |
| 701-800        | 92        | 1.66%   |
| 1001-1500      | 44        | 0.79%   |
| Unknown        | 42        | 0.76%   |
| 1501-2000      | 38        | 0.68%   |
| 801-900        | 30        | 0.54%   |
| 901-1000       | 3         | 0.05%   |
| 101-200        | 2         | 0.04%   |
| More than 2000 | 1         | 0.02%   |
| 1-100          | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4125      | 84.72%  |
| 16/10   | 542       | 11.13%  |
| 21/9    | 77        | 1.58%   |
| 3/2     | 55        | 1.13%   |
| Unknown | 23        | 0.47%   |
| 5/4     | 17        | 0.35%   |
| 32/9    | 10        | 0.21%   |
| 4/3     | 8         | 0.16%   |
| 3.40    | 3         | 0.06%   |
| 3.73    | 2         | 0.04%   |
| 0.62    | 2         | 0.04%   |
| 6/5     | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.63    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2372      | 42.49%  |
| 81-90          | 1208      | 21.64%  |
| 121-130        | 379       | 6.79%   |
| 201-250        | 353       | 6.32%   |
| 71-80          | 288       | 5.16%   |
| 301-350        | 193       | 3.46%   |
| 351-500        | 175       | 3.14%   |
| 61-70          | 114       | 2.04%   |
| 51-60          | 71        | 1.27%   |
| 151-200        | 71        | 1.27%   |
| More than 1000 | 68        | 1.22%   |
| 111-120        | 57        | 1.02%   |
| 251-300        | 52        | 0.93%   |
| 141-150        | 51        | 0.91%   |
| 501-1000       | 47        | 0.84%   |
| Unknown        | 42        | 0.75%   |
| 131-140        | 24        | 0.43%   |
| 91-100         | 9         | 0.16%   |
| 41-50          | 5         | 0.09%   |
| 1-40           | 3         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2405      | 43.97%  |
| 101-120       | 1528      | 27.93%  |
| 51-100        | 760       | 13.89%  |
| 161-240       | 419       | 7.66%   |
| More than 240 | 245       | 4.48%   |
| 1-50          | 71        | 1.3%    |
| Unknown       | 42        | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3840      | 77.58%  |
| 2     | 843       | 17.03%  |
| 0     | 163       | 3.29%   |
| 3     | 98        | 1.98%   |
| 4     | 6         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2633      | 33.75%  |
| Intel                             | 2596      | 33.27%  |
| Qualcomm Atheros                  | 1076      | 13.79%  |
| Broadcom                          | 526       | 6.74%   |
| Broadcom Limited                  | 153       | 1.96%   |
| MediaTek                          | 119       | 1.53%   |
| Marvell Technology Group          | 67        | 0.86%   |
| Ralink                            | 54        | 0.69%   |
| Nvidia                            | 54        | 0.69%   |
| ASIX Electronics                  | 51        | 0.65%   |
| TP-Link                           | 50        | 0.64%   |
| Ralink Technology                 | 39        | 0.5%    |
| Samsung Electronics               | 38        | 0.49%   |
| DisplayLink                       | 30        | 0.38%   |
| Dell                              | 26        | 0.33%   |
| Lenovo                            | 23        | 0.29%   |
| Ericsson Business Mobile Networks | 22        | 0.28%   |
| Sierra Wireless                   | 21        | 0.27%   |
| Xiaomi                            | 20        | 0.26%   |
| Qualcomm                          | 20        | 0.26%   |
| JMicron Technology                | 17        | 0.22%   |
| Hewlett-Packard                   | 14        | 0.18%   |
| Google                            | 14        | 0.18%   |
| OnePlus Technology (Shenzhen)     | 12        | 0.15%   |
| ASUSTek Computer                  | 12        | 0.15%   |
| NetGear                           | 11        | 0.14%   |
| Huawei Technologies               | 10        | 0.13%   |
| D-Link                            | 9         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.1%    |
| Motorola PCS                      | 8         | 0.1%    |
| OPPO Electronics                  | 6         | 0.08%   |
| Linksys                           | 6         | 0.08%   |
| Apple                             | 6         | 0.08%   |
| Microsoft                         | 4         | 0.05%   |
| Fibocom                           | 4         | 0.05%   |
| Qualcomm Atheros Communications   | 3         | 0.04%   |
| Edimax Technology                 | 3         | 0.04%   |
| U-Blox                            | 2         | 0.03%   |
| T & A Mobile Phones               | 2         | 0.03%   |
| Shenzhen Goodix Technology        | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1686      | 18.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 420       | 4.57%   |
| Intel Wi-Fi 6 AX200                                               | 328       | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 235       | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 206       | 2.24%   |
| Intel Wireless 8265 / 8275                                        | 196       | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 176       | 1.91%   |
| Intel Wi-Fi 6 AX201                                               | 168       | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 167       | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 164       | 1.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 160       | 1.74%   |
| Intel Wireless 7260                                               | 156       | 1.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 151       | 1.64%   |
| Intel Wireless 7265                                               | 145       | 1.58%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 143       | 1.56%   |
| Intel Wireless 8260                                               | 122       | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 120       | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 115       | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 112       | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 104       | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 103       | 1.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 87        | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 85        | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                     | 79        | 0.86%   |
| Intel Wireless 3165                                               | 71        | 0.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 69        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 65        | 0.71%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 63        | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 60        | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 58        | 0.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 58        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 57        | 0.62%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 57        | 0.62%   |
| Intel Wireless 3160                                               | 55        | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 53        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 53        | 0.58%   |
| Intel Wireless-AC 9260                                            | 52        | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 52        | 0.57%   |
| Intel Centrino Ultimate-N 6300                                    | 49        | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 47        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2503      | 49.78%  |
| Qualcomm Atheros                      | 901       | 17.92%  |
| Realtek Semiconductor                 | 680       | 13.52%  |
| Broadcom                              | 449       | 8.93%   |
| Broadcom Limited                      | 121       | 2.41%   |
| MediaTek                              | 115       | 2.29%   |
| Ralink                                | 54        | 1.07%   |
| TP-Link                               | 43        | 0.86%   |
| Ralink Technology                     | 39        | 0.78%   |
| Dell                                  | 22        | 0.44%   |
| Sierra Wireless                       | 19        | 0.38%   |
| Qualcomm                              | 17        | 0.34%   |
| NetGear                               | 10        | 0.2%    |
| ASUSTek Computer                      | 10        | 0.2%    |
| D-Link                                | 9         | 0.18%   |
| Hewlett-Packard                       | 6         | 0.12%   |
| Fibocom                               | 4         | 0.08%   |
| Qualcomm Atheros Communications       | 3         | 0.06%   |
| Microsoft                             | 3         | 0.06%   |
| Linksys                               | 3         | 0.06%   |
| Edimax Technology                     | 3         | 0.06%   |
| D-Link System                         | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| ZyDAS                                 | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Chu Yuen Enterprise                   | 1         | 0.02%   |
| Arduino SA                            | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 328       | 6.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 235       | 4.64%   |
| Intel Wireless 8265 / 8275                                     | 196       | 3.87%   |
| Intel Wi-Fi 6 AX201                                            | 168       | 3.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 167       | 3.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 164       | 3.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 160       | 3.16%   |
| Intel Wireless 7260                                            | 156       | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 151       | 2.98%   |
| Intel Wireless 7265                                            | 145       | 2.86%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 143       | 2.82%   |
| Intel Wireless 8260                                            | 122       | 2.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 120       | 2.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 115       | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 112       | 2.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 104       | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 103       | 2.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 87        | 1.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 85        | 1.68%   |
| Broadcom BCM43142 802.11b/g/n                                  | 79        | 1.56%   |
| Intel Wireless 3165                                            | 71        | 1.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 69        | 1.36%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 63        | 1.24%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 58        | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 58        | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 57        | 1.13%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 57        | 1.13%   |
| Intel Wireless 3160                                            | 55        | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 53        | 1.05%   |
| Intel Wireless-AC 9260                                         | 52        | 1.03%   |
| Intel Centrino Ultimate-N 6300                                 | 49        | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 47        | 0.93%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 47        | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 45        | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 43        | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 43        | 0.85%   |
| Intel Centrino Advanced-N 6235                                 | 42        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 39        | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 36        | 0.71%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 33        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2378      | 59.32%  |
| Intel                            | 758       | 18.91%  |
| Qualcomm Atheros                 | 283       | 7.06%   |
| Broadcom                         | 177       | 4.42%   |
| Marvell Technology Group         | 67        | 1.67%   |
| Nvidia                           | 54        | 1.35%   |
| ASIX Electronics                 | 51        | 1.27%   |
| Broadcom Limited                 | 36        | 0.9%    |
| DisplayLink                      | 30        | 0.75%   |
| Lenovo                           | 23        | 0.57%   |
| Xiaomi                           | 20        | 0.5%    |
| Samsung Electronics              | 19        | 0.47%   |
| JMicron Technology               | 17        | 0.42%   |
| Google                           | 14        | 0.35%   |
| OnePlus Technology (Shenzhen)    | 11        | 0.27%   |
| Silicon Integrated Systems [SiS] | 8         | 0.2%    |
| TP-Link                          | 7         | 0.17%   |
| Huawei Technologies              | 7         | 0.17%   |
| OPPO Electronics                 | 6         | 0.15%   |
| Motorola PCS                     | 6         | 0.15%   |
| Apple                            | 5         | 0.12%   |
| Qualcomm                         | 3         | 0.07%   |
| MediaTek                         | 3         | 0.07%   |
| Linksys                          | 3         | 0.07%   |
| T & A Mobile Phones              | 2         | 0.05%   |
| Sierra Wireless                  | 2         | 0.05%   |
| LSI                              | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| ASUSTek Computer                 | 2         | 0.05%   |
| Aquantia                         | 2         | 0.05%   |
| Research In Motion               | 1         | 0.02%   |
| NTmore                           | 1         | 0.02%   |
| NetGear                          | 1         | 0.02%   |
| Microsoft                        | 1         | 0.02%   |
| Foxconn / Hon Hai                | 1         | 0.02%   |
| Cypress Semiconductor            | 1         | 0.02%   |
| Attansic Technology              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1686      | 41.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 420       | 10.35%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 206       | 5.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 176       | 4.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 65        | 1.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 60        | 1.48%   |
| Intel Ethernet Connection I218-LM                                 | 53        | 1.31%   |
| Intel Ethernet Connection I219-LM                                 | 52        | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 46        | 1.13%   |
| Intel Ethernet Connection I217-LM                                 | 46        | 1.13%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 41        | 1.01%   |
| ASIX AX88179 Gigabit Ethernet                                     | 41        | 1.01%   |
| Nvidia MCP79 Ethernet                                             | 40        | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                             | 39        | 0.96%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 36        | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 33        | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 32        | 0.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 31        | 0.76%   |
| Intel Ethernet Connection (4) I219-V                              | 29        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 27        | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 27        | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.64%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 25        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 23        | 0.57%   |
| Intel 82567LM Gigabit Network Connection                          | 21        | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 21        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 20        | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 19        | 0.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 19        | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 0.47%   |
| Intel Ethernet Connection (13) I219-V                             | 19        | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 18        | 0.44%   |
| Intel Ethernet Connection I219-V                                  | 18        | 0.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 18        | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17        | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 17        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.42%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 16        | 0.39%   |
| Intel Ethernet Connection (6) I219-V                              | 16        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4780      | 55.05%  |
| Ethernet | 3831      | 44.12%  |
| Modem    | 59        | 0.68%   |
| Unknown  | 13        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4074      | 79.03%  |
| Ethernet | 1080      | 20.95%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3493      | 72.17%  |
| 1     | 1277      | 26.38%  |
| 0     | 38        | 0.79%   |
| 3     | 32        | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3864      | 78.81%  |
| Yes  | 1039      | 21.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2104      | 51.12%  |
| Qualcomm Atheros Communications | 404       | 9.82%   |
| Realtek Semiconductor           | 351       | 8.53%   |
| Apple                           | 250       | 6.07%   |
| IMC Networks                    | 214       | 5.2%    |
| Broadcom                        | 191       | 4.64%   |
| Lite-On Technology              | 190       | 4.62%   |
| Foxconn / Hon Hai               | 121       | 2.94%   |
| Dell                            | 64        | 1.55%   |
| Cambridge Silicon Radio         | 40        | 0.97%   |
| Toshiba                         | 30        | 0.73%   |
| Realtek                         | 30        | 0.73%   |
| Ralink                          | 28        | 0.68%   |
| Hewlett-Packard                 | 28        | 0.68%   |
| ASUSTek Computer                | 15        | 0.36%   |
| Foxconn International           | 11        | 0.27%   |
| Ralink Technology               | 8         | 0.19%   |
| Alps Electric                   | 7         | 0.17%   |
| Smart Modular Technologies      | 4         | 0.1%    |
| Askey Computer                  | 4         | 0.1%    |
| USI                             | 3         | 0.07%   |
| Taiyo Yuden                     | 3         | 0.07%   |
| Qcom                            | 3         | 0.07%   |
| Opticis                         | 3         | 0.07%   |
| MediaTek                        | 2         | 0.05%   |
| Fujitsu                         | 2         | 0.05%   |
| TP-Link                         | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Actions                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 728       | 17.68%  |
| Intel AX201 Bluetooth                               | 424       | 10.3%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 344       | 8.35%   |
| Intel AX200 Bluetooth                               | 323       | 7.84%   |
| Qualcomm Atheros  Bluetooth Device                  | 274       | 6.65%   |
| Realtek Bluetooth Radio                             | 212       | 5.15%   |
| Apple Bluetooth Host Controller                     | 146       | 3.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 96        | 2.33%   |
| Apple Bluetooth USB Host Controller                 | 73        | 1.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 72        | 1.75%   |
| IMC Networks Bluetooth Radio                        | 70        | 1.7%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 64        | 1.55%   |
| IMC Networks Wireless_Device                        | 54        | 1.31%   |
| Intel AX210 Bluetooth                               | 52        | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 50        | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 47        | 1.14%   |
| Intel Bluetooth Device                              | 47        | 1.14%   |
| IMC Networks Bluetooth Device                       | 45        | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 42        | 1.02%   |
| Lite-On Bluetooth Device                            | 41        | 1%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 40        | 0.97%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 39        | 0.95%   |
| Intel Wireless-AC 3168 Bluetooth                    | 39        | 0.95%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 38        | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 35        | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 31        | 0.75%   |
| Ralink RT3290 Bluetooth                             | 28        | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 24        | 0.58%   |
| Dell DW375 Bluetooth Module                         | 23        | 0.56%   |
| Realtek 802.11ac WLAN Adapter                       | 22        | 0.53%   |
| Lite-On Wireless_Device                             | 21        | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 0.51%   |
| Apple Bluetooth HCI                                 | 20        | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 19        | 0.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 17        | 0.41%   |
| HP Broadcom 2070 Bluetooth Combo                    | 17        | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                    | 15        | 0.36%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.36%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 14        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3834      | 60.67%  |
| Nvidia                               | 1089      | 17.23%  |
| AMD                                  | 988       | 15.64%  |
| C-Media Electronics                  | 49        | 0.78%   |
| Logitech                             | 41        | 0.65%   |
| Realtek Semiconductor                | 39        | 0.62%   |
| Lenovo                               | 20        | 0.32%   |
| JMTek                                | 20        | 0.32%   |
| GN Netcom                            | 19        | 0.3%    |
| Kingston Technology                  | 15        | 0.24%   |
| Apple                                | 14        | 0.22%   |
| Texas Instruments                    | 13        | 0.21%   |
| Generalplus Technology               | 13        | 0.21%   |
| Sony                                 | 11        | 0.17%   |
| Razer USA                            | 10        | 0.16%   |
| Hewlett-Packard                      | 10        | 0.16%   |
| Corsair                              | 10        | 0.16%   |
| SteelSeries ApS                      | 8         | 0.13%   |
| Silicon Integrated Systems [SiS]     | 8         | 0.13%   |
| Plantronics                          | 8         | 0.13%   |
| Focusrite-Novation                   | 5         | 0.08%   |
| Creative Technology                  | 5         | 0.08%   |
| ASUSTek Computer                     | 5         | 0.08%   |
| Sennheiser Communications            | 4         | 0.06%   |
| FiiO Electronics Technology          | 4         | 0.06%   |
| DSEA A/S                             | 4         | 0.06%   |
| Tenx Technology                      | 3         | 0.05%   |
| Samson Technologies                  | 3         | 0.05%   |
| No brand                             | 3         | 0.05%   |
| GYROCOM C&C                          | 3         | 0.05%   |
| Blue Microphones                     | 3         | 0.05%   |
| Yamaha                               | 2         | 0.03%   |
| XMOS                                 | 2         | 0.03%   |
| Turtle Beach                         | 2         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.03%   |
| TerraTec Electronic                  | 2         | 0.03%   |
| Pioneer DJ                           | 2         | 0.03%   |
| CMX Systems                          | 2         | 0.03%   |
| AudioQuest                           | 2         | 0.03%   |
| Astro Gaming                         | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 654       | 8.55%   |
| Intel Sunrise Point-LP HD Audio                                            | 562       | 7.34%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 382       | 4.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 349       | 4.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 300       | 3.92%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 297       | 3.88%   |
| Intel 8 Series HD Audio Controller                                         | 235       | 3.07%   |
| Intel Haswell-ULT HD Audio Controller                                      | 233       | 3.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 223       | 2.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 216       | 2.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 195       | 2.55%   |
| Intel Broadwell-U Audio Controller                                         | 181       | 2.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 174       | 2.27%   |
| Intel Comet Lake PCH cAVS                                                  | 174       | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 160       | 2.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 154       | 2.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 151       | 1.97%   |
| Intel Comet Lake PCH-LP cAVS                                               | 138       | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 133       | 1.74%   |
| Nvidia TU106 High Definition Audio Controller                              | 131       | 1.71%   |
| Intel CM238 HD Audio Controller                                            | 130       | 1.7%    |
| AMD FCH Azalia Controller                                                  | 126       | 1.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 113       | 1.48%   |
| Nvidia GP107GL High Definition Audio Controller                            | 94        | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 90        | 1.18%   |
| Nvidia GA106 High Definition Audio Controller                              | 80        | 1.05%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 80        | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 78        | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                   | 76        | 0.99%   |
| Nvidia GA104 High Definition Audio Controller                              | 70        | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                              | 67        | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 65        | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 59        | 0.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 58        | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 57        | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 51        | 0.67%   |
| Nvidia Audio device                                                        | 50        | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 46        | 0.6%    |
| AMD High Definition Audio Controller                                       | 45        | 0.59%   |
| Nvidia MCP79 High Definition Audio                                         | 44        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 471       | 29.81%  |
| SK hynix            | 358       | 22.66%  |
| Micron Technology   | 212       | 13.42%  |
| Kingston            | 125       | 7.91%   |
| Crucial             | 85        | 5.38%   |
| Unknown             | 54        | 3.42%   |
| A-DATA Technology   | 37        | 2.34%   |
| Smart               | 28        | 1.77%   |
| Ramaxel Technology  | 24        | 1.52%   |
| Corsair             | 21        | 1.33%   |
| Goldkey             | 20        | 1.27%   |
| Neo Forza           | 18        | 1.14%   |
| Elpida              | 18        | 1.14%   |
| G.Skill             | 14        | 0.89%   |
| Unknown (ABCD)      | 11        | 0.7%    |
| Smart Brazil        | 10        | 0.63%   |
| Unknown             | 9         | 0.57%   |
| Team                | 7         | 0.44%   |
| Teikon              | 6         | 0.38%   |
| Nanya Technology    | 6         | 0.38%   |
| Apacer              | 5         | 0.32%   |
| PNY                 | 4         | 0.25%   |
| Patriot             | 3         | 0.19%   |
| High Bridge         | 3         | 0.19%   |
| GSkill              | 3         | 0.19%   |
| Avant               | 3         | 0.19%   |
| Transcend           | 2         | 0.13%   |
| Timetec             | 2         | 0.13%   |
| GOODRAM             | 2         | 0.13%   |
| Gold Key            | 2         | 0.13%   |
| CSX                 | 2         | 0.13%   |
| ChangXin Memory     | 2         | 0.13%   |
| Unknown (8A02)      | 1         | 0.06%   |
| Unknown (898F)      | 1         | 0.06%   |
| Unknown (09B6)      | 1         | 0.06%   |
| Unknown (09A4)      | 1         | 0.06%   |
| Silicon Power       | 1         | 0.06%   |
| RZX                 | 1         | 0.06%   |
| PUSKILL             | 1         | 0.06%   |
| Multilaser          | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 39        | 2.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 27        | 1.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 25        | 1.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 1.39%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 1.15%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 18        | 1.09%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 1.03%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 1.03%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.97%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 0.97%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.91%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.91%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.84%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.72%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 12        | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 11        | 0.66%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.66%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.66%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.6%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 10        | 0.6%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.6%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.6%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.6%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 9         | 0.54%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.54%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 9         | 0.54%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 9         | 0.54%   |
| Unknown                                                          | 9         | 0.54%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.48%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 8         | 0.48%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.48%   |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s             | 8         | 0.48%   |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s         | 8         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 872       | 66.01%  |
| DDR3    | 261       | 19.76%  |
| LPDDR4  | 70        | 5.3%    |
| LPDDR3  | 60        | 4.54%   |
| DDR5    | 22        | 1.67%   |
| LPDDR5  | 18        | 1.36%   |
| DDR2    | 10        | 0.76%   |
| SDRAM   | 4         | 0.3%    |
| Unknown | 4         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1155      | 85.75%  |
| Row Of Chips | 174       | 12.92%  |
| Chip         | 12        | 0.89%   |
| DIMM         | 4         | 0.3%    |
| Unknown      | 2         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 656       | 45.37%  |
| 4096  | 359       | 24.83%  |
| 16384 | 279       | 19.29%  |
| 2048  | 73        | 5.05%   |
| 32768 | 69        | 4.77%   |
| 1024  | 10        | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 413       | 28.68%  |
| 3200    | 344       | 23.89%  |
| 1600    | 206       | 14.31%  |
| 2400    | 135       | 9.38%   |
| 2133    | 86        | 5.97%   |
| 4267    | 34        | 2.36%   |
| 1334    | 29        | 2.01%   |
| 3266    | 25        | 1.74%   |
| 4800    | 22        | 1.53%   |
| 1867    | 22        | 1.53%   |
| 1333    | 21        | 1.46%   |
| 8400    | 18        | 1.25%   |
| 6400    | 18        | 1.25%   |
| 4266    | 12        | 0.83%   |
| 1067    | 11        | 0.76%   |
| 800     | 9         | 0.63%   |
| 3733    | 7         | 0.49%   |
| 1866    | 5         | 0.35%   |
| 2933    | 4         | 0.28%   |
| 667     | 4         | 0.28%   |
| Unknown | 3         | 0.21%   |
| 4199    | 2         | 0.14%   |
| 2048    | 2         | 0.14%   |
| 1066    | 2         | 0.14%   |
| 3466    | 1         | 0.07%   |
| 3400    | 1         | 0.07%   |
| 3333    | 1         | 0.07%   |
| 3000    | 1         | 0.07%   |
| 1200    | 1         | 0.07%   |
| 666     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 30.77%  |
| Seiko Epson         | 5         | 19.23%  |
| Canon               | 4         | 15.38%  |
| Brother Industries  | 4         | 15.38%  |
| Samsung Electronics | 2         | 7.69%   |
| Xerox               | 1         | 3.85%   |
| MIIIW               | 1         | 3.85%   |
| ICS Advent          | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung M2020 Series            | 2         | 7.69%   |
| Xerox B215                      | 1         | 3.85%   |
| Seiko Epson WF-3520 Series      | 1         | 3.85%   |
| Seiko Epson L6160 Series        | 1         | 3.85%   |
| Seiko Epson L3110 Series        | 1         | 3.85%   |
| Seiko Epson L132 Series         | 1         | 3.85%   |
| Seiko Epson ET-2700 Series      | 1         | 3.85%   |
| MIIIW MW Keyboard Air Mini      | 1         | 3.85%   |
| ICS Advent Parallel Adapter     | 1         | 3.85%   |
| HP OfficeJet 3830 series        | 1         | 3.85%   |
| HP Ink Tank Wireless 410 series | 1         | 3.85%   |
| HP ENVY Photo 7800 series       | 1         | 3.85%   |
| HP ENVY 4520 series             | 1         | 3.85%   |
| HP Deskjet 3050 J610 series     | 1         | 3.85%   |
| HP Deskjet 2540 series          | 1         | 3.85%   |
| HP Deskjet 2050 J510            | 1         | 3.85%   |
| HP Color LaserJet CP2025dn      | 1         | 3.85%   |
| Canon PIXMA MX920 Series        | 1         | 3.85%   |
| Canon GX7000 series             | 1         | 3.85%   |
| Canon G4010 series              | 1         | 3.85%   |
| Canon E400 series               | 1         | 3.85%   |
| Brother HL-L2370DW series       | 1         | 3.85%   |
| Brother HL-L2320D series        | 1         | 3.85%   |
| Brother HL-3170CDW series       | 1         | 3.85%   |
| Brother HL-2270DW Laser Printer | 1         | 3.85%   |

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
| Chicony Electronics                    | 1033      | 23.92%  |
| IMC Networks                           | 469       | 10.86%  |
| Microdia                               | 434       | 10.05%  |
| Realtek Semiconductor                  | 359       | 8.31%   |
| Bison Electronics                      | 259       | 6%      |
| Sunplus Innovation Technology          | 240       | 5.56%   |
| Quanta                                 | 218       | 5.05%   |
| Apple                                  | 188       | 4.35%   |
| Acer                                   | 185       | 4.28%   |
| Cheng Uei Precision Industry (Foxlink) | 152       | 3.52%   |
| Suyin                                  | 124       | 2.87%   |
| Syntek                                 | 106       | 2.45%   |
| Lite-On Technology                     | 85        | 1.97%   |
| Luxvisions Innotech Limited            | 66        | 1.53%   |
| Silicon Motion                         | 61        | 1.41%   |
| Logitech                               | 57        | 1.32%   |
| Ricoh                                  | 38        | 0.88%   |
| Alcor Micro                            | 29        | 0.67%   |
| Samsung Electronics                    | 25        | 0.58%   |
| Sonix Technology                       | 19        | 0.44%   |
| SunplusIT                              | 13        | 0.3%    |
| ALi                                    | 13        | 0.3%    |
| Primax Electronics                     | 11        | 0.25%   |
| Z-Star Microelectronics                | 10        | 0.23%   |
| Microsoft                              | 10        | 0.23%   |
| Lenovo                                 | 10        | 0.23%   |
| DigiTech                               | 10        | 0.23%   |
| Importek                               | 9         | 0.21%   |
| Intel                                  | 7         | 0.16%   |
| OmniVision Technologies                | 6         | 0.14%   |
| Generalplus Technology                 | 6         | 0.14%   |
| icSpring                               | 5         | 0.12%   |
| MacroSilicon                           | 4         | 0.09%   |
| Foxconn / Hon Hai                      | 4         | 0.09%   |
| AVerMedia Technologies                 | 4         | 0.09%   |
| Unknown                                | 3         | 0.07%   |
| Tobii Technology AB                    | 3         | 0.07%   |
| Razer USA                              | 3         | 0.07%   |
| Alpha Imaging Technology               | 3         | 0.07%   |
| Sunplus Technology                     | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 233       | 5.37%   |
| Chicony Integrated Camera                           | 199       | 4.59%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 151       | 3.48%   |
| Chicony HD WebCam                                   | 143       | 3.3%    |
| Realtek Integrated_Webcam_HD                        | 139       | 3.2%    |
| IMC Networks Integrated Camera                      | 129       | 2.97%   |
| Chicony USB2.0 Camera                               | 98        | 2.26%   |
| Bison BisonCam,NB Pro                               | 91        | 2.1%    |
| Sunplus Integrated_Webcam_HD                        | 72        | 1.66%   |
| Syntek Integrated Camera                            | 66        | 1.52%   |
| Apple Built-in iSight                               | 62        | 1.43%   |
| Apple FaceTime HD Camera                            | 61        | 1.41%   |
| Quanta HD User Facing                               | 53        | 1.22%   |
| Acer Integrated Camera                              | 51        | 1.18%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 48        | 1.11%   |
| Bison HD Webcam                                     | 47        | 1.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 42        | 0.97%   |
| Microdia Integrated Webcam                          | 34        | 0.78%   |
| Chicony USB 2.0 Camera                              | 34        | 0.78%   |
| Chicony HD User Facing                              | 34        | 0.78%   |
| Lite-On Integrated Camera                           | 33        | 0.76%   |
| Chicony TOSHIBA Web Camera - HD                     | 33        | 0.76%   |
| Quanta HD Webcam                                    | 32        | 0.74%   |
| Chicony Integrated Camera (1280x720@30)             | 32        | 0.74%   |
| Bison Integrated Camera                             | 32        | 0.74%   |
| Sunplus HD WebCam                                   | 31        | 0.71%   |
| Bison SunplusIT Integrated Camera                   | 31        | 0.71%   |
| Sunplus Asus Webcam                                 | 30        | 0.69%   |
| Chicony HP HD Camera                                | 30        | 0.69%   |
| Acer BisonCam, NB Pro                               | 30        | 0.69%   |
| Microdia Laptop_Integrated_Webcam_HD                | 29        | 0.67%   |
| Chicony USB2.0 HD UVC WebCam                        | 29        | 0.67%   |
| Chicony USB2.0 VGA UVC WebCam                       | 28        | 0.65%   |
| Realtek Integrated Webcam                           | 27        | 0.62%   |
| Quanta HP TrueVision HD Camera                      | 25        | 0.58%   |
| Chicony HP TrueVision HD Camera                     | 25        | 0.58%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 24        | 0.55%   |
| Chicony HP Wide Vision HD Camera                    | 24        | 0.55%   |
| Realtek USB Camera                                  | 23        | 0.53%   |
| Acer Lenovo EasyCamera                              | 23        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 256       | 30.44%  |
| Synaptics                          | 256       | 30.44%  |
| Shenzhen Goodix Technology         | 153       | 18.19%  |
| Upek                               | 47        | 5.59%   |
| Elan Microelectronics              | 45        | 5.35%   |
| LighTuning Technology              | 37        | 4.4%    |
| AuthenTec                          | 28        | 3.33%   |
| STMicroelectronics                 | 7         | 0.83%   |
| Focal-systems.Corp                 | 4         | 0.48%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.36%   |
| HOLTEK                             | 3         | 0.36%   |
| Samsung Electronics                | 1         | 0.12%   |
| DigitalPersona                     | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 78        | 9.27%   |
| Shenzhen Goodix  Fingerprint Device                                        | 73        | 8.68%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 58        | 6.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 50        | 5.95%   |
| Shenzhen Goodix FingerPrint                                                | 49        | 5.83%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 43        | 5.11%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 35        | 4.16%   |
| Elan ELAN:Fingerprint                                                      | 34        | 4.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 31        | 3.69%   |
| Synaptics UWP WBDI                                                         | 28        | 3.33%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 2.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 20        | 2.38%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 19        | 2.26%   |
| Validity Sensors Synaptics WBDI                                            | 19        | 2.26%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 19        | 2.26%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.14%   |
| Validity Sensors VFS491                                                    | 18        | 2.14%   |
| Synaptics WBDI Device                                                      | 18        | 2.14%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 17        | 2.02%   |
| Unknown                                                                    | 16        | 1.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.78%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 1.43%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.31%   |
| Elan ELAN:ARM-M4                                                           | 11        | 1.31%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 1.07%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.07%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 1.07%   |
| Synaptics  WBDI                                                            | 8         | 0.95%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 0.95%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 0.95%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 0.83%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.83%   |
| AuthenTec AES2810                                                          | 7         | 0.83%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 0.83%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.71%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.59%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.48%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.48%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.48%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.36%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 151       | 47.63%  |
| Alcor Micro               | 87        | 27.44%  |
| Upek                      | 29        | 9.15%   |
| O2 Micro                  | 24        | 7.57%   |
| Lenovo                    | 17        | 5.36%   |
| Gemalto (was Gemplus)     | 2         | 0.63%   |
| Aladdin Knowledge Systems | 2         | 0.63%   |
| SCM Microsystems          | 1         | 0.32%   |
| OmniKey                   | 1         | 0.32%   |
| Giesecke & Devrient       | 1         | 0.32%   |
| Clay Logic                | 1         | 0.32%   |
| Advanced Card Systems     | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 87        | 27.44%  |
| Broadcom BCM5880 Secure Applications Processor                               | 46        | 14.51%  |
| Broadcom 5880                                                                | 41        | 12.93%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 40        | 12.62%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 9.15%   |
| Broadcom 58200                                                               | 22        | 6.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 20        | 6.31%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 5.36%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.63%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.63%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.32%   |
| OmniKey CardMan 4321                                                         | 1         | 0.32%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.32%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.32%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.32%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.32%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3051      | 61.99%  |
| 1     | 1474      | 29.95%  |
| 2     | 341       | 6.93%   |
| 3     | 50        | 1.02%   |
| 4     | 5         | 0.1%    |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 820       | 36.43%  |
| Chipcard                 | 309       | 13.73%  |
| Multimedia controller    | 308       | 13.68%  |
| Graphics card            | 277       | 12.31%  |
| Net/wireless             | 262       | 11.64%  |
| Bluetooth                | 66        | 2.93%   |
| Camera                   | 51        | 2.27%   |
| Storage                  | 38        | 1.69%   |
| Net/ethernet             | 28        | 1.24%   |
| Sound                    | 24        | 1.07%   |
| Card reader              | 18        | 0.8%    |
| Communication controller | 15        | 0.67%   |
| Network                  | 11        | 0.49%   |
| Modem                    | 10        | 0.44%   |
| Storage/ide              | 5         | 0.22%   |
| Storage/nvme             | 3         | 0.13%   |
| Flash memory             | 2         | 0.09%   |
| Firewire controller      | 2         | 0.09%   |
| Unclassified device      | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

