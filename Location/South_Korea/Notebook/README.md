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

Total: 291

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 44        | 20.75%  |
| Ubuntu 18.04       | 18        | 8.49%   |
| Ubuntu 22.04       | 14        | 6.6%    |
| Ubuntu 21.10       | 7         | 3.3%    |
| Gooroom            | 7         | 3.3%    |
| Debian 11          | 7         | 3.3%    |
| Arch               | 6         | 2.83%   |
| Arch Rolling       | 5         | 2.36%   |
| Linux Mint 20.3    | 4         | 1.89%   |
| Linux Mint 20.1    | 4         | 1.89%   |
| Fedora 36          | 4         | 1.89%   |
| Fedora 32          | 4         | 1.89%   |
| Ubuntu 19.10       | 3         | 1.42%   |
| Ubuntu 19.04       | 3         | 1.42%   |
| ROSA R11           | 3         | 1.42%   |
| OpenMandriva 4.2   | 3         | 1.42%   |
| HamoniKR 4.0       | 3         | 1.42%   |
| Fedora 34          | 3         | 1.42%   |
| Debian 10          | 3         | 1.42%   |
| CentOS 8           | 3         | 1.42%   |
| Zorin 15           | 2         | 0.94%   |
| Ubuntu MATE 18.04  | 2         | 0.94%   |
| ROSA R10           | 2         | 0.94%   |
| Pop!_OS 21.10      | 2         | 0.94%   |
| Manjaro 21.3.0     | 2         | 0.94%   |
| LMDE 5             | 2         | 0.94%   |
| Linux Mint 20      | 2         | 0.94%   |
| Kubuntu 22.04      | 2         | 0.94%   |
| KDE neon 20.04     | 2         | 0.94%   |
| Endless 3.8.5      | 2         | 0.94%   |
| Zorin 16           | 1         | 0.47%   |
| Xubuntu 20.04      | 1         | 0.47%   |
| Ubuntu Unity 18.04 | 1         | 0.47%   |
| Ubuntu Unity 16.04 | 1         | 0.47%   |
| Ubuntu 22.10       | 1         | 0.47%   |
| Ubuntu 21.04       | 1         | 0.47%   |
| Ubuntu 20.10       | 1         | 0.47%   |
| SteamOS 3.4        | 1         | 0.47%   |
| Pop!_OS 22.04      | 1         | 0.47%   |
| Pop!_OS 21.04      | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 90        | 43.9%   |
| Linux Mint   | 13        | 6.34%   |
| Fedora       | 13        | 6.34%   |
| Debian       | 10        | 4.88%   |
| Manjaro      | 9         | 4.39%   |
| Arch         | 9         | 4.39%   |
| Gooroom      | 8         | 3.9%    |
| ROSA         | 5         | 2.44%   |
| OpenMandriva | 5         | 2.44%   |
| Endless      | 5         | 2.44%   |
| Pop!_OS      | 4         | 1.95%   |
| Kubuntu      | 4         | 1.95%   |
| HamoniKR     | 4         | 1.95%   |
| CentOS       | 4         | 1.95%   |
| Zorin        | 3         | 1.46%   |
| No1          | 3         | 1.46%   |
| Ubuntu Unity | 2         | 0.98%   |
| Ubuntu MATE  | 2         | 0.98%   |
| LMDE         | 2         | 0.98%   |
| KDE neon     | 2         | 0.98%   |
| EndeavourOS  | 2         | 0.98%   |
| Xubuntu      | 1         | 0.49%   |
| SteamOS      | 1         | 0.49%   |
| openSUSE     | 1         | 0.49%   |
| Lubuntu      | 1         | 0.49%   |
| Gentoo       | 1         | 0.49%   |
| Garuda Linux | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.15.0-53-generic               | 5         | 2.23%   |
| 5.10.0-19-amd64                 | 5         | 2.23%   |
| 5.4.0-42-generic                | 4         | 1.79%   |
| 5.10.0-17-amd64                 | 4         | 1.79%   |
| 5.4.0-58-generic                | 3         | 1.34%   |
| 5.4.0-26-generic                | 3         | 1.34%   |
| 5.3.0-40-generic                | 3         | 1.34%   |
| 5.19.15-201.fc36.x86_64         | 3         | 1.34%   |
| 5.13.0-28-generic               | 3         | 1.34%   |
| 5.11.0-37-generic               | 3         | 1.34%   |
| 4.19.0-9-amd64                  | 3         | 1.34%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3         | 1.34%   |
| 5.8.4-200.fc32.x86_64           | 2         | 0.89%   |
| 5.8.0-53-generic                | 2         | 0.89%   |
| 5.8.0-43-generic                | 2         | 0.89%   |
| 5.4.0-81-generic                | 2         | 0.89%   |
| 5.4.0-56-generic                | 2         | 0.89%   |
| 5.4.0-48-generic                | 2         | 0.89%   |
| 5.4.0-39-generic                | 2         | 0.89%   |
| 5.4.0-33-generic                | 2         | 0.89%   |
| 5.4.0-31-generic                | 2         | 0.89%   |
| 5.4.0-29-generic                | 2         | 0.89%   |
| 5.3.0-46-generic                | 2         | 0.89%   |
| 5.18.5-1-MANJARO                | 2         | 0.89%   |
| 5.15.0-56-generic               | 2         | 0.89%   |
| 5.15.0-52-generic               | 2         | 0.89%   |
| 5.15.0-33-generic               | 2         | 0.89%   |
| 5.15.0-27-generic               | 2         | 0.89%   |
| 5.13.0-44-generic               | 2         | 0.89%   |
| 5.13.0-27-generic               | 2         | 0.89%   |
| 5.10.14-desktop-1omv4002        | 2         | 0.89%   |
| 5.0.0-37-generic                | 2         | 0.89%   |
| 5.0.0-25-generic                | 2         | 0.89%   |
| 5.0.0-13-generic                | 2         | 0.89%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.89%   |
| 4.18.0-17-generic               | 2         | 0.89%   |
| 4.15.0-112-generic              | 2         | 0.89%   |
| 6.1.0-060100rc1-generic         | 1         | 0.45%   |
| 6.0.9-060009-generic            | 1         | 0.45%   |
| 6.0.6-Wataten-T2-xanmod1-1      | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 45        | 20.74%  |
| 5.15.0  | 17        | 7.83%   |
| 5.13.0  | 14        | 6.45%   |
| 5.10.0  | 12        | 5.53%   |
| 5.8.0   | 11        | 5.07%   |
| 5.11.0  | 10        | 4.61%   |
| 4.15.0  | 10        | 4.61%   |
| 5.3.0   | 9         | 4.15%   |
| 5.0.0   | 7         | 3.23%   |
| 4.18.0  | 7         | 3.23%   |
| 4.19.0  | 6         | 2.76%   |
| 5.19.15 | 3         | 1.38%   |
| 6.0.0   | 2         | 0.92%   |
| 5.8.4   | 2         | 0.92%   |
| 5.18.5  | 2         | 0.92%   |
| 5.16.19 | 2         | 0.92%   |
| 5.15.11 | 2         | 0.92%   |
| 5.14.0  | 2         | 0.92%   |
| 5.10.14 | 2         | 0.92%   |
| 4.9.60  | 2         | 0.92%   |
| 6.1.0   | 1         | 0.46%   |
| 6.0.9   | 1         | 0.46%   |
| 6.0.6   | 1         | 0.46%   |
| 6.0.2   | 1         | 0.46%   |
| 6.0.14  | 1         | 0.46%   |
| 5.9.9   | 1         | 0.46%   |
| 5.8.18  | 1         | 0.46%   |
| 5.8.15  | 1         | 0.46%   |
| 5.7.17  | 1         | 0.46%   |
| 5.6.11  | 1         | 0.46%   |
| 5.6.0   | 1         | 0.46%   |
| 5.5.2   | 1         | 0.46%   |
| 5.4.61  | 1         | 0.46%   |
| 5.4.55  | 1         | 0.46%   |
| 5.3.7   | 1         | 0.46%   |
| 5.2.11  | 1         | 0.46%   |
| 5.19.11 | 1         | 0.46%   |
| 5.19.0  | 1         | 0.46%   |
| 5.18.17 | 1         | 0.46%   |
| 5.17.2  | 1         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 47        | 21.76%  |
| 5.15    | 25        | 11.57%  |
| 5.10    | 16        | 7.41%   |
| 5.8     | 15        | 6.94%   |
| 5.13    | 15        | 6.94%   |
| 5.11    | 15        | 6.94%   |
| 4.15    | 11        | 5.09%   |
| 5.3     | 10        | 4.63%   |
| 4.18    | 8         | 3.7%    |
| 5.0     | 7         | 3.24%   |
| 4.19    | 7         | 3.24%   |
| 6.0     | 6         | 2.78%   |
| 5.19    | 5         | 2.31%   |
| 5.16    | 5         | 2.31%   |
| 5.12    | 5         | 2.31%   |
| 5.14    | 4         | 1.85%   |
| 5.18    | 3         | 1.39%   |
| 5.6     | 2         | 0.93%   |
| 4.9     | 2         | 0.93%   |
| 6.1     | 1         | 0.46%   |
| 5.9     | 1         | 0.46%   |
| 5.7     | 1         | 0.46%   |
| 5.5     | 1         | 0.46%   |
| 5.2     | 1         | 0.46%   |
| 5.17    | 1         | 0.46%   |
| 4.16    | 1         | 0.46%   |
| 3.10    | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 195       | 97.99%  |
| i686    | 3         | 1.51%   |
| aarch64 | 1         | 0.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 108       | 52.68%  |
| KDE5            | 25        | 12.2%   |
| Unknown         | 17        | 8.29%   |
| X-Cinnamon      | 12        | 5.85%   |
| LXDE            | 8         | 3.9%    |
| GNOME Flashback | 8         | 3.9%    |
| XFCE            | 7         | 3.41%   |
| Cinnamon        | 6         | 2.93%   |
| KDE4            | 3         | 1.46%   |
| KDE             | 3         | 1.46%   |
| i3              | 3         | 1.46%   |
| Unity           | 2         | 0.98%   |
| MATE            | 2         | 0.98%   |
| sway            | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 142       | 70.65%  |
| Wayland | 38        | 18.91%  |
| Unknown | 13        | 6.47%   |
| Tty     | 8         | 3.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 96        | 46.6%   |
| GDM     | 41        | 19.9%   |
| SDDM    | 20        | 9.71%   |
| GDM3    | 17        | 8.25%   |
| LightDM | 15        | 7.28%   |
| TDM     | 13        | 6.31%   |
| KDM     | 3         | 1.46%   |
| XDM     | 1         | 0.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ko_KR   | 96        | 46.83%  |
| en_US   | 68        | 33.17%  |
| Unknown | 25        | 12.2%   |
| en_CA   | 4         | 1.95%   |
| zh_CN   | 3         | 1.46%   |
| id_ID   | 2         | 0.98%   |
| C       | 2         | 0.98%   |
| vi_VN   | 1         | 0.49%   |
| pt_BR   | 1         | 0.49%   |
| fr_FR   | 1         | 0.49%   |
| en_NZ   | 1         | 0.49%   |
| ar_EG   | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 140       | 70%     |
| BIOS | 60        | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 167       | 83.08%  |
| Btrfs   | 13        | 6.47%   |
| Xfs     | 6         | 2.99%   |
| Overlay | 6         | 2.99%   |
| Unknown | 6         | 2.99%   |
| Zfs     | 3         | 1.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 97        | 47.78%  |
| Unknown | 92        | 45.32%  |
| MBR     | 14        | 6.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 188       | 94%     |
| Yes       | 12        | 6%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 136       | 67.33%  |
| Yes       | 66        | 32.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 44        | 22.11%  |
| Samsung Electronics | 24        | 12.06%  |
| Hewlett-Packard     | 22        | 11.06%  |
| LG Electronics      | 21        | 10.55%  |
| ASUSTek Computer    | 19        | 9.55%   |
| Dell                | 15        | 7.54%   |
| MSI                 | 11        | 5.53%   |
| Apple               | 8         | 4.02%   |
| HANSUNG COMPUTER    | 4         | 2.01%   |
| Notebook            | 3         | 1.51%   |
| Acer                | 3         | 1.51%   |
| Toshiba             | 2         | 1.01%   |
| Razer               | 2         | 1.01%   |
| Google              | 2         | 1.01%   |
| Wolfnfox            | 1         | 0.5%    |
| Valve               | 1         | 0.5%    |
| TG                  | 1         | 0.5%    |
| Teclast             | 1         | 0.5%    |
| Sony                | 1         | 0.5%    |
| SLIMBOOK            | 1         | 0.5%    |
| Pine Microsystems   | 1         | 0.5%    |
| MS                  | 1         | 0.5%    |
| MECHREVO            | 1         | 0.5%    |
| Jooyontech Computer | 1         | 0.5%    |
| Jooyon Tech         | 1         | 0.5%    |
| Intel               | 1         | 0.5%    |
| IMUZ                | 1         | 0.5%    |
| Gigabyte Technology | 1         | 0.5%    |
| Clevo               | 1         | 0.5%    |
| AVERATEC            | 1         | 0.5%    |
| AMI                 | 1         | 0.5%    |
| Alienware           | 1         | 0.5%    |
| Unknown             | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung 950XED                                    | 3         | 1.51%   |
| Samsung 950XCJ/951XCJ/950XCR                      | 3         | 1.51%   |
| Razer Blade 17 (2022) - RZ09-0423                 | 2         | 1.01%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01S00              | 2         | 1.01%   |
| Lenovo IdeaPad 3 15IIL05 81WE                     | 2         | 1.01%   |
| HP Stream Notebook PC 13                          | 2         | 1.01%   |
| HP Laptop 15-db1xxx                               | 2         | 1.01%   |
| HANSUNG COMPUTER TFX5470H                         | 2         | 1.01%   |
| Dell XPS 15 7590                                  | 2         | 1.01%   |
| Dell Inspiron 15 5510                             | 2         | 1.01%   |
| Apple MacBookPro16,1                              | 2         | 1.01%   |
| Wolfnfox WF-TBAT                                  | 1         | 0.5%    |
| Valve Jupiter                                     | 1         | 0.5%    |
| Toshiba Satellite P50-B-103                       | 1         | 0.5%    |
| Toshiba Satellite L655                            | 1         | 0.5%    |
| TG NXI-A7000 Series                               | 1         | 0.5%    |
| Teclast tPAD                                      | 1         | 0.5%    |
| Sony VPCEA36FK                                    | 1         | 0.5%    |
| SLIMBOOK PROX15-AMD                               | 1         | 0.5%    |
| Samsung X120/X170/X171                            | 1         | 0.5%    |
| Samsung SX11S                                     | 1         | 0.5%    |
| Samsung RC420/RC520/RC720                         | 1         | 0.5%    |
| Samsung R59P/R60P/R61P                            | 1         | 0.5%    |
| Samsung R440/R480                                 | 1         | 0.5%    |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.5%    |
| Samsung 905S3G/906S3G/915S3G                      | 1         | 0.5%    |
| Samsung 800G5M/800G5W                             | 1         | 0.5%    |
| Samsung 760XBE                                    | 1         | 0.5%    |
| Samsung 730QCJ/730QCR                             | 1         | 0.5%    |
| Samsung 670Z5E                                    | 1         | 0.5%    |
| Samsung 570Z5E/580Z5E                             | 1         | 0.5%    |
| Samsung 550XED                                    | 1         | 0.5%    |
| Samsung 530U3BI/530U4BI/530U4BH                   | 1         | 0.5%    |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.5%    |
| Samsung 400B4C/400B5C/200B4C/200B5C               | 1         | 0.5%    |
| Samsung 400B4B/400B5B/200B4B/200B5B               | 1         | 0.5%    |
| Samsung 270E5J/2570EJ                             | 1         | 0.5%    |
| Pine Microsystems Pine64 Pinebook Pro             | 1         | 0.5%    |
| Notebook W330SU2                                  | 1         | 0.5%    |
| Notebook NL5xRU                                   | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 31        | 15.58%  |
| Lenovo IdeaPad            | 8         | 4.02%   |
| ASUS VivoBook             | 8         | 4.02%   |
| HP Pavilion               | 7         | 3.52%   |
| Dell Inspiron             | 5         | 2.51%   |
| HP Laptop                 | 4         | 2.01%   |
| HP EliteBook              | 4         | 2.01%   |
| Dell XPS                  | 4         | 2.01%   |
| Samsung 950XED            | 3         | 1.51%   |
| Samsung 950XCJ            | 3         | 1.51%   |
| HP Stream                 | 3         | 1.51%   |
| Dell Latitude             | 3         | 1.51%   |
| Toshiba Satellite         | 2         | 1.01%   |
| Razer Blade               | 2         | 1.01%   |
| MSI Prestige              | 2         | 1.01%   |
| HP ProBook                | 2         | 1.01%   |
| HANSUNG COMPUTER TFX5470H | 2         | 1.01%   |
| ASUS TUF                  | 2         | 1.01%   |
| ASUS ROG                  | 2         | 1.01%   |
| Apple MacBookPro5         | 2         | 1.01%   |
| Apple MacBookPro16        | 2         | 1.01%   |
| Acer Swift                | 2         | 1.01%   |
| Wolfnfox WF-TBAT          | 1         | 0.5%    |
| Valve Jupiter             | 1         | 0.5%    |
| TG NXI-A7000              | 1         | 0.5%    |
| Teclast tPAD              | 1         | 0.5%    |
| Sony VPCEA36FK            | 1         | 0.5%    |
| SLIMBOOK PROX15-AMD       | 1         | 0.5%    |
| Samsung X120              | 1         | 0.5%    |
| Samsung SX11S             | 1         | 0.5%    |
| Samsung RC420             | 1         | 0.5%    |
| Samsung R59P              | 1         | 0.5%    |
| Samsung R440              | 1         | 0.5%    |
| Samsung 950XDB            | 1         | 0.5%    |
| Samsung 905S3G            | 1         | 0.5%    |
| Samsung 800G5M            | 1         | 0.5%    |
| Samsung 760XBE            | 1         | 0.5%    |
| Samsung 730QCJ            | 1         | 0.5%    |
| Samsung 670Z5E            | 1         | 0.5%    |
| Samsung 570Z5E            | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 38        | 19.1%   |
| 2021    | 22        | 11.06%  |
| 2019    | 22        | 11.06%  |
| 2018    | 18        | 9.05%   |
| 2014    | 15        | 7.54%   |
| 2013    | 15        | 7.54%   |
| 2022    | 13        | 6.53%   |
| 2011    | 11        | 5.53%   |
| 2010    | 8         | 4.02%   |
| 2008    | 7         | 3.52%   |
| 2015    | 6         | 3.02%   |
| 2016    | 5         | 2.51%   |
| 2012    | 5         | 2.51%   |
| 2017    | 4         | 2.01%   |
| 2009    | 4         | 2.01%   |
| 2007    | 3         | 1.51%   |
| 2006    | 2         | 1.01%   |
| Unknown | 1         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 199       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 179       | 89.05%  |
| Enabled  | 22        | 10.95%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 197       | 98.99%  |
| Yes  | 2         | 1.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 51        | 25.25%  |
| 16.01-24.0  | 41        | 20.3%   |
| 8.01-16.0   | 35        | 17.33%  |
| 3.01-4.0    | 34        | 16.83%  |
| 32.01-64.0  | 17        | 8.42%   |
| 1.01-2.0    | 13        | 6.44%   |
| 64.01-256.0 | 7         | 3.47%   |
| 24.01-32.0  | 3         | 1.49%   |
| 2.01-3.0    | 1         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 69        | 31.8%   |
| 2.01-3.0   | 50        | 23.04%  |
| 4.01-8.0   | 34        | 15.67%  |
| 3.01-4.0   | 33        | 15.21%  |
| 0.51-1.0   | 17        | 7.83%   |
| 8.01-16.0  | 10        | 4.61%   |
| 16.01-24.0 | 3         | 1.38%   |
| 0.01-0.5   | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 128       | 62.75%  |
| 2      | 65        | 31.86%  |
| 3      | 9         | 4.41%   |
| 4      | 1         | 0.49%   |
| 0      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 167       | 83.92%  |
| Yes       | 32        | 16.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 70.15%  |
| No        | 60        | 29.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 190       | 95.48%  |
| No        | 9         | 4.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 165       | 82.5%   |
| No        | 35        | 17.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| South Korea | 199       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Seoul           | 33        | 15.87%  |
| Seocho-gu       | 13        | 6.25%   |
| Suwon           | 9         | 4.33%   |
| Uiwang          | 7         | 3.37%   |
| Gwanak-gu       | 7         | 3.37%   |
| Jung-gu         | 6         | 2.88%   |
| Yongin-si       | 5         | 2.4%    |
| Seongnam-si     | 5         | 2.4%    |
| Hwaseong-si     | 5         | 2.4%    |
| Yongsan-gu      | 4         | 1.92%   |
| Seongbuk-gu     | 4         | 1.92%   |
| Incheon         | 4         | 1.92%   |
| Daejeon         | 4         | 1.92%   |
| Busan           | 4         | 1.92%   |
| Bupyeong-gu     | 4         | 1.92%   |
| Anyang-si       | 4         | 1.92%   |
| Pyeongtaek-si   | 3         | 1.44%   |
| Jeonju          | 3         | 1.44%   |
| Gwangju         | 3         | 1.44%   |
| Geumjeong-gu    | 3         | 1.44%   |
| Gangseo-gu      | 3         | 1.44%   |
| Gangnam-gu      | 3         | 1.44%   |
| Daegu           | 3         | 1.44%   |
| Yuseong-gu      | 2         | 0.96%   |
| Yeonsu-gu       | 2         | 0.96%   |
| Siheung-si      | 2         | 0.96%   |
| Namdong-gu      | 2         | 0.96%   |
| Nam-gu          | 2         | 0.96%   |
| Jeju City       | 2         | 0.96%   |
| Gyeongsan-si    | 2         | 0.96%   |
| Gimpo-si        | 2         | 0.96%   |
| Danyang-gun     | 2         | 0.96%   |
| Cheongju-si     | 2         | 0.96%   |
| Changwon        | 2         | 0.96%   |
| Buk-gu          | 2         | 0.96%   |
| Yuseong         | 1         | 0.48%   |
| Yongsan-dong    | 1         | 0.48%   |
| Yeongdeungpo-gu | 1         | 0.48%   |
| Yangju          | 1         | 0.48%   |
| Yangcheon-gu    | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 68        | 83     | 25.66%  |
| WDC                            | 28        | 30     | 10.57%  |
| SK hynix                       | 19        | 25     | 7.17%   |
| SanDisk                        | 19        | 19     | 7.17%   |
| Unknown                        | 18        | 22     | 6.79%   |
| Seagate                        | 14        | 17     | 5.28%   |
| Toshiba                        | 13        | 15     | 4.91%   |
| Crucial                        | 12        | 13     | 4.53%   |
| Kingston                       | 7         | 8      | 2.64%   |
| Intel                          | 7         | 12     | 2.64%   |
| Phison                         | 5         | 6      | 1.89%   |
| Hitachi                        | 5         | 6      | 1.89%   |
| Apple                          | 5         | 5      | 1.89%   |
| A-DATA Technology              | 5         | 5      | 1.89%   |
| Micron Technology              | 4         | 5      | 1.51%   |
| TAMMUZ                         | 3         | 5      | 1.13%   |
| HGST                           | 3         | 4      | 1.13%   |
| Team                           | 2         | 2      | 0.75%   |
| JMicron Technology             | 2         | 2      | 0.75%   |
| Fujitsu                        | 2         | 2      | 0.75%   |
| ZTC                            | 1         | 1      | 0.38%   |
| XPG                            | 1         | 1      | 0.38%   |
| VIVA300s                       | 1         | 1      | 0.38%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.38%   |
| UMIS                           | 1         | 1      | 0.38%   |
| TYPEC 1T                       | 1         | 1      | 0.38%   |
| Transcend                      | 1         | 2      | 0.38%   |
| Solid State Storage Technology | 1         | 1      | 0.38%   |
| Silicon Motion                 | 1         | 1      | 0.38%   |
| RevuAhn                        | 1         | 1      | 0.38%   |
| Plextor                        | 1         | 1      | 0.38%   |
| Phison Electronics             | 1         | 1      | 0.38%   |
| O2 Micro                       | 1         | 1      | 0.38%   |
| LITEONIT                       | 1         | 1      | 0.38%   |
| KIOXIA                         | 1         | 1      | 0.38%   |
| KingSpec                       | 1         | 1      | 0.38%   |
| ipTIME                         | 1         | 1      | 0.38%   |
| IPLEX                          | 1         | 1      | 0.38%   |
| Imation                        | 1         | 1      | 0.38%   |
| External                       | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| SK hynix SHGP31-1000GM-2 1TB                       | 4         | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 3         | 1.06%   |
| Samsung SSD 980 PRO 2TB                            | 3         | 1.06%   |
| Samsung SSD 860 EVO 500GB                          | 3         | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 3         | 1.06%   |
| WDC WDS100T2B0C-00PXH0 1TB                         | 2         | 0.71%   |
| WDC WD50 00LPVX-22V0TT0 500GB                      | 2         | 0.71%   |
| Unknown SLD64G  64GB                               | 2         | 0.71%   |
| Unknown SD/MMC/MS PRO 64GB                         | 2         | 0.71%   |
| Unknown MMC Card  32GB                             | 2         | 0.71%   |
| Toshiba KBG30ZMV256G 256GB                         | 2         | 0.71%   |
| SK hynix SHGP31-1000GM 1TB                         | 2         | 0.71%   |
| SK hynix NVMe SSD Drive 256GB                      | 2         | 0.71%   |
| Seagate ST1000LM048-2E7172 1TB                     | 2         | 0.71%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 0.71%   |
| SanDisk SD8SBAT256G1122 256GB SSD                  | 2         | 0.71%   |
| SanDisk NVMe SSD Drive 512GB                       | 2         | 0.71%   |
| SanDisk NVMe SSD Drive 256GB                       | 2         | 0.71%   |
| Samsung SSD 860 EVO 1TB                            | 2         | 0.71%   |
| Samsung SSD 830 Series 256GB                       | 2         | 0.71%   |
| Samsung SSD 750 EVO 120GB                          | 2         | 0.71%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB             | 2         | 0.71%   |
| Samsung PSSD T7 2TB                                | 2         | 0.71%   |
| Samsung NVMe SSD Drive 2TB                         | 2         | 0.71%   |
| Samsung MZVLB512HAJQ-00000 512GB                   | 2         | 0.71%   |
| Samsung MZVLB256HBHQ-000 256GB                     | 2         | 0.71%   |
| Samsung MZVL21T0HCLR-00B00 1TB                     | 2         | 0.71%   |
| Samsung MZNLN256HAJQ-00000 256GB SSD               | 2         | 0.71%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD               | 2         | 0.71%   |
| Kingston OM8PCP3512F-AB 512GB                      | 2         | 0.71%   |
| JMicron Tech 250GB                                 | 2         | 0.71%   |
| HGST HTS721010A9E630 1TB                           | 2         | 0.71%   |
| Crucial CT500MX500SSD1 500GB                       | 2         | 0.71%   |
| Crucial CT1000MX500SSD1 1TB                        | 2         | 0.71%   |
| Apple ANS2 NVMe Controller 121GB                   | 2         | 0.71%   |
| ZTC SM201-256G SSD                                 | 1         | 0.35%   |
| XPG GAMMIX S11 Pro 512GB                           | 1         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.35%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                   | 1         | 0.35%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 13     | 28.26%  |
| Seagate             | 13        | 16     | 28.26%  |
| Toshiba             | 6         | 6      | 13.04%  |
| Hitachi             | 5         | 6      | 10.87%  |
| HGST                | 3         | 4      | 6.52%   |
| Unknown             | 2         | 2      | 4.35%   |
| Fujitsu             | 2         | 2      | 4.35%   |
| Samsung Electronics | 1         | 1      | 2.17%   |
| ipTIME              | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 42     | 38.54%  |
| SanDisk             | 11        | 11     | 11.46%  |
| Crucial             | 11        | 12     | 11.46%  |
| SK hynix            | 4         | 4      | 4.17%   |
| WDC                 | 3         | 4      | 3.13%   |
| TAMMUZ              | 3         | 5      | 3.13%   |
| Micron Technology   | 3         | 4      | 3.13%   |
| Kingston            | 3         | 4      | 3.13%   |
| Intel               | 3         | 4      | 3.13%   |
| Team                | 2         | 2      | 2.08%   |
| Apple               | 2         | 2      | 2.08%   |
| A-DATA Technology   | 2         | 2      | 2.08%   |
| ZTC                 | 1         | 1      | 1.04%   |
| TYPEC 1T            | 1         | 1      | 1.04%   |
| Transcend           | 1         | 2      | 1.04%   |
| Toshiba             | 1         | 1      | 1.04%   |
| RevuAhn             | 1         | 1      | 1.04%   |
| Plextor             | 1         | 1      | 1.04%   |
| LITEONIT            | 1         | 1      | 1.04%   |
| KingSpec            | 1         | 1      | 1.04%   |
| IPLEX               | 1         | 1      | 1.04%   |
| China               | 1         | 1      | 1.04%   |
| Biostar             | 1         | 1      | 1.04%   |
| Apacer              | 1         | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 94        | 125    | 37.45%  |
| SSD     | 90        | 109    | 35.86%  |
| HDD     | 46        | 51     | 18.33%  |
| MMC     | 16        | 20     | 6.37%   |
| Unknown | 5         | 6      | 1.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 109       | 149    | 46.58%  |
| NVMe | 94        | 125    | 40.17%  |
| MMC  | 16        | 20     | 6.84%   |
| SAS  | 15        | 17     | 6.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 90        | 113    | 68.18%  |
| 0.51-1.0   | 36        | 39     | 27.27%  |
| 1.01-2.0   | 5         | 6      | 3.79%   |
| 3.01-4.0   | 1         | 2      | 0.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 79        | 37.8%   |
| 251-500        | 42        | 20.1%   |
| 501-1000       | 26        | 12.44%  |
| 51-100         | 19        | 9.09%   |
| 1001-2000      | 17        | 8.13%   |
| 21-50          | 9         | 4.31%   |
| 1-20           | 8         | 3.83%   |
| More than 3000 | 5         | 2.39%   |
| 2001-3000      | 3         | 1.44%   |
| Unknown        | 1         | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 89        | 41.59%  |
| 21-50     | 47        | 21.96%  |
| 101-250   | 28        | 13.08%  |
| 51-100    | 20        | 9.35%   |
| 251-500   | 14        | 6.54%   |
| 501-1000  | 8         | 3.74%   |
| 1001-2000 | 6         | 2.8%    |
| 2001-3000 | 1         | 0.47%   |
| Unknown   | 1         | 0.47%   |

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
| Detected | 113       | 167    | 51.6%   |
| Works    | 92        | 130    | 42.01%  |
| Malfunc  | 14        | 14     | 6.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 110       | 46.41%  |
| Samsung Electronics              | 32        | 13.5%   |
| AMD                              | 25        | 10.55%  |
| SanDisk                          | 20        | 8.44%   |
| SK hynix                         | 14        | 5.91%   |
| Phison Electronics               | 8         | 3.38%   |
| Toshiba America Info Systems     | 6         | 2.53%   |
| Kingston Technology Company      | 4         | 1.69%   |
| Apple                            | 3         | 1.27%   |
| ADATA Technology                 | 3         | 1.27%   |
| Union Memory (Shenzhen)          | 2         | 0.84%   |
| Silicon Motion                   | 2         | 0.84%   |
| Nvidia                           | 2         | 0.84%   |
| Solid State Storage Technology   | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| O2 Micro                         | 1         | 0.42%   |
| Micron/Crucial Technology        | 1         | 0.42%   |
| Micron Technology                | 1         | 0.42%   |
| KIOXIA                           | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 23        | 9.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 5.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 4.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 4.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 3.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 3.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 3.25%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 6         | 2.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 6         | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 2.44%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 2.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 2.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 2.03%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 1.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.22%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 1.22%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 1.22%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 1.22%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.22%   |
| SanDisk PC SN520 NVMe SSD                                                      | 3         | 1.22%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 1.22%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.22%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.22%   |
| Intel SSD 660P Series                                                          | 3         | 1.22%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 1.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.22%   |
| Apple ANS2 NVMe Controller                                                     | 3         | 1.22%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.81%   |
| SK hynix BC511                                                                 | 2         | 0.81%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.81%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.81%   |
| Phison NVMe Storage Controller                                                 | 2         | 0.81%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 122       | 52.14%  |
| NVMe | 94        | 40.17%  |
| RAID | 10        | 4.27%   |
| IDE  | 8         | 3.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 160       | 80.4%   |
| AMD    | 38        | 19.1%   |
| ARM    | 1         | 0.5%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 3.02%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 3.02%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.51%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 2.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 2.01%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 2.01%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 2.01%   |
| Intel 12th Gen Core i5-1240P                  | 4         | 2.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.51%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.51%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 1.51%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.51%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 1.01%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 2         | 1.01%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.01%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 1.01%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 1.01%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 2         | 1.01%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 1.01%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 1.01%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 1.01%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.01%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 1.01%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.01%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 1.01%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.01%   |
| Intel 12th Gen Core i9-12900H                 | 2         | 1.01%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.01%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.01%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 2         | 1.01%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 2         | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.01%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.01%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 46        | 23.12%  |
| Intel Core i5        | 43        | 21.61%  |
| Other                | 25        | 12.56%  |
| Intel Core i3        | 12        | 6.03%   |
| AMD Ryzen 7          | 11        | 5.53%   |
| AMD Ryzen 5          | 11        | 5.53%   |
| Intel Core 2 Duo     | 8         | 4.02%   |
| Intel Celeron        | 8         | 4.02%   |
| Intel Pentium        | 4         | 2.01%   |
| Intel Core i9        | 4         | 2.01%   |
| Intel Atom           | 4         | 2.01%   |
| AMD Ryzen 7 PRO      | 3         | 1.51%   |
| Intel Pentium Silver | 2         | 1.01%   |
| Intel Genuine        | 2         | 1.01%   |
| Intel Core 2         | 2         | 1.01%   |
| AMD Ryzen 9          | 2         | 1.01%   |
| AMD Ryzen 5 PRO      | 2         | 1.01%   |
| AMD Ryzen 3          | 2         | 1.01%   |
| AMD A4               | 2         | 1.01%   |
| AMD A10              | 2         | 1.01%   |
| Intel Xeon           | 1         | 0.5%    |
| Intel Pentium Dual   | 1         | 0.5%    |
| AMD Quad-Core        | 1         | 0.5%    |
| AMD Athlon II        | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 76        | 38.19%  |
| 4       | 72        | 36.18%  |
| 8       | 22        | 11.06%  |
| 6       | 18        | 9.05%   |
| 12      | 6         | 3.02%   |
| 14      | 3         | 1.51%   |
| 1       | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 198       | 99.5%   |
| 2      | 1         | 0.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 162       | 81.41%  |
| 1       | 36        | 18.09%  |
| Unknown | 1         | 0.5%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 195       | 97.99%  |
| Unknown        | 2         | 1.01%   |
| 64-bit         | 1         | 0.5%    |
| 32-bit         | 1         | 0.5%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 12.25%  |
| 0x806ec    | 13        | 6.37%   |
| 0x806c1    | 12        | 5.88%   |
| 0x306a9    | 11        | 5.39%   |
| 0x206a7    | 9         | 4.41%   |
| 0x906a3    | 8         | 3.92%   |
| 0x806ea    | 8         | 3.92%   |
| 0x20655    | 8         | 3.92%   |
| 0x0a50000c | 7         | 3.43%   |
| 0x08600106 | 7         | 3.43%   |
| 0x806eb    | 6         | 2.94%   |
| 0x40651    | 6         | 2.94%   |
| 0x906e9    | 5         | 2.45%   |
| 0x706e5    | 5         | 2.45%   |
| 0x08108102 | 5         | 2.45%   |
| 0xa0652    | 4         | 1.96%   |
| 0x906ea    | 4         | 1.96%   |
| 0x706a1    | 4         | 1.96%   |
| 0x306c3    | 4         | 1.96%   |
| 0x30678    | 4         | 1.96%   |
| 0x906ed    | 3         | 1.47%   |
| 0x806e9    | 3         | 1.47%   |
| 0x6fd      | 3         | 1.47%   |
| 0x306d4    | 3         | 1.47%   |
| 0x1067a    | 3         | 1.47%   |
| 0xa0660    | 2         | 0.98%   |
| 0x6f6      | 2         | 0.98%   |
| 0x406e3    | 2         | 0.98%   |
| 0x406c3    | 2         | 0.98%   |
| 0x20652    | 2         | 0.98%   |
| 0x10676    | 2         | 0.98%   |
| 0x08608103 | 2         | 0.98%   |
| 0x08600103 | 2         | 0.98%   |
| 0x0700010f | 2         | 0.98%   |
| 0x06001119 | 2         | 0.98%   |
| 0x906a2    | 1         | 0.49%   |
| 0x806d1    | 1         | 0.49%   |
| 0x706a8    | 1         | 0.49%   |
| 0x6fb      | 1         | 0.49%   |
| 0x6e8      | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 45        | 22.61%  |
| Haswell          | 14        | 7.04%   |
| Zen 2            | 13        | 6.53%   |
| TigerLake        | 13        | 6.53%   |
| Westmere         | 11        | 5.53%   |
| IvyBridge        | 11        | 5.53%   |
| SandyBridge      | 10        | 5.03%   |
| Unknown          | 9         | 4.52%   |
| Zen 3            | 8         | 4.02%   |
| Silvermont       | 7         | 3.52%   |
| IceLake          | 7         | 3.52%   |
| Penryn           | 6         | 3.02%   |
| Core             | 6         | 3.02%   |
| CometLake        | 6         | 3.02%   |
| Zen+             | 5         | 2.51%   |
| Goldmont plus    | 5         | 2.51%   |
| Alderlake Hybrid | 5         | 2.51%   |
| Skylake          | 4         | 2.01%   |
| Broadwell        | 3         | 1.51%   |
| Zen              | 2         | 1.01%   |
| Piledriver       | 2         | 1.01%   |
| Jaguar           | 2         | 1.01%   |
| P6               | 1         | 0.5%    |
| Nehalem          | 1         | 0.5%    |
| K10              | 1         | 0.5%    |
| Excavator        | 1         | 0.5%    |
| Bonnell          | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 143       | 56.97%  |
| Nvidia                           | 59        | 23.51%  |
| AMD                              | 48        | 19.12%  |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 13        | 5.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 4.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 3.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 3.47%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 9         | 3.47%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 2.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.54%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.54%   |
| Intel HD Graphics 630                                                                    | 4         | 1.54%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.54%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.16%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.16%   |
| AMD Barcelo                                                                              | 3         | 1.16%   |
| Nvidia TU117M                                                                            | 2         | 0.77%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.77%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.77%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.77%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                               | 2         | 0.77%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.77%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.77%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.77%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 94        | 47.24%  |
| Intel + Nvidia | 42        | 21.11%  |
| 1 x AMD        | 35        | 17.59%  |
| 1 x Nvidia     | 12        | 6.03%   |
| Intel + AMD    | 6         | 3.02%   |
| AMD + Nvidia   | 4         | 2.01%   |
| 2 x AMD        | 3         | 1.51%   |
| Other          | 1         | 0.5%    |
| 2 x Nvidia     | 1         | 0.5%    |
| 1 x SiS        | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 162       | 80.6%   |
| Proprietary | 30        | 14.93%  |
| Unknown     | 9         | 4.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 121       | 59.9%   |
| 0.01-0.5   | 24        | 11.88%  |
| 1.01-2.0   | 20        | 9.9%    |
| 3.01-4.0   | 18        | 8.91%   |
| 0.51-1.0   | 11        | 5.45%   |
| 5.01-6.0   | 4         | 1.98%   |
| 7.01-8.0   | 3         | 1.49%   |
| 8.01-16.0  | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 42        | 18.26%  |
| AU Optronics            | 38        | 16.52%  |
| Samsung Electronics     | 28        | 12.17%  |
| BOE                     | 28        | 12.17%  |
| Chimei Innolux          | 22        | 9.57%   |
| Goldstar                | 11        | 4.78%   |
| Sharp                   | 8         | 3.48%   |
| Apple                   | 8         | 3.48%   |
| Dell                    | 6         | 2.61%   |
| Lenovo                  | 5         | 2.17%   |
| PANDA                   | 4         | 1.74%   |
| JCH                     | 3         | 1.3%    |
| CPT                     | 3         | 1.3%    |
| ALP                     | 3         | 1.3%    |
| Philips                 | 2         | 0.87%   |
| CSO                     | 2         | 0.87%   |
| Chi Mei Optoelectronics | 2         | 0.87%   |
| BenQ                    | 2         | 0.87%   |
| VMO                     | 1         | 0.43%   |
| Valve                   | 1         | 0.43%   |
| TMX                     | 1         | 0.43%   |
| Sony                    | 1         | 0.43%   |
| PRISM+                  | 1         | 0.43%   |
| MSI                     | 1         | 0.43%   |
| InfoVision              | 1         | 0.43%   |
| HKC                     | 1         | 0.43%   |
| Hewlett-Packard         | 1         | 0.43%   |
| HannStar                | 1         | 0.43%   |
| Denver                  | 1         | 0.43%   |
| CM_                     | 1         | 0.43%   |
| Ancor Communications    | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 1.71%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 1.28%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 1.28%   |
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 3         | 1.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 1.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.28%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.85%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 2         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 2         | 0.85%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 2         | 0.85%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 2         | 0.85%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch          | 2         | 0.85%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch          | 2         | 0.85%   |
| LG Display LCD Monitor LGD03B5 1920x1080 294x165mm 13.3-inch          | 2         | 0.85%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.85%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 0.85%   |
| BOE LCD Monitor BOE06D7 3840x2160 345x194mm 15.6-inch                 | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO749D 3840x2160 381x214mm 17.2-inch        | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO6A92 1920x1080 344x194mm 15.5-inch        | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 2         | 0.85%   |
| AU Optronics LCD Monitor 1920x1080                                    | 2         | 0.85%   |
| Apple Color LCD APPA044 3072x1920 345x215mm 16.0-inch                 | 2         | 0.85%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch             | 1         | 0.43%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.43%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.43%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 0.43%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.43%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.43%   |
| Samsung Electronics U32H85x SAM0E3A 3840x2160 697x392mm 31.5-inch     | 1         | 0.43%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch     | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM01A2 1280x1024 376x301mm 19.0-inch  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0138 1280x1024 338x270mm 17.0-inch  | 1         | 0.43%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch  | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 110       | 50.46%  |
| 1366x768 (WXGA)    | 36        | 16.51%  |
| 3840x2160 (4K)     | 14        | 6.42%   |
| 2560x1600          | 9         | 4.13%   |
| 2560x1440 (QHD)    | 8         | 3.67%   |
| 1600x900 (HD+)     | 7         | 3.21%   |
| 1280x800 (WXGA)    | 7         | 3.21%   |
| 1920x1200 (WUXGA)  | 6         | 2.75%   |
| 3440x1440          | 3         | 1.38%   |
| 2880x1800          | 3         | 1.38%   |
| 1440x900 (WXGA+)   | 3         | 1.38%   |
| 3072x1920          | 2         | 0.92%   |
| 1680x1050 (WSXGA+) | 2         | 0.92%   |
| 1280x1024 (SXGA)   | 2         | 0.92%   |
| 800x1280           | 1         | 0.46%   |
| 3840x2400          | 1         | 0.46%   |
| 2560x1080          | 1         | 0.46%   |
| 1680x945           | 1         | 0.46%   |
| 1400x1050          | 1         | 0.46%   |
| 1024x768 (XGA)     | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 93        | 40.09%  |
| 13      | 35        | 15.09%  |
| 14      | 27        | 11.64%  |
| 17      | 11        | 4.74%   |
| 27      | 10        | 4.31%   |
| 24      | 9         | 3.88%   |
| 16      | 8         | 3.45%   |
| 23      | 7         | 3.02%   |
| 31      | 5         | 2.16%   |
| 21      | 4         | 1.72%   |
| 12      | 4         | 1.72%   |
| 34      | 3         | 1.29%   |
| 20      | 3         | 1.29%   |
| 11      | 3         | 1.29%   |
| Unknown | 2         | 0.86%   |
| 74      | 1         | 0.43%   |
| 54      | 1         | 0.43%   |
| 40      | 1         | 0.43%   |
| 25      | 1         | 0.43%   |
| 19      | 1         | 0.43%   |
| 18      | 1         | 0.43%   |
| 10      | 1         | 0.43%   |
| 7       | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 136       | 58.87%  |
| 201-300     | 32        | 13.85%  |
| 501-600     | 25        | 10.82%  |
| 351-400     | 14        | 6.06%   |
| 401-500     | 9         | 3.9%    |
| 601-700     | 6         | 2.6%    |
| 701-800     | 3         | 1.3%    |
| Unknown     | 2         | 0.87%   |
| 801-900     | 1         | 0.43%   |
| 1501-2000   | 1         | 0.43%   |
| 1001-1500   | 1         | 0.43%   |
| 1-100       | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 157       | 78.5%   |
| 16/10   | 31        | 15.5%   |
| 21/9    | 3         | 1.5%    |
| 5/4     | 2         | 1%      |
| 4/3     | 2         | 1%      |
| 3/2     | 2         | 1%      |
| Unknown | 2         | 1%      |
| 0.67    | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 93        | 40.09%  |
| 81-90          | 40        | 17.24%  |
| 71-80          | 20        | 8.62%   |
| 201-250        | 17        | 7.33%   |
| 301-350        | 10        | 4.31%   |
| 121-130        | 10        | 4.31%   |
| 351-500        | 8         | 3.45%   |
| 111-120        | 7         | 3.02%   |
| 61-70          | 4         | 1.72%   |
| 251-300        | 4         | 1.72%   |
| 151-200        | 4         | 1.72%   |
| 51-60          | 3         | 1.29%   |
| 91-100         | 3         | 1.29%   |
| More than 1000 | 2         | 0.86%   |
| 141-150        | 2         | 0.86%   |
| Unknown        | 2         | 0.86%   |
| 41-50          | 1         | 0.43%   |
| 1-40           | 1         | 0.43%   |
| 501-1000       | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 96        | 42.11%  |
| 101-120       | 45        | 19.74%  |
| 51-100        | 36        | 15.79%  |
| 161-240       | 34        | 14.91%  |
| More than 240 | 13        | 5.7%    |
| 1-50          | 2         | 0.88%   |
| Unknown       | 2         | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 153       | 73.91%  |
| 2     | 41        | 19.81%  |
| 0     | 9         | 4.35%   |
| 3     | 4         | 1.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 132       | 42.58%  |
| Realtek Semiconductor            | 99        | 31.94%  |
| Qualcomm Atheros                 | 26        | 8.39%   |
| Broadcom                         | 19        | 6.13%   |
| ASIX Electronics                 | 7         | 2.26%   |
| MediaTek                         | 3         | 0.97%   |
| Marvell Technology Group         | 3         | 0.97%   |
| Apple                            | 3         | 0.97%   |
| TP-Link                          | 2         | 0.65%   |
| Ralink Technology                | 2         | 0.65%   |
| Nvidia                           | 2         | 0.65%   |
| Lenovo                           | 2         | 0.65%   |
| Broadcom Limited                 | 2         | 0.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| Samsung Electronics              | 1         | 0.32%   |
| Ralink                           | 1         | 0.32%   |
| Qualcomm                         | 1         | 0.32%   |
| Microsoft                        | 1         | 0.32%   |
| D-Link                           | 1         | 0.32%   |
| Comneon                          | 1         | 0.32%   |
| Arduino SA                       | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68        | 19.21%  |
| Intel Wi-Fi 6 AX200                                               | 24        | 6.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 3.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.11%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 3.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 2.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 9         | 2.54%   |
| Intel Wireless 7260                                               | 8         | 2.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.69%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 1.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.13%   |
| Intel Wireless 3165                                               | 4         | 1.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 1.13%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 4         | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.85%   |
| Intel Wireless 7265                                               | 3         | 0.85%   |
| Intel Wireless 3160                                               | 3         | 0.85%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.85%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.85%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                | 3         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 128       | 64.97%  |
| Realtek Semiconductor | 21        | 10.66%  |
| Qualcomm Atheros      | 20        | 10.15%  |
| Broadcom              | 16        | 8.12%   |
| MediaTek              | 3         | 1.52%   |
| TP-Link               | 2         | 1.02%   |
| Ralink Technology     | 2         | 1.02%   |
| Broadcom Limited      | 2         | 1.02%   |
| Ralink                | 1         | 0.51%   |
| Qualcomm              | 1         | 0.51%   |
| D-Link                | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 24        | 12.12%  |
| Intel Wi-Fi 6 AX201                                           | 11        | 5.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 10        | 5.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 9         | 4.55%   |
| Intel Wireless 7260                                           | 8         | 4.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 6         | 3.03%   |
| Intel Wireless 8265 / 8275                                    | 5         | 2.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 5         | 2.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 5         | 2.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 4         | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 2.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 4         | 2.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 4         | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 4         | 2.02%   |
| Intel Wireless 3165                                           | 4         | 2.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 4         | 2.02%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 4         | 2.02%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 4         | 2.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 3         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 1.52%   |
| Intel Wireless 7265                                           | 3         | 1.52%   |
| Intel Wireless 3160                                           | 3         | 1.52%   |
| Intel Centrino Wireless-N 2230                                | 3         | 1.52%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 3         | 1.52%   |
| Intel Centrino Advanced-N 6235                                | 3         | 1.52%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 3         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                 | 3         | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 2         | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 1.01%   |
| Intel Wireless 8260                                           | 2         | 1.01%   |
| Intel WiFi Link 5100                                          | 2         | 1.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 1.01%   |
| Intel Centrino Advanced-N 6200                                | 2         | 1.01%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller        | 2         | 1.01%   |
| Broadcom BCM43162 802.11ac Wireless Network Adapter           | 2         | 1.01%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 93        | 63.7%   |
| Intel                            | 22        | 15.07%  |
| Qualcomm Atheros                 | 8         | 5.48%   |
| ASIX Electronics                 | 7         | 4.79%   |
| Marvell Technology Group         | 3         | 2.05%   |
| Broadcom                         | 3         | 2.05%   |
| Apple                            | 3         | 2.05%   |
| Nvidia                           | 2         | 1.37%   |
| Lenovo                           | 2         | 1.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.68%   |
| Samsung Electronics              | 1         | 0.68%   |
| Microsoft                        | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 68        | 44.44%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 12        | 7.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11        | 7.19%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 4.58%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 3.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.61%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.96%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.31%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.31%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.31%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.31%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.31%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.31%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.31%   |
| Apple iBridge                                                                  | 2         | 1.31%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.65%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.65%   |
| Microsoft Ethernet Adapter                                                     | 1         | 0.65%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.65%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.65%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.65%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.65%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.65%   |
| Intel Ethernet controller                                                      | 1         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.65%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.65%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.65%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.65%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.65%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.65%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.65%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 190       | 57.06%  |
| Ethernet | 140       | 42.04%  |
| Modem    | 2         | 0.6%    |
| Unknown  | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 154       | 72.3%   |
| Ethernet | 59        | 27.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 117       | 58.79%  |
| 1     | 76        | 38.19%  |
| 0     | 4         | 2.01%   |
| 3     | 2         | 1.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 198       | 99.5%   |
| Yes  | 1         | 0.5%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 106       | 64.24%  |
| Broadcom                        | 14        | 8.48%   |
| Realtek Semiconductor           | 13        | 7.88%   |
| Qualcomm Atheros Communications | 9         | 5.45%   |
| IMC Networks                    | 8         | 4.85%   |
| Foxconn / Hon Hai               | 5         | 3.03%   |
| Lite-On Technology              | 4         | 2.42%   |
| Apple                           | 4         | 2.42%   |
| Qcom                            | 1         | 0.61%   |
| Micro Star International        | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 25        | 15.15%  |
| Intel AX200 Bluetooth                                                               | 24        | 14.55%  |
| Intel AX201 Bluetooth                                                               | 22        | 13.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 10.91%  |
| Realtek Bluetooth Radio                                                             | 9         | 5.45%   |
| Intel Bluetooth Device                                                              | 8         | 4.85%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 3.03%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.42%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.42%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.42%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.82%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.82%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.82%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.21%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.21%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.21%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 1.21%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.21%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.21%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.21%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 1.21%   |
| Realtek CSR BS8510                                                                  | 1         | 0.61%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.61%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.61%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.61%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.61%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.61%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 152       | 63.87%  |
| AMD                              | 45        | 18.91%  |
| Nvidia                           | 28        | 11.76%  |
| JMTek                            | 3         | 1.26%   |
| Apple                            | 3         | 1.26%   |
| Lenovo                           | 2         | 0.84%   |
| Texas Instruments                | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Razer USA                        | 1         | 0.42%   |
| Dell                             | 1         | 0.42%   |
| Unknown                          | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 31        | 10.65%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 22        | 7.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 4.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 4.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 4.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 3.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 3.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 3.44%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 3.09%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.75%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 2.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 2.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.72%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.37%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.37%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.37%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.03%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 1.03%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 1.03%   |
| Nvidia Audio device                                                                               | 3         | 1.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.03%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.03%   |
| Apple Audio Device                                                                                | 3         | 1.03%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.03%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.69%   |
| JMTek USB Audio Device                                                                            | 2         | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 70        | 50.72%  |
| SK hynix            | 28        | 20.29%  |
| Micron Technology   | 14        | 10.14%  |
| Unknown             | 7         | 5.07%   |
| Kingston            | 3         | 2.17%   |
| A-DATA Technology   | 3         | 2.17%   |
| Unknown             | 3         | 2.17%   |
| Unknown (ABCD)      | 2         | 1.45%   |
| Ramaxel Technology  | 2         | 1.45%   |
| Unknown (09D5)      | 1         | 0.72%   |
| Team                | 1         | 0.72%   |
| Silicon Power       | 1         | 0.72%   |
| Imation             | 1         | 0.72%   |
| Essencore           | 1         | 0.72%   |
| Elpida              | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 5.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 2.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.67%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 2%      |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 3         | 2%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2%      |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 2%      |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2%      |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 2%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 2%      |
| Samsung RAM M471A1G44AB0-CTD 8GB DDR4 2667MT/s                   | 3         | 2%      |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 2%      |
| Unknown                                                          | 3         | 2%      |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 1.33%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.33%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.33%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 2         | 1.33%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DDR4 2667MT/s                   | 2         | 1.33%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 2         | 1.33%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.67%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.67%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.67%   |
| Unknown RAM CL22-22-22 D4-3200 16384MB SODIMM DDR4 3200MT/s      | 1         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.67%   |
| Unknown (09D5) RAM Module 16384MB SODIMM DDR4 2400MT/s           | 1         | 0.67%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.67%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.67%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 1         | 0.67%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                 | 1         | 0.67%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 68        | 58.12%  |
| DDR3    | 26        | 22.22%  |
| LPDDR4  | 8         | 6.84%   |
| LPDDR3  | 6         | 5.13%   |
| DDR2    | 3         | 2.56%   |
| SDRAM   | 2         | 1.71%   |
| DDR5    | 2         | 1.71%   |
| LPDDR5  | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 92        | 77.31%  |
| Row Of Chips | 19        | 15.97%  |
| Unknown      | 5         | 4.2%    |
| DIMM         | 3         | 2.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 60        | 47.24%  |
| 4096  | 30        | 23.62%  |
| 16384 | 16        | 12.6%   |
| 2048  | 12        | 9.45%   |
| 32768 | 7         | 5.51%   |
| 1024  | 2         | 1.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 32        | 25.4%   |
| 2667    | 31        | 24.6%   |
| 1600    | 16        | 12.7%   |
| 2400    | 11        | 8.73%   |
| 2133    | 7         | 5.56%   |
| 4267    | 5         | 3.97%   |
| 1334    | 5         | 3.97%   |
| 3266    | 4         | 3.17%   |
| 4800    | 3         | 2.38%   |
| 1333    | 2         | 1.59%   |
| 1067    | 2         | 1.59%   |
| 8400    | 1         | 0.79%   |
| 6400    | 1         | 0.79%   |
| 4199    | 1         | 0.79%   |
| 2048    | 1         | 0.79%   |
| 1867    | 1         | 0.79%   |
| 800     | 1         | 0.79%   |
| 667     | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

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
| Chicony Electronics                    | 34        | 20.36%  |
| IMC Networks                           | 23        | 13.77%  |
| Acer                                   | 19        | 11.38%  |
| Realtek Semiconductor                  | 13        | 7.78%   |
| Microdia                               | 12        | 7.19%   |
| Silicon Motion                         | 10        | 5.99%   |
| Quanta                                 | 8         | 4.79%   |
| Apple                                  | 7         | 4.19%   |
| Unknown                                | 6         | 3.59%   |
| Syntek                                 | 5         | 2.99%   |
| Suyin                                  | 5         | 2.99%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.99%   |
| SunplusIT                              | 4         | 2.4%    |
| Sunplus Innovation Technology          | 3         | 1.8%    |
| Z-Star Microelectronics                | 2         | 1.2%    |
| Luxvisions Innotech Limited            | 2         | 1.2%    |
| Lenovo                                 | 2         | 1.2%    |
| SJ-180517-N                            | 1         | 0.6%    |
| Microsoft                              | 1         | 0.6%    |
| Logitech                               | 1         | 0.6%    |
| Goodong Industry                       | 1         | 0.6%    |
| DJJHFA1BIF5595                         | 1         | 0.6%    |
| DigiTech                               | 1         | 0.6%    |
| Alcor Micro                            | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 10        | 5.92%   |
| Microdia Integrated_Webcam_HD                           | 7         | 4.14%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 7         | 4.14%   |
| IMC Networks Integrated Camera                          | 7         | 4.14%   |
| Unknown 720p HD Camera                                  | 6         | 3.55%   |
| Chicony HD WebCam                                       | 6         | 3.55%   |
| Realtek LG Camera                                       | 5         | 2.96%   |
| Acer Integrated Camera                                  | 5         | 2.96%   |
| Acer HD Webcam                                          | 5         | 2.96%   |
| Syntek Integrated Camera                                | 3         | 1.78%   |
| Suyin HP Truevision HD                                  | 3         | 1.78%   |
| SunplusIT 1080p FHD Camera                              | 3         | 1.78%   |
| Silicon Motion LG HD WebCam                             | 3         | 1.78%   |
| Quanta HP TrueVision HD Camera                          | 3         | 1.78%   |
| Microdia USB 2.0 Camera                                 | 3         | 1.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.78%   |
| Chicony LG Camera                                       | 3         | 1.78%   |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 1.78%   |
| Z-Star Webcam                                           | 2         | 1.18%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 2         | 1.18%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.18%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.18%   |
| Quanta LG Webcam                                        | 2         | 1.18%   |
| IMC Networks USB HD Webcam                              | 2         | 1.18%   |
| IMC Networks Integrated RGB Camera                      | 2         | 1.18%   |
| Chicony USB 2.0 Camera                                  | 2         | 1.18%   |
| Chicony LG HD WebCam                                    | 2         | 1.18%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.18%   |
| Apple iPhone5/5C/5S/6                                   | 2         | 1.18%   |
| Apple Built-in iSight                                   | 2         | 1.18%   |
| Acer Lenovo EasyCamera                                  | 2         | 1.18%   |
| Acer BisonCam,NB Pro                                    | 2         | 1.18%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.59%   |
| Syntek HP Webcam                                        | 1         | 0.59%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.59%   |
| Suyin HP TrueVision Full HD                             | 1         | 0.59%   |
| SunplusIT 720p HD Camera                                | 1         | 0.59%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.59%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 13        | 30.23%  |
| Validity Sensors                   | 9         | 20.93%  |
| Samsung Electronics                | 5         | 11.63%  |
| Upek                               | 4         | 9.3%    |
| Shenzhen Goodix Technology         | 4         | 9.3%    |
| STMicroelectronics                 | 2         | 4.65%   |
| LighTuning Technology              | 2         | 4.65%   |
| Elan Microelectronics              | 2         | 4.65%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.33%   |
| AuthenTec                          | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown                                                         | 6         | 13.95%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 9.3%    |
| Samsung Fingerprint Sensor Device - 730B                        | 4         | 9.3%    |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 4.65%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 4.65%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 2         | 4.65%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 4.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 4.65%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 4.65%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 4.65%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 4.65%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 4.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 1         | 2.33%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 2.33%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 2.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 2.33%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.33%   |
| Synaptics WBDI Device                                           | 1         | 2.33%   |
| Samsung Fingerprint Device                                      | 1         | 2.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.33%   |
| Elan ELAN:Fingerprint                                           | 1         | 2.33%   |
| Elan ELAN:ARM-M4                                                | 1         | 2.33%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 2.33%   |

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
| 0     | 118       | 58.13%  |
| 1     | 72        | 35.47%  |
| 2     | 9         | 4.43%   |
| 3     | 4         | 1.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 43        | 43.43%  |
| Graphics card         | 23        | 23.23%  |
| Net/wireless          | 14        | 14.14%  |
| Chipcard              | 7         | 7.07%   |
| Multimedia controller | 4         | 4.04%   |
| Bluetooth             | 3         | 3.03%   |
| Sound                 | 2         | 2.02%   |
| Net/ethernet          | 2         | 2.02%   |
| Network               | 1         | 1.01%   |

