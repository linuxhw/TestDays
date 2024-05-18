Linux in Uruguay - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Uruguay.

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

Total: 267

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Google        | Phaser                      | [feb45bf2a2](https://linux-hardware.org/?probe=feb45bf2a2) | May 02, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [859396f855](https://linux-hardware.org/?probe=859396f855) | Apr 30, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | [4d6a9bb700](https://linux-hardware.org/?probe=4d6a9bb700) | Apr 12, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e108ca29d2](https://linux-hardware.org/?probe=e108ca29d2) | Apr 12, 2024 |
| HP            | Presario V6000 (GH918EA#... | [19c9124453](https://linux-hardware.org/?probe=19c9124453) | Apr 10, 2024 |
| MSI           | Unknown                     | [a975d469da](https://linux-hardware.org/?probe=a975d469da) | Mar 19, 2024 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [0e8d4b681b](https://linux-hardware.org/?probe=0e8d4b681b) | Mar 11, 2024 |
| HP            | Pavilion Sleekbook 14 PC    | [225e16d7af](https://linux-hardware.org/?probe=225e16d7af) | Mar 05, 2024 |
| Valve         | Jupiter                     | [30c94fd159](https://linux-hardware.org/?probe=30c94fd159) | Feb 29, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [0973b9cfb2](https://linux-hardware.org/?probe=0973b9cfb2) | Feb 29, 2024 |
| Lenovo        | G480 20156                  | [8ffe1342b1](https://linux-hardware.org/?probe=8ffe1342b1) | Feb 16, 2024 |
| Acer          | Aspire A315-59              | [51886537be](https://linux-hardware.org/?probe=51886537be) | Feb 09, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1fcf02a6c3](https://linux-hardware.org/?probe=1fcf02a6c3) | Feb 06, 2024 |
| HP            | Stream Laptop 14-ax0XX      | [d83dd7b361](https://linux-hardware.org/?probe=d83dd7b361) | Feb 05, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [33e55cd5c5](https://linux-hardware.org/?probe=33e55cd5c5) | Feb 03, 2024 |
| HP            | Laptop 15-bw0xx             | [118dcfd484](https://linux-hardware.org/?probe=118dcfd484) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [88f29ebedf](https://linux-hardware.org/?probe=88f29ebedf) | Jan 24, 2024 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [da8a8d5994](https://linux-hardware.org/?probe=da8a8d5994) | Dec 28, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [418992da4d](https://linux-hardware.org/?probe=418992da4d) | Dec 27, 2023 |
| Dell          | Inspiron 1564               | [a1945990cc](https://linux-hardware.org/?probe=a1945990cc) | Dec 24, 2023 |
| Dell          | Inspiron 1564               | [e02428db4a](https://linux-hardware.org/?probe=e02428db4a) | Dec 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [0f2cad4391](https://linux-hardware.org/?probe=0f2cad4391) | Dec 22, 2023 |
| Standard      | SF20BA2                     | [431580b18d](https://linux-hardware.org/?probe=431580b18d) | Dec 19, 2023 |
| HP            | Pavilion Notebook           | [81baeeb4c6](https://linux-hardware.org/?probe=81baeeb4c6) | Dec 12, 2023 |
| ASUSTek       | UX305CA                     | [6bac81f943](https://linux-hardware.org/?probe=6bac81f943) | Dec 06, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [248ac55d99](https://linux-hardware.org/?probe=248ac55d99) | Nov 29, 2023 |
| HP            | Laptop 15-dy2xxx            | [858c641fcf](https://linux-hardware.org/?probe=858c641fcf) | Nov 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [2188d0c4b8](https://linux-hardware.org/?probe=2188d0c4b8) | Nov 25, 2023 |
| Samsung       | 550P5C/550P7C               | [b7294ed55c](https://linux-hardware.org/?probe=b7294ed55c) | Nov 20, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [eb4b6a5c65](https://linux-hardware.org/?probe=eb4b6a5c65) | Nov 15, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [339062b95b](https://linux-hardware.org/?probe=339062b95b) | Nov 15, 2023 |
| Lenovo        | ThinkPad T420 42361H7       | [0f1bd55fbf](https://linux-hardware.org/?probe=0f1bd55fbf) | Nov 09, 2023 |
| Razer         | Blade                       | [e9ad529ed4](https://linux-hardware.org/?probe=e9ad529ed4) | Nov 01, 2023 |
| HP            | Laptop 14-ck0xxx            | [8ef0f47332](https://linux-hardware.org/?probe=8ef0f47332) | Oct 20, 2023 |
| GPU Compan... | GWTN156-2BK                 | [f4eec82fb9](https://linux-hardware.org/?probe=f4eec82fb9) | Oct 09, 2023 |
| Razer         | Blade                       | [b3b2eb7db8](https://linux-hardware.org/?probe=b3b2eb7db8) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4398558915](https://linux-hardware.org/?probe=4398558915) | Sep 19, 2023 |
| ASUSTek       | X542UQ                      | [6793d8c052](https://linux-hardware.org/?probe=6793d8c052) | Sep 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [a51361ebb2](https://linux-hardware.org/?probe=a51361ebb2) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [00cbde2fb9](https://linux-hardware.org/?probe=00cbde2fb9) | Sep 12, 2023 |
| GPU Compan... | GWTN156-9                   | [4c8ea16ab2](https://linux-hardware.org/?probe=4c8ea16ab2) | Aug 30, 2023 |
| Chuwi         | GemiBook Pro                | [62b31c86bb](https://linux-hardware.org/?probe=62b31c86bb) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [a435538cb2](https://linux-hardware.org/?probe=a435538cb2) | Aug 20, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [0dc75dae26](https://linux-hardware.org/?probe=0dc75dae26) | Aug 18, 2023 |
| HP            | 14                          | [8692626574](https://linux-hardware.org/?probe=8692626574) | Aug 09, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [46ca3ef1f4](https://linux-hardware.org/?probe=46ca3ef1f4) | Aug 01, 2023 |
| HP            | Laptop 15-dy2xxx            | [bbe4e49261](https://linux-hardware.org/?probe=bbe4e49261) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [d16a211675](https://linux-hardware.org/?probe=d16a211675) | Jul 21, 2023 |
| Dell          | Latitude E5420              | [be15c1e3d1](https://linux-hardware.org/?probe=be15c1e3d1) | Jul 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [0fc498ccfb](https://linux-hardware.org/?probe=0fc498ccfb) | Jul 06, 2023 |
| Acer          | Aspire E1-571               | [d0258b4ca5](https://linux-hardware.org/?probe=d0258b4ca5) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [ad76ecf5a9](https://linux-hardware.org/?probe=ad76ecf5a9) | Jul 01, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [b8bab5a2e6](https://linux-hardware.org/?probe=b8bab5a2e6) | Jul 01, 2023 |
| Acer          | One S1002                   | [f7b8d25603](https://linux-hardware.org/?probe=f7b8d25603) | Jun 21, 2023 |
| Fujitsu       | LIFEBOOK E734               | [3742e80123](https://linux-hardware.org/?probe=3742e80123) | Jun 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [3cfa2bccb7](https://linux-hardware.org/?probe=3cfa2bccb7) | Jun 08, 2023 |
| HP            | Pavilion g6                 | [12b1174ce8](https://linux-hardware.org/?probe=12b1174ce8) | Jun 08, 2023 |
| Toshiba       | Satellite C645D             | [085994472d](https://linux-hardware.org/?probe=085994472d) | May 28, 2023 |
| HP            | Stream Notebook             | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Apple         | MacBookPro9,2               | [6855a79270](https://linux-hardware.org/?probe=6855a79270) | May 23, 2023 |
| Acer          | Aspire 4315                 | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [7af74c5864](https://linux-hardware.org/?probe=7af74c5864) | May 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [0fd753db6d](https://linux-hardware.org/?probe=0fd753db6d) | May 16, 2023 |
| HP            | Notebook                    | [c14e7a41cf](https://linux-hardware.org/?probe=c14e7a41cf) | May 13, 2023 |
| HP            | Notebook                    | [726fa4fcd1](https://linux-hardware.org/?probe=726fa4fcd1) | May 13, 2023 |
| Dell          | Latitude 5530               | [ade218e4fa](https://linux-hardware.org/?probe=ade218e4fa) | May 11, 2023 |
| Toshiba       | Satellite L45-B             | [8f1db96b6f](https://linux-hardware.org/?probe=8f1db96b6f) | Apr 29, 2023 |
| HP            | 240 G4                      | [997e6e6a0b](https://linux-hardware.org/?probe=997e6e6a0b) | Apr 24, 2023 |
| HP            | 240 G4                      | [887b406c56](https://linux-hardware.org/?probe=887b406c56) | Apr 22, 2023 |
| Standard      | SF20BA2                     | [17763324b6](https://linux-hardware.org/?probe=17763324b6) | Apr 08, 2023 |
| Intel         | EF20                        | [120257faca](https://linux-hardware.org/?probe=120257faca) | Apr 04, 2023 |
| Acer          | Aspire 4315                 | [0bf18c8c90](https://linux-hardware.org/?probe=0bf18c8c90) | Mar 26, 2023 |
| Toshiba       | Satellite C75D-B            | [1ff56ed31f](https://linux-hardware.org/?probe=1ff56ed31f) | Mar 19, 2023 |
| Dell          | Latitude 7310               | [6b5de5fe3c](https://linux-hardware.org/?probe=6b5de5fe3c) | Mar 17, 2023 |
| Standard      | SF20BA                      | [e85dc022b5](https://linux-hardware.org/?probe=e85dc022b5) | Mar 15, 2023 |
| HP            | Laptop 17-ak0xx             | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| HP            | EliteBook 840 G3            | [41bf4fb877](https://linux-hardware.org/?probe=41bf4fb877) | Mar 10, 2023 |
| Dell          | Latitude 3150               | [f1554a5df0](https://linux-hardware.org/?probe=f1554a5df0) | Mar 05, 2023 |
| Acer          | Swift SF314-54              | [62defb89e3](https://linux-hardware.org/?probe=62defb89e3) | Mar 02, 2023 |
| ECS           | SF20PA2                     | [f0ad83686f](https://linux-hardware.org/?probe=f0ad83686f) | Feb 21, 2023 |
| HP            | 15 Notebook PC              | [c5256638eb](https://linux-hardware.org/?probe=c5256638eb) | Feb 20, 2023 |
| Lenovo        | ThinkPad P50 20EQS14H00     | [de5c7ac3f6](https://linux-hardware.org/?probe=de5c7ac3f6) | Feb 19, 2023 |
| Unknown       | Unknown                     | [e8183bc042](https://linux-hardware.org/?probe=e8183bc042) | Feb 16, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| ECS           | SF20PA2                     | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Gateway       | LT41P                       | [1684d937e7](https://linux-hardware.org/?probe=1684d937e7) | Feb 02, 2023 |
| HP            | 3115-AEC13432GR1            | [98eb70341a](https://linux-hardware.org/?probe=98eb70341a) | Jan 30, 2023 |
| Valve         | Jupiter                     | [4bda80131d](https://linux-hardware.org/?probe=4bda80131d) | Jan 15, 2023 |
| Valve         | Jupiter                     | [dc137d0d08](https://linux-hardware.org/?probe=dc137d0d08) | Jan 09, 2023 |
| Toshiba       | Satellite C75D-B            | [d5380976a2](https://linux-hardware.org/?probe=d5380976a2) | Jan 03, 2023 |
| Toshiba       | Satellite C75D-B            | [04282775ba](https://linux-hardware.org/?probe=04282775ba) | Dec 24, 2022 |
| ECS           | SF20PA2                     | [2e0892ec48](https://linux-hardware.org/?probe=2e0892ec48) | Nov 18, 2022 |
| Acer          | Aspire one 1-431            | [c27978fdc4](https://linux-hardware.org/?probe=c27978fdc4) | Nov 18, 2022 |
| Apple         | MacBookPro9,2               | [e974c2ceff](https://linux-hardware.org/?probe=e974c2ceff) | Nov 12, 2022 |
| Alienware     | 14                          | [0c11295ebe](https://linux-hardware.org/?probe=0c11295ebe) | Nov 03, 2022 |
| Toshiba       | Satellite L45-B             | [e2f30e0f1e](https://linux-hardware.org/?probe=e2f30e0f1e) | Oct 26, 2022 |
| HP            | Laptop 17-ak0xx             | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Acer          | Aspire ES1-572              | [1bd18c9a15](https://linux-hardware.org/?probe=1bd18c9a15) | Oct 04, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [5e91cc6f07](https://linux-hardware.org/?probe=5e91cc6f07) | Sep 21, 2022 |
| Toshiba       | Satellite C855              | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| Dell          | Latitude 3150               | [6bc88c696c](https://linux-hardware.org/?probe=6bc88c696c) | Sep 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| ECS           | SF20PA2                     | [67dd8af18f](https://linux-hardware.org/?probe=67dd8af18f) | Aug 23, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| Gateway       | NV55C                       | [cc3c8d23e4](https://linux-hardware.org/?probe=cc3c8d23e4) | Aug 03, 2022 |
| Dell          | Latitude 3150               | [aecf1fe543](https://linux-hardware.org/?probe=aecf1fe543) | Aug 01, 2022 |
| HP            | Laptop 14-dk1xxx            | [4eb7e0d085](https://linux-hardware.org/?probe=4eb7e0d085) | Jul 22, 2022 |
| GPU Compan... | GWTN156-9                   | [df5c4b480d](https://linux-hardware.org/?probe=df5c4b480d) | Jul 15, 2022 |
| Acer          | Swift SF314-54              | [47420af7dc](https://linux-hardware.org/?probe=47420af7dc) | Jun 23, 2022 |
| iClever       | IC-T01                      | [f82c34c612](https://linux-hardware.org/?probe=f82c34c612) | Jun 17, 2022 |
| HP            | Pavilion g4                 | [193875edcc](https://linux-hardware.org/?probe=193875edcc) | Jun 15, 2022 |
| Acer          | Swift SF314-54              | [06bccc3696](https://linux-hardware.org/?probe=06bccc3696) | Jun 14, 2022 |
| Dell          | XPS 15 7590                 | [482ed9f535](https://linux-hardware.org/?probe=482ed9f535) | May 29, 2022 |
| Acer          | Swift SF314-54              | [39f85b46d7](https://linux-hardware.org/?probe=39f85b46d7) | May 23, 2022 |
| Acer          | Swift SF314-54              | [fc1233f258](https://linux-hardware.org/?probe=fc1233f258) | May 22, 2022 |
| Acer          | Swift SF314-54              | [478550abf1](https://linux-hardware.org/?probe=478550abf1) | May 21, 2022 |
| Acer          | Swift SF314-54              | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| Acer          | Swift SF314-54              | [cc3411e0b4](https://linux-hardware.org/?probe=cc3411e0b4) | May 10, 2022 |
| HP            | Laptop 14-dk1xxx            | [fa6da4906f](https://linux-hardware.org/?probe=fa6da4906f) | May 07, 2022 |
| Toshiba       | Satellite C645D             | [53153cb65d](https://linux-hardware.org/?probe=53153cb65d) | May 04, 2022 |
| Acer          | Aspire ES1-572              | [25f9b83c30](https://linux-hardware.org/?probe=25f9b83c30) | Apr 28, 2022 |
| Lenovo        | B50-45 20388                | [7ad45f257f](https://linux-hardware.org/?probe=7ad45f257f) | Apr 20, 2022 |
| HP            | EliteBook 840 G1            | [d2e2811388](https://linux-hardware.org/?probe=d2e2811388) | Apr 20, 2022 |
| Dell          | Inspiron 5585               | [2c6e96d91f](https://linux-hardware.org/?probe=2c6e96d91f) | Apr 18, 2022 |
| Dell          | Inspiron 15-3567            | [73be944f6c](https://linux-hardware.org/?probe=73be944f6c) | Apr 14, 2022 |
| Dell          | Precision 7550              | [4619da9502](https://linux-hardware.org/?probe=4619da9502) | Apr 14, 2022 |
| Lenovo        | G405 20239                  | [ab55cb1e13](https://linux-hardware.org/?probe=ab55cb1e13) | Apr 13, 2022 |
| HP            | Laptop 14-dq1xxx            | [7d203f8bc0](https://linux-hardware.org/?probe=7d203f8bc0) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| HP            | Laptop 14-dq1xxx            | [9bf7ed495b](https://linux-hardware.org/?probe=9bf7ed495b) | Mar 28, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [d9afd858b4](https://linux-hardware.org/?probe=d9afd858b4) | Mar 23, 2022 |
| HP            | ZBook 14u G4                | [cc637b12de](https://linux-hardware.org/?probe=cc637b12de) | Mar 10, 2022 |
| HP            | Pavilion dv5                | [81371d4535](https://linux-hardware.org/?probe=81371d4535) | Mar 04, 2022 |
| GPU Compan... | GWTN156-4                   | [89e7b9fa39](https://linux-hardware.org/?probe=89e7b9fa39) | Mar 02, 2022 |
| ECS           | SF20PA2                     | [3bddc7e08a](https://linux-hardware.org/?probe=3bddc7e08a) | Feb 11, 2022 |
| MSI           | GS63VR 6RF                  | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Sony          | SVF14211CLB                 | [d25b1846ff](https://linux-hardware.org/?probe=d25b1846ff) | Dec 07, 2021 |
| Sony          | SVF14211CLB                 | [41bfe6e292](https://linux-hardware.org/?probe=41bfe6e292) | Dec 06, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [a664218f29](https://linux-hardware.org/?probe=a664218f29) | Nov 28, 2021 |
| Acer          | Aspire 5733Z                | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Acer          | Swift SF314-54              | [b506625dc2](https://linux-hardware.org/?probe=b506625dc2) | Nov 05, 2021 |
| Acer          | Swift SF314-54              | [4e606c817f](https://linux-hardware.org/?probe=4e606c817f) | Nov 04, 2021 |
| Samsung       | N102SP/N100SP/N101SP        | [c04d448530](https://linux-hardware.org/?probe=c04d448530) | Oct 21, 2021 |
| Lenovo        | B51-30 80LK                 | [dea10156c6](https://linux-hardware.org/?probe=dea10156c6) | Sep 20, 2021 |
| Haitech       | H7141A                      | [496c0eb316](https://linux-hardware.org/?probe=496c0eb316) | Sep 18, 2021 |
| ECS           | SF20PA2                     | [6d17cf08ad](https://linux-hardware.org/?probe=6d17cf08ad) | Sep 12, 2021 |
| Panasonic     | CF-31JEGAX1M                | [c5acecef3a](https://linux-hardware.org/?probe=c5acecef3a) | Aug 22, 2021 |
| Lenovo        | ThinkPad L490 20Q6S0NF00    | [a8f222614b](https://linux-hardware.org/?probe=a8f222614b) | Aug 11, 2021 |
| Lenovo        | ThinkPad T450 20BUS0G91F    | [8db659cf12](https://linux-hardware.org/?probe=8db659cf12) | Aug 09, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CDS02... | [4781e962e7](https://linux-hardware.org/?probe=4781e962e7) | Aug 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| HP            | Pavilion 15                 | [ec0019224a](https://linux-hardware.org/?probe=ec0019224a) | Jul 28, 2021 |
| ECS           | SF20PA2                     | [2016dfe42c](https://linux-hardware.org/?probe=2016dfe42c) | Jul 26, 2021 |
| HP            | Laptop 15-bs0xx             | [c84d445008](https://linux-hardware.org/?probe=c84d445008) | Jul 18, 2021 |
| Acer          | Aspire E5-521               | [d4629ecbed](https://linux-hardware.org/?probe=d4629ecbed) | Jul 18, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| HP            | Laptop 15-bs0xx             | [27582e9e17](https://linux-hardware.org/?probe=27582e9e17) | Jun 21, 2021 |
| Acer          | TravelMate 5730             | [4a21735ce1](https://linux-hardware.org/?probe=4a21735ce1) | Jun 17, 2021 |
| Acer          | Acadia V1.45                | [9357025bc9](https://linux-hardware.org/?probe=9357025bc9) | Jun 01, 2021 |
| HP            | ENVY TS 15                  | [8369c42ce2](https://linux-hardware.org/?probe=8369c42ce2) | May 31, 2021 |
| Positivo      | Serie AT300                 | [38a0173a4a](https://linux-hardware.org/?probe=38a0173a4a) | May 28, 2021 |
| HP            | Pavilion 17                 | [f12450cc62](https://linux-hardware.org/?probe=f12450cc62) | May 28, 2021 |
| Lenovo        | ThinkPad T590 20N5S2GP05    | [2444839350](https://linux-hardware.org/?probe=2444839350) | May 25, 2021 |
| Dell          | Latitude E5470              | [212d434e24](https://linux-hardware.org/?probe=212d434e24) | May 25, 2021 |
| Positivo      | Serie AT300                 | [a021ecf0dd](https://linux-hardware.org/?probe=a021ecf0dd) | May 24, 2021 |
| Acer          | Aspire 5715Z                | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Toshiba       | Satellite C45-A             | [cb57bbefd0](https://linux-hardware.org/?probe=cb57bbefd0) | May 22, 2021 |
| Toshiba       | Satellite C45-A             | [297e5b458a](https://linux-hardware.org/?probe=297e5b458a) | May 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [883f67612b](https://linux-hardware.org/?probe=883f67612b) | May 19, 2021 |
| Standard      | SF20BA2                     | [e0fdbc36a2](https://linux-hardware.org/?probe=e0fdbc36a2) | May 16, 2021 |
| Acer          | Acadia V1.45                | [321e5159ac](https://linux-hardware.org/?probe=321e5159ac) | May 15, 2021 |
| ECS           | SF20PA2                     | [f3cc58b0e4](https://linux-hardware.org/?probe=f3cc58b0e4) | May 13, 2021 |
| Dell          | Inspiron N5110              | [6f67fbb9d4](https://linux-hardware.org/?probe=6f67fbb9d4) | May 08, 2021 |
| ECS           | SF20PA2                     | [cfbd36f40b](https://linux-hardware.org/?probe=cfbd36f40b) | May 07, 2021 |
| Acer          | Aspire E5-521               | [d1c6c7309a](https://linux-hardware.org/?probe=d1c6c7309a) | May 03, 2021 |
| ASUSTek       | N46VJ                       | [0d6e007969](https://linux-hardware.org/?probe=0d6e007969) | Apr 28, 2021 |
| Standard      | SF20BA2                     | [d51e9f653f](https://linux-hardware.org/?probe=d51e9f653f) | Apr 26, 2021 |
| Standard      | SF20BA2                     | [a568b21782](https://linux-hardware.org/?probe=a568b21782) | Apr 23, 2021 |
| Standard      | SF20BA2                     | [e454415213](https://linux-hardware.org/?probe=e454415213) | Apr 23, 2021 |
| Lenovo        | G50-70 20351                | [44e6cc36ce](https://linux-hardware.org/?probe=44e6cc36ce) | Apr 20, 2021 |
| Lenovo        | V15-ADA 82C7                | [9065c52996](https://linux-hardware.org/?probe=9065c52996) | Apr 17, 2021 |
| Dell          | Inspiron 5565               | [8f75eda1de](https://linux-hardware.org/?probe=8f75eda1de) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [4e23f3b6b5](https://linux-hardware.org/?probe=4e23f3b6b5) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [18ee0d2d64](https://linux-hardware.org/?probe=18ee0d2d64) | Apr 16, 2021 |
| HP            | 240 G7                      | [721c4c3dbd](https://linux-hardware.org/?probe=721c4c3dbd) | Apr 14, 2021 |
| Apple         | MacBookAir7,1               | [2296b37506](https://linux-hardware.org/?probe=2296b37506) | Apr 12, 2021 |
| Acer          | Aspire 5715Z                | [9a7aa83895](https://linux-hardware.org/?probe=9a7aa83895) | Apr 07, 2021 |
| Acer          | Aspire 5715Z                | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [118abf533e](https://linux-hardware.org/?probe=118abf533e) | Mar 28, 2021 |
| Panasonic     | CF-31JEGAX1M                | [4636e611d8](https://linux-hardware.org/?probe=4636e611d8) | Mar 14, 2021 |
| MSI           | GL65 Leopard 10SCXR         | [8497db47ab](https://linux-hardware.org/?probe=8497db47ab) | Mar 09, 2021 |
| HP            | Laptop 14-df0xxx            | [c1d21b6940](https://linux-hardware.org/?probe=c1d21b6940) | Mar 01, 2021 |
| Dell          | XPS 13 9370                 | [f51dac04a1](https://linux-hardware.org/?probe=f51dac04a1) | Feb 17, 2021 |
| Dell          | XPS 13 9370                 | [bea8cc11d5](https://linux-hardware.org/?probe=bea8cc11d5) | Feb 17, 2021 |
| MSI           | GL65 Leopard 10SCXR         | [ac71737361](https://linux-hardware.org/?probe=ac71737361) | Jan 16, 2021 |
| Acer          | Aspire 5733                 | [1f4e4d7fbc](https://linux-hardware.org/?probe=1f4e4d7fbc) | Jan 08, 2021 |
| Toshiba       | Satellite L55t-B            | [ab3b576bd1](https://linux-hardware.org/?probe=ab3b576bd1) | Jan 07, 2021 |
| Toshiba       | Satellite L55t-B            | [6fc9533a15](https://linux-hardware.org/?probe=6fc9533a15) | Jan 06, 2021 |
| ECS           | SF20PA2                     | [f26e0bf23f](https://linux-hardware.org/?probe=f26e0bf23f) | Jan 04, 2021 |
| HP            | 2000                        | [99481f08e3](https://linux-hardware.org/?probe=99481f08e3) | Dec 31, 2020 |
| Panasonic     | CF-31JEGAX1M                | [c0745f5a94](https://linux-hardware.org/?probe=c0745f5a94) | Dec 31, 2020 |
| HP            | Notebook                    | [213a94eab7](https://linux-hardware.org/?probe=213a94eab7) | Dec 28, 2020 |
| HP            | Notebook                    | [bb3749dd61](https://linux-hardware.org/?probe=bb3749dd61) | Dec 28, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f55e2642ef](https://linux-hardware.org/?probe=f55e2642ef) | Dec 15, 2020 |
| Toshiba       | Satellite C75D-C            | [f158fc821a](https://linux-hardware.org/?probe=f158fc821a) | Nov 10, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [5a8d4603be](https://linux-hardware.org/?probe=5a8d4603be) | Nov 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [19081a3c58](https://linux-hardware.org/?probe=19081a3c58) | Oct 27, 2020 |
| Dell          | Latitude E6430              | [8ea63ec090](https://linux-hardware.org/?probe=8ea63ec090) | Oct 23, 2020 |
| HP            | Pavilion dm4                | [21a3ef42e0](https://linux-hardware.org/?probe=21a3ef42e0) | Oct 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [64e95b4174](https://linux-hardware.org/?probe=64e95b4174) | Oct 10, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ffffb855b](https://linux-hardware.org/?probe=0ffffb855b) | Oct 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7ddfb80220](https://linux-hardware.org/?probe=7ddfb80220) | Oct 04, 2020 |
| Toshiba       | Satellite C75D-C            | [12c65e3222](https://linux-hardware.org/?probe=12c65e3222) | Sep 25, 2020 |
| MSI           | GE62 6QD                    | [cf444064fc](https://linux-hardware.org/?probe=cf444064fc) | Sep 03, 2020 |
| HP            | Casablanca H710             | [2061828542](https://linux-hardware.org/?probe=2061828542) | Aug 26, 2020 |
| HP            | Casablanca H710             | [f566c52ffd](https://linux-hardware.org/?probe=f566c52ffd) | Aug 26, 2020 |
| Samsung       | NC208/NC108                 | [f425b1dc48](https://linux-hardware.org/?probe=f425b1dc48) | Aug 17, 2020 |
| Samsung       | NC208/NC108                 | [759ee832fb](https://linux-hardware.org/?probe=759ee832fb) | Aug 17, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3c55f58986](https://linux-hardware.org/?probe=3c55f58986) | Jul 03, 2020 |
| HP            | Presario CQ43               | [bba4f49ed1](https://linux-hardware.org/?probe=bba4f49ed1) | Jun 23, 2020 |
| Acer          | Aspire A715-72G             | [70acf4ea22](https://linux-hardware.org/?probe=70acf4ea22) | Jun 18, 2020 |
| HP            | Presario CQ43               | [3af51e5df2](https://linux-hardware.org/?probe=3af51e5df2) | Jun 13, 2020 |
| ECS           | SF20PA2                     | [fc1653c118](https://linux-hardware.org/?probe=fc1653c118) | Jun 10, 2020 |
| Dell          | Inspiron 5748               | [d7010adabe](https://linux-hardware.org/?probe=d7010adabe) | Jun 09, 2020 |
| OEM           | V40SI2                      | [e2ad8d9479](https://linux-hardware.org/?probe=e2ad8d9479) | Jun 06, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [13b3a46069](https://linux-hardware.org/?probe=13b3a46069) | May 27, 2020 |
| ASUSTek       | X555LAB                     | [7e4107b1b4](https://linux-hardware.org/?probe=7e4107b1b4) | May 26, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [7e4e3c078f](https://linux-hardware.org/?probe=7e4e3c078f) | May 20, 2020 |
| MSI           | GL63 8RD                    | [7e41ab8d71](https://linux-hardware.org/?probe=7e41ab8d71) | May 15, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [3b397b64f7](https://linux-hardware.org/?probe=3b397b64f7) | May 06, 2020 |
| HP            | Laptop 15-bs0xx             | [a9832cd92e](https://linux-hardware.org/?probe=a9832cd92e) | May 05, 2020 |
| HP            | Laptop 15-bs0xx             | [a8857822b2](https://linux-hardware.org/?probe=a8857822b2) | May 03, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [8609a3503d](https://linux-hardware.org/?probe=8609a3503d) | May 02, 2020 |
| HP            | Laptop 15-bs0xx             | [7fdc3c7af9](https://linux-hardware.org/?probe=7fdc3c7af9) | May 02, 2020 |
| Lenovo        | ThinkPad X240 20AMS72901    | [ad1e10654b](https://linux-hardware.org/?probe=ad1e10654b) | Apr 30, 2020 |
| Standard      | EF20EA                      | [11882357e0](https://linux-hardware.org/?probe=11882357e0) | Apr 26, 2020 |
| Dell          | Inspiron N5110              | [3be039900b](https://linux-hardware.org/?probe=3be039900b) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | [cf6e400de0](https://linux-hardware.org/?probe=cf6e400de0) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | [bb8bd669f6](https://linux-hardware.org/?probe=bb8bd669f6) | Apr 17, 2020 |
| Dell          | Inspiron N5110              | [f1caefcea5](https://linux-hardware.org/?probe=f1caefcea5) | Apr 17, 2020 |
| HP            | 620                         | [812b274fd4](https://linux-hardware.org/?probe=812b274fd4) | Apr 13, 2020 |
| HP            | 620                         | [ca26b96168](https://linux-hardware.org/?probe=ca26b96168) | Apr 13, 2020 |
| ECS           | SF20PA2                     | [d685560200](https://linux-hardware.org/?probe=d685560200) | Feb 01, 2020 |
| ECS           | SF20PA2                     | [e6212ece14](https://linux-hardware.org/?probe=e6212ece14) | Nov 27, 2019 |
| ECS           | SF20PA2                     | [1d4a07f181](https://linux-hardware.org/?probe=1d4a07f181) | Nov 19, 2019 |
| Toshiba       | Satellite C55-B             | [1fab0cb871](https://linux-hardware.org/?probe=1fab0cb871) | Nov 16, 2019 |
| ECS           | SF20PA2                     | [063490d972](https://linux-hardware.org/?probe=063490d972) | Nov 03, 2019 |
| HP            | Laptop 14-dk0xxx            | [623c96ec6e](https://linux-hardware.org/?probe=623c96ec6e) | Oct 07, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | [0925f5642c](https://linux-hardware.org/?probe=0925f5642c) | Sep 24, 2019 |
| ECS           | SF20PA2                     | [3c9b29c0c7](https://linux-hardware.org/?probe=3c9b29c0c7) | Sep 20, 2019 |
| ECS           | SF20PA2                     | [6d35e092fa](https://linux-hardware.org/?probe=6d35e092fa) | Sep 16, 2019 |
| Dell          | Inspiron 13-5368            | [0dab5b3510](https://linux-hardware.org/?probe=0dab5b3510) | Sep 15, 2019 |
| ECS           | SF20PA2                     | [80d3b6b8cf](https://linux-hardware.org/?probe=80d3b6b8cf) | Aug 04, 2019 |
| ECS           | SF20PA2                     | [a7b095e2f0](https://linux-hardware.org/?probe=a7b095e2f0) | Jul 30, 2019 |
| ECS           | SF20PA2                     | [01cad0b14a](https://linux-hardware.org/?probe=01cad0b14a) | Jul 10, 2019 |
| Acer          | TravelMate P249-G2-M        | [0e1338db33](https://linux-hardware.org/?probe=0e1338db33) | Jul 01, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [08c0f291e9](https://linux-hardware.org/?probe=08c0f291e9) | Jun 13, 2019 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | [5619d594fa](https://linux-hardware.org/?probe=5619d594fa) | Jun 10, 2019 |
| Dell          | Inspiron N5040              | [b8f0a4691d](https://linux-hardware.org/?probe=b8f0a4691d) | May 17, 2019 |
| Samsung       | 700T                        | [dcf693f16f](https://linux-hardware.org/?probe=dcf693f16f) | May 11, 2019 |
| HP            | Pavilion dv6                | [36299cef92](https://linux-hardware.org/?probe=36299cef92) | Apr 17, 2019 |
| HP            | Laptop 15-db0xxx            | [b26531074c](https://linux-hardware.org/?probe=b26531074c) | Apr 16, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [7d9905cfe7](https://linux-hardware.org/?probe=7d9905cfe7) | Mar 27, 2019 |
| ASUSTek       | TP300LAB                    | [538b5e5d24](https://linux-hardware.org/?probe=538b5e5d24) | Mar 26, 2019 |
| HP            | Pavilion 15                 | [7376903dca](https://linux-hardware.org/?probe=7376903dca) | May 13, 2018 |
| HP            | Pavilion 15                 | [2cc0124d5d](https://linux-hardware.org/?probe=2cc0124d5d) | May 13, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 25        | 12.2%   |
| Ubuntu 18.04       | 20        | 9.76%   |
| Ubuntu 22.04       | 12        | 5.85%   |
| Manjaro            | 7         | 3.41%   |
| Arch Rolling       | 7         | 3.41%   |
| OpenMandriva 4.2   | 6         | 2.93%   |
| KDE neon 20.04     | 6         | 2.93%   |
| OpenMandriva 4.3   | 5         | 2.44%   |
| Zorin 16           | 4         | 1.95%   |
| OpenMandriva 23.03 | 4         | 1.95%   |
| Linux Mint 21.2    | 4         | 1.95%   |
| Fedora 38          | 4         | 1.95%   |
| Debian 12          | 4         | 1.95%   |
| Ubuntu 21.10       | 3         | 1.46%   |
| Ubuntu 19.04       | 3         | 1.46%   |
| Linux Mint 21.1    | 3         | 1.46%   |
| Linux Mint 19.3    | 3         | 1.46%   |
| Fedora 39          | 3         | 1.46%   |
| Fedora 36          | 3         | 1.46%   |
| Debian 11          | 3         | 1.46%   |
| Xubuntu 18.04      | 2         | 0.98%   |
| Ubuntu 23.10       | 2         | 0.98%   |
| Ubuntu 23.04       | 2         | 0.98%   |
| Ubuntu 21.04       | 2         | 0.98%   |
| Ubuntu 18.10       | 2         | 0.98%   |
| Pop!_OS 22.04      | 2         | 0.98%   |
| OpenMandriva 23.01 | 2         | 0.98%   |
| Linux Mint 20.1    | 2         | 0.98%   |
| Linux Mint 19.1    | 2         | 0.98%   |
| Kubuntu 18.04      | 2         | 0.98%   |
| ArcoLinux Rolling  | 2         | 0.98%   |
| Zorin 17           | 1         | 0.49%   |
| Zorin 15           | 1         | 0.49%   |
| Xubuntu 23.10      | 1         | 0.49%   |
| Xubuntu 22.04      | 1         | 0.49%   |
| Xubuntu 20.04      | 1         | 0.49%   |
| Void Linux Rolling | 1         | 0.49%   |
| Ubuntu MATE 20.04  | 1         | 0.49%   |
| Ubuntu 20.10       | 1         | 0.49%   |
| Ubuntu 19.10       | 1         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 72        | 36.73%  |
| Linux Mint   | 21        | 10.71%  |
| OpenMandriva | 17        | 8.67%   |
| Fedora       | 13        | 6.63%   |
| Manjaro      | 9         | 4.59%   |
| Arch         | 7         | 3.57%   |
| Zorin        | 6         | 3.06%   |
| KDE neon     | 6         | 3.06%   |
| Debian       | 6         | 3.06%   |
| Xubuntu      | 4         | 2.04%   |
| Kubuntu      | 4         | 2.04%   |
| Endless      | 4         | 2.04%   |
| ArcoLinux    | 3         | 1.53%   |
| SteamOS      | 2         | 1.02%   |
| Pop!_OS      | 2         | 1.02%   |
| openSUSE     | 2         | 1.02%   |
| Lubuntu      | 2         | 1.02%   |
| EndeavourOS  | 2         | 1.02%   |
| Elementary   | 2         | 1.02%   |
| Archcraft    | 2         | 1.02%   |
| Void Linux   | 1         | 0.51%   |
| Ubuntu MATE  | 1         | 0.51%   |
| ROSA         | 1         | 0.51%   |
| NixOS        | 1         | 0.51%   |
| MX           | 1         | 0.51%   |
| Gentoo       | 1         | 0.51%   |
| Feren OS     | 1         | 0.51%   |
| blendOS      | 1         | 0.51%   |
| BlackPanther | 1         | 0.51%   |
| antiX        | 1         | 0.51%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 6         | 2.71%   |
| 4.16.18-pa2-2bp1         | 6         | 2.71%   |
| 4.16.18-pa2-1bp5         | 5         | 2.26%   |
| 6.2.6-desktop-1omv2390   | 4         | 1.81%   |
| 5.8.0-53-generic         | 4         | 1.81%   |
| 5.5.19-bp0               | 4         | 1.81%   |
| 5.16.7-desktop-1omv4003  | 4         | 1.81%   |
| 5.13.0-39-generic        | 4         | 1.81%   |
| 5.4.0-73-generic         | 3         | 1.36%   |
| 5.4.0-58-generic         | 3         | 1.36%   |
| 5.4.0-52-generic         | 3         | 1.36%   |
| 5.11.0-38-generic        | 3         | 1.36%   |
| 6.5.12-300.fc39.x86_64   | 2         | 0.9%    |
| 6.5.0-17-generic         | 2         | 0.9%    |
| 6.5.0-15-generic         | 2         | 0.9%    |
| 6.4.7-arch1-1            | 2         | 0.9%    |
| 6.3.9-zen1-1-zen         | 2         | 0.9%    |
| 6.2.0-39-generic         | 2         | 0.9%    |
| 6.1.1-desktop-1omv2290   | 2         | 0.9%    |
| 6.1.0-18-amd64           | 2         | 0.9%    |
| 5.8.0-50-generic         | 2         | 0.9%    |
| 5.8.0-43-generic         | 2         | 0.9%    |
| 5.4.0-72-generic         | 2         | 0.9%    |
| 5.4.0-42-generic         | 2         | 0.9%    |
| 5.3.0-28-generic         | 2         | 0.9%    |
| 5.19.0-41-generic        | 2         | 0.9%    |
| 5.19.0-35-generic        | 2         | 0.9%    |
| 5.16.13-desktop-1omv4003 | 2         | 0.9%    |
| 5.15.0-46-generic        | 2         | 0.9%    |
| 5.15.0-41-generic        | 2         | 0.9%    |
| 5.13.0-40-generic        | 2         | 0.9%    |
| 5.13.0-37-generic        | 2         | 0.9%    |
| 5.13.0-30-generic        | 2         | 0.9%    |
| 5.11.12-desktop-1omv4002 | 2         | 0.9%    |
| 5.0.0-13-generic         | 2         | 0.9%    |
| 4.15.0-51-generic        | 2         | 0.9%    |
| 4.15.0-20-generic        | 2         | 0.9%    |
| 4.15.0-101-generic       | 2         | 0.9%    |
| 6.7.9-arch1-1.1          | 1         | 0.45%   |
| 6.6.6-arch1-1            | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 23        | 10.75%  |
| 5.15.0  | 13        | 6.07%   |
| 5.8.0   | 12        | 5.61%   |
| 5.13.0  | 12        | 5.61%   |
| 4.16.18 | 11        | 5.14%   |
| 4.15.0  | 9         | 4.21%   |
| 6.5.0   | 6         | 2.8%    |
| 6.2.0   | 6         | 2.8%    |
| 5.11.0  | 6         | 2.8%    |
| 5.10.14 | 6         | 2.8%    |
| 5.0.0   | 6         | 2.8%    |
| 5.3.0   | 5         | 2.34%   |
| 5.19.0  | 5         | 2.34%   |
| 6.2.6   | 4         | 1.87%   |
| 6.1.0   | 4         | 1.87%   |
| 5.5.19  | 4         | 1.87%   |
| 5.16.7  | 4         | 1.87%   |
| 5.10.0  | 4         | 1.87%   |
| 4.18.0  | 4         | 1.87%   |
| 6.5.12  | 2         | 0.93%   |
| 6.4.7   | 2         | 0.93%   |
| 6.3.9   | 2         | 0.93%   |
| 6.3.4   | 2         | 0.93%   |
| 6.1.1   | 2         | 0.93%   |
| 5.19.12 | 2         | 0.93%   |
| 5.16.13 | 2         | 0.93%   |
| 5.11.12 | 2         | 0.93%   |
| 6.7.9   | 1         | 0.47%   |
| 6.6.6   | 1         | 0.47%   |
| 6.6.16  | 1         | 0.47%   |
| 6.6.13  | 1         | 0.47%   |
| 6.6.10  | 1         | 0.47%   |
| 6.5.9   | 1         | 0.47%   |
| 6.5.5   | 1         | 0.47%   |
| 6.5.4   | 1         | 0.47%   |
| 6.5.3   | 1         | 0.47%   |
| 6.5.10  | 1         | 0.47%   |
| 6.4.8   | 1         | 0.47%   |
| 6.4.6   | 1         | 0.47%   |
| 6.4.1   | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 25        | 11.9%   |
| 5.15    | 15        | 7.14%   |
| 5.8     | 14        | 6.67%   |
| 5.10    | 13        | 6.19%   |
| 6.5     | 12        | 5.71%   |
| 6.2     | 12        | 5.71%   |
| 5.13    | 12        | 5.71%   |
| 4.16    | 12        | 5.71%   |
| 6.1     | 11        | 5.24%   |
| 5.11    | 10        | 4.76%   |
| 4.15    | 9         | 4.29%   |
| 5.16    | 8         | 3.81%   |
| 5.19    | 7         | 3.33%   |
| 6.4     | 6         | 2.86%   |
| 5.0     | 6         | 2.86%   |
| 5.3     | 5         | 2.38%   |
| 4.18    | 5         | 2.38%   |
| 6.6     | 4         | 1.9%    |
| 6.3     | 4         | 1.9%    |
| 5.5     | 4         | 1.9%    |
| 6.0     | 3         | 1.43%   |
| 5.17    | 3         | 1.43%   |
| 5.18    | 2         | 0.95%   |
| 6.7     | 1         | 0.48%   |
| 5.6     | 1         | 0.48%   |
| 5.2     | 1         | 0.48%   |
| 5.14    | 1         | 0.48%   |
| 4.9     | 1         | 0.48%   |
| 4.17    | 1         | 0.48%   |
| 4.13    | 1         | 0.48%   |
| 4.12    | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 188       | 98.95%  |
| i686   | 2         | 1.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 69        | 35.03%  |
| KDE5            | 35        | 17.77%  |
| Unknown         | 23        | 11.68%  |
| XFCE            | 19        | 9.64%   |
| X-Cinnamon      | 16        | 8.12%   |
| GNOME Flashback | 13        | 6.6%    |
| KDE             | 6         | 3.05%   |
| MATE            | 3         | 1.52%   |
| LXQt            | 3         | 1.52%   |
| Pantheon        | 2         | 1.02%   |
| openbox         | 2         | 1.02%   |
| Cinnamon        | 2         | 1.02%   |
| sway            | 1         | 0.51%   |
| LXDE            | 1         | 0.51%   |
| LeftWM          | 1         | 0.51%   |
| i3              | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 141       | 73.44%  |
| Wayland | 39        | 20.31%  |
| Unknown | 10        | 5.21%   |
| Tty     | 2         | 1.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 89        | 45.18%  |
| SDDM    | 33        | 16.75%  |
| GDM3    | 24        | 12.18%  |
| GDM     | 24        | 12.18%  |
| LightDM | 22        | 11.17%  |
| TDM     | 3         | 1.52%   |
| XDM     | 1         | 0.51%   |
| GREETD  | 1         | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_UY      | 100       | 50%     |
| en_US      | 50        | 25%     |
| es_ES      | 18        | 9%      |
| Unknown    | 18        | 9%      |
| es_MX      | 7         | 3.5%    |
| es_AR      | 2         | 1%      |
| C          | 2         | 1%      |
| pt_BR      | 1         | 0.5%    |
| es_UY.UTF8 | 1         | 0.5%    |
| en_CA      | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 107       | 55.44%  |
| BIOS | 86        | 44.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 147       | 74.62%  |
| Btrfs   | 19        | 9.64%   |
| Overlay | 16        | 8.12%   |
| Tmpfs   | 9         | 4.57%   |
| Unknown | 4         | 2.03%   |
| Xfs     | 1         | 0.51%   |
| Ext3    | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 102       | 52.85%  |
| GPT     | 73        | 37.82%  |
| MBR     | 18        | 9.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 158       | 82.72%  |
| Yes       | 33        | 17.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 148       | 76.68%  |
| Yes       | 45        | 23.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 40        | 21.05%  |
| Lenovo              | 34        | 17.89%  |
| ASUSTek Computer    | 20        | 10.53%  |
| Dell                | 17        | 8.95%   |
| ECS                 | 16        | 8.42%   |
| Acer                | 15        | 7.89%   |
| Toshiba             | 9         | 4.74%   |
| Standard            | 6         | 3.16%   |
| Samsung Electronics | 6         | 3.16%   |
| MSI                 | 5         | 2.63%   |
| GPU Company         | 3         | 1.58%   |
| Valve               | 2         | 1.05%   |
| Gateway             | 2         | 1.05%   |
| Apple               | 2         | 1.05%   |
| Sony                | 1         | 0.53%   |
| Razer               | 1         | 0.53%   |
| Positivo            | 1         | 0.53%   |
| Panasonic           | 1         | 0.53%   |
| OEM                 | 1         | 0.53%   |
| Intel               | 1         | 0.53%   |
| iClever             | 1         | 0.53%   |
| Haitech             | 1         | 0.53%   |
| Google              | 1         | 0.53%   |
| Fujitsu             | 1         | 0.53%   |
| Chuwi               | 1         | 0.53%   |
| Alienware           | 1         | 0.53%   |
| Unknown             | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ECS SF20PA2                                 | 16        | 8.42%   |
| Standard SF20BA2                            | 4         | 2.11%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV       | 3         | 1.58%   |
| Valve Jupiter                               | 2         | 1.05%   |
| Toshiba Satellite L55t-B                    | 2         | 1.05%   |
| HP Stream Laptop 14-ax0XX                   | 2         | 1.05%   |
| HP Pavilion 15                              | 2         | 1.05%   |
| HP Notebook                                 | 2         | 1.05%   |
| HP Laptop 15-bs0xx                          | 2         | 1.05%   |
| Unknown                                     | 2         | 1.05%   |
| Toshiba Satellite L45-B                     | 1         | 0.53%   |
| Toshiba Satellite C855                      | 1         | 0.53%   |
| Toshiba Satellite C75D-C                    | 1         | 0.53%   |
| Toshiba Satellite C75D-B                    | 1         | 0.53%   |
| Toshiba Satellite C645D                     | 1         | 0.53%   |
| Toshiba Satellite C55-B                     | 1         | 0.53%   |
| Toshiba Satellite C45-A                     | 1         | 0.53%   |
| Standard SF20BA                             | 1         | 0.53%   |
| Standard EF20EA                             | 1         | 0.53%   |
| Sony SVF14211CLB                            | 1         | 0.53%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.53%   |
| Samsung NC208/NC108                         | 1         | 0.53%   |
| Samsung N102SP/N100SP/N101SP                | 1         | 0.53%   |
| Samsung 700T                                | 1         | 0.53%   |
| Samsung 550P5C/550P7C                       | 1         | 0.53%   |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.53%   |
| Razer Blade                                 | 1         | 0.53%   |
| Positivo Serie AT300                        | 1         | 0.53%   |
| Panasonic CF-31JEGAX1M                      | 1         | 0.53%   |
| OEM V40SI2                                  | 1         | 0.53%   |
| MSI GS63VR 6RF                              | 1         | 0.53%   |
| MSI GL65 Leopard 10SCXR                     | 1         | 0.53%   |
| MSI GL63 8RD                                | 1         | 0.53%   |
| MSI GE62 6QD                                | 1         | 0.53%   |
| Lenovo V15-ADA 82C7                         | 1         | 0.53%   |
| Lenovo ThinkPad X240 20AMS72901             | 1         | 0.53%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS36700    | 1         | 0.53%   |
| Lenovo ThinkPad T590 20N5S2GP05             | 1         | 0.53%   |
| Lenovo ThinkPad T480 20L5000UUS             | 1         | 0.53%   |
| Lenovo ThinkPad T450 20BUS0G91F             | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 16        | 8.42%   |
| ECS SF20PA2            | 16        | 8.42%   |
| HP Laptop              | 11        | 5.79%   |
| Acer Aspire            | 11        | 5.79%   |
| HP Pavilion            | 10        | 5.26%   |
| Toshiba Satellite      | 9         | 4.74%   |
| Lenovo IdeaPad         | 9         | 4.74%   |
| Dell Inspiron          | 8         | 4.21%   |
| Dell Latitude          | 6         | 3.16%   |
| ASUS VivoBook          | 5         | 2.63%   |
| ASUS ROG               | 5         | 2.63%   |
| Standard SF20BA2       | 4         | 2.11%   |
| ASUS Zenbook           | 4         | 2.11%   |
| HP Stream              | 3         | 1.58%   |
| Valve Jupiter          | 2         | 1.05%   |
| HP Presario            | 2         | 1.05%   |
| HP Notebook            | 2         | 1.05%   |
| HP EliteBook           | 2         | 1.05%   |
| HP 240                 | 2         | 1.05%   |
| Dell XPS               | 2         | 1.05%   |
| Acer TravelMate        | 2         | 1.05%   |
| Unknown                | 2         | 1.05%   |
| Standard SF20BA        | 1         | 0.53%   |
| Standard EF20EA        | 1         | 0.53%   |
| Sony SVF14211CLB       | 1         | 0.53%   |
| Samsung RV411          | 1         | 0.53%   |
| Samsung NC208          | 1         | 0.53%   |
| Samsung N102SP         | 1         | 0.53%   |
| Samsung 700T           | 1         | 0.53%   |
| Samsung 550P5C         | 1         | 0.53%   |
| Samsung 300E4C         | 1         | 0.53%   |
| Razer Blade            | 1         | 0.53%   |
| Positivo Serie         | 1         | 0.53%   |
| Panasonic CF-31JEGAX1M | 1         | 0.53%   |
| OEM V40SI2             | 1         | 0.53%   |
| MSI GS63VR             | 1         | 0.53%   |
| MSI GL65               | 1         | 0.53%   |
| MSI GL63               | 1         | 0.53%   |
| MSI GE62               | 1         | 0.53%   |
| Lenovo V15-ADA         | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 27        | 14.21%  |
| 2020 | 18        | 9.47%   |
| 2019 | 17        | 8.95%   |
| 2015 | 16        | 8.42%   |
| 2018 | 15        | 7.89%   |
| 2013 | 15        | 7.89%   |
| 2014 | 14        | 7.37%   |
| 2011 | 14        | 7.37%   |
| 2016 | 13        | 6.84%   |
| 2012 | 12        | 6.32%   |
| 2022 | 7         | 3.68%   |
| 2021 | 6         | 3.16%   |
| 2010 | 4         | 2.11%   |
| 2007 | 4         | 2.11%   |
| 2008 | 3         | 1.58%   |
| 2023 | 2         | 1.05%   |
| 2009 | 2         | 1.05%   |
| 2024 | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 190       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 171       | 89.06%  |
| Enabled  | 21        | 10.94%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 188       | 98.95%  |
| Yes  | 2         | 1.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 47        | 24.35%  |
| 4.01-8.0    | 46        | 23.83%  |
| 1.01-2.0    | 28        | 14.51%  |
| 16.01-24.0  | 26        | 13.47%  |
| 8.01-16.0   | 26        | 13.47%  |
| 32.01-64.0  | 12        | 6.22%   |
| 24.01-32.0  | 4         | 2.07%   |
| 2.01-3.0    | 2         | 1.04%   |
| 64.01-256.0 | 1         | 0.52%   |
| 0.01-0.5    | 1         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 79        | 37.62%  |
| 2.01-3.0   | 59        | 28.1%   |
| 4.01-8.0   | 26        | 12.38%  |
| 3.01-4.0   | 22        | 10.48%  |
| 0.51-1.0   | 13        | 6.19%   |
| 8.01-16.0  | 8         | 3.81%   |
| 0.01-0.5   | 2         | 0.95%   |
| 16.01-24.0 | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 156       | 81.68%  |
| 2      | 34        | 17.8%   |
| 0      | 1         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 134       | 69.79%  |
| Yes       | 58        | 30.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 63.87%  |
| No        | 69        | 36.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 96.32%  |
| No        | 7         | 3.68%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 78.95%  |
| No        | 40        | 21.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Uruguay | 190       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Montevideo             | 142       | 70.3%   |
| Maldonado              | 10        | 4.95%   |
| Canelones              | 8         | 3.96%   |
| Punta del Este         | 4         | 1.98%   |
| Buceo                  | 3         | 1.49%   |
| Salto                  | 2         | 0.99%   |
| Rocha                  | 2         | 0.99%   |
| Punta Gorda            | 2         | 0.99%   |
| Paysandú              | 2         | 0.99%   |
| Las Piedras            | 2         | 0.99%   |
| El Pinar               | 2         | 0.99%   |
| Ciudad del Plata       | 2         | 0.99%   |
| Solymar                | 1         | 0.5%    |
| San Jose de Mayo       | 1         | 0.5%    |
| Pocitos                | 1         | 0.5%    |
| Pinamar                | 1         | 0.5%    |
| Parque Rodo            | 1         | 0.5%    |
| Nueva Helvecia         | 1         | 0.5%    |
| Minas                  | 1         | 0.5%    |
| Melilla                | 1         | 0.5%    |
| Maronas                | 1         | 0.5%    |
| Las Flores             | 1         | 0.5%    |
| La Paz                 | 1         | 0.5%    |
| Joaquin Suarez         | 1         | 0.5%    |
| El Tesoro              | 1         | 0.5%    |
| Durazno                | 1         | 0.5%    |
| Colonia Rosario        | 1         | 0.5%    |
| Colonia Nicolich       | 1         | 0.5%    |
| Chui                   | 1         | 0.5%    |
| Centro                 | 1         | 0.5%    |
| Barrancas Coloradas    | 1         | 0.5%    |
| Atlantida              | 1         | 0.5%    |
| Arenas de Jose Ignacio | 1         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 28        | 35     | 13.21%  |
| Kingston                    | 28        | 38     | 13.21%  |
| Toshiba                     | 26        | 30     | 12.26%  |
| WDC                         | 24        | 29     | 11.32%  |
| Seagate                     | 19        | 23     | 8.96%   |
| SanDisk                     | 16        | 19     | 7.55%   |
| Samsung Electronics         | 13        | 14     | 6.13%   |
| SK hynix                    | 8         | 9      | 3.77%   |
| Hitachi                     | 7         | 9      | 3.3%    |
| Intel                       | 6         | 7      | 2.83%   |
| HGST                        | 6         | 6      | 2.83%   |
| Netac                       | 4         | 5      | 1.89%   |
| Micron Technology           | 4         | 4      | 1.89%   |
| Kingston Technology Company | 3         | 3      | 1.42%   |
| Hewlett-Packard             | 3         | 3      | 1.42%   |
| KIOXIA                      | 2         | 3      | 0.94%   |
| Crucial                     | 2         | 3      | 0.94%   |
| W800SH                      | 1         | 1      | 0.47%   |
| Union Memory (Shenzhen)     | 1         | 2      | 0.47%   |
| SAGE                        | 1         | 2      | 0.47%   |
| Phison Electronics          | 1         | 1      | 0.47%   |
| LITEON                      | 1         | 2      | 0.47%   |
| KingFast                    | 1         | 1      | 0.47%   |
| Hikvision                   | 1         | 1      | 0.47%   |
| Gateway                     | 1         | 1      | 0.47%   |
| Dahua                       | 1         | 2      | 0.47%   |
| China                       | 1         | 1      | 0.47%   |
| BIWIN                       | 1         | 1      | 0.47%   |
| BHT                         | 1         | 1      | 0.47%   |
| Apple                       | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                  | 14        | 6.39%   |
| Kingston SA400S37480G 480GB SSD         | 8         | 3.65%   |
| Kingston SA400S37240G 240GB SSD         | 8         | 3.65%   |
| Unknown DA4032  32GB                    | 5         | 2.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 5         | 2.28%   |
| Toshiba MQ01ABD075 752GB                | 4         | 1.83%   |
| Toshiba HDWK105 500GB                   | 4         | 1.83%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 4         | 1.83%   |
| Seagate ST1000LM035-1RK172 1TB          | 4         | 1.83%   |
| Toshiba MQ01ABF050 500GB                | 3         | 1.37%   |
| Toshiba MQ01ABD100 1TB                  | 3         | 1.37%   |
| SanDisk DF4032  32GB                    | 3         | 1.37%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 2         | 0.91%   |
| WDC WD5000BEKT-60KA9T0 500GB            | 2         | 0.91%   |
| Unknown SD/MMC/MS PRO 128GB             | 2         | 0.91%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB  | 2         | 0.91%   |
| SanDisk SSD U100 8GB                    | 2         | 0.91%   |
| SanDisk NVMe SSD Drive 256GB            | 2         | 0.91%   |
| SanDisk NVMe SSD Drive 1024GB           | 2         | 0.91%   |
| Netac SSD 480GB                         | 2         | 0.91%   |
| Netac SSD 256GB                         | 2         | 0.91%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB | 2         | 0.91%   |
| Hitachi HTS547564A9E384 640GB           | 2         | 0.91%   |
| HGST HTS545050A7E680 500GB              | 2         | 0.91%   |
| WDC WDS250G2X0C-00L350 250GB            | 1         | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.46%   |
| WDC WD7500BPVX-22JC3T0 752GB            | 1         | 0.46%   |
| WDC WD6400BPVT-75HXZT1 640GB            | 1         | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 0.46%   |
| WDC WD5000LPVX-00V0TT0 500GB            | 1         | 0.46%   |
| WDC WD5000LPVT-24G33T1 500GB            | 1         | 0.46%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.46%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 0.46%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 1         | 0.46%   |
| WDC WD3200LPCX-24C6HT0 320GB            | 1         | 0.46%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1         | 0.46%   |
| WDC WD3200BEVT-26ZCT0 320GB             | 1         | 0.46%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.46%   |
| WDC WD10SPZX-08Z10 1TB                  | 1         | 0.46%   |
| WDC WD10SPCX-24HWST1 1TB                | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 22        | 26     | 29.33%  |
| Seagate | 19        | 23     | 25.33%  |
| WDC     | 18        | 23     | 24%     |
| Hitachi | 7         | 9      | 9.33%   |
| HGST    | 6         | 6      | 8%      |
| Unknown | 2         | 2      | 2.67%   |
| SAGE    | 1         | 2      | 1.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 22        | 27     | 38.6%   |
| Samsung Electronics | 6         | 6      | 10.53%  |
| SanDisk             | 5         | 6      | 8.77%   |
| Netac               | 4         | 5      | 7.02%   |
| WDC                 | 3         | 3      | 5.26%   |
| Hewlett-Packard     | 3         | 3      | 5.26%   |
| SK hynix            | 2         | 2      | 3.51%   |
| Intel               | 2         | 2      | 3.51%   |
| W800SH              | 1         | 1      | 1.75%   |
| Toshiba             | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| Hikvision           | 1         | 1      | 1.75%   |
| Gateway             | 1         | 1      | 1.75%   |
| Dahua               | 1         | 2      | 1.75%   |
| Crucial             | 1         | 2      | 1.75%   |
| China               | 1         | 1      | 1.75%   |
| BIWIN               | 1         | 1      | 1.75%   |
| BHT                 | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 73        | 91     | 35.44%  |
| SSD     | 55        | 66     | 26.7%   |
| NVMe    | 47        | 61     | 22.82%  |
| MMC     | 30        | 38     | 14.56%  |
| Unknown | 1         | 1      | 0.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 118       | 153    | 59.3%   |
| NVMe | 47        | 61     | 23.62%  |
| MMC  | 30        | 38     | 15.08%  |
| SAS  | 4         | 5      | 2.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 89        | 112    | 71.2%   |
| 0.51-1.0   | 34        | 43     | 27.2%   |
| 1.01-2.0   | 2         | 2      | 1.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 52        | 25.87%  |
| 101-250        | 49        | 24.38%  |
| 501-1000       | 29        | 14.43%  |
| 21-50          | 24        | 11.94%  |
| 1-20           | 21        | 10.45%  |
| 1001-2000      | 10        | 4.98%   |
| 51-100         | 10        | 4.98%   |
| Unknown        | 4         | 1.99%   |
| More than 3000 | 1         | 0.5%    |
| 2001-3000      | 1         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 95        | 44.81%  |
| 21-50          | 41        | 19.34%  |
| 51-100         | 23        | 10.85%  |
| 251-500        | 20        | 9.43%   |
| 101-250        | 19        | 8.96%   |
| 501-1000       | 8         | 3.77%   |
| Unknown        | 4         | 1.89%   |
| More than 3000 | 1         | 0.47%   |
| 1001-2000      | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Notebooks | Drives | Percent |
|---------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB                                  | 2         | 2      | 11.76%  |
| WDC WD5000LPCX-24C6HT0 500GB                                  | 1         | 1      | 5.88%   |
| WDC WD3200BEVT-26ZCT0 320GB                                   | 1         | 1      | 5.88%   |
| WDC WD10SPCX-24HWST1 1TB                                      | 1         | 1      | 5.88%   |
| Toshiba MK5059GSXP 500GB                                      | 1         | 2      | 5.88%   |
| Toshiba MK3265GSX 320GB                                       | 1         | 1      | 5.88%   |
| Toshiba MK3259GSXP 320GB                                      | 1         | 1      | 5.88%   |
| Toshiba MK2555GSX 250GB                                       | 1         | 1      | 5.88%   |
| Seagate ST980811AS 80GB                                       | 1         | 2      | 5.88%   |
| Seagate ST9120821AS 120GB                                     | 1         | 1      | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB                                | 1         | 1      | 5.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                            | 1         | 1      | 5.88%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                           | 1         | 1      | 5.88%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 2      | 5.88%   |
| Hitachi HTS547564A9E384 640GB                                 | 1         | 1      | 5.88%   |
| HGST HTS545032A7E380 320GB                                    | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 25%     |
| Toshiba             | 4         | 5      | 25%     |
| Seagate             | 4         | 5      | 25%     |
| SanDisk             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 2      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 28.57%  |
| Toshiba | 4         | 5      | 28.57%  |
| Seagate | 4         | 5      | 28.57%  |
| Hitachi | 1         | 1      | 7.14%   |
| HGST    | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 17     | 87.5%   |
| NVMe | 1         | 2      | 6.25%   |
| SSD  | 1         | 1      | 6.25%   |

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
| Detected | 121       | 160    | 62.69%  |
| Works    | 56        | 77     | 29.02%  |
| Malfunc  | 16        | 20     | 8.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 128       | 63.05%  |
| AMD                              | 30        | 14.78%  |
| SanDisk                          | 11        | 5.42%   |
| Kingston Technology Company      | 8         | 3.94%   |
| Samsung Electronics              | 7         | 3.45%   |
| SK hynix                         | 5         | 2.46%   |
| Toshiba America Info Systems     | 4         | 1.97%   |
| Micron Technology                | 3         | 1.48%   |
| Union Memory (Shenzhen)          | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| Phison Electronics               | 1         | 0.49%   |
| Micron/Crucial Technology        | 1         | 0.49%   |
| Lite-On Technology               | 1         | 0.49%   |
| KIOXIA                           | 1         | 0.49%   |
| Apple                            | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 12.68%  |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 17        | 7.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 13        | 6.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 4.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8         | 3.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 3.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 3.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.82%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 5         | 2.35%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.35%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.88%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.41%   |
| Intel SSD 660P Series                                                            | 3         | 1.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.41%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.94%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.94%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.94%   |
| Kingston Company NV1 NVMe SSD E13T (DRAM-less)                                   | 2         | 0.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.94%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 2         | 0.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.94%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                  | 1         | 0.47%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.47%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 141       | 67.46%  |
| NVMe | 47        | 22.49%  |
| RAID | 13        | 6.22%   |
| IDE  | 8         | 3.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 149       | 78.42%  |
| AMD    | 41        | 21.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz            | 17        | 8.95%   |
| Intel Celeron CPU N3160 @ 1.60GHz            | 4         | 2.11%   |
| Intel 12th Gen Core i7-1255U                 | 4         | 2.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 3         | 1.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 3         | 1.58%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 3         | 1.58%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 3         | 1.58%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 3         | 1.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 1.58%   |
| Intel Celeron CPU N3060 @ 1.60GHz            | 3         | 1.58%   |
| Intel Celeron CPU N3050 @ 1.60GHz            | 3         | 1.58%   |
| AMD Ryzen 9 4900HS with Radeon Graphics      | 3         | 1.58%   |
| AMD E-300 APU with Radeon HD Graphics        | 3         | 1.58%   |
| Intel Pentium CPU P6200 @ 2.13GHz            | 2         | 1.05%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 1.05%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 2         | 1.05%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 2         | 1.05%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 2         | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz           | 2         | 1.05%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 2         | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.05%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 2         | 1.05%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 1.05%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 2         | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 2         | 1.05%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 2         | 1.05%   |
| Intel Celeron N4000 CPU @ 1.10GHz            | 2         | 1.05%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 2         | 1.05%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 1.05%   |
| Intel Atom CPU Z3735F @ 1.33GHz              | 2         | 1.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 2         | 1.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 2         | 1.05%   |
| AMD Ryzen 7 4800H with Radeon Graphics       | 2         | 1.05%   |
| AMD Custom APU 0405                          | 2         | 1.05%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.05%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics  | 2         | 1.05%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 1         | 0.53%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.53%   |
| Intel Pentium CPU N3540 @ 2.16GHz            | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Celeron      | 38        | 20%     |
| Intel Core i5      | 33        | 17.37%  |
| Intel Core i7      | 31        | 16.32%  |
| Intel Core i3      | 15        | 7.89%   |
| Other              | 14        | 7.37%   |
| Intel Pentium      | 8         | 4.21%   |
| Intel Atom         | 7         | 3.68%   |
| AMD A6             | 6         | 3.16%   |
| AMD Ryzen 9        | 5         | 2.63%   |
| AMD Ryzen 5        | 4         | 2.11%   |
| AMD Ryzen 7        | 3         | 1.58%   |
| AMD E2             | 3         | 1.58%   |
| AMD E              | 3         | 1.58%   |
| Intel Genuine      | 2         | 1.05%   |
| Intel Core 2 Duo   | 2         | 1.05%   |
| AMD Ryzen 3        | 2         | 1.05%   |
| AMD E1             | 2         | 1.05%   |
| AMD A8             | 2         | 1.05%   |
| Intel Pentium Dual | 1         | 0.53%   |
| Intel Core m3      | 1         | 0.53%   |
| Intel Core 2       | 1         | 0.53%   |
| AMD Ryzen 5 PRO    | 1         | 0.53%   |
| AMD Phenom II      | 1         | 0.53%   |
| AMD FX             | 1         | 0.53%   |
| AMD Athlon II      | 1         | 0.53%   |
| AMD Athlon         | 1         | 0.53%   |
| AMD A4             | 1         | 0.53%   |
| AMD A10            | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 107       | 56.32%  |
| 4      | 57        | 30%     |
| 6      | 10        | 5.26%   |
| 8      | 7         | 3.68%   |
| 10     | 4         | 2.11%   |
| 1      | 4         | 2.11%   |
| 12     | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 190       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 111       | 58.42%  |
| 1      | 79        | 41.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 187       | 98.42%  |
| Unknown        | 3         | 1.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 34.69%  |
| 0x406c4    | 7         | 3.57%   |
| 0x206a7    | 7         | 3.57%   |
| 0x506c9    | 6         | 3.06%   |
| 0x40651    | 6         | 3.06%   |
| 0x20655    | 6         | 3.06%   |
| 0x806ec    | 5         | 2.55%   |
| 0x406e3    | 5         | 2.55%   |
| 0x306d4    | 5         | 2.55%   |
| 0x806ea    | 4         | 2.04%   |
| 0x806e9    | 4         | 2.04%   |
| 0x406c3    | 4         | 2.04%   |
| 0x30678    | 4         | 2.04%   |
| 0x906ea    | 3         | 1.53%   |
| 0x806c1    | 3         | 1.53%   |
| 0x706a1    | 3         | 1.53%   |
| 0x6fd      | 3         | 1.53%   |
| 0x306c3    | 3         | 1.53%   |
| 0x306a9    | 3         | 1.53%   |
| 0x08108109 | 3         | 1.53%   |
| 0x06006705 | 3         | 1.53%   |
| 0x706e5    | 2         | 1.02%   |
| 0x506e3    | 2         | 1.02%   |
| 0x0a50000c | 2         | 1.02%   |
| 0x08600104 | 2         | 1.02%   |
| 0x0810100b | 2         | 1.02%   |
| 0x07030105 | 2         | 1.02%   |
| 0x07030104 | 2         | 1.02%   |
| 0x0700010f | 2         | 1.02%   |
| 0x05000119 | 2         | 1.02%   |
| 0xa0652    | 1         | 0.51%   |
| 0x806eb    | 1         | 0.51%   |
| 0x6f2      | 1         | 0.51%   |
| 0x30673    | 1         | 0.51%   |
| 0x30661    | 1         | 0.51%   |
| 0x106e5    | 1         | 0.51%   |
| 0x106ca    | 1         | 0.51%   |
| 0x1067a    | 1         | 0.51%   |
| 0x10676    | 1         | 0.51%   |
| 0x10661    | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 12.11%  |
| Silvermont       | 22        | 11.58%  |
| Goldmont         | 17        | 8.95%   |
| Haswell          | 12        | 6.32%   |
| Skylake          | 10        | 5.26%   |
| SandyBridge      | 10        | 5.26%   |
| IvyBridge        | 9         | 4.74%   |
| Broadwell        | 8         | 4.21%   |
| Westmere         | 7         | 3.68%   |
| Excavator        | 7         | 3.68%   |
| Zen 2            | 6         | 3.16%   |
| Puma             | 6         | 3.16%   |
| Unknown          | 6         | 3.16%   |
| TigerLake        | 5         | 2.63%   |
| Core             | 5         | 2.63%   |
| Zen+             | 4         | 2.11%   |
| IceLake          | 4         | 2.11%   |
| Bobcat           | 4         | 2.11%   |
| Zen 3            | 3         | 1.58%   |
| Goldmont plus    | 3         | 1.58%   |
| CometLake        | 3         | 1.58%   |
| Zen              | 2         | 1.05%   |
| Piledriver       | 2         | 1.05%   |
| Penryn           | 2         | 1.05%   |
| K10              | 2         | 1.05%   |
| Jaguar           | 2         | 1.05%   |
| Bonnell          | 2         | 1.05%   |
| Alderlake Hybrid | 2         | 1.05%   |
| Tremont          | 1         | 0.53%   |
| Nehalem          | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 147       | 66.22%  |
| AMD                              | 49        | 22.07%  |
| Nvidia                           | 25        | 11.26%  |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 500                                                                    | 17        | 7.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 7.02%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 3.95%   |
| Intel HD Graphics 5500                                                                   | 7         | 3.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.07%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 3.07%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.63%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 6         | 2.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.19%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 2.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.75%   |
| Intel HD Graphics 620                                                                    | 4         | 1.75%   |
| Intel HD Graphics 530                                                                    | 4         | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.75%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 4         | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.75%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.32%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.32%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 1.32%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.32%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.32%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.88%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.88%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.88%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 2         | 0.88%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.88%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 0.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 122       | 64.21%  |
| 1 x AMD        | 32        | 16.84%  |
| Intel + Nvidia | 17        | 8.95%   |
| Intel + AMD    | 8         | 4.21%   |
| AMD + Nvidia   | 7         | 3.68%   |
| 2 x AMD        | 2         | 1.05%   |
| 1 x SiS        | 1         | 0.53%   |
| 1 x Nvidia     | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 173       | 90.1%   |
| Proprietary | 16        | 8.33%   |
| Unknown     | 3         | 1.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 142       | 73.58%  |
| 0.01-0.5   | 19        | 9.84%   |
| 1.01-2.0   | 11        | 5.7%    |
| 0.51-1.0   | 11        | 5.7%    |
| 3.01-4.0   | 6         | 3.11%   |
| 5.01-6.0   | 3         | 1.55%   |
| 7.01-8.0   | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 34        | 16.35%  |
| Chimei Innolux          | 30        | 14.42%  |
| BOE                     | 28        | 13.46%  |
| Samsung Electronics     | 26        | 12.5%   |
| AU Optronics            | 24        | 11.54%  |
| KDC                     | 8         | 3.85%   |
| InfoVision              | 8         | 3.85%   |
| PANDA                   | 7         | 3.37%   |
| ViewSonic               | 4         | 1.92%   |
| Sharp                   | 4         | 1.92%   |
| Dell                    | 4         | 1.92%   |
| Chi Mei Optoelectronics | 4         | 1.92%   |
| Acer                    | 3         | 1.44%   |
| Valve                   | 2         | 0.96%   |
| LG Philips              | 2         | 0.96%   |
| KTC                     | 2         | 0.96%   |
| HSI                     | 2         | 0.96%   |
| Apple                   | 2         | 0.96%   |
| Toshiba                 | 1         | 0.48%   |
| TopView                 | 1         | 0.48%   |
| TMX                     | 1         | 0.48%   |
| Sun                     | 1         | 0.48%   |
| Mi                      | 1         | 0.48%   |
| Konka                   | 1         | 0.48%   |
| JDI                     | 1         | 0.48%   |
| InnoLux Display         | 1         | 0.48%   |
| HKC                     | 1         | 0.48%   |
| Hewlett-Packard         | 1         | 0.48%   |
| Goldstar                | 1         | 0.48%   |
| CPT                     | 1         | 0.48%   |
| AOC                     | 1         | 0.48%   |
| Ancor Communications    | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| KDC LCD Monitor KDC05F1 1366x768 256x144mm 11.6-inch                 | 6         | 2.83%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch         | 6         | 2.83%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 4         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 3         | 1.42%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 3         | 1.42%   |
| ViewSonic VA2261 VSC0F30 1920x1080 480x270mm 21.7-inch               | 2         | 0.94%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 2         | 0.94%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch              | 2         | 0.94%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch | 2         | 0.94%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2         | 0.94%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch              | 2         | 0.94%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 2         | 0.94%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch          | 2         | 0.94%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch          | 2         | 0.94%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.94%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                 | 2         | 0.94%   |
| HSI LED-TV HSI0001 1920x1080 708x398mm 32.0-inch                     | 2         | 0.94%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                    | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch      | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch      | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch      | 2         | 0.94%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 2         | 0.94%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch        | 1         | 0.47%   |
| ViewSonic VSD220 VSC2CB2 1920x1080 477x268mm 21.5-inch               | 1         | 0.47%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                | 1         | 0.47%   |
| TopView HDMI TOP0814 1600x900 430x270mm 20.0-inch                    | 1         | 0.47%   |
| TMX TL140ADXP02-0 TMX1401 2560x1600 301x188mm 14.0-inch              | 1         | 0.47%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.47%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch              | 1         | 0.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1         | 0.47%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch    | 1         | 0.47%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch    | 1         | 0.47%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 95        | 50.53%  |
| 1920x1080 (FHD)   | 51        | 27.13%  |
| 1600x900 (HD+)    | 9         | 4.79%   |
| 1920x1200 (WUXGA) | 8         | 4.26%   |
| 3840x2160 (4K)    | 5         | 2.66%   |
| 1280x800 (WXGA)   | 5         | 2.66%   |
| 2560x1440 (QHD)   | 4         | 2.13%   |
| 2560x1600         | 3         | 1.6%    |
| 800x1280          | 2         | 1.06%   |
| 3200x1800 (QHD+)  | 1         | 0.53%   |
| 2288x1287         | 1         | 0.53%   |
| 2160x1440         | 1         | 0.53%   |
| 1680x945          | 1         | 0.53%   |
| 1360x768          | 1         | 0.53%   |
| 1024x600          | 1         | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 90        | 43.06%  |
| 14     | 35        | 16.75%  |
| 13     | 27        | 12.92%  |
| 11     | 9         | 4.31%   |
| 17     | 8         | 3.83%   |
| 21     | 7         | 3.35%   |
| 23     | 6         | 2.87%   |
| 24     | 5         | 2.39%   |
| 18     | 4         | 1.91%   |
| 40     | 2         | 0.96%   |
| 34     | 2         | 0.96%   |
| 27     | 2         | 0.96%   |
| 12     | 2         | 0.96%   |
| 10     | 2         | 0.96%   |
| 7      | 2         | 0.96%   |
| 86     | 1         | 0.48%   |
| 57     | 1         | 0.48%   |
| 52     | 1         | 0.48%   |
| 29     | 1         | 0.48%   |
| 26     | 1         | 0.48%   |
| 20     | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 142       | 68.6%   |
| 201-300     | 20        | 9.66%   |
| 501-600     | 14        | 6.76%   |
| 401-500     | 12        | 5.8%    |
| 351-400     | 9         | 4.35%   |
| 1001-1500   | 3         | 1.45%   |
| 801-900     | 2         | 0.97%   |
| 701-800     | 2         | 0.97%   |
| 1-100       | 2         | 0.97%   |
| 601-700     | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 161       | 89.94%  |
| 16/10 | 12        | 6.7%    |
| 21/9  | 2         | 1.12%   |
| 0.67  | 2         | 1.12%   |
| 3/2   | 1         | 0.56%   |
| 0.56  | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 90        | 42.86%  |
| 81-90          | 57        | 27.14%  |
| 201-250        | 17        | 8.1%    |
| 51-60          | 9         | 4.29%   |
| 121-130        | 7         | 3.33%   |
| 71-80          | 5         | 2.38%   |
| 141-150        | 4         | 1.9%    |
| More than 1000 | 3         | 1.43%   |
| 351-500        | 3         | 1.43%   |
| 301-350        | 3         | 1.43%   |
| 151-200        | 3         | 1.43%   |
| 61-70          | 2         | 0.95%   |
| 41-50          | 2         | 0.95%   |
| 1-40           | 2         | 0.95%   |
| 501-1000       | 2         | 0.95%   |
| 131-140        | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 102       | 49.76%  |
| 121-160       | 54        | 26.34%  |
| 51-100        | 32        | 15.61%  |
| 161-240       | 12        | 5.85%   |
| 1-50          | 3         | 1.46%   |
| More than 240 | 2         | 0.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 157       | 80.51%  |
| 2     | 31        | 15.9%   |
| 3     | 4         | 2.05%   |
| 0     | 3         | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 92        | 32.28%  |
| Intel                            | 89        | 31.23%  |
| Qualcomm Atheros                 | 39        | 13.68%  |
| Broadcom                         | 23        | 8.07%   |
| MediaTek                         | 9         | 3.16%   |
| Ralink Technology                | 5         | 1.75%   |
| Ralink                           | 4         | 1.4%    |
| Broadcom Limited                 | 4         | 1.4%    |
| TP-Link                          | 3         | 1.05%   |
| Samsung Electronics              | 3         | 1.05%   |
| ASIX Electronics                 | 3         | 1.05%   |
| Qualcomm Atheros Communications  | 2         | 0.7%    |
| Huawei Technologies              | 2         | 0.7%    |
| Xiaomi                           | 1         | 0.35%   |
| T & A Mobile Phones              | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Sierra Wireless                  | 1         | 0.35%   |
| Marvell Technology Group         | 1         | 0.35%   |
| Lenovo                           | 1         | 0.35%   |
| DisplayLink                      | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 44        | 13.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 29        | 8.81%   |
| Intel Wireless 3165                                                     | 26        | 7.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.43%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 2.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.13%   |
| Intel Wireless 7265                                                     | 7         | 2.13%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 2.13%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 6         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.82%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 1.52%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.52%   |
| Intel Wireless 7260                                                     | 5         | 1.52%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.22%   |
| Intel Wireless 8260                                                     | 4         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.91%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.91%   |
| Intel Wireless 8265 / 8275                                              | 3         | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 0.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 0.91%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 3         | 0.91%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.61%   |
| Intel Wireless 3160                                                     | 2         | 0.61%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 86        | 43.88%  |
| Realtek Semiconductor           | 38        | 19.39%  |
| Qualcomm Atheros                | 30        | 15.31%  |
| Broadcom                        | 17        | 8.67%   |
| MediaTek                        | 8         | 4.08%   |
| Ralink Technology               | 5         | 2.55%   |
| Ralink                          | 4         | 2.04%   |
| Broadcom Limited                | 3         | 1.53%   |
| TP-Link                         | 2         | 1.02%   |
| Qualcomm Atheros Communications | 2         | 1.02%   |
| Sierra Wireless                 | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 26        | 13.2%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 4.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 4.06%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 4.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 3.55%   |
| Intel Wireless 7265                                                     | 7         | 3.55%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 3.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 3.55%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 6         | 3.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.05%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 2.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.54%   |
| Intel Wireless 7260                                                     | 5         | 2.54%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.03%   |
| Intel Wireless 8260                                                     | 4         | 2.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.52%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.52%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.52%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.02%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.02%   |
| Intel Wireless 3160                                                     | 2         | 1.02%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.02%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.02%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.51%   |
| TP-Link 802.11ac NIC                                                    | 1         | 0.51%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.51%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 76        | 57.58%  |
| Intel                            | 20        | 15.15%  |
| Qualcomm Atheros                 | 11        | 8.33%   |
| Broadcom                         | 8         | 6.06%   |
| Samsung Electronics              | 3         | 2.27%   |
| ASIX Electronics                 | 3         | 2.27%   |
| Huawei Technologies              | 2         | 1.52%   |
| Xiaomi                           | 1         | 0.76%   |
| TP-Link                          | 1         | 0.76%   |
| T & A Mobile Phones              | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] | 1         | 0.76%   |
| MediaTek                         | 1         | 0.76%   |
| Marvell Technology Group         | 1         | 0.76%   |
| Lenovo                           | 1         | 0.76%   |
| DisplayLink                      | 1         | 0.76%   |
| Broadcom Limited                 | 1         | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 44        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 29        | 21.97%  |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 2.27%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 2.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 1.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 1.52%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.52%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.52%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.52%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.52%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 1.52%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.76%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.76%   |
| T & A Mobile Phones TCL 20E                                            | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.76%   |
| Samsung Kiera                                                          | 1         | 0.76%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.76%   |
| MediaTek RMX3085                                                       | 1         | 0.76%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 0.76%   |
| Lenovo USB-C to LAN                                                    | 1         | 0.76%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 0.76%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.76%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.76%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.76%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 0.76%   |
| Huawei VTR-L09                                                         | 1         | 0.76%   |
| Huawei E353/E3131                                                      | 1         | 0.76%   |
| DisplayLink Plugable UD-3900                                           | 1         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 183       | 60%     |
| Ethernet | 122       | 40%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 165       | 85.94%  |
| Ethernet | 27        | 14.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 110       | 57.89%  |
| 1     | 74        | 38.95%  |
| 0     | 5         | 2.63%   |
| 3     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 130       | 66.67%  |
| Yes  | 65        | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 76        | 50%     |
| Realtek Semiconductor           | 18        | 11.84%  |
| IMC Networks                    | 13        | 8.55%   |
| Qualcomm Atheros Communications | 12        | 7.89%   |
| Toshiba                         | 7         | 4.61%   |
| Broadcom                        | 6         | 3.95%   |
| Foxconn / Hon Hai               | 5         | 3.29%   |
| Lite-On Technology              | 4         | 2.63%   |
| Ralink                          | 3         | 1.97%   |
| Cambridge Silicon Radio         | 3         | 1.97%   |
| Apple                           | 2         | 1.32%   |
| Ralink Technology               | 1         | 0.66%   |
| Foxconn International           | 1         | 0.66%   |
| Alps Electric                   | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 25.66%  |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 5.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 5.26%   |
| Realtek Bluetooth Radio                             | 7         | 4.61%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 4.61%   |
| Intel AX201 Bluetooth                               | 7         | 4.61%   |
| Intel AX200 Bluetooth                               | 7         | 4.61%   |
| Intel Bluetooth Device                              | 6         | 3.95%   |
| IMC Networks Wireless_Device                        | 5         | 3.29%   |
| IMC Networks Bluetooth Radio                        | 4         | 2.63%   |
| Toshiba Bluetooth Device                            | 3         | 1.97%   |
| Toshiba BCM43142A0                                  | 3         | 1.97%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.32%   |
| Lite-On Bluetooth Device                            | 2         | 1.32%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.32%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.32%   |
| Intel AX211 Bluetooth                               | 2         | 1.32%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.32%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.32%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.32%   |
| Toshiba Bluetooth Radio                             | 1         | 0.66%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.66%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.66%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.66%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.66%   |
| Intel AX210 Bluetooth                               | 1         | 0.66%   |
| IMC Networks Bluetooth Device                       | 1         | 0.66%   |
| IMC Networks Bluetooth                              | 1         | 0.66%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.66%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.66%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.66%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.66%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.66%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.66%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 143       | 66.51%  |
| AMD                                  | 41        | 19.07%  |
| Nvidia                               | 17        | 7.91%   |
| Logitech                             | 4         | 1.86%   |
| Generalplus Technology               | 2         | 0.93%   |
| C-Media Electronics                  | 2         | 0.93%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.47%   |
| Texas Instruments                    | 1         | 0.47%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.47%   |
| Kingston Technology                  | 1         | 0.47%   |
| DSEA A/S                             | 1         | 0.47%   |
| ASUSTek Computer                     | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 17        | 6.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 5.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 5.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 4.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 4.78%   |
| AMD FCH Azalia Controller                                                                         | 13        | 4.78%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 3.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 2.94%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.57%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 2.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.84%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 1.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.84%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.84%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.47%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.1%    |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.1%    |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.1%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.1%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.74%   |
| Logitech H390 headset with microphone                                                             | 2         | 0.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 26.72%  |
| SK hynix            | 17        | 14.66%  |
| Micron Technology   | 15        | 12.93%  |
| Ramaxel Technology  | 9         | 7.76%   |
| Kingston            | 9         | 7.76%   |
| Unknown             | 7         | 6.03%   |
| Goldkey             | 7         | 6.03%   |
| Crucial             | 6         | 5.17%   |
| Elpida              | 4         | 3.45%   |
| A-DATA Technology   | 4         | 3.45%   |
| Nanya Technology    | 2         | 1.72%   |
| Team                | 1         | 0.86%   |
| Patriot             | 1         | 0.86%   |
| Hikvision           | 1         | 0.86%   |
| ff                  | 1         | 0.86%   |
| 4ea5                | 1         | 0.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH200SO25608-1600 2GB SODIMM DDR3 1600MT/s       | 4         | 3.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 2.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 3         | 2.48%   |
| Goldkey RAM GKH400SO25608-1600 4GB SODIMM DDR3 1600MT/s       | 3         | 2.48%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                | 2         | 1.65%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                  | 2         | 1.65%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 2         | 1.65%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 2         | 1.65%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 2         | 1.65%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s      | 2         | 1.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 1.65%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s       | 2         | 1.65%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.65%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 2         | 1.65%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 2         | 1.65%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                    | 1         | 0.83%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 1         | 0.83%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s          | 1         | 0.83%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 0.83%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM 1334MT/s          | 1         | 0.83%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 0.83%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 0.83%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 0.83%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s        | 1         | 0.83%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 0.83%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 0.83%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s     | 1         | 0.83%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2400MT/s        | 1         | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 1         | 0.83%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 1         | 0.83%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s    | 1         | 0.83%   |
| SK hynix RAM H5TC4G63CFR-PBA 2GB SODIMM DDR3 1600MT/s         | 1         | 0.83%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 0.83%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 0.83%   |
| Samsung RAM Module 2GB DIMM DDR2 533MT/s                      | 1         | 0.83%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                      | 1         | 0.83%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM 1600MT/s              | 1         | 0.83%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 1         | 0.83%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 42        | 45.65%  |
| DDR4   | 35        | 38.04%  |
| LPDDR4 | 5         | 5.43%   |
| DDR2   | 4         | 4.35%   |
| LPDDR3 | 3         | 3.26%   |
| SDRAM  | 2         | 2.17%   |
| DDR5   | 1         | 1.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 79        | 87.78%  |
| Row Of Chips | 8         | 8.89%   |
| DIMM         | 2         | 2.22%   |
| Unknown      | 1         | 1.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 34        | 30.63%  |
| 8192  | 33        | 29.73%  |
| 2048  | 18        | 16.22%  |
| 16384 | 16        | 14.41%  |
| 32768 | 5         | 4.5%    |
| 1024  | 3         | 2.7%    |
| 512   | 2         | 1.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 36        | 35.64%  |
| 2667  | 18        | 17.82%  |
| 3200  | 13        | 12.87%  |
| 2400  | 7         | 6.93%   |
| 1334  | 6         | 5.94%   |
| 2133  | 4         | 3.96%   |
| 533   | 4         | 3.96%   |
| 3266  | 3         | 2.97%   |
| 1333  | 3         | 2.97%   |
| 4199  | 2         | 1.98%   |
| 4800  | 1         | 0.99%   |
| 4267  | 1         | 0.99%   |
| 4266  | 1         | 0.99%   |
| 1867  | 1         | 0.99%   |
| 1067  | 1         | 0.99%   |

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
| Chicony Electronics                    | 49        | 28%     |
| Realtek Semiconductor                  | 16        | 9.14%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 8.57%   |
| Bison Electronics                      | 15        | 8.57%   |
| Microdia                               | 10        | 5.71%   |
| Suyin                                  | 8         | 4.57%   |
| Sunplus Innovation Technology          | 8         | 4.57%   |
| IMC Networks                           | 7         | 4%      |
| Silicon Motion                         | 6         | 3.43%   |
| Quanta                                 | 6         | 3.43%   |
| Unknown                                | 5         | 2.86%   |
| Sonix Technology                       | 5         | 2.86%   |
| Lite-On Technology                     | 4         | 2.29%   |
| Samsung Electronics                    | 3         | 1.71%   |
| Luxvisions Innotech Limited            | 3         | 1.71%   |
| Importek                               | 3         | 1.71%   |
| Alcor Micro                            | 3         | 1.71%   |
| Syntek                                 | 2         | 1.14%   |
| Acer                                   | 2         | 1.14%   |
| Primax Electronics                     | 1         | 0.57%   |
| Novatek Microelectronics               | 1         | 0.57%   |
| Logitech                               | 1         | 0.57%   |
| DigiTech                               | 1         | 0.57%   |
| Apple                                  | 1         | 0.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD camera                                              | 17        | 9.71%   |
| Chicony Integrated Camera                                      | 10        | 5.71%   |
| Chicony HP Truevision HD                                       | 6         | 3.43%   |
| Bison Integrated Camera                                        | 6         | 3.43%   |
| Unknown USB Camera                                             | 5         | 2.86%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 2.29%   |
| Microdia Integrated_Webcam_HD                                  | 4         | 2.29%   |
| Chicony TOSHIBA Web Camera - HD                                | 4         | 2.29%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 2.29%   |
| Sonix USB2.0 HD UVC WebCam                                     | 3         | 1.71%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 3         | 1.71%   |
| Realtek Lenovo EasyCamera                                      | 3         | 1.71%   |
| Chicony HD WebCam                                              | 3         | 1.71%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 1.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 3         | 1.71%   |
| Bison HD Webcam                                                | 3         | 1.71%   |
| Suyin Asus Integrated Webcam                                   | 2         | 1.14%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 2         | 1.14%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 2         | 1.14%   |
| Silicon Motion WebCam SC-0311139N                              | 2         | 1.14%   |
| Realtek USB Camera                                             | 2         | 1.14%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.14%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.14%   |
| Luxvisions Innotech Limited Integrated Camera                  | 2         | 1.14%   |
| Lite-On Integrated Camera                                      | 2         | 1.14%   |
| Lite-On HP Webcam                                              | 2         | 1.14%   |
| Importek TOSHIBA Web Camera                                    | 2         | 1.14%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 1.14%   |
| IMC Networks Integrated Camera                                 | 2         | 1.14%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 1.14%   |
| Chicony HP Webcam                                              | 2         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 2         | 1.14%   |
| Bison NEC HD WebCam                                            | 2         | 1.14%   |
| Bison Lenovo EasyCamera                                        | 2         | 1.14%   |
| Syntek Integrated Camera                                       | 1         | 0.57%   |
| Syntek EasyCamera                                              | 1         | 0.57%   |
| Suyin VGA Webcam                                               | 1         | 0.57%   |
| Suyin HP Truevision HD                                         | 1         | 0.57%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.57%   |
| Suyin HD WebCam                                                | 1         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 36.36%  |
| Synaptics                  | 5         | 22.73%  |
| Shenzhen Goodix Technology | 4         | 18.18%  |
| Upek                       | 1         | 4.55%   |
| LighTuning Technology      | 1         | 4.55%   |
| Focal-systems.Corp         | 1         | 4.55%   |
| Elan Microelectronics      | 1         | 4.55%   |
| AuthenTec                  | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 13.64%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 3         | 13.64%  |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 13.64%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4.55%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.55%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.55%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.55%   |
| Validity Sensors Fingerprint scanner                   | 1         | 4.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.55%   |
| Synaptics UWP WBDI Device                              | 1         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 4.55%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.55%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.55%   |
| AuthenTec Fingerprint Sensor                           | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 5880                       | 1         | 33.33%  |
| Broadcom 58200                      | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 146       | 75.65%  |
| 1     | 44        | 22.8%   |
| 2     | 3         | 1.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 21        | 42%     |
| Net/wireless          | 8         | 16%     |
| Graphics card         | 6         | 12%     |
| Multimedia controller | 5         | 10%     |
| Chipcard              | 3         | 6%      |
| Bluetooth             | 3         | 6%      |
| Storage               | 2         | 4%      |
| Modem                 | 1         | 2%      |
| Camera                | 1         | 2%      |

