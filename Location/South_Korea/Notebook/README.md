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

Total: 318

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 44        | 18.88%  |
| Ubuntu 18.04       | 19        | 8.15%   |
| Ubuntu 22.04       | 18        | 7.73%   |
| Ubuntu 21.10       | 7         | 3%      |
| Gooroom            | 7         | 3%      |
| Debian 11          | 7         | 3%      |
| Arch               | 6         | 2.58%   |
| Arch Rolling       | 5         | 2.15%   |
| Linux Mint 20.3    | 4         | 1.72%   |
| Linux Mint 20.1    | 4         | 1.72%   |
| Fedora 37          | 4         | 1.72%   |
| Fedora 36          | 4         | 1.72%   |
| Fedora 32          | 4         | 1.72%   |
| Zorin 16           | 3         | 1.29%   |
| Ubuntu 19.10       | 3         | 1.29%   |
| Ubuntu 19.04       | 3         | 1.29%   |
| ROSA R11           | 3         | 1.29%   |
| OpenMandriva 4.2   | 3         | 1.29%   |
| Kubuntu 22.04      | 3         | 1.29%   |
| HamoniKR 4.0       | 3         | 1.29%   |
| Fedora 34          | 3         | 1.29%   |
| Debian 10          | 3         | 1.29%   |
| CentOS 8           | 3         | 1.29%   |
| Zorin 15           | 2         | 0.86%   |
| Ubuntu MATE 18.04  | 2         | 0.86%   |
| Ubuntu 22.10       | 2         | 0.86%   |
| SteamOS 3.4.4      | 2         | 0.86%   |
| ROSA R10           | 2         | 0.86%   |
| Pop!_OS 21.10      | 2         | 0.86%   |
| OpenMandriva 23.01 | 2         | 0.86%   |
| Manjaro 21.3.0     | 2         | 0.86%   |
| LMDE 5             | 2         | 0.86%   |
| Linux Mint 20      | 2         | 0.86%   |
| KDE neon 20.04     | 2         | 0.86%   |
| Endless 3.8.5      | 2         | 0.86%   |
| Xubuntu 20.04      | 1         | 0.43%   |
| Ubuntu Unity 18.04 | 1         | 0.43%   |
| Ubuntu Unity 16.04 | 1         | 0.43%   |
| Ubuntu 21.04       | 1         | 0.43%   |
| Ubuntu 20.10       | 1         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 96        | 42.86%  |
| Fedora       | 16        | 7.14%   |
| Linux Mint   | 13        | 5.8%    |
| Debian       | 10        | 4.46%   |
| Manjaro      | 9         | 4.02%   |
| Arch         | 9         | 4.02%   |
| OpenMandriva | 8         | 3.57%   |
| Gooroom      | 8         | 3.57%   |
| Zorin        | 5         | 2.23%   |
| ROSA         | 5         | 2.23%   |
| Kubuntu      | 5         | 2.23%   |
| Endless      | 5         | 2.23%   |
| Pop!_OS      | 4         | 1.79%   |
| No1          | 4         | 1.79%   |
| HamoniKR     | 4         | 1.79%   |
| CentOS       | 4         | 1.79%   |
| SteamOS      | 3         | 1.34%   |
| KDE neon     | 3         | 1.34%   |
| Ubuntu Unity | 2         | 0.89%   |
| Ubuntu MATE  | 2         | 0.89%   |
| LMDE         | 2         | 0.89%   |
| EndeavourOS  | 2         | 0.89%   |
| Xubuntu      | 1         | 0.45%   |
| openSUSE     | 1         | 0.45%   |
| Lubuntu      | 1         | 0.45%   |
| Gentoo       | 1         | 0.45%   |
| Garuda Linux | 1         | 0.45%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.15.0-53-generic               | 5         | 2.03%   |
| 5.10.0-19-amd64                 | 5         | 2.03%   |
| 5.4.0-42-generic                | 4         | 1.63%   |
| 5.15.0-58-generic               | 4         | 1.63%   |
| 5.10.0-17-amd64                 | 4         | 1.63%   |
| 5.4.0-58-generic                | 3         | 1.22%   |
| 5.4.0-26-generic                | 3         | 1.22%   |
| 5.3.0-40-generic                | 3         | 1.22%   |
| 5.19.15-201.fc36.x86_64         | 3         | 1.22%   |
| 5.15.0-56-generic               | 3         | 1.22%   |
| 5.13.0-28-generic               | 3         | 1.22%   |
| 5.11.0-37-generic               | 3         | 1.22%   |
| 4.19.0-9-amd64                  | 3         | 1.22%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3         | 1.22%   |
| 6.1.1-desktop-1omv2290          | 2         | 0.81%   |
| 5.8.4-200.fc32.x86_64           | 2         | 0.81%   |
| 5.8.0-53-generic                | 2         | 0.81%   |
| 5.8.0-43-generic                | 2         | 0.81%   |
| 5.4.0-81-generic                | 2         | 0.81%   |
| 5.4.0-56-generic                | 2         | 0.81%   |
| 5.4.0-48-generic                | 2         | 0.81%   |
| 5.4.0-39-generic                | 2         | 0.81%   |
| 5.4.0-33-generic                | 2         | 0.81%   |
| 5.4.0-31-generic                | 2         | 0.81%   |
| 5.4.0-29-generic                | 2         | 0.81%   |
| 5.3.0-46-generic                | 2         | 0.81%   |
| 5.18.5-1-MANJARO                | 2         | 0.81%   |
| 5.15.0-60-generic               | 2         | 0.81%   |
| 5.15.0-52-generic               | 2         | 0.81%   |
| 5.15.0-33-generic               | 2         | 0.81%   |
| 5.15.0-27-generic               | 2         | 0.81%   |
| 5.13.0-valve36-1-neptune        | 2         | 0.81%   |
| 5.13.0-44-generic               | 2         | 0.81%   |
| 5.13.0-27-generic               | 2         | 0.81%   |
| 5.10.14-desktop-1omv4002        | 2         | 0.81%   |
| 5.0.0-37-generic                | 2         | 0.81%   |
| 5.0.0-25-generic                | 2         | 0.81%   |
| 5.0.0-13-generic                | 2         | 0.81%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.81%   |
| 4.18.0-17-generic               | 2         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 46        | 19.41%  |
| 5.15.0  | 24        | 10.13%  |
| 5.13.0  | 16        | 6.75%   |
| 5.10.0  | 12        | 5.06%   |
| 5.8.0   | 11        | 4.64%   |
| 5.11.0  | 10        | 4.22%   |
| 4.15.0  | 10        | 4.22%   |
| 5.3.0   | 9         | 3.8%    |
| 5.0.0   | 7         | 2.95%   |
| 4.18.0  | 7         | 2.95%   |
| 4.19.0  | 6         | 2.53%   |
| 5.19.15 | 3         | 1.27%   |
| 6.1.1   | 2         | 0.84%   |
| 6.0.0   | 2         | 0.84%   |
| 5.8.4   | 2         | 0.84%   |
| 5.19.0  | 2         | 0.84%   |
| 5.18.5  | 2         | 0.84%   |
| 5.16.19 | 2         | 0.84%   |
| 5.15.11 | 2         | 0.84%   |
| 5.14.0  | 2         | 0.84%   |
| 5.10.14 | 2         | 0.84%   |
| 4.9.60  | 2         | 0.84%   |
| 6.2.8   | 1         | 0.42%   |
| 6.2.6   | 1         | 0.42%   |
| 6.2.5   | 1         | 0.42%   |
| 6.1.9   | 1         | 0.42%   |
| 6.1.13  | 1         | 0.42%   |
| 6.1.11  | 1         | 0.42%   |
| 6.1.10  | 1         | 0.42%   |
| 6.1.0   | 1         | 0.42%   |
| 6.0.9   | 1         | 0.42%   |
| 6.0.6   | 1         | 0.42%   |
| 6.0.2   | 1         | 0.42%   |
| 6.0.14  | 1         | 0.42%   |
| 5.9.9   | 1         | 0.42%   |
| 5.8.18  | 1         | 0.42%   |
| 5.8.15  | 1         | 0.42%   |
| 5.7.17  | 1         | 0.42%   |
| 5.6.11  | 1         | 0.42%   |
| 5.6.0   | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 48        | 20.34%  |
| 5.15    | 32        | 13.56%  |
| 5.13    | 17        | 7.2%    |
| 5.10    | 16        | 6.78%   |
| 5.8     | 15        | 6.36%   |
| 5.11    | 15        | 6.36%   |
| 4.15    | 11        | 4.66%   |
| 5.3     | 10        | 4.24%   |
| 4.18    | 8         | 3.39%   |
| 6.1     | 7         | 2.97%   |
| 5.0     | 7         | 2.97%   |
| 4.19    | 7         | 2.97%   |
| 6.0     | 6         | 2.54%   |
| 5.19    | 6         | 2.54%   |
| 5.16    | 5         | 2.12%   |
| 5.12    | 5         | 2.12%   |
| 5.14    | 4         | 1.69%   |
| 6.2     | 3         | 1.27%   |
| 5.18    | 3         | 1.27%   |
| 5.6     | 2         | 0.85%   |
| 4.9     | 2         | 0.85%   |
| 5.9     | 1         | 0.42%   |
| 5.7     | 1         | 0.42%   |
| 5.5     | 1         | 0.42%   |
| 5.2     | 1         | 0.42%   |
| 5.17    | 1         | 0.42%   |
| 4.16    | 1         | 0.42%   |
| 3.10    | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 214       | 98.17%  |
| i686    | 3         | 1.38%   |
| aarch64 | 1         | 0.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 119       | 53.13%  |
| KDE5            | 33        | 14.73%  |
| Unknown         | 17        | 7.59%   |
| X-Cinnamon      | 12        | 5.36%   |
| LXDE            | 8         | 3.57%   |
| GNOME Flashback | 8         | 3.57%   |
| XFCE            | 7         | 3.13%   |
| Cinnamon        | 6         | 2.68%   |
| KDE4            | 3         | 1.34%   |
| KDE             | 3         | 1.34%   |
| i3              | 3         | 1.34%   |
| Unity           | 2         | 0.89%   |
| MATE            | 2         | 0.89%   |
| sway            | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 155       | 70.45%  |
| Wayland | 44        | 20%     |
| Unknown | 13        | 5.91%   |
| Tty     | 8         | 3.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 105       | 46.67%  |
| GDM     | 43        | 19.11%  |
| SDDM    | 25        | 11.11%  |
| GDM3    | 20        | 8.89%   |
| LightDM | 15        | 6.67%   |
| TDM     | 13        | 5.78%   |
| KDM     | 3         | 1.33%   |
| XDM     | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ko_KR   | 99        | 44.2%   |
| en_US   | 81        | 36.16%  |
| Unknown | 26        | 11.61%  |
| en_CA   | 4         | 1.79%   |
| zh_CN   | 3         | 1.34%   |
| C       | 3         | 1.34%   |
| id_ID   | 2         | 0.89%   |
| vi_VN   | 1         | 0.45%   |
| pt_BR   | 1         | 0.45%   |
| fr_FR   | 1         | 0.45%   |
| en_NZ   | 1         | 0.45%   |
| el_GR   | 1         | 0.45%   |
| ar_EG   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 151       | 68.95%  |
| BIOS | 68        | 31.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 180       | 81.45%  |
| Btrfs   | 19        | 8.6%    |
| Xfs     | 6         | 2.71%   |
| Overlay | 6         | 2.71%   |
| Unknown | 6         | 2.71%   |
| Zfs     | 3         | 1.36%   |
| Rootfs  | 1         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 106       | 47.75%  |
| Unknown | 101       | 45.5%   |
| MBR     | 15        | 6.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 206       | 94.06%  |
| Yes       | 13        | 5.94%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 149       | 67.42%  |
| Yes       | 72        | 32.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 47        | 21.56%  |
| Samsung Electronics | 28        | 12.84%  |
| Hewlett-Packard     | 25        | 11.47%  |
| LG Electronics      | 21        | 9.63%   |
| ASUSTek Computer    | 21        | 9.63%   |
| Dell                | 15        | 6.88%   |
| MSI                 | 11        | 5.05%   |
| Apple               | 10        | 4.59%   |
| Notebook            | 4         | 1.83%   |
| HANSUNG COMPUTER    | 4         | 1.83%   |
| Valve               | 3         | 1.38%   |
| Acer                | 3         | 1.38%   |
| Toshiba             | 2         | 0.92%   |
| Razer               | 2         | 0.92%   |
| Google              | 2         | 0.92%   |
| Gigabyte Technology | 2         | 0.92%   |
| Wolfnfox            | 1         | 0.46%   |
| WEIPAI              | 1         | 0.46%   |
| TG                  | 1         | 0.46%   |
| Teclast             | 1         | 0.46%   |
| Sony                | 1         | 0.46%   |
| SLIMBOOK            | 1         | 0.46%   |
| Pine Microsystems   | 1         | 0.46%   |
| MS                  | 1         | 0.46%   |
| MECHREVO            | 1         | 0.46%   |
| Jooyontech Computer | 1         | 0.46%   |
| Jooyon Tech         | 1         | 0.46%   |
| Intel               | 1         | 0.46%   |
| IMUZ                | 1         | 0.46%   |
| Clevo               | 1         | 0.46%   |
| AVERATEC            | 1         | 0.46%   |
| AMI                 | 1         | 0.46%   |
| Alienware           | 1         | 0.46%   |
| Unknown             | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Valve Jupiter                                     | 3         | 1.38%   |
| Samsung 950XED                                    | 3         | 1.38%   |
| Samsung 950XCJ/951XCJ/950XCR                      | 3         | 1.38%   |
| Samsung 760XDA                                    | 2         | 0.92%   |
| Razer Blade 17 (2022) - RZ09-0423                 | 2         | 0.92%   |
| Notebook N650DU                                   | 2         | 0.92%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01S00              | 2         | 0.92%   |
| Lenovo IdeaPad 3 15IIL05 81WE                     | 2         | 0.92%   |
| HP Stream Notebook PC 13                          | 2         | 0.92%   |
| HP Laptop 15-db1xxx                               | 2         | 0.92%   |
| HP EliteBook 855 G7 Notebook PC                   | 2         | 0.92%   |
| HANSUNG COMPUTER TFX5470H                         | 2         | 0.92%   |
| Dell XPS 15 7590                                  | 2         | 0.92%   |
| Dell Inspiron 15 5510                             | 2         | 0.92%   |
| Apple MacBookPro16,1                              | 2         | 0.92%   |
| Wolfnfox WF-TBAT                                  | 1         | 0.46%   |
| WEIPAI S15                                        | 1         | 0.46%   |
| Toshiba Satellite P50-B-103                       | 1         | 0.46%   |
| Toshiba Satellite L655                            | 1         | 0.46%   |
| TG NXI-A7000 Series                               | 1         | 0.46%   |
| Teclast tPAD                                      | 1         | 0.46%   |
| Sony VPCEA36FK                                    | 1         | 0.46%   |
| SLIMBOOK PROX15-AMD                               | 1         | 0.46%   |
| Samsung X120/X170/X171                            | 1         | 0.46%   |
| Samsung SX11S                                     | 1         | 0.46%   |
| Samsung RC420/RC520/RC720                         | 1         | 0.46%   |
| Samsung R59P/R60P/R61P                            | 1         | 0.46%   |
| Samsung R440/R480                                 | 1         | 0.46%   |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.46%   |
| Samsung 940XFG                                    | 1         | 0.46%   |
| Samsung 905S3G/906S3G/915S3G                      | 1         | 0.46%   |
| Samsung 900X5N                                    | 1         | 0.46%   |
| Samsung 800G5M/800G5W                             | 1         | 0.46%   |
| Samsung 760XBE                                    | 1         | 0.46%   |
| Samsung 730QCJ/730QCR                             | 1         | 0.46%   |
| Samsung 670Z5E                                    | 1         | 0.46%   |
| Samsung 570Z5E/580Z5E                             | 1         | 0.46%   |
| Samsung 550XED                                    | 1         | 0.46%   |
| Samsung 530U3BI/530U4BI/530U4BH                   | 1         | 0.46%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 31        | 14.22%  |
| Lenovo IdeaPad            | 11        | 5.05%   |
| ASUS VivoBook             | 8         | 3.67%   |
| HP Pavilion               | 7         | 3.21%   |
| HP Laptop                 | 5         | 2.29%   |
| HP EliteBook              | 5         | 2.29%   |
| Dell Inspiron             | 5         | 2.29%   |
| Dell XPS                  | 4         | 1.83%   |
| Valve Jupiter             | 3         | 1.38%   |
| Samsung 950XED            | 3         | 1.38%   |
| Samsung 950XCJ            | 3         | 1.38%   |
| HP Stream                 | 3         | 1.38%   |
| Dell Latitude             | 3         | 1.38%   |
| Toshiba Satellite         | 2         | 0.92%   |
| Samsung 760XDA            | 2         | 0.92%   |
| Razer Blade               | 2         | 0.92%   |
| Notebook N650DU           | 2         | 0.92%   |
| MSI Prestige              | 2         | 0.92%   |
| HP ProBook                | 2         | 0.92%   |
| HANSUNG COMPUTER TFX5470H | 2         | 0.92%   |
| ASUS TUF                  | 2         | 0.92%   |
| ASUS ROG                  | 2         | 0.92%   |
| Apple MacBookPro5         | 2         | 0.92%   |
| Apple MacBookPro16        | 2         | 0.92%   |
| Acer Swift                | 2         | 0.92%   |
| Wolfnfox WF-TBAT          | 1         | 0.46%   |
| WEIPAI S15                | 1         | 0.46%   |
| TG NXI-A7000              | 1         | 0.46%   |
| Teclast tPAD              | 1         | 0.46%   |
| Sony VPCEA36FK            | 1         | 0.46%   |
| SLIMBOOK PROX15-AMD       | 1         | 0.46%   |
| Samsung X120              | 1         | 0.46%   |
| Samsung SX11S             | 1         | 0.46%   |
| Samsung RC420             | 1         | 0.46%   |
| Samsung R59P              | 1         | 0.46%   |
| Samsung R440              | 1         | 0.46%   |
| Samsung 950XDB            | 1         | 0.46%   |
| Samsung 940XFG            | 1         | 0.46%   |
| Samsung 905S3G            | 1         | 0.46%   |
| Samsung 900X5N            | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 43        | 19.72%  |
| 2021    | 26        | 11.93%  |
| 2019    | 22        | 10.09%  |
| 2018    | 18        | 8.26%   |
| 2022    | 17        | 7.8%    |
| 2014    | 15        | 6.88%   |
| 2013    | 15        | 6.88%   |
| 2011    | 11        | 5.05%   |
| 2016    | 8         | 3.67%   |
| 2010    | 8         | 3.67%   |
| 2017    | 7         | 3.21%   |
| 2008    | 7         | 3.21%   |
| 2012    | 6         | 2.75%   |
| 2015    | 5         | 2.29%   |
| 2009    | 4         | 1.83%   |
| 2007    | 3         | 1.38%   |
| 2006    | 2         | 0.92%   |
| Unknown | 1         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 218       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 197       | 89.55%  |
| Enabled  | 23        | 10.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 216       | 99.08%  |
| Yes  | 2         | 0.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 57        | 25.79%  |
| 16.01-24.0  | 45        | 20.36%  |
| 8.01-16.0   | 39        | 17.65%  |
| 3.01-4.0    | 35        | 15.84%  |
| 32.01-64.0  | 20        | 9.05%   |
| 1.01-2.0    | 13        | 5.88%   |
| 64.01-256.0 | 8         | 3.62%   |
| 24.01-32.0  | 3         | 1.36%   |
| 2.01-3.0    | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 73        | 30.67%  |
| 2.01-3.0   | 59        | 24.79%  |
| 4.01-8.0   | 37        | 15.55%  |
| 3.01-4.0   | 36        | 15.13%  |
| 0.51-1.0   | 17        | 7.14%   |
| 8.01-16.0  | 11        | 4.62%   |
| 16.01-24.0 | 3         | 1.26%   |
| 24.01-32.0 | 1         | 0.42%   |
| 0.01-0.5   | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 140       | 62.5%   |
| 2      | 72        | 32.14%  |
| 3      | 9         | 4.02%   |
| 4      | 2         | 0.89%   |
| 0      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 185       | 84.86%  |
| Yes       | 33        | 15.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 69.55%  |
| No        | 67        | 30.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 210       | 95.89%  |
| No        | 9         | 4.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 82.73%  |
| No        | 38        | 17.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| South Korea | 218       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Seoul         | 37        | 16.16%  |
| Seocho-gu     | 13        | 5.68%   |
| Suwon         | 10        | 4.37%   |
| Gwanak-gu     | 8         | 3.49%   |
| Uiwang        | 7         | 3.06%   |
| Seongnam-si   | 6         | 2.62%   |
| Jung-gu       | 6         | 2.62%   |
| Hwaseong-si   | 6         | 2.62%   |
| Yongin-si     | 5         | 2.18%   |
| Seongbuk-gu   | 5         | 2.18%   |
| Yongsan-gu    | 4         | 1.75%   |
| Mapo-gu       | 4         | 1.75%   |
| Incheon       | 4         | 1.75%   |
| Daejeon       | 4         | 1.75%   |
| Daegu         | 4         | 1.75%   |
| Busan         | 4         | 1.75%   |
| Bupyeong-gu   | 4         | 1.75%   |
| Anyang-si     | 4         | 1.75%   |
| Pyeongtaek-si | 3         | 1.31%   |
| Nam-gu        | 3         | 1.31%   |
| Jeonju        | 3         | 1.31%   |
| Gwangju       | 3         | 1.31%   |
| Geumjeong-gu  | 3         | 1.31%   |
| Gangseo-gu    | 3         | 1.31%   |
| Gangnam-gu    | 3         | 1.31%   |
| Yuseong-gu    | 2         | 0.87%   |
| Yongsan-dong  | 2         | 0.87%   |
| Yeonsu-gu     | 2         | 0.87%   |
| Songpa-gu     | 2         | 0.87%   |
| Siheung-si    | 2         | 0.87%   |
| Seo-gu        | 2         | 0.87%   |
| Namdong-gu    | 2         | 0.87%   |
| Jeju City     | 2         | 0.87%   |
| Gyeongsan-si  | 2         | 0.87%   |
| Goyang-si     | 2         | 0.87%   |
| Gimpo-si      | 2         | 0.87%   |
| Danyang-gun   | 2         | 0.87%   |
| Cheongju-si   | 2         | 0.87%   |
| Changwon      | 2         | 0.87%   |
| Buk-gu        | 2         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 77        | 94     | 26.37%  |
| WDC                            | 31        | 33     | 10.62%  |
| Unknown                        | 20        | 24     | 6.85%   |
| SK hynix                       | 20        | 27     | 6.85%   |
| SanDisk                        | 20        | 20     | 6.85%   |
| Seagate                        | 15        | 19     | 5.14%   |
| Toshiba                        | 13        | 15     | 4.45%   |
| Crucial                        | 12        | 13     | 4.11%   |
| Kingston                       | 8         | 10     | 2.74%   |
| Intel                          | 8         | 13     | 2.74%   |
| Apple                          | 6         | 7      | 2.05%   |
| Phison                         | 5         | 6      | 1.71%   |
| Hitachi                        | 5         | 6      | 1.71%   |
| A-DATA Technology              | 5         | 5      | 1.71%   |
| Micron Technology              | 4         | 5      | 1.37%   |
| Team                           | 3         | 3      | 1.03%   |
| TAMMUZ                         | 3         | 5      | 1.03%   |
| Silicon Motion                 | 3         | 3      | 1.03%   |
| HGST                           | 3         | 4      | 1.03%   |
| UMIS                           | 2         | 2      | 0.68%   |
| KIOXIA                         | 2         | 2      | 0.68%   |
| JMicron Technology             | 2         | 2      | 0.68%   |
| Fujitsu                        | 2         | 2      | 0.68%   |
| ZTC                            | 1         | 1      | 0.34%   |
| XPG                            | 1         | 2      | 0.34%   |
| VIVA300s                       | 1         | 1      | 0.34%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.34%   |
| TYPEC 1T                       | 1         | 1      | 0.34%   |
| Transcend                      | 1         | 2      | 0.34%   |
| T-FORCE                        | 1         | 1      | 0.34%   |
| Solid State Storage Technology | 1         | 1      | 0.34%   |
| RevuAhn                        | 1         | 1      | 0.34%   |
| Plextor                        | 1         | 1      | 0.34%   |
| Phison Electronics             | 1         | 1      | 0.34%   |
| O2 Micro                       | 1         | 1      | 0.34%   |
| LITEONIT                       | 1         | 1      | 0.34%   |
| LITEON                         | 1         | 1      | 0.34%   |
| KingSpec                       | 1         | 1      | 0.34%   |
| ipTIME                         | 1         | 1      | 0.34%   |
| IPLEX                          | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix SHGP31-1000GM-2 1TB                           | 4         | 1.29%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 3         | 0.97%   |
| Samsung SSD 980 PRO 2TB                                | 3         | 0.97%   |
| Samsung SSD 860 EVO 500GB                              | 3         | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB     | 3         | 0.97%   |
| Samsung MZVL21T0HCLR-00B00 1TB                         | 3         | 0.97%   |
| WDC WDS100T2B0C-00PXH0 1TB                             | 2         | 0.65%   |
| WDC WD50 00LPVX-22V0TT0 500GB                          | 2         | 0.65%   |
| Unknown SLD64G  64GB                                   | 2         | 0.65%   |
| Unknown SD/MMC/MS PRO 64GB                             | 2         | 0.65%   |
| Unknown MMC Card  512GB                                | 2         | 0.65%   |
| Unknown MMC Card  32GB                                 | 2         | 0.65%   |
| Unknown MMC Card  256GB                                | 2         | 0.65%   |
| Toshiba KBG30ZMV256G 256GB                             | 2         | 0.65%   |
| SK hynix SHGP31-1000GM 1TB                             | 2         | 0.65%   |
| SK hynix NVMe SSD Drive 256GB                          | 2         | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1024GB | 2         | 0.65%   |
| Seagate ST1000LM048-2E7172 1TB                         | 2         | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB                         | 2         | 0.65%   |
| Seagate Expansion+ 2TB                                 | 2         | 0.65%   |
| SanDisk SD8SBAT256G1122 256GB SSD                      | 2         | 0.65%   |
| SanDisk NVMe SSD Drive 512GB                           | 2         | 0.65%   |
| SanDisk NVMe SSD Drive 256GB                           | 2         | 0.65%   |
| Samsung SSD 860 EVO 1TB                                | 2         | 0.65%   |
| Samsung SSD 830 Series 256GB                           | 2         | 0.65%   |
| Samsung SSD 750 EVO 120GB                              | 2         | 0.65%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB                 | 2         | 0.65%   |
| Samsung PSSD T7 2TB                                    | 2         | 0.65%   |
| Samsung NVMe SSD Drive 2TB                             | 2         | 0.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB    | 2         | 0.65%   |
| Samsung MZVLQ1T0HBLB-00B 1TB                           | 2         | 0.65%   |
| Samsung MZVLB512HAJQ-00000 512GB                       | 2         | 0.65%   |
| Samsung MZVLB256HBHQ-000 256GB                         | 2         | 0.65%   |
| Samsung MZNLN256HAJQ-00000 256GB SSD                   | 2         | 0.65%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD                   | 2         | 0.65%   |
| Kingston OM8PCP3512F-AB 512GB                          | 2         | 0.65%   |
| JMicron Tech 250GB                                     | 2         | 0.65%   |
| Intel SSDPEKNU512GZ 512GB                              | 2         | 0.65%   |
| HGST HTS721010A9E630 1TB                               | 2         | 0.65%   |
| Crucial CT500MX500SSD1 500GB                           | 2         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 14     | 29.17%  |
| Seagate             | 14        | 18     | 29.17%  |
| Toshiba             | 6         | 6      | 12.5%   |
| Hitachi             | 5         | 6      | 10.42%  |
| HGST                | 3         | 4      | 6.25%   |
| Unknown             | 2         | 2      | 4.17%   |
| Fujitsu             | 2         | 2      | 4.17%   |
| Samsung Electronics | 1         | 1      | 2.08%   |
| ipTIME              | 1         | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 45     | 37.62%  |
| SanDisk             | 11        | 11     | 10.89%  |
| Crucial             | 11        | 12     | 10.89%  |
| SK hynix            | 5         | 6      | 4.95%   |
| WDC                 | 4         | 5      | 3.96%   |
| TAMMUZ              | 3         | 5      | 2.97%   |
| Micron Technology   | 3         | 4      | 2.97%   |
| Kingston            | 3         | 4      | 2.97%   |
| Intel               | 3         | 4      | 2.97%   |
| Team                | 2         | 2      | 1.98%   |
| Apple               | 2         | 2      | 1.98%   |
| A-DATA Technology   | 2         | 2      | 1.98%   |
| ZTC                 | 1         | 1      | 0.99%   |
| TYPEC 1T            | 1         | 1      | 0.99%   |
| Transcend           | 1         | 2      | 0.99%   |
| Toshiba             | 1         | 1      | 0.99%   |
| T-FORCE             | 1         | 1      | 0.99%   |
| RevuAhn             | 1         | 1      | 0.99%   |
| Plextor             | 1         | 1      | 0.99%   |
| LITEONIT            | 1         | 1      | 0.99%   |
| LITEON              | 1         | 1      | 0.99%   |
| KingSpec            | 1         | 1      | 0.99%   |
| IPLEX               | 1         | 1      | 0.99%   |
| China               | 1         | 1      | 0.99%   |
| Biostar             | 1         | 1      | 0.99%   |
| Apacer              | 1         | 1      | 0.99%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 109       | 145    | 39.64%  |
| SSD     | 94        | 117    | 34.18%  |
| HDD     | 48        | 54     | 17.45%  |
| MMC     | 18        | 22     | 6.55%   |
| Unknown | 6         | 7      | 2.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 116       | 160    | 44.79%  |
| NVMe | 109       | 143    | 42.08%  |
| MMC  | 18        | 22     | 6.95%   |
| SAS  | 16        | 20     | 6.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 96        | 120    | 70.07%  |
| 0.51-1.0   | 36        | 40     | 26.28%  |
| 1.01-2.0   | 4         | 10     | 2.92%   |
| 3.01-4.0   | 1         | 1      | 0.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 83        | 36.4%   |
| 251-500        | 46        | 20.18%  |
| 501-1000       | 29        | 12.72%  |
| 1001-2000      | 22        | 9.65%   |
| 51-100         | 19        | 8.33%   |
| 21-50          | 10        | 4.39%   |
| 1-20           | 9         | 3.95%   |
| More than 3000 | 6         | 2.63%   |
| 2001-3000      | 3         | 1.32%   |
| Unknown        | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 95        | 40.6%   |
| 21-50          | 50        | 21.37%  |
| 101-250        | 31        | 13.25%  |
| 51-100         | 20        | 8.55%   |
| 251-500        | 18        | 7.69%   |
| 501-1000       | 11        | 4.7%    |
| 1001-2000      | 6         | 2.56%   |
| More than 3000 | 1         | 0.43%   |
| 2001-3000      | 1         | 0.43%   |
| Unknown        | 1         | 0.43%   |

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
| Detected | 126       | 189    | 52.72%  |
| Works    | 99        | 142    | 41.42%  |
| Malfunc  | 14        | 14     | 5.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 120       | 45.8%   |
| Samsung Electronics              | 38        | 14.5%   |
| AMD                              | 26        | 9.92%   |
| SanDisk                          | 21        | 8.02%   |
| SK hynix                         | 14        | 5.34%   |
| Phison Electronics               | 8         | 3.05%   |
| Toshiba America Info Systems     | 6         | 2.29%   |
| Kingston Technology Company      | 5         | 1.91%   |
| Silicon Motion                   | 4         | 1.53%   |
| Apple                            | 4         | 1.53%   |
| Union Memory (Shenzhen)          | 3         | 1.15%   |
| ADATA Technology                 | 3         | 1.15%   |
| Nvidia                           | 2         | 0.76%   |
| KIOXIA                           | 2         | 0.76%   |
| Solid State Storage Technology   | 1         | 0.38%   |
| Silicon Integrated Systems [SiS] | 1         | 0.38%   |
| O2 Micro                         | 1         | 0.38%   |
| Micron/Crucial Technology        | 1         | 0.38%   |
| Micron Technology                | 1         | 0.38%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24        | 8.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 5.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 4.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 3.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 3.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 3.68%   |
| Samsung NVMe SSD Controller 980                                                | 8         | 2.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 2.94%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 6         | 2.21%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 6         | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 2.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 2.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 1.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.47%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 1.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.1%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 1.1%    |
| SK hynix Non-Volatile memory controller                                        | 3         | 1.1%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 1.1%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.1%    |
| SanDisk PC SN520 NVMe SSD                                                      | 3         | 1.1%    |
| Sandisk Non-Volatile memory controller                                         | 3         | 1.1%    |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 1.1%    |
| Phison E12 NVMe Controller                                                     | 3         | 1.1%    |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.1%    |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.1%    |
| Intel SSD 660P Series                                                          | 3         | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.1%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.1%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.1%    |
| Apple ANS2 NVMe Controller                                                     | 3         | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 132       | 50.77%  |
| NVMe | 109       | 41.92%  |
| RAID | 11        | 4.23%   |
| IDE  | 8         | 3.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 172       | 78.9%   |
| AMD    | 45        | 20.64%  |
| ARM    | 1         | 0.46%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 2.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 2.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.29%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 2.29%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.83%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 1.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.83%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.83%   |
| Intel 12th Gen Core i5-1240P                  | 4         | 1.83%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 4         | 1.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.38%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.38%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.38%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.38%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.38%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 1.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.38%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 1.38%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.38%   |
| AMD Custom APU 0405                           | 3         | 1.38%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 0.92%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 2         | 0.92%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 0.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.92%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.92%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 0.92%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.92%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 2         | 0.92%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.92%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.92%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 0.92%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.92%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.92%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.92%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 0.92%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.92%   |
| Intel 12th Gen Core i9-12900H                 | 2         | 0.92%   |
| Intel 11th Gen Core i7-11600H @ 2.90GHz       | 2         | 0.92%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.92%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 48        | 22.02%  |
| Intel Core i5        | 45        | 20.64%  |
| Other                | 31        | 14.22%  |
| Intel Core i3        | 13        | 5.96%   |
| AMD Ryzen 5          | 13        | 5.96%   |
| AMD Ryzen 7          | 11        | 5.05%   |
| Intel Core 2 Duo     | 8         | 3.67%   |
| Intel Celeron        | 8         | 3.67%   |
| Intel Pentium        | 6         | 2.75%   |
| Intel Core i9        | 4         | 1.83%   |
| Intel Atom           | 4         | 1.83%   |
| AMD Ryzen 7 PRO      | 4         | 1.83%   |
| AMD Ryzen 3          | 3         | 1.38%   |
| Intel Pentium Silver | 2         | 0.92%   |
| Intel Genuine        | 2         | 0.92%   |
| Intel Core 2         | 2         | 0.92%   |
| AMD Ryzen 9          | 2         | 0.92%   |
| AMD Ryzen 5 PRO      | 2         | 0.92%   |
| AMD A4               | 2         | 0.92%   |
| AMD A10              | 2         | 0.92%   |
| Intel Xeon           | 1         | 0.46%   |
| Intel Pentium Dual   | 1         | 0.46%   |
| Intel Core m3        | 1         | 0.46%   |
| AMD Quad-Core        | 1         | 0.46%   |
| AMD Athlon II        | 1         | 0.46%   |
| AMD A6               | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 84        | 38.53%  |
| 4       | 77        | 35.32%  |
| 8       | 23        | 10.55%  |
| 6       | 22        | 10.09%  |
| 12      | 7         | 3.21%   |
| 14      | 3         | 1.38%   |
| 1       | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 217       | 99.54%  |
| 2      | 1         | 0.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 180       | 82.57%  |
| 1       | 37        | 16.97%  |
| Unknown | 1         | 0.46%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 214       | 98.17%  |
| Unknown        | 2         | 0.92%   |
| 64-bit         | 1         | 0.46%   |
| 32-bit         | 1         | 0.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 14.73%  |
| 0x806ec    | 13        | 5.8%    |
| 0x806c1    | 13        | 5.8%    |
| 0x306a9    | 11        | 4.91%   |
| 0x806ea    | 9         | 4.02%   |
| 0x206a7    | 9         | 4.02%   |
| 0x906a3    | 8         | 3.57%   |
| 0x20655    | 8         | 3.57%   |
| 0x0a50000c | 8         | 3.57%   |
| 0x08600106 | 7         | 3.13%   |
| 0x806eb    | 6         | 2.68%   |
| 0x40651    | 6         | 2.68%   |
| 0x906e9    | 5         | 2.23%   |
| 0x706e5    | 5         | 2.23%   |
| 0x08108102 | 5         | 2.23%   |
| 0xa0652    | 4         | 1.79%   |
| 0x906ea    | 4         | 1.79%   |
| 0x806e9    | 4         | 1.79%   |
| 0x706a1    | 4         | 1.79%   |
| 0x306d4    | 4         | 1.79%   |
| 0x306c3    | 4         | 1.79%   |
| 0x30678    | 4         | 1.79%   |
| 0x906ed    | 3         | 1.34%   |
| 0x806d1    | 3         | 1.34%   |
| 0x6fd      | 3         | 1.34%   |
| 0x406e3    | 3         | 1.34%   |
| 0x1067a    | 3         | 1.34%   |
| 0xa0660    | 2         | 0.89%   |
| 0x6f6      | 2         | 0.89%   |
| 0x406c3    | 2         | 0.89%   |
| 0x20652    | 2         | 0.89%   |
| 0x10676    | 2         | 0.89%   |
| 0x08608103 | 2         | 0.89%   |
| 0x08600103 | 2         | 0.89%   |
| 0x0700010f | 2         | 0.89%   |
| 0x06001119 | 2         | 0.89%   |
| 0xb06a2    | 1         | 0.45%   |
| 0x906a2    | 1         | 0.45%   |
| 0x706a8    | 1         | 0.45%   |
| 0x6fb      | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 49        | 22.48%  |
| Haswell          | 15        | 6.88%   |
| Zen 2            | 14        | 6.42%   |
| TigerLake        | 14        | 6.42%   |
| Westmere         | 11        | 5.05%   |
| IvyBridge        | 11        | 5.05%   |
| Unknown          | 11        | 5.05%   |
| Zen 3            | 10        | 4.59%   |
| SandyBridge      | 10        | 4.59%   |
| IceLake          | 9         | 4.13%   |
| Silvermont       | 7         | 3.21%   |
| Zen+             | 6         | 2.75%   |
| Skylake          | 6         | 2.75%   |
| Penryn           | 6         | 2.75%   |
| Core             | 6         | 2.75%   |
| CometLake        | 6         | 2.75%   |
| Alderlake Hybrid | 6         | 2.75%   |
| Goldmont plus    | 5         | 2.29%   |
| Broadwell        | 4         | 1.83%   |
| Jaguar           | 3         | 1.38%   |
| Zen              | 2         | 0.92%   |
| Piledriver       | 2         | 0.92%   |
| P6               | 1         | 0.46%   |
| Nehalem          | 1         | 0.46%   |
| K10              | 1         | 0.46%   |
| Excavator        | 1         | 0.46%   |
| Bonnell          | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 155       | 57.2%   |
| Nvidia                           | 60        | 22.14%  |
| AMD                              | 55        | 20.3%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 14        | 5.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 4.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 3.23%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 3.23%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 9         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.15%   |
| AMD Barcelo                                                                              | 5         | 1.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.43%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.43%   |
| Intel HD Graphics 630                                                                    | 4         | 1.43%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.43%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.08%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 1.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.08%   |
| Intel HD Graphics 620                                                                    | 3         | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.08%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 3         | 1.08%   |
| Nvidia TU117M                                                                            | 2         | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.72%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.72%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                               | 2         | 0.72%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.72%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.72%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 105       | 48.17%  |
| Intel + Nvidia | 43        | 19.72%  |
| 1 x AMD        | 42        | 19.27%  |
| 1 x Nvidia     | 12        | 5.5%    |
| Intel + AMD    | 6         | 2.75%   |
| AMD + Nvidia   | 4         | 1.83%   |
| 2 x AMD        | 3         | 1.38%   |
| Other          | 1         | 0.46%   |
| 2 x Nvidia     | 1         | 0.46%   |
| 1 x SiS        | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 178       | 80.91%  |
| Proprietary | 31        | 14.09%  |
| Unknown     | 11        | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 137       | 61.71%  |
| 0.01-0.5   | 27        | 12.16%  |
| 1.01-2.0   | 20        | 9.01%   |
| 3.01-4.0   | 18        | 8.11%   |
| 0.51-1.0   | 11        | 4.95%   |
| 5.01-6.0   | 4         | 1.8%    |
| 7.01-8.0   | 3         | 1.35%   |
| 8.01-16.0  | 2         | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 44        | 17.67%  |
| AU Optronics            | 40        | 16.06%  |
| BOE                     | 31        | 12.45%  |
| Samsung Electronics     | 29        | 11.65%  |
| Chimei Innolux          | 26        | 10.44%  |
| Goldstar                | 10        | 4.02%   |
| Apple                   | 9         | 3.61%   |
| Sharp                   | 8         | 3.21%   |
| Dell                    | 8         | 3.21%   |
| PANDA                   | 5         | 2.01%   |
| Lenovo                  | 5         | 2.01%   |
| Valve                   | 3         | 1.2%    |
| Philips                 | 3         | 1.2%    |
| JCH                     | 3         | 1.2%    |
| CPT                     | 3         | 1.2%    |
| ALP                     | 3         | 1.2%    |
| CSO                     | 2         | 0.8%    |
| Chi Mei Optoelectronics | 2         | 0.8%    |
| BenQ                    | 2         | 0.8%    |
| VMO                     | 1         | 0.4%    |
| TMX                     | 1         | 0.4%    |
| Sony                    | 1         | 0.4%    |
| PRISM+                  | 1         | 0.4%    |
| MSI                     | 1         | 0.4%    |
| InfoVision              | 1         | 0.4%    |
| HKC                     | 1         | 0.4%    |
| Hewlett-Packard         | 1         | 0.4%    |
| HannStar                | 1         | 0.4%    |
| Denver                  | 1         | 0.4%    |
| CM_                     | 1         | 0.4%    |
| AOC                     | 1         | 0.4%    |
| Ancor Communications    | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 4         | 1.58%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 1.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.58%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 3         | 1.19%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 1.19%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 1.19%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 1.19%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.79%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 2         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 2         | 0.79%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch               | 2         | 0.79%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 2         | 0.79%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 2         | 0.79%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch          | 2         | 0.79%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch          | 2         | 0.79%   |
| LG Display LCD Monitor LGD03B5 1920x1080 294x165mm 13.3-inch          | 2         | 0.79%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.79%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 2         | 0.79%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                 | 2         | 0.79%   |
| BOE LCD Monitor BOE06D7 3840x2160 345x194mm 15.6-inch                 | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO749D 3840x2160 381x214mm 17.2-inch        | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO6A92 1920x1080 344x194mm 15.5-inch        | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.79%   |
| AU Optronics LCD Monitor 1920x1080                                    | 2         | 0.79%   |
| Apple Color LCD APPA044 3072x1920 345x215mm 16.0-inch                 | 2         | 0.79%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch             | 1         | 0.4%    |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.4%    |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.4%    |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.4%    |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 122       | 51.48%  |
| 1366x768 (WXGA)    | 37        | 15.61%  |
| 3840x2160 (4K)     | 16        | 6.75%   |
| 2560x1600          | 9         | 3.8%    |
| 2560x1440 (QHD)    | 8         | 3.38%   |
| 1600x900 (HD+)     | 7         | 2.95%   |
| 1280x800 (WXGA)    | 7         | 2.95%   |
| 1920x1200 (WUXGA)  | 6         | 2.53%   |
| 2880x1800          | 5         | 2.11%   |
| 800x1280           | 3         | 1.27%   |
| 3440x1440          | 3         | 1.27%   |
| 1440x900 (WXGA+)   | 3         | 1.27%   |
| 3072x1920          | 2         | 0.84%   |
| 1680x1050 (WSXGA+) | 2         | 0.84%   |
| 1280x1024 (SXGA)   | 2         | 0.84%   |
| 3840x2400          | 1         | 0.42%   |
| 2560x1080          | 1         | 0.42%   |
| 1680x945           | 1         | 0.42%   |
| 1400x1050          | 1         | 0.42%   |
| 1024x768 (XGA)     | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 105       | 42%     |
| 13      | 36        | 14.4%   |
| 14      | 28        | 11.2%   |
| 27      | 11        | 4.4%    |
| 17      | 11        | 4.4%    |
| 24      | 10        | 4%      |
| 16      | 8         | 3.2%    |
| 23      | 7         | 2.8%    |
| 31      | 4         | 1.6%    |
| 21      | 4         | 1.6%    |
| 12      | 4         | 1.6%    |
| 34      | 3         | 1.2%    |
| 20      | 3         | 1.2%    |
| 11      | 3         | 1.2%    |
| 7       | 3         | 1.2%    |
| Unknown | 2         | 0.8%    |
| 74      | 1         | 0.4%    |
| 54      | 1         | 0.4%    |
| 42      | 1         | 0.4%    |
| 40      | 1         | 0.4%    |
| 25      | 1         | 0.4%    |
| 19      | 1         | 0.4%    |
| 18      | 1         | 0.4%    |
| 10      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 150       | 60.24%  |
| 201-300     | 32        | 12.85%  |
| 501-600     | 27        | 10.84%  |
| 351-400     | 14        | 5.62%   |
| 401-500     | 9         | 3.61%   |
| 601-700     | 5         | 2.01%   |
| 701-800     | 3         | 1.2%    |
| 1-100       | 3         | 1.2%    |
| Unknown     | 2         | 0.8%    |
| 801-900     | 1         | 0.4%    |
| 1501-2000   | 1         | 0.4%    |
| 1001-1500   | 1         | 0.4%    |
| 901-1000    | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 171       | 78.44%  |
| 16/10   | 33        | 15.14%  |
| 21/9    | 3         | 1.38%   |
| 0.67    | 3         | 1.38%   |
| 5/4     | 2         | 0.92%   |
| 4/3     | 2         | 0.92%   |
| 3/2     | 2         | 0.92%   |
| Unknown | 2         | 0.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 104       | 41.6%   |
| 81-90          | 42        | 16.8%   |
| 71-80          | 20        | 8%      |
| 201-250        | 18        | 7.2%    |
| 301-350        | 11        | 4.4%    |
| 121-130        | 10        | 4%      |
| 351-500        | 7         | 2.8%    |
| 111-120        | 7         | 2.8%    |
| 61-70          | 4         | 1.6%    |
| 251-300        | 4         | 1.6%    |
| 151-200        | 4         | 1.6%    |
| 91-100         | 4         | 1.6%    |
| 51-60          | 3         | 1.2%    |
| 1-40           | 3         | 1.2%    |
| More than 1000 | 2         | 0.8%    |
| 141-150        | 2         | 0.8%    |
| 501-1000       | 2         | 0.8%    |
| Unknown        | 2         | 0.8%    |
| 41-50          | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 108       | 43.72%  |
| 101-120       | 47        | 19.03%  |
| 161-240       | 38        | 15.38%  |
| 51-100        | 36        | 14.57%  |
| More than 240 | 14        | 5.67%   |
| 1-50          | 2         | 0.81%   |
| Unknown       | 2         | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 168       | 74.01%  |
| 2     | 44        | 19.38%  |
| 0     | 11        | 4.85%   |
| 3     | 4         | 1.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 141       | 41.84%  |
| Realtek Semiconductor            | 110       | 32.64%  |
| Qualcomm Atheros                 | 28        | 8.31%   |
| Broadcom                         | 21        | 6.23%   |
| ASIX Electronics                 | 8         | 2.37%   |
| MediaTek                         | 4         | 1.19%   |
| Marvell Technology Group         | 3         | 0.89%   |
| Apple                            | 3         | 0.89%   |
| TP-Link                          | 2         | 0.59%   |
| Samsung Electronics              | 2         | 0.59%   |
| Ralink Technology                | 2         | 0.59%   |
| Nvidia                           | 2         | 0.59%   |
| Lenovo                           | 2         | 0.59%   |
| Broadcom Limited                 | 2         | 0.59%   |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |
| Ralink                           | 1         | 0.3%    |
| Qualcomm                         | 1         | 0.3%    |
| Microsoft                        | 1         | 0.3%    |
| D-Link                           | 1         | 0.3%    |
| Comneon                          | 1         | 0.3%    |
| Arduino SA                       | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 18.6%   |
| Intel Wi-Fi 6 AX200                                               | 25        | 6.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 3.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.1%    |
| Intel Wi-Fi 6 AX201                                               | 12        | 3.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 2.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 9         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.07%   |
| Intel Wireless 7260                                               | 8         | 2.07%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.55%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.55%   |
| Intel Wireless 3165                                               | 6         | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.29%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 1.03%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 4         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.78%   |
| Intel Wireless 7265                                               | 3         | 0.78%   |
| Intel Wireless 3160                                               | 3         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.78%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.78%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.78%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                | 3         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 137       | 62.84%  |
| Realtek Semiconductor | 28        | 12.84%  |
| Qualcomm Atheros      | 22        | 10.09%  |
| Broadcom              | 18        | 8.26%   |
| MediaTek              | 4         | 1.83%   |
| TP-Link               | 2         | 0.92%   |
| Ralink Technology     | 2         | 0.92%   |
| Broadcom Limited      | 2         | 0.92%   |
| Ralink                | 1         | 0.46%   |
| Qualcomm              | 1         | 0.46%   |
| D-Link                | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 25        | 11.36%  |
| Intel Wi-Fi 6 AX201                                           | 12        | 5.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 10        | 4.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 9         | 4.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 8         | 3.64%   |
| Intel Wireless 7260                                           | 8         | 3.64%   |
| Intel Wireless 8265 / 8275                                    | 6         | 2.73%   |
| Intel Wireless 3165                                           | 6         | 2.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 6         | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 5         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 2.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 5         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 5         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 4         | 1.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 4         | 1.82%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 4         | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 4         | 1.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 3         | 1.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 1.36%   |
| Intel Wireless 7265                                           | 3         | 1.36%   |
| Intel Wireless 3160                                           | 3         | 1.36%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 1.36%   |
| Intel Centrino Wireless-N 2230                                | 3         | 1.36%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 3         | 1.36%   |
| Intel Centrino Advanced-N 6235                                | 3         | 1.36%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 3         | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                 | 3         | 1.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 2         | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 0.91%   |
| Intel Wireless 8260                                           | 2         | 0.91%   |
| Intel WiFi Link 5100                                          | 2         | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 0.91%   |
| Intel Centrino Advanced-N 6200                                | 2         | 0.91%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter            | 2         | 0.91%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller        | 2         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 101       | 63.92%  |
| Intel                            | 23        | 14.56%  |
| Qualcomm Atheros                 | 8         | 5.06%   |
| ASIX Electronics                 | 8         | 5.06%   |
| Broadcom                         | 4         | 2.53%   |
| Marvell Technology Group         | 3         | 1.9%    |
| Apple                            | 3         | 1.9%    |
| Samsung Electronics              | 2         | 1.27%   |
| Nvidia                           | 2         | 1.27%   |
| Lenovo                           | 2         | 1.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.63%   |
| Microsoft                        | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 72        | 43.64%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 15        | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 7.27%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 8         | 4.85%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.42%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.82%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.21%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.21%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.21%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.21%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.21%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.21%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.21%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.21%   |
| Apple iBridge                                                                  | 2         | 1.21%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.61%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.61%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 0.61%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.61%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.61%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.61%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.61%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                            | 1         | 0.61%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.61%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.61%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.61%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.61%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.61%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.61%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.61%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 210       | 57.69%  |
| Ethernet | 152       | 41.76%  |
| Modem    | 2         | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 169       | 72.22%  |
| Ethernet | 65        | 27.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 124       | 56.62%  |
| 1     | 89        | 40.64%  |
| 0     | 4         | 1.83%   |
| 3     | 2         | 0.91%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 216       | 99.08%  |
| Yes  | 2         | 0.92%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 115       | 63.19%  |
| Realtek Semiconductor           | 15        | 8.24%   |
| Broadcom                        | 14        | 7.69%   |
| IMC Networks                    | 13        | 7.14%   |
| Qualcomm Atheros Communications | 9         | 4.95%   |
| Foxconn / Hon Hai               | 5         | 2.75%   |
| Apple                           | 5         | 2.75%   |
| Lite-On Technology              | 4         | 2.2%    |
| Qcom                            | 1         | 0.55%   |
| Micro Star International        | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 29        | 15.93%  |
| Intel AX201 Bluetooth                                                               | 25        | 13.74%  |
| Intel AX200 Bluetooth                                                               | 25        | 13.74%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 9.89%   |
| Realtek Bluetooth Radio                                                             | 9         | 4.95%   |
| Intel Bluetooth Device                                                              | 9         | 4.95%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 2.75%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 2.75%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.75%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.2%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.2%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.65%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.65%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.65%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.1%    |
| Intel AX210 Bluetooth                                                               | 2         | 1.1%    |
| IMC Networks Bluetooth Device                                                       | 2         | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.1%    |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 1.1%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.1%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.1%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.1%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 1.1%    |
| Realtek CSR BS8510                                                                  | 1         | 0.55%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.55%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.55%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.55%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.55%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.55%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 164       | 63.08%  |
| AMD                              | 52        | 20%     |
| Nvidia                           | 28        | 10.77%  |
| JMTek                            | 3         | 1.15%   |
| Apple                            | 3         | 1.15%   |
| Lenovo                           | 2         | 0.77%   |
| Texas Instruments                | 1         | 0.38%   |
| Silicon Integrated Systems [SiS] | 1         | 0.38%   |
| Razer USA                        | 1         | 0.38%   |
| No brand                         | 1         | 0.38%   |
| Native Instruments               | 1         | 0.38%   |
| Generalplus Technology           | 1         | 0.38%   |
| Dell                             | 1         | 0.38%   |
| Unknown                          | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 35        | 10.94%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 25        | 7.81%   |
| Intel Sunrise Point-LP HD Audio                                            | 18        | 5.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 4.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 3.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 3.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 3.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 3.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 3.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 2.81%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 2.5%    |
| Intel 8 Series HD Audio Controller                                         | 8         | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 2.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 2.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 1.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.56%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.56%   |
| Nvidia High Definition Audio Controller                                    | 4         | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.25%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.25%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.25%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.25%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.94%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.94%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.94%   |
| Nvidia Audio device                                                        | 3         | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.94%   |
| Apple Audio Device                                                         | 3         | 0.94%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 0.94%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.63%   |
| JMTek USB Audio Device                                                     | 2         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 77        | 50.99%  |
| SK hynix            | 29        | 19.21%  |
| Micron Technology   | 17        | 11.26%  |
| Unknown             | 7         | 4.64%   |
| Unknown             | 4         | 2.65%   |
| Kingston            | 3         | 1.99%   |
| A-DATA Technology   | 3         | 1.99%   |
| Unknown (ABCD)      | 2         | 1.32%   |
| Ramaxel Technology  | 2         | 1.32%   |
| Unknown (899D)      | 1         | 0.66%   |
| Unknown (09D5)      | 1         | 0.66%   |
| Team                | 1         | 0.66%   |
| Silicon Power       | 1         | 0.66%   |
| Imation             | 1         | 0.66%   |
| Essencore           | 1         | 0.66%   |
| Elpida              | 1         | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 4.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 3.03%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 2.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.42%   |
| Unknown                                                          | 4         | 2.42%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.82%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 3         | 1.82%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.82%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 1.82%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.82%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 3         | 1.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.82%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.82%   |
| Samsung RAM M471A1G44AB0-CTD 8GB DDR4 2667MT/s                   | 3         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 1.82%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 1.21%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.21%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.21%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.21%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.21%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.21%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.21%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.21%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.21%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.21%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.21%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.21%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DDR4 2667MT/s                   | 2         | 1.21%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 2         | 1.21%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.21%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.21%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.61%   |
| Unknown RAM CL22-22-22 D4-3200 16384MB SODIMM DDR4 3200MT/s      | 1         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 1         | 0.61%   |
| Unknown (899D) RAM TZD2G0816S32-SK001 16GB SODIMM DDR4 2133MT/s  | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 75        | 59.06%  |
| DDR3    | 26        | 20.47%  |
| LPDDR4  | 10        | 7.87%   |
| LPDDR3  | 6         | 4.72%   |
| DDR2    | 3         | 2.36%   |
| SDRAM   | 2         | 1.57%   |
| LPDDR5  | 2         | 1.57%   |
| DDR5    | 2         | 1.57%   |
| Unknown | 1         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 77.52%  |
| Row Of Chips | 21        | 16.28%  |
| Unknown      | 5         | 3.88%   |
| DIMM         | 3         | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 62        | 45.26%  |
| 4096  | 32        | 23.36%  |
| 16384 | 21        | 15.33%  |
| 2048  | 13        | 9.49%   |
| 32768 | 7         | 5.11%   |
| 1024  | 2         | 1.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 36        | 26.09%  |
| 2667    | 33        | 23.91%  |
| 1600    | 16        | 11.59%  |
| 2400    | 12        | 8.7%    |
| 2133    | 9         | 6.52%   |
| 4267    | 5         | 3.62%   |
| 3266    | 5         | 3.62%   |
| 1334    | 5         | 3.62%   |
| 4800    | 3         | 2.17%   |
| 6400    | 2         | 1.45%   |
| 1333    | 2         | 1.45%   |
| 1067    | 2         | 1.45%   |
| 8400    | 1         | 0.72%   |
| 4266    | 1         | 0.72%   |
| 4199    | 1         | 0.72%   |
| 2048    | 1         | 0.72%   |
| 1867    | 1         | 0.72%   |
| 800     | 1         | 0.72%   |
| 667     | 1         | 0.72%   |
| Unknown | 1         | 0.72%   |

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
| Chicony Electronics                    | 36        | 19.89%  |
| IMC Networks                           | 28        | 15.47%  |
| Acer                                   | 18        | 9.94%   |
| Realtek Semiconductor                  | 13        | 7.18%   |
| Microdia                               | 12        | 6.63%   |
| Silicon Motion                         | 11        | 6.08%   |
| Quanta                                 | 8         | 4.42%   |
| Apple                                  | 7         | 3.87%   |
| SunplusIT                              | 6         | 3.31%   |
| Shenzhen Kingcome Optoelectronic       | 6         | 3.31%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.31%   |
| Syntek                                 | 5         | 2.76%   |
| Suyin                                  | 5         | 2.76%   |
| Luxvisions Innotech Limited            | 4         | 2.21%   |
| Sunplus Innovation Technology          | 3         | 1.66%   |
| Z-Star Microelectronics                | 2         | 1.1%    |
| Lenovo                                 | 2         | 1.1%    |
| Bison Electronics                      | 2         | 1.1%    |
| Sonix Technology                       | 1         | 0.55%   |
| Microsoft                              | 1         | 0.55%   |
| Logitech                               | 1         | 0.55%   |
| Goodong Industry                       | 1         | 0.55%   |
| DigiTech                               | 1         | 0.55%   |
| Cubeternet                             | 1         | 0.55%   |
| Alcor Micro                            | 1         | 0.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 10        | 5.46%   |
| IMC Networks Integrated Camera                          | 9         | 4.92%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 8         | 4.37%   |
| Microdia Integrated_Webcam_HD                           | 7         | 3.83%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera         | 6         | 3.28%   |
| Realtek LG Camera                                       | 5         | 2.73%   |
| Chicony HD WebCam                                       | 5         | 2.73%   |
| Acer HD Webcam                                          | 5         | 2.73%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 4         | 2.19%   |
| Syntek Integrated Camera                                | 3         | 1.64%   |
| Suyin HP Truevision HD                                  | 3         | 1.64%   |
| SunplusIT 1080p FHD Camera                              | 3         | 1.64%   |
| Silicon Motion LG HD WebCam                             | 3         | 1.64%   |
| Quanta HP TrueVision HD Camera                          | 3         | 1.64%   |
| Chicony USB 2.0 Camera                                  | 3         | 1.64%   |
| Chicony LG Camera                                       | 3         | 1.64%   |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 1.64%   |
| Acer Integrated Camera                                  | 3         | 1.64%   |
| Z-Star Webcam                                           | 2         | 1.09%   |
| SunplusIT 720p HD Camera                                | 2         | 1.09%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 2         | 1.09%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.09%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.09%   |
| Quanta LG Webcam                                        | 2         | 1.09%   |
| Microdia USB 2.0 Camera                                 | 2         | 1.09%   |
| Luxvisions Innotech Limited HP HD Camera                | 2         | 1.09%   |
| IMC Networks USB HD Webcam                              | 2         | 1.09%   |
| IMC Networks Integrated RGB Camera                      | 2         | 1.09%   |
| Chicony LG HD WebCam                                    | 2         | 1.09%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.09%   |
| Chicony HP TrueVision HD Camera                         | 2         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.09%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 2         | 1.09%   |
| Apple Built-in iSight                                   | 2         | 1.09%   |
| Acer Lenovo EasyCamera                                  | 2         | 1.09%   |
| Acer BisonCam,NB Pro                                    | 2         | 1.09%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.55%   |
| Syntek HP Webcam                                        | 1         | 0.55%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.55%   |
| Suyin HP TrueVision Full HD                             | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 15        | 31.25%  |
| Validity Sensors                   | 9         | 18.75%  |
| Samsung Electronics                | 6         | 12.5%   |
| Upek                               | 4         | 8.33%   |
| Shenzhen Goodix Technology         | 4         | 8.33%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 6.25%   |
| STMicroelectronics                 | 2         | 4.17%   |
| LighTuning Technology              | 2         | 4.17%   |
| Elan Microelectronics              | 2         | 4.17%   |
| AuthenTec                          | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 8.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 4         | 8.33%   |
| Samsung Fingerprint Sensor Device - 730B                        | 4         | 8.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 3         | 6.25%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 4.17%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 4.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 4.17%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 4.17%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 4.17%   |
| Samsung Fingerprint Device                                      | 2         | 4.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 4.17%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 1         | 2.08%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 2.08%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 2.08%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 2.08%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.08%   |
| Synaptics WBDI Device                                           | 1         | 2.08%   |
| Synaptics WBDI                                                  | 1         | 2.08%   |
| Synaptics UWP WBDI Device                                       | 1         | 2.08%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 2.08%   |
| Elan ELAN:Fingerprint                                           | 1         | 2.08%   |
| Elan ELAN:ARM-M4                                                | 1         | 2.08%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 2.08%   |

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
| 0     | 129       | 57.85%  |
| 1     | 77        | 34.53%  |
| 2     | 13        | 5.83%   |
| 3     | 4         | 1.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 48        | 42.86%  |
| Graphics card         | 26        | 23.21%  |
| Net/wireless          | 16        | 14.29%  |
| Multimedia controller | 8         | 7.14%   |
| Chipcard              | 7         | 6.25%   |
| Bluetooth             | 3         | 2.68%   |
| Sound                 | 2         | 1.79%   |
| Net/ethernet          | 2         | 1.79%   |

