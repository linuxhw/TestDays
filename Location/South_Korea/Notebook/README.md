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

Total: 327

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 47        | 19.67%  |
| Ubuntu 18.04       | 19        | 7.95%   |
| Ubuntu 22.04       | 18        | 7.53%   |
| Ubuntu 21.10       | 7         | 2.93%   |
| Gooroom            | 7         | 2.93%   |
| Debian 11          | 7         | 2.93%   |
| Arch               | 6         | 2.51%   |
| Arch Rolling       | 5         | 2.09%   |
| Linux Mint 20.3    | 4         | 1.67%   |
| Linux Mint 20.1    | 4         | 1.67%   |
| Fedora 37          | 4         | 1.67%   |
| Fedora 36          | 4         | 1.67%   |
| Fedora 32          | 4         | 1.67%   |
| Zorin 16           | 3         | 1.26%   |
| Ubuntu 19.10       | 3         | 1.26%   |
| Ubuntu 19.04       | 3         | 1.26%   |
| ROSA R11           | 3         | 1.26%   |
| OpenMandriva 4.2   | 3         | 1.26%   |
| Kubuntu 22.04      | 3         | 1.26%   |
| HamoniKR 4.0       | 3         | 1.26%   |
| Fedora 34          | 3         | 1.26%   |
| Debian 10          | 3         | 1.26%   |
| CentOS 8           | 3         | 1.26%   |
| Zorin 15           | 2         | 0.84%   |
| Ubuntu MATE 18.04  | 2         | 0.84%   |
| Ubuntu 22.10       | 2         | 0.84%   |
| SteamOS 3.4.4      | 2         | 0.84%   |
| ROSA R10           | 2         | 0.84%   |
| Pop!_OS 21.10      | 2         | 0.84%   |
| OpenMandriva 23.01 | 2         | 0.84%   |
| Manjaro 21.3.0     | 2         | 0.84%   |
| LMDE 5             | 2         | 0.84%   |
| Linux Mint 20      | 2         | 0.84%   |
| KDE neon 20.04     | 2         | 0.84%   |
| Fedora 38          | 2         | 0.84%   |
| Endless 3.8.5      | 2         | 0.84%   |
| Xubuntu 20.04      | 1         | 0.42%   |
| Ubuntu Unity 18.04 | 1         | 0.42%   |
| Ubuntu Unity 16.04 | 1         | 0.42%   |
| Ubuntu 21.04       | 1         | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 99        | 43.04%  |
| Fedora       | 18        | 7.83%   |
| Linux Mint   | 13        | 5.65%   |
| Debian       | 10        | 4.35%   |
| Manjaro      | 9         | 3.91%   |
| Arch         | 9         | 3.91%   |
| OpenMandriva | 8         | 3.48%   |
| Gooroom      | 8         | 3.48%   |
| Kubuntu      | 6         | 2.61%   |
| Zorin        | 5         | 2.17%   |
| ROSA         | 5         | 2.17%   |
| Endless      | 5         | 2.17%   |
| Pop!_OS      | 4         | 1.74%   |
| No1          | 4         | 1.74%   |
| HamoniKR     | 4         | 1.74%   |
| CentOS       | 4         | 1.74%   |
| SteamOS      | 3         | 1.3%    |
| KDE neon     | 3         | 1.3%    |
| Ubuntu Unity | 2         | 0.87%   |
| Ubuntu MATE  | 2         | 0.87%   |
| LMDE         | 2         | 0.87%   |
| EndeavourOS  | 2         | 0.87%   |
| Xubuntu      | 1         | 0.43%   |
| openSUSE     | 1         | 0.43%   |
| Lubuntu      | 1         | 0.43%   |
| Gentoo       | 1         | 0.43%   |
| Garuda Linux | 1         | 0.43%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.15.0-53-generic               | 5         | 1.98%   |
| 5.10.0-19-amd64                 | 5         | 1.98%   |
| 5.4.0-42-generic                | 4         | 1.59%   |
| 5.15.0-58-generic               | 4         | 1.59%   |
| 5.10.0-17-amd64                 | 4         | 1.59%   |
| 5.8.0-43-generic                | 3         | 1.19%   |
| 5.4.0-58-generic                | 3         | 1.19%   |
| 5.4.0-26-generic                | 3         | 1.19%   |
| 5.3.0-40-generic                | 3         | 1.19%   |
| 5.19.15-201.fc36.x86_64         | 3         | 1.19%   |
| 5.15.0-56-generic               | 3         | 1.19%   |
| 5.13.0-28-generic               | 3         | 1.19%   |
| 5.11.0-37-generic               | 3         | 1.19%   |
| 4.19.0-9-amd64                  | 3         | 1.19%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3         | 1.19%   |
| 6.1.1-desktop-1omv2290          | 2         | 0.79%   |
| 5.8.4-200.fc32.x86_64           | 2         | 0.79%   |
| 5.8.0-53-generic                | 2         | 0.79%   |
| 5.4.0-81-generic                | 2         | 0.79%   |
| 5.4.0-56-generic                | 2         | 0.79%   |
| 5.4.0-48-generic                | 2         | 0.79%   |
| 5.4.0-39-generic                | 2         | 0.79%   |
| 5.4.0-33-generic                | 2         | 0.79%   |
| 5.4.0-31-generic                | 2         | 0.79%   |
| 5.4.0-29-generic                | 2         | 0.79%   |
| 5.3.0-46-generic                | 2         | 0.79%   |
| 5.18.5-1-MANJARO                | 2         | 0.79%   |
| 5.15.0-67-generic               | 2         | 0.79%   |
| 5.15.0-60-generic               | 2         | 0.79%   |
| 5.15.0-52-generic               | 2         | 0.79%   |
| 5.15.0-33-generic               | 2         | 0.79%   |
| 5.15.0-27-generic               | 2         | 0.79%   |
| 5.13.0-valve36-1-neptune        | 2         | 0.79%   |
| 5.13.0-44-generic               | 2         | 0.79%   |
| 5.13.0-27-generic               | 2         | 0.79%   |
| 5.10.14-desktop-1omv4002        | 2         | 0.79%   |
| 5.0.0-37-generic                | 2         | 0.79%   |
| 5.0.0-25-generic                | 2         | 0.79%   |
| 5.0.0-13-generic                | 2         | 0.79%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 46        | 18.93%  |
| 5.15.0  | 26        | 10.7%   |
| 5.13.0  | 16        | 6.58%   |
| 5.8.0   | 12        | 4.94%   |
| 5.10.0  | 12        | 4.94%   |
| 5.11.0  | 10        | 4.12%   |
| 4.15.0  | 10        | 4.12%   |
| 5.3.0   | 9         | 3.7%    |
| 5.0.0   | 7         | 2.88%   |
| 4.18.0  | 7         | 2.88%   |
| 4.19.0  | 6         | 2.47%   |
| 5.19.15 | 3         | 1.23%   |
| 5.19.0  | 3         | 1.23%   |
| 6.1.1   | 2         | 0.82%   |
| 6.0.0   | 2         | 0.82%   |
| 5.8.4   | 2         | 0.82%   |
| 5.18.5  | 2         | 0.82%   |
| 5.16.19 | 2         | 0.82%   |
| 5.15.11 | 2         | 0.82%   |
| 5.14.0  | 2         | 0.82%   |
| 5.10.14 | 2         | 0.82%   |
| 4.9.60  | 2         | 0.82%   |
| 6.2.9   | 1         | 0.41%   |
| 6.2.8   | 1         | 0.41%   |
| 6.2.6   | 1         | 0.41%   |
| 6.2.5   | 1         | 0.41%   |
| 6.2.2   | 1         | 0.41%   |
| 6.1.9   | 1         | 0.41%   |
| 6.1.13  | 1         | 0.41%   |
| 6.1.11  | 1         | 0.41%   |
| 6.1.10  | 1         | 0.41%   |
| 6.1.0   | 1         | 0.41%   |
| 6.0.9   | 1         | 0.41%   |
| 6.0.6   | 1         | 0.41%   |
| 6.0.2   | 1         | 0.41%   |
| 6.0.14  | 1         | 0.41%   |
| 5.9.9   | 1         | 0.41%   |
| 5.8.18  | 1         | 0.41%   |
| 5.8.15  | 1         | 0.41%   |
| 5.7.17  | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 48        | 19.83%  |
| 5.15    | 34        | 14.05%  |
| 5.13    | 17        | 7.02%   |
| 5.8     | 16        | 6.61%   |
| 5.10    | 16        | 6.61%   |
| 5.11    | 15        | 6.2%    |
| 4.15    | 11        | 4.55%   |
| 5.3     | 10        | 4.13%   |
| 4.18    | 8         | 3.31%   |
| 6.1     | 7         | 2.89%   |
| 5.19    | 7         | 2.89%   |
| 5.0     | 7         | 2.89%   |
| 4.19    | 7         | 2.89%   |
| 6.0     | 6         | 2.48%   |
| 6.2     | 5         | 2.07%   |
| 5.16    | 5         | 2.07%   |
| 5.12    | 5         | 2.07%   |
| 5.14    | 4         | 1.65%   |
| 5.18    | 3         | 1.24%   |
| 5.6     | 2         | 0.83%   |
| 4.9     | 2         | 0.83%   |
| 5.9     | 1         | 0.41%   |
| 5.7     | 1         | 0.41%   |
| 5.5     | 1         | 0.41%   |
| 5.2     | 1         | 0.41%   |
| 5.17    | 1         | 0.41%   |
| 4.16    | 1         | 0.41%   |
| 3.10    | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 220       | 98.21%  |
| i686    | 3         | 1.34%   |
| aarch64 | 1         | 0.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 124       | 53.91%  |
| KDE5            | 34        | 14.78%  |
| Unknown         | 17        | 7.39%   |
| X-Cinnamon      | 12        | 5.22%   |
| LXDE            | 8         | 3.48%   |
| GNOME Flashback | 8         | 3.48%   |
| XFCE            | 7         | 3.04%   |
| Cinnamon        | 6         | 2.61%   |
| KDE4            | 3         | 1.3%    |
| KDE             | 3         | 1.3%    |
| i3              | 3         | 1.3%    |
| Unity           | 2         | 0.87%   |
| MATE            | 2         | 0.87%   |
| sway            | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 159       | 70.35%  |
| Wayland | 46        | 20.35%  |
| Unknown | 13        | 5.75%   |
| Tty     | 8         | 3.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 107       | 46.32%  |
| GDM     | 47        | 20.35%  |
| SDDM    | 25        | 10.82%  |
| GDM3    | 20        | 8.66%   |
| LightDM | 15        | 6.49%   |
| TDM     | 13        | 5.63%   |
| KDM     | 3         | 1.3%    |
| XDM     | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ko_KR   | 99        | 43.04%  |
| en_US   | 86        | 37.39%  |
| Unknown | 26        | 11.3%   |
| en_CA   | 4         | 1.74%   |
| zh_CN   | 3         | 1.3%    |
| C       | 3         | 1.3%    |
| id_ID   | 2         | 0.87%   |
| vi_VN   | 1         | 0.43%   |
| pt_BR   | 1         | 0.43%   |
| fr_FR   | 1         | 0.43%   |
| en_NZ   | 1         | 0.43%   |
| el_GR   | 1         | 0.43%   |
| ba_RU   | 1         | 0.43%   |
| ar_EG   | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 156       | 69.33%  |
| BIOS | 69        | 30.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 184       | 81.06%  |
| Btrfs   | 21        | 9.25%   |
| Xfs     | 6         | 2.64%   |
| Overlay | 6         | 2.64%   |
| Unknown | 6         | 2.64%   |
| Zfs     | 3         | 1.32%   |
| Rootfs  | 1         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 110       | 48.25%  |
| Unknown | 103       | 45.18%  |
| MBR     | 15        | 6.58%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 211       | 93.78%  |
| Yes       | 14        | 6.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 154       | 67.84%  |
| Yes       | 73        | 32.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 50        | 22.32%  |
| Samsung Electronics | 28        | 12.5%   |
| Hewlett-Packard     | 26        | 11.61%  |
| ASUSTek Computer    | 22        | 9.82%   |
| LG Electronics      | 21        | 9.38%   |
| Dell                | 15        | 6.7%    |
| MSI                 | 11        | 4.91%   |
| Apple               | 11        | 4.91%   |
| Notebook            | 4         | 1.79%   |
| HANSUNG COMPUTER    | 4         | 1.79%   |
| Valve               | 3         | 1.34%   |
| Acer                | 3         | 1.34%   |
| Toshiba             | 2         | 0.89%   |
| Razer               | 2         | 0.89%   |
| Google              | 2         | 0.89%   |
| Gigabyte Technology | 2         | 0.89%   |
| Wolfnfox            | 1         | 0.45%   |
| WEIPAI              | 1         | 0.45%   |
| TG                  | 1         | 0.45%   |
| Teclast             | 1         | 0.45%   |
| Sony                | 1         | 0.45%   |
| SLIMBOOK            | 1         | 0.45%   |
| Pine Microsystems   | 1         | 0.45%   |
| MS                  | 1         | 0.45%   |
| MECHREVO            | 1         | 0.45%   |
| Jooyontech Computer | 1         | 0.45%   |
| Jooyon Tech         | 1         | 0.45%   |
| Intel               | 1         | 0.45%   |
| IMUZ                | 1         | 0.45%   |
| Clevo               | 1         | 0.45%   |
| AVERATEC            | 1         | 0.45%   |
| AMI                 | 1         | 0.45%   |
| Alienware           | 1         | 0.45%   |
| Unknown             | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Valve Jupiter                                     | 3         | 1.34%   |
| Samsung 950XED                                    | 3         | 1.34%   |
| Samsung 950XCJ/951XCJ/950XCR                      | 3         | 1.34%   |
| Samsung 760XDA                                    | 2         | 0.89%   |
| Razer Blade 17 (2022) - RZ09-0423                 | 2         | 0.89%   |
| Notebook N650DU                                   | 2         | 0.89%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01S00              | 2         | 0.89%   |
| Lenovo IdeaPad 3 15IIL05 81WE                     | 2         | 0.89%   |
| HP Stream Notebook PC 13                          | 2         | 0.89%   |
| HP Laptop 15-db1xxx                               | 2         | 0.89%   |
| HP EliteBook 855 G7 Notebook PC                   | 2         | 0.89%   |
| HANSUNG COMPUTER TFX5470H                         | 2         | 0.89%   |
| Dell XPS 15 7590                                  | 2         | 0.89%   |
| Dell Inspiron 15 5510                             | 2         | 0.89%   |
| Apple MacBookPro16,1                              | 2         | 0.89%   |
| Wolfnfox WF-TBAT                                  | 1         | 0.45%   |
| WEIPAI S15                                        | 1         | 0.45%   |
| Toshiba Satellite P50-B-103                       | 1         | 0.45%   |
| Toshiba Satellite L655                            | 1         | 0.45%   |
| TG NXI-A7000 Series                               | 1         | 0.45%   |
| Teclast tPAD                                      | 1         | 0.45%   |
| Sony VPCEA36FK                                    | 1         | 0.45%   |
| SLIMBOOK PROX15-AMD                               | 1         | 0.45%   |
| Samsung X120/X170/X171                            | 1         | 0.45%   |
| Samsung SX11S                                     | 1         | 0.45%   |
| Samsung RC420/RC520/RC720                         | 1         | 0.45%   |
| Samsung R59P/R60P/R61P                            | 1         | 0.45%   |
| Samsung R440/R480                                 | 1         | 0.45%   |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.45%   |
| Samsung 940XFG                                    | 1         | 0.45%   |
| Samsung 905S3G/906S3G/915S3G                      | 1         | 0.45%   |
| Samsung 900X5N                                    | 1         | 0.45%   |
| Samsung 800G5M/800G5W                             | 1         | 0.45%   |
| Samsung 760XBE                                    | 1         | 0.45%   |
| Samsung 730QCJ/730QCR                             | 1         | 0.45%   |
| Samsung 670Z5E                                    | 1         | 0.45%   |
| Samsung 570Z5E/580Z5E                             | 1         | 0.45%   |
| Samsung 550XED                                    | 1         | 0.45%   |
| Samsung 530U3BI/530U4BI/530U4BH                   | 1         | 0.45%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 33        | 14.73%  |
| Lenovo IdeaPad            | 11        | 4.91%   |
| ASUS VivoBook             | 8         | 3.57%   |
| HP Pavilion               | 7         | 3.13%   |
| HP Laptop                 | 5         | 2.23%   |
| HP EliteBook              | 5         | 2.23%   |
| Dell Inspiron             | 5         | 2.23%   |
| Dell XPS                  | 4         | 1.79%   |
| Valve Jupiter             | 3         | 1.34%   |
| Samsung 950XED            | 3         | 1.34%   |
| Samsung 950XCJ            | 3         | 1.34%   |
| HP Stream                 | 3         | 1.34%   |
| Dell Latitude             | 3         | 1.34%   |
| ASUS ROG                  | 3         | 1.34%   |
| Toshiba Satellite         | 2         | 0.89%   |
| Samsung 760XDA            | 2         | 0.89%   |
| Razer Blade               | 2         | 0.89%   |
| Notebook N650DU           | 2         | 0.89%   |
| MSI Prestige              | 2         | 0.89%   |
| HP ProBook                | 2         | 0.89%   |
| HANSUNG COMPUTER TFX5470H | 2         | 0.89%   |
| ASUS TUF                  | 2         | 0.89%   |
| Apple MacBookPro5         | 2         | 0.89%   |
| Apple MacBookPro16        | 2         | 0.89%   |
| Acer Swift                | 2         | 0.89%   |
| Wolfnfox WF-TBAT          | 1         | 0.45%   |
| WEIPAI S15                | 1         | 0.45%   |
| TG NXI-A7000              | 1         | 0.45%   |
| Teclast tPAD              | 1         | 0.45%   |
| Sony VPCEA36FK            | 1         | 0.45%   |
| SLIMBOOK PROX15-AMD       | 1         | 0.45%   |
| Samsung X120              | 1         | 0.45%   |
| Samsung SX11S             | 1         | 0.45%   |
| Samsung RC420             | 1         | 0.45%   |
| Samsung R59P              | 1         | 0.45%   |
| Samsung R440              | 1         | 0.45%   |
| Samsung 950XDB            | 1         | 0.45%   |
| Samsung 940XFG            | 1         | 0.45%   |
| Samsung 905S3G            | 1         | 0.45%   |
| Samsung 900X5N            | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 43        | 19.2%   |
| 2021    | 29        | 12.95%  |
| 2019    | 23        | 10.27%  |
| 2018    | 18        | 8.04%   |
| 2022    | 17        | 7.59%   |
| 2014    | 15        | 6.7%    |
| 2013    | 14        | 6.25%   |
| 2011    | 11        | 4.91%   |
| 2017    | 8         | 3.57%   |
| 2016    | 8         | 3.57%   |
| 2012    | 8         | 3.57%   |
| 2010    | 8         | 3.57%   |
| 2008    | 7         | 3.13%   |
| 2015    | 5         | 2.23%   |
| 2009    | 4         | 1.79%   |
| 2007    | 3         | 1.34%   |
| 2006    | 2         | 0.89%   |
| Unknown | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 224       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 203       | 89.82%  |
| Enabled  | 23        | 10.18%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 222       | 99.11%  |
| Yes  | 2         | 0.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 60        | 26.43%  |
| 16.01-24.0  | 47        | 20.7%   |
| 8.01-16.0   | 39        | 17.18%  |
| 3.01-4.0    | 35        | 15.42%  |
| 32.01-64.0  | 21        | 9.25%   |
| 1.01-2.0    | 13        | 5.73%   |
| 64.01-256.0 | 8         | 3.52%   |
| 24.01-32.0  | 3         | 1.32%   |
| 2.01-3.0    | 1         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 73        | 29.92%  |
| 2.01-3.0   | 61        | 25%     |
| 4.01-8.0   | 39        | 15.98%  |
| 3.01-4.0   | 37        | 15.16%  |
| 0.51-1.0   | 17        | 6.97%   |
| 8.01-16.0  | 12        | 4.92%   |
| 16.01-24.0 | 3         | 1.23%   |
| 24.01-32.0 | 1         | 0.41%   |
| 0.01-0.5   | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 144       | 62.61%  |
| 2      | 73        | 31.74%  |
| 3      | 10        | 4.35%   |
| 4      | 2         | 0.87%   |
| 0      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 190       | 84.82%  |
| Yes       | 34        | 15.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 69.91%  |
| No        | 68        | 30.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 216       | 96%     |
| No        | 9         | 4%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 83.19%  |
| No        | 38        | 16.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| South Korea | 224       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Seoul         | 39        | 16.6%   |
| Seocho-gu     | 13        | 5.53%   |
| Suwon         | 10        | 4.26%   |
| Gwanak-gu     | 8         | 3.4%    |
| Uiwang        | 7         | 2.98%   |
| Seongnam-si   | 6         | 2.55%   |
| Jung-gu       | 6         | 2.55%   |
| Hwaseong-si   | 6         | 2.55%   |
| Yongin-si     | 5         | 2.13%   |
| Seongbuk-gu   | 5         | 2.13%   |
| Yongsan-gu    | 4         | 1.7%    |
| Nam-gu        | 4         | 1.7%    |
| Mapo-gu       | 4         | 1.7%    |
| Incheon       | 4         | 1.7%    |
| Geumjeong-gu  | 4         | 1.7%    |
| Daejeon       | 4         | 1.7%    |
| Daegu         | 4         | 1.7%    |
| Busan         | 4         | 1.7%    |
| Bupyeong-gu   | 4         | 1.7%    |
| Anyang-si     | 4         | 1.7%    |
| Pyeongtaek-si | 3         | 1.28%   |
| Jeonju        | 3         | 1.28%   |
| Gwangju       | 3         | 1.28%   |
| Gangseo-gu    | 3         | 1.28%   |
| Gangnam-gu    | 3         | 1.28%   |
| Yuseong-gu    | 2         | 0.85%   |
| Yongsan-dong  | 2         | 0.85%   |
| Yeonsu-gu     | 2         | 0.85%   |
| Yangju        | 2         | 0.85%   |
| Songpa-gu     | 2         | 0.85%   |
| Siheung-si    | 2         | 0.85%   |
| Seo-gu        | 2         | 0.85%   |
| Namdong-gu    | 2         | 0.85%   |
| Jeju City     | 2         | 0.85%   |
| Gyeongsan-si  | 2         | 0.85%   |
| Goyang-si     | 2         | 0.85%   |
| Gimpo-si      | 2         | 0.85%   |
| Danyang-gun   | 2         | 0.85%   |
| Cheongju-si   | 2         | 0.85%   |
| Changwon      | 2         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 78        | 95     | 25.91%  |
| WDC                            | 31        | 33     | 10.3%   |
| SanDisk                        | 22        | 22     | 7.31%   |
| Unknown                        | 20        | 24     | 6.64%   |
| SK hynix                       | 20        | 27     | 6.64%   |
| Seagate                        | 16        | 20     | 5.32%   |
| Toshiba                        | 13        | 15     | 4.32%   |
| Crucial                        | 12        | 13     | 3.99%   |
| Kingston                       | 8         | 10     | 2.66%   |
| Intel                          | 8         | 13     | 2.66%   |
| Micron Technology              | 7         | 8      | 2.33%   |
| Apple                          | 6         | 7      | 1.99%   |
| Phison                         | 5         | 6      | 1.66%   |
| Hitachi                        | 5         | 6      | 1.66%   |
| A-DATA Technology              | 5         | 5      | 1.66%   |
| Team                           | 3         | 3      | 1%      |
| TAMMUZ                         | 3         | 5      | 1%      |
| Silicon Motion                 | 3         | 3      | 1%      |
| HGST                           | 3         | 4      | 1%      |
| UMIS                           | 2         | 2      | 0.66%   |
| KIOXIA                         | 2         | 2      | 0.66%   |
| JMicron Technology             | 2         | 2      | 0.66%   |
| Fujitsu                        | 2         | 2      | 0.66%   |
| China                          | 2         | 2      | 0.66%   |
| ZTC                            | 1         | 1      | 0.33%   |
| XPG                            | 1         | 2      | 0.33%   |
| VIVA300s                       | 1         | 1      | 0.33%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.33%   |
| TYPEC 1T                       | 1         | 1      | 0.33%   |
| Transcend                      | 1         | 2      | 0.33%   |
| T-FORCE                        | 1         | 1      | 0.33%   |
| Solid State Storage Technology | 1         | 1      | 0.33%   |
| RevuAhn                        | 1         | 1      | 0.33%   |
| Plextor                        | 1         | 1      | 0.33%   |
| Phison Electronics             | 1         | 1      | 0.33%   |
| O2 Micro                       | 1         | 1      | 0.33%   |
| MG                             | 1         | 1      | 0.33%   |
| LITEONIT                       | 1         | 1      | 0.33%   |
| LITEON                         | 1         | 1      | 0.33%   |
| KingSpec                       | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix SHGP31-1000GM-2 1TB                           | 4         | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 3         | 0.94%   |
| SanDisk NVMe SSD Drive 512GB                           | 3         | 0.94%   |
| Samsung SSD 980 PRO 2TB                                | 3         | 0.94%   |
| Samsung SSD 860 EVO 500GB                              | 3         | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB     | 3         | 0.94%   |
| Samsung MZVL21T0HCLR-00B00 1TB                         | 3         | 0.94%   |
| WDC WDS100T2B0C-00PXH0 1TB                             | 2         | 0.63%   |
| WDC WD50 00LPVX-22V0TT0 500GB                          | 2         | 0.63%   |
| Unknown SLD64G  64GB                                   | 2         | 0.63%   |
| Unknown SD/MMC/MS PRO 249GB                            | 2         | 0.63%   |
| Unknown MMC Card  512GB                                | 2         | 0.63%   |
| Unknown MMC Card  32GB                                 | 2         | 0.63%   |
| Unknown MMC Card  256GB                                | 2         | 0.63%   |
| Toshiba KBG30ZMV256G 256GB                             | 2         | 0.63%   |
| SK hynix SHGP31-1000GM 1TB                             | 2         | 0.63%   |
| SK hynix NVMe SSD Drive 256GB                          | 2         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1024GB | 2         | 0.63%   |
| Seagate ST1000LM048-2E7172 1TB                         | 2         | 0.63%   |
| Seagate ST1000LM035-1RK172 970GB                       | 2         | 0.63%   |
| Seagate Expansion 4TB                                  | 2         | 0.63%   |
| SanDisk SD8SBAT256G1122 256GB SSD                      | 2         | 0.63%   |
| SanDisk NVMe SSD Drive 256GB                           | 2         | 0.63%   |
| Samsung SSD 860 EVO 1TB                                | 2         | 0.63%   |
| Samsung SSD 830 Series 256GB                           | 2         | 0.63%   |
| Samsung SSD 750 EVO 120GB                              | 2         | 0.63%   |
| Samsung PSSD T7 2TB                                    | 2         | 0.63%   |
| Samsung NVMe SSD Drive 2TB                             | 2         | 0.63%   |
| Samsung NVMe SSD Drive 256GB                           | 2         | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB      | 2         | 0.63%   |
| Samsung MZVLQ1T0HBLB-00B 1TB                           | 2         | 0.63%   |
| Samsung MZVLB512HAJQ-00000 512GB                       | 2         | 0.63%   |
| Samsung MZVLB256HBHQ-000 256GB                         | 2         | 0.63%   |
| Samsung MZNLN256HAJQ-00000 256GB SSD                   | 2         | 0.63%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD                   | 2         | 0.63%   |
| Kingston OM8PCP3512F-AB 512GB                          | 2         | 0.63%   |
| JMicron Tech 250GB                                     | 2         | 0.63%   |
| Intel SSDPEKNU512GZ 512GB                              | 2         | 0.63%   |
| HGST HTS721010A9E630 1TB                               | 2         | 0.63%   |
| Crucial CT500MX500SSD1 500GB                           | 2         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 19     | 30.61%  |
| WDC                 | 14        | 14     | 28.57%  |
| Toshiba             | 6         | 6      | 12.24%  |
| Hitachi             | 5         | 6      | 10.2%   |
| HGST                | 3         | 4      | 6.12%   |
| Unknown             | 2         | 2      | 4.08%   |
| Fujitsu             | 2         | 2      | 4.08%   |
| Samsung Electronics | 1         | 1      | 2.04%   |
| ipTIME              | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 46     | 37.14%  |
| SanDisk             | 11        | 11     | 10.48%  |
| Crucial             | 11        | 12     | 10.48%  |
| WDC                 | 5         | 6      | 4.76%   |
| SK hynix            | 5         | 6      | 4.76%   |
| TAMMUZ              | 3         | 5      | 2.86%   |
| Micron Technology   | 3         | 4      | 2.86%   |
| Kingston            | 3         | 4      | 2.86%   |
| Intel               | 3         | 4      | 2.86%   |
| Team                | 2         | 2      | 1.9%    |
| China               | 2         | 2      | 1.9%    |
| Apple               | 2         | 2      | 1.9%    |
| A-DATA Technology   | 2         | 2      | 1.9%    |
| ZTC                 | 1         | 1      | 0.95%   |
| TYPEC 1T            | 1         | 1      | 0.95%   |
| Transcend           | 1         | 2      | 0.95%   |
| Toshiba             | 1         | 1      | 0.95%   |
| T-FORCE             | 1         | 1      | 0.95%   |
| RevuAhn             | 1         | 1      | 0.95%   |
| Plextor             | 1         | 1      | 0.95%   |
| MG                  | 1         | 1      | 0.95%   |
| LITEONIT            | 1         | 1      | 0.95%   |
| LITEON              | 1         | 1      | 0.95%   |
| KingSpec            | 1         | 1      | 0.95%   |
| IPLEX               | 1         | 1      | 0.95%   |
| Biostar             | 1         | 1      | 0.95%   |
| Apacer              | 1         | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 113       | 150    | 40.07%  |
| SSD     | 97        | 121    | 34.4%   |
| HDD     | 49        | 55     | 17.38%  |
| MMC     | 18        | 22     | 6.38%   |
| Unknown | 5         | 6      | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 118       | 163    | 44.36%  |
| NVMe | 113       | 148    | 42.48%  |
| MMC  | 18        | 22     | 6.77%   |
| SAS  | 17        | 21     | 6.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 99        | 123    | 68.28%  |
| 0.51-1.0   | 37        | 41     | 25.52%  |
| 1.01-2.0   | 5         | 7      | 3.45%   |
| 3.01-4.0   | 2         | 3      | 1.38%   |
| 4.01-10.0  | 2         | 2      | 1.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 36.75%  |
| 251-500        | 47        | 20.09%  |
| 501-1000       | 30        | 12.82%  |
| 1001-2000      | 22        | 9.4%    |
| 51-100         | 19        | 8.12%   |
| 21-50          | 10        | 4.27%   |
| 1-20           | 9         | 3.85%   |
| More than 3000 | 7         | 2.99%   |
| 2001-3000      | 3         | 1.28%   |
| Unknown        | 1         | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 98        | 40.83%  |
| 21-50          | 52        | 21.67%  |
| 101-250        | 31        | 12.92%  |
| 51-100         | 20        | 8.33%   |
| 251-500        | 18        | 7.5%    |
| 501-1000       | 11        | 4.58%   |
| 1001-2000      | 6         | 2.5%    |
| 2001-3000      | 2         | 0.83%   |
| More than 3000 | 1         | 0.42%   |
| Unknown        | 1         | 0.42%   |

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
| Detected | 130       | 194    | 52.85%  |
| Works    | 102       | 146    | 41.46%  |
| Malfunc  | 14        | 14     | 5.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 122       | 45.35%  |
| Samsung Electronics              | 38        | 14.13%  |
| AMD                              | 26        | 9.67%   |
| SanDisk                          | 23        | 8.55%   |
| SK hynix                         | 14        | 5.2%    |
| Phison Electronics               | 8         | 2.97%   |
| Toshiba America Info Systems     | 6         | 2.23%   |
| Kingston Technology Company      | 5         | 1.86%   |
| Silicon Motion                   | 4         | 1.49%   |
| Micron Technology                | 4         | 1.49%   |
| Apple                            | 4         | 1.49%   |
| Union Memory (Shenzhen)          | 3         | 1.12%   |
| ADATA Technology                 | 3         | 1.12%   |
| Nvidia                           | 2         | 0.74%   |
| KIOXIA                           | 2         | 0.74%   |
| Solid State Storage Technology   | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| O2 Micro                         | 1         | 0.37%   |
| Micron/Crucial Technology        | 1         | 0.37%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24        | 8.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 5.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 4.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 3.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 3.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 3.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 3.58%   |
| Samsung NVMe SSD Controller 980                                                | 8         | 2.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 2.87%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 2.51%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 6         | 2.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 2.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 2.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 2.15%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 1.79%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.43%   |
| Micron NVMe Storage Controller                                                 | 4         | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.43%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 1.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.08%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 1.08%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 1.08%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 1.08%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 1.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.08%   |
| SanDisk PC SN520 NVMe SSD                                                      | 3         | 1.08%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 1.08%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.08%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.08%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.08%   |
| Intel SSD 660P Series                                                          | 3         | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.08%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.08%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 134       | 50.38%  |
| NVMe | 113       | 42.48%  |
| RAID | 11        | 4.14%   |
| IDE  | 8         | 3.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 177       | 79.02%  |
| AMD    | 46        | 20.54%  |
| ARM    | 1         | 0.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 2.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 2.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.23%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 2.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.79%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.79%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.79%   |
| Intel 12th Gen Core i5-1240P                  | 4         | 1.79%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 4         | 1.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.34%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.34%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.34%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.34%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.34%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 1.34%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.34%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 1.34%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.34%   |
| AMD Custom APU 0405                           | 3         | 1.34%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 0.89%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 2         | 0.89%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 0.89%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.89%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.89%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 0.89%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.89%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 2         | 0.89%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.89%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.89%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 0.89%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.89%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.89%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.89%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 0.89%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.89%   |
| Intel 12th Gen Core i9-12900H                 | 2         | 0.89%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 0.89%   |
| Intel 12th Gen Core i7-1260P                  | 2         | 0.89%   |
| Intel 11th Gen Core i7-11600H @ 2.90GHz       | 2         | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 49        | 21.88%  |
| Intel Core i5        | 47        | 20.98%  |
| Other                | 33        | 14.73%  |
| Intel Core i3        | 13        | 5.8%    |
| AMD Ryzen 5          | 13        | 5.8%    |
| AMD Ryzen 7          | 12        | 5.36%   |
| Intel Core 2 Duo     | 8         | 3.57%   |
| Intel Celeron        | 8         | 3.57%   |
| Intel Pentium        | 6         | 2.68%   |
| Intel Core i9        | 4         | 1.79%   |
| Intel Atom           | 4         | 1.79%   |
| AMD Ryzen 7 PRO      | 4         | 1.79%   |
| AMD Ryzen 3          | 3         | 1.34%   |
| Intel Pentium Silver | 2         | 0.89%   |
| Intel Genuine        | 2         | 0.89%   |
| Intel Core 2         | 2         | 0.89%   |
| AMD Ryzen 9          | 2         | 0.89%   |
| AMD Ryzen 5 PRO      | 2         | 0.89%   |
| AMD A4               | 2         | 0.89%   |
| AMD A10              | 2         | 0.89%   |
| Intel Xeon           | 1         | 0.45%   |
| Intel Pentium Dual   | 1         | 0.45%   |
| Intel Core m3        | 1         | 0.45%   |
| AMD Quad-Core        | 1         | 0.45%   |
| AMD Athlon II        | 1         | 0.45%   |
| AMD A6               | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 85        | 37.95%  |
| 4       | 78        | 34.82%  |
| 8       | 24        | 10.71%  |
| 6       | 23        | 10.27%  |
| 12      | 8         | 3.57%   |
| 14      | 4         | 1.79%   |
| 1       | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 223       | 99.55%  |
| 2      | 1         | 0.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 184       | 82.14%  |
| 1       | 39        | 17.41%  |
| Unknown | 1         | 0.45%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 220       | 98.21%  |
| Unknown        | 2         | 0.89%   |
| 64-bit         | 1         | 0.45%   |
| 32-bit         | 1         | 0.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 15.65%  |
| 0x806ec    | 13        | 5.65%   |
| 0x806c1    | 13        | 5.65%   |
| 0x306a9    | 11        | 4.78%   |
| 0x906a3    | 9         | 3.91%   |
| 0x806ea    | 9         | 3.91%   |
| 0x206a7    | 9         | 3.91%   |
| 0x0a50000c | 9         | 3.91%   |
| 0x20655    | 8         | 3.48%   |
| 0x08600106 | 7         | 3.04%   |
| 0x906e9    | 6         | 2.61%   |
| 0x806eb    | 6         | 2.61%   |
| 0x40651    | 6         | 2.61%   |
| 0x706e5    | 5         | 2.17%   |
| 0x08108102 | 5         | 2.17%   |
| 0xa0652    | 4         | 1.74%   |
| 0x906ea    | 4         | 1.74%   |
| 0x806e9    | 4         | 1.74%   |
| 0x706a1    | 4         | 1.74%   |
| 0x306d4    | 4         | 1.74%   |
| 0x306c3    | 4         | 1.74%   |
| 0x30678    | 4         | 1.74%   |
| 0x906ed    | 3         | 1.3%    |
| 0x806d1    | 3         | 1.3%    |
| 0x6fd      | 3         | 1.3%    |
| 0x406e3    | 3         | 1.3%    |
| 0x1067a    | 3         | 1.3%    |
| 0xa0660    | 2         | 0.87%   |
| 0x6f6      | 2         | 0.87%   |
| 0x406c3    | 2         | 0.87%   |
| 0x20652    | 2         | 0.87%   |
| 0x10676    | 2         | 0.87%   |
| 0x08608103 | 2         | 0.87%   |
| 0x08600103 | 2         | 0.87%   |
| 0x0700010f | 2         | 0.87%   |
| 0x06001119 | 2         | 0.87%   |
| 0xb06a2    | 1         | 0.43%   |
| 0x906a2    | 1         | 0.43%   |
| 0x706a8    | 1         | 0.43%   |
| 0x6fb      | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 50        | 22.32%  |
| Haswell          | 15        | 6.7%    |
| Zen 2            | 14        | 6.25%   |
| TigerLake        | 14        | 6.25%   |
| IvyBridge        | 12        | 5.36%   |
| Unknown          | 12        | 5.36%   |
| Zen 3            | 11        | 4.91%   |
| Westmere         | 11        | 4.91%   |
| SandyBridge      | 10        | 4.46%   |
| IceLake          | 9         | 4.02%   |
| Silvermont       | 7         | 3.13%   |
| CometLake        | 7         | 3.13%   |
| Alderlake Hybrid | 7         | 3.13%   |
| Zen+             | 6         | 2.68%   |
| Skylake          | 6         | 2.68%   |
| Penryn           | 6         | 2.68%   |
| Core             | 6         | 2.68%   |
| Goldmont plus    | 5         | 2.23%   |
| Broadwell        | 4         | 1.79%   |
| Jaguar           | 3         | 1.34%   |
| Zen              | 2         | 0.89%   |
| Piledriver       | 2         | 0.89%   |
| P6               | 1         | 0.45%   |
| Nehalem          | 1         | 0.45%   |
| K10              | 1         | 0.45%   |
| Excavator        | 1         | 0.45%   |
| Bonnell          | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 160       | 57.14%  |
| Nvidia                           | 63        | 22.5%   |
| AMD                              | 56        | 20%     |
| Silicon Integrated Systems [SiS] | 1         | 0.36%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 14        | 4.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 4.17%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 11        | 3.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 3.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 3.13%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.43%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.08%   |
| AMD Barcelo                                                                              | 6         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.74%   |
| Intel HD Graphics 630                                                                    | 5         | 1.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.74%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.39%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.39%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.39%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.04%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 1.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.04%   |
| Intel HD Graphics 620                                                                    | 3         | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.04%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 3         | 1.04%   |
| Nvidia TU117M                                                                            | 2         | 0.69%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.69%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.69%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.69%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                               | 2         | 0.69%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.69%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 107       | 47.77%  |
| Intel + Nvidia | 46        | 20.54%  |
| 1 x AMD        | 43        | 19.2%   |
| 1 x Nvidia     | 12        | 5.36%   |
| Intel + AMD    | 6         | 2.68%   |
| AMD + Nvidia   | 4         | 1.79%   |
| 2 x AMD        | 3         | 1.34%   |
| Other          | 1         | 0.45%   |
| 2 x Nvidia     | 1         | 0.45%   |
| 1 x SiS        | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 181       | 80.09%  |
| Proprietary | 33        | 14.6%   |
| Unknown     | 12        | 5.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 142       | 62.28%  |
| 0.01-0.5   | 27        | 11.84%  |
| 1.01-2.0   | 20        | 8.77%   |
| 3.01-4.0   | 18        | 7.89%   |
| 0.51-1.0   | 12        | 5.26%   |
| 5.01-6.0   | 4         | 1.75%   |
| 7.01-8.0   | 3         | 1.32%   |
| 8.01-16.0  | 2         | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 46        | 18.11%  |
| AU Optronics            | 41        | 16.14%  |
| BOE                     | 31        | 12.2%   |
| Samsung Electronics     | 29        | 11.42%  |
| Chimei Innolux          | 27        | 10.63%  |
| Goldstar                | 10        | 3.94%   |
| Apple                   | 10        | 3.94%   |
| Sharp                   | 8         | 3.15%   |
| Dell                    | 8         | 3.15%   |
| PANDA                   | 5         | 1.97%   |
| Lenovo                  | 5         | 1.97%   |
| Valve                   | 3         | 1.18%   |
| Philips                 | 3         | 1.18%   |
| JCH                     | 3         | 1.18%   |
| CPT                     | 3         | 1.18%   |
| ALP                     | 3         | 1.18%   |
| CSO                     | 2         | 0.79%   |
| Chi Mei Optoelectronics | 2         | 0.79%   |
| BenQ                    | 2         | 0.79%   |
| VMO                     | 1         | 0.39%   |
| TMX                     | 1         | 0.39%   |
| Sony                    | 1         | 0.39%   |
| PRISM+                  | 1         | 0.39%   |
| MSI                     | 1         | 0.39%   |
| InfoVision              | 1         | 0.39%   |
| HKC                     | 1         | 0.39%   |
| Hewlett-Packard         | 1         | 0.39%   |
| HannStar                | 1         | 0.39%   |
| Denver                  | 1         | 0.39%   |
| CM_                     | 1         | 0.39%   |
| AOC                     | 1         | 0.39%   |
| Ancor Communications    | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 4         | 1.55%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 1.55%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.55%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 3         | 1.16%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 1.16%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 1.16%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 1.16%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SDCA029 2560x1440 294x165mm 13.3-inch | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 2         | 0.78%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch               | 2         | 0.78%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 2         | 0.78%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 2         | 0.78%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch          | 2         | 0.78%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch          | 2         | 0.78%   |
| LG Display LCD Monitor LGD03B5 1920x1080 294x165mm 13.3-inch          | 2         | 0.78%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.78%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 2         | 0.78%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                 | 2         | 0.78%   |
| BOE LCD Monitor BOE06D7 3840x2160 345x194mm 15.6-inch                 | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO749D 3840x2160 381x214mm 17.2-inch        | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO6A92 1920x1080 344x194mm 15.5-inch        | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x165mm 13.2-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.78%   |
| AU Optronics LCD Monitor 1920x1080                                    | 2         | 0.78%   |
| Apple Color LCD APPA044 3072x1920 345x215mm 16.0-inch                 | 2         | 0.78%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch             | 1         | 0.39%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.39%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 0.39%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.39%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 125       | 51.65%  |
| 1366x768 (WXGA)    | 37        | 15.29%  |
| 3840x2160 (4K)     | 16        | 6.61%   |
| 2560x1600          | 9         | 3.72%   |
| 2560x1440 (QHD)    | 8         | 3.31%   |
| 1280x800 (WXGA)    | 8         | 3.31%   |
| 1600x900 (HD+)     | 7         | 2.89%   |
| 1920x1200 (WUXGA)  | 6         | 2.48%   |
| 2880x1800          | 5         | 2.07%   |
| 800x1280           | 3         | 1.24%   |
| 3440x1440          | 3         | 1.24%   |
| 1440x900 (WXGA+)   | 3         | 1.24%   |
| 3072x1920          | 2         | 0.83%   |
| 1680x1050 (WSXGA+) | 2         | 0.83%   |
| 1280x1024 (SXGA)   | 2         | 0.83%   |
| 3840x2400          | 1         | 0.41%   |
| 2560x1080          | 1         | 0.41%   |
| 2160x1350          | 1         | 0.41%   |
| 1680x945           | 1         | 0.41%   |
| 1400x1050          | 1         | 0.41%   |
| 1024x768 (XGA)     | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 107       | 41.96%  |
| 13      | 38        | 14.9%   |
| 14      | 28        | 10.98%  |
| 17      | 12        | 4.71%   |
| 27      | 11        | 4.31%   |
| 24      | 10        | 3.92%   |
| 16      | 8         | 3.14%   |
| 23      | 7         | 2.75%   |
| 31      | 4         | 1.57%   |
| 21      | 4         | 1.57%   |
| 12      | 4         | 1.57%   |
| 34      | 3         | 1.18%   |
| 20      | 3         | 1.18%   |
| 11      | 3         | 1.18%   |
| 7       | 3         | 1.18%   |
| Unknown | 2         | 0.78%   |
| 74      | 1         | 0.39%   |
| 54      | 1         | 0.39%   |
| 42      | 1         | 0.39%   |
| 40      | 1         | 0.39%   |
| 25      | 1         | 0.39%   |
| 19      | 1         | 0.39%   |
| 18      | 1         | 0.39%   |
| 10      | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 152       | 59.84%  |
| 201-300     | 34        | 13.39%  |
| 501-600     | 27        | 10.63%  |
| 351-400     | 15        | 5.91%   |
| 401-500     | 9         | 3.54%   |
| 601-700     | 5         | 1.97%   |
| 701-800     | 3         | 1.18%   |
| 1-100       | 3         | 1.18%   |
| Unknown     | 2         | 0.79%   |
| 801-900     | 1         | 0.39%   |
| 1501-2000   | 1         | 0.39%   |
| 1001-1500   | 1         | 0.39%   |
| 901-1000    | 1         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 174       | 78.03%  |
| 16/10   | 35        | 15.7%   |
| 21/9    | 3         | 1.35%   |
| 0.67    | 3         | 1.35%   |
| 5/4     | 2         | 0.9%    |
| 4/3     | 2         | 0.9%    |
| 3/2     | 2         | 0.9%    |
| Unknown | 2         | 0.9%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 106       | 41.57%  |
| 81-90          | 43        | 16.86%  |
| 71-80          | 21        | 8.24%   |
| 201-250        | 18        | 7.06%   |
| 301-350        | 11        | 4.31%   |
| 121-130        | 11        | 4.31%   |
| 351-500        | 7         | 2.75%   |
| 111-120        | 7         | 2.75%   |
| 61-70          | 4         | 1.57%   |
| 251-300        | 4         | 1.57%   |
| 151-200        | 4         | 1.57%   |
| 91-100         | 4         | 1.57%   |
| 51-60          | 3         | 1.18%   |
| 1-40           | 3         | 1.18%   |
| More than 1000 | 2         | 0.78%   |
| 141-150        | 2         | 0.78%   |
| 501-1000       | 2         | 0.78%   |
| Unknown        | 2         | 0.78%   |
| 41-50          | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 111       | 44.05%  |
| 101-120       | 48        | 19.05%  |
| 161-240       | 39        | 15.48%  |
| 51-100        | 36        | 14.29%  |
| More than 240 | 14        | 5.56%   |
| 1-50          | 2         | 0.79%   |
| Unknown       | 2         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 173       | 74.25%  |
| 2     | 44        | 18.88%  |
| 0     | 12        | 5.15%   |
| 3     | 4         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 145       | 41.79%  |
| Realtek Semiconductor            | 114       | 32.85%  |
| Qualcomm Atheros                 | 28        | 8.07%   |
| Broadcom                         | 22        | 6.34%   |
| ASIX Electronics                 | 8         | 2.31%   |
| MediaTek                         | 4         | 1.15%   |
| Marvell Technology Group         | 3         | 0.86%   |
| Apple                            | 3         | 0.86%   |
| TP-Link                          | 2         | 0.58%   |
| Samsung Electronics              | 2         | 0.58%   |
| Ralink Technology                | 2         | 0.58%   |
| Nvidia                           | 2         | 0.58%   |
| Lenovo                           | 2         | 0.58%   |
| Broadcom Limited                 | 2         | 0.58%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Ralink                           | 1         | 0.29%   |
| Quectel Wireless Solutions       | 1         | 0.29%   |
| Qualcomm                         | 1         | 0.29%   |
| Microsoft                        | 1         | 0.29%   |
| D-Link                           | 1         | 0.29%   |
| Comneon                          | 1         | 0.29%   |
| Arduino SA                       | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76        | 19.05%  |
| Intel Wi-Fi 6 AX200                                               | 25        | 6.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 3.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.01%   |
| Intel Wi-Fi 6 AX201                                               | 12        | 3.01%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 11        | 2.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 2.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.01%   |
| Intel Wireless 7260                                               | 8         | 2.01%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 2.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.5%    |
| Intel Wireless 8265 / 8275                                        | 6         | 1.5%    |
| Intel Wireless 3165                                               | 6         | 1.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 1%      |
| Intel Gemini Lake PCH CNVi WiFi                                   | 4         | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.75%   |
| Intel Wireless 7265                                               | 3         | 0.75%   |
| Intel Wireless 3160                                               | 3         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.75%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.75%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.75%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.75%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                | 3         | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.5%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 141       | 62.67%  |
| Realtek Semiconductor      | 29        | 12.89%  |
| Qualcomm Atheros           | 22        | 9.78%   |
| Broadcom                   | 19        | 8.44%   |
| MediaTek                   | 4         | 1.78%   |
| TP-Link                    | 2         | 0.89%   |
| Ralink Technology          | 2         | 0.89%   |
| Broadcom Limited           | 2         | 0.89%   |
| Ralink                     | 1         | 0.44%   |
| Quectel Wireless Solutions | 1         | 0.44%   |
| Qualcomm                   | 1         | 0.44%   |
| D-Link                     | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 25        | 11.01%  |
| Intel Wi-Fi 6 AX201                                           | 12        | 5.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 11        | 4.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 10        | 4.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 8         | 3.52%   |
| Intel Wireless 7260                                           | 8         | 3.52%   |
| Intel Wireless 8265 / 8275                                    | 6         | 2.64%   |
| Intel Wireless 3165                                           | 6         | 2.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 6         | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 5         | 2.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 2.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 5         | 2.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 5         | 2.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 4         | 1.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 4         | 1.76%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 4         | 1.76%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 1.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 4         | 1.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 3         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 1.32%   |
| Intel Wireless 7265                                           | 3         | 1.32%   |
| Intel Wireless 3160                                           | 3         | 1.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 1.32%   |
| Intel Centrino Wireless-N 2230                                | 3         | 1.32%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 3         | 1.32%   |
| Intel Centrino Advanced-N 6235                                | 3         | 1.32%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 3         | 1.32%   |
| Broadcom BCM43142 802.11b/g/n                                 | 3         | 1.32%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 2         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 2         | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 0.88%   |
| Intel Wireless 8260                                           | 2         | 0.88%   |
| Intel WiFi Link 5100                                          | 2         | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 2         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 105       | 64.42%  |
| Intel                            | 23        | 14.11%  |
| Qualcomm Atheros                 | 8         | 4.91%   |
| ASIX Electronics                 | 8         | 4.91%   |
| Broadcom                         | 5         | 3.07%   |
| Marvell Technology Group         | 3         | 1.84%   |
| Apple                            | 3         | 1.84%   |
| Samsung Electronics              | 2         | 1.23%   |
| Nvidia                           | 2         | 1.23%   |
| Lenovo                           | 2         | 1.23%   |
| Silicon Integrated Systems [SiS] | 1         | 0.61%   |
| Microsoft                        | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 76        | 44.71%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 15        | 8.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 7.06%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 8         | 4.71%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 3.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.35%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.76%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.18%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.18%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.18%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.18%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.18%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.18%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.18%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.18%   |
| Apple iBridge                                                                  | 2         | 1.18%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.59%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.59%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 0.59%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.59%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.59%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.59%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.59%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                            | 1         | 0.59%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.59%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.59%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.59%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.59%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.59%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.59%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.59%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.59%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 216       | 57.6%   |
| Ethernet | 157       | 41.87%  |
| Modem    | 2         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 172       | 71.37%  |
| Ethernet | 69        | 28.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 129       | 57.33%  |
| 1     | 90        | 40%     |
| 0     | 4         | 1.78%   |
| 3     | 2         | 0.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 222       | 99.11%  |
| Yes  | 2         | 0.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 63.3%   |
| Realtek Semiconductor           | 16        | 8.51%   |
| Broadcom                        | 14        | 7.45%   |
| IMC Networks                    | 13        | 6.91%   |
| Qualcomm Atheros Communications | 9         | 4.79%   |
| Apple                           | 6         | 3.19%   |
| Foxconn / Hon Hai               | 5         | 2.66%   |
| Lite-On Technology              | 4         | 2.13%   |
| Qcom                            | 1         | 0.53%   |
| Micro Star International        | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 30        | 15.96%  |
| Intel AX201 Bluetooth                                                               | 26        | 13.83%  |
| Intel AX200 Bluetooth                                                               | 25        | 13.3%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 9.57%   |
| Intel Bluetooth Device                                                              | 11        | 5.85%   |
| Realtek Bluetooth Radio                                                             | 10        | 5.32%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 3.19%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 2.66%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 2.66%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.66%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.13%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.6%    |
| Lite-On Bluetooth Device                                                            | 3         | 1.6%    |
| IMC Networks Wireless_Device                                                        | 3         | 1.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.06%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.06%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.06%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.06%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 1.06%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.06%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.06%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.06%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 1.06%   |
| Realtek CSR BS8510                                                                  | 1         | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.53%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.53%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.53%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.53%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.53%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.53%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 169       | 63.06%  |
| AMD                              | 53        | 19.78%  |
| Nvidia                           | 30        | 11.19%  |
| JMTek                            | 3         | 1.12%   |
| Apple                            | 3         | 1.12%   |
| Lenovo                           | 2         | 0.75%   |
| Texas Instruments                | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| Razer USA                        | 1         | 0.37%   |
| No brand                         | 1         | 0.37%   |
| Native Instruments               | 1         | 0.37%   |
| Generalplus Technology           | 1         | 0.37%   |
| Dell                             | 1         | 0.37%   |
| Unknown                          | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 36        | 10.94%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 26        | 7.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 18        | 5.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 4.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 3.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 3.65%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 3.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 3.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 11        | 3.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 3.04%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 2.43%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 2.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 1.82%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.52%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.52%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.52%   |
| Nvidia High Definition Audio Controller                                    | 4         | 1.22%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.22%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.22%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.91%   |
| Nvidia Audio device                                                        | 3         | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.91%   |
| Apple Audio Device                                                         | 3         | 0.91%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 0.91%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.61%   |
| JMTek USB Audio Device                                                     | 2         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 80        | 51.61%  |
| SK hynix            | 30        | 19.35%  |
| Micron Technology   | 17        | 10.97%  |
| Unknown             | 7         | 4.52%   |
| Unknown             | 4         | 2.58%   |
| Kingston            | 3         | 1.94%   |
| A-DATA Technology   | 3         | 1.94%   |
| Unknown (ABCD)      | 2         | 1.29%   |
| Ramaxel Technology  | 2         | 1.29%   |
| Unknown (899D)      | 1         | 0.65%   |
| Unknown (09D5)      | 1         | 0.65%   |
| Team                | 1         | 0.65%   |
| Silicon Power       | 1         | 0.65%   |
| Imation             | 1         | 0.65%   |
| Essencore           | 1         | 0.65%   |
| Elpida              | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 4.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 2.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 2.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.37%   |
| Unknown                                                          | 4         | 2.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.78%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 3         | 1.78%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.78%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 1.78%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.78%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.78%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.78%   |
| Samsung RAM M471A1G44AB0-CTD 8GB DDR4 2667MT/s                   | 3         | 1.78%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 1.78%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 1.18%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.18%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.18%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.18%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.18%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.18%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.18%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.18%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.18%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DDR4 2667MT/s                   | 2         | 1.18%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.18%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 2         | 1.18%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.18%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.59%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.59%   |
| Unknown RAM CL22-22-22 D4-3200 16384MB SODIMM DDR4 3200MT/s      | 1         | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 77        | 58.78%  |
| DDR3    | 26        | 19.85%  |
| LPDDR4  | 10        | 7.63%   |
| LPDDR3  | 6         | 4.58%   |
| LPDDR5  | 3         | 2.29%   |
| DDR5    | 3         | 2.29%   |
| DDR2    | 3         | 2.29%   |
| SDRAM   | 2         | 1.53%   |
| Unknown | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 103       | 77.44%  |
| Row Of Chips | 22        | 16.54%  |
| Unknown      | 5         | 3.76%   |
| DIMM         | 3         | 2.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 65        | 46.1%   |
| 4096  | 32        | 22.7%   |
| 16384 | 21        | 14.89%  |
| 2048  | 14        | 9.93%   |
| 32768 | 7         | 4.96%   |
| 1024  | 2         | 1.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 37        | 26.06%  |
| 2667    | 34        | 23.94%  |
| 1600    | 16        | 11.27%  |
| 2400    | 12        | 8.45%   |
| 2133    | 9         | 6.34%   |
| 4267    | 5         | 3.52%   |
| 3266    | 5         | 3.52%   |
| 1334    | 5         | 3.52%   |
| 4800    | 4         | 2.82%   |
| 6400    | 3         | 2.11%   |
| 1333    | 2         | 1.41%   |
| 1067    | 2         | 1.41%   |
| 8400    | 1         | 0.7%    |
| 4266    | 1         | 0.7%    |
| 4199    | 1         | 0.7%    |
| 2048    | 1         | 0.7%    |
| 1867    | 1         | 0.7%    |
| 800     | 1         | 0.7%    |
| 667     | 1         | 0.7%    |
| Unknown | 1         | 0.7%    |

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
| Chicony Electronics                    | 37        | 19.79%  |
| IMC Networks                           | 28        | 14.97%  |
| Realtek Semiconductor                  | 13        | 6.95%   |
| Microdia                               | 12        | 6.42%   |
| Acer                                   | 12        | 6.42%   |
| Silicon Motion                         | 11        | 5.88%   |
| Bison Electronics                      | 10        | 5.35%   |
| Quanta                                 | 8         | 4.28%   |
| Apple                                  | 8         | 4.28%   |
| Syntek                                 | 6         | 3.21%   |
| Shenzhen Kingcome Optoelectronic       | 6         | 3.21%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.21%   |
| Suyin                                  | 5         | 2.67%   |
| SunplusIT                              | 5         | 2.67%   |
| Luxvisions Innotech Limited            | 4         | 2.14%   |
| Sunplus Innovation Technology          | 3         | 1.6%    |
| Z-Star Microelectronics                | 2         | 1.07%   |
| Lenovo                                 | 2         | 1.07%   |
| Sunplus IT                             | 1         | 0.53%   |
| Sonix Technology                       | 1         | 0.53%   |
| Microsoft                              | 1         | 0.53%   |
| Logitech                               | 1         | 0.53%   |
| LG Electronics                         | 1         | 0.53%   |
| Goodong Industry                       | 1         | 0.53%   |
| DigiTech                               | 1         | 0.53%   |
| Cubeternet                             | 1         | 0.53%   |
| Alcor Micro                            | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 10        | 5.32%   |
| IMC Networks Integrated Camera                          | 9         | 4.79%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 8         | 4.26%   |
| Microdia Integrated_Webcam_HD                           | 7         | 3.72%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera         | 6         | 3.19%   |
| Chicony HD WebCam                                       | 6         | 3.19%   |
| Realtek LG Camera                                       | 5         | 2.66%   |
| Syntek Integrated Camera                                | 4         | 2.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 4         | 2.13%   |
| Bison HD Webcam                                         | 4         | 2.13%   |
| Suyin HP Truevision HD                                  | 3         | 1.6%    |
| SunplusIT 1080p FHD Camera                              | 3         | 1.6%    |
| Silicon Motion LG HD WebCam                             | 3         | 1.6%    |
| Quanta HP TrueVision HD Camera                          | 3         | 1.6%    |
| Chicony USB 2.0 Camera                                  | 3         | 1.6%    |
| Chicony LG Camera                                       | 3         | 1.6%    |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 1.6%    |
| Acer Lenovo EasyCamera                                  | 3         | 1.6%    |
| Acer Integrated Camera                                  | 3         | 1.6%    |
| Z-Star Webcam                                           | 2         | 1.06%   |
| SunplusIT 720p HD Camera                                | 2         | 1.06%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 2         | 1.06%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.06%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.06%   |
| Quanta LG Webcam                                        | 2         | 1.06%   |
| Microdia USB 2.0 Camera                                 | 2         | 1.06%   |
| Luxvisions Innotech Limited HP HD Camera                | 2         | 1.06%   |
| IMC Networks USB HD Webcam                              | 2         | 1.06%   |
| IMC Networks Integrated RGB Camera                      | 2         | 1.06%   |
| Chicony LG HD WebCam                                    | 2         | 1.06%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.06%   |
| Chicony HP TrueVision HD Camera                         | 2         | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.06%   |
| Bison BisonCam,NB Pro                                   | 2         | 1.06%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 2         | 1.06%   |
| Apple Built-in iSight                                   | 2         | 1.06%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.53%   |
| Syntek HP Webcam                                        | 1         | 0.53%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.53%   |
| Suyin HP TrueVision Full HD                             | 1         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 16        | 32.65%  |
| Validity Sensors                   | 9         | 18.37%  |
| Samsung Electronics                | 6         | 12.24%  |
| Upek                               | 4         | 8.16%   |
| Shenzhen Goodix Technology         | 4         | 8.16%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 6.12%   |
| STMicroelectronics                 | 2         | 4.08%   |
| LighTuning Technology              | 2         | 4.08%   |
| Elan Microelectronics              | 2         | 4.08%   |
| AuthenTec                          | 1         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 8.16%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 4         | 8.16%   |
| Samsung Fingerprint Sensor Device - 730B                        | 4         | 8.16%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 3         | 6.12%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 3         | 6.12%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 6.12%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 4.08%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 4.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 4.08%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 4.08%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 4.08%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 4.08%   |
| Samsung Fingerprint Device                                      | 2         | 4.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 4.08%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 1         | 2.04%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 2.04%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 2.04%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 2.04%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.04%   |
| Synaptics WBDI Device                                           | 1         | 2.04%   |
| Synaptics WBDI                                                  | 1         | 2.04%   |
| Synaptics UWP WBDI Device                                       | 1         | 2.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 2.04%   |
| Elan ELAN:Fingerprint                                           | 1         | 2.04%   |
| Elan ELAN:ARM-M4                                                | 1         | 2.04%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 2         | 28.57%  |
| Alcor Micro      | 2         | 28.57%  |
| Upek             | 1         | 14.29%  |
| SCM Microsystems | 1         | 14.29%  |
| O2 Micro         | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 14.29%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 14.29%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 132       | 57.64%  |
| 1     | 78        | 34.06%  |
| 2     | 14        | 6.11%   |
| 3     | 4         | 1.75%   |
| 5     | 1         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 49        | 41.18%  |
| Graphics card            | 27        | 22.69%  |
| Net/wireless             | 18        | 15.13%  |
| Multimedia controller    | 9         | 7.56%   |
| Chipcard                 | 7         | 5.88%   |
| Sound                    | 3         | 2.52%   |
| Bluetooth                | 3         | 2.52%   |
| Net/ethernet             | 2         | 1.68%   |
| Communication controller | 1         | 0.84%   |

