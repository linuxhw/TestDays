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

Total: 216

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 40        | 24.39%  |
| Ubuntu 18.04                 | 18        | 10.98%  |
| Ubuntu 21.10                 | 6         | 3.66%   |
| Arch Rolling                 | 5         | 3.05%   |
| Arch                         | 5         | 3.05%   |
| Ubuntu 22.04                 | 4         | 2.44%   |
| Linux Mint 20.3              | 4         | 2.44%   |
| Linux Mint 20.1              | 4         | 2.44%   |
| Fedora 32                    | 4         | 2.44%   |
| Ubuntu 19.10                 | 3         | 1.83%   |
| Ubuntu 19.04                 | 3         | 1.83%   |
| ROSA R11                     | 3         | 1.83%   |
| OpenMandriva 4.2             | 3         | 1.83%   |
| HamoniKR 4.0                 | 3         | 1.83%   |
| Gooroom                      | 3         | 1.83%   |
| Fedora 34                    | 3         | 1.83%   |
| Debian 10                    | 3         | 1.83%   |
| Zorin 15                     | 2         | 1.22%   |
| Ubuntu MATE 18.04            | 2         | 1.22%   |
| ROSA R10                     | 2         | 1.22%   |
| Pop!_OS 21.10                | 2         | 1.22%   |
| Linux Mint 20                | 2         | 1.22%   |
| Endless 3.8.5                | 2         | 1.22%   |
| Debian 11                    | 2         | 1.22%   |
| CentOS 8                     | 2         | 1.22%   |
| Xubuntu 20.04                | 1         | 0.61%   |
| Ubuntu 21.04                 | 1         | 0.61%   |
| Ubuntu 20.10                 | 1         | 0.61%   |
| Ubuntu 16.04                 | 1         | 0.61%   |
| Pop!_OS 21.04                | 1         | 0.61%   |
| Pop!_OS 20.10                | 1         | 0.61%   |
| Pop!_OS 20.04                | 1         | 0.61%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.61%   |
| OpenMandriva 4.50            | 1         | 0.61%   |
| No1 2022 kde plasma te       | 1         | 0.61%   |
| No1 2020 te                  | 1         | 0.61%   |
| No1 2018                     | 1         | 0.61%   |
| Manjaro 21.1.3               | 1         | 0.61%   |
| Manjaro 20.2.1               | 1         | 0.61%   |
| Manjaro 20.1                 | 1         | 0.61%   |
| Manjaro 19.0.2               | 1         | 0.61%   |
| Manjaro 18.1.0               | 1         | 0.61%   |
| Manjaro                      | 1         | 0.61%   |
| Lubuntu 18.04                | 1         | 0.61%   |
| LMDE 5                       | 1         | 0.61%   |
| Linux Mint 20.2              | 1         | 0.61%   |
| Linux Mint 19.3              | 1         | 0.61%   |
| Kubuntu 21.10                | 1         | 0.61%   |
| Kubuntu 20.04                | 1         | 0.61%   |
| KDE neon 20.04               | 1         | 0.61%   |
| HamoniKR 5.0                 | 1         | 0.61%   |
| HamoniKR                     | 1         | 0.61%   |
| Gentoo 2.7                   | 1         | 0.61%   |
| Garuda Linux                 | 1         | 0.61%   |
| Fedora 33                    | 1         | 0.61%   |
| Endless 3.9.4                | 1         | 0.61%   |
| Endless 3.7.7-nexthw1        | 1         | 0.61%   |
| Endless 3.4.3-nexthw1        | 1         | 0.61%   |
| EndeavourOS                  | 1         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 75        | 47.77%  |
| Linux Mint   | 12        | 7.64%   |
| Fedora       | 8         | 5.1%    |
| Arch         | 8         | 5.1%    |
| Manjaro      | 6         | 3.82%   |
| ROSA         | 5         | 3.18%   |
| Endless      | 5         | 3.18%   |
| Debian       | 5         | 3.18%   |
| OpenMandriva | 4         | 2.55%   |
| HamoniKR     | 4         | 2.55%   |
| Pop!_OS      | 3         | 1.91%   |
| No1          | 3         | 1.91%   |
| Gooroom      | 3         | 1.91%   |
| Zorin        | 2         | 1.27%   |
| Ubuntu MATE  | 2         | 1.27%   |
| Kubuntu      | 2         | 1.27%   |
| CentOS       | 2         | 1.27%   |
| Xubuntu      | 1         | 0.64%   |
| openSUSE     | 1         | 0.64%   |
| Lubuntu      | 1         | 0.64%   |
| LMDE         | 1         | 0.64%   |
| KDE neon     | 1         | 0.64%   |
| Gentoo       | 1         | 0.64%   |
| Garuda Linux | 1         | 0.64%   |
| EndeavourOS  | 1         | 0.64%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 4         | 2.26%   |
| 5.4.0-58-generic                | 3         | 1.69%   |
| 5.4.0-26-generic                | 3         | 1.69%   |
| 5.3.0-40-generic                | 3         | 1.69%   |
| 5.11.0-37-generic               | 3         | 1.69%   |
| 4.19.0-9-amd64                  | 3         | 1.69%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3         | 1.69%   |
| 5.8.4-200.fc32.x86_64           | 2         | 1.13%   |
| 5.8.0-53-generic                | 2         | 1.13%   |
| 5.8.0-43-generic                | 2         | 1.13%   |
| 5.4.0-81-generic                | 2         | 1.13%   |
| 5.4.0-56-generic                | 2         | 1.13%   |
| 5.4.0-48-generic                | 2         | 1.13%   |
| 5.4.0-39-generic                | 2         | 1.13%   |
| 5.4.0-33-generic                | 2         | 1.13%   |
| 5.4.0-31-generic                | 2         | 1.13%   |
| 5.4.0-29-generic                | 2         | 1.13%   |
| 5.3.0-46-generic                | 2         | 1.13%   |
| 5.15.0-27-generic               | 2         | 1.13%   |
| 5.13.0-28-generic               | 2         | 1.13%   |
| 5.13.0-27-generic               | 2         | 1.13%   |
| 5.10.14-desktop-1omv4002        | 2         | 1.13%   |
| 5.0.0-37-generic                | 2         | 1.13%   |
| 5.0.0-25-generic                | 2         | 1.13%   |
| 5.0.0-13-generic                | 2         | 1.13%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 1.13%   |
| 4.18.0-17-generic               | 2         | 1.13%   |
| 4.15.0-112-generic              | 2         | 1.13%   |
| 5.9.9-zen1-1-zen                | 1         | 0.56%   |
| 5.8.18-050818-generic           | 1         | 0.56%   |
| 5.8.15-301.fc33.x86_64          | 1         | 0.56%   |
| 5.8.0-59-generic                | 1         | 0.56%   |
| 5.8.0-55-generic                | 1         | 0.56%   |
| 5.8.0-50-generic                | 1         | 0.56%   |
| 5.8.0-38-generic                | 1         | 0.56%   |
| 5.8.0-32-generic                | 1         | 0.56%   |
| 5.8.0-29-generic                | 1         | 0.56%   |
| 5.8.0-14-generic                | 1         | 0.56%   |
| 5.7.17-2-MANJARO                | 1         | 0.56%   |
| 5.6.11-300.fc32.x86_64          | 1         | 0.56%   |
| 5.6.0-1036-oem                  | 1         | 0.56%   |
| 5.5.2-arch2-2                   | 1         | 0.56%   |
| 5.4.61-1-lts                    | 1         | 0.56%   |
| 5.4.55-1-lts                    | 1         | 0.56%   |
| 5.4.0-96-generic                | 1         | 0.56%   |
| 5.4.0-91-generic                | 1         | 0.56%   |
| 5.4.0-89-generic                | 1         | 0.56%   |
| 5.4.0-7642-generic              | 1         | 0.56%   |
| 5.4.0-74-generic                | 1         | 0.56%   |
| 5.4.0-72-generic                | 1         | 0.56%   |
| 5.4.0-70-generic                | 1         | 0.56%   |
| 5.4.0-7-generic                 | 1         | 0.56%   |
| 5.4.0-66-generic                | 1         | 0.56%   |
| 5.4.0-54-generic                | 1         | 0.56%   |
| 5.4.0-53-generic                | 1         | 0.56%   |
| 5.4.0-52-generic                | 1         | 0.56%   |
| 5.4.0-47-generic                | 1         | 0.56%   |
| 5.4.0-45-generic                | 1         | 0.56%   |
| 5.4.0-44-generic                | 1         | 0.56%   |
| 5.4.0-40-generic                | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.4.0    | 45        | 26.47%  |
| 5.8.0    | 11        | 6.47%   |
| 5.11.0   | 10        | 5.88%   |
| 4.15.0   | 10        | 5.88%   |
| 5.3.0    | 9         | 5.29%   |
| 5.13.0   | 9         | 5.29%   |
| 5.0.0    | 7         | 4.12%   |
| 4.18.0   | 7         | 4.12%   |
| 4.19.0   | 6         | 3.53%   |
| 5.15.0   | 5         | 2.94%   |
| 5.8.4    | 2         | 1.18%   |
| 5.16.19  | 2         | 1.18%   |
| 5.15.11  | 2         | 1.18%   |
| 5.10.14  | 2         | 1.18%   |
| 5.10.0   | 2         | 1.18%   |
| 4.9.60   | 2         | 1.18%   |
| 5.9.9    | 1         | 0.59%   |
| 5.8.18   | 1         | 0.59%   |
| 5.8.15   | 1         | 0.59%   |
| 5.7.17   | 1         | 0.59%   |
| 5.6.11   | 1         | 0.59%   |
| 5.6.0    | 1         | 0.59%   |
| 5.5.2    | 1         | 0.59%   |
| 5.4.61   | 1         | 0.59%   |
| 5.4.55   | 1         | 0.59%   |
| 5.3.7    | 1         | 0.59%   |
| 5.2.11   | 1         | 0.59%   |
| 5.16.8   | 1         | 0.59%   |
| 5.16.5   | 1         | 0.59%   |
| 5.15.8   | 1         | 0.59%   |
| 5.15.2   | 1         | 0.59%   |
| 5.15.16  | 1         | 0.59%   |
| 5.15.15  | 1         | 0.59%   |
| 5.15.13  | 1         | 0.59%   |
| 5.15.12  | 1         | 0.59%   |
| 5.14.6   | 1         | 0.59%   |
| 5.14.14  | 1         | 0.59%   |
| 5.14.0   | 1         | 0.59%   |
| 5.13.12  | 1         | 0.59%   |
| 5.12.5   | 1         | 0.59%   |
| 5.12.4   | 1         | 0.59%   |
| 5.12.19  | 1         | 0.59%   |
| 5.12.15  | 1         | 0.59%   |
| 5.12.13  | 1         | 0.59%   |
| 5.11.19  | 1         | 0.59%   |
| 5.11.17  | 1         | 0.59%   |
| 5.11.16  | 1         | 0.59%   |
| 5.11.12  | 1         | 0.59%   |
| 5.11.1   | 1         | 0.59%   |
| 5.10.61  | 1         | 0.59%   |
| 5.10.2   | 1         | 0.59%   |
| 4.19.114 | 1         | 0.59%   |
| 4.18.16  | 1         | 0.59%   |
| 4.16.0   | 1         | 0.59%   |
| 4.15.8   | 1         | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 47        | 27.81%  |
| 5.8     | 15        | 8.88%   |
| 5.11    | 15        | 8.88%   |
| 5.15    | 12        | 7.1%    |
| 4.15    | 11        | 6.51%   |
| 5.3     | 10        | 5.92%   |
| 5.13    | 10        | 5.92%   |
| 4.18    | 8         | 4.73%   |
| 5.0     | 7         | 4.14%   |
| 4.19    | 7         | 4.14%   |
| 5.10    | 6         | 3.55%   |
| 5.12    | 5         | 2.96%   |
| 5.16    | 4         | 2.37%   |
| 5.14    | 3         | 1.78%   |
| 5.6     | 2         | 1.18%   |
| 4.9     | 2         | 1.18%   |
| 5.9     | 1         | 0.59%   |
| 5.7     | 1         | 0.59%   |
| 5.5     | 1         | 0.59%   |
| 5.2     | 1         | 0.59%   |
| 4.16    | 1         | 0.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 150       | 98.04%  |
| i686    | 2         | 1.31%   |
| aarch64 | 1         | 0.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 84        | 53.16%  |
| KDE5            | 16        | 10.13%  |
| Unknown         | 16        | 10.13%  |
| X-Cinnamon      | 11        | 6.96%   |
| XFCE            | 6         | 3.8%    |
| Cinnamon        | 6         | 3.8%    |
| LXDE            | 3         | 1.9%    |
| KDE4            | 3         | 1.9%    |
| KDE             | 3         | 1.9%    |
| GNOME Flashback | 3         | 1.9%    |
| Unity           | 2         | 1.27%   |
| MATE            | 2         | 1.27%   |
| i3              | 2         | 1.27%   |
| sway            | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 118       | 76.13%  |
| Wayland | 22        | 14.19%  |
| Unknown | 12        | 7.74%   |
| Tty     | 3         | 1.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 78        | 49.06%  |
| GDM     | 30        | 18.87%  |
| SDDM    | 17        | 10.69%  |
| TDM     | 13        | 8.18%   |
| LightDM | 11        | 6.92%   |
| GDM3    | 6         | 3.77%   |
| KDM     | 3         | 1.89%   |
| XDM     | 1         | 0.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ko_KR   | 70        | 44.03%  |
| en_US   | 50        | 31.45%  |
| Unknown | 25        | 15.72%  |
| zh_CN   | 3         | 1.89%   |
| id_ID   | 2         | 1.26%   |
| en_CA   | 2         | 1.26%   |
| C       | 2         | 1.26%   |
| vi_VN   | 1         | 0.63%   |
| pt_BR   | 1         | 0.63%   |
| fr_FR   | 1         | 0.63%   |
| en_NZ   | 1         | 0.63%   |
| ar_EG   | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 105       | 68.18%  |
| BIOS | 49        | 31.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 130       | 83.87%  |
| Btrfs   | 8         | 5.16%   |
| Overlay | 6         | 3.87%   |
| Unknown | 6         | 3.87%   |
| Xfs     | 3         | 1.94%   |
| Zfs     | 2         | 1.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 79        | 50.64%  |
| GPT     | 68        | 43.59%  |
| MBR     | 9         | 5.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 93.51%  |
| Yes       | 10        | 6.49%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 102       | 65.81%  |
| Yes       | 53        | 34.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 29        | 18.95%  |
| Hewlett-Packard     | 20        | 13.07%  |
| Samsung Electronics | 18        | 11.76%  |
| LG Electronics      | 16        | 10.46%  |
| ASUSTek Computer    | 16        | 10.46%  |
| Dell                | 12        | 7.84%   |
| MSI                 | 10        | 6.54%   |
| Apple               | 5         | 3.27%   |
| HANSUNG COMPUTER    | 4         | 2.61%   |
| Notebook            | 3         | 1.96%   |
| Acer                | 3         | 1.96%   |
| Toshiba             | 2         | 1.31%   |
| Wolfnfox            | 1         | 0.65%   |
| TG                  | 1         | 0.65%   |
| Teclast             | 1         | 0.65%   |
| Sony                | 1         | 0.65%   |
| SLIMBOOK            | 1         | 0.65%   |
| Pine Microsystems   | 1         | 0.65%   |
| MECHREVO            | 1         | 0.65%   |
| Jooyontech Computer | 1         | 0.65%   |
| Intel               | 1         | 0.65%   |
| IMUZ                | 1         | 0.65%   |
| Google              | 1         | 0.65%   |
| Clevo               | 1         | 0.65%   |
| AVERATEC            | 1         | 0.65%   |
| AMI                 | 1         | 0.65%   |
| Alienware           | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung 950XCJ/951XCJ/950XCR                      | 2         | 1.31%   |
| HP Stream Notebook PC 13                          | 2         | 1.31%   |
| HP Laptop 15-db1xxx                               | 2         | 1.31%   |
| HANSUNG COMPUTER TFX5470H                         | 2         | 1.31%   |
| Dell XPS 15 7590                                  | 2         | 1.31%   |
| Wolfnfox WF-TBAT                                  | 1         | 0.65%   |
| Toshiba Satellite P50-B-103                       | 1         | 0.65%   |
| Toshiba Satellite L655                            | 1         | 0.65%   |
| TG NXI-A7000 Series                               | 1         | 0.65%   |
| Teclast tPAD                                      | 1         | 0.65%   |
| Sony VPCEA36FK                                    | 1         | 0.65%   |
| SLIMBOOK PROX15-AMD                               | 1         | 0.65%   |
| Samsung X120/X170/X171                            | 1         | 0.65%   |
| Samsung SX11S                                     | 1         | 0.65%   |
| Samsung RC420/RC520/RC720                         | 1         | 0.65%   |
| Samsung R59P/R60P/R61P                            | 1         | 0.65%   |
| Samsung R440/R480                                 | 1         | 0.65%   |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.65%   |
| Samsung 905S3G/906S3G/915S3G                      | 1         | 0.65%   |
| Samsung 800G5M/800G5W                             | 1         | 0.65%   |
| Samsung 760XBE                                    | 1         | 0.65%   |
| Samsung 730QCJ/730QCR                             | 1         | 0.65%   |
| Samsung 570Z5E/580Z5E                             | 1         | 0.65%   |
| Samsung 530U3BI/530U4BI/530U4BH                   | 1         | 0.65%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.65%   |
| Samsung 400B4C/400B5C/200B4C/200B5C               | 1         | 0.65%   |
| Samsung 400B4B/400B5B/200B4B/200B5B               | 1         | 0.65%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.65%   |
| Pine Microsystems Pine64 Pinebook Pro             | 1         | 0.65%   |
| Notebook W330SU2                                  | 1         | 0.65%   |
| Notebook NL5xRU                                   | 1         | 0.65%   |
| Notebook N650DU                                   | 1         | 0.65%   |
| MSI PS63 Modern 8RC                               | 1         | 0.65%   |
| MSI PS42 Modern 8MO                               | 1         | 0.65%   |
| MSI Prestige 15 A10SC                             | 1         | 0.65%   |
| MSI Prestige 14 A10SC                             | 1         | 0.65%   |
| MSI MS-16F1                                       | 1         | 0.65%   |
| MSI MS-1675                                       | 1         | 0.65%   |
| MSI GX60 3CC                                      | 1         | 0.65%   |
| MSI GF75 Thin 9SCXR                               | 1         | 0.65%   |
| MSI GF63 Thin 9SC                                 | 1         | 0.65%   |
| MSI GE75 Raider 10SF                              | 1         | 0.65%   |
| MECHREVO Taitan Series GM7TG0M                    | 1         | 0.65%   |
| LG ZD360-GD30K                                    | 1         | 0.65%   |
| LG Z435-GE40K                                     | 1         | 0.65%   |
| LG R510                                           | 1         | 0.65%   |
| LG R490-KR6WK                                     | 1         | 0.65%   |
| LG A520-DEHRK                                     | 1         | 0.65%   |
| LG A505-K.AFC4L                                   | 1         | 0.65%   |
| LG 17ZD90P-GX7LK                                  | 1         | 0.65%   |
| LG 17UD790-PX76K                                  | 1         | 0.65%   |
| LG 17UD70P-PX76K                                  | 1         | 0.65%   |
| LG 16ZD90P-GX7LK                                  | 1         | 0.65%   |
| LG 16ZD90P-GX5LK                                  | 1         | 0.65%   |
| LG 15Z990-HA50K                                   | 1         | 0.65%   |
| LG 15ND530-GX30K                                  | 1         | 0.65%   |
| LG 14ZB990-GP70ML                                 | 1         | 0.65%   |
| LG 14Z90N-VA76K                                   | 1         | 0.65%   |
| LG 13Z940-MF6BL                                   | 1         | 0.65%   |
| Lenovo XiaoXin Air 13IWL 81J8                     | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 20        | 13.07%  |
| HP Pavilion               | 6         | 3.92%   |
| ASUS VivoBook             | 6         | 3.92%   |
| Lenovo IdeaPad            | 4         | 2.61%   |
| HP Laptop                 | 4         | 2.61%   |
| Dell XPS                  | 4         | 2.61%   |
| Dell Inspiron             | 4         | 2.61%   |
| HP Stream                 | 3         | 1.96%   |
| HP EliteBook              | 3         | 1.96%   |
| Toshiba Satellite         | 2         | 1.31%   |
| Samsung 950XCJ            | 2         | 1.31%   |
| MSI Prestige              | 2         | 1.31%   |
| HP ProBook                | 2         | 1.31%   |
| HANSUNG COMPUTER TFX5470H | 2         | 1.31%   |
| Dell Latitude             | 2         | 1.31%   |
| ASUS TUF                  | 2         | 1.31%   |
| ASUS ROG                  | 2         | 1.31%   |
| Apple MacBookPro5         | 2         | 1.31%   |
| Acer Swift                | 2         | 1.31%   |
| Wolfnfox WF-TBAT          | 1         | 0.65%   |
| TG NXI-A7000              | 1         | 0.65%   |
| Teclast tPAD              | 1         | 0.65%   |
| Sony VPCEA36FK            | 1         | 0.65%   |
| SLIMBOOK PROX15-AMD       | 1         | 0.65%   |
| Samsung X120              | 1         | 0.65%   |
| Samsung SX11S             | 1         | 0.65%   |
| Samsung RC420             | 1         | 0.65%   |
| Samsung R59P              | 1         | 0.65%   |
| Samsung R440              | 1         | 0.65%   |
| Samsung 950XDB            | 1         | 0.65%   |
| Samsung 905S3G            | 1         | 0.65%   |
| Samsung 800G5M            | 1         | 0.65%   |
| Samsung 760XBE            | 1         | 0.65%   |
| Samsung 730QCJ            | 1         | 0.65%   |
| Samsung 570Z5E            | 1         | 0.65%   |
| Samsung 530U3BI           | 1         | 0.65%   |
| Samsung 500R4K            | 1         | 0.65%   |
| Samsung 400B4C            | 1         | 0.65%   |
| Samsung 400B4B            | 1         | 0.65%   |
| Samsung 270E5J            | 1         | 0.65%   |
| Pine Microsystems Pine64  | 1         | 0.65%   |
| Notebook W330SU2          | 1         | 0.65%   |
| Notebook NL5xRU           | 1         | 0.65%   |
| Notebook N650DU           | 1         | 0.65%   |
| MSI PS63                  | 1         | 0.65%   |
| MSI PS42                  | 1         | 0.65%   |
| MSI MS-16F1               | 1         | 0.65%   |
| MSI MS-1675               | 1         | 0.65%   |
| MSI GX60                  | 1         | 0.65%   |
| MSI GF75                  | 1         | 0.65%   |
| MSI GF63                  | 1         | 0.65%   |
| MSI GE75                  | 1         | 0.65%   |
| MECHREVO Taitan           | 1         | 0.65%   |
| LG ZD360-GD30K            | 1         | 0.65%   |
| LG Z435-GE40K             | 1         | 0.65%   |
| LG R510                   | 1         | 0.65%   |
| LG R490-KR6WK             | 1         | 0.65%   |
| LG A520-DEHRK             | 1         | 0.65%   |
| LG A505-K.AFC4L           | 1         | 0.65%   |
| LG 17ZD90P-GX7LK          | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 31        | 20.26%  |
| 2019    | 21        | 13.73%  |
| 2021    | 15        | 9.8%    |
| 2014    | 14        | 9.15%   |
| 2018    | 13        | 8.5%    |
| 2011    | 11        | 7.19%   |
| 2013    | 10        | 6.54%   |
| 2010    | 7         | 4.58%   |
| 2008    | 6         | 3.92%   |
| 2015    | 5         | 3.27%   |
| 2012    | 5         | 3.27%   |
| 2016    | 4         | 2.61%   |
| 2009    | 4         | 2.61%   |
| 2017    | 3         | 1.96%   |
| 2007    | 2         | 1.31%   |
| 2006    | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 153       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 138       | 89.03%  |
| Enabled  | 17        | 10.97%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 152       | 99.35%  |
| Yes  | 1         | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 42        | 26.92%  |
| 16.01-24.0  | 34        | 21.79%  |
| 3.01-4.0    | 30        | 19.23%  |
| 8.01-16.0   | 23        | 14.74%  |
| 1.01-2.0    | 12        | 7.69%   |
| 32.01-64.0  | 10        | 6.41%   |
| 24.01-32.0  | 2         | 1.28%   |
| 64.01-256.0 | 2         | 1.28%   |
| 2.01-3.0    | 1         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 59        | 34.71%  |
| 2.01-3.0   | 40        | 23.53%  |
| 3.01-4.0   | 25        | 14.71%  |
| 4.01-8.0   | 23        | 13.53%  |
| 0.51-1.0   | 14        | 8.24%   |
| 8.01-16.0  | 7         | 4.12%   |
| 16.01-24.0 | 2         | 1.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 99        | 62.66%  |
| 2      | 51        | 32.28%  |
| 3      | 6         | 3.8%    |
| 4      | 1         | 0.63%   |
| 0      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 125       | 81.7%   |
| Yes       | 28        | 18.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 70.13%  |
| No        | 46        | 29.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 94.77%  |
| No        | 8         | 5.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 79.74%  |
| No        | 31        | 20.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| South Korea | 153       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Seoul         | 29        | 18.13%  |
| Gwanak-gu     | 7         | 4.38%   |
| Suwon         | 6         | 3.75%   |
| Seocho-gu     | 6         | 3.75%   |
| Uiwang        | 5         | 3.13%   |
| Seongnam-si   | 5         | 3.13%   |
| Jung-gu       | 4         | 2.5%    |
| Hwaseong-si   | 4         | 2.5%    |
| Daejeon       | 4         | 2.5%    |
| Bupyeong-gu   | 4         | 2.5%    |
| Anyang-si     | 4         | 2.5%    |
| Pyeongtaek-si | 3         | 1.88%   |
| Incheon       | 3         | 1.88%   |
| Busan         | 3         | 1.88%   |
| Yongsan-gu    | 2         | 1.25%   |
| Yeonsu-gu     | 2         | 1.25%   |
| Namdong-gu    | 2         | 1.25%   |
| Nam-gu        | 2         | 1.25%   |
| Jeonju        | 2         | 1.25%   |
| Jeju City     | 2         | 1.25%   |
| Gyeongsan-si  | 2         | 1.25%   |
| Gwangju       | 2         | 1.25%   |
| Gimpo-si      | 2         | 1.25%   |
| Geumjeong-gu  | 2         | 1.25%   |
| Gangseo-gu    | 2         | 1.25%   |
| Gangnam-gu    | 2         | 1.25%   |
| Danyang-gun   | 2         | 1.25%   |
| Daegu         | 2         | 1.25%   |
| Yuseong-gu    | 1         | 0.63%   |
| Yuseong       | 1         | 0.63%   |
| Yongin-si     | 1         | 0.63%   |
| Yangju        | 1         | 0.63%   |
| Yangcheon-gu  | 1         | 0.63%   |
| Suseong-gu    | 1         | 0.63%   |
| Sinsa-dong    | 1         | 0.63%   |
| Siheung-si    | 1         | 0.63%   |
| Seongdong-gu  | 1         | 0.63%   |
| Seongbuk-gu   | 1         | 0.63%   |
| Seo-gu        | 1         | 0.63%   |
| Pohang        | 1         | 0.63%   |
| Pocheon-si    | 1         | 0.63%   |
| Paju          | 1         | 0.63%   |
| Osan          | 1         | 0.63%   |
| Okcheon-gun   | 1         | 0.63%   |
| Namyangju     | 1         | 0.63%   |
| Mapo-gu       | 1         | 0.63%   |
| Koesan        | 1         | 0.63%   |
| Jungnang-gu   | 1         | 0.63%   |
| Hwacheon      | 1         | 0.63%   |
| Haeundae-gu   | 1         | 0.63%   |
| Gyeyang-gu    | 1         | 0.63%   |
| Gyeonggi-do   | 1         | 0.63%   |
| Gwangsan-gu   | 1         | 0.63%   |
| Gwangmyeong   | 1         | 0.63%   |
| Gumi          | 1         | 0.63%   |
| Guji          | 1         | 0.63%   |
| Goseong-gun   | 1         | 0.63%   |
| Gimhae        | 1         | 0.63%   |
| Geumcheon-gu  | 1         | 0.63%   |
| Geochang-gun  | 1         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 51        | 60     | 25%     |
| WDC                     | 22        | 24     | 10.78%  |
| Unknown                 | 15        | 19     | 7.35%   |
| SK Hynix                | 13        | 18     | 6.37%   |
| SanDisk                 | 13        | 13     | 6.37%   |
| Toshiba                 | 12        | 14     | 5.88%   |
| Seagate                 | 11        | 14     | 5.39%   |
| Crucial                 | 8         | 9      | 3.92%   |
| Kingston                | 7         | 8      | 3.43%   |
| Intel                   | 6         | 11     | 2.94%   |
| Hitachi                 | 5         | 6      | 2.45%   |
| Phison                  | 4         | 4      | 1.96%   |
| Micron Technology       | 4         | 5      | 1.96%   |
| A-DATA Technology       | 4         | 4      | 1.96%   |
| TAMMUZ                  | 3         | 5      | 1.47%   |
| HGST                    | 3         | 4      | 1.47%   |
| Fujitsu                 | 2         | 2      | 0.98%   |
| Apple                   | 2         | 2      | 0.98%   |
| VIVA300s                | 1         | 1      | 0.49%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.49%   |
| UMIS                    | 1         | 1      | 0.49%   |
| TYPEC 1T                | 1         | 1      | 0.49%   |
| Transcend               | 1         | 2      | 0.49%   |
| Team                    | 1         | 1      | 0.49%   |
| RevuAhn                 | 1         | 1      | 0.49%   |
| PLEXTOR                 | 1         | 1      | 0.49%   |
| LITEONIT                | 1         | 1      | 0.49%   |
| KIOXIA                  | 1         | 1      | 0.49%   |
| KingSpec                | 1         | 1      | 0.49%   |
| JMicron                 | 1         | 1      | 0.49%   |
| ipTIME                  | 1         | 1      | 0.49%   |
| IPLEX                   | 1         | 1      | 0.49%   |
| imation                 | 1         | 1      | 0.49%   |
| External                | 1         | 1      | 0.49%   |
| ES                      | 1         | 1      | 0.49%   |
| Biostar                 | 1         | 1      | 0.49%   |
| Apacer                  | 1         | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| SK Hynix SHGP31-1000GM-2 1TB                 | 3         | 1.38%   |
| Samsung SSD 860 EVO 500GB                    | 3         | 1.38%   |
| WDC WDS100T2B0C-00PXH0 1TB                   | 2         | 0.92%   |
| WDC WD50 00LPVX-22V0TT0 500GB                | 2         | 0.92%   |
| Unknown SLD64G  64GB                         | 2         | 0.92%   |
| Unknown MMC Card  32GB                       | 2         | 0.92%   |
| Toshiba KBG30ZMV256G 256GB                   | 2         | 0.92%   |
| SK Hynix NVMe SSD Drive 256GB                | 2         | 0.92%   |
| Seagate ST1000LM035-1RK172 1TB               | 2         | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 0.92%   |
| Sandisk NVMe SSD Drive 512GB                 | 2         | 0.92%   |
| Sandisk NVMe SSD Drive 256GB                 | 2         | 0.92%   |
| Samsung SSD 860 EVO 1TB                      | 2         | 0.92%   |
| Samsung SSD 830 Series 256GB                 | 2         | 0.92%   |
| Samsung SSD 750 EVO 120GB                    | 2         | 0.92%   |
| Samsung NVMe SSD Drive 2TB                   | 2         | 0.92%   |
| Samsung NVMe SSD Drive 256GB                 | 2         | 0.92%   |
| Samsung MZVLB512HAJQ-00000 512GB             | 2         | 0.92%   |
| Samsung MZVLB256HBHQ-000 256GB               | 2         | 0.92%   |
| Samsung MZNLN256HAJQ-00000 256GB SSD         | 2         | 0.92%   |
| Kingston OM8PCP3512F-AB 512GB                | 2         | 0.92%   |
| HGST HTS721010A9E630 1TB                     | 2         | 0.92%   |
| Crucial CT500MX500SSD1 500GB                 | 2         | 0.92%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 0.46%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD             | 1         | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 1         | 0.46%   |
| WDC WDS120G1G0A-00SS50 120GB SSD             | 1         | 0.46%   |
| WDC WD7500BPVT-22HXZT1 752GB                 | 1         | 0.46%   |
| WDC WD600BEVS-60LAT0 64GB                    | 1         | 0.46%   |
| WDC WD3200BEKT-00F3T0 320GB                  | 1         | 0.46%   |
| WDC WD20SPZX-22UA7T0 2TB                     | 1         | 0.46%   |
| WDC WD10SPZX-75Z10T1 1TB                     | 1         | 0.46%   |
| WDC WD10SPZX-60Z10T0 1TB                     | 1         | 0.46%   |
| WDC WD10SPZX-22Z10T0 1TB                     | 1         | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB                     | 1         | 0.46%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 1         | 0.46%   |
| WDC WD10JPVX-08JC3T5 1TB                     | 1         | 0.46%   |
| WDC PC SN720 SDAPNTW-512G-1101 512GB         | 1         | 0.46%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB         | 1         | 0.46%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB         | 1         | 0.46%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB         | 1         | 0.46%   |
| WDC PC SN530 SDBPNPZ-1T00-10SB 1TB           | 1         | 0.46%   |
| WDC PC SN530 NVMe 256GB                      | 1         | 0.46%   |
| VIVA300s LITE MM 1024GB                      | 1         | 0.46%   |
| Unknown USDU1  65GB                          | 1         | 0.46%   |
| Unknown SU08G  8GB                           | 1         | 0.46%   |
| Unknown SDW32G  32GB                         | 1         | 0.46%   |
| Unknown SD/MMC/MS PRO 999GB                  | 1         | 0.46%   |
| Unknown NVMe SSD Drive 256GB                 | 1         | 0.46%   |
| Unknown MMC Card  8GB                        | 1         | 0.46%   |
| Unknown MMC Card  64GB                       | 1         | 0.46%   |
| Unknown MMC Card  4GB                        | 1         | 0.46%   |
| Unknown MMC Card  256GB                      | 1         | 0.46%   |
| Unknown MBG4GC  32GB                         | 1         | 0.46%   |
| Unknown DA4064  64GB                         | 1         | 0.46%   |
| Unknown Biwin  32GB                          | 1         | 0.46%   |
| Unknown 032GE4  32GB                         | 1         | 0.46%   |
| Unknown 00000  8GB                           | 1         | 0.46%   |
| Union Memory (Shenzhen) NVMe SSD Drive 256GB | 1         | 0.46%   |
| UMIS RPETJ256MGE2MDQ 256GB                   | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 30%     |
| Seagate             | 10        | 13     | 25%     |
| Toshiba             | 5         | 5      | 12.5%   |
| Hitachi             | 5         | 6      | 12.5%   |
| HGST                | 3         | 4      | 7.5%    |
| Fujitsu             | 2         | 2      | 5%      |
| Unknown             | 1         | 1      | 2.5%    |
| Samsung Electronics | 1         | 1      | 2.5%    |
| ipTIME              | 1         | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 36     | 41.33%  |
| SanDisk             | 7         | 7      | 9.33%   |
| Crucial             | 7         | 8      | 9.33%   |
| WDC                 | 3         | 4      | 4%      |
| TAMMUZ              | 3         | 5      | 4%      |
| Micron Technology   | 3         | 4      | 4%      |
| Kingston            | 3         | 4      | 4%      |
| Intel               | 3         | 4      | 4%      |
| A-DATA Technology   | 2         | 2      | 2.67%   |
| TYPEC 1T            | 1         | 1      | 1.33%   |
| Transcend           | 1         | 2      | 1.33%   |
| Toshiba             | 1         | 1      | 1.33%   |
| Team                | 1         | 1      | 1.33%   |
| SK Hynix            | 1         | 1      | 1.33%   |
| RevuAhn             | 1         | 1      | 1.33%   |
| PLEXTOR             | 1         | 1      | 1.33%   |
| LITEONIT            | 1         | 1      | 1.33%   |
| KingSpec            | 1         | 1      | 1.33%   |
| IPLEX               | 1         | 1      | 1.33%   |
| Biostar             | 1         | 1      | 1.33%   |
| Apple               | 1         | 1      | 1.33%   |
| Apacer              | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 69        | 88     | 36.13%  |
| NVMe    | 64        | 86     | 33.51%  |
| HDD     | 40        | 45     | 20.94%  |
| MMC     | 14        | 18     | 7.33%   |
| Unknown | 4         | 5      | 2.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 88        | 126    | 50%     |
| NVMe | 64        | 86     | 36.36%  |
| MMC  | 14        | 18     | 7.95%   |
| SAS  | 10        | 12     | 5.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 73        | 95     | 68.22%  |
| 0.51-1.0   | 30        | 33     | 28.04%  |
| 1.01-2.0   | 2         | 3      | 1.87%   |
| 3.01-4.0   | 1         | 1      | 0.93%   |
| 4.01-10.0  | 1         | 1      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 60        | 37.27%  |
| 251-500        | 33        | 20.5%   |
| 501-1000       | 21        | 13.04%  |
| 51-100         | 15        | 9.32%   |
| 1001-2000      | 11        | 6.83%   |
| 21-50          | 8         | 4.97%   |
| 1-20           | 7         | 4.35%   |
| More than 3000 | 4         | 2.48%   |
| 2001-3000      | 1         | 0.62%   |
| Unknown        | 1         | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 70        | 41.92%  |
| 21-50     | 36        | 21.56%  |
| 101-250   | 22        | 13.17%  |
| 51-100    | 17        | 10.18%  |
| 251-500   | 11        | 6.59%   |
| 1001-2000 | 5         | 2.99%   |
| 501-1000  | 4         | 2.4%    |
| 2001-3000 | 1         | 0.6%    |
| Unknown   | 1         | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB             | 1         | 1      | 10%     |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 10%     |
| Toshiba MK5061GSYN 500GB                 | 1         | 1      | 10%     |
| Toshiba MK2565GSX 250GB                  | 1         | 1      | 10%     |
| Samsung Electronics SSD 830 Series 512GB | 1         | 1      | 10%     |
| Phison ES 512GB                          | 1         | 1      | 10%     |
| LITEONIT LMT-256M3M 256GB SSD            | 1         | 1      | 10%     |
| Kingston SHFS37A120G 120GB SSD           | 1         | 1      | 10%     |
| Hitachi HTS541616J9SA00 160GB            | 1         | 1      | 10%     |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 20%     |
| Toshiba             | 2         | 2      | 20%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Phison              | 1         | 1      | 10%     |
| LITEONIT            | 1         | 1      | 10%     |
| Kingston            | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| HGST                | 1         | 1      | 10%     |

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
| HDD  | 6         | 6      | 60%     |
| SSD  | 3         | 3      | 30%     |
| NVMe | 1         | 1      | 10%     |

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
| Detected | 93        | 139    | 55.69%  |
| Works    | 64        | 93     | 38.32%  |
| Malfunc  | 10        | 10     | 5.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 91        | 50.84%  |
| Samsung Electronics              | 19        | 10.61%  |
| AMD                              | 18        | 10.06%  |
| Sandisk                          | 13        | 7.26%   |
| SK Hynix                         | 11        | 6.15%   |
| Toshiba America Info Systems     | 6         | 3.35%   |
| Phison Electronics               | 6         | 3.35%   |
| Kingston Technology Company      | 4         | 2.23%   |
| Union Memory (Shenzhen)          | 2         | 1.12%   |
| Nvidia                           | 2         | 1.12%   |
| ADATA Technology                 | 2         | 1.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Micron/Crucial Technology        | 1         | 0.56%   |
| Micron Technology                | 1         | 0.56%   |
| KIOXIA                           | 1         | 0.56%   |
| Apple                            | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 17        | 9.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 6.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 5.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 4.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 4.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 4.3%    |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 6         | 3.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 2.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 2.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.69%   |
| SK Hynix Gold P31 SSD                                                            | 4         | 2.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 2.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 2.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.15%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 1.61%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 1.61%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.61%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.61%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.61%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 1.08%   |
| SK Hynix Non-Volatile memory controller                                          | 2         | 1.08%   |
| SK Hynix BC511                                                                   | 2         | 1.08%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 1.08%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 1.08%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 1.08%   |
| Phison NVMe Storage Controller                                                   | 2         | 1.08%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.08%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.08%   |
| Intel SSD 660P Series                                                            | 2         | 1.08%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.08%   |
| SK Hynix PC300 NVMe Solid State Drive 512GB                                      | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.54%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.54%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.54%   |
| Sandisk Non-Volatile memory controller                                           | 1         | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.54%   |
| Micron/Crucial Non-Volatile memory controller                                    | 1         | 0.54%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.54%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 0.54%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.54%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.54%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.54%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.54%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 0.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 0.54%   |
| Apple ANS2 NVMe Controller                                                       | 1         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 97        | 55.11%  |
| NVMe | 64        | 36.36%  |
| RAID | 9         | 5.11%   |
| IDE  | 6         | 3.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 126       | 82.35%  |
| AMD    | 26        | 16.99%  |
| ARM    | 1         | 0.65%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 3.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 3.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 3.27%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 3.27%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.96%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 1.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.96%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.96%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 1.96%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 1.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.31%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 1.31%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 1.31%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 1.31%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 1.31%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.31%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 1.31%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.31%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 1.31%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.31%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.31%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.31%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.31%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.31%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.31%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.31%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.65%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.65%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.65%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.65%   |
| Intel Pentium 3558U @ 1.70GHz                 | 1         | 0.65%   |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 0.65%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 0.65%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.65%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 1         | 0.65%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.65%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.65%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.65%   |
| Intel Core i7-8569U CPU @ 2.80GHz             | 1         | 0.65%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.65%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.65%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz            | 1         | 0.65%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.65%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.65%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 0.65%   |
| Intel Core i7-3820QM CPU @ 2.70GHz            | 1         | 0.65%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.65%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.65%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.65%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.65%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.65%   |
| Intel Core i5-8265UC CPU @ 1.60GHz            | 1         | 0.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.65%   |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 0.65%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 40        | 26.14%  |
| Intel Core i5        | 33        | 21.57%  |
| Other                | 13        | 8.5%    |
| Intel Core i3        | 11        | 7.19%   |
| AMD Ryzen 7          | 9         | 5.88%   |
| Intel Core 2 Duo     | 7         | 4.58%   |
| Intel Celeron        | 7         | 4.58%   |
| AMD Ryzen 5          | 6         | 3.92%   |
| Intel Pentium        | 4         | 2.61%   |
| Intel Atom           | 4         | 2.61%   |
| Intel Pentium Silver | 2         | 1.31%   |
| Intel Genuine        | 2         | 1.31%   |
| Intel Core i9        | 2         | 1.31%   |
| AMD Ryzen 7 PRO      | 2         | 1.31%   |
| AMD Ryzen 3          | 2         | 1.31%   |
| AMD A4               | 2         | 1.31%   |
| AMD A10              | 2         | 1.31%   |
| Intel Pentium Dual   | 1         | 0.65%   |
| Intel Core 2         | 1         | 0.65%   |
| AMD Ryzen 9          | 1         | 0.65%   |
| AMD Ryzen 5 PRO      | 1         | 0.65%   |
| AMD Quad-Core        | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 63        | 41.18%  |
| 4       | 60        | 39.22%  |
| 8       | 16        | 10.46%  |
| 6       | 12        | 7.84%   |
| 1       | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 152       | 99.35%  |
| 2      | 1         | 0.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 120       | 78.43%  |
| 1       | 32        | 20.92%  |
| Unknown | 1         | 0.65%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 149       | 97.39%  |
| Unknown        | 2         | 1.31%   |
| 64-bit         | 1         | 0.65%   |
| 32-bit         | 1         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 11.46%  |
| 0x806ec    | 12        | 7.64%   |
| 0x806c1    | 11        | 7.01%   |
| 0x306a9    | 9         | 5.73%   |
| 0x206a7    | 9         | 5.73%   |
| 0x20655    | 7         | 4.46%   |
| 0x08600106 | 7         | 4.46%   |
| 0x806eb    | 6         | 3.82%   |
| 0x806ea    | 5         | 3.18%   |
| 0x906e9    | 4         | 2.55%   |
| 0x706e5    | 4         | 2.55%   |
| 0x706a1    | 4         | 2.55%   |
| 0x40651    | 4         | 2.55%   |
| 0x30678    | 4         | 2.55%   |
| 0x08108102 | 4         | 2.55%   |
| 0xa0652    | 3         | 1.91%   |
| 0x906ed    | 3         | 1.91%   |
| 0x806e9    | 3         | 1.91%   |
| 0x6fd      | 3         | 1.91%   |
| 0x306c3    | 3         | 1.91%   |
| 0x1067a    | 3         | 1.91%   |
| 0xa0660    | 2         | 1.27%   |
| 0x906ea    | 2         | 1.27%   |
| 0x406c3    | 2         | 1.27%   |
| 0x306d4    | 2         | 1.27%   |
| 0x20652    | 2         | 1.27%   |
| 0x10676    | 2         | 1.27%   |
| 0x0a50000c | 2         | 1.27%   |
| 0x08600103 | 2         | 1.27%   |
| 0x0700010f | 2         | 1.27%   |
| 0x06001119 | 2         | 1.27%   |
| 0x806d1    | 1         | 0.64%   |
| 0x706a8    | 1         | 0.64%   |
| 0x6f6      | 1         | 0.64%   |
| 0x6e8      | 1         | 0.64%   |
| 0x106e5    | 1         | 0.64%   |
| 0x0a50000b | 1         | 0.64%   |
| 0x08608103 | 1         | 0.64%   |
| 0x08600104 | 1         | 0.64%   |
| 0x08600102 | 1         | 0.64%   |
| 0x07000106 | 1         | 0.64%   |
| 0x0600611a | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 37        | 24.18%  |
| Zen 2         | 12        | 7.84%   |
| TigerLake     | 11        | 7.19%   |
| Westmere      | 10        | 6.54%   |
| SandyBridge   | 10        | 6.54%   |
| Haswell       | 10        | 6.54%   |
| IvyBridge     | 9         | 5.88%   |
| Silvermont    | 7         | 4.58%   |
| Penryn        | 6         | 3.92%   |
| IceLake       | 5         | 3.27%   |
| Goldmont plus | 5         | 3.27%   |
| CometLake     | 5         | 3.27%   |
| Zen+          | 4         | 2.61%   |
| Core          | 4         | 2.61%   |
| Zen 3         | 3         | 1.96%   |
| Skylake       | 2         | 1.31%   |
| Piledriver    | 2         | 1.31%   |
| Jaguar        | 2         | 1.31%   |
| Broadwell     | 2         | 1.31%   |
| Unknown       | 2         | 1.31%   |
| Zen           | 1         | 0.65%   |
| P6            | 1         | 0.65%   |
| Nehalem       | 1         | 0.65%   |
| Excavator     | 1         | 0.65%   |
| Bonnell       | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 111       | 56.63%  |
| Nvidia                           | 51        | 26.02%  |
| AMD                              | 33        | 16.84%  |
| Silicon Integrated Systems [SiS] | 1         | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 12        | 5.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 4.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 4.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 3.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 3.98%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.99%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.99%   |
| Intel HD Graphics 630                                                                    | 4         | 1.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.99%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.49%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 1.49%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.49%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.49%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 1%      |
| Nvidia TU117M                                                                            | 2         | 1%      |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1%      |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1%      |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 1%      |
| Intel HD Graphics 530                                                                    | 2         | 1%      |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1%      |
| Intel Comet Lake UHD Graphics                                                            | 2         | 1%      |
| AMD Cezanne                                                                              | 2         | 1%      |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.5%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.5%    |
| Nvidia GT215GLM [Quadro FX 1800M]                                                        | 1         | 0.5%    |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.5%    |
| Nvidia GP108GLM [Quadro P500 Mobile]                                                     | 1         | 0.5%    |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.5%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.5%    |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 0.5%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.5%    |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.5%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.5%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.5%    |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 1         | 0.5%    |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 0.5%    |
| Nvidia GK106M [GeForce GTX 760M]                                                         | 1         | 0.5%    |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.5%    |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.5%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.5%    |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.5%    |
| Nvidia GF106M [GeForce GTX 460M]                                                         | 1         | 0.5%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.5%    |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 0.5%    |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.5%    |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.5%    |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 71        | 46.41%  |
| Intel + Nvidia | 35        | 22.88%  |
| 1 x AMD        | 23        | 15.03%  |
| 1 x Nvidia     | 11        | 7.19%   |
| Intel + AMD    | 4         | 2.61%   |
| AMD + Nvidia   | 4         | 2.61%   |
| 2 x AMD        | 2         | 1.31%   |
| Other          | 1         | 0.65%   |
| 2 x Nvidia     | 1         | 0.65%   |
| 1 x SiS        | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 125       | 81.17%  |
| Proprietary | 23        | 14.94%  |
| Unknown     | 6         | 3.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 57.69%  |
| 0.01-0.5   | 18        | 11.54%  |
| 1.01-2.0   | 17        | 10.9%   |
| 3.01-4.0   | 16        | 10.26%  |
| 0.51-1.0   | 9         | 5.77%   |
| 5.01-6.0   | 4         | 2.56%   |
| 7.01-8.0   | 2         | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 35        | 19.89%  |
| AU Optronics            | 31        | 17.61%  |
| Samsung Electronics     | 24        | 13.64%  |
| BOE                     | 22        | 12.5%   |
| Chimei Innolux          | 11        | 6.25%   |
| Goldstar                | 8         | 4.55%   |
| Sharp                   | 7         | 3.98%   |
| Apple                   | 5         | 2.84%   |
| PANDA                   | 4         | 2.27%   |
| Dell                    | 3         | 1.7%    |
| CPT                     | 3         | 1.7%    |
| Philips                 | 2         | 1.14%   |
| JCH                     | 2         | 1.14%   |
| CSO                     | 2         | 1.14%   |
| Chi Mei Optoelectronics | 2         | 1.14%   |
| ALP                     | 2         | 1.14%   |
| VMO                     | 1         | 0.57%   |
| TMX                     | 1         | 0.57%   |
| Sony                    | 1         | 0.57%   |
| PRISM+                  | 1         | 0.57%   |
| Lenovo                  | 1         | 0.57%   |
| InfoVision              | 1         | 0.57%   |
| HKC                     | 1         | 0.57%   |
| Hewlett-Packard         | 1         | 0.57%   |
| HannStar                | 1         | 0.57%   |
| Denver                  | 1         | 0.57%   |
| CM_                     | 1         | 0.57%   |
| BenQ                    | 1         | 0.57%   |
| Ancor Communications    | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 1.69%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 3         | 1.69%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 1.69%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.69%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 1.12%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch          | 2         | 1.12%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 2         | 1.12%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch          | 2         | 1.12%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.12%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 1.12%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 1.12%   |
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                 | 2         | 1.12%   |
| BOE LCD Monitor BOE06D7 3840x2160 345x194mm 15.6-inch                 | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 2         | 1.12%   |
| AU Optronics LCD Monitor 1920x1080                                    | 2         | 1.12%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch             | 1         | 0.56%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.56%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.56%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch               | 1         | 0.56%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.56%   |
| Samsung Electronics U32H85x SAM0E3A 3840x2160 697x392mm 31.5-inch     | 1         | 0.56%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch     | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM01A2 1280x1024 376x301mm 19.0-inch  | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM0138 1280x1024 338x270mm 17.0-inch  | 1         | 0.56%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch  | 1         | 0.56%   |
| Samsung Electronics SMBX2350 SAM071E 1920x1080 509x286mm 23.0-inch    | 1         | 0.56%   |
| Samsung Electronics S27R65 SAM1045 1920x1080 598x336mm 27.0-inch      | 1         | 0.56%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch     | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5643 1280x800 303x190mm 14.1-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5244 1600x900 360x210mm 16.4-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 331x207mm 15.4-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 530x300mm 24.0-inch | 1         | 0.56%   |
| PRISM+ X315 INN3200 2560x1440 697x393mm 31.5-inch                     | 1         | 0.56%   |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch               | 1         | 0.56%   |
| Philips 237E4 PHLC0AD 1920x1080 509x286mm 23.0-inch                   | 1         | 0.56%   |
| PANDA LCD Monitor NCP0064 1920x1080 344x194mm 15.5-inch               | 1         | 0.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.56%   |
| PANDA LCD Monitor NCP0021 1920x1080 344x194mm 15.5-inch               | 1         | 0.56%   |
| PANDA LCD Monitor NCP000D 1920x1080 344x194mm 15.5-inch               | 1         | 0.56%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD0695 2560x1600 366x229mm 17.0-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD0644 1920x1080 309x174mm 14.0-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 83        | 50%     |
| 1366x768 (WXGA)    | 32        | 19.28%  |
| 3840x2160 (4K)     | 9         | 5.42%   |
| 2560x1600          | 8         | 4.82%   |
| 1600x900 (HD+)     | 7         | 4.22%   |
| 1280x800 (WXGA)    | 6         | 3.61%   |
| 2560x1440 (QHD)    | 5         | 3.01%   |
| 1920x1200 (WUXGA)  | 5         | 3.01%   |
| 1440x900 (WXGA+)   | 3         | 1.81%   |
| 2880x1800          | 2         | 1.2%    |
| 1280x1024 (SXGA)   | 2         | 1.2%    |
| 3440x1440          | 1         | 0.6%    |
| 2560x1080          | 1         | 0.6%    |
| 1680x945           | 1         | 0.6%    |
| 1680x1050 (WSXGA+) | 1         | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 70        | 39.55%  |
| 13      | 27        | 15.25%  |
| 14      | 23        | 12.99%  |
| 17      | 9         | 5.08%   |
| 24      | 8         | 4.52%   |
| 23      | 7         | 3.95%   |
| 27      | 5         | 2.82%   |
| 16      | 5         | 2.82%   |
| 31      | 4         | 2.26%   |
| 21      | 3         | 1.69%   |
| 11      | 3         | 1.69%   |
| 12      | 2         | 1.13%   |
| Unknown | 2         | 1.13%   |
| 74      | 1         | 0.56%   |
| 54      | 1         | 0.56%   |
| 40      | 1         | 0.56%   |
| 34      | 1         | 0.56%   |
| 25      | 1         | 0.56%   |
| 20      | 1         | 0.56%   |
| 19      | 1         | 0.56%   |
| 18      | 1         | 0.56%   |
| 10      | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 103       | 58.52%  |
| 201-300     | 25        | 14.2%   |
| 501-600     | 19        | 10.8%   |
| 351-400     | 12        | 6.82%   |
| 401-500     | 6         | 3.41%   |
| 601-700     | 5         | 2.84%   |
| Unknown     | 2         | 1.14%   |
| 801-900     | 1         | 0.57%   |
| 701-800     | 1         | 0.57%   |
| 1501-2000   | 1         | 0.57%   |
| 1001-1500   | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 123       | 79.87%  |
| 16/10   | 25        | 16.23%  |
| 5/4     | 2         | 1.3%    |
| Unknown | 2         | 1.3%    |
| 3/2     | 1         | 0.65%   |
| 21/9    | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 70        | 39.55%  |
| 81-90          | 33        | 18.64%  |
| 71-80          | 17        | 9.6%    |
| 201-250        | 15        | 8.47%   |
| 121-130        | 8         | 4.52%   |
| 351-500        | 5         | 2.82%   |
| 301-350        | 5         | 2.82%   |
| 251-300        | 4         | 2.26%   |
| 111-120        | 4         | 2.26%   |
| 51-60          | 3         | 1.69%   |
| More than 1000 | 2         | 1.13%   |
| 61-70          | 2         | 1.13%   |
| 151-200        | 2         | 1.13%   |
| 141-150        | 2         | 1.13%   |
| Unknown        | 2         | 1.13%   |
| 41-50          | 1         | 0.56%   |
| 501-1000       | 1         | 0.56%   |
| 91-100         | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 74        | 42.53%  |
| 101-120       | 36        | 20.69%  |
| 51-100        | 31        | 17.82%  |
| 161-240       | 21        | 12.07%  |
| More than 240 | 8         | 4.6%    |
| 1-50          | 2         | 1.15%   |
| Unknown       | 2         | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 119       | 74.84%  |
| 2     | 31        | 19.5%   |
| 0     | 6         | 3.77%   |
| 3     | 3         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 98        | 41.53%  |
| Realtek Semiconductor            | 74        | 31.36%  |
| Qualcomm Atheros                 | 23        | 9.75%   |
| Broadcom                         | 15        | 6.36%   |
| ASIX Electronics                 | 6         | 2.54%   |
| Marvell Technology Group         | 3         | 1.27%   |
| TP-Link                          | 2         | 0.85%   |
| Nvidia                           | 2         | 0.85%   |
| MEDIATEK                         | 2         | 0.85%   |
| Lenovo                           | 2         | 0.85%   |
| Broadcom Limited                 | 2         | 0.85%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Samsung Electronics              | 1         | 0.42%   |
| Ralink Technology                | 1         | 0.42%   |
| Ralink                           | 1         | 0.42%   |
| D-Link                           | 1         | 0.42%   |
| Comneon                          | 1         | 0.42%   |
| Arduino SA                       | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 56        | 20.9%   |
| Intel Wi-Fi 6 AX200                                               | 17        | 6.34%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 3.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 3.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 3.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 2.24%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 2.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.87%   |
| Intel Wireless 7260                                               | 5         | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.49%   |
| Intel Wireless 3165                                               | 4         | 1.49%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 4         | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.12%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.12%   |
| Intel Wireless 7265                                               | 3         | 1.12%   |
| Intel Wireless 3160                                               | 3         | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.12%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.12%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.75%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.75%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.75%   |
| Intel WiFi Link 5100                                              | 2         | 0.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.75%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.75%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.75%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.75%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.75%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 2         | 0.75%   |
| Broadcom BCM43162 802.11ac Wireless Network Adapter               | 2         | 0.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.37%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                             | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.37%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1         | 0.37%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.37%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.37%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 95        | 62.91%  |
| Realtek Semiconductor | 18        | 11.92%  |
| Qualcomm Atheros      | 17        | 11.26%  |
| Broadcom              | 12        | 7.95%   |
| TP-Link               | 2         | 1.32%   |
| MEDIATEK              | 2         | 1.32%   |
| Broadcom Limited      | 2         | 1.32%   |
| Ralink Technology     | 1         | 0.66%   |
| Ralink                | 1         | 0.66%   |
| D-Link                | 1         | 0.66%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 17        | 11.18%  |
| Intel Wi-Fi 6 AX201                                                     | 10        | 6.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 5.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 3.95%   |
| Intel Wireless 7260                                                     | 5         | 3.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 3.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.63%   |
| Intel Wireless 3165                                                     | 4         | 2.63%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 4         | 2.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.97%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.97%   |
| Intel Wireless 7265                                                     | 3         | 1.97%   |
| Intel Wireless 3160                                                     | 3         | 1.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.97%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 1.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.97%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.32%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.32%   |
| Intel WiFi Link 5100                                                    | 2         | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.32%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.32%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.32%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.32%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 1.32%   |
| Broadcom BCM43162 802.11ac Wireless Network Adapter                     | 2         | 1.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.66%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                   | 1         | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.66%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1         | 0.66%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.66%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.66%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.66%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.66%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.66%   |
| D-Link 802.11ac NIC                                                     | 1         | 0.66%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                  | 1         | 0.66%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 0.66%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 1         | 0.66%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 70        | 63.06%  |
| Intel                            | 15        | 13.51%  |
| Qualcomm Atheros                 | 8         | 7.21%   |
| ASIX Electronics                 | 6         | 5.41%   |
| Marvell Technology Group         | 3         | 2.7%    |
| Broadcom                         | 3         | 2.7%    |
| Nvidia                           | 2         | 1.8%    |
| Lenovo                           | 2         | 1.8%    |
| Silicon Integrated Systems [SiS] | 1         | 0.9%    |
| Samsung Electronics              | 1         | 0.9%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 56        | 49.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 7.89%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 6         | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 3.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.75%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.75%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.75%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.75%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.88%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.88%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.88%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.88%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.88%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.88%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.88%   |
| Intel Ethernet controller                                                      | 1         | 0.88%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.88%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.88%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.88%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 145       | 57.09%  |
| Ethernet | 107       | 42.13%  |
| Modem    | 2         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 117       | 72.67%  |
| Ethernet | 44        | 27.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 93        | 60.78%  |
| 1     | 55        | 35.95%  |
| 0     | 4         | 2.61%   |
| 3     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 152       | 99.35%  |
| Yes  | 1         | 0.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 76        | 62.3%   |
| Realtek Semiconductor           | 10        | 8.2%    |
| Broadcom                        | 10        | 8.2%    |
| Qualcomm Atheros Communications | 7         | 5.74%   |
| IMC Networks                    | 7         | 5.74%   |
| Lite-On Technology              | 4         | 3.28%   |
| Foxconn / Hon Hai               | 3         | 2.46%   |
| Apple                           | 3         | 2.46%   |
| Qcom                            | 1         | 0.82%   |
| Micro Star International        | 1         | 0.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 19        | 15.57%  |
| Intel Bluetooth wireless interface                                                  | 18        | 14.75%  |
| Intel AX200 Bluetooth                                                               | 17        | 13.93%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 15        | 12.3%   |
| Realtek Bluetooth Radio                                                             | 5         | 4.1%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.46%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 2.46%   |
| Lite-On Bluetooth Device                                                            | 3         | 2.46%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 2.46%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 2.46%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 2.46%   |
| Apple Bluetooth Host Controller                                                     | 3         | 2.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.64%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.64%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.64%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.64%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 1.64%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.64%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.64%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.82%   |
| Realtek CSR BS8510                                                                  | 1         | 0.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.82%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.82%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.82%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.82%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.82%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.82%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 120       | 65.93%  |
| AMD                              | 31        | 17.03%  |
| Nvidia                           | 22        | 12.09%  |
| Lenovo                           | 2         | 1.1%    |
| JMTek                            | 2         | 1.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| Razer USA                        | 1         | 0.55%   |
| Dell                             | 1         | 0.55%   |
| Apple                            | 1         | 0.55%   |
| Unknown                          | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 21        | 9.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 6.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 5.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 5.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 5.02%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 4.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 4.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 4.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 3.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.74%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 2.28%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.83%   |
| Nvidia Audio device                                                                               | 4         | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.83%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.37%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.37%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.37%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.91%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.91%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.91%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.91%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.91%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.46%   |
| Razer USA Razer Barracuda X                                                                       | 1         | 0.46%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.46%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.46%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.46%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.46%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.46%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 1         | 0.46%   |
| Lenovo ThinkPad Dock Audio                                                                        | 1         | 0.46%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.46%   |
| JMTek USB Audio Device                                                                            | 1         | 0.46%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.46%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.46%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.46%   |
| Dell AC511 Sound Bar                                                                              | 1         | 0.46%   |
| Apple Audio Device                                                                                | 1         | 0.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.46%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.46%   |
| Unknown                                                                                           | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 50        | 50%     |
| SK Hynix            | 22        | 22%     |
| Micron Technology   | 9         | 9%      |
| Unknown             | 4         | 4%      |
| Kingston            | 3         | 3%      |
| Unknown (ABCD)      | 2         | 2%      |
| Ramaxel Technology  | 2         | 2%      |
| A-DATA Technology   | 2         | 2%      |
| Unknown             | 2         | 2%      |
| Unknown (09D5)      | 1         | 1%      |
| Team                | 1         | 1%      |
| Silicon Power       | 1         | 1%      |
| Elpida              | 1         | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 5.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 3.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 3.67%   |
| SK Hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 3         | 2.75%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2.75%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 2.75%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 1.83%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 2         | 1.83%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.83%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.83%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.83%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.83%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.83%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.83%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.83%   |
| Samsung RAM M471A1G44AB0-CTD 8GB DDR4 2667MT/s                   | 2         | 1.83%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.83%   |
| Unknown                                                          | 2         | 1.83%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.92%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.92%   |
| Unknown RAM CL22-22-22 D4-3200 16384MB SODIMM DDR4 3200MT/s      | 1         | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s   | 1         | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.92%   |
| Unknown (09D5) RAM Module 16384MB SODIMM DDR4 2400MT/s           | 1         | 0.92%   |
| Team RAM TEAMGROUP-SD4-2666 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.92%   |
| SK Hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.92%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                 | 1         | 0.92%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.92%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.92%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.92%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s        | 1         | 0.92%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s    | 1         | 0.92%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.92%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.92%   |
| SK Hynix RAM HMA851S6DJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.92%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.92%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.92%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.92%   |
| SK Hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.92%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.92%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 1         | 0.92%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.92%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 0.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.92%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.92%   |
| Samsung RAM M471B1G73CB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.92%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4096MB DDR4 2667MT/s                | 1         | 0.92%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.92%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 0.92%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 0.92%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 1         | 0.92%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 0.92%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.92%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.92%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB DDR4 2667MT/s                | 1         | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DDR4 2667MT/s                   | 1         | 0.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 54.12%  |
| DDR3   | 23        | 27.06%  |
| LPDDR4 | 8         | 9.41%   |
| LPDDR3 | 5         | 5.88%   |
| SDRAM  | 2         | 2.35%   |
| DDR2   | 1         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 65        | 75.58%  |
| Row Of Chips | 14        | 16.28%  |
| Unknown      | 4         | 4.65%   |
| DIMM         | 3         | 3.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 44        | 47.83%  |
| 4096  | 27        | 29.35%  |
| 16384 | 9         | 9.78%   |
| 2048  | 9         | 9.78%   |
| 32768 | 2         | 2.17%   |
| 1024  | 1         | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 24        | 26.09%  |
| 3200  | 20        | 21.74%  |
| 1600  | 15        | 16.3%   |
| 2400  | 8         | 8.7%    |
| 4267  | 5         | 5.43%   |
| 2133  | 5         | 5.43%   |
| 1334  | 5         | 5.43%   |
| 3266  | 4         | 4.35%   |
| 1333  | 2         | 2.17%   |
| 4199  | 1         | 1.09%   |
| 2048  | 1         | 1.09%   |
| 1067  | 1         | 1.09%   |
| 800   | 1         | 1.09%   |

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
| Chicony Electronics                    | 30        | 23.08%  |
| IMC Networks                           | 16        | 12.31%  |
| Acer                                   | 15        | 11.54%  |
| Realtek Semiconductor                  | 10        | 7.69%   |
| Microdia                               | 9         | 6.92%   |
| Silicon Motion                         | 8         | 6.15%   |
| Quanta                                 | 6         | 4.62%   |
| Unknown                                | 5         | 3.85%   |
| Suyin                                  | 5         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.85%   |
| Apple                                  | 5         | 3.85%   |
| Syntek                                 | 4         | 3.08%   |
| Sunplus Innovation Technology          | 3         | 2.31%   |
| Z-Star Microelectronics                | 2         | 1.54%   |
| Microsoft                              | 1         | 0.77%   |
| Luxvisions Innotech Limited            | 1         | 0.77%   |
| Logitech                               | 1         | 0.77%   |
| Lenovo                                 | 1         | 0.77%   |
| Goodong Industry                       | 1         | 0.77%   |
| DigiTech                               | 1         | 0.77%   |
| Alcor Micro                            | 1         | 0.77%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 8         | 6.06%   |
| Microdia Integrated_Webcam_HD                           | 6         | 4.55%   |
| Unknown 720p HD Camera                                  | 5         | 3.79%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 5         | 3.79%   |
| IMC Networks Integrated Camera                          | 5         | 3.79%   |
| Chicony HD Webcam                                       | 5         | 3.79%   |
| Acer HD Webcam                                          | 4         | 3.03%   |
| Suyin HP Truevision HD                                  | 3         | 2.27%   |
| Realtek LG Camera                                       | 3         | 2.27%   |
| Quanta HP TrueVision HD Camera                          | 3         | 2.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 2.27%   |
| Chicony LG Camera                                       | 3         | 2.27%   |
| Acer Integrated Camera                                  | 3         | 2.27%   |
| Z-Star Webcam                                           | 2         | 1.52%   |
| Syntek Integrated Camera                                | 2         | 1.52%   |
| Silicon Motion LG HD WebCam                             | 2         | 1.52%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.52%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.52%   |
| Quanta LG Webcam                                        | 2         | 1.52%   |
| Chicony USB 2.0 Camera                                  | 2         | 1.52%   |
| Chicony LG HD WebCam                                    | 2         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.52%   |
| Apple iPhone 5/5C/5S/6/SE                               | 2         | 1.52%   |
| Apple Built-in iSight                                   | 2         | 1.52%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.76%   |
| Syntek HP Webcam                                        | 1         | 0.76%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.76%   |
| Suyin HP TrueVision Full HD                             | 1         | 0.76%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.76%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.76%   |
| Sunplus Asus Webcam                                     | 1         | 0.76%   |
| Silicon Motion WebCam SC-13HDN10939N                    | 1         | 0.76%   |
| Silicon Motion WebCam SC-13HDL11431N                    | 1         | 0.76%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 1         | 0.76%   |
| Silicon Motion WebCam SC-10HDD13335N                    | 1         | 0.76%   |
| Silicon Motion Web Camera                               | 1         | 0.76%   |
| Silicon Motion ATIV VGA Camera                          | 1         | 0.76%   |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 0.76%   |
| Realtek Integrated Webcam                               | 1         | 0.76%   |
| Realtek HD WebCam                                       | 1         | 0.76%   |
| Quanta HP HD Camera                                     | 1         | 0.76%   |
| Microsoft LifeCam VX-2000                               | 1         | 0.76%   |
| Microdia Webcam SC-10HDD12636P                          | 1         | 0.76%   |
| Microdia USB 2.0 Camera                                 | 1         | 0.76%   |
| Microdia HP Webcam-101                                  | 1         | 0.76%   |
| Luxvisions Innotech Limited HP HD Camera                | 1         | 0.76%   |
| Logitech C922 Pro Stream Webcam                         | 1         | 0.76%   |
| Lenovo Integrated Webcam [R5U877]                       | 1         | 0.76%   |
| IMC Networks USB2.0 VGA Webcam                          | 1         | 0.76%   |
| IMC Networks USB2.0 5M AF UVC WebCam                    | 1         | 0.76%   |
| IMC Networks USB HD Webcam                              | 1         | 0.76%   |
| IMC Networks HP TrueVision HD Camera                    | 1         | 0.76%   |
| Goodong Industry USB2.0 HD UVC WebCam                   | 1         | 0.76%   |
| DigiTech WebCam SCB-1110M                               | 1         | 0.76%   |
| Chicony USB2.0 VGA UVC WebCam                           | 1         | 0.76%   |
| Chicony TOSHIBA Web Camera - HD                         | 1         | 0.76%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 1         | 0.76%   |
| Chicony Integrated Camera (1280x720@30)                 | 1         | 0.76%   |
| Chicony HP Webcam [2 MP Macro]                          | 1         | 0.76%   |
| Chicony HP Truevision HD camera                         | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 33.33%  |
| Validity Sensors           | 7         | 21.21%  |
| Samsung Electronics        | 4         | 12.12%  |
| Upek                       | 3         | 9.09%   |
| Shenzhen Goodix Technology | 3         | 9.09%   |
| LighTuning Technology      | 2         | 6.06%   |
| Elan Microelectronics      | 2         | 6.06%   |
| AuthenTec                  | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 4         | 12.12%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 3         | 9.09%   |
| Samsung Fingerprint Sensor Device - 730B                  | 3         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 6.06%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 6.06%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 6.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 6.06%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 6.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 2         | 6.06%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 3.03%   |
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 3.03%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 3.03%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 3.03%   |
| Validity Sensors Fingerprint scanner                      | 1         | 3.03%   |
| Synaptics WBDI Device                                     | 1         | 3.03%   |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 3.03%   |
| Samsung Fingerprint Device                                | 1         | 3.03%   |
| Elan ELAN:Fingerprint                                     | 1         | 3.03%   |
| Elan ELAN:ARM-M4                                          | 1         | 3.03%   |
| AuthenTec Fingerprint Sensor                              | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 40%     |
| Upek        | 1         | 20%     |
| O2 Micro    | 1         | 20%     |
| Broadcom    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 40%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 92        | 58.97%  |
| 1     | 55        | 35.26%  |
| 2     | 8         | 5.13%   |
| 3     | 1         | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 33        | 45.21%  |
| Graphics card         | 18        | 24.66%  |
| Net/wireless          | 11        | 15.07%  |
| Chipcard              | 5         | 6.85%   |
| Net/ethernet          | 2         | 2.74%   |
| Multimedia controller | 2         | 2.74%   |
| Sound                 | 1         | 1.37%   |
| Bluetooth             | 1         | 1.37%   |

