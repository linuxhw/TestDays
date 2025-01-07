Linux in Denmark - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Denmark.

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

Total: 1069

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro14,3              | [f0fd4c6916](https://linux-hardware.org/?probe=f0fd4c6916) | Jan 04, 2025 |
| Apple         | MacBookPro14,3              | [bb8ec4a124](https://linux-hardware.org/?probe=bb8ec4a124) | Jan 04, 2025 |
| Lenovo        | ThinkPad T460s 20FAS14F0... | [f72b380ee6](https://linux-hardware.org/?probe=f72b380ee6) | Jan 02, 2025 |
| Acer          | Aspire A317-52              | [8a5d9221e7](https://linux-hardware.org/?probe=8a5d9221e7) | Dec 31, 2024 |
| HP            | Laptop 14-bp0xx             | [cb99b9c4f9](https://linux-hardware.org/?probe=cb99b9c4f9) | Dec 29, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [bb120a943a](https://linux-hardware.org/?probe=bb120a943a) | Dec 21, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | [d2c83af14f](https://linux-hardware.org/?probe=d2c83af14f) | Dec 17, 2024 |
| Lenovo        | ThinkPad X250 20CLS64200    | [d92935db90](https://linux-hardware.org/?probe=d92935db90) | Dec 17, 2024 |
| Lenovo        | G570 PIWG1                  | [b41ab58347](https://linux-hardware.org/?probe=b41ab58347) | Dec 17, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [6f50478831](https://linux-hardware.org/?probe=6f50478831) | Dec 16, 2024 |
| Acer          | Aspire A317-52              | [9523b85250](https://linux-hardware.org/?probe=9523b85250) | Dec 10, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [a477748a96](https://linux-hardware.org/?probe=a477748a96) | Dec 10, 2024 |
| Acer          | Aspire A315-41              | [629a42a94d](https://linux-hardware.org/?probe=629a42a94d) | Dec 03, 2024 |
| Acer          | Aspire A315-41              | [dff6e368e4](https://linux-hardware.org/?probe=dff6e368e4) | Dec 02, 2024 |
| Lenovo        | ThinkPad L430 24686FG       | [4e8a8081b5](https://linux-hardware.org/?probe=4e8a8081b5) | Nov 27, 2024 |
| Dell          | XPS 13 9350                 | [e26379b5f0](https://linux-hardware.org/?probe=e26379b5f0) | Nov 24, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [54831941d8](https://linux-hardware.org/?probe=54831941d8) | Nov 23, 2024 |
| Dell          | XPS 13 9350                 | [e508f9977c](https://linux-hardware.org/?probe=e508f9977c) | Nov 20, 2024 |
| Dell          | XPS 13 9350                 | [e616b2e3b6](https://linux-hardware.org/?probe=e616b2e3b6) | Nov 20, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M3C... | [3651cea5f4](https://linux-hardware.org/?probe=3651cea5f4) | Nov 10, 2024 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [6370e4afbb](https://linux-hardware.org/?probe=6370e4afbb) | Nov 10, 2024 |
| Lenovo        | ThinkPad T510 4349WDB       | [096b262747](https://linux-hardware.org/?probe=096b262747) | Nov 10, 2024 |
| PC Special... | Lafite Pro IV 14M           | [401560b9d8](https://linux-hardware.org/?probe=401560b9d8) | Nov 08, 2024 |
| Lenovo        | ThinkPad L430 24686FG       | [ad1f01a426](https://linux-hardware.org/?probe=ad1f01a426) | Nov 07, 2024 |
| Dell          | Precision 3590              | [bc82f6333a](https://linux-hardware.org/?probe=bc82f6333a) | Nov 02, 2024 |
| HUAWEI        | NBD-WXX9                    | [3f98ffc684](https://linux-hardware.org/?probe=3f98ffc684) | Oct 31, 2024 |
| Lenovo        | ThinkPad T495 20NKS02N00    | [ab02b5d5f4](https://linux-hardware.org/?probe=ab02b5d5f4) | Oct 29, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [4408314643](https://linux-hardware.org/?probe=4408314643) | Oct 29, 2024 |
| Apple         | MacBookPro11,1              | [95fc0bceda](https://linux-hardware.org/?probe=95fc0bceda) | Oct 26, 2024 |
| Apple         | MacBookPro11,1              | [dbd73dea03](https://linux-hardware.org/?probe=dbd73dea03) | Oct 26, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [f697805e66](https://linux-hardware.org/?probe=f697805e66) | Oct 24, 2024 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [a915ce3cad](https://linux-hardware.org/?probe=a915ce3cad) | Oct 22, 2024 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [1b0f12acd4](https://linux-hardware.org/?probe=1b0f12acd4) | Oct 22, 2024 |
| Lenovo        | ThinkPad L430 24686FG       | [6d653f02e9](https://linux-hardware.org/?probe=6d653f02e9) | Oct 21, 2024 |
| MSI           | GT72S 6QE                   | [0cfe32ce18](https://linux-hardware.org/?probe=0cfe32ce18) | Oct 20, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [8132169207](https://linux-hardware.org/?probe=8132169207) | Oct 17, 2024 |
| Dell          | XPS 15 9560                 | [cac6b26403](https://linux-hardware.org/?probe=cac6b26403) | Oct 15, 2024 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [3daad6b7aa](https://linux-hardware.org/?probe=3daad6b7aa) | Oct 14, 2024 |
| MSI           | GT72S 6QE                   | [dd761bfc6f](https://linux-hardware.org/?probe=dd761bfc6f) | Oct 13, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [d875e5f8df](https://linux-hardware.org/?probe=d875e5f8df) | Oct 11, 2024 |
| Apple         | MacBookPro11,1              | [7d61f2702c](https://linux-hardware.org/?probe=7d61f2702c) | Oct 08, 2024 |
| ASUSTek       | ZenBook UX482EGR_UX482EG... | [3ebec0e8f3](https://linux-hardware.org/?probe=3ebec0e8f3) | Oct 04, 2024 |
| Gigabyte      | G5 KC                       | [b342b2a6f1](https://linux-hardware.org/?probe=b342b2a6f1) | Sep 30, 2024 |
| HP            | Laptop 15-fd0xxx            | [a61ba00701](https://linux-hardware.org/?probe=a61ba00701) | Sep 30, 2024 |
| HP            | Laptop 14-bw0xx             | [5be8d95c83](https://linux-hardware.org/?probe=5be8d95c83) | Sep 29, 2024 |
| Gigabyte      | AORUS 15G XC                | [e713caaf0f](https://linux-hardware.org/?probe=e713caaf0f) | Sep 26, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [2fa674eb00](https://linux-hardware.org/?probe=2fa674eb00) | Sep 26, 2024 |
| Lenovo        | ThinkPad T520 42404CG       | [696d5cd6ec](https://linux-hardware.org/?probe=696d5cd6ec) | Sep 25, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [34bb43620b](https://linux-hardware.org/?probe=34bb43620b) | Sep 24, 2024 |
| Packard Be... | EasyNote TE69BM             | [6990e9cba3](https://linux-hardware.org/?probe=6990e9cba3) | Sep 23, 2024 |
| Insyde        | CherryTrail                 | [aa218e8eef](https://linux-hardware.org/?probe=aa218e8eef) | Sep 22, 2024 |
| Insyde        | CherryTrail                 | [c314b95caf](https://linux-hardware.org/?probe=c314b95caf) | Sep 22, 2024 |
| Lenovo        | ThinkPad L430 24686FG       | [4b56e663e1](https://linux-hardware.org/?probe=4b56e663e1) | Sep 19, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [dfca2e65f8](https://linux-hardware.org/?probe=dfca2e65f8) | Sep 19, 2024 |
| Apple         | MacBookPro14,1              | [004786a4d3](https://linux-hardware.org/?probe=004786a4d3) | Sep 18, 2024 |
| Lenovo        | ThinkPad T480s 20L8S9JE0... | [9ef5814db9](https://linux-hardware.org/?probe=9ef5814db9) | Sep 17, 2024 |
| Lenovo        | ThinkPad T420 4236Y19       | [13fbdbca13](https://linux-hardware.org/?probe=13fbdbca13) | Sep 15, 2024 |
| Lenovo        | G505s 20255                 | [929b9ceeda](https://linux-hardware.org/?probe=929b9ceeda) | Sep 14, 2024 |
| Lenovo        | IdeaPad S540-14API 81NH     | [a1593b5f7c](https://linux-hardware.org/?probe=a1593b5f7c) | Sep 14, 2024 |
| Acer          | Aspire 8943G                | [281d735bda](https://linux-hardware.org/?probe=281d735bda) | Sep 12, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3dee7cffac](https://linux-hardware.org/?probe=3dee7cffac) | Sep 11, 2024 |
| Apple         | MacBookPro9,2               | [8062c8c6db](https://linux-hardware.org/?probe=8062c8c6db) | Sep 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [682b1cad5b](https://linux-hardware.org/?probe=682b1cad5b) | Sep 02, 2024 |
| Apple         | MacBookPro8,1               | [3de9cb3d60](https://linux-hardware.org/?probe=3de9cb3d60) | Sep 01, 2024 |
| HP            | EliteBook 865 16 inch G9... | [8f52a83d6b](https://linux-hardware.org/?probe=8f52a83d6b) | Aug 30, 2024 |
| Acer          | Aspire 5755G                | [0482183a93](https://linux-hardware.org/?probe=0482183a93) | Aug 26, 2024 |
| KaiTian       | N80z G1d                    | [58db0eb2b0](https://linux-hardware.org/?probe=58db0eb2b0) | Aug 26, 2024 |
| Lenovo        | Legion 5 17ACH6 82K0        | [fa9e63db04](https://linux-hardware.org/?probe=fa9e63db04) | Aug 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [43e253bc17](https://linux-hardware.org/?probe=43e253bc17) | Aug 24, 2024 |
| Lenovo        | ThinkPad T490s 20NX001KM... | [83f3da5e32](https://linux-hardware.org/?probe=83f3da5e32) | Aug 22, 2024 |
| ASUSTek       | ZenBook UX482EGR_UX482EG... | [6d91f09db2](https://linux-hardware.org/?probe=6d91f09db2) | Aug 19, 2024 |
| HP            | EliteBook 865 16 inch G1... | [32e5b4ca60](https://linux-hardware.org/?probe=32e5b4ca60) | Aug 17, 2024 |
| Lenovo        | ThinkPad T460 20FMS5DX00    | [fab5ffbd76](https://linux-hardware.org/?probe=fab5ffbd76) | Aug 15, 2024 |
| HP            | EliteBook 820 G1            | [78dbe2d953](https://linux-hardware.org/?probe=78dbe2d953) | Aug 12, 2024 |
| Valve         | Jupiter                     | [548d0048d4](https://linux-hardware.org/?probe=548d0048d4) | Aug 10, 2024 |
| Samsung       | 530U3C/530U4C               | [eed67edfb9](https://linux-hardware.org/?probe=eed67edfb9) | Aug 09, 2024 |
| ASUSTek       | K56CB                       | [729ed18903](https://linux-hardware.org/?probe=729ed18903) | Aug 09, 2024 |
| Apple         | MacBookPro6,2               | [6abef655ee](https://linux-hardware.org/?probe=6abef655ee) | Aug 05, 2024 |
| HP            | Pavilion Notebook           | [5762943352](https://linux-hardware.org/?probe=5762943352) | Aug 04, 2024 |
| Toshiba       | Satellite L50-B             | [00b4917faf](https://linux-hardware.org/?probe=00b4917faf) | Aug 02, 2024 |
| Lenovo        | ThinkPad T450 20BUS04U00    | [720b525240](https://linux-hardware.org/?probe=720b525240) | Jul 31, 2024 |
| HP            | Laptop 14-cf3xxx            | [b09688c182](https://linux-hardware.org/?probe=b09688c182) | Jul 30, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [6332bb4a7c](https://linux-hardware.org/?probe=6332bb4a7c) | Jul 29, 2024 |
| Dell          | XPS 15 9560                 | [25ebe75076](https://linux-hardware.org/?probe=25ebe75076) | Jul 27, 2024 |
| ASUSTek       | X555LN                      | [1af7465509](https://linux-hardware.org/?probe=1af7465509) | Jul 25, 2024 |
| Apple         | MacBookPro12,1              | [21a780bb08](https://linux-hardware.org/?probe=21a780bb08) | Jul 25, 2024 |
| Lenovo        | ThinkPad R500 2718Y21       | [527c6d0299](https://linux-hardware.org/?probe=527c6d0299) | Jul 23, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | [9ee15286f8](https://linux-hardware.org/?probe=9ee15286f8) | Jul 23, 2024 |
| ASUSTek       | X555LN                      | [f80f9105c0](https://linux-hardware.org/?probe=f80f9105c0) | Jul 22, 2024 |
| Dell          | Latitude E5570              | [0165747ee0](https://linux-hardware.org/?probe=0165747ee0) | Jul 22, 2024 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [604f304877](https://linux-hardware.org/?probe=604f304877) | Jul 20, 2024 |
| Lenovo        | Legion 5 17ACH6 82K0        | [b2785d195d](https://linux-hardware.org/?probe=b2785d195d) | Jul 19, 2024 |
| MSI           | GE60 0NC\0ND                | [1ed51b449b](https://linux-hardware.org/?probe=1ed51b449b) | Jul 17, 2024 |
| Apple         | MacBookAir7,2               | [fb2b18385d](https://linux-hardware.org/?probe=fb2b18385d) | Jul 16, 2024 |
| Apple         | MacBookAir7,2               | [a4156a8d93](https://linux-hardware.org/?probe=a4156a8d93) | Jul 15, 2024 |
| Lenovo        | ThinkPad P50 20EQS0SS02     | [d40bef0611](https://linux-hardware.org/?probe=d40bef0611) | Jul 15, 2024 |
| HP            | Laptop 14-bp0xx             | [b937727b2f](https://linux-hardware.org/?probe=b937727b2f) | Jul 14, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [4da9ebe6b5](https://linux-hardware.org/?probe=4da9ebe6b5) | Jul 13, 2024 |
| ASUSTek       | N61Ja                       | [d84f30b1ac](https://linux-hardware.org/?probe=d84f30b1ac) | Jul 11, 2024 |
| Dell          | XPS 15 9560                 | [25ede9dd80](https://linux-hardware.org/?probe=25ede9dd80) | Jul 08, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [fa8f1445c6](https://linux-hardware.org/?probe=fa8f1445c6) | Jul 07, 2024 |
| DukaPC        | Notebook                    | [663f76e509](https://linux-hardware.org/?probe=663f76e509) | Jul 06, 2024 |
| DukaPC        | Notebook                    | [92320431fc](https://linux-hardware.org/?probe=92320431fc) | Jul 06, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f846e6d9a0](https://linux-hardware.org/?probe=f846e6d9a0) | Jul 05, 2024 |
| Dell          | Latitude E5530 vPro         | [0aee03627c](https://linux-hardware.org/?probe=0aee03627c) | Jul 05, 2024 |
| Lenovo        | ThinkPad W520 42844DG       | [dbf9675b6f](https://linux-hardware.org/?probe=dbf9675b6f) | Jul 03, 2024 |
| HUAWEI        | VLT-WX0                     | [f81bb40cb8](https://linux-hardware.org/?probe=f81bb40cb8) | Jul 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [4ace4ec7d7](https://linux-hardware.org/?probe=4ace4ec7d7) | Jun 26, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [c8bce44bed](https://linux-hardware.org/?probe=c8bce44bed) | Jun 26, 2024 |
| Dell          | XPS 15 9560                 | [94420d4e41](https://linux-hardware.org/?probe=94420d4e41) | Jun 22, 2024 |
| Lenovo        | ThinkPad P50 20EQS4WE00     | [848e7fb28d](https://linux-hardware.org/?probe=848e7fb28d) | Jun 22, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M3C... | [2439930306](https://linux-hardware.org/?probe=2439930306) | Jun 21, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1559ed1fe8](https://linux-hardware.org/?probe=1559ed1fe8) | Jun 21, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | [640bc2625d](https://linux-hardware.org/?probe=640bc2625d) | Jun 20, 2024 |
| Apple         | MacBookPro9,2               | [1e749ba1db](https://linux-hardware.org/?probe=1e749ba1db) | Jun 16, 2024 |
| Apple         | MacBookPro9,2               | [3320dec817](https://linux-hardware.org/?probe=3320dec817) | Jun 16, 2024 |
| HP            | EliteBook 835 G7 Noteboo... | [b61a1876ce](https://linux-hardware.org/?probe=b61a1876ce) | Jun 10, 2024 |
| Dell          | Latitude E6540              | [2ee4199956](https://linux-hardware.org/?probe=2ee4199956) | Jun 08, 2024 |
| Acer          | Swift SF314-71              | [abf6fd0327](https://linux-hardware.org/?probe=abf6fd0327) | Jun 06, 2024 |
| Apple         | MacBookPro11,1              | [84e47689d9](https://linux-hardware.org/?probe=84e47689d9) | Jun 05, 2024 |
| Samsung       | 930XCJ/931XCJ/930XCR        | [695c57972e](https://linux-hardware.org/?probe=695c57972e) | Jun 03, 2024 |
| HP            | EliteBook 840 G4            | [48160903f4](https://linux-hardware.org/?probe=48160903f4) | May 31, 2024 |
| HP            | ProBook 650 G5              | [a16d697703](https://linux-hardware.org/?probe=a16d697703) | May 31, 2024 |
| ASUSTek       | N61Ja                       | [7c18215693](https://linux-hardware.org/?probe=7c18215693) | May 30, 2024 |
| ASUSTek       | N61Ja                       | [e19c4ee418](https://linux-hardware.org/?probe=e19c4ee418) | May 29, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [e013c89601](https://linux-hardware.org/?probe=e013c89601) | May 29, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [0be687bb2b](https://linux-hardware.org/?probe=0be687bb2b) | May 24, 2024 |
| Acer          | Predator PH517-61           | [73fa0da6ff](https://linux-hardware.org/?probe=73fa0da6ff) | May 19, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | [54d8293b03](https://linux-hardware.org/?probe=54d8293b03) | May 18, 2024 |
| Lenovo        | ThinkPad P52 20M9001GMX     | [66fffdafc4](https://linux-hardware.org/?probe=66fffdafc4) | May 18, 2024 |
| Acer          | Aspire A315-58              | [c91df0ad77](https://linux-hardware.org/?probe=c91df0ad77) | May 10, 2024 |
| Dell          | XPS 13 9370                 | [f0b2a52c24](https://linux-hardware.org/?probe=f0b2a52c24) | May 09, 2024 |
| Apple         | MacBookPro9,1               | [6d6aee3150](https://linux-hardware.org/?probe=6d6aee3150) | May 09, 2024 |
| Apple         | MacBookPro9,1               | [2c63121414](https://linux-hardware.org/?probe=2c63121414) | May 09, 2024 |
| Lenovo        | Z50-75 80EC                 | [1a1e8edc3b](https://linux-hardware.org/?probe=1a1e8edc3b) | May 08, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | [9c6cf56bbb](https://linux-hardware.org/?probe=9c6cf56bbb) | May 05, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5975b5df1b](https://linux-hardware.org/?probe=5975b5df1b) | May 04, 2024 |
| Lenovo        | ThinkPad T450 20BUS2SS00    | [5d764e707b](https://linux-hardware.org/?probe=5d764e707b) | May 04, 2024 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [ad5d8cbdf2](https://linux-hardware.org/?probe=ad5d8cbdf2) | May 03, 2024 |
| Lenovo        | ThinkPad T480S 20L7001PM... | [4baef88334](https://linux-hardware.org/?probe=4baef88334) | May 03, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | [901ee2545c](https://linux-hardware.org/?probe=901ee2545c) | Apr 30, 2024 |
| Acer          | Aspire 7741                 | [69f109864f](https://linux-hardware.org/?probe=69f109864f) | Apr 28, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3f5beab74c](https://linux-hardware.org/?probe=3f5beab74c) | Apr 28, 2024 |
| Apple         | MacBookPro11,3              | [923b49223a](https://linux-hardware.org/?probe=923b49223a) | Apr 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [66f95f549d](https://linux-hardware.org/?probe=66f95f549d) | Apr 27, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [967c710a95](https://linux-hardware.org/?probe=967c710a95) | Apr 19, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [ab7744c990](https://linux-hardware.org/?probe=ab7744c990) | Apr 19, 2024 |
| Apple         | MacBookPro8,1               | [8c7365ffeb](https://linux-hardware.org/?probe=8c7365ffeb) | Apr 17, 2024 |
| Apple         | MacBookPro8,1               | [3b4a5c61ff](https://linux-hardware.org/?probe=3b4a5c61ff) | Apr 17, 2024 |
| Dell          | XPS 15 9560                 | [5e92237577](https://linux-hardware.org/?probe=5e92237577) | Apr 16, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [a00d0bb1b4](https://linux-hardware.org/?probe=a00d0bb1b4) | Apr 16, 2024 |
| ASUSTek       | EB1503                      | [21afa9fbb5](https://linux-hardware.org/?probe=21afa9fbb5) | Apr 10, 2024 |
| Samsung       | 930XCJ/931XCJ/930XCR        | [c08adc1120](https://linux-hardware.org/?probe=c08adc1120) | Apr 09, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [9868b5573c](https://linux-hardware.org/?probe=9868b5573c) | Apr 07, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | [1658229b9a](https://linux-hardware.org/?probe=1658229b9a) | Apr 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a93a4109d7](https://linux-hardware.org/?probe=a93a4109d7) | Apr 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b51e077a23](https://linux-hardware.org/?probe=b51e077a23) | Apr 07, 2024 |
| Dell          | Latitude E7440              | [dbc6236ae1](https://linux-hardware.org/?probe=dbc6236ae1) | Apr 06, 2024 |
| Razer         | Blade 15 Base Model (Ear... | [a2838e8dc8](https://linux-hardware.org/?probe=a2838e8dc8) | Apr 06, 2024 |
| Unknown       | TK23D                       | [47ffc66996](https://linux-hardware.org/?probe=47ffc66996) | Apr 05, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [09a8421999](https://linux-hardware.org/?probe=09a8421999) | Apr 04, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [77d2d8ef3e](https://linux-hardware.org/?probe=77d2d8ef3e) | Mar 31, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [070fdbee15](https://linux-hardware.org/?probe=070fdbee15) | Mar 29, 2024 |
| Lenovo        | ThinkPad T530 24295L4       | [bc2f245e57](https://linux-hardware.org/?probe=bc2f245e57) | Mar 28, 2024 |
| Acer          | Aspire 5755G                | [4aa12cd64e](https://linux-hardware.org/?probe=4aa12cd64e) | Mar 24, 2024 |
| HP            | Pavilion dv9700             | [6851f7a21a](https://linux-hardware.org/?probe=6851f7a21a) | Mar 22, 2024 |
| Razer         | Blade Stealth               | [427d6b97d0](https://linux-hardware.org/?probe=427d6b97d0) | Mar 20, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [a72ccae833](https://linux-hardware.org/?probe=a72ccae833) | Mar 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5bfcaa91cf](https://linux-hardware.org/?probe=5bfcaa91cf) | Mar 19, 2024 |
| Lenovo        | ThinkPad T480s 20L8S9DL0... | [0df7e53a5b](https://linux-hardware.org/?probe=0df7e53a5b) | Mar 19, 2024 |
| Lenovo        | ThinkPad T410 2537PW4       | [29306b301d](https://linux-hardware.org/?probe=29306b301d) | Mar 15, 2024 |
| Dell          | Precision 7530              | [d78921804c](https://linux-hardware.org/?probe=d78921804c) | Mar 15, 2024 |
| Apple         | MacBookAir6,2               | [f18604dfcc](https://linux-hardware.org/?probe=f18604dfcc) | Mar 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [66ebc0d790](https://linux-hardware.org/?probe=66ebc0d790) | Mar 11, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [2e420dae7e](https://linux-hardware.org/?probe=2e420dae7e) | Mar 09, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [321f40d2d0](https://linux-hardware.org/?probe=321f40d2d0) | Mar 08, 2024 |
| ASUSTek       | EP121                       | [6f48afbbb5](https://linux-hardware.org/?probe=6f48afbbb5) | Mar 04, 2024 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [e64f4ad280](https://linux-hardware.org/?probe=e64f4ad280) | Feb 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c011a124eb](https://linux-hardware.org/?probe=c011a124eb) | Feb 24, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [63323ac7cf](https://linux-hardware.org/?probe=63323ac7cf) | Feb 23, 2024 |
| Lenovo        | ThinkPad T570 20H9001EMD    | [0841df80ee](https://linux-hardware.org/?probe=0841df80ee) | Feb 21, 2024 |
| Lenovo        | ThinkPad T460 20FMS4E900    | [c8b5b2db19](https://linux-hardware.org/?probe=c8b5b2db19) | Feb 20, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [bf621b6156](https://linux-hardware.org/?probe=bf621b6156) | Feb 18, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [2d7a44f48a](https://linux-hardware.org/?probe=2d7a44f48a) | Feb 09, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [26118c8441](https://linux-hardware.org/?probe=26118c8441) | Feb 09, 2024 |
| Lenovo        | ThinkPad L440 20AT0020US    | [1b7b76a553](https://linux-hardware.org/?probe=1b7b76a553) | Feb 09, 2024 |
| Lenovo        | ThinkPad T470 20HES20V02    | [58ebcebabd](https://linux-hardware.org/?probe=58ebcebabd) | Feb 08, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [86d506e6eb](https://linux-hardware.org/?probe=86d506e6eb) | Feb 08, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [49de677b38](https://linux-hardware.org/?probe=49de677b38) | Feb 08, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | [521842d39b](https://linux-hardware.org/?probe=521842d39b) | Feb 07, 2024 |
| Lenovo        | ThinkPad L440 20AT0020US    | [31fe816ba8](https://linux-hardware.org/?probe=31fe816ba8) | Feb 05, 2024 |
| Apple         | MacBookPro11,1              | [a52e3353f6](https://linux-hardware.org/?probe=a52e3353f6) | Feb 03, 2024 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [74173e2c0a](https://linux-hardware.org/?probe=74173e2c0a) | Feb 01, 2024 |
| ASUSTek       | K54C                        | [59e4e733f0](https://linux-hardware.org/?probe=59e4e733f0) | Feb 01, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [d8ab9529f3](https://linux-hardware.org/?probe=d8ab9529f3) | Jan 27, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | [1c0f2e8a2f](https://linux-hardware.org/?probe=1c0f2e8a2f) | Jan 26, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [789bbeb50a](https://linux-hardware.org/?probe=789bbeb50a) | Jan 24, 2024 |
| Apple         | MacBookPro11,1              | [e9bc4f9199](https://linux-hardware.org/?probe=e9bc4f9199) | Jan 22, 2024 |
| ASUSTek       | K56CB                       | [5cc6df781d](https://linux-hardware.org/?probe=5cc6df781d) | Jan 20, 2024 |
| Toshiba       | Satellite C855D-11X         | [d047649166](https://linux-hardware.org/?probe=d047649166) | Jan 14, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | [b521a115f8](https://linux-hardware.org/?probe=b521a115f8) | Jan 12, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | [7d95af598c](https://linux-hardware.org/?probe=7d95af598c) | Jan 12, 2024 |
| Lenovo        | ThinkPad T560 20FH001BMD    | [aefb2eccb9](https://linux-hardware.org/?probe=aefb2eccb9) | Jan 09, 2024 |
| Lenovo        | Z50-70 20354                | [052f307ab5](https://linux-hardware.org/?probe=052f307ab5) | Jan 09, 2024 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [70681bd4a7](https://linux-hardware.org/?probe=70681bd4a7) | Jan 09, 2024 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [bbe152d4f5](https://linux-hardware.org/?probe=bbe152d4f5) | Jan 07, 2024 |
| Apple         | MacBookPro13,2              | [c7e8eb2475](https://linux-hardware.org/?probe=c7e8eb2475) | Jan 07, 2024 |
| Notebook      | N14xWU                      | [0460984dea](https://linux-hardware.org/?probe=0460984dea) | Jan 02, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | [095d9cbf7e](https://linux-hardware.org/?probe=095d9cbf7e) | Jan 01, 2024 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [e456132635](https://linux-hardware.org/?probe=e456132635) | Dec 28, 2023 |
| HP            | Compaq 2510p                | [b7b88f9c1c](https://linux-hardware.org/?probe=b7b88f9c1c) | Dec 27, 2023 |
| Apple         | MacBookPro11,1              | [344f1c919a](https://linux-hardware.org/?probe=344f1c919a) | Dec 27, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [fb78f052e1](https://linux-hardware.org/?probe=fb78f052e1) | Dec 25, 2023 |
| Toshiba       | Satellite P850              | [e16f04d074](https://linux-hardware.org/?probe=e16f04d074) | Dec 23, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [987ab63f96](https://linux-hardware.org/?probe=987ab63f96) | Dec 17, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [2167a2f148](https://linux-hardware.org/?probe=2167a2f148) | Dec 16, 2023 |
| Acer          | Nitro AN715-51              | [279ade4fb0](https://linux-hardware.org/?probe=279ade4fb0) | Dec 16, 2023 |
| Medion        | P7624                       | [4828985ec0](https://linux-hardware.org/?probe=4828985ec0) | Dec 15, 2023 |
| Medion        | P7624                       | [050fbbd613](https://linux-hardware.org/?probe=050fbbd613) | Dec 15, 2023 |
| Apple         | MacBookPro13,2              | [9200b90a95](https://linux-hardware.org/?probe=9200b90a95) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | [917471b136](https://linux-hardware.org/?probe=917471b136) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | [6c3498a025](https://linux-hardware.org/?probe=6c3498a025) | Dec 12, 2023 |
| Dell          | Latitude E6540              | [0d56fcda0e](https://linux-hardware.org/?probe=0d56fcda0e) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [332492b0c4](https://linux-hardware.org/?probe=332492b0c4) | Dec 11, 2023 |
| Unknown       | TK23D                       | [27c0f3c1f6](https://linux-hardware.org/?probe=27c0f3c1f6) | Dec 07, 2023 |
| Lenovo        | V110-15IAP 80TG             | [ff40966f37](https://linux-hardware.org/?probe=ff40966f37) | Dec 04, 2023 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | [151a3ceaf0](https://linux-hardware.org/?probe=151a3ceaf0) | Dec 03, 2023 |
| Acer          | Aspire V5-573               | [8a76c8baac](https://linux-hardware.org/?probe=8a76c8baac) | Nov 30, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BE09    | [33b3b8ed10](https://linux-hardware.org/?probe=33b3b8ed10) | Nov 29, 2023 |
| Apple         | MacBookPro8,1               | [b305057bc5](https://linux-hardware.org/?probe=b305057bc5) | Nov 27, 2023 |
| Acer          | Aspire 7741                 | [d1e2c905e1](https://linux-hardware.org/?probe=d1e2c905e1) | Nov 25, 2023 |
| Dell          | Studio XPS 1640             | [3b9a32eb3f](https://linux-hardware.org/?probe=3b9a32eb3f) | Nov 24, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [3b995f6b47](https://linux-hardware.org/?probe=3b995f6b47) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [37a1e3b979](https://linux-hardware.org/?probe=37a1e3b979) | Nov 23, 2023 |
| Gigabyte      | B650M DS3H                  | [dfcb329b5a](https://linux-hardware.org/?probe=dfcb329b5a) | Nov 23, 2023 |
| Sony          | SVE14A2M6EW                 | [9f444d1508](https://linux-hardware.org/?probe=9f444d1508) | Nov 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [049356e4bc](https://linux-hardware.org/?probe=049356e4bc) | Nov 15, 2023 |
| HP            | EliteBook 840 G2            | [64cfcced5b](https://linux-hardware.org/?probe=64cfcced5b) | Nov 14, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | [f5f9243038](https://linux-hardware.org/?probe=f5f9243038) | Nov 11, 2023 |
| HP            | Pavilion g7                 | [f963761c30](https://linux-hardware.org/?probe=f963761c30) | Nov 10, 2023 |
| Dell          | Precision M4600             | [0aabbcfa0b](https://linux-hardware.org/?probe=0aabbcfa0b) | Nov 06, 2023 |
| Acer          | Aspire A315-58              | [95f3002643](https://linux-hardware.org/?probe=95f3002643) | Nov 05, 2023 |
| Lenovo        | ThinkPad W550s 20E2000PM... | [1294d54c1a](https://linux-hardware.org/?probe=1294d54c1a) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | [1d51aba71e](https://linux-hardware.org/?probe=1d51aba71e) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | [585906fa27](https://linux-hardware.org/?probe=585906fa27) | Nov 04, 2023 |
| Dell          | Precision 5750              | [00e8468779](https://linux-hardware.org/?probe=00e8468779) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [00a8b74f46](https://linux-hardware.org/?probe=00a8b74f46) | Nov 03, 2023 |
| Acer          | Aspire A515-45              | [b367027f2a](https://linux-hardware.org/?probe=b367027f2a) | Oct 30, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | [e8252549f4](https://linux-hardware.org/?probe=e8252549f4) | Oct 29, 2023 |
| ASUSTek       | X555LN                      | [783a3b6555](https://linux-hardware.org/?probe=783a3b6555) | Oct 24, 2023 |
| HP            | Laptop 15s-eq1xxx           | [5795100325](https://linux-hardware.org/?probe=5795100325) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a2756e1d2b](https://linux-hardware.org/?probe=a2756e1d2b) | Oct 21, 2023 |
| Lenovo        | IdeaPad Y500 9541           | [999de2ca37](https://linux-hardware.org/?probe=999de2ca37) | Oct 16, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [1215db6b88](https://linux-hardware.org/?probe=1215db6b88) | Oct 13, 2023 |
| ASUSTek       | Strix 15 GL503GE            | [95ef83d6fd](https://linux-hardware.org/?probe=95ef83d6fd) | Oct 08, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [69383bf7da](https://linux-hardware.org/?probe=69383bf7da) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [81ece14527](https://linux-hardware.org/?probe=81ece14527) | Oct 08, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [c9d4efa819](https://linux-hardware.org/?probe=c9d4efa819) | Oct 07, 2023 |
| Apple         | MacBookPro12,1              | [50fc69b25f](https://linux-hardware.org/?probe=50fc69b25f) | Oct 06, 2023 |
| Valve         | Jupiter                     | [1323f200dd](https://linux-hardware.org/?probe=1323f200dd) | Oct 01, 2023 |
| Dell          | XPS 13 9380                 | [9c2ba935b9](https://linux-hardware.org/?probe=9c2ba935b9) | Sep 29, 2023 |
| Google        | Lindar                      | [f8f947a025](https://linux-hardware.org/?probe=f8f947a025) | Sep 28, 2023 |
| Google        | Lindar                      | [9ddbc21f0d](https://linux-hardware.org/?probe=9ddbc21f0d) | Sep 28, 2023 |
| Dell          | Latitude 5480               | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| Google        | Droid                       | [fa5f650f3a](https://linux-hardware.org/?probe=fa5f650f3a) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0YE0... | [20c9a90aca](https://linux-hardware.org/?probe=20c9a90aca) | Sep 24, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [72c4bdf239](https://linux-hardware.org/?probe=72c4bdf239) | Sep 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [fd9d93d90d](https://linux-hardware.org/?probe=fd9d93d90d) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [72fe934225](https://linux-hardware.org/?probe=72fe934225) | Sep 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0918609cf3](https://linux-hardware.org/?probe=0918609cf3) | Sep 13, 2023 |
| Valve         | Jupiter                     | [f6467570d4](https://linux-hardware.org/?probe=f6467570d4) | Sep 11, 2023 |
| ASUSTek       | S550CB                      | [dbf2770e09](https://linux-hardware.org/?probe=dbf2770e09) | Sep 10, 2023 |
| ASUSTek       | Strix GL504GM_GL504GM       | [3297d8f0aa](https://linux-hardware.org/?probe=3297d8f0aa) | Sep 10, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HH0... | [94c99c8274](https://linux-hardware.org/?probe=94c99c8274) | Sep 06, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| ASUSTek       | N73SV                       | [1e0b979775](https://linux-hardware.org/?probe=1e0b979775) | Sep 04, 2023 |
| HP            | Pavilion dv9500             | [653fbbb509](https://linux-hardware.org/?probe=653fbbb509) | Sep 04, 2023 |
| HP            | ProBook 650 G2              | [64026d5e6d](https://linux-hardware.org/?probe=64026d5e6d) | Sep 04, 2023 |
| Dell          | XPS 15 7590                 | [b423b914f7](https://linux-hardware.org/?probe=b423b914f7) | Aug 30, 2023 |
| Acer          | Aspire A315-58              | [75ef08524c](https://linux-hardware.org/?probe=75ef08524c) | Aug 30, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [3f7455be45](https://linux-hardware.org/?probe=3f7455be45) | Aug 27, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| Lenovo        | ThinkPad T460s 20F9003VM... | [e6e076d380](https://linux-hardware.org/?probe=e6e076d380) | Aug 23, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [d68939adcf](https://linux-hardware.org/?probe=d68939adcf) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| HP            | Pavilion dv9500             | [d5cc7639c3](https://linux-hardware.org/?probe=d5cc7639c3) | Aug 21, 2023 |
| Dell          | Latitude E6410              | [5ae66b0d4a](https://linux-hardware.org/?probe=5ae66b0d4a) | Aug 18, 2023 |
| Dell          | Latitude 5540               | [d1f00897b3](https://linux-hardware.org/?probe=d1f00897b3) | Aug 18, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | [0c47627604](https://linux-hardware.org/?probe=0c47627604) | Aug 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [2cd51b6fce](https://linux-hardware.org/?probe=2cd51b6fce) | Aug 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b326fccb63](https://linux-hardware.org/?probe=b326fccb63) | Aug 16, 2023 |
| Valve         | Jupiter                     | [508611b16c](https://linux-hardware.org/?probe=508611b16c) | Aug 16, 2023 |
| Apple         | MacBookPro12,1              | [12e0dbd72c](https://linux-hardware.org/?probe=12e0dbd72c) | Aug 09, 2023 |
| Acer          | Swift SF114-32              | [3474fa639e](https://linux-hardware.org/?probe=3474fa639e) | Aug 08, 2023 |
| Dell          | G3 3590                     | [56d5cdc390](https://linux-hardware.org/?probe=56d5cdc390) | Aug 04, 2023 |
| Sony          | SVF1521G1EW                 | [b46b664a9e](https://linux-hardware.org/?probe=b46b664a9e) | Aug 03, 2023 |
| ASUSTek       | K95VM                       | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| MSI           | Raider GE78HX 13VI          | [0b179ca997](https://linux-hardware.org/?probe=0b179ca997) | Jul 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS22905    | [f95fe4ced5](https://linux-hardware.org/?probe=f95fe4ced5) | Jul 28, 2023 |
| Dell          | XPS 13 9370                 | [8cf3728f9b](https://linux-hardware.org/?probe=8cf3728f9b) | Jul 25, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| Acer          | Aspire E5-553               | [1321d9a034](https://linux-hardware.org/?probe=1321d9a034) | Jul 21, 2023 |
| Acer          | Aspire E5-553               | [7ef01e963d](https://linux-hardware.org/?probe=7ef01e963d) | Jul 21, 2023 |
| Dell          | Precision 7530              | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [26a2238069](https://linux-hardware.org/?probe=26a2238069) | Jul 19, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [9672a393c9](https://linux-hardware.org/?probe=9672a393c9) | Jul 19, 2023 |
| Dell          | XPS 13 9370                 | [ea47e53a45](https://linux-hardware.org/?probe=ea47e53a45) | Jul 18, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [14defb538e](https://linux-hardware.org/?probe=14defb538e) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | [f440759b5b](https://linux-hardware.org/?probe=f440759b5b) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | [2e7199aa1a](https://linux-hardware.org/?probe=2e7199aa1a) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | [9a14a53c9c](https://linux-hardware.org/?probe=9a14a53c9c) | Jul 16, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [0c4b8e49f8](https://linux-hardware.org/?probe=0c4b8e49f8) | Jul 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [72af2d01c0](https://linux-hardware.org/?probe=72af2d01c0) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [e87ea192ea](https://linux-hardware.org/?probe=e87ea192ea) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [4e47f48ca8](https://linux-hardware.org/?probe=4e47f48ca8) | Jul 07, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [382fff8a04](https://linux-hardware.org/?probe=382fff8a04) | Jul 06, 2023 |
| Dell          | XPS 15 7590                 | [81a034858f](https://linux-hardware.org/?probe=81a034858f) | Jul 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [46e3ea33a3](https://linux-hardware.org/?probe=46e3ea33a3) | Jun 27, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L480 20LS002YMX    | [9c9702483c](https://linux-hardware.org/?probe=9c9702483c) | Jun 22, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [5314aeb7e0](https://linux-hardware.org/?probe=5314aeb7e0) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [fc06bc7209](https://linux-hardware.org/?probe=fc06bc7209) | Jun 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [5bd2521f5c](https://linux-hardware.org/?probe=5bd2521f5c) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| Dell          | Inspiron 15-7568            | [4d0efefd7c](https://linux-hardware.org/?probe=4d0efefd7c) | Jun 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [2aaa4324d0](https://linux-hardware.org/?probe=2aaa4324d0) | Jun 12, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| Acer          | Aspire E5-553               | [76ca69b8cc](https://linux-hardware.org/?probe=76ca69b8cc) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | [3932ac5190](https://linux-hardware.org/?probe=3932ac5190) | Jun 07, 2023 |
| Razer         | Blade 15 Advanced Model ... | [8f55e469c8](https://linux-hardware.org/?probe=8f55e469c8) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [525601c31e](https://linux-hardware.org/?probe=525601c31e) | Jun 04, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | 1225B                       | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [742ae62ba6](https://linux-hardware.org/?probe=742ae62ba6) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [c507b25480](https://linux-hardware.org/?probe=c507b25480) | May 30, 2023 |
| Dell          | Inspiron 15-7568            | [227930e25d](https://linux-hardware.org/?probe=227930e25d) | May 29, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [4147fc8cb7](https://linux-hardware.org/?probe=4147fc8cb7) | May 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [d9295f37bc](https://linux-hardware.org/?probe=d9295f37bc) | May 27, 2023 |
| Acer          | Aspire E5-553               | [3740264eb0](https://linux-hardware.org/?probe=3740264eb0) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [97687a73c3](https://linux-hardware.org/?probe=97687a73c3) | May 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0037MD     | [f1a58d3a7f](https://linux-hardware.org/?probe=f1a58d3a7f) | May 11, 2023 |
| Acer          | Aspire 5810T                | [d21ea25d7a](https://linux-hardware.org/?probe=d21ea25d7a) | May 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS0AP00    | [f628b12917](https://linux-hardware.org/?probe=f628b12917) | May 10, 2023 |
| Acer          | Aspire 5810T                | [d4b401ef3f](https://linux-hardware.org/?probe=d4b401ef3f) | May 06, 2023 |
| HP            | ProBook 6570b               | [d240b443c4](https://linux-hardware.org/?probe=d240b443c4) | May 06, 2023 |
| Acer          | Aspire 5810T                | [ecdd99c704](https://linux-hardware.org/?probe=ecdd99c704) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6cb7429ec6](https://linux-hardware.org/?probe=6cb7429ec6) | May 02, 2023 |
| Acer          | Aspire E5-553               | [ff448e32c3](https://linux-hardware.org/?probe=ff448e32c3) | Apr 29, 2023 |
| HUAWEI        | BOD-WXX9                    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X250 20CLA003TA    | [ea8109c2a7](https://linux-hardware.org/?probe=ea8109c2a7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| Lenovo        | ThinkPad T520 4243W4L       | [bcdd9e5f74](https://linux-hardware.org/?probe=bcdd9e5f74) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [0ec2388253](https://linux-hardware.org/?probe=0ec2388253) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [a196246f09](https://linux-hardware.org/?probe=a196246f09) | Apr 17, 2023 |
| Lenovo        | ThinkPad W541 20EGS03800    | [4be9d98954](https://linux-hardware.org/?probe=4be9d98954) | Apr 11, 2023 |
| eMachines     | E725                        | [758d0c86b2](https://linux-hardware.org/?probe=758d0c86b2) | Apr 06, 2023 |
| Acer          | Aspire E5-771               | [2ef87c5f77](https://linux-hardware.org/?probe=2ef87c5f77) | Apr 06, 2023 |
| Acer          | Swift SF314-59              | [d12cbc4044](https://linux-hardware.org/?probe=d12cbc4044) | Apr 06, 2023 |
| HUAWEI        | BOD-WXX9                    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| Dell          | Latitude 7480               | [f1ca485181](https://linux-hardware.org/?probe=f1ca485181) | Apr 02, 2023 |
| Lenovo        | G505 20240                  | [d873632b2b](https://linux-hardware.org/?probe=d873632b2b) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420 4236W1K       | [e093aace6e](https://linux-hardware.org/?probe=e093aace6e) | Mar 27, 2023 |
| Lenovo        | ThinkPad L530 24812SG       | [163d4e376e](https://linux-hardware.org/?probe=163d4e376e) | Mar 26, 2023 |
| MSI           | GT72 2QE                    | [438f4cb9d9](https://linux-hardware.org/?probe=438f4cb9d9) | Mar 26, 2023 |
| Acer          | Aspire E5-553               | [3d591cd190](https://linux-hardware.org/?probe=3d591cd190) | Mar 21, 2023 |
| Acer          | Extensa 7620                | [59bb9967c2](https://linux-hardware.org/?probe=59bb9967c2) | Mar 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [ccfa4fb30e](https://linux-hardware.org/?probe=ccfa4fb30e) | Mar 17, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | [4012d2fb1f](https://linux-hardware.org/?probe=4012d2fb1f) | Mar 16, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | [f2f8796262](https://linux-hardware.org/?probe=f2f8796262) | Mar 16, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0AF00    | [fe02ac3290](https://linux-hardware.org/?probe=fe02ac3290) | Mar 15, 2023 |
| Samsung       | NP770                       | [ab2677e28e](https://linux-hardware.org/?probe=ab2677e28e) | Mar 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| HP            | OMEN by Laptop              | [a3a369de93](https://linux-hardware.org/?probe=a3a369de93) | Mar 08, 2023 |
| Apple         | MacBookPro9,2               | [8995f4a3b0](https://linux-hardware.org/?probe=8995f4a3b0) | Mar 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | [38623506fd](https://linux-hardware.org/?probe=38623506fd) | Mar 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [05e7af9004](https://linux-hardware.org/?probe=05e7af9004) | Mar 02, 2023 |
| HP            | Pavilion dv7                | [3d8c3db030](https://linux-hardware.org/?probe=3d8c3db030) | Feb 26, 2023 |
| HP            | EliteBook 840 G6            | [ea6777bf2d](https://linux-hardware.org/?probe=ea6777bf2d) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [7380033a44](https://linux-hardware.org/?probe=7380033a44) | Feb 22, 2023 |
| HP            | Pavilion dv7                | [5fd9a2f9c5](https://linux-hardware.org/?probe=5fd9a2f9c5) | Feb 17, 2023 |
| HP            | Notebook                    | [682935bcda](https://linux-hardware.org/?probe=682935bcda) | Feb 16, 2023 |
| HP            | Notebook                    | [1ea98ae976](https://linux-hardware.org/?probe=1ea98ae976) | Feb 16, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [aa3655a17e](https://linux-hardware.org/?probe=aa3655a17e) | Feb 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [36f57d56f8](https://linux-hardware.org/?probe=36f57d56f8) | Feb 15, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [92cbb2e876](https://linux-hardware.org/?probe=92cbb2e876) | Feb 11, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a55211363f](https://linux-hardware.org/?probe=a55211363f) | Feb 09, 2023 |
| HP            | Notebook                    | [eb0699bb89](https://linux-hardware.org/?probe=eb0699bb89) | Feb 07, 2023 |
| HP            | Pavilion g7                 | [e64e08ebd4](https://linux-hardware.org/?probe=e64e08ebd4) | Feb 05, 2023 |
| Lenovo        | ThinkPad L380 20M5S09Y00    | [5a7e90c12d](https://linux-hardware.org/?probe=5a7e90c12d) | Feb 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ab57658c86](https://linux-hardware.org/?probe=ab57658c86) | Jan 31, 2023 |
| Lenovo        | ThinkPad L380 20M5S09Y00    | [2326ffc032](https://linux-hardware.org/?probe=2326ffc032) | Jan 31, 2023 |
| HP            | Laptop 14-bp0xx             | [68d8a60823](https://linux-hardware.org/?probe=68d8a60823) | Jan 27, 2023 |
| Standard      | Unknown                     | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| HP            | ProBook 650 G1              | [f9882955cb](https://linux-hardware.org/?probe=f9882955cb) | Jan 24, 2023 |
| Lenovo        | ThinkPad W541 20EF0020MD    | [fca73ad2a9](https://linux-hardware.org/?probe=fca73ad2a9) | Jan 24, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [96a5ca6b92](https://linux-hardware.org/?probe=96a5ca6b92) | Jan 23, 2023 |
| System76      | Darter UltraThin            | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Google        | Phaser                      | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| Lenovo        | ThinkPad X230 2325AS7       | [71a521018d](https://linux-hardware.org/?probe=71a521018d) | Jan 19, 2023 |
| ASUSTek       | S301LA                      | [c45b4758ed](https://linux-hardware.org/?probe=c45b4758ed) | Jan 18, 2023 |
| Lenovo        | G505 20240                  | [ef2fdd351c](https://linux-hardware.org/?probe=ef2fdd351c) | Jan 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [138f888e23](https://linux-hardware.org/?probe=138f888e23) | Jan 15, 2023 |
| Acer          | Aspire 5810T                | [a39184ad9b](https://linux-hardware.org/?probe=a39184ad9b) | Jan 13, 2023 |
| Acer          | Aspire 5810T                | [ccc420a65a](https://linux-hardware.org/?probe=ccc420a65a) | Jan 13, 2023 |
| Acer          | Aspire A515-56              | [2f95543d62](https://linux-hardware.org/?probe=2f95543d62) | Jan 11, 2023 |
| Acer          | Aspire E5-553               | [e68c76cbee](https://linux-hardware.org/?probe=e68c76cbee) | Jan 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [bc17e3a0f4](https://linux-hardware.org/?probe=bc17e3a0f4) | Jan 04, 2023 |
| Medion        | P7621                       | [6ce2ef1abc](https://linux-hardware.org/?probe=6ce2ef1abc) | Jan 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | [65c34944ec](https://linux-hardware.org/?probe=65c34944ec) | Jan 03, 2023 |
| Notebook      | P17SM                       | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Apple         | MacBookPro10,2              | [a01c19a34d](https://linux-hardware.org/?probe=a01c19a34d) | Dec 29, 2022 |
| GPD           | WIN2                        | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| ASUSTek       | X75A1                       | [5a5ee8db71](https://linux-hardware.org/?probe=5a5ee8db71) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [196d570869](https://linux-hardware.org/?probe=196d570869) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| Valve         | Jupiter                     | [5c07d82410](https://linux-hardware.org/?probe=5c07d82410) | Dec 23, 2022 |
| MSI           | GP65 Leopard 9SE            | [7b980fbd8f](https://linux-hardware.org/?probe=7b980fbd8f) | Dec 21, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [97d8552a67](https://linux-hardware.org/?probe=97d8552a67) | Dec 21, 2022 |
| Medion        | P7621                       | [eced009b2a](https://linux-hardware.org/?probe=eced009b2a) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [95aca2679a](https://linux-hardware.org/?probe=95aca2679a) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [be36edb132](https://linux-hardware.org/?probe=be36edb132) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [491b8d0b8f](https://linux-hardware.org/?probe=491b8d0b8f) | Dec 11, 2022 |
| Lenovo        | ThinkPad Z61m 94503HG       | [4131ed9268](https://linux-hardware.org/?probe=4131ed9268) | Dec 11, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [4686ea3469](https://linux-hardware.org/?probe=4686ea3469) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Dell          | XPS 13 9370                 | [e5291ae74e](https://linux-hardware.org/?probe=e5291ae74e) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7a802a74b7](https://linux-hardware.org/?probe=7a802a74b7) | Dec 04, 2022 |
| Acer          | Aspire E5-575G              | [dddc2b5f29](https://linux-hardware.org/?probe=dddc2b5f29) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Standard      | Unknown                     | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [687d4d78a4](https://linux-hardware.org/?probe=687d4d78a4) | Nov 29, 2022 |
| Dell          | Inspiron 15 3520            | [7c53fcc73b](https://linux-hardware.org/?probe=7c53fcc73b) | Nov 24, 2022 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [dee6d2a740](https://linux-hardware.org/?probe=dee6d2a740) | Nov 23, 2022 |
| Lenovo        | ThinkPad T460 20FN004CMD    | [1b7140151d](https://linux-hardware.org/?probe=1b7140151d) | Nov 20, 2022 |
| Acer          | Aspire 5810T                | [2c671f2494](https://linux-hardware.org/?probe=2c671f2494) | Nov 18, 2022 |
| Timi          | TM1607                      | [a93d1611bb](https://linux-hardware.org/?probe=a93d1611bb) | Nov 18, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [7352c1f1ed](https://linux-hardware.org/?probe=7352c1f1ed) | Nov 17, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6af7c2ad85](https://linux-hardware.org/?probe=6af7c2ad85) | Nov 15, 2022 |
| Acer          | Aspire E5-553               | [4c031f5f3b](https://linux-hardware.org/?probe=4c031f5f3b) | Nov 15, 2022 |
| Apple         | MacBookPro5,5               | [a35952fc68](https://linux-hardware.org/?probe=a35952fc68) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [270045ffa3](https://linux-hardware.org/?probe=270045ffa3) | Nov 11, 2022 |
| Komplett      | LAPQC71B                    | [b5ee8960c6](https://linux-hardware.org/?probe=b5ee8960c6) | Nov 11, 2022 |
| MSI           | GV62 8RC                    | [859227b2bb](https://linux-hardware.org/?probe=859227b2bb) | Nov 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [a62bf9ed3b](https://linux-hardware.org/?probe=a62bf9ed3b) | Nov 08, 2022 |
| HP            | Notebook                    | [0868a7d110](https://linux-hardware.org/?probe=0868a7d110) | Nov 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS3CF0... | [2c52a84e7c](https://linux-hardware.org/?probe=2c52a84e7c) | Nov 06, 2022 |
| ASUSTek       | N55SF                       | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | Latitude 5280               | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Unknown       | Unknown                     | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [e21d202e50](https://linux-hardware.org/?probe=e21d202e50) | Oct 22, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| Acer          | Aspire E5-551               | [9d281c015c](https://linux-hardware.org/?probe=9d281c015c) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | [6c351b94ff](https://linux-hardware.org/?probe=6c351b94ff) | Oct 11, 2022 |
| Dell          | XPS 13 9370                 | [17f73f4f28](https://linux-hardware.org/?probe=17f73f4f28) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| Lenovo        | Z50-75 80EC                 | [e3f9c7a4f1](https://linux-hardware.org/?probe=e3f9c7a4f1) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| Unknown       | Unknown                     | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | XPS 15 9570                 | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | [87c9436154](https://linux-hardware.org/?probe=87c9436154) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d3047f6963](https://linux-hardware.org/?probe=d3047f6963) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | [6ea648bc51](https://linux-hardware.org/?probe=6ea648bc51) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| Acer          | Aspire E5-553               | [5db637f345](https://linux-hardware.org/?probe=5db637f345) | Sep 19, 2022 |
| Acer          | Aspire E5-553               | [f0bbe89fe8](https://linux-hardware.org/?probe=f0bbe89fe8) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Dell          | XPS 13 9360                 | [af2f12093c](https://linux-hardware.org/?probe=af2f12093c) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| Valve         | Jupiter                     | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [865455aae7](https://linux-hardware.org/?probe=865455aae7) | Sep 05, 2022 |
| Acer          | Aspire E5-553               | [de2cfb43d7](https://linux-hardware.org/?probe=de2cfb43d7) | Sep 03, 2022 |
| Apple         | MacBookPro9,2               | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| HP            | ProBook 6550b               | [662065bfe2](https://linux-hardware.org/?probe=662065bfe2) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Lenovo        | B50-50 80S2                 | [45f5a72c59](https://linux-hardware.org/?probe=45f5a72c59) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Dell          | XPS 13 9370                 | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [1d97fa15fb](https://linux-hardware.org/?probe=1d97fa15fb) | Aug 08, 2022 |
| Acer          | Aspire M3-581TG             | [5c73e4c75b](https://linux-hardware.org/?probe=5c73e4c75b) | Aug 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [41189cd175](https://linux-hardware.org/?probe=41189cd175) | Aug 03, 2022 |
| Notebook      | NS50_70MU                   | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [e6ccfdf23c](https://linux-hardware.org/?probe=e6ccfdf23c) | Jul 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [83e5824a05](https://linux-hardware.org/?probe=83e5824a05) | Jul 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| HP            | Laptop 15-gw0xxx            | [a7f15d1696](https://linux-hardware.org/?probe=a7f15d1696) | Jul 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [4d9388058d](https://linux-hardware.org/?probe=4d9388058d) | Jul 12, 2022 |
| Acer          | Aspire E5-553               | [e7cdc97a90](https://linux-hardware.org/?probe=e7cdc97a90) | Jul 11, 2022 |
| Dell          | Latitude 7490               | [b456bca385](https://linux-hardware.org/?probe=b456bca385) | Jul 06, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [0e23c1fc2b](https://linux-hardware.org/?probe=0e23c1fc2b) | Jul 02, 2022 |
| Lenovo        | ThinkPad T530 24295L4       | [1bdf25550e](https://linux-hardware.org/?probe=1bdf25550e) | Jun 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6dfa236f76](https://linux-hardware.org/?probe=6dfa236f76) | Jun 18, 2022 |
| Notebook      | PB50_70DFx,DDx              | [21206dd6bf](https://linux-hardware.org/?probe=21206dd6bf) | Jun 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [527587d2b9](https://linux-hardware.org/?probe=527587d2b9) | Jun 14, 2022 |
| Lenovo        | ThinkPad T550 20CK003HMD    | [ea8155f580](https://linux-hardware.org/?probe=ea8155f580) | Jun 14, 2022 |
| Dell          | Latitude E7440              | [6bbb1944af](https://linux-hardware.org/?probe=6bbb1944af) | Jun 12, 2022 |
| Google        | Babytiger                   | [18f6f97122](https://linux-hardware.org/?probe=18f6f97122) | Jun 12, 2022 |
| HP            | EliteBook 2560p             | [5f1e0dfee7](https://linux-hardware.org/?probe=5f1e0dfee7) | Jun 09, 2022 |
| HP            | EliteBook 8570p             | [bd545aec1b](https://linux-hardware.org/?probe=bd545aec1b) | Jun 09, 2022 |
| Acer          | Aspire ES1-523              | [242fc61e3a](https://linux-hardware.org/?probe=242fc61e3a) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | [b9a30cba65](https://linux-hardware.org/?probe=b9a30cba65) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | [3c14a5bf10](https://linux-hardware.org/?probe=3c14a5bf10) | Jun 08, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | V330-14ARR 81B1             | [dad2acbf49](https://linux-hardware.org/?probe=dad2acbf49) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| HP            | ProBook 6450b               | [8c35a4c278](https://linux-hardware.org/?probe=8c35a4c278) | May 26, 2022 |
| Dell          | Latitude E7440              | [975715a96b](https://linux-hardware.org/?probe=975715a96b) | May 26, 2022 |
| HP            | ProBook 6450b               | [863987eb13](https://linux-hardware.org/?probe=863987eb13) | May 26, 2022 |
| HP            | ProBook 650 G1              | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [62486fe8d6](https://linux-hardware.org/?probe=62486fe8d6) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f0f481f187](https://linux-hardware.org/?probe=f0f481f187) | May 21, 2022 |
| SLIMBOOK      | PROX14-10                   | [b0d5e9b290](https://linux-hardware.org/?probe=b0d5e9b290) | May 19, 2022 |
| Dell          | XPS 13 9370                 | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [6efbcdabfc](https://linux-hardware.org/?probe=6efbcdabfc) | May 17, 2022 |
| Lenovo        | ThinkPad T480 20L6S14Y01    | [d3f3fff089](https://linux-hardware.org/?probe=d3f3fff089) | May 16, 2022 |
| Dell          | Precision 5750              | [11e888b7d9](https://linux-hardware.org/?probe=11e888b7d9) | May 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [591d3fa922](https://linux-hardware.org/?probe=591d3fa922) | May 07, 2022 |
| Packard Be... | EasyNote TE69BM             | [ed538d5b79](https://linux-hardware.org/?probe=ed538d5b79) | May 07, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [ac5b1123ad](https://linux-hardware.org/?probe=ac5b1123ad) | Apr 30, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [8694f28b60](https://linux-hardware.org/?probe=8694f28b60) | Apr 25, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [0cd6fe25ec](https://linux-hardware.org/?probe=0cd6fe25ec) | Apr 22, 2022 |
| Acer          | Aspire E5-553               | [1c736596fa](https://linux-hardware.org/?probe=1c736596fa) | Apr 21, 2022 |
| Lenovo        | B575e 36852EG               | [8f5e5f427a](https://linux-hardware.org/?probe=8f5e5f427a) | Apr 18, 2022 |
| Lenovo        | B575e 36852EG               | [4731516b58](https://linux-hardware.org/?probe=4731516b58) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440 20B7S1EV00    | [b035e7ae3e](https://linux-hardware.org/?probe=b035e7ae3e) | Apr 16, 2022 |
| HP            | EliteBook 820 G3            | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| MSI           | GF63 Thin 10SC              | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Acer          | Aspire V5-573G              | [2b608bcde8](https://linux-hardware.org/?probe=2b608bcde8) | Apr 04, 2022 |
| Lenovo        | ThinkPad X390 20Q0002LMX    | [22aaabe433](https://linux-hardware.org/?probe=22aaabe433) | Apr 03, 2022 |
| HP            | Laptop 14-dk1xxx            | [0ba5fd01fa](https://linux-hardware.org/?probe=0ba5fd01fa) | Mar 30, 2022 |
| HP            | Laptop 15-bw0xx             | [b9a21aea35](https://linux-hardware.org/?probe=b9a21aea35) | Mar 29, 2022 |
| Lenovo        | E31-80 80MX                 | [8dc93e34e9](https://linux-hardware.org/?probe=8dc93e34e9) | Mar 25, 2022 |
| HP            | Pavilion Notebook           | [3bf42ed5a6](https://linux-hardware.org/?probe=3bf42ed5a6) | Mar 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [72da14a2b2](https://linux-hardware.org/?probe=72da14a2b2) | Mar 23, 2022 |
| MSI           | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| Apple         | MacBookPro11,5              | [abc4597fe1](https://linux-hardware.org/?probe=abc4597fe1) | Mar 18, 2022 |
| Notebook      | P65xHP                      | [3222aab43a](https://linux-hardware.org/?probe=3222aab43a) | Mar 16, 2022 |
| Acer          | Aspire 3830T                | [bad3a5c2d7](https://linux-hardware.org/?probe=bad3a5c2d7) | Mar 15, 2022 |
| HP            | EliteBook 850 G5            | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Latitude E6410              | [d4fa7879a4](https://linux-hardware.org/?probe=d4fa7879a4) | Mar 09, 2022 |
| Dell          | Precision M4800             | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| Dell          | Latitude E6410              | [6748e5a7aa](https://linux-hardware.org/?probe=6748e5a7aa) | Feb 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [30879c05cc](https://linux-hardware.org/?probe=30879c05cc) | Feb 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [505e1dc8cc](https://linux-hardware.org/?probe=505e1dc8cc) | Feb 21, 2022 |
| Lenovo        | ThinkPad L530 24812SG       | [6eb3e0ed53](https://linux-hardware.org/?probe=6eb3e0ed53) | Feb 19, 2022 |
| HP            | Pavilion g6                 | [3971fd709d](https://linux-hardware.org/?probe=3971fd709d) | Feb 13, 2022 |
| Acer          | Aspire E5-575               | [3e75911df8](https://linux-hardware.org/?probe=3e75911df8) | Feb 12, 2022 |
| Apple         | MacBookPro7,1               | [b059819620](https://linux-hardware.org/?probe=b059819620) | Feb 11, 2022 |
| Apple         | MacBookPro7,1               | [87f4740598](https://linux-hardware.org/?probe=87f4740598) | Feb 11, 2022 |
| Toshiba       | Satellite L40               | [ba6d18935b](https://linux-hardware.org/?probe=ba6d18935b) | Feb 08, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [23c6243856](https://linux-hardware.org/?probe=23c6243856) | Feb 05, 2022 |
| Medion        | P7612                       | [e1c076ee06](https://linux-hardware.org/?probe=e1c076ee06) | Feb 03, 2022 |
| HP            | Compaq Presario CQ71        | [436407f045](https://linux-hardware.org/?probe=436407f045) | Feb 01, 2022 |
| Lenovo        | B50-50 80S2                 | [7602963c65](https://linux-hardware.org/?probe=7602963c65) | Feb 01, 2022 |
| Dell          | Latitude E6540              | [fe6720f0de](https://linux-hardware.org/?probe=fe6720f0de) | Jan 30, 2022 |
| Dell          | Latitude E6540              | [7c972de545](https://linux-hardware.org/?probe=7c972de545) | Jan 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [478d5281bd](https://linux-hardware.org/?probe=478d5281bd) | Jan 29, 2022 |
| HP            | Pavilion dv7                | [e6ec9b5f6a](https://linux-hardware.org/?probe=e6ec9b5f6a) | Jan 26, 2022 |
| Medion        | P7612                       | [50be4d531e](https://linux-hardware.org/?probe=50be4d531e) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| HP            | EliteBook 840 G3            | [82cce77f87](https://linux-hardware.org/?probe=82cce77f87) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| DukaPC        | Notebook                    | [21b4827b4b](https://linux-hardware.org/?probe=21b4827b4b) | Jan 21, 2022 |
| Acer          | Aspire F5-572G              | [221a91f679](https://linux-hardware.org/?probe=221a91f679) | Jan 19, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [cc39f1fd96](https://linux-hardware.org/?probe=cc39f1fd96) | Jan 18, 2022 |
| IBM           | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [4ebb815948](https://linux-hardware.org/?probe=4ebb815948) | Jan 15, 2022 |
| HP            | Pavilion g7                 | [6efd331acf](https://linux-hardware.org/?probe=6efd331acf) | Jan 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [4cefa23802](https://linux-hardware.org/?probe=4cefa23802) | Jan 14, 2022 |
| Acer          | Aspire E5-553               | [149c0538ca](https://linux-hardware.org/?probe=149c0538ca) | Jan 13, 2022 |
| Lenovo        | M30-70 80H8                 | [2f61d772a4](https://linux-hardware.org/?probe=2f61d772a4) | Jan 12, 2022 |
| Lenovo        | Y50-70 20378                | [ab93bc517a](https://linux-hardware.org/?probe=ab93bc517a) | Jan 12, 2022 |
| Razer         | Blade                       | [afad6aaa95](https://linux-hardware.org/?probe=afad6aaa95) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1f327abc43](https://linux-hardware.org/?probe=1f327abc43) | Jan 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [53a3989606](https://linux-hardware.org/?probe=53a3989606) | Jan 03, 2022 |
| Acer          | Aspire V5-573G              | [a7e3940936](https://linux-hardware.org/?probe=a7e3940936) | Jan 02, 2022 |
| Dell          | Inspiron 7720               | [4e1ebc00ff](https://linux-hardware.org/?probe=4e1ebc00ff) | Jan 02, 2022 |
| Apple         | MacBookAir7,2               | [6246bb8ef6](https://linux-hardware.org/?probe=6246bb8ef6) | Dec 31, 2021 |
| Lenovo        | V330-14ARR 81B1             | [290d6b4ad5](https://linux-hardware.org/?probe=290d6b4ad5) | Dec 29, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [13f35d1d12](https://linux-hardware.org/?probe=13f35d1d12) | Dec 26, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [369d18645c](https://linux-hardware.org/?probe=369d18645c) | Dec 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [e68ec90909](https://linux-hardware.org/?probe=e68ec90909) | Dec 24, 2021 |
| Medion        | P6630                       | [de245dfdb6](https://linux-hardware.org/?probe=de245dfdb6) | Dec 23, 2021 |
| Notebook      | N24_25JU                    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| Quanta        | MW1/HW1                     | [06bcb3603d](https://linux-hardware.org/?probe=06bcb3603d) | Dec 17, 2021 |
| ASUSTek       | K53SV                       | [be7844ea44](https://linux-hardware.org/?probe=be7844ea44) | Dec 17, 2021 |
| Lenovo        | ThinkPad T460s 20FAS05Q0... | [3a4b9beb1d](https://linux-hardware.org/?probe=3a4b9beb1d) | Dec 12, 2021 |
| Toshiba       | Satellite P850              | [bfc37f531a](https://linux-hardware.org/?probe=bfc37f531a) | Dec 11, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [e7144e5f86](https://linux-hardware.org/?probe=e7144e5f86) | Dec 09, 2021 |
| Fujitsu Si... | LIFEBOOK E8420              | [7ff3493cfe](https://linux-hardware.org/?probe=7ff3493cfe) | Dec 08, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| DukaPC        | Notebook                    | [cfb399153a](https://linux-hardware.org/?probe=cfb399153a) | Dec 01, 2021 |
| Razer         | Blade Stealth               | [54acf9844b](https://linux-hardware.org/?probe=54acf9844b) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [c224ffa45a](https://linux-hardware.org/?probe=c224ffa45a) | Nov 23, 2021 |
| Toshiba       | Satellite U300              | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| Dell          | Inspiron 7572               | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| HUAWEI        | KLVL-WXX9                   | [c80aeaf7b0](https://linux-hardware.org/?probe=c80aeaf7b0) | Nov 17, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [52eef25506](https://linux-hardware.org/?probe=52eef25506) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [7252f23e5f](https://linux-hardware.org/?probe=7252f23e5f) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [1a20afde4b](https://linux-hardware.org/?probe=1a20afde4b) | Nov 15, 2021 |
| Acer          | Aspire 5810T                | [c41d1671bc](https://linux-hardware.org/?probe=c41d1671bc) | Nov 14, 2021 |
| Lenovo        | ThinkPad R61 8935W7T        | [bef030b1ef](https://linux-hardware.org/?probe=bef030b1ef) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [e03bf03f1d](https://linux-hardware.org/?probe=e03bf03f1d) | Nov 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [1def6bd5d8](https://linux-hardware.org/?probe=1def6bd5d8) | Nov 10, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d2a33ad9d9](https://linux-hardware.org/?probe=d2a33ad9d9) | Nov 07, 2021 |
| HP            | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Apple         | MacBookPro14,1              | [68ebc1af79](https://linux-hardware.org/?probe=68ebc1af79) | Oct 28, 2021 |
| Lenovo        | ThinkPad T430s 23561R0      | [bef1593d06](https://linux-hardware.org/?probe=bef1593d06) | Oct 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [14d159c564](https://linux-hardware.org/?probe=14d159c564) | Oct 20, 2021 |
| Unknown       | Unknown                     | [a6e5e7b6ef](https://linux-hardware.org/?probe=a6e5e7b6ef) | Oct 18, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [a7fa6a8110](https://linux-hardware.org/?probe=a7fa6a8110) | Oct 14, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [df32df0b62](https://linux-hardware.org/?probe=df32df0b62) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [c7239a1379](https://linux-hardware.org/?probe=c7239a1379) | Oct 13, 2021 |
| Toshiba       | Satellite P55W-C            | [f16be2ec1b](https://linux-hardware.org/?probe=f16be2ec1b) | Oct 13, 2021 |
| HP            | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Acer          | Aspire A315-41              | [3d5d3ddf84](https://linux-hardware.org/?probe=3d5d3ddf84) | Oct 09, 2021 |
| Lenovo        | ThinkPad X201T 3113CC7      | [47f63d40d5](https://linux-hardware.org/?probe=47f63d40d5) | Oct 09, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [93c695e5ba](https://linux-hardware.org/?probe=93c695e5ba) | Oct 08, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | [85a242883c](https://linux-hardware.org/?probe=85a242883c) | Oct 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [56ce2c44cb](https://linux-hardware.org/?probe=56ce2c44cb) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [4d0eb4ccf2](https://linux-hardware.org/?probe=4d0eb4ccf2) | Oct 04, 2021 |
| Lenovo        | V330-14ARR 81B1             | [c8a0e5de69](https://linux-hardware.org/?probe=c8a0e5de69) | Oct 04, 2021 |
| HUAWEI        | EUL-WX9                     | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| Lenovo        | ThinkPad X260 20F5S31G00    | [575dd64064](https://linux-hardware.org/?probe=575dd64064) | Oct 01, 2021 |
| HP            | Pavilion dv7                | [31b035faec](https://linux-hardware.org/?probe=31b035faec) | Sep 28, 2021 |
| Acer          | Aspire 5810T                | [be3f4d5a01](https://linux-hardware.org/?probe=be3f4d5a01) | Sep 26, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [edfae5b796](https://linux-hardware.org/?probe=edfae5b796) | Sep 25, 2021 |
| HUAWEI        | MACHC-WAX9                  | [e2fc9d2585](https://linux-hardware.org/?probe=e2fc9d2585) | Sep 23, 2021 |
| Dell          | XPS 13 9370                 | [5df047615c](https://linux-hardware.org/?probe=5df047615c) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | [d7ccece3d4](https://linux-hardware.org/?probe=d7ccece3d4) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | [466841a201](https://linux-hardware.org/?probe=466841a201) | Sep 22, 2021 |
| HP            | ZBook 15                    | [206882306c](https://linux-hardware.org/?probe=206882306c) | Sep 20, 2021 |
| Lenovo        | V130-15IKB 81HN             | [f427b869d9](https://linux-hardware.org/?probe=f427b869d9) | Sep 17, 2021 |
| Lenovo        | ThinkPad X220 4291WAY       | [ca0ab89977](https://linux-hardware.org/?probe=ca0ab89977) | Sep 16, 2021 |
| Lenovo        | ThinkPad W541 20EFS01B09    | [8dd2c7497e](https://linux-hardware.org/?probe=8dd2c7497e) | Sep 13, 2021 |
| Dell          | Inspiron 3583               | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| HP            | Pavilion dv7                | [2fd3b811f6](https://linux-hardware.org/?probe=2fd3b811f6) | Sep 12, 2021 |
| Dell          | XPS 15 9510                 | [1b80533734](https://linux-hardware.org/?probe=1b80533734) | Sep 11, 2021 |
| Dell          | XPS 15 9510                 | [4befd2306c](https://linux-hardware.org/?probe=4befd2306c) | Sep 11, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5cf3ed1411](https://linux-hardware.org/?probe=5cf3ed1411) | Aug 31, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | [70585e2360](https://linux-hardware.org/?probe=70585e2360) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [9c0457479f](https://linux-hardware.org/?probe=9c0457479f) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [23b7937411](https://linux-hardware.org/?probe=23b7937411) | Aug 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [9382443dc7](https://linux-hardware.org/?probe=9382443dc7) | Aug 27, 2021 |
| Google        | Relm                        | [12475037ed](https://linux-hardware.org/?probe=12475037ed) | Aug 27, 2021 |
| Google        | Relm                        | [36e7a1d7a1](https://linux-hardware.org/?probe=36e7a1d7a1) | Aug 26, 2021 |
| HP            | ProBook 650 G1              | [61f6289d2c](https://linux-hardware.org/?probe=61f6289d2c) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 2325AN3       | [d6b5ef49af](https://linux-hardware.org/?probe=d6b5ef49af) | Aug 24, 2021 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [900b0ce643](https://linux-hardware.org/?probe=900b0ce643) | Aug 24, 2021 |
| HP            | ZBook 15 G6                 | [93ec0ceb52](https://linux-hardware.org/?probe=93ec0ceb52) | Aug 23, 2021 |
| Lenovo        | ThinkPad E595 20NF001HMX    | [8e75269d33](https://linux-hardware.org/?probe=8e75269d33) | Aug 20, 2021 |
| Lenovo        | G550 2958                   | [5207c5584c](https://linux-hardware.org/?probe=5207c5584c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | [b7b363db20](https://linux-hardware.org/?probe=b7b363db20) | Aug 15, 2021 |
| HP            | ProBook 445 G7              | [e42e169a72](https://linux-hardware.org/?probe=e42e169a72) | Aug 15, 2021 |
| HP            | Notebook                    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| GPD           | P2 MAX                      | [78f79b2790](https://linux-hardware.org/?probe=78f79b2790) | Jul 31, 2021 |
| ASUSTek       | GL702VM                     | [bb9d228646](https://linux-hardware.org/?probe=bb9d228646) | Jul 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [a02dac8dff](https://linux-hardware.org/?probe=a02dac8dff) | Jul 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | [e52365f866](https://linux-hardware.org/?probe=e52365f866) | Jul 21, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | [704fb2e1d1](https://linux-hardware.org/?probe=704fb2e1d1) | Jul 21, 2021 |
| Dell          | Latitude 7370               | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | [7a03dbd869](https://linux-hardware.org/?probe=7a03dbd869) | Jul 17, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | [ce58f3f770](https://linux-hardware.org/?probe=ce58f3f770) | Jul 16, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [a56195f1f1](https://linux-hardware.org/?probe=a56195f1f1) | Jul 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [440841d04a](https://linux-hardware.org/?probe=440841d04a) | Jul 12, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [3b106f1da0](https://linux-hardware.org/?probe=3b106f1da0) | Jul 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [f8872c9e84](https://linux-hardware.org/?probe=f8872c9e84) | Jul 05, 2021 |
| AMI           | Cherry Trail CR             | [4e6f9ccc6c](https://linux-hardware.org/?probe=4e6f9ccc6c) | Jul 05, 2021 |
| DukaPC        | Notebook                    | [6d87054512](https://linux-hardware.org/?probe=6d87054512) | Jul 02, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| Timi          | TM1703                      | [bd3756811d](https://linux-hardware.org/?probe=bd3756811d) | Jun 26, 2021 |
| DukaPC        | Notebook                    | [c29d208cdf](https://linux-hardware.org/?probe=c29d208cdf) | Jun 24, 2021 |
| Lenovo        | ThinkPad T420 4236Y19       | [48927432b4](https://linux-hardware.org/?probe=48927432b4) | Jun 20, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d8ad69d368](https://linux-hardware.org/?probe=d8ad69d368) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0Y70... | [5e57af6782](https://linux-hardware.org/?probe=5e57af6782) | Jun 11, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | [fa5abfccf8](https://linux-hardware.org/?probe=fa5abfccf8) | Jun 04, 2021 |
| HP            | Compaq Presario CQ71        | [d4deb2b08d](https://linux-hardware.org/?probe=d4deb2b08d) | Jun 01, 2021 |
| Dell          | Latitude E6520              | [d1d0976880](https://linux-hardware.org/?probe=d1d0976880) | May 31, 2021 |
| Lenovo        | ThinkPad T400 647358G       | [b4f44d7932](https://linux-hardware.org/?probe=b4f44d7932) | May 29, 2021 |
| Toshiba       | Satellite C660              | [58d3740c30](https://linux-hardware.org/?probe=58d3740c30) | May 28, 2021 |
| Acer          | Aspire E5-553               | [70037bddcb](https://linux-hardware.org/?probe=70037bddcb) | May 27, 2021 |
| LAMINA        | T-1012B NORD                | [71e70e946a](https://linux-hardware.org/?probe=71e70e946a) | May 25, 2021 |
| LAMINA        | T-1012B NORD                | [9dc2932064](https://linux-hardware.org/?probe=9dc2932064) | May 24, 2021 |
| ASUSTek       | X553SA                      | [c470382d2a](https://linux-hardware.org/?probe=c470382d2a) | May 24, 2021 |
| ASUSTek       | X553SA                      | [31d6a914fd](https://linux-hardware.org/?probe=31d6a914fd) | May 24, 2021 |
| Acer          | Aspire E5-511               | [9edec55620](https://linux-hardware.org/?probe=9edec55620) | May 23, 2021 |
| Acer          | Aspire E5-511               | [e20c93a2c1](https://linux-hardware.org/?probe=e20c93a2c1) | May 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [a9e4c7793b](https://linux-hardware.org/?probe=a9e4c7793b) | May 18, 2021 |
| eMachines     | E725                        | [329f8f580e](https://linux-hardware.org/?probe=329f8f580e) | May 14, 2021 |
| ASUSTek       | K95VM                       | [58d4ed3c2b](https://linux-hardware.org/?probe=58d4ed3c2b) | May 10, 2021 |
| HP            | 15                          | [a13c097d59](https://linux-hardware.org/?probe=a13c097d59) | May 09, 2021 |
| HP            | 15                          | [c3cdcdab60](https://linux-hardware.org/?probe=c3cdcdab60) | May 09, 2021 |
| Alienware     | 17 R2                       | [a8470edc65](https://linux-hardware.org/?probe=a8470edc65) | May 06, 2021 |
| ASUSTek       | G74Sx                       | [73c1eaa647](https://linux-hardware.org/?probe=73c1eaa647) | Apr 29, 2021 |
| Lenovo        | ThinkPad T520 4243PC2       | [915d41f361](https://linux-hardware.org/?probe=915d41f361) | Apr 29, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [e259d34a4c](https://linux-hardware.org/?probe=e259d34a4c) | Apr 28, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | [e2f8b2beda](https://linux-hardware.org/?probe=e2f8b2beda) | Apr 25, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | [684f1471b1](https://linux-hardware.org/?probe=684f1471b1) | Apr 23, 2021 |
| Lenovo        | E31-80 80MX                 | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [bd14a696eb](https://linux-hardware.org/?probe=bd14a696eb) | Apr 20, 2021 |
| Lenovo        | ThinkPad T520 42434YG       | [8e0b4ee3a1](https://linux-hardware.org/?probe=8e0b4ee3a1) | Apr 17, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | [49e1959064](https://linux-hardware.org/?probe=49e1959064) | Apr 16, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | [b2853266e8](https://linux-hardware.org/?probe=b2853266e8) | Apr 15, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [4b127c0ba4](https://linux-hardware.org/?probe=4b127c0ba4) | Apr 11, 2021 |
| HP            | Laptop 15-da1xxx            | [a844e710cc](https://linux-hardware.org/?probe=a844e710cc) | Apr 09, 2021 |
| Lenovo        | ThinkPad T60 20076RG        | [aa3ea77acf](https://linux-hardware.org/?probe=aa3ea77acf) | Apr 08, 2021 |
| HP            | G72                         | [2ab4eb5fcd](https://linux-hardware.org/?probe=2ab4eb5fcd) | Apr 05, 2021 |
| ASUSTek       | K95VM                       | [81a01884d2](https://linux-hardware.org/?probe=81a01884d2) | Mar 24, 2021 |
| Lenovo        | ThinkPad W520 4284Y54       | [8d564e495b](https://linux-hardware.org/?probe=8d564e495b) | Mar 23, 2021 |
| Toshiba       | Satellite L350D             | [b083513b72](https://linux-hardware.org/?probe=b083513b72) | Mar 23, 2021 |
| Acer          | Aspire E5-553               | [0c21dc1b96](https://linux-hardware.org/?probe=0c21dc1b96) | Mar 19, 2021 |
| HP            | Pavilion dm1                | [438cf03315](https://linux-hardware.org/?probe=438cf03315) | Mar 18, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [7e7a4bc992](https://linux-hardware.org/?probe=7e7a4bc992) | Mar 18, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | [1b8a078a19](https://linux-hardware.org/?probe=1b8a078a19) | Mar 16, 2021 |
| HP            | EliteBook 830 G5            | [248eb896a0](https://linux-hardware.org/?probe=248eb896a0) | Mar 15, 2021 |
| HP            | Compaq Presario CQ60        | [e4613a6f75](https://linux-hardware.org/?probe=e4613a6f75) | Mar 15, 2021 |
| Dell          | Latitude E5250              | [22067e0909](https://linux-hardware.org/?probe=22067e0909) | Mar 13, 2021 |
| Dell          | Latitude E5250              | [df9d913f0f](https://linux-hardware.org/?probe=df9d913f0f) | Mar 13, 2021 |
| HP            | Pavilion dv9700             | [f55ec4dd18](https://linux-hardware.org/?probe=f55ec4dd18) | Mar 11, 2021 |
| Dell          | XPS 13 9370                 | [865e070587](https://linux-hardware.org/?probe=865e070587) | Mar 10, 2021 |
| Dell          | Latitude E5250              | [78f0a24d9a](https://linux-hardware.org/?probe=78f0a24d9a) | Mar 07, 2021 |
| Acer          | Aspire E5-575G              | [18240d24d8](https://linux-hardware.org/?probe=18240d24d8) | Mar 06, 2021 |
| Toshiba       | Satellite L350D             | [ef8a29af20](https://linux-hardware.org/?probe=ef8a29af20) | Mar 05, 2021 |
| Acer          | Aspire E5-553               | [74e6da0017](https://linux-hardware.org/?probe=74e6da0017) | Feb 27, 2021 |
| HP            | 630                         | [6803747e34](https://linux-hardware.org/?probe=6803747e34) | Feb 22, 2021 |
| HP            | 630                         | [8b04fe81aa](https://linux-hardware.org/?probe=8b04fe81aa) | Feb 22, 2021 |
| Lenovo        | ThinkPad T61 7661W1D        | [6db91fdd34](https://linux-hardware.org/?probe=6db91fdd34) | Feb 17, 2021 |
| Lenovo        | 3000 G530 444622G           | [3ef99e25df](https://linux-hardware.org/?probe=3ef99e25df) | Feb 16, 2021 |
| Lenovo        | ThinkPad X240 20AMA2AE00    | [2730f6215a](https://linux-hardware.org/?probe=2730f6215a) | Feb 12, 2021 |
| Dell          | XPS 13 9360                 | [564f71d6f3](https://linux-hardware.org/?probe=564f71d6f3) | Feb 10, 2021 |
| Acer          | Aspire E5-553               | [ab7532985d](https://linux-hardware.org/?probe=ab7532985d) | Feb 05, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [ed806c00b2](https://linux-hardware.org/?probe=ed806c00b2) | Feb 04, 2021 |
| HP            | EliteBook 2560p             | [f741035d0d](https://linux-hardware.org/?probe=f741035d0d) | Feb 02, 2021 |
| HP            | EliteBook 840 G5            | [19ef5f3adb](https://linux-hardware.org/?probe=19ef5f3adb) | Jan 29, 2021 |
| Dell          | Latitude E7440              | [ee2c17a895](https://linux-hardware.org/?probe=ee2c17a895) | Jan 26, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [964b7c1b1f](https://linux-hardware.org/?probe=964b7c1b1f) | Jan 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [82da77953a](https://linux-hardware.org/?probe=82da77953a) | Jan 19, 2021 |
| Dell          | Latitude 5500               | [d7e06bd87b](https://linux-hardware.org/?probe=d7e06bd87b) | Jan 18, 2021 |
| Dell          | Latitude 5500               | [f40a2d50bc](https://linux-hardware.org/?probe=f40a2d50bc) | Jan 16, 2021 |
| Quanta        | MW1/HW1                     | [ebab0a47f8](https://linux-hardware.org/?probe=ebab0a47f8) | Jan 16, 2021 |
| Lenovo        | ThinkPad P52 20M9001GMX     | [ffdee2c6e0](https://linux-hardware.org/?probe=ffdee2c6e0) | Jan 11, 2021 |
| Dell          | XPS 13 9300                 | [229b46a693](https://linux-hardware.org/?probe=229b46a693) | Jan 10, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [fa963386d8](https://linux-hardware.org/?probe=fa963386d8) | Jan 07, 2021 |
| Toshiba       | Satellite L40               | [bd26bbbe43](https://linux-hardware.org/?probe=bd26bbbe43) | Jan 06, 2021 |
| Lenovo        | G570 4334                   | [c643363b80](https://linux-hardware.org/?probe=c643363b80) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2ed1a3283e](https://linux-hardware.org/?probe=2ed1a3283e) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [c0c38c5aee](https://linux-hardware.org/?probe=c0c38c5aee) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [65fe7eb049](https://linux-hardware.org/?probe=65fe7eb049) | Dec 30, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c3f9fc25d4](https://linux-hardware.org/?probe=c3f9fc25d4) | Dec 29, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [dbc2669fc0](https://linux-hardware.org/?probe=dbc2669fc0) | Dec 28, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [f514e54057](https://linux-hardware.org/?probe=f514e54057) | Dec 28, 2020 |
| ASUSTek       | PU401LAC                    | [c5bf49eabf](https://linux-hardware.org/?probe=c5bf49eabf) | Dec 26, 2020 |
| HP            | EliteBook 850 G5            | [ce2a32dd24](https://linux-hardware.org/?probe=ce2a32dd24) | Dec 22, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3e419467e2](https://linux-hardware.org/?probe=3e419467e2) | Dec 22, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [87c08ecbb6](https://linux-hardware.org/?probe=87c08ecbb6) | Dec 22, 2020 |
| Notebook      | W54_55SU1,SUW               | [52e86fd2a9](https://linux-hardware.org/?probe=52e86fd2a9) | Dec 20, 2020 |
| Lenovo        | ThinkPad T490s 20NX001PM... | [af7d2d4eb5](https://linux-hardware.org/?probe=af7d2d4eb5) | Dec 20, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [14a84d3948](https://linux-hardware.org/?probe=14a84d3948) | Dec 20, 2020 |
| Lenovo        | ThinkPad T520 4243W54       | [15862aca5c](https://linux-hardware.org/?probe=15862aca5c) | Dec 20, 2020 |
| Lenovo        | ThinkPad X260 20F5S31G00    | [01b87f6602](https://linux-hardware.org/?probe=01b87f6602) | Dec 18, 2020 |
| Lenovo        | Unknown                     | [92b19a0db9](https://linux-hardware.org/?probe=92b19a0db9) | Dec 18, 2020 |
| Dell          | Latitude E7270              | [bac2c2820f](https://linux-hardware.org/?probe=bac2c2820f) | Dec 17, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [5dfa78d268](https://linux-hardware.org/?probe=5dfa78d268) | Dec 15, 2020 |
| HP            | ProBook 650 G5              | [56c46edc3f](https://linux-hardware.org/?probe=56c46edc3f) | Dec 13, 2020 |
| HP            | ProBook 650 G5              | [a035f76fcb](https://linux-hardware.org/?probe=a035f76fcb) | Dec 12, 2020 |
| Acer          | Extensa 2519                | [17bdd3b68f](https://linux-hardware.org/?probe=17bdd3b68f) | Dec 10, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [e9f3972862](https://linux-hardware.org/?probe=e9f3972862) | Dec 04, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [f98c566bb6](https://linux-hardware.org/?probe=f98c566bb6) | Dec 03, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [ff051ee214](https://linux-hardware.org/?probe=ff051ee214) | Dec 01, 2020 |
| Dell          | Latitude E6540              | [5a0fbaa262](https://linux-hardware.org/?probe=5a0fbaa262) | Nov 28, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8b31225bd7](https://linux-hardware.org/?probe=8b31225bd7) | Nov 27, 2020 |
| Apple         | MacBookPro7,1               | [ad6bb1f253](https://linux-hardware.org/?probe=ad6bb1f253) | Nov 24, 2020 |
| Lenovo        | ThinkPad P52 20M9001MMD     | [72ba2ae6cb](https://linux-hardware.org/?probe=72ba2ae6cb) | Nov 19, 2020 |
| Acer          | Aspire V3-575G              | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| Dell          | System XPS L321X            | [3fb9a4373c](https://linux-hardware.org/?probe=3fb9a4373c) | Nov 18, 2020 |
| Lenovo        | ThinkPad T530 24292VG       | [3460614c7f](https://linux-hardware.org/?probe=3460614c7f) | Nov 15, 2020 |
| Lenovo        | ThinkPad W541 20EFS01B09    | [ee5da1d9b0](https://linux-hardware.org/?probe=ee5da1d9b0) | Nov 10, 2020 |
| Lenovo        | ThinkPad X301 2776LEG       | [2c4aa61663](https://linux-hardware.org/?probe=2c4aa61663) | Nov 09, 2020 |
| Dell          | XPS 13 9370                 | [b75b281fee](https://linux-hardware.org/?probe=b75b281fee) | Nov 08, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de9ea1422c](https://linux-hardware.org/?probe=de9ea1422c) | Nov 08, 2020 |
| HP            | Pavilion Notebook           | [1698bf3366](https://linux-hardware.org/?probe=1698bf3366) | Nov 07, 2020 |
| HP            | EliteBook 820 G3            | [e34831e959](https://linux-hardware.org/?probe=e34831e959) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | [bb40872a6b](https://linux-hardware.org/?probe=bb40872a6b) | Nov 05, 2020 |
| HP            | ProBook 4720s               | [acb46376ad](https://linux-hardware.org/?probe=acb46376ad) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [d65f8070e0](https://linux-hardware.org/?probe=d65f8070e0) | Nov 03, 2020 |
| HP            | Compaq 8510p                | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Dell          | XPS 15 9560                 | [5e06a37540](https://linux-hardware.org/?probe=5e06a37540) | Nov 01, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [1213098826](https://linux-hardware.org/?probe=1213098826) | Oct 30, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [de02478ef0](https://linux-hardware.org/?probe=de02478ef0) | Oct 29, 2020 |
| Lenovo        | E31-80 80MX                 | [d56dacea36](https://linux-hardware.org/?probe=d56dacea36) | Oct 29, 2020 |
| Razer         | Blade                       | [7aef75c2c6](https://linux-hardware.org/?probe=7aef75c2c6) | Oct 28, 2020 |
| Dell          | Vostro 3558                 | [eda9a94c60](https://linux-hardware.org/?probe=eda9a94c60) | Oct 28, 2020 |
| Acer          | Nitro AN515-53              | [08235cd1ad](https://linux-hardware.org/?probe=08235cd1ad) | Oct 25, 2020 |
| Acer          | Nitro AN515-53              | [80a32fe04b](https://linux-hardware.org/?probe=80a32fe04b) | Oct 24, 2020 |
| Dell          | Vostro 3558                 | [e22529c904](https://linux-hardware.org/?probe=e22529c904) | Oct 23, 2020 |
| Apple         | MacBookPro5,5               | [b7c6f0c157](https://linux-hardware.org/?probe=b7c6f0c157) | Oct 22, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [cbd374b1d9](https://linux-hardware.org/?probe=cbd374b1d9) | Oct 22, 2020 |
| Toshiba       | Satellite L40               | [3d02e46571](https://linux-hardware.org/?probe=3d02e46571) | Oct 22, 2020 |
| HP            | EliteBook 850 G5            | [1a2d14ded4](https://linux-hardware.org/?probe=1a2d14ded4) | Oct 20, 2020 |
| HP            | Pavilion dv6                | [6fd2a79436](https://linux-hardware.org/?probe=6fd2a79436) | Oct 18, 2020 |
| Toshiba       | Satellite P50-A-11J         | [720f19d566](https://linux-hardware.org/?probe=720f19d566) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | [20453e8620](https://linux-hardware.org/?probe=20453e8620) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | [eee8f03871](https://linux-hardware.org/?probe=eee8f03871) | Oct 10, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [4ffeac234f](https://linux-hardware.org/?probe=4ffeac234f) | Oct 09, 2020 |
| Acer          | Nitro AN515-53              | [fe2889ef02](https://linux-hardware.org/?probe=fe2889ef02) | Oct 08, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | [bea20b3463](https://linux-hardware.org/?probe=bea20b3463) | Oct 04, 2020 |
| Acer          | Aspire 7551                 | [0524a7f258](https://linux-hardware.org/?probe=0524a7f258) | Oct 04, 2020 |
| Acer          | Aspire VN7-792G             | [908eea39dd](https://linux-hardware.org/?probe=908eea39dd) | Oct 04, 2020 |
| Acer          | Nitro AN515-53              | [a1d00d9bc3](https://linux-hardware.org/?probe=a1d00d9bc3) | Oct 03, 2020 |
| Acer          | Nitro AN515-53              | [be2aafbbae](https://linux-hardware.org/?probe=be2aafbbae) | Oct 03, 2020 |
| HP            | ProBook 650 G2              | [f04b6dbdc5](https://linux-hardware.org/?probe=f04b6dbdc5) | Oct 02, 2020 |
| HP            | ProBook 650 G2              | [7b826236e8](https://linux-hardware.org/?probe=7b826236e8) | Oct 02, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | [9a69eca48e](https://linux-hardware.org/?probe=9a69eca48e) | Oct 01, 2020 |
| Acer          | AOD270                      | [4d7f40e97b](https://linux-hardware.org/?probe=4d7f40e97b) | Sep 30, 2020 |
| Lenovo        | 3000 N200 0769B6G           | [7e9967fb0e](https://linux-hardware.org/?probe=7e9967fb0e) | Sep 30, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | [3b51f51354](https://linux-hardware.org/?probe=3b51f51354) | Sep 29, 2020 |
| Notebook      | W54_55SU1,SUW               | [8616e28654](https://linux-hardware.org/?probe=8616e28654) | Sep 29, 2020 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [a3846db026](https://linux-hardware.org/?probe=a3846db026) | Sep 26, 2020 |
| Lenovo        | G710 20252                  | [6d3ef693db](https://linux-hardware.org/?probe=6d3ef693db) | Sep 23, 2020 |
| HP            | Pavilion Sleekbook 15       | [d5217dd737](https://linux-hardware.org/?probe=d5217dd737) | Sep 20, 2020 |
| Google        | Liara                       | [e6434b38e5](https://linux-hardware.org/?probe=e6434b38e5) | Sep 16, 2020 |
| HP            | 620                         | [3cd40bde20](https://linux-hardware.org/?probe=3cd40bde20) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | [1f2fba4e2e](https://linux-hardware.org/?probe=1f2fba4e2e) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | [46f7d12d9e](https://linux-hardware.org/?probe=46f7d12d9e) | Sep 11, 2020 |
| HP            | EliteBook 850 G5            | [826772015a](https://linux-hardware.org/?probe=826772015a) | Sep 09, 2020 |
| LG Electro... | 17Z90N-V.AA77G              | [eaeb99f180](https://linux-hardware.org/?probe=eaeb99f180) | Sep 06, 2020 |
| Apple         | MacBookPro10,1              | [3d676f563d](https://linux-hardware.org/?probe=3d676f563d) | Sep 06, 2020 |
| Lenovo        | ThinkPad X230 2325W3J       | [b076277c46](https://linux-hardware.org/?probe=b076277c46) | Sep 05, 2020 |
| Lenovo        | ThinkPad X240 20AMS39B00    | [b2f7ace5e9](https://linux-hardware.org/?probe=b2f7ace5e9) | Sep 05, 2020 |
| Notebook      | W35xSTQ_370ST               | [69960189a7](https://linux-hardware.org/?probe=69960189a7) | Sep 04, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | [392b8d8877](https://linux-hardware.org/?probe=392b8d8877) | Sep 04, 2020 |
| Lenovo        | V110-15IAP 80TG             | [74a552046a](https://linux-hardware.org/?probe=74a552046a) | Sep 02, 2020 |
| Toshiba       | Satellite L755D             | [e3aa57d80d](https://linux-hardware.org/?probe=e3aa57d80d) | Aug 30, 2020 |
| HP            | 620                         | [2abb876aa3](https://linux-hardware.org/?probe=2abb876aa3) | Aug 27, 2020 |
| Purism        | Librem 13 v2                | [23cd34d2f6](https://linux-hardware.org/?probe=23cd34d2f6) | Aug 27, 2020 |
| HP            | Pavilion dm1                | [39154c83b0](https://linux-hardware.org/?probe=39154c83b0) | Aug 27, 2020 |
| Acer          | NC-SF314-51-56Y4            | [0627a672e7](https://linux-hardware.org/?probe=0627a672e7) | Aug 27, 2020 |
| Lenovo        | Unknown                     | [74313d4eb1](https://linux-hardware.org/?probe=74313d4eb1) | Aug 24, 2020 |
| Lenovo        | ThinkPad P50s 20FLS02200    | [68d5ec0716](https://linux-hardware.org/?probe=68d5ec0716) | Aug 24, 2020 |
| HP            | ProBook 650 G2              | [4a91b4b21f](https://linux-hardware.org/?probe=4a91b4b21f) | Aug 18, 2020 |
| Razer         | Blade                       | [b8e7f44d4a](https://linux-hardware.org/?probe=b8e7f44d4a) | Aug 17, 2020 |
| HP            | EliteBook 820 G3            | [0d1ad99429](https://linux-hardware.org/?probe=0d1ad99429) | Aug 13, 2020 |
| Toshiba       | Satellite L40               | [33ec17e21b](https://linux-hardware.org/?probe=33ec17e21b) | Aug 13, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | [8e3eee2d07](https://linux-hardware.org/?probe=8e3eee2d07) | Aug 06, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | [6b9f38754c](https://linux-hardware.org/?probe=6b9f38754c) | Aug 06, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [72a1412fb1](https://linux-hardware.org/?probe=72a1412fb1) | Aug 04, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [133bc3dd52](https://linux-hardware.org/?probe=133bc3dd52) | Aug 04, 2020 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [6d4445f122](https://linux-hardware.org/?probe=6d4445f122) | Aug 02, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [c535bd5654](https://linux-hardware.org/?probe=c535bd5654) | Jul 29, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [fa42e14984](https://linux-hardware.org/?probe=fa42e14984) | Jul 28, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [e748a3510c](https://linux-hardware.org/?probe=e748a3510c) | Jul 27, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [3122f02f2c](https://linux-hardware.org/?probe=3122f02f2c) | Jul 23, 2020 |
| Packard Be... | EasyNote LJ73               | [b7cb387fea](https://linux-hardware.org/?probe=b7cb387fea) | Jul 21, 2020 |
| Dell          | Latitude E6420              | [e9238dcfff](https://linux-hardware.org/?probe=e9238dcfff) | Jul 19, 2020 |
| Dell          | Latitude E6420              | [231cadfc4a](https://linux-hardware.org/?probe=231cadfc4a) | Jul 19, 2020 |
| Toshiba       | Satellite L755D             | [a0cdb2f0bf](https://linux-hardware.org/?probe=a0cdb2f0bf) | Jul 12, 2020 |
| Toshiba       | Satellite L755D             | [f4ab460d93](https://linux-hardware.org/?probe=f4ab460d93) | Jul 12, 2020 |
| Dell          | Latitude 7480               | [c265940ec9](https://linux-hardware.org/?probe=c265940ec9) | Jul 11, 2020 |
| Apple         | MacBookPro6,1               | [432c9e6acf](https://linux-hardware.org/?probe=432c9e6acf) | Jul 05, 2020 |
| Apple         | MacBookPro14,1              | [b1b965bcfa](https://linux-hardware.org/?probe=b1b965bcfa) | Jul 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [26dfef89d5](https://linux-hardware.org/?probe=26dfef89d5) | Jun 30, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [3f43b86780](https://linux-hardware.org/?probe=3f43b86780) | Jun 29, 2020 |
| Fujitsu       | LIFEBOOK U938               | [445cfe436d](https://linux-hardware.org/?probe=445cfe436d) | Jun 28, 2020 |
| ASUSTek       | K56CB                       | [bbdd76a080](https://linux-hardware.org/?probe=bbdd76a080) | Jun 21, 2020 |
| Fujitsu       | LIFEBOOK U938               | [6fab40c5c2](https://linux-hardware.org/?probe=6fab40c5c2) | Jun 20, 2020 |
| Acer          | Mantasta                    | [fae9194978](https://linux-hardware.org/?probe=fae9194978) | Jun 19, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | [12d9fce39b](https://linux-hardware.org/?probe=12d9fce39b) | Jun 18, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [8307e528e0](https://linux-hardware.org/?probe=8307e528e0) | Jun 17, 2020 |
| HP            | Pavilion 15                 | [6d0c4b8b4f](https://linux-hardware.org/?probe=6d0c4b8b4f) | Jun 16, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [c9de665933](https://linux-hardware.org/?probe=c9de665933) | Jun 14, 2020 |
| Dell          | Latitude 7480               | [f1120b6914](https://linux-hardware.org/?probe=f1120b6914) | Jun 14, 2020 |
| Dell          | XPS 15 9560                 | [68f8b211cb](https://linux-hardware.org/?probe=68f8b211cb) | Jun 13, 2020 |
| Dell          | XPS 15 9560                 | [5e9c9bd030](https://linux-hardware.org/?probe=5e9c9bd030) | Jun 13, 2020 |
| Razer         | Blade                       | [5ed51b12b4](https://linux-hardware.org/?probe=5ed51b12b4) | Jun 12, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | [6e1571661e](https://linux-hardware.org/?probe=6e1571661e) | Jun 12, 2020 |
| Lenovo        | ThinkPad W520 4284Y19       | [ac2ade7339](https://linux-hardware.org/?probe=ac2ade7339) | Jun 07, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [1431224dcf](https://linux-hardware.org/?probe=1431224dcf) | Jun 03, 2020 |
| Dell          | XPS 15 7590                 | [386ef00203](https://linux-hardware.org/?probe=386ef00203) | May 25, 2020 |
| Dell          | XPS 15 7590                 | [544670327d](https://linux-hardware.org/?probe=544670327d) | May 21, 2020 |
| Acer          | TravelMate 6592             | [9bb4619272](https://linux-hardware.org/?probe=9bb4619272) | May 17, 2020 |
| Acer          | TravelMate 6592             | [e4e54de319](https://linux-hardware.org/?probe=e4e54de319) | May 17, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [788a18932c](https://linux-hardware.org/?probe=788a18932c) | May 16, 2020 |
| Acer          | Swift SF514-52T             | [93ede38f81](https://linux-hardware.org/?probe=93ede38f81) | May 16, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [b47983a36a](https://linux-hardware.org/?probe=b47983a36a) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [5fbd9385df](https://linux-hardware.org/?probe=5fbd9385df) | May 13, 2020 |
| Lenovo        | ThinkPad T410 2522WPH       | [236d1e64eb](https://linux-hardware.org/?probe=236d1e64eb) | May 10, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a54bb2200a](https://linux-hardware.org/?probe=a54bb2200a) | May 06, 2020 |
| HP            | 255 G7 Notebook PC          | [0a904bfe70](https://linux-hardware.org/?probe=0a904bfe70) | May 05, 2020 |
| TUXEDO        | Unknown                     | [3f23947dd8](https://linux-hardware.org/?probe=3f23947dd8) | May 04, 2020 |
| HP            | 255 G7 Notebook PC          | [b85ac004b3](https://linux-hardware.org/?probe=b85ac004b3) | May 04, 2020 |
| Lenovo        | ThinkPad T480s 20L8S5U50... | [d295ec1834](https://linux-hardware.org/?probe=d295ec1834) | May 03, 2020 |
| Dell          | Latitude E7450              | [0f14ff60e1](https://linux-hardware.org/?probe=0f14ff60e1) | May 02, 2020 |
| HP            | EliteBook 840 G1            | [9c6700839f](https://linux-hardware.org/?probe=9c6700839f) | May 01, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [689865b9bf](https://linux-hardware.org/?probe=689865b9bf) | Apr 30, 2020 |
| Acer          | Aspire A715-72G             | [db52ab416a](https://linux-hardware.org/?probe=db52ab416a) | Apr 29, 2020 |
| HP            | EliteBook 840 G1            | [b77a2c1bdc](https://linux-hardware.org/?probe=b77a2c1bdc) | Apr 27, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | [2ea2bebae7](https://linux-hardware.org/?probe=2ea2bebae7) | Apr 25, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | [47ae6712b9](https://linux-hardware.org/?probe=47ae6712b9) | Apr 25, 2020 |
| HP            | Unknown                     | [7da32c9344](https://linux-hardware.org/?probe=7da32c9344) | Apr 21, 2020 |
| Dell          | Latitude E5510              | [a70ec059cf](https://linux-hardware.org/?probe=a70ec059cf) | Apr 13, 2020 |
| HP            | Pavilion dv9700             | [6096eebeb4](https://linux-hardware.org/?probe=6096eebeb4) | Apr 11, 2020 |
| Apple         | MacBookPro5,5               | [9f7081cc76](https://linux-hardware.org/?probe=9f7081cc76) | Apr 04, 2020 |
| Lenovo        | B50-10 80QR                 | [587fb80750](https://linux-hardware.org/?probe=587fb80750) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | [bfb0ade0c7](https://linux-hardware.org/?probe=bfb0ade0c7) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | [26154d1d2c](https://linux-hardware.org/?probe=26154d1d2c) | Apr 01, 2020 |
| ASUSTek       | N76VB                       | [a771ac7748](https://linux-hardware.org/?probe=a771ac7748) | Mar 24, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [069d575f4a](https://linux-hardware.org/?probe=069d575f4a) | Mar 21, 2020 |
| HP            | Pavilion dv7                | [64000a6ec8](https://linux-hardware.org/?probe=64000a6ec8) | Mar 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [69559fb5ce](https://linux-hardware.org/?probe=69559fb5ce) | Mar 18, 2020 |
| Toshiba       | Satellite C670D-10C         | [bdcd7e9b36](https://linux-hardware.org/?probe=bdcd7e9b36) | Mar 17, 2020 |
| Toshiba       | Satellite C670D-10C         | [ab2ea68be0](https://linux-hardware.org/?probe=ab2ea68be0) | Mar 17, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [86e1d115b9](https://linux-hardware.org/?probe=86e1d115b9) | Mar 15, 2020 |
| HP            | ProBook 4720s               | [a32d5c092c](https://linux-hardware.org/?probe=a32d5c092c) | Mar 15, 2020 |
| Toshiba       | Satellite L40               | [467c320928](https://linux-hardware.org/?probe=467c320928) | Mar 11, 2020 |
| Lenovo        | ThinkPad Edge E530 3259C... | [7e0acb9bed](https://linux-hardware.org/?probe=7e0acb9bed) | Mar 06, 2020 |
| HP            | ProBook 4720s               | [823553cfbd](https://linux-hardware.org/?probe=823553cfbd) | Mar 03, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [de25ec2891](https://linux-hardware.org/?probe=de25ec2891) | Feb 28, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [b333f7015a](https://linux-hardware.org/?probe=b333f7015a) | Feb 28, 2020 |
| HP            | ZBook 14u G5                | [03871e6b83](https://linux-hardware.org/?probe=03871e6b83) | Feb 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [0937d2a588](https://linux-hardware.org/?probe=0937d2a588) | Feb 20, 2020 |
| Dell          | Inspiron 3542               | [5e00c1766c](https://linux-hardware.org/?probe=5e00c1766c) | Feb 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [7f8aef2f6b](https://linux-hardware.org/?probe=7f8aef2f6b) | Feb 19, 2020 |
| MSI           | MS-1738                     | [0cbf139f1d](https://linux-hardware.org/?probe=0cbf139f1d) | Feb 11, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [7773f702ab](https://linux-hardware.org/?probe=7773f702ab) | Feb 10, 2020 |
| ASUSTek       | UX331UA                     | [62bdf0c233](https://linux-hardware.org/?probe=62bdf0c233) | Feb 10, 2020 |
| HP            | EliteBook 850 G5            | [fc9101307a](https://linux-hardware.org/?probe=fc9101307a) | Feb 07, 2020 |
| Dell          | Precision 7530              | [bb59dc45d2](https://linux-hardware.org/?probe=bb59dc45d2) | Feb 06, 2020 |
| MSI           | MS-1738                     | [1f7c3ccb75](https://linux-hardware.org/?probe=1f7c3ccb75) | Jan 29, 2020 |
| Lenovo        | IdeaPad Y500 9541           | [1435e47012](https://linux-hardware.org/?probe=1435e47012) | Jan 27, 2020 |
| ASUSTek       | X555UJ                      | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | [44ad91d4da](https://linux-hardware.org/?probe=44ad91d4da) | Jan 24, 2020 |
| Dell          | Latitude 5590               | [206a367d42](https://linux-hardware.org/?probe=206a367d42) | Jan 24, 2020 |
| HP            | EliteBook 850 G5            | [bcc6422548](https://linux-hardware.org/?probe=bcc6422548) | Jan 18, 2020 |
| Samsung       | N150/N210/N220              | [91718b856a](https://linux-hardware.org/?probe=91718b856a) | Jan 16, 2020 |
| HP            | EliteBook 840 G6            | [79936056dd](https://linux-hardware.org/?probe=79936056dd) | Jan 16, 2020 |
| HP            | Laptop 15-bw0xx             | [2aff706ca4](https://linux-hardware.org/?probe=2aff706ca4) | Jan 15, 2020 |
| Lenovo        | ThinkPad T430s 2356W1L      | [42b6186198](https://linux-hardware.org/?probe=42b6186198) | Jan 13, 2020 |
| HP            | ProBook 4710s               | [d6124de12a](https://linux-hardware.org/?probe=d6124de12a) | Jan 01, 2020 |
| HP            | ProBook 4710s               | [7eb0b2437d](https://linux-hardware.org/?probe=7eb0b2437d) | Jan 01, 2020 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [14015a6cde](https://linux-hardware.org/?probe=14015a6cde) | Dec 24, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [c7b13e4ba2](https://linux-hardware.org/?probe=c7b13e4ba2) | Dec 23, 2019 |
| Dell          | Inspiron 1545               | [adaa5b6d54](https://linux-hardware.org/?probe=adaa5b6d54) | Dec 10, 2019 |
| Lenovo        | ThinkPad P51 20HH001RMD     | [7ab81dbd28](https://linux-hardware.org/?probe=7ab81dbd28) | Nov 30, 2019 |
| HP            | Pavilion dv6                | [fdc46ce1cd](https://linux-hardware.org/?probe=fdc46ce1cd) | Nov 26, 2019 |
| Lenovo        | ThinkPad S5-S540 20B3005... | [e84f3912be](https://linux-hardware.org/?probe=e84f3912be) | Nov 10, 2019 |
| eMachines     | E725                        | [599a7f6c54](https://linux-hardware.org/?probe=599a7f6c54) | Nov 03, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [9607f525a8](https://linux-hardware.org/?probe=9607f525a8) | Oct 29, 2019 |
| Apple         | MacBookPro9,2               | [99702307ab](https://linux-hardware.org/?probe=99702307ab) | Oct 21, 2019 |
| HP            | OMEN by Laptop              | [90ef6677b7](https://linux-hardware.org/?probe=90ef6677b7) | Oct 15, 2019 |
| Dell          | XPS 15 9570                 | [6cdbd762c1](https://linux-hardware.org/?probe=6cdbd762c1) | Oct 13, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [acd2d7dfad](https://linux-hardware.org/?probe=acd2d7dfad) | Oct 12, 2019 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [98855b1409](https://linux-hardware.org/?probe=98855b1409) | Oct 09, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Denmark/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 96        | 11.94%  |
| Ubuntu 22.04       | 55        | 6.84%   |
| Ubuntu 18.04       | 48        | 5.97%   |
| Pop!_OS 22.04      | 26        | 3.23%   |
| Arch Rolling       | 23        | 2.86%   |
| Fedora 40          | 19        | 2.36%   |
| Fedora 38          | 18        | 2.24%   |
| Ubuntu 24.04       | 16        | 1.99%   |
| Ubuntu 21.10       | 15        | 1.87%   |
| OpenMandriva 4.2   | 12        | 1.49%   |
| Fedora 34          | 12        | 1.49%   |
| Linux Mint 21.2    | 11        | 1.37%   |
| Fedora 39          | 11        | 1.37%   |
| Arch               | 11        | 1.37%   |
| Manjaro            | 10        | 1.24%   |
| Debian 12          | 10        | 1.24%   |
| Debian 11          | 10        | 1.24%   |
| Fedora 36          | 9         | 1.12%   |
| Zorin 16           | 8         | 1%      |
| Ubuntu 19.04       | 8         | 1%      |
| Pop!_OS 20.04      | 8         | 1%      |
| OpenMandriva 23.03 | 8         | 1%      |
| KDE neon 22.04     | 8         | 1%      |
| ArcoLinux Rolling  | 8         | 1%      |
| Zorin 17           | 7         | 0.87%   |
| Zorin 15           | 7         | 0.87%   |
| Pop!_OS 21.04      | 7         | 0.87%   |
| Linux Mint 21.1    | 7         | 0.87%   |
| Linux Mint 20.3    | 7         | 0.87%   |
| Linux Mint 20.2    | 7         | 0.87%   |
| KDE neon 20.04     | 7         | 0.87%   |
| Fedora 32          | 7         | 0.87%   |
| Debian 10          | 7         | 0.87%   |
| Ubuntu 23.10       | 6         | 0.75%   |
| Ubuntu 22.10       | 6         | 0.75%   |
| Ubuntu 20.10       | 6         | 0.75%   |
| Pop!_OS 21.10      | 6         | 0.75%   |
| OpenMandriva 4.3   | 6         | 0.75%   |
| Linux Mint 21      | 6         | 0.75%   |
| Linux Mint 20.1    | 6         | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 254       | 34%     |
| Fedora        | 88        | 11.78%  |
| Linux Mint    | 62        | 8.3%    |
| Pop!_OS       | 51        | 6.83%   |
| OpenMandriva  | 40        | 5.35%   |
| Arch          | 32        | 4.28%   |
| Debian        | 29        | 3.88%   |
| Manjaro       | 24        | 3.21%   |
| Zorin         | 22        | 2.95%   |
| Kubuntu       | 17        | 2.28%   |
| KDE neon      | 15        | 2.01%   |
| Xubuntu       | 12        | 1.61%   |
| ArcoLinux     | 10        | 1.34%   |
| Ubuntu Unity  | 8         | 1.07%   |
| SteamOS       | 7         | 0.94%   |
| Elementary    | 7         | 0.94%   |
| openSUSE      | 6         | 0.8%    |
| Kali          | 6         | 0.8%    |
| Void Linux    | 5         | 0.67%   |
| ROSA          | 5         | 0.67%   |
| EndeavourOS   | 5         | 0.67%   |
| Ubuntu MATE   | 4         | 0.54%   |
| Parrot        | 4         | 0.54%   |
| LMDE          | 4         | 0.54%   |
| NixOS         | 3         | 0.4%    |
| Garuda Linux  | 3         | 0.4%    |
| Endless       | 3         | 0.4%    |
| Clear Linux   | 3         | 0.4%    |
| Xero          | 2         | 0.27%   |
| TUXEDO OS     | 2         | 0.27%   |
| Lubuntu       | 2         | 0.27%   |
| antiX         | 2         | 0.27%   |
| Vanilla       | 1         | 0.13%   |
| Ubuntu Studio | 1         | 0.13%   |
| Ubuntu Budgie | 1         | 0.13%   |
| Reborn OS     | 1         | 0.13%   |
| Nobara        | 1         | 0.13%   |
| LinuxFX       | 1         | 0.13%   |
| Guix          | 1         | 0.13%   |
| Gentoo        | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 14        | 1.59%   |
| 5.10.14-desktop-1omv4002 | 12        | 1.36%   |
| 6.2.6-desktop-1omv2390   | 8         | 0.91%   |
| 5.16.7-desktop-1omv4003  | 7         | 0.8%    |
| 5.15.0-56-generic        | 7         | 0.8%    |
| 6.9.3-76060903-generic   | 6         | 0.68%   |
| 6.2.6-76060206-generic   | 6         | 0.68%   |
| 5.4.0-52-generic         | 6         | 0.68%   |
| 5.4.0-48-generic         | 6         | 0.68%   |
| 5.4.0-26-generic         | 6         | 0.68%   |
| 6.8.0-45-generic         | 5         | 0.57%   |
| 6.5.0-41-generic         | 5         | 0.57%   |
| 6.5.0-26-generic         | 5         | 0.57%   |
| 5.4.0-7634-generic       | 5         | 0.57%   |
| 5.4.0-47-generic         | 5         | 0.57%   |
| 5.19.0-35-generic        | 5         | 0.57%   |
| 5.15.0-53-generic        | 5         | 0.57%   |
| 5.15.0-52-generic        | 5         | 0.57%   |
| 5.11.0-40-generic        | 5         | 0.57%   |
| 6.8.0-40-generic         | 4         | 0.45%   |
| 6.8.0-35-generic         | 4         | 0.45%   |
| 6.5.0-15-generic         | 4         | 0.45%   |
| 6.5.0-14-generic         | 4         | 0.45%   |
| 6.4.6-76060406-generic   | 4         | 0.45%   |
| 6.2.0-26-generic         | 4         | 0.45%   |
| 6.10.6-200.fc40.x86_64   | 4         | 0.45%   |
| 5.4.0-58-generic         | 4         | 0.45%   |
| 5.4.0-40-generic         | 4         | 0.45%   |
| 5.3.0-40-generic         | 4         | 0.45%   |
| 5.19.0-76051900-generic  | 4         | 0.45%   |
| 5.15.0-46-generic        | 4         | 0.45%   |
| 5.15.0-43-generic        | 4         | 0.45%   |
| 5.11.0-41-generic        | 4         | 0.45%   |
| 5.11.0-27-generic        | 4         | 0.45%   |
| 5.0.0-23-generic         | 4         | 0.45%   |
| 4.15.0-55-generic        | 4         | 0.45%   |
| 6.5.0-45-generic         | 3         | 0.34%   |
| 6.5.0-28-generic         | 3         | 0.34%   |
| 6.5.0-17-generic         | 3         | 0.34%   |
| 6.4.11-desktop-1omv2390  | 3         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 96        | 11.64%  |
| 5.15.0  | 71        | 8.61%   |
| 6.5.0   | 38        | 4.61%   |
| 5.11.0  | 36        | 4.36%   |
| 4.15.0  | 36        | 4.36%   |
| 5.13.0  | 30        | 3.64%   |
| 5.8.0   | 28        | 3.39%   |
| 5.19.0  | 28        | 3.39%   |
| 6.8.0   | 24        | 2.91%   |
| 6.2.0   | 18        | 2.18%   |
| 5.3.0   | 18        | 2.18%   |
| 5.0.0   | 17        | 2.06%   |
| 6.2.6   | 16        | 1.94%   |
| 4.18.0  | 13        | 1.58%   |
| 6.1.0   | 12        | 1.45%   |
| 5.10.14 | 12        | 1.45%   |
| 5.10.0  | 12        | 1.45%   |
| 6.9.3   | 7         | 0.85%   |
| 5.16.7  | 7         | 0.85%   |
| 4.19.0  | 7         | 0.85%   |
| 6.4.6   | 5         | 0.61%   |
| 6.10.6  | 5         | 0.61%   |
| 6.7.9   | 4         | 0.48%   |
| 6.1.1   | 4         | 0.48%   |
| 5.7.15  | 4         | 0.48%   |
| 6.9.7   | 3         | 0.36%   |
| 6.8.7   | 3         | 0.36%   |
| 6.6.2   | 3         | 0.36%   |
| 6.5.9   | 3         | 0.36%   |
| 6.5.6   | 3         | 0.36%   |
| 6.5.5   | 3         | 0.36%   |
| 6.4.8   | 3         | 0.36%   |
| 6.4.11  | 3         | 0.36%   |
| 6.3.8   | 3         | 0.36%   |
| 6.11.0  | 3         | 0.36%   |
| 6.10.5  | 3         | 0.36%   |
| 6.10.12 | 3         | 0.36%   |
| 6.10.0  | 3         | 0.36%   |
| 6.0.10  | 3         | 0.36%   |
| 5.9.0   | 3         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 105       | 12.87%  |
| 5.15    | 91        | 11.15%  |
| 6.5     | 53        | 6.5%    |
| 5.19    | 40        | 4.9%    |
| 5.11    | 40        | 4.9%    |
| 5.8     | 39        | 4.78%   |
| 6.2     | 38        | 4.66%   |
| 6.8     | 36        | 4.41%   |
| 4.15    | 36        | 4.41%   |
| 5.13    | 35        | 4.29%   |
| 5.10    | 31        | 3.8%    |
| 6.1     | 28        | 3.43%   |
| 5.16    | 20        | 2.45%   |
| 6.10    | 19        | 2.33%   |
| 5.3     | 18        | 2.21%   |
| 5.0     | 18        | 2.21%   |
| 6.9     | 15        | 1.84%   |
| 6.6     | 14        | 1.72%   |
| 6.4     | 14        | 1.72%   |
| 4.18    | 14        | 1.72%   |
| 5.14    | 13        | 1.59%   |
| 6.0     | 11        | 1.35%   |
| 6.7     | 10        | 1.23%   |
| 6.11    | 9         | 1.1%    |
| 5.9     | 9         | 1.1%    |
| 4.19    | 8         | 0.98%   |
| 5.18    | 7         | 0.86%   |
| 6.3     | 6         | 0.74%   |
| 5.7     | 6         | 0.74%   |
| 5.6     | 6         | 0.74%   |
| 5.17    | 6         | 0.74%   |
| 5.12    | 5         | 0.61%   |
| 5.1     | 3         | 0.37%   |
| 6.12    | 2         | 0.25%   |
| 4.9     | 2         | 0.25%   |
| 4.4     | 2         | 0.25%   |
| 4.14    | 2         | 0.25%   |
| 5.2     | 1         | 0.12%   |
| 4.16    | 1         | 0.12%   |
| 4.13    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 696       | 97.21%  |
| i686   | 20        | 2.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 379       | 49.93%  |
| KDE5            | 109       | 14.36%  |
| Unknown         | 78        | 10.28%  |
| X-Cinnamon      | 52        | 6.85%   |
| XFCE            | 46        | 6.06%   |
| KDE6            | 17        | 2.24%   |
| MATE            | 16        | 2.11%   |
| KDE             | 13        | 1.71%   |
| Unity           | 8         | 1.05%   |
| i3              | 8         | 1.05%   |
| Pantheon        | 6         | 0.79%   |
| LXQt            | 5         | 0.66%   |
| Cinnamon        | 4         | 0.53%   |
| sway            | 3         | 0.4%    |
| icewm           | 2         | 0.26%   |
| GNOME Flashback | 2         | 0.26%   |
| ubuntu          | 1         | 0.13%   |
| qtile-default   | 1         | 0.13%   |
| none+awesome    | 1         | 0.13%   |
| LeftWM          | 1         | 0.13%   |
| KDE4            | 1         | 0.13%   |
| Hyprland        | 1         | 0.13%   |
| fluxbox         | 1         | 0.13%   |
| Endless:GNOME   | 1         | 0.13%   |
| COSMIC          | 1         | 0.13%   |
| Budgie          | 1         | 0.13%   |
| awesome         | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 487       | 65.02%  |
| Wayland | 216       | 28.84%  |
| Unknown | 39        | 5.21%   |
| Tty     | 7         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 376       | 50.81%  |
| GDM3    | 121       | 16.35%  |
| SDDM    | 88        | 11.89%  |
| GDM     | 82        | 11.08%  |
| LightDM | 57        | 7.7%    |
| TDM     | 12        | 1.62%   |
| SLIMSKI | 1         | 0.14%   |
| LY-DM   | 1         | 0.14%   |
| Ly      | 1         | 0.14%   |
| GREETD  | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 262       | 35.36%  |
| da_DK   | 228       | 30.77%  |
| en_DK   | 90        | 12.15%  |
| Unknown | 64        | 8.64%   |
| en_GB   | 50        | 6.75%   |
| de_DE   | 16        | 2.16%   |
| C       | 13        | 1.75%   |
| pl_PL   | 3         | 0.4%    |
| en_AG   | 3         | 0.4%    |
| fr_FR   | 2         | 0.27%   |
| zh_TW   | 1         | 0.13%   |
| pt_BR   | 1         | 0.13%   |
| nl_NL   | 1         | 0.13%   |
| it_IT   | 1         | 0.13%   |
| is_IS   | 1         | 0.13%   |
| es_ES   | 1         | 0.13%   |
| en_CA   | 1         | 0.13%   |
| en_AU   | 1         | 0.13%   |
| el_GR   | 1         | 0.13%   |
| de_CH   | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 371       | 50.68%  |
| BIOS | 361       | 49.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 512       | 69.19%  |
| Btrfs   | 116       | 15.68%  |
| Tmpfs   | 46        | 6.22%   |
| Overlay | 32        | 4.32%   |
| Unknown | 21        | 2.84%   |
| Zfs     | 8         | 1.08%   |
| Ext2    | 3         | 0.41%   |
| Xfs     | 2         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 391       | 53.13%  |
| GPT     | 291       | 39.54%  |
| MBR     | 54        | 7.34%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 657       | 90.5%   |
| Yes       | 69        | 9.5%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 586       | 80.72%  |
| Yes       | 140       | 19.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 274       | 38.32%  |
| Hewlett-Packard     | 108       | 15.1%   |
| ASUSTek Computer    | 68        | 9.51%   |
| Dell                | 65        | 9.09%   |
| Acer                | 51        | 7.13%   |
| Apple               | 38        | 5.31%   |
| Toshiba             | 13        | 1.82%   |
| MSI                 | 13        | 1.82%   |
| Notebook            | 10        | 1.4%    |
| HUAWEI              | 7         | 0.98%   |
| Valve               | 6         | 0.84%   |
| Samsung Electronics | 6         | 0.84%   |
| Google              | 6         | 0.84%   |
| Razer               | 4         | 0.56%   |
| Medion              | 4         | 0.56%   |
| TUXEDO              | 3         | 0.42%   |
| Gigabyte Technology | 3         | 0.42%   |
| Unknown             | 3         | 0.42%   |
| Timi                | 2         | 0.28%   |
| Sony                | 2         | 0.28%   |
| Quanta              | 2         | 0.28%   |
| Packard Bell        | 2         | 0.28%   |
| GPD                 | 2         | 0.28%   |
| Fujitsu             | 2         | 0.28%   |
| eMachines           | 2         | 0.28%   |
| DukaPC              | 2         | 0.28%   |
| AMI                 | 2         | 0.28%   |
| System76            | 1         | 0.14%   |
| Standard            | 1         | 0.14%   |
| SLIMBOOK            | 1         | 0.14%   |
| Purism              | 1         | 0.14%   |
| PC Specialist       | 1         | 0.14%   |
| LG Electronics      | 1         | 0.14%   |
| LAMINA              | 1         | 0.14%   |
| Komplett            | 1         | 0.14%   |
| KaiTian             | 1         | 0.14%   |
| Insyde              | 1         | 0.14%   |
| IBM                 | 1         | 0.14%   |
| Fujitsu Siemens     | 1         | 0.14%   |
| Framework           | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 10        | 1.4%    |
| Valve Jupiter                         | 6         | 0.84%   |
| Dell XPS 15 9560                      | 6         | 0.84%   |
| HP Pavilion dv7                       | 5         | 0.7%    |
| Apple MacBookPro9,2                   | 5         | 0.7%    |
| Apple MacBookPro11,1                  | 5         | 0.7%    |
| Dell XPS 15 9570                      | 4         | 0.56%   |
| Dell XPS 13 9370                      | 4         | 0.56%   |
| Lenovo ThinkPad T530 24295L4          | 3         | 0.42%   |
| HP Pavilion Notebook                  | 3         | 0.42%   |
| HP Pavilion g7                        | 3         | 0.42%   |
| HP OMEN by Laptop                     | 3         | 0.42%   |
| HP Notebook                           | 3         | 0.42%   |
| HP EliteBook 820 G3                   | 3         | 0.42%   |
| Dell Latitude E7440                   | 3         | 0.42%   |
| Dell Latitude E6540                   | 3         | 0.42%   |
| Dell Latitude 7480                    | 3         | 0.42%   |
| ASUS ROG Zephyrus G14 GA402RK_GA402RK | 3         | 0.42%   |
| Apple MacBookPro8,1                   | 3         | 0.42%   |
| Apple MacBookPro5,5                   | 3         | 0.42%   |
| Apple MacBookPro14,1                  | 3         | 0.42%   |
| Apple MacBookPro12,1                  | 3         | 0.42%   |
| Apple MacBookAir7,2                   | 3         | 0.42%   |
| Toshiba Satellite P850                | 2         | 0.28%   |
| Toshiba Satellite L40                 | 2         | 0.28%   |
| Razer Blade Stealth                   | 2         | 0.28%   |
| Quanta MW1/HW1                        | 2         | 0.28%   |
| Notebook W54_55SU1,SUW                | 2         | 0.28%   |
| Lenovo Z50-75 80EC                    | 2         | 0.28%   |
| Lenovo V110-15IAP 80TG                | 2         | 0.28%   |
| Lenovo ThinkPad X13 Gen 4 21J3CTO1WW  | 2         | 0.28%   |
| Lenovo ThinkPad T14 Gen 3 21CFCTO1WW  | 2         | 0.28%   |
| Lenovo ThinkPad P52 20M9001GMX        | 2         | 0.28%   |
| Lenovo ThinkBook 15 G2 ARE 20VG       | 2         | 0.28%   |
| Lenovo Legion 5 15ACH6H 82JU          | 2         | 0.28%   |
| Lenovo IdeaPad Y700-15ISK 80NV        | 2         | 0.28%   |
| Lenovo IdeaPad Y500 9541              | 2         | 0.28%   |
| Lenovo IdeaPad S130-14IGM 81J2        | 2         | 0.28%   |
| Lenovo IdeaPad 310-15IKB 80TV         | 2         | 0.28%   |
| Lenovo G505 20240                     | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 200       | 27.97%  |
| Acer Aspire           | 35        | 4.9%    |
| HP EliteBook          | 30        | 4.2%    |
| Dell Latitude         | 27        | 3.78%   |
| Lenovo IdeaPad        | 26        | 3.64%   |
| HP Pavilion           | 25        | 3.5%    |
| Dell XPS              | 21        | 2.94%   |
| HP Laptop             | 14        | 1.96%   |
| Toshiba Satellite     | 13        | 1.82%   |
| HP ProBook            | 13        | 1.82%   |
| ASUS ROG              | 11        | 1.54%   |
| ASUS ZenBook          | 10        | 1.4%    |
| Unknown               | 10        | 1.4%    |
| Lenovo Legion         | 9         | 1.26%   |
| ASUS Vivobook         | 8         | 1.12%   |
| Apple MacBookPro11    | 8         | 1.12%   |
| HP Compaq             | 7         | 0.98%   |
| Dell Inspiron         | 7         | 0.98%   |
| Valve Jupiter         | 6         | 0.84%   |
| Lenovo ThinkBook      | 6         | 0.84%   |
| Dell Precision        | 6         | 0.84%   |
| Apple MacBookPro9     | 6         | 0.84%   |
| Acer Swift            | 6         | 0.84%   |
| Lenovo Yoga           | 5         | 0.7%    |
| HP OMEN               | 5         | 0.7%    |
| ASUS ASUS             | 5         | 0.7%    |
| Razer Blade           | 4         | 0.56%   |
| Apple MacBookPro14    | 4         | 0.56%   |
| HP ZBook              | 3         | 0.42%   |
| HP Notebook           | 3         | 0.42%   |
| ASUS Strix            | 3         | 0.42%   |
| Apple MacBookPro8     | 3         | 0.42%   |
| Apple MacBookPro5     | 3         | 0.42%   |
| Apple MacBookPro12    | 3         | 0.42%   |
| Apple MacBookAir7     | 3         | 0.42%   |
| Acer Nitro            | 3         | 0.42%   |
| Samsung 530U3C        | 2         | 0.28%   |
| Quanta MW1            | 2         | 0.28%   |
| Packard Bell EasyNote | 2         | 0.28%   |
| Notebook W54          | 2         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 62        | 8.67%   |
| 2013    | 61        | 8.53%   |
| 2021    | 56        | 7.83%   |
| 2017    | 56        | 7.83%   |
| 2020    | 54        | 7.55%   |
| 2019    | 54        | 7.55%   |
| 2015    | 48        | 6.71%   |
| 2012    | 48        | 6.71%   |
| 2011    | 48        | 6.71%   |
| 2016    | 42        | 5.87%   |
| 2014    | 38        | 5.31%   |
| 2022    | 28        | 3.92%   |
| 2010    | 26        | 3.64%   |
| 2009    | 23        | 3.22%   |
| 2007    | 22        | 3.08%   |
| 2008    | 19        | 2.66%   |
| 2023    | 18        | 2.52%   |
| 2024    | 5         | 0.7%    |
| 2006    | 5         | 0.7%    |
| 2003    | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 715       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 635       | 88.07%  |
| Enabled  | 86        | 11.93%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 708       | 99.02%  |
| Yes  | 7         | 0.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 227       | 31.22%  |
| 8.01-16.0   | 138       | 18.98%  |
| 16.01-24.0  | 132       | 18.16%  |
| 3.01-4.0    | 102       | 14.03%  |
| 32.01-64.0  | 62        | 8.53%   |
| 24.01-32.0  | 24        | 3.3%    |
| 1.01-2.0    | 18        | 2.48%   |
| 2.01-3.0    | 11        | 1.51%   |
| 64.01-256.0 | 10        | 1.38%   |
| 0.51-1.0    | 2         | 0.28%   |
| 0.01-0.5    | 1         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 231       | 28.91%  |
| 2.01-3.0   | 229       | 28.66%  |
| 4.01-8.0   | 157       | 19.65%  |
| 3.01-4.0   | 114       | 14.27%  |
| 8.01-16.0  | 28        | 3.5%    |
| 0.51-1.0   | 28        | 3.5%    |
| 0.01-0.5   | 5         | 0.63%   |
| 24.01-32.0 | 3         | 0.38%   |
| 16.01-24.0 | 3         | 0.38%   |
| 32.01-64.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 577       | 78.93%  |
| 2      | 136       | 18.6%   |
| 3      | 14        | 1.92%   |
| 0      | 3         | 0.41%   |
| 4      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 505       | 70.14%  |
| Yes       | 215       | 29.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 589       | 81.81%  |
| No        | 131       | 18.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 703       | 98.18%  |
| No        | 13        | 1.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 603       | 83.06%  |
| No        | 123       | 16.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Denmark | 715       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Copenhagen            | 171       | 22.18%  |
| Frederiksberg         | 44        | 5.71%   |
| Odense                | 42        | 5.45%   |
| Aarhus                | 24        | 3.11%   |
| Bronshoj              | 20        | 2.59%   |
| Slagelse              | 19        | 2.46%   |
| Aalborg               | 18        | 2.33%   |
| Valby                 | 16        | 2.08%   |
| Silkeborg             | 14        | 1.82%   |
| Kongens Lyngby        | 11        | 1.43%   |
| Esbjerg               | 11        | 1.43%   |
| Viborg                | 10        | 1.3%    |
| Taastrup              | 10        | 1.3%    |
| Holstebro             | 10        | 1.3%    |
| Skanderborg           | 9         | 1.17%   |
| Norresundby           | 9         | 1.17%   |
| Glostrup Municipality | 9         | 1.17%   |
| Horsens               | 8         | 1.04%   |
| Roskilde              | 7         | 0.91%   |
| Kolding               | 7         | 0.91%   |
| Gentofte Municipality | 7         | 0.91%   |
| Aabenraa              | 7         | 0.91%   |
| Naestved              | 6         | 0.78%   |
| Kastrup               | 6         | 0.78%   |
| Hvidovre              | 6         | 0.78%   |
| Herlev                | 6         | 0.78%   |
| Fredericia            | 6         | 0.78%   |
| Albertslund           | 6         | 0.78%   |
| Vanlose               | 5         | 0.65%   |
| Sabro                 | 5         | 0.65%   |
| Nyborg                | 5         | 0.65%   |
| Hojbjerg              | 5         | 0.65%   |
| Elsinore              | 5         | 0.65%   |
| Brønderslev          | 5         | 0.65%   |
| Viby J                | 4         | 0.52%   |
| Thisted               | 4         | 0.52%   |
| Skive                 | 4         | 0.52%   |
| Sindal                | 4         | 0.52%   |
| Rønne                | 4         | 0.52%   |
| Rødovre Municipality | 4         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 215       | 279    | 25.15%  |
| WDC                         | 70        | 91     | 8.19%   |
| Kingston                    | 58        | 82     | 6.78%   |
| Seagate                     | 57        | 66     | 6.67%   |
| Toshiba                     | 54        | 76     | 6.32%   |
| SK hynix                    | 53        | 70     | 6.2%    |
| SanDisk                     | 49        | 63     | 5.73%   |
| Unknown                     | 44        | 53     | 5.15%   |
| Micron Technology           | 33        | 41     | 3.86%   |
| Intel                       | 31        | 35     | 3.63%   |
| Hitachi                     | 28        | 34     | 3.27%   |
| Apple                       | 22        | 29     | 2.57%   |
| HGST                        | 18        | 23     | 2.11%   |
| LITEON                      | 11        | 24     | 1.29%   |
| Crucial                     | 11        | 11     | 1.29%   |
| PNY                         | 9         | 9      | 1.05%   |
| Intenso                     | 9         | 11     | 1.05%   |
| KIOXIA                      | 8         | 10     | 0.94%   |
| LITEONIT                    | 6         | 8      | 0.7%    |
| A-DATA Technology           | 6         | 7      | 0.7%    |
| Verbatim                    | 5         | 9      | 0.58%   |
| Lenovo                      | 5         | 6      | 0.58%   |
| OCZ                         | 4         | 4      | 0.47%   |
| China                       | 4         | 5      | 0.47%   |
| Phison Electronics          | 3         | 3      | 0.35%   |
| Phison                      | 3         | 4      | 0.35%   |
| Kingston Technology Company | 3         | 3      | 0.35%   |
| USB3.0                      | 2         | 2      | 0.23%   |
| Solid State Storage         | 2         | 2      | 0.23%   |
| Silicon Motion              | 2         | 2      | 0.23%   |
| Fujitsu                     | 2         | 3      | 0.23%   |
| ADATA Technology            | 2         | 3      | 0.23%   |
| XPG                         | 1         | 1      | 0.12%   |
| Union Memory                | 1         | 4      | 0.12%   |
| UMIS                        | 1         | 1      | 0.12%   |
| Transcend                   | 1         | 1      | 0.12%   |
| TO Exter                    | 1         | 1      | 0.12%   |
| Team                        | 1         | 1      | 0.12%   |
| SPCC                        | 1         | 1      | 0.12%   |
| Plextor                     | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 18        | 2.02%   |
| Samsung SSD 850 EVO 250GB                            | 12        | 1.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 11        | 1.23%   |
| Kingston SA400S37480G 480GB SSD                      | 11        | 1.23%   |
| Samsung SSD 850 EVO 500GB                            | 10        | 1.12%   |
| Samsung NVMe SSD Drive 256GB                         | 10        | 1.12%   |
| Unknown MMC Card  32GB                               | 8         | 0.9%    |
| Unknown MMC Card  128GB                              | 8         | 0.9%    |
| Samsung SSD 860 EVO 500GB                            | 7         | 0.79%   |
| Kingston SA400S37240G 240GB SSD                      | 7         | 0.79%   |
| Unknown MMC Card  64GB                               | 6         | 0.67%   |
| Toshiba NVMe SSD Drive 512GB                         | 6         | 0.67%   |
| Samsung NVMe SSD Drive 512GB                         | 6         | 0.67%   |
| HGST HTS721010A9E630 1TB                             | 6         | 0.67%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 5         | 0.56%   |
| SK hynix NVMe SSD Drive 512GB                        | 5         | 0.56%   |
| SK hynix HFS256G39TND-N210A 256GB SSD                | 5         | 0.56%   |
| Samsung NVMe SSD Drive 1024GB                        | 5         | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 4         | 0.45%   |
| Toshiba NVMe SSD Drive 256GB                         | 4         | 0.45%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB               | 4         | 0.45%   |
| Seagate ST2000LM015-2E8174 2TB                       | 4         | 0.45%   |
| Seagate Expansion 1TB                                | 4         | 0.45%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 4         | 0.45%   |
| SanDisk NVMe SSD Drive 512GB                         | 4         | 0.45%   |
| Samsung SSD 840 EVO 250GB                            | 4         | 0.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 4         | 0.45%   |
| Samsung MZVLB512HAJQ-000L7 512GB                     | 4         | 0.45%   |
| PNY CS900 120GB SSD                                  | 4         | 0.45%   |
| Kingston SV300S37A240G 240GB SSD                     | 4         | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                     | 4         | 0.45%   |
| HGST HTS545050A7E380 500GB                           | 4         | 0.45%   |
| Apple SSD SM0256F 256GB                              | 4         | 0.45%   |
| WDC WD2500BEVT-60ZCT1 250GB                          | 3         | 0.34%   |
| WDC WD10JPVX-75JC3T0 1TB                             | 3         | 0.34%   |
| Verbatim Vi550 S3 1TB SSD                            | 3         | 0.34%   |
| Toshiba THNSFJ256GCSU 256GB SSD                      | 3         | 0.34%   |
| SK hynix PC401 NVMe Solid State Drive 256GB          | 3         | 0.34%   |
| SK hynix NVMe SSD Drive 256GB                        | 3         | 0.34%   |
| SK hynix HFM512GD3JX013N 512GB                       | 3         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 56        | 65     | 33.73%  |
| WDC                 | 40        | 54     | 24.1%   |
| Hitachi             | 28        | 34     | 16.87%  |
| HGST                | 18        | 23     | 10.84%  |
| Toshiba             | 17        | 18     | 10.24%  |
| Fujitsu             | 2         | 3      | 1.2%    |
| Apple               | 2         | 3      | 1.2%    |
| TO Exter            | 1         | 1      | 0.6%    |
| Samsung Electronics | 1         | 1      | 0.6%    |
| Apricorn            | 1         | 2      | 0.6%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 111       | 135    | 34.15%  |
| Kingston            | 47        | 67     | 14.46%  |
| SanDisk             | 21        | 26     | 6.46%   |
| Apple               | 16        | 17     | 4.92%   |
| Toshiba             | 15        | 17     | 4.62%   |
| WDC                 | 12        | 15     | 3.69%   |
| SK hynix            | 11        | 13     | 3.38%   |
| LITEON              | 10        | 23     | 3.08%   |
| Intel               | 10        | 12     | 3.08%   |
| PNY                 | 9         | 9      | 2.77%   |
| Crucial             | 9         | 9      | 2.77%   |
| Micron Technology   | 8         | 9      | 2.46%   |
| Intenso             | 7         | 9      | 2.15%   |
| LITEONIT            | 6         | 8      | 1.85%   |
| Verbatim            | 5         | 9      | 1.54%   |
| A-DATA Technology   | 5         | 5      | 1.54%   |
| OCZ                 | 4         | 4      | 1.23%   |
| China               | 4         | 5      | 1.23%   |
| USB3.0              | 2         | 2      | 0.62%   |
| Team                | 1         | 1      | 0.31%   |
| SPCC                | 1         | 1      | 0.31%   |
| Plextor             | 1         | 1      | 0.31%   |
| Patriot             | 1         | 1      | 0.31%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.31%   |
| KingFast            | 1         | 1      | 0.31%   |
| KingDian            | 1         | 1      | 0.31%   |
| Kingchuxing         | 1         | 1      | 0.31%   |
| KING                | 1         | 1      | 0.31%   |
| GOODRAM             | 1         | 1      | 0.31%   |
| Dogfish             | 1         | 1      | 0.31%   |
| Corsair             | 1         | 1      | 0.31%   |
| ASUS-PHISON         | 1         | 1      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 305       | 407    | 37.56%  |
| NVMe    | 297       | 428    | 36.58%  |
| HDD     | 160       | 204    | 19.7%   |
| MMC     | 45        | 54     | 5.54%   |
| Unknown | 5         | 5      | 0.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 426       | 590    | 53.86%  |
| NVMe | 297       | 428    | 37.55%  |
| MMC  | 45        | 54     | 5.69%   |
| SAS  | 23        | 26     | 2.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 342       | 465    | 73.39%  |
| 0.51-1.0   | 99        | 117    | 21.24%  |
| 1.01-2.0   | 19        | 22     | 4.08%   |
| 3.01-4.0   | 3         | 3      | 0.64%   |
| 4.01-10.0  | 3         | 4      | 0.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 235       | 31%     |
| 251-500        | 182       | 24.01%  |
| 501-1000       | 113       | 14.91%  |
| 1-20           | 48        | 6.33%   |
| 1001-2000      | 44        | 5.8%    |
| 51-100         | 42        | 5.54%   |
| Unknown        | 35        | 4.62%   |
| 21-50          | 28        | 3.69%   |
| More than 3000 | 17        | 2.24%   |
| 2001-3000      | 14        | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 306       | 38.98%  |
| 21-50          | 135       | 17.2%   |
| 101-250        | 98        | 12.48%  |
| 51-100         | 91        | 11.59%  |
| 251-500        | 69        | 8.79%   |
| Unknown        | 35        | 4.46%   |
| 501-1000       | 34        | 4.33%   |
| 1001-2000      | 9         | 1.15%   |
| More than 3000 | 4         | 0.51%   |
| 2001-3000      | 4         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 7.14%   |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 7.14%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 3.57%   |
| WDC WD5000BPVT-80HXZT3 500GB          | 1         | 1      | 3.57%   |
| WDC WD5000BEVT-35ZAT0 500GB           | 1         | 1      | 3.57%   |
| WDC WD1600BEVT-00M9YT0 160GB          | 1         | 2      | 3.57%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 3.57%   |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 3.57%   |
| Toshiba KSG60ZSE256G SATA 256GB SSD   | 1         | 1      | 3.57%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 3.57%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 3.57%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 3.57%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 3.57%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 3.57%   |
| SanDisk SSD U100 24GB                 | 1         | 1      | 3.57%   |
| Micron Technology 1100 SATA 512GB SSD | 1         | 1      | 3.57%   |
| Kingston SHPM2280P2H 480G SSD         | 1         | 1      | 3.57%   |
| Kingston SA400S37480G 480GB SSD       | 1         | 1      | 3.57%   |
| Intel SSD 600P Series 256GB           | 1         | 1      | 3.57%   |
| Hitachi HTS725032A9A364 320GB         | 1         | 1      | 3.57%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 3.57%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 3.57%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 3.57%   |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 3.57%   |
| Apple HDD HTS547550A9E384 500GB       | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 21.43%  |
| HGST              | 5         | 5      | 17.86%  |
| WDC               | 4         | 5      | 14.29%  |
| Toshiba           | 3         | 3      | 10.71%  |
| SK hynix          | 2         | 2      | 7.14%   |
| Kingston          | 2         | 2      | 7.14%   |
| Hitachi           | 2         | 2      | 7.14%   |
| SanDisk           | 1         | 1      | 3.57%   |
| Micron Technology | 1         | 1      | 3.57%   |
| Intel             | 1         | 1      | 3.57%   |
| Apple             | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 33.33%  |
| HGST    | 5         | 5      | 27.78%  |
| WDC     | 3         | 4      | 16.67%  |
| Hitachi | 2         | 2      | 11.11%  |
| Toshiba | 1         | 1      | 5.56%   |
| Apple   | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 19     | 64.29%  |
| SSD  | 8         | 8      | 28.57%  |
| NVMe | 2         | 2      | 7.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 475       | 740    | 62.66%  |
| Works    | 254       | 328    | 33.51%  |
| Malfunc  | 28        | 29     | 3.69%   |
| Failed   | 1         | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 435       | 52.92%  |
| Samsung Electronics              | 121       | 14.72%  |
| AMD                              | 63        | 7.66%   |
| SanDisk                          | 44        | 5.35%   |
| SK hynix                         | 41        | 4.99%   |
| Micron Technology                | 25        | 3.04%   |
| Toshiba America Info Systems     | 22        | 2.68%   |
| Kingston Technology Company      | 14        | 1.7%    |
| Nvidia                           | 10        | 1.22%   |
| Phison Electronics               | 7         | 0.85%   |
| KIOXIA                           | 7         | 0.85%   |
| Silicon Motion                   | 5         | 0.61%   |
| Lenovo                           | 5         | 0.61%   |
| ADATA Technology                 | 4         | 0.49%   |
| Marvell Technology Group         | 3         | 0.36%   |
| Apple                            | 3         | 0.36%   |
| Union Memory (Shenzhen)          | 2         | 0.24%   |
| Solid State Storage Technology   | 2         | 0.24%   |
| Micron/Crucial Technology        | 2         | 0.24%   |
| Lite-On Technology               | 2         | 0.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.12%   |
| JMicron Technology               | 1         | 0.12%   |
| Biwin Storage Technology         | 1         | 0.12%   |
| ASMedia Technology               | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 58        | 6.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 55        | 6.22%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 53        | 6%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 48        | 5.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 42        | 4.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 39        | 4.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 25        | 2.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 24        | 2.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 24        | 2.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 20        | 2.26%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 19        | 2.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 19        | 2.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 17        | 1.92%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 17        | 1.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 1.81%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 13        | 1.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 13        | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 1.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 12        | 1.36%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 12        | 1.36%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 11        | 1.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 11        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 10        | 1.13%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 8         | 0.9%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 7         | 0.79%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 7         | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                            | 7         | 0.79%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 6         | 0.68%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 6         | 0.68%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 6         | 0.68%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 6         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 6         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 6         | 0.68%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 5         | 0.57%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 5         | 0.57%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 5         | 0.57%   |
| Intel SSD 660P Series                                                          | 5         | 0.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 0.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 5         | 0.57%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 5         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 450       | 53.76%  |
| NVMe | 298       | 35.6%   |
| IDE  | 47        | 5.62%   |
| RAID | 42        | 5.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 575       | 80.42%  |
| AMD          | 139       | 19.44%  |
| CentaurHauls | 1         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 17        | 2.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 16        | 2.24%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 11        | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 11        | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 10        | 1.4%    |
| Intel Core i5-4300U CPU @ 1.90GHz           | 10        | 1.4%    |
| Intel Core i5-2520M CPU @ 2.50GHz           | 10        | 1.4%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 9         | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 9         | 1.26%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 9         | 1.26%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 9         | 1.26%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 9         | 1.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 9         | 1.26%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 8         | 1.12%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 8         | 1.12%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 8         | 1.12%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 7         | 0.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 7         | 0.98%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 7         | 0.98%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 6         | 0.84%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 6         | 0.84%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 6         | 0.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 6         | 0.84%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 6         | 0.84%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 6         | 0.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 6         | 0.84%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 6         | 0.84%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 6         | 0.84%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 6         | 0.84%   |
| AMD Custom APU 0405                         | 6         | 0.84%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 5         | 0.7%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 5         | 0.7%    |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 5         | 0.7%    |
| Intel Core i5-8300H CPU @ 2.30GHz           | 5         | 0.7%    |
| Intel Core i5-7300U CPU @ 2.60GHz           | 5         | 0.7%    |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 5         | 0.7%    |
| AMD Ryzen 9 5900HS with Radeon Graphics     | 5         | 0.7%    |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics  | 5         | 0.7%    |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 4         | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 214       | 29.93%  |
| Intel Core i7                  | 190       | 26.57%  |
| Other                          | 53        | 7.41%   |
| AMD Ryzen 7                    | 30        | 4.2%    |
| Intel Core i3                  | 28        | 3.92%   |
| Intel Core 2 Duo               | 28        | 3.92%   |
| AMD Ryzen 5                    | 20        | 2.8%    |
| Intel Celeron                  | 19        | 2.66%   |
| AMD Ryzen 7 PRO                | 18        | 2.52%   |
| Intel Pentium                  | 12        | 1.68%   |
| AMD Ryzen 9                    | 11        | 1.54%   |
| Intel Atom                     | 9         | 1.26%   |
| Intel Pentium Dual-Core        | 7         | 0.98%   |
| AMD Ryzen 5 PRO                | 7         | 0.98%   |
| AMD A6                         | 7         | 0.98%   |
| Intel Core i9                  | 5         | 0.7%    |
| AMD A8                         | 5         | 0.7%    |
| AMD Turion 64 X2 Mobile        | 4         | 0.56%   |
| AMD Ryzen 3                    | 4         | 0.56%   |
| AMD E1                         | 4         | 0.56%   |
| Intel Pentium Silver           | 3         | 0.42%   |
| Intel Pentium M                | 3         | 0.42%   |
| AMD E                          | 3         | 0.42%   |
| AMD Athlon                     | 3         | 0.42%   |
| AMD A4                         | 3         | 0.42%   |
| AMD A10                        | 3         | 0.42%   |
| Intel Pentium Dual             | 2         | 0.28%   |
| Intel Genuine                  | 2         | 0.28%   |
| Intel Core m3                  | 2         | 0.28%   |
| Intel Core 2                   | 2         | 0.28%   |
| Intel Core                     | 2         | 0.28%   |
| Intel Core m7                  | 1         | 0.14%   |
| Intel Core M                   | 1         | 0.14%   |
| Intel Celeron M                | 1         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.14%   |
| AMD Ryzen 3 PRO                | 1         | 0.14%   |
| AMD FX                         | 1         | 0.14%   |
| AMD E2                         | 1         | 0.14%   |
| AMD Athlon X2                  | 1         | 0.14%   |
| AMD Athlon Neo                 | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 343       | 47.97%  |
| 4      | 225       | 31.47%  |
| 8      | 67        | 9.37%   |
| 6      | 46        | 6.43%   |
| 1      | 16        | 2.24%   |
| 12     | 6         | 0.84%   |
| 10     | 6         | 0.84%   |
| 14     | 3         | 0.42%   |
| 16     | 2         | 0.28%   |
| 24     | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 714       | 99.86%  |
| 2      | 1         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 578       | 80.84%  |
| 1      | 136       | 19.02%  |
| 4      | 1         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 698       | 97.35%  |
| Unknown        | 13        | 1.81%   |
| 32-bit         | 6         | 0.84%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 312       | 41.71%  |
| 0x306a9    | 31        | 4.14%   |
| 0x40651    | 30        | 4.01%   |
| 0x206a7    | 28        | 3.74%   |
| 0x406e3    | 24        | 3.21%   |
| 0x906ea    | 19        | 2.54%   |
| 0x806ea    | 19        | 2.54%   |
| 0x806e9    | 19        | 2.54%   |
| 0x306c3    | 19        | 2.54%   |
| 0x1067a    | 19        | 2.54%   |
| 0x806ec    | 16        | 2.14%   |
| 0x20655    | 15        | 2.01%   |
| 0x0a50000c | 12        | 1.6%    |
| 0x806c1    | 11        | 1.47%   |
| 0x906e9    | 9         | 1.2%    |
| 0x08600106 | 9         | 1.2%    |
| 0x906ed    | 6         | 0.8%    |
| 0x806eb    | 6         | 0.8%    |
| 0x20652    | 6         | 0.8%    |
| 0x0a404102 | 6         | 0.8%    |
| 0x08600104 | 6         | 0.8%    |
| 0x706e5    | 5         | 0.67%   |
| 0x6fd      | 5         | 0.67%   |
| 0x506e3    | 5         | 0.67%   |
| 0x406c3    | 5         | 0.67%   |
| 0x306d4    | 5         | 0.67%   |
| 0x30678    | 5         | 0.67%   |
| 0x08608103 | 5         | 0.67%   |
| 0x08108102 | 5         | 0.67%   |
| 0x07030105 | 5         | 0.67%   |
| 0x10676    | 4         | 0.53%   |
| 0x08108109 | 4         | 0.53%   |
| 0x0810100b | 4         | 0.53%   |
| 0xa0652    | 3         | 0.4%    |
| 0x706a1    | 3         | 0.4%    |
| 0x6fb      | 3         | 0.4%    |
| 0x6d8      | 3         | 0.4%    |
| 0x406c4    | 3         | 0.4%    |
| 0x40661    | 3         | 0.4%    |
| 0x906a3    | 2         | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 154       | 21.54%  |
| Haswell           | 78        | 10.91%  |
| Skylake           | 55        | 7.69%   |
| IvyBridge         | 49        | 6.85%   |
| SandyBridge       | 48        | 6.71%   |
| Unknown           | 44        | 6.15%   |
| Penryn            | 29        | 4.06%   |
| Westmere          | 28        | 3.92%   |
| TigerLake         | 25        | 3.5%    |
| Zen 3             | 22        | 3.08%   |
| Zen 2             | 22        | 3.08%   |
| Broadwell         | 21        | 2.94%   |
| Zen+              | 16        | 2.24%   |
| Silvermont        | 15        | 2.1%    |
| Core              | 15        | 2.1%    |
| Alderlake Hybrid  | 11        | 1.54%   |
| CometLake         | 10        | 1.4%    |
| IceLake           | 8         | 1.12%   |
| Excavator         | 7         | 0.98%   |
| Puma              | 6         | 0.84%   |
| Goldmont plus     | 6         | 0.84%   |
| P6                | 5         | 0.7%    |
| K8 Hammer         | 5         | 0.7%    |
| Bobcat            | 5         | 0.7%    |
| Zen               | 4         | 0.56%   |
| Bonnell           | 4         | 0.56%   |
| Steamroller       | 3         | 0.42%   |
| Piledriver        | 3         | 0.42%   |
| K8 & K10 hybrid   | 3         | 0.42%   |
| K10               | 3         | 0.42%   |
| Goldmont          | 3         | 0.42%   |
| Nehalem           | 2         | 0.28%   |
| K10 Llano         | 2         | 0.28%   |
| Jaguar            | 2         | 0.28%   |
| Meteorlake Hybrid | 1         | 0.14%   |
| Lunarlake Hybrid  | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 519       | 57.73%  |
| Nvidia                           | 208       | 23.14%  |
| AMD                              | 170       | 18.91%  |
| Zhaoxin                          | 1         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 5.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 46        | 4.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 46        | 4.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 39        | 4.22%   |
| Intel UHD Graphics 620                                                                   | 36        | 3.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 31        | 3.35%   |
| Intel HD Graphics 620                                                                    | 27        | 2.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 2.49%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 22        | 2.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 2.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 2.05%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 19        | 2.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 1.62%   |
| Intel HD Graphics 630                                                                    | 15        | 1.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.62%   |
| Intel HD Graphics 5500                                                                   | 13        | 1.41%   |
| AMD Rembrandt [Radeon 680M]                                                              | 13        | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 12        | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.19%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.08%   |
| Intel HD Graphics 530                                                                    | 9         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 0.97%   |
| AMD Lucienne                                                                             | 9         | 0.97%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.65%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 6         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.54%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 5         | 0.54%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 5         | 0.54%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.54%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.54%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.43%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 4         | 0.43%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 4         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 352       | 48.96%  |
| Intel + Nvidia | 142       | 19.75%  |
| 1 x AMD        | 115       | 15.99%  |
| 1 x Nvidia     | 47        | 6.54%   |
| Intel + AMD    | 22        | 3.06%   |
| AMD + Nvidia   | 18        | 2.5%    |
| 2 x AMD        | 16        | 2.23%   |
| 2 x Intel      | 3         | 0.42%   |
| Other          | 2         | 0.28%   |
| 1 x Zhaoxin    | 1         | 0.14%   |
| 1 x SiS        | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 597       | 82.57%  |
| Proprietary | 104       | 14.38%  |
| Unknown     | 22        | 3.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 491       | 67.54%  |
| 0.01-0.5   | 82        | 11.28%  |
| 1.01-2.0   | 69        | 9.49%   |
| 0.51-1.0   | 36        | 4.95%   |
| 3.01-4.0   | 29        | 3.99%   |
| 5.01-6.0   | 11        | 1.51%   |
| 7.01-8.0   | 6         | 0.83%   |
| 2.01-3.0   | 2         | 0.28%   |
| 8.01-16.0  | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 164       | 19.62%  |
| LG Display              | 122       | 14.59%  |
| BOE                     | 98        | 11.72%  |
| Chimei Innolux          | 91        | 10.89%  |
| Samsung Electronics     | 73        | 8.73%   |
| Lenovo                  | 46        | 5.5%    |
| Apple                   | 41        | 4.9%    |
| Sharp                   | 26        | 3.11%   |
| Dell                    | 26        | 3.11%   |
| Hewlett-Packard         | 15        | 1.79%   |
| Chi Mei Optoelectronics | 15        | 1.79%   |
| Philips                 | 12        | 1.44%   |
| PANDA                   | 11        | 1.32%   |
| AOC                     | 9         | 1.08%   |
| InfoVision              | 7         | 0.84%   |
| Goldstar                | 7         | 0.84%   |
| CSO                     | 7         | 0.84%   |
| Valve                   | 5         | 0.6%    |
| BenQ                    | 5         | 0.6%    |
| Panasonic               | 4         | 0.48%   |
| MSI                     | 4         | 0.48%   |
| LG Philips              | 4         | 0.48%   |
| ASUSTek Computer        | 4         | 0.48%   |
| Sony                    | 3         | 0.36%   |
| Ancor Communications    | 3         | 0.36%   |
| Acer                    | 3         | 0.36%   |
| TMX                     | 2         | 0.24%   |
| Seiko/Epson             | 2         | 0.24%   |
| Packard Bell            | 2         | 0.24%   |
| LGD                     | 2         | 0.24%   |
| IBM                     | 2         | 0.24%   |
| HKC                     | 2         | 0.24%   |
| CPT                     | 2         | 0.24%   |
| ViewSonic               | 1         | 0.12%   |
| Vestel Elektronik       | 1         | 0.12%   |
| Toshiba                 | 1         | 0.12%   |
| Tianma XM               | 1         | 0.12%   |
| RTK                     | 1         | 0.12%   |
| PVT                     | 1         | 0.12%   |
| Lenovo Group Limited    | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 11        | 1.29%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 10        | 1.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 8         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 7         | 0.82%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 7         | 0.82%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.7%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 6         | 0.7%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 5         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 5         | 0.59%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.47%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 4         | 0.47%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch           | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch           | 4         | 0.47%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                    | 4         | 0.47%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 3         | 0.35%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 3         | 0.35%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 3         | 0.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.35%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 3         | 0.35%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 3         | 0.35%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 3         | 0.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.35%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 3         | 0.35%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 3         | 0.35%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch         | 3         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 3         | 0.35%   |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch                    | 3         | 0.35%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 3         | 0.35%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 3         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 354       | 44.75%  |
| 1366x768 (WXGA)    | 125       | 15.8%   |
| 1600x900 (HD+)     | 58        | 7.33%   |
| 3840x2160 (4K)     | 54        | 6.83%   |
| 2560x1440 (QHD)    | 37        | 4.68%   |
| 1280x800 (WXGA)    | 28        | 3.54%   |
| 1920x1200 (WUXGA)  | 24        | 3.03%   |
| 2560x1600          | 20        | 2.53%   |
| 1440x900 (WXGA+)   | 17        | 2.15%   |
| 2880x1800          | 15        | 1.9%    |
| 1680x1050 (WSXGA+) | 15        | 1.9%    |
| 800x1280           | 6         | 0.76%   |
| 3440x1440          | 5         | 0.63%   |
| 3200x1800 (QHD+)   | 4         | 0.51%   |
| 1280x1024 (SXGA)   | 4         | 0.51%   |
| 2240x1400          | 3         | 0.38%   |
| 1400x1050          | 3         | 0.38%   |
| 3840x2400          | 2         | 0.25%   |
| 3840x1100          | 2         | 0.25%   |
| 3000x2000          | 2         | 0.25%   |
| 2256x1504          | 2         | 0.25%   |
| 1920x540           | 2         | 0.25%   |
| 1024x600           | 2         | 0.25%   |
| 3840x1600          | 1         | 0.13%   |
| 3840x1080          | 1         | 0.13%   |
| 3072x1920          | 1         | 0.13%   |
| 2160x1440          | 1         | 0.13%   |
| 1920x515           | 1         | 0.13%   |
| 1360x768           | 1         | 0.13%   |
| Unknown            | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 289       | 34.49%  |
| 14      | 141       | 16.83%  |
| 13      | 136       | 16.23%  |
| 17      | 54        | 6.44%   |
| 27      | 38        | 4.53%   |
| 12      | 31        | 3.7%    |
| 24      | 30        | 3.58%   |
| 31      | 16        | 1.91%   |
| 23      | 15        | 1.79%   |
| Unknown | 13        | 1.55%   |
| 16      | 11        | 1.31%   |
| 22      | 8         | 0.95%   |
| 21      | 6         | 0.72%   |
| 18      | 6         | 0.72%   |
| 84      | 5         | 0.6%    |
| 34      | 5         | 0.6%    |
| 11      | 5         | 0.6%    |
| 7       | 5         | 0.6%    |
| 19      | 4         | 0.48%   |
| 72      | 3         | 0.36%   |
| 25      | 3         | 0.36%   |
| 10      | 3         | 0.36%   |
| 32      | 2         | 0.24%   |
| 20      | 2         | 0.24%   |
| 85      | 1         | 0.12%   |
| 74      | 1         | 0.12%   |
| 57      | 1         | 0.12%   |
| 49      | 1         | 0.12%   |
| 37      | 1         | 0.12%   |
| 29      | 1         | 0.12%   |
| 3       | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 489       | 59.06%  |
| 201-300     | 114       | 13.77%  |
| 501-600     | 75        | 9.06%   |
| 351-400     | 66        | 7.97%   |
| 601-700     | 24        | 2.9%    |
| 401-500     | 21        | 2.54%   |
| Unknown     | 13        | 1.57%   |
| 1501-2000   | 10        | 1.21%   |
| 701-800     | 7         | 0.85%   |
| 1-100       | 6         | 0.72%   |
| 1001-1500   | 2         | 0.24%   |
| 801-900     | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 577       | 77.24%  |
| 16/10   | 129       | 17.27%  |
| Unknown | 9         | 1.2%    |
| 3/2     | 8         | 1.07%   |
| 21/9    | 6         | 0.8%    |
| 0.67    | 5         | 0.67%   |
| 5/4     | 3         | 0.4%    |
| 4/3     | 3         | 0.4%    |
| 6/5     | 2         | 0.27%   |
| 32/9    | 2         | 0.27%   |
| 3.40    | 2         | 0.27%   |
| 3.73    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 287       | 34.54%  |
| 81-90          | 222       | 26.71%  |
| 71-80          | 53        | 6.38%   |
| 201-250        | 43        | 5.17%   |
| 121-130        | 42        | 5.05%   |
| 301-350        | 38        | 4.57%   |
| 61-70          | 28        | 3.37%   |
| 351-500        | 22        | 2.65%   |
| 251-300        | 14        | 1.68%   |
| Unknown        | 13        | 1.56%   |
| 131-140        | 12        | 1.44%   |
| More than 1000 | 11        | 1.32%   |
| 111-120        | 11        | 1.32%   |
| 51-60          | 7         | 0.84%   |
| 151-200        | 7         | 0.84%   |
| 141-150        | 7         | 0.84%   |
| 1-40           | 6         | 0.72%   |
| 41-50          | 3         | 0.36%   |
| 91-100         | 3         | 0.36%   |
| 501-1000       | 2         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 376       | 46.08%  |
| 101-120       | 180       | 22.06%  |
| 51-100        | 109       | 13.36%  |
| 161-240       | 90        | 11.03%  |
| More than 240 | 42        | 5.15%   |
| Unknown       | 13        | 1.59%   |
| 1-50          | 6         | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 588       | 79.46%  |
| 2     | 116       | 15.68%  |
| 3     | 20        | 2.7%    |
| 0     | 13        | 1.76%   |
| 4     | 3         | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 439       | 40.09%  |
| Realtek Semiconductor                  | 295       | 26.94%  |
| Qualcomm Atheros                       | 121       | 11.05%  |
| Broadcom                               | 69        | 6.3%    |
| Broadcom Limited                       | 21        | 1.92%   |
| MediaTek                               | 19        | 1.74%   |
| Lenovo                                 | 18        | 1.64%   |
| Sierra Wireless                        | 17        | 1.55%   |
| Ericsson Business Mobile Networks      | 14        | 1.28%   |
| Qualcomm                               | 9         | 0.82%   |
| Ralink                                 | 8         | 0.73%   |
| Nvidia                                 | 8         | 0.73%   |
| Samsung Electronics                    | 6         | 0.55%   |
| Dell                                   | 6         | 0.55%   |
| Marvell Technology Group               | 5         | 0.46%   |
| DisplayLink                            | 5         | 0.46%   |
| TP-Link                                | 4         | 0.37%   |
| ASIX Electronics                       | 4         | 0.37%   |
| Xiaomi                                 | 3         | 0.27%   |
| Ralink Technology                      | 3         | 0.27%   |
| NetGear                                | 2         | 0.18%   |
| Hewlett-Packard                        | 2         | 0.18%   |
| D-Link System                          | 2         | 0.18%   |
| ZyXEL Communications                   | 1         | 0.09%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.09%   |
| Philips (or NXP)                       | 1         | 0.09%   |
| OPPO Electronics                       | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.09%   |
| Linksys                                | 1         | 0.09%   |
| ICS Advent                             | 1         | 0.09%   |
| Huawei Technologies                    | 1         | 0.09%   |
| Google                                 | 1         | 0.09%   |
| Fibocom                                | 1         | 0.09%   |
| Edimax Technology                      | 1         | 0.09%   |
| ASUSTek Computer                       | 1         | 0.09%   |
| Aquantia                               | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 185       | 13.2%   |
| Intel Wireless 8265 / 8275                                             | 49        | 3.5%    |
| Intel Wi-Fi 6 AX200                                                    | 45        | 3.21%   |
| Intel Wireless 7260                                                    | 40        | 2.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 39        | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 2.71%   |
| Intel Wireless 8260                                                    | 34        | 2.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 32        | 2.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 30        | 2.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 26        | 1.85%   |
| Intel Wireless 7265                                                    | 24        | 1.71%   |
| Intel Ethernet Connection (4) I219-LM                                  | 24        | 1.71%   |
| Intel Ethernet Connection I218-LM                                      | 19        | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 18        | 1.28%   |
| Intel Wi-Fi 6 AX201                                                    | 18        | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 16        | 1.14%   |
| Intel Ethernet Connection I219-LM                                      | 15        | 1.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 15        | 1.07%   |
| Intel Ethernet Connection (4) I219-V                                   | 14        | 1%      |
| Intel Centrino Ultimate-N 6300                                         | 14        | 1%      |
| Intel Centrino Wireless-N 2230                                         | 13        | 0.93%   |
| Intel 82577LM Gigabit Network Connection                               | 13        | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 12        | 0.86%   |
| Intel Ethernet Connection I217-LM                                      | 12        | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 12        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 12        | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 11        | 0.78%   |
| Intel Ethernet Connection I219-V                                       | 11        | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 11        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 10        | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 10        | 0.71%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 10        | 0.71%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 10        | 0.71%   |
| Sierra Wireless EM7455                                                 | 9         | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 9         | 0.64%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 9         | 0.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 9         | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 0.64%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 9         | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 428       | 57.6%   |
| Qualcomm Atheros      | 94        | 12.65%  |
| Realtek Semiconductor | 79        | 10.63%  |
| Broadcom              | 55        | 7.4%    |
| Sierra Wireless       | 17        | 2.29%   |
| MediaTek              | 17        | 2.29%   |
| Broadcom Limited      | 17        | 2.29%   |
| Ralink                | 8         | 1.08%   |
| Qualcomm              | 8         | 1.08%   |
| TP-Link               | 4         | 0.54%   |
| Dell                  | 4         | 0.54%   |
| Ralink Technology     | 3         | 0.4%    |
| NetGear               | 2         | 0.27%   |
| D-Link System         | 2         | 0.27%   |
| ZyXEL Communications  | 1         | 0.13%   |
| Philips (or NXP)      | 1         | 0.13%   |
| Fibocom               | 1         | 0.13%   |
| Edimax Technology     | 1         | 0.13%   |
| ASUSTek Computer      | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 49        | 6.59%   |
| Intel Wi-Fi 6 AX200                                                  | 45        | 6.06%   |
| Intel Wireless 7260                                                  | 40        | 5.38%   |
| Intel Wireless 8260                                                  | 34        | 4.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 30        | 4.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 26        | 3.5%    |
| Intel Wireless 7265                                                  | 24        | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 18        | 2.42%   |
| Intel Wi-Fi 6 AX201                                                  | 18        | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 16        | 2.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 15        | 2.02%   |
| Intel Centrino Ultimate-N 6300                                       | 14        | 1.88%   |
| Intel Centrino Wireless-N 2230                                       | 13        | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 12        | 1.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 12        | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 12        | 1.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 11        | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 11        | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 10        | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 10        | 1.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 10        | 1.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 10        | 1.35%   |
| Sierra Wireless EM7455                                               | 9         | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 9         | 1.21%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 9         | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 9         | 1.21%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 9         | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 8         | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 8         | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 8         | 1.08%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                        | 7         | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 7         | 0.94%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 7         | 0.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 7         | 0.94%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 7         | 0.94%   |
| Intel Centrino Advanced-N 6200                                       | 7         | 0.94%   |
| Intel Wireless 3165                                                  | 6         | 0.81%   |
| Intel Wireless 3160                                                  | 6         | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 6         | 0.81%   |
| Intel Centrino Advanced-N 6235                                       | 6         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 263       | 41.81%  |
| Intel                                  | 232       | 36.88%  |
| Qualcomm Atheros                       | 40        | 6.36%   |
| Broadcom                               | 31        | 4.93%   |
| Lenovo                                 | 18        | 2.86%   |
| Nvidia                                 | 8         | 1.27%   |
| Marvell Technology Group               | 5         | 0.79%   |
| DisplayLink                            | 5         | 0.79%   |
| Samsung Electronics                    | 4         | 0.64%   |
| Broadcom Limited                       | 4         | 0.64%   |
| ASIX Electronics                       | 4         | 0.64%   |
| Xiaomi                                 | 3         | 0.48%   |
| MediaTek                               | 2         | 0.32%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.16%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.16%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.16%   |
| Qualcomm                               | 1         | 0.16%   |
| OPPO Electronics                       | 1         | 0.16%   |
| Linksys                                | 1         | 0.16%   |
| ICS Advent                             | 1         | 0.16%   |
| Hewlett-Packard                        | 1         | 0.16%   |
| Google                                 | 1         | 0.16%   |
| Aquantia                               | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 185       | 29.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 39        | 6.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 5.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 32        | 5.02%   |
| Intel Ethernet Connection (4) I219-LM                                  | 24        | 3.77%   |
| Intel Ethernet Connection I218-LM                                      | 19        | 2.98%   |
| Intel Ethernet Connection I219-LM                                      | 15        | 2.35%   |
| Intel Ethernet Connection (4) I219-V                                   | 14        | 2.2%    |
| Intel 82577LM Gigabit Network Connection                               | 13        | 2.04%   |
| Intel Ethernet Connection I217-LM                                      | 12        | 1.88%   |
| Intel Ethernet Connection I219-V                                       | 11        | 1.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 1.41%   |
| Intel Ethernet Connection (7) I219-LM                                  | 7         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                                   | 7         | 1.1%    |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 1.1%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.94%   |
| Lenovo ThinkPad Lan                                                    | 6         | 0.94%   |
| Intel Ethernet Connection (6) I219-LM                                  | 6         | 0.94%   |
| Intel Ethernet Connection (10) I219-V                                  | 6         | 0.94%   |
| Intel 82566MM Gigabit Network Connection                               | 6         | 0.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 5         | 0.78%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 5         | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 0.78%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 5         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 4         | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4         | 0.63%   |
| Lenovo USB-C Dock Ethernet                                             | 4         | 0.63%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.63%   |
| Intel Ethernet Connection (13) I219-V                                  | 4         | 0.63%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 4         | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.63%   |
| Realtek PCIe GbE Family Controller                                     | 3         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 0.47%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 703       | 53.46%  |
| Ethernet | 590       | 44.87%  |
| Modem    | 21        | 1.6%    |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 594       | 77.75%  |
| Ethernet | 170       | 22.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 534       | 74.37%  |
| 1     | 170       | 23.68%  |
| 3     | 9         | 1.25%   |
| 0     | 5         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 676       | 94.15%  |
| Yes  | 42        | 5.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 333       | 54.68%  |
| Broadcom                        | 51        | 8.37%   |
| Realtek Semiconductor           | 45        | 7.39%   |
| Qualcomm Atheros Communications | 34        | 5.58%   |
| Apple                           | 31        | 5.09%   |
| IMC Networks                    | 27        | 4.43%   |
| Lite-On Technology              | 25        | 4.11%   |
| Foxconn / Hon Hai               | 24        | 3.94%   |
| Hewlett-Packard                 | 11        | 1.81%   |
| USI                             | 5         | 0.82%   |
| Dell                            | 4         | 0.66%   |
| Cambridge Silicon Radio         | 4         | 0.66%   |
| ASUSTek Computer                | 3         | 0.49%   |
| Realtek                         | 2         | 0.33%   |
| Ralink Technology               | 2         | 0.33%   |
| Ralink                          | 2         | 0.33%   |
| Toshiba                         | 1         | 0.16%   |
| Taiyo Yuden                     | 1         | 0.16%   |
| MediaTek                        | 1         | 0.16%   |
| Foxconn International           | 1         | 0.16%   |
| D-Link System                   | 1         | 0.16%   |
| Chicony Electronics             | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 159       | 26.11%  |
| Intel AX200 Bluetooth                               | 44        | 7.22%   |
| Intel AX201 Bluetooth                               | 39        | 6.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 34        | 5.58%   |
| Realtek Bluetooth Radio                             | 26        | 4.27%   |
| Broadcom BCM2045B (BDC-2.1)                         | 23        | 3.78%   |
| Apple Bluetooth Host Controller                     | 21        | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 3.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 2.13%   |
| Intel AX211 Bluetooth                               | 12        | 1.97%   |
| IMC Networks Wireless_Device                        | 12        | 1.97%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 1.81%   |
| IMC Networks Bluetooth Radio                        | 11        | 1.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 1.81%   |
| Intel AX210 Bluetooth                               | 10        | 1.64%   |
| Apple Bluetooth USB Host Controller                 | 10        | 1.64%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 1.31%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 1.31%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 1.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 1.15%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.99%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.99%   |
| USI Bluetooth Device                                | 5         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.82%   |
| Lite-On Bluetooth Device                            | 5         | 0.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 0.82%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 5         | 0.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 0.66%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.66%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.49%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.49%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.49%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 3         | 0.49%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.49%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 3         | 0.49%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.33%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.33%   |
| Realtek Bluetooth Radio                             | 2         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 561       | 61.38%  |
| AMD                              | 148       | 16.19%  |
| Nvidia                           | 126       | 13.79%  |
| Lenovo                           | 15        | 1.64%   |
| GN Netcom                        | 8         | 0.88%   |
| Hewlett-Packard                  | 6         | 0.66%   |
| Realtek Semiconductor            | 5         | 0.55%   |
| Logitech                         | 5         | 0.55%   |
| Plantronics                      | 3         | 0.33%   |
| Kingston Technology              | 3         | 0.33%   |
| C-Media Electronics              | 3         | 0.33%   |
| XMOS                             | 2         | 0.22%   |
| Trust                            | 2         | 0.22%   |
| Razer USA                        | 2         | 0.22%   |
| Generalplus Technology           | 2         | 0.22%   |
| DSEA A/S                         | 2         | 0.22%   |
| Zhaoxin                          | 1         | 0.11%   |
| VIA Technologies                 | 1         | 0.11%   |
| Texas Instruments                | 1         | 0.11%   |
| SteelSeries ApS                  | 1         | 0.11%   |
| Sony                             | 1         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |
| Samson Technologies              | 1         | 0.11%   |
| RODE Microphones                 | 1         | 0.11%   |
| Project DAC DS                   | 1         | 0.11%   |
| OPPO Electronics                 | 1         | 0.11%   |
| NAD Electronics                  | 1         | 0.11%   |
| KTMicro                          | 1         | 0.11%   |
| JMTek                            | 1         | 0.11%   |
| Focusrite-Novation               | 1         | 0.11%   |
| Evolution Electronics            | 1         | 0.11%   |
| Creative Technology              | 1         | 0.11%   |
| Blue Microphones                 | 1         | 0.11%   |
| AudioQuest                       | 1         | 0.11%   |
| Apple                            | 1         | 0.11%   |
| Antelope Audio                   | 1         | 0.11%   |
| Afatech                          | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 112       | 9.89%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 93        | 8.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 52        | 4.59%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 48        | 4.24%   |
| Intel Haswell-ULT HD Audio Controller                                      | 47        | 4.15%   |
| Intel 8 Series HD Audio Controller                                         | 47        | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 43        | 3.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 35        | 3.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 32        | 2.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 30        | 2.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 27        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 25        | 2.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 25        | 2.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 22        | 1.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 21        | 1.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 20        | 1.77%   |
| Intel Broadwell-U Audio Controller                                         | 20        | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 18        | 1.59%   |
| AMD FCH Azalia Controller                                                  | 18        | 1.59%   |
| Intel CM238 HD Audio Controller                                            | 16        | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.24%   |
| Nvidia GK107 HDMI Audio Controller                                         | 13        | 1.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 13        | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                              | 11        | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 9         | 0.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 0.79%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 0.71%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 0.62%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 0.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 0.62%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 0.62%   |
| Nvidia GT216 HDMI Audio Controller                                         | 6         | 0.53%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 0.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 0.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 126       | 31.42%  |
| SK hynix            | 101       | 25.19%  |
| Micron Technology   | 57        | 14.21%  |
| Kingston            | 38        | 9.48%   |
| Unknown             | 20        | 4.99%   |
| Crucial             | 15        | 3.74%   |
| Elpida              | 13        | 3.24%   |
| Corsair             | 6         | 1.5%    |
| Ramaxel Technology  | 5         | 1.25%   |
| Nanya Technology    | 4         | 1%      |
| A-DATA Technology   | 3         | 0.75%   |
| G.Skill             | 2         | 0.5%    |
| ff                  | 2         | 0.5%    |
| 4ea5                | 2         | 0.5%    |
| Transcend           | 1         | 0.25%   |
| SHARETRONIC         | 1         | 0.25%   |
| Neo Forza           | 1         | 0.25%   |
| fef5                | 1         | 0.25%   |
| Avant               | 1         | 0.25%   |
| Apacer              | 1         | 0.25%   |
| Unknown             | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 9         | 2.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 8         | 1.9%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 8         | 1.9%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 6         | 1.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 6         | 1.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 6         | 1.42%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 6         | 1.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 6         | 1.42%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 1.18%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 5         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 5         | 1.18%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 5         | 1.18%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 5         | 1.18%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 4         | 0.95%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 4         | 0.95%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s       | 4         | 0.95%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 4         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 3         | 0.71%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 3         | 0.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 3         | 0.71%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 3         | 0.71%   |
| Samsung RAM M425R1GB4DB0-CWMOL 16GB SODIMM DDR5 5600MT/s     | 3         | 0.71%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.71%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 3         | 0.71%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 3         | 0.71%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 3         | 0.71%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 3         | 0.71%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 2         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 2         | 0.47%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s         | 2         | 0.47%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s              | 2         | 0.47%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                 | 2         | 0.47%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                | 2         | 0.47%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 162       | 46.96%  |
| DDR3    | 107       | 31.01%  |
| LPDDR3  | 23        | 6.67%   |
| LPDDR4  | 15        | 4.35%   |
| DDR5    | 12        | 3.48%   |
| LPDDR5  | 10        | 2.9%    |
| DDR2    | 10        | 2.9%    |
| SDRAM   | 2         | 0.58%   |
| Unknown | 2         | 0.58%   |
| DRAM    | 1         | 0.29%   |
| DDR     | 1         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 299       | 86.67%  |
| Row Of Chips | 34        | 9.86%   |
| Chip         | 6         | 1.74%   |
| Unknown      | 5         | 1.45%   |
| DIMM         | 1         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 160       | 43.36%  |
| 4096  | 91        | 24.66%  |
| 16384 | 72        | 19.51%  |
| 2048  | 25        | 6.78%   |
| 32768 | 12        | 3.25%   |
| 1024  | 7         | 1.9%    |
| 512   | 2         | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 78        | 21.31%  |
| 2667    | 72        | 19.67%  |
| 3200    | 65        | 17.76%  |
| 2133    | 34        | 9.29%   |
| 2400    | 20        | 5.46%   |
| 1334    | 16        | 4.37%   |
| 1867    | 11        | 3.01%   |
| 5600    | 9         | 2.46%   |
| 1333    | 9         | 2.46%   |
| 667     | 8         | 2.19%   |
| 4267    | 7         | 1.91%   |
| 1067    | 7         | 1.91%   |
| 6400    | 6         | 1.64%   |
| Unknown | 5         | 1.37%   |
| 4266    | 4         | 1.09%   |
| 4800    | 3         | 0.82%   |
| 3266    | 3         | 0.82%   |
| 7500    | 2         | 0.55%   |
| 2933    | 2         | 0.55%   |
| 800     | 2         | 0.55%   |
| 8533    | 1         | 0.27%   |
| 8400    | 1         | 0.27%   |
| 4199    | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 28.57%  |
| Canon               | 2         | 28.57%  |
| Brother Industries  | 2         | 28.57%  |
| Samsung Electronics | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Samsung ML-1630 Series   | 1         | 14.29%  |
| HP Officejet Pro 6230    | 1         | 14.29%  |
| HP DeskJet 3700 series   | 1         | 14.29%  |
| Canon PIXMA MX370 Series | 1         | 14.29%  |
| Canon PIXMA MP280        | 1         | 14.29%  |
| Brother HL-1210W series  | 1         | 14.29%  |
| Brother HL-1110 series   | 1         | 14.29%  |

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


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 50%     |
| Canon CanoScan LiDE 600F                         | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 181       | 28.5%   |
| Bison Electronics                      | 74        | 11.65%  |
| IMC Networks                           | 69        | 10.87%  |
| Realtek Semiconductor                  | 43        | 6.77%   |
| Microdia                               | 31        | 4.88%   |
| Quanta                                 | 30        | 4.72%   |
| Lite-On Technology                     | 23        | 3.62%   |
| Cheng Uei Precision Industry (Foxlink) | 22        | 3.46%   |
| Apple                                  | 22        | 3.46%   |
| Syntek                                 | 21        | 3.31%   |
| Sunplus Innovation Technology          | 21        | 3.31%   |
| Suyin                                  | 20        | 3.15%   |
| Logitech                               | 14        | 2.2%    |
| Luxvisions Innotech Limited            | 12        | 1.89%   |
| Lenovo                                 | 10        | 1.57%   |
| Acer                                   | 10        | 1.57%   |
| Silicon Motion                         | 6         | 0.94%   |
| Sonix Technology                       | 4         | 0.63%   |
| Samsung Electronics                    | 3         | 0.47%   |
| Primax Electronics                     | 3         | 0.47%   |
| Shinetech                              | 2         | 0.31%   |
| Alcor Micro                            | 2         | 0.31%   |
| Z-Star Microelectronics                | 1         | 0.16%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.16%   |
| Ricoh                                  | 1         | 0.16%   |
| Microsoft                              | 1         | 0.16%   |
| MacroSilicon                           | 1         | 0.16%   |
| kingcome                               | 1         | 0.16%   |
| Hewlett-Packard                        | 1         | 0.16%   |
| Genesys Logic                          | 1         | 0.16%   |
| Generalplus Technology                 | 1         | 0.16%   |
| GEMBIRD                                | 1         | 0.16%   |
| Foxconn / Hon Hai                      | 1         | 0.16%   |
| ALi                                    | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 61        | 9.58%   |
| IMC Networks Integrated Camera                                 | 25        | 3.92%   |
| Bison Integrated Camera                                        | 21        | 3.3%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 19        | 2.98%   |
| Chicony HD WebCam                                              | 17        | 2.67%   |
| Realtek Integrated_Webcam_HD                                   | 16        | 2.51%   |
| Microdia Integrated_Webcam_HD                                  | 15        | 2.35%   |
| Lite-On Integrated Camera                                      | 15        | 2.35%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 12        | 1.88%   |
| Syntek Integrated Camera                                       | 9         | 1.41%   |
| Chicony Integrated Camera (1280x720@30)                        | 9         | 1.41%   |
| Chicony HP HD Camera                                           | 9         | 1.41%   |
| Apple FaceTime HD Camera                                       | 9         | 1.41%   |
| Syntek Lenovo EasyCamera                                       | 8         | 1.26%   |
| Bison SunplusIT Integrated Camera                              | 8         | 1.26%   |
| Bison ThinkPad P50 Integrated Camera                           | 7         | 1.1%    |
| Apple Built-in iSight                                          | 7         | 1.1%    |
| Quanta HD User Facing                                          | 6         | 0.94%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 5         | 0.78%   |
| Quanta USB2.0 HD UVC WebCam                                    | 5         | 0.78%   |
| Quanta HD Webcam                                               | 5         | 0.78%   |
| Luxvisions Innotech Limited HP HD Camera                       | 5         | 0.78%   |
| Lenovo Integrated Webcam                                       | 5         | 0.78%   |
| IMC Networks USB Camera                                        | 5         | 0.78%   |
| Chicony USB2.0 Camera                                          | 5         | 0.78%   |
| Chicony USB 2.0 Camera                                         | 5         | 0.78%   |
| Chicony Lenovo EasyCamera                                      | 5         | 0.78%   |
| Chicony Integrated Camera [ThinkPad]                           | 5         | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 5         | 0.78%   |
| Bison ThinkPad Integrated Camera                               | 5         | 0.78%   |
| Bison SunplusIT INC. Integrated Camera                         | 5         | 0.78%   |
| Bison Lenovo EasyCamera                                        | 5         | 0.78%   |
| Sunplus Integrated_Webcam_HD                                   | 4         | 0.63%   |
| Realtek Integrated Webcam HD                                   | 4         | 0.63%   |
| Realtek Integrated Camera                                      | 4         | 0.63%   |
| Quanta HP Webcam                                               | 4         | 0.63%   |
| Microdia Integrated Webcam                                     | 4         | 0.63%   |
| IMC Networks HD Camera                                         | 4         | 0.63%   |
| Chicony HP Truevision HD                                       | 4         | 0.63%   |
| Chicony EasyCamera                                             | 4         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 69        | 35.75%  |
| Validity Sensors           | 66        | 34.2%   |
| Upek                       | 19        | 9.84%   |
| Shenzhen Goodix Technology | 14        | 7.25%   |
| AuthenTec                  | 12        | 6.22%   |
| Elan Microelectronics      | 6         | 3.11%   |
| STMicroelectronics         | 3         | 1.55%   |
| LighTuning Technology      | 3         | 1.55%   |
| Samsung Electronics        | 1         | 0.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 34        | 17.62%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 10.88%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 9.84%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 6.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 5.18%   |
| Shenzhen Goodix  Fingerprint Device                                        | 10        | 5.18%   |
| Synaptics UWP WBDI Device                                                  | 8         | 4.15%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 3.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 3.11%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 2.59%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 2.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.07%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 2.07%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.07%   |
| AuthenTec AES2810                                                          | 4         | 2.07%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 1.55%   |
| Validity Sensors VFS491                                                    | 2         | 1.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.04%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.04%   |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 1.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.04%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.04%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.52%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.52%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.52%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.52%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.52%   |
| Synaptics WBDI                                                             | 1         | 0.52%   |
| Synaptics TouchPad                                                         | 1         | 0.52%   |
| Synaptics  WBDI                                                            | 1         | 0.52%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.52%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.52%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.52%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 0.52%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.52%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 58        | 62.37%  |
| Broadcom    | 24        | 25.81%  |
| Upek        | 6         | 6.45%   |
| Lenovo      | 5         | 5.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 58        | 62.37%  |
| Broadcom 5880                                                                | 11        | 11.83%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 6.45%   |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 6.45%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 5.38%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 4.3%    |
| Broadcom 58200                                                               | 3         | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 379       | 51.71%  |
| 1     | 257       | 35.06%  |
| 2     | 81        | 11.05%  |
| 3     | 10        | 1.36%   |
| 4     | 3         | 0.41%   |
| 6     | 2         | 0.27%   |
| 10    | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 191       | 41.25%  |
| Chipcard                 | 82        | 17.71%  |
| Graphics card            | 73        | 15.77%  |
| Multimedia controller    | 37        | 7.99%   |
| Net/wireless             | 26        | 5.62%   |
| Card reader              | 12        | 2.59%   |
| Camera                   | 11        | 2.38%   |
| Communication controller | 7         | 1.51%   |
| Bluetooth                | 7         | 1.51%   |
| Storage                  | 6         | 1.3%    |
| Net/ethernet             | 5         | 1.08%   |
| Sound                    | 4         | 0.86%   |
| Wireless                 | 1         | 0.22%   |
| Modem                    | 1         | 0.22%   |

