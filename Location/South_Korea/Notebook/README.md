Linux in South Korea - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in South Korea.

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

Total: 372

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X230 2325KZ5       | [7c10f1a5de](https://linux-hardware.org/?probe=7c10f1a5de) | Sep 30, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [7941c7c6cc](https://linux-hardware.org/?probe=7941c7c6cc) | Sep 27, 2023 |
| ASUSTek       | X542UN                      | [76f91b9954](https://linux-hardware.org/?probe=76f91b9954) | Sep 24, 2023 |
| HP            | OMEN by Transcend Gaming... | [866ab5c907](https://linux-hardware.org/?probe=866ab5c907) | Sep 11, 2023 |
| HP            | OMEN by Transcend Gaming... | [2afa6e66d2](https://linux-hardware.org/?probe=2afa6e66d2) | Sep 11, 2023 |
| Samsung       | 700T1C                      | [6240a5d18a](https://linux-hardware.org/?probe=6240a5d18a) | Sep 09, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [2a900ea3bd](https://linux-hardware.org/?probe=2a900ea3bd) | Sep 03, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | [3c811f59ba](https://linux-hardware.org/?probe=3c811f59ba) | Aug 23, 2023 |
| ASUSTek       | GL502VMZ                    | [65952bbced](https://linux-hardware.org/?probe=65952bbced) | Aug 23, 2023 |
| LG Electro... | 15Z990-VA5WK                | [51c419c795](https://linux-hardware.org/?probe=51c419c795) | Aug 23, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | [df8b84163a](https://linux-hardware.org/?probe=df8b84163a) | Aug 23, 2023 |
| Lenovo        | ThinkPad X230 2306AV4       | [d52720a4dc](https://linux-hardware.org/?probe=d52720a4dc) | Aug 21, 2023 |
| Valve         | Jupiter                     | [1d87714ed5](https://linux-hardware.org/?probe=1d87714ed5) | Aug 20, 2023 |
| HP            | EliteBook 865 16 inch G9... | [f99d3dca93](https://linux-hardware.org/?probe=f99d3dca93) | Aug 17, 2023 |
| HP            | EliteBook 845 14 inch G9... | [0650746552](https://linux-hardware.org/?probe=0650746552) | Aug 13, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [fee93b31f5](https://linux-hardware.org/?probe=fee93b31f5) | Aug 13, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5892469c5b](https://linux-hardware.org/?probe=5892469c5b) | Aug 12, 2023 |
| Notebook      | N650DU                      | [c04f4faa06](https://linux-hardware.org/?probe=c04f4faa06) | Jul 19, 2023 |
| HP            | Pavilion dv6                | [2abf53d250](https://linux-hardware.org/?probe=2abf53d250) | Jul 17, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [c9a443767b](https://linux-hardware.org/?probe=c9a443767b) | Jul 16, 2023 |
| Dell          | XPS 15 9570                 | [1c15fc53af](https://linux-hardware.org/?probe=1c15fc53af) | Jul 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [09419812ab](https://linux-hardware.org/?probe=09419812ab) | Jun 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [856acf81ed](https://linux-hardware.org/?probe=856acf81ed) | Jun 22, 2023 |
| Acer          | Predator PHN16-71           | [16f2ca887d](https://linux-hardware.org/?probe=16f2ca887d) | Jun 20, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [4777b096a3](https://linux-hardware.org/?probe=4777b096a3) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| HP            | Laptop 15-fc0xxx            | [af90ec4131](https://linux-hardware.org/?probe=af90ec4131) | Jun 16, 2023 |
| HP            | ENVY Notebook               | [4a4602250b](https://linux-hardware.org/?probe=4a4602250b) | Jun 15, 2023 |
| HP            | ENVY Notebook               | [54115f309f](https://linux-hardware.org/?probe=54115f309f) | Jun 15, 2023 |
| Samsung       | 760XDA                      | [f0decf4dbe](https://linux-hardware.org/?probe=f0decf4dbe) | Jun 14, 2023 |
| Samsung       | 910S3L                      | [f8e59b4c0f](https://linux-hardware.org/?probe=f8e59b4c0f) | Jun 08, 2023 |
| Samsung       | 910S3L                      | [2db0ae25d8](https://linux-hardware.org/?probe=2db0ae25d8) | Jun 06, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [95ec288436](https://linux-hardware.org/?probe=95ec288436) | Jun 03, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [7720a9f71c](https://linux-hardware.org/?probe=7720a9f71c) | Jun 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [8a6ceb7d8b](https://linux-hardware.org/?probe=8a6ceb7d8b) | May 30, 2023 |
| Samsung       | 950XDC/951XDC/950XDX        | [105d3da269](https://linux-hardware.org/?probe=105d3da269) | May 30, 2023 |
| Samsung       | 900X5T                      | [9f1d226c85](https://linux-hardware.org/?probe=9f1d226c85) | May 25, 2023 |
| ASUSTek       | X542UN                      | [29547f8e99](https://linux-hardware.org/?probe=29547f8e99) | May 24, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [2d07f38ffa](https://linux-hardware.org/?probe=2d07f38ffa) | May 17, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [de6d4ede23](https://linux-hardware.org/?probe=de6d4ede23) | May 17, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [64353c7d87](https://linux-hardware.org/?probe=64353c7d87) | May 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [efc35b1887](https://linux-hardware.org/?probe=efc35b1887) | May 11, 2023 |
| Unknown       | Unknown                     | [0225c3c300](https://linux-hardware.org/?probe=0225c3c300) | May 09, 2023 |
| Samsung       | 730QCJ/730QCR               | [4541d2e721](https://linux-hardware.org/?probe=4541d2e721) | May 02, 2023 |
| Lenovo        | E520-15IKB 80WA             | [abd1d98b9b](https://linux-hardware.org/?probe=abd1d98b9b) | Apr 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [62399bace9](https://linux-hardware.org/?probe=62399bace9) | Apr 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [1f3ed1329d](https://linux-hardware.org/?probe=1f3ed1329d) | Apr 16, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [91946b965a](https://linux-hardware.org/?probe=91946b965a) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [674533c5cd](https://linux-hardware.org/?probe=674533c5cd) | Apr 12, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [9ddd50e0ed](https://linux-hardware.org/?probe=9ddd50e0ed) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [36338ecf6e](https://linux-hardware.org/?probe=36338ecf6e) | Apr 05, 2023 |
| Apple         | MacBookPro9,2               | [f4343acc49](https://linux-hardware.org/?probe=f4343acc49) | Apr 03, 2023 |
| Apple         | MacBookPro9,2               | [3e558165a4](https://linux-hardware.org/?probe=3e558165a4) | Apr 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | [758bb2556e](https://linux-hardware.org/?probe=758bb2556e) | Apr 01, 2023 |
| Notebook      | N650DU                      | [e8ec3c6462](https://linux-hardware.org/?probe=e8ec3c6462) | Mar 30, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [bf2f7820cd](https://linux-hardware.org/?probe=bf2f7820cd) | Mar 29, 2023 |
| Apple         | MacBook9,1                  | [9639f02d57](https://linux-hardware.org/?probe=9639f02d57) | Mar 25, 2023 |
| WEIPAI        | S15                         | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| Apple         | MacBookPro11,2              | [9404efe255](https://linux-hardware.org/?probe=9404efe255) | Mar 18, 2023 |
| Gigabyte      | GB-BSi7A-6500               | [5a9b5297c2](https://linux-hardware.org/?probe=5a9b5297c2) | Mar 16, 2023 |
| Valve         | Jupiter                     | [0d12931010](https://linux-hardware.org/?probe=0d12931010) | Mar 11, 2023 |
| Dell          | Latitude E5440              | [25cf039ffd](https://linux-hardware.org/?probe=25cf039ffd) | Feb 27, 2023 |
| Dell          | Latitude E5440              | [5546f00169](https://linux-hardware.org/?probe=5546f00169) | Feb 26, 2023 |
| Samsung       | 760XDA                      | [efa040a93f](https://linux-hardware.org/?probe=efa040a93f) | Feb 22, 2023 |
| Samsung       | 760XDA                      | [1ba36d420d](https://linux-hardware.org/?probe=1ba36d420d) | Feb 22, 2023 |
| Gigabyte      | GB-BSi7A-6500               | [6ec55330a7](https://linux-hardware.org/?probe=6ec55330a7) | Feb 21, 2023 |
| Samsung       | 940XFG                      | [56f236f8ab](https://linux-hardware.org/?probe=56f236f8ab) | Feb 16, 2023 |
| Samsung       | 900X5N                      | [91793918de](https://linux-hardware.org/?probe=91793918de) | Feb 07, 2023 |
| Unknown       | Unknown                     | [d1da7498da](https://linux-hardware.org/?probe=d1da7498da) | Feb 02, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [9b17a7541e](https://linux-hardware.org/?probe=9b17a7541e) | Jan 30, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| HP            | Notebook                    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| ASUSTek       | X540UA                      | [39f992a141](https://linux-hardware.org/?probe=39f992a141) | Jan 22, 2023 |
| ASUSTek       | X540UA                      | [dda62597f7](https://linux-hardware.org/?probe=dda62597f7) | Jan 21, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [dfca68067c](https://linux-hardware.org/?probe=dfca68067c) | Jan 10, 2023 |
| Samsung       | 760XDA                      | [06a850e558](https://linux-hardware.org/?probe=06a850e558) | Jan 10, 2023 |
| Samsung       | 760XDA                      | [180727ef64](https://linux-hardware.org/?probe=180727ef64) | Jan 10, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [a56af08eb5](https://linux-hardware.org/?probe=a56af08eb5) | Jan 07, 2023 |
| Valve         | Jupiter                     | [e47684954b](https://linux-hardware.org/?probe=e47684954b) | Jan 04, 2023 |
| Lenovo        | ThinkPad E585 20KVS06F00    | [8c3bdcc48c](https://linux-hardware.org/?probe=8c3bdcc48c) | Dec 25, 2022 |
| Jooyon Tec... | J6BF                        | [dabe200abe](https://linux-hardware.org/?probe=dabe200abe) | Dec 23, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | [f244715ee3](https://linux-hardware.org/?probe=f244715ee3) | Dec 22, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | [2ebd48d256](https://linux-hardware.org/?probe=2ebd48d256) | Dec 22, 2022 |
| Gigabyte      | AERO 15 YC                  | [24e48000be](https://linux-hardware.org/?probe=24e48000be) | Dec 22, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | [d6f3d14b20](https://linux-hardware.org/?probe=d6f3d14b20) | Dec 22, 2022 |
| LG Electro... | 15UD480-GX50K               | [16be4a033d](https://linux-hardware.org/?probe=16be4a033d) | Dec 19, 2022 |
| Valve         | Jupiter                     | [24182862cd](https://linux-hardware.org/?probe=24182862cd) | Dec 15, 2022 |
| Valve         | Jupiter                     | [cfe8d55199](https://linux-hardware.org/?probe=cfe8d55199) | Dec 14, 2022 |
| Samsung       | 550XED                      | [8e5bdc1eab](https://linux-hardware.org/?probe=8e5bdc1eab) | Dec 14, 2022 |
| Samsung       | 550XED                      | [3165e8b2df](https://linux-hardware.org/?probe=3165e8b2df) | Dec 14, 2022 |
| Lenovo        | ThinkPad X260 20F6007KKR    | [9b788f857e](https://linux-hardware.org/?probe=9b788f857e) | Dec 14, 2022 |
| Valve         | Jupiter                     | [a2f1af21a0](https://linux-hardware.org/?probe=a2f1af21a0) | Dec 13, 2022 |
| Valve         | Jupiter                     | [a505c76dfa](https://linux-hardware.org/?probe=a505c76dfa) | Dec 13, 2022 |
| LG Electro... | 15ND530-GX3FK               | [47b90cbe2a](https://linux-hardware.org/?probe=47b90cbe2a) | Dec 12, 2022 |
| Google        | Peppy                       | [59f9af1c52](https://linux-hardware.org/?probe=59f9af1c52) | Dec 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5S... | [7772d8b9f8](https://linux-hardware.org/?probe=7772d8b9f8) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [5254612ca4](https://linux-hardware.org/?probe=5254612ca4) | Dec 09, 2022 |
| Samsung       | 550XED                      | [705495532e](https://linux-hardware.org/?probe=705495532e) | Dec 09, 2022 |
| Samsung       | 550XED                      | [0df3845885](https://linux-hardware.org/?probe=0df3845885) | Dec 08, 2022 |
| Lenovo        | ThinkPad T61 889502U        | [b9d0a07e47](https://linux-hardware.org/?probe=b9d0a07e47) | Dec 08, 2022 |
| Lenovo        | ThinkPad T60 1953PKK        | [fc308e2f1c](https://linux-hardware.org/?probe=fc308e2f1c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [e13e889312](https://linux-hardware.org/?probe=e13e889312) | Dec 08, 2022 |
| Samsung       | 550XED                      | [0ce3bd481f](https://linux-hardware.org/?probe=0ce3bd481f) | Dec 07, 2022 |
| Lenovo        | ThinkPad E495 20NES0J800    | [17182155b5](https://linux-hardware.org/?probe=17182155b5) | Dec 07, 2022 |
| Samsung       | 550XED                      | [fee55cdb61](https://linux-hardware.org/?probe=fee55cdb61) | Dec 02, 2022 |
| Samsung       | 550XED                      | [d8894f602a](https://linux-hardware.org/?probe=d8894f602a) | Dec 01, 2022 |
| Dell          | Latitude E5440              | [90d18073d6](https://linux-hardware.org/?probe=90d18073d6) | Nov 29, 2022 |
| Dell          | Inspiron 15 5510            | [5ec5306c0f](https://linux-hardware.org/?probe=5ec5306c0f) | Nov 28, 2022 |
| Samsung       | 550XED                      | [143518e596](https://linux-hardware.org/?probe=143518e596) | Nov 26, 2022 |
| Unknown       | Unknown                     | [d96c2be612](https://linux-hardware.org/?probe=d96c2be612) | Nov 23, 2022 |
| Samsung       | 950XED                      | [48213c8f60](https://linux-hardware.org/?probe=48213c8f60) | Nov 23, 2022 |
| Samsung       | 950XED                      | [0c91469d8f](https://linux-hardware.org/?probe=0c91469d8f) | Nov 21, 2022 |
| Dell          | Latitude E5440              | [6d90726959](https://linux-hardware.org/?probe=6d90726959) | Nov 21, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [2bc3a22052](https://linux-hardware.org/?probe=2bc3a22052) | Nov 20, 2022 |
| MSI           | Vector GP66 12UGS           | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| Samsung       | 550XED                      | [06722b1fee](https://linux-hardware.org/?probe=06722b1fee) | Nov 16, 2022 |
| Samsung       | 950XED                      | [2558d99814](https://linux-hardware.org/?probe=2558d99814) | Nov 16, 2022 |
| Samsung       | 950XED                      | [ddcb4e15c7](https://linux-hardware.org/?probe=ddcb4e15c7) | Nov 14, 2022 |
| Samsung       | 550XED                      | [bbebe45363](https://linux-hardware.org/?probe=bbebe45363) | Nov 13, 2022 |
| Samsung       | 550XED                      | [60c1aa4cc9](https://linux-hardware.org/?probe=60c1aa4cc9) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [9cdaa4c88b](https://linux-hardware.org/?probe=9cdaa4c88b) | Nov 09, 2022 |
| Samsung       | 550XED                      | [fc6d96f9fe](https://linux-hardware.org/?probe=fc6d96f9fe) | Nov 06, 2022 |
| Samsung       | 550XED                      | [6db345f53d](https://linux-hardware.org/?probe=6db345f53d) | Nov 03, 2022 |
| Samsung       | 550XED                      | [6992db47be](https://linux-hardware.org/?probe=6992db47be) | Nov 02, 2022 |
| Samsung       | 950XED                      | [821bc59c17](https://linux-hardware.org/?probe=821bc59c17) | Nov 02, 2022 |
| Samsung       | 550XED                      | [3b04d21991](https://linux-hardware.org/?probe=3b04d21991) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| MS            | MPGIO                       | [4fc8637bf3](https://linux-hardware.org/?probe=4fc8637bf3) | Nov 01, 2022 |
| HP            | Pavilion dv6                | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| LG Electro... | 15Z980-HA76K                | [914156672d](https://linux-hardware.org/?probe=914156672d) | Oct 30, 2022 |
| Samsung       | 950XED                      | [350a0f9d44](https://linux-hardware.org/?probe=350a0f9d44) | Oct 28, 2022 |
| Samsung       | 550XED                      | [1ebb9be92b](https://linux-hardware.org/?probe=1ebb9be92b) | Oct 28, 2022 |
| Samsung       | 550XED                      | [110d85c2e0](https://linux-hardware.org/?probe=110d85c2e0) | Oct 27, 2022 |
| Samsung       | 950XED                      | [a636a02096](https://linux-hardware.org/?probe=a636a02096) | Oct 27, 2022 |
| LG Electro... | 15Z90N-HA76K                | [7805c272fb](https://linux-hardware.org/?probe=7805c272fb) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [866d0f49a2](https://linux-hardware.org/?probe=866d0f49a2) | Oct 20, 2022 |
| Dell          | Precision 7520              | [366eed3b66](https://linux-hardware.org/?probe=366eed3b66) | Oct 20, 2022 |
| Dell          | Precision 7520              | [8c2829bbb2](https://linux-hardware.org/?probe=8c2829bbb2) | Oct 19, 2022 |
| HP            | EliteBook 865 16 inch G9... | [8665ee6ba6](https://linux-hardware.org/?probe=8665ee6ba6) | Oct 19, 2022 |
| Apple         | MacBookPro12,1              | [7979753fa9](https://linux-hardware.org/?probe=7979753fa9) | Oct 15, 2022 |
| Apple         | MacBookPro16,1              | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d4797ada2a](https://linux-hardware.org/?probe=d4797ada2a) | Sep 28, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| ASUSTek       | Zephyrus S GX531GX_GX531... | [0041774402](https://linux-hardware.org/?probe=0041774402) | Aug 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YJC... | [ce2df1e866](https://linux-hardware.org/?probe=ce2df1e866) | Jul 18, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [87edfcaadf](https://linux-hardware.org/?probe=87edfcaadf) | Jul 09, 2022 |
| Lenovo        | ThinkPad S2 20GJA00S00      | [44eb58334d](https://linux-hardware.org/?probe=44eb58334d) | Jun 24, 2022 |
| LG Electro... | 14Z90N-VA76K                | [9e606a176f](https://linux-hardware.org/?probe=9e606a176f) | Jun 24, 2022 |
| Samsung       | 670Z5E                      | [95ec23c2e9](https://linux-hardware.org/?probe=95ec23c2e9) | Jun 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | [014c9a184e](https://linux-hardware.org/?probe=014c9a184e) | Jun 06, 2022 |
| LG Electro... | Z360-GH6SK                  | [cb91c2c2bd](https://linux-hardware.org/?probe=cb91c2c2bd) | Jun 02, 2022 |
| HP            | Spectre 13 x2 PC            | [9b67243691](https://linux-hardware.org/?probe=9b67243691) | May 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4f941ba9fe](https://linux-hardware.org/?probe=4f941ba9fe) | May 24, 2022 |
| Dell          | Vostro 3500                 | [617edab20c](https://linux-hardware.org/?probe=617edab20c) | May 20, 2022 |
| LG Electro... | 15Z990-HA50K                | [e5cf57d2f4](https://linux-hardware.org/?probe=e5cf57d2f4) | May 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [7286fd4e36](https://linux-hardware.org/?probe=7286fd4e36) | May 11, 2022 |
| Toshiba       | Satellite P50-B-103         | [6df44e9098](https://linux-hardware.org/?probe=6df44e9098) | Apr 29, 2022 |
| Teclast       | tPAD                        | [2b86292373](https://linux-hardware.org/?probe=2b86292373) | Apr 20, 2022 |
| Wolfnfox      | WF-TBAT                     | [7d04cc8361](https://linux-hardware.org/?probe=7d04cc8361) | Apr 13, 2022 |
| Teclast       | tPAD                        | [a9f93e289b](https://linux-hardware.org/?probe=a9f93e289b) | Apr 13, 2022 |
| MECHREVO      | Taitan Series GM7TG0M       | [948d29a218](https://linux-hardware.org/?probe=948d29a218) | Apr 10, 2022 |
| Teclast       | tPAD                        | [5eddc816df](https://linux-hardware.org/?probe=5eddc816df) | Apr 07, 2022 |
| HP            | Stream Notebook PC 13       | [1874ac7edf](https://linux-hardware.org/?probe=1874ac7edf) | Apr 03, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [f22fa67906](https://linux-hardware.org/?probe=f22fa67906) | Apr 01, 2022 |
| HP            | Stream Notebook PC 11       | [8fc09857a6](https://linux-hardware.org/?probe=8fc09857a6) | Apr 01, 2022 |
| Intel         | powered classmate PC        | [8ce4fa1757](https://linux-hardware.org/?probe=8ce4fa1757) | Apr 01, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6c36c54313](https://linux-hardware.org/?probe=6c36c54313) | Mar 31, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a8cacc7845](https://linux-hardware.org/?probe=a8cacc7845) | Mar 27, 2022 |
| MSI           | GF75 Thin 9SCXR             | [df19241968](https://linux-hardware.org/?probe=df19241968) | Mar 20, 2022 |
| MSI           | GF75 Thin 9SCXR             | [b3458eda8f](https://linux-hardware.org/?probe=b3458eda8f) | Mar 14, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [f86d99b8a1](https://linux-hardware.org/?probe=f86d99b8a1) | Feb 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [95ff70277e](https://linux-hardware.org/?probe=95ff70277e) | Feb 24, 2022 |
| Dell          | Inspiron 15 5510            | [bb04a03420](https://linux-hardware.org/?probe=bb04a03420) | Feb 23, 2022 |
| Dell          | Inspiron 15 5510            | [38ad42c186](https://linux-hardware.org/?probe=38ad42c186) | Feb 22, 2022 |
| LG Electro... | 17UD70P-PX76K               | [968b189e38](https://linux-hardware.org/?probe=968b189e38) | Feb 21, 2022 |
| LG Electro... | 17UD70P-PX76K               | [d8f6d95994](https://linux-hardware.org/?probe=d8f6d95994) | Feb 14, 2022 |
| HANSUNG CO... | EX58                        | [7c2a023530](https://linux-hardware.org/?probe=7c2a023530) | Feb 10, 2022 |
| HP            | Spectre 13 x2 PC            | [ed95e4c1c7](https://linux-hardware.org/?probe=ed95e4c1c7) | Feb 09, 2022 |
| HP            | Spectre 13 x2 PC            | [a597b083c9](https://linux-hardware.org/?probe=a597b083c9) | Feb 08, 2022 |
| Google        | Ampton                      | [0f1564bb4a](https://linux-hardware.org/?probe=0f1564bb4a) | Feb 06, 2022 |
| Apple         | MacBookPro5,3               | [7742fa4642](https://linux-hardware.org/?probe=7742fa4642) | Feb 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [65a6ca3880](https://linux-hardware.org/?probe=65a6ca3880) | Feb 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [144717a1f1](https://linux-hardware.org/?probe=144717a1f1) | Feb 04, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [7f9793a709](https://linux-hardware.org/?probe=7f9793a709) | Jan 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [2c22ac6a5f](https://linux-hardware.org/?probe=2c22ac6a5f) | Jan 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [882dab7b0e](https://linux-hardware.org/?probe=882dab7b0e) | Jan 22, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [c081d60b2a](https://linux-hardware.org/?probe=c081d60b2a) | Jan 22, 2022 |
| Apple         | MacBookPro5,5               | [11d1870f98](https://linux-hardware.org/?probe=11d1870f98) | Jan 21, 2022 |
| LG Electro... | 17UD70P-PX76K               | [d0d21d2892](https://linux-hardware.org/?probe=d0d21d2892) | Jan 18, 2022 |
| LG Electro... | 16ZD90P-GX7LK               | [0870fd8772](https://linux-hardware.org/?probe=0870fd8772) | Dec 29, 2021 |
| Lenovo        | G480 20149                  | [08a0d07d28](https://linux-hardware.org/?probe=08a0d07d28) | Dec 28, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [a8fbe33d19](https://linux-hardware.org/?probe=a8fbe33d19) | Dec 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [ff620ffdcd](https://linux-hardware.org/?probe=ff620ffdcd) | Dec 07, 2021 |
| Jooyontech... | J3GP Pro                    | [6f13d68344](https://linux-hardware.org/?probe=6f13d68344) | Dec 04, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | [c7cc850f29](https://linux-hardware.org/?probe=c7cc850f29) | Dec 03, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | [901fdc3726](https://linux-hardware.org/?probe=901fdc3726) | Dec 03, 2021 |
| LG Electro... | 17UD70P-PX76K               | [b4c7522ea3](https://linux-hardware.org/?probe=b4c7522ea3) | Nov 15, 2021 |
| LG Electro... | 15Z990-HA50K                | [6f5255e0f2](https://linux-hardware.org/?probe=6f5255e0f2) | Nov 01, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [70074ebee1](https://linux-hardware.org/?probe=70074ebee1) | Nov 01, 2021 |
| ASUSTek       | X556URK                     | [212240b258](https://linux-hardware.org/?probe=212240b258) | Oct 29, 2021 |
| LG Electro... | 17ZD90P-GX7LK               | [23aa2c83ae](https://linux-hardware.org/?probe=23aa2c83ae) | Oct 27, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2f6634b953](https://linux-hardware.org/?probe=2f6634b953) | Oct 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fb8b55960a](https://linux-hardware.org/?probe=fb8b55960a) | Oct 20, 2021 |
| Lenovo        | ThinkPad W530 24475HU       | [b8973b3b0a](https://linux-hardware.org/?probe=b8973b3b0a) | Oct 02, 2021 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [e93b95fc3c](https://linux-hardware.org/?probe=e93b95fc3c) | Sep 30, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | [fbc7a613a6](https://linux-hardware.org/?probe=fbc7a613a6) | Sep 29, 2021 |
| HANSUNG CO... | TFX4150H                    | [11f2fbef85](https://linux-hardware.org/?probe=11f2fbef85) | Sep 29, 2021 |
| ASUSTek       | U36JC                       | [c6e87f1fb7](https://linux-hardware.org/?probe=c6e87f1fb7) | Sep 23, 2021 |
| Samsung       | 730QCJ/730QCR               | [54cd6887df](https://linux-hardware.org/?probe=54cd6887df) | Sep 21, 2021 |
| Clevo         | M740T/M760T                 | [7731b8340f](https://linux-hardware.org/?probe=7731b8340f) | Sep 17, 2021 |
| Samsung       | 400B4C/400B5C/200B4C/200... | [581ab7ecde](https://linux-hardware.org/?probe=581ab7ecde) | Sep 17, 2021 |
| HP            | Pavilion Laptop 15z-eh00... | [33233b370e](https://linux-hardware.org/?probe=33233b370e) | Aug 30, 2021 |
| LG Electro... | 14Z90N-VA76K                | [df36a7a61c](https://linux-hardware.org/?probe=df36a7a61c) | Aug 22, 2021 |
| Lenovo        | XiaoXin Air 13IWL 81J8      | [e68dfe0824](https://linux-hardware.org/?probe=e68dfe0824) | Aug 19, 2021 |
| Apple         | MacBookPro15,2              | [c722c00c56](https://linux-hardware.org/?probe=c722c00c56) | Aug 18, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e47beb0587](https://linux-hardware.org/?probe=e47beb0587) | Aug 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e7997203d4](https://linux-hardware.org/?probe=e7997203d4) | Aug 11, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [3147760301](https://linux-hardware.org/?probe=3147760301) | Aug 07, 2021 |
| Dell          | XPS 13 7390                 | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| LG Electro... | 17UD70P-PX76K               | [dc6d809e73](https://linux-hardware.org/?probe=dc6d809e73) | Jul 23, 2021 |
| LG Electro... | 17UD70P-PX76K               | [c0869b1919](https://linux-hardware.org/?probe=c0869b1919) | Jul 23, 2021 |
| HP            | OMEN by Laptop              | [2392366002](https://linux-hardware.org/?probe=2392366002) | Jul 16, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [9c2b77b3c6](https://linux-hardware.org/?probe=9c2b77b3c6) | Jun 24, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [99b25335b3](https://linux-hardware.org/?probe=99b25335b3) | Jun 22, 2021 |
| MSI           | GF63 Thin 9SC               | [98faadcfa3](https://linux-hardware.org/?probe=98faadcfa3) | Jun 10, 2021 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [5742c8e4e5](https://linux-hardware.org/?probe=5742c8e4e5) | May 28, 2021 |
| Lenovo        | G500 20236                  | [2aca6cd805](https://linux-hardware.org/?probe=2aca6cd805) | May 27, 2021 |
| Dell          | Latitude E6400              | [2a4c5f6eec](https://linux-hardware.org/?probe=2a4c5f6eec) | May 25, 2021 |
| Samsung       | R440/R480                   | [777c05d80b](https://linux-hardware.org/?probe=777c05d80b) | May 19, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [15a742842f](https://linux-hardware.org/?probe=15a742842f) | May 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f3cb68f8cf](https://linux-hardware.org/?probe=f3cb68f8cf) | May 13, 2021 |
| HP            | EliteBook 8540p (WQ983PA... | [28b1df49ae](https://linux-hardware.org/?probe=28b1df49ae) | May 11, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | [035481a413](https://linux-hardware.org/?probe=035481a413) | May 05, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [473f17b0f1](https://linux-hardware.org/?probe=473f17b0f1) | May 01, 2021 |
| LG Electro... | 15ND530-GX30K               | [9d700ce0b6](https://linux-hardware.org/?probe=9d700ce0b6) | Apr 30, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [84f31a5fd7](https://linux-hardware.org/?probe=84f31a5fd7) | Apr 28, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | [410e4fd232](https://linux-hardware.org/?probe=410e4fd232) | Apr 22, 2021 |
| HP            | Stream Notebook PC 13       | [0bf3f6f761](https://linux-hardware.org/?probe=0bf3f6f761) | Apr 15, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [c5e7a3d16e](https://linux-hardware.org/?probe=c5e7a3d16e) | Apr 09, 2021 |
| Notebook      | NL5xRU                      | [7cac175bde](https://linux-hardware.org/?probe=7cac175bde) | Apr 07, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [51931e3821](https://linux-hardware.org/?probe=51931e3821) | Apr 05, 2021 |
| Samsung       | 270E5J/2570EJ               | [b36716f462](https://linux-hardware.org/?probe=b36716f462) | Apr 02, 2021 |
| Samsung       | 400B4B/400B5B/200B4B/200... | [af785987c5](https://linux-hardware.org/?probe=af785987c5) | Mar 29, 2021 |
| LG Electro... | Z435-GE40K                  | [41dfc50f20](https://linux-hardware.org/?probe=41dfc50f20) | Mar 27, 2021 |
| Alienware     | m15 R4                      | [33977ceca8](https://linux-hardware.org/?probe=33977ceca8) | Mar 08, 2021 |
| Notebook      | W330SU2                     | [e5e71a4e94](https://linux-hardware.org/?probe=e5e71a4e94) | Mar 05, 2021 |
| Dell          | Inspiron 5590               | [94e3d38a99](https://linux-hardware.org/?probe=94e3d38a99) | Mar 04, 2021 |
| Notebook      | N650DU                      | [beef9a4540](https://linux-hardware.org/?probe=beef9a4540) | Feb 24, 2021 |
| HP            | Pavilion dv3                | [d563465019](https://linux-hardware.org/?probe=d563465019) | Jan 23, 2021 |
| HP            | Pavilion dv3                | [7140d63f79](https://linux-hardware.org/?probe=7140d63f79) | Jan 16, 2021 |
| LG Electro... | 13Z940-MF6BL                | [ee9f312333](https://linux-hardware.org/?probe=ee9f312333) | Jan 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [28d2ddf944](https://linux-hardware.org/?probe=28d2ddf944) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FA706II_FA706... | [cbc872e471](https://linux-hardware.org/?probe=cbc872e471) | Dec 29, 2020 |
| HANSUNG CO... | TFX5470H                    | [4f038027ac](https://linux-hardware.org/?probe=4f038027ac) | Dec 27, 2020 |
| HANSUNG CO... | TFX5470H                    | [659c45927e](https://linux-hardware.org/?probe=659c45927e) | Dec 26, 2020 |
| HP            | Pavilion g6                 | [9b2e1ccb17](https://linux-hardware.org/?probe=9b2e1ccb17) | Dec 15, 2020 |
| HP            | Pavilion g6                 | [01bd113f0d](https://linux-hardware.org/?probe=01bd113f0d) | Dec 15, 2020 |
| MSI           | PS42 Modern 8MO             | [c469679bd0](https://linux-hardware.org/?probe=c469679bd0) | Dec 14, 2020 |
| HP            | ProBook 635 Aero G7 Note... | [9ff7890a24](https://linux-hardware.org/?probe=9ff7890a24) | Dec 11, 2020 |
| Samsung       | 760XBE                      | [7b117d1e93](https://linux-hardware.org/?probe=7b117d1e93) | Dec 08, 2020 |
| Samsung       | R440/R480                   | [2c57659a41](https://linux-hardware.org/?probe=2c57659a41) | Dec 06, 2020 |
| Acer          | Swift SF314-54              | [e387afac15](https://linux-hardware.org/?probe=e387afac15) | Nov 29, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [b6570c8388](https://linux-hardware.org/?probe=b6570c8388) | Nov 28, 2020 |
| Apple         | MacBookPro10,1              | [ecfaa7232b](https://linux-hardware.org/?probe=ecfaa7232b) | Nov 28, 2020 |
| HP            | EliteBook 840 G1            | [eb842cd3c4](https://linux-hardware.org/?probe=eb842cd3c4) | Nov 25, 2020 |
| HP            | EliteBook 840 G1            | [2a9cc167d3](https://linux-hardware.org/?probe=2a9cc167d3) | Nov 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| Samsung       | R59P/R60P/R61P              | [e4a465ff4c](https://linux-hardware.org/?probe=e4a465ff4c) | Nov 15, 2020 |
| Samsung       | R59P/R60P/R61P              | [8a39cadb17](https://linux-hardware.org/?probe=8a39cadb17) | Nov 14, 2020 |
| Samsung       | SX11S                       | [7946db3be4](https://linux-hardware.org/?probe=7946db3be4) | Nov 05, 2020 |
| Lenovo        | ThinkPad T580 20L9S06H00    | [4cda554e60](https://linux-hardware.org/?probe=4cda554e60) | Oct 31, 2020 |
| LG Electro... | 14ZB990-GP70ML              | [7184b7e890](https://linux-hardware.org/?probe=7184b7e890) | Oct 29, 2020 |
| HANSUNG CO... | TFX5470H                    | [7a0c7ef25d](https://linux-hardware.org/?probe=7a0c7ef25d) | Oct 22, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [7f2d533ddf](https://linux-hardware.org/?probe=7f2d533ddf) | Oct 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [57c9a2fdbb](https://linux-hardware.org/?probe=57c9a2fdbb) | Oct 12, 2020 |
| Acer          | Aspire A514-52              | [151c57e477](https://linux-hardware.org/?probe=151c57e477) | Oct 11, 2020 |
| Lenovo        | ThinkPad E595 20NFS01P00    | [5cce7e56d5](https://linux-hardware.org/?probe=5cce7e56d5) | Oct 02, 2020 |
| MSI           | MS-16F1                     | [94a744ecb7](https://linux-hardware.org/?probe=94a744ecb7) | Oct 01, 2020 |
| MSI           | GE75 Raider 10SF            | [c5f31d8ff8](https://linux-hardware.org/?probe=c5f31d8ff8) | Sep 21, 2020 |
| MSI           | GE75 Raider 10SF            | [80b54a584c](https://linux-hardware.org/?probe=80b54a584c) | Sep 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [335490808b](https://linux-hardware.org/?probe=335490808b) | Sep 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [611b4d4515](https://linux-hardware.org/?probe=611b4d4515) | Sep 12, 2020 |
| Samsung       | SX11S                       | [de5f3f5244](https://linux-hardware.org/?probe=de5f3f5244) | Sep 10, 2020 |
| Dell          | XPS 15 7590                 | [0ed21172b2](https://linux-hardware.org/?probe=0ed21172b2) | Sep 07, 2020 |
| HP            | Laptop 14s-cf1xxx           | [56e8c74784](https://linux-hardware.org/?probe=56e8c74784) | Sep 05, 2020 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [5b29fd8262](https://linux-hardware.org/?probe=5b29fd8262) | Sep 05, 2020 |
| HP            | Laptop 15s-du0xxx           | [226702f09a](https://linux-hardware.org/?probe=226702f09a) | Sep 05, 2020 |
| LG Electro... | 15ND530-GX30K               | [8f8a5ce10c](https://linux-hardware.org/?probe=8f8a5ce10c) | Sep 04, 2020 |
| Lenovo        | ThinkPad X390 20SCCTO1WW    | [765a0cde4c](https://linux-hardware.org/?probe=765a0cde4c) | Sep 03, 2020 |
| HP            | Laptop 15s-du0xxx           | [2ef3a6b6c8](https://linux-hardware.org/?probe=2ef3a6b6c8) | Sep 03, 2020 |
| Acer          | Swift SF315-41              | [c57a2c8249](https://linux-hardware.org/?probe=c57a2c8249) | Aug 26, 2020 |
| LG Electro... | A520-DEHRK                  | [33e6f6950c](https://linux-hardware.org/?probe=33e6f6950c) | Aug 20, 2020 |
| LG Electro... | ZD360-GD30K                 | [5f695a5cfd](https://linux-hardware.org/?probe=5f695a5cfd) | Aug 19, 2020 |
| Lenovo        | ThinkPad L420 7829AZ2       | [af5c485d91](https://linux-hardware.org/?probe=af5c485d91) | Aug 17, 2020 |
| ASUSTek       | UX31E                       | [107d53bd73](https://linux-hardware.org/?probe=107d53bd73) | Aug 14, 2020 |
| Lenovo        | ThinkPad Edge E440 20C50... | [e2a554e507](https://linux-hardware.org/?probe=e2a554e507) | Aug 11, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [4657a3e758](https://linux-hardware.org/?probe=4657a3e758) | Aug 11, 2020 |
| Lenovo        | ThinkPad T420s 417429U      | [a0cc9e062e](https://linux-hardware.org/?probe=a0cc9e062e) | Aug 09, 2020 |
| MSI           | GX60 3CC                    | [dabfcf887e](https://linux-hardware.org/?probe=dabfcf887e) | Aug 05, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [806b0f6ffc](https://linux-hardware.org/?probe=806b0f6ffc) | Aug 04, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [03dcb81800](https://linux-hardware.org/?probe=03dcb81800) | Aug 04, 2020 |
| LG Electro... | 14ZB990-GP70ML              | [953e68f29d](https://linux-hardware.org/?probe=953e68f29d) | Jul 29, 2020 |
| Samsung       | X120/X170/X171              | [d52c424e0f](https://linux-hardware.org/?probe=d52c424e0f) | Jul 12, 2020 |
| MSI           | PS63 Modern 8RC             | [1f2f8bb2cf](https://linux-hardware.org/?probe=1f2f8bb2cf) | Jul 06, 2020 |
| MSI           | PS63 Modern 8RC             | [ed2dc1f4eb](https://linux-hardware.org/?probe=ed2dc1f4eb) | Jul 05, 2020 |
| Sony          | SVF1421ESGW                 | [025b1a05fe](https://linux-hardware.org/?probe=025b1a05fe) | Jun 29, 2020 |
| ASUSTek       | X553SA                      | [de56d8fe26](https://linux-hardware.org/?probe=de56d8fe26) | Jun 23, 2020 |
| MSI           | GX60 3CC                    | [41702d8f8c](https://linux-hardware.org/?probe=41702d8f8c) | Jun 14, 2020 |
| MSI           | GX60 3CC                    | [16345ce4e3](https://linux-hardware.org/?probe=16345ce4e3) | Jun 14, 2020 |
| TG            | NXI-A7000 Series            | [20018e6c2a](https://linux-hardware.org/?probe=20018e6c2a) | Jun 07, 2020 |
| Dell          | G3 3579                     | [f21ec2528f](https://linux-hardware.org/?probe=f21ec2528f) | Jun 06, 2020 |
| Lenovo        | ThinkPad E495 20NES0WU00    | [bd7072c5e9](https://linux-hardware.org/?probe=bd7072c5e9) | May 27, 2020 |
| HP            | Laptop 15-db1xxx            | [229612b5fa](https://linux-hardware.org/?probe=229612b5fa) | May 26, 2020 |
| LG Electro... | 17UD790-PX76K               | [ac4f8e9cc6](https://linux-hardware.org/?probe=ac4f8e9cc6) | May 24, 2020 |
| LG Electro... | 17UD790-PX76K               | [9bb4fea940](https://linux-hardware.org/?probe=9bb4fea940) | May 24, 2020 |
| HP            | Laptop 15-db1xxx            | [65f85ef8e9](https://linux-hardware.org/?probe=65f85ef8e9) | May 20, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b3a561d5db](https://linux-hardware.org/?probe=b3a561d5db) | May 20, 2020 |
| MSI           | Prestige 15 A10SC           | [69c9f3bce6](https://linux-hardware.org/?probe=69c9f3bce6) | May 17, 2020 |
| Samsung       | 570Z5E/580Z5E               | [435579b481](https://linux-hardware.org/?probe=435579b481) | May 16, 2020 |
| Samsung       | 570Z5E/580Z5E               | [5e2ed0ac77](https://linux-hardware.org/?probe=5e2ed0ac77) | May 16, 2020 |
| LG Electro... | 14ZB990-GP70ML              | [dc05f2344d](https://linux-hardware.org/?probe=dc05f2344d) | May 16, 2020 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [5919a15425](https://linux-hardware.org/?probe=5919a15425) | May 11, 2020 |
| Lenovo        | ThinkPad X220 4290P39       | [1b5c469306](https://linux-hardware.org/?probe=1b5c469306) | May 02, 2020 |
| Dell          | XPS 15 7590                 | [0bbf773840](https://linux-hardware.org/?probe=0bbf773840) | Apr 27, 2020 |
| Dell          | XPS 15 7590                 | [5348bea534](https://linux-hardware.org/?probe=5348bea534) | Apr 27, 2020 |
| Lenovo        | ThinkPad X230 2325KZ5       | [150d9801f0](https://linux-hardware.org/?probe=150d9801f0) | Apr 21, 2020 |
| Lenovo        | ThinkPad E495 20NES0WU00    | [fb49bbe9f1](https://linux-hardware.org/?probe=fb49bbe9f1) | Apr 18, 2020 |
| Dell          | Latitude D630               | [0540c0a191](https://linux-hardware.org/?probe=0540c0a191) | Apr 15, 2020 |
| HP            | Pavilion Gaming Notebook    | [4d5a5a3a34](https://linux-hardware.org/?probe=4d5a5a3a34) | Apr 14, 2020 |
| LG Electro... | R490-KR6WK                  | [b0c23e23f7](https://linux-hardware.org/?probe=b0c23e23f7) | Mar 21, 2020 |
| HP            | Pavilion dv7                | [61bbb3da8a](https://linux-hardware.org/?probe=61bbb3da8a) | Mar 12, 2020 |
| LG Electro... | A505-K.AFC4L                | [33b72b423b](https://linux-hardware.org/?probe=33b72b423b) | Feb 26, 2020 |
| Toshiba       | Satellite L655              | [8212e2eb65](https://linux-hardware.org/?probe=8212e2eb65) | Feb 13, 2020 |
| MSI           | Prestige 14 A10SC           | [00af81dd32](https://linux-hardware.org/?probe=00af81dd32) | Feb 12, 2020 |
| MSI           | Prestige 14 A10SC           | [dac2e1709e](https://linux-hardware.org/?probe=dac2e1709e) | Feb 12, 2020 |
| MSI           | GF63 Thin 9SC               | [47b9bc192c](https://linux-hardware.org/?probe=47b9bc192c) | Jan 29, 2020 |
| MSI           | GF63 Thin 9SC               | [21dbcd5aca](https://linux-hardware.org/?probe=21dbcd5aca) | Jan 28, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [6515ce1c97](https://linux-hardware.org/?probe=6515ce1c97) | Jan 23, 2020 |
| HP            | ProBook 453                 | [ad3d1ff0fc](https://linux-hardware.org/?probe=ad3d1ff0fc) | Dec 27, 2019 |
| Lenovo        | ThinkPad E565 20EYA007KD    | [c1c9dd614a](https://linux-hardware.org/?probe=c1c9dd614a) | Dec 17, 2019 |
| HP            | Laptop 14s-cf1xxx           | [61765ee913](https://linux-hardware.org/?probe=61765ee913) | Dec 11, 2019 |
| HP            | Laptop 14s-cf1xxx           | [fa008b24fc](https://linux-hardware.org/?probe=fa008b24fc) | Dec 11, 2019 |
| HP            | Pavilion 15                 | [5f9b510e87](https://linux-hardware.org/?probe=5f9b510e87) | Oct 28, 2019 |
| MSI           | MS-1675                     | [c5bf6f209a](https://linux-hardware.org/?probe=c5bf6f209a) | Sep 07, 2019 |
| MSI           | MS-1675                     | [be1db420ea](https://linux-hardware.org/?probe=be1db420ea) | Sep 07, 2019 |
| AMI           | Cherry Trail CR             | [caaebe3071](https://linux-hardware.org/?probe=caaebe3071) | Sep 01, 2019 |
| AMI           | Cherry Trail CR             | [5637a7d5ca](https://linux-hardware.org/?probe=5637a7d5ca) | Sep 01, 2019 |
| Lenovo        | U41-70 80JV                 | [0af65c15a0](https://linux-hardware.org/?probe=0af65c15a0) | Aug 30, 2019 |
| IMUZ          | StormBook 15                | [daf3b9ea48](https://linux-hardware.org/?probe=daf3b9ea48) | Aug 07, 2019 |
| Samsung       | 800G5M/800G5W               | [01cb2e9401](https://linux-hardware.org/?probe=01cb2e9401) | May 22, 2019 |
| HP            | Laptop 15-db1xxx            | [e318a9dac5](https://linux-hardware.org/?probe=e318a9dac5) | May 10, 2019 |
| Sony          | VPCEA36FK                   | [6c4b2a047b](https://linux-hardware.org/?probe=6c4b2a047b) | May 01, 2019 |
| Dell          | Inspiron 7559               | [fb5730a29c](https://linux-hardware.org/?probe=fb5730a29c) | Apr 17, 2019 |
| Apple         | MacBookPro14,1              | [606c70c0db](https://linux-hardware.org/?probe=606c70c0db) | Apr 15, 2019 |
| Dell          | Inspiron 7570               | [f46c9c93f9](https://linux-hardware.org/?probe=f46c9c93f9) | Apr 12, 2019 |
| Dell          | Inspiron 7570               | [e1c522656b](https://linux-hardware.org/?probe=e1c522656b) | Apr 12, 2019 |
| Samsung       | 905S3G/906S3G/915S3G        | [8e21d7bf0c](https://linux-hardware.org/?probe=8e21d7bf0c) | Mar 30, 2019 |
| Lenovo        | ThinkPad P52s 20LBCTO1WW    | [ed9f709e73](https://linux-hardware.org/?probe=ed9f709e73) | Feb 20, 2019 |
| Samsung       | RC420/RC520/RC720           | [4a0abda7de](https://linux-hardware.org/?probe=4a0abda7de) | Dec 14, 2018 |
| AVERATEC      | 6600                        | [a55a983b35](https://linux-hardware.org/?probe=a55a983b35) | Nov 11, 2018 |
| AVERATEC      | 6600                        | [8ca54d992c](https://linux-hardware.org/?probe=8ca54d992c) | Nov 11, 2018 |
| Dell          | XPS 15 9560                 | [d5d9e2cef1](https://linux-hardware.org/?probe=d5d9e2cef1) | Nov 04, 2018 |
| LG Electro... | R510                        | [f7b3f1d4a5](https://linux-hardware.org/?probe=f7b3f1d4a5) | Oct 13, 2018 |
| ASUSTek       | N56JR                       | [27253306bc](https://linux-hardware.org/?probe=27253306bc) | Dec 28, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 52        | 18.84%  |
| Ubuntu 22.04       | 26        | 9.42%   |
| Ubuntu 18.04       | 21        | 7.61%   |
| Gooroom            | 8         | 2.9%    |
| Arch Rolling       | 8         | 2.9%    |
| Ubuntu 21.10       | 7         | 2.54%   |
| Debian 11          | 7         | 2.54%   |
| Fedora 38          | 6         | 2.17%   |
| Arch               | 6         | 2.17%   |
| Zorin 16           | 4         | 1.45%   |
| Linux Mint 20.3    | 4         | 1.45%   |
| Linux Mint 20.1    | 4         | 1.45%   |
| Fedora 37          | 4         | 1.45%   |
| Fedora 36          | 4         | 1.45%   |
| Fedora 32          | 4         | 1.45%   |
| Ubuntu 19.10       | 3         | 1.09%   |
| Ubuntu 19.04       | 3         | 1.09%   |
| ROSA R11           | 3         | 1.09%   |
| OpenMandriva 4.2   | 3         | 1.09%   |
| Kubuntu 22.04      | 3         | 1.09%   |
| HamoniKR 4.0       | 3         | 1.09%   |
| Fedora 34          | 3         | 1.09%   |
| Debian 10          | 3         | 1.09%   |
| CentOS 8           | 3         | 1.09%   |
| Zorin 15           | 2         | 0.72%   |
| Xubuntu 22.04      | 2         | 0.72%   |
| Ubuntu MATE 18.04  | 2         | 0.72%   |
| Ubuntu 22.10       | 2         | 0.72%   |
| SteamOS 3.4.4      | 2         | 0.72%   |
| ROSA R10           | 2         | 0.72%   |
| Pop!_OS 21.10      | 2         | 0.72%   |
| OpenMandriva 23.01 | 2         | 0.72%   |
| Manjaro 21.3.0     | 2         | 0.72%   |
| LMDE 5             | 2         | 0.72%   |
| Linux Mint 21.1    | 2         | 0.72%   |
| Linux Mint 20      | 2         | 0.72%   |
| KDE neon 22.04     | 2         | 0.72%   |
| KDE neon 20.04     | 2         | 0.72%   |
| Endless 3.8.5      | 2         | 0.72%   |
| Xubuntu 20.04      | 1         | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 114       | 42.86%  |
| Fedora       | 22        | 8.27%   |
| Linux Mint   | 14        | 5.26%   |
| Arch         | 12        | 4.51%   |
| Debian       | 11        | 4.14%   |
| OpenMandriva | 9         | 3.38%   |
| Manjaro      | 9         | 3.38%   |
| Gooroom      | 9         | 3.38%   |
| Zorin        | 6         | 2.26%   |
| Kubuntu      | 6         | 2.26%   |
| ROSA         | 5         | 1.88%   |
| No1 Linux    | 5         | 1.88%   |
| Endless      | 5         | 1.88%   |
| SteamOS      | 4         | 1.5%    |
| Pop!_OS      | 4         | 1.5%    |
| KDE neon     | 4         | 1.5%    |
| HamoniKR     | 4         | 1.5%    |
| CentOS       | 4         | 1.5%    |
| Xubuntu      | 3         | 1.13%   |
| Ubuntu Unity | 2         | 0.75%   |
| Ubuntu MATE  | 2         | 0.75%   |
| LMDE         | 2         | 0.75%   |
| EndeavourOS  | 2         | 0.75%   |
| Xero         | 1         | 0.38%   |
| openSUSE     | 1         | 0.38%   |
| Lubuntu      | 1         | 0.38%   |
| Kali         | 1         | 0.38%   |
| Gentoo       | 1         | 0.38%   |
| Garuda Linux | 1         | 0.38%   |
| ArcoLinux    | 1         | 0.38%   |
| Alpine       | 1         | 0.38%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Notebooks | Percent |
|--------------------------------|-----------|---------|
| 5.15.0-53-generic              | 5         | 1.73%   |
| 5.10.0-19-amd64                | 5         | 1.73%   |
| 5.4.0-42-generic               | 4         | 1.38%   |
| 5.19.0-45-generic              | 4         | 1.38%   |
| 5.15.0-58-generic              | 4         | 1.38%   |
| 5.15.0-56-generic              | 4         | 1.38%   |
| 5.10.0-17-amd64                | 4         | 1.38%   |
| 4.19.0-9-amd64                 | 4         | 1.38%   |
| 5.8.0-43-generic               | 3         | 1.04%   |
| 5.4.0-58-generic               | 3         | 1.04%   |
| 5.4.0-26-generic               | 3         | 1.04%   |
| 5.3.0-40-generic               | 3         | 1.04%   |
| 5.19.15-201.fc36.x86_64        | 3         | 1.04%   |
| 5.13.0-valve36-1-neptune       | 3         | 1.04%   |
| 5.13.0-28-generic              | 3         | 1.04%   |
| 5.11.0-37-generic              | 3         | 1.04%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 3         | 1.04%   |
| 6.1.1-desktop-1omv2290         | 2         | 0.69%   |
| 5.8.4-200.fc32.x86_64          | 2         | 0.69%   |
| 5.8.0-53-generic               | 2         | 0.69%   |
| 5.4.0-81-generic               | 2         | 0.69%   |
| 5.4.0-56-generic               | 2         | 0.69%   |
| 5.4.0-48-generic               | 2         | 0.69%   |
| 5.4.0-39-generic               | 2         | 0.69%   |
| 5.4.0-33-generic               | 2         | 0.69%   |
| 5.4.0-31-generic               | 2         | 0.69%   |
| 5.4.0-29-generic               | 2         | 0.69%   |
| 5.3.0-46-generic               | 2         | 0.69%   |
| 5.19.0-46-generic              | 2         | 0.69%   |
| 5.19.0-43-generic              | 2         | 0.69%   |
| 5.18.5-1-MANJARO               | 2         | 0.69%   |
| 5.15.0-67-generic              | 2         | 0.69%   |
| 5.15.0-60-generic              | 2         | 0.69%   |
| 5.15.0-52-generic              | 2         | 0.69%   |
| 5.15.0-33-generic              | 2         | 0.69%   |
| 5.15.0-27-generic              | 2         | 0.69%   |
| 5.13.0-44-generic              | 2         | 0.69%   |
| 5.13.0-27-generic              | 2         | 0.69%   |
| 5.10.14-desktop-1omv4002       | 2         | 0.69%   |
| 5.0.0-37-generic               | 2         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 17.86%  |
| 5.15.0  | 31        | 11.07%  |
| 5.13.0  | 17        | 6.07%   |
| 5.19.0  | 14        | 5%      |
| 5.8.0   | 12        | 4.29%   |
| 5.10.0  | 12        | 4.29%   |
| 5.11.0  | 10        | 3.57%   |
| 4.15.0  | 10        | 3.57%   |
| 5.3.0   | 9         | 3.21%   |
| 5.0.0   | 7         | 2.5%    |
| 4.19.0  | 7         | 2.5%    |
| 4.18.0  | 7         | 2.5%    |
| 6.1.0   | 3         | 1.07%   |
| 5.19.15 | 3         | 1.07%   |
| 6.2.8   | 2         | 0.71%   |
| 6.1.1   | 2         | 0.71%   |
| 6.0.0   | 2         | 0.71%   |
| 5.8.4   | 2         | 0.71%   |
| 5.18.5  | 2         | 0.71%   |
| 5.16.19 | 2         | 0.71%   |
| 5.15.11 | 2         | 0.71%   |
| 5.14.0  | 2         | 0.71%   |
| 5.10.14 | 2         | 0.71%   |
| 4.9.60  | 2         | 0.71%   |
| 6.5.0   | 1         | 0.36%   |
| 6.4.9   | 1         | 0.36%   |
| 6.4.12  | 1         | 0.36%   |
| 6.3.8   | 1         | 0.36%   |
| 6.3.5   | 1         | 0.36%   |
| 6.3.4   | 1         | 0.36%   |
| 6.2.9   | 1         | 0.36%   |
| 6.2.6   | 1         | 0.36%   |
| 6.2.5   | 1         | 0.36%   |
| 6.2.2   | 1         | 0.36%   |
| 6.2.15  | 1         | 0.36%   |
| 6.2.14  | 1         | 0.36%   |
| 6.2.13  | 1         | 0.36%   |
| 6.2.0   | 1         | 0.36%   |
| 6.1.9   | 1         | 0.36%   |
| 6.1.55  | 1         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 52        | 18.71%  |
| 5.15    | 39        | 14.03%  |
| 5.19    | 18        | 6.47%   |
| 5.13    | 18        | 6.47%   |
| 5.8     | 16        | 5.76%   |
| 5.10    | 16        | 5.76%   |
| 5.11    | 15        | 5.4%    |
| 4.15    | 11        | 3.96%   |
| 6.2     | 10        | 3.6%    |
| 6.1     | 10        | 3.6%    |
| 5.3     | 10        | 3.6%    |
| 4.19    | 8         | 2.88%   |
| 4.18    | 8         | 2.88%   |
| 5.0     | 7         | 2.52%   |
| 6.0     | 6         | 2.16%   |
| 5.16    | 5         | 1.8%    |
| 5.12    | 5         | 1.8%    |
| 5.14    | 4         | 1.44%   |
| 6.3     | 3         | 1.08%   |
| 5.18    | 3         | 1.08%   |
| 6.4     | 2         | 0.72%   |
| 5.6     | 2         | 0.72%   |
| 4.9     | 2         | 0.72%   |
| 6.5     | 1         | 0.36%   |
| 5.9     | 1         | 0.36%   |
| 5.7     | 1         | 0.36%   |
| 5.5     | 1         | 0.36%   |
| 5.2     | 1         | 0.36%   |
| 5.17    | 1         | 0.36%   |
| 4.16    | 1         | 0.36%   |
| 3.10    | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 254       | 98.45%  |
| i686    | 3         | 1.16%   |
| aarch64 | 1         | 0.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 145       | 54.72%  |
| KDE5            | 41        | 15.47%  |
| Unknown         | 19        | 7.17%   |
| X-Cinnamon      | 13        | 4.91%   |
| GNOME Flashback | 9         | 3.4%    |
| XFCE            | 8         | 3.02%   |
| LXDE            | 8         | 3.02%   |
| Cinnamon        | 6         | 2.26%   |
| i3              | 5         | 1.89%   |
| KDE4            | 3         | 1.13%   |
| KDE             | 3         | 1.13%   |
| Unity           | 2         | 0.75%   |
| MATE            | 2         | 0.75%   |
| sway            | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 180       | 68.7%   |
| Wayland | 57        | 21.76%  |
| Unknown | 15        | 5.73%   |
| Tty     | 10        | 3.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 114       | 42.7%   |
| GDM     | 54        | 20.22%  |
| GDM3    | 33        | 12.36%  |
| SDDM    | 31        | 11.61%  |
| LightDM | 18        | 6.74%   |
| TDM     | 13        | 4.87%   |
| KDM     | 3         | 1.12%   |
| XDM     | 1         | 0.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ko_KR   | 115       | 43.23%  |
| en_US   | 100       | 37.59%  |
| Unknown | 28        | 10.53%  |
| C       | 6         | 2.26%   |
| en_CA   | 4         | 1.5%    |
| zh_CN   | 3         | 1.13%   |
| id_ID   | 2         | 0.75%   |
| fr_FR   | 2         | 0.75%   |
| vi_VN   | 1         | 0.38%   |
| pt_BR   | 1         | 0.38%   |
| en_NZ   | 1         | 0.38%   |
| el_GR   | 1         | 0.38%   |
| ba_RU   | 1         | 0.38%   |
| ar_EG   | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 183       | 70.66%  |
| BIOS | 76        | 29.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 206       | 78.63%  |
| Btrfs   | 25        | 9.54%   |
| Tmpfs   | 7         | 2.67%   |
| Overlay | 7         | 2.67%   |
| Xfs     | 6         | 2.29%   |
| Unknown | 6         | 2.29%   |
| Zfs     | 4         | 1.53%   |
| Rootfs  | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 138       | 52.47%  |
| Unknown | 108       | 41.06%  |
| MBR     | 17        | 6.46%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 242       | 93.44%  |
| Yes       | 17        | 6.56%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 174       | 66.67%  |
| Yes       | 87        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 58        | 22.48%  |
| Samsung Electronics | 35        | 13.57%  |
| Hewlett-Packard     | 33        | 12.79%  |
| ASUSTek Computer    | 28        | 10.85%  |
| LG Electronics      | 22        | 8.53%   |
| Dell                | 16        | 6.2%    |
| MSI                 | 11        | 4.26%   |
| Apple               | 11        | 4.26%   |
| Valve               | 4         | 1.55%   |
| Notebook            | 4         | 1.55%   |
| HANSUNG COMPUTER    | 4         | 1.55%   |
| Acer                | 4         | 1.55%   |
| Toshiba             | 2         | 0.78%   |
| Razer               | 2         | 0.78%   |
| Google              | 2         | 0.78%   |
| Gigabyte Technology | 2         | 0.78%   |
| Unknown             | 2         | 0.78%   |
| Wolfnfox            | 1         | 0.39%   |
| WEIPAI              | 1         | 0.39%   |
| TG                  | 1         | 0.39%   |
| Teclast             | 1         | 0.39%   |
| Sony                | 1         | 0.39%   |
| SLIMBOOK            | 1         | 0.39%   |
| Pine Microsystems   | 1         | 0.39%   |
| MS                  | 1         | 0.39%   |
| MECHREVO            | 1         | 0.39%   |
| Jooyontech Computer | 1         | 0.39%   |
| Jooyon Tech         | 1         | 0.39%   |
| Intel               | 1         | 0.39%   |
| IMUZ                | 1         | 0.39%   |
| HUAWEI              | 1         | 0.39%   |
| Clevo               | 1         | 0.39%   |
| AVERATEC            | 1         | 0.39%   |
| AMI                 | 1         | 0.39%   |
| Alienware           | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung 950XCJ/951XCJ/950XCR         | 5         | 1.94%   |
| Valve Jupiter                        | 4         | 1.55%   |
| Samsung 950XED                       | 3         | 1.16%   |
| Samsung 760XDA                       | 3         | 1.16%   |
| Razer Blade 17 (2022) - RZ09-0423    | 2         | 0.78%   |
| Notebook N650DU                      | 2         | 0.78%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01S00 | 2         | 0.78%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 2         | 0.78%   |
| HP Stream Notebook PC 13             | 2         | 0.78%   |
| HP Pavilion dv6                      | 2         | 0.78%   |
| HP Laptop 15-db1xxx                  | 2         | 0.78%   |
| HP EliteBook 855 G7 Notebook PC      | 2         | 0.78%   |
| HANSUNG COMPUTER TFX5470H            | 2         | 0.78%   |
| Dell XPS 15 7590                     | 2         | 0.78%   |
| Dell Inspiron 15 5510                | 2         | 0.78%   |
| ASUS Zenbook UM3402YA_UM3402YA       | 2         | 0.78%   |
| ASUS X542UN                          | 2         | 0.78%   |
| Apple MacBookPro16,1                 | 2         | 0.78%   |
| Unknown                              | 2         | 0.78%   |
| Wolfnfox WF-TBAT                     | 1         | 0.39%   |
| WEIPAI S15                           | 1         | 0.39%   |
| Toshiba Satellite P50-B-103          | 1         | 0.39%   |
| Toshiba Satellite L655               | 1         | 0.39%   |
| TG NXI-A7000 Series                  | 1         | 0.39%   |
| Teclast tPAD                         | 1         | 0.39%   |
| Sony VPCEA36FK                       | 1         | 0.39%   |
| SLIMBOOK PROX15-AMD                  | 1         | 0.39%   |
| Samsung X120/X170/X171               | 1         | 0.39%   |
| Samsung SX11S                        | 1         | 0.39%   |
| Samsung RC420/RC520/RC720            | 1         | 0.39%   |
| Samsung R59P/R60P/R61P               | 1         | 0.39%   |
| Samsung R440/R480                    | 1         | 0.39%   |
| Samsung 950XDC/951XDC/950XDX         | 1         | 0.39%   |
| Samsung 950XDB/951XDB/950XDY         | 1         | 0.39%   |
| Samsung 940XFG                       | 1         | 0.39%   |
| Samsung 910S3L                       | 1         | 0.39%   |
| Samsung 905S3G/906S3G/915S3G         | 1         | 0.39%   |
| Samsung 900X5T                       | 1         | 0.39%   |
| Samsung 900X5N                       | 1         | 0.39%   |
| Samsung 800G5M/800G5W                | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 35        | 13.57%  |
| Lenovo IdeaPad            | 13        | 5.04%   |
| ASUS VivoBook             | 9         | 3.49%   |
| HP Pavilion               | 8         | 3.1%    |
| HP Laptop                 | 6         | 2.33%   |
| HP EliteBook              | 6         | 2.33%   |
| Samsung 950XCJ            | 5         | 1.94%   |
| Dell XPS                  | 5         | 1.94%   |
| Dell Inspiron             | 5         | 1.94%   |
| Valve Jupiter             | 4         | 1.55%   |
| ASUS ROG                  | 4         | 1.55%   |
| Samsung 950XED            | 3         | 1.16%   |
| Samsung 760XDA            | 3         | 1.16%   |
| Lenovo ThinkBook          | 3         | 1.16%   |
| HP Stream                 | 3         | 1.16%   |
| Dell Latitude             | 3         | 1.16%   |
| Toshiba Satellite         | 2         | 0.78%   |
| Razer Blade               | 2         | 0.78%   |
| Notebook N650DU           | 2         | 0.78%   |
| MSI Prestige              | 2         | 0.78%   |
| HP ProBook                | 2         | 0.78%   |
| HP OMEN                   | 2         | 0.78%   |
| HP ENVY                   | 2         | 0.78%   |
| HANSUNG COMPUTER TFX5470H | 2         | 0.78%   |
| ASUS Zenbook              | 2         | 0.78%   |
| ASUS X542UN               | 2         | 0.78%   |
| ASUS TUF                  | 2         | 0.78%   |
| Apple MacBookPro5         | 2         | 0.78%   |
| Apple MacBookPro16        | 2         | 0.78%   |
| Acer Swift                | 2         | 0.78%   |
| Unknown                   | 2         | 0.78%   |
| Wolfnfox WF-TBAT          | 1         | 0.39%   |
| WEIPAI S15                | 1         | 0.39%   |
| TG NXI-A7000              | 1         | 0.39%   |
| Teclast tPAD              | 1         | 0.39%   |
| Sony VPCEA36FK            | 1         | 0.39%   |
| SLIMBOOK PROX15-AMD       | 1         | 0.39%   |
| Samsung X120              | 1         | 0.39%   |
| Samsung SX11S             | 1         | 0.39%   |
| Samsung RC420             | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 46        | 17.83%  |
| 2021    | 35        | 13.57%  |
| 2019    | 26        | 10.08%  |
| 2022    | 22        | 8.53%   |
| 2018    | 21        | 8.14%   |
| 2014    | 16        | 6.2%    |
| 2013    | 16        | 6.2%    |
| 2017    | 11        | 4.26%   |
| 2011    | 11        | 4.26%   |
| 2012    | 10        | 3.88%   |
| 2016    | 8         | 3.1%    |
| 2010    | 8         | 3.1%    |
| 2008    | 8         | 3.1%    |
| 2023    | 5         | 1.94%   |
| 2015    | 5         | 1.94%   |
| 2009    | 4         | 1.55%   |
| 2007    | 3         | 1.16%   |
| 2006    | 2         | 0.78%   |
| Unknown | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 258       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 235       | 90.38%  |
| Enabled  | 25        | 9.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 256       | 99.22%  |
| Yes  | 2         | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Notebooks | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 68        | 26.05%  |
| 16.01-24.0      | 51        | 19.54%  |
| 8.01-16.0       | 49        | 18.77%  |
| 3.01-4.0        | 39        | 14.94%  |
| 32.01-64.0      | 26        | 9.96%   |
| 1.01-2.0        | 13        | 4.98%   |
| 64.01-256.0     | 9         | 3.45%   |
| 24.01-32.0      | 4         | 1.53%   |
| More than 256.0 | 1         | 0.38%   |
| 2.01-3.0        | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 79        | 28.32%  |
| 2.01-3.0   | 72        | 25.81%  |
| 4.01-8.0   | 50        | 17.92%  |
| 3.01-4.0   | 43        | 15.41%  |
| 0.51-1.0   | 17        | 6.09%   |
| 8.01-16.0  | 13        | 4.66%   |
| 16.01-24.0 | 3         | 1.08%   |
| 24.01-32.0 | 1         | 0.36%   |
| 0.01-0.5   | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 169       | 64.02%  |
| 2      | 80        | 30.3%   |
| 3      | 12        | 4.55%   |
| 4      | 2         | 0.76%   |
| 0      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 219       | 84.88%  |
| Yes       | 39        | 15.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 66.92%  |
| No        | 86        | 33.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 96.14%  |
| No        | 10        | 3.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 221       | 85%     |
| No        | 39        | 15%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| South Korea | 258       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Seoul         | 41        | 15.13%  |
| Suwon         | 15        | 5.54%   |
| Seocho-gu     | 13        | 4.8%    |
| Seongnam-si   | 9         | 3.32%   |
| Gwanak-gu     | 8         | 2.95%   |
| Uiwang        | 7         | 2.58%   |
| Jung-gu       | 6         | 2.21%   |
| Hwaseong-si   | 6         | 2.21%   |
| Anyang-si     | 6         | 2.21%   |
| Yongsan-gu    | 5         | 1.85%   |
| Yongin-si     | 5         | 1.85%   |
| Seongbuk-gu   | 5         | 1.85%   |
| Daegu         | 5         | 1.85%   |
| Busan         | 5         | 1.85%   |
| Bucheon-si    | 5         | 1.85%   |
| Mapo-gu       | 4         | 1.48%   |
| Jeonju        | 4         | 1.48%   |
| Incheon       | 4         | 1.48%   |
| Daejeon       | 4         | 1.48%   |
| Bupyeong-gu   | 4         | 1.48%   |
| Seo-gu        | 3         | 1.11%   |
| Pyeongtaek-si | 3         | 1.11%   |
| Nam-gu        | 3         | 1.11%   |
| Gwangju       | 3         | 1.11%   |
| Gimpo-si      | 3         | 1.11%   |
| Geumjeong-gu  | 3         | 1.11%   |
| Gangseo-gu    | 3         | 1.11%   |
| Gangnam-gu    | 3         | 1.11%   |
| Yuseong-gu    | 2         | 0.74%   |
| Yongsan-dong  | 2         | 0.74%   |
| Yeonsu-gu     | 2         | 0.74%   |
| Siheung-si    | 2         | 0.74%   |
| Seongdong-gu  | 2         | 0.74%   |
| Sejong        | 2         | 0.74%   |
| Paju          | 2         | 0.74%   |
| Namyangju     | 2         | 0.74%   |
| Namdong-gu    | 2         | 0.74%   |
| Jeju City     | 2         | 0.74%   |
| Gyeongsan-si  | 2         | 0.74%   |
| Gwacheon      | 2         | 0.74%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 87        | 110    | 25.44%  |
| WDC                            | 33        | 35     | 9.65%   |
| SanDisk                        | 25        | 25     | 7.31%   |
| SK hynix                       | 24        | 31     | 7.02%   |
| Unknown                        | 21        | 25     | 6.14%   |
| Seagate                        | 17        | 21     | 4.97%   |
| Toshiba                        | 14        | 16     | 4.09%   |
| Crucial                        | 13        | 14     | 3.8%    |
| Micron Technology              | 11        | 12     | 3.22%   |
| Intel                          | 10        | 15     | 2.92%   |
| Kingston                       | 8         | 10     | 2.34%   |
| Phison                         | 6         | 7      | 1.75%   |
| Apple                          | 6         | 7      | 1.75%   |
| Hitachi                        | 5         | 6      | 1.46%   |
| A-DATA Technology              | 5         | 5      | 1.46%   |
| Team                           | 3         | 3      | 0.88%   |
| TAMMUZ                         | 3         | 5      | 0.88%   |
| Silicon Motion                 | 3         | 4      | 0.88%   |
| KIOXIA                         | 3         | 3      | 0.88%   |
| JMicron Technology             | 3         | 3      | 0.88%   |
| HGST                           | 3         | 4      | 0.88%   |
| UMIS                           | 2         | 2      | 0.58%   |
| RevuAhn                        | 2         | 2      | 0.58%   |
| Phison Electronics             | 2         | 2      | 0.58%   |
| LITEONIT                       | 2         | 2      | 0.58%   |
| LITEON                         | 2         | 2      | 0.58%   |
| Imation                        | 2         | 2      | 0.58%   |
| Fujitsu                        | 2         | 2      | 0.58%   |
| China                          | 2         | 2      | 0.58%   |
| ZTC                            | 1         | 1      | 0.29%   |
| XPG                            | 1         | 2      | 0.29%   |
| VIVA300s                       | 1         | 1      | 0.29%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.29%   |
| TYPEC 1T                       | 1         | 1      | 0.29%   |
| Transcend                      | 1         | 2      | 0.29%   |
| T-FORCE                        | 1         | 1      | 0.29%   |
| Solid State Storage Technology | 1         | 1      | 0.29%   |
| Realtek                        | 1         | 1      | 0.29%   |
| Plextor                        | 1         | 1      | 0.29%   |
| O2 Micro                       | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB   | 5         | 1.38%   |
| SK hynix SHGP31-1000GM-2 1TB                          | 4         | 1.1%    |
| SanDisk NVMe SSD Drive 512GB                          | 4         | 1.1%    |
| Unknown MMC Card  256GB                               | 3         | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 3         | 0.83%   |
| Samsung SSD 980 PRO 2TB                               | 3         | 0.83%   |
| Samsung SSD 860 EVO 500GB                             | 3         | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 3         | 0.83%   |
| Samsung MZVLQ1T0HBLB-00B 1024GB                       | 3         | 0.83%   |
| Samsung MZVLB256HBHQ-000 256GB                        | 3         | 0.83%   |
| Samsung MZVL21T0HCLR-00B00 1TB                        | 3         | 0.83%   |
| Intel SSDPEKNU512GZ 512GB                             | 3         | 0.83%   |
| WDC WDS100T2B0C-00PXH0 1TB                            | 2         | 0.55%   |
| WDC WD50 00LPVX-22V0TT0 500GB                         | 2         | 0.55%   |
| Unknown SLD64G  64GB                                  | 2         | 0.55%   |
| Unknown SD/MMC/MS PRO 128GB                           | 2         | 0.55%   |
| Unknown MMC Card  512GB                               | 2         | 0.55%   |
| Unknown MMC Card  32GB                                | 2         | 0.55%   |
| Toshiba KBG30ZMV256G 256GB                            | 2         | 0.55%   |
| SK hynix SHGP31-1000GM 1TB                            | 2         | 0.55%   |
| SK hynix NVMe SSD Drive 256GB                         | 2         | 0.55%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                 | 2         | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 2         | 0.55%   |
| Seagate ST1000LM048-2E7172 1TB                        | 2         | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB                        | 2         | 0.55%   |
| Seagate Expansion 1TB                                 | 2         | 0.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 2         | 0.55%   |
| SanDisk SD8SBAT256G1122 256GB SSD                     | 2         | 0.55%   |
| SanDisk NVMe SSD Drive 256GB                          | 2         | 0.55%   |
| Samsung SSD 870 EVO 500GB                             | 2         | 0.55%   |
| Samsung SSD 860 EVO 1TB                               | 2         | 0.55%   |
| Samsung SSD 830 Series 256GB                          | 2         | 0.55%   |
| Samsung SSD 750 EVO 120GB                             | 2         | 0.55%   |
| Samsung PSSD T7 2TB                                   | 2         | 0.55%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 2         | 0.55%   |
| Samsung NVMe SSD Drive 2TB                            | 2         | 0.55%   |
| Samsung MZVLB512HAJQ-00000 512GB                      | 2         | 0.55%   |
| Samsung MZNLN256HAJQ-00000 256GB SSD                  | 2         | 0.55%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD                  | 2         | 0.55%   |
| Micron MTFDKCD256TFK 256GB                            | 2         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 20     | 30.77%  |
| WDC                 | 15        | 15     | 28.85%  |
| Toshiba             | 6         | 6      | 11.54%  |
| Hitachi             | 5         | 6      | 9.62%   |
| HGST                | 3         | 4      | 5.77%   |
| Unknown             | 2         | 2      | 3.85%   |
| Samsung Electronics | 2         | 2      | 3.85%   |
| Fujitsu             | 2         | 2      | 3.85%   |
| ipTIME              | 1         | 1      | 1.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 52     | 36.13%  |
| SanDisk             | 12        | 12     | 10.08%  |
| Crucial             | 11        | 12     | 9.24%   |
| WDC                 | 6         | 7      | 5.04%   |
| SK hynix            | 6         | 7      | 5.04%   |
| Intel               | 4         | 5      | 3.36%   |
| TAMMUZ              | 3         | 5      | 2.52%   |
| Micron Technology   | 3         | 4      | 2.52%   |
| Kingston            | 3         | 4      | 2.52%   |
| Team                | 2         | 2      | 1.68%   |
| LITEONIT            | 2         | 2      | 1.68%   |
| LITEON              | 2         | 2      | 1.68%   |
| China               | 2         | 2      | 1.68%   |
| Apple               | 2         | 2      | 1.68%   |
| A-DATA Technology   | 2         | 2      | 1.68%   |
| ZTC                 | 1         | 1      | 0.84%   |
| TYPEC 1T            | 1         | 1      | 0.84%   |
| Transcend           | 1         | 2      | 0.84%   |
| Toshiba             | 1         | 1      | 0.84%   |
| T-FORCE             | 1         | 1      | 0.84%   |
| RevuAhn             | 1         | 1      | 0.84%   |
| Plextor             | 1         | 1      | 0.84%   |
| NT-1TB              | 1         | 1      | 0.84%   |
| MG                  | 1         | 1      | 0.84%   |
| KingSpec            | 1         | 1      | 0.84%   |
| JMicron Technology  | 1         | 1      | 0.84%   |
| IPLEX               | 1         | 1      | 0.84%   |
| Imation             | 1         | 1      | 0.84%   |
| Biostar             | 1         | 1      | 0.84%   |
| ASMT                | 1         | 1      | 0.84%   |
| Apacer              | 1         | 1      | 0.84%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 137       | 177    | 42.41%  |
| SSD     | 109       | 137    | 33.75%  |
| HDD     | 52        | 58     | 16.1%   |
| MMC     | 19        | 23     | 5.88%   |
| Unknown | 6         | 7      | 1.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 137       | 176    | 44.77%  |
| SATA | 129       | 178    | 42.16%  |
| SAS  | 21        | 25     | 6.86%   |
| MMC  | 19        | 23     | 6.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 109       | 136    | 68.99%  |
| 0.51-1.0   | 42        | 50     | 26.58%  |
| 1.01-2.0   | 5         | 7      | 3.16%   |
| 3.01-4.0   | 2         | 2      | 1.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 95        | 35.32%  |
| 251-500        | 55        | 20.45%  |
| 501-1000       | 33        | 12.27%  |
| 1001-2000      | 25        | 9.29%   |
| 51-100         | 24        | 8.92%   |
| 21-50          | 11        | 4.09%   |
| 1-20           | 11        | 4.09%   |
| More than 3000 | 8         | 2.97%   |
| 2001-3000      | 5         | 1.86%   |
| Unknown        | 2         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 111       | 40.22%  |
| 21-50          | 58        | 21.01%  |
| 101-250        | 35        | 12.68%  |
| 51-100         | 25        | 9.06%   |
| 251-500        | 20        | 7.25%   |
| 501-1000       | 14        | 5.07%   |
| 1001-2000      | 6         | 2.17%   |
| 2001-3000      | 4         | 1.45%   |
| Unknown        | 2         | 0.72%   |
| More than 3000 | 1         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB             | 1         | 1      | 7.14%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 7.14%   |
| Toshiba MK5061GSYN 500GB                 | 1         | 1      | 7.14%   |
| Toshiba MK2565GSX 250GB                  | 1         | 1      | 7.14%   |
| SK hynix HFS512G39TND-N210A 512GB SSD    | 1         | 1      | 7.14%   |
| SK hynix HFS128G3AMNM-1010A 128GB SSD    | 1         | 1      | 7.14%   |
| SanDisk SD9SN8W256G1009 256GB SSD        | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 830 Series 512GB | 1         | 1      | 7.14%   |
| Samsung Electronics SM961 NVMe 1024GB    | 1         | 1      | 7.14%   |
| Phison ES 512GB                          | 1         | 1      | 7.14%   |
| LITEONIT LMT-256M3M 256GB SSD            | 1         | 1      | 7.14%   |
| Kingston SHFS37A120G 120GB SSD           | 1         | 1      | 7.14%   |
| Hitachi HTS541616J9SA00 160GB            | 1         | 1      | 7.14%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 14.29%  |
| Toshiba             | 2         | 2      | 14.29%  |
| SK hynix            | 2         | 2      | 14.29%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| SanDisk             | 1         | 1      | 7.14%   |
| Phison              | 1         | 1      | 7.14%   |
| LITEONIT            | 1         | 1      | 7.14%   |
| Kingston            | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 33.33%  |
| Toshiba | 2         | 2      | 33.33%  |
| Hitachi | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 6         | 6      | 42.86%  |
| HDD  | 6         | 6      | 42.86%  |
| NVMe | 2         | 2      | 14.29%  |

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
| Detected | 143       | 215    | 50.89%  |
| Works    | 124       | 173    | 44.13%  |
| Malfunc  | 14        | 14     | 4.98%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 139       | 44.41%  |
| Samsung Electronics              | 46        | 14.7%   |
| AMD                              | 28        | 8.95%   |
| SanDisk                          | 25        | 7.99%   |
| SK hynix                         | 17        | 5.43%   |
| Phison Electronics               | 10        | 3.19%   |
| Micron Technology                | 8         | 2.56%   |
| Toshiba America Info Systems     | 7         | 2.24%   |
| Silicon Motion                   | 5         | 1.6%    |
| Kingston Technology Company      | 5         | 1.6%    |
| Apple                            | 4         | 1.28%   |
| Union Memory (Shenzhen)          | 3         | 0.96%   |
| Micron/Crucial Technology        | 3         | 0.96%   |
| KIOXIA                           | 3         | 0.96%   |
| ADATA Technology                 | 3         | 0.96%   |
| Nvidia                           | 2         | 0.64%   |
| Solid State Storage Technology   | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| O2 Micro                         | 1         | 0.32%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.32%   |
| Broadcom / LSI                   | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 26        | 7.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 20        | 6.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 5.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 3.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 3.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 3.07%   |
| Samsung NVMe SSD Controller 980                                                | 9         | 2.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 2.45%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 2.15%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 2.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 2.15%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 7         | 2.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 1.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.53%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.23%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.23%   |
| Phison PS5013 E13 NVMe Controller                                              | 4         | 1.23%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 4         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.23%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 0.92%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 3         | 0.92%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.92%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.92%   |
| SanDisk PC SN520 NVMe SSD                                                      | 3         | 0.92%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.92%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 3         | 0.92%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 0.92%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 3         | 0.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 0.92%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.92%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 0.92%   |
| Intel SSD 660P Series                                                          | 3         | 0.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.92%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 151       | 48.55%  |
| NVMe | 137       | 44.05%  |
| RAID | 14        | 4.5%    |
| IDE  | 9         | 2.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 201       | 77.91%  |
| AMD    | 56        | 21.71%  |
| ARM    | 1         | 0.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 3.1%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 2.71%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 2.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.94%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.94%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 5         | 1.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.55%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 1.55%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.55%   |
| Intel 12th Gen Core i5-1240P                  | 4         | 1.55%   |
| AMD Custom APU 0405                           | 4         | 1.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.16%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 1.16%   |
| Intel 11th Gen Core i7-11600H @ 2.90GHz       | 3         | 1.16%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.16%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.16%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 0.78%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 2         | 0.78%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.78%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 0.78%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.78%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.78%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.78%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 2         | 0.78%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.78%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.78%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 0.78%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.78%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.78%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.78%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 55        | 21.32%  |
| Intel Core i7        | 54        | 20.93%  |
| Other                | 42        | 16.28%  |
| AMD Ryzen 5          | 18        | 6.98%   |
| Intel Core i3        | 14        | 5.43%   |
| AMD Ryzen 7          | 14        | 5.43%   |
| Intel Core 2 Duo     | 8         | 3.1%    |
| Intel Celeron        | 8         | 3.1%    |
| Intel Pentium        | 7         | 2.71%   |
| Intel Core i9        | 4         | 1.55%   |
| Intel Atom           | 4         | 1.55%   |
| AMD Ryzen 7 PRO      | 4         | 1.55%   |
| AMD Ryzen 5 PRO      | 3         | 1.16%   |
| AMD Ryzen 3          | 3         | 1.16%   |
| Intel Pentium Silver | 2         | 0.78%   |
| Intel Genuine        | 2         | 0.78%   |
| Intel Core 2         | 2         | 0.78%   |
| AMD Ryzen 9          | 2         | 0.78%   |
| AMD A6               | 2         | 0.78%   |
| AMD A4               | 2         | 0.78%   |
| AMD A10              | 2         | 0.78%   |
| Intel Xeon Gold      | 1         | 0.39%   |
| Intel Xeon           | 1         | 0.39%   |
| Intel Pentium Dual   | 1         | 0.39%   |
| Intel Core m3        | 1         | 0.39%   |
| AMD Quad-Core        | 1         | 0.39%   |
| AMD Athlon II        | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 92        | 35.66%  |
| 4       | 91        | 35.27%  |
| 6       | 31        | 12.02%  |
| 8       | 25        | 9.69%   |
| 12      | 8         | 3.1%    |
| 14      | 5         | 1.94%   |
| 16      | 2         | 0.78%   |
| 32      | 1         | 0.39%   |
| 10      | 1         | 0.39%   |
| 1       | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 256       | 99.22%  |
| 2      | 2         | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 214       | 82.95%  |
| 1       | 43        | 16.67%  |
| Unknown | 1         | 0.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 253       | 98.06%  |
| Unknown        | 3         | 1.16%   |
| 64-bit         | 1         | 0.39%   |
| 32-bit         | 1         | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 18.42%  |
| 0x806ec    | 15        | 5.64%   |
| 0x806c1    | 15        | 5.64%   |
| 0x306a9    | 12        | 4.51%   |
| 0x806ea    | 10        | 3.76%   |
| 0x0a50000c | 10        | 3.76%   |
| 0x906a3    | 9         | 3.38%   |
| 0x206a7    | 9         | 3.38%   |
| 0x20655    | 8         | 3.01%   |
| 0x906e9    | 7         | 2.63%   |
| 0x806eb    | 7         | 2.63%   |
| 0x08600106 | 7         | 2.63%   |
| 0x40651    | 6         | 2.26%   |
| 0x906ea    | 5         | 1.88%   |
| 0x706e5    | 5         | 1.88%   |
| 0x08108102 | 5         | 1.88%   |
| 0xa0652    | 4         | 1.5%    |
| 0x806e9    | 4         | 1.5%    |
| 0x806d1    | 4         | 1.5%    |
| 0x706a1    | 4         | 1.5%    |
| 0x406e3    | 4         | 1.5%    |
| 0x306d4    | 4         | 1.5%    |
| 0x306c3    | 4         | 1.5%    |
| 0x30678    | 4         | 1.5%    |
| 0x0a50000d | 4         | 1.5%    |
| 0x906ed    | 3         | 1.13%   |
| 0x6fd      | 3         | 1.13%   |
| 0x1067a    | 3         | 1.13%   |
| 0x0a404102 | 3         | 1.13%   |
| 0xb06f2    | 2         | 0.75%   |
| 0xa0660    | 2         | 0.75%   |
| 0x6f6      | 2         | 0.75%   |
| 0x406c3    | 2         | 0.75%   |
| 0x20652    | 2         | 0.75%   |
| 0x10676    | 2         | 0.75%   |
| 0x08608103 | 2         | 0.75%   |
| 0x08600103 | 2         | 0.75%   |
| 0x0700010f | 2         | 0.75%   |
| 0x06001119 | 2         | 0.75%   |
| 0xb06a2    | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 60        | 23.26%  |
| Unknown          | 18        | 6.98%   |
| TigerLake        | 17        | 6.59%   |
| Zen 3            | 16        | 6.2%    |
| Haswell          | 15        | 5.81%   |
| Zen 2            | 14        | 5.43%   |
| IvyBridge        | 14        | 5.43%   |
| Westmere         | 11        | 4.26%   |
| SandyBridge      | 10        | 3.88%   |
| IceLake          | 10        | 3.88%   |
| Skylake          | 9         | 3.49%   |
| Alderlake Hybrid | 8         | 3.1%    |
| Zen+             | 7         | 2.71%   |
| Silvermont       | 7         | 2.71%   |
| CometLake        | 7         | 2.71%   |
| Penryn           | 6         | 2.33%   |
| Core             | 6         | 2.33%   |
| Goldmont plus    | 5         | 1.94%   |
| Broadwell        | 4         | 1.55%   |
| Jaguar           | 3         | 1.16%   |
| Zen              | 2         | 0.78%   |
| Piledriver       | 2         | 0.78%   |
| Nehalem          | 2         | 0.78%   |
| Excavator        | 2         | 0.78%   |
| P6               | 1         | 0.39%   |
| K10              | 1         | 0.39%   |
| Bonnell          | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 181       | 55.69%  |
| Nvidia                           | 76        | 23.38%  |
| AMD                              | 66        | 20.31%  |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Matrox Electronics Systems       | 1         | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 4.2%    |
| AMD Renoir                                                                               | 14        | 4.2%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 3.9%    |
| Intel UHD Graphics 620                                                                   | 12        | 3.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 3.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 3.3%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 11        | 3.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 2.4%    |
| AMD Barcelo                                                                              | 8         | 2.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 2.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 1.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.8%    |
| Nvidia TU117M [GeForce MX450]                                                            | 5         | 1.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.5%    |
| Intel HD Graphics 630                                                                    | 5         | 1.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.5%    |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.2%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.2%    |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.2%    |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 4         | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.9%    |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 0.9%    |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 3         | 0.9%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.9%    |
| Intel HD Graphics 620                                                                    | 3         | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.9%    |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 0.9%    |
| Nvidia TU117M                                                                            | 2         | 0.6%    |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.6%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.6%    |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.6%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 119       | 46.12%  |
| Intel + Nvidia  | 55        | 21.32%  |
| 1 x AMD         | 52        | 20.16%  |
| 1 x Nvidia      | 14        | 5.43%   |
| Intel + AMD     | 6         | 2.33%   |
| AMD + Nvidia    | 5         | 1.94%   |
| 2 x AMD         | 3         | 1.16%   |
| Other           | 1         | 0.39%   |
| 2 x Nvidia      | 1         | 0.39%   |
| 1 x SiS         | 1         | 0.39%   |
| Nvidia + Matrox | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 208       | 80%     |
| Proprietary | 40        | 15.38%  |
| Unknown     | 12        | 4.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 162       | 61.83%  |
| 0.01-0.5   | 31        | 11.83%  |
| 3.01-4.0   | 23        | 8.78%   |
| 1.01-2.0   | 22        | 8.4%    |
| 0.51-1.0   | 14        | 5.34%   |
| 5.01-6.0   | 4         | 1.53%   |
| 7.01-8.0   | 3         | 1.15%   |
| 8.01-16.0  | 2         | 0.76%   |
| 2.01-3.0   | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 47        | 16.04%  |
| AU Optronics            | 46        | 15.7%   |
| BOE                     | 41        | 13.99%  |
| Samsung Electronics     | 34        | 11.6%   |
| Chimei Innolux          | 31        | 10.58%  |
| Goldstar                | 12        | 4.1%    |
| Apple                   | 10        | 3.41%   |
| Sharp                   | 9         | 3.07%   |
| Dell                    | 8         | 2.73%   |
| PANDA                   | 6         | 2.05%   |
| Lenovo                  | 5         | 1.71%   |
| Valve                   | 4         | 1.37%   |
| Philips                 | 3         | 1.02%   |
| JCH                     | 3         | 1.02%   |
| CSO                     | 3         | 1.02%   |
| CPT                     | 3         | 1.02%   |
| BenQ                    | 3         | 1.02%   |
| ALP                     | 3         | 1.02%   |
| Sony                    | 2         | 0.68%   |
| InfoVision              | 2         | 0.68%   |
| Chi Mei Optoelectronics | 2         | 0.68%   |
| AOC                     | 2         | 0.68%   |
| WIT                     | 1         | 0.34%   |
| VMO                     | 1         | 0.34%   |
| TMX                     | 1         | 0.34%   |
| STD                     | 1         | 0.34%   |
| PRISM+                  | 1         | 0.34%   |
| MSI                     | 1         | 0.34%   |
| LGD                     | 1         | 0.34%   |
| KVM                     | 1         | 0.34%   |
| HKC                     | 1         | 0.34%   |
| Hewlett-Packard         | 1         | 0.34%   |
| HannStar                | 1         | 0.34%   |
| Denver                  | 1         | 0.34%   |
| CM_                     | 1         | 0.34%   |
| Ancor Communications    | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 6         | 2.01%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 4         | 1.34%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 1.34%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.34%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 3         | 1%      |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 1%      |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 1%      |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 3         | 1%      |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                 | 3         | 1%      |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 1%      |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 2         | 0.67%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch               | 2         | 0.67%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 2         | 0.67%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 2         | 0.67%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch          | 2         | 0.67%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch          | 2         | 0.67%   |
| LG Display LCD Monitor LGD03B5 1920x1080 294x165mm 13.3-inch          | 2         | 0.67%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.67%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 0.67%   |
| BOE LCD Monitor BOE06E8 1920x1080 332x186mm 15.0-inch                 | 2         | 0.67%   |
| BOE LCD Monitor BOE06D7 3840x2160 345x194mm 15.6-inch                 | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO749D 3840x2160 381x214mm 17.2-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO6A92 1920x1080 344x194mm 15.5-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor 1920x1080                                    | 2         | 0.67%   |
| Apple Color LCD APPA044 3072x1920 345x215mm 16.0-inch                 | 2         | 0.67%   |
| AOC 28E850 AOC0CCD 2560x1440 480x270mm 21.7-inch                      | 2         | 0.67%   |
| WIT HDMI WIT5082 2560x1440 596x335mm 26.9-inch                        | 1         | 0.33%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch             | 1         | 0.33%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.33%   |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.33%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.33%   |
| Sony BW8 MS_9001 2560x1600                                            | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 145       | 51.42%  |
| 1366x768 (WXGA)    | 40        | 14.18%  |
| 3840x2160 (4K)     | 17        | 6.03%   |
| 2560x1600          | 13        | 4.61%   |
| 2560x1440 (QHD)    | 11        | 3.9%    |
| 1920x1200 (WUXGA)  | 9         | 3.19%   |
| 1280x800 (WXGA)    | 8         | 2.84%   |
| 1600x900 (HD+)     | 7         | 2.48%   |
| 2880x1800          | 6         | 2.13%   |
| 800x1280           | 4         | 1.42%   |
| 3440x1440          | 4         | 1.42%   |
| 1440x900 (WXGA+)   | 3         | 1.06%   |
| 1280x1024 (SXGA)   | 3         | 1.06%   |
| 3840x2400          | 2         | 0.71%   |
| 3072x1920          | 2         | 0.71%   |
| 1680x1050 (WSXGA+) | 2         | 0.71%   |
| 2560x1080          | 1         | 0.35%   |
| 2160x1350          | 1         | 0.35%   |
| 1920x1280          | 1         | 0.35%   |
| 1680x945           | 1         | 0.35%   |
| 1400x1050          | 1         | 0.35%   |
| 1024x768 (XGA)     | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 120       | 40.54%  |
| 13      | 43        | 14.53%  |
| 14      | 33        | 11.15%  |
| 17      | 13        | 4.39%   |
| 27      | 12        | 4.05%   |
| 24      | 11        | 3.72%   |
| 23      | 10        | 3.38%   |
| 16      | 10        | 3.38%   |
| 21      | 5         | 1.69%   |
| 12      | 5         | 1.69%   |
| 34      | 4         | 1.35%   |
| 31      | 4         | 1.35%   |
| 11      | 4         | 1.35%   |
| 7       | 4         | 1.35%   |
| 20      | 3         | 1.01%   |
| Unknown | 3         | 1.01%   |
| 19      | 2         | 0.68%   |
| 18      | 2         | 0.68%   |
| 74      | 1         | 0.34%   |
| 54      | 1         | 0.34%   |
| 42      | 1         | 0.34%   |
| 40      | 1         | 0.34%   |
| 26      | 1         | 0.34%   |
| 25      | 1         | 0.34%   |
| 10      | 1         | 0.34%   |
| 8       | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 174       | 59.18%  |
| 201-300     | 39        | 13.27%  |
| 501-600     | 32        | 10.88%  |
| 351-400     | 18        | 6.12%   |
| 401-500     | 10        | 3.4%    |
| 601-700     | 5         | 1.7%    |
| 701-800     | 4         | 1.36%   |
| 1-100       | 4         | 1.36%   |
| Unknown     | 3         | 1.02%   |
| 801-900     | 1         | 0.34%   |
| 1501-2000   | 1         | 0.34%   |
| 101-200     | 1         | 0.34%   |
| 1001-1500   | 1         | 0.34%   |
| 901-1000    | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 198       | 75.86%  |
| 16/10   | 43        | 16.48%  |
| 21/9    | 4         | 1.53%   |
| 0.67    | 4         | 1.53%   |
| 5/4     | 3         | 1.15%   |
| 3/2     | 3         | 1.15%   |
| Unknown | 3         | 1.15%   |
| 4/3     | 2         | 0.77%   |
| 0.62    | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 118       | 39.86%  |
| 81-90          | 52        | 17.57%  |
| 71-80          | 22        | 7.43%   |
| 201-250        | 22        | 7.43%   |
| 301-350        | 13        | 4.39%   |
| 121-130        | 12        | 4.05%   |
| 111-120        | 9         | 3.04%   |
| 351-500        | 8         | 2.7%    |
| 61-70          | 5         | 1.69%   |
| 1-40           | 5         | 1.69%   |
| 251-300        | 5         | 1.69%   |
| 151-200        | 5         | 1.69%   |
| 91-100         | 5         | 1.69%   |
| 51-60          | 4         | 1.35%   |
| 141-150        | 3         | 1.01%   |
| Unknown        | 3         | 1.01%   |
| More than 1000 | 2         | 0.68%   |
| 501-1000       | 2         | 0.68%   |
| 41-50          | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 126       | 43.3%   |
| 101-120       | 52        | 17.87%  |
| 161-240       | 49        | 16.84%  |
| 51-100        | 41        | 14.09%  |
| More than 240 | 18        | 6.19%   |
| Unknown       | 3         | 1.03%   |
| 1-50          | 2         | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 201       | 75%     |
| 2     | 48        | 17.91%  |
| 0     | 13        | 4.85%   |
| 3     | 6         | 2.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 164       | 41.52%  |
| Realtek Semiconductor            | 134       | 33.92%  |
| Qualcomm Atheros                 | 32        | 8.1%    |
| Broadcom                         | 24        | 6.08%   |
| ASIX Electronics                 | 8         | 2.03%   |
| MediaTek                         | 6         | 1.52%   |
| Ralink Technology                | 3         | 0.76%   |
| Marvell Technology Group         | 3         | 0.76%   |
| Apple                            | 3         | 0.76%   |
| TP-Link                          | 2         | 0.51%   |
| Samsung Electronics              | 2         | 0.51%   |
| Nvidia                           | 2         | 0.51%   |
| Lenovo                           | 2         | 0.51%   |
| Broadcom Limited                 | 2         | 0.51%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| Ralink                           | 1         | 0.25%   |
| Quectel Wireless Solutions       | 1         | 0.25%   |
| Qualcomm                         | 1         | 0.25%   |
| Microsoft                        | 1         | 0.25%   |
| D-Link                           | 1         | 0.25%   |
| Comneon                          | 1         | 0.25%   |
| Arduino SA                       | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 87        | 19.25%  |
| Intel Wi-Fi 6 AX200                                               | 26        | 5.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 4.2%    |
| Intel Wi-Fi 6 AX201                                               | 14        | 3.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 2.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 2.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 12        | 2.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 2.21%   |
| Intel Wireless 7260                                               | 8         | 1.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 1.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.55%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.33%   |
| Intel Wireless 3165                                               | 6         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 5         | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.88%   |
| Intel Wireless 7265                                               | 4         | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.88%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 4         | 0.88%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.66%   |
| Intel Wireless 8260                                               | 3         | 0.66%   |
| Intel Wireless 3160                                               | 3         | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.66%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.66%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 160       | 61.54%  |
| Realtek Semiconductor      | 37        | 14.23%  |
| Qualcomm Atheros           | 26        | 10%     |
| Broadcom                   | 20        | 7.69%   |
| MediaTek                   | 6         | 2.31%   |
| Ralink Technology          | 3         | 1.15%   |
| TP-Link                    | 2         | 0.77%   |
| Broadcom Limited           | 2         | 0.77%   |
| Ralink                     | 1         | 0.38%   |
| Quectel Wireless Solutions | 1         | 0.38%   |
| Qualcomm                   | 1         | 0.38%   |
| D-Link                     | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 26        | 9.92%   |
| Intel Wi-Fi 6 AX201                                           | 14        | 5.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 13        | 4.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 12        | 4.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 10        | 3.82%   |
| Intel Wireless 7260                                           | 8         | 3.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 8         | 3.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 7         | 2.67%   |
| Intel Wireless 8265 / 8275                                    | 7         | 2.67%   |
| Intel Wireless 3165                                           | 6         | 2.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 6         | 2.29%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 5         | 1.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5         | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 5         | 1.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 5         | 1.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 5         | 1.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 4         | 1.53%   |
| Intel Wireless 7265                                           | 4         | 1.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 4         | 1.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 4         | 1.53%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 4         | 1.53%   |
| Intel Centrino Advanced-N 6235                                | 4         | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 4         | 1.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 3         | 1.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 3         | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 1.15%   |
| Intel Wireless 8260                                           | 3         | 1.15%   |
| Intel Wireless 3160                                           | 3         | 1.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 1.15%   |
| Intel Centrino Wireless-N 2230                                | 3         | 1.15%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 3         | 1.15%   |
| Intel 700 Series Chipset Family Wi-Fi                         | 3         | 1.15%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 3         | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                 | 3         | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2         | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 119       | 66.48%  |
| Intel                            | 24        | 13.41%  |
| Qualcomm Atheros                 | 8         | 4.47%   |
| ASIX Electronics                 | 8         | 4.47%   |
| Broadcom                         | 6         | 3.35%   |
| Marvell Technology Group         | 3         | 1.68%   |
| Apple                            | 3         | 1.68%   |
| Samsung Electronics              | 2         | 1.12%   |
| Nvidia                           | 2         | 1.12%   |
| Lenovo                           | 2         | 1.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Microsoft                        | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 87        | 46.28%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 19        | 10.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 6.38%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 8         | 4.26%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 3.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 2.66%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.6%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.06%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.06%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.06%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.06%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.06%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.06%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.06%   |
| Apple iBridge                                                                  | 2         | 1.06%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.53%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 0.53%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.53%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.53%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.53%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.53%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.53%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                            | 1         | 0.53%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.53%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.53%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.53%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.53%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.53%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.53%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.53%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 249       | 58.73%  |
| Ethernet | 173       | 40.8%   |
| Modem    | 2         | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 202       | 72.14%  |
| Ethernet | 78        | 27.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 143       | 55.21%  |
| 1     | 110       | 42.47%  |
| 0     | 4         | 1.54%   |
| 3     | 2         | 0.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 256       | 99.22%  |
| Yes  | 2         | 0.78%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 137       | 61.71%  |
| Realtek Semiconductor           | 22        | 9.91%   |
| IMC Networks                    | 17        | 7.66%   |
| Broadcom                        | 15        | 6.76%   |
| Qualcomm Atheros Communications | 11        | 4.95%   |
| Foxconn / Hon Hai               | 6         | 2.7%    |
| Apple                           | 6         | 2.7%    |
| Lite-On Technology              | 4         | 1.8%    |
| Realtek                         | 1         | 0.45%   |
| Qcom                            | 1         | 0.45%   |
| Micro Star International        | 1         | 0.45%   |
| Hewlett-Packard                 | 1         | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 33        | 14.86%  |
| Intel AX201 Bluetooth                                                               | 32        | 14.41%  |
| Intel AX200 Bluetooth                                                               | 26        | 11.71%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 9.46%   |
| Realtek Bluetooth Radio                                                             | 16        | 7.21%   |
| Intel Bluetooth Device                                                              | 14        | 6.31%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 2.7%    |
| IMC Networks Bluetooth Radio                                                        | 6         | 2.7%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 2.25%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.25%   |
| IMC Networks Wireless_Device                                                        | 4         | 1.8%    |
| IMC Networks Bluetooth Device                                                       | 4         | 1.8%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.8%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 1.35%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.35%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.35%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.9%    |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 0.9%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.9%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.9%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.9%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.9%    |
| Realtek CSR BS8510                                                                  | 1         | 0.45%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.45%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.45%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.45%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.45%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.45%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.45%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.45%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.45%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 192       | 62.14%  |
| AMD                              | 63        | 20.39%  |
| Nvidia                           | 36        | 11.65%  |
| JMTek                            | 3         | 0.97%   |
| Apple                            | 3         | 0.97%   |
| Lenovo                           | 2         | 0.65%   |
| Texas Instruments                | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| Realtek Semiconductor            | 1         | 0.32%   |
| Razer USA                        | 1         | 0.32%   |
| No brand                         | 1         | 0.32%   |
| Native Instruments               | 1         | 0.32%   |
| Generalplus Technology           | 1         | 0.32%   |
| Dell                             | 1         | 0.32%   |
| DCMT Technology                  | 1         | 0.32%   |
| Unknown                          | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 44        | 11.61%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 31        | 8.18%   |
| Intel Sunrise Point-LP HD Audio                                            | 23        | 6.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 17        | 4.49%   |
| Intel Comet Lake PCH-LP cAVS                                               | 14        | 3.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14        | 3.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 13        | 3.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 3.43%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 12        | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 2.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 2.37%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 2.11%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 1.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 1.85%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7         | 1.85%   |
| Nvidia Audio device                                                        | 6         | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.58%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.58%   |
| Intel CM238 HD Audio Controller                                            | 6         | 1.58%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.32%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.32%   |
| Nvidia High Definition Audio Controller                                    | 4         | 1.06%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.06%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.06%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.06%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.79%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 3         | 0.79%   |
| Apple Audio Device                                                         | 3         | 0.79%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 0.79%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 94        | 51.09%  |
| SK hynix            | 37        | 20.11%  |
| Micron Technology   | 21        | 11.41%  |
| Unknown             | 8         | 4.35%   |
| Unknown             | 4         | 2.17%   |
| Kingston            | 3         | 1.63%   |
| A-DATA Technology   | 3         | 1.63%   |
| Unknown (ABCD)      | 2         | 1.09%   |
| Ramaxel Technology  | 2         | 1.09%   |
| Elpida              | 2         | 1.09%   |
| Unknown (899D)      | 1         | 0.54%   |
| Unknown (09D5)      | 1         | 0.54%   |
| Team                | 1         | 0.54%   |
| Silicon Power       | 1         | 0.54%   |
| PUSKILL             | 1         | 0.54%   |
| KLEVV               | 1         | 0.54%   |
| Imation             | 1         | 0.54%   |
| Essencore           | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 4%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 3.5%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 2%      |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 2%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 2%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 2%      |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2%      |
| Samsung RAM M471A1G44AB0-CTD 8GB DDR4 2667MT/s                   | 4         | 2%      |
| Unknown                                                          | 4         | 2%      |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 3         | 1.5%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.5%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.5%    |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 3         | 1.5%    |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 3         | 1.5%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.5%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 1.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 1.5%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 1%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1%      |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1%      |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 1%      |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1%      |
| Samsung RAM M471A1K43CB1-CTD 8GB DDR4 2667MT/s                   | 2         | 1%      |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1%      |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 2         | 1%      |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 1%      |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1%      |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1%      |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.5%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 92        | 58.23%  |
| DDR3    | 27        | 17.09%  |
| LPDDR4  | 14        | 8.86%   |
| LPDDR3  | 7         | 4.43%   |
| DDR5    | 7         | 4.43%   |
| LPDDR5  | 4         | 2.53%   |
| DDR2    | 3         | 1.9%    |
| SDRAM   | 2         | 1.27%   |
| Unknown | 2         | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 121       | 74.69%  |
| Row Of Chips | 31        | 19.14%  |
| Unknown      | 7         | 4.32%   |
| DIMM         | 3         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 79        | 46.2%   |
| 4096  | 35        | 20.47%  |
| 16384 | 29        | 16.96%  |
| 2048  | 16        | 9.36%   |
| 32768 | 10        | 5.85%   |
| 1024  | 2         | 1.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 44        | 25.73%  |
| 2667    | 40        | 23.39%  |
| 1600    | 18        | 10.53%  |
| 2400    | 13        | 7.6%    |
| 2133    | 9         | 5.26%   |
| 4800    | 8         | 4.68%   |
| 4267    | 8         | 4.68%   |
| 3266    | 7         | 4.09%   |
| 6400    | 5         | 2.92%   |
| 1334    | 5         | 2.92%   |
| 8400    | 2         | 1.17%   |
| 4266    | 2         | 1.17%   |
| 1333    | 2         | 1.17%   |
| 1067    | 2         | 1.17%   |
| 4199    | 1         | 0.58%   |
| 2048    | 1         | 0.58%   |
| 1867    | 1         | 0.58%   |
| 800     | 1         | 0.58%   |
| 667     | 1         | 0.58%   |
| Unknown | 1         | 0.58%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP OfficeJet 4650 series | 1         | 100%    |

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
| Chicony Electronics                    | 40        | 18.52%  |
| IMC Networks                           | 34        | 15.74%  |
| Bison Electronics                      | 16        | 7.41%   |
| Silicon Motion                         | 14        | 6.48%   |
| Realtek Semiconductor                  | 14        | 6.48%   |
| Microdia                               | 13        | 6.02%   |
| Quanta                                 | 10        | 4.63%   |
| Shenzhen Kingcome Optoelectronic       | 9         | 4.17%   |
| SunplusIT                              | 8         | 3.7%    |
| Apple                                  | 8         | 3.7%    |
| Acer                                   | 8         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.24%   |
| Syntek                                 | 6         | 2.78%   |
| Suyin                                  | 5         | 2.31%   |
| Luxvisions Innotech Limited            | 5         | 2.31%   |
| Sunplus Innovation Technology          | 3         | 1.39%   |
| Z-Star Microelectronics                | 2         | 0.93%   |
| Sonix Technology                       | 2         | 0.93%   |
| Logitech                               | 2         | 0.93%   |
| Lenovo                                 | 2         | 0.93%   |
| Samsung Electronics                    | 1         | 0.46%   |
| Microsoft                              | 1         | 0.46%   |
| LG Electronics                         | 1         | 0.46%   |
| Goodong Industry                       | 1         | 0.46%   |
| DRFCB0ABIHW8TC                         | 1         | 0.46%   |
| DigiTech                               | 1         | 0.46%   |
| Cubeternet                             | 1         | 0.46%   |
| Alcor Micro                            | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 10        | 4.55%   |
| IMC Networks Integrated Camera                          | 10        | 4.55%   |
| Chicony Integrated Camera                               | 10        | 4.55%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera         | 9         | 4.09%   |
| Microdia Integrated_Webcam_HD                           | 8         | 3.64%   |
| Realtek LG Camera                                       | 6         | 2.73%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 6         | 2.73%   |
| Bison Integrated Camera                                 | 6         | 2.73%   |
| Chicony HD WebCam                                       | 5         | 2.27%   |
| Bison HD Webcam                                         | 5         | 2.27%   |
| Syntek Integrated Camera                                | 4         | 1.82%   |
| Suyin HP Truevision HD                                  | 3         | 1.36%   |
| SunplusIT 720p HD Camera                                | 3         | 1.36%   |
| SunplusIT 1080p FHD Camera                              | 3         | 1.36%   |
| Silicon Motion LG HD WebCam                             | 3         | 1.36%   |
| Quanta HP TrueVision HD Camera                          | 3         | 1.36%   |
| Chicony USB 2.0 Camera                                  | 3         | 1.36%   |
| Chicony LG Camera                                       | 3         | 1.36%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 3         | 1.36%   |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 1.36%   |
| Z-Star Webcam                                           | 2         | 0.91%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 2         | 0.91%   |
| Silicon Motion 720p HD Camera                           | 2         | 0.91%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.91%   |
| Realtek Integrated_Webcam_HD                            | 2         | 0.91%   |
| Quanta LG Webcam                                        | 2         | 0.91%   |
| Microdia USB 2.0 Camera                                 | 2         | 0.91%   |
| Luxvisions Innotech Limited Integrated Camera           | 2         | 0.91%   |
| Luxvisions Innotech Limited HP HD Camera                | 2         | 0.91%   |
| Logitech C922 Pro Stream Webcam                         | 2         | 0.91%   |
| IMC Networks USB HD Webcam                              | 2         | 0.91%   |
| IMC Networks Integrated RGB Camera                      | 2         | 0.91%   |
| Chicony LG HD WebCam                                    | 2         | 0.91%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 2         | 0.91%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 0.91%   |
| Chicony HP TrueVision HD Camera                         | 2         | 0.91%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 2         | 0.91%   |
| Apple Built-in iSight                                   | 2         | 0.91%   |
| Acer Integrated Camera                                  | 2         | 0.91%   |
| Acer BisonCam,NB Pro                                    | 2         | 0.91%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 18        | 30.51%  |
| Validity Sensors                   | 11        | 18.64%  |
| Samsung Electronics                | 9         | 15.25%  |
| Shenzhen Goodix Technology         | 6         | 10.17%  |
| Upek                               | 4         | 6.78%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 6.78%   |
| STMicroelectronics                 | 2         | 3.39%   |
| LighTuning Technology              | 2         | 3.39%   |
| Elan Microelectronics              | 2         | 3.39%   |
| AuthenTec                          | 1         | 1.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung Fingerprint Sensor Device - 730B                        | 6         | 10.17%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 6.78%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 4         | 6.78%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 4         | 6.78%   |
| Shenzhen Goodix  FingerPrint Device                             | 4         | 6.78%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 4         | 6.78%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 3         | 5.08%   |
| Samsung Fingerprint Device                                      | 3         | 5.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 3.39%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 3.39%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 3.39%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 3.39%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 3.39%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 3.39%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 3.39%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 1         | 1.69%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 1.69%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 1.69%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 1.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.69%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.69%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.69%   |
| Synaptics WBDI Device                                           | 1         | 1.69%   |
| Synaptics WBDI                                                  | 1         | 1.69%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.69%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.69%   |
| Elan ELAN:ARM-M4                                                | 1         | 1.69%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Upek             | 2         | 25%     |
| Broadcom         | 2         | 25%     |
| Alcor Micro      | 2         | 25%     |
| SCM Microsystems | 1         | 12.5%   |
| O2 Micro         | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 25%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 12.5%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 151       | 57.41%  |
| 1     | 87        | 33.08%  |
| 2     | 18        | 6.84%   |
| 3     | 5         | 1.9%    |
| 5     | 1         | 0.38%   |
| 4     | 1         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 59        | 42.14%  |
| Graphics card            | 31        | 22.14%  |
| Net/wireless             | 19        | 13.57%  |
| Multimedia controller    | 10        | 7.14%   |
| Chipcard                 | 8         | 5.71%   |
| Sound                    | 3         | 2.14%   |
| Communication controller | 3         | 2.14%   |
| Bluetooth                | 3         | 2.14%   |
| Net/ethernet             | 2         | 1.43%   |
| Unassigned class         | 1         | 0.71%   |
| Camera                   | 1         | 0.71%   |

