Fedora 37 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 912

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop M540... | [8bc290ef67](https://linux-hardware.org/?probe=8bc290ef67) | Feb 01, 2023 |
| MSI           | Modern 14 B11MOU            | [542173e9a2](https://linux-hardware.org/?probe=542173e9a2) | Feb 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [22abfb4a79](https://linux-hardware.org/?probe=22abfb4a79) | Feb 01, 2023 |
| Lenovo        | ThinkPad A485 20MVS0U500    | [b398a8e8e6](https://linux-hardware.org/?probe=b398a8e8e6) | Feb 01, 2023 |
| ASUSTek       | N552VW                      | [1ebeeec517](https://linux-hardware.org/?probe=1ebeeec517) | Feb 01, 2023 |
| Dell          | Inspiron 7501               | [426493e8a5](https://linux-hardware.org/?probe=426493e8a5) | Feb 01, 2023 |
| HP            | Laptop 14-dq4xxx            | [c102edf6a0](https://linux-hardware.org/?probe=c102edf6a0) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [6b9dc508e1](https://linux-hardware.org/?probe=6b9dc508e1) | Feb 01, 2023 |
| Dell          | Inspiron 5748               | [7ee6505f8d](https://linux-hardware.org/?probe=7ee6505f8d) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [1d212c67b2](https://linux-hardware.org/?probe=1d212c67b2) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| HUAWEI        | HN-WX9X                     | [4b8ddf5d09](https://linux-hardware.org/?probe=4b8ddf5d09) | Jan 31, 2023 |
| Dell          | Inspiron 5748               | [ecbd4ac8b6](https://linux-hardware.org/?probe=ecbd4ac8b6) | Jan 31, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | [85ac6a588d](https://linux-hardware.org/?probe=85ac6a588d) | Jan 31, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [4dcc88b215](https://linux-hardware.org/?probe=4dcc88b215) | Jan 31, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [2df9f60f2e](https://linux-hardware.org/?probe=2df9f60f2e) | Jan 31, 2023 |
| Acer          | Predator PH315-52           | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [a64ae29757](https://linux-hardware.org/?probe=a64ae29757) | Jan 31, 2023 |
| Samsung       | 550XCJ/550XCR               | [75fad3daf3](https://linux-hardware.org/?probe=75fad3daf3) | Jan 31, 2023 |
| Dell          | XPS 15 9570                 | [ee60c1c921](https://linux-hardware.org/?probe=ee60c1c921) | Jan 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [87904d9d06](https://linux-hardware.org/?probe=87904d9d06) | Jan 31, 2023 |
| Dell          | Vostro 15 3515              | [357d14774f](https://linux-hardware.org/?probe=357d14774f) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Latitude 7480               | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ecef01472](https://linux-hardware.org/?probe=1ecef01472) | Jan 30, 2023 |
| HP            | Pavilion 15                 | [6ceccb3d73](https://linux-hardware.org/?probe=6ceccb3d73) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| Dell          | XPS 15 9570                 | [1d06f2715a](https://linux-hardware.org/?probe=1d06f2715a) | Jan 30, 2023 |
| Dell          | Vostro 7620                 | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| HP            | Laptop 14-cm0xxx            | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Acer          | Aspire V5-573G              | [e253d5b49b](https://linux-hardware.org/?probe=e253d5b49b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| TECNO         | MEGABOOK T1                 | [db0e6c89b4](https://linux-hardware.org/?probe=db0e6c89b4) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| Dell          | XPS 13 7390                 | [60c03ee1f7](https://linux-hardware.org/?probe=60c03ee1f7) | Jan 29, 2023 |
| HP            | EliteBook 840 G1            | [30549ebd3a](https://linux-hardware.org/?probe=30549ebd3a) | Jan 28, 2023 |
| HP            | Laptop 15-da2xxx            | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ed1ce46901](https://linux-hardware.org/?probe=ed1ce46901) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [844e4e4b2a](https://linux-hardware.org/?probe=844e4e4b2a) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ab3f84f96b](https://linux-hardware.org/?probe=ab3f84f96b) | Jan 28, 2023 |
| Apple         | MacBookPro11,4              | [8a5423443a](https://linux-hardware.org/?probe=8a5423443a) | Jan 28, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [7e6cf30d81](https://linux-hardware.org/?probe=7e6cf30d81) | Jan 28, 2023 |
| Timi          | A35S                        | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad T450s 20BWS23W0... | [41c82dbadb](https://linux-hardware.org/?probe=41c82dbadb) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a69331d2ea](https://linux-hardware.org/?probe=a69331d2ea) | Jan 27, 2023 |
| Acer          | Swift SF314-511             | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| HONOR         | BMH-WCX9                    | [882bb3b505](https://linux-hardware.org/?probe=882bb3b505) | Jan 27, 2023 |
| MECHREVO      | Code10-7CC6U                | [86e769b2a3](https://linux-hardware.org/?probe=86e769b2a3) | Jan 27, 2023 |
| Dell          | Precision 3550              | [4c42615cef](https://linux-hardware.org/?probe=4c42615cef) | Jan 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [00e21c8359](https://linux-hardware.org/?probe=00e21c8359) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | [a2ad3f4eb3](https://linux-hardware.org/?probe=a2ad3f4eb3) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | [3921b100b4](https://linux-hardware.org/?probe=3921b100b4) | Jan 27, 2023 |
| ASUSTek       | X550VX                      | [37d2157b37](https://linux-hardware.org/?probe=37d2157b37) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [9dfc820ceb](https://linux-hardware.org/?probe=9dfc820ceb) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [0168a5cae2](https://linux-hardware.org/?probe=0168a5cae2) | Jan 26, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4024f7c3bd](https://linux-hardware.org/?probe=4024f7c3bd) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [a1dfc58700](https://linux-hardware.org/?probe=a1dfc58700) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Multilaser    | PC150                       | [1c4ace00d1](https://linux-hardware.org/?probe=1c4ace00d1) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [8725d530e5](https://linux-hardware.org/?probe=8725d530e5) | Jan 26, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ea142e4848](https://linux-hardware.org/?probe=ea142e4848) | Jan 25, 2023 |
| HP            | EliteBook 2540p             | [f03240c746](https://linux-hardware.org/?probe=f03240c746) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [af63cfc79a](https://linux-hardware.org/?probe=af63cfc79a) | Jan 25, 2023 |
| Clevo         | M815P                       | [cfc5f6689f](https://linux-hardware.org/?probe=cfc5f6689f) | Jan 25, 2023 |
| MSI           | GL63 8RC                    | [138e8de541](https://linux-hardware.org/?probe=138e8de541) | Jan 25, 2023 |
| Acer          | Aspire A315-59              | [33292253d0](https://linux-hardware.org/?probe=33292253d0) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| Dynabook      | TECRA A50-J                 | [2f24f18672](https://linux-hardware.org/?probe=2f24f18672) | Jan 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [993ba3e73b](https://linux-hardware.org/?probe=993ba3e73b) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [aa6488b6b8](https://linux-hardware.org/?probe=aa6488b6b8) | Jan 25, 2023 |
| Fujitsu Si... | AMILO Notebook Xa 3530      | [e8384494a3](https://linux-hardware.org/?probe=e8384494a3) | Jan 25, 2023 |
| Dell          | Inspiron 5402               | [d8df4aafe8](https://linux-hardware.org/?probe=d8df4aafe8) | Jan 25, 2023 |
| Dell          | Inspiron 5468               | [3e59c1f38b](https://linux-hardware.org/?probe=3e59c1f38b) | Jan 25, 2023 |
| Acer          | Nitro AN515-42              | [cb02367642](https://linux-hardware.org/?probe=cb02367642) | Jan 25, 2023 |
| Dell          | Latitude 5420               | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Dell          | Latitude 5520               | [662284824b](https://linux-hardware.org/?probe=662284824b) | Jan 24, 2023 |
| HP            | ProBook 6570b               | [841250ba59](https://linux-hardware.org/?probe=841250ba59) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [3fb25133ec](https://linux-hardware.org/?probe=3fb25133ec) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Google        | Treeya                      | [27a381272a](https://linux-hardware.org/?probe=27a381272a) | Jan 24, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a227de29c5](https://linux-hardware.org/?probe=a227de29c5) | Jan 24, 2023 |
| Dell          | Precision 3551              | [1338d3df20](https://linux-hardware.org/?probe=1338d3df20) | Jan 23, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [335275777a](https://linux-hardware.org/?probe=335275777a) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [e40bb2f01f](https://linux-hardware.org/?probe=e40bb2f01f) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [31789ae630](https://linux-hardware.org/?probe=31789ae630) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [091effd2ac](https://linux-hardware.org/?probe=091effd2ac) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | [0a597ba033](https://linux-hardware.org/?probe=0a597ba033) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | [90884b19a9](https://linux-hardware.org/?probe=90884b19a9) | Jan 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS12Q3M     | [e46b5a8b46](https://linux-hardware.org/?probe=e46b5a8b46) | Jan 23, 2023 |
| Dell          | Latitude E6500              | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | [689fe06d4d](https://linux-hardware.org/?probe=689fe06d4d) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | [92690b43cd](https://linux-hardware.org/?probe=92690b43cd) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d03b7c0a68](https://linux-hardware.org/?probe=d03b7c0a68) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [07005e3e32](https://linux-hardware.org/?probe=07005e3e32) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [d999192dbf](https://linux-hardware.org/?probe=d999192dbf) | Jan 22, 2023 |
| HP            | EliteBook 820 G3            | [3edd4ab0dc](https://linux-hardware.org/?probe=3edd4ab0dc) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [0aa98390a7](https://linux-hardware.org/?probe=0aa98390a7) | Jan 21, 2023 |
| Acer          | Predator G9-591             | [0544a1b07c](https://linux-hardware.org/?probe=0544a1b07c) | Jan 21, 2023 |
| Dell          | XPS 9315                    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [e8a0c0066b](https://linux-hardware.org/?probe=e8a0c0066b) | Jan 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [adeb24c41e](https://linux-hardware.org/?probe=adeb24c41e) | Jan 21, 2023 |
| Dell          | G5 5587                     | [96ca22c550](https://linux-hardware.org/?probe=96ca22c550) | Jan 21, 2023 |
| Dell          | G5 5587                     | [a070a8ba69](https://linux-hardware.org/?probe=a070a8ba69) | Jan 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Dell          | Venue 8 Pro 5830            | [4f815d5b4f](https://linux-hardware.org/?probe=4f815d5b4f) | Jan 20, 2023 |
| Acer          | Aspire A315-42G             | [ed4c536efa](https://linux-hardware.org/?probe=ed4c536efa) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| Acer          | Aspire A515-45              | [9d5faff505](https://linux-hardware.org/?probe=9d5faff505) | Jan 20, 2023 |
| MSI           | GS66 Stealth 10UE           | [d5a2a6aaa8](https://linux-hardware.org/?probe=d5a2a6aaa8) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | [15c0522754](https://linux-hardware.org/?probe=15c0522754) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | [e81652a68c](https://linux-hardware.org/?probe=e81652a68c) | Jan 19, 2023 |
| Dell          | Precision 3551              | [4ff5a0ab8d](https://linux-hardware.org/?probe=4ff5a0ab8d) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [0f079e1dc7](https://linux-hardware.org/?probe=0f079e1dc7) | Jan 19, 2023 |
| Acer          | Aspire A315-23              | [90049e4bb7](https://linux-hardware.org/?probe=90049e4bb7) | Jan 19, 2023 |
| Acer          | Nitro AN515-42              | [d6a24ede85](https://linux-hardware.org/?probe=d6a24ede85) | Jan 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [6a47296f0c](https://linux-hardware.org/?probe=6a47296f0c) | Jan 19, 2023 |
| Dell          | Latitude 3410               | [187aebc2cd](https://linux-hardware.org/?probe=187aebc2cd) | Jan 19, 2023 |
| Intel Clie... | LAPRC510                    | [6d570a1aee](https://linux-hardware.org/?probe=6d570a1aee) | Jan 19, 2023 |
| ASUSTek       | X455LF                      | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| HP            | Victus by Gaming Laptop ... | [533d99e2f1](https://linux-hardware.org/?probe=533d99e2f1) | Jan 18, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [d27ca45841](https://linux-hardware.org/?probe=d27ca45841) | Jan 18, 2023 |
| Dell          | Precision 3561              | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Acer          | Swift SFX14-41G             | [1b916fe30d](https://linux-hardware.org/?probe=1b916fe30d) | Jan 18, 2023 |
| Lenovo        | Yoga 500-14IHW 80N5         | [e233e8d6d2](https://linux-hardware.org/?probe=e233e8d6d2) | Jan 18, 2023 |
| Acer          | Nitro AN515-54              | [4a997fa99d](https://linux-hardware.org/?probe=4a997fa99d) | Jan 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| HP            | Laptop 17-ca0xxx            | [a8fbe01fc5](https://linux-hardware.org/?probe=a8fbe01fc5) | Jan 17, 2023 |
| Acer          | Aspire A315-59              | [469c40ec75](https://linux-hardware.org/?probe=469c40ec75) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [681de2b0c1](https://linux-hardware.org/?probe=681de2b0c1) | Jan 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b36d7e8eb](https://linux-hardware.org/?probe=7b36d7e8eb) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [f1ee502754](https://linux-hardware.org/?probe=f1ee502754) | Jan 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0d91852ebf](https://linux-hardware.org/?probe=0d91852ebf) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| Acer          | Aspire AV14-51              | [596219796d](https://linux-hardware.org/?probe=596219796d) | Jan 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b39c4fc9b7](https://linux-hardware.org/?probe=b39c4fc9b7) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [1c81e8c322](https://linux-hardware.org/?probe=1c81e8c322) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| PC Special... | Recoil II RTX               | [33850c8810](https://linux-hardware.org/?probe=33850c8810) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [b53dd87f87](https://linux-hardware.org/?probe=b53dd87f87) | Jan 16, 2023 |
| Schenker      | XMG CORE 15 (M22)           | [6c2b631f12](https://linux-hardware.org/?probe=6c2b631f12) | Jan 16, 2023 |
| HP            | 15                          | [ae082994e2](https://linux-hardware.org/?probe=ae082994e2) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | [1de96d005a](https://linux-hardware.org/?probe=1de96d005a) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | [f0eab1c81a](https://linux-hardware.org/?probe=f0eab1c81a) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e1aa5d3186](https://linux-hardware.org/?probe=e1aa5d3186) | Jan 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1a51848ffb](https://linux-hardware.org/?probe=1a51848ffb) | Jan 16, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [b36eb94e80](https://linux-hardware.org/?probe=b36eb94e80) | Jan 16, 2023 |
| HP            | 255 G6 Notebook PC          | [4d2e9f3ee4](https://linux-hardware.org/?probe=4d2e9f3ee4) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9ac2f0ab83](https://linux-hardware.org/?probe=9ac2f0ab83) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [4850c49a4a](https://linux-hardware.org/?probe=4850c49a4a) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [448ae92dc8](https://linux-hardware.org/?probe=448ae92dc8) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [972e3e026a](https://linux-hardware.org/?probe=972e3e026a) | Jan 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [57d99b139f](https://linux-hardware.org/?probe=57d99b139f) | Jan 15, 2023 |
| Acer          | Aspire A515-43              | [cefbe7ee6e](https://linux-hardware.org/?probe=cefbe7ee6e) | Jan 15, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fcc6481e2a](https://linux-hardware.org/?probe=fcc6481e2a) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | [ebe90b5052](https://linux-hardware.org/?probe=ebe90b5052) | Jan 15, 2023 |
| Dell          | Inspiron N5110              | [20625ce99d](https://linux-hardware.org/?probe=20625ce99d) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [fe5c9c2425](https://linux-hardware.org/?probe=fe5c9c2425) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [649546bc61](https://linux-hardware.org/?probe=649546bc61) | Jan 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [86fff559f5](https://linux-hardware.org/?probe=86fff559f5) | Jan 14, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | [bcbf941284](https://linux-hardware.org/?probe=bcbf941284) | Jan 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [efffe2d61b](https://linux-hardware.org/?probe=efffe2d61b) | Jan 14, 2023 |
| MSI           | PS63 Modern 8RC             | [e55e0d9d0a](https://linux-hardware.org/?probe=e55e0d9d0a) | Jan 14, 2023 |
| HP            | ZBook 15 G4                 | [3325b8ab60](https://linux-hardware.org/?probe=3325b8ab60) | Jan 14, 2023 |
| System76      | Oryx Pro                    | [f706b667bb](https://linux-hardware.org/?probe=f706b667bb) | Jan 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [5047da7461](https://linux-hardware.org/?probe=5047da7461) | Jan 14, 2023 |
| Acer          | Swift SF314-43              | [e292f699eb](https://linux-hardware.org/?probe=e292f699eb) | Jan 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9096450d56](https://linux-hardware.org/?probe=9096450d56) | Jan 14, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| Dell          | Latitude 7430               | [9caa5939ef](https://linux-hardware.org/?probe=9caa5939ef) | Jan 13, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [61c432b134](https://linux-hardware.org/?probe=61c432b134) | Jan 13, 2023 |
| Acer          | Nitro AN515-44              | [b2c96e31d9](https://linux-hardware.org/?probe=b2c96e31d9) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [810b2daeef](https://linux-hardware.org/?probe=810b2daeef) | Jan 13, 2023 |
| Toshiba       | Satellite L855D             | [0606d04520](https://linux-hardware.org/?probe=0606d04520) | Jan 13, 2023 |
| Dell          | Inspiron 5721               | [b9435f9f7d](https://linux-hardware.org/?probe=b9435f9f7d) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [64c403ce6d](https://linux-hardware.org/?probe=64c403ce6d) | Jan 13, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | [28d821da5f](https://linux-hardware.org/?probe=28d821da5f) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f9d244586a](https://linux-hardware.org/?probe=f9d244586a) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [033a92981f](https://linux-hardware.org/?probe=033a92981f) | Jan 13, 2023 |
| Acer          | Predator PT515-51           | [150f12dceb](https://linux-hardware.org/?probe=150f12dceb) | Jan 12, 2023 |
| Dell          | G15 5520                    | [1aeaf74f9a](https://linux-hardware.org/?probe=1aeaf74f9a) | Jan 12, 2023 |
| HP            | ProBook 450 G6              | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Nitro AN517-42              | [c8440739f9](https://linux-hardware.org/?probe=c8440739f9) | Jan 12, 2023 |
| Dell          | Latitude E5550              | [0b14eb18d9](https://linux-hardware.org/?probe=0b14eb18d9) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2349W1C       | [1f310a8a2e](https://linux-hardware.org/?probe=1f310a8a2e) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [fad743f278](https://linux-hardware.org/?probe=fad743f278) | Jan 12, 2023 |
| HUAWEI        | KLVL-WXXW                   | [1270cfda4e](https://linux-hardware.org/?probe=1270cfda4e) | Jan 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8c1eb7fc02](https://linux-hardware.org/?probe=8c1eb7fc02) | Jan 11, 2023 |
| Dell          | Latitude E5550              | [5e76d378f9](https://linux-hardware.org/?probe=5e76d378f9) | Jan 11, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ec0f3564ed](https://linux-hardware.org/?probe=ec0f3564ed) | Jan 11, 2023 |
| Acer          | Aspire A315-59              | [a436e3e89f](https://linux-hardware.org/?probe=a436e3e89f) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c79ad1fc10](https://linux-hardware.org/?probe=c79ad1fc10) | Jan 11, 2023 |
| Acer          | Predator G9-591             | [aa9794813e](https://linux-hardware.org/?probe=aa9794813e) | Jan 11, 2023 |
| Dell          | Latitude E7440              | [bfdc9dfc63](https://linux-hardware.org/?probe=bfdc9dfc63) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| MSI           | Modern 14 B4MW              | [815ee96451](https://linux-hardware.org/?probe=815ee96451) | Jan 11, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | [790736a10e](https://linux-hardware.org/?probe=790736a10e) | Jan 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [fdb726b276](https://linux-hardware.org/?probe=fdb726b276) | Jan 11, 2023 |
| Infinix       | INBOOK X2                   | [11aac46bdc](https://linux-hardware.org/?probe=11aac46bdc) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | [dc3e0fffe7](https://linux-hardware.org/?probe=dc3e0fffe7) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | [53d6bec0e8](https://linux-hardware.org/?probe=53d6bec0e8) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [51d6d75e64](https://linux-hardware.org/?probe=51d6d75e64) | Jan 10, 2023 |
| ASUSTek       | FX503VD                     | [c3a958527e](https://linux-hardware.org/?probe=c3a958527e) | Jan 10, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [37b5b1648e](https://linux-hardware.org/?probe=37b5b1648e) | Jan 10, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [e16ef8937b](https://linux-hardware.org/?probe=e16ef8937b) | Jan 09, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [ef83299ad4](https://linux-hardware.org/?probe=ef83299ad4) | Jan 09, 2023 |
| Chuwi         | GemiBook                    | [918dc5f283](https://linux-hardware.org/?probe=918dc5f283) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| HP            | EliteBook 850 G4            | [e6cb9446f5](https://linux-hardware.org/?probe=e6cb9446f5) | Jan 09, 2023 |
| HP            | Laptop 15-da1xxx            | [2fa89881b4](https://linux-hardware.org/?probe=2fa89881b4) | Jan 09, 2023 |
| Dell          | XPS 15 9520                 | [2e13f150e6](https://linux-hardware.org/?probe=2e13f150e6) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6e756926b8](https://linux-hardware.org/?probe=6e756926b8) | Jan 09, 2023 |
| Apple         | MacBookPro11,1              | [92a4be502c](https://linux-hardware.org/?probe=92a4be502c) | Jan 09, 2023 |
| Acer          | Iconia W700                 | [bcfec36896](https://linux-hardware.org/?probe=bcfec36896) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [8c76c72880](https://linux-hardware.org/?probe=8c76c72880) | Jan 08, 2023 |
| HP            | ProBook 6465b               | [336f10e70b](https://linux-hardware.org/?probe=336f10e70b) | Jan 08, 2023 |
| ASUSTek       | X541UVK                     | [50e9caee7f](https://linux-hardware.org/?probe=50e9caee7f) | Jan 08, 2023 |
| Lenovo        | V330-15IKB 81AX             | [1ca4c751d8](https://linux-hardware.org/?probe=1ca4c751d8) | Jan 08, 2023 |
| Framework     | Laptop                      | [0c13e3ab8d](https://linux-hardware.org/?probe=0c13e3ab8d) | Jan 08, 2023 |
| Acer          | Aspire A315-41              | [b4ed141fd3](https://linux-hardware.org/?probe=b4ed141fd3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [d2e10cee5b](https://linux-hardware.org/?probe=d2e10cee5b) | Jan 08, 2023 |
| Dell          | Latitude 3450               | [e4e8bee1cb](https://linux-hardware.org/?probe=e4e8bee1cb) | Jan 08, 2023 |
| HP            | EliteBook 745 G5            | [b732d98167](https://linux-hardware.org/?probe=b732d98167) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | [206359e4ad](https://linux-hardware.org/?probe=206359e4ad) | Jan 08, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [f75fea559f](https://linux-hardware.org/?probe=f75fea559f) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | [eed9db8255](https://linux-hardware.org/?probe=eed9db8255) | Jan 08, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [6290949f56](https://linux-hardware.org/?probe=6290949f56) | Jan 08, 2023 |
| Dell          | Vostro 15-3568              | [a6c731c83b](https://linux-hardware.org/?probe=a6c731c83b) | Jan 08, 2023 |
| Dell          | Inspiron 5567               | [a43647cad6](https://linux-hardware.org/?probe=a43647cad6) | Jan 08, 2023 |
| Acer          | Predator PT515-51           | [a33d9c5a74](https://linux-hardware.org/?probe=a33d9c5a74) | Jan 07, 2023 |
| HP            | EliteBook 850 G6            | [595e6fa89a](https://linux-hardware.org/?probe=595e6fa89a) | Jan 07, 2023 |
| Dell          | XPS 15 9510                 | [f0a688060c](https://linux-hardware.org/?probe=f0a688060c) | Jan 07, 2023 |
| Lenovo        | ThinkPad T530 2392CTO       | [8c1cf48875](https://linux-hardware.org/?probe=8c1cf48875) | Jan 07, 2023 |
| Framework     | Laptop                      | [cfabfdec3c](https://linux-hardware.org/?probe=cfabfdec3c) | Jan 07, 2023 |
| System76      | Lemur Pro                   | [36156d9aa7](https://linux-hardware.org/?probe=36156d9aa7) | Jan 07, 2023 |
| Dell          | Inspiron 13 5320            | [0007a36030](https://linux-hardware.org/?probe=0007a36030) | Jan 07, 2023 |
| HP            | EliteBook 840 G3            | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| HP            | ZBook Studio G5             | [dfd35ce9ca](https://linux-hardware.org/?probe=dfd35ce9ca) | Jan 07, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [bf4c8770e7](https://linux-hardware.org/?probe=bf4c8770e7) | Jan 07, 2023 |
| Dell          | Inspiron 7577               | [ff95fa094b](https://linux-hardware.org/?probe=ff95fa094b) | Jan 06, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1fc8d104f7](https://linux-hardware.org/?probe=1fc8d104f7) | Jan 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [0a6589c07d](https://linux-hardware.org/?probe=0a6589c07d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ab29e81efd](https://linux-hardware.org/?probe=ab29e81efd) | Jan 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [684653e302](https://linux-hardware.org/?probe=684653e302) | Jan 06, 2023 |
| Acer          | Aspire A515-47              | [896288776d](https://linux-hardware.org/?probe=896288776d) | Jan 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9946b25232](https://linux-hardware.org/?probe=9946b25232) | Jan 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fd5120fea6](https://linux-hardware.org/?probe=fd5120fea6) | Jan 06, 2023 |
| Lenovo        | ThinkPad T430 2349KB4       | [4546ecbe85](https://linux-hardware.org/?probe=4546ecbe85) | Jan 06, 2023 |
| Chuwi         | HeroBook Air                | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| Dell          | XPS 15 9520                 | [ec6743fa1b](https://linux-hardware.org/?probe=ec6743fa1b) | Jan 06, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [c84d3b6b03](https://linux-hardware.org/?probe=c84d3b6b03) | Jan 06, 2023 |
| Dell          | G15 5525                    | [2c61cbc942](https://linux-hardware.org/?probe=2c61cbc942) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cddb2a7b81](https://linux-hardware.org/?probe=cddb2a7b81) | Jan 06, 2023 |
| Lenovo        | Z50-75 80EC                 | [7fe70dc4c8](https://linux-hardware.org/?probe=7fe70dc4c8) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [c47405aaf4](https://linux-hardware.org/?probe=c47405aaf4) | Jan 05, 2023 |
| Lenovo        | ThinkPad X220 4290KJ6       | [8296e61afd](https://linux-hardware.org/?probe=8296e61afd) | Jan 05, 2023 |
| Acer          | Predator PT515-51           | [77651b16db](https://linux-hardware.org/?probe=77651b16db) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | [28af5637ef](https://linux-hardware.org/?probe=28af5637ef) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | [4605f322cb](https://linux-hardware.org/?probe=4605f322cb) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a2ec6616aa](https://linux-hardware.org/?probe=a2ec6616aa) | Jan 05, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| MSI           | Modern 14 B4MW              | [b7855a84cf](https://linux-hardware.org/?probe=b7855a84cf) | Jan 05, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [343d0f4c48](https://linux-hardware.org/?probe=343d0f4c48) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | [39f45e87d1](https://linux-hardware.org/?probe=39f45e87d1) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | [2f4bb5b17d](https://linux-hardware.org/?probe=2f4bb5b17d) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [272d23ec5d](https://linux-hardware.org/?probe=272d23ec5d) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [76f2ef98b9](https://linux-hardware.org/?probe=76f2ef98b9) | Jan 04, 2023 |
| Acer          | Swift SF314-43              | [50d8f0c1cb](https://linux-hardware.org/?probe=50d8f0c1cb) | Jan 04, 2023 |
| HP            | Notebook                    | [679c0bfbe8](https://linux-hardware.org/?probe=679c0bfbe8) | Jan 04, 2023 |
| HP            | EliteBook 845 14 inch G9... | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| HP            | ZBook 15 G3                 | [6a38362bbe](https://linux-hardware.org/?probe=6a38362bbe) | Jan 04, 2023 |
| Unknown       | Unknown                     | [b363093f89](https://linux-hardware.org/?probe=b363093f89) | Jan 04, 2023 |
| Acer          | Nitro AN515-45              | [5741654cdc](https://linux-hardware.org/?probe=5741654cdc) | Jan 04, 2023 |
| MSI           | Modern 14 B11MOU            | [036ae164e8](https://linux-hardware.org/?probe=036ae164e8) | Jan 04, 2023 |
| Clevo         | M815P                       | [7f1503c5e6](https://linux-hardware.org/?probe=7f1503c5e6) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | [d788f444ff](https://linux-hardware.org/?probe=d788f444ff) | Jan 03, 2023 |
| HP            | ProBook 6570b               | [875054c6d7](https://linux-hardware.org/?probe=875054c6d7) | Jan 03, 2023 |
| ASUSTek       | X453MA                      | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [40af3a30ca](https://linux-hardware.org/?probe=40af3a30ca) | Jan 03, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [c621679405](https://linux-hardware.org/?probe=c621679405) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Toshiba       | Satellite C50-A             | [9b02393248](https://linux-hardware.org/?probe=9b02393248) | Jan 02, 2023 |
| HP            | Notebook                    | [530e6cfeb9](https://linux-hardware.org/?probe=530e6cfeb9) | Jan 02, 2023 |
| Clevo         | M815P                       | [034cecc238](https://linux-hardware.org/?probe=034cecc238) | Jan 02, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [daeb060f32](https://linux-hardware.org/?probe=daeb060f32) | Jan 02, 2023 |
| Acer          | Aspire A315-31              | [4a79c65764](https://linux-hardware.org/?probe=4a79c65764) | Jan 02, 2023 |
| ASUSTek       | X756UXK                     | [f0bc632c50](https://linux-hardware.org/?probe=f0bc632c50) | Jan 02, 2023 |
| Dell          | Latitude 7410               | [acb8ce902e](https://linux-hardware.org/?probe=acb8ce902e) | Jan 01, 2023 |
| Acer          | Aspire A315-59              | [f84116ec07](https://linux-hardware.org/?probe=f84116ec07) | Jan 01, 2023 |
| Fujitsu       | LIFEBOOK U749               | [c09072c09f](https://linux-hardware.org/?probe=c09072c09f) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [f438866c0d](https://linux-hardware.org/?probe=f438866c0d) | Jan 01, 2023 |
| Lenovo        | ThinkPad X270 20K60018GE    | [a92939c1f5](https://linux-hardware.org/?probe=a92939c1f5) | Jan 01, 2023 |
| Lenovo        | ThinkPad X390 20Q00051GE    | [5b3d1b750d](https://linux-hardware.org/?probe=5b3d1b750d) | Dec 31, 2022 |
| Valve         | Jupiter                     | [c0fb48bccb](https://linux-hardware.org/?probe=c0fb48bccb) | Dec 31, 2022 |
| System76      | Oryx Pro                    | [0d65e57758](https://linux-hardware.org/?probe=0d65e57758) | Dec 31, 2022 |
| Lenovo        | ThinkPad X390 20Q00051GE    | [775096be09](https://linux-hardware.org/?probe=775096be09) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [322cf5484d](https://linux-hardware.org/?probe=322cf5484d) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5fbe1632b0](https://linux-hardware.org/?probe=5fbe1632b0) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5a479fed95](https://linux-hardware.org/?probe=5a479fed95) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [591d985e85](https://linux-hardware.org/?probe=591d985e85) | Dec 31, 2022 |
| HP            | Pavilion dv6700             | [4b3b106bee](https://linux-hardware.org/?probe=4b3b106bee) | Dec 30, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [f7ed4a6609](https://linux-hardware.org/?probe=f7ed4a6609) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | [d2cd50a2a6](https://linux-hardware.org/?probe=d2cd50a2a6) | Dec 30, 2022 |
| Timi          | A35S                        | [c62c9ae956](https://linux-hardware.org/?probe=c62c9ae956) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | [ae7d821823](https://linux-hardware.org/?probe=ae7d821823) | Dec 30, 2022 |
| Dell          | XPS 15 9520                 | [19b4bfd852](https://linux-hardware.org/?probe=19b4bfd852) | Dec 30, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [68b3b51892](https://linux-hardware.org/?probe=68b3b51892) | Dec 30, 2022 |
| MSI           | GP72MVR 7RFX                | [cefedef93c](https://linux-hardware.org/?probe=cefedef93c) | Dec 30, 2022 |
| MSI           | Stealth GS66 12UGS          | [da812c8fa2](https://linux-hardware.org/?probe=da812c8fa2) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [770c5eee84](https://linux-hardware.org/?probe=770c5eee84) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| Dell          | Inspiron N4050              | [b34f09894d](https://linux-hardware.org/?probe=b34f09894d) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ed5315b768](https://linux-hardware.org/?probe=ed5315b768) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [3c627bc707](https://linux-hardware.org/?probe=3c627bc707) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [b246257695](https://linux-hardware.org/?probe=b246257695) | Dec 29, 2022 |
| HP            | Stream Notebook PC 13       | [2154a332b0](https://linux-hardware.org/?probe=2154a332b0) | Dec 29, 2022 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6c67e1435e](https://linux-hardware.org/?probe=6c67e1435e) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | [51bb19bbf2](https://linux-hardware.org/?probe=51bb19bbf2) | Dec 29, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [74f8dcfbb4](https://linux-hardware.org/?probe=74f8dcfbb4) | Dec 29, 2022 |
| Schenker      | VISION 16 Pro (L22)         | [bbd6e1daf5](https://linux-hardware.org/?probe=bbd6e1daf5) | Dec 29, 2022 |
| Acer          | Predator PH315-53           | [d5d0e740c1](https://linux-hardware.org/?probe=d5d0e740c1) | Dec 29, 2022 |
| Schenker      | VISION 16 Pro (L22)         | [2412713729](https://linux-hardware.org/?probe=2412713729) | Dec 29, 2022 |
| Dell          | G5 5590                     | [58bd69f40b](https://linux-hardware.org/?probe=58bd69f40b) | Dec 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [8901206dd0](https://linux-hardware.org/?probe=8901206dd0) | Dec 28, 2022 |
| Dell          | Inspiron 5458               | [269d455191](https://linux-hardware.org/?probe=269d455191) | Dec 28, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [e23c23e61f](https://linux-hardware.org/?probe=e23c23e61f) | Dec 28, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [5c4856e5c8](https://linux-hardware.org/?probe=5c4856e5c8) | Dec 28, 2022 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | [0852995abb](https://linux-hardware.org/?probe=0852995abb) | Dec 28, 2022 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [e12c24fd74](https://linux-hardware.org/?probe=e12c24fd74) | Dec 28, 2022 |
| Google        | Voxel rev3                  | [430244f188](https://linux-hardware.org/?probe=430244f188) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [6240bc3677](https://linux-hardware.org/?probe=6240bc3677) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [f5689c6edc](https://linux-hardware.org/?probe=f5689c6edc) | Dec 28, 2022 |
| Dell          | Inspiron 16 5625            | [dbc2d2fc6f](https://linux-hardware.org/?probe=dbc2d2fc6f) | Dec 28, 2022 |
| HUAWEI        | HLYL-WXX9                   | [790b3dcdde](https://linux-hardware.org/?probe=790b3dcdde) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| HP            | G62                         | [05ad917600](https://linux-hardware.org/?probe=05ad917600) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| HUAWEI        | BOM-WXX9                    | [826a683b58](https://linux-hardware.org/?probe=826a683b58) | Dec 28, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [00a92c3818](https://linux-hardware.org/?probe=00a92c3818) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| MSI           | GL63 8RC                    | [0b973e252f](https://linux-hardware.org/?probe=0b973e252f) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Dell          | Inspiron 15 3525            | [64a70af984](https://linux-hardware.org/?probe=64a70af984) | Dec 27, 2022 |
| HP            | Laptop 15-dy5xxx            | [d7daff3ed1](https://linux-hardware.org/?probe=d7daff3ed1) | Dec 27, 2022 |
| Timi          | RedmiBook 15                | [cf38b14bc5](https://linux-hardware.org/?probe=cf38b14bc5) | Dec 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [e41c8ca4ee](https://linux-hardware.org/?probe=e41c8ca4ee) | Dec 27, 2022 |
| Dell          | Latitude E7440              | [f2c052dde9](https://linux-hardware.org/?probe=f2c052dde9) | Dec 27, 2022 |
| Dell          | Inspiron 15-3567            | [2f5381fa26](https://linux-hardware.org/?probe=2f5381fa26) | Dec 26, 2022 |
| HP            | ProBook 450 G7              | [dfedb566ff](https://linux-hardware.org/?probe=dfedb566ff) | Dec 26, 2022 |
| Lenovo        | G510 20238                  | [812d6eb07e](https://linux-hardware.org/?probe=812d6eb07e) | Dec 26, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c7babe827f](https://linux-hardware.org/?probe=c7babe827f) | Dec 26, 2022 |
| Dell          | Inspiron 3521               | [9d544fbcd4](https://linux-hardware.org/?probe=9d544fbcd4) | Dec 26, 2022 |
| Dell          | Inspiron 5458               | [4e393c7334](https://linux-hardware.org/?probe=4e393c7334) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [ce352bf1b1](https://linux-hardware.org/?probe=ce352bf1b1) | Dec 26, 2022 |
| Acer          | Aspire A515-51              | [e763dd5dfe](https://linux-hardware.org/?probe=e763dd5dfe) | Dec 26, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Dell          | Inspiron 5759               | [d1938219e9](https://linux-hardware.org/?probe=d1938219e9) | Dec 26, 2022 |
| Dell          | Latitude 5580               | [72c0e42aeb](https://linux-hardware.org/?probe=72c0e42aeb) | Dec 26, 2022 |
| Acer          | Aspire A315-59              | [6625ce058f](https://linux-hardware.org/?probe=6625ce058f) | Dec 25, 2022 |
| HP            | ProBook 6465b               | [d0f5218f72](https://linux-hardware.org/?probe=d0f5218f72) | Dec 25, 2022 |
| ASUSTek       | K55VD                       | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| MSI           | Modern 14 B4MW              | [e9dbd838ec](https://linux-hardware.org/?probe=e9dbd838ec) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| Dell          | XPS 15 9510                 | [6c809c224c](https://linux-hardware.org/?probe=6c809c224c) | Dec 24, 2022 |
| Dell          | Latitude 5510               | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| HUAWEI        | CREM-WXX9                   | [a48a2f6362](https://linux-hardware.org/?probe=a48a2f6362) | Dec 24, 2022 |
| HP            | Pavilion g6                 | [71d7947da6](https://linux-hardware.org/?probe=71d7947da6) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0AY0... | [28e67f37bc](https://linux-hardware.org/?probe=28e67f37bc) | Dec 24, 2022 |
| Acer          | Aspire A514-54              | [ea57f4aa3a](https://linux-hardware.org/?probe=ea57f4aa3a) | Dec 24, 2022 |
| Dell          | Latitude 5420               | [201e81d0ed](https://linux-hardware.org/?probe=201e81d0ed) | Dec 23, 2022 |
| Dell          | Latitude 5420               | [9fd9875465](https://linux-hardware.org/?probe=9fd9875465) | Dec 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f114731a78](https://linux-hardware.org/?probe=f114731a78) | Dec 23, 2022 |
| ASUSTek       | X750JN                      | [d933b1a80b](https://linux-hardware.org/?probe=d933b1a80b) | Dec 23, 2022 |
| Jooyon Tec... | J6BF                        | [dabe200abe](https://linux-hardware.org/?probe=dabe200abe) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [756390ae0c](https://linux-hardware.org/?probe=756390ae0c) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [c2dd56664a](https://linux-hardware.org/?probe=c2dd56664a) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [627186e9e8](https://linux-hardware.org/?probe=627186e9e8) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [77e30fee83](https://linux-hardware.org/?probe=77e30fee83) | Dec 23, 2022 |
| Acer          | Aspire A515-57G             | [a208b5598e](https://linux-hardware.org/?probe=a208b5598e) | Dec 22, 2022 |
| Acer          | Aspire A515-57G             | [cccd3d01d7](https://linux-hardware.org/?probe=cccd3d01d7) | Dec 22, 2022 |
| Acer          | Aspire V5-571               | [b4de144f3e](https://linux-hardware.org/?probe=b4de144f3e) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [677cb5b0b3](https://linux-hardware.org/?probe=677cb5b0b3) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2b25ab8790](https://linux-hardware.org/?probe=2b25ab8790) | Dec 22, 2022 |
| GPD           | P3 MAX                      | [9069ed5580](https://linux-hardware.org/?probe=9069ed5580) | Dec 22, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [6db25ba5ca](https://linux-hardware.org/?probe=6db25ba5ca) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [fb60e7984c](https://linux-hardware.org/?probe=fb60e7984c) | Dec 21, 2022 |
| ASUSTek       | X450CA                      | [5b793f14ff](https://linux-hardware.org/?probe=5b793f14ff) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| Apple         | MacBookPro9,2               | [5bc62fc208](https://linux-hardware.org/?probe=5bc62fc208) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HP            | Stream Notebook PC 13       | [9c88ffc394](https://linux-hardware.org/?probe=9c88ffc394) | Dec 21, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [77c9275988](https://linux-hardware.org/?probe=77c9275988) | Dec 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [ec20f98178](https://linux-hardware.org/?probe=ec20f98178) | Dec 21, 2022 |
| Dell          | Latitude 5520               | [203652b6dd](https://linux-hardware.org/?probe=203652b6dd) | Dec 21, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [1f1c718c61](https://linux-hardware.org/?probe=1f1c718c61) | Dec 21, 2022 |
| Timi          | Mi NoteBook Pro             | [b5bbb4f410](https://linux-hardware.org/?probe=b5bbb4f410) | Dec 21, 2022 |
| MSI           | Modern 14 B4MW              | [2d446beedf](https://linux-hardware.org/?probe=2d446beedf) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| Dell          | Latitude 3420               | [99d501d768](https://linux-hardware.org/?probe=99d501d768) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [383b0f3311](https://linux-hardware.org/?probe=383b0f3311) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| HP            | ZBook 15                    | [a3bf671d64](https://linux-hardware.org/?probe=a3bf671d64) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| Dell          | Vostro 5620                 | [005d388376](https://linux-hardware.org/?probe=005d388376) | Dec 20, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [bbfea042cd](https://linux-hardware.org/?probe=bbfea042cd) | Dec 20, 2022 |
| HP            | Pavilion dv6                | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [011d3e746d](https://linux-hardware.org/?probe=011d3e746d) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [b30bf77d27](https://linux-hardware.org/?probe=b30bf77d27) | Dec 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [c67b4d2b31](https://linux-hardware.org/?probe=c67b4d2b31) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [9f5a91c628](https://linux-hardware.org/?probe=9f5a91c628) | Dec 19, 2022 |
| Sony          | SVE15133CNB                 | [a2bee3bb3f](https://linux-hardware.org/?probe=a2bee3bb3f) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| MSI           | GE63 Raider RGB 8RF         | [a85193c482](https://linux-hardware.org/?probe=a85193c482) | Dec 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [714d2a6dea](https://linux-hardware.org/?probe=714d2a6dea) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [856515e522](https://linux-hardware.org/?probe=856515e522) | Dec 19, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a5a207a46d](https://linux-hardware.org/?probe=a5a207a46d) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| Acer          | Swift SF114-32              | [757b666913](https://linux-hardware.org/?probe=757b666913) | Dec 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [23b255ed61](https://linux-hardware.org/?probe=23b255ed61) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [86c9426d80](https://linux-hardware.org/?probe=86c9426d80) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [05fcf7302f](https://linux-hardware.org/?probe=05fcf7302f) | Dec 18, 2022 |
| Acer          | Aspire A315-31              | [e391c56a47](https://linux-hardware.org/?probe=e391c56a47) | Dec 18, 2022 |
| Lenovo        | ThinkPad W550s 20E2000PG... | [938c10075a](https://linux-hardware.org/?probe=938c10075a) | Dec 18, 2022 |
| HP            | Laptop 15-da0xxx            | [b712a7bd77](https://linux-hardware.org/?probe=b712a7bd77) | Dec 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [56e75d70fa](https://linux-hardware.org/?probe=56e75d70fa) | Dec 18, 2022 |
| HP            | ProBook 450 G7              | [ad9bf6b390](https://linux-hardware.org/?probe=ad9bf6b390) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c9cc617e08](https://linux-hardware.org/?probe=c9cc617e08) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [f047451b08](https://linux-hardware.org/?probe=f047451b08) | Dec 17, 2022 |
| Sony          | SVE15133CNB                 | [acca7c4697](https://linux-hardware.org/?probe=acca7c4697) | Dec 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [49969f1b81](https://linux-hardware.org/?probe=49969f1b81) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [df49d0114f](https://linux-hardware.org/?probe=df49d0114f) | Dec 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [a481e4a590](https://linux-hardware.org/?probe=a481e4a590) | Dec 17, 2022 |
| GPD           | P2 MAX                      | [de5983ec37](https://linux-hardware.org/?probe=de5983ec37) | Dec 17, 2022 |
| ASUSTek       | X45C                        | [80377ba23f](https://linux-hardware.org/?probe=80377ba23f) | Dec 17, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | [8d631bb590](https://linux-hardware.org/?probe=8d631bb590) | Dec 17, 2022 |
| Dell          | Inspiron 3583               | [5629961182](https://linux-hardware.org/?probe=5629961182) | Dec 17, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [5ab1c3b848](https://linux-hardware.org/?probe=5ab1c3b848) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [645e7245d4](https://linux-hardware.org/?probe=645e7245d4) | Dec 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [2ba98da01d](https://linux-hardware.org/?probe=2ba98da01d) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a767e0fbf0](https://linux-hardware.org/?probe=a767e0fbf0) | Dec 16, 2022 |
| HP            | Laptop 14-cm0xxx            | [a5bdc5f3c9](https://linux-hardware.org/?probe=a5bdc5f3c9) | Dec 16, 2022 |
| Dell          | Vostro 5590                 | [3735674d3f](https://linux-hardware.org/?probe=3735674d3f) | Dec 16, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7c678e18cd](https://linux-hardware.org/?probe=7c678e18cd) | Dec 16, 2022 |
| Dell          | Inspiron 5566               | [ccfc358303](https://linux-hardware.org/?probe=ccfc358303) | Dec 16, 2022 |
| ASUSTek       | X550LD                      | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Lenovo        | ThinkPad W530 243858U       | [9dc4fb1abb](https://linux-hardware.org/?probe=9dc4fb1abb) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [955de558cb](https://linux-hardware.org/?probe=955de558cb) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [e1d8403247](https://linux-hardware.org/?probe=e1d8403247) | Dec 16, 2022 |
| Dell          | XPS 13 9380                 | [719f489e01](https://linux-hardware.org/?probe=719f489e01) | Dec 15, 2022 |
| Dell          | Inspiron 7501               | [1749ece1b3](https://linux-hardware.org/?probe=1749ece1b3) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [b8cc280665](https://linux-hardware.org/?probe=b8cc280665) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1dd0f2a71f](https://linux-hardware.org/?probe=1dd0f2a71f) | Dec 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [85c38f0af3](https://linux-hardware.org/?probe=85c38f0af3) | Dec 15, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [06d690e9fe](https://linux-hardware.org/?probe=06d690e9fe) | Dec 15, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [1380e253a5](https://linux-hardware.org/?probe=1380e253a5) | Dec 14, 2022 |
| Samsung       | 750XDA                      | [0120054e9f](https://linux-hardware.org/?probe=0120054e9f) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [fe7f585504](https://linux-hardware.org/?probe=fe7f585504) | Dec 14, 2022 |
| Dell          | Inspiron 3583               | [70992b154e](https://linux-hardware.org/?probe=70992b154e) | Dec 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [b2d808ab85](https://linux-hardware.org/?probe=b2d808ab85) | Dec 14, 2022 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | [bed7f6d44e](https://linux-hardware.org/?probe=bed7f6d44e) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [95aca2679a](https://linux-hardware.org/?probe=95aca2679a) | Dec 14, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [44484456f8](https://linux-hardware.org/?probe=44484456f8) | Dec 14, 2022 |
| HP            | Laptop 14-fq1xxx            | [2da9ae7906](https://linux-hardware.org/?probe=2da9ae7906) | Dec 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [034b34f6d6](https://linux-hardware.org/?probe=034b34f6d6) | Dec 13, 2022 |
| Pegatron      | C17A                        | [adde308568](https://linux-hardware.org/?probe=adde308568) | Dec 13, 2022 |
| HP            | Laptop 14-fq1xxx            | [ed92313ebc](https://linux-hardware.org/?probe=ed92313ebc) | Dec 13, 2022 |
| HP            | ProBook 440 G7              | [ca2ba2d622](https://linux-hardware.org/?probe=ca2ba2d622) | Dec 13, 2022 |
| Toshiba       | TECRA A10                   | [760bda2b7d](https://linux-hardware.org/?probe=760bda2b7d) | Dec 13, 2022 |
| Acer          | Predator G9-591             | [838b0e0f8c](https://linux-hardware.org/?probe=838b0e0f8c) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [63cbf5d0e9](https://linux-hardware.org/?probe=63cbf5d0e9) | Dec 13, 2022 |
| MSI           | Modern 14 B4MW              | [8489ca12d8](https://linux-hardware.org/?probe=8489ca12d8) | Dec 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [3eb157838e](https://linux-hardware.org/?probe=3eb157838e) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [3c5a5379a4](https://linux-hardware.org/?probe=3c5a5379a4) | Dec 13, 2022 |
| Dell          | Inspiron 13-5368            | [952dd9d819](https://linux-hardware.org/?probe=952dd9d819) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [d742af8997](https://linux-hardware.org/?probe=d742af8997) | Dec 13, 2022 |
| HUAWEI        | KLVL-WXX9                   | [469a37f1e4](https://linux-hardware.org/?probe=469a37f1e4) | Dec 12, 2022 |
| Dell          | Inspiron 7380               | [29d4feb456](https://linux-hardware.org/?probe=29d4feb456) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| HP            | ProBook 6570b               | [a6b67497a1](https://linux-hardware.org/?probe=a6b67497a1) | Dec 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | [bdddbb7807](https://linux-hardware.org/?probe=bdddbb7807) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [9fb659eea3](https://linux-hardware.org/?probe=9fb659eea3) | Dec 12, 2022 |
| MSI           | GE63 Raider RGB 8RF         | [b311865418](https://linux-hardware.org/?probe=b311865418) | Dec 12, 2022 |
| MSI           | Modern 14 B11MOU            | [9739ffdf34](https://linux-hardware.org/?probe=9739ffdf34) | Dec 12, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [257e692fa4](https://linux-hardware.org/?probe=257e692fa4) | Dec 11, 2022 |
| Toshiba       | Satellite A300              | [211e44e5d2](https://linux-hardware.org/?probe=211e44e5d2) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [50e8243e50](https://linux-hardware.org/?probe=50e8243e50) | Dec 11, 2022 |
| Acer          | Aspire E5-576G              | [9cc371883c](https://linux-hardware.org/?probe=9cc371883c) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [5cdd66c849](https://linux-hardware.org/?probe=5cdd66c849) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [624ea43f9d](https://linux-hardware.org/?probe=624ea43f9d) | Dec 11, 2022 |
| Notebook      | WA50SRQ                     | [da74211ac6](https://linux-hardware.org/?probe=da74211ac6) | Dec 11, 2022 |
| HP            | Pavilion g6                 | [b5662e5fec](https://linux-hardware.org/?probe=b5662e5fec) | Dec 11, 2022 |
| Dell          | Latitude E7240              | [591f0ad589](https://linux-hardware.org/?probe=591f0ad589) | Dec 11, 2022 |
| MSI           | Prestige 15 A11SCX          | [5941b1aed7](https://linux-hardware.org/?probe=5941b1aed7) | Dec 10, 2022 |
| MSI           | Prestige 15 A11SCX          | [ab1334fca2](https://linux-hardware.org/?probe=ab1334fca2) | Dec 10, 2022 |
| Dell          | XPS 17 9700                 | [0426545e91](https://linux-hardware.org/?probe=0426545e91) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [e80dfca4a8](https://linux-hardware.org/?probe=e80dfca4a8) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [25d5b5623b](https://linux-hardware.org/?probe=25d5b5623b) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [72f0e70b26](https://linux-hardware.org/?probe=72f0e70b26) | Dec 10, 2022 |
| Pegatron      | C17A                        | [2437a88730](https://linux-hardware.org/?probe=2437a88730) | Dec 09, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [ad09795330](https://linux-hardware.org/?probe=ad09795330) | Dec 09, 2022 |
| Schenker      | VIA 15                      | [25883b06a1](https://linux-hardware.org/?probe=25883b06a1) | Dec 09, 2022 |
| MSI           | Modern 15 A11MU             | [e5ba0c8749](https://linux-hardware.org/?probe=e5ba0c8749) | Dec 09, 2022 |
| HP            | 245 G8 Notebook PC          | [c291bac936](https://linux-hardware.org/?probe=c291bac936) | Dec 09, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5250630bdd](https://linux-hardware.org/?probe=5250630bdd) | Dec 09, 2022 |
| Acer          | Aspire E1-572G              | [2dabd7cf91](https://linux-hardware.org/?probe=2dabd7cf91) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1595cc246a](https://linux-hardware.org/?probe=1595cc246a) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [94c151e95d](https://linux-hardware.org/?probe=94c151e95d) | Dec 09, 2022 |
| HP            | Pavilion dv5                | [cdd08235ff](https://linux-hardware.org/?probe=cdd08235ff) | Dec 09, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [182678a056](https://linux-hardware.org/?probe=182678a056) | Dec 08, 2022 |
| Acer          | Aspire E1-572G              | [df78e85dfe](https://linux-hardware.org/?probe=df78e85dfe) | Dec 08, 2022 |
| HP            | ProBook 640 G1              | [c3bf44d032](https://linux-hardware.org/?probe=c3bf44d032) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | MACH-WX9                    | [5ed19862a7](https://linux-hardware.org/?probe=5ed19862a7) | Dec 08, 2022 |
| Dell          | Inspiron 5566               | [dcf5539e74](https://linux-hardware.org/?probe=dcf5539e74) | Dec 08, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [00995baaae](https://linux-hardware.org/?probe=00995baaae) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | [59118a0638](https://linux-hardware.org/?probe=59118a0638) | Dec 07, 2022 |
| Dell          | XPS 13 9350                 | [9779817777](https://linux-hardware.org/?probe=9779817777) | Dec 07, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [efe4d93e2d](https://linux-hardware.org/?probe=efe4d93e2d) | Dec 07, 2022 |
| Acer          | Aspire E5-571               | [d5d013b642](https://linux-hardware.org/?probe=d5d013b642) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | [a214979767](https://linux-hardware.org/?probe=a214979767) | Dec 07, 2022 |
| Dell          | Latitude E6420              | [e87ced9ea4](https://linux-hardware.org/?probe=e87ced9ea4) | Dec 06, 2022 |
| Dell          | Latitude E6420              | [17c9263444](https://linux-hardware.org/?probe=17c9263444) | Dec 06, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [a3b78e7093](https://linux-hardware.org/?probe=a3b78e7093) | Dec 06, 2022 |
| Acer          | Predator G9-591             | [6e8fe2e030](https://linux-hardware.org/?probe=6e8fe2e030) | Dec 06, 2022 |
| Acer          | Aspire E5-571               | [e9d00a798c](https://linux-hardware.org/?probe=e9d00a798c) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| BANGHO        | BES T5                      | [db1db74a86](https://linux-hardware.org/?probe=db1db74a86) | Dec 06, 2022 |
| HP            | Laptop 14-fq1xxx            | [4f93d8895e](https://linux-hardware.org/?probe=4f93d8895e) | Dec 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [12e33b1925](https://linux-hardware.org/?probe=12e33b1925) | Dec 06, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a6763bdd89](https://linux-hardware.org/?probe=a6763bdd89) | Dec 05, 2022 |
| Dell          | XPS 13 9343                 | [476763a913](https://linux-hardware.org/?probe=476763a913) | Dec 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c22a748043](https://linux-hardware.org/?probe=c22a748043) | Dec 05, 2022 |
| Dell          | Latitude 7490               | [e75a902d11](https://linux-hardware.org/?probe=e75a902d11) | Dec 05, 2022 |
| ASUSTek       | X510UNR                     | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |
| MSI           | Modern 14 B4MW              | [03c0b9e50d](https://linux-hardware.org/?probe=03c0b9e50d) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [9b87c97ed5](https://linux-hardware.org/?probe=9b87c97ed5) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [fe17634e66](https://linux-hardware.org/?probe=fe17634e66) | Dec 05, 2022 |
| Dell          | Inspiron 13-7378            | [b628250da9](https://linux-hardware.org/?probe=b628250da9) | Dec 04, 2022 |
| MSI           | GE72 6QD                    | [257a807435](https://linux-hardware.org/?probe=257a807435) | Dec 04, 2022 |
| Sony          | SVE15133CNB                 | [16f43f11a1](https://linux-hardware.org/?probe=16f43f11a1) | Dec 04, 2022 |
| Dell          | Inspiron 5459               | [9b714617c8](https://linux-hardware.org/?probe=9b714617c8) | Dec 04, 2022 |
| Apple         | MacBookPro8,1               | [29fa28c3f1](https://linux-hardware.org/?probe=29fa28c3f1) | Dec 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [076685806a](https://linux-hardware.org/?probe=076685806a) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fb96bd56ad](https://linux-hardware.org/?probe=fb96bd56ad) | Dec 04, 2022 |
| Dell          | Inspiron 5566               | [fb9c1854a2](https://linux-hardware.org/?probe=fb9c1854a2) | Dec 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [937053920b](https://linux-hardware.org/?probe=937053920b) | Dec 04, 2022 |
| Acer          | Aspire A515-45              | [48d98f5da4](https://linux-hardware.org/?probe=48d98f5da4) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f93dd5ad2d](https://linux-hardware.org/?probe=f93dd5ad2d) | Dec 03, 2022 |
| Apple         | MacBookPro9,2               | [eadd4cd3e1](https://linux-hardware.org/?probe=eadd4cd3e1) | Dec 03, 2022 |
| Pegatron      | A15W8                       | [f33c1aea21](https://linux-hardware.org/?probe=f33c1aea21) | Dec 03, 2022 |
| HP            | Laptop 15s-fr2xxx           | [623e794238](https://linux-hardware.org/?probe=623e794238) | Dec 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [c00aab388c](https://linux-hardware.org/?probe=c00aab388c) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [037216f966](https://linux-hardware.org/?probe=037216f966) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [1c27bd3d06](https://linux-hardware.org/?probe=1c27bd3d06) | Dec 03, 2022 |
| MSI           | Modern 14 B4MW              | [6890b98eeb](https://linux-hardware.org/?probe=6890b98eeb) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [d64c6bc6f4](https://linux-hardware.org/?probe=d64c6bc6f4) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [a9f812a233](https://linux-hardware.org/?probe=a9f812a233) | Dec 03, 2022 |
| Acer          | Aspire A715-51G             | [65aa3f7e69](https://linux-hardware.org/?probe=65aa3f7e69) | Dec 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [958e17ffc9](https://linux-hardware.org/?probe=958e17ffc9) | Dec 03, 2022 |
| Toshiba       | Satellite C50D-A-138        | [ccda846d5e](https://linux-hardware.org/?probe=ccda846d5e) | Dec 03, 2022 |
| Dell          | XPS 13 9350                 | [38c002d686](https://linux-hardware.org/?probe=38c002d686) | Dec 02, 2022 |
| Google        | Lick                        | [a03c415d36](https://linux-hardware.org/?probe=a03c415d36) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [dc80fd6907](https://linux-hardware.org/?probe=dc80fd6907) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [be8f757095](https://linux-hardware.org/?probe=be8f757095) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [1e40d6a94b](https://linux-hardware.org/?probe=1e40d6a94b) | Dec 02, 2022 |
| HP            | Pavilion Laptop 14-bk0xx    | [57c3eeaf3d](https://linux-hardware.org/?probe=57c3eeaf3d) | Dec 02, 2022 |
| Acer          | Aspire A515-45              | [495abda40a](https://linux-hardware.org/?probe=495abda40a) | Dec 02, 2022 |
| Sony          | VPCEB1M1E                   | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [2397eee427](https://linux-hardware.org/?probe=2397eee427) | Dec 01, 2022 |
| Google        | Kasumi                      | [d67591d35c](https://linux-hardware.org/?probe=d67591d35c) | Dec 01, 2022 |
| Acer          | Iconia W4-820               | [cf25eeba85](https://linux-hardware.org/?probe=cf25eeba85) | Dec 01, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [4ab89a8ad2](https://linux-hardware.org/?probe=4ab89a8ad2) | Dec 01, 2022 |
| Dell          | Latitude E5450              | [305bf364f6](https://linux-hardware.org/?probe=305bf364f6) | Dec 01, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [de34f148b9](https://linux-hardware.org/?probe=de34f148b9) | Dec 01, 2022 |
| Dell          | Latitude E5450              | [2b934a729c](https://linux-hardware.org/?probe=2b934a729c) | Dec 01, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [0128a48982](https://linux-hardware.org/?probe=0128a48982) | Dec 01, 2022 |
| HP            | ProBook 440 G7              | [a54a325001](https://linux-hardware.org/?probe=a54a325001) | Dec 01, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [f0ee9f78bd](https://linux-hardware.org/?probe=f0ee9f78bd) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [2436f4cf5e](https://linux-hardware.org/?probe=2436f4cf5e) | Nov 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [2df1670891](https://linux-hardware.org/?probe=2df1670891) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Notebook                    | [afac08b852](https://linux-hardware.org/?probe=afac08b852) | Nov 30, 2022 |
| Dell          | Inspiron 3580               | [6bc2705d99](https://linux-hardware.org/?probe=6bc2705d99) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S01Q3K    | [9fd6308179](https://linux-hardware.org/?probe=9fd6308179) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [38c4009dba](https://linux-hardware.org/?probe=38c4009dba) | Nov 30, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4a49152177](https://linux-hardware.org/?probe=4a49152177) | Nov 29, 2022 |
| Lenovo        | ThinkPad E550 20DF004RGE    | [a06fd97ee3](https://linux-hardware.org/?probe=a06fd97ee3) | Nov 29, 2022 |
| ASUSTek       | X756UXK                     | [a8fde1c59a](https://linux-hardware.org/?probe=a8fde1c59a) | Nov 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9216162e85](https://linux-hardware.org/?probe=9216162e85) | Nov 29, 2022 |
| Dell          | Latitude D620               | [9f6317405c](https://linux-hardware.org/?probe=9f6317405c) | Nov 29, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [bb023e130b](https://linux-hardware.org/?probe=bb023e130b) | Nov 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [fd821a4b54](https://linux-hardware.org/?probe=fd821a4b54) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [39e771bd92](https://linux-hardware.org/?probe=39e771bd92) | Nov 28, 2022 |
| Dell          | Latitude 7480               | [409c2f27c8](https://linux-hardware.org/?probe=409c2f27c8) | Nov 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [e1495dc120](https://linux-hardware.org/?probe=e1495dc120) | Nov 28, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [901fa6e871](https://linux-hardware.org/?probe=901fa6e871) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [86f58e68b6](https://linux-hardware.org/?probe=86f58e68b6) | Nov 28, 2022 |
| Acer          | Nitro AN517-54              | [a9b90b8910](https://linux-hardware.org/?probe=a9b90b8910) | Nov 27, 2022 |
| Unknown       | Unknown                     | [4f73de3788](https://linux-hardware.org/?probe=4f73de3788) | Nov 27, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [415a8f0d8b](https://linux-hardware.org/?probe=415a8f0d8b) | Nov 27, 2022 |
| Acer          | Nitro AN517-54              | [445583d2bb](https://linux-hardware.org/?probe=445583d2bb) | Nov 27, 2022 |
| HP            | Laptop 15-da1xxx            | [8c4cae32db](https://linux-hardware.org/?probe=8c4cae32db) | Nov 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [bdc1a14cd4](https://linux-hardware.org/?probe=bdc1a14cd4) | Nov 27, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [26083dd909](https://linux-hardware.org/?probe=26083dd909) | Nov 27, 2022 |
| ASUSTek       | N53Jf                       | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| AVITA         | NS14A6                      | [b9cc8fe757](https://linux-hardware.org/?probe=b9cc8fe757) | Nov 27, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [f91c391079](https://linux-hardware.org/?probe=f91c391079) | Nov 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [dc561bb107](https://linux-hardware.org/?probe=dc561bb107) | Nov 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [336d829333](https://linux-hardware.org/?probe=336d829333) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | [bda395e731](https://linux-hardware.org/?probe=bda395e731) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | [0138561b29](https://linux-hardware.org/?probe=0138561b29) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [74fcf5cb22](https://linux-hardware.org/?probe=74fcf5cb22) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a4dbfc0da9](https://linux-hardware.org/?probe=a4dbfc0da9) | Nov 26, 2022 |
| MACHENIKE     | MACHCREATOR-16              | [15d49eb71a](https://linux-hardware.org/?probe=15d49eb71a) | Nov 26, 2022 |
| Apple         | MacBookPro15,2              | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| MSI           | Modern 14 B5M               | [bf3c55e13b](https://linux-hardware.org/?probe=bf3c55e13b) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ab6ce548bc](https://linux-hardware.org/?probe=ab6ce548bc) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [848b6ab7b3](https://linux-hardware.org/?probe=848b6ab7b3) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [c34893c661](https://linux-hardware.org/?probe=c34893c661) | Nov 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [83a97530e1](https://linux-hardware.org/?probe=83a97530e1) | Nov 26, 2022 |
| Google        | Glimmer                     | [8ad30368c9](https://linux-hardware.org/?probe=8ad30368c9) | Nov 26, 2022 |
| GPD           | G1621-02                    | [f0e9e8442c](https://linux-hardware.org/?probe=f0e9e8442c) | Nov 26, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [d845cbb51d](https://linux-hardware.org/?probe=d845cbb51d) | Nov 26, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [18130ae317](https://linux-hardware.org/?probe=18130ae317) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | [376fc86892](https://linux-hardware.org/?probe=376fc86892) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | [f46e1bc341](https://linux-hardware.org/?probe=f46e1bc341) | Nov 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [4261949a3e](https://linux-hardware.org/?probe=4261949a3e) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [8acafcf4ab](https://linux-hardware.org/?probe=8acafcf4ab) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [682993f58f](https://linux-hardware.org/?probe=682993f58f) | Nov 25, 2022 |
| HP            | Laptop 14-dq1xxx            | [1e6fa19cc3](https://linux-hardware.org/?probe=1e6fa19cc3) | Nov 25, 2022 |
| Acer          | Nitro AN515-54              | [9226b4c616](https://linux-hardware.org/?probe=9226b4c616) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [95f653bddb](https://linux-hardware.org/?probe=95f653bddb) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [a4a2b60b09](https://linux-hardware.org/?probe=a4a2b60b09) | Nov 24, 2022 |
| Dell          | Inspiron 5370               | [469b2c3fd4](https://linux-hardware.org/?probe=469b2c3fd4) | Nov 24, 2022 |
| Toshiba       | Satellite S55-A             | [5466c61736](https://linux-hardware.org/?probe=5466c61736) | Nov 24, 2022 |
| ASUSTek       | Q550LF                      | [713f7b2c74](https://linux-hardware.org/?probe=713f7b2c74) | Nov 24, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [1c65fff6e7](https://linux-hardware.org/?probe=1c65fff6e7) | Nov 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d84bc82678](https://linux-hardware.org/?probe=d84bc82678) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [5b18e83e0d](https://linux-hardware.org/?probe=5b18e83e0d) | Nov 23, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [57dfd88985](https://linux-hardware.org/?probe=57dfd88985) | Nov 23, 2022 |
| HP            | Laptop 15-da0xxx            | [fa989478ad](https://linux-hardware.org/?probe=fa989478ad) | Nov 23, 2022 |
| HP            | Laptop 15-dw3xxx            | [fbf991818d](https://linux-hardware.org/?probe=fbf991818d) | Nov 23, 2022 |
| Apple         | MacBookPro9,2               | [3e176f0c26](https://linux-hardware.org/?probe=3e176f0c26) | Nov 22, 2022 |
| Acer          | Extensa 4220                | [af778b2ec9](https://linux-hardware.org/?probe=af778b2ec9) | Nov 22, 2022 |
| Acer          | Extensa 4220                | [04187e0d6e](https://linux-hardware.org/?probe=04187e0d6e) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [923ccf8b76](https://linux-hardware.org/?probe=923ccf8b76) | Nov 22, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [8a773e7358](https://linux-hardware.org/?probe=8a773e7358) | Nov 22, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [d49ca08585](https://linux-hardware.org/?probe=d49ca08585) | Nov 22, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [d48ad61c01](https://linux-hardware.org/?probe=d48ad61c01) | Nov 22, 2022 |
| Acer          | Aspire A515-45              | [0dcdb72cd6](https://linux-hardware.org/?probe=0dcdb72cd6) | Nov 22, 2022 |
| Acer          | Predator PH315-55           | [f411f75743](https://linux-hardware.org/?probe=f411f75743) | Nov 22, 2022 |
| HP            | Laptop 15-da0xxx            | [aef0888523](https://linux-hardware.org/?probe=aef0888523) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [8c624c76fa](https://linux-hardware.org/?probe=8c624c76fa) | Nov 21, 2022 |
| Acer          | Aspire A315-51              | [bcff111ecd](https://linux-hardware.org/?probe=bcff111ecd) | Nov 21, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [bce41d01ae](https://linux-hardware.org/?probe=bce41d01ae) | Nov 21, 2022 |
| Dell          | Latitude D620               | [d45ad40496](https://linux-hardware.org/?probe=d45ad40496) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| Dell          | Inspiron 3505               | [634f7d190d](https://linux-hardware.org/?probe=634f7d190d) | Nov 21, 2022 |
| HP            | ZBook 15 G4                 | [3378343bab](https://linux-hardware.org/?probe=3378343bab) | Nov 21, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [0e9d717db2](https://linux-hardware.org/?probe=0e9d717db2) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [aa4d9601ee](https://linux-hardware.org/?probe=aa4d9601ee) | Nov 21, 2022 |
| MSI           | Stealth GS66 12UGS          | [ca3d88f38d](https://linux-hardware.org/?probe=ca3d88f38d) | Nov 21, 2022 |
| Dell          | Latitude 7420               | [ca5319fd67](https://linux-hardware.org/?probe=ca5319fd67) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [5739045caa](https://linux-hardware.org/?probe=5739045caa) | Nov 20, 2022 |
| HUAWEI        | MACH-WX9                    | [32fa69ea64](https://linux-hardware.org/?probe=32fa69ea64) | Nov 20, 2022 |
| Dell          | XPS 13 7390                 | [9f6c38b4ee](https://linux-hardware.org/?probe=9f6c38b4ee) | Nov 20, 2022 |
| Acer          | Aspire A515-45              | [11e00d597d](https://linux-hardware.org/?probe=11e00d597d) | Nov 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [678cfec38b](https://linux-hardware.org/?probe=678cfec38b) | Nov 20, 2022 |
| MSI           | Katana GF76 11UD            | [1f47d7c31b](https://linux-hardware.org/?probe=1f47d7c31b) | Nov 20, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [ade5f58f0e](https://linux-hardware.org/?probe=ade5f58f0e) | Nov 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [58c63522a4](https://linux-hardware.org/?probe=58c63522a4) | Nov 20, 2022 |
| Lenovo        | ThinkPad T460 20FN004CMD    | [1b7140151d](https://linux-hardware.org/?probe=1b7140151d) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMS56K00    | [5ff1608320](https://linux-hardware.org/?probe=5ff1608320) | Nov 19, 2022 |
| Apple         | MacBookPro11,5              | [3b5c35b319](https://linux-hardware.org/?probe=3b5c35b319) | Nov 19, 2022 |
| Google        | Celes                       | [00ed0ea4b5](https://linux-hardware.org/?probe=00ed0ea4b5) | Nov 19, 2022 |
| Sony          | SVE15133CNB                 | [3d78ceb657](https://linux-hardware.org/?probe=3d78ceb657) | Nov 19, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [bed1f98f04](https://linux-hardware.org/?probe=bed1f98f04) | Nov 19, 2022 |
| HUAWEI        | CREM-WXX9                   | [f9b8181279](https://linux-hardware.org/?probe=f9b8181279) | Nov 19, 2022 |
| Google        | Lick                        | [6d8750d974](https://linux-hardware.org/?probe=6d8750d974) | Nov 19, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [87d8a1ee6b](https://linux-hardware.org/?probe=87d8a1ee6b) | Nov 19, 2022 |
| ASUSTek       | M80TA                       | [d2427d8942](https://linux-hardware.org/?probe=d2427d8942) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L6S3L400    | [ae98e93989](https://linux-hardware.org/?probe=ae98e93989) | Nov 18, 2022 |
| Google        | Careena                     | [81dd8e9906](https://linux-hardware.org/?probe=81dd8e9906) | Nov 18, 2022 |
| HP            | EliteBook 840 14 inch G9... | [b5d4ff63a5](https://linux-hardware.org/?probe=b5d4ff63a5) | Nov 18, 2022 |
| HP            | Laptop 15-ef1xxx            | [2e47c9c20f](https://linux-hardware.org/?probe=2e47c9c20f) | Nov 18, 2022 |
| Dell          | XPS 13 7390                 | [19d18ac52c](https://linux-hardware.org/?probe=19d18ac52c) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [33113bb27d](https://linux-hardware.org/?probe=33113bb27d) | Nov 17, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [61f6e057e6](https://linux-hardware.org/?probe=61f6e057e6) | Nov 17, 2022 |
| Acer          | Aspire A515-51              | [ee9d0faeef](https://linux-hardware.org/?probe=ee9d0faeef) | Nov 17, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [190c6d9cc7](https://linux-hardware.org/?probe=190c6d9cc7) | Nov 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [450e658685](https://linux-hardware.org/?probe=450e658685) | Nov 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [6f2f504425](https://linux-hardware.org/?probe=6f2f504425) | Nov 16, 2022 |
| Lenovo        | ThinkPad Edge 03192AG       | [48da1b11bc](https://linux-hardware.org/?probe=48da1b11bc) | Nov 16, 2022 |
| Apple         | MacBookPro11,5              | [62586ed7f9](https://linux-hardware.org/?probe=62586ed7f9) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8b2d48cd24](https://linux-hardware.org/?probe=8b2d48cd24) | Nov 16, 2022 |
| MSI           | Katana GF76 11UD            | [fec345f330](https://linux-hardware.org/?probe=fec345f330) | Nov 16, 2022 |
| GPD           | G1619-04                    | [c1e365fd5d](https://linux-hardware.org/?probe=c1e365fd5d) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | [03426a19e5](https://linux-hardware.org/?probe=03426a19e5) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e7343719c2](https://linux-hardware.org/?probe=e7343719c2) | Nov 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [5d11a28230](https://linux-hardware.org/?probe=5d11a28230) | Nov 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [94983688d2](https://linux-hardware.org/?probe=94983688d2) | Nov 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [bafff409d9](https://linux-hardware.org/?probe=bafff409d9) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [1104a26017](https://linux-hardware.org/?probe=1104a26017) | Nov 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [119f9da4af](https://linux-hardware.org/?probe=119f9da4af) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [4c05f821c1](https://linux-hardware.org/?probe=4c05f821c1) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6af7c2ad85](https://linux-hardware.org/?probe=6af7c2ad85) | Nov 15, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [d2cf28fbb9](https://linux-hardware.org/?probe=d2cf28fbb9) | Nov 15, 2022 |
| Kraftway      | ACCORD                      | [7021cedadf](https://linux-hardware.org/?probe=7021cedadf) | Nov 15, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [465bc481e2](https://linux-hardware.org/?probe=465bc481e2) | Nov 14, 2022 |
| Lenovo        | ThinkPad L450 20DSS1GD00    | [b0ea02b16c](https://linux-hardware.org/?probe=b0ea02b16c) | Nov 13, 2022 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [09285b9428](https://linux-hardware.org/?probe=09285b9428) | Nov 13, 2022 |
| Apple         | MacBook9,1                  | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Laptop 15s-eq2xxx           | [b64a32327f](https://linux-hardware.org/?probe=b64a32327f) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0e3e3c885a](https://linux-hardware.org/?probe=0e3e3c885a) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2421b6c5a4](https://linux-hardware.org/?probe=2421b6c5a4) | Nov 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3bcdc36fff](https://linux-hardware.org/?probe=3bcdc36fff) | Nov 11, 2022 |
| Dell          | Latitude 7480               | [cd19ef7ab8](https://linux-hardware.org/?probe=cd19ef7ab8) | Nov 10, 2022 |
| Dell          | Latitude 7480               | [100bc3303a](https://linux-hardware.org/?probe=100bc3303a) | Nov 10, 2022 |
| Acer          | Nitro AN515-46              | [741209999d](https://linux-hardware.org/?probe=741209999d) | Nov 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [4e535c916f](https://linux-hardware.org/?probe=4e535c916f) | Nov 10, 2022 |
| GPD           | G1619-04                    | [cf4cb47a12](https://linux-hardware.org/?probe=cf4cb47a12) | Nov 09, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [4a6aec2eb8](https://linux-hardware.org/?probe=4a6aec2eb8) | Nov 09, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [a2e9b34d94](https://linux-hardware.org/?probe=a2e9b34d94) | Nov 09, 2022 |
| Acer          | SW5-017                     | [d4ff3ee29e](https://linux-hardware.org/?probe=d4ff3ee29e) | Nov 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [1cca3aa247](https://linux-hardware.org/?probe=1cca3aa247) | Nov 08, 2022 |
| Eluktronic... | P670RE3                     | [d96ecdf7ab](https://linux-hardware.org/?probe=d96ecdf7ab) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fc4fb9249e](https://linux-hardware.org/?probe=fc4fb9249e) | Nov 08, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [f0c2157642](https://linux-hardware.org/?probe=f0c2157642) | Nov 07, 2022 |
| Acer          | Aspire A315-41              | [df6426eef5](https://linux-hardware.org/?probe=df6426eef5) | Nov 07, 2022 |
| Acer          | Aspire A315-41              | [bae4adcff9](https://linux-hardware.org/?probe=bae4adcff9) | Nov 07, 2022 |
| Dell          | G3 3579                     | [b793526167](https://linux-hardware.org/?probe=b793526167) | Nov 06, 2022 |
| Dell          | Vostro 13 5310              | [c25e192969](https://linux-hardware.org/?probe=c25e192969) | Nov 05, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [a2905cad90](https://linux-hardware.org/?probe=a2905cad90) | Nov 04, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3cb1f34e2a](https://linux-hardware.org/?probe=3cb1f34e2a) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | [80dbecb998](https://linux-hardware.org/?probe=80dbecb998) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [9d1ba43c71](https://linux-hardware.org/?probe=9d1ba43c71) | Nov 04, 2022 |
| Lenovo        | Unknown                     | [0825807141](https://linux-hardware.org/?probe=0825807141) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [dac055fa29](https://linux-hardware.org/?probe=dac055fa29) | Nov 04, 2022 |
| SLIMBOOK      | Executive                   | [cff86cc921](https://linux-hardware.org/?probe=cff86cc921) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9af713ef6e](https://linux-hardware.org/?probe=9af713ef6e) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [d87e75abbf](https://linux-hardware.org/?probe=d87e75abbf) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dae32fcba7](https://linux-hardware.org/?probe=dae32fcba7) | Nov 04, 2022 |
| Alienware     | x17 R2                      | [2e25d30db1](https://linux-hardware.org/?probe=2e25d30db1) | Nov 04, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [a2d3502165](https://linux-hardware.org/?probe=a2d3502165) | Nov 04, 2022 |
| UNOWHY        | Y13G011S4EI                 | [da784a5c82](https://linux-hardware.org/?probe=da784a5c82) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 14S           | [9fbf084c28](https://linux-hardware.org/?probe=9fbf084c28) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [18b0671002](https://linux-hardware.org/?probe=18b0671002) | Nov 03, 2022 |
| HUAWEI        | CREM-WXX9                   | [870d04c833](https://linux-hardware.org/?probe=870d04c833) | Nov 03, 2022 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | [984c379f69](https://linux-hardware.org/?probe=984c379f69) | Nov 03, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [aa6c06f2bb](https://linux-hardware.org/?probe=aa6c06f2bb) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [584db1dcb2](https://linux-hardware.org/?probe=584db1dcb2) | Nov 02, 2022 |
| GPD           | G1619-04                    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [1d24aac4ce](https://linux-hardware.org/?probe=1d24aac4ce) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [2eb32b1bb3](https://linux-hardware.org/?probe=2eb32b1bb3) | Nov 01, 2022 |
| HP            | ZBook 15 G2                 | [7254a9a2fc](https://linux-hardware.org/?probe=7254a9a2fc) | Nov 01, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [566d83485b](https://linux-hardware.org/?probe=566d83485b) | Oct 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [e993af2670](https://linux-hardware.org/?probe=e993af2670) | Oct 31, 2022 |
| HP            | ENVY 17                     | [5b845d9ee3](https://linux-hardware.org/?probe=5b845d9ee3) | Oct 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [073ba962ff](https://linux-hardware.org/?probe=073ba962ff) | Oct 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [221710c9ea](https://linux-hardware.org/?probe=221710c9ea) | Oct 31, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Dell          | Latitude 7490               | [95d0006efb](https://linux-hardware.org/?probe=95d0006efb) | Oct 30, 2022 |
| Dell          | XPS 13 9300                 | [cc62dbe2f6](https://linux-hardware.org/?probe=cc62dbe2f6) | Oct 29, 2022 |
| Dell          | XPS 13 9300                 | [301aab9126](https://linux-hardware.org/?probe=301aab9126) | Oct 29, 2022 |
| HP            | ZBook 15 G3                 | [c60b429baa](https://linux-hardware.org/?probe=c60b429baa) | Oct 28, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [0c6a68368c](https://linux-hardware.org/?probe=0c6a68368c) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [670823778e](https://linux-hardware.org/?probe=670823778e) | Oct 27, 2022 |
| Dell          | Latitude E7270              | [7f2c8b9e9c](https://linux-hardware.org/?probe=7f2c8b9e9c) | Oct 25, 2022 |
| Dell          | Latitude E7450              | [45e65cd626](https://linux-hardware.org/?probe=45e65cd626) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | [dc8eab937b](https://linux-hardware.org/?probe=dc8eab937b) | Oct 24, 2022 |
| HP            | 340S G7 Notebook PC         | [406538a0de](https://linux-hardware.org/?probe=406538a0de) | Oct 23, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [14830504a7](https://linux-hardware.org/?probe=14830504a7) | Oct 22, 2022 |
| Lenovo        | ThinkPad X260 20F5S5Q200    | [c2e041fd54](https://linux-hardware.org/?probe=c2e041fd54) | Oct 21, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [41bade1339](https://linux-hardware.org/?probe=41bade1339) | Oct 21, 2022 |
| LG Electro... | 16Z90P-G.AP75D              | [1e1526e9d8](https://linux-hardware.org/?probe=1e1526e9d8) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06328b7f7c](https://linux-hardware.org/?probe=06328b7f7c) | Oct 20, 2022 |
| Dell          | Latitude 7420               | [332d2cd420](https://linux-hardware.org/?probe=332d2cd420) | Oct 19, 2022 |
| System76      | Kudu                        | [49c0e1c400](https://linux-hardware.org/?probe=49c0e1c400) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [f91daeac73](https://linux-hardware.org/?probe=f91daeac73) | Oct 19, 2022 |
| Dell          | Precision 5510              | [d56d0aceaf](https://linux-hardware.org/?probe=d56d0aceaf) | Oct 18, 2022 |
| Acer          | Aspire A717-71G             | [969c0ac771](https://linux-hardware.org/?probe=969c0ac771) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [678415db20](https://linux-hardware.org/?probe=678415db20) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2a36feb313](https://linux-hardware.org/?probe=2a36feb313) | Oct 16, 2022 |
| Timi          | TM1701                      | [c2b709ff0c](https://linux-hardware.org/?probe=c2b709ff0c) | Oct 15, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [478b58f9b6](https://linux-hardware.org/?probe=478b58f9b6) | Oct 15, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [dbd2328d0f](https://linux-hardware.org/?probe=dbd2328d0f) | Oct 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3a8bdfb3f5](https://linux-hardware.org/?probe=3a8bdfb3f5) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9b0a923899](https://linux-hardware.org/?probe=9b0a923899) | Oct 13, 2022 |
| Acer          | Aspire A715-71G             | [2b0752150c](https://linux-hardware.org/?probe=2b0752150c) | Oct 12, 2022 |
| HP            | EliteBook 840 G6            | [29f63f8a32](https://linux-hardware.org/?probe=29f63f8a32) | Oct 10, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | [52658eb393](https://linux-hardware.org/?probe=52658eb393) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c0c2e0ca69](https://linux-hardware.org/?probe=c0c2e0ca69) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | [615578d390](https://linux-hardware.org/?probe=615578d390) | Oct 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5dbeb45ba5](https://linux-hardware.org/?probe=5dbeb45ba5) | Oct 06, 2022 |
| Acer          | Aspire E5-475G              | [a545cecc64](https://linux-hardware.org/?probe=a545cecc64) | Oct 05, 2022 |
| Acer          | Aspire E5-475G              | [06fa787cb1](https://linux-hardware.org/?probe=06fa787cb1) | Oct 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [f6fc1950ac](https://linux-hardware.org/?probe=f6fc1950ac) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d0d3494971](https://linux-hardware.org/?probe=d0d3494971) | Oct 05, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [ddb0e3fb81](https://linux-hardware.org/?probe=ddb0e3fb81) | Oct 05, 2022 |
| HP            | Laptop 15s-eq3xxx           | [2bd986670e](https://linux-hardware.org/?probe=2bd986670e) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [4ba3e28201](https://linux-hardware.org/?probe=4ba3e28201) | Oct 04, 2022 |
| Timi          | A35S                        | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [80a2948ff1](https://linux-hardware.org/?probe=80a2948ff1) | Oct 02, 2022 |
| Lenovo        | ThinkPad T470s 20HGS09L0... | [7c384e5578](https://linux-hardware.org/?probe=7c384e5578) | Sep 30, 2022 |
| A-DATA Tec... | XENIA 14                    | [251f390772](https://linux-hardware.org/?probe=251f390772) | Sep 30, 2022 |
| Dell          | Latitude 7430               | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| A-DATA Tec... | XENIA 14                    | [e819e5dc14](https://linux-hardware.org/?probe=e819e5dc14) | Sep 29, 2022 |
| HP            | ZBook 15 G3                 | [1d612b997a](https://linux-hardware.org/?probe=1d612b997a) | Sep 29, 2022 |
| ASUSTek       | X550CL                      | [ded047597e](https://linux-hardware.org/?probe=ded047597e) | Sep 28, 2022 |
| Timi          | A35S                        | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [7c62f5131f](https://linux-hardware.org/?probe=7c62f5131f) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [d8b270de2b](https://linux-hardware.org/?probe=d8b270de2b) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9f37c7c4fa](https://linux-hardware.org/?probe=9f37c7c4fa) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0d790a94fa](https://linux-hardware.org/?probe=0d790a94fa) | Sep 25, 2022 |
| Dell          | XPS 15 9520                 | [fab5b34402](https://linux-hardware.org/?probe=fab5b34402) | Sep 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [2e96ddfdd1](https://linux-hardware.org/?probe=2e96ddfdd1) | Sep 25, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [96f4499ec5](https://linux-hardware.org/?probe=96f4499ec5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [91bd22b430](https://linux-hardware.org/?probe=91bd22b430) | Sep 25, 2022 |
| Dell          | XPS 13 9380                 | [332540a4c8](https://linux-hardware.org/?probe=332540a4c8) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Lenovo        | ThinkPad T440s 20ARA0YL0... | [93eedc638b](https://linux-hardware.org/?probe=93eedc638b) | Sep 24, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [b7f6ab8ad0](https://linux-hardware.org/?probe=b7f6ab8ad0) | Sep 23, 2022 |
| Timi          | A35S                        | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Dell          | XPS 9320                    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| Acer          | Nitro AN517-51              | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1da95a964b](https://linux-hardware.org/?probe=1da95a964b) | Sep 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [3615e82cb6](https://linux-hardware.org/?probe=3615e82cb6) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Irbis         | NB264                       | [e9361bf1c8](https://linux-hardware.org/?probe=e9361bf1c8) | Sep 17, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ec8f0a9ebf](https://linux-hardware.org/?probe=ec8f0a9ebf) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [8fab790c57](https://linux-hardware.org/?probe=8fab790c57) | Sep 14, 2022 |
| System76      | Lemur Pro                   | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| HUAWEI        | HVY-WXX9                    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7326474aae](https://linux-hardware.org/?probe=7326474aae) | Sep 13, 2022 |
| AXDIA Inte... | WINPAD V10                  | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| HP            | EliteBook 820 G1            | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| Samsung       | 270E5G/270E5U               | [d1f2245fb4](https://linux-hardware.org/?probe=d1f2245fb4) | Jul 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [43098a1f34](https://linux-hardware.org/?probe=43098a1f34) | Apr 23, 2022 |
| HP            | Laptop 14-dq2xxx            | [2477951c04](https://linux-hardware.org/?probe=2477951c04) | Apr 15, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_37/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| 6.0.15-300.fc37.x86_64                             | 75        | 10.49%  |
| 6.0.8-300.fc37.x86_64                              | 54        | 7.55%   |
| 6.0.9-300.fc37.x86_64                              | 51        | 7.13%   |
| 6.0.12-300.fc37.x86_64                             | 49        | 6.85%   |
| 6.1.7-200.fc37.x86_64                              | 48        | 6.71%   |
| 6.0.7-301.fc37.x86_64                              | 46        | 6.43%   |
| 6.0.11-300.fc37.x86_64                             | 35        | 4.9%    |
| 6.0.10-300.fc37.x86_64                             | 35        | 4.9%    |
| 6.1.6-200.fc37.x86_64                              | 32        | 4.48%   |
| 6.0.16-300.fc37.x86_64                             | 31        | 4.34%   |
| 6.0.18-300.fc37.x86_64                             | 29        | 4.06%   |
| 5.19.16-301.fc37.x86_64                            | 25        | 3.5%    |
| 6.1.5-200.fc37.x86_64                              | 21        | 2.94%   |
| 6.0.17-300.fc37.x86_64                             | 18        | 2.52%   |
| 6.0.14-300.fc37.x86_64                             | 17        | 2.38%   |
| 6.0.13-300.fc37.x86_64                             | 16        | 2.24%   |
| 6.1.8-200.fc37.x86_64                              | 15        | 2.1%    |
| 5.19.8-300.fc37.x86_64                             | 10        | 1.4%    |
| 5.19.7-300.fc37.x86_64                             | 9         | 1.26%   |
| 5.19.13-300.fc37.x86_64                            | 9         | 1.26%   |
| 5.19.14-300.fc37.x86_64                            | 7         | 0.98%   |
| 6.0.6-300.fc37.x86_64                              | 6         | 0.84%   |
| 5.19.15-301.fc37.x86_64                            | 6         | 0.84%   |
| 5.19.11-300.fc37.x86_64                            | 6         | 0.84%   |
| 5.19.10-300.fc37.x86_64                            | 6         | 0.84%   |
| 5.19.9-300.fc37.x86_64                             | 5         | 0.7%    |
| 5.19.12-300.fc37.x86_64                            | 4         | 0.56%   |
| 6.0.5-300.fc37.x86_64                              | 3         | 0.42%   |
| 5.19.16-300.fc37.x86_64                            | 3         | 0.42%   |
| 6.0.9-300.mbp.fc37.x86_64                          | 2         | 0.28%   |
| 6.0.2-xm1.0.fc37.x86_64                            | 2         | 0.28%   |
| 5.19.15-300.fc37.x86_64                            | 2         | 0.28%   |
| 5.18.0-0.rc2.23.fc37.x86_64                        | 2         | 0.28%   |
| 5.17.5-300.fc36.x86_64                             | 2         | 0.28%   |
| 6.2.0-0.rc3.20230110git5a41237ad1d4.25.fc38.x86_64 | 1         | 0.14%   |
| 6.2.0-0.rc2.20230103git69b41ac87e4a.19.fc38.x86_64 | 1         | 0.14%   |
| 6.1.8-603.inttf.fc37.x86_64                        | 1         | 0.14%   |
| 6.1.2-200.fc37.x86_64                              | 1         | 0.14%   |
| 6.1.1-xm1.0.fc37.x86_64                            | 1         | 0.14%   |
| 6.1.1-225.vanilla.1.fc37.x86_64                    | 1         | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.15  | 77        | 10.77%  |
| 6.0.9   | 57        | 7.97%   |
| 6.0.8   | 57        | 7.97%   |
| 6.0.12  | 49        | 6.85%   |
| 6.1.7   | 48        | 6.71%   |
| 6.0.7   | 46        | 6.43%   |
| 6.0.10  | 36        | 5.03%   |
| 6.0.11  | 35        | 4.9%    |
| 6.1.6   | 32        | 4.48%   |
| 6.0.16  | 31        | 4.34%   |
| 6.0.18  | 29        | 4.06%   |
| 5.19.16 | 29        | 4.06%   |
| 6.1.5   | 21        | 2.94%   |
| 6.0.17  | 18        | 2.52%   |
| 6.0.14  | 17        | 2.38%   |
| 6.1.8   | 16        | 2.24%   |
| 6.0.13  | 16        | 2.24%   |
| 5.19.8  | 10        | 1.4%    |
| 5.19.7  | 9         | 1.26%   |
| 5.19.13 | 9         | 1.26%   |
| 5.19.15 | 8         | 1.12%   |
| 6.1.0   | 7         | 0.98%   |
| 5.19.14 | 7         | 0.98%   |
| 5.19.10 | 7         | 0.98%   |
| 6.0.6   | 6         | 0.84%   |
| 5.19.12 | 6         | 0.84%   |
| 5.19.11 | 6         | 0.84%   |
| 5.19.9  | 5         | 0.7%    |
| 6.0.5   | 3         | 0.42%   |
| 5.19.0  | 3         | 0.42%   |
| 6.2.0   | 2         | 0.28%   |
| 6.1.1   | 2         | 0.28%   |
| 6.0.2   | 2         | 0.28%   |
| 5.18.0  | 2         | 0.28%   |
| 5.17.5  | 2         | 0.28%   |
| 6.1.2   | 1         | 0.14%   |
| 6.0.0   | 1         | 0.14%   |
| 5.19.4  | 1         | 0.14%   |
| 5.15.55 | 1         | 0.14%   |
| 5.15.54 | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 453       | 66.33%  |
| 6.1     | 125       | 18.3%   |
| 5.19    | 97        | 14.2%   |
| 6.2     | 2         | 0.29%   |
| 5.18    | 2         | 0.29%   |
| 5.17    | 2         | 0.29%   |
| 5.15    | 2         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 669       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 503       | 74.63%  |
| KDE5       | 117       | 17.36%  |
| Unknown    | 12        | 1.78%   |
| XFCE       | 9         | 1.34%   |
| X-Cinnamon | 9         | 1.34%   |
| MATE       | 6         | 0.89%   |
| i3         | 6         | 0.89%   |
| LXDE       | 3         | 0.45%   |
| Cinnamon   | 3         | 0.45%   |
| sway       | 2         | 0.3%    |
| xmonad     | 1         | 0.15%   |
| qtile      | 1         | 0.15%   |
| LXQt       | 1         | 0.15%   |
| KDE        | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 519       | 76.89%  |
| X11     | 144       | 21.33%  |
| Unknown | 9         | 1.33%   |
| Tty     | 3         | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 341       | 50.52%  |
| GDM     | 243       | 36%     |
| SDDM    | 56        | 8.3%    |
| LightDM | 32        | 4.74%   |
| LXDM    | 2         | 0.3%    |
| GREETD  | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 343       | 51.04%  |
| ru_RU   | 46        | 6.85%   |
| en_GB   | 42        | 6.25%   |
| pt_BR   | 31        | 4.61%   |
| de_DE   | 26        | 3.87%   |
| fr_FR   | 23        | 3.42%   |
| it_IT   | 18        | 2.68%   |
| en_IN   | 16        | 2.38%   |
| en_AU   | 14        | 2.08%   |
| pl_PL   | 10        | 1.49%   |
| en_CA   | 10        | 1.49%   |
| es_ES   | 8         | 1.19%   |
| zh_CN   | 6         | 0.89%   |
| tr_TR   | 5         | 0.74%   |
| es_MX   | 5         | 0.74%   |
| es_CL   | 5         | 0.74%   |
| es_AR   | 5         | 0.74%   |
| en_ZA   | 4         | 0.6%    |
| de_AT   | 4         | 0.6%    |
| C       | 4         | 0.6%    |
| zh_TW   | 3         | 0.45%   |
| hu_HU   | 3         | 0.45%   |
| en_PH   | 3         | 0.45%   |
| en_IE   | 3         | 0.45%   |
| nl_NL   | 2         | 0.3%    |
| fi_FI   | 2         | 0.3%    |
| en_DK   | 2         | 0.3%    |
| de_CH   | 2         | 0.3%    |
| ca_ES   | 2         | 0.3%    |
| Unknown | 2         | 0.3%    |
| uk_UA   | 1         | 0.15%   |
| sv_SE   | 1         | 0.15%   |
| sk_SK   | 1         | 0.15%   |
| ro_RO   | 1         | 0.15%   |
| pt_PT   | 1         | 0.15%   |
| nb_NO   | 1         | 0.15%   |
| ja_JP   | 1         | 0.15%   |
| id_ID   | 1         | 0.15%   |
| hr_HR   | 1         | 0.15%   |
| fr_CA   | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 588       | 87.76%  |
| BIOS | 82        | 12.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 566       | 84.35%  |
| Ext4    | 97        | 14.46%  |
| Xfs     | 4         | 0.6%    |
| Overlay | 4         | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 331       | 49.18%  |
| Unknown | 330       | 49.03%  |
| MBR     | 12        | 1.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 614       | 91.1%   |
| Yes       | 60        | 8.9%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 546       | 81.49%  |
| Yes       | 124       | 18.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 190       | 28.4%   |
| Hewlett-Packard       | 105       | 15.7%   |
| Dell                  | 99        | 14.8%   |
| ASUSTek Computer      | 79        | 11.81%  |
| Acer                  | 55        | 8.22%   |
| HUAWEI                | 23        | 3.44%   |
| MSI                   | 18        | 2.69%   |
| Apple                 | 14        | 2.09%   |
| Timi                  | 9         | 1.35%   |
| Google                | 7         | 1.05%   |
| Toshiba               | 6         | 0.9%    |
| TUXEDO                | 5         | 0.75%   |
| GPD                   | 5         | 0.75%   |
| Schenker              | 4         | 0.6%    |
| Samsung Electronics   | 4         | 0.6%    |
| System76              | 3         | 0.45%   |
| Framework             | 3         | 0.45%   |
| Chuwi                 | 3         | 0.45%   |
| Sony                  | 2         | 0.3%    |
| SLIMBOOK              | 2         | 0.3%    |
| Pegatron              | 2         | 0.3%    |
| Notebook              | 2         | 0.3%    |
| MACHENIKE             | 2         | 0.3%    |
| Alienware             | 2         | 0.3%    |
| Valve                 | 1         | 0.15%   |
| UNOWHY                | 1         | 0.15%   |
| TECNO                 | 1         | 0.15%   |
| Razer                 | 1         | 0.15%   |
| Positivo Bahia - VAIO | 1         | 0.15%   |
| PC Specialist         | 1         | 0.15%   |
| Olivetti              | 1         | 0.15%   |
| Multilaser            | 1         | 0.15%   |
| MECHREVO              | 1         | 0.15%   |
| LG Electronics        | 1         | 0.15%   |
| Kraftway              | 1         | 0.15%   |
| Jooyon Tech           | 1         | 0.15%   |
| Irbis                 | 1         | 0.15%   |
| Intel Client Systems  | 1         | 0.15%   |
| Infinix               | 1         | 0.15%   |
| HONOR                 | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo IdeaPad 330-15IKB 81DE              | 4         | 0.6%    |
| HUAWEI CREM-WXX9                           | 4         | 0.6%    |
| Lenovo ThinkBook 15 G3 ACL 21A4            | 3         | 0.45%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5           | 3         | 0.45%   |
| HP OMEN by Laptop 16-c0xxx                 | 3         | 0.45%   |
| GPD G1619-04                               | 3         | 0.45%   |
| Dell XPS 15 9570                           | 3         | 0.45%   |
| Dell XPS 15 9520                           | 3         | 0.45%   |
| Dell Latitude 7490                         | 3         | 0.45%   |
| Dell Latitude 7480                         | 3         | 0.45%   |
| Dell Latitude 5420                         | 3         | 0.45%   |
| Dell Inspiron 5566                         | 3         | 0.45%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA     | 3         | 0.45%   |
| ASUS VivoBook_ASUSLaptop M5402RA_M5402RA   | 3         | 0.45%   |
| Apple MacBookPro9,2                        | 3         | 0.45%   |
| Acer Aspire A515-45                        | 3         | 0.45%   |
| Timi A35S                                  | 2         | 0.3%    |
| MSI Stealth GS66 12UGS                     | 2         | 0.3%    |
| MSI Modern 14 B11MOU                       | 2         | 0.3%    |
| MACHENIKE MACHCREATOR-16                   | 2         | 0.3%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 2         | 0.3%    |
| Lenovo ThinkBook 16p Gen 2 20YM            | 2         | 0.3%    |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 0.3%    |
| Lenovo Legion 5 15ACH6H 82JU               | 2         | 0.3%    |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 2         | 0.3%    |
| Lenovo IdeaPad 5 Pro 14ARH7 82SJ           | 2         | 0.3%    |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7           | 2         | 0.3%    |
| Lenovo IdeaPad 3 15ALC6 82KU               | 2         | 0.3%    |
| HUAWEI NBLK-WAX9X                          | 2         | 0.3%    |
| HUAWEI NBLB-WAX9N                          | 2         | 0.3%    |
| HUAWEI MACH-WX9                            | 2         | 0.3%    |
| HUAWEI KLVL-WXX9                           | 2         | 0.3%    |
| HUAWEI HVY-WXX9                            | 2         | 0.3%    |
| HUAWEI BOHK-WAX9X                          | 2         | 0.3%    |
| HUAWEI BOHB-WAX9                           | 2         | 0.3%    |
| HP ZBook 15 G3                             | 2         | 0.3%    |
| HP Victus by Gaming Laptop 15-fa0xxx       | 2         | 0.3%    |
| HP ProBook 640 G1                          | 2         | 0.3%    |
| HP ProBook 440 G7                          | 2         | 0.3%    |
| HP ProBook 430 G8 Notebook PC              | 2         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 110       | 16.44%  |
| Lenovo IdeaPad      | 41        | 6.13%   |
| Dell Inspiron       | 33        | 4.93%   |
| Dell Latitude       | 32        | 4.78%   |
| Acer Aspire         | 29        | 4.33%   |
| HP Laptop           | 21        | 3.14%   |
| HP EliteBook        | 21        | 3.14%   |
| ASUS VivoBook       | 21        | 3.14%   |
| HP Pavilion         | 19        | 2.84%   |
| Dell XPS            | 18        | 2.69%   |
| Lenovo ThinkBook    | 17        | 2.54%   |
| ASUS ASUS           | 14        | 2.09%   |
| HP ProBook          | 13        | 1.94%   |
| ASUS ROG            | 11        | 1.64%   |
| Acer Nitro          | 11        | 1.64%   |
| HP ZBook            | 9         | 1.35%   |
| ASUS Zenbook        | 9         | 1.35%   |
| Lenovo Legion       | 8         | 1.2%    |
| HP OMEN             | 6         | 0.9%    |
| Dell Vostro         | 6         | 0.9%    |
| Acer Predator       | 6         | 0.9%    |
| Toshiba Satellite   | 5         | 0.75%   |
| MSI Modern          | 5         | 0.75%   |
| Acer Swift          | 5         | 0.75%   |
| Lenovo Yoga         | 4         | 0.6%    |
| HUAWEI CREM-WXX9    | 4         | 0.6%    |
| HP ENVY             | 4         | 0.6%    |
| Dell Precision      | 4         | 0.6%    |
| Apple MacBookPro9   | 4         | 0.6%    |
| HP Victus           | 3         | 0.45%   |
| GPD G1619-04        | 3         | 0.45%   |
| Framework Laptop    | 3         | 0.45%   |
| Apple MacBookPro11  | 3         | 0.45%   |
| TUXEDO Pulse        | 2         | 0.3%    |
| TUXEDO InfinityBook | 2         | 0.3%    |
| Timi Xiaomi         | 2         | 0.3%    |
| Timi RedmiBook      | 2         | 0.3%    |
| Timi A35S           | 2         | 0.3%    |
| Schenker XMG        | 2         | 0.3%    |
| MSI Stealth         | 2         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 147       | 21.97%  |
| 2022 | 109       | 16.29%  |
| 2020 | 98        | 14.65%  |
| 2019 | 64        | 9.57%   |
| 2018 | 61        | 9.12%   |
| 2017 | 43        | 6.43%   |
| 2013 | 31        | 4.63%   |
| 2016 | 29        | 4.33%   |
| 2012 | 25        | 3.74%   |
| 2015 | 20        | 2.99%   |
| 2014 | 13        | 1.94%   |
| 2011 | 9         | 1.35%   |
| 2010 | 9         | 1.35%   |
| 2008 | 8         | 1.2%    |
| 2009 | 1         | 0.15%   |
| 2007 | 1         | 0.15%   |
| 2006 | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 669       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 475       | 70.79%  |
| Enabled  | 196       | 29.21%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 661       | 98.8%   |
| Yes  | 8         | 1.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 183       | 27.27%  |
| 8.01-16.0   | 159       | 23.7%   |
| 16.01-24.0  | 156       | 23.25%  |
| 32.01-64.0  | 80        | 11.92%  |
| 3.01-4.0    | 51        | 7.6%    |
| 24.01-32.0  | 16        | 2.38%   |
| 64.01-256.0 | 15        | 2.24%   |
| 1.01-2.0    | 9         | 1.34%   |
| 2.01-3.0    | 2         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 243       | 34.86%  |
| 3.01-4.0   | 165       | 23.67%  |
| 2.01-3.0   | 162       | 23.24%  |
| 1.01-2.0   | 62        | 8.9%    |
| 8.01-16.0  | 51        | 7.32%   |
| 0.51-1.0   | 7         | 1%      |
| 16.01-24.0 | 6         | 0.86%   |
| 24.01-32.0 | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 502       | 74.81%  |
| 2      | 154       | 22.95%  |
| 3      | 11        | 1.64%   |
| 0      | 3         | 0.45%   |
| 4      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 584       | 87.29%  |
| Yes       | 85        | 12.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 454       | 67.86%  |
| No        | 215       | 32.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 665       | 99.25%  |
| No        | 5         | 0.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 581       | 86.59%  |
| No        | 90        | 13.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 91        | 13.56%  |
| Russia             | 57        | 8.49%   |
| Germany            | 49        | 7.3%    |
| Brazil             | 42        | 6.26%   |
| Italy              | 39        | 5.81%   |
| India              | 38        | 5.66%   |
| France             | 28        | 4.17%   |
| Canada             | 22        | 3.28%   |
| Poland             | 20        | 2.98%   |
| Australia          | 18        | 2.68%   |
| Turkey             | 15        | 2.24%   |
| Austria            | 15        | 2.24%   |
| UK                 | 14        | 2.09%   |
| Spain              | 14        | 2.09%   |
| Netherlands        | 14        | 2.09%   |
| Mexico             | 10        | 1.49%   |
| Taiwan             | 9         | 1.34%   |
| Switzerland        | 9         | 1.34%   |
| Sweden             | 9         | 1.34%   |
| Argentina          | 8         | 1.19%   |
| Indonesia          | 7         | 1.04%   |
| Hungary            | 7         | 1.04%   |
| Czechia            | 7         | 1.04%   |
| Slovakia           | 5         | 0.75%   |
| Norway             | 5         | 0.75%   |
| Finland            | 5         | 0.75%   |
| Chile              | 5         | 0.75%   |
| South Africa       | 4         | 0.6%    |
| Serbia             | 4         | 0.6%    |
| Philippines        | 4         | 0.6%    |
| Japan              | 4         | 0.6%    |
| Ireland            | 4         | 0.6%    |
| Hong Kong          | 4         | 0.6%    |
| Belgium            | 4         | 0.6%    |
| Sri Lanka          | 3         | 0.45%   |
| Peru               | 3         | 0.45%   |
| Israel             | 3         | 0.45%   |
| Dominican Republic | 3         | 0.45%   |
| Denmark            | 3         | 0.45%   |
| Colombia           | 3         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 15        | 2.19%   |
| Vienna            | 9         | 1.32%   |
| St Petersburg     | 7         | 1.02%   |
| Madrid            | 7         | 1.02%   |
| Sao Paulo         | 6         | 0.88%   |
| Brisbane          | 6         | 0.88%   |
| Melbourne         | 5         | 0.73%   |
| Istanbul          | 5         | 0.73%   |
| Frankfurt am Main | 5         | 0.73%   |
| Amsterdam         | 5         | 0.73%   |
| Warsaw            | 4         | 0.58%   |
| Montreal          | 4         | 0.58%   |
| Jakarta           | 4         | 0.58%   |
| Izmir             | 4         | 0.58%   |
| Cape Town         | 4         | 0.58%   |
| Berlin            | 4         | 0.58%   |
| Bengaluru         | 4         | 0.58%   |
| Zurich            | 3         | 0.44%   |
| Zapopan           | 3         | 0.44%   |
| Sydney            | 3         | 0.44%   |
| Santiago          | 3         | 0.44%   |
| Pune              | 3         | 0.44%   |
| Prague            | 3         | 0.44%   |
| Porto Alegre      | 3         | 0.44%   |
| Portland          | 3         | 0.44%   |
| Perm              | 3         | 0.44%   |
| Paris             | 3         | 0.44%   |
| New York          | 3         | 0.44%   |
| New Taipei        | 3         | 0.44%   |
| Milan             | 3         | 0.44%   |
| Miami             | 3         | 0.44%   |
| London            | 3         | 0.44%   |
| Krasnodar         | 3         | 0.44%   |
| Karlskrona        | 3         | 0.44%   |
| Innsbruck         | 3         | 0.44%   |
| Helsinki          | 3         | 0.44%   |
| Easton            | 3         | 0.44%   |
| Delft             | 3         | 0.44%   |
| Curitiba          | 3         | 0.44%   |
| Chennai           | 3         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 186       | 216    | 22.66%  |
| SK hynix                       | 72        | 74     | 8.77%   |
| SanDisk                        | 72        | 81     | 8.77%   |
| WDC                            | 70        | 78     | 8.53%   |
| Micron Technology              | 44        | 48     | 5.36%   |
| Toshiba                        | 40        | 41     | 4.87%   |
| Kingston                       | 40        | 46     | 4.87%   |
| Seagate                        | 37        | 40     | 4.51%   |
| Intel                          | 31        | 34     | 3.78%   |
| Crucial                        | 31        | 31     | 3.78%   |
| Unknown                        | 28        | 33     | 3.41%   |
| KIOXIA                         | 22        | 25     | 2.68%   |
| Apple                          | 10        | 13     | 1.22%   |
| HGST                           | 9         | 10     | 1.1%    |
| A-DATA Technology              | 9         | 10     | 1.1%    |
| LITEON                         | 8         | 8      | 0.97%   |
| Micron/Crucial Technology      | 7         | 7      | 0.85%   |
| China                          | 6         | 7      | 0.73%   |
| Phison Electronics             | 5         | 6      | 0.61%   |
| Kingston Technology Company    | 5         | 5      | 0.61%   |
| Hitachi                        | 5         | 5      | 0.61%   |
| ADATA Technology               | 5         | 5      | 0.61%   |
| Unknown                        | 5         | 6      | 0.61%   |
| PNY                            | 4         | 4      | 0.49%   |
| Phison                         | 4         | 4      | 0.49%   |
| HS-SSD-E100                    | 4         | 4      | 0.49%   |
| FORESEE                        | 4         | 4      | 0.49%   |
| UMIS                           | 3         | 3      | 0.37%   |
| SPCC                           | 3         | 3      | 0.37%   |
| Realtek Semiconductor          | 3         | 3      | 0.37%   |
| Netac                          | 3         | 4      | 0.37%   |
| Lexar                          | 3         | 3      | 0.37%   |
| Apacer                         | 3         | 3      | 0.37%   |
| YMTC                           | 2         | 2      | 0.24%   |
| XPG                            | 2         | 2      | 0.24%   |
| Solid State Storage Technology | 2         | 2      | 0.24%   |
| Silicon Motion                 | 2         | 2      | 0.24%   |
| SABRENT                        | 2         | 2      | 0.24%   |
| Biwin Storage Technology       | 2         | 2      | 0.24%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 30        | 3.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 18        | 2.14%   |
| Seagate ST1000LM035-1RK172 1TB                       | 13        | 1.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB       | 13        | 1.55%   |
| Toshiba MQ04ABF100 1TB                               | 12        | 1.43%   |
| Kingston SA400S37240G 240GB SSD                      | 10        | 1.19%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 9         | 1.07%   |
| Crucial CT240BX500SSD1 240GB                         | 8         | 0.95%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 7         | 0.83%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 7         | 0.83%   |
| KIOXIA KBG40ZNV512G 512GB                            | 7         | 0.83%   |
| Intel SSDPEKNU512GZ 512GB                            | 7         | 0.83%   |
| Micron 2210_MTFDHBA512QFD 512GB                      | 6         | 0.71%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 5         | 0.59%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB               | 5         | 0.59%   |
| Sandisk WD Black SN850 2TB                           | 5         | 0.59%   |
| Samsung MZVLQ512HALU-000H1 512GB                     | 5         | 0.59%   |
| Crucial CT1000MX500SSD1 1TB                          | 5         | 0.59%   |
| Unknown                                              | 5         | 0.59%   |
| Unknown MMC Card  64GB                               | 4         | 0.48%   |
| Unknown MMC Card  32GB                               | 4         | 0.48%   |
| SK hynix HFM256GD3JX016N 256GB                       | 4         | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 4         | 0.48%   |
| SanDisk NVMe SSD Drive 1TB                           | 4         | 0.48%   |
| Samsung SSD 980 PRO 1TB                              | 4         | 0.48%   |
| Samsung SSD 980 500GB                                | 4         | 0.48%   |
| Samsung SSD 980 1TB                                  | 4         | 0.48%   |
| Samsung SSD 870 EVO 500GB                            | 4         | 0.48%   |
| Samsung SSD 860 EVO 500GB                            | 4         | 0.48%   |
| Samsung MZVLQ512HALU-00000 512GB                     | 4         | 0.48%   |
| Samsung MZALQ512HALU-000L2 512GB                     | 4         | 0.48%   |
| Kingston OM8PCP3512F-AI1 512GB                       | 4         | 0.48%   |
| Intel SSD 600P Series 256GB                          | 4         | 0.48%   |
| Crucial CT1000BX500SSD1 1TB                          | 4         | 0.48%   |
| A-DATA IM2P33F8ABR2-256GB                            | 4         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 3         | 0.36%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 3         | 0.36%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 3         | 0.36%   |
| WDC PC SN730 SDBPNTY-512G                            | 3         | 0.36%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                   | 3         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 37        | 40     | 34.91%  |
| Toshiba  | 26        | 26     | 24.53%  |
| WDC      | 24        | 26     | 22.64%  |
| HGST     | 9         | 10     | 8.49%   |
| Hitachi  | 5         | 5      | 4.72%   |
| Unknown  | 2         | 2      | 1.89%   |
| SABRENT  | 2         | 2      | 1.89%   |
| External | 1         | 1      | 0.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 44     | 19.9%   |
| Crucial             | 24        | 24     | 12.57%  |
| Kingston            | 21        | 23     | 10.99%  |
| WDC                 | 16        | 17     | 8.38%   |
| SanDisk             | 15        | 17     | 7.85%   |
| SK hynix            | 9         | 9      | 4.71%   |
| Micron Technology   | 9         | 9      | 4.71%   |
| Apple               | 7         | 7      | 3.66%   |
| LITEON              | 6         | 6      | 3.14%   |
| China               | 6         | 7      | 3.14%   |
| PNY                 | 4         | 4      | 2.09%   |
| Toshiba             | 3         | 3      | 1.57%   |
| Lexar               | 3         | 3      | 1.57%   |
| Intel               | 3         | 3      | 1.57%   |
| Apacer              | 3         | 3      | 1.57%   |
| SPCC                | 2         | 2      | 1.05%   |
| Netac               | 2         | 2      | 1.05%   |
| FORESEE             | 2         | 2      | 1.05%   |
| A-DATA Technology   | 2         | 2      | 1.05%   |
| Unknown             | 2         | 2      | 1.05%   |
| Teclast             | 1         | 2      | 0.52%   |
| Team                | 1         | 2      | 0.52%   |
| Ramaxel Technology  | 1         | 1      | 0.52%   |
| Patriot             | 1         | 1      | 0.52%   |
| OCZ                 | 1         | 1      | 0.52%   |
| JAMESDONKEY         | 1         | 1      | 0.52%   |
| Intenso             | 1         | 1      | 0.52%   |
| HS-SSD-C100         | 1         | 1      | 0.52%   |
| GOODRAM             | 1         | 2      | 0.52%   |
| Gigabyte Technology | 1         | 2      | 0.52%   |
| G521N               | 1         | 1      | 0.52%   |
| ExeGate             | 1         | 1      | 0.52%   |
| Eluktro             | 1         | 1      | 0.52%   |
| Dahua               | 1         | 1      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 450       | 546    | 57.92%  |
| SSD     | 183       | 207    | 23.55%  |
| HDD     | 105       | 112    | 13.51%  |
| MMC     | 29        | 34     | 3.73%   |
| Unknown | 10        | 10     | 1.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 450       | 546    | 59.76%  |
| SATA | 260       | 315    | 34.53%  |
| MMC  | 29        | 34     | 3.85%   |
| SAS  | 14        | 14     | 1.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 179       | 208    | 63.03%  |
| 0.51-1.0   | 93        | 98     | 32.75%  |
| 1.01-2.0   | 6         | 7      | 2.11%   |
| 3.01-4.0   | 4         | 4      | 1.41%   |
| 4.01-10.0  | 2         | 2      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 160       | 23.6%   |
| 251-500        | 147       | 21.68%  |
| 1-20           | 98        | 14.45%  |
| 1001-2000      | 81        | 11.95%  |
| 101-250        | 73        | 10.77%  |
| Unknown        | 61        | 9%      |
| 2001-3000      | 15        | 2.21%   |
| 51-100         | 15        | 2.21%   |
| More than 3000 | 14        | 2.06%   |
| 21-50          | 14        | 2.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 208       | 30.06%  |
| 21-50     | 122       | 17.63%  |
| 101-250   | 96        | 13.87%  |
| 51-100    | 87        | 12.57%  |
| 251-500   | 65        | 9.39%   |
| Unknown   | 61        | 8.82%   |
| 501-1000  | 41        | 5.92%   |
| 1001-2000 | 11        | 1.59%   |
| 2001-3000 | 1         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 6.25%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 6.25%   |
| Toshiba MK5061GSY 500GB                             | 1         | 1      | 6.25%   |
| Toshiba MK3265GSX 320GB                             | 1         | 1      | 6.25%   |
| Toshiba MK1237GSX 120GB                             | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 6.25%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 6.25%   |
| Seagate ST500LM000-SSHD-8GB                         | 1         | 1      | 6.25%   |
| Seagate ST4000LM024-2AN17V 4TB                      | 1         | 1      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 2      | 6.25%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 6.25%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 1         | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 6.25%   |
| Unknown                                             | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 31.25%  |
| Toshiba             | 4         | 4      | 25%     |
| WDC                 | 2         | 2      | 12.5%   |
| Micron Technology   | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 2      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |
| Unknown             | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 45.45%  |
| Toshiba | 4         | 4      | 36.36%  |
| WDC     | 1         | 1      | 9.09%   |
| HGST    | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 68.75%  |
| SSD  | 5         | 6      | 31.25%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 382       | 522    | 54.81%  |
| Works    | 298       | 369    | 42.75%  |
| Malfunc  | 16        | 17     | 2.3%    |
| Failed   | 1         | 1      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 355       | 39.18%  |
| Samsung Electronics            | 153       | 16.89%  |
| AMD                            | 89        | 9.82%   |
| SanDisk                        | 88        | 9.71%   |
| SK hynix                       | 63        | 6.95%   |
| Micron Technology              | 36        | 3.97%   |
| Kingston Technology Company    | 24        | 2.65%   |
| KIOXIA                         | 18        | 1.99%   |
| Toshiba America Info Systems   | 15        | 1.66%   |
| Micron/Crucial Technology      | 12        | 1.32%   |
| ADATA Technology               | 12        | 1.32%   |
| Phison Electronics             | 10        | 1.1%    |
| Union Memory (Shenzhen)        | 4         | 0.44%   |
| Realtek Semiconductor          | 4         | 0.44%   |
| Yangtze Memory Technologies    | 3         | 0.33%   |
| Solid State Storage Technology | 3         | 0.33%   |
| Silicon Motion                 | 3         | 0.33%   |
| Lite-On Technology             | 3         | 0.33%   |
| Apple                          | 3         | 0.33%   |
| Shenzhen Longsys Electronics   | 2         | 0.22%   |
| Biwin Storage Technology       | 2         | 0.22%   |
| Netac Technology               | 1         | 0.11%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.11%   |
| Marvell Technology Group       | 1         | 0.11%   |
| Lenovo                         | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 87        | 9.18%   |
| Intel Volume Management Device NVMe RAID Controller                            | 62        | 6.54%   |
| Samsung NVMe SSD Controller 980                                                | 55        | 5.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 52        | 5.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 50        | 5.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 40        | 4.22%   |
| Micron Non-Volatile memory controller                                          | 36        | 3.8%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 35        | 3.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 35        | 3.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 31        | 3.27%   |
| SanDisk Non-Volatile memory controller                                         | 25        | 2.64%   |
| Intel Tiger Lake-LP SATA Controller                                            | 23        | 2.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 23        | 2.43%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 22        | 2.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 16        | 1.69%   |
| Intel Comet Lake SATA AHCI Controller                                          | 16        | 1.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 15        | 1.58%   |
| Intel Non-Volatile memory controller                                           | 15        | 1.58%   |
| Kingston Company Company Non-Volatile memory controller                        | 14        | 1.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 14        | 1.48%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 13        | 1.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 11        | 1.16%   |
| SK hynix Non-Volatile memory controller                                        | 10        | 1.05%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 10        | 1.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 10        | 1.05%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 0.95%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 9         | 0.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 0.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 0.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 0.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 0.74%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 6         | 0.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 0.63%   |
| SK hynix BC511                                                                 | 5         | 0.53%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 5         | 0.53%   |
| Phison E12 NVMe Controller                                                     | 5         | 0.53%   |
| KIOXIA Non-Volatile memory controller                                          | 5         | 0.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 0.53%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 4         | 0.42%   |
| SanDisk PC SN520 NVMe SSD                                                      | 4         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 449       | 49.56%  |
| SATA | 359       | 39.62%  |
| RAID | 94        | 10.38%  |
| IDE  | 4         | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 484       | 72.35%  |
| AMD    | 185       | 27.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 26        | 3.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 20        | 2.99%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 18        | 2.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 2.09%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 14        | 2.09%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 1.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 1.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 12        | 1.79%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 1.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 1.49%   |
| Intel 12th Gen Core i7-12700H                 | 10        | 1.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 1.35%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 1.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 1.35%   |
| Intel 12th Gen Core i5-1240P                  | 9         | 1.35%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 9         | 1.35%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 9         | 1.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 1.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 1.2%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 8         | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 1.2%    |
| Intel 12th Gen Core i5-1235U                  | 8         | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.05%   |
| Intel 12th Gen Core i9-12900H                 | 7         | 1.05%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 7         | 1.05%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 1.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.9%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 6         | 0.9%    |
| AMD Ryzen 7 6800H with Radeon Graphics        | 6         | 0.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 0.75%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 5         | 0.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.75%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 0.75%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 5         | 0.75%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 5         | 0.75%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Other                                | 142       | 21.23%  |
| Intel Core i5                        | 136       | 20.33%  |
| Intel Core i7                        | 127       | 18.98%  |
| AMD Ryzen 7                          | 67        | 10.01%  |
| AMD Ryzen 5                          | 55        | 8.22%   |
| Intel Core i3                        | 35        | 5.23%   |
| Intel Celeron                        | 16        | 2.39%   |
| AMD Ryzen 9                          | 13        | 1.94%   |
| AMD Ryzen 7 PRO                      | 13        | 1.94%   |
| AMD Ryzen 5 PRO                      | 12        | 1.79%   |
| AMD Ryzen 3                          | 11        | 1.64%   |
| Intel Core 2 Duo                     | 8         | 1.2%    |
| Intel Core i9                        | 5         | 0.75%   |
| Intel Atom                           | 5         | 0.75%   |
| AMD A4                               | 5         | 0.75%   |
| Intel Pentium                        | 4         | 0.6%    |
| AMD A6                               | 4         | 0.6%    |
| Intel Pentium Silver                 | 3         | 0.45%   |
| Intel Pentium Dual-Core              | 1         | 0.15%   |
| Intel Core m5                        | 1         | 0.15%   |
| Intel Core m3                        | 1         | 0.15%   |
| Intel Core 2                         | 1         | 0.15%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.15%   |
| AMD E1                               | 1         | 0.15%   |
| AMD A8                               | 1         | 0.15%   |
| AMD A10                              | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 237       | 35.43%  |
| 2      | 186       | 27.8%   |
| 8      | 106       | 15.84%  |
| 6      | 84        | 12.56%  |
| 14     | 21        | 3.14%   |
| 12     | 18        | 2.69%   |
| 10     | 14        | 2.09%   |
| 1      | 2         | 0.3%    |
| 16     | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 669       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 607       | 90.6%   |
| 1      | 63        | 9.4%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 669       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 60        | 8.94%   |
| 0x806ec    | 42        | 6.26%   |
| 0x0a50000c | 42        | 6.26%   |
| 0x906a3    | 41        | 6.11%   |
| Unknown    | 40        | 5.96%   |
| 0x806ea    | 35        | 5.22%   |
| 0x306a9    | 30        | 4.47%   |
| 0x906ea    | 24        | 3.58%   |
| 0x406e3    | 21        | 3.13%   |
| 0x806e9    | 20        | 2.98%   |
| 0x08600106 | 20        | 2.98%   |
| 0x08608103 | 19        | 2.83%   |
| 0xa0652    | 18        | 2.68%   |
| 0x306d4    | 18        | 2.68%   |
| 0x40651    | 16        | 2.38%   |
| 0x08108109 | 14        | 2.09%   |
| 0x906a4    | 13        | 1.94%   |
| 0x806d1    | 13        | 1.94%   |
| 0x0a404102 | 12        | 1.79%   |
| 0x206a7    | 11        | 1.64%   |
| 0x0a404101 | 10        | 1.49%   |
| 0x08600104 | 10        | 1.49%   |
| 0x906e9    | 9         | 1.34%   |
| 0x706e5    | 9         | 1.34%   |
| 0x506e3    | 9         | 1.34%   |
| 0x306c3    | 9         | 1.34%   |
| 0x806c2    | 8         | 1.19%   |
| 0x706a8    | 8         | 1.19%   |
| 0x08608102 | 7         | 1.04%   |
| 0x806eb    | 6         | 0.89%   |
| 0x1067a    | 6         | 0.89%   |
| 0x0810100b | 6         | 0.89%   |
| 0x06006705 | 6         | 0.89%   |
| 0x506c9    | 4         | 0.6%    |
| 0x30678    | 4         | 0.6%    |
| 0x20655    | 4         | 0.6%    |
| 0x0a50000d | 4         | 0.6%    |
| 0x08108102 | 4         | 0.6%    |
| 0x906ed    | 3         | 0.45%   |
| 0x906c0    | 3         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 152       | 22.72%  |
| TigerLake        | 71        | 10.61%  |
| Alderlake Hybrid | 57        | 8.52%   |
| Zen 3            | 55        | 8.22%   |
| Unknown          | 52        | 7.77%   |
| Zen 2            | 35        | 5.23%   |
| Skylake          | 31        | 4.63%   |
| IvyBridge        | 31        | 4.63%   |
| Haswell          | 27        | 4.04%   |
| IceLake          | 23        | 3.44%   |
| Zen+             | 20        | 2.99%   |
| CometLake        | 20        | 2.99%   |
| Broadwell        | 18        | 2.69%   |
| SandyBridge      | 11        | 1.64%   |
| Zen              | 10        | 1.49%   |
| Silvermont       | 9         | 1.35%   |
| Goldmont plus    | 9         | 1.35%   |
| Excavator        | 7         | 1.05%   |
| Westmere         | 6         | 0.9%    |
| Penryn           | 6         | 0.9%    |
| Goldmont         | 4         | 0.6%    |
| Core             | 4         | 0.6%    |
| Tremont          | 3         | 0.45%   |
| Jaguar           | 2         | 0.3%    |
| Steamroller      | 1         | 0.15%   |
| Piledriver       | 1         | 0.15%   |
| Nehalem          | 1         | 0.15%   |
| K8 & K10 hybrid  | 1         | 0.15%   |
| K10 Llano        | 1         | 0.15%   |
| Bonnell          | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 469       | 52.82%  |
| Nvidia | 213       | 23.99%  |
| AMD    | 206       | 23.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 62        | 6.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 43        | 4.76%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 38        | 4.21%   |
| AMD Renoir                                                                | 35        | 3.88%   |
| Intel UHD Graphics 620                                                    | 32        | 3.54%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 31        | 3.43%   |
| AMD Lucienne                                                              | 29        | 3.21%   |
| Intel HD Graphics 620                                                     | 27        | 2.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 27        | 2.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 26        | 2.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 24        | 2.66%   |
| AMD Rembrandt [Radeon 680M]                                               | 22        | 2.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 20        | 2.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 20        | 2.21%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 18        | 1.99%   |
| Intel HD Graphics 5500                                                    | 17        | 1.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 17        | 1.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 16        | 1.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 15        | 1.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 13        | 1.44%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 13        | 1.44%   |
| Nvidia GP108M [GeForce MX150]                                             | 11        | 1.22%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 11        | 1.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 11        | 1.22%   |
| AMD Barcelo                                                               | 11        | 1.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 10        | 1.11%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 9         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 9         | 1%      |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 9         | 1%      |
| Intel HD Graphics 630                                                     | 9         | 1%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 9         | 1%      |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 8         | 0.89%   |
| Intel HD Graphics 530                                                     | 8         | 0.89%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 8         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 7         | 0.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 7         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 6         | 0.66%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 6         | 0.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 6         | 0.66%   |
| Nvidia TU117M                                                             | 5         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 288       | 43.05%  |
| Intel + Nvidia     | 161       | 24.07%  |
| 1 x AMD            | 141       | 21.08%  |
| AMD + Nvidia       | 38        | 5.68%   |
| Intel + AMD        | 16        | 2.39%   |
| 1 x Nvidia         | 12        | 1.79%   |
| 2 x AMD            | 11        | 1.64%   |
| 2 x Intel          | 1         | 0.15%   |
| Intel + 2 x Nvidia | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 549       | 81.82%  |
| Proprietary | 115       | 17.14%  |
| Unknown     | 7         | 1.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 399       | 59.29%  |
| 0.01-0.5   | 102       | 15.16%  |
| 1.01-2.0   | 70        | 10.4%   |
| 3.01-4.0   | 43        | 6.39%   |
| 0.51-1.0   | 31        | 4.61%   |
| 5.01-6.0   | 17        | 2.53%   |
| 7.01-8.0   | 5         | 0.74%   |
| 2.01-3.0   | 4         | 0.59%   |
| 8.01-16.0  | 2         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 158       | 19.48%  |
| AU Optronics            | 148       | 18.25%  |
| Chimei Innolux          | 114       | 14.06%  |
| LG Display              | 84        | 10.36%  |
| Samsung Electronics     | 48        | 5.92%   |
| Dell                    | 22        | 2.71%   |
| CSO                     | 22        | 2.71%   |
| Goldstar                | 20        | 2.47%   |
| Sharp                   | 19        | 2.34%   |
| PANDA                   | 19        | 2.34%   |
| Lenovo                  | 16        | 1.97%   |
| Apple                   | 13        | 1.6%    |
| InfoVision              | 12        | 1.48%   |
| Hewlett-Packard         | 12        | 1.48%   |
| AOC                     | 12        | 1.48%   |
| BenQ                    | 10        | 1.23%   |
| Acer                    | 10        | 1.23%   |
| ASUSTek Computer        | 6         | 0.74%   |
| JDI                     | 5         | 0.62%   |
| Chi Mei Optoelectronics | 5         | 0.62%   |
| ViewSonic               | 4         | 0.49%   |
| Toshiba                 | 4         | 0.49%   |
| TMX                     | 4         | 0.49%   |
| Philips                 | 4         | 0.49%   |
| Sony                    | 3         | 0.37%   |
| Mi                      | 3         | 0.37%   |
| Vestel Elektronik       | 2         | 0.25%   |
| Panasonic               | 2         | 0.25%   |
| NCS                     | 2         | 0.25%   |
| MSI                     | 2         | 0.25%   |
| LG Philips              | 2         | 0.25%   |
| Iiyama                  | 2         | 0.25%   |
| HUAWEI                  | 2         | 0.25%   |
| Vizio                   | 1         | 0.12%   |
| Valve                   | 1         | 0.12%   |
| Tianma XM               | 1         | 0.12%   |
| Sceptre Tech            | 1         | 0.12%   |
| Pixio                   | 1         | 0.12%   |
| OEM                     | 1         | 0.12%   |
| LNV                     | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 10        | 1.22%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 10        | 1.22%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 9         | 1.1%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 8         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 8         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 6         | 0.73%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 6         | 0.73%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.73%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 5         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 5         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.61%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 4         | 0.49%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 4         | 0.49%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 0.49%   |
| CSO LCD Monitor CSO160A 2560x1600 345x215mm 16.0-inch                 | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 0.49%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 4         | 0.49%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 4         | 0.49%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 4         | 0.49%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 4         | 0.49%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 4         | 0.49%   |
| AU Optronics LCD Monitor AUOA08B 1920x1080 344x193mm 15.5-inch        | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 4         | 0.49%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 3         | 0.37%   |
| Mi Monitor XMI3446 3440x1440 797x334mm 34.0-inch                      | 3         | 0.37%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.37%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 3         | 0.37%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 0.37%   |
| CSO LCD Monitor CSO1601 2560x1600 345x215mm 16.0-inch                 | 3         | 0.37%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                 | 3         | 0.37%   |
| CSO LCD Monitor CSO140C 2880x1800 302x188mm 14.0-inch                 | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch      | 3         | 0.37%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.37%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 3         | 0.37%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 401       | 52.9%   |
| 1366x768 (WXGA)    | 103       | 13.59%  |
| 2560x1440 (QHD)    | 38        | 5.01%   |
| 2560x1600          | 35        | 4.62%   |
| 3840x2160 (4K)     | 34        | 4.49%   |
| 1920x1200 (WUXGA)  | 30        | 3.96%   |
| 1600x900 (HD+)     | 21        | 2.77%   |
| 2880x1800          | 19        | 2.51%   |
| 3440x1440          | 10        | 1.32%   |
| 1280x800 (WXGA)    | 9         | 1.19%   |
| 2560x1080          | 6         | 0.79%   |
| 2160x1440          | 6         | 0.79%   |
| 1280x1024 (SXGA)   | 6         | 0.79%   |
| 3840x2400          | 4         | 0.53%   |
| 2520x1680          | 4         | 0.53%   |
| 2256x1504          | 4         | 0.53%   |
| 3456x2160          | 3         | 0.4%    |
| 3000x2000          | 3         | 0.4%    |
| 1440x900 (WXGA+)   | 3         | 0.4%    |
| 3840x1080          | 2         | 0.26%   |
| 3200x2000          | 2         | 0.26%   |
| 2240x1400          | 2         | 0.26%   |
| 2160x1350          | 2         | 0.26%   |
| 1680x1050 (WSXGA+) | 2         | 0.26%   |
| 1024x768 (XGA)     | 2         | 0.26%   |
| 800x1280           | 1         | 0.13%   |
| 3200x1800 (QHD+)   | 1         | 0.13%   |
| 2880x864           | 1         | 0.13%   |
| 2304x1440          | 1         | 0.13%   |
| 1920x540           | 1         | 0.13%   |
| 1360x768           | 1         | 0.13%   |
| 1024x600           | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 320       | 39.17%  |
| 14      | 125       | 15.3%   |
| 13      | 124       | 15.18%  |
| 27      | 38        | 4.65%   |
| 16      | 36        | 4.41%   |
| 17      | 29        | 3.55%   |
| 24      | 28        | 3.43%   |
| 23      | 18        | 2.2%    |
| 12      | 15        | 1.84%   |
| 34      | 13        | 1.59%   |
| 21      | 13        | 1.59%   |
| 31      | 9         | 1.1%    |
| 11      | 7         | 0.86%   |
| 40      | 6         | 0.73%   |
| 18      | 5         | 0.61%   |
| 20      | 4         | 0.49%   |
| 72      | 3         | 0.37%   |
| 26      | 3         | 0.37%   |
| Unknown | 3         | 0.37%   |
| 84      | 2         | 0.24%   |
| 48      | 2         | 0.24%   |
| 32      | 2         | 0.24%   |
| 29      | 2         | 0.24%   |
| 25      | 2         | 0.24%   |
| 19      | 2         | 0.24%   |
| 54      | 1         | 0.12%   |
| 47      | 1         | 0.12%   |
| 39      | 1         | 0.12%   |
| 28      | 1         | 0.12%   |
| 10      | 1         | 0.12%   |
| 7       | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 534       | 66.09%  |
| 201-300     | 80        | 9.9%    |
| 501-600     | 79        | 9.78%   |
| 351-400     | 42        | 5.2%    |
| 401-500     | 22        | 2.72%   |
| 601-700     | 16        | 1.98%   |
| 701-800     | 15        | 1.86%   |
| 801-900     | 6         | 0.74%   |
| 1501-2000   | 5         | 0.62%   |
| 1001-1500   | 4         | 0.5%    |
| Unknown     | 3         | 0.37%   |
| 901-1000    | 1         | 0.12%   |
| 1-100       | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 554       | 78.25%  |
| 16/10 | 106       | 14.97%  |
| 3/2   | 18        | 2.54%   |
| 21/9  | 15        | 2.12%   |
| 4/3   | 8         | 1.13%   |
| 5/4   | 3         | 0.42%   |
| 32/9  | 2         | 0.28%   |
| 3.33  | 1         | 0.14%   |
| 0.67  | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 324       | 39.66%  |
| 81-90          | 204       | 24.97%  |
| 201-250        | 45        | 5.51%   |
| 71-80          | 43        | 5.26%   |
| 301-350        | 41        | 5.02%   |
| 111-120        | 31        | 3.79%   |
| 351-500        | 26        | 3.18%   |
| 121-130        | 25        | 3.06%   |
| 61-70          | 13        | 1.59%   |
| 151-200        | 13        | 1.59%   |
| 251-300        | 12        | 1.47%   |
| 501-1000       | 10        | 1.22%   |
| 51-60          | 7         | 0.86%   |
| More than 1000 | 6         | 0.73%   |
| 91-100         | 5         | 0.61%   |
| 141-150        | 4         | 0.49%   |
| 131-140        | 3         | 0.37%   |
| Unknown        | 3         | 0.37%   |
| 41-50          | 1         | 0.12%   |
| 1-40           | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 381       | 47.63%  |
| 101-120       | 131       | 16.38%  |
| 161-240       | 120       | 15%     |
| 51-100        | 118       | 14.75%  |
| More than 240 | 44        | 5.5%    |
| 1-50          | 3         | 0.38%   |
| Unknown       | 3         | 0.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 517       | 76.03%  |
| 2     | 140       | 20.59%  |
| 3     | 12        | 1.76%   |
| 0     | 10        | 1.47%   |
| 5     | 1         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 400       | 40.28%  |
| Realtek Semiconductor             | 351       | 35.35%  |
| Qualcomm Atheros                  | 89        | 8.96%   |
| MediaTek                          | 48        | 4.83%   |
| Broadcom                          | 30        | 3.02%   |
| Qualcomm                          | 7         | 0.7%    |
| Lenovo                            | 7         | 0.7%    |
| Broadcom Limited                  | 6         | 0.6%    |
| ASIX Electronics                  | 6         | 0.6%    |
| Sierra Wireless                   | 5         | 0.5%    |
| Xiaomi                            | 4         | 0.4%    |
| TP-Link                           | 4         | 0.4%    |
| ASUSTek Computer                  | 4         | 0.4%    |
| Ralink Technology                 | 3         | 0.3%    |
| Hewlett-Packard                   | 3         | 0.3%    |
| Google                            | 3         | 0.3%    |
| Dell                              | 3         | 0.3%    |
| Samsung Electronics               | 2         | 0.2%    |
| Ralink                            | 2         | 0.2%    |
| Marvell Technology Group          | 2         | 0.2%    |
| Fibocom                           | 2         | 0.2%    |
| Ericsson Business Mobile Networks | 2         | 0.2%    |
| DisplayLink                       | 2         | 0.2%    |
| Microsoft                         | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |
| JMicron Technology                | 1         | 0.1%    |
| Huawei Technologies               | 1         | 0.1%    |
| D-Link System                     | 1         | 0.1%    |
| D-Link                            | 1         | 0.1%    |
| Aquantia                          | 1         | 0.1%    |
| Apple                             | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 205       | 17.28%  |
| Intel Wi-Fi 6 AX201                                               | 59        | 4.97%   |
| Intel Wi-Fi 6 AX200                                               | 48        | 4.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 45        | 3.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 3.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36        | 3.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 36        | 3.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 2.78%   |
| Intel Wireless 8265 / 8275                                        | 32        | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 24        | 2.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 21        | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 19        | 1.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 19        | 1.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 17        | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 17        | 1.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 16        | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 16        | 1.35%   |
| Intel Wireless 8260                                               | 16        | 1.35%   |
| Intel Wireless 7265                                               | 15        | 1.26%   |
| Intel Wireless 7260                                               | 15        | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 14        | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 13        | 1.1%    |
| Realtek Realtek Network controller                                | 11        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 9         | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.76%   |
| Intel Ethernet Connection (13) I219-V                             | 9         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 9         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 0.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 8         | 0.67%   |
| Intel Ethernet Connection (16) I219-V                             | 8         | 0.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 7         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 0.51%   |
| Intel Wireless-AC 9260                                            | 6         | 0.51%   |
| Intel Wireless 3160                                               | 6         | 0.51%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 393       | 56.63%  |
| Realtek Semiconductor             | 114       | 16.43%  |
| Qualcomm Atheros                  | 76        | 10.95%  |
| MediaTek                          | 48        | 6.92%   |
| Broadcom                          | 24        | 3.46%   |
| Broadcom Limited                  | 6         | 0.86%   |
| Sierra Wireless                   | 5         | 0.72%   |
| Qualcomm                          | 5         | 0.72%   |
| ASUSTek Computer                  | 4         | 0.58%   |
| TP-Link                           | 3         | 0.43%   |
| Ralink Technology                 | 3         | 0.43%   |
| Dell                              | 3         | 0.43%   |
| Ralink                            | 2         | 0.29%   |
| Hewlett-Packard                   | 2         | 0.29%   |
| Fibocom                           | 2         | 0.29%   |
| Linksys                           | 1         | 0.14%   |
| Ericsson Business Mobile Networks | 1         | 0.14%   |
| D-Link System                     | 1         | 0.14%   |
| D-Link                            | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 59        | 8.5%    |
| Intel Wi-Fi 6 AX200                                            | 48        | 6.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 45        | 6.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 39        | 5.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 36        | 5.19%   |
| Intel Wireless 8265 / 8275                                     | 32        | 4.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 24        | 3.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 21        | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19        | 2.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 19        | 2.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 17        | 2.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 17        | 2.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 16        | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 2.31%   |
| Intel Wireless 8260                                            | 16        | 2.31%   |
| Intel Wireless 7265                                            | 15        | 2.16%   |
| Intel Wireless 7260                                            | 15        | 2.16%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 14        | 2.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 1.87%   |
| Realtek Realtek Network controller                             | 10        | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 1.44%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 9         | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8         | 1.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 7         | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 0.86%   |
| Intel Wireless-AC 9260                                         | 6         | 0.86%   |
| Intel Wireless 3160                                            | 6         | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 0.86%   |
| Intel Wireless 3165                                            | 5         | 0.72%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 0.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 0.72%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 0.72%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 4         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.43%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 3         | 0.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 294       | 61.12%  |
| Intel                    | 125       | 25.99%  |
| Qualcomm Atheros         | 16        | 3.33%   |
| Broadcom                 | 12        | 2.49%   |
| Lenovo                   | 7         | 1.46%   |
| ASIX Electronics         | 6         | 1.25%   |
| Xiaomi                   | 4         | 0.83%   |
| Google                   | 3         | 0.62%   |
| Samsung Electronics      | 2         | 0.42%   |
| Qualcomm                 | 2         | 0.42%   |
| Marvell Technology Group | 2         | 0.42%   |
| DisplayLink              | 2         | 0.42%   |
| TP-Link                  | 1         | 0.21%   |
| Microsoft                | 1         | 0.21%   |
| JMicron Technology       | 1         | 0.21%   |
| Hewlett-Packard          | 1         | 0.21%   |
| Aquantia                 | 1         | 0.21%   |
| Apple                    | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 205       | 41.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36        | 7.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 6.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 3.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.04%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.84%   |
| Intel Ethernet Connection (13) I219-V                             | 9         | 1.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 1.64%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 1.64%   |
| Intel Ethernet Connection (16) I219-V                             | 8         | 1.64%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 1.23%   |
| Intel Ethernet Connection (10) I219-V                             | 6         | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 1.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 1.02%   |
| Intel Ethernet Connection I219-V                                  | 5         | 1.02%   |
| Intel Ethernet Connection (6) I219-LM                             | 5         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.82%   |
| Realtek Killer E3000 2.5GbE Controller                            | 4         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.82%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 4         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.61%   |
| Lenovo USB-C Dock Ethernet                                        | 3         | 0.61%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.61%   |
| Intel Ethernet Connection (13) I219-LM                            | 3         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.61%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.61%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.41%   |
| Qualcomm FP3                                                      | 2         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.41%   |
| Intel Ethernet Controller I225-LM                                 | 2         | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.41%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.41%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 665       | 59.32%  |
| Ethernet | 453       | 40.41%  |
| Modem    | 2         | 0.18%   |
| Unknown  | 1         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 595       | 84.04%  |
| Ethernet | 113       | 15.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 406       | 60.6%   |
| 1     | 245       | 36.57%  |
| 3     | 12        | 1.79%   |
| 0     | 7         | 1.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 492       | 73%     |
| Yes  | 182       | 27%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 345       | 59.08%  |
| Realtek Semiconductor           | 70        | 11.99%  |
| Qualcomm Atheros Communications | 32        | 5.48%   |
| Lite-On Technology              | 30        | 5.14%   |
| IMC Networks                    | 29        | 4.97%   |
| Foxconn / Hon Hai               | 27        | 4.62%   |
| Broadcom                        | 14        | 2.4%    |
| Realtek                         | 13        | 2.23%   |
| Apple                           | 11        | 1.88%   |
| Opticis                         | 3         | 0.51%   |
| Toshiba                         | 2         | 0.34%   |
| MediaTek                        | 2         | 0.34%   |
| Hewlett-Packard                 | 2         | 0.34%   |
| USI                             | 1         | 0.17%   |
| Dell                            | 1         | 0.17%   |
| Corsair                         | 1         | 0.17%   |
| Cambridge Silicon Radio         | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                         | 127       | 21.75%  |
| Intel Bluetooth wireless interface             | 79        | 13.53%  |
| Realtek Bluetooth Radio                        | 56        | 9.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 56        | 9.59%   |
| Intel AX200 Bluetooth                          | 47        | 8.05%   |
| Foxconn / Hon Hai Wireless_Device              | 23        | 3.94%   |
| Qualcomm Atheros  Bluetooth Device             | 22        | 3.77%   |
| Intel AX210 Bluetooth                          | 19        | 3.25%   |
| Lite-On Bluetooth Device                       | 18        | 3.08%   |
| IMC Networks Wireless_Device                   | 14        | 2.4%    |
| Realtek Bluetooth Radio                        | 13        | 2.23%   |
| Realtek  Bluetooth 4.2 Adapter                 | 9         | 1.54%   |
| Intel Wireless-AC 3168 Bluetooth               | 9         | 1.54%   |
| Lite-On Wireless_Device                        | 8         | 1.37%   |
| IMC Networks Bluetooth Radio                   | 8         | 1.37%   |
| Apple Bluetooth Host Controller                | 7         | 1.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 6         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 5         | 0.86%   |
| IMC Networks Bluetooth Device                  | 5         | 0.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 5         | 0.86%   |
| Apple Bluetooth USB Host Controller            | 4         | 0.68%   |
| Opticis Bluetooth Radio                        | 3         | 0.51%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 3         | 0.51%   |
| Foxconn / Hon Hai Bluetooth Device             | 3         | 0.51%   |
| Broadcom BCM43142 Bluetooth 4.0                | 3         | 0.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter        | 2         | 0.34%   |
| Realtek RTL8821A Bluetooth                     | 2         | 0.34%   |
| Qualcomm Atheros AR3011 Bluetooth              | 2         | 0.34%   |
| MediaTek Wireless_Device                       | 2         | 0.34%   |
| Lite-On Bluetooth Radio                        | 2         | 0.34%   |
| Lite-On Atheros AR3012 Bluetooth               | 2         | 0.34%   |
| Broadcom HP Portable Bumble Bee                | 2         | 0.34%   |
| USI Bluetooth Device                           | 1         | 0.17%   |
| Toshiba Integrated Bluetooth HCI               | 1         | 0.17%   |
| Toshiba Bluetooth Device                       | 1         | 0.17%   |
| Realtek RTL8723B Bluetooth                     | 1         | 0.17%   |
| Qualcomm Atheros Bluetooth (AR3011)            | 1         | 0.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 0.17%   |
| IMC Networks Bluetooth USB Host Controller     | 1         | 0.17%   |
| IMC Networks Bluetooth                         | 1         | 0.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 479       | 55.89%  |
| AMD                                  | 188       | 21.94%  |
| Nvidia                               | 109       | 12.72%  |
| Lenovo                               | 10        | 1.17%   |
| Logitech                             | 9         | 1.05%   |
| C-Media Electronics                  | 9         | 1.05%   |
| Plantronics                          | 6         | 0.7%    |
| Realtek Semiconductor                | 4         | 0.47%   |
| Hewlett-Packard                      | 4         | 0.47%   |
| GN Netcom                            | 4         | 0.47%   |
| Razer USA                            | 3         | 0.35%   |
| Kingston Technology                  | 3         | 0.35%   |
| SteelSeries ApS                      | 2         | 0.23%   |
| Samsung Electronics                  | 2         | 0.23%   |
| Focusrite-Novation                   | 2         | 0.23%   |
| Creative Technology                  | 2         | 0.23%   |
| Blue Microphones                     | 2         | 0.23%   |
| ASUSTek Computer                     | 2         | 0.23%   |
| Asahi Kasei Microsystems             | 2         | 0.23%   |
| Apple                                | 2         | 0.23%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.12%   |
| Samson Technologies                  | 1         | 0.12%   |
| RODE Microphones                     | 1         | 0.12%   |
| Power Delivery                       | 1         | 0.12%   |
| Microsoft                            | 1         | 0.12%   |
| Microchip Technology                 | 1         | 0.12%   |
| Micro Star International             | 1         | 0.12%   |
| JMTek                                | 1         | 0.12%   |
| Huawei Technologies                  | 1         | 0.12%   |
| Google                               | 1         | 0.12%   |
| Corsair                              | 1         | 0.12%   |
| Conexant Systems                     | 1         | 0.12%   |
| Alesis                               | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 165       | 15.48%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 105       | 9.85%   |
| Intel Sunrise Point-LP HD Audio                                            | 83        | 7.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 70        | 6.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 55        | 5.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 35        | 3.28%   |
| Intel Comet Lake PCH-LP cAVS                                               | 29        | 2.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 29        | 2.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 29        | 2.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 26        | 2.44%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 21        | 1.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 20        | 1.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 18        | 1.69%   |
| Intel Comet Lake PCH cAVS                                                  | 18        | 1.69%   |
| Intel Broadwell-U Audio Controller                                         | 18        | 1.69%   |
| Nvidia GA106 High Definition Audio Controller                              | 16        | 1.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 1.5%    |
| Intel 8 Series HD Audio Controller                                         | 16        | 1.5%    |
| Nvidia Audio device                                                        | 13        | 1.22%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 1.22%   |
| Nvidia TU106 High Definition Audio Controller                              | 12        | 1.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 10        | 0.94%   |
| Intel CM238 HD Audio Controller                                            | 9         | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 9         | 0.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 0.84%   |
| Nvidia GA104 High Definition Audio Controller                              | 8         | 0.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 0.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 0.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 0.66%   |
| AMD High Definition Audio Controller                                       | 7         | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 0.47%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 0.47%   |
| AMD FCH Azalia Controller                                                  | 5         | 0.47%   |
| Realtek Semiconductor USB Audio                                            | 4         | 0.38%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 0.38%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 4         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 124       | 30.47%  |
| SK hynix            | 98        | 24.08%  |
| Micron Technology   | 62        | 15.23%  |
| Crucial             | 23        | 5.65%   |
| Kingston            | 17        | 4.18%   |
| A-DATA Technology   | 14        | 3.44%   |
| Unknown             | 9         | 2.21%   |
| Unknown             | 8         | 1.97%   |
| Ramaxel Technology  | 7         | 1.72%   |
| Corsair             | 6         | 1.47%   |
| Team                | 5         | 1.23%   |
| G.Skill             | 4         | 0.98%   |
| Elpida              | 4         | 0.98%   |
| Unknown (ABCD)      | 3         | 0.74%   |
| Smart               | 2         | 0.49%   |
| Goldkey             | 2         | 0.49%   |
| Avant               | 2         | 0.49%   |
| Wilk                | 1         | 0.25%   |
| Transcend           | 1         | 0.25%   |
| Timetec             | 1         | 0.25%   |
| Teikon              | 1         | 0.25%   |
| Smart Brazil        | 1         | 0.25%   |
| Qumo                | 1         | 0.25%   |
| PUSKILL             | 1         | 0.25%   |
| Patriot             | 1         | 0.25%   |
| Nanya Technology    | 1         | 0.25%   |
| Miron               | 1         | 0.25%   |
| Lexar Co Limited    | 1         | 0.25%   |
| Lexar               | 1         | 0.25%   |
| Kllisre             | 1         | 0.25%   |
| High Bridge         | 1         | 0.25%   |
| Hewlett-Packard     | 1         | 0.25%   |
| ASint Technology    | 1         | 0.25%   |
| 4ea5                | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 2.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.86%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 8         | 1.86%   |
| Unknown                                                          | 8         | 1.86%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 1.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 7         | 1.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 1.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 1.4%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 6         | 1.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.16%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 5         | 1.16%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.93%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 4         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.7%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.7%    |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 3         | 0.7%    |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.7%    |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 3         | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.7%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.7%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 3         | 0.7%    |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 3         | 0.7%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.7%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.7%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.7%    |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s          | 3         | 0.7%    |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.47%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.47%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.47%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 2         | 0.47%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.47%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 217       | 63.82%  |
| DDR3   | 47        | 13.82%  |
| LPDDR4 | 24        | 7.06%   |
| LPDDR5 | 17        | 5%      |
| LPDDR3 | 15        | 4.41%   |
| DDR5   | 15        | 4.41%   |
| DDR2   | 4         | 1.18%   |
| SDRAM  | 1         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 276       | 79.08%  |
| Row Of Chips | 67        | 19.2%   |
| DIMM         | 2         | 0.57%   |
| Chip         | 2         | 0.57%   |
| Unknown      | 2         | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 185       | 51.25%  |
| 4096  | 76        | 21.05%  |
| 16384 | 59        | 16.34%  |
| 32768 | 19        | 5.26%   |
| 2048  | 19        | 5.26%   |
| 1024  | 3         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 130       | 35.91%  |
| 2667    | 72        | 19.89%  |
| 1600    | 40        | 11.05%  |
| 2400    | 25        | 6.91%   |
| 2133    | 19        | 5.25%   |
| 6400    | 16        | 4.42%   |
| 4800    | 15        | 4.14%   |
| 4267    | 9         | 2.49%   |
| 4266    | 8         | 2.21%   |
| 1867    | 5         | 1.38%   |
| 3266    | 4         | 1.1%    |
| 1333    | 4         | 1.1%    |
| 8400    | 2         | 0.55%   |
| 1334    | 2         | 0.55%   |
| 933     | 2         | 0.55%   |
| 800     | 2         | 0.55%   |
| Unknown | 2         | 0.55%   |
| 3733    | 1         | 0.28%   |
| 2933    | 1         | 0.28%   |
| 2048    | 1         | 0.28%   |
| 1066    | 1         | 0.28%   |
| 667     | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP Officejet 2620 series | 1         | 50%     |
| Brother DCP-1600         | 1         | 50%     |

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
| Chicony Electronics                    | 163       | 25.96%  |
| IMC Networks                           | 89        | 14.17%  |
| Quanta                                 | 65        | 10.35%  |
| Microdia                               | 55        | 8.76%   |
| Acer                                   | 54        | 8.6%    |
| Realtek Semiconductor                  | 29        | 4.62%   |
| Sunplus Innovation Technology          | 26        | 4.14%   |
| Cheng Uei Precision Industry (Foxlink) | 25        | 3.98%   |
| Syntek                                 | 20        | 3.18%   |
| Luxvisions Innotech Limited            | 20        | 3.18%   |
| Lite-On Technology                     | 14        | 2.23%   |
| Logitech                               | 12        | 1.91%   |
| Sonix Technology                       | 10        | 1.59%   |
| Apple                                  | 10        | 1.59%   |
| Suyin                                  | 5         | 0.8%    |
| Silicon Motion                         | 5         | 0.8%    |
| Tripath Technology                     | 3         | 0.48%   |
| SunplusIT                              | 3         | 0.48%   |
| Alcor Micro                            | 3         | 0.48%   |
| Microsoft                              | 2         | 0.32%   |
| MacroSilicon                           | 2         | 0.32%   |
| Lenovo                                 | 2         | 0.32%   |
| icSpring                               | 2         | 0.32%   |
| USB Camera CS                          | 1         | 0.16%   |
| Primax Electronics                     | 1         | 0.16%   |
| Novatek Microelectronics               | 1         | 0.16%   |
| Importek                               | 1         | 0.16%   |
| Hewlett-Packard                        | 1         | 0.16%   |
| Goodong Industry                       | 1         | 0.16%   |
| Generalplus Technology                 | 1         | 0.16%   |
| ARC International                      | 1         | 0.16%   |
| A4Tech                                 | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 58        | 9.18%   |
| Microdia Integrated_Webcam_HD                        | 35        | 5.54%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 29        | 4.59%   |
| IMC Networks Integrated Camera                       | 24        | 3.8%    |
| Acer Integrated Camera                               | 22        | 3.48%   |
| Realtek Integrated_Webcam_HD                         | 17        | 2.69%   |
| Chicony HD Webcam                                    | 15        | 2.37%   |
| Quanta HD User Facing                                | 13        | 2.06%   |
| Syntek Integrated Camera                             | 12        | 1.9%    |
| Quanta HP HD Camera                                  | 11        | 1.74%   |
| IMC Networks HD Camera                               | 11        | 1.74%   |
| Chicony HP TrueVision HD Camera                      | 9         | 1.42%   |
| Sonix USB2.0 HD UVC WebCam                           | 8         | 1.27%   |
| Quanta HP Wide Vision HD Camera                      | 8         | 1.27%   |
| Chicony Integrated Camera (1280x720@30)              | 8         | 1.27%   |
| Sunplus Integrated_Webcam_HD                         | 7         | 1.11%   |
| Quanta HP TrueVision HD Camera                       | 7         | 1.11%   |
| Lite-On Integrated Camera                            | 7         | 1.11%   |
| Chicony HD User Facing                               | 7         | 1.11%   |
| Quanta HD Webcam                                     | 6         | 0.95%   |
| Chicony HP Wide Vision HD Camera                     | 6         | 0.95%   |
| Chicony HP HD Camera                                 | 6         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 6         | 0.95%   |
| Acer HD Webcam                                       | 6         | 0.95%   |
| Quanta VGA WebCam                                    | 5         | 0.79%   |
| Microdia Integrated_Webcam_FHD                       | 5         | 0.79%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 0.79%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 5         | 0.79%   |
| Chicony EasyCamera                                   | 5         | 0.79%   |
| Chicony ACER HD User Facing                          | 5         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 5         | 0.79%   |
| Apple FaceTime HD Camera                             | 5         | 0.79%   |
| Syntek EasyCamera                                    | 4         | 0.63%   |
| Sunplus Integrated_Webcam_FHD                        | 4         | 0.63%   |
| Quanta ACER HD User Facing                           | 4         | 0.63%   |
| Microdia Integrated Webcam                           | 4         | 0.63%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 4         | 0.63%   |
| Luxvisions Innotech Limited Integrated Camera        | 4         | 0.63%   |
| Logitech StreamCam                                   | 4         | 0.63%   |
| Lite-On HP HD Camera                                 | 4         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 62        | 41.06%  |
| Shenzhen Goodix Technology         | 37        | 24.5%   |
| Validity Sensors                   | 30        | 19.87%  |
| Elan Microelectronics              | 14        | 9.27%   |
| LighTuning Technology              | 3         | 1.99%   |
| Upek                               | 2         | 1.32%   |
| AuthenTec                          | 2         | 1.32%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.66%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 31        | 20.53%  |
| Shenzhen Goodix  Fingerprint Device                                        | 30        | 19.87%  |
| Unknown                                                                    | 15        | 9.93%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 5.96%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 5.96%   |
| Elan ELAN:ARM-M4                                                           | 9         | 5.96%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 4.64%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 3.31%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 3.31%   |
| Elan ELAN:Fingerprint                                                      | 5         | 3.31%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.65%   |
| Synaptics  WBDI                                                            | 4         | 2.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.32%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 1.32%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.32%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.32%   |
| Validity Sensors VFS491                                                    | 1         | 0.66%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.66%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.66%   |
| Synaptics WBDI Device                                                      | 1         | 0.66%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.66%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.66%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.66%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.66%   |
| AuthenTec AES2810                                                          | 1         | 0.66%   |
| AuthenTec AES1600                                                          | 1         | 0.66%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 29        | 46.77%  |
| Broadcom              | 23        | 37.1%   |
| Upek                  | 4         | 6.45%   |
| Lenovo                | 3         | 4.84%   |
| Yubico.com            | 1         | 1.61%   |
| O2 Micro              | 1         | 1.61%   |
| Gemalto (was Gemplus) | 1         | 1.61%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 29        | 46.77%  |
| Broadcom 58200                                                               | 10        | 16.13%  |
| Broadcom 5880                                                                | 6         | 9.68%   |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 8.06%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 6.45%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.84%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.23%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.61%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.61%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.61%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 388       | 57.4%   |
| 1     | 245       | 36.24%  |
| 2     | 36        | 5.33%   |
| 3     | 3         | 0.44%   |
| 5     | 2         | 0.3%    |
| 4     | 2         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 150       | 44.51%  |
| Graphics card            | 75        | 22.26%  |
| Multimedia controller    | 39        | 11.57%  |
| Camera                   | 22        | 6.53%   |
| Net/wireless             | 16        | 4.75%   |
| Chipcard                 | 14        | 4.15%   |
| Card reader              | 7         | 2.08%   |
| Bluetooth                | 4         | 1.19%   |
| Sound                    | 3         | 0.89%   |
| Net/ethernet             | 3         | 0.89%   |
| Communication controller | 2         | 0.59%   |
| Storage                  | 1         | 0.3%    |
| Network                  | 1         | 0.3%    |

