Lubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Lubuntu.

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

Total: 830

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S145-15IGM 81MX     | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| MSI           | VR630                       | [097cd732b3](https://linux-hardware.org/?probe=097cd732b3) | Jun 27, 2022 |
| Apple         | MacBookPro10,1              | [a27f696a28](https://linux-hardware.org/?probe=a27f696a28) | Jun 27, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | [f6f825d83a](https://linux-hardware.org/?probe=f6f825d83a) | Jun 22, 2022 |
| HP            | Notebook                    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| Gateway       | Sonic-C                     | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Dell          | Latitude XT                 | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Notebook                    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| Intel         | W7650                       | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| ASUSTek       | 1000H                       | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | G62                         | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| HP            | Pavilion g6                 | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Packard Be... | EasyNote TE11HC             | [8350bd6d87](https://linux-hardware.org/?probe=8350bd6d87) | May 30, 2022 |
| HP            | Berknip                     | [c81d3442c2](https://linux-hardware.org/?probe=c81d3442c2) | May 27, 2022 |
| ASUSTek       | X205TA                      | [9fa4c6beef](https://linux-hardware.org/?probe=9fa4c6beef) | May 26, 2022 |
| HP            | Pavilion g6                 | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| HP            | OMEN by Laptop              | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| Toshiba       | Satellite L40               | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| ASUSTek       | X402CA                      | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [68ee4b094a](https://linux-hardware.org/?probe=68ee4b094a) | May 13, 2022 |
| Acer          | Swift SF114-34              | [5774e3f483](https://linux-hardware.org/?probe=5774e3f483) | May 12, 2022 |
| Acer          | Aspire A317-33              | [f3bd3e55aa](https://linux-hardware.org/?probe=f3bd3e55aa) | May 12, 2022 |
| Acer          | Aspire A317-33              | [3a09364bb2](https://linux-hardware.org/?probe=3a09364bb2) | May 12, 2022 |
| Toshiba       | Satellite P20               | [923779da79](https://linux-hardware.org/?probe=923779da79) | May 11, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Positivo      | AT300b                      | [7f5c5ceed4](https://linux-hardware.org/?probe=7f5c5ceed4) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| ASUSTek       | 900                         | [6cbd0391b3](https://linux-hardware.org/?probe=6cbd0391b3) | May 07, 2022 |
| Intel         | W7650                       | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| ASUSTek       | K55VD                       | [8ff47b2a2c](https://linux-hardware.org/?probe=8ff47b2a2c) | May 05, 2022 |
| Toshiba       | Satellite C670D-12N         | [f6bd692d1f](https://linux-hardware.org/?probe=f6bd692d1f) | May 05, 2022 |
| Apple         | MacBookPro14,1              | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [4682643304](https://linux-hardware.org/?probe=4682643304) | May 05, 2022 |
| Apple         | MacBookPro14,1              | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [5a36e4d0fc](https://linux-hardware.org/?probe=5a36e4d0fc) | May 04, 2022 |
| Samsung       | RV415/RV515                 | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| HP            | Pavilion g4                 | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| ASUSTek       | 900                         | [70b70a4392](https://linux-hardware.org/?probe=70b70a4392) | May 03, 2022 |
| Fujitsu       | LIFEBOOK S751               | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | [c206790d1e](https://linux-hardware.org/?probe=c206790d1e) | May 01, 2022 |
| HP            | EliteBook 8570p             | [2dffdad8a4](https://linux-hardware.org/?probe=2dffdad8a4) | May 01, 2022 |
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| YASHI         | MYBOOK 360                  | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| HP            | Pavilion g4                 | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| Dell          | Latitude 7480               | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| Gigabyte      | M912                        | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | 1215N                       | [b921f6fbae](https://linux-hardware.org/?probe=b921f6fbae) | Apr 24, 2022 |
| Mediacom      | GTZS                        | [41939828a4](https://linux-hardware.org/?probe=41939828a4) | Apr 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| Google        | Droid                       | [b7b4dc6117](https://linux-hardware.org/?probe=b7b4dc6117) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| Mediacom      | GTZS                        | [edc22ef82a](https://linux-hardware.org/?probe=edc22ef82a) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| HP            | Pavilion dv4                | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| Intel         | W7650                       | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| HP            | Compaq Presario C700        | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Dell          | Inspiron 3180               | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| Dell          | Latitude E6410              | [e5e350a4a8](https://linux-hardware.org/?probe=e5e350a4a8) | Apr 13, 2022 |
| Google        | Kip                         | [4641a94428](https://linux-hardware.org/?probe=4641a94428) | Apr 13, 2022 |
| Dell          | Latitude E7240              | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| ASUSTek       | 1000H                       | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| Dell          | Inspiron N4010              | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| Samsung       | N100SP                      | [6a70399256](https://linux-hardware.org/?probe=6a70399256) | Mar 31, 2022 |
| Acer          | AOA150                      | [a59a005250](https://linux-hardware.org/?probe=a59a005250) | Mar 30, 2022 |
| Intel         | W7650                       | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Haier         | U1520EM                     | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | [af80d44a27](https://linux-hardware.org/?probe=af80d44a27) | Mar 23, 2022 |
| HP            | Pavilion g7                 | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| IBM           | Unknown                     | [2bcbb8a946](https://linux-hardware.org/?probe=2bcbb8a946) | Mar 21, 2022 |
| HP            | EliteBook 745 G6            | [a3f94c2957](https://linux-hardware.org/?probe=a3f94c2957) | Mar 20, 2022 |
| Apple         | MacBookPro6,2               | [d4c7ecbc5e](https://linux-hardware.org/?probe=d4c7ecbc5e) | Mar 20, 2022 |
| Acer          | AO751h                      | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| Google        | Celes                       | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| HP            | Laptop 15-bs0xx             | [37a24fa0b8](https://linux-hardware.org/?probe=37a24fa0b8) | Mar 13, 2022 |
| HP            | Laptop 15-da0xxx            | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| ASUSTek       | X550LA                      | [eb7071ed13](https://linux-hardware.org/?probe=eb7071ed13) | Mar 12, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| Fujitsu Si... | AMILO Li3710                | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| Lenovo        | G50-30 80G0                 | [efc41b55f4](https://linux-hardware.org/?probe=efc41b55f4) | Mar 06, 2022 |
| Dell          | Inspiron 1090               | [31efa1bb6f](https://linux-hardware.org/?probe=31efa1bb6f) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | [6a97a96f56](https://linux-hardware.org/?probe=6a97a96f56) | Mar 01, 2022 |
| Dell          | Inspiron 1090               | [9d63b9e47f](https://linux-hardware.org/?probe=9d63b9e47f) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [9a59eff157](https://linux-hardware.org/?probe=9a59eff157) | Feb 26, 2022 |
| Toshiba       | Satellite S55-B             | [f07aaa2fd3](https://linux-hardware.org/?probe=f07aaa2fd3) | Feb 25, 2022 |
| Insyde        | N116                        | [a6dd43dfb4](https://linux-hardware.org/?probe=a6dd43dfb4) | Feb 21, 2022 |
| Toshiba       | Satellite S55-B             | [8551d043a9](https://linux-hardware.org/?probe=8551d043a9) | Feb 20, 2022 |
| Intel         | W7650                       | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |
| Alienware     | M17                         | [9d29db918d](https://linux-hardware.org/?probe=9d29db918d) | Feb 18, 2022 |
| HP            | Pavilion g6                 | [5601a4d596](https://linux-hardware.org/?probe=5601a4d596) | Feb 14, 2022 |
| HP            | Laptop 15-da0xxx            | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [1f9694d47d](https://linux-hardware.org/?probe=1f9694d47d) | Feb 12, 2022 |
| Sony          | VGN-SZ71WN_C                | [677d24e366](https://linux-hardware.org/?probe=677d24e366) | Feb 11, 2022 |
| Positivo      | N600                        | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Dell          | Inspiron 11-3168            | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Dell          | Latitude E5540              | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| HP            | 255 G6 Notebook PC          | [9c5efed237](https://linux-hardware.org/?probe=9c5efed237) | Feb 06, 2022 |
| Lenovo        | 3000 N200 0769ALU           | [695855f143](https://linux-hardware.org/?probe=695855f143) | Feb 05, 2022 |
| Lenovo        | 3000 N200 0769ALU           | [661ffedd80](https://linux-hardware.org/?probe=661ffedd80) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | [4c355aa7c2](https://linux-hardware.org/?probe=4c355aa7c2) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | [61fc6b2cb0](https://linux-hardware.org/?probe=61fc6b2cb0) | Feb 05, 2022 |
| Toshiba       | Satellite C875              | [1dd31ebdd6](https://linux-hardware.org/?probe=1dd31ebdd6) | Feb 02, 2022 |
| Insyde        | i101c                       | [375f7e61b2](https://linux-hardware.org/?probe=375f7e61b2) | Feb 02, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| Google        | Peppy                       | [15cd563f21](https://linux-hardware.org/?probe=15cd563f21) | Jan 27, 2022 |
| ASUSTek       | GL553VW                     | [7713319e74](https://linux-hardware.org/?probe=7713319e74) | Jan 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| Apple         | MacBookPro10,1              | [1aa2cd2e8f](https://linux-hardware.org/?probe=1aa2cd2e8f) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Apple         | MacBookPro10,2              | [804b4adedc](https://linux-hardware.org/?probe=804b4adedc) | Jan 15, 2022 |
| HP            | ProBook 450 G2              | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| HP            | Notebook                    | [847afd8ac5](https://linux-hardware.org/?probe=847afd8ac5) | Jan 12, 2022 |
| System76      | Lemur Pro                   | [fa22d4610e](https://linux-hardware.org/?probe=fa22d4610e) | Jan 11, 2022 |
| Positivo      | N600                        | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| HP            | Compaq 6910p (GX316UC#AB... | [0ffa23c15e](https://linux-hardware.org/?probe=0ffa23c15e) | Jan 07, 2022 |
| Toshiba       | Satellite L50D-B            | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| HP            | Pavilion dv2700             | [c8aafbbc8d](https://linux-hardware.org/?probe=c8aafbbc8d) | Jan 04, 2022 |
| Alienware     | m15                         | [a0d4f93250](https://linux-hardware.org/?probe=a0d4f93250) | Jan 04, 2022 |
| Apple         | MacBookPro8,1               | [eaf2e708d9](https://linux-hardware.org/?probe=eaf2e708d9) | Jan 03, 2022 |
| Acer          | Aspire 7715Z                | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Dell          | Latitude 7480               | [a338b67d45](https://linux-hardware.org/?probe=a338b67d45) | Dec 30, 2021 |
| Sony          | VPCEJ1E1E                   | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Dell          | Inspiron 15 3515            | [8d130910ab](https://linux-hardware.org/?probe=8d130910ab) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [f5924cb8b4](https://linux-hardware.org/?probe=f5924cb8b4) | Dec 25, 2021 |
| Sony          | VPCEJ1E1E                   | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| Acer          | AOA150                      | [47cae573c1](https://linux-hardware.org/?probe=47cae573c1) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| Acer          | Aspire F5-573G              | [2e9fd50292](https://linux-hardware.org/?probe=2e9fd50292) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | [452b8c0ac4](https://linux-hardware.org/?probe=452b8c0ac4) | Dec 20, 2021 |
| Dell          | Latitude E6520              | [c7edb79be7](https://linux-hardware.org/?probe=c7edb79be7) | Dec 20, 2021 |
| Samsung       | 275E4E/275E5E               | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [b956646608](https://linux-hardware.org/?probe=b956646608) | Dec 12, 2021 |
| HP            | EliteBook 850 G3            | [7cf21876b0](https://linux-hardware.org/?probe=7cf21876b0) | Dec 12, 2021 |
| Acer          | Aspire 5742G                | [950da990e7](https://linux-hardware.org/?probe=950da990e7) | Dec 12, 2021 |
| HP            | OMEN by Laptop              | [8419e68dd3](https://linux-hardware.org/?probe=8419e68dd3) | Dec 12, 2021 |
| ASUSTek       | 1015BXO                     | [f9eb963d74](https://linux-hardware.org/?probe=f9eb963d74) | Dec 12, 2021 |
| MSI           | Katana GF76 11UC            | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Positivo      | AT300b                      | [20b3635188](https://linux-hardware.org/?probe=20b3635188) | Dec 06, 2021 |
| HP            | Compaq 6510b (GR691EA#AB... | [4d657211eb](https://linux-hardware.org/?probe=4d657211eb) | Dec 04, 2021 |
| Acer          | AOD255E                     | [390afd35cb](https://linux-hardware.org/?probe=390afd35cb) | Dec 03, 2021 |
| HP            | ProBook 440 G7              | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [edce40927f](https://linux-hardware.org/?probe=edce40927f) | Dec 01, 2021 |
| Toshiba       | Satellite C50-A-19U         | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| HP            | Compaq 6720s                | [2c62d9df9c](https://linux-hardware.org/?probe=2c62d9df9c) | Nov 28, 2021 |
| ASUSTek       | 1000HE                      | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| I-Life Dig... | ZED AIR                     | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Toshiba       | Satellite L40               | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Dell          | Latitude 3330               | [2c8f88588b](https://linux-hardware.org/?probe=2c8f88588b) | Nov 23, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | [867419b410](https://linux-hardware.org/?probe=867419b410) | Nov 21, 2021 |
| Medion        | P6630                       | [edc09031bd](https://linux-hardware.org/?probe=edc09031bd) | Nov 16, 2021 |
| HP            | Pavilion dv6                | [591f986631](https://linux-hardware.org/?probe=591f986631) | Nov 14, 2021 |
| ASUSTek       | 1015BX                      | [51933ea3ac](https://linux-hardware.org/?probe=51933ea3ac) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [0e17c0b84d](https://linux-hardware.org/?probe=0e17c0b84d) | Nov 13, 2021 |
| HP            | ProBook 440 G7              | [35b6f85a28](https://linux-hardware.org/?probe=35b6f85a28) | Nov 10, 2021 |
| Acer          | AO751h                      | [e2beb798cc](https://linux-hardware.org/?probe=e2beb798cc) | Nov 10, 2021 |
| Dell          | Inspiron MM061              | [03bba840c5](https://linux-hardware.org/?probe=03bba840c5) | Nov 07, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [4e3e71f6ab](https://linux-hardware.org/?probe=4e3e71f6ab) | Nov 07, 2021 |
| HP            | Laptop 15s-fq1xxx           | [25f858c7b1](https://linux-hardware.org/?probe=25f858c7b1) | Nov 05, 2021 |
| Mediacom      | GTZS                        | [a2a881793d](https://linux-hardware.org/?probe=a2a881793d) | Nov 03, 2021 |
| HP            | ProBook 4540s               | [fca622f4c4](https://linux-hardware.org/?probe=fca622f4c4) | Nov 01, 2021 |
| Samsung       | R40/R41                     | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| HP            | Pavilion dv6                | [e84cd86eb0](https://linux-hardware.org/?probe=e84cd86eb0) | Oct 31, 2021 |
| HP            | Pavilion Notebook           | [2c6c86b1fb](https://linux-hardware.org/?probe=2c6c86b1fb) | Oct 31, 2021 |
| HP            | ProBook 4540s               | [e12d7e47e6](https://linux-hardware.org/?probe=e12d7e47e6) | Oct 31, 2021 |
| HP            | ProBook 4540s               | [e565d7befe](https://linux-hardware.org/?probe=e565d7befe) | Oct 31, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f86520f5a7](https://linux-hardware.org/?probe=f86520f5a7) | Oct 28, 2021 |
| HP            | Presario CQ58               | [60d72bdce7](https://linux-hardware.org/?probe=60d72bdce7) | Oct 28, 2021 |
| HP            | Presario CQ58               | [8989debda6](https://linux-hardware.org/?probe=8989debda6) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [e1e44b58f3](https://linux-hardware.org/?probe=e1e44b58f3) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [42d3788463](https://linux-hardware.org/?probe=42d3788463) | Oct 27, 2021 |
| HP            | 2000                        | [65ec913842](https://linux-hardware.org/?probe=65ec913842) | Oct 27, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1663dc4946](https://linux-hardware.org/?probe=1663dc4946) | Oct 26, 2021 |
| Samsung       | N100SP                      | [7e4ef50289](https://linux-hardware.org/?probe=7e4ef50289) | Oct 26, 2021 |
| Acer          | TravelMate P253             | [d74c10f41f](https://linux-hardware.org/?probe=d74c10f41f) | Oct 24, 2021 |
| Dell          | Inspiron 3583               | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Sony          | VGN-CR11Z_R                 | [538c03b235](https://linux-hardware.org/?probe=538c03b235) | Oct 23, 2021 |
| Samsung       | N100SP                      | [4d8eadf806](https://linux-hardware.org/?probe=4d8eadf806) | Oct 23, 2021 |
| Apple         | MacBookPro8,1               | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Sony          | VGN-CR11Z_R                 | [57043d09fe](https://linux-hardware.org/?probe=57043d09fe) | Oct 22, 2021 |
| Acer          | Aspire ES1-131              | [de7bee5c36](https://linux-hardware.org/?probe=de7bee5c36) | Oct 20, 2021 |
| Intel         | W7650                       | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| Toshiba       | Satellite C50D-A-13G        | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| MSI           | Modern 15 A10M              | [184c512c35](https://linux-hardware.org/?probe=184c512c35) | Oct 18, 2021 |
| Lenovo        | ThinkPad X61 76744NG        | [ee90608b54](https://linux-hardware.org/?probe=ee90608b54) | Oct 15, 2021 |
| NOBLEX        | E11IS2                      | [463e1f38e8](https://linux-hardware.org/?probe=463e1f38e8) | Oct 14, 2021 |
| HP            | Pavilion x2 Detachable      | [e5702172f9](https://linux-hardware.org/?probe=e5702172f9) | Oct 11, 2021 |
| HP            | Notebook                    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | 2000                        | [d84546de1b](https://linux-hardware.org/?probe=d84546de1b) | Oct 08, 2021 |
| HP            | Pavilion x2 Detachable      | [f81838645f](https://linux-hardware.org/?probe=f81838645f) | Oct 07, 2021 |
| HP            | Notebook                    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Dell          | Inspiron 15-3567            | [414e52d7a4](https://linux-hardware.org/?probe=414e52d7a4) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| HP            | Laptop 15-da0xxx            | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| Sony          | VPCSA2FGX                   | [60cfbaebef](https://linux-hardware.org/?probe=60cfbaebef) | Sep 29, 2021 |
| HP            | EliteBook 2560p             | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Apple         | MacBookPro8,1               | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| ASUSTek       | 1215B                       | [c45de8d3b1](https://linux-hardware.org/?probe=c45de8d3b1) | Sep 21, 2021 |
| Toshiba       | Satellite L20               | [654c60e971](https://linux-hardware.org/?probe=654c60e971) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Unknown       | Unknown                     | [64604612b2](https://linux-hardware.org/?probe=64604612b2) | Sep 19, 2021 |
| Lenovo        | G50-80 80L0                 | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| Dell          | Inspiron 3558               | [be96e8a7e1](https://linux-hardware.org/?probe=be96e8a7e1) | Sep 13, 2021 |
| Dell          | Inspiron 3558               | [f1414fdf7b](https://linux-hardware.org/?probe=f1414fdf7b) | Sep 13, 2021 |
| Apple         | MacBookPro8,1               | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| Lenovo        | G50-80 80L0                 | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| HP            | ProBook 450 G1              | [284c0763b3](https://linux-hardware.org/?probe=284c0763b3) | Sep 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Toshiba       | Satellite A215              | [2d0d778e8e](https://linux-hardware.org/?probe=2d0d778e8e) | Aug 31, 2021 |
| Notebook      | NL40_50GU                   | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| Google        | Careena                     | [ab1bafda25](https://linux-hardware.org/?probe=ab1bafda25) | Aug 27, 2021 |
| Toshiba       | Satellite A205              | [50f9ce0180](https://linux-hardware.org/?probe=50f9ce0180) | Aug 26, 2021 |
| Dell          | XPS 13 9300                 | [6e1f484406](https://linux-hardware.org/?probe=6e1f484406) | Aug 24, 2021 |
| Toshiba       | Satellite A205              | [63b870739f](https://linux-hardware.org/?probe=63b870739f) | Aug 19, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Toshiba       | Satellite A205              | [bc09a1e988](https://linux-hardware.org/?probe=bc09a1e988) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| Dell          | Inspiron 3583               | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [798feee097](https://linux-hardware.org/?probe=798feee097) | Aug 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| HP            | Pavilion g4                 | [f1d3ddf197](https://linux-hardware.org/?probe=f1d3ddf197) | Aug 06, 2021 |
| Dell          | G3 3500                     | [239b740235](https://linux-hardware.org/?probe=239b740235) | Aug 03, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| HP            | OMEN by Laptop              | [7ca0de35b4](https://linux-hardware.org/?probe=7ca0de35b4) | Aug 01, 2021 |
| Dell          | Latitude E5450              | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | ProBook 6450b               | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Acer          | Aspire 5735                 | [db933e0ebd](https://linux-hardware.org/?probe=db933e0ebd) | Jul 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d77a8cde0f](https://linux-hardware.org/?probe=d77a8cde0f) | Jul 23, 2021 |
| Dell          | Inspiron M5040              | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Dell          | Inspiron 1018               | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| Sony          | SVE1113M1EW                 | [b01beadd52](https://linux-hardware.org/?probe=b01beadd52) | Jul 16, 2021 |
| Toshiba       | K201                        | [85abf16ca0](https://linux-hardware.org/?probe=85abf16ca0) | Jul 15, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| Google        | Winky                       | [696230b066](https://linux-hardware.org/?probe=696230b066) | Jul 14, 2021 |
| Google        | Winky                       | [6048ac2ff9](https://linux-hardware.org/?probe=6048ac2ff9) | Jul 14, 2021 |
| Apple         | MacBookPro10,2              | [0f8c7a6b66](https://linux-hardware.org/?probe=0f8c7a6b66) | Jul 12, 2021 |
| LEADER        | TW9/SW9                     | [6da16947e1](https://linux-hardware.org/?probe=6da16947e1) | Jul 07, 2021 |
| ASUSTek       | 1015PE                      | [051265df6e](https://linux-hardware.org/?probe=051265df6e) | Jul 05, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [b083bc08c4](https://linux-hardware.org/?probe=b083bc08c4) | Jul 04, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| Apple         | MacBook4,1                  | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| MSI           | GX780R/GT780R/GT780DXR/G... | [212a084b93](https://linux-hardware.org/?probe=212a084b93) | Jul 01, 2021 |
| Samsung       | RV415/RV515                 | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| HP            | EliteBook 840 G6            | [cfd34d8c5b](https://linux-hardware.org/?probe=cfd34d8c5b) | Jun 22, 2021 |
| ASUSTek       | T100TA                      | [8a1c5e9daf](https://linux-hardware.org/?probe=8a1c5e9daf) | Jun 21, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [d94415969c](https://linux-hardware.org/?probe=d94415969c) | Jun 19, 2021 |
| Notebook      | NHxxRZQ                     | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [fdbc9729c1](https://linux-hardware.org/?probe=fdbc9729c1) | Jun 18, 2021 |
| HP            | EliteBook 2560p             | [b8cf45e412](https://linux-hardware.org/?probe=b8cf45e412) | Jun 15, 2021 |
| Positivo      | Mobile                      | [050aa55013](https://linux-hardware.org/?probe=050aa55013) | Jun 14, 2021 |
| Samsung       | RC512                       | [d8681e5e08](https://linux-hardware.org/?probe=d8681e5e08) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Google        | Kohaku                      | [6de3f99f1d](https://linux-hardware.org/?probe=6de3f99f1d) | Jun 08, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [0a5cb29f98](https://linux-hardware.org/?probe=0a5cb29f98) | Jun 07, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [29f66db2d1](https://linux-hardware.org/?probe=29f66db2d1) | Jun 07, 2021 |
| Acer          | Aspire 5715Z                | [5824a05a58](https://linux-hardware.org/?probe=5824a05a58) | Jun 05, 2021 |
| ASUSTek       | T100HAN                     | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| Lenovo        | ThinkPad T410s 2924C39      | [5dc4a1e557](https://linux-hardware.org/?probe=5dc4a1e557) | May 31, 2021 |
| Acer          | Aspire 5715Z                | [2e325cddc1](https://linux-hardware.org/?probe=2e325cddc1) | May 30, 2021 |
| Acer          | Aspire 5715Z                | [417206cc6a](https://linux-hardware.org/?probe=417206cc6a) | May 30, 2021 |
| Dell          | Latitude D820               | [5b23528d58](https://linux-hardware.org/?probe=5b23528d58) | May 29, 2021 |
| MSI           | Modern 15 A10M              | [23182c745b](https://linux-hardware.org/?probe=23182c745b) | May 27, 2021 |
| HP            | ProBook 6550b               | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | Latitude D630               | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| Acer          | Aspire 5715Z                | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Dell          | Inspiron MM061              | [3eb7729825](https://linux-hardware.org/?probe=3eb7729825) | May 23, 2021 |
| Lenovo        | G70-80 80FF                 | [fba07779e2](https://linux-hardware.org/?probe=fba07779e2) | May 21, 2021 |
| MSI           | Modern 15 A10M              | [001eb9ea2f](https://linux-hardware.org/?probe=001eb9ea2f) | May 21, 2021 |
| Lenovo        | ThinkPad W510 4318CTO       | [bc53ad8072](https://linux-hardware.org/?probe=bc53ad8072) | May 20, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | [6e24cb56ad](https://linux-hardware.org/?probe=6e24cb56ad) | May 19, 2021 |
| HP            | Presario V5000 (ET820UA#... | [f91a752d4d](https://linux-hardware.org/?probe=f91a752d4d) | May 19, 2021 |
| ASUSTek       | 1005HA                      | [e819e51835](https://linux-hardware.org/?probe=e819e51835) | May 18, 2021 |
| Acer          | Extensa 5620                | [2da2f6a795](https://linux-hardware.org/?probe=2da2f6a795) | May 17, 2021 |
| Apple         | MacBookPro8,1               | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Toshiba       | Satellite L70-B             | [aba62024a7](https://linux-hardware.org/?probe=aba62024a7) | May 15, 2021 |
| Sony          | VPCSB1V9E                   | [5682d68364](https://linux-hardware.org/?probe=5682d68364) | May 14, 2021 |
| Samsung       | R520/R522/R620              | [2216d5b0b1](https://linux-hardware.org/?probe=2216d5b0b1) | May 14, 2021 |
| Samsung       | R520/R522/R620              | [b724b0cc62](https://linux-hardware.org/?probe=b724b0cc62) | May 14, 2021 |
| Lenovo        | ThinkPad X240 20AMS2P400    | [9f6e7024d4](https://linux-hardware.org/?probe=9f6e7024d4) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | [d044706f11](https://linux-hardware.org/?probe=d044706f11) | May 13, 2021 |
| Lenovo        | G40-30 80FY                 | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | [25eb899222](https://linux-hardware.org/?probe=25eb899222) | May 12, 2021 |
| Unknown       | Unknown                     | [a54c655ae8](https://linux-hardware.org/?probe=a54c655ae8) | May 12, 2021 |
| Packard Be... | EasyNote MH35               | [b755c5449a](https://linux-hardware.org/?probe=b755c5449a) | May 11, 2021 |
| IBM           | ThinkPad Z60m 25303JM       | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [0b34a1f92d](https://linux-hardware.org/?probe=0b34a1f92d) | May 04, 2021 |
| HP            | Laptop 15-da0xxx            | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| HP            | Notebook                    | [ca99bba8dc](https://linux-hardware.org/?probe=ca99bba8dc) | May 02, 2021 |
| Lenovo        | 100-14IBY 80R7              | [61af9638d2](https://linux-hardware.org/?probe=61af9638d2) | Apr 30, 2021 |
| LG Electro... | S425-L.BC22P1               | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| Lenovo        | G460 20041                  | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| ASUSTek       | X102BA                      | [de8b267423](https://linux-hardware.org/?probe=de8b267423) | Apr 25, 2021 |
| ASUSTek       | X102BA                      | [c660d95c3f](https://linux-hardware.org/?probe=c660d95c3f) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Dell          | Vostro A90                  | [21b167db8c](https://linux-hardware.org/?probe=21b167db8c) | Apr 25, 2021 |
| HP            | Laptop 15-da0xxx            | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Gateway       | Blade-K8F                   | [13e1a6028e](https://linux-hardware.org/?probe=13e1a6028e) | Apr 24, 2021 |
| Dell          | Inspiron N4020              | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| Intel Clie... | LAPQC71B                    | [272956b140](https://linux-hardware.org/?probe=272956b140) | Apr 20, 2021 |
| Acer          | Aspire V5-123               | [448b0afd35](https://linux-hardware.org/?probe=448b0afd35) | Apr 20, 2021 |
| Lenovo        | Z50-70 20354                | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Apple         | MacBook2,1                  | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [6a22991dbe](https://linux-hardware.org/?probe=6a22991dbe) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | [0a367170ed](https://linux-hardware.org/?probe=0a367170ed) | Apr 17, 2021 |
| HP            | Laptop 15-da0xxx            | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Toshiba       | Satellite L35               | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| LG Electro... | S425-L.BC22P1               | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| HP            | Compaq 6820s                | [551053e9d6](https://linux-hardware.org/?probe=551053e9d6) | Apr 15, 2021 |
| Lenovo        | G460 20041                  | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Dell          | Studio 1555                 | [c161e182c2](https://linux-hardware.org/?probe=c161e182c2) | Apr 14, 2021 |
| Toshiba       | Satellite L450              | [2c5ef0687b](https://linux-hardware.org/?probe=2c5ef0687b) | Apr 13, 2021 |
| HP            | EliteBook 8440p (VV954AV... | [3e0b56daf3](https://linux-hardware.org/?probe=3e0b56daf3) | Apr 12, 2021 |
| ASHI          | Unknown                     | [68a2b34c2f](https://linux-hardware.org/?probe=68a2b34c2f) | Apr 12, 2021 |
| HP            | ProBook 6560b               | [8c2a2cfdef](https://linux-hardware.org/?probe=8c2a2cfdef) | Apr 12, 2021 |
| Toshiba       | Satellite L40               | [0f6ed90100](https://linux-hardware.org/?probe=0f6ed90100) | Apr 11, 2021 |
| HP            | Laptop 15s-eq1xxx           | [530be6ce7b](https://linux-hardware.org/?probe=530be6ce7b) | Apr 08, 2021 |
| Acer          | Aspire 5715Z                | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| GTZS          | Unknown                     | [5600074bc0](https://linux-hardware.org/?probe=5600074bc0) | Apr 07, 2021 |
| Samsung       | R520/R522/R620              | [a7f2749d3b](https://linux-hardware.org/?probe=a7f2749d3b) | Apr 06, 2021 |
| Toshiba       | Satellite C70D-B            | [f3e45414fa](https://linux-hardware.org/?probe=f3e45414fa) | Apr 04, 2021 |
| Toshiba       | Satellite C70D-B            | [eacca5eceb](https://linux-hardware.org/?probe=eacca5eceb) | Apr 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [db0eb79b4e](https://linux-hardware.org/?probe=db0eb79b4e) | Mar 31, 2021 |
| ASUSTek       | 1005PE                      | [d75411e5b3](https://linux-hardware.org/?probe=d75411e5b3) | Mar 30, 2021 |
| Lenovo        | IdeaPad Z580                | [6224897fde](https://linux-hardware.org/?probe=6224897fde) | Mar 29, 2021 |
| Toshiba       | Satellite L70-B             | [4f1445876a](https://linux-hardware.org/?probe=4f1445876a) | Mar 27, 2021 |
| Toshiba       | Satellite A200              | [b477c99ab7](https://linux-hardware.org/?probe=b477c99ab7) | Mar 27, 2021 |
| Dell          | Vostro 5470                 | [c9dfbce9bd](https://linux-hardware.org/?probe=c9dfbce9bd) | Mar 26, 2021 |
| ASUSTek       | K45VD                       | [74592068ee](https://linux-hardware.org/?probe=74592068ee) | Mar 25, 2021 |
| Dell          | Latitude D810               | [ca3886900f](https://linux-hardware.org/?probe=ca3886900f) | Mar 25, 2021 |
| Toshiba       | Satellite L70-B             | [961ef41a18](https://linux-hardware.org/?probe=961ef41a18) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | [82480a0f24](https://linux-hardware.org/?probe=82480a0f24) | Mar 21, 2021 |
| Lenovo        | S10-3                       | [42884278c4](https://linux-hardware.org/?probe=42884278c4) | Mar 19, 2021 |
| Dell          | System XPS 15Z              | [cb1bcbb365](https://linux-hardware.org/?probe=cb1bcbb365) | Mar 18, 2021 |
| Acer          | Aspire A315-57G             | [4235b59b38](https://linux-hardware.org/?probe=4235b59b38) | Mar 17, 2021 |
| Acer          | Aspire A315-57G             | [4b3b196273](https://linux-hardware.org/?probe=4b3b196273) | Mar 17, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| HP            | EliteBook 8460p             | [821bcfc074](https://linux-hardware.org/?probe=821bcfc074) | Mar 09, 2021 |
| HP            | EliteBook 8460p             | [47a0bdcb00](https://linux-hardware.org/?probe=47a0bdcb00) | Mar 08, 2021 |
| ASUSTek       | P53E                        | [3aacf8a497](https://linux-hardware.org/?probe=3aacf8a497) | Mar 07, 2021 |
| IBM           | 2647KNG                     | [65d3c4c3c2](https://linux-hardware.org/?probe=65d3c4c3c2) | Mar 07, 2021 |
| IBM           | 2647KNG                     | [e4d4761cfe](https://linux-hardware.org/?probe=e4d4761cfe) | Mar 07, 2021 |
| Dell          | Vostro 3700                 | [0b9b8232f9](https://linux-hardware.org/?probe=0b9b8232f9) | Mar 05, 2021 |
| Dell          | Inspiron N5010              | [8273ed53f3](https://linux-hardware.org/?probe=8273ed53f3) | Mar 04, 2021 |
| HP            | Compaq Presario CQ60        | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| Dell          | Inspiron 1012               | [e66eef020e](https://linux-hardware.org/?probe=e66eef020e) | Mar 03, 2021 |
| Toshiba       | Satellite A135              | [05bbae8a9c](https://linux-hardware.org/?probe=05bbae8a9c) | Mar 02, 2021 |
| MSI           | MS-1453                     | [2be581dfbb](https://linux-hardware.org/?probe=2be581dfbb) | Mar 02, 2021 |
| MSI           | MS-1453                     | [bfaf417259](https://linux-hardware.org/?probe=bfaf417259) | Mar 02, 2021 |
| Toshiba       | Satellite A135              | [1986fa7acf](https://linux-hardware.org/?probe=1986fa7acf) | Mar 02, 2021 |
| Toshiba       | Satellite A660              | [70166b0f32](https://linux-hardware.org/?probe=70166b0f32) | Mar 01, 2021 |
| Lenovo        | S10-3                       | [6d4f0001a3](https://linux-hardware.org/?probe=6d4f0001a3) | Mar 01, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Acer          | Aspire 5610                 | [1cac0acc28](https://linux-hardware.org/?probe=1cac0acc28) | Feb 25, 2021 |
| Itautec       | Infoway w7430               | [72a0d46cbd](https://linux-hardware.org/?probe=72a0d46cbd) | Feb 25, 2021 |
| Timi          | TM1612                      | [517a0ea812](https://linux-hardware.org/?probe=517a0ea812) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [c8fa1fd6d2](https://linux-hardware.org/?probe=c8fa1fd6d2) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [bda750c182](https://linux-hardware.org/?probe=bda750c182) | Feb 23, 2021 |
| Dell          | Vostro 3700                 | [1063468eed](https://linux-hardware.org/?probe=1063468eed) | Feb 21, 2021 |
| Dell          | Vostro 3700                 | [234fac5997](https://linux-hardware.org/?probe=234fac5997) | Feb 21, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | [e79cbcdc53](https://linux-hardware.org/?probe=e79cbcdc53) | Feb 20, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | [eaeef8bb7b](https://linux-hardware.org/?probe=eaeef8bb7b) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| Dell          | Inspiron 1525               | [eeabc1752d](https://linux-hardware.org/?probe=eeabc1752d) | Feb 15, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [95b0ea2335](https://linux-hardware.org/?probe=95b0ea2335) | Feb 15, 2021 |
| HP            | Spectre Laptop 13-af0xx     | [e40f1f67bd](https://linux-hardware.org/?probe=e40f1f67bd) | Feb 15, 2021 |
| Dell          | Inspiron 15-3565            | [7c39aa2965](https://linux-hardware.org/?probe=7c39aa2965) | Feb 14, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [0f15feb522](https://linux-hardware.org/?probe=0f15feb522) | Feb 13, 2021 |
| HP            | ProBook 440 G6              | [715d525514](https://linux-hardware.org/?probe=715d525514) | Feb 07, 2021 |
| HP            | ProBook 440 G7              | [4fd36e0cb3](https://linux-hardware.org/?probe=4fd36e0cb3) | Feb 07, 2021 |
| Unknown       | Unknown                     | [bcad30556a](https://linux-hardware.org/?probe=bcad30556a) | Feb 07, 2021 |
| HP            | ProBook 440 G6              | [f943690f6e](https://linux-hardware.org/?probe=f943690f6e) | Feb 07, 2021 |
| HP            | Pavilion g7                 | [5151e90c72](https://linux-hardware.org/?probe=5151e90c72) | Feb 06, 2021 |
| HP            | G42                         | [b9fbeca924](https://linux-hardware.org/?probe=b9fbeca924) | Feb 05, 2021 |
| HP            | Compaq 6715b (GP690US#AB... | [e77dbfe4a6](https://linux-hardware.org/?probe=e77dbfe4a6) | Feb 05, 2021 |
| ASUSTek       | GL553VD                     | [51102bc7a6](https://linux-hardware.org/?probe=51102bc7a6) | Feb 04, 2021 |
| HP            | Pavilion dv6000 (RP154UA... | [44347b7399](https://linux-hardware.org/?probe=44347b7399) | Jan 31, 2021 |
| Lenovo        | ThinkPad L460 20FVS20700    | [e456ebd9cc](https://linux-hardware.org/?probe=e456ebd9cc) | Jan 29, 2021 |
| HP            | Notebook                    | [c83f3fcce6](https://linux-hardware.org/?probe=c83f3fcce6) | Jan 27, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [c654b7b4ad](https://linux-hardware.org/?probe=c654b7b4ad) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [20f7e526b4](https://linux-hardware.org/?probe=20f7e526b4) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| Samsung       | RV415/RV515                 | [8cf59ea427](https://linux-hardware.org/?probe=8cf59ea427) | Jan 23, 2021 |
| Apple         | MacBookPro10,2              | [19b2ebc706](https://linux-hardware.org/?probe=19b2ebc706) | Jan 22, 2021 |
| Dell          | Latitude 3440               | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| ASUSTek       | K53SD                       | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| HP            | ProBook 6360b               | [3e3cda2a19](https://linux-hardware.org/?probe=3e3cda2a19) | Jan 19, 2021 |
| Lenovo        | IdeaPad Y550 4186           | [d6ae69ca34](https://linux-hardware.org/?probe=d6ae69ca34) | Jan 17, 2021 |
| Toshiba       | Satellite A205              | [57f9413b16](https://linux-hardware.org/?probe=57f9413b16) | Jan 16, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| HP            | Pavilion g6                 | [23360e9a39](https://linux-hardware.org/?probe=23360e9a39) | Jan 12, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | [1f7fadda6e](https://linux-hardware.org/?probe=1f7fadda6e) | Jan 10, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [3aca8223d6](https://linux-hardware.org/?probe=3aca8223d6) | Jan 09, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [9764fca96a](https://linux-hardware.org/?probe=9764fca96a) | Jan 08, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [01626f040a](https://linux-hardware.org/?probe=01626f040a) | Jan 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [1bf71bd97d](https://linux-hardware.org/?probe=1bf71bd97d) | Jan 04, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [266231dab8](https://linux-hardware.org/?probe=266231dab8) | Jan 04, 2021 |
| Sony          | VPCYB35AL                   | [f82ea2b0dc](https://linux-hardware.org/?probe=f82ea2b0dc) | Jan 03, 2021 |
| Lenovo        | G50-45 80E3                 | [65ed0bcd53](https://linux-hardware.org/?probe=65ed0bcd53) | Jan 02, 2021 |
| Positivo      | S14CT01                     | [2b0f53fc1a](https://linux-hardware.org/?probe=2b0f53fc1a) | Jan 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [752fb8d0c7](https://linux-hardware.org/?probe=752fb8d0c7) | Dec 25, 2020 |
| Sony          | VPCYB35AL                   | [490e3a1b0a](https://linux-hardware.org/?probe=490e3a1b0a) | Dec 23, 2020 |
| Fujitsu       | FMVNFA50                    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| HP            | Pavilion TS 15              | [aea4de88ed](https://linux-hardware.org/?probe=aea4de88ed) | Dec 22, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | [0377183ebd](https://linux-hardware.org/?probe=0377183ebd) | Dec 20, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | [17467ac4ff](https://linux-hardware.org/?probe=17467ac4ff) | Dec 20, 2020 |
| Toshiba       | Satellite C55D-A            | [f29fb73181](https://linux-hardware.org/?probe=f29fb73181) | Dec 20, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8402e6dc04](https://linux-hardware.org/?probe=8402e6dc04) | Dec 18, 2020 |
| Acer          | Aspire 4720Z                | [88bd8075b2](https://linux-hardware.org/?probe=88bd8075b2) | Dec 16, 2020 |
| Acer          | Aspire 4720Z                | [93cfeab463](https://linux-hardware.org/?probe=93cfeab463) | Dec 16, 2020 |
| Sony          | VGN-S5XP_B                  | [50c6c9d78a](https://linux-hardware.org/?probe=50c6c9d78a) | Dec 15, 2020 |
| ASUSTek       | GL553VD                     | [8cf11c15f8](https://linux-hardware.org/?probe=8cf11c15f8) | Dec 13, 2020 |
| ASUSTek       | K53SD                       | [96067d7a81](https://linux-hardware.org/?probe=96067d7a81) | Dec 13, 2020 |
| Toshiba       | NB510                       | [41d6c29f97](https://linux-hardware.org/?probe=41d6c29f97) | Dec 13, 2020 |
| Gateway       | NE56R                       | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| Acer          | Aspire 5735                 | [8e251a6942](https://linux-hardware.org/?probe=8e251a6942) | Dec 10, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WP0... | [6ee5c7543b](https://linux-hardware.org/?probe=6ee5c7543b) | Dec 10, 2020 |
| ASUSTek       | X58L                        | [a7fd194aaa](https://linux-hardware.org/?probe=a7fd194aaa) | Dec 07, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | [80ecb8f763](https://linux-hardware.org/?probe=80ecb8f763) | Dec 06, 2020 |
| Lenovo        | IdeaPad Z580                | [f31b40572a](https://linux-hardware.org/?probe=f31b40572a) | Dec 02, 2020 |
| Gigabyte      | W466U                       | [527d2ea4da](https://linux-hardware.org/?probe=527d2ea4da) | Nov 30, 2020 |
| Panasonic     | CF-52PGNBE2M                | [e6e31de556](https://linux-hardware.org/?probe=e6e31de556) | Nov 28, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | [503449ba47](https://linux-hardware.org/?probe=503449ba47) | Nov 27, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | [f45a6362f7](https://linux-hardware.org/?probe=f45a6362f7) | Nov 27, 2020 |
| HP            | Presario F700 (KA698EA#A... | [19fd9647b4](https://linux-hardware.org/?probe=19fd9647b4) | Nov 23, 2020 |
| HP            | Presario F700 (KA698EA#A... | [b46ffd3c2e](https://linux-hardware.org/?probe=b46ffd3c2e) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| LG Electro... | C400-G.BG21P1               | [033a9d8cd0](https://linux-hardware.org/?probe=033a9d8cd0) | Nov 19, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [bb11d08947](https://linux-hardware.org/?probe=bb11d08947) | Nov 19, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [4f73e063d1](https://linux-hardware.org/?probe=4f73e063d1) | Nov 19, 2020 |
| HP            | Pavilion TS 11              | [a71dfc4983](https://linux-hardware.org/?probe=a71dfc4983) | Nov 19, 2020 |
| HP            | ProBook 455 G7              | [86e6b8d3b3](https://linux-hardware.org/?probe=86e6b8d3b3) | Nov 18, 2020 |
| Positivo      | S14BW01                     | [13fed8ca27](https://linux-hardware.org/?probe=13fed8ca27) | Nov 17, 2020 |
| HP            | EliteBook 2570p             | [3d005c24b6](https://linux-hardware.org/?probe=3d005c24b6) | Nov 17, 2020 |
| Gateway       | NE56R                       | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| HP            | ProBook 4720s               | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| Dell          | Inspiron 5423               | [3bd134ed30](https://linux-hardware.org/?probe=3bd134ed30) | Nov 11, 2020 |
| Unknown       | Unknown                     | [5ecd7c84ac](https://linux-hardware.org/?probe=5ecd7c84ac) | Nov 09, 2020 |
| Unknown       | Unknown                     | [abc04e2dfd](https://linux-hardware.org/?probe=abc04e2dfd) | Nov 09, 2020 |
| HP            | Unknown                     | [1cee50e485](https://linux-hardware.org/?probe=1cee50e485) | Nov 07, 2020 |
| Sony          | VGN-S5XP_B                  | [62453951ca](https://linux-hardware.org/?probe=62453951ca) | Nov 06, 2020 |
| Apple         | MacBookPro10,2              | [20951f6ce6](https://linux-hardware.org/?probe=20951f6ce6) | Nov 05, 2020 |
| Samsung       | SX11S                       | [7946db3be4](https://linux-hardware.org/?probe=7946db3be4) | Nov 05, 2020 |
| Samsung       | R530/R730/P530              | [f83b2806d0](https://linux-hardware.org/?probe=f83b2806d0) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| HP            | 650                         | [d1e41ec5c0](https://linux-hardware.org/?probe=d1e41ec5c0) | Nov 03, 2020 |
| Acer          | AOD257                      | [a45ddcc3ab](https://linux-hardware.org/?probe=a45ddcc3ab) | Nov 03, 2020 |
| Acer          | AOD257                      | [3daaf2fdad](https://linux-hardware.org/?probe=3daaf2fdad) | Nov 02, 2020 |
| Samsung       | RV408/RV508                 | [208f929309](https://linux-hardware.org/?probe=208f929309) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| ASUSTek       | E200HA                      | [7fd48df4aa](https://linux-hardware.org/?probe=7fd48df4aa) | Oct 31, 2020 |
| Lenovo        | 100-14IBY 80R7              | [48cb3a624d](https://linux-hardware.org/?probe=48cb3a624d) | Oct 31, 2020 |
| Fujitsu Si... | AMILO Li 2727               | [3e90cc2ba4](https://linux-hardware.org/?probe=3e90cc2ba4) | Oct 31, 2020 |
| Samsung       | N150P/N210P/N220P           | [986ac8d550](https://linux-hardware.org/?probe=986ac8d550) | Oct 30, 2020 |
| Toshiba       | Satellite L305              | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Dell          | Inspiron 5759               | [a9f65003ad](https://linux-hardware.org/?probe=a9f65003ad) | Oct 29, 2020 |
| Samsung       | R530/R730/P530              | [855274d6b0](https://linux-hardware.org/?probe=855274d6b0) | Oct 29, 2020 |
| Notebook      | W740SU                      | [cd23f8c64d](https://linux-hardware.org/?probe=cd23f8c64d) | Oct 28, 2020 |
| Alienware     | 13 R3                       | [c0fc10a320](https://linux-hardware.org/?probe=c0fc10a320) | Oct 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS8CH0... | [bd938bf5fd](https://linux-hardware.org/?probe=bd938bf5fd) | Oct 28, 2020 |
| Positivo      | H14BT58                     | [84c73b4beb](https://linux-hardware.org/?probe=84c73b4beb) | Oct 27, 2020 |
| Itautec       | Infoway                     | [b67c3f6870](https://linux-hardware.org/?probe=b67c3f6870) | Oct 27, 2020 |
| MSI           | U180                        | [7b3f357ff5](https://linux-hardware.org/?probe=7b3f357ff5) | Oct 26, 2020 |
| Toshiba       | Satellite L30               | [0504cfe362](https://linux-hardware.org/?probe=0504cfe362) | Oct 26, 2020 |
| Lenovo        | G575 4383                   | [43b5c51358](https://linux-hardware.org/?probe=43b5c51358) | Oct 25, 2020 |
| Acer          | Aspire F5-573               | [60b785b9cf](https://linux-hardware.org/?probe=60b785b9cf) | Oct 25, 2020 |
| Acer          | Extensa 4620                | [62e829d249](https://linux-hardware.org/?probe=62e829d249) | Oct 22, 2020 |
| Notebook      | W54_55SU1,SUW               | [9655c9ef29](https://linux-hardware.org/?probe=9655c9ef29) | Oct 21, 2020 |
| HP            | Presario V5000 (RE317EA#... | [87b9f12d09](https://linux-hardware.org/?probe=87b9f12d09) | Oct 19, 2020 |
| HP            | Presario V5000 (RE317EA#... | [e09f71e34f](https://linux-hardware.org/?probe=e09f71e34f) | Oct 19, 2020 |
| Acer          | Aspire E1-532P              | [95778c93aa](https://linux-hardware.org/?probe=95778c93aa) | Oct 18, 2020 |
| HP            | Pavilion zd8000 (EL017EA... | [944d295a6b](https://linux-hardware.org/?probe=944d295a6b) | Oct 16, 2020 |
| Toshiba       | Satellite L840              | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| Acer          | Extensa 4620                | [dd858548d7](https://linux-hardware.org/?probe=dd858548d7) | Oct 15, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | [a422be5fc0](https://linux-hardware.org/?probe=a422be5fc0) | Oct 15, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | [1717667731](https://linux-hardware.org/?probe=1717667731) | Oct 13, 2020 |
| LG Electro... | C400-G.BG21P1               | [feb6bd4cac](https://linux-hardware.org/?probe=feb6bd4cac) | Oct 13, 2020 |
| LAMINA        | T-1012B NORD                | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| Google        | Wolf                        | [0ebdfebf96](https://linux-hardware.org/?probe=0ebdfebf96) | Oct 10, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | [03d64c9c3d](https://linux-hardware.org/?probe=03d64c9c3d) | Oct 10, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | [5171d8bc33](https://linux-hardware.org/?probe=5171d8bc33) | Oct 08, 2020 |
| HP            | Pavilion dv6                | [0d0a5ac639](https://linux-hardware.org/?probe=0d0a5ac639) | Oct 07, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | [5e75a35a7d](https://linux-hardware.org/?probe=5e75a35a7d) | Oct 07, 2020 |
| HP            | Unknown                     | [6ff5164672](https://linux-hardware.org/?probe=6ff5164672) | Oct 07, 2020 |
| HP            | Unknown                     | [3815163813](https://linux-hardware.org/?probe=3815163813) | Oct 06, 2020 |
| Dell          | Latitude D630               | [df80a0678a](https://linux-hardware.org/?probe=df80a0678a) | Oct 04, 2020 |
| HP            | Laptop 15-da2xxx            | [a071c6ca32](https://linux-hardware.org/?probe=a071c6ca32) | Sep 30, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | [adb08b74c2](https://linux-hardware.org/?probe=adb08b74c2) | Sep 28, 2020 |
| Panasonic     | CF-31JAGAX1M                | [50fe0189f0](https://linux-hardware.org/?probe=50fe0189f0) | Sep 27, 2020 |
| ASUSTek       | X202EP                      | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Dell          | Inspiron 1440               | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Fujitsu       | LIFEBOOK P702               | [4f2bb45d77](https://linux-hardware.org/?probe=4f2bb45d77) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57e9fe3f34](https://linux-hardware.org/?probe=57e9fe3f34) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [2c253a5689](https://linux-hardware.org/?probe=2c253a5689) | Sep 23, 2020 |
| Samsung       | N230                        | [d4ba29fa0c](https://linux-hardware.org/?probe=d4ba29fa0c) | Sep 23, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [d62d875657](https://linux-hardware.org/?probe=d62d875657) | Sep 22, 2020 |
| Samsung       | N230                        | [786e9275d0](https://linux-hardware.org/?probe=786e9275d0) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [cb4d6ae384](https://linux-hardware.org/?probe=cb4d6ae384) | Sep 22, 2020 |
| Apple         | MacBook3,1                  | [900daa65d7](https://linux-hardware.org/?probe=900daa65d7) | Sep 20, 2020 |
| Fujitsu       | FMVA05008                   | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| Lenovo        | 3000 N200 0769ALU           | [16fb38706f](https://linux-hardware.org/?probe=16fb38706f) | Sep 17, 2020 |
| ASUSTek       | 1015PE                      | [9328bb0c6a](https://linux-hardware.org/?probe=9328bb0c6a) | Sep 16, 2020 |
| ASUSTek       | X202EP                      | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [bb9ff1e41f](https://linux-hardware.org/?probe=bb9ff1e41f) | Sep 15, 2020 |
| Sony          | VPCEG25EN                   | [10bd76f50c](https://linux-hardware.org/?probe=10bd76f50c) | Sep 14, 2020 |
| Acer          | Prespa M                    | [4310240814](https://linux-hardware.org/?probe=4310240814) | Sep 13, 2020 |
| Acer          | Prespa M                    | [dc7c7827ea](https://linux-hardware.org/?probe=dc7c7827ea) | Sep 13, 2020 |
| ASUSTek       | F7L                         | [0190224dc8](https://linux-hardware.org/?probe=0190224dc8) | Sep 12, 2020 |
| Dell          | MXG071                      | [5fc63c5480](https://linux-hardware.org/?probe=5fc63c5480) | Sep 12, 2020 |
| Apple         | MacBookPro10,2              | [3bc9d8ad1e](https://linux-hardware.org/?probe=3bc9d8ad1e) | Sep 10, 2020 |
| ASUSTek       | P553UA                      | [fca37591fc](https://linux-hardware.org/?probe=fca37591fc) | Sep 10, 2020 |
| Samsung       | SX11S                       | [de5f3f5244](https://linux-hardware.org/?probe=de5f3f5244) | Sep 10, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | [2cca042481](https://linux-hardware.org/?probe=2cca042481) | Sep 10, 2020 |
| Lenovo        | Y50-70 20378                | [84a053df62](https://linux-hardware.org/?probe=84a053df62) | Sep 09, 2020 |
| Dell          | Latitude E5450              | [d5eebfddb5](https://linux-hardware.org/?probe=d5eebfddb5) | Sep 07, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c2a66820da](https://linux-hardware.org/?probe=c2a66820da) | Sep 06, 2020 |
| Google        | Gandof                      | [6b79edadc5](https://linux-hardware.org/?probe=6b79edadc5) | Sep 04, 2020 |
| HP            | Compaq Presario CQ50        | [18e30a3f69](https://linux-hardware.org/?probe=18e30a3f69) | Sep 02, 2020 |
| Acer          | Aspire ES1-522              | [c5e6143bbd](https://linux-hardware.org/?probe=c5e6143bbd) | Sep 02, 2020 |
| Acer          | Aspire ES1-523              | [e0afac617e](https://linux-hardware.org/?probe=e0afac617e) | Aug 31, 2020 |
| Dell          | XPS 13 9300                 | [121fd4e00e](https://linux-hardware.org/?probe=121fd4e00e) | Aug 30, 2020 |
| Dell          | XPS 13 9300                 | [3a0e9bb81b](https://linux-hardware.org/?probe=3a0e9bb81b) | Aug 30, 2020 |
| Dell          | Inspiron 1440               | [ea7a9a7e0f](https://linux-hardware.org/?probe=ea7a9a7e0f) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | [b7beb93997](https://linux-hardware.org/?probe=b7beb93997) | Aug 28, 2020 |
| Apple         | MacBookPro10,2              | [b5a228d9bf](https://linux-hardware.org/?probe=b5a228d9bf) | Aug 26, 2020 |
| Acer          | Aspire ES1-523              | [b0a8136f20](https://linux-hardware.org/?probe=b0a8136f20) | Aug 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [e95b44a1c2](https://linux-hardware.org/?probe=e95b44a1c2) | Aug 23, 2020 |
| Acer          | Aspire 5735                 | [043232c833](https://linux-hardware.org/?probe=043232c833) | Aug 20, 2020 |
| ASUSTek       | K50C                        | [dd9986741e](https://linux-hardware.org/?probe=dd9986741e) | Aug 19, 2020 |
| HP            | EliteBook 6930p             | [955c527ef0](https://linux-hardware.org/?probe=955c527ef0) | Aug 19, 2020 |
| Acer          | Aspire A315-21              | [72e40559e9](https://linux-hardware.org/?probe=72e40559e9) | Aug 17, 2020 |
| Digibras      | NH4CU03                     | [3ba7006e38](https://linux-hardware.org/?probe=3ba7006e38) | Aug 15, 2020 |
| HP            | ProBook 440 G2              | [18e6bfd3b5](https://linux-hardware.org/?probe=18e6bfd3b5) | Aug 14, 2020 |
| Toshiba       | Satellite C855D             | [ca848be2f0](https://linux-hardware.org/?probe=ca848be2f0) | Aug 12, 2020 |
| Toshiba       | Satellite C855D             | [723c72f289](https://linux-hardware.org/?probe=723c72f289) | Aug 12, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [a8401cc827](https://linux-hardware.org/?probe=a8401cc827) | Aug 12, 2020 |
| Philco        | 14M-W549                    | [d69911bb55](https://linux-hardware.org/?probe=d69911bb55) | Aug 12, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [f8e01e00f5](https://linux-hardware.org/?probe=f8e01e00f5) | Aug 05, 2020 |
| Toshiba       | Satellite L310              | [eba63dd806](https://linux-hardware.org/?probe=eba63dd806) | Aug 03, 2020 |
| Samsung       | N150/N210/N220              | [e15da00326](https://linux-hardware.org/?probe=e15da00326) | Aug 02, 2020 |
| Positivo      | CHT14B                      | [bb848a6069](https://linux-hardware.org/?probe=bb848a6069) | Aug 01, 2020 |
| HP            | 245 G6                      | [eb51696edd](https://linux-hardware.org/?probe=eb51696edd) | Jul 29, 2020 |
| ASUSTek       | K52Je                       | [5e4fd0731b](https://linux-hardware.org/?probe=5e4fd0731b) | Jul 29, 2020 |
| Dell          | Latitude C840               | [5489df545b](https://linux-hardware.org/?probe=5489df545b) | Jul 28, 2020 |
| ASUSTek       | X101CH                      | [92c248f423](https://linux-hardware.org/?probe=92c248f423) | Jul 27, 2020 |
| ASUSTek       | X101CH                      | [a729294016](https://linux-hardware.org/?probe=a729294016) | Jul 27, 2020 |
| Acer          | AO722                       | [75b6a0b9d5](https://linux-hardware.org/?probe=75b6a0b9d5) | Jul 27, 2020 |
| HP            | ProBook 445 G7              | [6507b9ca49](https://linux-hardware.org/?probe=6507b9ca49) | Jul 25, 2020 |
| Acer          | V5-171                      | [1f30ec8b2e](https://linux-hardware.org/?probe=1f30ec8b2e) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | [8b84442168](https://linux-hardware.org/?probe=8b84442168) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | [468608973e](https://linux-hardware.org/?probe=468608973e) | Jul 25, 2020 |
| Acer          | Aspire F5-573               | [af6c0b4c67](https://linux-hardware.org/?probe=af6c0b4c67) | Jul 24, 2020 |
| Positivo      | H14BT58                     | [3cb433c2cc](https://linux-hardware.org/?probe=3cb433c2cc) | Jul 24, 2020 |
| ASUSTek       | 1015BX                      | [5f48c6c53b](https://linux-hardware.org/?probe=5f48c6c53b) | Jul 24, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [3d1f4e7cb8](https://linux-hardware.org/?probe=3d1f4e7cb8) | Jul 21, 2020 |
| Apple         | MacBookPro10,2              | [ee73a556b1](https://linux-hardware.org/?probe=ee73a556b1) | Jul 19, 2020 |
| Apple         | MacBookPro10,2              | [33e46bd029](https://linux-hardware.org/?probe=33e46bd029) | Jul 19, 2020 |
| Dell          | Studio 1555                 | [0d511c045e](https://linux-hardware.org/?probe=0d511c045e) | Jul 16, 2020 |
| Dell          | Latitude D520               | [c41f563801](https://linux-hardware.org/?probe=c41f563801) | Jul 16, 2020 |
| ASUSTek       | GL553VD                     | [448b62138b](https://linux-hardware.org/?probe=448b62138b) | Jul 14, 2020 |
| ASUSTek       | Q302LA                      | [c453eada8f](https://linux-hardware.org/?probe=c453eada8f) | Jul 09, 2020 |
| HP            | Notebook                    | [10cadcd9b6](https://linux-hardware.org/?probe=10cadcd9b6) | Jul 09, 2020 |
| Toshiba       | Satellite C55D-A            | [9e35eb4bff](https://linux-hardware.org/?probe=9e35eb4bff) | Jul 08, 2020 |
| HP            | Pavilion 15                 | [9f54b2c875](https://linux-hardware.org/?probe=9f54b2c875) | Jul 06, 2020 |
| Acer          | Swift SF314-52G             | [8cd6b05831](https://linux-hardware.org/?probe=8cd6b05831) | Jul 03, 2020 |
| HP            | Pavilion dv6000 (RD870AV... | [921ea4c212](https://linux-hardware.org/?probe=921ea4c212) | Jul 03, 2020 |
| Acer          | Aspire ES1-331              | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| HP            | ProBook 450 G6              | [193cbfc862](https://linux-hardware.org/?probe=193cbfc862) | Jun 30, 2020 |
| HP            | Compaq 615                  | [38dc3f0f55](https://linux-hardware.org/?probe=38dc3f0f55) | Jun 29, 2020 |
| Toshiba       | Satellite L20               | [06b394c839](https://linux-hardware.org/?probe=06b394c839) | Jun 27, 2020 |
| Dell          | XPS 13 7390                 | [598acef23f](https://linux-hardware.org/?probe=598acef23f) | Jun 26, 2020 |
| ASUSTek       | 1011PX                      | [868f757bd9](https://linux-hardware.org/?probe=868f757bd9) | Jun 25, 2020 |
| HP            | Compaq 6710b (RM338UT#AB... | [997dd3289c](https://linux-hardware.org/?probe=997dd3289c) | Jun 25, 2020 |
| OEM           | I41SI                       | [04a393c6ca](https://linux-hardware.org/?probe=04a393c6ca) | Jun 25, 2020 |
| HP            | Compaq 615                  | [d24b727a5b](https://linux-hardware.org/?probe=d24b727a5b) | Jun 24, 2020 |
| Acer          | Aspire one                  | [3eefd3d4df](https://linux-hardware.org/?probe=3eefd3d4df) | Jun 23, 2020 |
| Acer          | Aspire one                  | [68e2ee0c29](https://linux-hardware.org/?probe=68e2ee0c29) | Jun 23, 2020 |
| ASUSTek       | K52Je                       | [401a42e02d](https://linux-hardware.org/?probe=401a42e02d) | Jun 21, 2020 |
| HP            | Laptop 15-bw0xx             | [f7cfb3c14a](https://linux-hardware.org/?probe=f7cfb3c14a) | Jun 20, 2020 |
| OEM           | I41SI                       | [900d32d15b](https://linux-hardware.org/?probe=900d32d15b) | Jun 20, 2020 |
| Apple         | MacBookPro8,1               | [93ced4c964](https://linux-hardware.org/?probe=93ced4c964) | Jun 18, 2020 |
| HP            | ProBook 645 G4              | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| Acer          | Aspire A515-51G             | [a612626f7b](https://linux-hardware.org/?probe=a612626f7b) | Jun 16, 2020 |
| HP            | ProBook 645 G4              | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| Dixonsxp      | Unknown                     | [dbbb512dc1](https://linux-hardware.org/?probe=dbbb512dc1) | Jun 11, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [cf72cf6048](https://linux-hardware.org/?probe=cf72cf6048) | Jun 11, 2020 |
| Toshiba       | Satellite L735              | [71df99e435](https://linux-hardware.org/?probe=71df99e435) | Jun 11, 2020 |
| HP            | Compaq Presario C700        | [5473d1a8e3](https://linux-hardware.org/?probe=5473d1a8e3) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | [ad60c0409d](https://linux-hardware.org/?probe=ad60c0409d) | Jun 09, 2020 |
| Acer          | Aspire 5734Z                | [6af54cea15](https://linux-hardware.org/?probe=6af54cea15) | Jun 07, 2020 |
| Samsung       | RV413/RV513                 | [7c9043ca0a](https://linux-hardware.org/?probe=7c9043ca0a) | Jun 04, 2020 |
| Sony          | VGN-P610                    | [950506fe40](https://linux-hardware.org/?probe=950506fe40) | Jun 04, 2020 |
| HP            | Pavilion 15                 | [131d6a40c2](https://linux-hardware.org/?probe=131d6a40c2) | Jun 03, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | [ea9fb1590a](https://linux-hardware.org/?probe=ea9fb1590a) | Jun 03, 2020 |
| Sony          | VGN-P610                    | [6c66c60336](https://linux-hardware.org/?probe=6c66c60336) | Jun 02, 2020 |
| HUAWEI        | KPL-W0X                     | [89038c4214](https://linux-hardware.org/?probe=89038c4214) | Jun 01, 2020 |
| ASUSTek       | K45VM                       | [15c4339e00](https://linux-hardware.org/?probe=15c4339e00) | May 30, 2020 |
| HP            | Pavilion dv5                | [41390482f3](https://linux-hardware.org/?probe=41390482f3) | May 30, 2020 |
| Positivo      | S14CT01                     | [027689152b](https://linux-hardware.org/?probe=027689152b) | May 28, 2020 |
| HP            | Pavilion dv6                | [2431a0aa32](https://linux-hardware.org/?probe=2431a0aa32) | May 28, 2020 |
| ASUSTek       | 1015B                       | [4a7ecd1578](https://linux-hardware.org/?probe=4a7ecd1578) | May 28, 2020 |
| ASUSTek       | 1015B                       | [51f3309bfb](https://linux-hardware.org/?probe=51f3309bfb) | May 28, 2020 |
| Dell          | Latitude C840               | [f56665d93f](https://linux-hardware.org/?probe=f56665d93f) | May 27, 2020 |
| ASUSTek       | 1015B                       | [73d7cd6398](https://linux-hardware.org/?probe=73d7cd6398) | May 27, 2020 |
| ASUSTek       | 1015B                       | [a3759de413](https://linux-hardware.org/?probe=a3759de413) | May 27, 2020 |
| ASUSTek       | 1015B                       | [63b8cdead7](https://linux-hardware.org/?probe=63b8cdead7) | May 27, 2020 |
| Acer          | Aspire E1-531               | [663bfb0664](https://linux-hardware.org/?probe=663bfb0664) | May 27, 2020 |
| ASUSTek       | 1015B                       | [26bdbf2454](https://linux-hardware.org/?probe=26bdbf2454) | May 27, 2020 |
| ASUSTek       | 1015B                       | [cb7235636f](https://linux-hardware.org/?probe=cb7235636f) | May 27, 2020 |
| ASUSTek       | 1015B                       | [0493e9e9bc](https://linux-hardware.org/?probe=0493e9e9bc) | May 27, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [0686c2c434](https://linux-hardware.org/?probe=0686c2c434) | May 25, 2020 |
| HP            | Pavilion dv6                | [d2b5ccc307](https://linux-hardware.org/?probe=d2b5ccc307) | May 25, 2020 |
| Dell          | Latitude D420               | [40458ce50c](https://linux-hardware.org/?probe=40458ce50c) | May 25, 2020 |
| Dell          | Latitude C840               | [94307b80af](https://linux-hardware.org/?probe=94307b80af) | May 22, 2020 |
| Positivo      | Smash                       | [662402d21c](https://linux-hardware.org/?probe=662402d21c) | May 22, 2020 |
| Fujitsu Si... | AMILO Pi 1505               | [f231ceaf4a](https://linux-hardware.org/?probe=f231ceaf4a) | May 21, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | [78df8e8526](https://linux-hardware.org/?probe=78df8e8526) | May 21, 2020 |
| Fujitsu Si... | AMILO Pi 1505               | [4010948e4f](https://linux-hardware.org/?probe=4010948e4f) | May 20, 2020 |
| Dell          | Inspiron MM061              | [bdd3ec7fdf](https://linux-hardware.org/?probe=bdd3ec7fdf) | May 19, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [a68c9e0a74](https://linux-hardware.org/?probe=a68c9e0a74) | May 18, 2020 |
| ASUSTek       | X201E                       | [aa1e3973cf](https://linux-hardware.org/?probe=aa1e3973cf) | May 18, 2020 |
| ASUSTek       | 1001HA                      | [973de18bf0](https://linux-hardware.org/?probe=973de18bf0) | May 17, 2020 |
| ASUSTek       | 1001HA                      | [ec49101a42](https://linux-hardware.org/?probe=ec49101a42) | May 17, 2020 |
| Packard Be... | EN Butterfly s              | [587286fd1b](https://linux-hardware.org/?probe=587286fd1b) | May 17, 2020 |
| ASUSTek       | F5N                         | [19a648832e](https://linux-hardware.org/?probe=19a648832e) | May 15, 2020 |
| Sony          | VGN-NR430E                  | [6e3da2829e](https://linux-hardware.org/?probe=6e3da2829e) | May 15, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | [c0cf69cb37](https://linux-hardware.org/?probe=c0cf69cb37) | May 13, 2020 |
| Positivo      | EC10IS1                     | [b66b7b1fe1](https://linux-hardware.org/?probe=b66b7b1fe1) | May 12, 2020 |
| ASUSTek       | F5N                         | [81878f74de](https://linux-hardware.org/?probe=81878f74de) | May 10, 2020 |
| Toshiba       | NB505                       | [26eaa80c8a](https://linux-hardware.org/?probe=26eaa80c8a) | May 10, 2020 |
| Acer          | Aspire 5742G                | [0e50f534db](https://linux-hardware.org/?probe=0e50f534db) | May 10, 2020 |
| Dixonsxp      | Unknown                     | [7ee061c41d](https://linux-hardware.org/?probe=7ee061c41d) | May 09, 2020 |
| HP            | Pavilion dv2500             | [794202d954](https://linux-hardware.org/?probe=794202d954) | May 08, 2020 |
| Dell          | Latitude D810               | [7391f06281](https://linux-hardware.org/?probe=7391f06281) | May 07, 2020 |
| HP            | Notebook                    | [0cab8a6d17](https://linux-hardware.org/?probe=0cab8a6d17) | May 07, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Dell          | Latitude D810               | [da4ecfc379](https://linux-hardware.org/?probe=da4ecfc379) | May 06, 2020 |
| Dixonsxp      | Unknown                     | [baf1cb6830](https://linux-hardware.org/?probe=baf1cb6830) | May 06, 2020 |
| Clevo         | M540SS Bottom               | [d5e1de02bb](https://linux-hardware.org/?probe=d5e1de02bb) | May 05, 2020 |
| Clevo         | M540SS Bottom               | [84338255ae](https://linux-hardware.org/?probe=84338255ae) | May 05, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Positivo      | Smash                       | [02a9fd0d4a](https://linux-hardware.org/?probe=02a9fd0d4a) | May 03, 2020 |
| Positivo      | Smash                       | [f9734c79af](https://linux-hardware.org/?probe=f9734c79af) | May 03, 2020 |
| Toshiba       | TECRA A3X                   | [52ea725f65](https://linux-hardware.org/?probe=52ea725f65) | May 02, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| Acer          | Extensa 5630                | [2040fe8553](https://linux-hardware.org/?probe=2040fe8553) | Apr 30, 2020 |
| Toshiba       | TECRA A8                    | [6110d010ad](https://linux-hardware.org/?probe=6110d010ad) | Apr 28, 2020 |
| Dell          | Inspiron 1545               | [0fc9a3fc11](https://linux-hardware.org/?probe=0fc9a3fc11) | Apr 28, 2020 |
| Packard Be... | EasyNote_GN45               | [a06ff5e1c7](https://linux-hardware.org/?probe=a06ff5e1c7) | Apr 27, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [1a00b67e81](https://linux-hardware.org/?probe=1a00b67e81) | Apr 27, 2020 |
| Standard      | EF20EA                      | [11882357e0](https://linux-hardware.org/?probe=11882357e0) | Apr 26, 2020 |
| Apple         | MacBookPro9,2               | [74edb3ce25](https://linux-hardware.org/?probe=74edb3ce25) | Apr 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [86e4dd0977](https://linux-hardware.org/?probe=86e4dd0977) | Apr 26, 2020 |
| Toshiba       | Satellite U500              | [cbb92d0bb3](https://linux-hardware.org/?probe=cbb92d0bb3) | Apr 25, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [c194d8e6be](https://linux-hardware.org/?probe=c194d8e6be) | Apr 24, 2020 |
| MSI           | PR200                       | [4da6b718ee](https://linux-hardware.org/?probe=4da6b718ee) | Apr 22, 2020 |
| MSI           | PR200                       | [bd6e464307](https://linux-hardware.org/?probe=bd6e464307) | Apr 22, 2020 |
| Samsung       | 600B4B/600B5B               | [66fdcd74f6](https://linux-hardware.org/?probe=66fdcd74f6) | Apr 22, 2020 |
| HP            | Compaq CQ58                 | [82172cc7b5](https://linux-hardware.org/?probe=82172cc7b5) | Apr 21, 2020 |
| Toshiba       | Satellite Pro S500          | [2acae4110c](https://linux-hardware.org/?probe=2acae4110c) | Apr 20, 2020 |
| Toshiba       | Satellite Pro S500          | [01b278ea81](https://linux-hardware.org/?probe=01b278ea81) | Apr 20, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [6e83174540](https://linux-hardware.org/?probe=6e83174540) | Apr 18, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [878a9628b9](https://linux-hardware.org/?probe=878a9628b9) | Apr 18, 2020 |
| ASUSTek       | K52Je                       | [2954b09134](https://linux-hardware.org/?probe=2954b09134) | Apr 17, 2020 |
| ASUSTek       | K52Je                       | [bd4175ea08](https://linux-hardware.org/?probe=bd4175ea08) | Apr 17, 2020 |
| Toshiba       | NB505                       | [174dd8b4cd](https://linux-hardware.org/?probe=174dd8b4cd) | Apr 16, 2020 |
| HP            | EliteBook 840 G1            | [4998a5a5b5](https://linux-hardware.org/?probe=4998a5a5b5) | Apr 15, 2020 |
| Dell          | Inspiron 13-5378            | [6500bad3f7](https://linux-hardware.org/?probe=6500bad3f7) | Apr 14, 2020 |
| Toshiba       | NB505                       | [a28c9ef432](https://linux-hardware.org/?probe=a28c9ef432) | Apr 12, 2020 |
| HP            | Compaq Presario CQ50        | [6c0d513235](https://linux-hardware.org/?probe=6c0d513235) | Apr 12, 2020 |
| ASUSTek       | A6R                         | [e298b642f1](https://linux-hardware.org/?probe=e298b642f1) | Apr 11, 2020 |
| Ematic        | EW147                       | [ea27684494](https://linux-hardware.org/?probe=ea27684494) | Apr 11, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | [734c5c160a](https://linux-hardware.org/?probe=734c5c160a) | Apr 11, 2020 |
| Ematic        | EW147                       | [a6d2f7cfcf](https://linux-hardware.org/?probe=a6d2f7cfcf) | Apr 11, 2020 |
| Phoenix/Si... | M7X0SU                      | [c86682fc32](https://linux-hardware.org/?probe=c86682fc32) | Apr 11, 2020 |
| ASUSTek       | X550LC                      | [05de338581](https://linux-hardware.org/?probe=05de338581) | Apr 09, 2020 |
| ASUSTek       | 1000H                       | [ee3f7c6ddc](https://linux-hardware.org/?probe=ee3f7c6ddc) | Apr 09, 2020 |
| Toshiba       | NB505                       | [c52e8296ad](https://linux-hardware.org/?probe=c52e8296ad) | Apr 06, 2020 |
| HP            | Pavilion 15                 | [b7c8f5e391](https://linux-hardware.org/?probe=b7c8f5e391) | Apr 05, 2020 |
| HP            | Pavilion 15                 | [812ce15917](https://linux-hardware.org/?probe=812ce15917) | Apr 05, 2020 |
| Apple         | MacBookPro5,5               | [9f7081cc76](https://linux-hardware.org/?probe=9f7081cc76) | Apr 04, 2020 |
| Toshiba       | Satellite Pro S500          | [053784b92f](https://linux-hardware.org/?probe=053784b92f) | Apr 03, 2020 |
| HP            | Pavilion dm1                | [f3ade8b8f4](https://linux-hardware.org/?probe=f3ade8b8f4) | Apr 02, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [b112c2d6c6](https://linux-hardware.org/?probe=b112c2d6c6) | Mar 30, 2020 |
| Dell          | Inspiron MM061              | [d60d4df102](https://linux-hardware.org/?probe=d60d4df102) | Mar 29, 2020 |
| Itautec       | Infoway                     | [6df484929a](https://linux-hardware.org/?probe=6df484929a) | Mar 28, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [daf3f5783d](https://linux-hardware.org/?probe=daf3f5783d) | Mar 27, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [7dee8ed61e](https://linux-hardware.org/?probe=7dee8ed61e) | Mar 26, 2020 |
| Dell          | Inspiron 910                | [5a445b86f5](https://linux-hardware.org/?probe=5a445b86f5) | Mar 26, 2020 |
| Sony          | VGN-CS325J                  | [a2f2fc1b18](https://linux-hardware.org/?probe=a2f2fc1b18) | Mar 25, 2020 |
| ASUSTek       | X550LC                      | [cdcf191c24](https://linux-hardware.org/?probe=cdcf191c24) | Mar 25, 2020 |
| Toshiba       | Satellite A100              | [f7fb11c89f](https://linux-hardware.org/?probe=f7fb11c89f) | Mar 25, 2020 |
| Acer          | Aspire V3-571G              | [be88d1499a](https://linux-hardware.org/?probe=be88d1499a) | Mar 25, 2020 |
| Sony          | VGN-CS325J                  | [628add2bae](https://linux-hardware.org/?probe=628add2bae) | Mar 23, 2020 |
| Sony          | VGN-FE21M                   | [b117ba3f2f](https://linux-hardware.org/?probe=b117ba3f2f) | Mar 22, 2020 |
| Sony          | VGN-CS325J                  | [3eeafc3bdb](https://linux-hardware.org/?probe=3eeafc3bdb) | Mar 22, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [b65f9246d0](https://linux-hardware.org/?probe=b65f9246d0) | Mar 21, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [a02304934f](https://linux-hardware.org/?probe=a02304934f) | Mar 21, 2020 |
| Acer          | Aspire E1-431               | [7a4eb7e049](https://linux-hardware.org/?probe=7a4eb7e049) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | [912c22a4fd](https://linux-hardware.org/?probe=912c22a4fd) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | [3a11fa91b5](https://linux-hardware.org/?probe=3a11fa91b5) | Mar 20, 2020 |
| HP            | Compaq Presario CQ50        | [210babb2ca](https://linux-hardware.org/?probe=210babb2ca) | Mar 19, 2020 |
| Thomson       | NEO14A-4BK64                | [a0cc23a5cf](https://linux-hardware.org/?probe=a0cc23a5cf) | Mar 19, 2020 |
| Thomson       | NEO14A-4BK64                | [38b21006a6](https://linux-hardware.org/?probe=38b21006a6) | Mar 19, 2020 |
| Dell          | Inspiron 910                | [40deae1721](https://linux-hardware.org/?probe=40deae1721) | Mar 18, 2020 |
| Toshiba       | Satellite Pro S500          | [2cdafa2543](https://linux-hardware.org/?probe=2cdafa2543) | Mar 17, 2020 |
| ASUSTek       | 1001PXD                     | [011393aea9](https://linux-hardware.org/?probe=011393aea9) | Mar 12, 2020 |
| ASUSTek       | K43E                        | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | X51R                        | [27bb6f3f14](https://linux-hardware.org/?probe=27bb6f3f14) | Mar 11, 2020 |
| Dell          | Inspiron 910                | [b8ec7ce084](https://linux-hardware.org/?probe=b8ec7ce084) | Mar 10, 2020 |
| Acer          | Aspire ES1-571              | [6fa4f9484a](https://linux-hardware.org/?probe=6fa4f9484a) | Mar 10, 2020 |
| ASUSTek       | K43E                        | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |
| Acer          | Aspire ES1-571              | [7980f53bfc](https://linux-hardware.org/?probe=7980f53bfc) | Mar 10, 2020 |
| Acer          | Aspire 6930G                | [0ec678525f](https://linux-hardware.org/?probe=0ec678525f) | Mar 09, 2020 |
| Dell          | Inspiron 1464               | [d6a38ddcea](https://linux-hardware.org/?probe=d6a38ddcea) | Mar 08, 2020 |
| Sony          | VPCYB15AB                   | [af5e9fd3c4](https://linux-hardware.org/?probe=af5e9fd3c4) | Mar 03, 2020 |
| ASUSTek       | GL553VD                     | [db39fea346](https://linux-hardware.org/?probe=db39fea346) | Mar 02, 2020 |
| Positivo      | Mobile                      | [3dc5b2844f](https://linux-hardware.org/?probe=3dc5b2844f) | Feb 29, 2020 |
| Positivo      | Mobile                      | [6908d01959](https://linux-hardware.org/?probe=6908d01959) | Feb 26, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [108b4a03ac](https://linux-hardware.org/?probe=108b4a03ac) | Feb 26, 2020 |
| Toshiba       | Satellite C650D             | [fff96c147a](https://linux-hardware.org/?probe=fff96c147a) | Feb 20, 2020 |
| Dell          | Latitude D630               | [81239fd39f](https://linux-hardware.org/?probe=81239fd39f) | Feb 19, 2020 |
| ASUSTek       | 1005HA                      | [0f5187ce04](https://linux-hardware.org/?probe=0f5187ce04) | Feb 18, 2020 |
| HP            | Stream Notebook             | [413af6cde9](https://linux-hardware.org/?probe=413af6cde9) | Feb 18, 2020 |
| HP            | Stream Notebook             | [305ee95288](https://linux-hardware.org/?probe=305ee95288) | Feb 18, 2020 |
| HP            | Stream Notebook             | [3cc3c65c80](https://linux-hardware.org/?probe=3cc3c65c80) | Feb 18, 2020 |
| Acer          | AOD257                      | [42c2447bcf](https://linux-hardware.org/?probe=42c2447bcf) | Feb 18, 2020 |
| HP            | Pavilion g6                 | [147eea4e00](https://linux-hardware.org/?probe=147eea4e00) | Feb 17, 2020 |
| Acer          | Aspire 9420                 | [eb72545df3](https://linux-hardware.org/?probe=eb72545df3) | Feb 13, 2020 |
| Acer          | Aspire 9420                 | [7321cd7d41](https://linux-hardware.org/?probe=7321cd7d41) | Feb 13, 2020 |
| Samsung       | 275E4E/275E5E               | [15d64735e6](https://linux-hardware.org/?probe=15d64735e6) | Feb 07, 2020 |
| HP            | EliteBook 8540w             | [064e671b09](https://linux-hardware.org/?probe=064e671b09) | Feb 07, 2020 |
| HP            | EliteBook 840 G1            | [9f00848eda](https://linux-hardware.org/?probe=9f00848eda) | Feb 06, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | [00e62f0a24](https://linux-hardware.org/?probe=00e62f0a24) | Feb 04, 2020 |
| ASUSTek       | GL553VD                     | [c8da6705be](https://linux-hardware.org/?probe=c8da6705be) | Feb 02, 2020 |
| Acer          | Lugano M                    | [312fa4b009](https://linux-hardware.org/?probe=312fa4b009) | Feb 02, 2020 |
| HP            | ProBook 450 G2              | [10e8be6a70](https://linux-hardware.org/?probe=10e8be6a70) | Feb 02, 2020 |
| Acer          | Aspire E1-530               | [0e64af354b](https://linux-hardware.org/?probe=0e64af354b) | Jan 30, 2020 |
| Dell          | Vostro A90                  | [ea2668497d](https://linux-hardware.org/?probe=ea2668497d) | Jan 25, 2020 |
| HP            | Laptop 15s-fq1xxx           | [179223c787](https://linux-hardware.org/?probe=179223c787) | Jan 21, 2020 |
| TrekStor      | Surfbook A13B               | [a5b513e810](https://linux-hardware.org/?probe=a5b513e810) | Jan 18, 2020 |
| ASUSTek       | 1015PN                      | [5619d74a6f](https://linux-hardware.org/?probe=5619d74a6f) | Jan 13, 2020 |
| Acer          | Aspire 5542                 | [aeeb077808](https://linux-hardware.org/?probe=aeeb077808) | Jan 05, 2020 |
| Acer          | Aspire 5542                 | [1458705a5f](https://linux-hardware.org/?probe=1458705a5f) | Jan 04, 2020 |
| Fujitsu       | LIFEBOOK S710               | [b3b0d2e40e](https://linux-hardware.org/?probe=b3b0d2e40e) | Dec 30, 2019 |
| HP            | Pavilion dv7                | [1147f13741](https://linux-hardware.org/?probe=1147f13741) | Dec 30, 2019 |
| Dell          | Studio 1555                 | [4507496780](https://linux-hardware.org/?probe=4507496780) | Dec 29, 2019 |
| HP            | Stream Laptop 11-y0XX       | [aca2eac05b](https://linux-hardware.org/?probe=aca2eac05b) | Dec 29, 2019 |
| Dell          | Studio 1555                 | [9aba9666d7](https://linux-hardware.org/?probe=9aba9666d7) | Dec 28, 2019 |
| HP            | Pavilion 15                 | [98e4efccb2](https://linux-hardware.org/?probe=98e4efccb2) | Dec 24, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | [011ab343ef](https://linux-hardware.org/?probe=011ab343ef) | Dec 22, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | [bb9da61133](https://linux-hardware.org/?probe=bb9da61133) | Dec 21, 2019 |
| Toshiba       | Satellite L20               | [563f05aae7](https://linux-hardware.org/?probe=563f05aae7) | Dec 18, 2019 |
| HP            | Compaq Presario CQ50        | [d672b4583e](https://linux-hardware.org/?probe=d672b4583e) | Dec 15, 2019 |
| HP            | Laptop 14-cm0xxx            | [3a1243a77f](https://linux-hardware.org/?probe=3a1243a77f) | Dec 12, 2019 |
| HP            | Laptop 14-cm0xxx            | [71a8ef2f9c](https://linux-hardware.org/?probe=71a8ef2f9c) | Dec 12, 2019 |
| Dell          | Inspiron MM061              | [74039c6d39](https://linux-hardware.org/?probe=74039c6d39) | Dec 01, 2019 |
| Toshiba       | Satellite Pro S500          | [03ab084bc4](https://linux-hardware.org/?probe=03ab084bc4) | Nov 30, 2019 |
| ASUSTek       | X51RL                       | [2d4367bb57](https://linux-hardware.org/?probe=2d4367bb57) | Nov 29, 2019 |
| Samsung       | 275E4E/275E5E               | [4e229f13aa](https://linux-hardware.org/?probe=4e229f13aa) | Nov 23, 2019 |
| AMI           | Cherry Trail CR             | [fd9a3df2b6](https://linux-hardware.org/?probe=fd9a3df2b6) | Nov 19, 2019 |
| HP            | Laptop 15-bw0xx             | [c4b7195697](https://linux-hardware.org/?probe=c4b7195697) | Nov 18, 2019 |
| Dell          | Inspiron MM061              | [c382fdc34a](https://linux-hardware.org/?probe=c382fdc34a) | Nov 14, 2019 |
| Sony          | SVE14A2V1EW                 | [e80c47963a](https://linux-hardware.org/?probe=e80c47963a) | Nov 12, 2019 |
| Acer          | Aspire V3-571G              | [2e7b8ff7ae](https://linux-hardware.org/?probe=2e7b8ff7ae) | Nov 11, 2019 |
| ASUSTek       | U32U                        | [656773dca2](https://linux-hardware.org/?probe=656773dca2) | Oct 22, 2019 |
| Acer          | Aspire one 1-431            | [33ff5f5399](https://linux-hardware.org/?probe=33ff5f5399) | Jul 14, 2019 |
| ASUSTek       | 1215B                       | [5e3f89149f](https://linux-hardware.org/?probe=5e3f89149f) | Jun 29, 2019 |
| HP            | ProBook 430 G1              | [9be61e9a2d](https://linux-hardware.org/?probe=9be61e9a2d) | Jun 24, 2019 |
| Dell          | Inspiron 5566               | [a8122ef82d](https://linux-hardware.org/?probe=a8122ef82d) | Apr 26, 2019 |
| ASUSTek       | K55VJ                       | [fac5cee3e3](https://linux-hardware.org/?probe=fac5cee3e3) | Apr 05, 2019 |
| Dell          | Inspiron 5566               | [e4dc78de4f](https://linux-hardware.org/?probe=e4dc78de4f) | Mar 28, 2019 |
| HP            | Pavilion Sleekbook 15       | [81ac047bce](https://linux-hardware.org/?probe=81ac047bce) | Mar 10, 2019 |
| HP            | Pavilion Sleekbook 15       | [26ccc6c647](https://linux-hardware.org/?probe=26ccc6c647) | Mar 10, 2019 |
| Acer          | Aspire F5-771G              | [8f2bbcbea8](https://linux-hardware.org/?probe=8f2bbcbea8) | Dec 23, 2018 |
| Toshiba       | Satellite L20               | [409df1d9a6](https://linux-hardware.org/?probe=409df1d9a6) | Oct 30, 2018 |
| Toshiba       | Satellite L300              | [c50c4eed87](https://linux-hardware.org/?probe=c50c4eed87) | Sep 02, 2018 |
| ASUSTek       | X200MA                      | [62851925f7](https://linux-hardware.org/?probe=62851925f7) | Jul 27, 2018 |
| Lenovo        | G580 20150                  | [69369b93d2](https://linux-hardware.org/?probe=69369b93d2) | Jul 09, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lubuntu 20.04   | 233       | 40.95%  |
| Lubuntu 18.04   | 115       | 20.21%  |
| Lubuntu 21.10   | 47        | 8.26%   |
| Lubuntu 19.10   | 43        | 7.56%   |
| Lubuntu 21.04   | 37        | 6.5%    |
| Lubuntu 20.10   | 29        | 5.1%    |
| Lubuntu 22.04   | 27        | 4.75%   |
| Lubuntu 16.04   | 15        | 2.64%   |
| Lubuntu 19.04   | 12        | 2.11%   |
| Lubuntu 18.10   | 6         | 1.05%   |
| Lubuntu         | 3         | 0.53%   |
| Lubuntu 20.04.1 | 1         | 0.18%   |
| Lubuntu 17.10   | 1         | 0.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Lubuntu | 553       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.4.0-42-generic   | 24        | 3.8%    |
| 5.4.0-52-generic   | 15        | 2.37%   |
| 5.3.0-46-generic   | 11        | 1.74%   |
| 5.13.0-28-generic  | 11        | 1.74%   |
| 5.13.0-19-generic  | 11        | 1.74%   |
| 5.11.0-16-generic  | 11        | 1.74%   |
| 5.13.0-40-generic  | 10        | 1.58%   |
| 5.4.0-48-generic   | 9         | 1.42%   |
| 5.4.0-47-generic   | 9         | 1.42%   |
| 5.4.0-26-generic   | 9         | 1.42%   |
| 5.13.0-35-generic  | 9         | 1.42%   |
| 5.4.0-65-generic   | 8         | 1.27%   |
| 5.3.0-18-generic   | 8         | 1.27%   |
| 5.13.0-30-generic  | 8         | 1.27%   |
| 5.11.0-25-generic  | 8         | 1.27%   |
| 4.15.0-112-generic | 8         | 1.27%   |
| 5.4.0-73-generic   | 7         | 1.11%   |
| 5.4.0-40-generic   | 7         | 1.11%   |
| 5.15.0-30-generic  | 7         | 1.11%   |
| 5.8.0-63-generic   | 6         | 0.95%   |
| 5.4.0-72-generic   | 6         | 0.95%   |
| 5.4.0-54-generic   | 6         | 0.95%   |
| 5.4.0-29-generic   | 6         | 0.95%   |
| 5.3.0-51-generic   | 6         | 0.95%   |
| 5.3.0-40-generic   | 6         | 0.95%   |
| 5.15.0-27-generic  | 6         | 0.95%   |
| 5.13.0-22-generic  | 6         | 0.95%   |
| 5.11.0-38-generic  | 6         | 0.95%   |
| 5.11.0-37-generic  | 6         | 0.95%   |
| 4.15.0-96-generic  | 6         | 0.95%   |
| 4.15.0-91-generic  | 6         | 0.95%   |
| 5.8.0-53-generic   | 5         | 0.79%   |
| 5.8.0-48-generic   | 5         | 0.79%   |
| 5.4.0-70-generic   | 5         | 0.79%   |
| 5.4.0-58-generic   | 5         | 0.79%   |
| 5.4.0-56-generic   | 5         | 0.79%   |
| 5.4.0-51-generic   | 5         | 0.79%   |
| 5.4.0-33-generic   | 5         | 0.79%   |
| 5.3.0-42-generic   | 5         | 0.79%   |
| 5.11.0-41-generic  | 5         | 0.79%   |
| 5.11.0-17-generic  | 5         | 0.79%   |
| 5.0.0-36-generic   | 5         | 0.79%   |
| 4.15.0-136-generic | 5         | 0.79%   |
| 4.15.0-101-generic | 5         | 0.79%   |
| 5.8.0-55-generic   | 4         | 0.63%   |
| 5.8.0-49-generic   | 4         | 0.63%   |
| 5.8.0-45-generic   | 4         | 0.63%   |
| 5.8.0-26-generic   | 4         | 0.63%   |
| 5.4.0-89-generic   | 4         | 0.63%   |
| 5.4.0-59-generic   | 4         | 0.63%   |
| 5.4.0-45-generic   | 4         | 0.63%   |
| 5.4.0-37-generic   | 4         | 0.63%   |
| 5.3.0-64-generic   | 4         | 0.63%   |
| 5.3.0-28-generic   | 4         | 0.63%   |
| 5.3.0-24-generic   | 4         | 0.63%   |
| 5.15.0-25-generic  | 4         | 0.63%   |
| 5.11.0-40-generic  | 4         | 0.63%   |
| 5.11.0-27-generic  | 4         | 0.63%   |
| 5.0.0-38-generic   | 4         | 0.63%   |
| 5.0.0-37-generic   | 4         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.4.0    | 185       | 32.06%  |
| 5.13.0   | 71        | 12.31%  |
| 4.15.0   | 71        | 12.31%  |
| 5.11.0   | 65        | 11.27%  |
| 5.3.0    | 63        | 10.92%  |
| 5.8.0    | 56        | 9.71%   |
| 5.15.0   | 27        | 4.68%   |
| 5.0.0    | 16        | 2.77%   |
| 4.18.0   | 7         | 1.21%   |
| 4.4.0    | 4         | 0.69%   |
| 4.13.0   | 2         | 0.35%   |
| 5.9.0    | 1         | 0.17%   |
| 5.7.9    | 1         | 0.17%   |
| 5.6.0    | 1         | 0.17%   |
| 5.5.2    | 1         | 0.17%   |
| 5.18.0   | 1         | 0.17%   |
| 5.16.0   | 1         | 0.17%   |
| 5.10.0   | 1         | 0.17%   |
| 4.14.225 | 1         | 0.17%   |
| 4.13.9   | 1         | 0.17%   |
| 4.10.0   | 1         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 185       | 32.06%  |
| 5.13    | 71        | 12.31%  |
| 4.15    | 71        | 12.31%  |
| 5.11    | 65        | 11.27%  |
| 5.3     | 63        | 10.92%  |
| 5.8     | 56        | 9.71%   |
| 5.15    | 27        | 4.68%   |
| 5.0     | 16        | 2.77%   |
| 4.18    | 7         | 1.21%   |
| 4.4     | 4         | 0.69%   |
| 4.13    | 3         | 0.52%   |
| 5.9     | 1         | 0.17%   |
| 5.7     | 1         | 0.17%   |
| 5.6     | 1         | 0.17%   |
| 5.5     | 1         | 0.17%   |
| 5.18    | 1         | 0.17%   |
| 5.16    | 1         | 0.17%   |
| 5.10    | 1         | 0.17%   |
| 4.14    | 1         | 0.17%   |
| 4.10    | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 480       | 86.8%   |
| i686   | 73        | 13.2%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| LXQt            | 408       | 73.51%  |
| LXDE            | 113       | 20.36%  |
| Unknown         | 15        | 2.7%    |
| Openbox         | 5         | 0.9%    |
| GNOME           | 5         | 0.9%    |
| KDE5            | 2         | 0.36%   |
| Cinnamon        | 2         | 0.36%   |
| MATE            | 1         | 0.18%   |
| Lubuntu         | 1         | 0.18%   |
| KDE             | 1         | 0.18%   |
| GNOME Flashback | 1         | 0.18%   |
| Budgie          | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 541       | 97.48%  |
| Tty     | 11        | 1.98%   |
| Wayland | 3         | 0.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 229       | 40.82%  |
| Unknown | 225       | 40.11%  |
| TDM     | 43        | 7.66%   |
| LightDM | 41        | 7.31%   |
| GDM     | 20        | 3.57%   |
| GDM3    | 2         | 0.36%   |
| XDM     | 1         | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 150       | 26.98%  |
| pt_BR   | 52        | 9.35%   |
| fr_FR   | 45        | 8.09%   |
| it_IT   | 36        | 6.47%   |
| en_GB   | 29        | 5.22%   |
| de_DE   | 27        | 4.86%   |
| ru_RU   | 20        | 3.6%    |
| pl_PL   | 20        | 3.6%    |
| C       | 19        | 3.42%   |
| Unknown | 17        | 3.06%   |
| es_ES   | 14        | 2.52%   |
| en_AU   | 11        | 1.98%   |
| en_CA   | 10        | 1.8%    |
| tr_TR   | 7         | 1.26%   |
| es_AR   | 7         | 1.26%   |
| en_IN   | 7         | 1.26%   |
| nl_NL   | 5         | 0.9%    |
| hu_HU   | 5         | 0.9%    |
| es_CR   | 5         | 0.9%    |
| en_IE   | 5         | 0.9%    |
| cs_CZ   | 5         | 0.9%    |
| fr_BE   | 4         | 0.72%   |
| es_MX   | 4         | 0.72%   |
| es_CL   | 4         | 0.72%   |
| nl_BE   | 3         | 0.54%   |
| ja_JP   | 3         | 0.54%   |
| fr_CH   | 3         | 0.54%   |
| zh_TW   | 2         | 0.36%   |
| id_ID   | 2         | 0.36%   |
| es_VE   | 2         | 0.36%   |
| es_UY   | 2         | 0.36%   |
| es_PE   | 2         | 0.36%   |
| es_CO   | 2         | 0.36%   |
| en_SG   | 2         | 0.36%   |
| en_NZ   | 2         | 0.36%   |
| el_GR   | 2         | 0.36%   |
| zh_CN   | 1         | 0.18%   |
| uk_UA   | 1         | 0.18%   |
| sr_RS   | 1         | 0.18%   |
| ru_UA   | 1         | 0.18%   |
| ro_RO   | 1         | 0.18%   |
| pt_PT   | 1         | 0.18%   |
| nb_NO   | 1         | 0.18%   |
| lt_LT   | 1         | 0.18%   |
| ko_KR   | 1         | 0.18%   |
| fr_CA   | 1         | 0.18%   |
| fi_FI   | 1         | 0.18%   |
| fa_IR   | 1         | 0.18%   |
| es_DO   | 1         | 0.18%   |
| en_ZM   | 1         | 0.18%   |
| en_ZA   | 1         | 0.18%   |
| en_PH   | 1         | 0.18%   |
| en_DE   | 1         | 0.18%   |
| en_CM   | 1         | 0.18%   |
| en_CH   | 1         | 0.18%   |
| de_AT   | 1         | 0.18%   |
| bg_BG   | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 353       | 63.04%  |
| EFI  | 207       | 36.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 517       | 93.32%  |
| Overlay | 19        | 3.43%   |
| Btrfs   | 8         | 1.44%   |
| Aufs    | 5         | 0.9%    |
| Unknown | 3         | 0.54%   |
| Ext3    | 2         | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 275       | 49.37%  |
| GPT     | 153       | 27.47%  |
| MBR     | 129       | 23.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 512       | 91.76%  |
| Yes       | 46        | 8.24%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 422       | 75.76%  |
| Yes       | 135       | 24.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 119       | 21.52%  |
| Lenovo                      | 68        | 12.3%   |
| ASUSTek Computer            | 60        | 10.85%  |
| Dell                        | 59        | 10.67%  |
| Acer                        | 50        | 9.04%   |
| Toshiba                     | 37        | 6.69%   |
| Samsung Electronics         | 22        | 3.98%   |
| Sony                        | 16        | 2.89%   |
| Apple                       | 15        | 2.71%   |
| Google                      | 12        | 2.17%   |
| Positivo                    | 11        | 1.99%   |
| MSI                         | 9         | 1.63%   |
| Packard Bell                | 5         | 0.9%    |
| Notebook                    | 5         | 0.9%    |
| Mediacom                    | 5         | 0.9%    |
| Fujitsu Siemens             | 5         | 0.9%    |
| Fujitsu                     | 5         | 0.9%    |
| Unknown                     | 4         | 0.72%   |
| IBM                         | 3         | 0.54%   |
| Alienware                   | 3         | 0.54%   |
| YASHI                       | 2         | 0.36%   |
| Panasonic                   | 2         | 0.36%   |
| Itautec                     | 2         | 0.36%   |
| Insyde                      | 2         | 0.36%   |
| Gigabyte Technology         | 2         | 0.36%   |
| Gateway                     | 2         | 0.36%   |
| Dixonsxp                    | 2         | 0.36%   |
| AMI                         | 2         | 0.36%   |
| UNOWHY                      | 1         | 0.18%   |
| TrekStor                    | 1         | 0.18%   |
| Timi                        | 1         | 0.18%   |
| Thomson                     | 1         | 0.18%   |
| System76                    | 1         | 0.18%   |
| Standard                    | 1         | 0.18%   |
| Semp Toshiba                | 1         | 0.18%   |
| Prestigio                   | 1         | 0.18%   |
| Phoenix/SiS                 | 1         | 0.18%   |
| Philco                      | 1         | 0.18%   |
| OEM                         | 1         | 0.18%   |
| NOBLEX                      | 1         | 0.18%   |
| LG Electronics              | 1         | 0.18%   |
| LEADER                      | 1         | 0.18%   |
| Lanix                       | 1         | 0.18%   |
| LAMINA                      | 1         | 0.18%   |
| Intel                       | 1         | 0.18%   |
| I-Life Digital Technologies | 1         | 0.18%   |
| Hungaro Flotta Kft          | 1         | 0.18%   |
| HUAWEI                      | 1         | 0.18%   |
| Haier                       | 1         | 0.18%   |
| GTZS                        | 1         | 0.18%   |
| Digibras                    | 1         | 0.18%   |
| ASHI                        | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 11        | 1.99%   |
| HP Notebook                         | 7         | 1.27%   |
| Apple MacBookPro8,1                 | 6         | 1.08%   |
| HP Pavilion g6                      | 4         | 0.72%   |
| HP Pavilion dv6                     | 4         | 0.72%   |
| Dell Latitude D630                  | 4         | 0.72%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS | 3         | 0.54%   |
| HP ProBook 440 G7                   | 3         | 0.54%   |
| HP Pavilion 15                      | 3         | 0.54%   |
| ASUS 1000H                          | 3         | 0.54%   |
| Acer Aspire 5742G                   | 3         | 0.54%   |
| YASHI MYBOOK 360                    | 2         | 0.36%   |
| Toshiba Satellite L40               | 2         | 0.36%   |
| Toshiba Satellite A205              | 2         | 0.36%   |
| Samsung RV415/RV515                 | 2         | 0.36%   |
| Samsung 275E4E/275E5E               | 2         | 0.36%   |
| Positivo Mobile                     | 2         | 0.36%   |
| Positivo H14BT58                    | 2         | 0.36%   |
| Mediacom WinPad 11,6 FullHD- WPU11  | 2         | 0.36%   |
| Mediacom GTZS                       | 2         | 0.36%   |
| Lenovo IdeaPad 330-17AST 81D7       | 2         | 0.36%   |
| Lenovo IdeaPad 320-15AST 80XV       | 2         | 0.36%   |
| Lenovo IdeaPad 100-15IBD 80QQ       | 2         | 0.36%   |
| Itautec Infoway                     | 2         | 0.36%   |
| HP ProBook 450 G2                   | 2         | 0.36%   |
| HP ProBook 440 G8 Notebook PC       | 2         | 0.36%   |
| HP Pavilion g7                      | 2         | 0.36%   |
| HP Pavilion g4                      | 2         | 0.36%   |
| HP Laptop 15-bw0xx                  | 2         | 0.36%   |
| HP EliteBook 840 G1                 | 2         | 0.36%   |
| HP EliteBook 2560p                  | 2         | 0.36%   |
| HP Compaq Presario CQ50             | 2         | 0.36%   |
| HP Compaq Presario C700             | 2         | 0.36%   |
| Dell XPS 13 9300                    | 2         | 0.36%   |
| Dell Studio 1555                    | 2         | 0.36%   |
| Dell Latitude 7480                  | 2         | 0.36%   |
| Dell Inspiron 15-3567               | 2         | 0.36%   |
| ASUS 1215B                          | 2         | 0.36%   |
| ASUS 1015PE                         | 2         | 0.36%   |
| ASUS 1015BX                         | 2         | 0.36%   |
| Apple MacBookPro10,1                | 2         | 0.36%   |
| Acer Aspire 5735                    | 2         | 0.36%   |
| Acer Aspire 5715Z                   | 2         | 0.36%   |
| Acer AOD257                         | 2         | 0.36%   |
| UNOWHY Y13G010S4EI                  | 1         | 0.18%   |
| TrekStor Surfbook A13B              | 1         | 0.18%   |
| Toshiba TECRA A8                    | 1         | 0.18%   |
| Toshiba TECRA A3X                   | 1         | 0.18%   |
| Toshiba Satellite U500              | 1         | 0.18%   |
| Toshiba Satellite S55-B             | 1         | 0.18%   |
| Toshiba Satellite Pro U400          | 1         | 0.18%   |
| Toshiba Satellite Pro S500          | 1         | 0.18%   |
| Toshiba Satellite Pro C850-1GR      | 1         | 0.18%   |
| Toshiba Satellite P20               | 1         | 0.18%   |
| Toshiba Satellite L840              | 1         | 0.18%   |
| Toshiba Satellite L735              | 1         | 0.18%   |
| Toshiba Satellite L70-B             | 1         | 0.18%   |
| Toshiba Satellite L50D-B            | 1         | 0.18%   |
| Toshiba Satellite L450              | 1         | 0.18%   |
| Toshiba Satellite L35               | 1         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 37        | 6.69%   |
| HP Pavilion           | 34        | 6.15%   |
| Toshiba Satellite     | 33        | 5.97%   |
| Lenovo IdeaPad        | 28        | 5.06%   |
| Dell Inspiron         | 27        | 4.88%   |
| Lenovo ThinkPad       | 25        | 4.52%   |
| HP ProBook            | 22        | 3.98%   |
| Dell Latitude         | 19        | 3.44%   |
| HP EliteBook          | 15        | 2.71%   |
| HP Compaq             | 14        | 2.53%   |
| Unknown               | 11        | 1.99%   |
| HP Laptop             | 9         | 1.63%   |
| HP Notebook           | 7         | 1.27%   |
| ASUS VivoBook         | 6         | 1.08%   |
| Apple MacBookPro8     | 6         | 1.08%   |
| Fujitsu Siemens AMILO | 5         | 0.9%    |
| Packard Bell EasyNote | 4         | 0.72%   |
| HP Presario           | 4         | 0.72%   |
| Dell Vostro           | 4         | 0.72%   |
| HP Stream             | 3         | 0.54%   |
| Fujitsu LIFEBOOK      | 3         | 0.54%   |
| Dell XPS              | 3         | 0.54%   |
| Dell Studio           | 3         | 0.54%   |
| ASUS 1000H            | 3         | 0.54%   |
| Apple MacBookPro10    | 3         | 0.54%   |
| Acer Extensa          | 3         | 0.54%   |
| YASHI MYBOOK          | 2         | 0.36%   |
| Toshiba TECRA         | 2         | 0.36%   |
| Samsung RV415         | 2         | 0.36%   |
| Samsung 275E4E        | 2         | 0.36%   |
| Positivo Mobile       | 2         | 0.36%   |
| Positivo H14BT58      | 2         | 0.36%   |
| Notebook W54          | 2         | 0.36%   |
| Mediacom WinPad       | 2         | 0.36%   |
| Mediacom GTZS         | 2         | 0.36%   |
| Lenovo Yoga           | 2         | 0.36%   |
| Itautec Infoway       | 2         | 0.36%   |
| Dell System           | 2         | 0.36%   |
| ASUS 1215B            | 2         | 0.36%   |
| ASUS 1015PE           | 2         | 0.36%   |
| ASUS 1015BX           | 2         | 0.36%   |
| Acer Swift            | 2         | 0.36%   |
| Acer AOD257           | 2         | 0.36%   |
| UNOWHY Y13G010S4EI    | 1         | 0.18%   |
| TrekStor Surfbook     | 1         | 0.18%   |
| Toshiba NB510         | 1         | 0.18%   |
| Toshiba NB505         | 1         | 0.18%   |
| Timi TM1612           | 1         | 0.18%   |
| Thomson NEO14A-4BK64  | 1         | 0.18%   |
| System76 Lemur        | 1         | 0.18%   |
| Standard EF20EA       | 1         | 0.18%   |
| Sony VPCYB35AL        | 1         | 0.18%   |
| Sony VPCYB15AB        | 1         | 0.18%   |
| Sony VPCSB1V9E        | 1         | 0.18%   |
| Sony VPCSA2FGX        | 1         | 0.18%   |
| Sony VPCEJ1E1E        | 1         | 0.18%   |
| Sony VPCEG25EN        | 1         | 0.18%   |
| Sony VGN-SZ71WN       | 1         | 0.18%   |
| Sony VGN-SZ670AN      | 1         | 0.18%   |
| Sony VGN-S5XP         | 1         | 0.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 59        | 10.67%  |
| 2008    | 50        | 9.04%   |
| 2010    | 45        | 8.14%   |
| 2013    | 44        | 7.96%   |
| 2007    | 44        | 7.96%   |
| 2012    | 42        | 7.59%   |
| 2019    | 37        | 6.69%   |
| 2016    | 31        | 5.61%   |
| 2009    | 28        | 5.06%   |
| 2017    | 27        | 4.88%   |
| 2014    | 26        | 4.7%    |
| 2018    | 25        | 4.52%   |
| 2015    | 22        | 3.98%   |
| 2006    | 22        | 3.98%   |
| 2020    | 20        | 3.62%   |
| 2021    | 18        | 3.25%   |
| 2005    | 5         | 0.9%    |
| 2022    | 3         | 0.54%   |
| 2002    | 2         | 0.36%   |
| Unknown | 2         | 0.36%   |
| 2004    | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 553       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 522       | 94.22%  |
| Enabled  | 32        | 5.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 538       | 97.29%  |
| Yes  | 15        | 2.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 184       | 32.92%  |
| 4.01-8.0   | 121       | 21.65%  |
| 1.01-2.0   | 117       | 20.93%  |
| 8.01-16.0  | 51        | 9.12%   |
| 2.01-3.0   | 32        | 5.72%   |
| 16.01-24.0 | 28        | 5.01%   |
| 0.51-1.0   | 19        | 3.4%    |
| 32.01-64.0 | 5         | 0.89%   |
| 0.01-0.5   | 2         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 267       | 44.65%  |
| 0.51-1.0  | 164       | 27.42%  |
| 2.01-3.0  | 66        | 11.04%  |
| 0.01-0.5  | 39        | 6.52%   |
| 4.01-8.0  | 30        | 5.02%   |
| 3.01-4.0  | 28        | 4.68%   |
| 8.01-16.0 | 4         | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 423       | 75.81%  |
| 2      | 117       | 20.97%  |
| 0      | 12        | 2.15%   |
| 3      | 5         | 0.9%    |
| 4      | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 289       | 52.17%  |
| No        | 265       | 47.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 477       | 86.1%   |
| No        | 77        | 13.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 519       | 93.85%  |
| No        | 34        | 6.15%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 333       | 59.15%  |
| No        | 230       | 40.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 74        | 13.36%  |
| Brazil                 | 64        | 11.55%  |
| France                 | 47        | 8.48%   |
| Italy                  | 44        | 7.94%   |
| Germany                | 34        | 6.14%   |
| Russia                 | 30        | 5.42%   |
| UK                     | 27        | 4.87%   |
| Poland                 | 20        | 3.61%   |
| Canada                 | 17        | 3.07%   |
| Spain                  | 13        | 2.35%   |
| Turkey                 | 11        | 1.99%   |
| Netherlands            | 10        | 1.81%   |
| Belgium                | 10        | 1.81%   |
| Australia              | 10        | 1.81%   |
| Ukraine                | 8         | 1.44%   |
| Czechia                | 8         | 1.44%   |
| Mexico                 | 7         | 1.26%   |
| India                  | 7         | 1.26%   |
| Argentina              | 7         | 1.26%   |
| Indonesia              | 6         | 1.08%   |
| Switzerland            | 5         | 0.9%    |
| Ireland                | 5         | 0.9%    |
| Hungary                | 5         | 0.9%    |
| Costa Rica             | 5         | 0.9%    |
| Portugal               | 4         | 0.72%   |
| Chile                  | 4         | 0.72%   |
| Sweden                 | 3         | 0.54%   |
| Serbia                 | 3         | 0.54%   |
| Malaysia               | 3         | 0.54%   |
| Lithuania              | 3         | 0.54%   |
| Finland                | 3         | 0.54%   |
| Colombia               | 3         | 0.54%   |
| Bulgaria               | 3         | 0.54%   |
| Uruguay                | 2         | 0.36%   |
| Tunisia                | 2         | 0.36%   |
| Taiwan                 | 2         | 0.36%   |
| South Africa           | 2         | 0.36%   |
| Slovenia               | 2         | 0.36%   |
| Singapore              | 2         | 0.36%   |
| Romania                | 2         | 0.36%   |
| Peru                   | 2         | 0.36%   |
| Norway                 | 2         | 0.36%   |
| New Zealand            | 2         | 0.36%   |
| Japan                  | 2         | 0.36%   |
| Greece                 | 2         | 0.36%   |
| Ecuador                | 2         | 0.36%   |
| Bosnia and Herzegovina | 2         | 0.36%   |
| Belarus                | 2         | 0.36%   |
| Austria                | 2         | 0.36%   |
| Zambia                 | 1         | 0.18%   |
| Vietnam                | 1         | 0.18%   |
| Venezuela              | 1         | 0.18%   |
| Thailand               | 1         | 0.18%   |
| Sri Lanka              | 1         | 0.18%   |
| South Korea            | 1         | 0.18%   |
| Slovakia               | 1         | 0.18%   |
| Philippines            | 1         | 0.18%   |
| Luxembourg             | 1         | 0.18%   |
| Lebanon                | 1         | 0.18%   |
| Israel                 | 1         | 0.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 10        | 1.71%   |
| Moscow            | 6         | 1.03%   |
| Milan             | 6         | 1.03%   |
| Rome              | 5         | 0.86%   |
| Melbourne         | 5         | 0.86%   |
| Heredia           | 5         | 0.86%   |
| Stuttgart         | 4         | 0.68%   |
| Porto Alegre      | 4         | 0.68%   |
| Mexico City       | 4         | 0.68%   |
| Istanbul          | 4         | 0.68%   |
| Bengaluru         | 4         | 0.68%   |
| Yekaterinburg     | 3         | 0.51%   |
| Warsaw            | 3         | 0.51%   |
| Teresina          | 3         | 0.51%   |
| Salvador          | 3         | 0.51%   |
| Rio de Janeiro    | 3         | 0.51%   |
| Oshawa            | 3         | 0.51%   |
| New York          | 3         | 0.51%   |
| Munich            | 3         | 0.51%   |
| Kyiv              | 3         | 0.51%   |
| Fortaleza         | 3         | 0.51%   |
| Derry             | 3         | 0.51%   |
| Curitiba          | 3         | 0.51%   |
| Buenos Aires      | 3         | 0.51%   |
| Zurich            | 2         | 0.34%   |
| Winnipeg          | 2         | 0.34%   |
| Vienna            | 2         | 0.34%   |
| Vicosa            | 2         | 0.34%   |
| Venice            | 2         | 0.34%   |
| St Petersburg     | 2         | 0.34%   |
| Southampton       | 2         | 0.34%   |
| Sao Paulo         | 2         | 0.34%   |
| Santa Lucia       | 2         | 0.34%   |
| Sankt Leon-Rot    | 2         | 0.34%   |
| Prague            | 2         | 0.34%   |
| Poznan            | 2         | 0.34%   |
| Portland          | 2         | 0.34%   |
| Petrolina         | 2         | 0.34%   |
| Perth Amboy       | 2         | 0.34%   |
| Orléans          | 2         | 0.34%   |
| Orlando           | 2         | 0.34%   |
| Olomouc           | 2         | 0.34%   |
| Nizhniy Novgorod  | 2         | 0.34%   |
| Niterói          | 2         | 0.34%   |
| Nantes            | 2         | 0.34%   |
| Montevideo        | 2         | 0.34%   |
| Mississauga       | 2         | 0.34%   |
| Loveland          | 2         | 0.34%   |
| Kuala Lumpur      | 2         | 0.34%   |
| Krakow            | 2         | 0.34%   |
| Kazan’          | 2         | 0.34%   |
| Joao Pessoa       | 2         | 0.34%   |
| Houston           | 2         | 0.34%   |
| Helsinki          | 2         | 0.34%   |
| Glasgow           | 2         | 0.34%   |
| Ghent             | 2         | 0.34%   |
| Frankfurt am Main | 2         | 0.34%   |
| Florence          | 2         | 0.34%   |
| Dublin            | 2         | 0.34%   |
| Córdoba          | 2         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 91        | 102    | 14.89%  |
| WDC                 | 86        | 104    | 14.08%  |
| Toshiba             | 59        | 66     | 9.66%   |
| Unknown             | 58        | 79     | 9.49%   |
| Hitachi             | 55        | 66     | 9%      |
| Samsung Electronics | 46        | 68     | 7.53%   |
| Kingston            | 29        | 32     | 4.75%   |
| Crucial             | 23        | 25     | 3.76%   |
| Fujitsu             | 18        | 19     | 2.95%   |
| Intel               | 17        | 21     | 2.78%   |
| HGST                | 17        | 21     | 2.78%   |
| SanDisk             | 15        | 19     | 2.45%   |
| SK hynix            | 11        | 11     | 1.8%    |
| Apacer              | 8         | 8      | 1.31%   |
| A-DATA Technology   | 6         | 6      | 0.98%   |
| KIOXIA              | 5         | 5      | 0.82%   |
| China               | 5         | 7      | 0.82%   |
| Micron Technology   | 4         | 4      | 0.65%   |
| Apple               | 4         | 11     | 0.65%   |
| Unknown             | 4         | 5      | 0.65%   |
| Transcend           | 3         | 3      | 0.49%   |
| Patriot             | 3         | 3      | 0.49%   |
| OCZ                 | 3         | 3      | 0.49%   |
| LITEONIT            | 3         | 3      | 0.49%   |
| LITEON              | 3         | 4      | 0.49%   |
| IBM/Hitachi         | 3         | 4      | 0.49%   |
| STEC                | 2         | 3      | 0.33%   |
| SPCC                | 2         | 2      | 0.33%   |
| PNY                 | 2         | 2      | 0.33%   |
| LDLC                | 2         | 2      | 0.33%   |
| KingDian            | 2         | 2      | 0.33%   |
| Gigabyte Technology | 2         | 2      | 0.33%   |
| Dogfish             | 2         | 2      | 0.33%   |
| USB                 | 1         | 1      | 0.16%   |
| Teclast             | 1         | 1      | 0.16%   |
| TEAM T25            | 1         | 1      | 0.16%   |
| TCSUNBOW            | 1         | 1      | 0.16%   |
| Phison Electronics  | 1         | 1      | 0.16%   |
| Phison              | 1         | 5      | 0.16%   |
| NGFF                | 1         | 1      | 0.16%   |
| MyDigitalSSD        | 1         | 1      | 0.16%   |
| Mushkin             | 1         | 1      | 0.16%   |
| LS                  | 1         | 1      | 0.16%   |
| Lenovo              | 1         | 2      | 0.16%   |
| LaCie               | 1         | 2      | 0.16%   |
| KingSpec            | 1         | 3      | 0.16%   |
| JMicron Technology  | 1         | 1      | 0.16%   |
| Integral            | 1         | 1      | 0.16%   |
| General             | 1         | 1      | 0.16%   |
| EMTEC               | 1         | 1      | 0.16%   |
| Dell                | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 13        | 2.03%   |
| Seagate ST1000LM035-1RK172 1TB       | 8         | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 8         | 1.25%   |
| Kingston SA400S37240G 240GB SSD      | 8         | 1.25%   |
| Toshiba MQ01ABF050 500GB             | 7         | 1.09%   |
| Toshiba MQ01ABD100 1TB               | 7         | 1.09%   |
| Seagate ST9500325AS 500GB            | 7         | 1.09%   |
| Seagate ST500LT012-1DG142 500GB      | 7         | 1.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 7         | 1.09%   |
| Unknown MMC Card  64GB               | 6         | 0.94%   |
| Toshiba MQ01ABD050 500GB             | 5         | 0.78%   |
| Crucial CT240BX500SSD1 240GB         | 5         | 0.78%   |
| Unknown NCard  32GB                  | 4         | 0.63%   |
| Unknown MMC64G  64GB                 | 4         | 0.63%   |
| Unknown DA4064  64GB                 | 4         | 0.63%   |
| Seagate ST9320325AS 320GB            | 4         | 0.63%   |
| Seagate ST9250315AS 250GB            | 4         | 0.63%   |
| Samsung SSD 850 EVO 250GB            | 4         | 0.63%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.63%   |
| Hitachi HTS543216L9SA00 160GB        | 4         | 0.63%   |
| Hitachi HTS542512K9SA00 120GB        | 4         | 0.63%   |
| Crucial CT480BX500SSD1 480GB         | 4         | 0.63%   |
| Unknown                              | 4         | 0.63%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 3         | 0.47%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 3         | 0.47%   |
| WDC WD2500BEVT-80A23T0 250GB         | 3         | 0.47%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 3         | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 0.47%   |
| Unknown SD/MMC/MS PRO 128GB          | 3         | 0.47%   |
| Unknown MMC Card  16GB               | 3         | 0.47%   |
| Unknown 128G32  128GB                | 3         | 0.47%   |
| Seagate ST98823AS 80GB               | 3         | 0.47%   |
| Seagate ST9250410AS 250GB            | 3         | 0.47%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 0.47%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 3         | 0.47%   |
| Samsung SSD 860 EVO 500GB            | 3         | 0.47%   |
| Samsung SSD 840 EVO 250GB            | 3         | 0.47%   |
| Samsung HN-M500MBB 500GB             | 3         | 0.47%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.47%   |
| Hitachi HTS547575A9E384 752GB        | 3         | 0.47%   |
| Hitachi HTS545050A7E380 500GB        | 3         | 0.47%   |
| Hitachi HTS543232L9A300 320GB        | 3         | 0.47%   |
| Hitachi HTS543232A7A384 320GB        | 3         | 0.47%   |
| Hitachi HTS541616J9SA00 160GB        | 3         | 0.47%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.47%   |
| HGST HTS545050A7E680 500GB           | 3         | 0.47%   |
| HGST HTS545050A7E380 500GB           | 3         | 0.47%   |
| HGST HTS541010A9E680 1TB             | 3         | 0.47%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 0.47%   |
| WDC WD3200BEVT-22A23T0 320GB         | 2         | 0.31%   |
| WDC WD1200BEVS-60UST0 120GB          | 2         | 0.31%   |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 0.31%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 0.31%   |
| WDC WD10JPVX-60JC3T1 1TB             | 2         | 0.31%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.31%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 2         | 0.31%   |
| Unknown MMC Card  128GB              | 2         | 0.31%   |
| Unknown ED2S5  128GB                 | 2         | 0.31%   |
| Unknown DA4032  32GB                 | 2         | 0.31%   |
| Toshiba THNSFJ256GDNU A 256GB SSD    | 2         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 90        | 101    | 27.36%  |
| WDC                 | 75        | 91     | 22.8%   |
| Hitachi             | 55        | 66     | 16.72%  |
| Toshiba             | 50        | 55     | 15.2%   |
| Fujitsu             | 18        | 19     | 5.47%   |
| HGST                | 17        | 21     | 5.17%   |
| Samsung Electronics | 15        | 24     | 4.56%   |
| Unknown             | 3         | 3      | 0.91%   |
| IBM/Hitachi         | 3         | 4      | 0.91%   |
| USB                 | 1         | 1      | 0.3%    |
| LaCie               | 1         | 1      | 0.3%    |
| Apple               | 1         | 1      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 24        | 26     | 14.12%  |
| Samsung Electronics | 23        | 33     | 13.53%  |
| Crucial             | 22        | 24     | 12.94%  |
| Intel               | 14        | 18     | 8.24%   |
| SanDisk             | 11        | 15     | 6.47%   |
| Apacer              | 8         | 8      | 4.71%   |
| WDC                 | 6         | 7      | 3.53%   |
| A-DATA Technology   | 6         | 6      | 3.53%   |
| Toshiba             | 5         | 6      | 2.94%   |
| China               | 5         | 7      | 2.94%   |
| Transcend           | 3         | 3      | 1.76%   |
| SK hynix            | 3         | 3      | 1.76%   |
| Patriot             | 3         | 3      | 1.76%   |
| OCZ                 | 3         | 3      | 1.76%   |
| LITEONIT            | 3         | 3      | 1.76%   |
| LITEON              | 3         | 4      | 1.76%   |
| SPCC                | 2         | 2      | 1.18%   |
| PNY                 | 2         | 2      | 1.18%   |
| Micron Technology   | 2         | 2      | 1.18%   |
| LDLC                | 2         | 2      | 1.18%   |
| KingDian            | 2         | 2      | 1.18%   |
| Dogfish             | 2         | 2      | 1.18%   |
| Apple               | 2         | 8      | 1.18%   |
| Unknown             | 1         | 1      | 0.59%   |
| Teclast             | 1         | 1      | 0.59%   |
| TEAM T25            | 1         | 1      | 0.59%   |
| TCSUNBOW            | 1         | 1      | 0.59%   |
| Seagate             | 1         | 1      | 0.59%   |
| NGFF                | 1         | 1      | 0.59%   |
| MyDigitalSSD        | 1         | 1      | 0.59%   |
| Mushkin             | 1         | 1      | 0.59%   |
| LS                  | 1         | 1      | 0.59%   |
| Lenovo              | 1         | 2      | 0.59%   |
| KingSpec            | 1         | 3      | 0.59%   |
| Integral            | 1         | 1      | 0.59%   |
| Gigabyte Technology | 1         | 1      | 0.59%   |
| Dell                | 1         | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 325       | 387    | 53.81%  |
| SSD     | 165       | 206    | 27.32%  |
| MMC     | 62        | 82     | 10.26%  |
| NVMe    | 45        | 57     | 7.45%   |
| Unknown | 7         | 8      | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 458       | 581    | 78.69%  |
| MMC  | 62        | 82     | 10.65%  |
| NVMe | 45        | 57     | 7.73%   |
| SAS  | 17        | 20     | 2.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 376       | 467    | 78.66%  |
| 0.51-1.0   | 91        | 112    | 19.04%  |
| 1.01-2.0   | 8         | 10     | 1.67%   |
| 3.01-4.0   | 2         | 2      | 0.42%   |
| 4.01-10.0  | 1         | 2      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 167       | 29.72%  |
| 251-500        | 140       | 24.91%  |
| 51-100         | 65        | 11.57%  |
| 501-1000       | 59        | 10.5%   |
| 21-50          | 52        | 9.25%   |
| 1-20           | 48        | 8.54%   |
| 1001-2000      | 18        | 3.2%    |
| More than 3000 | 6         | 1.07%   |
| 2001-3000      | 4         | 0.71%   |
| Unknown        | 3         | 0.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 324       | 55.86%  |
| 21-50          | 103       | 17.76%  |
| 101-250        | 61        | 10.52%  |
| 51-100         | 42        | 7.24%   |
| 251-500        | 20        | 3.45%   |
| 501-1000       | 18        | 3.1%    |
| 1001-2000      | 6         | 1.03%   |
| Unknown        | 3         | 0.52%   |
| More than 3000 | 2         | 0.34%   |
| 2001-3000      | 1         | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB         | 3         | 3      | 4.62%   |
| Seagate ST9500325AS 500GB                  | 2         | 2      | 3.08%   |
| Seagate ST9320325AS 320GB                  | 2         | 2      | 3.08%   |
| Hitachi HTS542512K9SA00 120GB              | 2         | 2      | 3.08%   |
| WDC WDS240G2G0A-00JH30 240GB SSD           | 1         | 1      | 1.54%   |
| WDC WD800BEVS-60RST0 80GB                  | 1         | 1      | 1.54%   |
| WDC WD5000LUCT-62C26Y0 500GB               | 1         | 1      | 1.54%   |
| WDC WD3200BPVT-80ZEST0 320GB               | 1         | 1      | 1.54%   |
| WDC WD3200BEKT-60PVMT0 320GB               | 1         | 1      | 1.54%   |
| WDC WD2500BEVT-80A23T0 250GB               | 1         | 2      | 1.54%   |
| WDC WD1200BEVS-60UST0 120GB                | 1         | 1      | 1.54%   |
| WDC WD1200BEVS-07LAT0 120GB                | 1         | 1      | 1.54%   |
| WDC WD10JPVX-75JC3T0 1TB                   | 1         | 1      | 1.54%   |
| WDC WD10JPVX-60JC3T1 1TB                   | 1         | 1      | 1.54%   |
| Toshiba MQ01ABD050 500GB                   | 1         | 1      | 1.54%   |
| Toshiba MK5059GSXP 500GB                   | 1         | 1      | 1.54%   |
| Toshiba MK3276GSX 320GB                    | 1         | 1      | 1.54%   |
| Toshiba MK2046GSX 200GB                    | 1         | 1      | 1.54%   |
| TCSUNBOW X1 32GB SSD                       | 1         | 1      | 1.54%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD      | 1         | 1      | 1.54%   |
| SK hynix HFS128G39TND-N210A 128GB SSD      | 1         | 1      | 1.54%   |
| Seagate ST9250410AS 250GB                  | 1         | 1      | 1.54%   |
| Seagate ST9250315AS 250GB                  | 1         | 1      | 1.54%   |
| Seagate ST9160821AS 160GB                  | 1         | 1      | 1.54%   |
| Seagate ST500LT012-1DG142 500GB            | 1         | 1      | 1.54%   |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 1.54%   |
| Seagate ST320LT007-9ZV142 320GB            | 1         | 1      | 1.54%   |
| Samsung Electronics HM160JI 160GB          | 1         | 1      | 1.54%   |
| Samsung Electronics HM121HI 120GB          | 1         | 5      | 1.54%   |
| OCZ VERTEX3 120GB SSD                      | 1         | 1      | 1.54%   |
| LITEON IT LST-16S9G-HP 16GB SSD            | 1         | 1      | 1.54%   |
| LITEON CV8-8E128-HP 128GB SSD              | 1         | 1      | 1.54%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD    | 1         | 1      | 1.54%   |
| KingSpec PA25-128 128GB SSD                | 1         | 3      | 1.54%   |
| Intel SSDSC2BF240A4L 240GB                 | 1         | 1      | 1.54%   |
| Intel SSDSC2BF180A5L 180GB                 | 1         | 1      | 1.54%   |
| Hitachi HTS725050A9A364 500GB              | 1         | 1      | 1.54%   |
| Hitachi HTS723232A7A364 320GB              | 1         | 1      | 1.54%   |
| Hitachi HTS722012K9SA00 120GB              | 1         | 1      | 1.54%   |
| Hitachi HTS547564A9E384 640GB              | 1         | 2      | 1.54%   |
| Hitachi HTS545050A7E380 500GB              | 1         | 1      | 1.54%   |
| Hitachi HTS545032B9A300 320GB              | 1         | 1      | 1.54%   |
| Hitachi HTS541616J9SA00 160GB              | 1         | 1      | 1.54%   |
| Hitachi HTS541040G9AT00 40GB               | 1         | 1      | 1.54%   |
| Hitachi HTS421280H9AT00 80GB               | 1         | 1      | 1.54%   |
| HGST HTS721010A9E630 1TB                   | 1         | 1      | 1.54%   |
| HGST HTS545050A7E680 500GB                 | 1         | 1      | 1.54%   |
| HGST HTS545050A7E380 500GB                 | 1         | 1      | 1.54%   |
| HGST HTS541075A9E680 752GB                 | 1         | 1      | 1.54%   |
| HGST HTS541010A9E680 1TB                   | 1         | 1      | 1.54%   |
| Fujitsu MHY2200BH 200GB                    | 1         | 1      | 1.54%   |
| Fujitsu MHY2120BH 120GB                    | 1         | 1      | 1.54%   |
| Fujitsu MHW2080BH PL 80GB                  | 1         | 1      | 1.54%   |
| Crucial M4-CT512M4SSD2 512GB               | 1         | 1      | 1.54%   |
| Crucial CT960M500SSD1 960GB                | 1         | 1      | 1.54%   |
| Crucial CT500P1SSD8 500GB                  | 1         | 1      | 1.54%   |
| Crucial CT120M500SSD3 120GB                | 1         | 1      | 1.54%   |
| Crucial CT120M500SSD1 120GB                | 1         | 1      | 1.54%   |
| Apacer 16GB SATA Flash Drive SSD           | 1         | 1      | 1.54%   |
| A-DATA Technology IM2S3334-256GD 256GB SSD | 1         | 1      | 1.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 20%     |
| Hitachi             | 11        | 12     | 16.92%  |
| WDC                 | 10        | 11     | 15.38%  |
| HGST                | 5         | 5      | 7.69%   |
| Crucial             | 5         | 5      | 7.69%   |
| Toshiba             | 4         | 4      | 6.15%   |
| Fujitsu             | 3         | 3      | 4.62%   |
| SK hynix            | 2         | 2      | 3.08%   |
| Samsung Electronics | 2         | 6      | 3.08%   |
| LITEON              | 2         | 2      | 3.08%   |
| Intel               | 2         | 2      | 3.08%   |
| TCSUNBOW            | 1         | 1      | 1.54%   |
| OCZ                 | 1         | 1      | 1.54%   |
| Kingston            | 1         | 1      | 1.54%   |
| KingSpec            | 1         | 3      | 1.54%   |
| Apacer              | 1         | 1      | 1.54%   |
| A-DATA Technology   | 1         | 1      | 1.54%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 27.66%  |
| Hitachi             | 11        | 12     | 23.4%   |
| WDC                 | 9         | 10     | 19.15%  |
| HGST                | 5         | 5      | 10.64%  |
| Toshiba             | 4         | 4      | 8.51%   |
| Fujitsu             | 3         | 3      | 6.38%   |
| Samsung Electronics | 2         | 6      | 4.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 53     | 72.31%  |
| SSD  | 17        | 19     | 26.15%  |
| NVMe | 1         | 1      | 1.54%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 33.33%  |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 33.33%  |
| Samsung Electronics HM320JI 320GB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 3      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 317       | 438    | 55.32%  |
| Works    | 188       | 225    | 32.81%  |
| Malfunc  | 65        | 73     | 11.34%  |
| Failed   | 3         | 4      | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 385       | 71.56%  |
| AMD                              | 90        | 16.73%  |
| Nvidia                           | 11        | 2.04%   |
| SanDisk                          | 8         | 1.49%   |
| Samsung Electronics              | 8         | 1.49%   |
| SK hynix                         | 6         | 1.12%   |
| Silicon Integrated Systems [SiS] | 6         | 1.12%   |
| KIOXIA                           | 5         | 0.93%   |
| Kingston Technology Company      | 5         | 0.93%   |
| Toshiba America Info Systems     | 4         | 0.74%   |
| VIA Technologies                 | 3         | 0.56%   |
| Phison Electronics               | 2         | 0.37%   |
| Micron Technology                | 2         | 0.37%   |
| Solid State Storage Technology   | 1         | 0.19%   |
| Micron/Crucial Technology        | 1         | 0.19%   |
| JMicron Technology               | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 52        | 8.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 41        | 6.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 41        | 6.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 33        | 5.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 31        | 4.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 31        | 4.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 26        | 4.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 25        | 3.97%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 20        | 3.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 20        | 3.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 17        | 2.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 17        | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 17        | 2.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 13        | 2.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 12        | 1.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 1.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 10        | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 10        | 1.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 1.43%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 9         | 1.43%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 8         | 1.27%   |
| AMD IXP SB4x0 IDE Controller                                                           | 7         | 1.11%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 6         | 0.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 6         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 6         | 0.95%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 5         | 0.79%   |
| KIOXIA Non-Volatile memory controller                                                  | 5         | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 5         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 0.79%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 5         | 0.79%   |
| AMD SB600 IDE                                                                          | 5         | 0.79%   |
| Nvidia MCP67 AHCI Controller                                                           | 4         | 0.63%   |
| Kingston Company Company Non-Volatile memory controller                                | 4         | 0.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 4         | 0.63%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 4         | 0.63%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 4         | 0.63%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 3         | 0.48%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 3         | 0.48%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 0.48%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 3         | 0.48%   |
| Nvidia MCP67 IDE Controller                                                            | 3         | 0.48%   |
| Nvidia MCP51 Serial ATA Controller                                                     | 3         | 0.48%   |
| Nvidia MCP51 IDE                                                                       | 3         | 0.48%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 0.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 0.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 3         | 0.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 3         | 0.48%   |
| AMD IXP SB4x0 Serial ATA Controller                                                    | 3         | 0.48%   |
| SK hynix Non-Volatile memory controller                                                | 2         | 0.32%   |
| SK hynix BC511                                                                         | 2         | 0.32%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 0.32%   |
| SanDisk PC SN520 NVMe SSD                                                              | 2         | 0.32%   |
| Phison E12 NVMe Controller                                                             | 2         | 0.32%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                           | 2         | 0.32%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                       | 2         | 0.32%   |
| Micron Non-Volatile memory controller                                                  | 2         | 0.32%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 2         | 0.32%   |
| Intel SSD 660P Series                                                                  | 2         | 0.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 0.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 394       | 66.67%  |
| IDE  | 134       | 22.67%  |
| NVMe | 43        | 7.28%   |
| RAID | 20        | 3.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 453       | 81.92%  |
| AMD    | 100       | 18.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 10        | 1.81%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 10        | 1.81%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 8         | 1.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 1.27%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 1.27%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 1.08%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 6         | 1.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 1.08%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 6         | 1.08%   |
| AMD E-450 APU with Radeon HD Graphics         | 6         | 1.08%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 5         | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.9%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 5         | 0.9%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 0.9%    |
| Intel Atom CPU Z3735F @ 1.33GHz               | 5         | 0.9%    |
| Intel Atom CPU N450 @ 1.66GHz                 | 5         | 0.9%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 4         | 0.72%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 4         | 0.72%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 4         | 0.72%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 4         | 0.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.72%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.72%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 0.72%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 0.72%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 0.72%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 4         | 0.72%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 0.72%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 0.72%   |
| AMD E-350 Processor                           | 4         | 0.72%   |
| AMD E-300 APU with Radeon HD Graphics         | 4         | 0.72%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 4         | 0.72%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.54%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 3         | 0.54%   |
| Intel Pentium Dual CPU T2310 @ 1.46GHz        | 3         | 0.54%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.54%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 3         | 0.54%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 3         | 0.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.54%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.54%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 0.54%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 0.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.54%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 3         | 0.54%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 3         | 0.54%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 0.54%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 0.54%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 3         | 0.54%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.54%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 3         | 0.54%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 3         | 0.54%   |
| Intel Core 2 CPU T5200 @ 1.60GHz              | 3         | 0.54%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 3         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 90        | 16.27%  |
| Intel Atom                     | 60        | 10.85%  |
| Intel Core i7                  | 58        | 10.49%  |
| Intel Celeron                  | 54        | 9.76%   |
| Intel Core 2 Duo               | 45        | 8.14%   |
| Intel Core i3                  | 43        | 7.78%   |
| Intel Pentium                  | 21        | 3.8%    |
| Intel Pentium Dual             | 18        | 3.25%   |
| AMD E                          | 14        | 2.53%   |
| Intel Pentium Dual-Core        | 13        | 2.35%   |
| AMD A6                         | 12        | 2.17%   |
| Intel Core 2                   | 11        | 1.99%   |
| Intel Genuine                  | 10        | 1.81%   |
| AMD A4                         | 9         | 1.63%   |
| Other                          | 8         | 1.45%   |
| AMD E1                         | 8         | 1.45%   |
| Intel Pentium M                | 5         | 0.9%    |
| Intel Celeron M                | 5         | 0.9%    |
| AMD Ryzen 7                    | 5         | 0.9%    |
| AMD Ryzen 5                    | 5         | 0.9%    |
| AMD E2                         | 5         | 0.9%    |
| Intel Pentium Silver           | 4         | 0.72%   |
| AMD Mobile Sempron             | 4         | 0.72%   |
| Intel Pentium 4                | 3         | 0.54%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.54%   |
| AMD Ryzen 3                    | 3         | 0.54%   |
| AMD Athlon X2                  | 3         | 0.54%   |
| AMD Athlon 64 X2               | 3         | 0.54%   |
| AMD Athlon                     | 3         | 0.54%   |
| AMD A8                         | 3         | 0.54%   |
| Intel Core Duo                 | 2         | 0.36%   |
| Intel Celeron Dual-Core        | 2         | 0.36%   |
| AMD Ryzen 7 PRO                | 2         | 0.36%   |
| AMD Phenom II                  | 2         | 0.36%   |
| AMD C-60                       | 2         | 0.36%   |
| AMD C-50                       | 2         | 0.36%   |
| AMD A10                        | 2         | 0.36%   |
| Intel Mobile Pentium 4         | 1         | 0.18%   |
| Intel Core m3                  | 1         | 0.18%   |
| Intel Core 2 Solo              | 1         | 0.18%   |
| Intel Core 2 Extreme           | 1         | 0.18%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.18%   |
| AMD Turion 64 X2               | 1         | 0.18%   |
| AMD Turion 64 Mobile           | 1         | 0.18%   |
| AMD Ryzen 5 PRO                | 1         | 0.18%   |
| AMD C-70                       | 1         | 0.18%   |
| AMD C-30                       | 1         | 0.18%   |
| AMD Athlon II Dual-Core        | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 381       | 68.9%   |
| 4      | 103       | 18.63%  |
| 1      | 56        | 10.13%  |
| 8      | 7         | 1.27%   |
| 6      | 5         | 0.9%    |
| 3      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 553       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 301       | 54.43%  |
| 2      | 252       | 45.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 512       | 92.59%  |
| 32-bit         | 41        | 7.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 14.16%  |
| 0x206a7    | 44        | 7.79%   |
| 0x6fd      | 32        | 5.66%   |
| 0x306a9    | 25        | 4.42%   |
| 0x40651    | 24        | 4.25%   |
| 0x1067a    | 23        | 4.07%   |
| 0x05000119 | 18        | 3.19%   |
| 0x20655    | 17        | 3.01%   |
| 0x106ca    | 17        | 3.01%   |
| 0x406e3    | 16        | 2.83%   |
| 0x406c4    | 16        | 2.83%   |
| 0x406c3    | 14        | 2.48%   |
| 0x30678    | 13        | 2.3%    |
| 0x106c2    | 13        | 2.3%    |
| 0x806ec    | 12        | 2.12%   |
| 0x6f6      | 10        | 1.77%   |
| 0x306c3    | 10        | 1.77%   |
| 0x20652    | 10        | 1.77%   |
| 0x6e8      | 9         | 1.59%   |
| 0x10676    | 9         | 1.59%   |
| 0x06006705 | 9         | 1.59%   |
| 0x6d8      | 8         | 1.42%   |
| 0x306d4    | 8         | 1.42%   |
| 0x806e9    | 7         | 1.24%   |
| 0x706a1    | 7         | 1.24%   |
| 0x05000029 | 7         | 1.24%   |
| 0x6fb      | 6         | 1.06%   |
| 0x706a8    | 5         | 0.88%   |
| 0x30661    | 5         | 0.88%   |
| 0x10661    | 5         | 0.88%   |
| 0x906ea    | 4         | 0.71%   |
| 0x806eb    | 4         | 0.71%   |
| 0x806ea    | 4         | 0.71%   |
| 0x6ec      | 4         | 0.71%   |
| 0x0700010f | 4         | 0.71%   |
| 0x06006704 | 4         | 0.71%   |
| 0x706e5    | 3         | 0.53%   |
| 0x506c9    | 3         | 0.53%   |
| 0x30673    | 3         | 0.53%   |
| 0x08600106 | 3         | 0.53%   |
| 0x08600103 | 3         | 0.53%   |
| 0x0810100b | 3         | 0.53%   |
| 0x07030105 | 3         | 0.53%   |
| 0x906ed    | 2         | 0.35%   |
| 0x906c0    | 2         | 0.35%   |
| 0x806c1    | 2         | 0.35%   |
| 0x6fa      | 2         | 0.35%   |
| 0x506ca    | 2         | 0.35%   |
| 0x08200103 | 2         | 0.35%   |
| 0x08108102 | 2         | 0.35%   |
| 0x07030106 | 2         | 0.35%   |
| 0x0600611a | 2         | 0.35%   |
| 0x06001116 | 2         | 0.35%   |
| 0x03000027 | 2         | 0.35%   |
| 0x02000057 | 2         | 0.35%   |
| 0x02000032 | 2         | 0.35%   |
| 0x010000c8 | 2         | 0.35%   |
| 0xf43      | 1         | 0.18%   |
| 0xf29      | 1         | 0.18%   |
| 0xf27      | 1         | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Core            | 61        | 11.03%  |
| Silvermont      | 50        | 9.04%   |
| SandyBridge     | 49        | 8.86%   |
| KabyLake        | 39        | 7.05%   |
| Haswell         | 38        | 6.87%   |
| Penryn          | 36        | 6.51%   |
| Bonnell         | 35        | 6.33%   |
| Westmere        | 31        | 5.61%   |
| IvyBridge       | 30        | 5.42%   |
| Bobcat          | 26        | 4.7%    |
| P6              | 22        | 3.98%   |
| Skylake         | 19        | 3.44%   |
| Excavator       | 18        | 3.25%   |
| Goldmont plus   | 14        | 2.53%   |
| K8 Hammer       | 12        | 2.17%   |
| Broadwell       | 9         | 1.63%   |
| Puma            | 8         | 1.45%   |
| Zen 2           | 7         | 1.27%   |
| Zen             | 6         | 1.08%   |
| K8 & K10 hybrid | 6         | 1.08%   |
| Jaguar          | 5         | 0.9%    |
| Icelake         | 5         | 0.9%    |
| Goldmont        | 5         | 0.9%    |
| Zen+            | 4         | 0.72%   |
| NetBurst        | 4         | 0.72%   |
| TigerLake       | 3         | 0.54%   |
| Piledriver      | 3         | 0.54%   |
| K10             | 3         | 0.54%   |
| Tremont         | 2         | 0.36%   |
| K10 Llano       | 2         | 0.36%   |
| Nehalem         | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 389       | 62.34%  |
| AMD                              | 139       | 22.28%  |
| Nvidia                           | 87        | 13.94%  |
| Silicon Integrated Systems [SiS] | 5         | 0.8%    |
| VIA Technologies                 | 3         | 0.48%   |
| S3 Graphics                      | 1         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 44        | 6.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 37        | 5.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 37        | 5.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 33        | 4.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 4.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 27        | 3.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 25        | 3.62%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 24        | 3.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 21        | 3.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 2.46%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 16        | 2.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 16        | 2.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 2.03%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 13        | 1.88%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 11        | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.3%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 8         | 1.16%   |
| Intel HD Graphics 620                                                                    | 7         | 1.01%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 1.01%   |
| AMD Renoir                                                                               | 7         | 1.01%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                                 | 7         | 1.01%   |
| Intel HD Graphics 5500                                                                   | 6         | 0.87%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 6         | 0.87%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.87%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 6         | 0.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 0.87%   |
| Intel UHD Graphics 620                                                                   | 5         | 0.72%   |
| Intel HD Graphics 500                                                                    | 5         | 0.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 0.72%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 5         | 0.72%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.72%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 0.58%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 4         | 0.58%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.58%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 4         | 0.58%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.58%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 0.43%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.43%   |
| Nvidia GT218M [NVS 3100M]                                                                | 3         | 0.43%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 3         | 0.43%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 3         | 0.43%   |
| Nvidia GF119M [GeForce 610M]                                                             | 3         | 0.43%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 3         | 0.43%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                                 | 3         | 0.43%   |
| Intel HD Graphics                                                                        | 3         | 0.43%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.43%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 3         | 0.43%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.43%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.43%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 3         | 0.43%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3         | 0.43%   |
| AMD Kabini [Radeon HD 8210]                                                              | 3         | 0.43%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 0.29%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.29%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.29%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.29%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 2         | 0.29%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 317       | 57.32%  |
| 1 x AMD         | 110       | 19.89%  |
| Intel + Nvidia  | 47        | 8.5%    |
| 1 x Nvidia      | 39        | 7.05%   |
| Intel + AMD     | 23        | 4.16%   |
| 2 x AMD         | 5         | 0.9%    |
| 1 x SiS         | 5         | 0.9%    |
| 1 x VIA         | 3         | 0.54%   |
| Other           | 2         | 0.36%   |
| 1 x S3 Graphics | 1         | 0.18%   |
| AMD + Nvidia    | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 505       | 91.16%  |
| Proprietary | 33        | 5.96%   |
| Unknown     | 16        | 2.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 333       | 59.68%  |
| 0.01-0.5   | 140       | 25.09%  |
| 1.01-2.0   | 42        | 7.53%   |
| 0.51-1.0   | 27        | 4.84%   |
| 3.01-4.0   | 11        | 1.97%   |
| 5.01-6.0   | 3         | 0.54%   |
| 2.01-3.0   | 2         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 103       | 18.86%  |
| Samsung Electronics     | 81        | 14.84%  |
| LG Display              | 71        | 13%     |
| Chimei Innolux          | 65        | 11.9%   |
| BOE                     | 58        | 10.62%  |
| Chi Mei Optoelectronics | 28        | 5.13%   |
| LG Philips              | 23        | 4.21%   |
| HannStar                | 17        | 3.11%   |
| Apple                   | 15        | 2.75%   |
| CPT                     | 10        | 1.83%   |
| Lenovo                  | 9         | 1.65%   |
| InfoVision              | 8         | 1.47%   |
| Goldstar                | 7         | 1.28%   |
| Acer                    | 7         | 1.28%   |
| Dell                    | 6         | 1.1%    |
| Hewlett-Packard         | 5         | 0.92%   |
| Sharp                   | 4         | 0.73%   |
| AOC                     | 3         | 0.55%   |
| Sony                    | 2         | 0.37%   |
| Philips                 | 2         | 0.37%   |
| PANDA                   | 2         | 0.37%   |
| NEC Computers           | 2         | 0.37%   |
| Vizio                   | 1         | 0.18%   |
| ViewSonic               | 1         | 0.18%   |
| Videoseven              | 1         | 0.18%   |
| Unknown                 | 1         | 0.18%   |
| Sceptre Tech            | 1         | 0.18%   |
| Panasonic               | 1         | 0.18%   |
| Nvidia                  | 1         | 0.18%   |
| NCS                     | 1         | 0.18%   |
| Lenovo Group Limited    | 1         | 0.18%   |
| KDC                     | 1         | 0.18%   |
| InnoLux Display         | 1         | 0.18%   |
| Iiyama                  | 1         | 0.18%   |
| IBM                     | 1         | 0.18%   |
| eMachines               | 1         | 0.18%   |
| DENON                   | 1         | 0.18%   |
| CVT                     | 1         | 0.18%   |
| BenQ                    | 1         | 0.18%   |
| ASUSTek Computer        | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 9         | 1.64%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 8         | 1.46%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 6         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 1.09%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 5         | 0.91%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 4         | 0.73%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 4         | 0.73%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 3         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.55%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch            | 3         | 0.55%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch              | 3         | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.55%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 3         | 0.55%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 3         | 0.55%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 3         | 0.55%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 3         | 0.55%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 3         | 0.55%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 3         | 0.55%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 0.55%   |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                     | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.55%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 3         | 0.55%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                  | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 261x163mm 12.1-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 2         | 0.36%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 2         | 0.36%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch              | 2         | 0.36%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.36%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 2         | 0.36%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch             | 2         | 0.36%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.36%   |
| CPT LCD Monitor CPT22CE 1024x600 210x127mm 9.7-inch                      | 2         | 0.36%   |
| CPT LCD Monitor CPT1BC7 1024x600 223x125mm 10.1-inch                     | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch          | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch          | 2         | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 2         | 0.36%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.36%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 0.36%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                     | 2         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 245       | 45.88%  |
| 1920x1080 (FHD)    | 99        | 18.54%  |
| 1280x800 (WXGA)    | 79        | 14.79%  |
| 1600x900 (HD+)     | 28        | 5.24%   |
| 1024x600           | 24        | 4.49%   |
| 1920x1200 (WUXGA)  | 14        | 2.62%   |
| 3840x2160 (4K)     | 8         | 1.5%    |
| 1680x1050 (WSXGA+) | 7         | 1.31%   |
| 1440x900 (WXGA+)   | 6         | 1.12%   |
| 2560x1440 (QHD)    | 4         | 0.75%   |
| 1280x1024 (SXGA)   | 4         | 0.75%   |
| 3840x2400          | 2         | 0.37%   |
| 2880x1800          | 2         | 0.37%   |
| 2288x1287          | 2         | 0.37%   |
| 1360x768           | 2         | 0.37%   |
| 3200x1800 (QHD+)   | 1         | 0.19%   |
| 3200x1080          | 1         | 0.19%   |
| 2560x1600          | 1         | 0.19%   |
| 1920x540           | 1         | 0.19%   |
| 1280x768           | 1         | 0.19%   |
| 1280x720 (HD)      | 1         | 0.19%   |
| 1024x768 (XGA)     | 1         | 0.19%   |
| Unknown            | 1         | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 227       | 41.65%  |
| 13      | 78        | 14.31%  |
| 14      | 76        | 13.94%  |
| 11      | 32        | 5.87%   |
| 17      | 30        | 5.5%    |
| 10      | 23        | 4.22%   |
| 12      | 16        | 2.94%   |
| 27      | 8         | 1.47%   |
| Unknown | 8         | 1.47%   |
| 24      | 6         | 1.1%    |
| 23      | 6         | 1.1%    |
| 21      | 6         | 1.1%    |
| 22      | 5         | 0.92%   |
| 18      | 4         | 0.73%   |
| 19      | 3         | 0.55%   |
| 8       | 3         | 0.55%   |
| 72      | 2         | 0.37%   |
| 9       | 2         | 0.37%   |
| 142     | 1         | 0.18%   |
| 84      | 1         | 0.18%   |
| 63      | 1         | 0.18%   |
| 48      | 1         | 0.18%   |
| 33      | 1         | 0.18%   |
| 31      | 1         | 0.18%   |
| 26      | 1         | 0.18%   |
| 25      | 1         | 0.18%   |
| 20      | 1         | 0.18%   |
| 16      | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 340       | 62.62%  |
| 201-300        | 103       | 18.97%  |
| 351-400        | 42        | 7.73%   |
| 501-600        | 22        | 4.05%   |
| 401-500        | 17        | 3.13%   |
| Unknown        | 8         | 1.47%   |
| 1501-2000      | 3         | 0.55%   |
| 101-200        | 3         | 0.55%   |
| 1001-1500      | 2         | 0.37%   |
| More than 2000 | 1         | 0.18%   |
| 701-800        | 1         | 0.18%   |
| 601-700        | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 391       | 76.52%  |
| 16/10   | 109       | 21.33%  |
| Unknown | 4         | 0.78%   |
| 5/4     | 3         | 0.59%   |
| 4/3     | 3         | 0.59%   |
| 1.00    | 1         | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 225       | 41.28%  |
| 81-90          | 132       | 24.22%  |
| 51-60          | 32        | 5.87%   |
| 41-50          | 25        | 4.59%   |
| 71-80          | 24        | 4.4%    |
| 121-130        | 24        | 4.4%    |
| 201-250        | 18        | 3.3%    |
| 61-70          | 14        | 2.57%   |
| 301-350        | 8         | 1.47%   |
| Unknown        | 8         | 1.47%   |
| 251-300        | 7         | 1.28%   |
| More than 1000 | 6         | 1.1%    |
| 131-140        | 6         | 1.1%    |
| 141-150        | 5         | 0.92%   |
| 151-200        | 4         | 0.73%   |
| 1-40           | 3         | 0.55%   |
| 351-500        | 2         | 0.37%   |
| 111-120        | 1         | 0.18%   |
| 91-100         | 1         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 259       | 48.05%  |
| 121-160       | 138       | 25.6%   |
| 51-100        | 112       | 20.78%  |
| 161-240       | 11        | 2.04%   |
| Unknown       | 8         | 1.48%   |
| More than 240 | 6         | 1.11%   |
| 1-50          | 5         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 493       | 87.72%  |
| 2     | 54        | 9.61%   |
| 0     | 12        | 2.14%   |
| 3     | 3         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 282       | 31.09%  |
| Intel                             | 200       | 22.05%  |
| Qualcomm Atheros                  | 167       | 18.41%  |
| Broadcom                          | 94        | 10.36%  |
| Marvell Technology Group          | 26        | 2.87%   |
| Broadcom Limited                  | 25        | 2.76%   |
| Ralink                            | 23        | 2.54%   |
| Nvidia                            | 10        | 1.1%    |
| TP-Link                           | 9         | 0.99%   |
| Attansic Technology               | 9         | 0.99%   |
| Ralink Technology                 | 8         | 0.88%   |
| ASIX Electronics                  | 7         | 0.77%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.55%   |
| Samsung Electronics               | 5         | 0.55%   |
| Xiaomi                            | 4         | 0.44%   |
| AMD                               | 4         | 0.44%   |
| VIA Technologies                  | 3         | 0.33%   |
| Hewlett-Packard                   | 3         | 0.33%   |
| Fibocom                           | 2         | 0.22%   |
| Dell                              | 2         | 0.22%   |
| Tenda                             | 1         | 0.11%   |
| Seeed                             | 1         | 0.11%   |
| Research In Motion                | 1         | 0.11%   |
| Qualcomm Atheros Communications   | 1         | 0.11%   |
| Qualcomm                          | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.11%   |
| NetGear                           | 1         | 0.11%   |
| Microchip Technology              | 1         | 0.11%   |
| MediaTek                          | 1         | 0.11%   |
| Linksys                           | 1         | 0.11%   |
| LG Electronics                    | 1         | 0.11%   |
| Lab126                            | 1         | 0.11%   |
| JMicron Technology                | 1         | 0.11%   |
| Intersil                          | 1         | 0.11%   |
| ICS Advent                        | 1         | 0.11%   |
| Huawei Technologies               | 1         | 0.11%   |
| Ericsson Business Mobile Networks | 1         | 0.11%   |
| Arduino SA                        | 1         | 0.11%   |
| 3Com                              | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 123       | 11.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 90        | 8.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 34        | 3.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 28        | 2.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 27        | 2.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 24        | 2.25%   |
| Intel Wireless 7260                                                           | 22        | 2.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 20        | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 19        | 1.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 18        | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 17        | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13        | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 11        | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 11        | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 11        | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 11        | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 10        | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 10        | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 10        | 0.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 10        | 0.94%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 10        | 0.94%   |
| Intel Wireless 7265                                                           | 9         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                                      | 9         | 0.84%   |
| Attansic AR8152 v2.0 Fast Ethernet                                            | 9         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 8         | 0.75%   |
| Intel Wireless 3160                                                           | 8         | 0.75%   |
| Intel WiFi Link 5100                                                          | 8         | 0.75%   |
| Intel Wi-Fi 6 AX200                                                           | 8         | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 7         | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 7         | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 7         | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 7         | 0.65%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 6         | 0.56%   |
| Realtek 802.11ac NIC                                                          | 6         | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 6         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 6         | 0.56%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 6         | 0.56%   |
| Intel Wireless 8260                                                           | 6         | 0.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 6         | 0.56%   |
| Intel Ethernet Connection I218-LM                                             | 6         | 0.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 6         | 0.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 6         | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 6         | 0.56%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 6         | 0.56%   |
| Ralink MT7601U Wireless Adapter                                               | 5         | 0.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 5         | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 5         | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 5         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 5         | 0.47%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 0.47%   |
| Intel Centrino Ultimate-N 6300                                                | 5         | 0.47%   |
| Intel 82567LM Gigabit Network Connection                                      | 5         | 0.47%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 5         | 0.47%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 4         | 0.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 4         | 0.37%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 4         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 4         | 0.37%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 4         | 0.37%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 4         | 0.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 4         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 186       | 34.19%  |
| Qualcomm Atheros                | 145       | 26.65%  |
| Realtek Semiconductor           | 90        | 16.54%  |
| Broadcom                        | 60        | 11.03%  |
| Ralink                          | 23        | 4.23%   |
| Broadcom Limited                | 17        | 3.13%   |
| TP-Link                         | 9         | 1.65%   |
| Ralink Technology               | 8         | 1.47%   |
| Tenda                           | 1         | 0.18%   |
| Qualcomm Atheros Communications | 1         | 0.18%   |
| NetGear                         | 1         | 0.18%   |
| MediaTek                        | 1         | 0.18%   |
| Linksys                         | 1         | 0.18%   |
| Dell                            | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 34        | 6.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 28        | 5.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 27        | 4.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 24        | 4.38%   |
| Intel Wireless 7260                                                           | 22        | 4.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 19        | 3.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 18        | 3.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 17        | 3.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 11        | 2.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 11        | 2.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 11        | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 10        | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 10        | 1.82%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 10        | 1.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 10        | 1.82%   |
| Intel Wireless 7265                                                           | 9         | 1.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 8         | 1.46%   |
| Intel Wireless 3160                                                           | 8         | 1.46%   |
| Intel WiFi Link 5100                                                          | 8         | 1.46%   |
| Intel Wi-Fi 6 AX200                                                           | 8         | 1.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 7         | 1.28%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 7         | 1.28%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 6         | 1.09%   |
| Realtek 802.11ac NIC                                                          | 6         | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 6         | 1.09%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 6         | 1.09%   |
| Intel Wireless 8260                                                           | 6         | 1.09%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 6         | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 6         | 1.09%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 6         | 1.09%   |
| Ralink MT7601U Wireless Adapter                                               | 5         | 0.91%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 5         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 5         | 0.91%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                                | 5         | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 5         | 0.91%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 4         | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 4         | 0.73%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 4         | 0.73%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 4         | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 4         | 0.73%   |
| Intel Wireless 3165                                                           | 4         | 0.73%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 4         | 0.73%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 4         | 0.73%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                   | 4         | 0.73%   |
| Broadcom Limited BCM4311 802.11a/b/g                                          | 4         | 0.73%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 4         | 0.73%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 3         | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 0.55%   |
| Realtek RTL8187B Wireless Adapter                                             | 3         | 0.55%   |
| Intel Wi-Fi 6 AX201                                                           | 3         | 0.55%   |
| Intel Ultimate N WiFi Link 5300                                               | 3         | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 3         | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 0.55%   |
| Intel Centrino Wireless-N 2230                                                | 3         | 0.55%   |
| Intel Centrino Wireless-N 130                                                 | 3         | 0.55%   |
| Intel Centrino Wireless-N 100                                                 | 3         | 0.55%   |
| Intel Centrino Advanced-N 6200                                                | 3         | 0.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 3         | 0.55%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 3         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 248       | 49.6%   |
| Intel                            | 72        | 14.4%   |
| Qualcomm Atheros                 | 45        | 9%      |
| Broadcom                         | 45        | 9%      |
| Marvell Technology Group         | 26        | 5.2%    |
| Nvidia                           | 10        | 2%      |
| Attansic Technology              | 9         | 1.8%    |
| Broadcom Limited                 | 8         | 1.6%    |
| ASIX Electronics                 | 7         | 1.4%    |
| Silicon Integrated Systems [SiS] | 5         | 1%      |
| Samsung Electronics              | 5         | 1%      |
| Xiaomi                           | 4         | 0.8%    |
| VIA Technologies                 | 3         | 0.6%    |
| Fibocom                          | 2         | 0.4%    |
| Research In Motion               | 1         | 0.2%    |
| Qualcomm                         | 1         | 0.2%    |
| OnePlus Technology (Shenzhen)    | 1         | 0.2%    |
| Microchip Technology             | 1         | 0.2%    |
| LG Electronics                   | 1         | 0.2%    |
| Lab126                           | 1         | 0.2%    |
| JMicron Technology               | 1         | 0.2%    |
| Intersil                         | 1         | 0.2%    |
| ICS Advent                       | 1         | 0.2%    |
| Hewlett-Packard                  | 1         | 0.2%    |
| 3Com                             | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 123       | 24.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 90        | 17.93%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 20        | 3.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 13        | 2.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 11        | 2.19%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                | 10        | 1.99%   |
| Intel 82577LM Gigabit Network Connection                             | 9         | 1.79%   |
| Attansic AR8152 v2.0 Fast Ethernet                                   | 9         | 1.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                 | 7         | 1.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 7         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 6         | 1.2%    |
| Intel Ethernet Connection I218-LM                                    | 6         | 1.2%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                    | 6         | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 6         | 1.2%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                | 5         | 1%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 5         | 1%      |
| Intel 82567LM Gigabit Network Connection                             | 5         | 1%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter        | 4         | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                                | 4         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 4         | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 4         | 0.8%    |
| Nvidia MCP67 Ethernet                                                | 4         | 0.8%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller              | 4         | 0.8%    |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                 | 4         | 0.8%    |
| Intel Ethernet Connection I219-V                                     | 4         | 0.8%    |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express             | 4         | 0.8%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express       | 4         | 0.8%    |
| Broadcom BCM4401-B0 100Base-TX                                       | 4         | 0.8%    |
| VIA VT6102/VT6103 [Rhine-II]                                         | 3         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 3         | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                           | 3         | 0.6%    |
| Nvidia MCP51 Ethernet Controller                                     | 3         | 0.6%    |
| Intel PRO/100 VE Network Connection                                  | 3         | 0.6%    |
| Intel Ethernet Connection I217-LM                                    | 3         | 0.6%    |
| Intel 82579V Gigabit Network Connection                              | 3         | 0.6%    |
| Intel 82577LC Gigabit Network Connection                             | 3         | 0.6%    |
| Intel 82573L Gigabit Ethernet Controller                             | 3         | 0.6%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express               | 3         | 0.6%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                      | 3         | 0.6%    |
| ASIX AX88772A Fast Ethernet                                          | 3         | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                        | 3         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 2         | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                 | 2         | 0.4%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 2         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                        | 2         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 2         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller            | 2         | 0.4%    |
| Nvidia MCP77 Ethernet                                                | 2         | 0.4%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller              | 2         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller              | 2         | 0.4%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller              | 2         | 0.4%    |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                 | 2         | 0.4%    |
| Intel Ethernet Connection I219-LM                                    | 2         | 0.4%    |
| Intel Ethernet Connection I217-V                                     | 2         | 0.4%    |
| Intel Ethernet Connection (4) I219-LM                                | 2         | 0.4%    |
| Intel 82566MM Gigabit Network Connection                             | 2         | 0.4%    |
| Intel 82562GT 10/100 Network Connection                              | 2         | 0.4%    |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 2         | 0.4%    |
| Fibocom L831-EAU-00                                                  | 2         | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                    | 2         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 520       | 51.28%  |
| Ethernet | 475       | 46.84%  |
| Modem    | 19        | 1.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 428       | 76.29%  |
| Ethernet | 133       | 23.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 427       | 77.22%  |
| 1     | 89        | 16.09%  |
| 0     | 31        | 5.61%   |
| 3     | 6         | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 489       | 86.86%  |
| Yes  | 74        | 13.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 102       | 30.18%  |
| Realtek Semiconductor           | 35        | 10.36%  |
| Qualcomm Atheros Communications | 33        | 9.76%   |
| Broadcom                        | 29        | 8.58%   |
| Cambridge Silicon Radio         | 19        | 5.62%   |
| IMC Networks                    | 16        | 4.73%   |
| Lite-On Technology              | 14        | 4.14%   |
| Hewlett-Packard                 | 14        | 4.14%   |
| Apple                           | 14        | 4.14%   |
| Foxconn / Hon Hai               | 12        | 3.55%   |
| Dell                            | 12        | 3.55%   |
| Toshiba                         | 9         | 2.66%   |
| Ralink                          | 8         | 2.37%   |
| Alps Electric                   | 8         | 2.37%   |
| ASUSTek Computer                | 5         | 1.48%   |
| Ralink Technology               | 2         | 0.59%   |
| Askey Computer                  | 2         | 0.59%   |
| Qcom                            | 1         | 0.3%    |
| Micro Star International        | 1         | 0.3%    |
| MediaTek                        | 1         | 0.3%    |
| Chicony Electronics             | 1         | 0.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 58        | 17.11%  |
| Realtek Bluetooth Radio                                                             | 21        | 6.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 19        | 5.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 5.31%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 3.83%   |
| Apple Bluetooth Host Controller                                                     | 10        | 2.95%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 2.36%   |
| Intel AX200 Bluetooth                                                               | 8         | 2.36%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 2.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 7         | 2.06%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 1.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 1.77%   |
| Intel Bluetooth Device                                                              | 6         | 1.77%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.77%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.47%   |
| IMC Networks Bluetooth module                                                       | 5         | 1.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 5         | 1.47%   |
| Toshiba Integrated Bluetooth HCI                                                    | 4         | 1.18%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 1.18%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 1.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 4         | 1.18%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.18%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.18%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 1.18%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.18%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 1.18%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 1.18%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 0.88%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.88%   |
| Dell Wireless 365 Bluetooth                                                         | 3         | 0.88%   |
| Dell Wireless 350 Bluetooth                                                         | 3         | 0.88%   |
| Broadcom BCM2045 Bluetooth                                                          | 3         | 0.88%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.88%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 3         | 0.88%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.59%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.59%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 2         | 0.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.59%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.59%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 2         | 0.59%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 0.59%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.59%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.59%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.59%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.59%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 2         | 0.59%   |
| Askey Bluetooth Device                                                              | 2         | 0.59%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 2         | 0.59%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 2         | 0.59%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.29%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.29%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.29%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.29%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.29%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.29%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.29%   |
| Micro Star International Bluetooth EDR Device                                       | 1         | 0.29%   |
| MediaTek BT                                                                         | 1         | 0.29%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 409       | 69.91%  |
| AMD                               | 110       | 18.8%   |
| Nvidia                            | 46        | 7.86%   |
| Silicon Integrated Systems [SiS]  | 6         | 1.03%   |
| VIA Technologies                  | 3         | 0.51%   |
| GN Netcom                         | 3         | 0.51%   |
| C-Media Electronics               | 3         | 0.51%   |
| Plantronics                       | 2         | 0.34%   |
| Logitech                          | 2         | 0.34%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 51        | 7.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 44        | 6.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 43        | 6.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 35        | 4.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 34        | 4.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 32        | 4.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 30        | 4.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 28        | 3.95%   |
| Intel 8 Series HD Audio Controller                                                                | 27        | 3.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 26        | 3.67%   |
| AMD FCH Azalia Controller                                                                         | 26        | 3.67%   |
| AMD Wrestler HDMI Audio                                                                           | 22        | 3.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 17        | 2.4%    |
| AMD High Definition Audio Controller                                                              | 16        | 2.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 2.26%   |
| AMD Kabini HDMI/DP Audio                                                                          | 15        | 2.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 1.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 1.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 1.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.27%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.27%   |
| Nvidia High Definition Audio Controller                                                           | 8         | 1.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 0.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 0.85%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 5         | 0.71%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.71%   |
| Nvidia MCP67 High Definition Audio                                                                | 4         | 0.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 4         | 0.56%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 0.56%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 4         | 0.56%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.42%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.42%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 3         | 0.42%   |
| Nvidia MCP51 High Definition Audio                                                                | 3         | 0.42%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.42%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.42%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 0.42%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 3         | 0.42%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.28%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.28%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.28%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 0.28%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.28%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.28%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2         | 0.28%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 2         | 0.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.28%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 2         | 0.28%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.28%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.28%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 90        | 23.08%  |
| Unknown             | 81        | 20.77%  |
| SK hynix            | 72        | 18.46%  |
| Micron Technology   | 39        | 10%     |
| Kingston            | 19        | 4.87%   |
| A-DATA Technology   | 12        | 3.08%   |
| Corsair             | 11        | 2.82%   |
| Crucial             | 10        | 2.56%   |
| Nanya Technology    | 9         | 2.31%   |
| Elpida              | 9         | 2.31%   |
| Unknown (ABCD)      | 6         | 1.54%   |
| Smart               | 6         | 1.54%   |
| Team                | 3         | 0.77%   |
| Teikon              | 2         | 0.51%   |
| Qimonda             | 2         | 0.51%   |
| Patriot             | 2         | 0.51%   |
| Apacer              | 2         | 0.51%   |
| Transcend           | 1         | 0.26%   |
| Toshiba             | 1         | 0.26%   |
| Smart Brazil        | 1         | 0.26%   |
| Sesame              | 1         | 0.26%   |
| Ramaxel Technology  | 1         | 0.26%   |
| PNY                 | 1         | 0.26%   |
| Neo Forza           | 1         | 0.26%   |
| Multilaser          | 1         | 0.26%   |
| HMD                 | 1         | 0.26%   |
| High Bridge         | 1         | 0.26%   |
| Goldkey             | 1         | 0.26%   |
| G.Skill             | 1         | 0.26%   |
| Digiboard           | 1         | 0.26%   |
| Avant               | 1         | 0.26%   |
| ASint Technology    | 1         | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 11        | 2.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 8         | 1.87%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 8         | 1.87%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 7         | 1.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 7         | 1.64%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 6         | 1.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 6         | 1.4%    |
| Unknown RAM Module 1024MB SODIMM DRAM                               | 5         | 1.17%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 1.17%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 5         | 1.17%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.93%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 4         | 0.93%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 4         | 0.93%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 4         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 3         | 0.7%    |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 3         | 0.7%    |
| Unknown RAM Module 1024MB SODIMM DDR                                | 3         | 0.7%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 3         | 0.7%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 0.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 0.7%    |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.7%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 3         | 0.7%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 3         | 0.7%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.7%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 0.7%    |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s         | 3         | 0.7%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 3         | 0.7%    |
| Kingston RAM ACR16D3LS1KNG/4G 4GB SODIMM DDR3 1600MT/s              | 3         | 0.7%    |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                   | 3         | 0.7%    |
| Unknown RAM Module 512MB SODIMM DDR2                                | 2         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                      | 2         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 2         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 2         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                         | 2         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                           | 2         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                              | 2         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 2         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                      | 2         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 2         | 0.47%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                       | 2         | 0.47%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                     | 2         | 0.47%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.47%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.47%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.47%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 2         | 0.47%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                     | 2         | 0.47%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 2         | 0.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.47%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.47%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR2 2048MT/s              | 2         | 0.47%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4096MB SODIMM DDR3 1334MT/s             | 2         | 0.47%   |
| Micron RAM MT52L512M32D2PF-09 4096MB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.47%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                       | 2         | 0.47%   |
| Micron RAM Module 4096MB SODIMM DDR4 3200MT/s                       | 2         | 0.47%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 2         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 171       | 50.44%  |
| DDR4    | 73        | 21.53%  |
| DDR2    | 47        | 13.86%  |
| SDRAM   | 12        | 3.54%   |
| LPDDR4  | 11        | 3.24%   |
| LPDDR3  | 9         | 2.65%   |
| DRAM    | 7         | 2.06%   |
| DDR     | 6         | 1.77%   |
| Unknown | 3         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 309       | 92.51%  |
| Row Of Chips | 16        | 4.79%   |
| DIMM         | 5         | 1.5%    |
| Unknown      | 3         | 0.9%    |
| Chip         | 1         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 149       | 38.11%  |
| 2048  | 105       | 26.85%  |
| 8192  | 65        | 16.62%  |
| 1024  | 46        | 11.76%  |
| 16384 | 15        | 3.84%   |
| 512   | 8         | 2.05%   |
| 32768 | 1         | 0.26%   |
| 256   | 1         | 0.26%   |
| 128   | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 97        | 26.36%  |
| 1334    | 36        | 9.78%   |
| 2667    | 29        | 7.88%   |
| Unknown | 28        | 7.61%   |
| 1333    | 27        | 7.34%   |
| 2400    | 26        | 7.07%   |
| 667     | 26        | 7.07%   |
| 3200    | 17        | 4.62%   |
| 1066    | 13        | 3.53%   |
| 1067    | 11        | 2.99%   |
| 533     | 11        | 2.99%   |
| 2133    | 10        | 2.72%   |
| 3266    | 6         | 1.63%   |
| 2048    | 5         | 1.36%   |
| 1867    | 5         | 1.36%   |
| 800     | 5         | 1.36%   |
| 1866    | 4         | 1.09%   |
| 4267    | 3         | 0.82%   |
| 4199    | 3         | 0.82%   |
| 975     | 2         | 0.54%   |
| 8400    | 1         | 0.27%   |
| 1200    | 1         | 0.27%   |
| 2       | 1         | 0.27%   |
| 1       | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 3         | 27.27%  |
| Brother Industries    | 3         | 27.27%  |
| Samsung Electronics   | 2         | 18.18%  |
| STMicroelectronics    | 1         | 9.09%   |
| Lexmark International | 1         | 9.09%   |
| Canon                 | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| STMicroelectronics USB Printer P     | 1         | 9.09%   |
| Samsung SCX-4200 series              | 1         | 9.09%   |
| Samsung ML-1640 Series Laser Printer | 1         | 9.09%   |
| Lexmark International MS610de        | 1         | 9.09%   |
| HP LaserJet 1200                     | 1         | 9.09%   |
| HP Deskjet 3520 series               | 1         | 9.09%   |
| HP Deskjet 1050 J410                 | 1         | 9.09%   |
| Canon MF3110                         | 1         | 9.09%   |
| Brother PTUSB Printing               | 1         | 9.09%   |
| Brother PT-2450DX                    | 1         | 9.09%   |
| Brother DCP-7055W                    | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 50%     |
| Canon CanoScan LiDE 500F                                      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 120       | 27.78%  |
| IMC Networks                           | 37        | 8.56%   |
| Realtek Semiconductor                  | 34        | 7.87%   |
| Microdia                               | 28        | 6.48%   |
| Suyin                                  | 27        | 6.25%   |
| Acer                                   | 25        | 5.79%   |
| Sunplus Innovation Technology          | 17        | 3.94%   |
| Silicon Motion                         | 17        | 3.94%   |
| Quanta                                 | 17        | 3.94%   |
| Alcor Micro                            | 17        | 3.94%   |
| Apple                                  | 16        | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 15        | 3.47%   |
| Syntek                                 | 9         | 2.08%   |
| Ricoh                                  | 9         | 2.08%   |
| Lite-On Technology                     | 9         | 2.08%   |
| Lenovo                                 | 6         | 1.39%   |
| Importek                               | 4         | 0.93%   |
| GEMBIRD                                | 3         | 0.69%   |
| Z-Star Microelectronics                | 2         | 0.46%   |
| Samsung Electronics                    | 2         | 0.46%   |
| Luxvisions Innotech Limited            | 2         | 0.46%   |
| icSpring                               | 2         | 0.46%   |
| ALi                                    | 2         | 0.46%   |
| Y Media                                | 1         | 0.23%   |
| Toshiba                                | 1         | 0.23%   |
| SunplusIT                              | 1         | 0.23%   |
| OmniVision Technologies                | 1         | 0.23%   |
| Novatek Microelectronics               | 1         | 0.23%   |
| Nintendo                               | 1         | 0.23%   |
| Logitech                               | 1         | 0.23%   |
| LG Electronics                         | 1         | 0.23%   |
| Genesys Logic                          | 1         | 0.23%   |
| Generalplus Technology                 | 1         | 0.23%   |
| DigiTech                               | 1         | 0.23%   |
| Creative Technology                    | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 10        | 2.3%    |
| Chicony Integrated Camera                           | 10        | 2.3%    |
| Alcor Micro USB 2.0 Camera                          | 10        | 2.3%    |
| Chicony HP Truevision HD                            | 8         | 1.84%   |
| Chicony EasyCamera                                  | 8         | 1.84%   |
| Chicony HD WebCam                                   | 7         | 1.61%   |
| IMC Networks UVC VGA Webcam                         | 6         | 1.38%   |
| Chicony TOSHIBA Web Camera - HD                     | 6         | 1.38%   |
| Chicony HP HD Webcam                                | 6         | 1.38%   |
| Apple FaceTime HD Camera                            | 6         | 1.38%   |
| Silicon Motion WebCam SC-0311139N                   | 5         | 1.15%   |
| Realtek USB Camera                                  | 5         | 1.15%   |
| IMC Networks USB 2.0 UVC VGA WebCam                 | 5         | 1.15%   |
| Chicony HP Webcam                                   | 5         | 1.15%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 5         | 1.15%   |
| Acer Lenovo EasyCamera                              | 5         | 1.15%   |
| Suyin Acer CrystalEye Webcam                        | 4         | 0.92%   |
| Sunplus HD WebCam                                   | 4         | 0.92%   |
| Quanta HP Webcam                                    | 4         | 0.92%   |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 0.92%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 4         | 0.92%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 0.92%   |
| Chicony USB 2.0 Camera                              | 4         | 0.92%   |
| Chicony HP HD Camera                                | 4         | 0.92%   |
| Apple iPhone 5/5C/5S/6/SE                           | 4         | 0.92%   |
| Alcor Micro Asus Integrated Webcam                  | 4         | 0.92%   |
| Suyin WebCam                                        | 3         | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 0.69%   |
| Sunplus HP HD Webcam [Fixed]                        | 3         | 0.69%   |
| Sunplus Asus Webcam                                 | 3         | 0.69%   |
| Realtek Integrated Webcam                           | 3         | 0.69%   |
| Quanta HP HD Camera                                 | 3         | 0.69%   |
| Microdia Sonix USB 2.0 Camera                       | 3         | 0.69%   |
| Microdia Laptop_Integrated_Webcam_2M                | 3         | 0.69%   |
| Microdia Integrated_Webcam_HD                       | 3         | 0.69%   |
| Microdia 1.3 MPixel Integrated Webcam               | 3         | 0.69%   |
| Lite-On TOSHIBA Web Camera - HD                     | 3         | 0.69%   |
| Lite-On HP HD Camera                                | 3         | 0.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 0.69%   |
| IMC Networks USB 2.0 Camera                         | 3         | 0.69%   |
| IMC Networks Lenovo EasyCamera                      | 3         | 0.69%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]   | 3         | 0.69%   |
| Chicony Lenovo EasyCamera                           | 3         | 0.69%   |
| Chicony Integrated HP HD Webcam                     | 3         | 0.69%   |
| Chicony HD WebCam (Acer)                            | 3         | 0.69%   |
| Chicony Camera                                      | 3         | 0.69%   |
| Acer VGA WebCam                                     | 3         | 0.69%   |
| Acer HD WebCam                                      | 3         | 0.69%   |
| Syntek Integrated Camera                            | 2         | 0.46%   |
| Syntek EasyCamera                                   | 2         | 0.46%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 0.46%   |
| Suyin HP TrueVision HD                              | 2         | 0.46%   |
| Sunplus Laptop Integrated Webcam HD                 | 2         | 0.46%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 0.46%   |
| Silicon Motion WebCam SC-13HDL11939N                | 2         | 0.46%   |
| Silicon Motion WebCam SC-10HDD12636N                | 2         | 0.46%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 0.46%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 2         | 0.46%   |
| Realtek USB2.0 HD UVC WebCam                        | 2         | 0.46%   |
| Realtek Lenovo EasyCamera                           | 2         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 27        | 46.55%  |
| AuthenTec                  | 11        | 18.97%  |
| Upek                       | 7         | 12.07%  |
| STMicroelectronics         | 5         | 8.62%   |
| Shenzhen Goodix Technology | 4         | 6.9%    |
| Synaptics                  | 3         | 5.17%   |
| LighTuning Technology      | 1         | 1.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 10.34%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 6         | 10.34%  |
| STMicroelectronics Fingerprint Reader                      | 5         | 8.62%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 4         | 6.9%    |
| Validity Sensors VFS491                                    | 3         | 5.17%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 3         | 5.17%   |
| AuthenTec AES2810                                          | 3         | 5.17%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 3         | 5.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.45%   |
| Validity Sensors Fingerprint scanner                       | 2         | 3.45%   |
| Shenzhen Goodix FingerPrint                                | 2         | 3.45%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 2         | 3.45%   |
| AuthenTec AES1600                                          | 2         | 3.45%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.72%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.72%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 1.72%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 1.72%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.72%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 1.72%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.72%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 1.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 1.72%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 1.72%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 1.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 1.72%   |
| AuthenTec Fingerprint Sensor                               | 1         | 1.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| O2 Micro              | 7         | 33.33%  |
| Broadcom              | 6         | 28.57%  |
| Alcor Micro           | 6         | 28.57%  |
| Upek                  | 1         | 4.76%   |
| Realtek Semiconductor | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 28.57%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 23.81%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 14.29%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 9.52%   |
| Broadcom 5880                                                                | 2         | 9.52%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.76%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 419       | 75.09%  |
| 1     | 110       | 19.71%  |
| 2     | 24        | 4.3%    |
| 3     | 4         | 0.72%   |
| 4     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 58        | 33.72%  |
| Graphics card            | 26        | 15.12%  |
| Net/wireless             | 21        | 12.21%  |
| Chipcard                 | 19        | 11.05%  |
| Bluetooth                | 12        | 6.98%   |
| Modem                    | 8         | 4.65%   |
| Camera                   | 6         | 3.49%   |
| Storage                  | 5         | 2.91%   |
| Net/ethernet             | 4         | 2.33%   |
| Flash memory             | 4         | 2.33%   |
| Multimedia controller    | 3         | 1.74%   |
| Communication controller | 3         | 1.74%   |
| Sound                    | 2         | 1.16%   |
| Card reader              | 1         | 0.58%   |

