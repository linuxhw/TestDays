Ubuntu 23.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 906

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ENVY 15                     | [996948fd3c](https://linux-hardware.org/?probe=996948fd3c) | Sep 07, 2023 |
| Dell          | XPS 15 9550                 | [c9f30a2b26](https://linux-hardware.org/?probe=c9f30a2b26) | Sep 06, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HH0... | [94c99c8274](https://linux-hardware.org/?probe=94c99c8274) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [b6b2af8418](https://linux-hardware.org/?probe=b6b2af8418) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [89767db9e4](https://linux-hardware.org/?probe=89767db9e4) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | [aa37593b87](https://linux-hardware.org/?probe=aa37593b87) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | [230cd8c32e](https://linux-hardware.org/?probe=230cd8c32e) | Sep 06, 2023 |
| Dell          | Precision 5570              | [9baca62616](https://linux-hardware.org/?probe=9baca62616) | Sep 06, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [8d550b32d9](https://linux-hardware.org/?probe=8d550b32d9) | Sep 06, 2023 |
| HP            | ZBook Studio G3             | [208f21a716](https://linux-hardware.org/?probe=208f21a716) | Sep 05, 2023 |
| Dell          | G5 5590                     | [40098c0a79](https://linux-hardware.org/?probe=40098c0a79) | Sep 05, 2023 |
| Dell          | G5 5590                     | [1af9fd689a](https://linux-hardware.org/?probe=1af9fd689a) | Sep 05, 2023 |
| Acer          | Aspire A315-24P             | [d082fdd668](https://linux-hardware.org/?probe=d082fdd668) | Sep 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9accfe317a](https://linux-hardware.org/?probe=9accfe317a) | Sep 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [daeb81e2f6](https://linux-hardware.org/?probe=daeb81e2f6) | Sep 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [b7d2eae326](https://linux-hardware.org/?probe=b7d2eae326) | Sep 04, 2023 |
| Dell          | Inspiron 5770               | [1f2c94fe31](https://linux-hardware.org/?probe=1f2c94fe31) | Sep 03, 2023 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | [f9ae8ae2db](https://linux-hardware.org/?probe=f9ae8ae2db) | Sep 03, 2023 |
| HP            | OMEN by Laptop              | [a135074689](https://linux-hardware.org/?probe=a135074689) | Sep 03, 2023 |
| ASUSTek       | X540NA                      | [e335c8210f](https://linux-hardware.org/?probe=e335c8210f) | Sep 03, 2023 |
| ASUSTek       | X55A                        | [da721dec12](https://linux-hardware.org/?probe=da721dec12) | Sep 03, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [e27673ed4c](https://linux-hardware.org/?probe=e27673ed4c) | Sep 03, 2023 |
| HUAWEI        | FRD-WX9                     | [5831652a84](https://linux-hardware.org/?probe=5831652a84) | Sep 03, 2023 |
| Acer          | Aspire A715-75G             | [69b91f1c46](https://linux-hardware.org/?probe=69b91f1c46) | Sep 03, 2023 |
| VENEZOLANA... | VIT P2460-02                | [9c1d875ec4](https://linux-hardware.org/?probe=9c1d875ec4) | Sep 03, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [c5787921e3](https://linux-hardware.org/?probe=c5787921e3) | Sep 03, 2023 |
| Acer          | Aspire A517-51G             | [762498a914](https://linux-hardware.org/?probe=762498a914) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ddae17d733](https://linux-hardware.org/?probe=ddae17d733) | Sep 02, 2023 |
| HP            | EliteBook 8460p             | [b6f6192ef9](https://linux-hardware.org/?probe=b6f6192ef9) | Sep 02, 2023 |
| Lenovo        | IdeaPad Slim 5 16IAH8 83... | [2cfbf5b20c](https://linux-hardware.org/?probe=2cfbf5b20c) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [60889fc028](https://linux-hardware.org/?probe=60889fc028) | Sep 02, 2023 |
| HP            | 245 G7 Notebook PC          | [bb268c3828](https://linux-hardware.org/?probe=bb268c3828) | Sep 02, 2023 |
| Dell          | Inspiron 5720               | [9b802cfff6](https://linux-hardware.org/?probe=9b802cfff6) | Sep 02, 2023 |
| Dell          | Inspiron 1545               | [cb4847f435](https://linux-hardware.org/?probe=cb4847f435) | Sep 01, 2023 |
| Acer          | Swift SF114-34              | [987f4bab43](https://linux-hardware.org/?probe=987f4bab43) | Aug 31, 2023 |
| Toshiba       | Satellite S75-B             | [2ffc319636](https://linux-hardware.org/?probe=2ffc319636) | Aug 31, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [23242fe856](https://linux-hardware.org/?probe=23242fe856) | Aug 31, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [5cfa9a748f](https://linux-hardware.org/?probe=5cfa9a748f) | Aug 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [f01ca37e4c](https://linux-hardware.org/?probe=f01ca37e4c) | Aug 31, 2023 |
| ASUSTek       | Zenbook UX6404VV_UX6404V... | [b7be264a8d](https://linux-hardware.org/?probe=b7be264a8d) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | [1964cb4738](https://linux-hardware.org/?probe=1964cb4738) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | [7176f2933c](https://linux-hardware.org/?probe=7176f2933c) | Aug 30, 2023 |
| HP            | Dragonfly Pro Laptop PC     | [2b08121ea1](https://linux-hardware.org/?probe=2b08121ea1) | Aug 30, 2023 |
| Infinix       | INBOOK X2 SLIM              | [93fd8245ab](https://linux-hardware.org/?probe=93fd8245ab) | Aug 29, 2023 |
| Infinix       | INBOOK X2 SLIM              | [fafc374d46](https://linux-hardware.org/?probe=fafc374d46) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | [8a7f22304b](https://linux-hardware.org/?probe=8a7f22304b) | Aug 29, 2023 |
| HP            | ZBook Studio G3             | [bdaea6156d](https://linux-hardware.org/?probe=bdaea6156d) | Aug 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [863b7d7901](https://linux-hardware.org/?probe=863b7d7901) | Aug 29, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [e5923577ad](https://linux-hardware.org/?probe=e5923577ad) | Aug 28, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [c6e30be0e9](https://linux-hardware.org/?probe=c6e30be0e9) | Aug 27, 2023 |
| HP            | EliteBook 840 G5            | [cd64a75511](https://linux-hardware.org/?probe=cd64a75511) | Aug 27, 2023 |
| HP            | Compaq nx6325 (EN188UT#A... | [4324feffa1](https://linux-hardware.org/?probe=4324feffa1) | Aug 27, 2023 |
| Dell          | XPS 13 9310                 | [9dddd0c80b](https://linux-hardware.org/?probe=9dddd0c80b) | Aug 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [0fd39b7eb6](https://linux-hardware.org/?probe=0fd39b7eb6) | Aug 27, 2023 |
| Lenovo        | ThinkPad X200 7459ED2       | [4885ef4597](https://linux-hardware.org/?probe=4885ef4597) | Aug 27, 2023 |
| Apple         | MacBookPro16,2              | [f153f48649](https://linux-hardware.org/?probe=f153f48649) | Aug 27, 2023 |
| HP            | 2000                        | [a63dd6e0f1](https://linux-hardware.org/?probe=a63dd6e0f1) | Aug 26, 2023 |
| Dell          | Latitude 7380               | [396738805e](https://linux-hardware.org/?probe=396738805e) | Aug 26, 2023 |
| Dell          | Latitude 7380               | [4a0db5ad8a](https://linux-hardware.org/?probe=4a0db5ad8a) | Aug 26, 2023 |
| Acer          | Aspire V5-571               | [033994cebf](https://linux-hardware.org/?probe=033994cebf) | Aug 26, 2023 |
| Apple         | MacBookPro7,1               | [a8d794f4bb](https://linux-hardware.org/?probe=a8d794f4bb) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [a305956d47](https://linux-hardware.org/?probe=a305956d47) | Aug 26, 2023 |
| Dell          | XPS 13 9300                 | [ca90d2134f](https://linux-hardware.org/?probe=ca90d2134f) | Aug 26, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [01ae0852df](https://linux-hardware.org/?probe=01ae0852df) | Aug 25, 2023 |
| Lenovo        | G50-70 20351                | [25c5011587](https://linux-hardware.org/?probe=25c5011587) | Aug 25, 2023 |
| Casper        | NIRVANA NB X400             | [e8aa46ffbc](https://linux-hardware.org/?probe=e8aa46ffbc) | Aug 25, 2023 |
| Dell          | G3 3579                     | [843084a77c](https://linux-hardware.org/?probe=843084a77c) | Aug 25, 2023 |
| HP            | Notebook                    | [6404f1dc3a](https://linux-hardware.org/?probe=6404f1dc3a) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [aa3de32445](https://linux-hardware.org/?probe=aa3de32445) | Aug 25, 2023 |
| Lenovo        | V15-IIL 82C5                | [cee65701f2](https://linux-hardware.org/?probe=cee65701f2) | Aug 25, 2023 |
| Acer          | Nitro AN515-45              | [de7752b138](https://linux-hardware.org/?probe=de7752b138) | Aug 25, 2023 |
| Notebook      | NL5xNU                      | [116561b889](https://linux-hardware.org/?probe=116561b889) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [3ce0d3817d](https://linux-hardware.org/?probe=3ce0d3817d) | Aug 25, 2023 |
| Lenovo        | ThinkPad T460s 20F90039U... | [e632335144](https://linux-hardware.org/?probe=e632335144) | Aug 25, 2023 |
| Dell          | Latitude E5570              | [2694b6c409](https://linux-hardware.org/?probe=2694b6c409) | Aug 24, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582HM_... | [2281d96afb](https://linux-hardware.org/?probe=2281d96afb) | Aug 24, 2023 |
| HP            | ENVY 15                     | [6367186102](https://linux-hardware.org/?probe=6367186102) | Aug 24, 2023 |
| Acer          | Aspire 5750G                | [b7ab89701b](https://linux-hardware.org/?probe=b7ab89701b) | Aug 24, 2023 |
| HP            | Notebook                    | [1d3025a033](https://linux-hardware.org/?probe=1d3025a033) | Aug 24, 2023 |
| Dell          | System XPS L502X            | [a5357a41b4](https://linux-hardware.org/?probe=a5357a41b4) | Aug 23, 2023 |
| HP            | Pavilion x2 Detachable      | [a8fb075a9a](https://linux-hardware.org/?probe=a8fb075a9a) | Aug 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1d0505af7f](https://linux-hardware.org/?probe=1d0505af7f) | Aug 23, 2023 |
| Infinix       | INBOOK X2                   | [297d07a2e3](https://linux-hardware.org/?probe=297d07a2e3) | Aug 22, 2023 |
| Dell          | Latitude E6430              | [8125ef4bf1](https://linux-hardware.org/?probe=8125ef4bf1) | Aug 22, 2023 |
| Intel         | HuronRiver Platform         | [7cf233eb4d](https://linux-hardware.org/?probe=7cf233eb4d) | Aug 22, 2023 |
| HP            | ZBook Studio G3             | [cc07dc8140](https://linux-hardware.org/?probe=cc07dc8140) | Aug 22, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | [f30e9be6d0](https://linux-hardware.org/?probe=f30e9be6d0) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [210e9d3b38](https://linux-hardware.org/?probe=210e9d3b38) | Aug 21, 2023 |
| HP            | EliteBook 845 14 inch G9... | [75776f43bf](https://linux-hardware.org/?probe=75776f43bf) | Aug 21, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [81bc5661ca](https://linux-hardware.org/?probe=81bc5661ca) | Aug 21, 2023 |
| Dell          | Inspiron 5720               | [c2ca279bdd](https://linux-hardware.org/?probe=c2ca279bdd) | Aug 21, 2023 |
| Medion        | WIM2210                     | [5ef8675128](https://linux-hardware.org/?probe=5ef8675128) | Aug 21, 2023 |
| HP            | EliteBook 835 13 inch G9... | [f973c9678d](https://linux-hardware.org/?probe=f973c9678d) | Aug 20, 2023 |
| HP            | Victus by Gaming Laptop ... | [872053c50b](https://linux-hardware.org/?probe=872053c50b) | Aug 20, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [a11383f5b3](https://linux-hardware.org/?probe=a11383f5b3) | Aug 19, 2023 |
| Lenovo        | V320-17ISK 81B6             | [cc96bcc8d9](https://linux-hardware.org/?probe=cc96bcc8d9) | Aug 19, 2023 |
| Dell          | XPS 15 7590                 | [b7347b4f7c](https://linux-hardware.org/?probe=b7347b4f7c) | Aug 19, 2023 |
| HP            | Laptop 14-fq0xxx            | [950ffc31ff](https://linux-hardware.org/?probe=950ffc31ff) | Aug 18, 2023 |
| Apple         | MacBookAir7,2               | [e37325dbc2](https://linux-hardware.org/?probe=e37325dbc2) | Aug 18, 2023 |
| HP            | 255 G7 Notebook PC          | [79d5cb1a00](https://linux-hardware.org/?probe=79d5cb1a00) | Aug 18, 2023 |
| Apple         | MacBookAir6,1               | [ed669d11d8](https://linux-hardware.org/?probe=ed669d11d8) | Aug 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b65293c5a8](https://linux-hardware.org/?probe=b65293c5a8) | Aug 17, 2023 |
| Intel         | SandyBridge Platform        | [0e1961a9b3](https://linux-hardware.org/?probe=0e1961a9b3) | Aug 17, 2023 |
| Acer          | Swift SF314-510G            | [11a4bc0bac](https://linux-hardware.org/?probe=11a4bc0bac) | Aug 16, 2023 |
| Dell          | Precision 7530              | [dfaa8829e1](https://linux-hardware.org/?probe=dfaa8829e1) | Aug 16, 2023 |
| ASUSTek       | X55A                        | [03099661ec](https://linux-hardware.org/?probe=03099661ec) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [4c4e9222ce](https://linux-hardware.org/?probe=4c4e9222ce) | Aug 16, 2023 |
| Shuttle       | NC03U                       | [91097c1ebf](https://linux-hardware.org/?probe=91097c1ebf) | Aug 16, 2023 |
| Acer          | Aspire V5-571               | [bb39a5a125](https://linux-hardware.org/?probe=bb39a5a125) | Aug 15, 2023 |
| HP            | 15                          | [c4b30192fa](https://linux-hardware.org/?probe=c4b30192fa) | Aug 15, 2023 |
| Lenovo        | G50-70 20351                | [ea9845e55b](https://linux-hardware.org/?probe=ea9845e55b) | Aug 15, 2023 |
| HP            | ENVY 15                     | [caa5e1d37a](https://linux-hardware.org/?probe=caa5e1d37a) | Aug 14, 2023 |
| MSI           | Stealth 14Studio A13VG      | [a8035775f2](https://linux-hardware.org/?probe=a8035775f2) | Aug 14, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [9a680df78d](https://linux-hardware.org/?probe=9a680df78d) | Aug 14, 2023 |
| Alienware     | m15 R7                      | [a501a43d37](https://linux-hardware.org/?probe=a501a43d37) | Aug 14, 2023 |
| Acer          | Aspire A317-33              | [e069c1f3d5](https://linux-hardware.org/?probe=e069c1f3d5) | Aug 13, 2023 |
| Acer          | Aspire A315-51              | [c94361f09d](https://linux-hardware.org/?probe=c94361f09d) | Aug 13, 2023 |
| Acer          | Extensa 5220                | [fb3e613b5c](https://linux-hardware.org/?probe=fb3e613b5c) | Aug 13, 2023 |
| HP            | EliteBook 840 G6            | [bcf7b9bd8f](https://linux-hardware.org/?probe=bcf7b9bd8f) | Aug 13, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [fee93b31f5](https://linux-hardware.org/?probe=fee93b31f5) | Aug 13, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [4d954b8546](https://linux-hardware.org/?probe=4d954b8546) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7d7349fef7](https://linux-hardware.org/?probe=7d7349fef7) | Aug 12, 2023 |
| Toshiba       | Satellite C50D-B            | [61f00a0418](https://linux-hardware.org/?probe=61f00a0418) | Aug 12, 2023 |
| Dell          | Inspiron 13 5310            | [d42fa686e5](https://linux-hardware.org/?probe=d42fa686e5) | Aug 12, 2023 |
| Dell          | Inspiron 13 5310            | [45509c2727](https://linux-hardware.org/?probe=45509c2727) | Aug 12, 2023 |
| Dell          | XPS 15 9560                 | [756901f27f](https://linux-hardware.org/?probe=756901f27f) | Aug 12, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [8abafe1b65](https://linux-hardware.org/?probe=8abafe1b65) | Aug 12, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5892469c5b](https://linux-hardware.org/?probe=5892469c5b) | Aug 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [53196a01fa](https://linux-hardware.org/?probe=53196a01fa) | Aug 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [f8c24a1b02](https://linux-hardware.org/?probe=f8c24a1b02) | Aug 11, 2023 |
| ASUSTek       | K55A                        | [bf260cea2c](https://linux-hardware.org/?probe=bf260cea2c) | Aug 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [b21e9793a5](https://linux-hardware.org/?probe=b21e9793a5) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [fadee3e38d](https://linux-hardware.org/?probe=fadee3e38d) | Aug 11, 2023 |
| Dell          | Precision 5530              | [f74dac5dcf](https://linux-hardware.org/?probe=f74dac5dcf) | Aug 11, 2023 |
| Dell          | Latitude 5400               | [1ec248c607](https://linux-hardware.org/?probe=1ec248c607) | Aug 10, 2023 |
| Lenovo        | ThinkPad Edge 03193VG       | [abb370836a](https://linux-hardware.org/?probe=abb370836a) | Aug 10, 2023 |
| Avell         | A70 ION                     | [6ab02a34e4](https://linux-hardware.org/?probe=6ab02a34e4) | Aug 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [89e3ef8e6c](https://linux-hardware.org/?probe=89e3ef8e6c) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4180X06       | [77e54b4b97](https://linux-hardware.org/?probe=77e54b4b97) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4180X06       | [ba950eb9e1](https://linux-hardware.org/?probe=ba950eb9e1) | Aug 10, 2023 |
| Google        | Snappy                      | [73ecdd5048](https://linux-hardware.org/?probe=73ecdd5048) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [92fda27219](https://linux-hardware.org/?probe=92fda27219) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [3bd085d1a5](https://linux-hardware.org/?probe=3bd085d1a5) | Aug 10, 2023 |
| Lenovo        | ThinkPad T430 2347AT2       | [a874870955](https://linux-hardware.org/?probe=a874870955) | Aug 09, 2023 |
| Acer          | Aspire A317-53              | [de8d362cb8](https://linux-hardware.org/?probe=de8d362cb8) | Aug 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [194ec12831](https://linux-hardware.org/?probe=194ec12831) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | [abf7479cb8](https://linux-hardware.org/?probe=abf7479cb8) | Aug 09, 2023 |
| Acer          | Aspire V3-112P              | [e6305472c5](https://linux-hardware.org/?probe=e6305472c5) | Aug 09, 2023 |
| Dell          | Latitude 3350               | [77100b2ef6](https://linux-hardware.org/?probe=77100b2ef6) | Aug 09, 2023 |
| Dell          | Latitude 5400               | [773e9320a8](https://linux-hardware.org/?probe=773e9320a8) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | [f3ee04187f](https://linux-hardware.org/?probe=f3ee04187f) | Aug 09, 2023 |
| Acer          | Aspire 4820TG               | [49a63e5cc4](https://linux-hardware.org/?probe=49a63e5cc4) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | [60a28c22c7](https://linux-hardware.org/?probe=60a28c22c7) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | [9f044dbe9e](https://linux-hardware.org/?probe=9f044dbe9e) | Aug 08, 2023 |
| HP            | ProBook 455 G7              | [bd9f67ee72](https://linux-hardware.org/?probe=bd9f67ee72) | Aug 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3ec4223487](https://linux-hardware.org/?probe=3ec4223487) | Aug 07, 2023 |
| Dell          | Latitude 7300               | [932f04033c](https://linux-hardware.org/?probe=932f04033c) | Aug 07, 2023 |
| Dell          | XPS 15 9500                 | [dbefafc94d](https://linux-hardware.org/?probe=dbefafc94d) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [ce02da2586](https://linux-hardware.org/?probe=ce02da2586) | Aug 07, 2023 |
| Acer          | Nitro AN517-52              | [d24385ceb8](https://linux-hardware.org/?probe=d24385ceb8) | Aug 07, 2023 |
| Timi          | TM1607                      | [c545853106](https://linux-hardware.org/?probe=c545853106) | Aug 07, 2023 |
| HP            | EliteBook 840 G6            | [9f230de889](https://linux-hardware.org/?probe=9f230de889) | Aug 07, 2023 |
| HP            | ProBook 450 G2              | [de0ce7c424](https://linux-hardware.org/?probe=de0ce7c424) | Aug 06, 2023 |
| HP            | ProBook 640 G2              | [8dae611904](https://linux-hardware.org/?probe=8dae611904) | Aug 06, 2023 |
| ASUSTek       | K54L                        | [3ce0c0b7b2](https://linux-hardware.org/?probe=3ce0c0b7b2) | Aug 06, 2023 |
| HP            | EliteBook 840 G1            | [8a0a837f0b](https://linux-hardware.org/?probe=8a0a837f0b) | Aug 06, 2023 |
| ASUSTek       | K54L                        | [b28f27325f](https://linux-hardware.org/?probe=b28f27325f) | Aug 06, 2023 |
| Acer          | Aspire A515-56              | [dfe905b869](https://linux-hardware.org/?probe=dfe905b869) | Aug 06, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [4bd753037a](https://linux-hardware.org/?probe=4bd753037a) | Aug 06, 2023 |
| Dell          | Inspiron 15 5510            | [88f7813621](https://linux-hardware.org/?probe=88f7813621) | Aug 06, 2023 |
| HP            | EliteBook 840 G1            | [cc48d8c23e](https://linux-hardware.org/?probe=cc48d8c23e) | Aug 06, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [52b9918d42](https://linux-hardware.org/?probe=52b9918d42) | Aug 06, 2023 |
| Unknown       | Unknown                     | [9431f6f4e8](https://linux-hardware.org/?probe=9431f6f4e8) | Aug 06, 2023 |
| Dell          | Latitude 5590               | [83d389e795](https://linux-hardware.org/?probe=83d389e795) | Aug 06, 2023 |
| Dell          | Latitude 5400               | [e788e3a534](https://linux-hardware.org/?probe=e788e3a534) | Aug 05, 2023 |
| Dell          | Latitude E6420              | [3636e69adb](https://linux-hardware.org/?probe=3636e69adb) | Aug 05, 2023 |
| ASUSTek       | K52Je                       | [34fa8887dd](https://linux-hardware.org/?probe=34fa8887dd) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [24dc4f34a2](https://linux-hardware.org/?probe=24dc4f34a2) | Aug 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [779c23fe06](https://linux-hardware.org/?probe=779c23fe06) | Aug 05, 2023 |
| Lenovo        | ThinkPad X131e 33671S2      | [3f83b5efac](https://linux-hardware.org/?probe=3f83b5efac) | Aug 05, 2023 |
| MSI           | GF75 Thin 10SCXR            | [21d2f0b558](https://linux-hardware.org/?probe=21d2f0b558) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [364aa911cf](https://linux-hardware.org/?probe=364aa911cf) | Aug 05, 2023 |
| Apple         | MacBookPro14,1              | [08f78bf99a](https://linux-hardware.org/?probe=08f78bf99a) | Aug 05, 2023 |
| HP            | EliteBook 8740w             | [b30001b3fe](https://linux-hardware.org/?probe=b30001b3fe) | Aug 05, 2023 |
| HP            | ZBook Studio G3             | [3f7f45a94e](https://linux-hardware.org/?probe=3f7f45a94e) | Aug 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f7354ee466](https://linux-hardware.org/?probe=f7354ee466) | Aug 04, 2023 |
| Apple         | MacBookAir7,2               | [e21469f818](https://linux-hardware.org/?probe=e21469f818) | Aug 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [8a2dafef83](https://linux-hardware.org/?probe=8a2dafef83) | Aug 04, 2023 |
| HP            | Laptop 14s-dq2xxx           | [8aad3290a7](https://linux-hardware.org/?probe=8aad3290a7) | Aug 03, 2023 |
| Apple         | MacBookAir7,2               | [89c0c5c135](https://linux-hardware.org/?probe=89c0c5c135) | Aug 03, 2023 |
| HP            | ZBook Studio G3             | [69b35fdf25](https://linux-hardware.org/?probe=69b35fdf25) | Aug 03, 2023 |
| Shanghai Z... | ZXE CRB                     | [2d4fc6f4ce](https://linux-hardware.org/?probe=2d4fc6f4ce) | Aug 03, 2023 |
| Dell          | Latitude 5490               | [e93c786075](https://linux-hardware.org/?probe=e93c786075) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | [38f33f3878](https://linux-hardware.org/?probe=38f33f3878) | Aug 03, 2023 |
| Samsung       | 930X2K/931X2K               | [5985901bef](https://linux-hardware.org/?probe=5985901bef) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | [49a27fb8fb](https://linux-hardware.org/?probe=49a27fb8fb) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | [e2d58e4a51](https://linux-hardware.org/?probe=e2d58e4a51) | Aug 03, 2023 |
| HP            | Notebook                    | [0e8585ef71](https://linux-hardware.org/?probe=0e8585ef71) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5f2529e42b](https://linux-hardware.org/?probe=5f2529e42b) | Aug 02, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [4d0d3b78e7](https://linux-hardware.org/?probe=4d0d3b78e7) | Aug 02, 2023 |
| Unknown       | Unknown                     | [41ff18df05](https://linux-hardware.org/?probe=41ff18df05) | Aug 02, 2023 |
| Unknown       | Unknown                     | [eb3d428d41](https://linux-hardware.org/?probe=eb3d428d41) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [cbc721a89f](https://linux-hardware.org/?probe=cbc721a89f) | Aug 01, 2023 |
| HP            | Unknown                     | [f7ffb3c085](https://linux-hardware.org/?probe=f7ffb3c085) | Aug 01, 2023 |
| Acer          | Aspire E5-573G              | [7e3e1a7ee9](https://linux-hardware.org/?probe=7e3e1a7ee9) | Jul 31, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [ff6816b285](https://linux-hardware.org/?probe=ff6816b285) | Jul 31, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [71379f70f2](https://linux-hardware.org/?probe=71379f70f2) | Jul 30, 2023 |
| Dell          | Latitude E6510              | [f8ebba29c6](https://linux-hardware.org/?probe=f8ebba29c6) | Jul 30, 2023 |
| HP            | ProBook 4540s               | [0fae07b574](https://linux-hardware.org/?probe=0fae07b574) | Jul 30, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [579d4eebb8](https://linux-hardware.org/?probe=579d4eebb8) | Jul 29, 2023 |
| Dell          | Precision 5510              | [56b4073d3f](https://linux-hardware.org/?probe=56b4073d3f) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0180... | [cde4989301](https://linux-hardware.org/?probe=cde4989301) | Jul 28, 2023 |
| Apple         | MacBookAir7,2               | [3e7b8ae52e](https://linux-hardware.org/?probe=3e7b8ae52e) | Jul 28, 2023 |
| HP            | ZBook Studio G3             | [68618d14ef](https://linux-hardware.org/?probe=68618d14ef) | Jul 28, 2023 |
| Dell          | Vostro 15 3515              | [08990a8da3](https://linux-hardware.org/?probe=08990a8da3) | Jul 28, 2023 |
| HUAWEI        | BOM-WXX9                    | [1e0ad64e6f](https://linux-hardware.org/?probe=1e0ad64e6f) | Jul 27, 2023 |
| Toshiba       | PORTEGE X30-E               | [c610464fb5](https://linux-hardware.org/?probe=c610464fb5) | Jul 27, 2023 |
| Apple         | MacBookPro8,1               | [d54574b3f8](https://linux-hardware.org/?probe=d54574b3f8) | Jul 27, 2023 |
| HP            | Laptop 14s-fq1xxx           | [84ab2faa6f](https://linux-hardware.org/?probe=84ab2faa6f) | Jul 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [44647ce47e](https://linux-hardware.org/?probe=44647ce47e) | Jul 26, 2023 |
| Apple         | MacBookPro8,1               | [d0d94c9be7](https://linux-hardware.org/?probe=d0d94c9be7) | Jul 26, 2023 |
| Acer          | Nitro AN17-41               | [7909f8c5f3](https://linux-hardware.org/?probe=7909f8c5f3) | Jul 26, 2023 |
| Dell          | XPS 15 9530                 | [d6855eabe2](https://linux-hardware.org/?probe=d6855eabe2) | Jul 26, 2023 |
| HP            | Pavilion dv6                | [1ed1c25f7e](https://linux-hardware.org/?probe=1ed1c25f7e) | Jul 26, 2023 |
| HP            | ProBook 450 G2              | [18eceddda0](https://linux-hardware.org/?probe=18eceddda0) | Jul 26, 2023 |
| HP            | ProBook 4540s               | [f41d6c4f4b](https://linux-hardware.org/?probe=f41d6c4f4b) | Jul 26, 2023 |
| Sony          | VPCSB1V9R                   | [12b5777cff](https://linux-hardware.org/?probe=12b5777cff) | Jul 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [802ba60219](https://linux-hardware.org/?probe=802ba60219) | Jul 25, 2023 |
| Apple         | MacBookPro9,2               | [af0355313e](https://linux-hardware.org/?probe=af0355313e) | Jul 25, 2023 |
| HP            | Laptop 17-cp0xxx            | [f8720bbd07](https://linux-hardware.org/?probe=f8720bbd07) | Jul 25, 2023 |
| Lenovo        | B590 62743QG                | [d8bd2493ec](https://linux-hardware.org/?probe=d8bd2493ec) | Jul 25, 2023 |
| MSI           | WF66 11UJ                   | [305e24e26d](https://linux-hardware.org/?probe=305e24e26d) | Jul 25, 2023 |
| HP            | ProBook 4540s               | [5c4b165cea](https://linux-hardware.org/?probe=5c4b165cea) | Jul 25, 2023 |
| HP            | ProBook 4540s               | [4ad8be01ca](https://linux-hardware.org/?probe=4ad8be01ca) | Jul 25, 2023 |
| Dell          | Latitude 5420               | [c286ff883f](https://linux-hardware.org/?probe=c286ff883f) | Jul 24, 2023 |
| HP            | EliteBook 840 G3            | [72a17a2b8f](https://linux-hardware.org/?probe=72a17a2b8f) | Jul 24, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [02cae62d32](https://linux-hardware.org/?probe=02cae62d32) | Jul 24, 2023 |
| Google        | Treeya                      | [808e203694](https://linux-hardware.org/?probe=808e203694) | Jul 24, 2023 |
| Google        | Treeya                      | [db2b782253](https://linux-hardware.org/?probe=db2b782253) | Jul 24, 2023 |
| Dell          | Inspiron 3543               | [3fd49d8f38](https://linux-hardware.org/?probe=3fd49d8f38) | Jul 24, 2023 |
| Lenovo        | ThinkPad P50 20EQS2A500     | [d25f59d64d](https://linux-hardware.org/?probe=d25f59d64d) | Jul 23, 2023 |
| ASUSTek       | X45U                        | [53a411cd41](https://linux-hardware.org/?probe=53a411cd41) | Jul 23, 2023 |
| Google        | Lillipup                    | [3915bca457](https://linux-hardware.org/?probe=3915bca457) | Jul 23, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [383118634e](https://linux-hardware.org/?probe=383118634e) | Jul 23, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0XV0... | [4a5ded3dcc](https://linux-hardware.org/?probe=4a5ded3dcc) | Jul 23, 2023 |
| Lenovo        | ThinkPad P53 20QN004BCA     | [04a2ed4bd2](https://linux-hardware.org/?probe=04a2ed4bd2) | Jul 23, 2023 |
| MSI           | Cyborg 15 A12VF             | [62efe51727](https://linux-hardware.org/?probe=62efe51727) | Jul 23, 2023 |
| Dell          | Latitude 3500               | [fcfa320897](https://linux-hardware.org/?probe=fcfa320897) | Jul 23, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [1ee910fc1c](https://linux-hardware.org/?probe=1ee910fc1c) | Jul 22, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [d02b0e9f74](https://linux-hardware.org/?probe=d02b0e9f74) | Jul 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [808ae8a334](https://linux-hardware.org/?probe=808ae8a334) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [ca2f317f1a](https://linux-hardware.org/?probe=ca2f317f1a) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [9f14acd318](https://linux-hardware.org/?probe=9f14acd318) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [fee4019ae0](https://linux-hardware.org/?probe=fee4019ae0) | Jul 22, 2023 |
| Acer          | Aspire A514-53              | [b754fb3410](https://linux-hardware.org/?probe=b754fb3410) | Jul 21, 2023 |
| Dell          | XPS 9315                    | [f97422b64b](https://linux-hardware.org/?probe=f97422b64b) | Jul 21, 2023 |
| ASUSTek       | B53E                        | [08012052d5](https://linux-hardware.org/?probe=08012052d5) | Jul 21, 2023 |
| Acer          | Aspire E5-553               | [1321d9a034](https://linux-hardware.org/?probe=1321d9a034) | Jul 21, 2023 |
| Acer          | Aspire E5-553               | [7ef01e963d](https://linux-hardware.org/?probe=7ef01e963d) | Jul 21, 2023 |
| HP            | Laptop 14-fq0xxx            | [ce5f140a90](https://linux-hardware.org/?probe=ce5f140a90) | Jul 21, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [e9a58d14e7](https://linux-hardware.org/?probe=e9a58d14e7) | Jul 20, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [64b51936ea](https://linux-hardware.org/?probe=64b51936ea) | Jul 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [903099ae11](https://linux-hardware.org/?probe=903099ae11) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [26a2238069](https://linux-hardware.org/?probe=26a2238069) | Jul 19, 2023 |
| Lenovo        | ThinkPad E560 20EV000YUK    | [0e89144534](https://linux-hardware.org/?probe=0e89144534) | Jul 19, 2023 |
| Fujitsu       | LIFEBOOK A544               | [5643f29431](https://linux-hardware.org/?probe=5643f29431) | Jul 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a646f5d0fb](https://linux-hardware.org/?probe=a646f5d0fb) | Jul 19, 2023 |
| Apple         | MacBookPro5,5               | [b5b8d4fce2](https://linux-hardware.org/?probe=b5b8d4fce2) | Jul 19, 2023 |
| Acer          | Nitro AN17-41               | [81c4c542a9](https://linux-hardware.org/?probe=81c4c542a9) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [dac4434339](https://linux-hardware.org/?probe=dac4434339) | Jul 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | [631e54097b](https://linux-hardware.org/?probe=631e54097b) | Jul 18, 2023 |
| HP            | EliteBook 745 G5            | [7b7cf50cba](https://linux-hardware.org/?probe=7b7cf50cba) | Jul 18, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [dc76c90236](https://linux-hardware.org/?probe=dc76c90236) | Jul 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | [192f8de028](https://linux-hardware.org/?probe=192f8de028) | Jul 18, 2023 |
| Dell          | Latitude 7480               | [83caa544f7](https://linux-hardware.org/?probe=83caa544f7) | Jul 18, 2023 |
| Dell          | Latitude 7480               | [526e020c94](https://linux-hardware.org/?probe=526e020c94) | Jul 18, 2023 |
| Dell          | Latitude 3500               | [bd6b4ea554](https://linux-hardware.org/?probe=bd6b4ea554) | Jul 18, 2023 |
| ASUSTek       | X756UQ                      | [be24f941c7](https://linux-hardware.org/?probe=be24f941c7) | Jul 17, 2023 |
| Google        | Lick                        | [be8f8d1fd5](https://linux-hardware.org/?probe=be8f8d1fd5) | Jul 17, 2023 |
| Dell          | Inspiron 5521               | [16715e16b9](https://linux-hardware.org/?probe=16715e16b9) | Jul 17, 2023 |
| Dell          | Latitude 7420               | [acf0339a4c](https://linux-hardware.org/?probe=acf0339a4c) | Jul 17, 2023 |
| Dell          | Latitude E7470              | [a3b762c162](https://linux-hardware.org/?probe=a3b762c162) | Jul 17, 2023 |
| Dell          | Latitude E7470              | [69531585c0](https://linux-hardware.org/?probe=69531585c0) | Jul 17, 2023 |
| Google        | Lick                        | [177ed7483f](https://linux-hardware.org/?probe=177ed7483f) | Jul 16, 2023 |
| Dell          | G5 5587                     | [fc861c593a](https://linux-hardware.org/?probe=fc861c593a) | Jul 16, 2023 |
| Apple         | MacBookAir6,2               | [0059901b85](https://linux-hardware.org/?probe=0059901b85) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [45c881b739](https://linux-hardware.org/?probe=45c881b739) | Jul 16, 2023 |
| Dell          | Inspiron 3442               | [4767e5dc31](https://linux-hardware.org/?probe=4767e5dc31) | Jul 15, 2023 |
| Gigabyte      | P65                         | [b46e8302f7](https://linux-hardware.org/?probe=b46e8302f7) | Jul 15, 2023 |
| Acer          | Aspire A315-51              | [938e7cd384](https://linux-hardware.org/?probe=938e7cd384) | Jul 15, 2023 |
| Samsung       | 300E5K/300E5Q               | [92bd2944cb](https://linux-hardware.org/?probe=92bd2944cb) | Jul 15, 2023 |
| Lenovo        | ThinkPad X250 20CL00DHBR    | [dd92f9ce05](https://linux-hardware.org/?probe=dd92f9ce05) | Jul 14, 2023 |
| Alienware     | m15 R7                      | [99e796a389](https://linux-hardware.org/?probe=99e796a389) | Jul 14, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [ea96a066b6](https://linux-hardware.org/?probe=ea96a066b6) | Jul 14, 2023 |
| Lenovo        | G50-70 20351                | [b8481d7a4c](https://linux-hardware.org/?probe=b8481d7a4c) | Jul 14, 2023 |
| Alienware     | m15 R7                      | [e80cfeb390](https://linux-hardware.org/?probe=e80cfeb390) | Jul 14, 2023 |
| Notebook      | N150ZU                      | [61be22ac36](https://linux-hardware.org/?probe=61be22ac36) | Jul 14, 2023 |
| Apple         | MacBookAir6,2               | [5932f3d2eb](https://linux-hardware.org/?probe=5932f3d2eb) | Jul 14, 2023 |
| HP            | ENVY 15                     | [d69bc2702c](https://linux-hardware.org/?probe=d69bc2702c) | Jul 14, 2023 |
| Dell          | Latitude 7480               | [b0ce3265f2](https://linux-hardware.org/?probe=b0ce3265f2) | Jul 14, 2023 |
| Lenovo        | ThinkPad Edge E535 3260C... | [9ff1a61e2a](https://linux-hardware.org/?probe=9ff1a61e2a) | Jul 14, 2023 |
| HP            | Laptop 17-bs1xx             | [26a95caa91](https://linux-hardware.org/?probe=26a95caa91) | Jul 14, 2023 |
| Unknown       | Unknown                     | [a67315ae3e](https://linux-hardware.org/?probe=a67315ae3e) | Jul 13, 2023 |
| Acer          | Swift SF314-71              | [95a7d172c2](https://linux-hardware.org/?probe=95a7d172c2) | Jul 13, 2023 |
| Acer          | Swift SF314-71              | [876eb35009](https://linux-hardware.org/?probe=876eb35009) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | [69bd0f2129](https://linux-hardware.org/?probe=69bd0f2129) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | [20225a0680](https://linux-hardware.org/?probe=20225a0680) | Jul 13, 2023 |
| Acer          | Aspire 4820TG               | [a93793ae9c](https://linux-hardware.org/?probe=a93793ae9c) | Jul 13, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | [1412ecd811](https://linux-hardware.org/?probe=1412ecd811) | Jul 13, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | [49657bd961](https://linux-hardware.org/?probe=49657bd961) | Jul 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [d5ff5f9f79](https://linux-hardware.org/?probe=d5ff5f9f79) | Jul 13, 2023 |
| Positivo      | A14CR6A                     | [7ad49c61bd](https://linux-hardware.org/?probe=7ad49c61bd) | Jul 13, 2023 |
| HP            | Notebook                    | [adbdafe73d](https://linux-hardware.org/?probe=adbdafe73d) | Jul 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0V30... | [174cb234d5](https://linux-hardware.org/?probe=174cb234d5) | Jul 12, 2023 |
| HUAWEI        | RLEF-XX                     | [8974860f56](https://linux-hardware.org/?probe=8974860f56) | Jul 12, 2023 |
| Intel Clie... | LAPBC710                    | [c957ebba28](https://linux-hardware.org/?probe=c957ebba28) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [e594307388](https://linux-hardware.org/?probe=e594307388) | Jul 12, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [706f24ffe5](https://linux-hardware.org/?probe=706f24ffe5) | Jul 12, 2023 |
| Lenovo        | ThinkPad X230 2324DP1       | [5b139ff19a](https://linux-hardware.org/?probe=5b139ff19a) | Jul 12, 2023 |
| Samsung       | 950XED                      | [2f8f9d9277](https://linux-hardware.org/?probe=2f8f9d9277) | Jul 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [e40458ffe3](https://linux-hardware.org/?probe=e40458ffe3) | Jul 12, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [90466d16ca](https://linux-hardware.org/?probe=90466d16ca) | Jul 11, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [5a1636d8ce](https://linux-hardware.org/?probe=5a1636d8ce) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [0fbc8ca097](https://linux-hardware.org/?probe=0fbc8ca097) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [fddbab0cf6](https://linux-hardware.org/?probe=fddbab0cf6) | Jul 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [443e3f909c](https://linux-hardware.org/?probe=443e3f909c) | Jul 11, 2023 |
| Acer          | Aspire A715-71G             | [cd76343b6e](https://linux-hardware.org/?probe=cd76343b6e) | Jul 11, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | [52f242e136](https://linux-hardware.org/?probe=52f242e136) | Jul 10, 2023 |
| Dell          | Latitude 3580               | [b1bfa37b93](https://linux-hardware.org/?probe=b1bfa37b93) | Jul 10, 2023 |
| Dell          | XPS 15 9530                 | [f60d21d84f](https://linux-hardware.org/?probe=f60d21d84f) | Jul 10, 2023 |
| Acer          | ConceptD CN315-71P          | [a211dd78de](https://linux-hardware.org/?probe=a211dd78de) | Jul 09, 2023 |
| Dell          | Inspiron 3521               | [49c5ec535d](https://linux-hardware.org/?probe=49c5ec535d) | Jul 09, 2023 |
| Acer          | Aspire 4720Z                | [312486a5b7](https://linux-hardware.org/?probe=312486a5b7) | Jul 09, 2023 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | [e9410cf823](https://linux-hardware.org/?probe=e9410cf823) | Jul 09, 2023 |
| Lenovo        | ThinkPad P50 20EQS2A500     | [d053bea459](https://linux-hardware.org/?probe=d053bea459) | Jul 09, 2023 |
| Acer          | Nitro AN515-46              | [010208e38d](https://linux-hardware.org/?probe=010208e38d) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [b01bdb1bd6](https://linux-hardware.org/?probe=b01bdb1bd6) | Jul 08, 2023 |
| HP            | 14                          | [71d49b008d](https://linux-hardware.org/?probe=71d49b008d) | Jul 08, 2023 |
| HP            | 14                          | [ba511c29ac](https://linux-hardware.org/?probe=ba511c29ac) | Jul 08, 2023 |
| Dell          | Latitude 5290 2-in-1        | [61e7b20b21](https://linux-hardware.org/?probe=61e7b20b21) | Jul 08, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [31d5e724ba](https://linux-hardware.org/?probe=31d5e724ba) | Jul 07, 2023 |
| HP            | ZBook Studio G3             | [790145611f](https://linux-hardware.org/?probe=790145611f) | Jul 07, 2023 |
| Samsung       | 930X2K/931X2K               | [fd0d25039d](https://linux-hardware.org/?probe=fd0d25039d) | Jul 07, 2023 |
| Samsung       | 930X2K/931X2K               | [294e57d915](https://linux-hardware.org/?probe=294e57d915) | Jul 07, 2023 |
| Notebook      | NJx0PU                      | [29ebf426d1](https://linux-hardware.org/?probe=29ebf426d1) | Jul 06, 2023 |
| Toshiba       | PORTEGE X30-E               | [d68e9cd764](https://linux-hardware.org/?probe=d68e9cd764) | Jul 06, 2023 |
| HP            | Laptop 15-fc0xxx            | [a0183085b8](https://linux-hardware.org/?probe=a0183085b8) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [265dc6c0e9](https://linux-hardware.org/?probe=265dc6c0e9) | Jul 06, 2023 |
| HUAWEI        | HVY-WXX9                    | [8d64c46d1d](https://linux-hardware.org/?probe=8d64c46d1d) | Jul 06, 2023 |
| Sony          | VPCEA1AGG                   | [edbc1fff31](https://linux-hardware.org/?probe=edbc1fff31) | Jul 05, 2023 |
| HP            | EliteBook 755 G5            | [356eae0e07](https://linux-hardware.org/?probe=356eae0e07) | Jul 05, 2023 |
| Acer          | Predator G9-591             | [3c20dda613](https://linux-hardware.org/?probe=3c20dda613) | Jul 05, 2023 |
| Dell          | Latitude 5480               | [ac446902dd](https://linux-hardware.org/?probe=ac446902dd) | Jul 05, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [8e16561151](https://linux-hardware.org/?probe=8e16561151) | Jul 05, 2023 |
| HP            | 650                         | [a3077996ad](https://linux-hardware.org/?probe=a3077996ad) | Jul 05, 2023 |
| Dell          | Latitude 3500               | [2ab8fe06f8](https://linux-hardware.org/?probe=2ab8fe06f8) | Jul 05, 2023 |
| Apple         | MacBook8,1                  | [d27490cbe0](https://linux-hardware.org/?probe=d27490cbe0) | Jul 04, 2023 |
| Lenovo        | ThinkPad X250 20CL00DHBR    | [e8f0daea94](https://linux-hardware.org/?probe=e8f0daea94) | Jul 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [d47bc7229c](https://linux-hardware.org/?probe=d47bc7229c) | Jul 04, 2023 |
| Acer          | Aspire 4820TG               | [69e40b4481](https://linux-hardware.org/?probe=69e40b4481) | Jul 04, 2023 |
| MSI           | GF63 Thin 11UC              | [86c82575ec](https://linux-hardware.org/?probe=86c82575ec) | Jul 04, 2023 |
| Acer          | Aspire E5-771G              | [39716dd662](https://linux-hardware.org/?probe=39716dd662) | Jul 03, 2023 |
| Samsung       | 950XED                      | [e81ef31b14](https://linux-hardware.org/?probe=e81ef31b14) | Jul 03, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [75a8750d34](https://linux-hardware.org/?probe=75a8750d34) | Jul 03, 2023 |
| HP            | Laptop 15-da0xxx            | [4e2a9c1363](https://linux-hardware.org/?probe=4e2a9c1363) | Jul 03, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [275acaaa00](https://linux-hardware.org/?probe=275acaaa00) | Jul 03, 2023 |
| Dell          | Latitude 3500               | [4f287ac318](https://linux-hardware.org/?probe=4f287ac318) | Jul 03, 2023 |
| Acer          | Aspire A315-21              | [eaeac1cc79](https://linux-hardware.org/?probe=eaeac1cc79) | Jul 03, 2023 |
| Sony          | VPCEA1AGG                   | [de28a65daa](https://linux-hardware.org/?probe=de28a65daa) | Jul 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [51d003ae6a](https://linux-hardware.org/?probe=51d003ae6a) | Jul 02, 2023 |
| Lenovo        | G50-70 20351                | [033ce7c13d](https://linux-hardware.org/?probe=033ce7c13d) | Jul 02, 2023 |
| Dell          | XPS 17 9710                 | [8f6145f929](https://linux-hardware.org/?probe=8f6145f929) | Jul 02, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [d703fd9378](https://linux-hardware.org/?probe=d703fd9378) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [3271b3b559](https://linux-hardware.org/?probe=3271b3b559) | Jul 02, 2023 |
| HP            | OMEN by Laptop              | [6ad6d2e8c6](https://linux-hardware.org/?probe=6ad6d2e8c6) | Jul 02, 2023 |
| Gigabyte      | Q2532N                      | [4560685060](https://linux-hardware.org/?probe=4560685060) | Jul 02, 2023 |
| HP            | 245 G6 Notebook PC          | [48195d85f8](https://linux-hardware.org/?probe=48195d85f8) | Jul 02, 2023 |
| Acer          | Aspire A315-21              | [079e6d2d51](https://linux-hardware.org/?probe=079e6d2d51) | Jul 02, 2023 |
| Samsung       | 300E5K/300E5Q               | [5248df0795](https://linux-hardware.org/?probe=5248df0795) | Jul 01, 2023 |
| Acer          | Aspire A315-21              | [079de94ff1](https://linux-hardware.org/?probe=079de94ff1) | Jul 01, 2023 |
| Dell          | Latitude E6410              | [675794fe6e](https://linux-hardware.org/?probe=675794fe6e) | Jul 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [c66f880677](https://linux-hardware.org/?probe=c66f880677) | Jul 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [a1a9486fc8](https://linux-hardware.org/?probe=a1a9486fc8) | Jul 01, 2023 |
| Dell          | Latitude 7390               | [ef05796af7](https://linux-hardware.org/?probe=ef05796af7) | Jul 01, 2023 |
| Timi          | TM1701                      | [5dee3c6b81](https://linux-hardware.org/?probe=5dee3c6b81) | Jul 01, 2023 |
| Dell          | Latitude 7390               | [ea8982e574](https://linux-hardware.org/?probe=ea8982e574) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | [88b4565c0b](https://linux-hardware.org/?probe=88b4565c0b) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | [7e1b98b585](https://linux-hardware.org/?probe=7e1b98b585) | Jul 01, 2023 |
| HP            | 245 G6 Notebook PC          | [189320a2cf](https://linux-hardware.org/?probe=189320a2cf) | Jul 01, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [b5d1a7e115](https://linux-hardware.org/?probe=b5d1a7e115) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430 2347AT2       | [951adb91cd](https://linux-hardware.org/?probe=951adb91cd) | Jun 30, 2023 |
| HP            | ProBook 650 G5              | [99a03772fb](https://linux-hardware.org/?probe=99a03772fb) | Jun 30, 2023 |
| HP            | Laptop 17-cp2xxx            | [2012cd2c37](https://linux-hardware.org/?probe=2012cd2c37) | Jun 30, 2023 |
| HP            | 245 G6 Notebook PC          | [22a896d74b](https://linux-hardware.org/?probe=22a896d74b) | Jun 30, 2023 |
| Dell          | Latitude 5440               | [7868400967](https://linux-hardware.org/?probe=7868400967) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1e4c2cf905](https://linux-hardware.org/?probe=1e4c2cf905) | Jun 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [b98433fa84](https://linux-hardware.org/?probe=b98433fa84) | Jun 29, 2023 |
| Acer          | NC-A515-51G-59DM            | [a521f2cc60](https://linux-hardware.org/?probe=a521f2cc60) | Jun 29, 2023 |
| Intel         | Whiskey Platform            | [1caca06d89](https://linux-hardware.org/?probe=1caca06d89) | Jun 29, 2023 |
| ASUSTek       | K56CB                       | [952909bc80](https://linux-hardware.org/?probe=952909bc80) | Jun 29, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [61930889dc](https://linux-hardware.org/?probe=61930889dc) | Jun 29, 2023 |
| Unknown       | Unknown                     | [d358089f32](https://linux-hardware.org/?probe=d358089f32) | Jun 29, 2023 |
| HP            | Laptop 17-cp2xxx            | [f1a1aa76e2](https://linux-hardware.org/?probe=f1a1aa76e2) | Jun 29, 2023 |
| Sony          | SVE17137CXB                 | [ed6f82dc16](https://linux-hardware.org/?probe=ed6f82dc16) | Jun 29, 2023 |
| Acer          | Nitro AN515-55              | [a41ff8c573](https://linux-hardware.org/?probe=a41ff8c573) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | [3c4acbf380](https://linux-hardware.org/?probe=3c4acbf380) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ff560998d8](https://linux-hardware.org/?probe=ff560998d8) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7017964456](https://linux-hardware.org/?probe=7017964456) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | [8ae62960d8](https://linux-hardware.org/?probe=8ae62960d8) | Jun 28, 2023 |
| Acer          | Nitro AN515-54              | [b30ff15571](https://linux-hardware.org/?probe=b30ff15571) | Jun 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [90a10ed8ed](https://linux-hardware.org/?probe=90a10ed8ed) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [4e40b350ca](https://linux-hardware.org/?probe=4e40b350ca) | Jun 28, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | [1d6bf708ce](https://linux-hardware.org/?probe=1d6bf708ce) | Jun 28, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [8ef6f6f24a](https://linux-hardware.org/?probe=8ef6f6f24a) | Jun 27, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [d4c9f8de35](https://linux-hardware.org/?probe=d4c9f8de35) | Jun 27, 2023 |
| HP            | ENVY 15                     | [0d46d829d2](https://linux-hardware.org/?probe=0d46d829d2) | Jun 27, 2023 |
| HP            | ENVY 15                     | [189cf01c37](https://linux-hardware.org/?probe=189cf01c37) | Jun 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7497c404d4](https://linux-hardware.org/?probe=7497c404d4) | Jun 27, 2023 |
| Daten Tecn... | ESTELAR                     | [0052df6a90](https://linux-hardware.org/?probe=0052df6a90) | Jun 27, 2023 |
| Daten Tecn... | ESTELAR                     | [d5f99bced6](https://linux-hardware.org/?probe=d5f99bced6) | Jun 26, 2023 |
| HUAWEI        | BOM-WXX9                    | [2e9bc10188](https://linux-hardware.org/?probe=2e9bc10188) | Jun 26, 2023 |
| Gateway       | NV57H                       | [a49db45595](https://linux-hardware.org/?probe=a49db45595) | Jun 26, 2023 |
| Gateway       | NV57H                       | [ee84597590](https://linux-hardware.org/?probe=ee84597590) | Jun 26, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | [70a6547925](https://linux-hardware.org/?probe=70a6547925) | Jun 26, 2023 |
| Star Labs     | LabTop                      | [87a0d9dc09](https://linux-hardware.org/?probe=87a0d9dc09) | Jun 26, 2023 |
| Acer          | TravelMate 6493             | [490906b996](https://linux-hardware.org/?probe=490906b996) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [286826f3b2](https://linux-hardware.org/?probe=286826f3b2) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b15f68a294](https://linux-hardware.org/?probe=b15f68a294) | Jun 25, 2023 |
| Acer          | Nitro AN517-54              | [9a87719748](https://linux-hardware.org/?probe=9a87719748) | Jun 25, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [9f1f9757a2](https://linux-hardware.org/?probe=9f1f9757a2) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [223911e8f0](https://linux-hardware.org/?probe=223911e8f0) | Jun 25, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | [1809b4709e](https://linux-hardware.org/?probe=1809b4709e) | Jun 25, 2023 |
| HP            | EliteBook 840 G4            | [2e20ab8996](https://linux-hardware.org/?probe=2e20ab8996) | Jun 25, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [7d8f0212e9](https://linux-hardware.org/?probe=7d8f0212e9) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | [ade3806ebb](https://linux-hardware.org/?probe=ade3806ebb) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [8a22a7fba4](https://linux-hardware.org/?probe=8a22a7fba4) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | [b82cc440a0](https://linux-hardware.org/?probe=b82cc440a0) | Jun 24, 2023 |
| Dell          | G5 5590                     | [6d6974b0eb](https://linux-hardware.org/?probe=6d6974b0eb) | Jun 24, 2023 |
| HP            | ENVY 15                     | [3918cca1e5](https://linux-hardware.org/?probe=3918cca1e5) | Jun 23, 2023 |
| Acer          | Swift SFE16-42              | [9afa4fb174](https://linux-hardware.org/?probe=9afa4fb174) | Jun 22, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [44050251e9](https://linux-hardware.org/?probe=44050251e9) | Jun 22, 2023 |
| Positivo      | Mobile                      | [f9a55866f0](https://linux-hardware.org/?probe=f9a55866f0) | Jun 22, 2023 |
| Positivo      | Mobile                      | [25df2e5abc](https://linux-hardware.org/?probe=25df2e5abc) | Jun 22, 2023 |
| Acer          | Aspire E5-575G              | [0fb6c61a2b](https://linux-hardware.org/?probe=0fb6c61a2b) | Jun 21, 2023 |
| Acer          | Aspire A515-53G             | [430cfefc6a](https://linux-hardware.org/?probe=430cfefc6a) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | [f96a1a3552](https://linux-hardware.org/?probe=f96a1a3552) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | [52c4c32098](https://linux-hardware.org/?probe=52c4c32098) | Jun 21, 2023 |
| HP            | EliteBook 830 G6            | [7a29f3d086](https://linux-hardware.org/?probe=7a29f3d086) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [513165d4f6](https://linux-hardware.org/?probe=513165d4f6) | Jun 20, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [b51dda105a](https://linux-hardware.org/?probe=b51dda105a) | Jun 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [bff08fbf94](https://linux-hardware.org/?probe=bff08fbf94) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [15e75e17fc](https://linux-hardware.org/?probe=15e75e17fc) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [6dea148dd7](https://linux-hardware.org/?probe=6dea148dd7) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [91f85b5bb5](https://linux-hardware.org/?probe=91f85b5bb5) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [93f576698e](https://linux-hardware.org/?probe=93f576698e) | Jun 19, 2023 |
| HP            | Laptop 15-rb0xx             | [067eeb10e5](https://linux-hardware.org/?probe=067eeb10e5) | Jun 19, 2023 |
| HP            | Notebook                    | [6df5e3f6ff](https://linux-hardware.org/?probe=6df5e3f6ff) | Jun 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [948225d98e](https://linux-hardware.org/?probe=948225d98e) | Jun 18, 2023 |
| Toshiba       | Satellite-L845              | [cfe5a81354](https://linux-hardware.org/?probe=cfe5a81354) | Jun 18, 2023 |
| ASUSTek       | X555LJ                      | [a4bea0f3e3](https://linux-hardware.org/?probe=a4bea0f3e3) | Jun 18, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [8bf2dd01d7](https://linux-hardware.org/?probe=8bf2dd01d7) | Jun 18, 2023 |
| Panasonic     | CF-54-2                     | [48b7e4f212](https://linux-hardware.org/?probe=48b7e4f212) | Jun 18, 2023 |
| HP            | Pavilion dv6                | [f47b055767](https://linux-hardware.org/?probe=f47b055767) | Jun 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | [8f32e75d6e](https://linux-hardware.org/?probe=8f32e75d6e) | Jun 18, 2023 |
| Medion        | S15449                      | [9ee17b411b](https://linux-hardware.org/?probe=9ee17b411b) | Jun 17, 2023 |
| HP            | ENVY 15                     | [10a4cb8865](https://linux-hardware.org/?probe=10a4cb8865) | Jun 17, 2023 |
| Acer          | Aspire A715-71G             | [0ef00ccccc](https://linux-hardware.org/?probe=0ef00ccccc) | Jun 16, 2023 |
| Toshiba       | Satellite C870-199          | [cc18b4ff53](https://linux-hardware.org/?probe=cc18b4ff53) | Jun 16, 2023 |
| MSI           | GF63 Thin 10SC              | [cd928f7cc4](https://linux-hardware.org/?probe=cd928f7cc4) | Jun 16, 2023 |
| MSI           | GF63 Thin 10SC              | [3204bd2215](https://linux-hardware.org/?probe=3204bd2215) | Jun 16, 2023 |
| Packard Be... | EasyNote TK87               | [eeb1bdc4d1](https://linux-hardware.org/?probe=eeb1bdc4d1) | Jun 15, 2023 |
| Packard Be... | EasyNote TK87               | [3ba89fb405](https://linux-hardware.org/?probe=3ba89fb405) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [fe65868ffe](https://linux-hardware.org/?probe=fe65868ffe) | Jun 15, 2023 |
| MSI           | Stealth GS77 12UE           | [48df655e45](https://linux-hardware.org/?probe=48df655e45) | Jun 15, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [e9aeb26aeb](https://linux-hardware.org/?probe=e9aeb26aeb) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [f675b70f23](https://linux-hardware.org/?probe=f675b70f23) | Jun 14, 2023 |
| Dell          | XPS 15 9510                 | [9a8a71741e](https://linux-hardware.org/?probe=9a8a71741e) | Jun 14, 2023 |
| Sony          | SVS1312J3EW                 | [6668ed0dbe](https://linux-hardware.org/?probe=6668ed0dbe) | Jun 14, 2023 |
| PC Special... | P65_P67RGRERA               | [49773a4767](https://linux-hardware.org/?probe=49773a4767) | Jun 14, 2023 |
| ASUSTek       | N73SV                       | [b3b70ef13b](https://linux-hardware.org/?probe=b3b70ef13b) | Jun 14, 2023 |
| Toshiba       | PORTEGE X30-D               | [9f26d41d53](https://linux-hardware.org/?probe=9f26d41d53) | Jun 14, 2023 |
| Samsung       | 670Z5E                      | [20f84530c7](https://linux-hardware.org/?probe=20f84530c7) | Jun 14, 2023 |
| Acer          | Nitro AN517-54              | [d0187875be](https://linux-hardware.org/?probe=d0187875be) | Jun 13, 2023 |
| Dell          | Vostro 3420                 | [1ede32fb28](https://linux-hardware.org/?probe=1ede32fb28) | Jun 13, 2023 |
| Dell          | Inspiron 13-7359            | [3ddafcad45](https://linux-hardware.org/?probe=3ddafcad45) | Jun 13, 2023 |
| Alienware     | m15 R7                      | [c4a2634a83](https://linux-hardware.org/?probe=c4a2634a83) | Jun 13, 2023 |
| Alienware     | m15 R7                      | [7b53840b8b](https://linux-hardware.org/?probe=7b53840b8b) | Jun 13, 2023 |
| Apple         | MacBookPro5,5               | [b303846ade](https://linux-hardware.org/?probe=b303846ade) | Jun 13, 2023 |
| Toshiba       | Satellite P755              | [3b0c830987](https://linux-hardware.org/?probe=3b0c830987) | Jun 13, 2023 |
| Dell          | Latitude E7250              | [cc9fc2bace](https://linux-hardware.org/?probe=cc9fc2bace) | Jun 13, 2023 |
| Dell          | 500                         | [b220c5553e](https://linux-hardware.org/?probe=b220c5553e) | Jun 12, 2023 |
| MSI           | Stealth 15M B12UE           | [aabb8192ee](https://linux-hardware.org/?probe=aabb8192ee) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | [b31d9c8e55](https://linux-hardware.org/?probe=b31d9c8e55) | Jun 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | [235239b42b](https://linux-hardware.org/?probe=235239b42b) | Jun 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [d2c4574d58](https://linux-hardware.org/?probe=d2c4574d58) | Jun 11, 2023 |
| ASUSTek       | G750JM                      | [da1f33a87b](https://linux-hardware.org/?probe=da1f33a87b) | Jun 11, 2023 |
| Dell          | Latitude 7480               | [03b8f5a162](https://linux-hardware.org/?probe=03b8f5a162) | Jun 11, 2023 |
| Dell          | Precision 5570              | [32975fdf08](https://linux-hardware.org/?probe=32975fdf08) | Jun 11, 2023 |
| ASUSTek       | GX501VIK                    | [e54a895262](https://linux-hardware.org/?probe=e54a895262) | Jun 11, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | [3d3375df75](https://linux-hardware.org/?probe=3d3375df75) | Jun 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [65a47406b0](https://linux-hardware.org/?probe=65a47406b0) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0XV0... | [b2f7d876c7](https://linux-hardware.org/?probe=b2f7d876c7) | Jun 10, 2023 |
| MSI           | Prestige 13Evo A13M         | [3feb3bce01](https://linux-hardware.org/?probe=3feb3bce01) | Jun 10, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [4b6aa9a912](https://linux-hardware.org/?probe=4b6aa9a912) | Jun 10, 2023 |
| Dell          | Latitude E5500              | [41ad12c465](https://linux-hardware.org/?probe=41ad12c465) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [246facab73](https://linux-hardware.org/?probe=246facab73) | Jun 10, 2023 |
| Sony          | VPCF120FD                   | [47f02bd498](https://linux-hardware.org/?probe=47f02bd498) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [233dac6c68](https://linux-hardware.org/?probe=233dac6c68) | Jun 09, 2023 |
| Dell          | XPS 9320                    | [c9f26e18c2](https://linux-hardware.org/?probe=c9f26e18c2) | Jun 09, 2023 |
| Dell          | Inspiron 15-5568            | [19b686b7d7](https://linux-hardware.org/?probe=19b686b7d7) | Jun 09, 2023 |
| HP            | Laptop 15s-fq2xxx           | [09ba95bf3b](https://linux-hardware.org/?probe=09ba95bf3b) | Jun 08, 2023 |
| ASUSTek       | X455LA                      | [583596672d](https://linux-hardware.org/?probe=583596672d) | Jun 08, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [8fa2e2acc9](https://linux-hardware.org/?probe=8fa2e2acc9) | Jun 08, 2023 |
| Dell          | Inspiron 5379               | [b161b2177a](https://linux-hardware.org/?probe=b161b2177a) | Jun 08, 2023 |
| Gigabyte      | P2542                       | [12a2415432](https://linux-hardware.org/?probe=12a2415432) | Jun 08, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ea8584cbda](https://linux-hardware.org/?probe=ea8584cbda) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | [76ca69b8cc](https://linux-hardware.org/?probe=76ca69b8cc) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | [3932ac5190](https://linux-hardware.org/?probe=3932ac5190) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | [ff2ebbb0ae](https://linux-hardware.org/?probe=ff2ebbb0ae) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [265c19be27](https://linux-hardware.org/?probe=265c19be27) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [b0435761df](https://linux-hardware.org/?probe=b0435761df) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [a76212cc40](https://linux-hardware.org/?probe=a76212cc40) | Jun 07, 2023 |
| HP            | Laptop 15s-fq2xxx           | [9d0aa12b81](https://linux-hardware.org/?probe=9d0aa12b81) | Jun 06, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e56988bf8e](https://linux-hardware.org/?probe=e56988bf8e) | Jun 06, 2023 |
| Dell          | Latitude 7480               | [61c800a3b4](https://linux-hardware.org/?probe=61c800a3b4) | Jun 06, 2023 |
| Notebook      | P65xHP                      | [bf35e218d7](https://linux-hardware.org/?probe=bf35e218d7) | Jun 06, 2023 |
| Toshiba       | PORTEGE X30-D               | [262ee566e1](https://linux-hardware.org/?probe=262ee566e1) | Jun 06, 2023 |
| HP            | EliteBook 840 G6            | [0763f751ac](https://linux-hardware.org/?probe=0763f751ac) | Jun 05, 2023 |
| Notebook      | P65xHP                      | [51834b893c](https://linux-hardware.org/?probe=51834b893c) | Jun 05, 2023 |
| Toshiba       | Satellite Pro C70-B         | [d4bc6d6c8c](https://linux-hardware.org/?probe=d4bc6d6c8c) | Jun 04, 2023 |
| Sony          | VPCEH2H4E                   | [793e883d0c](https://linux-hardware.org/?probe=793e883d0c) | Jun 04, 2023 |
| Dell          | Inspiron 3442               | [5c1f2cc0d3](https://linux-hardware.org/?probe=5c1f2cc0d3) | Jun 04, 2023 |
| Acer          | Swift SF314-43              | [969354604a](https://linux-hardware.org/?probe=969354604a) | Jun 04, 2023 |
| Dell          | Latitude E5520              | [7e2d1fdd22](https://linux-hardware.org/?probe=7e2d1fdd22) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | [f39742476c](https://linux-hardware.org/?probe=f39742476c) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | [efa49bf468](https://linux-hardware.org/?probe=efa49bf468) | Jun 04, 2023 |
| Dell          | Latitude E5510              | [353a2174af](https://linux-hardware.org/?probe=353a2174af) | Jun 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [6d8d7f6384](https://linux-hardware.org/?probe=6d8d7f6384) | Jun 04, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [4f62d33d84](https://linux-hardware.org/?probe=4f62d33d84) | Jun 04, 2023 |
| ASUSTek       | K52Je                       | [0190eef08c](https://linux-hardware.org/?probe=0190eef08c) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [069b512b91](https://linux-hardware.org/?probe=069b512b91) | Jun 03, 2023 |
| Lenovo        | ThinkPad T420 4236WQD       | [69a63f31e1](https://linux-hardware.org/?probe=69a63f31e1) | Jun 03, 2023 |
| HP            | ENVY 17                     | [79fd438f05](https://linux-hardware.org/?probe=79fd438f05) | Jun 03, 2023 |
| Dell          | Latitude 5491               | [6a8a7e6188](https://linux-hardware.org/?probe=6a8a7e6188) | Jun 03, 2023 |
| Acer          | Aspire 7750G                | [160d4525c6](https://linux-hardware.org/?probe=160d4525c6) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [fa4bd41f4b](https://linux-hardware.org/?probe=fa4bd41f4b) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [959b76650d](https://linux-hardware.org/?probe=959b76650d) | Jun 02, 2023 |
| Acer          | Aspire ES1-523              | [a080a07f52](https://linux-hardware.org/?probe=a080a07f52) | Jun 02, 2023 |
| Acer          | Aspire 7750G                | [e94cab5008](https://linux-hardware.org/?probe=e94cab5008) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1aea71b6c0](https://linux-hardware.org/?probe=1aea71b6c0) | Jun 02, 2023 |
| Unknown       | Unknown                     | [655398fc94](https://linux-hardware.org/?probe=655398fc94) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1bdb74a8ba](https://linux-hardware.org/?probe=1bdb74a8ba) | Jun 02, 2023 |
| HP            | ProBook 6450b               | [d3d4e45f9d](https://linux-hardware.org/?probe=d3d4e45f9d) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [f66667b7fb](https://linux-hardware.org/?probe=f66667b7fb) | Jun 01, 2023 |
| Dell          | XPS 15 9570                 | [6d7803788d](https://linux-hardware.org/?probe=6d7803788d) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | [8a69d6c123](https://linux-hardware.org/?probe=8a69d6c123) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | [ecfe7565f4](https://linux-hardware.org/?probe=ecfe7565f4) | Jun 01, 2023 |
| HP            | EliteBook 2560p             | [e822eb4072](https://linux-hardware.org/?probe=e822eb4072) | Jun 01, 2023 |
| ASUSTek       | K53SK                       | [9b376cdd45](https://linux-hardware.org/?probe=9b376cdd45) | Jun 01, 2023 |
| HP            | Pavilion Notebook           | [3fb05bfb0b](https://linux-hardware.org/?probe=3fb05bfb0b) | May 31, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [560680687c](https://linux-hardware.org/?probe=560680687c) | May 31, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | [239faf8c55](https://linux-hardware.org/?probe=239faf8c55) | May 31, 2023 |
| HONOR         | BBR-WAX9                    | [8630cfad52](https://linux-hardware.org/?probe=8630cfad52) | May 31, 2023 |
| Acer          | Nitro AN515-54              | [7c031081c5](https://linux-hardware.org/?probe=7c031081c5) | May 31, 2023 |
| Acer          | Swift SF314-512             | [a8c97baf10](https://linux-hardware.org/?probe=a8c97baf10) | May 31, 2023 |
| ASUSTek       | ROG Strix G513RS_G513RS     | [69b1782cce](https://linux-hardware.org/?probe=69b1782cce) | May 31, 2023 |
| ASUSTek       | K53SK                       | [bfd926c8da](https://linux-hardware.org/?probe=bfd926c8da) | May 30, 2023 |
| VALE          | Notebook Classic C140       | [cdc6168586](https://linux-hardware.org/?probe=cdc6168586) | May 30, 2023 |
| Gigabyte      | P2542                       | [b1064cae7a](https://linux-hardware.org/?probe=b1064cae7a) | May 30, 2023 |
| Dell          | Inspiron 15-3567            | [e51e0ef0da](https://linux-hardware.org/?probe=e51e0ef0da) | May 30, 2023 |
| Gigabyte      | P2542                       | [7cded000f2](https://linux-hardware.org/?probe=7cded000f2) | May 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [8002face48](https://linux-hardware.org/?probe=8002face48) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cddd43859b](https://linux-hardware.org/?probe=cddd43859b) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [46f455ce35](https://linux-hardware.org/?probe=46f455ce35) | May 30, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [1e0fbe86da](https://linux-hardware.org/?probe=1e0fbe86da) | May 29, 2023 |
| Alienware     | x15 R1                      | [19e9b8e338](https://linux-hardware.org/?probe=19e9b8e338) | May 29, 2023 |
| HONOR         | BBR-WAX9                    | [e57b9850f8](https://linux-hardware.org/?probe=e57b9850f8) | May 28, 2023 |
| ALLDOCUBE     | i1405C                      | [7e4475ef13](https://linux-hardware.org/?probe=7e4475ef13) | May 28, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c2408a1885](https://linux-hardware.org/?probe=c2408a1885) | May 28, 2023 |
| Apple         | MacBookPro10,2              | [34d96aa1df](https://linux-hardware.org/?probe=34d96aa1df) | May 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [c7afdbbd76](https://linux-hardware.org/?probe=c7afdbbd76) | May 28, 2023 |
| AVITA         | NE14A2                      | [89c5edafbc](https://linux-hardware.org/?probe=89c5edafbc) | May 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | [618a907425](https://linux-hardware.org/?probe=618a907425) | May 27, 2023 |
| Dell          | Vostro 15 3515              | [2fadb86df4](https://linux-hardware.org/?probe=2fadb86df4) | May 27, 2023 |
| Dell          | Latitude 5440               | [9ed4f0e7ac](https://linux-hardware.org/?probe=9ed4f0e7ac) | May 27, 2023 |
| Dell          | Latitude 5480               | [c7566d1ab9](https://linux-hardware.org/?probe=c7566d1ab9) | May 27, 2023 |
| Dell          | Latitude 5480               | [5327e82af6](https://linux-hardware.org/?probe=5327e82af6) | May 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [57b9304725](https://linux-hardware.org/?probe=57b9304725) | May 27, 2023 |
| Acer          | Aspire A315-22              | [18a13174aa](https://linux-hardware.org/?probe=18a13174aa) | May 27, 2023 |
| Dell          | Latitude 7480               | [2c74ec8198](https://linux-hardware.org/?probe=2c74ec8198) | May 27, 2023 |
| Toshiba       | Satellite Pro C70-B         | [3058a75499](https://linux-hardware.org/?probe=3058a75499) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [433b367e58](https://linux-hardware.org/?probe=433b367e58) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [ac85063e46](https://linux-hardware.org/?probe=ac85063e46) | May 26, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [b8bb801b93](https://linux-hardware.org/?probe=b8bb801b93) | May 26, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [a8c4cf6158](https://linux-hardware.org/?probe=a8c4cf6158) | May 26, 2023 |
| Acer          | Predator PT316-51s          | [0242988287](https://linux-hardware.org/?probe=0242988287) | May 26, 2023 |
| HP            | ENVY Laptop 13-ah0503na     | [cdf2d7b4b4](https://linux-hardware.org/?probe=cdf2d7b4b4) | May 25, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [0316f8d274](https://linux-hardware.org/?probe=0316f8d274) | May 25, 2023 |
| Lenovo        | ThinkPad T580 20LAS62M07    | [48ad025649](https://linux-hardware.org/?probe=48ad025649) | May 25, 2023 |
| Google        | Akali 360                   | [2a4bbc5d81](https://linux-hardware.org/?probe=2a4bbc5d81) | May 25, 2023 |
| Acer          | Aspire A715-51G             | [53cbfa6255](https://linux-hardware.org/?probe=53cbfa6255) | May 25, 2023 |
| Toshiba       | Satellite Pro C650          | [50fc04b16c](https://linux-hardware.org/?probe=50fc04b16c) | May 25, 2023 |
| Mediacom      | SMARTBOOK ONE               | [ad010a6b3e](https://linux-hardware.org/?probe=ad010a6b3e) | May 25, 2023 |
| HP            | ZBook Studio G3             | [a7274d19af](https://linux-hardware.org/?probe=a7274d19af) | May 24, 2023 |
| Dell          | Latitude 7390               | [999bb94a31](https://linux-hardware.org/?probe=999bb94a31) | May 24, 2023 |
| HUAWEI        | BOD-WXX9                    | [9486b7ca4f](https://linux-hardware.org/?probe=9486b7ca4f) | May 24, 2023 |
| HP            | Laptop 15s-fq4xxx           | [810c2ac411](https://linux-hardware.org/?probe=810c2ac411) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [4c512786cc](https://linux-hardware.org/?probe=4c512786cc) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [da0b980bc3](https://linux-hardware.org/?probe=da0b980bc3) | May 24, 2023 |
| Allview       | Allbook H                   | [8b0c0a3436](https://linux-hardware.org/?probe=8b0c0a3436) | May 24, 2023 |
| Dell          | Precision 3571              | [3806fcdb9c](https://linux-hardware.org/?probe=3806fcdb9c) | May 24, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | [306ecade71](https://linux-hardware.org/?probe=306ecade71) | May 24, 2023 |
| Dell          | Inspiron 5720               | [c9eaabeb95](https://linux-hardware.org/?probe=c9eaabeb95) | May 24, 2023 |
| HP            | Pavilion dv5                | [2906e3ff3b](https://linux-hardware.org/?probe=2906e3ff3b) | May 24, 2023 |
| HP            | 15                          | [b62229cac1](https://linux-hardware.org/?probe=b62229cac1) | May 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | [4c3c861f80](https://linux-hardware.org/?probe=4c3c861f80) | May 23, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [77f092da32](https://linux-hardware.org/?probe=77f092da32) | May 23, 2023 |
| Dell          | Inspiron 1525               | [a92437f5aa](https://linux-hardware.org/?probe=a92437f5aa) | May 23, 2023 |
| ASUSTek       | X751MA                      | [674b64f381](https://linux-hardware.org/?probe=674b64f381) | May 23, 2023 |
| HP            | Laptop 14s-fq1xxx           | [73d0ff64b6](https://linux-hardware.org/?probe=73d0ff64b6) | May 23, 2023 |
| Acer          | Aspire E5-553               | [3740264eb0](https://linux-hardware.org/?probe=3740264eb0) | May 23, 2023 |
| HP            | 250 G6 Notebook PC          | [431f2db1fc](https://linux-hardware.org/?probe=431f2db1fc) | May 23, 2023 |
| HP            | Laptop 14-dq2xxx            | [fe7d1e1f90](https://linux-hardware.org/?probe=fe7d1e1f90) | May 22, 2023 |
| Dell          | Inspiron 1525               | [2afda2396c](https://linux-hardware.org/?probe=2afda2396c) | May 22, 2023 |
| Acer          | Nitro AN515-46              | [702a597b36](https://linux-hardware.org/?probe=702a597b36) | May 22, 2023 |
| Acer          | Swift SF514-56T             | [81a0e002b7](https://linux-hardware.org/?probe=81a0e002b7) | May 22, 2023 |
| Dell          | Latitude 3420               | [d598f2634f](https://linux-hardware.org/?probe=d598f2634f) | May 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS1GQ00    | [1ea9bac322](https://linux-hardware.org/?probe=1ea9bac322) | May 22, 2023 |
| MSI           | Stealth 15M B12UE           | [4051f4b27d](https://linux-hardware.org/?probe=4051f4b27d) | May 22, 2023 |
| HUAWEI        | NBM-WXX9                    | [e3ea42dd02](https://linux-hardware.org/?probe=e3ea42dd02) | May 22, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [55a289b426](https://linux-hardware.org/?probe=55a289b426) | May 21, 2023 |
| Apple         | MacBookPro14,2              | [d29f7a36f9](https://linux-hardware.org/?probe=d29f7a36f9) | May 21, 2023 |
| Dell          | Latitude E6530              | [7c04efc558](https://linux-hardware.org/?probe=7c04efc558) | May 21, 2023 |
| Dell          | Inspiron 3542               | [166b73ef05](https://linux-hardware.org/?probe=166b73ef05) | May 20, 2023 |
| HP            | Pavilion dv6                | [17ac43247a](https://linux-hardware.org/?probe=17ac43247a) | May 20, 2023 |
| Unknown       | Unknown                     | [c7157cc723](https://linux-hardware.org/?probe=c7157cc723) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [de162ff16c](https://linux-hardware.org/?probe=de162ff16c) | May 20, 2023 |
| Acer          | Nitro AN517-54              | [105fb43fc1](https://linux-hardware.org/?probe=105fb43fc1) | May 20, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [42ab4c7e67](https://linux-hardware.org/?probe=42ab4c7e67) | May 20, 2023 |
| MSI           | VR601                       | [7f9381407d](https://linux-hardware.org/?probe=7f9381407d) | May 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5bac34a5f5](https://linux-hardware.org/?probe=5bac34a5f5) | May 19, 2023 |
| Dell          | Inspiron 3442               | [a8bb37c78e](https://linux-hardware.org/?probe=a8bb37c78e) | May 19, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [9475bc847b](https://linux-hardware.org/?probe=9475bc847b) | May 19, 2023 |
| HP            | Pavilion dv6                | [4fb1281981](https://linux-hardware.org/?probe=4fb1281981) | May 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [7af74c5864](https://linux-hardware.org/?probe=7af74c5864) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [161776168b](https://linux-hardware.org/?probe=161776168b) | May 18, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [e17fc662cc](https://linux-hardware.org/?probe=e17fc662cc) | May 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [b5d454d4ec](https://linux-hardware.org/?probe=b5d454d4ec) | May 18, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | [d1569df0f6](https://linux-hardware.org/?probe=d1569df0f6) | May 18, 2023 |
| HP            | Laptop 14-dq0xxx            | [1923d74fbc](https://linux-hardware.org/?probe=1923d74fbc) | May 18, 2023 |
| Dell          | Precision 5570              | [c9e52e6e8c](https://linux-hardware.org/?probe=c9e52e6e8c) | May 18, 2023 |
| MSI           | GF63 Thin 11SC              | [89e05e4477](https://linux-hardware.org/?probe=89e05e4477) | May 17, 2023 |
| Dell          | Latitude E6530              | [e6064ac95c](https://linux-hardware.org/?probe=e6064ac95c) | May 17, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | [58b895e713](https://linux-hardware.org/?probe=58b895e713) | May 16, 2023 |
| Toshiba       | IS 1413G                    | [df01be5efd](https://linux-hardware.org/?probe=df01be5efd) | May 16, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ba609eb1e6](https://linux-hardware.org/?probe=ba609eb1e6) | May 15, 2023 |
| VALE          | Notebook Classic C140       | [656e811dfb](https://linux-hardware.org/?probe=656e811dfb) | May 14, 2023 |
| Acer          | Aspire A717-72G             | [1ab0673015](https://linux-hardware.org/?probe=1ab0673015) | May 14, 2023 |
| Acer          | Aspire A717-72G             | [62a46acc18](https://linux-hardware.org/?probe=62a46acc18) | May 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [b08b887e1a](https://linux-hardware.org/?probe=b08b887e1a) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [020d4612bd](https://linux-hardware.org/?probe=020d4612bd) | May 14, 2023 |
| HP            | Notebook                    | [decd46d3ed](https://linux-hardware.org/?probe=decd46d3ed) | May 14, 2023 |
| HP            | Laptop 14-dq2xxx            | [274fbdb43e](https://linux-hardware.org/?probe=274fbdb43e) | May 14, 2023 |
| Toshiba       | IS 1413G                    | [821d79dc3f](https://linux-hardware.org/?probe=821d79dc3f) | May 14, 2023 |
| MSI           | GS75 Stealth 10SFS          | [a2116b61ea](https://linux-hardware.org/?probe=a2116b61ea) | May 14, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [803f9dba3c](https://linux-hardware.org/?probe=803f9dba3c) | May 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [09eb36df64](https://linux-hardware.org/?probe=09eb36df64) | May 13, 2023 |
| Dell          | Inspiron 7520               | [d06731c12e](https://linux-hardware.org/?probe=d06731c12e) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5768cd981e](https://linux-hardware.org/?probe=5768cd981e) | May 13, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [66bff684b7](https://linux-hardware.org/?probe=66bff684b7) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | [14eae60f4f](https://linux-hardware.org/?probe=14eae60f4f) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | [7ac717a41d](https://linux-hardware.org/?probe=7ac717a41d) | May 13, 2023 |
| Samsung       | 960XFH                      | [6d6b4a9c5e](https://linux-hardware.org/?probe=6d6b4a9c5e) | May 12, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | [795e44d159](https://linux-hardware.org/?probe=795e44d159) | May 12, 2023 |
| ASUSTek       | X555LJ                      | [f39ba53533](https://linux-hardware.org/?probe=f39ba53533) | May 12, 2023 |
| HP            | Stream Notebook             | [5ed3be74da](https://linux-hardware.org/?probe=5ed3be74da) | May 12, 2023 |
| Apple         | MacBookPro11,2              | [ceea346358](https://linux-hardware.org/?probe=ceea346358) | May 12, 2023 |
| Apple         | MacBookPro11,4              | [576d66cba7](https://linux-hardware.org/?probe=576d66cba7) | May 12, 2023 |
| Unknown       | Unknown                     | [8375f52559](https://linux-hardware.org/?probe=8375f52559) | May 12, 2023 |
| HP            | EliteBook 840 G6            | [80158c51fb](https://linux-hardware.org/?probe=80158c51fb) | May 12, 2023 |
| Dell          | Vostro 3500                 | [81f86e6678](https://linux-hardware.org/?probe=81f86e6678) | May 11, 2023 |
| Rombica       | myBook Zenith               | [f7438f1448](https://linux-hardware.org/?probe=f7438f1448) | May 11, 2023 |
| Apple         | MacBookPro9,2               | [ecb43775d1](https://linux-hardware.org/?probe=ecb43775d1) | May 11, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [f9c1eb381f](https://linux-hardware.org/?probe=f9c1eb381f) | May 11, 2023 |
| Unknown       | Unknown                     | [3fbabd3df0](https://linux-hardware.org/?probe=3fbabd3df0) | May 11, 2023 |
| Dell          | Latitude 5490               | [2cba18ddec](https://linux-hardware.org/?probe=2cba18ddec) | May 11, 2023 |
| Lenovo        | Yoga 7 14IRL8 82YL          | [ae2fd3b0ae](https://linux-hardware.org/?probe=ae2fd3b0ae) | May 11, 2023 |
| MSI           | Stealth 14Studio A13VE      | [86f43bbff1](https://linux-hardware.org/?probe=86f43bbff1) | May 10, 2023 |
| Acer          | Aspire 3935                 | [39cbd19b39](https://linux-hardware.org/?probe=39cbd19b39) | May 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [2e58ce6bd7](https://linux-hardware.org/?probe=2e58ce6bd7) | May 10, 2023 |
| Unknown       | Unknown                     | [87e3ae6f24](https://linux-hardware.org/?probe=87e3ae6f24) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [727163d7b9](https://linux-hardware.org/?probe=727163d7b9) | May 09, 2023 |
| Dell          | XPS 13 9380                 | [af31929040](https://linux-hardware.org/?probe=af31929040) | May 09, 2023 |
| Medion        | E6234                       | [6c3bd7d77f](https://linux-hardware.org/?probe=6c3bd7d77f) | May 08, 2023 |
| Toshiba       | Satellite L650              | [ba32d27df1](https://linux-hardware.org/?probe=ba32d27df1) | May 08, 2023 |
| HP            | 625                         | [956346de67](https://linux-hardware.org/?probe=956346de67) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0628913a60](https://linux-hardware.org/?probe=0628913a60) | May 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | [db609197b4](https://linux-hardware.org/?probe=db609197b4) | May 08, 2023 |
| Acer          | Swift SFA16-41              | [7934eebd9b](https://linux-hardware.org/?probe=7934eebd9b) | May 08, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f23fb5cca0](https://linux-hardware.org/?probe=f23fb5cca0) | May 08, 2023 |
| HP            | Meep                        | [4b99a0c5f8](https://linux-hardware.org/?probe=4b99a0c5f8) | May 08, 2023 |
| Apple         | MacBookPro9,2               | [a8d45ac430](https://linux-hardware.org/?probe=a8d45ac430) | May 07, 2023 |
| Toshiba       | IS 1413G                    | [c437a16a33](https://linux-hardware.org/?probe=c437a16a33) | May 07, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [a312f0545f](https://linux-hardware.org/?probe=a312f0545f) | May 07, 2023 |
| HP            | EliteBook 850 G3            | [9a068c66d5](https://linux-hardware.org/?probe=9a068c66d5) | May 07, 2023 |
| Medion        | E6234                       | [5afe99ed93](https://linux-hardware.org/?probe=5afe99ed93) | May 07, 2023 |
| HP            | Meep                        | [46a81f105c](https://linux-hardware.org/?probe=46a81f105c) | May 07, 2023 |
| Dell          | XPS 13 9380                 | [b4e9bb9147](https://linux-hardware.org/?probe=b4e9bb9147) | May 07, 2023 |
| ASUSTek       | X555LJ                      | [febe8d60fc](https://linux-hardware.org/?probe=febe8d60fc) | May 07, 2023 |
| ASUSTek       | X555LJ                      | [2e25cad4b3](https://linux-hardware.org/?probe=2e25cad4b3) | May 07, 2023 |
| Razer         | Blade                       | [d90bda8f52](https://linux-hardware.org/?probe=d90bda8f52) | May 07, 2023 |
| Dell          | Latitude 5290               | [255da608b8](https://linux-hardware.org/?probe=255da608b8) | May 07, 2023 |
| Dell          | XPS 13 9343                 | [5e91733408](https://linux-hardware.org/?probe=5e91733408) | May 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [9355511511](https://linux-hardware.org/?probe=9355511511) | May 07, 2023 |
| Dell          | Inspiron 5521               | [d5f70fc2eb](https://linux-hardware.org/?probe=d5f70fc2eb) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [50b503ae3e](https://linux-hardware.org/?probe=50b503ae3e) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [64bbfa416b](https://linux-hardware.org/?probe=64bbfa416b) | May 07, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [abc9ce4fa4](https://linux-hardware.org/?probe=abc9ce4fa4) | May 06, 2023 |
| Dell          | Latitude E6410              | [535fd92f64](https://linux-hardware.org/?probe=535fd92f64) | May 06, 2023 |
| Dell          | Latitude E4200              | [af2baa1787](https://linux-hardware.org/?probe=af2baa1787) | May 06, 2023 |
| Acer          | Aspire 5810T                | [d4b401ef3f](https://linux-hardware.org/?probe=d4b401ef3f) | May 06, 2023 |
| Dell          | Vostro 3360                 | [13a1e30b53](https://linux-hardware.org/?probe=13a1e30b53) | May 06, 2023 |
| Dell          | Precision 7740              | [4cd3b0701e](https://linux-hardware.org/?probe=4cd3b0701e) | May 06, 2023 |
| Acer          | Aspire 5810T                | [ecdd99c704](https://linux-hardware.org/?probe=ecdd99c704) | May 05, 2023 |
| HP            | Pavilion g6                 | [9e469df99e](https://linux-hardware.org/?probe=9e469df99e) | May 05, 2023 |
| Toshiba       | PORTEGE Z30t-A              | [18cc14eee0](https://linux-hardware.org/?probe=18cc14eee0) | May 05, 2023 |
| Shanghai Z... | ZXE CRB                     | [d63ef842c1](https://linux-hardware.org/?probe=d63ef842c1) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b9cfd37540](https://linux-hardware.org/?probe=b9cfd37540) | May 05, 2023 |
| Google        | Meep                        | [1e5e0e6673](https://linux-hardware.org/?probe=1e5e0e6673) | May 04, 2023 |
| Dell          | XPS 13 9300                 | [8864ce10e7](https://linux-hardware.org/?probe=8864ce10e7) | May 03, 2023 |
| Dell          | XPS 13 9300                 | [8ef1ddf82a](https://linux-hardware.org/?probe=8ef1ddf82a) | May 03, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | [bb924b0c19](https://linux-hardware.org/?probe=bb924b0c19) | May 03, 2023 |
| MSI           | Katana GF66 12UE            | [799a951714](https://linux-hardware.org/?probe=799a951714) | May 03, 2023 |
| Lenovo        | G500s 20245                 | [560b69d616](https://linux-hardware.org/?probe=560b69d616) | May 03, 2023 |
| Toshiba       | IS 1413G                    | [81a4d2ac8b](https://linux-hardware.org/?probe=81a4d2ac8b) | May 03, 2023 |
| Acer          | Aspire E1-571               | [46ecc78df6](https://linux-hardware.org/?probe=46ecc78df6) | May 02, 2023 |
| HP            | EliteBook Folio G1          | [a31ef5e00e](https://linux-hardware.org/?probe=a31ef5e00e) | May 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5101f4e19d](https://linux-hardware.org/?probe=5101f4e19d) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [000c0450b9](https://linux-hardware.org/?probe=000c0450b9) | May 02, 2023 |
| HP            | Notebook                    | [749fa6a38e](https://linux-hardware.org/?probe=749fa6a38e) | May 02, 2023 |
| Acer          | Nitro AN515-44              | [e26aee893f](https://linux-hardware.org/?probe=e26aee893f) | May 01, 2023 |
| HUAWEI        | BOHB-WAX9                   | [3a9a2590e3](https://linux-hardware.org/?probe=3a9a2590e3) | May 01, 2023 |
| HP            | ProBook 430 G4              | [3c422c5e96](https://linux-hardware.org/?probe=3c422c5e96) | May 01, 2023 |
| Acer          | Aspire E1-571               | [7b4e78233a](https://linux-hardware.org/?probe=7b4e78233a) | May 01, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3be920565f](https://linux-hardware.org/?probe=3be920565f) | May 01, 2023 |
| Medion        | E16402                      | [cff2f785ad](https://linux-hardware.org/?probe=cff2f785ad) | May 01, 2023 |
| Dell          | Latitude E6400              | [33b7764234](https://linux-hardware.org/?probe=33b7764234) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5002NAU    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| HP            | EliteBook 840 G3            | [c490c44357](https://linux-hardware.org/?probe=c490c44357) | May 01, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [4bec088d90](https://linux-hardware.org/?probe=4bec088d90) | Apr 30, 2023 |
| Dell          | XPS 15 9500                 | [93fef964a7](https://linux-hardware.org/?probe=93fef964a7) | Apr 30, 2023 |
| Samsung       | 950XED                      | [41f620de17](https://linux-hardware.org/?probe=41f620de17) | Apr 30, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [1714bffa0e](https://linux-hardware.org/?probe=1714bffa0e) | Apr 30, 2023 |
| Acer          | Peppy                       | [4caf11594a](https://linux-hardware.org/?probe=4caf11594a) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [da5f050510](https://linux-hardware.org/?probe=da5f050510) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [1e65b46a12](https://linux-hardware.org/?probe=1e65b46a12) | Apr 29, 2023 |
| ASUSTek       | X751MA                      | [c952010dbb](https://linux-hardware.org/?probe=c952010dbb) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | [6a102a2c37](https://linux-hardware.org/?probe=6a102a2c37) | Apr 29, 2023 |
| Dell          | Inspiron N5110              | [04da6f1db9](https://linux-hardware.org/?probe=04da6f1db9) | Apr 29, 2023 |
| MSI           | Modern 14 A10M              | [22ad1f6bfb](https://linux-hardware.org/?probe=22ad1f6bfb) | Apr 29, 2023 |
| Acer          | Aspire E5-553               | [ff448e32c3](https://linux-hardware.org/?probe=ff448e32c3) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| Samsung       | 930X2K/931X2K               | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | [004e0007e4](https://linux-hardware.org/?probe=004e0007e4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | [3f6a89023c](https://linux-hardware.org/?probe=3f6a89023c) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [216a4b9b67](https://linux-hardware.org/?probe=216a4b9b67) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [6736f3d911](https://linux-hardware.org/?probe=6736f3d911) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [a808e47839](https://linux-hardware.org/?probe=a808e47839) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [67ae1efc54](https://linux-hardware.org/?probe=67ae1efc54) | Apr 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | [b1e6130b77](https://linux-hardware.org/?probe=b1e6130b77) | Apr 28, 2023 |
| Acer          | Swift SF314-512             | [2ba1bab0fe](https://linux-hardware.org/?probe=2ba1bab0fe) | Apr 28, 2023 |
| MSI           | Katana GF66 12UGS           | [3607ee704e](https://linux-hardware.org/?probe=3607ee704e) | Apr 28, 2023 |
| Dell          | XPS 15 9570                 | [3479673283](https://linux-hardware.org/?probe=3479673283) | Apr 28, 2023 |
| Acer          | ConceptD CN315-71P          | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Dell          | Latitude E5470              | [caac023f65](https://linux-hardware.org/?probe=caac023f65) | Apr 27, 2023 |
| Valve         | Jupiter                     | [f65ece2859](https://linux-hardware.org/?probe=f65ece2859) | Apr 27, 2023 |
| ASUSTek       | X751MA                      | [eb9967626a](https://linux-hardware.org/?probe=eb9967626a) | Apr 27, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [404ec697ac](https://linux-hardware.org/?probe=404ec697ac) | Apr 27, 2023 |
| Dell          | Inspiron 5567               | [012329ee1f](https://linux-hardware.org/?probe=012329ee1f) | Apr 27, 2023 |
| MSI           | PE60 6QE                    | [1a5ae975ee](https://linux-hardware.org/?probe=1a5ae975ee) | Apr 27, 2023 |
| Acer          | Aspire 5742G                | [a1391b4372](https://linux-hardware.org/?probe=a1391b4372) | Apr 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [f0a2365878](https://linux-hardware.org/?probe=f0a2365878) | Apr 27, 2023 |
| Dell          | Inspiron 5558               | [9f3b8c952d](https://linux-hardware.org/?probe=9f3b8c952d) | Apr 27, 2023 |
| Acer          | Aspire E1-571               | [c95605ef8e](https://linux-hardware.org/?probe=c95605ef8e) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [d49ace71b4](https://linux-hardware.org/?probe=d49ace71b4) | Apr 27, 2023 |
| Dell          | Latitude 5520               | [bec614b168](https://linux-hardware.org/?probe=bec614b168) | Apr 26, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [7ca1ebbe7f](https://linux-hardware.org/?probe=7ca1ebbe7f) | Apr 26, 2023 |
| Dell          | Latitude 7420               | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| ASUSTek       | X541SA                      | [362ede5435](https://linux-hardware.org/?probe=362ede5435) | Apr 26, 2023 |
| Acer          | Swift SF313-53              | [b487229ea2](https://linux-hardware.org/?probe=b487229ea2) | Apr 25, 2023 |
| MSI           | Modern 14 A10M              | [dc3595e3cc](https://linux-hardware.org/?probe=dc3595e3cc) | Apr 25, 2023 |
| HP            | 240 G8                      | [ab322ed08e](https://linux-hardware.org/?probe=ab322ed08e) | Apr 25, 2023 |
| HP            | 240 G8                      | [8cf9892fe9](https://linux-hardware.org/?probe=8cf9892fe9) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e7b20d71b7](https://linux-hardware.org/?probe=e7b20d71b7) | Apr 25, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [2732f4b096](https://linux-hardware.org/?probe=2732f4b096) | Apr 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [7d3b6ba1a3](https://linux-hardware.org/?probe=7d3b6ba1a3) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [5fb905227b](https://linux-hardware.org/?probe=5fb905227b) | Apr 25, 2023 |
| Dell          | XPS 13 9310                 | [65ccee11a0](https://linux-hardware.org/?probe=65ccee11a0) | Apr 24, 2023 |
| ICL           | RAYbook Si1512              | [4e960cbe90](https://linux-hardware.org/?probe=4e960cbe90) | Apr 24, 2023 |
| ASUSTek       | GL752VW                     | [26c754e5f0](https://linux-hardware.org/?probe=26c754e5f0) | Apr 24, 2023 |
| Dell          | XPS 13 9310                 | [070d7e791f](https://linux-hardware.org/?probe=070d7e791f) | Apr 24, 2023 |
| Acer          | Aspire 5742G                | [84679bc442](https://linux-hardware.org/?probe=84679bc442) | Apr 24, 2023 |
| Lenovo        | ThinkPad A285 20MXS0NJ00    | [f155ad2bf4](https://linux-hardware.org/?probe=f155ad2bf4) | Apr 24, 2023 |
| ASUSTek       | GL752VW                     | [216aaf8fff](https://linux-hardware.org/?probe=216aaf8fff) | Apr 24, 2023 |
| Gateway       | NV55C                       | [3c560a28cf](https://linux-hardware.org/?probe=3c560a28cf) | Apr 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2e7585d261](https://linux-hardware.org/?probe=2e7585d261) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [59c225df6e](https://linux-hardware.org/?probe=59c225df6e) | Apr 24, 2023 |
| Lenovo        | 20RD001FHV                  | [782ded0435](https://linux-hardware.org/?probe=782ded0435) | Apr 24, 2023 |
| Samsung       | 950XED                      | [6226147e11](https://linux-hardware.org/?probe=6226147e11) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [b1c3492700](https://linux-hardware.org/?probe=b1c3492700) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [db8e950d12](https://linux-hardware.org/?probe=db8e950d12) | Apr 24, 2023 |
| Acer          | Aspire A515-47              | [35a591e26a](https://linux-hardware.org/?probe=35a591e26a) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| Shanghai Z... | ZXE CRB                     | [298d51ae78](https://linux-hardware.org/?probe=298d51ae78) | Apr 24, 2023 |
| Dell          | Latitude E5470              | [bc1dca3c78](https://linux-hardware.org/?probe=bc1dca3c78) | Apr 24, 2023 |
| HP            | ZBook 17 G5                 | [c1d71592a4](https://linux-hardware.org/?probe=c1d71592a4) | Apr 24, 2023 |
| Acer          | Aspire A317-53              | [c47ec3530e](https://linux-hardware.org/?probe=c47ec3530e) | Apr 24, 2023 |
| Dell          | G5 5590                     | [eef3722c35](https://linux-hardware.org/?probe=eef3722c35) | Apr 23, 2023 |
| HP            | ZBook 17 G5                 | [ce9fd79431](https://linux-hardware.org/?probe=ce9fd79431) | Apr 23, 2023 |
| Dell          | Precision M4400             | [0c367cbf45](https://linux-hardware.org/?probe=0c367cbf45) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4286A44       | [6b6e909d11](https://linux-hardware.org/?probe=6b6e909d11) | Apr 23, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [641374c815](https://linux-hardware.org/?probe=641374c815) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [aa01246f8b](https://linux-hardware.org/?probe=aa01246f8b) | Apr 23, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [90b7213592](https://linux-hardware.org/?probe=90b7213592) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [620334c0fc](https://linux-hardware.org/?probe=620334c0fc) | Apr 23, 2023 |
| Dell          | Latitude E6420              | [475a16531a](https://linux-hardware.org/?probe=475a16531a) | Apr 22, 2023 |
| Dell          | Precision M4400             | [291a0de9a8](https://linux-hardware.org/?probe=291a0de9a8) | Apr 22, 2023 |
| Acer          | Nitro AN515-58              | [60251e08f5](https://linux-hardware.org/?probe=60251e08f5) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ce5e9aad85](https://linux-hardware.org/?probe=ce5e9aad85) | Apr 22, 2023 |
| Acer          | Aspire 7750G                | [afdab44276](https://linux-hardware.org/?probe=afdab44276) | Apr 22, 2023 |
| Acer          | Aspire 7750G                | [1f6e58080a](https://linux-hardware.org/?probe=1f6e58080a) | Apr 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [0f5a55a8d1](https://linux-hardware.org/?probe=0f5a55a8d1) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | [63cafebe06](https://linux-hardware.org/?probe=63cafebe06) | Apr 21, 2023 |
| ASUSTek       | N53SN                       | [7c0a7d4494](https://linux-hardware.org/?probe=7c0a7d4494) | Apr 21, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [2a5d9adcd4](https://linux-hardware.org/?probe=2a5d9adcd4) | Apr 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [85fa6bf3d5](https://linux-hardware.org/?probe=85fa6bf3d5) | Apr 21, 2023 |
| Dell          | Latitude E6420              | [5e3466ce98](https://linux-hardware.org/?probe=5e3466ce98) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | [d34d10b1ad](https://linux-hardware.org/?probe=d34d10b1ad) | Apr 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [05321d1ddd](https://linux-hardware.org/?probe=05321d1ddd) | Apr 20, 2023 |
| Dell          | Inspiron 3501               | [e09f00bead](https://linux-hardware.org/?probe=e09f00bead) | Apr 20, 2023 |
| HP            | Pavilion g4                 | [96a0210940](https://linux-hardware.org/?probe=96a0210940) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | [b54a612e76](https://linux-hardware.org/?probe=b54a612e76) | Apr 20, 2023 |
| Crusaders ... | CS14D01                     | [b25acea9f7](https://linux-hardware.org/?probe=b25acea9f7) | Apr 19, 2023 |
| Dell          | Vostro 15 7510              | [d9e766f446](https://linux-hardware.org/?probe=d9e766f446) | Apr 16, 2023 |
| HUAWEI        | BOM-WXX9                    | [04eead074d](https://linux-hardware.org/?probe=04eead074d) | Apr 14, 2023 |
| HUAWEI        | HLY-WX9XX                   | [d0742654bb](https://linux-hardware.org/?probe=d0742654bb) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [df35f6916a](https://linux-hardware.org/?probe=df35f6916a) | Apr 14, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | [0c4578a674](https://linux-hardware.org/?probe=0c4578a674) | Apr 14, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [6b481f17c2](https://linux-hardware.org/?probe=6b481f17c2) | Apr 13, 2023 |
| HUAWEI        | BOM-WXX9                    | [c56952417d](https://linux-hardware.org/?probe=c56952417d) | Apr 11, 2023 |
| Toshiba       | IS 1413G                    | [be9d1636a7](https://linux-hardware.org/?probe=be9d1636a7) | Apr 09, 2023 |
| Acer          | Swift SF314-55G             | [e15eaec4c0](https://linux-hardware.org/?probe=e15eaec4c0) | Apr 07, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [29f00590fb](https://linux-hardware.org/?probe=29f00590fb) | Apr 05, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [a1dceb9ce7](https://linux-hardware.org/?probe=a1dceb9ce7) | Apr 04, 2023 |
| Google        | Akemi                       | [14e5c7b93b](https://linux-hardware.org/?probe=14e5c7b93b) | Apr 04, 2023 |
| HUAWEI        | CREM-WXX9                   | [dd3c0ff2e5](https://linux-hardware.org/?probe=dd3c0ff2e5) | Apr 03, 2023 |
| Samsung       | 767XCL                      | [b5a44d9194](https://linux-hardware.org/?probe=b5a44d9194) | Apr 03, 2023 |
| Dell          | Inspiron 5458               | [38b9db2538](https://linux-hardware.org/?probe=38b9db2538) | Apr 01, 2023 |
| Samsung       | 767XCL                      | [a3167908c0](https://linux-hardware.org/?probe=a3167908c0) | Apr 01, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [13e8d4f50b](https://linux-hardware.org/?probe=13e8d4f50b) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b56e2a41ed](https://linux-hardware.org/?probe=b56e2a41ed) | Mar 31, 2023 |
| Shanghai Z... | ZXE CRB                     | [aafbb2815f](https://linux-hardware.org/?probe=aafbb2815f) | Mar 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4f2d3a2402](https://linux-hardware.org/?probe=4f2d3a2402) | Mar 25, 2023 |
| Shanghai Z... | ZXE CRB                     | [7f98044a04](https://linux-hardware.org/?probe=7f98044a04) | Mar 24, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [8c5fde8c1e](https://linux-hardware.org/?probe=8c5fde8c1e) | Mar 22, 2023 |
| Dell          | Latitude 7520               | [09c8e699d3](https://linux-hardware.org/?probe=09c8e699d3) | Mar 16, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [66094e937a](https://linux-hardware.org/?probe=66094e937a) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | [49130084c4](https://linux-hardware.org/?probe=49130084c4) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | [a6091bc2e2](https://linux-hardware.org/?probe=a6091bc2e2) | Mar 11, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [89e2fd827d](https://linux-hardware.org/?probe=89e2fd827d) | Mar 05, 2023 |
| Shanghai Z... | ZXE CRB                     | [bb68a61939](https://linux-hardware.org/?probe=bb68a61939) | Mar 05, 2023 |
| Lenovo        | E51-80 80QB                 | [824ece168f](https://linux-hardware.org/?probe=824ece168f) | Mar 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [525be1bcbe](https://linux-hardware.org/?probe=525be1bcbe) | Mar 02, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [830a8a94e2](https://linux-hardware.org/?probe=830a8a94e2) | Mar 02, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [0bf8c9ca74](https://linux-hardware.org/?probe=0bf8c9ca74) | Mar 02, 2023 |
| Toshiba       | IS 1413G                    | [05ad6c694b](https://linux-hardware.org/?probe=05ad6c694b) | Mar 01, 2023 |
| HP            | Laptop 17-by3xxx            | [5beb40c486](https://linux-hardware.org/?probe=5beb40c486) | Feb 28, 2023 |
| Samsung       | 370E4K                      | [aba5535c2a](https://linux-hardware.org/?probe=aba5535c2a) | Feb 28, 2023 |
| Toshiba       | IS 1413G                    | [c361aabb21](https://linux-hardware.org/?probe=c361aabb21) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | [17338cbd01](https://linux-hardware.org/?probe=17338cbd01) | Feb 27, 2023 |
| Apple         | MacBookPro10,1              | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| HP            | EliteBook 840 G2            | [33dc8202e9](https://linux-hardware.org/?probe=33dc8202e9) | Feb 25, 2023 |
| HUAWEI        | CREM-WXX9                   | [643d79fd46](https://linux-hardware.org/?probe=643d79fd46) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [ba0144c710](https://linux-hardware.org/?probe=ba0144c710) | Feb 20, 2023 |
| Apple         | MacBookPro13,3              | [628feb8b19](https://linux-hardware.org/?probe=628feb8b19) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | [2f591ee9e3](https://linux-hardware.org/?probe=2f591ee9e3) | Feb 13, 2023 |
| Timi          | RedmiBook 15                | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Acer          | Aspire V5-552G              | [2750863407](https://linux-hardware.org/?probe=2750863407) | Feb 02, 2023 |
| HP            | ProBook 6560b               | [a9eba68b79](https://linux-hardware.org/?probe=a9eba68b79) | Jan 14, 2023 |
| Samsung       | SBB-DA                      | [a4c6b4f454](https://linux-hardware.org/?probe=a4c6b4f454) | Jan 07, 2023 |
| MSI           | Raider GE67HX 12UGS         | [28822be06e](https://linux-hardware.org/?probe=28822be06e) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [e1ae2ba145](https://linux-hardware.org/?probe=e1ae2ba145) | Dec 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d1342c521a](https://linux-hardware.org/?probe=d1342c521a) | Dec 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5c0099832f](https://linux-hardware.org/?probe=5c0099832f) | Dec 15, 2022 |
| Lenovo        | B50-70 20384                | [82edcc6c08](https://linux-hardware.org/?probe=82edcc6c08) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | [6f8c8644e2](https://linux-hardware.org/?probe=6f8c8644e2) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [33f7ac03f4](https://linux-hardware.org/?probe=33f7ac03f4) | Nov 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| Apple         | MacBookPro9,2               | [e87a096d85](https://linux-hardware.org/?probe=e87a096d85) | Nov 27, 2022 |
| Apple         | MacBookPro9,2               | [9e465f741d](https://linux-hardware.org/?probe=9e465f741d) | Nov 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_23.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.0-20-generic        | 293       | 41.98%  |
| 6.2.0-26-generic        | 59        | 8.45%   |
| 6.2.0-27-generic        | 56        | 8.02%   |
| 6.2.0-25-generic        | 55        | 7.88%   |
| 6.2.0-24-generic        | 53        | 7.59%   |
| 6.2.0-23-generic        | 44        | 6.3%    |
| 6.2.0-31-generic        | 25        | 3.58%   |
| 5.19.0-21-generic       | 15        | 2.15%   |
| 6.2.0-18-generic        | 11        | 1.58%   |
| 6.4.0-060400-generic    | 7         | 1%      |
| 5.19.0-41-generic       | 7         | 1%      |
| 5.19.0-46-generic       | 6         | 0.86%   |
| 6.1.0-16-generic        | 5         | 0.72%   |
| 6.2.0-32-generic        | 4         | 0.57%   |
| 6.2.9-060209-generic    | 3         | 0.43%   |
| 5.19.0-40-generic       | 3         | 0.43%   |
| 5.19.0-31-generic       | 3         | 0.43%   |
| 6.3.5-060305-generic    | 2         | 0.29%   |
| 6.3.2-060302-generic    | 2         | 0.29%   |
| 6.2.0-19-generic        | 2         | 0.29%   |
| 6.2.0-1003-lowlatency   | 2         | 0.29%   |
| 5.19.0-28-generic       | 2         | 0.29%   |
| 6.5.1-tkg-cfs           | 1         | 0.14%   |
| 6.5.0-060500-generic    | 1         | 0.14%   |
| 6.4.8-tkg-cfs           | 1         | 0.14%   |
| 6.4.8-060408-generic    | 1         | 0.14%   |
| 6.4.7-t2-lunar          | 1         | 0.14%   |
| 6.4.6-060406-generic    | 1         | 0.14%   |
| 6.4.5-x64v3-xanmod1     | 1         | 0.14%   |
| 6.4.2-tkg-cfs           | 1         | 0.14%   |
| 6.3.8-x64v4-xanmod1     | 1         | 0.14%   |
| 6.3.7-060307-generic    | 1         | 0.14%   |
| 6.3.4-060304-generic    | 1         | 0.14%   |
| 6.3.1-x64v3-xanmod1     | 1         | 0.14%   |
| 6.3.0-rc7               | 1         | 0.14%   |
| 6.3.0-060300rc7-generic | 1         | 0.14%   |
| 6.3.0-060300-generic    | 1         | 0.14%   |
| 6.3.0+                  | 1         | 0.14%   |
| 6.2.6-060206-generic    | 1         | 0.14%   |
| 6.2.12-060212-generic   | 1         | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 6.2.0    | 579       | 86.42%  |
| 5.19.0   | 44        | 6.57%   |
| 6.4.0    | 7         | 1.04%   |
| 6.1.0    | 6         | 0.9%    |
| 6.3.0    | 4         | 0.6%    |
| 6.2.9    | 3         | 0.45%   |
| 5.14.0   | 3         | 0.45%   |
| 6.4.8    | 2         | 0.3%    |
| 6.3.5    | 2         | 0.3%    |
| 6.3.2    | 2         | 0.3%    |
| 6.5.1    | 1         | 0.15%   |
| 6.5.0    | 1         | 0.15%   |
| 6.4.7    | 1         | 0.15%   |
| 6.4.6    | 1         | 0.15%   |
| 6.4.5    | 1         | 0.15%   |
| 6.4.2    | 1         | 0.15%   |
| 6.3.8    | 1         | 0.15%   |
| 6.3.7    | 1         | 0.15%   |
| 6.3.4    | 1         | 0.15%   |
| 6.3.1    | 1         | 0.15%   |
| 6.2.6    | 1         | 0.15%   |
| 6.2.12   | 1         | 0.15%   |
| 6.2.11   | 1         | 0.15%   |
| 6.0.9    | 1         | 0.15%   |
| 5.17.0   | 1         | 0.15%   |
| 5.15.108 | 1         | 0.15%   |
| 5.15.0   | 1         | 0.15%   |
| 5.11.0   | 1         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 585       | 87.57%  |
| 5.19    | 44        | 6.59%   |
| 6.3     | 12        | 1.8%    |
| 6.4     | 11        | 1.65%   |
| 6.1     | 6         | 0.9%    |
| 5.14    | 3         | 0.45%   |
| 6.5     | 2         | 0.3%    |
| 5.15    | 2         | 0.3%    |
| 6.0     | 1         | 0.15%   |
| 5.17    | 1         | 0.15%   |
| 5.11    | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 660       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 643       | 97.28%  |
| X-Cinnamon      | 7         | 1.06%   |
| Unknown         | 7         | 1.06%   |
| sway            | 2         | 0.3%    |
| GNOME Flashback | 1         | 0.15%   |
| GNOME Classic   | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 449       | 67.01%  |
| X11     | 211       | 31.49%  |
| Unknown | 6         | 0.9%    |
| Tty     | 4         | 0.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 586       | 88.65%  |
| Unknown | 62        | 9.38%   |
| LightDM | 11        | 1.66%   |
| GREETD  | 1         | 0.15%   |
| GDM     | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 307       | 46.37%  |
| de_DE   | 66        | 9.97%   |
| fr_FR   | 33        | 4.98%   |
| es_ES   | 31        | 4.68%   |
| C       | 29        | 4.38%   |
| pt_BR   | 26        | 3.93%   |
| ru_RU   | 25        | 3.78%   |
| en_GB   | 18        | 2.72%   |
| it_IT   | 16        | 2.42%   |
| pl_PL   | 13        | 1.96%   |
| en_AU   | 10        | 1.51%   |
| nl_NL   | 7         | 1.06%   |
| en_CA   | 7         | 1.06%   |
| en_IN   | 6         | 0.91%   |
| es_MX   | 5         | 0.76%   |
| Unknown | 5         | 0.76%   |
| cs_CZ   | 4         | 0.6%    |
| bg_BG   | 4         | 0.6%    |
| sv_SE   | 3         | 0.45%   |
| nb_NO   | 3         | 0.45%   |
| ja_JP   | 3         | 0.45%   |
| hu_HU   | 3         | 0.45%   |
| fr_CA   | 3         | 0.45%   |
| en_ZA   | 3         | 0.45%   |
| el_GR   | 3         | 0.45%   |
| zh_CN   | 2         | 0.3%    |
| fi_FI   | 2         | 0.3%    |
| de_CH   | 2         | 0.3%    |
| de_AT   | 2         | 0.3%    |
| da_DK   | 2         | 0.3%    |
| ca_ES   | 2         | 0.3%    |
| tr_TR   | 1         | 0.15%   |
| th_TH   | 1         | 0.15%   |
| sr_RS   | 1         | 0.15%   |
| ro_RO   | 1         | 0.15%   |
| pt_PT   | 1         | 0.15%   |
| lt_LT   | 1         | 0.15%   |
| ko_KR   | 1         | 0.15%   |
| hr_HR   | 1         | 0.15%   |
| fa_IR   | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 381       | 57.47%  |
| EFI  | 282       | 42.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Tmpfs   | 329       | 49.7%   |
| Ext4    | 305       | 46.07%  |
| Overlay | 16        | 2.42%   |
| Btrfs   | 8         | 1.21%   |
| Zfs     | 3         | 0.45%   |
| Xfs     | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 575       | 86.99%  |
| Unknown | 55        | 8.32%   |
| MBR     | 31        | 4.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 603       | 91.23%  |
| Yes       | 58        | 8.77%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 425       | 63.91%  |
| Yes       | 240       | 36.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo                                   | 137       | 20.76%  |
| Hewlett-Packard                          | 109       | 16.52%  |
| Dell                                     | 109       | 16.52%  |
| ASUSTek Computer                         | 71        | 10.76%  |
| Acer                                     | 61        | 9.24%   |
| Apple                                    | 24        | 3.64%   |
| HUAWEI                                   | 23        | 3.48%   |
| MSI                                      | 20        | 3.03%   |
| Toshiba                                  | 12        | 1.82%   |
| Samsung Electronics                      | 10        | 1.52%   |
| Google                                   | 7         | 1.06%   |
| Unknown                                  | 7         | 1.06%   |
| Timi                                     | 6         | 0.91%   |
| Sony                                     | 6         | 0.91%   |
| Notebook                                 | 6         | 0.91%   |
| Medion                                   | 4         | 0.61%   |
| Shanghai Zhaoxin Semiconductor           | 3         | 0.45%   |
| Razer                                    | 3         | 0.45%   |
| Packard Bell                             | 3         | 0.45%   |
| Intel                                    | 3         | 0.45%   |
| Gigabyte Technology                      | 3         | 0.45%   |
| Alienware                                | 3         | 0.45%   |
| Positivo                                 | 2         | 0.3%    |
| Panasonic                                | 2         | 0.3%    |
| Infinix                                  | 2         | 0.3%    |
| HONOR                                    | 2         | 0.3%    |
| Gateway                                  | 2         | 0.3%    |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. | 1         | 0.15%   |
| VALE                                     | 1         | 0.15%   |
| Star Labs                                | 1         | 0.15%   |
| Shuttle                                  | 1         | 0.15%   |
| Semp Toshiba                             | 1         | 0.15%   |
| Rombica                                  | 1         | 0.15%   |
| PC Specialist                            | 1         | 0.15%   |
| Olivetti                                 | 1         | 0.15%   |
| Mediacom                                 | 1         | 0.15%   |
| Intel Client Systems                     | 1         | 0.15%   |
| ICL                                      | 1         | 0.15%   |
| Fujitsu                                  | 1         | 0.15%   |
| Framework                                | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 8         | 1.21%   |
| HP EliteBook 840 G6              | 5         | 0.76%   |
| Dell Latitude 7480               | 5         | 0.76%   |
| HUAWEI BOM-WXX9                  | 4         | 0.61%   |
| HP Notebook                      | 4         | 0.61%   |
| Apple MacBookPro9,2              | 4         | 0.61%   |
| Apple MacBookAir7,2              | 4         | 0.61%   |
| Shanghai Zhaoxin ZXE CRB         | 3         | 0.45%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7 | 3         | 0.45%   |
| Lenovo G50-70 20351              | 3         | 0.45%   |
| HUAWEI BOHB-WAX9                 | 3         | 0.45%   |
| Dell XPS 15 9500                 | 3         | 0.45%   |
| Dell Precision 5570              | 3         | 0.45%   |
| Dell Inspiron 3442               | 3         | 0.45%   |
| Dell G5 5590                     | 3         | 0.45%   |
| ASUS ZenBook UX325EA_UX325EA     | 3         | 0.45%   |
| ASUS Zenbook UM5302TA_UM5302TA   | 3         | 0.45%   |
| Acer Swift SF314-512             | 3         | 0.45%   |
| Toshiba Satellite Pro C70-B      | 2         | 0.3%    |
| Timi Redmi Book Pro 14 2022      | 2         | 0.3%    |
| Packard Bell EasyNote ENTF71BM   | 2         | 0.3%    |
| MSI Stealth 15M B12UE            | 2         | 0.3%    |
| MSI Modern 14 A10M               | 2         | 0.3%    |
| Lenovo IdeaPad 5 15ITL05 82FG    | 2         | 0.3%    |
| Lenovo IdeaPad 5 15ARE05 81YQ    | 2         | 0.3%    |
| HUAWEI NBLB-WAX9N                | 2         | 0.3%    |
| HUAWEI KLVD-WXX9                 | 2         | 0.3%    |
| HUAWEI HVY-WXX9                  | 2         | 0.3%    |
| HUAWEI CREM-WXX9                 | 2         | 0.3%    |
| HUAWEI BOD-WXX9                  | 2         | 0.3%    |
| HONOR BBR-WAX9                   | 2         | 0.3%    |
| HP ZBook Studio G3               | 2         | 0.3%    |
| HP Pavilion Notebook             | 2         | 0.3%    |
| HP Pavilion dv6                  | 2         | 0.3%    |
| HP OMEN by Laptop                | 2         | 0.3%    |
| HP Meep                          | 2         | 0.3%    |
| HP Laptop 15s-eq2xxx             | 2         | 0.3%    |
| HP Laptop 14s-fq1xxx             | 2         | 0.3%    |
| HP Laptop 14-fq0xxx              | 2         | 0.3%    |
| HP Laptop 14-dq2xxx              | 2         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 76        | 11.52%  |
| Dell Latitude         | 45        | 6.82%   |
| Acer Aspire           | 32        | 4.85%   |
| Lenovo IdeaPad        | 29        | 4.39%   |
| HP EliteBook          | 24        | 3.64%   |
| Dell Inspiron         | 24        | 3.64%   |
| ASUS VivoBook         | 23        | 3.48%   |
| HP Laptop             | 20        | 3.03%   |
| Dell XPS              | 19        | 2.88%   |
| HP Pavilion           | 18        | 2.73%   |
| ASUS ZenBook          | 14        | 2.12%   |
| Acer Swift            | 12        | 1.82%   |
| HP ProBook            | 11        | 1.67%   |
| Acer Nitro            | 11        | 1.67%   |
| Dell Precision        | 9         | 1.36%   |
| ASUS ASUS             | 9         | 1.36%   |
| Toshiba Satellite     | 8         | 1.21%   |
| Unknown               | 8         | 1.21%   |
| Lenovo Legion         | 7         | 1.06%   |
| MSI Stealth           | 5         | 0.76%   |
| Lenovo ThinkBook      | 5         | 0.76%   |
| Dell Vostro           | 5         | 0.76%   |
| Lenovo Yoga           | 4         | 0.61%   |
| HUAWEI BOM-WXX9       | 4         | 0.61%   |
| HP ZBook              | 4         | 0.61%   |
| HP Notebook           | 4         | 0.61%   |
| HP ENVY               | 4         | 0.61%   |
| Dell G5               | 4         | 0.61%   |
| Apple MacBookPro9     | 4         | 0.61%   |
| Apple MacBookAir7     | 4         | 0.61%   |
| Toshiba PORTEGE       | 3         | 0.45%   |
| Shanghai Zhaoxin ZXE  | 3         | 0.45%   |
| Razer Blade           | 3         | 0.45%   |
| Packard Bell EasyNote | 3         | 0.45%   |
| MSI GF63              | 3         | 0.45%   |
| Lenovo V15            | 3         | 0.45%   |
| Lenovo G50-70         | 3         | 0.45%   |
| HUAWEI BOHB-WAX9      | 3         | 0.45%   |
| HP OMEN               | 3         | 0.45%   |
| Apple MacBookPro14    | 3         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 105       | 15.91%  |
| 2022    | 81        | 12.27%  |
| 2020    | 76        | 11.52%  |
| 2019    | 51        | 7.73%   |
| 2016    | 40        | 6.06%   |
| 2023    | 39        | 5.91%   |
| 2017    | 39        | 5.91%   |
| 2018    | 35        | 5.3%    |
| 2011    | 34        | 5.15%   |
| 2012    | 32        | 4.85%   |
| 2015    | 31        | 4.7%    |
| 2014    | 28        | 4.24%   |
| 2013    | 23        | 3.48%   |
| 2010    | 21        | 3.18%   |
| 2008    | 11        | 1.67%   |
| 2009    | 9         | 1.36%   |
| 2007    | 4         | 0.61%   |
| Unknown | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 660       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 581       | 87.9%   |
| Enabled  | 80        | 12.1%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 651       | 98.64%  |
| Yes  | 9         | 1.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 194       | 29.39%  |
| 16.01-24.0  | 138       | 20.91%  |
| 8.01-16.0   | 126       | 19.09%  |
| 3.01-4.0    | 92        | 13.94%  |
| 32.01-64.0  | 68        | 10.3%   |
| 24.01-32.0  | 20        | 3.03%   |
| 64.01-256.0 | 12        | 1.82%   |
| 1.01-2.0    | 7         | 1.06%   |
| 2.01-3.0    | 2         | 0.3%    |
| 0.01-0.5    | 1         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 215       | 31.48%  |
| 1.01-2.0   | 157       | 22.99%  |
| 4.01-8.0   | 151       | 22.11%  |
| 3.01-4.0   | 125       | 18.3%   |
| 8.01-16.0  | 26        | 3.81%   |
| 16.01-24.0 | 4         | 0.59%   |
| 0.51-1.0   | 2         | 0.29%   |
| 32.01-64.0 | 1         | 0.15%   |
| 24.01-32.0 | 1         | 0.15%   |
| 0.01-0.5   | 1         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 509       | 76.66%  |
| 2      | 138       | 20.78%  |
| 3      | 12        | 1.81%   |
| 4      | 2         | 0.3%    |
| 0      | 2         | 0.3%    |
| 5      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 516       | 78.18%  |
| Yes       | 144       | 21.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 455       | 68.94%  |
| No        | 205       | 31.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 653       | 98.94%  |
| No        | 7         | 1.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 574       | 86.58%  |
| No        | 89        | 13.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 97        | 14.67%  |
| Germany      | 75        | 11.35%  |
| France       | 41        | 6.2%    |
| Russia       | 40        | 6.05%   |
| Brazil       | 38        | 5.75%   |
| Italy        | 31        | 4.69%   |
| UK           | 22        | 3.33%   |
| India        | 20        | 3.03%   |
| Spain        | 19        | 2.87%   |
| Canada       | 16        | 2.42%   |
| Australia    | 16        | 2.42%   |
| Netherlands  | 15        | 2.27%   |
| Mexico       | 14        | 2.12%   |
| Poland       | 13        | 1.97%   |
| Norway       | 13        | 1.97%   |
| Romania      | 9         | 1.36%   |
| Turkey       | 8         | 1.21%   |
| Belgium      | 8         | 1.21%   |
| Switzerland  | 7         | 1.06%   |
| Sweden       | 7         | 1.06%   |
| Indonesia    | 7         | 1.06%   |
| Czechia      | 7         | 1.06%   |
| Hungary      | 6         | 0.91%   |
| Chile        | 6         | 0.91%   |
| Portugal     | 5         | 0.76%   |
| Kenya        | 5         | 0.76%   |
| Japan        | 5         | 0.76%   |
| Ireland      | 5         | 0.76%   |
| Colombia     | 5         | 0.76%   |
| China        | 5         | 0.76%   |
| Austria      | 5         | 0.76%   |
| South Africa | 4         | 0.61%   |
| Greece       | 4         | 0.61%   |
| Finland      | 4         | 0.61%   |
| Bulgaria     | 4         | 0.61%   |
| Belarus      | 4         | 0.61%   |
| Vietnam      | 3         | 0.45%   |
| Serbia       | 3         | 0.45%   |
| Qatar        | 3         | 0.45%   |
| Malaysia     | 3         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 10        | 1.48%   |
| Berlin            | 10        | 1.48%   |
| Sao Paulo         | 7         | 1.04%   |
| Oslo              | 7         | 1.04%   |
| Barcelona         | 6         | 0.89%   |
| St Petersburg     | 5         | 0.74%   |
| Nairobi           | 5         | 0.74%   |
| Atlanta           | 5         | 0.74%   |
| Santiago          | 4         | 0.59%   |
| Montreal          | 4         | 0.59%   |
| Milan             | 4         | 0.59%   |
| Melbourne         | 4         | 0.59%   |
| Hamburg           | 4         | 0.59%   |
| Denver            | 4         | 0.59%   |
| Cologne           | 4         | 0.59%   |
| Zurich            | 3         | 0.44%   |
| Warsaw            | 3         | 0.44%   |
| Valencia          | 3         | 0.44%   |
| Toronto           | 3         | 0.44%   |
| Sofia             | 3         | 0.44%   |
| Rio de Janeiro    | 3         | 0.44%   |
| Prague            | 3         | 0.44%   |
| Paris             | 3         | 0.44%   |
| Oshawa            | 3         | 0.44%   |
| New York          | 3         | 0.44%   |
| Munich            | 3         | 0.44%   |
| Mumbai            | 3         | 0.44%   |
| Milano            | 3         | 0.44%   |
| Madrid            | 3         | 0.44%   |
| Krakow            | 3         | 0.44%   |
| Helsinki          | 3         | 0.44%   |
| Ghaziabad         | 3         | 0.44%   |
| Frankfurt am Main | 3         | 0.44%   |
| Dublin            | 3         | 0.44%   |
| Doha              | 3         | 0.44%   |
| Brussels          | 3         | 0.44%   |
| Brisbane          | 3         | 0.44%   |
| Antalya           | 3         | 0.44%   |
| Adelaide          | 3         | 0.44%   |
| Vienna            | 2         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 138       | 160    | 17.25%  |
| Sandisk                     | 64        | 71     | 8%      |
| WDC                         | 59        | 70     | 7.38%   |
| Seagate                     | 54        | 62     | 6.75%   |
| SK hynix                    | 50        | 54     | 6.25%   |
| Kingston                    | 45        | 50     | 5.63%   |
| Micron Technology           | 41        | 45     | 5.13%   |
| Toshiba                     | 35        | 37     | 4.38%   |
| Unknown                     | 34        | 38     | 4.25%   |
| Intel                       | 34        | 40     | 4.25%   |
| Crucial                     | 26        | 28     | 3.25%   |
| KIOXIA                      | 24        | 25     | 3%      |
| Apple                       | 16        | 20     | 2%      |
| Phison Electronics          | 14        | 17     | 1.75%   |
| China                       | 12        | 12     | 1.5%    |
| Hitachi                     | 10        | 12     | 1.25%   |
| Kingston Technology Company | 9         | 9      | 1.13%   |
| HGST                        | 9         | 11     | 1.13%   |
| Phison                      | 7         | 7      | 0.88%   |
| Unknown                     | 6         | 8      | 0.75%   |
| Silicon Motion              | 5         | 5      | 0.63%   |
| LITEONIT                    | 5         | 6      | 0.63%   |
| Intenso                     | 5         | 7      | 0.63%   |
| ADATA Technology            | 5         | 6      | 0.63%   |
| A-DATA Technology           | 5         | 5      | 0.63%   |
| SPCC                        | 4         | 4      | 0.5%    |
| FORESEE                     | 4         | 5      | 0.5%    |
| Union Memory (Shenzhen)     | 3         | 3      | 0.38%   |
| Team                        | 3         | 3      | 0.38%   |
| SSSTC                       | 3         | 3      | 0.38%   |
| Realtek Semiconductor       | 3         | 3      | 0.38%   |
| Netac                       | 3         | 3      | 0.38%   |
| Micron/Crucial Technology   | 3         | 3      | 0.38%   |
| LITEON                      | 3         | 6      | 0.38%   |
| Lexar                       | 3         | 3      | 0.38%   |
| GOODRAM                     | 3         | 3      | 0.38%   |
| Gigabyte Technology         | 3         | 3      | 0.38%   |
| YMTC                        | 2         | 2      | 0.25%   |
| Union Memory                | 2         | 2      | 0.25%   |
| Transcend                   | 2         | 2      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 17        | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB                        | 13        | 1.59%   |
| Kingston SA400S37240G 240GB SSD                       | 13        | 1.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 10        | 1.22%   |
| Unknown MMC Card  64GB                                | 8         | 0.98%   |
| SanDisk NVMe SSD Drive 512GB                          | 8         | 0.98%   |
| Intel SSDPEKNU512GZ 512GB                             | 8         | 0.98%   |
| Kingston SA400S37480G 480GB SSD                       | 7         | 0.86%   |
| Unknown MMC Card  32GB                                | 6         | 0.73%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 6         | 0.73%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 6         | 0.73%   |
| Phison E12 NVMe Controller 256GB                      | 6         | 0.73%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                         | 6         | 0.73%   |
| Unknown                                               | 6         | 0.73%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 5         | 0.61%   |
| Toshiba MQ01ABF050 500GB                              | 5         | 0.61%   |
| Seagate ST500LT012-1DG142 500GB                       | 5         | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 5         | 0.61%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 5         | 0.61%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB               | 5         | 0.61%   |
| HGST HTS721010A9E630 1TB                              | 5         | 0.61%   |
| Unknown MMC Card  128GB                               | 4         | 0.49%   |
| SK hynix HFM512GD3JX013N 512GB                        | 4         | 0.49%   |
| SK hynix BC511 512GB                                  | 4         | 0.49%   |
| Seagate ST1000LM049-2GH172 1TB                        | 4         | 0.49%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD                   | 4         | 0.49%   |
| SanDisk NVMe SSD Drive 1TB                            | 4         | 0.49%   |
| Samsung SSD 870 EVO 500GB                             | 4         | 0.49%   |
| Samsung SSD 870 EVO 1TB                               | 4         | 0.49%   |
| Samsung SSD 860 EVO 250GB                             | 4         | 0.49%   |
| Samsung SSD 850 EVO 250GB                             | 4         | 0.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 4         | 0.49%   |
| Samsung MZVL21T0HCLR-00B00 1TB                        | 4         | 0.49%   |
| KIOXIA KBG40ZNV512G 512GB                             | 4         | 0.49%   |
| Crucial CT500MX500SSD1 500GB                          | 4         | 0.49%   |
| Crucial CT240BX500SSD1 240GB                          | 4         | 0.49%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB                  | 3         | 0.37%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                  | 3         | 0.37%   |
| Unknown SD/MMC/MS PRO 1GB                             | 3         | 0.37%   |
| Unknown MMC Card  16GB                                | 3         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 60     | 39.39%  |
| WDC                 | 28        | 33     | 21.21%  |
| Toshiba             | 21        | 23     | 15.91%  |
| Hitachi             | 10        | 12     | 7.58%   |
| HGST                | 9         | 11     | 6.82%   |
| Samsung Electronics | 4         | 4      | 3.03%   |
| Unknown             | 3         | 3      | 2.27%   |
| HGST HTS            | 2         | 2      | 1.52%   |
| JMicron Technology  | 1         | 1      | 0.76%   |
| Fujitsu             | 1         | 1      | 0.76%   |
| Apple               | 1         | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 48        | 56     | 19.35%  |
| Kingston            | 35        | 40     | 14.11%  |
| Crucial             | 22        | 24     | 8.87%   |
| SanDisk             | 19        | 20     | 7.66%   |
| WDC                 | 14        | 19     | 5.65%   |
| SK hynix            | 12        | 12     | 4.84%   |
| China               | 12        | 12     | 4.84%   |
| Apple               | 9         | 10     | 3.63%   |
| Micron Technology   | 7         | 7      | 2.82%   |
| Intel               | 7         | 8      | 2.82%   |
| LITEONIT            | 5         | 6      | 2.02%   |
| Intenso             | 4         | 5      | 1.61%   |
| A-DATA Technology   | 4         | 4      | 1.61%   |
| Unknown             | 4         | 4      | 1.61%   |
| Team                | 3         | 3      | 1.21%   |
| SPCC                | 3         | 3      | 1.21%   |
| Netac               | 3         | 3      | 1.21%   |
| LITEON              | 3         | 6      | 1.21%   |
| Lexar               | 3         | 3      | 1.21%   |
| Gigabyte Technology | 3         | 3      | 1.21%   |
| Toshiba             | 2         | 2      | 0.81%   |
| PNY                 | 2         | 2      | 0.81%   |
| Patriot             | 2         | 2      | 0.81%   |
| Kingchuxing         | 2         | 2      | 0.81%   |
| GOODRAM             | 2         | 2      | 0.81%   |
| XrayDisk            | 1         | 1      | 0.4%    |
| WDC WDS2            | 1         | 1      | 0.4%    |
| Transcend           | 1         | 1      | 0.4%    |
| Smartbuy            | 1         | 1      | 0.4%    |
| S3+                 | 1         | 1      | 0.4%    |
| POWER               | 1         | 1      | 0.4%    |
| Plextor             | 1         | 1      | 0.4%    |
| Pioneer             | 1         | 1      | 0.4%    |
| OWC                 | 1         | 1      | 0.4%    |
| ORTIAL              | 1         | 1      | 0.4%    |
| NT-512              | 1         | 1      | 0.4%    |
| KINGBANK            | 1         | 1      | 0.4%    |
| JMicron Technology  | 1         | 1      | 0.4%    |
| INTEL SS            | 1         | 2      | 0.4%    |
| GLOWAY              | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 357       | 422    | 47.04%  |
| SSD     | 230       | 277    | 30.3%   |
| HDD     | 131       | 151    | 17.26%  |
| MMC     | 31        | 36     | 4.08%   |
| Unknown | 10        | 12     | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 357       | 420    | 48.31%  |
| SATA | 321       | 408    | 43.44%  |
| MMC  | 31        | 36     | 4.19%   |
| SAS  | 30        | 34     | 4.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 240       | 288    | 66.12%  |
| 0.51-1.0   | 106       | 117    | 29.2%   |
| 1.01-2.0   | 13        | 19     | 3.58%   |
| 4.01-10.0  | 4         | 4      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 217       | 32.15%  |
| 101-250        | 197       | 29.19%  |
| 501-1000       | 106       | 15.7%   |
| 1-20           | 38        | 5.63%   |
| 51-100         | 33        | 4.89%   |
| 1001-2000      | 31        | 4.59%   |
| 21-50          | 28        | 4.15%   |
| More than 3000 | 12        | 1.78%   |
| 2001-3000      | 8         | 1.19%   |
| Unknown        | 5         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 231       | 33.97%  |
| 21-50          | 177       | 26.03%  |
| 101-250        | 90        | 13.24%  |
| 51-100         | 81        | 11.91%  |
| 251-500        | 56        | 8.24%   |
| 501-1000       | 22        | 3.24%   |
| 1001-2000      | 11        | 1.62%   |
| Unknown        | 5         | 0.74%   |
| 2001-3000      | 4         | 0.59%   |
| More than 3000 | 3         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 11.76%  |
| WDC WD10SPZX-21Z10T0 1TB                 | 1         | 1      | 5.88%   |
| WDC WD Green M.2 2280 240GB SSD          | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 5.88%   |
| Toshiba MK5065GSXF 500GB                 | 1         | 1      | 5.88%   |
| SSSTC CA6-8D2048-Q11 NVMe 2048GB         | 1         | 1      | 5.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 5.88%   |
| SanDisk SDSSDX120GG25 120GB              | 1         | 1      | 5.88%   |
| LITEONIT LCT-256M3S-41 7mm 256GB FDE SSD | 1         | 1      | 5.88%   |
| Hitachi HTS723225A7A365 OPAL 250GB       | 1         | 1      | 5.88%   |
| Hitachi HTS547564A9E384 640GB            | 1         | 1      | 5.88%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 5.88%   |
| HGST HTS541010A9E680 1TB                 | 1         | 1      | 5.88%   |
| Fujitsu MHW2160BH 160GB                  | 1         | 1      | 5.88%   |
| Crucial CT525MX300SSD4 528GB             | 1         | 1      | 5.88%   |
| Unknown                                  | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 3      | 17.65%  |
| WDC      | 2         | 2      | 11.76%  |
| Toshiba  | 2         | 2      | 11.76%  |
| Hitachi  | 2         | 2      | 11.76%  |
| HGST     | 2         | 2      | 11.76%  |
| SSSTC    | 1         | 1      | 5.88%   |
| SanDisk  | 1         | 1      | 5.88%   |
| LITEONIT | 1         | 1      | 5.88%   |
| Fujitsu  | 1         | 1      | 5.88%   |
| Crucial  | 1         | 1      | 5.88%   |
| Unknown  | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 27.27%  |
| Toshiba | 2         | 2      | 18.18%  |
| Hitachi | 2         | 2      | 18.18%  |
| HGST    | 2         | 2      | 18.18%  |
| WDC     | 1         | 1      | 9.09%   |
| Fujitsu | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 64.71%  |
| SSD  | 5         | 5      | 29.41%  |
| NVMe | 1         | 1      | 5.88%   |

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
| Detected | 420       | 599    | 62.13%  |
| Works    | 239       | 282    | 35.36%  |
| Malfunc  | 17        | 17     | 2.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 420       | 49.76%  |
| Samsung Electronics                     | 95        | 11.26%  |
| SanDisk                                 | 62        | 7.35%   |
| AMD                                     | 57        | 6.75%   |
| SK hynix                                | 38        | 4.5%    |
| Micron Technology                       | 34        | 4.03%   |
| Phison Electronics                      | 23        | 2.73%   |
| KIOXIA                                  | 22        | 2.61%   |
| Kingston Technology Company             | 17        | 2.01%   |
| Toshiba America Info Systems            | 14        | 1.66%   |
| Micron/Crucial Technology               | 7         | 0.83%   |
| ADATA Technology                        | 7         | 0.83%   |
| Solid State Storage Technology          | 6         | 0.71%   |
| Union Memory (Shenzhen)                 | 5         | 0.59%   |
| Silicon Motion                          | 5         | 0.59%   |
| Shenzhen Longsys Electronics            | 5         | 0.59%   |
| Apple                                   | 5         | 0.59%   |
| Realtek Semiconductor                   | 4         | 0.47%   |
| Zhaoxin                                 | 3         | 0.36%   |
| Nvidia                                  | 3         | 0.36%   |
| Yangtze Memory Technologies             | 2         | 0.24%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.24%   |
| Transcend                               | 1         | 0.12%   |
| Solidigm                                | 1         | 0.12%   |
| Silicon Image                           | 1         | 0.12%   |
| Shenzhen Unionmemory Information System | 1         | 0.12%   |
| Marvell Technology Group                | 1         | 0.12%   |
| Lite-On Technology                      | 1         | 0.12%   |
| Lenovo                                  | 1         | 0.12%   |
| ASMedia Technology                      | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                            | 63        | 7.09%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 54        | 6.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 49        | 5.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 37        | 4.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 34        | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 30        | 3.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 28        | 3.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 26        | 2.92%   |
| Samsung NVMe SSD Controller 980                                                | 24        | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 19        | 2.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 18        | 2.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 18        | 2.02%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 17        | 1.91%   |
| Intel Tiger Lake-LP SATA Controller                                            | 16        | 1.8%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 15        | 1.69%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 13        | 1.46%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 12        | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                          | 12        | 1.35%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 11        | 1.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 11        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 11        | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 10        | 1.12%   |
| Phison PS5013 E13 NVMe Controller                                              | 10        | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 1.12%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 1.01%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 9         | 1.01%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 8         | 0.9%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 8         | 0.9%    |
| SK hynix BC511 NVMe SSD                                                        | 7         | 0.79%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 7         | 0.79%   |
| Phison E12 NVMe Controller                                                     | 7         | 0.79%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 7         | 0.79%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 7         | 0.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 7         | 0.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 0.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 0.67%   |
| Intel SSD 660P Series                                                          | 6         | 0.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 379       | 44.28%  |
| NVMe | 355       | 41.47%  |
| RAID | 109       | 12.73%  |
| IDE  | 13        | 1.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 524       | 79.39%  |
| AMD          | 133       | 20.15%  |
| CentaurHauls | 3         | 0.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 14        | 2.12%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 14        | 2.12%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 11        | 1.67%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 11        | 1.67%   |
| Intel 12th Gen Core i7-12700H           | 10        | 1.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 9         | 1.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 9         | 1.36%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 9         | 1.36%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 9         | 1.36%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 8         | 1.21%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 8         | 1.21%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 1.21%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 7         | 1.06%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 7         | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 7         | 1.06%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 1.06%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 7         | 1.06%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 7         | 1.06%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 7         | 1.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 6         | 0.91%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 6         | 0.91%   |
| Intel 12th Gen Core i7-1260P            | 6         | 0.91%   |
| Intel 12th Gen Core i5-1240P            | 6         | 0.91%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 6         | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 5         | 0.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 5         | 0.76%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 5         | 0.76%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 5         | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 0.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 0.76%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 5         | 0.76%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 5         | 0.76%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 5         | 0.76%   |
| Intel Core i3-10110U CPU @ 2.10GHz      | 5         | 0.76%   |
| Intel 13th Gen Core i7-13700H           | 5         | 0.76%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 5         | 0.76%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 5         | 0.76%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 5         | 0.76%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 4         | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 4         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 154       | 23.33%  |
| Other                   | 142       | 21.52%  |
| Intel Core i7           | 117       | 17.73%  |
| AMD Ryzen 7             | 48        | 7.27%   |
| Intel Core i3           | 44        | 6.67%   |
| AMD Ryzen 5             | 33        | 5%      |
| Intel Celeron           | 25        | 3.79%   |
| Intel Core 2 Duo        | 19        | 2.88%   |
| Intel Pentium           | 9         | 1.36%   |
| AMD Ryzen 9             | 9         | 1.36%   |
| AMD Ryzen 3             | 7         | 1.06%   |
| AMD Ryzen 7 PRO         | 6         | 0.91%   |
| AMD Ryzen 5 PRO         | 6         | 0.91%   |
| Intel Pentium Silver    | 5         | 0.76%   |
| AMD A4                  | 5         | 0.76%   |
| AMD E2                  | 4         | 0.61%   |
| AMD A8                  | 4         | 0.61%   |
| Intel Pentium Dual      | 3         | 0.45%   |
| Intel Core i9           | 3         | 0.45%   |
| Intel Xeon              | 2         | 0.3%    |
| Intel Core M            | 2         | 0.3%    |
| AMD A10                 | 2         | 0.3%    |
| Intel Pentium Dual-Core | 1         | 0.15%   |
| Intel Genuine           | 1         | 0.15%   |
| Intel Core m7           | 1         | 0.15%   |
| Intel Core m3           | 1         | 0.15%   |
| Intel Atom              | 1         | 0.15%   |
| AMD Turion 64 X2 Mobile | 1         | 0.15%   |
| AMD E1                  | 1         | 0.15%   |
| AMD E                   | 1         | 0.15%   |
| AMD Athlon II           | 1         | 0.15%   |
| AMD Athlon              | 1         | 0.15%   |
| AMD A6                  | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 264       | 39.94%  |
| 4      | 196       | 29.65%  |
| 8      | 78        | 11.8%   |
| 6      | 61        | 9.23%   |
| 14     | 27        | 4.08%   |
| 12     | 15        | 2.27%   |
| 10     | 13        | 1.97%   |
| 16     | 3         | 0.45%   |
| 1      | 2         | 0.3%    |
| 24     | 1         | 0.15%   |
| 5      | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 660       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 544       | 82.42%  |
| 1      | 116       | 17.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 660       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 574       | 86.71%  |
| 0x0a404102 | 10        | 1.51%   |
| 0x0a50000c | 9         | 1.36%   |
| 0x08608103 | 9         | 1.36%   |
| 0x08600106 | 7         | 1.06%   |
| 0x0a50000d | 6         | 0.91%   |
| 0x0a404101 | 5         | 0.76%   |
| 0x906a3    | 4         | 0.6%    |
| 0x806ec    | 3         | 0.45%   |
| 0x08a00006 | 3         | 0.45%   |
| 0x306a9    | 2         | 0.3%    |
| 0x0a704101 | 2         | 0.3%    |
| 0x08608104 | 2         | 0.3%    |
| 0x08608102 | 2         | 0.3%    |
| 0x08600109 | 2         | 0.3%    |
| 0x08108109 | 2         | 0.3%    |
| 0x08108102 | 2         | 0.3%    |
| 0x08101016 | 2         | 0.3%    |
| 0x906ea    | 1         | 0.15%   |
| 0x806d1    | 1         | 0.15%   |
| 0x806c1    | 1         | 0.15%   |
| 0x506e3    | 1         | 0.15%   |
| 0x406e3    | 1         | 0.15%   |
| 0x40651    | 1         | 0.15%   |
| 0x306d4    | 1         | 0.15%   |
| 0x206a7    | 1         | 0.15%   |
| 0x0a601203 | 1         | 0.15%   |
| 0x08600103 | 1         | 0.15%   |
| 0x08200103 | 1         | 0.15%   |
| 0x0810100b | 1         | 0.15%   |
| 0x07030105 | 1         | 0.15%   |
| 0x06006704 | 1         | 0.15%   |
| 0x06006113 | 1         | 0.15%   |
| 0x06001119 | 1         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 119       | 18%     |
| Unknown          | 89        | 13.46%  |
| TigerLake        | 59        | 8.93%   |
| Skylake          | 43        | 6.51%   |
| Alderlake Hybrid | 43        | 6.51%   |
| IvyBridge        | 38        | 5.75%   |
| SandyBridge      | 36        | 5.45%   |
| Haswell          | 30        | 4.54%   |
| Zen 3            | 27        | 4.08%   |
| Broadwell        | 24        | 3.63%   |
| Zen 2            | 20        | 3.03%   |
| Penryn           | 16        | 2.42%   |
| Westmere         | 15        | 2.27%   |
| Goldmont plus    | 15        | 2.27%   |
| CometLake        | 15        | 2.27%   |
| IceLake          | 12        | 1.82%   |
| Zen+             | 10        | 1.51%   |
| Silvermont       | 9         | 1.36%   |
| Excavator        | 7         | 1.06%   |
| Core             | 7         | 1.06%   |
| Zen              | 5         | 0.76%   |
| Goldmont         | 5         | 0.76%   |
| Puma             | 4         | 0.61%   |
| Piledriver       | 3         | 0.45%   |
| Jaguar           | 2         | 0.3%    |
| Bobcat           | 2         | 0.3%    |
| Tremont          | 1         | 0.15%   |
| Steamroller      | 1         | 0.15%   |
| Nehalem          | 1         | 0.15%   |
| K8 Hammer        | 1         | 0.15%   |
| K10 Llano        | 1         | 0.15%   |
| K10              | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Intel          | 496       | 58.22%  |
| Nvidia         | 186       | 21.83%  |
| AMD            | 166       | 19.48%  |
| Zhaoxin        | 3         | 0.35%   |
| Silicon Motion | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 45        | 5.22%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 35        | 4.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 34        | 3.94%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 30        | 3.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 29        | 3.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 24        | 2.78%   |
| Intel HD Graphics 620                                                     | 22        | 2.55%   |
| AMD Rembrandt [Radeon 680M]                                               | 22        | 2.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 21        | 2.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 20        | 2.32%   |
| AMD Renoir                                                                | 20        | 2.32%   |
| Intel UHD Graphics 620                                                    | 19        | 2.2%    |
| AMD Lucienne                                                              | 19        | 2.2%    |
| Intel HD Graphics 5500                                                    | 18        | 2.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 17        | 1.97%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 16        | 1.86%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 16        | 1.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 16        | 1.86%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 13        | 1.51%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 12        | 1.39%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 12        | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 12        | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 12        | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 12        | 1.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 11        | 1.28%   |
| AMD Barcelo                                                               | 11        | 1.28%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 10        | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                       | 10        | 1.16%   |
| Intel HD Graphics 630                                                     | 7         | 0.81%   |
| Intel HD Graphics 530                                                     | 7         | 0.81%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                     | 7         | 0.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 7         | 0.81%   |
| Nvidia TU117M                                                             | 6         | 0.7%    |
| Nvidia GP108M [GeForce MX150]                                             | 6         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 6         | 0.7%    |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 6         | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 6         | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 6         | 0.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 6         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 6         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 323       | 48.87%  |
| Intel + Nvidia     | 144       | 21.79%  |
| 1 x AMD            | 117       | 17.7%   |
| Intel + AMD        | 24        | 3.63%   |
| AMD + Nvidia       | 23        | 3.48%   |
| 1 x Nvidia         | 18        | 2.72%   |
| 2 x Intel          | 3         | 0.45%   |
| 2 x AMD            | 3         | 0.45%   |
| 1 x Zhaoxin        | 3         | 0.45%   |
| Other              | 2         | 0.3%    |
| 1 x Silicon Motion | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 533       | 80.51%  |
| Proprietary | 110       | 16.62%  |
| Unknown     | 19        | 2.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 555       | 83.46%  |
| 0.01-0.5   | 45        | 6.77%   |
| 1.01-2.0   | 33        | 4.96%   |
| 3.01-4.0   | 13        | 1.95%   |
| 0.51-1.0   | 12        | 1.8%    |
| 5.01-6.0   | 4         | 0.6%    |
| 7.01-8.0   | 2         | 0.3%    |
| 8.01-16.0  | 1         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 158       | 20.13%  |
| BOE                     | 120       | 15.29%  |
| Chimei Innolux          | 104       | 13.25%  |
| LG Display              | 80        | 10.19%  |
| Samsung Electronics     | 76        | 9.68%   |
| Sharp                   | 27        | 3.44%   |
| Goldstar                | 25        | 3.18%   |
| Dell                    | 23        | 2.93%   |
| Apple                   | 23        | 2.93%   |
| PANDA                   | 16        | 2.04%   |
| CSO                     | 15        | 1.91%   |
| Hewlett-Packard         | 12        | 1.53%   |
| Lenovo                  | 10        | 1.27%   |
| InfoVision              | 10        | 1.27%   |
| Acer                    | 8         | 1.02%   |
| Ancor Communications    | 7         | 0.89%   |
| Sony                    | 6         | 0.76%   |
| BenQ                    | 6         | 0.76%   |
| Chi Mei Optoelectronics | 5         | 0.64%   |
| Philips                 | 4         | 0.51%   |
| AOC                     | 4         | 0.51%   |
| ViewSonic               | 3         | 0.38%   |
| LG Philips              | 3         | 0.38%   |
| Iiyama                  | 3         | 0.38%   |
| Denver                  | 3         | 0.38%   |
| ASUSTek Computer        | 3         | 0.38%   |
| Vestel Elektronik       | 2         | 0.25%   |
| Unknown                 | 2         | 0.25%   |
| Panasonic               | 2         | 0.25%   |
| HJC                     | 2         | 0.25%   |
| WST                     | 1         | 0.13%   |
| Wacom                   | 1         | 0.13%   |
| Unknown (XXX)           | 1         | 0.13%   |
| Tianma XM               | 1         | 0.13%   |
| Seiki                   | 1         | 0.13%   |
| Sceptre Tech            | 1         | 0.13%   |
| Quanta Display          | 1         | 0.13%   |
| ONN                     | 1         | 0.13%   |
| NEC Computers           | 1         | 0.13%   |
| MStar                   | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 11        | 1.39%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 7         | 0.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 0.89%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch        | 7         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.76%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 5         | 0.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 5         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 4         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 0.51%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 4         | 0.51%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 4         | 0.51%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO5799 1920x1080 344x194mm 15.5-inch        | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 4         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4172 2880x1800 289x186mm 13.5-inch | 3         | 0.38%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 3         | 0.38%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 3         | 0.38%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 3         | 0.38%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 0.38%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 3         | 0.38%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                 | 3         | 0.38%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO333D 1920x1080 309x174mm 14.0-inch        | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO0BA2 2560x1440 309x174mm 14.0-inch        | 3         | 0.38%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 3         | 0.38%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                         | 2         | 0.25%   |
| Sony TV SNY4502 1920x1080                                             | 2         | 0.25%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                         | 2         | 0.25%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch               | 2         | 0.25%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.25%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 2         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 335       | 45.7%   |
| 1366x768 (WXGA)    | 157       | 21.42%  |
| 3840x2160 (4K)     | 36        | 4.91%   |
| 2560x1440 (QHD)    | 25        | 3.41%   |
| 1600x900 (HD+)     | 25        | 3.41%   |
| 2560x1600          | 23        | 3.14%   |
| 1920x1200 (WUXGA)  | 23        | 3.14%   |
| 2880x1800          | 22        | 3%      |
| 1280x800 (WXGA)    | 19        | 2.59%   |
| 3440x1440          | 12        | 1.64%   |
| 3840x2400          | 10        | 1.36%   |
| 1440x900 (WXGA+)   | 8         | 1.09%   |
| 1280x1024 (SXGA)   | 5         | 0.68%   |
| 2240x1400          | 4         | 0.55%   |
| 1680x1050 (WSXGA+) | 4         | 0.55%   |
| 2560x1080          | 3         | 0.41%   |
| 2256x1504          | 3         | 0.41%   |
| 2160x1440          | 3         | 0.41%   |
| 3840x1600          | 2         | 0.27%   |
| 3456x2160          | 2         | 0.27%   |
| 3200x1800 (QHD+)   | 2         | 0.27%   |
| 2520x1680          | 2         | 0.27%   |
| 3072x1920          | 1         | 0.14%   |
| 3000x2000          | 1         | 0.14%   |
| 2880x1620          | 1         | 0.14%   |
| 2304x1440          | 1         | 0.14%   |
| 1920x550           | 1         | 0.14%   |
| 1920x540           | 1         | 0.14%   |
| 1920x1280          | 1         | 0.14%   |
| 1024x768 (XGA)     | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 287       | 36.61%  |
| 13      | 127       | 16.2%   |
| 14      | 114       | 14.54%  |
| 17      | 52        | 6.63%   |
| 27      | 30        | 3.83%   |
| 16      | 27        | 3.44%   |
| 23      | 18        | 2.3%    |
| 12      | 17        | 2.17%   |
| 24      | 15        | 1.91%   |
| 21      | 15        | 1.91%   |
| 34      | 12        | 1.53%   |
| 11      | 12        | 1.53%   |
| 31      | 6         | 0.77%   |
| Unknown | 6         | 0.77%   |
| 72      | 5         | 0.64%   |
| 20      | 5         | 0.64%   |
| 40      | 4         | 0.51%   |
| 25      | 4         | 0.51%   |
| 22      | 4         | 0.51%   |
| 84      | 3         | 0.38%   |
| 35      | 3         | 0.38%   |
| 19      | 3         | 0.38%   |
| 54      | 2         | 0.26%   |
| 37      | 2         | 0.26%   |
| 18      | 2         | 0.26%   |
| 58      | 1         | 0.13%   |
| 52      | 1         | 0.13%   |
| 49      | 1         | 0.13%   |
| 42      | 1         | 0.13%   |
| 32      | 1         | 0.13%   |
| 28      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |
| 10      | 1         | 0.13%   |
| 8       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 470       | 60.49%  |
| 201-300     | 103       | 13.26%  |
| 501-600     | 65        | 8.37%   |
| 351-400     | 62        | 7.98%   |
| 401-500     | 26        | 3.35%   |
| 701-800     | 13        | 1.67%   |
| 801-900     | 9         | 1.16%   |
| 601-700     | 8         | 1.03%   |
| 1501-2000   | 8         | 1.03%   |
| Unknown     | 6         | 0.77%   |
| 1001-1500   | 5         | 0.64%   |
| 101-200     | 1         | 0.13%   |
| 901-1000    | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 527       | 77.27%  |
| 16/10   | 116       | 17.01%  |
| 21/9    | 17        | 2.49%   |
| 3/2     | 10        | 1.47%   |
| 5/4     | 5         | 0.73%   |
| 32/9    | 2         | 0.29%   |
| Unknown | 2         | 0.29%   |
| 6/5     | 1         | 0.15%   |
| 4/3     | 1         | 0.15%   |
| 0.62    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 286       | 36.43%  |
| 81-90          | 191       | 24.33%  |
| 71-80          | 47        | 5.99%   |
| 121-130        | 46        | 5.86%   |
| 201-250        | 45        | 5.73%   |
| 301-350        | 31        | 3.95%   |
| 111-120        | 27        | 3.44%   |
| 351-500        | 23        | 2.93%   |
| 61-70          | 16        | 2.04%   |
| More than 1000 | 13        | 1.66%   |
| 51-60          | 12        | 1.53%   |
| 151-200        | 12        | 1.53%   |
| 251-300        | 8         | 1.02%   |
| 501-1000       | 7         | 0.89%   |
| Unknown        | 6         | 0.76%   |
| 91-100         | 5         | 0.64%   |
| 141-150        | 4         | 0.51%   |
| 131-140        | 4         | 0.51%   |
| 41-50          | 1         | 0.13%   |
| 1-40           | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 328       | 42.76%  |
| 101-120       | 186       | 24.25%  |
| 161-240       | 98        | 12.78%  |
| 51-100        | 98        | 12.78%  |
| More than 240 | 43        | 5.61%   |
| 1-50          | 8         | 1.04%   |
| Unknown       | 6         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 512       | 76.88%  |
| 2     | 115       | 17.27%  |
| 0     | 21        | 3.15%   |
| 3     | 17        | 2.55%   |
| 4     | 1         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 369       | 36.5%   |
| Realtek Semiconductor             | 329       | 32.54%  |
| Qualcomm Atheros                  | 92        | 9.1%    |
| Broadcom                          | 49        | 4.85%   |
| MediaTek                          | 42        | 4.15%   |
| Broadcom Limited                  | 15        | 1.48%   |
| ASIX Electronics                  | 13        | 1.29%   |
| TP-Link                           | 11        | 1.09%   |
| DisplayLink                       | 9         | 0.89%   |
| Lenovo                            | 8         | 0.79%   |
| Ralink                            | 7         | 0.69%   |
| Xiaomi                            | 6         | 0.59%   |
| Marvell Technology Group          | 6         | 0.59%   |
| Sierra Wireless                   | 5         | 0.49%   |
| Qualcomm                          | 5         | 0.49%   |
| Hewlett-Packard                   | 4         | 0.4%    |
| Dell                              | 4         | 0.4%    |
| Ralink Technology                 | 3         | 0.3%    |
| JMicron Technology                | 3         | 0.3%    |
| Samsung Electronics               | 2         | 0.2%    |
| Nvidia                            | 2         | 0.2%    |
| Huawei Technologies               | 2         | 0.2%    |
| Google                            | 2         | 0.2%    |
| Ericsson Business Mobile Networks | 2         | 0.2%    |
| ASUSTek Computer                  | 2         | 0.2%    |
| Apple                             | 2         | 0.2%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.1%    |
| Vimtron Electronics               | 1         | 0.1%    |
| U-Blox                            | 1         | 0.1%    |
| TRENDnet                          | 1         | 0.1%    |
| Tenda                             | 1         | 0.1%    |
| Quectel Wireless Solutions        | 1         | 0.1%    |
| Qualcomm Technologies             | 1         | 0.1%    |
| OPPO Electronics                  | 1         | 0.1%    |
| NetGear                           | 1         | 0.1%    |
| Motorola PCS                      | 1         | 0.1%    |
| MosChip Semiconductor             | 1         | 0.1%    |
| ICS Advent                        | 1         | 0.1%    |
| Flipper Devices                   | 1         | 0.1%    |
| Edimax Technology                 | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 174       | 14.54%  |
| Intel Wi-Fi 6 AX201                                               | 46        | 3.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43        | 3.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 37        | 3.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 31        | 2.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 2.51%   |
| Intel Wireless 8265 / 8275                                        | 28        | 2.34%   |
| Intel Wi-Fi 6 AX200                                               | 28        | 2.34%   |
| Intel Wireless 8260                                               | 25        | 2.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 1.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 20        | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 19        | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 18        | 1.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 1.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 1.42%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 16        | 1.34%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 16        | 1.34%   |
| Intel Wireless 7265                                               | 16        | 1.34%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 16        | 1.34%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 1.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 13        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 12        | 1%      |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 11        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                     | 10        | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 9         | 0.75%   |
| Intel Wireless 7260                                               | 8         | 0.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 0.58%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 7         | 0.58%   |
| Intel Wireless 3165                                               | 6         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.5%    |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 357       | 52.04%  |
| Realtek Semiconductor      | 111       | 16.18%  |
| Qualcomm Atheros           | 84        | 12.24%  |
| Broadcom                   | 41        | 5.98%   |
| MediaTek                   | 39        | 5.69%   |
| Broadcom Limited           | 11        | 1.6%    |
| TP-Link                    | 10        | 1.46%   |
| Ralink                     | 7         | 1.02%   |
| Sierra Wireless            | 5         | 0.73%   |
| Qualcomm                   | 5         | 0.73%   |
| Ralink Technology          | 3         | 0.44%   |
| Dell                       | 2         | 0.29%   |
| ASUSTek Computer           | 2         | 0.29%   |
| TRENDnet                   | 1         | 0.15%   |
| Tenda                      | 1         | 0.15%   |
| Quectel Wireless Solutions | 1         | 0.15%   |
| Qualcomm Technologies      | 1         | 0.15%   |
| NetGear                    | 1         | 0.15%   |
| Edimax Technology          | 1         | 0.15%   |
| D-Link System              | 1         | 0.15%   |
| D-Link                     | 1         | 0.15%   |
| Belkin Components          | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 46        | 6.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 37        | 5.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 31        | 4.49%   |
| Intel Wireless 8265 / 8275                                     | 28        | 4.05%   |
| Intel Wi-Fi 6 AX200                                            | 28        | 4.05%   |
| Intel Wireless 8260                                            | 25        | 3.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20        | 2.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 20        | 2.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 19        | 2.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 18        | 2.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 18        | 2.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 16        | 2.32%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 16        | 2.32%   |
| Intel Wireless 7265                                            | 16        | 2.32%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 16        | 2.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 15        | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13        | 1.88%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 13        | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 13        | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 1.45%   |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 1.3%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 9         | 1.3%    |
| Intel Wireless 7260                                            | 8         | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 7         | 1.01%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 7         | 1.01%   |
| Intel Wireless 3165                                            | 6         | 0.87%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 6         | 0.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 0.87%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 5         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 0.72%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 5         | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 0.72%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 5         | 0.72%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 0.72%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 0.72%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 268       | 54.58%  |
| Intel                      | 118       | 24.03%  |
| Qualcomm Atheros           | 17        | 3.46%   |
| Broadcom                   | 17        | 3.46%   |
| ASIX Electronics           | 13        | 2.65%   |
| DisplayLink                | 9         | 1.83%   |
| Lenovo                     | 8         | 1.63%   |
| Xiaomi                     | 6         | 1.22%   |
| Marvell Technology Group   | 6         | 1.22%   |
| Broadcom Limited           | 5         | 1.02%   |
| MediaTek                   | 3         | 0.61%   |
| JMicron Technology         | 3         | 0.61%   |
| TP-Link                    | 2         | 0.41%   |
| Samsung Electronics        | 2         | 0.41%   |
| Nvidia                     | 2         | 0.41%   |
| Google                     | 2         | 0.41%   |
| Apple                      | 2         | 0.41%   |
| ZTE WCDMA Technologies MSM | 1         | 0.2%    |
| Vimtron Electronics        | 1         | 0.2%    |
| OPPO Electronics           | 1         | 0.2%    |
| Motorola PCS               | 1         | 0.2%    |
| MosChip Semiconductor      | 1         | 0.2%    |
| ICS Advent                 | 1         | 0.2%    |
| Huawei Technologies        | 1         | 0.2%    |
| Hewlett-Packard            | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 174       | 35.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43        | 8.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 6.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 3.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 3.43%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 3.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 2.62%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 11        | 2.22%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 1.21%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 1.21%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 1.21%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.01%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.01%   |
| Realtek Killer E3000 2.5GbE Controller                            | 4         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.81%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.81%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.6%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 3         | 0.6%    |
| MediaTek moto g22                                                 | 3         | 0.6%    |
| Lenovo USB-C Dock Ethernet                                        | 3         | 0.6%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.6%    |
| Intel Ethernet Connection I219-V                                  | 3         | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.6%    |
| Intel Ethernet Connection (13) I219-V                             | 3         | 0.6%    |
| DisplayLink USB3.0 Display                                        | 3         | 0.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.6%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.6%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.4%    |
| Realtek PCIe GbE Family Controller                                | 2         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.4%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.4%    |
| Nvidia MCP79 Ethernet                                             | 2         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 653       | 58.41%  |
| Ethernet | 455       | 40.7%   |
| Modem    | 9         | 0.81%   |
| Unknown  | 1         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 547       | 79.97%  |
| Ethernet | 137       | 20.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 391       | 59.15%  |
| 1     | 262       | 39.64%  |
| 3     | 5         | 0.76%   |
| 0     | 3         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 463       | 69.73%  |
| Yes  | 201       | 30.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 310       | 53.36%  |
| Realtek Semiconductor           | 65        | 11.19%  |
| Qualcomm Atheros Communications | 39        | 6.71%   |
| Foxconn / Hon Hai               | 29        | 4.99%   |
| IMC Networks                    | 28        | 4.82%   |
| Lite-On Technology              | 21        | 3.61%   |
| Broadcom                        | 18        | 3.1%    |
| Apple                           | 18        | 3.1%    |
| Realtek                         | 12        | 2.07%   |
| Cambridge Silicon Radio         | 7         | 1.2%    |
| Dell                            | 6         | 1.03%   |
| Hewlett-Packard                 | 5         | 0.86%   |
| Toshiba                         | 4         | 0.69%   |
| Ralink                          | 4         | 0.69%   |
| ASUSTek Computer                | 4         | 0.69%   |
| USI                             | 3         | 0.52%   |
| Opticis                         | 2         | 0.34%   |
| TP-Link                         | 1         | 0.17%   |
| Ralink Technology               | 1         | 0.17%   |
| Fujitsu                         | 1         | 0.17%   |
| Edimax Technology               | 1         | 0.17%   |
| Chicony Electronics             | 1         | 0.17%   |
| Actions                         | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 87        | 14.97%  |
| Intel Bluetooth wireless interface                                                  | 82        | 14.11%  |
| Realtek Bluetooth Radio                                                             | 53        | 9.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 51        | 8.78%   |
| Intel Bluetooth Device                                                              | 42        | 7.23%   |
| Intel AX200 Bluetooth                                                               | 26        | 4.48%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 19        | 3.27%   |
| IMC Networks Wireless_Device                                                        | 17        | 2.93%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 13        | 2.24%   |
| Realtek 802.11ac WLAN Adapter                                                       | 11        | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 10        | 1.72%   |
| IMC Networks Bluetooth Radio                                                        | 10        | 1.72%   |
| Apple Bluetooth USB Host Controller                                                 | 10        | 1.72%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 9         | 1.55%   |
| Apple Bluetooth Host Controller                                                     | 8         | 1.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 7         | 1.2%    |
| Intel AX210 Bluetooth                                                               | 7         | 1.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 1.2%    |
| Lite-On Bluetooth Device                                                            | 6         | 1.03%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 5         | 0.86%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 5         | 0.86%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 0.86%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 0.69%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 0.69%   |
| Lite-On Wireless_Device                                                             | 4         | 0.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 0.69%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 0.69%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 0.69%   |
| USI Bluetooth Device                                                                | 3         | 0.52%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.52%   |
| ASUS ASUS USB-BT500                                                                 | 3         | 0.52%   |
| Toshiba BCM43142A0                                                                  | 2         | 0.34%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.34%   |
| Opticis Bluetooth Radio                                                             | 2         | 0.34%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.34%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.34%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 518       | 61.3%   |
| AMD                                          | 144       | 17.04%  |
| Nvidia                                       | 114       | 13.49%  |
| Realtek Semiconductor                        | 9         | 1.07%   |
| C-Media Electronics                          | 9         | 1.07%   |
| Lenovo                                       | 8         | 0.95%   |
| GN Netcom                                    | 7         | 0.83%   |
| Plantronics                                  | 4         | 0.47%   |
| Zhaoxin                                      | 3         | 0.36%   |
| Generalplus Technology                       | 3         | 0.36%   |
| VIA Technologies                             | 2         | 0.24%   |
| Razer USA                                    | 2         | 0.24%   |
| Focusrite-Novation                           | 2         | 0.24%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.12%   |
| Texas Instruments                            | 1         | 0.12%   |
| Superlux digit                               | 1         | 0.12%   |
| Sennheiser Communications                    | 1         | 0.12%   |
| Native Instruments                           | 1         | 0.12%   |
| Microsoft                                    | 1         | 0.12%   |
| M-Audio                                      | 1         | 0.12%   |
| Logitech                                     | 1         | 0.12%   |
| Kingston Technology                          | 1         | 0.12%   |
| JMTek                                        | 1         | 0.12%   |
| Jieli Technology                             | 1         | 0.12%   |
| Huawei Technologies                          | 1         | 0.12%   |
| DSEA A/S                                     | 1         | 0.12%   |
| DCMT Technology                              | 1         | 0.12%   |
| Creative Technology                          | 1         | 0.12%   |
| Corsair                                      | 1         | 0.12%   |
| Blue Microphones                             | 1         | 0.12%   |
| BEHRINGER International                      | 1         | 0.12%   |
| Apple                                        | 1         | 0.12%   |
| Antlion Audio                                | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 101       | 9.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 79        | 7.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 60        | 5.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 59        | 5.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 42        | 4.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 41        | 4.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 32        | 3.15%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 28        | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 25        | 2.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 24        | 2.36%   |
| Intel Broadwell-U Audio Controller                                         | 24        | 2.36%   |
| Intel Haswell-ULT HD Audio Controller                                      | 21        | 2.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 21        | 2.07%   |
| Intel 8 Series HD Audio Controller                                         | 21        | 2.07%   |
| Nvidia Audio device                                                        | 19        | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 18        | 1.77%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 17        | 1.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 16        | 1.58%   |
| Nvidia GA106 High Definition Audio Controller                              | 16        | 1.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 15        | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 15        | 1.48%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 14        | 1.38%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 14        | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14        | 1.38%   |
| AMD FCH Azalia Controller                                                  | 13        | 1.28%   |
| Intel CM238 HD Audio Controller                                            | 10        | 0.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 9         | 0.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 0.89%   |
| Realtek Semiconductor USB Audio                                            | 8         | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 8         | 0.79%   |
| AMD Kabini HDMI/DP Audio                                                   | 8         | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 0.69%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 0.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6         | 0.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 0.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 102       | 25.82%  |
| SK hynix            | 86        | 21.77%  |
| Micron Technology   | 72        | 18.23%  |
| Kingston            | 32        | 8.1%    |
| Crucial             | 18        | 4.56%   |
| Unknown             | 14        | 3.54%   |
| A-DATA Technology   | 9         | 2.28%   |
| Ramaxel Technology  | 8         | 2.03%   |
| Smart               | 7         | 1.77%   |
| Unknown (ABCD)      | 6         | 1.52%   |
| Elpida              | 5         | 1.27%   |
| Transcend           | 3         | 0.76%   |
| Timetec             | 3         | 0.76%   |
| Shenzhen WODPOSIT   | 3         | 0.76%   |
| Corsair             | 3         | 0.76%   |
| Unknown             | 3         | 0.76%   |
| PNY                 | 2         | 0.51%   |
| Patriot             | 2         | 0.51%   |
| GOODRAM             | 2         | 0.51%   |
| G.Skill             | 2         | 0.51%   |
| Unknown (0x0CDC)    | 1         | 0.25%   |
| Teikon              | 1         | 0.25%   |
| Saikano             | 1         | 0.25%   |
| PUSKILL             | 1         | 0.25%   |
| Nanya Technology    | 1         | 0.25%   |
| Kingmax             | 1         | 0.25%   |
| KINGBANK            | 1         | 0.25%   |
| Gold Key            | 1         | 0.25%   |
| fef5                | 1         | 0.25%   |
| ChangXin Memory     | 1         | 0.25%   |
| ASint Technology    | 1         | 0.25%   |
| Apacer              | 1         | 0.25%   |
| AMD                 | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 7         | 1.69%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 6         | 1.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.21%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 5         | 1.21%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.21%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.97%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.97%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.97%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.97%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.97%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 4         | 0.97%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 4         | 0.97%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.97%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.72%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.72%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 3         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.72%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 3         | 0.72%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s            | 3         | 0.72%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB SODIMM LPDDR5 6400MT/s           | 3         | 0.72%   |
| Micron RAM MT40A512M16LY-075:E 4GB SODIMM DDR4 3200MT/s          | 3         | 0.72%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.72%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.72%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 3         | 0.72%   |
| Unknown                                                          | 3         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.48%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 2         | 0.48%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.48%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 2         | 0.48%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.48%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.48%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.48%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 2         | 0.48%   |
| SK hynix RAM HMCG66AGBSA095N 8GB SODIMM DDR5 5600MT/s            | 2         | 0.48%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.48%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.48%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.48%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.48%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 168       | 49.12%  |
| DDR3    | 65        | 19.01%  |
| LPDDR4  | 34        | 9.94%   |
| LPDDR5  | 31        | 9.06%   |
| DDR5    | 25        | 7.31%   |
| LPDDR3  | 10        | 2.92%   |
| DDR2    | 5         | 1.46%   |
| SDRAM   | 3         | 0.88%   |
| Unknown | 1         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 270       | 78.26%  |
| Row Of Chips | 66        | 19.13%  |
| Chip         | 5         | 1.45%   |
| Unknown      | 4         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 176       | 47.44%  |
| 4096  | 87        | 23.45%  |
| 16384 | 66        | 17.79%  |
| 2048  | 22        | 5.93%   |
| 32768 | 15        | 4.04%   |
| 1024  | 4         | 1.08%   |
| 1536  | 1         | 0.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 101       | 27.75%  |
| 1600    | 56        | 15.38%  |
| 2667    | 54        | 14.84%  |
| 6400    | 29        | 7.97%   |
| 2400    | 22        | 6.04%   |
| 4800    | 20        | 5.49%   |
| 4267    | 19        | 5.22%   |
| 2133    | 14        | 3.85%   |
| 1333    | 7         | 1.92%   |
| 5600    | 5         | 1.37%   |
| 1334    | 5         | 1.37%   |
| 1867    | 4         | 1.1%    |
| 3733    | 3         | 0.82%   |
| 2666    | 3         | 0.82%   |
| 8400    | 2         | 0.55%   |
| 5500    | 2         | 0.55%   |
| 4266    | 2         | 0.55%   |
| 3266    | 2         | 0.55%   |
| 2048    | 2         | 0.55%   |
| 975     | 2         | 0.55%   |
| 667     | 2         | 0.55%   |
| Unknown | 2         | 0.55%   |
| 5200    | 1         | 0.27%   |
| 4199    | 1         | 0.27%   |
| 2933    | 1         | 0.27%   |
| 1067    | 1         | 0.27%   |
| 800     | 1         | 0.27%   |
| 533     | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 50%     |
| Samsung Electronics | 1         | 16.67%  |
| Canon               | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 1         | 16.67%  |
| HP LaserJet Pro M201dw               | 1         | 16.67%  |
| HP LaserJet P2015 series             | 1         | 16.67%  |
| HP DeskJet 4100 series               | 1         | 16.67%  |
| Canon TS3100 series                  | 1         | 16.67%  |
| Brother HL-2250DN Laser Printer      | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 8800F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 129       | 21.5%   |
| IMC Networks                           | 65        | 10.83%  |
| Microdia                               | 61        | 10.17%  |
| Quanta                                 | 57        | 9.5%    |
| Realtek Semiconductor                  | 52        | 8.67%   |
| Bison Electronics                      | 33        | 5.5%    |
| Sunplus Innovation Technology          | 28        | 4.67%   |
| Luxvisions Innotech Limited            | 28        | 4.67%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 2.83%   |
| Apple                                  | 16        | 2.67%   |
| Sonix Technology                       | 14        | 2.33%   |
| Lite-On Technology                     | 13        | 2.17%   |
| Syntek                                 | 12        | 2%      |
| Acer                                   | 12        | 2%      |
| Suyin                                  | 7         | 1.17%   |
| Alcor Micro                            | 7         | 1.17%   |
| Logitech                               | 6         | 1%      |
| Importek                               | 6         | 1%      |
| Silicon Motion                         | 5         | 0.83%   |
| ShineTech                              | 5         | 0.83%   |
| SunplusIT                              | 3         | 0.5%    |
| Shine-optics                           | 3         | 0.5%    |
| Samsung Electronics                    | 3         | 0.5%    |
| Microsoft                              | 3         | 0.5%    |
| icSpring                               | 3         | 0.5%    |
| Lenovo                                 | 2         | 0.33%   |
| Google                                 | 2         | 0.33%   |
| Sunplus Technology                     | 1         | 0.17%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.17%   |
| Ricoh                                  | 1         | 0.17%   |
| Pixart Imaging                         | 1         | 0.17%   |
| OmniVision Technologies                | 1         | 0.17%   |
| Foxconn / Hon Hai                      | 1         | 0.17%   |
| BKX-210918                             | 1         | 0.17%   |
| ALi                                    | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 42        | 6.94%   |
| Microdia Integrated_Webcam_HD                                  | 33        | 5.45%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 21        | 3.47%   |
| IMC Networks Integrated Camera                                 | 20        | 3.31%   |
| Realtek Integrated_Webcam_HD                                   | 16        | 2.64%   |
| Chicony HP HD Camera                                           | 15        | 2.48%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 11        | 1.82%   |
| Quanta HD User Facing                                          | 10        | 1.65%   |
| Syntek Integrated Camera                                       | 9         | 1.49%   |
| Sonix USB2.0 HD UVC WebCam                                     | 9         | 1.49%   |
| Bison Integrated Camera                                        | 9         | 1.49%   |
| Sunplus Integrated_Webcam_HD                                   | 8         | 1.32%   |
| Quanta ov9734_techfront_camera                                 | 8         | 1.32%   |
| Chicony HP Truevision HD                                       | 8         | 1.32%   |
| Chicony HD WebCam                                              | 8         | 1.32%   |
| Chicony HD User Facing                                         | 7         | 1.16%   |
| Realtek USB Camera                                             | 6         | 0.99%   |
| Quanta HD Camera                                               | 6         | 0.99%   |
| Lite-On Integrated Camera                                      | 6         | 0.99%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 5         | 0.83%   |
| Realtek Integrated Webcam_HD                                   | 5         | 0.83%   |
| Quanta HP TrueVision HD Camera                                 | 5         | 0.83%   |
| Quanta HP HD Camera                                            | 5         | 0.83%   |
| Quanta HD Webcam                                               | 5         | 0.83%   |
| Luxvisions Innotech Limited Integrated RGB Camera              | 5         | 0.83%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 5         | 0.83%   |
| IMC Networks HD Camera                                         | 5         | 0.83%   |
| Chicony TOSHIBA Web Camera - HD                                | 5         | 0.83%   |
| Chicony HP Wide Vision HD Camera                               | 5         | 0.83%   |
| Apple FaceTime HD Camera                                       | 5         | 0.83%   |
| Realtek MTD camera                                             | 4         | 0.66%   |
| Realtek Integrated Webcam HD                                   | 4         | 0.66%   |
| Quanta ACER HD User Facing                                     | 4         | 0.66%   |
| Microdia Laptop_Integrated_Webcam_E4HD                         | 4         | 0.66%   |
| Luxvisions Innotech Limited Integrated Camera                  | 4         | 0.66%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 4         | 0.66%   |
| Lite-On HP HD Camera                                           | 4         | 0.66%   |
| IMC Networks Integrated RGB Camera                             | 4         | 0.66%   |
| Chicony HP Truevision HD camera                                | 4         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 42        | 29.58%  |
| Shenzhen Goodix Technology         | 39        | 27.46%  |
| Synaptics                          | 32        | 22.54%  |
| Elan Microelectronics              | 13        | 9.15%   |
| Upek                               | 4         | 2.82%   |
| LighTuning Technology              | 4         | 2.82%   |
| AuthenTec                          | 4         | 2.82%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.11%   |
| Focal-systems.Corp                 | 1         | 0.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 30        | 21.13%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 6.34%   |
| Elan ELAN:ARM-M4                                                           | 8         | 5.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 4.93%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 4.93%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 4.93%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 4.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.23%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 4.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 3.52%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 3.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 2.82%   |
| Elan WBF Fingerprint Sensor                                                | 4         | 2.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.11%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.11%   |
| Synaptics UWP WBDI Device                                                  | 3         | 2.11%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 2.11%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.41%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.41%   |
| AuthenTec AES2810                                                          | 2         | 1.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.7%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.7%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.7%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.7%    |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.7%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.7%    |
| Synaptics WBDI                                                             | 1         | 0.7%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.7%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.7%    |
| Elan ELAN:Fingerprint                                                      | 1         | 0.7%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.7%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.7%    |
| Unknown                                                                    | 1         | 0.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 27        | 61.36%  |
| Alcor Micro           | 12        | 27.27%  |
| Upek                  | 3         | 6.82%   |
| Hewlett-Packard       | 1         | 2.27%   |
| Advanced Card Systems | 1         | 2.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 13        | 29.55%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 27.27%  |
| Broadcom 58200                                                               | 7         | 15.91%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 13.64%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 6.82%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 2.27%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.27%   |
| Advanced Card Systems ACR122U                                                | 1         | 2.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 359       | 53.74%  |
| 1     | 238       | 35.63%  |
| 2     | 56        | 8.38%   |
| 3     | 9         | 1.35%   |
| 4     | 5         | 0.75%   |
| 10    | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 142       | 37.97%  |
| Graphics card            | 83        | 22.19%  |
| Chipcard                 | 42        | 11.23%  |
| Camera                   | 28        | 7.49%   |
| Net/wireless             | 27        | 7.22%   |
| Multimedia controller    | 24        | 6.42%   |
| Sound                    | 6         | 1.6%    |
| Bluetooth                | 6         | 1.6%    |
| Storage                  | 5         | 1.34%   |
| Net/ethernet             | 3         | 0.8%    |
| Card reader              | 3         | 0.8%    |
| Communication controller | 2         | 0.53%   |
| Unassigned class         | 1         | 0.27%   |
| Network                  | 1         | 0.27%   |
| Modem                    | 1         | 0.27%   |

