Linux in France - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in France.

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

Total: 8691

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dm1                | [f4c8f5a8e6](https://linux-hardware.org/?probe=f4c8f5a8e6) | Feb 02, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [e05005f76b](https://linux-hardware.org/?probe=e05005f76b) | Feb 02, 2024 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [3aa20161d9](https://linux-hardware.org/?probe=3aa20161d9) | Feb 02, 2024 |
| Samsung       | RV410/RV510/S3510/E3510     | [1f85f107bb](https://linux-hardware.org/?probe=1f85f107bb) | Feb 02, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [d9a0906eac](https://linux-hardware.org/?probe=d9a0906eac) | Feb 02, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | [c01e746574](https://linux-hardware.org/?probe=c01e746574) | Feb 02, 2024 |
| ALTYK         | L14F-I5U16-N1               | [7cb618fcca](https://linux-hardware.org/?probe=7cb618fcca) | Feb 01, 2024 |
| ALTYK         | L14F-I5U16-N1               | [81274a6f09](https://linux-hardware.org/?probe=81274a6f09) | Feb 01, 2024 |
| Apple         | MacBookPro1,2               | [5e40347a6e](https://linux-hardware.org/?probe=5e40347a6e) | Feb 01, 2024 |
| Acer          | Aspire E5-722               | [2a4988436d](https://linux-hardware.org/?probe=2a4988436d) | Feb 01, 2024 |
| Thomson       | N15C8BK2T                   | [5de65dcec1](https://linux-hardware.org/?probe=5de65dcec1) | Jan 31, 2024 |
| HP            | ENVY dv6                    | [a91621750a](https://linux-hardware.org/?probe=a91621750a) | Jan 31, 2024 |
| HP            | EliteBook 840 G1            | [920b1ecb34](https://linux-hardware.org/?probe=920b1ecb34) | Jan 31, 2024 |
| HP            | EliteBook 8440p             | [e8c221770b](https://linux-hardware.org/?probe=e8c221770b) | Jan 31, 2024 |
| Dell          | Latitude 5501               | [7c92ef29c9](https://linux-hardware.org/?probe=7c92ef29c9) | Jan 31, 2024 |
| HP            | Pavilion 17                 | [27b6494c43](https://linux-hardware.org/?probe=27b6494c43) | Jan 31, 2024 |
| HP            | Pavilion g6                 | [7f9863aaa2](https://linux-hardware.org/?probe=7f9863aaa2) | Jan 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [8d8a09ab09](https://linux-hardware.org/?probe=8d8a09ab09) | Jan 31, 2024 |
| Packard Be... | EasyNote ENLG71BM           | [ab713b894e](https://linux-hardware.org/?probe=ab713b894e) | Jan 31, 2024 |
| Acer          | Swift SF514-56T             | [14b287861f](https://linux-hardware.org/?probe=14b287861f) | Jan 31, 2024 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [5193f57d67](https://linux-hardware.org/?probe=5193f57d67) | Jan 31, 2024 |
| HP            | ZBook 17 G3                 | [fefc37bfa1](https://linux-hardware.org/?probe=fefc37bfa1) | Jan 30, 2024 |
| HP            | Pavilion dv7                | [7899a3498e](https://linux-hardware.org/?probe=7899a3498e) | Jan 30, 2024 |
| HP            | ZBook 17 G3                 | [525b120614](https://linux-hardware.org/?probe=525b120614) | Jan 30, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K3C... | [649745f3ae](https://linux-hardware.org/?probe=649745f3ae) | Jan 30, 2024 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [0af07cd951](https://linux-hardware.org/?probe=0af07cd951) | Jan 30, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d78102063d](https://linux-hardware.org/?probe=d78102063d) | Jan 30, 2024 |
| HP            | EliteBook 8460p             | [9fd5ed9142](https://linux-hardware.org/?probe=9fd5ed9142) | Jan 30, 2024 |
| Acer          | Aspire 9420                 | [d0c7154097](https://linux-hardware.org/?probe=d0c7154097) | Jan 30, 2024 |
| Medion        | E15423                      | [2d39a42a0a](https://linux-hardware.org/?probe=2d39a42a0a) | Jan 29, 2024 |
| Toshiba       | Satellite P300              | [14da91750f](https://linux-hardware.org/?probe=14da91750f) | Jan 29, 2024 |
| HP            | EliteBook 860 16 inch G1... | [737d54004b](https://linux-hardware.org/?probe=737d54004b) | Jan 29, 2024 |
| HP            | 250 G7 Notebook PC          | [9dab8601c1](https://linux-hardware.org/?probe=9dab8601c1) | Jan 29, 2024 |
| Dell          | Inspiron N5110              | [eaf977415d](https://linux-hardware.org/?probe=eaf977415d) | Jan 29, 2024 |
| HUAWEI        | BOM-WXX9                    | [346c925e80](https://linux-hardware.org/?probe=346c925e80) | Jan 29, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [0c4fb535dc](https://linux-hardware.org/?probe=0c4fb535dc) | Jan 29, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [79381fe2e8](https://linux-hardware.org/?probe=79381fe2e8) | Jan 29, 2024 |
| Acer          | Nitro AN515-57              | [e179099ff6](https://linux-hardware.org/?probe=e179099ff6) | Jan 29, 2024 |
| Lenovo        | ThinkPad T61 6464AS3        | [1aa0d9f766](https://linux-hardware.org/?probe=1aa0d9f766) | Jan 28, 2024 |
| HP            | Notebook                    | [d8a6181633](https://linux-hardware.org/?probe=d8a6181633) | Jan 28, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1069da15da](https://linux-hardware.org/?probe=1069da15da) | Jan 28, 2024 |
| Apple         | MacBookPro10,1              | [35238c08e4](https://linux-hardware.org/?probe=35238c08e4) | Jan 28, 2024 |
| Dell          | Latitude E6530              | [185381cc95](https://linux-hardware.org/?probe=185381cc95) | Jan 28, 2024 |
| ASUSTek       | X541UJ                      | [14f153b6c9](https://linux-hardware.org/?probe=14f153b6c9) | Jan 28, 2024 |
| HP            | Notebook                    | [78ffba1358](https://linux-hardware.org/?probe=78ffba1358) | Jan 27, 2024 |
| Dell          | Latitude 7390 2-in-1        | [d57566edb3](https://linux-hardware.org/?probe=d57566edb3) | Jan 27, 2024 |
| Dell          | Latitude 7390 2-in-1        | [26a44b8cab](https://linux-hardware.org/?probe=26a44b8cab) | Jan 27, 2024 |
| Dell          | Inspiron N7010              | [21ed3bec20](https://linux-hardware.org/?probe=21ed3bec20) | Jan 27, 2024 |
| Acer          | Aspire 6530G                | [cd71356945](https://linux-hardware.org/?probe=cd71356945) | Jan 26, 2024 |
| Samsung       | N150/N210/N220              | [11b2fc832f](https://linux-hardware.org/?probe=11b2fc832f) | Jan 26, 2024 |
| Toshiba       | Satellite L300              | [127697d4f1](https://linux-hardware.org/?probe=127697d4f1) | Jan 26, 2024 |
| Toshiba       | Satellite L300              | [63be13a245](https://linux-hardware.org/?probe=63be13a245) | Jan 26, 2024 |
| Dell          | Latitude 5521               | [0524c08c30](https://linux-hardware.org/?probe=0524c08c30) | Jan 26, 2024 |
| UNOWHY        | Y13G011S4EI                 | [30193a9845](https://linux-hardware.org/?probe=30193a9845) | Jan 26, 2024 |
| Dell          | Latitude 5490               | [f1fe39af02](https://linux-hardware.org/?probe=f1fe39af02) | Jan 26, 2024 |
| Google        | Markarth                    | [39dface7d9](https://linux-hardware.org/?probe=39dface7d9) | Jan 26, 2024 |
| Apple         | MacBook5,1                  | [51346a4084](https://linux-hardware.org/?probe=51346a4084) | Jan 25, 2024 |
| HP            | Compaq 6730s                | [caa48b80fb](https://linux-hardware.org/?probe=caa48b80fb) | Jan 25, 2024 |
| Dell          | Latitude 7340               | [880054b099](https://linux-hardware.org/?probe=880054b099) | Jan 25, 2024 |
| HP            | EliteBook 865 16 inch G1... | [72f849d40c](https://linux-hardware.org/?probe=72f849d40c) | Jan 25, 2024 |
| Acer          | Aspire A317-53              | [9b9d2bfdc3](https://linux-hardware.org/?probe=9b9d2bfdc3) | Jan 25, 2024 |
| Fujitsu       | LIFEBOOK A531               | [647bf81332](https://linux-hardware.org/?probe=647bf81332) | Jan 25, 2024 |
| Dell          | Precision 5510              | [e1e543eaa4](https://linux-hardware.org/?probe=e1e543eaa4) | Jan 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [86ff649a4d](https://linux-hardware.org/?probe=86ff649a4d) | Jan 24, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P3540FA_... | [a20369a079](https://linux-hardware.org/?probe=a20369a079) | Jan 24, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P3540FA_... | [9ac42c58bf](https://linux-hardware.org/?probe=9ac42c58bf) | Jan 24, 2024 |
| Google        | Markarth                    | [2258b38e4b](https://linux-hardware.org/?probe=2258b38e4b) | Jan 24, 2024 |
| Dell          | Vostro1710                  | [1fc84171b5](https://linux-hardware.org/?probe=1fc84171b5) | Jan 24, 2024 |
| Toshiba       | Satellite Pro NB10-A-125    | [6594f8afba](https://linux-hardware.org/?probe=6594f8afba) | Jan 24, 2024 |
| MSI           | GL62M 7RDX                  | [bd42ee7dc8](https://linux-hardware.org/?probe=bd42ee7dc8) | Jan 24, 2024 |
| LDLC          | SPC-I                       | [518c66f608](https://linux-hardware.org/?probe=518c66f608) | Jan 23, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [122f69f8c5](https://linux-hardware.org/?probe=122f69f8c5) | Jan 23, 2024 |
| Dell          | Latitude 5521               | [34567d3078](https://linux-hardware.org/?probe=34567d3078) | Jan 23, 2024 |
| Dell          | XPS 13 9360                 | [cf5a6036e8](https://linux-hardware.org/?probe=cf5a6036e8) | Jan 23, 2024 |
| Lenovo        | Legion 5 17ACH6 82K0        | [5bd83d3f0c](https://linux-hardware.org/?probe=5bd83d3f0c) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [48f8a71c93](https://linux-hardware.org/?probe=48f8a71c93) | Jan 23, 2024 |
| Dell          | Latitude 5521               | [76aa51e658](https://linux-hardware.org/?probe=76aa51e658) | Jan 23, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [c22fff0afb](https://linux-hardware.org/?probe=c22fff0afb) | Jan 23, 2024 |
| Dell          | Precision 5540              | [604697c5db](https://linux-hardware.org/?probe=604697c5db) | Jan 23, 2024 |
| Google        | Woomax                      | [8b76a06477](https://linux-hardware.org/?probe=8b76a06477) | Jan 23, 2024 |
| Dell          | Inspiron 5567               | [dc061193f2](https://linux-hardware.org/?probe=dc061193f2) | Jan 22, 2024 |
| HP            | Pavilion dv6                | [ac628c20c7](https://linux-hardware.org/?probe=ac628c20c7) | Jan 22, 2024 |
| HP            | Pavilion dv6                | [6d29e8c44e](https://linux-hardware.org/?probe=6d29e8c44e) | Jan 22, 2024 |
| HUAWEI        | BoDE-WXX9                   | [1cfa83e1fc](https://linux-hardware.org/?probe=1cfa83e1fc) | Jan 22, 2024 |
| Medion        | Deputy P50                  | [57081b7e90](https://linux-hardware.org/?probe=57081b7e90) | Jan 22, 2024 |
| ASUSTek       | X550LA                      | [3010861da1](https://linux-hardware.org/?probe=3010861da1) | Jan 21, 2024 |
| MSI           | GF63 Thin 11UC              | [b6fa224856](https://linux-hardware.org/?probe=b6fa224856) | Jan 21, 2024 |
| Samsung       | N150/N210/N220              | [044a8a24d6](https://linux-hardware.org/?probe=044a8a24d6) | Jan 21, 2024 |
| ASUSTek       | X75VCP                      | [63c2472460](https://linux-hardware.org/?probe=63c2472460) | Jan 21, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [58f6bacae6](https://linux-hardware.org/?probe=58f6bacae6) | Jan 21, 2024 |
| Notebook      | W65_W67RZ1                  | [3ad0a034e4](https://linux-hardware.org/?probe=3ad0a034e4) | Jan 21, 2024 |
| Toshiba       | Satellite C70-B             | [452f1d82f7](https://linux-hardware.org/?probe=452f1d82f7) | Jan 21, 2024 |
| Dell          | Precision 5480              | [2ebc089368](https://linux-hardware.org/?probe=2ebc089368) | Jan 20, 2024 |
| HP            | ProBook 450 G0              | [18424b46c5](https://linux-hardware.org/?probe=18424b46c5) | Jan 20, 2024 |
| Lenovo        | Z50-70 20354                | [3260559363](https://linux-hardware.org/?probe=3260559363) | Jan 20, 2024 |
| Notebook      | W54_55SU1,SUW               | [c66b9a59bb](https://linux-hardware.org/?probe=c66b9a59bb) | Jan 20, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [06567bb3ae](https://linux-hardware.org/?probe=06567bb3ae) | Jan 20, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [01db0b0650](https://linux-hardware.org/?probe=01db0b0650) | Jan 20, 2024 |
| Dell          | Precision 7560              | [f5a631a694](https://linux-hardware.org/?probe=f5a631a694) | Jan 19, 2024 |
| Apple         | MacBookPro15,2              | [b36cb3cc5a](https://linux-hardware.org/?probe=b36cb3cc5a) | Jan 19, 2024 |
| Acer          | Nitro AN515-58              | [e0368be539](https://linux-hardware.org/?probe=e0368be539) | Jan 19, 2024 |
| Medion        | Crawler E30e                | [537214d414](https://linux-hardware.org/?probe=537214d414) | Jan 18, 2024 |
| Medion        | Crawler E30e                | [76c56f06b5](https://linux-hardware.org/?probe=76c56f06b5) | Jan 18, 2024 |
| HP            | ZBook 15u G5                | [334b143154](https://linux-hardware.org/?probe=334b143154) | Jan 17, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [385ae61d79](https://linux-hardware.org/?probe=385ae61d79) | Jan 17, 2024 |
| Dell          | XPS 15 7590                 | [226e37fde1](https://linux-hardware.org/?probe=226e37fde1) | Jan 17, 2024 |
| Medion        | Defender P30                | [d8f109106c](https://linux-hardware.org/?probe=d8f109106c) | Jan 17, 2024 |
| PC Special... | GK5NPFO                     | [f7eda564b1](https://linux-hardware.org/?probe=f7eda564b1) | Jan 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [11e51bc70c](https://linux-hardware.org/?probe=11e51bc70c) | Jan 17, 2024 |
| Dell          | G3 3500                     | [0fd2b03a7c](https://linux-hardware.org/?probe=0fd2b03a7c) | Jan 17, 2024 |
| HP            | 250 G5 Notebook PC          | [099418d854](https://linux-hardware.org/?probe=099418d854) | Jan 16, 2024 |
| UNOWHY        | Y13G010S4EI                 | [9768c4c698](https://linux-hardware.org/?probe=9768c4c698) | Jan 16, 2024 |
| Packard Be... | EasyNote TJ65               | [bcf20a0a9c](https://linux-hardware.org/?probe=bcf20a0a9c) | Jan 16, 2024 |
| Lenovo        | B590 62743QG                | [53c2b981bf](https://linux-hardware.org/?probe=53c2b981bf) | Jan 16, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [f73401456d](https://linux-hardware.org/?probe=f73401456d) | Jan 16, 2024 |
| Lenovo        | ThinkPad Edge 030253G       | [f5b2d04869](https://linux-hardware.org/?probe=f5b2d04869) | Jan 16, 2024 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [60df96228f](https://linux-hardware.org/?probe=60df96228f) | Jan 16, 2024 |
| ASUSTek       | X555LAB                     | [a5e1ffbe3f](https://linux-hardware.org/?probe=a5e1ffbe3f) | Jan 15, 2024 |
| Dell          | Latitude E6400              | [704c5e4d39](https://linux-hardware.org/?probe=704c5e4d39) | Jan 15, 2024 |
| ASUSTek       | ROG Strix G513QC_PX513QC    | [bfecaac2ee](https://linux-hardware.org/?probe=bfecaac2ee) | Jan 14, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [bdbb97ace1](https://linux-hardware.org/?probe=bdbb97ace1) | Jan 14, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [3b89bdc1d9](https://linux-hardware.org/?probe=3b89bdc1d9) | Jan 14, 2024 |
| MSI           | GF63 Thin 11UC              | [6d2801d1d8](https://linux-hardware.org/?probe=6d2801d1d8) | Jan 14, 2024 |
| Lenovo        | ThinkPad X230 2325BA3       | [2663e39ea0](https://linux-hardware.org/?probe=2663e39ea0) | Jan 14, 2024 |
| Dell          | Latitude E6400              | [035c1106d9](https://linux-hardware.org/?probe=035c1106d9) | Jan 13, 2024 |
| Sony          | SVF1521H2EW                 | [ef7a3ce205](https://linux-hardware.org/?probe=ef7a3ce205) | Jan 13, 2024 |
| Lenovo        | G50-70 20351                | [5187db04f2](https://linux-hardware.org/?probe=5187db04f2) | Jan 13, 2024 |
| HP            | Pavilion Laptop 14-dv0xx... | [fb216e5ee6](https://linux-hardware.org/?probe=fb216e5ee6) | Jan 12, 2024 |
| HP            | ZBook 15                    | [390b667998](https://linux-hardware.org/?probe=390b667998) | Jan 12, 2024 |
| Dell          | Precision 7560              | [c540ef8073](https://linux-hardware.org/?probe=c540ef8073) | Jan 12, 2024 |
| HP            | ZBook 15                    | [5649070333](https://linux-hardware.org/?probe=5649070333) | Jan 12, 2024 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [bb96dd4a3c](https://linux-hardware.org/?probe=bb96dd4a3c) | Jan 12, 2024 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [7b99f5e393](https://linux-hardware.org/?probe=7b99f5e393) | Jan 12, 2024 |
| Dell          | Latitude 7300               | [0ad6fa9f50](https://linux-hardware.org/?probe=0ad6fa9f50) | Jan 12, 2024 |
| Toshiba       | Satellite C55-C             | [191762e8f6](https://linux-hardware.org/?probe=191762e8f6) | Jan 12, 2024 |
| Dell          | XPS 15 9570                 | [3f6db7dde8](https://linux-hardware.org/?probe=3f6db7dde8) | Jan 11, 2024 |
| Medion        | Crawler E30e                | [2d2cd7c215](https://linux-hardware.org/?probe=2d2cd7c215) | Jan 11, 2024 |
| Acer          | Aspire R3-131T              | [98521cc1f9](https://linux-hardware.org/?probe=98521cc1f9) | Jan 10, 2024 |
| Acer          | Aspire R3-131T              | [23b6c85a7f](https://linux-hardware.org/?probe=23b6c85a7f) | Jan 10, 2024 |
| HUAWEI        | HVY-WXX9                    | [2a28690851](https://linux-hardware.org/?probe=2a28690851) | Jan 10, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [681ea2eb1a](https://linux-hardware.org/?probe=681ea2eb1a) | Jan 10, 2024 |
| HUAWEI        | BOHB-WAX9                   | [f962b901f7](https://linux-hardware.org/?probe=f962b901f7) | Jan 10, 2024 |
| HUAWEI        | BOHB-WAX9                   | [763d9d2018](https://linux-hardware.org/?probe=763d9d2018) | Jan 10, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [2894cc00dc](https://linux-hardware.org/?probe=2894cc00dc) | Jan 10, 2024 |
| Dell          | Precision 7520              | [a36b0e554a](https://linux-hardware.org/?probe=a36b0e554a) | Jan 10, 2024 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [d9894176d4](https://linux-hardware.org/?probe=d9894176d4) | Jan 10, 2024 |
| Dell          | Inspiron 16 7610            | [2605684e23](https://linux-hardware.org/?probe=2605684e23) | Jan 09, 2024 |
| Acer          | Aspire E5-571               | [a9f2a0569a](https://linux-hardware.org/?probe=a9f2a0569a) | Jan 09, 2024 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [87f2d98083](https://linux-hardware.org/?probe=87f2d98083) | Jan 09, 2024 |
| Apple         | MacBook5,1                  | [75835b3764](https://linux-hardware.org/?probe=75835b3764) | Jan 09, 2024 |
| Toshiba       | Satellite Pro C660          | [3e32f98160](https://linux-hardware.org/?probe=3e32f98160) | Jan 09, 2024 |
| Dell          | Latitude 5440               | [6ab5039217](https://linux-hardware.org/?probe=6ab5039217) | Jan 09, 2024 |
| Apple         | MacBookAir9,1               | [143ae6dd48](https://linux-hardware.org/?probe=143ae6dd48) | Jan 09, 2024 |
| Dell          | Latitude 5590               | [80ab1a3a35](https://linux-hardware.org/?probe=80ab1a3a35) | Jan 08, 2024 |
| Toshiba       | Satellite P200              | [bda7517862](https://linux-hardware.org/?probe=bda7517862) | Jan 08, 2024 |
| Dell          | XPS 15 9530                 | [40a1d7ca08](https://linux-hardware.org/?probe=40a1d7ca08) | Jan 08, 2024 |
| Lenovo        | ThinkPad E550 20DF0052FR    | [d23e6bf17a](https://linux-hardware.org/?probe=d23e6bf17a) | Jan 08, 2024 |
| Lenovo        | ThinkPad X260 20F5S6V200    | [421cb02ac3](https://linux-hardware.org/?probe=421cb02ac3) | Jan 08, 2024 |
| Lenovo        | ThinkPad X230 2325Y3G       | [f2c9141668](https://linux-hardware.org/?probe=f2c9141668) | Jan 08, 2024 |
| HP            | ZBook 15 G3                 | [05ad98f468](https://linux-hardware.org/?probe=05ad98f468) | Jan 08, 2024 |
| Dell          | Precision 3571              | [9a96981f77](https://linux-hardware.org/?probe=9a96981f77) | Jan 08, 2024 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [cce2fde2ac](https://linux-hardware.org/?probe=cce2fde2ac) | Jan 08, 2024 |
| Dell          | Precision 5510              | [521a57df4a](https://linux-hardware.org/?probe=521a57df4a) | Jan 08, 2024 |
| Sony          | SVF1521G6EW                 | [de442d56ef](https://linux-hardware.org/?probe=de442d56ef) | Jan 08, 2024 |
| Acer          | Swift SF314-511             | [14eac9efff](https://linux-hardware.org/?probe=14eac9efff) | Jan 07, 2024 |
| Acer          | Aspire A315-24P             | [fccab2dc4a](https://linux-hardware.org/?probe=fccab2dc4a) | Jan 07, 2024 |
| HP            | EliteBook 840 G5            | [391ab997b5](https://linux-hardware.org/?probe=391ab997b5) | Jan 07, 2024 |
| Toshiba       | PORTEGE R500                | [315837012b](https://linux-hardware.org/?probe=315837012b) | Jan 07, 2024 |
| Lenovo        | IdeaPad 510S-13ISK 80SJ     | [90fe273da6](https://linux-hardware.org/?probe=90fe273da6) | Jan 06, 2024 |
| Apple         | MacBook5,1                  | [3a4a960ff8](https://linux-hardware.org/?probe=3a4a960ff8) | Jan 06, 2024 |
| HP            | EliteBook Folio 1040 G3     | [c33fb1df3f](https://linux-hardware.org/?probe=c33fb1df3f) | Jan 06, 2024 |
| Toshiba       | Satellite L655              | [75ab5d9c47](https://linux-hardware.org/?probe=75ab5d9c47) | Jan 06, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7f3dd6873f](https://linux-hardware.org/?probe=7f3dd6873f) | Jan 06, 2024 |
| Dell          | Inspiron 5515               | [6ff66dee9c](https://linux-hardware.org/?probe=6ff66dee9c) | Jan 06, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2846bd9486](https://linux-hardware.org/?probe=2846bd9486) | Jan 06, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c733e5bbb6](https://linux-hardware.org/?probe=c733e5bbb6) | Jan 06, 2024 |
| Dell          | Inspiron 5480               | [fb0ac8ac2b](https://linux-hardware.org/?probe=fb0ac8ac2b) | Jan 06, 2024 |
| Dell          | XPS 15 9570                 | [090d0eae61](https://linux-hardware.org/?probe=090d0eae61) | Jan 05, 2024 |
| HP            | Pavilion dv7                | [2ecfa94f3b](https://linux-hardware.org/?probe=2ecfa94f3b) | Jan 05, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [687eb2054f](https://linux-hardware.org/?probe=687eb2054f) | Jan 05, 2024 |
| Thomson       | N17V3C8WH512                | [37fa4a2a98](https://linux-hardware.org/?probe=37fa4a2a98) | Jan 05, 2024 |
| HP            | EliteBook 840 G6            | [0e3e8e1d4a](https://linux-hardware.org/?probe=0e3e8e1d4a) | Jan 05, 2024 |
| Dell          | Venue 11 Pro 5130           | [4b4853f647](https://linux-hardware.org/?probe=4b4853f647) | Jan 05, 2024 |
| Unknown       | Unknown                     | [402ff82119](https://linux-hardware.org/?probe=402ff82119) | Jan 04, 2024 |
| Apple         | MacBookPro5,5               | [5242f988d3](https://linux-hardware.org/?probe=5242f988d3) | Jan 04, 2024 |
| Dell          | XPS 9315                    | [9cfbab7e05](https://linux-hardware.org/?probe=9cfbab7e05) | Jan 04, 2024 |
| Dell          | XPS 15 9510                 | [7df831af81](https://linux-hardware.org/?probe=7df831af81) | Jan 04, 2024 |
| Dell          | XPS 15 9510                 | [338187cb01](https://linux-hardware.org/?probe=338187cb01) | Jan 04, 2024 |
| HP            | Pavilion Power Laptop 15... | [37ea5af9b1](https://linux-hardware.org/?probe=37ea5af9b1) | Jan 04, 2024 |
| Dell          | XPS 17 9730                 | [b8400fab0f](https://linux-hardware.org/?probe=b8400fab0f) | Jan 04, 2024 |
| Toshiba       | PORTEGE R30-A               | [8830dd30d3](https://linux-hardware.org/?probe=8830dd30d3) | Jan 04, 2024 |
| Dell          | XPS 13 9360                 | [6d877fb5f9](https://linux-hardware.org/?probe=6d877fb5f9) | Jan 04, 2024 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [050bd9db54](https://linux-hardware.org/?probe=050bd9db54) | Jan 04, 2024 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [2575bb7352](https://linux-hardware.org/?probe=2575bb7352) | Jan 04, 2024 |
| Dell          | Latitude E7250              | [0c6c42e76e](https://linux-hardware.org/?probe=0c6c42e76e) | Jan 03, 2024 |
| Packard Be... | EasyNote LM85               | [e756bb57ba](https://linux-hardware.org/?probe=e756bb57ba) | Jan 03, 2024 |
| ASUSTek       | 1015CX                      | [55d418530d](https://linux-hardware.org/?probe=55d418530d) | Jan 03, 2024 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [f845df595a](https://linux-hardware.org/?probe=f845df595a) | Jan 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [d139ce529e](https://linux-hardware.org/?probe=d139ce529e) | Jan 03, 2024 |
| Acer          | Nitro AN515-58              | [638b0599b5](https://linux-hardware.org/?probe=638b0599b5) | Jan 03, 2024 |
| Acer          | Aspire ES1-572              | [3ad96238e4](https://linux-hardware.org/?probe=3ad96238e4) | Jan 02, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [2b2856700c](https://linux-hardware.org/?probe=2b2856700c) | Jan 02, 2024 |
| HP            | ProBook 6570b               | [113503a0a8](https://linux-hardware.org/?probe=113503a0a8) | Jan 02, 2024 |
| ASUSTek       | G75VX                       | [7f8494ffcf](https://linux-hardware.org/?probe=7f8494ffcf) | Jan 02, 2024 |
| HP            | Pavilion dv6                | [61a52110ba](https://linux-hardware.org/?probe=61a52110ba) | Jan 02, 2024 |
| HP            | ProBook 6570b               | [98ccfce078](https://linux-hardware.org/?probe=98ccfce078) | Jan 02, 2024 |
| Dell          | Latitude 5590               | [847f4fd079](https://linux-hardware.org/?probe=847f4fd079) | Jan 02, 2024 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [a679e6f722](https://linux-hardware.org/?probe=a679e6f722) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [20f988146c](https://linux-hardware.org/?probe=20f988146c) | Jan 01, 2024 |
| HP            | Pavilion 17                 | [77a7431f73](https://linux-hardware.org/?probe=77a7431f73) | Dec 31, 2023 |
| Toshiba       | Satellite Pro C660          | [c3736ea548](https://linux-hardware.org/?probe=c3736ea548) | Dec 31, 2023 |
| ASUSTek       | K53U                        | [84ba38c3c5](https://linux-hardware.org/?probe=84ba38c3c5) | Dec 31, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [a4596b8ae1](https://linux-hardware.org/?probe=a4596b8ae1) | Dec 31, 2023 |
| HP            | ProBook 470 G3              | [22bd0ee412](https://linux-hardware.org/?probe=22bd0ee412) | Dec 30, 2023 |
| MSI           | Prestige 15 A10SC           | [e61eb5428f](https://linux-hardware.org/?probe=e61eb5428f) | Dec 30, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [aa1bee686a](https://linux-hardware.org/?probe=aa1bee686a) | Dec 30, 2023 |
| ASUSTek       | X751LJ                      | [0ebf64067f](https://linux-hardware.org/?probe=0ebf64067f) | Dec 30, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [c6751f4e51](https://linux-hardware.org/?probe=c6751f4e51) | Dec 30, 2023 |
| Acer          | Aspire A517-52              | [0dfed3df52](https://linux-hardware.org/?probe=0dfed3df52) | Dec 30, 2023 |
| Acer          | Aspire A517-52              | [1c4684011d](https://linux-hardware.org/?probe=1c4684011d) | Dec 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [01c6121d4c](https://linux-hardware.org/?probe=01c6121d4c) | Dec 29, 2023 |
| HP            | ProBook 650 G1              | [c7383a1237](https://linux-hardware.org/?probe=c7383a1237) | Dec 29, 2023 |
| HP            | ProBook 650 G1              | [cc8196ebec](https://linux-hardware.org/?probe=cc8196ebec) | Dec 29, 2023 |
| Toshiba       | Satellite C50D-A-138        | [cfb74314e2](https://linux-hardware.org/?probe=cfb74314e2) | Dec 29, 2023 |
| HP            | ProBook 655 G2              | [50589e94ba](https://linux-hardware.org/?probe=50589e94ba) | Dec 29, 2023 |
| ASUSTek       | K53BE                       | [23efadbf2f](https://linux-hardware.org/?probe=23efadbf2f) | Dec 29, 2023 |
| HP            | ProBook 655 G2              | [71ef8433cc](https://linux-hardware.org/?probe=71ef8433cc) | Dec 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | [f37cd9143d](https://linux-hardware.org/?probe=f37cd9143d) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [791788fbbc](https://linux-hardware.org/?probe=791788fbbc) | Dec 29, 2023 |
| Toshiba       | Satellite L655              | [c7e2a4aa7c](https://linux-hardware.org/?probe=c7e2a4aa7c) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [4861953728](https://linux-hardware.org/?probe=4861953728) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [650d02f634](https://linux-hardware.org/?probe=650d02f634) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [0a2d1d5688](https://linux-hardware.org/?probe=0a2d1d5688) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [3d0513bb6c](https://linux-hardware.org/?probe=3d0513bb6c) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | [af69ec2d33](https://linux-hardware.org/?probe=af69ec2d33) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | [143c6b4161](https://linux-hardware.org/?probe=143c6b4161) | Dec 29, 2023 |
| Star Labs     | StarBook                    | [930fb359dd](https://linux-hardware.org/?probe=930fb359dd) | Dec 29, 2023 |
| Notebook      | NL40_50CU                   | [a91c55ef9f](https://linux-hardware.org/?probe=a91c55ef9f) | Dec 28, 2023 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [e0bfd9face](https://linux-hardware.org/?probe=e0bfd9face) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [76b6ceb6cf](https://linux-hardware.org/?probe=76b6ceb6cf) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [32b6e45042](https://linux-hardware.org/?probe=32b6e45042) | Dec 28, 2023 |
| HP            | OMEN Laptop 15-ek1xxx       | [16c7cb0337](https://linux-hardware.org/?probe=16c7cb0337) | Dec 28, 2023 |
| HP            | ZBook 15                    | [92d7e45b22](https://linux-hardware.org/?probe=92d7e45b22) | Dec 28, 2023 |
| HP            | EliteBook 840 G2            | [bbce6fb229](https://linux-hardware.org/?probe=bbce6fb229) | Dec 28, 2023 |
| Lenovo        | ThinkPad L540 20AUS0N200    | [e94a7fb094](https://linux-hardware.org/?probe=e94a7fb094) | Dec 28, 2023 |
| Lenovo        | ThinkPad L540 20AV0031FR    | [96e1e4403d](https://linux-hardware.org/?probe=96e1e4403d) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [98b0838eb2](https://linux-hardware.org/?probe=98b0838eb2) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [4eb0a16723](https://linux-hardware.org/?probe=4eb0a16723) | Dec 28, 2023 |
| HP            | EliteBook 840 G2            | [6ba5504a6f](https://linux-hardware.org/?probe=6ba5504a6f) | Dec 28, 2023 |
| Google        | Lillipup                    | [e8ac3dc206](https://linux-hardware.org/?probe=e8ac3dc206) | Dec 28, 2023 |
| ASUSTek       | X555LB                      | [f29fe264f5](https://linux-hardware.org/?probe=f29fe264f5) | Dec 28, 2023 |
| UNOWHY        | Y13G012S4EI                 | [a3bb952104](https://linux-hardware.org/?probe=a3bb952104) | Dec 27, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | [c16f162169](https://linux-hardware.org/?probe=c16f162169) | Dec 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [e36502092e](https://linux-hardware.org/?probe=e36502092e) | Dec 27, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [3d96eb6f36](https://linux-hardware.org/?probe=3d96eb6f36) | Dec 27, 2023 |
| Lenovo        | ThinkPad L530 2475A61       | [990d8dce86](https://linux-hardware.org/?probe=990d8dce86) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | [e623c937a6](https://linux-hardware.org/?probe=e623c937a6) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | [f6c6dba166](https://linux-hardware.org/?probe=f6c6dba166) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [705f4fa6fd](https://linux-hardware.org/?probe=705f4fa6fd) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | [9435700f28](https://linux-hardware.org/?probe=9435700f28) | Dec 27, 2023 |
| Dell          | Latitude E7440              | [6e44f58de9](https://linux-hardware.org/?probe=6e44f58de9) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [06264d7b71](https://linux-hardware.org/?probe=06264d7b71) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [09c41915d8](https://linux-hardware.org/?probe=09c41915d8) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [a89881fc3b](https://linux-hardware.org/?probe=a89881fc3b) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [b18f714a89](https://linux-hardware.org/?probe=b18f714a89) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | [2424999ad8](https://linux-hardware.org/?probe=2424999ad8) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | [1126414dff](https://linux-hardware.org/?probe=1126414dff) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | [2ddc54287d](https://linux-hardware.org/?probe=2ddc54287d) | Dec 27, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [8017d1c054](https://linux-hardware.org/?probe=8017d1c054) | Dec 27, 2023 |
| HONOR         | NMH-WCX9                    | [5647df79c0](https://linux-hardware.org/?probe=5647df79c0) | Dec 26, 2023 |
| HP            | ProBook 450 G3              | [1e952ed878](https://linux-hardware.org/?probe=1e952ed878) | Dec 26, 2023 |
| Lenovo        | ThinkPad P50 20EQS1MY00     | [a49698d49d](https://linux-hardware.org/?probe=a49698d49d) | Dec 26, 2023 |
| Lenovo        | Unknown                     | [5d5f205d61](https://linux-hardware.org/?probe=5d5f205d61) | Dec 26, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [db50c73272](https://linux-hardware.org/?probe=db50c73272) | Dec 26, 2023 |
| Acer          | Aspire ES1-572              | [64d63264dc](https://linux-hardware.org/?probe=64d63264dc) | Dec 25, 2023 |
| Acer          | Aspire ES1-572              | [2698d102c0](https://linux-hardware.org/?probe=2698d102c0) | Dec 25, 2023 |
| Acer          | Swift SF314-51              | [a2f71698e2](https://linux-hardware.org/?probe=a2f71698e2) | Dec 25, 2023 |
| MSI           | GX70 3CC                    | [30d22e2d74](https://linux-hardware.org/?probe=30d22e2d74) | Dec 25, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [d775a90c0e](https://linux-hardware.org/?probe=d775a90c0e) | Dec 25, 2023 |
| HP            | Pavilion g7                 | [f6a852d547](https://linux-hardware.org/?probe=f6a852d547) | Dec 24, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | [28ab1a916a](https://linux-hardware.org/?probe=28ab1a916a) | Dec 24, 2023 |
| Toshiba       | Satellite L655              | [679c502604](https://linux-hardware.org/?probe=679c502604) | Dec 24, 2023 |
| eMachines     | E725                        | [830cb3faa4](https://linux-hardware.org/?probe=830cb3faa4) | Dec 24, 2023 |
| Google        | Magolor                     | [f5d079bc79](https://linux-hardware.org/?probe=f5d079bc79) | Dec 24, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [6cc304ea54](https://linux-hardware.org/?probe=6cc304ea54) | Dec 23, 2023 |
| Dell          | Latitude E4310              | [41f607e5e5](https://linux-hardware.org/?probe=41f607e5e5) | Dec 23, 2023 |
| Acer          | Aspire ES1-572              | [e726ce9f63](https://linux-hardware.org/?probe=e726ce9f63) | Dec 23, 2023 |
| Sony          | VPCEA1S1E                   | [af850dd5f3](https://linux-hardware.org/?probe=af850dd5f3) | Dec 23, 2023 |
| HP            | ProBook 655 G2              | [033325e722](https://linux-hardware.org/?probe=033325e722) | Dec 23, 2023 |
| Alienware     | m15 R7 AMD                  | [9d80128f05](https://linux-hardware.org/?probe=9d80128f05) | Dec 23, 2023 |
| MSI           | GE62 2QF                    | [cf9a783196](https://linux-hardware.org/?probe=cf9a783196) | Dec 23, 2023 |
| ASUSTek       | T100TA                      | [9ad17d2d3c](https://linux-hardware.org/?probe=9ad17d2d3c) | Dec 23, 2023 |
| eMachines     | E527                        | [cf5b096be7](https://linux-hardware.org/?probe=cf5b096be7) | Dec 22, 2023 |
| GPD           | G1621-02                    | [eaf78f9da1](https://linux-hardware.org/?probe=eaf78f9da1) | Dec 22, 2023 |
| Dell          | Studio 1737                 | [a157d70ea2](https://linux-hardware.org/?probe=a157d70ea2) | Dec 22, 2023 |
| Dell          | Latitude 14 Rugged (5404... | [084f663c15](https://linux-hardware.org/?probe=084f663c15) | Dec 22, 2023 |
| Acer          | Aspire 5742G                | [1f9d486306](https://linux-hardware.org/?probe=1f9d486306) | Dec 22, 2023 |
| Dell          | Latitude E6440              | [904540fc01](https://linux-hardware.org/?probe=904540fc01) | Dec 21, 2023 |
| Dell          | System Vostro 3750          | [aa1fb5d9a6](https://linux-hardware.org/?probe=aa1fb5d9a6) | Dec 21, 2023 |
| HONOR         | HYM-WXX                     | [1c225a853e](https://linux-hardware.org/?probe=1c225a853e) | Dec 21, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [907851c66b](https://linux-hardware.org/?probe=907851c66b) | Dec 21, 2023 |
| Toshiba       | Satellite L655              | [7a1001a094](https://linux-hardware.org/?probe=7a1001a094) | Dec 21, 2023 |
| Dell          | Precision 3581              | [aa0186ade6](https://linux-hardware.org/?probe=aa0186ade6) | Dec 21, 2023 |
| Dell          | Inspiron 15 3535            | [466204d787](https://linux-hardware.org/?probe=466204d787) | Dec 21, 2023 |
| Dell          | Latitude 5590               | [9877862088](https://linux-hardware.org/?probe=9877862088) | Dec 21, 2023 |
| Acer          | Aspire E1-771G              | [07bcd26f94](https://linux-hardware.org/?probe=07bcd26f94) | Dec 20, 2023 |
| Dell          | Latitude 5590               | [4f307c792f](https://linux-hardware.org/?probe=4f307c792f) | Dec 20, 2023 |
| HP            | Pavilion dv6                | [4cc379dfbd](https://linux-hardware.org/?probe=4cc379dfbd) | Dec 19, 2023 |
| HP            | EliteBook 840 14 inch G1... | [2222f1a1fb](https://linux-hardware.org/?probe=2222f1a1fb) | Dec 19, 2023 |
| Dell          | G7 7790                     | [bcc6b4046b](https://linux-hardware.org/?probe=bcc6b4046b) | Dec 19, 2023 |
| Acer          | Nitro ANV15-51              | [c4ddaa9bc4](https://linux-hardware.org/?probe=c4ddaa9bc4) | Dec 19, 2023 |
| DellInc.      | Venue 8 Pro 5830            | [d6408a26a1](https://linux-hardware.org/?probe=d6408a26a1) | Dec 19, 2023 |
| Acer          | Nitro ANV15-51              | [aa343c3d4f](https://linux-hardware.org/?probe=aa343c3d4f) | Dec 19, 2023 |
| HP            | Pavilion 17                 | [449c36ff1c](https://linux-hardware.org/?probe=449c36ff1c) | Dec 19, 2023 |
| MSI           | Bravo 15 B5DD               | [7bb3bd0328](https://linux-hardware.org/?probe=7bb3bd0328) | Dec 18, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [02ffa90273](https://linux-hardware.org/?probe=02ffa90273) | Dec 18, 2023 |
| Dell          | Precision 7530              | [6de510283f](https://linux-hardware.org/?probe=6de510283f) | Dec 18, 2023 |
| Dell          | Latitude 7440               | [644c46aba6](https://linux-hardware.org/?probe=644c46aba6) | Dec 18, 2023 |
| Dell          | Venue 11 Pro 5130           | [74cdfd92c0](https://linux-hardware.org/?probe=74cdfd92c0) | Dec 18, 2023 |
| Fujitsu       | LIFEBOOK A512               | [0c3974dad9](https://linux-hardware.org/?probe=0c3974dad9) | Dec 18, 2023 |
| Acer          | Aspire S7-391               | [ab734913e8](https://linux-hardware.org/?probe=ab734913e8) | Dec 17, 2023 |
| Acer          | Aspire S7-391               | [1d66b3f887](https://linux-hardware.org/?probe=1d66b3f887) | Dec 17, 2023 |
| Acer          | Nitro AN517-54              | [80aeddc1b2](https://linux-hardware.org/?probe=80aeddc1b2) | Dec 17, 2023 |
| HP            | ZBook 17 G5                 | [288e976604](https://linux-hardware.org/?probe=288e976604) | Dec 17, 2023 |
| Acer          | Nitro AN517-54              | [2f2bcf0c97](https://linux-hardware.org/?probe=2f2bcf0c97) | Dec 17, 2023 |
| Dell          | G5 5587                     | [0200ad8ea9](https://linux-hardware.org/?probe=0200ad8ea9) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [6e359357d4](https://linux-hardware.org/?probe=6e359357d4) | Dec 17, 2023 |
| HP            | Compaq 6730s                | [628e8cf362](https://linux-hardware.org/?probe=628e8cf362) | Dec 17, 2023 |
| HP            | Compaq 6730s                | [774f3d4feb](https://linux-hardware.org/?probe=774f3d4feb) | Dec 17, 2023 |
| ASUSTek       | X456UB                      | [5a4a0662e1](https://linux-hardware.org/?probe=5a4a0662e1) | Dec 17, 2023 |
| MSI           | GF63 Thin 11UC              | [06556bd61a](https://linux-hardware.org/?probe=06556bd61a) | Dec 17, 2023 |
| Google        | Woomax                      | [7516d70c03](https://linux-hardware.org/?probe=7516d70c03) | Dec 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | [b90524a691](https://linux-hardware.org/?probe=b90524a691) | Dec 16, 2023 |
| Toshiba       | Satellite L655              | [5f625c9177](https://linux-hardware.org/?probe=5f625c9177) | Dec 16, 2023 |
| Dell          | Inspiron 14 5420            | [ef0c78ce49](https://linux-hardware.org/?probe=ef0c78ce49) | Dec 16, 2023 |
| Lenovo        | ThinkPad T420 4238AW2       | [01fae631cf](https://linux-hardware.org/?probe=01fae631cf) | Dec 16, 2023 |
| Toshiba       | Satellite C660D             | [4277f53694](https://linux-hardware.org/?probe=4277f53694) | Dec 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [bac2e83dd7](https://linux-hardware.org/?probe=bac2e83dd7) | Dec 16, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [12c5d1d331](https://linux-hardware.org/?probe=12c5d1d331) | Dec 16, 2023 |
| MSI           | Katana GF66 11SC            | [1eb5b02078](https://linux-hardware.org/?probe=1eb5b02078) | Dec 15, 2023 |
| Apple         | MacBookAir6,2               | [31426d7740](https://linux-hardware.org/?probe=31426d7740) | Dec 15, 2023 |
| Sony          | SVF1521G6EW                 | [55b5387ed5](https://linux-hardware.org/?probe=55b5387ed5) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [05141b9b76](https://linux-hardware.org/?probe=05141b9b76) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [a869524ac6](https://linux-hardware.org/?probe=a869524ac6) | Dec 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [51e42890da](https://linux-hardware.org/?probe=51e42890da) | Dec 14, 2023 |
| Dell          | Precision 5510              | [ddc02a6165](https://linux-hardware.org/?probe=ddc02a6165) | Dec 14, 2023 |
| GPD           | G1619-04                    | [27dd6e79da](https://linux-hardware.org/?probe=27dd6e79da) | Dec 14, 2023 |
| Dell          | XPS 15 9520                 | [ac8fb0b18d](https://linux-hardware.org/?probe=ac8fb0b18d) | Dec 14, 2023 |
| ASUSTek       | E403SA                      | [141030490c](https://linux-hardware.org/?probe=141030490c) | Dec 14, 2023 |
| HP            | Pavilion 17                 | [81e5865518](https://linux-hardware.org/?probe=81e5865518) | Dec 14, 2023 |
| Apple         | MacBookPro5,1               | [277dadb387](https://linux-hardware.org/?probe=277dadb387) | Dec 13, 2023 |
| Packard Be... | EasyNote LM85               | [18a9f48bee](https://linux-hardware.org/?probe=18a9f48bee) | Dec 13, 2023 |
| Lenovo        | V110-15IAP 80TG             | [de6e3bf0eb](https://linux-hardware.org/?probe=de6e3bf0eb) | Dec 13, 2023 |
| Dell          | Precision 5510              | [0ce634decf](https://linux-hardware.org/?probe=0ce634decf) | Dec 13, 2023 |
| Timi          | TM1604                      | [67597f3bd5](https://linux-hardware.org/?probe=67597f3bd5) | Dec 13, 2023 |
| HP            | ZBook 17                    | [d1269ca08c](https://linux-hardware.org/?probe=d1269ca08c) | Dec 13, 2023 |
| HP            | EliteBook 840 G3            | [01752b90ef](https://linux-hardware.org/?probe=01752b90ef) | Dec 12, 2023 |
| ASUSTek       | P553UA                      | [9a0bb65e3f](https://linux-hardware.org/?probe=9a0bb65e3f) | Dec 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [4293932b86](https://linux-hardware.org/?probe=4293932b86) | Dec 12, 2023 |
| Dell          | Inspiron 7591               | [10a266d0ff](https://linux-hardware.org/?probe=10a266d0ff) | Dec 12, 2023 |
| Acer          | Aspire E1-571               | [4576cb723a](https://linux-hardware.org/?probe=4576cb723a) | Dec 12, 2023 |
| Dell          | Latitude E6320              | [dbacdcadba](https://linux-hardware.org/?probe=dbacdcadba) | Dec 12, 2023 |
| Valve         | Galileo                     | [beb6edb04f](https://linux-hardware.org/?probe=beb6edb04f) | Dec 12, 2023 |
| ASUSTek       | G551JM                      | [10dfa9e380](https://linux-hardware.org/?probe=10dfa9e380) | Dec 12, 2023 |
| MSI           | GX60 1AC/GX60 3AE/GX60 3... | [262637b1e2](https://linux-hardware.org/?probe=262637b1e2) | Dec 11, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [ffcb3c9798](https://linux-hardware.org/?probe=ffcb3c9798) | Dec 11, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [8a61a6bdd6](https://linux-hardware.org/?probe=8a61a6bdd6) | Dec 11, 2023 |
| HP            | ProBook 450 G3              | [57a80d9d1b](https://linux-hardware.org/?probe=57a80d9d1b) | Dec 11, 2023 |
| GPD           | G1619-03                    | [92773d52d8](https://linux-hardware.org/?probe=92773d52d8) | Dec 10, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [dbf172e6c8](https://linux-hardware.org/?probe=dbf172e6c8) | Dec 10, 2023 |
| Acer          | Aspire ES1-572              | [c66bd8de67](https://linux-hardware.org/?probe=c66bd8de67) | Dec 10, 2023 |
| HP            | EliteBook 820 G3            | [50335a1ca6](https://linux-hardware.org/?probe=50335a1ca6) | Dec 09, 2023 |
| HP            | ProBook 640 G2              | [0989548d19](https://linux-hardware.org/?probe=0989548d19) | Dec 09, 2023 |
| Toshiba       | Satellite C870D-116         | [78a800febe](https://linux-hardware.org/?probe=78a800febe) | Dec 09, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [b3f7b8b30a](https://linux-hardware.org/?probe=b3f7b8b30a) | Dec 09, 2023 |
| Dell          | Inspiron 7591               | [7907f73ee0](https://linux-hardware.org/?probe=7907f73ee0) | Dec 09, 2023 |
| Valve         | Jupiter                     | [7d649cef63](https://linux-hardware.org/?probe=7d649cef63) | Dec 09, 2023 |
| GPD           | G1619-03                    | [bc2ade83b8](https://linux-hardware.org/?probe=bc2ade83b8) | Dec 08, 2023 |
| ASUSTek       | X555BP                      | [b7680df948](https://linux-hardware.org/?probe=b7680df948) | Dec 07, 2023 |
| Acer          | Aspire E1-771G              | [099fae46db](https://linux-hardware.org/?probe=099fae46db) | Dec 07, 2023 |
| Toshiba       | Satellite C70-B             | [6493c4fcf8](https://linux-hardware.org/?probe=6493c4fcf8) | Dec 07, 2023 |
| Unknown       | AX15                        | [3eb1590b8e](https://linux-hardware.org/?probe=3eb1590b8e) | Dec 07, 2023 |
| Toshiba       | Satellite L655              | [dc8c17b9fd](https://linux-hardware.org/?probe=dc8c17b9fd) | Dec 07, 2023 |
| Acer          | Aspire E1-771G              | [28f6aca279](https://linux-hardware.org/?probe=28f6aca279) | Dec 06, 2023 |
| HP            | Laptop 15-db0xxx            | [8b324f5c18](https://linux-hardware.org/?probe=8b324f5c18) | Dec 06, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [beaa75c727](https://linux-hardware.org/?probe=beaa75c727) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5e71510e4c](https://linux-hardware.org/?probe=5e71510e4c) | Dec 06, 2023 |
| Toshiba       | Satellite C70-B             | [ea76b3e92c](https://linux-hardware.org/?probe=ea76b3e92c) | Dec 06, 2023 |
| Acer          | Swift SF515-51T             | [941ba24cf2](https://linux-hardware.org/?probe=941ba24cf2) | Dec 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS5QV00    | [d04d3a298f](https://linux-hardware.org/?probe=d04d3a298f) | Dec 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0JC0... | [11fdf05513](https://linux-hardware.org/?probe=11fdf05513) | Dec 05, 2023 |
| HP            | 15                          | [561269f586](https://linux-hardware.org/?probe=561269f586) | Dec 05, 2023 |
| Dell          | Inspiron 15 5510            | [f20f7f2563](https://linux-hardware.org/?probe=f20f7f2563) | Dec 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [6e9230f8ab](https://linux-hardware.org/?probe=6e9230f8ab) | Dec 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [e6e58d5148](https://linux-hardware.org/?probe=e6e58d5148) | Dec 05, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [fe06cb32bc](https://linux-hardware.org/?probe=fe06cb32bc) | Dec 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [da8437565a](https://linux-hardware.org/?probe=da8437565a) | Dec 04, 2023 |
| Lenovo        | G50-45 80E3                 | [9cbacbf139](https://linux-hardware.org/?probe=9cbacbf139) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3f26c37883](https://linux-hardware.org/?probe=3f26c37883) | Dec 04, 2023 |
| Samsung       | R530/R730                   | [3919c76efa](https://linux-hardware.org/?probe=3919c76efa) | Dec 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS3L502    | [592eb925fd](https://linux-hardware.org/?probe=592eb925fd) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [7afcab06a4](https://linux-hardware.org/?probe=7afcab06a4) | Dec 04, 2023 |
| Lenovo        | ThinkPad T460 20FMS5QV00    | [3b08be3ebc](https://linux-hardware.org/?probe=3b08be3ebc) | Dec 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [bbd413d34b](https://linux-hardware.org/?probe=bbd413d34b) | Dec 03, 2023 |
| ASUSTek       | GL703VM                     | [616bfbe220](https://linux-hardware.org/?probe=616bfbe220) | Dec 03, 2023 |
| HP            | Unknown                     | [ac64007236](https://linux-hardware.org/?probe=ac64007236) | Dec 03, 2023 |
| Apple         | MacBookPro10,1              | [198b467b8f](https://linux-hardware.org/?probe=198b467b8f) | Dec 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [e7c23bf6d5](https://linux-hardware.org/?probe=e7c23bf6d5) | Dec 03, 2023 |
| MSI           | PS63 Modern 8RC             | [76f07c96fd](https://linux-hardware.org/?probe=76f07c96fd) | Dec 03, 2023 |
| Apple         | MacBookPro10,1              | [948e2f229a](https://linux-hardware.org/?probe=948e2f229a) | Dec 03, 2023 |
| UNOWHY        | Y13G002S4EI                 | [4587cd55f9](https://linux-hardware.org/?probe=4587cd55f9) | Dec 03, 2023 |
| Lenovo        | ThinkPad T530 2429F37       | [7db847c98e](https://linux-hardware.org/?probe=7db847c98e) | Dec 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [fe6c19062f](https://linux-hardware.org/?probe=fe6c19062f) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6189dc268f](https://linux-hardware.org/?probe=6189dc268f) | Dec 02, 2023 |
| Apple         | MacBookPro5,5               | [53e38cd006](https://linux-hardware.org/?probe=53e38cd006) | Dec 02, 2023 |
| Dell          | Latitude E6510              | [0c49353fa5](https://linux-hardware.org/?probe=0c49353fa5) | Dec 02, 2023 |
| Samsung       | R610                        | [63c97d55c8](https://linux-hardware.org/?probe=63c97d55c8) | Dec 02, 2023 |
| Acer          | Aspire E5-771G              | [907744429e](https://linux-hardware.org/?probe=907744429e) | Dec 02, 2023 |
| HP            | Notebook                    | [4b88cdde01](https://linux-hardware.org/?probe=4b88cdde01) | Dec 02, 2023 |
| Clevo         | W251ESQ/W270ESQ             | [8572803f38](https://linux-hardware.org/?probe=8572803f38) | Dec 01, 2023 |
| Acer          | Aspire A317-51K             | [aa5652abe0](https://linux-hardware.org/?probe=aa5652abe0) | Dec 01, 2023 |
| Acer          | Swift SF314-511             | [ca692e6dcb](https://linux-hardware.org/?probe=ca692e6dcb) | Dec 01, 2023 |
| Toshiba       | Satellite C870-1F3          | [adb628ff38](https://linux-hardware.org/?probe=adb628ff38) | Dec 01, 2023 |
| Toshiba       | Satellite C870-1F3          | [93907ea0f4](https://linux-hardware.org/?probe=93907ea0f4) | Dec 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [fc30a356f0](https://linux-hardware.org/?probe=fc30a356f0) | Dec 01, 2023 |
| Notebook      | NJ50_70CU                   | [613d0fb4a0](https://linux-hardware.org/?probe=613d0fb4a0) | Dec 01, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [62ab001788](https://linux-hardware.org/?probe=62ab001788) | Dec 01, 2023 |
| HP            | ProBook 650 G1              | [a3bf52bd5d](https://linux-hardware.org/?probe=a3bf52bd5d) | Nov 30, 2023 |
| Qilive        | QW2214FR                    | [8daddd5057](https://linux-hardware.org/?probe=8daddd5057) | Nov 30, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [bd0ae5856a](https://linux-hardware.org/?probe=bd0ae5856a) | Nov 30, 2023 |
| Clevo         | C4100/C5100                 | [8e2637b70f](https://linux-hardware.org/?probe=8e2637b70f) | Nov 30, 2023 |
| Clevo         | C4100/C5100                 | [ea98614215](https://linux-hardware.org/?probe=ea98614215) | Nov 30, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [5a628a7b0f](https://linux-hardware.org/?probe=5a628a7b0f) | Nov 30, 2023 |
| HP            | ProBook 450 G1              | [7c7825a9c9](https://linux-hardware.org/?probe=7c7825a9c9) | Nov 30, 2023 |
| Dell          | XPS 9320                    | [e4ca1d9f5f](https://linux-hardware.org/?probe=e4ca1d9f5f) | Nov 30, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b682c56733](https://linux-hardware.org/?probe=b682c56733) | Nov 29, 2023 |
| Teclast       | F15S                        | [34392dd87e](https://linux-hardware.org/?probe=34392dd87e) | Nov 29, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [a5caeab77f](https://linux-hardware.org/?probe=a5caeab77f) | Nov 29, 2023 |
| ASUSTek       | GL703VM                     | [262f681abe](https://linux-hardware.org/?probe=262f681abe) | Nov 29, 2023 |
| Lenovo        | ThinkPad R500 27148UG       | [546c56f7bb](https://linux-hardware.org/?probe=546c56f7bb) | Nov 28, 2023 |
| MSI           | GF63 Thin 11UD              | [bde4e92728](https://linux-hardware.org/?probe=bde4e92728) | Nov 28, 2023 |
| HP            | EliteBook 860 16 inch G1... | [ebf45c9457](https://linux-hardware.org/?probe=ebf45c9457) | Nov 28, 2023 |
| MSI           | Prestige 14H B12UCX         | [d7c4903da6](https://linux-hardware.org/?probe=d7c4903da6) | Nov 28, 2023 |
| Lenovo        | Unknown                     | [0324aeaf06](https://linux-hardware.org/?probe=0324aeaf06) | Nov 28, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [413049d0f4](https://linux-hardware.org/?probe=413049d0f4) | Nov 28, 2023 |
| Acer          | Nitro AN515-58              | [2ddc688d1d](https://linux-hardware.org/?probe=2ddc688d1d) | Nov 28, 2023 |
| Sony          | VGN-NS12M_W                 | [c1400d8699](https://linux-hardware.org/?probe=c1400d8699) | Nov 27, 2023 |
| ASUSTek       | K73SD                       | [cd71879827](https://linux-hardware.org/?probe=cd71879827) | Nov 27, 2023 |
| MSI           | GE72VR 7RF                  | [8f1366b9a9](https://linux-hardware.org/?probe=8f1366b9a9) | Nov 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8739388aac](https://linux-hardware.org/?probe=8739388aac) | Nov 27, 2023 |
| Dell          | Latitude E7470              | [7b07507b58](https://linux-hardware.org/?probe=7b07507b58) | Nov 27, 2023 |
| HP            | Laptop 17-cp0xxx            | [63ddfa6f43](https://linux-hardware.org/?probe=63ddfa6f43) | Nov 27, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [0bc55c4101](https://linux-hardware.org/?probe=0bc55c4101) | Nov 27, 2023 |
| Toshiba       | Satellite S70t-A            | [a98f08b161](https://linux-hardware.org/?probe=a98f08b161) | Nov 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [06bf1b0f79](https://linux-hardware.org/?probe=06bf1b0f79) | Nov 27, 2023 |
| MSI           | Modern 15 A10M              | [105e84e282](https://linux-hardware.org/?probe=105e84e282) | Nov 26, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [21bc20e802](https://linux-hardware.org/?probe=21bc20e802) | Nov 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS07C01    | [c05294f5f5](https://linux-hardware.org/?probe=c05294f5f5) | Nov 26, 2023 |
| Apple         | MacBookPro11,1              | [9bb8e96cf9](https://linux-hardware.org/?probe=9bb8e96cf9) | Nov 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS07C01    | [dc051898f5](https://linux-hardware.org/?probe=dc051898f5) | Nov 26, 2023 |
| Apple         | MacBookPro8,1               | [1a31182007](https://linux-hardware.org/?probe=1a31182007) | Nov 26, 2023 |
| Packard Be... | DOT S                       | [c42837d646](https://linux-hardware.org/?probe=c42837d646) | Nov 26, 2023 |
| HUAWEI        | CREM-WXX9                   | [ab6a5cd935](https://linux-hardware.org/?probe=ab6a5cd935) | Nov 26, 2023 |
| HP            | Notebook                    | [671f5f59ac](https://linux-hardware.org/?probe=671f5f59ac) | Nov 26, 2023 |
| Dell          | Precision M4800             | [8712b3ecb9](https://linux-hardware.org/?probe=8712b3ecb9) | Nov 26, 2023 |
| Google        | Droid                       | [f0bc6c8af1](https://linux-hardware.org/?probe=f0bc6c8af1) | Nov 25, 2023 |
| MSI           | Prestige 14H B12UCX         | [6034c0b26d](https://linux-hardware.org/?probe=6034c0b26d) | Nov 25, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [3b163ea99b](https://linux-hardware.org/?probe=3b163ea99b) | Nov 25, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6007599bc5](https://linux-hardware.org/?probe=6007599bc5) | Nov 25, 2023 |
| ASUSTek       | GL753VD                     | [214c1cc15b](https://linux-hardware.org/?probe=214c1cc15b) | Nov 25, 2023 |
| HP            | EliteBook 860 16 inch G1... | [5d2574b6cf](https://linux-hardware.org/?probe=5d2574b6cf) | Nov 24, 2023 |
| Dell          | XPS 13 9305                 | [6a47a3a5de](https://linux-hardware.org/?probe=6a47a3a5de) | Nov 24, 2023 |
| Valve         | Jupiter                     | [cd4e80c195](https://linux-hardware.org/?probe=cd4e80c195) | Nov 24, 2023 |
| Valve         | Jupiter                     | [cb881f1c27](https://linux-hardware.org/?probe=cb881f1c27) | Nov 24, 2023 |
| Packard Be... | EasyNote ENLG71BM           | [25ae01fde2](https://linux-hardware.org/?probe=25ae01fde2) | Nov 24, 2023 |
| Dell          | Latitude E5550              | [96a4d03e8c](https://linux-hardware.org/?probe=96a4d03e8c) | Nov 23, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [04dd78f309](https://linux-hardware.org/?probe=04dd78f309) | Nov 23, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b450d3fe43](https://linux-hardware.org/?probe=b450d3fe43) | Nov 23, 2023 |
| Toshiba       | Satellite Pro L500          | [712435b9a5](https://linux-hardware.org/?probe=712435b9a5) | Nov 22, 2023 |
| Acer          | Aspire E1-570               | [8c6fd80245](https://linux-hardware.org/?probe=8c6fd80245) | Nov 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [4ade8c4182](https://linux-hardware.org/?probe=4ade8c4182) | Nov 22, 2023 |
| Fujitsu Si... | AMILO Pi 3625               | [e93688d366](https://linux-hardware.org/?probe=e93688d366) | Nov 22, 2023 |
| Toshiba       | Satellite C670D-11Z         | [354cabf09c](https://linux-hardware.org/?probe=354cabf09c) | Nov 22, 2023 |
| MSI           | Prestige 15 A11SCX          | [e443925a9c](https://linux-hardware.org/?probe=e443925a9c) | Nov 22, 2023 |
| HP            | Pavilion 15                 | [9ac4b59c55](https://linux-hardware.org/?probe=9ac4b59c55) | Nov 21, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [af6326319c](https://linux-hardware.org/?probe=af6326319c) | Nov 21, 2023 |
| Lenovo        | ThinkPad T550 20CJS02E00    | [00e8b77882](https://linux-hardware.org/?probe=00e8b77882) | Nov 21, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [8d5fa67be3](https://linux-hardware.org/?probe=8d5fa67be3) | Nov 21, 2023 |
| ASUSTek       | ROG Strix G713IM_G713IM     | [bacf466ce6](https://linux-hardware.org/?probe=bacf466ce6) | Nov 21, 2023 |
| ASUSTek       | N550JK                      | [e29a6a807e](https://linux-hardware.org/?probe=e29a6a807e) | Nov 21, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [1e58f5a4f9](https://linux-hardware.org/?probe=1e58f5a4f9) | Nov 21, 2023 |
| Valve         | Jupiter                     | [f36d771d28](https://linux-hardware.org/?probe=f36d771d28) | Nov 20, 2023 |
| HUAWEI        | HVY-WXX9                    | [6c2755ced9](https://linux-hardware.org/?probe=6c2755ced9) | Nov 20, 2023 |
| PC Special... | Lafite Pro II 15            | [b7b85ab8ce](https://linux-hardware.org/?probe=b7b85ab8ce) | Nov 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [bf2a6c9451](https://linux-hardware.org/?probe=bf2a6c9451) | Nov 20, 2023 |
| HP            | ProBook 650 G5              | [ea9539a6d2](https://linux-hardware.org/?probe=ea9539a6d2) | Nov 20, 2023 |
| Acer          | Aspire 7535                 | [8316560129](https://linux-hardware.org/?probe=8316560129) | Nov 20, 2023 |
| HP            | EliteBook 840 G1            | [f2462919d4](https://linux-hardware.org/?probe=f2462919d4) | Nov 19, 2023 |
| ASUSTek       | GL553VD                     | [eff083cd7e](https://linux-hardware.org/?probe=eff083cd7e) | Nov 19, 2023 |
| HP            | Pavilion dm4                | [6fb416e928](https://linux-hardware.org/?probe=6fb416e928) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [886c5bc9a6](https://linux-hardware.org/?probe=886c5bc9a6) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [bcd7007cde](https://linux-hardware.org/?probe=bcd7007cde) | Nov 19, 2023 |
| Notebook      | W54_55SU1,SUW               | [c11c5d127d](https://linux-hardware.org/?probe=c11c5d127d) | Nov 18, 2023 |
| Notebook      | W54_55SU1,SUW               | [12a0c7cc59](https://linux-hardware.org/?probe=12a0c7cc59) | Nov 18, 2023 |
| HP            | 250 G6 Notebook PC          | [b62a8b07f4](https://linux-hardware.org/?probe=b62a8b07f4) | Nov 18, 2023 |
| HP            | Compaq 6510b (GR680ET)      | [4d849ef131](https://linux-hardware.org/?probe=4d849ef131) | Nov 18, 2023 |
| Acer          | Aspire ES1-711              | [b7e85345bc](https://linux-hardware.org/?probe=b7e85345bc) | Nov 18, 2023 |
| Dell          | Latitude 7400               | [953d5c7200](https://linux-hardware.org/?probe=953d5c7200) | Nov 18, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [c3769c8a57](https://linux-hardware.org/?probe=c3769c8a57) | Nov 18, 2023 |
| LG Electro... | 16Z90R-G.AD75F              | [83d650792f](https://linux-hardware.org/?probe=83d650792f) | Nov 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [67b231cfe0](https://linux-hardware.org/?probe=67b231cfe0) | Nov 18, 2023 |
| Teclast       | F15Plus 2                   | [e263f987c0](https://linux-hardware.org/?probe=e263f987c0) | Nov 18, 2023 |
| ASUSTek       | X550JX                      | [d8e10147d2](https://linux-hardware.org/?probe=d8e10147d2) | Nov 18, 2023 |
| HP            | ProBook 430 G7              | [093edd002d](https://linux-hardware.org/?probe=093edd002d) | Nov 18, 2023 |
| Thomson       | N15C8BK2T                   | [e5a62b2035](https://linux-hardware.org/?probe=e5a62b2035) | Nov 18, 2023 |
| ASUSTek       | X540LJ                      | [fef63b579f](https://linux-hardware.org/?probe=fef63b579f) | Nov 17, 2023 |
| MSI           | GS65 Stealth 9SD            | [b0eba2e921](https://linux-hardware.org/?probe=b0eba2e921) | Nov 16, 2023 |
| MSI           | GS65 Stealth 9SD            | [0331447937](https://linux-hardware.org/?probe=0331447937) | Nov 16, 2023 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | [47427f60c0](https://linux-hardware.org/?probe=47427f60c0) | Nov 16, 2023 |
| Lenovo        | Yoga 2 13 20344             | [ebb7ed0d8c](https://linux-hardware.org/?probe=ebb7ed0d8c) | Nov 16, 2023 |
| HP            | ProBook 650 G5              | [5736b02f06](https://linux-hardware.org/?probe=5736b02f06) | Nov 16, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [e7e00bb090](https://linux-hardware.org/?probe=e7e00bb090) | Nov 16, 2023 |
| Apple         | MacBookAir3,1               | [e2eb5cacb7](https://linux-hardware.org/?probe=e2eb5cacb7) | Nov 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [adab9bb3b4](https://linux-hardware.org/?probe=adab9bb3b4) | Nov 15, 2023 |
| Acer          | Aspire ES1-572              | [9622b50e1e](https://linux-hardware.org/?probe=9622b50e1e) | Nov 15, 2023 |
| HP            | EliteBook 840 G6            | [d702c8d829](https://linux-hardware.org/?probe=d702c8d829) | Nov 15, 2023 |
| Google        | Kohaku                      | [ac5c19b11f](https://linux-hardware.org/?probe=ac5c19b11f) | Nov 15, 2023 |
| Dell          | Latitude 7310               | [8370505908](https://linux-hardware.org/?probe=8370505908) | Nov 15, 2023 |
| Lenovo        | IdeaPad S300 9803           | [21f7433934](https://linux-hardware.org/?probe=21f7433934) | Nov 15, 2023 |
| MSI           | GP72 6QF                    | [89f6458e06](https://linux-hardware.org/?probe=89f6458e06) | Nov 15, 2023 |
| ASUSTek       | GL753VD                     | [a05c294e1e](https://linux-hardware.org/?probe=a05c294e1e) | Nov 15, 2023 |
| Lenovo        | ThinkPad X280 20KES5840A    | [8800b951d8](https://linux-hardware.org/?probe=8800b951d8) | Nov 14, 2023 |
| MSI           | Prestige 15 A10SC           | [a9ff569501](https://linux-hardware.org/?probe=a9ff569501) | Nov 14, 2023 |
| Toshiba       | Satellite C870D-116         | [117931b0aa](https://linux-hardware.org/?probe=117931b0aa) | Nov 14, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [2521cc716f](https://linux-hardware.org/?probe=2521cc716f) | Nov 14, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [556cb2f633](https://linux-hardware.org/?probe=556cb2f633) | Nov 14, 2023 |
| Thomson       | N14C4WH64                   | [79fb5c8b87](https://linux-hardware.org/?probe=79fb5c8b87) | Nov 14, 2023 |
| Dell          | Latitude 5430               | [9aed6642da](https://linux-hardware.org/?probe=9aed6642da) | Nov 14, 2023 |
| Dell          | XPS 15 9520                 | [a8e7103aa2](https://linux-hardware.org/?probe=a8e7103aa2) | Nov 13, 2023 |
| Dell          | Latitude E5420              | [dc67f70b3b](https://linux-hardware.org/?probe=dc67f70b3b) | Nov 13, 2023 |
| Apple         | MacBookAir4,2               | [aefe53a7b6](https://linux-hardware.org/?probe=aefe53a7b6) | Nov 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6d1d512f69](https://linux-hardware.org/?probe=6d1d512f69) | Nov 12, 2023 |
| HP            | Laptop 15-db0xxx            | [44aa818077](https://linux-hardware.org/?probe=44aa818077) | Nov 12, 2023 |
| Notebook      | NJ50_70CU                   | [ed00b585a3](https://linux-hardware.org/?probe=ed00b585a3) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 42369N1       | [632121ae02](https://linux-hardware.org/?probe=632121ae02) | Nov 12, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | [a7bd543bb7](https://linux-hardware.org/?probe=a7bd543bb7) | Nov 12, 2023 |
| Toshiba       | Satellite C70-B             | [a9534bcb6d](https://linux-hardware.org/?probe=a9534bcb6d) | Nov 12, 2023 |
| Toshiba       | Satellite C650D             | [a49e05d0b8](https://linux-hardware.org/?probe=a49e05d0b8) | Nov 11, 2023 |
| HP            | Stream Notebook             | [2434e6cef4](https://linux-hardware.org/?probe=2434e6cef4) | Nov 11, 2023 |
| Acer          | Aspire 5715Z                | [532b575898](https://linux-hardware.org/?probe=532b575898) | Nov 11, 2023 |
| Fujitsu       | LIFEBOOK E780               | [86e17547d2](https://linux-hardware.org/?probe=86e17547d2) | Nov 11, 2023 |
| ASUSTek       | X580VD                      | [81b80194be](https://linux-hardware.org/?probe=81b80194be) | Nov 10, 2023 |
| ASUSTek       | X580VD                      | [5dcc6790c2](https://linux-hardware.org/?probe=5dcc6790c2) | Nov 10, 2023 |
| HP            | ProBook 650 G5              | [3442cd2670](https://linux-hardware.org/?probe=3442cd2670) | Nov 10, 2023 |
| Samsung       | R425D/R525D                 | [566985b28a](https://linux-hardware.org/?probe=566985b28a) | Nov 10, 2023 |
| HP            | EliteBook 840 G6            | [33e3267f6a](https://linux-hardware.org/?probe=33e3267f6a) | Nov 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3f1d1d36ef](https://linux-hardware.org/?probe=3f1d1d36ef) | Nov 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [1284e15df1](https://linux-hardware.org/?probe=1284e15df1) | Nov 10, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [ebbeac415f](https://linux-hardware.org/?probe=ebbeac415f) | Nov 10, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [9b881d355c](https://linux-hardware.org/?probe=9b881d355c) | Nov 09, 2023 |
| ASUSTek       | K95VM                       | [a58011f5bc](https://linux-hardware.org/?probe=a58011f5bc) | Nov 09, 2023 |
| Lenovo        | G50-45 80E3                 | [51f7d5e2dc](https://linux-hardware.org/?probe=51f7d5e2dc) | Nov 09, 2023 |
| Dell          | Latitude 5590               | [5712f37060](https://linux-hardware.org/?probe=5712f37060) | Nov 09, 2023 |
| Lenovo        | G50-45 80E3                 | [0a23b4526a](https://linux-hardware.org/?probe=0a23b4526a) | Nov 09, 2023 |
| ASUSTek       | ROG Strix G713IM_G713IM     | [95d3d270b2](https://linux-hardware.org/?probe=95d3d270b2) | Nov 09, 2023 |
| Notebook      | NJ50_70CU                   | [7ffd65d532](https://linux-hardware.org/?probe=7ffd65d532) | Nov 09, 2023 |
| Dell          | Latitude 7280               | [a91cab2bb9](https://linux-hardware.org/?probe=a91cab2bb9) | Nov 08, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [5cf379008d](https://linux-hardware.org/?probe=5cf379008d) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [58e4e6690a](https://linux-hardware.org/?probe=58e4e6690a) | Nov 08, 2023 |
| Notebook      | NJ50_70CU                   | [f48a185656](https://linux-hardware.org/?probe=f48a185656) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [52b0129f48](https://linux-hardware.org/?probe=52b0129f48) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [b05a5bff97](https://linux-hardware.org/?probe=b05a5bff97) | Nov 08, 2023 |
| Dell          | Latitude 7280               | [22957cd62d](https://linux-hardware.org/?probe=22957cd62d) | Nov 08, 2023 |
| Dell          | Latitude 5430               | [e7df6855a7](https://linux-hardware.org/?probe=e7df6855a7) | Nov 08, 2023 |
| MSI           | Creator M16 B12VE           | [fec840c7fd](https://linux-hardware.org/?probe=fec840c7fd) | Nov 08, 2023 |
| HP            | Compaq 6830s                | [069a45be37](https://linux-hardware.org/?probe=069a45be37) | Nov 08, 2023 |
| Dell          | Inspiron 7720               | [beed298cdb](https://linux-hardware.org/?probe=beed298cdb) | Nov 07, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c28217d1ed](https://linux-hardware.org/?probe=c28217d1ed) | Nov 07, 2023 |
| Lenovo        | ThinkPad X240 20AMS7X300    | [e87e6bdcfc](https://linux-hardware.org/?probe=e87e6bdcfc) | Nov 07, 2023 |
| Lenovo        | ThinkPad X230 23259T0       | [bc52f6064a](https://linux-hardware.org/?probe=bc52f6064a) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | [c2434cadfc](https://linux-hardware.org/?probe=c2434cadfc) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | [a5628b0f9d](https://linux-hardware.org/?probe=a5628b0f9d) | Nov 07, 2023 |
| Toshiba       | Satellite L550              | [530b650093](https://linux-hardware.org/?probe=530b650093) | Nov 07, 2023 |
| Apple         | MacBookPro8,1               | [e8e313e8e9](https://linux-hardware.org/?probe=e8e313e8e9) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [996538af0c](https://linux-hardware.org/?probe=996538af0c) | Nov 07, 2023 |
| ASUSTek       | X55A                        | [705bc0e6a5](https://linux-hardware.org/?probe=705bc0e6a5) | Nov 07, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d33b9781b7](https://linux-hardware.org/?probe=d33b9781b7) | Nov 06, 2023 |
| Lenovo        | ThinkPad T420 4236NHG       | [6db239877b](https://linux-hardware.org/?probe=6db239877b) | Nov 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [94847646c8](https://linux-hardware.org/?probe=94847646c8) | Nov 06, 2023 |
| ASUSTek       | X751MA                      | [d5e1758d4e](https://linux-hardware.org/?probe=d5e1758d4e) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [5d63a1487d](https://linux-hardware.org/?probe=5d63a1487d) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [0facd311dc](https://linux-hardware.org/?probe=0facd311dc) | Nov 05, 2023 |
| Dell          | Latitude 7280               | [3f1419b0ea](https://linux-hardware.org/?probe=3f1419b0ea) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | [27740d5118](https://linux-hardware.org/?probe=27740d5118) | Nov 05, 2023 |
| MSI           | Bravo 15 B5DD               | [72b02cceec](https://linux-hardware.org/?probe=72b02cceec) | Nov 05, 2023 |
| MSI           | Bravo 15 B5DD               | [8a35411be4](https://linux-hardware.org/?probe=8a35411be4) | Nov 05, 2023 |
| Lenovo        | G50-45 80E3                 | [2ac9878b30](https://linux-hardware.org/?probe=2ac9878b30) | Nov 05, 2023 |
| ASUSTek       | G75VW                       | [94bc809d57](https://linux-hardware.org/?probe=94bc809d57) | Nov 05, 2023 |
| ASUSTek       | K55VJ                       | [47851a05e9](https://linux-hardware.org/?probe=47851a05e9) | Nov 05, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [257e40f6bd](https://linux-hardware.org/?probe=257e40f6bd) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [c235d90592](https://linux-hardware.org/?probe=c235d90592) | Nov 05, 2023 |
| HP            | Pavilion dv7                | [6a44cc2c3c](https://linux-hardware.org/?probe=6a44cc2c3c) | Nov 04, 2023 |
| ASUSTek       | X550LC                      | [bd59b07dbf](https://linux-hardware.org/?probe=bd59b07dbf) | Nov 04, 2023 |
| ASUSTek       | X550LC                      | [b7fa2bbb0b](https://linux-hardware.org/?probe=b7fa2bbb0b) | Nov 04, 2023 |
| Apple         | MacBook5,2                  | [1d8dad6600](https://linux-hardware.org/?probe=1d8dad6600) | Nov 04, 2023 |
| Unknown       | Unknown                     | [662c88776a](https://linux-hardware.org/?probe=662c88776a) | Nov 04, 2023 |
| Dell          | Latitude E5450              | [1f23c5fd7c](https://linux-hardware.org/?probe=1f23c5fd7c) | Nov 04, 2023 |
| ASUSTek       | UX32VD                      | [7c4eefbe35](https://linux-hardware.org/?probe=7c4eefbe35) | Nov 04, 2023 |
| HP            | OMEN by Laptop 17-ck2xxx    | [e34a0ab109](https://linux-hardware.org/?probe=e34a0ab109) | Nov 03, 2023 |
| Thomson       | N14C4WH64                   | [51c94bc00f](https://linux-hardware.org/?probe=51c94bc00f) | Nov 03, 2023 |
| Lenovo        | G50-45 80E3                 | [a816b34b9e](https://linux-hardware.org/?probe=a816b34b9e) | Nov 03, 2023 |
| HUAWEI        | HLYL-WXX9                   | [993a2b9f3e](https://linux-hardware.org/?probe=993a2b9f3e) | Nov 03, 2023 |
| Timi          | A35                         | [1baa5932cc](https://linux-hardware.org/?probe=1baa5932cc) | Nov 03, 2023 |
| Dell          | Latitude 7280               | [b795f0157b](https://linux-hardware.org/?probe=b795f0157b) | Nov 03, 2023 |
| Star Labs     | StarBook                    | [288fdf6f55](https://linux-hardware.org/?probe=288fdf6f55) | Nov 02, 2023 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [3030ad2bc8](https://linux-hardware.org/?probe=3030ad2bc8) | Nov 02, 2023 |
| Acer          | Predator PH717-71           | [a72ab29450](https://linux-hardware.org/?probe=a72ab29450) | Nov 02, 2023 |
| ASUSTek       | T100TAF                     | [ea9f809740](https://linux-hardware.org/?probe=ea9f809740) | Nov 02, 2023 |
| Dell          | Inspiron 1750               | [0250d0fe82](https://linux-hardware.org/?probe=0250d0fe82) | Nov 02, 2023 |
| Dell          | Inspiron 1750               | [39bb893e18](https://linux-hardware.org/?probe=39bb893e18) | Nov 02, 2023 |
| Dell          | Latitude E6530              | [878bc8ec66](https://linux-hardware.org/?probe=878bc8ec66) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X411... | [8ac5fd2789](https://linux-hardware.org/?probe=8ac5fd2789) | Nov 02, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4372a2d9eb](https://linux-hardware.org/?probe=4372a2d9eb) | Nov 02, 2023 |
| HP            | Notebook                    | [3e766ed947](https://linux-hardware.org/?probe=3e766ed947) | Nov 01, 2023 |
| HP            | Notebook                    | [47c0e83dcc](https://linux-hardware.org/?probe=47c0e83dcc) | Nov 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [ac563e5542](https://linux-hardware.org/?probe=ac563e5542) | Nov 01, 2023 |
| Apple         | MacBookPro11,5              | [99e5155c24](https://linux-hardware.org/?probe=99e5155c24) | Nov 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [6afebfd732](https://linux-hardware.org/?probe=6afebfd732) | Nov 01, 2023 |
| Dell          | Latitude E7450              | [5e39e2bc88](https://linux-hardware.org/?probe=5e39e2bc88) | Nov 01, 2023 |
| ASUSTek       | G53JW                       | [fcc18f3b68](https://linux-hardware.org/?probe=fcc18f3b68) | Nov 01, 2023 |
| Dell          | Precision 5550              | [87a9861125](https://linux-hardware.org/?probe=87a9861125) | Nov 01, 2023 |
| Teclast       | F6 Pro                      | [27dd740e4c](https://linux-hardware.org/?probe=27dd740e4c) | Nov 01, 2023 |
| HP            | EliteBook 840 G3            | [a09d649781](https://linux-hardware.org/?probe=a09d649781) | Nov 01, 2023 |
| ASUSTek       | UX430UA                     | [d99926d970](https://linux-hardware.org/?probe=d99926d970) | Nov 01, 2023 |
| Lenovo        | IdeaPad S300 9803           | [543dfc0b4e](https://linux-hardware.org/?probe=543dfc0b4e) | Oct 31, 2023 |
| HP            | Notebook                    | [b1491b73ae](https://linux-hardware.org/?probe=b1491b73ae) | Oct 31, 2023 |
| ASUSTek       | G53JW                       | [6795430efa](https://linux-hardware.org/?probe=6795430efa) | Oct 31, 2023 |
| Dell          | G15 5510                    | [12bd3f99da](https://linux-hardware.org/?probe=12bd3f99da) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [97ae72d7b7](https://linux-hardware.org/?probe=97ae72d7b7) | Oct 31, 2023 |
| Dell          | XPS 15 9530                 | [148857cc51](https://linux-hardware.org/?probe=148857cc51) | Oct 31, 2023 |
| HP            | Laptop 15-db0xxx            | [cf7f0c142e](https://linux-hardware.org/?probe=cf7f0c142e) | Oct 31, 2023 |
| HP            | Victus by Gaming Laptop ... | [0f4fa9169b](https://linux-hardware.org/?probe=0f4fa9169b) | Oct 31, 2023 |
| OFF GLOBAL    | Nokia PureBook Pro 17       | [5bc799ab5a](https://linux-hardware.org/?probe=5bc799ab5a) | Oct 30, 2023 |
| Acer          | Aspire E5-576G              | [c0626d553b](https://linux-hardware.org/?probe=c0626d553b) | Oct 30, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [56f24de5ff](https://linux-hardware.org/?probe=56f24de5ff) | Oct 30, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [0e7bb14862](https://linux-hardware.org/?probe=0e7bb14862) | Oct 30, 2023 |
| HP            | ProBook 640 G1              | [cf78ef09d2](https://linux-hardware.org/?probe=cf78ef09d2) | Oct 30, 2023 |
| Dell          | Precision 3551              | [4f054a63ef](https://linux-hardware.org/?probe=4f054a63ef) | Oct 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | [5da6238372](https://linux-hardware.org/?probe=5da6238372) | Oct 30, 2023 |
| Acer          | Aspire A315-21              | [48785f697c](https://linux-hardware.org/?probe=48785f697c) | Oct 29, 2023 |
| Sony          | VPCEH1L0E                   | [2a5fa0340e](https://linux-hardware.org/?probe=2a5fa0340e) | Oct 29, 2023 |
| Sony          | VPCEH1L0E                   | [103e485a0f](https://linux-hardware.org/?probe=103e485a0f) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [7301c9b3df](https://linux-hardware.org/?probe=7301c9b3df) | Oct 29, 2023 |
| Notebook      | NS5x_NS7xAU                 | [151d6e2c69](https://linux-hardware.org/?probe=151d6e2c69) | Oct 29, 2023 |
| Dell          | Precision 3550              | [f07af59705](https://linux-hardware.org/?probe=f07af59705) | Oct 29, 2023 |
| HP            | Pavilion 17                 | [2ef396fb9c](https://linux-hardware.org/?probe=2ef396fb9c) | Oct 29, 2023 |
| Dell          | Precision 5480              | [5df408828c](https://linux-hardware.org/?probe=5df408828c) | Oct 29, 2023 |
| Acer          | Aspire ES1-572              | [12b1df4e2b](https://linux-hardware.org/?probe=12b1df4e2b) | Oct 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [1ad2b79950](https://linux-hardware.org/?probe=1ad2b79950) | Oct 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [ab6e0c5094](https://linux-hardware.org/?probe=ab6e0c5094) | Oct 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [67a82dac1b](https://linux-hardware.org/?probe=67a82dac1b) | Oct 28, 2023 |
| MSI           | Modern 15 A5M               | [903418110a](https://linux-hardware.org/?probe=903418110a) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d8bfe77d00](https://linux-hardware.org/?probe=d8bfe77d00) | Oct 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [334f8582b0](https://linux-hardware.org/?probe=334f8582b0) | Oct 27, 2023 |
| Dell          | Inspiron MM061              | [d4b3f62ecb](https://linux-hardware.org/?probe=d4b3f62ecb) | Oct 27, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [a899ecd171](https://linux-hardware.org/?probe=a899ecd171) | Oct 27, 2023 |
| MSI           | GL73 8RD                    | [62d3ea64dd](https://linux-hardware.org/?probe=62d3ea64dd) | Oct 27, 2023 |
| Dell          | XPS 15 9530                 | [dbc8a87975](https://linux-hardware.org/?probe=dbc8a87975) | Oct 27, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [3a2901251b](https://linux-hardware.org/?probe=3a2901251b) | Oct 27, 2023 |
| HP            | Laptop 17-cp2xxx            | [788d8538b6](https://linux-hardware.org/?probe=788d8538b6) | Oct 27, 2023 |
| Dell          | Latitude E5470              | [fbbcdd8d9f](https://linux-hardware.org/?probe=fbbcdd8d9f) | Oct 26, 2023 |
| HP            | ProBook 4530s               | [b86df6ad72](https://linux-hardware.org/?probe=b86df6ad72) | Oct 26, 2023 |
| HP            | G61                         | [d184a33522](https://linux-hardware.org/?probe=d184a33522) | Oct 26, 2023 |
| MSI           | Stealth 16Studio A13VG      | [2009a0a84b](https://linux-hardware.org/?probe=2009a0a84b) | Oct 26, 2023 |
| Valve         | Jupiter                     | [eda569093f](https://linux-hardware.org/?probe=eda569093f) | Oct 25, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [c66ebc8e70](https://linux-hardware.org/?probe=c66ebc8e70) | Oct 25, 2023 |
| Acer          | Aspire VN7-572G             | [979741d1d0](https://linux-hardware.org/?probe=979741d1d0) | Oct 25, 2023 |
| Dell          | Latitude E5470              | [cac52e6eaf](https://linux-hardware.org/?probe=cac52e6eaf) | Oct 25, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD000... | [4e393023d7](https://linux-hardware.org/?probe=4e393023d7) | Oct 25, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [3ce0f8310d](https://linux-hardware.org/?probe=3ce0f8310d) | Oct 25, 2023 |
| HP            | Pavilion dv7                | [6c8a64fc73](https://linux-hardware.org/?probe=6c8a64fc73) | Oct 24, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [05a3492143](https://linux-hardware.org/?probe=05a3492143) | Oct 24, 2023 |
| ASUSTek       | UX303LB                     | [1fdfa51ddc](https://linux-hardware.org/?probe=1fdfa51ddc) | Oct 24, 2023 |
| ASUSTek       | G551JX                      | [db16c87fe8](https://linux-hardware.org/?probe=db16c87fe8) | Oct 24, 2023 |
| MSI           | GT62VR 6RD                  | [0d10c5251c](https://linux-hardware.org/?probe=0d10c5251c) | Oct 23, 2023 |
| HP            | ProBook 450 G6              | [5dc90618a7](https://linux-hardware.org/?probe=5dc90618a7) | Oct 23, 2023 |
| Fujitsu       | LIFEBOOK E754               | [17e7fcc400](https://linux-hardware.org/?probe=17e7fcc400) | Oct 23, 2023 |
| Google        | Bobba                       | [3a660aaaef](https://linux-hardware.org/?probe=3a660aaaef) | Oct 23, 2023 |
| UNOWHY        | Y13G012S4EI                 | [37680f1ed6](https://linux-hardware.org/?probe=37680f1ed6) | Oct 22, 2023 |
| Toshiba       | Satellite C70D-B            | [7f1637fdb9](https://linux-hardware.org/?probe=7f1637fdb9) | Oct 22, 2023 |
| Dell          | Precision 3571              | [a2ba806246](https://linux-hardware.org/?probe=a2ba806246) | Oct 22, 2023 |
| Dell          | Precision 3571              | [efedaee27d](https://linux-hardware.org/?probe=efedaee27d) | Oct 22, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [96e2577624](https://linux-hardware.org/?probe=96e2577624) | Oct 22, 2023 |
| Acer          | Aspire V3-111P              | [3c17975c8c](https://linux-hardware.org/?probe=3c17975c8c) | Oct 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [b7b860ac67](https://linux-hardware.org/?probe=b7b860ac67) | Oct 22, 2023 |
| Acer          | Aspire ES1-572              | [b4e1647054](https://linux-hardware.org/?probe=b4e1647054) | Oct 21, 2023 |
| Thomson       | X15I5-8TU512                | [68099cb005](https://linux-hardware.org/?probe=68099cb005) | Oct 21, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [eb4d59cc70](https://linux-hardware.org/?probe=eb4d59cc70) | Oct 21, 2023 |
| HP            | Pavilion dm1                | [74c8fce8f0](https://linux-hardware.org/?probe=74c8fce8f0) | Oct 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [314c39b6d1](https://linux-hardware.org/?probe=314c39b6d1) | Oct 21, 2023 |
| ASUSTek       | GL553VD                     | [87210c3d86](https://linux-hardware.org/?probe=87210c3d86) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [130d199934](https://linux-hardware.org/?probe=130d199934) | Oct 21, 2023 |
| Dell          | Latitude 7440               | [e0997ac78c](https://linux-hardware.org/?probe=e0997ac78c) | Oct 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [148be53a91](https://linux-hardware.org/?probe=148be53a91) | Oct 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d9a8c7946e](https://linux-hardware.org/?probe=d9a8c7946e) | Oct 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [5cac857cd9](https://linux-hardware.org/?probe=5cac857cd9) | Oct 20, 2023 |
| Toshiba       | Satellite C660              | [483998d7de](https://linux-hardware.org/?probe=483998d7de) | Oct 20, 2023 |
| ASUSTek       | X540LJ                      | [2aea2077db](https://linux-hardware.org/?probe=2aea2077db) | Oct 20, 2023 |
| Toshiba       | Satellite C70D-B            | [793d71f1d2](https://linux-hardware.org/?probe=793d71f1d2) | Oct 20, 2023 |
| HP            | Compaq 15                   | [992044ca80](https://linux-hardware.org/?probe=992044ca80) | Oct 20, 2023 |
| Dell          | Latitude E6430s             | [ce1c3a6c86](https://linux-hardware.org/?probe=ce1c3a6c86) | Oct 20, 2023 |
| Acer          | Aspire S3                   | [612caa1082](https://linux-hardware.org/?probe=612caa1082) | Oct 20, 2023 |
| Lenovo        | ThinkPad L540 20AUA044FR    | [70d42f0667](https://linux-hardware.org/?probe=70d42f0667) | Oct 20, 2023 |
| Lenovo        | G50-45 80E3                 | [41f9f44ee1](https://linux-hardware.org/?probe=41f9f44ee1) | Oct 20, 2023 |
| Lenovo        | G50-45 80E3                 | [98f1b28357](https://linux-hardware.org/?probe=98f1b28357) | Oct 20, 2023 |
| HP            | Pavilion 17                 | [855c6109eb](https://linux-hardware.org/?probe=855c6109eb) | Oct 20, 2023 |
| HP            | Pavilion 17                 | [36613b2f1f](https://linux-hardware.org/?probe=36613b2f1f) | Oct 19, 2023 |
| Dell          | XPS 15 9520                 | [dd0f8dcb86](https://linux-hardware.org/?probe=dd0f8dcb86) | Oct 19, 2023 |
| ASUSTek       | X542UR                      | [72390695fd](https://linux-hardware.org/?probe=72390695fd) | Oct 19, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [2e7d97492d](https://linux-hardware.org/?probe=2e7d97492d) | Oct 19, 2023 |
| ASUSTek       | N501JW                      | [a61bad1bae](https://linux-hardware.org/?probe=a61bad1bae) | Oct 19, 2023 |
| ASUSTek       | X540LJ                      | [a0c126c4ce](https://linux-hardware.org/?probe=a0c126c4ce) | Oct 19, 2023 |
| UNOWHY        | Y13G012S4EI                 | [70032c78d7](https://linux-hardware.org/?probe=70032c78d7) | Oct 18, 2023 |
| Apple         | MacBookPro9,2               | [d9d804297d](https://linux-hardware.org/?probe=d9d804297d) | Oct 18, 2023 |
| HP            | EliteBook 840 G3            | [726f0ecc0b](https://linux-hardware.org/?probe=726f0ecc0b) | Oct 18, 2023 |
| Apple         | MacBookPro9,2               | [90413e0c45](https://linux-hardware.org/?probe=90413e0c45) | Oct 18, 2023 |
| Dell          | Latitude E6320              | [91e5128fd5](https://linux-hardware.org/?probe=91e5128fd5) | Oct 18, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [ebf8cac9b8](https://linux-hardware.org/?probe=ebf8cac9b8) | Oct 18, 2023 |
| HP            | EliteBook 860 16 inch G1... | [bde071302f](https://linux-hardware.org/?probe=bde071302f) | Oct 18, 2023 |
| HP            | EliteBook 850 G3            | [58831524ae](https://linux-hardware.org/?probe=58831524ae) | Oct 18, 2023 |
| MSI           | CX61 2PC                    | [67442a53f9](https://linux-hardware.org/?probe=67442a53f9) | Oct 18, 2023 |
| HP            | ProBook 450 G6              | [b3c36f8233](https://linux-hardware.org/?probe=b3c36f8233) | Oct 17, 2023 |
| ASUSTek       | K55VJ                       | [f5cfc1c08e](https://linux-hardware.org/?probe=f5cfc1c08e) | Oct 17, 2023 |
| ASUSTek       | EP121                       | [9c01d196e1](https://linux-hardware.org/?probe=9c01d196e1) | Oct 17, 2023 |
| Google        | Bobba                       | [f8cdd51f65](https://linux-hardware.org/?probe=f8cdd51f65) | Oct 17, 2023 |
| HP            | Pavilion Notebook           | [5981bba0dd](https://linux-hardware.org/?probe=5981bba0dd) | Oct 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d63ed71e40](https://linux-hardware.org/?probe=d63ed71e40) | Oct 17, 2023 |
| Acer          | Aspire A314-23P             | [99490448ae](https://linux-hardware.org/?probe=99490448ae) | Oct 16, 2023 |
| Acer          | Aspire A314-23P             | [431b672bf5](https://linux-hardware.org/?probe=431b672bf5) | Oct 16, 2023 |
| Acer          | Aspire ES1-523              | [6f80d0517c](https://linux-hardware.org/?probe=6f80d0517c) | Oct 16, 2023 |
| Apple         | MacBookPro16,1              | [6417009f82](https://linux-hardware.org/?probe=6417009f82) | Oct 16, 2023 |
| Lenovo        | ThinkPad R61 8935AC7        | [fc4f024a54](https://linux-hardware.org/?probe=fc4f024a54) | Oct 16, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [9aaa4cdee5](https://linux-hardware.org/?probe=9aaa4cdee5) | Oct 16, 2023 |
| HP            | ProBook 4730s               | [42a7295a49](https://linux-hardware.org/?probe=42a7295a49) | Oct 15, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [0d80ec0e27](https://linux-hardware.org/?probe=0d80ec0e27) | Oct 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6e4a6a34cd](https://linux-hardware.org/?probe=6e4a6a34cd) | Oct 15, 2023 |
| Lenovo        | ThinkPad X240 20AMS7X300    | [0cc0243579](https://linux-hardware.org/?probe=0cc0243579) | Oct 15, 2023 |
| Lenovo        | ThinkPad X230 23259T0       | [a9d4c1b781](https://linux-hardware.org/?probe=a9d4c1b781) | Oct 15, 2023 |
| Acer          | Aspire ES1-523              | [2dfea2666c](https://linux-hardware.org/?probe=2dfea2666c) | Oct 15, 2023 |
| Acer          | Aspire A317-51K             | [b342c56fc5](https://linux-hardware.org/?probe=b342c56fc5) | Oct 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [85e073cb44](https://linux-hardware.org/?probe=85e073cb44) | Oct 15, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | [d1eebbe97a](https://linux-hardware.org/?probe=d1eebbe97a) | Oct 14, 2023 |
| UNOWHY        | Y13G011S4EI                 | [15ee1d73bb](https://linux-hardware.org/?probe=15ee1d73bb) | Oct 14, 2023 |
| UNOWHY        | Y13G011S4EI                 | [ea84658524](https://linux-hardware.org/?probe=ea84658524) | Oct 14, 2023 |
| Clevo         | W150ER                      | [e119814a32](https://linux-hardware.org/?probe=e119814a32) | Oct 14, 2023 |
| Dell          | Latitude 5400               | [26c8a94f7f](https://linux-hardware.org/?probe=26c8a94f7f) | Oct 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [98ebe6766d](https://linux-hardware.org/?probe=98ebe6766d) | Oct 14, 2023 |
| Notebook      | NJ50_70CU                   | [885120121b](https://linux-hardware.org/?probe=885120121b) | Oct 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7ee4351584](https://linux-hardware.org/?probe=7ee4351584) | Oct 13, 2023 |
| HUAWEI        | BOM-WXX9                    | [7310efb29d](https://linux-hardware.org/?probe=7310efb29d) | Oct 13, 2023 |
| Thomson       | NEO14-4W64                  | [f68e52a8a1](https://linux-hardware.org/?probe=f68e52a8a1) | Oct 12, 2023 |
| Lenovo        | V145-15AST 81MT             | [47c6aaf7b8](https://linux-hardware.org/?probe=47c6aaf7b8) | Oct 12, 2023 |
| Dell          | XPS 13 9360                 | [d227c42e18](https://linux-hardware.org/?probe=d227c42e18) | Oct 12, 2023 |
| MSI           | GF63 8RC                    | [6fcc7aa3b0](https://linux-hardware.org/?probe=6fcc7aa3b0) | Oct 12, 2023 |
| HP            | EliteBook 840 G6 HC         | [e1b3f5dbeb](https://linux-hardware.org/?probe=e1b3f5dbeb) | Oct 11, 2023 |
| Dell          | Latitude E7470              | [7bf3b8f1ae](https://linux-hardware.org/?probe=7bf3b8f1ae) | Oct 11, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [be6e7011cc](https://linux-hardware.org/?probe=be6e7011cc) | Oct 11, 2023 |
| Notebook      | W510LU                      | [7b46aa1486](https://linux-hardware.org/?probe=7b46aa1486) | Oct 11, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [cca48ceee9](https://linux-hardware.org/?probe=cca48ceee9) | Oct 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [ea3f6440b2](https://linux-hardware.org/?probe=ea3f6440b2) | Oct 11, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [4f5f1c9eea](https://linux-hardware.org/?probe=4f5f1c9eea) | Oct 11, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [22df79ec5d](https://linux-hardware.org/?probe=22df79ec5d) | Oct 11, 2023 |
| Acer          | Aspire A315-24P             | [30640ecf17](https://linux-hardware.org/?probe=30640ecf17) | Oct 10, 2023 |
| Clevo         | W240HU/W250HUQ              | [deb84129fb](https://linux-hardware.org/?probe=deb84129fb) | Oct 10, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [62325b0861](https://linux-hardware.org/?probe=62325b0861) | Oct 10, 2023 |
| ASUSTek       | G750JM                      | [62af3377c2](https://linux-hardware.org/?probe=62af3377c2) | Oct 10, 2023 |
| EUROCOM       | RAPTOR X17                  | [468a885ee9](https://linux-hardware.org/?probe=468a885ee9) | Oct 10, 2023 |
| Dell          | Precision 5570              | [3b9cb31d2f](https://linux-hardware.org/?probe=3b9cb31d2f) | Oct 10, 2023 |
| Dell          | XPS 15 9550                 | [a5ef1797e7](https://linux-hardware.org/?probe=a5ef1797e7) | Oct 09, 2023 |
| Dell          | XPS 9320                    | [1cd3d3eb22](https://linux-hardware.org/?probe=1cd3d3eb22) | Oct 09, 2023 |
| Toshiba       | Satellite C660D             | [1106658f2c](https://linux-hardware.org/?probe=1106658f2c) | Oct 09, 2023 |
| Extra Terr... | Unknown                     | [505b2e0823](https://linux-hardware.org/?probe=505b2e0823) | Oct 08, 2023 |
| Dell          | Latitude E5440              | [a039ff25ef](https://linux-hardware.org/?probe=a039ff25ef) | Oct 08, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [91f26dd2c7](https://linux-hardware.org/?probe=91f26dd2c7) | Oct 08, 2023 |
| MSI           | GT73EVR 7RE                 | [b68e25b341](https://linux-hardware.org/?probe=b68e25b341) | Oct 08, 2023 |
| Dell          | Latitude E7440              | [40ffa6c211](https://linux-hardware.org/?probe=40ffa6c211) | Oct 08, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [a830045a2a](https://linux-hardware.org/?probe=a830045a2a) | Oct 07, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [93faa713c7](https://linux-hardware.org/?probe=93faa713c7) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | [cae6954f11](https://linux-hardware.org/?probe=cae6954f11) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | [ca68af85fb](https://linux-hardware.org/?probe=ca68af85fb) | Oct 07, 2023 |
| EUROCOM       | RAPTOR X17                  | [b720194674](https://linux-hardware.org/?probe=b720194674) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | [f4c0266602](https://linux-hardware.org/?probe=f4c0266602) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | [8978850a77](https://linux-hardware.org/?probe=8978850a77) | Oct 06, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [75690ff16c](https://linux-hardware.org/?probe=75690ff16c) | Oct 06, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [642e50dbfd](https://linux-hardware.org/?probe=642e50dbfd) | Oct 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7add8932c3](https://linux-hardware.org/?probe=7add8932c3) | Oct 06, 2023 |
| Dell          | Precision 5480              | [3a87c7a065](https://linux-hardware.org/?probe=3a87c7a065) | Oct 05, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [bfe115219f](https://linux-hardware.org/?probe=bfe115219f) | Oct 05, 2023 |
| Acer          | Aspire A317-53              | [523e4c1ed6](https://linux-hardware.org/?probe=523e4c1ed6) | Oct 05, 2023 |
| Dell          | Latitude 7490               | [fd6fe204ae](https://linux-hardware.org/?probe=fd6fe204ae) | Oct 05, 2023 |
| Fujitsu Si... | AMILO Li 2727               | [a95e5535f4](https://linux-hardware.org/?probe=a95e5535f4) | Oct 05, 2023 |
| Dell          | Latitude 3420               | [c5a2d75e6c](https://linux-hardware.org/?probe=c5a2d75e6c) | Oct 05, 2023 |
| Fujitsu Si... | AMILO Li 2727               | [fd0dc36129](https://linux-hardware.org/?probe=fd0dc36129) | Oct 05, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [763ef47e79](https://linux-hardware.org/?probe=763ef47e79) | Oct 05, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | [dfb6b7140d](https://linux-hardware.org/?probe=dfb6b7140d) | Oct 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [2a4f34aeb4](https://linux-hardware.org/?probe=2a4f34aeb4) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [258d726766](https://linux-hardware.org/?probe=258d726766) | Oct 04, 2023 |
| MSI           | GE63 Raider RGB 9SF         | [6eaabebb19](https://linux-hardware.org/?probe=6eaabebb19) | Oct 04, 2023 |
| Lenovo        | ThinkPad P51 20HJS0RE02     | [892c35359f](https://linux-hardware.org/?probe=892c35359f) | Oct 04, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [48ee75db0b](https://linux-hardware.org/?probe=48ee75db0b) | Oct 03, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [12331db1c1](https://linux-hardware.org/?probe=12331db1c1) | Oct 03, 2023 |
| Dell          | Latitude 7310               | [1c6453acbe](https://linux-hardware.org/?probe=1c6453acbe) | Oct 03, 2023 |
| ASUSTek       | Zenbook UX535QA_UM535QA     | [ffd1d0957b](https://linux-hardware.org/?probe=ffd1d0957b) | Oct 03, 2023 |
| Valve         | Jupiter                     | [35dc2f9bbd](https://linux-hardware.org/?probe=35dc2f9bbd) | Oct 02, 2023 |
| Acer          | Swift SF515-51T             | [2452e6e54f](https://linux-hardware.org/?probe=2452e6e54f) | Oct 02, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [9b38690634](https://linux-hardware.org/?probe=9b38690634) | Oct 02, 2023 |
| ASUSTek       | UX303UA                     | [657233bb53](https://linux-hardware.org/?probe=657233bb53) | Oct 02, 2023 |
| Dell          | Precision 5480              | [21bd104767](https://linux-hardware.org/?probe=21bd104767) | Oct 02, 2023 |
| Dell          | G15 5511                    | [8510f95ae4](https://linux-hardware.org/?probe=8510f95ae4) | Oct 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [45dc056bee](https://linux-hardware.org/?probe=45dc056bee) | Oct 02, 2023 |
| Dell          | Inspiron 16 7610            | [ae7655427a](https://linux-hardware.org/?probe=ae7655427a) | Oct 02, 2023 |
| Apple         | MacBookAir6,2               | [25d2225829](https://linux-hardware.org/?probe=25d2225829) | Oct 02, 2023 |
| GPD           | G1621-02                    | [10ca9df59f](https://linux-hardware.org/?probe=10ca9df59f) | Oct 01, 2023 |
| Dell          | Latitude E6320              | [58713ab6bf](https://linux-hardware.org/?probe=58713ab6bf) | Oct 01, 2023 |
| Packard Be... | EasyNote LM98               | [8fdf8eee6c](https://linux-hardware.org/?probe=8fdf8eee6c) | Oct 01, 2023 |
| Lenovo        | ThinkPad P50 20EQS2U20N     | [4dc6dfbc84](https://linux-hardware.org/?probe=4dc6dfbc84) | Oct 01, 2023 |
| HP            | Victus by Laptop 16-d0xx... | [5ee355215f](https://linux-hardware.org/?probe=5ee355215f) | Oct 01, 2023 |
| Medion        | Deputy P40                  | [7e0fc5b52d](https://linux-hardware.org/?probe=7e0fc5b52d) | Sep 30, 2023 |
| UNOWHY        | Y13G012S4EI                 | [2b60435562](https://linux-hardware.org/?probe=2b60435562) | Sep 30, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | [681d3e6c86](https://linux-hardware.org/?probe=681d3e6c86) | Sep 30, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [89d519a3f5](https://linux-hardware.org/?probe=89d519a3f5) | Sep 30, 2023 |
| Dell          | Latitude 5500               | [ea091dbcf2](https://linux-hardware.org/?probe=ea091dbcf2) | Sep 29, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [7392f9db3b](https://linux-hardware.org/?probe=7392f9db3b) | Sep 29, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [96fa5ddfa8](https://linux-hardware.org/?probe=96fa5ddfa8) | Sep 29, 2023 |
| ASUSTek       | K72Jr                       | [9167494336](https://linux-hardware.org/?probe=9167494336) | Sep 28, 2023 |
| HP            | EliteBook 840 G2            | [bec979fcd0](https://linux-hardware.org/?probe=bec979fcd0) | Sep 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [7cbed3fca6](https://linux-hardware.org/?probe=7cbed3fca6) | Sep 28, 2023 |
| Dell          | XPS 17 9700                 | [38196b3712](https://linux-hardware.org/?probe=38196b3712) | Sep 28, 2023 |
| Dell          | G3 3590                     | [3523165978](https://linux-hardware.org/?probe=3523165978) | Sep 27, 2023 |
| Lenovo        | ThinkPad T430 2349S6S       | [e9b81983f2](https://linux-hardware.org/?probe=e9b81983f2) | Sep 27, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [593ddb6105](https://linux-hardware.org/?probe=593ddb6105) | Sep 27, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [cd5d2fae9e](https://linux-hardware.org/?probe=cd5d2fae9e) | Sep 27, 2023 |
| Dell          | XPS 17 9700                 | [c341826b7a](https://linux-hardware.org/?probe=c341826b7a) | Sep 27, 2023 |
| Notebook      | PCx0Dx                      | [53dd8cbd0d](https://linux-hardware.org/?probe=53dd8cbd0d) | Sep 27, 2023 |
| ASUSTek       | K72Jr                       | [9f32819945](https://linux-hardware.org/?probe=9f32819945) | Sep 26, 2023 |
| Dell          | G5 5590                     | [c7e7205fff](https://linux-hardware.org/?probe=c7e7205fff) | Sep 26, 2023 |
| Dell          | G5 5590                     | [0e80b66cb6](https://linux-hardware.org/?probe=0e80b66cb6) | Sep 26, 2023 |
| HP            | EliteBook 745 G6            | [bb5a7f8b2c](https://linux-hardware.org/?probe=bb5a7f8b2c) | Sep 26, 2023 |
| PC Special... | PCX0DX                      | [935fe5ddb0](https://linux-hardware.org/?probe=935fe5ddb0) | Sep 26, 2023 |
| Dell          | Inspiron 7577               | [a90c8128d1](https://linux-hardware.org/?probe=a90c8128d1) | Sep 26, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [24a1d008e6](https://linux-hardware.org/?probe=24a1d008e6) | Sep 26, 2023 |
| Notebook      | N2x0WU                      | [49046ef274](https://linux-hardware.org/?probe=49046ef274) | Sep 26, 2023 |
| Dell          | XPS 9315                    | [11411507e8](https://linux-hardware.org/?probe=11411507e8) | Sep 26, 2023 |
| HP            | Laptop 15s-eq1xxx           | [8142da7d40](https://linux-hardware.org/?probe=8142da7d40) | Sep 25, 2023 |
| Dell          | Precision M6800             | [027ed86f53](https://linux-hardware.org/?probe=027ed86f53) | Sep 25, 2023 |
| Acer          | Swift SF314-41              | [ef8b479649](https://linux-hardware.org/?probe=ef8b479649) | Sep 25, 2023 |
| Acer          | Swift SF314-44              | [6f5d49e16f](https://linux-hardware.org/?probe=6f5d49e16f) | Sep 25, 2023 |
| Acer          | Swift SF314-44              | [12f4ab85f3](https://linux-hardware.org/?probe=12f4ab85f3) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | [4e0f83e1fe](https://linux-hardware.org/?probe=4e0f83e1fe) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | [60ff167d14](https://linux-hardware.org/?probe=60ff167d14) | Sep 25, 2023 |
| Lenovo        | Yoga 2 13 20344             | [6a06543ed3](https://linux-hardware.org/?probe=6a06543ed3) | Sep 25, 2023 |
| Toshiba       | Satellite C50-B             | [92a5c3605c](https://linux-hardware.org/?probe=92a5c3605c) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK E734               | [61f61b1b63](https://linux-hardware.org/?probe=61f61b1b63) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK E734               | [ffb5ff9359](https://linux-hardware.org/?probe=ffb5ff9359) | Sep 25, 2023 |
| Dell          | Precision 5550              | [5a4d44b194](https://linux-hardware.org/?probe=5a4d44b194) | Sep 24, 2023 |
| Dell          | Latitude E6330              | [1375d355a5](https://linux-hardware.org/?probe=1375d355a5) | Sep 24, 2023 |
| Acer          | Swift SF314-44              | [b7f58e92a0](https://linux-hardware.org/?probe=b7f58e92a0) | Sep 24, 2023 |
| Lenovo        | ThinkPad P50 20EQS3FS00     | [a3ee3b9ca3](https://linux-hardware.org/?probe=a3ee3b9ca3) | Sep 24, 2023 |
| HP            | ZBook 14 G2                 | [1f29f31860](https://linux-hardware.org/?probe=1f29f31860) | Sep 24, 2023 |
| HP            | EliteBook 2560p             | [5072a3a6d5](https://linux-hardware.org/?probe=5072a3a6d5) | Sep 24, 2023 |
| Lenovo        | ThinkPad W550s 20E1S0VW0... | [e5c12ca1ce](https://linux-hardware.org/?probe=e5c12ca1ce) | Sep 23, 2023 |
| Unknown       | Unknown                     | [940b1d1eeb](https://linux-hardware.org/?probe=940b1d1eeb) | Sep 23, 2023 |
| Lenovo        | G50-80 80L0                 | [f08b8528da](https://linux-hardware.org/?probe=f08b8528da) | Sep 23, 2023 |
| UNOWHY        | Y13G002S4EI                 | [c3f95beccb](https://linux-hardware.org/?probe=c3f95beccb) | Sep 23, 2023 |
| Toshiba       | Satellite C70-B             | [904a43b77e](https://linux-hardware.org/?probe=904a43b77e) | Sep 23, 2023 |
| ASUSTek       | X750JB                      | [b9db8f6f02](https://linux-hardware.org/?probe=b9db8f6f02) | Sep 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1e9774c53c](https://linux-hardware.org/?probe=1e9774c53c) | Sep 22, 2023 |
| Acer          | Aspire 7530G                | [37d34804dd](https://linux-hardware.org/?probe=37d34804dd) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bab5438645](https://linux-hardware.org/?probe=bab5438645) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ad1f9f63c0](https://linux-hardware.org/?probe=ad1f9f63c0) | Sep 22, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [57c3bb43f5](https://linux-hardware.org/?probe=57c3bb43f5) | Sep 22, 2023 |
| Lenovo        | ThinkPad X230 23259T0       | [20286ecb4c](https://linux-hardware.org/?probe=20286ecb4c) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | [01f346ff26](https://linux-hardware.org/?probe=01f346ff26) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | [ba1ec3eb6d](https://linux-hardware.org/?probe=ba1ec3eb6d) | Sep 22, 2023 |
| Acer          | Nitro AN515-57              | [05c9cbc8e5](https://linux-hardware.org/?probe=05c9cbc8e5) | Sep 22, 2023 |
| Valve         | Jupiter                     | [dcc631e0fd](https://linux-hardware.org/?probe=dcc631e0fd) | Sep 22, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | [c5cda29091](https://linux-hardware.org/?probe=c5cda29091) | Sep 21, 2023 |
| Dell          | Latitude D500               | [1861582ebd](https://linux-hardware.org/?probe=1861582ebd) | Sep 21, 2023 |
| ASUSTek       | X550CC                      | [265f8a4dcd](https://linux-hardware.org/?probe=265f8a4dcd) | Sep 21, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [9a1d56bda1](https://linux-hardware.org/?probe=9a1d56bda1) | Sep 20, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [43e04cf99c](https://linux-hardware.org/?probe=43e04cf99c) | Sep 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [2846c7bbed](https://linux-hardware.org/?probe=2846c7bbed) | Sep 20, 2023 |
| Dell          | Latitude D500               | [19ccfd47c6](https://linux-hardware.org/?probe=19ccfd47c6) | Sep 20, 2023 |
| Chuwi         | LapBook Pro                 | [c3ff4d2f56](https://linux-hardware.org/?probe=c3ff4d2f56) | Sep 20, 2023 |
| Dell          | Latitude E5540              | [759aeff4ee](https://linux-hardware.org/?probe=759aeff4ee) | Sep 19, 2023 |
| Apple         | MacBookPro11,1              | [26f998fafb](https://linux-hardware.org/?probe=26f998fafb) | Sep 19, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a5f79b33f4](https://linux-hardware.org/?probe=a5f79b33f4) | Sep 19, 2023 |
| Acer          | Aspire 7715Z                | [7abea387dc](https://linux-hardware.org/?probe=7abea387dc) | Sep 19, 2023 |
| Dell          | Inspiron 7537               | [f3e268a82d](https://linux-hardware.org/?probe=f3e268a82d) | Sep 19, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [8b2701d6c7](https://linux-hardware.org/?probe=8b2701d6c7) | Sep 19, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [f9e5656f54](https://linux-hardware.org/?probe=f9e5656f54) | Sep 19, 2023 |
| Acer          | Aspire A317-53              | [7dfeb3f7ff](https://linux-hardware.org/?probe=7dfeb3f7ff) | Sep 19, 2023 |
| KUU           | Andes II                    | [a104ad8142](https://linux-hardware.org/?probe=a104ad8142) | Sep 18, 2023 |
| Lenovo        | ThinkPad T61 7661AU5        | [af39839071](https://linux-hardware.org/?probe=af39839071) | Sep 18, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [c1070eb99b](https://linux-hardware.org/?probe=c1070eb99b) | Sep 18, 2023 |
| Acer          | Swift SF314-42              | [1519801016](https://linux-hardware.org/?probe=1519801016) | Sep 18, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [a4964c1b7a](https://linux-hardware.org/?probe=a4964c1b7a) | Sep 18, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | [4b1c4ae225](https://linux-hardware.org/?probe=4b1c4ae225) | Sep 18, 2023 |
| HP            | ProBook 4540s               | [12465042c9](https://linux-hardware.org/?probe=12465042c9) | Sep 17, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1212656ddf](https://linux-hardware.org/?probe=1212656ddf) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [87f26cde55](https://linux-hardware.org/?probe=87f26cde55) | Sep 16, 2023 |
| HP            | EliteBook 840 G1            | [71bcb4c527](https://linux-hardware.org/?probe=71bcb4c527) | Sep 16, 2023 |
| MSI           | Stealth 14Studio A13VE      | [e57ab86521](https://linux-hardware.org/?probe=e57ab86521) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [00fd2287c0](https://linux-hardware.org/?probe=00fd2287c0) | Sep 16, 2023 |
| HP            | EliteBook 725 G3            | [6086fd0180](https://linux-hardware.org/?probe=6086fd0180) | Sep 16, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [fa207e873a](https://linux-hardware.org/?probe=fa207e873a) | Sep 15, 2023 |
| HP            | Laptop 17-ak0xx             | [b6c9c0ab68](https://linux-hardware.org/?probe=b6c9c0ab68) | Sep 15, 2023 |
| Dell          | Latitude 7310               | [afeaddd126](https://linux-hardware.org/?probe=afeaddd126) | Sep 15, 2023 |
| Dell          | Latitude 7310               | [ab616edf3b](https://linux-hardware.org/?probe=ab616edf3b) | Sep 15, 2023 |
| Dell          | Precision 5570              | [8b3c21b110](https://linux-hardware.org/?probe=8b3c21b110) | Sep 15, 2023 |
| Toshiba       | Satellite L875-11M          | [3774a26687](https://linux-hardware.org/?probe=3774a26687) | Sep 14, 2023 |
| Dell          | Latitude E6420              | [3aa2a92dbe](https://linux-hardware.org/?probe=3aa2a92dbe) | Sep 14, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [756eff685a](https://linux-hardware.org/?probe=756eff685a) | Sep 14, 2023 |
| Dell          | Latitude 5440               | [93a296a628](https://linux-hardware.org/?probe=93a296a628) | Sep 14, 2023 |
| KUU           | Andes II                    | [6270750e1e](https://linux-hardware.org/?probe=6270750e1e) | Sep 14, 2023 |
| ASUSTek       | K53SC                       | [814e80310b](https://linux-hardware.org/?probe=814e80310b) | Sep 13, 2023 |
| Dell          | XPS 15 9570                 | [b8932f0fbd](https://linux-hardware.org/?probe=b8932f0fbd) | Sep 13, 2023 |
| Dell          | Latitude 7480               | [82ba4e9fde](https://linux-hardware.org/?probe=82ba4e9fde) | Sep 13, 2023 |
| ASUSTek       | N75SF                       | [cff971fa54](https://linux-hardware.org/?probe=cff971fa54) | Sep 13, 2023 |
| Dell          | Vostro 14 3435              | [edbdf685d6](https://linux-hardware.org/?probe=edbdf685d6) | Sep 13, 2023 |
| Sony          | VPCEB1E1E                   | [cbd095ee01](https://linux-hardware.org/?probe=cbd095ee01) | Sep 12, 2023 |
| ASUSTek       | X550JK                      | [0965a776b0](https://linux-hardware.org/?probe=0965a776b0) | Sep 12, 2023 |
| Dell          | Latitude E5420              | [3d9680f20d](https://linux-hardware.org/?probe=3d9680f20d) | Sep 12, 2023 |
| ASUSTek       | X550JK                      | [00a34c8719](https://linux-hardware.org/?probe=00a34c8719) | Sep 12, 2023 |
| Google        | Droid                       | [7b7eb437c6](https://linux-hardware.org/?probe=7b7eb437c6) | Sep 12, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [de7acf45a6](https://linux-hardware.org/?probe=de7acf45a6) | Sep 12, 2023 |
| Dell          | Latitude E6410              | [14c3b0cdeb](https://linux-hardware.org/?probe=14c3b0cdeb) | Sep 12, 2023 |
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | [9506117d6f](https://linux-hardware.org/?probe=9506117d6f) | Sep 12, 2023 |
| Dell          | Precision 3571              | [cf2bec0e5b](https://linux-hardware.org/?probe=cf2bec0e5b) | Sep 12, 2023 |
| Dell          | Precision 7520              | [35bbdb93c9](https://linux-hardware.org/?probe=35bbdb93c9) | Sep 11, 2023 |
| Dell          | Latitude E6230              | [fa184bbd98](https://linux-hardware.org/?probe=fa184bbd98) | Sep 11, 2023 |
| Acer          | Aspire VX5-591G             | [70b8cb408c](https://linux-hardware.org/?probe=70b8cb408c) | Sep 11, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [5ac44fe5ec](https://linux-hardware.org/?probe=5ac44fe5ec) | Sep 11, 2023 |
| Dell          | Latitude 5420               | [d561f541f6](https://linux-hardware.org/?probe=d561f541f6) | Sep 10, 2023 |
| Dell          | Latitude 5420               | [982a0e5ce2](https://linux-hardware.org/?probe=982a0e5ce2) | Sep 10, 2023 |
| Dell          | Latitude 5414               | [9fff061209](https://linux-hardware.org/?probe=9fff061209) | Sep 10, 2023 |
| ASUSTek       | ZenBook UX393EA_UX393EA     | [21d20fbd09](https://linux-hardware.org/?probe=21d20fbd09) | Sep 10, 2023 |
| Dell          | Precision 3571              | [0790a2726f](https://linux-hardware.org/?probe=0790a2726f) | Sep 10, 2023 |
| Dell          | Precision 3571              | [2d92d73c33](https://linux-hardware.org/?probe=2d92d73c33) | Sep 10, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [8121162f41](https://linux-hardware.org/?probe=8121162f41) | Sep 10, 2023 |
| Dell          | Latitude E6540              | [7bd2661f03](https://linux-hardware.org/?probe=7bd2661f03) | Sep 10, 2023 |
| Dell          | Latitude 5540               | [cb3d385ed5](https://linux-hardware.org/?probe=cb3d385ed5) | Sep 09, 2023 |
| Lenovo        | ThinkPad L580 20LW000VFR    | [a7dfc5e0f5](https://linux-hardware.org/?probe=a7dfc5e0f5) | Sep 09, 2023 |
| Lenovo        | ThinkPad L580 20LW000VFR    | [e224a5dc53](https://linux-hardware.org/?probe=e224a5dc53) | Sep 09, 2023 |
| Dell          | Inspiron 7580               | [9705f02462](https://linux-hardware.org/?probe=9705f02462) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [8bbba91a69](https://linux-hardware.org/?probe=8bbba91a69) | Sep 09, 2023 |
| HP            | Laptop 17-ak0xx             | [d5220131ff](https://linux-hardware.org/?probe=d5220131ff) | Sep 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [65c3a9e2d5](https://linux-hardware.org/?probe=65c3a9e2d5) | Sep 09, 2023 |
| Thomson       | N14C4WH64                   | [1e817297bb](https://linux-hardware.org/?probe=1e817297bb) | Sep 08, 2023 |
| Thomson       | N14C4WH64                   | [c1dae32be6](https://linux-hardware.org/?probe=c1dae32be6) | Sep 08, 2023 |
| Dell          | Vostro 5502                 | [a131efa36e](https://linux-hardware.org/?probe=a131efa36e) | Sep 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ee89a78be0](https://linux-hardware.org/?probe=ee89a78be0) | Sep 08, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [4159e1ea16](https://linux-hardware.org/?probe=4159e1ea16) | Sep 08, 2023 |
| Dell          | Inspiron 15 5510            | [c7e4b4dfc1](https://linux-hardware.org/?probe=c7e4b4dfc1) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [8a05090057](https://linux-hardware.org/?probe=8a05090057) | Sep 07, 2023 |
| HP            | ProBook 650 G8 Notebook ... | [b11a7b69f0](https://linux-hardware.org/?probe=b11a7b69f0) | Sep 07, 2023 |
| Dell          | Latitude 7420               | [77df1805f6](https://linux-hardware.org/?probe=77df1805f6) | Sep 07, 2023 |
| Dell          | XPS 15 9550                 | [c9f30a2b26](https://linux-hardware.org/?probe=c9f30a2b26) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [2505f514b1](https://linux-hardware.org/?probe=2505f514b1) | Sep 06, 2023 |
| MSI           | GS60 2PC Ghost              | [0b971b067a](https://linux-hardware.org/?probe=0b971b067a) | Sep 06, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [c31e15f2ba](https://linux-hardware.org/?probe=c31e15f2ba) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Samsung       | 950XED                      | [3d8ba5a34c](https://linux-hardware.org/?probe=3d8ba5a34c) | Sep 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [02c4374b47](https://linux-hardware.org/?probe=02c4374b47) | Sep 04, 2023 |
| eMachines     | Rhine V1.42                 | [c18c4d64bd](https://linux-hardware.org/?probe=c18c4d64bd) | Sep 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d5f8d13304](https://linux-hardware.org/?probe=d5f8d13304) | Sep 04, 2023 |
| Dell          | Vostro 14 3435              | [d35ddd8539](https://linux-hardware.org/?probe=d35ddd8539) | Sep 04, 2023 |
| Dell          | Vostro 14 3435              | [34a27b9c29](https://linux-hardware.org/?probe=34a27b9c29) | Sep 04, 2023 |
| Dell          | Precision 3581              | [739b270d83](https://linux-hardware.org/?probe=739b270d83) | Sep 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ0E    | [c5cdf73aa5](https://linux-hardware.org/?probe=c5cdf73aa5) | Sep 04, 2023 |
| Dell          | XPS 13 9310                 | [e30eaf0d9a](https://linux-hardware.org/?probe=e30eaf0d9a) | Sep 03, 2023 |
| Acer          | Nitro AN515-57              | [95b036ac9a](https://linux-hardware.org/?probe=95b036ac9a) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [88a04ab4b8](https://linux-hardware.org/?probe=88a04ab4b8) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [56cc7d7a27](https://linux-hardware.org/?probe=56cc7d7a27) | Sep 03, 2023 |
| Samsung       | R510/P510                   | [fa457144d5](https://linux-hardware.org/?probe=fa457144d5) | Sep 03, 2023 |
| Notebook      | PCx0Dx                      | [89d5a9b606](https://linux-hardware.org/?probe=89d5a9b606) | Sep 03, 2023 |
| Acer          | Swift SF314-42              | [89dcb5988f](https://linux-hardware.org/?probe=89dcb5988f) | Sep 03, 2023 |
| HP            | Pavilion x2 Detachable      | [c98b2d5aba](https://linux-hardware.org/?probe=c98b2d5aba) | Sep 03, 2023 |
| MSI           | GF63 Thin 9SC               | [510641439b](https://linux-hardware.org/?probe=510641439b) | Sep 03, 2023 |
| ASUSTek       | X550CC                      | [1468567e45](https://linux-hardware.org/?probe=1468567e45) | Sep 03, 2023 |
| Acer          | Swift SF314-42              | [8552bc9508](https://linux-hardware.org/?probe=8552bc9508) | Sep 03, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [8146fce36b](https://linux-hardware.org/?probe=8146fce36b) | Sep 03, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [7ebd20a049](https://linux-hardware.org/?probe=7ebd20a049) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [9903b0fbea](https://linux-hardware.org/?probe=9903b0fbea) | Sep 03, 2023 |
| EUROCOM       | RAPTOR X17                  | [93827ff6f1](https://linux-hardware.org/?probe=93827ff6f1) | Sep 03, 2023 |
| Thomson       | N14C4WH64                   | [3a5fd5b62b](https://linux-hardware.org/?probe=3a5fd5b62b) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [d669a79662](https://linux-hardware.org/?probe=d669a79662) | Sep 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [88673d4088](https://linux-hardware.org/?probe=88673d4088) | Sep 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6ed47558ae](https://linux-hardware.org/?probe=6ed47558ae) | Sep 03, 2023 |
| Apple         | MacBookAir5,1               | [57bb5d91ab](https://linux-hardware.org/?probe=57bb5d91ab) | Sep 03, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [c5787921e3](https://linux-hardware.org/?probe=c5787921e3) | Sep 03, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1008      | 15.52%  |
| Ubuntu 22.04       | 599       | 9.23%   |
| Ubuntu 18.04       | 314       | 4.84%   |
| Debian 11          | 222       | 3.42%   |
| OpenMandriva 4.2   | 183       | 2.82%   |
| OpenMandriva 4.3   | 158       | 2.43%   |
| Linux Mint 20.3    | 128       | 1.97%   |
| Arch Rolling       | 128       | 1.97%   |
| Debian 12          | 116       | 1.79%   |
| Xubuntu 20.04      | 110       | 1.69%   |
| Linux Mint 21.1    | 90        | 1.39%   |
| Zorin 16           | 80        | 1.23%   |
| Arch               | 80        | 1.23%   |
| OpenMandriva 23.01 | 77        | 1.19%   |
| Ubuntu 21.10       | 71        | 1.09%   |
| Debian 10          | 69        | 1.06%   |
| Pop!_OS 22.04      | 67        | 1.03%   |
| Linux Mint 20.2    | 67        | 1.03%   |
| Fedora 38          | 64        | 0.99%   |
| Manjaro            | 62        | 0.95%   |
| OpenMandriva 23.03 | 61        | 0.94%   |
| Ubuntu 23.04       | 60        | 0.92%   |
| Ubuntu 19.10       | 59        | 0.91%   |
| Xubuntu 22.04      | 57        | 0.88%   |
| Ubuntu 21.04       | 57        | 0.88%   |
| Ubuntu 20.10       | 53        | 0.82%   |
| Linux Mint 21.2    | 53        | 0.82%   |
| Linux Mint 19.3    | 52        | 0.8%    |
| Xubuntu 18.04      | 50        | 0.77%   |
| Linux Mint 21      | 50        | 0.77%   |
| Fedora 33          | 49        | 0.75%   |
| Ubuntu 22.10       | 48        | 0.74%   |
| OpenMandriva 23.08 | 48        | 0.74%   |
| Fedora 37          | 47        | 0.72%   |
| Fedora 34          | 45        | 0.69%   |
| Linux Mint 20.1    | 43        | 0.66%   |
| Kubuntu 20.04      | 42        | 0.65%   |
| ArcoLinux Rolling  | 41        | 0.63%   |
| Fedora 36          | 40        | 0.62%   |
| Fedora 32          | 40        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2244      | 36.64%  |
| OpenMandriva  | 575       | 9.39%   |
| Linux Mint    | 525       | 8.57%   |
| Debian        | 463       | 7.56%   |
| Fedora        | 342       | 5.58%   |
| Xubuntu       | 239       | 3.9%    |
| Arch          | 204       | 3.33%   |
| Pop!_OS       | 169       | 2.76%   |
| Manjaro       | 159       | 2.6%    |
| Kubuntu       | 143       | 2.33%   |
| Zorin         | 114       | 1.86%   |
| Lubuntu       | 84        | 1.37%   |
| Ubuntu MATE   | 79        | 1.29%   |
| ROSA          | 75        | 1.22%   |
| KDE neon      | 63        | 1.03%   |
| openSUSE      | 55        | 0.9%    |
| Kali          | 52        | 0.85%   |
| Endless       | 43        | 0.7%    |
| ArcoLinux     | 42        | 0.69%   |
| Gentoo        | 41        | 0.67%   |
| Elementary    | 37        | 0.6%    |
| SteamOS       | 34        | 0.56%   |
| Ubuntu Budgie | 32        | 0.52%   |
| Ubuntu Unity  | 27        | 0.44%   |
| EndeavourOS   | 25        | 0.41%   |
| LMDE          | 22        | 0.36%   |
| BlackPanther  | 20        | 0.33%   |
| Parrot        | 19        | 0.31%   |
| Ubuntu Studio | 13        | 0.21%   |
| MX            | 13        | 0.21%   |
| Xero          | 11        | 0.18%   |
| CentOS        | 11        | 0.18%   |
| Kaisen        | 9         | 0.15%   |
| NixOS         | 8         | 0.13%   |
| Linux Lite    | 8         | 0.13%   |
| Clear Linux   | 8         | 0.13%   |
| Peppermint    | 6         | 0.1%    |
| Mageia        | 6         | 0.1%    |
| Garuda Linux  | 6         | 0.1%    |
| RHEL          | 5         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 173       | 2.44%   |
| 5.16.7-desktop-1omv4003  | 145       | 2.05%   |
| 5.15.0-56-generic        | 83        | 1.17%   |
| 5.4.0-42-generic         | 73        | 1.03%   |
| 6.1.1-desktop-1omv2290   | 68        | 0.96%   |
| 5.15.0-58-generic        | 60        | 0.85%   |
| 6.2.6-desktop-1omv2390   | 56        | 0.79%   |
| 5.15.0-52-generic        | 53        | 0.75%   |
| 5.11.0-38-generic        | 51        | 0.72%   |
| 6.2.0-26-generic         | 44        | 0.62%   |
| 5.4.0-58-generic         | 44        | 0.62%   |
| 5.4.0-52-generic         | 44        | 0.62%   |
| 5.15.0-48-generic        | 44        | 0.62%   |
| 5.11.0-27-generic        | 43        | 0.61%   |
| 6.4.11-desktop-1omv2390  | 40        | 0.56%   |
| 5.4.0-26-generic         | 40        | 0.56%   |
| 5.4.0-48-generic         | 36        | 0.51%   |
| 6.1.0-16-amd64           | 35        | 0.49%   |
| 5.8.0-50-generic         | 35        | 0.49%   |
| 5.15.0-91-generic        | 35        | 0.49%   |
| 5.15.0-46-generic        | 35        | 0.49%   |
| 5.11.0-37-generic        | 35        | 0.49%   |
| 6.2.0-39-generic         | 34        | 0.48%   |
| 5.8.0-43-generic         | 34        | 0.48%   |
| 5.4.0-91-generic         | 33        | 0.47%   |
| 5.4.0-65-generic         | 33        | 0.47%   |
| 5.15.0-47-generic        | 33        | 0.47%   |
| 5.15.0-43-generic        | 33        | 0.47%   |
| 5.13.0-30-generic        | 33        | 0.47%   |
| 5.8.0-44-generic         | 32        | 0.45%   |
| 5.19.0-35-generic        | 32        | 0.45%   |
| 5.11.0-43-generic        | 32        | 0.45%   |
| 5.4.0-37-generic         | 31        | 0.44%   |
| 5.11.0-40-generic        | 31        | 0.44%   |
| 6.5.0-14-generic         | 30        | 0.42%   |
| 6.2.0-36-generic         | 30        | 0.42%   |
| 5.19.0-41-generic        | 30        | 0.42%   |
| 5.15.0-60-generic        | 30        | 0.42%   |
| 5.13.0-40-generic        | 30        | 0.42%   |
| 5.19.0-38-generic        | 29        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 978       | 14.63%  |
| 5.15.0  | 783       | 11.71%  |
| 5.11.0  | 358       | 5.36%   |
| 5.8.0   | 353       | 5.28%   |
| 5.13.0  | 318       | 4.76%   |
| 6.2.0   | 270       | 4.04%   |
| 5.10.0  | 261       | 3.9%    |
| 5.19.0  | 258       | 3.86%   |
| 4.15.0  | 232       | 3.47%   |
| 5.3.0   | 176       | 2.63%   |
| 5.10.14 | 174       | 2.6%    |
| 5.16.7  | 145       | 2.17%   |
| 6.1.0   | 127       | 1.9%    |
| 5.0.0   | 99        | 1.48%   |
| 6.1.1   | 78        | 1.17%   |
| 6.5.0   | 77        | 1.15%   |
| 4.18.0  | 66        | 0.99%   |
| 4.19.0  | 64        | 0.96%   |
| 6.2.6   | 63        | 0.94%   |
| 6.4.11  | 46        | 0.69%   |
| 5.14.0  | 37        | 0.55%   |
| 6.0.0   | 29        | 0.43%   |
| 6.6.2   | 26        | 0.39%   |
| 5.17.5  | 21        | 0.31%   |
| 5.16.13 | 20        | 0.3%    |
| 5.16.0  | 19        | 0.28%   |
| 5.11.12 | 19        | 0.28%   |
| 4.18.16 | 19        | 0.28%   |
| 5.18.0  | 17        | 0.25%   |
| 5.17.0  | 16        | 0.24%   |
| 5.18.12 | 15        | 0.22%   |
| 4.9.20  | 15        | 0.22%   |
| 6.5.5   | 14        | 0.21%   |
| 5.9.0   | 14        | 0.21%   |
| 5.6.0   | 14        | 0.21%   |
| 4.4.0   | 14        | 0.21%   |
| 6.6.8   | 13        | 0.19%   |
| 6.3.5   | 13        | 0.19%   |
| 5.9.11  | 13        | 0.19%   |
| 5.19.12 | 13        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 1028      | 15.59%  |
| 5.15    | 895       | 13.57%  |
| 5.10    | 516       | 7.82%   |
| 5.11    | 409       | 6.2%    |
| 6.2     | 397       | 6.02%   |
| 5.8     | 394       | 5.97%   |
| 5.13    | 355       | 5.38%   |
| 5.19    | 312       | 4.73%   |
| 6.1     | 292       | 4.43%   |
| 4.15    | 232       | 3.52%   |
| 5.16    | 221       | 3.35%   |
| 5.3     | 201       | 3.05%   |
| 6.5     | 152       | 2.3%    |
| 6.4     | 112       | 1.7%    |
| 5.0     | 103       | 1.56%   |
| 5.14    | 97        | 1.47%   |
| 6.0     | 91        | 1.38%   |
| 4.18    | 87        | 1.32%   |
| 6.6     | 86        | 1.3%    |
| 5.9     | 71        | 1.08%   |
| 4.19    | 71        | 1.08%   |
| 5.18    | 67        | 1.02%   |
| 5.17    | 66        | 1%      |
| 6.3     | 65        | 0.99%   |
| 5.6     | 50        | 0.76%   |
| 4.9     | 47        | 0.71%   |
| 5.7     | 42        | 0.64%   |
| 5.12    | 38        | 0.58%   |
| 5.5     | 23        | 0.35%   |
| 4.4     | 16        | 0.24%   |
| 4.1     | 11        | 0.17%   |
| 4.14    | 9         | 0.14%   |
| 6.7     | 8         | 0.12%   |
| 5.2     | 7         | 0.11%   |
| 4.13    | 5         | 0.08%   |
| 4.12    | 5         | 0.08%   |
| 4.10    | 4         | 0.06%   |
| 3.10    | 3         | 0.05%   |
| 5.1     | 2         | 0.03%   |
| 4.20    | 2         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 5818      | 97.8%   |
| i686    | 127       | 2.13%   |
| aarch64 | 2         | 0.03%   |
| armv7l  | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 2897      | 46.89%  |
| KDE5              | 1082      | 17.51%  |
| XFCE              | 554       | 8.97%   |
| Unknown           | 458       | 7.41%   |
| X-Cinnamon        | 371       | 6.01%   |
| MATE              | 232       | 3.76%   |
| LXQt              | 102       | 1.65%   |
| Cinnamon          | 87        | 1.41%   |
| i3                | 66        | 1.07%   |
| KDE               | 64        | 1.04%   |
| KDE4              | 51        | 0.83%   |
| Budgie            | 43        | 0.7%    |
| Pantheon          | 39        | 0.63%   |
| Unity             | 28        | 0.45%   |
| LXDE              | 21        | 0.34%   |
| GNOME Flashback   | 20        | 0.32%   |
| Deepin            | 11        | 0.18%   |
| GNOME Classic     | 7         | 0.11%   |
| sway              | 6         | 0.1%    |
| awesome           | 6         | 0.1%    |
| Hyprland          | 4         | 0.06%   |
| Enlightenment     | 4         | 0.06%   |
| trinity           | 3         | 0.05%   |
| i3-with-shmlog    | 3         | 0.05%   |
| icewm             | 2         | 0.03%   |
| bspwm             | 2         | 0.03%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| xmonad            | 1         | 0.02%   |
| wmaker-common     | 1         | 0.02%   |
| qtile             | 1         | 0.02%   |
| openbox           | 1         | 0.02%   |
| none+i3           | 1         | 0.02%   |
| Lubuntu           | 1         | 0.02%   |
| lightdm-xsession  | 1         | 0.02%   |
| LeftWM            | 1         | 0.02%   |
| KDE6              | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| GNOME-Classic     | 1         | 0.02%   |
| dwm-sc            | 1         | 0.02%   |
| DDE               | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 4522      | 73.4%   |
| Wayland | 1308      | 21.23%  |
| Unknown | 239       | 3.88%   |
| Tty     | 91        | 1.48%   |
| Xcb     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2083      | 33.61%  |
| SDDM    | 1059      | 17.09%  |
| GDM     | 1014      | 16.36%  |
| GDM3    | 989       | 15.96%  |
| LightDM | 791       | 12.76%  |
| TDM     | 183       | 2.95%   |
| KDM     | 49        | 0.79%   |
| XDM     | 9         | 0.15%   |
| SLiM    | 8         | 0.13%   |
| NODM    | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| LXDM    | 2         | 0.03%   |
| GREETD  | 2         | 0.03%   |
| WDM     | 1         | 0.02%   |
| SLIMSKI | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| LY-DM   | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| fr_FR       | 4197      | 69.27%  |
| en_US       | 1134      | 18.72%  |
| Unknown     | 405       | 6.68%   |
| en_GB       | 103       | 1.7%    |
| C           | 64        | 1.06%   |
| de_DE       | 17        | 0.28%   |
| it_IT       | 16        | 0.26%   |
| ru_RU       | 14        | 0.23%   |
| pl_PL       | 10        | 0.17%   |
| es_ES       | 10        | 0.17%   |
| fr_CH       | 8         | 0.13%   |
| POSIX       | 5         | 0.08%   |
| nl_NL       | 5         | 0.08%   |
| fr_CA       | 5         | 0.08%   |
| en_IE       | 5         | 0.08%   |
| pt_PT       | 4         | 0.07%   |
| fr_BE       | 4         | 0.07%   |
| en_IN       | 4         | 0.07%   |
| sv_SE       | 3         | 0.05%   |
| ru_UA       | 3         | 0.05%   |
| pt_BR       | 3         | 0.05%   |
| en_CA       | 3         | 0.05%   |
| en_AU       | 3         | 0.05%   |
| sk_SK       | 2         | 0.03%   |
| ro_RO       | 2         | 0.03%   |
| hu_HU       | 2         | 0.03%   |
| fr_LU       | 2         | 0.03%   |
| en_DK       | 2         | 0.03%   |
| en_AG       | 2         | 0.03%   |
| cs_CZ       | 2         | 0.03%   |
| C.UTF8      | 2         | 0.03%   |
| zh_CN       | 1         | 0.02%   |
| UTF-8       | 1         | 0.02%   |
| tr_TR       | 1         | 0.02%   |
| oc_FR       | 1         | 0.02%   |
| nb_NO       | 1         | 0.02%   |
| fr_FR@euro  | 1         | 0.02%   |
| fr_FR.UTF8  | 1         | 0.02%   |
| fr_FR.utf-8 | 1         | 0.02%   |
| es_VE       | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3564      | 58.69%  |
| BIOS | 2509      | 41.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 4786      | 78.27%  |
| Overlay  | 468       | 7.65%   |
| Btrfs    | 461       | 7.54%   |
| Tmpfs    | 170       | 2.78%   |
| Unknown  | 111       | 1.82%   |
| Xfs      | 48        | 0.78%   |
| Zfs      | 34        | 0.56%   |
| F2fs     | 14        | 0.23%   |
| Ext3     | 12        | 0.2%    |
| Ext2     | 9         | 0.15%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 3105      | 50.82%  |
| Unknown | 2231      | 36.51%  |
| MBR     | 774       | 12.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5236      | 86.55%  |
| Yes       | 814       | 13.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4253      | 70.51%  |
| Yes       | 1779      | 29.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 1054      | 17.72%  |
| Hewlett-Packard     | 1011      | 17%     |
| Lenovo              | 974       | 16.38%  |
| ASUSTek Computer    | 946       | 15.9%   |
| Acer                | 435       | 7.31%   |
| MSI                 | 222       | 3.73%   |
| Toshiba             | 197       | 3.31%   |
| Apple               | 131       | 2.2%    |
| Notebook            | 104       | 1.75%   |
| HUAWEI              | 98        | 1.65%   |
| Samsung Electronics | 77        | 1.29%   |
| Sony                | 73        | 1.23%   |
| Packard Bell        | 67        | 1.13%   |
| Valve               | 34        | 0.57%   |
| UNOWHY              | 30        | 0.5%    |
| TUXEDO              | 30        | 0.5%    |
| Thomson             | 29        | 0.49%   |
| Unknown             | 29        | 0.49%   |
| Timi                | 26        | 0.44%   |
| eMachines           | 25        | 0.42%   |
| Clevo               | 24        | 0.4%    |
| Google              | 23        | 0.39%   |
| Fujitsu             | 23        | 0.39%   |
| Fujitsu Siemens     | 22        | 0.37%   |
| Gigabyte Technology | 21        | 0.35%   |
| Alienware           | 21        | 0.35%   |
| PC Specialist       | 17        | 0.29%   |
| Medion              | 17        | 0.29%   |
| Teclast             | 13        | 0.22%   |
| Chuwi               | 13        | 0.22%   |
| Razer               | 12        | 0.2%    |
| Framework           | 11        | 0.18%   |
| HONOR               | 9         | 0.15%   |
| Intel               | 7         | 0.12%   |
| BESSTAR Tech        | 7         | 0.12%   |
| LDLC                | 6         | 0.1%    |
| System76            | 5         | 0.08%   |
| Schenker            | 5         | 0.08%   |
| LG Electronics      | 5         | 0.08%   |
| SLIMBOOK            | 4         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 50        | 0.84%   |
| HP Notebook                     | 46        | 0.77%   |
| HP Pavilion 17                  | 38        | 0.64%   |
| Valve Jupiter                   | 33        | 0.55%   |
| HP Pavilion dv6                 | 31        | 0.52%   |
| HP Pavilion dv7                 | 29        | 0.49%   |
| ASUS S551LN                     | 22        | 0.37%   |
| HP Pavilion g7                  | 19        | 0.32%   |
| HP EliteBook 840 G3             | 18        | 0.3%    |
| Dell XPS 13 9310                | 18        | 0.3%    |
| HP ProBook 650 G1               | 17        | 0.29%   |
| Dell XPS 15 9570                | 17        | 0.29%   |
| Dell Latitude E6420             | 16        | 0.27%   |
| HUAWEI HVY-WXX9                 | 15        | 0.25%   |
| HP Pavilion Notebook            | 15        | 0.25%   |
| HP Pavilion 15                  | 15        | 0.25%   |
| Dell XPS 15 7590                | 15        | 0.25%   |
| Dell XPS 13 9380                | 15        | 0.25%   |
| Dell XPS 13 7390                | 15        | 0.25%   |
| Dell Latitude 5420              | 15        | 0.25%   |
| Dell Latitude 5400              | 15        | 0.25%   |
| HP Pavilion g6                  | 14        | 0.24%   |
| HP EliteBook 840 G2             | 14        | 0.24%   |
| Dell XPS 15 9500                | 13        | 0.22%   |
| Dell Latitude 7490              | 13        | 0.22%   |
| HUAWEI NBLK-WAX9X               | 12        | 0.2%    |
| HP OMEN by Laptop               | 12        | 0.2%    |
| HP EliteBook 840 G8 Notebook PC | 12        | 0.2%    |
| HP EliteBook 840 G1             | 12        | 0.2%    |
| Dell Latitude E6400             | 12        | 0.2%    |
| Lenovo Legion 5 15ACH6H 82JU    | 11        | 0.18%   |
| Dell Precision 7560             | 11        | 0.18%   |
| Dell Precision 5570             | 11        | 0.18%   |
| UNOWHY Y13G010S4EI              | 10        | 0.17%   |
| Toshiba Satellite C660          | 10        | 0.17%   |
| Lenovo G50-45 80E3              | 10        | 0.17%   |
| Lenovo G50-30 80G0              | 10        | 0.17%   |
| HP ProBook 640 G1               | 10        | 0.17%   |
| HP Laptop 17-cp0xxx             | 10        | 0.17%   |
| HP Laptop 15-db0xxx             | 10        | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 568       | 9.55%   |
| Dell Latitude         | 421       | 7.08%   |
| Acer Aspire           | 295       | 4.96%   |
| HP Pavilion           | 263       | 4.42%   |
| HP EliteBook          | 206       | 3.46%   |
| Lenovo IdeaPad        | 193       | 3.24%   |
| Dell XPS              | 187       | 3.14%   |
| Dell Precision        | 168       | 2.82%   |
| Toshiba Satellite     | 164       | 2.76%   |
| HP ProBook            | 161       | 2.71%   |
| Dell Inspiron         | 153       | 2.57%   |
| ASUS VivoBook         | 143       | 2.4%    |
| HP Laptop             | 89        | 1.5%    |
| ASUS ZenBook          | 71        | 1.19%   |
| Packard Bell EasyNote | 58        | 0.98%   |
| Acer Swift            | 57        | 0.96%   |
| ASUS ROG              | 51        | 0.86%   |
| HP ZBook              | 50        | 0.84%   |
| Unknown               | 50        | 0.84%   |
| Lenovo Legion         | 49        | 0.82%   |
| Dell Vostro           | 47        | 0.79%   |
| HP Notebook           | 46        | 0.77%   |
| ASUS ASUS             | 45        | 0.76%   |
| HP Compaq             | 40        | 0.67%   |
| Acer Nitro            | 34        | 0.57%   |
| Valve Jupiter         | 33        | 0.55%   |
| HP OMEN               | 28        | 0.47%   |
| HP ENVY               | 25        | 0.42%   |
| Lenovo Yoga           | 22        | 0.37%   |
| Lenovo ThinkBook      | 22        | 0.37%   |
| ASUS S551LN           | 22        | 0.37%   |
| MSI Modern            | 21        | 0.35%   |
| Fujitsu LIFEBOOK      | 21        | 0.35%   |
| Dell G5               | 20        | 0.34%   |
| ASUS TUF              | 19        | 0.32%   |
| Acer TravelMate       | 18        | 0.3%    |
| Toshiba PORTEGE       | 17        | 0.29%   |
| Dell G3               | 17        | 0.29%   |
| Apple MacBookPro5     | 16        | 0.27%   |
| HUAWEI HVY-WXX9       | 15        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 589       | 9.9%    |
| 2019    | 559       | 9.4%    |
| 2021    | 509       | 8.56%   |
| 2018    | 486       | 8.17%   |
| 2013    | 425       | 7.15%   |
| 2012    | 383       | 6.44%   |
| 2015    | 368       | 6.19%   |
| 2011    | 352       | 5.92%   |
| 2016    | 327       | 5.5%    |
| 2014    | 317       | 5.33%   |
| 2017    | 312       | 5.25%   |
| 2008    | 284       | 4.77%   |
| 2010    | 281       | 4.72%   |
| 2022    | 276       | 4.64%   |
| 2009    | 203       | 3.41%   |
| 2007    | 111       | 1.87%   |
| 2023    | 102       | 1.71%   |
| 2006    | 37        | 0.62%   |
| 2005    | 17        | 0.29%   |
| Unknown | 5         | 0.08%   |
| 2004    | 3         | 0.05%   |
| 2003    | 1         | 0.02%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5948      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5300      | 88.35%  |
| Enabled  | 699       | 11.65%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5916      | 99.45%  |
| Yes  | 33        | 0.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1650      | 27.43%  |
| 3.01-4.0    | 1406      | 23.37%  |
| 16.01-24.0  | 1028      | 17.09%  |
| 8.01-16.0   | 965       | 16.04%  |
| 32.01-64.0  | 446       | 7.41%   |
| 1.01-2.0    | 235       | 3.91%   |
| 2.01-3.0    | 107       | 1.78%   |
| 64.01-256.0 | 77        | 1.28%   |
| 24.01-32.0  | 58        | 0.96%   |
| 0.51-1.0    | 35        | 0.58%   |
| 0.01-0.5    | 6         | 0.1%    |
| Unknown     | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2215      | 33.91%  |
| 2.01-3.0   | 1701      | 26.04%  |
| 4.01-8.0   | 998       | 15.28%  |
| 3.01-4.0   | 864       | 13.23%  |
| 0.51-1.0   | 373       | 5.71%   |
| 8.01-16.0  | 285       | 4.36%   |
| 0.01-0.5   | 48        | 0.73%   |
| 16.01-24.0 | 32        | 0.49%   |
| 24.01-32.0 | 12        | 0.18%   |
| 32.01-64.0 | 2         | 0.03%   |
| Unknown    | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4443      | 73.49%  |
| 2      | 1378      | 22.79%  |
| 3      | 143       | 2.37%   |
| 0      | 47        | 0.78%   |
| 4      | 23        | 0.38%   |
| 5      | 6         | 0.1%    |
| 6      | 3         | 0.05%   |
| 7      | 2         | 0.03%   |
| 8      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3764      | 63.01%  |
| Yes       | 2210      | 36.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4814      | 80.58%  |
| No        | 1160      | 19.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5849      | 98.22%  |
| No        | 106       | 1.78%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4623      | 76.79%  |
| No        | 1397      | 23.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 5948      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Paris                | 985       | 15.16%  |
| Lyon                 | 126       | 1.94%   |
| Toulouse             | 120       | 1.85%   |
| Marseille            | 116       | 1.79%   |
| Nantes               | 78        | 1.2%    |
| Montpellier          | 76        | 1.17%   |
| Rennes               | 65        | 1%      |
| Roubaix              | 64        | 0.98%   |
| Bordeaux             | 63        | 0.97%   |
| Strasbourg           | 59        | 0.91%   |
| Lille                | 58        | 0.89%   |
| Grenoble             | 55        | 0.85%   |
| Villeurbanne         | 38        | 0.58%   |
| Brest                | 34        | 0.52%   |
| Nice                 | 32        | 0.49%   |
| Clichy-sous-Bois     | 31        | 0.48%   |
| Rouen                | 28        | 0.43%   |
| Caen                 | 28        | 0.43%   |
| Poitiers             | 24        | 0.37%   |
| Argenteuil           | 24        | 0.37%   |
| Cergy                | 23        | 0.35%   |
| Saint-Denis          | 22        | 0.34%   |
| Clermont-Ferrand     | 22        | 0.34%   |
| Tours                | 20        | 0.31%   |
| Toulon               | 20        | 0.31%   |
| Orléans             | 20        | 0.31%   |
| Nancy                | 20        | 0.31%   |
| La Rochelle          | 20        | 0.31%   |
| Aix-en-Provence      | 20        | 0.31%   |
| Versailles           | 19        | 0.29%   |
| Valenciennes         | 19        | 0.29%   |
| Palaiseau            | 19        | 0.29%   |
| Metz                 | 19        | 0.29%   |
| Ivry-sur-Seine       | 19        | 0.29%   |
| Dijon                | 19        | 0.29%   |
| Champs-sur-Marne     | 19        | 0.29%   |
| Perpignan            | 18        | 0.28%   |
| Le Mans              | 18        | 0.28%   |
| Colmar               | 18        | 0.28%   |
| Boulogne-Billancourt | 18        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1159      | 1587   | 15.8%   |
| WDC                         | 772       | 972    | 10.52%  |
| Seagate                     | 727       | 927    | 9.91%   |
| Toshiba                     | 592       | 734    | 8.07%   |
| SanDisk                     | 441       | 564    | 6.01%   |
| Crucial                     | 417       | 547    | 5.69%   |
| SK hynix                    | 382       | 463    | 5.21%   |
| Unknown                     | 371       | 489    | 5.06%   |
| Kingston                    | 333       | 396    | 4.54%   |
| HGST                        | 303       | 367    | 4.13%   |
| Micron Technology           | 239       | 277    | 3.26%   |
| Intel                       | 235       | 286    | 3.2%    |
| Hitachi                     | 213       | 245    | 2.9%    |
| KIOXIA                      | 111       | 130    | 1.51%   |
| PNY                         | 62        | 68     | 0.85%   |
| Apple                       | 62        | 78     | 0.85%   |
| China                       | 49        | 58     | 0.67%   |
| LDLC                        | 48        | 67     | 0.65%   |
| Transcend                   | 46        | 52     | 0.63%   |
| Fujitsu                     | 44        | 52     | 0.6%    |
| LITEON                      | 43        | 49     | 0.59%   |
| Phison                      | 38        | 41     | 0.52%   |
| SPCC                        | 37        | 43     | 0.5%    |
| JMicron Technology          | 36        | 39     | 0.49%   |
| Micron/Crucial Technology   | 33        | 37     | 0.45%   |
| Unknown                     | 30        | 31     | 0.41%   |
| Phison Electronics          | 26        | 27     | 0.35%   |
| LITEONIT                    | 26        | 30     | 0.35%   |
| Kingston Technology Company | 24        | 29     | 0.33%   |
| Corsair                     | 19        | 23     | 0.26%   |
| Silicon Motion              | 17        | 21     | 0.23%   |
| A-DATA Technology           | 17        | 23     | 0.23%   |
| Emtec                       | 16        | 18     | 0.22%   |
| SSSTC                       | 14        | 17     | 0.19%   |
| Netac                       | 12        | 14     | 0.16%   |
| BHT                         | 11        | 15     | 0.15%   |
| OCZ                         | 10        | 14     | 0.14%   |
| KingSpec                    | 10        | 12     | 0.14%   |
| ASMT                        | 10        | 12     | 0.14%   |
| YMTC                        | 9         | 10     | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                           | 111       | 1.46%   |
| Seagate ST1000LM035-1RK172 1TB                     | 109       | 1.43%   |
| Toshiba MQ01ABD100 1TB                             | 93        | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 86        | 1.13%   |
| Crucial CT500MX500SSD1 500GB                       | 73        | 0.96%   |
| Crucial CT240BX500SSD1 240GB                       | 73        | 0.96%   |
| Unknown MMC Card  32GB                             | 70        | 0.92%   |
| Toshiba MQ04ABF100 1TB                             | 67        | 0.88%   |
| Unknown MMC Card  64GB                             | 60        | 0.79%   |
| HGST HTS541010A9E680 1TB                           | 58        | 0.76%   |
| Samsung SSD 860 EVO 500GB                          | 56        | 0.74%   |
| Kingston SA400S37240G 240GB SSD                    | 50        | 0.66%   |
| SanDisk NVMe SSD Drive 512GB                       | 48        | 0.63%   |
| Seagate ST9500325AS 500GB                          | 42        | 0.55%   |
| Seagate ST500LT012-1DG142 500GB                    | 42        | 0.55%   |
| Crucial CT1000MX500SSD1 1TB                        | 39        | 0.51%   |
| Toshiba MQ01ABF050 500GB                           | 38        | 0.5%    |
| Samsung NVMe SSD Drive 512GB                       | 37        | 0.49%   |
| Samsung SSD 850 EVO 500GB                          | 35        | 0.46%   |
| Seagate ST1000LM048-2E7172 1TB                     | 34        | 0.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 34        | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 34        | 0.45%   |
| HGST HTS725050A7E630 500GB                         | 34        | 0.45%   |
| Samsung SSD 870 QVO 1TB                            | 33        | 0.43%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 32        | 0.42%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                     | 31        | 0.41%   |
| Unknown                                            | 30        | 0.39%   |
| Unknown MMC Card  128GB                            | 29        | 0.38%   |
| Crucial CT480BX500SSD1 480GB                       | 29        | 0.38%   |
| Seagate ST500LM021-1KJ152 500GB                    | 28        | 0.37%   |
| Kingston SA400S37480G 480GB SSD                    | 28        | 0.37%   |
| Samsung SSD 850 EVO 250GB                          | 27        | 0.35%   |
| Crucial CT120BX500SSD1 120GB                       | 27        | 0.35%   |
| Seagate ST1000LM049-2GH172 1TB                     | 26        | 0.34%   |
| Samsung SSD 980 1TB                                | 26        | 0.34%   |
| Toshiba NVMe SSD Drive 512GB                       | 25        | 0.33%   |
| Samsung SSD 860 EVO 1TB                            | 25        | 0.33%   |
| Intel SSDPEKNW512G8 512GB                          | 25        | 0.33%   |
| Intel SSDPEKNU512GZ 512GB                          | 25        | 0.33%   |
| HGST HTS545050A7E680 500GB                         | 25        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 718       | 909    | 31.2%   |
| WDC                 | 513       | 655    | 22.29%  |
| Toshiba             | 407       | 490    | 17.69%  |
| HGST                | 303       | 367    | 13.17%  |
| Hitachi             | 213       | 245    | 9.26%   |
| Fujitsu             | 43        | 51     | 1.87%   |
| Samsung Electronics | 40        | 62     | 1.74%   |
| Unknown             | 15        | 16     | 0.65%   |
| JMicron Technology  | 10        | 11     | 0.43%   |
| Apple               | 7         | 7      | 0.3%    |
| IBM/Hitachi         | 5         | 6      | 0.22%   |
| HGST HTS            | 4         | 6      | 0.17%   |
| Inateck             | 3         | 3      | 0.13%   |
| ASMT                | 3         | 5      | 0.13%   |
| TO Exter            | 2         | 2      | 0.09%   |
| LaCie               | 2         | 2      | 0.09%   |
| External            | 2         | 2      | 0.09%   |
| XrayDisk            | 1         | 1      | 0.04%   |
| USB3.0              | 1         | 1      | 0.04%   |
| USB                 | 1         | 1      | 0.04%   |
| StoreJet            | 1         | 1      | 0.04%   |
| SILICONMOTION       | 1         | 1      | 0.04%   |
| Magnetic Data       | 1         | 1      | 0.04%   |
| KESU                | 1         | 1      | 0.04%   |
| Intenso             | 1         | 1      | 0.04%   |
| Generic-            | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |
| APPLE HD            | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 526       | 699    | 22.84%  |
| Crucial             | 375       | 494    | 16.28%  |
| SanDisk             | 260       | 336    | 11.29%  |
| Kingston            | 242       | 288    | 10.51%  |
| Micron Technology   | 78        | 102    | 3.39%   |
| SK hynix            | 77        | 97     | 3.34%   |
| WDC                 | 60        | 67     | 2.61%   |
| Intel               | 57        | 60     | 2.48%   |
| PNY                 | 54        | 59     | 2.34%   |
| China               | 48        | 57     | 2.08%   |
| Apple               | 47        | 60     | 2.04%   |
| Transcend           | 44        | 50     | 1.91%   |
| Toshiba             | 41        | 48     | 1.78%   |
| LDLC                | 40        | 56     | 1.74%   |
| LITEON              | 37        | 41     | 1.61%   |
| SPCC                | 33        | 39     | 1.43%   |
| LITEONIT            | 26        | 30     | 1.13%   |
| Emtec               | 15        | 17     | 0.65%   |
| A-DATA Technology   | 12        | 18     | 0.52%   |
| BHT                 | 11        | 15     | 0.48%   |
| OCZ                 | 10        | 14     | 0.43%   |
| Netac               | 10        | 12     | 0.43%   |
| KingSpec            | 10        | 12     | 0.43%   |
| JMicron Technology  | 10        | 11     | 0.43%   |
| Corsair             | 10        | 13     | 0.43%   |
| Teclast             | 9         | 11     | 0.39%   |
| Dogfish             | 9         | 12     | 0.39%   |
| Patriot             | 7         | 7      | 0.3%    |
| ASMT                | 7         | 7      | 0.3%    |
| Unknown             | 7         | 7      | 0.3%    |
| SABRENT             | 6         | 6      | 0.26%   |
| Plextor             | 6         | 16     | 0.26%   |
| KingDian            | 6         | 9      | 0.26%   |
| Intenso             | 6         | 8      | 0.26%   |
| Verbatim            | 5         | 5      | 0.22%   |
| Fanxiang            | 5         | 6      | 0.22%   |
| Lexar               | 4         | 4      | 0.17%   |
| Gigabyte Technology | 4         | 5      | 0.17%   |
| ASMedia             | 4         | 4      | 0.17%   |
| Unknown             | 3         | 4      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2223      | 2850   | 31.86%  |
| NVMe    | 2174      | 2857   | 31.16%  |
| SSD     | 2121      | 2907   | 30.4%   |
| MMC     | 379       | 510    | 5.43%   |
| Unknown | 81        | 91     | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3855      | 5544   | 57.99%  |
| NVMe | 2173      | 2847   | 32.69%  |
| MMC  | 379       | 510    | 5.7%    |
| SAS  | 241       | 314    | 3.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2772      | 3738   | 63.94%  |
| 0.51-1.0   | 1411      | 1826   | 32.55%  |
| 1.01-2.0   | 124       | 160    | 2.86%   |
| 3.01-4.0   | 14        | 16     | 0.32%   |
| 4.01-10.0  | 10        | 12     | 0.23%   |
| 2.01-3.0   | 2         | 2      | 0.05%   |
| 10.01-20.0 | 2         | 3      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1717      | 27.49%  |
| 101-250        | 1673      | 26.79%  |
| 501-1000       | 1073      | 17.18%  |
| 1-20           | 471       | 7.54%   |
| 51-100         | 377       | 6.04%   |
| 1001-2000      | 324       | 5.19%   |
| 21-50          | 255       | 4.08%   |
| Unknown        | 158       | 2.53%   |
| More than 3000 | 100       | 1.6%    |
| 2001-3000      | 97        | 1.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2462      | 37.95%  |
| 21-50          | 1178      | 18.16%  |
| 101-250        | 928       | 14.3%   |
| 51-100         | 817       | 12.59%  |
| 251-500        | 514       | 7.92%   |
| 501-1000       | 283       | 4.36%   |
| Unknown        | 158       | 2.44%   |
| 1001-2000      | 88        | 1.36%   |
| 2001-3000      | 36        | 0.55%   |
| More than 3000 | 21        | 0.32%   |
| 0              | 3         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                         | 22        | 26     | 4.01%   |
| HGST HTS541010A9E680 1TB                         | 16        | 17     | 2.92%   |
| Seagate ST9500325AS 500GB                        | 15        | 16     | 2.74%   |
| Seagate ST500LM021-1KJ152 500GB                  | 13        | 15     | 2.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 13        | 14     | 2.37%   |
| Toshiba MQ01ABD100 1TB                           | 10        | 12     | 1.82%   |
| Seagate ST500LT012-1DG142 500GB                  | 9         | 9      | 1.64%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 7         | 7      | 1.28%   |
| Toshiba MQ01ABD050 500GB                         | 7         | 7      | 1.28%   |
| Seagate ST1000LM035-1RK172 1TB                   | 7         | 7      | 1.28%   |
| HGST HTS725050A7E630 500GB                       | 7         | 7      | 1.28%   |
| Toshiba MQ01ABF050 500GB                         | 6         | 6      | 1.09%   |
| Hitachi HTS547575A9E384 752GB                    | 6         | 6      | 1.09%   |
| HGST HTS545050A7E380 500GB                       | 6         | 6      | 1.09%   |
| Seagate ST320LT007-9ZV142 320GB                  | 5         | 6      | 0.91%   |
| Hitachi HTS727575A9E364 752GB                    | 5         | 5      | 0.91%   |
| Hitachi HTS545050A7E380 500GB                    | 5         | 5      | 0.91%   |
| HGST HTS545050A7E680 500GB                       | 5         | 6      | 0.91%   |
| Toshiba MK3265GSX 320GB                          | 4         | 5      | 0.73%   |
| SK hynix HFS256G39TND-N210A 256GB SSD            | 4         | 4      | 0.73%   |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 4         | 4      | 0.73%   |
| Kingston RBU-SMSM151S324GD 24GB SSD              | 4         | 4      | 0.73%   |
| Hitachi HTS547550A9E384 500GB                    | 4         | 4      | 0.73%   |
| Hitachi HTS545050B9A300 500GB                    | 4         | 4      | 0.73%   |
| Hitachi HTS543232A7A384 320GB                    | 4         | 6      | 0.73%   |
| HGST HTS541075A9E680 752GB                       | 4         | 4      | 0.73%   |
| Crucial CT525MX300SSD1 528GB                     | 4         | 4      | 0.73%   |
| Toshiba MQ04ABF100 1TB                           | 3         | 3      | 0.55%   |
| Toshiba MQ01ACF050 500GB                         | 3         | 3      | 0.55%   |
| Toshiba MK7575GSX 752GB                          | 3         | 3      | 0.55%   |
| Toshiba MK5055GSX 500GB                          | 3         | 3      | 0.55%   |
| Toshiba MK3261GSYN 320GB                         | 3         | 3      | 0.55%   |
| SK hynix PC711 HFS512GDE9X073N 512GB             | 3         | 4      | 0.55%   |
| Seagate ST9500420AS 500GB                        | 3         | 3      | 0.55%   |
| Seagate ST9320325AS 320GB                        | 3         | 3      | 0.55%   |
| Seagate ST9250827AS 250GB                        | 3         | 4      | 0.55%   |
| Seagate ST1000LM048-2E7172 1TB                   | 3         | 3      | 0.55%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 3         | 3      | 0.55%   |
| Hitachi HTS725032A9A364 320GB                    | 3         | 3      | 0.55%   |
| Hitachi HTS723232A7A364 320GB                    | 3         | 3      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 112       | 124    | 20.48%  |
| Toshiba             | 72        | 76     | 13.16%  |
| WDC                 | 67        | 70     | 12.25%  |
| HGST                | 66        | 73     | 12.07%  |
| Hitachi             | 60        | 62     | 10.97%  |
| Samsung Electronics | 27        | 30     | 4.94%   |
| SK hynix            | 23        | 27     | 4.2%    |
| SanDisk             | 21        | 27     | 3.84%   |
| Crucial             | 17        | 18     | 3.11%   |
| Kingston            | 16        | 16     | 2.93%   |
| Intel               | 14        | 15     | 2.56%   |
| Fujitsu             | 8         | 8      | 1.46%   |
| Micron Technology   | 5         | 5      | 0.91%   |
| LITEONIT            | 3         | 3      | 0.55%   |
| LDLC                | 3         | 5      | 0.55%   |
| Netac               | 2         | 2      | 0.37%   |
| LITEON              | 2         | 2      | 0.37%   |
| JMicron Technology  | 2         | 2      | 0.37%   |
| Intenso             | 2         | 3      | 0.37%   |
| Dogfish             | 2         | 2      | 0.37%   |
| Corsair             | 2         | 3      | 0.37%   |
| China               | 2         | 2      | 0.37%   |
| Apple               | 2         | 3      | 0.37%   |
| Apacer              | 2         | 2      | 0.37%   |
| A-DATA Technology   | 2         | 2      | 0.37%   |
| Unknown             | 1         | 1      | 0.18%   |
| Transcend           | 1         | 1      | 0.18%   |
| TakeMS              | 1         | 1      | 0.18%   |
| SSSTC               | 1         | 1      | 0.18%   |
| SPCC                | 1         | 1      | 0.18%   |
| Phison              | 1         | 1      | 0.18%   |
| OCZ                 | 1         | 1      | 0.18%   |
| Magnetic Data       | 1         | 1      | 0.18%   |
| KingSpec            | 1         | 1      | 0.18%   |
| IBM/Hitachi         | 1         | 1      | 0.18%   |
| Hypertec            | 1         | 1      | 0.18%   |
| ASMT                | 1         | 1      | 0.18%   |
| ASENNO              | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 112       | 124    | 28.87%  |
| Toshiba             | 68        | 72     | 17.53%  |
| HGST                | 66        | 73     | 17.01%  |
| WDC                 | 62        | 65     | 15.98%  |
| Hitachi             | 60        | 62     | 15.46%  |
| Samsung Electronics | 9         | 9      | 2.32%   |
| Fujitsu             | 8         | 8      | 2.06%   |
| Unknown             | 1         | 1      | 0.26%   |
| Magnetic Data       | 1         | 1      | 0.26%   |
| IBM/Hitachi         | 1         | 1      | 0.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 385       | 416    | 71.03%  |
| SSD     | 137       | 155    | 25.28%  |
| NVMe    | 18        | 22     | 3.32%   |
| Unknown | 2         | 2      | 0.37%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB          | 2         | 3      | 11.11%  |
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 11.11%  |
| WDC WD5000BEVT-35A0RT0 500GB          | 1         | 1      | 5.56%   |
| WDC WD10SPZX-21Z10T0 1TB              | 1         | 1      | 5.56%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 5.56%   |
| Toshiba MQ02ABF050H 500GB             | 1         | 1      | 5.56%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 5.56%   |
| Toshiba MK5055GSX 500GB               | 1         | 1      | 5.56%   |
| Toshiba MK3259GSXP 320GB              | 1         | 2      | 5.56%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 5.56%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 980 500GB     | 1         | 1      | 5.56%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 5.56%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 5.56%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 5.56%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 33.33%  |
| Toshiba             | 6         | 7      | 33.33%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| HGST                | 2         | 2      | 11.11%  |
| SK hynix            | 1         | 1      | 5.56%   |
| Seagate             | 1         | 1      | 5.56%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3042      | 4108   | 47.58%  |
| Detected | 2803      | 4489   | 43.84%  |
| Malfunc  | 528       | 595    | 8.26%   |
| Failed   | 18        | 20     | 0.28%   |
| Fixed    | 2         | 2      | 0.03%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 4158      | 58.95%  |
| Samsung Electronics                     | 646       | 9.16%   |
| AMD                                     | 642       | 9.1%    |
| SanDisk                                 | 363       | 5.15%   |
| SK hynix                                | 295       | 4.18%   |
| Toshiba America Info Systems            | 165       | 2.34%   |
| Micron Technology                       | 163       | 2.31%   |
| Kingston Technology Company             | 114       | 1.62%   |
| KIOXIA                                  | 102       | 1.45%   |
| Phison Electronics                      | 78        | 1.11%   |
| Micron/Crucial Technology               | 74        | 1.05%   |
| Nvidia                                  | 63        | 0.89%   |
| Silicon Motion                          | 22        | 0.31%   |
| Union Memory (Shenzhen)                 | 18        | 0.26%   |
| Marvell Technology Group                | 16        | 0.23%   |
| Lite-On Technology                      | 16        | 0.23%   |
| Solid State Storage Technology          | 15        | 0.21%   |
| Silicon Integrated Systems [SiS]        | 15        | 0.21%   |
| JMicron Technology                      | 12        | 0.17%   |
| Yangtze Memory Technologies             | 11        | 0.16%   |
| Apple                                   | 8         | 0.11%   |
| ADATA Technology                        | 7         | 0.1%    |
| Lenovo                                  | 6         | 0.09%   |
| Solidigm                                | 5         | 0.07%   |
| Shenzhen Longsys Electronics            | 5         | 0.07%   |
| O2 Micro                                | 5         | 0.07%   |
| ASMedia Technology                      | 5         | 0.07%   |
| Seagate Technology                      | 4         | 0.06%   |
| Realtek Semiconductor                   | 4         | 0.06%   |
| MAXIO Technology (Hangzhou)             | 4         | 0.06%   |
| VIA Technologies                        | 3         | 0.04%   |
| Silicon Image                           | 3         | 0.04%   |
| Biwin Storage Technology                | 3         | 0.04%   |
| ULi Electronics                         | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |
| INNOGRIT                                | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 527       | 7%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 415       | 5.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 415       | 5.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 334       | 4.44%   |
| Intel Volume Management Device NVMe RAID Controller                              | 267       | 3.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 261       | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 258       | 3.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 228       | 3.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 222       | 2.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 210       | 2.79%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 195       | 2.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 193       | 2.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 188       | 2.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 148       | 1.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 142       | 1.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 109       | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 109       | 1.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 107       | 1.42%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 101       | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 98        | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 92        | 1.22%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 89        | 1.18%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 80        | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 80        | 1.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 78        | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                            | 74        | 0.98%   |
| Intel Tiger Lake-LP SATA Controller                                              | 73        | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 72        | 0.96%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 66        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 65        | 0.86%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 60        | 0.8%    |
| Intel SSD 660P Series                                                            | 59        | 0.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 57        | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 57        | 0.76%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 56        | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 53        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 51        | 0.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 48        | 0.64%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 46        | 0.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 42        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 4076      | 56.09%  |
| NVMe | 2190      | 30.14%  |
| RAID | 636       | 8.75%   |
| IDE  | 365       | 5.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 4934      | 82.95%  |
| AMD    | 1011      | 17%     |
| ARM    | 3         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 114       | 1.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 80        | 1.34%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 78        | 1.31%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 75        | 1.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 75        | 1.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 73        | 1.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 65        | 1.09%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 60        | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 59        | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 59        | 0.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 59        | 0.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 59        | 0.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 58        | 0.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 56        | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 56        | 0.94%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 55        | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 54        | 0.91%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 53        | 0.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 53        | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 50        | 0.84%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 46        | 0.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 45        | 0.76%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 45        | 0.76%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 43        | 0.72%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 42        | 0.71%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 42        | 0.71%   |
| Intel 12th Gen Core i7-12700H                 | 40        | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 39        | 0.66%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 39        | 0.66%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 39        | 0.66%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 38        | 0.64%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 35        | 0.59%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 34        | 0.57%   |
| AMD Custom APU 0405                           | 34        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 33        | 0.55%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 33        | 0.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 33        | 0.55%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 31        | 0.52%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 31        | 0.52%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 30        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1409      | 23.68%  |
| Intel Core i7           | 1211      | 20.35%  |
| Other                   | 674       | 11.33%  |
| Intel Core i3           | 508       | 8.54%   |
| Intel Celeron           | 339       | 5.7%    |
| Intel Core 2 Duo        | 296       | 4.97%   |
| AMD Ryzen 5             | 224       | 3.76%   |
| AMD Ryzen 7             | 214       | 3.6%    |
| Intel Pentium           | 159       | 2.67%   |
| Intel Atom              | 113       | 1.9%    |
| AMD E1                  | 63        | 1.06%   |
| Intel Pentium Dual-Core | 62        | 1.04%   |
| AMD A4                  | 47        | 0.79%   |
| AMD Ryzen 7 PRO         | 42        | 0.71%   |
| AMD E2                  | 40        | 0.67%   |
| AMD Ryzen 9             | 38        | 0.64%   |
| Intel Pentium Dual      | 37        | 0.62%   |
| AMD A6                  | 36        | 0.6%    |
| AMD E                   | 33        | 0.55%   |
| Intel Genuine           | 32        | 0.54%   |
| Intel Core i9           | 31        | 0.52%   |
| Intel Core 2            | 30        | 0.5%    |
| AMD Ryzen 5 PRO         | 30        | 0.5%    |
| AMD A8                  | 23        | 0.39%   |
| AMD Ryzen 3             | 22        | 0.37%   |
| Intel Pentium Silver    | 19        | 0.32%   |
| Intel Xeon              | 16        | 0.27%   |
| AMD Athlon II           | 16        | 0.27%   |
| AMD Athlon              | 16        | 0.27%   |
| Intel Celeron Dual-Core | 15        | 0.25%   |
| Intel Pentium M         | 12        | 0.2%    |
| AMD Athlon X2           | 12        | 0.2%    |
| Intel Core m3           | 10        | 0.17%   |
| AMD Turion 64 X2 Mobile | 10        | 0.17%   |
| AMD A12                 | 9         | 0.15%   |
| AMD A10                 | 9         | 0.15%   |
| Intel Celeron M         | 8         | 0.13%   |
| AMD Athlon II Dual-Core | 8         | 0.13%   |
| AMD Athlon 64 X2        | 7         | 0.12%   |
| AMD C-60                | 6         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2860      | 48.06%  |
| 4       | 1937      | 32.55%  |
| 6       | 445       | 7.48%   |
| 8       | 376       | 6.32%   |
| 1       | 123       | 2.07%   |
| 14      | 77        | 1.29%   |
| 10      | 58        | 0.97%   |
| 12      | 56        | 0.94%   |
| Unknown | 9         | 0.15%   |
| 24      | 4         | 0.07%   |
| 16      | 4         | 0.07%   |
| 5       | 1         | 0.02%   |
| 3       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5945      | 99.93%  |
| 2      | 4         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4348      | 72.99%  |
| 1       | 1599      | 26.84%  |
| Unknown | 9         | 0.15%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5858      | 98.34%  |
| Unknown        | 49        | 0.82%   |
| 32-bit         | 48        | 0.81%   |
| 64-bit         | 2         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1622      | 26.25%  |
| 0x306a9    | 329       | 5.32%   |
| 0x206a7    | 303       | 4.9%    |
| 0x806c1    | 219       | 3.54%   |
| 0x806ec    | 202       | 3.27%   |
| 0x1067a    | 198       | 3.2%    |
| 0x906ea    | 184       | 2.98%   |
| 0x406e3    | 177       | 2.86%   |
| 0x40651    | 167       | 2.7%    |
| 0x306d4    | 160       | 2.59%   |
| 0x306c3    | 157       | 2.54%   |
| 0x806ea    | 153       | 2.48%   |
| 0x806e9    | 127       | 2.06%   |
| 0x20655    | 127       | 2.06%   |
| 0x6fd      | 100       | 1.62%   |
| 0x506e3    | 89        | 1.44%   |
| 0xa0652    | 86        | 1.39%   |
| 0x906e9    | 75        | 1.21%   |
| 0x08600106 | 75        | 1.21%   |
| 0x08108109 | 74        | 1.2%    |
| 0x30678    | 67        | 1.08%   |
| 0x0a50000c | 66        | 1.07%   |
| 0x906a3    | 63        | 1.02%   |
| 0x806d1    | 61        | 0.99%   |
| 0x10676    | 56        | 0.91%   |
| 0x706e5    | 52        | 0.84%   |
| 0x08608103 | 51        | 0.83%   |
| 0x406c4    | 50        | 0.81%   |
| 0x07030105 | 48        | 0.78%   |
| 0x806eb    | 46        | 0.74%   |
| 0x506c9    | 44        | 0.71%   |
| 0x08108102 | 44        | 0.71%   |
| 0x706a8    | 43        | 0.7%    |
| 0x406c3    | 43        | 0.7%    |
| 0x706a1    | 42        | 0.68%   |
| 0x05000119 | 41        | 0.66%   |
| 0x20652    | 40        | 0.65%   |
| 0x06006705 | 40        | 0.65%   |
| 0x906ed    | 35        | 0.57%   |
| 0x0700010f | 30        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1107      | 18.58%  |
| Haswell          | 460       | 7.72%   |
| IvyBridge        | 413       | 6.93%   |
| SandyBridge      | 370       | 6.21%   |
| Skylake          | 366       | 6.14%   |
| Penryn           | 305       | 5.12%   |
| TigerLake        | 303       | 5.09%   |
| Unknown          | 243       | 4.08%   |
| Silvermont       | 218       | 3.66%   |
| Broadwell        | 213       | 3.58%   |
| Westmere         | 212       | 3.56%   |
| Core             | 187       | 3.14%   |
| Alderlake Hybrid | 160       | 2.69%   |
| Zen 2            | 157       | 2.64%   |
| IceLake          | 146       | 2.45%   |
| Zen+             | 134       | 2.25%   |
| Zen 3            | 131       | 2.2%    |
| CometLake        | 125       | 2.1%    |
| Goldmont plus    | 111       | 1.86%   |
| Puma             | 76        | 1.28%   |
| Excavator        | 75        | 1.26%   |
| Bobcat           | 74        | 1.24%   |
| Goldmont         | 61        | 1.02%   |
| Bonnell          | 45        | 0.76%   |
| Jaguar           | 44        | 0.74%   |
| Zen              | 41        | 0.69%   |
| K10              | 38        | 0.64%   |
| K8 Hammer        | 28        | 0.47%   |
| P6               | 27        | 0.45%   |
| Nehalem          | 22        | 0.37%   |
| K8 & K10 hybrid  | 19        | 0.32%   |
| Piledriver       | 17        | 0.29%   |
| K10 Llano        | 14        | 0.24%   |
| Tremont          | 8         | 0.13%   |
| NetBurst         | 3         | 0.05%   |
| Steamroller      | 2         | 0.03%   |
| K6               | 1         | 0.02%   |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4439      | 57.81%  |
| Nvidia                           | 1863      | 24.26%  |
| AMD                              | 1365      | 17.78%  |
| Silicon Integrated Systems [SiS] | 10        | 0.13%   |
| VIA Technologies                 | 2         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 382       | 4.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 331       | 4.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 280       | 3.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 256       | 3.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 223       | 2.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 217       | 2.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 196       | 2.49%   |
| Intel HD Graphics 5500                                                                   | 189       | 2.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 185       | 2.35%   |
| Intel UHD Graphics 620                                                                   | 182       | 2.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 175       | 2.22%   |
| Intel HD Graphics 620                                                                    | 168       | 2.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 157       | 1.99%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 153       | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 138       | 1.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 130       | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 112       | 1.42%   |
| Intel HD Graphics 530                                                                    | 111       | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 107       | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 106       | 1.34%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 102       | 1.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 96        | 1.22%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 95        | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 95        | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 91        | 1.15%   |
| Intel HD Graphics 630                                                                    | 91        | 1.15%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 82        | 1.04%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 72        | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 72        | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 72        | 0.91%   |
| AMD Lucienne                                                                             | 67        | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 61        | 0.77%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 57        | 0.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 57        | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                                             | 50        | 0.63%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 49        | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 49        | 0.62%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 49        | 0.62%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 48        | 0.61%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 48        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2812      | 47.12%  |
| Intel + Nvidia           | 1395      | 23.37%  |
| 1 x AMD                  | 940       | 15.75%  |
| 1 x Nvidia               | 343       | 5.75%   |
| Intel + AMD              | 213       | 3.57%   |
| AMD + Nvidia             | 117       | 1.96%   |
| 2 x AMD                  | 95        | 1.59%   |
| 2 x Intel                | 22        | 0.37%   |
| 1 x SiS                  | 10        | 0.17%   |
| 2 x Nvidia               | 9         | 0.15%   |
| Other                    | 8         | 0.13%   |
| 1 x VIA                  | 2         | 0.03%   |
| Intel + 2 x Nvidia       | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5081      | 84.5%   |
| Proprietary | 786       | 13.07%  |
| Unknown     | 146       | 2.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3811      | 62.63%  |
| 0.01-0.5   | 789       | 12.97%  |
| 1.01-2.0   | 634       | 10.42%  |
| 0.51-1.0   | 352       | 5.78%   |
| 3.01-4.0   | 323       | 5.31%   |
| 5.01-6.0   | 94        | 1.54%   |
| 7.01-8.0   | 53        | 0.87%   |
| 2.01-3.0   | 25        | 0.41%   |
| 8.01-16.0  | 4         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1351      | 19.84%  |
| Chimei Innolux          | 927       | 13.62%  |
| LG Display              | 857       | 12.59%  |
| BOE                     | 856       | 12.57%  |
| Samsung Electronics     | 699       | 10.27%  |
| Sharp                   | 228       | 3.35%   |
| Dell                    | 194       | 2.85%   |
| Chi Mei Optoelectronics | 172       | 2.53%   |
| Iiyama                  | 135       | 1.98%   |
| Apple                   | 130       | 1.91%   |
| Lenovo                  | 106       | 1.56%   |
| PANDA                   | 93        | 1.37%   |
| Hewlett-Packard         | 90        | 1.32%   |
| Goldstar                | 85        | 1.25%   |
| Acer                    | 81        | 1.19%   |
| LG Philips              | 79        | 1.16%   |
| InfoVision              | 77        | 1.13%   |
| BenQ                    | 54        | 0.79%   |
| Ancor Communications    | 54        | 0.79%   |
| Philips                 | 52        | 0.76%   |
| AOC                     | 51        | 0.75%   |
| ViewSonic               | 37        | 0.54%   |
| CSO                     | 29        | 0.43%   |
| ASUSTek Computer        | 27        | 0.4%    |
| CPT                     | 21        | 0.31%   |
| Sony                    | 20        | 0.29%   |
| Valve                   | 19        | 0.28%   |
| HannStar                | 16        | 0.24%   |
| Fujitsu Siemens         | 14        | 0.21%   |
| Toshiba                 | 12        | 0.18%   |
| Analogix                | 11        | 0.16%   |
| Vestel Elektronik       | 10        | 0.15%   |
| Seiko/Epson             | 9         | 0.13%   |
| LGD                     | 9         | 0.13%   |
| Unknown                 | 8         | 0.12%   |
| TMX                     | 8         | 0.12%   |
| Panasonic               | 7         | 0.1%    |
| MSI                     | 6         | 0.09%   |
| JDZ                     | 6         | 0.09%   |
| InnoLux Display         | 6         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 50        | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 39        | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 38        | 0.55%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 38        | 0.55%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 37        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 32        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 30        | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 30        | 0.44%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 30        | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 28        | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 28        | 0.41%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 27        | 0.39%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 26        | 0.38%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 25        | 0.36%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 25        | 0.36%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 24        | 0.35%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 23        | 0.33%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 23        | 0.33%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 22        | 0.32%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 22        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 22        | 0.32%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch             | 22        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 21        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 21        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 20        | 0.29%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 20        | 0.29%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch              | 19        | 0.28%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 19        | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 19        | 0.28%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 18        | 0.26%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 18        | 0.26%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 18        | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 18        | 0.26%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 18        | 0.26%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 18        | 0.26%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 18        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 17        | 0.25%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 17        | 0.25%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 17        | 0.25%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 17        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2766      | 43.72%  |
| 1366x768 (WXGA)    | 1497      | 23.66%  |
| 1600x900 (HD+)     | 573       | 9.06%   |
| 3840x2160 (4K)     | 220       | 3.48%   |
| 1280x800 (WXGA)    | 212       | 3.35%   |
| 1920x1200 (WUXGA)  | 189       | 2.99%   |
| 2560x1440 (QHD)    | 166       | 2.62%   |
| 1440x900 (WXGA+)   | 154       | 2.43%   |
| 1680x1050 (WSXGA+) | 73        | 1.15%   |
| 2560x1600          | 54        | 0.85%   |
| 2880x1800          | 41        | 0.65%   |
| 1280x1024 (SXGA)   | 37        | 0.58%   |
| 3440x1440          | 36        | 0.57%   |
| 1024x600           | 36        | 0.57%   |
| 800x1280           | 29        | 0.46%   |
| 3840x2400          | 27        | 0.43%   |
| 2160x1440          | 21        | 0.33%   |
| 2560x1080          | 16        | 0.25%   |
| 3200x1800 (QHD+)   | 15        | 0.24%   |
| Unknown            | 12        | 0.19%   |
| 2256x1504          | 11        | 0.17%   |
| 1360x768           | 11        | 0.17%   |
| 1920x540           | 10        | 0.16%   |
| 3840x1080          | 9         | 0.14%   |
| 3000x2000          | 9         | 0.14%   |
| 1600x1200          | 9         | 0.14%   |
| 3072x1920          | 8         | 0.13%   |
| 2880x1620          | 8         | 0.13%   |
| 1680x945           | 8         | 0.13%   |
| 1024x768 (XGA)     | 7         | 0.11%   |
| 2520x1680          | 6         | 0.09%   |
| 2288x1287          | 5         | 0.08%   |
| 1920x1280          | 5         | 0.08%   |
| 3840x1200          | 4         | 0.06%   |
| 3456x2160          | 4         | 0.06%   |
| 3200x2000          | 4         | 0.06%   |
| 1920x515           | 4         | 0.06%   |
| 1400x1050          | 4         | 0.06%   |
| 2240x1400          | 3         | 0.05%   |
| 5760x2160          | 2         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2512      | 36.96%  |
| 13      | 939       | 13.81%  |
| 17      | 919       | 13.52%  |
| 14      | 660       | 9.71%   |
| 24      | 291       | 4.28%   |
| 27      | 232       | 3.41%   |
| 23      | 200       | 2.94%   |
| 12      | 183       | 2.69%   |
| 21      | 129       | 1.9%    |
| 16      | 104       | 1.53%   |
| 11      | 84        | 1.24%   |
| Unknown | 79        | 1.16%   |
| 18      | 52        | 0.77%   |
| 10      | 50        | 0.74%   |
| 34      | 48        | 0.71%   |
| 22      | 48        | 0.71%   |
| 19      | 41        | 0.6%    |
| 31      | 38        | 0.56%   |
| 20      | 22        | 0.32%   |
| 7       | 19        | 0.28%   |
| 84      | 18        | 0.26%   |
| 72      | 16        | 0.24%   |
| 25      | 11        | 0.16%   |
| 3       | 11        | 0.16%   |
| 32      | 10        | 0.15%   |
| 40      | 9         | 0.13%   |
| 26      | 9         | 0.13%   |
| 54      | 8         | 0.12%   |
| 52      | 6         | 0.09%   |
| 33      | 6         | 0.09%   |
| 49      | 5         | 0.07%   |
| 39      | 5         | 0.07%   |
| 142     | 3         | 0.04%   |
| 65      | 3         | 0.04%   |
| 48      | 3         | 0.04%   |
| 43      | 3         | 0.04%   |
| 86      | 2         | 0.03%   |
| 50      | 2         | 0.03%   |
| 46      | 2         | 0.03%   |
| 36      | 2         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3587      | 53.36%  |
| 351-400        | 1035      | 15.4%   |
| 201-300        | 838       | 12.47%  |
| 501-600        | 666       | 9.91%   |
| 401-500        | 268       | 3.99%   |
| Unknown        | 79        | 1.18%   |
| 701-800        | 65        | 0.97%   |
| 601-700        | 60        | 0.89%   |
| 1501-2000      | 35        | 0.52%   |
| 1001-1500      | 34        | 0.51%   |
| 1-100          | 29        | 0.43%   |
| 801-900        | 19        | 0.28%   |
| More than 2000 | 3         | 0.04%   |
| 101-200        | 3         | 0.04%   |
| 901-1000       | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4922      | 82.51%  |
| 16/10   | 753       | 12.62%  |
| 3/2     | 66        | 1.11%   |
| 21/9    | 54        | 0.91%   |
| Unknown | 49        | 0.82%   |
| 5/4     | 39        | 0.65%   |
| 4/3     | 28        | 0.47%   |
| 0.67    | 18        | 0.3%    |
| 6/5     | 11        | 0.18%   |
| 32/9    | 8         | 0.13%   |
| 3.20    | 4         | 0.07%   |
| 3.73    | 3         | 0.05%   |
| 1.00    | 3         | 0.05%   |
| 0.56    | 3         | 0.05%   |
| 0.62    | 2         | 0.03%   |
| 3.88    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2511      | 37.06%  |
| 81-90          | 1171      | 17.28%  |
| 121-130        | 766       | 11.3%   |
| 201-250        | 539       | 7.95%   |
| 71-80          | 427       | 6.3%    |
| 301-350        | 239       | 3.53%   |
| 61-70          | 171       | 2.52%   |
| 131-140        | 143       | 2.11%   |
| 351-500        | 105       | 1.55%   |
| 151-200        | 100       | 1.48%   |
| 111-120        | 91        | 1.34%   |
| 251-300        | 88        | 1.3%    |
| 51-60          | 84        | 1.24%   |
| Unknown        | 79        | 1.17%   |
| 141-150        | 63        | 0.93%   |
| More than 1000 | 61        | 0.9%    |
| 41-50          | 51        | 0.75%   |
| 1-40           | 32        | 0.47%   |
| 501-1000       | 30        | 0.44%   |
| 91-100         | 25        | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2621      | 39.46%  |
| 101-120       | 1985      | 29.89%  |
| 51-100        | 1164      | 17.52%  |
| 161-240       | 557       | 8.39%   |
| More than 240 | 186       | 2.8%    |
| Unknown       | 79        | 1.19%   |
| 1-50          | 50        | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4820      | 79.06%  |
| 2     | 977       | 16.02%  |
| 0     | 160       | 2.62%   |
| 3     | 127       | 2.08%   |
| 4     | 11        | 0.18%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3270      | 34.55%  |
| Realtek Semiconductor             | 3032      | 32.04%  |
| Qualcomm Atheros                  | 1345      | 14.21%  |
| Broadcom                          | 611       | 6.46%   |
| MediaTek                          | 154       | 1.63%   |
| Broadcom Limited                  | 130       | 1.37%   |
| Marvell Technology Group          | 113       | 1.19%   |
| Ralink                            | 91        | 0.96%   |
| ASIX Electronics                  | 86        | 0.91%   |
| Dell                              | 56        | 0.59%   |
| Samsung Electronics               | 44        | 0.46%   |
| Nvidia                            | 41        | 0.43%   |
| Xiaomi                            | 39        | 0.41%   |
| DisplayLink                       | 39        | 0.41%   |
| Ericsson Business Mobile Networks | 37        | 0.39%   |
| Sierra Wireless                   | 28        | 0.3%    |
| Qualcomm                          | 28        | 0.3%    |
| Lenovo                            | 27        | 0.29%   |
| TP-Link                           | 25        | 0.26%   |
| NetGear                           | 23        | 0.24%   |
| JMicron Technology                | 22        | 0.23%   |
| Ralink Technology                 | 21        | 0.22%   |
| Huawei Technologies               | 18        | 0.19%   |
| Hewlett-Packard                   | 16        | 0.17%   |
| Attansic Technology               | 15        | 0.16%   |
| OPPO Electronics                  | 14        | 0.15%   |
| Google                            | 13        | 0.14%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.13%   |
| D-Link                            | 11        | 0.12%   |
| Toshiba                           | 6         | 0.06%   |
| Fibocom                           | 6         | 0.06%   |
| Apple                             | 6         | 0.06%   |
| Qualcomm Atheros Communications   | 5         | 0.05%   |
| ICS Advent                        | 5         | 0.05%   |
| D-Link System                     | 5         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.04%   |
| ASUSTek Computer                  | 4         | 0.04%   |
| Arduino SA                        | 4         | 0.04%   |
| Aquantia                          | 4         | 0.04%   |
| VIA Technologies                  | 3         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1745      | 15.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 473       | 4.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 359       | 3.15%   |
| Intel Wi-Fi 6 AX200                                                    | 262       | 2.3%    |
| Intel Wireless 8265 / 8275                                             | 228       | 2%      |
| Intel Wi-Fi 6 AX201                                                    | 228       | 2%      |
| Intel Wireless 7265                                                    | 221       | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 217       | 1.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 194       | 1.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 193       | 1.69%   |
| Intel Wireless 8260                                                    | 186       | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 182       | 1.6%    |
| Intel Wireless 7260                                                    | 177       | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 170       | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 161       | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 151       | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 150       | 1.32%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 141       | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 134       | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 132       | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 130       | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 117       | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 111       | 0.97%   |
| Intel Wireless 3165                                                    | 106       | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 106       | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 102       | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                          | 95        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 89        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                          | 80        | 0.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 78        | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                                  | 78        | 0.68%   |
| Intel Ethernet Connection I219-LM                                      | 77        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 73        | 0.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 73        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                                  | 70        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 67        | 0.59%   |
| Intel WiFi Link 5100                                                   | 67        | 0.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 63        | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 62        | 0.54%   |
| Intel Ethernet Connection I218-LM                                      | 62        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3105      | 50.92%  |
| Qualcomm Atheros                      | 1107      | 18.15%  |
| Realtek Semiconductor                 | 900       | 14.76%  |
| Broadcom                              | 451       | 7.4%    |
| MediaTek                              | 147       | 2.41%   |
| Ralink                                | 91        | 1.49%   |
| Broadcom Limited                      | 90        | 1.48%   |
| Dell                                  | 30        | 0.49%   |
| Sierra Wireless                       | 28        | 0.46%   |
| Qualcomm                              | 22        | 0.36%   |
| TP-Link                               | 21        | 0.34%   |
| Ralink Technology                     | 21        | 0.34%   |
| NetGear                               | 20        | 0.33%   |
| D-Link                                | 10        | 0.16%   |
| Ericsson Business Mobile Networks     | 8         | 0.13%   |
| Hewlett-Packard                       | 6         | 0.1%    |
| Fibocom                               | 6         | 0.1%    |
| Qualcomm Atheros Communications       | 5         | 0.08%   |
| D-Link System                         | 5         | 0.08%   |
| ASUSTek Computer                      | 4         | 0.07%   |
| Microsoft                             | 3         | 0.05%   |
| Edimax Technology                     | 3         | 0.05%   |
| Belkin Components                     | 3         | 0.05%   |
| Guillemot                             | 2         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.03%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| ZyDAS                                 | 1         | 0.02%   |
| Texas Instruments                     | 1         | 0.02%   |
| Sagem                                 | 1         | 0.02%   |
| Qualcomm Technologies                 | 1         | 0.02%   |
| Memorex                               | 1         | 0.02%   |
| Fujitsu Siemens Computers             | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 262       | 4.28%   |
| Intel Wireless 8265 / 8275                                              | 228       | 3.72%   |
| Intel Wi-Fi 6 AX201                                                     | 228       | 3.72%   |
| Intel Wireless 7265                                                     | 221       | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 217       | 3.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 194       | 3.17%   |
| Intel Wireless 8260                                                     | 186       | 3.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 182       | 2.97%   |
| Intel Wireless 7260                                                     | 177       | 2.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 170       | 2.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 161       | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 151       | 2.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 150       | 2.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 141       | 2.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 134       | 2.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 132       | 2.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 130       | 2.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 117       | 1.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 111       | 1.81%   |
| Intel Wireless 3165                                                     | 106       | 1.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 106       | 1.73%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 102       | 1.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 95        | 1.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 89        | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 78        | 1.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 73        | 1.19%   |
| Intel WiFi Link 5100                                                    | 67        | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 63        | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 62        | 1.01%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 60        | 0.98%   |
| Intel Wireless 3160                                                     | 57        | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 56        | 0.91%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 55        | 0.9%    |
| Intel Centrino Wireless-N 2230                                          | 55        | 0.9%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 47        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 47        | 0.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 47        | 0.77%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 45        | 0.73%   |
| Intel Centrino Advanced-N 6235                                          | 44        | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 42        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2682      | 52.71%  |
| Intel                            | 1186      | 23.31%  |
| Qualcomm Atheros                 | 416       | 8.18%   |
| Broadcom                         | 227       | 4.46%   |
| Marvell Technology Group         | 113       | 2.22%   |
| ASIX Electronics                 | 86        | 1.69%   |
| Samsung Electronics              | 43        | 0.85%   |
| Broadcom Limited                 | 43        | 0.85%   |
| Nvidia                           | 41        | 0.81%   |
| Xiaomi                           | 39        | 0.77%   |
| DisplayLink                      | 39        | 0.77%   |
| Lenovo                           | 27        | 0.53%   |
| JMicron Technology               | 22        | 0.43%   |
| Attansic Technology              | 15        | 0.29%   |
| OPPO Electronics                 | 14        | 0.28%   |
| Google                           | 13        | 0.26%   |
| Silicon Integrated Systems [SiS] | 12        | 0.24%   |
| Huawei Technologies              | 12        | 0.24%   |
| MediaTek                         | 7         | 0.14%   |
| Qualcomm                         | 6         | 0.12%   |
| Apple                            | 6         | 0.12%   |
| ICS Advent                       | 5         | 0.1%    |
| TP-Link                          | 4         | 0.08%   |
| Aquantia                         | 4         | 0.08%   |
| NetGear                          | 3         | 0.06%   |
| Motorola PCS                     | 3         | 0.06%   |
| VIA Technologies                 | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.04%   |
| Microchip Technology             | 2         | 0.04%   |
| Linksys                          | 2         | 0.04%   |
| Hisense                          | 2         | 0.04%   |
| Hewlett-Packard                  | 2         | 0.04%   |
| Cypress Semiconductor            | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| T & A Mobile Phones              | 1         | 0.02%   |
| Davicom Semiconductor            | 1         | 0.02%   |
| D-Link                           | 1         | 0.02%   |
| Archos                           | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1745      | 33.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 473       | 9.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 359       | 6.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 193       | 3.75%   |
| ASIX AX88179 Gigabit Ethernet                                          | 80        | 1.56%   |
| Intel Ethernet Connection (4) I219-LM                                  | 78        | 1.52%   |
| Intel Ethernet Connection I219-LM                                      | 77        | 1.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 73        | 1.42%   |
| Intel Ethernet Connection (3) I218-LM                                  | 70        | 1.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 67        | 1.3%    |
| Intel Ethernet Connection I218-LM                                      | 62        | 1.21%   |
| Intel Ethernet Connection I217-LM                                      | 62        | 1.21%   |
| Intel 82577LM Gigabit Network Connection                               | 49        | 0.95%   |
| Intel Ethernet Connection I219-V                                       | 45        | 0.87%   |
| Intel 82567LM Gigabit Network Connection                               | 43        | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 41        | 0.8%    |
| Intel Ethernet Connection I217-V                                       | 40        | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 39        | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 38        | 0.74%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 37        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                  | 35        | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                   | 35        | 0.68%   |
| Intel Ethernet Connection (4) I219-V                                   | 35        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 33        | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 33        | 0.64%   |
| Intel Ethernet Connection (6) I219-LM                                  | 33        | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 31        | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 31        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                  | 30        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 29        | 0.56%   |
| Nvidia MCP79 Ethernet                                                  | 28        | 0.54%   |
| Intel Ethernet Connection (13) I219-V                                  | 28        | 0.54%   |
| Intel Ethernet Connection (13) I219-LM                                 | 28        | 0.54%   |
| Realtek Killer E2600 GbE Controller                                    | 27        | 0.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 27        | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 26        | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 25        | 0.49%   |
| Intel Ethernet Connection (14) I219-LM                                 | 25        | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 25        | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 24        | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5849      | 54.31%  |
| Ethernet | 4804      | 44.61%  |
| Modem    | 108       | 1%      |
| Unknown  | 9         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4685      | 74.01%  |
| Ethernet | 1645      | 25.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4257      | 71.46%  |
| 1     | 1557      | 26.14%  |
| 0     | 89        | 1.49%   |
| 3     | 54        | 0.91%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3672      | 59.67%  |
| Yes  | 2482      | 40.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2467      | 52.99%  |
| Realtek Semiconductor           | 385       | 8.27%   |
| IMC Networks                    | 361       | 7.75%   |
| Qualcomm Atheros Communications | 288       | 6.19%   |
| Broadcom                        | 234       | 5.03%   |
| Foxconn / Hon Hai               | 176       | 3.78%   |
| Lite-On Technology              | 159       | 3.41%   |
| Apple                           | 125       | 2.68%   |
| Dell                            | 99        | 2.13%   |
| Cambridge Silicon Radio         | 65        | 1.4%    |
| Realtek                         | 52        | 1.12%   |
| Toshiba                         | 48        | 1.03%   |
| Hewlett-Packard                 | 47        | 1.01%   |
| Ralink                          | 36        | 0.77%   |
| ASUSTek Computer                | 26        | 0.56%   |
| Ralink Technology               | 24        | 0.52%   |
| Foxconn International           | 14        | 0.3%    |
| Alps Electric                   | 14        | 0.3%    |
| MediaTek                        | 13        | 0.28%   |
| USI                             | 7         | 0.15%   |
| Chicony Electronics             | 7         | 0.15%   |
| TP-Link                         | 3         | 0.06%   |
| Syntek                          | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 923       | 19.82%  |
| Intel AX201 Bluetooth                               | 522       | 11.21%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 373       | 8.01%   |
| Realtek Bluetooth Radio                             | 269       | 5.78%   |
| Intel AX200 Bluetooth                               | 250       | 5.37%   |
| Intel Bluetooth Device                              | 179       | 3.84%   |
| IMC Networks Bluetooth Device                       | 122       | 2.62%   |
| Qualcomm Atheros  Bluetooth Device                  | 115       | 2.47%   |
| IMC Networks Bluetooth Radio                        | 106       | 2.28%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 86        | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 85        | 1.82%   |
| Apple Bluetooth Host Controller                     | 70        | 1.5%    |
| Foxconn / Hon Hai Bluetooth Device                  | 65        | 1.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 65        | 1.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 57        | 1.22%   |
| IMC Networks Wireless_Device                        | 57        | 1.22%   |
| Foxconn / Hon Hai Wireless_Device                   | 55        | 1.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 53        | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 53        | 1.14%   |
| Realtek Bluetooth Radio                             | 52        | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 49        | 1.05%   |
| Intel AX210 Bluetooth                               | 49        | 1.05%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 46        | 0.99%   |
| Dell DW375 Bluetooth Module                         | 44        | 0.94%   |
| Lite-On Bluetooth Device                            | 41        | 0.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 37        | 0.79%   |
| Ralink RT3290 Bluetooth                             | 36        | 0.77%   |
| Apple Bluetooth USB Host Controller                 | 35        | 0.75%   |
| Intel Wireless-AC 3168 Bluetooth                    | 33        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 32        | 0.69%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 31        | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 30        | 0.64%   |
| HP Broadcom 2070 Bluetooth Combo                    | 28        | 0.6%    |
| Broadcom BCM43142A0 Bluetooth Device                | 28        | 0.6%    |
| Realtek RTL8723B Bluetooth                          | 21        | 0.45%   |
| Dell BCM20702A0 Bluetooth Module                    | 20        | 0.43%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 20        | 0.43%   |
| Toshiba Bluetooth Device                            | 19        | 0.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 19        | 0.41%   |
| IMC Networks Bluetooth                              | 18        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4800      | 64.59%  |
| AMD                                          | 1170      | 15.74%  |
| Nvidia                                       | 935       | 12.58%  |
| Realtek Semiconductor                        | 74        | 1%      |
| Logitech                                     | 52        | 0.7%    |
| GN Netcom                                    | 39        | 0.52%   |
| C-Media Electronics                          | 36        | 0.48%   |
| Plantronics                                  | 29        | 0.39%   |
| Lenovo                                       | 25        | 0.34%   |
| JMTek                                        | 22        | 0.3%    |
| Hewlett-Packard                              | 22        | 0.3%    |
| Kingston Technology                          | 19        | 0.26%   |
| Silicon Integrated Systems [SiS]             | 14        | 0.19%   |
| Corsair                                      | 14        | 0.19%   |
| Generalplus Technology                       | 10        | 0.13%   |
| Texas Instruments                            | 9         | 0.12%   |
| Focusrite-Novation                           | 9         | 0.12%   |
| SteelSeries ApS                              | 8         | 0.11%   |
| Apple                                        | 8         | 0.11%   |
| Sony                                         | 7         | 0.09%   |
| Razer USA                                    | 6         | 0.08%   |
| ASUSTek Computer                             | 6         | 0.08%   |
| VIA Technologies                             | 4         | 0.05%   |
| Sennheiser Communications                    | 3         | 0.04%   |
| RODE Microphones                             | 3         | 0.04%   |
| PreSonus Audio Electronics                   | 3         | 0.04%   |
| No brand                                     | 3         | 0.04%   |
| M-Audio                                      | 3         | 0.04%   |
| Elitegroup Computer Systems (ECS)            | 3         | 0.04%   |
| DSEA A/S                                     | 3         | 0.04%   |
| Creative Technology                          | 3         | 0.04%   |
| Conexant Systems                             | 3         | 0.04%   |
| BR23                                         | 3         | 0.04%   |
| Blue Microphones                             | 3         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| ZOOM                                         | 2         | 0.03%   |
| Yamaha                                       | 2         | 0.03%   |
| XMOS                                         | 2         | 0.03%   |
| ROCCAT                                       | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)                | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 610       | 6.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 559       | 6.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 483       | 5.4%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 310       | 3.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 302       | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 300       | 3.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 287       | 3.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 283       | 3.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 236       | 2.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 234       | 2.62%   |
| Intel 8 Series HD Audio Controller                                                                | 225       | 2.51%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 223       | 2.49%   |
| Intel Broadwell-U Audio Controller                                                                | 213       | 2.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 212       | 2.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 197       | 2.2%    |
| AMD FCH Azalia Controller                                                                         | 185       | 2.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 180       | 2.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 166       | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 162       | 1.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 147       | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 139       | 1.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 119       | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 117       | 1.31%   |
| Intel CM238 HD Audio Controller                                                                   | 116       | 1.3%    |
| Intel Comet Lake PCH cAVS                                                                         | 115       | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 111       | 1.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 105       | 1.17%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 102       | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 93        | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 88        | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 83        | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 82        | 0.92%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 81        | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 78        | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 75        | 0.84%   |
| Realtek Semiconductor USB Audio                                                                   | 72        | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 72        | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 72        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 70        | 0.78%   |
| AMD Wrestler HDMI Audio                                                                           | 64        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 1396      | 29.87%  |
| SK hynix                                         | 1224      | 26.19%  |
| Micron Technology                                | 577       | 12.34%  |
| Kingston                                         | 324       | 6.93%   |
| Unknown                                          | 303       | 6.48%   |
| Crucial                                          | 225       | 4.81%   |
| Ramaxel Technology                               | 89        | 1.9%    |
| Elpida                                           | 88        | 1.88%   |
| Corsair                                          | 72        | 1.54%   |
| Nanya Technology                                 | 63        | 1.35%   |
| Unknown (ABCD)                                   | 60        | 1.28%   |
| G.Skill                                          | 57        | 1.22%   |
| A-DATA Technology                                | 57        | 1.22%   |
| Unknown                                          | 30        | 0.64%   |
| Transcend                                        | 12        | 0.26%   |
| ASint Technology                                 | 7         | 0.15%   |
| Timetec                                          | 6         | 0.13%   |
| Apacer                                           | 6         | 0.13%   |
| Patriot                                          | 5         | 0.11%   |
| Toshiba                                          | 4         | 0.09%   |
| Team                                             | 4         | 0.09%   |
| Qimonda                                          | 4         | 0.09%   |
| V-Color                                          | 3         | 0.06%   |
| TEXTORM                                          | 3         | 0.06%   |
| SHARETRONIC                                      | 3         | 0.06%   |
| PNY                                              | 3         | 0.06%   |
| Unknown (0x0C97)                                 | 2         | 0.04%   |
| Neo Forza                                        | 2         | 0.04%   |
| Lexar                                            | 2         | 0.04%   |
| Goldkey                                          | 2         | 0.04%   |
| ChangXin Memory                                  | 2         | 0.04%   |
| 48spaces                                         | 2         | 0.04%   |
| Wilk                                             | 1         | 0.02%   |
| Unknown (F301)                                   | 1         | 0.02%   |
| Unknown (0x8634)                                 | 1         | 0.02%   |
| Unknown (0x7301)                                 | 1         | 0.02%   |
| Unknown (0x5846)                                 | 1         | 0.02%   |
| Unknown (0x4D3420373054353636334548332D43463720) | 1         | 0.02%   |
| Unknown (0x4D342037305432383634515A332D43463720) | 1         | 0.02%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 68        | 1.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 68        | 1.39%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 66        | 1.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 65        | 1.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 61        | 1.24%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 58        | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 57        | 1.16%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 55        | 1.12%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 49        | 1%      |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 45        | 0.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 45        | 0.92%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 43        | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 42        | 0.86%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 42        | 0.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 42        | 0.86%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 41        | 0.84%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 41        | 0.84%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 41        | 0.84%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 37        | 0.75%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 32        | 0.65%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 31        | 0.63%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 30        | 0.61%   |
| Unknown                                                             | 30        | 0.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 29        | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 25        | 0.51%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 25        | 0.51%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 25        | 0.51%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                          | 23        | 0.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 23        | 0.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 22        | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 22        | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 22        | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 22        | 0.45%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 21        | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 20        | 0.41%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 20        | 0.41%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 20        | 0.41%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 20        | 0.41%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s              | 19        | 0.39%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 19        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1826      | 45.57%  |
| DDR3    | 1381      | 34.46%  |
| DDR2    | 191       | 4.77%   |
| LPDDR4  | 187       | 4.67%   |
| LPDDR3  | 114       | 2.85%   |
| DDR5    | 88        | 2.2%    |
| SDRAM   | 86        | 2.15%   |
| LPDDR5  | 81        | 2.02%   |
| Unknown | 30        | 0.75%   |
| DDR     | 15        | 0.37%   |
| DRAM    | 8         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3571      | 89.14%  |
| Row Of Chips | 378       | 9.44%   |
| Chip         | 22        | 0.55%   |
| Unknown      | 18        | 0.45%   |
| DIMM         | 17        | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1635      | 37.49%  |
| 4096  | 1333      | 30.57%  |
| 16384 | 592       | 13.57%  |
| 2048  | 556       | 12.75%  |
| 1024  | 134       | 3.07%   |
| 32768 | 100       | 2.29%   |
| 512   | 9         | 0.21%   |
| 49152 | 1         | 0.02%   |
| 256   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1003      | 23.46%  |
| 3200    | 801       | 18.74%  |
| 2667    | 787       | 18.41%  |
| 2400    | 263       | 6.15%   |
| 2133    | 215       | 5.03%   |
| 1334    | 214       | 5.01%   |
| 1333    | 123       | 2.88%   |
| 667     | 100       | 2.34%   |
| 6400    | 77        | 1.8%    |
| 4800    | 76        | 1.78%   |
| 4267    | 71        | 1.66%   |
| Unknown | 68        | 1.59%   |
| 3266    | 66        | 1.54%   |
| 1067    | 63        | 1.47%   |
| 800     | 51        | 1.19%   |
| 1867    | 49        | 1.15%   |
| 4199    | 41        | 0.96%   |
| 2048    | 39        | 0.91%   |
| 1066    | 29        | 0.68%   |
| 975     | 27        | 0.63%   |
| 4266    | 21        | 0.49%   |
| 533     | 19        | 0.44%   |
| 5600    | 17        | 0.4%    |
| 8400    | 14        | 0.33%   |
| 2933    | 9         | 0.21%   |
| 1866    | 7         | 0.16%   |
| 333     | 5         | 0.12%   |
| 3733    | 4         | 0.09%   |
| 3000    | 4         | 0.09%   |
| 1639    | 3         | 0.07%   |
| 7500    | 2         | 0.05%   |
| 400     | 2         | 0.05%   |
| 266     | 2         | 0.05%   |
| 5500    | 1         | 0.02%   |
| 1776    | 1         | 0.02%   |
| 933     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 35.56%  |
| Canon               | 12        | 26.67%  |
| Samsung Electronics | 5         | 11.11%  |
| Seiko Epson         | 4         | 8.89%   |
| Brother Industries  | 4         | 8.89%   |
| Xiaomi              | 1         | 2.22%   |
| STMicroelectronics  | 1         | 2.22%   |
| QinHeng Electronics | 1         | 2.22%   |
| Dymo-CoStar         | 1         | 2.22%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 5         | 11.11%  |
| HP DeskJet 3630 series                                    | 3         | 6.67%   |
| Canon PIXMA MG2500 Series                                 | 3         | 6.67%   |
| Seiko Epson WF-2830 Series                                | 2         | 4.44%   |
| Canon PIXMA MG3600 Series                                 | 2         | 4.44%   |
| Xiaomi MiMouse 2                                          | 1         | 2.22%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.22%   |
| Seiko Epson XP-255 257 Series                             | 1         | 2.22%   |
| Seiko Epson XP-2150 Series                                | 1         | 2.22%   |
| Samsung SCX-3200 Series                                   | 1         | 2.22%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 2.22%   |
| Samsung M2070 Series                                      | 1         | 2.22%   |
| Samsung M2020 Series                                      | 1         | 2.22%   |
| Samsung CLX-3180 Series                                   | 1         | 2.22%   |
| QinHeng CH340S                                            | 1         | 2.22%   |
| HP Photosmart B010 series                                 | 1         | 2.22%   |
| HP OfficeJet Pro 69                                       | 1         | 2.22%   |
| HP OfficeJet 3830 series                                  | 1         | 2.22%   |
| HP ENVY Photo 6200 series                                 | 1         | 2.22%   |
| HP ENVY 5540 series                                       | 1         | 2.22%   |
| HP ENVY 4500 series                                       | 1         | 2.22%   |
| HP Deskjet F4500 series                                   | 1         | 2.22%   |
| HP DeskJet 2600 series                                    | 1         | 2.22%   |
| Dymo-CoStar LabelWriter 450                               | 1         | 2.22%   |
| Canon TS6100 series                                       | 1         | 2.22%   |
| Canon TS3100 series                                       | 1         | 2.22%   |
| Canon PIXMA MP495                                         | 1         | 2.22%   |
| Canon PIXMA MP270 All-In-One Printer                      | 1         | 2.22%   |
| Canon PIXMA MG3500 Series                                 | 1         | 2.22%   |
| Canon MG2100 series                                       | 1         | 2.22%   |
| Canon LBP6020                                             | 1         | 2.22%   |
| Brother MFC-L8690CDW series                               | 1         | 2.22%   |
| Brother MFC-L2710DW series                                | 1         | 2.22%   |
| Brother MFC-1810                                          | 1         | 2.22%   |
| Brother DCP-L3550CDW                                      | 1         | 2.22%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 58.33%  |
| Seiko Epson     | 4         | 33.33%  |
| Hewlett-Packard | 1         | 8.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                       | 3         | 25%     |
| Seiko Epson Scanner                           | 1         | 8.33%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]   | 1         | 8.33%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 8.33%   |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 8.33%   |
| HP ScanJet 3570c                              | 1         | 8.33%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 8.33%   |
| Canon CanoScan N650U/N656U                    | 1         | 8.33%   |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 8.33%   |
| Canon CanoScan 8800F                          | 1         | 8.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1316      | 24.7%   |
| IMC Networks                           | 595       | 11.17%  |
| Microdia                               | 526       | 9.87%   |
| Realtek Semiconductor                  | 485       | 9.1%    |
| Sunplus Innovation Technology          | 320       | 6.01%   |
| Bison Electronics                      | 311       | 5.84%   |
| Cheng Uei Precision Industry (Foxlink) | 220       | 4.13%   |
| Quanta                                 | 211       | 3.96%   |
| Suyin                                  | 209       | 3.92%   |
| Lite-On Technology                     | 147       | 2.76%   |
| Acer                                   | 129       | 2.42%   |
| Apple                                  | 118       | 2.22%   |
| Syntek                                 | 101       | 1.9%    |
| Luxvisions Innotech Limited            | 78        | 1.46%   |
| Logitech                               | 74        | 1.39%   |
| Alcor Micro                            | 74        | 1.39%   |
| Ricoh                                  | 53        | 0.99%   |
| Silicon Motion                         | 46        | 0.86%   |
| Samsung Electronics                    | 38        | 0.71%   |
| Sonix Technology                       | 37        | 0.69%   |
| Lenovo                                 | 23        | 0.43%   |
| Primax Electronics                     | 21        | 0.39%   |
| Z-Star Microelectronics                | 19        | 0.36%   |
| Importek                               | 17        | 0.32%   |
| DigiTech                               | 16        | 0.3%    |
| ALi                                    | 15        | 0.28%   |
| Y Media                                | 11        | 0.21%   |
| Shinetech                              | 11        | 0.21%   |
| USB Camera                             | 9         | 0.17%   |
| GEMBIRD                                | 8         | 0.15%   |
| SunplusIT                              | 7         | 0.13%   |
| OmniVision Technologies                | 7         | 0.13%   |
| Microsoft                              | 6         | 0.11%   |
| Intel                                  | 4         | 0.08%   |
| Denron                                 | 4         | 0.08%   |
| Xiaomi                                 | 3         | 0.06%   |
| Sunplus Technology                     | 3         | 0.06%   |
| Pixart Imaging                         | 3         | 0.06%   |
| Generalplus Technology                 | 3         | 0.06%   |
| ARC International                      | 3         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 282       | 5.27%   |
| Realtek Integrated_Webcam_HD             | 219       | 4.09%   |
| Chicony Integrated Camera                | 210       | 3.93%   |
| IMC Networks USB2.0 HD UVC WebCam        | 147       | 2.75%   |
| Chicony HD Webcam                        | 127       | 2.37%   |
| IMC Networks Integrated Camera           | 102       | 1.91%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 97        | 1.81%   |
| Realtek USB Camera                       | 86        | 1.61%   |
| Sunplus Integrated_Webcam_HD             | 85        | 1.59%   |
| Bison Integrated Camera                  | 74        | 1.38%   |
| Chicony USB2.0 Camera                    | 65        | 1.22%   |
| Chicony USB2.0 VGA UVC WebCam            | 59        | 1.1%    |
| Chicony HP HD Camera                     | 59        | 1.1%    |
| Microdia Integrated Webcam               | 54        | 1.01%   |
| Syntek Integrated Camera                 | 53        | 0.99%   |
| Chicony USB2.0 HD UVC WebCam             | 50        | 0.93%   |
| Chicony TOSHIBA Web Camera - HD          | 49        | 0.92%   |
| Chicony HP Truevision HD camera          | 47        | 0.88%   |
| Sunplus ASUS Webcam                      | 46        | 0.86%   |
| Lite-On Integrated Camera                | 46        | 0.86%   |
| Chicony HP TrueVision HD                 | 46        | 0.86%   |
| Bison HD Webcam                          | 46        | 0.86%   |
| Chicony USB 2.0 Camera                   | 44        | 0.82%   |
| Bison BisonCam,NB Pro                    | 44        | 0.82%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR       | 41        | 0.77%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 38        | 0.71%   |
| Samsung Galaxy series, misc. (MTP mode)  | 38        | 0.71%   |
| Chicony HP HD Webcam                     | 38        | 0.71%   |
| Realtek USB2.0 HD UVC WebCam             | 37        | 0.69%   |
| Quanta HP HD Camera                      | 37        | 0.69%   |
| Alcor Micro USB 2.0 Camera               | 37        | 0.69%   |
| Apple Built-in iSight                    | 35        | 0.65%   |
| Quanta HD User Facing                    | 34        | 0.64%   |
| Sunplus HD WebCam                        | 33        | 0.62%   |
| Lite-On HP HD Camera                     | 32        | 0.6%    |
| Chicony VGA Webcam                       | 32        | 0.6%    |
| Lite-On HP HD Webcam                     | 30        | 0.56%   |
| IMC Networks ov9734_azurewave_camera     | 29        | 0.54%   |
| Luxvisions Innotech Limited HP HD Camera | 28        | 0.52%   |
| IMC Networks UVC VGA Webcam              | 28        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 340       | 36.13%  |
| Synaptics                          | 200       | 21.25%  |
| Shenzhen Goodix Technology         | 181       | 19.23%  |
| AuthenTec                          | 69        | 7.33%   |
| LighTuning Technology              | 49        | 5.21%   |
| Elan Microelectronics              | 47        | 4.99%   |
| Upek                               | 40        | 4.25%   |
| STMicroelectronics                 | 11        | 1.17%   |
| Focal-systems.Corp                 | 3         | 0.32%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 100       | 10.63%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 99        | 10.52%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 74        | 7.86%   |
| Shenzhen Goodix FingerPrint                                                | 47        | 4.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 43        | 4.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 36        | 3.83%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 35        | 3.72%   |
| Shenzhen Goodix Fingerprint Reader                                         | 34        | 3.61%   |
| Elan ELAN:Fingerprint                                                      | 30        | 3.19%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 2.98%   |
| Validity Sensors VFS491                                                    | 26        | 2.76%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 26        | 2.76%   |
| AuthenTec AES2810                                                          | 24        | 2.55%   |
| Validity Sensors Fingerprint scanner                                       | 22        | 2.34%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 21        | 2.23%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 21        | 2.23%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 19        | 2.02%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 17        | 1.81%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 17        | 1.81%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 1.7%    |
| AuthenTec AES1600                                                          | 16        | 1.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 15        | 1.59%   |
| Elan ELAN:ARM-M4                                                           | 15        | 1.59%   |
| AuthenTec Fingerprint Sensor                                               | 15        | 1.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 1.49%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 1.49%   |
| Synaptics Fingerprint reader [HP G6]                                       | 14        | 1.49%   |
| Validity Sensors VFS Fingerprint sensor                                    | 12        | 1.28%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 0.96%   |
| Unknown                                                                    | 8         | 0.85%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 0.64%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.53%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.53%   |
| Synaptics WBDI Device                                                      | 5         | 0.53%   |
| Synaptics TouchPad                                                         | 5         | 0.53%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 4         | 0.43%   |
| Synaptics WBDI                                                             | 4         | 0.43%   |
| Synaptics  WBDI                                                            | 4         | 0.43%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 292       | 59.11%  |
| Alcor Micro                       | 102       | 20.65%  |
| O2 Micro                          | 40        | 8.1%    |
| Lenovo                            | 20        | 4.05%   |
| Upek                              | 18        | 3.64%   |
| Hewlett-Packard                   | 5         | 1.01%   |
| Yubico.com                        | 4         | 0.81%   |
| Gemalto (was Gemplus)             | 4         | 0.81%   |
| Clay Logic                        | 2         | 0.4%    |
| Aladdin Knowledge Systems         | 2         | 0.4%    |
| VASCO Data Security International | 1         | 0.2%    |
| SpringCard                        | 1         | 0.2%    |
| OmniKey                           | 1         | 0.2%    |
| Chicony Electronics               | 1         | 0.2%    |
| Advanced Card Systems             | 1         | 0.2%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 102       | 20.65%  |
| Broadcom 58200                                                               | 94        | 19.03%  |
| Broadcom BCM5880 Secure Applications Processor                               | 92        | 18.62%  |
| Broadcom 5880                                                                | 63        | 12.75%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 42        | 8.5%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 36        | 7.29%   |
| Lenovo Integrated Smart Card Reader                                          | 19        | 3.85%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 18        | 3.64%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 5         | 1.01%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 4         | 0.81%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 0.81%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.4%    |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.4%    |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.2%    |
| SpringCard Two                                                               | 1         | 0.2%    |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.2%    |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.2%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.2%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.2%    |
| Clay Logic Nitrokey Start                                                    | 1         | 0.2%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.2%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.2%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.2%    |
| Advanced Card Systems ACR122U                                                | 1         | 0.2%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3770      | 61.47%  |
| 1     | 1903      | 31.03%  |
| 2     | 370       | 6.03%   |
| 3     | 72        | 1.17%   |
| 5     | 6         | 0.1%    |
| 4     | 6         | 0.1%    |
| 7     | 3         | 0.05%   |
| 6     | 3         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 929       | 32.85%  |
| Graphics card            | 617       | 21.82%  |
| Chipcard                 | 453       | 16.02%  |
| Net/wireless             | 241       | 8.52%   |
| Multimedia controller    | 130       | 4.6%    |
| Camera                   | 115       | 4.07%   |
| Bluetooth                | 80        | 2.83%   |
| Storage                  | 66        | 2.33%   |
| Communication controller | 48        | 1.7%    |
| Card reader              | 42        | 1.49%   |
| Sound                    | 34        | 1.2%    |
| Modem                    | 25        | 0.88%   |
| Net/ethernet             | 23        | 0.81%   |
| Network                  | 10        | 0.35%   |
| Flash memory             | 4         | 0.14%   |
| Wireless                 | 2         | 0.07%   |
| Unclassified device      | 2         | 0.07%   |
| Dvb card                 | 2         | 0.07%   |
| Unassigned class         | 1         | 0.04%   |
| Storage/raid             | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |
| Firewire controller      | 1         | 0.04%   |

