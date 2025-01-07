Linux in Puerto Rico - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Puerto Rico.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Puerto_Rico/Desktop/README.md) and [notebooks](/Location/Puerto_Rico/Notebook/README.md).

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

Total: 384

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| TUXEDO        | Sirius 16 Gen2              | Notebook    | [db603109a0](https://linux-hardware.org/?probe=db603109a0) | Dec 21, 2024 |
| TUXEDO        | Sirius 16 Gen2              | Notebook    | [142da0d66b](https://linux-hardware.org/?probe=142da0d66b) | Dec 21, 2024 |
| Alienware     | m15                         | Notebook    | [7002846b7f](https://linux-hardware.org/?probe=7002846b7f) | Dec 21, 2024 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [5b4fa92a70](https://linux-hardware.org/?probe=5b4fa92a70) | Dec 20, 2024 |
| MSI           | MS-B1711                    | Desktop     | [e389d750a3](https://linux-hardware.org/?probe=e389d750a3) | Dec 14, 2024 |
| Google        | Kefka                       | Notebook    | [f7b5366d11](https://linux-hardware.org/?probe=f7b5366d11) | Dec 12, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [efae733196](https://linux-hardware.org/?probe=efae733196) | Dec 01, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [b66ce33bf3](https://linux-hardware.org/?probe=b66ce33bf3) | Nov 30, 2024 |
| Dell          | Latitude 5420               | Notebook    | [9e6c2d1825](https://linux-hardware.org/?probe=9e6c2d1825) | Nov 28, 2024 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [799a5ecff4](https://linux-hardware.org/?probe=799a5ecff4) | Nov 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5f31e2e5a1](https://linux-hardware.org/?probe=5f31e2e5a1) | Nov 11, 2024 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [cca5e7d15f](https://linux-hardware.org/?probe=cca5e7d15f) | Nov 11, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [831b3ca2c3](https://linux-hardware.org/?probe=831b3ca2c3) | Nov 09, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [0c5bfcfa09](https://linux-hardware.org/?probe=0c5bfcfa09) | Oct 24, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [1cad2c1f05](https://linux-hardware.org/?probe=1cad2c1f05) | Oct 20, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [76ef7c1a25](https://linux-hardware.org/?probe=76ef7c1a25) | Oct 15, 2024 |
| Lenovo        | ThinkPad T440 20B6005RUS    | Notebook    | [5152b1d77d](https://linux-hardware.org/?probe=5152b1d77d) | Oct 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4010b8ca8d](https://linux-hardware.org/?probe=4010b8ca8d) | Oct 06, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [f5bb6216b9](https://linux-hardware.org/?probe=f5bb6216b9) | Oct 05, 2024 |
| Dell          | 0FDY5C A00                  | Desktop     | [2975c3986e](https://linux-hardware.org/?probe=2975c3986e) | Oct 02, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [32cd855c59](https://linux-hardware.org/?probe=32cd855c59) | Oct 01, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [0e57e17e13](https://linux-hardware.org/?probe=0e57e17e13) | Oct 01, 2024 |
| Dell          | Latitude 5510               | Notebook    | [3ab14db3ae](https://linux-hardware.org/?probe=3ab14db3ae) | Sep 19, 2024 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [4202cf424e](https://linux-hardware.org/?probe=4202cf424e) | Sep 16, 2024 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | Notebook    | [ba4a0a5792](https://linux-hardware.org/?probe=ba4a0a5792) | Sep 12, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [30c637782b](https://linux-hardware.org/?probe=30c637782b) | Sep 10, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7579c9ebe1](https://linux-hardware.org/?probe=7579c9ebe1) | Sep 03, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c83b938a0f](https://linux-hardware.org/?probe=c83b938a0f) | Aug 28, 2024 |
| Apple         | MacBookAir8,2               | Notebook    | [42c209d7ae](https://linux-hardware.org/?probe=42c209d7ae) | Aug 03, 2024 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [b3488f2839](https://linux-hardware.org/?probe=b3488f2839) | Jul 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d54b80cd10](https://linux-hardware.org/?probe=d54b80cd10) | Jul 22, 2024 |
| GEEKOM        | GT13 Pro                    | Server      | [93032c41f9](https://linux-hardware.org/?probe=93032c41f9) | Jul 17, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [af219f9ab4](https://linux-hardware.org/?probe=af219f9ab4) | Jul 17, 2024 |
| Dell          | Latitude 5420               | Notebook    | [888c0e84bc](https://linux-hardware.org/?probe=888c0e84bc) | Jul 16, 2024 |
| HP            | EliteBook 6930p             | Notebook    | [c192a8f718](https://linux-hardware.org/?probe=c192a8f718) | Jul 13, 2024 |
| HP            | 89B5 A                      | Desktop     | [f87a73cfdf](https://linux-hardware.org/?probe=f87a73cfdf) | Jul 11, 2024 |
| ASUSTek       | X510UAR                     | Notebook    | [9e2faefcd3](https://linux-hardware.org/?probe=9e2faefcd3) | Jul 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [89bd38729a](https://linux-hardware.org/?probe=89bd38729a) | Jul 09, 2024 |
| ASUSTek       | X510UAR                     | Notebook    | [c93c6cabe1](https://linux-hardware.org/?probe=c93c6cabe1) | Jul 06, 2024 |
| Valve         | Galileo                     | Notebook    | [f5bd2681fd](https://linux-hardware.org/?probe=f5bd2681fd) | Jul 03, 2024 |
| Dell          | Latitude 5420               | Notebook    | [cba0355eb0](https://linux-hardware.org/?probe=cba0355eb0) | Jun 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [a68ec50af1](https://linux-hardware.org/?probe=a68ec50af1) | Jun 18, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [3faecb222b](https://linux-hardware.org/?probe=3faecb222b) | Jun 12, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [732c1e1bf1](https://linux-hardware.org/?probe=732c1e1bf1) | Jun 08, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [f62551a57f](https://linux-hardware.org/?probe=f62551a57f) | May 30, 2024 |
| Dell          | Latitude 5420               | Notebook    | [4c74fc0b78](https://linux-hardware.org/?probe=4c74fc0b78) | May 21, 2024 |
| HP            | ENVY dv7                    | Notebook    | [79378e58b1](https://linux-hardware.org/?probe=79378e58b1) | May 15, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c94fe08160](https://linux-hardware.org/?probe=c94fe08160) | May 02, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [92878d7fb2](https://linux-hardware.org/?probe=92878d7fb2) | Apr 28, 2024 |
| Dell          | Latitude 3150               | Notebook    | [2591de095d](https://linux-hardware.org/?probe=2591de095d) | Apr 22, 2024 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [07ab4bf081](https://linux-hardware.org/?probe=07ab4bf081) | Apr 20, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [56a4aeab46](https://linux-hardware.org/?probe=56a4aeab46) | Apr 17, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b70239f287](https://linux-hardware.org/?probe=b70239f287) | Apr 15, 2024 |
| HP            | EliteBook 8560p             | Notebook    | [e9b9656231](https://linux-hardware.org/?probe=e9b9656231) | Apr 09, 2024 |
| Alienware     | m18 R1 AMD                  | Notebook    | [8031bfa7f7](https://linux-hardware.org/?probe=8031bfa7f7) | Apr 08, 2024 |
| Lenovo        | ThinkPad T460s 20F9003GU... | Notebook    | [497b326dc9](https://linux-hardware.org/?probe=497b326dc9) | Apr 04, 2024 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [6ea19c4f02](https://linux-hardware.org/?probe=6ea19c4f02) | Apr 04, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [922723cbd4](https://linux-hardware.org/?probe=922723cbd4) | Mar 30, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3932e020fb](https://linux-hardware.org/?probe=3932e020fb) | Mar 30, 2024 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [25d9669839](https://linux-hardware.org/?probe=25d9669839) | Mar 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bdaf911fd](https://linux-hardware.org/?probe=2bdaf911fd) | Mar 20, 2024 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [cfcb468980](https://linux-hardware.org/?probe=cfcb468980) | Mar 05, 2024 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [fc18695b87](https://linux-hardware.org/?probe=fc18695b87) | Mar 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5a9461ea0f](https://linux-hardware.org/?probe=5a9461ea0f) | Feb 21, 2024 |
| Dell          | 0YNVJG A02                  | Desktop     | [c979ee9419](https://linux-hardware.org/?probe=c979ee9419) | Feb 11, 2024 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [5e505eb9f1](https://linux-hardware.org/?probe=5e505eb9f1) | Feb 02, 2024 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [97575d7173](https://linux-hardware.org/?probe=97575d7173) | Jan 31, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [f38d7bb62a](https://linux-hardware.org/?probe=f38d7bb62a) | Jan 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6723cbd4cd](https://linux-hardware.org/?probe=6723cbd4cd) | Jan 20, 2024 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [fb81d9ccfe](https://linux-hardware.org/?probe=fb81d9ccfe) | Jan 20, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [9a5efc4dd3](https://linux-hardware.org/?probe=9a5efc4dd3) | Jan 19, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [641df770ba](https://linux-hardware.org/?probe=641df770ba) | Jan 17, 2024 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [b9fe694efb](https://linux-hardware.org/?probe=b9fe694efb) | Jan 12, 2024 |
| Apple         | MacBookAir8,2               | Notebook    | [d9ddd91356](https://linux-hardware.org/?probe=d9ddd91356) | Jan 07, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [54f70ad2a1](https://linux-hardware.org/?probe=54f70ad2a1) | Jan 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [561c912554](https://linux-hardware.org/?probe=561c912554) | Jan 05, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [86bb3586e0](https://linux-hardware.org/?probe=86bb3586e0) | Jan 04, 2024 |
| HP            | 83E1                        | Desktop     | [9006156354](https://linux-hardware.org/?probe=9006156354) | Jan 04, 2024 |
| HP            | 8767 A                      | Desktop     | [6d2a367189](https://linux-hardware.org/?probe=6d2a367189) | Dec 25, 2023 |
| Lenovo        | ThinkPad E570 20H50048US    | Notebook    | [70b5d1cb69](https://linux-hardware.org/?probe=70b5d1cb69) | Dec 05, 2023 |
| ASUSTek       | K53E                        | Notebook    | [4b184d1d81](https://linux-hardware.org/?probe=4b184d1d81) | Dec 02, 2023 |
| Dell          | Latitude 7290               | Notebook    | [c9068c7692](https://linux-hardware.org/?probe=c9068c7692) | Nov 30, 2023 |
| Dell          | Latitude 7290               | Notebook    | [c75434aea3](https://linux-hardware.org/?probe=c75434aea3) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [49fad3d40c](https://linux-hardware.org/?probe=49fad3d40c) | Nov 28, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7fce567d9e](https://linux-hardware.org/?probe=7fce567d9e) | Nov 25, 2023 |
| Lenovo        | ThinkPad T510 4314RBS       | Notebook    | [883b10d260](https://linux-hardware.org/?probe=883b10d260) | Nov 19, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [f2123bd01c](https://linux-hardware.org/?probe=f2123bd01c) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3d00034c4e](https://linux-hardware.org/?probe=3d00034c4e) | Nov 01, 2023 |
| Lenovo        | ThinkPad E560 20EV002JUS    | Notebook    | [07a3c8eea8](https://linux-hardware.org/?probe=07a3c8eea8) | Oct 28, 2023 |
| Lenovo        | ThinkPad E560 20EV002JUS    | Notebook    | [906ed51ecf](https://linux-hardware.org/?probe=906ed51ecf) | Oct 27, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [63107ac52c](https://linux-hardware.org/?probe=63107ac52c) | Oct 23, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b9698d48be](https://linux-hardware.org/?probe=b9698d48be) | Oct 22, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [809ff050d7](https://linux-hardware.org/?probe=809ff050d7) | Oct 13, 2023 |
| Dell          | Inspiron 11-3168            | Notebook    | [538c1421e9](https://linux-hardware.org/?probe=538c1421e9) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f56c04f3e2](https://linux-hardware.org/?probe=f56c04f3e2) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0e27147016](https://linux-hardware.org/?probe=0e27147016) | Oct 09, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [2ee56e1ee0](https://linux-hardware.org/?probe=2ee56e1ee0) | Oct 07, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7fb0e4c19c](https://linux-hardware.org/?probe=7fb0e4c19c) | Sep 28, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [1308430981](https://linux-hardware.org/?probe=1308430981) | Sep 28, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [31a635bff8](https://linux-hardware.org/?probe=31a635bff8) | Sep 24, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a2a2bc81e9](https://linux-hardware.org/?probe=a2a2bc81e9) | Sep 20, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [932df74a39](https://linux-hardware.org/?probe=932df74a39) | Sep 17, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [8db6f2c947](https://linux-hardware.org/?probe=8db6f2c947) | Sep 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [06f7e4ef1b](https://linux-hardware.org/?probe=06f7e4ef1b) | Sep 13, 2023 |
| Gigabyte      | MKLP3AP-00                  | Mini pc     | [ca3874e5b8](https://linux-hardware.org/?probe=ca3874e5b8) | Sep 13, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [eae373ebd4](https://linux-hardware.org/?probe=eae373ebd4) | Sep 07, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [c9431922ba](https://linux-hardware.org/?probe=c9431922ba) | Sep 01, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [53bcd4ec72](https://linux-hardware.org/?probe=53bcd4ec72) | Aug 31, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [f120556c56](https://linux-hardware.org/?probe=f120556c56) | Aug 30, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [aac7eeec4e](https://linux-hardware.org/?probe=aac7eeec4e) | Aug 30, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [4f3d3f12a4](https://linux-hardware.org/?probe=4f3d3f12a4) | Aug 30, 2023 |
| Gateway       | RS780                       | Desktop     | [d73767c9f7](https://linux-hardware.org/?probe=d73767c9f7) | Aug 21, 2023 |
| Dell          | Latitude 7290               | Notebook    | [eb12e0d829](https://linux-hardware.org/?probe=eb12e0d829) | Aug 17, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [df5fa32e56](https://linux-hardware.org/?probe=df5fa32e56) | Jul 25, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [9b0de4f244](https://linux-hardware.org/?probe=9b0de4f244) | Jul 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b52a9ea310](https://linux-hardware.org/?probe=b52a9ea310) | Jul 08, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [c9a8bc63d4](https://linux-hardware.org/?probe=c9a8bc63d4) | Jun 27, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [4428a36327](https://linux-hardware.org/?probe=4428a36327) | Jun 27, 2023 |
| Gateway       | H61H2-AD V1.0               | Desktop     | [9a34a9295c](https://linux-hardware.org/?probe=9a34a9295c) | Jun 15, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [58b9a1f862](https://linux-hardware.org/?probe=58b9a1f862) | Jun 13, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [318f1f4d2a](https://linux-hardware.org/?probe=318f1f4d2a) | Jun 12, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [0afa6e53d0](https://linux-hardware.org/?probe=0afa6e53d0) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ea06bd5806](https://linux-hardware.org/?probe=ea06bd5806) | May 29, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [2d42a4443c](https://linux-hardware.org/?probe=2d42a4443c) | May 23, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [b6336515aa](https://linux-hardware.org/?probe=b6336515aa) | May 19, 2023 |
| Gateway       | RS780                       | Desktop     | [e04207a390](https://linux-hardware.org/?probe=e04207a390) | May 07, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3a89155791](https://linux-hardware.org/?probe=3a89155791) | May 03, 2023 |
| Sony          | SVE11113FXW                 | Notebook    | [248c7717a4](https://linux-hardware.org/?probe=248c7717a4) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [940cbb6ef0](https://linux-hardware.org/?probe=940cbb6ef0) | Apr 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [21111146cd](https://linux-hardware.org/?probe=21111146cd) | Apr 21, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [eaade18ae0](https://linux-hardware.org/?probe=eaade18ae0) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [da0c8e23ed](https://linux-hardware.org/?probe=da0c8e23ed) | Apr 13, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [83132b245e](https://linux-hardware.org/?probe=83132b245e) | Apr 05, 2023 |
| ECS           | Iris8                       | Desktop     | [f86927f9ff](https://linux-hardware.org/?probe=f86927f9ff) | Apr 04, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [3c3a2da37a](https://linux-hardware.org/?probe=3c3a2da37a) | Apr 02, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [9aba047596](https://linux-hardware.org/?probe=9aba047596) | Mar 30, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [5cf96e41e0](https://linux-hardware.org/?probe=5cf96e41e0) | Mar 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [4606b5b93d](https://linux-hardware.org/?probe=4606b5b93d) | Mar 29, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [3f3967267f](https://linux-hardware.org/?probe=3f3967267f) | Mar 26, 2023 |
| HP            | 83E1                        | Desktop     | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| HP            | 83E1                        | Desktop     | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [40bda215a2](https://linux-hardware.org/?probe=40bda215a2) | Mar 11, 2023 |
| HP            | 83E1                        | Desktop     | [86061f121d](https://linux-hardware.org/?probe=86061f121d) | Mar 08, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [5afd8e3f42](https://linux-hardware.org/?probe=5afd8e3f42) | Mar 04, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [be9b47dc08](https://linux-hardware.org/?probe=be9b47dc08) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [3c378a3736](https://linux-hardware.org/?probe=3c378a3736) | Mar 02, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [e189c60b09](https://linux-hardware.org/?probe=e189c60b09) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3883ba28c7](https://linux-hardware.org/?probe=3883ba28c7) | Mar 01, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [5beb40c486](https://linux-hardware.org/?probe=5beb40c486) | Feb 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [593206879a](https://linux-hardware.org/?probe=593206879a) | Feb 02, 2023 |
| Dell          | Latitude E6420              | Notebook    | [68908b991a](https://linux-hardware.org/?probe=68908b991a) | Jan 30, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| Dell          | Latitude E6420              | Notebook    | [ea94fc4f3b](https://linux-hardware.org/?probe=ea94fc4f3b) | Jan 13, 2023 |
| HP            | 89B5 A                      | Desktop     | [4fcef21d82](https://linux-hardware.org/?probe=4fcef21d82) | Jan 07, 2023 |
| HP            | 2000                        | Notebook    | [0f801f2309](https://linux-hardware.org/?probe=0f801f2309) | Jan 07, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [0708d07cd4](https://linux-hardware.org/?probe=0708d07cd4) | Dec 28, 2022 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [b26dc749a5](https://linux-hardware.org/?probe=b26dc749a5) | Dec 23, 2022 |
| Dell          | Latitude E6420              | Notebook    | [7d592f1759](https://linux-hardware.org/?probe=7d592f1759) | Dec 20, 2022 |
| MSI           | MS-AE031                    | All in one  | [7047861d13](https://linux-hardware.org/?probe=7047861d13) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0c94171d5b](https://linux-hardware.org/?probe=0c94171d5b) | Dec 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3d516c4ca3](https://linux-hardware.org/?probe=3d516c4ca3) | Dec 06, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [267ffa24d1](https://linux-hardware.org/?probe=267ffa24d1) | Dec 04, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [7145280e9e](https://linux-hardware.org/?probe=7145280e9e) | Dec 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [251fb963fe](https://linux-hardware.org/?probe=251fb963fe) | Nov 28, 2022 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [fe69e51efe](https://linux-hardware.org/?probe=fe69e51efe) | Nov 03, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [9e63ba2bf9](https://linux-hardware.org/?probe=9e63ba2bf9) | Oct 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5dbeb45ba5](https://linux-hardware.org/?probe=5dbeb45ba5) | Oct 06, 2022 |
| ASRock        | X570 Phantom Gaming 4S      | Desktop     | [2215129a47](https://linux-hardware.org/?probe=2215129a47) | Oct 02, 2022 |
| Dell          | G5 5505                     | Notebook    | [e26e58afac](https://linux-hardware.org/?probe=e26e58afac) | Sep 08, 2022 |
| Intel         | SKYBAY                      | Desktop     | [b667cf66e8](https://linux-hardware.org/?probe=b667cf66e8) | Sep 07, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [1c9628e804](https://linux-hardware.org/?probe=1c9628e804) | Aug 15, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [12a6ae992a](https://linux-hardware.org/?probe=12a6ae992a) | Aug 14, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [846e1d6c9f](https://linux-hardware.org/?probe=846e1d6c9f) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 20RA004WUS     | Notebook    | [b140ac0aea](https://linux-hardware.org/?probe=b140ac0aea) | Aug 07, 2022 |
| Dell          | Precision M4700             | Notebook    | [25efd53898](https://linux-hardware.org/?probe=25efd53898) | Aug 05, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [96645b0a94](https://linux-hardware.org/?probe=96645b0a94) | Aug 04, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [3f1e6ca5cb](https://linux-hardware.org/?probe=3f1e6ca5cb) | Jul 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [012b0c7fa9](https://linux-hardware.org/?probe=012b0c7fa9) | Jul 23, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [9122678102](https://linux-hardware.org/?probe=9122678102) | Jul 21, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [e45f2cd5d8](https://linux-hardware.org/?probe=e45f2cd5d8) | Jul 20, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [69d676f7be](https://linux-hardware.org/?probe=69d676f7be) | Jul 12, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [9d8195a435](https://linux-hardware.org/?probe=9d8195a435) | Jul 12, 2022 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [a42903b516](https://linux-hardware.org/?probe=a42903b516) | Jul 10, 2022 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [404e81318c](https://linux-hardware.org/?probe=404e81318c) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d0cfec8d80](https://linux-hardware.org/?probe=d0cfec8d80) | Jul 04, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [9b53e39bad](https://linux-hardware.org/?probe=9b53e39bad) | Jul 04, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [ac53d2f956](https://linux-hardware.org/?probe=ac53d2f956) | Jul 02, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9fd7dc8784](https://linux-hardware.org/?probe=9fd7dc8784) | Jul 02, 2022 |
| MSI           | MS-AE031                    | All in one  | [d6f4214361](https://linux-hardware.org/?probe=d6f4214361) | Jun 30, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [3193cbe3fd](https://linux-hardware.org/?probe=3193cbe3fd) | Jun 20, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [9eaa432fcd](https://linux-hardware.org/?probe=9eaa432fcd) | Jun 02, 2022 |
| Dell          | 0F2A30 A00                  | All in one  | [ae5664a81f](https://linux-hardware.org/?probe=ae5664a81f) | May 12, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [83ed9adfc1](https://linux-hardware.org/?probe=83ed9adfc1) | May 04, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [860d883e5b](https://linux-hardware.org/?probe=860d883e5b) | Apr 29, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [bce1bba9ff](https://linux-hardware.org/?probe=bce1bba9ff) | Apr 29, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [32cc2a24ac](https://linux-hardware.org/?probe=32cc2a24ac) | Apr 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [074f1f75dc](https://linux-hardware.org/?probe=074f1f75dc) | Apr 20, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b4ea114ce4](https://linux-hardware.org/?probe=b4ea114ce4) | Apr 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [656e8c50dd](https://linux-hardware.org/?probe=656e8c50dd) | Apr 13, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [c32c875fc6](https://linux-hardware.org/?probe=c32c875fc6) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2315db07e2](https://linux-hardware.org/?probe=2315db07e2) | Apr 02, 2022 |
| Dell          | Latitude E6330              | Notebook    | [1911200c56](https://linux-hardware.org/?probe=1911200c56) | Mar 23, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [fd3185704d](https://linux-hardware.org/?probe=fd3185704d) | Mar 21, 2022 |
| HP            | 0AA8h                       | Desktop     | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| Dell          | Inspiron 17-7778            | Notebook    | [bcc52b2596](https://linux-hardware.org/?probe=bcc52b2596) | Mar 17, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| Dell          | 0F2A30 A00                  | All in one  | [f96e26bb9a](https://linux-hardware.org/?probe=f96e26bb9a) | Mar 08, 2022 |
| Dell          | OptiPlex 7020               | Desktop     | [ba82f9d852](https://linux-hardware.org/?probe=ba82f9d852) | Mar 01, 2022 |
| HP            | 0AA8h                       | Desktop     | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a1ecd8a3cb](https://linux-hardware.org/?probe=a1ecd8a3cb) | Feb 12, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [832b48c46d](https://linux-hardware.org/?probe=832b48c46d) | Feb 11, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [e7ce3f2f38](https://linux-hardware.org/?probe=e7ce3f2f38) | Feb 09, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [86dbaf1d07](https://linux-hardware.org/?probe=86dbaf1d07) | Jan 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [51e8a3a34d](https://linux-hardware.org/?probe=51e8a3a34d) | Dec 31, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [1b74edca8c](https://linux-hardware.org/?probe=1b74edca8c) | Dec 27, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [9f1e770843](https://linux-hardware.org/?probe=9f1e770843) | Dec 22, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [464d10c41d](https://linux-hardware.org/?probe=464d10c41d) | Dec 22, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [7143ced3cd](https://linux-hardware.org/?probe=7143ced3cd) | Dec 20, 2021 |
| Dell          | 0R6JMP A00                  | Desktop     | [7bc4106877](https://linux-hardware.org/?probe=7bc4106877) | Dec 12, 2021 |
| Dell          | 0R6JMP A00                  | Desktop     | [2b3e03c89b](https://linux-hardware.org/?probe=2b3e03c89b) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [7bf355c3c1](https://linux-hardware.org/?probe=7bf355c3c1) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [cfa6005bc4](https://linux-hardware.org/?probe=cfa6005bc4) | Dec 09, 2021 |
| HP            | 1998                        | Desktop     | [7bc6ddebf4](https://linux-hardware.org/?probe=7bc6ddebf4) | Nov 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9af646fd14](https://linux-hardware.org/?probe=9af646fd14) | Nov 10, 2021 |
| ASRock        | Q1900M                      | Desktop     | [8482ae3a2f](https://linux-hardware.org/?probe=8482ae3a2f) | Nov 09, 2021 |
| HP            | 339A                        | Desktop     | [e2ce00d1ec](https://linux-hardware.org/?probe=e2ce00d1ec) | Nov 08, 2021 |
| Alienware     | 07W25T A00                  | Desktop     | [c08c87521f](https://linux-hardware.org/?probe=c08c87521f) | Nov 08, 2021 |
| HP            | ENVY Laptop 17m-bw0xxx      | Notebook    | [9ec292c9d9](https://linux-hardware.org/?probe=9ec292c9d9) | Oct 25, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [8649bba9b6](https://linux-hardware.org/?probe=8649bba9b6) | Oct 22, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [fede248f75](https://linux-hardware.org/?probe=fede248f75) | Oct 19, 2021 |
| HP            | ProBook 6450b               | Notebook    | [518e694864](https://linux-hardware.org/?probe=518e694864) | Oct 19, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [29c7fa76a8](https://linux-hardware.org/?probe=29c7fa76a8) | Oct 10, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [6818ec3abc](https://linux-hardware.org/?probe=6818ec3abc) | Oct 10, 2021 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [732c00f018](https://linux-hardware.org/?probe=732c00f018) | Oct 06, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [7ecda0a147](https://linux-hardware.org/?probe=7ecda0a147) | Sep 23, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [9ed2b3cf12](https://linux-hardware.org/?probe=9ed2b3cf12) | Sep 21, 2021 |
| GPU Compan... | GWTN156-9                   | Notebook    | [a9ac79c22a](https://linux-hardware.org/?probe=a9ac79c22a) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a96d28c504](https://linux-hardware.org/?probe=a96d28c504) | Sep 16, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [686eb55129](https://linux-hardware.org/?probe=686eb55129) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [d120a0016d](https://linux-hardware.org/?probe=d120a0016d) | Aug 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [9ad69ca6ad](https://linux-hardware.org/?probe=9ad69ca6ad) | Jul 27, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [75fd544183](https://linux-hardware.org/?probe=75fd544183) | Jul 26, 2021 |
| HP            | 1495                        | Desktop     | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a3b055840b](https://linux-hardware.org/?probe=a3b055840b) | Jul 13, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [cbcf0ae65d](https://linux-hardware.org/?probe=cbcf0ae65d) | Jul 07, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [c3b8ac12be](https://linux-hardware.org/?probe=c3b8ac12be) | Jul 07, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3a88077121](https://linux-hardware.org/?probe=3a88077121) | Jul 07, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [17a65dfb0e](https://linux-hardware.org/?probe=17a65dfb0e) | Jul 06, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [5af810dc36](https://linux-hardware.org/?probe=5af810dc36) | Jul 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [675992d5f9](https://linux-hardware.org/?probe=675992d5f9) | Jul 04, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [4782df79ce](https://linux-hardware.org/?probe=4782df79ce) | Jul 02, 2021 |
| HP            | ProBook 6560b               | Notebook    | [806dfcb6f0](https://linux-hardware.org/?probe=806dfcb6f0) | Jul 01, 2021 |
| HP            | ProBook 6450b               | Notebook    | [a8689c5d60](https://linux-hardware.org/?probe=a8689c5d60) | Jun 25, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [fed4ef6298](https://linux-hardware.org/?probe=fed4ef6298) | Jun 23, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [14e1d81078](https://linux-hardware.org/?probe=14e1d81078) | Jun 23, 2021 |
| HP            | ProBook 6450b               | Notebook    | [b4c7a0fd32](https://linux-hardware.org/?probe=b4c7a0fd32) | Jun 21, 2021 |
| Pegatron      | 2ACD                        | Desktop     | [fd757c14ce](https://linux-hardware.org/?probe=fd757c14ce) | Jun 13, 2021 |
| HP            | 1998                        | Desktop     | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [95fdac8e1c](https://linux-hardware.org/?probe=95fdac8e1c) | Jun 08, 2021 |
| HP            | 1998                        | Desktop     | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| HP            | 1998                        | Desktop     | [4c3248677a](https://linux-hardware.org/?probe=4c3248677a) | May 25, 2021 |
| HP            | 1998                        | Desktop     | [9239b61815](https://linux-hardware.org/?probe=9239b61815) | May 25, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [6b2ff5fb12](https://linux-hardware.org/?probe=6b2ff5fb12) | May 25, 2021 |
| HP            | 1998                        | Desktop     | [639725c8af](https://linux-hardware.org/?probe=639725c8af) | May 24, 2021 |
| HP            | ENVY dv7                    | Notebook    | [651a68adc6](https://linux-hardware.org/?probe=651a68adc6) | May 24, 2021 |
| HP            | 339A                        | Desktop     | [ac11f05a1a](https://linux-hardware.org/?probe=ac11f05a1a) | May 21, 2021 |
| Intel         | SKYBAY                      | Desktop     | [9bc7ab87d1](https://linux-hardware.org/?probe=9bc7ab87d1) | May 19, 2021 |
| ASRock        | Q1900M                      | Desktop     | [7c778b5654](https://linux-hardware.org/?probe=7c778b5654) | May 02, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| HP            | 1998                        | Desktop     | [7442c54767](https://linux-hardware.org/?probe=7442c54767) | Apr 29, 2021 |
| HP            | 1998                        | Desktop     | [ec0fdacf3a](https://linux-hardware.org/?probe=ec0fdacf3a) | Apr 12, 2021 |
| HP            | 1998                        | Desktop     | [c395021e6a](https://linux-hardware.org/?probe=c395021e6a) | Apr 12, 2021 |
| Lenovo        | ThinkPad T410 2516ADU       | Notebook    | [5feb962d24](https://linux-hardware.org/?probe=5feb962d24) | Apr 07, 2021 |
| Intel         | SKYBAY                      | Desktop     | [472818e347](https://linux-hardware.org/?probe=472818e347) | Apr 04, 2021 |
| HP            | 1998                        | Desktop     | [f515fbf660](https://linux-hardware.org/?probe=f515fbf660) | Apr 01, 2021 |
| HP            | 1998                        | Desktop     | [3bc0a0dcb6](https://linux-hardware.org/?probe=3bc0a0dcb6) | Mar 20, 2021 |
| HP            | 1998                        | Desktop     | [a10d91fc1b](https://linux-hardware.org/?probe=a10d91fc1b) | Mar 20, 2021 |
| Intel         | SKYBAY                      | Desktop     | [5ab0183bc4](https://linux-hardware.org/?probe=5ab0183bc4) | Mar 18, 2021 |
| Intel         | SKYBAY                      | Desktop     | [ecefc99ed5](https://linux-hardware.org/?probe=ecefc99ed5) | Mar 14, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [332f4238da](https://linux-hardware.org/?probe=332f4238da) | Mar 09, 2021 |
| Acer          | AAHD3.VC                    | Desktop     | [775057eb07](https://linux-hardware.org/?probe=775057eb07) | Feb 20, 2021 |
| Acer          | AAHD3.VC                    | Desktop     | [b11309575f](https://linux-hardware.org/?probe=b11309575f) | Feb 19, 2021 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [48d2054858](https://linux-hardware.org/?probe=48d2054858) | Feb 16, 2021 |
| Dell          | 0DFRFW A00                  | Desktop     | [093c47fb9c](https://linux-hardware.org/?probe=093c47fb9c) | Feb 13, 2021 |
| ASRock        | Q1900M                      | Desktop     | [d4372897b8](https://linux-hardware.org/?probe=d4372897b8) | Feb 13, 2021 |
| MSI           | H81M-P33                    | Desktop     | [190f14bae7](https://linux-hardware.org/?probe=190f14bae7) | Feb 13, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [2140e64244](https://linux-hardware.org/?probe=2140e64244) | Feb 13, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [81a3e9faea](https://linux-hardware.org/?probe=81a3e9faea) | Feb 11, 2021 |
| HP            | 18E4                        | Desktop     | [db6eb1d366](https://linux-hardware.org/?probe=db6eb1d366) | Feb 05, 2021 |
| HP            | 18E4                        | Desktop     | [bad5f5110c](https://linux-hardware.org/?probe=bad5f5110c) | Feb 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [63a2a56eda](https://linux-hardware.org/?probe=63a2a56eda) | Jan 25, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [b2513f813d](https://linux-hardware.org/?probe=b2513f813d) | Jan 16, 2021 |
| ASUSTek       | K53E                        | Notebook    | [0523ff890c](https://linux-hardware.org/?probe=0523ff890c) | Jan 15, 2021 |
| HP            | 18E4                        | Desktop     | [729391b32e](https://linux-hardware.org/?probe=729391b32e) | Jan 08, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [5780c56d1e](https://linux-hardware.org/?probe=5780c56d1e) | Jan 06, 2021 |
| Toshiba       | Satellite C55-C             | Notebook    | [ecaae6f562](https://linux-hardware.org/?probe=ecaae6f562) | Jan 05, 2021 |
| AMI           | Intel                       | Notebook    | [0ea3da73ad](https://linux-hardware.org/?probe=0ea3da73ad) | Jan 04, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| Lenovo        | ThinkCentre M58p 6136A66    | Desktop     | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [5e4b418568](https://linux-hardware.org/?probe=5e4b418568) | Dec 19, 2020 |
| AZW           | GT-R                        | Notebook    | [19b47cf9f6](https://linux-hardware.org/?probe=19b47cf9f6) | Dec 16, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [ba371f8d43](https://linux-hardware.org/?probe=ba371f8d43) | Dec 07, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [646f020b0d](https://linux-hardware.org/?probe=646f020b0d) | Nov 27, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [9464486b83](https://linux-hardware.org/?probe=9464486b83) | Nov 22, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [844bb428a9](https://linux-hardware.org/?probe=844bb428a9) | Nov 22, 2020 |
| MSI           | MS-B1711                    | Desktop     | [8d69ecec16](https://linux-hardware.org/?probe=8d69ecec16) | Nov 17, 2020 |
| MSI           | MS-B1711                    | Desktop     | [958741b7b6](https://linux-hardware.org/?probe=958741b7b6) | Nov 17, 2020 |
| MSI           | MS-B1711                    | Desktop     | [3c327ae485](https://linux-hardware.org/?probe=3c327ae485) | Nov 17, 2020 |
| CompuLab      | fit-PC3                     | Mini pc     | [2e92dc00d4](https://linux-hardware.org/?probe=2e92dc00d4) | Nov 12, 2020 |
| Dell          | Latitude E6410              | Notebook    | [d188c9653d](https://linux-hardware.org/?probe=d188c9653d) | Nov 07, 2020 |
| Dell          | Latitude E6410              | Notebook    | [caf34f9e21](https://linux-hardware.org/?probe=caf34f9e21) | Nov 02, 2020 |
| MSI           | MS-B1711                    | Desktop     | [26c2dcf112](https://linux-hardware.org/?probe=26c2dcf112) | Nov 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [62ebca752a](https://linux-hardware.org/?probe=62ebca752a) | Oct 31, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [362d74125d](https://linux-hardware.org/?probe=362d74125d) | Oct 31, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [f7ec0211fb](https://linux-hardware.org/?probe=f7ec0211fb) | Oct 27, 2020 |
| ASRock        | Q1900M                      | Desktop     | [72cddfd9ae](https://linux-hardware.org/?probe=72cddfd9ae) | Oct 24, 2020 |
| Dell          | 0R6JMP A00                  | Desktop     | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [9d734dee6e](https://linux-hardware.org/?probe=9d734dee6e) | Sep 30, 2020 |
| HP            | ENVY dv7                    | Notebook    | [e5448099f1](https://linux-hardware.org/?probe=e5448099f1) | Sep 27, 2020 |
| HP            | 339A                        | Desktop     | [47db0521b7](https://linux-hardware.org/?probe=47db0521b7) | Sep 23, 2020 |
| HP            | 339A                        | Desktop     | [51cec5b6f8](https://linux-hardware.org/?probe=51cec5b6f8) | Sep 23, 2020 |
| HP            | ENVY dv7                    | Notebook    | [a027a185e5](https://linux-hardware.org/?probe=a027a185e5) | Sep 23, 2020 |
| HP            | ENVY dv7                    | Notebook    | [ff87d18b2b](https://linux-hardware.org/?probe=ff87d18b2b) | Sep 21, 2020 |
| HP            | 339A                        | Desktop     | [37cfc48ef8](https://linux-hardware.org/?probe=37cfc48ef8) | Sep 21, 2020 |
| HP            | 339A                        | Desktop     | [254f23a364](https://linux-hardware.org/?probe=254f23a364) | Sep 21, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| HP            | 18E4                        | Desktop     | [277593bde6](https://linux-hardware.org/?probe=277593bde6) | Aug 07, 2020 |
| Acer          | Swift SF314-51              | Notebook    | [ff4068d40b](https://linux-hardware.org/?probe=ff4068d40b) | Jul 31, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [25ca74bc56](https://linux-hardware.org/?probe=25ca74bc56) | Jul 24, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [478381d890](https://linux-hardware.org/?probe=478381d890) | Jul 12, 2020 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [f9271f6dae](https://linux-hardware.org/?probe=f9271f6dae) | Jul 09, 2020 |
| MSI           | Z370-A PRO                  | Desktop     | [f8629928a6](https://linux-hardware.org/?probe=f8629928a6) | Jun 18, 2020 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9aaeabab3d](https://linux-hardware.org/?probe=9aaeabab3d) | Jun 18, 2020 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [d161c397ca](https://linux-hardware.org/?probe=d161c397ca) | Jun 14, 2020 |
| HP            | ENVY dv7                    | Notebook    | [2ae56a2828](https://linux-hardware.org/?probe=2ae56a2828) | May 24, 2020 |
| HP            | Compaq nc6400 (RB516UT#A... | Notebook    | [f950094ff1](https://linux-hardware.org/?probe=f950094ff1) | May 21, 2020 |
| Sony          | VPCEA36FX                   | Notebook    | [98ba3a8ad5](https://linux-hardware.org/?probe=98ba3a8ad5) | May 17, 2020 |
| Sony          | VPCEA36FX                   | Notebook    | [572157356f](https://linux-hardware.org/?probe=572157356f) | May 13, 2020 |
| HP            | 18E4                        | Desktop     | [1fe1707854](https://linux-hardware.org/?probe=1fe1707854) | May 07, 2020 |
| ASUSTek       | X540SAA                     | Notebook    | [8805cd4168](https://linux-hardware.org/?probe=8805cd4168) | Apr 16, 2020 |
| Dell          | 0M017G A00                  | Desktop     | [e8b9eefb82](https://linux-hardware.org/?probe=e8b9eefb82) | Apr 13, 2020 |
| HP            | ENVY dv7                    | Notebook    | [e2de1ae596](https://linux-hardware.org/?probe=e2de1ae596) | Apr 04, 2020 |
| HP            | ENVY dv7                    | Notebook    | [97ae3dc919](https://linux-hardware.org/?probe=97ae3dc919) | Mar 14, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [44caca0bb1](https://linux-hardware.org/?probe=44caca0bb1) | Mar 12, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [3d3261ccc3](https://linux-hardware.org/?probe=3d3261ccc3) | Mar 09, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [c0f180f342](https://linux-hardware.org/?probe=c0f180f342) | Mar 07, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [4ac0a3b1fe](https://linux-hardware.org/?probe=4ac0a3b1fe) | Mar 06, 2020 |
| ASRock        | G31M-S                      | Desktop     | [a2582aaec1](https://linux-hardware.org/?probe=a2582aaec1) | Mar 06, 2020 |
| ASRock        | G31M-S                      | Desktop     | [a63cd159a1](https://linux-hardware.org/?probe=a63cd159a1) | Mar 06, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [aa32ea3cb7](https://linux-hardware.org/?probe=aa32ea3cb7) | Mar 05, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [efa77a90cb](https://linux-hardware.org/?probe=efa77a90cb) | Mar 01, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [aca2204df4](https://linux-hardware.org/?probe=aca2204df4) | Mar 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [40a8750e54](https://linux-hardware.org/?probe=40a8750e54) | Feb 28, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [399d92cf32](https://linux-hardware.org/?probe=399d92cf32) | Feb 28, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [7c094d733b](https://linux-hardware.org/?probe=7c094d733b) | Feb 28, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [ddebe02bcd](https://linux-hardware.org/?probe=ddebe02bcd) | Feb 28, 2020 |
| HP            | Notebook                    | Notebook    | [80f2a12798](https://linux-hardware.org/?probe=80f2a12798) | Feb 28, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [132413f9bd](https://linux-hardware.org/?probe=132413f9bd) | Feb 21, 2020 |
| HP            | 18E4                        | Desktop     | [ee3dae8f72](https://linux-hardware.org/?probe=ee3dae8f72) | Feb 17, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [fa684e430c](https://linux-hardware.org/?probe=fa684e430c) | Feb 13, 2020 |
| MSI           | B150 PC MATE                | Desktop     | [ed98074061](https://linux-hardware.org/?probe=ed98074061) | Oct 08, 2019 |
| ASRock        | G31M-S                      | Desktop     | [d1f69377d4](https://linux-hardware.org/?probe=d1f69377d4) | Aug 18, 2019 |
| ASRock        | G31M-S                      | Desktop     | [595867810d](https://linux-hardware.org/?probe=595867810d) | Aug 18, 2019 |
| ASRock        | G31M-S                      | Desktop     | [556d0f2ca6](https://linux-hardware.org/?probe=556d0f2ca6) | Jun 06, 2019 |
| ASRock        | 945GCM-S                    | Desktop     | [d4ea4c5cb6](https://linux-hardware.org/?probe=d4ea4c5cb6) | May 04, 2019 |
| HP            | 18E4                        | Desktop     | [36f9656af0](https://linux-hardware.org/?probe=36f9656af0) | Feb 15, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [d24fc7f682](https://linux-hardware.org/?probe=d24fc7f682) | Jan 30, 2019 |
| Toshiba       | Satellite L655              | Notebook    | [525707b787](https://linux-hardware.org/?probe=525707b787) | Jan 21, 2019 |
| Toshiba       | Satellite L655              | Notebook    | [a7616fb055](https://linux-hardware.org/?probe=a7616fb055) | Jan 21, 2019 |
| HP            | 18E4                        | Desktop     | [c6cf9c7817](https://linux-hardware.org/?probe=c6cf9c7817) | Jan 04, 2019 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [85398272dc](https://linux-hardware.org/?probe=85398272dc) | Dec 03, 2018 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [10a5b1559d](https://linux-hardware.org/?probe=10a5b1559d) | Dec 03, 2018 |
| Dell          | Inspiron MP061              | Notebook    | [113fc7a00d](https://linux-hardware.org/?probe=113fc7a00d) | Jul 15, 2018 |
| ASRock        | G31M-S                      | Desktop     | [82229858ec](https://linux-hardware.org/?probe=82229858ec) | Jun 15, 2018 |
| ASRock        | G31M-S                      | Desktop     | [90f397422e](https://linux-hardware.org/?probe=90f397422e) | Jun 15, 2018 |
| ASRock        | 945GCM-S                    | Desktop     | [c7cbed362d](https://linux-hardware.org/?probe=c7cbed362d) | May 27, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 23        | 9.66%   |
| Ubuntu 22.04                 | 19        | 7.98%   |
| Ubuntu 18.04                 | 11        | 4.62%   |
| Fedora 39                    | 7         | 2.94%   |
| OpenMandriva 4.2             | 6         | 2.52%   |
| Arch Rolling                 | 6         | 2.52%   |
| OpenMandriva 4.3             | 5         | 2.1%    |
| Zorin 16                     | 4         | 1.68%   |
| Ubuntu 21.10                 | 4         | 1.68%   |
| Ubuntu 20.10                 | 4         | 1.68%   |
| Pop!_OS 22.04                | 4         | 1.68%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 1.68%   |
| OpenMandriva 24.07           | 4         | 1.68%   |
| OpenMandriva 23.03           | 4         | 1.68%   |
| Manjaro                      | 4         | 1.68%   |
| Fedora 40                    | 4         | 1.68%   |
| ArcoLinux Rolling            | 4         | 1.68%   |
| Zorin 17                     | 3         | 1.26%   |
| Ubuntu 24.04                 | 3         | 1.26%   |
| Linux Mint 20.1              | 3         | 1.26%   |
| Linux Mint 19.3              | 3         | 1.26%   |
| KDE neon 20.04               | 3         | 1.26%   |
| Fedora 38                    | 3         | 1.26%   |
| Fedora 36                    | 3         | 1.26%   |
| BlackPanther 18.1            | 3         | 1.26%   |
| Zorin 15                     | 2         | 0.84%   |
| Xubuntu 20.04                | 2         | 0.84%   |
| Ubuntu Unity 20.04           | 2         | 0.84%   |
| Ubuntu 23.04                 | 2         | 0.84%   |
| Ubuntu 22.10                 | 2         | 0.84%   |
| Ubuntu 19.10                 | 2         | 0.84%   |
| SteamOS 3.5.19               | 2         | 0.84%   |
| ROSA R11                     | 2         | 0.84%   |
| ROSA R10                     | 2         | 0.84%   |
| OpenMandriva 4.90            | 2         | 0.84%   |
| OpenMandriva 23.11           | 2         | 0.84%   |
| OpenMandriva 23.01           | 2         | 0.84%   |
| Lubuntu 20.04                | 2         | 0.84%   |
| LMDE 4                       | 2         | 0.84%   |
| Linux Mint 21                | 2         | 0.84%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 63        | 28.9%   |
| OpenMandriva  | 26        | 11.93%  |
| Fedora        | 19        | 8.72%   |
| Linux Mint    | 15        | 6.88%   |
| Zorin         | 9         | 4.13%   |
| Pop!_OS       | 9         | 4.13%   |
| Arch          | 7         | 3.21%   |
| SteamOS       | 5         | 2.29%   |
| openSUSE      | 5         | 2.29%   |
| Manjaro       | 5         | 2.29%   |
| KDE neon      | 5         | 2.29%   |
| ArcoLinux     | 5         | 2.29%   |
| ROSA          | 4         | 1.83%   |
| Debian        | 4         | 1.83%   |
| Xubuntu       | 3         | 1.38%   |
| LMDE          | 3         | 1.38%   |
| Elementary    | 3         | 1.38%   |
| BlackPanther  | 3         | 1.38%   |
| Ubuntu Unity  | 2         | 0.92%   |
| Ubuntu Budgie | 2         | 0.92%   |
| Parrot        | 2         | 0.92%   |
| Lubuntu       | 2         | 0.92%   |
| Garuda Linux  | 2         | 0.92%   |
| Endless       | 2         | 0.92%   |
| CentOS        | 2         | 0.92%   |
| Xero          | 1         | 0.46%   |
| Ubuntu MATE   | 1         | 0.46%   |
| Peppermint    | 1         | 0.46%   |
| Nobara        | 1         | 0.46%   |
| LinuxFX       | 1         | 0.46%   |
| EndeavourOS   | 1         | 0.46%   |
| Devuan        | 1         | 0.46%   |
| Bazzite       | 1         | 0.46%   |
| Aurora        | 1         | 0.46%   |
| Alpine        | 1         | 0.46%   |
| AlmaLinux     | 1         | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002    | 6         | 2.06%   |
| 5.16.7-desktop-1omv4003     | 5         | 1.72%   |
| 6.2.6-desktop-1omv2390      | 4         | 1.37%   |
| 5.4.0-58-generic            | 4         | 1.37%   |
| 6.9.7-desktop-1omv2490      | 3         | 1.03%   |
| 6.5.0-35-generic            | 3         | 1.03%   |
| 6.2.0-34-generic            | 3         | 1.03%   |
| 6.2.0-32-generic            | 3         | 1.03%   |
| 5.8.0-59-generic            | 3         | 1.03%   |
| 5.11.0-38-generic           | 3         | 1.03%   |
| 4.15.0-43-generic           | 3         | 1.03%   |
| 6.8.0-49-generic            | 2         | 0.69%   |
| 6.8.0-48-generic            | 2         | 0.69%   |
| 6.8.0-45-generic            | 2         | 0.69%   |
| 6.8.0-109049-tuxedo         | 2         | 0.69%   |
| 6.6.2-desktop-1omv2390      | 2         | 0.69%   |
| 6.5.0-41-generic            | 2         | 0.69%   |
| 6.5.0-28-generic            | 2         | 0.69%   |
| 6.5.0-18-generic            | 2         | 0.69%   |
| 6.5.0-14-generic            | 2         | 0.69%   |
| 6.3.6-200.fc38.x86_64       | 2         | 0.69%   |
| 6.2.0-31-generic            | 2         | 0.69%   |
| 6.2.0-26-generic            | 2         | 0.69%   |
| 6.1.52-valve16-1-neptune-61 | 2         | 0.69%   |
| 6.1.1-desktop-1omv2290      | 2         | 0.69%   |
| 5.8.18-1-MANJARO            | 2         | 0.69%   |
| 5.8.0-55-generic            | 2         | 0.69%   |
| 5.8.0-45-generic            | 2         | 0.69%   |
| 5.4.0-73-generic            | 2         | 0.69%   |
| 5.4.0-72-generic            | 2         | 0.69%   |
| 5.4.0-52-generic            | 2         | 0.69%   |
| 5.4.0-48-generic            | 2         | 0.69%   |
| 5.4.0-47-generic            | 2         | 0.69%   |
| 5.4.0-40-generic            | 2         | 0.69%   |
| 5.4.0-109-generic           | 2         | 0.69%   |
| 5.3.0-41-generic            | 2         | 0.69%   |
| 5.3.0-28-generic            | 2         | 0.69%   |
| 5.19.0-42-generic           | 2         | 0.69%   |
| 5.19.0-38-generic           | 2         | 0.69%   |
| 5.18.15-1-default           | 2         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 31        | 12.4%   |
| 5.8.0   | 14        | 5.6%    |
| 5.13.0  | 13        | 5.2%    |
| 5.15.0  | 12        | 4.8%    |
| 6.2.0   | 11        | 4.4%    |
| 6.8.0   | 10        | 4%      |
| 6.5.0   | 10        | 4%      |
| 4.15.0  | 10        | 4%      |
| 5.11.0  | 9         | 3.6%    |
| 5.19.0  | 8         | 3.2%    |
| 5.3.0   | 6         | 2.4%    |
| 5.10.14 | 6         | 2.4%    |
| 6.2.6   | 5         | 2%      |
| 5.16.7  | 5         | 2%      |
| 5.10.0  | 4         | 1.6%    |
| 6.9.7   | 3         | 1.2%    |
| 6.6.2   | 3         | 1.2%    |
| 6.1.52  | 3         | 1.2%    |
| 4.19.0  | 3         | 1.2%    |
| 4.18.0  | 3         | 1.2%    |
| 6.5.9   | 2         | 0.8%    |
| 6.3.6   | 2         | 0.8%    |
| 6.1.1   | 2         | 0.8%    |
| 5.9.16  | 2         | 0.8%    |
| 5.8.18  | 2         | 0.8%    |
| 5.18.15 | 2         | 0.8%    |
| 5.18.12 | 2         | 0.8%    |
| 5.14.0  | 2         | 0.8%    |
| 4.18.16 | 2         | 0.8%    |
| 6.9.12  | 1         | 0.4%    |
| 6.9.11  | 1         | 0.4%    |
| 6.8.7   | 1         | 0.4%    |
| 6.8.6   | 1         | 0.4%    |
| 6.8.5   | 1         | 0.4%    |
| 6.8.4   | 1         | 0.4%    |
| 6.8.11  | 1         | 0.4%    |
| 6.7.9   | 1         | 0.4%    |
| 6.7.4   | 1         | 0.4%    |
| 6.7.11  | 1         | 0.4%    |
| 6.7.1   | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 31        | 12.6%   |
| 6.2     | 20        | 8.13%   |
| 5.8     | 18        | 7.32%   |
| 6.8     | 15        | 6.1%    |
| 5.15    | 15        | 6.1%    |
| 6.5     | 14        | 5.69%   |
| 5.13    | 14        | 5.69%   |
| 5.19    | 10        | 4.07%   |
| 5.11    | 10        | 4.07%   |
| 5.10    | 10        | 4.07%   |
| 4.15    | 10        | 4.07%   |
| 6.6     | 8         | 3.25%   |
| 5.3     | 8         | 3.25%   |
| 6.1     | 7         | 2.85%   |
| 5.18    | 6         | 2.44%   |
| 6.9     | 5         | 2.03%   |
| 6.7     | 5         | 2.03%   |
| 6.4     | 5         | 2.03%   |
| 5.16    | 5         | 2.03%   |
| 4.9     | 4         | 1.63%   |
| 4.18    | 4         | 1.63%   |
| 6.11    | 3         | 1.22%   |
| 6.10    | 3         | 1.22%   |
| 5.9     | 3         | 1.22%   |
| 5.14    | 3         | 1.22%   |
| 4.19    | 3         | 1.22%   |
| 6.3     | 2         | 0.81%   |
| 6.12    | 2         | 0.81%   |
| 5.6     | 1         | 0.41%   |
| 5.17    | 1         | 0.41%   |
| 5.12    | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 188       | 97.92%  |
| i686    | 2         | 1.04%   |
| aarch64 | 2         | 1.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 101       | 46.76%  |
| KDE5          | 46        | 21.3%   |
| X-Cinnamon    | 16        | 7.41%   |
| Unknown       | 11        | 5.09%   |
| XFCE          | 8         | 3.7%    |
| MATE          | 6         | 2.78%   |
| KDE6          | 5         | 2.31%   |
| Pantheon      | 3         | 1.39%   |
| Budgie        | 3         | 1.39%   |
| Unity         | 2         | 0.93%   |
| LXQt          | 2         | 0.93%   |
| LXDE          | 2         | 0.93%   |
| KDE4          | 2         | 0.93%   |
| KDE           | 2         | 0.93%   |
| i3            | 2         | 0.93%   |
| Cinnamon      | 2         | 0.93%   |
| GNOME Classic | 1         | 0.46%   |
| Deepin        | 1         | 0.46%   |
| awesome       | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 143       | 69.76%  |
| Wayland | 60        | 29.27%  |
| Unknown | 2         | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 114       | 54.03%  |
| GDM3    | 36        | 17.06%  |
| SDDM    | 34        | 16.11%  |
| GDM     | 13        | 6.16%   |
| LightDM | 9         | 4.27%   |
| TDM     | 3         | 1.42%   |
| KDM     | 2         | 0.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 169       | 85.79%  |
| Unknown | 12        | 6.09%   |
| es_PR   | 10        | 5.08%   |
| es_ES   | 3         | 1.52%   |
| C       | 3         | 1.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 111       | 55.22%  |
| EFI  | 90        | 44.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 130       | 61.9%   |
| Btrfs   | 31        | 14.76%  |
| Overlay | 25        | 11.9%   |
| Tmpfs   | 14        | 6.67%   |
| Unknown | 5         | 2.38%   |
| Xfs     | 3         | 1.43%   |
| Zfs     | 2         | 0.95%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 124       | 59.62%  |
| GPT     | 66        | 31.73%  |
| MBR     | 18        | 8.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 171       | 83.82%  |
| Yes       | 33        | 16.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 156       | 76.85%  |
| Yes       | 47        | 23.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 38        | 19.79%  |
| Dell                    | 32        | 16.67%  |
| Lenovo                  | 19        | 9.9%    |
| ASUSTek Computer        | 19        | 9.9%    |
| Gigabyte Technology     | 14        | 7.29%   |
| MSI                     | 12        | 6.25%   |
| ASRock                  | 10        | 5.21%   |
| Apple                   | 7         | 3.65%   |
| Acer                    | 5         | 2.6%    |
| Valve                   | 4         | 2.08%   |
| Toshiba                 | 3         | 1.56%   |
| Sony                    | 3         | 1.56%   |
| Intel                   | 3         | 1.56%   |
| Alienware               | 3         | 1.56%   |
| TUXEDO                  | 2         | 1.04%   |
| Raspberry Pi Foundation | 2         | 1.04%   |
| GPU Company             | 2         | 1.04%   |
| Gateway                 | 2         | 1.04%   |
| Pegatron                | 1         | 0.52%   |
| ONE-NETBOOK TECHNOLOGY  | 1         | 0.52%   |
| Microsoft               | 1         | 0.52%   |
| Google                  | 1         | 0.52%   |
| GEEKOM                  | 1         | 0.52%   |
| Framework               | 1         | 0.52%   |
| Foxconn                 | 1         | 0.52%   |
| ECS                     | 1         | 0.52%   |
| CompuLab                | 1         | 0.52%   |
| AZW                     | 1         | 0.52%   |
| AMI                     | 1         | 0.52%   |
| Acidanthera             | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Valve Jupiter                            | 3         | 1.56%   |
| Intel SKYBAY                             | 3         | 1.56%   |
| Dell Vostro 3550                         | 3         | 1.56%   |
| RPi Raspberry Pi                         | 2         | 1.04%   |
| MSI Cubi N 8GL (MS-B171)                 | 2         | 1.04%   |
| HP EliteBook 840 G2                      | 2         | 1.04%   |
| Gigabyte F2A68HM-H                       | 2         | 1.04%   |
| Dell Inspiron 11-3168                    | 2         | 1.04%   |
| ASUS X510UAR                             | 2         | 1.04%   |
| ASUS K53E                                | 2         | 1.04%   |
| ASRock Q1900M                            | 2         | 1.04%   |
| ASRock 945GCM-S                          | 2         | 1.04%   |
| Valve Galileo                            | 1         | 0.52%   |
| TUXEDO Sirius 16 Gen2                    | 1         | 0.52%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.52%   |
| Toshiba Satellite P755                   | 1         | 0.52%   |
| Toshiba Satellite L655                   | 1         | 0.52%   |
| Toshiba Satellite C55-C                  | 1         | 0.52%   |
| Sony VPCEA36FX                           | 1         | 0.52%   |
| Sony VGN-CS320J                          | 1         | 0.52%   |
| Sony SVE11113FXW                         | 1         | 0.52%   |
| Pegatron QW716AA#ABA                     | 1         | 0.52%   |
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER       | 1         | 0.52%   |
| MSI US PIO PRO AP241                     | 1         | 0.52%   |
| MSI MS-7D75                              | 1         | 0.52%   |
| MSI MS-7D07                              | 1         | 0.52%   |
| MSI MS-7C56                              | 1         | 0.52%   |
| MSI MS-7B48                              | 1         | 0.52%   |
| MSI MS-7A40                              | 1         | 0.52%   |
| MSI MS-7971                              | 1         | 0.52%   |
| MSI MS-7817                              | 1         | 0.52%   |
| MSI GF65 Thin 10SDR                      | 1         | 0.52%   |
| MSI Cubi N JSL (MS-B0A1)                 | 1         | 0.52%   |
| Microsoft Surface Pro 3                  | 1         | 0.52%   |
| Lenovo Yoga 910-13IKB 80VF               | 1         | 0.52%   |
| Lenovo Yoga 900-13ISK 80MK               | 1         | 0.52%   |
| Lenovo Y70-70 Touch 80DU                 | 1         | 0.52%   |
| Lenovo Y50-70 Touch 20349                | 1         | 0.52%   |
| Lenovo V14-ARE 82DQ                      | 1         | 0.52%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0000US | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 9         | 4.69%   |
| Lenovo ThinkPad      | 8         | 4.17%   |
| HP Pavilion          | 7         | 3.65%   |
| HP Laptop            | 7         | 3.65%   |
| Dell OptiPlex        | 7         | 3.65%   |
| Dell Latitude        | 7         | 3.65%   |
| HP Compaq            | 5         | 2.6%    |
| ASUS ROG             | 5         | 2.6%    |
| HP ENVY              | 4         | 2.08%   |
| HP EliteBook         | 4         | 2.08%   |
| Valve Jupiter        | 3         | 1.56%   |
| Toshiba Satellite    | 3         | 1.56%   |
| MSI Cubi             | 3         | 1.56%   |
| Intel SKYBAY         | 3         | 1.56%   |
| HP ProBook           | 3         | 1.56%   |
| HP EliteDesk         | 3         | 1.56%   |
| Dell Vostro          | 3         | 1.56%   |
| Acer Aspire          | 3         | 1.56%   |
| RPi Raspberry        | 2         | 1.04%   |
| Lenovo Yoga          | 2         | 1.04%   |
| Lenovo ThinkCentre   | 2         | 1.04%   |
| Gigabyte X570        | 2         | 1.04%   |
| Gigabyte F2A68HM-H   | 2         | 1.04%   |
| Dell XPS             | 2         | 1.04%   |
| ASUS X510UAR         | 2         | 1.04%   |
| ASUS VivoBook        | 2         | 1.04%   |
| ASUS TUF             | 2         | 1.04%   |
| ASUS PRIME           | 2         | 1.04%   |
| ASUS K53E            | 2         | 1.04%   |
| ASRock Q1900M        | 2         | 1.04%   |
| ASRock B450M-HDV     | 2         | 1.04%   |
| ASRock 945GCM-S      | 2         | 1.04%   |
| Acer Swift           | 2         | 1.04%   |
| Valve Galileo        | 1         | 0.52%   |
| TUXEDO Sirius        | 1         | 0.52%   |
| TUXEDO Aura          | 1         | 0.52%   |
| Sony VPCEA36FX       | 1         | 0.52%   |
| Sony VGN-CS320J      | 1         | 0.52%   |
| Sony SVE11113FXW     | 1         | 0.52%   |
| Pegatron QW716AA#ABA | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 26        | 13.54%  |
| 2019    | 20        | 10.42%  |
| 2020    | 19        | 9.9%    |
| 2011    | 16        | 8.33%   |
| 2015    | 13        | 6.77%   |
| 2014    | 13        | 6.77%   |
| 2021    | 10        | 5.21%   |
| 2017    | 10        | 5.21%   |
| 2016    | 10        | 5.21%   |
| 2012    | 10        | 5.21%   |
| 2013    | 8         | 4.17%   |
| 2008    | 8         | 4.17%   |
| 2009    | 6         | 3.13%   |
| 2023    | 5         | 2.6%    |
| 2022    | 5         | 2.6%    |
| 2010    | 5         | 2.6%    |
| 2024    | 2         | 1.04%   |
| 2006    | 2         | 1.04%   |
| Unknown | 2         | 1.04%   |
| 2007    | 1         | 0.52%   |
| 2005    | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 106       | 55.21%  |
| Desktop        | 73        | 38.02%  |
| All in one     | 4         | 2.08%   |
| Convertible    | 3         | 1.56%   |
| System on chip | 2         | 1.04%   |
| Mini pc        | 2         | 1.04%   |
| Tablet         | 1         | 0.52%   |
| Server         | 1         | 0.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 181       | 93.3%   |
| Enabled  | 13        | 6.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 191       | 99.48%  |
| Yes  | 1         | 0.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 62        | 30.24%  |
| 8.01-16.0   | 40        | 19.51%  |
| 16.01-24.0  | 39        | 19.02%  |
| 3.01-4.0    | 33        | 16.1%   |
| 32.01-64.0  | 12        | 5.85%   |
| 24.01-32.0  | 7         | 3.41%   |
| 1.01-2.0    | 6         | 2.93%   |
| 64.01-256.0 | 5         | 2.44%   |
| 0.51-1.0    | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 92        | 39.48%  |
| 2.01-3.0  | 51        | 21.89%  |
| 3.01-4.0  | 40        | 17.17%  |
| 4.01-8.0  | 33        | 14.16%  |
| 0.51-1.0  | 12        | 5.15%   |
| 8.01-16.0 | 5         | 2.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 120       | 59.11%  |
| 2      | 51        | 25.12%  |
| 3      | 21        | 10.34%  |
| 4      | 6         | 2.96%   |
| 5      | 2         | 0.99%   |
| 0      | 2         | 0.99%   |
| 6      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 61.14%  |
| Yes       | 75        | 38.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 82.81%  |
| No        | 33        | 17.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 82.47%  |
| No        | 34        | 17.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 64.97%  |
| No        | 69        | 35.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Puerto Rico | 192       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San Juan      | 89        | 41.59%  |
| Bayamón      | 27        | 12.62%  |
| Ponce         | 10        | 4.67%   |
| Carolina      | 10        | 4.67%   |
| Rio Grande    | 7         | 3.27%   |
| Caguas        | 6         | 2.8%    |
| San Sebastian | 5         | 2.34%   |
| Toa Baja      | 4         | 1.87%   |
| Cayey         | 4         | 1.87%   |
| Aguadilla     | 4         | 1.87%   |
| Vega Alta     | 3         | 1.4%    |
| Utuado        | 3         | 1.4%    |
| Lares         | 3         | 1.4%    |
| Santa Isabel  | 2         | 0.93%   |
| Sabana Grande | 2         | 0.93%   |
| Mayagüez     | 2         | 0.93%   |
| Manati        | 2         | 0.93%   |
| Guaynabo      | 2         | 0.93%   |
| Guayama       | 2         | 0.93%   |
| Dorado        | 2         | 0.93%   |
| Cataño       | 2         | 0.93%   |
| Cabo Rojo     | 2         | 0.93%   |
| Arecibo       | 2         | 0.93%   |
| Yauco         | 1         | 0.47%   |
| Villalba      | 1         | 0.47%   |
| Vega Baja     | 1         | 0.47%   |
| Trujillo Alto | 1         | 0.47%   |
| Patillas      | 1         | 0.47%   |
| Morovis       | 1         | 0.47%   |
| Maunabo       | 1         | 0.47%   |
| Las Piedras   | 1         | 0.47%   |
| Humacao       | 1         | 0.47%   |
| Hatillo       | 1         | 0.47%   |
| Gurabo        | 1         | 0.47%   |
| Garrochales   | 1         | 0.47%   |
| Fajardo       | 1         | 0.47%   |
| Ensenada      | 1         | 0.47%   |
| Corozal       | 1         | 0.47%   |
| Coamo         | 1         | 0.47%   |
| Cidra         | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 48        | 90     | 16.72%  |
| Samsung Electronics         | 31        | 48     | 10.8%   |
| Seagate                     | 28        | 49     | 9.76%   |
| Toshiba                     | 23        | 29     | 8.01%   |
| Sandisk                     | 19        | 26     | 6.62%   |
| Unknown                     | 15        | 22     | 5.23%   |
| Hitachi                     | 13        | 35     | 4.53%   |
| Crucial                     | 13        | 29     | 4.53%   |
| SK hynix                    | 9         | 11     | 3.14%   |
| Kingston                    | 9         | 11     | 3.14%   |
| A-DATA Technology           | 7         | 14     | 2.44%   |
| China                       | 6         | 10     | 2.09%   |
| Micron/Crucial Technology   | 5         | 9      | 1.74%   |
| Intel                       | 5         | 6      | 1.74%   |
| SPCC                        | 4         | 7      | 1.39%   |
| Silicon Motion              | 4         | 4      | 1.39%   |
| Micron Technology           | 4         | 14     | 1.39%   |
| External                    | 4         | 13     | 1.39%   |
| TDAS                        | 3         | 17     | 1.05%   |
| PNY                         | 3         | 4      | 1.05%   |
| Patriot                     | 3         | 7      | 1.05%   |
| SABRENT                     | 2         | 3      | 0.7%    |
| Phison                      | 2         | 2      | 0.7%    |
| LITEONIT                    | 2         | 2      | 0.7%    |
| Axiom                       | 2         | 10     | 0.7%    |
| Apple                       | 2         | 3      | 0.7%    |
| WD MediaMax                 | 1         | 3      | 0.35%   |
| W800SH                      | 1         | 1      | 0.35%   |
| USB3.0                      | 1         | 1      | 0.35%   |
| Team                        | 1         | 1      | 0.35%   |
| Realtek Semiconductor       | 1         | 1      | 0.35%   |
| Phison Electronics          | 1         | 1      | 0.35%   |
| OCZ                         | 1         | 1      | 0.35%   |
| Mushkin                     | 1         | 1      | 0.35%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.35%   |
| MaxDigital                  | 1         | 1      | 0.35%   |
| Lexar                       | 1         | 4      | 0.35%   |
| Kingston Technology Company | 1         | 1      | 0.35%   |
| KingSpec                    | 1         | 1      | 0.35%   |
| JMicron Technology          | 1         | 4      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB                         | 5         | 1.62%   |
| Toshiba MQ01ABD100 1TB                               | 4         | 1.29%   |
| Toshiba DT01ACA100 1TB                               | 4         | 1.29%   |
| External USB3.0 1TB                                  | 4         | 1.29%   |
| Crucial CT240M500SSD1 240GB                          | 4         | 1.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 3         | 0.97%   |
| WDC WD5000LPVT-22G33T0 500GB                         | 3         | 0.97%   |
| Unknown MMC Card  128GB                              | 3         | 0.97%   |
| Toshiba MQ04ABF100 1TB                               | 3         | 0.97%   |
| TDAS TerraMaster 4TB                                 | 3         | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3         | 0.97%   |
| Kingston SKC6001024G 1024GB SSD                      | 3         | 0.97%   |
| Hitachi HTS547550A9E384 500GB                        | 3         | 0.97%   |
| WDC WDS250G2B0B 250GB SSD                            | 2         | 0.65%   |
| WDC WDBNCE2500PNC 250GB SSD                          | 2         | 0.65%   |
| WDC WDBNCE0010PNC 1TB SSD                            | 2         | 0.65%   |
| WDC WD5000LPLX-22ZNTT0 500GB                         | 2         | 0.65%   |
| WDC WD40EZRZ-22GXCB0 4TB                             | 2         | 0.65%   |
| WDC WD2500BEVS-60UST0 250GB                          | 2         | 0.65%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 2         | 0.65%   |
| Unknown MMC Card  2GB                                | 2         | 0.65%   |
| Toshiba MQ01ABF050 500GB                             | 2         | 0.65%   |
| Toshiba MK3261GSYN 320GB                             | 2         | 0.65%   |
| Toshiba DT01ACA050 500GB                             | 2         | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 2         | 0.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 2         | 0.65%   |
| Seagate ST3250310AS 250GB                            | 2         | 0.65%   |
| Seagate ST320DM001 HD322GJ 320GB                     | 2         | 0.65%   |
| Seagate ST2000VM003-1CT164 2TB                       | 2         | 0.65%   |
| Seagate Expansion 1TB                                | 2         | 0.65%   |
| Sandisk WD_BLACK SN770 1TB                           | 2         | 0.65%   |
| Sandisk WD Blue SN570 500GB                          | 2         | 0.65%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 2         | 0.65%   |
| SanDisk NVMe SSD Drive 1TB                           | 2         | 0.65%   |
| Samsung SSD 860 EVO 500GB                            | 2         | 0.65%   |
| Samsung SSD 850 EVO 500GB                            | 2         | 0.65%   |
| Samsung NVMe SSD Drive 500GB                         | 2         | 0.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 2         | 0.65%   |
| Samsung MZVL4256HBJD-00BL7 256GB                     | 2         | 0.65%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD                 | 2         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 73     | 31.25%  |
| Seagate             | 28        | 49     | 25%     |
| Toshiba             | 22        | 28     | 19.64%  |
| Hitachi             | 13        | 35     | 11.61%  |
| External            | 4         | 13     | 3.57%   |
| TDAS                | 3         | 17     | 2.68%   |
| Samsung Electronics | 2         | 3      | 1.79%   |
| SABRENT             | 2         | 3      | 1.79%   |
| MaxDigital          | 1         | 1      | 0.89%   |
| HGST                | 1         | 1      | 0.89%   |
| Apple               | 1         | 1      | 0.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 20     | 16.87%  |
| Crucial             | 12        | 28     | 14.46%  |
| WDC                 | 10        | 13     | 12.05%  |
| Kingston            | 8         | 10     | 9.64%   |
| A-DATA Technology   | 7         | 13     | 8.43%   |
| China               | 6         | 10     | 7.23%   |
| SanDisk             | 5         | 5      | 6.02%   |
| SPCC                | 3         | 6      | 3.61%   |
| PNY                 | 3         | 4      | 3.61%   |
| Patriot             | 3         | 7      | 3.61%   |
| LITEONIT            | 2         | 2      | 2.41%   |
| W800SH              | 1         | 1      | 1.2%    |
| USB3.0              | 1         | 1      | 1.2%    |
| SK hynix            | 1         | 1      | 1.2%    |
| OCZ                 | 1         | 1      | 1.2%    |
| Mushkin             | 1         | 1      | 1.2%    |
| Micron Technology   | 1         | 1      | 1.2%    |
| Lexar               | 1         | 4      | 1.2%    |
| KingSpec            | 1         | 1      | 1.2%    |
| INTEL SS            | 1         | 2      | 1.2%    |
| Argon               | 1         | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 99        | 224    | 38.22%  |
| SSD     | 75        | 132    | 28.96%  |
| NVMe    | 65        | 109    | 25.1%   |
| MMC     | 14        | 20     | 5.41%   |
| Unknown | 6         | 20     | 2.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 148       | 327    | 60.16%  |
| NVMe | 65        | 109    | 26.42%  |
| SAS  | 19        | 49     | 7.72%   |
| MMC  | 14        | 20     | 5.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 96        | 182    | 52.75%  |
| 0.51-1.0   | 59        | 112    | 32.42%  |
| 1.01-2.0   | 18        | 32     | 9.89%   |
| 3.01-4.0   | 7         | 28     | 3.85%   |
| 2.01-3.0   | 1         | 1      | 0.55%   |
| 10.01-20.0 | 1         | 1      | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 55        | 23.21%  |
| 101-250        | 52        | 21.94%  |
| 501-1000       | 38        | 16.03%  |
| 1-20           | 24        | 10.13%  |
| 1001-2000      | 23        | 9.7%    |
| More than 3000 | 14        | 5.91%   |
| 2001-3000      | 14        | 5.91%   |
| 51-100         | 7         | 2.95%   |
| 21-50          | 5         | 2.11%   |
| Unknown        | 5         | 2.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 82        | 33.74%  |
| 21-50          | 43        | 17.7%   |
| 101-250        | 31        | 12.76%  |
| 51-100         | 26        | 10.7%   |
| 251-500        | 22        | 9.05%   |
| 501-1000       | 18        | 7.41%   |
| 1001-2000      | 10        | 4.12%   |
| Unknown        | 5         | 2.06%   |
| More than 3000 | 3         | 1.23%   |
| 2001-3000      | 3         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-60UST0 250GB                      | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 5.56%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB          | 1         | 1      | 5.56%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 5.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 5.56%   |
| Seagate ST3320613AS 320GB                        | 1         | 2      | 5.56%   |
| Seagate ST3250310AS 250GB                        | 1         | 1      | 5.56%   |
| Seagate ST320DM001 HD322GJ 320GB                 | 1         | 1      | 5.56%   |
| Seagate ST2000VM003-1CT164 2TB                   | 1         | 1      | 5.56%   |
| Seagate ST2000LM007-1R8174 2TB                   | 1         | 2      | 5.56%   |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 5.56%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 5.56%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 5.56%   |
| Hitachi HTS545025B9A300 250GB                    | 1         | 1      | 5.56%   |
| Hitachi HTS543232L9A300 320GB                    | 1         | 1      | 5.56%   |
| Crucial CT240M500SSD1 240GB                      | 1         | 1      | 5.56%   |
| A-DATA Technology SU740 500GB SSD                | 1         | 1      | 5.56%   |
| A-DATA Technology SU630 240GB SSD                | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 10     | 37.5%   |
| Hitachi             | 2         | 2      | 12.5%   |
| A-DATA Technology   | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| Toshiba             | 1         | 1      | 6.25%   |
| SK hynix            | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 1      | 6.25%   |
| Crucial             | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 10     | 60%     |
| Hitachi | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |
| Toshiba | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 14     | 62.5%   |
| SSD  | 5         | 5      | 31.25%  |
| NVMe | 1         | 1      | 6.25%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 141       | 400    | 67.46%  |
| Works    | 52        | 85     | 24.88%  |
| Malfunc  | 16        | 20     | 7.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 132       | 55%     |
| AMD                          | 36        | 15%     |
| Samsung Electronics          | 16        | 6.67%   |
| SanDisk                      | 15        | 6.25%   |
| SK hynix                     | 8         | 3.33%   |
| Micron/Crucial Technology    | 6         | 2.5%    |
| Silicon Motion               | 5         | 2.08%   |
| Phison Electronics           | 5         | 2.08%   |
| Nvidia                       | 4         | 1.67%   |
| Micron Technology            | 3         | 1.25%   |
| Kingston Technology Company  | 2         | 0.83%   |
| ASMedia Technology           | 2         | 0.83%   |
| Toshiba America Info Systems | 1         | 0.42%   |
| Realtek Semiconductor        | 1         | 0.42%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.42%   |
| Biwin Storage Technology     | 1         | 0.42%   |
| Apple                        | 1         | 0.42%   |
| ADATA Technology             | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 26        | 9.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 6.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 3.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 3.62%   |
| AMD 400 Series Chipset SATA Controller                                           | 9         | 3.26%   |
| Intel SATA Controller [RAID mode]                                                | 8         | 2.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 2.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 2.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 2.17%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 5         | 1.81%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 5         | 1.81%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 1.81%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 1.45%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 4         | 1.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.45%   |
| Phison E12 NVMe Controller                                                       | 4         | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4         | 1.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 1.45%   |
| AMD FCH IDE Controller                                                           | 4         | 1.45%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 3         | 1.09%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 3         | 1.09%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 3         | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 1.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.09%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.09%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 3         | 1.09%   |
| AMD FCH SATA Controller [IDE mode]                                               | 3         | 1.09%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.72%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.72%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 0.72%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 136       | 55.06%  |
| NVMe | 65        | 26.32%  |
| RAID | 23        | 9.31%   |
| IDE  | 23        | 9.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 143       | 74.48%  |
| AMD    | 47        | 24.48%  |
| ARM    | 2         | 1.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz           | 5         | 2.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 2.08%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 3         | 1.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 3         | 1.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.56%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 3         | 1.56%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3         | 1.56%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 3         | 1.56%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 3         | 1.56%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3         | 1.56%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3         | 1.56%   |
| AMD Custom APU 0405                         | 3         | 1.56%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 2         | 1.04%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 1.04%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 2         | 1.04%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.04%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 2         | 1.04%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 2         | 1.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.04%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 2         | 1.04%   |
| Intel Core i3-4020Y CPU @ 1.50GHz           | 2         | 1.04%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2         | 1.04%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.04%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz        | 2         | 1.04%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.04%   |
| Intel Celeron CPU E1200 @ 1.60GHz           | 2         | 1.04%   |
| Intel 13th Gen Core i9-13900H               | 2         | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.04%   |
| ARM Processor                               | 2         | 1.04%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.04%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 2         | 1.04%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 1.04%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 2         | 1.04%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 0.52%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.52%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.52%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 0.52%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 41        | 21.35%  |
| Intel Core i7           | 28        | 14.58%  |
| Intel Core i3           | 20        | 10.42%  |
| Other                   | 19        | 9.9%    |
| Intel Celeron           | 16        | 8.33%   |
| AMD Ryzen 5             | 13        | 6.77%   |
| Intel Core 2 Duo        | 9         | 4.69%   |
| AMD Ryzen 7             | 8         | 4.17%   |
| Intel Pentium Silver    | 6         | 3.13%   |
| Intel Pentium           | 6         | 3.13%   |
| AMD Ryzen 3             | 4         | 2.08%   |
| AMD A8                  | 4         | 2.08%   |
| AMD A6                  | 3         | 1.56%   |
| Intel Pentium Dual-Core | 2         | 1.04%   |
| Intel Genuine           | 1         | 0.52%   |
| Intel Core 2            | 1         | 0.52%   |
| AMD Ryzen Threadripper  | 1         | 0.52%   |
| AMD Ryzen 9             | 1         | 0.52%   |
| AMD Phenom II X4        | 1         | 0.52%   |
| AMD G                   | 1         | 0.52%   |
| AMD FX                  | 1         | 0.52%   |
| AMD E2                  | 1         | 0.52%   |
| AMD Athlon X4           | 1         | 0.52%   |
| AMD Athlon Dual Core    | 1         | 0.52%   |
| AMD Athlon 64 X2        | 1         | 0.52%   |
| AMD Athlon              | 1         | 0.52%   |
| AMD A10                 | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 84        | 43.52%  |
| 4      | 65        | 33.68%  |
| 6      | 25        | 12.95%  |
| 8      | 10        | 5.18%   |
| 1      | 4         | 2.07%   |
| 14     | 2         | 1.04%   |
| 12     | 2         | 1.04%   |
| 16     | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 192       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 123       | 63.73%  |
| 1      | 70        | 36.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 188       | 97.41%  |
| Unknown        | 4         | 2.07%   |
| 32-bit         | 1         | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 47.62%  |
| 0x206a7    | 12        | 5.71%   |
| 0x306c3    | 8         | 3.81%   |
| 0x806e9    | 5         | 2.38%   |
| 0x306a9    | 5         | 2.38%   |
| 0x706a1    | 4         | 1.9%    |
| 0x30678    | 4         | 1.9%    |
| 0x20655    | 4         | 1.9%    |
| 0x1067a    | 4         | 1.9%    |
| 0xa0671    | 3         | 1.43%   |
| 0x906ea    | 3         | 1.43%   |
| 0x806ec    | 3         | 1.43%   |
| 0x806ea    | 3         | 1.43%   |
| 0x08108109 | 3         | 1.43%   |
| 0x06001119 | 3         | 1.43%   |
| 0x6fd      | 2         | 0.95%   |
| 0x406e3    | 2         | 0.95%   |
| 0x306d4    | 2         | 0.95%   |
| 0x08701021 | 2         | 0.95%   |
| 0x08701013 | 2         | 0.95%   |
| 0x08600106 | 2         | 0.95%   |
| 0x0800820d | 2         | 0.95%   |
| 0x06003106 | 2         | 0.95%   |
| 0xa0652    | 1         | 0.48%   |
| 0x906ed    | 1         | 0.48%   |
| 0x906e9    | 1         | 0.48%   |
| 0x906c0    | 1         | 0.48%   |
| 0x90675    | 1         | 0.48%   |
| 0x806eb    | 1         | 0.48%   |
| 0x806c1    | 1         | 0.48%   |
| 0x706e5    | 1         | 0.48%   |
| 0x6fb      | 1         | 0.48%   |
| 0x6e8      | 1         | 0.48%   |
| 0x506e3    | 1         | 0.48%   |
| 0x506c9    | 1         | 0.48%   |
| 0x406c4    | 1         | 0.48%   |
| 0x406c3    | 1         | 0.48%   |
| 0x40651    | 1         | 0.48%   |
| 0x30679    | 1         | 0.48%   |
| 0x20652    | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 19.27%  |
| SandyBridge      | 16        | 8.33%   |
| Unknown          | 13        | 6.77%   |
| Haswell          | 12        | 6.25%   |
| Zen 2            | 10        | 5.21%   |
| Silvermont       | 10        | 5.21%   |
| Penryn           | 10        | 5.21%   |
| Skylake          | 9         | 4.69%   |
| Zen+             | 8         | 4.17%   |
| IvyBridge        | 8         | 4.17%   |
| Goldmont plus    | 7         | 3.65%   |
| Westmere         | 6         | 3.13%   |
| TigerLake        | 5         | 2.6%    |
| IceLake          | 5         | 2.6%    |
| Zen              | 4         | 2.08%   |
| Steamroller      | 4         | 2.08%   |
| Piledriver       | 4         | 2.08%   |
| Core             | 4         | 2.08%   |
| Broadwell        | 3         | 1.56%   |
| Alderlake Hybrid | 3         | 1.56%   |
| Zen 3            | 2         | 1.04%   |
| K8 Hammer        | 2         | 1.04%   |
| CometLake        | 2         | 1.04%   |
| Bobcat           | 2         | 1.04%   |
| Tremont          | 1         | 0.52%   |
| Puma             | 1         | 0.52%   |
| P6               | 1         | 0.52%   |
| K10 Llano        | 1         | 0.52%   |
| K10              | 1         | 0.52%   |
| Goldmont         | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 129       | 59.72%  |
| AMD    | 49        | 22.69%  |
| Nvidia | 38        | 17.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 6.55%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 3.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 2.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.18%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 5         | 2.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.75%   |
| Intel HD Graphics 620                                                                    | 4         | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.75%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.75%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 1.75%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 4         | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.31%   |
| Intel HD Graphics 610                                                                    | 3         | 1.31%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.31%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 1.31%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 3         | 1.31%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.87%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.87%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 0.87%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 2         | 0.87%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.87%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 2         | 0.87%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 0.87%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.87%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.87%   |
| Intel HD Graphics 630                                                                    | 2         | 0.87%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 2         | 0.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 108       | 55.38%  |
| 1 x AMD            | 38        | 19.49%  |
| 1 x Nvidia         | 19        | 9.74%   |
| Intel + Nvidia     | 14        | 7.18%   |
| Intel + AMD        | 5         | 2.56%   |
| 2 x AMD            | 4         | 2.05%   |
| Other              | 2         | 1.03%   |
| Intel + 2 x Nvidia | 2         | 1.03%   |
| AMD + Nvidia       | 2         | 1.03%   |
| 2 x Nvidia         | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 172       | 86.87%  |
| Proprietary | 17        | 8.59%   |
| Unknown     | 9         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 141       | 69.12%  |
| 0.01-0.5   | 17        | 8.33%   |
| 3.01-4.0   | 11        | 5.39%   |
| 1.01-2.0   | 11        | 5.39%   |
| 0.51-1.0   | 11        | 5.39%   |
| 7.01-8.0   | 4         | 1.96%   |
| 5.01-6.0   | 4         | 1.96%   |
| 8.01-16.0  | 3         | 1.47%   |
| 2.01-3.0   | 2         | 0.98%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 22        | 9.95%   |
| LG Display              | 21        | 9.5%    |
| Goldstar                | 19        | 8.6%    |
| Chimei Innolux          | 18        | 8.14%   |
| BOE                     | 18        | 8.14%   |
| AU Optronics            | 16        | 7.24%   |
| Dell                    | 11        | 4.98%   |
| Hewlett-Packard         | 9         | 4.07%   |
| Acer                    | 9         | 4.07%   |
| Apple                   | 7         | 3.17%   |
| Sony                    | 6         | 2.71%   |
| ViewSonic               | 5         | 2.26%   |
| AOC                     | 5         | 2.26%   |
| Vizio                   | 4         | 1.81%   |
| Valve                   | 4         | 1.81%   |
| Sceptre Tech            | 4         | 1.81%   |
| PANDA                   | 4         | 1.81%   |
| Gateway                 | 3         | 1.36%   |
| Element                 | 3         | 1.36%   |
| ASUSTek Computer        | 3         | 1.36%   |
| VIZ                     | 2         | 0.9%    |
| Unknown                 | 2         | 0.9%    |
| Tech Concepts           | 2         | 0.9%    |
| RTK                     | 2         | 0.9%    |
| Lenovo                  | 2         | 0.9%    |
| eMachines               | 2         | 0.9%    |
| Chi Mei Optoelectronics | 2         | 0.9%    |
| Ancor Communications    | 2         | 0.9%    |
| Unknown (XXX)           | 1         | 0.45%   |
| UGD                     | 1         | 0.45%   |
| Toshiba                 | 1         | 0.45%   |
| Sharp                   | 1         | 0.45%   |
| Seiki                   | 1         | 0.45%   |
| SANSUI                  | 1         | 0.45%   |
| ONN                     | 1         | 0.45%   |
| MTK                     | 1         | 0.45%   |
| MStar                   | 1         | 0.45%   |
| MSI                     | 1         | 0.45%   |
| InnoLux Display         | 1         | 0.45%   |
| Iiyama                  | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 7         | 3.07%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch | 4         | 1.75%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 3         | 1.32%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 3         | 1.32%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch               | 3         | 1.32%   |
| Element ELEFW408 ELE1366 1920x1080 890x500mm 40.2-inch               | 3         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 3         | 1.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 3         | 1.32%   |
| VIZ LCD Monitor M551d-A2R                                            | 2         | 0.88%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch        | 2         | 0.88%   |
| Sony TV SNY4502 1920x1080                                            | 2         | 0.88%   |
| Sony TV *00 SNY4B04 3840x2160                                        | 2         | 0.88%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch    | 2         | 0.88%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch | 2         | 0.88%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch    | 2         | 0.88%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch         | 2         | 0.88%   |
| Hewlett-Packard L2105tm HWP2863 1920x1080 477x268mm 21.5-inch        | 2         | 0.88%   |
| Goldstar ULTRAGEAR GSM5B70 1920x1080 531x298mm 24.0-inch             | 2         | 0.88%   |
| Gateway LCD Monitor FHX2300                                          | 2         | 0.88%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                | 2         | 0.88%   |
| eMachines E19T6W EMA0783 1440x900 410x257mm 19.1-inch                | 2         | 0.88%   |
| Dell DELLSE2216HV DELF072 1920x1080 480x270mm 21.7-inch              | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch      | 2         | 0.88%   |
| ASUSTek Computer VA24D AUS2403 1920x1080 527x296mm 23.8-inch         | 2         | 0.88%   |
| Acer LCD Monitor G236HL 5760x1080                                    | 2         | 0.88%   |
| Vizio M602i-B3 VIZ1006 1920x1080 1333x748mm 60.2-inch                | 1         | 0.44%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                   | 1         | 0.44%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                  | 1         | 0.44%   |
| Vizio D32f-E1 VIZ1027 1920x1080 698x392mm 31.5-inch                  | 1         | 0.44%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch        | 1         | 0.44%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch             | 1         | 0.44%   |
| ViewSonic VA1930wm VSC171F 1440x900 410x260mm 19.1-inch              | 1         | 0.44%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                  | 1         | 0.44%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1         | 0.44%   |
| Unknown LCD Monitor Dell S2719DGF 2560x1440                          | 1         | 0.44%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch       | 1         | 0.44%   |
| UGD Artist 156 UGD1501 1920x1080 344x193mm 15.5-inch                 | 1         | 0.44%   |
| Toshiba TV TSB0212 1920x1080                                         | 1         | 0.44%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                           | 1         | 0.44%   |
| Tech Concepts LCD Monitor 43S423 1920x1080                           | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 90        | 43.69%  |
| 1366x768 (WXGA)    | 44        | 21.36%  |
| 3840x2160 (4K)     | 17        | 8.25%   |
| 2560x1440 (QHD)    | 8         | 3.88%   |
| 1600x900 (HD+)     | 6         | 2.91%   |
| 1440x900 (WXGA+)   | 6         | 2.91%   |
| 1280x800 (WXGA)    | 6         | 2.91%   |
| 800x1280           | 4         | 1.94%   |
| 1280x1024 (SXGA)   | 4         | 1.94%   |
| 3440x1440          | 3         | 1.46%   |
| 2560x1080          | 3         | 1.46%   |
| 5760x1080          | 2         | 0.97%   |
| Unknown            | 2         | 0.97%   |
| 3840x1080          | 1         | 0.49%   |
| 3200x1800 (QHD+)   | 1         | 0.49%   |
| 2560x1600          | 1         | 0.49%   |
| 2288x1287          | 1         | 0.49%   |
| 2256x1504          | 1         | 0.49%   |
| 2160x1440          | 1         | 0.49%   |
| 1920x1200 (WUXGA)  | 1         | 0.49%   |
| 1680x1050 (WSXGA+) | 1         | 0.49%   |
| 1600x2560          | 1         | 0.49%   |
| 1360x768           | 1         | 0.49%   |
| 1280x720 (HD)      | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 54        | 25.12%  |
| 31      | 20        | 9.3%    |
| 23      | 16        | 7.44%   |
| 14      | 13        | 6.05%   |
| 17      | 12        | 5.58%   |
| 13      | 12        | 5.58%   |
| 72      | 11        | 5.12%   |
| 27      | 10        | 4.65%   |
| 21      | 10        | 4.65%   |
| 24      | 7         | 3.26%   |
| 19      | 6         | 2.79%   |
| 11      | 6         | 2.79%   |
| 34      | 5         | 2.33%   |
| Unknown | 5         | 2.33%   |
| 20      | 4         | 1.86%   |
| 18      | 4         | 1.86%   |
| 7       | 4         | 1.86%   |
| 32      | 2         | 0.93%   |
| 12      | 2         | 0.93%   |
| 142     | 1         | 0.47%   |
| 84      | 1         | 0.47%   |
| 64      | 1         | 0.47%   |
| 54      | 1         | 0.47%   |
| 52      | 1         | 0.47%   |
| 49      | 1         | 0.47%   |
| 29      | 1         | 0.47%   |
| 26      | 1         | 0.47%   |
| 25      | 1         | 0.47%   |
| 22      | 1         | 0.47%   |
| 16      | 1         | 0.47%   |
| 8       | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 71        | 33.49%  |
| 501-600        | 33        | 15.57%  |
| 601-700        | 23        | 10.85%  |
| 401-500        | 21        | 9.91%   |
| 201-300        | 16        | 7.55%   |
| 351-400        | 15        | 7.08%   |
| 1501-2000      | 11        | 5.19%   |
| 701-800        | 7         | 3.3%    |
| Unknown        | 5         | 2.36%   |
| 1001-1500      | 4         | 1.89%   |
| 1-100          | 4         | 1.89%   |
| More than 2000 | 1         | 0.47%   |
| 101-200        | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 152       | 79.58%  |
| 16/10   | 16        | 8.38%   |
| 21/9    | 6         | 3.14%   |
| 5/4     | 5         | 2.62%   |
| Unknown | 5         | 2.62%   |
| 0.67    | 3         | 1.57%   |
| 3/2     | 1         | 0.52%   |
| 1.00    | 1         | 0.52%   |
| 0.63    | 1         | 0.52%   |
| 0.62    | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 55        | 25.94%  |
| 201-250        | 29        | 13.68%  |
| 351-500        | 27        | 12.74%  |
| 81-90          | 21        | 9.91%   |
| More than 1000 | 15        | 7.08%   |
| 151-200        | 15        | 7.08%   |
| 301-350        | 11        | 5.19%   |
| 121-130        | 8         | 3.77%   |
| 51-60          | 6         | 2.83%   |
| 141-150        | 6         | 2.83%   |
| 1-40           | 5         | 2.36%   |
| Unknown        | 5         | 2.36%   |
| 71-80          | 4         | 1.89%   |
| 61-70          | 2         | 0.94%   |
| 251-300        | 2         | 0.94%   |
| 131-140        | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 69        | 33.17%  |
| 101-120       | 54        | 25.96%  |
| 121-160       | 50        | 24.04%  |
| 1-50          | 17        | 8.17%   |
| 161-240       | 9         | 4.33%   |
| Unknown       | 5         | 2.4%    |
| More than 240 | 4         | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 158       | 78.61%  |
| 2     | 36        | 17.91%  |
| 0     | 5         | 2.49%   |
| 3     | 2         | 1%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 116       | 38.41%  |
| Intel                    | 99        | 32.78%  |
| Qualcomm Atheros         | 24        | 7.95%   |
| Broadcom                 | 11        | 3.64%   |
| NetGear                  | 6         | 1.99%   |
| Ralink Technology        | 5         | 1.66%   |
| MediaTek                 | 5         | 1.66%   |
| Broadcom Limited         | 5         | 1.66%   |
| TP-Link                  | 4         | 1.32%   |
| Nvidia                   | 4         | 1.32%   |
| Marvell Technology Group | 4         | 1.32%   |
| ASIX Electronics         | 4         | 1.32%   |
| Samsung Electronics      | 3         | 0.99%   |
| Ralink                   | 3         | 0.99%   |
| Qualcomm Technologies    | 1         | 0.33%   |
| Qualcomm                 | 1         | 0.33%   |
| OPPO Electronics         | 1         | 0.33%   |
| Microsoft                | 1         | 0.33%   |
| Gemtek                   | 1         | 0.33%   |
| Dell                     | 1         | 0.33%   |
| Belkin Components        | 1         | 0.33%   |
| Aquantia                 | 1         | 0.33%   |
| Apple                    | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 69        | 19.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 3.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9         | 2.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 2.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 8         | 2.29%   |
| Intel Wi-Fi 6 AX200                                                    | 8         | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 1.71%   |
| Intel Wireless 7265                                                    | 6         | 1.71%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 1.43%   |
| Intel Wireless 8265 / 8275                                             | 5         | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 5         | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 4         | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 1.14%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.14%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.86%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 3         | 0.86%   |
| Realtek 802.11ac NIC                                                   | 3         | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.86%   |
| Intel Wireless 8260                                                    | 3         | 0.86%   |
| Intel Wireless 7260                                                    | 3         | 0.86%   |
| Intel Wireless 3165                                                    | 3         | 0.86%   |
| Intel Wireless 3160                                                    | 3         | 0.86%   |
| Intel Ethernet Controller I225-V                                       | 3         | 0.86%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 3         | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.86%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.86%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3         | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 0.57%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 2         | 0.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2         | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2         | 0.57%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                 | 2         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 71        | 39.89%  |
| Realtek Semiconductor    | 46        | 25.84%  |
| Qualcomm Atheros         | 19        | 10.67%  |
| Broadcom                 | 10        | 5.62%   |
| Ralink Technology        | 5         | 2.81%   |
| MediaTek                 | 5         | 2.81%   |
| TP-Link                  | 4         | 2.25%   |
| NetGear                  | 4         | 2.25%   |
| Broadcom Limited         | 4         | 2.25%   |
| Ralink                   | 3         | 1.69%   |
| Qualcomm Technologies    | 1         | 0.56%   |
| Qualcomm                 | 1         | 0.56%   |
| Microsoft                | 1         | 0.56%   |
| Marvell Technology Group | 1         | 0.56%   |
| Gemtek                   | 1         | 0.56%   |
| Dell                     | 1         | 0.56%   |
| Belkin Components        | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 9         | 4.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 8         | 4.32%   |
| Intel Wi-Fi 6 AX200                                                  | 8         | 4.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 6         | 3.24%   |
| Intel Wireless 7265                                                  | 6         | 3.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 5         | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 2.7%    |
| Intel Wireless 8265 / 8275                                           | 5         | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 5         | 2.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 4         | 2.16%   |
| Intel Wi-Fi 6 AX201                                                  | 4         | 2.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 1.62%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 3         | 1.62%   |
| Realtek 802.11ac NIC                                                 | 3         | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 1.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 1.62%   |
| Intel Wireless 8260                                                  | 3         | 1.62%   |
| Intel Wireless 7260                                                  | 3         | 1.62%   |
| Intel Wireless 3165                                                  | 3         | 1.62%   |
| Intel Wireless 3160                                                  | 3         | 1.62%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 3         | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 1.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2         | 1.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 2         | 1.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 2         | 1.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 1.08%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter               | 2         | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 1.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2         | 1.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2         | 1.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 2         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 1.08%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 2         | 1.08%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                        | 2         | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.08%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 2         | 1.08%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                              | 2         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 88        | 53.33%  |
| Intel                    | 47        | 28.48%  |
| Qualcomm Atheros         | 6         | 3.64%   |
| Nvidia                   | 4         | 2.42%   |
| Broadcom                 | 4         | 2.42%   |
| ASIX Electronics         | 4         | 2.42%   |
| Samsung Electronics      | 3         | 1.82%   |
| Marvell Technology Group | 3         | 1.82%   |
| NetGear                  | 2         | 1.21%   |
| OPPO Electronics         | 1         | 0.61%   |
| Broadcom Limited         | 1         | 0.61%   |
| Aquantia                 | 1         | 0.61%   |
| Apple                    | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 69        | 41.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11        | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 5.45%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 3.64%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 2.42%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 2.42%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 1.82%   |
| Intel Ethernet Controller I225-V                                               | 3         | 1.82%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.82%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 1.82%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.21%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.21%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.21%   |
| NetGear LB1120-100NAS                                                          | 2         | 1.21%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.21%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 1.21%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.21%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.21%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.61%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.61%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.61%   |
| OPPO OnePlus Nord 4                                                            | 1         | 0.61%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.61%   |
| Nvidia CK804 Ethernet Controller                                               | 1         | 0.61%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.61%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.61%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.61%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.61%   |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.61%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.61%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.61%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 0.61%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 160       | 50.16%  |
| Ethernet | 159       | 49.84%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 121       | 58.17%  |
| Ethernet | 87        | 41.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 101       | 52.06%  |
| 1     | 85        | 43.81%  |
| 0     | 5         | 2.58%   |
| 3     | 3         | 1.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 149       | 74.87%  |
| Yes  | 50        | 25.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 45.04%  |
| Realtek Semiconductor           | 19        | 14.5%   |
| Cambridge Silicon Radio         | 9         | 6.87%   |
| Qualcomm Atheros Communications | 8         | 6.11%   |
| IMC Networks                    | 8         | 6.11%   |
| Foxconn / Hon Hai               | 6         | 4.58%   |
| Apple                           | 5         | 3.82%   |
| Lite-On Technology              | 3         | 2.29%   |
| Dell                            | 3         | 2.29%   |
| Broadcom                        | 3         | 2.29%   |
| Hewlett-Packard                 | 2         | 1.53%   |
| Toshiba                         | 1         | 0.76%   |
| MediaTek                        | 1         | 0.76%   |
| Marvell Semiconductor           | 1         | 0.76%   |
| Dynex                           | 1         | 0.76%   |
| Belkin Components               | 1         | 0.76%   |
| Alps Electric                   | 1         | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 21        | 16.03%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 10        | 7.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 7.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 6.87%   |
| Intel AX201 Bluetooth                                                               | 8         | 6.11%   |
| Intel AX200 Bluetooth                                                               | 8         | 6.11%   |
| Realtek Bluetooth Radio                                                             | 5         | 3.82%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 3.82%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 3.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 3.05%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 3.05%   |
| IMC Networks Wireless_Device                                                        | 3         | 2.29%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.29%   |
| Apple Bluetooth Host Controller                                                     | 3         | 2.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.53%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.53%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.53%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.53%   |
| Broadcom Bluetooth Device                                                           | 2         | 1.53%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.76%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.76%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.76%   |
| Realtek Bluetooth 5.3 Radio                                                         | 1         | 0.76%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.76%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.76%   |
| MediaTek Wireless_Device                                                            | 1         | 0.76%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.76%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.76%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.76%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.76%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 1         | 0.76%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.76%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.76%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.76%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.76%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.76%   |
| Belkin Components Bluetooth Mini Dongle                                             | 1         | 0.76%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 141       | 58.02%  |
| AMD                                             | 52        | 21.4%   |
| Nvidia                                          | 31        | 12.76%  |
| Logitech                                        | 7         | 2.88%   |
| C-Media Electronics                             | 3         | 1.23%   |
| Micro Star International                        | 2         | 0.82%   |
| NZXT                                            | 1         | 0.41%   |
| Nintendo                                        | 1         | 0.41%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.41%   |
| Kingston Technology                             | 1         | 0.41%   |
| Hewlett-Packard                                 | 1         | 0.41%   |
| Focusrite-Novation                              | 1         | 0.41%   |
| Apple                                           | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 8.11%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 18        | 6.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 5.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 3.38%   |
| AMD FCH Azalia Controller                                                                         | 10        | 3.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 3.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.03%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 6         | 2.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.69%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 1.69%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1.35%   |
| Logitech EasyCall Speakerphone                                                                    | 4         | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.35%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.35%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.35%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.01%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.01%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.01%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.01%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.01%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 1.01%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 1.01%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 18        | 23.68%  |
| Samsung Electronics | 15        | 19.74%  |
| Unknown             | 7         | 9.21%   |
| Micron Technology   | 5         | 6.58%   |
| Kingston            | 5         | 6.58%   |
| Crucial             | 5         | 6.58%   |
| G.Skill             | 3         | 3.95%   |
| Corsair             | 3         | 3.95%   |
| Team                | 2         | 2.63%   |
| PNY                 | 2         | 2.63%   |
| A-DATA Technology   | 2         | 2.63%   |
| Unknown (0x0B45)    | 1         | 1.32%   |
| Silicon Power       | 1         | 1.32%   |
| Sesame              | 1         | 1.32%   |
| Ramaxel Technology  | 1         | 1.32%   |
| Qumo                | 1         | 1.32%   |
| Euronet             | 1         | 1.32%   |
| Elpida              | 1         | 1.32%   |
| Avant               | 1         | 1.32%   |
| Unknown             | 1         | 1.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                             | 3         | 3.61%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 3         | 3.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 3.61%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 2.41%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 1.2%    |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 1         | 1.2%    |
| Unknown RAM Module 1GB DIMM                                      | 1         | 1.2%    |
| Unknown RAM CL18-22-22 D4-3600 16384MB DIMM DDR4 3600MT/s        | 1         | 1.2%    |
| Unknown RAM CL18-20-20 D4-3600 8192MB DIMM DDR4 3600MT/s         | 1         | 1.2%    |
| Unknown (0x0B45) RAM WPBH32D416SWA-16G 16GB SODIMM DDR4 3200MT/s | 1         | 1.2%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s               | 1         | 1.2%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 1         | 1.2%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.2%    |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 1.2%    |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                       | 1         | 1.2%    |
| SK hynix RAM Module 4GB SODIMM LPDDR3 2133MT/s                   | 1         | 1.2%    |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s                    | 1         | 1.2%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 1.2%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.2%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.2%    |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.2%    |
| SK hynix RAM H9CCNNN8GTALAR-NUD 2GB LPDDR3 1600MT/s              | 1         | 1.2%    |
| Silicon Power RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 1.2%    |
| Sesame RAM S939A2UGS-ITR 8GB DIMM DDR3 3200MT/s                  | 1         | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.2%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.2%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.2%    |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s              | 1         | 1.2%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.2%    |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s           | 1         | 1.2%    |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s              | 1         | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 34        | 47.89%  |
| DDR3    | 23        | 32.39%  |
| LPDDR3  | 4         | 5.63%   |
| SDRAM   | 3         | 4.23%   |
| LPDDR4  | 2         | 2.82%   |
| Unknown | 2         | 2.82%   |
| DDR5    | 1         | 1.41%   |
| DDR2    | 1         | 1.41%   |
| DDR     | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 54.29%  |
| DIMM         | 29        | 41.43%  |
| Row Of Chips | 2         | 2.86%   |
| Unknown      | 1         | 1.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 31        | 42.47%  |
| 4096  | 18        | 24.66%  |
| 16384 | 13        | 17.81%  |
| 2048  | 7         | 9.59%   |
| 32768 | 3         | 4.11%   |
| 1024  | 1         | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 22.97%  |
| 3200    | 15        | 20.27%  |
| 2667    | 13        | 17.57%  |
| 2133    | 4         | 5.41%   |
| Unknown | 4         | 5.41%   |
| 3600    | 3         | 4.05%   |
| 1333    | 3         | 4.05%   |
| 2400    | 2         | 2.7%    |
| 667     | 2         | 2.7%    |
| 5600    | 1         | 1.35%   |
| 3733    | 1         | 1.35%   |
| 3533    | 1         | 1.35%   |
| 3266    | 1         | 1.35%   |
| 2666    | 1         | 1.35%   |
| 1867    | 1         | 1.35%   |
| 1866    | 1         | 1.35%   |
| 1334    | 1         | 1.35%   |
| 1067    | 1         | 1.35%   |
| 975     | 1         | 1.35%   |
| 800     | 1         | 1.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Canon              | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP OfficeJet Pro 6960   | 1         | 25%     |
| HP DeskJet 2700 series  | 1         | 25%     |
| Canon CanoScan LiDE 300 | 1         | 25%     |
| Brother MFC-L2685DW     | 1         | 25%     |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 11.61%  |
| Realtek Semiconductor                  | 11        | 9.82%   |
| Microdia                               | 11        | 9.82%   |
| Bison Electronics                      | 8         | 7.14%   |
| Sunplus Innovation Technology          | 7         | 6.25%   |
| Logitech                               | 7         | 6.25%   |
| Lite-On Technology                     | 6         | 5.36%   |
| Apple                                  | 6         | 5.36%   |
| Ricoh                                  | 5         | 4.46%   |
| Quanta                                 | 5         | 4.46%   |
| IMC Networks                           | 5         | 4.46%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.46%   |
| Luxvisions Innotech Limited            | 3         | 2.68%   |
| Syntek                                 | 2         | 1.79%   |
| Suyin                                  | 2         | 1.79%   |
| Razer USA                              | 2         | 1.79%   |
| Microsoft                              | 2         | 1.79%   |
| Lenovo                                 | 2         | 1.79%   |
| Acer                                   | 2         | 1.79%   |
| Trust                                  | 1         | 0.89%   |
| ShineTech                              | 1         | 0.89%   |
| Primax Electronics                     | 1         | 0.89%   |
| MacroSilicon                           | 1         | 0.89%   |
| Jieli Technology                       | 1         | 0.89%   |
| Goertek Electronics                    | 1         | 0.89%   |
| Cubeternet                             | 1         | 0.89%   |
| Alpha Imaging Technology               | 1         | 0.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 4         | 3.51%   |
| Microdia Camera                                                | 4         | 3.51%   |
| Lite-On HP Wide Vision HD Camera                               | 4         | 3.51%   |
| Ricoh Integrated Webcam                                        | 3         | 2.63%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 2.63%   |
| Logitech HD Pro Webcam C920                                    | 3         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 2.63%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.75%   |
| Quanta HP Wide Vision HD Camera                                | 2         | 1.75%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 1.75%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 2         | 1.75%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 1.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 1.75%   |
| Lite-On HP HD Webcam                                           | 2         | 1.75%   |
| Lenovo Integrated Webcam [R5U877]                              | 2         | 1.75%   |
| IMC Networks UVC VGA Webcam                                    | 2         | 1.75%   |
| Chicony HP Truevision HD                                       | 2         | 1.75%   |
| Chicony HD WebCam                                              | 2         | 1.75%   |
| Bison Lenovo EasyCamera                                        | 2         | 1.75%   |
| Bison Integrated Camera                                        | 2         | 1.75%   |
| Apple FaceTime HD Camera (Built-in)                            | 2         | 1.75%   |
| Apple FaceTime HD Camera                                       | 2         | 1.75%   |
| Apple Built-in iSight                                          | 2         | 1.75%   |
| Trust Trust 1080p HD Webcam                                    | 1         | 0.88%   |
| Syntek Lenovo EasyCamera                                       | 1         | 0.88%   |
| Syntek Integrated Camera                                       | 1         | 0.88%   |
| Suyin USB 2.0 Camera                                           | 1         | 0.88%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.88%   |
| Sunplus MTD Camera                                             | 1         | 0.88%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 0.88%   |
| Sunplus DICOTA 4K                                              | 1         | 0.88%   |
| ShineTech USB2.0 HD UVC WebCam                                 | 1         | 0.88%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam       | 1         | 0.88%   |
| Ricoh HD Webcam                                                | 1         | 0.88%   |
| Realtek USB2.0 camera                                          | 1         | 0.88%   |
| Realtek Laptop Camera                                          | 1         | 0.88%   |
| Realtek Integrated_Webcam_FHD                                  | 1         | 0.88%   |
| Realtek Integrated Webcam                                      | 1         | 0.88%   |
| Realtek Integrated Camera                                      | 1         | 0.88%   |
| Realtek 2SF022                                                 | 1         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 13        | 61.9%   |
| Synaptics             | 4         | 19.05%  |
| LighTuning Technology | 2         | 9.52%   |
| Upek                  | 1         | 4.76%   |
| AuthenTec             | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 5         | 23.81%  |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 9.52%   |
| Synaptics UWP WBDI                                     | 2         | 9.52%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 9.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4.76%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4.76%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.76%   |
| Validity Sensors Synaptics WBDI                        | 1         | 4.76%   |
| Validity Sensors Fingerprint scanner                   | 1         | 4.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.76%   |
| Synaptics  WBDI                                        | 1         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.76%   |
| AuthenTec AES2810                                      | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 140       | 69.31%  |
| 1     | 54        | 26.73%  |
| 2     | 8         | 3.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 31.34%  |
| Net/wireless             | 19        | 28.36%  |
| Graphics card            | 13        | 19.4%   |
| Chipcard                 | 5         | 7.46%   |
| Communication controller | 3         | 4.48%   |
| Multimedia controller    | 2         | 2.99%   |
| Storage                  | 1         | 1.49%   |
| Net/ethernet             | 1         | 1.49%   |
| Modem                    | 1         | 1.49%   |
| Camera                   | 1         | 1.49%   |

