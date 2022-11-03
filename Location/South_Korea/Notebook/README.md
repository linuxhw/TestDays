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

Total: 246

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 42        | 22.22%  |
| Ubuntu 18.04                 | 18        | 9.52%   |
| Ubuntu 22.04                 | 8         | 4.23%   |
| Ubuntu 21.10                 | 7         | 3.7%    |
| Gooroom                      | 6         | 3.17%   |
| Arch                         | 6         | 3.17%   |
| Arch Rolling                 | 5         | 2.65%   |
| Linux Mint 20.3              | 4         | 2.12%   |
| Linux Mint 20.1              | 4         | 2.12%   |
| Fedora 36                    | 4         | 2.12%   |
| Fedora 32                    | 4         | 2.12%   |
| Ubuntu 19.10                 | 3         | 1.59%   |
| Ubuntu 19.04                 | 3         | 1.59%   |
| ROSA R11                     | 3         | 1.59%   |
| OpenMandriva 4.2             | 3         | 1.59%   |
| HamoniKR 4.0                 | 3         | 1.59%   |
| Fedora 34                    | 3         | 1.59%   |
| Debian 10                    | 3         | 1.59%   |
| Zorin 15                     | 2         | 1.06%   |
| Ubuntu MATE 18.04            | 2         | 1.06%   |
| ROSA R10                     | 2         | 1.06%   |
| Pop!_OS 21.10                | 2         | 1.06%   |
| Manjaro 21.3.0               | 2         | 1.06%   |
| LMDE 5                       | 2         | 1.06%   |
| Linux Mint 20                | 2         | 1.06%   |
| KDE neon 20.04               | 2         | 1.06%   |
| Endless 3.8.5                | 2         | 1.06%   |
| Debian 11                    | 2         | 1.06%   |
| CentOS 8                     | 2         | 1.06%   |
| Zorin 16                     | 1         | 0.53%   |
| Xubuntu 20.04                | 1         | 0.53%   |
| Ubuntu Unity 18.04           | 1         | 0.53%   |
| Ubuntu Unity 16.04           | 1         | 0.53%   |
| Ubuntu 21.04                 | 1         | 0.53%   |
| Ubuntu 20.10                 | 1         | 0.53%   |
| Pop!_OS 21.04                | 1         | 0.53%   |
| Pop!_OS 20.10                | 1         | 0.53%   |
| Pop!_OS 20.04                | 1         | 0.53%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.53%   |
| OpenMandriva 4.50            | 1         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 81        | 44.51%  |
| Linux Mint   | 12        | 6.59%   |
| Fedora       | 12        | 6.59%   |
| Arch         | 9         | 4.95%   |
| Manjaro      | 8         | 4.4%    |
| Gooroom      | 7         | 3.85%   |
| ROSA         | 5         | 2.75%   |
| OpenMandriva | 5         | 2.75%   |
| Endless      | 5         | 2.75%   |
| Debian       | 5         | 2.75%   |
| HamoniKR     | 4         | 2.2%    |
| Zorin        | 3         | 1.65%   |
| Pop!_OS      | 3         | 1.65%   |
| No1          | 3         | 1.65%   |
| Kubuntu      | 3         | 1.65%   |
| Ubuntu Unity | 2         | 1.1%    |
| Ubuntu MATE  | 2         | 1.1%    |
| LMDE         | 2         | 1.1%    |
| KDE neon     | 2         | 1.1%    |
| EndeavourOS  | 2         | 1.1%    |
| CentOS       | 2         | 1.1%    |
| Xubuntu      | 1         | 0.55%   |
| openSUSE     | 1         | 0.55%   |
| Lubuntu      | 1         | 0.55%   |
| Gentoo       | 1         | 0.55%   |
| Garuda Linux | 1         | 0.55%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 4         | 1.99%   |
| 5.10.0-17-amd64                 | 4         | 1.99%   |
| 5.4.0-58-generic                | 3         | 1.49%   |
| 5.4.0-26-generic                | 3         | 1.49%   |
| 5.3.0-40-generic                | 3         | 1.49%   |
| 5.19.15-201.fc36.x86_64         | 3         | 1.49%   |
| 5.11.0-37-generic               | 3         | 1.49%   |
| 4.19.0-9-amd64                  | 3         | 1.49%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3         | 1.49%   |
| 5.8.4-200.fc32.x86_64           | 2         | 1%      |
| 5.8.0-53-generic                | 2         | 1%      |
| 5.8.0-43-generic                | 2         | 1%      |
| 5.4.0-81-generic                | 2         | 1%      |
| 5.4.0-56-generic                | 2         | 1%      |
| 5.4.0-48-generic                | 2         | 1%      |
| 5.4.0-39-generic                | 2         | 1%      |
| 5.4.0-33-generic                | 2         | 1%      |
| 5.4.0-31-generic                | 2         | 1%      |
| 5.4.0-29-generic                | 2         | 1%      |
| 5.3.0-46-generic                | 2         | 1%      |
| 5.18.5-1-MANJARO                | 2         | 1%      |
| 5.15.0-52-generic               | 2         | 1%      |
| 5.15.0-33-generic               | 2         | 1%      |
| 5.15.0-27-generic               | 2         | 1%      |
| 5.13.0-44-generic               | 2         | 1%      |
| 5.13.0-28-generic               | 2         | 1%      |
| 5.13.0-27-generic               | 2         | 1%      |
| 5.10.14-desktop-1omv4002        | 2         | 1%      |
| 5.0.0-37-generic                | 2         | 1%      |
| 5.0.0-25-generic                | 2         | 1%      |
| 5.0.0-13-generic                | 2         | 1%      |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 1%      |
| 4.18.0-17-generic               | 2         | 1%      |
| 4.15.0-112-generic              | 2         | 1%      |
| 6.0.6-Wataten-T2-xanmod1-1      | 1         | 0.5%    |
| 6.0.0-t2                        | 1         | 0.5%    |
| 5.9.9-zen1-1-zen                | 1         | 0.5%    |
| 5.8.18-050818-generic           | 1         | 0.5%    |
| 5.8.15-301.fc33.x86_64          | 1         | 0.5%    |
| 5.8.0-59-generic                | 1         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 45        | 23.2%   |
| 5.13.0  | 12        | 6.19%   |
| 5.8.0   | 11        | 5.67%   |
| 5.15.0  | 10        | 5.15%   |
| 5.11.0  | 10        | 5.15%   |
| 4.15.0  | 10        | 5.15%   |
| 5.3.0   | 9         | 4.64%   |
| 5.10.0  | 7         | 3.61%   |
| 5.0.0   | 7         | 3.61%   |
| 4.18.0  | 7         | 3.61%   |
| 4.19.0  | 6         | 3.09%   |
| 5.19.15 | 3         | 1.55%   |
| 5.8.4   | 2         | 1.03%   |
| 5.18.5  | 2         | 1.03%   |
| 5.16.19 | 2         | 1.03%   |
| 5.15.11 | 2         | 1.03%   |
| 5.14.0  | 2         | 1.03%   |
| 5.10.14 | 2         | 1.03%   |
| 4.9.60  | 2         | 1.03%   |
| 6.0.6   | 1         | 0.52%   |
| 6.0.0   | 1         | 0.52%   |
| 5.9.9   | 1         | 0.52%   |
| 5.8.18  | 1         | 0.52%   |
| 5.8.15  | 1         | 0.52%   |
| 5.7.17  | 1         | 0.52%   |
| 5.6.11  | 1         | 0.52%   |
| 5.6.0   | 1         | 0.52%   |
| 5.5.2   | 1         | 0.52%   |
| 5.4.61  | 1         | 0.52%   |
| 5.4.55  | 1         | 0.52%   |
| 5.3.7   | 1         | 0.52%   |
| 5.2.11  | 1         | 0.52%   |
| 5.19.11 | 1         | 0.52%   |
| 5.18.17 | 1         | 0.52%   |
| 5.16.8  | 1         | 0.52%   |
| 5.16.7  | 1         | 0.52%   |
| 5.16.5  | 1         | 0.52%   |
| 5.15.8  | 1         | 0.52%   |
| 5.15.2  | 1         | 0.52%   |
| 5.15.16 | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 47        | 24.35%  |
| 5.15    | 17        | 8.81%   |
| 5.8     | 15        | 7.77%   |
| 5.11    | 15        | 7.77%   |
| 5.13    | 13        | 6.74%   |
| 5.10    | 11        | 5.7%    |
| 4.15    | 11        | 5.7%    |
| 5.3     | 10        | 5.18%   |
| 4.18    | 8         | 4.15%   |
| 5.0     | 7         | 3.63%   |
| 4.19    | 7         | 3.63%   |
| 5.16    | 5         | 2.59%   |
| 5.12    | 5         | 2.59%   |
| 5.19    | 4         | 2.07%   |
| 5.14    | 4         | 2.07%   |
| 5.18    | 3         | 1.55%   |
| 6.0     | 2         | 1.04%   |
| 5.6     | 2         | 1.04%   |
| 4.9     | 2         | 1.04%   |
| 5.9     | 1         | 0.52%   |
| 5.7     | 1         | 0.52%   |
| 5.5     | 1         | 0.52%   |
| 5.2     | 1         | 0.52%   |
| 4.16    | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 173       | 98.3%   |
| i686    | 2         | 1.14%   |
| aarch64 | 1         | 0.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 95        | 52.2%   |
| KDE5            | 23        | 12.64%  |
| Unknown         | 17        | 9.34%   |
| X-Cinnamon      | 11        | 6.04%   |
| XFCE            | 7         | 3.85%   |
| GNOME Flashback | 7         | 3.85%   |
| Cinnamon        | 6         | 3.3%    |
| LXDE            | 3         | 1.65%   |
| KDE4            | 3         | 1.65%   |
| KDE             | 3         | 1.65%   |
| Unity           | 2         | 1.1%    |
| MATE            | 2         | 1.1%    |
| i3              | 2         | 1.1%    |
| sway            | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 131       | 73.6%   |
| Wayland | 31        | 17.42%  |
| Unknown | 13        | 7.3%    |
| Tty     | 3         | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 86        | 46.99%  |
| GDM     | 37        | 20.22%  |
| SDDM    | 20        | 10.93%  |
| LightDM | 14        | 7.65%   |
| TDM     | 13        | 7.1%    |
| GDM3    | 9         | 4.92%   |
| KDM     | 3         | 1.64%   |
| XDM     | 1         | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ko_KR   | 83        | 45.6%   |
| en_US   | 59        | 32.42%  |
| Unknown | 25        | 13.74%  |
| zh_CN   | 3         | 1.65%   |
| en_CA   | 3         | 1.65%   |
| id_ID   | 2         | 1.1%    |
| C       | 2         | 1.1%    |
| vi_VN   | 1         | 0.55%   |
| pt_BR   | 1         | 0.55%   |
| fr_FR   | 1         | 0.55%   |
| en_NZ   | 1         | 0.55%   |
| ar_EG   | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 124       | 70.06%  |
| BIOS | 53        | 29.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 148       | 83.15%  |
| Btrfs   | 12        | 6.74%   |
| Overlay | 6         | 3.37%   |
| Unknown | 6         | 3.37%   |
| Xfs     | 4         | 2.25%   |
| Zfs     | 2         | 1.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 86        | 47.78%  |
| GPT     | 84        | 46.67%  |
| MBR     | 10        | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 167       | 94.35%  |
| Yes       | 10        | 5.65%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 67.6%   |
| Yes       | 58        | 32.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 36        | 20.45%  |
| Samsung Electronics | 22        | 12.5%   |
| Hewlett-Packard     | 22        | 12.5%   |
| LG Electronics      | 19        | 10.8%   |
| ASUSTek Computer    | 18        | 10.23%  |
| Dell                | 13        | 7.39%   |
| MSI                 | 10        | 5.68%   |
| Apple               | 8         | 4.55%   |
| HANSUNG COMPUTER    | 4         | 2.27%   |
| Notebook            | 3         | 1.7%    |
| Acer                | 3         | 1.7%    |
| Toshiba             | 2         | 1.14%   |
| Wolfnfox            | 1         | 0.57%   |
| TG                  | 1         | 0.57%   |
| Teclast             | 1         | 0.57%   |
| Sony                | 1         | 0.57%   |
| SLIMBOOK            | 1         | 0.57%   |
| Pine Microsystems   | 1         | 0.57%   |
| MS                  | 1         | 0.57%   |
| MECHREVO            | 1         | 0.57%   |
| Jooyontech Computer | 1         | 0.57%   |
| Intel               | 1         | 0.57%   |
| IMUZ                | 1         | 0.57%   |
| Google              | 1         | 0.57%   |
| Clevo               | 1         | 0.57%   |
| AVERATEC            | 1         | 0.57%   |
| AMI                 | 1         | 0.57%   |
| Alienware           | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung 950XED                                    | 2         | 1.14%   |
| Samsung 950XCJ/951XCJ/950XCR                      | 2         | 1.14%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01S00              | 2         | 1.14%   |
| Lenovo IdeaPad 3 15IIL05 81WE                     | 2         | 1.14%   |
| HP Stream Notebook PC 13                          | 2         | 1.14%   |
| HP Laptop 15-db1xxx                               | 2         | 1.14%   |
| HANSUNG COMPUTER TFX5470H                         | 2         | 1.14%   |
| Dell XPS 15 7590                                  | 2         | 1.14%   |
| Apple MacBookPro16,1                              | 2         | 1.14%   |
| Wolfnfox WF-TBAT                                  | 1         | 0.57%   |
| Toshiba Satellite P50-B-103                       | 1         | 0.57%   |
| Toshiba Satellite L655                            | 1         | 0.57%   |
| TG NXI-A7000 Series                               | 1         | 0.57%   |
| Teclast tPAD                                      | 1         | 0.57%   |
| Sony VPCEA36FK                                    | 1         | 0.57%   |
| SLIMBOOK PROX15-AMD                               | 1         | 0.57%   |
| Samsung X120/X170/X171                            | 1         | 0.57%   |
| Samsung SX11S                                     | 1         | 0.57%   |
| Samsung RC420/RC520/RC720                         | 1         | 0.57%   |
| Samsung R59P/R60P/R61P                            | 1         | 0.57%   |
| Samsung R440/R480                                 | 1         | 0.57%   |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.57%   |
| Samsung 905S3G/906S3G/915S3G                      | 1         | 0.57%   |
| Samsung 800G5M/800G5W                             | 1         | 0.57%   |
| Samsung 760XBE                                    | 1         | 0.57%   |
| Samsung 730QCJ/730QCR                             | 1         | 0.57%   |
| Samsung 670Z5E                                    | 1         | 0.57%   |
| Samsung 570Z5E/580Z5E                             | 1         | 0.57%   |
| Samsung 550XED                                    | 1         | 0.57%   |
| Samsung 530U3BI/530U4BI/530U4BH                   | 1         | 0.57%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.57%   |
| Samsung 400B4C/400B5C/200B4C/200B5C               | 1         | 0.57%   |
| Samsung 400B4B/400B5B/200B4B/200B5B               | 1         | 0.57%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.57%   |
| Pine Microsystems Pine64 Pinebook Pro             | 1         | 0.57%   |
| Notebook W330SU2                                  | 1         | 0.57%   |
| Notebook NL5xRU                                   | 1         | 0.57%   |
| Notebook N650DU                                   | 1         | 0.57%   |
| MSI PS63 Modern 8RC                               | 1         | 0.57%   |
| MSI PS42 Modern 8MO                               | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 24        | 13.64%  |
| Lenovo IdeaPad            | 7         | 3.98%   |
| HP Pavilion               | 7         | 3.98%   |
| ASUS VivoBook             | 7         | 3.98%   |
| HP Laptop                 | 4         | 2.27%   |
| HP EliteBook              | 4         | 2.27%   |
| Dell XPS                  | 4         | 2.27%   |
| Dell Inspiron             | 4         | 2.27%   |
| HP Stream                 | 3         | 1.7%    |
| Toshiba Satellite         | 2         | 1.14%   |
| Samsung 950XED            | 2         | 1.14%   |
| Samsung 950XCJ            | 2         | 1.14%   |
| MSI Prestige              | 2         | 1.14%   |
| HP ProBook                | 2         | 1.14%   |
| HANSUNG COMPUTER TFX5470H | 2         | 1.14%   |
| Dell Latitude             | 2         | 1.14%   |
| ASUS TUF                  | 2         | 1.14%   |
| ASUS ROG                  | 2         | 1.14%   |
| Apple MacBookPro5         | 2         | 1.14%   |
| Apple MacBookPro16        | 2         | 1.14%   |
| Acer Swift                | 2         | 1.14%   |
| Wolfnfox WF-TBAT          | 1         | 0.57%   |
| TG NXI-A7000              | 1         | 0.57%   |
| Teclast tPAD              | 1         | 0.57%   |
| Sony VPCEA36FK            | 1         | 0.57%   |
| SLIMBOOK PROX15-AMD       | 1         | 0.57%   |
| Samsung X120              | 1         | 0.57%   |
| Samsung SX11S             | 1         | 0.57%   |
| Samsung RC420             | 1         | 0.57%   |
| Samsung R59P              | 1         | 0.57%   |
| Samsung R440              | 1         | 0.57%   |
| Samsung 950XDB            | 1         | 0.57%   |
| Samsung 905S3G            | 1         | 0.57%   |
| Samsung 800G5M            | 1         | 0.57%   |
| Samsung 760XBE            | 1         | 0.57%   |
| Samsung 730QCJ            | 1         | 0.57%   |
| Samsung 670Z5E            | 1         | 0.57%   |
| Samsung 570Z5E            | 1         | 0.57%   |
| Samsung 550XED            | 1         | 0.57%   |
| Samsung 530U3BI           | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 36        | 20.45%  |
| 2019    | 21        | 11.93%  |
| 2021    | 19        | 10.8%   |
| 2018    | 16        | 9.09%   |
| 2014    | 14        | 7.95%   |
| 2013    | 13        | 7.39%   |
| 2011    | 11        | 6.25%   |
| 2010    | 7         | 3.98%   |
| 2008    | 7         | 3.98%   |
| 2015    | 6         | 3.41%   |
| 2022    | 5         | 2.84%   |
| 2012    | 5         | 2.84%   |
| 2017    | 4         | 2.27%   |
| 2016    | 4         | 2.27%   |
| 2009    | 4         | 2.27%   |
| 2007    | 2         | 1.14%   |
| 2006    | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 176       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 156       | 87.64%  |
| Enabled  | 22        | 12.36%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 175       | 99.43%  |
| Yes  | 1         | 0.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 49        | 27.37%  |
| 16.01-24.0  | 37        | 20.67%  |
| 3.01-4.0    | 31        | 17.32%  |
| 8.01-16.0   | 29        | 16.2%   |
| 32.01-64.0  | 14        | 7.82%   |
| 1.01-2.0    | 12        | 6.7%    |
| 24.01-32.0  | 3         | 1.68%   |
| 64.01-256.0 | 3         | 1.68%   |
| 2.01-3.0    | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 64        | 32.99%  |
| 2.01-3.0   | 46        | 23.71%  |
| 4.01-8.0   | 30        | 15.46%  |
| 3.01-4.0   | 30        | 15.46%  |
| 0.51-1.0   | 15        | 7.73%   |
| 8.01-16.0  | 7         | 3.61%   |
| 16.01-24.0 | 2         | 1.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 117       | 64.64%  |
| 2      | 56        | 30.94%  |
| 3      | 6         | 3.31%   |
| 4      | 1         | 0.55%   |
| 0      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 147       | 83.52%  |
| Yes       | 29        | 16.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 69.66%  |
| No        | 54        | 30.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 94.89%  |
| No        | 9         | 5.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 80.79%  |
| No        | 34        | 19.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| South Korea | 176       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Seoul         | 31        | 16.76%  |
| Suwon         | 9         | 4.86%   |
| Seocho-gu     | 8         | 4.32%   |
| Gwanak-gu     | 7         | 3.78%   |
| Yongin-si     | 5         | 2.7%    |
| Uiwang        | 5         | 2.7%    |
| Seongnam-si   | 5         | 2.7%    |
| Jung-gu       | 5         | 2.7%    |
| Incheon       | 4         | 2.16%   |
| Hwaseong-si   | 4         | 2.16%   |
| Daejeon       | 4         | 2.16%   |
| Bupyeong-gu   | 4         | 2.16%   |
| Anyang-si     | 4         | 2.16%   |
| Yongsan-gu    | 3         | 1.62%   |
| Seongbuk-gu   | 3         | 1.62%   |
| Pyeongtaek-si | 3         | 1.62%   |
| Jeonju        | 3         | 1.62%   |
| Gwangju       | 3         | 1.62%   |
| Geumjeong-gu  | 3         | 1.62%   |
| Gangnam-gu    | 3         | 1.62%   |
| Busan         | 3         | 1.62%   |
| Yeonsu-gu     | 2         | 1.08%   |
| Namdong-gu    | 2         | 1.08%   |
| Nam-gu        | 2         | 1.08%   |
| Jeju City     | 2         | 1.08%   |
| Gyeongsan-si  | 2         | 1.08%   |
| Gimpo-si      | 2         | 1.08%   |
| Gangseo-gu    | 2         | 1.08%   |
| Danyang-gun   | 2         | 1.08%   |
| Daegu         | 2         | 1.08%   |
| Buk-gu        | 2         | 1.08%   |
| Yuseong-gu    | 1         | 0.54%   |
| Yuseong       | 1         | 0.54%   |
| Yongsan-dong  | 1         | 0.54%   |
| Yangju        | 1         | 0.54%   |
| Yangcheon-gu  | 1         | 0.54%   |
| Wonju         | 1         | 0.54%   |
| Suseong-gu    | 1         | 0.54%   |
| Sinsa-dong    | 1         | 0.54%   |
| Siheung-si    | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 60        | 71     | 25.97%  |
| WDC                     | 27        | 29     | 11.69%  |
| Unknown                 | 16        | 20     | 6.93%   |
| SK hynix                | 16        | 22     | 6.93%   |
| SanDisk                 | 15        | 15     | 6.49%   |
| Toshiba                 | 12        | 14     | 5.19%   |
| Seagate                 | 12        | 15     | 5.19%   |
| Crucial                 | 9         | 10     | 3.9%    |
| Kingston                | 7         | 8      | 3.03%   |
| Intel                   | 7         | 12     | 3.03%   |
| Hitachi                 | 5         | 6      | 2.16%   |
| Apple                   | 5         | 5      | 2.16%   |
| Phison                  | 4         | 4      | 1.73%   |
| Micron Technology       | 4         | 5      | 1.73%   |
| A-DATA Technology       | 4         | 4      | 1.73%   |
| TAMMUZ                  | 3         | 5      | 1.3%    |
| HGST                    | 3         | 4      | 1.3%    |
| Fujitsu                 | 2         | 2      | 0.87%   |
| VIVA300s                | 1         | 1      | 0.43%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.43%   |
| UMIS                    | 1         | 1      | 0.43%   |
| TYPEC 1T                | 1         | 1      | 0.43%   |
| Transcend               | 1         | 2      | 0.43%   |
| Team                    | 1         | 1      | 0.43%   |
| Silicon Motion          | 1         | 1      | 0.43%   |
| RevuAhn                 | 1         | 1      | 0.43%   |
| Plextor                 | 1         | 1      | 0.43%   |
| LITEONIT                | 1         | 1      | 0.43%   |
| KIOXIA                  | 1         | 1      | 0.43%   |
| KingSpec                | 1         | 1      | 0.43%   |
| JMicron Technology      | 1         | 1      | 0.43%   |
| ipTIME                  | 1         | 1      | 0.43%   |
| IPLEX                   | 1         | 1      | 0.43%   |
| Imation                 | 1         | 1      | 0.43%   |
| External                | 1         | 1      | 0.43%   |
| ES                      | 1         | 1      | 0.43%   |
| Biostar                 | 1         | 1      | 0.43%   |
| Apacer                  | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| SK hynix SHGP31-1000GM-2 1TB                         | 3         | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 1.22%   |
| Samsung SSD 860 EVO 500GB                            | 3         | 1.22%   |
| WDC WDS100T2B0C-00PXH0 1TB                           | 2         | 0.81%   |
| WDC WD50 00LPVX-22V0TT0 500GB                        | 2         | 0.81%   |
| Unknown SLD64G  64GB                                 | 2         | 0.81%   |
| Unknown SD/MMC/MS PRO 1TB                            | 2         | 0.81%   |
| Unknown MMC Card  32GB                               | 2         | 0.81%   |
| Toshiba KBG30ZMV256G 256GB                           | 2         | 0.81%   |
| SK hynix NVMe SSD Drive 256GB                        | 2         | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB                       | 2         | 0.81%   |
| SanDisk SD8SBAT256G1122 256GB SSD                    | 2         | 0.81%   |
| SanDisk NVMe SSD Drive 512GB                         | 2         | 0.81%   |
| SanDisk NVMe SSD Drive 256GB                         | 2         | 0.81%   |
| Samsung SSD 860 EVO 1TB                              | 2         | 0.81%   |
| Samsung SSD 830 Series 256GB                         | 2         | 0.81%   |
| Samsung SSD 750 EVO 120GB                            | 2         | 0.81%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 2         | 0.81%   |
| Samsung NVMe SSD Drive 2TB                           | 2         | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 2         | 0.81%   |
| Samsung MZVLB512HAJQ-00000 512GB                     | 2         | 0.81%   |
| Samsung MZVLB256HBHQ-000 256GB                       | 2         | 0.81%   |
| Samsung MZNLN256HAJQ-00000 256GB SSD                 | 2         | 0.81%   |
| Kingston OM8PCP3512F-AB 512GB                        | 2         | 0.81%   |
| HGST HTS721010A9E630 1TB                             | 2         | 0.81%   |
| Crucial CT500MX500SSD1 500GB                         | 2         | 0.81%   |
| Crucial CT1000MX500SSD1 1TB                          | 2         | 0.81%   |
| Apple ANS2 NVMe Controller 500GB                     | 2         | 0.81%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1         | 0.41%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                     | 1         | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                     | 1         | 0.41%   |
| WDC WDS120G1G0A-00SS50 120GB SSD                     | 1         | 0.41%   |
| WDC WD7500BPVT-22HXZT1 752GB                         | 1         | 0.41%   |
| WDC WD600BEVS-60LAT0 64GB                            | 1         | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB                         | 1         | 0.41%   |
| WDC WD3200BEKT-00F3T0 320GB                          | 1         | 0.41%   |
| WDC WD20SPZX-22UA7T0 2TB                             | 1         | 0.41%   |
| WDC WD10SPZX-75Z10T1 1TB                             | 1         | 0.41%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 1         | 0.41%   |
| WDC WD10SPZX-22Z10T0 1TB                             | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 13     | 30.23%  |
| Seagate             | 11        | 14     | 25.58%  |
| Toshiba             | 5         | 5      | 11.63%  |
| Hitachi             | 5         | 6      | 11.63%  |
| HGST                | 3         | 4      | 6.98%   |
| Unknown             | 2         | 2      | 4.65%   |
| Fujitsu             | 2         | 2      | 4.65%   |
| Samsung Electronics | 1         | 1      | 2.33%   |
| ipTIME              | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 38     | 39.76%  |
| SanDisk             | 9         | 9      | 10.84%  |
| Crucial             | 8         | 9      | 9.64%   |
| WDC                 | 3         | 4      | 3.61%   |
| TAMMUZ              | 3         | 5      | 3.61%   |
| SK hynix            | 3         | 3      | 3.61%   |
| Micron Technology   | 3         | 4      | 3.61%   |
| Kingston            | 3         | 4      | 3.61%   |
| Intel               | 3         | 4      | 3.61%   |
| Apple               | 2         | 2      | 2.41%   |
| A-DATA Technology   | 2         | 2      | 2.41%   |
| TYPEC 1T            | 1         | 1      | 1.2%    |
| Transcend           | 1         | 2      | 1.2%    |
| Toshiba             | 1         | 1      | 1.2%    |
| Team                | 1         | 1      | 1.2%    |
| RevuAhn             | 1         | 1      | 1.2%    |
| Plextor             | 1         | 1      | 1.2%    |
| LITEONIT            | 1         | 1      | 1.2%    |
| KingSpec            | 1         | 1      | 1.2%    |
| IPLEX               | 1         | 1      | 1.2%    |
| Biostar             | 1         | 1      | 1.2%    |
| Apacer              | 1         | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 79        | 105    | 36.41%  |
| SSD     | 77        | 96     | 35.48%  |
| HDD     | 43        | 48     | 19.82%  |
| MMC     | 14        | 18     | 6.45%   |
| Unknown | 4         | 5      | 1.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 97        | 136    | 48.26%  |
| NVMe | 79        | 105    | 39.3%   |
| MMC  | 14        | 18     | 6.97%   |
| SAS  | 11        | 13     | 5.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 102    | 68.38%  |
| 0.51-1.0   | 34        | 37     | 29.06%  |
| 1.01-2.0   | 2         | 4      | 1.71%   |
| 3.01-4.0   | 1         | 1      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 68        | 36.76%  |
| 251-500        | 39        | 21.08%  |
| 501-1000       | 23        | 12.43%  |
| 51-100         | 18        | 9.73%   |
| 1001-2000      | 13        | 7.03%   |
| 21-50          | 9         | 4.86%   |
| 1-20           | 8         | 4.32%   |
| More than 3000 | 4         | 2.16%   |
| 2001-3000      | 2         | 1.08%   |
| Unknown        | 1         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 82        | 42.93%  |
| 21-50     | 40        | 20.94%  |
| 101-250   | 26        | 13.61%  |
| 51-100    | 18        | 9.42%   |
| 251-500   | 14        | 7.33%   |
| 1001-2000 | 5         | 2.62%   |
| 501-1000  | 4         | 2.09%   |
| 2001-3000 | 1         | 0.52%   |
| Unknown   | 1         | 0.52%   |

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
| Detected | 102       | 150    | 52.85%  |
| Works    | 78        | 109    | 40.41%  |
| Malfunc  | 13        | 13     | 6.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 102       | 49.04%  |
| Samsung Electronics              | 27        | 12.98%  |
| AMD                              | 20        | 9.62%   |
| SanDisk                          | 17        | 8.17%   |
| SK hynix                         | 12        | 5.77%   |
| Toshiba America Info Systems     | 6         | 2.88%   |
| Phison Electronics               | 6         | 2.88%   |
| Kingston Technology Company      | 4         | 1.92%   |
| Apple                            | 3         | 1.44%   |
| Union Memory (Shenzhen)          | 2         | 0.96%   |
| Nvidia                           | 2         | 0.96%   |
| ADATA Technology                 | 2         | 0.96%   |
| Silicon Motion                   | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] | 1         | 0.48%   |
| Micron/Crucial Technology        | 1         | 0.48%   |
| Micron Technology                | 1         | 0.48%   |
| KIOXIA                           | 1         | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18        | 8.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 6.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 4.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 4.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 3.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 3.26%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 6         | 2.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 2.33%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 2.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 2.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 2.33%   |
| SK hynix Gold P31 SSD                                                          | 4         | 1.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.86%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.4%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 1.4%    |
| SK hynix Non-Volatile memory controller                                        | 3         | 1.4%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 1.4%    |
| SanDisk Non-Volatile memory controller                                         | 3         | 1.4%    |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.4%    |
| Intel SSD 660P Series                                                          | 3         | 1.4%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 1.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.4%    |
| Apple ANS2 NVMe Controller                                                     | 3         | 1.4%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.93%   |
| SK hynix BC511                                                                 | 2         | 0.93%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.93%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.93%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.93%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.93%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.93%   |
| Phison NVMe Storage Controller                                                 | 2         | 0.93%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.93%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 110       | 53.92%  |
| NVMe | 79        | 38.73%  |
| RAID | 9         | 4.41%   |
| IDE  | 6         | 2.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 144       | 81.82%  |
| AMD    | 31        | 17.61%  |
| ARM    | 1         | 0.57%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 3.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.84%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 2.84%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 2.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 2.27%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 2.27%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.7%    |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 1.7%    |
| Intel 12th Gen Core i5-1240P                  | 3         | 1.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.7%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 1.14%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 2         | 1.14%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.14%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 1.14%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 2         | 1.14%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 1.14%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 1.14%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.14%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 1.14%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.14%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 1.14%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.14%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.14%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 2         | 1.14%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.14%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.14%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 0.57%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.57%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.57%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 45        | 25.57%  |
| Intel Core i5        | 39        | 22.16%  |
| Other                | 18        | 10.23%  |
| Intel Core i3        | 11        | 6.25%   |
| AMD Ryzen 7          | 11        | 6.25%   |
| Intel Core 2 Duo     | 7         | 3.98%   |
| Intel Celeron        | 7         | 3.98%   |
| AMD Ryzen 5          | 7         | 3.98%   |
| Intel Pentium        | 4         | 2.27%   |
| Intel Atom           | 4         | 2.27%   |
| Intel Core i9        | 3         | 1.7%    |
| Intel Pentium Silver | 2         | 1.14%   |
| Intel Genuine        | 2         | 1.14%   |
| AMD Ryzen 7 PRO      | 2         | 1.14%   |
| AMD Ryzen 5 PRO      | 2         | 1.14%   |
| AMD Ryzen 3          | 2         | 1.14%   |
| AMD A4               | 2         | 1.14%   |
| AMD A10              | 2         | 1.14%   |
| Intel Xeon           | 1         | 0.57%   |
| Intel Pentium Dual   | 1         | 0.57%   |
| Intel Core 2         | 1         | 0.57%   |
| AMD Ryzen 9          | 1         | 0.57%   |
| AMD Quad-Core        | 1         | 0.57%   |
| AMD Athlon II        | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 69        | 39.2%   |
| 4       | 66        | 37.5%   |
| 8       | 19        | 10.8%   |
| 6       | 16        | 9.09%   |
| 12      | 4         | 2.27%   |
| 1       | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 175       | 99.43%  |
| 2      | 1         | 0.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 142       | 80.68%  |
| 1       | 33        | 18.75%  |
| Unknown | 1         | 0.57%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 172       | 97.73%  |
| Unknown        | 2         | 1.14%   |
| 64-bit         | 1         | 0.57%   |
| 32-bit         | 1         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 12.71%  |
| 0x806ec    | 12        | 6.63%   |
| 0x806c1    | 12        | 6.63%   |
| 0x306a9    | 11        | 6.08%   |
| 0x206a7    | 9         | 4.97%   |
| 0x806ea    | 7         | 3.87%   |
| 0x20655    | 7         | 3.87%   |
| 0x08600106 | 7         | 3.87%   |
| 0x806eb    | 6         | 3.31%   |
| 0x906e9    | 5         | 2.76%   |
| 0x706e5    | 5         | 2.76%   |
| 0x906ea    | 4         | 2.21%   |
| 0x706a1    | 4         | 2.21%   |
| 0x40651    | 4         | 2.21%   |
| 0x30678    | 4         | 2.21%   |
| 0x08108102 | 4         | 2.21%   |
| 0xa0652    | 3         | 1.66%   |
| 0x906ed    | 3         | 1.66%   |
| 0x906a3    | 3         | 1.66%   |
| 0x806e9    | 3         | 1.66%   |
| 0x6fd      | 3         | 1.66%   |
| 0x306d4    | 3         | 1.66%   |
| 0x306c3    | 3         | 1.66%   |
| 0x1067a    | 3         | 1.66%   |
| 0x0a50000c | 3         | 1.66%   |
| 0xa0660    | 2         | 1.1%    |
| 0x406c3    | 2         | 1.1%    |
| 0x20652    | 2         | 1.1%    |
| 0x10676    | 2         | 1.1%    |
| 0x08608103 | 2         | 1.1%    |
| 0x08600103 | 2         | 1.1%    |
| 0x0700010f | 2         | 1.1%    |
| 0x06001119 | 2         | 1.1%    |
| 0x906a2    | 1         | 0.55%   |
| 0x806d1    | 1         | 0.55%   |
| 0x706a8    | 1         | 0.55%   |
| 0x6f6      | 1         | 0.55%   |
| 0x6e8      | 1         | 0.55%   |
| 0x406e3    | 1         | 0.55%   |
| 0x106e5    | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 43        | 24.43%  |
| Zen 2            | 13        | 7.39%   |
| TigerLake        | 12        | 6.82%   |
| IvyBridge        | 11        | 6.25%   |
| Haswell          | 11        | 6.25%   |
| Westmere         | 10        | 5.68%   |
| SandyBridge      | 10        | 5.68%   |
| Silvermont       | 7         | 3.98%   |
| IceLake          | 7         | 3.98%   |
| Unknown          | 7         | 3.98%   |
| Penryn           | 6         | 3.41%   |
| Goldmont plus    | 5         | 2.84%   |
| CometLake        | 5         | 2.84%   |
| Zen+             | 4         | 2.27%   |
| Zen 3            | 4         | 2.27%   |
| Core             | 4         | 2.27%   |
| Skylake          | 3         | 1.7%    |
| Broadwell        | 3         | 1.7%    |
| Piledriver       | 2         | 1.14%   |
| Jaguar           | 2         | 1.14%   |
| Zen              | 1         | 0.57%   |
| P6               | 1         | 0.57%   |
| Nehalem          | 1         | 0.57%   |
| K10              | 1         | 0.57%   |
| Excavator        | 1         | 0.57%   |
| Bonnell          | 1         | 0.57%   |
| Alderlake Hybrid | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 127       | 56.95%  |
| Nvidia                           | 54        | 24.22%  |
| AMD                              | 41        | 18.39%  |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 13        | 5.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 4.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 4.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 3.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 3.49%   |
| Intel UHD Graphics 620                                                                   | 7         | 3.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 3.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.18%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.18%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.75%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.75%   |
| Intel HD Graphics 630                                                                    | 4         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.75%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.31%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 1.31%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.31%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.31%   |
| AMD Cezanne                                                                              | 3         | 1.31%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.87%   |
| Nvidia TU117M                                                                            | 2         | 0.87%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.87%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.87%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.87%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 0.87%   |
| Intel HD Graphics 530                                                                    | 2         | 0.87%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.87%   |
| Intel Comet Lake UHD Graphics                                                            | 2         | 0.87%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 2         | 0.87%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 0.87%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 0.87%   |
| AMD Lucienne                                                                             | 2         | 0.87%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 83        | 47.16%  |
| Intel + Nvidia | 37        | 21.02%  |
| 1 x AMD        | 28        | 15.91%  |
| 1 x Nvidia     | 12        | 6.82%   |
| Intel + AMD    | 6         | 3.41%   |
| AMD + Nvidia   | 4         | 2.27%   |
| 2 x AMD        | 3         | 1.7%    |
| Other          | 1         | 0.57%   |
| 2 x Nvidia     | 1         | 0.57%   |
| 1 x SiS        | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 144       | 80.9%   |
| Proprietary | 25        | 14.04%  |
| Unknown     | 9         | 5.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 106       | 59.22%  |
| 0.01-0.5   | 22        | 12.29%  |
| 1.01-2.0   | 18        | 10.06%  |
| 3.01-4.0   | 17        | 9.5%    |
| 0.51-1.0   | 10        | 5.59%   |
| 5.01-6.0   | 4         | 2.23%   |
| 7.01-8.0   | 2         | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 40        | 20%     |
| AU Optronics            | 34        | 17%     |
| BOE                     | 26        | 13%     |
| Samsung Electronics     | 25        | 12.5%   |
| Chimei Innolux          | 16        | 8%      |
| Goldstar                | 9         | 4.5%    |
| Sharp                   | 8         | 4%      |
| Apple                   | 8         | 4%      |
| PANDA                   | 4         | 2%      |
| Dell                    | 3         | 1.5%    |
| CPT                     | 3         | 1.5%    |
| Philips                 | 2         | 1%      |
| JCH                     | 2         | 1%      |
| CSO                     | 2         | 1%      |
| Chi Mei Optoelectronics | 2         | 1%      |
| ALP                     | 2         | 1%      |
| VMO                     | 1         | 0.5%    |
| TMX                     | 1         | 0.5%    |
| Sony                    | 1         | 0.5%    |
| PRISM+                  | 1         | 0.5%    |
| MSI                     | 1         | 0.5%    |
| Lenovo                  | 1         | 0.5%    |
| InfoVision              | 1         | 0.5%    |
| HKC                     | 1         | 0.5%    |
| Hewlett-Packard         | 1         | 0.5%    |
| HannStar                | 1         | 0.5%    |
| Denver                  | 1         | 0.5%    |
| CM_                     | 1         | 0.5%    |
| BenQ                    | 1         | 0.5%    |
| Ancor Communications    | 1         | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 4         | 1.97%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 3         | 1.48%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 3         | 1.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 1.48%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 2         | 0.99%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch         | 2         | 0.99%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch         | 2         | 0.99%   |
| LG Display LCD Monitor LGD05AC 1920x1080 344x194mm 15.5-inch         | 2         | 0.99%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch         | 2         | 0.99%   |
| LG Display LCD Monitor LGD03B5 1920x1080 294x165mm 13.3-inch         | 2         | 0.99%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 2         | 0.99%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2         | 0.99%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 2         | 0.99%   |
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                | 2         | 0.99%   |
| BOE LCD Monitor BOE06D7 3840x2160 345x194mm 15.6-inch                | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch        | 2         | 0.99%   |
| AU Optronics LCD Monitor 1920x1080                                   | 2         | 0.99%   |
| Apple Color LCD APPA044 3072x1920 345x215mm 16.0-inch                | 2         | 0.99%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch            | 1         | 0.49%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 0.49%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                | 1         | 0.49%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 0.49%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch              | 1         | 0.49%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch              | 1         | 0.49%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch              | 1         | 0.49%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch              | 1         | 0.49%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch              | 1         | 0.49%   |
| Samsung Electronics U32H85x SAM0E3A 3840x2160 697x392mm 31.5-inch    | 1         | 0.49%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch    | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM01A2 1280x1024 376x301mm 19.0-inch | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0138 1280x1024 338x270mm 17.0-inch | 1         | 0.49%   |
| Samsung Electronics SMBX2350 SAM071E 1920x1080 509x286mm 23.0-inch   | 1         | 0.49%   |
| Samsung Electronics S34J55x SAM0F72 1720x1440                        | 1         | 0.49%   |
| Samsung Electronics S27R65x SAM1045 1920x1080 598x336mm 27.0-inch    | 1         | 0.49%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch    | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5643 1280x800 303x190mm 14.1-inch | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5244 1600x900 360x210mm 16.4-inch | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 96        | 50.26%  |
| 1366x768 (WXGA)    | 34        | 17.8%   |
| 3840x2160 (4K)     | 10        | 5.24%   |
| 2560x1600          | 9         | 4.71%   |
| 1600x900 (HD+)     | 7         | 3.66%   |
| 2560x1440 (QHD)    | 6         | 3.14%   |
| 1920x1200 (WUXGA)  | 6         | 3.14%   |
| 1280x800 (WXGA)    | 6         | 3.14%   |
| 3440x1440          | 3         | 1.57%   |
| 1440x900 (WXGA+)   | 3         | 1.57%   |
| 3072x1920          | 2         | 1.05%   |
| 2880x1800          | 2         | 1.05%   |
| 1680x1050 (WSXGA+) | 2         | 1.05%   |
| 1280x1024 (SXGA)   | 2         | 1.05%   |
| 3840x2400          | 1         | 0.52%   |
| 2560x1080          | 1         | 0.52%   |
| 1680x945           | 1         | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 82        | 40.59%  |
| 13      | 33        | 16.34%  |
| 14      | 24        | 11.88%  |
| 17      | 9         | 4.46%   |
| 24      | 8         | 3.96%   |
| 16      | 8         | 3.96%   |
| 23      | 7         | 3.47%   |
| 31      | 5         | 2.48%   |
| 27      | 5         | 2.48%   |
| 34      | 3         | 1.49%   |
| 21      | 3         | 1.49%   |
| 20      | 2         | 0.99%   |
| 12      | 2         | 0.99%   |
| 11      | 2         | 0.99%   |
| Unknown | 2         | 0.99%   |
| 74      | 1         | 0.5%    |
| 54      | 1         | 0.5%    |
| 40      | 1         | 0.5%    |
| 25      | 1         | 0.5%    |
| 19      | 1         | 0.5%    |
| 18      | 1         | 0.5%    |
| 10      | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 121       | 60.2%   |
| 201-300     | 28        | 13.93%  |
| 501-600     | 19        | 9.45%   |
| 351-400     | 12        | 5.97%   |
| 401-500     | 7         | 3.48%   |
| 601-700     | 6         | 2.99%   |
| 701-800     | 3         | 1.49%   |
| Unknown     | 2         | 1%      |
| 801-900     | 1         | 0.5%    |
| 1501-2000   | 1         | 0.5%    |
| 1001-1500   | 1         | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 139       | 78.53%  |
| 16/10   | 30        | 16.95%  |
| 21/9    | 3         | 1.69%   |
| 5/4     | 2         | 1.13%   |
| Unknown | 2         | 1.13%   |
| 3/2     | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 82        | 40.59%  |
| 81-90          | 37        | 18.32%  |
| 71-80          | 20        | 9.9%    |
| 201-250        | 15        | 7.43%   |
| 351-500        | 8         | 3.96%   |
| 121-130        | 8         | 3.96%   |
| 111-120        | 7         | 3.47%   |
| 301-350        | 5         | 2.48%   |
| 251-300        | 4         | 1.98%   |
| 151-200        | 3         | 1.49%   |
| More than 1000 | 2         | 0.99%   |
| 61-70          | 2         | 0.99%   |
| 51-60          | 2         | 0.99%   |
| 141-150        | 2         | 0.99%   |
| Unknown        | 2         | 0.99%   |
| 41-50          | 1         | 0.5%    |
| 501-1000       | 1         | 0.5%    |
| 91-100         | 1         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 84        | 42.21%  |
| 101-120       | 41        | 20.6%   |
| 51-100        | 33        | 16.58%  |
| 161-240       | 27        | 13.57%  |
| More than 240 | 10        | 5.03%   |
| 1-50          | 2         | 1.01%   |
| Unknown       | 2         | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 137       | 74.46%  |
| 2     | 35        | 19.02%  |
| 0     | 9         | 4.89%   |
| 3     | 3         | 1.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 115       | 41.67%  |
| Realtek Semiconductor            | 87        | 31.52%  |
| Qualcomm Atheros                 | 23        | 8.33%   |
| Broadcom                         | 19        | 6.88%   |
| ASIX Electronics                 | 7         | 2.54%   |
| Marvell Technology Group         | 3         | 1.09%   |
| TP-Link                          | 2         | 0.72%   |
| Ralink Technology                | 2         | 0.72%   |
| Nvidia                           | 2         | 0.72%   |
| MediaTek                         | 2         | 0.72%   |
| Lenovo                           | 2         | 0.72%   |
| Broadcom Limited                 | 2         | 0.72%   |
| Apple                            | 2         | 0.72%   |
| Silicon Integrated Systems [SiS] | 1         | 0.36%   |
| Samsung Electronics              | 1         | 0.36%   |
| Ralink                           | 1         | 0.36%   |
| Qualcomm                         | 1         | 0.36%   |
| Microsoft                        | 1         | 0.36%   |
| D-Link                           | 1         | 0.36%   |
| Comneon                          | 1         | 0.36%   |
| Arduino SA                       | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 19.61%  |
| Intel Wi-Fi 6 AX200                                               | 20        | 6.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 3.22%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 3.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 2.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 2.25%   |
| Intel Wireless 7260                                               | 6         | 1.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.93%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.29%   |
| Intel Wireless 3165                                               | 4         | 1.29%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 4         | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 1.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.96%   |
| Intel Wireless 7265                                               | 3         | 0.96%   |
| Intel Wireless 3160                                               | 3         | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.96%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.96%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.96%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.96%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                | 3         | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.64%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 111       | 63.79%  |
| Realtek Semiconductor | 19        | 10.92%  |
| Qualcomm Atheros      | 17        | 9.77%   |
| Broadcom              | 16        | 9.2%    |
| TP-Link               | 2         | 1.15%   |
| Ralink Technology     | 2         | 1.15%   |
| MediaTek              | 2         | 1.15%   |
| Broadcom Limited      | 2         | 1.15%   |
| Ralink                | 1         | 0.57%   |
| Qualcomm              | 1         | 0.57%   |
| D-Link                | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 20        | 11.43%  |
| Intel Wi-Fi 6 AX201                                           | 10        | 5.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 9         | 5.14%   |
| Intel Wireless 7260                                           | 6         | 3.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 6         | 3.43%   |
| Intel Wireless 8265 / 8275                                    | 5         | 2.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 5         | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 5         | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 4         | 2.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 4         | 2.29%   |
| Intel Wireless 3165                                           | 4         | 2.29%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 4         | 2.29%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 2.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 4         | 2.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 4         | 2.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3         | 1.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 3         | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 1.71%   |
| Intel Wireless 7265                                           | 3         | 1.71%   |
| Intel Wireless 3160                                           | 3         | 1.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 3         | 1.71%   |
| Intel Centrino Wireless-N 2230                                | 3         | 1.71%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 3         | 1.71%   |
| Intel Centrino Advanced-N 6235                                | 3         | 1.71%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter            | 3         | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                 | 3         | 1.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 2         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 1.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 1.14%   |
| Intel WiFi Link 5100                                          | 2         | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 1.14%   |
| Intel Centrino Advanced-N 6200                                | 2         | 1.14%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller        | 2         | 1.14%   |
| Broadcom BCM43162 802.11ac Wireless Network Adapter           | 2         | 1.14%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.57%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                         | 1         | 0.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 82        | 63.57%  |
| Intel                            | 17        | 13.18%  |
| Qualcomm Atheros                 | 8         | 6.2%    |
| ASIX Electronics                 | 7         | 5.43%   |
| Marvell Technology Group         | 3         | 2.33%   |
| Broadcom                         | 3         | 2.33%   |
| Nvidia                           | 2         | 1.55%   |
| Lenovo                           | 2         | 1.55%   |
| Apple                            | 2         | 1.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.78%   |
| Samsung Electronics              | 1         | 0.78%   |
| Microsoft                        | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 61        | 45.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11        | 8.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 7.52%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 3.01%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.5%    |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.5%    |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.5%    |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.5%    |
| Apple iBridge                                                                  | 2         | 1.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.75%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.75%   |
| Microsoft Ethernet Adapter                                                     | 1         | 0.75%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.75%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.75%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.75%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.75%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.75%   |
| Intel Ethernet controller                                                      | 1         | 0.75%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.75%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.75%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.75%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.75%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.75%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.75%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.75%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 167       | 57%     |
| Ethernet | 123       | 41.98%  |
| Modem    | 2         | 0.68%   |
| Unknown  | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 71.43%  |
| Ethernet | 54        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 102       | 57.95%  |
| 1     | 69        | 39.2%   |
| 0     | 4         | 2.27%   |
| 3     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 175       | 99.43%  |
| Yes  | 1         | 0.57%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 64.34%  |
| Realtek Semiconductor           | 12        | 8.39%   |
| Broadcom                        | 11        | 7.69%   |
| Qualcomm Atheros Communications | 7         | 4.9%    |
| IMC Networks                    | 7         | 4.9%    |
| Lite-On Technology              | 4         | 2.8%    |
| Foxconn / Hon Hai               | 4         | 2.8%    |
| Apple                           | 4         | 2.8%    |
| Qcom                            | 1         | 0.7%    |
| Micro Star International        | 1         | 0.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 15.38%  |
| Intel AX201 Bluetooth                                                               | 20        | 13.99%  |
| Intel AX200 Bluetooth                                                               | 20        | 13.99%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 12.59%  |
| Realtek Bluetooth Radio                                                             | 7         | 4.9%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 3.5%    |
| Apple Bluetooth Host Controller                                                     | 4         | 2.8%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.1%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 2.1%    |
| Lite-On Bluetooth Device                                                            | 3         | 2.1%    |
| Intel Bluetooth Device                                                              | 3         | 2.1%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 2.1%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 2.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.4%    |
| Intel AX210 Bluetooth                                                               | 2         | 1.4%    |
| IMC Networks Wireless_Device                                                        | 2         | 1.4%    |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.4%    |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 1.4%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.4%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.4%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.7%    |
| Realtek CSR BS8510                                                                  | 1         | 0.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.7%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.7%    |
| Qcom Bluetooth USB                                                                  | 1         | 0.7%    |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.7%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.7%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.7%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.7%    |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 136       | 64.76%  |
| AMD                              | 38        | 18.1%   |
| Nvidia                           | 24        | 11.43%  |
| Apple                            | 3         | 1.43%   |
| Lenovo                           | 2         | 0.95%   |
| JMTek                            | 2         | 0.95%   |
| Texas Instruments                | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] | 1         | 0.48%   |
| Razer USA                        | 1         | 0.48%   |
| Dell                             | 1         | 0.48%   |
| Unknown                          | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 25        | 9.84%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 7.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 4.72%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 4.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 4.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 4.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 4.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 3.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 3.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 2.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.36%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.97%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.57%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.57%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.18%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.18%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.18%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.18%   |
| Apple Audio Device                                                                                | 3         | 1.18%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.18%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.79%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.79%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 59        | 48.36%  |
| SK hynix            | 28        | 22.95%  |
| Micron Technology   | 13        | 10.66%  |
| Unknown             | 5         | 4.1%    |
| Kingston            | 3         | 2.46%   |
| A-DATA Technology   | 3         | 2.46%   |
| Unknown (ABCD)      | 2         | 1.64%   |
| Ramaxel Technology  | 2         | 1.64%   |
| Unknown             | 2         | 1.64%   |
| Unknown (09D5)      | 1         | 0.82%   |
| Team                | 1         | 0.82%   |
| Silicon Power       | 1         | 0.82%   |
| Essencore           | 1         | 0.82%   |
| Elpida              | 1         | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 4.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 4         | 3.05%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 3.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 3.05%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 2.29%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 3         | 2.29%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 2.29%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 2.29%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 3         | 2.29%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                           | 2         | 1.53%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                    | 2         | 1.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 1.53%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 2         | 1.53%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s          | 2         | 1.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.53%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.53%   |
| Samsung RAM M471A1G44AB0-CTD 8192MB DDR4 2667MT/s                   | 2         | 1.53%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 2         | 1.53%   |
| Unknown                                                             | 2         | 1.53%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 1         | 0.76%   |
| Unknown RAM CL22-22-22 D4-3200 16384MB SODIMM DDR4 3200MT/s         | 1         | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s        | 1         | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 1         | 0.76%   |
| Unknown (09D5) RAM Module 16384MB SODIMM DDR4 2400MT/s              | 1         | 0.76%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 0.76%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.76%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                        | 1         | 0.76%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                    | 1         | 0.76%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.76%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.76%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.76%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB Row Of Chips DDR4 3200MT/s    | 1         | 0.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 0.76%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.76%   |
| SK hynix RAM HMA851S6DJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 57        | 56.44%  |
| DDR3    | 25        | 24.75%  |
| LPDDR4  | 8         | 7.92%   |
| LPDDR3  | 6         | 5.94%   |
| SDRAM   | 2         | 1.98%   |
| LPDDR5  | 1         | 0.99%   |
| DDR2    | 1         | 0.99%   |
| Unknown | 1         | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 78        | 75.73%  |
| Row Of Chips | 18        | 17.48%  |
| Unknown      | 4         | 3.88%   |
| DIMM         | 3         | 2.91%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 52        | 47.27%  |
| 4096  | 32        | 29.09%  |
| 16384 | 14        | 12.73%  |
| 2048  | 9         | 8.18%   |
| 32768 | 2         | 1.82%   |
| 1024  | 1         | 0.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 28        | 25.45%  |
| 3200  | 25        | 22.73%  |
| 1600  | 16        | 14.55%  |
| 2400  | 10        | 9.09%   |
| 2133  | 7         | 6.36%   |
| 4267  | 5         | 4.55%   |
| 1334  | 5         | 4.55%   |
| 3266  | 4         | 3.64%   |
| 1333  | 2         | 1.82%   |
| 8400  | 1         | 0.91%   |
| 6400  | 1         | 0.91%   |
| 4800  | 1         | 0.91%   |
| 4199  | 1         | 0.91%   |
| 2048  | 1         | 0.91%   |
| 1867  | 1         | 0.91%   |
| 1067  | 1         | 0.91%   |
| 800   | 1         | 0.91%   |

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
| Chicony Electronics                    | 32        | 21.62%  |
| IMC Networks                           | 17        | 11.49%  |
| Acer                                   | 16        | 10.81%  |
| Realtek Semiconductor                  | 13        | 8.78%   |
| Silicon Motion                         | 10        | 6.76%   |
| Microdia                               | 10        | 6.76%   |
| Quanta                                 | 7         | 4.73%   |
| Apple                                  | 7         | 4.73%   |
| Unknown                                | 5         | 3.38%   |
| Syntek                                 | 5         | 3.38%   |
| Suyin                                  | 5         | 3.38%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.38%   |
| SunplusIT                              | 3         | 2.03%   |
| Sunplus Innovation Technology          | 3         | 2.03%   |
| Z-Star Microelectronics                | 2         | 1.35%   |
| Luxvisions Innotech Limited            | 2         | 1.35%   |
| Microsoft                              | 1         | 0.68%   |
| Logitech                               | 1         | 0.68%   |
| Lenovo                                 | 1         | 0.68%   |
| Goodong Industry                       | 1         | 0.68%   |
| DigiTech                               | 1         | 0.68%   |
| Alcor Micro                            | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 10        | 6.67%   |
| Microdia Integrated_Webcam_HD                           | 6         | 4%      |
| IMC Networks Integrated Camera                          | 6         | 4%      |
| Unknown 720p HD Camera                                  | 5         | 3.33%   |
| Realtek LG Camera                                       | 5         | 3.33%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 5         | 3.33%   |
| Chicony HD Webcam                                       | 5         | 3.33%   |
| Acer HD Webcam                                          | 4         | 2.67%   |
| Syntek Integrated Camera                                | 3         | 2%      |
| Suyin HP Truevision HD                                  | 3         | 2%      |
| Silicon Motion LG HD WebCam                             | 3         | 2%      |
| Quanta HP TrueVision HD Camera                          | 3         | 2%      |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 2%      |
| Chicony LG Camera                                       | 3         | 2%      |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 2%      |
| Acer Integrated Camera                                  | 3         | 2%      |
| Z-Star Webcam                                           | 2         | 1.33%   |
| SunplusIT 1080p FHD Camera                              | 2         | 1.33%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 2         | 1.33%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.33%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.33%   |
| Quanta LG Webcam                                        | 2         | 1.33%   |
| Chicony USB 2.0 Camera                                  | 2         | 1.33%   |
| Chicony LG HD WebCam                                    | 2         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.33%   |
| Apple iPhone 5/5C/5S/6/SE                               | 2         | 1.33%   |
| Apple Built-in iSight                                   | 2         | 1.33%   |
| Acer Lenovo EasyCamera                                  | 2         | 1.33%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.67%   |
| Syntek HP Webcam                                        | 1         | 0.67%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.67%   |
| Suyin HP TrueVision Full HD                             | 1         | 0.67%   |
| SunplusIT 720p HD Camera                                | 1         | 0.67%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.67%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.67%   |
| Sunplus Asus Webcam                                     | 1         | 0.67%   |
| Silicon Motion WebCam SC-13HDN10939N                    | 1         | 0.67%   |
| Silicon Motion WebCam SC-13HDL11431N                    | 1         | 0.67%   |
| Silicon Motion WebCam SC-10HDD13335N                    | 1         | 0.67%   |
| Silicon Motion Web Camera                               | 1         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 13        | 35.14%  |
| Validity Sensors           | 8         | 21.62%  |
| Shenzhen Goodix Technology | 4         | 10.81%  |
| Samsung Electronics        | 4         | 10.81%  |
| Upek                       | 3         | 8.11%   |
| LighTuning Technology      | 2         | 5.41%   |
| Elan Microelectronics      | 2         | 5.41%   |
| AuthenTec                  | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 6         | 16.22%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 3         | 8.11%   |
| Samsung Fingerprint Sensor Device - 730B                  | 3         | 8.11%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 5.41%   |
| Validity Sensors VFS301 Fingerprint Reader                | 2         | 5.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 5.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 5.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 5.41%   |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 5.41%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 5.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 2         | 5.41%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 2.7%    |
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 2.7%    |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 2.7%    |
| Validity Sensors Fingerprint scanner                      | 1         | 2.7%    |
| Synaptics WBDI Device                                     | 1         | 2.7%    |
| Samsung Fingerprint Device                                | 1         | 2.7%    |
| Elan ELAN:Fingerprint                                     | 1         | 2.7%    |
| Elan ELAN:ARM-M4                                          | 1         | 2.7%    |
| AuthenTec Fingerprint Sensor                              | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 33.33%  |
| Alcor Micro | 2         | 33.33%  |
| Upek        | 1         | 16.67%  |
| O2 Micro    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 102       | 56.98%  |
| 1     | 65        | 36.31%  |
| 2     | 9         | 5.03%   |
| 3     | 3         | 1.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 37        | 40.66%  |
| Graphics card         | 23        | 25.27%  |
| Net/wireless          | 14        | 15.38%  |
| Chipcard              | 6         | 6.59%   |
| Multimedia controller | 4         | 4.4%    |
| Bluetooth             | 3         | 3.3%    |
| Net/ethernet          | 2         | 2.2%    |
| Sound                 | 1         | 1.1%    |
| Network               | 1         | 1.1%    |

