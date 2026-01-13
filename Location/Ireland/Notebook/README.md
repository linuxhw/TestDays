Linux in Ireland - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

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

Total: 837

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5480               | [bf6091037f](https://linux-hardware.org/?probe=bf6091037f) | Jan 02, 2026 |
| Lenovo        | ThinkPad L14 Gen 5 21L6S... | [26d690db11](https://linux-hardware.org/?probe=26d690db11) | Jan 01, 2026 |
| Apple         | MacBookPro9,2               | [6177dbde06](https://linux-hardware.org/?probe=6177dbde06) | Dec 29, 2025 |
| Schenker      | XMG EVO (M24)               | [3c9ed7a8e1](https://linux-hardware.org/?probe=3c9ed7a8e1) | Dec 26, 2025 |
| Apple         | MacBookPro5,4               | [238e2b95cc](https://linux-hardware.org/?probe=238e2b95cc) | Dec 22, 2025 |
| Dell          | Latitude 5480               | [f9cb3f4f06](https://linux-hardware.org/?probe=f9cb3f4f06) | Dec 08, 2025 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [ad7d44ca83](https://linux-hardware.org/?probe=ad7d44ca83) | Dec 07, 2025 |
| HP            | Pavilion m6                 | [83ae8543ad](https://linux-hardware.org/?probe=83ae8543ad) | Dec 06, 2025 |
| Dell          | Latitude E5420              | [87fa4c5494](https://linux-hardware.org/?probe=87fa4c5494) | Dec 04, 2025 |
| Apple         | MacBookPro5,5               | [c9d9e42f58](https://linux-hardware.org/?probe=c9d9e42f58) | Dec 02, 2025 |
| Lenovo        | ThinkPad P16s Gen 4 21QV... | [2d69745285](https://linux-hardware.org/?probe=2d69745285) | Nov 30, 2025 |
| Dell          | Latitude 5480               | [c4f9267dd0](https://linux-hardware.org/?probe=c4f9267dd0) | Nov 27, 2025 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | [ac7a4ba5fa](https://linux-hardware.org/?probe=ac7a4ba5fa) | Nov 27, 2025 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c6c798ec6a](https://linux-hardware.org/?probe=c6c798ec6a) | Nov 22, 2025 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | [bc44863efb](https://linux-hardware.org/?probe=bc44863efb) | Nov 21, 2025 |
| MSI           | Stealth GS66 12UGS          | [88a072f547](https://linux-hardware.org/?probe=88a072f547) | Nov 14, 2025 |
| Lenovo        | ThinkPad T480 20L6S0CG04    | [41102d245e](https://linux-hardware.org/?probe=41102d245e) | Nov 14, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ed6b6d3adb](https://linux-hardware.org/?probe=ed6b6d3adb) | Nov 13, 2025 |
| Lenovo        | ThinkPad Z16 Gen 1 21D5S... | [a98b6568d5](https://linux-hardware.org/?probe=a98b6568d5) | Nov 13, 2025 |
| HP            | EliteBook 850 G5            | [187ad354a0](https://linux-hardware.org/?probe=187ad354a0) | Oct 22, 2025 |
| Dell          | Latitude 7290               | [17d6b12d74](https://linux-hardware.org/?probe=17d6b12d74) | Oct 21, 2025 |
| HP            | ProBook 460 16 inch G11 ... | [474c444bb7](https://linux-hardware.org/?probe=474c444bb7) | Oct 16, 2025 |
| HP            | ProBook 460 16 inch G11 ... | [0e855ea22e](https://linux-hardware.org/?probe=0e855ea22e) | Oct 13, 2025 |
| Acer          | Aspire 4820T                | [0b96b1a45c](https://linux-hardware.org/?probe=0b96b1a45c) | Oct 11, 2025 |
| HP            | ZBook 15 G3                 | [fda4022552](https://linux-hardware.org/?probe=fda4022552) | Oct 10, 2025 |
| Acer          | Aspire AV16-51P             | [8ee21f7207](https://linux-hardware.org/?probe=8ee21f7207) | Oct 09, 2025 |
| Dell          | XPS 9320                    | [cfdf87fa43](https://linux-hardware.org/?probe=cfdf87fa43) | Oct 07, 2025 |
| HP            | OMEN by Gaming Laptop 16... | [d93fd9cd68](https://linux-hardware.org/?probe=d93fd9cd68) | Oct 05, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | [b373da7b66](https://linux-hardware.org/?probe=b373da7b66) | Oct 02, 2025 |
| Dell          | Precision 3570              | [0792cd8ac5](https://linux-hardware.org/?probe=0792cd8ac5) | Oct 01, 2025 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [0ab773f2cb](https://linux-hardware.org/?probe=0ab773f2cb) | Sep 30, 2025 |
| System76      | Darter Pro                  | [93e47e0ea8](https://linux-hardware.org/?probe=93e47e0ea8) | Sep 28, 2025 |
| Dell          | Latitude 5550               | [3a45309ea3](https://linux-hardware.org/?probe=3a45309ea3) | Sep 26, 2025 |
| HP            | Pavilion Laptop 15-eh0xx... | [5f13a167cf](https://linux-hardware.org/?probe=5f13a167cf) | Sep 22, 2025 |
| Dell          | Latitude E7250              | [23d0cae5a2](https://linux-hardware.org/?probe=23d0cae5a2) | Sep 21, 2025 |
| HP            | ProBook 650 G3              | [14e64e6479](https://linux-hardware.org/?probe=14e64e6479) | Sep 20, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MCC... | [f820f5c67e](https://linux-hardware.org/?probe=f820f5c67e) | Sep 20, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [133d9ca143](https://linux-hardware.org/?probe=133d9ca143) | Sep 19, 2025 |
| System76      | Darter Pro                  | [ea73200ad1](https://linux-hardware.org/?probe=ea73200ad1) | Sep 13, 2025 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [feedd5c728](https://linux-hardware.org/?probe=feedd5c728) | Sep 12, 2025 |
| Lenovo        | ThinkPad T580 20L9001YUK    | [ae256cd6a3](https://linux-hardware.org/?probe=ae256cd6a3) | Sep 11, 2025 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | [35d85793e9](https://linux-hardware.org/?probe=35d85793e9) | Sep 07, 2025 |
| Framework     | Laptop (12th Gen Intel C... | [a256c85c0e](https://linux-hardware.org/?probe=a256c85c0e) | Sep 04, 2025 |
| Framework     | Laptop (12th Gen Intel C... | [f9edae111e](https://linux-hardware.org/?probe=f9edae111e) | Sep 04, 2025 |
| System76      | Darter Pro                  | [ca35503054](https://linux-hardware.org/?probe=ca35503054) | Sep 03, 2025 |
| HP            | Laptop 15-fc0xxx            | [1bc81eac5d](https://linux-hardware.org/?probe=1bc81eac5d) | Sep 03, 2025 |
| HP            | Pavilion 15                 | [ab1864300c](https://linux-hardware.org/?probe=ab1864300c) | Sep 02, 2025 |
| Apple         | MacBookPro11,5              | [424d535907](https://linux-hardware.org/?probe=424d535907) | Aug 29, 2025 |
| AZW           | GT-R                        | [6341fd2b0a](https://linux-hardware.org/?probe=6341fd2b0a) | Aug 27, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [dcb47bcd7a](https://linux-hardware.org/?probe=dcb47bcd7a) | Aug 27, 2025 |
| HP            | EliteBook Folio 1040 G3     | [bfbcf4905c](https://linux-hardware.org/?probe=bfbcf4905c) | Aug 23, 2025 |
| Dell          | Precision 5540              | [83d6c9afdb](https://linux-hardware.org/?probe=83d6c9afdb) | Aug 17, 2025 |
| Lenovo        | ThinkPad P52 20M90017MX     | [12512c558c](https://linux-hardware.org/?probe=12512c558c) | Aug 13, 2025 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | [5fadb3c020](https://linux-hardware.org/?probe=5fadb3c020) | Aug 12, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [7bd56fcc64](https://linux-hardware.org/?probe=7bd56fcc64) | Aug 04, 2025 |
| Lenovo        | ThinkPad P1 Gen 7 21KWS0... | [50840ef175](https://linux-hardware.org/?probe=50840ef175) | Jul 31, 2025 |
| Notebook      | NV4xPZ                      | [37a332f596](https://linux-hardware.org/?probe=37a332f596) | Jul 29, 2025 |
| System76      | Darter Pro                  | [25f8f54f0e](https://linux-hardware.org/?probe=25f8f54f0e) | Jul 24, 2025 |
| Dell          | Precision 7510              | [2b98d07080](https://linux-hardware.org/?probe=2b98d07080) | Jul 14, 2025 |
| Dell          | Latitude 7424 Rugged Ext... | [c58532453b](https://linux-hardware.org/?probe=c58532453b) | Jul 10, 2025 |
| System76      | Darter Pro                  | [17726b23c3](https://linux-hardware.org/?probe=17726b23c3) | Jul 09, 2025 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [01d5138add](https://linux-hardware.org/?probe=01d5138add) | Jul 09, 2025 |
| Apple         | MacBook6,1                  | [018d803185](https://linux-hardware.org/?probe=018d803185) | Jul 03, 2025 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [1f4aaf8ee0](https://linux-hardware.org/?probe=1f4aaf8ee0) | Jun 23, 2025 |
| HP            | Pavilion Laptop 15-eh0xx... | [2664beae66](https://linux-hardware.org/?probe=2664beae66) | Jun 21, 2025 |
| System76      | Darter Pro                  | [5ca8b470c6](https://linux-hardware.org/?probe=5ca8b470c6) | Jun 17, 2025 |
| Lenovo        | Legion S7 16IAH7 82TF       | [2e81385a5f](https://linux-hardware.org/?probe=2e81385a5f) | Jun 11, 2025 |
| Lenovo        | ThinkPad T480s 20L8S09L0... | [bc583ce6ee](https://linux-hardware.org/?probe=bc583ce6ee) | Jun 01, 2025 |
| Apple         | MacBook4,1                  | [d9ae84f37e](https://linux-hardware.org/?probe=d9ae84f37e) | Jun 01, 2025 |
| Lenovo        | V15-ADA 82C7                | [ffd469703c](https://linux-hardware.org/?probe=ffd469703c) | May 31, 2025 |
| Lenovo        | V15-ADA 82C7                | [dd811105df](https://linux-hardware.org/?probe=dd811105df) | May 29, 2025 |
| Dell          | Latitude 3420               | [b9411d97ee](https://linux-hardware.org/?probe=b9411d97ee) | May 27, 2025 |
| Chuwi         | LapBook Pro                 | [0be3d742be](https://linux-hardware.org/?probe=0be3d742be) | May 18, 2025 |
| Acer          | Aspire A315-43              | [80f219b944](https://linux-hardware.org/?probe=80f219b944) | May 04, 2025 |
| Google        | Pujjo                       | [19302700df](https://linux-hardware.org/?probe=19302700df) | May 03, 2025 |
| HP            | EliteBook 8460p             | [6149b5debc](https://linux-hardware.org/?probe=6149b5debc) | May 02, 2025 |
| TongFang      | GX4MRXL                     | [2eb600b776](https://linux-hardware.org/?probe=2eb600b776) | May 02, 2025 |
| Dell          | Inspiron 15 7510            | [58f2cd330f](https://linux-hardware.org/?probe=58f2cd330f) | Apr 27, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dead9d6449](https://linux-hardware.org/?probe=dead9d6449) | Apr 23, 2025 |
| Lenovo        | Yoga Slim 7 14ILL10 83JX    | [c79b637a89](https://linux-hardware.org/?probe=c79b637a89) | Apr 23, 2025 |
| Lenovo        | ThinkPad P51 20HJS0BR0E     | [cb7152ef4a](https://linux-hardware.org/?probe=cb7152ef4a) | Apr 19, 2025 |
| ASUSTek       | GL503VM                     | [6c9e57e895](https://linux-hardware.org/?probe=6c9e57e895) | Apr 18, 2025 |
| Lenovo        | ThinkPad S1 Yoga 20CD00A... | [8d9c12b21a](https://linux-hardware.org/?probe=8d9c12b21a) | Apr 16, 2025 |
| Lenovo        | Yoga Slim 7 14ILL10 83JX    | [88b6822a08](https://linux-hardware.org/?probe=88b6822a08) | Apr 10, 2025 |
| HUAWEI        | MRC-WX0                     | [4007d809cb](https://linux-hardware.org/?probe=4007d809cb) | Apr 07, 2025 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [2162ed7b48](https://linux-hardware.org/?probe=2162ed7b48) | Apr 03, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [15ec5ab51c](https://linux-hardware.org/?probe=15ec5ab51c) | Apr 03, 2025 |
| HP            | 355 G2                      | [da41c8fa00](https://linux-hardware.org/?probe=da41c8fa00) | Mar 23, 2025 |
| HP            | 355 G2                      | [8ccd514031](https://linux-hardware.org/?probe=8ccd514031) | Mar 23, 2025 |
| Dell          | XPS 15 9550                 | [7761b16ab8](https://linux-hardware.org/?probe=7761b16ab8) | Mar 21, 2025 |
| Alienware     | m17 R2                      | [55c4ba2a35](https://linux-hardware.org/?probe=55c4ba2a35) | Mar 21, 2025 |
| Alienware     | m17 R2                      | [08b2ce6a1a](https://linux-hardware.org/?probe=08b2ce6a1a) | Mar 21, 2025 |
| Apple         | MacBook6,1                  | [48a420e964](https://linux-hardware.org/?probe=48a420e964) | Mar 16, 2025 |
| Alienware     | m17 R2                      | [b4ba048ec9](https://linux-hardware.org/?probe=b4ba048ec9) | Mar 10, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6b87535141](https://linux-hardware.org/?probe=6b87535141) | Mar 10, 2025 |
| HP            | Laptop 14-cm0xxx            | [515f6f56bb](https://linux-hardware.org/?probe=515f6f56bb) | Mar 06, 2025 |
| Samsung       | RV410/RV510/S3510/E3510     | [247af323ec](https://linux-hardware.org/?probe=247af323ec) | Mar 04, 2025 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [ed8e4cc5ee](https://linux-hardware.org/?probe=ed8e4cc5ee) | Mar 01, 2025 |
| HP            | Laptop 15-fc0xxx            | [36b6d03f3b](https://linux-hardware.org/?probe=36b6d03f3b) | Feb 25, 2025 |
| Lenovo        | ThinkPad P14s Gen 4 21HG... | [207c8c56a3](https://linux-hardware.org/?probe=207c8c56a3) | Feb 19, 2025 |
| HP            | Pavilion Laptop 14-ec0xx... | [51f4c4c8a9](https://linux-hardware.org/?probe=51f4c4c8a9) | Feb 14, 2025 |
| Dell          | Latitude 3400               | [6316de7eb8](https://linux-hardware.org/?probe=6316de7eb8) | Feb 13, 2025 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [7ec3267a63](https://linux-hardware.org/?probe=7ec3267a63) | Feb 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [0a2a207aa2](https://linux-hardware.org/?probe=0a2a207aa2) | Feb 04, 2025 |
| Dell          | Precision M4700             | [3f43f6d9b6](https://linux-hardware.org/?probe=3f43f6d9b6) | Feb 03, 2025 |
| Dell          | XPS 15 9570                 | [e301d8ed01](https://linux-hardware.org/?probe=e301d8ed01) | Jan 28, 2025 |
| HP            | 255 G6 Notebook PC          | [b945b8159f](https://linux-hardware.org/?probe=b945b8159f) | Jan 28, 2025 |
| Samsung       | 530U3C/530U4C/532U3C        | [ce67196c06](https://linux-hardware.org/?probe=ce67196c06) | Jan 26, 2025 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [e48900314b](https://linux-hardware.org/?probe=e48900314b) | Jan 26, 2025 |
| Lenovo        | ThinkPad E590 20NCA005GI    | [bc2595d887](https://linux-hardware.org/?probe=bc2595d887) | Jan 26, 2025 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [8d0c94654d](https://linux-hardware.org/?probe=8d0c94654d) | Jan 26, 2025 |
| Lenovo        | ThinkPad X230 Tablet 343... | [140af0a66d](https://linux-hardware.org/?probe=140af0a66d) | Jan 25, 2025 |
| Dell          | Precision 7530              | [d6e9391b08](https://linux-hardware.org/?probe=d6e9391b08) | Jan 24, 2025 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [33fa5f78bf](https://linux-hardware.org/?probe=33fa5f78bf) | Jan 24, 2025 |
| Lenovo        | Y50-70 20378                | [6b820e0a67](https://linux-hardware.org/?probe=6b820e0a67) | Jan 19, 2025 |
| HP            | Laptop 15-bs0xx             | [64535b9eb9](https://linux-hardware.org/?probe=64535b9eb9) | Jan 17, 2025 |
| Unknown       | Unknown                     | [fb321de9f1](https://linux-hardware.org/?probe=fb321de9f1) | Jan 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [6c220b1cf8](https://linux-hardware.org/?probe=6c220b1cf8) | Jan 14, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [abb3061225](https://linux-hardware.org/?probe=abb3061225) | Jan 13, 2025 |
| Lenovo        | ThinkPad P52 20M90017MX     | [0891556ea8](https://linux-hardware.org/?probe=0891556ea8) | Jan 10, 2025 |
| Dell          | Latitude 7280               | [1673706549](https://linux-hardware.org/?probe=1673706549) | Jan 08, 2025 |
| Dell          | Latitude 5320               | [c7f4eada6c](https://linux-hardware.org/?probe=c7f4eada6c) | Jan 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [28e55a6043](https://linux-hardware.org/?probe=28e55a6043) | Jan 03, 2025 |
| Lenovo        | IdeaPad S400 20195          | [9cb18b3ddd](https://linux-hardware.org/?probe=9cb18b3ddd) | Jan 01, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [0de62191fb](https://linux-hardware.org/?probe=0de62191fb) | Dec 30, 2024 |
| HP            | Pavilion Laptop 14-dv0xx... | [92fad15c25](https://linux-hardware.org/?probe=92fad15c25) | Dec 15, 2024 |
| HP            | Pavilion Notebook           | [3db7006e49](https://linux-hardware.org/?probe=3db7006e49) | Dec 12, 2024 |
| Dell          | Latitude 5520               | [f1222f143e](https://linux-hardware.org/?probe=f1222f143e) | Nov 28, 2024 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [da194d6897](https://linux-hardware.org/?probe=da194d6897) | Nov 23, 2024 |
| Lenovo        | ThinkPad E590 20NCA005GI    | [e6e49dc8df](https://linux-hardware.org/?probe=e6e49dc8df) | Nov 23, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [b3d142c510](https://linux-hardware.org/?probe=b3d142c510) | Nov 21, 2024 |
| PC Special... | NH5xAx                      | [61b94b9412](https://linux-hardware.org/?probe=61b94b9412) | Nov 18, 2024 |
| Lenovo        | ThinkPad L450 20DT0003MH    | [64603771ce](https://linux-hardware.org/?probe=64603771ce) | Nov 14, 2024 |
| Toshiba       | Satellite C50-B             | [1d473c3a6c](https://linux-hardware.org/?probe=1d473c3a6c) | Nov 12, 2024 |
| Dell          | Latitude 5440               | [b13672d2ba](https://linux-hardware.org/?probe=b13672d2ba) | Nov 03, 2024 |
| Packard Be... | DOTS2                       | [8c96da9d65](https://linux-hardware.org/?probe=8c96da9d65) | Oct 28, 2024 |
| Dell          | XPS 13 9360                 | [03830ecacb](https://linux-hardware.org/?probe=03830ecacb) | Oct 27, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [71dd2a69e3](https://linux-hardware.org/?probe=71dd2a69e3) | Oct 25, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7468eead65](https://linux-hardware.org/?probe=7468eead65) | Oct 24, 2024 |
| Dell          | Latitude 5350               | [58f8fa615d](https://linux-hardware.org/?probe=58f8fa615d) | Oct 21, 2024 |
| Dell          | Latitude 5350               | [b2d8fecadb](https://linux-hardware.org/?probe=b2d8fecadb) | Oct 21, 2024 |
| Dell          | Latitude 5510               | [58a2b04e3e](https://linux-hardware.org/?probe=58a2b04e3e) | Oct 21, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [6ecd5007e0](https://linux-hardware.org/?probe=6ecd5007e0) | Oct 19, 2024 |
| Valve         | Galileo                     | [6fcae86bfc](https://linux-hardware.org/?probe=6fcae86bfc) | Oct 16, 2024 |
| System76      | Oryx Pro                    | [4a122791a4](https://linux-hardware.org/?probe=4a122791a4) | Oct 09, 2024 |
| AVITA         | NS14A6                      | [360beece3d](https://linux-hardware.org/?probe=360beece3d) | Oct 01, 2024 |
| Dell          | Inspiron N5040              | [d09e43e3e6](https://linux-hardware.org/?probe=d09e43e3e6) | Oct 01, 2024 |
| Dell          | Latitude E6320              | [e83def8251](https://linux-hardware.org/?probe=e83def8251) | Sep 30, 2024 |
| Lenovo        | ThinkPad E590 20NCA005GI    | [b072f8b0cc](https://linux-hardware.org/?probe=b072f8b0cc) | Sep 29, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [ed4eaaf121](https://linux-hardware.org/?probe=ed4eaaf121) | Sep 29, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [44ffa4ec45](https://linux-hardware.org/?probe=44ffa4ec45) | Sep 29, 2024 |
| Valve         | Jupiter                     | [9a260645fb](https://linux-hardware.org/?probe=9a260645fb) | Sep 23, 2024 |
| Dell          | XPS 15 9550                 | [a8471713fe](https://linux-hardware.org/?probe=a8471713fe) | Sep 23, 2024 |
| Google        | Careena                     | [bff7611d3d](https://linux-hardware.org/?probe=bff7611d3d) | Sep 22, 2024 |
| Google        | Careena                     | [34debfe95a](https://linux-hardware.org/?probe=34debfe95a) | Sep 22, 2024 |
| Tactus        | GeoBook 140                 | [a1ce5b2e82](https://linux-hardware.org/?probe=a1ce5b2e82) | Sep 22, 2024 |
| Tactus        | GeoBook 140                 | [b3f597938a](https://linux-hardware.org/?probe=b3f597938a) | Sep 22, 2024 |
| System76      | Oryx Pro                    | [6610d42db1](https://linux-hardware.org/?probe=6610d42db1) | Sep 20, 2024 |
| Novatech      | P7xxTM1                     | [d775331611](https://linux-hardware.org/?probe=d775331611) | Sep 15, 2024 |
| Acer          | Aspire 7740                 | [ca477b674b](https://linux-hardware.org/?probe=ca477b674b) | Sep 12, 2024 |
| Apple         | MacBook5,1                  | [42d52446ef](https://linux-hardware.org/?probe=42d52446ef) | Sep 11, 2024 |
| Acer          | Aspire 8930                 | [73a2294956](https://linux-hardware.org/?probe=73a2294956) | Sep 09, 2024 |
| Lenovo        | ThinkPad T410 253722G       | [851485830a](https://linux-hardware.org/?probe=851485830a) | Sep 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [74b60a3b85](https://linux-hardware.org/?probe=74b60a3b85) | Sep 03, 2024 |
| Acer          | Mammoth                     | [ccafd3b2e7](https://linux-hardware.org/?probe=ccafd3b2e7) | Sep 03, 2024 |
| Dell          | Latitude E7240              | [81904cae54](https://linux-hardware.org/?probe=81904cae54) | Aug 30, 2024 |
| Toshiba       | Satellite Pro C50-A-1E4     | [948af4a150](https://linux-hardware.org/?probe=948af4a150) | Aug 25, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [62f0ae71dd](https://linux-hardware.org/?probe=62f0ae71dd) | Aug 20, 2024 |
| HP            | ZBook 17 G6                 | [e6928ca128](https://linux-hardware.org/?probe=e6928ca128) | Aug 17, 2024 |
| Acer          | Aspire A517-53G             | [cc67b415a8](https://linux-hardware.org/?probe=cc67b415a8) | Aug 10, 2024 |
| Acer          | Aspire A517-53G             | [b746d7a719](https://linux-hardware.org/?probe=b746d7a719) | Aug 09, 2024 |
| Dell          | G3 3500                     | [e36e48651a](https://linux-hardware.org/?probe=e36e48651a) | Aug 07, 2024 |
| Lenovo        | ThinkPad E590 20NCA005GI    | [9bc06639cf](https://linux-hardware.org/?probe=9bc06639cf) | Aug 05, 2024 |
| Lenovo        | ThinkPad E590 20NCA005GI    | [a52122bb38](https://linux-hardware.org/?probe=a52122bb38) | Aug 05, 2024 |
| Lenovo        | B50-80 80EW                 | [39cd7e2e3c](https://linux-hardware.org/?probe=39cd7e2e3c) | Aug 03, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [d637423290](https://linux-hardware.org/?probe=d637423290) | Aug 01, 2024 |
| Apple         | MacBookPro13,1              | [63e8900b1d](https://linux-hardware.org/?probe=63e8900b1d) | Aug 01, 2024 |
| Lenovo        | B50-80 80EW                 | [1896ed136c](https://linux-hardware.org/?probe=1896ed136c) | Jul 23, 2024 |
| PC Special... | Initia Ii 15                | [e027b0a5a9](https://linux-hardware.org/?probe=e027b0a5a9) | Jul 13, 2024 |
| HP            | ProBook 640 G1              | [80dbd2fcb8](https://linux-hardware.org/?probe=80dbd2fcb8) | Jul 08, 2024 |
| Google        | Pujjoteen15W                | [0ec95a0e93](https://linux-hardware.org/?probe=0ec95a0e93) | Jul 03, 2024 |
| Dell          | Latitude E5420              | [a140673eb6](https://linux-hardware.org/?probe=a140673eb6) | Jul 01, 2024 |
| Lenovo        | ThinkPad X270 20HN0016MD    | [e01ca65526](https://linux-hardware.org/?probe=e01ca65526) | Jul 01, 2024 |
| HP            | Laptop 14-bs0xx             | [a5cd077129](https://linux-hardware.org/?probe=a5cd077129) | Jun 30, 2024 |
| HP            | EliteBook 8440p             | [1fd69cd28b](https://linux-hardware.org/?probe=1fd69cd28b) | Jun 29, 2024 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | [87e480dac2](https://linux-hardware.org/?probe=87e480dac2) | Jun 20, 2024 |
| HP            | ZBook 17 G6                 | [2095486226](https://linux-hardware.org/?probe=2095486226) | Jun 19, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [c58ac40c49](https://linux-hardware.org/?probe=c58ac40c49) | Jun 17, 2024 |
| Lenovo        | ThinkPad X230 Tablet 343... | [e8badf27ab](https://linux-hardware.org/?probe=e8badf27ab) | Jun 15, 2024 |
| Google        | Minnie                      | [3538fec98e](https://linux-hardware.org/?probe=3538fec98e) | Jun 12, 2024 |
| Acer          | Aspire V3-571               | [5a63cb3389](https://linux-hardware.org/?probe=5a63cb3389) | Jun 10, 2024 |
| Acer          | Aspire V3-571               | [bafbbe0825](https://linux-hardware.org/?probe=bafbbe0825) | Jun 10, 2024 |
| HUAWEI        | WRT-WX9                     | [96b329d349](https://linux-hardware.org/?probe=96b329d349) | Jun 09, 2024 |
| Samsung       | 750XFG                      | [c581b9c2af](https://linux-hardware.org/?probe=c581b9c2af) | Jun 08, 2024 |
| Dell          | Latitude 3420               | [356a53eef2](https://linux-hardware.org/?probe=356a53eef2) | Jun 08, 2024 |
| Dell          | Latitude 3420               | [0b6a5b6ad8](https://linux-hardware.org/?probe=0b6a5b6ad8) | Jun 08, 2024 |
| ASUSTek       | X541UAK                     | [1acb106c74](https://linux-hardware.org/?probe=1acb106c74) | Jun 02, 2024 |
| Alienware     | 17 R4                       | [b4872ce68c](https://linux-hardware.org/?probe=b4872ce68c) | May 28, 2024 |
| HP            | Stream Laptop 11-ak0xxx     | [564a4d2df9](https://linux-hardware.org/?probe=564a4d2df9) | May 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3f1cca26a0](https://linux-hardware.org/?probe=3f1cca26a0) | May 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ede73c3b15](https://linux-hardware.org/?probe=ede73c3b15) | May 22, 2024 |
| HP            | Laptop 15-bs0xx             | [28b6a47300](https://linux-hardware.org/?probe=28b6a47300) | May 22, 2024 |
| Lenovo        | B50-30 80ES                 | [a1857bbe42](https://linux-hardware.org/?probe=a1857bbe42) | May 19, 2024 |
| Lenovo        | B50-30 80ES                 | [5cfe795600](https://linux-hardware.org/?probe=5cfe795600) | May 19, 2024 |
| Alienware     | M11xR3                      | [ebbebdcdf9](https://linux-hardware.org/?probe=ebbebdcdf9) | May 15, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [d05298bbb0](https://linux-hardware.org/?probe=d05298bbb0) | May 14, 2024 |
| Packard Be... | EasyNote TE69KB             | [49d494a8ad](https://linux-hardware.org/?probe=49d494a8ad) | May 11, 2024 |
| Dell          | Inspiron 15 3530            | [a71239f845](https://linux-hardware.org/?probe=a71239f845) | May 05, 2024 |
| HP            | EliteBook 850 G7 Noteboo... | [8bc6786d26](https://linux-hardware.org/?probe=8bc6786d26) | May 04, 2024 |
| HP            | EliteBook 850 G7 Noteboo... | [5a7379a961](https://linux-hardware.org/?probe=5a7379a961) | May 04, 2024 |
| HP            | Notebook                    | [3719fa55d8](https://linux-hardware.org/?probe=3719fa55d8) | May 02, 2024 |
| Dell          | Precision 3551              | [1dc964b6fb](https://linux-hardware.org/?probe=1dc964b6fb) | Apr 30, 2024 |
| Dell          | XPS 15 9530                 | [2349cf6da5](https://linux-hardware.org/?probe=2349cf6da5) | Apr 26, 2024 |
| Toshiba       | Satellite Pro A200          | [305f0f136a](https://linux-hardware.org/?probe=305f0f136a) | Apr 23, 2024 |
| Google        | Morphius                    | [a8361bc931](https://linux-hardware.org/?probe=a8361bc931) | Apr 19, 2024 |
| Apple         | MacBookPro12,1              | [d297fd582e](https://linux-hardware.org/?probe=d297fd582e) | Apr 19, 2024 |
| Valve         | Jupiter                     | [46fe84935f](https://linux-hardware.org/?probe=46fe84935f) | Apr 18, 2024 |
| Dell          | Latitude E6410              | [af5738b699](https://linux-hardware.org/?probe=af5738b699) | Apr 07, 2024 |
| HP            | Laptop 14-bs0xx             | [36cae1df97](https://linux-hardware.org/?probe=36cae1df97) | Apr 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3bc12b2fdc](https://linux-hardware.org/?probe=3bc12b2fdc) | Mar 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f1279e5f4](https://linux-hardware.org/?probe=2f1279e5f4) | Mar 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [96e93279ce](https://linux-hardware.org/?probe=96e93279ce) | Mar 21, 2024 |
| Dell          | Latitude E7240              | [bac4c4e0b9](https://linux-hardware.org/?probe=bac4c4e0b9) | Mar 21, 2024 |
| Dell          | Latitude E7240              | [4b2cf432cb](https://linux-hardware.org/?probe=4b2cf432cb) | Mar 19, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [9275a0aa01](https://linux-hardware.org/?probe=9275a0aa01) | Mar 18, 2024 |
| Dell          | Precision 7780              | [0cea91e90e](https://linux-hardware.org/?probe=0cea91e90e) | Mar 13, 2024 |
| Dell          | Precision 3551              | [ac0c79297b](https://linux-hardware.org/?probe=ac0c79297b) | Mar 12, 2024 |
| Dell          | Latitude 7490               | [af0f098b77](https://linux-hardware.org/?probe=af0f098b77) | Mar 10, 2024 |
| Lenovo        | ThinkPad X230 2325AEG       | [8e4dbd3b9a](https://linux-hardware.org/?probe=8e4dbd3b9a) | Mar 10, 2024 |
| ASUSTek       | GL753VD                     | [10302c2e00](https://linux-hardware.org/?probe=10302c2e00) | Mar 04, 2024 |
| Linx          | LINX1010B                   | [185483454f](https://linux-hardware.org/?probe=185483454f) | Mar 03, 2024 |
| Notebook      | N15_17RD                    | [efc829810d](https://linux-hardware.org/?probe=efc829810d) | Feb 28, 2024 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [bc6b844872](https://linux-hardware.org/?probe=bc6b844872) | Feb 22, 2024 |
| ASUSTek       | GL753VD                     | [5f363c641f](https://linux-hardware.org/?probe=5f363c641f) | Feb 22, 2024 |
| Lenovo        | IdeaPad S340-15API 81NC     | [656953e587](https://linux-hardware.org/?probe=656953e587) | Feb 20, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [13aee4c968](https://linux-hardware.org/?probe=13aee4c968) | Feb 19, 2024 |
| Valve         | Jupiter                     | [51257484fe](https://linux-hardware.org/?probe=51257484fe) | Feb 17, 2024 |
| Dell          | XPS 13 9380                 | [4a65dda0f2](https://linux-hardware.org/?probe=4a65dda0f2) | Feb 10, 2024 |
| Dell          | Studio XPS 1645             | [cb868b4ea2](https://linux-hardware.org/?probe=cb868b4ea2) | Feb 09, 2024 |
| Google        | Reks                        | [5e667c40ed](https://linux-hardware.org/?probe=5e667c40ed) | Feb 09, 2024 |
| Lenovo        | ThinkPad L13 Gen 2a 21AC... | [a07cdee250](https://linux-hardware.org/?probe=a07cdee250) | Feb 08, 2024 |
| Dell          | XPS 13 9350                 | [24d22f38e9](https://linux-hardware.org/?probe=24d22f38e9) | Feb 08, 2024 |
| Lenovo        | ThinkPad P50 20EQS57700     | [39735c6cd2](https://linux-hardware.org/?probe=39735c6cd2) | Feb 03, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c8e849a73](https://linux-hardware.org/?probe=0c8e849a73) | Jan 15, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [3717e058ac](https://linux-hardware.org/?probe=3717e058ac) | Jan 13, 2024 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [8101d22b4a](https://linux-hardware.org/?probe=8101d22b4a) | Jan 09, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [999111d4e5](https://linux-hardware.org/?probe=999111d4e5) | Jan 09, 2024 |
| Acer          | Aspire ES1-533              | [68d1525855](https://linux-hardware.org/?probe=68d1525855) | Jan 08, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [e2b86aade4](https://linux-hardware.org/?probe=e2b86aade4) | Jan 07, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [e9337be795](https://linux-hardware.org/?probe=e9337be795) | Jan 07, 2024 |
| HP            | EliteBook 830 G6            | [1198f24836](https://linux-hardware.org/?probe=1198f24836) | Jan 04, 2024 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [0781004009](https://linux-hardware.org/?probe=0781004009) | Jan 02, 2024 |
| Medion        | Akoya E6239                 | [757858a876](https://linux-hardware.org/?probe=757858a876) | Dec 31, 2023 |
| Packard Be... | EasyNote TS44HR             | [a06265dd1e](https://linux-hardware.org/?probe=a06265dd1e) | Dec 30, 2023 |
| Dell          | Inspiron 3482               | [bbcb062420](https://linux-hardware.org/?probe=bbcb062420) | Dec 29, 2023 |
| AVITA         | NS14A6                      | [adf732b1b6](https://linux-hardware.org/?probe=adf732b1b6) | Dec 23, 2023 |
| Toshiba       | Satellite A660              | [d0415e05d3](https://linux-hardware.org/?probe=d0415e05d3) | Dec 23, 2023 |
| Fujitsu       | LIFEBOOK E736               | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| Dell          | Latitude 5400               | [9ae128faf4](https://linux-hardware.org/?probe=9ae128faf4) | Dec 16, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | [91fd392ea3](https://linux-hardware.org/?probe=91fd392ea3) | Dec 14, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | [2dc1349392](https://linux-hardware.org/?probe=2dc1349392) | Dec 10, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [e8383035b9](https://linux-hardware.org/?probe=e8383035b9) | Dec 10, 2023 |
| Samsung       | 750XED                      | [5263f7ebc0](https://linux-hardware.org/?probe=5263f7ebc0) | Dec 07, 2023 |
| Acer          | Swift SFG14-71              | [a84f25d406](https://linux-hardware.org/?probe=a84f25d406) | Dec 07, 2023 |
| Valve         | Jupiter                     | [6a95e96b1b](https://linux-hardware.org/?probe=6a95e96b1b) | Dec 02, 2023 |
| Dynabook      | Satellite Pro C50-H-11G     | [438812dbd7](https://linux-hardware.org/?probe=438812dbd7) | Nov 27, 2023 |
| Valve         | Jupiter                     | [2c7d8106d0](https://linux-hardware.org/?probe=2c7d8106d0) | Nov 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0af175a9d7](https://linux-hardware.org/?probe=0af175a9d7) | Nov 19, 2023 |
| ASUSTek       | X540NA                      | [d0f4cc3a98](https://linux-hardware.org/?probe=d0f4cc3a98) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [a76432f7df](https://linux-hardware.org/?probe=a76432f7df) | Nov 16, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [242621dab3](https://linux-hardware.org/?probe=242621dab3) | Nov 13, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [7736f94150](https://linux-hardware.org/?probe=7736f94150) | Nov 13, 2023 |
| Alienware     | m18 R1                      | [f4c5c9d2ec](https://linux-hardware.org/?probe=f4c5c9d2ec) | Nov 13, 2023 |
| HP            | Pavilion m6                 | [60a4921f94](https://linux-hardware.org/?probe=60a4921f94) | Nov 13, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | [5ad5316ab5](https://linux-hardware.org/?probe=5ad5316ab5) | Nov 11, 2023 |
| Acer          | Aspire 5750                 | [94186792b2](https://linux-hardware.org/?probe=94186792b2) | Nov 08, 2023 |
| Acer          | Aspire A315-41              | [e275461ffe](https://linux-hardware.org/?probe=e275461ffe) | Nov 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [680fae0bef](https://linux-hardware.org/?probe=680fae0bef) | Nov 07, 2023 |
| System76      | Lemur Pro                   | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| System76      | Lemur Pro                   | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| Acer          | Aspire 5750                 | [3ba4126936](https://linux-hardware.org/?probe=3ba4126936) | Nov 04, 2023 |
| Packard Be... | EasyNote TE69KB             | [440d52f445](https://linux-hardware.org/?probe=440d52f445) | Nov 04, 2023 |
| Acer          | Aspire 5736Z                | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Dell          | Latitude 5421               | [670d635ddc](https://linux-hardware.org/?probe=670d635ddc) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1a7844f56d](https://linux-hardware.org/?probe=1a7844f56d) | Oct 30, 2023 |
| Acer          | Swift SFG14-71              | [1a28398320](https://linux-hardware.org/?probe=1a28398320) | Oct 26, 2023 |
| Dell          | Inspiron 7560               | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [390f0188b4](https://linux-hardware.org/?probe=390f0188b4) | Oct 19, 2023 |
| HP            | EliteBook 830 G6            | [c9ab502087](https://linux-hardware.org/?probe=c9ab502087) | Oct 17, 2023 |
| Dell          | Latitude E6430              | [45d51130b0](https://linux-hardware.org/?probe=45d51130b0) | Oct 08, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [446c6847c3](https://linux-hardware.org/?probe=446c6847c3) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [da869ee2ba](https://linux-hardware.org/?probe=da869ee2ba) | Oct 04, 2023 |
| Dell          | Latitude 5580               | [cf79594d59](https://linux-hardware.org/?probe=cf79594d59) | Oct 02, 2023 |
| Dell          | Latitude 5580               | [9cb7ac852c](https://linux-hardware.org/?probe=9cb7ac852c) | Oct 02, 2023 |
| Dell          | Inspiron 5570               | [93e66c7d47](https://linux-hardware.org/?probe=93e66c7d47) | Oct 02, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [ffd2e0d99d](https://linux-hardware.org/?probe=ffd2e0d99d) | Oct 01, 2023 |
| Dell          | Latitude 5410               | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [86d39b72d6](https://linux-hardware.org/?probe=86d39b72d6) | Sep 29, 2023 |
| Dell          | Latitude 5410               | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | [0e12b69b96](https://linux-hardware.org/?probe=0e12b69b96) | Sep 29, 2023 |
| Acer          | Aspire 5736Z                | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Dell          | Latitude 7320               | [2549020a4e](https://linux-hardware.org/?probe=2549020a4e) | Sep 26, 2023 |
| MSI           | Katana GF76 12UG            | [ee50afcf85](https://linux-hardware.org/?probe=ee50afcf85) | Sep 18, 2023 |
| Dell          | Inspiron 5559               | [8bf4c79f98](https://linux-hardware.org/?probe=8bf4c79f98) | Sep 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| Dell          | Latitude E6400              | [b0943a149a](https://linux-hardware.org/?probe=b0943a149a) | Sep 10, 2023 |
| ASUSTek       | X540NA                      | [e335c8210f](https://linux-hardware.org/?probe=e335c8210f) | Sep 03, 2023 |
| ASUSTek       | K53SV                       | [17802d53e7](https://linux-hardware.org/?probe=17802d53e7) | Aug 30, 2023 |
| HP            | Compaq Presario CQ60        | [12b48399ac](https://linux-hardware.org/?probe=12b48399ac) | Aug 30, 2023 |
| Lenovo        | ThinkPad X200 7459ED2       | [4885ef4597](https://linux-hardware.org/?probe=4885ef4597) | Aug 27, 2023 |
| Chuwi         | GemiBook Pro                | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [546610fecb](https://linux-hardware.org/?probe=546610fecb) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | [692bd3fa37](https://linux-hardware.org/?probe=692bd3fa37) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | [6313b3f69e](https://linux-hardware.org/?probe=6313b3f69e) | Aug 20, 2023 |
| Apple         | MacBookPro14,2              | [8b0d028b37](https://linux-hardware.org/?probe=8b0d028b37) | Aug 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [2e4e848552](https://linux-hardware.org/?probe=2e4e848552) | Aug 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [179beade50](https://linux-hardware.org/?probe=179beade50) | Aug 08, 2023 |
| Dell          | Precision M2800             | [7d1afe9d42](https://linux-hardware.org/?probe=7d1afe9d42) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [76662ba2c9](https://linux-hardware.org/?probe=76662ba2c9) | Aug 05, 2023 |
| Acer          | Predator PH315-53           | [6c13f7a1f0](https://linux-hardware.org/?probe=6c13f7a1f0) | Aug 04, 2023 |
| Lenovo        | ThinkPad T430 2347FF9       | [30354c1f38](https://linux-hardware.org/?probe=30354c1f38) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [928fd8c7cb](https://linux-hardware.org/?probe=928fd8c7cb) | Jul 29, 2023 |
| Fujitsu       | LIFEBOOK A512               | [8e05eceeef](https://linux-hardware.org/?probe=8e05eceeef) | Jul 26, 2023 |
| Fujitsu       | LIFEBOOK A512               | [5457b19b2b](https://linux-hardware.org/?probe=5457b19b2b) | Jul 26, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [f47d2eaa8e](https://linux-hardware.org/?probe=f47d2eaa8e) | Jul 16, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | [99b59160a1](https://linux-hardware.org/?probe=99b59160a1) | Jul 16, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [a505a2e91f](https://linux-hardware.org/?probe=a505a2e91f) | Jul 15, 2023 |
| HP            | Pavilion m6                 | [8566e9607f](https://linux-hardware.org/?probe=8566e9607f) | Jul 14, 2023 |
| Dell          | Inspiron 1545               | [0e9916f3e3](https://linux-hardware.org/?probe=0e9916f3e3) | Jul 13, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [a72d009fab](https://linux-hardware.org/?probe=a72d009fab) | Jul 13, 2023 |
| Acer          | Aspire A515-56              | [9dee0fcab9](https://linux-hardware.org/?probe=9dee0fcab9) | Jul 09, 2023 |
| Samsung       | 750XED                      | [412a36c3f1](https://linux-hardware.org/?probe=412a36c3f1) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [aa8cfd7d60](https://linux-hardware.org/?probe=aa8cfd7d60) | Jul 07, 2023 |
| Dell          | Latitude 3410               | [da609df435](https://linux-hardware.org/?probe=da609df435) | Jul 03, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [bfa03ecd27](https://linux-hardware.org/?probe=bfa03ecd27) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [58d1b3da16](https://linux-hardware.org/?probe=58d1b3da16) | Jun 25, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [3fbef5ec38](https://linux-hardware.org/?probe=3fbef5ec38) | Jun 25, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [8bf2dd01d7](https://linux-hardware.org/?probe=8bf2dd01d7) | Jun 18, 2023 |
| Apple         | MacBook6,1                  | [913d8d26b9](https://linux-hardware.org/?probe=913d8d26b9) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC0F    | [581602e921](https://linux-hardware.org/?probe=581602e921) | Jun 07, 2023 |
| Lenovo        | V330-15IKB 81AX             | [476a44deee](https://linux-hardware.org/?probe=476a44deee) | Jun 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [8678eeac9b](https://linux-hardware.org/?probe=8678eeac9b) | Jun 03, 2023 |
| Dell          | Inspiron 5559               | [9e1fe43cf9](https://linux-hardware.org/?probe=9e1fe43cf9) | Jun 03, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | [e462733019](https://linux-hardware.org/?probe=e462733019) | May 29, 2023 |
| HP            | ZBook 15                    | [def4482b86](https://linux-hardware.org/?probe=def4482b86) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Dell          | Inspiron 5570               | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Dell          | XPS 13 9380                 | [af31929040](https://linux-hardware.org/?probe=af31929040) | May 09, 2023 |
| Dell          | XPS 13 9380                 | [b4e9bb9147](https://linux-hardware.org/?probe=b4e9bb9147) | May 07, 2023 |
| Acer          | Nitro AN515-54              | [c223c83063](https://linux-hardware.org/?probe=c223c83063) | May 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [8a7ed180c0](https://linux-hardware.org/?probe=8a7ed180c0) | May 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Dell          | Latitude E5520              | [43e2d970b5](https://linux-hardware.org/?probe=43e2d970b5) | Apr 30, 2023 |
| Dell          | Latitude 7420               | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| Dell          | Inspiron 7577               | [84ae892fb4](https://linux-hardware.org/?probe=84ae892fb4) | Apr 19, 2023 |
| HP            | Compaq Presario CQ70        | [030eff02bb](https://linux-hardware.org/?probe=030eff02bb) | Apr 18, 2023 |
| Dell          | Latitude 7420               | [1b2360944e](https://linux-hardware.org/?probe=1b2360944e) | Apr 17, 2023 |
| Lenovo        | S21e-20 80M4                | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| Dell          | Latitude 5400               | [f2d5671ba5](https://linux-hardware.org/?probe=f2d5671ba5) | Apr 07, 2023 |
| ASUSTek       | G752VM                      | [13d6602e92](https://linux-hardware.org/?probe=13d6602e92) | Apr 02, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8e927ead89](https://linux-hardware.org/?probe=8e927ead89) | Mar 30, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [889ef05f86](https://linux-hardware.org/?probe=889ef05f86) | Mar 30, 2023 |
| Dell          | Inspiron 13-5378            | [2aff972d11](https://linux-hardware.org/?probe=2aff972d11) | Mar 27, 2023 |
| Timi          | A35S                        | [92022a5fa2](https://linux-hardware.org/?probe=92022a5fa2) | Mar 25, 2023 |
| Acer          | Aspire F5-573G              | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| MSI           | GP72 7RE                    | [729f2297cb](https://linux-hardware.org/?probe=729f2297cb) | Mar 23, 2023 |
| Dell          | Latitude 7420               | [ac9a26d11c](https://linux-hardware.org/?probe=ac9a26d11c) | Mar 20, 2023 |
| Samsung       | 940XFG                      | [566a4046f6](https://linux-hardware.org/?probe=566a4046f6) | Mar 18, 2023 |
| Google        | Reks                        | [56296236c5](https://linux-hardware.org/?probe=56296236c5) | Mar 12, 2023 |
| Dell          | Inspiron 5570               | [f6da200721](https://linux-hardware.org/?probe=f6da200721) | Mar 11, 2023 |
| Dell          | Inspiron 5570               | [56e5783575](https://linux-hardware.org/?probe=56e5783575) | Mar 11, 2023 |
| HP            | ProBook 4330s               | [00d887061a](https://linux-hardware.org/?probe=00d887061a) | Mar 10, 2023 |
| Google        | Reks                        | [f877db79d3](https://linux-hardware.org/?probe=f877db79d3) | Mar 09, 2023 |
| Dell          | Latitude 7420               | [00ef839a27](https://linux-hardware.org/?probe=00ef839a27) | Mar 06, 2023 |
| Dell          | Latitude 7420               | [18b4bfe200](https://linux-hardware.org/?probe=18b4bfe200) | Mar 06, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [d70aeca173](https://linux-hardware.org/?probe=d70aeca173) | Mar 04, 2023 |
| Dell          | Latitude 7420               | [49bdd8711f](https://linux-hardware.org/?probe=49bdd8711f) | Mar 02, 2023 |
| HP            | EliteBook 755 G5            | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Dell          | Latitude 7420               | [d3af27a0ac](https://linux-hardware.org/?probe=d3af27a0ac) | Feb 27, 2023 |
| HP            | 655                         | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Valve         | Jupiter                     | [b6f7c77e33](https://linux-hardware.org/?probe=b6f7c77e33) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | [bb18722cf2](https://linux-hardware.org/?probe=bb18722cf2) | Feb 21, 2023 |
| Dell          | Latitude E7240              | [fb6daef60c](https://linux-hardware.org/?probe=fb6daef60c) | Feb 17, 2023 |
| Dell          | G15 5520                    | [a5966eaac0](https://linux-hardware.org/?probe=a5966eaac0) | Feb 15, 2023 |
| Dell          | G3 3779                     | [cc77f75f3d](https://linux-hardware.org/?probe=cc77f75f3d) | Feb 15, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [181833b556](https://linux-hardware.org/?probe=181833b556) | Feb 09, 2023 |
| HP            | EliteBook 830 G5            | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [e07858d71e](https://linux-hardware.org/?probe=e07858d71e) | Feb 03, 2023 |
| Valve         | Jupiter                     | [50727dbbde](https://linux-hardware.org/?probe=50727dbbde) | Feb 02, 2023 |
| Valve         | Jupiter                     | [0323a2bd47](https://linux-hardware.org/?probe=0323a2bd47) | Jan 27, 2023 |
| ASUSTek       | X501A1                      | [a0493c6731](https://linux-hardware.org/?probe=a0493c6731) | Jan 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [06f87714b0](https://linux-hardware.org/?probe=06f87714b0) | Jan 26, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [7b23698a1e](https://linux-hardware.org/?probe=7b23698a1e) | Jan 24, 2023 |
| Dell          | Latitude 7420               | [dc99eb6c92](https://linux-hardware.org/?probe=dc99eb6c92) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [7fb655b498](https://linux-hardware.org/?probe=7fb655b498) | Jan 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [397b4da9ab](https://linux-hardware.org/?probe=397b4da9ab) | Jan 21, 2023 |
| Dell          | Inspiron 5770               | [93932bdc92](https://linux-hardware.org/?probe=93932bdc92) | Jan 20, 2023 |
| Dell          | G5 5590                     | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude 5510               | [c9738f8691](https://linux-hardware.org/?probe=c9738f8691) | Jan 18, 2023 |
| Dell          | Inspiron 7560               | [fa1a881ee9](https://linux-hardware.org/?probe=fa1a881ee9) | Jan 17, 2023 |
| Dell          | Inspiron 7560               | [6941e3520e](https://linux-hardware.org/?probe=6941e3520e) | Jan 17, 2023 |
| Dell          | Inspiron 5570               | [5905971b70](https://linux-hardware.org/?probe=5905971b70) | Jan 16, 2023 |
| Valve         | Jupiter                     | [d390e11930](https://linux-hardware.org/?probe=d390e11930) | Jan 11, 2023 |
| Valve         | Jupiter                     | [a181d83115](https://linux-hardware.org/?probe=a181d83115) | Jan 11, 2023 |
| Dell          | Latitude 7420               | [4ce659b05d](https://linux-hardware.org/?probe=4ce659b05d) | Jan 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| Dell          | Latitude E7240              | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| Star Labs     | Lite                        | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| Dell          | Latitude 7420               | [cd159088a3](https://linux-hardware.org/?probe=cd159088a3) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | [1b8d741ea3](https://linux-hardware.org/?probe=1b8d741ea3) | Jan 03, 2023 |
| Samsung       | 940XFG                      | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| Dell          | Latitude 7420               | [60f07d5a45](https://linux-hardware.org/?probe=60f07d5a45) | Dec 16, 2022 |
| Dell          | Latitude 3310               | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Dell          | Latitude E7240              | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| Dynabook      | Satellite Pro C50-H-11G     | [57e8e4ab79](https://linux-hardware.org/?probe=57e8e4ab79) | Dec 06, 2022 |
| ASUSTek       | X510UNR                     | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |
| Dell          | Latitude 7290               | [3f0e476980](https://linux-hardware.org/?probe=3f0e476980) | Dec 04, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Toshiba       | Satellite C50D-A-138        | [ccda846d5e](https://linux-hardware.org/?probe=ccda846d5e) | Dec 03, 2022 |
| Dell          | Inspiron 15-7568            | [9887f68589](https://linux-hardware.org/?probe=9887f68589) | Dec 03, 2022 |
| Acer          | Nitro AN515-46              | [7bdc87a5cc](https://linux-hardware.org/?probe=7bdc87a5cc) | Dec 02, 2022 |
| Acer          | Nitro AN515-46              | [d17ff52554](https://linux-hardware.org/?probe=d17ff52554) | Dec 02, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [90fcc2d8d5](https://linux-hardware.org/?probe=90fcc2d8d5) | Nov 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [2c077b8cde](https://linux-hardware.org/?probe=2c077b8cde) | Nov 23, 2022 |
| Acer          | Aspire A514-55              | [7bf0186e00](https://linux-hardware.org/?probe=7bf0186e00) | Nov 18, 2022 |
| Chuwi         | X312B                       | [b0c9263212](https://linux-hardware.org/?probe=b0c9263212) | Nov 17, 2022 |
| Chuwi         | X312B                       | [7583d01bd8](https://linux-hardware.org/?probe=7583d01bd8) | Nov 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [a174d2b2b3](https://linux-hardware.org/?probe=a174d2b2b3) | Nov 12, 2022 |
| Valve         | Jupiter                     | [ed3f6fb61d](https://linux-hardware.org/?probe=ed3f6fb61d) | Nov 12, 2022 |
| Valve         | Jupiter                     | [c1805091ef](https://linux-hardware.org/?probe=c1805091ef) | Nov 12, 2022 |
| Chuwi         | X312B                       | [0e6a368329](https://linux-hardware.org/?probe=0e6a368329) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5d2ae18b0a](https://linux-hardware.org/?probe=5d2ae18b0a) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [51a3c87183](https://linux-hardware.org/?probe=51a3c87183) | Nov 10, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [bf3996f87d](https://linux-hardware.org/?probe=bf3996f87d) | Nov 03, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1d4a6dc6dc](https://linux-hardware.org/?probe=1d4a6dc6dc) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [a1694d3adc](https://linux-hardware.org/?probe=a1694d3adc) | Oct 29, 2022 |
| Dell          | Inspiron 15-7568            | [ae536fa220](https://linux-hardware.org/?probe=ae536fa220) | Oct 27, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Dell          | Latitude E6440              | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| Dell          | Latitude 7400               | [3b340aa7d4](https://linux-hardware.org/?probe=3b340aa7d4) | Oct 12, 2022 |
| Dell          | Latitude 7400               | [159021ed29](https://linux-hardware.org/?probe=159021ed29) | Oct 12, 2022 |
| Toshiba       | PORTEGE R830                | [ffda659565](https://linux-hardware.org/?probe=ffda659565) | Oct 11, 2022 |
| MSI           | MS-7A34                     | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| HP            | ProBook 455 G6              | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| Timi          | TM1709                      | [33022811a8](https://linux-hardware.org/?probe=33022811a8) | Oct 01, 2022 |
| Dell          | Latitude 7420               | [0834411088](https://linux-hardware.org/?probe=0834411088) | Sep 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| HP            | Pavilion m6                 | [83b6eb0119](https://linux-hardware.org/?probe=83b6eb0119) | Sep 01, 2022 |
| Medion        | E6227                       | [e6ca2257e7](https://linux-hardware.org/?probe=e6ca2257e7) | Sep 01, 2022 |
| Dell          | XPS 9320                    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Framework     | Laptop                      | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| Framework     | Laptop                      | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| HP            | Pavilion g6                 | [ae65121050](https://linux-hardware.org/?probe=ae65121050) | Aug 23, 2022 |
| Apple         | MacBook6,1                  | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| HP            | EliteBook 755 G5            | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 9320                    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| HP            | Pavilion g6                 | [3f462439ed](https://linux-hardware.org/?probe=3f462439ed) | Aug 11, 2022 |
| Samsung       | 935XDB                      | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Samsung       | 935XDB                      | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Samsung       | 935XDB                      | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Jumper        | EZbook                      | [5e7336ee93](https://linux-hardware.org/?probe=5e7336ee93) | Jul 02, 2022 |
| Dell          | XPS 15 9520                 | [ca7efa311a](https://linux-hardware.org/?probe=ca7efa311a) | Jul 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [282d2ad16b](https://linux-hardware.org/?probe=282d2ad16b) | Jun 29, 2022 |
| ASUSTek       | X411UN                      | [d4543f64dc](https://linux-hardware.org/?probe=d4543f64dc) | Jun 24, 2022 |
| ASUSTek       | X411UN                      | [57e0198d3a](https://linux-hardware.org/?probe=57e0198d3a) | Jun 23, 2022 |
| Samsung       | 935XDB                      | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [5caa4002f1](https://linux-hardware.org/?probe=5caa4002f1) | Jun 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| Samsung       | 935XDB                      | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Dell          | Precision M4800             | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| Dell          | Latitude 9420               | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| HP            | EliteBook 840 G1            | [07b116767e](https://linux-hardware.org/?probe=07b116767e) | May 27, 2022 |
| Dell          | Latitude D520               | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| ASUSTek       | UX330UAK                    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | Stealth GS66 12UGS          | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| Dell          | Latitude E6520              | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| Packard Be... | EasyNote TK85               | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Dell          | Latitude E5440              | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| Dell          | Latitude E6430              | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| PC Special... | NH5xAx                      | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| Dell          | Latitude 9420               | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| ASUSTek       | GL753VE                     | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Dell          | Precision M4600             | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Acer          | Predator PH317-54           | [8fb9ac25be](https://linux-hardware.org/?probe=8fb9ac25be) | Feb 11, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Lenovo        | ThinkPad T480s 20L7S0VJ0... | [7535369bb0](https://linux-hardware.org/?probe=7535369bb0) | Jan 31, 2022 |
| Dell          | XPS 13 9310                 | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| Notebook      | P15SM                       | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Toshiba       | PORTEGE R830                | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| Dell          | Latitude 5411               | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291W99       | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| AVITA         | NS14A8                      | [0ae2523309](https://linux-hardware.org/?probe=0ae2523309) | Dec 18, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Acer          | AOD255                      | [eae98753db](https://linux-hardware.org/?probe=eae98753db) | Dec 03, 2021 |
| Acer          | AOD255                      | [d2e31c1441](https://linux-hardware.org/?probe=d2e31c1441) | Dec 02, 2021 |
| Acer          | Aspire A315-51              | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Sony          | VPCCB35FG                   | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| HP            | Laptop 17-cn0xxx            | [291a2a17e2](https://linux-hardware.org/?probe=291a2a17e2) | Nov 21, 2021 |
| Dell          | Inspiron MM061              | [0424bd331e](https://linux-hardware.org/?probe=0424bd331e) | Nov 10, 2021 |
| HP            | Notebook                    | [65c122fe69](https://linux-hardware.org/?probe=65c122fe69) | Oct 31, 2021 |
| Dell          | XPS 13 9310                 | [22bc284f45](https://linux-hardware.org/?probe=22bc284f45) | Oct 27, 2021 |
| Toshiba       | PORTEGE R830                | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | G550 2958                   | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| ASUSTek       | X501A1                      | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Toshiba       | PORTEGE R830                | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Acer          | Nitro AN515-45              | [f564d05797](https://linux-hardware.org/?probe=f564d05797) | Oct 05, 2021 |
| Apple         | MacBookPro5,3               | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| Timi          | TM1607                      | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| Apple         | MacBook6,1                  | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| HP            | Notebook                    | [9c7d616423](https://linux-hardware.org/?probe=9c7d616423) | Sep 12, 2021 |
| Lenovo        | V15-IIL 82C5                | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Dell          | Inspiron 3585               | [3a55618aee](https://linux-hardware.org/?probe=3a55618aee) | Sep 10, 2021 |
| Lenovo        | ThinkPad E15 20RD0015FR     | [8a229968ef](https://linux-hardware.org/?probe=8a229968ef) | Sep 06, 2021 |
| Samsung       | 550P5C/550P7C               | [c483c45fc4](https://linux-hardware.org/?probe=c483c45fc4) | Sep 03, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Toshiba       | Satellite A300              | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Dell          | Precision 5550              | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Medion        | Akoya E6239                 | [e22d5c4b21](https://linux-hardware.org/?probe=e22d5c4b21) | Aug 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Sony          | VPCCB35FG                   | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| Dell          | Inspiron 3583               | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Acer          | Swift SF313-53              | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Dell          | Studio XPS 1640             | [00d5936a25](https://linux-hardware.org/?probe=00d5936a25) | Jul 22, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [77ab0c578d](https://linux-hardware.org/?probe=77ab0c578d) | Jul 17, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [06ba47ee9a](https://linux-hardware.org/?probe=06ba47ee9a) | Jul 17, 2021 |
| Dell          | Latitude 7370               | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| Entroware     | Apollo                      | [3cbf412b11](https://linux-hardware.org/?probe=3cbf412b11) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [fff9c1a758](https://linux-hardware.org/?probe=fff9c1a758) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [3980434b64](https://linux-hardware.org/?probe=3980434b64) | Jun 19, 2021 |
| Dell          | Inspiron 1525               | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| Dell          | XPS 13 9300                 | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| Dell          | Latitude C810               | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Inspiron MM061              | [62b30f282d](https://linux-hardware.org/?probe=62b30f282d) | Jun 04, 2021 |
| Dell          | Latitude C810               | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | [6fff0f3407](https://linux-hardware.org/?probe=6fff0f3407) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | [cfa1b1a4fd](https://linux-hardware.org/?probe=cfa1b1a4fd) | Jun 03, 2021 |
| Dell          | Inspiron 1764               | [a41c941365](https://linux-hardware.org/?probe=a41c941365) | Jun 02, 2021 |
| Entroware     | Proteus                     | [0ecc547a14](https://linux-hardware.org/?probe=0ecc547a14) | May 31, 2021 |
| HP            | Pavilion 15                 | [14128860c2](https://linux-hardware.org/?probe=14128860c2) | May 27, 2021 |
| HP            | ProBook 6550b               | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | XPS 13 7390                 | [e7292a5491](https://linux-hardware.org/?probe=e7292a5491) | May 26, 2021 |
| HP            | Pavilion Notebook           | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 15                          | [ab211b6ad8](https://linux-hardware.org/?probe=ab211b6ad8) | May 21, 2021 |
| HP            | 15                          | [d285154a2b](https://linux-hardware.org/?probe=d285154a2b) | May 21, 2021 |
| Entroware     | Proteus                     | [98be1903c4](https://linux-hardware.org/?probe=98be1903c4) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | Latitude 5520               | [34c3dc01e9](https://linux-hardware.org/?probe=34c3dc01e9) | May 07, 2021 |
| HP            | HDX 18                      | [dead2b5b56](https://linux-hardware.org/?probe=dead2b5b56) | May 07, 2021 |
| HP            | EliteBook Folio G1          | [f3bdc3e991](https://linux-hardware.org/?probe=f3bdc3e991) | Apr 24, 2021 |
| Acer          | Aspire 5333                 | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| Lenovo        | V110-15ISK 80TL             | [9c0bbd0e0c](https://linux-hardware.org/?probe=9c0bbd0e0c) | Apr 18, 2021 |
| Acer          | Aspire 5333                 | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [51b67b480d](https://linux-hardware.org/?probe=51b67b480d) | Apr 05, 2021 |
| HP            | Pavilion g6                 | [726040b78b](https://linux-hardware.org/?probe=726040b78b) | Apr 03, 2021 |
| Acer          | Aspire 5920G                | [9976792f0f](https://linux-hardware.org/?probe=9976792f0f) | Mar 26, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | [31a4336d63](https://linux-hardware.org/?probe=31a4336d63) | Mar 25, 2021 |
| Microtech     | e-book Lite                 | [85b6d19466](https://linux-hardware.org/?probe=85b6d19466) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [488904f6d8](https://linux-hardware.org/?probe=488904f6d8) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [7fbf31af63](https://linux-hardware.org/?probe=7fbf31af63) | Mar 18, 2021 |
| ASUSTek       | X540LA                      | [8b0145ff0c](https://linux-hardware.org/?probe=8b0145ff0c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| Chuwi         | GemiBook Pro                | [f2f15e9ef1](https://linux-hardware.org/?probe=f2f15e9ef1) | Mar 10, 2021 |
| HP            | Pavilion m6                 | [578aad5ad5](https://linux-hardware.org/?probe=578aad5ad5) | Feb 24, 2021 |
| HP            | Notebook                    | [21ead6ec52](https://linux-hardware.org/?probe=21ead6ec52) | Feb 22, 2021 |
| Chuwi         | GemiBook Pro                | [7dbba6ee59](https://linux-hardware.org/?probe=7dbba6ee59) | Feb 21, 2021 |
| HP            | Compaq 6530b (GW688AV)      | [2812d098fd](https://linux-hardware.org/?probe=2812d098fd) | Feb 20, 2021 |
| HP            | Stream Laptop 11-y0XX       | [ce0aecd52b](https://linux-hardware.org/?probe=ce0aecd52b) | Feb 20, 2021 |
| HP            | EliteBook 745 G6            | [3bf39bac3e](https://linux-hardware.org/?probe=3bf39bac3e) | Feb 19, 2021 |
| Apple         | MacBookPro2,2               | [52f24b3228](https://linux-hardware.org/?probe=52f24b3228) | Feb 19, 2021 |
| Acer          | Aspire F5-573G              | [6fad2f0ade](https://linux-hardware.org/?probe=6fad2f0ade) | Feb 14, 2021 |
| Chuwi         | GemiBook Pro                | [46556ad380](https://linux-hardware.org/?probe=46556ad380) | Feb 14, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [ec083139fc](https://linux-hardware.org/?probe=ec083139fc) | Feb 05, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b1ed72b941](https://linux-hardware.org/?probe=b1ed72b941) | Feb 04, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo        | V110-15ISK 80TL             | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | System XPS L502X            | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| HUAWEI        | BOHL-WXX9                   | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Samsung       | N150/N210/N220              | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| Dell          | System XPS L502X            | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
| Acer          | Aspire 5551                 | [cb35dac70b](https://linux-hardware.org/?probe=cb35dac70b) | Dec 09, 2020 |
| HP            | Notebook                    | [2564f14d0b](https://linux-hardware.org/?probe=2564f14d0b) | Dec 06, 2020 |
| Lenovo        | G580 20157                  | [325dd21da3](https://linux-hardware.org/?probe=325dd21da3) | Nov 27, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [703167df7b](https://linux-hardware.org/?probe=703167df7b) | Nov 24, 2020 |
| Dell          | Inspiron 15-3567            | [04e06f0e3b](https://linux-hardware.org/?probe=04e06f0e3b) | Nov 23, 2020 |
| HP            | Presario V6500              | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Presario V6500              | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| HP            | EliteBook 8740w             | [f30611840c](https://linux-hardware.org/?probe=f30611840c) | Nov 23, 2020 |
| PC Special... | PCX0DX                      | [b4498047ef](https://linux-hardware.org/?probe=b4498047ef) | Nov 22, 2020 |
| Apple         | MacBookPro5,4               | [a7492067f0](https://linux-hardware.org/?probe=a7492067f0) | Nov 21, 2020 |
| HP            | EliteBook 820 G1            | [4db5c39f50](https://linux-hardware.org/?probe=4db5c39f50) | Nov 21, 2020 |
| Lenovo        | ThinkPad T400 64754G7       | [770660037c](https://linux-hardware.org/?probe=770660037c) | Nov 21, 2020 |
| HP            | EliteBook 8740w             | [072b557a79](https://linux-hardware.org/?probe=072b557a79) | Nov 20, 2020 |
| Lenovo        | G580 20157                  | [58fc01c757](https://linux-hardware.org/?probe=58fc01c757) | Nov 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [578d1badca](https://linux-hardware.org/?probe=578d1badca) | Nov 18, 2020 |
| Alienware     | 17 R4                       | [8b7402a4e7](https://linux-hardware.org/?probe=8b7402a4e7) | Nov 16, 2020 |
| Alienware     | 17 R4                       | [62e5ac4fd3](https://linux-hardware.org/?probe=62e5ac4fd3) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| Dell          | Latitude E6420              | [f542aafd19](https://linux-hardware.org/?probe=f542aafd19) | Nov 13, 2020 |
| Notebook      | NL40_50CU                   | [893477956d](https://linux-hardware.org/?probe=893477956d) | Nov 10, 2020 |
| Toshiba       | Satellite Pro R50-B         | [418e9ce805](https://linux-hardware.org/?probe=418e9ce805) | Nov 06, 2020 |
| Toshiba       | Satellite Pro R50-B         | [7780f8f320](https://linux-hardware.org/?probe=7780f8f320) | Nov 06, 2020 |
| System76      | Galago Pro                  | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| Dell          | XPS M1530                   | [bc52d9b9a4](https://linux-hardware.org/?probe=bc52d9b9a4) | Nov 03, 2020 |
| Medion        | E6239 MD99452               | [2496b738ac](https://linux-hardware.org/?probe=2496b738ac) | Oct 29, 2020 |
| Medion        | E6239 MD99452               | [f875a122f9](https://linux-hardware.org/?probe=f875a122f9) | Oct 29, 2020 |
| PC Special... | TF                          | [e651ccb88e](https://linux-hardware.org/?probe=e651ccb88e) | Oct 29, 2020 |
| HP            | ZBook 15 G2                 | [0b113f8315](https://linux-hardware.org/?probe=0b113f8315) | Oct 29, 2020 |
| PC Special... | TF                          | [ba278ca133](https://linux-hardware.org/?probe=ba278ca133) | Oct 29, 2020 |
| HP            | Laptop 14-bs0xx             | [0e16f54971](https://linux-hardware.org/?probe=0e16f54971) | Oct 28, 2020 |
| Toshiba       | Satellite C50-B             | [0edec7c57f](https://linux-hardware.org/?probe=0edec7c57f) | Oct 27, 2020 |
| Toshiba       | Satellite C50-B             | [21e26c80bc](https://linux-hardware.org/?probe=21e26c80bc) | Oct 27, 2020 |
| Dell          | Vostro 3700                 | [5493bcf45a](https://linux-hardware.org/?probe=5493bcf45a) | Oct 26, 2020 |
| ASUSTek       | E200HA                      | [2db5bc3b28](https://linux-hardware.org/?probe=2db5bc3b28) | Oct 23, 2020 |
| ASUSTek       | E200HA                      | [acc7a651ac](https://linux-hardware.org/?probe=acc7a651ac) | Oct 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v5      | [6aea9a482c](https://linux-hardware.org/?probe=6aea9a482c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [96ff229c4c](https://linux-hardware.org/?probe=96ff229c4c) | Oct 17, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| Apple         | MacBook5,1                  | [598a9af3a1](https://linux-hardware.org/?probe=598a9af3a1) | Oct 12, 2020 |
| Dell          | XPS 13 9360                 | [1554f3d77d](https://linux-hardware.org/?probe=1554f3d77d) | Oct 05, 2020 |
| Toshiba       | Satellite L50-B             | [58ce88778b](https://linux-hardware.org/?probe=58ce88778b) | Sep 23, 2020 |
| HP            | G70                         | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| Apple         | MacBookPro12,1              | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| HP            | 255 G2                      | [5d06b6eeff](https://linux-hardware.org/?probe=5d06b6eeff) | Sep 04, 2020 |
| Lenovo        | U410                        | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| HP            | Laptop 14-bs0xx             | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| Acer          | Aspire 5349                 | [fdae61b8d4](https://linux-hardware.org/?probe=fdae61b8d4) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | [d702543fbb](https://linux-hardware.org/?probe=d702543fbb) | Aug 06, 2020 |
| Dell          | Latitude E7450              | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| PC Special... | N150CU                      | [6d19fc4569](https://linux-hardware.org/?probe=6d19fc4569) | Aug 01, 2020 |
| Lenovo        | ThinkPad T430 2349KB4       | [291151dae1](https://linux-hardware.org/?probe=291151dae1) | Jul 31, 2020 |
| MSI           | WS65 9TK                    | [e9feed814f](https://linux-hardware.org/?probe=e9feed814f) | Jul 29, 2020 |
| MSI           | WS65 9TK                    | [b296acb26a](https://linux-hardware.org/?probe=b296acb26a) | Jul 29, 2020 |
| HP            | Pavilion dm1                | [cc8ed632dc](https://linux-hardware.org/?probe=cc8ed632dc) | Jul 25, 2020 |
| Dell          | Latitude 5480               | [e06096d959](https://linux-hardware.org/?probe=e06096d959) | Jul 24, 2020 |
| Lenovo        | V110-15ISK 80TL             | [a8709e5362](https://linux-hardware.org/?probe=a8709e5362) | Jul 23, 2020 |
| Lenovo        | IdeaPad Y500 9541           | [bdf2ff973b](https://linux-hardware.org/?probe=bdf2ff973b) | Jul 20, 2020 |
| Dell          | Latitude 5400               | [11473792e0](https://linux-hardware.org/?probe=11473792e0) | Jul 19, 2020 |
| HP            | 255 G2                      | [6801725bae](https://linux-hardware.org/?probe=6801725bae) | Jul 17, 2020 |
| HP            | 255 G2                      | [7319f8f1b3](https://linux-hardware.org/?probe=7319f8f1b3) | Jul 17, 2020 |
| HP            | 255 G2                      | [d1dea15553](https://linux-hardware.org/?probe=d1dea15553) | Jul 16, 2020 |
| Lenovo        | G500 VIWGP                  | [37286d3145](https://linux-hardware.org/?probe=37286d3145) | Jul 08, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Apple         | MacBookPro8,3               | [2a16561ffa](https://linux-hardware.org/?probe=2a16561ffa) | Jun 28, 2020 |
| Apple         | MacBookPro8,3               | [8ba0fcfe7c](https://linux-hardware.org/?probe=8ba0fcfe7c) | Jun 28, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [a36f83366b](https://linux-hardware.org/?probe=a36f83366b) | Jun 21, 2020 |
| Dell          | Inspiron 15-3552            | [168dcc66c7](https://linux-hardware.org/?probe=168dcc66c7) | Jun 17, 2020 |
| Timi          | TM1703                      | [d3d89dc21d](https://linux-hardware.org/?probe=d3d89dc21d) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [1cfb078c4e](https://linux-hardware.org/?probe=1cfb078c4e) | Jun 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [18230e354a](https://linux-hardware.org/?probe=18230e354a) | Jun 13, 2020 |
| SLIMBOOK      | PROX15                      | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| ASUSTek       | G750JW                      | [cc02e1e15c](https://linux-hardware.org/?probe=cc02e1e15c) | Jun 10, 2020 |
| Dell          | Latitude E5420              | [eb3a4e918a](https://linux-hardware.org/?probe=eb3a4e918a) | Jun 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34431... | [c5d45645b7](https://linux-hardware.org/?probe=c5d45645b7) | Jun 01, 2020 |
| Acer          | Aspire V3-571G              | [fbef0c90d4](https://linux-hardware.org/?probe=fbef0c90d4) | May 28, 2020 |
| Lenovo        | ThinkPad T410s 2904HDU      | [b1eb7716ed](https://linux-hardware.org/?probe=b1eb7716ed) | May 26, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| HP            | Presario CQ61               | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| Chuwi         | LapBook SE                  | [c144d3a1bc](https://linux-hardware.org/?probe=c144d3a1bc) | May 24, 2020 |
| Lenovo        | V145-15AST 81MT             | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| Dell          | Vostro 5490                 | [9000fa541e](https://linux-hardware.org/?probe=9000fa541e) | May 18, 2020 |
| Dell          | Latitude E5420              | [5519dbffbc](https://linux-hardware.org/?probe=5519dbffbc) | May 18, 2020 |
| Lenovo        | ThinkPad T520 424329U       | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| System76      | Galago Pro                  | [3ae6d02922](https://linux-hardware.org/?probe=3ae6d02922) | May 14, 2020 |
| HP            | EliteBook 8560w             | [f05f9404d0](https://linux-hardware.org/?probe=f05f9404d0) | May 11, 2020 |
| Gigabyte      | P15FV7                      | [a7031c2684](https://linux-hardware.org/?probe=a7031c2684) | May 09, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Dell          | Latitude E7240              | [6f9d4efc51](https://linux-hardware.org/?probe=6f9d4efc51) | May 06, 2020 |
| Dell          | Latitude E7240              | [9e5819a0bc](https://linux-hardware.org/?probe=9e5819a0bc) | May 06, 2020 |
| Acer          | Okinawa                     | [9e22849a3a](https://linux-hardware.org/?probe=9e22849a3a) | May 03, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e356fece67](https://linux-hardware.org/?probe=e356fece67) | May 01, 2020 |
| Dell          | XPS M1530                   | [ef2ddf50e9](https://linux-hardware.org/?probe=ef2ddf50e9) | Apr 28, 2020 |
| Dell          | XPS M1530                   | [9d8053a9f5](https://linux-hardware.org/?probe=9d8053a9f5) | Apr 28, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | [e6010acabe](https://linux-hardware.org/?probe=e6010acabe) | Apr 28, 2020 |
| Dell          | Precision 7510              | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Dell          | Latitude E5570              | [4c46b3c18d](https://linux-hardware.org/?probe=4c46b3c18d) | Apr 27, 2020 |
| Dell          | XPS 13 9300                 | [9b6c98e396](https://linux-hardware.org/?probe=9b6c98e396) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | [0d9716a2e8](https://linux-hardware.org/?probe=0d9716a2e8) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | [951197ee19](https://linux-hardware.org/?probe=951197ee19) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | [64015bca38](https://linux-hardware.org/?probe=64015bca38) | Apr 24, 2020 |
| Acer          | Aspire 7741                 | [85a10d5a0c](https://linux-hardware.org/?probe=85a10d5a0c) | Apr 24, 2020 |
| Dell          | XPS M1530                   | [0d21d60816](https://linux-hardware.org/?probe=0d21d60816) | Apr 22, 2020 |
| HP            | Presario F500 (GH835EA#A... | [9e0244765a](https://linux-hardware.org/?probe=9e0244765a) | Apr 21, 2020 |
| Medion        | Erazer X7843 MD99945        | [f63ebecfac](https://linux-hardware.org/?probe=f63ebecfac) | Apr 20, 2020 |
| Medion        | Erazer X7843 MD99945        | [caa46f1899](https://linux-hardware.org/?probe=caa46f1899) | Apr 20, 2020 |
| Dell          | Latitude E5450              | [a0de4692f3](https://linux-hardware.org/?probe=a0de4692f3) | Apr 12, 2020 |
| Dell          | Latitude E5450              | [b934bac9f3](https://linux-hardware.org/?probe=b934bac9f3) | Apr 12, 2020 |
| Apple         | MacBook6,1                  | [7eae555356](https://linux-hardware.org/?probe=7eae555356) | Apr 11, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [75cee4eeef](https://linux-hardware.org/?probe=75cee4eeef) | Apr 08, 2020 |
| eMachines     | E627                        | [395c0dace2](https://linux-hardware.org/?probe=395c0dace2) | Apr 07, 2020 |
| Dell          | XPS M1530                   | [daf947b1f0](https://linux-hardware.org/?probe=daf947b1f0) | Apr 07, 2020 |
| HP            | Pavilion dv6                | [5ae586911d](https://linux-hardware.org/?probe=5ae586911d) | Apr 05, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4151ed01a0](https://linux-hardware.org/?probe=4151ed01a0) | Apr 01, 2020 |
| HP            | EliteBook 2560p             | [1b7dfeda09](https://linux-hardware.org/?probe=1b7dfeda09) | Mar 30, 2020 |
| HP            | EliteBook 2560p             | [c32ad7e810](https://linux-hardware.org/?probe=c32ad7e810) | Mar 30, 2020 |
| ASUSTek       | X550CC                      | [9d50122997](https://linux-hardware.org/?probe=9d50122997) | Mar 30, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | [b2b7dfbc87](https://linux-hardware.org/?probe=b2b7dfbc87) | Mar 29, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [ec4f08053a](https://linux-hardware.org/?probe=ec4f08053a) | Mar 23, 2020 |
| Dell          | Inspiron 13-5378            | [087223b15f](https://linux-hardware.org/?probe=087223b15f) | Mar 20, 2020 |
| Dell          | Inspiron 13-5378            | [9225b58c75](https://linux-hardware.org/?probe=9225b58c75) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | [1287493f4e](https://linux-hardware.org/?probe=1287493f4e) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | [989982faa3](https://linux-hardware.org/?probe=989982faa3) | Mar 18, 2020 |
| Dell          | Precision M6300             | [6e9681a74e](https://linux-hardware.org/?probe=6e9681a74e) | Feb 18, 2020 |
| Dell          | Precision M6300             | [e45c0c7fc9](https://linux-hardware.org/?probe=e45c0c7fc9) | Feb 18, 2020 |
| Dell          | Inspiron 13-5378            | [46dd15e54f](https://linux-hardware.org/?probe=46dd15e54f) | Feb 18, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | [b7a710c050](https://linux-hardware.org/?probe=b7a710c050) | Feb 10, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | E402BA                      | [ef0178479b](https://linux-hardware.org/?probe=ef0178479b) | Feb 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | [51d20a3d12](https://linux-hardware.org/?probe=51d20a3d12) | Feb 06, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [917f6c18a4](https://linux-hardware.org/?probe=917f6c18a4) | Feb 05, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8143d2c859](https://linux-hardware.org/?probe=8143d2c859) | Dec 23, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [efc1ac12c7](https://linux-hardware.org/?probe=efc1ac12c7) | Dec 21, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [0f6f830f1b](https://linux-hardware.org/?probe=0f6f830f1b) | Dec 21, 2019 |
| Acer          | Aspire 8930                 | [3bd04b5cd7](https://linux-hardware.org/?probe=3bd04b5cd7) | Dec 09, 2019 |
| Lenovo        | ThinkPad T410 2539W4Y       | [009c5c142e](https://linux-hardware.org/?probe=009c5c142e) | Dec 06, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [706aee4776](https://linux-hardware.org/?probe=706aee4776) | Dec 04, 2019 |
| Apple         | MacBookPro5,2               | [3b3fd20d67](https://linux-hardware.org/?probe=3b3fd20d67) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | [4918587a5c](https://linux-hardware.org/?probe=4918587a5c) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | [0ef52aaec2](https://linux-hardware.org/?probe=0ef52aaec2) | Dec 01, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [187a7265f0](https://linux-hardware.org/?probe=187a7265f0) | Dec 01, 2019 |
| System76      | Galago Pro                  | [15393d43e8](https://linux-hardware.org/?probe=15393d43e8) | Nov 25, 2019 |
| Dell          | Latitude 7490               | [4c5f40f7f3](https://linux-hardware.org/?probe=4c5f40f7f3) | Oct 18, 2019 |
| System76      | Galago Pro                  | [463dd28c7d](https://linux-hardware.org/?probe=463dd28c7d) | Oct 17, 2019 |
| Acer          | Aspire 5736Z                | [5ba5b7d13a](https://linux-hardware.org/?probe=5ba5b7d13a) | Oct 17, 2019 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [a2da44ce3d](https://linux-hardware.org/?probe=a2da44ce3d) | Oct 15, 2019 |
| Alienware     | 17 R4                       | [fa39f4bdb4](https://linux-hardware.org/?probe=fa39f4bdb4) | Oct 04, 2019 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [b17cca251b](https://linux-hardware.org/?probe=b17cca251b) | Sep 30, 2019 |
| System76      | Galago Pro                  | [8122dc5996](https://linux-hardware.org/?probe=8122dc5996) | Sep 25, 2019 |
| Alienware     | 17 R4                       | [5287c00902](https://linux-hardware.org/?probe=5287c00902) | Sep 15, 2019 |
| System76      | Galago Pro                  | [7c1dbad22c](https://linux-hardware.org/?probe=7c1dbad22c) | Sep 11, 2019 |
| Acer          | Aspire ES1-512              | [6b82a86df6](https://linux-hardware.org/?probe=6b82a86df6) | Sep 08, 2019 |
| Lenovo        | V145-15AST 81MT             | [e5fc9849a0](https://linux-hardware.org/?probe=e5fc9849a0) | Aug 30, 2019 |
| Acer          | Aspire ES1-512              | [11727f9491](https://linux-hardware.org/?probe=11727f9491) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | [6a08c4afd1](https://linux-hardware.org/?probe=6a08c4afd1) | Aug 17, 2019 |
| Toshiba       | Satellite L500              | [5819f81be3](https://linux-hardware.org/?probe=5819f81be3) | Aug 16, 2019 |
| Acer          | Aspire E1-572               | [96bf232f30](https://linux-hardware.org/?probe=96bf232f30) | Aug 03, 2019 |
| Advent        | Roma                        | [a7ec10f5ee](https://linux-hardware.org/?probe=a7ec10f5ee) | Jul 21, 2019 |
| System76      | Bonobo Extreme              | [aa49d07bb2](https://linux-hardware.org/?probe=aa49d07bb2) | Jul 05, 2019 |
| System76      | Bonobo Extreme              | [f867ec3a39](https://linux-hardware.org/?probe=f867ec3a39) | Jul 05, 2019 |
| Toshiba       | TECRA R850                  | [4398e73607](https://linux-hardware.org/?probe=4398e73607) | Jul 04, 2019 |
| HP            | Pavilion dv6                | [6cfff2060e](https://linux-hardware.org/?probe=6cfff2060e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | [90df3b230e](https://linux-hardware.org/?probe=90df3b230e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | [694239801c](https://linux-hardware.org/?probe=694239801c) | Jun 16, 2019 |
| Toshiba       | Satellite L500              | [7fcd49c923](https://linux-hardware.org/?probe=7fcd49c923) | Jun 08, 2019 |
| ASUSTek       | S550CA                      | [469e04e0d5](https://linux-hardware.org/?probe=469e04e0d5) | May 26, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | [a151a65fee](https://linux-hardware.org/?probe=a151a65fee) | May 21, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | [ba564750a2](https://linux-hardware.org/?probe=ba564750a2) | May 21, 2019 |
| ASUSTek       | K53U                        | [24a0045ecc](https://linux-hardware.org/?probe=24a0045ecc) | May 18, 2019 |
| ASUSTek       | K53U                        | [0f7bf61a9d](https://linux-hardware.org/?probe=0f7bf61a9d) | May 17, 2019 |
| ASUSTek       | S550CA                      | [afe6d9bfe2](https://linux-hardware.org/?probe=afe6d9bfe2) | Apr 28, 2019 |
| ASUSTek       | T100TA                      | [5025b4af94](https://linux-hardware.org/?probe=5025b4af94) | Apr 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S1G40L    | [47b05c165f](https://linux-hardware.org/?probe=47b05c165f) | Apr 24, 2019 |
| Toshiba       | Satellite L50-C             | [ffca1399e5](https://linux-hardware.org/?probe=ffca1399e5) | Apr 17, 2019 |
| Dell          | Inspiron ME051              | [6d096d9aa6](https://linux-hardware.org/?probe=6d096d9aa6) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | [a41940bc7f](https://linux-hardware.org/?probe=a41940bc7f) | Mar 30, 2019 |
| eMachines     | eM350                       | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Dell          | Latitude E6400              | [75df21c3fd](https://linux-hardware.org/?probe=75df21c3fd) | Jan 25, 2019 |
| Toshiba       | Satellite Pro C660          | [9b641633c5](https://linux-hardware.org/?probe=9b641633c5) | Nov 17, 2018 |
| Acer          | Swift SF114-31              | [96142e3044](https://linux-hardware.org/?probe=96142e3044) | Nov 01, 2018 |
| Dell          | Latitude E6230              | [889c4720de](https://linux-hardware.org/?probe=889c4720de) | Mar 31, 2018 |
| Acer          | Aspire E5-575G              | [5d4b293327](https://linux-hardware.org/?probe=5d4b293327) | Feb 07, 2018 |
| Dell          | Latitude E6230              | [70a07251da](https://linux-hardware.org/?probe=70a07251da) | Oct 21, 2017 |
| Dell          | Latitude D620               | [6652d3973b](https://linux-hardware.org/?probe=6652d3973b) | Sep 28, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ireland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 51        | 7.91%   |
| Ubuntu 22.04       | 35        | 5.43%   |
| Ubuntu 18.04       | 29        | 4.5%    |
| Pop!_OS 22.04      | 22        | 3.41%   |
| Debian 11          | 15        | 2.33%   |
| Zorin 17           | 13        | 2.02%   |
| Ubuntu 24.04       | 13        | 2.02%   |
| Debian 12          | 12        | 1.86%   |
| Arch Rolling       | 12        | 1.86%   |
| Zorin 16           | 11        | 1.71%   |
| Fedora 40          | 11        | 1.71%   |
| Linux Mint 21.1    | 10        | 1.55%   |
| Fedora 42          | 9         | 1.4%    |
| Linux Mint 21.3    | 8         | 1.24%   |
| Linux Mint 21.2    | 8         | 1.24%   |
| Fedora 38          | 8         | 1.24%   |
| Manjaro            | 7         | 1.09%   |
| Fedora 39          | 7         | 1.09%   |
| Fedora 36          | 7         | 1.09%   |
| Debian 10          | 7         | 1.09%   |
| Ubuntu 23.04       | 6         | 0.93%   |
| OpenMandriva 4.2   | 6         | 0.93%   |
| OpenMandriva 24.12 | 6         | 0.93%   |
| OpenMandriva 23.01 | 6         | 0.93%   |
| Linux Mint 21      | 6         | 0.93%   |
| Linux Mint 20.3    | 6         | 0.93%   |
| Linux Mint 20      | 6         | 0.93%   |
| BlackPanther 22.1  | 6         | 0.93%   |
| Ubuntu 22.10       | 5         | 0.78%   |
| Ubuntu 19.10       | 5         | 0.78%   |
| Linux Mint 22      | 5         | 0.78%   |
| Linux Mint 20.2    | 5         | 0.78%   |
| Kubuntu 20.04      | 5         | 0.78%   |
| KDE neon 20.04     | 5         | 0.78%   |
| Fedora 37          | 5         | 0.78%   |
| ArcoLinux Rolling  | 5         | 0.78%   |
| Ubuntu 21.10       | 4         | 0.62%   |
| Ubuntu 19.04       | 4         | 0.62%   |
| Pop!_OS 21.10      | 4         | 0.62%   |
| Pop!_OS 20.04      | 4         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 157       | 25.74%  |
| Linux Mint    | 68        | 11.15%  |
| Fedora        | 61        | 10%     |
| Debian        | 44        | 7.21%   |
| OpenMandriva  | 43        | 7.05%   |
| Pop!_OS       | 34        | 5.57%   |
| Zorin         | 30        | 4.92%   |
| Manjaro       | 17        | 2.79%   |
| Kubuntu       | 16        | 2.62%   |
| Arch          | 16        | 2.62%   |
| BlackPanther  | 10        | 1.64%   |
| SteamOS       | 9         | 1.48%   |
| KDE neon      | 8         | 1.31%   |
| Elementary    | 8         | 1.31%   |
| Lubuntu       | 7         | 1.15%   |
| ROSA          | 6         | 0.98%   |
| Ubuntu Budgie | 5         | 0.82%   |
| openSUSE      | 5         | 0.82%   |
| MX            | 5         | 0.82%   |
| ArcoLinux     | 5         | 0.82%   |
| Xubuntu       | 4         | 0.66%   |
| Ubuntu MATE   | 4         | 0.66%   |
| LMDE          | 4         | 0.66%   |
| Endless       | 4         | 0.66%   |
| EndeavourOS   | 4         | 0.66%   |
| Ubuntu Unity  | 3         | 0.49%   |
| CentOS        | 3         | 0.49%   |
| CachyOS       | 3         | 0.49%   |
| Bazzite       | 3         | 0.49%   |
| Rocky Linux   | 2         | 0.33%   |
| RHEL          | 2         | 0.33%   |
| Parrot        | 2         | 0.33%   |
| Kali          | 2         | 0.33%   |
| Gentoo        | 2         | 0.33%   |
| Clear Linux   | 2         | 0.33%   |
| Xero          | 1         | 0.16%   |
| Ubuntu Studio | 1         | 0.16%   |
| Redcore       | 1         | 0.16%   |
| Reborn OS     | 1         | 0.16%   |
| Peppermint    | 1         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.3.0-46-generic                    | 8         | 1.16%   |
| 6.14.2-desktop-3omv2590             | 6         | 0.87%   |
| 6.1.1-desktop-1omv2290              | 6         | 0.87%   |
| 5.4.0-42-generic                    | 6         | 0.87%   |
| 5.15.0-91-generic                   | 6         | 0.87%   |
| 5.10.14-desktop-1omv4002            | 6         | 0.87%   |
| 6.9.3-76060903-generic              | 5         | 0.72%   |
| 6.8.0-51-generic                    | 5         | 0.72%   |
| 6.12.9-desktop-1omv2490             | 5         | 0.72%   |
| 5.4.0-52-generic                    | 5         | 0.72%   |
| 5.19.0-35-generic                   | 5         | 0.72%   |
| 5.15.0-67-generic                   | 5         | 0.72%   |
| 5.15.0-56-generic                   | 5         | 0.72%   |
| 5.15.0-52-generic                   | 5         | 0.72%   |
| 5.15.0-46-generic                   | 5         | 0.72%   |
| 6.8.0-88-generic                    | 4         | 0.58%   |
| 6.8.0-52-generic                    | 4         | 0.58%   |
| 6.6.32-power-1bP                    | 4         | 0.58%   |
| 6.4.11-desktop-1omv2390             | 4         | 0.58%   |
| 6.2.0-39-generic                    | 4         | 0.58%   |
| 6.2.0-36-generic                    | 4         | 0.58%   |
| 5.4.0-26-generic                    | 4         | 0.58%   |
| 5.15.0-48-generic                   | 4         | 0.58%   |
| 6.8.0-76060800daily20240311-generic | 3         | 0.43%   |
| 6.8.0-65-generic                    | 3         | 0.43%   |
| 6.5.0-35-generic                    | 3         | 0.43%   |
| 6.2.6-desktop-1omv2390              | 3         | 0.43%   |
| 6.2.0-26-generic                    | 3         | 0.43%   |
| 6.14.0-36-generic                   | 3         | 0.43%   |
| 6.12.10-76061203-generic            | 3         | 0.43%   |
| 6.12.1-desktop-1omv2490             | 3         | 0.43%   |
| 6.11.0-13-generic                   | 3         | 0.43%   |
| 5.4.0-72-generic                    | 3         | 0.43%   |
| 5.4.0-31-generic                    | 3         | 0.43%   |
| 5.4.0-29-generic                    | 3         | 0.43%   |
| 5.19.0-32-generic                   | 3         | 0.43%   |
| 5.15.0-40-generic                   | 3         | 0.43%   |
| 5.11.0-27-generic                   | 3         | 0.43%   |
| 5.11.0-25-generic                   | 3         | 0.43%   |
| 5.10.0-8-amd64                      | 3         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 75        | 11.56%  |
| 5.15.0  | 56        | 8.63%   |
| 6.8.0   | 38        | 5.86%   |
| 5.19.0  | 23        | 3.54%   |
| 4.15.0  | 23        | 3.54%   |
| 6.5.0   | 19        | 2.93%   |
| 6.2.0   | 19        | 2.93%   |
| 5.11.0  | 18        | 2.77%   |
| 5.3.0   | 17        | 2.62%   |
| 6.1.0   | 16        | 2.47%   |
| 5.10.0  | 16        | 2.47%   |
| 5.8.0   | 15        | 2.31%   |
| 5.13.0  | 14        | 2.16%   |
| 6.14.0  | 13        | 2%      |
| 5.0.0   | 8         | 1.23%   |
| 4.19.0  | 8         | 1.23%   |
| 6.9.3   | 6         | 0.92%   |
| 6.14.2  | 6         | 0.92%   |
| 6.12.9  | 6         | 0.92%   |
| 6.1.1   | 6         | 0.92%   |
| 5.10.14 | 6         | 0.92%   |
| 5.14.0  | 5         | 0.77%   |
| 4.18.0  | 5         | 0.77%   |
| 6.6.32  | 4         | 0.62%   |
| 6.4.11  | 4         | 0.62%   |
| 6.3.8   | 4         | 0.62%   |
| 6.2.6   | 4         | 0.62%   |
| 6.11.0  | 4         | 0.62%   |
| 6.1.52  | 4         | 0.62%   |
| 6.5.6   | 3         | 0.46%   |
| 6.18.2  | 3         | 0.46%   |
| 6.16.3  | 3         | 0.46%   |
| 6.12.6  | 3         | 0.46%   |
| 6.12.10 | 3         | 0.46%   |
| 6.12.1  | 3         | 0.46%   |
| 6.0.0   | 3         | 0.46%   |
| 5.18.0  | 3         | 0.46%   |
| 4.18.16 | 3         | 0.46%   |
| 6.9.12  | 2         | 0.31%   |
| 6.8.11  | 2         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 78        | 12.07%  |
| 5.15    | 63        | 9.75%   |
| 6.8     | 45        | 6.97%   |
| 5.10    | 29        | 4.49%   |
| 6.1     | 28        | 4.33%   |
| 5.19    | 28        | 4.33%   |
| 6.5     | 26        | 4.02%   |
| 6.2     | 26        | 4.02%   |
| 6.14    | 24        | 3.72%   |
| 4.15    | 23        | 3.56%   |
| 6.12    | 20        | 3.1%    |
| 5.3     | 18        | 2.79%   |
| 5.11    | 18        | 2.79%   |
| 5.8     | 17        | 2.63%   |
| 5.13    | 16        | 2.48%   |
| 6.6     | 14        | 2.17%   |
| 6.0     | 14        | 2.17%   |
| 6.9     | 12        | 1.86%   |
| 5.14    | 10        | 1.55%   |
| 4.19    | 10        | 1.55%   |
| 6.16    | 9         | 1.39%   |
| 6.11    | 8         | 1.24%   |
| 5.0     | 8         | 1.24%   |
| 4.18    | 8         | 1.24%   |
| 6.4     | 7         | 1.08%   |
| 6.3     | 7         | 1.08%   |
| 6.10    | 7         | 1.08%   |
| 5.6     | 7         | 1.08%   |
| 5.18    | 7         | 1.08%   |
| 6.17    | 6         | 0.93%   |
| 5.17    | 6         | 0.93%   |
| 5.16    | 6         | 0.93%   |
| 6.13    | 5         | 0.77%   |
| 4.9     | 5         | 0.77%   |
| 6.7     | 4         | 0.62%   |
| 5.9     | 4         | 0.62%   |
| 5.7     | 4         | 0.62%   |
| 5.12    | 4         | 0.62%   |
| 6.18    | 3         | 0.46%   |
| 6.15    | 3         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 571       | 97.77%  |
| i686   | 12        | 2.05%   |
| armv7l | 1         | 0.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 281       | 45.92%  |
| KDE5            | 82        | 13.4%   |
| X-Cinnamon      | 58        | 9.48%   |
| Unknown         | 56        | 9.15%   |
| XFCE            | 38        | 6.21%   |
| KDE6            | 32        | 5.23%   |
| KDE             | 11        | 1.8%    |
| Pantheon        | 8         | 1.31%   |
| MATE            | 8         | 1.31%   |
| LXQt            | 7         | 1.14%   |
| i3              | 6         | 0.98%   |
| Cinnamon        | 6         | 0.98%   |
| Budgie          | 5         | 0.82%   |
| Unity           | 3         | 0.49%   |
| KDE4            | 2         | 0.33%   |
| Hyprland        | 2         | 0.33%   |
| GNOME Classic   | 2         | 0.33%   |
| GNOME Flashback | 1         | 0.16%   |
| Endless:GNOME   | 1         | 0.16%   |
| DWM             | 1         | 0.16%   |
| COSMIC          | 1         | 0.16%   |
| BunsenLabs      | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 409       | 67.83%  |
| Wayland | 160       | 26.53%  |
| Unknown | 25        | 4.15%   |
| Tty     | 9         | 1.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 276       | 45.62%  |
| SDDM           | 91        | 15.04%  |
| LightDM        | 79        | 13.06%  |
| GDM3           | 78        | 12.89%  |
| GDM            | 64        | 10.58%  |
| TDM            | 12        | 1.98%   |
| KDM            | 2         | 0.33%   |
| SLiM           | 1         | 0.17%   |
| Ly             | 1         | 0.17%   |
| COSMIC-GREETER | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_IE      | 281       | 46.22%  |
| en_US      | 118       | 19.41%  |
| en_GB      | 118       | 19.41%  |
| Unknown    | 42        | 6.91%   |
| pl_PL      | 14        | 2.3%    |
| C          | 8         | 1.32%   |
| hu_HU      | 3         | 0.49%   |
| uk_UA      | 2         | 0.33%   |
| ru_RU      | 2         | 0.33%   |
| fr_FR      | 2         | 0.33%   |
| en_IN      | 2         | 0.33%   |
| en_CA      | 2         | 0.33%   |
| bg_BG      | 2         | 0.33%   |
| zh_CN      | 1         | 0.16%   |
| pt_PT      | 1         | 0.16%   |
| lt_LT      | 1         | 0.16%   |
| it_IT      | 1         | 0.16%   |
| ga_IE.UTF8 | 1         | 0.16%   |
| ga_IE      | 1         | 0.16%   |
| fr_BE      | 1         | 0.16%   |
| es_ES      | 1         | 0.16%   |
| en_ZA      | 1         | 0.16%   |
| en_DE      | 1         | 0.16%   |
| en_AU      | 1         | 0.16%   |
| de_DE      | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 312       | 52.35%  |
| BIOS | 284       | 47.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 409       | 67.94%  |
| Btrfs               | 95        | 15.78%  |
| Overlay             | 38        | 6.31%   |
| Tmpfs               | 24        | 3.99%   |
| Unknown             | 14        | 2.33%   |
| Xfs                 | 11        | 1.83%   |
| Zfs                 | 5         | 0.83%   |
| Ext3                | 2         | 0.33%   |
| Ext2                | 2         | 0.33%   |
| Rootfs              | 1         | 0.17%   |
| Fuse.fuse-overlayfs | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 277       | 46.32%  |
| GPT     | 266       | 44.48%  |
| MBR     | 55        | 9.2%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 525       | 88.53%  |
| Yes       | 68        | 11.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 475       | 80.1%   |
| Yes       | 118       | 19.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 143       | 24.49%  |
| Dell                | 138       | 23.63%  |
| Hewlett-Packard     | 74        | 12.67%  |
| ASUSTek Computer    | 47        | 8.05%   |
| Acer                | 37        | 6.34%   |
| Apple               | 18        | 3.08%   |
| Toshiba             | 16        | 2.74%   |
| Samsung Electronics | 11        | 1.88%   |
| Valve               | 8         | 1.37%   |
| MSI                 | 7         | 1.2%    |
| Google              | 7         | 1.2%    |
| System76            | 5         | 0.86%   |
| PC Specialist       | 5         | 0.86%   |
| Notebook            | 5         | 0.86%   |
| Medion              | 5         | 0.86%   |
| HUAWEI              | 5         | 0.86%   |
| Chuwi               | 5         | 0.86%   |
| TUXEDO              | 4         | 0.68%   |
| Timi                | 4         | 0.68%   |
| Packard Bell        | 4         | 0.68%   |
| Framework           | 4         | 0.68%   |
| Alienware           | 4         | 0.68%   |
| Fujitsu             | 3         | 0.51%   |
| AVITA               | 3         | 0.51%   |
| Schenker            | 2         | 0.34%   |
| Fujitsu Siemens     | 2         | 0.34%   |
| Entroware           | 2         | 0.34%   |
| eMachines           | 2         | 0.34%   |
| TongFang            | 1         | 0.17%   |
| Tactus              | 1         | 0.17%   |
| Star Labs           | 1         | 0.17%   |
| Sony                | 1         | 0.17%   |
| SLIMBOOK            | 1         | 0.17%   |
| Novatech            | 1         | 0.17%   |
| Microtech           | 1         | 0.17%   |
| Linx                | 1         | 0.17%   |
| Jumper              | 1         | 0.17%   |
| Gigabyte Technology | 1         | 0.17%   |
| Dynabook            | 1         | 0.17%   |
| AZW                 | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Dell Latitude 7420                | 8         | 1.37%   |
| Valve Jupiter                     | 7         | 1.2%    |
| Lenovo IdeaPad 330-15IKB 81DE     | 6         | 1.03%   |
| Dell Latitude E7240               | 4         | 0.68%   |
| Dell Latitude 5480                | 4         | 0.68%   |
| Lenovo V145-15AST 81MT            | 3         | 0.51%   |
| HP Pavilion Laptop 15-eh0xxx      | 3         | 0.51%   |
| HP Notebook                       | 3         | 0.51%   |
| Dell XPS 9320                     | 3         | 0.51%   |
| Dell Latitude E5420               | 3         | 0.51%   |
| Dell Inspiron 13-5378             | 3         | 0.51%   |
| TUXEDO Pulse 15 Gen1              | 2         | 0.34%   |
| Toshiba Satellite C50-B           | 2         | 0.34%   |
| Samsung 750XED                    | 2         | 0.34%   |
| MSI Stealth GS66 12UGS            | 2         | 0.34%   |
| Medion Akoya E6239                | 2         | 0.34%   |
| Lenovo ThinkPad X1 Carbon 3443CTO | 2         | 0.34%   |
| Lenovo IdeaPad Slim 3 14IAH8 83EQ | 2         | 0.34%   |
| Lenovo IdeaPad S340-15API 81NC    | 2         | 0.34%   |
| Lenovo IdeaPad 510-15ISK 80SR     | 2         | 0.34%   |
| Lenovo IdeaPad 1 14IGL7 82V6      | 2         | 0.34%   |
| Lenovo B50-30 80ES                | 2         | 0.34%   |
| HUAWEI NBLK-WAX9X                 | 2         | 0.34%   |
| HP Pavilion Notebook              | 2         | 0.34%   |
| HP Pavilion g6                    | 2         | 0.34%   |
| HP Pavilion 15                    | 2         | 0.34%   |
| HP OMEN by Laptop 15-dc0xxx       | 2         | 0.34%   |
| HP EliteBook 830 G6               | 2         | 0.34%   |
| Google Reks                       | 2         | 0.34%   |
| Dell XPS 15 9550                  | 2         | 0.34%   |
| Dell XPS 13 9380                  | 2         | 0.34%   |
| Dell XPS 13 9360                  | 2         | 0.34%   |
| Dell XPS 13 9310                  | 2         | 0.34%   |
| Dell XPS 13 9300                  | 2         | 0.34%   |
| Dell XPS 13 7390                  | 2         | 0.34%   |
| Dell Precision 7510               | 2         | 0.34%   |
| Dell Precision 5550               | 2         | 0.34%   |
| Dell Latitude E6430               | 2         | 0.34%   |
| Dell Latitude E6400               | 2         | 0.34%   |
| Dell Latitude E6230               | 2         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 80        | 13.7%   |
| Dell Latitude         | 69        | 11.82%  |
| Lenovo IdeaPad        | 36        | 6.16%   |
| Acer Aspire           | 27        | 4.62%   |
| Dell Inspiron         | 25        | 4.28%   |
| Dell XPS              | 21        | 3.6%    |
| HP EliteBook          | 19        | 3.25%   |
| HP Pavilion           | 17        | 2.91%   |
| Dell Precision        | 14        | 2.4%    |
| Toshiba Satellite     | 13        | 2.23%   |
| ASUS Vivobook         | 11        | 1.88%   |
| ASUS ZenBook          | 8         | 1.37%   |
| Valve Jupiter         | 7         | 1.2%    |
| HP ProBook            | 6         | 1.03%   |
| HP Laptop             | 6         | 1.03%   |
| ASUS ROG              | 5         | 0.86%   |
| Apple MacBookPro5     | 5         | 0.86%   |
| HP ZBook              | 4         | 0.68%   |
| HP OMEN               | 4         | 0.68%   |
| Framework Laptop      | 4         | 0.68%   |
| Packard Bell EasyNote | 3         | 0.51%   |
| Lenovo Yoga           | 3         | 0.51%   |
| Lenovo V145-15AST     | 3         | 0.51%   |
| Lenovo ThinkBook      | 3         | 0.51%   |
| HP Presario           | 3         | 0.51%   |
| HP Notebook           | 3         | 0.51%   |
| HP Compaq             | 3         | 0.51%   |
| Fujitsu LIFEBOOK      | 3         | 0.51%   |
| Acer Swift            | 3         | 0.51%   |
| Acer Nitro            | 3         | 0.51%   |
| TUXEDO Pulse          | 2         | 0.34%   |
| TUXEDO InfinityBook   | 2         | 0.34%   |
| Toshiba TECRA         | 2         | 0.34%   |
| Schenker XMG          | 2         | 0.34%   |
| Samsung 750XED        | 2         | 0.34%   |
| MSI Stealth           | 2         | 0.34%   |
| Medion Akoya          | 2         | 0.34%   |
| Lenovo Legion         | 2         | 0.34%   |
| Lenovo IdeaPadFlex    | 2         | 0.34%   |
| Lenovo B50-30         | 2         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 55        | 9.42%   |
| 2018    | 54        | 9.25%   |
| 2019    | 49        | 8.39%   |
| 2021    | 42        | 7.19%   |
| 2017    | 42        | 7.19%   |
| 2022    | 40        | 6.85%   |
| 2016    | 40        | 6.85%   |
| 2012    | 36        | 6.16%   |
| 2013    | 33        | 5.65%   |
| 2011    | 31        | 5.31%   |
| 2015    | 28        | 4.79%   |
| 2023    | 23        | 3.94%   |
| 2009    | 21        | 3.6%    |
| 2008    | 21        | 3.6%    |
| 2014    | 18        | 3.08%   |
| 2010    | 18        | 3.08%   |
| 2024    | 15        | 2.57%   |
| 2007    | 8         | 1.37%   |
| 2025    | 4         | 0.68%   |
| 2006    | 3         | 0.51%   |
| 2005    | 1         | 0.17%   |
| 2003    | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 584       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 516       | 87.61%  |
| Enabled  | 73        | 12.39%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 573       | 98.12%  |
| Yes  | 11        | 1.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 160       | 26.85%  |
| 16.01-24.0  | 126       | 21.14%  |
| 8.01-16.0   | 101       | 16.95%  |
| 3.01-4.0    | 95        | 15.94%  |
| 32.01-64.0  | 61        | 10.23%  |
| 64.01-256.0 | 18        | 3.02%   |
| 1.01-2.0    | 18        | 3.02%   |
| 24.01-32.0  | 7         | 1.17%   |
| 2.01-3.0    | 7         | 1.17%   |
| 0.51-1.0    | 2         | 0.34%   |
| 0.01-0.5    | 1         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 175       | 27.13%  |
| 1.01-2.0   | 158       | 24.5%   |
| 4.01-8.0   | 131       | 20.31%  |
| 3.01-4.0   | 108       | 16.74%  |
| 8.01-16.0  | 36        | 5.58%   |
| 0.51-1.0   | 29        | 4.5%    |
| 16.01-24.0 | 5         | 0.78%   |
| 0.01-0.5   | 3         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 443       | 73.71%  |
| 2      | 130       | 21.63%  |
| 3      | 22        | 3.66%   |
| 0      | 4         | 0.67%   |
| 5      | 1         | 0.17%   |
| 4      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 431       | 73.42%  |
| Yes       | 156       | 26.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 450       | 76.4%   |
| No        | 139       | 23.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 568       | 97.09%  |
| No        | 17        | 2.91%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 485       | 82.06%  |
| No        | 106       | 17.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ireland | 584       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dublin              | 364       | 60.36%  |
| Cork                | 33        | 5.47%   |
| Galway              | 29        | 4.81%   |
| Limerick            | 16        | 2.65%   |
| Naas                | 10        | 1.66%   |
| Waterford           | 8         | 1.33%   |
| Drogheda            | 8         | 1.33%   |
| Ennis               | 6         | 1%      |
| Enniscorthy         | 5         | 0.83%   |
| Westport            | 4         | 0.66%   |
| Navan               | 4         | 0.66%   |
| Wexford             | 3         | 0.5%    |
| Tullamore           | 3         | 0.5%    |
| Lucan               | 3         | 0.5%    |
| Letterkenny         | 3         | 0.5%    |
| Kilkenny            | 3         | 0.5%    |
| Dundalk             | 3         | 0.5%    |
| Dún Laoghaire      | 3         | 0.5%    |
| Athlone             | 3         | 0.5%    |
| Wicklow             | 2         | 0.33%   |
| Tullow              | 2         | 0.33%   |
| Tralee              | 2         | 0.33%   |
| Portlaoise          | 2         | 0.33%   |
| Newmarket on Fergus | 2         | 0.33%   |
| Nenagh              | 2         | 0.33%   |
| Midleton            | 2         | 0.33%   |
| Meath               | 2         | 0.33%   |
| Maynooth            | 2         | 0.33%   |
| Loughrea            | 2         | 0.33%   |
| Kilrush             | 2         | 0.33%   |
| Greystones          | 2         | 0.33%   |
| Dunboyne            | 2         | 0.33%   |
| Donegal             | 2         | 0.33%   |
| Cobh                | 2         | 0.33%   |
| Clonmel             | 2         | 0.33%   |
| Clonakilty          | 2         | 0.33%   |
| Clane               | 2         | 0.33%   |
| Castlerea           | 2         | 0.33%   |
| Carlow              | 2         | 0.33%   |
| Ballina             | 2         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 136       | 181    | 18.84%  |
| WDC                         | 62        | 76     | 8.59%   |
| Sandisk                     | 61        | 72     | 8.45%   |
| Seagate                     | 56        | 70     | 7.76%   |
| Unknown                     | 53        | 70     | 7.34%   |
| Toshiba                     | 38        | 49     | 5.26%   |
| Micron Technology           | 33        | 38     | 4.57%   |
| SK hynix                    | 29        | 31     | 4.02%   |
| Crucial                     | 28        | 41     | 3.88%   |
| Intel                       | 25        | 36     | 3.46%   |
| Hitachi                     | 23        | 31     | 3.19%   |
| KIOXIA                      | 20        | 24     | 2.77%   |
| Kingston                    | 18        | 21     | 2.49%   |
| HGST                        | 15        | 20     | 2.08%   |
| Fujitsu                     | 7         | 8      | 0.97%   |
| Phison Electronics          | 5         | 5      | 0.69%   |
| LITEON                      | 5         | 6      | 0.69%   |
| Kingston Technology Company | 5         | 5      | 0.69%   |
| FORESEE                     | 5         | 6      | 0.69%   |
| Apple                       | 5         | 7      | 0.69%   |
| Transcend                   | 4         | 4      | 0.55%   |
| PNY                         | 4         | 4      | 0.55%   |
| Union Memory                | 3         | 3      | 0.42%   |
| Silicon Motion              | 3         | 4      | 0.42%   |
| SABRENT                     | 3         | 4      | 0.42%   |
| OCZ                         | 3         | 4      | 0.42%   |
| Micron/Crucial Technology   | 3         | 3      | 0.42%   |
| LITEONIT                    | 3         | 3      | 0.42%   |
| KingSpec                    | 3         | 3      | 0.42%   |
| JMicron Technology          | 3         | 3      | 0.42%   |
| A-DATA Technology           | 3         | 6      | 0.42%   |
| SSSTC                       | 2         | 2      | 0.28%   |
| Patriot                     | 2         | 2      | 0.28%   |
| O2 Micro                    | 2         | 4      | 0.28%   |
| Netac                       | 2         | 2      | 0.28%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.28%   |
| Lexar                       | 2         | 2      | 0.28%   |
| Lenovo                      | 2         | 2      | 0.28%   |
| FIKWOT                      | 2         | 3      | 0.28%   |
| China                       | 2         | 8      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 12        | 1.58%   |
| Seagate ST1000LM035-1RK172 1TB                       | 10        | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB   | 10        | 1.32%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                       | 10        | 1.32%   |
| Unknown MMC Card  64GB                               | 8         | 1.05%   |
| Unknown MMC Card  32GB                               | 8         | 1.05%   |
| SanDisk NVMe SSD Drive 512GB                         | 7         | 0.92%   |
| Kingston SA400S37480G 480GB SSD                      | 7         | 0.92%   |
| SanDisk SDSSDH3500G 500GB                            | 6         | 0.79%   |
| Unknown MMC Card  512GB                              | 5         | 0.66%   |
| Toshiba MQ01ABD100 1TB                               | 5         | 0.66%   |
| Intel SSDPEKNU512GZ 512GB                            | 5         | 0.66%   |
| HGST HTS721010A9E630 1TB                             | 5         | 0.66%   |
| HGST HTS545050A7E680 500GB                           | 5         | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                          | 5         | 0.66%   |
| Unknown MMC Card  128GB                              | 4         | 0.53%   |
| Samsung SSD 860 EVO 500GB                            | 4         | 0.53%   |
| Samsung SSD 850 EVO 250GB                            | 4         | 0.53%   |
| Samsung NVMe SSD Drive 256GB                         | 4         | 0.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 4         | 0.53%   |
| Hitachi HTS723232A7A364 320GB                        | 4         | 0.53%   |
| FORESEE 256GB SSD                                    | 4         | 0.53%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                     | 3         | 0.4%    |
| WDC PC SN530 NVMe 512GB                              | 3         | 0.4%    |
| Unknown SL16G  16GB                                  | 3         | 0.4%    |
| Unknown MMC Card  16GB                               | 3         | 0.4%    |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 3         | 0.4%    |
| Toshiba MQ04ABF100 1TB                               | 3         | 0.4%    |
| Toshiba MQ01ABF050 500GB                             | 3         | 0.4%    |
| Seagate ST9500325AS 500GB                            | 3         | 0.4%    |
| Seagate ST500LT012-1DG142 500GB                      | 3         | 0.4%    |
| Seagate ST2000LM003 HN-M201RAD 2TB                   | 3         | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 0.4%    |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                | 3         | 0.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 3         | 0.4%    |
| Samsung NVMe SSD Drive 512GB                         | 3         | 0.4%    |
| Samsung NVMe SSD Drive 500GB                         | 3         | 0.4%    |
| Samsung MZVLQ512HBLU-00B00 512GB                     | 3         | 0.4%    |
| Samsung MZVLB512HBJQ-000L7 512GB                     | 3         | 0.4%    |
| Samsung MZNLN128HAHQ-000H1 128GB SSD                 | 3         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 67     | 31.76%  |
| WDC                 | 37        | 42     | 21.76%  |
| Hitachi             | 23        | 31     | 13.53%  |
| Toshiba             | 22        | 25     | 12.94%  |
| HGST                | 15        | 20     | 8.82%   |
| Fujitsu             | 7         | 8      | 4.12%   |
| Samsung Electronics | 3         | 4      | 1.76%   |
| Unknown             | 2         | 2      | 1.18%   |
| JMicron Technology  | 2         | 2      | 1.18%   |
| USB                 | 1         | 2      | 0.59%   |
| SABRENT             | 1         | 2      | 0.59%   |
| QNAP                | 1         | 1      | 0.59%   |
| LaCie               | 1         | 1      | 0.59%   |
| Apple               | 1         | 1      | 0.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 52        | 63     | 24.76%  |
| SanDisk             | 31        | 32     | 14.76%  |
| Crucial             | 23        | 32     | 10.95%  |
| Kingston            | 16        | 19     | 7.62%   |
| WDC                 | 10        | 14     | 4.76%   |
| Intel               | 8         | 11     | 3.81%   |
| SK hynix            | 5         | 5      | 2.38%   |
| PNY                 | 4         | 4      | 1.9%    |
| Micron Technology   | 4         | 4      | 1.9%    |
| LITEON              | 4         | 5      | 1.9%    |
| FORESEE             | 4         | 5      | 1.9%    |
| Toshiba             | 3         | 5      | 1.43%   |
| OCZ                 | 3         | 4      | 1.43%   |
| LITEONIT            | 3         | 3      | 1.43%   |
| KingSpec            | 3         | 3      | 1.43%   |
| Transcend           | 2         | 2      | 0.95%   |
| SABRENT             | 2         | 2      | 0.95%   |
| Patriot             | 2         | 2      | 0.95%   |
| Netac               | 2         | 2      | 0.95%   |
| China               | 2         | 8      | 0.95%   |
| Apple               | 2         | 2      | 0.95%   |
| A-DATA Technology   | 2         | 5      | 0.95%   |
| 2-Power             | 2         | 3      | 0.95%   |
| ZTC                 | 1         | 1      | 0.48%   |
| Zheino              | 1         | 1      | 0.48%   |
| Wibtek              | 1         | 2      | 0.48%   |
| W800S               | 1         | 2      | 0.48%   |
| Verbatim            | 1         | 1      | 0.48%   |
| Union Memory        | 1         | 1      | 0.48%   |
| Star                | 1         | 1      | 0.48%   |
| SPCC                | 1         | 1      | 0.48%   |
| Plextor             | 1         | 1      | 0.48%   |
| Lexar               | 1         | 1      | 0.48%   |
| KuaiSuZhe           | 1         | 1      | 0.48%   |
| Intenso             | 1         | 1      | 0.48%   |
| Integral            | 1         | 1      | 0.48%   |
| GOODRAM             | 1         | 1      | 0.48%   |
| faspeed             | 1         | 1      | 0.48%   |
| Fanxiang            | 1         | 1      | 0.48%   |
| Emtec               | 1         | 2      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 271       | 366    | 39.45%  |
| SSD     | 196       | 259    | 28.53%  |
| HDD     | 161       | 208    | 23.44%  |
| MMC     | 49        | 66     | 7.13%   |
| Unknown | 10        | 12     | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 320       | 449    | 48.05%  |
| NVMe | 269       | 362    | 40.39%  |
| MMC  | 49        | 66     | 7.36%   |
| SAS  | 28        | 34     | 4.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 246       | 327    | 69.89%  |
| 0.51-1.0   | 87        | 115    | 24.72%  |
| 1.01-2.0   | 13        | 17     | 3.69%   |
| 3.01-4.0   | 5         | 7      | 1.42%   |
| 2.01-3.0   | 1         | 1      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 173       | 28.08%  |
| 251-500        | 169       | 27.44%  |
| 501-1000       | 78        | 12.66%  |
| 1-20           | 50        | 8.12%   |
| 1001-2000      | 42        | 6.82%   |
| 51-100         | 41        | 6.66%   |
| Unknown        | 25        | 4.06%   |
| 21-50          | 16        | 2.6%    |
| More than 3000 | 12        | 1.95%   |
| 2001-3000      | 10        | 1.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 234       | 36.22%  |
| 21-50          | 113       | 17.49%  |
| 101-250        | 96        | 14.86%  |
| 51-100         | 92        | 14.24%  |
| 251-500        | 48        | 7.43%   |
| Unknown        | 25        | 3.87%   |
| 501-1000       | 23        | 3.56%   |
| 1001-2000      | 13        | 2.01%   |
| More than 3000 | 1         | 0.15%   |
| 2001-3000      | 1         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 6.25%   |
| WDC WD5000LPCX-24VHAT0 500GB                   | 1         | 1      | 3.13%   |
| WDC WD32 00BEKT-75PVMT0 320GB                  | 1         | 1      | 3.13%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 3.13%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 3.13%   |
| Toshiba MK3261GSYN 320GB                       | 1         | 1      | 3.13%   |
| Toshiba MK3255GSXF 250GB                       | 1         | 1      | 3.13%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 3.13%   |
| SK hynix SC308 SATA 256GB SSD                  | 1         | 1      | 3.13%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 3.13%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 3.13%   |
| Seagate ST910021AS 100GB                       | 1         | 1      | 3.13%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 3.13%   |
| Seagate ST500LM030-2E717D 500GB                | 1         | 1      | 3.13%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 3.13%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 3.13%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 3.13%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 3.13%   |
| JMicron Technology Generic 320GB               | 1         | 1      | 3.13%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 3.13%   |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 3.13%   |
| Hitachi HTS545032A7E380 320GB                  | 1         | 1      | 3.13%   |
| Hitachi HTS545025B9SA02 250GB                  | 1         | 3      | 3.13%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 3.13%   |
| Hitachi DK23CA-30 32GB                         | 1         | 1      | 3.13%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 3.13%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 3.13%   |
| Fujitsu MHJ2181AT 18GB                         | 1         | 1      | 3.13%   |
| Crucial CT750MX300SSD1 752GB                   | 1         | 1      | 3.13%   |
| Crucial CT1050MX300SSD1 1050GB                 | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 8         | 10     | 25%     |
| Toshiba             | 5         | 5      | 15.63%  |
| Seagate             | 5         | 5      | 15.63%  |
| WDC                 | 3         | 3      | 9.38%   |
| Micron Technology   | 2         | 2      | 6.25%   |
| HGST                | 2         | 2      | 6.25%   |
| Crucial             | 2         | 2      | 6.25%   |
| SK hynix            | 1         | 1      | 3.13%   |
| SanDisk             | 1         | 1      | 3.13%   |
| Samsung Electronics | 1         | 1      | 3.13%   |
| JMicron Technology  | 1         | 1      | 3.13%   |
| Fujitsu             | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 8         | 10     | 30.77%  |
| Toshiba             | 5         | 5      | 19.23%  |
| Seagate             | 5         | 5      | 19.23%  |
| WDC                 | 3         | 3      | 11.54%  |
| HGST                | 2         | 2      | 7.69%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| JMicron Technology  | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 28     | 78.57%  |
| SSD  | 6         | 6      | 21.43%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD1200BEVS-22UST0 120GB     | 1         | 1      | 50%     |
| Sandisk PC SN520 NVMe SSD 128GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Sandisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 337       | 538    | 54.53%  |
| Works    | 251       | 337    | 40.61%  |
| Malfunc  | 28        | 34     | 4.53%   |
| Failed   | 2         | 2      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 358       | 51.29%  |
| Samsung Electronics                     | 83        | 11.89%  |
| AMD                                     | 56        | 8.02%   |
| SanDisk                                 | 47        | 6.73%   |
| Micron Technology                       | 31        | 4.44%   |
| SK hynix                                | 24        | 3.44%   |
| KIOXIA                                  | 19        | 2.72%   |
| Toshiba America Info Systems            | 14        | 2.01%   |
| Nvidia                                  | 12        | 1.72%   |
| Phison Electronics                      | 7         | 1%      |
| Micron/Crucial Technology               | 7         | 1%      |
| Kingston Technology Company             | 7         | 1%      |
| Union Memory (Shenzhen)                 | 5         | 0.72%   |
| Solid State Storage Technology          | 3         | 0.43%   |
| Silicon Motion                          | 3         | 0.43%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.43%   |
| Transcend                               | 2         | 0.29%   |
| O2 Micro                                | 2         | 0.29%   |
| Lenovo                                  | 2         | 0.29%   |
| ASMedia Technology                      | 2         | 0.29%   |
| Apple                                   | 2         | 0.29%   |
| Solidigm                                | 1         | 0.14%   |
| Silicon Image                           | 1         | 0.14%   |
| Shenzhen Unionmemory Information System | 1         | 0.14%   |
| Shenzhen Longsys Electronics            | 1         | 0.14%   |
| Lite-On Technology                      | 1         | 0.14%   |
| INNOGRIT                                | 1         | 0.14%   |
| Hosin Global Electronics                | 1         | 0.14%   |
| ADATA Technology                        | 1         | 0.14%   |
| Adaptec                                 | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 58        | 7.79%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 51        | 6.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 33        | 4.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 32        | 4.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 31        | 4.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 23        | 3.09%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 21        | 2.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 18        | 2.42%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 16        | 2.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 16        | 2.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13        | 1.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 13        | 1.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 12        | 1.61%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 11        | 1.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 1.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 10        | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 1.21%   |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 1.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 1.21%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 8         | 1.07%   |
| Nvidia MCP79 AHCI Controller                                                   | 8         | 1.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 1.07%   |
| Intel RST Volume Management Device Controller                                  | 8         | 1.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.07%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 8         | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 8         | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 1.07%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 7         | 0.94%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 7         | 0.94%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 7         | 0.94%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 6         | 0.81%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 6         | 0.81%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 6         | 0.81%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 6         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 0.81%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 0.81%   |
| SanDisk IX SN530 NVMe SSD / microSD Express Card (DRAM-less)                   | 5         | 0.67%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 5         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 348       | 48.95%  |
| NVMe | 270       | 37.97%  |
| RAID | 62        | 8.72%   |
| IDE  | 30        | 4.22%   |
| SCSI | 1         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 472       | 80.68%  |
| AMD    | 112       | 19.15%  |
| ARM    | 1         | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 2.56%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 13        | 2.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 1.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 1.88%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 1.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 1.37%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 1.37%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.2%    |
| AMD Custom APU 0405                           | 7         | 1.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.03%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 1.03%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 1.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 1.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 0.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 5         | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.85%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 5         | 0.85%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 0.85%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.85%   |
| Intel 12th Gen Core i5-1235U                  | 5         | 0.85%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.85%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 4         | 0.68%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.68%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.68%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.68%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 4         | 0.68%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 4         | 0.68%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 0.68%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 4         | 0.68%   |
| Intel 13th Gen Core i5-1335U                  | 4         | 0.68%   |
| Intel 12th Gen Core i7-1260P                  | 4         | 0.68%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 0.68%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 128       | 21.88%  |
| Intel Core i5           | 121       | 20.68%  |
| Other                   | 87        | 14.87%  |
| Intel Celeron           | 36        | 6.15%   |
| Intel Core i3           | 34        | 5.81%   |
| AMD Ryzen 5             | 30        | 5.13%   |
| Intel Core 2 Duo        | 27        | 4.62%   |
| AMD Ryzen 7             | 22        | 3.76%   |
| Intel Core              | 10        | 1.71%   |
| Intel Pentium           | 9         | 1.54%   |
| Intel Atom              | 8         | 1.37%   |
| AMD Ryzen 9             | 5         | 0.85%   |
| AMD Ryzen 3             | 5         | 0.85%   |
| AMD A8                  | 5         | 0.85%   |
| Intel Core i9           | 4         | 0.68%   |
| AMD Ryzen 7 PRO         | 4         | 0.68%   |
| AMD Ryzen 5 PRO         | 4         | 0.68%   |
| AMD E1                  | 4         | 0.68%   |
| Intel Core 2            | 3         | 0.51%   |
| Intel Celeron Dual-Core | 3         | 0.51%   |
| Intel Pentium Silver    | 2         | 0.34%   |
| Intel Pentium Dual-Core | 2         | 0.34%   |
| Intel Pentium Dual      | 2         | 0.34%   |
| AMD Sempron             | 2         | 0.34%   |
| AMD Ryzen 3 PRO         | 2         | 0.34%   |
| AMD E2                  | 2         | 0.34%   |
| AMD Athlon              | 2         | 0.34%   |
| AMD A6                  | 2         | 0.34%   |
| AMD A4                  | 2         | 0.34%   |
| AMD A10                 | 2         | 0.34%   |
| Intel Xeon              | 1         | 0.17%   |
| Intel Pentium M         | 1         | 0.17%   |
| Intel Pentium III       | 1         | 0.17%   |
| Intel Pentium Gold      | 1         | 0.17%   |
| Intel Genuine           | 1         | 0.17%   |
| Intel Core m7           | 1         | 0.17%   |
| Intel Core m5           | 1         | 0.17%   |
| Intel Core m3           | 1         | 0.17%   |
| Intel Core 2 Extreme    | 1         | 0.17%   |
| Intel Celeron M         | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 240       | 41.03%  |
| 4      | 207       | 35.38%  |
| 8      | 41        | 7.01%   |
| 6      | 39        | 6.67%   |
| 14     | 14        | 2.39%   |
| 12     | 13        | 2.22%   |
| 1      | 13        | 2.22%   |
| 10     | 12        | 2.05%   |
| 16     | 3         | 0.51%   |
| 24     | 2         | 0.34%   |
| 3      | 1         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 584       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 449       | 76.75%  |
| 1      | 136       | 23.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 575       | 97.96%  |
| Unknown        | 9         | 1.53%   |
| 32-bit         | 3         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 303       | 49.84%  |
| 0x806ec    | 21        | 3.45%   |
| 0x306a9    | 20        | 3.29%   |
| 0x806c1    | 16        | 2.63%   |
| 0x806e9    | 15        | 2.47%   |
| 0x206a7    | 15        | 2.47%   |
| 0x406e3    | 13        | 2.14%   |
| 0x1067a    | 13        | 2.14%   |
| 0x806ea    | 12        | 1.97%   |
| 0x40651    | 12        | 1.97%   |
| 0x0a50000c | 9         | 1.48%   |
| 0x906ea    | 8         | 1.32%   |
| 0xa0652    | 7         | 1.15%   |
| 0x406c4    | 7         | 1.15%   |
| 0x30678    | 7         | 1.15%   |
| 0x906e9    | 6         | 0.99%   |
| 0x306d4    | 6         | 0.99%   |
| 0x306c3    | 6         | 0.99%   |
| 0x20655    | 6         | 0.99%   |
| 0x10676    | 5         | 0.82%   |
| 0x08108109 | 5         | 0.82%   |
| 0x06006705 | 5         | 0.82%   |
| 0x906a3    | 4         | 0.66%   |
| 0x6fd      | 4         | 0.66%   |
| 0x20652    | 4         | 0.66%   |
| 0x106ca    | 4         | 0.66%   |
| 0x08108102 | 4         | 0.66%   |
| 0x806d1    | 3         | 0.49%   |
| 0x706e5    | 3         | 0.49%   |
| 0x706a8    | 3         | 0.49%   |
| 0x506e3    | 3         | 0.49%   |
| 0x08600106 | 3         | 0.49%   |
| 0x906a4    | 2         | 0.33%   |
| 0x706a1    | 2         | 0.33%   |
| 0x6f6      | 2         | 0.33%   |
| 0x6d8      | 2         | 0.33%   |
| 0x506c9    | 2         | 0.33%   |
| 0x106e5    | 2         | 0.33%   |
| 0x08608103 | 2         | 0.33%   |
| 0x08600109 | 2         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| KabyLake           | 122       | 20.82%  |
| Unknown            | 54        | 9.22%   |
| Skylake            | 36        | 6.14%   |
| IvyBridge          | 33        | 5.63%   |
| TigerLake          | 32        | 5.46%   |
| SandyBridge        | 31        | 5.29%   |
| Haswell            | 27        | 4.61%   |
| Penryn             | 26        | 4.44%   |
| Silvermont         | 21        | 3.58%   |
| Alderlake Hybrid   | 19        | 3.24%   |
| Zen+               | 18        | 3.07%   |
| Westmere           | 18        | 3.07%   |
| Zen 3              | 16        | 2.73%   |
| Goldmont plus      | 14        | 2.39%   |
| Zen 2              | 13        | 2.22%   |
| Core               | 13        | 2.22%   |
| IceLake            | 12        | 2.05%   |
| Excavator          | 11        | 1.88%   |
| CometLake          | 11        | 1.88%   |
| Broadwell          | 11        | 1.88%   |
| Zen                | 6         | 1.02%   |
| Puma               | 4         | 0.68%   |
| P6                 | 4         | 0.68%   |
| Goldmont           | 4         | 0.68%   |
| Bonnell            | 4         | 0.68%   |
| Bobcat             | 4         | 0.68%   |
| Meteorlake Hybrid  | 3         | 0.51%   |
| K8 Hammer          | 3         | 0.51%   |
| Jaguar             | 3         | 0.51%   |
| Piledriver         | 2         | 0.34%   |
| Nehalem            | 2         | 0.34%   |
| K10                | 2         | 0.34%   |
| Gracemont          | 2         | 0.34%   |
| Tremont            | 1         | 0.17%   |
| Steamroller        | 1         | 0.17%   |
| Lunarlake Hybrid   | 1         | 0.17%   |
| K8 & K10 hybrid    | 1         | 0.17%   |
| ArrowLake-H Hybrid | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 427       | 59.89%  |
| Nvidia | 160       | 22.44%  |
| AMD    | 126       | 17.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 32        | 4.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 31        | 4.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 3.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 27        | 3.69%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 22        | 3.01%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 19        | 2.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 2.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 2.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 2.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 2.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 2.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 1.92%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 13        | 1.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 1.64%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 12        | 1.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 11        | 1.5%    |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 11        | 1.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 1.5%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 11        | 1.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.23%   |
| Nvidia C79 [GeForce 9400M]                                                               | 8         | 1.09%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 8         | 1.09%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 8         | 1.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 1.09%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 7         | 0.96%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 0.96%   |
| AMD Rembrandt [Radeon 680M]                                                              | 7         | 0.96%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 6         | 0.82%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 0.68%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.68%   |
| AMD Lucienne                                                                             | 5         | 0.68%   |
| AMD Barcelo                                                                              | 5         | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 308       | 52.56%  |
| Intel + Nvidia | 107       | 18.26%  |
| 1 x AMD        | 93        | 15.87%  |
| 1 x Nvidia     | 41        | 7%      |
| AMD + Nvidia   | 12        | 2.05%   |
| 2 x AMD        | 10        | 1.71%   |
| Intel + AMD    | 10        | 1.71%   |
| 2 x Intel      | 3         | 0.51%   |
| Other          | 1         | 0.17%   |
| 2 x Nvidia     | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 484       | 82.03%  |
| Proprietary | 71        | 12.03%  |
| Unknown     | 35        | 5.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 427       | 71.17%  |
| 0.01-0.5   | 69        | 11.5%   |
| 1.01-2.0   | 34        | 5.67%   |
| 3.01-4.0   | 30        | 5%      |
| 0.51-1.0   | 26        | 4.33%   |
| 7.01-8.0   | 6         | 1%      |
| 5.01-6.0   | 6         | 1%      |
| 2.01-3.0   | 2         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 109       | 15.98%  |
| AU Optronics            | 108       | 15.84%  |
| LG Display              | 94        | 13.78%  |
| Chimei Innolux          | 83        | 12.17%  |
| Samsung Electronics     | 56        | 8.21%   |
| Dell                    | 38        | 5.57%   |
| Sharp                   | 31        | 4.55%   |
| Apple                   | 17        | 2.49%   |
| Lenovo                  | 15        | 2.2%    |
| Acer                    | 13        | 1.91%   |
| Goldstar                | 11        | 1.61%   |
| Chi Mei Optoelectronics | 11        | 1.61%   |
| ViewSonic               | 10        | 1.47%   |
| AOC                     | 10        | 1.47%   |
| PANDA                   | 9         | 1.32%   |
| Hewlett-Packard         | 8         | 1.17%   |
| Valve                   | 7         | 1.03%   |
| LG Philips              | 7         | 1.03%   |
| Philips                 | 6         | 0.88%   |
| InfoVision              | 6         | 0.88%   |
| KDB                     | 3         | 0.44%   |
| CSO                     | 3         | 0.44%   |
| BenQ                    | 3         | 0.44%   |
| Vestel Elektronik       | 2         | 0.29%   |
| MSI                     | 2         | 0.29%   |
| Iiyama                  | 2         | 0.29%   |
| CSW                     | 2         | 0.29%   |
| CPT                     | 2         | 0.29%   |
| BOE Technology Group    | 2         | 0.29%   |
| ___                     | 1         | 0.15%   |
| Unknown                 | 1         | 0.15%   |
| TVW                     | 1         | 0.15%   |
| Toshiba                 | 1         | 0.15%   |
| Quanta Display          | 1         | 0.15%   |
| OEM                     | 1         | 0.15%   |
| LGD                     | 1         | 0.15%   |
| Lenovo Group Limited    | 1         | 0.15%   |
| HUAWEI                  | 1         | 0.15%   |
| CSOT                    | 1         | 0.15%   |
| ASUSTek Computer        | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                 | 9         | 1.29%   |
| ViewSonic VP2756-2K VSCE63B 2560x1440 597x336mm 27.0-inch             | 8         | 1.15%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                     | 8         | 1.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 8         | 1.15%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 6         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 6         | 0.86%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 6         | 0.86%   |
| Acer KA220Q B ACR0A30 1920x1080 476x267mm 21.5-inch                   | 6         | 0.86%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 5         | 0.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.72%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.72%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 4         | 0.57%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 4         | 0.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 4         | 0.57%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.43%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 3         | 0.43%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 3         | 0.43%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 3         | 0.43%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 3         | 0.43%   |
| KDB LCD Monitor KDB0526 1920x1080 344x194mm 15.5-inch                 | 3         | 0.43%   |
| Dell P2422H DELA1C4 1920x1080 527x296mm 23.8-inch                     | 3         | 0.43%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                     | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch      | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 0.43%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.43%   |
| AU Optronics LCD Monitor AUOB78F 1920x1080 344x194mm 15.5-inch        | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 3         | 0.43%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch  | 2         | 0.29%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 2         | 0.29%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch               | 2         | 0.29%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 2         | 0.29%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch               | 2         | 0.29%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 2         | 0.29%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 2         | 0.29%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 2         | 0.29%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 298       | 46.78%  |
| 1366x768 (WXGA)    | 138       | 21.66%  |
| 3840x2160 (4K)     | 29        | 4.55%   |
| 1920x1200 (WUXGA)  | 25        | 3.92%   |
| 1600x900 (HD+)     | 20        | 3.14%   |
| 1280x800 (WXGA)    | 20        | 3.14%   |
| 2560x1440 (QHD)    | 18        | 2.83%   |
| 1440x900 (WXGA+)   | 13        | 2.04%   |
| 2880x1800          | 12        | 1.88%   |
| 2560x1600          | 10        | 1.57%   |
| 800x1280           | 8         | 1.26%   |
| 3440x1440          | 6         | 0.94%   |
| 3840x2400          | 5         | 0.78%   |
| 1280x1024 (SXGA)   | 4         | 0.63%   |
| 1024x600           | 4         | 0.63%   |
| 3456x2160          | 3         | 0.47%   |
| 3200x1800 (QHD+)   | 3         | 0.47%   |
| 2256x1504          | 3         | 0.47%   |
| 1680x1050 (WSXGA+) | 3         | 0.47%   |
| 3840x1100          | 2         | 0.31%   |
| 2560x1080          | 2         | 0.31%   |
| 2160x1440          | 2         | 0.31%   |
| 1920x540           | 2         | 0.31%   |
| 1600x1200          | 2         | 0.31%   |
| 1360x768           | 2         | 0.31%   |
| 3840x1600          | 1         | 0.16%   |
| 3840x1080          | 1         | 0.16%   |
| Unknown            | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 255       | 37.06%  |
| 14      | 100       | 14.53%  |
| 13      | 95        | 13.81%  |
| 27      | 33        | 4.8%    |
| 17      | 30        | 4.36%   |
| 21      | 29        | 4.22%   |
| 24      | 28        | 4.07%   |
| 12      | 24        | 3.49%   |
| 16      | 17        | 2.47%   |
| 23      | 13        | 1.89%   |
| 11      | 10        | 1.45%   |
| Unknown | 9         | 1.31%   |
| 34      | 8         | 1.16%   |
| 7       | 7         | 1.02%   |
| 31      | 5         | 0.73%   |
| 10      | 4         | 0.58%   |
| 18      | 3         | 0.44%   |
| 84      | 2         | 0.29%   |
| 29      | 2         | 0.29%   |
| 22      | 2         | 0.29%   |
| 19      | 2         | 0.29%   |
| 72      | 1         | 0.15%   |
| 48      | 1         | 0.15%   |
| 40      | 1         | 0.15%   |
| 39      | 1         | 0.15%   |
| 37      | 1         | 0.15%   |
| 32      | 1         | 0.15%   |
| 26      | 1         | 0.15%   |
| 25      | 1         | 0.15%   |
| 20      | 1         | 0.15%   |
| 3       | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 401       | 59.06%  |
| 201-300     | 92        | 13.55%  |
| 501-600     | 67        | 9.87%   |
| 351-400     | 39        | 5.74%   |
| 401-500     | 35        | 5.15%   |
| 601-700     | 12        | 1.77%   |
| 701-800     | 9         | 1.33%   |
| Unknown     | 9         | 1.33%   |
| 1-100       | 8         | 1.18%   |
| 1501-2000   | 3         | 0.44%   |
| 801-900     | 2         | 0.29%   |
| 1001-1500   | 1         | 0.15%   |
| 901-1000    | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 466       | 78.19%  |
| 16/10   | 88        | 14.77%  |
| 21/9    | 11        | 1.85%   |
| Unknown | 8         | 1.34%   |
| 3/2     | 6         | 1.01%   |
| 0.67    | 6         | 1.01%   |
| 5/4     | 4         | 0.67%   |
| 4/3     | 2         | 0.34%   |
| 3.40    | 2         | 0.34%   |
| 6/5     | 1         | 0.17%   |
| 32/9    | 1         | 0.17%   |
| 0.62    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 252       | 36.73%  |
| 81-90          | 156       | 22.74%  |
| 201-250        | 55        | 8.02%   |
| 71-80          | 38        | 5.54%   |
| 301-350        | 35        | 5.1%    |
| 61-70          | 23        | 3.35%   |
| 121-130        | 23        | 3.35%   |
| 111-120        | 19        | 2.77%   |
| 351-500        | 14        | 2.04%   |
| 51-60          | 12        | 1.75%   |
| 151-200        | 11        | 1.6%    |
| Unknown        | 9         | 1.31%   |
| 1-40           | 8         | 1.17%   |
| 251-300        | 8         | 1.17%   |
| 141-150        | 5         | 0.73%   |
| 131-140        | 5         | 0.73%   |
| 41-50          | 4         | 0.58%   |
| 501-1000       | 4         | 0.58%   |
| More than 1000 | 3         | 0.44%   |
| 91-100         | 2         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 296       | 44.44%  |
| 101-120       | 169       | 25.38%  |
| 51-100        | 89        | 13.36%  |
| 161-240       | 65        | 9.76%   |
| More than 240 | 36        | 5.41%   |
| Unknown       | 9         | 1.35%   |
| 1-50          | 2         | 0.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 463       | 77.42%  |
| 2     | 95        | 15.89%  |
| 3     | 21        | 3.51%   |
| 0     | 18        | 3.01%   |
| 4     | 1         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 341       | 36.79%  |
| Realtek Semiconductor                  | 271       | 29.23%  |
| Qualcomm Atheros                       | 100       | 10.79%  |
| Broadcom                               | 62        | 6.69%   |
| MediaTek                               | 22        | 2.37%   |
| Broadcom Limited                       | 13        | 1.4%    |
| Nvidia                                 | 12        | 1.29%   |
| Shenzhen Goodix Technology             | 10        | 1.08%   |
| Ralink Technology                      | 8         | 0.86%   |
| Marvell Technology Group               | 8         | 0.86%   |
| Qualcomm                               | 7         | 0.76%   |
| ASIX Electronics                       | 7         | 0.76%   |
| Samsung Electronics                    | 6         | 0.65%   |
| Ericsson Business Mobile Networks      | 6         | 0.65%   |
| DisplayLink                            | 6         | 0.65%   |
| Xiaomi                                 | 5         | 0.54%   |
| Lenovo                                 | 5         | 0.54%   |
| TP-Link                                | 4         | 0.43%   |
| Ralink                                 | 3         | 0.32%   |
| Dell                                   | 3         | 0.32%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.22%   |
| Sierra Wireless                        | 2         | 0.22%   |
| Microsoft                              | 2         | 0.22%   |
| Hewlett-Packard                        | 2         | 0.22%   |
| Xilinx                                 | 1         | 0.11%   |
| U-Blox                                 | 1         | 0.11%   |
| Toshiba                                | 1         | 0.11%   |
| T & A Mobile Phones                    | 1         | 0.11%   |
| Qualcomm Technologies                  | 1         | 0.11%   |
| Qualcomm Atheros Communications        | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.11%   |
| NetGear                                | 1         | 0.11%   |
| Naxiang                                | 1         | 0.11%   |
| Motorola PCS                           | 1         | 0.11%   |
| LSI                                    | 1         | 0.11%   |
| ICS Advent                             | 1         | 0.11%   |
| Google                                 | 1         | 0.11%   |
| Fibocom                                | 1         | 0.11%   |
| Edimax Technology                      | 1         | 0.11%   |
| BUFFALO                                | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 140       | 12.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 42        | 3.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 42        | 3.75%   |
| Intel Wireless 8265 / 8275                                             | 31        | 2.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 29        | 2.59%   |
| Intel Wi-Fi 6 AX200                                                    | 29        | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 26        | 2.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 23        | 2.05%   |
| Intel Wi-Fi 6 AX201                                                    | 22        | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 20        | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 18        | 1.61%   |
| Intel Wireless 8260                                                    | 18        | 1.61%   |
| Intel Wireless 7260                                                    | 18        | 1.61%   |
| Intel Ethernet Connection (4) I219-LM                                  | 16        | 1.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 14        | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 13        | 1.16%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 13        | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 12        | 1.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 12        | 1.07%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 12        | 1.07%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 11        | 0.98%   |
| Intel Wireless 7265                                                    | 11        | 0.98%   |
| Shenzhen Goodix Fingerprint Reader                                     | 10        | 0.89%   |
| Intel Wireless 3165                                                    | 10        | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 10        | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 10        | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 10        | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 9         | 0.8%    |
| Nvidia MCP79 Ethernet                                                  | 9         | 0.8%    |
| Intel Ethernet Connection I218-LM                                      | 9         | 0.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 9         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 9         | 0.8%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 9         | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                          | 8         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 7         | 0.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7         | 0.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 7         | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 7         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                   | 7         | 0.63%   |
| Intel Meteor Lake PCH CNVi WiFi                                        | 6         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 325       | 54.17%  |
| Qualcomm Atheros                | 89        | 14.83%  |
| Realtek Semiconductor           | 79        | 13.17%  |
| Broadcom                        | 49        | 8.17%   |
| MediaTek                        | 19        | 3.17%   |
| Ralink Technology               | 8         | 1.33%   |
| Qualcomm                        | 6         | 1%      |
| Broadcom Limited                | 5         | 0.83%   |
| TP-Link                         | 3         | 0.5%    |
| Ralink                          | 3         | 0.5%    |
| Dell                            | 3         | 0.5%    |
| Sierra Wireless                 | 2         | 0.33%   |
| Qualcomm Technologies           | 1         | 0.17%   |
| Qualcomm Atheros Communications | 1         | 0.17%   |
| NetGear                         | 1         | 0.17%   |
| Microsoft                       | 1         | 0.17%   |
| Fibocom                         | 1         | 0.17%   |
| Edimax Technology               | 1         | 0.17%   |
| BUFFALO                         | 1         | 0.17%   |
| ASUSTek Computer                | 1         | 0.17%   |
| Apple                           | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 31        | 5.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 29        | 4.81%   |
| Intel Wi-Fi 6 AX200                                                     | 29        | 4.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 23        | 3.81%   |
| Intel Wi-Fi 6 AX201                                                     | 22        | 3.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 3.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 2.99%   |
| Intel Wireless 8260                                                     | 18        | 2.99%   |
| Intel Wireless 7260                                                     | 18        | 2.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 2.16%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 13        | 2.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 1.99%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 11        | 1.82%   |
| Intel Wireless 7265                                                     | 11        | 1.82%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 11        | 1.82%   |
| Intel Wireless 3165                                                     | 10        | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 1.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 1.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 1.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.49%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 9         | 1.49%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 1.16%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 7         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 1.16%   |
| Intel Meteor Lake PCH CNVi WiFi                                         | 6         | 1%      |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 6         | 1%      |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 5         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.83%   |
| Intel Wireless 3160                                                     | 5         | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 5         | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.83%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 0.83%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 4         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 230       | 47.52%  |
| Intel                                  | 139       | 28.72%  |
| Qualcomm Atheros                       | 21        | 4.34%   |
| Broadcom                               | 19        | 3.93%   |
| Nvidia                                 | 12        | 2.48%   |
| Broadcom Limited                       | 9         | 1.86%   |
| Marvell Technology Group               | 8         | 1.65%   |
| ASIX Electronics                       | 7         | 1.45%   |
| Samsung Electronics                    | 6         | 1.24%   |
| DisplayLink                            | 6         | 1.24%   |
| Xiaomi                                 | 5         | 1.03%   |
| Lenovo                                 | 5         | 1.03%   |
| MediaTek                               | 3         | 0.62%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.41%   |
| Xilinx                                 | 1         | 0.21%   |
| TP-Link                                | 1         | 0.21%   |
| T & A Mobile Phones                    | 1         | 0.21%   |
| Qualcomm                               | 1         | 0.21%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.21%   |
| Naxiang                                | 1         | 0.21%   |
| Motorola PCS                           | 1         | 0.21%   |
| Microsoft                              | 1         | 0.21%   |
| ICS Advent                             | 1         | 0.21%   |
| Hewlett-Packard                        | 1         | 0.21%   |
| Google                                 | 1         | 0.21%   |
| 3Com                                   | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 140       | 28.28%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 42        | 8.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 42        | 8.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 26        | 5.25%   |
| Intel Ethernet Connection (4) I219-LM                                  | 16        | 3.23%   |
| Nvidia MCP79 Ethernet                                                  | 9         | 1.82%   |
| Intel Ethernet Connection I218-LM                                      | 9         | 1.82%   |
| Intel Ethernet Connection (4) I219-V                                   | 7         | 1.41%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.21%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 1.21%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 5         | 1.01%   |
| Intel Ethernet Connection I219-V                                       | 5         | 1.01%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 1.01%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 0.81%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 4         | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 4         | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.81%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 0.81%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 4         | 0.81%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.61%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.61%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.61%   |
| Intel Ethernet Connection (16) I219-V                                  | 3         | 0.61%   |
| Intel Ethernet Connection (11) I219-LM                                 | 3         | 0.61%   |
| Intel Ethernet Connection (10) I219-V                                  | 3         | 0.61%   |
| DisplayLink Dell Universal Dock D6000                                  | 3         | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.61%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 3         | 0.61%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 3         | 0.61%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 2         | 0.4%    |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 567       | 54.73%  |
| Ethernet | 447       | 43.15%  |
| Modem    | 22        | 2.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 473       | 78.18%  |
| Ethernet | 132       | 21.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 389       | 66.38%  |
| 1     | 184       | 31.4%   |
| 0     | 8         | 1.37%   |
| 3     | 5         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 476       | 80.13%  |
| Yes  | 118       | 19.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 268       | 54.36%  |
| Realtek Semiconductor           | 46        | 9.33%   |
| Qualcomm Atheros Communications | 33        | 6.69%   |
| IMC Networks                    | 30        | 6.09%   |
| Broadcom                        | 24        | 4.87%   |
| Lite-On Technology              | 18        | 3.65%   |
| Foxconn / Hon Hai               | 15        | 3.04%   |
| Apple                           | 14        | 2.84%   |
| Dell                            | 11        | 2.23%   |
| Toshiba                         | 7         | 1.42%   |
| Hewlett-Packard                 | 7         | 1.42%   |
| Cambridge Silicon Radio         | 7         | 1.42%   |
| Realtek                         | 4         | 0.81%   |
| USI                             | 3         | 0.61%   |
| MediaTek                        | 2         | 0.41%   |
| Foxconn International           | 2         | 0.41%   |
| Ralink                          | 1         | 0.2%    |
| ASUSTek Computer                | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 93        | 18.83%  |
| Intel AX201 Bluetooth                               | 54        | 10.93%  |
| Realtek Bluetooth Radio                             | 35        | 7.09%   |
| Intel Bluetooth Device                              | 34        | 6.88%   |
| Intel AX200 Bluetooth                               | 27        | 5.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 26        | 5.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 20        | 4.05%   |
| IMC Networks Bluetooth Radio                        | 14        | 2.83%   |
| Intel AX210 Bluetooth                               | 12        | 2.43%   |
| IMC Networks Wireless_Device                        | 10        | 2.02%   |
| Apple Bluetooth Host Controller                     | 10        | 2.02%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 1.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 1.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 1.42%   |
| Dell DW375 Bluetooth Module                         | 7         | 1.42%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 1.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.21%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.01%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 1.01%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 1.01%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 1.01%   |
| Realtek Bluetooth Radio                             | 4         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.81%   |
| Lite-On Wireless_Device                             | 4         | 0.81%   |
| IMC Networks Bluetooth Device                       | 4         | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.81%   |
| USI Bluetooth Device                                | 3         | 0.61%   |
| Toshiba Bluetooth Device                            | 3         | 0.61%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.61%   |
| Toshiba Atheros AR3012 Bluetooth                    | 2         | 0.4%    |
| MediaTek Wireless_Device                            | 2         | 0.4%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.4%    |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.4%    |
| Dell Wireless 355 Bluetooth                         | 2         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 456       | 61.96%  |
| AMD                     | 118       | 16.03%  |
| Nvidia                  | 100       | 13.59%  |
| Realtek Semiconductor   | 13        | 1.77%   |
| Plantronics             | 7         | 0.95%   |
| GN Netcom               | 7         | 0.95%   |
| Lenovo                  | 4         | 0.54%   |
| C-Media Electronics     | 4         | 0.54%   |
| Sony                    | 3         | 0.41%   |
| Logitech                | 3         | 0.41%   |
| RODE Microphones        | 2         | 0.27%   |
| Kingston Technology     | 2         | 0.27%   |
| Focusrite-Novation      | 2         | 0.27%   |
| VIA Technologies        | 1         | 0.14%   |
| Trust                   | 1         | 0.14%   |
| No brand                | 1         | 0.14%   |
| Huawei Technologies     | 1         | 0.14%   |
| Generalplus Technology  | 1         | 0.14%   |
| ESS Technology          | 1         | 0.14%   |
| Elite Silicon           | 1         | 0.14%   |
| Dell                    | 1         | 0.14%   |
| Creative Technology     | 1         | 0.14%   |
| Conexant Systems        | 1         | 0.14%   |
| Blue Microphones        | 1         | 0.14%   |
| bestechnic              | 1         | 0.14%   |
| BEHRINGER International | 1         | 0.14%   |
| AUDIOLAB                | 1         | 0.14%   |
| Audient                 | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 81        | 9.36%   |
| AMD Ryzen HD Audio Controller                                              | 69        | 7.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 38        | 4.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 30        | 3.47%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 29        | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 26        | 3.01%   |
| AMD Radeon High Definition Audio Controller                                | 23        | 2.66%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 21        | 2.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 21        | 2.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 20        | 2.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 19        | 2.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 2.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 1.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 17        | 1.97%   |
| Intel Haswell-ULT HD Audio Controller                                      | 15        | 1.73%   |
| Intel 8 Series HD Audio Controller                                         | 15        | 1.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 14        | 1.62%   |
| Realtek Semiconductor USB Audio                                            | 13        | 1.5%    |
| Intel Raptor Lake-P/U/H cAVS                                               | 13        | 1.5%    |
| AMD FCH Azalia Controller                                                  | 13        | 1.5%    |
| Intel CM238 HD Audio Controller                                            | 12        | 1.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 1.27%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 1.27%   |
| AMD Kabini HDMI/DP Audio                                                   | 11        | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10        | 1.16%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 10        | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                              | 9         | 1.04%   |
| Nvidia MCP79 High Definition Audio                                         | 9         | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 8         | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 8         | 0.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 8         | 0.92%   |
| Plantronics Poly Voyager Focus 2 Series                                    | 7         | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 0.81%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 0.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 121       | 30.87%  |
| SK hynix            | 86        | 21.94%  |
| Micron Technology   | 53        | 13.52%  |
| Kingston            | 30        | 7.65%   |
| Crucial             | 30        | 7.65%   |
| Unknown             | 17        | 4.34%   |
| Ramaxel Technology  | 11        | 2.81%   |
| Corsair             | 8         | 2.04%   |
| Elpida              | 7         | 1.79%   |
| Unknown             | 6         | 1.53%   |
| Unknown (ABCD)      | 4         | 1.02%   |
| Nanya Technology    | 4         | 1.02%   |
| G.Skill             | 3         | 0.77%   |
| Apacer              | 2         | 0.51%   |
| A-DATA Technology   | 2         | 0.51%   |
| Transcend           | 1         | 0.26%   |
| Silicon Power       | 1         | 0.26%   |
| SHARETRONIC         | 1         | 0.26%   |
| Patriot             | 1         | 0.26%   |
| CXMT                | 1         | 0.26%   |
| CSX                 | 1         | 0.26%   |
| A Force             | 1         | 0.26%   |
| 4ea5                | 1         | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 2.17%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 1.69%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.45%   |
| Crucial RAM CT8G4SFS824A.C8FN 8GB SODIMM DDR4 2400MT/s           | 6         | 1.45%   |
| Unknown                                                          | 6         | 1.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 5         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.2%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.2%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.96%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.96%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.96%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.96%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 4         | 0.96%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 4         | 0.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.72%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.72%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 3         | 0.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.72%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.72%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 3         | 0.72%   |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s          | 3         | 0.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.48%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s          | 2         | 0.48%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.48%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 2         | 0.48%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.48%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.48%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.48%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 0.48%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.48%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 172       | 51.81%  |
| DDR3    | 74        | 22.29%  |
| LPDDR4  | 20        | 6.02%   |
| LPDDR5  | 17        | 5.12%   |
| DDR5    | 15        | 4.52%   |
| LPDDR3  | 12        | 3.61%   |
| DDR2    | 11        | 3.31%   |
| SDRAM   | 6         | 1.81%   |
| DRAM    | 2         | 0.6%    |
| DDR     | 2         | 0.6%    |
| Unknown | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 281       | 83.63%  |
| Row Of Chips | 42        | 12.5%   |
| Chip         | 7         | 2.08%   |
| Unknown      | 4         | 1.19%   |
| DIMM         | 2         | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 139       | 37.77%  |
| 4096  | 101       | 27.45%  |
| 16384 | 68        | 18.48%  |
| 2048  | 34        | 9.24%   |
| 32768 | 15        | 4.08%   |
| 1024  | 7         | 1.9%    |
| 24576 | 1         | 0.27%   |
| 12288 | 1         | 0.27%   |
| 256   | 1         | 0.27%   |
| 128   | 1         | 0.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 76        | 20.54%  |
| 3200    | 68        | 18.38%  |
| 1600    | 52        | 14.05%  |
| 2400    | 34        | 9.19%   |
| 2133    | 20        | 5.41%   |
| 1334    | 12        | 3.24%   |
| 4267    | 10        | 2.7%    |
| 6400    | 9         | 2.43%   |
| 5600    | 9         | 2.43%   |
| 3266    | 9         | 2.43%   |
| 1333    | 8         | 2.16%   |
| 4800    | 7         | 1.89%   |
| 1867    | 7         | 1.89%   |
| 800     | 7         | 1.89%   |
| 667     | 7         | 1.89%   |
| 8400    | 6         | 1.62%   |
| 1067    | 6         | 1.62%   |
| 4266    | 3         | 0.81%   |
| 4199    | 3         | 0.81%   |
| 7500    | 2         | 0.54%   |
| 7467    | 2         | 0.54%   |
| 2267    | 2         | 0.54%   |
| 2048    | 2         | 0.54%   |
| 975     | 2         | 0.54%   |
| Unknown | 2         | 0.54%   |
| 8600    | 1         | 0.27%   |
| 8533    | 1         | 0.27%   |
| 7400    | 1         | 0.27%   |
| 3600    | 1         | 0.27%   |
| 533     | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| STMicroelectronics | 1         | 33.33%  |
| Seiko Epson        | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 33.33%  |
| Seiko Epson ET-2710 Series                                | 1         | 33.33%  |
| Brother HL-L2340D series                                  | 1         | 33.33%  |

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
| Chicony Electronics                    | 124       | 23.4%   |
| IMC Networks                           | 61        | 11.51%  |
| Realtek Semiconductor                  | 59        | 11.13%  |
| Microdia                               | 57        | 10.75%  |
| Bison Electronics                      | 42        | 7.92%   |
| Sunplus Innovation Technology          | 37        | 6.98%   |
| Quanta                                 | 25        | 4.72%   |
| Apple                                  | 14        | 2.64%   |
| Logitech                               | 12        | 2.26%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 2.26%   |
| Syntek                                 | 8         | 1.51%   |
| Luxvisions Innotech Limited            | 8         | 1.51%   |
| Lite-On Technology                     | 8         | 1.51%   |
| Suyin                                  | 7         | 1.32%   |
| Samsung Electronics                    | 7         | 1.32%   |
| Sonix Technology                       | 6         | 1.13%   |
| ALi                                    | 6         | 1.13%   |
| Silicon Motion                         | 5         | 0.94%   |
| Ricoh                                  | 5         | 0.94%   |
| SunplusIT                              | 3         | 0.57%   |
| Alcor Micro                            | 3         | 0.57%   |
| Z-Star Microelectronics                | 2         | 0.38%   |
| Microsoft                              | 2         | 0.38%   |
| Lenovo                                 | 2         | 0.38%   |
| kingcome                               | 2         | 0.38%   |
| Acer                                   | 2         | 0.38%   |
| Y Media                                | 1         | 0.19%   |
| webcam                                 | 1         | 0.19%   |
| Trust                                  | 1         | 0.19%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.19%   |
| Razer USA                              | 1         | 0.19%   |
| Nokia Mobile Phones                    | 1         | 0.19%   |
| Nikon                                  | 1         | 0.19%   |
| LianYi                                 | 1         | 0.19%   |
| icSpring                               | 1         | 0.19%   |
| DigiTech                               | 1         | 0.19%   |
| Dell                                   | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                 | 30        | 5.62%   |
| Chicony Integrated Camera                     | 29        | 5.43%   |
| Realtek Integrated_Webcam_HD                  | 21        | 3.93%   |
| IMC Networks Integrated Camera                | 20        | 3.75%   |
| IMC Networks USB2.0 HD UVC WebCam             | 15        | 2.81%   |
| Bison Integrated Camera                       | 14        | 2.62%   |
| Sunplus Integrated_Webcam_HD                  | 11        | 2.06%   |
| Sunplus Integrated_Webcam_FHD                 | 10        | 1.87%   |
| Apple Built-in iSight                         | 9         | 1.69%   |
| IMC Networks EasyCamera                       | 8         | 1.5%    |
| Chicony HD WebCam                             | 8         | 1.5%    |
| Samsung Galaxy series, misc. (MTP mode)       | 7         | 1.31%   |
| Chicony USB2.0 Camera                         | 7         | 1.31%   |
| Microdia Integrated Webcam                    | 6         | 1.12%   |
| Lite-On HP HD Camera                          | 6         | 1.12%   |
| Chicony Integrated Camera (1280x720@30)       | 6         | 1.12%   |
| Syntek Integrated Camera                      | 5         | 0.94%   |
| Realtek Integrated Webcam HD                  | 5         | 0.94%   |
| Chicony HP Wide Vision HD Camera              | 5         | 0.94%   |
| Chicony HP HD Camera                          | 5         | 0.94%   |
| Bison EasyCamera                              | 5         | 0.94%   |
| Bison BisonCam,NB Pro                         | 5         | 0.94%   |
| Bison BisonCam, NB Pro                        | 5         | 0.94%   |
| Sonix USB2.0 FHD UVC WebCam                   | 4         | 0.75%   |
| Realtek Integrated_Webcam_FHD                 | 4         | 0.75%   |
| Microdia Webcam Vitade AF                     | 4         | 0.75%   |
| Luxvisions Innotech Limited Integrated Camera | 4         | 0.75%   |
| Chicony USB2.0 HD UVC WebCam                  | 4         | 0.75%   |
| Chicony TOSHIBA Web Camera - HD               | 4         | 0.75%   |
| Chicony Integrated IR Camera                  | 4         | 0.75%   |
| Chicony HP Truevision HD camera               | 4         | 0.75%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 4         | 0.75%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 3         | 0.56%   |
| Sunplus Integrated Camera                     | 3         | 0.56%   |
| Sunplus HP HD Webcam [Fixed]                  | 3         | 0.56%   |
| Realtek USB2.0 HD UVC WebCam                  | 3         | 0.56%   |
| Realtek Integrated Webcam                     | 3         | 0.56%   |
| Realtek EasyCamera                            | 3         | 0.56%   |
| Quanta USB2.0 HD UVC WebCam                   | 3         | 0.56%   |
| Quanta HP HD Camera                           | 3         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 45        | 40.54%  |
| Validity Sensors           | 30        | 27.03%  |
| Shenzhen Goodix Technology | 15        | 13.51%  |
| Upek                       | 6         | 5.41%   |
| Elan Microelectronics      | 6         | 5.41%   |
| AuthenTec                  | 4         | 3.6%    |
| LighTuning Technology      | 3         | 2.7%    |
| STMicroelectronics         | 1         | 0.9%    |
| Focal-systems.Corp         | 1         | 0.9%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 8.11%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 8.11%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 7.21%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 5.41%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 5.41%   |
| Synaptics UWP WBDI Device                                                  | 5         | 4.5%    |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 4.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 4.5%    |
| Elan ELAN:ARM-M4                                                           | 5         | 4.5%    |
| Unknown                                                                    | 5         | 4.5%    |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 3.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.7%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.7%    |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.7%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 2.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 2.7%    |
| AuthenTec Fingerprint Sensor                                               | 3         | 2.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.8%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.8%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.8%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.8%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.8%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.9%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.9%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 0.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.9%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.9%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.9%    |
| Synaptics WBDI Device                                                      | 1         | 0.9%    |
| Synaptics WBDI                                                             | 1         | 0.9%    |
| Synaptics TouchPad                                                         | 1         | 0.9%    |
| Synaptics  WBDI                                                            | 1         | 0.9%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.9%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.9%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.9%    |
| Elan ELAN:Fingerprint                                                      | 1         | 0.9%    |
| AuthenTec AES2810                                                          | 1         | 0.9%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 50        | 64.94%  |
| Alcor Micro           | 12        | 15.58%  |
| Upek                  | 7         | 9.09%   |
| O2 Micro              | 5         | 6.49%   |
| Lenovo                | 2         | 2.6%    |
| Gemalto (was Gemplus) | 1         | 1.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 18        | 23.38%  |
| Broadcom 5880                                                                | 14        | 18.18%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 15.58%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 12.99%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 6.49%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 5.19%   |
| Broadcom 58200                                                               | 3         | 3.9%    |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.6%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 326       | 54.33%  |
| 1     | 224       | 37.33%  |
| 2     | 42        | 7%      |
| 3     | 8         | 1.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 109       | 34.28%  |
| Chipcard                 | 67        | 21.07%  |
| Graphics card            | 58        | 18.24%  |
| Net/wireless             | 39        | 12.26%  |
| Multimedia controller    | 9         | 2.83%   |
| Camera                   | 8         | 2.52%   |
| Storage                  | 7         | 2.2%    |
| Communication controller | 5         | 1.57%   |
| Bluetooth                | 5         | 1.57%   |
| Net/ethernet             | 4         | 1.26%   |
| Card reader              | 4         | 1.26%   |
| Modem                    | 2         | 0.63%   |
| Network                  | 1         | 0.31%   |

