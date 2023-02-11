Linux in UK - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

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

Total: 4875

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T470s 20HF0000U... | [d7a5b537d9](https://linux-hardware.org/?probe=d7a5b537d9) | Feb 01, 2023 |
| HP            | Sona                        | [36a3d72172](https://linux-hardware.org/?probe=36a3d72172) | Jan 31, 2023 |
| Lenovo        | Yoga 3 14 80JH              | [6c66b66a78](https://linux-hardware.org/?probe=6c66b66a78) | Jan 30, 2023 |
| Valve         | Jupiter                     | [9568a6f43d](https://linux-hardware.org/?probe=9568a6f43d) | Jan 30, 2023 |
| Acer          | Aspire A515-52              | [51fa3ff577](https://linux-hardware.org/?probe=51fa3ff577) | Jan 30, 2023 |
| HP            | Laptop 14-cm0xxx            | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Valve         | Jupiter                     | [91ef57c9e5](https://linux-hardware.org/?probe=91ef57c9e5) | Jan 29, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [3912652a13](https://linux-hardware.org/?probe=3912652a13) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| Dell          | Latitude E6530              | [87bca9f2a4](https://linux-hardware.org/?probe=87bca9f2a4) | Jan 29, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ed1ce46901](https://linux-hardware.org/?probe=ed1ce46901) | Jan 28, 2023 |
| Dell          | Inspiron 14-3452            | [baf61affa2](https://linux-hardware.org/?probe=baf61affa2) | Jan 28, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [c4877a8bc3](https://linux-hardware.org/?probe=c4877a8bc3) | Jan 28, 2023 |
| Apple         | MacBookAir7,2               | [b5f0169944](https://linux-hardware.org/?probe=b5f0169944) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ab3f84f96b](https://linux-hardware.org/?probe=ab3f84f96b) | Jan 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0245809d6a](https://linux-hardware.org/?probe=0245809d6a) | Jan 28, 2023 |
| Notebook      | P17SM-A                     | [609a89ca14](https://linux-hardware.org/?probe=609a89ca14) | Jan 27, 2023 |
| HP            | EliteBook 8530w             | [f395c475c9](https://linux-hardware.org/?probe=f395c475c9) | Jan 27, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | [e171a529b9](https://linux-hardware.org/?probe=e171a529b9) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| Dell          | Inspiron 15 3521            | [41f89081ff](https://linux-hardware.org/?probe=41f89081ff) | Jan 26, 2023 |
| Acer          | Aspire ES1-411              | [110767fd86](https://linux-hardware.org/?probe=110767fd86) | Jan 26, 2023 |
| MSI           | Katana GF66 11UE            | [aead8d4d18](https://linux-hardware.org/?probe=aead8d4d18) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [de8222900d](https://linux-hardware.org/?probe=de8222900d) | Jan 26, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0Q... | [cdd3eb5723](https://linux-hardware.org/?probe=cdd3eb5723) | Jan 26, 2023 |
| Notebook      | P17SM-A                     | [6ed204eca5](https://linux-hardware.org/?probe=6ed204eca5) | Jan 26, 2023 |
| Google        | Careena                     | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | [6faa58b4a1](https://linux-hardware.org/?probe=6faa58b4a1) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | [f437e45107](https://linux-hardware.org/?probe=f437e45107) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | [9dfb8ac7b0](https://linux-hardware.org/?probe=9dfb8ac7b0) | Jan 25, 2023 |
| OEGStone      | C4100/C5100                 | [4365b7b231](https://linux-hardware.org/?probe=4365b7b231) | Jan 25, 2023 |
| Dell          | Latitude 5520               | [662284824b](https://linux-hardware.org/?probe=662284824b) | Jan 24, 2023 |
| HP            | EliteBook 745 G2            | [0d073c35f4](https://linux-hardware.org/?probe=0d073c35f4) | Jan 24, 2023 |
| Toshiba       | Satellite Pro C660          | [3ffb5ed458](https://linux-hardware.org/?probe=3ffb5ed458) | Jan 24, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [97ca64cad1](https://linux-hardware.org/?probe=97ca64cad1) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [4f83721cab](https://linux-hardware.org/?probe=4f83721cab) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [9e12a145fd](https://linux-hardware.org/?probe=9e12a145fd) | Jan 23, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e9124adb70](https://linux-hardware.org/?probe=e9124adb70) | Jan 23, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [e1eeca8eab](https://linux-hardware.org/?probe=e1eeca8eab) | Jan 23, 2023 |
| Lenovo        | Z51-70 80K6                 | [f0cce92dd4](https://linux-hardware.org/?probe=f0cce92dd4) | Jan 23, 2023 |
| Lenovo        | Flex 2-15D 20377            | [e4a2f02d89](https://linux-hardware.org/?probe=e4a2f02d89) | Jan 23, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [37f26b2f10](https://linux-hardware.org/?probe=37f26b2f10) | Jan 23, 2023 |
| Sony          | SVF1521Q1EW                 | [1e8cceb35b](https://linux-hardware.org/?probe=1e8cceb35b) | Jan 23, 2023 |
| Dell          | Precision M6800             | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [d971cd0912](https://linux-hardware.org/?probe=d971cd0912) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [fe4b24bf26](https://linux-hardware.org/?probe=fe4b24bf26) | Jan 21, 2023 |
| Dell          | XPS 13 7390                 | [97b14c6835](https://linux-hardware.org/?probe=97b14c6835) | Jan 20, 2023 |
| Sony          | SVE1513B4E                  | [cbd9f98f30](https://linux-hardware.org/?probe=cbd9f98f30) | Jan 20, 2023 |
| HP            | Unknown                     | [b82faadc9d](https://linux-hardware.org/?probe=b82faadc9d) | Jan 19, 2023 |
| Dell          | XPS 13 7390                 | [01f3a78934](https://linux-hardware.org/?probe=01f3a78934) | Jan 19, 2023 |
| Dell          | XPS 15 9570                 | [ebd319efff](https://linux-hardware.org/?probe=ebd319efff) | Jan 19, 2023 |
| Apple         | MacBook8,1                  | [17e254a9ec](https://linux-hardware.org/?probe=17e254a9ec) | Jan 19, 2023 |
| PC Special... | Elimina Iv 17               | [72e46e7bad](https://linux-hardware.org/?probe=72e46e7bad) | Jan 18, 2023 |
| Toshiba       | Satellite L70-C-12H         | [aa6340dd48](https://linux-hardware.org/?probe=aa6340dd48) | Jan 18, 2023 |
| Novatech      | NL40_50CU                   | [395dab7c43](https://linux-hardware.org/?probe=395dab7c43) | Jan 18, 2023 |
| Dell          | Inspiron N5110              | [bf606ed50a](https://linux-hardware.org/?probe=bf606ed50a) | Jan 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [4b8096c4d2](https://linux-hardware.org/?probe=4b8096c4d2) | Jan 18, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [6d93895cac](https://linux-hardware.org/?probe=6d93895cac) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [0306622813](https://linux-hardware.org/?probe=0306622813) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [03c7a9b8a1](https://linux-hardware.org/?probe=03c7a9b8a1) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [84edd23a21](https://linux-hardware.org/?probe=84edd23a21) | Jan 18, 2023 |
| Dell          | Latitude E5440              | [eb945eac4e](https://linux-hardware.org/?probe=eb945eac4e) | Jan 18, 2023 |
| Notebook      | PCx0Dx                      | [658ed38b10](https://linux-hardware.org/?probe=658ed38b10) | Jan 17, 2023 |
| Notebook      | PCx0Dx                      | [44f839ccbd](https://linux-hardware.org/?probe=44f839ccbd) | Jan 17, 2023 |
| Toshiba       | Satellite C660              | [5012a7ccfc](https://linux-hardware.org/?probe=5012a7ccfc) | Jan 17, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [d05225350d](https://linux-hardware.org/?probe=d05225350d) | Jan 17, 2023 |
| Unknown       | Unknown                     | [aea2d1af0a](https://linux-hardware.org/?probe=aea2d1af0a) | Jan 17, 2023 |
| Apple         | MacBookPro7,1               | [6445b08ce9](https://linux-hardware.org/?probe=6445b08ce9) | Jan 17, 2023 |
| Apple         | MacBookPro7,1               | [5ff11074e0](https://linux-hardware.org/?probe=5ff11074e0) | Jan 17, 2023 |
| HP            | Laptop 15-dw3xxx            | [ccce363b13](https://linux-hardware.org/?probe=ccce363b13) | Jan 17, 2023 |
| Valve         | Jupiter                     | [a75cdaa463](https://linux-hardware.org/?probe=a75cdaa463) | Jan 16, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [b1581dd523](https://linux-hardware.org/?probe=b1581dd523) | Jan 16, 2023 |
| PC Special... | P65_P67RGRERA               | [39b18604bf](https://linux-hardware.org/?probe=39b18604bf) | Jan 16, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [31cf03aadd](https://linux-hardware.org/?probe=31cf03aadd) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Sony          | VGN-NW26M                   | [3660b874bc](https://linux-hardware.org/?probe=3660b874bc) | Jan 15, 2023 |
| Sony          | VGN-NW26M                   | [5b62bf0146](https://linux-hardware.org/?probe=5b62bf0146) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [dca583bf2e](https://linux-hardware.org/?probe=dca583bf2e) | Jan 15, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [9ec7c970da](https://linux-hardware.org/?probe=9ec7c970da) | Jan 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [38d732c237](https://linux-hardware.org/?probe=38d732c237) | Jan 15, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [ca73cb526c](https://linux-hardware.org/?probe=ca73cb526c) | Jan 15, 2023 |
| Dell          | Inspiron N5110              | [20625ce99d](https://linux-hardware.org/?probe=20625ce99d) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7d44980bca](https://linux-hardware.org/?probe=7d44980bca) | Jan 14, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [d113da489f](https://linux-hardware.org/?probe=d113da489f) | Jan 14, 2023 |
| Dell          | Inspiron 15 7510            | [67f4d14824](https://linux-hardware.org/?probe=67f4d14824) | Jan 14, 2023 |
| Valve         | Jupiter                     | [4d74819919](https://linux-hardware.org/?probe=4d74819919) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [da829cbbc7](https://linux-hardware.org/?probe=da829cbbc7) | Jan 14, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [e4e7a1d245](https://linux-hardware.org/?probe=e4e7a1d245) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| PC Special... | P65_67RSRP                  | [c7baf1a126](https://linux-hardware.org/?probe=c7baf1a126) | Jan 14, 2023 |
| Alienware     | 17 R3                       | [d4cf3c4f4d](https://linux-hardware.org/?probe=d4cf3c4f4d) | Jan 14, 2023 |
| Dell          | Vostro 3549                 | [b6970533c4](https://linux-hardware.org/?probe=b6970533c4) | Jan 13, 2023 |
| Valve         | Jupiter                     | [41e26fa7a1](https://linux-hardware.org/?probe=41e26fa7a1) | Jan 13, 2023 |
| Sony          | VPCEH3N6E                   | [15129f4c39](https://linux-hardware.org/?probe=15129f4c39) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS2BM00    | [afefa18c04](https://linux-hardware.org/?probe=afefa18c04) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2347B85       | [01fce134df](https://linux-hardware.org/?probe=01fce134df) | Jan 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ee7b0c337b](https://linux-hardware.org/?probe=ee7b0c337b) | Jan 12, 2023 |
| Google        | Link                        | [f73704d47a](https://linux-hardware.org/?probe=f73704d47a) | Jan 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [c3b6b8b400](https://linux-hardware.org/?probe=c3b6b8b400) | Jan 12, 2023 |
| Dell          | Latitude 3420               | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [606cb1231b](https://linux-hardware.org/?probe=606cb1231b) | Jan 12, 2023 |
| Sony          | VPCEH3N6E                   | [c10a0ccff5](https://linux-hardware.org/?probe=c10a0ccff5) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [566725e667](https://linux-hardware.org/?probe=566725e667) | Jan 12, 2023 |
| Lenovo        | ThinkPad W510 439123G       | [4fd1a4a217](https://linux-hardware.org/?probe=4fd1a4a217) | Jan 11, 2023 |
| Toshiba       | Satellite P50-C             | [1da161195b](https://linux-hardware.org/?probe=1da161195b) | Jan 11, 2023 |
| HP            | EliteBook 840 G4            | [680b0adb7b](https://linux-hardware.org/?probe=680b0adb7b) | Jan 11, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | [a25c10f2dd](https://linux-hardware.org/?probe=a25c10f2dd) | Jan 11, 2023 |
| Acer          | Swift SF314-52              | [2dc4c5a4d8](https://linux-hardware.org/?probe=2dc4c5a4d8) | Jan 10, 2023 |
| HP            | ProBook 645 G2              | [1298e3efb0](https://linux-hardware.org/?probe=1298e3efb0) | Jan 10, 2023 |
| Google        | Sparky360                   | [68e8848fba](https://linux-hardware.org/?probe=68e8848fba) | Jan 10, 2023 |
| Razer x La... | TensorBook (late 2021)      | [d798473e75](https://linux-hardware.org/?probe=d798473e75) | Jan 09, 2023 |
| Acer          | Aspire 5732Z                | [f1edf0ce01](https://linux-hardware.org/?probe=f1edf0ce01) | Jan 09, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [e86a06caea](https://linux-hardware.org/?probe=e86a06caea) | Jan 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ab227bc376](https://linux-hardware.org/?probe=ab227bc376) | Jan 09, 2023 |
| Dell          | XPS 15 9510                 | [ff6d324723](https://linux-hardware.org/?probe=ff6d324723) | Jan 08, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [652db107e8](https://linux-hardware.org/?probe=652db107e8) | Jan 08, 2023 |
| Toshiba       | Satellite Pro L450D         | [a2a9c2e730](https://linux-hardware.org/?probe=a2a9c2e730) | Jan 08, 2023 |
| Gateway       | MX8716B                     | [b8b9890719](https://linux-hardware.org/?probe=b8b9890719) | Jan 08, 2023 |
| Toshiba       | Satellite C660              | [c7fc660dd7](https://linux-hardware.org/?probe=c7fc660dd7) | Jan 08, 2023 |
| Dell          | Latitude E6400              | [9f15bde3f6](https://linux-hardware.org/?probe=9f15bde3f6) | Jan 08, 2023 |
| Dell          | Latitude 5290               | [1cd20e22fc](https://linux-hardware.org/?probe=1cd20e22fc) | Jan 07, 2023 |
| HP            | EliteBook 6930p             | [9a59c21db0](https://linux-hardware.org/?probe=9a59c21db0) | Jan 07, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1239be31f9](https://linux-hardware.org/?probe=1239be31f9) | Jan 07, 2023 |
| Valve         | Jupiter                     | [17c9c6288e](https://linux-hardware.org/?probe=17c9c6288e) | Jan 07, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [cf94b53a8b](https://linux-hardware.org/?probe=cf94b53a8b) | Jan 05, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | [19a3a4f1c3](https://linux-hardware.org/?probe=19a3a4f1c3) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | [c1a3bf015a](https://linux-hardware.org/?probe=c1a3bf015a) | Jan 04, 2023 |
| Sony          | VPCEH3N6E                   | [5253826cac](https://linux-hardware.org/?probe=5253826cac) | Jan 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [d83005eb10](https://linux-hardware.org/?probe=d83005eb10) | Jan 03, 2023 |
| ASUSTek       | X102BA                      | [5ccb37c1d7](https://linux-hardware.org/?probe=5ccb37c1d7) | Jan 03, 2023 |
| ASUSTek       | X102BA                      | [bd49b43116](https://linux-hardware.org/?probe=bd49b43116) | Jan 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [aa875f1083](https://linux-hardware.org/?probe=aa875f1083) | Jan 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9ed57548b6](https://linux-hardware.org/?probe=9ed57548b6) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| Valve         | Jupiter                     | [ae42b505d4](https://linux-hardware.org/?probe=ae42b505d4) | Jan 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7ff55c14b4](https://linux-hardware.org/?probe=7ff55c14b4) | Jan 02, 2023 |
| Acer          | Aspire A315-31              | [4a79c65764](https://linux-hardware.org/?probe=4a79c65764) | Jan 02, 2023 |
| Toshiba       | Satellite C850-1GL          | [6326869c9e](https://linux-hardware.org/?probe=6326869c9e) | Jan 02, 2023 |
| Valve         | Jupiter                     | [72a2446cd3](https://linux-hardware.org/?probe=72a2446cd3) | Jan 02, 2023 |
| Advent        | Modena M201 Blue            | [abaae97a6f](https://linux-hardware.org/?probe=abaae97a6f) | Jan 01, 2023 |
| Dell          | Inspiron 5580               | [c6a044c898](https://linux-hardware.org/?probe=c6a044c898) | Jan 01, 2023 |
| Toshiba       | EQUIUM A100                 | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| Dell          | Latitude E7270              | [09f72d101d](https://linux-hardware.org/?probe=09f72d101d) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| Packard Be... | EasyNote TM97               | [fad44d67ab](https://linux-hardware.org/?probe=fad44d67ab) | Jan 01, 2023 |
| Valve         | Jupiter                     | [10366e2627](https://linux-hardware.org/?probe=10366e2627) | Jan 01, 2023 |
| Valve         | Jupiter                     | [c0fb48bccb](https://linux-hardware.org/?probe=c0fb48bccb) | Dec 31, 2022 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [b68fa80860](https://linux-hardware.org/?probe=b68fa80860) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| Dell          | Latitude E5440              | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| Valve         | Jupiter                     | [294144217a](https://linux-hardware.org/?probe=294144217a) | Dec 30, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [5043868e71](https://linux-hardware.org/?probe=5043868e71) | Dec 30, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [465d2da36b](https://linux-hardware.org/?probe=465d2da36b) | Dec 30, 2022 |
| HP            | ZBook Studio G5             | [6d0b6881ac](https://linux-hardware.org/?probe=6d0b6881ac) | Dec 30, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [7a685e175c](https://linux-hardware.org/?probe=7a685e175c) | Dec 30, 2022 |
| Toshiba       | Satellite C850-1GL          | [f6f61f1841](https://linux-hardware.org/?probe=f6f61f1841) | Dec 30, 2022 |
| Toshiba       | Satellite C850-1GL          | [796edd73f6](https://linux-hardware.org/?probe=796edd73f6) | Dec 30, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [e7a5c8704b](https://linux-hardware.org/?probe=e7a5c8704b) | Dec 30, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [fa210be351](https://linux-hardware.org/?probe=fa210be351) | Dec 30, 2022 |
| MSI           | Stealth GS66 12UGS          | [da812c8fa2](https://linux-hardware.org/?probe=da812c8fa2) | Dec 30, 2022 |
| Apple         | MacBookAir9,1               | [d560c94d76](https://linux-hardware.org/?probe=d560c94d76) | Dec 30, 2022 |
| Dell          | Inspiron N5110              | [08682d735c](https://linux-hardware.org/?probe=08682d735c) | Dec 30, 2022 |
| Acer          | Swift SF314-57G             | [9d71d087d8](https://linux-hardware.org/?probe=9d71d087d8) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [23d1e04f4c](https://linux-hardware.org/?probe=23d1e04f4c) | Dec 29, 2022 |
| Lenovo        | Z50-70 20354                | [7b8f5e4379](https://linux-hardware.org/?probe=7b8f5e4379) | Dec 29, 2022 |
| Samsung       | NB30/N146                   | [7f9b976789](https://linux-hardware.org/?probe=7f9b976789) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f5cbe897b8](https://linux-hardware.org/?probe=f5cbe897b8) | Dec 29, 2022 |
| Unknown       | Unknown                     | [0c7bea2d0f](https://linux-hardware.org/?probe=0c7bea2d0f) | Dec 29, 2022 |
| PC Special... | PCX0DX                      | [0a33ad889c](https://linux-hardware.org/?probe=0a33ad889c) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [41f77d037b](https://linux-hardware.org/?probe=41f77d037b) | Dec 28, 2022 |
| Alienware     | M11x R2                     | [a0da72bec0](https://linux-hardware.org/?probe=a0da72bec0) | Dec 28, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Acer          | Swift SFX14-51G             | [16c5f2a610](https://linux-hardware.org/?probe=16c5f2a610) | Dec 27, 2022 |
| Valve         | Jupiter                     | [db0586ef7b](https://linux-hardware.org/?probe=db0586ef7b) | Dec 27, 2022 |
| Acer          | Predator PH317-56           | [b74460d91c](https://linux-hardware.org/?probe=b74460d91c) | Dec 27, 2022 |
| Valve         | Jupiter                     | [a1ab930dc6](https://linux-hardware.org/?probe=a1ab930dc6) | Dec 27, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [7a3513a2e1](https://linux-hardware.org/?probe=7a3513a2e1) | Dec 27, 2022 |
| HP            | Pavilion dv6                | [d759125511](https://linux-hardware.org/?probe=d759125511) | Dec 26, 2022 |
| Valve         | Jupiter                     | [1c516dc209](https://linux-hardware.org/?probe=1c516dc209) | Dec 26, 2022 |
| HP            | ENVY Notebook               | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| Star Labs     | StarLite                    | [0d27e6f7ee](https://linux-hardware.org/?probe=0d27e6f7ee) | Dec 25, 2022 |
| Lenovo        | ThinkPad T450 20BUS3GN01    | [e88a11d2bb](https://linux-hardware.org/?probe=e88a11d2bb) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0413176ecc](https://linux-hardware.org/?probe=0413176ecc) | Dec 25, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Lenovo        | ThinkPad SL 2746N8G         | [f540a3a892](https://linux-hardware.org/?probe=f540a3a892) | Dec 23, 2022 |
| Toshiba       | Satellite Pro C50-A-1MX     | [78487975ce](https://linux-hardware.org/?probe=78487975ce) | Dec 23, 2022 |
| Acer          | Swift SF314-57G             | [53678dec76](https://linux-hardware.org/?probe=53678dec76) | Dec 22, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| Dell          | Latitude E5430 non-vPro     | [cc88046606](https://linux-hardware.org/?probe=cc88046606) | Dec 22, 2022 |
| Acer          | Aspire V5-571               | [b4de144f3e](https://linux-hardware.org/?probe=b4de144f3e) | Dec 22, 2022 |
| System76      | Lemur Pro                   | [ed549bfe74](https://linux-hardware.org/?probe=ed549bfe74) | Dec 21, 2022 |
| System76      | Lemur Pro                   | [30be17e71c](https://linux-hardware.org/?probe=30be17e71c) | Dec 21, 2022 |
| Apple         | MacBook5,1                  | [d565332e52](https://linux-hardware.org/?probe=d565332e52) | Dec 21, 2022 |
| Acer          | Aspire 5735                 | [d2850b2e08](https://linux-hardware.org/?probe=d2850b2e08) | Dec 21, 2022 |
| Apple         | MacBookPro7,1               | [dbb80c6a3c](https://linux-hardware.org/?probe=dbb80c6a3c) | Dec 21, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [422faa5041](https://linux-hardware.org/?probe=422faa5041) | Dec 20, 2022 |
| RM Educati... | RM                          | [758b521362](https://linux-hardware.org/?probe=758b521362) | Dec 20, 2022 |
| Dell          | XPS 15 9510                 | [870c784f85](https://linux-hardware.org/?probe=870c784f85) | Dec 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [1b0b5a798f](https://linux-hardware.org/?probe=1b0b5a798f) | Dec 20, 2022 |
| Dell          | XPS 15 9560                 | [1f1c0123c7](https://linux-hardware.org/?probe=1f1c0123c7) | Dec 19, 2022 |
| Toshiba       | EQUIUM A300D                | [ffde5ccef4](https://linux-hardware.org/?probe=ffde5ccef4) | Dec 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [0644973fc3](https://linux-hardware.org/?probe=0644973fc3) | Dec 19, 2022 |
| HP            | 620                         | [c5ed6ae3bf](https://linux-hardware.org/?probe=c5ed6ae3bf) | Dec 19, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | [6c6dcce3d8](https://linux-hardware.org/?probe=6c6dcce3d8) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| MSI           | Delta 15 A5EFK              | [c793cb6f38](https://linux-hardware.org/?probe=c793cb6f38) | Dec 18, 2022 |
| Acer          | Aspire ES1-531              | [28dc03a1bc](https://linux-hardware.org/?probe=28dc03a1bc) | Dec 18, 2022 |
| Fusion5       | C60Bv2-128GB                | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| Valve         | Jupiter                     | [5fee494e26](https://linux-hardware.org/?probe=5fee494e26) | Dec 17, 2022 |
| Valve         | Jupiter                     | [d47eae36fe](https://linux-hardware.org/?probe=d47eae36fe) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| HP            | Pavilion g6                 | [d1bfb26644](https://linux-hardware.org/?probe=d1bfb26644) | Dec 16, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [a69be3386b](https://linux-hardware.org/?probe=a69be3386b) | Dec 16, 2022 |
| Valve         | Jupiter                     | [bb07a9abda](https://linux-hardware.org/?probe=bb07a9abda) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Acer          | Aspire ES1-512              | [302ea6f1dd](https://linux-hardware.org/?probe=302ea6f1dd) | Dec 14, 2022 |
| HP            | 355 G2                      | [c826d17369](https://linux-hardware.org/?probe=c826d17369) | Dec 14, 2022 |
| HP            | 355 G2                      | [f785946641](https://linux-hardware.org/?probe=f785946641) | Dec 14, 2022 |
| Valve         | Jupiter                     | [9330717977](https://linux-hardware.org/?probe=9330717977) | Dec 14, 2022 |
| Star Labs     | StarBook                    | [719a73ae26](https://linux-hardware.org/?probe=719a73ae26) | Dec 13, 2022 |
| HP            | ProBook 440 G7              | [ca2ba2d622](https://linux-hardware.org/?probe=ca2ba2d622) | Dec 13, 2022 |
| Lenovo        | ThinkPad T400 647419G       | [a73b681605](https://linux-hardware.org/?probe=a73b681605) | Dec 13, 2022 |
| Apple         | MacBookPro13,3              | [10b29f88c5](https://linux-hardware.org/?probe=10b29f88c5) | Dec 12, 2022 |
| MSI           | Prestige 14 A11SC           | [7fa118f812](https://linux-hardware.org/?probe=7fa118f812) | Dec 11, 2022 |
| Star Labs     | StarLite                    | [0d83c191fa](https://linux-hardware.org/?probe=0d83c191fa) | Dec 10, 2022 |
| Acer          | Aspire V5-573               | [1d88db5ee2](https://linux-hardware.org/?probe=1d88db5ee2) | Dec 10, 2022 |
| HP            | ProBook 6570b               | [073546a981](https://linux-hardware.org/?probe=073546a981) | Dec 10, 2022 |
| Star Labs     | StarLite                    | [4446ba1d6a](https://linux-hardware.org/?probe=4446ba1d6a) | Dec 10, 2022 |
| Toshiba       | Satellite C855-1W4          | [19149f22c5](https://linux-hardware.org/?probe=19149f22c5) | Dec 09, 2022 |
| Dell          | Latitude 7390               | [79812ceedd](https://linux-hardware.org/?probe=79812ceedd) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [e8fe4392be](https://linux-hardware.org/?probe=e8fe4392be) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [cf32d7158c](https://linux-hardware.org/?probe=cf32d7158c) | Dec 09, 2022 |
| Lenovo        | Z70-80 80FG                 | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [8ce314db56](https://linux-hardware.org/?probe=8ce314db56) | Dec 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [858f06f0e5](https://linux-hardware.org/?probe=858f06f0e5) | Dec 08, 2022 |
| Google        | Nami                        | [9861d341a7](https://linux-hardware.org/?probe=9861d341a7) | Dec 08, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2a30990d9](https://linux-hardware.org/?probe=d2a30990d9) | Dec 08, 2022 |
| LG Electro... | 16Z90P-K.AA78A1             | [1646f1763d](https://linux-hardware.org/?probe=1646f1763d) | Dec 08, 2022 |
| ASUSTek       | N55SF                       | [cfb7b0f7ad](https://linux-hardware.org/?probe=cfb7b0f7ad) | Dec 07, 2022 |
| Acer          | Aspire A515-45              | [7eebb7f601](https://linux-hardware.org/?probe=7eebb7f601) | Dec 07, 2022 |
| Valve         | Jupiter                     | [9fc6ea26bb](https://linux-hardware.org/?probe=9fc6ea26bb) | Dec 07, 2022 |
| Valve         | Jupiter                     | [70cd36710e](https://linux-hardware.org/?probe=70cd36710e) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [05f4b7d7cf](https://linux-hardware.org/?probe=05f4b7d7cf) | Dec 06, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [02130c9bbb](https://linux-hardware.org/?probe=02130c9bbb) | Dec 06, 2022 |
| HP            | EliteBook 2560p             | [bbe22c0ea7](https://linux-hardware.org/?probe=bbe22c0ea7) | Dec 06, 2022 |
| Valve         | Jupiter                     | [69e8f9815d](https://linux-hardware.org/?probe=69e8f9815d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [6f0ceb7a46](https://linux-hardware.org/?probe=6f0ceb7a46) | Dec 05, 2022 |
| Dell          | Latitude E5400              | [ab5b64fe8a](https://linux-hardware.org/?probe=ab5b64fe8a) | Dec 05, 2022 |
| Google        | Chell                       | [3ffe532315](https://linux-hardware.org/?probe=3ffe532315) | Dec 05, 2022 |
| HP            | EliteBook 2560p             | [21462d212f](https://linux-hardware.org/?probe=21462d212f) | Dec 05, 2022 |
| Dell          | XPS 13 9343                 | [476763a913](https://linux-hardware.org/?probe=476763a913) | Dec 05, 2022 |
| Dell          | Inspiron 5570               | [d9009fc1f5](https://linux-hardware.org/?probe=d9009fc1f5) | Dec 05, 2022 |
| Dell          | Latitude 7490               | [e75a902d11](https://linux-hardware.org/?probe=e75a902d11) | Dec 05, 2022 |
| Valve         | Jupiter                     | [13c990586f](https://linux-hardware.org/?probe=13c990586f) | Dec 05, 2022 |
| Lenovo        | ThinkPad T450 20BUS00700    | [141e7e9992](https://linux-hardware.org/?probe=141e7e9992) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f5be4eb37d](https://linux-hardware.org/?probe=f5be4eb37d) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| HP            | Notebook                    | [610cea9ebc](https://linux-hardware.org/?probe=610cea9ebc) | Dec 04, 2022 |
| Star Labs     | StarLite                    | [d4cf1b0cd0](https://linux-hardware.org/?probe=d4cf1b0cd0) | Dec 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [c99bd4ef76](https://linux-hardware.org/?probe=c99bd4ef76) | Dec 03, 2022 |
| Dell          | Latitude 5591               | [f5735acca7](https://linux-hardware.org/?probe=f5735acca7) | Dec 02, 2022 |
| Dell          | Latitude E5570              | [4db5cd2ef4](https://linux-hardware.org/?probe=4db5cd2ef4) | Dec 01, 2022 |
| Dell          | XPS 13 9310                 | [aadf1c39a0](https://linux-hardware.org/?probe=aadf1c39a0) | Dec 01, 2022 |
| Dell          | Latitude E5520              | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| HP            | ElitePad 1000 G2            | [0b05465735](https://linux-hardware.org/?probe=0b05465735) | Nov 30, 2022 |
| Dell          | Inspiron N5010              | [687aa83749](https://linux-hardware.org/?probe=687aa83749) | Nov 30, 2022 |
| Dell          | XPS 15 9500                 | [f9215967d3](https://linux-hardware.org/?probe=f9215967d3) | Nov 30, 2022 |
| Dell          | Inspiron 5570               | [9e4bdbc81d](https://linux-hardware.org/?probe=9e4bdbc81d) | Nov 29, 2022 |
| Dell          | Inspiron 5570               | [399346217e](https://linux-hardware.org/?probe=399346217e) | Nov 29, 2022 |
| HP            | Laptop 14s-fq0xxx           | [e71c023456](https://linux-hardware.org/?probe=e71c023456) | Nov 29, 2022 |
| Valve         | Jupiter                     | [0f40429822](https://linux-hardware.org/?probe=0f40429822) | Nov 29, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e0bdd2fbd2](https://linux-hardware.org/?probe=e0bdd2fbd2) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [d258962c35](https://linux-hardware.org/?probe=d258962c35) | Nov 28, 2022 |
| Timi          | TM1613                      | [37036a425d](https://linux-hardware.org/?probe=37036a425d) | Nov 28, 2022 |
| Dell          | XPS 15 7590                 | [8072eb50aa](https://linux-hardware.org/?probe=8072eb50aa) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [68e68e1e01](https://linux-hardware.org/?probe=68e68e1e01) | Nov 28, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | [6816e8f5ca](https://linux-hardware.org/?probe=6816e8f5ca) | Nov 27, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | [06c690a0e1](https://linux-hardware.org/?probe=06c690a0e1) | Nov 27, 2022 |
| Apple         | MacBookPro6,2               | [409c3edc19](https://linux-hardware.org/?probe=409c3edc19) | Nov 27, 2022 |
| Dell          | XPS 15 7590                 | [18b1ecf4fd](https://linux-hardware.org/?probe=18b1ecf4fd) | Nov 27, 2022 |
| MSI           | GL62 7QF                    | [abd74be332](https://linux-hardware.org/?probe=abd74be332) | Nov 27, 2022 |
| Valve         | Jupiter                     | [1d12c5839a](https://linux-hardware.org/?probe=1d12c5839a) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Toshiba       | Satellite C50D-B            | [c9feb7eed2](https://linux-hardware.org/?probe=c9feb7eed2) | Nov 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [759ad3eb43](https://linux-hardware.org/?probe=759ad3eb43) | Nov 26, 2022 |
| Valve         | Jupiter                     | [0a172d85fd](https://linux-hardware.org/?probe=0a172d85fd) | Nov 26, 2022 |
| Lenovo        | ThinkPad L13 20R3000FUK     | [c3ff5b014d](https://linux-hardware.org/?probe=c3ff5b014d) | Nov 26, 2022 |
| Toshiba       | Satellite C50D-B            | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Acer          | Aspire ES1-512              | [85c0936ee0](https://linux-hardware.org/?probe=85c0936ee0) | Nov 25, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0a9d327f59](https://linux-hardware.org/?probe=0a9d327f59) | Nov 25, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [869a5a808f](https://linux-hardware.org/?probe=869a5a808f) | Nov 25, 2022 |
| Acer          | Aspire A315-41              | [4408f2ceff](https://linux-hardware.org/?probe=4408f2ceff) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [770e9d413e](https://linux-hardware.org/?probe=770e9d413e) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| HP            | EliteBook 2560p             | [4c27c5511f](https://linux-hardware.org/?probe=4c27c5511f) | Nov 23, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0168e30f4f](https://linux-hardware.org/?probe=0168e30f4f) | Nov 23, 2022 |
| Apple         | MacBookPro12,1              | [063ffbb0e8](https://linux-hardware.org/?probe=063ffbb0e8) | Nov 23, 2022 |
| HP            | EliteBook 8530w             | [0c1d6d2201](https://linux-hardware.org/?probe=0c1d6d2201) | Nov 22, 2022 |
| Toshiba       | Satellite L750              | [b2e96ee4b2](https://linux-hardware.org/?probe=b2e96ee4b2) | Nov 21, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [16859cf0ca](https://linux-hardware.org/?probe=16859cf0ca) | Nov 21, 2022 |
| Alienware     | M17xR3                      | [d472e55685](https://linux-hardware.org/?probe=d472e55685) | Nov 20, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | [4a270e871f](https://linux-hardware.org/?probe=4a270e871f) | Nov 20, 2022 |
| Medion        | BEAST X25                   | [fddb326ca2](https://linux-hardware.org/?probe=fddb326ca2) | Nov 19, 2022 |
| Toshiba       | Satellite L50D-B            | [68d1c8a80a](https://linux-hardware.org/?probe=68d1c8a80a) | Nov 19, 2022 |
| ASUSTek       | K55A                        | [d09b309d4d](https://linux-hardware.org/?probe=d09b309d4d) | Nov 19, 2022 |
| Valve         | Jupiter                     | [afdcde154a](https://linux-hardware.org/?probe=afdcde154a) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [ceac47decc](https://linux-hardware.org/?probe=ceac47decc) | Nov 18, 2022 |
| HP            | EliteBook 840 G6            | [1faf8e38b4](https://linux-hardware.org/?probe=1faf8e38b4) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [5abeec1752](https://linux-hardware.org/?probe=5abeec1752) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [8f4df3bbda](https://linux-hardware.org/?probe=8f4df3bbda) | Nov 18, 2022 |
| HP            | EliteBook 8470p             | [f324f5bc16](https://linux-hardware.org/?probe=f324f5bc16) | Nov 18, 2022 |
| Acer          | Aspire 6930G                | [05ad62f97d](https://linux-hardware.org/?probe=05ad62f97d) | Nov 17, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [cc20cc9828](https://linux-hardware.org/?probe=cc20cc9828) | Nov 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [545eb5e46c](https://linux-hardware.org/?probe=545eb5e46c) | Nov 16, 2022 |
| Dell          | Latitude 5410               | [dd9eb324db](https://linux-hardware.org/?probe=dd9eb324db) | Nov 16, 2022 |
| Dell          | Vostro 3590                 | [67ffc3ab77](https://linux-hardware.org/?probe=67ffc3ab77) | Nov 16, 2022 |
| Razer x La... | TensorBook (late 2021)      | [b7fff356a7](https://linux-hardware.org/?probe=b7fff356a7) | Nov 16, 2022 |
| Toshiba       | Satellite Pro U500          | [064a36a5bb](https://linux-hardware.org/?probe=064a36a5bb) | Nov 16, 2022 |
| Dixonsxp      | F71IX1                      | [816c618ae7](https://linux-hardware.org/?probe=816c618ae7) | Nov 15, 2022 |
| OEGStone      | NOTCHA-322                  | [a5f28e095e](https://linux-hardware.org/?probe=a5f28e095e) | Nov 15, 2022 |
| Dell          | Inspiron 7501               | [15cd1d588f](https://linux-hardware.org/?probe=15cd1d588f) | Nov 15, 2022 |
| Dell          | Latitude E6320              | [a4767dfe35](https://linux-hardware.org/?probe=a4767dfe35) | Nov 14, 2022 |
| Toshiba       | Satellite L50D-B            | [6c53b0c32d](https://linux-hardware.org/?probe=6c53b0c32d) | Nov 14, 2022 |
| HP            | Pavilion dv6                | [fe166a1906](https://linux-hardware.org/?probe=fe166a1906) | Nov 14, 2022 |
| Acer          | Extensa 2530                | [ac83b4e3e9](https://linux-hardware.org/?probe=ac83b4e3e9) | Nov 14, 2022 |
| Dell          | Latitude D630               | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| HP            | EliteBook 6930p             | [4b6c28bf91](https://linux-hardware.org/?probe=4b6c28bf91) | Nov 13, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [62cbc0b03d](https://linux-hardware.org/?probe=62cbc0b03d) | Nov 13, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [305242c389](https://linux-hardware.org/?probe=305242c389) | Nov 13, 2022 |
| HP            | Presario CQ58               | [7a2e365b72](https://linux-hardware.org/?probe=7a2e365b72) | Nov 13, 2022 |
| Valve         | Jupiter                     | [5c1a39b012](https://linux-hardware.org/?probe=5c1a39b012) | Nov 13, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | [04a42845bf](https://linux-hardware.org/?probe=04a42845bf) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| HP            | ProBook 455 G2              | [1a5d0a1618](https://linux-hardware.org/?probe=1a5d0a1618) | Nov 12, 2022 |
| System76      | Oryx Pro                    | [5439d56b25](https://linux-hardware.org/?probe=5439d56b25) | Nov 12, 2022 |
| Fujitsu       | STYLISTIC Q572              | [afd0e0efc4](https://linux-hardware.org/?probe=afd0e0efc4) | Nov 12, 2022 |
| Dell          | Latitude D630               | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | [eb5ece0bb3](https://linux-hardware.org/?probe=eb5ece0bb3) | Nov 12, 2022 |
| Valve         | Jupiter                     | [54bca16c61](https://linux-hardware.org/?probe=54bca16c61) | Nov 11, 2022 |
| HP            | EliteBook 840 G3            | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| Dell          | XPS 15 7590                 | [d05d4d5371](https://linux-hardware.org/?probe=d05d4d5371) | Nov 10, 2022 |
| Valve         | Jupiter                     | [6227fbbebb](https://linux-hardware.org/?probe=6227fbbebb) | Nov 10, 2022 |
| Valve         | Jupiter                     | [340ef95fd9](https://linux-hardware.org/?probe=340ef95fd9) | Nov 08, 2022 |
| Valve         | Jupiter                     | [5673f6f505](https://linux-hardware.org/?probe=5673f6f505) | Nov 08, 2022 |
| Valve         | Jupiter                     | [1991a35643](https://linux-hardware.org/?probe=1991a35643) | Nov 08, 2022 |
| Linx          | LINX1010B                   | [fa6d1ebd57](https://linux-hardware.org/?probe=fa6d1ebd57) | Nov 07, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [185c483599](https://linux-hardware.org/?probe=185c483599) | Nov 07, 2022 |
| Entroware     | Hybris                      | [bf5c8bcbaf](https://linux-hardware.org/?probe=bf5c8bcbaf) | Nov 07, 2022 |
| Notebook      | PA70ES                      | [7254b24693](https://linux-hardware.org/?probe=7254b24693) | Nov 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [0c0bde7c74](https://linux-hardware.org/?probe=0c0bde7c74) | Nov 06, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [d763771ba6](https://linux-hardware.org/?probe=d763771ba6) | Nov 06, 2022 |
| Dell          | Inspiron 1525               | [f28061e4da](https://linux-hardware.org/?probe=f28061e4da) | Nov 06, 2022 |
| HP            | 250 G7 Notebook PC          | [d29197ed66](https://linux-hardware.org/?probe=d29197ed66) | Nov 06, 2022 |
| Dell          | G7 7700                     | [ba3a89822a](https://linux-hardware.org/?probe=ba3a89822a) | Nov 06, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [340f509c6b](https://linux-hardware.org/?probe=340f509c6b) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [256002ea80](https://linux-hardware.org/?probe=256002ea80) | Nov 06, 2022 |
| Valve         | Jupiter                     | [df94c19aa6](https://linux-hardware.org/?probe=df94c19aa6) | Nov 06, 2022 |
| Valve         | Jupiter                     | [55420be889](https://linux-hardware.org/?probe=55420be889) | Nov 05, 2022 |
| HP            | Pavilion g7                 | [4ad4ed4c47](https://linux-hardware.org/?probe=4ad4ed4c47) | Nov 05, 2022 |
| Acer          | Acadia V1.45                | [654585bbaf](https://linux-hardware.org/?probe=654585bbaf) | Nov 05, 2022 |
| HP            | 250 G7 Notebook PC          | [e5684c9b19](https://linux-hardware.org/?probe=e5684c9b19) | Nov 05, 2022 |
| Acer          | TravelMate B118-M           | [8b7e60aef0](https://linux-hardware.org/?probe=8b7e60aef0) | Nov 05, 2022 |
| Samsung       | 700T1C                      | [c561c328b3](https://linux-hardware.org/?probe=c561c328b3) | Nov 05, 2022 |
| Lenovo        | ThinkPad L520 78596CG       | [094f09bcf8](https://linux-hardware.org/?probe=094f09bcf8) | Nov 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [f0be03da28](https://linux-hardware.org/?probe=f0be03da28) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | [2a802edc5a](https://linux-hardware.org/?probe=2a802edc5a) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | [80e1206b6d](https://linux-hardware.org/?probe=80e1206b6d) | Nov 04, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [a43927efff](https://linux-hardware.org/?probe=a43927efff) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Samsung       | 400B2B/400B2B               | [a909b4b203](https://linux-hardware.org/?probe=a909b4b203) | Nov 03, 2022 |
| Star Labs     | StarBook                    | [1cfe5c0920](https://linux-hardware.org/?probe=1cfe5c0920) | Nov 02, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [c693004e08](https://linux-hardware.org/?probe=c693004e08) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| Dell          | Inspiron 15-3567            | [a9b57edf35](https://linux-hardware.org/?probe=a9b57edf35) | Nov 02, 2022 |
| Dell          | Inspiron 15 3511            | [5786a01590](https://linux-hardware.org/?probe=5786a01590) | Nov 02, 2022 |
| Acer          | Aspire A315-54              | [1421a5a4e9](https://linux-hardware.org/?probe=1421a5a4e9) | Nov 02, 2022 |
| PC Special... | Elimina Iv 15               | [f462ba9c43](https://linux-hardware.org/?probe=f462ba9c43) | Nov 02, 2022 |
| ASUSTek       | P52F                        | [a83cb4c35d](https://linux-hardware.org/?probe=a83cb4c35d) | Nov 01, 2022 |
| Packard Be... | EasyNote TK85               | [a233571587](https://linux-hardware.org/?probe=a233571587) | Oct 31, 2022 |
| ASUSTek       | G75VW                       | [6f1d41a85c](https://linux-hardware.org/?probe=6f1d41a85c) | Oct 31, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [92e9764aa0](https://linux-hardware.org/?probe=92e9764aa0) | Oct 31, 2022 |
| Acer          | Swift SF314-512             | [d6bf187cc9](https://linux-hardware.org/?probe=d6bf187cc9) | Oct 31, 2022 |
| MSI           | Modern 14 B10MW             | [cf2b620a60](https://linux-hardware.org/?probe=cf2b620a60) | Oct 31, 2022 |
| Valve         | Jupiter                     | [38d0d0e32a](https://linux-hardware.org/?probe=38d0d0e32a) | Oct 31, 2022 |
| Apple         | MacBookPro5,5               | [00e1f1f754](https://linux-hardware.org/?probe=00e1f1f754) | Oct 31, 2022 |
| Acer          | Swift SFX14-51G             | [6812d7cf22](https://linux-hardware.org/?probe=6812d7cf22) | Oct 30, 2022 |
| HP            | Pavilion 15                 | [f1eac2c0c3](https://linux-hardware.org/?probe=f1eac2c0c3) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [bf8945db85](https://linux-hardware.org/?probe=bf8945db85) | Oct 30, 2022 |
| GEO           | GeoBook3                    | [133a4460f6](https://linux-hardware.org/?probe=133a4460f6) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| Dell          | Latitude E6530              | [cdd3b5ce40](https://linux-hardware.org/?probe=cdd3b5ce40) | Oct 28, 2022 |
| Valve         | Jupiter                     | [127bd00558](https://linux-hardware.org/?probe=127bd00558) | Oct 28, 2022 |
| Tactus        | GeoBook 110                 | [aad56b27f0](https://linux-hardware.org/?probe=aad56b27f0) | Oct 28, 2022 |
| Dell          | XPS 13 9305                 | [20bf043d6f](https://linux-hardware.org/?probe=20bf043d6f) | Oct 28, 2022 |
| Valve         | Jupiter                     | [7cc988201b](https://linux-hardware.org/?probe=7cc988201b) | Oct 28, 2022 |
| HP            | ENVY Laptop 13-ba0xxx       | [920b0eaa44](https://linux-hardware.org/?probe=920b0eaa44) | Oct 27, 2022 |
| Novatech      | NLx0MU                      | [41c5d984a0](https://linux-hardware.org/?probe=41c5d984a0) | Oct 27, 2022 |
| HP            | G62                         | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Toshiba       | Satellite C660              | [80c2aeb241](https://linux-hardware.org/?probe=80c2aeb241) | Oct 26, 2022 |
| HP            | Setzer                      | [a1039409cd](https://linux-hardware.org/?probe=a1039409cd) | Oct 26, 2022 |
| HP            | Setzer                      | [3945fea013](https://linux-hardware.org/?probe=3945fea013) | Oct 25, 2022 |
| Valve         | Jupiter                     | [dc86de125e](https://linux-hardware.org/?probe=dc86de125e) | Oct 25, 2022 |
| Toshiba       | Satellite C50D-A-133        | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Valve         | Jupiter                     | [c12839567e](https://linux-hardware.org/?probe=c12839567e) | Oct 25, 2022 |
| Dell          | Inspiron 1525               | [742bf13a9f](https://linux-hardware.org/?probe=742bf13a9f) | Oct 25, 2022 |
| Lenovo        | V15-IIL 82C5                | [a56ad41b2f](https://linux-hardware.org/?probe=a56ad41b2f) | Oct 25, 2022 |
| Dell          | Inspiron 16 7610            | [47a3e2b5f6](https://linux-hardware.org/?probe=47a3e2b5f6) | Oct 24, 2022 |
| Lenovo        | ThinkPad T520 4243PN7       | [fdca71510b](https://linux-hardware.org/?probe=fdca71510b) | Oct 24, 2022 |
| AMI           | Unknown                     | [337d94fb96](https://linux-hardware.org/?probe=337d94fb96) | Oct 23, 2022 |
| HP            | OMEN by Laptop 17-ck0xxx    | [34f4204ae8](https://linux-hardware.org/?probe=34f4204ae8) | Oct 23, 2022 |
| GEO           | GeoBook 140                 | [e97f8024f4](https://linux-hardware.org/?probe=e97f8024f4) | Oct 22, 2022 |
| GEO           | GeoBook 140                 | [bbbe5e0fca](https://linux-hardware.org/?probe=bbbe5e0fca) | Oct 22, 2022 |
| Samsung       | R519/R719                   | [da6668197e](https://linux-hardware.org/?probe=da6668197e) | Oct 22, 2022 |
| HP            | OMEN by Laptop 17-ck0xxx    | [0ed2f15c34](https://linux-hardware.org/?probe=0ed2f15c34) | Oct 21, 2022 |
| Razer x La... | TensorBook (late 2021)      | [27cae45787](https://linux-hardware.org/?probe=27cae45787) | Oct 20, 2022 |
| Acer          | Aspire S3                   | [a24603a142](https://linux-hardware.org/?probe=a24603a142) | Oct 20, 2022 |
| Dell          | XPS 13 9300                 | [ec9a97a15d](https://linux-hardware.org/?probe=ec9a97a15d) | Oct 20, 2022 |
| Toshiba       | Satellite C660              | [3632c8a48d](https://linux-hardware.org/?probe=3632c8a48d) | Oct 20, 2022 |
| Valve         | Jupiter                     | [a314a908eb](https://linux-hardware.org/?probe=a314a908eb) | Oct 20, 2022 |
| Razer x La... | TensorBook (late 2021)      | [fef9e26716](https://linux-hardware.org/?probe=fef9e26716) | Oct 20, 2022 |
| Valve         | Jupiter                     | [3fada6964f](https://linux-hardware.org/?probe=3fada6964f) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [56089b3625](https://linux-hardware.org/?probe=56089b3625) | Oct 19, 2022 |
| Acer          | Aspire V5-132P              | [420ad7ac8c](https://linux-hardware.org/?probe=420ad7ac8c) | Oct 19, 2022 |
| Lenovo        | G580 2689H2G                | [1d81a2fb3b](https://linux-hardware.org/?probe=1d81a2fb3b) | Oct 18, 2022 |
| Acer          | Aspire 6930G                | [d65e0cfe7a](https://linux-hardware.org/?probe=d65e0cfe7a) | Oct 18, 2022 |
| GEO           | GeoBook 120                 | [fe063a61a7](https://linux-hardware.org/?probe=fe063a61a7) | Oct 17, 2022 |
| HP            | ZBook 15                    | [6926e1a3c0](https://linux-hardware.org/?probe=6926e1a3c0) | Oct 17, 2022 |
| Valve         | Jupiter                     | [992d2b539a](https://linux-hardware.org/?probe=992d2b539a) | Oct 17, 2022 |
| Samsung       | 700T1C                      | [b0b2e6712c](https://linux-hardware.org/?probe=b0b2e6712c) | Oct 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [ee67e90b5f](https://linux-hardware.org/?probe=ee67e90b5f) | Oct 15, 2022 |
| Valve         | Jupiter                     | [022a7cab63](https://linux-hardware.org/?probe=022a7cab63) | Oct 15, 2022 |
| Valve         | Jupiter                     | [bd47ebea62](https://linux-hardware.org/?probe=bd47ebea62) | Oct 15, 2022 |
| Valve         | Jupiter                     | [627b9225cb](https://linux-hardware.org/?probe=627b9225cb) | Oct 15, 2022 |
| HP            | Presario C300 (RM500EA#A... | [c35d7b0ee3](https://linux-hardware.org/?probe=c35d7b0ee3) | Oct 14, 2022 |
| Dell          | Precision M4800             | [aa9a1680fd](https://linux-hardware.org/?probe=aa9a1680fd) | Oct 14, 2022 |
| Lenovo        | V110-15AST 80TD             | [9d4b6fafb6](https://linux-hardware.org/?probe=9d4b6fafb6) | Oct 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [cbc3888844](https://linux-hardware.org/?probe=cbc3888844) | Oct 12, 2022 |
| Lenovo        | Z50-75 80EC                 | [7dbdbc1de9](https://linux-hardware.org/?probe=7dbdbc1de9) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Lenovo        | ThinkPad T420 4236TL7       | [8a639f4457](https://linux-hardware.org/?probe=8a639f4457) | Oct 10, 2022 |
| Valve         | Jupiter                     | [c06c56de15](https://linux-hardware.org/?probe=c06c56de15) | Oct 10, 2022 |
| Lenovo        | Yoga 3 14 80JH              | [5e65bc0e8a](https://linux-hardware.org/?probe=5e65bc0e8a) | Oct 10, 2022 |
| Dell          | XPS 13 9380                 | [5d882bd47f](https://linux-hardware.org/?probe=5d882bd47f) | Oct 09, 2022 |
| Acer          | Acadia V1.45                | [c33c96e412](https://linux-hardware.org/?probe=c33c96e412) | Oct 09, 2022 |
| Packard Be... | EasyNote TM82               | [8e3ecfd03d](https://linux-hardware.org/?probe=8e3ecfd03d) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK U904               | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Dell          | Latitude 5411               | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| HP            | ProBook 640 G3              | [03112f2830](https://linux-hardware.org/?probe=03112f2830) | Oct 08, 2022 |
| Lenovo        | V155-15API 81V5             | [c08e4bed15](https://linux-hardware.org/?probe=c08e4bed15) | Oct 07, 2022 |
| Dell          | Latitude 7480               | [ad29ce89eb](https://linux-hardware.org/?probe=ad29ce89eb) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| Valve         | Jupiter                     | [28900801aa](https://linux-hardware.org/?probe=28900801aa) | Oct 06, 2022 |
| Valve         | Jupiter                     | [64f5b28613](https://linux-hardware.org/?probe=64f5b28613) | Oct 06, 2022 |
| Lenovo        | G510 20238                  | [700e1adbbb](https://linux-hardware.org/?probe=700e1adbbb) | Oct 05, 2022 |
| Lenovo        | ThinkPad Twist 20C41A3      | [3da96ac399](https://linux-hardware.org/?probe=3da96ac399) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [790114327c](https://linux-hardware.org/?probe=790114327c) | Oct 04, 2022 |
| Acer          | Aspire ES1-523              | [a80da55e0c](https://linux-hardware.org/?probe=a80da55e0c) | Oct 04, 2022 |
| Acer          | Extensa 2530                | [684b31b41d](https://linux-hardware.org/?probe=684b31b41d) | Oct 03, 2022 |
| Dell          | Inspiron N5040              | [8ccfb39433](https://linux-hardware.org/?probe=8ccfb39433) | Oct 03, 2022 |
| Lenovo        | Flex 2-14 20404             | [b3a9474c83](https://linux-hardware.org/?probe=b3a9474c83) | Oct 03, 2022 |
| Apple         | MacBookPro11,3              | [cdcd2cf0e6](https://linux-hardware.org/?probe=cdcd2cf0e6) | Oct 02, 2022 |
| eMachines     | E525                        | [1467bc71f7](https://linux-hardware.org/?probe=1467bc71f7) | Oct 02, 2022 |
| Dell          | Inspiron 1545               | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| HP            | Notebook                    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| Valve         | Jupiter                     | [12f0d9358a](https://linux-hardware.org/?probe=12f0d9358a) | Oct 01, 2022 |
| Apple         | MacBookPro16,2              | [8eaded9cb5](https://linux-hardware.org/?probe=8eaded9cb5) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Acer          | Swift SF314-43              | [cfd0c22e29](https://linux-hardware.org/?probe=cfd0c22e29) | Sep 30, 2022 |
| Valve         | Jupiter                     | [dab0a00c02](https://linux-hardware.org/?probe=dab0a00c02) | Sep 30, 2022 |
| Valve         | Jupiter                     | [e9737fcadf](https://linux-hardware.org/?probe=e9737fcadf) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Dell          | XPS 13 7390                 | [c4ccdf9992](https://linux-hardware.org/?probe=c4ccdf9992) | Sep 30, 2022 |
| Dell          | Latitude 7430               | [2151370437](https://linux-hardware.org/?probe=2151370437) | Sep 29, 2022 |
| HP            | Compaq 6720s                | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Dell          | Inspiron 1564               | [d9dd05aa12](https://linux-hardware.org/?probe=d9dd05aa12) | Sep 29, 2022 |
| Dell          | XPS 13 9360                 | [6f1ecca2f0](https://linux-hardware.org/?probe=6f1ecca2f0) | Sep 28, 2022 |
| Lenovo        | G570 4334                   | [7b96f1db41](https://linux-hardware.org/?probe=7b96f1db41) | Sep 28, 2022 |
| MSI           | GT72S 6QE                   | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Timi          | RedmiBook Pro 15S           | [533cc3b3ae](https://linux-hardware.org/?probe=533cc3b3ae) | Sep 26, 2022 |
| Valve         | Jupiter                     | [c3305d9bff](https://linux-hardware.org/?probe=c3305d9bff) | Sep 26, 2022 |
| Jumper        | EZbook                      | [1af58cd7e7](https://linux-hardware.org/?probe=1af58cd7e7) | Sep 25, 2022 |
| Dell          | XPS 15 9510                 | [1ccf6c5c41](https://linux-hardware.org/?probe=1ccf6c5c41) | Sep 25, 2022 |
| Acer          | Aspire A315-51              | [21121aa007](https://linux-hardware.org/?probe=21121aa007) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| Dell          | Inspiron 15 5510            | [cfda1aa63a](https://linux-hardware.org/?probe=cfda1aa63a) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 23476Y7       | [8488ad9e53](https://linux-hardware.org/?probe=8488ad9e53) | Sep 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [bdc8453efc](https://linux-hardware.org/?probe=bdc8453efc) | Sep 24, 2022 |
| Acer          | Swift SF315-52              | [b9e88a43d8](https://linux-hardware.org/?probe=b9e88a43d8) | Sep 24, 2022 |
| Lenovo        | ThinkPad T440s 20ARA0YL0... | [93eedc638b](https://linux-hardware.org/?probe=93eedc638b) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dc3a97d467](https://linux-hardware.org/?probe=dc3a97d467) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | [02787c733c](https://linux-hardware.org/?probe=02787c733c) | Sep 23, 2022 |
| ASUSTek       | N750JV                      | [f69fe7dacf](https://linux-hardware.org/?probe=f69fe7dacf) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | [fe7ae61ecd](https://linux-hardware.org/?probe=fe7ae61ecd) | Sep 23, 2022 |
| Dell          | Latitude E6330              | [5f1a272734](https://linux-hardware.org/?probe=5f1a272734) | Sep 23, 2022 |
| Dell          | Latitude 5411               | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| HP            | Laptop 15-bw0xx             | [c4915d8dd2](https://linux-hardware.org/?probe=c4915d8dd2) | Sep 22, 2022 |
| MSI           | GL73 8RD                    | [f197efe030](https://linux-hardware.org/?probe=f197efe030) | Sep 22, 2022 |
| MSI           | GL73 8RD                    | [0534ef55fc](https://linux-hardware.org/?probe=0534ef55fc) | Sep 22, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [03428c1a17](https://linux-hardware.org/?probe=03428c1a17) | Sep 21, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [c859bf5e24](https://linux-hardware.org/?probe=c859bf5e24) | Sep 21, 2022 |
| Valve         | Jupiter                     | [721ede2e11](https://linux-hardware.org/?probe=721ede2e11) | Sep 20, 2022 |
| Dell          | Inspiron 5570               | [16d661b4e5](https://linux-hardware.org/?probe=16d661b4e5) | Sep 20, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | [20c7b9dcf9](https://linux-hardware.org/?probe=20c7b9dcf9) | Sep 20, 2022 |
| Lenovo        | E50-80 80J2                 | [a399d96de2](https://linux-hardware.org/?probe=a399d96de2) | Sep 20, 2022 |
| Valve         | Jupiter                     | [e60653a4c7](https://linux-hardware.org/?probe=e60653a4c7) | Sep 20, 2022 |
| Lenovo        | Legion 5-15ACH6H 82JU       | [1f48647e32](https://linux-hardware.org/?probe=1f48647e32) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| HONOR         | NMH-WCX9                    | [dd2687098a](https://linux-hardware.org/?probe=dd2687098a) | Sep 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [6b6ad790c5](https://linux-hardware.org/?probe=6b6ad790c5) | Sep 19, 2022 |
| Lenovo        | Yoga 3 14 80JH              | [7b17bd93c0](https://linux-hardware.org/?probe=7b17bd93c0) | Sep 19, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| HONOR         | NMH-WCX9                    | [060f3bd895](https://linux-hardware.org/?probe=060f3bd895) | Sep 19, 2022 |
| Panasonic     | CF-53JAWZYDE                | [f8b1ca10d1](https://linux-hardware.org/?probe=f8b1ca10d1) | Sep 19, 2022 |
| Lenovo        | E50-80 80J2                 | [1a538a3132](https://linux-hardware.org/?probe=1a538a3132) | Sep 18, 2022 |
| Dell          | Studio 1737                 | [7218731367](https://linux-hardware.org/?probe=7218731367) | Sep 18, 2022 |
| ASUSTek       | X510UQ                      | [eb619ed1c5](https://linux-hardware.org/?probe=eb619ed1c5) | Sep 18, 2022 |
| Dell          | Precision 5530              | [8fc00af945](https://linux-hardware.org/?probe=8fc00af945) | Sep 18, 2022 |
| Unknown       | Unknown                     | [1e27521b13](https://linux-hardware.org/?probe=1e27521b13) | Sep 17, 2022 |
| Acer          | Aspire V3-571               | [3f20a5e69d](https://linux-hardware.org/?probe=3f20a5e69d) | Sep 17, 2022 |
| Dell          | Latitude 7390               | [64c9b13553](https://linux-hardware.org/?probe=64c9b13553) | Sep 17, 2022 |
| HUAWEI        | BOM-WXX9                    | [0c3d62f1c9](https://linux-hardware.org/?probe=0c3d62f1c9) | Sep 17, 2022 |
| Valve         | Jupiter                     | [c4dd2bf91f](https://linux-hardware.org/?probe=c4dd2bf91f) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| HP            | Laptop 15-da0xxx            | [6341f27d68](https://linux-hardware.org/?probe=6341f27d68) | Sep 16, 2022 |
| Apple         | MacBook6,1                  | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Acidanther... | iMac19,2                    | [94b79ac6e5](https://linux-hardware.org/?probe=94b79ac6e5) | Sep 16, 2022 |
| HP            | ProBook 4340s               | [acca12f9d4](https://linux-hardware.org/?probe=acca12f9d4) | Sep 16, 2022 |
| Valve         | Jupiter                     | [9adc000021](https://linux-hardware.org/?probe=9adc000021) | Sep 15, 2022 |
| Dell          | Latitude 7490               | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | Z70-80 80FG                 | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| HP            | Laptop 15-da0xxx            | [82140783de](https://linux-hardware.org/?probe=82140783de) | Sep 14, 2022 |
| Dell          | Latitude E7250              | [80a2e50cfc](https://linux-hardware.org/?probe=80a2e50cfc) | Sep 14, 2022 |
| Dell          | XPS 15 9510                 | [44be9b9134](https://linux-hardware.org/?probe=44be9b9134) | Sep 13, 2022 |
| HP            | EliteBook 850 G6            | [b284db5ac4](https://linux-hardware.org/?probe=b284db5ac4) | Sep 13, 2022 |
| Lenovo        | Flex 2-14 20404             | [a27c60fbde](https://linux-hardware.org/?probe=a27c60fbde) | Sep 13, 2022 |
| Dell          | Inspiron 3542               | [2c5a122ce9](https://linux-hardware.org/?probe=2c5a122ce9) | Sep 12, 2022 |
| Dell          | Inspiron 3542               | [ef3098c81a](https://linux-hardware.org/?probe=ef3098c81a) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a54854cd7](https://linux-hardware.org/?probe=4a54854cd7) | Sep 12, 2022 |
| Entroware     | Orion                       | [d96888edf9](https://linux-hardware.org/?probe=d96888edf9) | Sep 12, 2022 |
| Entroware     | Orion                       | [c06e53ad80](https://linux-hardware.org/?probe=c06e53ad80) | Sep 12, 2022 |
| Dell          | Inspiron 3537               | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| Dell          | XPS 13 9350                 | [e137564f6b](https://linux-hardware.org/?probe=e137564f6b) | Sep 12, 2022 |
| Acer          | Aspire E5-576G              | [ee2635dbc8](https://linux-hardware.org/?probe=ee2635dbc8) | Sep 11, 2022 |
| HP            | Pavilion 15                 | [1e6331a36b](https://linux-hardware.org/?probe=1e6331a36b) | Sep 11, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [576eec419f](https://linux-hardware.org/?probe=576eec419f) | Sep 10, 2022 |
| Tactus        | GeoBook 110                 | [d13211f478](https://linux-hardware.org/?probe=d13211f478) | Sep 09, 2022 |
| Dell          | Inspiron 1720               | [27de3ede0c](https://linux-hardware.org/?probe=27de3ede0c) | Sep 09, 2022 |
| Star Labs     | Lite                        | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f5c538e2c7](https://linux-hardware.org/?probe=f5c538e2c7) | Sep 09, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7c3cdfba24](https://linux-hardware.org/?probe=7c3cdfba24) | Sep 08, 2022 |
| ASUSTek       | UX430UAR                    | [478d0564a6](https://linux-hardware.org/?probe=478d0564a6) | Sep 08, 2022 |
| Dell          | Precision 5770              | [41e44b27f4](https://linux-hardware.org/?probe=41e44b27f4) | Sep 08, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGA039U... | [43c002ad40](https://linux-hardware.org/?probe=43c002ad40) | Sep 07, 2022 |
| Toshiba       | Satellite NB10t-A-101       | [b824e1e3d5](https://linux-hardware.org/?probe=b824e1e3d5) | Sep 06, 2022 |
| Toshiba       | Satellite A660              | [8a76871325](https://linux-hardware.org/?probe=8a76871325) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | [a4f8e52425](https://linux-hardware.org/?probe=a4f8e52425) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | [0daca2662d](https://linux-hardware.org/?probe=0daca2662d) | Sep 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [40d6a47565](https://linux-hardware.org/?probe=40d6a47565) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [a75fed8b3f](https://linux-hardware.org/?probe=a75fed8b3f) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [cd613ebcd2](https://linux-hardware.org/?probe=cd613ebcd2) | Sep 05, 2022 |
| Clevo         | P65_P67SE                   | [9a38027b73](https://linux-hardware.org/?probe=9a38027b73) | Sep 05, 2022 |
| HP            | OMEN by Laptop 17-cb1xxx    | [f0a6826f9d](https://linux-hardware.org/?probe=f0a6826f9d) | Sep 05, 2022 |
| Valve         | Jupiter                     | [04c7e44198](https://linux-hardware.org/?probe=04c7e44198) | Sep 05, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [4641fe397a](https://linux-hardware.org/?probe=4641fe397a) | Sep 05, 2022 |
| Acer          | Aspire V5-552               | [031439a681](https://linux-hardware.org/?probe=031439a681) | Sep 04, 2022 |
| Dell          | Inspiron 5558               | [2d4eeaf028](https://linux-hardware.org/?probe=2d4eeaf028) | Sep 03, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [1822ab5853](https://linux-hardware.org/?probe=1822ab5853) | Sep 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [2c5c9d2233](https://linux-hardware.org/?probe=2c5c9d2233) | Sep 02, 2022 |
| Dell          | Precision 5530              | [0151d15e28](https://linux-hardware.org/?probe=0151d15e28) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [9cabeefea8](https://linux-hardware.org/?probe=9cabeefea8) | Sep 01, 2022 |
| ASUSTek       | N552VW                      | [99d4a9be86](https://linux-hardware.org/?probe=99d4a9be86) | Sep 01, 2022 |
| Lenovo        | ThinkPad T400 6474W7T       | [f9a9b12b37](https://linux-hardware.org/?probe=f9a9b12b37) | Sep 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [55073b08dc](https://linux-hardware.org/?probe=55073b08dc) | Sep 01, 2022 |
| Lenovo        | ThinkPad T400 6474W7T       | [b52974ac00](https://linux-hardware.org/?probe=b52974ac00) | Sep 01, 2022 |
| HUAWEI        | HKD-WXX                     | [7ff88a93c2](https://linux-hardware.org/?probe=7ff88a93c2) | Sep 01, 2022 |
| HP            | Pavilion g6                 | [cc725d880c](https://linux-hardware.org/?probe=cc725d880c) | Aug 31, 2022 |
| HP            | ProBook 450 G6              | [7763040d56](https://linux-hardware.org/?probe=7763040d56) | Aug 30, 2022 |
| Valve         | Jupiter                     | [1b38f48059](https://linux-hardware.org/?probe=1b38f48059) | Aug 30, 2022 |
| Acer          | Aspire 5680                 | [e58163df64](https://linux-hardware.org/?probe=e58163df64) | Aug 30, 2022 |
| Dell          | Precision M6400             | [3cf32e24fa](https://linux-hardware.org/?probe=3cf32e24fa) | Aug 30, 2022 |
| Standard      | Unknown                     | [62e0164e5b](https://linux-hardware.org/?probe=62e0164e5b) | Aug 29, 2022 |
| Dell          | XPS 13 9305                 | [d8bd3d6fc6](https://linux-hardware.org/?probe=d8bd3d6fc6) | Aug 28, 2022 |
| HP            | Laptop 15-db0xxx            | [d67f262815](https://linux-hardware.org/?probe=d67f262815) | Aug 28, 2022 |
| Dell          | Studio 1735                 | [912f409b37](https://linux-hardware.org/?probe=912f409b37) | Aug 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | [1d29556c76](https://linux-hardware.org/?probe=1d29556c76) | Aug 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8841ba5f53](https://linux-hardware.org/?probe=8841ba5f53) | Aug 27, 2022 |
| Dell          | Latitude E6510              | [846791d8b9](https://linux-hardware.org/?probe=846791d8b9) | Aug 26, 2022 |
| HUAWEI        | KLVD-WXX9                   | [c8eb396b68](https://linux-hardware.org/?probe=c8eb396b68) | Aug 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [62ce95ce9c](https://linux-hardware.org/?probe=62ce95ce9c) | Aug 26, 2022 |
| Dell          | Vostro 5625                 | [741abbfe3d](https://linux-hardware.org/?probe=741abbfe3d) | Aug 26, 2022 |
| Acer          | Aspire 5680                 | [8ee728569a](https://linux-hardware.org/?probe=8ee728569a) | Aug 25, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [2a441a673b](https://linux-hardware.org/?probe=2a441a673b) | Aug 25, 2022 |
| Acer          | Aspire 5742G                | [dfe17e89f1](https://linux-hardware.org/?probe=dfe17e89f1) | Aug 25, 2022 |
| Valve         | Jupiter                     | [b74760105e](https://linux-hardware.org/?probe=b74760105e) | Aug 25, 2022 |
| Linx          | LINX1010B                   | [07194b77d4](https://linux-hardware.org/?probe=07194b77d4) | Aug 24, 2022 |
| Dell          | XPS 15 9520                 | [e4f7ce1ec7](https://linux-hardware.org/?probe=e4f7ce1ec7) | Aug 23, 2022 |
| Acer          | Nitro AN517-51              | [e53f196e21](https://linux-hardware.org/?probe=e53f196e21) | Aug 23, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [2ac415ca87](https://linux-hardware.org/?probe=2ac415ca87) | Aug 23, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [a48fff902b](https://linux-hardware.org/?probe=a48fff902b) | Aug 23, 2022 |
| Dell          | Inspiron 5567               | [7b0f03259b](https://linux-hardware.org/?probe=7b0f03259b) | Aug 23, 2022 |
| HUAWEI        | NBD-WXX9                    | [4391428197](https://linux-hardware.org/?probe=4391428197) | Aug 22, 2022 |
| Acer          | TravelMate 5760             | [3d9c208d81](https://linux-hardware.org/?probe=3d9c208d81) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [d08e00053f](https://linux-hardware.org/?probe=d08e00053f) | Aug 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f94ce7d00a](https://linux-hardware.org/?probe=f94ce7d00a) | Aug 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [5b8c529dab](https://linux-hardware.org/?probe=5b8c529dab) | Aug 22, 2022 |
| Apple         | MacBookPro12,1              | [e4dec4681f](https://linux-hardware.org/?probe=e4dec4681f) | Aug 22, 2022 |
| Acer          | Aspire 5740                 | [19158f2e35](https://linux-hardware.org/?probe=19158f2e35) | Aug 21, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [01416789ab](https://linux-hardware.org/?probe=01416789ab) | Aug 21, 2022 |
| Samsung       | R519/R719                   | [c0720d7924](https://linux-hardware.org/?probe=c0720d7924) | Aug 21, 2022 |
| HP            | ProBook 6570b               | [eba0cd02ec](https://linux-hardware.org/?probe=eba0cd02ec) | Aug 21, 2022 |
| HP            | Laptop 17-cp0xxx            | [6ba8616656](https://linux-hardware.org/?probe=6ba8616656) | Aug 20, 2022 |
| Acer          | Aspire one 1-431            | [cd1755e81d](https://linux-hardware.org/?probe=cd1755e81d) | Aug 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [b7c760ecee](https://linux-hardware.org/?probe=b7c760ecee) | Aug 19, 2022 |
| Valve         | Jupiter                     | [d6b92d1aa0](https://linux-hardware.org/?probe=d6b92d1aa0) | Aug 19, 2022 |
| Apple         | MacBookPro9,2               | [23fb1e2721](https://linux-hardware.org/?probe=23fb1e2721) | Aug 19, 2022 |
| Apple         | MacBookPro9,2               | [eb35a0b474](https://linux-hardware.org/?probe=eb35a0b474) | Aug 18, 2022 |
| Dell          | Inspiron 7570               | [7d353117aa](https://linux-hardware.org/?probe=7d353117aa) | Aug 18, 2022 |
| Dell          | Inspiron 7570               | [10609a18a8](https://linux-hardware.org/?probe=10609a18a8) | Aug 18, 2022 |
| Apple         | MacBookAir6,2               | [f27c089486](https://linux-hardware.org/?probe=f27c089486) | Aug 18, 2022 |
| Lenovo        | Z51-70 80K6                 | [f10fe1f561](https://linux-hardware.org/?probe=f10fe1f561) | Aug 18, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [e056c24d1d](https://linux-hardware.org/?probe=e056c24d1d) | Aug 18, 2022 |
| HP            | Laptop 14-cm0xxx            | [e6b2ec9760](https://linux-hardware.org/?probe=e6b2ec9760) | Aug 17, 2022 |
| Dell          | XPS 15 9560                 | [d971bbde47](https://linux-hardware.org/?probe=d971bbde47) | Aug 17, 2022 |
| Valve         | Jupiter                     | [c395a0f9db](https://linux-hardware.org/?probe=c395a0f9db) | Aug 16, 2022 |
| Lenovo        | G505s 20255                 | [58a439770d](https://linux-hardware.org/?probe=58a439770d) | Aug 15, 2022 |
| Apple         | MacBookPro10,1              | [c4738a316c](https://linux-hardware.org/?probe=c4738a316c) | Aug 15, 2022 |
| HP            | ProBook 6570b               | [b490a791c0](https://linux-hardware.org/?probe=b490a791c0) | Aug 15, 2022 |
| Lenovo        | IdeaPad Z580                | [f9d6b2f915](https://linux-hardware.org/?probe=f9d6b2f915) | Aug 14, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [1db8ed0da4](https://linux-hardware.org/?probe=1db8ed0da4) | Aug 14, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [105367d5d6](https://linux-hardware.org/?probe=105367d5d6) | Aug 14, 2022 |
| Notebook      | NL40_50CU                   | [dc6838dde5](https://linux-hardware.org/?probe=dc6838dde5) | Aug 14, 2022 |
| Notebook      | NL40_50CU                   | [84a0545593](https://linux-hardware.org/?probe=84a0545593) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [b3df3a51e0](https://linux-hardware.org/?probe=b3df3a51e0) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2043908eed](https://linux-hardware.org/?probe=2043908eed) | Aug 14, 2022 |
| HP            | Laptop 17-cn0xxx            | [0006dc34cf](https://linux-hardware.org/?probe=0006dc34cf) | Aug 14, 2022 |
| Notebook      | PCx0Dx                      | [b3df6d2bd8](https://linux-hardware.org/?probe=b3df6d2bd8) | Aug 13, 2022 |
| Notebook      | PCx0Dx                      | [a92687ac04](https://linux-hardware.org/?probe=a92687ac04) | Aug 13, 2022 |
| Toshiba       | Satellite C660              | [50d9a2d6fe](https://linux-hardware.org/?probe=50d9a2d6fe) | Aug 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SBD000    | [b0bbce7c9d](https://linux-hardware.org/?probe=b0bbce7c9d) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [dbbd0524d8](https://linux-hardware.org/?probe=dbbd0524d8) | Aug 12, 2022 |
| Valve         | Jupiter                     | [c6e02c54e7](https://linux-hardware.org/?probe=c6e02c54e7) | Aug 11, 2022 |
| HP            | Pavilion g6                 | [a03cc7e650](https://linux-hardware.org/?probe=a03cc7e650) | Aug 11, 2022 |
| Dell          | Inspiron 5570               | [b94818059a](https://linux-hardware.org/?probe=b94818059a) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | [8090e74c22](https://linux-hardware.org/?probe=8090e74c22) | Aug 10, 2022 |
| HP            | ProBook 6570b               | [0acbdaf806](https://linux-hardware.org/?probe=0acbdaf806) | Aug 10, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [6ca46e8126](https://linux-hardware.org/?probe=6ca46e8126) | Aug 09, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [ad3cfbb4c9](https://linux-hardware.org/?probe=ad3cfbb4c9) | Aug 09, 2022 |
| Acer          | Aspire 5740                 | [1934c32bc7](https://linux-hardware.org/?probe=1934c32bc7) | Aug 09, 2022 |
| HP            | G62                         | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Dell          | Inspiron 5593               | [1b59fcaefb](https://linux-hardware.org/?probe=1b59fcaefb) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [404319dfd4](https://linux-hardware.org/?probe=404319dfd4) | Aug 07, 2022 |
| Dell          | Latitude E5470              | [c39ddac6c9](https://linux-hardware.org/?probe=c39ddac6c9) | Aug 07, 2022 |
| Apple         | MacBookPro9,2               | [85dc12b4d1](https://linux-hardware.org/?probe=85dc12b4d1) | Aug 07, 2022 |
| Valve         | Jupiter                     | [d8ef9609a7](https://linux-hardware.org/?probe=d8ef9609a7) | Aug 07, 2022 |
| AMI           | Unknown                     | [d40dbd9414](https://linux-hardware.org/?probe=d40dbd9414) | Aug 07, 2022 |
| Acer          | Swift SF114-31              | [b1cba472dc](https://linux-hardware.org/?probe=b1cba472dc) | Aug 06, 2022 |
| ASUSTek       | G750JM                      | [0fc5828ad1](https://linux-hardware.org/?probe=0fc5828ad1) | Aug 06, 2022 |
| Lenovo        | V15-IIL 82C5                | [cc2c2e7ceb](https://linux-hardware.org/?probe=cc2c2e7ceb) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | [e0153e91b7](https://linux-hardware.org/?probe=e0153e91b7) | Aug 04, 2022 |
| Dell          | Latitude E6430              | [388b301ced](https://linux-hardware.org/?probe=388b301ced) | Aug 04, 2022 |
| Star Labs     | LabTop                      | [a32c7d706c](https://linux-hardware.org/?probe=a32c7d706c) | Aug 03, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c29778d816](https://linux-hardware.org/?probe=c29778d816) | Aug 03, 2022 |
| HP            | Notebook                    | [661237e74a](https://linux-hardware.org/?probe=661237e74a) | Aug 03, 2022 |
| MSI           | GE62VR 7RF                  | [e5f6f7e14c](https://linux-hardware.org/?probe=e5f6f7e14c) | Aug 03, 2022 |
| Valve         | Jupiter                     | [8689254ee7](https://linux-hardware.org/?probe=8689254ee7) | Aug 03, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [eb77f8f852](https://linux-hardware.org/?probe=eb77f8f852) | Aug 03, 2022 |
| HP            | ProBook 455 G7              | [86bdcba616](https://linux-hardware.org/?probe=86bdcba616) | Aug 02, 2022 |
| Dell          | Inspiron 5580               | [49d857e7bf](https://linux-hardware.org/?probe=49d857e7bf) | Aug 02, 2022 |
| Dell          | Latitude E7450              | [38051fe609](https://linux-hardware.org/?probe=38051fe609) | Aug 01, 2022 |
| Dell          | XPS 15 7590                 | [8a4cc1f177](https://linux-hardware.org/?probe=8a4cc1f177) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b2b969b0e3](https://linux-hardware.org/?probe=b2b969b0e3) | Aug 01, 2022 |
| Packard Be... | EasyNote TK13BZ             | [530d3ad8db](https://linux-hardware.org/?probe=530d3ad8db) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [b99b5ef83f](https://linux-hardware.org/?probe=b99b5ef83f) | Aug 01, 2022 |
| Dell          | XPS 13 9380                 | [75f131a86a](https://linux-hardware.org/?probe=75f131a86a) | Aug 01, 2022 |
| ASUSTek       | X555LAB                     | [33a1712f4d](https://linux-hardware.org/?probe=33a1712f4d) | Aug 01, 2022 |
| Toshiba       | TECRA Z40-C                 | [9612659f60](https://linux-hardware.org/?probe=9612659f60) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [3898ce2b5f](https://linux-hardware.org/?probe=3898ce2b5f) | Aug 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS02R0G    | [0aa31e3c39](https://linux-hardware.org/?probe=0aa31e3c39) | Jul 31, 2022 |
| Dell          | Latitude E6400              | [6962d36f57](https://linux-hardware.org/?probe=6962d36f57) | Jul 31, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [b3dc6e72d5](https://linux-hardware.org/?probe=b3dc6e72d5) | Jul 31, 2022 |
| Dell          | Precision M6800             | [3584b1693d](https://linux-hardware.org/?probe=3584b1693d) | Jul 31, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [521b86d8af](https://linux-hardware.org/?probe=521b86d8af) | Jul 31, 2022 |
| PC Special... | NS50MU                      | [b5dd220296](https://linux-hardware.org/?probe=b5dd220296) | Jul 29, 2022 |
| HP            | ProBook 4515s               | [b9759d3b5d](https://linux-hardware.org/?probe=b9759d3b5d) | Jul 28, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c2bcea4cf1](https://linux-hardware.org/?probe=c2bcea4cf1) | Jul 28, 2022 |
| HP            | Presario CQ56               | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| Apple         | MacBookAir7,2               | [a33f728c24](https://linux-hardware.org/?probe=a33f728c24) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [f005e0566d](https://linux-hardware.org/?probe=f005e0566d) | Jul 27, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [44954e91a2](https://linux-hardware.org/?probe=44954e91a2) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [6ae47baf6d](https://linux-hardware.org/?probe=6ae47baf6d) | Jul 26, 2022 |
| Dell          | XPS 15 9520                 | [007bab123f](https://linux-hardware.org/?probe=007bab123f) | Jul 26, 2022 |
| Dell          | XPS 15 9520                 | [b45acaf9b7](https://linux-hardware.org/?probe=b45acaf9b7) | Jul 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [414aede111](https://linux-hardware.org/?probe=414aede111) | Jul 25, 2022 |
| Gigabyte      | AORUS 17 XE4                | [0bddb42774](https://linux-hardware.org/?probe=0bddb42774) | Jul 25, 2022 |
| HP            | G61                         | [1586fc0cba](https://linux-hardware.org/?probe=1586fc0cba) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bf2cecb453](https://linux-hardware.org/?probe=bf2cecb453) | Jul 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [375ba933ba](https://linux-hardware.org/?probe=375ba933ba) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e2a1804b90](https://linux-hardware.org/?probe=e2a1804b90) | Jul 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6740b94551](https://linux-hardware.org/?probe=6740b94551) | Jul 24, 2022 |
| Dell          | Latitude E5570              | [fa3d675cde](https://linux-hardware.org/?probe=fa3d675cde) | Jul 24, 2022 |
| Lenovo        | ThinkPad X280 20KES2SN00    | [202423ba73](https://linux-hardware.org/?probe=202423ba73) | Jul 24, 2022 |
| Valve         | Jupiter                     | [3e7b7cb8cd](https://linux-hardware.org/?probe=3e7b7cb8cd) | Jul 23, 2022 |
| HP            | Pavilion g6                 | [73061b2ed5](https://linux-hardware.org/?probe=73061b2ed5) | Jul 23, 2022 |
| Dell          | Inspiron 1545               | [893377b9f7](https://linux-hardware.org/?probe=893377b9f7) | Jul 23, 2022 |
| Dell          | XPS 13 9370                 | [21e10aa056](https://linux-hardware.org/?probe=21e10aa056) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| AZW           | GT-R                        | [eb7604ea1c](https://linux-hardware.org/?probe=eb7604ea1c) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | [fe5dae3d4a](https://linux-hardware.org/?probe=fe5dae3d4a) | Jul 22, 2022 |
| Toshiba       | EQUIUM A110                 | [4b6ace9122](https://linux-hardware.org/?probe=4b6ace9122) | Jul 22, 2022 |
| Dell          | Inspiron 1525               | [6c43e1dfd6](https://linux-hardware.org/?probe=6c43e1dfd6) | Jul 22, 2022 |
| Acer          | Aspire A315-21              | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | G62                         | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Dell          | XPS 15 9520                 | [51ddccaf88](https://linux-hardware.org/?probe=51ddccaf88) | Jul 21, 2022 |
| Panasonic     | CF-53JAWZYDE                | [c1c835cb11](https://linux-hardware.org/?probe=c1c835cb11) | Jul 21, 2022 |
| Apple         | MacBookAir7,2               | [b0cdba7434](https://linux-hardware.org/?probe=b0cdba7434) | Jul 20, 2022 |
| HP            | G62                         | [3c4aab40ae](https://linux-hardware.org/?probe=3c4aab40ae) | Jul 20, 2022 |
| Dell          | Latitude 5285               | [2b46125d79](https://linux-hardware.org/?probe=2b46125d79) | Jul 20, 2022 |
| Acer          | Aspire ES1-531              | [45be1164f5](https://linux-hardware.org/?probe=45be1164f5) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| Razer         | Blade 15 Advanced Model ... | [8f3842495f](https://linux-hardware.org/?probe=8f3842495f) | Jul 18, 2022 |
| Dell          | Vostro 3559                 | [3770ab3d4c](https://linux-hardware.org/?probe=3770ab3d4c) | Jul 18, 2022 |
| Dell          | Latitude D430               | [22c020a070](https://linux-hardware.org/?probe=22c020a070) | Jul 18, 2022 |
| Lenovo        | ThinkPad W550s 20E2000PU... | [ee30c1c248](https://linux-hardware.org/?probe=ee30c1c248) | Jul 16, 2022 |
| Acer          | Nitro AN517-54              | [68f6109054](https://linux-hardware.org/?probe=68f6109054) | Jul 16, 2022 |
| Dell          | Latitude E6440              | [eabdcd7622](https://linux-hardware.org/?probe=eabdcd7622) | Jul 15, 2022 |
| HP            | ProBook 4545s               | [12575a32d1](https://linux-hardware.org/?probe=12575a32d1) | Jul 15, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [7177bb644a](https://linux-hardware.org/?probe=7177bb644a) | Jul 15, 2022 |
| Fusion5       | S14+                        | [64668fa44f](https://linux-hardware.org/?probe=64668fa44f) | Jul 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [ea2c3cd9e9](https://linux-hardware.org/?probe=ea2c3cd9e9) | Jul 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [63c4a7a0bd](https://linux-hardware.org/?probe=63c4a7a0bd) | Jul 14, 2022 |
| Dell          | Inspiron 7570               | [872ca81b40](https://linux-hardware.org/?probe=872ca81b40) | Jul 13, 2022 |
| Acer          | Predator PH315-51           | [37b04a8093](https://linux-hardware.org/?probe=37b04a8093) | Jul 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [80bb428b2a](https://linux-hardware.org/?probe=80bb428b2a) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Google        | Lindar                      | [2e12af7cf7](https://linux-hardware.org/?probe=2e12af7cf7) | Jul 11, 2022 |
| Medion        | Erazer P6661 MD60303        | [35fbb2c055](https://linux-hardware.org/?probe=35fbb2c055) | Jul 10, 2022 |
| MSI           | GF63 Thin 9RCX              | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| Dell          | Inspiron 16 7610            | [25dce193df](https://linux-hardware.org/?probe=25dce193df) | Jul 10, 2022 |
| Packard Be... | EasyNote TE69KB             | [89403f1acb](https://linux-hardware.org/?probe=89403f1acb) | Jul 09, 2022 |
| Valve         | Jupiter                     | [0c2ea27c49](https://linux-hardware.org/?probe=0c2ea27c49) | Jul 09, 2022 |
| Acer          | Aspire R3-131T              | [36851c847b](https://linux-hardware.org/?probe=36851c847b) | Jul 08, 2022 |
| HP            | G56                         | [5c38722298](https://linux-hardware.org/?probe=5c38722298) | Jul 07, 2022 |
| AZW           | SEi                         | [7556cabcae](https://linux-hardware.org/?probe=7556cabcae) | Jul 07, 2022 |
| Sony          | VGN-FS415B                  | [0387163846](https://linux-hardware.org/?probe=0387163846) | Jul 06, 2022 |
| MSI           | Raider GE66 12UH            | [59726526b6](https://linux-hardware.org/?probe=59726526b6) | Jul 06, 2022 |
| Lenovo        | S21e-20 80M4                | [968f07d190](https://linux-hardware.org/?probe=968f07d190) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [850003c6da](https://linux-hardware.org/?probe=850003c6da) | Jul 05, 2022 |
| Medion        | Erazer P6661 MD60303        | [59417db2d7](https://linux-hardware.org/?probe=59417db2d7) | Jul 05, 2022 |
| Dell          | XPS 13 7390                 | [c5155b28a7](https://linux-hardware.org/?probe=c5155b28a7) | Jul 04, 2022 |
| Apple         | MacBookAir6,2               | [072608d8d8](https://linux-hardware.org/?probe=072608d8d8) | Jul 04, 2022 |
| LG Electro... | 17Z90N-V.AA55A1             | [272164819f](https://linux-hardware.org/?probe=272164819f) | Jul 04, 2022 |
| Linx          | LINX1010B                   | [ae94ac08d9](https://linux-hardware.org/?probe=ae94ac08d9) | Jul 03, 2022 |
| Dell          | Vostro 5568                 | [c3e4fb87d2](https://linux-hardware.org/?probe=c3e4fb87d2) | Jul 03, 2022 |
| Dell          | Inspiron 7520               | [18acc5233d](https://linux-hardware.org/?probe=18acc5233d) | Jul 03, 2022 |
| Dell          | XPS 13 7390                 | [00370cb2ff](https://linux-hardware.org/?probe=00370cb2ff) | Jul 03, 2022 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | [d90a910042](https://linux-hardware.org/?probe=d90a910042) | Jul 02, 2022 |
| AWOW          | AL34                        | [be240349b7](https://linux-hardware.org/?probe=be240349b7) | Jul 02, 2022 |
| Samsung       | Q210/P210                   | [dfc97062be](https://linux-hardware.org/?probe=dfc97062be) | Jul 01, 2022 |
| Acer          | Extensa 5220                | [1ee1e31b52](https://linux-hardware.org/?probe=1ee1e31b52) | Jul 01, 2022 |
| HP            | Presario CQ56               | [af108b4933](https://linux-hardware.org/?probe=af108b4933) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| Dell          | Inspiron N5110              | [142c1c4ef2](https://linux-hardware.org/?probe=142c1c4ef2) | Jun 30, 2022 |
| Acer          | Aspire 5735                 | [b930fd3fcd](https://linux-hardware.org/?probe=b930fd3fcd) | Jun 29, 2022 |
| Toshiba       | Satellite C850-1NU          | [2b83cb161e](https://linux-hardware.org/?probe=2b83cb161e) | Jun 29, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [828f0b9ef1](https://linux-hardware.org/?probe=828f0b9ef1) | Jun 29, 2022 |
| Lenovo        | ThinkPad E590 20NB001AUK    | [f52aacfbfe](https://linux-hardware.org/?probe=f52aacfbfe) | Jun 29, 2022 |
| Toshiba       | Satellite L750              | [e01155e6ba](https://linux-hardware.org/?probe=e01155e6ba) | Jun 28, 2022 |
| HP            | Pavilion TS 14              | [f851b6a57b](https://linux-hardware.org/?probe=f851b6a57b) | Jun 28, 2022 |
| HP            | Pavilion Notebook           | [6e098b9c49](https://linux-hardware.org/?probe=6e098b9c49) | Jun 27, 2022 |
| HP            | Pavilion 15                 | [9e7a0c1889](https://linux-hardware.org/?probe=9e7a0c1889) | Jun 27, 2022 |
| Toshiba       | Satellite C870-1H2          | [edc5098a6f](https://linux-hardware.org/?probe=edc5098a6f) | Jun 27, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| Dell          | XPS 17 9710                 | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| HP            | EliteBook 2560p             | [47b4db95ed](https://linux-hardware.org/?probe=47b4db95ed) | Jun 26, 2022 |
| ASUSTek       | FX503VD                     | [f0e913f715](https://linux-hardware.org/?probe=f0e913f715) | Jun 26, 2022 |
| Dell          | XPS 17 9710                 | [f37581d70e](https://linux-hardware.org/?probe=f37581d70e) | Jun 26, 2022 |
| Acer          | Aspire A515-55G             | [d05c52e40b](https://linux-hardware.org/?probe=d05c52e40b) | Jun 26, 2022 |
| Lenovo        | S20-30 Touch 20434          | [b4ebe70967](https://linux-hardware.org/?probe=b4ebe70967) | Jun 26, 2022 |
| Dell          | XPS 13 9310                 | [fa3d29c80b](https://linux-hardware.org/?probe=fa3d29c80b) | Jun 25, 2022 |
| HP            | EliteBook 820 G2            | [e568c96372](https://linux-hardware.org/?probe=e568c96372) | Jun 25, 2022 |
| Sony          | VGN-FS415B                  | [00d146d9f4](https://linux-hardware.org/?probe=00d146d9f4) | Jun 24, 2022 |
| Medion        | Erazer P6661 MD60303        | [a678044765](https://linux-hardware.org/?probe=a678044765) | Jun 23, 2022 |
| Medion        | Erazer P6661 MD60303        | [babd561a16](https://linux-hardware.org/?probe=babd561a16) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f2b61e1e02](https://linux-hardware.org/?probe=f2b61e1e02) | Jun 23, 2022 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [13a427bd3b](https://linux-hardware.org/?probe=13a427bd3b) | Jun 23, 2022 |
| Razer         | Blade                       | [6c8b201cd9](https://linux-hardware.org/?probe=6c8b201cd9) | Jun 23, 2022 |
| Valve         | Jupiter                     | [213fbe4dd2](https://linux-hardware.org/?probe=213fbe4dd2) | Jun 22, 2022 |
| Lenovo        | V15-ADA 82C7                | [98350f1274](https://linux-hardware.org/?probe=98350f1274) | Jun 22, 2022 |
| HUAWEI        | BOD-WXX9                    | [b0d232a3c9](https://linux-hardware.org/?probe=b0d232a3c9) | Jun 20, 2022 |
| Sony          | VGN-UX27GN                  | [ed20bd45a4](https://linux-hardware.org/?probe=ed20bd45a4) | Jun 20, 2022 |
| IBM           | ThinkPad X40 2371LBG        | [e7610b86d4](https://linux-hardware.org/?probe=e7610b86d4) | Jun 20, 2022 |
| Lenovo        | ThinkPad T430 2349I46       | [3a7df4ea17](https://linux-hardware.org/?probe=3a7df4ea17) | Jun 20, 2022 |
| Lenovo        | Flex 2-15 20405             | [0cae0765c9](https://linux-hardware.org/?probe=0cae0765c9) | Jun 20, 2022 |
| HP            | 15                          | [61e6eddc93](https://linux-hardware.org/?probe=61e6eddc93) | Jun 20, 2022 |
| AVITA         | NS14A6                      | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Dell          | Inspiron 1720               | [8cc15a5651](https://linux-hardware.org/?probe=8cc15a5651) | Jun 19, 2022 |
| Lenovo        | ThinkPad T470 20HD000EUK    | [6cc2ca4099](https://linux-hardware.org/?probe=6cc2ca4099) | Jun 19, 2022 |
| Dell          | Inspiron 7370               | [e8a53b7f1b](https://linux-hardware.org/?probe=e8a53b7f1b) | Jun 18, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f399990b6e](https://linux-hardware.org/?probe=f399990b6e) | Jun 18, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | [41945e4369](https://linux-hardware.org/?probe=41945e4369) | Jun 18, 2022 |
| Sony          | VGN-P11Z_Q                  | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Acer          | Acadia V1.45                | [198f6e8fca](https://linux-hardware.org/?probe=198f6e8fca) | Jun 16, 2022 |
| HP            | ProBook 455 G3              | [507dcf06fc](https://linux-hardware.org/?probe=507dcf06fc) | Jun 16, 2022 |
| HP            | ProBook 455 G3              | [64794fafd4](https://linux-hardware.org/?probe=64794fafd4) | Jun 16, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | [8e0da08d4d](https://linux-hardware.org/?probe=8e0da08d4d) | Jun 15, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | [cf4df37657](https://linux-hardware.org/?probe=cf4df37657) | Jun 15, 2022 |
| Lenovo        | ThinkPad T430 2349AZ6       | [7369a5bd6b](https://linux-hardware.org/?probe=7369a5bd6b) | Jun 15, 2022 |
| MSI           | GP60 2OD                    | [6edff2c2ad](https://linux-hardware.org/?probe=6edff2c2ad) | Jun 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5b6f3d52c5](https://linux-hardware.org/?probe=5b6f3d52c5) | Jun 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [c1be5f13af](https://linux-hardware.org/?probe=c1be5f13af) | Jun 13, 2022 |
| Apple         | MacBookPro11,1              | [d40967b111](https://linux-hardware.org/?probe=d40967b111) | Jun 13, 2022 |
| Dell          | Studio XPS 1640             | [aac66b6b7b](https://linux-hardware.org/?probe=aac66b6b7b) | Jun 13, 2022 |
| HP            | EliteBook 820 G2            | [45ca271974](https://linux-hardware.org/?probe=45ca271974) | Jun 13, 2022 |
| Toshiba       | Satellite C55-C             | [6eef40304f](https://linux-hardware.org/?probe=6eef40304f) | Jun 13, 2022 |
| Acer          | Nitro AN515-52              | [72ea50523c](https://linux-hardware.org/?probe=72ea50523c) | Jun 13, 2022 |
| Acer          | Nitro AN515-52              | [05b64cc5de](https://linux-hardware.org/?probe=05b64cc5de) | Jun 12, 2022 |
| MSI           | P65 Creator 9SE             | [da30629803](https://linux-hardware.org/?probe=da30629803) | Jun 11, 2022 |
| Dell          | Inspiron 16 7610            | [9967260c3c](https://linux-hardware.org/?probe=9967260c3c) | Jun 11, 2022 |
| HP            | EliteBook 820 G2            | [0a0828f262](https://linux-hardware.org/?probe=0a0828f262) | Jun 11, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [83f46a355b](https://linux-hardware.org/?probe=83f46a355b) | Jun 11, 2022 |
| ASUSTek       | X555LAB                     | [8e47a3c188](https://linux-hardware.org/?probe=8e47a3c188) | Jun 10, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [53c2e38d14](https://linux-hardware.org/?probe=53c2e38d14) | Jun 10, 2022 |
| Toshiba       | Satellite L50-B             | [ce4d95c7bf](https://linux-hardware.org/?probe=ce4d95c7bf) | Jun 10, 2022 |
| Dell          | Latitude E7270              | [8d8f0db52c](https://linux-hardware.org/?probe=8d8f0db52c) | Jun 10, 2022 |
| HUAWEI        | NBD-WXX9                    | [b8e097f983](https://linux-hardware.org/?probe=b8e097f983) | Jun 10, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d29d3120fb](https://linux-hardware.org/?probe=d29d3120fb) | Jun 09, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Lenovo        | S130-11IGM 81J1             | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude E6510              | [083f1d576d](https://linux-hardware.org/?probe=083f1d576d) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | [737a4183c8](https://linux-hardware.org/?probe=737a4183c8) | Jun 07, 2022 |
| Apple         | MacBookPro11,4              | [d6662c5acf](https://linux-hardware.org/?probe=d6662c5acf) | Jun 07, 2022 |
| Lenovo        | ThinkPad T480 20L5000AUK    | [0bf67e4018](https://linux-hardware.org/?probe=0bf67e4018) | Jun 06, 2022 |
| Dell          | Latitude E6400              | [e4f54892c2](https://linux-hardware.org/?probe=e4f54892c2) | Jun 05, 2022 |
| HYPA          | FLUX                        | [76b0337ef8](https://linux-hardware.org/?probe=76b0337ef8) | Jun 05, 2022 |
| HP            | Laptop 15-bs1xx             | [e579d912d0](https://linux-hardware.org/?probe=e579d912d0) | Jun 04, 2022 |
| HP            | G62                         | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [d147abfc52](https://linux-hardware.org/?probe=d147abfc52) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [eaad038fde](https://linux-hardware.org/?probe=eaad038fde) | Jun 03, 2022 |
| Notebook      | NL40_50CU                   | [df0357703d](https://linux-hardware.org/?probe=df0357703d) | Jun 03, 2022 |
| Lenovo        | G780 2182                   | [878e602f7d](https://linux-hardware.org/?probe=878e602f7d) | Jun 02, 2022 |
| ASUSTek       | S550CA                      | [e683ab1965](https://linux-hardware.org/?probe=e683ab1965) | Jun 02, 2022 |
| Alienware     | M11x R2                     | [0b6837debb](https://linux-hardware.org/?probe=0b6837debb) | Jun 01, 2022 |
| Acer          | Aspire S3                   | [a78c44019e](https://linux-hardware.org/?probe=a78c44019e) | Jun 01, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM    | [8db5953984](https://linux-hardware.org/?probe=8db5953984) | Jun 01, 2022 |
| Dell          | G7 7700                     | [25e22bc243](https://linux-hardware.org/?probe=25e22bc243) | May 31, 2022 |
| HP            | Presario C500 (RT155EA#A... | [5eb3ee9cc2](https://linux-hardware.org/?probe=5eb3ee9cc2) | May 31, 2022 |
| Dell          | Latitude E6400              | [85d314bfd8](https://linux-hardware.org/?probe=85d314bfd8) | May 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [dc3ee2e520](https://linux-hardware.org/?probe=dc3ee2e520) | May 31, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [aae8744a5c](https://linux-hardware.org/?probe=aae8744a5c) | May 31, 2022 |
| Dell          | Latitude E6400              | [f5ae9fef9c](https://linux-hardware.org/?probe=f5ae9fef9c) | May 31, 2022 |
| HYPA          | FLUX                        | [8a69e3a34e](https://linux-hardware.org/?probe=8a69e3a34e) | May 31, 2022 |
| Alienware     | M11x R2                     | [4a364390a6](https://linux-hardware.org/?probe=4a364390a6) | May 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [5a813419eb](https://linux-hardware.org/?probe=5a813419eb) | May 30, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| Razer         | Blade                       | [d7271bb7c4](https://linux-hardware.org/?probe=d7271bb7c4) | May 30, 2022 |
| Dell          | Latitude E6540              | [ece4d207f3](https://linux-hardware.org/?probe=ece4d207f3) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| Toshiba       | Satellite C850-1KN          | [60b2c12831](https://linux-hardware.org/?probe=60b2c12831) | May 29, 2022 |
| AZW           | GT-R                        | [7823df6a86](https://linux-hardware.org/?probe=7823df6a86) | May 29, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [8d120a2350](https://linux-hardware.org/?probe=8d120a2350) | May 28, 2022 |
| PC Special... | NH5x_7xDCx_DDx              | [bd70d45ed2](https://linux-hardware.org/?probe=bd70d45ed2) | May 28, 2022 |
| Dell          | XPS 13 9305                 | [5dc9e065e3](https://linux-hardware.org/?probe=5dc9e065e3) | May 27, 2022 |
| Dell          | Precision 5530              | [2ecf3390bf](https://linux-hardware.org/?probe=2ecf3390bf) | May 27, 2022 |
| HP            | ZBook 15 G5                 | [4f083f0d35](https://linux-hardware.org/?probe=4f083f0d35) | May 25, 2022 |
| Dell          | Inspiron 3721               | [d4af21adb8](https://linux-hardware.org/?probe=d4af21adb8) | May 25, 2022 |
| Alienware     | x17 R1                      | [a4cfdafe9d](https://linux-hardware.org/?probe=a4cfdafe9d) | May 25, 2022 |
| Toshiba       | TECRA A50-C                 | [60a580cb3b](https://linux-hardware.org/?probe=60a580cb3b) | May 25, 2022 |
| Acer          | Aspire S3                   | [d91145e274](https://linux-hardware.org/?probe=d91145e274) | May 25, 2022 |
| HP            | ZBook 15 G5                 | [fea70c6484](https://linux-hardware.org/?probe=fea70c6484) | May 24, 2022 |
| Toshiba       | PORTEGE R30-A               | [94cf17bcb6](https://linux-hardware.org/?probe=94cf17bcb6) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Dell          | XPS 15 9560                 | [7152b312be](https://linux-hardware.org/?probe=7152b312be) | May 23, 2022 |
| BOX           | W54_W94_W955TU,-T,-C        | [a36f54939d](https://linux-hardware.org/?probe=a36f54939d) | May 23, 2022 |
| Entroware     | Apollo                      | [30881be24b](https://linux-hardware.org/?probe=30881be24b) | May 23, 2022 |
| Valve         | Jupiter                     | [7d3f9c0a5f](https://linux-hardware.org/?probe=7d3f9c0a5f) | May 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [fe1d187774](https://linux-hardware.org/?probe=fe1d187774) | May 22, 2022 |
| Dell          | XPS 13 9360                 | [47c446b3d8](https://linux-hardware.org/?probe=47c446b3d8) | May 22, 2022 |
| Lenovo        | S21e-20 80M4                | [90d0bb5bc0](https://linux-hardware.org/?probe=90d0bb5bc0) | May 22, 2022 |
| Lenovo        | S21e-20 80M4                | [48047cdaf6](https://linux-hardware.org/?probe=48047cdaf6) | May 22, 2022 |
| Valve         | Jupiter                     | [595b06f6c9](https://linux-hardware.org/?probe=595b06f6c9) | May 22, 2022 |
| Apple         | MacBookPro10,1              | [5bf86728dc](https://linux-hardware.org/?probe=5bf86728dc) | May 22, 2022 |
| Acer          | Aspire ES1-523              | [e856d4589a](https://linux-hardware.org/?probe=e856d4589a) | May 21, 2022 |
| Lenovo        | Z50-75 80EC                 | [adddbe7947](https://linux-hardware.org/?probe=adddbe7947) | May 21, 2022 |
| Entroware     | Triton                      | [2bfa3e5cc8](https://linux-hardware.org/?probe=2bfa3e5cc8) | May 20, 2022 |
| HP            | Laptop 15-bs0xx             | [5c989cad8d](https://linux-hardware.org/?probe=5c989cad8d) | May 20, 2022 |
| Lenovo        | V145-15AST 81MT             | [ab767eaa59](https://linux-hardware.org/?probe=ab767eaa59) | May 19, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [e30e3da709](https://linux-hardware.org/?probe=e30e3da709) | May 18, 2022 |
| Acer          | Aspire A315-21              | [8f9f8c2634](https://linux-hardware.org/?probe=8f9f8c2634) | May 18, 2022 |
| HP            | Pavilion Notebook           | [2e663e698c](https://linux-hardware.org/?probe=2e663e698c) | May 18, 2022 |
| Notebook      | NS50_70MU                   | [382192bd2c](https://linux-hardware.org/?probe=382192bd2c) | May 18, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| MSI           | Stealth GS66 12UGS          | [f92e29b330](https://linux-hardware.org/?probe=f92e29b330) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [b1afeba24a](https://linux-hardware.org/?probe=b1afeba24a) | May 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [06afc33451](https://linux-hardware.org/?probe=06afc33451) | May 16, 2022 |
| HP            | ZBook 15 G6                 | [6c433b3b60](https://linux-hardware.org/?probe=6c433b3b60) | May 16, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [ee54db9f9e](https://linux-hardware.org/?probe=ee54db9f9e) | May 16, 2022 |
| HP            | Unknown                     | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [0f70996b58](https://linux-hardware.org/?probe=0f70996b58) | May 15, 2022 |
| HP            | ProBook 6570b               | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Dell          | XPS 13 9305                 | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | Inspiron 1750               | [b37b4cdbbb](https://linux-hardware.org/?probe=b37b4cdbbb) | May 15, 2022 |
| Dell          | XPS 13 9305                 | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| Dell          | Inspiron N5110              | [2555fd899e](https://linux-hardware.org/?probe=2555fd899e) | May 15, 2022 |
| Fujitsu Si... | LIFEBOOK S7110              | [8586a581d0](https://linux-hardware.org/?probe=8586a581d0) | May 15, 2022 |
| Notebook      | NLx0MU                      | [b46632bd9a](https://linux-hardware.org/?probe=b46632bd9a) | May 14, 2022 |
| Lenovo        | ThinkPad T470 20HES1RB06    | [0d115ce977](https://linux-hardware.org/?probe=0d115ce977) | May 14, 2022 |
| HP            | Pavilion Notebook           | [44952d0fff](https://linux-hardware.org/?probe=44952d0fff) | May 13, 2022 |
| Star Labs     | Lite                        | [dbe031aada](https://linux-hardware.org/?probe=dbe031aada) | May 13, 2022 |
| AMI           | Cherry Trail CR             | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| Dell          | Precision M6600             | [730205ec1e](https://linux-hardware.org/?probe=730205ec1e) | May 11, 2022 |
| Lenovo        | ThinkPad T480 20L6S5M40M    | [f2213829f0](https://linux-hardware.org/?probe=f2213829f0) | May 11, 2022 |
| Acer          | Aspire E1-571               | [72b102de04](https://linux-hardware.org/?probe=72b102de04) | May 10, 2022 |
| HP            | EliteBook 2560p             | [debc8c7d47](https://linux-hardware.org/?probe=debc8c7d47) | May 10, 2022 |
| Acer          | Aspire E5-551               | [bef0e3659e](https://linux-hardware.org/?probe=bef0e3659e) | May 10, 2022 |
| ASUSTek       | N751JK                      | [bfdc40105f](https://linux-hardware.org/?probe=bfdc40105f) | May 10, 2022 |
| HP            | EliteBook 2730p             | [d4c5b7824d](https://linux-hardware.org/?probe=d4c5b7824d) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [20eb5bfb9f](https://linux-hardware.org/?probe=20eb5bfb9f) | May 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Clevo         | W55xEU                      | [7bdef594e1](https://linux-hardware.org/?probe=7bdef594e1) | May 09, 2022 |
| HP            | ENVY 17                     | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Acer          | Aspire 6930G                | [49228d9f61](https://linux-hardware.org/?probe=49228d9f61) | May 08, 2022 |
| Acer          | Aspire 6930G                | [912dbb8280](https://linux-hardware.org/?probe=912dbb8280) | May 08, 2022 |
| HUAWEI        | BOD-WXX9                    | [b0b389263a](https://linux-hardware.org/?probe=b0b389263a) | May 08, 2022 |
| Lenovo        | IdeaPad Z580                | [a0751c16d5](https://linux-hardware.org/?probe=a0751c16d5) | May 08, 2022 |
| Dell          | Inspiron 7501               | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| MSI           | GE63 Raider RGB 8RE         | [34bd31c9f9](https://linux-hardware.org/?probe=34bd31c9f9) | May 07, 2022 |
| HP            | ZBook 15 G5                 | [4a3960f047](https://linux-hardware.org/?probe=4a3960f047) | May 07, 2022 |
| HP            | ProBook 430 G4              | [cae67b53da](https://linux-hardware.org/?probe=cae67b53da) | May 06, 2022 |
| Acer          | Swift SF314-41              | [3dbf93ec7f](https://linux-hardware.org/?probe=3dbf93ec7f) | May 06, 2022 |
| Dell          | Inspiron 1525               | [67dbf0ac88](https://linux-hardware.org/?probe=67dbf0ac88) | May 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8aadfc9dc1](https://linux-hardware.org/?probe=8aadfc9dc1) | May 04, 2022 |
| Acer          | Aspire A515-45              | [e5f3e5b086](https://linux-hardware.org/?probe=e5f3e5b086) | May 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV0C     | [4ce87e4da1](https://linux-hardware.org/?probe=4ce87e4da1) | May 04, 2022 |
| HP            | EliteBook 820 G2            | [0e78293e95](https://linux-hardware.org/?probe=0e78293e95) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [584ec1055a](https://linux-hardware.org/?probe=584ec1055a) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [2e4fdc00b2](https://linux-hardware.org/?probe=2e4fdc00b2) | May 03, 2022 |
| ASUSTek       | E200HA                      | [399a40cb14](https://linux-hardware.org/?probe=399a40cb14) | May 03, 2022 |
| Lenovo        | Z50-75 80EC                 | [d16211782e](https://linux-hardware.org/?probe=d16211782e) | May 03, 2022 |
| Dell          | Latitude E7470              | [7991dfd7a5](https://linux-hardware.org/?probe=7991dfd7a5) | May 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [6a9dfa32d3](https://linux-hardware.org/?probe=6a9dfa32d3) | May 02, 2022 |
| Acer          | Aspire A515-45              | [8cf5364699](https://linux-hardware.org/?probe=8cf5364699) | May 02, 2022 |
| Toshiba       | Satellite P850              | [8e97662196](https://linux-hardware.org/?probe=8e97662196) | May 02, 2022 |
| Acer          | Aspire V5-573P              | [b64d1453d5](https://linux-hardware.org/?probe=b64d1453d5) | May 02, 2022 |
| ASUSTek       | UX310UA                     | [80fce5caed](https://linux-hardware.org/?probe=80fce5caed) | May 01, 2022 |
| Dell          | XPS 13 9310                 | [03b461596c](https://linux-hardware.org/?probe=03b461596c) | May 01, 2022 |
| Dell          | XPS 15 9570                 | [133b6670de](https://linux-hardware.org/?probe=133b6670de) | May 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [ab553d3a2f](https://linux-hardware.org/?probe=ab553d3a2f) | May 01, 2022 |
| Acer          | Aspire A515-45              | [a5fd51cc39](https://linux-hardware.org/?probe=a5fd51cc39) | May 01, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [3589ada8b3](https://linux-hardware.org/?probe=3589ada8b3) | Apr 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [31b081b116](https://linux-hardware.org/?probe=31b081b116) | Apr 30, 2022 |
| Valve         | Jupiter                     | [1c826aed5e](https://linux-hardware.org/?probe=1c826aed5e) | Apr 30, 2022 |
| Lenovo        | Z50-75 80EC                 | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| Lenovo        | ThinkPad T450 20BV001YMS    | [f38b762c83](https://linux-hardware.org/?probe=f38b762c83) | Apr 29, 2022 |
| Toshiba       | Satellite Pro R50-B         | [6a8bdd387c](https://linux-hardware.org/?probe=6a8bdd387c) | Apr 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [df82c076b8](https://linux-hardware.org/?probe=df82c076b8) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [34015c4874](https://linux-hardware.org/?probe=34015c4874) | Apr 29, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [06ef070e40](https://linux-hardware.org/?probe=06ef070e40) | Apr 28, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [8ef803f8c9](https://linux-hardware.org/?probe=8ef803f8c9) | Apr 28, 2022 |
| ASUSTek       | FX503VM                     | [c227966510](https://linux-hardware.org/?probe=c227966510) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | [1275aa643d](https://linux-hardware.org/?probe=1275aa643d) | Apr 27, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [37501fa5f3](https://linux-hardware.org/?probe=37501fa5f3) | Apr 27, 2022 |
| Dell          | Inspiron 5415               | [5edac5d5a6](https://linux-hardware.org/?probe=5edac5d5a6) | Apr 27, 2022 |
| Notebook      | W130SV                      | [a88535a3a5](https://linux-hardware.org/?probe=a88535a3a5) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [d23e7110f6](https://linux-hardware.org/?probe=d23e7110f6) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [3390e01a9c](https://linux-hardware.org/?probe=3390e01a9c) | Apr 27, 2022 |
| PC Special... | NJ50_70CU                   | [a9b4399cad](https://linux-hardware.org/?probe=a9b4399cad) | Apr 26, 2022 |
| MSI           | GF63 Thin 10SC              | [bc3cbdbc1f](https://linux-hardware.org/?probe=bc3cbdbc1f) | Apr 26, 2022 |
| Acer          | NC-E5-573-36PM              | [a98a807776](https://linux-hardware.org/?probe=a98a807776) | Apr 26, 2022 |
| MSI           | GP66 Leopard 11UH           | [549c216d66](https://linux-hardware.org/?probe=549c216d66) | Apr 26, 2022 |
| Dell          | XPS 13 9310                 | [1f95a73d57](https://linux-hardware.org/?probe=1f95a73d57) | Apr 26, 2022 |
| Apple         | MacBookPro11,1              | [a8626eb701](https://linux-hardware.org/?probe=a8626eb701) | Apr 26, 2022 |
| Acer          | Aspire E1-571               | [35824f9b37](https://linux-hardware.org/?probe=35824f9b37) | Apr 25, 2022 |
| HP            | Pavilion dv6                | [83093f24ef](https://linux-hardware.org/?probe=83093f24ef) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fbb2b97e0f](https://linux-hardware.org/?probe=fbb2b97e0f) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 539       | 15.31%  |
| Ubuntu 18.04       | 276       | 7.84%   |
| Ubuntu 22.04       | 134       | 3.81%   |
| Zorin 16           | 85        | 2.41%   |
| OpenMandriva 4.3   | 80        | 2.27%   |
| Linux Mint 19.3    | 68        | 1.93%   |
| Ubuntu 19.04       | 62        | 1.76%   |
| Debian 11          | 60        | 1.7%    |
| OpenMandriva 4.2   | 59        | 1.68%   |
| Pop!_OS 20.04      | 55        | 1.56%   |
| Linux Mint 20.3    | 55        | 1.56%   |
| Linux Mint 20.2    | 54        | 1.53%   |
| Arch               | 54        | 1.53%   |
| Ubuntu 20.10       | 53        | 1.51%   |
| Zorin 15           | 51        | 1.45%   |
| Ubuntu 21.10       | 51        | 1.45%   |
| Pop!_OS 22.04      | 51        | 1.45%   |
| Manjaro            | 51        | 1.45%   |
| KDE neon 20.04     | 51        | 1.45%   |
| Linux Mint 20.1    | 50        | 1.42%   |
| Ubuntu 19.10       | 49        | 1.39%   |
| Arch Rolling       | 49        | 1.39%   |
| Pop!_OS 21.04      | 45        | 1.28%   |
| Ubuntu 21.04       | 44        | 1.25%   |
| Xubuntu 20.04      | 39        | 1.11%   |
| Linux Mint 20      | 36        | 1.02%   |
| Pop!_OS 20.10      | 34        | 0.97%   |
| Pop!_OS 21.10      | 33        | 0.94%   |
| Fedora 35          | 33        | 0.94%   |
| Fedora 34          | 33        | 0.94%   |
| ArcoLinux Rolling  | 33        | 0.94%   |
| Ubuntu 18.10       | 31        | 0.88%   |
| OpenMandriva 23.01 | 31        | 0.88%   |
| Fedora 36          | 31        | 0.88%   |
| Fedora 32          | 28        | 0.8%    |
| Fedora 31          | 28        | 0.8%    |
| Kubuntu 20.04      | 25        | 0.71%   |
| Fedora 33          | 25        | 0.71%   |
| BlackPanther 18.1  | 25        | 0.71%   |
| Linux Mint 21      | 24        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1216      | 36.03%  |
| Linux Mint    | 305       | 9.04%   |
| Pop!_OS       | 204       | 6.04%   |
| OpenMandriva  | 194       | 5.75%   |
| Fedora        | 190       | 5.63%   |
| Zorin         | 144       | 4.27%   |
| Manjaro       | 116       | 3.44%   |
| Arch          | 101       | 2.99%   |
| Debian        | 96        | 2.84%   |
| Xubuntu       | 79        | 2.34%   |
| Kubuntu       | 69        | 2.04%   |
| KDE neon      | 62        | 1.84%   |
| SteamOS       | 59        | 1.75%   |
| Elementary    | 40        | 1.19%   |
| ArcoLinux     | 37        | 1.1%    |
| ROSA          | 36        | 1.07%   |
| Lubuntu       | 35        | 1.04%   |
| Ubuntu MATE   | 32        | 0.95%   |
| Endless       | 28        | 0.83%   |
| Ubuntu Unity  | 27        | 0.8%    |
| BlackPanther  | 26        | 0.77%   |
| openSUSE      | 25        | 0.74%   |
| Kali          | 23        | 0.68%   |
| Gentoo        | 23        | 0.68%   |
| Clear Linux   | 18        | 0.53%   |
| LMDE          | 17        | 0.5%    |
| Garuda Linux  | 15        | 0.44%   |
| EndeavourOS   | 14        | 0.41%   |
| Ubuntu Budgie | 13        | 0.39%   |
| MX            | 13        | 0.39%   |
| Peppermint    | 12        | 0.36%   |
| Parrot        | 11        | 0.33%   |
| CentOS        | 10        | 0.3%    |
| RHEL          | 6         | 0.18%   |
| NixOS         | 5         | 0.15%   |
| Alpine        | 5         | 0.15%   |
| PureOS        | 4         | 0.12%   |
| Artix         | 4         | 0.12%   |
| Sparky        | 3         | 0.09%   |
| Solus         | 3         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.4.0-42-generic           | 77        | 1.99%   |
| 5.16.7-desktop-1omv4003    | 76        | 1.96%   |
| 5.10.14-desktop-1omv4002   | 56        | 1.44%   |
| 5.4.0-48-generic           | 40        | 1.03%   |
| 5.4.0-52-generic           | 39        | 1.01%   |
| 5.15.0-56-generic          | 39        | 1.01%   |
| 5.15.0-52-generic          | 38        | 0.98%   |
| 5.4.0-29-generic           | 35        | 0.9%    |
| 5.3.0-40-generic           | 35        | 0.9%    |
| 5.11.0-27-generic          | 34        | 0.88%   |
| 5.4.0-26-generic           | 33        | 0.85%   |
| 5.3.0-28-generic           | 33        | 0.85%   |
| 5.15.0-46-generic          | 33        | 0.85%   |
| 5.4.0-58-generic           | 30        | 0.77%   |
| 6.1.1-desktop-1omv2290     | 29        | 0.75%   |
| 5.4.0-40-generic           | 29        | 0.75%   |
| 5.0.0-32-generic           | 29        | 0.75%   |
| 5.11.0-38-generic          | 28        | 0.72%   |
| 5.8.0-43-generic           | 25        | 0.64%   |
| 5.3.0-42-generic           | 25        | 0.64%   |
| 5.4.0-91-generic           | 24        | 0.62%   |
| 5.11.0-37-generic          | 24        | 0.62%   |
| 5.11.0-25-generic          | 24        | 0.62%   |
| 5.4.0-65-generic           | 23        | 0.59%   |
| 5.4.0-7634-generic         | 22        | 0.57%   |
| 5.4.0-33-generic           | 22        | 0.57%   |
| 5.13.0-7614-generic        | 22        | 0.57%   |
| 5.0.0-37-generic           | 22        | 0.57%   |
| 5.8.0-50-generic           | 21        | 0.54%   |
| 5.8.0-44-generic           | 21        | 0.54%   |
| 5.4.0-56-generic           | 21        | 0.54%   |
| 5.4.0-54-generic           | 21        | 0.54%   |
| 5.3.0-46-generic           | 21        | 0.54%   |
| 5.13.0-28-generic          | 21        | 0.54%   |
| 5.15.0-58-generic          | 20        | 0.52%   |
| 4.18.16-desktop-1bP        | 20        | 0.52%   |
| 5.4.0-31-generic           | 19        | 0.49%   |
| 5.15.0-41-generic          | 19        | 0.49%   |
| 5.13.0-valve21.3-1-neptune | 19        | 0.49%   |
| 5.11.0-40-generic          | 19        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 724       | 20.08%  |
| 5.15.0  | 271       | 7.52%   |
| 5.13.0  | 241       | 6.68%   |
| 5.11.0  | 241       | 6.68%   |
| 5.8.0   | 232       | 6.43%   |
| 5.3.0   | 204       | 5.66%   |
| 4.15.0  | 200       | 5.55%   |
| 5.0.0   | 137       | 3.8%    |
| 4.18.0  | 92        | 2.55%   |
| 5.10.0  | 78        | 2.16%   |
| 5.16.7  | 76        | 2.11%   |
| 5.10.14 | 56        | 1.55%   |
| 5.19.0  | 35        | 0.97%   |
| 6.1.1   | 30        | 0.83%   |
| 4.19.0  | 30        | 0.83%   |
| 4.18.16 | 21        | 0.58%   |
| 6.0.6   | 15        | 0.42%   |
| 5.17.5  | 15        | 0.42%   |
| 5.14.0  | 15        | 0.42%   |
| 4.9.60  | 12        | 0.33%   |
| 6.0.0   | 11        | 0.31%   |
| 5.17.1  | 11        | 0.31%   |
| 5.16.0  | 11        | 0.31%   |
| 5.9.16  | 10        | 0.28%   |
| 5.15.12 | 10        | 0.28%   |
| 4.4.0   | 10        | 0.28%   |
| 5.18.10 | 9         | 0.25%   |
| 5.9.0   | 8         | 0.22%   |
| 5.16.15 | 8         | 0.22%   |
| 5.16.11 | 8         | 0.22%   |
| 5.13.8  | 8         | 0.22%   |
| 5.12.13 | 8         | 0.22%   |
| 6.0.12  | 7         | 0.19%   |
| 5.7.0   | 7         | 0.19%   |
| 5.3.18  | 7         | 0.19%   |
| 5.19.9  | 7         | 0.19%   |
| 5.17.0  | 7         | 0.19%   |
| 5.16.18 | 7         | 0.19%   |
| 5.15.15 | 7         | 0.19%   |
| 5.14.14 | 7         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 760       | 21.25%  |
| 5.15    | 358       | 10.01%  |
| 5.13    | 281       | 7.86%   |
| 5.8     | 277       | 7.74%   |
| 5.11    | 264       | 7.38%   |
| 5.3     | 227       | 6.35%   |
| 4.15    | 201       | 5.62%   |
| 5.10    | 182       | 5.09%   |
| 5.0     | 144       | 4.03%   |
| 5.16    | 141       | 3.94%   |
| 4.18    | 115       | 3.21%   |
| 5.19    | 76        | 2.12%   |
| 6.0     | 65        | 1.82%   |
| 5.17    | 56        | 1.57%   |
| 5.14    | 49        | 1.37%   |
| 5.9     | 46        | 1.29%   |
| 4.19    | 46        | 1.29%   |
| 6.1     | 45        | 1.26%   |
| 5.12    | 42        | 1.17%   |
| 5.6     | 36        | 1.01%   |
| 4.9     | 33        | 0.92%   |
| 5.18    | 32        | 0.89%   |
| 5.7     | 30        | 0.84%   |
| 5.5     | 19        | 0.53%   |
| 5.2     | 11        | 0.31%   |
| 4.4     | 11        | 0.31%   |
| 5.1     | 8         | 0.22%   |
| 4.20    | 3         | 0.08%   |
| 4.16    | 3         | 0.08%   |
| 4.14    | 3         | 0.08%   |
| 3.10    | 3         | 0.08%   |
| 4.8     | 2         | 0.06%   |
| 4.12    | 2         | 0.06%   |
| 4.1     | 2         | 0.06%   |
| 4.6     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3146      | 96.59%  |
| i686    | 110       | 3.38%   |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1545      | 45.45%  |
| KDE5             | 513       | 15.09%  |
| Unknown          | 408       | 12%     |
| X-Cinnamon       | 252       | 7.41%   |
| XFCE             | 247       | 7.27%   |
| MATE             | 90        | 2.65%   |
| KDE              | 84        | 2.47%   |
| Pantheon         | 37        | 1.09%   |
| Cinnamon         | 36        | 1.06%   |
| LXQt             | 33        | 0.97%   |
| Unity            | 28        | 0.82%   |
| LXDE             | 24        | 0.71%   |
| Budgie           | 19        | 0.56%   |
| i3               | 17        | 0.5%    |
| KDE4             | 14        | 0.41%   |
| GNOME Flashback  | 14        | 0.41%   |
| qtile            | 5         | 0.15%   |
| GNOME Classic    | 5         | 0.15%   |
| awesome          | 5         | 0.15%   |
| sway             | 4         | 0.12%   |
| openbox          | 3         | 0.09%   |
| Deepin           | 3         | 0.09%   |
| xmonad           | 2         | 0.06%   |
| trinity          | 2         | 0.06%   |
| i3-with-shmlog   | 2         | 0.06%   |
| DWM              | 2         | 0.06%   |
| bspwm            | 2         | 0.06%   |
| lightdm-xsession | 1         | 0.03%   |
| GNUstep          | 1         | 0.03%   |
| Cutefish         | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2647      | 79.23%  |
| Wayland | 435       | 13.02%  |
| Unknown | 222       | 6.64%   |
| Tty     | 37        | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1893      | 55.86%  |
| SDDM    | 427       | 12.6%   |
| GDM     | 394       | 11.63%  |
| GDM3    | 280       | 8.26%   |
| LightDM | 265       | 7.82%   |
| TDM     | 100       | 2.95%   |
| KDM     | 15        | 0.44%   |
| XDM     | 5         | 0.15%   |
| Ly      | 4         | 0.12%   |
| LXDM    | 3         | 0.09%   |
| NODM    | 1         | 0.03%   |
| GREETD  | 1         | 0.03%   |
| CDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| en_GB          | 2365      | 70.94%  |
| Unknown        | 404       | 12.12%  |
| en_US          | 398       | 11.94%  |
| C              | 41        | 1.23%   |
| pl_PL          | 36        | 1.08%   |
| fr_FR          | 7         | 0.21%   |
| de_DE          | 7         | 0.21%   |
| ru_RU          | 6         | 0.18%   |
| POSIX          | 6         | 0.18%   |
| it_IT          | 6         | 0.18%   |
| en_CA          | 6         | 0.18%   |
| es_ES          | 5         | 0.15%   |
| en_IN          | 5         | 0.15%   |
| en_IE          | 5         | 0.15%   |
| en_AU          | 5         | 0.15%   |
| cs_CZ          | 5         | 0.15%   |
| zh_CN          | 3         | 0.09%   |
| ro_RO          | 3         | 0.09%   |
| hu_HU          | 3         | 0.09%   |
| sk_SK          | 2         | 0.06%   |
| pt_PT          | 2         | 0.06%   |
| pt_BR          | 2         | 0.06%   |
| uk_UA          | 1         | 0.03%   |
| tr_TR          | 1         | 0.03%   |
| nl_BE          | 1         | 0.03%   |
| en_IL          | 1         | 0.03%   |
| en_HK          | 1         | 0.03%   |
| en_GG          | 1         | 0.03%   |
| en_GB.utf-8    | 1         | 0.03%   |
| en_GB.iso88591 | 1         | 0.03%   |
| en_AG          | 1         | 0.03%   |
| da_DK          | 1         | 0.03%   |
| C.UTF8         | 1         | 0.03%   |
| bg_BG          | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1681      | 50.57%  |
| BIOS | 1643      | 49.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2609      | 78.54%  |
| Btrfs   | 277       | 8.34%   |
| Overlay | 236       | 7.1%    |
| Unknown | 112       | 3.37%   |
| Xfs     | 40        | 1.2%    |
| Zfs     | 25        | 0.75%   |
| Ext2    | 9         | 0.27%   |
| Tmpfs   | 5         | 0.15%   |
| F2fs    | 5         | 0.15%   |
| Ext3    | 3         | 0.09%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2014      | 60.46%  |
| GPT     | 1026      | 30.8%   |
| MBR     | 291       | 8.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2956      | 89.47%  |
| Yes       | 348       | 10.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2485      | 75.26%  |
| Yes       | 817       | 24.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 650       | 19.97%  |
| Lenovo              | 621       | 19.08%  |
| Hewlett-Packard     | 544       | 16.71%  |
| Acer                | 243       | 7.47%   |
| ASUSTek Computer    | 227       | 6.97%   |
| Toshiba             | 153       | 4.7%    |
| Apple               | 98        | 3.01%   |
| Samsung Electronics | 71        | 2.18%   |
| Valve               | 62        | 1.9%    |
| Sony                | 56        | 1.72%   |
| MSI                 | 51        | 1.57%   |
| PC Specialist       | 41        | 1.26%   |
| HUAWEI              | 35        | 1.08%   |
| Notebook            | 28        | 0.86%   |
| Google              | 28        | 0.86%   |
| Unknown             | 21        | 0.65%   |
| Fujitsu             | 19        | 0.58%   |
| Star Labs           | 18        | 0.55%   |
| Razer               | 18        | 0.55%   |
| Packard Bell        | 17        | 0.52%   |
| Alienware           | 15        | 0.46%   |
| Dixonsxp            | 14        | 0.43%   |
| Fujitsu Siemens     | 12        | 0.37%   |
| Entroware           | 12        | 0.37%   |
| Clevo               | 10        | 0.31%   |
| GEO                 | 9         | 0.28%   |
| TUXEDO              | 8         | 0.25%   |
| Linx                | 8         | 0.25%   |
| Jumper              | 8         | 0.25%   |
| Gigabyte Technology | 8         | 0.25%   |
| Advent              | 8         | 0.25%   |
| Panasonic           | 7         | 0.22%   |
| Intel               | 7         | 0.22%   |
| Medion              | 6         | 0.18%   |
| LG Electronics      | 6         | 0.18%   |
| eMachines           | 6         | 0.18%   |
| Timi                | 5         | 0.15%   |
| OEGStone            | 5         | 0.15%   |
| Novatech            | 5         | 0.15%   |
| Teclast             | 4         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Valve Jupiter                | 62        | 1.9%    |
| Unknown                      | 42        | 1.29%   |
| HP Pavilion g6               | 22        | 0.68%   |
| HP Pavilion 15               | 17        | 0.52%   |
| HP Pavilion Notebook         | 15        | 0.46%   |
| HP Notebook                  | 15        | 0.46%   |
| Dell XPS 15 7590             | 15        | 0.46%   |
| Dell Inspiron 1545           | 15        | 0.46%   |
| Dell XPS 15 9560             | 13        | 0.4%    |
| Dell XPS 13 9370             | 13        | 0.4%    |
| Dell XPS 15 9570             | 12        | 0.37%   |
| Dell XPS 13 9360             | 12        | 0.37%   |
| Dell Latitude E6400          | 12        | 0.37%   |
| Lenovo V145-15AST 81MT       | 11        | 0.34%   |
| Dell XPS 13 9380             | 11        | 0.34%   |
| Dell Latitude E6410          | 11        | 0.34%   |
| Toshiba Satellite C660       | 10        | 0.31%   |
| Dell XPS 15 9510             | 10        | 0.31%   |
| Dell XPS 13 7390             | 10        | 0.31%   |
| Dell Latitude E7240          | 10        | 0.31%   |
| Apple MacBookPro9,2          | 10        | 0.31%   |
| Lenovo Z50-75 80EC           | 9         | 0.28%   |
| HP Pavilion dv6              | 9         | 0.28%   |
| HP Laptop 15-bw0xx           | 9         | 0.28%   |
| HP 15                        | 9         | 0.28%   |
| Dell XPS 13 9310             | 9         | 0.28%   |
| Dell Latitude E7450          | 9         | 0.28%   |
| Apple MacBookPro12,1         | 9         | 0.28%   |
| Acer Aspire ES1-531          | 9         | 0.28%   |
| HP Laptop 15-da0xxx          | 8         | 0.25%   |
| Dell XPS 15 9550             | 8         | 0.25%   |
| Dell Latitude E7440          | 8         | 0.25%   |
| Apple MacBookPro5,5          | 8         | 0.25%   |
| Star Labs LabTop             | 7         | 0.22%   |
| HP Stream Laptop 14-ax0XX    | 7         | 0.22%   |
| HP ENVY Notebook             | 7         | 0.22%   |
| Dell XPS 15 9500             | 7         | 0.22%   |
| Dell XPS 13 9305             | 7         | 0.22%   |
| Dell Latitude E7270          | 7         | 0.22%   |
| Dell Latitude E5430 non-vPro | 7         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 351       | 10.78%  |
| Dell Latitude         | 221       | 6.79%   |
| Acer Aspire           | 177       | 5.44%   |
| Dell Inspiron         | 172       | 5.28%   |
| Dell XPS              | 151       | 4.64%   |
| Toshiba Satellite     | 134       | 4.12%   |
| HP Pavilion           | 122       | 3.75%   |
| Lenovo IdeaPad        | 118       | 3.63%   |
| HP EliteBook          | 94        | 2.89%   |
| Valve Jupiter         | 62        | 1.9%    |
| HP ProBook            | 55        | 1.69%   |
| HP Laptop             | 52        | 1.6%    |
| ASUS VivoBook         | 50        | 1.54%   |
| Unknown               | 42        | 1.29%   |
| Dell Precision        | 41        | 1.26%   |
| HP ENVY               | 32        | 0.98%   |
| HP Compaq             | 29        | 0.89%   |
| HP Stream             | 23        | 0.71%   |
| Acer Swift            | 23        | 0.71%   |
| Dell Vostro           | 21        | 0.65%   |
| ASUS Zenbook          | 21        | 0.65%   |
| Razer Blade           | 18        | 0.55%   |
| Lenovo Yoga           | 17        | 0.52%   |
| HP ZBook              | 17        | 0.52%   |
| HP Presario           | 17        | 0.52%   |
| Packard Bell EasyNote | 16        | 0.49%   |
| Lenovo ThinkBook      | 16        | 0.49%   |
| Lenovo Legion         | 16        | 0.49%   |
| Fujitsu LIFEBOOK      | 16        | 0.49%   |
| HP Notebook           | 15        | 0.46%   |
| HP 255                | 15        | 0.46%   |
| ASUS ROG              | 15        | 0.46%   |
| HP OMEN               | 13        | 0.4%    |
| Acer Nitro            | 13        | 0.4%    |
| Dell System           | 12        | 0.37%   |
| Apple MacBookPro9     | 12        | 0.37%   |
| Lenovo V145-15AST     | 11        | 0.34%   |
| ASUS TUF              | 10        | 0.31%   |
| ASUS ASUS             | 10        | 0.31%   |
| Apple MacBookPro5     | 10        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 303       | 9.31%   |
| 2019    | 279       | 8.57%   |
| 2020    | 263       | 8.08%   |
| 2012    | 255       | 7.83%   |
| 2013    | 236       | 7.25%   |
| 2011    | 231       | 7.1%    |
| 2017    | 211       | 6.48%   |
| 2015    | 201       | 6.18%   |
| 2021    | 199       | 6.11%   |
| 2016    | 194       | 5.96%   |
| 2014    | 184       | 5.65%   |
| 2010    | 172       | 5.28%   |
| 2008    | 152       | 4.67%   |
| 2009    | 131       | 4.02%   |
| 2022    | 105       | 3.23%   |
| 2007    | 85        | 2.61%   |
| 2006    | 38        | 1.17%   |
| 2005    | 7         | 0.22%   |
| Unknown | 6         | 0.18%   |
| 2023    | 1         | 0.03%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3255      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2911      | 88.53%  |
| Enabled  | 377       | 11.47%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3208      | 98.56%  |
| Yes  | 47        | 1.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 927       | 28.1%   |
| 3.01-4.0    | 688       | 20.85%  |
| 16.01-24.0  | 597       | 18.1%   |
| 8.01-16.0   | 538       | 16.31%  |
| 1.01-2.0    | 197       | 5.97%   |
| 32.01-64.0  | 190       | 5.76%   |
| 2.01-3.0    | 81        | 2.46%   |
| 0.51-1.0    | 30        | 0.91%   |
| 24.01-32.0  | 25        | 0.76%   |
| 64.01-256.0 | 25        | 0.76%   |
| 0.01-0.5    | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1419      | 39.6%   |
| 2.01-3.0   | 883       | 24.64%  |
| 4.01-8.0   | 454       | 12.67%  |
| 3.01-4.0   | 423       | 11.81%  |
| 0.51-1.0   | 254       | 7.09%   |
| 8.01-16.0  | 99        | 2.76%   |
| 0.01-0.5   | 35        | 0.98%   |
| 16.01-24.0 | 10        | 0.28%   |
| 24.01-32.0 | 4         | 0.11%   |
| 32.01-64.0 | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2426      | 73.01%  |
| 2      | 750       | 22.57%  |
| 3      | 87        | 2.62%   |
| 0      | 32        | 0.96%   |
| 4      | 19        | 0.57%   |
| 7      | 3         | 0.09%   |
| 5      | 3         | 0.09%   |
| 9      | 1         | 0.03%   |
| 8      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2027      | 61.89%  |
| Yes       | 1248      | 38.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2543      | 77.98%  |
| No        | 718       | 22.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3207      | 98.46%  |
| No        | 50        | 1.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2509      | 76.38%  |
| No        | 776       | 23.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UK      | 3255      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| London        | 225       | 6.34%   |
| Birmingham    | 66        | 1.86%   |
| Manchester    | 60        | 1.69%   |
| Glasgow       | 60        | 1.69%   |
| Edinburgh     | 51        | 1.44%   |
| Bristol       | 47        | 1.32%   |
| Sheffield     | 41        | 1.15%   |
| Leeds         | 40        | 1.13%   |
| Nottingham    | 39        | 1.1%    |
| Liverpool     | 38        | 1.07%   |
| Islington     | 36        | 1.01%   |
| Norwich       | 33        | 0.93%   |
| Cambridge     | 32        | 0.9%    |
| Reading       | 31        | 0.87%   |
| Coventry      | 27        | 0.76%   |
| Aberdeen      | 25        | 0.7%    |
| Oxford        | 24        | 0.68%   |
| Southampton   | 23        | 0.65%   |
| Milton Keynes | 23        | 0.65%   |
| Leicester     | 23        | 0.65%   |
| Croydon       | 23        | 0.65%   |
| Cardiff       | 21        | 0.59%   |
| Kensington    | 20        | 0.56%   |
| Brighton      | 20        | 0.56%   |
| Bolton        | 20        | 0.56%   |
| Harrow        | 19        | 0.54%   |
| York          | 18        | 0.51%   |
| Wolverhampton | 18        | 0.51%   |
| Gloucester    | 18        | 0.51%   |
| Chesterfield  | 18        | 0.51%   |
| Wigan         | 17        | 0.48%   |
| Plymouth      | 17        | 0.48%   |
| Swindon       | 16        | 0.45%   |
| Derby         | 16        | 0.45%   |
| Bromley       | 16        | 0.45%   |
| Belfast       | 16        | 0.45%   |
| Walsall       | 15        | 0.42%   |
| Peterborough  | 15        | 0.42%   |
| Hackney       | 15        | 0.42%   |
| Camden        | 15        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 611       | 812    | 15.41%  |
| Seagate                     | 421       | 571    | 10.62%  |
| WDC                         | 404       | 512    | 10.19%  |
| Toshiba                     | 363       | 437    | 9.16%   |
| Unknown                     | 341       | 449    | 8.6%    |
| SanDisk                     | 250       | 304    | 6.31%   |
| Crucial                     | 175       | 233    | 4.41%   |
| Hitachi                     | 160       | 186    | 4.04%   |
| SK hynix                    | 153       | 177    | 3.86%   |
| Kingston                    | 147       | 185    | 3.71%   |
| Intel                       | 112       | 134    | 2.83%   |
| HGST                        | 111       | 159    | 2.8%    |
| Micron Technology           | 73        | 88     | 1.84%   |
| Apple                       | 43        | 53     | 1.08%   |
| Phison                      | 39        | 46     | 0.98%   |
| KIOXIA                      | 36        | 42     | 0.91%   |
| A-DATA Technology           | 34        | 39     | 0.86%   |
| China                       | 33        | 44     | 0.83%   |
| LITEON                      | 31        | 36     | 0.78%   |
| PNY                         | 28        | 32     | 0.71%   |
| Fujitsu                     | 27        | 34     | 0.68%   |
| Transcend                   | 24        | 31     | 0.61%   |
| LITEONIT                    | 21        | 26     | 0.53%   |
| Phison Electronics          | 19        | 20     | 0.48%   |
| Unknown                     | 18        | 19     | 0.45%   |
| Silicon Motion              | 17        | 20     | 0.43%   |
| Integral                    | 12        | 13     | 0.3%    |
| OCZ                         | 11        | 12     | 0.28%   |
| O2 Micro                    | 10        | 10     | 0.25%   |
| Micron/Crucial Technology   | 10        | 11     | 0.25%   |
| Lenovo                      | 9         | 9      | 0.23%   |
| Kingston Technology Company | 9         | 9      | 0.23%   |
| Team                        | 8         | 9      | 0.2%    |
| Corsair                     | 8         | 12     | 0.2%    |
| TCSUNBOW                    | 7         | 10     | 0.18%   |
| SPCC                        | 7         | 11     | 0.18%   |
| Star                        | 6         | 7      | 0.15%   |
| Patriot                     | 5         | 10     | 0.13%   |
| KingFast                    | 5         | 5      | 0.13%   |
| JMicron Technology          | 5         | 9      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                  | 83        | 2%      |
| Seagate ST1000LM035-1RK172 1TB          | 55        | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 48        | 1.16%   |
| Toshiba MQ01ABD100 1TB                  | 40        | 0.96%   |
| Samsung NVMe SSD Drive 512GB            | 37        | 0.89%   |
| Unknown MMC Card  64GB                  | 36        | 0.87%   |
| Unknown MMC Card  128GB                 | 34        | 0.82%   |
| Toshiba MQ01ABF050 500GB                | 29        | 0.7%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB  | 29        | 0.7%    |
| HGST HTS721010A9E630 1TB                | 28        | 0.67%   |
| HGST HTS541010A9E680 1TB                | 28        | 0.67%   |
| Toshiba NVMe SSD Drive 256GB            | 25        | 0.6%    |
| Crucial CT500MX500SSD1 500GB            | 24        | 0.58%   |
| Samsung SSD 850 EVO 500GB               | 23        | 0.55%   |
| Unknown MMC Card  16GB                  | 22        | 0.53%   |
| Samsung SSD 860 EVO 500GB               | 22        | 0.53%   |
| Kingston SA400S37240G 240GB SSD         | 22        | 0.53%   |
| Unknown MMC Card  512GB                 | 20        | 0.48%   |
| SanDisk NVMe SSD Drive 512GB            | 20        | 0.48%   |
| Samsung NVMe SSD Drive 1024GB           | 20        | 0.48%   |
| Kingston SA400S37120G 120GB SSD         | 20        | 0.48%   |
| SK hynix NVMe SSD Drive 512GB           | 18        | 0.43%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 18        | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB            | 18        | 0.43%   |
| Crucial CT240BX500SSD1 240GB            | 18        | 0.43%   |
| Unknown                                 | 18        | 0.43%   |
| Toshiba NVMe SSD Drive 512GB            | 17        | 0.41%   |
| Toshiba MQ04ABF100 1TB                  | 17        | 0.41%   |
| Seagate ST9500325AS 500GB               | 17        | 0.41%   |
| Seagate ST500LT012-1DG142 500GB         | 17        | 0.41%   |
| Samsung SSD 850 EVO 250GB               | 17        | 0.41%   |
| Samsung NVMe SSD Drive 1TB              | 17        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB             | 17        | 0.41%   |
| Unknown SD/MMC/MS PRO 2GB               | 16        | 0.39%   |
| SanDisk NVMe SSD Drive 256GB            | 16        | 0.39%   |
| Crucial CT250MX500SSD1 250GB            | 16        | 0.39%   |
| Phison PS5013 E13 NVMe Controller 256GB | 15        | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 14        | 0.34%   |
| Seagate Expansion 240GB                 | 14        | 0.34%   |
| Samsung NVMe SSD Drive 500GB            | 14        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 408       | 551    | 32.2%   |
| WDC                 | 247       | 309    | 19.49%  |
| Toshiba             | 233       | 276    | 18.39%  |
| Hitachi             | 160       | 186    | 12.63%  |
| HGST                | 111       | 159    | 8.76%   |
| Samsung Electronics | 41        | 46     | 3.24%   |
| Fujitsu             | 27        | 34     | 2.13%   |
| Unknown             | 16        | 18     | 1.26%   |
| Apple               | 6         | 6      | 0.47%   |
| SABRENT             | 4         | 4      | 0.32%   |
| ASMT                | 4         | 27     | 0.32%   |
| IBM/Hitachi         | 2         | 2      | 0.16%   |
| USB3.0              | 1         | 1      | 0.08%   |
| PHD 3.0             | 1         | 1      | 0.08%   |
| Maxone              | 1         | 1      | 0.08%   |
| LaCie               | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 3      | 0.08%   |
| Intenso             | 1         | 1      | 0.08%   |
| HGST HTS            | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 286       | 389    | 22.2%   |
| Crucial             | 161       | 218    | 12.5%   |
| SanDisk             | 156       | 183    | 12.11%  |
| Kingston            | 116       | 141    | 9.01%   |
| WDC                 | 70        | 101    | 5.43%   |
| Intel               | 45        | 49     | 3.49%   |
| Micron Technology   | 36        | 44     | 2.8%    |
| SK hynix            | 33        | 42     | 2.56%   |
| Toshiba             | 32        | 40     | 2.48%   |
| China               | 31        | 42     | 2.41%   |
| LITEON              | 30        | 35     | 2.33%   |
| Apple               | 28        | 37     | 2.17%   |
| PNY                 | 27        | 30     | 2.1%    |
| A-DATA Technology   | 25        | 29     | 1.94%   |
| Transcend           | 24        | 31     | 1.86%   |
| LITEONIT            | 21        | 26     | 1.63%   |
| Integral            | 12        | 13     | 0.93%   |
| OCZ                 | 11        | 12     | 0.85%   |
| Seagate             | 8         | 8      | 0.62%   |
| Unknown             | 7         | 7      | 0.54%   |
| Team                | 7         | 8      | 0.54%   |
| TCSUNBOW            | 6         | 9      | 0.47%   |
| Star                | 6         | 7      | 0.47%   |
| SPCC                | 6         | 10     | 0.47%   |
| Corsair             | 6         | 10     | 0.47%   |
| Patriot             | 5         | 10     | 0.39%   |
| Drevo               | 5         | 7      | 0.39%   |
| BHT                 | 5         | 8      | 0.39%   |
| Netac               | 4         | 5      | 0.31%   |
| Lexar               | 4         | 5      | 0.31%   |
| ZTC                 | 3         | 6      | 0.23%   |
| Zheino              | 3         | 4      | 0.23%   |
| Vaseky              | 3         | 4      | 0.23%   |
| TO Exter            | 3         | 3      | 0.23%   |
| NGFF                | 3         | 3      | 0.23%   |
| Maxtor              | 3         | 3      | 0.23%   |
| KingDian            | 3         | 6      | 0.23%   |
| BIWIN               | 3         | 3      | 0.23%   |
| Plextor             | 2         | 3      | 0.16%   |
| ORTIAL              | 2         | 2      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1225      | 1628   | 32.53%  |
| SSD     | 1182      | 1649   | 31.39%  |
| NVMe    | 980       | 1268   | 26.02%  |
| MMC     | 338       | 445    | 8.98%   |
| Unknown | 41        | 51     | 1.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2216      | 3149   | 60.68%  |
| NVMe | 978       | 1263   | 26.78%  |
| MMC  | 338       | 445    | 9.26%   |
| SAS  | 120       | 184    | 3.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1681      | 2289   | 69.55%  |
| 0.51-1.0   | 628       | 844    | 25.98%  |
| 1.01-2.0   | 82        | 111    | 3.39%   |
| 4.01-10.0  | 16        | 23     | 0.66%   |
| 3.01-4.0   | 9         | 9      | 0.37%   |
| 10.01-20.0 | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1056      | 30.99%  |
| 251-500        | 776       | 22.77%  |
| 501-1000       | 480       | 14.08%  |
| 1-20           | 266       | 7.81%   |
| 51-100         | 255       | 7.48%   |
| 21-50          | 215       | 6.31%   |
| 1001-2000      | 169       | 4.96%   |
| Unknown        | 90        | 2.64%   |
| More than 3000 | 54        | 1.58%   |
| 2001-3000      | 47        | 1.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1563      | 44.23%  |
| 21-50          | 632       | 17.88%  |
| 101-250        | 450       | 12.73%  |
| 51-100         | 397       | 11.23%  |
| 251-500        | 222       | 6.28%   |
| 501-1000       | 105       | 2.97%   |
| Unknown        | 90        | 2.55%   |
| 1001-2000      | 51        | 1.44%   |
| 2001-3000      | 13        | 0.37%   |
| More than 3000 | 11        | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                 | 6         | 6      | 3.75%   |
| HGST HTS725050A7E630 500GB                     | 6         | 9      | 3.75%   |
| Hitachi HTS547575A9E384 752GB                  | 4         | 6      | 2.5%    |
| Seagate ST9500325AS 500GB                      | 3         | 5      | 1.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 3         | 4      | 1.88%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 1.88%   |
| WDC WD2500BEVT-80A23T0 250GB                   | 2         | 4      | 1.25%   |
| Toshiba MK3256GSY 320GB                        | 2         | 3      | 1.25%   |
| Toshiba MK1656GSY 160GB                        | 2         | 2      | 1.25%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 1.25%   |
| Seagate ST500LM021-1KJ152 500GB                | 2         | 2      | 1.25%   |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 3      | 1.25%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 1.25%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 2      | 1.25%   |
| LITEON CS1-SP32-11 M.2 2242 32GB SSD           | 2         | 2      | 1.25%   |
| Hitachi HTS547564A9E384 640GB                  | 2         | 2      | 1.25%   |
| Hitachi HTS545032B9A302 320GB                  | 2         | 3      | 1.25%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 1.25%   |
| Hitachi HTS545025B9A300 250GB                  | 2         | 2      | 1.25%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 1.25%   |
| Hitachi HTS542512K9SA00 120GB                  | 2         | 2      | 1.25%   |
| HGST HTS721010A9E630 1TB                       | 2         | 2      | 1.25%   |
| Crucial CT525MX300SSD4 528GB                   | 2         | 2      | 1.25%   |
| Zheino CHN mSATA02M 256 256GB SSD              | 1         | 2      | 0.63%   |
| WDC WD5000BPVT-55HXZT3 500GB                   | 1         | 1      | 0.63%   |
| WDC WD5000BEVT-75A0RT0 500GB                   | 1         | 1      | 0.63%   |
| WDC WD5000BEVT-60A0RT0 500GB                   | 1         | 2      | 0.63%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 0.63%   |
| WDC WD3200LPCX-24C6HT0 320GB                   | 1         | 1      | 0.63%   |
| WDC WD3200BEKT-75PVMT0 320GB                   | 1         | 1      | 0.63%   |
| WDC WD2500BEVT-75A23T0 250GB                   | 1         | 1      | 0.63%   |
| WDC WD2500BEVT-60A23T0 250GB                   | 1         | 1      | 0.63%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB           | 1         | 1      | 0.63%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD           | 1         | 1      | 0.63%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 0.63%   |
| Toshiba MK6475GSX 640GB                        | 1         | 1      | 0.63%   |
| Toshiba MK5065GSXN 500GB                       | 1         | 1      | 0.63%   |
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 0.63%   |
| Toshiba MK3276GSX -63 320GB                    | 1         | 1      | 0.63%   |
| Toshiba MK2565GSXN 250GB                       | 1         | 1      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 45     | 25.63%  |
| Hitachi             | 28        | 31     | 17.5%   |
| Toshiba             | 18        | 19     | 11.25%  |
| HGST                | 15        | 18     | 9.38%   |
| WDC                 | 11        | 14     | 6.88%   |
| Crucial             | 10        | 10     | 6.25%   |
| Samsung Electronics | 8         | 8      | 5%      |
| Intel               | 5         | 5      | 3.13%   |
| SanDisk             | 4         | 4      | 2.5%    |
| Micron Technology   | 3         | 3      | 1.88%   |
| LITEON              | 3         | 3      | 1.88%   |
| Kingston            | 3         | 3      | 1.88%   |
| Fujitsu             | 3         | 3      | 1.88%   |
| A-DATA Technology   | 2         | 2      | 1.25%   |
| Zheino              | 1         | 2      | 0.63%   |
| Team                | 1         | 1      | 0.63%   |
| SK hynix            | 1         | 1      | 0.63%   |
| Drevo               | 1         | 1      | 0.63%   |
| Corsair             | 1         | 1      | 0.63%   |
| 2-Power             | 1         | 1      | 0.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 45     | 35.04%  |
| Hitachi             | 28        | 31     | 23.93%  |
| Toshiba             | 17        | 18     | 14.53%  |
| HGST                | 15        | 18     | 12.82%  |
| WDC                 | 10        | 13     | 8.55%   |
| Samsung Electronics | 3         | 3      | 2.56%   |
| Fujitsu             | 3         | 3      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 117       | 131    | 73.13%  |
| SSD  | 40        | 41     | 25%     |
| NVMe | 3         | 3      | 1.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 2      | 50%     |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 3      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2187      | 3446   | 64.17%  |
| Works    | 1061      | 1417   | 31.13%  |
| Malfunc  | 158       | 175    | 4.64%   |
| Failed   | 2         | 3      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2249      | 60.67%  |
| AMD                              | 385       | 10.39%  |
| Samsung Electronics              | 335       | 9.04%   |
| SanDisk                          | 168       | 4.53%   |
| SK hynix                         | 116       | 3.13%   |
| Toshiba America Info Systems     | 105       | 2.83%   |
| Phison Electronics               | 66        | 1.78%   |
| Kingston Technology Company      | 40        | 1.08%   |
| Micron Technology                | 39        | 1.05%   |
| Nvidia                           | 35        | 0.94%   |
| KIOXIA                           | 35        | 0.94%   |
| Micron/Crucial Technology        | 23        | 0.62%   |
| Silicon Motion                   | 19        | 0.51%   |
| ADATA Technology                 | 13        | 0.35%   |
| Silicon Integrated Systems [SiS] | 12        | 0.32%   |
| O2 Micro                         | 10        | 0.27%   |
| Lenovo                           | 8         | 0.22%   |
| Apple                            | 8         | 0.22%   |
| Solid State Storage Technology   | 7         | 0.19%   |
| Marvell Technology Group         | 5         | 0.13%   |
| VIA Technologies                 | 4         | 0.11%   |
| Union Memory (Shenzhen)          | 4         | 0.11%   |
| Shenzhen Longsys Electronics     | 3         | 0.08%   |
| Lite-On Technology               | 3         | 0.08%   |
| JMicron Technology               | 3         | 0.08%   |
| Yangtze Memory Technologies      | 2         | 0.05%   |
| ASMedia Technology               | 2         | 0.05%   |
| Silicon Image                    | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| Realtek Semiconductor            | 1         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.03%   |
| INNOGRIT                         | 1         | 0.03%   |
| Enmotus                          | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 320       | 8.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 254       | 6.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 215       | 5.4%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 211       | 5.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 172       | 4.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 169       | 4.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 153       | 3.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 109       | 2.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 104       | 2.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 96        | 2.41%   |
| Intel Volume Management Device NVMe RAID Controller                              | 87        | 2.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 79        | 1.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 69        | 1.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 68        | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 66        | 1.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 65        | 1.63%   |
| Samsung NVMe SSD Controller 980                                                  | 55        | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 55        | 1.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 46        | 1.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 44        | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 43        | 1.08%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 42        | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 42        | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                            | 41        | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 41        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 40        | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 39        | 0.98%   |
| Micron Non-Volatile memory controller                                            | 39        | 0.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 38        | 0.95%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 37        | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 36        | 0.9%    |
| Phison PS5013 E13 NVMe Controller                                                | 34        | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 34        | 0.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 33        | 0.83%   |
| SK hynix Non-Volatile memory controller                                          | 31        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 31        | 0.78%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 30        | 0.75%   |
| SanDisk Non-Volatile memory controller                                           | 28        | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 28        | 0.7%    |
| Intel SSD 660P Series                                                            | 26        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2239      | 58.67%  |
| NVMe | 992       | 26%     |
| RAID | 305       | 7.99%   |
| IDE  | 280       | 7.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2703      | 83.04%  |
| AMD    | 551       | 16.93%  |
| ARM    | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 62        | 1.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 51        | 1.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 46        | 1.41%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 45        | 1.38%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 44        | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 40        | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 39        | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 39        | 1.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 38        | 1.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 36        | 1.11%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 36        | 1.11%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 36        | 1.11%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 34        | 1.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 34        | 1.04%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 34        | 1.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 33        | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 33        | 1.01%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 32        | 0.98%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 31        | 0.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 29        | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 26        | 0.8%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 25        | 0.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 0.77%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 25        | 0.77%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 25        | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 24        | 0.74%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 24        | 0.74%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 22        | 0.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 19        | 0.58%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 19        | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 19        | 0.58%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 19        | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 18        | 0.55%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 18        | 0.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.55%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 18        | 0.55%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 18        | 0.55%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 17        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 794       | 24.38%  |
| Intel Core i7           | 734       | 22.54%  |
| Other                   | 253       | 7.77%   |
| Intel Celeron           | 227       | 6.97%   |
| Intel Core i3           | 222       | 6.82%   |
| Intel Core 2 Duo        | 180       | 5.53%   |
| Intel Pentium           | 96        | 2.95%   |
| AMD Ryzen 7             | 83        | 2.55%   |
| AMD Ryzen 5             | 81        | 2.49%   |
| Intel Atom              | 68        | 2.09%   |
| AMD A6                  | 53        | 1.63%   |
| AMD A8                  | 37        | 1.14%   |
| Intel Pentium Dual-Core | 35        | 1.07%   |
| Intel Core 2            | 30        | 0.92%   |
| AMD Ryzen 3             | 27        | 0.83%   |
| Intel Pentium Dual      | 26        | 0.8%    |
| Intel Genuine           | 23        | 0.71%   |
| AMD A4                  | 21        | 0.64%   |
| Intel Celeron Dual-Core | 19        | 0.58%   |
| AMD E1                  | 18        | 0.55%   |
| Intel Core i9           | 17        | 0.52%   |
| AMD A10                 | 16        | 0.49%   |
| AMD Ryzen 9             | 15        | 0.46%   |
| AMD E                   | 15        | 0.46%   |
| Intel Celeron M         | 14        | 0.43%   |
| AMD E2                  | 13        | 0.4%    |
| Intel Pentium Silver    | 12        | 0.37%   |
| Intel Pentium M         | 9         | 0.28%   |
| AMD Turion 64 X2 Mobile | 8         | 0.25%   |
| AMD Athlon              | 8         | 0.25%   |
| AMD FX                  | 7         | 0.21%   |
| AMD Athlon X2           | 7         | 0.21%   |
| AMD Athlon II           | 7         | 0.21%   |
| AMD Turion 64 Mobile    | 6         | 0.18%   |
| AMD Ryzen 7 PRO         | 6         | 0.18%   |
| Intel Core M            | 5         | 0.15%   |
| AMD Phenom II           | 5         | 0.15%   |
| Intel Core m3           | 4         | 0.12%   |
| Intel Core 2 Extreme    | 4         | 0.12%   |
| AMD Ryzen 5 PRO         | 4         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1816      | 55.77%  |
| 4      | 989       | 30.37%  |
| 6      | 179       | 5.5%    |
| 8      | 141       | 4.33%   |
| 1      | 99        | 3.04%   |
| 14     | 20        | 0.61%   |
| 12     | 6         | 0.18%   |
| 10     | 4         | 0.12%   |
| 3      | 2         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3254      | 99.97%  |
| 2      | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2255      | 69.26%  |
| 1      | 1001      | 30.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3154      | 96.54%  |
| Unknown        | 58        | 1.78%   |
| 32-bit         | 55        | 1.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 749       | 22.27%  |
| 0x306a9    | 215       | 6.39%   |
| 0x206a7    | 197       | 5.86%   |
| 0x1067a    | 143       | 4.25%   |
| 0x806ea    | 109       | 3.24%   |
| 0x40651    | 108       | 3.21%   |
| 0x806ec    | 107       | 3.18%   |
| 0x406e3    | 99        | 2.94%   |
| 0x20655    | 93        | 2.77%   |
| 0x806e9    | 92        | 2.74%   |
| 0x306d4    | 92        | 2.74%   |
| 0x906ea    | 82        | 2.44%   |
| 0x806c1    | 77        | 2.29%   |
| 0x6fd      | 64        | 1.9%    |
| 0x306c3    | 60        | 1.78%   |
| 0x406c4    | 59        | 1.75%   |
| 0x30678    | 58        | 1.72%   |
| 0xa0652    | 46        | 1.37%   |
| 0x906e9    | 45        | 1.34%   |
| 0x506e3    | 39        | 1.16%   |
| 0x506c9    | 38        | 1.13%   |
| 0x06006705 | 37        | 1.1%    |
| 0x08108102 | 33        | 0.98%   |
| 0x706e5    | 32        | 0.95%   |
| 0x406c3    | 30        | 0.89%   |
| 0x08108109 | 30        | 0.89%   |
| 0x07030105 | 30        | 0.89%   |
| 0x20652    | 29        | 0.86%   |
| 0x706a1    | 28        | 0.83%   |
| 0x10676    | 28        | 0.83%   |
| 0x806d1    | 26        | 0.77%   |
| 0x6f6      | 24        | 0.71%   |
| 0x0a50000c | 23        | 0.68%   |
| 0x06006704 | 22        | 0.65%   |
| 0x906a3    | 21        | 0.62%   |
| 0x806eb    | 21        | 0.62%   |
| 0x05000119 | 20        | 0.59%   |
| 0x08600106 | 17        | 0.51%   |
| 0x08600104 | 17        | 0.51%   |
| 0x906ed    | 16        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 598       | 18.35%  |
| IvyBridge        | 254       | 7.8%    |
| SandyBridge      | 234       | 7.18%   |
| Haswell          | 226       | 6.94%   |
| Penryn           | 193       | 5.92%   |
| Silvermont       | 176       | 5.4%    |
| Skylake          | 163       | 5%      |
| Westmere         | 148       | 4.54%   |
| Core             | 139       | 4.27%   |
| Broadwell        | 120       | 3.68%   |
| Unknown          | 109       | 3.35%   |
| TigerLake        | 103       | 3.16%   |
| Zen+             | 78        | 2.39%   |
| Excavator        | 76        | 2.33%   |
| Icelake          | 67        | 2.06%   |
| CometLake        | 64        | 1.96%   |
| Zen 2            | 60        | 1.84%   |
| Goldmont plus    | 48        | 1.47%   |
| Puma             | 47        | 1.44%   |
| Goldmont         | 45        | 1.38%   |
| P6               | 39        | 1.2%    |
| Zen 3            | 33        | 1.01%   |
| Bobcat           | 33        | 1.01%   |
| Zen              | 31        | 0.95%   |
| Bonnell          | 27        | 0.83%   |
| Alderlake Hybrid | 24        | 0.74%   |
| K10              | 21        | 0.64%   |
| Piledriver       | 20        | 0.61%   |
| K8 Hammer        | 19        | 0.58%   |
| Jaguar           | 17        | 0.52%   |
| Steamroller      | 13        | 0.4%    |
| K8 & K10 hybrid  | 12        | 0.37%   |
| Nehalem          | 11        | 0.34%   |
| K10 Llano        | 6         | 0.18%   |
| Tremont          | 2         | 0.06%   |
| NetBurst         | 2         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2472      | 63.3%   |
| Nvidia                           | 757       | 19.39%  |
| AMD                              | 659       | 16.88%  |
| Silicon Integrated Systems [SiS] | 12        | 0.31%   |
| VIA Technologies                 | 4         | 0.1%    |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 240       | 5.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 223       | 5.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 155       | 3.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 131       | 3.24%   |
| Intel UHD Graphics 620                                                                   | 123       | 3.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 123       | 3.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 117       | 2.9%    |
| Intel HD Graphics 620                                                                    | 103       | 2.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 100       | 2.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 100       | 2.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 93        | 2.3%    |
| Intel HD Graphics 5500                                                                   | 91        | 2.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 88        | 2.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 82        | 2.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 81        | 2.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 76        | 1.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 71        | 1.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 64        | 1.59%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 62        | 1.54%   |
| AMD Renoir                                                                               | 56        | 1.39%   |
| Intel HD Graphics 630                                                                    | 55        | 1.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 52        | 1.29%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 52        | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 49        | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 49        | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 40        | 0.99%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 39        | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 39        | 0.97%   |
| Intel HD Graphics 500                                                                    | 38        | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 37        | 0.92%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 36        | 0.89%   |
| Intel HD Graphics 530                                                                    | 35        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 30        | 0.74%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 30        | 0.74%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 29        | 0.72%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 29        | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 27        | 0.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 24        | 0.59%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 23        | 0.57%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 22        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1865      | 57.14%  |
| Intel + Nvidia           | 534       | 16.36%  |
| 1 x AMD                  | 522       | 15.99%  |
| 1 x Nvidia               | 177       | 5.42%   |
| Intel + AMD              | 67        | 2.05%   |
| AMD + Nvidia             | 42        | 1.29%   |
| 2 x AMD                  | 26        | 0.8%    |
| 1 x SiS                  | 12        | 0.37%   |
| 2 x Intel                | 7         | 0.21%   |
| Other                    | 4         | 0.12%   |
| 1 x VIA                  | 4         | 0.12%   |
| 2 x Nvidia               | 2         | 0.06%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2828      | 85.91%  |
| Proprietary | 389       | 11.82%  |
| Unknown     | 75        | 2.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2247      | 67.4%   |
| 0.01-0.5   | 400       | 12%     |
| 1.01-2.0   | 287       | 8.61%   |
| 3.01-4.0   | 162       | 4.86%   |
| 0.51-1.0   | 138       | 4.14%   |
| 5.01-6.0   | 56        | 1.68%   |
| 7.01-8.0   | 31        | 0.93%   |
| 2.01-3.0   | 9         | 0.27%   |
| 8.01-16.0  | 4         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 708       | 19.94%  |
| LG Display              | 552       | 15.55%  |
| Chimei Innolux          | 418       | 11.77%  |
| Samsung Electronics     | 384       | 10.82%  |
| BOE                     | 374       | 10.54%  |
| Sharp                   | 174       | 4.9%    |
| Apple                   | 99        | 2.79%   |
| Dell                    | 83        | 2.34%   |
| Chi Mei Optoelectronics | 71        | 2%      |
| Lenovo                  | 70        | 1.97%   |
| PANDA                   | 53        | 1.49%   |
| Goldstar                | 50        | 1.41%   |
| LG Philips              | 45        | 1.27%   |
| Hewlett-Packard         | 36        | 1.01%   |
| Acer                    | 32        | 0.9%    |
| InfoVision              | 29        | 0.82%   |
| BenQ                    | 26        | 0.73%   |
| Analogix                | 26        | 0.73%   |
| AOC                     | 24        | 0.68%   |
| Iiyama                  | 23        | 0.65%   |
| ANX                     | 21        | 0.59%   |
| Philips                 | 18        | 0.51%   |
| Valve                   | 16        | 0.45%   |
| Ancor Communications    | 16        | 0.45%   |
| Panasonic               | 15        | 0.42%   |
| Sony                    | 14        | 0.39%   |
| Toshiba                 | 13        | 0.37%   |
| ViewSonic               | 12        | 0.34%   |
| LGD                     | 12        | 0.34%   |
| InnoLux Display         | 11        | 0.31%   |
| CSO                     | 11        | 0.31%   |
| HannStar                | 10        | 0.28%   |
| CPT                     | 7         | 0.2%    |
| Vestel Elektronik       | 6         | 0.17%   |
| Quanta Display          | 6         | 0.17%   |
| ASUSTek Computer        | 6         | 0.17%   |
| Seiko/Epson             | 5         | 0.14%   |
| Unknown                 | 4         | 0.11%   |
| TMX                     | 3         | 0.08%   |
| NEC Computers           | 3         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 40        | 1.12%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 31        | 0.86%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 30        | 0.84%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 29        | 0.81%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 27        | 0.75%   |
| Analogix ANX7530 U ANX7539 800x1280                                   | 26        | 0.73%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 25        | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 22        | 0.61%   |
| ANX ANX7530 U ANX7539 800x1280                                        | 21        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 19        | 0.53%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 17        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 17        | 0.47%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 16        | 0.45%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 15        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 14        | 0.39%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch         | 14        | 0.39%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 13        | 0.36%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 13        | 0.36%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 12        | 0.33%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 12        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 12        | 0.33%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 12        | 0.33%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 12        | 0.33%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 12        | 0.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 12        | 0.33%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 11        | 0.31%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 11        | 0.31%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 11        | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 11        | 0.31%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 11        | 0.31%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 11        | 0.31%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 10        | 0.28%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 10        | 0.28%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 10        | 0.28%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 10        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 10        | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 10        | 0.28%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 9         | 0.25%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 9         | 0.25%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 9         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1280      | 37.64%  |
| 1366x768 (WXGA)    | 1077      | 31.67%  |
| 1280x800 (WXGA)    | 187       | 5.5%    |
| 3840x2160 (4K)     | 147       | 4.32%   |
| 1600x900 (HD+)     | 137       | 4.03%   |
| 2560x1440 (QHD)    | 94        | 2.76%   |
| 1440x900 (WXGA+)   | 75        | 2.21%   |
| 800x1280           | 62        | 1.82%   |
| 1920x1200 (WUXGA)  | 55        | 1.62%   |
| 2560x1600          | 34        | 1%      |
| 1680x1050 (WSXGA+) | 29        | 0.85%   |
| 3840x2400          | 26        | 0.76%   |
| 3440x1440          | 21        | 0.62%   |
| 3200x1800 (QHD+)   | 21        | 0.62%   |
| 2880x1800          | 17        | 0.5%    |
| 1280x1024 (SXGA)   | 17        | 0.5%    |
| 1024x600           | 17        | 0.5%    |
| 2160x1440          | 11        | 0.32%   |
| 2560x1080          | 10        | 0.29%   |
| Unknown            | 10        | 0.29%   |
| 1360x768           | 8         | 0.24%   |
| 1024x768 (XGA)     | 6         | 0.18%   |
| 3072x1920          | 5         | 0.15%   |
| 1680x945           | 5         | 0.15%   |
| 2256x1504          | 4         | 0.12%   |
| 1920x540           | 4         | 0.12%   |
| 3456x2160          | 3         | 0.09%   |
| 2560x1700          | 3         | 0.09%   |
| 1280x768           | 3         | 0.09%   |
| 3840x1080          | 2         | 0.06%   |
| 3000x2000          | 2         | 0.06%   |
| 2880x1920          | 2         | 0.06%   |
| 2520x1680          | 2         | 0.06%   |
| 2240x1400          | 2         | 0.06%   |
| 2160x1350          | 2         | 0.06%   |
| 1920x1280          | 2         | 0.06%   |
| 1360x765           | 2         | 0.06%   |
| 8960x2160          | 1         | 0.03%   |
| 800x480            | 1         | 0.03%   |
| 7680x1080          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1478      | 41.69%  |
| 13      | 564       | 15.91%  |
| 14      | 342       | 9.65%   |
| 17      | 227       | 6.4%    |
| 12      | 159       | 4.49%   |
| Unknown | 101       | 2.85%   |
| 11      | 99        | 2.79%   |
| 27      | 91        | 2.57%   |
| 24      | 75        | 2.12%   |
| 21      | 64        | 1.81%   |
| 23      | 59        | 1.66%   |
| 31      | 28        | 0.79%   |
| 34      | 27        | 0.76%   |
| 18      | 27        | 0.76%   |
| 10      | 26        | 0.73%   |
| 16      | 24        | 0.68%   |
| 84      | 17        | 0.48%   |
| 7       | 16        | 0.45%   |
| 19      | 15        | 0.42%   |
| 25      | 14        | 0.39%   |
| 22      | 11        | 0.31%   |
| 72      | 9         | 0.25%   |
| 26      | 8         | 0.23%   |
| 54      | 7         | 0.2%    |
| 40      | 6         | 0.17%   |
| 20      | 6         | 0.17%   |
| 8       | 6         | 0.17%   |
| 48      | 5         | 0.14%   |
| 65      | 4         | 0.11%   |
| 28      | 4         | 0.11%   |
| 50      | 3         | 0.08%   |
| 35      | 3         | 0.08%   |
| 33      | 3         | 0.08%   |
| 32      | 3         | 0.08%   |
| 49      | 2         | 0.06%   |
| 46      | 2         | 0.06%   |
| 142     | 1         | 0.03%   |
| 99      | 1         | 0.03%   |
| 86      | 1         | 0.03%   |
| 75      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2023      | 57.29%  |
| 201-300        | 615       | 17.42%  |
| 351-400        | 290       | 8.21%   |
| 501-600        | 229       | 6.49%   |
| 401-500        | 110       | 3.12%   |
| Unknown        | 101       | 2.86%   |
| 601-700        | 41        | 1.16%   |
| 701-800        | 33        | 0.93%   |
| 1501-2000      | 28        | 0.79%   |
| 1001-1500      | 25        | 0.71%   |
| 1-100          | 16        | 0.45%   |
| 801-900        | 10        | 0.28%   |
| 101-200        | 6         | 0.17%   |
| More than 2000 | 2         | 0.06%   |
| 901-1000       | 2         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2603      | 80.74%  |
| 16/10   | 408       | 12.66%  |
| Unknown | 49        | 1.52%   |
| 0.62    | 48        | 1.49%   |
| 3/2     | 35        | 1.09%   |
| 21/9    | 32        | 0.99%   |
| 0.67    | 16        | 0.5%    |
| 4/3     | 13        | 0.4%    |
| 5/4     | 12        | 0.37%   |
| 6/5     | 3         | 0.09%   |
| 32/9    | 2         | 0.06%   |
| 1.00    | 2         | 0.06%   |
| 3.40    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1475      | 41.65%  |
| 81-90          | 628       | 17.74%  |
| 71-80          | 276       | 7.79%   |
| 121-130        | 187       | 5.28%   |
| 201-250        | 173       | 4.89%   |
| 61-70          | 153       | 4.32%   |
| 51-60          | 101       | 2.85%   |
| Unknown        | 101       | 2.85%   |
| 301-350        | 97        | 2.74%   |
| 351-500        | 67        | 1.89%   |
| More than 1000 | 51        | 1.44%   |
| 131-140        | 39        | 1.1%    |
| 251-300        | 38        | 1.07%   |
| 151-200        | 36        | 1.02%   |
| 141-150        | 27        | 0.76%   |
| 41-50          | 25        | 0.71%   |
| 1-40           | 22        | 0.62%   |
| 111-120        | 22        | 0.62%   |
| 501-1000       | 13        | 0.37%   |
| 91-100         | 10        | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1321      | 37.76%  |
| 101-120       | 1091      | 31.19%  |
| 51-100        | 488       | 13.95%  |
| 161-240       | 310       | 8.86%   |
| More than 240 | 144       | 4.12%   |
| Unknown       | 101       | 2.89%   |
| 1-50          | 43        | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2778      | 83.98%  |
| 2     | 417       | 12.61%  |
| 0     | 72        | 2.18%   |
| 3     | 37        | 1.12%   |
| 4     | 3         | 0.09%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1764      | 34.72%  |
| Realtek Semiconductor             | 1535      | 30.21%  |
| Qualcomm Atheros                  | 727       | 14.31%  |
| Broadcom                          | 390       | 7.68%   |
| Broadcom Limited                  | 92        | 1.81%   |
| Marvell Technology Group          | 85        | 1.67%   |
| Ralink                            | 42        | 0.83%   |
| Ralink Technology                 | 40        | 0.79%   |
| TP-Link                           | 36        | 0.71%   |
| Ericsson Business Mobile Networks | 36        | 0.71%   |
| MediaTek                          | 32        | 0.63%   |
| Dell                              | 30        | 0.59%   |
| Nvidia                            | 25        | 0.49%   |
| DisplayLink                       | 22        | 0.43%   |
| ASIX Electronics                  | 22        | 0.43%   |
| Lenovo                            | 18        | 0.35%   |
| Hewlett-Packard                   | 18        | 0.35%   |
| Samsung Electronics               | 15        | 0.3%    |
| Qualcomm                          | 15        | 0.3%    |
| Silicon Integrated Systems [SiS]  | 11        | 0.22%   |
| Sierra Wireless                   | 11        | 0.22%   |
| JMicron Technology                | 11        | 0.22%   |
| Huawei Technologies               | 11        | 0.22%   |
| NetGear                           | 7         | 0.14%   |
| Edimax Technology                 | 7         | 0.14%   |
| Qualcomm Atheros Communications   | 6         | 0.12%   |
| Micro Star International          | 5         | 0.1%    |
| Belkin Components                 | 5         | 0.1%    |
| Attansic Technology               | 5         | 0.1%    |
| VIA Technologies                  | 4         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.08%   |
| ICS Advent                        | 4         | 0.08%   |
| Apple                             | 4         | 0.08%   |
| Motorola PCS                      | 3         | 0.06%   |
| Google                            | 3         | 0.06%   |
| ASUSTek Computer                  | 3         | 0.06%   |
| AMD                               | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.04%   |
| Xiaomi                            | 2         | 0.04%   |
| Linksys                           | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 820       | 13.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 348       | 5.65%   |
| Intel Wi-Fi 6 AX200                                                     | 158       | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 149       | 2.42%   |
| Intel Wireless 8265 / 8275                                              | 136       | 2.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 122       | 1.98%   |
| Intel Wireless 7260                                                     | 122       | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 121       | 1.96%   |
| Intel Wireless 7265                                                     | 119       | 1.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 114       | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 111       | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 104       | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 101       | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 96        | 1.56%   |
| Intel Wireless 8260                                                     | 82        | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 78        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 77        | 1.25%   |
| Intel Wireless 3165                                                     | 68        | 1.1%    |
| Intel Wi-Fi 6 AX201                                                     | 68        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 67        | 1.09%   |
| Intel 82577LM Gigabit Network Connection                                | 63        | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 58        | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                           | 58        | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 56        | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 0.88%   |
| Intel Ethernet Connection I218-LM                                       | 53        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 53        | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                                   | 50        | 0.81%   |
| Intel Wireless 3160                                                     | 46        | 0.75%   |
| Intel Wireless-AC 9260                                                  | 45        | 0.73%   |
| Intel WiFi Link 5100                                                    | 45        | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 44        | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 44        | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 42        | 0.68%   |
| Intel Centrino Ultimate-N 6300                                          | 41        | 0.67%   |
| Intel Centrino Advanced-N 6200                                          | 40        | 0.65%   |
| Intel Centrino Advanced-N 6235                                          | 39        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 37        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                   | 36        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 36        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1689      | 49.57%  |
| Qualcomm Atheros                  | 632       | 18.55%  |
| Realtek Semiconductor             | 494       | 14.5%   |
| Broadcom                          | 294       | 8.63%   |
| Broadcom Limited                  | 72        | 2.11%   |
| Ralink                            | 42        | 1.23%   |
| Ralink Technology                 | 40        | 1.17%   |
| TP-Link                           | 30        | 0.88%   |
| MediaTek                          | 27        | 0.79%   |
| Dell                              | 16        | 0.47%   |
| Sierra Wireless                   | 11        | 0.32%   |
| Qualcomm                          | 7         | 0.21%   |
| NetGear                           | 7         | 0.21%   |
| Edimax Technology                 | 7         | 0.21%   |
| Qualcomm Atheros Communications   | 6         | 0.18%   |
| Micro Star International          | 5         | 0.15%   |
| Ericsson Business Mobile Networks | 5         | 0.15%   |
| Belkin Components                 | 5         | 0.15%   |
| Hewlett-Packard                   | 2         | 0.06%   |
| Fibocom                           | 2         | 0.06%   |
| ASUSTek Computer                  | 2         | 0.06%   |
| ZyDAS                             | 1         | 0.03%   |
| Wacom                             | 1         | 0.03%   |
| Senao                             | 1         | 0.03%   |
| Microsoft                         | 1         | 0.03%   |
| Marvell Technology Group          | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| InProComm                         | 1         | 0.03%   |
| Fujitsu Siemens Computers         | 1         | 0.03%   |
| D-Link                            | 1         | 0.03%   |
| Askey Computer                    | 1         | 0.03%   |
| Apple                             | 1         | 0.03%   |
| 3Com                              | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 158       | 4.61%   |
| Intel Wireless 8265 / 8275                                              | 136       | 3.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 122       | 3.56%   |
| Intel Wireless 7260                                                     | 122       | 3.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 121       | 3.53%   |
| Intel Wireless 7265                                                     | 119       | 3.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 111       | 3.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 104       | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 101       | 2.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 96        | 2.8%    |
| Intel Wireless 8260                                                     | 82        | 2.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 78        | 2.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 77        | 2.25%   |
| Intel Wireless 3165                                                     | 68        | 1.98%   |
| Intel Wi-Fi 6 AX201                                                     | 68        | 1.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 67        | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 58        | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                           | 58        | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 56        | 1.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 53        | 1.55%   |
| Intel Wireless 3160                                                     | 46        | 1.34%   |
| Intel Wireless-AC 9260                                                  | 45        | 1.31%   |
| Intel WiFi Link 5100                                                    | 45        | 1.31%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 44        | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 44        | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 42        | 1.23%   |
| Intel Centrino Ultimate-N 6300                                          | 41        | 1.2%    |
| Intel Centrino Advanced-N 6200                                          | 40        | 1.17%   |
| Intel Centrino Advanced-N 6235                                          | 39        | 1.14%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 37        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 36        | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 31        | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 30        | 0.88%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 28        | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 27        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 27        | 0.79%   |
| Intel Centrino Wireless-N 2230                                          | 26        | 0.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 26        | 0.76%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 25        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1332      | 50.72%  |
| Intel                            | 662       | 25.21%  |
| Qualcomm Atheros                 | 175       | 6.66%   |
| Broadcom                         | 158       | 6.02%   |
| Marvell Technology Group         | 84        | 3.2%    |
| Nvidia                           | 25        | 0.95%   |
| Broadcom Limited                 | 23        | 0.88%   |
| DisplayLink                      | 22        | 0.84%   |
| ASIX Electronics                 | 22        | 0.84%   |
| Lenovo                           | 18        | 0.69%   |
| Samsung Electronics              | 15        | 0.57%   |
| JMicron Technology               | 11        | 0.42%   |
| Silicon Integrated Systems [SiS] | 10        | 0.38%   |
| Huawei Technologies              | 9         | 0.34%   |
| Qualcomm                         | 8         | 0.3%    |
| TP-Link                          | 6         | 0.23%   |
| Attansic Technology              | 5         | 0.19%   |
| VIA Technologies                 | 4         | 0.15%   |
| OnePlus Technology (Shenzhen)    | 4         | 0.15%   |
| MediaTek                         | 4         | 0.15%   |
| ICS Advent                       | 4         | 0.15%   |
| Hewlett-Packard                  | 4         | 0.15%   |
| Motorola PCS                     | 3         | 0.11%   |
| Google                           | 3         | 0.11%   |
| Apple                            | 3         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.08%   |
| Xiaomi                           | 2         | 0.08%   |
| HTC (High Tech Computer)         | 2         | 0.08%   |
| T & A Mobile Phones              | 1         | 0.04%   |
| OPPO Electronics                 | 1         | 0.04%   |
| Microchip Technology             | 1         | 0.04%   |
| Linksys                          | 1         | 0.04%   |
| ASUSTek Computer                 | 1         | 0.04%   |
| Aquantia                         | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 820       | 30.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 348       | 13.14%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 149       | 5.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 114       | 4.3%    |
| Intel 82577LM Gigabit Network Connection                          | 63        | 2.38%   |
| Intel Ethernet Connection I218-LM                                 | 53        | 2%      |
| Intel Ethernet Connection (4) I219-LM                             | 50        | 1.89%   |
| Intel Ethernet Connection (3) I218-LM                             | 36        | 1.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 34        | 1.28%   |
| Intel Ethernet Connection I219-LM                                 | 34        | 1.28%   |
| Intel 82567LM Gigabit Network Connection                          | 34        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 32        | 1.21%   |
| Intel Ethernet Connection (4) I219-V                              | 29        | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 26        | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25        | 0.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 22        | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 21        | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 19        | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 18        | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 17        | 0.64%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 15        | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 15        | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.53%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 13        | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.49%   |
| Intel 82566MM Gigabit Network Connection                          | 13        | 0.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13        | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 12        | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12        | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                            | 11        | 0.42%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.42%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 11        | 0.42%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 11        | 0.42%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 10        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3206      | 54.99%  |
| Ethernet | 2539      | 43.55%  |
| Modem    | 80        | 1.37%   |
| Unknown  | 5         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2752      | 80.73%  |
| Ethernet | 657       | 19.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2321      | 71.22%  |
| 1     | 874       | 26.82%  |
| 0     | 50        | 1.53%   |
| 3     | 13        | 0.4%    |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2928      | 88.57%  |
| Yes  | 378       | 11.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1211      | 47.75%  |
| Qualcomm Atheros Communications | 240       | 9.46%   |
| Realtek Semiconductor           | 195       | 7.69%   |
| Broadcom                        | 180       | 7.1%    |
| IMC Networks                    | 145       | 5.72%   |
| Apple                           | 90        | 3.55%   |
| Lite-On Technology              | 85        | 3.35%   |
| Foxconn / Hon Hai               | 82        | 3.23%   |
| Dell                            | 70        | 2.76%   |
| Cambridge Silicon Radio         | 60        | 2.37%   |
| Toshiba                         | 49        | 1.93%   |
| Hewlett-Packard                 | 39        | 1.54%   |
| Realtek                         | 19        | 0.75%   |
| Alps Electric                   | 18        | 0.71%   |
| Foxconn International           | 14        | 0.55%   |
| Ralink                          | 9         | 0.35%   |
| Ralink Technology               | 6         | 0.24%   |
| ASUSTek Computer                | 6         | 0.24%   |
| Askey Computer                  | 6         | 0.24%   |
| Taiyo Yuden                     | 4         | 0.16%   |
| Belkin Components               | 4         | 0.16%   |
| USI                             | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 536       | 21.13%  |
| Intel Bluetooth Device                              | 208       | 8.2%    |
| Intel AX200 Bluetooth                               | 154       | 6.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 130       | 5.12%   |
| Realtek Bluetooth Radio                             | 108       | 4.26%   |
| IMC Networks Bluetooth Radio                        | 90        | 3.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 88        | 3.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 61        | 2.4%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 61        | 2.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 60        | 2.36%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 58        | 2.29%   |
| Apple Bluetooth Host Controller                     | 57        | 2.25%   |
| Lite-On Bluetooth Device                            | 54        | 2.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 48        | 1.89%   |
| Foxconn / Hon Hai Bluetooth Device                  | 47        | 1.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 1.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 37        | 1.46%   |
| Intel Wireless-AC 3168 Bluetooth                    | 36        | 1.42%   |
| Intel AX210 Bluetooth                               | 27        | 1.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 27        | 1.06%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 26        | 1.02%   |
| Dell DW375 Bluetooth Module                         | 26        | 1.02%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 24        | 0.95%   |
| Apple Bluetooth USB Host Controller                 | 24        | 0.95%   |
| IMC Networks Bluetooth Device                       | 22        | 0.87%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.79%   |
| Realtek Bluetooth Radio                             | 19        | 0.75%   |
| Dell BCM20702A0 Bluetooth Module                    | 18        | 0.71%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.67%   |
| IMC Networks Wireless_Device                        | 16        | 0.63%   |
| Toshiba Bluetooth Device                            | 15        | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 15        | 0.59%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.55%   |
| Broadcom HP Portable SoftSailing                    | 13        | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.47%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.47%   |
| Toshiba Atheros AR3012 Bluetooth                    | 10        | 0.39%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 10        | 0.39%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.35%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 9         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2624      | 68.21%  |
| AMD                              | 596       | 15.49%  |
| Nvidia                           | 400       | 10.4%   |
| C-Media Electronics              | 27        | 0.7%    |
| Realtek Semiconductor            | 20        | 0.52%   |
| Plantronics                      | 15        | 0.39%   |
| GN Netcom                        | 15        | 0.39%   |
| Lenovo                           | 13        | 0.34%   |
| Silicon Integrated Systems [SiS] | 12        | 0.31%   |
| Texas Instruments                | 11        | 0.29%   |
| JMTek                            | 8         | 0.21%   |
| Creative Technology              | 8         | 0.21%   |
| Apple                            | 8         | 0.21%   |
| Logitech                         | 6         | 0.16%   |
| Conexant Systems                 | 5         | 0.13%   |
| VIA Technologies                 | 4         | 0.1%    |
| Generalplus Technology           | 4         | 0.1%    |
| Corsair                          | 4         | 0.1%    |
| Blue Microphones                 | 4         | 0.1%    |
| Yamaha                           | 3         | 0.08%   |
| XMOS                             | 3         | 0.08%   |
| SteelSeries ApS                  | 3         | 0.08%   |
| Sony                             | 3         | 0.08%   |
| RODE Microphones                 | 3         | 0.08%   |
| Hewlett-Packard                  | 3         | 0.08%   |
| Focusrite-Novation               | 3         | 0.08%   |
| Dell                             | 3         | 0.08%   |
| ASUSTek Computer                 | 3         | 0.08%   |
| Sennheiser Communications        | 2         | 0.05%   |
| Samsung Electronics              | 2         | 0.05%   |
| PreSonus Audio Electronics       | 2         | 0.05%   |
| Kingston Technology              | 2         | 0.05%   |
| GYROCOM C&C                      | 2         | 0.05%   |
| Google                           | 2         | 0.05%   |
| AudioQuest                       | 2         | 0.05%   |
| AKAI Professional M.I.           | 2         | 0.05%   |
| Toshiba                          | 1         | 0.03%   |
| Tenx Technology                  | 1         | 0.03%   |
| Native Instruments               | 1         | 0.03%   |
| NanosIC                          | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 357       | 7.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 294       | 6.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 219       | 4.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 192       | 4.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 189       | 4.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 159       | 3.45%   |
| Intel 8 Series HD Audio Controller                                                                | 133       | 2.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 132       | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 130       | 2.82%   |
| Intel Broadwell-U Audio Controller                                                                | 120       | 2.6%    |
| AMD FCH Azalia Controller                                                                         | 119       | 2.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 116       | 2.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 103       | 2.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 101       | 2.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 94        | 2.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 93        | 2.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 92        | 2%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 78        | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 78        | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 77        | 1.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 76        | 1.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 75        | 1.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 74        | 1.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 73        | 1.58%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 64        | 1.39%   |
| AMD High Definition Audio Controller                                                              | 64        | 1.39%   |
| Intel CM238 HD Audio Controller                                                                   | 60        | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 59        | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 58        | 1.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 55        | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 48        | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 45        | 0.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 45        | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 41        | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 40        | 0.87%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 36        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 34        | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 32        | 0.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 29        | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 27        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 501       | 27.68%  |
| SK hynix            | 436       | 24.09%  |
| Micron Technology   | 233       | 12.87%  |
| Crucial             | 141       | 7.79%   |
| Unknown             | 134       | 7.4%    |
| Kingston            | 125       | 6.91%   |
| Ramaxel Technology  | 41        | 2.27%   |
| Corsair             | 41        | 2.27%   |
| Elpida              | 33        | 1.82%   |
| Nanya Technology    | 28        | 1.55%   |
| A-DATA Technology   | 18        | 0.99%   |
| Unknown (ABCD)      | 15        | 0.83%   |
| Unknown             | 7         | 0.39%   |
| Toshiba             | 6         | 0.33%   |
| Qimonda             | 5         | 0.28%   |
| GOODRAM             | 4         | 0.22%   |
| Transcend           | 3         | 0.17%   |
| Patriot             | 3         | 0.17%   |
| GSkill              | 3         | 0.17%   |
| ASint Technology    | 3         | 0.17%   |
| Apacer              | 3         | 0.17%   |
| Neo Forza           | 2         | 0.11%   |
| G.Skill             | 2         | 0.11%   |
| Essencore           | 2         | 0.11%   |
| A Force             | 2         | 0.11%   |
| V-Color             | 1         | 0.06%   |
| Unknown (F301)      | 1         | 0.06%   |
| Unknown (CB83)      | 1         | 0.06%   |
| Unknown (0B38)      | 1         | 0.06%   |
| Timetec             | 1         | 0.06%   |
| Smart               | 1         | 0.06%   |
| SHARETRONIC         | 1         | 0.06%   |
| OnBoard             | 1         | 0.06%   |
| Miron               | 1         | 0.06%   |
| Memox               | 1         | 0.06%   |
| KingFast            | 1         | 0.06%   |
| Gold Key            | 1         | 0.06%   |
| Foxline             | 1         | 0.06%   |
| ff                  | 1         | 0.06%   |
| ChangXin Memory     | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 38        | 1.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 28        | 1.45%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 1.24%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 22        | 1.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 21        | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 21        | 1.09%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.93%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 0.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 15        | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 13        | 0.67%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 13        | 0.67%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 13        | 0.67%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 12        | 0.62%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 12        | 0.62%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 0.62%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 12        | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.62%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 12        | 0.62%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s       | 12        | 0.62%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 11        | 0.57%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 11        | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.52%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.52%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 0.52%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 9         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.47%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 9         | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.47%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 9         | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.41%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.41%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 678       | 43.55%  |
| DDR3    | 533       | 34.23%  |
| DDR2    | 91        | 5.84%   |
| LPDDR3  | 82        | 5.27%   |
| LPDDR4  | 80        | 5.14%   |
| SDRAM   | 47        | 3.02%   |
| DDR5    | 15        | 0.96%   |
| Unknown | 11        | 0.71%   |
| DRAM    | 8         | 0.51%   |
| DDR     | 8         | 0.51%   |
| LPDDR5  | 4         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1353      | 87.57%  |
| Row Of Chips | 155       | 10.03%  |
| Chip         | 16        | 1.04%   |
| Unknown      | 14        | 0.91%   |
| DIMM         | 7         | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 636       | 37.68%  |
| 4096  | 516       | 30.57%  |
| 2048  | 228       | 13.51%  |
| 16384 | 201       | 11.91%  |
| 1024  | 69        | 4.09%   |
| 32768 | 27        | 1.6%    |
| 512   | 10        | 0.59%   |
| 256   | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 384       | 22.91%  |
| 2667    | 348       | 20.76%  |
| 3200    | 213       | 12.71%  |
| 2400    | 128       | 7.64%   |
| 2133    | 93        | 5.55%   |
| 1334    | 76        | 4.53%   |
| 1333    | 58        | 3.46%   |
| 667     | 45        | 2.68%   |
| 1867    | 43        | 2.57%   |
| Unknown | 40        | 2.39%   |
| 4267    | 35        | 2.09%   |
| 1067    | 32        | 1.91%   |
| 800     | 22        | 1.31%   |
| 3266    | 21        | 1.25%   |
| 4199    | 20        | 1.19%   |
| 2048    | 20        | 1.19%   |
| 4800    | 16        | 0.95%   |
| 1066    | 14        | 0.84%   |
| 4266    | 11        | 0.66%   |
| 975     | 11        | 0.66%   |
| 1866    | 8         | 0.48%   |
| 533     | 8         | 0.48%   |
| 8400    | 5         | 0.3%    |
| 3733    | 4         | 0.24%   |
| 6400    | 3         | 0.18%   |
| 3000    | 3         | 0.18%   |
| 1639    | 3         | 0.18%   |
| 400     | 3         | 0.18%   |
| 1776    | 2         | 0.12%   |
| 933     | 2         | 0.12%   |
| 333     | 2         | 0.12%   |
| 1596    | 1         | 0.06%   |
| 1200    | 1         | 0.06%   |
| 666     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Canon                 | 7         | 26.92%  |
| Hewlett-Packard       | 6         | 23.08%  |
| Samsung Electronics   | 3         | 11.54%  |
| Lexmark International | 3         | 11.54%  |
| Prolific Technology   | 2         | 7.69%   |
| Brother Industries    | 2         | 7.69%   |
| STMicroelectronics    | 1         | 3.85%   |
| Seiko Epson           | 1         | 3.85%   |
| Kyocera               | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                             | 2         | 7.41%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.7%    |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 3.7%    |
| Samsung CLX-6260 Series                                   | 1         | 3.7%    |
| Samsung CLP-300 Series                                    | 1         | 3.7%    |
| Samsung C43x Series                                       | 1         | 3.7%    |
| Lexmark International MS610de                             | 1         | 3.7%    |
| Lexmark International C544                                | 1         | 3.7%    |
| Lexmark International 640 Series                          | 1         | 3.7%    |
| Kyocera FS-1041                                           | 1         | 3.7%    |
| HP Officejet 4630 series                                  | 1         | 3.7%    |
| HP LaserJet P2015 series                                  | 1         | 3.7%    |
| HP LaserJet 1010                                          | 1         | 3.7%    |
| HP ENVY Photo 6200 series                                 | 1         | 3.7%    |
| HP ENVY 4520 series                                       | 1         | 3.7%    |
| HP Deskjet 2540 series                                    | 1         | 3.7%    |
| Canon SELPHY CP400                                        | 1         | 3.7%    |
| Canon PIXMA MX490 Series                                  | 1         | 3.7%    |
| Canon PIXMA MG2500 Series                                 | 1         | 3.7%    |
| Canon MF4360-4390                                         | 1         | 3.7%    |
| Canon LiDE 400                                            | 1         | 3.7%    |
| Canon iX6500 series                                       | 1         | 3.7%    |
| Canon iP4800 series                                       | 1         | 3.7%    |
| Canon CanoScan LiDE 300                                   | 1         | 3.7%    |
| Brother PT-9500PC                                         | 1         | 3.7%    |
| Brother DCP-L3510CDW                                      | 1         | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 62.5%   |
| Seiko Epson     | 2         | 25%     |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                     | 2         | 25%     |
| Seiko Epson Scanner                         | 1         | 12.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 12.5%   |
| HP ScanJet 5300c/5370c                      | 1         | 12.5%   |
| Canon CanoScan LiDE 600F                    | 1         | 12.5%   |
| Canon CanoScan LiDE 220                     | 1         | 12.5%   |
| Canon CanoScan LiDE 200                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 711       | 25.41%  |
| Microdia                               | 326       | 11.65%  |
| Realtek Semiconductor                  | 244       | 8.72%   |
| IMC Networks                           | 242       | 8.65%   |
| Acer                                   | 202       | 7.22%   |
| Sunplus Innovation Technology          | 149       | 5.33%   |
| Cheng Uei Precision Industry (Foxlink) | 119       | 4.25%   |
| Quanta                                 | 103       | 3.68%   |
| Suyin                                  | 101       | 3.61%   |
| Lite-On Technology                     | 79        | 2.82%   |
| Apple                                  | 71        | 2.54%   |
| Syntek                                 | 58        | 2.07%   |
| Silicon Motion                         | 57        | 2.04%   |
| Alcor Micro                            | 45        | 1.61%   |
| Ricoh                                  | 43        | 1.54%   |
| Logitech                               | 40        | 1.43%   |
| Lenovo                                 | 30        | 1.07%   |
| Luxvisions Innotech Limited            | 19        | 0.68%   |
| Samsung Electronics                    | 17        | 0.61%   |
| Z-Star Microelectronics                | 14        | 0.5%    |
| ALi                                    | 12        | 0.43%   |
| Primax Electronics                     | 11        | 0.39%   |
| Microsoft                              | 9         | 0.32%   |
| Sonix Technology                       | 8         | 0.29%   |
| Importek                               | 6         | 0.21%   |
| Generalplus Technology                 | 6         | 0.21%   |
| Sunplus Technology                     | 5         | 0.18%   |
| OmniVision Technologies                | 5         | 0.18%   |
| Intel                                  | 5         | 0.18%   |
| DigiTech                               | 5         | 0.18%   |
| SunplusIT                              | 4         | 0.14%   |
| ARC International                      | 4         | 0.14%   |
| Unknown                                | 3         | 0.11%   |
| MacroSilicon                           | 3         | 0.11%   |
| Genesys Logic                          | 3         | 0.11%   |
| GEMBIRD                                | 3         | 0.11%   |
| Foxconn / Hon Hai                      | 3         | 0.11%   |
| Y Media                                | 2         | 0.07%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.07%   |
| Razer USA                              | 2         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 161       | 5.72%   |
| Chicony Integrated Camera                               | 122       | 4.33%   |
| Realtek Integrated_Webcam_HD                            | 84        | 2.98%   |
| IMC Networks Integrated Camera                          | 65        | 2.31%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 63        | 2.24%   |
| Chicony HD WebCam                                       | 61        | 2.17%   |
| Sunplus Integrated_Webcam_HD                            | 51        | 1.81%   |
| Acer Integrated Camera                                  | 37        | 1.31%   |
| Microdia Integrated Webcam                              | 36        | 1.28%   |
| Chicony USB2.0 Camera                                   | 36        | 1.28%   |
| Realtek USB Camera                                      | 31        | 1.1%    |
| Chicony TOSHIBA Web Camera - HD                         | 31        | 1.1%    |
| Lite-On Integrated Camera                               | 30        | 1.07%   |
| Apple Built-in iSight                                   | 28        | 0.99%   |
| Chicony HP TrueVision HD Camera                         | 27        | 0.96%   |
| Acer Lenovo EasyCamera                                  | 27        | 0.96%   |
| Acer BisonCam,NB Pro                                    | 27        | 0.96%   |
| Chicony USB 2.0 Camera                                  | 25        | 0.89%   |
| Chicony VGA WebCam                                      | 24        | 0.85%   |
| Syntek Lenovo EasyCamera                                | 22        | 0.78%   |
| Chicony HP Truevision HD                                | 21        | 0.75%   |
| Chicony HP HD Camera                                    | 21        | 0.75%   |
| Chicony EasyCamera                                      | 21        | 0.75%   |
| Apple FaceTime HD Camera                                | 21        | 0.75%   |
| Acer SunplusIT Integrated Camera                        | 20        | 0.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 19        | 0.67%   |
| Chicony Integrated Camera (1280x720@30)                 | 19        | 0.67%   |
| Chicony CNF9055 Toshiba Webcam                          | 19        | 0.67%   |
| Quanta HD User Facing                                   | 18        | 0.64%   |
| Samsung Galaxy A5 (MTP)                                 | 17        | 0.6%    |
| Lenovo Integrated Webcam [R5U877]                       | 17        | 0.6%    |
| Chicony Lenovo Integrated Camera (0.3MP)                | 17        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 17        | 0.6%    |
| Syntek Integrated Camera                                | 16        | 0.57%   |
| Realtek Integrated Webcam HD                            | 16        | 0.57%   |
| Alcor Micro USB Camera                                  | 16        | 0.57%   |
| Syntek EasyCamera                                       | 15        | 0.53%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 15        | 0.53%   |
| Microdia Integrated Webcam HD                           | 15        | 0.53%   |
| Chicony HP Wide Vision HD Camera                        | 15        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 181       | 32.67%  |
| Synaptics                  | 136       | 24.55%  |
| Shenzhen Goodix Technology | 87        | 15.7%   |
| AuthenTec                  | 46        | 8.3%    |
| Upek                       | 44        | 7.94%   |
| LighTuning Technology      | 28        | 5.05%   |
| Elan Microelectronics      | 17        | 3.07%   |
| STMicroelectronics         | 13        | 2.35%   |
| Samsung Electronics        | 1         | 0.18%   |
| Focal-systems.Corp         | 1         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 46        | 8.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 43        | 7.76%   |
| Unknown                                                                    | 38        | 6.86%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 37        | 6.68%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 34        | 6.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 31        | 5.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 4.15%   |
| Shenzhen Goodix FingerPrint                                                | 22        | 3.97%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 3.43%   |
| Validity Sensors Synaptics WBDI                                            | 18        | 3.25%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 2.71%   |
| Validity Sensors VFS491                                                    | 14        | 2.53%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 2.53%   |
| STMicroelectronics Fingerprint Reader                                      | 13        | 2.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 2.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 12        | 2.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 2.17%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.17%   |
| AuthenTec AES2810                                                          | 11        | 1.99%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.81%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.81%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.81%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.62%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.62%   |
| Synaptics WBDI Device                                                      | 8         | 1.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.44%   |
| Synaptics  WBDI                                                            | 7         | 1.26%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.26%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.9%    |
| Elan ELAN:ARM-M4                                                           | 5         | 0.9%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.9%    |
| AuthenTec AES1600                                                          | 5         | 0.9%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 0.72%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.72%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.72%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.54%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.36%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.18%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.18%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 153       | 53.13%  |
| Alcor Micro           | 61        | 21.18%  |
| Upek                  | 23        | 7.99%   |
| O2 Micro              | 21        | 7.29%   |
| Lenovo                | 20        | 6.94%   |
| Gemalto (was Gemplus) | 4         | 1.39%   |
| SCM Microsystems      | 3         | 1.04%   |
| Purism, SPC           | 1         | 0.35%   |
| Clay Logic            | 1         | 0.35%   |
| Chicony Electronics   | 1         | 0.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 65        | 22.57%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 60        | 20.83%  |
| Broadcom 5880                                                                | 39        | 13.54%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 28        | 9.72%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 23        | 7.99%   |
| Lenovo Integrated Smart Card Reader                                          | 19        | 6.6%    |
| Broadcom 58200                                                               | 19        | 6.6%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 16        | 5.56%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.74%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.04%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.69%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.35%   |
| Purism, SPC Librem Key                                                       | 1         | 0.35%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.35%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.35%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.35%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.35%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2068      | 62.16%  |
| 1     | 964       | 28.98%  |
| 2     | 252       | 7.57%   |
| 3     | 33        | 0.99%   |
| 4     | 4         | 0.12%   |
| 5     | 3         | 0.09%   |
| 8     | 1         | 0.03%   |
| 7     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 538       | 34.33%  |
| Graphics card            | 283       | 18.06%  |
| Chipcard                 | 266       | 16.98%  |
| Net/wireless             | 174       | 11.1%   |
| Multimedia controller    | 78        | 4.98%   |
| Communication controller | 39        | 2.49%   |
| Storage                  | 35        | 2.23%   |
| Bluetooth                | 34        | 2.17%   |
| Camera                   | 29        | 1.85%   |
| Sound                    | 18        | 1.15%   |
| Card reader              | 18        | 1.15%   |
| Modem                    | 15        | 0.96%   |
| Net/ethernet             | 14        | 0.89%   |
| Flash memory             | 8         | 0.51%   |
| Network                  | 7         | 0.45%   |
| Firewire controller      | 4         | 0.26%   |
| Storage/nvme             | 3         | 0.19%   |
| Unassigned class         | 2         | 0.13%   |
| Storage/ide              | 2         | 0.13%   |

