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

Total: 221

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO        | Sirius 16 Gen2              | [db603109a0](https://linux-hardware.org/?probe=db603109a0) | Dec 21, 2024 |
| TUXEDO        | Sirius 16 Gen2              | [142da0d66b](https://linux-hardware.org/?probe=142da0d66b) | Dec 21, 2024 |
| Alienware     | m15                         | [7002846b7f](https://linux-hardware.org/?probe=7002846b7f) | Dec 21, 2024 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [5b4fa92a70](https://linux-hardware.org/?probe=5b4fa92a70) | Dec 20, 2024 |
| Google        | Kefka                       | [f7b5366d11](https://linux-hardware.org/?probe=f7b5366d11) | Dec 12, 2024 |
| TUXEDO        | Aura 15 Gen1                | [b66ce33bf3](https://linux-hardware.org/?probe=b66ce33bf3) | Nov 30, 2024 |
| Dell          | Latitude 5420               | [9e6c2d1825](https://linux-hardware.org/?probe=9e6c2d1825) | Nov 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5f31e2e5a1](https://linux-hardware.org/?probe=5f31e2e5a1) | Nov 11, 2024 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [cca5e7d15f](https://linux-hardware.org/?probe=cca5e7d15f) | Nov 11, 2024 |
| HP            | 15 Notebook PC              | [831b3ca2c3](https://linux-hardware.org/?probe=831b3ca2c3) | Nov 09, 2024 |
| HP            | 15 Notebook PC              | [0c5bfcfa09](https://linux-hardware.org/?probe=0c5bfcfa09) | Oct 24, 2024 |
| HP            | EliteBook 840 G2            | [1cad2c1f05](https://linux-hardware.org/?probe=1cad2c1f05) | Oct 20, 2024 |
| HP            | EliteBook 840 G2            | [76ef7c1a25](https://linux-hardware.org/?probe=76ef7c1a25) | Oct 15, 2024 |
| Lenovo        | ThinkPad T440 20B6005RUS    | [5152b1d77d](https://linux-hardware.org/?probe=5152b1d77d) | Oct 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4010b8ca8d](https://linux-hardware.org/?probe=4010b8ca8d) | Oct 06, 2024 |
| HP            | EliteBook 840 G2            | [f5bb6216b9](https://linux-hardware.org/?probe=f5bb6216b9) | Oct 05, 2024 |
| Dell          | Inspiron 3521               | [32cd855c59](https://linux-hardware.org/?probe=32cd855c59) | Oct 01, 2024 |
| Dell          | Inspiron 3521               | [0e57e17e13](https://linux-hardware.org/?probe=0e57e17e13) | Oct 01, 2024 |
| Dell          | Latitude 5510               | [3ab14db3ae](https://linux-hardware.org/?probe=3ab14db3ae) | Sep 19, 2024 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | [ba4a0a5792](https://linux-hardware.org/?probe=ba4a0a5792) | Sep 12, 2024 |
| Apple         | MacBookAir8,2               | [42c209d7ae](https://linux-hardware.org/?probe=42c209d7ae) | Aug 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d54b80cd10](https://linux-hardware.org/?probe=d54b80cd10) | Jul 22, 2024 |
| HP            | EliteBook 840 G2            | [af219f9ab4](https://linux-hardware.org/?probe=af219f9ab4) | Jul 17, 2024 |
| Dell          | Latitude 5420               | [888c0e84bc](https://linux-hardware.org/?probe=888c0e84bc) | Jul 16, 2024 |
| HP            | EliteBook 6930p             | [c192a8f718](https://linux-hardware.org/?probe=c192a8f718) | Jul 13, 2024 |
| ASUSTek       | X510UAR                     | [9e2faefcd3](https://linux-hardware.org/?probe=9e2faefcd3) | Jul 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [89bd38729a](https://linux-hardware.org/?probe=89bd38729a) | Jul 09, 2024 |
| ASUSTek       | X510UAR                     | [c93c6cabe1](https://linux-hardware.org/?probe=c93c6cabe1) | Jul 06, 2024 |
| Valve         | Galileo                     | [f5bd2681fd](https://linux-hardware.org/?probe=f5bd2681fd) | Jul 03, 2024 |
| Dell          | Latitude 5420               | [cba0355eb0](https://linux-hardware.org/?probe=cba0355eb0) | Jun 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [a68ec50af1](https://linux-hardware.org/?probe=a68ec50af1) | Jun 18, 2024 |
| TUXEDO        | Aura 15 Gen1                | [732c1e1bf1](https://linux-hardware.org/?probe=732c1e1bf1) | Jun 08, 2024 |
| HP            | EliteBook 840 G2            | [f62551a57f](https://linux-hardware.org/?probe=f62551a57f) | May 30, 2024 |
| Dell          | Latitude 5420               | [4c74fc0b78](https://linux-hardware.org/?probe=4c74fc0b78) | May 21, 2024 |
| HP            | ENVY dv7                    | [79378e58b1](https://linux-hardware.org/?probe=79378e58b1) | May 15, 2024 |
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
| Ubuntu 20.04                 | 17        | 13.49%  |
| Ubuntu 22.04                 | 16        | 12.7%   |
| Ubuntu 18.04                 | 5         | 3.97%   |
| Arch Rolling                 | 5         | 3.97%   |
| Fedora 40                    | 4         | 3.17%   |
| Fedora 39                    | 4         | 3.17%   |
| Pop!_OS 22.04                | 3         | 2.38%   |
| Zorin 17                     | 2         | 1.59%   |
| Ubuntu 24.04                 | 2         | 1.59%   |
| Ubuntu 22.10                 | 2         | 1.59%   |
| Ubuntu 21.10                 | 2         | 1.59%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.59%   |
| OpenMandriva 4.3             | 2         | 1.59%   |
| OpenMandriva 4.2             | 2         | 1.59%   |
| OpenMandriva 24.07           | 2         | 1.59%   |
| Linux Mint 21                | 2         | 1.59%   |
| Linux Mint 19.3              | 2         | 1.59%   |
| Fedora 38                    | 2         | 1.59%   |
| Fedora 37                    | 2         | 1.59%   |
| Elementary 7.1               | 2         | 1.59%   |
| Elementary 7                 | 2         | 1.59%   |
| Debian 11                    | 2         | 1.59%   |
| BlackPanther 18.1            | 2         | 1.59%   |
| ArcoLinux Rolling            | 2         | 1.59%   |
| Zorin 16                     | 1         | 0.79%   |
| Xubuntu 20.04                | 1         | 0.79%   |
| Ubuntu Unity 20.04           | 1         | 0.79%   |
| Ubuntu MATE 20.04            | 1         | 0.79%   |
| Ubuntu 23.10                 | 1         | 0.79%   |
| Ubuntu 23.04                 | 1         | 0.79%   |
| Ubuntu 19.10                 | 1         | 0.79%   |
| SteamOS 3.5.7                | 1         | 0.79%   |
| SteamOS 3.5.19               | 1         | 0.79%   |
| SteamOS 3.4.4                | 1         | 0.79%   |
| SteamOS 3.4.10               | 1         | 0.79%   |
| ROSA R10                     | 1         | 0.79%   |
| Peppermint 9                 | 1         | 0.79%   |
| Parrot 5.0                   | 1         | 0.79%   |
| Parrot 4.11                  | 1         | 0.79%   |
| openSUSE Leap-15.2           | 1         | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 40        | 35.09%  |
| Fedora       | 13        | 11.4%   |
| OpenMandriva | 11        | 9.65%   |
| Linux Mint   | 7         | 6.14%   |
| Arch         | 5         | 4.39%   |
| SteamOS      | 4         | 3.51%   |
| Zorin        | 3         | 2.63%   |
| Pop!_OS      | 3         | 2.63%   |
| openSUSE     | 3         | 2.63%   |
| Elementary   | 3         | 2.63%   |
| Debian       | 3         | 2.63%   |
| Parrot       | 2         | 1.75%   |
| KDE neon     | 2         | 1.75%   |
| BlackPanther | 2         | 1.75%   |
| ArcoLinux    | 2         | 1.75%   |
| Xubuntu      | 1         | 0.88%   |
| Ubuntu Unity | 1         | 0.88%   |
| Ubuntu MATE  | 1         | 0.88%   |
| ROSA         | 1         | 0.88%   |
| Peppermint   | 1         | 0.88%   |
| LMDE         | 1         | 0.88%   |
| Endless      | 1         | 0.88%   |
| EndeavourOS  | 1         | 0.88%   |
| Bazzite      | 1         | 0.88%   |
| Alpine       | 1         | 0.88%   |
| AlmaLinux    | 1         | 0.88%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 6.2.0-34-generic                    | 3         | 1.81%   |
| 5.8.0-59-generic                    | 3         | 1.81%   |
| 6.9.7-desktop-1omv2490              | 2         | 1.2%    |
| 6.8.0-48-generic                    | 2         | 1.2%    |
| 6.8.0-45-generic                    | 2         | 1.2%    |
| 6.8.0-109049-tuxedo                 | 2         | 1.2%    |
| 6.5.0-41-generic                    | 2         | 1.2%    |
| 6.5.0-35-generic                    | 2         | 1.2%    |
| 6.5.0-28-generic                    | 2         | 1.2%    |
| 6.5.0-18-generic                    | 2         | 1.2%    |
| 6.5.0-14-generic                    | 2         | 1.2%    |
| 6.3.6-200.fc38.x86_64               | 2         | 1.2%    |
| 6.2.0-32-generic                    | 2         | 1.2%    |
| 6.2.0-31-generic                    | 2         | 1.2%    |
| 5.8.0-55-generic                    | 2         | 1.2%    |
| 5.4.0-58-generic                    | 2         | 1.2%    |
| 5.19.0-42-generic                   | 2         | 1.2%    |
| 5.19.0-38-generic                   | 2         | 1.2%    |
| 5.16.7-desktop-1omv4003             | 2         | 1.2%    |
| 5.15.0-58-generic                   | 2         | 1.2%    |
| 5.15.0-46-generic                   | 2         | 1.2%    |
| 5.15.0-25-generic                   | 2         | 1.2%    |
| 5.13.0-35-generic                   | 2         | 1.2%    |
| 5.11.0-38-generic                   | 2         | 1.2%    |
| 5.11.0-27-generic                   | 2         | 1.2%    |
| 5.10.14-desktop-1omv4002            | 2         | 1.2%    |
| 5.10.0-19-amd64                     | 2         | 1.2%    |
| 6.9.12-205.fsync.fc40.x86_64        | 1         | 0.6%    |
| 6.9.11-200.t2.fc40.x86_64           | 1         | 0.6%    |
| 6.8.7-300.fc40.x86_64               | 1         | 0.6%    |
| 6.8.6-arch1-1                       | 1         | 0.6%    |
| 6.8.4-200.fc39.x86_64               | 1         | 0.6%    |
| 6.8.11-300.fc40.x86_64              | 1         | 0.6%    |
| 6.8.0-76060800daily20240311-generic | 1         | 0.6%    |
| 6.8.0-50-generic                    | 1         | 0.6%    |
| 6.8.0-49-generic                    | 1         | 0.6%    |
| 6.7.9-200.fc39.x86_64               | 1         | 0.6%    |
| 6.7.11-200.fc39.x86_64              | 1         | 0.6%    |
| 6.7.0-060700rc4-generic             | 1         | 0.6%    |
| 6.6.8-200.t2.fc39.x86_64            | 1         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 13        | 9.56%   |
| 5.15.0  | 10        | 7.35%   |
| 6.5.0   | 9         | 6.62%   |
| 5.13.0  | 8         | 5.88%   |
| 6.8.0   | 7         | 5.15%   |
| 6.2.0   | 7         | 5.15%   |
| 5.19.0  | 7         | 5.15%   |
| 5.11.0  | 5         | 3.68%   |
| 5.8.0   | 4         | 2.94%   |
| 5.3.0   | 3         | 2.21%   |
| 5.10.0  | 3         | 2.21%   |
| 4.15.0  | 3         | 2.21%   |
| 6.9.7   | 2         | 1.47%   |
| 6.6.2   | 2         | 1.47%   |
| 6.5.9   | 2         | 1.47%   |
| 6.3.6   | 2         | 1.47%   |
| 6.1.52  | 2         | 1.47%   |
| 5.16.7  | 2         | 1.47%   |
| 5.10.14 | 2         | 1.47%   |
| 6.9.12  | 1         | 0.74%   |
| 6.9.11  | 1         | 0.74%   |
| 6.8.7   | 1         | 0.74%   |
| 6.8.6   | 1         | 0.74%   |
| 6.8.4   | 1         | 0.74%   |
| 6.8.11  | 1         | 0.74%   |
| 6.7.9   | 1         | 0.74%   |
| 6.7.11  | 1         | 0.74%   |
| 6.7.0   | 1         | 0.74%   |
| 6.6.8   | 1         | 0.74%   |
| 6.6.1   | 1         | 0.74%   |
| 6.4.8   | 1         | 0.74%   |
| 6.4.6   | 1         | 0.74%   |
| 6.4.15  | 1         | 0.74%   |
| 6.4.11  | 1         | 0.74%   |
| 6.2.9   | 1         | 0.74%   |
| 6.2.8   | 1         | 0.74%   |
| 6.2.6   | 1         | 0.74%   |
| 6.2.12  | 1         | 0.74%   |
| 6.12.4  | 1         | 0.74%   |
| 6.12.1  | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 13        | 9.63%   |
| 6.8     | 11        | 8.15%   |
| 6.5     | 11        | 8.15%   |
| 6.2     | 11        | 8.15%   |
| 5.15    | 11        | 8.15%   |
| 5.19    | 8         | 5.93%   |
| 5.13    | 8         | 5.93%   |
| 5.11    | 6         | 4.44%   |
| 6.1     | 5         | 3.7%    |
| 5.3     | 5         | 3.7%    |
| 5.10    | 5         | 3.7%    |
| 6.9     | 4         | 2.96%   |
| 6.6     | 4         | 2.96%   |
| 6.4     | 4         | 2.96%   |
| 5.8     | 4         | 2.96%   |
| 6.7     | 3         | 2.22%   |
| 5.18    | 3         | 2.22%   |
| 4.15    | 3         | 2.22%   |
| 6.3     | 2         | 1.48%   |
| 6.12    | 2         | 1.48%   |
| 6.10    | 2         | 1.48%   |
| 5.16    | 2         | 1.48%   |
| 6.11    | 1         | 0.74%   |
| 5.9     | 1         | 0.74%   |
| 5.6     | 1         | 0.74%   |
| 5.14    | 1         | 0.74%   |
| 5.12    | 1         | 0.74%   |
| 4.9     | 1         | 0.74%   |
| 4.19    | 1         | 0.74%   |
| 4.18    | 1         | 0.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 104       | 98.11%  |
| i686   | 2         | 1.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 60        | 54.05%  |
| KDE5       | 21        | 18.92%  |
| X-Cinnamon | 7         | 6.31%   |
| Unknown    | 5         | 4.5%    |
| MATE       | 4         | 3.6%    |
| XFCE       | 3         | 2.7%    |
| Pantheon   | 3         | 2.7%    |
| KDE6       | 2         | 1.8%    |
| i3         | 2         | 1.8%    |
| Unity      | 1         | 0.9%    |
| LXDE       | 1         | 0.9%    |
| KDE4       | 1         | 0.9%    |
| awesome    | 1         | 0.9%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 73        | 63.48%  |
| Wayland | 41        | 35.65%  |
| Unknown | 1         | 0.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 57        | 50%     |
| GDM3    | 27        | 23.68%  |
| SDDM    | 15        | 13.16%  |
| GDM     | 8         | 7.02%   |
| LightDM | 4         | 3.51%   |
| TDM     | 2         | 1.75%   |
| KDM     | 1         | 0.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 95        | 86.36%  |
| es_PR   | 7         | 6.36%   |
| Unknown | 5         | 4.55%   |
| C       | 2         | 1.82%   |
| es_ES   | 1         | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 63        | 58.33%  |
| EFI  | 45        | 41.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 67        | 58.26%  |
| Btrfs   | 20        | 17.39%  |
| Tmpfs   | 12        | 10.43%  |
| Overlay | 12        | 10.43%  |
| Unknown | 2         | 1.74%   |
| Zfs     | 1         | 0.87%   |
| Xfs     | 1         | 0.87%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 64        | 56.14%  |
| GPT     | 39        | 34.21%  |
| MBR     | 11        | 9.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 83.78%  |
| Yes       | 18        | 16.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 84        | 76.36%  |
| Yes       | 26        | 23.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 28        | 26.42%  |
| Dell                   | 22        | 20.75%  |
| Lenovo                 | 14        | 13.21%  |
| ASUSTek Computer       | 10        | 9.43%   |
| Apple                  | 6         | 5.66%   |
| Valve                  | 4         | 3.77%   |
| Acer                   | 4         | 3.77%   |
| Toshiba                | 3         | 2.83%   |
| Sony                   | 3         | 2.83%   |
| TUXEDO                 | 2         | 1.89%   |
| GPU Company            | 2         | 1.89%   |
| Alienware              | 2         | 1.89%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.94%   |
| MSI                    | 1         | 0.94%   |
| Google                 | 1         | 0.94%   |
| Framework              | 1         | 0.94%   |
| AZW                    | 1         | 0.94%   |
| AMI                    | 1         | 0.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Valve Jupiter                            | 3         | 2.83%   |
| Dell Vostro 3550                         | 3         | 2.83%   |
| HP EliteBook 840 G2                      | 2         | 1.89%   |
| Dell Inspiron 11-3168                    | 2         | 1.89%   |
| ASUS X510UAR                             | 2         | 1.89%   |
| ASUS K53E                                | 2         | 1.89%   |
| Valve Galileo                            | 1         | 0.94%   |
| TUXEDO Sirius 16 Gen2                    | 1         | 0.94%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.94%   |
| Toshiba Satellite P755                   | 1         | 0.94%   |
| Toshiba Satellite L655                   | 1         | 0.94%   |
| Toshiba Satellite C55-C                  | 1         | 0.94%   |
| Sony VPCEA36FX                           | 1         | 0.94%   |
| Sony VGN-CS320J                          | 1         | 0.94%   |
| Sony SVE11113FXW                         | 1         | 0.94%   |
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER       | 1         | 0.94%   |
| MSI GF65 Thin 10SDR                      | 1         | 0.94%   |
| Lenovo Yoga 900-13ISK 80MK               | 1         | 0.94%   |
| Lenovo Y70-70 Touch 80DU                 | 1         | 0.94%   |
| Lenovo Y50-70 Touch 20349                | 1         | 0.94%   |
| Lenovo V14-ARE 82DQ                      | 1         | 0.94%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0000US | 1         | 0.94%   |
| Lenovo ThinkPad T510 4314RBS             | 1         | 0.94%   |
| Lenovo ThinkPad T460s 20F9003GUS         | 1         | 0.94%   |
| Lenovo ThinkPad T440 20B6005RUS          | 1         | 0.94%   |
| Lenovo ThinkPad T410 2516ADU             | 1         | 0.94%   |
| Lenovo ThinkPad E570 20H50048US          | 1         | 0.94%   |
| Lenovo ThinkPad E560 20EV002JUS          | 1         | 0.94%   |
| Lenovo ThinkPad E14 20RA004WUS           | 1         | 0.94%   |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 0.94%   |
| Lenovo G50-45 80E3                       | 1         | 0.94%   |
| HP Stream Laptop 14-CB1xxx               | 1         | 0.94%   |
| HP ProBook 6560b                         | 1         | 0.94%   |
| HP ProBook 6450b                         | 1         | 0.94%   |
| HP ProBook 450 G5                        | 1         | 0.94%   |
| HP Pavilion Laptop 15-eh1xxx             | 1         | 0.94%   |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 0.94%   |
| HP Pavilion Laptop 15-cs2xxx             | 1         | 0.94%   |
| HP Pavilion Laptop 15-cs0xxx             | 1         | 0.94%   |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 1         | 0.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 8         | 7.55%   |
| HP Laptop                  | 7         | 6.6%    |
| Dell Latitude              | 7         | 6.6%    |
| Dell Inspiron              | 7         | 6.6%    |
| HP Pavilion                | 5         | 4.72%   |
| HP EliteBook               | 4         | 3.77%   |
| Valve Jupiter              | 3         | 2.83%   |
| Toshiba Satellite          | 3         | 2.83%   |
| HP ProBook                 | 3         | 2.83%   |
| HP ENVY                    | 3         | 2.83%   |
| Dell Vostro                | 3         | 2.83%   |
| Dell XPS                   | 2         | 1.89%   |
| ASUS X510UAR               | 2         | 1.89%   |
| ASUS VivoBook              | 2         | 1.89%   |
| ASUS ROG                   | 2         | 1.89%   |
| ASUS K53E                  | 2         | 1.89%   |
| Acer Swift                 | 2         | 1.89%   |
| Acer Aspire                | 2         | 1.89%   |
| Valve Galileo              | 1         | 0.94%   |
| TUXEDO Sirius              | 1         | 0.94%   |
| TUXEDO Aura                | 1         | 0.94%   |
| Sony VPCEA36FX             | 1         | 0.94%   |
| Sony VGN-CS320J            | 1         | 0.94%   |
| Sony SVE11113FXW           | 1         | 0.94%   |
| ONE-NETBOOK TECHNOLOGY ONE | 1         | 0.94%   |
| MSI GF65                   | 1         | 0.94%   |
| Lenovo Yoga                | 1         | 0.94%   |
| Lenovo Y70-70              | 1         | 0.94%   |
| Lenovo Y50-70              | 1         | 0.94%   |
| Lenovo V14-ARE             | 1         | 0.94%   |
| Lenovo IdeaPad             | 1         | 0.94%   |
| Lenovo G50-45              | 1         | 0.94%   |
| HP Stream                  | 1         | 0.94%   |
| HP Notebook                | 1         | 0.94%   |
| HP Compaq                  | 1         | 0.94%   |
| HP 250                     | 1         | 0.94%   |
| HP 2000                    | 1         | 0.94%   |
| HP 15                      | 1         | 0.94%   |
| GPU Company GWTN156-9      | 1         | 0.94%   |
| GPU Company GWTN156-11     | 1         | 0.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 12        | 11.32%  |
| 2019 | 12        | 11.32%  |
| 2011 | 12        | 11.32%  |
| 2015 | 11        | 10.38%  |
| 2018 | 8         | 7.55%   |
| 2012 | 8         | 7.55%   |
| 2017 | 6         | 5.66%   |
| 2016 | 6         | 5.66%   |
| 2023 | 5         | 4.72%   |
| 2021 | 5         | 4.72%   |
| 2014 | 4         | 3.77%   |
| 2010 | 4         | 3.77%   |
| 2009 | 4         | 3.77%   |
| 2022 | 3         | 2.83%   |
| 2008 | 2         | 1.89%   |
| 2024 | 1         | 0.94%   |
| 2013 | 1         | 0.94%   |
| 2006 | 1         | 0.94%   |
| 2005 | 1         | 0.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 106       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 98        | 92.45%  |
| Enabled  | 8         | 7.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 105       | 99.06%  |
| Yes  | 1         | 0.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 40        | 35.71%  |
| 8.01-16.0   | 27        | 24.11%  |
| 3.01-4.0    | 21        | 18.75%  |
| 16.01-24.0  | 17        | 15.18%  |
| 1.01-2.0    | 4         | 3.57%   |
| 32.01-64.0  | 1         | 0.89%   |
| 24.01-32.0  | 1         | 0.89%   |
| 64.01-256.0 | 1         | 0.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 53        | 41.09%  |
| 2.01-3.0  | 28        | 21.71%  |
| 3.01-4.0  | 24        | 18.6%   |
| 4.01-8.0  | 16        | 12.4%   |
| 0.51-1.0  | 6         | 4.65%   |
| 8.01-16.0 | 2         | 1.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 76        | 68.47%  |
| 2      | 28        | 25.23%  |
| 3      | 5         | 4.5%    |
| 4      | 1         | 0.9%    |
| 0      | 1         | 0.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 67.92%  |
| Yes       | 34        | 32.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 74.53%  |
| No        | 27        | 25.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 99.06%  |
| No        | 1         | 0.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 79.44%  |
| No        | 22        | 20.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Puerto Rico | 106       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San Juan      | 55        | 47.83%  |
| Bayamón      | 14        | 12.17%  |
| Ponce         | 7         | 6.09%   |
| Carolina      | 5         | 4.35%   |
| Rio Grande    | 4         | 3.48%   |
| Utuado        | 3         | 2.61%   |
| Toa Baja      | 3         | 2.61%   |
| Lares         | 3         | 2.61%   |
| Caguas        | 3         | 2.61%   |
| San Sebastian | 2         | 1.74%   |
| Guaynabo      | 2         | 1.74%   |
| Cayey         | 2         | 1.74%   |
| Cabo Rojo     | 2         | 1.74%   |
| Vega Baja     | 1         | 0.87%   |
| Vega Alta     | 1         | 0.87%   |
| Santa Isabel  | 1         | 0.87%   |
| Sabana Grande | 1         | 0.87%   |
| Manati        | 1         | 0.87%   |
| Guayama       | 1         | 0.87%   |
| Cataño       | 1         | 0.87%   |
| Canovanas     | 1         | 0.87%   |
| Arecibo       | 1         | 0.87%   |
| Aguadilla     | 1         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 21        | 25     | 14.69%  |
| Samsung Electronics         | 15        | 22     | 10.49%  |
| Unknown                     | 13        | 17     | 9.09%   |
| Toshiba                     | 12        | 13     | 8.39%   |
| Hitachi                     | 11        | 33     | 7.69%   |
| Sandisk                     | 10        | 17     | 6.99%   |
| Crucial                     | 10        | 26     | 6.99%   |
| SK hynix                    | 7         | 9      | 4.9%    |
| Seagate                     | 7         | 11     | 4.9%    |
| Kingston                    | 5         | 7      | 3.5%    |
| Micron Technology           | 4         | 14     | 2.8%    |
| A-DATA Technology           | 4         | 4      | 2.8%    |
| Intel                       | 3         | 4      | 2.1%    |
| External                    | 3         | 12     | 2.1%    |
| Silicon Motion              | 2         | 2      | 1.4%    |
| Axiom                       | 2         | 10     | 1.4%    |
| W800SH                      | 1         | 1      | 0.7%    |
| SPCC                        | 1         | 3      | 0.7%    |
| PNY                         | 1         | 1      | 0.7%    |
| Phison Electronics          | 1         | 1      | 0.7%    |
| Patriot                     | 1         | 4      | 0.7%    |
| Micron/Crucial Technology   | 1         | 3      | 0.7%    |
| Lexar                       | 1         | 4      | 0.7%    |
| Kingston Technology Company | 1         | 1      | 0.7%    |
| KingSpec                    | 1         | 1      | 0.7%    |
| HGST                        | 1         | 1      | 0.7%    |
| China                       | 1         | 2      | 0.7%    |
| Apple                       | 1         | 2      | 0.7%    |
| ADATA Technology            | 1         | 1      | 0.7%    |
| Unknown                     | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Crucial CT240M500SSD1 240GB                          | 4         | 2.68%   |
| Crucial CT240BX500SSD1 240GB                         | 4         | 2.68%   |
| WDC WD5000LPVT-22G33T0 500GB                         | 3         | 2.01%   |
| Unknown MMC Card  128GB                              | 3         | 2.01%   |
| Toshiba MQ04ABF100 1TB                               | 3         | 2.01%   |
| Hitachi HTS547550A9E384 500GB                        | 3         | 2.01%   |
| External USB3.0 1TB                                  | 3         | 2.01%   |
| WDC WDS250G2B0B 250GB SSD                            | 2         | 1.34%   |
| WDC WD2500BEVS-60UST0 250GB                          | 2         | 1.34%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 2         | 1.34%   |
| Unknown MMC Card  2GB                                | 2         | 1.34%   |
| Toshiba MQ01ABD100 1TB                               | 2         | 1.34%   |
| Toshiba MK3261GSYN 320GB                             | 2         | 1.34%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 2         | 1.34%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 2         | 1.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 2         | 1.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 2         | 1.34%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD                 | 2         | 1.34%   |
| Micron 2200V_MTFDHBA512TCK 512GB                     | 2         | 1.34%   |
| Hitachi HTS543232A7A384 320GB                        | 2         | 1.34%   |
| Axiom 500GB                                          | 2         | 1.34%   |
| A-DATA SU740 1TB SSD                                 | 2         | 1.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1         | 0.67%   |
| WDC WDBNCE0010PNC 1TB SSD                            | 1         | 0.67%   |
| WDC WD5000LPCX-75VHAT0 500GB                         | 1         | 0.67%   |
| WDC WD5000BPVT-75HXZT1 500GB                         | 1         | 0.67%   |
| WDC WD32 00BEVT-00A23T0 320GB                        | 1         | 0.67%   |
| WDC WD1600BEKT-60F3T1 160GB                          | 1         | 0.67%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 1         | 0.67%   |
| WDC WD10SPCX-75KHST0 1TB                             | 1         | 0.67%   |
| WDC WD10JPVX-60JC3T1 1TB                             | 1         | 0.67%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 1         | 0.67%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                 | 1         | 0.67%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB                 | 1         | 0.67%   |
| W800SH 512GB SSD                                     | 1         | 0.67%   |
| Unknown USB DISK 3.2 1TB                             | 1         | 0.67%   |
| Unknown MMC Card  64GB                               | 1         | 0.67%   |
| Unknown MMC Card  512GB                              | 1         | 0.67%   |
| Unknown MMC Card  2TB                                | 1         | 0.67%   |
| Unknown MMC Card  256GB                              | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 17     | 30%     |
| Toshiba             | 12        | 13     | 24%     |
| Hitachi             | 11        | 33     | 22%     |
| Seagate             | 7         | 11     | 14%     |
| External            | 3         | 12     | 6%      |
| Samsung Electronics | 1         | 2      | 2%      |
| HGST                | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 25     | 22.5%   |
| Samsung Electronics | 7         | 9      | 17.5%   |
| WDC                 | 4         | 5      | 10%     |
| SanDisk             | 4         | 4      | 10%     |
| Kingston            | 4         | 6      | 10%     |
| A-DATA Technology   | 4         | 4      | 10%     |
| W800SH              | 1         | 1      | 2.5%    |
| SPCC                | 1         | 3      | 2.5%    |
| PNY                 | 1         | 1      | 2.5%    |
| Patriot             | 1         | 4      | 2.5%    |
| Micron Technology   | 1         | 1      | 2.5%    |
| Lexar               | 1         | 4      | 2.5%    |
| KingSpec            | 1         | 1      | 2.5%    |
| China               | 1         | 2      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 46        | 89     | 34.85%  |
| SSD     | 37        | 70     | 28.03%  |
| NVMe    | 33        | 65     | 25%     |
| MMC     | 13        | 17     | 9.85%   |
| Unknown | 3         | 11     | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 76        | 155    | 59.38%  |
| NVMe | 33        | 65     | 25.78%  |
| MMC  | 13        | 17     | 10.16%  |
| SAS  | 6         | 15     | 4.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 107    | 63.86%  |
| 0.51-1.0   | 28        | 50     | 33.73%  |
| 1.01-2.0   | 2         | 2      | 2.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 26.36%  |
| 251-500        | 30        | 23.26%  |
| 501-1000       | 25        | 19.38%  |
| 1-20           | 15        | 11.63%  |
| 1001-2000      | 12        | 9.3%    |
| More than 3000 | 3         | 2.33%   |
| 21-50          | 3         | 2.33%   |
| 2001-3000      | 3         | 2.33%   |
| 51-100         | 2         | 1.55%   |
| Unknown        | 2         | 1.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 43        | 31.62%  |
| 21-50     | 26        | 19.12%  |
| 101-250   | 21        | 15.44%  |
| 51-100    | 17        | 12.5%   |
| 501-1000  | 12        | 8.82%   |
| 251-500   | 10        | 7.35%   |
| 1001-2000 | 4         | 2.94%   |
| Unknown   | 2         | 1.47%   |
| 2001-3000 | 1         | 0.74%   |

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
| Detected | 78        | 209    | 70.91%  |
| Works    | 23        | 34     | 20.91%  |
| Malfunc  | 9         | 9      | 8.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 79        | 64.23%  |
| AMD                         | 8         | 6.5%    |
| SK hynix                    | 7         | 5.69%   |
| SanDisk                     | 7         | 5.69%   |
| Samsung Electronics         | 7         | 5.69%   |
| Micron Technology           | 3         | 2.44%   |
| Silicon Motion              | 2         | 1.63%   |
| Nvidia                      | 2         | 1.63%   |
| Micron/Crucial Technology   | 2         | 1.63%   |
| Kingston Technology Company | 2         | 1.63%   |
| Phison Electronics          | 1         | 0.81%   |
| ASMedia Technology          | 1         | 0.81%   |
| Apple                       | 1         | 0.81%   |
| ADATA Technology            | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 13        | 10%     |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 6.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 4.62%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 3.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 3.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 2.31%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 2.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 2.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 2.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.31%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.54%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 1.54%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 2         | 1.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.54%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 2         | 1.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.54%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 1.54%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 1.54%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.54%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.77%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.77%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 1         | 0.77%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 1         | 0.77%   |
| SanDisk PC SN735 / WD_BLACK SN750 SE NVMe SSD (DRAM-less)                        | 1         | 0.77%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 0.77%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                      | 1         | 0.77%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 0.77%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 1         | 0.77%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 0.77%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 0.77%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 1         | 0.77%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 72        | 58.06%  |
| NVMe | 33        | 26.61%  |
| RAID | 14        | 11.29%  |
| IDE  | 5         | 4.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 90        | 84.91%  |
| AMD    | 16        | 15.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz        | 5         | 4.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 4         | 3.77%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 3         | 2.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 3         | 2.83%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 3         | 2.83%   |
| AMD Custom APU 0405                      | 3         | 2.83%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 2         | 1.89%   |
| Intel Pentium CPU N3710 @ 1.60GHz        | 2         | 1.89%   |
| Intel Pentium CPU N3540 @ 2.16GHz        | 2         | 1.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 2         | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 1.89%   |
| Intel Core i7-2640M CPU @ 2.80GHz        | 2         | 1.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 1.89%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 2         | 1.89%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz       | 2         | 1.89%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz     | 2         | 1.89%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 1.89%   |
| AMD Ryzen 5 4500U with Radeon Graphics   | 2         | 1.89%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 0.94%   |
| Intel Pentium CPU P6100 @ 2.00GHz        | 1         | 0.94%   |
| Intel Pentium CPU B980 @ 2.40GHz         | 1         | 0.94%   |
| Intel Genuine CPU T2250 @ 1.73GHz        | 1         | 0.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 1         | 0.94%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz       | 1         | 0.94%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz       | 1         | 0.94%   |
| Intel Core i7-3740QM CPU @ 2.70GHz       | 1         | 0.94%   |
| Intel Core i7-3540M CPU @ 3.00GHz        | 1         | 0.94%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 1         | 0.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 0.94%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 0.94%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 1         | 0.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 1         | 0.94%   |
| Intel Core i5-8210Y CPU @ 1.60GHz        | 1         | 0.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 1         | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 1         | 0.94%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 1         | 0.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1         | 0.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 1         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 31        | 29.25%  |
| Intel Core i7        | 20        | 18.87%  |
| Other                | 11        | 10.38%  |
| Intel Core i3        | 11        | 10.38%  |
| Intel Pentium        | 6         | 5.66%   |
| Intel Core 2 Duo     | 5         | 4.72%   |
| Intel Celeron        | 5         | 4.72%   |
| AMD Ryzen 5          | 4         | 3.77%   |
| Intel Pentium Silver | 3         | 2.83%   |
| AMD Ryzen 7          | 2         | 1.89%   |
| AMD A8               | 2         | 1.89%   |
| Intel Genuine        | 1         | 0.94%   |
| Intel Core 2         | 1         | 0.94%   |
| AMD Ryzen 9          | 1         | 0.94%   |
| AMD Ryzen 3          | 1         | 0.94%   |
| AMD E2               | 1         | 0.94%   |
| AMD A10              | 1         | 0.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 53        | 50%     |
| 4      | 40        | 37.74%  |
| 6      | 7         | 6.6%    |
| 12     | 2         | 1.89%   |
| 8      | 2         | 1.89%   |
| 14     | 1         | 0.94%   |
| 1      | 1         | 0.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 106       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 80        | 75.47%  |
| 1      | 26        | 24.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 104       | 98.11%  |
| 32-bit         | 1         | 0.94%   |
| Unknown        | 1         | 0.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 52.17%  |
| 0x206a7    | 11        | 9.57%   |
| 0x20655    | 4         | 3.48%   |
| 0x806ec    | 3         | 2.61%   |
| 0x806ea    | 3         | 2.61%   |
| 0x706a1    | 3         | 2.61%   |
| 0x406e3    | 2         | 1.74%   |
| 0x306d4    | 2         | 1.74%   |
| 0x306c3    | 2         | 1.74%   |
| 0x306a9    | 2         | 1.74%   |
| 0x08600106 | 2         | 1.74%   |
| 0x08108109 | 2         | 1.74%   |
| 0xa0652    | 1         | 0.87%   |
| 0x906ea    | 1         | 0.87%   |
| 0x806eb    | 1         | 0.87%   |
| 0x806e9    | 1         | 0.87%   |
| 0x806c1    | 1         | 0.87%   |
| 0x706e5    | 1         | 0.87%   |
| 0x6e8      | 1         | 0.87%   |
| 0x506c9    | 1         | 0.87%   |
| 0x406c4    | 1         | 0.87%   |
| 0x406c3    | 1         | 0.87%   |
| 0x40651    | 1         | 0.87%   |
| 0x30678    | 1         | 0.87%   |
| 0x20652    | 1         | 0.87%   |
| 0x10676    | 1         | 0.87%   |
| 0x08608104 | 1         | 0.87%   |
| 0x08600104 | 1         | 0.87%   |
| 0x07030105 | 1         | 0.87%   |
| 0x06003106 | 1         | 0.87%   |
| 0x06001119 | 1         | 0.87%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 21.7%   |
| SandyBridge      | 13        | 12.26%  |
| Unknown          | 8         | 7.55%   |
| Westmere         | 6         | 5.66%   |
| Skylake          | 6         | 5.66%   |
| Silvermont       | 6         | 5.66%   |
| TigerLake        | 5         | 4.72%   |
| Penryn           | 5         | 4.72%   |
| Haswell          | 5         | 4.72%   |
| Goldmont plus    | 5         | 4.72%   |
| IvyBridge        | 4         | 3.77%   |
| Zen 2            | 3         | 2.83%   |
| IceLake          | 3         | 2.83%   |
| Broadwell        | 3         | 2.83%   |
| Zen+             | 2         | 1.89%   |
| Steamroller      | 1         | 0.94%   |
| Puma             | 1         | 0.94%   |
| Piledriver       | 1         | 0.94%   |
| P6               | 1         | 0.94%   |
| Goldmont         | 1         | 0.94%   |
| Core             | 1         | 0.94%   |
| CometLake        | 1         | 0.94%   |
| Bobcat           | 1         | 0.94%   |
| Alderlake Hybrid | 1         | 0.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 86        | 69.92%  |
| AMD    | 22        | 17.89%  |
| Nvidia | 15        | 12.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 9.3%    |
| Intel UHD Graphics 620                                                                   | 8         | 6.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 4.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 4.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 3.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 3.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 3.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 3.1%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.1%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 2.33%   |
| Intel HD Graphics 620                                                                    | 3         | 2.33%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.33%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.33%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 2.33%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 3         | 2.33%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 2.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.55%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.55%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 1.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.55%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.55%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.78%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.78%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.78%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.78%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.78%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.78%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 0.78%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.78%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                          | 1         | 0.78%   |
| Intel UHD Graphics 617                                                                   | 1         | 0.78%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 1         | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 70        | 66.04%  |
| 1 x AMD        | 15        | 14.15%  |
| Intel + Nvidia | 12        | 11.32%  |
| Intel + AMD    | 4         | 3.77%   |
| 2 x AMD        | 2         | 1.89%   |
| 2 x Nvidia     | 1         | 0.94%   |
| 1 x Nvidia     | 1         | 0.94%   |
| AMD + Nvidia   | 1         | 0.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 99        | 91.67%  |
| Proprietary | 6         | 5.56%   |
| Unknown     | 3         | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 80.18%  |
| 0.01-0.5   | 7         | 6.31%   |
| 0.51-1.0   | 5         | 4.5%    |
| 3.01-4.0   | 3         | 2.7%    |
| 1.01-2.0   | 3         | 2.7%    |
| 5.01-6.0   | 2         | 1.8%    |
| 7.01-8.0   | 1         | 0.9%    |
| 2.01-3.0   | 1         | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 20        | 16.53%  |
| Chimei Innolux          | 18        | 14.88%  |
| BOE                     | 17        | 14.05%  |
| AU Optronics            | 15        | 12.4%   |
| Samsung Electronics     | 11        | 9.09%   |
| Apple                   | 6         | 4.96%   |
| Valve                   | 4         | 3.31%   |
| PANDA                   | 4         | 3.31%   |
| Goldstar                | 3         | 2.48%   |
| Dell                    | 3         | 2.48%   |
| Sony                    | 2         | 1.65%   |
| Lenovo                  | 2         | 1.65%   |
| Hewlett-Packard         | 2         | 1.65%   |
| Chi Mei Optoelectronics | 2         | 1.65%   |
| Unknown (XXX)           | 1         | 0.83%   |
| Toshiba                 | 1         | 0.83%   |
| Sharp                   | 1         | 0.83%   |
| RTK                     | 1         | 0.83%   |
| ONN                     | 1         | 0.83%   |
| InnoLux Display         | 1         | 0.83%   |
| eMachines               | 1         | 0.83%   |
| DZX                     | 1         | 0.83%   |
| ASUSTek Computer        | 1         | 0.83%   |
| AOC                     | 1         | 0.83%   |
| Ancor Communications    | 1         | 0.83%   |
| Acer                    | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 3         | 2.48%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 3         | 2.48%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 3         | 2.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.48%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 2         | 1.65%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 1.65%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 1.65%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch       | 2         | 1.65%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                   | 1         | 0.83%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch        | 1         | 0.83%   |
| Toshiba TV TSB0212 1920x1080                                          | 1         | 0.83%   |
| Sony TV SNYEB01 1360x768                                              | 1         | 0.83%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.83%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.83%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC454A 3200x1800 293x165mm 13.2-inch | 1         | 0.83%   |
| RTK ARZOPA RTK3B3D 1920x1080 344x195mm 15.6-inch                      | 1         | 0.83%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.83%   |
| PANDA LCD Monitor NCP0030 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| PANDA LCD Monitor NCP0025 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 0.83%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 0.83%   |
| LG Display LCD Monitor LGD071C 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0513 1920x1080 382x215mm 17.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD04FF 1920x1080 309x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0492 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 43        | 38.05%  |
| 1366x768 (WXGA)   | 41        | 36.28%  |
| 1280x800 (WXGA)   | 6         | 5.31%   |
| 800x1280          | 4         | 3.54%   |
| 3840x2160 (4K)    | 3         | 2.65%   |
| 1600x900 (HD+)    | 3         | 2.65%   |
| 1440x900 (WXGA+)  | 3         | 2.65%   |
| 2560x1440 (QHD)   | 2         | 1.77%   |
| 3440x1440         | 1         | 0.88%   |
| 3200x1800 (QHD+)  | 1         | 0.88%   |
| 2560x1600         | 1         | 0.88%   |
| 2560x1080         | 1         | 0.88%   |
| 2256x1504         | 1         | 0.88%   |
| 1920x1200 (WUXGA) | 1         | 0.88%   |
| 1600x2560         | 1         | 0.88%   |
| 1360x768          | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 50        | 42.02%  |
| 13     | 12        | 10.08%  |
| 14     | 11        | 9.24%   |
| 17     | 9         | 7.56%   |
| 11     | 6         | 5.04%   |
| 31     | 4         | 3.36%   |
| 24     | 4         | 3.36%   |
| 7      | 4         | 3.36%   |
| 72     | 3         | 2.52%   |
| 21     | 3         | 2.52%   |
| 34     | 2         | 1.68%   |
| 27     | 2         | 1.68%   |
| 18     | 2         | 1.68%   |
| 12     | 2         | 1.68%   |
| 54     | 1         | 0.84%   |
| 23     | 1         | 0.84%   |
| 19     | 1         | 0.84%   |
| 16     | 1         | 0.84%   |
| 8      | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 63        | 52.94%  |
| 201-300     | 16        | 13.45%  |
| 351-400     | 13        | 10.92%  |
| 501-600     | 7         | 5.88%   |
| 401-500     | 5         | 4.2%    |
| 601-700     | 4         | 3.36%   |
| 1-100       | 4         | 3.36%   |
| 1501-2000   | 3         | 2.52%   |
| 701-800     | 2         | 1.68%   |
| 101-200     | 1         | 0.84%   |
| 1001-1500   | 1         | 0.84%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 91        | 82.73%  |
| 16/10 | 11        | 10%     |
| 0.67  | 3         | 2.73%   |
| 21/9  | 2         | 1.82%   |
| 3/2   | 1         | 0.91%   |
| 0.63  | 1         | 0.91%   |
| 0.62  | 1         | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 51        | 42.86%  |
| 81-90          | 19        | 15.97%  |
| 121-130        | 8         | 6.72%   |
| 51-60          | 6         | 5.04%   |
| 351-500        | 6         | 5.04%   |
| 201-250        | 6         | 5.04%   |
| 1-40           | 5         | 4.2%    |
| More than 1000 | 4         | 3.36%   |
| 71-80          | 4         | 3.36%   |
| 151-200        | 3         | 2.52%   |
| 61-70          | 2         | 1.68%   |
| 301-350        | 2         | 1.68%   |
| 141-150        | 2         | 1.68%   |
| 131-140        | 1         | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 43        | 35.83%  |
| 101-120       | 43        | 35.83%  |
| 51-100        | 18        | 15%     |
| 161-240       | 8         | 6.67%   |
| 1-50          | 5         | 4.17%   |
| More than 240 | 3         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 87        | 78.38%  |
| 2     | 21        | 18.92%  |
| 0     | 3         | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 57        | 33.14%  |
| Realtek Semiconductor    | 56        | 32.56%  |
| Qualcomm Atheros         | 19        | 11.05%  |
| Broadcom                 | 10        | 5.81%   |
| Broadcom Limited         | 5         | 2.91%   |
| ASIX Electronics         | 4         | 2.33%   |
| Marvell Technology Group | 3         | 1.74%   |
| TP-Link                  | 2         | 1.16%   |
| Samsung Electronics      | 2         | 1.16%   |
| Ralink Technology        | 2         | 1.16%   |
| Nvidia                   | 2         | 1.16%   |
| NetGear                  | 2         | 1.16%   |
| MediaTek                 | 2         | 1.16%   |
| Ralink                   | 1         | 0.58%   |
| Qualcomm Technologies    | 1         | 0.58%   |
| Qualcomm                 | 1         | 0.58%   |
| Dell                     | 1         | 0.58%   |
| Belkin Components        | 1         | 0.58%   |
| Apple                    | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 30        | 15.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 3.57%   |
| Intel Wireless 7265                                                    | 6         | 3.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 2.04%   |
| Intel Wireless 8265 / 8275                                             | 4         | 2.04%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 2.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3         | 1.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 3         | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 1.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 1.53%   |
| Intel Wireless 8260                                                    | 3         | 1.53%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 1.53%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 3         | 1.53%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.53%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.53%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 1.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.02%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 1.02%   |
| Intel Wireless 7260                                                    | 2         | 1.02%   |
| Intel Wireless 3160                                                    | 2         | 1.02%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.02%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 2         | 1.02%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                          | 2         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.02%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter   | 2         | 1.02%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                | 2         | 1.02%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 2         | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 44.35%  |
| Realtek Semiconductor | 24        | 20.87%  |
| Qualcomm Atheros      | 15        | 13.04%  |
| Broadcom              | 9         | 7.83%   |
| Broadcom Limited      | 4         | 3.48%   |
| TP-Link               | 2         | 1.74%   |
| Ralink Technology     | 2         | 1.74%   |
| MediaTek              | 2         | 1.74%   |
| Ralink                | 1         | 0.87%   |
| Qualcomm Technologies | 1         | 0.87%   |
| Qualcomm              | 1         | 0.87%   |
| NetGear               | 1         | 0.87%   |
| Dell                  | 1         | 0.87%   |
| Belkin Components     | 1         | 0.87%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 7         | 6.03%   |
| Intel Wireless 7265                                                  | 6         | 5.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 5         | 4.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 4         | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 3.45%   |
| Intel Wireless 8265 / 8275                                           | 4         | 3.45%   |
| Intel Wi-Fi 6 AX201                                                  | 4         | 3.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 3         | 2.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 3         | 2.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 2.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 2.59%   |
| Intel Wireless 8260                                                  | 3         | 2.59%   |
| Intel Wi-Fi 6 AX200                                                  | 3         | 2.59%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 3         | 2.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 1.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 1.72%   |
| Intel Wireless 7260                                                  | 2         | 1.72%   |
| Intel Wireless 3160                                                  | 2         | 1.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2         | 1.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 2         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1.72%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 2         | 1.72%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                        | 2         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 1.72%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 2         | 1.72%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                              | 2         | 1.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 2         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 1.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1         | 0.86%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1         | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1         | 0.86%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.86%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1         | 0.86%   |
| Realtek 802.11n WLAN Adapter                                         | 1         | 0.86%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter               | 1         | 0.86%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 1         | 0.86%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 1         | 0.86%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter           | 1         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 41        | 51.25%  |
| Intel                    | 17        | 21.25%  |
| Qualcomm Atheros         | 5         | 6.25%   |
| ASIX Electronics         | 4         | 5%      |
| Marvell Technology Group | 3         | 3.75%   |
| Broadcom                 | 3         | 3.75%   |
| Samsung Electronics      | 2         | 2.5%    |
| Nvidia                   | 2         | 2.5%    |
| NetGear                  | 1         | 1.25%   |
| Broadcom Limited         | 1         | 1.25%   |
| Apple                    | 1         | 1.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 30        | 37.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 5%      |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 3.75%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 3.75%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 2.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 2.5%    |
| Nvidia MCP79 Ethernet                                                          | 2         | 2.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.25%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.25%   |
| NetGear LB1120-100NAS                                                          | 1         | 1.25%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.25%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.25%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.25%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.25%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.25%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.25%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.25%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 1.25%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 1.25%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 1.25%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.25%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 1.25%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 1.25%   |
| ASIX AX88772B                                                                  | 1         | 1.25%   |
| Apple iBridge                                                                  | 1         | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 57.07%  |
| Ethernet | 79        | 42.93%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 77.19%  |
| Ethernet | 26        | 22.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 68        | 64.15%  |
| 1     | 35        | 33.02%  |
| 0     | 2         | 1.89%   |
| 3     | 1         | 0.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 67.86%  |
| Yes  | 36        | 32.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 47.06%  |
| Realtek Semiconductor           | 13        | 15.29%  |
| IMC Networks                    | 6         | 7.06%   |
| Foxconn / Hon Hai               | 6         | 7.06%   |
| Qualcomm Atheros Communications | 5         | 5.88%   |
| Apple                           | 5         | 5.88%   |
| Dell                            | 3         | 3.53%   |
| Lite-On Technology              | 2         | 2.35%   |
| Hewlett-Packard                 | 2         | 2.35%   |
| Toshiba                         | 1         | 1.18%   |
| Broadcom                        | 1         | 1.18%   |
| Alps Electric                   | 1         | 1.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 17        | 20%     |
| Realtek  Bluetooth 4.2 Adapter                                                      | 9         | 10.59%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 9.41%   |
| Intel AX201 Bluetooth                                                               | 5         | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 4.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 4.71%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 4.71%   |
| Realtek Bluetooth Radio                                                             | 3         | 3.53%   |
| Intel AX200 Bluetooth                                                               | 3         | 3.53%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 3.53%   |
| Apple Bluetooth Host Controller                                                     | 3         | 3.53%   |
| Intel AX210 Bluetooth                                                               | 2         | 2.35%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 2.35%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.18%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 1.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.18%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.18%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.18%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.18%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 1.18%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.18%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.18%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 1         | 1.18%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.18%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.18%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.18%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.18%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.18%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.18%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 88        | 75.86%  |
| AMD                 | 17        | 14.66%  |
| Nvidia              | 9         | 7.76%   |
| C-Media Electronics | 1         | 0.86%   |
| Apple               | 1         | 0.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 13.14%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 8.03%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 8         | 5.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 4.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 3.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 3.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 5         | 3.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.92%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.92%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.92%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.19%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.19%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.46%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 1.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.46%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.73%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.73%   |
| Nvidia AD106M High Definition Audio Controller                                                    | 1         | 0.73%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 0.73%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.73%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.73%   |
| C-Media Electronics CM106 Like Sound Device                                                       | 1         | 0.73%   |
| Apple Audio Device                                                                                | 1         | 0.73%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 13        | 32.5%   |
| Samsung Electronics | 11        | 27.5%   |
| Micron Technology   | 5         | 12.5%   |
| Kingston            | 4         | 10%     |
| Silicon Power       | 1         | 2.5%    |
| Ramaxel Technology  | 1         | 2.5%    |
| Qumo                | 1         | 2.5%    |
| PNY                 | 1         | 2.5%    |
| Elpida              | 1         | 2.5%    |
| Corsair             | 1         | 2.5%    |
| A-DATA Technology   | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s     | 3         | 6.82%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 2         | 4.55%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 4.55%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                 | 1         | 2.27%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s         | 1         | 2.27%   |
| SK hynix RAM Module 4GB SODIMM LPDDR3 2133MT/s               | 1         | 2.27%   |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s                | 1         | 2.27%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.27%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 2.27%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.27%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 1         | 2.27%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 2.27%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.27%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 2.27%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.27%   |
| SK hynix RAM H9CCNNN8GTALAR-NUD 2GB LPDDR3 1600MT/s          | 1         | 2.27%   |
| Silicon Power RAM Module 8GB SODIMM DDR3 1600MT/s            | 1         | 2.27%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.27%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 1         | 2.27%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 2.27%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.27%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.27%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 2.27%   |
| Qumo RAM Module 4GB SODIMM DDR3 1334MT/s                     | 1         | 2.27%   |
| PNY RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 2.27%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 1         | 2.27%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s       | 1         | 2.27%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s         | 1         | 2.27%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s         | 1         | 2.27%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 1         | 2.27%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s             | 1         | 2.27%   |
| Kingston RAM KHYXPX-MID 8GB SODIMM DDR4 2667MT/s             | 1         | 2.27%   |
| Kingston RAM KHX1600C9S3K2/8GX 4GB SODIMM DDR3 1334MT/s      | 1         | 2.27%   |
| Kingston RAM HP691160-H66-MCN 8GB SODIMM DDR3 1600MT/s       | 1         | 2.27%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 2.27%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s       | 1         | 2.27%   |
| Elpida RAM EBE21UE8ACUA-8G-E 2GB SODIMM DDR 975MT/s          | 1         | 2.27%   |
| Corsair RAM CMS5X32G2A56C48A2 32GB SODIMM DDR5 5600MT/s      | 1         | 2.27%   |
| A-DATA RAM AM1L16BC4R1-B1YS 4GB SODIMM DDR3 800MT/s          | 1         | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 17        | 45.95%  |
| DDR3   | 11        | 29.73%  |
| LPDDR3 | 4         | 10.81%  |
| LPDDR4 | 2         | 5.41%   |
| DDR5   | 1         | 2.7%    |
| DDR2   | 1         | 2.7%    |
| DDR    | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 91.67%  |
| Row Of Chips | 2         | 5.56%   |
| Unknown      | 1         | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 16        | 43.24%  |
| 4096  | 12        | 32.43%  |
| 16384 | 5         | 13.51%  |
| 2048  | 3         | 8.11%   |
| 32768 | 1         | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 11        | 28.95%  |
| 2667  | 9         | 23.68%  |
| 3200  | 7         | 18.42%  |
| 2133  | 3         | 7.89%   |
| 5600  | 1         | 2.63%   |
| 3266  | 1         | 2.63%   |
| 2400  | 1         | 2.63%   |
| 1334  | 1         | 2.63%   |
| 1067  | 1         | 2.63%   |
| 975   | 1         | 2.63%   |
| 800   | 1         | 2.63%   |
| 667   | 1         | 2.63%   |

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
| Chicony Electronics                    | 12        | 13.64%  |
| Realtek Semiconductor                  | 11        | 12.5%   |
| Bison Electronics                      | 7         | 7.95%   |
| Sunplus Innovation Technology          | 6         | 6.82%   |
| Microdia                               | 6         | 6.82%   |
| Ricoh                                  | 5         | 5.68%   |
| Quanta                                 | 5         | 5.68%   |
| Lite-On Technology                     | 5         | 5.68%   |
| IMC Networks                           | 5         | 5.68%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 5.68%   |
| Apple                                  | 5         | 5.68%   |
| Luxvisions Innotech Limited            | 3         | 3.41%   |
| Syntek                                 | 2         | 2.27%   |
| Suyin                                  | 2         | 2.27%   |
| Lenovo                                 | 2         | 2.27%   |
| Acer                                   | 2         | 2.27%   |
| ShineTech                              | 1         | 1.14%   |
| Primax Electronics                     | 1         | 1.14%   |
| MacroSilicon                           | 1         | 1.14%   |
| Goertek Electronics                    | 1         | 1.14%   |
| Alpha Imaging Technology               | 1         | 1.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 3         | 3.37%   |
| Ricoh Integrated Webcam                                        | 3         | 3.37%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 3.37%   |
| Lite-On HP Wide Vision HD Camera                               | 3         | 3.37%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 3.37%   |
| Realtek Integrated Webcam HD                                   | 2         | 2.25%   |
| Quanta HP Wide Vision HD Camera                                | 2         | 2.25%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 2.25%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 2         | 2.25%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 2.25%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 2.25%   |
| Lite-On HP HD Webcam                                           | 2         | 2.25%   |
| Lenovo Integrated Webcam [R5U877]                              | 2         | 2.25%   |
| IMC Networks UVC VGA Webcam                                    | 2         | 2.25%   |
| Chicony HP Truevision HD                                       | 2         | 2.25%   |
| Chicony HD WebCam                                              | 2         | 2.25%   |
| Bison Lenovo EasyCamera                                        | 2         | 2.25%   |
| Apple FaceTime HD Camera                                       | 2         | 2.25%   |
| Apple Built-in iSight                                          | 2         | 2.25%   |
| Syntek Lenovo EasyCamera                                       | 1         | 1.12%   |
| Syntek Integrated Camera                                       | 1         | 1.12%   |
| Suyin USB 2.0 Camera                                           | 1         | 1.12%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.12%   |
| Sunplus MTD Camera                                             | 1         | 1.12%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.12%   |
| Sunplus DICOTA 4K                                              | 1         | 1.12%   |
| ShineTech USB2.0 HD UVC WebCam                                 | 1         | 1.12%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam       | 1         | 1.12%   |
| Ricoh HD Webcam                                                | 1         | 1.12%   |
| Realtek USB2.0 camera                                          | 1         | 1.12%   |
| Realtek Laptop Camera                                          | 1         | 1.12%   |
| Realtek Integrated_Webcam_FHD                                  | 1         | 1.12%   |
| Realtek Integrated Webcam                                      | 1         | 1.12%   |
| Realtek Integrated Camera                                      | 1         | 1.12%   |
| Realtek 2SF022                                                 | 1         | 1.12%   |
| Quanta HD WebCam                                               | 1         | 1.12%   |
| Primax HP HD Webcam [Fixed]                                    | 1         | 1.12%   |
| Microdia Integrated Camera                                     | 1         | 1.12%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.12%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]                  | 1         | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 12        | 66.67%  |
| Synaptics             | 2         | 11.11%  |
| LighTuning Technology | 2         | 11.11%  |
| Upek                  | 1         | 5.56%   |
| AuthenTec             | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 5         | 27.78%  |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 11.11%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 11.11%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.56%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5.56%   |
| Validity Sensors Fingerprint scanner                   | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.56%   |
| Synaptics UWP WBDI                                     | 1         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 5.56%   |
| AuthenTec AES2810                                      | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom 5880                                                                | 1         | 20%     |
| Broadcom 58200                                                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 70        | 65.42%  |
| 1     | 34        | 31.78%  |
| 2     | 3         | 2.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 43.9%   |
| Graphics card            | 7         | 17.07%  |
| Net/wireless             | 5         | 12.2%   |
| Chipcard                 | 5         | 12.2%   |
| Communication controller | 2         | 4.88%   |
| Storage                  | 1         | 2.44%   |
| Multimedia controller    | 1         | 2.44%   |
| Modem                    | 1         | 2.44%   |
| Camera                   | 1         | 2.44%   |

