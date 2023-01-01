Linux in Romania - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Romania.

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

Total: 1515

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion 5 15ACH6H 82JU       | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [8db34630c3](https://linux-hardware.org/?probe=8db34630c3) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1ff4c4bf09](https://linux-hardware.org/?probe=1ff4c4bf09) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| Dell          | Latitude 7480               | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| Acer          | Aspire VX5-591G             | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [81f7e4d804](https://linux-hardware.org/?probe=81f7e4d804) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | [6306be2273](https://linux-hardware.org/?probe=6306be2273) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | [cf8576151f](https://linux-hardware.org/?probe=cf8576151f) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [20544e55bb](https://linux-hardware.org/?probe=20544e55bb) | Dec 14, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| ASUSTek       | G75VW                       | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [a1f1288337](https://linux-hardware.org/?probe=a1f1288337) | Dec 13, 2022 |
| ASUSTek       | GL752VW                     | [05c7382806](https://linux-hardware.org/?probe=05c7382806) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a7a3ccf712](https://linux-hardware.org/?probe=a7a3ccf712) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [83b02f1ffb](https://linux-hardware.org/?probe=83b02f1ffb) | Dec 10, 2022 |
| Dell          | Latitude E6520              | [ec32b72261](https://linux-hardware.org/?probe=ec32b72261) | Dec 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea7638c0f9](https://linux-hardware.org/?probe=ea7638c0f9) | Dec 07, 2022 |
| Acer          | Aspire A515-51G             | [10f8aab734](https://linux-hardware.org/?probe=10f8aab734) | Dec 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a35bac4078](https://linux-hardware.org/?probe=a35bac4078) | Dec 06, 2022 |
| ASUSTek       | X556UQK                     | [2f693620e1](https://linux-hardware.org/?probe=2f693620e1) | Dec 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [b387887bb6](https://linux-hardware.org/?probe=b387887bb6) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | [3d64de28f5](https://linux-hardware.org/?probe=3d64de28f5) | Dec 01, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1FR0... | [517347d2cf](https://linux-hardware.org/?probe=517347d2cf) | Nov 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [972f6f4355](https://linux-hardware.org/?probe=972f6f4355) | Nov 28, 2022 |
| HUAWEI        | BOD-WXX9                    | [5b2f9bfd5c](https://linux-hardware.org/?probe=5b2f9bfd5c) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | [a39632439e](https://linux-hardware.org/?probe=a39632439e) | Nov 27, 2022 |
| Acer          | Nitro AN515-58              | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| HP            | ProBook 450 G7              | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Dell          | Latitude E6410              | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| ASUSTek       | X541UAK                     | [75af06e026](https://linux-hardware.org/?probe=75af06e026) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c5ec7b9dcc](https://linux-hardware.org/?probe=c5ec7b9dcc) | Nov 20, 2022 |
| Lenovo        | V15 G1 IML 82NB             | [a120cac88b](https://linux-hardware.org/?probe=a120cac88b) | Nov 18, 2022 |
| Allview       | Allbook H                   | [4de72c8cba](https://linux-hardware.org/?probe=4de72c8cba) | Nov 17, 2022 |
| ASUSTek       | X550VX                      | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61bcea3891](https://linux-hardware.org/?probe=61bcea3891) | Nov 13, 2022 |
| Alienware     | Area-51m                    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| Dell          | Latitude E7270              | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Dell          | Latitude E7470              | [e80d2221f5](https://linux-hardware.org/?probe=e80d2221f5) | Nov 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Toshiba       | Satellite C50-A-1HF         | [8384350121](https://linux-hardware.org/?probe=8384350121) | Nov 08, 2022 |
| Acer          | Aspire A314-35              | [14751e1ae3](https://linux-hardware.org/?probe=14751e1ae3) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| Valve         | Jupiter                     | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| HP            | Laptop 15-da0xxx            | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Valve         | Jupiter                     | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [7dc3ed5f76](https://linux-hardware.org/?probe=7dc3ed5f76) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81A8     | [85efda7536](https://linux-hardware.org/?probe=85efda7536) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Dell          | XPS 15 9530                 | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | [f9238c2035](https://linux-hardware.org/?probe=f9238c2035) | Oct 28, 2022 |
| Samsung       | 550P5C/550P7C               | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [7274eca48b](https://linux-hardware.org/?probe=7274eca48b) | Oct 23, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| MSI           | GV72 7RE                    | [84941aaa84](https://linux-hardware.org/?probe=84941aaa84) | Oct 14, 2022 |
| ASUSTek       | N53Jf                       | [a6a5cdbf04](https://linux-hardware.org/?probe=a6a5cdbf04) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Dell          | XPS 15 9530                 | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| Medion        | Akoya E6239                 | [46ce690b32](https://linux-hardware.org/?probe=46ce690b32) | Oct 10, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| Dell          | Latitude E6410              | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Valve         | Jupiter                     | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d9474bd3b9](https://linux-hardware.org/?probe=d9474bd3b9) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| Medion        | Akoya P2214T                | [428205d2a5](https://linux-hardware.org/?probe=428205d2a5) | Oct 02, 2022 |
| HP            | Laptop 15-da0xxx            | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [3e92ba3812](https://linux-hardware.org/?probe=3e92ba3812) | Sep 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [96c4c8ba02](https://linux-hardware.org/?probe=96c4c8ba02) | Sep 28, 2022 |
| Dell          | System Inspiron N7110       | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| Acer          | Aspire 5750Z                | [38e1cc9153](https://linux-hardware.org/?probe=38e1cc9153) | Sep 22, 2022 |
| Fusion5       | S14                         | [9b3e06c4e4](https://linux-hardware.org/?probe=9b3e06c4e4) | Sep 22, 2022 |
| Acer          | Aspire 5750Z                | [b673d5cfe9](https://linux-hardware.org/?probe=b673d5cfe9) | Sep 22, 2022 |
| Dell          | Precision 3561              | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| HP            | ProBook 640 G4              | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| Acer          | Aspire 5349                 | [39f83f7692](https://linux-hardware.org/?probe=39f83f7692) | Sep 13, 2022 |
| Dell          | XPS 15 9530                 | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Samsung       | R530/R730/R540              | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| HP            | Pavilion g6                 | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| HP            | EliteBook 8440p             | [3474424d64](https://linux-hardware.org/?probe=3474424d64) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [e47c8e6967](https://linux-hardware.org/?probe=e47c8e6967) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [3f805d59b5](https://linux-hardware.org/?probe=3f805d59b5) | Sep 04, 2022 |
| Acer          | Extensa 5635ZG              | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| Dell          | Latitude 5521               | [dcf7869cf6](https://linux-hardware.org/?probe=dcf7869cf6) | Sep 01, 2022 |
| Valve         | Jupiter                     | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| Dell          | Latitude E7470              | [568c9bfd40](https://linux-hardware.org/?probe=568c9bfd40) | Aug 28, 2022 |
| Acer          | Aspire A315-23              | [4c16a58579](https://linux-hardware.org/?probe=4c16a58579) | Aug 28, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [fbf3d4a87a](https://linux-hardware.org/?probe=fbf3d4a87a) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| ASUSTek       | X550CC                      | [8b85141416](https://linux-hardware.org/?probe=8b85141416) | Aug 26, 2022 |
| Complet       | MY8312                      | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [09feb7053d](https://linux-hardware.org/?probe=09feb7053d) | Aug 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [69281b6cc3](https://linux-hardware.org/?probe=69281b6cc3) | Aug 24, 2022 |
| Dell          | Latitude 7410               | [ae90ce90ed](https://linux-hardware.org/?probe=ae90ce90ed) | Aug 22, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Latitude 7420               | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [1a0800fc4a](https://linux-hardware.org/?probe=1a0800fc4a) | Aug 19, 2022 |
| Dell          | Inspiron 5558               | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Dell          | Inspiron 1501               | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Acer          | Aspire V3-571G              | [f45a97ca40](https://linux-hardware.org/?probe=f45a97ca40) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [eb79423b1d](https://linux-hardware.org/?probe=eb79423b1d) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [6826a8d40d](https://linux-hardware.org/?probe=6826a8d40d) | Aug 08, 2022 |
| ASUSTek       | X550CL                      | [83626d765b](https://linux-hardware.org/?probe=83626d765b) | Aug 08, 2022 |
| Dell          | Latitude E6540              | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Acer          | Aspire A515-45              | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| HP            | Pavilion 15                 | [e6bfde2a29](https://linux-hardware.org/?probe=e6bfde2a29) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8b3fd99e18](https://linux-hardware.org/?probe=8b3fd99e18) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4ee4fc0689](https://linux-hardware.org/?probe=4ee4fc0689) | Jul 26, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [9a5f11c4b9](https://linux-hardware.org/?probe=9a5f11c4b9) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Acer          | Aspire SW3-016              | [c48cdf5576](https://linux-hardware.org/?probe=c48cdf5576) | Jul 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [55efce6cdc](https://linux-hardware.org/?probe=55efce6cdc) | Jul 13, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [be909dd3b4](https://linux-hardware.org/?probe=be909dd3b4) | Jul 12, 2022 |
| HP            | 355 G2                      | [55239c5062](https://linux-hardware.org/?probe=55239c5062) | Jul 11, 2022 |
| HP            | 355 G2                      | [9b5e64b838](https://linux-hardware.org/?probe=9b5e64b838) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| HP            | 250 G4                      | [33dcd9203d](https://linux-hardware.org/?probe=33dcd9203d) | Jul 09, 2022 |
| Acer          | Nitro AN515-45              | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | [99172a6e6f](https://linux-hardware.org/?probe=99172a6e6f) | Jul 08, 2022 |
| Dell          | Latitude 5420               | [cb302e010e](https://linux-hardware.org/?probe=cb302e010e) | Jul 08, 2022 |
| HP            | ProBook 4310s               | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| Acer          | Aspire A515-51G             | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| Acer          | Aspire A515-51G             | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| Dell          | Latitude 5521               | [2fda374f06](https://linux-hardware.org/?probe=2fda374f06) | Jun 24, 2022 |
| Dell          | Inspiron 5567               | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [70d6947d54](https://linux-hardware.org/?probe=70d6947d54) | Jun 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [1e88796016](https://linux-hardware.org/?probe=1e88796016) | Jun 15, 2022 |
| Acer          | Aspire One 522              | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| ASUSTek       | K50IJ                       | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Dell          | Latitude E6440              | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| HUAWEI        | KLVL-WXX9                   | [992f232db5](https://linux-hardware.org/?probe=992f232db5) | Jun 08, 2022 |
| Dell          | Latitude D520               | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Prestigio     | PSB141C04CGP                | [4fa2ee47c0](https://linux-hardware.org/?probe=4fa2ee47c0) | Jun 01, 2022 |
| Acer          | Aspire A315-51              | [083e3a354a](https://linux-hardware.org/?probe=083e3a354a) | May 29, 2022 |
| ASUSTek       | N53SM                       | [83209051cb](https://linux-hardware.org/?probe=83209051cb) | May 29, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [74c64ebe72](https://linux-hardware.org/?probe=74c64ebe72) | May 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| ASUSTek       | N53SM                       | [3115570400](https://linux-hardware.org/?probe=3115570400) | May 24, 2022 |
| Allview       | Allbook H                   | [9ea4897c6b](https://linux-hardware.org/?probe=9ea4897c6b) | May 24, 2022 |
| Dell          | Latitude E7470              | [b01633e1ae](https://linux-hardware.org/?probe=b01633e1ae) | May 24, 2022 |
| Dell          | Latitude E7470              | [815dbb114b](https://linux-hardware.org/?probe=815dbb114b) | May 23, 2022 |
| Dell          | Latitude E7470              | [9a6c29a243](https://linux-hardware.org/?probe=9a6c29a243) | May 21, 2022 |
| Acer          | Aspire One 522              | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Dell          | Latitude E6410              | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| Dell          | Inspiron 3542               | [949f8f3e50](https://linux-hardware.org/?probe=949f8f3e50) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [4d2d33c41c](https://linux-hardware.org/?probe=4d2d33c41c) | May 20, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| Lenovo        | ThinkPad P53 20QNS01900     | [158f212b30](https://linux-hardware.org/?probe=158f212b30) | May 13, 2022 |
| Dell          | Inspiron 3542               | [550824d592](https://linux-hardware.org/?probe=550824d592) | May 12, 2022 |
| Dell          | Inspiron 3542               | [324d1abe3b](https://linux-hardware.org/?probe=324d1abe3b) | May 08, 2022 |
| HP            | ProBook 4520s               | [06e044a425](https://linux-hardware.org/?probe=06e044a425) | May 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [52c2a321a4](https://linux-hardware.org/?probe=52c2a321a4) | May 07, 2022 |
| Acer          | Aspire E1-570               | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| HP            | Laptop 14s-dq1xxx           | [713358f855](https://linux-hardware.org/?probe=713358f855) | May 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [6537fb670a](https://linux-hardware.org/?probe=6537fb670a) | May 01, 2022 |
| Toshiba       | Satellite C55-A-1J8         | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| HP            | ProBook 4520s               | [60eab2c6c5](https://linux-hardware.org/?probe=60eab2c6c5) | Apr 30, 2022 |
| Pegatron      | Spring Peak                 | [66a1692171](https://linux-hardware.org/?probe=66a1692171) | Apr 30, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | [efcd6be006](https://linux-hardware.org/?probe=efcd6be006) | Apr 27, 2022 |
| Dell          | Latitude E4310              | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | [afe44fa080](https://linux-hardware.org/?probe=afe44fa080) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8ece944a7b](https://linux-hardware.org/?probe=8ece944a7b) | Apr 27, 2022 |
| Dell          | Latitude E6520              | [1ca407a69f](https://linux-hardware.org/?probe=1ca407a69f) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcc0c7612d](https://linux-hardware.org/?probe=bcc0c7612d) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1EH0... | [fae5ee6551](https://linux-hardware.org/?probe=fae5ee6551) | Apr 26, 2022 |
| Dell          | XPS 17 9710                 | [c7dfc69b32](https://linux-hardware.org/?probe=c7dfc69b32) | Apr 26, 2022 |
| HP            | ProBook 4520s               | [1621eddc70](https://linux-hardware.org/?probe=1621eddc70) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | [41276f12db](https://linux-hardware.org/?probe=41276f12db) | Apr 23, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | [55733b5ae3](https://linux-hardware.org/?probe=55733b5ae3) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [a551ef1ec7](https://linux-hardware.org/?probe=a551ef1ec7) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [fd6718859d](https://linux-hardware.org/?probe=fd6718859d) | Apr 23, 2022 |
| ASUSTek       | X450CP                      | [2518b6daad](https://linux-hardware.org/?probe=2518b6daad) | Apr 22, 2022 |
| ASUSTek       | X450CP                      | [17d51c502f](https://linux-hardware.org/?probe=17d51c502f) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | [de746c72d1](https://linux-hardware.org/?probe=de746c72d1) | Apr 20, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [5d95841f54](https://linux-hardware.org/?probe=5d95841f54) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| ASUSTek       | X541UAK                     | [8b54af493a](https://linux-hardware.org/?probe=8b54af493a) | Apr 19, 2022 |
| Dell          | Latitude E6440              | [33955db41e](https://linux-hardware.org/?probe=33955db41e) | Apr 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1825f45bfa](https://linux-hardware.org/?probe=1825f45bfa) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| HP            | Pavilion 17                 | [acb0c7fd0e](https://linux-hardware.org/?probe=acb0c7fd0e) | Apr 16, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | [a572c901ca](https://linux-hardware.org/?probe=a572c901ca) | Apr 15, 2022 |
| HP            | Pavilion 17                 | [014f42ecee](https://linux-hardware.org/?probe=014f42ecee) | Apr 15, 2022 |
| Acer          | Aspire 5750G                | [73d1368d93](https://linux-hardware.org/?probe=73d1368d93) | Apr 15, 2022 |
| Dell          | System XPS L702X            | [9ed530100f](https://linux-hardware.org/?probe=9ed530100f) | Apr 13, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [95ddaa1dae](https://linux-hardware.org/?probe=95ddaa1dae) | Apr 13, 2022 |
| Dell          | Inspiron 5570               | [ba6f51707b](https://linux-hardware.org/?probe=ba6f51707b) | Apr 13, 2022 |
| HP            | EliteBook 2540p             | [a06e300bfd](https://linux-hardware.org/?probe=a06e300bfd) | Apr 12, 2022 |
| ASUSTek       | X541UAK                     | [ffb5635168](https://linux-hardware.org/?probe=ffb5635168) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Dell          | Vostro 15 3515              | [5fea9b2c3a](https://linux-hardware.org/?probe=5fea9b2c3a) | Apr 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| Lenovo        | G510 20238                  | [beeceac759](https://linux-hardware.org/?probe=beeceac759) | Apr 04, 2022 |
| Lenovo        | B590 37612LG                | [153a6c2343](https://linux-hardware.org/?probe=153a6c2343) | Apr 04, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| HP            | 250 G4                      | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| Acer          | Aspire 5920G                | [c2d3fbb93e](https://linux-hardware.org/?probe=c2d3fbb93e) | Mar 30, 2022 |
| Acer          | Swift SF314-511             | [ffde31bd20](https://linux-hardware.org/?probe=ffde31bd20) | Mar 26, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| Dell          | Inspiron 15-3567            | [2bbea411a6](https://linux-hardware.org/?probe=2bbea411a6) | Mar 24, 2022 |
| Dell          | Inspiron 15-3567            | [c55e29b1e9](https://linux-hardware.org/?probe=c55e29b1e9) | Mar 22, 2022 |
| Gigabyte      | AERO 15 YD                  | [ce6cc28ca1](https://linux-hardware.org/?probe=ce6cc28ca1) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8d1c371df2](https://linux-hardware.org/?probe=8d1c371df2) | Mar 21, 2022 |
| Gigabyte      | AERO 15 YD                  | [35da4bbe2c](https://linux-hardware.org/?probe=35da4bbe2c) | Mar 21, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [626ee37f9b](https://linux-hardware.org/?probe=626ee37f9b) | Mar 21, 2022 |
| Acer          | Swift SF314-57              | [a93c59159d](https://linux-hardware.org/?probe=a93c59159d) | Mar 20, 2022 |
| Acer          | Swift SF514-55GT            | [ae09c5da41](https://linux-hardware.org/?probe=ae09c5da41) | Mar 20, 2022 |
| Acer          | Swift SF114-33              | [7e8098be12](https://linux-hardware.org/?probe=7e8098be12) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [b8b480e048](https://linux-hardware.org/?probe=b8b480e048) | Mar 20, 2022 |
| Dell          | Inspiron 3583               | [a3a8154156](https://linux-hardware.org/?probe=a3a8154156) | Mar 17, 2022 |
| HP            | ProBook 450 G2              | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |
| Dell          | Inspiron 15-3567            | [5da90f10f4](https://linux-hardware.org/?probe=5da90f10f4) | Mar 15, 2022 |
| ASUSTek       | X540YA                      | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| Lenovo        | G510 20238                  | [c82a0d33a2](https://linux-hardware.org/?probe=c82a0d33a2) | Mar 12, 2022 |
| Dell          | Inspiron MM061              | [ad5413d163](https://linux-hardware.org/?probe=ad5413d163) | Mar 06, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [3b3220eeee](https://linux-hardware.org/?probe=3b3220eeee) | Mar 06, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Acer          | Aspire A315-41              | [6d26072b9e](https://linux-hardware.org/?probe=6d26072b9e) | Mar 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [53d74176e9](https://linux-hardware.org/?probe=53d74176e9) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [73881ad12e](https://linux-hardware.org/?probe=73881ad12e) | Mar 03, 2022 |
| MSI           | GP75 Leopard 9SE            | [6090fb66ea](https://linux-hardware.org/?probe=6090fb66ea) | Mar 02, 2022 |
| MSI           | GP75 Leopard 9SE            | [c56a98389f](https://linux-hardware.org/?probe=c56a98389f) | Mar 01, 2022 |
| Medion        | E16402                      | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Acer          | Aspire E1-571               | [c8dd47fb82](https://linux-hardware.org/?probe=c8dd47fb82) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [402a27e190](https://linux-hardware.org/?probe=402a27e190) | Feb 24, 2022 |
| ASUSTek       | X55U                        | [c7c38f077d](https://linux-hardware.org/?probe=c7c38f077d) | Feb 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6083eed5da](https://linux-hardware.org/?probe=6083eed5da) | Feb 21, 2022 |
| Lenovo        | ThinkPad T430 2349U15       | [38a194c33d](https://linux-hardware.org/?probe=38a194c33d) | Feb 20, 2022 |
| Dell          | Latitude E6540              | [dfc7dad0ee](https://linux-hardware.org/?probe=dfc7dad0ee) | Feb 17, 2022 |
| Lenovo        | ThinkPad P50 20ENS0FQ00     | [8d8e30fdfb](https://linux-hardware.org/?probe=8d8e30fdfb) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [5d2de5cd73](https://linux-hardware.org/?probe=5d2de5cd73) | Feb 17, 2022 |
| Acer          | Aspire A315-34              | [f6383e06d7](https://linux-hardware.org/?probe=f6383e06d7) | Feb 16, 2022 |
| MSI           | EX620                       | [8eda01e2a8](https://linux-hardware.org/?probe=8eda01e2a8) | Feb 14, 2022 |
| HP            | EliteBook 8530p             | [6b45115b9e](https://linux-hardware.org/?probe=6b45115b9e) | Feb 13, 2022 |
| Lenovo        | ThinkPad T410 2522Y15       | [66a496ba4c](https://linux-hardware.org/?probe=66a496ba4c) | Feb 09, 2022 |
| Chuwi         | GemiBook Pro                | [7d600bcdc7](https://linux-hardware.org/?probe=7d600bcdc7) | Feb 08, 2022 |
| Lenovo        | ThinkPad L380 20M5003FUK    | [fe486b4de6](https://linux-hardware.org/?probe=fe486b4de6) | Feb 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS3W300    | [a49c14ab70](https://linux-hardware.org/?probe=a49c14ab70) | Feb 06, 2022 |
| Allview       | Allbook H                   | [f1ba3f22c4](https://linux-hardware.org/?probe=f1ba3f22c4) | Feb 05, 2022 |
| Lenovo        | G510 20238                  | [4975c3b6b7](https://linux-hardware.org/?probe=4975c3b6b7) | Feb 05, 2022 |
| HP            | Pavilion dv6                | [63c8ab5447](https://linux-hardware.org/?probe=63c8ab5447) | Feb 03, 2022 |
| HP            | EliteBook x360 1040 G5      | [4aa3aa1f30](https://linux-hardware.org/?probe=4aa3aa1f30) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [1e330f1e0e](https://linux-hardware.org/?probe=1e330f1e0e) | Feb 02, 2022 |
| HP            | Laptop 15s-fq1xxx           | [7c2762f41c](https://linux-hardware.org/?probe=7c2762f41c) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | [2aa45a8d1b](https://linux-hardware.org/?probe=2aa45a8d1b) | Jan 31, 2022 |
| Lenovo        | G510 20238                  | [b61bba90ad](https://linux-hardware.org/?probe=b61bba90ad) | Jan 30, 2022 |
| Acer          | Extensa 2510                | [1fcabc0254](https://linux-hardware.org/?probe=1fcabc0254) | Jan 26, 2022 |
| Lenovo        | V330-15IKB 81AX             | [3bcb1d5f53](https://linux-hardware.org/?probe=3bcb1d5f53) | Jan 25, 2022 |
| HP            | Pavilion TS 11              | [6d62bb9596](https://linux-hardware.org/?probe=6d62bb9596) | Jan 24, 2022 |
| Dell          | Inspiron 5567               | [0e47f03d64](https://linux-hardware.org/?probe=0e47f03d64) | Jan 24, 2022 |
| HP            | EliteBook 840 G6            | [ded9015aff](https://linux-hardware.org/?probe=ded9015aff) | Jan 23, 2022 |
| Acer          | Aspire E1-531               | [d90de3e8f7](https://linux-hardware.org/?probe=d90de3e8f7) | Jan 21, 2022 |
| HP            | Pavilion TS 11              | [d4187f35fd](https://linux-hardware.org/?probe=d4187f35fd) | Jan 19, 2022 |
| ASUSTek       | X541UAK                     | [2f55e0a142](https://linux-hardware.org/?probe=2f55e0a142) | Jan 19, 2022 |
| Dell          | MXG071                      | [cd914ee2f0](https://linux-hardware.org/?probe=cd914ee2f0) | Jan 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell          | Inspiron 5567               | [4b51693e30](https://linux-hardware.org/?probe=4b51693e30) | Jan 17, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| Samsung       | R580/R590                   | [be1e77de84](https://linux-hardware.org/?probe=be1e77de84) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | [342f6f2beb](https://linux-hardware.org/?probe=342f6f2beb) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | [34f103b8d2](https://linux-hardware.org/?probe=34f103b8d2) | Jan 16, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [efe75d8f3f](https://linux-hardware.org/?probe=efe75d8f3f) | Jan 14, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | [15dd95fdfd](https://linux-hardware.org/?probe=15dd95fdfd) | Jan 14, 2022 |
| Lenovo        | G50-70 20351                | [615ed31a98](https://linux-hardware.org/?probe=615ed31a98) | Jan 13, 2022 |
| Dell          | Inspiron 5570               | [5f41c8e050](https://linux-hardware.org/?probe=5f41c8e050) | Jan 12, 2022 |
| HP            | ProBook 450 G2              | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [56d6ea164b](https://linux-hardware.org/?probe=56d6ea164b) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d9bd1bab23](https://linux-hardware.org/?probe=d9bd1bab23) | Jan 09, 2022 |
| ASUSTek       | X541UAK                     | [353534e82a](https://linux-hardware.org/?probe=353534e82a) | Jan 08, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [ba78c8aef3](https://linux-hardware.org/?probe=ba78c8aef3) | Jan 07, 2022 |
| Hungaro Fl... | Navon Loop 360              | [3e7d72e09a](https://linux-hardware.org/?probe=3e7d72e09a) | Jan 06, 2022 |
| Chuwi         | Hero Book                   | [b111f44fad](https://linux-hardware.org/?probe=b111f44fad) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| ASUSTek       | X550VL                      | [46ed51f6ef](https://linux-hardware.org/?probe=46ed51f6ef) | Jan 04, 2022 |
| MSI           | Prestige 15 A10SC           | [0132076c85](https://linux-hardware.org/?probe=0132076c85) | Jan 04, 2022 |
| ASUSTek       | X550VX                      | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291B78       | [76350af57f](https://linux-hardware.org/?probe=76350af57f) | Jan 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a7217db810](https://linux-hardware.org/?probe=a7217db810) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [286ce69daf](https://linux-hardware.org/?probe=286ce69daf) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [f5eafcc9e4](https://linux-hardware.org/?probe=f5eafcc9e4) | Jan 02, 2022 |
| HP            | Laptop 15-da0xxx            | [50a5dc78eb](https://linux-hardware.org/?probe=50a5dc78eb) | Jan 02, 2022 |
| MSI           | EX705                       | [a969bd4369](https://linux-hardware.org/?probe=a969bd4369) | Dec 31, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [64743b9e56](https://linux-hardware.org/?probe=64743b9e56) | Dec 30, 2021 |
| MSI           | GP75 Leopard 9SE            | [af923f06cc](https://linux-hardware.org/?probe=af923f06cc) | Dec 29, 2021 |
| Dell          | Latitude E5420m             | [6f5af5da5c](https://linux-hardware.org/?probe=6f5af5da5c) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | [a7a37c26c7](https://linux-hardware.org/?probe=a7a37c26c7) | Dec 29, 2021 |
| Dream Mach... | NH5x_NH7x_HHx_HJx_HKx       | [c3f88b03df](https://linux-hardware.org/?probe=c3f88b03df) | Dec 28, 2021 |
| HP            | EliteBook 850 G2            | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b2b9ea9e60](https://linux-hardware.org/?probe=b2b9ea9e60) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 4291B78       | [2c8a912b3e](https://linux-hardware.org/?probe=2c8a912b3e) | Dec 24, 2021 |
| HP            | EliteBook 850 G2            | [e4dc4b8711](https://linux-hardware.org/?probe=e4dc4b8711) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| Acer          | Aspire A315-41              | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [6748ebc68a](https://linux-hardware.org/?probe=6748ebc68a) | Dec 20, 2021 |
| MSI           | Modern 14 B5M               | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [00868d9166](https://linux-hardware.org/?probe=00868d9166) | Dec 17, 2021 |
| Timi          | TM1701                      | [f063712cce](https://linux-hardware.org/?probe=f063712cce) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ac40d89d27](https://linux-hardware.org/?probe=ac40d89d27) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [7da5a1020d](https://linux-hardware.org/?probe=7da5a1020d) | Dec 15, 2021 |
| Chuwi         | Hero Book                   | [27e37e5a15](https://linux-hardware.org/?probe=27e37e5a15) | Dec 14, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [85770fb8f5](https://linux-hardware.org/?probe=85770fb8f5) | Dec 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | [b68de5799e](https://linux-hardware.org/?probe=b68de5799e) | Dec 12, 2021 |
| MSI           | Modern 14 B4MW              | [5d06e53d08](https://linux-hardware.org/?probe=5d06e53d08) | Dec 12, 2021 |
| ASUSTek       | X550LD                      | [5be7aac3a2](https://linux-hardware.org/?probe=5be7aac3a2) | Dec 09, 2021 |
| Hungaro Fl... | Navon Loop 360              | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [98f25277f5](https://linux-hardware.org/?probe=98f25277f5) | Dec 08, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [902395fcce](https://linux-hardware.org/?probe=902395fcce) | Dec 03, 2021 |
| HP            | ZBook 15 G5                 | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| Lenovo        | G510 20238                  | [d3040ac7d5](https://linux-hardware.org/?probe=d3040ac7d5) | Nov 30, 2021 |
| Allview       | Allbook J                   | [957074dbe3](https://linux-hardware.org/?probe=957074dbe3) | Nov 30, 2021 |
| Sony          | SVE1713Y1EB                 | [317b686b33](https://linux-hardware.org/?probe=317b686b33) | Nov 29, 2021 |
| Dell          | Vostro 3500                 | [c323b490bf](https://linux-hardware.org/?probe=c323b490bf) | Nov 26, 2021 |
| ASUSTek       | K53SD                       | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| Sony          | SVE1713Y1EB                 | [755b7b85f5](https://linux-hardware.org/?probe=755b7b85f5) | Nov 24, 2021 |
| Medion        | E7218                       | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| HP            | Compaq 2510p                | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [eb7191f8cb](https://linux-hardware.org/?probe=eb7191f8cb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [1169bef865](https://linux-hardware.org/?probe=1169bef865) | Nov 22, 2021 |
| HP            | Compaq 2510p                | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bb48a45349](https://linux-hardware.org/?probe=bb48a45349) | Nov 22, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| Acer          | Aspire E1-531               | [9a83e53e34](https://linux-hardware.org/?probe=9a83e53e34) | Nov 22, 2021 |
| ASUSTek       | X450CP                      | [7228a5157c](https://linux-hardware.org/?probe=7228a5157c) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [04fa536869](https://linux-hardware.org/?probe=04fa536869) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [097de81570](https://linux-hardware.org/?probe=097de81570) | Nov 20, 2021 |
| Sony          | SVE1713Y1EB                 | [4a77a751d9](https://linux-hardware.org/?probe=4a77a751d9) | Nov 20, 2021 |
| Dell          | Latitude 7410               | [226f912726](https://linux-hardware.org/?probe=226f912726) | Nov 18, 2021 |
| ASUSTek       | K53U                        | [8b542e61d9](https://linux-hardware.org/?probe=8b542e61d9) | Nov 18, 2021 |
| Dell          | Latitude E7470              | [0358863974](https://linux-hardware.org/?probe=0358863974) | Nov 16, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [6677eae4da](https://linux-hardware.org/?probe=6677eae4da) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| ASUSTek       | X540SA                      | [1292ab6f15](https://linux-hardware.org/?probe=1292ab6f15) | Nov 14, 2021 |
| Dell          | Latitude E6410              | [1a31fa8433](https://linux-hardware.org/?probe=1a31fa8433) | Nov 13, 2021 |
| ASUSTek       | X540SA                      | [463e1f35a9](https://linux-hardware.org/?probe=463e1f35a9) | Nov 13, 2021 |
| Sony          | SVF14N1E2ES                 | [a04441e5cd](https://linux-hardware.org/?probe=a04441e5cd) | Nov 13, 2021 |
| Dell          | Precision 3541              | [8f6085ab9d](https://linux-hardware.org/?probe=8f6085ab9d) | Nov 12, 2021 |
| Packard Be... | EasyNote TN36               | [17ebc64721](https://linux-hardware.org/?probe=17ebc64721) | Nov 11, 2021 |
| Dell          | XPS 13 9350                 | [e70882b3fd](https://linux-hardware.org/?probe=e70882b3fd) | Nov 11, 2021 |
| Notebook      | N85_N87HCHNHZ               | [32988fae95](https://linux-hardware.org/?probe=32988fae95) | Nov 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [b79aef683b](https://linux-hardware.org/?probe=b79aef683b) | Nov 11, 2021 |
| HP            | EliteBook 850 G2            | [c1bd9abdd2](https://linux-hardware.org/?probe=c1bd9abdd2) | Nov 03, 2021 |
| Dell          | G3 3579                     | [f9fdeb003b](https://linux-hardware.org/?probe=f9fdeb003b) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8cdb34dbc8](https://linux-hardware.org/?probe=8cdb34dbc8) | Nov 01, 2021 |
| Lenovo        | ThinkPad T430 2349U15       | [c9d8efc9b9](https://linux-hardware.org/?probe=c9d8efc9b9) | Oct 31, 2021 |
| Lenovo        | G510 20238                  | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| Dell          | Latitude E5450              | [fb61a77e5c](https://linux-hardware.org/?probe=fb61a77e5c) | Oct 26, 2021 |
| Lenovo        | ThinkPad X230 2325SWF       | [64f9882936](https://linux-hardware.org/?probe=64f9882936) | Oct 25, 2021 |
| Apple         | MacBookPro14,3              | [69a5d79a58](https://linux-hardware.org/?probe=69a5d79a58) | Oct 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [9b3e361eb7](https://linux-hardware.org/?probe=9b3e361eb7) | Oct 24, 2021 |
| Dell          | Latitude E7470              | [69a251cc1f](https://linux-hardware.org/?probe=69a251cc1f) | Oct 22, 2021 |
| Dell          | Latitude E7470              | [96ef0ee68c](https://linux-hardware.org/?probe=96ef0ee68c) | Oct 22, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [21379aad70](https://linux-hardware.org/?probe=21379aad70) | Oct 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f0c049fc34](https://linux-hardware.org/?probe=f0c049fc34) | Oct 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d550d04ac7](https://linux-hardware.org/?probe=d550d04ac7) | Oct 20, 2021 |
| HUAWEI        | MACHD-WXX9                  | [8563f3786e](https://linux-hardware.org/?probe=8563f3786e) | Oct 19, 2021 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [ac37b3fd23](https://linux-hardware.org/?probe=ac37b3fd23) | Oct 18, 2021 |
| MSI           | GE66 Raider 11UH            | [cbf3c67be2](https://linux-hardware.org/?probe=cbf3c67be2) | Oct 18, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [cc0290a8df](https://linux-hardware.org/?probe=cc0290a8df) | Oct 18, 2021 |
| MSI           | GE66 Raider 11UH            | [0b2123c367](https://linux-hardware.org/?probe=0b2123c367) | Oct 16, 2021 |
| Dell          | Latitude E7470              | [3bbcb85b9f](https://linux-hardware.org/?probe=3bbcb85b9f) | Oct 16, 2021 |
| HP            | 255 G7 Notebook PC          | [28930b356e](https://linux-hardware.org/?probe=28930b356e) | Oct 16, 2021 |
| Sony          | SVE1713Y1EB                 | [b59de957b3](https://linux-hardware.org/?probe=b59de957b3) | Oct 11, 2021 |
| Sony          | SVE1713Y1EB                 | [a427a26f34](https://linux-hardware.org/?probe=a427a26f34) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1965a71536](https://linux-hardware.org/?probe=1965a71536) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6166a72ec2](https://linux-hardware.org/?probe=6166a72ec2) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [0acb396573](https://linux-hardware.org/?probe=0acb396573) | Oct 11, 2021 |
| Acer          | Aspire 5741G                | [ea162f9171](https://linux-hardware.org/?probe=ea162f9171) | Oct 10, 2021 |
| Acer          | Aspire A315-51              | [d79188a009](https://linux-hardware.org/?probe=d79188a009) | Oct 10, 2021 |
| Acer          | Aspire A315-51              | [aae51881da](https://linux-hardware.org/?probe=aae51881da) | Oct 10, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [efb88027ec](https://linux-hardware.org/?probe=efb88027ec) | Oct 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [2236b91c55](https://linux-hardware.org/?probe=2236b91c55) | Oct 05, 2021 |
| HP            | EliteBook 8770w             | [d23574ecf1](https://linux-hardware.org/?probe=d23574ecf1) | Oct 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [2f89b6fcf1](https://linux-hardware.org/?probe=2f89b6fcf1) | Oct 03, 2021 |
| Lenovo        | ThinkPad T470 20HES0FA02    | [b368193a4e](https://linux-hardware.org/?probe=b368193a4e) | Oct 02, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [032d34e75b](https://linux-hardware.org/?probe=032d34e75b) | Sep 28, 2021 |
| Acer          | Aspire A315-42              | [3cbca1757f](https://linux-hardware.org/?probe=3cbca1757f) | Sep 26, 2021 |
| Alienware     | 17 R2                       | [cbe7430492](https://linux-hardware.org/?probe=cbe7430492) | Sep 26, 2021 |
| ASUSTek       | FX503VD                     | [c91cad59c2](https://linux-hardware.org/?probe=c91cad59c2) | Sep 25, 2021 |
| Acer          | Aspire 5715Z                | [a44995aac4](https://linux-hardware.org/?probe=a44995aac4) | Sep 25, 2021 |
| HP            | Pavilion dv6                | [a97e17fc48](https://linux-hardware.org/?probe=a97e17fc48) | Sep 25, 2021 |
| HP            | EliteBook 8530p             | [8002401481](https://linux-hardware.org/?probe=8002401481) | Sep 23, 2021 |
| HP            | Pavilion dv6                | [72f179ec58](https://linux-hardware.org/?probe=72f179ec58) | Sep 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [f6dfc42935](https://linux-hardware.org/?probe=f6dfc42935) | Sep 22, 2021 |
| ASUSTek       | UX550VE                     | [72925fef5d](https://linux-hardware.org/?probe=72925fef5d) | Sep 21, 2021 |
| ASUSTek       | GL752VW                     | [ec4b89fd42](https://linux-hardware.org/?probe=ec4b89fd42) | Sep 20, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [75c71d1f1e](https://linux-hardware.org/?probe=75c71d1f1e) | Sep 20, 2021 |
| Acer          | Aspire A515-56              | [7b95b06b4d](https://linux-hardware.org/?probe=7b95b06b4d) | Sep 20, 2021 |
| Dell          | Inspiron 1564               | [3a0a2208fb](https://linux-hardware.org/?probe=3a0a2208fb) | Sep 20, 2021 |
| ASUSTek       | X540YA                      | [c0b5da7979](https://linux-hardware.org/?probe=c0b5da7979) | Sep 19, 2021 |
| Acer          | AOA110                      | [a54c248743](https://linux-hardware.org/?probe=a54c248743) | Sep 19, 2021 |
| HP            | Pavilion dv6                | [b4d25f6f3a](https://linux-hardware.org/?probe=b4d25f6f3a) | Sep 19, 2021 |
| Sony          | VGN-CR21Z_N                 | [6fc19f4c67](https://linux-hardware.org/?probe=6fc19f4c67) | Sep 19, 2021 |
| Dell          | Inspiron 1564               | [252914c6d3](https://linux-hardware.org/?probe=252914c6d3) | Sep 16, 2021 |
| Dell          | Inspiron 7537               | [1493a2eae1](https://linux-hardware.org/?probe=1493a2eae1) | Sep 15, 2021 |
| Toshiba       | Satellite C55-C             | [8966b3a7b5](https://linux-hardware.org/?probe=8966b3a7b5) | Sep 14, 2021 |
| HP            | EliteBook 840 G4            | [8bd6acee77](https://linux-hardware.org/?probe=8bd6acee77) | Sep 13, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [bc6963f758](https://linux-hardware.org/?probe=bc6963f758) | Sep 11, 2021 |
| Packard Be... | EasyNote MV86               | [ea018cddf2](https://linux-hardware.org/?probe=ea018cddf2) | Sep 10, 2021 |
| Dell          | Inspiron 5520               | [835f9cb8a1](https://linux-hardware.org/?probe=835f9cb8a1) | Sep 07, 2021 |
| Dell          | Latitude 7410               | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell          | Latitude 7410               | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo        | G50-70 20351                | [576b96b6da](https://linux-hardware.org/?probe=576b96b6da) | Sep 06, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [47c2053681](https://linux-hardware.org/?probe=47c2053681) | Sep 02, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [4765b87a68](https://linux-hardware.org/?probe=4765b87a68) | Sep 01, 2021 |
| ASUSTek       | K52F                        | [743e5c8059](https://linux-hardware.org/?probe=743e5c8059) | Sep 01, 2021 |
| ASUSTek       | K52F                        | [54d5076bc6](https://linux-hardware.org/?probe=54d5076bc6) | Sep 01, 2021 |
| ASUSTek       | UX550VE                     | [cd80e1ebb2](https://linux-hardware.org/?probe=cd80e1ebb2) | Aug 31, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [c2b7f1ee7c](https://linux-hardware.org/?probe=c2b7f1ee7c) | Aug 30, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [301be6f800](https://linux-hardware.org/?probe=301be6f800) | Aug 30, 2021 |
| MSI           | MS-16Y1                     | [a9801b616e](https://linux-hardware.org/?probe=a9801b616e) | Aug 29, 2021 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [0a9f1f10d8](https://linux-hardware.org/?probe=0a9f1f10d8) | Aug 29, 2021 |
| ASUSTek       | X450CP                      | [d646ffd8db](https://linux-hardware.org/?probe=d646ffd8db) | Aug 29, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | [954900ccc6](https://linux-hardware.org/?probe=954900ccc6) | Aug 28, 2021 |
| Acer          | Aspire 5750G                | [03a89677c0](https://linux-hardware.org/?probe=03a89677c0) | Aug 26, 2021 |
| HP            | Presario CQ57               | [4b863ffc87](https://linux-hardware.org/?probe=4b863ffc87) | Aug 25, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f534340eab](https://linux-hardware.org/?probe=f534340eab) | Aug 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4f6bd2a75e](https://linux-hardware.org/?probe=4f6bd2a75e) | Aug 22, 2021 |
| HP            | Presario CQ57               | [a45389ec74](https://linux-hardware.org/?probe=a45389ec74) | Aug 21, 2021 |
| Dell          | Inspiron 5558               | [eb664f1a19](https://linux-hardware.org/?probe=eb664f1a19) | Aug 20, 2021 |
| ASUSTek       | N53SM                       | [cf9c1726af](https://linux-hardware.org/?probe=cf9c1726af) | Aug 19, 2021 |
| HP            | Pavilion dv6                | [40cd012d76](https://linux-hardware.org/?probe=40cd012d76) | Aug 18, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7465dcb16d](https://linux-hardware.org/?probe=7465dcb16d) | Aug 17, 2021 |
| HP            | Pavilion dv6                | [8bf5049adc](https://linux-hardware.org/?probe=8bf5049adc) | Aug 17, 2021 |
| HP            | Pavilion dv6                | [92e25a1c2c](https://linux-hardware.org/?probe=92e25a1c2c) | Aug 15, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [f3506aaa1c](https://linux-hardware.org/?probe=f3506aaa1c) | Aug 14, 2021 |
| HP            | 630                         | [eda8d23dba](https://linux-hardware.org/?probe=eda8d23dba) | Aug 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [c8b1a45676](https://linux-hardware.org/?probe=c8b1a45676) | Aug 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [20a828b938](https://linux-hardware.org/?probe=20a828b938) | Aug 11, 2021 |
| ASUSTek       | X550JX                      | [da2cacc763](https://linux-hardware.org/?probe=da2cacc763) | Aug 11, 2021 |
| Dell          | Inspiron 1564               | [86ab410358](https://linux-hardware.org/?probe=86ab410358) | Aug 10, 2021 |
| Dell          | Inspiron 1564               | [d7ad85015d](https://linux-hardware.org/?probe=d7ad85015d) | Aug 10, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [1a6e7a1825](https://linux-hardware.org/?probe=1a6e7a1825) | Aug 04, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [462a00dded](https://linux-hardware.org/?probe=462a00dded) | Aug 02, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [5f2773a82c](https://linux-hardware.org/?probe=5f2773a82c) | Aug 02, 2021 |
| HP            | 15                          | [715128c8f0](https://linux-hardware.org/?probe=715128c8f0) | Jul 31, 2021 |
| Toshiba       | Satellite Z30-B             | [af9632e99f](https://linux-hardware.org/?probe=af9632e99f) | Jul 30, 2021 |
| Lenovo        | ThinkPad T410 2537CJ0       | [3722a27c42](https://linux-hardware.org/?probe=3722a27c42) | Jul 28, 2021 |
| HP            | Laptop 15s-eq1xxx           | [f448eea5b9](https://linux-hardware.org/?probe=f448eea5b9) | Jul 27, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [7fa1d5f6ab](https://linux-hardware.org/?probe=7fa1d5f6ab) | Jul 24, 2021 |
| Toshiba       | Satellite C660D             | [039468c7c5](https://linux-hardware.org/?probe=039468c7c5) | Jul 18, 2021 |
| ASUSTek       | X406UAR                     | [f50ab25a97](https://linux-hardware.org/?probe=f50ab25a97) | Jul 17, 2021 |
| ASUSTek       | X406UAR                     | [594955a00b](https://linux-hardware.org/?probe=594955a00b) | Jul 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e2c9b58e23](https://linux-hardware.org/?probe=e2c9b58e23) | Jul 17, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [14ce128e1a](https://linux-hardware.org/?probe=14ce128e1a) | Jul 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f656b6c149](https://linux-hardware.org/?probe=f656b6c149) | Jul 16, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d1105aa53f](https://linux-hardware.org/?probe=d1105aa53f) | Jul 16, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [14b9ddda83](https://linux-hardware.org/?probe=14b9ddda83) | Jul 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [876c8173d3](https://linux-hardware.org/?probe=876c8173d3) | Jul 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f9d7bd513c](https://linux-hardware.org/?probe=f9d7bd513c) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c9c8fdd393](https://linux-hardware.org/?probe=c9c8fdd393) | Jul 11, 2021 |
| HP            | ProBook 4330s               | [64030992e8](https://linux-hardware.org/?probe=64030992e8) | Jul 08, 2021 |
| Dell          | System XPS L502X            | [c384fff091](https://linux-hardware.org/?probe=c384fff091) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | [6aa95f6599](https://linux-hardware.org/?probe=6aa95f6599) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | [2a2e03aaa8](https://linux-hardware.org/?probe=2a2e03aaa8) | Jul 08, 2021 |
| HP            | EliteBook 8540p             | [d09c65051f](https://linux-hardware.org/?probe=d09c65051f) | Jul 06, 2021 |
| Lenovo        | ThinkPad T470p 20J7S1860... | [6b3e194f93](https://linux-hardware.org/?probe=6b3e194f93) | Jul 06, 2021 |
| Allview       | Allbook H                   | [ac0835f4f5](https://linux-hardware.org/?probe=ac0835f4f5) | Jul 06, 2021 |
| HP            | EliteBook 8560w             | [e609104d2c](https://linux-hardware.org/?probe=e609104d2c) | Jul 06, 2021 |
| HP            | EliteBook 8560w             | [f3ac1ba96d](https://linux-hardware.org/?probe=f3ac1ba96d) | Jul 06, 2021 |
| Lenovo        | B50-80 80EW                 | [b35369b2b3](https://linux-hardware.org/?probe=b35369b2b3) | Jul 03, 2021 |
| Dell          | XPS L501X                   | [27ed8f445a](https://linux-hardware.org/?probe=27ed8f445a) | Jul 03, 2021 |
| HP            | ProBook 450 G1              | [9b296f3c9c](https://linux-hardware.org/?probe=9b296f3c9c) | Jul 03, 2021 |
| HP            | 15                          | [b435e6f220](https://linux-hardware.org/?probe=b435e6f220) | Jul 02, 2021 |
| Toshiba       | Satellite C660D             | [fdbefe0e71](https://linux-hardware.org/?probe=fdbefe0e71) | Jul 01, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| HUAWEI        | KLVL-WXX9                   | [a8f90b8625](https://linux-hardware.org/?probe=a8f90b8625) | Jun 30, 2021 |
| ASUSTek       | X751LJ                      | [8a67af6b70](https://linux-hardware.org/?probe=8a67af6b70) | Jun 30, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [21e0e9dda8](https://linux-hardware.org/?probe=21e0e9dda8) | Jun 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4a3a417531](https://linux-hardware.org/?probe=4a3a417531) | Jun 28, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [14b760d760](https://linux-hardware.org/?probe=14b760d760) | Jun 28, 2021 |
| ASUSTek       | X751LJ                      | [d4314245a2](https://linux-hardware.org/?probe=d4314245a2) | Jun 28, 2021 |
| HP            | InsydeH2O EFI BIOS          | [83b0ff67dd](https://linux-hardware.org/?probe=83b0ff67dd) | Jun 28, 2021 |
| HP            | EliteBook 2530p             | [7a20aa2c3b](https://linux-hardware.org/?probe=7a20aa2c3b) | Jun 27, 2021 |
| Allview       | Allbook H                   | [02832b0883](https://linux-hardware.org/?probe=02832b0883) | Jun 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a6c3875064](https://linux-hardware.org/?probe=a6c3875064) | Jun 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [3fabc021d6](https://linux-hardware.org/?probe=3fabc021d6) | Jun 25, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [f19497e31d](https://linux-hardware.org/?probe=f19497e31d) | Jun 22, 2021 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [07cc916c5e](https://linux-hardware.org/?probe=07cc916c5e) | Jun 21, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | [7bc2410a2a](https://linux-hardware.org/?probe=7bc2410a2a) | Jun 20, 2021 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [368b96ef78](https://linux-hardware.org/?probe=368b96ef78) | Jun 20, 2021 |
| HP            | 255 G4                      | [3a4a67761f](https://linux-hardware.org/?probe=3a4a67761f) | Jun 19, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [5ed8c507ef](https://linux-hardware.org/?probe=5ed8c507ef) | Jun 18, 2021 |
| Dell          | Precision M6600             | [3ba95fa890](https://linux-hardware.org/?probe=3ba95fa890) | Jun 18, 2021 |
| Dell          | Inspiron 3593               | [ba202e6f1e](https://linux-hardware.org/?probe=ba202e6f1e) | Jun 17, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [01666caf41](https://linux-hardware.org/?probe=01666caf41) | Jun 16, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [ef3ce7621e](https://linux-hardware.org/?probe=ef3ce7621e) | Jun 13, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [86c9df0816](https://linux-hardware.org/?probe=86c9df0816) | Jun 12, 2021 |
| Dell          | XPS L501X                   | [53b5e4986f](https://linux-hardware.org/?probe=53b5e4986f) | Jun 10, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | [5a8e01e79d](https://linux-hardware.org/?probe=5a8e01e79d) | Jun 05, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | [98c6853a46](https://linux-hardware.org/?probe=98c6853a46) | Jun 05, 2021 |
| Lenovo        | ThinkPad T440 20B7A04RGE    | [5b0de3fa72](https://linux-hardware.org/?probe=5b0de3fa72) | Jun 04, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| Packard Be... | EasyNote MV86               | [c393f3c880](https://linux-hardware.org/?probe=c393f3c880) | Jun 03, 2021 |
| Lenovo        | G550 20023                  | [a962a76b58](https://linux-hardware.org/?probe=a962a76b58) | Jun 01, 2021 |
| Lenovo        | G550 20023                  | [1bbec614aa](https://linux-hardware.org/?probe=1bbec614aa) | May 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [6aff8771b1](https://linux-hardware.org/?probe=6aff8771b1) | May 30, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b63698a4af](https://linux-hardware.org/?probe=b63698a4af) | May 29, 2021 |
| Lenovo        | G510 20238                  | [7fb630f632](https://linux-hardware.org/?probe=7fb630f632) | May 26, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [b251de2587](https://linux-hardware.org/?probe=b251de2587) | May 26, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [3ff174d668](https://linux-hardware.org/?probe=3ff174d668) | May 26, 2021 |
| ASUSTek       | X555LN                      | [7baba93fdf](https://linux-hardware.org/?probe=7baba93fdf) | May 25, 2021 |
| HP            | ZBook Studio G5             | [522583da69](https://linux-hardware.org/?probe=522583da69) | May 25, 2021 |
| Dell          | Latitude D630               | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| HP            | ENVY Laptop 15-ep0xxx       | [02d50458ce](https://linux-hardware.org/?probe=02d50458ce) | May 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8fe5ffb1cc](https://linux-hardware.org/?probe=8fe5ffb1cc) | May 21, 2021 |
| HP            | Laptop 15s-fq1xxx           | [1c24b50a75](https://linux-hardware.org/?probe=1c24b50a75) | May 20, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [32546ecaa0](https://linux-hardware.org/?probe=32546ecaa0) | May 17, 2021 |
| ASUSTek       | X541NA                      | [9f12330c51](https://linux-hardware.org/?probe=9f12330c51) | May 15, 2021 |
| HP            | Laptop 15s-fq1xxx           | [86b562f999](https://linux-hardware.org/?probe=86b562f999) | May 14, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [18ca89b617](https://linux-hardware.org/?probe=18ca89b617) | May 11, 2021 |
| ASUSTek       | X541NA                      | [7a0e366273](https://linux-hardware.org/?probe=7a0e366273) | May 09, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [1809630187](https://linux-hardware.org/?probe=1809630187) | May 09, 2021 |
| HP            | Laptop 15s-eq0xxx           | [d4cf6a320b](https://linux-hardware.org/?probe=d4cf6a320b) | May 07, 2021 |
| Dell          | Latitude E7470              | [c854d464d4](https://linux-hardware.org/?probe=c854d464d4) | May 07, 2021 |
| Toshiba       | Satellite Pro U200          | [ea94c20118](https://linux-hardware.org/?probe=ea94c20118) | May 06, 2021 |
| Acer          | Aspire E1-571               | [8770317d57](https://linux-hardware.org/?probe=8770317d57) | May 06, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [6367a7db0a](https://linux-hardware.org/?probe=6367a7db0a) | May 06, 2021 |
| Toshiba       | Satellite Pro U200          | [1442c68bc8](https://linux-hardware.org/?probe=1442c68bc8) | May 05, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f90ca57fa0](https://linux-hardware.org/?probe=f90ca57fa0) | May 04, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | ThinkPad T61 7659W1W        | [c366a3e7a2](https://linux-hardware.org/?probe=c366a3e7a2) | May 01, 2021 |
| Dell          | Latitude E7470              | [b4d85c0e7c](https://linux-hardware.org/?probe=b4d85c0e7c) | May 01, 2021 |
| Dell          | Latitude E7470              | [1e60f8c14a](https://linux-hardware.org/?probe=1e60f8c14a) | May 01, 2021 |
| Dell          | Latitude E6430              | [4ba28d9505](https://linux-hardware.org/?probe=4ba28d9505) | May 01, 2021 |
| ASUSTek       | X541UAK                     | [d0c8d6944c](https://linux-hardware.org/?probe=d0c8d6944c) | Apr 30, 2021 |
| Acer          | Aspire E5-573G              | [a72228a343](https://linux-hardware.org/?probe=a72228a343) | Apr 29, 2021 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [4dfa28cef5](https://linux-hardware.org/?probe=4dfa28cef5) | Apr 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| ASUSTek       | X541UAK                     | [d5a5a8496d](https://linux-hardware.org/?probe=d5a5a8496d) | Apr 23, 2021 |
| HP            | G62                         | [d728a70b0b](https://linux-hardware.org/?probe=d728a70b0b) | Apr 23, 2021 |
| ASUSTek       | GL552VX                     | [294a96afbb](https://linux-hardware.org/?probe=294a96afbb) | Apr 22, 2021 |
| ASUSTek       | GL552VX                     | [534b39dba5](https://linux-hardware.org/?probe=534b39dba5) | Apr 22, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [1c206551a3](https://linux-hardware.org/?probe=1c206551a3) | Apr 22, 2021 |
| ASUSTek       | X541UAK                     | [83c7d6b0a2](https://linux-hardware.org/?probe=83c7d6b0a2) | Apr 22, 2021 |
| Lenovo        | ThinkPad E560 20EV003AUK    | [3f10db447f](https://linux-hardware.org/?probe=3f10db447f) | Apr 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [3feeb55814](https://linux-hardware.org/?probe=3feeb55814) | Apr 20, 2021 |
| Acer          | Swift SF114-33              | [b91839a518](https://linux-hardware.org/?probe=b91839a518) | Apr 19, 2021 |
| HP            | ZBook Studio G7 Mobile W... | [22d879f5ea](https://linux-hardware.org/?probe=22d879f5ea) | Apr 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8b5a5a31fb](https://linux-hardware.org/?probe=8b5a5a31fb) | Apr 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d6b88752a0](https://linux-hardware.org/?probe=d6b88752a0) | Apr 12, 2021 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | [d2d3020f8b](https://linux-hardware.org/?probe=d2d3020f8b) | Apr 12, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [082fe11ffb](https://linux-hardware.org/?probe=082fe11ffb) | Apr 12, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [2e69cf4f5a](https://linux-hardware.org/?probe=2e69cf4f5a) | Apr 12, 2021 |
| Dell          | Latitude E6410              | [9fc394df40](https://linux-hardware.org/?probe=9fc394df40) | Apr 10, 2021 |
| ASUSTek       | X541UAK                     | [79528a1998](https://linux-hardware.org/?probe=79528a1998) | Apr 09, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [7730367108](https://linux-hardware.org/?probe=7730367108) | Apr 08, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [949f9eb773](https://linux-hardware.org/?probe=949f9eb773) | Apr 06, 2021 |
| Dell          | Vostro 3550                 | [af302c8ef5](https://linux-hardware.org/?probe=af302c8ef5) | Apr 05, 2021 |
| HP            | G62                         | [b706770f8d](https://linux-hardware.org/?probe=b706770f8d) | Apr 05, 2021 |
| Dell          | XPS 15 7590                 | [4b5d46fe3a](https://linux-hardware.org/?probe=4b5d46fe3a) | Apr 03, 2021 |
| Dell          | Latitude E6410              | [297aaeb4ac](https://linux-hardware.org/?probe=297aaeb4ac) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | [f66cd74385](https://linux-hardware.org/?probe=f66cd74385) | Apr 03, 2021 |
| ASUSTek       | X541UAK                     | [11d853a6cd](https://linux-hardware.org/?probe=11d853a6cd) | Apr 03, 2021 |
| Lenovo        | G710 20252                  | [a97fe90c04](https://linux-hardware.org/?probe=a97fe90c04) | Apr 03, 2021 |
| Samsung       | 300V3Z/300V4Z/300V5Z/200... | [51ed7ce2e8](https://linux-hardware.org/?probe=51ed7ce2e8) | Apr 03, 2021 |
| Samsung       | 300V3Z/300V4Z/300V5Z/200... | [a3bd82613b](https://linux-hardware.org/?probe=a3bd82613b) | Apr 03, 2021 |
| Fujitsu       | LIFEBOOK NH751              | [27bf374b6e](https://linux-hardware.org/?probe=27bf374b6e) | Apr 01, 2021 |
| Fujitsu       | LIFEBOOK NH751              | [24b8bc435b](https://linux-hardware.org/?probe=24b8bc435b) | Apr 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [c3bc72bfce](https://linux-hardware.org/?probe=c3bc72bfce) | Mar 29, 2021 |
| Lenovo        | ThinkPad T480s 20L7001LR... | [440edfbe7e](https://linux-hardware.org/?probe=440edfbe7e) | Mar 26, 2021 |
| HP            | OMEN by Laptop 15-dh0xxx    | [3fe5519929](https://linux-hardware.org/?probe=3fe5519929) | Mar 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [3d13dd330c](https://linux-hardware.org/?probe=3d13dd330c) | Mar 25, 2021 |
| ASUSTek       | GL552JX                     | [af998c8996](https://linux-hardware.org/?probe=af998c8996) | Mar 22, 2021 |
| HP            | OMEN by Laptop 15-dh0xxx    | [103f41c99c](https://linux-hardware.org/?probe=103f41c99c) | Mar 21, 2021 |
| Dell          | Latitude E6440              | [6f00c6ac0b](https://linux-hardware.org/?probe=6f00c6ac0b) | Mar 21, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e76eac394d](https://linux-hardware.org/?probe=e76eac394d) | Mar 20, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [a9efbe668e](https://linux-hardware.org/?probe=a9efbe668e) | Mar 20, 2021 |
| HP            | EliteBook x360 1040 G5      | [6c42757430](https://linux-hardware.org/?probe=6c42757430) | Mar 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [35f9677ce6](https://linux-hardware.org/?probe=35f9677ce6) | Mar 19, 2021 |
| Dell          | Inspiron 3537               | [98d6ff8291](https://linux-hardware.org/?probe=98d6ff8291) | Mar 19, 2021 |
| MSI           | EX620                       | [92223bedbf](https://linux-hardware.org/?probe=92223bedbf) | Mar 18, 2021 |
| HP            | Laptop 17-ak0xx             | [2eee8ebb3d](https://linux-hardware.org/?probe=2eee8ebb3d) | Mar 18, 2021 |
| HP            | Laptop 17-ak0xx             | [4e9b5c0bbe](https://linux-hardware.org/?probe=4e9b5c0bbe) | Mar 18, 2021 |
| HP            | Laptop 17-ak0xx             | [f6768a311c](https://linux-hardware.org/?probe=f6768a311c) | Mar 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b1f0621720](https://linux-hardware.org/?probe=b1f0621720) | Mar 15, 2021 |
| Dell          | Inspiron 3593               | [e2f95f0c46](https://linux-hardware.org/?probe=e2f95f0c46) | Mar 10, 2021 |
| ASUSTek       | X555LJ                      | [e645327b43](https://linux-hardware.org/?probe=e645327b43) | Mar 10, 2021 |
| Toshiba       | Satellite C55-A             | [7404ca8168](https://linux-hardware.org/?probe=7404ca8168) | Mar 10, 2021 |
| Toshiba       | Satellite C55-A             | [07d0435295](https://linux-hardware.org/?probe=07d0435295) | Mar 10, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [fa166645b1](https://linux-hardware.org/?probe=fa166645b1) | Mar 09, 2021 |
| HP            | ProBook 640 G1              | [c745fe0fbf](https://linux-hardware.org/?probe=c745fe0fbf) | Mar 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [3eab48365a](https://linux-hardware.org/?probe=3eab48365a) | Mar 08, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2b34023242](https://linux-hardware.org/?probe=2b34023242) | Mar 07, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [44428b2791](https://linux-hardware.org/?probe=44428b2791) | Mar 06, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | [665f41ae68](https://linux-hardware.org/?probe=665f41ae68) | Mar 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [74af4c6f9d](https://linux-hardware.org/?probe=74af4c6f9d) | Mar 05, 2021 |
| ASUSTek       | ZenBook Pro 15 UX550GD_U... | [3123875940](https://linux-hardware.org/?probe=3123875940) | Mar 05, 2021 |
| ASUSTek       | K54LY                       | [6968932b0f](https://linux-hardware.org/?probe=6968932b0f) | Mar 04, 2021 |
| Acer          | Aspire V5-552               | [7a32a8a1c3](https://linux-hardware.org/?probe=7a32a8a1c3) | Mar 03, 2021 |
| Dell          | Inspiron 3537               | [746e41378c](https://linux-hardware.org/?probe=746e41378c) | Mar 03, 2021 |
| HP            | ProBook 470 G3              | [395ee9975c](https://linux-hardware.org/?probe=395ee9975c) | Mar 01, 2021 |
| ASUSTek       | GL753VD                     | [bdb6fc8fb3](https://linux-hardware.org/?probe=bdb6fc8fb3) | Feb 27, 2021 |
| Acer          | Aspire E5-571               | [4a0c1cf20f](https://linux-hardware.org/?probe=4a0c1cf20f) | Feb 27, 2021 |
| ASUSTek       | X550MD                      | [75d04a8384](https://linux-hardware.org/?probe=75d04a8384) | Feb 27, 2021 |
| Dell          | Latitude 7410               | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Dell          | Latitude 7410               | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Dell          | Latitude 7410               | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Dell          | Latitude 7490               | [57718f7826](https://linux-hardware.org/?probe=57718f7826) | Feb 22, 2021 |
| Apple         | MacBookPro12,1              | [6a8d2a4826](https://linux-hardware.org/?probe=6a8d2a4826) | Feb 22, 2021 |
| Fujitsu Si... | AMILO Li 2735               | [ca3a6f2e30](https://linux-hardware.org/?probe=ca3a6f2e30) | Feb 21, 2021 |
| Fujitsu Si... | AMILO Li 2735               | [f873a05dc6](https://linux-hardware.org/?probe=f873a05dc6) | Feb 21, 2021 |
| Dell          | Latitude E6400              | [4285e6b02b](https://linux-hardware.org/?probe=4285e6b02b) | Feb 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | [c1dae36682](https://linux-hardware.org/?probe=c1dae36682) | Feb 20, 2021 |
| Apple         | MacBookPro12,1              | [d8a44d0f28](https://linux-hardware.org/?probe=d8a44d0f28) | Feb 20, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [f088672fd6](https://linux-hardware.org/?probe=f088672fd6) | Feb 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3f321d1a28](https://linux-hardware.org/?probe=3f321d1a28) | Feb 19, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [663573b53a](https://linux-hardware.org/?probe=663573b53a) | Feb 18, 2021 |
| Lenovo        | ThinkPad W510 431924G       | [2f320b6b8b](https://linux-hardware.org/?probe=2f320b6b8b) | Feb 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f35f504d4c](https://linux-hardware.org/?probe=f35f504d4c) | Feb 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5d1d62012e](https://linux-hardware.org/?probe=5d1d62012e) | Feb 18, 2021 |
| ASUSTek       | X540NA                      | [ffe6defb70](https://linux-hardware.org/?probe=ffe6defb70) | Feb 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | [f9157c519d](https://linux-hardware.org/?probe=f9157c519d) | Feb 17, 2021 |
| ASUSTek       | X541UAK                     | [784536a677](https://linux-hardware.org/?probe=784536a677) | Feb 16, 2021 |
| Dell          | Latitude E5540              | [7832e1a3b7](https://linux-hardware.org/?probe=7832e1a3b7) | Feb 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [152203a2ba](https://linux-hardware.org/?probe=152203a2ba) | Feb 16, 2021 |
| Toshiba       | Satellite C55-A-142         | [247d69009c](https://linux-hardware.org/?probe=247d69009c) | Feb 14, 2021 |
| Apple         | MacBookPro7,1               | [57ec5647c3](https://linux-hardware.org/?probe=57ec5647c3) | Feb 14, 2021 |
| ASUSTek       | 1015PN                      | [baf4b343fd](https://linux-hardware.org/?probe=baf4b343fd) | Feb 14, 2021 |
| Lenovo        | ThinkPad T400 6475CA6       | [73e76bab10](https://linux-hardware.org/?probe=73e76bab10) | Feb 14, 2021 |
| HP            | Laptop 17-by3xxx            | [b4b56c090a](https://linux-hardware.org/?probe=b4b56c090a) | Feb 13, 2021 |
| Acer          | Extensa 2510                | [817ace0ace](https://linux-hardware.org/?probe=817ace0ace) | Feb 13, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [31543637c8](https://linux-hardware.org/?probe=31543637c8) | Feb 13, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [cdb4ad1982](https://linux-hardware.org/?probe=cdb4ad1982) | Feb 13, 2021 |
| Dell          | Latitude E5540              | [5584cf7f24](https://linux-hardware.org/?probe=5584cf7f24) | Feb 13, 2021 |
| ASUSTek       | X541UAK                     | [8276f6c2bd](https://linux-hardware.org/?probe=8276f6c2bd) | Feb 11, 2021 |
| HP            | EliteBook 850 G2            | [043a4f9a2f](https://linux-hardware.org/?probe=043a4f9a2f) | Feb 10, 2021 |
| HP            | ProBook 4730s               | [5ff33d4354](https://linux-hardware.org/?probe=5ff33d4354) | Feb 09, 2021 |
| HP            | ProBook 4730s               | [93d90c3fb1](https://linux-hardware.org/?probe=93d90c3fb1) | Feb 09, 2021 |
| ASUSTek       | X550LN                      | [73d6c6f15e](https://linux-hardware.org/?probe=73d6c6f15e) | Feb 09, 2021 |
| ASUSTek       | ASUSPRO P2540FAC_P2540FA    | [abdca28e7c](https://linux-hardware.org/?probe=abdca28e7c) | Feb 09, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [f58cfe253f](https://linux-hardware.org/?probe=f58cfe253f) | Feb 07, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [013f6aff04](https://linux-hardware.org/?probe=013f6aff04) | Feb 07, 2021 |
| Dell          | MXP061                      | [6f7197b7ae](https://linux-hardware.org/?probe=6f7197b7ae) | Feb 06, 2021 |
| Dell          | MXP061                      | [22a06d3323](https://linux-hardware.org/?probe=22a06d3323) | Feb 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [cb770a2a4a](https://linux-hardware.org/?probe=cb770a2a4a) | Feb 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [2eb0c82f70](https://linux-hardware.org/?probe=2eb0c82f70) | Feb 03, 2021 |
| Sony          | VGN-FE41M                   | [c51a776cc5](https://linux-hardware.org/?probe=c51a776cc5) | Feb 02, 2021 |
| HP            | Presario CQ57               | [19a6c09c3e](https://linux-hardware.org/?probe=19a6c09c3e) | Jan 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [ac311333ff](https://linux-hardware.org/?probe=ac311333ff) | Jan 30, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d4da3e2513](https://linux-hardware.org/?probe=d4da3e2513) | Jan 29, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [272eade130](https://linux-hardware.org/?probe=272eade130) | Jan 29, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [289f9ae271](https://linux-hardware.org/?probe=289f9ae271) | Jan 29, 2021 |
| ASUSTek       | UX305UA                     | [b1dc433a09](https://linux-hardware.org/?probe=b1dc433a09) | Jan 28, 2021 |
| Lenovo        | ThinkPad T540p 20BE00B8G... | [9d1461485d](https://linux-hardware.org/?probe=9d1461485d) | Jan 28, 2021 |
| HP            | Presario CQ57               | [1919dbbb75](https://linux-hardware.org/?probe=1919dbbb75) | Jan 28, 2021 |
| Lenovo        | G70-35 80Q5                 | [f3c89d149b](https://linux-hardware.org/?probe=f3c89d149b) | Jan 27, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [a85ceac13e](https://linux-hardware.org/?probe=a85ceac13e) | Jan 26, 2021 |
| ASUSTek       | X541UAK                     | [6a5476a3e1](https://linux-hardware.org/?probe=6a5476a3e1) | Jan 26, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bafe61522f](https://linux-hardware.org/?probe=bafe61522f) | Jan 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [828f2b7754](https://linux-hardware.org/?probe=828f2b7754) | Jan 23, 2021 |
| ASUSTek       | N551JK                      | [a9a6946b8e](https://linux-hardware.org/?probe=a9a6946b8e) | Jan 23, 2021 |
| HP            | ProBook 650 G1              | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [43ba8acee5](https://linux-hardware.org/?probe=43ba8acee5) | Jan 22, 2021 |
| Dell          | Latitude E6510              | [bc65564608](https://linux-hardware.org/?probe=bc65564608) | Jan 22, 2021 |
| Dell          | Latitude E6510              | [19035e3a57](https://linux-hardware.org/?probe=19035e3a57) | Jan 22, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [0f10632552](https://linux-hardware.org/?probe=0f10632552) | Jan 21, 2021 |
| Dell          | Latitude 7490               | [b47d279f38](https://linux-hardware.org/?probe=b47d279f38) | Jan 19, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [acf297a14f](https://linux-hardware.org/?probe=acf297a14f) | Jan 18, 2021 |
| Acer          | Aspire E5-573G              | [8b86d45cac](https://linux-hardware.org/?probe=8b86d45cac) | Jan 18, 2021 |
| HP            | 250 G7 Notebook PC          | [28100702d5](https://linux-hardware.org/?probe=28100702d5) | Jan 17, 2021 |
| HP            | 250 G7 Notebook PC          | [a2d9b3dfda](https://linux-hardware.org/?probe=a2d9b3dfda) | Jan 17, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [7a5d933436](https://linux-hardware.org/?probe=7a5d933436) | Jan 17, 2021 |
| Acer          | Aspire E5-571G              | [57635b1aba](https://linux-hardware.org/?probe=57635b1aba) | Jan 17, 2021 |
| Acer          | Aspire E5-571G              | [65cde34da7](https://linux-hardware.org/?probe=65cde34da7) | Jan 17, 2021 |
| Dell          | System Vostro 3750          | [9937221a43](https://linux-hardware.org/?probe=9937221a43) | Jan 17, 2021 |
| Medion        | Akoya THE TOUCH 10          | [eceacb3f4d](https://linux-hardware.org/?probe=eceacb3f4d) | Jan 17, 2021 |
| Dell          | System Vostro 3750          | [a418e425c7](https://linux-hardware.org/?probe=a418e425c7) | Jan 17, 2021 |
| Medion        | Akoya THE TOUCH 10          | [a180a8e458](https://linux-hardware.org/?probe=a180a8e458) | Jan 17, 2021 |
| Acer          | Aspire S3                   | [7e2b356d79](https://linux-hardware.org/?probe=7e2b356d79) | Jan 16, 2021 |
| Dell          | G5 5590                     | [ba4c180ec8](https://linux-hardware.org/?probe=ba4c180ec8) | Jan 15, 2021 |
| ASUSTek       | X541UAK                     | [aa55f96c20](https://linux-hardware.org/?probe=aa55f96c20) | Jan 13, 2021 |
| Lenovo        | V14-ADA 82C6                | [0475ad6615](https://linux-hardware.org/?probe=0475ad6615) | Jan 13, 2021 |
| Lenovo        | V14-ADA 82C6                | [5b356a57ae](https://linux-hardware.org/?probe=5b356a57ae) | Jan 13, 2021 |
| Lenovo        | G50-30 80G0                 | [bb1bcd6b1e](https://linux-hardware.org/?probe=bb1bcd6b1e) | Jan 12, 2021 |
| Lenovo        | G50-30 80G0                 | [410e9671aa](https://linux-hardware.org/?probe=410e9671aa) | Jan 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [47079d3d35](https://linux-hardware.org/?probe=47079d3d35) | Jan 11, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [8f657c591d](https://linux-hardware.org/?probe=8f657c591d) | Jan 09, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [0fddb1fb39](https://linux-hardware.org/?probe=0fddb1fb39) | Jan 09, 2021 |
| ASUSTek       | X541NA                      | [6781408d67](https://linux-hardware.org/?probe=6781408d67) | Jan 09, 2021 |
| HP            | 620                         | [729c0df418](https://linux-hardware.org/?probe=729c0df418) | Jan 08, 2021 |
| Dell          | Latitude 3410               | [c5d394794f](https://linux-hardware.org/?probe=c5d394794f) | Jan 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d0e5cef961](https://linux-hardware.org/?probe=d0e5cef961) | Jan 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ae5845289c](https://linux-hardware.org/?probe=ae5845289c) | Jan 07, 2021 |
| Dell          | Latitude 5500               | [7d60998274](https://linux-hardware.org/?probe=7d60998274) | Jan 06, 2021 |
| Panasonic     | CF-C2CC-03CM                | [67c905be49](https://linux-hardware.org/?probe=67c905be49) | Jan 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [d1f58ffd6c](https://linux-hardware.org/?probe=d1f58ffd6c) | Jan 05, 2021 |
| Dell          | System XPS L502X            | [33310a7b7f](https://linux-hardware.org/?probe=33310a7b7f) | Jan 04, 2021 |
| Acer          | AOD255                      | [534f59ebc3](https://linux-hardware.org/?probe=534f59ebc3) | Jan 02, 2021 |
| Dell          | Inspiron 1564               | [0561beb40e](https://linux-hardware.org/?probe=0561beb40e) | Dec 30, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [de6fb7c6e1](https://linux-hardware.org/?probe=de6fb7c6e1) | Dec 28, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [94e0005a31](https://linux-hardware.org/?probe=94e0005a31) | Dec 26, 2020 |
| Lenovo        | ThinkPad X240 20AL007YMD    | [0d24a583d3](https://linux-hardware.org/?probe=0d24a583d3) | Dec 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [305752cb5f](https://linux-hardware.org/?probe=305752cb5f) | Dec 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0aaad8ee34](https://linux-hardware.org/?probe=0aaad8ee34) | Dec 24, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [f6164f5e30](https://linux-hardware.org/?probe=f6164f5e30) | Dec 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [99b7148d04](https://linux-hardware.org/?probe=99b7148d04) | Dec 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [76261098a6](https://linux-hardware.org/?probe=76261098a6) | Dec 23, 2020 |
| ASUSTek       | K52N                        | [8d2ca7de30](https://linux-hardware.org/?probe=8d2ca7de30) | Dec 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c68261476a](https://linux-hardware.org/?probe=c68261476a) | Dec 21, 2020 |
| Dell          | Inspiron 1525               | [747b27942b](https://linux-hardware.org/?probe=747b27942b) | Dec 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d0a8d6ce10](https://linux-hardware.org/?probe=d0a8d6ce10) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [77e1cb3ca1](https://linux-hardware.org/?probe=77e1cb3ca1) | Dec 18, 2020 |
| Dell          | Latitude E5530 non-vPro     | [141cb1851f](https://linux-hardware.org/?probe=141cb1851f) | Dec 18, 2020 |
| Dell          | Latitude E5530 non-vPro     | [b113008ece](https://linux-hardware.org/?probe=b113008ece) | Dec 17, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [5ad2754f9b](https://linux-hardware.org/?probe=5ad2754f9b) | Dec 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7bae88cc8f](https://linux-hardware.org/?probe=7bae88cc8f) | Dec 16, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [81ac257b9e](https://linux-hardware.org/?probe=81ac257b9e) | Dec 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [19516bc732](https://linux-hardware.org/?probe=19516bc732) | Dec 15, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [0caaf0f2b5](https://linux-hardware.org/?probe=0caaf0f2b5) | Dec 15, 2020 |
| Sony          | VPCSB11FX                   | [388e730d58](https://linux-hardware.org/?probe=388e730d58) | Dec 14, 2020 |
| ASUSTek       | X541UVK                     | [006e477f5f](https://linux-hardware.org/?probe=006e477f5f) | Dec 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [cd65198133](https://linux-hardware.org/?probe=cd65198133) | Dec 13, 2020 |
| Acer          | AOD260                      | [dabc9bc556](https://linux-hardware.org/?probe=dabc9bc556) | Dec 13, 2020 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [e34076901f](https://linux-hardware.org/?probe=e34076901f) | Dec 13, 2020 |
| ASUSTek       | X541NA                      | [3682e9a5cb](https://linux-hardware.org/?probe=3682e9a5cb) | Dec 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f0b1d1dfe8](https://linux-hardware.org/?probe=f0b1d1dfe8) | Dec 13, 2020 |
| Acer          | Extensa 5220                | [3dfca3a90f](https://linux-hardware.org/?probe=3dfca3a90f) | Dec 12, 2020 |
| Acer          | Extensa 5220                | [9b67134373](https://linux-hardware.org/?probe=9b67134373) | Dec 12, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [b8d0c8158d](https://linux-hardware.org/?probe=b8d0c8158d) | Dec 12, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [880408fa1c](https://linux-hardware.org/?probe=880408fa1c) | Dec 11, 2020 |
| ASUSTek       | X541UAK                     | [6b32f6d525](https://linux-hardware.org/?probe=6b32f6d525) | Dec 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [1579cfe3a2](https://linux-hardware.org/?probe=1579cfe3a2) | Dec 11, 2020 |
| HP            | Pavilion dv6700             | [2903cb1f15](https://linux-hardware.org/?probe=2903cb1f15) | Dec 10, 2020 |
| HP            | ProBook 6450b               | [4e8bb2e458](https://linux-hardware.org/?probe=4e8bb2e458) | Dec 09, 2020 |
| Dell          | Latitude D630               | [6c6318192a](https://linux-hardware.org/?probe=6c6318192a) | Dec 07, 2020 |
| Dell          | Inspiron 1545               | [87359e53e9](https://linux-hardware.org/?probe=87359e53e9) | Dec 07, 2020 |
| Dell          | Inspiron 1545               | [ea31ff03c8](https://linux-hardware.org/?probe=ea31ff03c8) | Dec 07, 2020 |
| Acer          | AOD255E                     | [5eea1b55a3](https://linux-hardware.org/?probe=5eea1b55a3) | Dec 06, 2020 |
| ASUSTek       | X541UAK                     | [f7463ea747](https://linux-hardware.org/?probe=f7463ea747) | Dec 05, 2020 |
| Dell          | Latitude 5500               | [26de745c7b](https://linux-hardware.org/?probe=26de745c7b) | Dec 04, 2020 |
| MSI           | Creator 17 A10SE            | [35220ae516](https://linux-hardware.org/?probe=35220ae516) | Dec 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d084d420e0](https://linux-hardware.org/?probe=d084d420e0) | Dec 03, 2020 |
| HP            | Compaq CQ58                 | [0e2bb3654b](https://linux-hardware.org/?probe=0e2bb3654b) | Dec 03, 2020 |
| ASUSTek       | G73Sw                       | [9b1e1d6799](https://linux-hardware.org/?probe=9b1e1d6799) | Dec 02, 2020 |
| ASUSTek       | G73Sw                       | [b01fce2bb9](https://linux-hardware.org/?probe=b01fce2bb9) | Dec 02, 2020 |
| Acer          | Aspire 7750G                | [47d2187fab](https://linux-hardware.org/?probe=47d2187fab) | Dec 01, 2020 |
| Dell          | Latitude E5530 non-vPro     | [7dcf0cebbe](https://linux-hardware.org/?probe=7dcf0cebbe) | Dec 01, 2020 |
| ASUSTek       | X550LB                      | [c56e4b8726](https://linux-hardware.org/?probe=c56e4b8726) | Nov 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [a5b0b03310](https://linux-hardware.org/?probe=a5b0b03310) | Nov 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4f20504a63](https://linux-hardware.org/?probe=4f20504a63) | Nov 30, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c614d0579b](https://linux-hardware.org/?probe=c614d0579b) | Nov 29, 2020 |
| ASUSTek       | X541NA                      | [0ba1837c2d](https://linux-hardware.org/?probe=0ba1837c2d) | Nov 29, 2020 |
| HP            | EliteBook 2540p             | [acdd976c37](https://linux-hardware.org/?probe=acdd976c37) | Nov 28, 2020 |
| ASUSTek       | G73Sw                       | [410a4cad90](https://linux-hardware.org/?probe=410a4cad90) | Nov 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [acc99cf7d1](https://linux-hardware.org/?probe=acc99cf7d1) | Nov 28, 2020 |
| HUAWEI        | WRTB-WXX9                   | [886c0ae823](https://linux-hardware.org/?probe=886c0ae823) | Nov 27, 2020 |
| Dell          | Vostro A860                 | [beffd605b7](https://linux-hardware.org/?probe=beffd605b7) | Nov 27, 2020 |
| ASUSTek       | GL552VX                     | [f325deb3a0](https://linux-hardware.org/?probe=f325deb3a0) | Nov 26, 2020 |
| HP            | ProBook 4540s               | [0e026f8802](https://linux-hardware.org/?probe=0e026f8802) | Nov 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [ee6d8b5ee8](https://linux-hardware.org/?probe=ee6d8b5ee8) | Nov 26, 2020 |
| ASUSTek       | X406UAR                     | [5b12bbe50c](https://linux-hardware.org/?probe=5b12bbe50c) | Nov 26, 2020 |
| HP            | ProBook 4540s               | [5d8ebf5589](https://linux-hardware.org/?probe=5d8ebf5589) | Nov 25, 2020 |
| HP            | ProBook 4540s               | [93f48c6529](https://linux-hardware.org/?probe=93f48c6529) | Nov 24, 2020 |
| HP            | ProBook 6450b               | [6bf78ad580](https://linux-hardware.org/?probe=6bf78ad580) | Nov 24, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [87ba3cd4ed](https://linux-hardware.org/?probe=87ba3cd4ed) | Nov 24, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [4129c71a62](https://linux-hardware.org/?probe=4129c71a62) | Nov 23, 2020 |
| ASUSTek       | G73Sw                       | [e3f441cd1d](https://linux-hardware.org/?probe=e3f441cd1d) | Nov 23, 2020 |
| ASUSTek       | G73Sw                       | [1dfdd6d63c](https://linux-hardware.org/?probe=1dfdd6d63c) | Nov 23, 2020 |
| HP            | Laptop 15-ra0xx             | [35b6daa8bf](https://linux-hardware.org/?probe=35b6daa8bf) | Nov 23, 2020 |
| ASUSTek       | G73Sw                       | [6a01d589bc](https://linux-hardware.org/?probe=6a01d589bc) | Nov 22, 2020 |
| Sony          | VPCZ13Z9E                   | [0590fd3738](https://linux-hardware.org/?probe=0590fd3738) | Nov 22, 2020 |
| ASUSTek       | X541NA                      | [a66fe0e5c8](https://linux-hardware.org/?probe=a66fe0e5c8) | Nov 21, 2020 |
| Dell          | Latitude E7450              | [d1a21c867e](https://linux-hardware.org/?probe=d1a21c867e) | Nov 20, 2020 |
| HP            | ProBook 6570b               | [37993e4fa8](https://linux-hardware.org/?probe=37993e4fa8) | Nov 20, 2020 |
| HP            | ProBook 6570b               | [7e9fdcc355](https://linux-hardware.org/?probe=7e9fdcc355) | Nov 20, 2020 |
| HP            | EliteBook 8540p             | [d797246cd7](https://linux-hardware.org/?probe=d797246cd7) | Nov 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [266411c1ec](https://linux-hardware.org/?probe=266411c1ec) | Nov 18, 2020 |
| HP            | OMEN by Laptop 15-dh1xxx    | [1174318685](https://linux-hardware.org/?probe=1174318685) | Nov 17, 2020 |
| HP            | OMEN by Laptop 15-dh1xxx    | [9ba00c3039](https://linux-hardware.org/?probe=9ba00c3039) | Nov 17, 2020 |
| ASUSTek       | K50IJ                       | [26b67890fc](https://linux-hardware.org/?probe=26b67890fc) | Nov 16, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | [2f7deb99e7](https://linux-hardware.org/?probe=2f7deb99e7) | Nov 15, 2020 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [889cb35866](https://linux-hardware.org/?probe=889cb35866) | Nov 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eb6ede0831](https://linux-hardware.org/?probe=eb6ede0831) | Nov 12, 2020 |
| HP            | EliteBook 840 G1            | [66a2004080](https://linux-hardware.org/?probe=66a2004080) | Nov 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [50e185035e](https://linux-hardware.org/?probe=50e185035e) | Nov 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c6a59cd43b](https://linux-hardware.org/?probe=c6a59cd43b) | Nov 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8c4f3792bb](https://linux-hardware.org/?probe=8c4f3792bb) | Nov 11, 2020 |
| Dynabook      | PORTEGE X30L-G              | [0499612b59](https://linux-hardware.org/?probe=0499612b59) | Nov 10, 2020 |
| ASUSTek       | X556UV                      | [0b3a9b5950](https://linux-hardware.org/?probe=0b3a9b5950) | Nov 09, 2020 |
| Medion        | E7212                       | [8979d90ea2](https://linux-hardware.org/?probe=8979d90ea2) | Nov 09, 2020 |
| Medion        | E7212                       | [3650f725ba](https://linux-hardware.org/?probe=3650f725ba) | Nov 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [30f3de963b](https://linux-hardware.org/?probe=30f3de963b) | Nov 09, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [0452d01d1a](https://linux-hardware.org/?probe=0452d01d1a) | Nov 08, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [4934aff2c8](https://linux-hardware.org/?probe=4934aff2c8) | Nov 08, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a5306af98c](https://linux-hardware.org/?probe=a5306af98c) | Nov 07, 2020 |
| HP            | 15                          | [a322932224](https://linux-hardware.org/?probe=a322932224) | Nov 07, 2020 |
| Dell          | Inspiron 3542               | [6dd030da31](https://linux-hardware.org/?probe=6dd030da31) | Nov 05, 2020 |
| ASUSTek       | X541NA                      | [4b61f9ffaa](https://linux-hardware.org/?probe=4b61f9ffaa) | Nov 05, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e35da2ef25](https://linux-hardware.org/?probe=e35da2ef25) | Nov 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [1234862547](https://linux-hardware.org/?probe=1234862547) | Nov 04, 2020 |
| Dell          | Latitude 7400               | [69820b5628](https://linux-hardware.org/?probe=69820b5628) | Nov 02, 2020 |
| ASUSTek       | X541UAK                     | [971d72f3f2](https://linux-hardware.org/?probe=971d72f3f2) | Nov 01, 2020 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | [85ed281e0a](https://linux-hardware.org/?probe=85ed281e0a) | Nov 01, 2020 |
| ASUSTek       | X541UAK                     | [80c9e12aad](https://linux-hardware.org/?probe=80c9e12aad) | Oct 30, 2020 |
| ASUSTek       | X541UAK                     | [1235a5963f](https://linux-hardware.org/?probe=1235a5963f) | Oct 29, 2020 |
| ASUSTek       | X541UAK                     | [1a907fd694](https://linux-hardware.org/?probe=1a907fd694) | Oct 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4df21abd9b](https://linux-hardware.org/?probe=4df21abd9b) | Oct 29, 2020 |
| Samsung       | 300V3Z/300V4Z/300V5Z/200... | [e9ff5b55dc](https://linux-hardware.org/?probe=e9ff5b55dc) | Oct 25, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6391e167a7](https://linux-hardware.org/?probe=6391e167a7) | Oct 25, 2020 |
| Toshiba       | Satellite C855-248          | [9cb35dc352](https://linux-hardware.org/?probe=9cb35dc352) | Oct 23, 2020 |
| HP            | EliteBook x360 1040 G5      | [118974f05c](https://linux-hardware.org/?probe=118974f05c) | Oct 22, 2020 |
| ASUSTek       | X541NA                      | [632eb67e6b](https://linux-hardware.org/?probe=632eb67e6b) | Oct 21, 2020 |
| ASUSTek       | X541NA                      | [6e16a63ab1](https://linux-hardware.org/?probe=6e16a63ab1) | Oct 20, 2020 |
| Fujitsu       | LIFEBOOK S710               | [fa8314c368](https://linux-hardware.org/?probe=fa8314c368) | Oct 19, 2020 |
| Lenovo        | ThinkPad T60 1952EB4        | [62681b5680](https://linux-hardware.org/?probe=62681b5680) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [70a35724ab](https://linux-hardware.org/?probe=70a35724ab) | Oct 17, 2020 |
| Dell          | Vostro 3578                 | [aca3bf63fc](https://linux-hardware.org/?probe=aca3bf63fc) | Oct 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c760b0c229](https://linux-hardware.org/?probe=c760b0c229) | Oct 16, 2020 |
| Dynabook      | PORTEGE X30L-G              | [00ad2832f0](https://linux-hardware.org/?probe=00ad2832f0) | Oct 15, 2020 |
| Toshiba       | Satellite C50-A-1HF         | [c7dfec30b3](https://linux-hardware.org/?probe=c7dfec30b3) | Oct 14, 2020 |
| Dell          | Latitude 7400               | [91bdb0cd8d](https://linux-hardware.org/?probe=91bdb0cd8d) | Oct 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [b572236a74](https://linux-hardware.org/?probe=b572236a74) | Oct 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [34500fc62e](https://linux-hardware.org/?probe=34500fc62e) | Oct 13, 2020 |
| Lenovo        | Z50-75 80EC                 | [ed6d8ada04](https://linux-hardware.org/?probe=ed6d8ada04) | Oct 10, 2020 |
| HP            | EliteBook x360 1040 G5      | [0c8712a97d](https://linux-hardware.org/?probe=0c8712a97d) | Oct 08, 2020 |
| Complet       | MY8312                      | [e9ec50e9d3](https://linux-hardware.org/?probe=e9ec50e9d3) | Oct 08, 2020 |
| Dell          | XPS 15 9570                 | [c9e22b9ded](https://linux-hardware.org/?probe=c9e22b9ded) | Oct 07, 2020 |
| Dell          | Vostro 1700                 | [9c48306437](https://linux-hardware.org/?probe=9c48306437) | Oct 07, 2020 |
| Dell          | Vostro 1700                 | [f6b7e65512](https://linux-hardware.org/?probe=f6b7e65512) | Oct 07, 2020 |
| Lenovo        | ThinkPad W510 431924G       | [3b3774f092](https://linux-hardware.org/?probe=3b3774f092) | Oct 06, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3a52d9b063](https://linux-hardware.org/?probe=3a52d9b063) | Oct 05, 2020 |
| Toshiba       | Satellite C55-C             | [100f1ee419](https://linux-hardware.org/?probe=100f1ee419) | Oct 05, 2020 |
| ASUSTek       | X541NA                      | [acb389920c](https://linux-hardware.org/?probe=acb389920c) | Oct 05, 2020 |
| ASUSTek       | S551LN                      | [5668b2f059](https://linux-hardware.org/?probe=5668b2f059) | Oct 04, 2020 |
| ASUSTek       | S551LN                      | [68fd29b9ee](https://linux-hardware.org/?probe=68fd29b9ee) | Oct 04, 2020 |
| HP            | ProBook 4540s               | [35d24d8dfe](https://linux-hardware.org/?probe=35d24d8dfe) | Oct 01, 2020 |
| HP            | ProBook 4540s               | [79aa030173](https://linux-hardware.org/?probe=79aa030173) | Oct 01, 2020 |
| Fujitsu Si... | AMILO Pa 1510               | [6d68ce16bd](https://linux-hardware.org/?probe=6d68ce16bd) | Oct 01, 2020 |
| Dell          | Inspiron 3583               | [4493f0ea26](https://linux-hardware.org/?probe=4493f0ea26) | Oct 01, 2020 |
| Dell          | Inspiron 3583               | [6bd973e7e1](https://linux-hardware.org/?probe=6bd973e7e1) | Oct 01, 2020 |
| Fujitsu Si... | AMILO Pa 1510               | [978510a0b5](https://linux-hardware.org/?probe=978510a0b5) | Oct 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [4f97d73b64](https://linux-hardware.org/?probe=4f97d73b64) | Sep 30, 2020 |
| ASUSTek       | X541NA                      | [93bdfaf3db](https://linux-hardware.org/?probe=93bdfaf3db) | Sep 29, 2020 |
| Acer          | Aspire 5710                 | [dedd73d125](https://linux-hardware.org/?probe=dedd73d125) | Sep 27, 2020 |
| ASUSTek       | X541NA                      | [653b643c7a](https://linux-hardware.org/?probe=653b643c7a) | Sep 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [a8cbab13ef](https://linux-hardware.org/?probe=a8cbab13ef) | Sep 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9e02133de7](https://linux-hardware.org/?probe=9e02133de7) | Sep 25, 2020 |
| ASUSTek       | X541UVK                     | [ea88cc333b](https://linux-hardware.org/?probe=ea88cc333b) | Sep 25, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [e0efe47cb6](https://linux-hardware.org/?probe=e0efe47cb6) | Sep 25, 2020 |
| Acer          | Extensa 5620                | [2cd43c8065](https://linux-hardware.org/?probe=2cd43c8065) | Sep 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9e488275fb](https://linux-hardware.org/?probe=9e488275fb) | Sep 23, 2020 |
| ASUSTek       | K50AB                       | [fa66c49c14](https://linux-hardware.org/?probe=fa66c49c14) | Sep 23, 2020 |
| Dell          | Inspiron 5593               | [f3c754bb88](https://linux-hardware.org/?probe=f3c754bb88) | Sep 21, 2020 |
| HP            | ZBook 15 G6                 | [ab03e826aa](https://linux-hardware.org/?probe=ab03e826aa) | Sep 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c118f72c5e](https://linux-hardware.org/?probe=c118f72c5e) | Sep 20, 2020 |
| ASUSTek       | K55VD                       | [6428dbb6a4](https://linux-hardware.org/?probe=6428dbb6a4) | Sep 20, 2020 |
| Hungaro Fl... | Navon Loop 360              | [4f768eeeac](https://linux-hardware.org/?probe=4f768eeeac) | Sep 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cbde92e63f](https://linux-hardware.org/?probe=cbde92e63f) | Sep 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d33cfb7831](https://linux-hardware.org/?probe=d33cfb7831) | Sep 17, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [1fa7cd3dc7](https://linux-hardware.org/?probe=1fa7cd3dc7) | Sep 16, 2020 |
| Lenovo        | V110-15ISK 80TL             | [1c7564950b](https://linux-hardware.org/?probe=1c7564950b) | Sep 13, 2020 |
| ASUSTek       | K50AB                       | [7a26a54f38](https://linux-hardware.org/?probe=7a26a54f38) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | [1697990f38](https://linux-hardware.org/?probe=1697990f38) | Sep 12, 2020 |
| ASUSTek       | X541UVK                     | [1c04612630](https://linux-hardware.org/?probe=1c04612630) | Sep 11, 2020 |
| Lenovo        | ThinkPad W510 431924G       | [8248f08a34](https://linux-hardware.org/?probe=8248f08a34) | Sep 11, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [652b191bb2](https://linux-hardware.org/?probe=652b191bb2) | Sep 11, 2020 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | [9b7beb4199](https://linux-hardware.org/?probe=9b7beb4199) | Sep 10, 2020 |
| Dell          | Latitude 5501               | [bceeec9520](https://linux-hardware.org/?probe=bceeec9520) | Sep 10, 2020 |
| ASUSTek       | X550JX                      | [73576f6c41](https://linux-hardware.org/?probe=73576f6c41) | Sep 09, 2020 |
| Dell          | Latitude 5501               | [0df822dc02](https://linux-hardware.org/?probe=0df822dc02) | Sep 09, 2020 |
| HP            | ENVY 15                     | [7c3a7ca004](https://linux-hardware.org/?probe=7c3a7ca004) | Sep 08, 2020 |
| HP            | ENVY 15                     | [271d977662](https://linux-hardware.org/?probe=271d977662) | Sep 08, 2020 |
| Hungaro Fl... | Navon Loop 360              | [24b55d18fb](https://linux-hardware.org/?probe=24b55d18fb) | Sep 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [a359d9bb3e](https://linux-hardware.org/?probe=a359d9bb3e) | Sep 07, 2020 |
| ASUSTek       | K50AB                       | [875022889d](https://linux-hardware.org/?probe=875022889d) | Sep 06, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [19bc56d65c](https://linux-hardware.org/?probe=19bc56d65c) | Sep 06, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [13c21685a6](https://linux-hardware.org/?probe=13c21685a6) | Sep 05, 2020 |
| Apple         | MacBook2,1                  | [7f1bcb2254](https://linux-hardware.org/?probe=7f1bcb2254) | Sep 05, 2020 |
| Acer          | Aspire A315-53              | [c2d5971945](https://linux-hardware.org/?probe=c2d5971945) | Sep 04, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [87fcc056b6](https://linux-hardware.org/?probe=87fcc056b6) | Sep 03, 2020 |
| Lenovo        | ThinkPad P1 20MES2PB00      | [79de72d26f](https://linux-hardware.org/?probe=79de72d26f) | Sep 03, 2020 |
| Dell          | Latitude E6420              | [2db037ae33](https://linux-hardware.org/?probe=2db037ae33) | Sep 02, 2020 |
| Dell          | Latitude E6420              | [2d61335a4c](https://linux-hardware.org/?probe=2d61335a4c) | Sep 02, 2020 |
| Acer          | Aspire VN7-592G             | [2eeaf6bdda](https://linux-hardware.org/?probe=2eeaf6bdda) | Sep 02, 2020 |
| Sony          | VGN-AW41ZF_B                | [84088f6217](https://linux-hardware.org/?probe=84088f6217) | Sep 01, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [f0392ec136](https://linux-hardware.org/?probe=f0392ec136) | Sep 01, 2020 |
| Toshiba       | Satellite C55-A-16D         | [ffb7e1e547](https://linux-hardware.org/?probe=ffb7e1e547) | Aug 31, 2020 |
| Lenovo        | V15-IWL 81YE                | [2e26a6fd67](https://linux-hardware.org/?probe=2e26a6fd67) | Aug 31, 2020 |
| Lenovo        | V15-IWL 81YE                | [6b077e7171](https://linux-hardware.org/?probe=6b077e7171) | Aug 31, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [448b7010bd](https://linux-hardware.org/?probe=448b7010bd) | Aug 29, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [0f60018033](https://linux-hardware.org/?probe=0f60018033) | Aug 28, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [6d902d850e](https://linux-hardware.org/?probe=6d902d850e) | Aug 28, 2020 |
| Dell          | G3 3579                     | [6a49371fb5](https://linux-hardware.org/?probe=6a49371fb5) | Aug 27, 2020 |
| Dell          | G3 3579                     | [0dbcb6c89c](https://linux-hardware.org/?probe=0dbcb6c89c) | Aug 27, 2020 |
| Apple         | MacBook2,1                  | [845d7083b8](https://linux-hardware.org/?probe=845d7083b8) | Aug 27, 2020 |
| HP            | Unknown                     | [d0efd61c2d](https://linux-hardware.org/?probe=d0efd61c2d) | Aug 25, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [a31f6d4a29](https://linux-hardware.org/?probe=a31f6d4a29) | Aug 25, 2020 |
| Lenovo        | G70-70 80HW                 | [fa6cb45c9b](https://linux-hardware.org/?probe=fa6cb45c9b) | Aug 24, 2020 |
| Hungaro Fl... | Navon Loop 360              | [55a00eeb5d](https://linux-hardware.org/?probe=55a00eeb5d) | Aug 23, 2020 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | [c7b50f684e](https://linux-hardware.org/?probe=c7b50f684e) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [96de1e7935](https://linux-hardware.org/?probe=96de1e7935) | Aug 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [42a29c8ce1](https://linux-hardware.org/?probe=42a29c8ce1) | Aug 22, 2020 |
| Lenovo        | G70-70 80HW                 | [97fd3ea86f](https://linux-hardware.org/?probe=97fd3ea86f) | Aug 18, 2020 |
| Lenovo        | G70-70 80HW                 | [ae00b8f92a](https://linux-hardware.org/?probe=ae00b8f92a) | Aug 18, 2020 |
| ASUSTek       | N56VB                       | [98b35742d1](https://linux-hardware.org/?probe=98b35742d1) | Aug 16, 2020 |
| Lenovo        | G510 20238                  | [0c2aa9c100](https://linux-hardware.org/?probe=0c2aa9c100) | Aug 16, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [e606d3b38d](https://linux-hardware.org/?probe=e606d3b38d) | Aug 13, 2020 |
| ASUSTek       | ASUSPRO P2540FAC_P2540FA    | [3a7aa036e3](https://linux-hardware.org/?probe=3a7aa036e3) | Aug 12, 2020 |
| Unknown       | Unknown                     | [ef5b05a658](https://linux-hardware.org/?probe=ef5b05a658) | Aug 12, 2020 |
| Acer          | Aspire A515-51G             | [045f3f0298](https://linux-hardware.org/?probe=045f3f0298) | Aug 10, 2020 |
| Toshiba       | Satellite L50-B             | [ee6cca4054](https://linux-hardware.org/?probe=ee6cca4054) | Aug 10, 2020 |
| Acer          | Extensa 5635ZG              | [e34aab5c40](https://linux-hardware.org/?probe=e34aab5c40) | Aug 10, 2020 |
| HP            | EliteBook 840 G3            | [1b5a9ac8fa](https://linux-hardware.org/?probe=1b5a9ac8fa) | Aug 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [bfce1a5904](https://linux-hardware.org/?probe=bfce1a5904) | Aug 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [966f3fe6a3](https://linux-hardware.org/?probe=966f3fe6a3) | Aug 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [af0796c69a](https://linux-hardware.org/?probe=af0796c69a) | Aug 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1a4de1242b](https://linux-hardware.org/?probe=1a4de1242b) | Aug 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [18baebae93](https://linux-hardware.org/?probe=18baebae93) | Aug 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [1204c0beec](https://linux-hardware.org/?probe=1204c0beec) | Aug 05, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2c3e9f51e5](https://linux-hardware.org/?probe=2c3e9f51e5) | Aug 05, 2020 |
| ASUSTek       | ASUSPRO P2540FAC_P2540FA    | [16345eadec](https://linux-hardware.org/?probe=16345eadec) | Aug 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [ce52dfcb6e](https://linux-hardware.org/?probe=ce52dfcb6e) | Aug 04, 2020 |
| Dell          | Inspiron 5558               | [41836e60d6](https://linux-hardware.org/?probe=41836e60d6) | Jul 31, 2020 |
| Unknown       | Unknown                     | [1046c4a095](https://linux-hardware.org/?probe=1046c4a095) | Jul 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [ed0bffa8e4](https://linux-hardware.org/?probe=ed0bffa8e4) | Jul 27, 2020 |
| Lenovo        | ThinkPad T470 20HDS07V00    | [3f62c519df](https://linux-hardware.org/?probe=3f62c519df) | Jul 24, 2020 |
| Acer          | Aspire E1-531               | [6104770d46](https://linux-hardware.org/?probe=6104770d46) | Jul 23, 2020 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | [fd2179a1f5](https://linux-hardware.org/?probe=fd2179a1f5) | Jul 23, 2020 |
| Dell          | Inspiron 3537               | [50a7e88fb1](https://linux-hardware.org/?probe=50a7e88fb1) | Jul 22, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [f144a6d038](https://linux-hardware.org/?probe=f144a6d038) | Jul 20, 2020 |
| Dell          | Latitude 5501               | [16c2224ca5](https://linux-hardware.org/?probe=16c2224ca5) | Jul 20, 2020 |
| Dell          | Latitude 5501               | [cc65eebb49](https://linux-hardware.org/?probe=cc65eebb49) | Jul 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [ac9895ec45](https://linux-hardware.org/?probe=ac9895ec45) | Jul 20, 2020 |
| HP            | Compaq nx7400 (RH387EA#A... | [dff9b522b5](https://linux-hardware.org/?probe=dff9b522b5) | Jul 19, 2020 |
| Toshiba       | Satellite P300              | [09001c1687](https://linux-hardware.org/?probe=09001c1687) | Jul 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [da2930279f](https://linux-hardware.org/?probe=da2930279f) | Jul 17, 2020 |
| HP            | ProBook 450 G6              | [fba6b3bdbc](https://linux-hardware.org/?probe=fba6b3bdbc) | Jul 15, 2020 |
| HP            | ProBook 450 G6              | [84ebe7a069](https://linux-hardware.org/?probe=84ebe7a069) | Jul 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [50932c1d96](https://linux-hardware.org/?probe=50932c1d96) | Jul 15, 2020 |
| ASUSTek       | GL552JX                     | [d34c14eba3](https://linux-hardware.org/?probe=d34c14eba3) | Jul 14, 2020 |
| ASUSTek       | GL552JX                     | [925e0dea47](https://linux-hardware.org/?probe=925e0dea47) | Jul 14, 2020 |
| ASUSTek       | X541UAK                     | [789952264e](https://linux-hardware.org/?probe=789952264e) | Jul 13, 2020 |
| Acer          | Aspire 7750G                | [901d2aad2d](https://linux-hardware.org/?probe=901d2aad2d) | Jul 12, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [a10a13d801](https://linux-hardware.org/?probe=a10a13d801) | Jul 12, 2020 |
| ASUSTek       | X541NA                      | [760dd006db](https://linux-hardware.org/?probe=760dd006db) | Jul 12, 2020 |
| HP            | ProBook 6555b               | [356a79988b](https://linux-hardware.org/?probe=356a79988b) | Jul 10, 2020 |
| HP            | ProBook 6555b               | [699cd52b2c](https://linux-hardware.org/?probe=699cd52b2c) | Jul 10, 2020 |
| HP            | EliteBook 820 G2            | [7518072c45](https://linux-hardware.org/?probe=7518072c45) | Jul 08, 2020 |
| Dell          | Latitude E6430              | [5146a82b91](https://linux-hardware.org/?probe=5146a82b91) | Jul 07, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Romania/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 136       | 12.29%  |
| Ubuntu 18.04      | 65        | 5.87%   |
| Ubuntu 22.04      | 34        | 3.07%   |
| BlackPanther 18.1 | 27        | 2.44%   |
| OpenMandriva 4.3  | 26        | 2.35%   |
| OpenMandriva 4.2  | 22        | 1.99%   |
| Pop!_OS 21.04     | 19        | 1.72%   |
| Ubuntu 21.10      | 18        | 1.63%   |
| KDE neon 20.04    | 17        | 1.54%   |
| Arch              | 17        | 1.54%   |
| ROSA R10          | 16        | 1.45%   |
| Endless 3.7.8     | 16        | 1.45%   |
| Zorin 15          | 15        | 1.36%   |
| Endless 3.9.5     | 15        | 1.36%   |
| Endless 3.9.1     | 15        | 1.36%   |
| Manjaro           | 13        | 1.17%   |
| Pop!_OS 20.04     | 12        | 1.08%   |
| Endless 3.8.6     | 12        | 1.08%   |
| Endless 3.8.0     | 12        | 1.08%   |
| Fedora 35         | 11        | 0.99%   |
| Debian 11         | 11        | 0.99%   |
| Zorin 16          | 10        | 0.9%    |
| Ubuntu 20.10      | 10        | 0.9%    |
| Ubuntu 19.10      | 10        | 0.9%    |
| Pop!_OS 22.04     | 10        | 0.9%    |
| Fedora 36         | 10        | 0.9%    |
| Fedora 34         | 10        | 0.9%    |
| Endless 3.9.0     | 10        | 0.9%    |
| Arch Rolling      | 10        | 0.9%    |
| Ubuntu 21.04      | 9         | 0.81%   |
| Ubuntu 19.04      | 9         | 0.81%   |
| Linux Mint 20.3   | 9         | 0.81%   |
| Endless 3.9.3     | 9         | 0.81%   |
| Endless 3.9.2     | 9         | 0.81%   |
| Endless 3.8.7     | 9         | 0.81%   |
| Endless 3.5.8     | 9         | 0.81%   |
| ArcoLinux Rolling | 9         | 0.81%   |
| Pop!_OS 20.10     | 8         | 0.72%   |
| Xubuntu 18.04     | 7         | 0.63%   |
| ROSA R9           | 7         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 293       | 28.87%  |
| Endless       | 206       | 20.3%   |
| OpenMandriva  | 55        | 5.42%   |
| Pop!_OS       | 53        | 5.22%   |
| Fedora        | 49        | 4.83%   |
| Linux Mint    | 47        | 4.63%   |
| ROSA          | 32        | 3.15%   |
| Manjaro       | 32        | 3.15%   |
| BlackPanther  | 28        | 2.76%   |
| Zorin         | 26        | 2.56%   |
| Arch          | 26        | 2.56%   |
| Debian        | 21        | 2.07%   |
| KDE neon      | 18        | 1.77%   |
| Kubuntu       | 14        | 1.38%   |
| Xubuntu       | 12        | 1.18%   |
| ArcoLinux     | 10        | 0.99%   |
| Kali          | 9         | 0.89%   |
| Ubuntu Unity  | 8         | 0.79%   |
| openSUSE      | 8         | 0.79%   |
| Elementary    | 8         | 0.79%   |
| Clear Linux   | 8         | 0.79%   |
| Ubuntu MATE   | 7         | 0.69%   |
| EndeavourOS   | 5         | 0.49%   |
| SteamOS       | 4         | 0.39%   |
| Peppermint    | 4         | 0.39%   |
| Linux Lite    | 4         | 0.39%   |
| Gentoo        | 4         | 0.39%   |
| LMDE          | 3         | 0.3%    |
| Garuda Linux  | 3         | 0.3%    |
| RHEL          | 2         | 0.2%    |
| Q4OS          | 2         | 0.2%    |
| MX            | 2         | 0.2%    |
| Lubuntu       | 2         | 0.2%    |
| Xero          | 1         | 0.1%    |
| Ubuntu Budgie | 1         | 0.1%    |
| Oracle Linux  | 1         | 0.1%    |
| Nobara        | 1         | 0.1%    |
| NixOS         | 1         | 0.1%    |
| Mageia        | 1         | 0.1%    |
| LinuxFX       | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-14-generic                | 55        | 4.83%   |
| 5.4.0-42-generic                | 39        | 3.43%   |
| 5.4.0-19-generic                | 26        | 2.28%   |
| 5.16.7-desktop-1omv4003         | 22        | 1.93%   |
| 5.10.14-desktop-1omv4002        | 22        | 1.93%   |
| 5.3.0-28-generic                | 21        | 1.85%   |
| 4.18.16-desktop-1bP             | 19        | 1.67%   |
| 4.18.0-15-generic               | 14        | 1.23%   |
| 5.3.0-23-generic                | 13        | 1.14%   |
| 5.11.0-35-generic               | 13        | 1.14%   |
| 5.0.0-25-generic                | 13        | 1.14%   |
| 5.0.0-20-generic                | 10        | 0.88%   |
| 4.15.0-15-generic               | 10        | 0.88%   |
| 5.3.0-46-generic                | 8         | 0.7%    |
| 5.15.0-52-generic               | 8         | 0.7%    |
| 5.13.0-7614-generic             | 8         | 0.7%    |
| 5.0.0-37-generic                | 8         | 0.7%    |
| 5.8.0-50-generic                | 7         | 0.62%   |
| 5.6.14-desktop-2bP              | 7         | 0.62%   |
| 5.4.0-56-generic                | 7         | 0.62%   |
| 5.4.0-54-generic                | 7         | 0.62%   |
| 5.4.0-40-generic                | 7         | 0.62%   |
| 5.4.0-26-generic                | 7         | 0.62%   |
| 5.3.0-51-generic                | 7         | 0.62%   |
| 5.3.0-19-generic                | 7         | 0.62%   |
| 5.3.0-12-generic                | 7         | 0.62%   |
| 5.15.0-48-generic               | 7         | 0.62%   |
| 5.11.0-7620-generic             | 7         | 0.62%   |
| 5.0.0-7-generic                 | 7         | 0.62%   |
| 5.4.0-37-generic                | 6         | 0.53%   |
| 5.4.0-31-generic                | 6         | 0.53%   |
| 5.4.0-29-generic                | 6         | 0.53%   |
| 5.3.0-40-generic                | 6         | 0.53%   |
| 5.11.0-43-generic               | 6         | 0.53%   |
| 5.0.0-15-generic                | 6         | 0.53%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 6         | 0.53%   |
| 4.13.0-32-generic               | 6         | 0.53%   |
| 5.8.0-7642-generic              | 5         | 0.44%   |
| 5.8.0-59-generic                | 5         | 0.44%   |
| 5.8.0-38-generic                | 5         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 197       | 18.09%  |
| 5.8.0   | 107       | 9.83%   |
| 5.3.0   | 87        | 7.99%   |
| 5.11.0  | 65        | 5.97%   |
| 5.0.0   | 63        | 5.79%   |
| 4.15.0  | 58        | 5.33%   |
| 5.15.0  | 52        | 4.78%   |
| 5.13.0  | 51        | 4.68%   |
| 4.18.0  | 40        | 3.67%   |
| 5.10.14 | 23        | 2.11%   |
| 5.16.7  | 22        | 2.02%   |
| 4.18.16 | 19        | 1.74%   |
| 5.10.0  | 15        | 1.38%   |
| 5.6.14  | 8         | 0.73%   |
| 5.19.0  | 8         | 0.73%   |
| 4.9.60  | 8         | 0.73%   |
| 4.9.20  | 8         | 0.73%   |
| 4.13.0  | 7         | 0.64%   |
| 4.19.0  | 6         | 0.55%   |
| 4.9.76  | 5         | 0.46%   |
| 5.9.0   | 4         | 0.37%   |
| 5.17.0  | 4         | 0.37%   |
| 5.16.13 | 4         | 0.37%   |
| 5.15.8  | 4         | 0.37%   |
| 6.0.7   | 3         | 0.28%   |
| 6.0.6   | 3         | 0.28%   |
| 6.0.0   | 3         | 0.28%   |
| 5.9.6   | 3         | 0.28%   |
| 5.9.16  | 3         | 0.28%   |
| 5.3.18  | 3         | 0.28%   |
| 5.19.3  | 3         | 0.28%   |
| 5.19.12 | 3         | 0.28%   |
| 5.18.12 | 3         | 0.28%   |
| 5.18.10 | 3         | 0.28%   |
| 5.18.0  | 3         | 0.28%   |
| 5.16.18 | 3         | 0.28%   |
| 5.15.32 | 3         | 0.28%   |
| 5.15.10 | 3         | 0.28%   |
| 5.1.15  | 3         | 0.28%   |
| 6.1.1   | 2         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 203       | 18.73%  |
| 5.8     | 120       | 11.07%  |
| 5.3     | 94        | 8.67%   |
| 5.15    | 77        | 7.1%    |
| 5.11    | 75        | 6.92%   |
| 5.0     | 65        | 6%      |
| 4.18    | 61        | 5.63%   |
| 4.15    | 58        | 5.35%   |
| 5.13    | 55        | 5.07%   |
| 5.10    | 53        | 4.89%   |
| 5.16    | 40        | 3.69%   |
| 4.9     | 27        | 2.49%   |
| 5.19    | 22        | 2.03%   |
| 5.6     | 16        | 1.48%   |
| 6.0     | 15        | 1.38%   |
| 5.9     | 15        | 1.38%   |
| 5.18    | 14        | 1.29%   |
| 5.17    | 14        | 1.29%   |
| 5.12    | 10        | 0.92%   |
| 5.14    | 9         | 0.83%   |
| 4.19    | 7         | 0.65%   |
| 4.13    | 7         | 0.65%   |
| 5.7     | 6         | 0.55%   |
| 5.5     | 5         | 0.46%   |
| 5.1     | 3         | 0.28%   |
| 4.1     | 3         | 0.28%   |
| 6.1     | 2         | 0.18%   |
| 5.2     | 2         | 0.18%   |
| 4.12    | 2         | 0.18%   |
| 4.8     | 1         | 0.09%   |
| 4.17    | 1         | 0.09%   |
| 4.16    | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 956       | 97.25%  |
| i686   | 27        | 2.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 517       | 50.94%  |
| KDE5            | 155       | 15.27%  |
| Unknown         | 147       | 14.48%  |
| XFCE            | 52        | 5.12%   |
| X-Cinnamon      | 33        | 3.25%   |
| KDE4            | 24        | 2.36%   |
| KDE             | 22        | 2.17%   |
| MATE            | 16        | 1.58%   |
| Unity           | 8         | 0.79%   |
| Pantheon        | 7         | 0.69%   |
| LXDE            | 7         | 0.69%   |
| Cinnamon        | 6         | 0.59%   |
| LXQt            | 4         | 0.39%   |
| i3              | 4         | 0.39%   |
| xmonad          | 2         | 0.2%    |
| GNOME Classic   | 2         | 0.2%    |
| Deepin          | 2         | 0.2%    |
| Budgie          | 2         | 0.2%    |
| sway            | 1         | 0.1%    |
| jwm             | 1         | 0.1%    |
| GNOME Flashback | 1         | 0.1%    |
| bspwm           | 1         | 0.1%    |
| awesome         | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 795       | 79.5%   |
| Unknown | 103       | 10.3%   |
| Wayland | 92        | 9.2%    |
| Tty     | 10        | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 595       | 58.56%  |
| SDDM    | 138       | 13.58%  |
| GDM     | 100       | 9.84%   |
| GDM3    | 73        | 7.19%   |
| LightDM | 59        | 5.81%   |
| TDM     | 24        | 2.36%   |
| KDM     | 23        | 2.26%   |
| XDM     | 2         | 0.2%    |
| SLiM    | 2         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 592       | 58.44%  |
| Unknown | 191       | 18.85%  |
| ro_RO   | 168       | 16.58%  |
| en_GB   | 16        | 1.58%   |
| C       | 15        | 1.48%   |
| it_IT   | 9         | 0.89%   |
| hu_HU   | 7         | 0.69%   |
| en_IL   | 3         | 0.3%    |
| es_ES   | 2         | 0.2%    |
| de_DE   | 2         | 0.2%    |
| ru_RU   | 1         | 0.1%    |
| fr_FR   | 1         | 0.1%    |
| fr_CH   | 1         | 0.1%    |
| en_IN   | 1         | 0.1%    |
| en_CA   | 1         | 0.1%    |
| en_AG   | 1         | 0.1%    |
| en_001  | 1         | 0.1%    |
| C.UTF8  | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 560       | 55.94%  |
| BIOS | 441       | 44.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 738       | 73.29%  |
| Unknown | 110       | 10.92%  |
| Overlay | 85        | 8.44%   |
| Btrfs   | 57        | 5.66%   |
| Tmpfs   | 7         | 0.7%    |
| Xfs     | 5         | 0.5%    |
| Zfs     | 2         | 0.2%    |
| Ext2    | 2         | 0.2%    |
| F2fs    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 627       | 62.83%  |
| GPT     | 261       | 26.15%  |
| MBR     | 110       | 11.02%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 884       | 88.76%  |
| Yes       | 112       | 11.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 742       | 74.27%  |
| Yes       | 257       | 25.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| ASUSTek Computer               | 288       | 29.33%  |
| Lenovo                         | 202       | 20.57%  |
| Dell                           | 134       | 13.65%  |
| Hewlett-Packard                | 129       | 13.14%  |
| Acer                           | 88        | 8.96%   |
| Toshiba                        | 21        | 2.14%   |
| MSI                            | 15        | 1.53%   |
| Sony                           | 10        | 1.02%   |
| Complet                        | 9         | 0.92%   |
| Medion                         | 8         | 0.81%   |
| HUAWEI                         | 8         | 0.81%   |
| Fujitsu Siemens                | 7         | 0.71%   |
| Apple                          | 7         | 0.71%   |
| Samsung Electronics            | 6         | 0.61%   |
| Unknown                        | 5         | 0.51%   |
| Valve                          | 4         | 0.41%   |
| Fujitsu                        | 4         | 0.41%   |
| Allview                        | 4         | 0.41%   |
| Packard Bell                   | 3         | 0.31%   |
| Chuwi                          | 3         | 0.31%   |
| Alienware                      | 3         | 0.31%   |
| TUXEDO                         | 2         | 0.2%    |
| Timi                           | 2         | 0.2%    |
| Visual Fan                     | 1         | 0.1%    |
| Thomson                        | 1         | 0.1%    |
| Prestigio                      | 1         | 0.1%    |
| Pegatron                       | 1         | 0.1%    |
| Panasonic                      | 1         | 0.1%    |
| Notebook                       | 1         | 0.1%    |
| nJoy Romania                   | 1         | 0.1%    |
| NEC Computers                  | 1         | 0.1%    |
| Mediacom                       | 1         | 0.1%    |
| Matsushita Electric Industrial | 1         | 0.1%    |
| Maguay                         | 1         | 0.1%    |
| LG Electronics                 | 1         | 0.1%    |
| IBM                            | 1         | 0.1%    |
| Hungaro Flotta Kft             | 1         | 0.1%    |
| Hampoo                         | 1         | 0.1%    |
| Gigabyte Technology            | 1         | 0.1%    |
| Fusion5                        | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| ASUS X541NA                                | 17        | 1.73%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 16        | 1.63%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 10        | 1.02%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA     | 9         | 0.92%   |
| Unknown                                    | 8         | 0.81%   |
| Dell XPS 15 9530                           | 7         | 0.71%   |
| Complet MY8312                             | 7         | 0.71%   |
| Lenovo Legion Y530-15ICH 81FV              | 6         | 0.61%   |
| ASUS X406UAR                               | 6         | 0.61%   |
| ASUS VivoBook_ASUSLaptop X509FB_X509FB     | 6         | 0.61%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_A540MA | 6         | 0.61%   |
| Lenovo V330-15IKB 81AX                     | 5         | 0.51%   |
| ASUS X541UVK                               | 5         | 0.51%   |
| ASUS X541UAK                               | 5         | 0.51%   |
| ASUS VivoBook_ASUS Laptop X505ZA_A505ZA    | 5         | 0.51%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 5         | 0.51%   |
| Valve Jupiter                              | 4         | 0.41%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 4         | 0.41%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 4         | 0.41%   |
| Lenovo G510 20238                          | 4         | 0.41%   |
| HP Notebook                                | 4         | 0.41%   |
| Dell Latitude E6410                        | 4         | 0.41%   |
| Dell Inspiron 5558                         | 4         | 0.41%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.41%   |
| ASUS X542UAR                               | 4         | 0.41%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA     | 4         | 0.41%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA     | 4         | 0.41%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 4         | 0.41%   |
| ASUS GL552JX                               | 4         | 0.41%   |
| Acer Aspire E5-573G                        | 4         | 0.41%   |
| Acer Aspire E1-531                         | 4         | 0.41%   |
| Acer Aspire A315-21G                       | 4         | 0.41%   |
| Lenovo V110-15ISK 80TL                     | 3         | 0.31%   |
| Lenovo ThinkPad E14 Gen 2 20TA002GRI       | 3         | 0.31%   |
| Lenovo IdeaPad L340-17API 81LY             | 3         | 0.31%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 3         | 0.31%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7           | 3         | 0.31%   |
| Lenovo IdeaPad 320-15ISK 80XH              | 3         | 0.31%   |
| Lenovo G50-70 20351                        | 3         | 0.31%   |
| HP Pavilion dv6                            | 3         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| ASUS VivoBook           | 109       | 11.1%   |
| Lenovo IdeaPad          | 73        | 7.43%   |
| Lenovo ThinkPad         | 68        | 6.92%   |
| Acer Aspire             | 63        | 6.42%   |
| Dell Latitude           | 51        | 5.19%   |
| Dell Inspiron           | 38        | 3.87%   |
| HP EliteBook            | 27        | 2.75%   |
| HP ProBook              | 26        | 2.65%   |
| Toshiba Satellite       | 20        | 2.04%   |
| Lenovo Legion           | 17        | 1.73%   |
| HP Pavilion             | 17        | 1.73%   |
| Dell XPS                | 17        | 1.73%   |
| ASUS X541NA             | 17        | 1.73%   |
| HP Laptop               | 15        | 1.53%   |
| ASUS ROG                | 14        | 1.43%   |
| ASUS ASUS               | 13        | 1.32%   |
| Dell Vostro             | 10        | 1.02%   |
| ASUS ZenBook            | 10        | 1.02%   |
| ASUS TUF                | 9         | 0.92%   |
| Unknown                 | 8         | 0.81%   |
| Lenovo ThinkBook        | 7         | 0.71%   |
| Complet MY8312          | 7         | 0.71%   |
| Acer Extensa            | 7         | 0.71%   |
| HP ZBook                | 6         | 0.61%   |
| Dell System             | 6         | 0.61%   |
| ASUS X406UAR            | 6         | 0.61%   |
| Acer Swift              | 6         | 0.61%   |
| Acer Nitro              | 6         | 0.61%   |
| Lenovo V330-15IKB       | 5         | 0.51%   |
| HP 250                  | 5         | 0.51%   |
| ASUS X541UVK            | 5         | 0.51%   |
| ASUS X541UAK            | 5         | 0.51%   |
| Valve Jupiter           | 4         | 0.41%   |
| Lenovo G510             | 4         | 0.41%   |
| HP Notebook             | 4         | 0.41%   |
| HP ENVY                 | 4         | 0.41%   |
| HP Compaq               | 4         | 0.41%   |
| Fujitsu Siemens ESPRIMO | 4         | 0.41%   |
| Fujitsu LIFEBOOK        | 4         | 0.41%   |
| Dell Precision          | 4         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 151       | 15.38%  |
| 2018    | 109       | 11.1%   |
| 2017    | 98        | 9.98%   |
| 2020    | 79        | 8.04%   |
| 2015    | 68        | 6.92%   |
| 2021    | 64        | 6.52%   |
| 2013    | 60        | 6.11%   |
| 2011    | 57        | 5.8%    |
| 2014    | 54        | 5.5%    |
| 2012    | 50        | 5.09%   |
| 2010    | 45        | 4.58%   |
| 2016    | 36        | 3.67%   |
| 2008    | 31        | 3.16%   |
| 2007    | 27        | 2.75%   |
| 2009    | 25        | 2.55%   |
| 2022    | 14        | 1.43%   |
| 2006    | 11        | 1.12%   |
| 2005    | 1         | 0.1%    |
| 2004    | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 982       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 928       | 93.83%  |
| Enabled  | 61        | 6.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 982       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 324       | 32.46%  |
| 4.01-8.0    | 268       | 26.85%  |
| 8.01-16.0   | 153       | 15.33%  |
| 16.01-24.0  | 141       | 14.13%  |
| 1.01-2.0    | 44        | 4.41%   |
| 32.01-64.0  | 37        | 3.71%   |
| 2.01-3.0    | 13        | 1.3%    |
| 0.51-1.0    | 8         | 0.8%    |
| 24.01-32.0  | 6         | 0.6%    |
| 64.01-256.0 | 4         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 451       | 41.15%  |
| 2.01-3.0   | 261       | 23.81%  |
| 3.01-4.0   | 121       | 11.04%  |
| 0.51-1.0   | 118       | 10.77%  |
| 4.01-8.0   | 105       | 9.58%   |
| 8.01-16.0  | 25        | 2.28%   |
| 0.01-0.5   | 13        | 1.19%   |
| 32.01-64.0 | 1         | 0.09%   |
| 24.01-32.0 | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 771       | 77.1%   |
| 2      | 198       | 19.8%   |
| 3      | 23        | 2.3%    |
| 0      | 6         | 0.6%    |
| 5      | 1         | 0.1%    |
| 4      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 614       | 62.15%  |
| Yes       | 374       | 37.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 738       | 75.08%  |
| No        | 245       | 24.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 975       | 99.09%  |
| No        | 9         | 0.91%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 787       | 79.25%  |
| No        | 206       | 20.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Romania | 982       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Bucharest             | 325       | 30.89%  |
| Cluj-Napoca           | 73        | 6.94%   |
| Iasi                  | 52        | 4.94%   |
| Timișoara            | 35        | 3.33%   |
| Târgu Mureş         | 32        | 3.04%   |
| Ploieşti             | 31        | 2.95%   |
| Brasov                | 29        | 2.76%   |
| Constanța            | 22        | 2.09%   |
| Piteşti              | 17        | 1.62%   |
| Sibiu                 | 14        | 1.33%   |
| Arad                  | 14        | 1.33%   |
| Popesti-Leordeni      | 13        | 1.24%   |
| Oradea                | 13        | 1.24%   |
| Craiova               | 12        | 1.14%   |
| Voluntari             | 10        | 0.95%   |
| Râmnicu Vâlcea      | 10        | 0.95%   |
| Zalău                | 9         | 0.86%   |
| Miercurea-Ciuc        | 9         | 0.86%   |
| Botosani              | 9         | 0.86%   |
| Baia Mare             | 9         | 0.86%   |
| Galati                | 8         | 0.76%   |
| Floresti              | 8         | 0.76%   |
| Bacau                 | 8         | 0.76%   |
| Reşiţa              | 7         | 0.67%   |
| Mediaş               | 6         | 0.57%   |
| Focşani              | 6         | 0.57%   |
| Drobeta-Turnu Severin | 6         | 0.57%   |
| Deva                  | 6         | 0.57%   |
| Braila                | 6         | 0.57%   |
| Tulcea                | 5         | 0.48%   |
| Târgu Jiu            | 5         | 0.48%   |
| Targoviste            | 5         | 0.48%   |
| Slatina               | 5         | 0.48%   |
| Iorcani               | 5         | 0.48%   |
| Alba Iulia            | 5         | 0.48%   |
| Suceava               | 4         | 0.38%   |
| Sfantu Gheorghe       | 4         | 0.38%   |
| Sector 1              | 4         | 0.38%   |
| Satu Mare             | 4         | 0.38%   |
| Roman                 | 4         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 154       | 205    | 12.85%  |
| Samsung Electronics         | 151       | 182    | 12.6%   |
| WDC                         | 140       | 164    | 11.69%  |
| Kingston                    | 129       | 160    | 10.77%  |
| Toshiba                     | 115       | 140    | 9.6%    |
| SanDisk                     | 64        | 72     | 5.34%   |
| Unknown                     | 53        | 72     | 4.42%   |
| Intel                       | 53        | 68     | 4.42%   |
| SK hynix                    | 51        | 73     | 4.26%   |
| HGST                        | 47        | 54     | 3.92%   |
| A-DATA Technology           | 37        | 41     | 3.09%   |
| Hitachi                     | 34        | 37     | 2.84%   |
| Micron Technology           | 33        | 39     | 2.75%   |
| Crucial                     | 13        | 16     | 1.09%   |
| Phison                      | 10        | 11     | 0.83%   |
| Patriot                     | 9         | 9      | 0.75%   |
| FORESEE                     | 9         | 10     | 0.75%   |
| KIOXIA                      | 7         | 7      | 0.58%   |
| SPCC                        | 6         | 7      | 0.5%    |
| Corsair                     | 6         | 7      | 0.5%    |
| Fujitsu                     | 5         | 6      | 0.42%   |
| Netac                       | 4         | 6      | 0.33%   |
| XPG                         | 3         | 4      | 0.25%   |
| Realtek Semiconductor       | 3         | 3      | 0.25%   |
| OCZ                         | 3         | 5      | 0.25%   |
| LITEON                      | 3         | 3      | 0.25%   |
| Kingston Technology Company | 3         | 3      | 0.25%   |
| Hewlett-Packard             | 3         | 3      | 0.25%   |
| Gigabyte Technology         | 3         | 3      | 0.25%   |
| Apple                       | 3         | 3      | 0.25%   |
| Unknown                     | 3         | 3      | 0.25%   |
| Teclast                     | 2         | 2      | 0.17%   |
| SSSTC                       | 2         | 2      | 0.17%   |
| Phison Electronics          | 2         | 2      | 0.17%   |
| LITEONIT                    | 2         | 2      | 0.17%   |
| Lite-On                     | 2         | 2      | 0.17%   |
| Lenovo                      | 2         | 2      | 0.17%   |
| KESU                        | 2         | 2      | 0.17%   |
| IBM/Hitachi                 | 2         | 2      | 0.17%   |
| China                       | 2         | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                            | 43        | 3.5%    |
| Seagate ST1000LM035-1RK172 1TB                      | 38        | 3.09%   |
| Seagate ST500LT012-1DG142 500GB                     | 25        | 2.04%   |
| Toshiba MQ04ABF100 1TB                              | 21        | 1.71%   |
| Kingston SA400S37240G 240GB SSD                     | 21        | 1.71%   |
| HGST HTS721010A9E630 1TB                            | 18        | 1.47%   |
| SanDisk NVMe SSD Drive 256GB                        | 17        | 1.38%   |
| Samsung NVMe SSD Drive 512GB                        | 17        | 1.38%   |
| Unknown MMC Card  32GB                              | 16        | 1.3%    |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 1.14%   |
| Kingston SA400S37480G 480GB SSD                     | 13        | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 12        | 0.98%   |
| SK hynix NVMe SSD Drive 512GB                       | 11        | 0.9%    |
| Kingston SV300S37A240G 240GB SSD                    | 10        | 0.81%   |
| Intel NVMe SSD Drive 512GB                          | 10        | 0.81%   |
| Toshiba MQ01ABD100 1TB                              | 9         | 0.73%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 9         | 0.73%   |
| HGST HTS545050A7E680 500GB                          | 9         | 0.73%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 8         | 0.65%   |
| Kingston SUV500MS480G 480GB SSD                     | 8         | 0.65%   |
| Kingston RBUSNS8180DS3256GJ 256GB SSD               | 8         | 0.65%   |
| HGST HTS541010A9E680 1TB                            | 8         | 0.65%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 7         | 0.57%   |
| Seagate ST9500325AS 500GB                           | 7         | 0.57%   |
| Seagate ST2000LM007-1R8174 2TB                      | 7         | 0.57%   |
| Kingston SUV400S37120G 120GB SSD                    | 7         | 0.57%   |
| Kingston SA400S37120G 120GB SSD                     | 7         | 0.57%   |
| Kingston RBUSC180DS37256GJ 256GB SSD                | 7         | 0.57%   |
| Intel NVMe SSD Drive 256GB                          | 7         | 0.57%   |
| Hitachi HTS725032A7E630 320GB                       | 7         | 0.57%   |
| FORESEE 256GB SSD                                   | 7         | 0.57%   |
| Unknown MMC Card  64GB                              | 6         | 0.49%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 6         | 0.49%   |
| Seagate Expansion 4TB                               | 6         | 0.49%   |
| Samsung SSD 860 EVO 500GB                           | 6         | 0.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 6         | 0.49%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 6         | 0.49%   |
| Kingston SV300S37A120G 120GB SSD                    | 6         | 0.49%   |
| SK hynix NVMe SSD Drive 256GB                       | 5         | 0.41%   |
| SK hynix HFM001TD3JX013N 1TB                        | 5         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 154       | 205    | 34.22%  |
| WDC                 | 101       | 121    | 22.44%  |
| Toshiba             | 96        | 119    | 21.33%  |
| HGST                | 47        | 54     | 10.44%  |
| Hitachi             | 34        | 37     | 7.56%   |
| Fujitsu             | 5         | 6      | 1.11%   |
| Samsung Electronics | 4         | 4      | 0.89%   |
| Unknown             | 3         | 3      | 0.67%   |
| IBM/Hitachi         | 2         | 2      | 0.44%   |
| ASMT                | 2         | 2      | 0.44%   |
| HGST HTS            | 1         | 1      | 0.22%   |
| Apple               | 1         | 1      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 110       | 140    | 29.57%  |
| Samsung Electronics | 63        | 81     | 16.94%  |
| A-DATA Technology   | 33        | 37     | 8.87%   |
| SanDisk             | 26        | 31     | 6.99%   |
| SK hynix            | 16        | 24     | 4.3%    |
| Micron Technology   | 14        | 15     | 3.76%   |
| Intel               | 13        | 14     | 3.49%   |
| Crucial             | 13        | 16     | 3.49%   |
| WDC                 | 12        | 12     | 3.23%   |
| FORESEE             | 9         | 10     | 2.42%   |
| Patriot             | 8         | 8      | 2.15%   |
| Toshiba             | 7         | 7      | 1.88%   |
| SPCC                | 6         | 7      | 1.61%   |
| Corsair             | 5         | 6      | 1.34%   |
| Netac               | 4         | 6      | 1.08%   |
| OCZ                 | 3         | 5      | 0.81%   |
| LITEON              | 3         | 3      | 0.81%   |
| Hewlett-Packard     | 3         | 3      | 0.81%   |
| Gigabyte Technology | 3         | 3      | 0.81%   |
| Teclast             | 2         | 2      | 0.54%   |
| LITEONIT            | 2         | 2      | 0.54%   |
| Lite-On             | 2         | 2      | 0.54%   |
| China               | 2         | 2      | 0.54%   |
| Apacer              | 2         | 2      | 0.54%   |
| W800S               | 1         | 1      | 0.27%   |
| Verbatim            | 1         | 1      | 0.27%   |
| Unknown             | 1         | 1      | 0.27%   |
| TO Exter            | 1         | 3      | 0.27%   |
| PNY                 | 1         | 2      | 0.27%   |
| Maxtor              | 1         | 1      | 0.27%   |
| Kingmax             | 1         | 1      | 0.27%   |
| GOODRAM             | 1         | 1      | 0.27%   |
| Emtec               | 1         | 1      | 0.27%   |
| ASUS-PHISON         | 1         | 2      | 0.27%   |
| Unknown             | 1         | 1      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 440       | 555    | 38.33%  |
| SSD     | 351       | 453    | 30.57%  |
| NVMe    | 300       | 375    | 26.13%  |
| MMC     | 48        | 67     | 4.18%   |
| Unknown | 9         | 11     | 0.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 699       | 981    | 64.72%  |
| NVMe | 300       | 374    | 27.78%  |
| MMC  | 48        | 67     | 4.44%   |
| SAS  | 33        | 39     | 3.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 519       | 691    | 67.67%  |
| 0.51-1.0   | 222       | 272    | 28.94%  |
| 1.01-2.0   | 20        | 37     | 2.61%   |
| 3.01-4.0   | 6         | 8      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 304       | 29.4%   |
| 251-500        | 271       | 26.21%  |
| 501-1000       | 160       | 15.47%  |
| 1-20           | 91        | 8.8%    |
| 51-100         | 63        | 6.09%   |
| 21-50          | 51        | 4.93%   |
| 1001-2000      | 40        | 3.87%   |
| Unknown        | 33        | 3.19%   |
| 2001-3000      | 12        | 1.16%   |
| More than 3000 | 9         | 0.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 435       | 40.65%  |
| 21-50          | 252       | 23.55%  |
| 101-250        | 125       | 11.68%  |
| 51-100         | 115       | 10.75%  |
| 251-500        | 53        | 4.95%   |
| 501-1000       | 39        | 3.64%   |
| Unknown        | 33        | 3.08%   |
| 1001-2000      | 16        | 1.5%    |
| More than 3000 | 2         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Hitachi HTS725032A7E630 320GB                    | 7         | 7      | 9.59%   |
| HGST HTS541010A9E680 1TB                         | 4         | 4      | 5.48%   |
| Seagate ST9500420AS 500GB                        | 3         | 3      | 4.11%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD         | 2         | 2      | 2.74%   |
| Seagate ST95005620AS 500GB                       | 2         | 5      | 2.74%   |
| Seagate ST9500325AS 500GB                        | 2         | 2      | 2.74%   |
| Seagate ST9160821AS 160GB                        | 2         | 2      | 2.74%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 3      | 2.74%   |
| Hitachi HTS545016B9A300 160GB                    | 2         | 2      | 2.74%   |
| HGST HTS725050A7E630 500GB                       | 2         | 2      | 2.74%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 2.74%   |
| WDC WD7500BPVT-60HXZT3 752GB                     | 1         | 2      | 1.37%   |
| WDC WD7500BPVT-22HXZT3 752GB                     | 1         | 1      | 1.37%   |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 1.37%   |
| WDC WD5000BPKT-60PK4T0 500GB                     | 1         | 2      | 1.37%   |
| WDC WD5000BEVT-60A0RT0 500GB                     | 1         | 1      | 1.37%   |
| WDC WD3200BPVT-22JJ5T0 320GB                     | 1         | 1      | 1.37%   |
| WDC WD1600BEVS-07RST0 160GB                      | 1         | 1      | 1.37%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 1.37%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 1.37%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.37%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 1.37%   |
| Toshiba MK6476GSX 640GB                          | 1         | 1      | 1.37%   |
| Toshiba MK5076GSX 500GB                          | 1         | 1      | 1.37%   |
| Toshiba MK3252GSX 320GB                          | 1         | 2      | 1.37%   |
| Toshiba MK2556GSY 250GB                          | 1         | 1      | 1.37%   |
| Toshiba MK2035GSS 200GB                          | 1         | 1      | 1.37%   |
| Teclast 360GB A850 SSD                           | 1         | 1      | 1.37%   |
| SK hynix SC210 2.5 7MM 256GB SSD                 | 1         | 1      | 1.37%   |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 1         | 1      | 1.37%   |
| SK hynix HFS128G32TND-N210A 128GB SSD            | 1         | 1      | 1.37%   |
| Seagate ST9250320AS 250GB                        | 1         | 1      | 1.37%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 2      | 1.37%   |
| Seagate ST2000LM007-1R8174 2TB                   | 1         | 1      | 1.37%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 1.37%   |
| Seagate ST1000LM014-1EJ164 1TB                   | 1         | 1      | 1.37%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 1.37%   |
| Samsung Electronics MZMPA128HMFU-000H1 128GB SSD | 1         | 1      | 1.37%   |
| Patriot P200 256GB SSD                           | 1         | 1      | 1.37%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD   | 1         | 1      | 1.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 21     | 22.54%  |
| Hitachi             | 14        | 16     | 19.72%  |
| WDC                 | 10        | 12     | 14.08%  |
| HGST                | 10        | 10     | 14.08%  |
| Toshiba             | 8         | 9      | 11.27%  |
| SK hynix            | 3         | 3      | 4.23%   |
| Kingston            | 2         | 2      | 2.82%   |
| Fujitsu             | 2         | 2      | 2.82%   |
| Teclast             | 1         | 1      | 1.41%   |
| SanDisk             | 1         | 1      | 1.41%   |
| Samsung Electronics | 1         | 1      | 1.41%   |
| Patriot             | 1         | 1      | 1.41%   |
| Micron Technology   | 1         | 1      | 1.41%   |
| LITEONIT            | 1         | 1      | 1.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 21     | 27.59%  |
| Hitachi | 14        | 16     | 24.14%  |
| HGST    | 10        | 10     | 17.24%  |
| WDC     | 8         | 10     | 13.79%  |
| Toshiba | 8         | 9      | 13.79%  |
| Fujitsu | 2         | 2      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 58        | 68     | 81.69%  |
| SSD  | 13        | 13     | 18.31%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60KA9T0 320GB | 1         | 1      | 50%     |
| WDC WD2500BEVS-22UST0 250GB  | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 670       | 978    | 63.99%  |
| Works    | 304       | 400    | 29.04%  |
| Malfunc  | 71        | 81     | 6.78%   |
| Failed   | 2         | 2      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 778       | 66.78%  |
| AMD                              | 98        | 8.41%   |
| Samsung Electronics              | 90        | 7.73%   |
| SanDisk                          | 61        | 5.24%   |
| SK hynix                         | 34        | 2.92%   |
| Kingston Technology Company      | 23        | 1.97%   |
| Micron Technology                | 19        | 1.63%   |
| Toshiba America Info Systems     | 12        | 1.03%   |
| Phison Electronics               | 11        | 0.94%   |
| KIOXIA                           | 9         | 0.77%   |
| ADATA Technology                 | 7         | 0.6%    |
| Realtek Semiconductor            | 6         | 0.52%   |
| Silicon Integrated Systems [SiS] | 4         | 0.34%   |
| Solid State Storage Technology   | 2         | 0.17%   |
| Silicon Motion                   | 2         | 0.17%   |
| Nvidia                           | 2         | 0.17%   |
| Lenovo                           | 2         | 0.17%   |
| JMicron Technology               | 2         | 0.17%   |
| VIA Technologies                 | 1         | 0.09%   |
| Silicon Image                    | 1         | 0.09%   |
| Lite-On Technology               | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 90        | 7.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 84        | 6.66%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 84        | 6.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 54        | 4.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 53        | 4.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 46        | 3.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 45        | 3.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 44        | 3.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 39        | 3.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 35        | 2.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 32        | 2.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 31        | 2.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 28        | 2.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 28        | 2.22%   |
| Samsung NVMe SSD Controller 980                                                  | 27        | 2.14%   |
| Intel Volume Management Device NVMe RAID Controller                              | 27        | 2.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 22        | 1.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 20        | 1.58%   |
| Micron Non-Volatile memory controller                                            | 19        | 1.51%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 19        | 1.51%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 18        | 1.43%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 18        | 1.43%   |
| Intel SSD 660P Series                                                            | 18        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 18        | 1.43%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 14        | 1.11%   |
| Intel Tiger Lake-LP SATA Controller                                              | 14        | 1.11%   |
| Intel Comet Lake SATA AHCI Controller                                            | 14        | 1.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 14        | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 11        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11        | 0.87%   |
| SanDisk Non-Volatile memory controller                                           | 10        | 0.79%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 9         | 0.71%   |
| Intel Non-Volatile memory controller                                             | 9         | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 0.71%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 9         | 0.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 9         | 0.71%   |
| SanDisk PC SN520 NVMe SSD                                                        | 8         | 0.63%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 7         | 0.55%   |
| Kingston Company Company Non-Volatile memory controller                          | 7         | 0.55%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 7         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 733       | 60.08%  |
| NVMe | 303       | 24.84%  |
| RAID | 113       | 9.26%   |
| IDE  | 71        | 5.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 838       | 85.34%  |
| AMD    | 144       | 14.66%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 39        | 3.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 2.54%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 24        | 2.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 21        | 2.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 18        | 1.83%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 17        | 1.73%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 15        | 1.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 1.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 1.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.22%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 1.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 1.22%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 11        | 1.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 1.12%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 10        | 1.02%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 9         | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 0.92%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.92%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 9         | 0.92%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 9         | 0.92%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 9         | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.81%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 8         | 0.81%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 8         | 0.81%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 7         | 0.71%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 7         | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 0.71%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 7         | 0.71%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.71%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 7         | 0.71%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 0.71%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 6         | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 6         | 0.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 6         | 0.61%   |
| Intel Celeron N4000C CPU @ 1.10GHz            | 6         | 0.61%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.61%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 236       | 24.01%  |
| Intel Core i5                  | 204       | 20.75%  |
| Intel Core i3                  | 115       | 11.7%   |
| Intel Celeron                  | 107       | 10.89%  |
| Other                          | 58        | 5.9%    |
| AMD Ryzen 5                    | 44        | 4.48%   |
| Intel Core 2 Duo               | 42        | 4.27%   |
| AMD Ryzen 7                    | 34        | 3.46%   |
| Intel Pentium                  | 33        | 3.36%   |
| Intel Atom                     | 15        | 1.53%   |
| Intel Pentium Dual-Core        | 8         | 0.81%   |
| AMD Ryzen 3                    | 8         | 0.81%   |
| Intel Core 2                   | 7         | 0.71%   |
| AMD A4                         | 7         | 0.71%   |
| Intel Genuine                  | 6         | 0.61%   |
| AMD E2                         | 5         | 0.51%   |
| AMD E                          | 5         | 0.51%   |
| Intel Pentium Dual             | 4         | 0.41%   |
| Intel Celeron M                | 4         | 0.41%   |
| AMD Ryzen 9                    | 4         | 0.41%   |
| AMD Athlon                     | 4         | 0.41%   |
| Intel Core i9                  | 3         | 0.31%   |
| AMD Ryzen 7 PRO                | 3         | 0.31%   |
| AMD A8                         | 3         | 0.31%   |
| Intel Core Duo                 | 2         | 0.2%    |
| AMD V140                       | 2         | 0.2%    |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.2%    |
| AMD A6                         | 2         | 0.2%    |
| AMD A10                        | 2         | 0.2%    |
| Intel Pentium M                | 1         | 0.1%    |
| Intel Mobile Pentium 4         | 1         | 0.1%    |
| Intel Core 2 Extreme           | 1         | 0.1%    |
| Intel Celeron Dual-Core        | 1         | 0.1%    |
| AMD Turion 64 X2 Mobile        | 1         | 0.1%    |
| AMD Turion 64 Mobile           | 1         | 0.1%    |
| AMD Phenom II                  | 1         | 0.1%    |
| AMD Mobile Sempron             | 1         | 0.1%    |
| AMD FX                         | 1         | 0.1%    |
| AMD E1                         | 1         | 0.1%    |
| AMD C-50                       | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 527       | 53.67%  |
| 4      | 314       | 31.98%  |
| 6      | 66        | 6.72%   |
| 8      | 50        | 5.09%   |
| 1      | 21        | 2.14%   |
| 14     | 3         | 0.31%   |
| 12     | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 982       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 707       | 71.92%  |
| 1      | 276       | 28.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 909       | 92.19%  |
| Unknown        | 65        | 6.59%   |
| 32-bit         | 12        | 1.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 166       | 16.52%  |
| 0x206a7    | 53        | 5.27%   |
| 0x806ec    | 51        | 5.07%   |
| 0x806ea    | 48        | 4.78%   |
| 0x306a9    | 46        | 4.58%   |
| 0x706a1    | 44        | 4.38%   |
| 0x306c3    | 37        | 3.68%   |
| 0x40651    | 36        | 3.58%   |
| 0x906ea    | 34        | 3.38%   |
| 0x506c9    | 30        | 2.99%   |
| 0x806e9    | 26        | 2.59%   |
| 0x806c1    | 26        | 2.59%   |
| 0x306d4    | 26        | 2.59%   |
| 0x20655    | 26        | 2.59%   |
| 0x1067a    | 24        | 2.39%   |
| 0x406e3    | 21        | 2.09%   |
| 0x906e9    | 19        | 1.89%   |
| 0x806eb    | 19        | 1.89%   |
| 0x706e5    | 16        | 1.59%   |
| 0x08108102 | 16        | 1.59%   |
| 0x0a50000c | 15        | 1.49%   |
| 0x08108109 | 14        | 1.39%   |
| 0xa0652    | 13        | 1.29%   |
| 0x506e3    | 13        | 1.29%   |
| 0x10676    | 12        | 1.19%   |
| 0x6fd      | 11        | 1.09%   |
| 0x08600104 | 10        | 1%      |
| 0x906ed    | 9         | 0.9%    |
| 0x406c3    | 9         | 0.9%    |
| 0x806d1    | 8         | 0.8%    |
| 0x406c4    | 8         | 0.8%    |
| 0x706a8    | 6         | 0.6%    |
| 0x20652    | 6         | 0.6%    |
| 0x106ca    | 6         | 0.6%    |
| 0x0810100b | 6         | 0.6%    |
| 0x6f6      | 5         | 0.5%    |
| 0x6e8      | 5         | 0.5%    |
| 0x30678    | 5         | 0.5%    |
| 0x08600106 | 5         | 0.5%    |
| 0x08101007 | 5         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 231       | 23.52%  |
| Haswell          | 88        | 8.96%   |
| SandyBridge      | 62        | 6.31%   |
| Goldmont plus    | 54        | 5.5%    |
| IvyBridge        | 51        | 5.19%   |
| Skylake          | 42        | 4.28%   |
| Westmere         | 40        | 4.07%   |
| Penryn           | 38        | 3.87%   |
| Zen+             | 36        | 3.67%   |
| Goldmont         | 35        | 3.56%   |
| Broadwell        | 35        | 3.56%   |
| TigerLake        | 32        | 3.26%   |
| Core             | 31        | 3.16%   |
| Silvermont       | 25        | 2.55%   |
| IceLake          | 25        | 2.55%   |
| Zen 3            | 21        | 2.14%   |
| Zen 2            | 21        | 2.14%   |
| Unknown          | 18        | 1.83%   |
| CometLake        | 16        | 1.63%   |
| Zen              | 12        | 1.22%   |
| Excavator        | 12        | 1.22%   |
| P6               | 10        | 1.02%   |
| Bonnell          | 9         | 0.92%   |
| Bobcat           | 7         | 0.71%   |
| Puma             | 6         | 0.61%   |
| K10              | 4         | 0.41%   |
| Piledriver       | 3         | 0.31%   |
| Nehalem          | 3         | 0.31%   |
| K8 Hammer        | 3         | 0.31%   |
| K8 & K10 hybrid  | 3         | 0.31%   |
| K10 Llano        | 2         | 0.2%    |
| Jaguar           | 2         | 0.2%    |
| Alderlake Hybrid | 2         | 0.2%    |
| Tremont          | 1         | 0.1%    |
| Steamroller      | 1         | 0.1%    |
| NetBurst         | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 771       | 59.08%  |
| Nvidia                           | 312       | 23.91%  |
| AMD                              | 217       | 16.63%  |
| Silicon Integrated Systems [SiS] | 4         | 0.31%   |
| VIA Technologies                 | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 56        | 4.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 54        | 4.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 53        | 3.94%   |
| Intel UHD Graphics 620                                                                   | 47        | 3.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 3.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 46        | 3.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 42        | 3.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 40        | 2.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 36        | 2.68%   |
| Intel HD Graphics 5500                                                                   | 34        | 2.53%   |
| Intel HD Graphics 620                                                                    | 32        | 2.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 32        | 2.38%   |
| Intel HD Graphics 500                                                                    | 25        | 1.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 24        | 1.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 1.49%   |
| AMD Renoir                                                                               | 20        | 1.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 1.41%   |
| Intel HD Graphics 630                                                                    | 19        | 1.41%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 19        | 1.41%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 17        | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 16        | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 16        | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 1.12%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 15        | 1.12%   |
| Intel HD Graphics 530                                                                    | 15        | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 1.04%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 14        | 1.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 0.97%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 12        | 0.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 12        | 0.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12        | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.82%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 11        | 0.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 11        | 0.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 0.82%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 10        | 0.74%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 0.74%   |
| Nvidia GM108M [GeForce MX110]                                                            | 10        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 477       | 48.48%  |
| Intel + Nvidia | 243       | 24.7%   |
| 1 x AMD        | 126       | 12.8%   |
| Intel + AMD    | 51        | 5.18%   |
| 1 x Nvidia     | 42        | 4.27%   |
| AMD + Nvidia   | 27        | 2.74%   |
| 2 x AMD        | 13        | 1.32%   |
| 1 x SiS        | 4         | 0.41%   |
| 1 x VIA        | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 793       | 80.34%  |
| Proprietary | 178       | 18.03%  |
| Unknown     | 16        | 1.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 597       | 59.4%   |
| 1.01-2.0   | 150       | 14.93%  |
| 0.01-0.5   | 105       | 10.45%  |
| 3.01-4.0   | 78        | 7.76%   |
| 0.51-1.0   | 44        | 4.38%   |
| 5.01-6.0   | 20        | 1.99%   |
| 7.01-8.0   | 7         | 0.7%    |
| 2.01-3.0   | 4         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 207       | 19.42%  |
| Chimei Innolux          | 170       | 15.95%  |
| BOE                     | 165       | 15.48%  |
| LG Display              | 164       | 15.38%  |
| Samsung Electronics     | 102       | 9.57%   |
| PANDA                   | 40        | 3.75%   |
| Chi Mei Optoelectronics | 31        | 2.91%   |
| Dell                    | 29        | 2.72%   |
| Sharp                   | 25        | 2.35%   |
| Lenovo                  | 17        | 1.59%   |
| LG Philips              | 11        | 1.03%   |
| Goldstar                | 11        | 1.03%   |
| BenQ                    | 8         | 0.75%   |
| Acer                    | 8         | 0.75%   |
| Apple                   | 7         | 0.66%   |
| Philips                 | 5         | 0.47%   |
| InfoVision              | 5         | 0.47%   |
| Hewlett-Packard         | 5         | 0.47%   |
| CSO                     | 5         | 0.47%   |
| LGD                     | 4         | 0.38%   |
| Sony                    | 3         | 0.28%   |
| Lenovo Group Limited    | 3         | 0.28%   |
| Fujitsu Siemens         | 3         | 0.28%   |
| CPT                     | 3         | 0.28%   |
| ASUSTek Computer        | 3         | 0.28%   |
| AOC                     | 3         | 0.28%   |
| Ancor Communications    | 3         | 0.28%   |
| Analogix                | 3         | 0.28%   |
| Vestel Elektronik       | 2         | 0.19%   |
| InnoLux Display         | 2         | 0.19%   |
| HannStar                | 2         | 0.19%   |
| Toshiba                 | 1         | 0.09%   |
| TMX                     | 1         | 0.09%   |
| Seiko/Epson             | 1         | 0.09%   |
| Quanta Display          | 1         | 0.09%   |
| Panasonic               | 1         | 0.09%   |
| Nvidia                  | 1         | 0.09%   |
| NAD                     | 1         | 0.09%   |
| MStar                   | 1         | 0.09%   |
| LG Electronics          | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 26        | 2.42%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 21        | 1.95%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 18        | 1.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 18        | 1.67%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 15        | 1.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 1.12%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 1.12%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 1.02%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 10        | 0.93%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 10        | 0.93%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.93%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 9         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 9         | 0.84%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 8         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 8         | 0.74%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 8         | 0.74%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                  | 7         | 0.65%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 7         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 7         | 0.65%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 6         | 0.56%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 6         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 6         | 0.56%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 6         | 0.56%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 6         | 0.56%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.47%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 5         | 0.47%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 5         | 0.47%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 5         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.47%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 5         | 0.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.47%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 5         | 0.47%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 4         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 4         | 0.37%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 4         | 0.37%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 4         | 0.37%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 4         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 467       | 45.92%  |
| 1366x768 (WXGA)    | 328       | 32.25%  |
| 1600x900 (HD+)     | 49        | 4.82%   |
| 1280x800 (WXGA)    | 35        | 3.44%   |
| 3840x2160 (4K)     | 25        | 2.46%   |
| 2560x1440 (QHD)    | 13        | 1.28%   |
| 1440x900 (WXGA+)   | 13        | 1.28%   |
| 3200x1800 (QHD+)   | 11        | 1.08%   |
| 1680x1050 (WSXGA+) | 11        | 1.08%   |
| 2880x1800          | 9         | 0.88%   |
| 1920x1200 (WUXGA)  | 8         | 0.79%   |
| 1280x1024 (SXGA)   | 7         | 0.69%   |
| 1024x600           | 7         | 0.69%   |
| 2160x1440          | 5         | 0.49%   |
| 800x1280           | 4         | 0.39%   |
| 2560x1600          | 4         | 0.39%   |
| 1360x768           | 4         | 0.39%   |
| 2560x1080          | 3         | 0.29%   |
| 1400x1050          | 2         | 0.2%    |
| 1024x768 (XGA)     | 2         | 0.2%    |
| Unknown            | 2         | 0.2%    |
| 3926x1440          | 1         | 0.1%    |
| 3840x2400          | 1         | 0.1%    |
| 3840x1080          | 1         | 0.1%    |
| 3000x2000          | 1         | 0.1%    |
| 2240x1400          | 1         | 0.1%    |
| 2048x1152          | 1         | 0.1%    |
| 1680x945           | 1         | 0.1%    |
| 1280x720 (HD)      | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 613       | 57.83%  |
| 14      | 113       | 10.66%  |
| 13      | 99        | 9.34%   |
| 17      | 72        | 6.79%   |
| 24      | 25        | 2.36%   |
| 23      | 23        | 2.17%   |
| 27      | 18        | 1.7%    |
| Unknown | 18        | 1.7%    |
| 12      | 15        | 1.42%   |
| 21      | 10        | 0.94%   |
| 19      | 7         | 0.66%   |
| 10      | 7         | 0.66%   |
| 22      | 6         | 0.57%   |
| 31      | 5         | 0.47%   |
| 84      | 4         | 0.38%   |
| 16      | 4         | 0.38%   |
| 11      | 4         | 0.38%   |
| 34      | 3         | 0.28%   |
| 54      | 2         | 0.19%   |
| 20      | 2         | 0.19%   |
| 18      | 2         | 0.19%   |
| 8       | 2         | 0.19%   |
| 72      | 1         | 0.09%   |
| 52      | 1         | 0.09%   |
| 48      | 1         | 0.09%   |
| 32      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |
| 25      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 772       | 73.18%  |
| 351-400     | 89        | 8.44%   |
| 201-300     | 67        | 6.35%   |
| 501-600     | 65        | 6.16%   |
| 401-500     | 23        | 2.18%   |
| Unknown     | 18        | 1.71%   |
| 601-700     | 6         | 0.57%   |
| 1501-2000   | 5         | 0.47%   |
| 701-800     | 4         | 0.38%   |
| 1001-1500   | 4         | 0.38%   |
| 101-200     | 2         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 863       | 88.06%  |
| 16/10   | 78        | 7.96%   |
| Unknown | 12        | 1.22%   |
| 3/2     | 8         | 0.82%   |
| 5/4     | 6         | 0.61%   |
| 4/3     | 5         | 0.51%   |
| 0.62    | 4         | 0.41%   |
| 21/9    | 3         | 0.31%   |
| 6/5     | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 614       | 57.98%  |
| 81-90          | 181       | 17.09%  |
| 121-130        | 63        | 5.95%   |
| 201-250        | 55        | 5.19%   |
| 71-80          | 28        | 2.64%   |
| 301-350        | 19        | 1.79%   |
| Unknown        | 18        | 1.7%    |
| 61-70          | 14        | 1.32%   |
| 151-200        | 11        | 1.04%   |
| More than 1000 | 9         | 0.85%   |
| 351-500        | 9         | 0.85%   |
| 131-140        | 8         | 0.76%   |
| 41-50          | 7         | 0.66%   |
| 251-300        | 7         | 0.66%   |
| 51-60          | 4         | 0.38%   |
| 141-150        | 4         | 0.38%   |
| 91-100         | 4         | 0.38%   |
| 1-40           | 2         | 0.19%   |
| 111-120        | 2         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 452       | 43.01%  |
| 101-120       | 360       | 34.25%  |
| 51-100        | 146       | 13.89%  |
| 161-240       | 46        | 4.38%   |
| More than 240 | 23        | 2.19%   |
| Unknown       | 18        | 1.71%   |
| 1-50          | 6         | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 876       | 87.6%   |
| 2     | 98        | 9.8%    |
| 0     | 16        | 1.6%    |
| 3     | 9         | 0.9%    |
| 4     | 1         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 580       | 38.26%  |
| Intel                             | 456       | 30.08%  |
| Qualcomm Atheros                  | 219       | 14.45%  |
| Broadcom                          | 98        | 6.46%   |
| MediaTek                          | 26        | 1.72%   |
| TP-Link                           | 22        | 1.45%   |
| Ralink                            | 15        | 0.99%   |
| Marvell Technology Group          | 15        | 0.99%   |
| Broadcom Limited                  | 14        | 0.92%   |
| Ralink Technology                 | 9         | 0.59%   |
| Xiaomi                            | 5         | 0.33%   |
| Huawei Technologies               | 5         | 0.33%   |
| Hewlett-Packard                   | 5         | 0.33%   |
| Ericsson Business Mobile Networks | 5         | 0.33%   |
| Samsung Electronics               | 4         | 0.26%   |
| JMicron Technology                | 4         | 0.26%   |
| ASUSTek Computer                  | 4         | 0.26%   |
| ASIX Electronics                  | 4         | 0.26%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.2%    |
| Silicon Integrated Systems [SiS]  | 3         | 0.2%    |
| Qualcomm Atheros Communications   | 3         | 0.2%    |
| Lenovo                            | 2         | 0.13%   |
| D-Link                            | 2         | 0.13%   |
| VIA Technologies                  | 1         | 0.07%   |
| U-Blox                            | 1         | 0.07%   |
| Sierra Wireless                   | 1         | 0.07%   |
| Qcom                              | 1         | 0.07%   |
| Nvidia                            | 1         | 0.07%   |
| Microsoft                         | 1         | 0.07%   |
| Microchip Technology              | 1         | 0.07%   |
| Fibocom                           | 1         | 0.07%   |
| Edimax Technology                 | 1         | 0.07%   |
| DisplayLink                       | 1         | 0.07%   |
| Dell                              | 1         | 0.07%   |
| D-Link System                     | 1         | 0.07%   |
| Belkin                            | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 320       | 17.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 104       | 5.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 65        | 3.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 50        | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 50        | 2.76%   |
| Intel Wireless 8265 / 8275                                        | 49        | 2.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 44        | 2.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 34        | 1.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 34        | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 33        | 1.82%   |
| Intel Wi-Fi 6 AX200                                               | 27        | 1.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 26        | 1.44%   |
| Intel Wi-Fi 6 AX201                                               | 26        | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26        | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 25        | 1.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 24        | 1.33%   |
| Intel Wireless 7260                                               | 24        | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 22        | 1.22%   |
| Intel Wireless 7265                                               | 21        | 1.16%   |
| Intel Wireless 8260                                               | 19        | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 19        | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 19        | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 18        | 1%      |
| Intel Wireless 3160                                               | 18        | 1%      |
| Broadcom BCM43142 802.11b/g/n                                     | 18        | 1%      |
| Realtek 802.11n WLAN Adapter                                      | 17        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 0.88%   |
| Intel Centrino Advanced-N 6200                                    | 16        | 0.88%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 15        | 0.83%   |
| Intel Wireless 3165                                               | 14        | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 13        | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 13        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 13        | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 9         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 0.5%    |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 437       | 42.93%  |
| Realtek Semiconductor           | 223       | 21.91%  |
| Qualcomm Atheros                | 195       | 19.16%  |
| Broadcom                        | 74        | 7.27%   |
| MediaTek                        | 22        | 2.16%   |
| TP-Link                         | 17        | 1.67%   |
| Ralink                          | 15        | 1.47%   |
| Broadcom Limited                | 11        | 1.08%   |
| Ralink Technology               | 9         | 0.88%   |
| ASUSTek Computer                | 4         | 0.39%   |
| Qualcomm Atheros Communications | 3         | 0.29%   |
| Sierra Wireless                 | 1         | 0.1%    |
| Qcom                            | 1         | 0.1%    |
| Microsoft                       | 1         | 0.1%    |
| Fibocom                         | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |
| D-Link System                   | 1         | 0.1%    |
| D-Link                          | 1         | 0.1%    |
| Belkin                          | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 65        | 6.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 50        | 4.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 50        | 4.88%   |
| Intel Wireless 8265 / 8275                                              | 49        | 4.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 44        | 4.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 34        | 3.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 3.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 3.22%   |
| Intel Wi-Fi 6 AX200                                                     | 27        | 2.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 26        | 2.54%   |
| Intel Wi-Fi 6 AX201                                                     | 26        | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 25        | 2.44%   |
| Intel Wireless 7260                                                     | 24        | 2.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 22        | 2.15%   |
| Intel Wireless 7265                                                     | 21        | 2.05%   |
| Intel Wireless 8260                                                     | 19        | 1.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 19        | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 19        | 1.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 18        | 1.76%   |
| Intel Wireless 3160                                                     | 18        | 1.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 18        | 1.76%   |
| Realtek 802.11n WLAN Adapter                                            | 17        | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 1.56%   |
| Intel Centrino Advanced-N 6200                                          | 16        | 1.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 1.46%   |
| Intel Wireless 3165                                                     | 14        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 1.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.27%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 0.68%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 7         | 0.68%   |
| Intel Centrino Advanced-N 6235                                          | 7         | 0.68%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 7         | 0.68%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 7         | 0.68%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 7         | 0.68%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 7         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 461       | 60.34%  |
| Intel                            | 153       | 20.03%  |
| Qualcomm Atheros                 | 52        | 6.81%   |
| Broadcom                         | 40        | 5.24%   |
| Marvell Technology Group         | 15        | 1.96%   |
| Xiaomi                           | 5         | 0.65%   |
| TP-Link                          | 5         | 0.65%   |
| Samsung Electronics              | 4         | 0.52%   |
| MediaTek                         | 4         | 0.52%   |
| JMicron Technology               | 4         | 0.52%   |
| Huawei Technologies              | 4         | 0.52%   |
| ASIX Electronics                 | 4         | 0.52%   |
| Silicon Integrated Systems [SiS] | 3         | 0.39%   |
| Broadcom Limited                 | 3         | 0.39%   |
| Lenovo                           | 2         | 0.26%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.13%   |
| VIA Technologies                 | 1         | 0.13%   |
| Nvidia                           | 1         | 0.13%   |
| DisplayLink                      | 1         | 0.13%   |
| D-Link                           | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 320       | 41.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 104       | 13.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26        | 3.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 24        | 3.13%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 2.09%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 1.56%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 1.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 1.17%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 1.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.91%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.91%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.91%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 7         | 0.91%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.65%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 5         | 0.65%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 4         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.52%   |
| MediaTek Infinix NOTE 11                                          | 4         | 0.52%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 4         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.52%   |
| Huawei STK-L21                                                    | 4         | 0.52%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 4         | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.52%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3         | 0.39%   |
| Intel PRO/100 VE Network Connection                               | 3         | 0.39%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.39%   |
| Intel Ethernet Connection (14) I219-LM                            | 3         | 0.39%   |
| Intel 82577LC Gigabit Network Connection                          | 3         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 975       | 56.39%  |
| Ethernet | 736       | 42.57%  |
| Modem    | 17        | 0.98%   |
| Unknown  | 1         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 827       | 80.06%  |
| Ethernet | 206       | 19.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 690       | 70.19%  |
| 1     | 271       | 27.57%  |
| 0     | 17        | 1.73%   |
| 3     | 5         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 860       | 85.74%  |
| Yes  | 143       | 14.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 332       | 41.97%  |
| IMC Networks                    | 124       | 15.68%  |
| Realtek Semiconductor           | 98        | 12.39%  |
| Qualcomm Atheros Communications | 64        | 8.09%   |
| Lite-On Technology              | 43        | 5.44%   |
| Broadcom                        | 36        | 4.55%   |
| Dell                            | 18        | 2.28%   |
| Foxconn / Hon Hai               | 17        | 2.15%   |
| Hewlett-Packard                 | 13        | 1.64%   |
| Toshiba                         | 10        | 1.26%   |
| Ralink                          | 9         | 1.14%   |
| Apple                           | 5         | 0.63%   |
| Cambridge Silicon Radio         | 4         | 0.51%   |
| ASUSTek Computer                | 4         | 0.51%   |
| Realtek                         | 3         | 0.38%   |
| Alps Electric                   | 3         | 0.38%   |
| Chicony Electronics             | 2         | 0.25%   |
| SINO WEALTH                     | 1         | 0.13%   |
| Ralink Technology               | 1         | 0.13%   |
| Opticis                         | 1         | 0.13%   |
| MediaTek                        | 1         | 0.13%   |
| Foxconn International           | 1         | 0.13%   |
| Askey Computer                  | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 150       | 18.96%  |
| IMC Networks Bluetooth Radio                        | 81        | 10.24%  |
| Realtek Bluetooth Radio                             | 74        | 9.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 63        | 7.96%   |
| Intel AX201 Bluetooth                               | 61        | 7.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 36        | 4.55%   |
| Intel AX200 Bluetooth                               | 27        | 3.41%   |
| IMC Networks Bluetooth Device                       | 23        | 2.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 20        | 2.53%   |
| Realtek  Bluetooth 4.2 Adapter                      | 16        | 2.02%   |
| IMC Networks Wireless_Device                        | 14        | 1.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 1.39%   |
| Ralink RT3290 Bluetooth                             | 9         | 1.14%   |
| Lite-On Bluetooth Device                            | 9         | 1.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.14%   |
| Dell DW375 Bluetooth Module                         | 9         | 1.14%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 1.01%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.88%   |
| Broadcom BCM2045A0                                  | 7         | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 0.76%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 0.63%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.63%   |
| Toshiba Bluetooth Device                            | 4         | 0.51%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.51%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.51%   |
| Intel AX210 Bluetooth                               | 4         | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 0.51%   |
| Realtek Bluetooth Radio                             | 3         | 0.38%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.38%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 0.38%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 3         | 0.38%   |
| Dell Wireless 365 Bluetooth                         | 3         | 0.38%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 829       | 69.49%  |
| AMD                              | 163       | 13.66%  |
| Nvidia                           | 155       | 12.99%  |
| C-Media Electronics              | 8         | 0.67%   |
| GN Netcom                        | 7         | 0.59%   |
| Logitech                         | 5         | 0.42%   |
| Silicon Integrated Systems [SiS] | 4         | 0.34%   |
| Realtek Semiconductor            | 3         | 0.25%   |
| ASUSTek Computer                 | 3         | 0.25%   |
| XMOS                             | 2         | 0.17%   |
| VIA Technologies                 | 2         | 0.17%   |
| Lenovo                           | 2         | 0.17%   |
| Creative Technology              | 2         | 0.17%   |
| Unknown                          | 1         | 0.08%   |
| Sony                             | 1         | 0.08%   |
| Sennheiser Communications        | 1         | 0.08%   |
| Plantronics                      | 1         | 0.08%   |
| Kingston Technology              | 1         | 0.08%   |
| Hewlett-Packard                  | 1         | 0.08%   |
| Dell                             | 1         | 0.08%   |
| CMX Systems                      | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 109       | 7.62%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 96        | 6.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 61        | 4.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 56        | 3.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 54        | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 52        | 3.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 50        | 3.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 47        | 3.28%   |
| Intel 8 Series HD Audio Controller                                                                | 46        | 3.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 43        | 3%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 42        | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 41        | 2.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 40        | 2.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 39        | 2.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 35        | 2.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 35        | 2.45%   |
| Intel Broadwell-U Audio Controller                                                                | 35        | 2.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 32        | 2.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 32        | 2.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 26        | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 23        | 1.61%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 23        | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 22        | 1.54%   |
| Intel CM238 HD Audio Controller                                                                   | 19        | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 17        | 1.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 17        | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 1.19%   |
| AMD FCH Azalia Controller                                                                         | 16        | 1.12%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 14        | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 0.98%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 12        | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 0.84%   |
| AMD High Definition Audio Controller                                                              | 11        | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 9         | 0.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 146       | 29.08%  |
| SK hynix                     | 115       | 22.91%  |
| Micron Technology            | 59        | 11.75%  |
| Kingston                     | 57        | 11.35%  |
| Unknown                      | 25        | 4.98%   |
| Ramaxel Technology           | 16        | 3.19%   |
| Corsair                      | 16        | 3.19%   |
| Elpida                       | 13        | 2.59%   |
| A-DATA Technology            | 13        | 2.59%   |
| Crucial                      | 11        | 2.19%   |
| Nanya Technology             | 10        | 1.99%   |
| Unknown (ABCD)               | 6         | 1.2%    |
| Kingmax                      | 3         | 0.6%    |
| Transcend                    | 2         | 0.4%    |
| Unknown (0x7FDA000000000000) | 1         | 0.2%    |
| Unknown (0B45)               | 1         | 0.2%    |
| Silicon Power                | 1         | 0.2%    |
| SHARETRONIC                  | 1         | 0.2%    |
| Patriot                      | 1         | 0.2%    |
| Kingmax Semiconductor        | 1         | 0.2%    |
| Avant                        | 1         | 0.2%    |
| ASint Technology             | 1         | 0.2%    |
| Apacer                       | 1         | 0.2%    |
| Unknown                      | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 2.01%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 2.01%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 10        | 1.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.82%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 1.64%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 1.64%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 1.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 1.28%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.09%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 1.09%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 1.09%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.91%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.91%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 5         | 0.91%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.91%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.73%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 4         | 0.73%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.73%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.73%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.73%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.73%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s          | 4         | 0.73%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 3         | 0.55%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 3         | 0.55%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.55%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.55%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.55%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.55%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 3         | 0.55%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.55%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.55%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.55%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.55%   |
| Samsung RAM M471A1K44BM0-CRC 8192MB SODIMM DDR4 2400MT/s         | 3         | 0.55%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 3         | 0.55%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 3         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 208       | 49.64%  |
| DDR3    | 146       | 34.84%  |
| DDR2    | 27        | 6.44%   |
| LPDDR4  | 12        | 2.86%   |
| LPDDR3  | 11        | 2.63%   |
| SDRAM   | 8         | 1.91%   |
| DDR5    | 2         | 0.48%   |
| Unknown | 2         | 0.48%   |
| LPDDR5  | 1         | 0.24%   |
| DRAM    | 1         | 0.24%   |
| DDR     | 1         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 390       | 93.53%  |
| Row Of Chips | 23        | 5.52%   |
| Chip         | 3         | 0.72%   |
| DIMM         | 1         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 176       | 38.6%   |
| 4096  | 146       | 32.02%  |
| 16384 | 54        | 11.84%  |
| 2048  | 54        | 11.84%  |
| 1024  | 20        | 4.39%   |
| 32768 | 5         | 1.1%    |
| 512   | 1         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 108       | 22.98%  |
| 2667    | 92        | 19.57%  |
| 3200    | 88        | 18.72%  |
| 2400    | 46        | 9.79%   |
| 1334    | 34        | 7.23%   |
| 2133    | 19        | 4.04%   |
| 1333    | 12        | 2.55%   |
| 3266    | 10        | 2.13%   |
| 667     | 10        | 2.13%   |
| 975     | 8         | 1.7%    |
| 800     | 7         | 1.49%   |
| Unknown | 7         | 1.49%   |
| 1067    | 6         | 1.28%   |
| 4267    | 4         | 0.85%   |
| 4199    | 3         | 0.64%   |
| 1066    | 3         | 0.64%   |
| 4800    | 2         | 0.43%   |
| 2048    | 2         | 0.43%   |
| 1867    | 2         | 0.43%   |
| 6400    | 1         | 0.21%   |
| 4266    | 1         | 0.21%   |
| 2933    | 1         | 0.21%   |
| 1639    | 1         | 0.21%   |
| 533     | 1         | 0.21%   |
| 400     | 1         | 0.21%   |
| 333     | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 28.57%  |
| Canon                 | 5         | 23.81%  |
| Seiko Epson           | 3         | 14.29%  |
| Samsung Electronics   | 3         | 14.29%  |
| Brother Industries    | 2         | 9.52%   |
| Xerox                 | 1         | 4.76%   |
| Lexmark International | 1         | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                   | 2         | 9.52%   |
| Samsung Composite Device                   | 2         | 9.52%   |
| Xerox Phaser 3020                          | 1         | 4.76%   |
| Seiko Epson L3150 Series                   | 1         | 4.76%   |
| Samsung M2070 Series                       | 1         | 4.76%   |
| Lexmark International InkJet Color Printer | 1         | 4.76%   |
| HP LaserJet 1022                           | 1         | 4.76%   |
| HP LaserJet 1018                           | 1         | 4.76%   |
| HP Laser 107a                              | 1         | 4.76%   |
| HP Deskjet F4500 series                    | 1         | 4.76%   |
| HP DeskJet 2300 series                     | 1         | 4.76%   |
| HP Deskjet 2050 J510                       | 1         | 4.76%   |
| Canon PIXMA MP250                          | 1         | 4.76%   |
| Canon MF4320-4350                          | 1         | 4.76%   |
| Canon MF3200 series                        | 1         | 4.76%   |
| Canon iP7200 series                        | 1         | 4.76%   |
| Canon CanoScan LiDE 300                    | 1         | 4.76%   |
| Brother HL-1110 series                     | 1         | 4.76%   |
| Brother DCP-T310                           | 1         | 4.76%   |

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
| IMC Networks                           | 215       | 24.27%  |
| Chicony Electronics                    | 193       | 21.78%  |
| Realtek Semiconductor                  | 81        | 9.14%   |
| Acer                                   | 65        | 7.34%   |
| Microdia                               | 58        | 6.55%   |
| Sunplus Innovation Technology          | 49        | 5.53%   |
| Quanta                                 | 39        | 4.4%    |
| Syntek                                 | 24        | 2.71%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 2.71%   |
| Alcor Micro                            | 22        | 2.48%   |
| Lite-On Technology                     | 20        | 2.26%   |
| Suyin                                  | 19        | 2.14%   |
| Sonix Technology                       | 12        | 1.35%   |
| Ricoh                                  | 9         | 1.02%   |
| Silicon Motion                         | 7         | 0.79%   |
| Samsung Electronics                    | 7         | 0.79%   |
| Luxvisions Innotech Limited            | 7         | 0.79%   |
| Apple                                  | 6         | 0.68%   |
| OmniVision Technologies                | 5         | 0.56%   |
| ALi                                    | 4         | 0.45%   |
| Z-Star Microelectronics                | 2         | 0.23%   |
| Sunplus Technology                     | 2         | 0.23%   |
| Primax Electronics                     | 2         | 0.23%   |
| Microsoft                              | 2         | 0.23%   |
| Lenovo                                 | 2         | 0.23%   |
| Importek                               | 2         | 0.23%   |
| Genesys Logic                          | 2         | 0.23%   |
| Trust                                  | 1         | 0.11%   |
| Philips (or NXP)                       | 1         | 0.11%   |
| Logitech                               | 1         | 0.11%   |
| Epiphan Systems                        | 1         | 0.11%   |
| DigiTech                               | 1         | 0.11%   |
| Cubeternet                             | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam            | 101       | 11.39%  |
| IMC Networks USB2.0 HD UVC WebCam             | 62        | 6.99%   |
| Chicony Integrated Camera                     | 40        | 4.51%   |
| Realtek Integrated_Webcam_HD                  | 31        | 3.49%   |
| Acer Integrated Camera                        | 21        | 2.37%   |
| IMC Networks Integrated Camera                | 20        | 2.25%   |
| Microdia Integrated_Webcam_HD                 | 17        | 1.92%   |
| Chicony USB2.0 VGA UVC WebCam                 | 16        | 1.8%    |
| Chicony HD Webcam                             | 15        | 1.69%   |
| Chicony USB2.0 HD UVC WebCam                  | 13        | 1.47%   |
| Syntek Integrated Camera                      | 12        | 1.35%   |
| Sunplus HD WebCam                             | 10        | 1.13%   |
| Realtek USB Camera                            | 10        | 1.13%   |
| Acer Lenovo EasyCamera                        | 10        | 1.13%   |
| Sonix USB2.0 HD UVC WebCam                    | 9         | 1.01%   |
| Quanta VGA WebCam                             | 9         | 1.01%   |
| Chicony TOSHIBA Web Camera - HD               | 9         | 1.01%   |
| Microdia Integrated Webcam                    | 8         | 0.9%    |
| Lite-On Integrated Camera                     | 8         | 0.9%    |
| Chicony HP Webcam                             | 8         | 0.9%    |
| Chicony EasyCamera                            | 8         | 0.9%    |
| Acer SunplusIT Integrated Camera              | 8         | 0.9%    |
| Sunplus Integrated_Webcam_HD                  | 7         | 0.79%   |
| Samsung Galaxy A5 (MTP)                       | 7         | 0.79%   |
| Microdia USB 2.0 Camera                       | 7         | 0.79%   |
| IMC Networks USB2.0 UVC HD Webcam             | 7         | 0.79%   |
| Chicony VGA WebCam                            | 7         | 0.79%   |
| Alcor Micro USB 2.0 PC Camera                 | 7         | 0.79%   |
| Acer EasyCamera                               | 7         | 0.79%   |
| Syntek EasyCamera                             | 6         | 0.68%   |
| Sunplus ASUS Webcam                           | 6         | 0.68%   |
| Realtek USB2.0 HD UVC WebCam                  | 6         | 0.68%   |
| Realtek Lenovo EasyCamera                     | 6         | 0.68%   |
| Chicony HP HD Webcam                          | 6         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 6         | 0.68%   |
| Alcor Micro USB 2.0 Camera                    | 6         | 0.68%   |
| Syntek Lenovo EasyCamera                      | 5         | 0.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 5         | 0.56%   |
| Realtek USB2.0 VGA UVC WebCam                 | 5         | 0.56%   |
| Realtek Integrated Webcam                     | 5         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 51        | 37.78%  |
| Synaptics                  | 33        | 24.44%  |
| Shenzhen Goodix Technology | 14        | 10.37%  |
| Upek                       | 11        | 8.15%   |
| Elan Microelectronics      | 11        | 8.15%   |
| AuthenTec                  | 7         | 5.19%   |
| LighTuning Technology      | 5         | 3.7%    |
| STMicroelectronics         | 1         | 0.74%   |
| GDMicroelectronics         | 1         | 0.74%   |
| Focal-systems.Corp         | 1         | 0.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 8.15%   |
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 8.15%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 7.41%   |
| Synaptics  WBDI                                                            | 9         | 6.67%   |
| Elan ELAN:Fingerprint                                                      | 9         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 5.93%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 5.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 4.44%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.44%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 3.7%    |
| AuthenTec AES2810                                                          | 5         | 3.7%    |
| Unknown                                                                    | 5         | 3.7%    |
| Validity Sensors VFS491                                                    | 4         | 2.96%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.96%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.96%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.22%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 2.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 2.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.48%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.48%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.48%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.48%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.48%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.74%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.74%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.74%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.74%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.74%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.74%   |
| GDMicroelectronics Touch Fingerprint Sensor                                | 1         | 0.74%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.74%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.74%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.74%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 38        | 61.29%  |
| Alcor Micro               | 13        | 20.97%  |
| Lenovo                    | 4         | 6.45%   |
| O2 Micro                  | 3         | 4.84%   |
| Upek                      | 2         | 3.23%   |
| Gemalto (was Gemplus)     | 1         | 1.61%   |
| Aladdin Knowledge Systems | 1         | 1.61%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 20.97%  |
| Broadcom 58200                                                               | 11        | 17.74%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 16.13%  |
| Broadcom 5880                                                                | 9         | 14.52%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 12.9%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 4.84%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.23%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.61%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.61%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 669       | 67.03%  |
| 1     | 265       | 26.55%  |
| 2     | 58        | 5.81%   |
| 3     | 4         | 0.4%    |
| 10    | 1         | 0.1%    |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 134       | 33.84%  |
| Graphics card            | 72        | 18.18%  |
| Chipcard                 | 58        | 14.65%  |
| Net/wireless             | 41        | 10.35%  |
| Multimedia controller    | 22        | 5.56%   |
| Camera                   | 15        | 3.79%   |
| Bluetooth                | 14        | 3.54%   |
| Storage                  | 13        | 3.28%   |
| Communication controller | 12        | 3.03%   |
| Sound                    | 3         | 0.76%   |
| Card reader              | 3         | 0.76%   |
| Network                  | 2         | 0.51%   |
| Net/ethernet             | 2         | 0.51%   |
| Storage/nvme             | 1         | 0.25%   |
| Modem                    | 1         | 0.25%   |
| Flash memory             | 1         | 0.25%   |
| Firewire controller      | 1         | 0.25%   |
| Dvb card                 | 1         | 0.25%   |

