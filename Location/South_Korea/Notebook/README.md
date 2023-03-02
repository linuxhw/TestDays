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

Total: 310

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 44        | 19.56%  |
| Ubuntu 18.04       | 19        | 8.44%   |
| Ubuntu 22.04       | 17        | 7.56%   |
| Ubuntu 21.10       | 7         | 3.11%   |
| Gooroom            | 7         | 3.11%   |
| Debian 11          | 7         | 3.11%   |
| Arch               | 6         | 2.67%   |
| Arch Rolling       | 5         | 2.22%   |
| Linux Mint 20.3    | 4         | 1.78%   |
| Linux Mint 20.1    | 4         | 1.78%   |
| Fedora 36          | 4         | 1.78%   |
| Fedora 32          | 4         | 1.78%   |
| Ubuntu 19.10       | 3         | 1.33%   |
| Ubuntu 19.04       | 3         | 1.33%   |
| ROSA R11           | 3         | 1.33%   |
| OpenMandriva 4.2   | 3         | 1.33%   |
| Kubuntu 22.04      | 3         | 1.33%   |
| HamoniKR 4.0       | 3         | 1.33%   |
| Fedora 37          | 3         | 1.33%   |
| Fedora 34          | 3         | 1.33%   |
| Debian 10          | 3         | 1.33%   |
| CentOS 8           | 3         | 1.33%   |
| Zorin 16           | 2         | 0.89%   |
| Zorin 15           | 2         | 0.89%   |
| Ubuntu MATE 18.04  | 2         | 0.89%   |
| ROSA R10           | 2         | 0.89%   |
| Pop!_OS 21.10      | 2         | 0.89%   |
| OpenMandriva 23.01 | 2         | 0.89%   |
| Manjaro 21.3.0     | 2         | 0.89%   |
| LMDE 5             | 2         | 0.89%   |
| Linux Mint 20      | 2         | 0.89%   |
| KDE neon 20.04     | 2         | 0.89%   |
| Endless 3.8.5      | 2         | 0.89%   |
| Xubuntu 20.04      | 1         | 0.44%   |
| Ubuntu Unity 18.04 | 1         | 0.44%   |
| Ubuntu Unity 16.04 | 1         | 0.44%   |
| Ubuntu 22.10       | 1         | 0.44%   |
| Ubuntu 21.04       | 1         | 0.44%   |
| Ubuntu 20.10       | 1         | 0.44%   |
| SteamOS 3.4.4      | 1         | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 94        | 43.32%  |
| Fedora       | 15        | 6.91%   |
| Linux Mint   | 13        | 5.99%   |
| Debian       | 10        | 4.61%   |
| Manjaro      | 9         | 4.15%   |
| Arch         | 9         | 4.15%   |
| Gooroom      | 8         | 3.69%   |
| OpenMandriva | 7         | 3.23%   |
| ROSA         | 5         | 2.3%    |
| Kubuntu      | 5         | 2.3%    |
| Endless      | 5         | 2.3%    |
| Zorin        | 4         | 1.84%   |
| Pop!_OS      | 4         | 1.84%   |
| No1          | 4         | 1.84%   |
| HamoniKR     | 4         | 1.84%   |
| CentOS       | 4         | 1.84%   |
| Ubuntu Unity | 2         | 0.92%   |
| Ubuntu MATE  | 2         | 0.92%   |
| SteamOS      | 2         | 0.92%   |
| LMDE         | 2         | 0.92%   |
| KDE neon     | 2         | 0.92%   |
| EndeavourOS  | 2         | 0.92%   |
| Xubuntu      | 1         | 0.46%   |
| openSUSE     | 1         | 0.46%   |
| Lubuntu      | 1         | 0.46%   |
| Gentoo       | 1         | 0.46%   |
| Garuda Linux | 1         | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.15.0-53-generic               | 5         | 2.1%    |
| 5.10.0-19-amd64                 | 5         | 2.1%    |
| 5.4.0-42-generic                | 4         | 1.68%   |
| 5.15.0-58-generic               | 4         | 1.68%   |
| 5.10.0-17-amd64                 | 4         | 1.68%   |
| 5.4.0-58-generic                | 3         | 1.26%   |
| 5.4.0-26-generic                | 3         | 1.26%   |
| 5.3.0-40-generic                | 3         | 1.26%   |
| 5.19.15-201.fc36.x86_64         | 3         | 1.26%   |
| 5.15.0-56-generic               | 3         | 1.26%   |
| 5.13.0-28-generic               | 3         | 1.26%   |
| 5.11.0-37-generic               | 3         | 1.26%   |
| 4.19.0-9-amd64                  | 3         | 1.26%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3         | 1.26%   |
| 6.1.1-desktop-1omv2290          | 2         | 0.84%   |
| 5.8.4-200.fc32.x86_64           | 2         | 0.84%   |
| 5.8.0-53-generic                | 2         | 0.84%   |
| 5.8.0-43-generic                | 2         | 0.84%   |
| 5.4.0-81-generic                | 2         | 0.84%   |
| 5.4.0-56-generic                | 2         | 0.84%   |
| 5.4.0-48-generic                | 2         | 0.84%   |
| 5.4.0-39-generic                | 2         | 0.84%   |
| 5.4.0-33-generic                | 2         | 0.84%   |
| 5.4.0-31-generic                | 2         | 0.84%   |
| 5.4.0-29-generic                | 2         | 0.84%   |
| 5.3.0-46-generic                | 2         | 0.84%   |
| 5.18.5-1-MANJARO                | 2         | 0.84%   |
| 5.15.0-52-generic               | 2         | 0.84%   |
| 5.15.0-33-generic               | 2         | 0.84%   |
| 5.15.0-27-generic               | 2         | 0.84%   |
| 5.13.0-44-generic               | 2         | 0.84%   |
| 5.13.0-27-generic               | 2         | 0.84%   |
| 5.10.14-desktop-1omv4002        | 2         | 0.84%   |
| 5.0.0-37-generic                | 2         | 0.84%   |
| 5.0.0-25-generic                | 2         | 0.84%   |
| 5.0.0-13-generic                | 2         | 0.84%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.84%   |
| 4.18.0-17-generic               | 2         | 0.84%   |
| 4.15.0-112-generic              | 2         | 0.84%   |
| 6.1.9-200.fc37.x86_64           | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 46        | 20.09%  |
| 5.15.0  | 22        | 9.61%   |
| 5.13.0  | 15        | 6.55%   |
| 5.10.0  | 12        | 5.24%   |
| 5.8.0   | 11        | 4.8%    |
| 5.11.0  | 10        | 4.37%   |
| 4.15.0  | 10        | 4.37%   |
| 5.3.0   | 9         | 3.93%   |
| 5.0.0   | 7         | 3.06%   |
| 4.18.0  | 7         | 3.06%   |
| 4.19.0  | 6         | 2.62%   |
| 5.19.15 | 3         | 1.31%   |
| 6.1.1   | 2         | 0.87%   |
| 6.0.0   | 2         | 0.87%   |
| 5.8.4   | 2         | 0.87%   |
| 5.18.5  | 2         | 0.87%   |
| 5.16.19 | 2         | 0.87%   |
| 5.15.11 | 2         | 0.87%   |
| 5.14.0  | 2         | 0.87%   |
| 5.10.14 | 2         | 0.87%   |
| 4.9.60  | 2         | 0.87%   |
| 6.1.9   | 1         | 0.44%   |
| 6.1.11  | 1         | 0.44%   |
| 6.1.10  | 1         | 0.44%   |
| 6.1.0   | 1         | 0.44%   |
| 6.0.9   | 1         | 0.44%   |
| 6.0.6   | 1         | 0.44%   |
| 6.0.2   | 1         | 0.44%   |
| 6.0.14  | 1         | 0.44%   |
| 5.9.9   | 1         | 0.44%   |
| 5.8.18  | 1         | 0.44%   |
| 5.8.15  | 1         | 0.44%   |
| 5.7.17  | 1         | 0.44%   |
| 5.6.11  | 1         | 0.44%   |
| 5.6.0   | 1         | 0.44%   |
| 5.5.2   | 1         | 0.44%   |
| 5.4.61  | 1         | 0.44%   |
| 5.4.55  | 1         | 0.44%   |
| 5.3.7   | 1         | 0.44%   |
| 5.2.11  | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 48        | 21.05%  |
| 5.15    | 30        | 13.16%  |
| 5.13    | 16        | 7.02%   |
| 5.10    | 16        | 7.02%   |
| 5.8     | 15        | 6.58%   |
| 5.11    | 15        | 6.58%   |
| 4.15    | 11        | 4.82%   |
| 5.3     | 10        | 4.39%   |
| 4.18    | 8         | 3.51%   |
| 5.0     | 7         | 3.07%   |
| 4.19    | 7         | 3.07%   |
| 6.1     | 6         | 2.63%   |
| 6.0     | 6         | 2.63%   |
| 5.19    | 5         | 2.19%   |
| 5.16    | 5         | 2.19%   |
| 5.12    | 5         | 2.19%   |
| 5.14    | 4         | 1.75%   |
| 5.18    | 3         | 1.32%   |
| 5.6     | 2         | 0.88%   |
| 4.9     | 2         | 0.88%   |
| 5.9     | 1         | 0.44%   |
| 5.7     | 1         | 0.44%   |
| 5.5     | 1         | 0.44%   |
| 5.2     | 1         | 0.44%   |
| 5.17    | 1         | 0.44%   |
| 4.16    | 1         | 0.44%   |
| 3.10    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 207       | 98.1%   |
| i686    | 3         | 1.42%   |
| aarch64 | 1         | 0.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 115       | 53%     |
| KDE5            | 30        | 13.82%  |
| Unknown         | 17        | 7.83%   |
| X-Cinnamon      | 12        | 5.53%   |
| LXDE            | 8         | 3.69%   |
| GNOME Flashback | 8         | 3.69%   |
| XFCE            | 7         | 3.23%   |
| Cinnamon        | 6         | 2.76%   |
| KDE4            | 3         | 1.38%   |
| KDE             | 3         | 1.38%   |
| i3              | 3         | 1.38%   |
| Unity           | 2         | 0.92%   |
| MATE            | 2         | 0.92%   |
| sway            | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 150       | 70.42%  |
| Wayland | 42        | 19.72%  |
| Unknown | 13        | 6.1%    |
| Tty     | 8         | 3.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 99        | 45.41%  |
| GDM     | 43        | 19.72%  |
| SDDM    | 24        | 11.01%  |
| GDM3    | 20        | 9.17%   |
| LightDM | 15        | 6.88%   |
| TDM     | 13        | 5.96%   |
| KDM     | 3         | 1.38%   |
| XDM     | 1         | 0.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ko_KR   | 98        | 45.16%  |
| en_US   | 76        | 35.02%  |
| Unknown | 26        | 11.98%  |
| en_CA   | 4         | 1.84%   |
| zh_CN   | 3         | 1.38%   |
| id_ID   | 2         | 0.92%   |
| C       | 2         | 0.92%   |
| vi_VN   | 1         | 0.46%   |
| pt_BR   | 1         | 0.46%   |
| fr_FR   | 1         | 0.46%   |
| en_NZ   | 1         | 0.46%   |
| el_GR   | 1         | 0.46%   |
| ar_EG   | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 149       | 70.28%  |
| BIOS | 63        | 29.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 176       | 82.63%  |
| Btrfs   | 16        | 7.51%   |
| Xfs     | 6         | 2.82%   |
| Overlay | 6         | 2.82%   |
| Unknown | 6         | 2.82%   |
| Zfs     | 3         | 1.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 105       | 48.84%  |
| Unknown | 95        | 44.19%  |
| MBR     | 15        | 6.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 199       | 93.87%  |
| Yes       | 13        | 6.13%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 143       | 66.82%  |
| Yes       | 71        | 33.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 47        | 22.27%  |
| Samsung Electronics | 28        | 13.27%  |
| Hewlett-Packard     | 23        | 10.9%   |
| LG Electronics      | 21        | 9.95%   |
| ASUSTek Computer    | 21        | 9.95%   |
| Dell                | 15        | 7.11%   |
| MSI                 | 11        | 5.21%   |
| Apple               | 8         | 3.79%   |
| HANSUNG COMPUTER    | 4         | 1.9%    |
| Notebook            | 3         | 1.42%   |
| Acer                | 3         | 1.42%   |
| Valve               | 2         | 0.95%   |
| Toshiba             | 2         | 0.95%   |
| Razer               | 2         | 0.95%   |
| Google              | 2         | 0.95%   |
| Gigabyte Technology | 2         | 0.95%   |
| Wolfnfox            | 1         | 0.47%   |
| TG                  | 1         | 0.47%   |
| Teclast             | 1         | 0.47%   |
| Sony                | 1         | 0.47%   |
| SLIMBOOK            | 1         | 0.47%   |
| Pine Microsystems   | 1         | 0.47%   |
| MS                  | 1         | 0.47%   |
| MECHREVO            | 1         | 0.47%   |
| Jooyontech Computer | 1         | 0.47%   |
| Jooyon Tech         | 1         | 0.47%   |
| Intel               | 1         | 0.47%   |
| IMUZ                | 1         | 0.47%   |
| Clevo               | 1         | 0.47%   |
| AVERATEC            | 1         | 0.47%   |
| AMI                 | 1         | 0.47%   |
| Alienware           | 1         | 0.47%   |
| Unknown             | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung 950XED                                    | 3         | 1.42%   |
| Samsung 950XCJ/951XCJ/950XCR                      | 3         | 1.42%   |
| Valve Jupiter                                     | 2         | 0.95%   |
| Samsung 760XDA                                    | 2         | 0.95%   |
| Razer Blade 17 (2022) - RZ09-0423                 | 2         | 0.95%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01S00              | 2         | 0.95%   |
| Lenovo IdeaPad 3 15IIL05 81WE                     | 2         | 0.95%   |
| HP Stream Notebook PC 13                          | 2         | 0.95%   |
| HP Laptop 15-db1xxx                               | 2         | 0.95%   |
| HANSUNG COMPUTER TFX5470H                         | 2         | 0.95%   |
| Dell XPS 15 7590                                  | 2         | 0.95%   |
| Dell Inspiron 15 5510                             | 2         | 0.95%   |
| Apple MacBookPro16,1                              | 2         | 0.95%   |
| Wolfnfox WF-TBAT                                  | 1         | 0.47%   |
| Toshiba Satellite P50-B-103                       | 1         | 0.47%   |
| Toshiba Satellite L655                            | 1         | 0.47%   |
| TG NXI-A7000 Series                               | 1         | 0.47%   |
| Teclast tPAD                                      | 1         | 0.47%   |
| Sony VPCEA36FK                                    | 1         | 0.47%   |
| SLIMBOOK PROX15-AMD                               | 1         | 0.47%   |
| Samsung X120/X170/X171                            | 1         | 0.47%   |
| Samsung SX11S                                     | 1         | 0.47%   |
| Samsung RC420/RC520/RC720                         | 1         | 0.47%   |
| Samsung R59P/R60P/R61P                            | 1         | 0.47%   |
| Samsung R440/R480                                 | 1         | 0.47%   |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.47%   |
| Samsung 940XFG                                    | 1         | 0.47%   |
| Samsung 905S3G/906S3G/915S3G                      | 1         | 0.47%   |
| Samsung 900X5N                                    | 1         | 0.47%   |
| Samsung 800G5M/800G5W                             | 1         | 0.47%   |
| Samsung 760XBE                                    | 1         | 0.47%   |
| Samsung 730QCJ/730QCR                             | 1         | 0.47%   |
| Samsung 670Z5E                                    | 1         | 0.47%   |
| Samsung 570Z5E/580Z5E                             | 1         | 0.47%   |
| Samsung 550XED                                    | 1         | 0.47%   |
| Samsung 530U3BI/530U4BI/530U4BH                   | 1         | 0.47%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.47%   |
| Samsung 400B4C/400B5C/200B4C/200B5C               | 1         | 0.47%   |
| Samsung 400B4B/400B5B/200B4B/200B5B               | 1         | 0.47%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 31        | 14.69%  |
| Lenovo IdeaPad            | 11        | 5.21%   |
| ASUS VivoBook             | 8         | 3.79%   |
| HP Pavilion               | 7         | 3.32%   |
| Dell Inspiron             | 5         | 2.37%   |
| HP Laptop                 | 4         | 1.9%    |
| HP EliteBook              | 4         | 1.9%    |
| Dell XPS                  | 4         | 1.9%    |
| Samsung 950XED            | 3         | 1.42%   |
| Samsung 950XCJ            | 3         | 1.42%   |
| HP Stream                 | 3         | 1.42%   |
| Dell Latitude             | 3         | 1.42%   |
| Valve Jupiter             | 2         | 0.95%   |
| Toshiba Satellite         | 2         | 0.95%   |
| Samsung 760XDA            | 2         | 0.95%   |
| Razer Blade               | 2         | 0.95%   |
| MSI Prestige              | 2         | 0.95%   |
| HP ProBook                | 2         | 0.95%   |
| HANSUNG COMPUTER TFX5470H | 2         | 0.95%   |
| ASUS TUF                  | 2         | 0.95%   |
| ASUS ROG                  | 2         | 0.95%   |
| Apple MacBookPro5         | 2         | 0.95%   |
| Apple MacBookPro16        | 2         | 0.95%   |
| Acer Swift                | 2         | 0.95%   |
| Wolfnfox WF-TBAT          | 1         | 0.47%   |
| TG NXI-A7000              | 1         | 0.47%   |
| Teclast tPAD              | 1         | 0.47%   |
| Sony VPCEA36FK            | 1         | 0.47%   |
| SLIMBOOK PROX15-AMD       | 1         | 0.47%   |
| Samsung X120              | 1         | 0.47%   |
| Samsung SX11S             | 1         | 0.47%   |
| Samsung RC420             | 1         | 0.47%   |
| Samsung R59P              | 1         | 0.47%   |
| Samsung R440              | 1         | 0.47%   |
| Samsung 950XDB            | 1         | 0.47%   |
| Samsung 940XFG            | 1         | 0.47%   |
| Samsung 905S3G            | 1         | 0.47%   |
| Samsung 900X5N            | 1         | 0.47%   |
| Samsung 800G5M            | 1         | 0.47%   |
| Samsung 760XBE            | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 40        | 18.96%  |
| 2021    | 25        | 11.85%  |
| 2019    | 22        | 10.43%  |
| 2018    | 18        | 8.53%   |
| 2022    | 15        | 7.11%   |
| 2014    | 15        | 7.11%   |
| 2013    | 15        | 7.11%   |
| 2011    | 11        | 5.21%   |
| 2010    | 8         | 3.79%   |
| 2017    | 7         | 3.32%   |
| 2008    | 7         | 3.32%   |
| 2016    | 6         | 2.84%   |
| 2012    | 6         | 2.84%   |
| 2015    | 5         | 2.37%   |
| 2009    | 4         | 1.9%    |
| 2007    | 3         | 1.42%   |
| 2006    | 2         | 0.95%   |
| 2023    | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 211       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 190       | 89.2%   |
| Enabled  | 23        | 10.8%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 209       | 99.05%  |
| Yes  | 2         | 0.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 55        | 25.7%   |
| 16.01-24.0  | 43        | 20.09%  |
| 8.01-16.0   | 38        | 17.76%  |
| 3.01-4.0    | 35        | 16.36%  |
| 32.01-64.0  | 19        | 8.88%   |
| 1.01-2.0    | 13        | 6.07%   |
| 64.01-256.0 | 7         | 3.27%   |
| 24.01-32.0  | 3         | 1.4%    |
| 2.01-3.0    | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 73        | 31.74%  |
| 2.01-3.0   | 55        | 23.91%  |
| 4.01-8.0   | 35        | 15.22%  |
| 3.01-4.0   | 35        | 15.22%  |
| 0.51-1.0   | 17        | 7.39%   |
| 8.01-16.0  | 10        | 4.35%   |
| 16.01-24.0 | 3         | 1.3%    |
| 24.01-32.0 | 1         | 0.43%   |
| 0.01-0.5   | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 136       | 62.67%  |
| 2      | 69        | 31.8%   |
| 3      | 9         | 4.15%   |
| 4      | 2         | 0.92%   |
| 0      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 177       | 83.89%  |
| Yes       | 34        | 16.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 69.48%  |
| No        | 65        | 30.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 203       | 95.75%  |
| No        | 9         | 4.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 176       | 82.63%  |
| No        | 37        | 17.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| South Korea | 211       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Seoul           | 36        | 16.22%  |
| Seocho-gu       | 13        | 5.86%   |
| Suwon           | 9         | 4.05%   |
| Gwanak-gu       | 8         | 3.6%    |
| Uiwang          | 7         | 3.15%   |
| Seongnam-si     | 6         | 2.7%    |
| Jung-gu         | 6         | 2.7%    |
| Hwaseong-si     | 6         | 2.7%    |
| Yongin-si       | 5         | 2.25%   |
| Yongsan-gu      | 4         | 1.8%    |
| Seongbuk-gu     | 4         | 1.8%    |
| Incheon         | 4         | 1.8%    |
| Daejeon         | 4         | 1.8%    |
| Daegu           | 4         | 1.8%    |
| Busan           | 4         | 1.8%    |
| Bupyeong-gu     | 4         | 1.8%    |
| Anyang-si       | 4         | 1.8%    |
| Pyeongtaek-si   | 3         | 1.35%   |
| Nam-gu          | 3         | 1.35%   |
| Mapo-gu         | 3         | 1.35%   |
| Jeonju          | 3         | 1.35%   |
| Gwangju         | 3         | 1.35%   |
| Geumjeong-gu    | 3         | 1.35%   |
| Gangseo-gu      | 3         | 1.35%   |
| Gangnam-gu      | 3         | 1.35%   |
| Yuseong-gu      | 2         | 0.9%    |
| Yongsan-dong    | 2         | 0.9%    |
| Yeonsu-gu       | 2         | 0.9%    |
| Siheung-si      | 2         | 0.9%    |
| Namdong-gu      | 2         | 0.9%    |
| Jeju City       | 2         | 0.9%    |
| Gyeongsan-si    | 2         | 0.9%    |
| Gimpo-si        | 2         | 0.9%    |
| Danyang-gun     | 2         | 0.9%    |
| Cheongju-si     | 2         | 0.9%    |
| Changwon        | 2         | 0.9%    |
| Buk-gu          | 2         | 0.9%    |
| Yuseong         | 1         | 0.45%   |
| Yeongdeungpo-gu | 1         | 0.45%   |
| Yangju          | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 75        | 91     | 26.5%   |
| WDC                            | 30        | 32     | 10.6%   |
| SK hynix                       | 20        | 27     | 7.07%   |
| Unknown                        | 19        | 23     | 6.71%   |
| SanDisk                        | 19        | 19     | 6.71%   |
| Seagate                        | 15        | 19     | 5.3%    |
| Toshiba                        | 13        | 15     | 4.59%   |
| Crucial                        | 12        | 13     | 4.24%   |
| Kingston                       | 8         | 9      | 2.83%   |
| Intel                          | 8         | 13     | 2.83%   |
| Phison                         | 5         | 6      | 1.77%   |
| Hitachi                        | 5         | 6      | 1.77%   |
| Apple                          | 5         | 5      | 1.77%   |
| A-DATA Technology              | 5         | 5      | 1.77%   |
| Micron Technology              | 4         | 5      | 1.41%   |
| TAMMUZ                         | 3         | 5      | 1.06%   |
| HGST                           | 3         | 4      | 1.06%   |
| UMIS                           | 2         | 2      | 0.71%   |
| Team                           | 2         | 2      | 0.71%   |
| KIOXIA                         | 2         | 2      | 0.71%   |
| JMicron Technology             | 2         | 2      | 0.71%   |
| Fujitsu                        | 2         | 2      | 0.71%   |
| ZTC                            | 1         | 1      | 0.35%   |
| XPG                            | 1         | 2      | 0.35%   |
| VIVA300s                       | 1         | 1      | 0.35%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.35%   |
| TYPEC 1T                       | 1         | 1      | 0.35%   |
| Transcend                      | 1         | 2      | 0.35%   |
| T-FORCE                        | 1         | 1      | 0.35%   |
| Solid State Storage Technology | 1         | 1      | 0.35%   |
| Silicon Motion                 | 1         | 1      | 0.35%   |
| RevuAhn                        | 1         | 1      | 0.35%   |
| Plextor                        | 1         | 1      | 0.35%   |
| Phison Electronics             | 1         | 1      | 0.35%   |
| O2 Micro                       | 1         | 1      | 0.35%   |
| LITEONIT                       | 1         | 1      | 0.35%   |
| LITEON                         | 1         | 1      | 0.35%   |
| KingSpec                       | 1         | 1      | 0.35%   |
| ipTIME                         | 1         | 1      | 0.35%   |
| IPLEX                          | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| SK hynix SHGP31-1000GM-2 1TB                         | 4         | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 1%      |
| Samsung SSD 980 PRO 2TB                              | 3         | 1%      |
| Samsung SSD 860 EVO 500GB                            | 3         | 1%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 3         | 1%      |
| Samsung MZVL21T0HCLR-00B00 1TB                       | 3         | 1%      |
| WDC WDS100T2B0C-00PXH0 1TB                           | 2         | 0.66%   |
| WDC WD50 00LPVX-22V0TT0 500GB                        | 2         | 0.66%   |
| Unknown SLD64G  64GB                                 | 2         | 0.66%   |
| Unknown SD/MMC/MS PRO 16GB                           | 2         | 0.66%   |
| Unknown MMC Card  32GB                               | 2         | 0.66%   |
| Unknown MMC Card  256GB                              | 2         | 0.66%   |
| Toshiba KBG30ZMV256G 256GB                           | 2         | 0.66%   |
| SK hynix SHGP31-1000GM 1TB                           | 2         | 0.66%   |
| SK hynix NVMe SSD Drive 256GB                        | 2         | 0.66%   |
| Seagate ST1000LM048-2E7172 1TB                       | 2         | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB                       | 2         | 0.66%   |
| Seagate Expansion 1TB                                | 2         | 0.66%   |
| SanDisk SD8SBAT256G1122 256GB SSD                    | 2         | 0.66%   |
| SanDisk NVMe SSD Drive 512GB                         | 2         | 0.66%   |
| SanDisk NVMe SSD Drive 256GB                         | 2         | 0.66%   |
| Samsung SSD 860 EVO 1TB                              | 2         | 0.66%   |
| Samsung SSD 830 Series 256GB                         | 2         | 0.66%   |
| Samsung SSD 750 EVO 120GB                            | 2         | 0.66%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 2         | 0.66%   |
| Samsung PSSD T7 2TB                                  | 2         | 0.66%   |
| Samsung NVMe SSD Drive 2TB                           | 2         | 0.66%   |
| Samsung MZVLQ1T0HBLB-00B 1TB                         | 2         | 0.66%   |
| Samsung MZVLB512HAJQ-00000 512GB                     | 2         | 0.66%   |
| Samsung MZVLB256HBHQ-000 256GB                       | 2         | 0.66%   |
| Samsung MZNLN256HAJQ-00000 256GB SSD                 | 2         | 0.66%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD                 | 2         | 0.66%   |
| Kingston OM8PCP3512F-AB 512GB                        | 2         | 0.66%   |
| JMicron Tech 250GB                                   | 2         | 0.66%   |
| Intel SSDPEKNU512GZ 512GB                            | 2         | 0.66%   |
| HGST HTS721010A9E630 1TB                             | 2         | 0.66%   |
| Crucial CT500MX500SSD1 500GB                         | 2         | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                          | 2         | 0.66%   |
| Apple ANS2 NVMe Controller 1TB                       | 2         | 0.66%   |
| ZTC SM201-256G SSD                                   | 1         | 0.33%   |

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
| Samsung Electronics | 39        | 45     | 38.24%  |
| SanDisk             | 11        | 11     | 10.78%  |
| Crucial             | 11        | 12     | 10.78%  |
| SK hynix            | 5         | 6      | 4.9%    |
| WDC                 | 4         | 5      | 3.92%   |
| TAMMUZ              | 3         | 5      | 2.94%   |
| Micron Technology   | 3         | 4      | 2.94%   |
| Kingston            | 3         | 4      | 2.94%   |
| Intel               | 3         | 4      | 2.94%   |
| Team                | 2         | 2      | 1.96%   |
| Apple               | 2         | 2      | 1.96%   |
| A-DATA Technology   | 2         | 2      | 1.96%   |
| ZTC                 | 1         | 1      | 0.98%   |
| TYPEC 1T            | 1         | 1      | 0.98%   |
| Transcend           | 1         | 2      | 0.98%   |
| Toshiba             | 1         | 1      | 0.98%   |
| T-FORCE             | 1         | 1      | 0.98%   |
| RevuAhn             | 1         | 1      | 0.98%   |
| Plextor             | 1         | 1      | 0.98%   |
| LITEONIT            | 1         | 1      | 0.98%   |
| LITEON              | 1         | 1      | 0.98%   |
| KingSpec            | 1         | 1      | 0.98%   |
| IPLEX               | 1         | 1      | 0.98%   |
| China               | 1         | 1      | 0.98%   |
| Biostar             | 1         | 1      | 0.98%   |
| Apacer              | 1         | 1      | 0.98%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 103       | 135    | 38.43%  |
| SSD     | 95        | 117    | 35.45%  |
| HDD     | 48        | 54     | 17.91%  |
| MMC     | 17        | 21     | 6.34%   |
| Unknown | 5         | 6      | 1.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 114       | 157    | 45.6%   |
| NVMe | 103       | 135    | 41.2%   |
| MMC  | 17        | 21     | 6.8%    |
| SAS  | 16        | 20     | 6.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 95        | 118    | 67.86%  |
| 0.51-1.0   | 38        | 44     | 27.14%  |
| 1.01-2.0   | 6         | 8      | 4.29%   |
| 4.01-10.0  | 1         | 1      | 0.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 82        | 37.1%   |
| 251-500        | 45        | 20.36%  |
| 501-1000       | 28        | 12.67%  |
| 1001-2000      | 19        | 8.6%    |
| 51-100         | 19        | 8.6%    |
| 21-50          | 10        | 4.52%   |
| 1-20           | 8         | 3.62%   |
| More than 3000 | 6         | 2.71%   |
| 2001-3000      | 3         | 1.36%   |
| Unknown        | 1         | 0.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 94        | 41.41%  |
| 21-50          | 48        | 21.15%  |
| 101-250        | 30        | 13.22%  |
| 51-100         | 20        | 8.81%   |
| 251-500        | 16        | 7.05%   |
| 501-1000       | 10        | 4.41%   |
| 1001-2000      | 6         | 2.64%   |
| More than 3000 | 1         | 0.44%   |
| 2001-3000      | 1         | 0.44%   |
| Unknown        | 1         | 0.44%   |

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
| Detected | 120       | 179    | 51.72%  |
| Works    | 98        | 140    | 42.24%  |
| Malfunc  | 14        | 14     | 6.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 118       | 46.46%  |
| Samsung Electronics              | 37        | 14.57%  |
| AMD                              | 26        | 10.24%  |
| SanDisk                          | 20        | 7.87%   |
| SK hynix                         | 14        | 5.51%   |
| Phison Electronics               | 8         | 3.15%   |
| Toshiba America Info Systems     | 6         | 2.36%   |
| Kingston Technology Company      | 5         | 1.97%   |
| Union Memory (Shenzhen)          | 3         | 1.18%   |
| Apple                            | 3         | 1.18%   |
| ADATA Technology                 | 3         | 1.18%   |
| Silicon Motion                   | 2         | 0.79%   |
| Nvidia                           | 2         | 0.79%   |
| KIOXIA                           | 2         | 0.79%   |
| Solid State Storage Technology   | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] | 1         | 0.39%   |
| O2 Micro                         | 1         | 0.39%   |
| Micron/Crucial Technology        | 1         | 0.39%   |
| Micron Technology                | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24        | 9.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 5.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 4.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 3.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 3.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 3.79%   |
| Samsung NVMe SSD Controller 980                                                | 8         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 3.03%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 6         | 2.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 6         | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 2.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 1.89%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.52%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 1.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.52%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 1.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.14%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 1.14%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 1.14%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 1.14%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.14%   |
| SanDisk PC SN520 NVMe SSD                                                      | 3         | 1.14%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 1.14%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.14%   |
| Intel SSD 660P Series                                                          | 3         | 1.14%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.14%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.14%   |
| Apple ANS2 NVMe Controller                                                     | 3         | 1.14%   |
| SK hynix BC511                                                                 | 2         | 0.76%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.76%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 130       | 51.59%  |
| NVMe | 103       | 40.87%  |
| RAID | 11        | 4.37%   |
| IDE  | 8         | 3.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 168       | 79.62%  |
| AMD    | 42        | 19.91%  |
| ARM    | 1         | 0.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 2.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 2.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.37%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 2.37%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.9%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 1.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.9%    |
| Intel 12th Gen Core i5-1240P                  | 4         | 1.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.42%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.42%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.42%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.42%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.42%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 3         | 1.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.42%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 0.95%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 2         | 0.95%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.95%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.95%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 0.95%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.95%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 2         | 0.95%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.95%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.95%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 0.95%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.95%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.95%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.95%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 0.95%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.95%   |
| Intel 12th Gen Core i9-12900H                 | 2         | 0.95%   |
| Intel 11th Gen Core i7-11600H @ 2.90GHz       | 2         | 0.95%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.95%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.95%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 2         | 0.95%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 47        | 22.27%  |
| Intel Core i5        | 44        | 20.85%  |
| Other                | 30        | 14.22%  |
| Intel Core i3        | 13        | 6.16%   |
| AMD Ryzen 5          | 12        | 5.69%   |
| AMD Ryzen 7          | 11        | 5.21%   |
| Intel Core 2 Duo     | 8         | 3.79%   |
| Intel Celeron        | 8         | 3.79%   |
| Intel Pentium        | 5         | 2.37%   |
| Intel Core i9        | 4         | 1.9%    |
| Intel Atom           | 4         | 1.9%    |
| AMD Ryzen 7 PRO      | 3         | 1.42%   |
| AMD Ryzen 3          | 3         | 1.42%   |
| Intel Pentium Silver | 2         | 0.95%   |
| Intel Genuine        | 2         | 0.95%   |
| Intel Core 2         | 2         | 0.95%   |
| AMD Ryzen 9          | 2         | 0.95%   |
| AMD Ryzen 5 PRO      | 2         | 0.95%   |
| AMD A4               | 2         | 0.95%   |
| AMD A10              | 2         | 0.95%   |
| Intel Xeon           | 1         | 0.47%   |
| Intel Pentium Dual   | 1         | 0.47%   |
| AMD Quad-Core        | 1         | 0.47%   |
| AMD Athlon II        | 1         | 0.47%   |
| AMD A6               | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 81        | 38.39%  |
| 4       | 75        | 35.55%  |
| 8       | 22        | 10.43%  |
| 6       | 21        | 9.95%   |
| 12      | 7         | 3.32%   |
| 14      | 3         | 1.42%   |
| 1       | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 210       | 99.53%  |
| 2      | 1         | 0.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 173       | 81.99%  |
| 1       | 37        | 17.54%  |
| Unknown | 1         | 0.47%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 207       | 98.1%   |
| Unknown        | 2         | 0.95%   |
| 64-bit         | 1         | 0.47%   |
| 32-bit         | 1         | 0.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 12.96%  |
| 0x806ec    | 13        | 6.02%   |
| 0x806c1    | 13        | 6.02%   |
| 0x306a9    | 11        | 5.09%   |
| 0x806ea    | 9         | 4.17%   |
| 0x206a7    | 9         | 4.17%   |
| 0x906a3    | 8         | 3.7%    |
| 0x20655    | 8         | 3.7%    |
| 0x0a50000c | 8         | 3.7%    |
| 0x08600106 | 7         | 3.24%   |
| 0x806eb    | 6         | 2.78%   |
| 0x40651    | 6         | 2.78%   |
| 0x906e9    | 5         | 2.31%   |
| 0x706e5    | 5         | 2.31%   |
| 0x08108102 | 5         | 2.31%   |
| 0xa0652    | 4         | 1.85%   |
| 0x906ea    | 4         | 1.85%   |
| 0x806e9    | 4         | 1.85%   |
| 0x706a1    | 4         | 1.85%   |
| 0x306c3    | 4         | 1.85%   |
| 0x30678    | 4         | 1.85%   |
| 0x906ed    | 3         | 1.39%   |
| 0x806d1    | 3         | 1.39%   |
| 0x6fd      | 3         | 1.39%   |
| 0x406e3    | 3         | 1.39%   |
| 0x306d4    | 3         | 1.39%   |
| 0x1067a    | 3         | 1.39%   |
| 0xa0660    | 2         | 0.93%   |
| 0x6f6      | 2         | 0.93%   |
| 0x406c3    | 2         | 0.93%   |
| 0x20652    | 2         | 0.93%   |
| 0x10676    | 2         | 0.93%   |
| 0x08608103 | 2         | 0.93%   |
| 0x08600103 | 2         | 0.93%   |
| 0x0700010f | 2         | 0.93%   |
| 0x06001119 | 2         | 0.93%   |
| 0xb06a2    | 1         | 0.46%   |
| 0x906a2    | 1         | 0.46%   |
| 0x706a8    | 1         | 0.46%   |
| 0x6fb      | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 48        | 22.75%  |
| TigerLake        | 14        | 6.64%   |
| Haswell          | 14        | 6.64%   |
| Zen 2            | 13        | 6.16%   |
| Westmere         | 11        | 5.21%   |
| IvyBridge        | 11        | 5.21%   |
| SandyBridge      | 10        | 4.74%   |
| Unknown          | 10        | 4.74%   |
| Zen 3            | 9         | 4.27%   |
| IceLake          | 9         | 4.27%   |
| Silvermont       | 7         | 3.32%   |
| Zen+             | 6         | 2.84%   |
| Penryn           | 6         | 2.84%   |
| Core             | 6         | 2.84%   |
| CometLake        | 6         | 2.84%   |
| Alderlake Hybrid | 6         | 2.84%   |
| Skylake          | 5         | 2.37%   |
| Goldmont plus    | 5         | 2.37%   |
| Jaguar           | 3         | 1.42%   |
| Broadwell        | 3         | 1.42%   |
| Zen              | 2         | 0.95%   |
| Piledriver       | 2         | 0.95%   |
| P6               | 1         | 0.47%   |
| Nehalem          | 1         | 0.47%   |
| K10              | 1         | 0.47%   |
| Excavator        | 1         | 0.47%   |
| Bonnell          | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 151       | 57.2%   |
| Nvidia                           | 60        | 22.73%  |
| AMD                              | 52        | 19.7%   |
| Silicon Integrated Systems [SiS] | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 13        | 4.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 4.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 3.31%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 3.31%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 9         | 3.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.21%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 2.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.47%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.47%   |
| Intel HD Graphics 630                                                                    | 4         | 1.47%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.47%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.47%   |
| AMD Barcelo                                                                              | 4         | 1.47%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.1%    |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 1.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.1%    |
| Intel HD Graphics 620                                                                    | 3         | 1.1%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.1%    |
| Nvidia TU117M                                                                            | 2         | 0.74%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.74%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.74%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.74%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                               | 2         | 0.74%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.74%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 101       | 47.87%  |
| Intel + Nvidia | 43        | 20.38%  |
| 1 x AMD        | 39        | 18.48%  |
| 1 x Nvidia     | 12        | 5.69%   |
| Intel + AMD    | 6         | 2.84%   |
| AMD + Nvidia   | 4         | 1.9%    |
| 2 x AMD        | 3         | 1.42%   |
| Other          | 1         | 0.47%   |
| 2 x Nvidia     | 1         | 0.47%   |
| 1 x SiS        | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 172       | 80.75%  |
| Proprietary | 31        | 14.55%  |
| Unknown     | 10        | 4.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 61.4%   |
| 0.01-0.5   | 25        | 11.63%  |
| 1.01-2.0   | 20        | 9.3%    |
| 3.01-4.0   | 18        | 8.37%   |
| 0.51-1.0   | 11        | 5.12%   |
| 5.01-6.0   | 4         | 1.86%   |
| 7.01-8.0   | 3         | 1.4%    |
| 8.01-16.0  | 2         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 42        | 17.43%  |
| AU Optronics            | 39        | 16.18%  |
| BOE                     | 30        | 12.45%  |
| Samsung Electronics     | 29        | 12.03%  |
| Chimei Innolux          | 26        | 10.79%  |
| Goldstar                | 11        | 4.56%   |
| Sharp                   | 8         | 3.32%   |
| Apple                   | 8         | 3.32%   |
| Dell                    | 6         | 2.49%   |
| PANDA                   | 5         | 2.07%   |
| Lenovo                  | 5         | 2.07%   |
| JCH                     | 3         | 1.24%   |
| CPT                     | 3         | 1.24%   |
| ALP                     | 3         | 1.24%   |
| Valve                   | 2         | 0.83%   |
| Philips                 | 2         | 0.83%   |
| CSO                     | 2         | 0.83%   |
| Chi Mei Optoelectronics | 2         | 0.83%   |
| BenQ                    | 2         | 0.83%   |
| VMO                     | 1         | 0.41%   |
| TMX                     | 1         | 0.41%   |
| Sony                    | 1         | 0.41%   |
| PRISM+                  | 1         | 0.41%   |
| MSI                     | 1         | 0.41%   |
| InfoVision              | 1         | 0.41%   |
| HKC                     | 1         | 0.41%   |
| Hewlett-Packard         | 1         | 0.41%   |
| HannStar                | 1         | 0.41%   |
| Denver                  | 1         | 0.41%   |
| CM_                     | 1         | 0.41%   |
| AOC                     | 1         | 0.41%   |
| Ancor Communications    | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 1.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.63%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 1.22%   |
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 1.22%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.82%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.82%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 2         | 0.82%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 2         | 0.82%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch               | 2         | 0.82%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 2         | 0.82%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 2         | 0.82%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch          | 2         | 0.82%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch          | 2         | 0.82%   |
| LG Display LCD Monitor LGD03B5 1920x1080 294x165mm 13.3-inch          | 2         | 0.82%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.82%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 2         | 0.82%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                 | 2         | 0.82%   |
| BOE LCD Monitor BOE06D7 3840x2160 345x194mm 15.6-inch                 | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO749D 3840x2160 381x214mm 17.2-inch        | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO6A92 1920x1080 344x194mm 15.5-inch        | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 2         | 0.82%   |
| AU Optronics LCD Monitor 1920x1080                                    | 2         | 0.82%   |
| Apple Color LCD APPA044 3072x1920 345x215mm 16.0-inch                 | 2         | 0.82%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch             | 1         | 0.41%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.41%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.41%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.41%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.41%   |
| Samsung Electronics U32H85x SAM0E3A 3840x2160 697x392mm 31.5-inch     | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 117       | 51.09%  |
| 1366x768 (WXGA)    | 37        | 16.16%  |
| 3840x2160 (4K)     | 14        | 6.11%   |
| 2560x1600          | 9         | 3.93%   |
| 2560x1440 (QHD)    | 9         | 3.93%   |
| 1600x900 (HD+)     | 7         | 3.06%   |
| 1280x800 (WXGA)    | 7         | 3.06%   |
| 1920x1200 (WUXGA)  | 6         | 2.62%   |
| 2880x1800          | 4         | 1.75%   |
| 3440x1440          | 3         | 1.31%   |
| 1440x900 (WXGA+)   | 3         | 1.31%   |
| 800x1280           | 2         | 0.87%   |
| 3072x1920          | 2         | 0.87%   |
| 1680x1050 (WSXGA+) | 2         | 0.87%   |
| 1280x1024 (SXGA)   | 2         | 0.87%   |
| 3840x2400          | 1         | 0.44%   |
| 2560x1080          | 1         | 0.44%   |
| 1680x945           | 1         | 0.44%   |
| 1400x1050          | 1         | 0.44%   |
| 1024x768 (XGA)     | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 100       | 41.32%  |
| 13      | 36        | 14.88%  |
| 14      | 28        | 11.57%  |
| 17      | 11        | 4.55%   |
| 27      | 10        | 4.13%   |
| 24      | 9         | 3.72%   |
| 16      | 8         | 3.31%   |
| 23      | 7         | 2.89%   |
| 31      | 5         | 2.07%   |
| 21      | 4         | 1.65%   |
| 12      | 4         | 1.65%   |
| 34      | 3         | 1.24%   |
| 20      | 3         | 1.24%   |
| 11      | 3         | 1.24%   |
| 7       | 2         | 0.83%   |
| Unknown | 2         | 0.83%   |
| 74      | 1         | 0.41%   |
| 54      | 1         | 0.41%   |
| 40      | 1         | 0.41%   |
| 25      | 1         | 0.41%   |
| 19      | 1         | 0.41%   |
| 18      | 1         | 0.41%   |
| 10      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 145       | 60.17%  |
| 201-300     | 32        | 13.28%  |
| 501-600     | 25        | 10.37%  |
| 351-400     | 14        | 5.81%   |
| 401-500     | 9         | 3.73%   |
| 601-700     | 6         | 2.49%   |
| 701-800     | 3         | 1.24%   |
| 1-100       | 2         | 0.83%   |
| Unknown     | 2         | 0.83%   |
| 801-900     | 1         | 0.41%   |
| 1501-2000   | 1         | 0.41%   |
| 1001-1500   | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 165       | 78.57%  |
| 16/10   | 32        | 15.24%  |
| 21/9    | 3         | 1.43%   |
| 5/4     | 2         | 0.95%   |
| 4/3     | 2         | 0.95%   |
| 3/2     | 2         | 0.95%   |
| 0.67    | 2         | 0.95%   |
| Unknown | 2         | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 99        | 40.91%  |
| 81-90          | 42        | 17.36%  |
| 71-80          | 20        | 8.26%   |
| 201-250        | 17        | 7.02%   |
| 301-350        | 10        | 4.13%   |
| 121-130        | 10        | 4.13%   |
| 351-500        | 8         | 3.31%   |
| 111-120        | 7         | 2.89%   |
| 61-70          | 4         | 1.65%   |
| 251-300        | 4         | 1.65%   |
| 151-200        | 4         | 1.65%   |
| 91-100         | 4         | 1.65%   |
| 51-60          | 3         | 1.24%   |
| More than 1000 | 2         | 0.83%   |
| 1-40           | 2         | 0.83%   |
| 141-150        | 2         | 0.83%   |
| Unknown        | 2         | 0.83%   |
| 41-50          | 1         | 0.41%   |
| 501-1000       | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 104       | 43.51%  |
| 101-120       | 46        | 19.25%  |
| 51-100        | 36        | 15.06%  |
| 161-240       | 35        | 14.64%  |
| More than 240 | 14        | 5.86%   |
| 1-50          | 2         | 0.84%   |
| Unknown       | 2         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 165       | 75%     |
| 2     | 41        | 18.64%  |
| 0     | 10        | 4.55%   |
| 3     | 4         | 1.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 139       | 42.38%  |
| Realtek Semiconductor            | 106       | 32.32%  |
| Qualcomm Atheros                 | 27        | 8.23%   |
| Broadcom                         | 19        | 5.79%   |
| ASIX Electronics                 | 8         | 2.44%   |
| MediaTek                         | 4         | 1.22%   |
| Marvell Technology Group         | 3         | 0.91%   |
| Apple                            | 3         | 0.91%   |
| TP-Link                          | 2         | 0.61%   |
| Samsung Electronics              | 2         | 0.61%   |
| Ralink Technology                | 2         | 0.61%   |
| Nvidia                           | 2         | 0.61%   |
| Lenovo                           | 2         | 0.61%   |
| Broadcom Limited                 | 2         | 0.61%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 18.98%  |
| Intel Wi-Fi 6 AX200                                               | 24        | 6.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 3.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.21%   |
| Intel Wi-Fi 6 AX201                                               | 12        | 3.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 2.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 9         | 2.41%   |
| Intel Wireless 7260                                               | 8         | 2.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 2.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.6%    |
| Intel Wireless 8265 / 8275                                        | 6         | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.34%   |
| Intel Wireless 3165                                               | 5         | 1.34%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 1.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.07%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 1.07%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 4         | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.8%    |
| Intel Wireless 7265                                               | 3         | 0.8%    |
| Intel Wireless 3160                                               | 3         | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.8%    |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.8%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.8%    |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.8%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.8%    |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                | 3         | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.8%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 135       | 63.98%  |
| Realtek Semiconductor | 26        | 12.32%  |
| Qualcomm Atheros      | 21        | 9.95%   |
| Broadcom              | 16        | 7.58%   |
| MediaTek              | 4         | 1.9%    |
| TP-Link               | 2         | 0.95%   |
| Ralink Technology     | 2         | 0.95%   |
| Broadcom Limited      | 2         | 0.95%   |
| Ralink                | 1         | 0.47%   |
| Qualcomm              | 1         | 0.47%   |
| D-Link                | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 24        | 11.32%  |
| Intel Wi-Fi 6 AX201                                           | 12        | 5.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 10        | 4.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 9         | 4.25%   |
| Intel Wireless 7260                                           | 8         | 3.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 6         | 2.83%   |
| Intel Wireless 8265 / 8275                                    | 6         | 2.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 6         | 2.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 5         | 2.36%   |
| Intel Wireless 3165                                           | 5         | 2.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 5         | 2.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 5         | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 4         | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 4         | 1.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 4         | 1.89%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 4         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 4         | 1.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 3         | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 1.42%   |
| Intel Wireless 7265                                           | 3         | 1.42%   |
| Intel Wireless 3160                                           | 3         | 1.42%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 1.42%   |
| Intel Centrino Wireless-N 2230                                | 3         | 1.42%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 3         | 1.42%   |
| Intel Centrino Advanced-N 6235                                | 3         | 1.42%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 3         | 1.42%   |
| Broadcom BCM43142 802.11b/g/n                                 | 3         | 1.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 2         | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 0.94%   |
| Intel Wireless 8260                                           | 2         | 0.94%   |
| Intel WiFi Link 5100                                          | 2         | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 0.94%   |
| Intel Centrino Advanced-N 6200                                | 2         | 0.94%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller        | 2         | 0.94%   |
| Broadcom BCM43162 802.11ac Wireless Network Adapter           | 2         | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 97        | 63.4%   |
| Intel                            | 23        | 15.03%  |
| Qualcomm Atheros                 | 8         | 5.23%   |
| ASIX Electronics                 | 8         | 5.23%   |
| Marvell Technology Group         | 3         | 1.96%   |
| Broadcom                         | 3         | 1.96%   |
| Apple                            | 3         | 1.96%   |
| Samsung Electronics              | 2         | 1.31%   |
| Nvidia                           | 2         | 1.31%   |
| Lenovo                           | 2         | 1.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.65%   |
| Microsoft                        | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 71        | 44.38%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 12        | 7.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 7.5%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 8         | 5%      |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.5%    |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.88%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.25%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.25%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.25%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.25%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.25%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.25%   |
| Apple T2 Controller                                                            | 2         | 1.25%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.63%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 0.63%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.63%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.63%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.63%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.63%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.63%   |
| Intel Ethernet controller                                                      | 1         | 0.63%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.63%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.63%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.63%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.63%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.63%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.63%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 203       | 57.67%  |
| Ethernet | 147       | 41.76%  |
| Modem    | 2         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 163       | 72.12%  |
| Ethernet | 63        | 27.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 122       | 57.55%  |
| 1     | 84        | 39.62%  |
| 0     | 4         | 1.89%   |
| 3     | 2         | 0.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 209       | 99.05%  |
| Yes  | 2         | 0.95%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 64.2%   |
| Realtek Semiconductor           | 14        | 7.95%   |
| Broadcom                        | 14        | 7.95%   |
| IMC Networks                    | 11        | 6.25%   |
| Qualcomm Atheros Communications | 9         | 5.11%   |
| Foxconn / Hon Hai               | 5         | 2.84%   |
| Lite-On Technology              | 4         | 2.27%   |
| Apple                           | 4         | 2.27%   |
| Qcom                            | 1         | 0.57%   |
| Micro Star International        | 1         | 0.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 28        | 15.91%  |
| Intel AX201 Bluetooth                                                               | 25        | 14.2%   |
| Intel AX200 Bluetooth                                                               | 24        | 13.64%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 10.23%  |
| Intel Bluetooth Device                                                              | 9         | 5.11%   |
| Realtek Bluetooth Radio                                                             | 8         | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 2.84%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.27%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.27%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.27%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.27%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.7%    |
| Lite-On Bluetooth Device                                                            | 3         | 1.7%    |
| IMC Networks Wireless_Device                                                        | 3         | 1.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.7%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.14%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.14%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.14%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 1.14%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.14%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.14%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.14%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 1.14%   |
| Realtek CSR BS8510                                                                  | 1         | 0.57%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.57%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.57%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.57%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.57%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.57%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.57%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.57%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 160       | 64%     |
| AMD                              | 49        | 19.6%   |
| Nvidia                           | 28        | 11.2%   |
| JMTek                            | 3         | 1.2%    |
| Apple                            | 3         | 1.2%    |
| Lenovo                           | 2         | 0.8%    |
| Texas Instruments                | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |
| Razer USA                        | 1         | 0.4%    |
| Dell                             | 1         | 0.4%    |
| Unknown                          | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 33        | 10.78%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 23        | 7.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 17        | 5.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 4.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 3.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 3.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 3.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 3.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 3.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 2.61%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 2.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.96%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 1.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 1.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.63%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.63%   |
| Nvidia High Definition Audio Controller                                    | 4         | 1.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.31%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.31%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.31%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.98%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.98%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.98%   |
| Nvidia Audio device                                                        | 3         | 0.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.98%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 0.98%   |
| Apple Audio Device                                                         | 3         | 0.98%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 0.98%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 0.98%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.65%   |
| JMTek USB Audio Device                                                     | 2         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 76        | 51.01%  |
| SK hynix            | 29        | 19.46%  |
| Micron Technology   | 17        | 11.41%  |
| Unknown             | 7         | 4.7%    |
| Kingston            | 3         | 2.01%   |
| A-DATA Technology   | 3         | 2.01%   |
| Unknown             | 3         | 2.01%   |
| Unknown (ABCD)      | 2         | 1.34%   |
| Ramaxel Technology  | 2         | 1.34%   |
| Unknown (899D)      | 1         | 0.67%   |
| Unknown (09D5)      | 1         | 0.67%   |
| Team                | 1         | 0.67%   |
| Silicon Power       | 1         | 0.67%   |
| Imation             | 1         | 0.67%   |
| Essencore           | 1         | 0.67%   |
| Elpida              | 1         | 0.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 4.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 3.07%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 2.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.45%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.84%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 3         | 1.84%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.84%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 1.84%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.84%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.84%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.84%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.84%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.84%   |
| Samsung RAM M471A1G44AB0-CTD 8GB DDR4 2667MT/s                   | 3         | 1.84%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 1.84%   |
| Unknown                                                          | 3         | 1.84%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 1.23%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.23%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.23%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.23%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.23%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.23%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.23%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.23%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.23%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DDR4 2667MT/s                   | 2         | 1.23%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 2         | 1.23%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.23%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.61%   |
| Unknown RAM CL22-22-22 D4-3200 16384MB SODIMM DDR4 3200MT/s      | 1         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.61%   |
| Unknown (899D) RAM TZD2G0816S32-SK001 16GB SODIMM DDR4 2133MT/s  | 1         | 0.61%   |
| Unknown (09D5) RAM Module 16384MB SODIMM DDR4 2400MT/s           | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 74        | 58.73%  |
| DDR3    | 26        | 20.63%  |
| LPDDR4  | 10        | 7.94%   |
| LPDDR3  | 6         | 4.76%   |
| DDR2    | 3         | 2.38%   |
| SDRAM   | 2         | 1.59%   |
| LPDDR5  | 2         | 1.59%   |
| DDR5    | 2         | 1.59%   |
| Unknown | 1         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 99        | 77.34%  |
| Row Of Chips | 21        | 16.41%  |
| Unknown      | 5         | 3.91%   |
| DIMM         | 3         | 2.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 62        | 45.59%  |
| 4096  | 32        | 23.53%  |
| 16384 | 20        | 14.71%  |
| 2048  | 13        | 9.56%   |
| 32768 | 7         | 5.15%   |
| 1024  | 2         | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 35        | 25.55%  |
| 2667    | 33        | 24.09%  |
| 1600    | 16        | 11.68%  |
| 2400    | 12        | 8.76%   |
| 2133    | 9         | 6.57%   |
| 4267    | 5         | 3.65%   |
| 3266    | 5         | 3.65%   |
| 1334    | 5         | 3.65%   |
| 4800    | 3         | 2.19%   |
| 6400    | 2         | 1.46%   |
| 1333    | 2         | 1.46%   |
| 1067    | 2         | 1.46%   |
| 8400    | 1         | 0.73%   |
| 4266    | 1         | 0.73%   |
| 4199    | 1         | 0.73%   |
| 2048    | 1         | 0.73%   |
| 1867    | 1         | 0.73%   |
| 800     | 1         | 0.73%   |
| 667     | 1         | 0.73%   |
| Unknown | 1         | 0.73%   |

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
| Chicony Electronics                    | 34        | 19.32%  |
| IMC Networks                           | 28        | 15.91%  |
| Acer                                   | 20        | 11.36%  |
| Realtek Semiconductor                  | 13        | 7.39%   |
| Microdia                               | 12        | 6.82%   |
| Silicon Motion                         | 11        | 6.25%   |
| Quanta                                 | 8         | 4.55%   |
| Apple                                  | 7         | 3.98%   |
| Unknown                                | 6         | 3.41%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.41%   |
| Syntek                                 | 5         | 2.84%   |
| Suyin                                  | 5         | 2.84%   |
| SunplusIT                              | 5         | 2.84%   |
| Sunplus Innovation Technology          | 3         | 1.7%    |
| Luxvisions Innotech Limited            | 3         | 1.7%    |
| Z-Star Microelectronics                | 2         | 1.14%   |
| Lenovo                                 | 2         | 1.14%   |
| SJ-180517-N                            | 1         | 0.57%   |
| Microsoft                              | 1         | 0.57%   |
| Logitech                               | 1         | 0.57%   |
| Goodong Industry                       | 1         | 0.57%   |
| DigiTech                               | 1         | 0.57%   |
| Alcor Micro                            | 1         | 0.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 10        | 5.62%   |
| IMC Networks Integrated Camera                          | 9         | 5.06%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 8         | 4.49%   |
| Microdia Integrated_Webcam_HD                           | 7         | 3.93%   |
| Unknown 720p HD Camera                                  | 6         | 3.37%   |
| Chicony HD WebCam                                       | 6         | 3.37%   |
| Realtek LG Camera                                       | 5         | 2.81%   |
| Acer HD Webcam                                          | 5         | 2.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 4         | 2.25%   |
| Acer Integrated Camera                                  | 4         | 2.25%   |
| Syntek Integrated Camera                                | 3         | 1.69%   |
| Suyin HP Truevision HD                                  | 3         | 1.69%   |
| SunplusIT 1080p FHD Camera                              | 3         | 1.69%   |
| Silicon Motion LG HD WebCam                             | 3         | 1.69%   |
| Quanta HP TrueVision HD Camera                          | 3         | 1.69%   |
| Chicony LG Camera                                       | 3         | 1.69%   |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 1.69%   |
| Z-Star Webcam                                           | 2         | 1.12%   |
| SunplusIT 720p HD Camera                                | 2         | 1.12%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 2         | 1.12%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.12%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.12%   |
| Quanta LG Webcam                                        | 2         | 1.12%   |
| IMC Networks USB HD Webcam                              | 2         | 1.12%   |
| IMC Networks Integrated RGB Camera                      | 2         | 1.12%   |
| Chicony USB 2.0 Camera                                  | 2         | 1.12%   |
| Chicony LG HD WebCam                                    | 2         | 1.12%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.12%   |
| Apple iPhone 5/5C/5S/6/SE                               | 2         | 1.12%   |
| Apple Built-in iSight                                   | 2         | 1.12%   |
| Acer Lenovo EasyCamera                                  | 2         | 1.12%   |
| Acer BisonCam,NB Pro                                    | 2         | 1.12%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.56%   |
| Syntek HP Webcam                                        | 1         | 0.56%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.56%   |
| Suyin HP TrueVision Full HD                             | 1         | 0.56%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.56%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.56%   |
| Sunplus Asus Webcam                                     | 1         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 14        | 29.79%  |
| Validity Sensors                   | 9         | 19.15%  |
| Samsung Electronics                | 6         | 12.77%  |
| Upek                               | 4         | 8.51%   |
| Shenzhen Goodix Technology         | 4         | 8.51%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 6.38%   |
| STMicroelectronics                 | 2         | 4.26%   |
| LighTuning Technology              | 2         | 4.26%   |
| Elan Microelectronics              | 2         | 4.26%   |
| AuthenTec                          | 1         | 2.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown                                                         | 7         | 14.89%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 8.51%   |
| Samsung Fingerprint Sensor Device - 730B                        | 4         | 8.51%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 6.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 4.26%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 4.26%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 2         | 4.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 4.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 4.26%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 4.26%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 4.26%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 4.26%   |
| Samsung Fingerprint Device                                      | 2         | 4.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 4.26%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 1         | 2.13%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 2.13%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 2.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 2.13%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.13%   |
| Synaptics WBDI Device                                           | 1         | 2.13%   |
| Elan ELAN:Fingerprint                                           | 1         | 2.13%   |
| Elan ELAN:ARM-M4                                                | 1         | 2.13%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 2.13%   |

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
| 0     | 125       | 57.87%  |
| 1     | 75        | 34.72%  |
| 2     | 12        | 5.56%   |
| 3     | 4         | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 47        | 43.52%  |
| Graphics card         | 26        | 24.07%  |
| Net/wireless          | 16        | 14.81%  |
| Chipcard              | 7         | 6.48%   |
| Multimedia controller | 5         | 4.63%   |
| Bluetooth             | 3         | 2.78%   |
| Sound                 | 2         | 1.85%   |
| Net/ethernet          | 2         | 1.85%   |

