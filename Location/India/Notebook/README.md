Linux in India - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in India.

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

Total: 4635

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [c336f9aa8c](https://linux-hardware.org/?probe=c336f9aa8c) | Aug 11, 2023 |
| HP            | Pavilion Notebook           | [980f6773f8](https://linux-hardware.org/?probe=980f6773f8) | Aug 10, 2023 |
| HP            | Pavilion Laptop 14-dv2xx... | [479f066821](https://linux-hardware.org/?probe=479f066821) | Aug 10, 2023 |
| Apple         | MacBookPro9,2               | [e703bb179f](https://linux-hardware.org/?probe=e703bb179f) | Aug 10, 2023 |
| Valve         | Jupiter                     | [eee501d93c](https://linux-hardware.org/?probe=eee501d93c) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eec04bec1d](https://linux-hardware.org/?probe=eec04bec1d) | Aug 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c9c978701a](https://linux-hardware.org/?probe=c9c978701a) | Aug 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [f69459e15a](https://linux-hardware.org/?probe=f69459e15a) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [58446ba97c](https://linux-hardware.org/?probe=58446ba97c) | Aug 08, 2023 |
| MSI           | GL63 8RC                    | [d91d6193e6](https://linux-hardware.org/?probe=d91d6193e6) | Aug 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | [ebcf58253e](https://linux-hardware.org/?probe=ebcf58253e) | Aug 07, 2023 |
| HP            | ProBook 640 G2              | [8dae611904](https://linux-hardware.org/?probe=8dae611904) | Aug 06, 2023 |
| Dell          | Inspiron 15-3552            | [91376cc583](https://linux-hardware.org/?probe=91376cc583) | Aug 06, 2023 |
| HP            | EliteBook 840 G4            | [44d851d327](https://linux-hardware.org/?probe=44d851d327) | Aug 06, 2023 |
| Dell          | Inspiron 7572               | [2509709a1e](https://linux-hardware.org/?probe=2509709a1e) | Aug 06, 2023 |
| Dell          | Precision 3571              | [fdbbd33ee6](https://linux-hardware.org/?probe=fdbbd33ee6) | Aug 06, 2023 |
| Dell          | Precision 3571              | [76de48bd02](https://linux-hardware.org/?probe=76de48bd02) | Aug 06, 2023 |
| Dell          | Inspiron 3542               | [6af70944d8](https://linux-hardware.org/?probe=6af70944d8) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | [1790fa9d72](https://linux-hardware.org/?probe=1790fa9d72) | Aug 05, 2023 |
| HP            | 15                          | [77ae1d8e7e](https://linux-hardware.org/?probe=77ae1d8e7e) | Aug 05, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | [771a45e46f](https://linux-hardware.org/?probe=771a45e46f) | Aug 05, 2023 |
| Fujitsu       | LIFEBOOK LH532              | [ba3a2e1773](https://linux-hardware.org/?probe=ba3a2e1773) | Aug 04, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| HP            | Compaq Presario CQ40        | [c5ea71f927](https://linux-hardware.org/?probe=c5ea71f927) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [082f92da07](https://linux-hardware.org/?probe=082f92da07) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [1078db460a](https://linux-hardware.org/?probe=1078db460a) | Aug 04, 2023 |
| Dell          | Vostro 3405                 | [db4954c21d](https://linux-hardware.org/?probe=db4954c21d) | Aug 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [0cf8e99478](https://linux-hardware.org/?probe=0cf8e99478) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | [38f33f3878](https://linux-hardware.org/?probe=38f33f3878) | Aug 03, 2023 |
| Alienware     | 14                          | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | Notebook                    | [258f6a82ad](https://linux-hardware.org/?probe=258f6a82ad) | Aug 02, 2023 |
| Dell          | Inspiron 1545               | [97d2508df2](https://linux-hardware.org/?probe=97d2508df2) | Aug 02, 2023 |
| Dell          | Inspiron 15-3552            | [2019699cac](https://linux-hardware.org/?probe=2019699cac) | Aug 02, 2023 |
| Acer          | Nitro AN515-45              | [5523e61097](https://linux-hardware.org/?probe=5523e61097) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [32d205bbdf](https://linux-hardware.org/?probe=32d205bbdf) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [6fe0b53a1b](https://linux-hardware.org/?probe=6fe0b53a1b) | Aug 02, 2023 |
| Dell          | Latitude E7470              | [d377538364](https://linux-hardware.org/?probe=d377538364) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [5650f66cd4](https://linux-hardware.org/?probe=5650f66cd4) | Jul 31, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [ff6816b285](https://linux-hardware.org/?probe=ff6816b285) | Jul 31, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [f641b9c622](https://linux-hardware.org/?probe=f641b9c622) | Jul 30, 2023 |
| Dell          | Latitude E5270              | [ae07c57989](https://linux-hardware.org/?probe=ae07c57989) | Jul 30, 2023 |
| MSI           | Bravo 15 B5DD               | [d9d3f5bce4](https://linux-hardware.org/?probe=d9d3f5bce4) | Jul 30, 2023 |
| Lenovo        | G500s 20245                 | [eff9350e7f](https://linux-hardware.org/?probe=eff9350e7f) | Jul 29, 2023 |
| Dell          | Inspiron 5593               | [6a6420b23e](https://linux-hardware.org/?probe=6a6420b23e) | Jul 29, 2023 |
| Dell          | Precision 3550              | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [2f6969a3c9](https://linux-hardware.org/?probe=2f6969a3c9) | Jul 27, 2023 |
| MSI           | Alpha 15 B5EEK              | [d6a4c29101](https://linux-hardware.org/?probe=d6a4c29101) | Jul 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CJC... | [d7fa33e7b1](https://linux-hardware.org/?probe=d7fa33e7b1) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [1bac11c715](https://linux-hardware.org/?probe=1bac11c715) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [1409af2a38](https://linux-hardware.org/?probe=1409af2a38) | Jul 26, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [866a4197cd](https://linux-hardware.org/?probe=866a4197cd) | Jul 26, 2023 |
| Acer          | Aspire A715-42G             | [a6abe36eef](https://linux-hardware.org/?probe=a6abe36eef) | Jul 26, 2023 |
| Acer          | Aspire A515-57G             | [8a297cb644](https://linux-hardware.org/?probe=8a297cb644) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [82a990b785](https://linux-hardware.org/?probe=82a990b785) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [dc97ca175a](https://linux-hardware.org/?probe=dc97ca175a) | Jul 25, 2023 |
| HP            | ENVY Notebook               | [9ab8362949](https://linux-hardware.org/?probe=9ab8362949) | Jul 25, 2023 |
| Timi          | Mi NoteBook Ultra           | [e1fea727ff](https://linux-hardware.org/?probe=e1fea727ff) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | [61646d77f1](https://linux-hardware.org/?probe=61646d77f1) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [8377b87a66](https://linux-hardware.org/?probe=8377b87a66) | Jul 24, 2023 |
| ASUSTek       | X541UV                      | [eb0aac9c32](https://linux-hardware.org/?probe=eb0aac9c32) | Jul 24, 2023 |
| Acer          | Aspire A315-59              | [8ecb2eb1fc](https://linux-hardware.org/?probe=8ecb2eb1fc) | Jul 24, 2023 |
| Lenovo        | E41-25 81FS                 | [d9f18f8f28](https://linux-hardware.org/?probe=d9f18f8f28) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [e822964466](https://linux-hardware.org/?probe=e822964466) | Jul 24, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [313f3aa210](https://linux-hardware.org/?probe=313f3aa210) | Jul 23, 2023 |
| Dell          | Latitude 3490               | [8988026686](https://linux-hardware.org/?probe=8988026686) | Jul 23, 2023 |
| Dell          | Latitude 3490               | [b7f8f886f8](https://linux-hardware.org/?probe=b7f8f886f8) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [6c0c0671df](https://linux-hardware.org/?probe=6c0c0671df) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cc08425e5b](https://linux-hardware.org/?probe=cc08425e5b) | Jul 22, 2023 |
| Dell          | Inspiron 3558               | [2cad6d3cb7](https://linux-hardware.org/?probe=2cad6d3cb7) | Jul 22, 2023 |
| Timi          | Mi NoteBook Horizon Edit... | [72a5dfb7cd](https://linux-hardware.org/?probe=72a5dfb7cd) | Jul 21, 2023 |
| Lenovo        | Z50-70 20354                | [33150ea27b](https://linux-hardware.org/?probe=33150ea27b) | Jul 21, 2023 |
| Timi          | Mi NoteBook Ultra           | [6bb2b5bfb6](https://linux-hardware.org/?probe=6bb2b5bfb6) | Jul 20, 2023 |
| HP            | EliteBook 840 G5            | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [061efe2135](https://linux-hardware.org/?probe=061efe2135) | Jul 20, 2023 |
| Acer          | Nitro AN515-58              | [18a6e9f055](https://linux-hardware.org/?probe=18a6e9f055) | Jul 20, 2023 |
| HP            | Pavilion Notebook           | [d366e7101c](https://linux-hardware.org/?probe=d366e7101c) | Jul 20, 2023 |
| AVITA         | NS14A6                      | [594afbeb74](https://linux-hardware.org/?probe=594afbeb74) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [77468bcff7](https://linux-hardware.org/?probe=77468bcff7) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [eb7b37c1d2](https://linux-hardware.org/?probe=eb7b37c1d2) | Jul 19, 2023 |
| HP            | Notebook                    | [2ccf016245](https://linux-hardware.org/?probe=2ccf016245) | Jul 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [38c5f4d547](https://linux-hardware.org/?probe=38c5f4d547) | Jul 19, 2023 |
| Dell          | Precision 3581              | [68d58784d5](https://linux-hardware.org/?probe=68d58784d5) | Jul 18, 2023 |
| Dell          | Latitude 5480               | [30aaaf3ba8](https://linux-hardware.org/?probe=30aaaf3ba8) | Jul 18, 2023 |
| Dell          | Latitude 3590               | [6386a869e5](https://linux-hardware.org/?probe=6386a869e5) | Jul 18, 2023 |
| Acer          | Predator PH315-53           | [3d0b2577a1](https://linux-hardware.org/?probe=3d0b2577a1) | Jul 18, 2023 |
| Dell          | Latitude 7480               | [83caa544f7](https://linux-hardware.org/?probe=83caa544f7) | Jul 18, 2023 |
| Dell          | Latitude 7480               | [526e020c94](https://linux-hardware.org/?probe=526e020c94) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d43ad7594c](https://linux-hardware.org/?probe=d43ad7594c) | Jul 16, 2023 |
| HP            | 15                          | [73b0c0312f](https://linux-hardware.org/?probe=73b0c0312f) | Jul 15, 2023 |
| Timi          | Mi NoteBook Ultra           | [94f963ff8c](https://linux-hardware.org/?probe=94f963ff8c) | Jul 15, 2023 |
| Lenovo        | G50-70 20351                | [b8481d7a4c](https://linux-hardware.org/?probe=b8481d7a4c) | Jul 14, 2023 |
| Dell          | Latitude 5480               | [c74dc748f5](https://linux-hardware.org/?probe=c74dc748f5) | Jul 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1e2b959156](https://linux-hardware.org/?probe=1e2b959156) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [e042e7c94e](https://linux-hardware.org/?probe=e042e7c94e) | Jul 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [76513f6a7d](https://linux-hardware.org/?probe=76513f6a7d) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [934947072a](https://linux-hardware.org/?probe=934947072a) | Jul 13, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [d5079cefe1](https://linux-hardware.org/?probe=d5079cefe1) | Jul 13, 2023 |
| MSI           | Katana GF66 11UC            | [d22ab22240](https://linux-hardware.org/?probe=d22ab22240) | Jul 13, 2023 |
| Acer          | Nitro AN515-58              | [b31130eea6](https://linux-hardware.org/?probe=b31130eea6) | Jul 13, 2023 |
| Timi          | Mi NoteBook Ultra           | [04c4e233af](https://linux-hardware.org/?probe=04c4e233af) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| Dell          | Inspiron 5590               | [f3c9995017](https://linux-hardware.org/?probe=f3c9995017) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [aea754f076](https://linux-hardware.org/?probe=aea754f076) | Jul 11, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [05f889dc1a](https://linux-hardware.org/?probe=05f889dc1a) | Jul 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [37bc760339](https://linux-hardware.org/?probe=37bc760339) | Jul 11, 2023 |
| Acer          | Nitro AN515-58              | [76d89b3b3b](https://linux-hardware.org/?probe=76d89b3b3b) | Jul 11, 2023 |
| Dell          | Inspiron 1545               | [50ed801045](https://linux-hardware.org/?probe=50ed801045) | Jul 11, 2023 |
| HP            | Pavilion - 14-CE2068ST      | [bdf8b67813](https://linux-hardware.org/?probe=bdf8b67813) | Jul 10, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [806e14ad19](https://linux-hardware.org/?probe=806e14ad19) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3a1baa8f6c](https://linux-hardware.org/?probe=3a1baa8f6c) | Jul 09, 2023 |
| HP            | Notebook                    | [a1c37a6a4b](https://linux-hardware.org/?probe=a1c37a6a4b) | Jul 09, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [ce4fed4466](https://linux-hardware.org/?probe=ce4fed4466) | Jul 08, 2023 |
| Dell          | Latitude E5440              | [9b4a70fe2b](https://linux-hardware.org/?probe=9b4a70fe2b) | Jul 08, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [629f165835](https://linux-hardware.org/?probe=629f165835) | Jul 07, 2023 |
| Dell          | Inspiron 3543               | [b7459d1653](https://linux-hardware.org/?probe=b7459d1653) | Jul 07, 2023 |
| HP            | ProBook 4525s               | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| HP            | Laptop                      | [30a1d8ec1c](https://linux-hardware.org/?probe=30a1d8ec1c) | Jul 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e555b073b5](https://linux-hardware.org/?probe=e555b073b5) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [b11fe33b8c](https://linux-hardware.org/?probe=b11fe33b8c) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | [f5f96d51ed](https://linux-hardware.org/?probe=f5f96d51ed) | Jul 05, 2023 |
| HP            | Laptop 14s-ef1xxx           | [14e321559e](https://linux-hardware.org/?probe=14e321559e) | Jul 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a889efa719](https://linux-hardware.org/?probe=a889efa719) | Jul 04, 2023 |
| MSI           | GF63 Thin 11UC              | [86c82575ec](https://linux-hardware.org/?probe=86c82575ec) | Jul 04, 2023 |
| Dell          | Precision 3581              | [1d4db3cec3](https://linux-hardware.org/?probe=1d4db3cec3) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [dfd66d3d07](https://linux-hardware.org/?probe=dfd66d3d07) | Jul 03, 2023 |
| ASUSTek       | X541UAK                     | [c4dcbea71d](https://linux-hardware.org/?probe=c4dcbea71d) | Jul 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [da24c07da6](https://linux-hardware.org/?probe=da24c07da6) | Jul 02, 2023 |
| HP            | EliteBook 820 G3            | [09c7b86b2c](https://linux-hardware.org/?probe=09c7b86b2c) | Jul 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [835f3a390f](https://linux-hardware.org/?probe=835f3a390f) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [3271b3b559](https://linux-hardware.org/?probe=3271b3b559) | Jul 02, 2023 |
| HONOR         | NMH-WCX9                    | [a8caf9af8e](https://linux-hardware.org/?probe=a8caf9af8e) | Jul 02, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [0c4c59cf86](https://linux-hardware.org/?probe=0c4c59cf86) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | [d0fc2ea58e](https://linux-hardware.org/?probe=d0fc2ea58e) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | [8b5dc3456b](https://linux-hardware.org/?probe=8b5dc3456b) | Jul 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [0aed51f639](https://linux-hardware.org/?probe=0aed51f639) | Jul 01, 2023 |
| Infinix       | INBOOK X2 PLUS              | [9a74f19725](https://linux-hardware.org/?probe=9a74f19725) | Jul 01, 2023 |
| Acer          | Aspire E5-575G              | [f127804b4a](https://linux-hardware.org/?probe=f127804b4a) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [10467d9f3e](https://linux-hardware.org/?probe=10467d9f3e) | Jun 30, 2023 |
| HP            | 15                          | [2d80407689](https://linux-hardware.org/?probe=2d80407689) | Jun 30, 2023 |
| HP            | 15                          | [398d659d8c](https://linux-hardware.org/?probe=398d659d8c) | Jun 30, 2023 |
| Acer          | Aspire E5-575               | [602d134940](https://linux-hardware.org/?probe=602d134940) | Jun 30, 2023 |
| Dell          | Inspiron N5010              | [eab5331f66](https://linux-hardware.org/?probe=eab5331f66) | Jun 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0f0defbd9c](https://linux-hardware.org/?probe=0f0defbd9c) | Jun 29, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | [0086cae258](https://linux-hardware.org/?probe=0086cae258) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [5d30ae9d05](https://linux-hardware.org/?probe=5d30ae9d05) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6a29eda577](https://linux-hardware.org/?probe=6a29eda577) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bf4abd6e9e](https://linux-hardware.org/?probe=bf4abd6e9e) | Jun 28, 2023 |
| Dell          | Inspiron 3543               | [4baea798b1](https://linux-hardware.org/?probe=4baea798b1) | Jun 27, 2023 |
| Acer          | Swift SFG14-71              | [f66ac636e6](https://linux-hardware.org/?probe=f66ac636e6) | Jun 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [fc7f2b378b](https://linux-hardware.org/?probe=fc7f2b378b) | Jun 27, 2023 |
| Dell          | Inspiron 1545               | [d6b3d5cb90](https://linux-hardware.org/?probe=d6b3d5cb90) | Jun 27, 2023 |
| Acer          | Aspire A715-51G             | [08ba4bf92b](https://linux-hardware.org/?probe=08ba4bf92b) | Jun 26, 2023 |
| Acer          | Aspire A715-51G             | [3dc15705c8](https://linux-hardware.org/?probe=3dc15705c8) | Jun 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA    | [8a764f6629](https://linux-hardware.org/?probe=8a764f6629) | Jun 26, 2023 |
| HP            | Laptop 14s-dq2xxx           | [23499b1838](https://linux-hardware.org/?probe=23499b1838) | Jun 25, 2023 |
| Acer          | Aspire E5-575G              | [2f5357533f](https://linux-hardware.org/?probe=2f5357533f) | Jun 25, 2023 |
| Lenovo        | E41-55 82FJ                 | [f725e1bd1a](https://linux-hardware.org/?probe=f725e1bd1a) | Jun 25, 2023 |
| Dell          | Precision M6400             | [b68c09e274](https://linux-hardware.org/?probe=b68c09e274) | Jun 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | [14cc9e067f](https://linux-hardware.org/?probe=14cc9e067f) | Jun 25, 2023 |
| Dell          | Precision 5540              | [7d6c1fe39d](https://linux-hardware.org/?probe=7d6c1fe39d) | Jun 25, 2023 |
| Dell          | Inspiron 1545               | [7f8217bce2](https://linux-hardware.org/?probe=7f8217bce2) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [5679200535](https://linux-hardware.org/?probe=5679200535) | Jun 24, 2023 |
| Dell          | Vostro 2520                 | [9279842ec3](https://linux-hardware.org/?probe=9279842ec3) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [628fca0448](https://linux-hardware.org/?probe=628fca0448) | Jun 24, 2023 |
| Dell          | Inspiron 15 3515            | [77473ea84c](https://linux-hardware.org/?probe=77473ea84c) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [de0580cf77](https://linux-hardware.org/?probe=de0580cf77) | Jun 24, 2023 |
| HP            | Pavilion g6                 | [b8d79ce295](https://linux-hardware.org/?probe=b8d79ce295) | Jun 24, 2023 |
| Dell          | G5 5505                     | [dbe52869d7](https://linux-hardware.org/?probe=dbe52869d7) | Jun 23, 2023 |
| Lenovo        | G500s 20245                 | [515f5a5392](https://linux-hardware.org/?probe=515f5a5392) | Jun 23, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [15fd4078ea](https://linux-hardware.org/?probe=15fd4078ea) | Jun 23, 2023 |
| Lenovo        | G500s 20245                 | [4d9c9f9bd0](https://linux-hardware.org/?probe=4d9c9f9bd0) | Jun 23, 2023 |
| Dell          | G5 5505                     | [f435440e91](https://linux-hardware.org/?probe=f435440e91) | Jun 23, 2023 |
| Acer          | Aspire E5-575G              | [5c76172491](https://linux-hardware.org/?probe=5c76172491) | Jun 22, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | [110c366456](https://linux-hardware.org/?probe=110c366456) | Jun 22, 2023 |
| HP            | 250 G6 Notebook PC          | [7cc301b3f7](https://linux-hardware.org/?probe=7cc301b3f7) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | [baab7764b1](https://linux-hardware.org/?probe=baab7764b1) | Jun 21, 2023 |
| Acer          | Aspire R3-131T              | [ab7c961e2b](https://linux-hardware.org/?probe=ab7c961e2b) | Jun 21, 2023 |
| HP            | 250 G6 Notebook PC          | [1ba2e18bc1](https://linux-hardware.org/?probe=1ba2e18bc1) | Jun 21, 2023 |
| MSI           | Bravo 15 B5DD               | [c80413d259](https://linux-hardware.org/?probe=c80413d259) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | [3375eaaeb3](https://linux-hardware.org/?probe=3375eaaeb3) | Jun 20, 2023 |
| Dell          | Precision 5560              | [ee53248c8c](https://linux-hardware.org/?probe=ee53248c8c) | Jun 20, 2023 |
| Lenovo        | ThinkPad T460s 20F9005BU... | [59a527c934](https://linux-hardware.org/?probe=59a527c934) | Jun 20, 2023 |
| Timi          | RedmiBook 15                | [f975205ebd](https://linux-hardware.org/?probe=f975205ebd) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [6dea148dd7](https://linux-hardware.org/?probe=6dea148dd7) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | [63381e724a](https://linux-hardware.org/?probe=63381e724a) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| HP            | ProBook 440 G4              | [4b20fef62f](https://linux-hardware.org/?probe=4b20fef62f) | Jun 19, 2023 |
| Dell          | Vostro 1015                 | [e195f838c3](https://linux-hardware.org/?probe=e195f838c3) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [4907b6927a](https://linux-hardware.org/?probe=4907b6927a) | Jun 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [edd82d072b](https://linux-hardware.org/?probe=edd82d072b) | Jun 16, 2023 |
| HP            | EliteBook 2540p             | [20ddd7a28b](https://linux-hardware.org/?probe=20ddd7a28b) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| Dell          | Inspiron 15-3567            | [69048c54c9](https://linux-hardware.org/?probe=69048c54c9) | Jun 14, 2023 |
| HP            | ProBook 430 G4              | [fe39c9b2ce](https://linux-hardware.org/?probe=fe39c9b2ce) | Jun 14, 2023 |
| HP            | ProBook 430 G4              | [2b4d088695](https://linux-hardware.org/?probe=2b4d088695) | Jun 14, 2023 |
| Lenovo        | E41-25 81FS                 | [fffb0a25f1](https://linux-hardware.org/?probe=fffb0a25f1) | Jun 13, 2023 |
| Dell          | Vostro 3420                 | [1ede32fb28](https://linux-hardware.org/?probe=1ede32fb28) | Jun 13, 2023 |
| Dell          | XPS 17 9710                 | [9ab7a065c4](https://linux-hardware.org/?probe=9ab7a065c4) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [5e636c4693](https://linux-hardware.org/?probe=5e636c4693) | Jun 13, 2023 |
| Acer          | Aspire ES1-572              | [e6713db4c3](https://linux-hardware.org/?probe=e6713db4c3) | Jun 12, 2023 |
| Lenovo        | E41-25 81FS                 | [a192769f1b](https://linux-hardware.org/?probe=a192769f1b) | Jun 11, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [66aa96212a](https://linux-hardware.org/?probe=66aa96212a) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1d46e48d92](https://linux-hardware.org/?probe=1d46e48d92) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [1eeb12a5ca](https://linux-hardware.org/?probe=1eeb12a5ca) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [e46f2fe66e](https://linux-hardware.org/?probe=e46f2fe66e) | Jun 10, 2023 |
| HP            | G42                         | [83eca37118](https://linux-hardware.org/?probe=83eca37118) | Jun 10, 2023 |
| HP            | Laptop 15-db0xxx            | [5dd8c1fed8](https://linux-hardware.org/?probe=5dd8c1fed8) | Jun 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| Valve         | Jupiter                     | [b23bc1dc48](https://linux-hardware.org/?probe=b23bc1dc48) | Jun 08, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [fb6aca39d9](https://linux-hardware.org/?probe=fb6aca39d9) | Jun 08, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [e103817b2d](https://linux-hardware.org/?probe=e103817b2d) | Jun 07, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [6062ee64a9](https://linux-hardware.org/?probe=6062ee64a9) | Jun 07, 2023 |
| Dell          | G15 5511                    | [ddee46cbfa](https://linux-hardware.org/?probe=ddee46cbfa) | Jun 07, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [721ff5908a](https://linux-hardware.org/?probe=721ff5908a) | Jun 06, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Dell          | Latitude E6430              | [bfa5da5406](https://linux-hardware.org/?probe=bfa5da5406) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [1e5a50fa47](https://linux-hardware.org/?probe=1e5a50fa47) | Jun 06, 2023 |
| Acer          | Aspire A314-36M             | [7cab0d1591](https://linux-hardware.org/?probe=7cab0d1591) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [503bc1f4cc](https://linux-hardware.org/?probe=503bc1f4cc) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [31a814cd0e](https://linux-hardware.org/?probe=31a814cd0e) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [2a612dc748](https://linux-hardware.org/?probe=2a612dc748) | Jun 06, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [5159be9e2b](https://linux-hardware.org/?probe=5159be9e2b) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Sony          | VPCEH25EN                   | [2b47c1b9a5](https://linux-hardware.org/?probe=2b47c1b9a5) | Jun 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [6528b4bffe](https://linux-hardware.org/?probe=6528b4bffe) | Jun 05, 2023 |
| Dell          | Latitude 3460               | [1a92cd0779](https://linux-hardware.org/?probe=1a92cd0779) | Jun 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [dbc9b8df0b](https://linux-hardware.org/?probe=dbc9b8df0b) | Jun 05, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [ceab55a00c](https://linux-hardware.org/?probe=ceab55a00c) | Jun 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| AVITA         | NS14A8                      | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [87b33e1181](https://linux-hardware.org/?probe=87b33e1181) | Jun 04, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [1e4ffa48ce](https://linux-hardware.org/?probe=1e4ffa48ce) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [e86a159ec5](https://linux-hardware.org/?probe=e86a159ec5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [01cd20c83d](https://linux-hardware.org/?probe=01cd20c83d) | Jun 03, 2023 |
| Dell          | Inspiron 5490               | [a0cc355293](https://linux-hardware.org/?probe=a0cc355293) | Jun 03, 2023 |
| Acer          | Aspire ES1-523              | [a080a07f52](https://linux-hardware.org/?probe=a080a07f52) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b8c8f96b56](https://linux-hardware.org/?probe=b8c8f96b56) | Jun 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [13adb1e221](https://linux-hardware.org/?probe=13adb1e221) | Jun 02, 2023 |
| Acer          | Nitro AN515-42              | [0acaadb3d1](https://linux-hardware.org/?probe=0acaadb3d1) | Jun 01, 2023 |
| HP            | ProBook 440 G4              | [af2f742bc5](https://linux-hardware.org/?probe=af2f742bc5) | Jun 01, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [b7032438d2](https://linux-hardware.org/?probe=b7032438d2) | May 31, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [2c315764a9](https://linux-hardware.org/?probe=2c315764a9) | May 31, 2023 |
| Dell          | Inspiron 5559               | [6c814f5bb5](https://linux-hardware.org/?probe=6c814f5bb5) | May 31, 2023 |
| Toshiba       | Satellite L850              | [cee0a13d3f](https://linux-hardware.org/?probe=cee0a13d3f) | May 31, 2023 |
| Dell          | Inspiron 15-3567            | [dc6256036e](https://linux-hardware.org/?probe=dc6256036e) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [7653baa0f8](https://linux-hardware.org/?probe=7653baa0f8) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [89bb5ff663](https://linux-hardware.org/?probe=89bb5ff663) | May 29, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [087565aed3](https://linux-hardware.org/?probe=087565aed3) | May 29, 2023 |
| Acer          | Aspire A515-56              | [108833c92b](https://linux-hardware.org/?probe=108833c92b) | May 29, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [c5b13d6ea2](https://linux-hardware.org/?probe=c5b13d6ea2) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| Dell          | Inspiron 3542               | [423fe90cad](https://linux-hardware.org/?probe=423fe90cad) | May 28, 2023 |
| HP            | EliteBook 840 G1            | [a1aa06298d](https://linux-hardware.org/?probe=a1aa06298d) | May 28, 2023 |
| Acer          | Aspire A515-56              | [4d8767d94b](https://linux-hardware.org/?probe=4d8767d94b) | May 28, 2023 |
| HP            | Laptop 14s-dk0xxx           | [902b837f1a](https://linux-hardware.org/?probe=902b837f1a) | May 27, 2023 |
| Dell          | Latitude 7480               | [2c74ec8198](https://linux-hardware.org/?probe=2c74ec8198) | May 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | [5cf35078b0](https://linux-hardware.org/?probe=5cf35078b0) | May 26, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [0316f8d274](https://linux-hardware.org/?probe=0316f8d274) | May 25, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [270540781d](https://linux-hardware.org/?probe=270540781d) | May 25, 2023 |
| Acer          | Aspire A715-51G             | [53cbfa6255](https://linux-hardware.org/?probe=53cbfa6255) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1fea1a6529](https://linux-hardware.org/?probe=1fea1a6529) | May 25, 2023 |
| Dell          | Vostro 3480                 | [490c47960a](https://linux-hardware.org/?probe=490c47960a) | May 25, 2023 |
| MSI           | GF63 Thin 9RC               | [aef2c48b64](https://linux-hardware.org/?probe=aef2c48b64) | May 24, 2023 |
| Dell          | Vostro 3480                 | [ae4f8dba2c](https://linux-hardware.org/?probe=ae4f8dba2c) | May 24, 2023 |
| Dell          | Vostro 2420                 | [ebff669275](https://linux-hardware.org/?probe=ebff669275) | May 24, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [e8bc14fc34](https://linux-hardware.org/?probe=e8bc14fc34) | May 23, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [c5615351bb](https://linux-hardware.org/?probe=c5615351bb) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [691b17e221](https://linux-hardware.org/?probe=691b17e221) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [d704fd9efd](https://linux-hardware.org/?probe=d704fd9efd) | May 23, 2023 |
| Dell          | Inspiron 5575               | [7d93944943](https://linux-hardware.org/?probe=7d93944943) | May 23, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [33773ecf4d](https://linux-hardware.org/?probe=33773ecf4d) | May 22, 2023 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [7d81e00b27](https://linux-hardware.org/?probe=7d81e00b27) | May 22, 2023 |
| Lenovo        | ThinkPad T440p              | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro9,2               | [88d77ec57e](https://linux-hardware.org/?probe=88d77ec57e) | May 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [59464cac80](https://linux-hardware.org/?probe=59464cac80) | May 20, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [ff730fcbf6](https://linux-hardware.org/?probe=ff730fcbf6) | May 20, 2023 |
| Apple         | MacBookAir7,2               | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| HP            | Laptop 15s-dr3xxx           | [4c44db2d32](https://linux-hardware.org/?probe=4c44db2d32) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [b0ed659e7d](https://linux-hardware.org/?probe=b0ed659e7d) | May 19, 2023 |
| Dell          | Inspiron 14 5408            | [c1853f7df2](https://linux-hardware.org/?probe=c1853f7df2) | May 17, 2023 |
| HP            | Pavilion g6                 | [da7af17667](https://linux-hardware.org/?probe=da7af17667) | May 17, 2023 |
| HP            | Laptop 15s-du0xxx           | [ddc3152cbc](https://linux-hardware.org/?probe=ddc3152cbc) | May 17, 2023 |
| MSI           | GF63 Thin 9RC               | [b8f2e92853](https://linux-hardware.org/?probe=b8f2e92853) | May 16, 2023 |
| Dell          | XPS 13 9350                 | [3e34d3a71c](https://linux-hardware.org/?probe=3e34d3a71c) | May 15, 2023 |
| HP            | Laptop 14s-dk0xxx           | [000f3c2444](https://linux-hardware.org/?probe=000f3c2444) | May 15, 2023 |
| HONOR         | NMH-WCX9                    | [b938ce8d64](https://linux-hardware.org/?probe=b938ce8d64) | May 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [fb4bda01b7](https://linux-hardware.org/?probe=fb4bda01b7) | May 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0060b3cb1c](https://linux-hardware.org/?probe=0060b3cb1c) | May 14, 2023 |
| Lenovo        | E41-25 81FS                 | [b9e5026a6a](https://linux-hardware.org/?probe=b9e5026a6a) | May 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [4a322b398b](https://linux-hardware.org/?probe=4a322b398b) | May 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [d251ccd249](https://linux-hardware.org/?probe=d251ccd249) | May 13, 2023 |
| Dell          | Inspiron 7520               | [d06731c12e](https://linux-hardware.org/?probe=d06731c12e) | May 13, 2023 |
| Dell          | G3 3590                     | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| AVITA         | NS14A6                      | [253f084ba1](https://linux-hardware.org/?probe=253f084ba1) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c9597b5b24](https://linux-hardware.org/?probe=c9597b5b24) | May 11, 2023 |
| Dell          | Latitude E5470              | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| AVITA         | NS14A6                      | [d2cdbff22c](https://linux-hardware.org/?probe=d2cdbff22c) | May 11, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [328d899b1c](https://linux-hardware.org/?probe=328d899b1c) | May 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [601a09abf6](https://linux-hardware.org/?probe=601a09abf6) | May 10, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | [0308c5d0c5](https://linux-hardware.org/?probe=0308c5d0c5) | May 10, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d2d1037c9d](https://linux-hardware.org/?probe=d2d1037c9d) | May 09, 2023 |
| Dell          | Latitude 3490               | [f9ed2aa5ab](https://linux-hardware.org/?probe=f9ed2aa5ab) | May 09, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [745096932c](https://linux-hardware.org/?probe=745096932c) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [dfe5f362e2](https://linux-hardware.org/?probe=dfe5f362e2) | May 09, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [cbc45e8ffa](https://linux-hardware.org/?probe=cbc45e8ffa) | May 09, 2023 |
| HP            | Laptop 15-da1xxx            | [e1313af3e6](https://linux-hardware.org/?probe=e1313af3e6) | May 08, 2023 |
| Acer          | Aspire A315-53              | [c74bb83ac9](https://linux-hardware.org/?probe=c74bb83ac9) | May 08, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [f5acf4a186](https://linux-hardware.org/?probe=f5acf4a186) | May 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7e003cf7a9](https://linux-hardware.org/?probe=7e003cf7a9) | May 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b1b0fa7485](https://linux-hardware.org/?probe=b1b0fa7485) | May 07, 2023 |
| Dell          | Vostro 15-3568              | [08b1152328](https://linux-hardware.org/?probe=08b1152328) | May 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [741b9f90e1](https://linux-hardware.org/?probe=741b9f90e1) | May 07, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [1dbc92c072](https://linux-hardware.org/?probe=1dbc92c072) | May 07, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [845c2112be](https://linux-hardware.org/?probe=845c2112be) | May 06, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [3569e8fb31](https://linux-hardware.org/?probe=3569e8fb31) | May 06, 2023 |
| Dell          | Inspiron 3537               | [5b49eec8c6](https://linux-hardware.org/?probe=5b49eec8c6) | May 06, 2023 |
| HP            | EliteBook Folio 9470m       | [20461b100d](https://linux-hardware.org/?probe=20461b100d) | May 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [834d2304aa](https://linux-hardware.org/?probe=834d2304aa) | May 06, 2023 |
| HP            | Laptop 15-db1xxx            | [dd6f6a940f](https://linux-hardware.org/?probe=dd6f6a940f) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | [c7b66fbdc3](https://linux-hardware.org/?probe=c7b66fbdc3) | May 05, 2023 |
| Acer          | Aspire E5-576               | [a73b11b28f](https://linux-hardware.org/?probe=a73b11b28f) | May 05, 2023 |
| HP            | ProBook 440 G5              | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS0SE00     | [c5d4b5a3a7](https://linux-hardware.org/?probe=c5d4b5a3a7) | May 05, 2023 |
| Sony          | SVE15117FNW                 | [7ec421e4a1](https://linux-hardware.org/?probe=7ec421e4a1) | May 04, 2023 |
| Dell          | Inspiron 1545               | [e60b96481a](https://linux-hardware.org/?probe=e60b96481a) | May 04, 2023 |
| Gateway       | NE46R                       | [05291d9029](https://linux-hardware.org/?probe=05291d9029) | May 04, 2023 |
| Dell          | Latitude 5490               | [2ce70b7a2c](https://linux-hardware.org/?probe=2ce70b7a2c) | May 04, 2023 |
| HP            | ProBook 440 G4              | [ac499d5a17](https://linux-hardware.org/?probe=ac499d5a17) | May 04, 2023 |
| Dell          | Latitude 5480               | [a8b85d06d8](https://linux-hardware.org/?probe=a8b85d06d8) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [530aaeef9d](https://linux-hardware.org/?probe=530aaeef9d) | May 02, 2023 |
| Dell          | Inspiron 1564               | [e94ef67ab2](https://linux-hardware.org/?probe=e94ef67ab2) | May 01, 2023 |
| Dell          | Inspiron 14 5420            | [cc65b3de6f](https://linux-hardware.org/?probe=cc65b3de6f) | May 01, 2023 |
| Acer          | Aspire A715-51G             | [842333a8da](https://linux-hardware.org/?probe=842333a8da) | May 01, 2023 |
| Acer          | Aspire A715-51G             | [4f72daaab8](https://linux-hardware.org/?probe=4f72daaab8) | May 01, 2023 |
| Dell          | Latitude E5420              | [df8c9e7f40](https://linux-hardware.org/?probe=df8c9e7f40) | Apr 30, 2023 |
| Apple         | MacBook5,1                  | [7077a00b02](https://linux-hardware.org/?probe=7077a00b02) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [446a548122](https://linux-hardware.org/?probe=446a548122) | Apr 30, 2023 |
| Dell          | Inspiron N5110              | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| Acer          | Nitro AN515-58              | [2c335c5bfb](https://linux-hardware.org/?probe=2c335c5bfb) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [0ea5e1926e](https://linux-hardware.org/?probe=0ea5e1926e) | Apr 29, 2023 |
| Dell          | Latitude E5470              | [c6c943679f](https://linux-hardware.org/?probe=c6c943679f) | Apr 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [216a4b9b67](https://linux-hardware.org/?probe=216a4b9b67) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [6736f3d911](https://linux-hardware.org/?probe=6736f3d911) | Apr 28, 2023 |
| Acer          | Swift SF314-512             | [2ba1bab0fe](https://linux-hardware.org/?probe=2ba1bab0fe) | Apr 28, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | [65f390b956](https://linux-hardware.org/?probe=65f390b956) | Apr 28, 2023 |
| Acer          | Nitro AN515-54              | [000022b2dd](https://linux-hardware.org/?probe=000022b2dd) | Apr 28, 2023 |
| MSI           | Modern 14 C7M               | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Dell          | Inspiron 1545               | [a23cf53cec](https://linux-hardware.org/?probe=a23cf53cec) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [4bdb6b2a7f](https://linux-hardware.org/?probe=4bdb6b2a7f) | Apr 27, 2023 |
| Dell          | Vostro 1550                 | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| Valve         | Jupiter                     | [7ab7e066cf](https://linux-hardware.org/?probe=7ab7e066cf) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| HP            | EliteBook Folio 9470m       | [e0d69966e9](https://linux-hardware.org/?probe=e0d69966e9) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [ab52633e07](https://linux-hardware.org/?probe=ab52633e07) | Apr 26, 2023 |
| Timi          | Mi NoteBook Ultra           | [b6b7cdfe22](https://linux-hardware.org/?probe=b6b7cdfe22) | Apr 25, 2023 |
| Lenovo        | ThinkPad E14 20RAS1DB00     | [8e09a153f5](https://linux-hardware.org/?probe=8e09a153f5) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [45199e8296](https://linux-hardware.org/?probe=45199e8296) | Apr 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [2787d97e6e](https://linux-hardware.org/?probe=2787d97e6e) | Apr 24, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [8bfea5add2](https://linux-hardware.org/?probe=8bfea5add2) | Apr 24, 2023 |
| HP            | G42                         | [58b0a0981e](https://linux-hardware.org/?probe=58b0a0981e) | Apr 23, 2023 |
| HP            | Laptop 15s-du3xxx           | [45af810de1](https://linux-hardware.org/?probe=45af810de1) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [888b7bed45](https://linux-hardware.org/?probe=888b7bed45) | Apr 21, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [8578f44f47](https://linux-hardware.org/?probe=8578f44f47) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [91999697ba](https://linux-hardware.org/?probe=91999697ba) | Apr 20, 2023 |
| Acer          | Aspire 5745                 | [19e6d70ce0](https://linux-hardware.org/?probe=19e6d70ce0) | Apr 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHS... | [59d7ef5ddd](https://linux-hardware.org/?probe=59d7ef5ddd) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | [46ade409df](https://linux-hardware.org/?probe=46ade409df) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | [954388c5e0](https://linux-hardware.org/?probe=954388c5e0) | Apr 19, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0W    | [97447a0777](https://linux-hardware.org/?probe=97447a0777) | Apr 19, 2023 |
| HP            | Pavilion 15                 | [3a855386b4](https://linux-hardware.org/?probe=3a855386b4) | Apr 18, 2023 |
| MSI           | GP65 Leopard 10SEK          | [3b852bad57](https://linux-hardware.org/?probe=3b852bad57) | Apr 18, 2023 |
| Lenovo        | E41-25 81FS                 | [10bfabc1b8](https://linux-hardware.org/?probe=10bfabc1b8) | Apr 18, 2023 |
| HP            | 630                         | [daeae9f12e](https://linux-hardware.org/?probe=daeae9f12e) | Apr 18, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9be6e0f395](https://linux-hardware.org/?probe=9be6e0f395) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | [d1d3cf9928](https://linux-hardware.org/?probe=d1d3cf9928) | Apr 17, 2023 |
| HP            | Laptop 15-da0xxx            | [786daebed0](https://linux-hardware.org/?probe=786daebed0) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| Dell          | Vostro 3580                 | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [0dfc78d12a](https://linux-hardware.org/?probe=0dfc78d12a) | Apr 15, 2023 |
| Apple         | MacBookPro16,1              | [bc7d49c64c](https://linux-hardware.org/?probe=bc7d49c64c) | Apr 15, 2023 |
| Acer          | AO756                       | [c17d5276ec](https://linux-hardware.org/?probe=c17d5276ec) | Apr 14, 2023 |
| Acer          | Aspire A515-57G             | [42e4889a44](https://linux-hardware.org/?probe=42e4889a44) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | [0d0ff5240b](https://linux-hardware.org/?probe=0d0ff5240b) | Apr 12, 2023 |
| ASUSTek       | K53U                        | [19ec753136](https://linux-hardware.org/?probe=19ec753136) | Apr 12, 2023 |
| Dell          | Precision 5520              | [32eb960b25](https://linux-hardware.org/?probe=32eb960b25) | Apr 12, 2023 |
| MSI           | GF63 Thin 9SCXR             | [3225aa17d2](https://linux-hardware.org/?probe=3225aa17d2) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [40c7ac46e2](https://linux-hardware.org/?probe=40c7ac46e2) | Apr 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b9d22dfaea](https://linux-hardware.org/?probe=b9d22dfaea) | Apr 10, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [0bbe9702ca](https://linux-hardware.org/?probe=0bbe9702ca) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [c82c56c81e](https://linux-hardware.org/?probe=c82c56c81e) | Apr 09, 2023 |
| Dell          | Latitude 7275               | [d1a55f8f55](https://linux-hardware.org/?probe=d1a55f8f55) | Apr 09, 2023 |
| HONOR         | NMH-WCX9                    | [51c8f59aeb](https://linux-hardware.org/?probe=51c8f59aeb) | Apr 08, 2023 |
| Dell          | Latitude 3410               | [9fd7d9d439](https://linux-hardware.org/?probe=9fd7d9d439) | Apr 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [133568abf2](https://linux-hardware.org/?probe=133568abf2) | Apr 07, 2023 |
| ASUSTek       | K54C                        | [4f37849c94](https://linux-hardware.org/?probe=4f37849c94) | Apr 07, 2023 |
| Apple         | MacBookPro9,2               | [f29d8154a2](https://linux-hardware.org/?probe=f29d8154a2) | Apr 06, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [fef3cbc941](https://linux-hardware.org/?probe=fef3cbc941) | Apr 05, 2023 |
| Valve         | Jupiter                     | [8425bb5da3](https://linux-hardware.org/?probe=8425bb5da3) | Apr 04, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [d56565f374](https://linux-hardware.org/?probe=d56565f374) | Apr 04, 2023 |
| Dell          | Latitude E6420              | [b35bf27d28](https://linux-hardware.org/?probe=b35bf27d28) | Apr 04, 2023 |
| HP            | 1000                        | [111c9bd980](https://linux-hardware.org/?probe=111c9bd980) | Apr 04, 2023 |
| Unknown       | Unknown                     | [7325272558](https://linux-hardware.org/?probe=7325272558) | Apr 04, 2023 |
| Lenovo        | Unknown                     | [4216d2969c](https://linux-hardware.org/?probe=4216d2969c) | Apr 04, 2023 |
| Gateway       | NE56R                       | [ffa6b1d3f3](https://linux-hardware.org/?probe=ffa6b1d3f3) | Apr 03, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [6ace928ea5](https://linux-hardware.org/?probe=6ace928ea5) | Apr 03, 2023 |
| Lenovo        | Flex 2-14 20404             | [cc341f3faf](https://linux-hardware.org/?probe=cc341f3faf) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Lenovo        | ThinkPad E14 20RAS0D800     | [ea2f5b484f](https://linux-hardware.org/?probe=ea2f5b484f) | Apr 02, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [d018871b72](https://linux-hardware.org/?probe=d018871b72) | Apr 02, 2023 |
| HP            | Laptop 15q-ds0xxx           | [42bd53a04e](https://linux-hardware.org/?probe=42bd53a04e) | Apr 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | [bfba694531](https://linux-hardware.org/?probe=bfba694531) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | [4169f13182](https://linux-hardware.org/?probe=4169f13182) | Apr 01, 2023 |
| Lenovo        | V310-14ISK 80SX             | [cd6dee4651](https://linux-hardware.org/?probe=cd6dee4651) | Apr 01, 2023 |
| Dell          | Vostro 15-3568              | [d93b1d27e1](https://linux-hardware.org/?probe=d93b1d27e1) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| HP            | 250 G3                      | [519b0e31a8](https://linux-hardware.org/?probe=519b0e31a8) | Mar 30, 2023 |
| Dell          | Vostro 15-3568              | [3636f7f999](https://linux-hardware.org/?probe=3636f7f999) | Mar 30, 2023 |
| Lenovo        | Flex 2-14 20404             | [f24b481b5b](https://linux-hardware.org/?probe=f24b481b5b) | Mar 30, 2023 |
| HP            | Pavilion Laptop 15-cs1xx... | [c68415cbb6](https://linux-hardware.org/?probe=c68415cbb6) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [d1295d9d1e](https://linux-hardware.org/?probe=d1295d9d1e) | Mar 30, 2023 |
| Acer          | Extensa 215-23              | [bf5730d468](https://linux-hardware.org/?probe=bf5730d468) | Mar 29, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [a2ba637448](https://linux-hardware.org/?probe=a2ba637448) | Mar 29, 2023 |
| Apple         | MacBookPro13,1              | [d6be820d7d](https://linux-hardware.org/?probe=d6be820d7d) | Mar 29, 2023 |
| Apple         | MacBookPro13,1              | [c800850b44](https://linux-hardware.org/?probe=c800850b44) | Mar 29, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [67789fc0d1](https://linux-hardware.org/?probe=67789fc0d1) | Mar 28, 2023 |
| MSI           | Alpha 15 B5EEK              | [c7f5eaf3f1](https://linux-hardware.org/?probe=c7f5eaf3f1) | Mar 28, 2023 |
| Dell          | Vostro 2420                 | [0a1739f44c](https://linux-hardware.org/?probe=0a1739f44c) | Mar 28, 2023 |
| Dell          | G15 5511                    | [7f15a1e2c7](https://linux-hardware.org/?probe=7f15a1e2c7) | Mar 28, 2023 |
| Lenovo        | G560 20042                  | [83407cead8](https://linux-hardware.org/?probe=83407cead8) | Mar 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [d484c5e138](https://linux-hardware.org/?probe=d484c5e138) | Mar 27, 2023 |
| Dell          | Inspiron 3537               | [5b1971e361](https://linux-hardware.org/?probe=5b1971e361) | Mar 27, 2023 |
| Dell          | Inspiron 1545               | [70c5569887](https://linux-hardware.org/?probe=70c5569887) | Mar 26, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [3c7b4a17ed](https://linux-hardware.org/?probe=3c7b4a17ed) | Mar 26, 2023 |
| Dell          | Inspiron 3501               | [14cc8c6a5e](https://linux-hardware.org/?probe=14cc8c6a5e) | Mar 26, 2023 |
| Lenovo        | G500s 20245                 | [bad00d337f](https://linux-hardware.org/?probe=bad00d337f) | Mar 25, 2023 |
| Lenovo        | E41-25 81FS                 | [9d9e4e184f](https://linux-hardware.org/?probe=9d9e4e184f) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| Lenovo        | ThinkPad T470 20HES4EG00    | [20f698f6d1](https://linux-hardware.org/?probe=20f698f6d1) | Mar 24, 2023 |
| HP            | Laptop 15s-du2xxx           | [882f1dbee1](https://linux-hardware.org/?probe=882f1dbee1) | Mar 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [19efb75aa1](https://linux-hardware.org/?probe=19efb75aa1) | Mar 23, 2023 |
| HP            | Pavilion 15                 | [6c184935d3](https://linux-hardware.org/?probe=6c184935d3) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [85accc79b1](https://linux-hardware.org/?probe=85accc79b1) | Mar 23, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [f8cd7d94b2](https://linux-hardware.org/?probe=f8cd7d94b2) | Mar 23, 2023 |
| HONOR         | NMH-WCX9                    | [21f61b5987](https://linux-hardware.org/?probe=21f61b5987) | Mar 23, 2023 |
| Dell          | Precision 7720              | [c3ef75d6eb](https://linux-hardware.org/?probe=c3ef75d6eb) | Mar 23, 2023 |
| Acer          | Predator PH315-53           | [25c6ad6f8b](https://linux-hardware.org/?probe=25c6ad6f8b) | Mar 23, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [8c5fde8c1e](https://linux-hardware.org/?probe=8c5fde8c1e) | Mar 22, 2023 |
| Dell          | Vostro 2420                 | [e885d387ee](https://linux-hardware.org/?probe=e885d387ee) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [d068d67f2d](https://linux-hardware.org/?probe=d068d67f2d) | Mar 21, 2023 |
| Dell          | Latitude E6420              | [0ed503758b](https://linux-hardware.org/?probe=0ed503758b) | Mar 20, 2023 |
| Dell          | Vostro 2420                 | [a98665cff1](https://linux-hardware.org/?probe=a98665cff1) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3f233b6f9d](https://linux-hardware.org/?probe=3f233b6f9d) | Mar 20, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [a911c14f22](https://linux-hardware.org/?probe=a911c14f22) | Mar 19, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [28092bd4a4](https://linux-hardware.org/?probe=28092bd4a4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ee8b155a83](https://linux-hardware.org/?probe=ee8b155a83) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [928a8fe84e](https://linux-hardware.org/?probe=928a8fe84e) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [00dc1c3b6e](https://linux-hardware.org/?probe=00dc1c3b6e) | Mar 18, 2023 |
| Dell          | Latitude 5420               | [a0555ea0f6](https://linux-hardware.org/?probe=a0555ea0f6) | Mar 17, 2023 |
| HP            | Victus by Gaming Laptop ... | [6bee303acb](https://linux-hardware.org/?probe=6bee303acb) | Mar 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | [06dd580c2e](https://linux-hardware.org/?probe=06dd580c2e) | Mar 16, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [e5ec1e2903](https://linux-hardware.org/?probe=e5ec1e2903) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | [2eff18f570](https://linux-hardware.org/?probe=2eff18f570) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | [2c0d31ff9e](https://linux-hardware.org/?probe=2c0d31ff9e) | Mar 16, 2023 |
| HP            | Laptop 15-dw3xxx            | [87046cb547](https://linux-hardware.org/?probe=87046cb547) | Mar 16, 2023 |
| Dell          | Inspiron 5505               | [33c9adbcee](https://linux-hardware.org/?probe=33c9adbcee) | Mar 16, 2023 |
| Dell          | Latitude 3490               | [ec0778fc94](https://linux-hardware.org/?probe=ec0778fc94) | Mar 15, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [8272edb058](https://linux-hardware.org/?probe=8272edb058) | Mar 15, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [af254fca4d](https://linux-hardware.org/?probe=af254fca4d) | Mar 15, 2023 |
| HP            | 245 G8 Notebook PC          | [6c73c46184](https://linux-hardware.org/?probe=6c73c46184) | Mar 15, 2023 |
| Lenovo        | ThinkPad E480 20KNA01HIG    | [c8054d1090](https://linux-hardware.org/?probe=c8054d1090) | Mar 15, 2023 |
| Dell          | Vostro 2420                 | [a87952a308](https://linux-hardware.org/?probe=a87952a308) | Mar 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [a13648959d](https://linux-hardware.org/?probe=a13648959d) | Mar 14, 2023 |
| Dell          | Latitude 3490               | [bd46ba543b](https://linux-hardware.org/?probe=bd46ba543b) | Mar 14, 2023 |
| RDP           | ThinBook 1010               | [fe650dfe16](https://linux-hardware.org/?probe=fe650dfe16) | Mar 14, 2023 |
| HP            | 245 G6 Notebook PC          | [8ff2a816b5](https://linux-hardware.org/?probe=8ff2a816b5) | Mar 13, 2023 |
| Valve         | Jupiter                     | [e9844f7162](https://linux-hardware.org/?probe=e9844f7162) | Mar 13, 2023 |
| Dell          | Inspiron 5505               | [fc24776ab1](https://linux-hardware.org/?probe=fc24776ab1) | Mar 13, 2023 |
| HP            | Laptop 15s-du0xxx           | [8c91461d71](https://linux-hardware.org/?probe=8c91461d71) | Mar 12, 2023 |
| Dell          | Latitude 3510               | [13ed29770d](https://linux-hardware.org/?probe=13ed29770d) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [d1bf2f0a8b](https://linux-hardware.org/?probe=d1bf2f0a8b) | Mar 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3d98940e14](https://linux-hardware.org/?probe=3d98940e14) | Mar 12, 2023 |
| Infinix       | INBOOK X2 PLUS              | [62b4169c3e](https://linux-hardware.org/?probe=62b4169c3e) | Mar 11, 2023 |
| Dell          | G15 Special Edition 5521    | [f6b2a6bfe0](https://linux-hardware.org/?probe=f6b2a6bfe0) | Mar 11, 2023 |
| Dell          | G15 Special Edition 5521    | [9fab787ede](https://linux-hardware.org/?probe=9fab787ede) | Mar 11, 2023 |
| HP            | Laptop 15s-du0xxx           | [36133f02b8](https://linux-hardware.org/?probe=36133f02b8) | Mar 11, 2023 |
| Dell          | Inspiron 5505               | [a493a6ea35](https://linux-hardware.org/?probe=a493a6ea35) | Mar 11, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [126b4a73a2](https://linux-hardware.org/?probe=126b4a73a2) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS55Q1... | [302abad9dc](https://linux-hardware.org/?probe=302abad9dc) | Mar 11, 2023 |
| HONOR         | NMH-WCX9                    | [f9cf8b06f6](https://linux-hardware.org/?probe=f9cf8b06f6) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d35772b8bc](https://linux-hardware.org/?probe=d35772b8bc) | Mar 09, 2023 |
| HP            | Notebook                    | [b5ee32f085](https://linux-hardware.org/?probe=b5ee32f085) | Mar 09, 2023 |
| HP            | Pavilion 15                 | [80a4b9038d](https://linux-hardware.org/?probe=80a4b9038d) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [187761b57d](https://linux-hardware.org/?probe=187761b57d) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4e1196658a](https://linux-hardware.org/?probe=4e1196658a) | Mar 09, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [07f4220473](https://linux-hardware.org/?probe=07f4220473) | Mar 09, 2023 |
| HP            | Laptop 15s-du3xxx           | [bdfaf09cd0](https://linux-hardware.org/?probe=bdfaf09cd0) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [3e32daea8a](https://linux-hardware.org/?probe=3e32daea8a) | Mar 09, 2023 |
| Lenovo        | IdeaPad S540-15IML D 81N... | [31e144de96](https://linux-hardware.org/?probe=31e144de96) | Mar 08, 2023 |
| Dell          | Inspiron 15 3520            | [face0290e3](https://linux-hardware.org/?probe=face0290e3) | Mar 08, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3087a03cb5](https://linux-hardware.org/?probe=3087a03cb5) | Mar 08, 2023 |
| Acer          | Aspire A515-45              | [3089c37fd4](https://linux-hardware.org/?probe=3089c37fd4) | Mar 08, 2023 |
| Intel         | Raptor Lake Client Platf... | [f52d925104](https://linux-hardware.org/?probe=f52d925104) | Mar 08, 2023 |
| Dell          | Latitude 5400               | [3d2504745e](https://linux-hardware.org/?probe=3d2504745e) | Mar 08, 2023 |
| Dell          | G15 5515                    | [fc1b55ddc1](https://linux-hardware.org/?probe=fc1b55ddc1) | Mar 07, 2023 |
| HP            | Laptop 15s-dr1xxx           | [be222c3e23](https://linux-hardware.org/?probe=be222c3e23) | Mar 07, 2023 |
| Dell          | Inspiron 15-3567            | [ff582d0370](https://linux-hardware.org/?probe=ff582d0370) | Mar 07, 2023 |
| Dell          | Inspiron N5010              | [16d683966c](https://linux-hardware.org/?probe=16d683966c) | Mar 07, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [d00485842a](https://linux-hardware.org/?probe=d00485842a) | Mar 06, 2023 |
| Lenovo        | G50-80 80E5                 | [75dab4cddf](https://linux-hardware.org/?probe=75dab4cddf) | Mar 06, 2023 |
| Dell          | Latitude 7480               | [c4e5e8923c](https://linux-hardware.org/?probe=c4e5e8923c) | Mar 05, 2023 |
| HP            | Pavilion 15                 | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [657175938b](https://linux-hardware.org/?probe=657175938b) | Mar 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2a93373173](https://linux-hardware.org/?probe=2a93373173) | Mar 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5871fdcf26](https://linux-hardware.org/?probe=5871fdcf26) | Mar 04, 2023 |
| HP            | Pavilion 15                 | [50a27abb52](https://linux-hardware.org/?probe=50a27abb52) | Mar 04, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5a15c4c2b0](https://linux-hardware.org/?probe=5a15c4c2b0) | Mar 03, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [20dc6b7a10](https://linux-hardware.org/?probe=20dc6b7a10) | Mar 03, 2023 |
| Dell          | Inspiron 15-3567            | [aefdf1040c](https://linux-hardware.org/?probe=aefdf1040c) | Mar 03, 2023 |
| Lenovo        | ThinkPad W530 2447C83       | [c5f046d2fb](https://linux-hardware.org/?probe=c5f046d2fb) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [edf5f00bf8](https://linux-hardware.org/?probe=edf5f00bf8) | Mar 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [23d5a9e0a8](https://linux-hardware.org/?probe=23d5a9e0a8) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [94809b7bc2](https://linux-hardware.org/?probe=94809b7bc2) | Mar 01, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [e9b7ee04ec](https://linux-hardware.org/?probe=e9b7ee04ec) | Mar 01, 2023 |
| Getac         | B360                        | [c4bd09adf1](https://linux-hardware.org/?probe=c4bd09adf1) | Mar 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [e1733fa8c9](https://linux-hardware.org/?probe=e1733fa8c9) | Mar 01, 2023 |
| Dell          | Inspiron N5110              | [5a6d88e081](https://linux-hardware.org/?probe=5a6d88e081) | Feb 28, 2023 |
| Lenovo        | ThinkPad T460s 20FAS55Q1... | [815b6ea9f2](https://linux-hardware.org/?probe=815b6ea9f2) | Feb 27, 2023 |
| Dell          | Inspiron 15 3511            | [4c96506f38](https://linux-hardware.org/?probe=4c96506f38) | Feb 27, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [82a40f1881](https://linux-hardware.org/?probe=82a40f1881) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [fe8735a027](https://linux-hardware.org/?probe=fe8735a027) | Feb 26, 2023 |
| Dell          | Vostro 3578                 | [da6968c8ac](https://linux-hardware.org/?probe=da6968c8ac) | Feb 26, 2023 |
| Acer          | Nitro AN515-58              | [1c93095718](https://linux-hardware.org/?probe=1c93095718) | Feb 26, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [b410d220e6](https://linux-hardware.org/?probe=b410d220e6) | Feb 26, 2023 |
| HP            | Victus by 16 Laptop PC      | [05ef574a7c](https://linux-hardware.org/?probe=05ef574a7c) | Feb 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | [64504d9860](https://linux-hardware.org/?probe=64504d9860) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [787270bc9e](https://linux-hardware.org/?probe=787270bc9e) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [759b3114be](https://linux-hardware.org/?probe=759b3114be) | Feb 24, 2023 |
| Acer          | Aspire A315-23              | [e0fcd4e578](https://linux-hardware.org/?probe=e0fcd4e578) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f7063f868f](https://linux-hardware.org/?probe=f7063f868f) | Feb 24, 2023 |
| HP            | 245 G8 Notebook PC          | [7686bcd76d](https://linux-hardware.org/?probe=7686bcd76d) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [93dfbdd8cd](https://linux-hardware.org/?probe=93dfbdd8cd) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05C 82AU      | [a5a58a8dc4](https://linux-hardware.org/?probe=a5a58a8dc4) | Feb 23, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ead0af8ae4](https://linux-hardware.org/?probe=ead0af8ae4) | Feb 23, 2023 |
| Dell          | Vostro 3446                 | [c6df0f1b65](https://linux-hardware.org/?probe=c6df0f1b65) | Feb 23, 2023 |
| Dell          | Studio 1450                 | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| Lenovo        | G50-80 80E5                 | [d196877f8d](https://linux-hardware.org/?probe=d196877f8d) | Feb 22, 2023 |
| Lenovo        | G50-80 80E5                 | [9485c15a78](https://linux-hardware.org/?probe=9485c15a78) | Feb 22, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d09dc2494a](https://linux-hardware.org/?probe=d09dc2494a) | Feb 21, 2023 |
| Dell          | Vostro 3491                 | [d557c581cf](https://linux-hardware.org/?probe=d557c581cf) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| HP            | ProBook 440 G4              | [d495b4eb1e](https://linux-hardware.org/?probe=d495b4eb1e) | Feb 20, 2023 |
| HP            | Laptop 15s-dr0xxx           | [6733a448f9](https://linux-hardware.org/?probe=6733a448f9) | Feb 20, 2023 |
| HP            | Pavilion 15                 | [7c652212fb](https://linux-hardware.org/?probe=7c652212fb) | Feb 19, 2023 |
| HP            | Pavilion 15                 | [cecc8c4a23](https://linux-hardware.org/?probe=cecc8c4a23) | Feb 19, 2023 |
| Dell          | Precision 3510              | [b20156e847](https://linux-hardware.org/?probe=b20156e847) | Feb 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [affa3bb9f1](https://linux-hardware.org/?probe=affa3bb9f1) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [7e5327c1ed](https://linux-hardware.org/?probe=7e5327c1ed) | Feb 19, 2023 |
| HP            | ProBook 440 G4              | [f6372e6b96](https://linux-hardware.org/?probe=f6372e6b96) | Feb 19, 2023 |
| HP            | ProBook 445 G1              | [bcd5c952f1](https://linux-hardware.org/?probe=bcd5c952f1) | Feb 18, 2023 |
| HP            | Unknown                     | [3fea6a053b](https://linux-hardware.org/?probe=3fea6a053b) | Feb 18, 2023 |
| HP            | 15                          | [4db2520843](https://linux-hardware.org/?probe=4db2520843) | Feb 18, 2023 |
| Dell          | G7 7588                     | [caf1cd6176](https://linux-hardware.org/?probe=caf1cd6176) | Feb 18, 2023 |
| Dell          | Inspiron 3537               | [7890bf1c68](https://linux-hardware.org/?probe=7890bf1c68) | Feb 17, 2023 |
| Apple         | MacBookPro9,2               | [e67f600749](https://linux-hardware.org/?probe=e67f600749) | Feb 16, 2023 |
| Dell          | Inspiron 1545               | [32794e5a2e](https://linux-hardware.org/?probe=32794e5a2e) | Feb 16, 2023 |
| Dell          | Latitude 7490               | [796443d889](https://linux-hardware.org/?probe=796443d889) | Feb 16, 2023 |
| Dell          | Inspiron 1564               | [7b90c0a5cc](https://linux-hardware.org/?probe=7b90c0a5cc) | Feb 15, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [0488cd4f01](https://linux-hardware.org/?probe=0488cd4f01) | Feb 15, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [561e1a6160](https://linux-hardware.org/?probe=561e1a6160) | Feb 14, 2023 |
| HP            | Pavilion 15                 | [7f54c595f1](https://linux-hardware.org/?probe=7f54c595f1) | Feb 14, 2023 |
| HP            | Laptop 15s-du3xxx           | [4750f3ad3a](https://linux-hardware.org/?probe=4750f3ad3a) | Feb 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [31593ae5b9](https://linux-hardware.org/?probe=31593ae5b9) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [a6af7624cd](https://linux-hardware.org/?probe=a6af7624cd) | Feb 13, 2023 |
| HP            | ProBook 440 G5              | [566c6a5316](https://linux-hardware.org/?probe=566c6a5316) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | [a833fa9a0c](https://linux-hardware.org/?probe=a833fa9a0c) | Feb 12, 2023 |
| HP            | Notebook                    | [a17adfd867](https://linux-hardware.org/?probe=a17adfd867) | Feb 12, 2023 |
| HP            | 430                         | [9350af0a6b](https://linux-hardware.org/?probe=9350af0a6b) | Feb 12, 2023 |
| Dell          | Vostro 3446                 | [e3784684f4](https://linux-hardware.org/?probe=e3784684f4) | Feb 11, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [321710ca2d](https://linux-hardware.org/?probe=321710ca2d) | Feb 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | [5f2fb779b4](https://linux-hardware.org/?probe=5f2fb779b4) | Feb 11, 2023 |
| ASUSTek       | K52F                        | [6820e56394](https://linux-hardware.org/?probe=6820e56394) | Feb 11, 2023 |
| Acer          | Aspire A715-41G             | [92b7a6f08d](https://linux-hardware.org/?probe=92b7a6f08d) | Feb 11, 2023 |
| Dell          | Inspiron 1564               | [687573b718](https://linux-hardware.org/?probe=687573b718) | Feb 10, 2023 |
| Timi          | Mi NoteBook Pro             | [34e8df3dea](https://linux-hardware.org/?probe=34e8df3dea) | Feb 10, 2023 |
| Dell          | Inspiron 1564               | [043eef223c](https://linux-hardware.org/?probe=043eef223c) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [482b3ea2be](https://linux-hardware.org/?probe=482b3ea2be) | Feb 10, 2023 |
| HP            | Pavilion 15                 | [8e014440da](https://linux-hardware.org/?probe=8e014440da) | Feb 10, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [c4ba4f3bc6](https://linux-hardware.org/?probe=c4ba4f3bc6) | Feb 10, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [812df42bc4](https://linux-hardware.org/?probe=812df42bc4) | Feb 10, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | [fc292cd441](https://linux-hardware.org/?probe=fc292cd441) | Feb 09, 2023 |
| Dell          | Inspiron 3576               | [69949c02d9](https://linux-hardware.org/?probe=69949c02d9) | Feb 09, 2023 |
| Dell          | Latitude 5410               | [08ab3250ae](https://linux-hardware.org/?probe=08ab3250ae) | Feb 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ce71e8ab61](https://linux-hardware.org/?probe=ce71e8ab61) | Feb 08, 2023 |
| MSI           | GF63 Thin 11UC              | [722d0ce3be](https://linux-hardware.org/?probe=722d0ce3be) | Feb 07, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [fa97fe509b](https://linux-hardware.org/?probe=fa97fe509b) | Feb 07, 2023 |
| HONOR         | NMH-WCX9                    | [1f2418bafb](https://linux-hardware.org/?probe=1f2418bafb) | Feb 06, 2023 |
| Lenovo        | G505 20240                  | [31e2c2f5e1](https://linux-hardware.org/?probe=31e2c2f5e1) | Feb 06, 2023 |
| Dell          | Latitude 7480               | [850e6ed168](https://linux-hardware.org/?probe=850e6ed168) | Feb 06, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [1ce10af418](https://linux-hardware.org/?probe=1ce10af418) | Feb 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d95f28d447](https://linux-hardware.org/?probe=d95f28d447) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [400b29056d](https://linux-hardware.org/?probe=400b29056d) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [de72d92ada](https://linux-hardware.org/?probe=de72d92ada) | Feb 05, 2023 |
| Dell          | Latitude 7490               | [b8ecfb712c](https://linux-hardware.org/?probe=b8ecfb712c) | Feb 05, 2023 |
| Dell          | Latitude 7490               | [aa51c3690f](https://linux-hardware.org/?probe=aa51c3690f) | Feb 05, 2023 |
| HP            | Pavilion 15                 | [00ebdfe948](https://linux-hardware.org/?probe=00ebdfe948) | Feb 04, 2023 |
| Acer          | Nitro AN515-43              | [8fd252af27](https://linux-hardware.org/?probe=8fd252af27) | Feb 04, 2023 |
| Dell          | Inspiron 5593               | [e08416e7a9](https://linux-hardware.org/?probe=e08416e7a9) | Feb 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b3eac5c97d](https://linux-hardware.org/?probe=b3eac5c97d) | Feb 04, 2023 |
| HP            | Pavilion 15                 | [a5508059a1](https://linux-hardware.org/?probe=a5508059a1) | Feb 04, 2023 |
| Dell          | Inspiron 5537               | [5bfa4ad142](https://linux-hardware.org/?probe=5bfa4ad142) | Feb 02, 2023 |
| MSI           | GE63 Raider RGB 9SE         | [b7ec016843](https://linux-hardware.org/?probe=b7ec016843) | Feb 02, 2023 |
| Dell          | Inspiron 3584               | [4bfcbe7c13](https://linux-hardware.org/?probe=4bfcbe7c13) | Feb 02, 2023 |
| Acer          | Aspire ES1-572              | [09d76d7d2a](https://linux-hardware.org/?probe=09d76d7d2a) | Feb 02, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [22abfb4a79](https://linux-hardware.org/?probe=22abfb4a79) | Feb 01, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [8360c9e13f](https://linux-hardware.org/?probe=8360c9e13f) | Feb 01, 2023 |
| Timi          | Mi NoteBook Ultra           | [d897ec0114](https://linux-hardware.org/?probe=d897ec0114) | Feb 01, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [07b498f669](https://linux-hardware.org/?probe=07b498f669) | Feb 01, 2023 |
| HP            | Pavilion 15                 | [e3adac798e](https://linux-hardware.org/?probe=e3adac798e) | Jan 30, 2023 |
| HP            | 15                          | [409a15bdf3](https://linux-hardware.org/?probe=409a15bdf3) | Jan 30, 2023 |
| ASUSTek       | X507UA                      | [49cc52b5b2](https://linux-hardware.org/?probe=49cc52b5b2) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [47438e081a](https://linux-hardware.org/?probe=47438e081a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [4b8206c892](https://linux-hardware.org/?probe=4b8206c892) | Jan 29, 2023 |
| HP            | Pavilion 15                 | [c5ac9f6d89](https://linux-hardware.org/?probe=c5ac9f6d89) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [621aca8707](https://linux-hardware.org/?probe=621aca8707) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [55fe252b4e](https://linux-hardware.org/?probe=55fe252b4e) | Jan 29, 2023 |
| Lenovo        | ThinkPad X61 7674BE1        | [a22ac0a9f5](https://linux-hardware.org/?probe=a22ac0a9f5) | Jan 28, 2023 |
| Acer          | Aspire A515-57G             | [f5492fbdaa](https://linux-hardware.org/?probe=f5492fbdaa) | Jan 27, 2023 |
| Timi          | Mi NoteBook Pro             | [33905a4ee9](https://linux-hardware.org/?probe=33905a4ee9) | Jan 26, 2023 |
| Dell          | Latitude 7480               | [3cb61c5b71](https://linux-hardware.org/?probe=3cb61c5b71) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| HP            | Pavilion 15                 | [e3ac708616](https://linux-hardware.org/?probe=e3ac708616) | Jan 26, 2023 |
| Acer          | Aspire A515-52G             | [a95489f0b7](https://linux-hardware.org/?probe=a95489f0b7) | Jan 24, 2023 |
| MSI           | GF63 Thin 9SCXR             | [edbaabb13a](https://linux-hardware.org/?probe=edbaabb13a) | Jan 24, 2023 |
| Acer          | Aspire ES1-521              | [32a1eb6d60](https://linux-hardware.org/?probe=32a1eb6d60) | Jan 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [07005e3e32](https://linux-hardware.org/?probe=07005e3e32) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [348a78bb64](https://linux-hardware.org/?probe=348a78bb64) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c6a463e92f](https://linux-hardware.org/?probe=c6a463e92f) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a09d1d224c](https://linux-hardware.org/?probe=a09d1d224c) | Jan 22, 2023 |
| Timi          | Mi Notebook Pro             | [1db1382f0b](https://linux-hardware.org/?probe=1db1382f0b) | Jan 21, 2023 |
| Dell          | Inspiron 5505               | [9a17165647](https://linux-hardware.org/?probe=9a17165647) | Jan 20, 2023 |
| Dell          | Inspiron 5505               | [e1003a85c9](https://linux-hardware.org/?probe=e1003a85c9) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [0f079e1dc7](https://linux-hardware.org/?probe=0f079e1dc7) | Jan 19, 2023 |
| Acer          | Aspire A315-23              | [90049e4bb7](https://linux-hardware.org/?probe=90049e4bb7) | Jan 19, 2023 |
| Dell          | Latitude E6510              | [4b10c4532e](https://linux-hardware.org/?probe=4b10c4532e) | Jan 19, 2023 |
| Dell          | Latitude E6510              | [6b8112e4c1](https://linux-hardware.org/?probe=6b8112e4c1) | Jan 19, 2023 |
| Lenovo        | ThinkPad X200 7459VB9       | [a58c604cf7](https://linux-hardware.org/?probe=a58c604cf7) | Jan 18, 2023 |
| Dell          | Inspiron 3442               | [04fe55a1a1](https://linux-hardware.org/?probe=04fe55a1a1) | Jan 18, 2023 |
| HP            | Victus by Gaming Laptop ... | [533d99e2f1](https://linux-hardware.org/?probe=533d99e2f1) | Jan 18, 2023 |
| HP            | 15                          | [cebe1b150e](https://linux-hardware.org/?probe=cebe1b150e) | Jan 18, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [681de2b0c1](https://linux-hardware.org/?probe=681de2b0c1) | Jan 17, 2023 |
| MSI           | GF63 Thin 9SCXR             | [592a29d649](https://linux-hardware.org/?probe=592a29d649) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [f1ee502754](https://linux-hardware.org/?probe=f1ee502754) | Jan 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0d91852ebf](https://linux-hardware.org/?probe=0d91852ebf) | Jan 17, 2023 |
| MSI           | Prestige 15 A11SCX          | [9c5bf0d05c](https://linux-hardware.org/?probe=9c5bf0d05c) | Jan 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1a51848ffb](https://linux-hardware.org/?probe=1a51848ffb) | Jan 16, 2023 |
| Lenovo        | V14-IIL 82C4                | [1b195c04d8](https://linux-hardware.org/?probe=1b195c04d8) | Jan 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X600    | [2c2e9caacc](https://linux-hardware.org/?probe=2c2e9caacc) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440p 20AN00DJA... | [250aa5a61b](https://linux-hardware.org/?probe=250aa5a61b) | Jan 15, 2023 |
| HP            | Pavilion g6                 | [fba7cebfff](https://linux-hardware.org/?probe=fba7cebfff) | Jan 14, 2023 |
| MSI           | Bravo 15 B5DD               | [ffb8653d34](https://linux-hardware.org/?probe=ffb8653d34) | Jan 14, 2023 |
| Lenovo        | ThinkPad W540 20BHS1840P    | [0046521475](https://linux-hardware.org/?probe=0046521475) | Jan 14, 2023 |
| Dell          | XPS 15 9570                 | [bff6278ed8](https://linux-hardware.org/?probe=bff6278ed8) | Jan 14, 2023 |
| HONOR         | NMH-WCX9                    | [10a9c33aed](https://linux-hardware.org/?probe=10a9c33aed) | Jan 13, 2023 |
| MSI           | GF63 Thin 9SCXR             | [3ba9f40d9b](https://linux-hardware.org/?probe=3ba9f40d9b) | Jan 13, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| HP            | 245 G7 Notebook PC          | [3997d98a9a](https://linux-hardware.org/?probe=3997d98a9a) | Jan 11, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [6c67fc3995](https://linux-hardware.org/?probe=6c67fc3995) | Jan 11, 2023 |
| Acer          | TravelMate P245-M           | [1722e41c8d](https://linux-hardware.org/?probe=1722e41c8d) | Jan 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [a786384700](https://linux-hardware.org/?probe=a786384700) | Jan 10, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8367c27d81](https://linux-hardware.org/?probe=8367c27d81) | Jan 10, 2023 |
| MSI           | GF63 Thin 9SCXR             | [805265229e](https://linux-hardware.org/?probe=805265229e) | Jan 10, 2023 |
| ASUSTek       | K53SM                       | [f1ac679157](https://linux-hardware.org/?probe=f1ac679157) | Jan 10, 2023 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | [debe9fa9d2](https://linux-hardware.org/?probe=debe9fa9d2) | Jan 08, 2023 |
| Lenovo        | ThinkPad T430 2349E56       | [ff2639c47b](https://linux-hardware.org/?probe=ff2639c47b) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [f191d63ace](https://linux-hardware.org/?probe=f191d63ace) | Jan 07, 2023 |
| MSI           | GF63 Thin 9SCXR             | [a6b7ce48a7](https://linux-hardware.org/?probe=a6b7ce48a7) | Jan 07, 2023 |
| MSI           | GF63 Thin 9SCXR             | [a3cc92ede0](https://linux-hardware.org/?probe=a3cc92ede0) | Jan 07, 2023 |
| MSI           | GF63 8RD                    | [d9fc4d53c9](https://linux-hardware.org/?probe=d9fc4d53c9) | Jan 07, 2023 |
| Dell          | Vostro 15-3568              | [2dd2c1c022](https://linux-hardware.org/?probe=2dd2c1c022) | Jan 06, 2023 |
| Dell          | Vostro 15-3568              | [f3d1187b29](https://linux-hardware.org/?probe=f3d1187b29) | Jan 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fd5120fea6](https://linux-hardware.org/?probe=fd5120fea6) | Jan 06, 2023 |
| HP            | Laptop 14s-dk0xxx           | [00212160f7](https://linux-hardware.org/?probe=00212160f7) | Jan 05, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [482205e492](https://linux-hardware.org/?probe=482205e492) | Jan 05, 2023 |
| HP            | Notebook                    | [611e618b60](https://linux-hardware.org/?probe=611e618b60) | Jan 03, 2023 |
| Lenovo        | ThinkPad E490 20N8S0H300    | [fb3233e525](https://linux-hardware.org/?probe=fb3233e525) | Jan 02, 2023 |
| ITI LIMITE... | ITI Smaash ITIB15LI3        | [6e271cd1c3](https://linux-hardware.org/?probe=6e271cd1c3) | Jan 02, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| HP            | Laptop HP Laptop 14s-dr1... | [2a27236865](https://linux-hardware.org/?probe=2a27236865) | Jan 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [60b4a8e506](https://linux-hardware.org/?probe=60b4a8e506) | Jan 01, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [5d0ff5ea2d](https://linux-hardware.org/?probe=5d0ff5ea2d) | Dec 31, 2022 |
| Dell          | Inspiron 3421               | [d2cd50a2a6](https://linux-hardware.org/?probe=d2cd50a2a6) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | [ae7d821823](https://linux-hardware.org/?probe=ae7d821823) | Dec 30, 2022 |
| ITI LIMITE... | ITI Smaash ITIB15LI3        | [6a08f378e2](https://linux-hardware.org/?probe=6a08f378e2) | Dec 30, 2022 |
| ITI LIMITE... | ITI Smaash ITIB15LI3        | [282a44d1ff](https://linux-hardware.org/?probe=282a44d1ff) | Dec 30, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [3a7cfd8073](https://linux-hardware.org/?probe=3a7cfd8073) | Dec 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ce45aaceaf](https://linux-hardware.org/?probe=ce45aaceaf) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [264e3738ec](https://linux-hardware.org/?probe=264e3738ec) | Dec 29, 2022 |
| Dell          | Latitude 3420               | [eb6d4c6921](https://linux-hardware.org/?probe=eb6d4c6921) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [d5be261567](https://linux-hardware.org/?probe=d5be261567) | Dec 29, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | [c25b644aca](https://linux-hardware.org/?probe=c25b644aca) | Dec 28, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [5054f77353](https://linux-hardware.org/?probe=5054f77353) | Dec 27, 2022 |
| Timi          | RedmiBook 15                | [cf38b14bc5](https://linux-hardware.org/?probe=cf38b14bc5) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c8b85cb0cd](https://linux-hardware.org/?probe=c8b85cb0cd) | Dec 26, 2022 |
| Lenovo        | G510 20238                  | [812d6eb07e](https://linux-hardware.org/?probe=812d6eb07e) | Dec 26, 2022 |
| Dell          | Inspiron N5010              | [69ac8a9522](https://linux-hardware.org/?probe=69ac8a9522) | Dec 26, 2022 |
| Dell          | Latitude E6400              | [435ac90ddc](https://linux-hardware.org/?probe=435ac90ddc) | Dec 26, 2022 |
| Sony          | SVE15133CNB                 | [40ac0f9ffc](https://linux-hardware.org/?probe=40ac0f9ffc) | Dec 25, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [576fb3852f](https://linux-hardware.org/?probe=576fb3852f) | Dec 25, 2022 |
| Dell          | Vostro 3501                 | [2bd2de39fb](https://linux-hardware.org/?probe=2bd2de39fb) | Dec 24, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| HP            | EliteBook 840 G5            | [05ab61864f](https://linux-hardware.org/?probe=05ab61864f) | Dec 23, 2022 |
| HP            | Laptop 14s-dk0xxx           | [53aa474cf5](https://linux-hardware.org/?probe=53aa474cf5) | Dec 23, 2022 |
| HONOR         | BBR-WAX9                    | [19909aa86b](https://linux-hardware.org/?probe=19909aa86b) | Dec 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [0256ea50a4](https://linux-hardware.org/?probe=0256ea50a4) | Dec 23, 2022 |
| Acer          | Aspire A515-57G             | [a208b5598e](https://linux-hardware.org/?probe=a208b5598e) | Dec 22, 2022 |
| Acer          | Aspire A515-57G             | [cccd3d01d7](https://linux-hardware.org/?probe=cccd3d01d7) | Dec 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b221e3103a](https://linux-hardware.org/?probe=b221e3103a) | Dec 22, 2022 |
| Acer          | Swift SF314-512             | [505ab3f60a](https://linux-hardware.org/?probe=505ab3f60a) | Dec 22, 2022 |
| Acer          | Gateway NE46Rs1             | [45a25a89d7](https://linux-hardware.org/?probe=45a25a89d7) | Dec 21, 2022 |
| MSI           | GL65 Leopard 10SDK          | [2c6e6ec3ec](https://linux-hardware.org/?probe=2c6e6ec3ec) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9438c80c85](https://linux-hardware.org/?probe=9438c80c85) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7d5914dcb2](https://linux-hardware.org/?probe=7d5914dcb2) | Dec 21, 2022 |
| Timi          | Mi NoteBook Pro             | [b5bbb4f410](https://linux-hardware.org/?probe=b5bbb4f410) | Dec 21, 2022 |
| HP            | ZBook 15                    | [a3bf671d64](https://linux-hardware.org/?probe=a3bf671d64) | Dec 20, 2022 |
| Dell          | Vostro 5620                 | [005d388376](https://linux-hardware.org/?probe=005d388376) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | [93eff781da](https://linux-hardware.org/?probe=93eff781da) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | [0b7352a343](https://linux-hardware.org/?probe=0b7352a343) | Dec 20, 2022 |
| Dell          | Inspiron 7572               | [418178c3ca](https://linux-hardware.org/?probe=418178c3ca) | Dec 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [c67b4d2b31](https://linux-hardware.org/?probe=c67b4d2b31) | Dec 19, 2022 |
| Sony          | SVE15133CNB                 | [a2bee3bb3f](https://linux-hardware.org/?probe=a2bee3bb3f) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [08e38b2be9](https://linux-hardware.org/?probe=08e38b2be9) | Dec 18, 2022 |
| HP            | Laptop 14s-dk0xxx           | [eaf1b6a773](https://linux-hardware.org/?probe=eaf1b6a773) | Dec 17, 2022 |
| HP            | 245 G3                      | [ceee8f33ca](https://linux-hardware.org/?probe=ceee8f33ca) | Dec 17, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [b0f674ae6f](https://linux-hardware.org/?probe=b0f674ae6f) | Dec 17, 2022 |
| Sony          | SVE15133CNB                 | [acca7c4697](https://linux-hardware.org/?probe=acca7c4697) | Dec 17, 2022 |
| HP            | 250 G1                      | [07f20cc1ec](https://linux-hardware.org/?probe=07f20cc1ec) | Dec 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [f6e6cfc7b3](https://linux-hardware.org/?probe=f6e6cfc7b3) | Dec 17, 2022 |
| Dell          | Inspiron 3442               | [3b5142322b](https://linux-hardware.org/?probe=3b5142322b) | Dec 16, 2022 |
| HP            | Laptop 15q-bu0xx            | [d291ab8cf8](https://linux-hardware.org/?probe=d291ab8cf8) | Dec 16, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [f54a021496](https://linux-hardware.org/?probe=f54a021496) | Dec 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | [7aab463e8e](https://linux-hardware.org/?probe=7aab463e8e) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [7ea1bad26b](https://linux-hardware.org/?probe=7ea1bad26b) | Dec 15, 2022 |
| Dell          | Latitude 3420               | [a6c668f4a2](https://linux-hardware.org/?probe=a6c668f4a2) | Dec 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | [484c320457](https://linux-hardware.org/?probe=484c320457) | Dec 14, 2022 |
| Dell          | Inspiron 3583               | [70992b154e](https://linux-hardware.org/?probe=70992b154e) | Dec 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | [7ffd00681b](https://linux-hardware.org/?probe=7ffd00681b) | Dec 12, 2022 |
| HP            | Laptop 14s-fq1xxx           | [811092647b](https://linux-hardware.org/?probe=811092647b) | Dec 11, 2022 |
| HP            | Pavilion g6                 | [964081eed7](https://linux-hardware.org/?probe=964081eed7) | Dec 11, 2022 |
| Unknown       | Unknown                     | [bde36454f9](https://linux-hardware.org/?probe=bde36454f9) | Dec 11, 2022 |
| HP            | Laptop 15s-du3xxx           | [400a0b555d](https://linux-hardware.org/?probe=400a0b555d) | Dec 10, 2022 |
| Acer          | Nitro AN515-45              | [36af891d5d](https://linux-hardware.org/?probe=36af891d5d) | Dec 10, 2022 |
| Lenovo        | IdeaPadS540 81NE            | [3e5b528d0f](https://linux-hardware.org/?probe=3e5b528d0f) | Dec 09, 2022 |
| Unknown       | Unknown                     | [d737aa3978](https://linux-hardware.org/?probe=d737aa3978) | Dec 09, 2022 |
| HP            | 245 G8 Notebook PC          | [c291bac936](https://linux-hardware.org/?probe=c291bac936) | Dec 09, 2022 |
| Dynabook      | Satellite Pro C40-H Y030... | [a804b63bcd](https://linux-hardware.org/?probe=a804b63bcd) | Dec 09, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [30cc472125](https://linux-hardware.org/?probe=30cc472125) | Dec 08, 2022 |
| Dell          | Vostro 3500                 | [9d46a5fb80](https://linux-hardware.org/?probe=9d46a5fb80) | Dec 08, 2022 |
| Lenovo        | G550 2958                   | [e04f421926](https://linux-hardware.org/?probe=e04f421926) | Dec 08, 2022 |
| HP            | Laptop 14s-dq2xxx           | [383bc11a0d](https://linux-hardware.org/?probe=383bc11a0d) | Dec 07, 2022 |
| Dynabook      | Satellite Pro C40-H Y030... | [3167658218](https://linux-hardware.org/?probe=3167658218) | Dec 06, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | [4dc49eeb10](https://linux-hardware.org/?probe=4dc49eeb10) | Dec 06, 2022 |
| Dell          | Latitude E5430 vPro         | [9ccc3c8d05](https://linux-hardware.org/?probe=9ccc3c8d05) | Dec 06, 2022 |
| Dell          | Inspiron 3421               | [9af2847ac7](https://linux-hardware.org/?probe=9af2847ac7) | Dec 06, 2022 |
| Dell          | Inspiron 7577               | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| Dell          | Inspiron 3521               | [496bcc21ca](https://linux-hardware.org/?probe=496bcc21ca) | Dec 05, 2022 |
| Dell          | Inspiron 3521               | [3a74cfee45](https://linux-hardware.org/?probe=3a74cfee45) | Dec 05, 2022 |
| HP            | 430                         | [3c0de30201](https://linux-hardware.org/?probe=3c0de30201) | Dec 04, 2022 |
| Sony          | SVE15133CNB                 | [16f43f11a1](https://linux-hardware.org/?probe=16f43f11a1) | Dec 04, 2022 |
| HP            | 247 G8                      | [f7cc5f6544](https://linux-hardware.org/?probe=f7cc5f6544) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3d8af3595b](https://linux-hardware.org/?probe=3d8af3595b) | Dec 03, 2022 |
| Acer          | Aspire A715-51G             | [65aa3f7e69](https://linux-hardware.org/?probe=65aa3f7e69) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [dc80fd6907](https://linux-hardware.org/?probe=dc80fd6907) | Dec 02, 2022 |
| HP            | Laptop 15-da0xxx            | [f6d1014498](https://linux-hardware.org/?probe=f6d1014498) | Dec 02, 2022 |
| Lenovo        | 510-15IKB 80SV              | [9378fc7d09](https://linux-hardware.org/?probe=9378fc7d09) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [2397eee427](https://linux-hardware.org/?probe=2397eee427) | Dec 01, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [c9ccbe1018](https://linux-hardware.org/?probe=c9ccbe1018) | Dec 01, 2022 |
| HP            | Notebook                    | [7c22b96a9a](https://linux-hardware.org/?probe=7c22b96a9a) | Dec 01, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [65fa0de0a2](https://linux-hardware.org/?probe=65fa0de0a2) | Dec 01, 2022 |
| Dell          | Inspiron 15-3567            | [ee99c81e47](https://linux-hardware.org/?probe=ee99c81e47) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| Acer          | Nitro AN515-43              | [b315e85bda](https://linux-hardware.org/?probe=b315e85bda) | Nov 30, 2022 |
| HP            | Notebook                    | [afac08b852](https://linux-hardware.org/?probe=afac08b852) | Nov 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Toshiba       | Satellite L40               | [fa36933936](https://linux-hardware.org/?probe=fa36933936) | Nov 29, 2022 |
| Dell          | Latitude 3500               | [de0731ac74](https://linux-hardware.org/?probe=de0731ac74) | Nov 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [16705fe86c](https://linux-hardware.org/?probe=16705fe86c) | Nov 28, 2022 |
| Acer          | Predator PH315-54           | [15909202b8](https://linux-hardware.org/?probe=15909202b8) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2aba12235d](https://linux-hardware.org/?probe=2aba12235d) | Nov 27, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [26083dd909](https://linux-hardware.org/?probe=26083dd909) | Nov 27, 2022 |
| AVITA         | NS14A6                      | [b9cc8fe757](https://linux-hardware.org/?probe=b9cc8fe757) | Nov 27, 2022 |
| Dell          | Vostro 3580                 | [350202deed](https://linux-hardware.org/?probe=350202deed) | Nov 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [dc561bb107](https://linux-hardware.org/?probe=dc561bb107) | Nov 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [336d829333](https://linux-hardware.org/?probe=336d829333) | Nov 26, 2022 |
| Sony          | VPCEA45FG                   | [847b1cb39a](https://linux-hardware.org/?probe=847b1cb39a) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [2902b75068](https://linux-hardware.org/?probe=2902b75068) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [973662f8d5](https://linux-hardware.org/?probe=973662f8d5) | Nov 26, 2022 |
| Dell          | Latitude 5490               | [7aedc1fbd7](https://linux-hardware.org/?probe=7aedc1fbd7) | Nov 26, 2022 |
| HUAWEI        | HVY-WXX9                    | [00d2cc22aa](https://linux-hardware.org/?probe=00d2cc22aa) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | [376fc86892](https://linux-hardware.org/?probe=376fc86892) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | [f46e1bc341](https://linux-hardware.org/?probe=f46e1bc341) | Nov 25, 2022 |
| HP            | 245 G3                      | [c155a2a926](https://linux-hardware.org/?probe=c155a2a926) | Nov 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [32ab0a36a4](https://linux-hardware.org/?probe=32ab0a36a4) | Nov 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ce5f08445d](https://linux-hardware.org/?probe=ce5f08445d) | Nov 24, 2022 |
| Dell          | Inspiron 5370               | [469b2c3fd4](https://linux-hardware.org/?probe=469b2c3fd4) | Nov 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d84bc82678](https://linux-hardware.org/?probe=d84bc82678) | Nov 23, 2022 |
| HP            | 15                          | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| HP            | EliteBook 840 G1            | [1071e10a2c](https://linux-hardware.org/?probe=1071e10a2c) | Nov 23, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [0483728614](https://linux-hardware.org/?probe=0483728614) | Nov 23, 2022 |
| Lenovo        | ThinkPad T480 20L50011US    | [2f32726e0d](https://linux-hardware.org/?probe=2f32726e0d) | Nov 23, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [2eec6b4f39](https://linux-hardware.org/?probe=2eec6b4f39) | Nov 22, 2022 |
| Acer          | Aspire A715-42G             | [88f4469c5d](https://linux-hardware.org/?probe=88f4469c5d) | Nov 21, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [bce41d01ae](https://linux-hardware.org/?probe=bce41d01ae) | Nov 21, 2022 |
| Acer          | Aspire A715-42G             | [687044a497](https://linux-hardware.org/?probe=687044a497) | Nov 21, 2022 |
| HP            | 245 G5 Notebook PC          | [deed1dcf4d](https://linux-hardware.org/?probe=deed1dcf4d) | Nov 21, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2da86d4e21](https://linux-hardware.org/?probe=2da86d4e21) | Nov 21, 2022 |
| Dell          | Inspiron 3505               | [634f7d190d](https://linux-hardware.org/?probe=634f7d190d) | Nov 21, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [88bbdb925b](https://linux-hardware.org/?probe=88bbdb925b) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [8b07bd39c9](https://linux-hardware.org/?probe=8b07bd39c9) | Nov 19, 2022 |
| HP            | Laptop 15s-du3xxx           | [a90cea62ff](https://linux-hardware.org/?probe=a90cea62ff) | Nov 19, 2022 |
| Sony          | SVE15133CNB                 | [3d78ceb657](https://linux-hardware.org/?probe=3d78ceb657) | Nov 19, 2022 |
| Sony          | VPCEA45FG                   | [cb719dbd60](https://linux-hardware.org/?probe=cb719dbd60) | Nov 19, 2022 |
| ASUSTek       | K53SM                       | [ea2f588ed8](https://linux-hardware.org/?probe=ea2f588ed8) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L6S3L400    | [ae98e93989](https://linux-hardware.org/?probe=ae98e93989) | Nov 18, 2022 |
| Acer          | Nitro AN515-42              | [785ae6891c](https://linux-hardware.org/?probe=785ae6891c) | Nov 17, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [190c6d9cc7](https://linux-hardware.org/?probe=190c6d9cc7) | Nov 17, 2022 |
| HP            | Laptop 15s-eq0xxx           | [e48c737ed6](https://linux-hardware.org/?probe=e48c737ed6) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [5c49c7037b](https://linux-hardware.org/?probe=5c49c7037b) | Nov 16, 2022 |
| Dell          | Inspiron 3543               | [15cc03ec87](https://linux-hardware.org/?probe=15cc03ec87) | Nov 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [94983688d2](https://linux-hardware.org/?probe=94983688d2) | Nov 16, 2022 |
| Acer          | Aspire E5-573G              | [6b14e6a41b](https://linux-hardware.org/?probe=6b14e6a41b) | Nov 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [119f9da4af](https://linux-hardware.org/?probe=119f9da4af) | Nov 16, 2022 |
| Dell          | Inspiron N5050              | [ddc155c281](https://linux-hardware.org/?probe=ddc155c281) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | [dea1636b05](https://linux-hardware.org/?probe=dea1636b05) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | [9ed613b632](https://linux-hardware.org/?probe=9ed613b632) | Nov 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [35cb137655](https://linux-hardware.org/?probe=35cb137655) | Nov 15, 2022 |
| Dell          | Precision 7510              | [111903e578](https://linux-hardware.org/?probe=111903e578) | Nov 14, 2022 |
| Dell          | Latitude 3190               | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| MSI           | Modern 14 A10M              | [9708710429](https://linux-hardware.org/?probe=9708710429) | Nov 14, 2022 |
| Dell          | Latitude 7480               | [2e485b361c](https://linux-hardware.org/?probe=2e485b361c) | Nov 14, 2022 |
| Dell          | Vostro 3401                 | [e8acccbe3c](https://linux-hardware.org/?probe=e8acccbe3c) | Nov 13, 2022 |
| Dell          | Vostro 3401                 | [5279c2e222](https://linux-hardware.org/?probe=5279c2e222) | Nov 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e19fef63c9](https://linux-hardware.org/?probe=e19fef63c9) | Nov 12, 2022 |
| ASUSTek       | X550LC                      | [2cfd92452e](https://linux-hardware.org/?probe=2cfd92452e) | Nov 12, 2022 |
| HP            | Notebook                    | [2419e7d149](https://linux-hardware.org/?probe=2419e7d149) | Nov 12, 2022 |
| HP            | Notebook                    | [97c6c3c412](https://linux-hardware.org/?probe=97c6c3c412) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [adf09c8455](https://linux-hardware.org/?probe=adf09c8455) | Nov 11, 2022 |
| Lenovo        | V310-14ISK 80SX             | [0e0de3ee86](https://linux-hardware.org/?probe=0e0de3ee86) | Nov 11, 2022 |
| Dell          | Latitude E6420              | [70ebe12e06](https://linux-hardware.org/?probe=70ebe12e06) | Nov 11, 2022 |
| HP            | EliteBook 840 G1            | [671714bc5a](https://linux-hardware.org/?probe=671714bc5a) | Nov 11, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d020fa04fe](https://linux-hardware.org/?probe=d020fa04fe) | Nov 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3bcdc36fff](https://linux-hardware.org/?probe=3bcdc36fff) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [217544b651](https://linux-hardware.org/?probe=217544b651) | Nov 11, 2022 |
| HP            | Pavilion Laptop 14-dv2xx... | [4ff5cb368c](https://linux-hardware.org/?probe=4ff5cb368c) | Nov 10, 2022 |
| HP            | 2000                        | [5045f21cc3](https://linux-hardware.org/?probe=5045f21cc3) | Nov 10, 2022 |
| Dell          | Latitude E6420              | [4be923e459](https://linux-hardware.org/?probe=4be923e459) | Nov 10, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [4366631db8](https://linux-hardware.org/?probe=4366631db8) | Nov 09, 2022 |
| Dell          | Vostro 3401                 | [0b1b8bf15d](https://linux-hardware.org/?probe=0b1b8bf15d) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-dv2xx... | [bbc7236402](https://linux-hardware.org/?probe=bbc7236402) | Nov 08, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [cb9f2f3d87](https://linux-hardware.org/?probe=cb9f2f3d87) | Nov 08, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [27fcb50d7a](https://linux-hardware.org/?probe=27fcb50d7a) | Nov 07, 2022 |
| Dell          | Latitude 3190               | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [006e91ea03](https://linux-hardware.org/?probe=006e91ea03) | Nov 06, 2022 |
| HP            | EliteBook 840 G1            | [43c1e8b8a8](https://linux-hardware.org/?probe=43c1e8b8a8) | Nov 06, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [1f4a1244b3](https://linux-hardware.org/?probe=1f4a1244b3) | Nov 06, 2022 |
| Dell          | Inspiron 15-3567            | [390f51010e](https://linux-hardware.org/?probe=390f51010e) | Nov 06, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [1fd362dd3c](https://linux-hardware.org/?probe=1fd362dd3c) | Nov 06, 2022 |
| HP            | 245 G5 Notebook PC          | [4d52b15940](https://linux-hardware.org/?probe=4d52b15940) | Nov 06, 2022 |
| HP            | Notebook                    | [49e26e62f7](https://linux-hardware.org/?probe=49e26e62f7) | Nov 05, 2022 |
| Dell          | G3 3500                     | [36918f305b](https://linux-hardware.org/?probe=36918f305b) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8f3cf6499e](https://linux-hardware.org/?probe=8f3cf6499e) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2eb5db395b](https://linux-hardware.org/?probe=2eb5db395b) | Nov 05, 2022 |
| MSI           | Bravo 15 B5DD               | [2c605465bb](https://linux-hardware.org/?probe=2c605465bb) | Nov 04, 2022 |
| Dell          | Inspiron 3543               | [9e6efb3e67](https://linux-hardware.org/?probe=9e6efb3e67) | Nov 04, 2022 |
| Dell          | Inspiron N5050              | [ecea714e26](https://linux-hardware.org/?probe=ecea714e26) | Nov 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f790aefcad](https://linux-hardware.org/?probe=f790aefcad) | Nov 03, 2022 |
| Lenovo        | E41-25 81FS                 | [57df10cb95](https://linux-hardware.org/?probe=57df10cb95) | Nov 03, 2022 |
| Lenovo        | E41-25 81FS                 | [5d9743e91d](https://linux-hardware.org/?probe=5d9743e91d) | Nov 02, 2022 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [95ddb63cb1](https://linux-hardware.org/?probe=95ddb63cb1) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [aa6c06f2bb](https://linux-hardware.org/?probe=aa6c06f2bb) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [584db1dcb2](https://linux-hardware.org/?probe=584db1dcb2) | Nov 02, 2022 |
| Dell          | Latitude 3420               | [9c2b9ab298](https://linux-hardware.org/?probe=9c2b9ab298) | Nov 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6323d7e1b3](https://linux-hardware.org/?probe=6323d7e1b3) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| Lenovo        | G50-80 80E5                 | [0470f02ccb](https://linux-hardware.org/?probe=0470f02ccb) | Nov 01, 2022 |
| Acer          | Unknown                     | [284f534a6a](https://linux-hardware.org/?probe=284f534a6a) | Oct 31, 2022 |
| Acer          | Unknown                     | [27b5267fa3](https://linux-hardware.org/?probe=27b5267fa3) | Oct 31, 2022 |
| Dell          | Inspiron 3542               | [dcccad24af](https://linux-hardware.org/?probe=dcccad24af) | Oct 31, 2022 |
| Lenovo        | Legion Y7000 2019 1050 8... | [3821dabcb9](https://linux-hardware.org/?probe=3821dabcb9) | Oct 31, 2022 |
| HP            | 2000                        | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | [26a8adcee2](https://linux-hardware.org/?probe=26a8adcee2) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [dea1724953](https://linux-hardware.org/?probe=dea1724953) | Oct 31, 2022 |
| HP            | Laptop 15s-gr0xxx           | [02d23cb1b9](https://linux-hardware.org/?probe=02d23cb1b9) | Oct 30, 2022 |
| Sony          | VPCEA45FG                   | [3448172ca3](https://linux-hardware.org/?probe=3448172ca3) | Oct 29, 2022 |
| Acer          | Extensa 215-54              | [0fe46d7655](https://linux-hardware.org/?probe=0fe46d7655) | Oct 29, 2022 |
| Dell          | Vostro 3580                 | [74a79dbdb6](https://linux-hardware.org/?probe=74a79dbdb6) | Oct 29, 2022 |
| HP            | Laptop 15s-gr0xxx           | [f7155fd671](https://linux-hardware.org/?probe=f7155fd671) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [9b90ea1d4d](https://linux-hardware.org/?probe=9b90ea1d4d) | Oct 27, 2022 |
| Dell          | Latitude E7470              | [a9274c9070](https://linux-hardware.org/?probe=a9274c9070) | Oct 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [09d3217ce4](https://linux-hardware.org/?probe=09d3217ce4) | Oct 25, 2022 |
| ASUSTek       | X550LC                      | [75c0c3e97b](https://linux-hardware.org/?probe=75c0c3e97b) | Oct 24, 2022 |
| HP            | Laptop 15s-gy0xxx           | [d1219c1387](https://linux-hardware.org/?probe=d1219c1387) | Oct 23, 2022 |
| Dell          | Vostro 3491                 | [8809be3a93](https://linux-hardware.org/?probe=8809be3a93) | Oct 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9a104497e3](https://linux-hardware.org/?probe=9a104497e3) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [bea9c6b47b](https://linux-hardware.org/?probe=bea9c6b47b) | Oct 23, 2022 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [d37b700ffb](https://linux-hardware.org/?probe=d37b700ffb) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KY00     | [657b1ee865](https://linux-hardware.org/?probe=657b1ee865) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [2f761b8c2f](https://linux-hardware.org/?probe=2f761b8c2f) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f07691d6b1](https://linux-hardware.org/?probe=f07691d6b1) | Oct 20, 2022 |
| Acer          | Aspire E5-553G              | [8e75bbadf5](https://linux-hardware.org/?probe=8e75bbadf5) | Oct 20, 2022 |
| Lenovo        | ThinkPad T450s 20BWA0DW0... | [117e1e8e03](https://linux-hardware.org/?probe=117e1e8e03) | Oct 20, 2022 |
| Dell          | Vostro 3500                 | [5d1bb5d8aa](https://linux-hardware.org/?probe=5d1bb5d8aa) | Oct 19, 2022 |
| HP            | 255 G8 Notebook PC          | [2f69a96661](https://linux-hardware.org/?probe=2f69a96661) | Oct 18, 2022 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [96a36651bf](https://linux-hardware.org/?probe=96a36651bf) | Oct 18, 2022 |
| Lenovo        | G500 20236                  | [e38bd0cb56](https://linux-hardware.org/?probe=e38bd0cb56) | Oct 17, 2022 |
| HP            | 255 G8 Notebook PC          | [cb651a5071](https://linux-hardware.org/?probe=cb651a5071) | Oct 17, 2022 |
| Dell          | Latitude E6430s             | [ca202dddd6](https://linux-hardware.org/?probe=ca202dddd6) | Oct 17, 2022 |
| HP            | InsydeH2O EFI BIOS          | [0c9c2f85b4](https://linux-hardware.org/?probe=0c9c2f85b4) | Oct 17, 2022 |
| Dell          | Inspiron 3521               | [f7b9f3cab2](https://linux-hardware.org/?probe=f7b9f3cab2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [82ab4c516a](https://linux-hardware.org/?probe=82ab4c516a) | Oct 16, 2022 |
| Timi          | Mi NoteBook Pro             | [dbdd6179c7](https://linux-hardware.org/?probe=dbdd6179c7) | Oct 16, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [411a334a74](https://linux-hardware.org/?probe=411a334a74) | Oct 16, 2022 |
| Dell          | Inspiron 15-3567            | [2b00bd7a92](https://linux-hardware.org/?probe=2b00bd7a92) | Oct 15, 2022 |
| HP            | EliteBook 840 G1            | [06cda048c3](https://linux-hardware.org/?probe=06cda048c3) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [2ba7e8c424](https://linux-hardware.org/?probe=2ba7e8c424) | Oct 14, 2022 |
| HP            | EliteBook 840 G3            | [5e4c8b36d2](https://linux-hardware.org/?probe=5e4c8b36d2) | Oct 14, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [7ca53492d5](https://linux-hardware.org/?probe=7ca53492d5) | Oct 14, 2022 |
| Dell          | Inspiron 3543               | [25556b5183](https://linux-hardware.org/?probe=25556b5183) | Oct 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f4d190e864](https://linux-hardware.org/?probe=f4d190e864) | Oct 13, 2022 |
| HP            | Laptop 15s-du3xxx           | [5985f3564a](https://linux-hardware.org/?probe=5985f3564a) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | [d71c1d033a](https://linux-hardware.org/?probe=d71c1d033a) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | [07783bd6a7](https://linux-hardware.org/?probe=07783bd6a7) | Oct 13, 2022 |
| Dell          | Vostro 3446                 | [da79693286](https://linux-hardware.org/?probe=da79693286) | Oct 13, 2022 |
| HP            | Laptop 14s-ef1xxx           | [4a38e7efc3](https://linux-hardware.org/?probe=4a38e7efc3) | Oct 13, 2022 |
| Dell          | G3 3500                     | [831b4e147e](https://linux-hardware.org/?probe=831b4e147e) | Oct 12, 2022 |
| AVITA         | NS14A6                      | [0ed9ac0a2b](https://linux-hardware.org/?probe=0ed9ac0a2b) | Oct 11, 2022 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | [36abc6f39f](https://linux-hardware.org/?probe=36abc6f39f) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [40adf0a5d8](https://linux-hardware.org/?probe=40adf0a5d8) | Oct 11, 2022 |
| AVITA         | NS14A6                      | [27412eff74](https://linux-hardware.org/?probe=27412eff74) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Dell          | Inspiron 5584               | [0800772df3](https://linux-hardware.org/?probe=0800772df3) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3e7ef86329](https://linux-hardware.org/?probe=3e7ef86329) | Oct 09, 2022 |
| Sony          | VPCEB46FG                   | [71e2273974](https://linux-hardware.org/?probe=71e2273974) | Oct 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c0c2e0ca69](https://linux-hardware.org/?probe=c0c2e0ca69) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | [615578d390](https://linux-hardware.org/?probe=615578d390) | Oct 08, 2022 |
| Lenovo        | IdeaPad S540-15IML D 81N... | [f7d3139c23](https://linux-hardware.org/?probe=f7d3139c23) | Oct 08, 2022 |
| HP            | Pavilion dv6                | [0c2329c8d6](https://linux-hardware.org/?probe=0c2329c8d6) | Oct 07, 2022 |
| HP            | Laptop 15-bs0xx             | [6009358723](https://linux-hardware.org/?probe=6009358723) | Oct 07, 2022 |
| HP            | Laptop 15-bs0xx             | [c37715196b](https://linux-hardware.org/?probe=c37715196b) | Oct 07, 2022 |
| Dell          | Vostro 3578                 | [4fa0e607b7](https://linux-hardware.org/?probe=4fa0e607b7) | Oct 07, 2022 |
| HP            | Laptop 14s-dr1xxx           | [00d04b6a56](https://linux-hardware.org/?probe=00d04b6a56) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [a431b20f04](https://linux-hardware.org/?probe=a431b20f04) | Oct 07, 2022 |
| Acer          | Nitro AN515-58              | [6a9f611fd5](https://linux-hardware.org/?probe=6a9f611fd5) | Oct 07, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [4bb56ef4e6](https://linux-hardware.org/?probe=4bb56ef4e6) | Oct 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [20ea012e04](https://linux-hardware.org/?probe=20ea012e04) | Oct 06, 2022 |
| HP            | 15                          | [9f0981ed52](https://linux-hardware.org/?probe=9f0981ed52) | Oct 06, 2022 |
| Dell          | Vostro 2520                 | [da789d3a06](https://linux-hardware.org/?probe=da789d3a06) | Oct 06, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | [4fe1810c2c](https://linux-hardware.org/?probe=4fe1810c2c) | Oct 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [f6fc1950ac](https://linux-hardware.org/?probe=f6fc1950ac) | Oct 05, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [cb204abf9b](https://linux-hardware.org/?probe=cb204abf9b) | Oct 04, 2022 |
| Lenovo        | ThinkPad T490 20RYS07R00    | [d6be1b9cf9](https://linux-hardware.org/?probe=d6be1b9cf9) | Oct 04, 2022 |
| Dell          | Latitude E7440              | [8dda778da4](https://linux-hardware.org/?probe=8dda778da4) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [62b67bffae](https://linux-hardware.org/?probe=62b67bffae) | Oct 04, 2022 |
| HP            | ProBook 4540s               | [ef3e02b39c](https://linux-hardware.org/?probe=ef3e02b39c) | Oct 03, 2022 |
| HP            | EliteBook 840 G5            | [5d6a3f11e7](https://linux-hardware.org/?probe=5d6a3f11e7) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7d1f20cf17](https://linux-hardware.org/?probe=7d1f20cf17) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dfd00dd2d1](https://linux-hardware.org/?probe=dfd00dd2d1) | Oct 03, 2022 |
| Dell          | Inspiron 3543               | [9e5ab25f54](https://linux-hardware.org/?probe=9e5ab25f54) | Oct 02, 2022 |
| MICROMAX      | Canvas Lapbook L1161        | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [88c05ba074](https://linux-hardware.org/?probe=88c05ba074) | Oct 01, 2022 |
| ASUSTek       | K53SM                       | [f05f33fa9b](https://linux-hardware.org/?probe=f05f33fa9b) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | [82e89b9263](https://linux-hardware.org/?probe=82e89b9263) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | [e64a9cf0e2](https://linux-hardware.org/?probe=e64a9cf0e2) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | [1a210b9eb5](https://linux-hardware.org/?probe=1a210b9eb5) | Oct 01, 2022 |
| Lenovo        | ThinkPad L450 20DSS00M01    | [e52e98a7e7](https://linux-hardware.org/?probe=e52e98a7e7) | Oct 01, 2022 |
| Dell          | G3 3500                     | [245ebaabe5](https://linux-hardware.org/?probe=245ebaabe5) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/India/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 717       | 20.82%  |
| Ubuntu 18.04                 | 277       | 8.04%   |
| Ubuntu 22.04                 | 242       | 7.03%   |
| Arch                         | 80        | 2.32%   |
| Arch Rolling                 | 73        | 2.12%   |
| Pop!_OS 22.04                | 70        | 2.03%   |
| Zorin 16                     | 61        | 1.77%   |
| KDE neon 20.04               | 56        | 1.63%   |
| Pop!_OS 20.04                | 54        | 1.57%   |
| Fedora 36                    | 53        | 1.54%   |
| Fedora 37                    | 52        | 1.51%   |
| ArcoLinux Rolling            | 52        | 1.51%   |
| Pop!_OS 21.04                | 49        | 1.42%   |
| Ubuntu 20.10                 | 46        | 1.34%   |
| Fedora 34                    | 45        | 1.31%   |
| Fedora 38                    | 44        | 1.28%   |
| Ubuntu 19.10                 | 39        | 1.13%   |
| Zorin 15                     | 38        | 1.1%    |
| Ubuntu 21.04                 | 38        | 1.1%    |
| Pop!_OS 20.10                | 36        | 1.05%   |
| Manjaro                      | 34        | 0.99%   |
| OpenMandriva 4.2             | 33        | 0.96%   |
| Ubuntu 19.04                 | 32        | 0.93%   |
| Fedora 35                    | 32        | 0.93%   |
| Linux Mint 21.1              | 30        | 0.87%   |
| Ubuntu 21.10                 | 29        | 0.84%   |
| OpenMandriva 4.3             | 29        | 0.84%   |
| Debian 11                    | 29        | 0.84%   |
| Linux Mint 20.2              | 26        | 0.75%   |
| Fedora 32                    | 26        | 0.75%   |
| Ubuntu Unity 16.04           | 25        | 0.73%   |
| Linux Mint 20.3              | 25        | 0.73%   |
| Linux Mint 20.1              | 25        | 0.73%   |
| Fedora 33                    | 25        | 0.73%   |
| openSUSE Tumbleweed-XXXXXXXX | 23        | 0.67%   |
| Linux Mint 20                | 23        | 0.67%   |
| Ubuntu 22.10                 | 22        | 0.64%   |
| Kubuntu 20.04                | 19        | 0.55%   |
| OpenMandriva 23.03           | 18        | 0.52%   |
| Elementary 6.1               | 18        | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1444      | 43.51%  |
| Fedora        | 274       | 8.26%   |
| Pop!_OS       | 218       | 6.57%   |
| Linux Mint    | 155       | 4.67%   |
| Arch          | 146       | 4.4%    |
| OpenMandriva  | 108       | 3.25%   |
| Zorin         | 99        | 2.98%   |
| Manjaro       | 99        | 2.98%   |
| KDE neon      | 79        | 2.38%   |
| Kali          | 72        | 2.17%   |
| Debian        | 70        | 2.11%   |
| Kubuntu       | 59        | 1.78%   |
| ArcoLinux     | 58        | 1.75%   |
| Elementary    | 46        | 1.39%   |
| Ubuntu Unity  | 44        | 1.33%   |
| Endless       | 36        | 1.08%   |
| openSUSE      | 28        | 0.84%   |
| Xubuntu       | 27        | 0.81%   |
| Garuda Linux  | 21        | 0.63%   |
| EndeavourOS   | 20        | 0.6%    |
| RHEL          | 18        | 0.54%   |
| ROSA          | 16        | 0.48%   |
| Ubuntu Budgie | 15        | 0.45%   |
| Clear Linux   | 14        | 0.42%   |
| Xero          | 12        | 0.36%   |
| Parrot        | 11        | 0.33%   |
| Ubuntu MATE   | 10        | 0.3%    |
| MX            | 10        | 0.3%    |
| Void Linux    | 9         | 0.27%   |
| Lubuntu       | 9         | 0.27%   |
| Solus         | 8         | 0.24%   |
| Nobara        | 7         | 0.21%   |
| Gentoo        | 7         | 0.21%   |
| CentOS        | 7         | 0.21%   |
| Artix         | 7         | 0.21%   |
| Slackware     | 4         | 0.12%   |
| LMDE          | 4         | 0.12%   |
| Archcraft     | 4         | 0.12%   |
| UbuntuDDE     | 3         | 0.09%   |
| SteamOS       | 3         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 112       | 3.03%   |
| 5.4.0-40-generic         | 54        | 1.46%   |
| 5.15.0-56-generic        | 45        | 1.22%   |
| 5.11.0-27-generic        | 34        | 0.92%   |
| 5.10.14-desktop-1omv4002 | 33        | 0.89%   |
| 5.4.0-48-generic         | 30        | 0.81%   |
| 5.4.0-26-generic         | 30        | 0.81%   |
| 5.4.0-47-generic         | 29        | 0.79%   |
| 5.11.0-7620-generic      | 28        | 0.76%   |
| 5.4.0-58-generic         | 27        | 0.73%   |
| 5.16.7-desktop-1omv4003  | 27        | 0.73%   |
| 5.4.0-52-generic         | 26        | 0.7%    |
| 5.4.0-29-generic         | 24        | 0.65%   |
| 5.3.0-28-generic         | 24        | 0.65%   |
| 5.15.0-58-generic        | 24        | 0.65%   |
| 5.11.0-40-generic        | 23        | 0.62%   |
| 5.4.0-45-generic         | 22        | 0.6%    |
| 5.11.0-43-generic        | 22        | 0.6%    |
| 5.11.0-25-generic        | 22        | 0.6%    |
| 5.8.0-53-generic         | 21        | 0.57%   |
| 5.8.0-44-generic         | 21        | 0.57%   |
| 5.8.0-43-generic         | 21        | 0.57%   |
| 5.15.0-52-generic        | 21        | 0.57%   |
| 5.15.0-46-generic        | 21        | 0.57%   |
| 5.11.0-38-generic        | 21        | 0.57%   |
| 5.8.0-55-generic         | 20        | 0.54%   |
| 5.8.0-48-generic         | 20        | 0.54%   |
| 5.4.0-37-generic         | 20        | 0.54%   |
| 5.3.0-40-generic         | 20        | 0.54%   |
| 5.4.0-74-generic         | 19        | 0.51%   |
| 5.11.0-37-generic        | 19        | 0.51%   |
| 6.2.6-desktop-1omv2390   | 18        | 0.49%   |
| 5.4.0-39-generic         | 18        | 0.49%   |
| 5.19.0-41-generic        | 18        | 0.49%   |
| 5.13.0-30-generic        | 18        | 0.49%   |
| 4.15.0-45-generic        | 18        | 0.49%   |
| 5.8.0-7630-generic       | 17        | 0.46%   |
| 5.3.0-51-generic         | 17        | 0.46%   |
| 5.13.0-40-generic        | 17        | 0.46%   |
| 5.0.0-37-generic         | 17        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 647       | 18.29%  |
| 5.15.0  | 298       | 8.42%   |
| 5.11.0  | 261       | 7.38%   |
| 5.8.0   | 229       | 6.47%   |
| 4.15.0  | 153       | 4.32%   |
| 5.13.0  | 151       | 4.27%   |
| 5.3.0   | 144       | 4.07%   |
| 5.19.0  | 142       | 4.01%   |
| 5.0.0   | 91        | 2.57%   |
| 4.18.0  | 64        | 1.81%   |
| 5.10.0  | 55        | 1.55%   |
| 5.10.14 | 33        | 0.93%   |
| 6.2.6   | 32        | 0.9%    |
| 5.16.7  | 28        | 0.79%   |
| 6.2.0   | 27        | 0.76%   |
| 6.1.0   | 25        | 0.71%   |
| 5.14.0  | 24        | 0.68%   |
| 4.4.0   | 19        | 0.54%   |
| 5.17.5  | 18        | 0.51%   |
| 6.0.12  | 17        | 0.48%   |
| 6.0.0   | 15        | 0.42%   |
| 4.19.0  | 15        | 0.42%   |
| 6.1.1   | 13        | 0.37%   |
| 6.0.8   | 13        | 0.37%   |
| 6.0.6   | 12        | 0.34%   |
| 5.9.0   | 11        | 0.31%   |
| 5.7.0   | 11        | 0.31%   |
| 6.3.5   | 10        | 0.28%   |
| 5.18.0  | 10        | 0.28%   |
| 5.15.11 | 10        | 0.28%   |
| 6.3.8   | 8         | 0.23%   |
| 6.2.9   | 8         | 0.23%   |
| 6.0.9   | 8         | 0.23%   |
| 5.17.4  | 8         | 0.23%   |
| 5.16.11 | 8         | 0.23%   |
| 5.15.5  | 8         | 0.23%   |
| 5.13.9  | 8         | 0.23%   |
| 5.13.12 | 8         | 0.23%   |
| 6.2.8   | 7         | 0.2%    |
| 6.2.11  | 7         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 673       | 19.26%  |
| 5.15    | 395       | 11.3%   |
| 5.11    | 293       | 8.38%   |
| 5.8     | 276       | 7.9%    |
| 5.13    | 191       | 5.46%   |
| 5.19    | 187       | 5.35%   |
| 5.3     | 164       | 4.69%   |
| 4.15    | 153       | 4.38%   |
| 5.10    | 143       | 4.09%   |
| 6.2     | 106       | 3.03%   |
| 6.0     | 97        | 2.78%   |
| 5.0     | 93        | 2.66%   |
| 6.1     | 90        | 2.58%   |
| 5.16    | 79        | 2.26%   |
| 5.17    | 69        | 1.97%   |
| 4.18    | 66        | 1.89%   |
| 5.14    | 57        | 1.63%   |
| 5.18    | 50        | 1.43%   |
| 5.12    | 45        | 1.29%   |
| 6.3     | 44        | 1.26%   |
| 5.9     | 43        | 1.23%   |
| 5.7     | 40        | 1.14%   |
| 5.6     | 27        | 0.77%   |
| 5.5     | 22        | 0.63%   |
| 4.19    | 21        | 0.6%    |
| 4.4     | 20        | 0.57%   |
| 6.4     | 16        | 0.46%   |
| 4.9     | 11        | 0.31%   |
| 5.2     | 6         | 0.17%   |
| 5.1     | 3         | 0.09%   |
| 3.16    | 3         | 0.09%   |
| 3.10    | 3         | 0.09%   |
| 4.13    | 2         | 0.06%   |
| 4.1     | 2         | 0.06%   |
| 4.20    | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.16    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 4.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3150      | 98.84%  |
| i686   | 36        | 1.13%   |
| armv7l | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1948      | 58.71%  |
| KDE5              | 390       | 11.75%  |
| Unknown           | 320       | 9.64%   |
| XFCE              | 157       | 4.73%   |
| X-Cinnamon        | 127       | 3.83%   |
| KDE               | 75        | 2.26%   |
| Unity             | 45        | 1.36%   |
| Pantheon          | 44        | 1.33%   |
| MATE              | 33        | 0.99%   |
| Cinnamon          | 30        | 0.9%    |
| i3                | 21        | 0.63%   |
| GNOME Flashback   | 21        | 0.63%   |
| Budgie            | 21        | 0.63%   |
| LXQt              | 13        | 0.39%   |
| LXDE              | 10        | 0.3%    |
| Deepin            | 9         | 0.27%   |
| awesome           | 9         | 0.27%   |
| KDE4              | 7         | 0.21%   |
| bspwm             | 7         | 0.21%   |
| Hyprland          | 6         | 0.18%   |
| qtile             | 5         | 0.15%   |
| sway              | 4         | 0.12%   |
| LeftWM            | 3         | 0.09%   |
| xmonad            | 2         | 0.06%   |
| openbox           | 2         | 0.06%   |
| lightdm-xsession  | 2         | 0.06%   |
| dwm               | 2         | 0.06%   |
| Yaru:ubuntu:GNOME | 1         | 0.03%   |
| i3-with-shmlog    | 1         | 0.03%   |
| i3-gaps           | 1         | 0.03%   |
| GNOME Classic     | 1         | 0.03%   |
| chadwm            | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2394      | 72.92%  |
| Wayland | 649       | 19.77%  |
| Unknown | 207       | 6.31%   |
| Tty     | 33        | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1587      | 48%     |
| GDM     | 609       | 18.42%  |
| GDM3    | 426       | 12.89%  |
| SDDM    | 356       | 10.77%  |
| LightDM | 226       | 6.84%   |
| TDM     | 79        | 2.39%   |
| XDM     | 9         | 0.27%   |
| KDM     | 6         | 0.18%   |
| LXDM    | 4         | 0.12%   |
| SLiM    | 2         | 0.06%   |
| Ly      | 2         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IN   | 1989      | 60.29%  |
| en_US   | 921       | 27.92%  |
| Unknown | 256       | 7.76%   |
| en_GB   | 57        | 1.73%   |
| C       | 47        | 1.42%   |
| en_AG   | 8         | 0.24%   |
| en_CA   | 3         | 0.09%   |
| zh_TW   | 2         | 0.06%   |
| POSIX   | 2         | 0.06%   |
| mr_IN   | 2         | 0.06%   |
| en_IE   | 2         | 0.06%   |
| en_AU   | 2         | 0.06%   |
| pl_PL   | 1         | 0.03%   |
| ks_IN   | 1         | 0.03%   |
| es_ES   | 1         | 0.03%   |
| en_SG   | 1         | 0.03%   |
| en_BW   | 1         | 0.03%   |
| Default | 1         | 0.03%   |
| C.UTF8  | 1         | 0.03%   |
| aa_DJ   | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2027      | 62.5%   |
| BIOS | 1216      | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2620      | 80.1%   |
| Btrfs   | 335       | 10.24%  |
| Overlay | 131       | 4%      |
| Unknown | 59        | 1.8%    |
| Tmpfs   | 48        | 1.47%   |
| Xfs     | 37        | 1.13%   |
| Zfs     | 16        | 0.49%   |
| F2fs    | 11        | 0.34%   |
| Ext2    | 7         | 0.21%   |
| Ext3    | 6         | 0.18%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1674      | 51.56%  |
| GPT     | 1334      | 41.08%  |
| MBR     | 239       | 7.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2851      | 88.1%   |
| Yes       | 385       | 11.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1938      | 59.91%  |
| Yes       | 1297      | 40.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 776       | 24.36%  |
| Dell                           | 717       | 22.5%   |
| Hewlett-Packard                | 710       | 22.28%  |
| ASUSTek Computer               | 396       | 12.43%  |
| Acer                           | 256       | 8.04%   |
| MSI                            | 51        | 1.6%    |
| Sony                           | 49        | 1.54%   |
| Toshiba                        | 34        | 1.07%   |
| Timi                           | 31        | 0.97%   |
| Apple                          | 26        | 0.82%   |
| Samsung Electronics            | 25        | 0.78%   |
| AVITA                          | 20        | 0.63%   |
| HCL Infosystems Limited        | 8         | 0.25%   |
| Fujitsu                        | 8         | 0.25%   |
| HUAWEI                         | 7         | 0.22%   |
| HONOR                          | 7         | 0.22%   |
| LG Electronics                 | 5         | 0.16%   |
| Intel                          | 5         | 0.16%   |
| Google                         | 5         | 0.16%   |
| Alienware                      | 5         | 0.16%   |
| Unknown                        | 5         | 0.16%   |
| Gateway                        | 4         | 0.13%   |
| eMachines                      | 4         | 0.13%   |
| Valve                          | 3         | 0.09%   |
| realme                         | 3         | 0.09%   |
| Razer                          | 2         | 0.06%   |
| MICROMAX                       | 2         | 0.06%   |
| ITI LIMITED                    | 2         | 0.06%   |
| Infinix                        | 2         | 0.06%   |
| Dynabook                       | 2         | 0.06%   |
| Coconics Private Limited       | 2         | 0.06%   |
| WIPRO                          | 1         | 0.03%   |
| System76                       | 1         | 0.03%   |
| SmbiosType1_SystemManufacturer | 1         | 0.03%   |
| RDP                            | 1         | 0.03%   |
| ONDA                           | 1         | 0.03%   |
| Notebook                       | 1         | 0.03%   |
| NEC Computers                  | 1         | 0.03%   |
| iBall                          | 1         | 0.03%   |
| HASEE Computer                 | 1         | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP Notebook                          | 76        | 2.39%   |
| HP 15                                | 33        | 1.04%   |
| HP Pavilion 15                       | 30        | 0.94%   |
| HP Pavilion g6                       | 27        | 0.85%   |
| Dell Inspiron 3542                   | 27        | 0.85%   |
| Lenovo E41-25 81FS                   | 22        | 0.69%   |
| Dell Inspiron 15-3567                | 22        | 0.69%   |
| HP Laptop 15-bs0xx                   | 21        | 0.66%   |
| Dell Inspiron 5570                   | 20        | 0.63%   |
| Unknown                              | 19        | 0.6%    |
| Lenovo IdeaPad 330-15IKB 81DE        | 18        | 0.56%   |
| HP Pavilion Notebook                 | 18        | 0.56%   |
| Dell Inspiron 3521                   | 18        | 0.56%   |
| ASUS TUF Gaming FX505DT_FX505DT      | 17        | 0.53%   |
| Acer Aspire A715-75G                 | 16        | 0.5%    |
| Lenovo G50-80 80E5                   | 15        | 0.47%   |
| Dell Vostro 3480                     | 15        | 0.47%   |
| Dell Vostro 15-3568                  | 15        | 0.47%   |
| HP Laptop 15-da0xxx                  | 13        | 0.41%   |
| Dell Vostro 3578                     | 13        | 0.41%   |
| Dell Inspiron 1545                   | 13        | 0.41%   |
| HP Pavilion Gaming Laptop 15-ec2xxx  | 12        | 0.38%   |
| Dell Inspiron 5559                   | 12        | 0.38%   |
| ASUS X510UNR                         | 12        | 0.38%   |
| Lenovo IdeaPad 320-15ISK 80XH        | 11        | 0.35%   |
| Lenovo G50-45 80E3                   | 11        | 0.35%   |
| HP Pavilion Laptop 14-dv0xxx         | 11        | 0.35%   |
| HP Laptop 15-bw0xx                   | 11        | 0.35%   |
| Dell Inspiron N5010                  | 11        | 0.35%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR | 11        | 0.35%   |
| ASUS TUF Gaming FX505DY_FX505DY      | 11        | 0.35%   |
| Timi Mi NoteBook Ultra               | 10        | 0.31%   |
| HP Pavilion dv6                      | 10        | 0.31%   |
| Dell Vostro 3478                     | 10        | 0.31%   |
| AVITA NS14A8                         | 10        | 0.31%   |
| ASUS X556UQK                         | 10        | 0.31%   |
| Lenovo ThinkBook 14-IML 20RV         | 9         | 0.28%   |
| Lenovo IdeaPad S540-15IWL D 81NE     | 9         | 0.28%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 9         | 0.28%   |
| Lenovo IdeaPad 520-15IKB 81BF        | 9         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 342       | 10.73%  |
| Lenovo ThinkPad   | 272       | 8.54%   |
| Lenovo IdeaPad    | 268       | 8.41%   |
| HP Pavilion       | 203       | 6.37%   |
| HP Laptop         | 159       | 4.99%   |
| ASUS VivoBook     | 159       | 4.99%   |
| Dell Latitude     | 152       | 4.77%   |
| Acer Aspire       | 146       | 4.58%   |
| Dell Vostro       | 134       | 4.21%   |
| HP Notebook       | 77        | 2.42%   |
| HP EliteBook      | 56        | 1.76%   |
| HP ProBook        | 50        | 1.57%   |
| ASUS ASUS         | 47        | 1.48%   |
| ASUS TUF          | 42        | 1.32%   |
| Acer Nitro        | 39        | 1.22%   |
| ASUS ROG          | 35        | 1.1%    |
| HP 15             | 34        | 1.07%   |
| Lenovo Legion     | 33        | 1.04%   |
| Dell XPS          | 30        | 0.94%   |
| Toshiba Satellite | 29        | 0.91%   |
| Lenovo ThinkBook  | 28        | 0.88%   |
| Acer Swift        | 27        | 0.85%   |
| Dell Precision    | 24        | 0.75%   |
| Lenovo E41-25     | 22        | 0.69%   |
| Timi Mi           | 21        | 0.66%   |
| Unknown           | 19        | 0.6%    |
| Acer Predator     | 17        | 0.53%   |
| Lenovo G50-80     | 15        | 0.47%   |
| HP OMEN           | 15        | 0.47%   |
| HP 245            | 14        | 0.44%   |
| Dell G3           | 14        | 0.44%   |
| ASUS ZenBook      | 14        | 0.44%   |
| HP ENVY           | 12        | 0.38%   |
| ASUS X510UNR      | 12        | 0.38%   |
| MSI GF63          | 11        | 0.35%   |
| Lenovo G50-45     | 11        | 0.35%   |
| HP Compaq         | 11        | 0.35%   |
| AVITA NS14A8      | 10        | 0.31%   |
| ASUS X556UQK      | 10        | 0.31%   |
| HP ZBook          | 9         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 445       | 13.97%  |
| 2018    | 414       | 12.99%  |
| 2020    | 361       | 11.33%  |
| 2021    | 313       | 9.82%   |
| 2017    | 268       | 8.41%   |
| 2016    | 201       | 6.31%   |
| 2013    | 184       | 5.78%   |
| 2011    | 182       | 5.71%   |
| 2012    | 170       | 5.34%   |
| 2014    | 168       | 5.27%   |
| 2015    | 147       | 4.61%   |
| 2022    | 109       | 3.42%   |
| 2010    | 107       | 3.36%   |
| 2008    | 53        | 1.66%   |
| 2009    | 38        | 1.19%   |
| 2023    | 11        | 0.35%   |
| 2007    | 10        | 0.31%   |
| 2006    | 2         | 0.06%   |
| 2005    | 1         | 0.03%   |
| 2003    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3186      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2743      | 85.27%  |
| Enabled  | 474       | 14.73%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3175      | 99.65%  |
| Yes  | 11        | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1156      | 35.81%  |
| 3.01-4.0    | 694       | 21.5%   |
| 8.01-16.0   | 643       | 19.92%  |
| 16.01-24.0  | 513       | 15.89%  |
| 1.01-2.0    | 87        | 2.7%    |
| 32.01-64.0  | 77        | 2.39%   |
| 2.01-3.0    | 25        | 0.77%   |
| 24.01-32.0  | 17        | 0.53%   |
| 64.01-256.0 | 9         | 0.28%   |
| 0.51-1.0    | 6         | 0.19%   |
| 0.01-0.5    | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1111      | 31.82%  |
| 1.01-2.0   | 1012      | 28.98%  |
| 4.01-8.0   | 568       | 16.27%  |
| 3.01-4.0   | 564       | 16.15%  |
| 8.01-16.0  | 116       | 3.32%   |
| 0.51-1.0   | 102       | 2.92%   |
| 0.01-0.5   | 12        | 0.34%   |
| 16.01-24.0 | 5         | 0.14%   |
| 24.01-32.0 | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2394      | 74.3%   |
| 2      | 762       | 23.65%  |
| 3      | 41        | 1.27%   |
| 0      | 24        | 0.74%   |
| 5      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2120      | 66.11%  |
| Yes       | 1087      | 33.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2577      | 80.73%  |
| No        | 615       | 19.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3155      | 98.96%  |
| No        | 33        | 1.04%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2822      | 87.69%  |
| No        | 396       | 12.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| India   | 3186      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Bengaluru     | 405       | 11.87%  |
| Chennai       | 212       | 6.21%   |
| Mumbai        | 209       | 6.12%   |
| Delhi         | 193       | 5.65%   |
| Hyderabad     | 177       | 5.19%   |
| Pune          | 176       | 5.16%   |
| New Delhi     | 147       | 4.31%   |
| Kolkata       | 130       | 3.81%   |
| Ahmedabad     | 78        | 2.29%   |
| Lucknow       | 70        | 2.05%   |
| Ernakulam     | 58        | 1.7%    |
| Jaipur        | 56        | 1.64%   |
| Patna         | 55        | 1.61%   |
| Gurgaon       | 53        | 1.55%   |
| Coimbatore    | 47        | 1.38%   |
| Indore        | 41        | 1.2%    |
| Navi Mumbai   | 39        | 1.14%   |
| Trivandrum    | 37        | 1.08%   |
| Kochi         | 37        | 1.08%   |
| Bhopal        | 36        | 1.05%   |
| Thrissur      | 31        | 0.91%   |
| Surat         | 29        | 0.85%   |
| Ludhiana      | 29        | 0.85%   |
| Nagpur        | 28        | 0.82%   |
| Guwahati      | 28        | 0.82%   |
| Malappuram    | 27        | 0.79%   |
| Bhubaneswar   | 23        | 0.67%   |
| Noida         | 22        | 0.64%   |
| Mangalore     | 18        | 0.53%   |
| Ghaziabad     | 18        | 0.53%   |
| Visakhapatnam | 17        | 0.5%    |
| Thane         | 17        | 0.5%    |
| Chandigarh    | 17        | 0.5%    |
| Mohali        | 16        | 0.47%   |
| Kanpur        | 15        | 0.44%   |
| Kozhikode     | 14        | 0.41%   |
| Tiruchi       | 13        | 0.38%   |
| Dehradun      | 13        | 0.38%   |
| Vadodara      | 12        | 0.35%   |
| Mysore        | 12        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 749       | 909    | 19.25%  |
| WDC                         | 659       | 784    | 16.94%  |
| Toshiba                     | 428       | 487    | 11%     |
| Samsung Electronics         | 405       | 494    | 10.41%  |
| Sandisk                     | 179       | 224    | 4.6%    |
| SK hynix                    | 177       | 201    | 4.55%   |
| Intel                       | 158       | 207    | 4.06%   |
| HGST                        | 152       | 168    | 3.91%   |
| Crucial                     | 144       | 172    | 3.7%    |
| Kingston                    | 140       | 165    | 3.6%    |
| Micron Technology           | 123       | 139    | 3.16%   |
| Hitachi                     | 76        | 90     | 1.95%   |
| KIOXIA                      | 74        | 84     | 1.9%    |
| Unknown                     | 72        | 90     | 1.85%   |
| China                       | 29        | 34     | 0.75%   |
| A-DATA Technology           | 25        | 26     | 0.64%   |
| FORESEE                     | 20        | 22     | 0.51%   |
| Unknown                     | 18        | 21     | 0.46%   |
| Micron/Crucial Technology   | 16        | 17     | 0.41%   |
| UMIS                        | 15        | 18     | 0.39%   |
| Apple                       | 15        | 19     | 0.39%   |
| Silicon Motion              | 14        | 17     | 0.36%   |
| LITEON                      | 14        | 18     | 0.36%   |
| Phison                      | 12        | 13     | 0.31%   |
| Hewlett-Packard             | 10        | 14     | 0.26%   |
| Acer                        | 10        | 10     | 0.26%   |
| Kingston Technology Company | 9         | 11     | 0.23%   |
| Fujitsu                     | 9         | 9      | 0.23%   |
| Union Memory (Shenzhen)     | 6         | 6      | 0.15%   |
| Gigabyte Technology         | 6         | 7      | 0.15%   |
| YMTC                        | 5         | 5      | 0.13%   |
| SPCC                        | 5         | 6      | 0.13%   |
| XPG                         | 4         | 4      | 0.1%    |
| Transcend                   | 4         | 4      | 0.1%    |
| TO Exter                    | 4         | 4      | 0.1%    |
| Realtek Semiconductor       | 4         | 8      | 0.1%    |
| PNY                         | 4         | 6      | 0.1%    |
| Netac                       | 4         | 4      | 0.1%    |
| Maxtor                      | 4         | 6      | 0.1%    |
| Lexar                       | 4         | 4      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 278       | 6.96%   |
| Toshiba MQ04ABF100 1TB              | 143       | 3.58%   |
| Toshiba MQ01ABD100 1TB              | 105       | 2.63%   |
| Seagate ST1000LM049-2GH172 1TB      | 66        | 1.65%   |
| Seagate ST500LT012-1DG142 500GB     | 57        | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 57        | 1.43%   |
| Crucial CT240BX500SSD1 240GB        | 49        | 1.23%   |
| Intel NVMe SSD Drive 512GB          | 48        | 1.2%    |
| Toshiba MQ01ABF050 500GB            | 43        | 1.08%   |
| HGST HTS541010A9E680 1TB            | 39        | 0.98%   |
| Intel SSDPEKNW512G8 512GB           | 38        | 0.95%   |
| SanDisk NVMe SSD Drive 256GB        | 36        | 0.9%    |
| WDC WD10SPZX-60Z10T0 1TB            | 35        | 0.88%   |
| SanDisk NVMe SSD Drive 512GB        | 35        | 0.88%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 33        | 0.83%   |
| Seagate ST2000LM007-1R8174 2TB      | 33        | 0.83%   |
| Seagate ST1000LM048-2E7172 1TB      | 33        | 0.83%   |
| Samsung NVMe SSD Drive 512GB        | 33        | 0.83%   |
| WDC WD10SPZX-24Z10 1TB              | 32        | 0.8%    |
| Seagate ST9500325AS 500GB           | 32        | 0.8%    |
| Kingston SA400S37240G 240GB SSD     | 31        | 0.78%   |
| SK hynix NVMe SSD Drive 512GB       | 29        | 0.73%   |
| WDC WD10JPVX-60JC3T1 1TB            | 27        | 0.68%   |
| HGST HTS721010A9E630 1TB            | 27        | 0.68%   |
| WDC WD10SPZX-21Z10T0 1TB            | 25        | 0.63%   |
| Samsung NVMe SSD Drive 256GB        | 23        | 0.58%   |
| Seagate ST500LT012-9WS142 500GB     | 21        | 0.53%   |
| Micron 2450_MTFDKBA512TFK 512GB     | 21        | 0.53%   |
| KIOXIA KBG40ZNS512G NVMe 512GB      | 21        | 0.53%   |
| HGST HTS545050A7E680 500GB          | 21        | 0.53%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 20        | 0.5%    |
| Crucial CT480BX500SSD1 480GB        | 20        | 0.5%    |
| WDC WD5000LPVX-75V0TT0 500GB        | 19        | 0.48%   |
| HGST HTS545050A7E380 500GB          | 19        | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB            | 18        | 0.45%   |
| Unknown                             | 18        | 0.45%   |
| WDC WD10SPZX-24Z10T0 1TB            | 17        | 0.43%   |
| WDC WD10JPVX-60JC3T0 1TB            | 17        | 0.43%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 17        | 0.43%   |
| WDC WD10SPZX-08Z10 1TB              | 16        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 742       | 900    | 40.24%  |
| WDC                 | 456       | 529    | 24.73%  |
| Toshiba             | 382       | 427    | 20.72%  |
| HGST                | 152       | 168    | 8.24%   |
| Hitachi             | 76        | 90     | 4.12%   |
| Fujitsu             | 9         | 9      | 0.49%   |
| Unknown             | 7         | 7      | 0.38%   |
| Samsung Electronics | 7         | 7      | 0.38%   |
| External            | 4         | 6      | 0.22%   |
| Apple               | 4         | 4      | 0.22%   |
| Hewlett-Packard     | 3         | 4      | 0.16%   |
| StoreJet            | 1         | 1      | 0.05%   |
| MARSHAL             | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 137       | 155    | 17.61%  |
| Crucial             | 130       | 158    | 16.71%  |
| WDC                 | 103       | 118    | 13.24%  |
| Kingston            | 82        | 102    | 10.54%  |
| SanDisk             | 49        | 66     | 6.3%    |
| SK hynix            | 35        | 37     | 4.5%    |
| China               | 28        | 33     | 3.6%    |
| Micron Technology   | 24        | 29     | 3.08%   |
| A-DATA Technology   | 20        | 21     | 2.57%   |
| FORESEE             | 18        | 20     | 2.31%   |
| Intel               | 15        | 16     | 1.93%   |
| LITEON              | 12        | 16     | 1.54%   |
| Unknown             | 11        | 11     | 1.41%   |
| Toshiba             | 10        | 10     | 1.29%   |
| Acer                | 9         | 9      | 1.16%   |
| Apple               | 8         | 9      | 1.03%   |
| Seagate             | 6         | 6      | 0.77%   |
| Hewlett-Packard     | 6         | 9      | 0.77%   |
| Gigabyte Technology | 6         | 7      | 0.77%   |
| Unknown             | 4         | 4      | 0.51%   |
| TO Exter            | 4         | 4      | 0.51%   |
| PNY                 | 4         | 6      | 0.51%   |
| Netac               | 4         | 4      | 0.51%   |
| Maxtor              | 4         | 6      | 0.51%   |
| Lexar               | 4         | 4      | 0.51%   |
| EVM                 | 4         | 6      | 0.51%   |
| Transcend           | 3         | 3      | 0.39%   |
| SPCC                | 3         | 4      | 0.39%   |
| Team                | 2         | 2      | 0.26%   |
| OSCOO               | 2         | 4      | 0.26%   |
| KLEVV               | 2         | 3      | 0.26%   |
| CONSISTENT          | 2         | 2      | 0.26%   |
| BIWIN               | 2         | 2      | 0.26%   |
| Aarvex              | 2         | 3      | 0.26%   |
| Zebronics           | 1         | 1      | 0.13%   |
| W800S               | 1         | 1      | 0.13%   |
| Unknown (690)       | 1         | 1      | 0.13%   |
| StoreJet            | 1         | 1      | 0.13%   |
| Secureye            | 1         | 1      | 0.13%   |
| Phison              | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1820      | 2153   | 47.73%  |
| NVMe    | 1152      | 1455   | 30.21%  |
| SSD     | 755       | 914    | 19.8%   |
| MMC     | 57        | 73     | 1.49%   |
| Unknown | 29        | 37     | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2290      | 3027   | 64.22%  |
| NVMe | 1152      | 1455   | 32.31%  |
| SAS  | 67        | 77     | 1.88%   |
| MMC  | 57        | 73     | 1.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1270      | 1558   | 50%     |
| 0.51-1.0   | 1205      | 1439   | 47.44%  |
| 1.01-2.0   | 59        | 63     | 2.32%   |
| 4.01-10.0  | 6         | 7      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 971       | 28.97%  |
| 101-250        | 872       | 26.01%  |
| 501-1000       | 582       | 17.36%  |
| 51-100         | 305       | 9.1%    |
| 1001-2000      | 188       | 5.61%   |
| 1-20           | 166       | 4.95%   |
| 21-50          | 161       | 4.8%    |
| Unknown        | 52        | 1.55%   |
| 2001-3000      | 31        | 0.92%   |
| More than 3000 | 24        | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1260      | 36.26%  |
| 21-50          | 765       | 22.01%  |
| 101-250        | 500       | 14.39%  |
| 51-100         | 456       | 13.12%  |
| 251-500        | 274       | 7.88%   |
| 501-1000       | 132       | 3.8%    |
| Unknown        | 52        | 1.5%    |
| 1001-2000      | 30        | 0.86%   |
| 2001-3000      | 3         | 0.09%   |
| More than 3000 | 2         | 0.06%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 23        | 25     | 8.68%   |
| HGST HTS541010A9E680 1TB             | 14        | 14     | 5.28%   |
| Toshiba MQ01ABD100 1TB               | 11        | 11     | 4.15%   |
| HGST HTS545050A7E680 500GB           | 10        | 12     | 3.77%   |
| Seagate ST500LT012-1DG142 500GB      | 9         | 9      | 3.4%    |
| Seagate ST1000LM049-2GH172 1TB       | 9         | 11     | 3.4%    |
| Seagate ST9500325AS 500GB            | 8         | 8      | 3.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 8         | 8      | 3.02%   |
| Toshiba MQ04ABF100 1TB               | 6         | 7      | 2.26%   |
| Toshiba MQ01ABF050 500GB             | 6         | 6      | 2.26%   |
| Seagate ST500LT012-9WS142 500GB      | 6         | 7      | 2.26%   |
| Seagate ST500LM021-1KJ152 500GB      | 6         | 6      | 2.26%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 4      | 1.51%   |
| HGST HTS721010A9E630 1TB             | 4         | 4      | 1.51%   |
| HGST HTS545050A7E380 500GB           | 4         | 4      | 1.51%   |
| WDC WD10JPVX-60JC3T1 1TB             | 3         | 3      | 1.13%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 3         | 3      | 1.13%   |
| Seagate ST9320325AS 320GB            | 3         | 3      | 1.13%   |
| Seagate ST2000LM007-1R8174 2TB       | 3         | 3      | 1.13%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 1.13%   |
| Hitachi HTS547575A9E384 752GB        | 3         | 3      | 1.13%   |
| Hitachi HTS545032B9A300 320GB        | 3         | 5      | 1.13%   |
| HGST HTS725050A7E630 500GB           | 3         | 3      | 1.13%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 2      | 0.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 2      | 0.75%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 2      | 0.75%   |
| WDC WD5000LPVT-22G33T0 500GB         | 2         | 2      | 0.75%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 2      | 0.75%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 2      | 0.75%   |
| Toshiba MQ01ABD050 500GB             | 2         | 2      | 0.75%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 0.75%   |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 2      | 0.75%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD  | 2         | 2      | 0.75%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 2      | 0.75%   |
| Hitachi HTS542516K9SA00 160GB        | 2         | 2      | 0.75%   |
| Crucial CT500P1SSD8 500GB            | 2         | 2      | 0.75%   |
| Unknown                              | 2         | 2      | 0.75%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 1      | 0.38%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 1      | 0.38%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 94        | 102    | 35.61%  |
| HGST                | 39        | 41     | 14.77%  |
| WDC                 | 38        | 39     | 14.39%  |
| Toshiba             | 36        | 38     | 13.64%  |
| Hitachi             | 23        | 26     | 8.71%   |
| SK hynix            | 9         | 10     | 3.41%   |
| Samsung Electronics | 6         | 7      | 2.27%   |
| SanDisk             | 5         | 5      | 1.89%   |
| Intel               | 3         | 3      | 1.14%   |
| Crucial             | 2         | 2      | 0.76%   |
| Unknown             | 2         | 2      | 0.76%   |
| Micron Technology   | 1         | 1      | 0.38%   |
| MARSHAL             | 1         | 1      | 0.38%   |
| Leven               | 1         | 1      | 0.38%   |
| Lenovo              | 1         | 2      | 0.38%   |
| China               | 1         | 1      | 0.38%   |
| Apple               | 1         | 1      | 0.38%   |
| A-DATA Technology   | 1         | 1      | 0.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 94        | 102    | 41.05%  |
| HGST                | 39        | 41     | 17.03%  |
| Toshiba             | 36        | 38     | 15.72%  |
| WDC                 | 33        | 34     | 14.41%  |
| Hitachi             | 23        | 26     | 10.04%  |
| Samsung Electronics | 2         | 2      | 0.87%   |
| MARSHAL             | 1         | 1      | 0.44%   |
| Apple               | 1         | 1      | 0.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 229       | 245    | 86.74%  |
| SSD  | 21        | 22     | 7.95%   |
| NVMe | 14        | 16     | 5.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 1      | 20%     |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 20%     |
| Seagate ST1000LM 024 HN-M101MBB 1TB | 1         | 1      | 20%     |
| Apple HDD HTS545050A7E362 500GB     | 1         | 1      | 20%     |
| Acer SSD FA100 256GB                | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Apple   | 1         | 1      | 20%     |
| Acer    | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1857      | 2628   | 55.27%  |
| Works    | 1237      | 1716   | 36.82%  |
| Malfunc  | 261       | 283    | 7.77%   |
| Failed   | 5         | 5      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2392      | 61.13%  |
| AMD                                     | 444       | 11.35%  |
| Samsung Electronics                     | 276       | 7.05%   |
| SanDisk                                 | 234       | 5.98%   |
| SK hynix                                | 141       | 3.6%    |
| Micron Technology                       | 99        | 2.53%   |
| KIOXIA                                  | 77        | 1.97%   |
| Kingston Technology Company             | 68        | 1.74%   |
| Toshiba America Info Systems            | 46        | 1.18%   |
| Micron/Crucial Technology               | 28        | 0.72%   |
| Union Memory (Shenzhen)                 | 24        | 0.61%   |
| Silicon Motion                          | 18        | 0.46%   |
| Phison Electronics                      | 12        | 0.31%   |
| Yangtze Memory Technologies             | 8         | 0.2%    |
| ADATA Technology                        | 8         | 0.2%    |
| Solid State Storage Technology          | 7         | 0.18%   |
| Realtek Semiconductor                   | 7         | 0.18%   |
| Nvidia                                  | 5         | 0.13%   |
| Lite-On Technology                      | 4         | 0.1%    |
| Shenzhen Longsys Electronics            | 3         | 0.08%   |
| Lenovo                                  | 3         | 0.08%   |
| Apple                                   | 3         | 0.08%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.03%   |
| Marvell Technology Group                | 1         | 0.03%   |
| INNOGRIT                                | 1         | 0.03%   |
| ASMedia Technology                      | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 461       | 11.14%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 431       | 10.42%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 311       | 7.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 199       | 4.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 181       | 4.37%   |
| Intel Volume Management Device NVMe RAID Controller                              | 158       | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 125       | 3.02%   |
| Samsung NVMe SSD Controller 980                                                  | 122       | 2.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 119       | 2.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 107       | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 105       | 2.54%   |
| Intel Comet Lake SATA AHCI Controller                                            | 100       | 2.42%   |
| Intel Tiger Lake-LP SATA Controller                                              | 97        | 2.34%   |
| Intel SSD 660P Series                                                            | 96        | 2.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 85        | 2.05%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 66        | 1.59%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 66        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 59        | 1.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 51        | 1.23%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 50        | 1.21%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 48        | 1.16%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 47        | 1.14%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 41        | 0.99%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 40        | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 38        | 0.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 36        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 34        | 0.82%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 33        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 33        | 0.8%    |
| SK hynix BC511 NVMe SSD                                                          | 32        | 0.77%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 30        | 0.72%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 28        | 0.68%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 23        | 0.56%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 21        | 0.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 21        | 0.51%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 21        | 0.51%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 19        | 0.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 17        | 0.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 17        | 0.41%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 17        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2348      | 57.86%  |
| NVMe | 1162      | 28.63%  |
| RAID | 480       | 11.83%  |
| IDE  | 68        | 1.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2583      | 81.07%  |
| AMD    | 602       | 18.9%   |
| ARM    | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 179       | 5.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 115       | 3.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 93        | 2.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 81        | 2.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 80        | 2.51%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 77        | 2.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 55        | 1.73%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 52        | 1.63%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 50        | 1.57%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 50        | 1.57%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 48        | 1.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 47        | 1.48%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 47        | 1.48%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 45        | 1.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 37        | 1.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 37        | 1.16%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 37        | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 36        | 1.13%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 36        | 1.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 34        | 1.07%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 33        | 1.04%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 33        | 1.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 32        | 1%      |
| AMD Ryzen 7 5800H with Radeon Graphics        | 30        | 0.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 0.91%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 29        | 0.91%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 29        | 0.91%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 29        | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 0.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 27        | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 26        | 0.82%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 24        | 0.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 23        | 0.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 23        | 0.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 23        | 0.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 23        | 0.72%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 23        | 0.72%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 23        | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 23        | 0.72%   |
| AMD PRO A4-4350B R4, 5 COMPUTE CORES 2C+3G    | 23        | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1061      | 33.3%   |
| Intel Core i3           | 544       | 17.07%  |
| Intel Core i7           | 449       | 14.09%  |
| Other                   | 326       | 10.23%  |
| AMD Ryzen 5             | 255       | 8%      |
| AMD Ryzen 7             | 99        | 3.11%   |
| Intel Pentium           | 80        | 2.51%   |
| Intel Core 2 Duo        | 62        | 1.95%   |
| Intel Celeron           | 45        | 1.41%   |
| AMD A6                  | 42        | 1.32%   |
| AMD Ryzen 3             | 40        | 1.26%   |
| AMD A8                  | 26        | 0.82%   |
| AMD A4                  | 20        | 0.63%   |
| Intel Atom              | 16        | 0.5%    |
| AMD Ryzen 9             | 16        | 0.5%    |
| AMD A10                 | 16        | 0.5%    |
| Intel Pentium Dual-Core | 13        | 0.41%   |
| AMD E1                  | 13        | 0.41%   |
| AMD Ryzen 7 PRO         | 9         | 0.28%   |
| AMD E2                  | 7         | 0.22%   |
| Intel Pentium Silver    | 6         | 0.19%   |
| Intel Pentium Dual      | 5         | 0.16%   |
| Intel Core 2            | 5         | 0.16%   |
| AMD Ryzen 5 PRO         | 4         | 0.13%   |
| AMD E                   | 4         | 0.13%   |
| Intel Xeon              | 3         | 0.09%   |
| Intel Core i9           | 3         | 0.09%   |
| AMD C-60                | 3         | 0.09%   |
| AMD A12                 | 3         | 0.09%   |
| AMD PRO A10             | 2         | 0.06%   |
| Intel Pentium M         | 1         | 0.03%   |
| Intel Genuine           | 1         | 0.03%   |
| Intel Core m5           | 1         | 0.03%   |
| Intel Core m3           | 1         | 0.03%   |
| Intel Celeron M         | 1         | 0.03%   |
| Intel Celeron Dual-Core | 1         | 0.03%   |
| AMD Turion 64 X2 Mobile | 1         | 0.03%   |
| AMD Phenom II           | 1         | 0.03%   |
| AMD Athlon II           | 1         | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1554      | 48.76%  |
| 4      | 1167      | 36.62%  |
| 6      | 235       | 7.37%   |
| 8      | 147       | 4.61%   |
| 12     | 27        | 0.85%   |
| 1      | 26        | 0.82%   |
| 10     | 15        | 0.47%   |
| 14     | 12        | 0.38%   |
| 16     | 2         | 0.06%   |
| 3      | 2         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3186      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2762      | 86.69%  |
| 1      | 421       | 13.21%  |
| 4      | 2         | 0.06%   |
| 12     | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3157      | 99.03%  |
| Unknown        | 27        | 0.85%   |
| 32-bit         | 4         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 719       | 21.91%  |
| 0x806ea    | 212       | 6.46%   |
| 0x806ec    | 207       | 6.31%   |
| 0x806c1    | 155       | 4.72%   |
| 0x40651    | 151       | 4.6%    |
| 0x206a7    | 151       | 4.6%    |
| 0x306a9    | 150       | 4.57%   |
| 0x406e3    | 148       | 4.51%   |
| 0x806e9    | 140       | 4.27%   |
| 0x906ea    | 113       | 3.44%   |
| 0x306d4    | 108       | 3.29%   |
| 0x706e5    | 74        | 2.26%   |
| 0x08108109 | 68        | 2.07%   |
| 0x0a50000c | 60        | 1.83%   |
| 0x806eb    | 53        | 1.62%   |
| 0x20655    | 52        | 1.58%   |
| 0x08108102 | 50        | 1.52%   |
| 0xa0652    | 44        | 1.34%   |
| 0x06006705 | 43        | 1.31%   |
| 0x1067a    | 38        | 1.16%   |
| 0x306c3    | 33        | 1.01%   |
| 0x07030105 | 30        | 0.91%   |
| 0x906e9    | 29        | 0.88%   |
| 0x906a3    | 28        | 0.85%   |
| 0x08600106 | 27        | 0.82%   |
| 0x08608103 | 26        | 0.79%   |
| 0x08600104 | 26        | 0.79%   |
| 0x20652    | 25        | 0.76%   |
| 0x0810100b | 18        | 0.55%   |
| 0x08101007 | 17        | 0.52%   |
| 0x6fd      | 16        | 0.49%   |
| 0x30678    | 15        | 0.46%   |
| 0x906ed    | 14        | 0.43%   |
| 0x806d1    | 14        | 0.43%   |
| 0x506e3    | 13        | 0.4%    |
| 0x0a50000d | 12        | 0.37%   |
| 0x08600103 | 12        | 0.37%   |
| 0x06001119 | 12        | 0.37%   |
| 0x406c4    | 10        | 0.3%    |
| 0x06006704 | 10        | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 932       | 29.24%  |
| Haswell          | 232       | 7.28%   |
| Skylake          | 209       | 6.56%   |
| TigerLake        | 197       | 6.18%   |
| IvyBridge        | 188       | 5.9%    |
| SandyBridge      | 185       | 5.8%    |
| Zen+             | 143       | 4.49%   |
| Broadwell        | 134       | 4.2%    |
| Icelake          | 106       | 3.33%   |
| Westmere         | 97        | 3.04%   |
| Zen 2            | 92        | 2.89%   |
| Zen 3            | 89        | 2.79%   |
| Unknown          | 80        | 2.51%   |
| Excavator        | 78        | 2.45%   |
| Penryn           | 63        | 1.98%   |
| CometLake        | 58        | 1.82%   |
| Alderlake Hybrid | 56        | 1.76%   |
| Puma             | 51        | 1.6%    |
| Silvermont       | 42        | 1.32%   |
| Zen              | 39        | 1.22%   |
| Core             | 26        | 0.82%   |
| Piledriver       | 18        | 0.56%   |
| Goldmont plus    | 13        | 0.41%   |
| K10 Llano        | 11        | 0.35%   |
| Bonnell          | 10        | 0.31%   |
| Goldmont         | 9         | 0.28%   |
| Bobcat           | 8         | 0.25%   |
| Nehalem          | 6         | 0.19%   |
| Jaguar           | 5         | 0.16%   |
| P6               | 3         | 0.09%   |
| Tremont          | 2         | 0.06%   |
| Steamroller      | 2         | 0.06%   |
| K10              | 2         | 0.06%   |
| K8 Hammer        | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2497      | 57.46%  |
| Nvidia                           | 936       | 21.54%  |
| AMD                              | 912       | 20.98%  |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 241       | 5.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 188       | 4.22%   |
| Intel HD Graphics 620                                                                 | 183       | 4.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 179       | 4.02%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 169       | 3.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 168       | 3.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 162       | 3.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 159       | 3.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 146       | 3.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 143       | 3.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 143       | 3.21%   |
| Intel HD Graphics 5500                                                                | 122       | 2.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 110       | 2.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 96        | 2.16%   |
| AMD Renoir                                                                            | 90        | 2.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 75        | 1.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 73        | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                   | 72        | 1.62%   |
| Nvidia TU117M                                                                         | 71        | 1.6%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 69        | 1.55%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 63        | 1.42%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 58        | 1.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 56        | 1.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 51        | 1.15%   |
| Nvidia GP108M [GeForce MX250]                                                         | 49        | 1.1%    |
| AMD Lucienne                                                                          | 45        | 1.01%   |
| Nvidia GP108M [GeForce MX150]                                                         | 44        | 0.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 42        | 0.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 39        | 0.88%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 38        | 0.85%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 37        | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 36        | 0.81%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 35        | 0.79%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 35        | 0.79%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 34        | 0.76%   |
| Nvidia GM108M [GeForce MX130]                                                         | 33        | 0.74%   |
| Intel HD Graphics 630                                                                 | 32        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 31        | 0.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 30        | 0.67%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 29        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1485      | 46.44%  |
| Intel + Nvidia | 727       | 22.73%  |
| 1 x AMD        | 404       | 12.63%  |
| Intel + AMD    | 280       | 8.76%   |
| AMD + Nvidia   | 151       | 4.72%   |
| 2 x AMD        | 79        | 2.47%   |
| 1 x Nvidia     | 57        | 1.78%   |
| 2 x Intel      | 11        | 0.34%   |
| Other          | 3         | 0.09%   |
| 1 x SiS        | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2663      | 82.55%  |
| Proprietary | 493       | 15.28%  |
| Unknown     | 70        | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2017      | 61.57%  |
| 1.01-2.0   | 507       | 15.48%  |
| 0.01-0.5   | 295       | 9%      |
| 3.01-4.0   | 255       | 7.78%   |
| 0.51-1.0   | 153       | 4.67%   |
| 5.01-6.0   | 37        | 1.13%   |
| 7.01-8.0   | 8         | 0.24%   |
| 2.01-3.0   | 3         | 0.09%   |
| 8.01-16.0  | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 704       | 20.87%  |
| Chimei Innolux          | 658       | 19.51%  |
| AU Optronics            | 653       | 19.36%  |
| LG Display              | 515       | 15.27%  |
| Samsung Electronics     | 239       | 7.09%   |
| PANDA                   | 109       | 3.23%   |
| Dell                    | 62        | 1.84%   |
| Goldstar                | 52        | 1.54%   |
| Sharp                   | 46        | 1.36%   |
| BenQ                    | 42        | 1.25%   |
| Chi Mei Optoelectronics | 41        | 1.22%   |
| Lenovo                  | 31        | 0.92%   |
| Acer                    | 27        | 0.8%    |
| InfoVision              | 25        | 0.74%   |
| Apple                   | 25        | 0.74%   |
| Hewlett-Packard         | 18        | 0.53%   |
| Sony                    | 17        | 0.5%    |
| TMX                     | 15        | 0.44%   |
| AOC                     | 10        | 0.3%    |
| LG Philips              | 8         | 0.24%   |
| InnoLux Display         | 7         | 0.21%   |
| CSO                     | 7         | 0.21%   |
| Toshiba                 | 5         | 0.15%   |
| HKC                     | 5         | 0.15%   |
| ViewSonic               | 3         | 0.09%   |
| Valve                   | 3         | 0.09%   |
| Unknown                 | 3         | 0.09%   |
| LGD                     | 3         | 0.09%   |
| CPT                     | 3         | 0.09%   |
| STA                     | 2         | 0.06%   |
| Panasonic               | 2         | 0.06%   |
| MSI                     | 2         | 0.06%   |
| KDC                     | 2         | 0.06%   |
| HannStar                | 2         | 0.06%   |
| AGO                     | 2         | 0.06%   |
| VST                     | 1         | 0.03%   |
| Unknown (XXX)           | 1         | 0.03%   |
| TCL                     | 1         | 0.03%   |
| STD                     | 1         | 0.03%   |
| SGT                     | 1         | 0.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 87        | 2.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 71        | 2.1%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 41        | 1.21%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 40        | 1.18%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 37        | 1.09%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 37        | 1.09%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 35        | 1.04%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 35        | 1.04%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 32        | 0.95%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 29        | 0.86%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 27        | 0.8%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 27        | 0.8%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 25        | 0.74%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 23        | 0.68%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 23        | 0.68%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 22        | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 22        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 22        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 22        | 0.65%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 22        | 0.65%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 20        | 0.59%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 20        | 0.59%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 19        | 0.56%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 18        | 0.53%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 17        | 0.5%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 16        | 0.47%   |
| BOE LCD Monitor BOE07BD 1920x1080 309x174mm 14.0-inch                | 16        | 0.47%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 16        | 0.47%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 15        | 0.44%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 15        | 0.44%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 14        | 0.41%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 14        | 0.41%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 14        | 0.41%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 14        | 0.41%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch       | 14        | 0.41%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 14        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 14        | 0.41%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 13        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch      | 13        | 0.38%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                | 13        | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1628      | 50.12%  |
| 1366x768 (WXGA)    | 1273      | 39.19%  |
| 1600x900 (HD+)     | 54        | 1.66%   |
| 2560x1440 (QHD)    | 46        | 1.42%   |
| 1280x800 (WXGA)    | 43        | 1.32%   |
| 3840x2160 (4K)     | 40        | 1.23%   |
| 1920x1200 (WUXGA)  | 35        | 1.08%   |
| 2560x1600          | 26        | 0.8%    |
| 1440x900 (WXGA+)   | 20        | 0.62%   |
| 2880x1800          | 14        | 0.43%   |
| 3200x2000          | 10        | 0.31%   |
| 2560x1080          | 9         | 0.28%   |
| 1360x768           | 7         | 0.22%   |
| 1024x600           | 7         | 0.22%   |
| 1280x1024 (SXGA)   | 6         | 0.18%   |
| 3840x2400          | 4         | 0.12%   |
| 800x1280           | 3         | 0.09%   |
| 2160x1440          | 3         | 0.09%   |
| 1680x1050 (WSXGA+) | 3         | 0.09%   |
| 3456x2160          | 2         | 0.06%   |
| 3440x1440          | 2         | 0.06%   |
| 3072x1920          | 2         | 0.06%   |
| 2256x1504          | 2         | 0.06%   |
| 2240x1400          | 2         | 0.06%   |
| 3840x1100          | 1         | 0.03%   |
| 3200x1800 (QHD+)   | 1         | 0.03%   |
| 2732x768           | 1         | 0.03%   |
| 1920x1280          | 1         | 0.03%   |
| 1280x768           | 1         | 0.03%   |
| 1280x720 (HD)      | 1         | 0.03%   |
| Unknown            | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1874      | 55.64%  |
| 13      | 527       | 15.65%  |
| 14      | 523       | 15.53%  |
| 21      | 71        | 2.11%   |
| 24      | 59        | 1.75%   |
| 12      | 45        | 1.34%   |
| 17      | 35        | 1.04%   |
| 27      | 34        | 1.01%   |
| 23      | 33        | 0.98%   |
| 16      | 24        | 0.71%   |
| 19      | 20        | 0.59%   |
| 18      | 20        | 0.59%   |
| 31      | 15        | 0.45%   |
| 11      | 14        | 0.42%   |
| Unknown | 14        | 0.42%   |
| 34      | 10        | 0.3%    |
| 20      | 10        | 0.3%    |
| 10      | 8         | 0.24%   |
| 26      | 6         | 0.18%   |
| 72      | 5         | 0.15%   |
| 46      | 4         | 0.12%   |
| 40      | 4         | 0.12%   |
| 7       | 3         | 0.09%   |
| 54      | 2         | 0.06%   |
| 32      | 2         | 0.06%   |
| 65      | 1         | 0.03%   |
| 58      | 1         | 0.03%   |
| 42      | 1         | 0.03%   |
| 35      | 1         | 0.03%   |
| 25      | 1         | 0.03%   |
| 22      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2798      | 83.22%  |
| 201-300     | 174       | 5.18%   |
| 401-500     | 125       | 3.72%   |
| 501-600     | 120       | 3.57%   |
| 351-400     | 77        | 2.29%   |
| 601-700     | 20        | 0.59%   |
| Unknown     | 14        | 0.42%   |
| 701-800     | 12        | 0.36%   |
| 1001-1500   | 8         | 0.24%   |
| 801-900     | 5         | 0.15%   |
| 1501-2000   | 5         | 0.15%   |
| 1-100       | 3         | 0.09%   |
| 901-1000    | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2925      | 93.48%  |
| 16/10   | 155       | 4.95%   |
| Unknown | 13        | 0.42%   |
| 21/9    | 11        | 0.35%   |
| 4/3     | 8         | 0.26%   |
| 3/2     | 7         | 0.22%   |
| 5/4     | 3         | 0.1%    |
| 0.67    | 3         | 0.1%    |
| 6/5     | 2         | 0.06%   |
| 3.40    | 1         | 0.03%   |
| 2.00    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1868      | 55.5%   |
| 81-90          | 968       | 28.76%  |
| 201-250        | 146       | 4.34%   |
| 71-80          | 81        | 2.41%   |
| 61-70          | 42        | 1.25%   |
| 151-200        | 41        | 1.22%   |
| 301-350        | 37        | 1.1%    |
| 121-130        | 32        | 0.95%   |
| 351-500        | 28        | 0.83%   |
| 141-150        | 20        | 0.59%   |
| 111-120        | 19        | 0.56%   |
| 51-60          | 15        | 0.45%   |
| Unknown        | 14        | 0.42%   |
| 91-100         | 13        | 0.39%   |
| More than 1000 | 9         | 0.27%   |
| 501-1000       | 9         | 0.27%   |
| 41-50          | 8         | 0.24%   |
| 251-300        | 8         | 0.24%   |
| 131-140        | 5         | 0.15%   |
| 1-40           | 3         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1568      | 47.06%  |
| 101-120       | 1256      | 37.7%   |
| 51-100        | 301       | 9.03%   |
| 161-240       | 134       | 4.02%   |
| More than 240 | 46        | 1.38%   |
| Unknown       | 14        | 0.42%   |
| 1-50          | 13        | 0.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2874      | 89.03%  |
| 2     | 290       | 8.98%   |
| 0     | 59        | 1.83%   |
| 3     | 5         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2116      | 40.35%  |
| Intel                             | 1435      | 27.36%  |
| Qualcomm Atheros                  | 796       | 15.18%  |
| Broadcom                          | 259       | 4.94%   |
| MediaTek                          | 84        | 1.6%    |
| Xiaomi                            | 72        | 1.37%   |
| Ralink                            | 63        | 1.2%    |
| Broadcom Limited                  | 50        | 0.95%   |
| TP-Link                           | 47        | 0.9%    |
| Samsung Electronics               | 46        | 0.88%   |
| OPPO Electronics                  | 40        | 0.76%   |
| Qualcomm                          | 31        | 0.59%   |
| Ralink Technology                 | 30        | 0.57%   |
| Marvell Technology Group          | 28        | 0.53%   |
| ASIX Electronics                  | 17        | 0.32%   |
| OnePlus Technology (Shenzhen)     | 15        | 0.29%   |
| Motorola PCS                      | 14        | 0.27%   |
| Huawei Technologies               | 13        | 0.25%   |
| Google                            | 8         | 0.15%   |
| ICS Advent                        | 7         | 0.13%   |
| D-Link                            | 7         | 0.13%   |
| JMicron Technology                | 5         | 0.1%    |
| Foxconn / Hon Hai                 | 5         | 0.1%    |
| DisplayLink                       | 5         | 0.1%    |
| vivo                              | 4         | 0.08%   |
| HMD Global                        | 4         | 0.08%   |
| Dell                              | 4         | 0.08%   |
| Qualcomm Atheros Communications   | 3         | 0.06%   |
| Nvidia                            | 3         | 0.06%   |
| Lenovo                            | 3         | 0.06%   |
| Ericsson Business Mobile Networks | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.04%   |
| Sierra Wireless                   | 2         | 0.04%   |
| NTmore                            | 2         | 0.04%   |
| Edimax Technology                 | 2         | 0.04%   |
| Attansic Technology               | 2         | 0.04%   |
| ASUSTek Computer                  | 2         | 0.04%   |
| Apple                             | 2         | 0.04%   |
| VIA Technologies                  | 1         | 0.02%   |
| U-Blox                            | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1359      | 22.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 545       | 8.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 301       | 4.92%   |
| Intel Wi-Fi 6 AX201                                               | 145       | 2.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 142       | 2.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 140       | 2.29%   |
| Intel Wireless 8265 / 8275                                        | 133       | 2.17%   |
| Intel Wi-Fi 6 AX200                                               | 132       | 2.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 113       | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 107       | 1.75%   |
| Broadcom BCM43142 802.11b/g/n                                     | 105       | 1.72%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 104       | 1.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 95        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 89        | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 87        | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 86        | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 85        | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 76        | 1.24%   |
| Intel Wireless 7265                                               | 70        | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 63        | 1.03%   |
| Intel Wireless 3165                                               | 62        | 1.01%   |
| Intel Wireless 3160                                               | 61        | 1%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58        | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 57        | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 54        | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 49        | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 48        | 0.78%   |
| Intel Wireless 8260                                               | 45        | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 44        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 42        | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 41        | 0.67%   |
| Intel Wireless 7260                                               | 38        | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 36        | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 35        | 0.57%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 35        | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 33        | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 33        | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 32        | 0.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 32        | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 29        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1385      | 42.29%  |
| Qualcomm Atheros                  | 724       | 22.11%  |
| Realtek Semiconductor             | 650       | 19.85%  |
| Broadcom                          | 233       | 7.11%   |
| MediaTek                          | 77        | 2.35%   |
| Ralink                            | 63        | 1.92%   |
| TP-Link                           | 42        | 1.28%   |
| Broadcom Limited                  | 39        | 1.19%   |
| Ralink Technology                 | 30        | 0.92%   |
| Qualcomm                          | 8         | 0.24%   |
| D-Link                            | 7         | 0.21%   |
| Dell                              | 4         | 0.12%   |
| Qualcomm Atheros Communications   | 3         | 0.09%   |
| Sierra Wireless                   | 2         | 0.06%   |
| Edimax Technology                 | 2         | 0.06%   |
| Philips (or NXP)                  | 1         | 0.03%   |
| NetGear                           | 1         | 0.03%   |
| Micro Star International          | 1         | 0.03%   |
| IMC Networks                      | 1         | 0.03%   |
| Ericsson Business Mobile Networks | 1         | 0.03%   |
| D-Link System                     | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 301       | 9.15%   |
| Intel Wi-Fi 6 AX201                                            | 145       | 4.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 142       | 4.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 140       | 4.26%   |
| Intel Wireless 8265 / 8275                                     | 133       | 4.05%   |
| Intel Wi-Fi 6 AX200                                            | 132       | 4.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 113       | 3.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 107       | 3.25%   |
| Broadcom BCM43142 802.11b/g/n                                  | 105       | 3.19%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 104       | 3.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 95        | 2.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 89        | 2.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 87        | 2.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 86        | 2.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 85        | 2.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 76        | 2.31%   |
| Intel Wireless 7265                                            | 70        | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 63        | 1.92%   |
| Intel Wireless 3165                                            | 62        | 1.89%   |
| Intel Wireless 3160                                            | 61        | 1.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 57        | 1.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 54        | 1.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 49        | 1.49%   |
| Intel Wireless 8260                                            | 45        | 1.37%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 44        | 1.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 42        | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 41        | 1.25%   |
| Intel Wireless 7260                                            | 38        | 1.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 36        | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 32        | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 29        | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 29        | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 26        | 0.79%   |
| Intel Wireless-AC 9260                                         | 24        | 0.73%   |
| Ralink MT7601U Wireless Adapter                                | 21        | 0.64%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 21        | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 19        | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 18        | 0.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 17        | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1961      | 70.41%  |
| Intel                            | 341       | 12.24%  |
| Qualcomm Atheros                 | 116       | 4.17%   |
| Xiaomi                           | 72        | 2.59%   |
| Broadcom                         | 47        | 1.69%   |
| OPPO Electronics                 | 40        | 1.44%   |
| Samsung Electronics              | 35        | 1.26%   |
| Marvell Technology Group         | 28        | 1.01%   |
| Qualcomm                         | 23        | 0.83%   |
| ASIX Electronics                 | 17        | 0.61%   |
| Huawei Technologies              | 11        | 0.39%   |
| Broadcom Limited                 | 11        | 0.39%   |
| OnePlus Technology (Shenzhen)    | 10        | 0.36%   |
| Motorola PCS                     | 9         | 0.32%   |
| MediaTek                         | 8         | 0.29%   |
| Google                           | 8         | 0.29%   |
| ICS Advent                       | 7         | 0.25%   |
| TP-Link                          | 5         | 0.18%   |
| JMicron Technology               | 5         | 0.18%   |
| DisplayLink                      | 5         | 0.18%   |
| HMD Global                       | 4         | 0.14%   |
| Nvidia                           | 3         | 0.11%   |
| Lenovo                           | 3         | 0.11%   |
| Foxconn / Hon Hai                | 3         | 0.11%   |
| vivo                             | 2         | 0.07%   |
| NTmore                           | 2         | 0.07%   |
| Attansic Technology              | 2         | 0.07%   |
| ASUSTek Computer                 | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.04%   |
| VIA Technologies                 | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| LeEco                            | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1359      | 48.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 545       | 19.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 58        | 2.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 48        | 1.72%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 35        | 1.25%   |
| OPPO SM6375-QRD _SN:F4A23F05                                                   | 35        | 1.25%   |
| Intel Ethernet Connection I219-LM                                              | 33        | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                                          | 33        | 1.18%   |
| Intel Ethernet Connection (4) I219-V                                           | 32        | 1.14%   |
| Intel Ethernet Connection I218-LM                                              | 27        | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 24        | 0.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 24        | 0.86%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 23        | 0.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 23        | 0.82%   |
| Qualcomm Redmi Note 8                                                          | 21        | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                          | 19        | 0.68%   |
| Intel Ethernet Connection I217-LM                                              | 16        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                                       | 16        | 0.57%   |
| Intel Ethernet Connection (10) I219-V                                          | 15        | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 14        | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 14        | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 13        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 12        | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 12        | 0.43%   |
| Intel Ethernet Connection (6) I219-V                                           | 12        | 0.43%   |
| Intel Ethernet Connection (6) I219-LM                                          | 12        | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 11        | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 10        | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 10        | 0.36%   |
| OnePlus (Shenzhen) OnePlus                                                     | 10        | 0.36%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 10        | 0.36%   |
| Motorola PCS XT1032                                                            | 9         | 0.32%   |
| Intel Ethernet Connection (16) I219-V                                          | 9         | 0.32%   |
| Realtek RTL8125 2.5GbE Controller                                              | 8         | 0.29%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 8         | 0.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 0.29%   |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 0.29%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 0.21%   |
| MediaTek Titan pocket                                                          | 6         | 0.21%   |
| Intel Ethernet Connection (10) I219-LM                                         | 6         | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3154      | 54.72%  |
| Ethernet | 2572      | 44.62%  |
| Modem    | 21        | 0.36%   |
| Unknown  | 17        | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2729      | 85.28%  |
| Ethernet | 469       | 14.66%  |
| Modem    | 1         | 0.03%   |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2436      | 76.36%  |
| 1     | 733       | 22.98%  |
| 0     | 13        | 0.41%   |
| 3     | 8         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2578      | 79.54%  |
| Yes  | 663       | 20.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1191      | 41.91%  |
| Realtek Semiconductor           | 453       | 15.94%  |
| Qualcomm Atheros Communications | 449       | 15.8%   |
| IMC Networks                    | 156       | 5.49%   |
| Broadcom                        | 154       | 5.42%   |
| Lite-On Technology              | 130       | 4.57%   |
| Foxconn / Hon Hai               | 94        | 3.31%   |
| Ralink                          | 54        | 1.9%    |
| Dell                            | 35        | 1.23%   |
| Apple                           | 23        | 0.81%   |
| Cambridge Silicon Radio         | 22        | 0.77%   |
| Hewlett-Packard                 | 17        | 0.6%    |
| Foxconn International           | 10        | 0.35%   |
| Toshiba                         | 8         | 0.28%   |
| MediaTek                        | 8         | 0.28%   |
| Realtek                         | 7         | 0.25%   |
| Ralink Technology               | 7         | 0.25%   |
| TP-Link                         | 6         | 0.21%   |
| Opticis                         | 5         | 0.18%   |
| ASUSTek Computer                | 5         | 0.18%   |
| USI                             | 2         | 0.07%   |
| Chicony Electronics             | 2         | 0.07%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Integrated System Solution      | 1         | 0.04%   |
| Alps Electric                   | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 396       | 13.93%  |
| Realtek Bluetooth Radio                                                             | 280       | 9.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 280       | 9.85%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 267       | 9.39%   |
| Intel AX201 Bluetooth                                                               | 263       | 9.25%   |
| Intel AX200 Bluetooth                                                               | 129       | 4.54%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 125       | 4.4%    |
| IMC Networks Bluetooth Radio                                                        | 58        | 2.04%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 56        | 1.97%   |
| Ralink RT3290 Bluetooth                                                             | 54        | 1.9%    |
| IMC Networks Bluetooth Device                                                       | 54        | 1.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 47        | 1.65%   |
| Lite-On Bluetooth Device                                                            | 47        | 1.65%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 42        | 1.48%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 42        | 1.48%   |
| IMC Networks Wireless_Device                                                        | 41        | 1.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 36        | 1.27%   |
| Intel Bluetooth Device                                                              | 31        | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 29        | 1.02%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 28        | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 27        | 0.95%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 26        | 0.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 22        | 0.77%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 20        | 0.7%    |
| Realtek RTL8821A Bluetooth                                                          | 17        | 0.6%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 17        | 0.6%    |
| Realtek RTL8723B Bluetooth                                                          | 16        | 0.56%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 15        | 0.53%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 15        | 0.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 14        | 0.49%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 14        | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 13        | 0.46%   |
| Dell Wireless 365 Bluetooth                                                         | 13        | 0.46%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 12        | 0.42%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 12        | 0.42%   |
| Apple Bluetooth USB Host Controller                                                 | 12        | 0.42%   |
| Qualcomm Atheros Bluetooth                                                          | 11        | 0.39%   |
| Lite-On Wireless_Device                                                             | 11        | 0.39%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 11        | 0.39%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 11        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2569      | 69.56%  |
| AMD                              | 636       | 17.22%  |
| Nvidia                           | 397       | 10.75%  |
| C-Media Electronics              | 17        | 0.46%   |
| GN Netcom                        | 10        | 0.27%   |
| Realtek Semiconductor            | 6         | 0.16%   |
| Plantronics                      | 4         | 0.11%   |
| JMTek                            | 4         | 0.11%   |
| Generalplus Technology           | 4         | 0.11%   |
| ASUSTek Computer                 | 4         | 0.11%   |
| SteelSeries ApS                  | 3         | 0.08%   |
| Sennheiser Communications        | 3         | 0.08%   |
| Logitech                         | 3         | 0.08%   |
| Lenovo                           | 3         | 0.08%   |
| Texas Instruments                | 2         | 0.05%   |
| Tenx Technology                  | 2         | 0.05%   |
| FUXIN                            | 2         | 0.05%   |
| Apple                            | 2         | 0.05%   |
| Yamaha                           | 1         | 0.03%   |
| XMOS                             | 1         | 0.03%   |
| Vault                            | 1         | 0.03%   |
| Synaptics                        | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Shenzhen Rapoo Technology        | 1         | 0.03%   |
| Samson Technologies              | 1         | 0.03%   |
| Razer USA                        | 1         | 0.03%   |
| Panasonic (Matsushita)           | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Kingston Technology              | 1         | 0.03%   |
| Jieli Technology                 | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Focusrite-Novation               | 1         | 0.03%   |
| FiiO Electronics Technology      | 1         | 0.03%   |
| DSEA A/S                         | 1         | 0.03%   |
| Creative Technology              | 1         | 0.03%   |
| Corsair                          | 1         | 0.03%   |
| CMX Systems                      | 1         | 0.03%   |
| bestechnic                       | 1         | 0.03%   |
| Arturia                          | 1         | 0.03%   |
| Anlya.cn                         | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 619       | 13.54%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 419       | 9.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 228       | 4.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 197       | 4.31%   |
| Intel 8 Series HD Audio Controller                                                                | 188       | 4.11%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 186       | 4.07%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 171       | 3.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 168       | 3.68%   |
| Intel Cannon Lake PCH cAVS                                                                        | 154       | 3.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 151       | 3.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 147       | 3.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 145       | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 144       | 3.15%   |
| Intel Broadwell-U Audio Controller                                                                | 134       | 2.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 133       | 2.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 103       | 2.25%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 88        | 1.93%   |
| AMD FCH Azalia Controller                                                                         | 88        | 1.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 78        | 1.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 69        | 1.51%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 64        | 1.4%    |
| AMD High Definition Audio Controller                                                              | 63        | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 61        | 1.33%   |
| Intel Comet Lake PCH cAVS                                                                         | 55        | 1.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 44        | 0.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 40        | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 39        | 0.85%   |
| Nvidia Audio device                                                                               | 36        | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 35        | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 27        | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 21        | 0.46%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 21        | 0.46%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 20        | 0.44%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 19        | 0.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 19        | 0.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 19        | 0.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19        | 0.42%   |
| AMD Trinity HDMI Audio Controller                                                                 | 18        | 0.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 17        | 0.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 672       | 29.59%  |
| SK hynix            | 609       | 26.82%  |
| Micron Technology   | 316       | 13.91%  |
| Kingston            | 178       | 7.84%   |
| Crucial             | 135       | 5.94%   |
| Ramaxel Technology  | 96        | 4.23%   |
| A-DATA Technology   | 77        | 3.39%   |
| Unknown             | 57        | 2.51%   |
| Transcend           | 32        | 1.41%   |
| CSX                 | 23        | 1.01%   |
| Elpida              | 20        | 0.88%   |
| Nanya Technology    | 18        | 0.79%   |
| Corsair             | 10        | 0.44%   |
| G.Skill             | 5         | 0.22%   |
| Unknown (ABCD)      | 2         | 0.09%   |
| Avant               | 2         | 0.09%   |
| ASint Technology    | 2         | 0.09%   |
| ZION                | 1         | 0.04%   |
| Unknown (0x1007)    | 1         | 0.04%   |
| Unknown (0x0CDC)    | 1         | 0.04%   |
| Unknown (09D5)      | 1         | 0.04%   |
| Unknown (07F7)      | 1         | 0.04%   |
| Team                | 1         | 0.04%   |
| Strontium           | 1         | 0.04%   |
| Silicon Power       | 1         | 0.04%   |
| SHARETRONIC         | 1         | 0.04%   |
| Qumo                | 1         | 0.04%   |
| Qimonda             | 1         | 0.04%   |
| OM Nanotech         | 1         | 0.04%   |
| Lexar Co Limited    | 1         | 0.04%   |
| Kllisre             | 1         | 0.04%   |
| Gold Key            | 1         | 0.04%   |
| Apacer              | 1         | 0.04%   |
| Unknown             | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 62        | 2.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 59        | 2.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 54        | 2.27%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 39        | 1.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s   | 39        | 1.64%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 38        | 1.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 38        | 1.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 34        | 1.43%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 32        | 1.35%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s    | 32        | 1.35%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 30        | 1.26%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 28        | 1.18%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 28        | 1.18%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 27        | 1.14%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 26        | 1.09%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s    | 25        | 1.05%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 23        | 0.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 22        | 0.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 22        | 0.93%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 22        | 0.93%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 22        | 0.93%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 20        | 0.84%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 20        | 0.84%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 20        | 0.84%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 19        | 0.8%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 18        | 0.76%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 17        | 0.71%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s        | 17        | 0.71%   |
| Crucial RAM CB8GS2400.C8ET 8GB SODIMM DDR4 2667MT/s         | 17        | 0.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 16        | 0.67%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s       | 16        | 0.67%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 15        | 0.63%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s       | 14        | 0.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 13        | 0.55%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 13        | 0.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 13        | 0.55%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 13        | 0.55%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s   | 12        | 0.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 12        | 0.5%    |
| Ramaxel RAM RMSA3260MF68H9F-2666 4GB SODIMM DDR4 2400MT/s   | 12        | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1182      | 64.73%  |
| DDR3    | 463       | 25.36%  |
| LPDDR4  | 72        | 3.94%   |
| DDR2    | 28        | 1.53%   |
| LPDDR3  | 26        | 1.42%   |
| SDRAM   | 24        | 1.31%   |
| DDR5    | 14        | 0.77%   |
| LPDDR5  | 13        | 0.71%   |
| Unknown | 3         | 0.16%   |
| DDR     | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1679      | 92.51%  |
| Row Of Chips | 131       | 7.22%   |
| Chip         | 2         | 0.11%   |
| Unknown      | 2         | 0.11%   |
| DIMM         | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 995       | 49.11%  |
| 4096  | 645       | 31.84%  |
| 16384 | 196       | 9.67%   |
| 2048  | 156       | 7.7%    |
| 1024  | 20        | 0.99%   |
| 32768 | 12        | 0.59%   |
| 512   | 2         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 602       | 30.19%  |
| 3200    | 445       | 22.32%  |
| 1600    | 363       | 18.2%   |
| 2400    | 186       | 9.33%   |
| 2133    | 68        | 3.41%   |
| 3266    | 62        | 3.11%   |
| 1334    | 60        | 3.01%   |
| 1333    | 46        | 2.31%   |
| 4267    | 22        | 1.1%    |
| 4199    | 19        | 0.95%   |
| 1067    | 16        | 0.8%    |
| 667     | 15        | 0.75%   |
| 975     | 14        | 0.7%    |
| Unknown | 14        | 0.7%    |
| 6400    | 13        | 0.65%   |
| 4800    | 13        | 0.65%   |
| 1867    | 12        | 0.6%    |
| 800     | 7         | 0.35%   |
| 3733    | 4         | 0.2%    |
| 8400    | 3         | 0.15%   |
| 4266    | 3         | 0.15%   |
| 2048    | 3         | 0.15%   |
| 5200    | 1         | 0.05%   |
| 2800    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 533     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 7         | 41.18%  |
| Canon              | 5         | 29.41%  |
| Seiko Epson        | 2         | 11.76%  |
| STMicroelectronics | 1         | 5.88%   |
| Ricoh              | 1         | 5.88%   |
| Brother Industries | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP LaserJet 1020                        | 2         | 11.76%  |
| HP DeskJet 1110 series                  | 2         | 11.76%  |
| Canon LBP2900                           | 2         | 11.76%  |
| STMicroelectronics USB Printing Support | 1         | 5.88%   |
| Seiko Epson L360 Series                 | 1         | 5.88%   |
| Seiko Epson L132 Series                 | 1         | 5.88%   |
| Ricoh SP 112SU                          | 1         | 5.88%   |
| HP Ink Tank 310 series                  | 1         | 5.88%   |
| HP DeskJet 2620 All-in-One Printer      | 1         | 5.88%   |
| HP DeskJet 2130 series                  | 1         | 5.88%   |
| Canon PIXMA MP190                       | 1         | 5.88%   |
| Canon MF4800 Series                     | 1         | 5.88%   |
| Canon G2000 series                      | 1         | 5.88%   |
| Brother HL-L2320D series                | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 582       | 19.46%  |
| IMC Networks                           | 456       | 15.25%  |
| Realtek Semiconductor                  | 314       | 10.5%   |
| Microdia                               | 304       | 10.17%  |
| Quanta                                 | 203       | 6.79%   |
| Sunplus Innovation Technology          | 187       | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 150       | 5.02%   |
| Bison Electronics                      | 138       | 4.62%   |
| Suyin                                  | 119       | 3.98%   |
| Syntek                                 | 110       | 3.68%   |
| Luxvisions Innotech Limited            | 73        | 2.44%   |
| Acer                                   | 67        | 2.24%   |
| Lite-On Technology                     | 52        | 1.74%   |
| Sonix Technology                       | 29        | 0.97%   |
| Alcor Micro                            | 28        | 0.94%   |
| Apple                                  | 22        | 0.74%   |
| Silicon Motion                         | 21        | 0.7%    |
| Samsung Electronics                    | 21        | 0.7%    |
| Logitech                               | 15        | 0.5%    |
| Ricoh                                  | 14        | 0.47%   |
| Importek                               | 12        | 0.4%    |
| Primax Electronics                     | 10        | 0.33%   |
| OmniVision Technologies                | 8         | 0.27%   |
| Z-Star Microelectronics                | 6         | 0.2%    |
| SunplusIT                              | 6         | 0.2%    |
| Lenovo                                 | 6         | 0.2%    |
| Intel                                  | 5         | 0.17%   |
| Pixart Imaging                         | 4         | 0.13%   |
| vivo                                   | 3         | 0.1%    |
| OPPO Electronics                       | 3         | 0.1%    |
| MSD                                    | 3         | 0.1%    |
| Unknown                                | 2         | 0.07%   |
| Holitech                               | 2         | 0.07%   |
| Foxconn / Hon Hai                      | 2         | 0.07%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| ShineOptics                            | 1         | 0.03%   |
| Nihon KOHDEN                           | 1         | 0.03%   |
| MacroSilicon                           | 1         | 0.03%   |
| Hewlett-Packard                        | 1         | 0.03%   |
| Google                                 | 1         | 0.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 163       | 5.44%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 153       | 5.11%   |
| Realtek Integrated_Webcam_HD                                   | 126       | 4.2%    |
| IMC Networks Integrated Camera                                 | 122       | 4.07%   |
| Chicony Integrated Camera                                      | 121       | 4.04%   |
| Sunplus Integrated_Webcam_HD                                   | 94        | 3.14%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 87        | 2.9%    |
| Chicony HP Truevision HD camera                                | 62        | 2.07%   |
| Realtek Integrated Webcam                                      | 61        | 2.04%   |
| Syntek Integrated Camera                                       | 58        | 1.94%   |
| Chicony HP TrueVision HD                                       | 56        | 1.87%   |
| Quanta HP TrueVision HD Camera                                 | 47        | 1.57%   |
| Chicony HD WebCam                                              | 46        | 1.53%   |
| Chicony EasyCamera                                             | 46        | 1.53%   |
| Quanta HD User Facing                                          | 43        | 1.43%   |
| Suyin HP Truevision HD                                         | 42        | 1.4%    |
| Bison Integrated Camera                                        | 37        | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 34        | 1.13%   |
| Syntek EasyCamera                                              | 32        | 1.07%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 31        | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 31        | 1.03%   |
| Chicony HD User Facing                                         | 30        | 1%      |
| Quanta HD Webcam                                               | 29        | 0.97%   |
| Acer Integrated Camera                                         | 29        | 0.97%   |
| Lite-On Integrated Camera                                      | 26        | 0.87%   |
| IMC Networks HP TrueVision HD Camera                           | 26        | 0.87%   |
| Bison EasyCamera                                               | 26        | 0.87%   |
| Suyin Integrated_Webcam_HD                                     | 24        | 0.8%    |
| Sonix USB2.0 HD UVC WebCam                                     | 24        | 0.8%    |
| Quanta HP Wide Vision HD Camera                                | 24        | 0.8%    |
| Microdia Laptop_Integrated_Webcam_HD                           | 24        | 0.8%    |
| Microdia Integrated Webcam                                     | 24        | 0.8%    |
| Bison Lenovo EasyCamera                                        | 23        | 0.77%   |
| Realtek EasyCamera                                             | 22        | 0.73%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 21        | 0.7%    |
| Chicony HP Wide Vision HD Camera                               | 21        | 0.7%    |
| Bison SunplusIT Integrated Camera                              | 21        | 0.7%    |
| Luxvisions Innotech Limited Integrated Camera                  | 20        | 0.67%   |
| Chicony Integrated Camera (1280x720@30)                        | 20        | 0.67%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 19        | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 179       | 33.65%  |
| Shenzhen Goodix Technology         | 110       | 20.68%  |
| Synaptics                          | 100       | 18.8%   |
| Elan Microelectronics              | 83        | 15.6%   |
| LighTuning Technology              | 21        | 3.95%   |
| AuthenTec                          | 12        | 2.26%   |
| Upek                               | 10        | 1.88%   |
| Realtek USB2.0 Finger Print Bridge | 10        | 1.88%   |
| Focal-systems.Corp                 | 6         | 1.13%   |
| STMicroelectronics                 | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 68        | 12.78%  |
| Elan ELAN:ARM-M4                                                           | 54        | 10.15%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 51        | 9.59%   |
| Shenzhen Goodix Fingerprint Reader                                         | 36        | 6.77%   |
| Elan ELAN:Fingerprint                                                      | 29        | 5.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 4.51%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 23        | 4.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 23        | 4.32%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 3.95%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 3.2%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 15        | 2.82%   |
| Synaptics WBDI                                                             | 14        | 2.63%   |
| Synaptics  WBDI                                                            | 13        | 2.44%   |
| Validity Sensors VFS491                                                    | 11        | 2.07%   |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 2.07%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 2.07%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 10        | 1.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 1.69%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 1.5%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.13%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.13%   |
| Synaptics UWP WBDI                                                         | 6         | 1.13%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 1.13%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 6         | 1.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 0.94%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 0.94%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.94%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 0.75%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 0.75%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.38%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 0.38%   |
| AuthenTec AES2810                                                          | 2         | 0.38%   |
| AuthenTec AES1600                                                          | 2         | 0.38%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.19%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.19%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.19%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 63        | 64.95%  |
| Alcor Micro           | 19        | 19.59%  |
| Upek                  | 8         | 8.25%   |
| O2 Micro              | 3         | 3.09%   |
| Lenovo                | 3         | 3.09%   |
| Gemalto (was Gemplus) | 1         | 1.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 22.45%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 19.39%  |
| Broadcom 5880                                                                | 18        | 18.37%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 13.27%  |
| Broadcom 58200                                                               | 11        | 11.22%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 8.16%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.06%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.04%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.02%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.02%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2054      | 62.83%  |
| 1     | 1017      | 31.11%  |
| 2     | 161       | 4.93%   |
| 3     | 25        | 0.76%   |
| 4     | 5         | 0.15%   |
| 5     | 4         | 0.12%   |
| 9     | 2         | 0.06%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 527       | 37.09%  |
| Graphics card            | 336       | 23.65%  |
| Net/wireless             | 177       | 12.46%  |
| Chipcard                 | 93        | 6.54%   |
| Bluetooth                | 84        | 5.91%   |
| Multimedia controller    | 70        | 4.93%   |
| Camera                   | 49        | 3.45%   |
| Communication controller | 31        | 2.18%   |
| Net/ethernet             | 15        | 1.06%   |
| Sound                    | 13        | 0.91%   |
| Storage                  | 12        | 0.84%   |
| Card reader              | 5         | 0.35%   |
| Network                  | 4         | 0.28%   |
| Modem                    | 4         | 0.28%   |
| Storage/nvme             | 1         | 0.07%   |

