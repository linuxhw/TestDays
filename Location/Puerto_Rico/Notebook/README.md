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

Total: 171

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Strix G531GT_G531GT     | [5e505eb9f1](https://linux-hardware.org/?probe=5e505eb9f1) | Feb 02, 2024 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [97575d7173](https://linux-hardware.org/?probe=97575d7173) | Jan 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6723cbd4cd](https://linux-hardware.org/?probe=6723cbd4cd) | Jan 20, 2024 |
| Lenovo        | Y70-70 Touch 80DU           | [fb81d9ccfe](https://linux-hardware.org/?probe=fb81d9ccfe) | Jan 20, 2024 |
| Apple         | MacBook6,1                  | [641df770ba](https://linux-hardware.org/?probe=641df770ba) | Jan 17, 2024 |
| Apple         | MacBookAir8,2               | [d9ddd91356](https://linux-hardware.org/?probe=d9ddd91356) | Jan 07, 2024 |
| Valve         | Jupiter                     | [561c912554](https://linux-hardware.org/?probe=561c912554) | Jan 05, 2024 |
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
| Ubuntu 20.04                 | 16        | 16.67%  |
| Ubuntu 22.04                 | 12        | 12.5%   |
| Ubuntu 18.04                 | 5         | 5.21%   |
| Arch Rolling                 | 3         | 3.13%   |
| Ubuntu 22.10                 | 2         | 2.08%   |
| Ubuntu 21.10                 | 2         | 2.08%   |
| Pop!_OS 22.04                | 2         | 2.08%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 2.08%   |
| OpenMandriva 4.3             | 2         | 2.08%   |
| OpenMandriva 4.2             | 2         | 2.08%   |
| Linux Mint 21                | 2         | 2.08%   |
| Linux Mint 19.3              | 2         | 2.08%   |
| Fedora 38                    | 2         | 2.08%   |
| Fedora 37                    | 2         | 2.08%   |
| Elementary 7                 | 2         | 2.08%   |
| Debian 11                    | 2         | 2.08%   |
| BlackPanther 18.1            | 2         | 2.08%   |
| Zorin 16                     | 1         | 1.04%   |
| Xubuntu 20.04                | 1         | 1.04%   |
| Ubuntu Unity 20.04           | 1         | 1.04%   |
| Ubuntu MATE 20.04            | 1         | 1.04%   |
| Ubuntu 23.10                 | 1         | 1.04%   |
| Ubuntu 23.04                 | 1         | 1.04%   |
| Ubuntu 19.10                 | 1         | 1.04%   |
| SteamOS 3.5.7                | 1         | 1.04%   |
| SteamOS 3.4.4                | 1         | 1.04%   |
| SteamOS 3.4.10               | 1         | 1.04%   |
| ROSA R10                     | 1         | 1.04%   |
| Peppermint 9                 | 1         | 1.04%   |
| Parrot 5.0                   | 1         | 1.04%   |
| Parrot 4.11                  | 1         | 1.04%   |
| openSUSE Leap-15.2           | 1         | 1.04%   |
| OpenMandriva 4.90            | 1         | 1.04%   |
| OpenMandriva 4.50            | 1         | 1.04%   |
| OpenMandriva 23.01           | 1         | 1.04%   |
| LMDE 6                       | 1         | 1.04%   |
| Linux Mint 21.2              | 1         | 1.04%   |
| Linux Mint 21.1              | 1         | 1.04%   |
| Linux Mint 20.1              | 1         | 1.04%   |
| KDE neon 22.04               | 1         | 1.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 35        | 39.33%  |
| OpenMandriva | 7         | 7.87%   |
| Fedora       | 7         | 7.87%   |
| Linux Mint   | 6         | 6.74%   |
| SteamOS      | 3         | 3.37%   |
| openSUSE     | 3         | 3.37%   |
| Debian       | 3         | 3.37%   |
| Arch         | 3         | 3.37%   |
| Pop!_OS      | 2         | 2.25%   |
| Parrot       | 2         | 2.25%   |
| KDE neon     | 2         | 2.25%   |
| Elementary   | 2         | 2.25%   |
| BlackPanther | 2         | 2.25%   |
| Zorin        | 1         | 1.12%   |
| Xubuntu      | 1         | 1.12%   |
| Ubuntu Unity | 1         | 1.12%   |
| Ubuntu MATE  | 1         | 1.12%   |
| ROSA         | 1         | 1.12%   |
| Peppermint   | 1         | 1.12%   |
| LMDE         | 1         | 1.12%   |
| Endless      | 1         | 1.12%   |
| EndeavourOS  | 1         | 1.12%   |
| ArcoLinux    | 1         | 1.12%   |
| Alpine       | 1         | 1.12%   |
| AlmaLinux    | 1         | 1.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 6.2.0-34-generic           | 3         | 2.42%   |
| 5.8.0-59-generic           | 3         | 2.42%   |
| 6.5.0-14-generic           | 2         | 1.61%   |
| 6.3.6-200.fc38.x86_64      | 2         | 1.61%   |
| 6.2.0-32-generic           | 2         | 1.61%   |
| 6.2.0-31-generic           | 2         | 1.61%   |
| 5.8.0-55-generic           | 2         | 1.61%   |
| 5.4.0-58-generic           | 2         | 1.61%   |
| 5.19.0-42-generic          | 2         | 1.61%   |
| 5.19.0-38-generic          | 2         | 1.61%   |
| 5.16.7-desktop-1omv4003    | 2         | 1.61%   |
| 5.15.0-58-generic          | 2         | 1.61%   |
| 5.15.0-46-generic          | 2         | 1.61%   |
| 5.15.0-25-generic          | 2         | 1.61%   |
| 5.13.0-35-generic          | 2         | 1.61%   |
| 5.11.0-38-generic          | 2         | 1.61%   |
| 5.11.0-27-generic          | 2         | 1.61%   |
| 5.10.14-desktop-1omv4002   | 2         | 1.61%   |
| 5.10.0-19-amd64            | 2         | 1.61%   |
| 6.7.0-060700rc4-generic    | 1         | 0.81%   |
| 6.6.8-200.t2.fc39.x86_64   | 1         | 0.81%   |
| 6.6.2-x64v4-xanmod1        | 1         | 0.81%   |
| 6.6.1-arch1-1              | 1         | 0.81%   |
| 6.5.9-1-default            | 1         | 0.81%   |
| 6.5.0-15-generic           | 1         | 0.81%   |
| 6.4.6-76060406-generic     | 1         | 0.81%   |
| 6.4.15-200.fc38.x86_64     | 1         | 0.81%   |
| 6.4.11-060411-generic      | 1         | 0.81%   |
| 6.2.9-1-default            | 1         | 0.81%   |
| 6.2.8-200.fc37.x86_64      | 1         | 0.81%   |
| 6.2.6-76060206-generic     | 1         | 0.81%   |
| 6.2.12-arch1-1             | 1         | 0.81%   |
| 6.2.0-36-generic           | 1         | 0.81%   |
| 6.2.0-35-generic           | 1         | 0.81%   |
| 6.2.0-26-generic           | 1         | 0.81%   |
| 6.1.71-haos                | 1         | 0.81%   |
| 6.1.60-1-lts               | 1         | 0.81%   |
| 6.1.52-valve9-1-neptune-61 | 1         | 0.81%   |
| 6.1.1-desktop-1omv2290     | 1         | 0.81%   |
| 6.1.0-13-amd64             | 1         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 13        | 12.75%  |
| 5.13.0  | 8         | 7.84%   |
| 6.2.0   | 7         | 6.86%   |
| 5.19.0  | 7         | 6.86%   |
| 5.15.0  | 7         | 6.86%   |
| 5.11.0  | 5         | 4.9%    |
| 5.8.0   | 4         | 3.92%   |
| 6.5.0   | 3         | 2.94%   |
| 5.3.0   | 3         | 2.94%   |
| 5.10.0  | 3         | 2.94%   |
| 4.15.0  | 3         | 2.94%   |
| 6.3.6   | 2         | 1.96%   |
| 5.16.7  | 2         | 1.96%   |
| 5.10.14 | 2         | 1.96%   |
| 6.7.0   | 1         | 0.98%   |
| 6.6.8   | 1         | 0.98%   |
| 6.6.2   | 1         | 0.98%   |
| 6.6.1   | 1         | 0.98%   |
| 6.5.9   | 1         | 0.98%   |
| 6.4.6   | 1         | 0.98%   |
| 6.4.15  | 1         | 0.98%   |
| 6.4.11  | 1         | 0.98%   |
| 6.2.9   | 1         | 0.98%   |
| 6.2.8   | 1         | 0.98%   |
| 6.2.6   | 1         | 0.98%   |
| 6.2.12  | 1         | 0.98%   |
| 6.1.71  | 1         | 0.98%   |
| 6.1.60  | 1         | 0.98%   |
| 6.1.52  | 1         | 0.98%   |
| 6.1.1   | 1         | 0.98%   |
| 6.1.0   | 1         | 0.98%   |
| 5.9.16  | 1         | 0.98%   |
| 5.6.14  | 1         | 0.98%   |
| 5.3.6   | 1         | 0.98%   |
| 5.3.18  | 1         | 0.98%   |
| 5.19.7  | 1         | 0.98%   |
| 5.18.6  | 1         | 0.98%   |
| 5.18.15 | 1         | 0.98%   |
| 5.18.12 | 1         | 0.98%   |
| 5.18.0  | 1         | 0.98%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 13        | 12.87%  |
| 6.2     | 11        | 10.89%  |
| 5.19    | 8         | 7.92%   |
| 5.15    | 8         | 7.92%   |
| 5.13    | 8         | 7.92%   |
| 5.11    | 6         | 5.94%   |
| 6.1     | 5         | 4.95%   |
| 5.3     | 5         | 4.95%   |
| 5.10    | 5         | 4.95%   |
| 6.5     | 4         | 3.96%   |
| 5.8     | 4         | 3.96%   |
| 6.6     | 3         | 2.97%   |
| 6.4     | 3         | 2.97%   |
| 5.18    | 3         | 2.97%   |
| 4.15    | 3         | 2.97%   |
| 6.3     | 2         | 1.98%   |
| 5.16    | 2         | 1.98%   |
| 6.7     | 1         | 0.99%   |
| 5.9     | 1         | 0.99%   |
| 5.6     | 1         | 0.99%   |
| 5.14    | 1         | 0.99%   |
| 5.12    | 1         | 0.99%   |
| 4.9     | 1         | 0.99%   |
| 4.19    | 1         | 0.99%   |
| 4.18    | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 81        | 97.59%  |
| i686   | 2         | 2.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 45        | 52.33%  |
| KDE5       | 18        | 20.93%  |
| X-Cinnamon | 5         | 5.81%   |
| MATE       | 4         | 4.65%   |
| XFCE       | 3         | 3.49%   |
| Unknown    | 3         | 3.49%   |
| Pantheon   | 2         | 2.33%   |
| i3         | 2         | 2.33%   |
| Unity      | 1         | 1.16%   |
| LXDE       | 1         | 1.16%   |
| KDE4       | 1         | 1.16%   |
| awesome    | 1         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 65        | 74.71%  |
| Wayland | 21        | 24.14%  |
| Unknown | 1         | 1.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 47        | 52.22%  |
| GDM3    | 21        | 23.33%  |
| SDDM    | 10        | 11.11%  |
| GDM     | 6         | 6.67%   |
| LightDM | 3         | 3.33%   |
| TDM     | 2         | 2.22%   |
| KDM     | 1         | 1.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 72        | 85.71%  |
| es_PR   | 5         | 5.95%   |
| Unknown | 5         | 5.95%   |
| C       | 2         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 48        | 56.47%  |
| EFI  | 37        | 43.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 57        | 63.33%  |
| Btrfs   | 12        | 13.33%  |
| Overlay | 9         | 10%     |
| Tmpfs   | 8         | 8.89%   |
| Unknown | 2         | 2.22%   |
| Zfs     | 1         | 1.11%   |
| Xfs     | 1         | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 54        | 60%     |
| GPT     | 30        | 33.33%  |
| MBR     | 6         | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 82.95%  |
| Yes       | 15        | 17.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 75.86%  |
| Yes       | 21        | 24.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 22        | 26.51%  |
| Dell             | 17        | 20.48%  |
| Lenovo           | 12        | 14.46%  |
| ASUSTek Computer | 7         | 8.43%   |
| Apple            | 6         | 7.23%   |
| Acer             | 4         | 4.82%   |
| Valve            | 3         | 3.61%   |
| Toshiba          | 3         | 3.61%   |
| Sony             | 3         | 3.61%   |
| GPU Company      | 2         | 2.41%   |
| TUXEDO           | 1         | 1.2%    |
| MSI              | 1         | 1.2%    |
| AZW              | 1         | 1.2%    |
| AMI              | 1         | 1.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Valve Jupiter                            | 3         | 3.61%   |
| Dell Vostro 3550                         | 3         | 3.61%   |
| Dell Inspiron 11-3168                    | 2         | 2.41%   |
| ASUS K53E                                | 2         | 2.41%   |
| TUXEDO Aura 15 Gen1                      | 1         | 1.2%    |
| Toshiba Satellite P755                   | 1         | 1.2%    |
| Toshiba Satellite L655                   | 1         | 1.2%    |
| Toshiba Satellite C55-C                  | 1         | 1.2%    |
| Sony VPCEA36FX                           | 1         | 1.2%    |
| Sony VGN-CS320J                          | 1         | 1.2%    |
| Sony SVE11113FXW                         | 1         | 1.2%    |
| MSI GF65 Thin 10SDR                      | 1         | 1.2%    |
| Lenovo Yoga 900-13ISK 80MK               | 1         | 1.2%    |
| Lenovo Y70-70 Touch 80DU                 | 1         | 1.2%    |
| Lenovo Y50-70 Touch 20349                | 1         | 1.2%    |
| Lenovo V14-ARE 82DQ                      | 1         | 1.2%    |
| Lenovo ThinkPad X1 Carbon 7th 20QD0000US | 1         | 1.2%    |
| Lenovo ThinkPad T510 4314RBS             | 1         | 1.2%    |
| Lenovo ThinkPad T410 2516ADU             | 1         | 1.2%    |
| Lenovo ThinkPad E570 20H50048US          | 1         | 1.2%    |
| Lenovo ThinkPad E560 20EV002JUS          | 1         | 1.2%    |
| Lenovo ThinkPad E14 20RA004WUS           | 1         | 1.2%    |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 1.2%    |
| Lenovo G50-45 80E3                       | 1         | 1.2%    |
| HP Stream Laptop 14-CB1xxx               | 1         | 1.2%    |
| HP ProBook 6560b                         | 1         | 1.2%    |
| HP ProBook 6450b                         | 1         | 1.2%    |
| HP ProBook 450 G5                        | 1         | 1.2%    |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 1.2%    |
| HP Pavilion Laptop 15-cs2xxx             | 1         | 1.2%    |
| HP Pavilion Laptop 15-cs0xxx             | 1         | 1.2%    |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 1         | 1.2%    |
| HP Notebook                              | 1         | 1.2%    |
| HP Laptop 17-by3xxx                      | 1         | 1.2%    |
| HP Laptop 15-dy2xxx                      | 1         | 1.2%    |
| HP Laptop 15-dy1xxx                      | 1         | 1.2%    |
| HP Laptop 15-dw0xxx                      | 1         | 1.2%    |
| HP Laptop 14-dq0xxx                      | 1         | 1.2%    |
| HP Laptop 14-dk1xxx                      | 1         | 1.2%    |
| HP ENVY Laptop 17m-bw0xxx                | 1         | 1.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 6         | 7.23%   |
| HP Laptop              | 6         | 7.23%   |
| Dell Inspiron          | 6         | 7.23%   |
| HP Pavilion            | 4         | 4.82%   |
| Dell Latitude          | 4         | 4.82%   |
| Valve Jupiter          | 3         | 3.61%   |
| Toshiba Satellite      | 3         | 3.61%   |
| HP ProBook             | 3         | 3.61%   |
| HP ENVY                | 3         | 3.61%   |
| Dell Vostro            | 3         | 3.61%   |
| ASUS ROG               | 2         | 2.41%   |
| ASUS K53E              | 2         | 2.41%   |
| Acer Swift             | 2         | 2.41%   |
| Acer Aspire            | 2         | 2.41%   |
| TUXEDO Aura            | 1         | 1.2%    |
| Sony VPCEA36FX         | 1         | 1.2%    |
| Sony VGN-CS320J        | 1         | 1.2%    |
| Sony SVE11113FXW       | 1         | 1.2%    |
| MSI GF65               | 1         | 1.2%    |
| Lenovo Yoga            | 1         | 1.2%    |
| Lenovo Y70-70          | 1         | 1.2%    |
| Lenovo Y50-70          | 1         | 1.2%    |
| Lenovo V14-ARE         | 1         | 1.2%    |
| Lenovo IdeaPad         | 1         | 1.2%    |
| Lenovo G50-45          | 1         | 1.2%    |
| HP Stream              | 1         | 1.2%    |
| HP Notebook            | 1         | 1.2%    |
| HP EliteBook           | 1         | 1.2%    |
| HP Compaq              | 1         | 1.2%    |
| HP 250                 | 1         | 1.2%    |
| HP 2000                | 1         | 1.2%    |
| GPU Company GWTN156-9  | 1         | 1.2%    |
| GPU Company GWTN156-11 | 1         | 1.2%    |
| Dell XPS               | 1         | 1.2%    |
| Dell Venue             | 1         | 1.2%    |
| Dell Precision         | 1         | 1.2%    |
| Dell G5                | 1         | 1.2%    |
| AZW GT-R               | 1         | 1.2%    |
| ASUS X540SAA           | 1         | 1.2%    |
| ASUS VivoBook          | 1         | 1.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 12        | 14.46%  |
| 2011 | 11        | 13.25%  |
| 2020 | 10        | 12.05%  |
| 2015 | 8         | 9.64%   |
| 2012 | 7         | 8.43%   |
| 2018 | 6         | 7.23%   |
| 2016 | 5         | 6.02%   |
| 2014 | 4         | 4.82%   |
| 2010 | 4         | 4.82%   |
| 2009 | 4         | 4.82%   |
| 2021 | 3         | 3.61%   |
| 2023 | 2         | 2.41%   |
| 2022 | 2         | 2.41%   |
| 2017 | 2         | 2.41%   |
| 2008 | 1         | 1.2%    |
| 2006 | 1         | 1.2%    |
| 2005 | 1         | 1.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 83        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 76        | 91.57%  |
| Enabled  | 7         | 8.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 32        | 36.36%  |
| 8.01-16.0  | 20        | 22.73%  |
| 3.01-4.0   | 19        | 21.59%  |
| 16.01-24.0 | 13        | 14.77%  |
| 1.01-2.0   | 3         | 3.41%   |
| 32.01-64.0 | 1         | 1.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 47        | 46.08%  |
| 2.01-3.0  | 21        | 20.59%  |
| 3.01-4.0  | 16        | 15.69%  |
| 4.01-8.0  | 13        | 12.75%  |
| 0.51-1.0  | 4         | 3.92%   |
| 8.01-16.0 | 1         | 0.98%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 61        | 69.32%  |
| 2      | 20        | 22.73%  |
| 3      | 5         | 5.68%   |
| 4      | 1         | 1.14%   |
| 0      | 1         | 1.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 64.29%  |
| Yes       | 30        | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 77.11%  |
| No        | 19        | 22.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 98.8%   |
| No        | 1         | 1.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 78.57%  |
| No        | 18        | 21.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Puerto Rico | 83        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San Juan      | 43        | 48.31%  |
| Bayamón      | 14        | 15.73%  |
| Carolina      | 5         | 5.62%   |
| Ponce         | 4         | 4.49%   |
| Rio Grande    | 3         | 3.37%   |
| Lares         | 3         | 3.37%   |
| Caguas        | 3         | 3.37%   |
| Toa Baja      | 2         | 2.25%   |
| Cayey         | 2         | 2.25%   |
| Cabo Rojo     | 2         | 2.25%   |
| Santa Isabel  | 1         | 1.12%   |
| San Sebastian | 1         | 1.12%   |
| Sabana Grande | 1         | 1.12%   |
| Manati        | 1         | 1.12%   |
| Guaynabo      | 1         | 1.12%   |
| Guayama       | 1         | 1.12%   |
| Canovanas     | 1         | 1.12%   |
| Arecibo       | 1         | 1.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 16        | 19     | 14.55%  |
| Toshiba                     | 11        | 12     | 10%     |
| Hitachi                     | 11        | 30     | 10%     |
| Unknown                     | 9         | 13     | 8.18%   |
| Crucial                     | 9         | 21     | 8.18%   |
| SanDisk                     | 7         | 9      | 6.36%   |
| SK hynix                    | 6         | 8      | 5.45%   |
| Seagate                     | 6         | 10     | 5.45%   |
| Samsung Electronics         | 6         | 7      | 5.45%   |
| Micron Technology           | 4         | 10     | 3.64%   |
| Kingston                    | 4         | 6      | 3.64%   |
| External                    | 3         | 12     | 2.73%   |
| Intel                       | 2         | 3      | 1.82%   |
| A-DATA Technology           | 2         | 2      | 1.82%   |
| W800SH                      | 1         | 1      | 0.91%   |
| SPCC                        | 1         | 3      | 0.91%   |
| Silicon Motion              | 1         | 1      | 0.91%   |
| PNY                         | 1         | 1      | 0.91%   |
| Phison Electronics          | 1         | 1      | 0.91%   |
| Patriot                     | 1         | 4      | 0.91%   |
| Micron/Crucial Technology   | 1         | 3      | 0.91%   |
| Kingston Technology Company | 1         | 1      | 0.91%   |
| KingSpec                    | 1         | 1      | 0.91%   |
| HGST                        | 1         | 1      | 0.91%   |
| China                       | 1         | 2      | 0.91%   |
| Axiom                       | 1         | 7      | 0.91%   |
| Apple                       | 1         | 1      | 0.91%   |
| Unknown                     | 1         | 1      | 0.91%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Crucial CT240M500SSD1 240GB                 | 4         | 3.48%   |
| Crucial CT240BX500SSD1 240GB                | 4         | 3.48%   |
| WDC WD5000LPVT-22G33T0 500GB                | 3         | 2.61%   |
| Unknown MMC Card  128GB                     | 3         | 2.61%   |
| Toshiba MQ04ABF100 1TB                      | 3         | 2.61%   |
| Hitachi HTS547550A9E384 500GB               | 3         | 2.61%   |
| External USB3.0 752GB                       | 3         | 2.61%   |
| WDC WD2500BEVS-60UST0 250GB                 | 2         | 1.74%   |
| WDC WD10SPZX-60Z10T0 1TB                    | 2         | 1.74%   |
| Unknown MMC Card  2GB                       | 2         | 1.74%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 1.74%   |
| Toshiba MK3261GSYN 320GB                    | 2         | 1.74%   |
| Seagate ST500LM012 HN-M500MBB 500GB         | 2         | 1.74%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD        | 2         | 1.74%   |
| Micron 2200V_MTFDHBA512TCK 512GB            | 2         | 1.74%   |
| Hitachi HTS543232A7A384 320GB               | 2         | 1.74%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 0.87%   |
| WDC WDBNCE0010PNC 1TB SSD                   | 1         | 0.87%   |
| WDC WD5000LPCX-75VHAT0 500GB                | 1         | 0.87%   |
| WDC WD5000BPVT-75HXZT1 500GB                | 1         | 0.87%   |
| WDC WD10SPZX-21Z10T0 1TB                    | 1         | 0.87%   |
| WDC WD10SPCX-75KHST0 1TB                    | 1         | 0.87%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 0.87%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB        | 1         | 0.87%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB        | 1         | 0.87%   |
| W800SH 512GB SSD                            | 1         | 0.87%   |
| Unknown MMC Card  64GB                      | 1         | 0.87%   |
| Unknown MMC Card  512GB                     | 1         | 0.87%   |
| Unknown MMC Card  10GB                      | 1         | 0.87%   |
| Unknown HBG4a2  32GB                        | 1         | 0.87%   |
| Unknown DA4064  64GB                        | 1         | 0.87%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 0.87%   |
| Toshiba MK6476GSX 640GB                     | 1         | 0.87%   |
| Toshiba MK3276GSX 320GB                     | 1         | 0.87%   |
| Toshiba MK3254GSY 320GB                     | 1         | 0.87%   |
| SPCC M.2 SSD 1TB                            | 1         | 0.87%   |
| SPCC M.2 SSD 1024GB                         | 1         | 0.87%   |
| SK hynix PC401 NVMe Solid State Drive 256GB | 1         | 0.87%   |
| SK hynix NVMe SSD Drive 256GB               | 1         | 0.87%   |
| SK hynix BC511 NVMe 256GB                   | 1         | 0.87%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 12        | 13     | 27.27%  |
| Toshiba  | 11        | 12     | 25%     |
| Hitachi  | 11        | 30     | 25%     |
| Seagate  | 6         | 10     | 13.64%  |
| External | 3         | 12     | 6.82%   |
| HGST     | 1         | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 21     | 28.13%  |
| Samsung Electronics | 5         | 6      | 15.63%  |
| SanDisk             | 4         | 4      | 12.5%   |
| Kingston            | 3         | 5      | 9.38%   |
| WDC                 | 2         | 3      | 6.25%   |
| A-DATA Technology   | 2         | 2      | 6.25%   |
| W800SH              | 1         | 1      | 3.13%   |
| SPCC                | 1         | 3      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| Patriot             | 1         | 4      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| KingSpec            | 1         | 1      | 3.13%   |
| China               | 1         | 2      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 40        | 78     | 38.83%  |
| SSD     | 31        | 54     | 30.1%   |
| NVMe    | 21        | 37     | 20.39%  |
| MMC     | 10        | 14     | 9.71%   |
| Unknown | 1         | 7      | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 64        | 126    | 64.65%  |
| NVMe | 21        | 37     | 21.21%  |
| MMC  | 10        | 14     | 10.1%   |
| SAS  | 4         | 13     | 4.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 86     | 62.32%  |
| 0.51-1.0   | 24        | 44     | 34.78%  |
| 1.01-2.0   | 2         | 2      | 2.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 31%     |
| 251-500        | 24        | 24%     |
| 501-1000       | 19        | 19%     |
| 1-20           | 12        | 12%     |
| 1001-2000      | 6         | 6%      |
| 21-50          | 3         | 3%      |
| More than 3000 | 2         | 2%      |
| 2001-3000      | 1         | 1%      |
| 51-100         | 1         | 1%      |
| Unknown        | 1         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 34        | 31.78%  |
| 21-50     | 23        | 21.5%   |
| 101-250   | 18        | 16.82%  |
| 51-100    | 15        | 14.02%  |
| 501-1000  | 7         | 6.54%   |
| 251-500   | 6         | 5.61%   |
| 1001-2000 | 2         | 1.87%   |
| 2001-3000 | 1         | 0.93%   |
| Unknown   | 1         | 0.93%   |

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
| Detected | 61        | 160    | 70.93%  |
| Works    | 16        | 21     | 18.6%   |
| Malfunc  | 9         | 9      | 10.47%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 64        | 67.37%  |
| AMD                         | 8         | 8.42%   |
| SK hynix                    | 6         | 6.32%   |
| SanDisk                     | 4         | 4.21%   |
| Micron Technology           | 3         | 3.16%   |
| Nvidia                      | 2         | 2.11%   |
| Kingston Technology Company | 2         | 2.11%   |
| Silicon Motion              | 1         | 1.05%   |
| Samsung Electronics         | 1         | 1.05%   |
| Phison Electronics          | 1         | 1.05%   |
| Micron/Crucial Technology   | 1         | 1.05%   |
| ASMedia Technology          | 1         | 1.05%   |
| Apple                       | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 10.1%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 10.1%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 8.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 5.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 4.04%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 3.03%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 2.02%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 2.02%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 2.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.02%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 2.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 2.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 2.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 2.02%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.01%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 1.01%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 1         | 1.01%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 1.01%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 1.01%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 1.01%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 1         | 1.01%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 1.01%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 1         | 1.01%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.01%   |
| Kingston Company KC2000/KC2500 NVMe SSD SM2262EN                                 | 1         | 1.01%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.01%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]               | 1         | 1.01%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 1.01%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 60        | 61.86%  |
| NVMe | 21        | 21.65%  |
| RAID | 12        | 12.37%  |
| IDE  | 4         | 4.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 71        | 85.54%  |
| AMD    | 12        | 14.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-6500U CPU @ 2.50GHz        | 4         | 4.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 3         | 3.61%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 3         | 3.61%   |
| AMD Custom APU 0405                      | 3         | 3.61%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 2         | 2.41%   |
| Intel Pentium CPU N3710 @ 1.60GHz        | 2         | 2.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 2         | 2.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 2.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 2.41%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 2.41%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz       | 2         | 2.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 2.41%   |
| AMD Ryzen 5 4500U with Radeon Graphics   | 2         | 2.41%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 1.2%    |
| Intel Pentium CPU P6100 @ 2.00GHz        | 1         | 1.2%    |
| Intel Pentium CPU B980 @ 2.40GHz         | 1         | 1.2%    |
| Intel Genuine CPU T2250 @ 1.73GHz        | 1         | 1.2%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz       | 1         | 1.2%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz       | 1         | 1.2%    |
| Intel Core i7-3740QM CPU @ 2.70GHz       | 1         | 1.2%    |
| Intel Core i7-3540M CPU @ 3.00GHz        | 1         | 1.2%    |
| Intel Core i7-2640M CPU @ 2.80GHz        | 1         | 1.2%    |
| Intel Core i7-10750H CPU @ 2.60GHz       | 1         | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 1.2%    |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 1.2%    |
| Intel Core i5-8350U CPU @ 1.70GHz        | 1         | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz        | 1         | 1.2%    |
| Intel Core i5-8210Y CPU @ 1.60GHz        | 1         | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz        | 1         | 1.2%    |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 1.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz        | 1         | 1.2%    |
| Intel Core i5-2450M CPU @ 2.50GHz        | 1         | 1.2%    |
| Intel Core i5-2410M CPU @ 2.30GHz        | 1         | 1.2%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz       | 1         | 1.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz       | 1         | 1.2%    |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 1         | 1.2%    |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 1         | 1.2%    |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 1         | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 25        | 30.12%  |
| Intel Core i7        | 17        | 20.48%  |
| Intel Core i3        | 9         | 10.84%  |
| Other                | 6         | 7.23%   |
| Intel Pentium        | 4         | 4.82%   |
| Intel Core 2 Duo     | 4         | 4.82%   |
| Intel Celeron        | 4         | 4.82%   |
| AMD Ryzen 5          | 4         | 4.82%   |
| Intel Pentium Silver | 3         | 3.61%   |
| AMD A8               | 2         | 2.41%   |
| Intel Genuine        | 1         | 1.2%    |
| Intel Core 2         | 1         | 1.2%    |
| AMD Ryzen 3          | 1         | 1.2%    |
| AMD E2               | 1         | 1.2%    |
| AMD A10              | 1         | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 45        | 54.22%  |
| 4      | 31        | 37.35%  |
| 6      | 6         | 7.23%   |
| 1      | 1         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 83        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 61        | 73.49%  |
| 1      | 22        | 26.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 81        | 97.59%  |
| 32-bit         | 1         | 1.2%    |
| Unknown        | 1         | 1.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 40.45%  |
| 0x206a7    | 11        | 12.36%  |
| 0x20655    | 4         | 4.49%   |
| 0x806ec    | 3         | 3.37%   |
| 0x806ea    | 3         | 3.37%   |
| 0x706a1    | 3         | 3.37%   |
| 0x406e3    | 2         | 2.25%   |
| 0x306d4    | 2         | 2.25%   |
| 0x306c3    | 2         | 2.25%   |
| 0x306a9    | 2         | 2.25%   |
| 0x08600106 | 2         | 2.25%   |
| 0x08108109 | 2         | 2.25%   |
| 0xa0652    | 1         | 1.12%   |
| 0x906ea    | 1         | 1.12%   |
| 0x806eb    | 1         | 1.12%   |
| 0x806e9    | 1         | 1.12%   |
| 0x806c1    | 1         | 1.12%   |
| 0x706e5    | 1         | 1.12%   |
| 0x6e8      | 1         | 1.12%   |
| 0x506c9    | 1         | 1.12%   |
| 0x406c4    | 1         | 1.12%   |
| 0x406c3    | 1         | 1.12%   |
| 0x40651    | 1         | 1.12%   |
| 0x20652    | 1         | 1.12%   |
| 0x10676    | 1         | 1.12%   |
| 0x08600104 | 1         | 1.12%   |
| 0x07030105 | 1         | 1.12%   |
| 0x06003106 | 1         | 1.12%   |
| 0x06001119 | 1         | 1.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 20.48%  |
| SandyBridge   | 12        | 14.46%  |
| Westmere      | 6         | 7.23%   |
| Skylake       | 5         | 6.02%   |
| Goldmont plus | 5         | 6.02%   |
| Penryn        | 4         | 4.82%   |
| Haswell       | 4         | 4.82%   |
| Zen 2         | 3         | 3.61%   |
| TigerLake     | 3         | 3.61%   |
| Silvermont    | 3         | 3.61%   |
| IvyBridge     | 3         | 3.61%   |
| IceLake       | 3         | 3.61%   |
| Unknown       | 3         | 3.61%   |
| Zen+          | 2         | 2.41%   |
| Broadwell     | 2         | 2.41%   |
| Steamroller   | 1         | 1.2%    |
| Puma          | 1         | 1.2%    |
| Piledriver    | 1         | 1.2%    |
| P6            | 1         | 1.2%    |
| Goldmont      | 1         | 1.2%    |
| Core          | 1         | 1.2%    |
| CometLake     | 1         | 1.2%    |
| Bobcat        | 1         | 1.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 70.41%  |
| AMD    | 16        | 16.33%  |
| Nvidia | 13        | 13.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 11.65%  |
| Intel UHD Graphics 620                                                                   | 6         | 5.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 5.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 4.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.91%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 2.91%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 2.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.91%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 2.91%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 3         | 2.91%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 2.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.94%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.94%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 1.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.94%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.94%   |
| Intel HD Graphics 620                                                                    | 2         | 1.94%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.97%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.97%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.97%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.97%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.97%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 0.97%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.97%   |
| Intel UHD Graphics 617                                                                   | 1         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.97%   |
| Intel HD Graphics 500                                                                    | 1         | 0.97%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 1         | 0.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 54        | 65.06%  |
| Intel + Nvidia | 11        | 13.25%  |
| 1 x AMD        | 11        | 13.25%  |
| Intel + AMD    | 4         | 4.82%   |
| 2 x Nvidia     | 1         | 1.2%    |
| 2 x AMD        | 1         | 1.2%    |
| 1 x Nvidia     | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 78        | 91.76%  |
| Proprietary | 5         | 5.88%   |
| Unknown     | 2         | 2.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 78.16%  |
| 0.51-1.0   | 5         | 5.75%   |
| 0.01-0.5   | 5         | 5.75%   |
| 3.01-4.0   | 3         | 3.45%   |
| 1.01-2.0   | 3         | 3.45%   |
| 5.01-6.0   | 2         | 2.3%    |
| 2.01-3.0   | 1         | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 13        | 13.83%  |
| LG Display              | 12        | 12.77%  |
| Chimei Innolux          | 12        | 12.77%  |
| AU Optronics            | 12        | 12.77%  |
| Samsung Electronics     | 11        | 11.7%   |
| Apple                   | 6         | 6.38%   |
| PANDA                   | 4         | 4.26%   |
| Valve                   | 3         | 3.19%   |
| Dell                    | 3         | 3.19%   |
| Sony                    | 2         | 2.13%   |
| Lenovo                  | 2         | 2.13%   |
| Goldstar                | 2         | 2.13%   |
| Chi Mei Optoelectronics | 2         | 2.13%   |
| Unknown (XXX)           | 1         | 1.06%   |
| Sharp                   | 1         | 1.06%   |
| RTK                     | 1         | 1.06%   |
| ONN                     | 1         | 1.06%   |
| InnoLux Display         | 1         | 1.06%   |
| Hewlett-Packard         | 1         | 1.06%   |
| eMachines               | 1         | 1.06%   |
| AOC                     | 1         | 1.06%   |
| Ancor Communications    | 1         | 1.06%   |
| Acer                    | 1         | 1.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 3         | 3.19%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 3         | 3.19%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 3.19%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 2.13%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 2.13%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch        | 1         | 1.06%   |
| Sony TV SNYEB01 1360x768                                              | 1         | 1.06%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 1.06%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 1.06%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC454A 3200x1800 293x165mm 13.2-inch | 1         | 1.06%   |
| RTK ARZOPA RTK3B3D 1920x1080 344x195mm 15.6-inch                      | 1         | 1.06%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 1.06%   |
| PANDA LCD Monitor NCP0030 1920x1080 344x194mm 15.5-inch               | 1         | 1.06%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 1.06%   |
| PANDA LCD Monitor NCP0025 1920x1080 344x194mm 15.5-inch               | 1         | 1.06%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 1.06%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 1.06%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD0513 1920x1080 382x215mm 17.3-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD0492 1920x1080 344x194mm 15.5-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 1         | 1.06%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch               | 1         | 1.06%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch               | 1         | 1.06%   |
| InnoLux Display LCD Monitor INL0028 1366x768 309x174mm 14.0-inch      | 1         | 1.06%   |
| Hewlett-Packard 27ea HPN3395 1920x1080 527x296mm 23.8-inch            | 1         | 1.06%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 1.06%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.06%   |
| eMachines E19T6W EMA0783 1440x900 410x257mm 19.1-inch                 | 1         | 1.06%   |
| Dell S2330MX DELD049 1920x1080 509x286mm 23.0-inch                    | 1         | 1.06%   |
| Dell P2419HC DELA11C 1920x1080 527x296mm 23.8-inch                    | 1         | 1.06%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 34        | 39.08%  |
| 1366x768 (WXGA)  | 34        | 39.08%  |
| 1280x800 (WXGA)  | 6         | 6.9%    |
| 800x1280         | 3         | 3.45%   |
| 1440x900 (WXGA+) | 3         | 3.45%   |
| 1600x900 (HD+)   | 2         | 2.3%    |
| 3840x2160 (4K)   | 1         | 1.15%   |
| 3200x1800 (QHD+) | 1         | 1.15%   |
| 2560x1600        | 1         | 1.15%   |
| 2560x1080        | 1         | 1.15%   |
| 1360x768         | 1         | 1.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 40        | 43.01%  |
| 17     | 9         | 9.68%   |
| 13     | 9         | 9.68%   |
| 14     | 8         | 8.6%    |
| 24     | 4         | 4.3%    |
| 11     | 4         | 4.3%    |
| 31     | 3         | 3.23%   |
| 21     | 3         | 3.23%   |
| 7      | 3         | 3.23%   |
| 72     | 2         | 2.15%   |
| 12     | 2         | 2.15%   |
| 54     | 1         | 1.08%   |
| 34     | 1         | 1.08%   |
| 27     | 1         | 1.08%   |
| 23     | 1         | 1.08%   |
| 19     | 1         | 1.08%   |
| 18     | 1         | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 52.69%  |
| 201-300     | 12        | 12.9%   |
| 351-400     | 11        | 11.83%  |
| 501-600     | 6         | 6.45%   |
| 401-500     | 5         | 5.38%   |
| 601-700     | 3         | 3.23%   |
| 1-100       | 3         | 3.23%   |
| 1501-2000   | 2         | 2.15%   |
| 701-800     | 1         | 1.08%   |
| 1001-1500   | 1         | 1.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 71        | 83.53%  |
| 16/10 | 10        | 11.76%  |
| 0.67  | 3         | 3.53%   |
| 21/9  | 1         | 1.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 40        | 43.01%  |
| 81-90          | 14        | 15.05%  |
| 121-130        | 8         | 8.6%    |
| 201-250        | 6         | 6.45%   |
| 51-60          | 4         | 4.3%    |
| 351-500        | 4         | 4.3%    |
| More than 1000 | 3         | 3.23%   |
| 71-80          | 3         | 3.23%   |
| 1-40           | 3         | 3.23%   |
| 151-200        | 3         | 3.23%   |
| 61-70          | 2         | 2.15%   |
| 301-350        | 1         | 1.08%   |
| 141-150        | 1         | 1.08%   |
| 131-140        | 1         | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 35        | 37.23%  |
| 121-160       | 32        | 34.04%  |
| 51-100        | 16        | 17.02%  |
| 1-50          | 5         | 5.32%   |
| 161-240       | 5         | 5.32%   |
| More than 240 | 1         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 68        | 78.16%  |
| 2     | 17        | 19.54%  |
| 0     | 2         | 2.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 46        | 33.82%  |
| Intel                    | 42        | 30.88%  |
| Qualcomm Atheros         | 16        | 11.76%  |
| Broadcom                 | 10        | 7.35%   |
| Broadcom Limited         | 4         | 2.94%   |
| Marvell Technology Group | 3         | 2.21%   |
| ASIX Electronics         | 3         | 2.21%   |
| Ralink Technology        | 2         | 1.47%   |
| Nvidia                   | 2         | 1.47%   |
| NetGear                  | 2         | 1.47%   |
| TP-Link                  | 1         | 0.74%   |
| Samsung Electronics      | 1         | 0.74%   |
| Ralink                   | 1         | 0.74%   |
| MediaTek                 | 1         | 0.74%   |
| Dell                     | 1         | 0.74%   |
| Belkin Components        | 1         | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 27        | 17.65%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 4.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 3.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 3.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4         | 2.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 3         | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 1.96%   |
| Intel Wireless 7265                                                    | 3         | 1.96%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 1.96%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 3         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.96%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 1.31%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2         | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 1.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.31%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 1.31%   |
| Intel Wireless 8265 / 8275                                             | 2         | 1.31%   |
| Intel Wireless 8260                                                    | 2         | 1.31%   |
| Intel Wireless 3160                                                    | 2         | 1.31%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.31%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 1.31%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 2         | 1.31%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                          | 2         | 1.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.31%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.31%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                | 2         | 1.31%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 2         | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.31%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.31%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 0.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1         | 0.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.65%   |
| Realtek 802.11n WLAN Adapter                                           | 1         | 0.65%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                 | 1         | 0.65%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter             | 1         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 40.45%  |
| Realtek Semiconductor | 20        | 22.47%  |
| Qualcomm Atheros      | 13        | 14.61%  |
| Broadcom              | 9         | 10.11%  |
| Broadcom Limited      | 3         | 3.37%   |
| Ralink Technology     | 2         | 2.25%   |
| TP-Link               | 1         | 1.12%   |
| Ralink                | 1         | 1.12%   |
| NetGear               | 1         | 1.12%   |
| MediaTek              | 1         | 1.12%   |
| Dell                  | 1         | 1.12%   |
| Belkin Components     | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 7         | 7.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 5         | 5.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 4         | 4.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 3         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 3.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 3         | 3.33%   |
| Intel Wireless 7265                                        | 3         | 3.33%   |
| Intel Wi-Fi 6 AX200                                        | 3         | 3.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]               | 3         | 3.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 2.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 2         | 2.22%   |
| Intel Wireless 8265 / 8275                                 | 2         | 2.22%   |
| Intel Wireless 8260                                        | 2         | 2.22%   |
| Intel Wireless 3160                                        | 2         | 2.22%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 2.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 2         | 2.22%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 2         | 2.22%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 2         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2         | 2.22%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 2         | 2.22%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 2         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 2         | 2.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 1.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 1.11%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 1.11%   |
| Realtek 802.11n WLAN Adapter                               | 1         | 1.11%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1         | 1.11%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1         | 1.11%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]      | 1         | 1.11%   |
| MediaTek WiFi                                              | 1         | 1.11%   |
| Intel Wireless 7260                                        | 1         | 1.11%   |
| Intel Wireless 3165                                        | 1         | 1.11%   |
| Intel WiFi Link 5100                                       | 1         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 1.11%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 53.97%  |
| Intel                    | 11        | 17.46%  |
| Qualcomm Atheros         | 4         | 6.35%   |
| Marvell Technology Group | 3         | 4.76%   |
| Broadcom                 | 3         | 4.76%   |
| ASIX Electronics         | 3         | 4.76%   |
| Nvidia                   | 2         | 3.17%   |
| Samsung Electronics      | 1         | 1.59%   |
| NetGear                  | 1         | 1.59%   |
| Broadcom Limited         | 1         | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 27        | 42.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 9.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 4.76%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 4.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 3.17%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 3.17%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 3.17%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 3.17%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 1.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.59%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.59%   |
| NetGear LB1120-100NAS                                                          | 1         | 1.59%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.59%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.59%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.59%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 1.59%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.59%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 1.59%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 1.59%   |
| ASIX AX88772B                                                                  | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 56.55%  |
| Ethernet | 63        | 43.45%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 78.41%  |
| Ethernet | 19        | 21.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 55        | 66.27%  |
| 1     | 25        | 30.12%  |
| 0     | 2         | 2.41%   |
| 3     | 1         | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 61        | 70.11%  |
| Yes  | 26        | 29.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 42.42%  |
| Realtek Semiconductor           | 11        | 16.67%  |
| Qualcomm Atheros Communications | 5         | 7.58%   |
| IMC Networks                    | 5         | 7.58%   |
| Apple                           | 5         | 7.58%   |
| Foxconn / Hon Hai               | 4         | 6.06%   |
| Lite-On Technology              | 2         | 3.03%   |
| Dell                            | 2         | 3.03%   |
| Toshiba                         | 1         | 1.52%   |
| Hewlett-Packard                 | 1         | 1.52%   |
| Broadcom                        | 1         | 1.52%   |
| Alps Electric                   | 1         | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 11        | 16.67%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 12.12%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 12.12%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 6.06%   |
| Intel Bluetooth Device                                                              | 4         | 6.06%   |
| Realtek Bluetooth Radio                                                             | 3         | 4.55%   |
| Intel AX200 Bluetooth                                                               | 3         | 4.55%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 4.55%   |
| Apple Bluetooth Host Controller                                                     | 3         | 4.55%   |
| Intel AX201 Bluetooth                                                               | 2         | 3.03%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 3.03%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.52%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.52%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 1.52%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.52%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.52%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.52%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.52%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.52%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.52%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.52%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.52%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 77.53%  |
| AMD    | 12        | 13.48%  |
| Nvidia | 7         | 7.87%   |
| Apple  | 1         | 1.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 13.33%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 9.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 5.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 4.76%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 4.76%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 2.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.86%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 2.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.9%    |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.9%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.9%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.9%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.95%   |
| Apple Audio Device                                                                                | 1         | 0.95%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.95%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.95%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.95%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.95%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 11        | 36.67%  |
| Samsung Electronics | 6         | 20%     |
| Micron Technology   | 4         | 13.33%  |
| Kingston            | 4         | 13.33%  |
| Silicon Power       | 1         | 3.33%   |
| Ramaxel Technology  | 1         | 3.33%   |
| Qumo                | 1         | 3.33%   |
| PNY                 | 1         | 3.33%   |
| A-DATA Technology   | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 6.06%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 2         | 6.06%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 3.03%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 1         | 3.03%   |
| SK hynix RAM Module 4GB SODIMM LPDDR3 2133MT/s            | 1         | 3.03%   |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s             | 1         | 3.03%   |
| SK hynix RAM HMT451S6MFR8C-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 3.03%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 1         | 3.03%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 1         | 3.03%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 3.03%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 3.03%   |
| Silicon Power RAM Module 8GB SODIMM DDR3 1600MT/s         | 1         | 3.03%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s  | 1         | 3.03%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 3.03%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s  | 1         | 3.03%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 3.03%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 1         | 3.03%   |
| Qumo RAM Module 4GB SODIMM DDR3 1334MT/s                  | 1         | 3.03%   |
| PNY RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 3.03%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s  | 1         | 3.03%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s      | 1         | 3.03%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s          | 1         | 3.03%   |
| Kingston RAM KHX1600C9S3K2/8GX 4GB SODIMM DDR3 1334MT/s   | 1         | 3.03%   |
| Kingston RAM HP691160-H66-MCN 8GB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s    | 1         | 3.03%   |
| A-DATA RAM AM1L16BC4R1-B1YS 4GB SODIMM DDR3 800MT/s       | 1         | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 12        | 42.86%  |
| DDR3   | 11        | 39.29%  |
| LPDDR4 | 2         | 7.14%   |
| LPDDR3 | 2         | 7.14%   |
| DDR    | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 26        | 96.3%   |
| Row Of Chips | 1         | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 13        | 46.43%  |
| 4096  | 11        | 39.29%  |
| 16384 | 3         | 10.71%  |
| 2048  | 1         | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 10        | 34.48%  |
| 2667  | 7         | 24.14%  |
| 3200  | 4         | 13.79%  |
| 2133  | 2         | 6.9%    |
| 3266  | 1         | 3.45%   |
| 2400  | 1         | 3.45%   |
| 1334  | 1         | 3.45%   |
| 1067  | 1         | 3.45%   |
| 800   | 1         | 3.45%   |
| 667   | 1         | 3.45%   |

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
| Chicony Electronics                    | 11        | 15.71%  |
| Realtek Semiconductor                  | 8         | 11.43%  |
| Bison Electronics                      | 6         | 8.57%   |
| Ricoh                                  | 5         | 7.14%   |
| IMC Networks                           | 5         | 7.14%   |
| Apple                                  | 5         | 7.14%   |
| Quanta                                 | 4         | 5.71%   |
| Lite-On Technology                     | 4         | 5.71%   |
| Sunplus Innovation Technology          | 3         | 4.29%   |
| Microdia                               | 3         | 4.29%   |
| Luxvisions Innotech Limited            | 3         | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.29%   |
| Syntek                                 | 2         | 2.86%   |
| Suyin                                  | 2         | 2.86%   |
| Lenovo                                 | 2         | 2.86%   |
| MacroSilicon                           | 1         | 1.43%   |
| Goertek Electronics                    | 1         | 1.43%   |
| Alpha Imaging Technology               | 1         | 1.43%   |
| Acer                                   | 1         | 1.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Ricoh Integrated Webcam                                        | 3         | 4.29%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 4.29%   |
| Lite-On HP Wide Vision HD Camera                               | 3         | 4.29%   |
| Realtek USB Camera                                             | 2         | 2.86%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 2.86%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 2.86%   |
| Lenovo Integrated Webcam [R5U877]                              | 2         | 2.86%   |
| IMC Networks UVC VGA Webcam                                    | 2         | 2.86%   |
| Chicony HP Truevision HD                                       | 2         | 2.86%   |
| Chicony HD WebCam                                              | 2         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 2.86%   |
| Bison Lenovo EasyCamera                                        | 2         | 2.86%   |
| Apple FaceTime HD Camera                                       | 2         | 2.86%   |
| Apple Built-in iSight                                          | 2         | 2.86%   |
| Syntek Lenovo EasyCamera                                       | 1         | 1.43%   |
| Syntek Integrated Camera                                       | 1         | 1.43%   |
| Suyin USB 2.0 Camera                                           | 1         | 1.43%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.43%   |
| Sunplus MTD Camera                                             | 1         | 1.43%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.43%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 1.43%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam       | 1         | 1.43%   |
| Ricoh HD Webcam                                                | 1         | 1.43%   |
| Realtek Integrated Webcam HD                                   | 1         | 1.43%   |
| Realtek Integrated Webcam                                      | 1         | 1.43%   |
| Realtek Integrated Camera                                      | 1         | 1.43%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 1.43%   |
| Quanta HD WebCam                                               | 1         | 1.43%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 1.43%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.43%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.43%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]                  | 1         | 1.43%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.43%   |
| Lite-On HP HD Webcam                                           | 1         | 1.43%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.43%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 1.43%   |
| IMC Networks Integrated Camera                                 | 1         | 1.43%   |
| Goertek USB2.0 VGA UVC WebCam                                  | 1         | 1.43%   |
| Chicony TOSHIBA Web Camera - HD                                | 1         | 1.43%   |
| Chicony Toshiba Integrated Webcam                              | 1         | 1.43%   |

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
| 0     | 54        | 64.29%  |
| 1     | 26        | 30.95%  |
| 2     | 4         | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 41.18%  |
| Graphics card            | 8         | 23.53%  |
| Net/wireless             | 4         | 11.76%  |
| Chipcard                 | 4         | 11.76%  |
| Communication controller | 2         | 5.88%   |
| Storage                  | 1         | 2.94%   |
| Multimedia controller    | 1         | 2.94%   |

