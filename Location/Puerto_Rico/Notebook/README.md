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

Total: 164

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E570 20H50048US    | [70b5d1cb69](https://linux-hardware.org/?probe=70b5d1cb69) | Dec 05, 2023 |
| ASUSTek       | K53E                        | [4b184d1d81](https://linux-hardware.org/?probe=4b184d1d81) | Dec 02, 2023 |
| Dell          | Latitude 7290               | [c9068c7692](https://linux-hardware.org/?probe=c9068c7692) | Nov 30, 2023 |
| Dell          | Latitude 7290               | [c75434aea3](https://linux-hardware.org/?probe=c75434aea3) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [49fad3d40c](https://linux-hardware.org/?probe=49fad3d40c) | Nov 28, 2023 |
| HP            | 250 G7 Notebook PC          | [7fce567d9e](https://linux-hardware.org/?probe=7fce567d9e) | Nov 25, 2023 |
| Lenovo        | ThinkPad T510 4314RBS       | [883b10d260](https://linux-hardware.org/?probe=883b10d260) | Nov 19, 2023 |
| HP            | Laptop 14-dq0xxx            | [f2123bd01c](https://linux-hardware.org/?probe=f2123bd01c) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3d00034c4e](https://linux-hardware.org/?probe=3d00034c4e) | Nov 01, 2023 |
| Lenovo        | ThinkPad E560 20EV002JUS    | [07a3c8eea8](https://linux-hardware.org/?probe=07a3c8eea8) | Oct 28, 2023 |
| Lenovo        | ThinkPad E560 20EV002JUS    | [906ed51ecf](https://linux-hardware.org/?probe=906ed51ecf) | Oct 27, 2023 |
| HP            | EliteBook 840 G2            | [63107ac52c](https://linux-hardware.org/?probe=63107ac52c) | Oct 23, 2023 |
| HP            | 250 G7 Notebook PC          | [b9698d48be](https://linux-hardware.org/?probe=b9698d48be) | Oct 22, 2023 |
| HP            | 250 G7 Notebook PC          | [809ff050d7](https://linux-hardware.org/?probe=809ff050d7) | Oct 13, 2023 |
| Dell          | Inspiron 11-3168            | [538c1421e9](https://linux-hardware.org/?probe=538c1421e9) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f56c04f3e2](https://linux-hardware.org/?probe=f56c04f3e2) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0e27147016](https://linux-hardware.org/?probe=0e27147016) | Oct 09, 2023 |
| HP            | 250 G7 Notebook PC          | [7fb0e4c19c](https://linux-hardware.org/?probe=7fb0e4c19c) | Sep 28, 2023 |
| Lenovo        | V14-ARE 82DQ                | [31a635bff8](https://linux-hardware.org/?probe=31a635bff8) | Sep 24, 2023 |
| HP            | 250 G7 Notebook PC          | [a2a2bc81e9](https://linux-hardware.org/?probe=a2a2bc81e9) | Sep 20, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [932df74a39](https://linux-hardware.org/?probe=932df74a39) | Sep 17, 2023 |
| Apple         | MacBook6,1                  | [8db6f2c947](https://linux-hardware.org/?probe=8db6f2c947) | Sep 14, 2023 |
| Valve         | Jupiter                     | [06f7e4ef1b](https://linux-hardware.org/?probe=06f7e4ef1b) | Sep 13, 2023 |
| HP            | Laptop 15-dy2xxx            | [eae373ebd4](https://linux-hardware.org/?probe=eae373ebd4) | Sep 07, 2023 |
| Dell          | Vostro 3550                 | [c9431922ba](https://linux-hardware.org/?probe=c9431922ba) | Sep 01, 2023 |
| HP            | EliteBook 840 G2            | [53bcd4ec72](https://linux-hardware.org/?probe=53bcd4ec72) | Aug 31, 2023 |
| Dell          | Vostro 3550                 | [f120556c56](https://linux-hardware.org/?probe=f120556c56) | Aug 30, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [aac7eeec4e](https://linux-hardware.org/?probe=aac7eeec4e) | Aug 30, 2023 |
| HP            | EliteBook 840 G2            | [4f3d3f12a4](https://linux-hardware.org/?probe=4f3d3f12a4) | Aug 30, 2023 |
| Dell          | Latitude 7290               | [eb12e0d829](https://linux-hardware.org/?probe=eb12e0d829) | Aug 17, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [df5fa32e56](https://linux-hardware.org/?probe=df5fa32e56) | Jul 25, 2023 |
| HP            | EliteBook 840 G2            | [9b0de4f244](https://linux-hardware.org/?probe=9b0de4f244) | Jul 09, 2023 |
| Apple         | MacBookPro9,2               | [b52a9ea310](https://linux-hardware.org/?probe=b52a9ea310) | Jul 08, 2023 |
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
| Ubuntu 20.04                 | 16        | 17.58%  |
| Ubuntu 22.04                 | 12        | 13.19%  |
| Ubuntu 18.04                 | 5         | 5.49%   |
| Arch Rolling                 | 3         | 3.3%    |
| Ubuntu 22.10                 | 2         | 2.2%    |
| Ubuntu 21.10                 | 2         | 2.2%    |
| Pop!_OS 22.04                | 2         | 2.2%    |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 2.2%    |
| OpenMandriva 4.3             | 2         | 2.2%    |
| OpenMandriva 4.2             | 2         | 2.2%    |
| Linux Mint 21                | 2         | 2.2%    |
| Linux Mint 19.3              | 2         | 2.2%    |
| Fedora 38                    | 2         | 2.2%    |
| Fedora 37                    | 2         | 2.2%    |
| Elementary 7                 | 2         | 2.2%    |
| Debian 11                    | 2         | 2.2%    |
| BlackPanther 18.1            | 2         | 2.2%    |
| Zorin 16                     | 1         | 1.1%    |
| Xubuntu 20.04                | 1         | 1.1%    |
| Ubuntu Unity 20.04           | 1         | 1.1%    |
| Ubuntu MATE 20.04            | 1         | 1.1%    |
| Ubuntu 23.04                 | 1         | 1.1%    |
| Ubuntu 19.10                 | 1         | 1.1%    |
| SteamOS 3.4.4                | 1         | 1.1%    |
| SteamOS 3.4.10               | 1         | 1.1%    |
| ROSA R10                     | 1         | 1.1%    |
| Peppermint 9                 | 1         | 1.1%    |
| Parrot 5.0                   | 1         | 1.1%    |
| Parrot 4.11                  | 1         | 1.1%    |
| openSUSE Leap-15.2           | 1         | 1.1%    |
| OpenMandriva 4.90            | 1         | 1.1%    |
| OpenMandriva 4.50            | 1         | 1.1%    |
| OpenMandriva 23.01           | 1         | 1.1%    |
| LMDE 6                       | 1         | 1.1%    |
| Linux Mint 21.2              | 1         | 1.1%    |
| Linux Mint 21.1              | 1         | 1.1%    |
| Linux Mint 20.1              | 1         | 1.1%    |
| KDE neon 22.04               | 1         | 1.1%    |
| KDE neon 20.04               | 1         | 1.1%    |
| Fedora 36                    | 1         | 1.1%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 34        | 40%     |
| OpenMandriva | 7         | 8.24%   |
| Linux Mint   | 6         | 7.06%   |
| Fedora       | 6         | 7.06%   |
| openSUSE     | 3         | 3.53%   |
| Debian       | 3         | 3.53%   |
| Arch         | 3         | 3.53%   |
| SteamOS      | 2         | 2.35%   |
| Pop!_OS      | 2         | 2.35%   |
| Parrot       | 2         | 2.35%   |
| KDE neon     | 2         | 2.35%   |
| Elementary   | 2         | 2.35%   |
| BlackPanther | 2         | 2.35%   |
| Zorin        | 1         | 1.18%   |
| Xubuntu      | 1         | 1.18%   |
| Ubuntu Unity | 1         | 1.18%   |
| Ubuntu MATE  | 1         | 1.18%   |
| ROSA         | 1         | 1.18%   |
| Peppermint   | 1         | 1.18%   |
| LMDE         | 1         | 1.18%   |
| Endless      | 1         | 1.18%   |
| EndeavourOS  | 1         | 1.18%   |
| ArcoLinux    | 1         | 1.18%   |
| AlmaLinux    | 1         | 1.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.2.0-34-generic         | 3         | 2.54%   |
| 5.8.0-59-generic         | 3         | 2.54%   |
| 6.3.6-200.fc38.x86_64    | 2         | 1.69%   |
| 6.2.0-32-generic         | 2         | 1.69%   |
| 6.2.0-31-generic         | 2         | 1.69%   |
| 5.8.0-55-generic         | 2         | 1.69%   |
| 5.4.0-58-generic         | 2         | 1.69%   |
| 5.19.0-42-generic        | 2         | 1.69%   |
| 5.19.0-38-generic        | 2         | 1.69%   |
| 5.16.7-desktop-1omv4003  | 2         | 1.69%   |
| 5.15.0-58-generic        | 2         | 1.69%   |
| 5.15.0-46-generic        | 2         | 1.69%   |
| 5.15.0-25-generic        | 2         | 1.69%   |
| 5.13.0-35-generic        | 2         | 1.69%   |
| 5.11.0-38-generic        | 2         | 1.69%   |
| 5.11.0-27-generic        | 2         | 1.69%   |
| 5.10.14-desktop-1omv4002 | 2         | 1.69%   |
| 5.10.0-19-amd64          | 2         | 1.69%   |
| 6.7.0-060700rc4-generic  | 1         | 0.85%   |
| 6.6.2-x64v4-xanmod1      | 1         | 0.85%   |
| 6.6.1-arch1-1            | 1         | 0.85%   |
| 6.5.9-1-default          | 1         | 0.85%   |
| 6.4.6-76060406-generic   | 1         | 0.85%   |
| 6.4.15-200.fc38.x86_64   | 1         | 0.85%   |
| 6.4.11-060411-generic    | 1         | 0.85%   |
| 6.2.9-1-default          | 1         | 0.85%   |
| 6.2.8-200.fc37.x86_64    | 1         | 0.85%   |
| 6.2.6-76060206-generic   | 1         | 0.85%   |
| 6.2.12-arch1-1           | 1         | 0.85%   |
| 6.2.0-36-generic         | 1         | 0.85%   |
| 6.2.0-35-generic         | 1         | 0.85%   |
| 6.2.0-26-generic         | 1         | 0.85%   |
| 6.1.60-1-lts             | 1         | 0.85%   |
| 6.1.1-desktop-1omv2290   | 1         | 0.85%   |
| 6.1.0-13-amd64           | 1         | 0.85%   |
| 6.1.0-12-amd64           | 1         | 0.85%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.85%   |
| 5.8.0-63-generic         | 1         | 0.85%   |
| 5.6.14-desktop-2bP       | 1         | 0.85%   |
| 5.4.0-84-generic         | 1         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 13        | 13.54%  |
| 5.13.0  | 8         | 8.33%   |
| 6.2.0   | 7         | 7.29%   |
| 5.19.0  | 7         | 7.29%   |
| 5.15.0  | 7         | 7.29%   |
| 5.11.0  | 5         | 5.21%   |
| 5.8.0   | 4         | 4.17%   |
| 5.3.0   | 3         | 3.13%   |
| 5.10.0  | 3         | 3.13%   |
| 4.15.0  | 3         | 3.13%   |
| 6.3.6   | 2         | 2.08%   |
| 5.16.7  | 2         | 2.08%   |
| 5.10.14 | 2         | 2.08%   |
| 6.7.0   | 1         | 1.04%   |
| 6.6.2   | 1         | 1.04%   |
| 6.6.1   | 1         | 1.04%   |
| 6.5.9   | 1         | 1.04%   |
| 6.4.6   | 1         | 1.04%   |
| 6.4.15  | 1         | 1.04%   |
| 6.4.11  | 1         | 1.04%   |
| 6.2.9   | 1         | 1.04%   |
| 6.2.8   | 1         | 1.04%   |
| 6.2.6   | 1         | 1.04%   |
| 6.2.12  | 1         | 1.04%   |
| 6.1.60  | 1         | 1.04%   |
| 6.1.1   | 1         | 1.04%   |
| 6.1.0   | 1         | 1.04%   |
| 5.9.16  | 1         | 1.04%   |
| 5.6.14  | 1         | 1.04%   |
| 5.3.6   | 1         | 1.04%   |
| 5.3.18  | 1         | 1.04%   |
| 5.19.7  | 1         | 1.04%   |
| 5.18.6  | 1         | 1.04%   |
| 5.18.15 | 1         | 1.04%   |
| 5.18.12 | 1         | 1.04%   |
| 5.18.0  | 1         | 1.04%   |
| 5.15.59 | 1         | 1.04%   |
| 5.14.0  | 1         | 1.04%   |
| 5.12.4  | 1         | 1.04%   |
| 5.11.16 | 1         | 1.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 13        | 13.68%  |
| 6.2     | 11        | 11.58%  |
| 5.19    | 8         | 8.42%   |
| 5.15    | 8         | 8.42%   |
| 5.13    | 8         | 8.42%   |
| 5.11    | 6         | 6.32%   |
| 5.3     | 5         | 5.26%   |
| 5.10    | 5         | 5.26%   |
| 5.8     | 4         | 4.21%   |
| 6.4     | 3         | 3.16%   |
| 6.1     | 3         | 3.16%   |
| 5.18    | 3         | 3.16%   |
| 4.15    | 3         | 3.16%   |
| 6.6     | 2         | 2.11%   |
| 6.3     | 2         | 2.11%   |
| 5.16    | 2         | 2.11%   |
| 6.7     | 1         | 1.05%   |
| 6.5     | 1         | 1.05%   |
| 5.9     | 1         | 1.05%   |
| 5.6     | 1         | 1.05%   |
| 5.14    | 1         | 1.05%   |
| 5.12    | 1         | 1.05%   |
| 4.9     | 1         | 1.05%   |
| 4.19    | 1         | 1.05%   |
| 4.18    | 1         | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 77        | 97.47%  |
| i686   | 2         | 2.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 43        | 52.44%  |
| KDE5       | 17        | 20.73%  |
| X-Cinnamon | 5         | 6.1%    |
| MATE       | 4         | 4.88%   |
| XFCE       | 3         | 3.66%   |
| Pantheon   | 2         | 2.44%   |
| i3         | 2         | 2.44%   |
| Unknown    | 2         | 2.44%   |
| Unity      | 1         | 1.22%   |
| LXDE       | 1         | 1.22%   |
| KDE4       | 1         | 1.22%   |
| awesome    | 1         | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 64        | 77.11%  |
| Wayland | 19        | 22.89%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 45        | 52.33%  |
| GDM3    | 20        | 23.26%  |
| SDDM    | 10        | 11.63%  |
| GDM     | 5         | 5.81%   |
| LightDM | 3         | 3.49%   |
| TDM     | 2         | 2.33%   |
| KDM     | 1         | 1.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 70        | 87.5%   |
| Unknown | 5         | 6.25%   |
| es_PR   | 4         | 5%      |
| C       | 1         | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 46        | 56.79%  |
| EFI  | 35        | 43.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 57        | 66.28%  |
| Btrfs   | 10        | 11.63%  |
| Overlay | 8         | 9.3%    |
| Tmpfs   | 7         | 8.14%   |
| Unknown | 2         | 2.33%   |
| Zfs     | 1         | 1.16%   |
| Xfs     | 1         | 1.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 52        | 60.47%  |
| GPT     | 28        | 32.56%  |
| MBR     | 6         | 6.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 82.14%  |
| Yes       | 15        | 17.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 74.7%   |
| Yes       | 21        | 25.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 22        | 27.85%  |
| Dell             | 17        | 21.52%  |
| Lenovo           | 11        | 13.92%  |
| ASUSTek Computer | 6         | 7.59%   |
| Apple            | 5         | 6.33%   |
| Acer             | 4         | 5.06%   |
| Toshiba          | 3         | 3.8%    |
| Sony             | 3         | 3.8%    |
| Valve            | 2         | 2.53%   |
| GPU Company      | 2         | 2.53%   |
| TUXEDO           | 1         | 1.27%   |
| MSI              | 1         | 1.27%   |
| AZW              | 1         | 1.27%   |
| AMI              | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Vostro 3550                         | 3         | 3.8%    |
| Valve Jupiter                            | 2         | 2.53%   |
| Dell Inspiron 11-3168                    | 2         | 2.53%   |
| ASUS K53E                                | 2         | 2.53%   |
| TUXEDO Aura 15 Gen1                      | 1         | 1.27%   |
| Toshiba Satellite P755                   | 1         | 1.27%   |
| Toshiba Satellite L655                   | 1         | 1.27%   |
| Toshiba Satellite C55-C                  | 1         | 1.27%   |
| Sony VPCEA36FX                           | 1         | 1.27%   |
| Sony VGN-CS320J                          | 1         | 1.27%   |
| Sony SVE11113FXW                         | 1         | 1.27%   |
| MSI GF65 Thin 10SDR                      | 1         | 1.27%   |
| Lenovo Yoga 900-13ISK 80MK               | 1         | 1.27%   |
| Lenovo Y50-70 Touch 20349                | 1         | 1.27%   |
| Lenovo V14-ARE 82DQ                      | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0000US | 1         | 1.27%   |
| Lenovo ThinkPad T510 4314RBS             | 1         | 1.27%   |
| Lenovo ThinkPad T410 2516ADU             | 1         | 1.27%   |
| Lenovo ThinkPad E570 20H50048US          | 1         | 1.27%   |
| Lenovo ThinkPad E560 20EV002JUS          | 1         | 1.27%   |
| Lenovo ThinkPad E14 20RA004WUS           | 1         | 1.27%   |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 1.27%   |
| Lenovo G50-45 80E3                       | 1         | 1.27%   |
| HP Stream Laptop 14-CB1xxx               | 1         | 1.27%   |
| HP ProBook 6560b                         | 1         | 1.27%   |
| HP ProBook 6450b                         | 1         | 1.27%   |
| HP ProBook 450 G5                        | 1         | 1.27%   |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 1.27%   |
| HP Pavilion Laptop 15-cs2xxx             | 1         | 1.27%   |
| HP Pavilion Laptop 15-cs0xxx             | 1         | 1.27%   |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 1         | 1.27%   |
| HP Notebook                              | 1         | 1.27%   |
| HP Laptop 17-by3xxx                      | 1         | 1.27%   |
| HP Laptop 15-dy2xxx                      | 1         | 1.27%   |
| HP Laptop 15-dy1xxx                      | 1         | 1.27%   |
| HP Laptop 15-dw0xxx                      | 1         | 1.27%   |
| HP Laptop 14-dq0xxx                      | 1         | 1.27%   |
| HP Laptop 14-dk1xxx                      | 1         | 1.27%   |
| HP ENVY Laptop 17m-bw0xxx                | 1         | 1.27%   |
| HP ENVY Laptop 17-ce1xxx                 | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 6         | 7.59%   |
| HP Laptop              | 6         | 7.59%   |
| Dell Inspiron          | 6         | 7.59%   |
| HP Pavilion            | 4         | 5.06%   |
| Dell Latitude          | 4         | 5.06%   |
| Toshiba Satellite      | 3         | 3.8%    |
| HP ProBook             | 3         | 3.8%    |
| HP ENVY                | 3         | 3.8%    |
| Dell Vostro            | 3         | 3.8%    |
| Valve Jupiter          | 2         | 2.53%   |
| ASUS K53E              | 2         | 2.53%   |
| Acer Swift             | 2         | 2.53%   |
| Acer Aspire            | 2         | 2.53%   |
| TUXEDO Aura            | 1         | 1.27%   |
| Sony VPCEA36FX         | 1         | 1.27%   |
| Sony VGN-CS320J        | 1         | 1.27%   |
| Sony SVE11113FXW       | 1         | 1.27%   |
| MSI GF65               | 1         | 1.27%   |
| Lenovo Yoga            | 1         | 1.27%   |
| Lenovo Y50-70          | 1         | 1.27%   |
| Lenovo V14-ARE         | 1         | 1.27%   |
| Lenovo IdeaPad         | 1         | 1.27%   |
| Lenovo G50-45          | 1         | 1.27%   |
| HP Stream              | 1         | 1.27%   |
| HP Notebook            | 1         | 1.27%   |
| HP EliteBook           | 1         | 1.27%   |
| HP Compaq              | 1         | 1.27%   |
| HP 250                 | 1         | 1.27%   |
| HP 2000                | 1         | 1.27%   |
| GPU Company GWTN156-9  | 1         | 1.27%   |
| GPU Company GWTN156-11 | 1         | 1.27%   |
| Dell XPS               | 1         | 1.27%   |
| Dell Venue             | 1         | 1.27%   |
| Dell Precision         | 1         | 1.27%   |
| Dell G5                | 1         | 1.27%   |
| AZW GT-R               | 1         | 1.27%   |
| ASUS X540SAA           | 1         | 1.27%   |
| ASUS VivoBook          | 1         | 1.27%   |
| ASUS S500CA            | 1         | 1.27%   |
| ASUS ROG               | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 11        | 13.92%  |
| 2011 | 11        | 13.92%  |
| 2020 | 10        | 12.66%  |
| 2015 | 8         | 10.13%  |
| 2012 | 7         | 8.86%   |
| 2018 | 6         | 7.59%   |
| 2016 | 5         | 6.33%   |
| 2010 | 4         | 5.06%   |
| 2009 | 4         | 5.06%   |
| 2021 | 3         | 3.8%    |
| 2014 | 3         | 3.8%    |
| 2022 | 2         | 2.53%   |
| 2017 | 2         | 2.53%   |
| 2008 | 1         | 1.27%   |
| 2006 | 1         | 1.27%   |
| 2005 | 1         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 79        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 72        | 91.14%  |
| Enabled  | 7         | 8.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 79        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 31        | 37.35%  |
| 3.01-4.0   | 19        | 22.89%  |
| 8.01-16.0  | 18        | 21.69%  |
| 16.01-24.0 | 12        | 14.46%  |
| 1.01-2.0   | 3         | 3.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 46        | 47.92%  |
| 2.01-3.0  | 20        | 20.83%  |
| 3.01-4.0  | 15        | 15.63%  |
| 4.01-8.0  | 10        | 10.42%  |
| 0.51-1.0  | 4         | 4.17%   |
| 8.01-16.0 | 1         | 1.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 71.08%  |
| 2      | 17        | 20.48%  |
| 3      | 5         | 6.02%   |
| 4      | 1         | 1.2%    |
| 0      | 1         | 1.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 62.5%   |
| Yes       | 30        | 37.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 75.95%  |
| No        | 19        | 24.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 98.73%  |
| No        | 1         | 1.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 78.75%  |
| No        | 17        | 21.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Puerto Rico | 79        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San Juan      | 42        | 50%     |
| Bayamón      | 12        | 14.29%  |
| Carolina      | 5         | 5.95%   |
| Ponce         | 4         | 4.76%   |
| Lares         | 3         | 3.57%   |
| Toa Baja      | 2         | 2.38%   |
| Rio Grande    | 2         | 2.38%   |
| Cayey         | 2         | 2.38%   |
| Caguas        | 2         | 2.38%   |
| Cabo Rojo     | 2         | 2.38%   |
| Santa Isabel  | 1         | 1.19%   |
| San Sebastian | 1         | 1.19%   |
| Sabana Grande | 1         | 1.19%   |
| Manati        | 1         | 1.19%   |
| Guaynabo      | 1         | 1.19%   |
| Guayama       | 1         | 1.19%   |
| Canovanas     | 1         | 1.19%   |
| Arecibo       | 1         | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 16        | 19     | 15.53%  |
| Hitachi                   | 11        | 29     | 10.68%  |
| Toshiba                   | 10        | 10     | 9.71%   |
| Crucial                   | 9         | 21     | 8.74%   |
| Unknown                   | 8         | 12     | 7.77%   |
| SanDisk                   | 7         | 8      | 6.8%    |
| SK hynix                  | 6         | 8      | 5.83%   |
| Seagate                   | 6         | 10     | 5.83%   |
| Samsung Electronics       | 5         | 6      | 4.85%   |
| Kingston                  | 4         | 6      | 3.88%   |
| Micron Technology         | 3         | 8      | 2.91%   |
| Intel                     | 2         | 3      | 1.94%   |
| External                  | 2         | 11     | 1.94%   |
| A-DATA Technology         | 2         | 2      | 1.94%   |
| W800SH                    | 1         | 1      | 0.97%   |
| SPCC                      | 1         | 3      | 0.97%   |
| Silicon Motion            | 1         | 1      | 0.97%   |
| PNY                       | 1         | 1      | 0.97%   |
| Phison Electronics        | 1         | 1      | 0.97%   |
| Patriot                   | 1         | 4      | 0.97%   |
| Micron/Crucial Technology | 1         | 3      | 0.97%   |
| KingSpec                  | 1         | 1      | 0.97%   |
| HGST                      | 1         | 1      | 0.97%   |
| China                     | 1         | 2      | 0.97%   |
| Axiom                     | 1         | 7      | 0.97%   |
| Unknown                   | 1         | 1      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Crucial CT240M500SSD1 240GB                 | 4         | 3.7%    |
| Crucial CT240BX500SSD1 240GB                | 4         | 3.7%    |
| WDC WD5000LPVT-22G33T0 500GB                | 3         | 2.78%   |
| Unknown MMC Card  128GB                     | 3         | 2.78%   |
| Hitachi HTS547550A9E384 500GB               | 3         | 2.78%   |
| WDC WD2500BEVS-60UST0 250GB                 | 2         | 1.85%   |
| WDC WD10SPZX-60Z10T0 1TB                    | 2         | 1.85%   |
| Unknown MMC Card  2GB                       | 2         | 1.85%   |
| Toshiba MQ04ABF100 1TB                      | 2         | 1.85%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 1.85%   |
| Toshiba MK3261GSYN 320GB                    | 2         | 1.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB         | 2         | 1.85%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD        | 2         | 1.85%   |
| Hitachi HTS543232A7A384 320GB               | 2         | 1.85%   |
| External USB3.0 1024GB                      | 2         | 1.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 0.93%   |
| WDC WDBNCE0010PNC 1TB SSD                   | 1         | 0.93%   |
| WDC WD5000LPCX-75VHAT0 500GB                | 1         | 0.93%   |
| WDC WD5000BPVT-75HXZT1 500GB                | 1         | 0.93%   |
| WDC WD10SPZX-21Z10T0 1TB                    | 1         | 0.93%   |
| WDC WD10SPCX-75KHST0 1TB                    | 1         | 0.93%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 0.93%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB        | 1         | 0.93%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB        | 1         | 0.93%   |
| W800SH 512GB SSD                            | 1         | 0.93%   |
| Unknown MMC Card  64GB                      | 1         | 0.93%   |
| Unknown MMC Card  10GB                      | 1         | 0.93%   |
| Unknown HBG4a2  32GB                        | 1         | 0.93%   |
| Unknown DA4064  64GB                        | 1         | 0.93%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 0.93%   |
| Toshiba MK6476GSX 640GB                     | 1         | 0.93%   |
| Toshiba MK3276GSX 320GB                     | 1         | 0.93%   |
| Toshiba MK3254GSY 320GB                     | 1         | 0.93%   |
| SPCC M.2 SSD 1TB                            | 1         | 0.93%   |
| SPCC M.2 SSD 1024GB                         | 1         | 0.93%   |
| SK hynix PC401 NVMe Solid State Drive 256GB | 1         | 0.93%   |
| SK hynix NVMe SSD Drive 256GB               | 1         | 0.93%   |
| SK hynix BC511 NVMe 256GB                   | 1         | 0.93%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 12        | 13     | 28.57%  |
| Hitachi  | 11        | 29     | 26.19%  |
| Toshiba  | 10        | 10     | 23.81%  |
| Seagate  | 6         | 10     | 14.29%  |
| External | 2         | 11     | 4.76%   |
| HGST     | 1         | 1      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 21     | 29.03%  |
| SanDisk             | 4         | 4      | 12.9%   |
| Samsung Electronics | 4         | 5      | 12.9%   |
| Kingston            | 3         | 5      | 9.68%   |
| WDC                 | 2         | 3      | 6.45%   |
| A-DATA Technology   | 2         | 2      | 6.45%   |
| W800SH              | 1         | 1      | 3.23%   |
| SPCC                | 1         | 3      | 3.23%   |
| PNY                 | 1         | 1      | 3.23%   |
| Patriot             | 1         | 4      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| KingSpec            | 1         | 1      | 3.23%   |
| China               | 1         | 2      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 38        | 74     | 39.58%  |
| SSD     | 30        | 53     | 31.25%  |
| NVMe    | 18        | 32     | 18.75%  |
| MMC     | 9         | 13     | 9.38%   |
| Unknown | 1         | 7      | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 62        | 122    | 67.39%  |
| NVMe | 18        | 32     | 19.57%  |
| MMC  | 9         | 13     | 9.78%   |
| SAS  | 3         | 12     | 3.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 85     | 64.18%  |
| 0.51-1.0   | 20        | 29     | 29.85%  |
| 1.01-2.0   | 4         | 13     | 5.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 32.63%  |
| 251-500        | 24        | 25.26%  |
| 501-1000       | 16        | 16.84%  |
| 1-20           | 11        | 11.58%  |
| 1001-2000      | 6         | 6.32%   |
| 21-50          | 3         | 3.16%   |
| More than 3000 | 1         | 1.05%   |
| 2001-3000      | 1         | 1.05%   |
| 51-100         | 1         | 1.05%   |
| Unknown        | 1         | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 33        | 32.35%  |
| 21-50     | 23        | 22.55%  |
| 101-250   | 17        | 16.67%  |
| 51-100    | 15        | 14.71%  |
| 251-500   | 6         | 5.88%   |
| 501-1000  | 5         | 4.9%    |
| 2001-3000 | 1         | 0.98%   |
| 1001-2000 | 1         | 0.98%   |
| Unknown   | 1         | 0.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-60UST0 250GB                      | 1         | 1      | 11.11%  |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 11.11%  |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB          | 1         | 1      | 11.11%  |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 11.11%  |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 11.11%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 11.11%  |
| Hitachi HTS545025B9A300 250GB                    | 1         | 1      | 11.11%  |
| Hitachi HTS543232L9A300 320GB                    | 1         | 1      | 11.11%  |
| Crucial CT240M500SSD1 240GB                      | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Toshiba             | 1         | 1      | 11.11%  |
| SK hynix            | 1         | 1      | 11.11%  |
| Seagate             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Micron Technology   | 1         | 1      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

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
| HDD  | 5         | 5      | 55.56%  |
| SSD  | 3         | 3      | 33.33%  |
| NVMe | 1         | 1      | 11.11%  |

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
| Detected | 58        | 150    | 70.73%  |
| Works    | 15        | 20     | 18.29%  |
| Malfunc  | 9         | 9      | 10.98%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 62        | 68.89%  |
| AMD                         | 8         | 8.89%   |
| SK hynix                    | 6         | 6.67%   |
| SanDisk                     | 4         | 4.44%   |
| Nvidia                      | 2         | 2.22%   |
| Micron Technology           | 2         | 2.22%   |
| Silicon Motion              | 1         | 1.11%   |
| Samsung Electronics         | 1         | 1.11%   |
| Phison Electronics          | 1         | 1.11%   |
| Micron/Crucial Technology   | 1         | 1.11%   |
| Kingston Technology Company | 1         | 1.11%   |
| ASMedia Technology          | 1         | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 10.64%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 10.64%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 9.57%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 8.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 5.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 4.26%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 3.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 3.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 3.19%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 2.13%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 2.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 2.13%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 1.06%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.06%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 1.06%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 1         | 1.06%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 1.06%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 1.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 1.06%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 1         | 1.06%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 1.06%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 1         | 1.06%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 1         | 1.06%   |
| Kingston Company KC2000/KC2500 NVMe SSD SM2262EN                                 | 1         | 1.06%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.06%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]               | 1         | 1.06%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 1.06%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.06%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.06%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 58        | 63.04%  |
| NVMe | 18        | 19.57%  |
| RAID | 12        | 13.04%  |
| IDE  | 4         | 4.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 68        | 86.08%  |
| AMD    | 11        | 13.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-6500U CPU @ 2.50GHz        | 4         | 5.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 3         | 3.8%    |
| Intel Core i5-2430M CPU @ 2.40GHz        | 3         | 3.8%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 2         | 2.53%   |
| Intel Pentium CPU N3710 @ 1.60GHz        | 2         | 2.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 2.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 2.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 2.53%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz       | 2         | 2.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 2.53%   |
| AMD Ryzen 5 4500U with Radeon Graphics   | 2         | 2.53%   |
| AMD Custom APU 0405                      | 2         | 2.53%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 1.27%   |
| Intel Pentium CPU P6100 @ 2.00GHz        | 1         | 1.27%   |
| Intel Pentium CPU B980 @ 2.40GHz         | 1         | 1.27%   |
| Intel Genuine CPU T2250 @ 1.73GHz        | 1         | 1.27%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 1         | 1.27%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz       | 1         | 1.27%   |
| Intel Core i7-3740QM CPU @ 2.70GHz       | 1         | 1.27%   |
| Intel Core i7-3540M CPU @ 3.00GHz        | 1         | 1.27%   |
| Intel Core i7-2640M CPU @ 2.80GHz        | 1         | 1.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 1         | 1.27%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 1.27%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 1.27%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 1         | 1.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 1         | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 1.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 1         | 1.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1         | 1.27%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 1.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 1         | 1.27%   |
| Intel Core i5-2450M CPU @ 2.50GHz        | 1         | 1.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 1         | 1.27%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz       | 1         | 1.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 1         | 1.27%   |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 1         | 1.27%   |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 1         | 1.27%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 1         | 1.27%   |
| Intel Core i5 CPU M 460 @ 2.53GHz        | 1         | 1.27%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 1         | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 24        | 30.38%  |
| Intel Core i7        | 15        | 18.99%  |
| Intel Core i3        | 9         | 11.39%  |
| Other                | 5         | 6.33%   |
| Intel Pentium        | 4         | 5.06%   |
| Intel Core 2 Duo     | 4         | 5.06%   |
| Intel Celeron        | 4         | 5.06%   |
| AMD Ryzen 5          | 4         | 5.06%   |
| Intel Pentium Silver | 3         | 3.8%    |
| AMD A8               | 2         | 2.53%   |
| Intel Genuine        | 1         | 1.27%   |
| Intel Core 2         | 1         | 1.27%   |
| AMD Ryzen 3          | 1         | 1.27%   |
| AMD E2               | 1         | 1.27%   |
| AMD A10              | 1         | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 55.7%   |
| 4      | 29        | 36.71%  |
| 6      | 5         | 6.33%   |
| 1      | 1         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 79        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 57        | 72.15%  |
| 1      | 22        | 27.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 78        | 98.73%  |
| 32-bit         | 1         | 1.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 38.82%  |
| 0x206a7    | 11        | 12.94%  |
| 0x20655    | 4         | 4.71%   |
| 0x806ec    | 3         | 3.53%   |
| 0x806ea    | 3         | 3.53%   |
| 0x706a1    | 3         | 3.53%   |
| 0x406e3    | 2         | 2.35%   |
| 0x306d4    | 2         | 2.35%   |
| 0x306a9    | 2         | 2.35%   |
| 0x08600106 | 2         | 2.35%   |
| 0x08108109 | 2         | 2.35%   |
| 0xa0652    | 1         | 1.18%   |
| 0x906ea    | 1         | 1.18%   |
| 0x806eb    | 1         | 1.18%   |
| 0x806e9    | 1         | 1.18%   |
| 0x806c1    | 1         | 1.18%   |
| 0x706e5    | 1         | 1.18%   |
| 0x6e8      | 1         | 1.18%   |
| 0x506c9    | 1         | 1.18%   |
| 0x406c4    | 1         | 1.18%   |
| 0x406c3    | 1         | 1.18%   |
| 0x40651    | 1         | 1.18%   |
| 0x306c3    | 1         | 1.18%   |
| 0x20652    | 1         | 1.18%   |
| 0x10676    | 1         | 1.18%   |
| 0x08600104 | 1         | 1.18%   |
| 0x07030105 | 1         | 1.18%   |
| 0x06003106 | 1         | 1.18%   |
| 0x06001119 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 18.99%  |
| SandyBridge   | 12        | 15.19%  |
| Westmere      | 6         | 7.59%   |
| Skylake       | 5         | 6.33%   |
| Goldmont plus | 5         | 6.33%   |
| Penryn        | 4         | 5.06%   |
| Zen 2         | 3         | 3.8%    |
| TigerLake     | 3         | 3.8%    |
| Silvermont    | 3         | 3.8%    |
| IvyBridge     | 3         | 3.8%    |
| IceLake       | 3         | 3.8%    |
| Haswell       | 3         | 3.8%    |
| Zen+          | 2         | 2.53%   |
| Broadwell     | 2         | 2.53%   |
| Unknown       | 2         | 2.53%   |
| Steamroller   | 1         | 1.27%   |
| Puma          | 1         | 1.27%   |
| Piledriver    | 1         | 1.27%   |
| P6            | 1         | 1.27%   |
| Goldmont      | 1         | 1.27%   |
| Core          | 1         | 1.27%   |
| CometLake     | 1         | 1.27%   |
| Bobcat        | 1         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 66        | 71.74%  |
| AMD    | 15        | 16.3%   |
| Nvidia | 11        | 11.96%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 12.37%  |
| Intel UHD Graphics 620                                                                   | 6         | 6.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 6.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 5.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 3.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.09%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 3.09%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 3.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 3.09%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.09%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 3.09%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 3.09%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 2.06%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 2.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 2.06%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.06%   |
| Intel HD Graphics 620                                                                    | 2         | 2.06%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.06%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 2         | 2.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.03%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.03%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.03%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.03%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 1.03%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 1.03%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.03%   |
| Intel HD Graphics 500                                                                    | 1         | 1.03%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 1         | 1.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.03%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 67.09%  |
| 1 x AMD        | 10        | 12.66%  |
| Intel + Nvidia | 9         | 11.39%  |
| Intel + AMD    | 4         | 5.06%   |
| 2 x Nvidia     | 1         | 1.27%   |
| 2 x AMD        | 1         | 1.27%   |
| 1 x Nvidia     | 1         | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 74        | 91.36%  |
| Proprietary | 5         | 6.17%   |
| Unknown     | 2         | 2.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 77.11%  |
| 0.51-1.0   | 5         | 6.02%   |
| 0.01-0.5   | 5         | 6.02%   |
| 3.01-4.0   | 3         | 3.61%   |
| 1.01-2.0   | 3         | 3.61%   |
| 5.01-6.0   | 2         | 2.41%   |
| 2.01-3.0   | 1         | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 13        | 14.61%  |
| Chimei Innolux          | 12        | 13.48%  |
| AU Optronics            | 12        | 13.48%  |
| Samsung Electronics     | 11        | 12.36%  |
| LG Display              | 11        | 12.36%  |
| Apple                   | 5         | 5.62%   |
| PANDA                   | 3         | 3.37%   |
| Dell                    | 3         | 3.37%   |
| Valve                   | 2         | 2.25%   |
| Sony                    | 2         | 2.25%   |
| Lenovo                  | 2         | 2.25%   |
| Goldstar                | 2         | 2.25%   |
| Chi Mei Optoelectronics | 2         | 2.25%   |
| Sharp                   | 1         | 1.12%   |
| RTK                     | 1         | 1.12%   |
| ONN                     | 1         | 1.12%   |
| InnoLux Display         | 1         | 1.12%   |
| Hewlett-Packard         | 1         | 1.12%   |
| eMachines               | 1         | 1.12%   |
| AOC                     | 1         | 1.12%   |
| Ancor Communications    | 1         | 1.12%   |
| Acer                    | 1         | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 3         | 3.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 3.37%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 2.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 2.25%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 2.25%   |
| Sony TV SNYEB01 1360x768                                              | 1         | 1.12%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 1.12%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 1.12%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC454A 3200x1800 293x165mm 13.2-inch | 1         | 1.12%   |
| RTK ARZOPA RTK3B3D 1920x1080 344x195mm 15.6-inch                      | 1         | 1.12%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 1.12%   |
| PANDA LCD Monitor NCP0030 1920x1080 344x194mm 15.5-inch               | 1         | 1.12%   |
| PANDA LCD Monitor NCP0025 1920x1080 344x194mm 15.5-inch               | 1         | 1.12%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 1.12%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 1.12%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD0513 1920x1080 382x215mm 17.3-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD0492 1920x1080 344x194mm 15.5-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 1         | 1.12%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch               | 1         | 1.12%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch               | 1         | 1.12%   |
| InnoLux Display LCD Monitor INL0028 1366x768 309x174mm 14.0-inch      | 1         | 1.12%   |
| Hewlett-Packard 27ea HPN3395 1920x1080 527x296mm 23.8-inch            | 1         | 1.12%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 1.12%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.12%   |
| eMachines E19T6W EMA0783 1440x900 410x257mm 19.1-inch                 | 1         | 1.12%   |
| Dell S2330MX DELD049 1920x1080 509x286mm 23.0-inch                    | 1         | 1.12%   |
| Dell P2419HC DELA11C 1920x1080 527x296mm 23.8-inch                    | 1         | 1.12%   |
| Dell DELLSE2216HV DELF072 1920x1080 476x268mm 21.5-inch               | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch      | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 34        | 41.46%  |
| 1920x1080 (FHD)  | 31        | 37.8%   |
| 1280x800 (WXGA)  | 6         | 7.32%   |
| 1440x900 (WXGA+) | 3         | 3.66%   |
| 800x1280         | 2         | 2.44%   |
| 1600x900 (HD+)   | 2         | 2.44%   |
| 3840x2160 (4K)   | 1         | 1.22%   |
| 3200x1800 (QHD+) | 1         | 1.22%   |
| 2560x1080        | 1         | 1.22%   |
| 1360x768         | 1         | 1.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 39        | 44.32%  |
| 17     | 8         | 9.09%   |
| 14     | 8         | 9.09%   |
| 13     | 8         | 9.09%   |
| 24     | 4         | 4.55%   |
| 11     | 4         | 4.55%   |
| 31     | 3         | 3.41%   |
| 21     | 3         | 3.41%   |
| 72     | 2         | 2.27%   |
| 12     | 2         | 2.27%   |
| 7      | 2         | 2.27%   |
| 34     | 1         | 1.14%   |
| 27     | 1         | 1.14%   |
| 23     | 1         | 1.14%   |
| 19     | 1         | 1.14%   |
| 18     | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 54.55%  |
| 201-300     | 11        | 12.5%   |
| 351-400     | 10        | 11.36%  |
| 501-600     | 6         | 6.82%   |
| 401-500     | 5         | 5.68%   |
| 601-700     | 3         | 3.41%   |
| 1501-2000   | 2         | 2.27%   |
| 1-100       | 2         | 2.27%   |
| 701-800     | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 68        | 85%     |
| 16/10 | 9         | 11.25%  |
| 0.67  | 2         | 2.5%    |
| 21/9  | 1         | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 44.32%  |
| 81-90          | 14        | 15.91%  |
| 121-130        | 7         | 7.95%   |
| 201-250        | 6         | 6.82%   |
| 51-60          | 4         | 4.55%   |
| 351-500        | 4         | 4.55%   |
| 151-200        | 3         | 3.41%   |
| More than 1000 | 2         | 2.27%   |
| 71-80          | 2         | 2.27%   |
| 61-70          | 2         | 2.27%   |
| 1-40           | 2         | 2.27%   |
| 301-350        | 1         | 1.14%   |
| 141-150        | 1         | 1.14%   |
| 131-140        | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 35        | 39.33%  |
| 121-160       | 30        | 33.71%  |
| 51-100        | 16        | 17.98%  |
| 1-50          | 4         | 4.49%   |
| 161-240       | 3         | 3.37%   |
| More than 240 | 1         | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 65        | 78.31%  |
| 2     | 16        | 19.28%  |
| 0     | 2         | 2.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 43        | 33.33%  |
| Intel                    | 41        | 31.78%  |
| Qualcomm Atheros         | 16        | 12.4%   |
| Broadcom                 | 9         | 6.98%   |
| Marvell Technology Group | 3         | 2.33%   |
| Broadcom Limited         | 3         | 2.33%   |
| Ralink Technology        | 2         | 1.55%   |
| Nvidia                   | 2         | 1.55%   |
| NetGear                  | 2         | 1.55%   |
| ASIX Electronics         | 2         | 1.55%   |
| TP-Link                  | 1         | 0.78%   |
| Samsung Electronics      | 1         | 0.78%   |
| Ralink                   | 1         | 0.78%   |
| MediaTek                 | 1         | 0.78%   |
| Dell                     | 1         | 0.78%   |
| Belkin Components        | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 17.12%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 4.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 4.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 2.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 2.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 2.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 2.05%   |
| Intel Wireless 7265                                               | 3         | 2.05%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.05%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 2.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.05%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.37%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.37%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.37%   |
| Intel Wireless 8260                                               | 2         | 1.37%   |
| Intel Wireless 3160                                               | 2         | 1.37%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 1.37%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 2         | 1.37%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 2         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.37%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                           | 2         | 1.37%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.68%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.68%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.68%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter        | 1         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 41.18%  |
| Realtek Semiconductor | 19        | 22.35%  |
| Qualcomm Atheros      | 13        | 15.29%  |
| Broadcom              | 8         | 9.41%   |
| Ralink Technology     | 2         | 2.35%   |
| Broadcom Limited      | 2         | 2.35%   |
| TP-Link               | 1         | 1.18%   |
| Ralink                | 1         | 1.18%   |
| NetGear               | 1         | 1.18%   |
| MediaTek              | 1         | 1.18%   |
| Dell                  | 1         | 1.18%   |
| Belkin Components     | 1         | 1.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 7         | 8.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 4         | 4.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 4         | 4.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 3         | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 3.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 3         | 3.49%   |
| Intel Wireless 7265                                        | 3         | 3.49%   |
| Intel Wi-Fi 6 AX200                                        | 3         | 3.49%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]               | 3         | 3.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 2.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2         | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 2         | 2.33%   |
| Intel Wireless 8265 / 8275                                 | 2         | 2.33%   |
| Intel Wireless 8260                                        | 2         | 2.33%   |
| Intel Wireless 3160                                        | 2         | 2.33%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 2.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 2         | 2.33%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 2         | 2.33%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 2         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 2.33%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 2         | 2.33%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 2         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 2         | 2.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 1.16%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 1.16%   |
| Realtek 802.11n WLAN Adapter                               | 1         | 1.16%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1         | 1.16%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter | 1         | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1         | 1.16%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]      | 1         | 1.16%   |
| MediaTek WiFi                                              | 1         | 1.16%   |
| Intel Wireless 7260                                        | 1         | 1.16%   |
| Intel Wireless 3165                                        | 1         | 1.16%   |
| Intel WiFi Link 5100                                       | 1         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 1.16%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 32        | 53.33%  |
| Intel                    | 11        | 18.33%  |
| Qualcomm Atheros         | 4         | 6.67%   |
| Marvell Technology Group | 3         | 5%      |
| Broadcom                 | 3         | 5%      |
| Nvidia                   | 2         | 3.33%   |
| ASIX Electronics         | 2         | 3.33%   |
| Samsung Electronics      | 1         | 1.67%   |
| NetGear                  | 1         | 1.67%   |
| Broadcom Limited         | 1         | 1.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 25        | 41.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 5%      |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 5%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 3.33%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 3.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 3.33%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 1.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.67%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.67%   |
| NetGear LB1120-100NAS                                                          | 1         | 1.67%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.67%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.67%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.67%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.67%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 1.67%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.67%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 1.67%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 1.67%   |
| ASIX AX88772B                                                                  | 1         | 1.67%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 56.52%  |
| Ethernet | 60        | 43.48%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 67        | 79.76%  |
| Ethernet | 17        | 20.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 53        | 67.09%  |
| 1     | 23        | 29.11%  |
| 0     | 2         | 2.53%   |
| 3     | 1         | 1.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 71.95%  |
| Yes  | 23        | 28.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 42.86%  |
| Realtek Semiconductor           | 11        | 17.46%  |
| Qualcomm Atheros Communications | 5         | 7.94%   |
| Apple                           | 5         | 7.94%   |
| IMC Networks                    | 4         | 6.35%   |
| Foxconn / Hon Hai               | 3         | 4.76%   |
| Lite-On Technology              | 2         | 3.17%   |
| Dell                            | 2         | 3.17%   |
| Toshiba                         | 1         | 1.59%   |
| Hewlett-Packard                 | 1         | 1.59%   |
| Broadcom                        | 1         | 1.59%   |
| Alps Electric                   | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 11        | 17.46%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 12.7%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 11.11%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 6.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 6.35%   |
| Realtek Bluetooth Radio                                                             | 3         | 4.76%   |
| Intel AX200 Bluetooth                                                               | 3         | 4.76%   |
| Apple Bluetooth Host Controller                                                     | 3         | 4.76%   |
| Intel Bluetooth Device                                                              | 2         | 3.17%   |
| IMC Networks 802.11ac WLAN Adapter                                                  | 2         | 3.17%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 3.17%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.59%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.59%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 1.59%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.59%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.59%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.59%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.59%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.59%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.59%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 66        | 79.52%  |
| AMD    | 11        | 13.25%  |
| Nvidia | 6         | 7.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 13.27%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 10.2%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 6.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 5.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 5.1%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 5.1%    |
| AMD FCH Azalia Controller                                                                         | 4         | 4.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 3.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 3.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 3.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.06%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.04%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.04%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.04%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.04%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.02%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.02%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.02%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.02%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 1.02%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.02%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 9         | 32.14%  |
| Samsung Electronics | 6         | 21.43%  |
| Micron Technology   | 4         | 14.29%  |
| Kingston            | 4         | 14.29%  |
| Silicon Power       | 1         | 3.57%   |
| Ramaxel Technology  | 1         | 3.57%   |
| Qumo                | 1         | 3.57%   |
| PNY                 | 1         | 3.57%   |
| A-DATA Technology   | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s | 2         | 6.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 2         | 6.45%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 3.23%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 1         | 3.23%   |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s             | 1         | 3.23%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 3.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 3.23%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 3.23%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 1         | 3.23%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 3.23%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 3.23%   |
| Silicon Power RAM Module 8GB SODIMM DDR3 1600MT/s         | 1         | 3.23%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 3.23%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 3.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 1         | 3.23%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s  | 1         | 3.23%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 1         | 3.23%   |
| Qumo RAM Module 4GB SODIMM DDR3 1334MT/s                  | 1         | 3.23%   |
| PNY RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 3.23%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s  | 1         | 3.23%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s    | 1         | 3.23%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s      | 1         | 3.23%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 1         | 3.23%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s          | 1         | 3.23%   |
| Kingston RAM KHX1600C9S3K2/8GX 4GB SODIMM DDR3 1334MT/s   | 1         | 3.23%   |
| Kingston RAM HP691160-H66-MCN 8GB SODIMM DDR3 1600MT/s    | 1         | 3.23%   |
| Kingston RAM ACR16D3LS1NGG/4G 4096MB SODIMM DDR3 1600MT/s | 1         | 3.23%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s    | 1         | 3.23%   |
| A-DATA RAM AM1L16BC4R1-B1YS 4GB SODIMM DDR3 800MT/s       | 1         | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 12        | 46.15%  |
| DDR3   | 10        | 38.46%  |
| LPDDR4 | 2         | 7.69%   |
| LPDDR3 | 1         | 3.85%   |
| DDR    | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 96%     |
| Row Of Chips | 1         | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 12        | 46.15%  |
| 4096  | 10        | 38.46%  |
| 16384 | 3         | 11.54%  |
| 2048  | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 9         | 33.33%  |
| 2667  | 7         | 25.93%  |
| 3200  | 4         | 14.81%  |
| 3266  | 1         | 3.7%    |
| 2400  | 1         | 3.7%    |
| 2133  | 1         | 3.7%    |
| 1334  | 1         | 3.7%    |
| 1067  | 1         | 3.7%    |
| 800   | 1         | 3.7%    |
| 667   | 1         | 3.7%    |

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
| Chicony Electronics                    | 11        | 16.42%  |
| Realtek Semiconductor                  | 8         | 11.94%  |
| Ricoh                                  | 5         | 7.46%   |
| IMC Networks                           | 5         | 7.46%   |
| Quanta                                 | 4         | 5.97%   |
| Lite-On Technology                     | 4         | 5.97%   |
| Apple                                  | 4         | 5.97%   |
| Sunplus Innovation Technology          | 3         | 4.48%   |
| Microdia                               | 3         | 4.48%   |
| Luxvisions Innotech Limited            | 3         | 4.48%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.48%   |
| Bison Electronics                      | 3         | 4.48%   |
| Acer                                   | 3         | 4.48%   |
| Syntek                                 | 2         | 2.99%   |
| Suyin                                  | 2         | 2.99%   |
| Lenovo                                 | 2         | 2.99%   |
| Goertek Electronics                    | 1         | 1.49%   |
| Alpha Imaging Technology               | 1         | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Ricoh Integrated Webcam                                        | 3         | 4.48%   |
| Lite-On HP Wide Vision HD Camera                               | 3         | 4.48%   |
| Realtek USB Camera                                             | 2         | 2.99%   |
| Realtek Integrated_Webcam_HD                                   | 2         | 2.99%   |
| Realtek Integrated Webcam HD                                   | 2         | 2.99%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 2.99%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 2.99%   |
| Lenovo Integrated Webcam [R5U877]                              | 2         | 2.99%   |
| IMC Networks UVC VGA Webcam                                    | 2         | 2.99%   |
| Chicony HP Truevision HD                                       | 2         | 2.99%   |
| Chicony HD WebCam                                              | 2         | 2.99%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 2.99%   |
| Apple FaceTime HD Camera                                       | 2         | 2.99%   |
| Apple Built-in iSight                                          | 2         | 2.99%   |
| Syntek Lenovo EasyCamera                                       | 1         | 1.49%   |
| Syntek Integrated Camera                                       | 1         | 1.49%   |
| Suyin USB 2.0 Camera                                           | 1         | 1.49%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.49%   |
| Sunplus USB Camera                                             | 1         | 1.49%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.49%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 1.49%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam       | 1         | 1.49%   |
| Ricoh HD Webcam                                                | 1         | 1.49%   |
| Realtek Integrated Webcam                                      | 1         | 1.49%   |
| Realtek Integrated Camera                                      | 1         | 1.49%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 1.49%   |
| Quanta HD WebCam                                               | 1         | 1.49%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 1.49%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.49%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.49%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.49%   |
| Lite-On HP HD Webcam                                           | 1         | 1.49%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.49%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 1.49%   |
| IMC Networks Integrated Camera                                 | 1         | 1.49%   |
| Goertek USB2.0 VGA UVC WebCam                                  | 1         | 1.49%   |
| Chicony TOSHIBA Web Camera - HD                                | 1         | 1.49%   |
| Chicony Toshiba Integrated Webcam                              | 1         | 1.49%   |
| Chicony Integrated HP HD Webcam                                | 1         | 1.49%   |
| Chicony HP Webcam                                              | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 9         | 64.29%  |
| Synaptics             | 2         | 14.29%  |
| LighTuning Technology | 2         | 14.29%  |
| Upek                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 5         | 35.71%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors Fingerprint scanner                   | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics UWP WBDI                                     | 1         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 4         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom 5880                                                                | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 52        | 65%     |
| 1     | 26        | 32.5%   |
| 2     | 2         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 45.16%  |
| Graphics card            | 6         | 19.35%  |
| Net/wireless             | 4         | 12.9%   |
| Chipcard                 | 4         | 12.9%   |
| Storage                  | 1         | 3.23%   |
| Multimedia controller    | 1         | 3.23%   |
| Communication controller | 1         | 3.23%   |

