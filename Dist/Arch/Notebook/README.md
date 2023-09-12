Arch - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Arch.

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

Total: 5336

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion 15                 | [c251475f43](https://linux-hardware.org/?probe=c251475f43) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f33c62ab06](https://linux-hardware.org/?probe=f33c62ab06) | Sep 07, 2023 |
| HP            | ProBook 445 G7              | [373ba724e4](https://linux-hardware.org/?probe=373ba724e4) | Sep 06, 2023 |
| HP            | Pavilion dv6                | [08d38c1680](https://linux-hardware.org/?probe=08d38c1680) | Sep 06, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [a4fb146fe8](https://linux-hardware.org/?probe=a4fb146fe8) | Sep 06, 2023 |
| Acer          | Aspire E1-571               | [5d22a61587](https://linux-hardware.org/?probe=5d22a61587) | Sep 06, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | [b884752710](https://linux-hardware.org/?probe=b884752710) | Sep 06, 2023 |
| ASUSTek       | X555QG                      | [8cf63afc0f](https://linux-hardware.org/?probe=8cf63afc0f) | Sep 06, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [57764e02db](https://linux-hardware.org/?probe=57764e02db) | Sep 06, 2023 |
| Lenovo        | ThinkPad X390 20Q0002UUS    | [aab185ac48](https://linux-hardware.org/?probe=aab185ac48) | Sep 06, 2023 |
| HUAWEI        | BOM-WXX9                    | [8e0ee8ad83](https://linux-hardware.org/?probe=8e0ee8ad83) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d3e36fc6ea](https://linux-hardware.org/?probe=d3e36fc6ea) | Sep 05, 2023 |
| Acer          | Nitro AN515-46              | [bbbba2bc47](https://linux-hardware.org/?probe=bbbba2bc47) | Sep 05, 2023 |
| Samsung       | 750XDA                      | [efe919fb13](https://linux-hardware.org/?probe=efe919fb13) | Sep 05, 2023 |
| HP            | ProBook 6570b               | [f66ec50e55](https://linux-hardware.org/?probe=f66ec50e55) | Sep 05, 2023 |
| HP            | ProBook 6570b               | [9a31047350](https://linux-hardware.org/?probe=9a31047350) | Sep 05, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5e7621ae15](https://linux-hardware.org/?probe=5e7621ae15) | Sep 04, 2023 |
| Dell          | XPS 15 9500                 | [3747ee0c29](https://linux-hardware.org/?probe=3747ee0c29) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ceade9f24f](https://linux-hardware.org/?probe=ceade9f24f) | Sep 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | [522dd175b1](https://linux-hardware.org/?probe=522dd175b1) | Sep 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ0E    | [c5cdf73aa5](https://linux-hardware.org/?probe=c5cdf73aa5) | Sep 04, 2023 |
| Dell          | XPS 13 9310                 | [e30eaf0d9a](https://linux-hardware.org/?probe=e30eaf0d9a) | Sep 03, 2023 |
| HP            | EliteBook Folio 9470m       | [0fe16a99d6](https://linux-hardware.org/?probe=0fe16a99d6) | Sep 03, 2023 |
| ASUSTek       | X555LAB                     | [b8aba55b59](https://linux-hardware.org/?probe=b8aba55b59) | Sep 03, 2023 |
| Acer          | Nitro AN515-46              | [ebfb4ddd3e](https://linux-hardware.org/?probe=ebfb4ddd3e) | Sep 03, 2023 |
| MSI           | Modern 14 B11MOU            | [239c2bbc02](https://linux-hardware.org/?probe=239c2bbc02) | Sep 02, 2023 |
| Dell          | Latitude 3410               | [695e65a1f0](https://linux-hardware.org/?probe=695e65a1f0) | Sep 02, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [6736962dbe](https://linux-hardware.org/?probe=6736962dbe) | Sep 01, 2023 |
| ASUSTek       | X555LAB                     | [e7d07d7c88](https://linux-hardware.org/?probe=e7d07d7c88) | Aug 31, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [3c434cdeda](https://linux-hardware.org/?probe=3c434cdeda) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | [aad9baafe2](https://linux-hardware.org/?probe=aad9baafe2) | Aug 31, 2023 |
| MSI           | MS-7E06                     | [afd9e6ccb2](https://linux-hardware.org/?probe=afd9e6ccb2) | Aug 30, 2023 |
| HP            | Pavilion Notebook           | [86b1c6ecfa](https://linux-hardware.org/?probe=86b1c6ecfa) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | [67d6ffca34](https://linux-hardware.org/?probe=67d6ffca34) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | [e5a008be38](https://linux-hardware.org/?probe=e5a008be38) | Aug 30, 2023 |
| ASUSTek       | X555LAB                     | [ce793ccb8d](https://linux-hardware.org/?probe=ce793ccb8d) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6dd95e8115](https://linux-hardware.org/?probe=6dd95e8115) | Aug 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [aa23e296ad](https://linux-hardware.org/?probe=aa23e296ad) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7075df2d62](https://linux-hardware.org/?probe=7075df2d62) | Aug 30, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7d74c2bc61](https://linux-hardware.org/?probe=7d74c2bc61) | Aug 29, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [dcceb74a56](https://linux-hardware.org/?probe=dcceb74a56) | Aug 29, 2023 |
| Acer          | One Z1402                   | [2e917719ec](https://linux-hardware.org/?probe=2e917719ec) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | [caaf599d6a](https://linux-hardware.org/?probe=caaf599d6a) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | [f91274084a](https://linux-hardware.org/?probe=f91274084a) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | [598458b278](https://linux-hardware.org/?probe=598458b278) | Aug 28, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [15b81ebfc0](https://linux-hardware.org/?probe=15b81ebfc0) | Aug 28, 2023 |
| Dell          | Precision 3520              | [a87048ecac](https://linux-hardware.org/?probe=a87048ecac) | Aug 28, 2023 |
| Dell          | Precision 3520              | [6afb6bacac](https://linux-hardware.org/?probe=6afb6bacac) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [c2c0708639](https://linux-hardware.org/?probe=c2c0708639) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4bff36d914](https://linux-hardware.org/?probe=4bff36d914) | Aug 28, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [9b94ab3887](https://linux-hardware.org/?probe=9b94ab3887) | Aug 27, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [72e8fd41af](https://linux-hardware.org/?probe=72e8fd41af) | Aug 26, 2023 |
| Dell          | Latitude 5580               | [e16786f57e](https://linux-hardware.org/?probe=e16786f57e) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [fc59d4358f](https://linux-hardware.org/?probe=fc59d4358f) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [caf8dd1fc3](https://linux-hardware.org/?probe=caf8dd1fc3) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [3cce8305bb](https://linux-hardware.org/?probe=3cce8305bb) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [83695164cc](https://linux-hardware.org/?probe=83695164cc) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [ee4e04964c](https://linux-hardware.org/?probe=ee4e04964c) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [3ee57cbdbe](https://linux-hardware.org/?probe=3ee57cbdbe) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [f30251883f](https://linux-hardware.org/?probe=f30251883f) | Aug 25, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2707044ee5](https://linux-hardware.org/?probe=2707044ee5) | Aug 25, 2023 |
| MECHREVO      | Code01 Ver2.0               | [f5f6d366a1](https://linux-hardware.org/?probe=f5f6d366a1) | Aug 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [9938e1fbcc](https://linux-hardware.org/?probe=9938e1fbcc) | Aug 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d44597af00](https://linux-hardware.org/?probe=d44597af00) | Aug 23, 2023 |
| HP            | ProBook 445 G7              | [90faf14c05](https://linux-hardware.org/?probe=90faf14c05) | Aug 23, 2023 |
| Chuwi         | GemiBook Pro                | [95b9733408](https://linux-hardware.org/?probe=95b9733408) | Aug 23, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [34532a7998](https://linux-hardware.org/?probe=34532a7998) | Aug 23, 2023 |
| Dell          | XPS 15 9560                 | [3a3b362bd0](https://linux-hardware.org/?probe=3a3b362bd0) | Aug 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e0a5f63a8b](https://linux-hardware.org/?probe=e0a5f63a8b) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8e478e15da](https://linux-hardware.org/?probe=8e478e15da) | Aug 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [cdb0c49b6a](https://linux-hardware.org/?probe=cdb0c49b6a) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8fd1db4fee](https://linux-hardware.org/?probe=8fd1db4fee) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [2cbbb89cd4](https://linux-hardware.org/?probe=2cbbb89cd4) | Aug 21, 2023 |
| HONOR         | NMH-WDX9                    | [edc1d99b63](https://linux-hardware.org/?probe=edc1d99b63) | Aug 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2e4f8c0f7c](https://linux-hardware.org/?probe=2e4f8c0f7c) | Aug 21, 2023 |
| Lenovo        | ThinkPad P51 20HJS5WH0D     | [ae8a51b2f5](https://linux-hardware.org/?probe=ae8a51b2f5) | Aug 21, 2023 |
| Acer          | Aspire E5-573G              | [005b310c55](https://linux-hardware.org/?probe=005b310c55) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | [19675df004](https://linux-hardware.org/?probe=19675df004) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | [b156da40ac](https://linux-hardware.org/?probe=b156da40ac) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | [8b4709e684](https://linux-hardware.org/?probe=8b4709e684) | Aug 20, 2023 |
| MSI           | GF75 Thin 10SC              | [f50df27008](https://linux-hardware.org/?probe=f50df27008) | Aug 20, 2023 |
| Alienware     | m15 R4                      | [46f36f26ff](https://linux-hardware.org/?probe=46f36f26ff) | Aug 20, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e33524b456](https://linux-hardware.org/?probe=e33524b456) | Aug 20, 2023 |
| Alienware     | m15 R4                      | [cf9a9e0729](https://linux-hardware.org/?probe=cf9a9e0729) | Aug 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [0585143fdc](https://linux-hardware.org/?probe=0585143fdc) | Aug 19, 2023 |
| Dell          | XPS 15 9500                 | [006d138f62](https://linux-hardware.org/?probe=006d138f62) | Aug 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [c95ab5ea6e](https://linux-hardware.org/?probe=c95ab5ea6e) | Aug 18, 2023 |
| Dell          | Inspiron 7591               | [2e09db6501](https://linux-hardware.org/?probe=2e09db6501) | Aug 18, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [1289521063](https://linux-hardware.org/?probe=1289521063) | Aug 18, 2023 |
| ASUSTek       | GL552VX                     | [fbe195ec09](https://linux-hardware.org/?probe=fbe195ec09) | Aug 17, 2023 |
| ASUSTek       | GL552VX                     | [37a66a073b](https://linux-hardware.org/?probe=37a66a073b) | Aug 17, 2023 |
| Notebook      | NS50MU                      | [37abf5de2d](https://linux-hardware.org/?probe=37abf5de2d) | Aug 17, 2023 |
| HUAWEI        | NBD-WXX9                    | [3a7f4ca491](https://linux-hardware.org/?probe=3a7f4ca491) | Aug 17, 2023 |
| ASUSTek       | K54HR                       | [14ea4148dc](https://linux-hardware.org/?probe=14ea4148dc) | Aug 17, 2023 |
| MSI           | GF75 Thin 9SCSR             | [365fe49e34](https://linux-hardware.org/?probe=365fe49e34) | Aug 17, 2023 |
| Acer          | Swift SFX14-41G             | [576626db19](https://linux-hardware.org/?probe=576626db19) | Aug 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [1b29161809](https://linux-hardware.org/?probe=1b29161809) | Aug 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | [fd91c311ff](https://linux-hardware.org/?probe=fd91c311ff) | Aug 16, 2023 |
| HP            | Laptop 15-db0xxx            | [73640f7f83](https://linux-hardware.org/?probe=73640f7f83) | Aug 16, 2023 |
| HUAWEI        | WRT-WX9                     | [39a98650a3](https://linux-hardware.org/?probe=39a98650a3) | Aug 16, 2023 |
| Timi          | A35S                        | [7f78fd50bd](https://linux-hardware.org/?probe=7f78fd50bd) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [2a3b142ddd](https://linux-hardware.org/?probe=2a3b142ddd) | Aug 16, 2023 |
| Dell          | Latitude 5300               | [506c05d30c](https://linux-hardware.org/?probe=506c05d30c) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [67a1535765](https://linux-hardware.org/?probe=67a1535765) | Aug 15, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [3750dc2cb1](https://linux-hardware.org/?probe=3750dc2cb1) | Aug 15, 2023 |
| Acer          | Swift SF314-71              | [b78f4bf01d](https://linux-hardware.org/?probe=b78f4bf01d) | Aug 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d6925a9c7a](https://linux-hardware.org/?probe=d6925a9c7a) | Aug 15, 2023 |
| Valve         | Jupiter                     | [acf70a31a9](https://linux-hardware.org/?probe=acf70a31a9) | Aug 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [bbe00bbe48](https://linux-hardware.org/?probe=bbe00bbe48) | Aug 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [10f2a6448d](https://linux-hardware.org/?probe=10f2a6448d) | Aug 14, 2023 |
| ASUSTek       | GL752VW                     | [17d837907e](https://linux-hardware.org/?probe=17d837907e) | Aug 14, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c822a4c96f](https://linux-hardware.org/?probe=c822a4c96f) | Aug 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [d344d7ada0](https://linux-hardware.org/?probe=d344d7ada0) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5286543cae](https://linux-hardware.org/?probe=5286543cae) | Aug 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [464dc037bd](https://linux-hardware.org/?probe=464dc037bd) | Aug 13, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [a6212b25ea](https://linux-hardware.org/?probe=a6212b25ea) | Aug 13, 2023 |
| Acer          | Aspire 7750G                | [494c725472](https://linux-hardware.org/?probe=494c725472) | Aug 13, 2023 |
| Dell          | XPS 13 9310                 | [11a7488d83](https://linux-hardware.org/?probe=11a7488d83) | Aug 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e0e0c962d5](https://linux-hardware.org/?probe=e0e0c962d5) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49662a8ac9](https://linux-hardware.org/?probe=49662a8ac9) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c946b79f5a](https://linux-hardware.org/?probe=c946b79f5a) | Aug 12, 2023 |
| Alienware     | 15                          | [d6c9c4f931](https://linux-hardware.org/?probe=d6c9c4f931) | Aug 12, 2023 |
| Acer          | Aspire E1-571G              | [ca51aaad9f](https://linux-hardware.org/?probe=ca51aaad9f) | Aug 12, 2023 |
| Timi          | RedmiBook Pro 15S           | [20559d710a](https://linux-hardware.org/?probe=20559d710a) | Aug 12, 2023 |
| HP            | EliteBook 840 G1            | [95d93fda2c](https://linux-hardware.org/?probe=95d93fda2c) | Aug 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [79889c3f89](https://linux-hardware.org/?probe=79889c3f89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7fe6adce5e](https://linux-hardware.org/?probe=7fe6adce5e) | Aug 10, 2023 |
| Dell          | Inspiron 5570               | [3771669b84](https://linux-hardware.org/?probe=3771669b84) | Aug 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [89cb081c1f](https://linux-hardware.org/?probe=89cb081c1f) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4236W1W       | [0b8fc947af](https://linux-hardware.org/?probe=0b8fc947af) | Aug 10, 2023 |
| Lenovo        | ThinkPad P51 20HH0015IX     | [77c11473b2](https://linux-hardware.org/?probe=77c11473b2) | Aug 10, 2023 |
| Dell          | Inspiron 5567               | [fdfeffb5f3](https://linux-hardware.org/?probe=fdfeffb5f3) | Aug 10, 2023 |
| Dell          | Inspiron 5567               | [71424c4380](https://linux-hardware.org/?probe=71424c4380) | Aug 10, 2023 |
| Acer          | Aspire A514-53              | [26e60daa62](https://linux-hardware.org/?probe=26e60daa62) | Aug 10, 2023 |
| HP            | Pavilion 17                 | [65733120b0](https://linux-hardware.org/?probe=65733120b0) | Aug 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [51fa860c87](https://linux-hardware.org/?probe=51fa860c87) | Aug 09, 2023 |
| Acer          | Swift SF114-32              | [3474fa639e](https://linux-hardware.org/?probe=3474fa639e) | Aug 08, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [3cd08fb125](https://linux-hardware.org/?probe=3cd08fb125) | Aug 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [ffd0be48c6](https://linux-hardware.org/?probe=ffd0be48c6) | Aug 08, 2023 |
| Dell          | Inspiron 13-7353            | [0b797c9368](https://linux-hardware.org/?probe=0b797c9368) | Aug 08, 2023 |
| Dell          | Inspiron 13-7353            | [90fbc716ed](https://linux-hardware.org/?probe=90fbc716ed) | Aug 07, 2023 |
| Lenovo        | Legion S7 15ARH5 82HM       | [044df6f82e](https://linux-hardware.org/?probe=044df6f82e) | Aug 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [5510e9c316](https://linux-hardware.org/?probe=5510e9c316) | Aug 06, 2023 |
| ASUSTek       | K73SV                       | [c908f2bfdd](https://linux-hardware.org/?probe=c908f2bfdd) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | [0219350ae0](https://linux-hardware.org/?probe=0219350ae0) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | [350a405f33](https://linux-hardware.org/?probe=350a405f33) | Aug 05, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [21eaf09dc9](https://linux-hardware.org/?probe=21eaf09dc9) | Aug 05, 2023 |
| Dell          | Latitude E5440              | [f6981c56b7](https://linux-hardware.org/?probe=f6981c56b7) | Aug 05, 2023 |
| HP            | OMEN by Laptop              | [78566a197e](https://linux-hardware.org/?probe=78566a197e) | Aug 05, 2023 |
| Acer          | Nitro AN515-54              | [c4d1667ffe](https://linux-hardware.org/?probe=c4d1667ffe) | Aug 05, 2023 |
| Dell          | Inspiron 14-3462            | [9300232981](https://linux-hardware.org/?probe=9300232981) | Aug 05, 2023 |
| HP            | EliteBook 840 G2            | [64810e5a10](https://linux-hardware.org/?probe=64810e5a10) | Aug 05, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [f1e284ec93](https://linux-hardware.org/?probe=f1e284ec93) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5799f1a89c](https://linux-hardware.org/?probe=5799f1a89c) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [058011da0f](https://linux-hardware.org/?probe=058011da0f) | Aug 04, 2023 |
| Chuwi         | GemiBook Pro                | [87ecdcb4bd](https://linux-hardware.org/?probe=87ecdcb4bd) | Aug 04, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [59dda0e2b7](https://linux-hardware.org/?probe=59dda0e2b7) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| HP            | Notebook                    | [9b9a2bd44a](https://linux-hardware.org/?probe=9b9a2bd44a) | Aug 04, 2023 |
| PC Special... | Lafite Pro III 17           | [702cdf4138](https://linux-hardware.org/?probe=702cdf4138) | Aug 03, 2023 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [a251ad988c](https://linux-hardware.org/?probe=a251ad988c) | Aug 03, 2023 |
| Acer          | Predator PHN16-71           | [1d1937f1d6](https://linux-hardware.org/?probe=1d1937f1d6) | Aug 03, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [c96666b80d](https://linux-hardware.org/?probe=c96666b80d) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [67d851300e](https://linux-hardware.org/?probe=67d851300e) | Aug 03, 2023 |
| Timi          | A7S                         | [7de693ff63](https://linux-hardware.org/?probe=7de693ff63) | Aug 03, 2023 |
| LG Electro... | 16Z90R-K.ADB9U1             | [d3a9e05559](https://linux-hardware.org/?probe=d3a9e05559) | Aug 02, 2023 |
| Dell          | XPS 15 9500                 | [5c8ad99a3c](https://linux-hardware.org/?probe=5c8ad99a3c) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [32d205bbdf](https://linux-hardware.org/?probe=32d205bbdf) | Aug 02, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [6cfc0b2281](https://linux-hardware.org/?probe=6cfc0b2281) | Aug 01, 2023 |
| Packard Be... | EasyNote TJ65               | [e5193cc5d3](https://linux-hardware.org/?probe=e5193cc5d3) | Aug 01, 2023 |
| HUAWEI        | KPR-WX9                     | [8918c544fe](https://linux-hardware.org/?probe=8918c544fe) | Aug 01, 2023 |
| Dell          | Latitude 5590               | [466fdce7aa](https://linux-hardware.org/?probe=466fdce7aa) | Aug 01, 2023 |
| Apple         | MacBookPro14,1              | [cb322d77a4](https://linux-hardware.org/?probe=cb322d77a4) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f7be9307b1](https://linux-hardware.org/?probe=f7be9307b1) | Jul 31, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [91887235b2](https://linux-hardware.org/?probe=91887235b2) | Jul 31, 2023 |
| Dell          | G15 5511                    | [278d65cdc0](https://linux-hardware.org/?probe=278d65cdc0) | Jul 31, 2023 |
| Dell          | G15 5511                    | [e4570caa8f](https://linux-hardware.org/?probe=e4570caa8f) | Jul 31, 2023 |
| Dell          | Latitude E6400              | [5863677081](https://linux-hardware.org/?probe=5863677081) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50s 20FLCTO1WW    | [1594795f9e](https://linux-hardware.org/?probe=1594795f9e) | Jul 31, 2023 |
| Acer          | Aspire A315-53              | [28ff56233b](https://linux-hardware.org/?probe=28ff56233b) | Jul 30, 2023 |
| Dell          | Latitude 5421               | [3872b1f799](https://linux-hardware.org/?probe=3872b1f799) | Jul 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | [5e1021c76b](https://linux-hardware.org/?probe=5e1021c76b) | Jul 30, 2023 |
| Razer         | Blade                       | [6c3ef3aa59](https://linux-hardware.org/?probe=6c3ef3aa59) | Jul 29, 2023 |
| HP            | EliteBook 745 G3            | [30e5e63466](https://linux-hardware.org/?probe=30e5e63466) | Jul 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | [6426edf740](https://linux-hardware.org/?probe=6426edf740) | Jul 29, 2023 |
| HP            | ProBook 455R G6             | [3731e7465c](https://linux-hardware.org/?probe=3731e7465c) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [d94c3cc0e8](https://linux-hardware.org/?probe=d94c3cc0e8) | Jul 28, 2023 |
| Acer          | Aspire A517-53              | [41c9602cac](https://linux-hardware.org/?probe=41c9602cac) | Jul 28, 2023 |
| Acer          | Aspire 5350                 | [698672b19c](https://linux-hardware.org/?probe=698672b19c) | Jul 28, 2023 |
| MSI           | Raider GE78HX 13VI          | [0b179ca997](https://linux-hardware.org/?probe=0b179ca997) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ea402f269e](https://linux-hardware.org/?probe=ea402f269e) | Jul 28, 2023 |
| Google        | Atlas                       | [c3f0326575](https://linux-hardware.org/?probe=c3f0326575) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [407859fa58](https://linux-hardware.org/?probe=407859fa58) | Jul 27, 2023 |
| HP            | ProBook 4530s               | [46852380f2](https://linux-hardware.org/?probe=46852380f2) | Jul 27, 2023 |
| HUAWEI        | MACHC-WAX9                  | [bf3f7b4c2d](https://linux-hardware.org/?probe=bf3f7b4c2d) | Jul 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6546d49225](https://linux-hardware.org/?probe=6546d49225) | Jul 27, 2023 |
| HUAWEI        | KPR-WX9                     | [2231e66b3d](https://linux-hardware.org/?probe=2231e66b3d) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [1bac11c715](https://linux-hardware.org/?probe=1bac11c715) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [1409af2a38](https://linux-hardware.org/?probe=1409af2a38) | Jul 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6c978ec74d](https://linux-hardware.org/?probe=6c978ec74d) | Jul 26, 2023 |
| Acer          | Aspire A514-54              | [787270abee](https://linux-hardware.org/?probe=787270abee) | Jul 25, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7910b0c067](https://linux-hardware.org/?probe=7910b0c067) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [412bc51f72](https://linux-hardware.org/?probe=412bc51f72) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | [e1fea727ff](https://linux-hardware.org/?probe=e1fea727ff) | Jul 24, 2023 |
| Gigabyte      | G5 KE                       | [4837040c2a](https://linux-hardware.org/?probe=4837040c2a) | Jul 24, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [cb7e913e03](https://linux-hardware.org/?probe=cb7e913e03) | Jul 24, 2023 |
| Acer          | Nitro AN515-46              | [a2d73523d4](https://linux-hardware.org/?probe=a2d73523d4) | Jul 24, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [313f3aa210](https://linux-hardware.org/?probe=313f3aa210) | Jul 23, 2023 |
| Acer          | Nitro AN515-54              | [f1db825d10](https://linux-hardware.org/?probe=f1db825d10) | Jul 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [3bd5c9d59c](https://linux-hardware.org/?probe=3bd5c9d59c) | Jul 23, 2023 |
| HUAWEI        | HVY-WXX9                    | [44958ef86b](https://linux-hardware.org/?probe=44958ef86b) | Jul 23, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [0e123e6d85](https://linux-hardware.org/?probe=0e123e6d85) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [4222b801a9](https://linux-hardware.org/?probe=4222b801a9) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [ddb8dbe4e4](https://linux-hardware.org/?probe=ddb8dbe4e4) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [82242fa0a6](https://linux-hardware.org/?probe=82242fa0a6) | Jul 23, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [a6e2f105ed](https://linux-hardware.org/?probe=a6e2f105ed) | Jul 23, 2023 |
| Infinix       | INBOOK X2 GEN11             | [2b3d4271bf](https://linux-hardware.org/?probe=2b3d4271bf) | Jul 22, 2023 |
| HUAWEI        | MACHC-WAX9                  | [fdbe29a1db](https://linux-hardware.org/?probe=fdbe29a1db) | Jul 22, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [45065697ac](https://linux-hardware.org/?probe=45065697ac) | Jul 22, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [fd2bcebb1d](https://linux-hardware.org/?probe=fd2bcebb1d) | Jul 22, 2023 |
| Acer          | Aspire V5-551               | [8a13138f82](https://linux-hardware.org/?probe=8a13138f82) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | [b2f5443fc2](https://linux-hardware.org/?probe=b2f5443fc2) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | [3161baf648](https://linux-hardware.org/?probe=3161baf648) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [55639a6416](https://linux-hardware.org/?probe=55639a6416) | Jul 21, 2023 |
| HP            | ProBook 4530s               | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8b2077101c](https://linux-hardware.org/?probe=8b2077101c) | Jul 21, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [daff830182](https://linux-hardware.org/?probe=daff830182) | Jul 21, 2023 |
| Dell          | Latitude 5580               | [f115a04168](https://linux-hardware.org/?probe=f115a04168) | Jul 20, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [cb2cdb1a94](https://linux-hardware.org/?probe=cb2cdb1a94) | Jul 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9a2d353d76](https://linux-hardware.org/?probe=9a2d353d76) | Jul 20, 2023 |
| Panasonic     | CFSZ5-3                     | [9eb560d292](https://linux-hardware.org/?probe=9eb560d292) | Jul 20, 2023 |
| ASUSTek       | N501VW                      | [08cd5a81b2](https://linux-hardware.org/?probe=08cd5a81b2) | Jul 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [9b44d7bd03](https://linux-hardware.org/?probe=9b44d7bd03) | Jul 19, 2023 |
| HP            | Pavilion Notebook           | [6623b71de2](https://linux-hardware.org/?probe=6623b71de2) | Jul 19, 2023 |
| Dell          | Inspiron 7400               | [f145687601](https://linux-hardware.org/?probe=f145687601) | Jul 19, 2023 |
| Avell High... | B.ON                        | [bf1f683383](https://linux-hardware.org/?probe=bf1f683383) | Jul 18, 2023 |
| Apple         | MacBookPro11,2              | [3121fc5450](https://linux-hardware.org/?probe=3121fc5450) | Jul 18, 2023 |
| Lenovo        | B50-45 20388                | [54b4137669](https://linux-hardware.org/?probe=54b4137669) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [50e78d6df5](https://linux-hardware.org/?probe=50e78d6df5) | Jul 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [53c97d91d4](https://linux-hardware.org/?probe=53c97d91d4) | Jul 18, 2023 |
| HP            | EliteBook 830 G5            | [42eb1edbb6](https://linux-hardware.org/?probe=42eb1edbb6) | Jul 17, 2023 |
| Apple         | MacBookPro11,2              | [6bebb2e751](https://linux-hardware.org/?probe=6bebb2e751) | Jul 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [13ba381894](https://linux-hardware.org/?probe=13ba381894) | Jul 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | [b53aa427b9](https://linux-hardware.org/?probe=b53aa427b9) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | [5be1306636](https://linux-hardware.org/?probe=5be1306636) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | [2b81f8a707](https://linux-hardware.org/?probe=2b81f8a707) | Jul 17, 2023 |
| HP            | Pavilion 17                 | [7c39d851fd](https://linux-hardware.org/?probe=7c39d851fd) | Jul 16, 2023 |
| Lenovo        | M490s 20215                 | [d029f6cf0b](https://linux-hardware.org/?probe=d029f6cf0b) | Jul 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2f2887fc32](https://linux-hardware.org/?probe=2f2887fc32) | Jul 15, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c36495481b](https://linux-hardware.org/?probe=c36495481b) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | [97e2731292](https://linux-hardware.org/?probe=97e2731292) | Jul 15, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [e204dc6cf1](https://linux-hardware.org/?probe=e204dc6cf1) | Jul 15, 2023 |
| HUAWEI        | HN-WX9X                     | [9868eab45f](https://linux-hardware.org/?probe=9868eab45f) | Jul 14, 2023 |
| Acer          | Swift SF313-52              | [3b393fc916](https://linux-hardware.org/?probe=3b393fc916) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [e042e7c94e](https://linux-hardware.org/?probe=e042e7c94e) | Jul 14, 2023 |
| Dell          | XPS 15 7590                 | [28b21d099f](https://linux-hardware.org/?probe=28b21d099f) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S4NR00    | [281c5a429c](https://linux-hardware.org/?probe=281c5a429c) | Jul 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [793289bc48](https://linux-hardware.org/?probe=793289bc48) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [934947072a](https://linux-hardware.org/?probe=934947072a) | Jul 13, 2023 |
| Acer          | TravelMate P246-MG          | [62348fa6ed](https://linux-hardware.org/?probe=62348fa6ed) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [adab548264](https://linux-hardware.org/?probe=adab548264) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [ce2deb4b1d](https://linux-hardware.org/?probe=ce2deb4b1d) | Jul 13, 2023 |
| Dell          | Inspiron 7577               | [a9b5963254](https://linux-hardware.org/?probe=a9b5963254) | Jul 13, 2023 |
| Dell          | Latitude 7480               | [a375f7685c](https://linux-hardware.org/?probe=a375f7685c) | Jul 13, 2023 |
| Lenovo        | ThinkPad T550 20CJS0P300    | [2c96c19647](https://linux-hardware.org/?probe=2c96c19647) | Jul 13, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [23e018569e](https://linux-hardware.org/?probe=23e018569e) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [392b02a797](https://linux-hardware.org/?probe=392b02a797) | Jul 13, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [222924f1c2](https://linux-hardware.org/?probe=222924f1c2) | Jul 12, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e2792f841d](https://linux-hardware.org/?probe=e2792f841d) | Jul 12, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [08bbd89b8c](https://linux-hardware.org/?probe=08bbd89b8c) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [23b123605f](https://linux-hardware.org/?probe=23b123605f) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [38f91b870c](https://linux-hardware.org/?probe=38f91b870c) | Jul 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b89cab90c0](https://linux-hardware.org/?probe=b89cab90c0) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e0c7ec0cbc](https://linux-hardware.org/?probe=e0c7ec0cbc) | Jul 11, 2023 |
| Dell          | Precision M4700             | [69a672ec44](https://linux-hardware.org/?probe=69a672ec44) | Jul 11, 2023 |
| Acer          | SF714-52T                   | [97b079be51](https://linux-hardware.org/?probe=97b079be51) | Jul 10, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [de7dbebf49](https://linux-hardware.org/?probe=de7dbebf49) | Jul 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [42aaaa0acb](https://linux-hardware.org/?probe=42aaaa0acb) | Jul 09, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [ee5ef8132f](https://linux-hardware.org/?probe=ee5ef8132f) | Jul 09, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [866af72fb6](https://linux-hardware.org/?probe=866af72fb6) | Jul 09, 2023 |
| Lenovo        | Legion R9000X ARHA7 82UG    | [5da53d3f61](https://linux-hardware.org/?probe=5da53d3f61) | Jul 09, 2023 |
| HUAWEI        | HN-WX9X                     | [c01a765f59](https://linux-hardware.org/?probe=c01a765f59) | Jul 09, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [214dd1ad57](https://linux-hardware.org/?probe=214dd1ad57) | Jul 09, 2023 |
| HP            | ProBook 6460b               | [af3006237f](https://linux-hardware.org/?probe=af3006237f) | Jul 09, 2023 |
| HP            | OMEN by Laptop              | [87a1bbb5cc](https://linux-hardware.org/?probe=87a1bbb5cc) | Jul 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [72af2d01c0](https://linux-hardware.org/?probe=72af2d01c0) | Jul 08, 2023 |
| Apple         | MacBookPro13,1              | [3a64eabd9b](https://linux-hardware.org/?probe=3a64eabd9b) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [dd8bd37036](https://linux-hardware.org/?probe=dd8bd37036) | Jul 08, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [6f3284cac3](https://linux-hardware.org/?probe=6f3284cac3) | Jul 07, 2023 |
| Purism        | Librem 14                   | [18db47d3f6](https://linux-hardware.org/?probe=18db47d3f6) | Jul 07, 2023 |
| HP            | Laptop 14s-dk0xxx           | [8f01854bc7](https://linux-hardware.org/?probe=8f01854bc7) | Jul 07, 2023 |
| Medion        | Erazer P7643 MD60299        | [2c74ffe58f](https://linux-hardware.org/?probe=2c74ffe58f) | Jul 07, 2023 |
| Lenovo        | B50-70 20384                | [8a0a97b362](https://linux-hardware.org/?probe=8a0a97b362) | Jul 07, 2023 |
| HP            | EliteBook 840 G1            | [2fd3eada0f](https://linux-hardware.org/?probe=2fd3eada0f) | Jul 07, 2023 |
| Lenovo        | Legion R9000P2021 82JS      | [0376dd3cbd](https://linux-hardware.org/?probe=0376dd3cbd) | Jul 07, 2023 |
| HP            | ENVY 15                     | [d519c2699c](https://linux-hardware.org/?probe=d519c2699c) | Jul 06, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [cf134cbdd9](https://linux-hardware.org/?probe=cf134cbdd9) | Jul 06, 2023 |
| Dell          | G3 3590                     | [e3cfb2968a](https://linux-hardware.org/?probe=e3cfb2968a) | Jul 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [0fc498ccfb](https://linux-hardware.org/?probe=0fc498ccfb) | Jul 06, 2023 |
| ASUSTek       | G750JZA                     | [fb2477dd61](https://linux-hardware.org/?probe=fb2477dd61) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [e17ab8bbe7](https://linux-hardware.org/?probe=e17ab8bbe7) | Jul 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e555b073b5](https://linux-hardware.org/?probe=e555b073b5) | Jul 05, 2023 |
| Acer          | TravelMate P246-MG          | [e1e4548a49](https://linux-hardware.org/?probe=e1e4548a49) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [b11fe33b8c](https://linux-hardware.org/?probe=b11fe33b8c) | Jul 05, 2023 |
| Dell          | G3 3590                     | [35906fded9](https://linux-hardware.org/?probe=35906fded9) | Jul 05, 2023 |
| Dell          | Latitude 7350               | [bc00420bfc](https://linux-hardware.org/?probe=bc00420bfc) | Jul 05, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c387c4fbf1](https://linux-hardware.org/?probe=c387c4fbf1) | Jul 04, 2023 |
| Dell          | Latitude 7350               | [14d41ff667](https://linux-hardware.org/?probe=14d41ff667) | Jul 04, 2023 |
| ASUSTek       | G750JZA                     | [72fc73822c](https://linux-hardware.org/?probe=72fc73822c) | Jul 04, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7ee43d9cad](https://linux-hardware.org/?probe=7ee43d9cad) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [90b6b19a97](https://linux-hardware.org/?probe=90b6b19a97) | Jul 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [25d3329df1](https://linux-hardware.org/?probe=25d3329df1) | Jul 03, 2023 |
| ASUSTek       | 1015BX                      | [c4bc43a932](https://linux-hardware.org/?probe=c4bc43a932) | Jul 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [da24c07da6](https://linux-hardware.org/?probe=da24c07da6) | Jul 02, 2023 |
| Lenovo        | ThinkPad T520 4243B65       | [07584ce70c](https://linux-hardware.org/?probe=07584ce70c) | Jul 02, 2023 |
| Lenovo        | ThinkPad T410 2537PW4       | [10079a3e26](https://linux-hardware.org/?probe=10079a3e26) | Jul 02, 2023 |
| Lenovo        | ThinkPad T530 2429AA9       | [708fe309bc](https://linux-hardware.org/?probe=708fe309bc) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | [d69c578d83](https://linux-hardware.org/?probe=d69c578d83) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | [2e20df184f](https://linux-hardware.org/?probe=2e20df184f) | Jul 02, 2023 |
| Dell          | Inspiron 7460               | [07f04b7377](https://linux-hardware.org/?probe=07f04b7377) | Jul 01, 2023 |
| Dell          | Inspiron 7460               | [65c2a81637](https://linux-hardware.org/?probe=65c2a81637) | Jul 01, 2023 |
| Apple         | MacBookPro11,1              | [998267633e](https://linux-hardware.org/?probe=998267633e) | Jul 01, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [2ba1cce30e](https://linux-hardware.org/?probe=2ba1cce30e) | Jul 01, 2023 |
| Lenovo        | ThinkPad E490 20N80017RT    | [a2a1011725](https://linux-hardware.org/?probe=a2a1011725) | Jun 30, 2023 |
| Chuwi         | CoreBook XPro               | [501d899938](https://linux-hardware.org/?probe=501d899938) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [31db4fffd0](https://linux-hardware.org/?probe=31db4fffd0) | Jun 30, 2023 |
| HP            | EliteBook 830 G6            | [6c6741deb9](https://linux-hardware.org/?probe=6c6741deb9) | Jun 30, 2023 |
| Dell          | Latitude E5440              | [1fd8c9652a](https://linux-hardware.org/?probe=1fd8c9652a) | Jun 30, 2023 |
| HP            | Pavilion Notebook           | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| Lenovo        | 3000 G530 4151/200          | [f3482421c4](https://linux-hardware.org/?probe=f3482421c4) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [9814b54843](https://linux-hardware.org/?probe=9814b54843) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [5b82e1dd39](https://linux-hardware.org/?probe=5b82e1dd39) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [b62328e801](https://linux-hardware.org/?probe=b62328e801) | Jun 28, 2023 |
| HP            | OMEN by Laptop              | [971852cb38](https://linux-hardware.org/?probe=971852cb38) | Jun 28, 2023 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | [18847b167a](https://linux-hardware.org/?probe=18847b167a) | Jun 28, 2023 |
| COLORFUL      | X16 Pro 23                  | [656cf52198](https://linux-hardware.org/?probe=656cf52198) | Jun 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | [6615a04065](https://linux-hardware.org/?probe=6615a04065) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| Lenovo        | Legion Y7000 81FW           | [c0af461776](https://linux-hardware.org/?probe=c0af461776) | Jun 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [47451d9f30](https://linux-hardware.org/?probe=47451d9f30) | Jun 27, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| GPU Compan... | GWTN141-10                  | [474833dcec](https://linux-hardware.org/?probe=474833dcec) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [85c3968edc](https://linux-hardware.org/?probe=85c3968edc) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | [1a17b8ee06](https://linux-hardware.org/?probe=1a17b8ee06) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | [2fd779cefc](https://linux-hardware.org/?probe=2fd779cefc) | Jun 26, 2023 |
| Dell          | Precision 5570              | [dbf68aa669](https://linux-hardware.org/?probe=dbf68aa669) | Jun 26, 2023 |
| HP            | EliteBook 840 G3            | [ef2e8da48a](https://linux-hardware.org/?probe=ef2e8da48a) | Jun 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [00cf0b0faa](https://linux-hardware.org/?probe=00cf0b0faa) | Jun 26, 2023 |
| Dell          | XPS 9315                    | [41bb8bd332](https://linux-hardware.org/?probe=41bb8bd332) | Jun 25, 2023 |
| Fujitsu       | LIFEBOOK S751               | [94fe70521f](https://linux-hardware.org/?probe=94fe70521f) | Jun 25, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [ba30e1369c](https://linux-hardware.org/?probe=ba30e1369c) | Jun 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8b0180f4d4](https://linux-hardware.org/?probe=8b0180f4d4) | Jun 25, 2023 |
| ASUSTek       | N501VW                      | [7513f535f9](https://linux-hardware.org/?probe=7513f535f9) | Jun 25, 2023 |
| HUAWEI        | BOD-WXX9                    | [aa75d0dace](https://linux-hardware.org/?probe=aa75d0dace) | Jun 25, 2023 |
| Notebook      | PCX0DX                      | [d02e6a9fa6](https://linux-hardware.org/?probe=d02e6a9fa6) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [2b4069db98](https://linux-hardware.org/?probe=2b4069db98) | Jun 25, 2023 |
| MSI           | GS63 7RD                    | [310191e110](https://linux-hardware.org/?probe=310191e110) | Jun 24, 2023 |
| HONOR         | GLO-GXXX                    | [0e22fb1d65](https://linux-hardware.org/?probe=0e22fb1d65) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | [dcfef21d2b](https://linux-hardware.org/?probe=dcfef21d2b) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | [62d08bd4ca](https://linux-hardware.org/?probe=62d08bd4ca) | Jun 24, 2023 |
| Dell          | Precision 3581              | [2e960d89db](https://linux-hardware.org/?probe=2e960d89db) | Jun 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2faa400326](https://linux-hardware.org/?probe=2faa400326) | Jun 23, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [856acf81ed](https://linux-hardware.org/?probe=856acf81ed) | Jun 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [83d89a8751](https://linux-hardware.org/?probe=83d89a8751) | Jun 22, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [928f167dee](https://linux-hardware.org/?probe=928f167dee) | Jun 22, 2023 |
| Acer          | Nitro AN515-58              | [cbf5b19c76](https://linux-hardware.org/?probe=cbf5b19c76) | Jun 21, 2023 |
| Casper        | EXCALIBUR G770              | [9fef8732b6](https://linux-hardware.org/?probe=9fef8732b6) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | [baab7764b1](https://linux-hardware.org/?probe=baab7764b1) | Jun 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26a3b9b3e9](https://linux-hardware.org/?probe=26a3b9b3e9) | Jun 21, 2023 |
| Dell          | Inspiron 5737               | [a7e4d1a6bd](https://linux-hardware.org/?probe=a7e4d1a6bd) | Jun 21, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [e67932c5a0](https://linux-hardware.org/?probe=e67932c5a0) | Jun 21, 2023 |
| Acer          | Nitro AN517-51              | [b4423e6ac2](https://linux-hardware.org/?probe=b4423e6ac2) | Jun 20, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [dd152b03bc](https://linux-hardware.org/?probe=dd152b03bc) | Jun 20, 2023 |
| Dell          | Inspiron 3558               | [3375eaaeb3](https://linux-hardware.org/?probe=3375eaaeb3) | Jun 20, 2023 |
| Lenovo        | ThinkPad T590 20N5S14V00    | [6f81cc6d57](https://linux-hardware.org/?probe=6f81cc6d57) | Jun 19, 2023 |
| HASEE Comp... | NH5x_NH7x_HHx_HJx_HKx       | [2c0be5d314](https://linux-hardware.org/?probe=2c0be5d314) | Jun 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [5bd2521f5c](https://linux-hardware.org/?probe=5bd2521f5c) | Jun 19, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [6a63f44627](https://linux-hardware.org/?probe=6a63f44627) | Jun 19, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [c1472b1c25](https://linux-hardware.org/?probe=c1472b1c25) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2324CD1       | [9ee6ed4144](https://linux-hardware.org/?probe=9ee6ed4144) | Jun 18, 2023 |
| Dell          | Latitude E7440              | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| Acer          | Aspire A314-22              | [676efbb266](https://linux-hardware.org/?probe=676efbb266) | Jun 18, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [d5ba369651](https://linux-hardware.org/?probe=d5ba369651) | Jun 17, 2023 |
| HP            | Pavilion dv7                | [f010c487a1](https://linux-hardware.org/?probe=f010c487a1) | Jun 17, 2023 |
| Acer          | Nitro AN517-51              | [d2f2f70083](https://linux-hardware.org/?probe=d2f2f70083) | Jun 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [bfa70344e3](https://linux-hardware.org/?probe=bfa70344e3) | Jun 16, 2023 |
| Samsung       | 750XDA                      | [e04dd13d49](https://linux-hardware.org/?probe=e04dd13d49) | Jun 16, 2023 |
| Dell          | XPS 13 9350                 | [1150629ceb](https://linux-hardware.org/?probe=1150629ceb) | Jun 16, 2023 |
| Lenovo        | ThinkPad E480 20KNA047CD    | [918de7de03](https://linux-hardware.org/?probe=918de7de03) | Jun 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [67b278ea0e](https://linux-hardware.org/?probe=67b278ea0e) | Jun 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0TG00    | [628c8fb554](https://linux-hardware.org/?probe=628c8fb554) | Jun 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a6f63a08e2](https://linux-hardware.org/?probe=a6f63a08e2) | Jun 15, 2023 |
| Acer          | Aspire A715-41G             | [66cc56555d](https://linux-hardware.org/?probe=66cc56555d) | Jun 15, 2023 |
| Lenovo        | ThinkPad L420 78545EG       | [bb42ee1009](https://linux-hardware.org/?probe=bb42ee1009) | Jun 14, 2023 |
| HP            | ProBook 650 G2              | [535950bae5](https://linux-hardware.org/?probe=535950bae5) | Jun 14, 2023 |
| ASUSTek       | P553UA                      | [2543eb4ce8](https://linux-hardware.org/?probe=2543eb4ce8) | Jun 14, 2023 |
| HP            | Laptop 15s-eq2xxx           | [20c6793733](https://linux-hardware.org/?probe=20c6793733) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [d2e4302f28](https://linux-hardware.org/?probe=d2e4302f28) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [e858489484](https://linux-hardware.org/?probe=e858489484) | Jun 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [6fcdcaa48c](https://linux-hardware.org/?probe=6fcdcaa48c) | Jun 12, 2023 |
| Acer          | Aspire A715-41G             | [7082d05ede](https://linux-hardware.org/?probe=7082d05ede) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | [41526d21bc](https://linux-hardware.org/?probe=41526d21bc) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | [6154060edd](https://linux-hardware.org/?probe=6154060edd) | Jun 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [2aaa4324d0](https://linux-hardware.org/?probe=2aaa4324d0) | Jun 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [ba129cd52d](https://linux-hardware.org/?probe=ba129cd52d) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [7a081b66af](https://linux-hardware.org/?probe=7a081b66af) | Jun 11, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [4ecff82426](https://linux-hardware.org/?probe=4ecff82426) | Jun 11, 2023 |
| Acer          | Swift SF314-43              | [823925da4a](https://linux-hardware.org/?probe=823925da4a) | Jun 11, 2023 |
| NEC Comput... | PC-LM550LS6R                | [695f9825a6](https://linux-hardware.org/?probe=695f9825a6) | Jun 11, 2023 |
| Dell          | Latitude E5470              | [cc81f6c74c](https://linux-hardware.org/?probe=cc81f6c74c) | Jun 11, 2023 |
| HP            | EliteBook 840 G2            | [80bc2607fb](https://linux-hardware.org/?probe=80bc2607fb) | Jun 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [57f37d5836](https://linux-hardware.org/?probe=57f37d5836) | Jun 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [0b0c11a052](https://linux-hardware.org/?probe=0b0c11a052) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [a165849009](https://linux-hardware.org/?probe=a165849009) | Jun 09, 2023 |
| Dell          | Latitude E5470              | [c9b909273b](https://linux-hardware.org/?probe=c9b909273b) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | [05c07442a3](https://linux-hardware.org/?probe=05c07442a3) | Jun 09, 2023 |
| HP            | 14                          | [1540a787fb](https://linux-hardware.org/?probe=1540a787fb) | Jun 09, 2023 |
| HP            | 14                          | [1404218cab](https://linux-hardware.org/?probe=1404218cab) | Jun 09, 2023 |
| Dell          | XPS 17 9730                 | [bb7335618d](https://linux-hardware.org/?probe=bb7335618d) | Jun 08, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [97d002b53a](https://linux-hardware.org/?probe=97d002b53a) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [19c6b51f80](https://linux-hardware.org/?probe=19c6b51f80) | Jun 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [3cfa2bccb7](https://linux-hardware.org/?probe=3cfa2bccb7) | Jun 08, 2023 |
| HP            | ZBook 15 G2                 | [ac292cca00](https://linux-hardware.org/?probe=ac292cca00) | Jun 08, 2023 |
| Fujitsu       | FMVNA4NE-                   | [59c8fdd841](https://linux-hardware.org/?probe=59c8fdd841) | Jun 08, 2023 |
| Dell          | G15 5520                    | [2410d016d6](https://linux-hardware.org/?probe=2410d016d6) | Jun 08, 2023 |
| Google        | Edgar                       | [bec197cb98](https://linux-hardware.org/?probe=bec197cb98) | Jun 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9529a983b8](https://linux-hardware.org/?probe=9529a983b8) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | [2b1a1d3e39](https://linux-hardware.org/?probe=2b1a1d3e39) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | [3308d91565](https://linux-hardware.org/?probe=3308d91565) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [1f4ef72dbd](https://linux-hardware.org/?probe=1f4ef72dbd) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire A515-47              | [db7f17cbe1](https://linux-hardware.org/?probe=db7f17cbe1) | Jun 07, 2023 |
| Acer          | Swift SF314-43              | [9636ea4dc5](https://linux-hardware.org/?probe=9636ea4dc5) | Jun 07, 2023 |
| Dell          | Latitude 5480               | [dd2fef35ee](https://linux-hardware.org/?probe=dd2fef35ee) | Jun 06, 2023 |
| Dell          | Latitude 5480               | [7917512387](https://linux-hardware.org/?probe=7917512387) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | [662e292b55](https://linux-hardware.org/?probe=662e292b55) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | [024a1f80a1](https://linux-hardware.org/?probe=024a1f80a1) | Jun 06, 2023 |
| Lenovo        | ThinkPad 21CKCT01WW         | [92c9ec75c4](https://linux-hardware.org/?probe=92c9ec75c4) | Jun 05, 2023 |
| MSI           | Crosshair 15 C12VF          | [6cd11169d0](https://linux-hardware.org/?probe=6cd11169d0) | Jun 05, 2023 |
| Apple         | MacBookPro7,1               | [e92db65759](https://linux-hardware.org/?probe=e92db65759) | Jun 05, 2023 |
| HUAWEI        | KPR-WX9                     | [3eb711e453](https://linux-hardware.org/?probe=3eb711e453) | Jun 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a3089228b1](https://linux-hardware.org/?probe=a3089228b1) | Jun 05, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [f8f07099c7](https://linux-hardware.org/?probe=f8f07099c7) | Jun 05, 2023 |
| Lenovo        | Legion R70002021 82JW       | [f4e7c7034f](https://linux-hardware.org/?probe=f4e7c7034f) | Jun 05, 2023 |
| Apple         | MacBookPro12,1              | [bfce53d6f5](https://linux-hardware.org/?probe=bfce53d6f5) | Jun 05, 2023 |
| Acer          | Aspire A315-42G             | [eb67866c74](https://linux-hardware.org/?probe=eb67866c74) | Jun 05, 2023 |
| MSI           | Katana GF66 11UG            | [d50f02e996](https://linux-hardware.org/?probe=d50f02e996) | Jun 04, 2023 |
| ASUSTek       | X505BP                      | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [2eeb67613f](https://linux-hardware.org/?probe=2eeb67613f) | Jun 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [7179829c20](https://linux-hardware.org/?probe=7179829c20) | Jun 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [038871f5be](https://linux-hardware.org/?probe=038871f5be) | Jun 04, 2023 |
| Cube          | i16-L                       | [5e0bd26a26](https://linux-hardware.org/?probe=5e0bd26a26) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [d45c069b9f](https://linux-hardware.org/?probe=d45c069b9f) | Jun 04, 2023 |
| ASUSTek       | Zenbook UM5401RA_RM5401R... | [763a52f3e8](https://linux-hardware.org/?probe=763a52f3e8) | Jun 03, 2023 |
| Acer          | Swift SF314-511             | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | [e0f06316db](https://linux-hardware.org/?probe=e0f06316db) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [95ec288436](https://linux-hardware.org/?probe=95ec288436) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [7720a9f71c](https://linux-hardware.org/?probe=7720a9f71c) | Jun 03, 2023 |
| Gigabyte      | AERO 15WV8                  | [a8700141be](https://linux-hardware.org/?probe=a8700141be) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [49ca1fd34f](https://linux-hardware.org/?probe=49ca1fd34f) | Jun 02, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [d75ea1f93f](https://linux-hardware.org/?probe=d75ea1f93f) | Jun 02, 2023 |
| Acer          | Nitro AN515-55              | [947c70d6b6](https://linux-hardware.org/?probe=947c70d6b6) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c9e1edde25](https://linux-hardware.org/?probe=c9e1edde25) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [1f18cef2df](https://linux-hardware.org/?probe=1f18cef2df) | Jun 01, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [7ae3edd73e](https://linux-hardware.org/?probe=7ae3edd73e) | Jun 01, 2023 |
| Dell          | Vostro 7590                 | [d9bfa42b63](https://linux-hardware.org/?probe=d9bfa42b63) | Jun 01, 2023 |
| Dell          | XPS 13 9310                 | [b3eed1356b](https://linux-hardware.org/?probe=b3eed1356b) | Jun 01, 2023 |
| Dell          | Inspiron 5515               | [f383c5193d](https://linux-hardware.org/?probe=f383c5193d) | Jun 01, 2023 |
| Dell          | Latitude E6400              | [efe855c429](https://linux-hardware.org/?probe=efe855c429) | May 31, 2023 |
| Dell          | Latitude E6400              | [c56e8318db](https://linux-hardware.org/?probe=c56e8318db) | May 31, 2023 |
| MSI           | Modern 14 B4MW              | [2c4acbbad3](https://linux-hardware.org/?probe=2c4acbbad3) | May 31, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [ceaf9120eb](https://linux-hardware.org/?probe=ceaf9120eb) | May 31, 2023 |
| Dell          | Inspiron 5593               | [ac6f421fef](https://linux-hardware.org/?probe=ac6f421fef) | May 31, 2023 |
| Dell          | Latitude E6420              | [102e4634b1](https://linux-hardware.org/?probe=102e4634b1) | May 31, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [8a6ceb7d8b](https://linux-hardware.org/?probe=8a6ceb7d8b) | May 30, 2023 |
| ASUSTek       | N61Jv                       | [7184d6add6](https://linux-hardware.org/?probe=7184d6add6) | May 30, 2023 |
| HP            | Laptop 15-ef1xxx            | [55b500a1a9](https://linux-hardware.org/?probe=55b500a1a9) | May 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d4cc055d3a](https://linux-hardware.org/?probe=d4cc055d3a) | May 30, 2023 |
| Dell          | Inspiron 1525               | [29d2e377ad](https://linux-hardware.org/?probe=29d2e377ad) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [b8e68f9227](https://linux-hardware.org/?probe=b8e68f9227) | May 29, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [541e16d421](https://linux-hardware.org/?probe=541e16d421) | May 29, 2023 |
| HP            | 14                          | [977d26c9b5](https://linux-hardware.org/?probe=977d26c9b5) | May 29, 2023 |
| Dell          | Inspiron 1525               | [7adfc9796d](https://linux-hardware.org/?probe=7adfc9796d) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [84781c068a](https://linux-hardware.org/?probe=84781c068a) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [97f0880258](https://linux-hardware.org/?probe=97f0880258) | May 29, 2023 |
| Acer          | Aspire A515-41G             | [644a5d7a16](https://linux-hardware.org/?probe=644a5d7a16) | May 29, 2023 |
| Dell          | Inspiron 5447               | [270e3cd993](https://linux-hardware.org/?probe=270e3cd993) | May 29, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [12838b3e3b](https://linux-hardware.org/?probe=12838b3e3b) | May 28, 2023 |
| Dell          | Inspiron 1525               | [99540846c4](https://linux-hardware.org/?probe=99540846c4) | May 28, 2023 |
| Dell          | Inspiron 1525               | [99c9a792f5](https://linux-hardware.org/?probe=99c9a792f5) | May 28, 2023 |
| Apple         | MacBookPro7,1               | [47ac3b9c43](https://linux-hardware.org/?probe=47ac3b9c43) | May 28, 2023 |
| HP            | EliteBook 840 G5            | [4a54b4e82c](https://linux-hardware.org/?probe=4a54b4e82c) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [462ae1c4f5](https://linux-hardware.org/?probe=462ae1c4f5) | May 28, 2023 |
| Lenovo        | ThinkPad T560 20FJS0CX00    | [cf7d5b7149](https://linux-hardware.org/?probe=cf7d5b7149) | May 27, 2023 |
| Dell          | Latitude E6440              | [821e3e3246](https://linux-hardware.org/?probe=821e3e3246) | May 27, 2023 |
| Acer          | Swift SF514-54GT            | [dd79b67b18](https://linux-hardware.org/?probe=dd79b67b18) | May 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [737d3fe7fb](https://linux-hardware.org/?probe=737d3fe7fb) | May 27, 2023 |
| HP            | EliteBook 8440p             | [cbcea9cc58](https://linux-hardware.org/?probe=cbcea9cc58) | May 27, 2023 |
| Dell          | Precision 3581              | [9fb00fd492](https://linux-hardware.org/?probe=9fb00fd492) | May 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [16ee98f9cc](https://linux-hardware.org/?probe=16ee98f9cc) | May 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [39cf075935](https://linux-hardware.org/?probe=39cf075935) | May 26, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [8b93a6ab33](https://linux-hardware.org/?probe=8b93a6ab33) | May 26, 2023 |
| Dell          | Latitude 5430               | [e8b9199229](https://linux-hardware.org/?probe=e8b9199229) | May 26, 2023 |
| Lenovo        | Yoga Slim 7 proX 14ARH7 ... | [684751d3db](https://linux-hardware.org/?probe=684751d3db) | May 26, 2023 |
| Acer          | Nitro AN515-45              | [a9e0505d3f](https://linux-hardware.org/?probe=a9e0505d3f) | May 26, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Lenovo        | IdeaPad Z580                | [8d9c3b024d](https://linux-hardware.org/?probe=8d9c3b024d) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [f876b5169a](https://linux-hardware.org/?probe=f876b5169a) | May 25, 2023 |
| ASUSTek       | S551LB                      | [86f50d3933](https://linux-hardware.org/?probe=86f50d3933) | May 25, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [fb5edbbd6b](https://linux-hardware.org/?probe=fb5edbbd6b) | May 24, 2023 |
| Acer          | Swift SF314-71              | [00979b3baa](https://linux-hardware.org/?probe=00979b3baa) | May 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d92b2ec905](https://linux-hardware.org/?probe=d92b2ec905) | May 24, 2023 |
| Acer          | Swift SF314-71              | [84d9f5a2cc](https://linux-hardware.org/?probe=84d9f5a2cc) | May 24, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e6c958dd68](https://linux-hardware.org/?probe=e6c958dd68) | May 24, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [82183f4762](https://linux-hardware.org/?probe=82183f4762) | May 24, 2023 |
| Acer          | Aspire A315-58              | [43069955ee](https://linux-hardware.org/?probe=43069955ee) | May 23, 2023 |
| Toshiba       | Satellite C645D             | [97abd98fdd](https://linux-hardware.org/?probe=97abd98fdd) | May 23, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [01c17ab9dc](https://linux-hardware.org/?probe=01c17ab9dc) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6e1c91c725](https://linux-hardware.org/?probe=6e1c91c725) | May 23, 2023 |
| HP            | Pavilion 17                 | [eb6c222cf7](https://linux-hardware.org/?probe=eb6c222cf7) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [324a8d5c88](https://linux-hardware.org/?probe=324a8d5c88) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [97687a73c3](https://linux-hardware.org/?probe=97687a73c3) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5300f7df17](https://linux-hardware.org/?probe=5300f7df17) | May 22, 2023 |
| Acer          | Nitro AN515-45              | [179e48239b](https://linux-hardware.org/?probe=179e48239b) | May 22, 2023 |
| HP            | Laptop 14-cf2xxx            | [c2d03bd839](https://linux-hardware.org/?probe=c2d03bd839) | May 22, 2023 |
| Apple         | MacBookPro7,1               | [88830e9fe8](https://linux-hardware.org/?probe=88830e9fe8) | May 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cccb529fd3](https://linux-hardware.org/?probe=cccb529fd3) | May 21, 2023 |
| MSI           | GF63 Thin 11UC              | [ca280c2e18](https://linux-hardware.org/?probe=ca280c2e18) | May 21, 2023 |
| Dell          | G3 3500                     | [490bdc1f92](https://linux-hardware.org/?probe=490bdc1f92) | May 21, 2023 |
| HP            | Laptop 15-dy4xxx            | [d739b1ab41](https://linux-hardware.org/?probe=d739b1ab41) | May 21, 2023 |
| HASEE Comp... | V1x0PNPx                    | [ce5f16dcfe](https://linux-hardware.org/?probe=ce5f16dcfe) | May 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [d82bf9332f](https://linux-hardware.org/?probe=d82bf9332f) | May 20, 2023 |
| Dell          | Latitude D630               | [d5d56f7183](https://linux-hardware.org/?probe=d5d56f7183) | May 20, 2023 |
| Dell          | Latitude D630               | [af41a1c303](https://linux-hardware.org/?probe=af41a1c303) | May 20, 2023 |
| Apple         | MacBookPro15,2              | [d52cf51575](https://linux-hardware.org/?probe=d52cf51575) | May 19, 2023 |
| Lenovo        | ThinkPad X240 20AMA21D00    | [a692a56bc0](https://linux-hardware.org/?probe=a692a56bc0) | May 19, 2023 |
| HP            | Unknown                     | [8ae91264ca](https://linux-hardware.org/?probe=8ae91264ca) | May 19, 2023 |
| ASUSTek       | X555LPB                     | [c1082eef21](https://linux-hardware.org/?probe=c1082eef21) | May 18, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [7df5747f30](https://linux-hardware.org/?probe=7df5747f30) | May 18, 2023 |
| Dell          | Latitude 5500               | [f03dddbf42](https://linux-hardware.org/?probe=f03dddbf42) | May 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [25e9a17dd0](https://linux-hardware.org/?probe=25e9a17dd0) | May 18, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [fdb0fb3d9c](https://linux-hardware.org/?probe=fdb0fb3d9c) | May 18, 2023 |
| Dell          | Latitude 5420               | [bd0c08b7b8](https://linux-hardware.org/?probe=bd0c08b7b8) | May 18, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [aa625a94a0](https://linux-hardware.org/?probe=aa625a94a0) | May 18, 2023 |
| Apple         | MacBookPro11,1              | [d23967583a](https://linux-hardware.org/?probe=d23967583a) | May 18, 2023 |
| Acer          | Swift SF315-51G             | [4361a75669](https://linux-hardware.org/?probe=4361a75669) | May 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [42f598550a](https://linux-hardware.org/?probe=42f598550a) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [2df1a28c50](https://linux-hardware.org/?probe=2df1a28c50) | May 17, 2023 |
| Emdoor        | AG958                       | [7ff5858830](https://linux-hardware.org/?probe=7ff5858830) | May 17, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [4d1cd4ec12](https://linux-hardware.org/?probe=4d1cd4ec12) | May 17, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [de0485927b](https://linux-hardware.org/?probe=de0485927b) | May 17, 2023 |
| Google        | Cyan                        | [41811cace9](https://linux-hardware.org/?probe=41811cace9) | May 17, 2023 |
| Dell          | Latitude 5330               | [3cc5328fee](https://linux-hardware.org/?probe=3cc5328fee) | May 16, 2023 |
| GPD           | MicroPC                     | [0da3fc7738](https://linux-hardware.org/?probe=0da3fc7738) | May 16, 2023 |
| Google        | Cyan                        | [65c63caab7](https://linux-hardware.org/?probe=65c63caab7) | May 16, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5402CBA... | [170341ae00](https://linux-hardware.org/?probe=170341ae00) | May 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b788039ba1](https://linux-hardware.org/?probe=b788039ba1) | May 15, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [dc5dd8c32a](https://linux-hardware.org/?probe=dc5dd8c32a) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5dadcb24d0](https://linux-hardware.org/?probe=5dadcb24d0) | May 15, 2023 |
| Dell          | XPS 17 9700                 | [55eb2f47b9](https://linux-hardware.org/?probe=55eb2f47b9) | May 15, 2023 |
| HONOR         | NMH-WCX9                    | [b938ce8d64](https://linux-hardware.org/?probe=b938ce8d64) | May 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2750a05721](https://linux-hardware.org/?probe=2750a05721) | May 15, 2023 |
| Dell          | XPS 17 9700                 | [85c2869727](https://linux-hardware.org/?probe=85c2869727) | May 15, 2023 |
| Acer          | Swift SF114-34              | [360db31139](https://linux-hardware.org/?probe=360db31139) | May 14, 2023 |
| Acer          | Swift SF114-34              | [c3bbc544d3](https://linux-hardware.org/?probe=c3bbc544d3) | May 14, 2023 |
| Lenovo        | ThinkPad T570 20H90002GE    | [e6ff63678e](https://linux-hardware.org/?probe=e6ff63678e) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [ba47df6545](https://linux-hardware.org/?probe=ba47df6545) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [0b6c34eefa](https://linux-hardware.org/?probe=0b6c34eefa) | May 14, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [fe36fee27a](https://linux-hardware.org/?probe=fe36fee27a) | May 14, 2023 |
| HP            | EliteBook 8470p             | [b9f9ed1b25](https://linux-hardware.org/?probe=b9f9ed1b25) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [92c052d9b4](https://linux-hardware.org/?probe=92c052d9b4) | May 14, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [4b296f5c40](https://linux-hardware.org/?probe=4b296f5c40) | May 12, 2023 |
| Razer         | Blade 15 Studio Edition ... | [f1884eebc6](https://linux-hardware.org/?probe=f1884eebc6) | May 12, 2023 |
| realme        | RMNBXXXX                    | [16782746d8](https://linux-hardware.org/?probe=16782746d8) | May 12, 2023 |
| Dell          | Latitude 7390               | [cbd8c5fdbe](https://linux-hardware.org/?probe=cbd8c5fdbe) | May 12, 2023 |
| Dell          | Latitude 7390               | [5677bfdac5](https://linux-hardware.org/?probe=5677bfdac5) | May 12, 2023 |
| Medion        | Crawler E40                 | [d0df38a2da](https://linux-hardware.org/?probe=d0df38a2da) | May 12, 2023 |
| Medion        | Crawler E40                 | [c58193ce55](https://linux-hardware.org/?probe=c58193ce55) | May 12, 2023 |
| Dell          | Latitude 7400               | [c8ce2e462f](https://linux-hardware.org/?probe=c8ce2e462f) | May 11, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [38acb76489](https://linux-hardware.org/?probe=38acb76489) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [79d149ff5c](https://linux-hardware.org/?probe=79d149ff5c) | May 11, 2023 |
| Dell          | Latitude 5480               | [eb671ee7d2](https://linux-hardware.org/?probe=eb671ee7d2) | May 11, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [39dd8fc09a](https://linux-hardware.org/?probe=39dd8fc09a) | May 10, 2023 |
| Lenovo        | ThinkPad T450s 20BWS34A0... | [775c2839fa](https://linux-hardware.org/?probe=775c2839fa) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [0a1c43b710](https://linux-hardware.org/?probe=0a1c43b710) | May 09, 2023 |
| MSI           | PS42 Modern 8RA             | [8371e35044](https://linux-hardware.org/?probe=8371e35044) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5cbf24306a](https://linux-hardware.org/?probe=5cbf24306a) | May 08, 2023 |
| Acer          | Aspire A315-22              | [8849d7a1c9](https://linux-hardware.org/?probe=8849d7a1c9) | May 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a4f5dce6d6](https://linux-hardware.org/?probe=a4f5dce6d6) | May 08, 2023 |
| Acer          | Aspire V3-772G              | [bbf20cfdad](https://linux-hardware.org/?probe=bbf20cfdad) | May 08, 2023 |
| MSI           | GV63 8SE                    | [55bfa86f43](https://linux-hardware.org/?probe=55bfa86f43) | May 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [af9591cedc](https://linux-hardware.org/?probe=af9591cedc) | May 07, 2023 |
| Dell          | Precision 7720              | [9e0a1bd8ef](https://linux-hardware.org/?probe=9e0a1bd8ef) | May 06, 2023 |
| Toshiba       | Satellite C855              | [775c7346eb](https://linux-hardware.org/?probe=775c7346eb) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | [9a510bb01b](https://linux-hardware.org/?probe=9a510bb01b) | May 06, 2023 |
| Dell          | Precision 7550              | [5f962aaea0](https://linux-hardware.org/?probe=5f962aaea0) | May 06, 2023 |
| HP            | Laptop 15s-eq0xxx           | [a5252d48f3](https://linux-hardware.org/?probe=a5252d48f3) | May 06, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b4f013c967](https://linux-hardware.org/?probe=b4f013c967) | May 06, 2023 |
| Lenovo        | ThinkPad X131e 33712MU      | [6957336ed7](https://linux-hardware.org/?probe=6957336ed7) | May 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5f4447aa45](https://linux-hardware.org/?probe=5f4447aa45) | May 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [907a94ae07](https://linux-hardware.org/?probe=907a94ae07) | May 05, 2023 |
| MSI           | GV63 8SE                    | [1c78e3feb9](https://linux-hardware.org/?probe=1c78e3feb9) | May 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [bd885c202d](https://linux-hardware.org/?probe=bd885c202d) | May 05, 2023 |
| Apple         | MacBookPro14,2              | [4124bb2dde](https://linux-hardware.org/?probe=4124bb2dde) | May 04, 2023 |
| ASUSTek       | N550JK                      | [a799667521](https://linux-hardware.org/?probe=a799667521) | May 04, 2023 |
| Lenovo        | G505s 20255                 | [44c5b43b8d](https://linux-hardware.org/?probe=44c5b43b8d) | May 04, 2023 |
| Quanta        | UW3 TBD                     | [0c951d032e](https://linux-hardware.org/?probe=0c951d032e) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [7d642208ec](https://linux-hardware.org/?probe=7d642208ec) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [e31ba8f396](https://linux-hardware.org/?probe=e31ba8f396) | May 04, 2023 |
| HUAWEI        | BOM-WXX9                    | [abc1819fc1](https://linux-hardware.org/?probe=abc1819fc1) | May 04, 2023 |
| Lenovo        | B490 37722XP                | [62808a2dee](https://linux-hardware.org/?probe=62808a2dee) | May 04, 2023 |
| Quanta        | UW3 TBD                     | [c138f57a47](https://linux-hardware.org/?probe=c138f57a47) | May 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [02df3a407e](https://linux-hardware.org/?probe=02df3a407e) | May 03, 2023 |
| Acer          | Predator G9-793             | [b3bd1a1031](https://linux-hardware.org/?probe=b3bd1a1031) | May 03, 2023 |
| Samsung       | 750XDA                      | [2e99c882ff](https://linux-hardware.org/?probe=2e99c882ff) | May 03, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [7c56fae21c](https://linux-hardware.org/?probe=7c56fae21c) | May 03, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [26bb61d72f](https://linux-hardware.org/?probe=26bb61d72f) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [2a4cf994ac](https://linux-hardware.org/?probe=2a4cf994ac) | May 02, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [abd1474dfc](https://linux-hardware.org/?probe=abd1474dfc) | May 02, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [9035ec79cd](https://linux-hardware.org/?probe=9035ec79cd) | May 02, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a5ac1bf5b4](https://linux-hardware.org/?probe=a5ac1bf5b4) | May 01, 2023 |
| HP            | ProBook 430 G1              | [56542de280](https://linux-hardware.org/?probe=56542de280) | May 01, 2023 |
| Dell          | Inspiron 5458               | [c38d3e6513](https://linux-hardware.org/?probe=c38d3e6513) | May 01, 2023 |
| HP            | EliteBook 830 G5            | [6b61472a4a](https://linux-hardware.org/?probe=6b61472a4a) | May 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bd460bdc62](https://linux-hardware.org/?probe=bd460bdc62) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [edfcd7daa6](https://linux-hardware.org/?probe=edfcd7daa6) | Apr 30, 2023 |
| HP            | Laptop 15s-eq3xxx           | [3c321c476a](https://linux-hardware.org/?probe=3c321c476a) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [df9cc0160a](https://linux-hardware.org/?probe=df9cc0160a) | Apr 30, 2023 |
| Dell          | XPS 13 9310                 | [2f3308a2ee](https://linux-hardware.org/?probe=2f3308a2ee) | Apr 29, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [4a8b2ebf8a](https://linux-hardware.org/?probe=4a8b2ebf8a) | Apr 29, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | [34420e9478](https://linux-hardware.org/?probe=34420e9478) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | [96194bc912](https://linux-hardware.org/?probe=96194bc912) | Apr 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6926565982](https://linux-hardware.org/?probe=6926565982) | Apr 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [640a71aea3](https://linux-hardware.org/?probe=640a71aea3) | Apr 27, 2023 |
| Dell          | Latitude 7420               | [7ceeb888fd](https://linux-hardware.org/?probe=7ceeb888fd) | Apr 27, 2023 |
| Dell          | Latitude E5440              | [0217386dbe](https://linux-hardware.org/?probe=0217386dbe) | Apr 27, 2023 |
| Sony          | SVE11113FXW                 | [248c7717a4](https://linux-hardware.org/?probe=248c7717a4) | Apr 26, 2023 |
| Apple         | MacBookPro14,2              | [4e1caf5a7a](https://linux-hardware.org/?probe=4e1caf5a7a) | Apr 26, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [bf207e9dc3](https://linux-hardware.org/?probe=bf207e9dc3) | Apr 25, 2023 |
| MSI           | Prestige 14 A12UC           | [137a3623dc](https://linux-hardware.org/?probe=137a3623dc) | Apr 25, 2023 |
| Notebook      | N85_N87HCHNHZ               | [ecb3270b4a](https://linux-hardware.org/?probe=ecb3270b4a) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| HP            | 240 G4                      | [997e6e6a0b](https://linux-hardware.org/?probe=997e6e6a0b) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| Notebook      | N15_N17RD1                  | [8bba7a7447](https://linux-hardware.org/?probe=8bba7a7447) | Apr 23, 2023 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [0be1fdd77a](https://linux-hardware.org/?probe=0be1fdd77a) | Apr 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [52001c8ac6](https://linux-hardware.org/?probe=52001c8ac6) | Apr 23, 2023 |
| Acer          | Swift SF314-43              | [b18f893905](https://linux-hardware.org/?probe=b18f893905) | Apr 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [5ecd3ed1bd](https://linux-hardware.org/?probe=5ecd3ed1bd) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [72088721ec](https://linux-hardware.org/?probe=72088721ec) | Apr 22, 2023 |
| HP            | 240 G4                      | [887b406c56](https://linux-hardware.org/?probe=887b406c56) | Apr 22, 2023 |
| Gigabyte      | AERO 15-X9                  | [5eb2235e10](https://linux-hardware.org/?probe=5eb2235e10) | Apr 22, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [3f01c5df6e](https://linux-hardware.org/?probe=3f01c5df6e) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [a5ef39681b](https://linux-hardware.org/?probe=a5ef39681b) | Apr 21, 2023 |
| HP            | 15                          | [4f563db114](https://linux-hardware.org/?probe=4f563db114) | Apr 21, 2023 |
| Valve         | Jupiter                     | [a0ee1dbeff](https://linux-hardware.org/?probe=a0ee1dbeff) | Apr 20, 2023 |
| Acer          | Aspire A715-71G             | [83b48fff59](https://linux-hardware.org/?probe=83b48fff59) | Apr 19, 2023 |
| MSI           | Bravo 15 B5DD               | [433c482314](https://linux-hardware.org/?probe=433c482314) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [be217cbc1e](https://linux-hardware.org/?probe=be217cbc1e) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d5e90c4b14](https://linux-hardware.org/?probe=d5e90c4b14) | Apr 19, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [146c678131](https://linux-hardware.org/?probe=146c678131) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | [d1d3cf9928](https://linux-hardware.org/?probe=d1d3cf9928) | Apr 17, 2023 |
| HP            | Laptop 15-da0xxx            | [786daebed0](https://linux-hardware.org/?probe=786daebed0) | Apr 17, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [65a5b3f43d](https://linux-hardware.org/?probe=65a5b3f43d) | Apr 17, 2023 |
| MSI           | GF75 Thin 9SC               | [40b6c3bad6](https://linux-hardware.org/?probe=40b6c3bad6) | Apr 17, 2023 |
| HP            | Pavilion dv6                | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9b05d61f11](https://linux-hardware.org/?probe=9b05d61f11) | Apr 16, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [040d876c1e](https://linux-hardware.org/?probe=040d876c1e) | Apr 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6S... | [6686a91041](https://linux-hardware.org/?probe=6686a91041) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [9b23be6c48](https://linux-hardware.org/?probe=9b23be6c48) | Apr 16, 2023 |
| Acer          | Aspire A515-45              | [5ce7874f2e](https://linux-hardware.org/?probe=5ce7874f2e) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2fcbae14f2](https://linux-hardware.org/?probe=2fcbae14f2) | Apr 16, 2023 |
| HP            | Laptop 15s-eq3xxx           | [fff7f3dd1f](https://linux-hardware.org/?probe=fff7f3dd1f) | Apr 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Dell          | Inspiron 5570               | [d582f92277](https://linux-hardware.org/?probe=d582f92277) | Apr 15, 2023 |
| Lenovo        | ThinkPad P52 20MAS1LH00     | [06ba20dc47](https://linux-hardware.org/?probe=06ba20dc47) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c7b7e028e4](https://linux-hardware.org/?probe=c7b7e028e4) | Apr 14, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [e0ad93045c](https://linux-hardware.org/?probe=e0ad93045c) | Apr 14, 2023 |
| Lenovo        | V15-ADA 82C7                | [f604f6e212](https://linux-hardware.org/?probe=f604f6e212) | Apr 14, 2023 |
| Dell          | Latitude 9420               | [529aa83bbc](https://linux-hardware.org/?probe=529aa83bbc) | Apr 14, 2023 |
| Avell High... | B.ON                        | [0ac252a73b](https://linux-hardware.org/?probe=0ac252a73b) | Apr 14, 2023 |
| HP            | ProBook 430 G6              | [9a4bce918e](https://linux-hardware.org/?probe=9a4bce918e) | Apr 14, 2023 |
| System76      | Pangolin                    | [b5dd9f13b9](https://linux-hardware.org/?probe=b5dd9f13b9) | Apr 14, 2023 |
| System76      | Pangolin                    | [a1a17fa4c4](https://linux-hardware.org/?probe=a1a17fa4c4) | Apr 14, 2023 |
| Lenovo        | ThinkPad T460 20FMS0E22C    | [ee911053e5](https://linux-hardware.org/?probe=ee911053e5) | Apr 13, 2023 |
| MSI           | Prestige 14 A12UC           | [43e044c37a](https://linux-hardware.org/?probe=43e044c37a) | Apr 13, 2023 |
| HP            | ProBook 450 G6              | [3364cf411c](https://linux-hardware.org/?probe=3364cf411c) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [1280936eba](https://linux-hardware.org/?probe=1280936eba) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| MSI           | Stealth 14Studio A13VF      | [b6cd64a19b](https://linux-hardware.org/?probe=b6cd64a19b) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U745               | [82bfc450e9](https://linux-hardware.org/?probe=82bfc450e9) | Apr 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | [6406153cbf](https://linux-hardware.org/?probe=6406153cbf) | Apr 12, 2023 |
| Dell          | XPS 9315                    | [20fa2b86b9](https://linux-hardware.org/?probe=20fa2b86b9) | Apr 12, 2023 |
| Dell          | Latitude E7440              | [4cfe81f687](https://linux-hardware.org/?probe=4cfe81f687) | Apr 12, 2023 |
| Toshiba       | Satellite S50-B             | [e9d26a9e89](https://linux-hardware.org/?probe=e9d26a9e89) | Apr 12, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [6bec4cb4a8](https://linux-hardware.org/?probe=6bec4cb4a8) | Apr 12, 2023 |
| HP            | EliteBook 840 G3            | [0daac07546](https://linux-hardware.org/?probe=0daac07546) | Apr 12, 2023 |
| HP            | Laptop 14s-cf1xxx           | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| HP            | Laptop 14s-cr0xxx           | [f95d67a702](https://linux-hardware.org/?probe=f95d67a702) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [649a715fba](https://linux-hardware.org/?probe=649a715fba) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [39c6b4afbe](https://linux-hardware.org/?probe=39c6b4afbe) | Apr 10, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [e762a4eb1d](https://linux-hardware.org/?probe=e762a4eb1d) | Apr 09, 2023 |
| Google        | Phaser360                   | [64953bc26c](https://linux-hardware.org/?probe=64953bc26c) | Apr 09, 2023 |
| Avell High... | A52 HYB                     | [7da3b9f780](https://linux-hardware.org/?probe=7da3b9f780) | Apr 09, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [5cf4615347](https://linux-hardware.org/?probe=5cf4615347) | Apr 08, 2023 |
| Apple         | MacBookPro11,1              | [08f117749f](https://linux-hardware.org/?probe=08f117749f) | Apr 08, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | [772414cda4](https://linux-hardware.org/?probe=772414cda4) | Apr 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | [ae8c333d72](https://linux-hardware.org/?probe=ae8c333d72) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK S935               | [e7ba943509](https://linux-hardware.org/?probe=e7ba943509) | Apr 07, 2023 |
| HP            | ZBook 15 G5                 | [1927fa08d1](https://linux-hardware.org/?probe=1927fa08d1) | Apr 07, 2023 |
| Dell          | Vostro 5620                 | [afdf8d46a2](https://linux-hardware.org/?probe=afdf8d46a2) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a02839d653](https://linux-hardware.org/?probe=a02839d653) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [80bd0aed09](https://linux-hardware.org/?probe=80bd0aed09) | Apr 05, 2023 |
| Timi          | RedmiBook Pro 15            | [4eb4d46bfc](https://linux-hardware.org/?probe=4eb4d46bfc) | Apr 05, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [fef3cbc941](https://linux-hardware.org/?probe=fef3cbc941) | Apr 05, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [3f750a4d82](https://linux-hardware.org/?probe=3f750a4d82) | Apr 05, 2023 |
| Alienware     | M17xR3                      | [514f79bd8e](https://linux-hardware.org/?probe=514f79bd8e) | Apr 05, 2023 |
| Acer          | AO756                       | [4e33479949](https://linux-hardware.org/?probe=4e33479949) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a467a04489](https://linux-hardware.org/?probe=a467a04489) | Apr 04, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [c529f9d1cc](https://linux-hardware.org/?probe=c529f9d1cc) | Apr 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [b9a98e8656](https://linux-hardware.org/?probe=b9a98e8656) | Apr 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fc89f163b0](https://linux-hardware.org/?probe=fc89f163b0) | Apr 03, 2023 |
| Prestigio     | PSB133S01ZFH                | [ba6746febf](https://linux-hardware.org/?probe=ba6746febf) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | [85e0077c83](https://linux-hardware.org/?probe=85e0077c83) | Apr 03, 2023 |
| Timi          | RedmiBook Pro 14S           | [e3eb0fe882](https://linux-hardware.org/?probe=e3eb0fe882) | Apr 02, 2023 |
| Toxic         | GM5MPHY                     | [9ce64fb49a](https://linux-hardware.org/?probe=9ce64fb49a) | Apr 02, 2023 |
| Lenovo        | ThinkPad E480 20KQS0B800    | [9c9b561ca2](https://linux-hardware.org/?probe=9c9b561ca2) | Apr 02, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [c7791aac7c](https://linux-hardware.org/?probe=c7791aac7c) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| Google        | Snappy                      | [6ca49159d2](https://linux-hardware.org/?probe=6ca49159d2) | Apr 01, 2023 |
| Schenker      | S405                        | [6d89f7e662](https://linux-hardware.org/?probe=6d89f7e662) | Apr 01, 2023 |
| ASUSTek       | X550LB                      | [3d35ff8b68](https://linux-hardware.org/?probe=3d35ff8b68) | Apr 01, 2023 |
| Dell          | Inspiron 13 5310            | [32bdbfa581](https://linux-hardware.org/?probe=32bdbfa581) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440p              | [4057e0c5e9](https://linux-hardware.org/?probe=4057e0c5e9) | Apr 01, 2023 |
| HP            | Notebook                    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| Apple         | MacBookPro11,1              | [53717700a1](https://linux-hardware.org/?probe=53717700a1) | Mar 31, 2023 |
| Dell          | XPS 17 9700                 | [5d0a908832](https://linux-hardware.org/?probe=5d0a908832) | Mar 31, 2023 |
| Lenovo        | ThinkPad T440p              | [1063ba3fb9](https://linux-hardware.org/?probe=1063ba3fb9) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [0ab4f4cd55](https://linux-hardware.org/?probe=0ab4f4cd55) | Mar 31, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6915349237](https://linux-hardware.org/?probe=6915349237) | Mar 31, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | [2e8eab25be](https://linux-hardware.org/?probe=2e8eab25be) | Mar 30, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| HP            | Victus by Laptop 16-d0xx... | [d96583e702](https://linux-hardware.org/?probe=d96583e702) | Mar 29, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [e9b1759970](https://linux-hardware.org/?probe=e9b1759970) | Mar 29, 2023 |
| Acer          | Aspire ES1-512              | [f6357798c5](https://linux-hardware.org/?probe=f6357798c5) | Mar 28, 2023 |
| Dell          | Vostro 2420                 | [0a1739f44c](https://linux-hardware.org/?probe=0a1739f44c) | Mar 28, 2023 |
| HP            | ElitePad 1000 G2            | [4b16a78f3e](https://linux-hardware.org/?probe=4b16a78f3e) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [54f096fd88](https://linux-hardware.org/?probe=54f096fd88) | Mar 27, 2023 |
| Dell          | XPS 15 9500                 | [cebc7c547a](https://linux-hardware.org/?probe=cebc7c547a) | Mar 26, 2023 |
| Dell          | XPS 15 9500                 | [4391dcbdd2](https://linux-hardware.org/?probe=4391dcbdd2) | Mar 26, 2023 |
| Dell          | Inspiron 3501               | [14cc8c6a5e](https://linux-hardware.org/?probe=14cc8c6a5e) | Mar 26, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [0933beb0f7](https://linux-hardware.org/?probe=0933beb0f7) | Mar 26, 2023 |
| Dell          | G3 3590                     | [db70257507](https://linux-hardware.org/?probe=db70257507) | Mar 26, 2023 |
| HUAWEI        | NBD-WXX9                    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Acer          | Swift SF314-511             | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [649b881439](https://linux-hardware.org/?probe=649b881439) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| HP            | ENVY Laptop 17-ce1xxx       | [f9ff96064b](https://linux-hardware.org/?probe=f9ff96064b) | Mar 24, 2023 |
| Toshiba       | Satellite C850-140          | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [71d058eb0e](https://linux-hardware.org/?probe=71d058eb0e) | Mar 24, 2023 |
| Toshiba       | Satellite C55D-B            | [ae6069d9bb](https://linux-hardware.org/?probe=ae6069d9bb) | Mar 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [56942672e1](https://linux-hardware.org/?probe=56942672e1) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | [ded37ac14c](https://linux-hardware.org/?probe=ded37ac14c) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | [13046d5580](https://linux-hardware.org/?probe=13046d5580) | Mar 24, 2023 |
| Acer          | Aspire A515-57              | [748d918a61](https://linux-hardware.org/?probe=748d918a61) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [38b0e00744](https://linux-hardware.org/?probe=38b0e00744) | Mar 23, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [ad1134944b](https://linux-hardware.org/?probe=ad1134944b) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| ASUSTek       | T100HAN                     | [5f0061dd7b](https://linux-hardware.org/?probe=5f0061dd7b) | Mar 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [28cd6cb051](https://linux-hardware.org/?probe=28cd6cb051) | Mar 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [fab7c8ab05](https://linux-hardware.org/?probe=fab7c8ab05) | Mar 22, 2023 |
| Dell          | Vostro 2420                 | [e885d387ee](https://linux-hardware.org/?probe=e885d387ee) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [0880214933](https://linux-hardware.org/?probe=0880214933) | Mar 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | [e7b50c8f22](https://linux-hardware.org/?probe=e7b50c8f22) | Mar 22, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [4b7801e829](https://linux-hardware.org/?probe=4b7801e829) | Mar 22, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [1da76d59b2](https://linux-hardware.org/?probe=1da76d59b2) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| MSI           | Modern 14 B10MW             | [2940ea3b40](https://linux-hardware.org/?probe=2940ea3b40) | Mar 21, 2023 |
| HP            | ProBook 440 G3              | [217e9242da](https://linux-hardware.org/?probe=217e9242da) | Mar 20, 2023 |
| HP            | ProBook 440 G3              | [b011027d1a](https://linux-hardware.org/?probe=b011027d1a) | Mar 20, 2023 |
| Dell          | XPS 9315                    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Dell          | XPS 9315                    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | [8d13f6eef9](https://linux-hardware.org/?probe=8d13f6eef9) | Mar 20, 2023 |
| MSI           | GS63VR 7RF                  | [5b4e0532f8](https://linux-hardware.org/?probe=5b4e0532f8) | Mar 20, 2023 |
| Dell          | Vostro 2420                 | [a98665cff1](https://linux-hardware.org/?probe=a98665cff1) | Mar 20, 2023 |
| Dell          | G15 5511                    | [ddb34b9c1f](https://linux-hardware.org/?probe=ddb34b9c1f) | Mar 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [0500018bce](https://linux-hardware.org/?probe=0500018bce) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [aa4184ac0c](https://linux-hardware.org/?probe=aa4184ac0c) | Mar 19, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [00de843c75](https://linux-hardware.org/?probe=00de843c75) | Mar 19, 2023 |
| MSI           | GP66 Leopard 11UG           | [7210f8c423](https://linux-hardware.org/?probe=7210f8c423) | Mar 19, 2023 |
| ASUSTek       | X205TA                      | [9727a94199](https://linux-hardware.org/?probe=9727a94199) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| Unknown       | Unknown                     | [e10e576833](https://linux-hardware.org/?probe=e10e576833) | Mar 18, 2023 |
| Unknown       | Unknown                     | [a791424f94](https://linux-hardware.org/?probe=a791424f94) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | [434b76d9cd](https://linux-hardware.org/?probe=434b76d9cd) | Mar 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | [2ffc3ebd28](https://linux-hardware.org/?probe=2ffc3ebd28) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [3a565fb944](https://linux-hardware.org/?probe=3a565fb944) | Mar 18, 2023 |
| HONOR         | BOD-WXX9                    | [9bca2e7122](https://linux-hardware.org/?probe=9bca2e7122) | Mar 18, 2023 |
| ASUSTek       | N550JK                      | [6b93d4a171](https://linux-hardware.org/?probe=6b93d4a171) | Mar 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [ccfa4fb30e](https://linux-hardware.org/?probe=ccfa4fb30e) | Mar 17, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [fc0e66fc8a](https://linux-hardware.org/?probe=fc0e66fc8a) | Mar 17, 2023 |
| Dell          | Precision 3520              | [2afa31184a](https://linux-hardware.org/?probe=2afa31184a) | Mar 17, 2023 |
| Dell          | Precision 3520              | [819b4aa330](https://linux-hardware.org/?probe=819b4aa330) | Mar 17, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [e7e152095b](https://linux-hardware.org/?probe=e7e152095b) | Mar 17, 2023 |
| HP            | 245 14 inch G9 Notebook ... | [03edff3e6f](https://linux-hardware.org/?probe=03edff3e6f) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [304f8b71db](https://linux-hardware.org/?probe=304f8b71db) | Mar 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [4bfe066835](https://linux-hardware.org/?probe=4bfe066835) | Mar 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [590a3ca248](https://linux-hardware.org/?probe=590a3ca248) | Mar 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | [e4254565ed](https://linux-hardware.org/?probe=e4254565ed) | Mar 15, 2023 |
| Star Labs     | StarBook                    | [13efc22826](https://linux-hardware.org/?probe=13efc22826) | Mar 15, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [29ebc422fe](https://linux-hardware.org/?probe=29ebc422fe) | Mar 15, 2023 |
| Timi          | RedmiBook 14                | [ff5feda02c](https://linux-hardware.org/?probe=ff5feda02c) | Mar 14, 2023 |
| Acer          | Aspire E5-571               | [6c7886396a](https://linux-hardware.org/?probe=6c7886396a) | Mar 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [0b9501dcc9](https://linux-hardware.org/?probe=0b9501dcc9) | Mar 14, 2023 |
| Dell          | Vostro 2420                 | [a87952a308](https://linux-hardware.org/?probe=a87952a308) | Mar 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [a13648959d](https://linux-hardware.org/?probe=a13648959d) | Mar 14, 2023 |
| Star Labs     | StarBook                    | [3e534c533a](https://linux-hardware.org/?probe=3e534c533a) | Mar 14, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [2906d8ad11](https://linux-hardware.org/?probe=2906d8ad11) | Mar 14, 2023 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [7f06c80526](https://linux-hardware.org/?probe=7f06c80526) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| Monster       | ABRA A7 V11.3               | [724a9e65d8](https://linux-hardware.org/?probe=724a9e65d8) | Mar 13, 2023 |
| Panasonic     | FZ40-1                      | [1dfcc0c545](https://linux-hardware.org/?probe=1dfcc0c545) | Mar 13, 2023 |
| HP            | ProBook 6460b               | [c6b7f1ec98](https://linux-hardware.org/?probe=c6b7f1ec98) | Mar 13, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [87331b21e8](https://linux-hardware.org/?probe=87331b21e8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [5522717dc5](https://linux-hardware.org/?probe=5522717dc5) | Mar 12, 2023 |
| MSI           | Pulse GL66 11UGKV           | [1abb09da1a](https://linux-hardware.org/?probe=1abb09da1a) | Mar 12, 2023 |
| Razer         | Blade 14 - RZ09-0370        | [a081c489c9](https://linux-hardware.org/?probe=a081c489c9) | Mar 12, 2023 |
| HP            | G61                         | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [062687b226](https://linux-hardware.org/?probe=062687b226) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Dell          | Latitude E6530              | [50a26c019d](https://linux-hardware.org/?probe=50a26c019d) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z480                | [eb63a9a0d3](https://linux-hardware.org/?probe=eb63a9a0d3) | Mar 10, 2023 |
| HP            | EliteBook 8730w             | [a012fe4bd2](https://linux-hardware.org/?probe=a012fe4bd2) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | [5d082aaf0e](https://linux-hardware.org/?probe=5d082aaf0e) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | [4745f71e81](https://linux-hardware.org/?probe=4745f71e81) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | [98c29f81d8](https://linux-hardware.org/?probe=98c29f81d8) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | [6ef05d9cbb](https://linux-hardware.org/?probe=6ef05d9cbb) | Mar 10, 2023 |
| Acer          | Aspire A715-71G             | [4f916d30c4](https://linux-hardware.org/?probe=4f916d30c4) | Mar 10, 2023 |
| Panasonic     | FZ40-1                      | [9eac1dc6f5](https://linux-hardware.org/?probe=9eac1dc6f5) | Mar 10, 2023 |
| Lenovo        | ThinkPad X250 20CLS2A100    | [06971429a7](https://linux-hardware.org/?probe=06971429a7) | Mar 10, 2023 |
| Lenovo        | ThinkPad T450 20BUA05K00    | [a496755d7a](https://linux-hardware.org/?probe=a496755d7a) | Mar 10, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [1b0ea7bf68](https://linux-hardware.org/?probe=1b0ea7bf68) | Mar 10, 2023 |
| HP            | Laptop 14-fq0xxx            | [8574146364](https://linux-hardware.org/?probe=8574146364) | Mar 09, 2023 |
| HP            | Laptop 14-fq0xxx            | [c397e2fa8b](https://linux-hardware.org/?probe=c397e2fa8b) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [79fc708bbd](https://linux-hardware.org/?probe=79fc708bbd) | Mar 09, 2023 |
| Lenovo        | IdeaPad Z480                | [bc5f204a78](https://linux-hardware.org/?probe=bc5f204a78) | Mar 08, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [59bddb27c4](https://linux-hardware.org/?probe=59bddb27c4) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | [0312ea16b6](https://linux-hardware.org/?probe=0312ea16b6) | Mar 08, 2023 |
| Dell          | Precision 3520              | [99eaeb743c](https://linux-hardware.org/?probe=99eaeb743c) | Mar 08, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [c768e8ff8f](https://linux-hardware.org/?probe=c768e8ff8f) | Mar 08, 2023 |
| Dell          | Precision 3520              | [acf74c7740](https://linux-hardware.org/?probe=acf74c7740) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Dell          | Latitude 5590               | [10e7ed8ff6](https://linux-hardware.org/?probe=10e7ed8ff6) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | [e2c5933515](https://linux-hardware.org/?probe=e2c5933515) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| GPD           | P2 MAX                      | [d73c7b9146](https://linux-hardware.org/?probe=d73c7b9146) | Mar 07, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [bbbf4112e4](https://linux-hardware.org/?probe=bbbf4112e4) | Mar 06, 2023 |
| HP            | Pavilion dv6                | [6485870687](https://linux-hardware.org/?probe=6485870687) | Mar 06, 2023 |
| Acer          | Aspire A114-31              | [33ce987151](https://linux-hardware.org/?probe=33ce987151) | Mar 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [0047dd8b2a](https://linux-hardware.org/?probe=0047dd8b2a) | Mar 06, 2023 |
| Lenovo        | Unknown                     | [2ae9263125](https://linux-hardware.org/?probe=2ae9263125) | Mar 06, 2023 |
| Lenovo        | ThinkPad E550 20DF002YUS    | [6a7ad331f8](https://linux-hardware.org/?probe=6a7ad331f8) | Mar 06, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [6a6864f933](https://linux-hardware.org/?probe=6a6864f933) | Mar 05, 2023 |
| Acer          | Aspire A514-55              | [97e8238d87](https://linux-hardware.org/?probe=97e8238d87) | Mar 05, 2023 |
| IGEL Techn... | H830C                       | [3619b3fcee](https://linux-hardware.org/?probe=3619b3fcee) | Mar 05, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [ea211d74ee](https://linux-hardware.org/?probe=ea211d74ee) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [71f2f93645](https://linux-hardware.org/?probe=71f2f93645) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [13fc723c9e](https://linux-hardware.org/?probe=13fc723c9e) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| Dell          | Latitude 5480               | [4679c9328e](https://linux-hardware.org/?probe=4679c9328e) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [bef62e57b0](https://linux-hardware.org/?probe=bef62e57b0) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [b42f1c3f6b](https://linux-hardware.org/?probe=b42f1c3f6b) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Acer          | Nitro AN515-58              | [d8d83e3bb3](https://linux-hardware.org/?probe=d8d83e3bb3) | Mar 03, 2023 |
| HP            | ENVY dv6                    | [357b5b3506](https://linux-hardware.org/?probe=357b5b3506) | Mar 03, 2023 |
| Dell          | Latitude E6510              | [80edceafbc](https://linux-hardware.org/?probe=80edceafbc) | Mar 03, 2023 |
| Dell          | XPS 15 9500                 | [13f585159e](https://linux-hardware.org/?probe=13f585159e) | Mar 02, 2023 |
| DTRI          | DT317CR                     | [b78d90835c](https://linux-hardware.org/?probe=b78d90835c) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| Dell          | Precision 5520              | [9ce4c56521](https://linux-hardware.org/?probe=9ce4c56521) | Mar 02, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | [f61c295d09](https://linux-hardware.org/?probe=f61c295d09) | Mar 01, 2023 |
| Dell          | XPS 15 9550                 | [0ffe1f9541](https://linux-hardware.org/?probe=0ffe1f9541) | Feb 28, 2023 |
| HP            | Laptop 15s-eq3xxx           | [a08a3c36ab](https://linux-hardware.org/?probe=a08a3c36ab) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [456504fe92](https://linux-hardware.org/?probe=456504fe92) | Feb 28, 2023 |
| HP            | Laptop 15s-eq1xxx           | [c070966ad7](https://linux-hardware.org/?probe=c070966ad7) | Feb 28, 2023 |
| Apple         | MacBookPro8,1               | [ec1f27de09](https://linux-hardware.org/?probe=ec1f27de09) | Feb 28, 2023 |
| MECHREVO      | Jiaolong Series MRID6       | [1643b96eae](https://linux-hardware.org/?probe=1643b96eae) | Feb 28, 2023 |
| MECHREVO      | Jiaolong Series MRID6       | [b48cc99ce3](https://linux-hardware.org/?probe=b48cc99ce3) | Feb 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [915fc4d913](https://linux-hardware.org/?probe=915fc4d913) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| HP            | ProBook 430 G1              | [fa75658ee0](https://linux-hardware.org/?probe=fa75658ee0) | Feb 28, 2023 |
| Dell          | G15 5510                    | [77ff8fd545](https://linux-hardware.org/?probe=77ff8fd545) | Feb 28, 2023 |
| Dell          | G15 5510                    | [2c8f883abe](https://linux-hardware.org/?probe=2c8f883abe) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [1f80bce21e](https://linux-hardware.org/?probe=1f80bce21e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [08e6c7285a](https://linux-hardware.org/?probe=08e6c7285a) | Feb 27, 2023 |
| Dell          | Latitude 7390               | [a2167ae72b](https://linux-hardware.org/?probe=a2167ae72b) | Feb 27, 2023 |
| Schenker      | VISION (E22)                | [498444ca02](https://linux-hardware.org/?probe=498444ca02) | Feb 27, 2023 |
| HP            | ProBook 430 G1              | [1354e0b47e](https://linux-hardware.org/?probe=1354e0b47e) | Feb 26, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [848e43f7c3](https://linux-hardware.org/?probe=848e43f7c3) | Feb 26, 2023 |
| Sony          | SVE1712C1EW                 | [20bd9411d9](https://linux-hardware.org/?probe=20bd9411d9) | Feb 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9755df8e75](https://linux-hardware.org/?probe=9755df8e75) | Feb 25, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [e07445a583](https://linux-hardware.org/?probe=e07445a583) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [d475dd1788](https://linux-hardware.org/?probe=d475dd1788) | Feb 25, 2023 |
| Star Labs     | StarBook                    | [fbd529b953](https://linux-hardware.org/?probe=fbd529b953) | Feb 25, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [46aedb5579](https://linux-hardware.org/?probe=46aedb5579) | Feb 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | [64504d9860](https://linux-hardware.org/?probe=64504d9860) | Feb 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | [8a573735cb](https://linux-hardware.org/?probe=8a573735cb) | Feb 24, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [ac2d78d240](https://linux-hardware.org/?probe=ac2d78d240) | Feb 24, 2023 |
| Dell          | XPS 13 9310                 | [1b60ef35ce](https://linux-hardware.org/?probe=1b60ef35ce) | Feb 24, 2023 |
| Lenovo        | ThinkPad X61s 7667CG7       | [f090aa4d60](https://linux-hardware.org/?probe=f090aa4d60) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [028814b990](https://linux-hardware.org/?probe=028814b990) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| Avell High... | A70 MOB                     | [1bf7d82ab3](https://linux-hardware.org/?probe=1bf7d82ab3) | Feb 23, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [c69ac67426](https://linux-hardware.org/?probe=c69ac67426) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d74903e764](https://linux-hardware.org/?probe=d74903e764) | Feb 23, 2023 |
| Acer          | Swift SF514-54GT            | [dbccc5afa9](https://linux-hardware.org/?probe=dbccc5afa9) | Feb 23, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [14cf9e07e0](https://linux-hardware.org/?probe=14cf9e07e0) | Feb 23, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [388f34d16e](https://linux-hardware.org/?probe=388f34d16e) | Feb 23, 2023 |
| Dell          | Latitude 7300               | [c4bb27e884](https://linux-hardware.org/?probe=c4bb27e884) | Feb 23, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [d16dd6d1f3](https://linux-hardware.org/?probe=d16dd6d1f3) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [701608fad1](https://linux-hardware.org/?probe=701608fad1) | Feb 22, 2023 |
| HP            | ProBook 640 G5              | [e90b71c2fd](https://linux-hardware.org/?probe=e90b71c2fd) | Feb 22, 2023 |
| Acer          | Aspire ES1-533              | [4a7563bd8e](https://linux-hardware.org/?probe=4a7563bd8e) | Feb 22, 2023 |
| Compaq        | 430                         | [4bd84653a5](https://linux-hardware.org/?probe=4bd84653a5) | Feb 21, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [dd12dc45d7](https://linux-hardware.org/?probe=dd12dc45d7) | Feb 21, 2023 |
| Dell          | XPS 13 9360                 | [f36328511d](https://linux-hardware.org/?probe=f36328511d) | Feb 21, 2023 |
| HP            | ProBook 430 G1              | [1505165a73](https://linux-hardware.org/?probe=1505165a73) | Feb 20, 2023 |
| ASUSTek       | X555LPB                     | [29eb95639c](https://linux-hardware.org/?probe=29eb95639c) | Feb 20, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [e008fd489b](https://linux-hardware.org/?probe=e008fd489b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [defde684a0](https://linux-hardware.org/?probe=defde684a0) | Feb 20, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [1832e70d83](https://linux-hardware.org/?probe=1832e70d83) | Feb 20, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [9adf6b834b](https://linux-hardware.org/?probe=9adf6b834b) | Feb 20, 2023 |
| Dell          | XPS 15 9520                 | [d346153872](https://linux-hardware.org/?probe=d346153872) | Feb 20, 2023 |
| HUAWEI        | MACHC-WAX9                  | [69a8710cbb](https://linux-hardware.org/?probe=69a8710cbb) | Feb 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | [db5d2b956a](https://linux-hardware.org/?probe=db5d2b956a) | Feb 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6aae20aa14](https://linux-hardware.org/?probe=6aae20aa14) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | [bf63748499](https://linux-hardware.org/?probe=bf63748499) | Feb 18, 2023 |
| Google        | Celes                       | [3004fce0ed](https://linux-hardware.org/?probe=3004fce0ed) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2e22d32463](https://linux-hardware.org/?probe=2e22d32463) | Feb 18, 2023 |
| MSI           | GL65 9SD                    | [a702514760](https://linux-hardware.org/?probe=a702514760) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bfeb3ab070](https://linux-hardware.org/?probe=bfeb3ab070) | Feb 17, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [c4ec00ef99](https://linux-hardware.org/?probe=c4ec00ef99) | Feb 17, 2023 |
| TUXEDO        | Unknown                     | [d770ba8b7b](https://linux-hardware.org/?probe=d770ba8b7b) | Feb 17, 2023 |
| Acer          | Nitro AN515-46              | [162b72d7a8](https://linux-hardware.org/?probe=162b72d7a8) | Feb 17, 2023 |
| Acer          | Aspire A515-51G             | [065827a397](https://linux-hardware.org/?probe=065827a397) | Feb 16, 2023 |
| Dell          | Latitude 5330               | [497897c322](https://linux-hardware.org/?probe=497897c322) | Feb 16, 2023 |
| Dell          | Latitude 5330               | [aa55aaad48](https://linux-hardware.org/?probe=aa55aaad48) | Feb 16, 2023 |
| Lenovo        | B40-70 20392                | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Dell          | Latitude 5480               | [ee1b786fd9](https://linux-hardware.org/?probe=ee1b786fd9) | Feb 15, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [2be1a08ef2](https://linux-hardware.org/?probe=2be1a08ef2) | Feb 15, 2023 |
| HUAWEI        | NBD-WXX9                    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [138839541a](https://linux-hardware.org/?probe=138839541a) | Feb 15, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | [dc352cd9dc](https://linux-hardware.org/?probe=dc352cd9dc) | Feb 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a3eb6fde29](https://linux-hardware.org/?probe=a3eb6fde29) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| Dell          | Venue 8 Pro 5855            | [6e5eacb53a](https://linux-hardware.org/?probe=6e5eacb53a) | Feb 14, 2023 |
| Lenovo        | G50-80 80R0                 | [86422b9261](https://linux-hardware.org/?probe=86422b9261) | Feb 14, 2023 |
| Toshiba       | Satellite P870              | [dcfa5b1fc5](https://linux-hardware.org/?probe=dcfa5b1fc5) | Feb 13, 2023 |
| Toshiba       | Satellite P870              | [3a4a4dedc3](https://linux-hardware.org/?probe=3a4a4dedc3) | Feb 13, 2023 |
| Dell          | Latitude E6530              | [c79c336ef7](https://linux-hardware.org/?probe=c79c336ef7) | Feb 13, 2023 |
| Acer          | Swift SF514-54GT            | [b7e961dae3](https://linux-hardware.org/?probe=b7e961dae3) | Feb 13, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [b3ab77c355](https://linux-hardware.org/?probe=b3ab77c355) | Feb 13, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [37c223623f](https://linux-hardware.org/?probe=37c223623f) | Feb 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [3f25b64868](https://linux-hardware.org/?probe=3f25b64868) | Feb 13, 2023 |
| ASUSTek       | X205TA                      | [dfc9ada1af](https://linux-hardware.org/?probe=dfc9ada1af) | Feb 13, 2023 |
| HP            | ProBook 430 G1              | [8d414de313](https://linux-hardware.org/?probe=8d414de313) | Feb 12, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [afb25c8733](https://linux-hardware.org/?probe=afb25c8733) | Feb 12, 2023 |
| MSI           | Modern 14 B11MOU            | [547c8e5750](https://linux-hardware.org/?probe=547c8e5750) | Feb 12, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [35d68b3769](https://linux-hardware.org/?probe=35d68b3769) | Feb 12, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [5335da53d0](https://linux-hardware.org/?probe=5335da53d0) | Feb 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | [5f2fb779b4](https://linux-hardware.org/?probe=5f2fb779b4) | Feb 11, 2023 |
| Samsung       | 767XCL                      | [8a62be0577](https://linux-hardware.org/?probe=8a62be0577) | Feb 11, 2023 |
| HP            | Laptop 15s-eq3xxx           | [36dd5f42fc](https://linux-hardware.org/?probe=36dd5f42fc) | Feb 11, 2023 |
| Unknown       | Unknown                     | [31d099a8db](https://linux-hardware.org/?probe=31d099a8db) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | [ca5ff923cc](https://linux-hardware.org/?probe=ca5ff923cc) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fd8d478a5b](https://linux-hardware.org/?probe=fd8d478a5b) | Feb 10, 2023 |
| Acer          | Aspire V5-551               | [cb3ab0bbf5](https://linux-hardware.org/?probe=cb3ab0bbf5) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [482b3ea2be](https://linux-hardware.org/?probe=482b3ea2be) | Feb 10, 2023 |
| Acer          | Aspire V5-551               | [132d55b2ed](https://linux-hardware.org/?probe=132d55b2ed) | Feb 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Arch Rolling  | 2052      | 53.9%   |
| Arch          | 1744      | 45.81%  |
| Arch V20.5.7  | 2         | 0.05%   |
| Arch V19.04.4 | 2         | 0.05%   |
| Arch V6.9.2   | 1         | 0.03%   |
| Arch V20.3.4  | 1         | 0.03%   |
| Arch V19.07.9 | 1         | 0.03%   |
| Arch V19.06.1 | 1         | 0.03%   |
| Arch V19.01.4 | 1         | 0.03%   |
| Arch 23.0.0   | 1         | 0.03%   |
| Arch 2.7      | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Arch | 3695      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 52        | 1.19%   |
| 6.0.2-arch1-1   | 51        | 1.16%   |
| 5.9.14-arch1-1  | 31        | 0.71%   |
| 5.9.1-arch1-1   | 31        | 0.71%   |
| 6.4.12-arch1-1  | 29        | 0.66%   |
| 6.0.9-arch1-1   | 28        | 0.64%   |
| 5.8.5-arch1-1   | 28        | 0.64%   |
| 5.17.5-arch1-1  | 28        | 0.64%   |
| 6.1.1-arch1-1   | 26        | 0.59%   |
| 5.8.10-arch1-1  | 26        | 0.59%   |
| 6.2.8-arch1-1   | 25        | 0.57%   |
| 5.17.9-arch1-1  | 25        | 0.57%   |
| 6.3.9-arch1-1   | 24        | 0.55%   |
| 6.0.12-arch1-1  | 24        | 0.55%   |
| 5.11.16-arch1-1 | 24        | 0.55%   |
| 6.3.2-arch1-1   | 23        | 0.53%   |
| 6.2.10-arch1-1  | 23        | 0.53%   |
| 5.8.14-arch1-1  | 23        | 0.53%   |
| 5.8.1-arch1-1   | 23        | 0.53%   |
| 5.7.12-arch1-1  | 23        | 0.53%   |
| 5.18.1-arch1-1  | 22        | 0.5%    |
| 5.13.13-arch1-1 | 22        | 0.5%    |
| 5.13.12-arch1-1 | 22        | 0.5%    |
| 5.18.16-arch1-1 | 21        | 0.48%   |
| 6.3.5-arch1-1   | 20        | 0.46%   |
| 5.9.10-arch1-1  | 20        | 0.46%   |
| 5.8.12-arch1-1  | 20        | 0.46%   |
| 6.4.10-arch1-1  | 19        | 0.43%   |
| 6.0.7-arch1-1   | 19        | 0.43%   |
| 5.8.3-arch1-1   | 19        | 0.43%   |
| 5.16.16-arch1-1 | 19        | 0.43%   |
| 5.11.11-arch1-1 | 19        | 0.43%   |
| 6.3.6-arch1-1   | 18        | 0.41%   |
| 6.0.10-arch2-1  | 18        | 0.41%   |
| 5.9.11-arch2-1  | 18        | 0.41%   |
| 5.19.13-arch1-1 | 18        | 0.41%   |
| 5.16.2-arch1-1  | 18        | 0.41%   |
| 5.12.15-arch1-1 | 18        | 0.41%   |
| 5.11.2-arch1-1  | 18        | 0.41%   |
| 6.3.1-arch2-1   | 17        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.1  | 65        | 1.48%   |
| 6.0.2   | 60        | 1.37%   |
| 5.9.1   | 40        | 0.91%   |
| 5.9.14  | 38        | 0.87%   |
| 5.8.5   | 38        | 0.87%   |
| 5.17.5  | 38        | 0.87%   |
| 6.3.1   | 37        | 0.84%   |
| 6.4.12  | 34        | 0.78%   |
| 6.0.9   | 34        | 0.78%   |
| 6.3.2   | 31        | 0.71%   |
| 6.1.9   | 31        | 0.71%   |
| 6.1.1   | 31        | 0.71%   |
| 5.13.13 | 31        | 0.71%   |
| 6.3.5   | 30        | 0.69%   |
| 6.2.8   | 30        | 0.69%   |
| 5.8.14  | 30        | 0.69%   |
| 5.17.9  | 30        | 0.69%   |
| 6.0.12  | 29        | 0.66%   |
| 5.8.10  | 29        | 0.66%   |
| 6.3.9   | 28        | 0.64%   |
| 6.2.10  | 28        | 0.64%   |
| 5.18.16 | 27        | 0.62%   |
| 6.4.3   | 26        | 0.59%   |
| 6.2.2   | 26        | 0.59%   |
| 5.8.12  | 26        | 0.59%   |
| 5.8.1   | 26        | 0.59%   |
| 5.18.1  | 26        | 0.59%   |
| 5.16.2  | 26        | 0.59%   |
| 5.13.12 | 26        | 0.59%   |
| 5.11.16 | 26        | 0.59%   |
| 6.1.12  | 25        | 0.57%   |
| 6.0.11  | 25        | 0.57%   |
| 5.7.12  | 25        | 0.57%   |
| 6.4.7   | 24        | 0.55%   |
| 6.4.10  | 24        | 0.55%   |
| 5.19.13 | 24        | 0.55%   |
| 5.16.16 | 24        | 0.55%   |
| 5.14.8  | 24        | 0.55%   |
| 5.11.2  | 24        | 0.55%   |
| 5.10.16 | 24        | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 266       | 6.32%   |
| 6.1     | 257       | 6.11%   |
| 6.0     | 245       | 5.82%   |
| 5.8     | 232       | 5.51%   |
| 6.2     | 222       | 5.28%   |
| 5.18    | 219       | 5.2%    |
| 6.4     | 215       | 5.11%   |
| 6.3     | 214       | 5.09%   |
| 5.9     | 208       | 4.94%   |
| 5.17    | 198       | 4.71%   |
| 5.4     | 193       | 4.59%   |
| 5.16    | 188       | 4.47%   |
| 5.10    | 182       | 4.33%   |
| 5.19    | 177       | 4.21%   |
| 5.11    | 168       | 3.99%   |
| 5.12    | 153       | 3.64%   |
| 5.13    | 142       | 3.37%   |
| 5.7     | 138       | 3.28%   |
| 5.6     | 135       | 3.21%   |
| 5.14    | 128       | 3.04%   |
| 5.5     | 93        | 2.21%   |
| 5.3     | 64        | 1.52%   |
| 5.2     | 33        | 0.78%   |
| 4.19    | 26        | 0.62%   |
| 5.0     | 19        | 0.45%   |
| 5.1     | 16        | 0.38%   |
| 4.18    | 16        | 0.38%   |
| 4.17    | 12        | 0.29%   |
| 4.20    | 9         | 0.21%   |
| 4.14    | 9         | 0.21%   |
| 4.15    | 5         | 0.12%   |
| 4.9     | 4         | 0.1%    |
| 4.7     | 4         | 0.1%    |
| 4.16    | 4         | 0.1%    |
| 4.6     | 3         | 0.07%   |
| 4.4     | 3         | 0.07%   |
| 4.8     | 2         | 0.05%   |
| 4.13    | 2         | 0.05%   |
| 4.11    | 2         | 0.05%   |
| 6.5     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3691      | 99.89%  |
| i686   | 4         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 1272      | 33.03%  |
| KDE5                     | 1008      | 26.18%  |
| Unknown                  | 460       | 11.94%  |
| XFCE                     | 290       | 7.53%   |
| i3                       | 208       | 5.4%    |
| KDE                      | 145       | 3.77%   |
| sway                     | 60        | 1.56%   |
| X-Cinnamon               | 48        | 1.25%   |
| MATE                     | 44        | 1.14%   |
| Cinnamon                 | 41        | 1.06%   |
| Budgie                   | 41        | 1.06%   |
| LXQt                     | 35        | 0.91%   |
| Hyprland                 | 31        | 0.8%    |
| awesome                  | 26        | 0.68%   |
| Deepin                   | 24        | 0.62%   |
| bspwm                    | 22        | 0.57%   |
| LXDE                     | 18        | 0.47%   |
| xmonad                   | 9         | 0.23%   |
| Unity                    | 9         | 0.23%   |
| qtile                    | 9         | 0.23%   |
| GNOME Flashback          | 9         | 0.23%   |
| DWM                      | 9         | 0.23%   |
| openbox                  | 6         | 0.16%   |
| GNOME Classic            | 5         | 0.13%   |
| Enlightenment            | 5         | 0.13%   |
| i3-with-shmlog           | 3         | 0.08%   |
| LeftWM                   | 2         | 0.05%   |
| X-Generic                | 1         | 0.03%   |
| river                    | 1         | 0.03%   |
| Pantheon                 | 1         | 0.03%   |
| jwm                      | 1         | 0.03%   |
| instantwm                | 1         | 0.03%   |
| ICEWM                    | 1         | 0.03%   |
| herbstluftwm             | 1         | 0.03%   |
| GNOME-Classic            | 1         | 0.03%   |
| dusk                     | 1         | 0.03%   |
| default                  | 1         | 0.03%   |
| chadwm                   | 1         | 0.03%   |
| /usr/bin/openbox-session | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2163      | 56.49%  |
| Wayland | 1085      | 28.34%  |
| Tty     | 311       | 8.12%   |
| Unknown | 270       | 7.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1563      | 40.97%  |
| SDDM    | 916       | 24.01%  |
| GDM     | 569       | 14.91%  |
| LightDM | 447       | 11.72%  |
| TDM     | 188       | 4.93%   |
| Ly      | 39        | 1.02%   |
| XDM     | 29        | 0.76%   |
| LXDM    | 26        | 0.68%   |
| SLiM    | 15        | 0.39%   |
| GREETD  | 10        | 0.26%   |
| EMPTTY  | 5         | 0.13%   |
| LY-DM   | 4         | 0.1%    |
| NODM    | 3         | 0.08%   |
| MDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1833      | 48.56%  |
| Unknown | 369       | 9.77%   |
| en_GB   | 218       | 5.77%   |
| C       | 205       | 5.43%   |
| it_IT   | 126       | 3.34%   |
| de_DE   | 121       | 3.21%   |
| pt_BR   | 107       | 2.83%   |
| ru_RU   | 106       | 2.81%   |
| fr_FR   | 95        | 2.52%   |
| zh_CN   | 56        | 1.48%   |
| en_IN   | 47        | 1.25%   |
| pl_PL   | 45        | 1.19%   |
| en_CA   | 41        | 1.09%   |
| es_ES   | 40        | 1.06%   |
| en_AU   | 30        | 0.79%   |
| es_MX   | 20        | 0.53%   |
| es_AR   | 14        | 0.37%   |
| pt_PT   | 13        | 0.34%   |
| en_IE   | 13        | 0.34%   |
| de_AT   | 13        | 0.34%   |
| tr_TR   | 12        | 0.32%   |
| en_DK   | 12        | 0.32%   |
| ja_JP   | 9         | 0.24%   |
| hu_HU   | 9         | 0.24%   |
| es_CO   | 9         | 0.24%   |
| es_CL   | 9         | 0.24%   |
| nl_NL   | 8         | 0.21%   |
| en_NZ   | 8         | 0.21%   |
| zh_TW   | 7         | 0.19%   |
| ru_UA   | 7         | 0.19%   |
| en_ZA   | 7         | 0.19%   |
| en_SG   | 7         | 0.19%   |
| cs_CZ   | 7         | 0.19%   |
| fr_CA   | 6         | 0.16%   |
| es_PE   | 6         | 0.16%   |
| en_AG   | 6         | 0.16%   |
| lv_LV   | 5         | 0.13%   |
| en_DE   | 5         | 0.13%   |
| en-US   | 5         | 0.13%   |
| ca_ES   | 5         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2359      | 62.54%  |
| BIOS | 1413      | 37.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2678      | 71.55%  |
| Btrfs   | 767       | 20.49%  |
| Unknown | 112       | 2.99%   |
| Xfs     | 84        | 2.24%   |
| F2fs    | 45        | 1.2%    |
| Overlay | 25        | 0.67%   |
| Zfs     | 18        | 0.48%   |
| Tmpfs   | 6         | 0.16%   |
| Ext2    | 3         | 0.08%   |
| XXXXX   | 2         | 0.05%   |
| XXX4    | 1         | 0.03%   |
| Jfs     | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2363      | 63.08%  |
| Unknown | 1075      | 28.7%   |
| MBR     | 308       | 8.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3363      | 90.09%  |
| Yes       | 370       | 9.91%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2766      | 73.78%  |
| Yes       | 983       | 26.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1066      | 28.85%  |
| Dell                   | 584       | 15.81%  |
| Hewlett-Packard        | 504       | 13.64%  |
| ASUSTek Computer       | 449       | 12.15%  |
| Acer                   | 296       | 8.01%   |
| MSI                    | 111       | 3%      |
| HUAWEI                 | 71        | 1.92%   |
| Apple                  | 71        | 1.92%   |
| Samsung Electronics    | 52        | 1.41%   |
| Toshiba                | 47        | 1.27%   |
| Notebook               | 34        | 0.92%   |
| Timi                   | 30        | 0.81%   |
| Google                 | 27        | 0.73%   |
| Sony                   | 23        | 0.62%   |
| TUXEDO                 | 22        | 0.6%    |
| Framework              | 20        | 0.54%   |
| Alienware              | 19        | 0.51%   |
| Fujitsu                | 16        | 0.43%   |
| Razer                  | 15        | 0.41%   |
| Unknown                | 13        | 0.35%   |
| LG Electronics         | 11        | 0.3%    |
| Gigabyte Technology    | 11        | 0.3%    |
| Avell High Performance | 11        | 0.3%    |
| System76               | 10        | 0.27%   |
| Schenker               | 10        | 0.27%   |
| Packard Bell           | 8         | 0.22%   |
| MECHREVO               | 8         | 0.22%   |
| Chuwi                  | 8         | 0.22%   |
| Medion                 | 7         | 0.19%   |
| Intel                  | 7         | 0.19%   |
| HONOR                  | 6         | 0.16%   |
| GPD                    | 6         | 0.16%   |
| Positivo               | 5         | 0.14%   |
| Monster                | 5         | 0.14%   |
| Intel Client Systems   | 5         | 0.14%   |
| Valve                  | 4         | 0.11%   |
| Teclast                | 4         | 0.11%   |
| Star Labs              | 4         | 0.11%   |
| SLIMBOOK               | 4         | 0.11%   |
| PC Specialist          | 4         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 34        | 0.92%   |
| Dell XPS 15 9570                | 18        | 0.49%   |
| Dell XPS 15 9500                | 18        | 0.49%   |
| HP Notebook                     | 16        | 0.43%   |
| Framework Laptop                | 16        | 0.43%   |
| Dell XPS 13 9360                | 13        | 0.35%   |
| Dell XPS 13 9380                | 11        | 0.3%    |
| HUAWEI NBLK-WAX9X               | 10        | 0.27%   |
| Dell XPS 15 7590                | 10        | 0.27%   |
| Dell XPS 13 9310                | 10        | 0.27%   |
| Dell Latitude E6430             | 10        | 0.27%   |
| Dell Inspiron 15 7000 Gaming    | 10        | 0.27%   |
| ASUS ROG Strix G513QY_G513QY    | 10        | 0.27%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 9         | 0.24%   |
| HP Pavilion dv6                 | 9         | 0.24%   |
| HP EliteBook 840 G6             | 9         | 0.24%   |
| Dell XPS 13 9370                | 9         | 0.24%   |
| Dell XPS 13 9350                | 9         | 0.24%   |
| Dell Inspiron 5570              | 9         | 0.24%   |
| Lenovo IdeaPad 5 14ARE05 81YM   | 8         | 0.22%   |
| HUAWEI BOHK-WAX9X               | 8         | 0.22%   |
| HP Pavilion Notebook            | 8         | 0.22%   |
| HP EliteBook 840 G5             | 8         | 0.22%   |
| Dell Latitude E7450             | 8         | 0.22%   |
| Dell Latitude 5480              | 8         | 0.22%   |
| ASUS TUF Gaming FX505DT_FX505DT | 8         | 0.22%   |
| Lenovo Legion Y530-15ICH 81FV   | 7         | 0.19%   |
| Lenovo Legion 5 15ARH05 82B5    | 7         | 0.19%   |
| HP Laptop 15-da0xxx             | 7         | 0.19%   |
| HP 250 G6 Notebook PC           | 7         | 0.19%   |
| Dell XPS 15 9560                | 7         | 0.19%   |
| Dell XPS 13 7390                | 7         | 0.19%   |
| Dell Precision 7540             | 7         | 0.19%   |
| Dell G3 3579                    | 7         | 0.19%   |
| Dell G3 3500                    | 7         | 0.19%   |
| Acer Swift SF314-43             | 7         | 0.19%   |
| Acer Nitro AN515-52             | 7         | 0.19%   |
| Acer Nitro AN515-45             | 7         | 0.19%   |
| Acer Aspire E5-571              | 7         | 0.19%   |
| Acer Aspire A515-45             | 7         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 632       | 17.1%   |
| Lenovo IdeaPad     | 208       | 5.63%   |
| Acer Aspire        | 169       | 4.57%   |
| Dell Latitude      | 157       | 4.25%   |
| Dell Inspiron      | 155       | 4.19%   |
| Dell XPS           | 150       | 4.06%   |
| HP Pavilion        | 109       | 2.95%   |
| HP EliteBook       | 104       | 2.81%   |
| HP Laptop          | 76        | 2.06%   |
| Lenovo Legion      | 74        | 2%      |
| ASUS ROG           | 72        | 1.95%   |
| ASUS VivoBook      | 71        | 1.92%   |
| HP ProBook         | 61        | 1.65%   |
| Dell Precision     | 50        | 1.35%   |
| Acer Nitro         | 48        | 1.3%    |
| ASUS ASUS          | 42        | 1.14%   |
| Acer Swift         | 40        | 1.08%   |
| Toshiba Satellite  | 38        | 1.03%   |
| ASUS Zenbook       | 37        | 1%      |
| Unknown            | 34        | 0.92%   |
| Lenovo ThinkBook   | 33        | 0.89%   |
| ASUS TUF           | 33        | 0.89%   |
| Dell Vostro        | 29        | 0.78%   |
| HP OMEN            | 25        | 0.68%   |
| HP ENVY            | 24        | 0.65%   |
| Lenovo Yoga        | 21        | 0.57%   |
| Framework Laptop   | 20        | 0.54%   |
| Dell G3            | 17        | 0.46%   |
| MSI Modern         | 16        | 0.43%   |
| HP Notebook        | 16        | 0.43%   |
| Razer Blade        | 15        | 0.41%   |
| HP 250             | 15        | 0.41%   |
| Fujitsu LIFEBOOK   | 15        | 0.41%   |
| HP ZBook           | 13        | 0.35%   |
| Apple MacBookPro11 | 12        | 0.32%   |
| Acer Predator      | 11        | 0.3%    |
| HUAWEI NBLK-WAX9X  | 10        | 0.27%   |
| Timi RedmiBook     | 9         | 0.24%   |
| HP 255             | 9         | 0.24%   |
| ASUS Strix         | 9         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 490       | 13.26%  |
| 2020    | 483       | 13.07%  |
| 2021    | 451       | 12.21%  |
| 2018    | 422       | 11.42%  |
| 2017    | 273       | 7.39%   |
| 2015    | 207       | 5.6%    |
| 2016    | 204       | 5.52%   |
| 2022    | 200       | 5.41%   |
| 2012    | 197       | 5.33%   |
| 2013    | 178       | 4.82%   |
| 2014    | 169       | 4.57%   |
| 2011    | 161       | 4.36%   |
| 2010    | 98        | 2.65%   |
| 2008    | 63        | 1.71%   |
| 2009    | 45        | 1.22%   |
| 2023    | 37        | 1%      |
| 2007    | 12        | 0.32%   |
| 2006    | 4         | 0.11%   |
| Unknown | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3695      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3652      | 98.6%   |
| Enabled  | 52        | 1.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3646      | 98.67%  |
| Yes  | 49        | 1.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 976       | 26.1%   |
| 16.01-24.0  | 897       | 23.99%  |
| 8.01-16.0   | 841       | 22.49%  |
| 3.01-4.0    | 397       | 10.62%  |
| 32.01-64.0  | 382       | 10.22%  |
| 24.01-32.0  | 79        | 2.11%   |
| 64.01-256.0 | 77        | 2.06%   |
| 1.01-2.0    | 56        | 1.5%    |
| 2.01-3.0    | 28        | 0.75%   |
| 0.51-1.0    | 6         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1025      | 25.07%  |
| 1.01-2.0   | 949       | 23.21%  |
| 4.01-8.0   | 896       | 21.92%  |
| 3.01-4.0   | 707       | 17.29%  |
| 8.01-16.0  | 272       | 6.65%   |
| 0.51-1.0   | 158       | 3.86%   |
| 0.01-0.5   | 36        | 0.88%   |
| 16.01-24.0 | 28        | 0.68%   |
| 24.01-32.0 | 14        | 0.34%   |
| 32.01-64.0 | 3         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2579      | 68.65%  |
| 2      | 1008      | 26.83%  |
| 3      | 138       | 3.67%   |
| 4      | 14        | 0.37%   |
| 0      | 14        | 0.37%   |
| 5      | 3         | 0.08%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3000      | 80.88%  |
| Yes       | 709       | 19.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2829      | 76.21%  |
| No        | 883       | 23.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3662      | 99%     |
| No        | 37        | 1%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3207      | 86%     |
| No        | 522       | 14%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 619       | 16.64%  |
| Germany     | 322       | 8.65%   |
| Russia      | 235       | 6.32%   |
| Italy       | 218       | 5.86%   |
| Brazil      | 204       | 5.48%   |
| France      | 178       | 4.78%   |
| India       | 152       | 4.08%   |
| UK          | 126       | 3.39%   |
| Poland      | 103       | 2.77%   |
| Canada      | 97        | 2.61%   |
| Spain       | 83        | 2.23%   |
| China       | 79        | 2.12%   |
| Netherlands | 70        | 1.88%   |
| Turkey      | 57        | 1.53%   |
| Australia   | 54        | 1.45%   |
| Austria     | 49        | 1.32%   |
| Sweden      | 43        | 1.16%   |
| Ukraine     | 42        | 1.13%   |
| Indonesia   | 42        | 1.13%   |
| Portugal    | 35        | 0.94%   |
| Mexico      | 35        | 0.94%   |
| Romania     | 34        | 0.91%   |
| Czechia     | 33        | 0.89%   |
| Belgium     | 33        | 0.89%   |
| Argentina   | 30        | 0.81%   |
| Vietnam     | 28        | 0.75%   |
| Switzerland | 28        | 0.75%   |
| Japan       | 25        | 0.67%   |
| Iran        | 25        | 0.67%   |
| Hungary     | 25        | 0.67%   |
| Finland     | 24        | 0.64%   |
| Denmark     | 24        | 0.64%   |
| New Zealand | 23        | 0.62%   |
| Colombia    | 23        | 0.62%   |
| Chile       | 21        | 0.56%   |
| Hong Kong   | 20        | 0.54%   |
| Greece      | 20        | 0.54%   |
| Taiwan      | 18        | 0.48%   |
| Peru        | 18        | 0.48%   |
| Belarus     | 18        | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 67        | 1.69%   |
| Paris             | 38        | 0.96%   |
| Milan             | 38        | 0.96%   |
| Berlin            | 37        | 0.93%   |
| Sao Paulo         | 35        | 0.88%   |
| St Petersburg     | 34        | 0.86%   |
| Warsaw            | 30        | 0.76%   |
| Munich            | 26        | 0.66%   |
| Vienna            | 25        | 0.63%   |
| Melbourne         | 23        | 0.58%   |
| Los Angeles       | 23        | 0.58%   |
| Istanbul          | 21        | 0.53%   |
| Bengaluru         | 21        | 0.53%   |
| Valencia          | 20        | 0.5%    |
| Amsterdam         | 19        | 0.48%   |
| Sydney            | 16        | 0.4%    |
| Prague            | 16        | 0.4%    |
| Montreal          | 16        | 0.4%    |
| Kyiv              | 16        | 0.4%    |
| Frankfurt am Main | 16        | 0.4%    |
| Tehran            | 15        | 0.38%   |
| Phoenix           | 14        | 0.35%   |
| Mexico City       | 14        | 0.35%   |
| Madrid            | 14        | 0.35%   |
| Lima              | 14        | 0.35%   |
| Jakarta           | 14        | 0.35%   |
| Helsinki          | 14        | 0.35%   |
| Budapest          | 14        | 0.35%   |
| Rome              | 13        | 0.33%   |
| New York          | 13        | 0.33%   |
| Hamburg           | 13        | 0.33%   |
| Curitiba          | 13        | 0.33%   |
| Bogotá           | 13        | 0.33%   |
| Singapore         | 12        | 0.3%    |
| Cologne           | 12        | 0.3%    |
| Central           | 12        | 0.3%    |
| Buenos Aires      | 12        | 0.3%    |
| Beijing           | 12        | 0.3%    |
| Turin             | 11        | 0.28%   |
| Seattle           | 11        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1036      | 1383   | 21.37%  |
| WDC                            | 470       | 577    | 9.69%   |
| SanDisk                        | 415       | 497    | 8.56%   |
| Seagate                        | 396       | 479    | 8.17%   |
| Toshiba                        | 316       | 366    | 6.52%   |
| SK hynix                       | 277       | 337    | 5.71%   |
| Kingston                       | 232       | 290    | 4.79%   |
| Unknown                        | 194       | 230    | 4%      |
| Intel                          | 181       | 236    | 3.73%   |
| Micron Technology              | 170       | 207    | 3.51%   |
| Crucial                        | 134       | 193    | 2.76%   |
| HGST                           | 122       | 133    | 2.52%   |
| A-DATA Technology              | 66        | 92     | 1.36%   |
| Hitachi                        | 65        | 66     | 1.34%   |
| KIOXIA                         | 49        | 56     | 1.01%   |
| Apple                          | 44        | 57     | 0.91%   |
| Phison Electronics             | 39        | 45     | 0.8%    |
| Phison                         | 32        | 37     | 0.66%   |
| LITEON                         | 30        | 31     | 0.62%   |
| Silicon Motion                 | 28        | 29     | 0.58%   |
| Kingston Technology Company    | 28        | 28     | 0.58%   |
| Micron/Crucial Technology      | 27        | 29     | 0.56%   |
| Transcend                      | 26        | 28     | 0.54%   |
| China                          | 26        | 32     | 0.54%   |
| SPCC                           | 19        | 21     | 0.39%   |
| Lenovo                         | 17        | 22     | 0.35%   |
| PNY                            | 16        | 20     | 0.33%   |
| JMicron Technology             | 16        | 17     | 0.33%   |
| ADATA Technology               | 14        | 16     | 0.29%   |
| LITEONIT                       | 12        | 12     | 0.25%   |
| Yangtze Memory Technologies    | 11        | 11     | 0.23%   |
| KingSpec                       | 11        | 12     | 0.23%   |
| GOODRAM                        | 11        | 11     | 0.23%   |
| OCZ                            | 10        | 10     | 0.21%   |
| Intenso                        | 10        | 12     | 0.21%   |
| Patriot                        | 9         | 10     | 0.19%   |
| Union Memory (Shenzhen)        | 8         | 9      | 0.17%   |
| Solid State Storage Technology | 8         | 8      | 0.17%   |
| Solid State Storage            | 8         | 10     | 0.17%   |
| Realtek Semiconductor          | 8         | 9      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 128       | 2.52%   |
| Seagate ST1000LM035-1RK172 1TB                        | 88        | 1.73%   |
| Samsung NVMe SSD Drive 512GB                          | 63        | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 59        | 1.16%   |
| HGST HTS721010A9E630 1TB                              | 48        | 0.95%   |
| SanDisk NVMe SSD Drive 512GB                          | 46        | 0.91%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 43        | 0.85%   |
| Toshiba MQ04ABF100 1TB                                | 41        | 0.81%   |
| Toshiba MQ01ABD100 1TB                                | 39        | 0.77%   |
| SK hynix NVMe SSD Drive 512GB                         | 39        | 0.77%   |
| Kingston SA400S37240G 240GB SSD                       | 38        | 0.75%   |
| Unknown MMC Card  32GB                                | 36        | 0.71%   |
| Samsung SSD 860 EVO 500GB                             | 36        | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 35        | 0.69%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 35        | 0.69%   |
| Samsung SSD 850 EVO 500GB                             | 30        | 0.59%   |
| Unknown MMC Card  64GB                                | 29        | 0.57%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 29        | 0.57%   |
| Seagate ST1000LM048-2E7172 1TB                        | 26        | 0.51%   |
| WDC WD10SPZX-21Z10T0 1TB                              | 24        | 0.47%   |
| SanDisk NVMe SSD Drive 256GB                          | 24        | 0.47%   |
| Crucial CT500MX500SSD1 500GB                          | 24        | 0.47%   |
| Seagate ST2000LM007-1R8174 2TB                        | 23        | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB                          | 22        | 0.43%   |
| Kingston SA400S37480G 480GB SSD                       | 22        | 0.43%   |
| Intel SSDPEKNU512GZ 512GB                             | 22        | 0.43%   |
| Unknown MMC Card  128GB                               | 21        | 0.41%   |
| SanDisk NVMe SSD Drive 1TB                            | 21        | 0.41%   |
| Kingston SA400S37120G 120GB SSD                       | 21        | 0.41%   |
| Intel SSD 660P Series 512GB                           | 21        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB                           | 21        | 0.41%   |
| Toshiba NVMe SSD Drive 512GB                          | 20        | 0.39%   |
| Toshiba MQ01ABF050 500GB                              | 20        | 0.39%   |
| Seagate ST500LT012-1DG142 500GB                       | 20        | 0.39%   |
| Seagate ST1000LX015-1U7172 1TB                        | 20        | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB                        | 20        | 0.39%   |
| Samsung NVMe SSD Drive 1TB                            | 20        | 0.39%   |
| HGST HTS541010A9E680 1TB                              | 20        | 0.39%   |
| Samsung SSD 980 1TB                                   | 18        | 0.35%   |
| Samsung SSD 860 EVO 1TB                               | 18        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 388       | 469    | 36.16%  |
| WDC                 | 270       | 309    | 25.16%  |
| Toshiba             | 172       | 194    | 16.03%  |
| HGST                | 122       | 133    | 11.37%  |
| Hitachi             | 65        | 66     | 6.06%   |
| Samsung Electronics | 11        | 11     | 1.03%   |
| Unknown             | 10        | 13     | 0.93%   |
| External            | 5         | 6      | 0.47%   |
| Fujitsu             | 4         | 4      | 0.37%   |
| SABRENT             | 3         | 3      | 0.28%   |
| HGST HTS            | 3         | 3      | 0.28%   |
| Apple               | 3         | 3      | 0.28%   |
| USB3.0              | 2         | 2      | 0.19%   |
| SSK                 | 2         | 2      | 0.19%   |
| SAGE                | 2         | 3      | 0.19%   |
| Generic-            | 2         | 3      | 0.19%   |
| ASMT                | 2         | 3      | 0.19%   |
| ACASIS              | 2         | 2      | 0.19%   |
| Pioneer             | 1         | 1      | 0.09%   |
| PHD 3.0             | 1         | 1      | 0.09%   |
| NeoTech             | 1         | 1      | 0.09%   |
| Maxone              | 1         | 1      | 0.09%   |
| Inateck             | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 355       | 439    | 25.41%  |
| SanDisk             | 154       | 175    | 11.02%  |
| Kingston            | 153       | 189    | 10.95%  |
| Crucial             | 120       | 169    | 8.59%   |
| WDC                 | 87        | 114    | 6.23%   |
| A-DATA Technology   | 42        | 61     | 3.01%   |
| Toshiba             | 36        | 44     | 2.58%   |
| SK hynix            | 36        | 43     | 2.58%   |
| Intel               | 35        | 39     | 2.51%   |
| Micron Technology   | 34        | 41     | 2.43%   |
| LITEON              | 27        | 28     | 1.93%   |
| China               | 26        | 32     | 1.86%   |
| Apple               | 26        | 27     | 1.86%   |
| Transcend           | 25        | 27     | 1.79%   |
| SPCC                | 15        | 16     | 1.07%   |
| PNY                 | 15        | 19     | 1.07%   |
| LITEONIT            | 12        | 12     | 0.86%   |
| KingSpec            | 11        | 12     | 0.79%   |
| JMicron Technology  | 11        | 13     | 0.79%   |
| OCZ                 | 10        | 10     | 0.72%   |
| Intenso             | 10        | 12     | 0.72%   |
| GOODRAM             | 10        | 10     | 0.72%   |
| Patriot             | 9         | 10     | 0.64%   |
| Plextor             | 8         | 8      | 0.57%   |
| FORESEE             | 6         | 9      | 0.43%   |
| TO Exter            | 5         | 10     | 0.36%   |
| Lexar               | 5         | 11     | 0.36%   |
| Gigabyte Technology | 5         | 5      | 0.36%   |
| ASMT                | 5         | 5      | 0.36%   |
| Mushkin             | 4         | 4      | 0.29%   |
| Hewlett-Packard     | 4         | 5      | 0.29%   |
| BHT                 | 4         | 6      | 0.29%   |
| Unknown             | 4         | 4      | 0.29%   |
| Unknown             | 3         | 3      | 0.21%   |
| Team                | 3         | 3      | 0.21%   |
| Phison              | 3         | 3      | 0.21%   |
| Netac               | 3         | 3      | 0.21%   |
| HS-SSD-E100         | 3         | 3      | 0.21%   |
| BIWIN               | 3         | 3      | 0.21%   |
| Apacer              | 3         | 3      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1983      | 2767   | 43.63%  |
| SSD     | 1290      | 1706   | 28.38%  |
| HDD     | 1042      | 1234   | 22.93%  |
| MMC     | 184       | 216    | 4.05%   |
| Unknown | 46        | 49     | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1981      | 2759   | 46.1%   |
| SATA | 1970      | 2794   | 45.85%  |
| MMC  | 184       | 216    | 4.28%   |
| SAS  | 162       | 203    | 3.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1384      | 1828   | 60.2%   |
| 0.51-1.0   | 806       | 969    | 35.06%  |
| 1.01-2.0   | 97        | 130    | 4.22%   |
| 3.01-4.0   | 6         | 7      | 0.26%   |
| 4.01-10.0  | 4         | 4      | 0.17%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |
| 10.01-20.0 | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1030      | 26.77%  |
| 101-250        | 1000      | 25.99%  |
| 501-1000       | 724       | 18.82%  |
| 1001-2000      | 436       | 11.33%  |
| 51-100         | 165       | 4.29%   |
| More than 3000 | 151       | 3.93%   |
| 2001-3000      | 125       | 3.25%   |
| Unknown        | 94        | 2.44%   |
| 21-50          | 64        | 1.66%   |
| 1-20           | 58        | 1.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 887       | 22.03%  |
| 101-250        | 770       | 19.13%  |
| 21-50          | 670       | 16.64%  |
| 51-100         | 581       | 14.43%  |
| 251-500        | 518       | 12.87%  |
| 501-1000       | 319       | 7.92%   |
| 1001-2000      | 118       | 2.93%   |
| Unknown        | 94        | 2.33%   |
| More than 3000 | 38        | 0.94%   |
| 2001-3000      | 30        | 0.75%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                                  | 11        | 11     | 4.7%    |
| HGST HTS721010A9E630 1TB                                        | 11        | 11     | 4.7%    |
| HGST HTS541010A9E680 1TB                                        | 6         | 6      | 2.56%   |
| Seagate ST9500325AS 500GB                                       | 5         | 5      | 2.14%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 5         | 5      | 2.14%   |
| HGST HTS545050A7E680 500GB                                      | 5         | 6      | 2.14%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 4         | 4      | 1.71%   |
| Seagate ST1000LX015-1U7172 1TB                                  | 4         | 5      | 1.71%   |
| HGST HTS725050A7E630 500GB                                      | 4         | 4      | 1.71%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 3         | 3      | 1.28%   |
| Seagate ST500LT012-1DG142 500GB                                 | 3         | 3      | 1.28%   |
| Seagate ST2000LM007-1R8174 2TB                                  | 3         | 3      | 1.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 3         | 3      | 1.28%   |
| Seagate ST1000LM014-SSHD-8GB                                    | 3         | 3      | 1.28%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 4      | 1.28%   |
| Hitachi HTS545025B9A300 250GB                                   | 3         | 3      | 1.28%   |
| Toshiba MQ01ABD100 1TB                                          | 2         | 2      | 0.85%   |
| Toshiba MK3276GSX 320GB                                         | 2         | 2      | 0.85%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD                         | 2         | 2      | 0.85%   |
| Seagate ST9320325AS 320GB                                       | 2         | 2      | 0.85%   |
| Seagate ST9250315AS 250GB                                       | 2         | 2      | 0.85%   |
| Seagate ST500LT012-9WS142 500GB                                 | 2         | 2      | 0.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB                             | 2         | 2      | 0.85%   |
| Seagate ST500LM000-SSHD-8GB                                     | 2         | 2      | 0.85%   |
| Seagate ST2000LX001-1RG174 2TB                                  | 2         | 2      | 0.85%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 2         | 2      | 0.85%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 2         | 2      | 0.85%   |
| Seagate ST1000LM014-1EJ164 1TB                                  | 2         | 2      | 0.85%   |
| SanDisk SD7SB3Q256G1002 256GB SSD                               | 2         | 2      | 0.85%   |
| Samsung Electronics SSD 970 EVO 2TB                             | 2         | 2      | 0.85%   |
| LITEON CV8-8E128-HP 128GB SSD                                   | 2         | 2      | 0.85%   |
| Intel SSDSC2BF240A4L 240GB                                      | 2         | 2      | 0.85%   |
| Hitachi HTS723232A7A364 320GB                                   | 2         | 2      | 0.85%   |
| Hitachi HTS545050A7E380 500GB                                   | 2         | 3      | 0.85%   |
| Hitachi HTS541680J9SA00 80GB                                    | 2         | 2      | 0.85%   |
| Hitachi HTS541616J9SA00 160GB                                   | 2         | 2      | 0.85%   |
| HGST HTS545050A7E380 500GB                                      | 2         | 2      | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1         | 1      | 0.43%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                                  | 1         | 1      | 0.43%   |
| WDC WD7500BPKT-00PK4T0 752GB                                    | 1         | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 67        | 71     | 28.63%  |
| HGST                  | 31        | 32     | 13.25%  |
| WDC                   | 27        | 29     | 11.54%  |
| Toshiba               | 23        | 26     | 9.83%   |
| Hitachi               | 20        | 21     | 8.55%   |
| Samsung Electronics   | 13        | 18     | 5.56%   |
| SK hynix              | 12        | 13     | 5.13%   |
| Intel                 | 7         | 8      | 2.99%   |
| SanDisk               | 6         | 7      | 2.56%   |
| Kingston              | 5         | 5      | 2.14%   |
| Crucial               | 5         | 5      | 2.14%   |
| Micron Technology     | 3         | 4      | 1.28%   |
| LITEON                | 3         | 3      | 1.28%   |
| China                 | 2         | 2      | 0.85%   |
| ASMT                  | 2         | 2      | 0.85%   |
| A-DATA Technology     | 2         | 2      | 0.85%   |
| VNYEZ                 | 1         | 1      | 0.43%   |
| SSSTC                 | 1         | 1      | 0.43%   |
| Realtek Semiconductor | 1         | 1      | 0.43%   |
| OCZ                   | 1         | 1      | 0.43%   |
| KingSpec              | 1         | 1      | 0.43%   |
| Apple                 | 1         | 1      | 0.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 67        | 71     | 41.1%   |
| HGST    | 31        | 32     | 19.02%  |
| WDC     | 25        | 27     | 15.34%  |
| Hitachi | 20        | 21     | 12.27%  |
| Toshiba | 18        | 21     | 11.04%  |
| ASMT    | 1         | 1      | 0.61%   |
| Apple   | 1         | 1      | 0.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 162       | 174    | 69.53%  |
| SSD  | 55        | 60     | 23.61%  |
| NVMe | 16        | 20     | 6.87%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60V5T1 320GB                      | 1         | 1      | 16.67%  |
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB    | 1         | 1      | 16.67%  |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 16.67%  |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 16.67%  |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 16.67%  |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 2         | 3      | 33.33%  |
| WDC                     | 1         | 1      | 16.67%  |
| Union Memory (Shenzhen) | 1         | 1      | 16.67%  |
| Phison                  | 1         | 1      | 16.67%  |
| Kingston                | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1907      | 2892   | 47.4%   |
| Detected | 1881      | 2819   | 46.76%  |
| Malfunc  | 229       | 254    | 5.69%   |
| Failed   | 6         | 7      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2213      | 47.03%  |
| Samsung Electronics              | 711       | 15.11%  |
| AMD                              | 457       | 9.71%   |
| SanDisk                          | 357       | 7.59%   |
| SK hynix                         | 238       | 5.06%   |
| Micron Technology                | 137       | 2.91%   |
| Toshiba America Info Systems     | 108       | 2.29%   |
| Kingston Technology Company      | 105       | 2.23%   |
| Phison Electronics               | 78        | 1.66%   |
| KIOXIA                           | 50        | 1.06%   |
| Micron/Crucial Technology        | 42        | 0.89%   |
| Silicon Motion                   | 35        | 0.74%   |
| ADATA Technology                 | 34        | 0.72%   |
| Union Memory (Shenzhen)          | 19        | 0.4%    |
| Solid State Storage Technology   | 19        | 0.4%    |
| Lenovo                           | 15        | 0.32%   |
| Apple                            | 15        | 0.32%   |
| Yangtze Memory Technologies      | 13        | 0.28%   |
| Realtek Semiconductor            | 13        | 0.28%   |
| Lite-On Technology               | 12        | 0.25%   |
| MAXIO Technology (Hangzhou)      | 8         | 0.17%   |
| Nvidia                           | 6         | 0.13%   |
| Shenzhen Longsys Electronics     | 5         | 0.11%   |
| Silicon Integrated Systems [SiS] | 3         | 0.06%   |
| Marvell Technology Group         | 3         | 0.06%   |
| Biwin Storage Technology         | 3         | 0.06%   |
| Netac Technology                 | 2         | 0.04%   |
| INNOGRIT                         | 2         | 0.04%   |
| Transcend                        | 1         | 0.02%   |
| Seagate Technology               | 1         | 0.02%   |
| ASMedia Technology               | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 434       | 8.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 387       | 7.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 311       | 6.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 207       | 4.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 203       | 4.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 171       | 3.5%    |
| Samsung NVMe SSD Controller 980                                                | 158       | 3.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 131       | 2.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 127       | 2.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 119       | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 116       | 2.38%   |
| Intel Volume Management Device NVMe RAID Controller                            | 112       | 2.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 109       | 2.23%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 96        | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 94        | 1.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 88        | 1.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 71        | 1.45%   |
| Intel SSD 660P Series                                                          | 69        | 1.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 62        | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 61        | 1.25%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 58        | 1.19%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 51        | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                            | 42        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 42        | 0.86%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 40        | 0.82%   |
| Phison E12 NVMe Controller                                                     | 40        | 0.82%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 38        | 0.78%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 35        | 0.72%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 35        | 0.72%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 35        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                          | 35        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 34        | 0.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 34        | 0.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 34        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 34        | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 31        | 0.63%   |
| SK hynix BC511 NVMe SSD                                                        | 30        | 0.61%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 29        | 0.59%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 27        | 0.55%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 27        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2293      | 49.2%   |
| NVMe | 1985      | 42.59%  |
| RAID | 332       | 7.12%   |
| IDE  | 51        | 1.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2842      | 76.91%  |
| AMD    | 853       | 23.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 81        | 2.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 80        | 2.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 77        | 2.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 75        | 2.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 75        | 2.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 74        | 2%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 74        | 2%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 69        | 1.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 63        | 1.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 53        | 1.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 51        | 1.38%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 49        | 1.33%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 48        | 1.3%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 47        | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 46        | 1.24%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 43        | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 43        | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 43        | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 43        | 1.16%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 43        | 1.16%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 39        | 1.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 38        | 1.03%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 37        | 1%      |
| AMD Ryzen 7 4700U with Radeon Graphics        | 34        | 0.92%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 31        | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 30        | 0.81%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 30        | 0.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 29        | 0.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 29        | 0.78%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 27        | 0.73%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 26        | 0.7%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 26        | 0.7%    |
| AMD Ryzen 5 5600H with Radeon Graphics        | 26        | 0.7%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 26        | 0.7%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 26        | 0.7%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 25        | 0.68%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 24        | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.65%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 24        | 0.65%   |
| Intel 12th Gen Core i7-12700H                 | 24        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1014      | 27.42%  |
| Intel Core i5           | 897       | 24.26%  |
| Other                   | 377       | 10.19%  |
| AMD Ryzen 5             | 270       | 7.3%    |
| AMD Ryzen 7             | 269       | 7.27%   |
| Intel Core i3           | 200       | 5.41%   |
| Intel Celeron           | 107       | 2.89%   |
| Intel Core 2 Duo        | 83        | 2.24%   |
| AMD Ryzen 7 PRO         | 72        | 1.95%   |
| AMD Ryzen 9             | 63        | 1.7%    |
| Intel Pentium           | 49        | 1.33%   |
| Intel Atom              | 37        | 1%      |
| AMD Ryzen 3             | 35        | 0.95%   |
| Intel Core i9           | 30        | 0.81%   |
| AMD Ryzen 5 PRO         | 25        | 0.68%   |
| AMD A6                  | 17        | 0.46%   |
| Intel Pentium Silver    | 15        | 0.41%   |
| AMD A4                  | 15        | 0.41%   |
| AMD A10                 | 14        | 0.38%   |
| Intel Xeon              | 12        | 0.32%   |
| AMD A8                  | 12        | 0.32%   |
| AMD E2                  | 10        | 0.27%   |
| Intel Pentium Dual-Core | 7         | 0.19%   |
| Intel Genuine           | 6         | 0.16%   |
| Intel Core m3           | 6         | 0.16%   |
| AMD E1                  | 6         | 0.16%   |
| AMD E                   | 6         | 0.16%   |
| Intel Core 2            | 4         | 0.11%   |
| AMD Athlon              | 4         | 0.11%   |
| AMD A12                 | 4         | 0.11%   |
| Intel Celeron Dual-Core | 3         | 0.08%   |
| Intel Pentium Dual      | 2         | 0.05%   |
| Intel Core m7           | 2         | 0.05%   |
| Intel Core m5           | 2         | 0.05%   |
| Intel Core M            | 2         | 0.05%   |
| AMD Turion Neo X2       | 2         | 0.05%   |
| AMD Phenom II           | 2         | 0.05%   |
| AMD C-60                | 2         | 0.05%   |
| AMD Athlon X2           | 2         | 0.05%   |
| Intel Pentium Gold      | 1         | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 1392      | 37.64%  |
| 2      | 1311      | 35.45%  |
| 8      | 450       | 12.17%  |
| 6      | 421       | 11.38%  |
| 12     | 37        | 1%      |
| 14     | 35        | 0.95%   |
| 1      | 22        | 0.59%   |
| 10     | 20        | 0.54%   |
| 16     | 6         | 0.16%   |
| 24     | 2         | 0.05%   |
| 5      | 1         | 0.03%   |
| 3      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3695      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3180      | 85.97%  |
| 1      | 519       | 14.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3634      | 98.3%   |
| Unknown        | 60        | 1.62%   |
| 32-bit         | 3         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1439      | 37.43%  |
| 0x906ea    | 138       | 3.59%   |
| 0x806ea    | 138       | 3.59%   |
| 0x306a9    | 121       | 3.15%   |
| 0x806ec    | 117       | 3.04%   |
| 0x806c1    | 111       | 2.89%   |
| 0x206a7    | 105       | 2.73%   |
| 0x0a50000c | 104       | 2.71%   |
| 0x406e3    | 99        | 2.58%   |
| 0x306d4    | 89        | 2.32%   |
| 0x40651    | 86        | 2.24%   |
| 0x906e9    | 84        | 2.19%   |
| 0x806e9    | 78        | 2.03%   |
| 0x08108102 | 76        | 1.98%   |
| 0x08600106 | 74        | 1.93%   |
| 0x306c3    | 66        | 1.72%   |
| 0xa0652    | 62        | 1.61%   |
| 0x08108109 | 55        | 1.43%   |
| 0x20655    | 46        | 1.2%    |
| 0x506e3    | 44        | 1.14%   |
| 0x08600104 | 43        | 1.12%   |
| 0x806eb    | 40        | 1.04%   |
| 0x08608103 | 40        | 1.04%   |
| 0x08600103 | 40        | 1.04%   |
| 0x0a404102 | 35        | 0.91%   |
| 0x1067a    | 34        | 0.88%   |
| 0x0810100b | 25        | 0.65%   |
| 0x906a3    | 24        | 0.62%   |
| 0x706e5    | 24        | 0.62%   |
| 0x08608102 | 23        | 0.6%    |
| 0x806d1    | 21        | 0.55%   |
| 0x406c4    | 21        | 0.55%   |
| 0x30678    | 20        | 0.52%   |
| 0x10676    | 19        | 0.49%   |
| 0x906ed    | 18        | 0.47%   |
| 0x706a1    | 16        | 0.42%   |
| 0x506c9    | 16        | 0.42%   |
| 0x20652    | 15        | 0.39%   |
| 0x06006705 | 15        | 0.39%   |
| 0x0a50000d | 13        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 974       | 26.33%  |
| Haswell          | 240       | 6.49%   |
| Skylake          | 236       | 6.38%   |
| Unknown          | 221       | 5.97%   |
| TigerLake        | 209       | 5.65%   |
| Zen 2            | 202       | 5.46%   |
| IvyBridge        | 201       | 5.43%   |
| Zen 3            | 167       | 4.51%   |
| Zen+             | 166       | 4.49%   |
| SandyBridge      | 164       | 4.43%   |
| Broadwell        | 140       | 3.78%   |
| CometLake        | 125       | 3.38%   |
| Penryn           | 83        | 2.24%   |
| Silvermont       | 78        | 2.11%   |
| Westmere         | 77        | 2.08%   |
| Icelake          | 73        | 1.97%   |
| Alderlake Hybrid | 70        | 1.89%   |
| Zen              | 47        | 1.27%   |
| Goldmont plus    | 40        | 1.08%   |
| Excavator        | 39        | 1.05%   |
| Core             | 24        | 0.65%   |
| Goldmont         | 22        | 0.59%   |
| Bobcat           | 17        | 0.46%   |
| Puma             | 14        | 0.38%   |
| Bonnell          | 14        | 0.38%   |
| Nehalem          | 9         | 0.24%   |
| Piledriver       | 8         | 0.22%   |
| Jaguar           | 8         | 0.22%   |
| Tremont          | 7         | 0.19%   |
| K10 Llano        | 7         | 0.19%   |
| K10              | 7         | 0.19%   |
| Steamroller      | 3         | 0.08%   |
| K8 Hammer        | 3         | 0.08%   |
| P6               | 2         | 0.05%   |
| K8 & K10 hybrid  | 2         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2668      | 53.22%  |
| Nvidia                           | 1312      | 26.17%  |
| AMD                              | 1029      | 20.53%  |
| Silicon Integrated Systems [SiS] | 3         | 0.06%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 223       | 4.37%   |
| Intel UHD Graphics 620                                                                   | 214       | 4.19%   |
| AMD Renoir                                                                               | 192       | 3.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 190       | 3.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 186       | 3.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 169       | 3.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 158       | 3.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 147       | 2.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 142       | 2.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 137       | 2.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 131       | 2.57%   |
| Intel HD Graphics 620                                                                    | 125       | 2.45%   |
| Intel HD Graphics 5500                                                                   | 120       | 2.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 111       | 2.17%   |
| Intel HD Graphics 630                                                                    | 101       | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 97        | 1.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 86        | 1.68%   |
| AMD Lucienne                                                                             | 86        | 1.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 79        | 1.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 75        | 1.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 72        | 1.41%   |
| AMD Rembrandt [Radeon 680M]                                                              | 62        | 1.21%   |
| Intel HD Graphics 530                                                                    | 61        | 1.19%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 59        | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 56        | 1.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 55        | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 53        | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 51        | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 50        | 0.98%   |
| Nvidia GP108M [GeForce MX150]                                                            | 48        | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 42        | 0.82%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 42        | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 41        | 0.8%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 37        | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 36        | 0.71%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 34        | 0.67%   |
| Nvidia TU117M                                                                            | 33        | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 33        | 0.65%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 30        | 0.59%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 29        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1531      | 41.29%  |
| Intel + Nvidia           | 986       | 26.59%  |
| 1 x AMD                  | 635       | 17.13%  |
| AMD + Nvidia             | 180       | 4.85%   |
| 1 x Nvidia               | 145       | 3.91%   |
| Intel + AMD              | 139       | 3.75%   |
| 2 x AMD                  | 74        | 2%      |
| 2 x Intel                | 7         | 0.19%   |
| Other                    | 3         | 0.08%   |
| 1 x SiS                  | 3         | 0.08%   |
| Intel + 2 x Nvidia       | 2         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.05%   |
| 2 x Nvidia               | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2903      | 77.85%  |
| Proprietary | 813       | 21.8%   |
| Unknown     | 13        | 0.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2573      | 67.78%  |
| 0.01-0.5   | 396       | 10.43%  |
| 1.01-2.0   | 319       | 8.4%    |
| 3.01-4.0   | 197       | 5.19%   |
| 0.51-1.0   | 144       | 3.79%   |
| 7.01-8.0   | 72        | 1.9%    |
| 5.01-6.0   | 71        | 1.87%   |
| 2.01-3.0   | 12        | 0.32%   |
| 8.01-16.0  | 12        | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 838       | 18.7%   |
| BOE                     | 672       | 14.99%  |
| Chimei Innolux          | 613       | 13.68%  |
| LG Display              | 575       | 12.83%  |
| Samsung Electronics     | 368       | 8.21%   |
| Sharp                   | 193       | 4.31%   |
| Dell                    | 154       | 3.44%   |
| PANDA                   | 114       | 2.54%   |
| Goldstar                | 105       | 2.34%   |
| Lenovo                  | 90        | 2.01%   |
| Apple                   | 73        | 1.63%   |
| Hewlett-Packard         | 66        | 1.47%   |
| AOC                     | 53        | 1.18%   |
| Acer                    | 48        | 1.07%   |
| CSO                     | 45        | 1%      |
| BenQ                    | 45        | 1%      |
| InfoVision              | 44        | 0.98%   |
| Philips                 | 37        | 0.83%   |
| Chi Mei Optoelectronics | 32        | 0.71%   |
| Ancor Communications    | 28        | 0.62%   |
| Iiyama                  | 22        | 0.49%   |
| TMX                     | 20        | 0.45%   |
| ASUSTek Computer        | 16        | 0.36%   |
| Sony                    | 15        | 0.33%   |
| ViewSonic               | 13        | 0.29%   |
| JDI                     | 10        | 0.22%   |
| CPT                     | 10        | 0.22%   |
| Panasonic               | 8         | 0.18%   |
| NEC Computers           | 8         | 0.18%   |
| MSI                     | 8         | 0.18%   |
| Toshiba                 | 7         | 0.16%   |
| LG Philips              | 7         | 0.16%   |
| Eizo                    | 7         | 0.16%   |
| BOE Technology Group    | 7         | 0.16%   |
| Pixio                   | 5         | 0.11%   |
| LGD                     | 5         | 0.11%   |
| InnoLux Display         | 5         | 0.11%   |
| HannStar                | 5         | 0.11%   |
| RTK                     | 4         | 0.09%   |
| Mi                      | 4         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 45        | 0.99%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 42        | 0.93%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 36        | 0.79%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 32        | 0.71%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 29        | 0.64%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 27        | 0.6%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 21        | 0.46%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 21        | 0.46%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 20        | 0.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 19        | 0.42%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 18        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 18        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 17        | 0.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 16        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 16        | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 15        | 0.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 15        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 15        | 0.33%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 15        | 0.33%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.33%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 14        | 0.31%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 14        | 0.31%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 14        | 0.31%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 14        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 13        | 0.29%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 12        | 0.26%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch      | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 12        | 0.26%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 11        | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 11        | 0.24%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 11        | 0.24%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 11        | 0.24%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 10        | 0.22%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 10        | 0.22%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch  | 10        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2157      | 51.88%  |
| 1366x768 (WXGA)    | 797       | 19.17%  |
| 3840x2160 (4K)     | 210       | 5.05%   |
| 2560x1440 (QHD)    | 172       | 4.14%   |
| 1600x900 (HD+)     | 141       | 3.39%   |
| 1920x1200 (WUXGA)  | 105       | 2.53%   |
| 2560x1600          | 81        | 1.95%   |
| 1280x800 (WXGA)    | 57        | 1.37%   |
| 2880x1800          | 51        | 1.23%   |
| 1440x900 (WXGA+)   | 42        | 1.01%   |
| 3840x2400          | 35        | 0.84%   |
| 3440x1440          | 33        | 0.79%   |
| 1680x1050 (WSXGA+) | 33        | 0.79%   |
| 2560x1080          | 22        | 0.53%   |
| 2256x1504          | 21        | 0.51%   |
| 3200x1800 (QHD+)   | 20        | 0.48%   |
| 2160x1440          | 20        | 0.48%   |
| 1280x1024 (SXGA)   | 20        | 0.48%   |
| 1360x768           | 15        | 0.36%   |
| 3200x2000          | 10        | 0.24%   |
| 3072x1920          | 10        | 0.24%   |
| 3000x2000          | 10        | 0.24%   |
| 3840x1600          | 9         | 0.22%   |
| Unknown            | 9         | 0.22%   |
| 2240x1400          | 8         | 0.19%   |
| 1024x600           | 8         | 0.19%   |
| 1920x540           | 6         | 0.14%   |
| 2520x1680          | 5         | 0.12%   |
| 1600x1200          | 5         | 0.12%   |
| 1280x720 (HD)      | 5         | 0.12%   |
| 800x1280           | 4         | 0.1%    |
| 3456x2160          | 4         | 0.1%    |
| 3840x1100          | 3         | 0.07%   |
| 3840x1080          | 3         | 0.07%   |
| 1680x945           | 3         | 0.07%   |
| 2880x1620          | 2         | 0.05%   |
| 1920x550           | 2         | 0.05%   |
| 1920x1280          | 2         | 0.05%   |
| 1400x1050          | 2         | 0.05%   |
| 7680x1440          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1722      | 38.42%  |
| 13      | 693       | 15.46%  |
| 14      | 645       | 14.39%  |
| 17      | 218       | 4.86%   |
| 27      | 200       | 4.46%   |
| 24      | 190       | 4.24%   |
| 23      | 132       | 2.95%   |
| 12      | 108       | 2.41%   |
| 21      | 92        | 2.05%   |
| 16      | 83        | 1.85%   |
| 11      | 54        | 1.2%    |
| Unknown | 52        | 1.16%   |
| 34      | 50        | 1.12%   |
| 18      | 36        | 0.8%    |
| 31      | 29        | 0.65%   |
| 19      | 24        | 0.54%   |
| 22      | 18        | 0.4%    |
| 20      | 16        | 0.36%   |
| 10      | 14        | 0.31%   |
| 84      | 10        | 0.22%   |
| 72      | 8         | 0.18%   |
| 54      | 8         | 0.18%   |
| 40      | 8         | 0.18%   |
| 37      | 8         | 0.18%   |
| 28      | 8         | 0.18%   |
| 25      | 8         | 0.18%   |
| 29      | 7         | 0.16%   |
| 32      | 5         | 0.11%   |
| 26      | 5         | 0.11%   |
| 52      | 4         | 0.09%   |
| 48      | 4         | 0.09%   |
| 74      | 2         | 0.04%   |
| 65      | 2         | 0.04%   |
| 42      | 2         | 0.04%   |
| 38      | 2         | 0.04%   |
| 35      | 2         | 0.04%   |
| 7       | 2         | 0.04%   |
| 3       | 2         | 0.04%   |
| 142     | 1         | 0.02%   |
| 57      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2736      | 61.72%  |
| 201-300        | 523       | 11.8%   |
| 501-600        | 485       | 10.94%  |
| 351-400        | 272       | 6.14%   |
| 401-500        | 171       | 3.86%   |
| 601-700        | 66        | 1.49%   |
| 701-800        | 56        | 1.26%   |
| Unknown        | 52        | 1.17%   |
| 1001-1500      | 22        | 0.5%    |
| 801-900        | 20        | 0.45%   |
| 1501-2000      | 20        | 0.45%   |
| 1-100          | 4         | 0.09%   |
| 901-1000       | 3         | 0.07%   |
| 101-200        | 2         | 0.05%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3220      | 82.86%  |
| 16/10   | 445       | 11.45%  |
| 3/2     | 69        | 1.78%   |
| 21/9    | 64        | 1.65%   |
| Unknown | 34        | 0.87%   |
| 5/4     | 20        | 0.51%   |
| 4/3     | 12        | 0.31%   |
| 32/9    | 8         | 0.21%   |
| 2.65    | 4         | 0.1%    |
| 6/5     | 3         | 0.08%   |
| 3.40    | 3         | 0.08%   |
| 0.67    | 2         | 0.05%   |
| 1.03    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1713      | 38.32%  |
| 81-90          | 1064      | 23.8%   |
| 201-250        | 360       | 8.05%   |
| 71-80          | 261       | 5.84%   |
| 301-350        | 204       | 4.56%   |
| 121-130        | 186       | 4.16%   |
| 61-70          | 105       | 2.35%   |
| 351-500        | 92        | 2.06%   |
| 111-120        | 80        | 1.79%   |
| 251-300        | 65        | 1.45%   |
| 151-200        | 61        | 1.36%   |
| 51-60          | 57        | 1.28%   |
| Unknown        | 52        | 1.16%   |
| More than 1000 | 39        | 0.87%   |
| 141-150        | 38        | 0.85%   |
| 501-1000       | 25        | 0.56%   |
| 91-100         | 25        | 0.56%   |
| 131-140        | 23        | 0.51%   |
| 41-50          | 15        | 0.34%   |
| 1-40           | 5         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2062      | 47.02%  |
| 101-120       | 909       | 20.73%  |
| 51-100        | 619       | 14.12%  |
| 161-240       | 479       | 10.92%  |
| More than 240 | 224       | 5.11%   |
| Unknown       | 52        | 1.19%   |
| 1-50          | 40        | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2931      | 77.6%   |
| 2     | 727       | 19.25%  |
| 3     | 95        | 2.52%   |
| 0     | 16        | 0.42%   |
| 4     | 8         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2244      | 38.77%  |
| Realtek Semiconductor             | 1939      | 33.5%   |
| Qualcomm Atheros                  | 676       | 11.68%  |
| Broadcom                          | 223       | 3.85%   |
| MediaTek                          | 160       | 2.76%   |
| Broadcom Limited                  | 54        | 0.93%   |
| Lenovo                            | 45        | 0.78%   |
| ASIX Electronics                  | 42        | 0.73%   |
| Qualcomm                          | 38        | 0.66%   |
| TP-Link                           | 36        | 0.62%   |
| Sierra Wireless                   | 31        | 0.54%   |
| Ericsson Business Mobile Networks | 27        | 0.47%   |
| Marvell Technology Group          | 24        | 0.41%   |
| Ralink                            | 22        | 0.38%   |
| DisplayLink                       | 20        | 0.35%   |
| Ralink Technology                 | 19        | 0.33%   |
| Xiaomi                            | 18        | 0.31%   |
| Samsung Electronics               | 18        | 0.31%   |
| Dell                              | 18        | 0.31%   |
| Hewlett-Packard                   | 15        | 0.26%   |
| Apple                             | 12        | 0.21%   |
| Google                            | 9         | 0.16%   |
| D-Link                            | 9         | 0.16%   |
| Huawei Technologies               | 8         | 0.14%   |
| Cypress Semiconductor             | 7         | 0.12%   |
| NetGear                           | 6         | 0.1%    |
| Fibocom                           | 6         | 0.1%    |
| Qualcomm Atheros Communications   | 5         | 0.09%   |
| Linksys                           | 5         | 0.09%   |
| JMicron Technology                | 5         | 0.09%   |
| OPPO Electronics                  | 4         | 0.07%   |
| Nvidia                            | 4         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.05%   |
| Motorola PCS                      | 3         | 0.05%   |
| Microsoft                         | 3         | 0.05%   |
| ASUSTek Computer                  | 3         | 0.05%   |
| Arduino SA                        | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.03%   |
| U-Blox                            | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1288      | 18.6%   |
| Intel Wi-Fi 6 AX200                                               | 319       | 4.61%   |
| Intel Wireless 8265 / 8275                                        | 224       | 3.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 221       | 3.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 173       | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 158       | 2.28%   |
| Intel Wi-Fi 6 AX201                                               | 153       | 2.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 136       | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 134       | 1.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 134       | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 133       | 1.92%   |
| Intel Wireless 7265                                               | 122       | 1.76%   |
| Intel Wireless 8260                                               | 109       | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 102       | 1.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 97        | 1.4%    |
| Intel Wireless 7260                                               | 97        | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 92        | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 92        | 1.33%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 90        | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 86        | 1.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 85        | 1.23%   |
| Intel Wireless 3165                                               | 79        | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 73        | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 73        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 72        | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 69        | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 64        | 0.92%   |
| Intel Wireless-AC 9260                                            | 57        | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 54        | 0.78%   |
| Intel Ethernet Connection (4) I219-V                              | 53        | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 45        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 44        | 0.64%   |
| Intel Wireless 3160                                               | 43        | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 42        | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 42        | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 42        | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 41        | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 40        | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 40        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 38        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2159      | 56.36%  |
| Qualcomm Atheros                  | 574       | 14.98%  |
| Realtek Semiconductor             | 511       | 13.34%  |
| Broadcom                          | 188       | 4.91%   |
| MediaTek                          | 157       | 4.1%    |
| Broadcom Limited                  | 43        | 1.12%   |
| Qualcomm                          | 34        | 0.89%   |
| Sierra Wireless                   | 31        | 0.81%   |
| TP-Link                           | 28        | 0.73%   |
| Ralink                            | 22        | 0.57%   |
| Ralink Technology                 | 19        | 0.5%    |
| Ericsson Business Mobile Networks | 11        | 0.29%   |
| Dell                              | 11        | 0.29%   |
| D-Link                            | 7         | 0.18%   |
| Hewlett-Packard                   | 6         | 0.16%   |
| Fibocom                           | 6         | 0.16%   |
| Qualcomm Atheros Communications   | 5         | 0.13%   |
| NetGear                           | 5         | 0.13%   |
| Linksys                           | 5         | 0.13%   |
| ASUSTek Computer                  | 3         | 0.08%   |
| Xiaomi                            | 2         | 0.05%   |
| Quectel Wireless Solutions        | 1         | 0.03%   |
| Microsoft                         | 1         | 0.03%   |
| Marvell Technology Group          | 1         | 0.03%   |
| Edimax Technology                 | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 319       | 8.3%    |
| Intel Wireless 8265 / 8275                                     | 224       | 5.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 158       | 4.11%   |
| Intel Wi-Fi 6 AX201                                            | 153       | 3.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 136       | 3.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 134       | 3.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 133       | 3.46%   |
| Intel Wireless 7265                                            | 122       | 3.17%   |
| Intel Wireless 8260                                            | 109       | 2.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 102       | 2.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 97        | 2.52%   |
| Intel Wireless 7260                                            | 97        | 2.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 92        | 2.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 92        | 2.39%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 90        | 2.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 86        | 2.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 85        | 2.21%   |
| Intel Wireless 3165                                            | 79        | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 73        | 1.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 73        | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 72        | 1.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 64        | 1.67%   |
| Intel Wireless-AC 9260                                         | 57        | 1.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 54        | 1.41%   |
| Intel Wireless 3160                                            | 43        | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 42        | 1.09%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 42        | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 41        | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 40        | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 37        | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 35        | 0.91%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 31        | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                  | 31        | 0.81%   |
| Intel Centrino Ultimate-N 6300                                 | 30        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 27        | 0.7%    |
| Intel Centrino Advanced-N 6235                                 | 25        | 0.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 23        | 0.6%    |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 21        | 0.55%   |
| Intel Centrino Advanced-N 6200                                 | 20        | 0.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 19        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1733      | 58.21%  |
| Intel                            | 769       | 25.83%  |
| Qualcomm Atheros                 | 156       | 5.24%   |
| Broadcom                         | 61        | 2.05%   |
| Lenovo                           | 42        | 1.41%   |
| ASIX Electronics                 | 42        | 1.41%   |
| Marvell Technology Group         | 23        | 0.77%   |
| DisplayLink                      | 20        | 0.67%   |
| Samsung Electronics              | 18        | 0.6%    |
| Xiaomi                           | 16        | 0.54%   |
| Apple                            | 12        | 0.4%    |
| Broadcom Limited                 | 11        | 0.37%   |
| Google                           | 9         | 0.3%    |
| TP-Link                          | 8         | 0.27%   |
| Cypress Semiconductor            | 7         | 0.24%   |
| JMicron Technology               | 5         | 0.17%   |
| Qualcomm                         | 4         | 0.13%   |
| OPPO Electronics                 | 4         | 0.13%   |
| Nvidia                           | 4         | 0.13%   |
| Huawei Technologies              | 4         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.1%    |
| Motorola PCS                     | 3         | 0.1%    |
| MediaTek                         | 3         | 0.1%    |
| Hewlett-Packard                  | 3         | 0.1%    |
| ZTE WCDMA Technologies MSM       | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.07%   |
| Microsoft                        | 2         | 0.07%   |
| D-Link                           | 2         | 0.07%   |
| QNAP System                      | 1         | 0.03%   |
| NetGear                          | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| LG Electronics                   | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| HTC (High Tech Computer)         | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| Attansic Technology              | 1         | 0.03%   |
| Aquantia                         | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1288      | 42.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 221       | 7.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 173       | 5.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 134       | 4.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 69        | 2.28%   |
| Intel Ethernet Connection (4) I219-V                              | 53        | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 45        | 1.48%   |
| Intel Ethernet Connection I217-LM                                 | 44        | 1.45%   |
| Intel Ethernet Connection I219-LM                                 | 42        | 1.39%   |
| Intel Ethernet Connection (6) I219-V                              | 40        | 1.32%   |
| Intel Ethernet Connection I218-LM                                 | 38        | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                     | 37        | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 32        | 1.06%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 31        | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 31        | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                             | 27        | 0.89%   |
| Intel Ethernet Connection (6) I219-LM                             | 26        | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 25        | 0.82%   |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19        | 0.63%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.59%   |
| Intel Ethernet Connection (10) I219-V                             | 18        | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 16        | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                             | 14        | 0.46%   |
| Intel Ethernet Connection (13) I219-V                             | 14        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11        | 0.36%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 11        | 0.36%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.33%   |
| Lenovo USB-C Dock Ethernet                                        | 10        | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.3%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 9         | 0.3%    |
| Intel Ethernet Connection (16) I219-V                             | 9         | 0.3%    |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3663      | 56.03%  |
| Ethernet | 2823      | 43.18%  |
| Modem    | 45        | 0.69%   |
| Unknown  | 6         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3128      | 79.35%  |
| Ethernet | 813       | 20.62%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2549      | 68.87%  |
| 1     | 1076      | 29.07%  |
| 3     | 44        | 1.19%   |
| 0     | 30        | 0.81%   |
| 4     | 2         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3067      | 81.55%  |
| Yes  | 694       | 18.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1827      | 56.48%  |
| Realtek Semiconductor           | 311       | 9.61%   |
| Qualcomm Atheros Communications | 256       | 7.91%   |
| IMC Networks                    | 164       | 5.07%   |
| Lite-On Technology              | 139       | 4.3%    |
| Broadcom                        | 135       | 4.17%   |
| Foxconn / Hon Hai               | 133       | 4.11%   |
| Apple                           | 53        | 1.64%   |
| Realtek                         | 44        | 1.36%   |
| Dell                            | 34        | 1.05%   |
| Cambridge Silicon Radio         | 25        | 0.77%   |
| Hewlett-Packard                 | 19        | 0.59%   |
| MediaTek                        | 16        | 0.49%   |
| USI                             | 13        | 0.4%    |
| Toshiba                         | 13        | 0.4%    |
| Ralink                          | 12        | 0.37%   |
| Foxconn International           | 8         | 0.25%   |
| ASUSTek Computer                | 6         | 0.19%   |
| Opticis                         | 4         | 0.12%   |
| TP-Link                         | 3         | 0.09%   |
| Chicony Electronics             | 3         | 0.09%   |
| Askey Computer                  | 3         | 0.09%   |
| Smart Modular Technologies      | 2         | 0.06%   |
| Ralink Technology               | 2         | 0.06%   |
| Dynex                           | 2         | 0.06%   |
| Alps Electric                   | 2         | 0.06%   |
| Syntek                          | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Marvell Semiconductor           | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 647       | 19.97%  |
| Intel AX201 Bluetooth                               | 331       | 10.22%  |
| Intel AX200 Bluetooth                               | 301       | 9.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 272       | 8.4%    |
| Realtek Bluetooth Radio                             | 204       | 6.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 140       | 4.32%   |
| Intel Bluetooth Device                              | 95        | 2.93%   |
| Intel AX210 Bluetooth                               | 85        | 2.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 69        | 2.13%   |
| IMC Networks Wireless_Device                        | 59        | 1.82%   |
| IMC Networks Bluetooth Radio                        | 53        | 1.64%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 52        | 1.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 49        | 1.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 47        | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 46        | 1.42%   |
| Lite-On Bluetooth Device                            | 43        | 1.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 42        | 1.3%    |
| Realtek 802.11ac WLAN Adapter                       | 37        | 1.14%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 37        | 1.14%   |
| Apple Bluetooth Host Controller                     | 34        | 1.05%   |
| IMC Networks Bluetooth Device                       | 33        | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 29        | 0.9%    |
| Foxconn / Hon Hai Wireless_Device                   | 29        | 0.9%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 26        | 0.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 26        | 0.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 25        | 0.77%   |
| Lite-On Wireless_Device                             | 23        | 0.71%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 21        | 0.65%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 0.56%   |
| MediaTek Wireless_Device                            | 15        | 0.46%   |
| USI Bluetooth Device                                | 13        | 0.4%    |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.4%    |
| Apple Bluetooth USB Host Controller                 | 13        | 0.4%    |
| Realtek RTL8821A Bluetooth                          | 12        | 0.37%   |
| Ralink RT3290 Bluetooth                             | 12        | 0.37%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.37%   |
| Dell DW375 Bluetooth Module                         | 12        | 0.37%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.37%   |
| Broadcom HP Portable SoftSailing                    | 11        | 0.34%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 9         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2800      | 57.51%  |
| AMD                                  | 914       | 18.77%  |
| Nvidia                               | 731       | 15.01%  |
| C-Media Electronics                  | 47        | 0.97%   |
| Lenovo                               | 41        | 0.84%   |
| Realtek Semiconductor                | 38        | 0.78%   |
| Logitech                             | 23        | 0.47%   |
| Texas Instruments                    | 21        | 0.43%   |
| JMTek                                | 21        | 0.43%   |
| GN Netcom                            | 17        | 0.35%   |
| Kingston Technology                  | 15        | 0.31%   |
| Focusrite-Novation                   | 15        | 0.31%   |
| Apple                                | 15        | 0.31%   |
| Razer USA                            | 12        | 0.25%   |
| SteelSeries ApS                      | 10        | 0.21%   |
| Plantronics                          | 9         | 0.18%   |
| Creative Technology                  | 8         | 0.16%   |
| Hewlett-Packard                      | 7         | 0.14%   |
| ASUSTek Computer                     | 7         | 0.14%   |
| Generalplus Technology               | 5         | 0.1%    |
| Samson Technologies                  | 4         | 0.08%   |
| Corsair                              | 4         | 0.08%   |
| Yamaha                               | 3         | 0.06%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.06%   |
| Sennheiser Communications            | 3         | 0.06%   |
| SAVITECH                             | 3         | 0.06%   |
| DSEA A/S                             | 3         | 0.06%   |
| Conexant Systems                     | 3         | 0.06%   |
| Unknown                              | 3         | 0.06%   |
| XMOS                                 | 2         | 0.04%   |
| Valve Software                       | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.04%   |
| Schiit Audio                         | 2         | 0.04%   |
| No brand                             | 2         | 0.04%   |
| Native Instruments                   | 2         | 0.04%   |
| Microsoft                            | 2         | 0.04%   |
| Medeli Electronics                   | 2         | 0.04%   |
| Mackie Designs                       | 2         | 0.04%   |
| Jieli Technology                     | 2         | 0.04%   |
| JBL                                  | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 719       | 12%     |
| Intel Sunrise Point-LP HD Audio                                                                   | 512       | 8.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 363       | 6.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 240       | 4.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 226       | 3.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 209       | 3.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 192       | 3.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 167       | 2.79%   |
| Intel Broadwell-U Audio Controller                                                                | 139       | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 138       | 2.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 135       | 2.25%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 132       | 2.2%    |
| Intel 8 Series HD Audio Controller                                                                | 132       | 2.2%    |
| Intel CM238 HD Audio Controller                                                                   | 120       | 2%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 117       | 1.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 117       | 1.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 111       | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 97        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 94        | 1.57%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 94        | 1.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 86        | 1.44%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 83        | 1.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 74        | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 74        | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 69        | 1.15%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 67        | 1.12%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 58        | 0.97%   |
| Nvidia Audio device                                                                               | 57        | 0.95%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 55        | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 54        | 0.9%    |
| AMD FCH Azalia Controller                                                                         | 47        | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 41        | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 40        | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 39        | 0.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 39        | 0.65%   |
| AMD Kabini HDMI/DP Audio                                                                          | 36        | 0.6%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 35        | 0.58%   |
| Realtek Semiconductor USB Audio                                                                   | 30        | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 30        | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 28        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 979       | 30.11%  |
| SK hynix            | 733       | 22.55%  |
| Micron Technology   | 435       | 13.38%  |
| Kingston            | 311       | 9.57%   |
| Crucial             | 203       | 6.24%   |
| Unknown             | 110       | 3.38%   |
| Ramaxel Technology  | 81        | 2.49%   |
| A-DATA Technology   | 67        | 2.06%   |
| Corsair             | 55        | 1.69%   |
| Elpida              | 44        | 1.35%   |
| G.Skill             | 24        | 0.74%   |
| Nanya Technology    | 19        | 0.58%   |
| Team                | 15        | 0.46%   |
| Patriot             | 15        | 0.46%   |
| GOODRAM             | 15        | 0.46%   |
| Transcend           | 13        | 0.4%    |
| Smart               | 13        | 0.4%    |
| Unknown             | 13        | 0.4%    |
| Unknown (ABCD)      | 12        | 0.37%   |
| Smart Brazil        | 7         | 0.22%   |
| AMD                 | 7         | 0.22%   |
| Teikon              | 6         | 0.18%   |
| PNY                 | 5         | 0.15%   |
| Goldkey             | 5         | 0.15%   |
| Apacer              | 5         | 0.15%   |
| Avant               | 4         | 0.12%   |
| V-GeN               | 3         | 0.09%   |
| GSkill              | 3         | 0.09%   |
| 48spaces            | 3         | 0.09%   |
| V-Color             | 2         | 0.06%   |
| Unknown (08AE)      | 2         | 0.06%   |
| Silicon Power       | 2         | 0.06%   |
| PKI/Kingston        | 2         | 0.06%   |
| Neo Forza           | 2         | 0.06%   |
| High Bridge         | 2         | 0.06%   |
| fef5                | 2         | 0.06%   |
| ASint Technology    | 2         | 0.06%   |
| 4ea5                | 2         | 0.06%   |
| ZIFEI               | 1         | 0.03%   |
| Wilk                | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 62        | 1.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 59        | 1.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 58        | 1.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 42        | 1.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 36        | 1.05%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 35        | 1.02%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 33        | 0.96%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 31        | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 29        | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 27        | 0.79%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 27        | 0.79%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 27        | 0.79%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 26        | 0.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.73%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 25        | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 23        | 0.67%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.67%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 22        | 0.64%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 22        | 0.64%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.64%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.58%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.55%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 19        | 0.55%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 18        | 0.53%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 18        | 0.53%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 17        | 0.5%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 17        | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 16        | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 16        | 0.47%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 16        | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.44%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 15        | 0.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 15        | 0.44%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.44%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 14        | 0.41%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 14        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1570      | 58.49%  |
| DDR3    | 665       | 24.78%  |
| LPDDR4  | 142       | 5.29%   |
| LPDDR3  | 106       | 3.95%   |
| DDR5    | 62        | 2.31%   |
| LPDDR5  | 61        | 2.27%   |
| DDR2    | 39        | 1.45%   |
| SDRAM   | 32        | 1.19%   |
| Unknown | 5         | 0.19%   |
| DRAM    | 1         | 0.04%   |
| DDR     | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2325      | 86.27%  |
| Row Of Chips | 317       | 11.76%  |
| Chip         | 31        | 1.15%   |
| Unknown      | 14        | 0.52%   |
| DIMM         | 8         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1333      | 45.22%  |
| 4096  | 713       | 24.19%  |
| 16384 | 534       | 18.11%  |
| 2048  | 211       | 7.16%   |
| 32768 | 121       | 4.1%    |
| 1024  | 36        | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 713       | 24.43%  |
| 3200    | 637       | 21.82%  |
| 1600    | 478       | 16.38%  |
| 2400    | 265       | 9.08%   |
| 2133    | 163       | 5.58%   |
| 1334    | 97        | 3.32%   |
| 4267    | 68        | 2.33%   |
| 4800    | 61        | 2.09%   |
| 6400    | 59        | 2.02%   |
| 3266    | 58        | 1.99%   |
| 1333    | 58        | 1.99%   |
| 1867    | 48        | 1.64%   |
| 1067    | 33        | 1.13%   |
| 667     | 29        | 0.99%   |
| 4266    | 27        | 0.92%   |
| 4199    | 19        | 0.65%   |
| 8400    | 18        | 0.62%   |
| Unknown | 14        | 0.48%   |
| 1066    | 13        | 0.45%   |
| 2048    | 10        | 0.34%   |
| 975     | 9         | 0.31%   |
| 2933    | 8         | 0.27%   |
| 800     | 8         | 0.27%   |
| 3733    | 6         | 0.21%   |
| 5600    | 2         | 0.07%   |
| 1866    | 2         | 0.07%   |
| 1777    | 2         | 0.07%   |
| 1200    | 2         | 0.07%   |
| 533     | 2         | 0.07%   |
| 400     | 2         | 0.07%   |
| 6000    | 1         | 0.03%   |
| 3400    | 1         | 0.03%   |
| 3000    | 1         | 0.03%   |
| 2666    | 1         | 0.03%   |
| 1776    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 666     | 1         | 0.03%   |
| 200     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 52.63%  |
| Samsung Electronics | 2         | 10.53%  |
| Prolific Technology | 2         | 10.53%  |
| Canon               | 2         | 10.53%  |
| Seiko Epson         | 1         | 5.26%   |
| Dymo-CoStar         | 1         | 5.26%   |
| Brother Industries  | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 2         | 10.53%  |
| HP DeskJet 2130 series        | 2         | 10.53%  |
| Seiko Epson WF-2530 Series    | 1         | 5.26%   |
| Samsung SCX-3200 Series       | 1         | 5.26%   |
| Samsung M2020 Series          | 1         | 5.26%   |
| HP OfficeJet 5600 (USBHUB)    | 1         | 5.26%   |
| HP LaserJet P1102             | 1         | 5.26%   |
| HP LaserJet 1320              | 1         | 5.26%   |
| HP LaserJet 1022              | 1         | 5.26%   |
| HP ENVY 5000 series           | 1         | 5.26%   |
| HP DeskJet 840c               | 1         | 5.26%   |
| HP DeskJet 4100 series        | 1         | 5.26%   |
| HP DeskJet 2600 series        | 1         | 5.26%   |
| Dymo-CoStar LabelWriter 400   | 1         | 5.26%   |
| Canon PIXMA MG2500 Series     | 1         | 5.26%   |
| Canon LiDE 400                | 1         | 5.26%   |
| Brother HL-1110 series        | 1         | 5.26%   |

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
| Chicony Electronics                    | 805       | 23.75%  |
| IMC Networks                           | 440       | 12.98%  |
| Microdia                               | 308       | 9.09%   |
| Bison Electronics                      | 301       | 8.88%   |
| Realtek Semiconductor                  | 243       | 7.17%   |
| Quanta                                 | 213       | 6.29%   |
| Sunplus Innovation Technology          | 168       | 4.96%   |
| Cheng Uei Precision Industry (Foxlink) | 118       | 3.48%   |
| Syntek                                 | 103       | 3.04%   |
| Lite-On Technology                     | 95        | 2.8%    |
| Luxvisions Innotech Limited            | 70        | 2.07%   |
| Logitech                               | 62        | 1.83%   |
| Acer                                   | 58        | 1.71%   |
| Suyin                                  | 56        | 1.65%   |
| Apple                                  | 55        | 1.62%   |
| Silicon Motion                         | 40        | 1.18%   |
| Alcor Micro                            | 35        | 1.03%   |
| Sonix Technology                       | 25        | 0.74%   |
| Lenovo                                 | 23        | 0.68%   |
| Samsung Electronics                    | 18        | 0.53%   |
| SunplusIT                              | 15        | 0.44%   |
| Importek                               | 13        | 0.38%   |
| Ricoh                                  | 11        | 0.32%   |
| ALi                                    | 11        | 0.32%   |
| Primax Electronics                     | 9         | 0.27%   |
| Microsoft                              | 7         | 0.21%   |
| Z-Star Microelectronics                | 6         | 0.18%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.15%   |
| ARC International                      | 5         | 0.15%   |
| OmniVision Technologies                | 4         | 0.12%   |
| MacroSilicon                           | 4         | 0.12%   |
| Google                                 | 4         | 0.12%   |
| ShineTech                              | 3         | 0.09%   |
| LG Electronics                         | 3         | 0.09%   |
| Valve Software                         | 2         | 0.06%   |
| Razer USA                              | 2         | 0.06%   |
| Pixart Imaging                         | 2         | 0.06%   |
| kingcome                               | 2         | 0.06%   |
| Intel                                  | 2         | 0.06%   |
| icSpring                               | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 229       | 6.7%    |
| Microdia Integrated_Webcam_HD                                              | 176       | 5.15%   |
| IMC Networks Integrated Camera                                             | 144       | 4.22%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 133       | 3.89%   |
| Bison Integrated Camera                                                    | 97        | 2.84%   |
| Realtek Integrated_Webcam_HD                                               | 92        | 2.69%   |
| Chicony HD WebCam                                                          | 82        | 2.4%    |
| Sunplus Integrated_Webcam_HD                                               | 74        | 2.17%   |
| Syntek Integrated Camera                                                   | 68        | 1.99%   |
| Quanta HD User Facing                                                      | 52        | 1.52%   |
| Lite-On Integrated Camera                                                  | 50        | 1.46%   |
| Bison HD Webcam                                                            | 49        | 1.43%   |
| Bison SunplusIT Integrated Camera                                          | 45        | 1.32%   |
| Chicony USB2.0 Camera                                                      | 37        | 1.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 35        | 1.02%   |
| Chicony Integrated Camera (1280x720@30)                                    | 35        | 1.02%   |
| Chicony HD User Facing                                                     | 35        | 1.02%   |
| Microdia Integrated Webcam                                                 | 31        | 0.91%   |
| Chicony HP HD Camera                                                       | 31        | 0.91%   |
| Sunplus HD WebCam                                                          | 26        | 0.76%   |
| IMC Networks HD Camera                                                     | 25        | 0.73%   |
| Chicony HP Wide Vision HD Camera                                           | 25        | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 25        | 0.73%   |
| Chicony Integrated IR Camera                                               | 24        | 0.7%    |
| Realtek Integrated Webcam                                                  | 23        | 0.67%   |
| Quanta HP Wide Vision HD Camera                                            | 23        | 0.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 23        | 0.67%   |
| Chicony HP Truevision HD                                                   | 23        | 0.67%   |
| Realtek USB Camera                                                         | 22        | 0.64%   |
| Quanta VGA WebCam                                                          | 22        | 0.64%   |
| Quanta HP TrueVision HD Camera                                             | 22        | 0.64%   |
| Chicony HP TrueVision HD Camera                                            | 21        | 0.61%   |
| IMC Networks ov9734_azurewave_camera                                       | 20        | 0.59%   |
| Chicony USB2.0 HD UVC WebCam                                               | 20        | 0.59%   |
| Chicony EasyCamera                                                         | 20        | 0.59%   |
| Quanta HP HD Camera                                                        | 19        | 0.56%   |
| Quanta HD Webcam                                                           | 19        | 0.56%   |
| Lite-On HP HD Camera                                                       | 19        | 0.56%   |
| Chicony ThinkPad T490 Webcam                                               | 19        | 0.56%   |
| Syntek Lenovo EasyCamera                                                   | 18        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 276       | 34.76%  |
| Validity Sensors                   | 215       | 27.08%  |
| Shenzhen Goodix Technology         | 154       | 19.4%   |
| Elan Microelectronics              | 50        | 6.3%    |
| LighTuning Technology              | 31        | 3.9%    |
| Upek                               | 29        | 3.65%   |
| AuthenTec                          | 20        | 2.52%   |
| STMicroelectronics                 | 9         | 1.13%   |
| Samsung Electronics                | 3         | 0.38%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.38%   |
| HOLTEK                             | 3         | 0.38%   |
| Focal-systems.Corp                 | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 117       | 14.74%  |
| Shenzhen Goodix  Fingerprint Device                                        | 90        | 11.34%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 55        | 6.93%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 42        | 5.29%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 35        | 4.41%   |
| Shenzhen Goodix FingerPrint                                                | 35        | 4.41%   |
| Shenzhen Goodix Fingerprint Reader                                         | 29        | 3.65%   |
| Validity Sensors Synaptics WBDI                                            | 27        | 3.4%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 27        | 3.4%    |
| Elan ELAN:Fingerprint                                                      | 25        | 3.15%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 24        | 3.02%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 19        | 2.39%   |
| Elan ELAN:ARM-M4                                                           | 19        | 2.39%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 2.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 18        | 2.27%   |
| Synaptics Fingerprint reader [HP G6]                                       | 17        | 2.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.89%   |
| Synaptics UWP WBDI Device                                                  | 14        | 1.76%   |
| Validity Sensors VFS491                                                    | 13        | 1.64%   |
| Validity Sensors Fingerprint scanner                                       | 13        | 1.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 13        | 1.64%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 1.39%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 1.39%   |
| AuthenTec AES2810                                                          | 11        | 1.39%   |
| Synaptics UWP WBDI                                                         | 10        | 1.26%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 1.13%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 1.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 0.76%   |
| Synaptics  WBDI                                                            | 6         | 0.76%   |
| Elan WBF Fingerprint Sensor                                                | 6         | 0.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.5%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.5%    |
| Synaptics WBDI Device                                                      | 4         | 0.5%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.38%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.38%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.38%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.38%   |
| HOLTEK FocalTech Fingerprint Device                                        | 3         | 0.38%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.38%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 135       | 42.99%  |
| Broadcom                  | 116       | 36.94%  |
| Upek                      | 24        | 7.64%   |
| Lenovo                    | 13        | 4.14%   |
| O2 Micro                  | 9         | 2.87%   |
| SCM Microsystems          | 4         | 1.27%   |
| Yubico.com                | 3         | 0.96%   |
| Gemalto (was Gemplus)     | 3         | 0.96%   |
| Clay Logic                | 2         | 0.64%   |
| Realtek Semiconductor     | 1         | 0.32%   |
| Hewlett-Packard           | 1         | 0.32%   |
| Chicony Electronics       | 1         | 0.32%   |
| Aladdin Knowledge Systems | 1         | 0.32%   |
| Aktiv                     | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 135       | 42.99%  |
| Broadcom 5880                                                                | 33        | 10.51%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 30        | 9.55%   |
| Broadcom BCM5880 Secure Applications Processor                               | 26        | 8.28%   |
| Broadcom 58200                                                               | 25        | 7.96%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 7.64%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 4.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 2.55%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.96%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.96%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.96%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.64%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.64%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.32%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.32%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.32%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.32%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.32%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.32%   |
| Aktiv Rutoken lite                                                           | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2250      | 59.45%  |
| 1     | 1200      | 31.7%   |
| 2     | 267       | 7.05%   |
| 3     | 58        | 1.53%   |
| 4     | 8         | 0.21%   |
| 7     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 775       | 40.94%  |
| Graphics card            | 354       | 18.7%   |
| Chipcard                 | 275       | 14.53%  |
| Multimedia controller    | 137       | 7.24%   |
| Net/wireless             | 110       | 5.81%   |
| Camera                   | 101       | 5.34%   |
| Bluetooth                | 35        | 1.85%   |
| Net/ethernet             | 19        | 1%      |
| Storage                  | 17        | 0.9%    |
| Sound                    | 16        | 0.85%   |
| Communication controller | 14        | 0.74%   |
| Card reader              | 12        | 0.63%   |
| Network                  | 11        | 0.58%   |
| Modem                    | 7         | 0.37%   |
| Dvb card                 | 3         | 0.16%   |
| Wireless                 | 2         | 0.11%   |
| Unassigned class         | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |
| Flash memory             | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |

