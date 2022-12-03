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

Total: 265

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 42        | 21.43%  |
| Ubuntu 18.04       | 18        | 9.18%   |
| Ubuntu 22.04       | 11        | 5.61%   |
| Ubuntu 21.10       | 7         | 3.57%   |
| Gooroom            | 7         | 3.57%   |
| Arch               | 6         | 3.06%   |
| Arch Rolling       | 5         | 2.55%   |
| Linux Mint 20.3    | 4         | 2.04%   |
| Linux Mint 20.1    | 4         | 2.04%   |
| Fedora 36          | 4         | 2.04%   |
| Fedora 32          | 4         | 2.04%   |
| Ubuntu 19.10       | 3         | 1.53%   |
| Ubuntu 19.04       | 3         | 1.53%   |
| ROSA R11           | 3         | 1.53%   |
| OpenMandriva 4.2   | 3         | 1.53%   |
| HamoniKR 4.0       | 3         | 1.53%   |
| Fedora 34          | 3         | 1.53%   |
| Debian 10          | 3         | 1.53%   |
| Zorin 15           | 2         | 1.02%   |
| Ubuntu MATE 18.04  | 2         | 1.02%   |
| ROSA R10           | 2         | 1.02%   |
| Pop!_OS 21.10      | 2         | 1.02%   |
| Manjaro 21.3.0     | 2         | 1.02%   |
| LMDE 5             | 2         | 1.02%   |
| Linux Mint 20      | 2         | 1.02%   |
| Kubuntu 22.04      | 2         | 1.02%   |
| KDE neon 20.04     | 2         | 1.02%   |
| Endless 3.8.5      | 2         | 1.02%   |
| Debian 11          | 2         | 1.02%   |
| CentOS 8           | 2         | 1.02%   |
| Zorin 16           | 1         | 0.51%   |
| Xubuntu 20.04      | 1         | 0.51%   |
| Ubuntu Unity 18.04 | 1         | 0.51%   |
| Ubuntu Unity 16.04 | 1         | 0.51%   |
| Ubuntu 21.04       | 1         | 0.51%   |
| Ubuntu 20.10       | 1         | 0.51%   |
| Pop!_OS 22.04      | 1         | 0.51%   |
| Pop!_OS 21.04      | 1         | 0.51%   |
| Pop!_OS 20.10      | 1         | 0.51%   |
| Pop!_OS 20.04      | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 84        | 44.44%  |
| Linux Mint   | 13        | 6.88%   |
| Fedora       | 12        | 6.35%   |
| Arch         | 9         | 4.76%   |
| Manjaro      | 8         | 4.23%   |
| Gooroom      | 8         | 4.23%   |
| ROSA         | 5         | 2.65%   |
| OpenMandriva | 5         | 2.65%   |
| Endless      | 5         | 2.65%   |
| Debian       | 5         | 2.65%   |
| Pop!_OS      | 4         | 2.12%   |
| Kubuntu      | 4         | 2.12%   |
| HamoniKR     | 4         | 2.12%   |
| Zorin        | 3         | 1.59%   |
| No1          | 3         | 1.59%   |
| Ubuntu Unity | 2         | 1.06%   |
| Ubuntu MATE  | 2         | 1.06%   |
| LMDE         | 2         | 1.06%   |
| KDE neon     | 2         | 1.06%   |
| EndeavourOS  | 2         | 1.06%   |
| CentOS       | 2         | 1.06%   |
| Xubuntu      | 1         | 0.53%   |
| openSUSE     | 1         | 0.53%   |
| Lubuntu      | 1         | 0.53%   |
| Gentoo       | 1         | 0.53%   |
| Garuda Linux | 1         | 0.53%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 4         | 1.92%   |
| 5.15.0-53-generic               | 4         | 1.92%   |
| 5.10.0-17-amd64                 | 4         | 1.92%   |
| 5.4.0-58-generic                | 3         | 1.44%   |
| 5.4.0-26-generic                | 3         | 1.44%   |
| 5.3.0-40-generic                | 3         | 1.44%   |
| 5.19.15-201.fc36.x86_64         | 3         | 1.44%   |
| 5.11.0-37-generic               | 3         | 1.44%   |
| 4.19.0-9-amd64                  | 3         | 1.44%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3         | 1.44%   |
| 5.8.4-200.fc32.x86_64           | 2         | 0.96%   |
| 5.8.0-53-generic                | 2         | 0.96%   |
| 5.8.0-43-generic                | 2         | 0.96%   |
| 5.4.0-81-generic                | 2         | 0.96%   |
| 5.4.0-56-generic                | 2         | 0.96%   |
| 5.4.0-48-generic                | 2         | 0.96%   |
| 5.4.0-39-generic                | 2         | 0.96%   |
| 5.4.0-33-generic                | 2         | 0.96%   |
| 5.4.0-31-generic                | 2         | 0.96%   |
| 5.4.0-29-generic                | 2         | 0.96%   |
| 5.3.0-46-generic                | 2         | 0.96%   |
| 5.18.5-1-MANJARO                | 2         | 0.96%   |
| 5.15.0-52-generic               | 2         | 0.96%   |
| 5.15.0-33-generic               | 2         | 0.96%   |
| 5.15.0-27-generic               | 2         | 0.96%   |
| 5.13.0-44-generic               | 2         | 0.96%   |
| 5.13.0-28-generic               | 2         | 0.96%   |
| 5.13.0-27-generic               | 2         | 0.96%   |
| 5.10.14-desktop-1omv4002        | 2         | 0.96%   |
| 5.0.0-37-generic                | 2         | 0.96%   |
| 5.0.0-25-generic                | 2         | 0.96%   |
| 5.0.0-13-generic                | 2         | 0.96%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.96%   |
| 4.18.0-17-generic               | 2         | 0.96%   |
| 4.15.0-112-generic              | 2         | 0.96%   |
| 6.1.0-060100rc1-generic         | 1         | 0.48%   |
| 6.0.6-Wataten-T2-xanmod1-1      | 1         | 0.48%   |
| 6.0.2-76060002-generic          | 1         | 0.48%   |
| 6.0.0-t2                        | 1         | 0.48%   |
| 6.0.0-2-amd64                   | 1         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 45        | 22.39%  |
| 5.15.0  | 14        | 6.97%   |
| 5.13.0  | 12        | 5.97%   |
| 5.8.0   | 11        | 5.47%   |
| 5.11.0  | 10        | 4.98%   |
| 4.15.0  | 10        | 4.98%   |
| 5.3.0   | 9         | 4.48%   |
| 5.10.0  | 7         | 3.48%   |
| 5.0.0   | 7         | 3.48%   |
| 4.18.0  | 7         | 3.48%   |
| 4.19.0  | 6         | 2.99%   |
| 5.19.15 | 3         | 1.49%   |
| 6.0.0   | 2         | 1%      |
| 5.8.4   | 2         | 1%      |
| 5.18.5  | 2         | 1%      |
| 5.16.19 | 2         | 1%      |
| 5.15.11 | 2         | 1%      |
| 5.14.0  | 2         | 1%      |
| 5.10.14 | 2         | 1%      |
| 4.9.60  | 2         | 1%      |
| 6.1.0   | 1         | 0.5%    |
| 6.0.6   | 1         | 0.5%    |
| 6.0.2   | 1         | 0.5%    |
| 5.9.9   | 1         | 0.5%    |
| 5.8.18  | 1         | 0.5%    |
| 5.8.15  | 1         | 0.5%    |
| 5.7.17  | 1         | 0.5%    |
| 5.6.11  | 1         | 0.5%    |
| 5.6.0   | 1         | 0.5%    |
| 5.5.2   | 1         | 0.5%    |
| 5.4.61  | 1         | 0.5%    |
| 5.4.55  | 1         | 0.5%    |
| 5.3.7   | 1         | 0.5%    |
| 5.2.11  | 1         | 0.5%    |
| 5.19.11 | 1         | 0.5%    |
| 5.18.17 | 1         | 0.5%    |
| 5.16.8  | 1         | 0.5%    |
| 5.16.7  | 1         | 0.5%    |
| 5.16.5  | 1         | 0.5%    |
| 5.15.8  | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 47        | 23.5%   |
| 5.15    | 21        | 10.5%   |
| 5.8     | 15        | 7.5%    |
| 5.11    | 15        | 7.5%    |
| 5.13    | 13        | 6.5%    |
| 5.10    | 11        | 5.5%    |
| 4.15    | 11        | 5.5%    |
| 5.3     | 10        | 5%      |
| 4.18    | 8         | 4%      |
| 5.0     | 7         | 3.5%    |
| 4.19    | 7         | 3.5%    |
| 5.16    | 5         | 2.5%    |
| 5.12    | 5         | 2.5%    |
| 6.0     | 4         | 2%      |
| 5.19    | 4         | 2%      |
| 5.14    | 4         | 2%      |
| 5.18    | 3         | 1.5%    |
| 5.6     | 2         | 1%      |
| 4.9     | 2         | 1%      |
| 6.1     | 1         | 0.5%    |
| 5.9     | 1         | 0.5%    |
| 5.7     | 1         | 0.5%    |
| 5.5     | 1         | 0.5%    |
| 5.2     | 1         | 0.5%    |
| 4.16    | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 180       | 98.36%  |
| i686    | 2         | 1.09%   |
| aarch64 | 1         | 0.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 99        | 52.38%  |
| KDE5            | 24        | 12.7%   |
| Unknown         | 17        | 8.99%   |
| X-Cinnamon      | 12        | 6.35%   |
| GNOME Flashback | 8         | 4.23%   |
| XFCE            | 7         | 3.7%    |
| Cinnamon        | 6         | 3.17%   |
| LXDE            | 3         | 1.59%   |
| KDE4            | 3         | 1.59%   |
| KDE             | 3         | 1.59%   |
| Unity           | 2         | 1.06%   |
| MATE            | 2         | 1.06%   |
| i3              | 2         | 1.06%   |
| sway            | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 135       | 72.97%  |
| Wayland | 34        | 18.38%  |
| Unknown | 13        | 7.03%   |
| Tty     | 3         | 1.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 90        | 47.37%  |
| GDM     | 37        | 19.47%  |
| SDDM    | 20        | 10.53%  |
| LightDM | 14        | 7.37%   |
| TDM     | 13        | 6.84%   |
| GDM3    | 12        | 6.32%   |
| KDM     | 3         | 1.58%   |
| XDM     | 1         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ko_KR   | 87        | 46.03%  |
| en_US   | 61        | 32.28%  |
| Unknown | 25        | 13.23%  |
| en_CA   | 4         | 2.12%   |
| zh_CN   | 3         | 1.59%   |
| id_ID   | 2         | 1.06%   |
| C       | 2         | 1.06%   |
| vi_VN   | 1         | 0.53%   |
| pt_BR   | 1         | 0.53%   |
| fr_FR   | 1         | 0.53%   |
| en_NZ   | 1         | 0.53%   |
| ar_EG   | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 129       | 70.11%  |
| BIOS | 55        | 29.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 154       | 83.24%  |
| Btrfs   | 12        | 6.49%   |
| Overlay | 6         | 3.24%   |
| Unknown | 6         | 3.24%   |
| Xfs     | 4         | 2.16%   |
| Zfs     | 3         | 1.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 90        | 48.13%  |
| GPT     | 87        | 46.52%  |
| MBR     | 10        | 5.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 174       | 94.57%  |
| Yes       | 10        | 5.43%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 125       | 67.2%   |
| Yes       | 61        | 32.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 36        | 19.67%  |
| Samsung Electronics | 24        | 13.11%  |
| Hewlett-Packard     | 22        | 12.02%  |
| LG Electronics      | 19        | 10.38%  |
| ASUSTek Computer    | 19        | 10.38%  |
| Dell                | 15        | 8.2%    |
| MSI                 | 11        | 6.01%   |
| Apple               | 8         | 4.37%   |
| HANSUNG COMPUTER    | 4         | 2.19%   |
| Notebook            | 3         | 1.64%   |
| Acer                | 3         | 1.64%   |
| Toshiba             | 2         | 1.09%   |
| Wolfnfox            | 1         | 0.55%   |
| TG                  | 1         | 0.55%   |
| Teclast             | 1         | 0.55%   |
| Sony                | 1         | 0.55%   |
| SLIMBOOK            | 1         | 0.55%   |
| Pine Microsystems   | 1         | 0.55%   |
| MS                  | 1         | 0.55%   |
| MECHREVO            | 1         | 0.55%   |
| Jooyontech Computer | 1         | 0.55%   |
| Intel               | 1         | 0.55%   |
| IMUZ                | 1         | 0.55%   |
| Google              | 1         | 0.55%   |
| Clevo               | 1         | 0.55%   |
| AVERATEC            | 1         | 0.55%   |
| AMI                 | 1         | 0.55%   |
| Alienware           | 1         | 0.55%   |
| Unknown             | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung 950XED                                    | 3         | 1.64%   |
| Samsung 950XCJ/951XCJ/950XCR                      | 3         | 1.64%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01S00              | 2         | 1.09%   |
| Lenovo IdeaPad 3 15IIL05 81WE                     | 2         | 1.09%   |
| HP Stream Notebook PC 13                          | 2         | 1.09%   |
| HP Laptop 15-db1xxx                               | 2         | 1.09%   |
| HANSUNG COMPUTER TFX5470H                         | 2         | 1.09%   |
| Dell XPS 15 7590                                  | 2         | 1.09%   |
| Dell Inspiron 15 5510                             | 2         | 1.09%   |
| Apple MacBookPro16,1                              | 2         | 1.09%   |
| Wolfnfox WF-TBAT                                  | 1         | 0.55%   |
| Toshiba Satellite P50-B-103                       | 1         | 0.55%   |
| Toshiba Satellite L655                            | 1         | 0.55%   |
| TG NXI-A7000 Series                               | 1         | 0.55%   |
| Teclast tPAD                                      | 1         | 0.55%   |
| Sony VPCEA36FK                                    | 1         | 0.55%   |
| SLIMBOOK PROX15-AMD                               | 1         | 0.55%   |
| Samsung X120/X170/X171                            | 1         | 0.55%   |
| Samsung SX11S                                     | 1         | 0.55%   |
| Samsung RC420/RC520/RC720                         | 1         | 0.55%   |
| Samsung R59P/R60P/R61P                            | 1         | 0.55%   |
| Samsung R440/R480                                 | 1         | 0.55%   |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.55%   |
| Samsung 905S3G/906S3G/915S3G                      | 1         | 0.55%   |
| Samsung 800G5M/800G5W                             | 1         | 0.55%   |
| Samsung 760XBE                                    | 1         | 0.55%   |
| Samsung 730QCJ/730QCR                             | 1         | 0.55%   |
| Samsung 670Z5E                                    | 1         | 0.55%   |
| Samsung 570Z5E/580Z5E                             | 1         | 0.55%   |
| Samsung 550XED                                    | 1         | 0.55%   |
| Samsung 530U3BI/530U4BI/530U4BH                   | 1         | 0.55%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.55%   |
| Samsung 400B4C/400B5C/200B4C/200B5C               | 1         | 0.55%   |
| Samsung 400B4B/400B5B/200B4B/200B5B               | 1         | 0.55%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.55%   |
| Pine Microsystems Pine64 Pinebook Pro             | 1         | 0.55%   |
| Notebook W330SU2                                  | 1         | 0.55%   |
| Notebook NL5xRU                                   | 1         | 0.55%   |
| Notebook N650DU                                   | 1         | 0.55%   |
| MSI Vector GP66 12UGS                             | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 24        | 13.11%  |
| ASUS VivoBook             | 8         | 4.37%   |
| Lenovo IdeaPad            | 7         | 3.83%   |
| HP Pavilion               | 7         | 3.83%   |
| Dell Inspiron             | 5         | 2.73%   |
| HP Laptop                 | 4         | 2.19%   |
| HP EliteBook              | 4         | 2.19%   |
| Dell XPS                  | 4         | 2.19%   |
| Samsung 950XED            | 3         | 1.64%   |
| Samsung 950XCJ            | 3         | 1.64%   |
| HP Stream                 | 3         | 1.64%   |
| Dell Latitude             | 3         | 1.64%   |
| Toshiba Satellite         | 2         | 1.09%   |
| MSI Prestige              | 2         | 1.09%   |
| HP ProBook                | 2         | 1.09%   |
| HANSUNG COMPUTER TFX5470H | 2         | 1.09%   |
| ASUS TUF                  | 2         | 1.09%   |
| ASUS ROG                  | 2         | 1.09%   |
| Apple MacBookPro5         | 2         | 1.09%   |
| Apple MacBookPro16        | 2         | 1.09%   |
| Acer Swift                | 2         | 1.09%   |
| Wolfnfox WF-TBAT          | 1         | 0.55%   |
| TG NXI-A7000              | 1         | 0.55%   |
| Teclast tPAD              | 1         | 0.55%   |
| Sony VPCEA36FK            | 1         | 0.55%   |
| SLIMBOOK PROX15-AMD       | 1         | 0.55%   |
| Samsung X120              | 1         | 0.55%   |
| Samsung SX11S             | 1         | 0.55%   |
| Samsung RC420             | 1         | 0.55%   |
| Samsung R59P              | 1         | 0.55%   |
| Samsung R440              | 1         | 0.55%   |
| Samsung 950XDB            | 1         | 0.55%   |
| Samsung 905S3G            | 1         | 0.55%   |
| Samsung 800G5M            | 1         | 0.55%   |
| Samsung 760XBE            | 1         | 0.55%   |
| Samsung 730QCJ            | 1         | 0.55%   |
| Samsung 670Z5E            | 1         | 0.55%   |
| Samsung 570Z5E            | 1         | 0.55%   |
| Samsung 550XED            | 1         | 0.55%   |
| Samsung 530U3BI           | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 37        | 20.22%  |
| 2021    | 21        | 11.48%  |
| 2019    | 21        | 11.48%  |
| 2018    | 16        | 8.74%   |
| 2014    | 14        | 7.65%   |
| 2013    | 14        | 7.65%   |
| 2011    | 11        | 6.01%   |
| 2022    | 8         | 4.37%   |
| 2010    | 7         | 3.83%   |
| 2008    | 7         | 3.83%   |
| 2015    | 6         | 3.28%   |
| 2012    | 5         | 2.73%   |
| 2017    | 4         | 2.19%   |
| 2016    | 4         | 2.19%   |
| 2009    | 4         | 2.19%   |
| 2007    | 2         | 1.09%   |
| 2006    | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 183       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 163       | 88.11%  |
| Enabled  | 22        | 11.89%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 182       | 99.45%  |
| Yes  | 1         | 0.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 49        | 26.34%  |
| 16.01-24.0  | 40        | 21.51%  |
| 3.01-4.0    | 31        | 16.67%  |
| 8.01-16.0   | 31        | 16.67%  |
| 32.01-64.0  | 16        | 8.6%    |
| 1.01-2.0    | 12        | 6.45%   |
| 24.01-32.0  | 3         | 1.61%   |
| 64.01-256.0 | 3         | 1.61%   |
| 2.01-3.0    | 1         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 66        | 32.84%  |
| 2.01-3.0   | 46        | 22.89%  |
| 3.01-4.0   | 33        | 16.42%  |
| 4.01-8.0   | 31        | 15.42%  |
| 0.51-1.0   | 15        | 7.46%   |
| 8.01-16.0  | 8         | 3.98%   |
| 16.01-24.0 | 2         | 1%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 121       | 64.36%  |
| 2      | 59        | 31.38%  |
| 3      | 6         | 3.19%   |
| 4      | 1         | 0.53%   |
| 0      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 153       | 83.61%  |
| Yes       | 30        | 16.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 69.19%  |
| No        | 57        | 30.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 95.08%  |
| No        | 9         | 4.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 81.52%  |
| No        | 34        | 18.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| South Korea | 183       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Seoul           | 31        | 16.15%  |
| Suwon           | 9         | 4.69%   |
| Seocho-gu       | 8         | 4.17%   |
| Gwanak-gu       | 7         | 3.65%   |
| Yongin-si       | 5         | 2.6%    |
| Uiwang          | 5         | 2.6%    |
| Seongnam-si     | 5         | 2.6%    |
| Jung-gu         | 5         | 2.6%    |
| Hwaseong-si     | 5         | 2.6%    |
| Yongsan-gu      | 4         | 2.08%   |
| Seongbuk-gu     | 4         | 2.08%   |
| Incheon         | 4         | 2.08%   |
| Daejeon         | 4         | 2.08%   |
| Bupyeong-gu     | 4         | 2.08%   |
| Anyang-si       | 4         | 2.08%   |
| Pyeongtaek-si   | 3         | 1.56%   |
| Jeonju          | 3         | 1.56%   |
| Gwangju         | 3         | 1.56%   |
| Geumjeong-gu    | 3         | 1.56%   |
| Gangseo-gu      | 3         | 1.56%   |
| Gangnam-gu      | 3         | 1.56%   |
| Daegu           | 3         | 1.56%   |
| Busan           | 3         | 1.56%   |
| Yeonsu-gu       | 2         | 1.04%   |
| Namdong-gu      | 2         | 1.04%   |
| Nam-gu          | 2         | 1.04%   |
| Jeju City       | 2         | 1.04%   |
| Gyeongsan-si    | 2         | 1.04%   |
| Gimpo-si        | 2         | 1.04%   |
| Danyang-gun     | 2         | 1.04%   |
| Buk-gu          | 2         | 1.04%   |
| Yuseong-gu      | 1         | 0.52%   |
| Yuseong         | 1         | 0.52%   |
| Yongsan-dong    | 1         | 0.52%   |
| Yeongdeungpo-gu | 1         | 0.52%   |
| Yangju          | 1         | 0.52%   |
| Yangcheon-gu    | 1         | 0.52%   |
| Wonju           | 1         | 0.52%   |
| Suseong-gu      | 1         | 0.52%   |
| Songpa-gu       | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 62        | 74     | 25.73%  |
| WDC                     | 27        | 29     | 11.2%   |
| SK hynix                | 19        | 25     | 7.88%   |
| SanDisk                 | 17        | 17     | 7.05%   |
| Unknown                 | 16        | 20     | 6.64%   |
| Seagate                 | 13        | 16     | 5.39%   |
| Toshiba                 | 12        | 14     | 4.98%   |
| Crucial                 | 9         | 10     | 3.73%   |
| Kingston                | 7         | 8      | 2.9%    |
| Intel                   | 7         | 12     | 2.9%    |
| Hitachi                 | 5         | 6      | 2.07%   |
| Apple                   | 5         | 5      | 2.07%   |
| Phison                  | 4         | 4      | 1.66%   |
| Micron Technology       | 4         | 5      | 1.66%   |
| A-DATA Technology       | 4         | 4      | 1.66%   |
| TAMMUZ                  | 3         | 5      | 1.24%   |
| HGST                    | 3         | 4      | 1.24%   |
| Fujitsu                 | 2         | 2      | 0.83%   |
| XPG                     | 1         | 1      | 0.41%   |
| VIVA300s                | 1         | 1      | 0.41%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.41%   |
| UMIS                    | 1         | 1      | 0.41%   |
| TYPEC 1T                | 1         | 1      | 0.41%   |
| Transcend               | 1         | 2      | 0.41%   |
| Team                    | 1         | 1      | 0.41%   |
| Silicon Motion          | 1         | 1      | 0.41%   |
| RevuAhn                 | 1         | 1      | 0.41%   |
| Plextor                 | 1         | 1      | 0.41%   |
| Phison Electronics      | 1         | 1      | 0.41%   |
| LITEONIT                | 1         | 1      | 0.41%   |
| KIOXIA                  | 1         | 1      | 0.41%   |
| KingSpec                | 1         | 1      | 0.41%   |
| JMicron Technology      | 1         | 1      | 0.41%   |
| ipTIME                  | 1         | 1      | 0.41%   |
| IPLEX                   | 1         | 1      | 0.41%   |
| Imation                 | 1         | 1      | 0.41%   |
| External                | 1         | 1      | 0.41%   |
| ES                      | 1         | 1      | 0.41%   |
| Biostar                 | 1         | 1      | 0.41%   |
| Apacer                  | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| SK hynix SHGP31-1000GM-2 1TB                         | 4         | 1.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 1.17%   |
| Samsung SSD 860 EVO 500GB                            | 3         | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 3         | 1.17%   |
| WDC WDS100T2B0C-00PXH0 1TB                           | 2         | 0.78%   |
| WDC WD50 00LPVX-22V0TT0 500GB                        | 2         | 0.78%   |
| Unknown SLD64G  64GB                                 | 2         | 0.78%   |
| Unknown SD/MMC/MS PRO 8GB                            | 2         | 0.78%   |
| Unknown MMC Card  32GB                               | 2         | 0.78%   |
| Toshiba KBG30ZMV256G 256GB                           | 2         | 0.78%   |
| SK hynix SHGP31-1000GM 1TB                           | 2         | 0.78%   |
| SK hynix NVMe SSD Drive 256GB                        | 2         | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB                       | 2         | 0.78%   |
| SanDisk SD8SBAT256G1122 256GB SSD                    | 2         | 0.78%   |
| SanDisk NVMe SSD Drive 512GB                         | 2         | 0.78%   |
| SanDisk NVMe SSD Drive 256GB                         | 2         | 0.78%   |
| Samsung SSD 860 EVO 1TB                              | 2         | 0.78%   |
| Samsung SSD 830 Series 256GB                         | 2         | 0.78%   |
| Samsung SSD 750 EVO 120GB                            | 2         | 0.78%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 2         | 0.78%   |
| Samsung NVMe SSD Drive 2TB                           | 2         | 0.78%   |
| Samsung MZVLB512HAJQ-00000 512GB                     | 2         | 0.78%   |
| Samsung MZVLB256HBHQ-000 256GB                       | 2         | 0.78%   |
| Samsung MZNLN256HAJQ-00000 256GB SSD                 | 2         | 0.78%   |
| Kingston OM8PCP3512F-AB 512GB                        | 2         | 0.78%   |
| HGST HTS721010A9E630 1TB                             | 2         | 0.78%   |
| Crucial CT500MX500SSD1 500GB                         | 2         | 0.78%   |
| Crucial CT1000MX500SSD1 1TB                          | 2         | 0.78%   |
| Apple ANS2 NVMe Controller 500GB                     | 2         | 0.78%   |
| XPG GAMMIX S11 Pro 1TB                               | 1         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1         | 0.39%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                     | 1         | 0.39%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                     | 1         | 0.39%   |
| WDC WDS120G1G0A-00SS50 120GB SSD                     | 1         | 0.39%   |
| WDC WD7500BPVT-22HXZT1 752GB                         | 1         | 0.39%   |
| WDC WD600BEVS-60LAT0 64GB                            | 1         | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB                         | 1         | 0.39%   |
| WDC WD3200BEKT-00F3T0 320GB                          | 1         | 0.39%   |
| WDC WD20SPZX-22UA7T0 2TB                             | 1         | 0.39%   |
| WDC WD10SPZX-75Z10T1 1TB                             | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 13     | 29.55%  |
| Seagate             | 12        | 15     | 27.27%  |
| Toshiba             | 5         | 5      | 11.36%  |
| Hitachi             | 5         | 6      | 11.36%  |
| HGST                | 3         | 4      | 6.82%   |
| Unknown             | 2         | 2      | 4.55%   |
| Fujitsu             | 2         | 2      | 4.55%   |
| Samsung Electronics | 1         | 1      | 2.27%   |
| ipTIME              | 1         | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 39     | 40%     |
| SanDisk             | 9         | 9      | 10.59%  |
| Crucial             | 8         | 9      | 9.41%   |
| SK hynix            | 4         | 4      | 4.71%   |
| WDC                 | 3         | 4      | 3.53%   |
| TAMMUZ              | 3         | 5      | 3.53%   |
| Micron Technology   | 3         | 4      | 3.53%   |
| Kingston            | 3         | 4      | 3.53%   |
| Intel               | 3         | 4      | 3.53%   |
| Apple               | 2         | 2      | 2.35%   |
| A-DATA Technology   | 2         | 2      | 2.35%   |
| TYPEC 1T            | 1         | 1      | 1.18%   |
| Transcend           | 1         | 2      | 1.18%   |
| Toshiba             | 1         | 1      | 1.18%   |
| Team                | 1         | 1      | 1.18%   |
| RevuAhn             | 1         | 1      | 1.18%   |
| Plextor             | 1         | 1      | 1.18%   |
| LITEONIT            | 1         | 1      | 1.18%   |
| KingSpec            | 1         | 1      | 1.18%   |
| IPLEX               | 1         | 1      | 1.18%   |
| Biostar             | 1         | 1      | 1.18%   |
| Apacer              | 1         | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 85        | 113    | 37.61%  |
| SSD     | 79        | 98     | 34.96%  |
| HDD     | 44        | 49     | 19.47%  |
| MMC     | 14        | 18     | 6.19%   |
| Unknown | 4         | 5      | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 99        | 138    | 47.14%  |
| NVMe | 85        | 113    | 40.48%  |
| MMC  | 14        | 18     | 6.67%   |
| SAS  | 12        | 14     | 5.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 104    | 68.64%  |
| 0.51-1.0   | 33        | 37     | 27.97%  |
| 1.01-2.0   | 3         | 5      | 2.54%   |
| 3.01-4.0   | 1         | 1      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 71        | 36.79%  |
| 251-500        | 40        | 20.73%  |
| 501-1000       | 25        | 12.95%  |
| 51-100         | 18        | 9.33%   |
| 1001-2000      | 15        | 7.77%   |
| 21-50          | 9         | 4.66%   |
| 1-20           | 8         | 4.15%   |
| More than 3000 | 4         | 2.07%   |
| 2001-3000      | 2         | 1.04%   |
| Unknown        | 1         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 83        | 41.92%  |
| 21-50     | 43        | 21.72%  |
| 101-250   | 27        | 13.64%  |
| 51-100    | 18        | 9.09%   |
| 251-500   | 14        | 7.07%   |
| 501-1000  | 6         | 3.03%   |
| 1001-2000 | 5         | 2.53%   |
| 2001-3000 | 1         | 0.51%   |
| Unknown   | 1         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB             | 1         | 1      | 7.69%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 7.69%   |
| Toshiba MK5061GSYN 500GB                 | 1         | 1      | 7.69%   |
| Toshiba MK2565GSX 250GB                  | 1         | 1      | 7.69%   |
| SK hynix HFS512G39TND-N210A 512GB SSD    | 1         | 1      | 7.69%   |
| SK hynix HFS128G3AMNM-1010A 128GB SSD    | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 830 Series 512GB | 1         | 1      | 7.69%   |
| Samsung Electronics SM961 NVMe 1024GB    | 1         | 1      | 7.69%   |
| Phison ES 512GB                          | 1         | 1      | 7.69%   |
| LITEONIT LMT-256M3M 256GB SSD            | 1         | 1      | 7.69%   |
| Kingston SHFS37A120G 120GB SSD           | 1         | 1      | 7.69%   |
| Hitachi HTS541616J9SA00 160GB            | 1         | 1      | 7.69%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 15.38%  |
| Toshiba             | 2         | 2      | 15.38%  |
| SK hynix            | 2         | 2      | 15.38%  |
| Samsung Electronics | 2         | 2      | 15.38%  |
| Phison              | 1         | 1      | 7.69%   |
| LITEONIT            | 1         | 1      | 7.69%   |
| Kingston            | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

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
| HDD  | 6         | 6      | 46.15%  |
| SSD  | 5         | 5      | 38.46%  |
| NVMe | 2         | 2      | 15.38%  |

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
| Detected | 107       | 158    | 53.5%   |
| Works    | 80        | 112    | 40%     |
| Malfunc  | 13        | 13     | 6.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 103       | 47.47%  |
| Samsung Electronics              | 28        | 12.9%   |
| AMD                              | 21        | 9.68%   |
| SanDisk                          | 19        | 8.76%   |
| SK hynix                         | 14        | 6.45%   |
| Phison Electronics               | 7         | 3.23%   |
| Toshiba America Info Systems     | 6         | 2.76%   |
| Kingston Technology Company      | 4         | 1.84%   |
| Apple                            | 3         | 1.38%   |
| ADATA Technology                 | 3         | 1.38%   |
| Union Memory (Shenzhen)          | 2         | 0.92%   |
| Nvidia                           | 2         | 0.92%   |
| Silicon Motion                   | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] | 1         | 0.46%   |
| Micron/Crucial Technology        | 1         | 0.46%   |
| Micron Technology                | 1         | 0.46%   |
| KIOXIA                           | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 8.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 5.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 4.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 4.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 3.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 3.13%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 6         | 2.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 6         | 2.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2.68%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 2.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 2.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 2.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 2.23%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 1.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.34%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 1.34%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 1.34%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 1.34%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.34%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 1.34%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.34%   |
| Intel SSD 660P Series                                                          | 3         | 1.34%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 1.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.34%   |
| Apple ANS2 NVMe Controller                                                     | 3         | 1.34%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.89%   |
| SK hynix BC511                                                                 | 2         | 0.89%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.89%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.89%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.89%   |
| Phison NVMe Storage Controller                                                 | 2         | 0.89%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.89%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 0.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 111       | 52.36%  |
| NVMe | 85        | 40.09%  |
| RAID | 10        | 4.72%   |
| IDE  | 6         | 2.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 150       | 81.97%  |
| AMD    | 32        | 17.49%  |
| ARM    | 1         | 0.55%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 3.28%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 3.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.73%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 2.73%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 2.19%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 2.19%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 2.19%   |
| Intel 12th Gen Core i5-1240P                  | 4         | 2.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.64%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 1.64%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.64%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 1.09%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 2         | 1.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.09%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 1.09%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.09%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 2         | 1.09%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 1.09%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 1.09%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.09%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 1.09%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.09%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 1.09%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.09%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.09%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.09%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 2         | 1.09%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.09%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.09%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.09%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.09%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 0.55%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.55%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.55%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 45        | 24.59%  |
| Intel Core i5        | 41        | 22.4%   |
| Other                | 22        | 12.02%  |
| Intel Core i3        | 11        | 6.01%   |
| AMD Ryzen 7          | 11        | 6.01%   |
| Intel Core 2 Duo     | 7         | 3.83%   |
| Intel Celeron        | 7         | 3.83%   |
| AMD Ryzen 5          | 7         | 3.83%   |
| Intel Pentium        | 4         | 2.19%   |
| Intel Atom           | 4         | 2.19%   |
| Intel Core i9        | 3         | 1.64%   |
| Intel Pentium Silver | 2         | 1.09%   |
| Intel Genuine        | 2         | 1.09%   |
| AMD Ryzen 9          | 2         | 1.09%   |
| AMD Ryzen 7 PRO      | 2         | 1.09%   |
| AMD Ryzen 5 PRO      | 2         | 1.09%   |
| AMD Ryzen 3          | 2         | 1.09%   |
| AMD A4               | 2         | 1.09%   |
| AMD A10              | 2         | 1.09%   |
| Intel Xeon           | 1         | 0.55%   |
| Intel Pentium Dual   | 1         | 0.55%   |
| Intel Core 2         | 1         | 0.55%   |
| AMD Quad-Core        | 1         | 0.55%   |
| AMD Athlon II        | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 70        | 38.25%  |
| 4       | 68        | 37.16%  |
| 8       | 20        | 10.93%  |
| 6       | 16        | 8.74%   |
| 12      | 6         | 3.28%   |
| 14      | 1         | 0.55%   |
| 1       | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 182       | 99.45%  |
| 2      | 1         | 0.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 149       | 81.42%  |
| 1       | 33        | 18.03%  |
| Unknown | 1         | 0.55%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 179       | 97.81%  |
| Unknown        | 2         | 1.09%   |
| 64-bit         | 1         | 0.55%   |
| 32-bit         | 1         | 0.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 12.77%  |
| 0x806ec    | 13        | 6.91%   |
| 0x806c1    | 12        | 6.38%   |
| 0x306a9    | 11        | 5.85%   |
| 0x206a7    | 9         | 4.79%   |
| 0x806ea    | 7         | 3.72%   |
| 0x20655    | 7         | 3.72%   |
| 0x08600106 | 7         | 3.72%   |
| 0x906a3    | 6         | 3.19%   |
| 0x806eb    | 6         | 3.19%   |
| 0x906e9    | 5         | 2.66%   |
| 0x706e5    | 5         | 2.66%   |
| 0x40651    | 5         | 2.66%   |
| 0x906ea    | 4         | 2.13%   |
| 0x706a1    | 4         | 2.13%   |
| 0x30678    | 4         | 2.13%   |
| 0x0a50000c | 4         | 2.13%   |
| 0x08108102 | 4         | 2.13%   |
| 0xa0652    | 3         | 1.6%    |
| 0x906ed    | 3         | 1.6%    |
| 0x806e9    | 3         | 1.6%    |
| 0x6fd      | 3         | 1.6%    |
| 0x306d4    | 3         | 1.6%    |
| 0x306c3    | 3         | 1.6%    |
| 0x1067a    | 3         | 1.6%    |
| 0xa0660    | 2         | 1.06%   |
| 0x406c3    | 2         | 1.06%   |
| 0x20652    | 2         | 1.06%   |
| 0x10676    | 2         | 1.06%   |
| 0x08608103 | 2         | 1.06%   |
| 0x08600103 | 2         | 1.06%   |
| 0x0700010f | 2         | 1.06%   |
| 0x06001119 | 2         | 1.06%   |
| 0x906a2    | 1         | 0.53%   |
| 0x806d1    | 1         | 0.53%   |
| 0x706a8    | 1         | 0.53%   |
| 0x6f6      | 1         | 0.53%   |
| 0x6e8      | 1         | 0.53%   |
| 0x406e3    | 1         | 0.53%   |
| 0x106e5    | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 44        | 24.04%  |
| Zen 2            | 13        | 7.1%    |
| TigerLake        | 13        | 7.1%    |
| Haswell          | 12        | 6.56%   |
| IvyBridge        | 11        | 6.01%   |
| Westmere         | 10        | 5.46%   |
| SandyBridge      | 10        | 5.46%   |
| Unknown          | 8         | 4.37%   |
| Silvermont       | 7         | 3.83%   |
| IceLake          | 7         | 3.83%   |
| Penryn           | 6         | 3.28%   |
| Zen 3            | 5         | 2.73%   |
| Goldmont plus    | 5         | 2.73%   |
| CometLake        | 5         | 2.73%   |
| Zen+             | 4         | 2.19%   |
| Core             | 4         | 2.19%   |
| Skylake          | 3         | 1.64%   |
| Broadwell        | 3         | 1.64%   |
| Alderlake Hybrid | 3         | 1.64%   |
| Piledriver       | 2         | 1.09%   |
| Jaguar           | 2         | 1.09%   |
| Zen              | 1         | 0.55%   |
| P6               | 1         | 0.55%   |
| Nehalem          | 1         | 0.55%   |
| K10              | 1         | 0.55%   |
| Excavator        | 1         | 0.55%   |
| Bonnell          | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 133       | 57.33%  |
| Nvidia                           | 56        | 24.14%  |
| AMD                              | 42        | 18.1%   |
| Silicon Integrated Systems [SiS] | 1         | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 13        | 5.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 5.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 4.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 3.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 3.78%   |
| Intel UHD Graphics 620                                                                   | 7         | 2.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.94%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 7         | 2.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.68%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.68%   |
| Intel HD Graphics 630                                                                    | 4         | 1.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.68%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 1.26%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.26%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 1.26%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.26%   |
| Nvidia TU117M                                                                            | 2         | 0.84%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.84%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.84%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.84%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 0.84%   |
| Intel HD Graphics 620                                                                    | 2         | 0.84%   |
| Intel HD Graphics 530                                                                    | 2         | 0.84%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.84%   |
| Intel Comet Lake UHD Graphics                                                            | 2         | 0.84%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 2         | 0.84%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 0.84%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 0.84%   |
| AMD Lucienne                                                                             | 2         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 87        | 47.54%  |
| Intel + Nvidia | 39        | 21.31%  |
| 1 x AMD        | 29        | 15.85%  |
| 1 x Nvidia     | 12        | 6.56%   |
| Intel + AMD    | 6         | 3.28%   |
| AMD + Nvidia   | 4         | 2.19%   |
| 2 x AMD        | 3         | 1.64%   |
| Other          | 1         | 0.55%   |
| 2 x Nvidia     | 1         | 0.55%   |
| 1 x SiS        | 1         | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 149       | 80.54%  |
| Proprietary | 27        | 14.59%  |
| Unknown     | 9         | 4.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 59.68%  |
| 0.01-0.5   | 22        | 11.83%  |
| 3.01-4.0   | 18        | 9.68%   |
| 1.01-2.0   | 18        | 9.68%   |
| 0.51-1.0   | 10        | 5.38%   |
| 5.01-6.0   | 4         | 2.15%   |
| 7.01-8.0   | 3         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 40        | 19.14%  |
| AU Optronics            | 35        | 16.75%  |
| Samsung Electronics     | 27        | 12.92%  |
| BOE                     | 27        | 12.92%  |
| Chimei Innolux          | 18        | 8.61%   |
| Goldstar                | 10        | 4.78%   |
| Sharp                   | 8         | 3.83%   |
| Apple                   | 8         | 3.83%   |
| PANDA                   | 4         | 1.91%   |
| JCH                     | 3         | 1.44%   |
| Dell                    | 3         | 1.44%   |
| CPT                     | 3         | 1.44%   |
| Philips                 | 2         | 0.96%   |
| CSO                     | 2         | 0.96%   |
| Chi Mei Optoelectronics | 2         | 0.96%   |
| BenQ                    | 2         | 0.96%   |
| ALP                     | 2         | 0.96%   |
| VMO                     | 1         | 0.48%   |
| TMX                     | 1         | 0.48%   |
| Sony                    | 1         | 0.48%   |
| PRISM+                  | 1         | 0.48%   |
| MSI                     | 1         | 0.48%   |
| Lenovo                  | 1         | 0.48%   |
| InfoVision              | 1         | 0.48%   |
| HKC                     | 1         | 0.48%   |
| Hewlett-Packard         | 1         | 0.48%   |
| HannStar                | 1         | 0.48%   |
| Denver                  | 1         | 0.48%   |
| CM_                     | 1         | 0.48%   |
| Ancor Communications    | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 1.89%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 1.42%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 1.42%   |
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 3         | 1.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 1.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.42%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 2         | 0.94%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 2         | 0.94%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 2         | 0.94%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch          | 2         | 0.94%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch          | 2         | 0.94%   |
| LG Display LCD Monitor LGD03B5 1920x1080 294x165mm 13.3-inch          | 2         | 0.94%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.94%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 0.94%   |
| BOE LCD Monitor BOE06D7 3840x2160 345x194mm 15.6-inch                 | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO6A92 1920x1080 344x194mm 15.5-inch        | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 2         | 0.94%   |
| AU Optronics LCD Monitor 1920x1080                                    | 2         | 0.94%   |
| Apple Color LCD APPA044 3072x1920 345x215mm 16.0-inch                 | 2         | 0.94%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch             | 1         | 0.47%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.47%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.47%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.47%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.47%   |
| Samsung Electronics U32H85x SAM0E3A 3840x2160 697x392mm 31.5-inch     | 1         | 0.47%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM01A2 1280x1024 376x301mm 19.0-inch  | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0138 1280x1024 338x270mm 17.0-inch  | 1         | 0.47%   |
| Samsung Electronics SMBX2350 SAM071E 1920x1080 509x286mm 23.0-inch    | 1         | 0.47%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1         | 0.47%   |
| Samsung Electronics S27R65 SAM1045 1920x1080 598x336mm 27.0-inch      | 1         | 0.47%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5643 1280x800 303x190mm 14.1-inch  | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 102       | 51%     |
| 1366x768 (WXGA)    | 35        | 17.5%   |
| 3840x2160 (4K)     | 10        | 5%      |
| 2560x1600          | 9         | 4.5%    |
| 2560x1440 (QHD)    | 7         | 3.5%    |
| 1600x900 (HD+)     | 7         | 3.5%    |
| 1920x1200 (WUXGA)  | 6         | 3%      |
| 1280x800 (WXGA)    | 6         | 3%      |
| 3440x1440          | 3         | 1.5%    |
| 2880x1800          | 3         | 1.5%    |
| 1440x900 (WXGA+)   | 3         | 1.5%    |
| 3072x1920          | 2         | 1%      |
| 1680x1050 (WSXGA+) | 2         | 1%      |
| 1280x1024 (SXGA)   | 2         | 1%      |
| 3840x2400          | 1         | 0.5%    |
| 2560x1080          | 1         | 0.5%    |
| 1680x945           | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 86        | 40.76%  |
| 13      | 33        | 15.64%  |
| 14      | 26        | 12.32%  |
| 24      | 9         | 4.27%   |
| 17      | 9         | 4.27%   |
| 16      | 8         | 3.79%   |
| 23      | 7         | 3.32%   |
| 31      | 5         | 2.37%   |
| 27      | 5         | 2.37%   |
| 21      | 4         | 1.9%    |
| 34      | 3         | 1.42%   |
| 20      | 3         | 1.42%   |
| 12      | 2         | 0.95%   |
| 11      | 2         | 0.95%   |
| Unknown | 2         | 0.95%   |
| 74      | 1         | 0.47%   |
| 54      | 1         | 0.47%   |
| 40      | 1         | 0.47%   |
| 25      | 1         | 0.47%   |
| 19      | 1         | 0.47%   |
| 18      | 1         | 0.47%   |
| 10      | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 127       | 60.48%  |
| 201-300     | 28        | 13.33%  |
| 501-600     | 20        | 9.52%   |
| 351-400     | 12        | 5.71%   |
| 401-500     | 9         | 4.29%   |
| 601-700     | 6         | 2.86%   |
| 701-800     | 3         | 1.43%   |
| Unknown     | 2         | 0.95%   |
| 801-900     | 1         | 0.48%   |
| 1501-2000   | 1         | 0.48%   |
| 1001-1500   | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 145       | 78.8%   |
| 16/10   | 31        | 16.85%  |
| 21/9    | 3         | 1.63%   |
| 5/4     | 2         | 1.09%   |
| Unknown | 2         | 1.09%   |
| 3/2     | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 86        | 40.76%  |
| 81-90          | 38        | 18.01%  |
| 71-80          | 20        | 9.48%   |
| 201-250        | 17        | 8.06%   |
| 351-500        | 8         | 3.79%   |
| 121-130        | 8         | 3.79%   |
| 111-120        | 7         | 3.32%   |
| 301-350        | 5         | 2.37%   |
| 251-300        | 4         | 1.9%    |
| 151-200        | 4         | 1.9%    |
| More than 1000 | 2         | 0.95%   |
| 61-70          | 2         | 0.95%   |
| 51-60          | 2         | 0.95%   |
| 141-150        | 2         | 0.95%   |
| 91-100         | 2         | 0.95%   |
| Unknown        | 2         | 0.95%   |
| 41-50          | 1         | 0.47%   |
| 501-1000       | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 87        | 42.03%  |
| 101-120       | 43        | 20.77%  |
| 51-100        | 34        | 16.43%  |
| 161-240       | 29        | 14.01%  |
| More than 240 | 10        | 4.83%   |
| 1-50          | 2         | 0.97%   |
| Unknown       | 2         | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 142       | 74.35%  |
| 2     | 37        | 19.37%  |
| 0     | 9         | 4.71%   |
| 3     | 3         | 1.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 122       | 42.66%  |
| Realtek Semiconductor            | 89        | 31.12%  |
| Qualcomm Atheros                 | 23        | 8.04%   |
| Broadcom                         | 19        | 6.64%   |
| ASIX Electronics                 | 7         | 2.45%   |
| Marvell Technology Group         | 3         | 1.05%   |
| Apple                            | 3         | 1.05%   |
| TP-Link                          | 2         | 0.7%    |
| Ralink Technology                | 2         | 0.7%    |
| Nvidia                           | 2         | 0.7%    |
| MediaTek                         | 2         | 0.7%    |
| Lenovo                           | 2         | 0.7%    |
| Broadcom Limited                 | 2         | 0.7%    |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Samsung Electronics              | 1         | 0.35%   |
| Ralink                           | 1         | 0.35%   |
| Qualcomm                         | 1         | 0.35%   |
| Microsoft                        | 1         | 0.35%   |
| D-Link                           | 1         | 0.35%   |
| Comneon                          | 1         | 0.35%   |
| Arduino SA                       | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62        | 19.2%   |
| Intel Wi-Fi 6 AX200                                               | 21        | 6.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.41%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 3.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 3.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 3.1%    |
| Intel Wireless 7260                                               | 7         | 2.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 2.17%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.86%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.24%   |
| Intel Wireless 3165                                               | 4         | 1.24%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 4         | 1.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.93%   |
| Intel Wireless 7265                                               | 3         | 0.93%   |
| Intel Wireless 3160                                               | 3         | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.93%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.93%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.93%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.93%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                | 3         | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.62%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.62%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 118       | 65.19%  |
| Realtek Semiconductor | 19        | 10.5%   |
| Qualcomm Atheros      | 17        | 9.39%   |
| Broadcom              | 16        | 8.84%   |
| TP-Link               | 2         | 1.1%    |
| Ralink Technology     | 2         | 1.1%    |
| MediaTek              | 2         | 1.1%    |
| Broadcom Limited      | 2         | 1.1%    |
| Ralink                | 1         | 0.55%   |
| Qualcomm              | 1         | 0.55%   |
| D-Link                | 1         | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 21        | 11.54%  |
| Intel Wi-Fi 6 AX201                                           | 11        | 6.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 10        | 5.49%   |
| Intel Wireless 7260                                           | 7         | 3.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 7         | 3.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 6         | 3.3%    |
| Intel Wireless 8265 / 8275                                    | 5         | 2.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 5         | 2.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 5         | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 2.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 4         | 2.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 4         | 2.2%    |
| Intel Wireless 3165                                           | 4         | 2.2%    |
| Intel Gemini Lake PCH CNVi WiFi                               | 4         | 2.2%    |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 4         | 2.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3         | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 3         | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 1.65%   |
| Intel Wireless 7265                                           | 3         | 1.65%   |
| Intel Wireless 3160                                           | 3         | 1.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 3         | 1.65%   |
| Intel Centrino Wireless-N 2230                                | 3         | 1.65%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 3         | 1.65%   |
| Intel Centrino Advanced-N 6235                                | 3         | 1.65%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 3         | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                 | 3         | 1.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 2         | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 1.1%    |
| Intel WiFi Link 5100                                          | 2         | 1.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 1.1%    |
| Intel Centrino Advanced-N 6200                                | 2         | 1.1%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller        | 2         | 1.1%    |
| Broadcom BCM43162 802.11ac Wireless Network Adapter           | 2         | 1.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.55%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                         | 1         | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 84        | 63.16%  |
| Intel                            | 18        | 13.53%  |
| Qualcomm Atheros                 | 8         | 6.02%   |
| ASIX Electronics                 | 7         | 5.26%   |
| Marvell Technology Group         | 3         | 2.26%   |
| Broadcom                         | 3         | 2.26%   |
| Apple                            | 3         | 2.26%   |
| Nvidia                           | 2         | 1.5%    |
| Lenovo                           | 2         | 1.5%    |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |
| Samsung Electronics              | 1         | 0.75%   |
| Microsoft                        | 1         | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 62        | 44.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11        | 7.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 7.25%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 5.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.9%    |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 2.17%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.45%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.45%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.45%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.45%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.45%   |
| Apple iBridge                                                                  | 2         | 1.45%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.72%   |
| Microsoft Ethernet Adapter                                                     | 1         | 0.72%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.72%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.72%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.72%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.72%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.72%   |
| Intel Ethernet controller                                                      | 1         | 0.72%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.72%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.72%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.72%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.72%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.72%   |
| Apple Ethernet Adapter [A1277]                                                 | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 174       | 57.24%  |
| Ethernet | 127       | 41.78%  |
| Modem    | 2         | 0.66%   |
| Unknown  | 1         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 140       | 71.07%  |
| Ethernet | 57        | 28.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 104       | 56.83%  |
| 1     | 73        | 39.89%  |
| 0     | 4         | 2.19%   |
| 3     | 2         | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 182       | 99.45%  |
| Yes  | 1         | 0.55%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 66%     |
| Realtek Semiconductor           | 12        | 8%      |
| Broadcom                        | 11        | 7.33%   |
| Qualcomm Atheros Communications | 7         | 4.67%   |
| IMC Networks                    | 7         | 4.67%   |
| Lite-On Technology              | 4         | 2.67%   |
| Foxconn / Hon Hai               | 4         | 2.67%   |
| Apple                           | 4         | 2.67%   |
| Qcom                            | 1         | 0.67%   |
| Micro Star International        | 1         | 0.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 23        | 15.33%  |
| Intel AX201 Bluetooth                                                               | 22        | 14.67%  |
| Intel AX200 Bluetooth                                                               | 21        | 14%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 12%     |
| Realtek Bluetooth Radio                                                             | 8         | 5.33%   |
| Intel Bluetooth Device                                                              | 6         | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 3.33%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.67%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2%      |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 2%      |
| Lite-On Bluetooth Device                                                            | 3         | 2%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 2%      |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 2%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.33%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.33%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.33%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.33%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 1.33%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.33%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.33%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.33%   |
| Realtek CSR BS8510                                                                  | 1         | 0.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.67%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.67%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.67%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.67%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.67%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.67%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.67%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 142       | 65.14%  |
| AMD                              | 39        | 17.89%  |
| Nvidia                           | 25        | 11.47%  |
| Apple                            | 3         | 1.38%   |
| Lenovo                           | 2         | 0.92%   |
| JMTek                            | 2         | 0.92%   |
| Texas Instruments                | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] | 1         | 0.46%   |
| Razer USA                        | 1         | 0.46%   |
| Dell                             | 1         | 0.46%   |
| Unknown                          | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 26        | 9.85%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 7.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 4.92%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 4.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 4.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 4.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 3.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 2.65%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.89%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.52%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.52%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.14%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.14%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.14%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.14%   |
| Apple Audio Device                                                                                | 3         | 1.14%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 1.14%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.14%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.76%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 62        | 49.21%  |
| SK hynix            | 28        | 22.22%  |
| Micron Technology   | 13        | 10.32%  |
| Unknown             | 5         | 3.97%   |
| Kingston            | 3         | 2.38%   |
| A-DATA Technology   | 3         | 2.38%   |
| Unknown (ABCD)      | 2         | 1.59%   |
| Ramaxel Technology  | 2         | 1.59%   |
| Unknown             | 2         | 1.59%   |
| Unknown (09D5)      | 1         | 0.79%   |
| Team                | 1         | 0.79%   |
| Silicon Power       | 1         | 0.79%   |
| Imation             | 1         | 0.79%   |
| Essencore           | 1         | 0.79%   |
| Elpida              | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 5.11%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 2.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.92%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 2.19%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 3         | 2.19%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2.19%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 2.19%   |
| Samsung RAM M471A1G44AB0-CTD 8GB DDR4 2667MT/s                   | 3         | 2.19%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 2.19%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 1.46%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.46%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.46%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.46%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.46%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.46%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.46%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.46%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DDR4 2667MT/s                   | 2         | 1.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.46%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.46%   |
| Unknown                                                          | 2         | 1.46%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.73%   |
| Unknown RAM CL22-22-22 D4-3200 16384MB SODIMM DDR4 3200MT/s      | 1         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.73%   |
| Unknown (09D5) RAM Module 16384MB SODIMM DDR4 2400MT/s           | 1         | 0.73%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.73%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.73%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 1         | 0.73%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                 | 1         | 0.73%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM 1334MT/s                | 1         | 0.73%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB Row Of Chips DDR4 3200MT/s | 1         | 0.73%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.73%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 61        | 58.1%   |
| DDR3    | 25        | 23.81%  |
| LPDDR4  | 8         | 7.62%   |
| LPDDR3  | 6         | 5.71%   |
| SDRAM   | 2         | 1.9%    |
| LPDDR5  | 1         | 0.95%   |
| DDR2    | 1         | 0.95%   |
| Unknown | 1         | 0.95%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 81        | 75.7%   |
| Row Of Chips | 18        | 16.82%  |
| Unknown      | 5         | 4.67%   |
| DIMM         | 3         | 2.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 55        | 48.25%  |
| 4096  | 31        | 27.19%  |
| 16384 | 15        | 13.16%  |
| 2048  | 9         | 7.89%   |
| 32768 | 3         | 2.63%   |
| 1024  | 1         | 0.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 29        | 25.44%  |
| 3200  | 28        | 24.56%  |
| 1600  | 16        | 14.04%  |
| 2400  | 10        | 8.77%   |
| 2133  | 7         | 6.14%   |
| 4267  | 5         | 4.39%   |
| 1334  | 5         | 4.39%   |
| 3266  | 4         | 3.51%   |
| 1333  | 2         | 1.75%   |
| 8400  | 1         | 0.88%   |
| 6400  | 1         | 0.88%   |
| 4800  | 1         | 0.88%   |
| 4199  | 1         | 0.88%   |
| 2048  | 1         | 0.88%   |
| 1867  | 1         | 0.88%   |
| 1067  | 1         | 0.88%   |
| 800   | 1         | 0.88%   |

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
| Chicony Electronics                    | 32        | 20.78%  |
| IMC Networks                           | 18        | 11.69%  |
| Acer                                   | 17        | 11.04%  |
| Realtek Semiconductor                  | 13        | 8.44%   |
| Microdia                               | 12        | 7.79%   |
| Silicon Motion                         | 10        | 6.49%   |
| Quanta                                 | 7         | 4.55%   |
| Apple                                  | 7         | 4.55%   |
| Unknown                                | 6         | 3.9%    |
| Syntek                                 | 5         | 3.25%   |
| Suyin                                  | 5         | 3.25%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.25%   |
| SunplusIT                              | 4         | 2.6%    |
| Sunplus Innovation Technology          | 3         | 1.95%   |
| Z-Star Microelectronics                | 2         | 1.3%    |
| Luxvisions Innotech Limited            | 2         | 1.3%    |
| Microsoft                              | 1         | 0.65%   |
| Logitech                               | 1         | 0.65%   |
| Lenovo                                 | 1         | 0.65%   |
| Goodong Industry                       | 1         | 0.65%   |
| DigiTech                               | 1         | 0.65%   |
| Alcor Micro                            | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 10        | 6.41%   |
| Microdia Integrated_Webcam_HD                           | 7         | 4.49%   |
| Unknown 720p HD Camera                                  | 6         | 3.85%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 6         | 3.85%   |
| IMC Networks Integrated Camera                          | 6         | 3.85%   |
| Realtek LG Camera                                       | 5         | 3.21%   |
| Chicony HD Webcam                                       | 5         | 3.21%   |
| Acer HD Webcam                                          | 5         | 3.21%   |
| Syntek Integrated Camera                                | 3         | 1.92%   |
| Suyin HP Truevision HD                                  | 3         | 1.92%   |
| SunplusIT 1080p FHD Camera                              | 3         | 1.92%   |
| Silicon Motion LG HD WebCam                             | 3         | 1.92%   |
| Quanta HP TrueVision HD Camera                          | 3         | 1.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.92%   |
| Chicony LG Camera                                       | 3         | 1.92%   |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 1.92%   |
| Acer Integrated Camera                                  | 3         | 1.92%   |
| Z-Star Webcam                                           | 2         | 1.28%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 2         | 1.28%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.28%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.28%   |
| Quanta LG Webcam                                        | 2         | 1.28%   |
| Chicony USB 2.0 Camera                                  | 2         | 1.28%   |
| Chicony LG HD WebCam                                    | 2         | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.28%   |
| Apple iPhone 5/5C/5S/6/SE                               | 2         | 1.28%   |
| Apple Built-in iSight                                   | 2         | 1.28%   |
| Acer Lenovo EasyCamera                                  | 2         | 1.28%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.64%   |
| Syntek HP Webcam                                        | 1         | 0.64%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.64%   |
| Suyin HP TrueVision Full HD                             | 1         | 0.64%   |
| SunplusIT 720p HD Camera                                | 1         | 0.64%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.64%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.64%   |
| Sunplus Asus Webcam                                     | 1         | 0.64%   |
| Silicon Motion WebCam SC-13HDN10939N                    | 1         | 0.64%   |
| Silicon Motion WebCam SC-13HDL11431N                    | 1         | 0.64%   |
| Silicon Motion WebCam SC-10HDD13335N                    | 1         | 0.64%   |
| Silicon Motion Web Camera                               | 1         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 13        | 33.33%  |
| Validity Sensors                   | 8         | 20.51%  |
| Samsung Electronics                | 5         | 12.82%  |
| Shenzhen Goodix Technology         | 4         | 10.26%  |
| Upek                               | 3         | 7.69%   |
| LighTuning Technology              | 2         | 5.13%   |
| Elan Microelectronics              | 2         | 5.13%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.56%   |
| AuthenTec                          | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown                                                         | 6         | 15.38%  |
| Samsung Fingerprint Sensor Device - 730B                        | 4         | 10.26%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 3         | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 5.13%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 5.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 2         | 5.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 5.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 5.13%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 5.13%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 5.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 5.13%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 1         | 2.56%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 2.56%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 2.56%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.56%   |
| Synaptics WBDI Device                                           | 1         | 2.56%   |
| Samsung Fingerprint Device                                      | 1         | 2.56%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.56%   |
| Elan ELAN:Fingerprint                                           | 1         | 2.56%   |
| Elan ELAN:ARM-M4                                                | 1         | 2.56%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 2.56%   |

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
| 0     | 106       | 56.99%  |
| 1     | 68        | 36.56%  |
| 2     | 9         | 4.84%   |
| 3     | 3         | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 39        | 41.49%  |
| Graphics card         | 23        | 24.47%  |
| Net/wireless          | 14        | 14.89%  |
| Chipcard              | 7         | 7.45%   |
| Multimedia controller | 4         | 4.26%   |
| Bluetooth             | 3         | 3.19%   |
| Net/ethernet          | 2         | 2.13%   |
| Sound                 | 1         | 1.06%   |
| Network               | 1         | 1.06%   |

