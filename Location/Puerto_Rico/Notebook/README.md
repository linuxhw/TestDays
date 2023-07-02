Linux in Puerto Rico - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Puerto Rico.

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

Total: 131

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Laptop 15-cs2xx... | [58b9a1f862](https://linux-hardware.org/?probe=58b9a1f862) | Jun 13, 2023 |
| Lenovo        | V14-ARE 82DQ                | [318f1f4d2a](https://linux-hardware.org/?probe=318f1f4d2a) | Jun 12, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [0afa6e53d0](https://linux-hardware.org/?probe=0afa6e53d0) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ea06bd5806](https://linux-hardware.org/?probe=ea06bd5806) | May 29, 2023 |
| Dell          | Latitude E6420              | [3a89155791](https://linux-hardware.org/?probe=3a89155791) | May 03, 2023 |
| Sony          | SVE11113FXW                 | [248c7717a4](https://linux-hardware.org/?probe=248c7717a4) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [940cbb6ef0](https://linux-hardware.org/?probe=940cbb6ef0) | Apr 26, 2023 |
| Dell          | Vostro 3550                 | [21111146cd](https://linux-hardware.org/?probe=21111146cd) | Apr 21, 2023 |
| Dell          | Vostro 3550                 | [eaade18ae0](https://linux-hardware.org/?probe=eaade18ae0) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [da0c8e23ed](https://linux-hardware.org/?probe=da0c8e23ed) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [3c3a2da37a](https://linux-hardware.org/?probe=3c3a2da37a) | Apr 02, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [5cf96e41e0](https://linux-hardware.org/?probe=5cf96e41e0) | Mar 30, 2023 |
| Dell          | XPS 13 9370                 | [3f3967267f](https://linux-hardware.org/?probe=3f3967267f) | Mar 26, 2023 |
| HP            | EliteBook 840 G2            | [40bda215a2](https://linux-hardware.org/?probe=40bda215a2) | Mar 11, 2023 |
| GPU Compan... | GWTN156-11                  | [5afd8e3f42](https://linux-hardware.org/?probe=5afd8e3f42) | Mar 04, 2023 |
| HP            | EliteBook 840 G2            | [be9b47dc08](https://linux-hardware.org/?probe=be9b47dc08) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [3c378a3736](https://linux-hardware.org/?probe=3c378a3736) | Mar 02, 2023 |
| GPU Compan... | GWTN156-11                  | [e189c60b09](https://linux-hardware.org/?probe=e189c60b09) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | [3883ba28c7](https://linux-hardware.org/?probe=3883ba28c7) | Mar 01, 2023 |
| HP            | Laptop 17-by3xxx            | [5beb40c486](https://linux-hardware.org/?probe=5beb40c486) | Feb 28, 2023 |
| Valve         | Jupiter                     | [593206879a](https://linux-hardware.org/?probe=593206879a) | Feb 02, 2023 |
| Dell          | Latitude E6420              | [68908b991a](https://linux-hardware.org/?probe=68908b991a) | Jan 30, 2023 |
| Lenovo        | V14-ARE 82DQ                | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| Dell          | Latitude E6420              | [ea94fc4f3b](https://linux-hardware.org/?probe=ea94fc4f3b) | Jan 13, 2023 |
| HP            | 2000                        | [0f801f2309](https://linux-hardware.org/?probe=0f801f2309) | Jan 07, 2023 |
| Dell          | Vostro 3550                 | [0708d07cd4](https://linux-hardware.org/?probe=0708d07cd4) | Dec 28, 2022 |
| Lenovo        | Y50-70 Touch 20349          | [b26dc749a5](https://linux-hardware.org/?probe=b26dc749a5) | Dec 23, 2022 |
| Dell          | Latitude E6420              | [7d592f1759](https://linux-hardware.org/?probe=7d592f1759) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0c94171d5b](https://linux-hardware.org/?probe=0c94171d5b) | Dec 10, 2022 |
| Dell          | Latitude E6420              | [3d516c4ca3](https://linux-hardware.org/?probe=3d516c4ca3) | Dec 06, 2022 |
| ASUSTek       | S500CA                      | [267ffa24d1](https://linux-hardware.org/?probe=267ffa24d1) | Dec 04, 2022 |
| ASUSTek       | S500CA                      | [7145280e9e](https://linux-hardware.org/?probe=7145280e9e) | Dec 03, 2022 |
| Dell          | Latitude E6420              | [251fb963fe](https://linux-hardware.org/?probe=251fb963fe) | Nov 28, 2022 |
| Lenovo        | Yoga 900-13ISK 80MK         | [fe69e51efe](https://linux-hardware.org/?probe=fe69e51efe) | Nov 03, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5dbeb45ba5](https://linux-hardware.org/?probe=5dbeb45ba5) | Oct 06, 2022 |
| Dell          | G5 5505                     | [e26e58afac](https://linux-hardware.org/?probe=e26e58afac) | Sep 08, 2022 |
| Apple         | MacBook4,1                  | [1c9628e804](https://linux-hardware.org/?probe=1c9628e804) | Aug 15, 2022 |
| Apple         | MacBook4,1                  | [12a6ae992a](https://linux-hardware.org/?probe=12a6ae992a) | Aug 14, 2022 |
| HP            | ProBook 450 G5              | [846e1d6c9f](https://linux-hardware.org/?probe=846e1d6c9f) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 20RA004WUS     | [b140ac0aea](https://linux-hardware.org/?probe=b140ac0aea) | Aug 07, 2022 |
| Dell          | Precision M4700             | [25efd53898](https://linux-hardware.org/?probe=25efd53898) | Aug 05, 2022 |
| Apple         | MacBook4,1                  | [96645b0a94](https://linux-hardware.org/?probe=96645b0a94) | Aug 04, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [3f1e6ca5cb](https://linux-hardware.org/?probe=3f1e6ca5cb) | Jul 29, 2022 |
| Apple         | MacBook4,1                  | [012b0c7fa9](https://linux-hardware.org/?probe=012b0c7fa9) | Jul 23, 2022 |
| Apple         | MacBook4,1                  | [9122678102](https://linux-hardware.org/?probe=9122678102) | Jul 21, 2022 |
| Apple         | MacBook4,1                  | [69d676f7be](https://linux-hardware.org/?probe=69d676f7be) | Jul 12, 2022 |
| Apple         | MacBook4,1                  | [9d8195a435](https://linux-hardware.org/?probe=9d8195a435) | Jul 12, 2022 |
| Dell          | Venue 11 Pro 7130 MS        | [a42903b516](https://linux-hardware.org/?probe=a42903b516) | Jul 10, 2022 |
| Dell          | Venue 11 Pro 7130 MS        | [404e81318c](https://linux-hardware.org/?probe=404e81318c) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Dell          | Vostro 3550                 | [d0cfec8d80](https://linux-hardware.org/?probe=d0cfec8d80) | Jul 04, 2022 |
| Apple         | MacBookPro5,1               | [ac53d2f956](https://linux-hardware.org/?probe=ac53d2f956) | Jul 02, 2022 |
| Apple         | MacBookPro5,1               | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| Dell          | Vostro 3550                 | [9eaa432fcd](https://linux-hardware.org/?probe=9eaa432fcd) | Jun 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [074f1f75dc](https://linux-hardware.org/?probe=074f1f75dc) | Apr 20, 2022 |
| Dell          | Latitude E6330              | [1911200c56](https://linux-hardware.org/?probe=1911200c56) | Mar 23, 2022 |
| Dell          | Vostro 3550                 | [fd3185704d](https://linux-hardware.org/?probe=fd3185704d) | Mar 21, 2022 |
| Dell          | Inspiron 17-7778            | [bcc52b2596](https://linux-hardware.org/?probe=bcc52b2596) | Mar 17, 2022 |
| Toshiba       | Satellite P755              | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a1ecd8a3cb](https://linux-hardware.org/?probe=a1ecd8a3cb) | Feb 12, 2022 |
| TUXEDO        | Aura 15 Gen1                | [832b48c46d](https://linux-hardware.org/?probe=832b48c46d) | Feb 11, 2022 |
| Dell          | Vostro 3550                 | [86dbaf1d07](https://linux-hardware.org/?probe=86dbaf1d07) | Jan 27, 2022 |
| Sony          | VGN-CS320J                  | [1b74edca8c](https://linux-hardware.org/?probe=1b74edca8c) | Dec 27, 2021 |
| Sony          | VGN-CS320J                  | [9f1e770843](https://linux-hardware.org/?probe=9f1e770843) | Dec 22, 2021 |
| Sony          | VGN-CS320J                  | [7143ced3cd](https://linux-hardware.org/?probe=7143ced3cd) | Dec 20, 2021 |
| Apple         | MacBook4,1                  | [7bf355c3c1](https://linux-hardware.org/?probe=7bf355c3c1) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | [cfa6005bc4](https://linux-hardware.org/?probe=cfa6005bc4) | Dec 09, 2021 |
| HP            | ENVY Laptop 17m-bw0xxx      | [9ec292c9d9](https://linux-hardware.org/?probe=9ec292c9d9) | Oct 25, 2021 |
| HP            | EliteBook 840 G2            | [8649bba9b6](https://linux-hardware.org/?probe=8649bba9b6) | Oct 22, 2021 |
| HP            | EliteBook 840 G2            | [fede248f75](https://linux-hardware.org/?probe=fede248f75) | Oct 19, 2021 |
| HP            | ProBook 6450b               | [518e694864](https://linux-hardware.org/?probe=518e694864) | Oct 19, 2021 |
| Acer          | Swift SF315-52              | [7ecda0a147](https://linux-hardware.org/?probe=7ecda0a147) | Sep 23, 2021 |
| GPU Compan... | GWTN156-9                   | [a9ac79c22a](https://linux-hardware.org/?probe=a9ac79c22a) | Sep 21, 2021 |
| Dell          | Vostro 3550                 | [686eb55129](https://linux-hardware.org/?probe=686eb55129) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [d120a0016d](https://linux-hardware.org/?probe=d120a0016d) | Aug 05, 2021 |
| Dell          | Inspiron N5110              | [9ad69ca6ad](https://linux-hardware.org/?probe=9ad69ca6ad) | Jul 27, 2021 |
| Dell          | Vostro 3550                 | [75fd544183](https://linux-hardware.org/?probe=75fd544183) | Jul 26, 2021 |
| Dell          | Inspiron N5110              | [a3b055840b](https://linux-hardware.org/?probe=a3b055840b) | Jul 13, 2021 |
| HP            | EliteBook 840 G2            | [cbcf0ae65d](https://linux-hardware.org/?probe=cbcf0ae65d) | Jul 07, 2021 |
| Dell          | Vostro 3550                 | [c3b8ac12be](https://linux-hardware.org/?probe=c3b8ac12be) | Jul 07, 2021 |
| Dell          | Inspiron N5110              | [3a88077121](https://linux-hardware.org/?probe=3a88077121) | Jul 07, 2021 |
| HP            | EliteBook 840 G2            | [17a65dfb0e](https://linux-hardware.org/?probe=17a65dfb0e) | Jul 06, 2021 |
| Acer          | Aspire E5-571               | [5af810dc36](https://linux-hardware.org/?probe=5af810dc36) | Jul 04, 2021 |
| HP            | EliteBook 840 G2            | [675992d5f9](https://linux-hardware.org/?probe=675992d5f9) | Jul 04, 2021 |
| Acer          | Aspire E5-571               | [4782df79ce](https://linux-hardware.org/?probe=4782df79ce) | Jul 02, 2021 |
| HP            | ProBook 6560b               | [806dfcb6f0](https://linux-hardware.org/?probe=806dfcb6f0) | Jul 01, 2021 |
| HP            | ProBook 6450b               | [a8689c5d60](https://linux-hardware.org/?probe=a8689c5d60) | Jun 25, 2021 |
| HP            | EliteBook 840 G2            | [fed4ef6298](https://linux-hardware.org/?probe=fed4ef6298) | Jun 23, 2021 |
| HP            | EliteBook 840 G2            | [14e1d81078](https://linux-hardware.org/?probe=14e1d81078) | Jun 23, 2021 |
| HP            | ProBook 6450b               | [b4c7a0fd32](https://linux-hardware.org/?probe=b4c7a0fd32) | Jun 21, 2021 |
| HP            | Laptop 15-dw0xxx            | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| HP            | Laptop 15-dw0xxx            | [95fdac8e1c](https://linux-hardware.org/?probe=95fdac8e1c) | Jun 08, 2021 |
| Lenovo        | G50-45 80E3                 | [6b2ff5fb12](https://linux-hardware.org/?probe=6b2ff5fb12) | May 25, 2021 |
| HP            | ENVY dv7                    | [651a68adc6](https://linux-hardware.org/?probe=651a68adc6) | May 24, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| Lenovo        | ThinkPad T410 2516ADU       | [5feb962d24](https://linux-hardware.org/?probe=5feb962d24) | Apr 07, 2021 |
| MSI           | GF65 Thin 10SDR             | [332f4238da](https://linux-hardware.org/?probe=332f4238da) | Mar 09, 2021 |
| HP            | Laptop 14-dk1xxx            | [48d2054858](https://linux-hardware.org/?probe=48d2054858) | Feb 16, 2021 |
| MSI           | GF65 Thin 10SDR             | [2140e64244](https://linux-hardware.org/?probe=2140e64244) | Feb 13, 2021 |
| ASUSTek       | K53E                        | [0523ff890c](https://linux-hardware.org/?probe=0523ff890c) | Jan 15, 2021 |
| MSI           | GF65 Thin 10SDR             | [5780c56d1e](https://linux-hardware.org/?probe=5780c56d1e) | Jan 06, 2021 |
| Toshiba       | Satellite C55-C             | [ecaae6f562](https://linux-hardware.org/?probe=ecaae6f562) | Jan 05, 2021 |
| AMI           | Intel                       | [0ea3da73ad](https://linux-hardware.org/?probe=0ea3da73ad) | Jan 04, 2021 |
| AZW           | GT-R                        | [19b47cf9f6](https://linux-hardware.org/?probe=19b47cf9f6) | Dec 16, 2020 |
| Dell          | Inspiron 11-3168            | [9464486b83](https://linux-hardware.org/?probe=9464486b83) | Nov 22, 2020 |
| Dell          | Latitude E6410              | [d188c9653d](https://linux-hardware.org/?probe=d188c9653d) | Nov 07, 2020 |
| Dell          | Latitude E6410              | [caf34f9e21](https://linux-hardware.org/?probe=caf34f9e21) | Nov 02, 2020 |
| Apple         | MacBookPro8,1               | [9d734dee6e](https://linux-hardware.org/?probe=9d734dee6e) | Sep 30, 2020 |
| HP            | ENVY dv7                    | [e5448099f1](https://linux-hardware.org/?probe=e5448099f1) | Sep 27, 2020 |
| HP            | ENVY dv7                    | [a027a185e5](https://linux-hardware.org/?probe=a027a185e5) | Sep 23, 2020 |
| HP            | ENVY dv7                    | [ff87d18b2b](https://linux-hardware.org/?probe=ff87d18b2b) | Sep 21, 2020 |
| Acer          | Swift SF314-51              | [ff4068d40b](https://linux-hardware.org/?probe=ff4068d40b) | Jul 31, 2020 |
| HP            | Laptop 15-dy1xxx            | [f9271f6dae](https://linux-hardware.org/?probe=f9271f6dae) | Jul 09, 2020 |
| HP            | ENVY dv7                    | [2ae56a2828](https://linux-hardware.org/?probe=2ae56a2828) | May 24, 2020 |
| HP            | Compaq nc6400 (RB516UT#A... | [f950094ff1](https://linux-hardware.org/?probe=f950094ff1) | May 21, 2020 |
| Sony          | VPCEA36FX                   | [98ba3a8ad5](https://linux-hardware.org/?probe=98ba3a8ad5) | May 17, 2020 |
| Sony          | VPCEA36FX                   | [572157356f](https://linux-hardware.org/?probe=572157356f) | May 13, 2020 |
| ASUSTek       | X540SAA                     | [8805cd4168](https://linux-hardware.org/?probe=8805cd4168) | Apr 16, 2020 |
| HP            | ENVY dv7                    | [e2de1ae596](https://linux-hardware.org/?probe=e2de1ae596) | Apr 04, 2020 |
| HP            | ENVY dv7                    | [97ae3dc919](https://linux-hardware.org/?probe=97ae3dc919) | Mar 14, 2020 |
| Acer          | Aspire E5-575               | [3d3261ccc3](https://linux-hardware.org/?probe=3d3261ccc3) | Mar 09, 2020 |
| Dell          | Inspiron 5559               | [aca2204df4](https://linux-hardware.org/?probe=aca2204df4) | Mar 01, 2020 |
| Dell          | Inspiron 5559               | [7c094d733b](https://linux-hardware.org/?probe=7c094d733b) | Feb 28, 2020 |
| HP            | Notebook                    | [80f2a12798](https://linux-hardware.org/?probe=80f2a12798) | Feb 28, 2020 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [d24fc7f682](https://linux-hardware.org/?probe=d24fc7f682) | Jan 30, 2019 |
| Toshiba       | Satellite L655              | [525707b787](https://linux-hardware.org/?probe=525707b787) | Jan 21, 2019 |
| Toshiba       | Satellite L655              | [a7616fb055](https://linux-hardware.org/?probe=a7616fb055) | Jan 21, 2019 |
| Dell          | Inspiron MP061              | [113fc7a00d](https://linux-hardware.org/?probe=113fc7a00d) | Jul 15, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 16        | 20.51%  |
| Ubuntu 22.04                 | 8         | 10.26%  |
| Ubuntu 18.04                 | 5         | 6.41%   |
| Ubuntu 22.10                 | 2         | 2.56%   |
| Ubuntu 21.10                 | 2         | 2.56%   |
| OpenMandriva 4.3             | 2         | 2.56%   |
| OpenMandriva 4.2             | 2         | 2.56%   |
| Linux Mint 21                | 2         | 2.56%   |
| Linux Mint 19.3              | 2         | 2.56%   |
| Fedora 38                    | 2         | 2.56%   |
| Fedora 37                    | 2         | 2.56%   |
| Debian 11                    | 2         | 2.56%   |
| BlackPanther 18.1            | 2         | 2.56%   |
| Arch Rolling                 | 2         | 2.56%   |
| Zorin 16                     | 1         | 1.28%   |
| Xubuntu 20.04                | 1         | 1.28%   |
| Ubuntu Unity 20.04           | 1         | 1.28%   |
| Ubuntu MATE 20.04            | 1         | 1.28%   |
| Ubuntu 23.04                 | 1         | 1.28%   |
| Ubuntu 19.10                 | 1         | 1.28%   |
| SteamOS 3.4.4                | 1         | 1.28%   |
| ROSA R10                     | 1         | 1.28%   |
| Pop!_OS 22.04                | 1         | 1.28%   |
| Peppermint 9                 | 1         | 1.28%   |
| Parrot 5.0                   | 1         | 1.28%   |
| Parrot 4.11                  | 1         | 1.28%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 1.28%   |
| openSUSE Leap-15.2           | 1         | 1.28%   |
| OpenMandriva 4.90            | 1         | 1.28%   |
| OpenMandriva 4.50            | 1         | 1.28%   |
| OpenMandriva 23.01           | 1         | 1.28%   |
| Linux Mint 21.1              | 1         | 1.28%   |
| Linux Mint 20.1              | 1         | 1.28%   |
| KDE neon 20.04               | 1         | 1.28%   |
| Fedora 36                    | 1         | 1.28%   |
| Fedora 33                    | 1         | 1.28%   |
| Endless 3.7.8                | 1         | 1.28%   |
| EndeavourOS Rolling          | 1         | 1.28%   |
| Elementary 7                 | 1         | 1.28%   |
| Debian 10                    | 1         | 1.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 31        | 42.47%  |
| OpenMandriva | 7         | 9.59%   |
| Fedora       | 6         | 8.22%   |
| Linux Mint   | 5         | 6.85%   |
| Debian       | 3         | 4.11%   |
| Parrot       | 2         | 2.74%   |
| openSUSE     | 2         | 2.74%   |
| BlackPanther | 2         | 2.74%   |
| Arch         | 2         | 2.74%   |
| Zorin        | 1         | 1.37%   |
| Xubuntu      | 1         | 1.37%   |
| Ubuntu Unity | 1         | 1.37%   |
| Ubuntu MATE  | 1         | 1.37%   |
| SteamOS      | 1         | 1.37%   |
| ROSA         | 1         | 1.37%   |
| Pop!_OS      | 1         | 1.37%   |
| Peppermint   | 1         | 1.37%   |
| KDE neon     | 1         | 1.37%   |
| Endless      | 1         | 1.37%   |
| EndeavourOS  | 1         | 1.37%   |
| Elementary   | 1         | 1.37%   |
| AlmaLinux    | 1         | 1.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.8.0-59-generic         | 3         | 3.23%   |
| 6.3.6-200.fc38.x86_64    | 2         | 2.15%   |
| 5.8.0-55-generic         | 2         | 2.15%   |
| 5.4.0-58-generic         | 2         | 2.15%   |
| 5.19.0-42-generic        | 2         | 2.15%   |
| 5.19.0-38-generic        | 2         | 2.15%   |
| 5.16.7-desktop-1omv4003  | 2         | 2.15%   |
| 5.15.0-58-generic        | 2         | 2.15%   |
| 5.15.0-46-generic        | 2         | 2.15%   |
| 5.15.0-25-generic        | 2         | 2.15%   |
| 5.13.0-35-generic        | 2         | 2.15%   |
| 5.11.0-38-generic        | 2         | 2.15%   |
| 5.11.0-27-generic        | 2         | 2.15%   |
| 5.10.14-desktop-1omv4002 | 2         | 2.15%   |
| 5.10.0-19-amd64          | 2         | 2.15%   |
| 6.2.8-200.fc37.x86_64    | 1         | 1.08%   |
| 6.2.6-76060206-generic   | 1         | 1.08%   |
| 6.2.12-arch1-1           | 1         | 1.08%   |
| 6.1.1-desktop-1omv2290   | 1         | 1.08%   |
| 5.9.16-200.fc33.x86_64   | 1         | 1.08%   |
| 5.8.0-63-generic         | 1         | 1.08%   |
| 5.6.14-desktop-2bP       | 1         | 1.08%   |
| 5.4.0-84-generic         | 1         | 1.08%   |
| 5.4.0-77-generic         | 1         | 1.08%   |
| 5.4.0-73-generic         | 1         | 1.08%   |
| 5.4.0-70-generic         | 1         | 1.08%   |
| 5.4.0-62-generic         | 1         | 1.08%   |
| 5.4.0-60-generic         | 1         | 1.08%   |
| 5.4.0-55-generic         | 1         | 1.08%   |
| 5.4.0-52-generic         | 1         | 1.08%   |
| 5.4.0-48-generic         | 1         | 1.08%   |
| 5.4.0-47-generic         | 1         | 1.08%   |
| 5.4.0-40-generic         | 1         | 1.08%   |
| 5.4.0-29-generic         | 1         | 1.08%   |
| 5.3.6-050306-generic     | 1         | 1.08%   |
| 5.3.18-lp152.57-default  | 1         | 1.08%   |
| 5.3.0-41-generic         | 1         | 1.08%   |
| 5.3.0-40-generic         | 1         | 1.08%   |
| 5.3.0-28-generic         | 1         | 1.08%   |
| 5.19.7-300.fc37.x86_64   | 1         | 1.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 13        | 17.11%  |
| 5.15.0  | 7         | 9.21%   |
| 5.13.0  | 7         | 9.21%   |
| 5.19.0  | 5         | 6.58%   |
| 5.11.0  | 5         | 6.58%   |
| 5.8.0   | 4         | 5.26%   |
| 5.3.0   | 3         | 3.95%   |
| 5.10.0  | 3         | 3.95%   |
| 4.15.0  | 3         | 3.95%   |
| 6.3.6   | 2         | 2.63%   |
| 5.16.7  | 2         | 2.63%   |
| 5.10.14 | 2         | 2.63%   |
| 6.2.8   | 1         | 1.32%   |
| 6.2.6   | 1         | 1.32%   |
| 6.2.12  | 1         | 1.32%   |
| 6.1.1   | 1         | 1.32%   |
| 5.9.16  | 1         | 1.32%   |
| 5.6.14  | 1         | 1.32%   |
| 5.3.6   | 1         | 1.32%   |
| 5.3.18  | 1         | 1.32%   |
| 5.19.7  | 1         | 1.32%   |
| 5.18.6  | 1         | 1.32%   |
| 5.18.15 | 1         | 1.32%   |
| 5.18.12 | 1         | 1.32%   |
| 5.18.0  | 1         | 1.32%   |
| 5.15.59 | 1         | 1.32%   |
| 5.14.0  | 1         | 1.32%   |
| 5.12.4  | 1         | 1.32%   |
| 5.11.16 | 1         | 1.32%   |
| 4.9.60  | 1         | 1.32%   |
| 4.19.0  | 1         | 1.32%   |
| 4.18.16 | 1         | 1.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 13        | 17.33%  |
| 5.15    | 8         | 10.67%  |
| 5.13    | 7         | 9.33%   |
| 5.19    | 6         | 8%      |
| 5.11    | 6         | 8%      |
| 5.3     | 5         | 6.67%   |
| 5.10    | 5         | 6.67%   |
| 5.8     | 4         | 5.33%   |
| 6.2     | 3         | 4%      |
| 5.18    | 3         | 4%      |
| 4.15    | 3         | 4%      |
| 6.3     | 2         | 2.67%   |
| 5.16    | 2         | 2.67%   |
| 6.1     | 1         | 1.33%   |
| 5.9     | 1         | 1.33%   |
| 5.6     | 1         | 1.33%   |
| 5.14    | 1         | 1.33%   |
| 5.12    | 1         | 1.33%   |
| 4.9     | 1         | 1.33%   |
| 4.19    | 1         | 1.33%   |
| 4.18    | 1         | 1.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 65        | 97.01%  |
| i686   | 2         | 2.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 39        | 55.71%  |
| KDE5       | 14        | 20%     |
| MATE       | 4         | 5.71%   |
| X-Cinnamon | 3         | 4.29%   |
| XFCE       | 2         | 2.86%   |
| i3         | 2         | 2.86%   |
| Unknown    | 2         | 2.86%   |
| Unity      | 1         | 1.43%   |
| Pantheon   | 1         | 1.43%   |
| LXDE       | 1         | 1.43%   |
| KDE4       | 1         | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 55        | 77.46%  |
| Wayland | 16        | 22.54%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 38        | 52.78%  |
| GDM3    | 16        | 22.22%  |
| SDDM    | 8         | 11.11%  |
| GDM     | 5         | 6.94%   |
| TDM     | 2         | 2.78%   |
| LightDM | 2         | 2.78%   |
| KDM     | 1         | 1.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 58        | 85.29%  |
| Unknown | 5         | 7.35%   |
| es_PR   | 4         | 5.88%   |
| C       | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 37        | 54.41%  |
| EFI  | 31        | 45.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 48        | 67.61%  |
| Btrfs   | 9         | 12.68%  |
| Overlay | 8         | 11.27%  |
| Tmpfs   | 2         | 2.82%   |
| Unknown | 2         | 2.82%   |
| Zfs     | 1         | 1.41%   |
| Xfs     | 1         | 1.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 45        | 62.5%   |
| GPT     | 23        | 31.94%  |
| MBR     | 4         | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 82.86%  |
| Yes       | 12        | 17.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 51        | 73.91%  |
| Yes       | 18        | 26.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 19        | 28.36%  |
| Dell             | 15        | 22.39%  |
| Lenovo           | 8         | 11.94%  |
| ASUSTek Computer | 5         | 7.46%   |
| Acer             | 4         | 5.97%   |
| Toshiba          | 3         | 4.48%   |
| Sony             | 3         | 4.48%   |
| Apple            | 3         | 4.48%   |
| GPU Company      | 2         | 2.99%   |
| Valve            | 1         | 1.49%   |
| TUXEDO           | 1         | 1.49%   |
| MSI              | 1         | 1.49%   |
| AZW              | 1         | 1.49%   |
| AMI              | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Vostro 3550                         | 3         | 4.48%   |
| Valve Jupiter                            | 1         | 1.49%   |
| TUXEDO Aura 15 Gen1                      | 1         | 1.49%   |
| Toshiba Satellite P755                   | 1         | 1.49%   |
| Toshiba Satellite L655                   | 1         | 1.49%   |
| Toshiba Satellite C55-C                  | 1         | 1.49%   |
| Sony VPCEA36FX                           | 1         | 1.49%   |
| Sony VGN-CS320J                          | 1         | 1.49%   |
| Sony SVE11113FXW                         | 1         | 1.49%   |
| MSI GF65 Thin 10SDR                      | 1         | 1.49%   |
| Lenovo Yoga 900-13ISK 80MK               | 1         | 1.49%   |
| Lenovo Y50-70 Touch 20349                | 1         | 1.49%   |
| Lenovo V14-ARE 82DQ                      | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0000US | 1         | 1.49%   |
| Lenovo ThinkPad T410 2516ADU             | 1         | 1.49%   |
| Lenovo ThinkPad E14 20RA004WUS           | 1         | 1.49%   |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 1.49%   |
| Lenovo G50-45 80E3                       | 1         | 1.49%   |
| HP Stream Laptop 14-CB1xxx               | 1         | 1.49%   |
| HP ProBook 6560b                         | 1         | 1.49%   |
| HP ProBook 6450b                         | 1         | 1.49%   |
| HP ProBook 450 G5                        | 1         | 1.49%   |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 1.49%   |
| HP Pavilion Laptop 15-cs2xxx             | 1         | 1.49%   |
| HP Pavilion Laptop 15-cs0xxx             | 1         | 1.49%   |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 1         | 1.49%   |
| HP Notebook                              | 1         | 1.49%   |
| HP Laptop 17-by3xxx                      | 1         | 1.49%   |
| HP Laptop 15-dy1xxx                      | 1         | 1.49%   |
| HP Laptop 15-dw0xxx                      | 1         | 1.49%   |
| HP Laptop 14-dk1xxx                      | 1         | 1.49%   |
| HP ENVY Laptop 17m-bw0xxx                | 1         | 1.49%   |
| HP ENVY Laptop 17-ce1xxx                 | 1         | 1.49%   |
| HP ENVY dv7                              | 1         | 1.49%   |
| HP EliteBook 840 G2                      | 1         | 1.49%   |
| HP Compaq nc6400 (RB516UT#ABA)           | 1         | 1.49%   |
| HP 2000                                  | 1         | 1.49%   |
| GPU Company GWTN156-9                    | 1         | 1.49%   |
| GPU Company GWTN156-11                   | 1         | 1.49%   |
| Dell XPS 13 9370                         | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 5         | 7.46%   |
| HP Pavilion            | 4         | 5.97%   |
| HP Laptop              | 4         | 5.97%   |
| Toshiba Satellite      | 3         | 4.48%   |
| Lenovo ThinkPad        | 3         | 4.48%   |
| HP ProBook             | 3         | 4.48%   |
| HP ENVY                | 3         | 4.48%   |
| Dell Vostro            | 3         | 4.48%   |
| Dell Latitude          | 3         | 4.48%   |
| Acer Swift             | 2         | 2.99%   |
| Acer Aspire            | 2         | 2.99%   |
| Valve Jupiter          | 1         | 1.49%   |
| TUXEDO Aura            | 1         | 1.49%   |
| Sony VPCEA36FX         | 1         | 1.49%   |
| Sony VGN-CS320J        | 1         | 1.49%   |
| Sony SVE11113FXW       | 1         | 1.49%   |
| MSI GF65               | 1         | 1.49%   |
| Lenovo Yoga            | 1         | 1.49%   |
| Lenovo Y50-70          | 1         | 1.49%   |
| Lenovo V14-ARE         | 1         | 1.49%   |
| Lenovo IdeaPad         | 1         | 1.49%   |
| Lenovo G50-45          | 1         | 1.49%   |
| HP Stream              | 1         | 1.49%   |
| HP Notebook            | 1         | 1.49%   |
| HP EliteBook           | 1         | 1.49%   |
| HP Compaq              | 1         | 1.49%   |
| HP 2000                | 1         | 1.49%   |
| GPU Company GWTN156-9  | 1         | 1.49%   |
| GPU Company GWTN156-11 | 1         | 1.49%   |
| Dell XPS               | 1         | 1.49%   |
| Dell Venue             | 1         | 1.49%   |
| Dell Precision         | 1         | 1.49%   |
| Dell G5                | 1         | 1.49%   |
| AZW GT-R               | 1         | 1.49%   |
| ASUS X540SAA           | 1         | 1.49%   |
| ASUS VivoBook          | 1         | 1.49%   |
| ASUS S500CA            | 1         | 1.49%   |
| ASUS ROG               | 1         | 1.49%   |
| ASUS K53E              | 1         | 1.49%   |
| Apple MacBookPro8      | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 10        | 14.93%  |
| 2011 | 10        | 14.93%  |
| 2020 | 9         | 13.43%  |
| 2015 | 6         | 8.96%   |
| 2012 | 6         | 8.96%   |
| 2018 | 4         | 5.97%   |
| 2016 | 4         | 5.97%   |
| 2010 | 4         | 5.97%   |
| 2021 | 3         | 4.48%   |
| 2014 | 3         | 4.48%   |
| 2017 | 2         | 2.99%   |
| 2009 | 2         | 2.99%   |
| 2022 | 1         | 1.49%   |
| 2008 | 1         | 1.49%   |
| 2006 | 1         | 1.49%   |
| 2005 | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 67        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 60        | 89.55%  |
| Enabled  | 7         | 10.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 67        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 27        | 38.03%  |
| 3.01-4.0   | 16        | 22.54%  |
| 8.01-16.0  | 15        | 21.13%  |
| 16.01-24.0 | 10        | 14.08%  |
| 1.01-2.0   | 3         | 4.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 41        | 49.4%   |
| 2.01-3.0 | 17        | 20.48%  |
| 3.01-4.0 | 13        | 15.66%  |
| 4.01-8.0 | 8         | 9.64%   |
| 0.51-1.0 | 4         | 4.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 67.61%  |
| 2      | 16        | 22.54%  |
| 3      | 5         | 7.04%   |
| 4      | 1         | 1.41%   |
| 0      | 1         | 1.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 64.71%  |
| Yes       | 24        | 35.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 76.12%  |
| No        | 16        | 23.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 98.51%  |
| No        | 1         | 1.49%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 77.61%  |
| No        | 15        | 22.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Puerto Rico | 67        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San Juan      | 36        | 50.7%   |
| Bayamón      | 11        | 15.49%  |
| Carolina      | 5         | 7.04%   |
| Ponce         | 4         | 5.63%   |
| Lares         | 3         | 4.23%   |
| Cayey         | 2         | 2.82%   |
| Caguas        | 2         | 2.82%   |
| Santa Isabel  | 1         | 1.41%   |
| San Sebastian | 1         | 1.41%   |
| Sabana Grande | 1         | 1.41%   |
| Rio Grande    | 1         | 1.41%   |
| Guaynabo      | 1         | 1.41%   |
| Guayama       | 1         | 1.41%   |
| Cabo Rojo     | 1         | 1.41%   |
| Arecibo       | 1         | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 18     | 16.85%  |
| Hitachi             | 10        | 26     | 11.24%  |
| Toshiba             | 9         | 9      | 10.11%  |
| Crucial             | 8         | 15     | 8.99%   |
| Unknown             | 7         | 11     | 7.87%   |
| SK hynix            | 6         | 8      | 6.74%   |
| Seagate             | 6         | 10     | 6.74%   |
| SanDisk             | 5         | 5      | 5.62%   |
| Samsung Electronics | 4         | 5      | 4.49%   |
| Micron Technology   | 2         | 4      | 2.25%   |
| Kingston            | 2         | 3      | 2.25%   |
| Intel               | 2         | 3      | 2.25%   |
| External            | 2         | 5      | 2.25%   |
| A-DATA Technology   | 2         | 2      | 2.25%   |
| W800SH              | 1         | 1      | 1.12%   |
| Silicon Motion      | 1         | 1      | 1.12%   |
| PNY                 | 1         | 1      | 1.12%   |
| Patriot             | 1         | 4      | 1.12%   |
| KingSpec            | 1         | 1      | 1.12%   |
| HGST                | 1         | 1      | 1.12%   |
| China               | 1         | 2      | 1.12%   |
| Axiom               | 1         | 4      | 1.12%   |
| Unknown             | 1         | 1      | 1.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB                | 4         | 4.3%    |
| WDC WD5000LPVT-22G33T0 500GB                | 3         | 3.23%   |
| Hitachi HTS547550A9E384 500GB               | 3         | 3.23%   |
| Crucial CT240M500SSD1 240GB                 | 3         | 3.23%   |
| WDC WD2500BEVS-60UST0 250GB                 | 2         | 2.15%   |
| WDC WD10SPZX-60Z10T0 1TB                    | 2         | 2.15%   |
| Unknown MMC Card  2GB                       | 2         | 2.15%   |
| Unknown MMC Card  128GB                     | 2         | 2.15%   |
| Toshiba MQ04ABF100 1TB                      | 2         | 2.15%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 2.15%   |
| Toshiba MK3261GSYN 320GB                    | 2         | 2.15%   |
| Seagate ST500LM012 HN-M500MBB 500GB         | 2         | 2.15%   |
| Hitachi HTS543232A7A384 320GB               | 2         | 2.15%   |
| External USB3.0 128GB SSD                   | 2         | 2.15%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 1.08%   |
| WDC WDBNCE0010PNC 1TB SSD                   | 1         | 1.08%   |
| WDC WD5000BPVT-75HXZT1 500GB                | 1         | 1.08%   |
| WDC WD10SPZX-21Z10T0 1TB                    | 1         | 1.08%   |
| WDC WD10SPCX-75KHST0 1TB                    | 1         | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1.08%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB        | 1         | 1.08%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB        | 1         | 1.08%   |
| W800SH 512GB SSD                            | 1         | 1.08%   |
| Unknown MMC Card  64GB                      | 1         | 1.08%   |
| Unknown MMC Card  10GB                      | 1         | 1.08%   |
| Unknown HBG4a2  32GB                        | 1         | 1.08%   |
| Unknown DA4064  64GB                        | 1         | 1.08%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1.08%   |
| Toshiba MK3276GSX 320GB                     | 1         | 1.08%   |
| Toshiba MK3254GSY 320GB                     | 1         | 1.08%   |
| SK hynix PC401 NVMe Solid State Drive 256GB | 1         | 1.08%   |
| SK hynix NVMe SSD Drive 256GB               | 1         | 1.08%   |
| SK hynix BC511 NVMe 256GB                   | 1         | 1.08%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 1.08%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1.08%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB     | 1         | 1.08%   |
| Silicon Motion 256GB                        | 1         | 1.08%   |
| Seagate ST98823AS 80GB                      | 1         | 1.08%   |
| Seagate ST9500420AS 500GB                   | 1         | 1.08%   |
| Seagate ST1000LM048-2E7172 1TB              | 1         | 1.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 12     | 29.73%  |
| Hitachi | 10        | 26     | 27.03%  |
| Toshiba | 9         | 9      | 24.32%  |
| Seagate | 6         | 10     | 16.22%  |
| HGST    | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 8         | 15     | 29.63%  |
| SanDisk             | 3         | 3      | 11.11%  |
| Samsung Electronics | 3         | 4      | 11.11%  |
| WDC                 | 2         | 3      | 7.41%   |
| External            | 2         | 5      | 7.41%   |
| A-DATA Technology   | 2         | 2      | 7.41%   |
| W800SH              | 1         | 1      | 3.7%    |
| PNY                 | 1         | 1      | 3.7%    |
| Patriot             | 1         | 4      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |
| Kingston            | 1         | 2      | 3.7%    |
| KingSpec            | 1         | 1      | 3.7%    |
| China               | 1         | 2      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 34        | 58     | 40.48%  |
| SSD     | 26        | 44     | 30.95%  |
| NVMe    | 15        | 22     | 17.86%  |
| MMC     | 8         | 12     | 9.52%   |
| Unknown | 1         | 4      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 53        | 100    | 67.09%  |
| NVMe | 15        | 22     | 18.99%  |
| MMC  | 8         | 12     | 10.13%  |
| SAS  | 3         | 6      | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 76     | 67.86%  |
| 0.51-1.0   | 18        | 26     | 32.14%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 28.75%  |
| 251-500        | 17        | 21.25%  |
| 501-1000       | 16        | 20%     |
| 1-20           | 11        | 13.75%  |
| 1001-2000      | 6         | 7.5%    |
| 21-50          | 3         | 3.75%   |
| More than 3000 | 1         | 1.25%   |
| 2001-3000      | 1         | 1.25%   |
| 51-100         | 1         | 1.25%   |
| Unknown        | 1         | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 31        | 36.05%  |
| 21-50     | 19        | 22.09%  |
| 101-250   | 13        | 15.12%  |
| 51-100    | 12        | 13.95%  |
| 501-1000  | 5         | 5.81%   |
| 251-500   | 4         | 4.65%   |
| 1001-2000 | 1         | 1.16%   |
| Unknown   | 1         | 1.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-60UST0 250GB                      | 1         | 1      | 12.5%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 12.5%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB          | 1         | 1      | 12.5%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 12.5%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 12.5%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 12.5%   |
| Hitachi HTS545025B9A300 250GB                    | 1         | 1      | 12.5%   |
| Hitachi HTS543232L9A300 320GB                    | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 2         | 2      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |
| Toshiba             | 1         | 1      | 12.5%   |
| SK hynix            | 1         | 1      | 12.5%   |
| Seagate             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Micron Technology   | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 62.5%   |
| SSD  | 2         | 2      | 25%     |
| NVMe | 1         | 1      | 12.5%   |

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
| Detected | 49        | 116    | 71.01%  |
| Works    | 12        | 16     | 17.39%  |
| Malfunc  | 8         | 8      | 11.59%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 52        | 69.33%  |
| AMD                         | 8         | 10.67%  |
| SK hynix                    | 6         | 8%      |
| SanDisk                     | 3         | 4%      |
| Silicon Motion              | 1         | 1.33%   |
| Samsung Electronics         | 1         | 1.33%   |
| Nvidia                      | 1         | 1.33%   |
| Micron Technology           | 1         | 1.33%   |
| Kingston Technology Company | 1         | 1.33%   |
| ASMedia Technology          | 1         | 1.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 11.39%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 10.13%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 10.13%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 8.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 5.06%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 3.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 3.8%    |
| SK hynix BC511 NVMe SSD                                                          | 2         | 2.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.53%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 2.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 2.53%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 1.27%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.27%   |
| SanDisk WD Black SN770 NVMe SSD                                                  | 1         | 1.27%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 1.27%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.27%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.27%   |
| Micron 2200S NVMe SSD                                                            | 1         | 1.27%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.27%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.27%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 1.27%   |
| Intel NVMe Controller                                                            | 1         | 1.27%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.27%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.27%   |
| AMD FCH IDE Controller                                                           | 1         | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 49        | 62.82%  |
| NVMe | 15        | 19.23%  |
| RAID | 10        | 12.82%  |
| IDE  | 4         | 5.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 57        | 85.07%  |
| AMD    | 10        | 14.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-6500U CPU @ 2.50GHz        | 3         | 4.48%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 3         | 4.48%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 3         | 4.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 2.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 2.99%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 2.99%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz       | 2         | 2.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 2.99%   |
| AMD Ryzen 5 4500U with Radeon Graphics   | 2         | 2.99%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 1.49%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 1.49%   |
| Intel Pentium CPU P6100 @ 2.00GHz        | 1         | 1.49%   |
| Intel Pentium CPU N3710 @ 1.60GHz        | 1         | 1.49%   |
| Intel Pentium CPU B980 @ 2.40GHz         | 1         | 1.49%   |
| Intel Genuine CPU T2250 @ 1.73GHz        | 1         | 1.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 1         | 1.49%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz       | 1         | 1.49%   |
| Intel Core i7-3740QM CPU @ 2.70GHz       | 1         | 1.49%   |
| Intel Core i7-3540M CPU @ 3.00GHz        | 1         | 1.49%   |
| Intel Core i7-2640M CPU @ 2.80GHz        | 1         | 1.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 1         | 1.49%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 1.49%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 1.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 1         | 1.49%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1         | 1.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 1         | 1.49%   |
| Intel Core i5-2450M CPU @ 2.50GHz        | 1         | 1.49%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 1         | 1.49%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz       | 1         | 1.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 1         | 1.49%   |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 1         | 1.49%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 1         | 1.49%   |
| Intel Core i5 CPU M 460 @ 2.53GHz        | 1         | 1.49%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 1         | 1.49%   |
| Intel Core i3-4020Y CPU @ 1.50GHz        | 1         | 1.49%   |
| Intel Core i3-2365M CPU @ 1.40GHz        | 1         | 1.49%   |
| Intel Core i3-2350M CPU @ 2.30GHz        | 1         | 1.49%   |
| Intel Core i3-2310M CPU @ 2.10GHz        | 1         | 1.49%   |
| Intel Core i3 CPU M 370 @ 2.40GHz        | 1         | 1.49%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz     | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 19        | 28.36%  |
| Intel Core i7        | 14        | 20.9%   |
| Intel Core i3        | 8         | 11.94%  |
| Intel Celeron        | 4         | 5.97%   |
| AMD Ryzen 5          | 4         | 5.97%   |
| Other                | 3         | 4.48%   |
| Intel Pentium        | 3         | 4.48%   |
| Intel Core 2 Duo     | 3         | 4.48%   |
| Intel Pentium Silver | 2         | 2.99%   |
| AMD A8               | 2         | 2.99%   |
| Intel Genuine        | 1         | 1.49%   |
| Intel Core 2         | 1         | 1.49%   |
| AMD Ryzen 3          | 1         | 1.49%   |
| AMD E2               | 1         | 1.49%   |
| AMD A10              | 1         | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 38        | 56.72%  |
| 4      | 23        | 34.33%  |
| 6      | 5         | 7.46%   |
| 1      | 1         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 48        | 71.64%  |
| 1      | 19        | 28.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 66        | 98.51%  |
| 32-bit         | 1         | 1.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 28.17%  |
| 0x206a7    | 11        | 15.49%  |
| 0x20655    | 4         | 5.63%   |
| 0x806ec    | 3         | 4.23%   |
| 0x806ea    | 3         | 4.23%   |
| 0x706a1    | 3         | 4.23%   |
| 0x406e3    | 2         | 2.82%   |
| 0x306d4    | 2         | 2.82%   |
| 0x306a9    | 2         | 2.82%   |
| 0x08600106 | 2         | 2.82%   |
| 0x08108109 | 2         | 2.82%   |
| 0xa0652    | 1         | 1.41%   |
| 0x906ea    | 1         | 1.41%   |
| 0x806e9    | 1         | 1.41%   |
| 0x806c1    | 1         | 1.41%   |
| 0x706e5    | 1         | 1.41%   |
| 0x6e8      | 1         | 1.41%   |
| 0x506c9    | 1         | 1.41%   |
| 0x406c4    | 1         | 1.41%   |
| 0x406c3    | 1         | 1.41%   |
| 0x40651    | 1         | 1.41%   |
| 0x306c3    | 1         | 1.41%   |
| 0x20652    | 1         | 1.41%   |
| 0x10676    | 1         | 1.41%   |
| 0x08600104 | 1         | 1.41%   |
| 0x07030105 | 1         | 1.41%   |
| 0x06003106 | 1         | 1.41%   |
| 0x06001119 | 1         | 1.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 17.91%  |
| SandyBridge   | 11        | 16.42%  |
| Westmere      | 5         | 7.46%   |
| Skylake       | 4         | 5.97%   |
| Goldmont plus | 4         | 5.97%   |
| Zen 2         | 3         | 4.48%   |
| Penryn        | 3         | 4.48%   |
| IceLake       | 3         | 4.48%   |
| Haswell       | 3         | 4.48%   |
| Zen+          | 2         | 2.99%   |
| TigerLake     | 2         | 2.99%   |
| Silvermont    | 2         | 2.99%   |
| IvyBridge     | 2         | 2.99%   |
| Broadwell     | 2         | 2.99%   |
| Steamroller   | 1         | 1.49%   |
| Puma          | 1         | 1.49%   |
| Piledriver    | 1         | 1.49%   |
| P6            | 1         | 1.49%   |
| Goldmont      | 1         | 1.49%   |
| Core          | 1         | 1.49%   |
| CometLake     | 1         | 1.49%   |
| Bobcat        | 1         | 1.49%   |
| Unknown       | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 70.89%  |
| AMD    | 13        | 16.46%  |
| Nvidia | 10        | 12.66%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 13.1%   |
| Intel UHD Graphics 620                                                                   | 5         | 5.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 5.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 4.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 3.57%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 3.57%   |
| AMD Renoir                                                                               | 3         | 3.57%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 2.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.38%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 2.38%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.38%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.38%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 2.38%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.19%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.19%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.19%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.19%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 1.19%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 1.19%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.19%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.19%   |
| Intel HD Graphics 620                                                                    | 1         | 1.19%   |
| Intel HD Graphics 500                                                                    | 1         | 1.19%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 1         | 1.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.19%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.19%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1.19%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 1         | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 65.67%  |
| Intel + Nvidia | 9         | 13.43%  |
| 1 x AMD        | 9         | 13.43%  |
| Intel + AMD    | 3         | 4.48%   |
| 2 x Nvidia     | 1         | 1.49%   |
| 2 x AMD        | 1         | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 63        | 91.3%   |
| Proprietary | 5         | 7.25%   |
| Unknown     | 1         | 1.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 72.86%  |
| 0.51-1.0   | 5         | 7.14%   |
| 0.01-0.5   | 5         | 7.14%   |
| 3.01-4.0   | 3         | 4.29%   |
| 1.01-2.0   | 3         | 4.29%   |
| 5.01-6.0   | 2         | 2.86%   |
| 2.01-3.0   | 1         | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 12        | 16%     |
| LG Display              | 11        | 14.67%  |
| Samsung Electronics     | 10        | 13.33%  |
| BOE                     | 10        | 13.33%  |
| AU Optronics            | 8         | 10.67%  |
| PANDA                   | 3         | 4%      |
| Dell                    | 3         | 4%      |
| Apple                   | 3         | 4%      |
| Goldstar                | 2         | 2.67%   |
| Chi Mei Optoelectronics | 2         | 2.67%   |
| Valve                   | 1         | 1.33%   |
| Sony                    | 1         | 1.33%   |
| Sharp                   | 1         | 1.33%   |
| RTK                     | 1         | 1.33%   |
| ONN                     | 1         | 1.33%   |
| Lenovo                  | 1         | 1.33%   |
| InnoLux Display         | 1         | 1.33%   |
| eMachines               | 1         | 1.33%   |
| AOC                     | 1         | 1.33%   |
| Ancor Communications    | 1         | 1.33%   |
| Acer                    | 1         | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 3         | 4%      |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 2.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 2.67%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.33%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 1.33%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 1.33%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch  | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch  | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SDC454A 3200x1800 293x165mm 13.2-inch | 1         | 1.33%   |
| RTK ARZOPA RTK3B3D 1920x1080 344x195mm 15.6-inch                      | 1         | 1.33%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 1.33%   |
| PANDA LCD Monitor NCP0030 1920x1080 344x194mm 15.5-inch               | 1         | 1.33%   |
| PANDA LCD Monitor NCP0025 1920x1080 344x194mm 15.5-inch               | 1         | 1.33%   |
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch                | 1         | 1.33%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 1.33%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch          | 1         | 1.33%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch          | 1         | 1.33%   |
| LG Display LCD Monitor LGD0513 1920x1080 382x215mm 17.3-inch          | 1         | 1.33%   |
| LG Display LCD Monitor LGD0492 1920x1080 344x194mm 15.5-inch          | 1         | 1.33%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 1.33%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.33%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 1         | 1.33%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 1.33%   |
| InnoLux Display LCD Monitor INL0028 1366x768 309x174mm 14.0-inch      | 1         | 1.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 1.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.33%   |
| eMachines E19T6W EMA0783 1440x900 410x257mm 19.1-inch                 | 1         | 1.33%   |
| Dell S2330MX DELD049 1920x1080 509x286mm 23.0-inch                    | 1         | 1.33%   |
| Dell P2419HC DELA11C 1920x1080 527x296mm 23.8-inch                    | 1         | 1.33%   |
| Dell DELLSE2216HV DELF072 1920x1080 476x268mm 21.5-inch               | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch      | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch       | 1         | 1.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 29        | 42.03%  |
| 1366x768 (WXGA)  | 27        | 39.13%  |
| 1280x800 (WXGA)  | 4         | 5.8%    |
| 1440x900 (WXGA+) | 3         | 4.35%   |
| 1600x900 (HD+)   | 2         | 2.9%    |
| 800x1280         | 1         | 1.45%   |
| 3840x2160 (4K)   | 1         | 1.45%   |
| 3200x1800 (QHD+) | 1         | 1.45%   |
| 2560x1080        | 1         | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 33        | 44.59%  |
| 17     | 8         | 10.81%  |
| 14     | 8         | 10.81%  |
| 13     | 6         | 8.11%   |
| 31     | 3         | 4.05%   |
| 21     | 3         | 4.05%   |
| 11     | 3         | 4.05%   |
| 24     | 2         | 2.7%    |
| 23     | 2         | 2.7%    |
| 72     | 1         | 1.35%   |
| 34     | 1         | 1.35%   |
| 27     | 1         | 1.35%   |
| 19     | 1         | 1.35%   |
| 18     | 1         | 1.35%   |
| 7      | 1         | 1.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 56.76%  |
| 351-400     | 9         | 12.16%  |
| 201-300     | 7         | 9.46%   |
| 501-600     | 5         | 6.76%   |
| 401-500     | 5         | 6.76%   |
| 601-700     | 3         | 4.05%   |
| 701-800     | 1         | 1.35%   |
| 1501-2000   | 1         | 1.35%   |
| 1-100       | 1         | 1.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 58        | 86.57%  |
| 16/10 | 7         | 10.45%  |
| 21/9  | 1         | 1.49%   |
| 0.67  | 1         | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 44.59%  |
| 81-90          | 12        | 16.22%  |
| 121-130        | 7         | 9.46%   |
| 201-250        | 5         | 6.76%   |
| 351-500        | 4         | 5.41%   |
| 51-60          | 3         | 4.05%   |
| 151-200        | 3         | 4.05%   |
| 71-80          | 2         | 2.7%    |
| More than 1000 | 1         | 1.35%   |
| 1-40           | 1         | 1.35%   |
| 301-350        | 1         | 1.35%   |
| 141-150        | 1         | 1.35%   |
| 131-140        | 1         | 1.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 31        | 41.33%  |
| 121-160       | 25        | 33.33%  |
| 51-100        | 13        | 17.33%  |
| 1-50          | 3         | 4%      |
| 161-240       | 2         | 2.67%   |
| More than 240 | 1         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 55        | 78.57%  |
| 2     | 13        | 18.57%  |
| 0     | 2         | 2.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 38        | 33.33%  |
| Realtek Semiconductor    | 37        | 32.46%  |
| Qualcomm Atheros         | 13        | 11.4%   |
| Broadcom                 | 7         | 6.14%   |
| Marvell Technology Group | 3         | 2.63%   |
| Broadcom Limited         | 3         | 2.63%   |
| Ralink Technology        | 2         | 1.75%   |
| NetGear                  | 2         | 1.75%   |
| ASIX Electronics         | 2         | 1.75%   |
| TP-Link                  | 1         | 0.88%   |
| Samsung Electronics      | 1         | 0.88%   |
| Ralink                   | 1         | 0.88%   |
| Nvidia                   | 1         | 0.88%   |
| MediaTek                 | 1         | 0.88%   |
| Dell                     | 1         | 0.88%   |
| Belkin Components        | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 23        | 18.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 4.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 3.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 3         | 2.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 3         | 2.4%    |
| Intel Wireless 7265                                                            | 3         | 2.4%    |
| Intel Wi-Fi 6 AX200                                                            | 3         | 2.4%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 3         | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 1.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 1.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 2         | 1.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 1.6%    |
| Intel Wireless 3160                                                            | 2         | 1.6%    |
| Intel Wi-Fi 6 AX201                                                            | 2         | 1.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 1.6%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 2         | 1.6%    |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                  | 2         | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 1.6%    |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.6%    |
| Broadcom Limited BCM43224 802.11a/b/g/n                                        | 2         | 1.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1         | 0.8%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 0.8%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 1         | 0.8%    |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 0.8%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1         | 0.8%    |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                     | 1         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.8%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.8%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.8%    |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                          | 1         | 0.8%    |
| NetGear LB1120-100NAS                                                          | 1         | 0.8%    |
| MediaTek WiFi                                                                  | 1         | 0.8%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.8%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 43.84%  |
| Realtek Semiconductor | 14        | 19.18%  |
| Qualcomm Atheros      | 11        | 15.07%  |
| Broadcom              | 6         | 8.22%   |
| Ralink Technology     | 2         | 2.74%   |
| Broadcom Limited      | 2         | 2.74%   |
| TP-Link               | 1         | 1.37%   |
| Ralink                | 1         | 1.37%   |
| NetGear               | 1         | 1.37%   |
| MediaTek              | 1         | 1.37%   |
| Dell                  | 1         | 1.37%   |
| Belkin Components     | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 4         | 5.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 3         | 4.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 4.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 3         | 4.05%   |
| Intel Wireless 7265                                        | 3         | 4.05%   |
| Intel Wi-Fi 6 AX200                                        | 3         | 4.05%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]               | 3         | 4.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 2.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 2         | 2.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 2         | 2.7%    |
| Intel Wireless 3160                                        | 2         | 2.7%    |
| Intel Wi-Fi 6 AX201                                        | 2         | 2.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 2         | 2.7%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 2         | 2.7%    |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 2         | 2.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 2.7%    |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 2         | 2.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 2         | 2.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 1.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 1.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 1.35%   |
| Realtek 802.11n WLAN Adapter                               | 1         | 1.35%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1         | 1.35%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter | 1         | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1         | 1.35%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]      | 1         | 1.35%   |
| MediaTek WiFi                                              | 1         | 1.35%   |
| Intel Wireless 8265 / 8275                                 | 1         | 1.35%   |
| Intel Wireless 8260                                        | 1         | 1.35%   |
| Intel Wireless 7260                                        | 1         | 1.35%   |
| Intel Wireless 3165                                        | 1         | 1.35%   |
| Intel WiFi Link 5100                                       | 1         | 1.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 1.35%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 56.86%  |
| Intel                    | 8         | 15.69%  |
| Qualcomm Atheros         | 3         | 5.88%   |
| Marvell Technology Group | 3         | 5.88%   |
| Broadcom                 | 2         | 3.92%   |
| ASIX Electronics         | 2         | 3.92%   |
| Samsung Electronics      | 1         | 1.96%   |
| Nvidia                   | 1         | 1.96%   |
| NetGear                  | 1         | 1.96%   |
| Broadcom Limited         | 1         | 1.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 23        | 45.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 11.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 5.88%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 3.92%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 1.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.96%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.96%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.96%   |
| NetGear LB1120-100NAS                                                          | 1         | 1.96%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.96%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.96%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.96%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.96%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 1.96%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.96%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 1.96%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 1.96%   |
| ASIX AX88772B                                                                  | 1         | 1.96%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 56.41%  |
| Ethernet | 51        | 43.59%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 80%     |
| Ethernet | 14        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 67.16%  |
| 1     | 19        | 28.36%  |
| 0     | 2         | 2.99%   |
| 3     | 1         | 1.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 75.36%  |
| Yes  | 17        | 24.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 48.08%  |
| Realtek Semiconductor           | 8         | 15.38%  |
| Qualcomm Atheros Communications | 3         | 5.77%   |
| IMC Networks                    | 3         | 5.77%   |
| Foxconn / Hon Hai               | 3         | 5.77%   |
| Apple                           | 3         | 5.77%   |
| Lite-On Technology              | 2         | 3.85%   |
| Dell                            | 2         | 3.85%   |
| Toshiba                         | 1         | 1.92%   |
| Hewlett-Packard                 | 1         | 1.92%   |
| Alps Electric                   | 1         | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 9         | 17.31%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 13.46%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 11.54%  |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 7.69%   |
| Intel AX200 Bluetooth                                                               | 3         | 5.77%   |
| Realtek Bluetooth Radio                                                             | 2         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 3.85%   |
| Intel AX201 Bluetooth                                                               | 2         | 3.85%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 3.85%   |
| Apple Bluetooth Host Controller                                                     | 2         | 3.85%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.92%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.92%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 1.92%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.92%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.92%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.92%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.92%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.92%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.92%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.92%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 78.87%  |
| AMD    | 10        | 14.08%  |
| Nvidia | 5         | 7.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 11.63%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 10.47%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 5.81%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 5.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 4.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 4.65%   |
| AMD FCH Azalia Controller                                                                         | 4         | 4.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 3.49%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.33%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.33%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.33%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.16%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.16%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.16%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.16%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.16%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 1.16%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 1.16%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 8         | 34.78%  |
| Samsung Electronics | 6         | 26.09%  |
| Micron Technology   | 3         | 13.04%  |
| Kingston            | 2         | 8.7%    |
| Silicon Power       | 1         | 4.35%   |
| Ramaxel Technology  | 1         | 4.35%   |
| PNY                 | 1         | 4.35%   |
| A-DATA Technology   | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 7.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 2         | 7.69%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 3.85%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 1         | 3.85%   |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s             | 1         | 3.85%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 3.85%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 3.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s | 1         | 3.85%   |
| Silicon Power RAM Module 8GB SODIMM DDR3 1600MT/s         | 1         | 3.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s  | 1         | 3.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 1         | 3.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 3.85%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 1         | 3.85%   |
| PNY RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 3.85%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Kingston RAM HP691160-H66-MCN 8GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s    | 1         | 3.85%   |
| A-DATA RAM AM1L16BC4R1-B1YS 4GB SODIMM DDR3 800MT/s       | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 45.45%  |
| DDR3   | 8         | 36.36%  |
| LPDDR4 | 2         | 9.09%   |
| LPDDR3 | 1         | 4.55%   |
| DDR    | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 95.24%  |
| Row Of Chips | 1         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 10        | 45.45%  |
| 4096  | 9         | 40.91%  |
| 16384 | 2         | 9.09%   |
| 2048  | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 8         | 34.78%  |
| 2667  | 6         | 26.09%  |
| 3200  | 3         | 13.04%  |
| 3266  | 1         | 4.35%   |
| 2400  | 1         | 4.35%   |
| 2133  | 1         | 4.35%   |
| 1067  | 1         | 4.35%   |
| 800   | 1         | 4.35%   |
| 667   | 1         | 4.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 10        | 17.86%  |
| Ricoh                                  | 5         | 8.93%   |
| Realtek Semiconductor                  | 5         | 8.93%   |
| Lite-On Technology                     | 4         | 7.14%   |
| IMC Networks                           | 4         | 7.14%   |
| Sunplus Innovation Technology          | 3         | 5.36%   |
| Quanta                                 | 3         | 5.36%   |
| Microdia                               | 3         | 5.36%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.36%   |
| Acer                                   | 3         | 5.36%   |
| Syntek                                 | 2         | 3.57%   |
| Suyin                                  | 2         | 3.57%   |
| Luxvisions Innotech Limited            | 2         | 3.57%   |
| Bison Electronics                      | 2         | 3.57%   |
| Apple                                  | 2         | 3.57%   |
| Lenovo                                 | 1         | 1.79%   |
| Goertek Electronics                    | 1         | 1.79%   |
| Alpha Imaging Technology               | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Ricoh Integrated Webcam                                        | 3         | 5.36%   |
| Lite-On HP Wide Vision HD Camera                               | 3         | 5.36%   |
| Chicony HP Truevision HD                                       | 2         | 3.57%   |
| Chicony HD WebCam                                              | 2         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 3.57%   |
| Acer Lenovo EasyCamera                                         | 2         | 3.57%   |
| Syntek Lenovo EasyCamera                                       | 1         | 1.79%   |
| Syntek Integrated Camera                                       | 1         | 1.79%   |
| Suyin USB 2.0 Camera                                           | 1         | 1.79%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.79%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.79%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 1.79%   |
| Sunplus Camera                                                 | 1         | 1.79%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam       | 1         | 1.79%   |
| Ricoh HD Webcam                                                | 1         | 1.79%   |
| Realtek USB2.0 camera                                          | 1         | 1.79%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.79%   |
| Realtek Integrated Webcam HD                                   | 1         | 1.79%   |
| Realtek Integrated Webcam                                      | 1         | 1.79%   |
| Realtek 2SF022                                                 | 1         | 1.79%   |
| Quanta VGA WebCam                                              | 1         | 1.79%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 1.79%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 1.79%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 1.79%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.79%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.79%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.79%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 1.79%   |
| Lite-On HP HD Webcam                                           | 1         | 1.79%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 1.79%   |
| IMC Networks UVC VGA Webcam                                    | 1         | 1.79%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.79%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 1.79%   |
| IMC Networks Integrated Camera                                 | 1         | 1.79%   |
| Goertek USB2.0 VGA UVC WebCam                                  | 1         | 1.79%   |
| Chicony TOSHIBA Web Camera - HD                                | 1         | 1.79%   |
| Chicony Toshiba Integrated Webcam                              | 1         | 1.79%   |
| Chicony Integrated HP HD Webcam                                | 1         | 1.79%   |
| Chicony HP Webcam                                              | 1         | 1.79%   |
| Chicony HP HD Camera                                           | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 63.64%  |
| Synaptics             | 2         | 18.18%  |
| LighTuning Technology | 2         | 18.18%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 3         | 27.27%  |
| LighTuning EgisTec Touch Fingerprint Sensor       | 2         | 18.18%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors Fingerprint scanner              | 1         | 9.09%   |
| Synaptics UWP WBDI                                | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 45        | 66.18%  |
| 1     | 21        | 30.88%  |
| 2     | 2         | 2.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 42.31%  |
| Graphics card            | 5         | 19.23%  |
| Net/wireless             | 4         | 15.38%  |
| Chipcard                 | 3         | 11.54%  |
| Storage                  | 1         | 3.85%   |
| Multimedia controller    | 1         | 3.85%   |
| Communication controller | 1         | 3.85%   |

