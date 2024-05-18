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

Total: 186

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Laptop 15-eh1xx... | [c94fe08160](https://linux-hardware.org/?probe=c94fe08160) | May 02, 2024 |
| HP            | Laptop 15-bs0xx             | [92878d7fb2](https://linux-hardware.org/?probe=92878d7fb2) | Apr 28, 2024 |
| Dell          | Latitude 3150               | [2591de095d](https://linux-hardware.org/?probe=2591de095d) | Apr 22, 2024 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [07ab4bf081](https://linux-hardware.org/?probe=07ab4bf081) | Apr 20, 2024 |
| Dell          | XPS 13 9380                 | [56a4aeab46](https://linux-hardware.org/?probe=56a4aeab46) | Apr 17, 2024 |
| HP            | EliteBook 8560p             | [e9b9656231](https://linux-hardware.org/?probe=e9b9656231) | Apr 09, 2024 |
| Alienware     | m18 R1 AMD                  | [8031bfa7f7](https://linux-hardware.org/?probe=8031bfa7f7) | Apr 08, 2024 |
| Lenovo        | ThinkPad T460s 20F9003GU... | [497b326dc9](https://linux-hardware.org/?probe=497b326dc9) | Apr 04, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [6ea19c4f02](https://linux-hardware.org/?probe=6ea19c4f02) | Apr 04, 2024 |
| HP            | Laptop 15-bs0xx             | [922723cbd4](https://linux-hardware.org/?probe=922723cbd4) | Mar 30, 2024 |
| HP            | Laptop 15-bs0xx             | [3932e020fb](https://linux-hardware.org/?probe=3932e020fb) | Mar 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2bdaf911fd](https://linux-hardware.org/?probe=2bdaf911fd) | Mar 20, 2024 |
| HP            | Laptop 14-dq0xxx            | [cfcb468980](https://linux-hardware.org/?probe=cfcb468980) | Mar 05, 2024 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [fc18695b87](https://linux-hardware.org/?probe=fc18695b87) | Mar 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5a9461ea0f](https://linux-hardware.org/?probe=5a9461ea0f) | Feb 21, 2024 |
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
| Ubuntu 20.04                 | 16        | 15.24%  |
| Ubuntu 22.04                 | 13        | 12.38%  |
| Ubuntu 18.04                 | 5         | 4.76%   |
| Fedora 39                    | 4         | 3.81%   |
| Arch Rolling                 | 4         | 3.81%   |
| Pop!_OS 22.04                | 3         | 2.86%   |
| Ubuntu 22.10                 | 2         | 1.9%    |
| Ubuntu 21.10                 | 2         | 1.9%    |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.9%    |
| OpenMandriva 4.3             | 2         | 1.9%    |
| OpenMandriva 4.2             | 2         | 1.9%    |
| Linux Mint 21                | 2         | 1.9%    |
| Linux Mint 19.3              | 2         | 1.9%    |
| Fedora 38                    | 2         | 1.9%    |
| Fedora 37                    | 2         | 1.9%    |
| Elementary 7                 | 2         | 1.9%    |
| Debian 11                    | 2         | 1.9%    |
| BlackPanther 18.1            | 2         | 1.9%    |
| Zorin 17                     | 1         | 0.95%   |
| Zorin 16                     | 1         | 0.95%   |
| Xubuntu 20.04                | 1         | 0.95%   |
| Ubuntu Unity 20.04           | 1         | 0.95%   |
| Ubuntu MATE 20.04            | 1         | 0.95%   |
| Ubuntu 23.10                 | 1         | 0.95%   |
| Ubuntu 23.04                 | 1         | 0.95%   |
| Ubuntu 19.10                 | 1         | 0.95%   |
| SteamOS 3.5.7                | 1         | 0.95%   |
| SteamOS 3.4.4                | 1         | 0.95%   |
| SteamOS 3.4.10               | 1         | 0.95%   |
| ROSA R10                     | 1         | 0.95%   |
| Peppermint 9                 | 1         | 0.95%   |
| Parrot 5.0                   | 1         | 0.95%   |
| Parrot 4.11                  | 1         | 0.95%   |
| openSUSE Leap-15.2           | 1         | 0.95%   |
| OpenMandriva 4.90            | 1         | 0.95%   |
| OpenMandriva 4.50            | 1         | 0.95%   |
| OpenMandriva 23.01           | 1         | 0.95%   |
| LMDE 6                       | 1         | 0.95%   |
| Linux Mint 21.3              | 1         | 0.95%   |
| Linux Mint 21.2              | 1         | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 36        | 37.11%  |
| Fedora       | 10        | 10.31%  |
| OpenMandriva | 7         | 7.22%   |
| Linux Mint   | 7         | 7.22%   |
| Arch         | 4         | 4.12%   |
| SteamOS      | 3         | 3.09%   |
| Pop!_OS      | 3         | 3.09%   |
| openSUSE     | 3         | 3.09%   |
| Debian       | 3         | 3.09%   |
| Zorin        | 2         | 2.06%   |
| Parrot       | 2         | 2.06%   |
| KDE neon     | 2         | 2.06%   |
| Elementary   | 2         | 2.06%   |
| BlackPanther | 2         | 2.06%   |
| Xubuntu      | 1         | 1.03%   |
| Ubuntu Unity | 1         | 1.03%   |
| Ubuntu MATE  | 1         | 1.03%   |
| ROSA         | 1         | 1.03%   |
| Peppermint   | 1         | 1.03%   |
| LMDE         | 1         | 1.03%   |
| Endless      | 1         | 1.03%   |
| EndeavourOS  | 1         | 1.03%   |
| ArcoLinux    | 1         | 1.03%   |
| Alpine       | 1         | 1.03%   |
| AlmaLinux    | 1         | 1.03%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 6.2.0-34-generic                    | 3         | 2.17%   |
| 5.8.0-59-generic                    | 3         | 2.17%   |
| 6.5.0-28-generic                    | 2         | 1.45%   |
| 6.5.0-18-generic                    | 2         | 1.45%   |
| 6.5.0-14-generic                    | 2         | 1.45%   |
| 6.3.6-200.fc38.x86_64               | 2         | 1.45%   |
| 6.2.0-32-generic                    | 2         | 1.45%   |
| 6.2.0-31-generic                    | 2         | 1.45%   |
| 5.8.0-55-generic                    | 2         | 1.45%   |
| 5.4.0-58-generic                    | 2         | 1.45%   |
| 5.19.0-42-generic                   | 2         | 1.45%   |
| 5.19.0-38-generic                   | 2         | 1.45%   |
| 5.16.7-desktop-1omv4003             | 2         | 1.45%   |
| 5.15.0-58-generic                   | 2         | 1.45%   |
| 5.15.0-46-generic                   | 2         | 1.45%   |
| 5.15.0-25-generic                   | 2         | 1.45%   |
| 5.13.0-35-generic                   | 2         | 1.45%   |
| 5.11.0-38-generic                   | 2         | 1.45%   |
| 5.11.0-27-generic                   | 2         | 1.45%   |
| 5.10.14-desktop-1omv4002            | 2         | 1.45%   |
| 5.10.0-19-amd64                     | 2         | 1.45%   |
| 6.8.7-300.fc40.x86_64               | 1         | 0.72%   |
| 6.8.6-arch1-1                       | 1         | 0.72%   |
| 6.8.4-200.fc39.x86_64               | 1         | 0.72%   |
| 6.8.0-76060800daily20240311-generic | 1         | 0.72%   |
| 6.7.9-200.fc39.x86_64               | 1         | 0.72%   |
| 6.7.11-200.fc39.x86_64              | 1         | 0.72%   |
| 6.7.0-060700rc4-generic             | 1         | 0.72%   |
| 6.6.8-200.t2.fc39.x86_64            | 1         | 0.72%   |
| 6.6.2-x64v4-xanmod1                 | 1         | 0.72%   |
| 6.6.1-arch1-1                       | 1         | 0.72%   |
| 6.5.9-arch2-1                       | 1         | 0.72%   |
| 6.5.9-1-default                     | 1         | 0.72%   |
| 6.5.0-26-generic                    | 1         | 0.72%   |
| 6.5.0-25-generic                    | 1         | 0.72%   |
| 6.5.0-21-generic                    | 1         | 0.72%   |
| 6.5.0-15-generic                    | 1         | 0.72%   |
| 6.4.6-76060406-generic              | 1         | 0.72%   |
| 6.4.15-200.fc38.x86_64              | 1         | 0.72%   |
| 6.4.11-060411-generic               | 1         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 13        | 11.5%   |
| 5.15.0  | 8         | 7.08%   |
| 5.13.0  | 8         | 7.08%   |
| 6.5.0   | 7         | 6.19%   |
| 6.2.0   | 7         | 6.19%   |
| 5.19.0  | 7         | 6.19%   |
| 5.11.0  | 5         | 4.42%   |
| 5.8.0   | 4         | 3.54%   |
| 5.3.0   | 3         | 2.65%   |
| 5.10.0  | 3         | 2.65%   |
| 4.15.0  | 3         | 2.65%   |
| 6.5.9   | 2         | 1.77%   |
| 6.3.6   | 2         | 1.77%   |
| 5.16.7  | 2         | 1.77%   |
| 5.10.14 | 2         | 1.77%   |
| 6.8.7   | 1         | 0.88%   |
| 6.8.6   | 1         | 0.88%   |
| 6.8.4   | 1         | 0.88%   |
| 6.8.0   | 1         | 0.88%   |
| 6.7.9   | 1         | 0.88%   |
| 6.7.11  | 1         | 0.88%   |
| 6.7.0   | 1         | 0.88%   |
| 6.6.8   | 1         | 0.88%   |
| 6.6.2   | 1         | 0.88%   |
| 6.6.1   | 1         | 0.88%   |
| 6.4.6   | 1         | 0.88%   |
| 6.4.15  | 1         | 0.88%   |
| 6.4.11  | 1         | 0.88%   |
| 6.2.9   | 1         | 0.88%   |
| 6.2.8   | 1         | 0.88%   |
| 6.2.6   | 1         | 0.88%   |
| 6.2.12  | 1         | 0.88%   |
| 6.1.71  | 1         | 0.88%   |
| 6.1.52  | 1         | 0.88%   |
| 6.1.1   | 1         | 0.88%   |
| 6.1.0   | 1         | 0.88%   |
| 5.9.16  | 1         | 0.88%   |
| 5.6.14  | 1         | 0.88%   |
| 5.3.6   | 1         | 0.88%   |
| 5.3.18  | 1         | 0.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 13        | 11.61%  |
| 6.2     | 11        | 9.82%   |
| 6.5     | 9         | 8.04%   |
| 5.15    | 9         | 8.04%   |
| 5.19    | 8         | 7.14%   |
| 5.13    | 8         | 7.14%   |
| 5.11    | 6         | 5.36%   |
| 5.3     | 5         | 4.46%   |
| 5.10    | 5         | 4.46%   |
| 6.8     | 4         | 3.57%   |
| 6.1     | 4         | 3.57%   |
| 5.8     | 4         | 3.57%   |
| 6.7     | 3         | 2.68%   |
| 6.6     | 3         | 2.68%   |
| 6.4     | 3         | 2.68%   |
| 5.18    | 3         | 2.68%   |
| 4.15    | 3         | 2.68%   |
| 6.3     | 2         | 1.79%   |
| 5.16    | 2         | 1.79%   |
| 5.9     | 1         | 0.89%   |
| 5.6     | 1         | 0.89%   |
| 5.14    | 1         | 0.89%   |
| 5.12    | 1         | 0.89%   |
| 4.9     | 1         | 0.89%   |
| 4.19    | 1         | 0.89%   |
| 4.18    | 1         | 0.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 89        | 97.8%   |
| i686   | 2         | 2.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 51        | 54.26%  |
| KDE5       | 18        | 19.15%  |
| X-Cinnamon | 7         | 7.45%   |
| MATE       | 4         | 4.26%   |
| XFCE       | 3         | 3.19%   |
| Unknown    | 3         | 3.19%   |
| Pantheon   | 2         | 2.13%   |
| i3         | 2         | 2.13%   |
| Unity      | 1         | 1.06%   |
| LXDE       | 1         | 1.06%   |
| KDE4       | 1         | 1.06%   |
| awesome    | 1         | 1.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 68        | 71.58%  |
| Wayland | 26        | 27.37%  |
| Unknown | 1         | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 52.58%  |
| GDM3    | 22        | 22.68%  |
| SDDM    | 10        | 10.31%  |
| GDM     | 7         | 7.22%   |
| LightDM | 4         | 4.12%   |
| TDM     | 2         | 2.06%   |
| KDM     | 1         | 1.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 80        | 86.96%  |
| es_PR   | 5         | 5.43%   |
| Unknown | 5         | 5.43%   |
| C       | 2         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 54        | 58.06%  |
| EFI  | 39        | 41.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 61        | 62.24%  |
| Btrfs   | 15        | 15.31%  |
| Tmpfs   | 9         | 9.18%   |
| Overlay | 9         | 9.18%   |
| Unknown | 2         | 2.04%   |
| Zfs     | 1         | 1.02%   |
| Xfs     | 1         | 1.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 58        | 59.79%  |
| GPT     | 33        | 34.02%  |
| MBR     | 6         | 6.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 84.21%  |
| Yes       | 15        | 15.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 75.79%  |
| Yes       | 23        | 24.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 25        | 27.47%  |
| Dell             | 19        | 20.88%  |
| Lenovo           | 13        | 14.29%  |
| ASUSTek Computer | 7         | 7.69%   |
| Apple            | 6         | 6.59%   |
| Acer             | 4         | 4.4%    |
| Valve            | 3         | 3.3%    |
| Toshiba          | 3         | 3.3%    |
| Sony             | 3         | 3.3%    |
| GPU Company      | 2         | 2.2%    |
| TUXEDO           | 1         | 1.1%    |
| MSI              | 1         | 1.1%    |
| Framework        | 1         | 1.1%    |
| AZW              | 1         | 1.1%    |
| AMI              | 1         | 1.1%    |
| Alienware        | 1         | 1.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Valve Jupiter                            | 3         | 3.3%    |
| Dell Vostro 3550                         | 3         | 3.3%    |
| Dell Inspiron 11-3168                    | 2         | 2.2%    |
| ASUS K53E                                | 2         | 2.2%    |
| TUXEDO Aura 15 Gen1                      | 1         | 1.1%    |
| Toshiba Satellite P755                   | 1         | 1.1%    |
| Toshiba Satellite L655                   | 1         | 1.1%    |
| Toshiba Satellite C55-C                  | 1         | 1.1%    |
| Sony VPCEA36FX                           | 1         | 1.1%    |
| Sony VGN-CS320J                          | 1         | 1.1%    |
| Sony SVE11113FXW                         | 1         | 1.1%    |
| MSI GF65 Thin 10SDR                      | 1         | 1.1%    |
| Lenovo Yoga 900-13ISK 80MK               | 1         | 1.1%    |
| Lenovo Y70-70 Touch 80DU                 | 1         | 1.1%    |
| Lenovo Y50-70 Touch 20349                | 1         | 1.1%    |
| Lenovo V14-ARE 82DQ                      | 1         | 1.1%    |
| Lenovo ThinkPad X1 Carbon 7th 20QD0000US | 1         | 1.1%    |
| Lenovo ThinkPad T510 4314RBS             | 1         | 1.1%    |
| Lenovo ThinkPad T460s 20F9003GUS         | 1         | 1.1%    |
| Lenovo ThinkPad T410 2516ADU             | 1         | 1.1%    |
| Lenovo ThinkPad E570 20H50048US          | 1         | 1.1%    |
| Lenovo ThinkPad E560 20EV002JUS          | 1         | 1.1%    |
| Lenovo ThinkPad E14 20RA004WUS           | 1         | 1.1%    |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 1.1%    |
| Lenovo G50-45 80E3                       | 1         | 1.1%    |
| HP Stream Laptop 14-CB1xxx               | 1         | 1.1%    |
| HP ProBook 6560b                         | 1         | 1.1%    |
| HP ProBook 6450b                         | 1         | 1.1%    |
| HP ProBook 450 G5                        | 1         | 1.1%    |
| HP Pavilion Laptop 15-eh1xxx             | 1         | 1.1%    |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 1.1%    |
| HP Pavilion Laptop 15-cs2xxx             | 1         | 1.1%    |
| HP Pavilion Laptop 15-cs0xxx             | 1         | 1.1%    |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 1         | 1.1%    |
| HP Notebook                              | 1         | 1.1%    |
| HP Laptop 17-by3xxx                      | 1         | 1.1%    |
| HP Laptop 15-dy2xxx                      | 1         | 1.1%    |
| HP Laptop 15-dy1xxx                      | 1         | 1.1%    |
| HP Laptop 15-dw0xxx                      | 1         | 1.1%    |
| HP Laptop 15-bs0xx                       | 1         | 1.1%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 7         | 7.69%   |
| HP Laptop              | 7         | 7.69%   |
| Dell Inspiron          | 6         | 6.59%   |
| HP Pavilion            | 5         | 5.49%   |
| Dell Latitude          | 5         | 5.49%   |
| Valve Jupiter          | 3         | 3.3%    |
| Toshiba Satellite      | 3         | 3.3%    |
| HP ProBook             | 3         | 3.3%    |
| HP ENVY                | 3         | 3.3%    |
| Dell Vostro            | 3         | 3.3%    |
| HP EliteBook           | 2         | 2.2%    |
| Dell XPS               | 2         | 2.2%    |
| ASUS ROG               | 2         | 2.2%    |
| ASUS K53E              | 2         | 2.2%    |
| Acer Swift             | 2         | 2.2%    |
| Acer Aspire            | 2         | 2.2%    |
| TUXEDO Aura            | 1         | 1.1%    |
| Sony VPCEA36FX         | 1         | 1.1%    |
| Sony VGN-CS320J        | 1         | 1.1%    |
| Sony SVE11113FXW       | 1         | 1.1%    |
| MSI GF65               | 1         | 1.1%    |
| Lenovo Yoga            | 1         | 1.1%    |
| Lenovo Y70-70          | 1         | 1.1%    |
| Lenovo Y50-70          | 1         | 1.1%    |
| Lenovo V14-ARE         | 1         | 1.1%    |
| Lenovo IdeaPad         | 1         | 1.1%    |
| Lenovo G50-45          | 1         | 1.1%    |
| HP Stream              | 1         | 1.1%    |
| HP Notebook            | 1         | 1.1%    |
| HP Compaq              | 1         | 1.1%    |
| HP 250                 | 1         | 1.1%    |
| HP 2000                | 1         | 1.1%    |
| GPU Company GWTN156-9  | 1         | 1.1%    |
| GPU Company GWTN156-11 | 1         | 1.1%    |
| Framework Laptop       | 1         | 1.1%    |
| Dell Venue             | 1         | 1.1%    |
| Dell Precision         | 1         | 1.1%    |
| Dell G5                | 1         | 1.1%    |
| AZW GT-R               | 1         | 1.1%    |
| ASUS X540SAA           | 1         | 1.1%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 12        | 13.19%  |
| 2011 | 12        | 13.19%  |
| 2020 | 10        | 10.99%  |
| 2015 | 9         | 9.89%   |
| 2018 | 7         | 7.69%   |
| 2012 | 7         | 7.69%   |
| 2016 | 6         | 6.59%   |
| 2021 | 4         | 4.4%    |
| 2014 | 4         | 4.4%    |
| 2010 | 4         | 4.4%    |
| 2009 | 4         | 4.4%    |
| 2023 | 3         | 3.3%    |
| 2022 | 3         | 3.3%    |
| 2017 | 3         | 3.3%    |
| 2008 | 1         | 1.1%    |
| 2006 | 1         | 1.1%    |
| 2005 | 1         | 1.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 91        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 84        | 92.31%  |
| Enabled  | 7         | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 91        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 36        | 37.5%   |
| 8.01-16.0  | 21        | 21.88%  |
| 3.01-4.0   | 19        | 19.79%  |
| 16.01-24.0 | 15        | 15.63%  |
| 1.01-2.0   | 3         | 3.13%   |
| 32.01-64.0 | 1         | 1.04%   |
| 24.01-32.0 | 1         | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 47        | 42.73%  |
| 2.01-3.0  | 23        | 20.91%  |
| 3.01-4.0  | 20        | 18.18%  |
| 4.01-8.0  | 14        | 12.73%  |
| 0.51-1.0  | 5         | 4.55%   |
| 8.01-16.0 | 1         | 0.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 66        | 68.75%  |
| 2      | 23        | 23.96%  |
| 3      | 5         | 5.21%   |
| 4      | 1         | 1.04%   |
| 0      | 1         | 1.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 65.22%  |
| Yes       | 32        | 34.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 75.82%  |
| No        | 22        | 24.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 98.9%   |
| No        | 1         | 1.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 78.26%  |
| No        | 20        | 21.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Puerto Rico | 91        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San Juan      | 47        | 47.96%  |
| Bayamón      | 14        | 14.29%  |
| Ponce         | 6         | 6.12%   |
| Carolina      | 5         | 5.1%    |
| Toa Baja      | 3         | 3.06%   |
| Rio Grande    | 3         | 3.06%   |
| Lares         | 3         | 3.06%   |
| Caguas        | 3         | 3.06%   |
| Cayey         | 2         | 2.04%   |
| Cabo Rojo     | 2         | 2.04%   |
| Vega Baja     | 1         | 1.02%   |
| Santa Isabel  | 1         | 1.02%   |
| San Sebastian | 1         | 1.02%   |
| Sabana Grande | 1         | 1.02%   |
| Manati        | 1         | 1.02%   |
| Guaynabo      | 1         | 1.02%   |
| Guayama       | 1         | 1.02%   |
| Cataño       | 1         | 1.02%   |
| Canovanas     | 1         | 1.02%   |
| Arecibo       | 1         | 1.02%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 18        | 22     | 14.75%  |
| Toshiba                     | 12        | 13     | 9.84%   |
| Unknown                     | 11        | 15     | 9.02%   |
| Hitachi                     | 11        | 30     | 9.02%   |
| SanDisk                     | 9         | 13     | 7.38%   |
| Crucial                     | 9         | 23     | 7.38%   |
| Samsung Electronics         | 7         | 9      | 5.74%   |
| SK hynix                    | 6         | 8      | 4.92%   |
| Seagate                     | 6         | 10     | 4.92%   |
| Micron Technology           | 4         | 12     | 3.28%   |
| Kingston                    | 4         | 6      | 3.28%   |
| Intel                       | 3         | 4      | 2.46%   |
| External                    | 3         | 12     | 2.46%   |
| Silicon Motion              | 2         | 2      | 1.64%   |
| A-DATA Technology           | 2         | 2      | 1.64%   |
| W800SH                      | 1         | 1      | 0.82%   |
| SPCC                        | 1         | 3      | 0.82%   |
| PNY                         | 1         | 1      | 0.82%   |
| Phison Electronics          | 1         | 1      | 0.82%   |
| Patriot                     | 1         | 4      | 0.82%   |
| Micron/Crucial Technology   | 1         | 3      | 0.82%   |
| Lexar                       | 1         | 1      | 0.82%   |
| Kingston Technology Company | 1         | 1      | 0.82%   |
| KingSpec                    | 1         | 1      | 0.82%   |
| HGST                        | 1         | 1      | 0.82%   |
| China                       | 1         | 2      | 0.82%   |
| Axiom                       | 1         | 7      | 0.82%   |
| Apple                       | 1         | 1      | 0.82%   |
| ADATA Technology            | 1         | 1      | 0.82%   |
| Unknown                     | 1         | 1      | 0.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Crucial CT240M500SSD1 240GB          | 4         | 3.15%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 3.15%   |
| WDC WD5000LPVT-22G33T0 500GB         | 3         | 2.36%   |
| Unknown MMC Card  128GB              | 3         | 2.36%   |
| Toshiba MQ04ABF100 1TB               | 3         | 2.36%   |
| Hitachi HTS547550A9E384 500GB        | 3         | 2.36%   |
| External USB3.0 500GB                | 3         | 2.36%   |
| WDC WD2500BEVS-60UST0 250GB          | 2         | 1.57%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 1.57%   |
| Unknown MMC Card  2GB                | 2         | 1.57%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.57%   |
| Toshiba MK3261GSYN 320GB             | 2         | 1.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 1.57%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD | 2         | 1.57%   |
| Micron 2200V_MTFDHBA512TCK 512GB     | 2         | 1.57%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 1.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.79%   |
| WDC WDBNCE0010PNC 1TB SSD            | 1         | 0.79%   |
| WDC WD5000LPCX-75VHAT0 500GB         | 1         | 0.79%   |
| WDC WD5000BPVT-75HXZT1 500GB         | 1         | 0.79%   |
| WDC WD32 00BEVT-00A23T0 320GB        | 1         | 0.79%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.79%   |
| WDC WD10SPCX-75KHST0 1TB             | 1         | 0.79%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.79%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.79%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB | 1         | 0.79%   |
| W800SH 512GB SSD                     | 1         | 0.79%   |
| Unknown USB DISK 3.2 1TB             | 1         | 0.79%   |
| Unknown MMC Card  64GB               | 1         | 0.79%   |
| Unknown MMC Card  512GB              | 1         | 0.79%   |
| Unknown MMC Card  2TB                | 1         | 0.79%   |
| Unknown MMC Card  10GB               | 1         | 0.79%   |
| Unknown HBG4a2  32GB                 | 1         | 0.79%   |
| Unknown DA4064  64GB                 | 1         | 0.79%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.79%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.79%   |
| Toshiba MK6476GSX 640GB              | 1         | 0.79%   |
| Toshiba MK3276GSX 320GB              | 1         | 0.79%   |
| Toshiba MK3254GSY 320GB              | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 14        | 16     | 31.82%  |
| Toshiba | 12        | 13     | 27.27%  |
| Hitachi | 11        | 30     | 25%     |
| Seagate | 6         | 10     | 13.64%  |
| HGST    | 1         | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 23     | 24.32%  |
| Samsung Electronics | 6         | 8      | 16.22%  |
| SanDisk             | 4         | 4      | 10.81%  |
| Kingston            | 3         | 5      | 8.11%   |
| External            | 3         | 12     | 8.11%   |
| WDC                 | 2         | 3      | 5.41%   |
| A-DATA Technology   | 2         | 2      | 5.41%   |
| W800SH              | 1         | 1      | 2.7%    |
| SPCC                | 1         | 3      | 2.7%    |
| PNY                 | 1         | 1      | 2.7%    |
| Patriot             | 1         | 4      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| Lexar               | 1         | 1      | 2.7%    |
| KingSpec            | 1         | 1      | 2.7%    |
| China               | 1         | 2      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 41        | 70     | 35.65%  |
| SSD     | 35        | 71     | 30.43%  |
| NVMe    | 26        | 46     | 22.61%  |
| MMC     | 11        | 15     | 9.57%   |
| Unknown | 2         | 8      | 1.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 68        | 134    | 61.26%  |
| NVMe | 26        | 46     | 23.42%  |
| MMC  | 11        | 15     | 9.91%   |
| SAS  | 6         | 15     | 5.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 105    | 65.75%  |
| 0.51-1.0   | 24        | 35     | 32.88%  |
| 1.01-2.0   | 1         | 1      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 28.44%  |
| 251-500        | 28        | 25.69%  |
| 501-1000       | 21        | 19.27%  |
| 1-20           | 12        | 11.01%  |
| 1001-2000      | 8         | 7.34%   |
| 21-50          | 3         | 2.75%   |
| More than 3000 | 2         | 1.83%   |
| Unknown        | 2         | 1.83%   |
| 2001-3000      | 1         | 0.92%   |
| 51-100         | 1         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 36        | 31.03%  |
| 21-50     | 25        | 21.55%  |
| 101-250   | 19        | 16.38%  |
| 51-100    | 15        | 12.93%  |
| 251-500   | 9         | 7.76%   |
| 501-1000  | 7         | 6.03%   |
| 1001-2000 | 2         | 1.72%   |
| Unknown   | 2         | 1.72%   |
| 2001-3000 | 1         | 0.86%   |

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
| Detected | 69        | 179    | 72.63%  |
| Works    | 17        | 22     | 17.89%  |
| Malfunc  | 9         | 9      | 9.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 68        | 66.02%  |
| AMD                         | 8         | 7.77%   |
| SK hynix                    | 6         | 5.83%   |
| SanDisk                     | 6         | 5.83%   |
| Micron Technology           | 3         | 2.91%   |
| Silicon Motion              | 2         | 1.94%   |
| Nvidia                      | 2         | 1.94%   |
| Kingston Technology Company | 2         | 1.94%   |
| Samsung Electronics         | 1         | 0.97%   |
| Phison Electronics          | 1         | 0.97%   |
| Micron/Crucial Technology   | 1         | 0.97%   |
| ASMedia Technology          | 1         | 0.97%   |
| Apple                       | 1         | 0.97%   |
| ADATA Technology            | 1         | 0.97%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 10.28%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 9.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 9.35%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 7.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 4.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 3.74%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 2.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 2.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.8%    |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.87%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 1.87%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 1.87%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 1.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.87%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.87%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.87%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.93%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.93%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 0.93%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 1         | 0.93%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 0.93%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                            | 1         | 0.93%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 0.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 0.93%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 1         | 0.93%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 0.93%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 1         | 0.93%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.93%   |
| Kingston Company KC2000/KC2500 NVMe SSD SM2262EN                                 | 1         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.93%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 1         | 0.93%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]               | 1         | 0.93%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 0.93%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 63        | 60%     |
| NVMe | 26        | 24.76%  |
| RAID | 12        | 11.43%  |
| IDE  | 4         | 3.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 77        | 84.62%  |
| AMD    | 14        | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i7-6500U CPU @ 2.50GHz        | 4         | 4.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz        | 3         | 3.3%    |
| Intel Core i5-8250U CPU @ 1.60GHz        | 3         | 3.3%    |
| Intel Core i5-2430M CPU @ 2.40GHz        | 3         | 3.3%    |
| AMD Custom APU 0405                      | 3         | 3.3%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 2         | 2.2%    |
| Intel Pentium CPU N3710 @ 1.60GHz        | 2         | 2.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz        | 2         | 2.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 2.2%    |
| Intel Core i7-2640M CPU @ 2.80GHz        | 2         | 2.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 2.2%    |
| Intel Core i3-7100U CPU @ 2.40GHz        | 2         | 2.2%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz       | 2         | 2.2%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 2.2%    |
| AMD Ryzen 5 4500U with Radeon Graphics   | 2         | 2.2%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 1.1%    |
| Intel Pentium CPU P6100 @ 2.00GHz        | 1         | 1.1%    |
| Intel Pentium CPU N3540 @ 2.16GHz        | 1         | 1.1%    |
| Intel Pentium CPU B980 @ 2.40GHz         | 1         | 1.1%    |
| Intel Genuine CPU T2250 @ 1.73GHz        | 1         | 1.1%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz       | 1         | 1.1%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz       | 1         | 1.1%    |
| Intel Core i7-3740QM CPU @ 2.70GHz       | 1         | 1.1%    |
| Intel Core i7-3540M CPU @ 3.00GHz        | 1         | 1.1%    |
| Intel Core i7-10750H CPU @ 2.60GHz       | 1         | 1.1%    |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 1.1%    |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 1.1%    |
| Intel Core i5-8350U CPU @ 1.70GHz        | 1         | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz        | 1         | 1.1%    |
| Intel Core i5-8210Y CPU @ 1.60GHz        | 1         | 1.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 1.1%    |
| Intel Core i5-6300U CPU @ 2.40GHz        | 1         | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz        | 1         | 1.1%    |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1         | 1.1%    |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 1.1%    |
| Intel Core i5-2520M CPU @ 2.50GHz        | 1         | 1.1%    |
| Intel Core i5-2450M CPU @ 2.50GHz        | 1         | 1.1%    |
| Intel Core i5-2410M CPU @ 2.30GHz        | 1         | 1.1%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz       | 1         | 1.1%    |
| Intel Core i5-10210U CPU @ 1.60GHz       | 1         | 1.1%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 26        | 28.57%  |
| Intel Core i7        | 19        | 20.88%  |
| Intel Core i3        | 10        | 10.99%  |
| Other                | 7         | 7.69%   |
| Intel Pentium        | 5         | 5.49%   |
| Intel Core 2 Duo     | 4         | 4.4%    |
| Intel Celeron        | 4         | 4.4%    |
| AMD Ryzen 5          | 4         | 4.4%    |
| Intel Pentium Silver | 3         | 3.3%    |
| AMD A8               | 2         | 2.2%    |
| Intel Genuine        | 1         | 1.1%    |
| Intel Core 2         | 1         | 1.1%    |
| AMD Ryzen 9          | 1         | 1.1%    |
| AMD Ryzen 7          | 1         | 1.1%    |
| AMD Ryzen 3          | 1         | 1.1%    |
| AMD E2               | 1         | 1.1%    |
| AMD A10              | 1         | 1.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 48        | 52.75%  |
| 4      | 33        | 36.26%  |
| 6      | 6         | 6.59%   |
| 12     | 2         | 2.2%    |
| 8      | 1         | 1.1%    |
| 1      | 1         | 1.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 91        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 68        | 74.73%  |
| 1      | 23        | 25.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 89        | 97.8%   |
| 32-bit         | 1         | 1.1%    |
| Unknown        | 1         | 1.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 44.33%  |
| 0x206a7    | 11        | 11.34%  |
| 0x20655    | 4         | 4.12%   |
| 0x806ec    | 3         | 3.09%   |
| 0x806ea    | 3         | 3.09%   |
| 0x706a1    | 3         | 3.09%   |
| 0x406e3    | 2         | 2.06%   |
| 0x306d4    | 2         | 2.06%   |
| 0x306c3    | 2         | 2.06%   |
| 0x306a9    | 2         | 2.06%   |
| 0x08600106 | 2         | 2.06%   |
| 0x08108109 | 2         | 2.06%   |
| 0xa0652    | 1         | 1.03%   |
| 0x906ea    | 1         | 1.03%   |
| 0x806eb    | 1         | 1.03%   |
| 0x806e9    | 1         | 1.03%   |
| 0x806c1    | 1         | 1.03%   |
| 0x706e5    | 1         | 1.03%   |
| 0x6e8      | 1         | 1.03%   |
| 0x506c9    | 1         | 1.03%   |
| 0x406c4    | 1         | 1.03%   |
| 0x406c3    | 1         | 1.03%   |
| 0x40651    | 1         | 1.03%   |
| 0x20652    | 1         | 1.03%   |
| 0x10676    | 1         | 1.03%   |
| 0x08608104 | 1         | 1.03%   |
| 0x08600104 | 1         | 1.03%   |
| 0x07030105 | 1         | 1.03%   |
| 0x06003106 | 1         | 1.03%   |
| 0x06001119 | 1         | 1.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 19        | 20.88%  |
| SandyBridge   | 13        | 14.29%  |
| Westmere      | 6         | 6.59%   |
| Skylake       | 6         | 6.59%   |
| Unknown       | 6         | 6.59%   |
| Goldmont plus | 5         | 5.49%   |
| Silvermont    | 4         | 4.4%    |
| Penryn        | 4         | 4.4%    |
| Haswell       | 4         | 4.4%    |
| Zen 2         | 3         | 3.3%    |
| TigerLake     | 3         | 3.3%    |
| IvyBridge     | 3         | 3.3%    |
| IceLake       | 3         | 3.3%    |
| Zen+          | 2         | 2.2%    |
| Broadwell     | 2         | 2.2%    |
| Steamroller   | 1         | 1.1%    |
| Puma          | 1         | 1.1%    |
| Piledriver    | 1         | 1.1%    |
| P6            | 1         | 1.1%    |
| Goldmont      | 1         | 1.1%    |
| Core          | 1         | 1.1%    |
| CometLake     | 1         | 1.1%    |
| Bobcat        | 1         | 1.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 74        | 69.16%  |
| AMD    | 19        | 17.76%  |
| Nvidia | 14        | 13.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 10.71%  |
| Intel UHD Graphics 620                                                                   | 6         | 5.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 5.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 5.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 3.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 2.68%   |
| Intel HD Graphics 620                                                                    | 3         | 2.68%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 2.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.68%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 2.68%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 3         | 2.68%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 2.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.79%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.79%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 1.79%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.79%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.79%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.89%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.89%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.89%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.89%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.89%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 0.89%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.89%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                          | 1         | 0.89%   |
| Intel UHD Graphics 617                                                                   | 1         | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.89%   |
| Intel HD Graphics 500                                                                    | 1         | 0.89%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 1         | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 59        | 64.84%  |
| 1 x AMD        | 13        | 14.29%  |
| Intel + Nvidia | 11        | 12.09%  |
| Intel + AMD    | 4         | 4.4%    |
| 2 x Nvidia     | 1         | 1.1%    |
| 2 x AMD        | 1         | 1.1%    |
| 1 x Nvidia     | 1         | 1.1%    |
| AMD + Nvidia   | 1         | 1.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 86        | 92.47%  |
| Proprietary | 5         | 5.38%   |
| Unknown     | 2         | 2.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 78.95%  |
| 0.01-0.5   | 6         | 6.32%   |
| 0.51-1.0   | 5         | 5.26%   |
| 3.01-4.0   | 3         | 3.16%   |
| 1.01-2.0   | 3         | 3.16%   |
| 5.01-6.0   | 2         | 2.11%   |
| 2.01-3.0   | 1         | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 15        | 14.42%  |
| Chimei Innolux          | 15        | 14.42%  |
| BOE                     | 14        | 13.46%  |
| AU Optronics            | 13        | 12.5%   |
| Samsung Electronics     | 11        | 10.58%  |
| Apple                   | 6         | 5.77%   |
| PANDA                   | 4         | 3.85%   |
| Valve                   | 3         | 2.88%   |
| Dell                    | 3         | 2.88%   |
| Sony                    | 2         | 1.92%   |
| Lenovo                  | 2         | 1.92%   |
| Goldstar                | 2         | 1.92%   |
| Chi Mei Optoelectronics | 2         | 1.92%   |
| Unknown (XXX)           | 1         | 0.96%   |
| Toshiba                 | 1         | 0.96%   |
| Sharp                   | 1         | 0.96%   |
| RTK                     | 1         | 0.96%   |
| ONN                     | 1         | 0.96%   |
| InnoLux Display         | 1         | 0.96%   |
| Hewlett-Packard         | 1         | 0.96%   |
| eMachines               | 1         | 0.96%   |
| DZX                     | 1         | 0.96%   |
| AOC                     | 1         | 0.96%   |
| Ancor Communications    | 1         | 0.96%   |
| Acer                    | 1         | 0.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 3         | 2.88%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 3         | 2.88%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.88%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.92%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 2         | 1.92%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch        | 1         | 0.96%   |
| Toshiba TV TSB0212 1920x1080                                          | 1         | 0.96%   |
| Sony TV SNYEB01 1360x768                                              | 1         | 0.96%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.96%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.96%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SDC454A 3200x1800 293x165mm 13.2-inch | 1         | 0.96%   |
| RTK ARZOPA RTK3B3D 1920x1080 344x195mm 15.6-inch                      | 1         | 0.96%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.96%   |
| PANDA LCD Monitor NCP0030 1920x1080 344x194mm 15.5-inch               | 1         | 0.96%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.96%   |
| PANDA LCD Monitor NCP0025 1920x1080 344x194mm 15.5-inch               | 1         | 0.96%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 0.96%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 0.96%   |
| LG Display LCD Monitor LGD071C 1920x1080 344x194mm 15.5-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD0513 1920x1080 382x215mm 17.3-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD04FF 1920x1080 309x174mm 14.0-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD0492 1920x1080 344x194mm 15.5-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 0.96%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 1         | 0.96%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 0.96%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch               | 1         | 0.96%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 0.96%   |
| InnoLux Display LCD Monitor INL0028 1366x768 309x174mm 14.0-inch      | 1         | 0.96%   |
| Hewlett-Packard 27ea HPN3395 1920x1080 527x296mm 23.8-inch            | 1         | 0.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 37        | 38.14%  |
| 1366x768 (WXGA)   | 36        | 37.11%  |
| 1280x800 (WXGA)   | 6         | 6.19%   |
| 800x1280          | 3         | 3.09%   |
| 3840x2160 (4K)    | 3         | 3.09%   |
| 1600x900 (HD+)    | 3         | 3.09%   |
| 1440x900 (WXGA+)  | 3         | 3.09%   |
| 3200x1800 (QHD+)  | 1         | 1.03%   |
| 2560x1600         | 1         | 1.03%   |
| 2560x1080         | 1         | 1.03%   |
| 2256x1504         | 1         | 1.03%   |
| 1920x1200 (WUXGA) | 1         | 1.03%   |
| 1360x768          | 1         | 1.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 43        | 41.75%  |
| 13     | 11        | 10.68%  |
| 17     | 9         | 8.74%   |
| 14     | 9         | 8.74%   |
| 11     | 5         | 4.85%   |
| 24     | 4         | 3.88%   |
| 21     | 4         | 3.88%   |
| 72     | 3         | 2.91%   |
| 31     | 3         | 2.91%   |
| 7      | 3         | 2.91%   |
| 18     | 2         | 1.94%   |
| 12     | 2         | 1.94%   |
| 54     | 1         | 0.97%   |
| 34     | 1         | 0.97%   |
| 27     | 1         | 0.97%   |
| 23     | 1         | 0.97%   |
| 19     | 1         | 0.97%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 51.46%  |
| 201-300     | 15        | 14.56%  |
| 351-400     | 12        | 11.65%  |
| 501-600     | 6         | 5.83%   |
| 401-500     | 6         | 5.83%   |
| 601-700     | 3         | 2.91%   |
| 1501-2000   | 3         | 2.91%   |
| 1-100       | 3         | 2.91%   |
| 701-800     | 1         | 0.97%   |
| 1001-1500   | 1         | 0.97%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 78        | 82.98%  |
| 16/10 | 11        | 11.7%   |
| 0.67  | 3         | 3.19%   |
| 3/2   | 1         | 1.06%   |
| 21/9  | 1         | 1.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 43        | 41.75%  |
| 81-90          | 16        | 15.53%  |
| 121-130        | 8         | 7.77%   |
| 201-250        | 7         | 6.8%    |
| 51-60          | 5         | 4.85%   |
| More than 1000 | 4         | 3.88%   |
| 71-80          | 4         | 3.88%   |
| 351-500        | 4         | 3.88%   |
| 1-40           | 3         | 2.91%   |
| 151-200        | 3         | 2.91%   |
| 61-70          | 2         | 1.94%   |
| 141-150        | 2         | 1.94%   |
| 301-350        | 1         | 0.97%   |
| 131-140        | 1         | 0.97%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 38        | 36.54%  |
| 121-160       | 36        | 34.62%  |
| 51-100        | 17        | 16.35%  |
| 161-240       | 6         | 5.77%   |
| 1-50          | 5         | 4.81%   |
| More than 240 | 2         | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 74        | 77.89%  |
| 2     | 19        | 20%     |
| 0     | 2         | 2.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 50        | 34.01%  |
| Intel                    | 46        | 31.29%  |
| Qualcomm Atheros         | 17        | 11.56%  |
| Broadcom                 | 10        | 6.8%    |
| Broadcom Limited         | 4         | 2.72%   |
| Marvell Technology Group | 3         | 2.04%   |
| ASIX Electronics         | 3         | 2.04%   |
| TP-Link                  | 2         | 1.36%   |
| Ralink Technology        | 2         | 1.36%   |
| Nvidia                   | 2         | 1.36%   |
| NetGear                  | 2         | 1.36%   |
| Samsung Electronics      | 1         | 0.68%   |
| Ralink                   | 1         | 0.68%   |
| Qualcomm Technologies    | 1         | 0.68%   |
| MediaTek                 | 1         | 0.68%   |
| Dell                     | 1         | 0.68%   |
| Belkin Components        | 1         | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 29        | 17.37%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 4.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 3.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 2.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4         | 2.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 2.4%    |
| Intel Wireless 7265                                                    | 4         | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 2.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 3         | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 1.8%    |
| Intel Wireless 8260                                                    | 3         | 1.8%    |
| Intel Wi-Fi 6 AX200                                                    | 3         | 1.8%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 3         | 1.8%    |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 1.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.2%    |
| Nvidia MCP79 Ethernet                                                  | 2         | 1.2%    |
| Intel Wireless 8265 / 8275                                             | 2         | 1.2%    |
| Intel Wireless 3160                                                    | 2         | 1.2%    |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 1.2%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 2         | 1.2%    |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                          | 2         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.2%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.2%    |
| Broadcom Limited BCM43224 802.11a/b/g/n                                | 2         | 1.2%    |
| Broadcom BCM4331 802.11a/b/g/n                                         | 2         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1         | 0.6%    |
| TP-Link 802.11ac WLAN Adapter                                          | 1         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.6%    |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 40.82%  |
| Realtek Semiconductor | 22        | 22.45%  |
| Qualcomm Atheros      | 14        | 14.29%  |
| Broadcom              | 9         | 9.18%   |
| Broadcom Limited      | 3         | 3.06%   |
| TP-Link               | 2         | 2.04%   |
| Ralink Technology     | 2         | 2.04%   |
| Ralink                | 1         | 1.02%   |
| Qualcomm Technologies | 1         | 1.02%   |
| NetGear               | 1         | 1.02%   |
| MediaTek              | 1         | 1.02%   |
| Dell                  | 1         | 1.02%   |
| Belkin Components     | 1         | 1.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 7         | 7.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 5         | 5.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 4         | 4.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 4         | 4.04%   |
| Intel Wireless 7265                                        | 4         | 4.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 3         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 3.03%   |
| Intel Wireless 8260                                        | 3         | 3.03%   |
| Intel Wi-Fi 6 AX200                                        | 3         | 3.03%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]               | 3         | 3.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 2.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2         | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 2         | 2.02%   |
| Intel Wireless 8265 / 8275                                 | 2         | 2.02%   |
| Intel Wireless 3160                                        | 2         | 2.02%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 2.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 2         | 2.02%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 2         | 2.02%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 2         | 2.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 2         | 2.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 2.02%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2         | 2.02%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 2         | 2.02%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 2         | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 2         | 2.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 1.01%   |
| TP-Link 802.11ac WLAN Adapter                              | 1         | 1.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 1.01%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                 | 1         | 1.01%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 1.01%   |
| Realtek 802.11n WLAN Adapter                               | 1         | 1.01%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1         | 1.01%   |
| Qualcomm QCNFA765 Wireless Network Adapter                 | 1         | 1.01%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter | 1         | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1         | 1.01%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]      | 1         | 1.01%   |
| MediaTek WiFi                                              | 1         | 1.01%   |
| Intel Wireless 7260                                        | 1         | 1.01%   |
| Intel Wireless 3165                                        | 1         | 1.01%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 54.41%  |
| Intel                    | 13        | 19.12%  |
| Qualcomm Atheros         | 4         | 5.88%   |
| Marvell Technology Group | 3         | 4.41%   |
| Broadcom                 | 3         | 4.41%   |
| ASIX Electronics         | 3         | 4.41%   |
| Nvidia                   | 2         | 2.94%   |
| Samsung Electronics      | 1         | 1.47%   |
| NetGear                  | 1         | 1.47%   |
| Broadcom Limited         | 1         | 1.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 29        | 42.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 8.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 5.88%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 4.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 2.94%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 2.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 2.94%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 2.94%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 1.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.47%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.47%   |
| NetGear LB1120-100NAS                                                          | 1         | 1.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.47%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.47%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.47%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.47%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 1.47%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.47%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 1.47%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 1.47%   |
| ASIX AX88772B                                                                  | 1         | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 90        | 56.96%  |
| Ethernet | 68        | 43.04%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 79.17%  |
| Ethernet | 20        | 20.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 60        | 65.93%  |
| 1     | 28        | 30.77%  |
| 0     | 2         | 2.2%    |
| 3     | 1         | 1.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 66        | 68.75%  |
| Yes  | 30        | 31.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 41.67%  |
| Realtek Semiconductor           | 13        | 18.06%  |
| Foxconn / Hon Hai               | 6         | 8.33%   |
| Qualcomm Atheros Communications | 5         | 6.94%   |
| IMC Networks                    | 5         | 6.94%   |
| Apple                           | 5         | 6.94%   |
| Lite-On Technology              | 2         | 2.78%   |
| Dell                            | 2         | 2.78%   |
| Toshiba                         | 1         | 1.39%   |
| Hewlett-Packard                 | 1         | 1.39%   |
| Broadcom                        | 1         | 1.39%   |
| Alps Electric                   | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 9.72%   |
| Intel Bluetooth wireless interface                                                  | 7         | 9.72%   |
| Realtek Bluetooth Radio                                                             | 5         | 6.94%   |
| Intel Bluetooth Device                                                              | 5         | 6.94%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 5.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 5.56%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 5.56%   |
| Intel AX200 Bluetooth                                                               | 3         | 4.17%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 4.17%   |
| Apple Bluetooth Host Controller                                                     | 3         | 4.17%   |
| Intel AX201 Bluetooth                                                               | 2         | 2.78%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.39%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.39%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.39%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.39%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 1.39%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.39%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.39%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 1         | 1.39%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.39%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.39%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.39%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.39%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.39%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 75        | 75%     |
| AMD                 | 15        | 15%     |
| Nvidia              | 8         | 8%      |
| C-Media Electronics | 1         | 1%      |
| Apple               | 1         | 1%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 13.68%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 9.4%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 5.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 5.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 4.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 4.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 3.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.42%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2.56%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 2.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.71%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.71%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.71%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.71%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.71%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.71%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.85%   |
| Nvidia Audio device                                                                               | 1         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.85%   |
| C-Media Electronics CM106 Like Sound Device                                                       | 1         | 0.85%   |
| Apple Audio Device                                                                                | 1         | 0.85%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.85%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.85%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 11        | 34.38%  |
| Samsung Electronics | 8         | 25%     |
| Micron Technology   | 4         | 12.5%   |
| Kingston            | 4         | 12.5%   |
| Silicon Power       | 1         | 3.13%   |
| Ramaxel Technology  | 1         | 3.13%   |
| Qumo                | 1         | 3.13%   |
| PNY                 | 1         | 3.13%   |
| A-DATA Technology   | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 3         | 8.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 2         | 5.71%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                 | 1         | 2.86%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s         | 1         | 2.86%   |
| SK hynix RAM Module 4GB SODIMM LPDDR3 2133MT/s               | 1         | 2.86%   |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s                | 1         | 2.86%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 1         | 2.86%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 2.86%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.86%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.86%   |
| Silicon Power RAM Module 8GB SODIMM DDR3 1600MT/s            | 1         | 2.86%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 1         | 2.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.86%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.86%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 2.86%   |
| Qumo RAM Module 4GB SODIMM DDR3 1334MT/s                     | 1         | 2.86%   |
| PNY RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 2.86%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 1         | 2.86%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s         | 1         | 2.86%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s             | 1         | 2.86%   |
| Kingston RAM KHX1600C9S3K2/8GX 4GB SODIMM DDR3 1334MT/s      | 1         | 2.86%   |
| Kingston RAM HP691160-H66-MCN 8GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s       | 1         | 2.86%   |
| A-DATA RAM AM1L16BC4R1-B1YS 4GB SODIMM DDR3 800MT/s          | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 43.33%  |
| DDR3   | 11        | 36.67%  |
| LPDDR3 | 3         | 10%     |
| LPDDR4 | 2         | 6.67%   |
| DDR    | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 93.1%   |
| Row Of Chips | 2         | 6.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 13        | 43.33%  |
| 4096  | 12        | 40%     |
| 16384 | 4         | 13.33%  |
| 2048  | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 10        | 32.26%  |
| 2667  | 7         | 22.58%  |
| 3200  | 5         | 16.13%  |
| 2133  | 3         | 9.68%   |
| 3266  | 1         | 3.23%   |
| 2400  | 1         | 3.23%   |
| 1334  | 1         | 3.23%   |
| 1067  | 1         | 3.23%   |
| 800   | 1         | 3.23%   |
| 667   | 1         | 3.23%   |

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
| Chicony Electronics                    | 11        | 14.29%  |
| Realtek Semiconductor                  | 9         | 11.69%  |
| Ricoh                                  | 5         | 6.49%   |
| Quanta                                 | 5         | 6.49%   |
| IMC Networks                           | 5         | 6.49%   |
| Apple                                  | 5         | 6.49%   |
| Sunplus Innovation Technology          | 4         | 5.19%   |
| Microdia                               | 4         | 5.19%   |
| Lite-On Technology                     | 4         | 5.19%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.19%   |
| Bison Electronics                      | 4         | 5.19%   |
| Acer                                   | 4         | 5.19%   |
| Luxvisions Innotech Limited            | 3         | 3.9%    |
| Syntek                                 | 2         | 2.6%    |
| Suyin                                  | 2         | 2.6%    |
| Lenovo                                 | 2         | 2.6%    |
| Primax Electronics                     | 1         | 1.3%    |
| MacroSilicon                           | 1         | 1.3%    |
| Goertek Electronics                    | 1         | 1.3%    |
| Alpha Imaging Technology               | 1         | 1.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Ricoh Integrated Webcam                                        | 3         | 3.9%    |
| Lite-On HP Wide Vision HD Camera                               | 3         | 3.9%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 3.9%    |
| Sunplus Integrated_Webcam_HD                                   | 2         | 2.6%    |
| Realtek USB Camera                                             | 2         | 2.6%    |
| Realtek Integrated_Webcam_HD                                   | 2         | 2.6%    |
| Realtek Integrated Webcam HD                                   | 2         | 2.6%    |
| Quanta HP Wide Vision HD Camera                                | 2         | 2.6%    |
| Quanta HP TrueVision HD Camera                                 | 2         | 2.6%    |
| Microdia Integrated_Webcam_HD                                  | 2         | 2.6%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 2.6%    |
| Lenovo Integrated Webcam [R5U877]                              | 2         | 2.6%    |
| IMC Networks UVC VGA Webcam                                    | 2         | 2.6%    |
| Chicony HP Truevision HD                                       | 2         | 2.6%    |
| Chicony HD WebCam                                              | 2         | 2.6%    |
| Bison Lenovo EasyCamera                                        | 2         | 2.6%    |
| Apple FaceTime HD Camera                                       | 2         | 2.6%    |
| Apple Built-in iSight                                          | 2         | 2.6%    |
| Syntek Lenovo EasyCamera                                       | 1         | 1.3%    |
| Syntek Integrated Camera                                       | 1         | 1.3%    |
| Suyin USB 2.0 Camera                                           | 1         | 1.3%    |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.3%    |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.3%    |
| Sunplus Integrated Camera                                      | 1         | 1.3%    |
| Ricoh Sony Visual Communication Camera Integrated Webcam       | 1         | 1.3%    |
| Ricoh HD Webcam                                                | 1         | 1.3%    |
| Realtek Laptop Camera                                          | 1         | 1.3%    |
| Realtek Integrated Webcam                                      | 1         | 1.3%    |
| Realtek Integrated Camera                                      | 1         | 1.3%    |
| Quanta VGA WebCam                                              | 1         | 1.3%    |
| Primax HP HD Webcam [Fixed]                                    | 1         | 1.3%    |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 1.3%    |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.3%    |
| MacroSilicon MS210x Video Grabber [EasierCAP]                  | 1         | 1.3%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.3%    |
| Lite-On HP HD Webcam                                           | 1         | 1.3%    |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.3%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 1.3%    |
| IMC Networks Integrated Camera                                 | 1         | 1.3%    |
| Goertek USB2.0 VGA UVC WebCam                                  | 1         | 1.3%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 11        | 68.75%  |
| Synaptics             | 2         | 12.5%   |
| LighTuning Technology | 2         | 12.5%   |
| Upek                  | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 5         | 31.25%  |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors Fingerprint scanner                   | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.25%   |
| Synaptics UWP WBDI                                     | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 6.25%   |

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
| 0     | 59        | 64.13%  |
| 1     | 30        | 32.61%  |
| 2     | 3         | 3.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 43.24%  |
| Graphics card            | 7         | 18.92%  |
| Net/wireless             | 4         | 10.81%  |
| Chipcard                 | 4         | 10.81%  |
| Communication controller | 2         | 5.41%   |
| Storage                  | 1         | 2.7%    |
| Multimedia controller    | 1         | 2.7%    |
| Modem                    | 1         | 2.7%    |
| Camera                   | 1         | 2.7%    |

