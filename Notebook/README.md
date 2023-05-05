Linux - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/linuxhw/TestDays_VE)

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

Total: 160731

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | X550CC                      | [cc784397f9](https://linux-hardware.org/?probe=cc784397f9) | May 01, 2023 |
| Valve         | Jupiter                     | [09f9cbd392](https://linux-hardware.org/?probe=09f9cbd392) | May 01, 2023 |
| Lenovo        | 4068AGJ                     | [6a2c3207b5](https://linux-hardware.org/?probe=6a2c3207b5) | May 01, 2023 |
| Dell          | Latitude 3190               | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| ASUSTek       | UX430UNR                    | [4d01364a94](https://linux-hardware.org/?probe=4d01364a94) | May 01, 2023 |
| Acer          | Aspire V5-471P              | [d44b4f12a5](https://linux-hardware.org/?probe=d44b4f12a5) | May 01, 2023 |
| Valve         | Jupiter                     | [07ef050535](https://linux-hardware.org/?probe=07ef050535) | May 01, 2023 |
| Acer          | Aspire A515-51G             | [388b693b6d](https://linux-hardware.org/?probe=388b693b6d) | May 01, 2023 |
| Medion        | E16402                      | [cff2f785ad](https://linux-hardware.org/?probe=cff2f785ad) | May 01, 2023 |
| Alienware     | m17 R5 AMD                  | [4e665db2b1](https://linux-hardware.org/?probe=4e665db2b1) | May 01, 2023 |
| Dell          | Latitude 3420               | [327be624ce](https://linux-hardware.org/?probe=327be624ce) | May 01, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [b54238dc33](https://linux-hardware.org/?probe=b54238dc33) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| Toshiba       | Satellite L755              | [3bafb50baa](https://linux-hardware.org/?probe=3bafb50baa) | May 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d1b974c33a](https://linux-hardware.org/?probe=d1b974c33a) | May 01, 2023 |
| Valve         | Jupiter                     | [9d8a549c47](https://linux-hardware.org/?probe=9d8a549c47) | May 01, 2023 |
| Acer          | Aspire A715-51G             | [842333a8da](https://linux-hardware.org/?probe=842333a8da) | May 01, 2023 |
| Dell          | Latitude 3420               | [1ce0c58a17](https://linux-hardware.org/?probe=1ce0c58a17) | May 01, 2023 |
| Dell          | Latitude E6400              | [33b7764234](https://linux-hardware.org/?probe=33b7764234) | May 01, 2023 |
| Lenovo        | B490 20205                  | [c786307607](https://linux-hardware.org/?probe=c786307607) | May 01, 2023 |
| Timi          | TM1612                      | [3c06f7495e](https://linux-hardware.org/?probe=3c06f7495e) | May 01, 2023 |
| HP            | Laptop 15z-fc000            | [7b57cc42a0](https://linux-hardware.org/?probe=7b57cc42a0) | May 01, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | [34b877bcb5](https://linux-hardware.org/?probe=34b877bcb5) | May 01, 2023 |
| HP            | Compaq 15                   | [0c65bb3d3c](https://linux-hardware.org/?probe=0c65bb3d3c) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6A0LJCL    | [f67154866c](https://linux-hardware.org/?probe=f67154866c) | May 01, 2023 |
| HP            | ElitePad 1000 G2            | [8ae27e00f6](https://linux-hardware.org/?probe=8ae27e00f6) | May 01, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| Acer          | Nitro AN517-54              | [593a6b247f](https://linux-hardware.org/?probe=593a6b247f) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5002NAU    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| Acer          | Aspire A715-51G             | [4f72daaab8](https://linux-hardware.org/?probe=4f72daaab8) | May 01, 2023 |
| Notebook      | NJx0MU                      | [66a3f8bc3a](https://linux-hardware.org/?probe=66a3f8bc3a) | May 01, 2023 |
| HP            | Laptop 14-dk1xxx            | [2a49a2ad57](https://linux-hardware.org/?probe=2a49a2ad57) | May 01, 2023 |
| HP            | EliteBook 8470p             | [f75b4a9457](https://linux-hardware.org/?probe=f75b4a9457) | May 01, 2023 |
| Unknown       | Unknown                     | [8978b9aa5f](https://linux-hardware.org/?probe=8978b9aa5f) | May 01, 2023 |
| HP            | EliteBook 840 G3            | [c490c44357](https://linux-hardware.org/?probe=c490c44357) | May 01, 2023 |
| Lenovo        | B490 20205                  | [bc1fdb2575](https://linux-hardware.org/?probe=bc1fdb2575) | May 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [ba99960d5f](https://linux-hardware.org/?probe=ba99960d5f) | May 01, 2023 |
| ASUSTek       | X455LJ                      | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [a7d6d782b2](https://linux-hardware.org/?probe=a7d6d782b2) | May 01, 2023 |
| Valve         | Jupiter                     | [0494e0759f](https://linux-hardware.org/?probe=0494e0759f) | May 01, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8f8a912636](https://linux-hardware.org/?probe=8f8a912636) | May 01, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [96a8ba3062](https://linux-hardware.org/?probe=96a8ba3062) | May 01, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [856577ad04](https://linux-hardware.org/?probe=856577ad04) | May 01, 2023 |
| HP            | ProBook 640 G2              | [55ac658b79](https://linux-hardware.org/?probe=55ac658b79) | May 01, 2023 |
| Lenovo        | Slim 9 14IAP7 82T1          | [fe1b421c9d](https://linux-hardware.org/?probe=fe1b421c9d) | May 01, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| HP            | Unknown                     | [475eb33956](https://linux-hardware.org/?probe=475eb33956) | May 01, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [6c58138c35](https://linux-hardware.org/?probe=6c58138c35) | May 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [d3ef8c638e](https://linux-hardware.org/?probe=d3ef8c638e) | Apr 30, 2023 |
| Acer          | Aspire V5-561P              | [8818106a28](https://linux-hardware.org/?probe=8818106a28) | Apr 30, 2023 |
| Notebook      | NJx0MU                      | [193fb3ba91](https://linux-hardware.org/?probe=193fb3ba91) | Apr 30, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [4bec088d90](https://linux-hardware.org/?probe=4bec088d90) | Apr 30, 2023 |
| Acer          | Aspire V5-561P              | [fe60e0412d](https://linux-hardware.org/?probe=fe60e0412d) | Apr 30, 2023 |
| Lenovo        | IdeaPad S340-15IWLTouch ... | [6857a16a6c](https://linux-hardware.org/?probe=6857a16a6c) | Apr 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [f84a692777](https://linux-hardware.org/?probe=f84a692777) | Apr 30, 2023 |
| Dell          | XPS 15 9500                 | [93fef964a7](https://linux-hardware.org/?probe=93fef964a7) | Apr 30, 2023 |
| Unknown       | Unknown                     | [070854df6b](https://linux-hardware.org/?probe=070854df6b) | Apr 30, 2023 |
| Apple         | MacBookAir7,2               | [1a343a4622](https://linux-hardware.org/?probe=1a343a4622) | Apr 30, 2023 |
| Apple         | MacBookPro6,2               | [0cb8947c84](https://linux-hardware.org/?probe=0cb8947c84) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0784fc9b1c](https://linux-hardware.org/?probe=0784fc9b1c) | Apr 30, 2023 |
| Toshiba       | EQUIUM P200                 | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| HP            | Notebook                    | [fd6aa4aeb6](https://linux-hardware.org/?probe=fd6aa4aeb6) | Apr 30, 2023 |
| Dell          | Latitude 5580               | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Notebook      | W250EGQ / W270EGQ           | [e523dbbf78](https://linux-hardware.org/?probe=e523dbbf78) | Apr 30, 2023 |
| HUAWEI        | RLEF-XX                     | [b7ca4beb49](https://linux-hardware.org/?probe=b7ca4beb49) | Apr 30, 2023 |
| Acer          | Aspire E1-571               | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| Sony          | SVF1521C6EW                 | [57e1c14061](https://linux-hardware.org/?probe=57e1c14061) | Apr 30, 2023 |
| VIOS          | LTH17                       | [4d1a86ee61](https://linux-hardware.org/?probe=4d1a86ee61) | Apr 30, 2023 |
| Dell          | Latitude E5420              | [df8c9e7f40](https://linux-hardware.org/?probe=df8c9e7f40) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bd460bdc62](https://linux-hardware.org/?probe=bd460bdc62) | Apr 30, 2023 |
| Dell          | Inspiron 5567               | [910f08075b](https://linux-hardware.org/?probe=910f08075b) | Apr 30, 2023 |
| Valve         | Jupiter                     | [3bee1a3271](https://linux-hardware.org/?probe=3bee1a3271) | Apr 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| eMachines     | E725                        | [282c0c9f11](https://linux-hardware.org/?probe=282c0c9f11) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [2dd85470a0](https://linux-hardware.org/?probe=2dd85470a0) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [edfcd7daa6](https://linux-hardware.org/?probe=edfcd7daa6) | Apr 30, 2023 |
| HP            | Laptop 15s-eq3xxx           | [3c321c476a](https://linux-hardware.org/?probe=3c321c476a) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [07e2cc77f8](https://linux-hardware.org/?probe=07e2cc77f8) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [638e747fb1](https://linux-hardware.org/?probe=638e747fb1) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [eb559d913e](https://linux-hardware.org/?probe=eb559d913e) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9c07454907](https://linux-hardware.org/?probe=9c07454907) | Apr 30, 2023 |
| ASUSTek       | X751MA                      | [00fbe71b59](https://linux-hardware.org/?probe=00fbe71b59) | Apr 30, 2023 |
| Lenovo        | Z50-75 80EC                 | [af5d37f4f7](https://linux-hardware.org/?probe=af5d37f4f7) | Apr 30, 2023 |
| HP            | Notebook                    | [4cece109d5](https://linux-hardware.org/?probe=4cece109d5) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [43a167afad](https://linux-hardware.org/?probe=43a167afad) | Apr 30, 2023 |
| Samsung       | 950XED                      | [41f620de17](https://linux-hardware.org/?probe=41f620de17) | Apr 30, 2023 |
| HP            | EliteBook 840 G1            | [c8b979d035](https://linux-hardware.org/?probe=c8b979d035) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [05251702aa](https://linux-hardware.org/?probe=05251702aa) | Apr 30, 2023 |
| ASUSTek       | X501A1                      | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| Dell          | Latitude XT2                | [3cfd979c60](https://linux-hardware.org/?probe=3cfd979c60) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0ae3fb5506](https://linux-hardware.org/?probe=0ae3fb5506) | Apr 30, 2023 |
| Acer          | Aspire A315-33              | [fdba59c054](https://linux-hardware.org/?probe=fdba59c054) | Apr 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [3695c070f9](https://linux-hardware.org/?probe=3695c070f9) | Apr 30, 2023 |
| Positivo      | Q464C                       | [8e41593bd3](https://linux-hardware.org/?probe=8e41593bd3) | Apr 30, 2023 |
| Notebook      | NJx0MU                      | [5fd8f6db6e](https://linux-hardware.org/?probe=5fd8f6db6e) | Apr 30, 2023 |
| Acer          | AO725                       | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| Medion        | P6630                       | [93abad41dd](https://linux-hardware.org/?probe=93abad41dd) | Apr 30, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [1714bffa0e](https://linux-hardware.org/?probe=1714bffa0e) | Apr 30, 2023 |
| Lenovo        | ThinkPad X230 2325V1K       | [d630569df9](https://linux-hardware.org/?probe=d630569df9) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [558cde0a43](https://linux-hardware.org/?probe=558cde0a43) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| Dell          | Inspiron 7548               | [15fe439a9a](https://linux-hardware.org/?probe=15fe439a9a) | Apr 30, 2023 |
| ASUSTek       | X751SA                      | [5192130c0e](https://linux-hardware.org/?probe=5192130c0e) | Apr 30, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [32b3bf20de](https://linux-hardware.org/?probe=32b3bf20de) | Apr 30, 2023 |
| Apple         | MacBook5,1                  | [7077a00b02](https://linux-hardware.org/?probe=7077a00b02) | Apr 30, 2023 |
| ASUSTek       | X555QG                      | [5263b174b2](https://linux-hardware.org/?probe=5263b174b2) | Apr 30, 2023 |
| Thomson       | NEO14A-4WH128               | [be47cb81e5](https://linux-hardware.org/?probe=be47cb81e5) | Apr 30, 2023 |
| Acer          | Peppy                       | [dcac703c46](https://linux-hardware.org/?probe=dcac703c46) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [446a548122](https://linux-hardware.org/?probe=446a548122) | Apr 30, 2023 |
| Lenovo        | ThinkPad T490s 20NX002SG... | [874f19f26e](https://linux-hardware.org/?probe=874f19f26e) | Apr 30, 2023 |
| HP            | Compaq 6720s                | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| eMachines     | E725                        | [25da91560d](https://linux-hardware.org/?probe=25da91560d) | Apr 30, 2023 |
| Acer          | Peppy                       | [4caf11594a](https://linux-hardware.org/?probe=4caf11594a) | Apr 30, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | [44c60dcec2](https://linux-hardware.org/?probe=44c60dcec2) | Apr 30, 2023 |
| Dell          | Latitude 5521               | [1629b4efc4](https://linux-hardware.org/?probe=1629b4efc4) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9876205c45](https://linux-hardware.org/?probe=9876205c45) | Apr 30, 2023 |
| Dell          | Vostro 3558                 | [5d77d7d922](https://linux-hardware.org/?probe=5d77d7d922) | Apr 30, 2023 |
| HP            | EliteBook Folio 1040 G3     | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Medion        | E6214                       | [7bb9f39d76](https://linux-hardware.org/?probe=7bb9f39d76) | Apr 30, 2023 |
| Medion        | E6214                       | [39747632e6](https://linux-hardware.org/?probe=39747632e6) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [25c6042b4e](https://linux-hardware.org/?probe=25c6042b4e) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [94118ab632](https://linux-hardware.org/?probe=94118ab632) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [230f3dd04b](https://linux-hardware.org/?probe=230f3dd04b) | Apr 30, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d4cfc1e964](https://linux-hardware.org/?probe=d4cfc1e964) | Apr 30, 2023 |
| Fujitsu       | LIFEBOOK E734               | [f99ecceaeb](https://linux-hardware.org/?probe=f99ecceaeb) | Apr 30, 2023 |
| Fujitsu       | LIFEBOOK E734               | [31fa8aa587](https://linux-hardware.org/?probe=31fa8aa587) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| Dell          | XPS 13 9350                 | [95b5e79487](https://linux-hardware.org/?probe=95b5e79487) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| Dell          | Latitude E5520              | [43e2d970b5](https://linux-hardware.org/?probe=43e2d970b5) | Apr 30, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [9df1b688c0](https://linux-hardware.org/?probe=9df1b688c0) | Apr 30, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [cc20d89b69](https://linux-hardware.org/?probe=cc20d89b69) | Apr 30, 2023 |
| Acer          | Aspire E5-551G              | [bba2f8d1ad](https://linux-hardware.org/?probe=bba2f8d1ad) | Apr 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [99a89a2055](https://linux-hardware.org/?probe=99a89a2055) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [fcd7a6a42b](https://linux-hardware.org/?probe=fcd7a6a42b) | Apr 30, 2023 |
| HP            | ProBook 650 G4              | [fd991056e0](https://linux-hardware.org/?probe=fd991056e0) | Apr 30, 2023 |
| Dell          | Inspiron 15 3525            | [41c212fa2c](https://linux-hardware.org/?probe=41c212fa2c) | Apr 30, 2023 |
| Dell          | Vostro 5468                 | [93eb16d30d](https://linux-hardware.org/?probe=93eb16d30d) | Apr 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4470195d38](https://linux-hardware.org/?probe=4470195d38) | Apr 30, 2023 |
| Dell          | Inspiron N5110              | [9f932190c4](https://linux-hardware.org/?probe=9f932190c4) | Apr 30, 2023 |
| Acer          | TravelMate B311-31          | [de172b8988](https://linux-hardware.org/?probe=de172b8988) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [dff6f75899](https://linux-hardware.org/?probe=dff6f75899) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [28b11100ac](https://linux-hardware.org/?probe=28b11100ac) | Apr 30, 2023 |
| ASUSTek       | K53E                        | [dcb4502d05](https://linux-hardware.org/?probe=dcb4502d05) | Apr 30, 2023 |
| HP            | Laptop 17-by3xxx            | [552dac328b](https://linux-hardware.org/?probe=552dac328b) | Apr 30, 2023 |
| Toshiba       | Satellite Pro R50-C         | [56f112d60c](https://linux-hardware.org/?probe=56f112d60c) | Apr 30, 2023 |
| Valve         | Jupiter                     | [5645561cbb](https://linux-hardware.org/?probe=5645561cbb) | Apr 30, 2023 |
| Gateway       | P-7805u                     | [0958f250f2](https://linux-hardware.org/?probe=0958f250f2) | Apr 30, 2023 |
| HP            | EliteBook 840 G3            | [c262e81ab9](https://linux-hardware.org/?probe=c262e81ab9) | Apr 30, 2023 |
| Acer          | Extensa 5620                | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [df9cc0160a](https://linux-hardware.org/?probe=df9cc0160a) | Apr 30, 2023 |
| HP            | 255 G6 Notebook PC          | [d99135522b](https://linux-hardware.org/?probe=d99135522b) | Apr 30, 2023 |
| Maibenben     | MaiBook X series            | [5f97e34b20](https://linux-hardware.org/?probe=5f97e34b20) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [875ae124a1](https://linux-hardware.org/?probe=875ae124a1) | Apr 30, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1ba3883d83](https://linux-hardware.org/?probe=1ba3883d83) | Apr 30, 2023 |
| Acer          | Nitro AN515-45              | [9b28e69254](https://linux-hardware.org/?probe=9b28e69254) | Apr 30, 2023 |
| Dell          | G15 5511                    | [7d5f166e7a](https://linux-hardware.org/?probe=7d5f166e7a) | Apr 30, 2023 |
| Dell          | XPS 13 7390                 | [c5000ec967](https://linux-hardware.org/?probe=c5000ec967) | Apr 30, 2023 |
| Valve         | Jupiter                     | [23d976b25f](https://linux-hardware.org/?probe=23d976b25f) | Apr 30, 2023 |
| Acer          | Aspire M5-481T              | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| Dell          | Latitude E6430              | [4c20239367](https://linux-hardware.org/?probe=4c20239367) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [cc7ea9df99](https://linux-hardware.org/?probe=cc7ea9df99) | Apr 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0S... | [2bc3c5303f](https://linux-hardware.org/?probe=2bc3c5303f) | Apr 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [9d5cd21a8f](https://linux-hardware.org/?probe=9d5cd21a8f) | Apr 30, 2023 |
| HP            | Pavilion dv7                | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [9bb7a9b712](https://linux-hardware.org/?probe=9bb7a9b712) | Apr 30, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [da5f050510](https://linux-hardware.org/?probe=da5f050510) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [1e65b46a12](https://linux-hardware.org/?probe=1e65b46a12) | Apr 29, 2023 |
| Lenovo        | V130-15IGM 81HL             | [ff24454021](https://linux-hardware.org/?probe=ff24454021) | Apr 29, 2023 |
| Positivo      | S14CT01                     | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Dell          | Vostro 15 3515              | [8f07407e1a](https://linux-hardware.org/?probe=8f07407e1a) | Apr 29, 2023 |
| HP            | EliteBook 840 G1            | [6f4c134615](https://linux-hardware.org/?probe=6f4c134615) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f2ad30321e](https://linux-hardware.org/?probe=f2ad30321e) | Apr 29, 2023 |
| Framework     | Laptop                      | [84b3b9547b](https://linux-hardware.org/?probe=84b3b9547b) | Apr 29, 2023 |
| Dell          | XPS 13 7390                 | [b976cc9656](https://linux-hardware.org/?probe=b976cc9656) | Apr 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c36b7b72de](https://linux-hardware.org/?probe=c36b7b72de) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [0a9a85f5f0](https://linux-hardware.org/?probe=0a9a85f5f0) | Apr 29, 2023 |
| HP            | Pavilion g6                 | [6d3e51b808](https://linux-hardware.org/?probe=6d3e51b808) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [83b10185e8](https://linux-hardware.org/?probe=83b10185e8) | Apr 29, 2023 |
| HP            | ProBook 450 G7              | [a1c1008bf1](https://linux-hardware.org/?probe=a1c1008bf1) | Apr 29, 2023 |
| MSI           | GF63 Thin 9SC               | [f6a250b3e2](https://linux-hardware.org/?probe=f6a250b3e2) | Apr 29, 2023 |
| ASUSTek       | X751MA                      | [c952010dbb](https://linux-hardware.org/?probe=c952010dbb) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | [3feeeb3341](https://linux-hardware.org/?probe=3feeeb3341) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | [8e0692ebe3](https://linux-hardware.org/?probe=8e0692ebe3) | Apr 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [272103e5a7](https://linux-hardware.org/?probe=272103e5a7) | Apr 29, 2023 |
| ASUSTek       | GL702VMK                    | [a3c0cb6515](https://linux-hardware.org/?probe=a3c0cb6515) | Apr 29, 2023 |
| Lenovo        | G585 20137                  | [f0b4e5c5fd](https://linux-hardware.org/?probe=f0b4e5c5fd) | Apr 29, 2023 |
| Lenovo        | IdeaCentre AIO 3 24IMB05... | [94a285f1f1](https://linux-hardware.org/?probe=94a285f1f1) | Apr 29, 2023 |
| Alienware     | x15 R1                      | [6e2d296667](https://linux-hardware.org/?probe=6e2d296667) | Apr 29, 2023 |
| Alienware     | x15 R1                      | [007beb8981](https://linux-hardware.org/?probe=007beb8981) | Apr 29, 2023 |
| Alienware     | x15 R1                      | [79c6a76fb3](https://linux-hardware.org/?probe=79c6a76fb3) | Apr 29, 2023 |
| Lenovo        | G50-30 80G0                 | [c8d8595af5](https://linux-hardware.org/?probe=c8d8595af5) | Apr 29, 2023 |
| Dell          | XPS 13 9380                 | [c6591b0852](https://linux-hardware.org/?probe=c6591b0852) | Apr 29, 2023 |
| Sony          | VPCF11M1E                   | [16772fe220](https://linux-hardware.org/?probe=16772fe220) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | [6a102a2c37](https://linux-hardware.org/?probe=6a102a2c37) | Apr 29, 2023 |
| ASUSTek       | G56JR                       | [b7eb868ec4](https://linux-hardware.org/?probe=b7eb868ec4) | Apr 29, 2023 |
| HONOR         | HYM-WXX                     | [6923c4c1ce](https://linux-hardware.org/?probe=6923c4c1ce) | Apr 29, 2023 |
| Valve         | Jupiter                     | [183d16708b](https://linux-hardware.org/?probe=183d16708b) | Apr 29, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [e6257e3e50](https://linux-hardware.org/?probe=e6257e3e50) | Apr 29, 2023 |
| Lenovo        | Unknown                     | [33a55a2347](https://linux-hardware.org/?probe=33a55a2347) | Apr 29, 2023 |
| Clevo         | E512xQ/E4129                | [7499c233c9](https://linux-hardware.org/?probe=7499c233c9) | Apr 29, 2023 |
| Dell          | Inspiron N5110              | [04da6f1db9](https://linux-hardware.org/?probe=04da6f1db9) | Apr 29, 2023 |
| MSI           | P65 Creator 9SF             | [4e682b2c20](https://linux-hardware.org/?probe=4e682b2c20) | Apr 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [dca12f3f6a](https://linux-hardware.org/?probe=dca12f3f6a) | Apr 29, 2023 |
| MSI           | Modern 14 A10M              | [22ad1f6bfb](https://linux-hardware.org/?probe=22ad1f6bfb) | Apr 29, 2023 |
| Toshiba       | Satellite C650D             | [472dedd62a](https://linux-hardware.org/?probe=472dedd62a) | Apr 29, 2023 |
| Acer          | Aspire E5-553               | [ff448e32c3](https://linux-hardware.org/?probe=ff448e32c3) | Apr 29, 2023 |
| Acer          | Aspire E5-722               | [d02052aeab](https://linux-hardware.org/?probe=d02052aeab) | Apr 29, 2023 |
| Dell          | Inspiron 15 3520            | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [edf1d60e46](https://linux-hardware.org/?probe=edf1d60e46) | Apr 29, 2023 |
| HP            | Laptop 15-dw1xxx            | [3056c07eb6](https://linux-hardware.org/?probe=3056c07eb6) | Apr 29, 2023 |
| Acer          | TravelMate 5730             | [e74d115d0d](https://linux-hardware.org/?probe=e74d115d0d) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [32f6248b20](https://linux-hardware.org/?probe=32f6248b20) | Apr 29, 2023 |
| Lenovo        | V130-15IGM 81HL             | [9081fc703d](https://linux-hardware.org/?probe=9081fc703d) | Apr 29, 2023 |
| Dell          | XPS 13 9310                 | [2f3308a2ee](https://linux-hardware.org/?probe=2f3308a2ee) | Apr 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [9f604fc816](https://linux-hardware.org/?probe=9f604fc816) | Apr 29, 2023 |
| Medion        | X681X                       | [f65ca1e461](https://linux-hardware.org/?probe=f65ca1e461) | Apr 29, 2023 |
| Dell          | Vostro 3558                 | [e1e3261c15](https://linux-hardware.org/?probe=e1e3261c15) | Apr 29, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [6f6a016997](https://linux-hardware.org/?probe=6f6a016997) | Apr 29, 2023 |
| Lenovo        | ThinkPad T530 24294A1       | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| COPELION I... | QX-250 Series               | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| Acer          | Aspire 8950G                | [348a7d728c](https://linux-hardware.org/?probe=348a7d728c) | Apr 29, 2023 |
| HUAWEI        | BOM-WXX9                    | [b09f495645](https://linux-hardware.org/?probe=b09f495645) | Apr 29, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [2545d9dd31](https://linux-hardware.org/?probe=2545d9dd31) | Apr 29, 2023 |
| HUAWEI        | BOM-WXX9                    | [a69dab4a99](https://linux-hardware.org/?probe=a69dab4a99) | Apr 29, 2023 |
| MSI           | Modern 14 B11MOU            | [6b3fcf3fcc](https://linux-hardware.org/?probe=6b3fcf3fcc) | Apr 29, 2023 |
| HP            | Pavilion dm4                | [3473d4b312](https://linux-hardware.org/?probe=3473d4b312) | Apr 29, 2023 |
| HUAWEI        | CREM-WXX9                   | [c17b468722](https://linux-hardware.org/?probe=c17b468722) | Apr 29, 2023 |
| Dell          | Inspiron 7773               | [19741ac2ea](https://linux-hardware.org/?probe=19741ac2ea) | Apr 29, 2023 |
| Notebook      | W250EGQ / W270EGQ           | [f25ef6f165](https://linux-hardware.org/?probe=f25ef6f165) | Apr 29, 2023 |
| Fujitsu       | FMVNU6G1C                   | [969957b527](https://linux-hardware.org/?probe=969957b527) | Apr 29, 2023 |
| Lenovo        | B50-30 80ES                 | [d84727b8e4](https://linux-hardware.org/?probe=d84727b8e4) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7c378d88a2](https://linux-hardware.org/?probe=7c378d88a2) | Apr 29, 2023 |
| Acer          | Aspire A514-54G             | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Chuwi         | HeroBook Air                | [123f6df9f8](https://linux-hardware.org/?probe=123f6df9f8) | Apr 29, 2023 |
| Toshiba       | Satellite C850-D8K          | [a27eb72e94](https://linux-hardware.org/?probe=a27eb72e94) | Apr 29, 2023 |
| Acer          | Aspire A515-51G             | [bd4c84da60](https://linux-hardware.org/?probe=bd4c84da60) | Apr 29, 2023 |
| Insyde        | M890BAP                     | [151efb0278](https://linux-hardware.org/?probe=151efb0278) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | [a9f658c8af](https://linux-hardware.org/?probe=a9f658c8af) | Apr 29, 2023 |
| Dell          | Inspiron N5110              | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f502c40867](https://linux-hardware.org/?probe=f502c40867) | Apr 29, 2023 |
| Toshiba       | PORTEGE R830                | [11dc4b3a3e](https://linux-hardware.org/?probe=11dc4b3a3e) | Apr 29, 2023 |
| Apple         | MacBookPro13,3              | [0f22698060](https://linux-hardware.org/?probe=0f22698060) | Apr 29, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [59fcc52279](https://linux-hardware.org/?probe=59fcc52279) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [cd266d7680](https://linux-hardware.org/?probe=cd266d7680) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [21d008c7d8](https://linux-hardware.org/?probe=21d008c7d8) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [49557b8214](https://linux-hardware.org/?probe=49557b8214) | Apr 29, 2023 |
| Notebook      | W250EGQ / W270EGQ           | [e4ab273aac](https://linux-hardware.org/?probe=e4ab273aac) | Apr 29, 2023 |
| Acer          | Aspire 5349                 | [aa8c0bb2b9](https://linux-hardware.org/?probe=aa8c0bb2b9) | Apr 29, 2023 |
| HP            | 250 G7 Notebook PC          | [e5fe9aa407](https://linux-hardware.org/?probe=e5fe9aa407) | Apr 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [7598c18042](https://linux-hardware.org/?probe=7598c18042) | Apr 29, 2023 |
| HP            | Stream Laptop 11-y0XX       | [4f777df0e8](https://linux-hardware.org/?probe=4f777df0e8) | Apr 29, 2023 |
| Acer          | Aspire V5-552G              | [07c58a5169](https://linux-hardware.org/?probe=07c58a5169) | Apr 29, 2023 |
| Valve         | Jupiter                     | [cf4ff7fcb1](https://linux-hardware.org/?probe=cf4ff7fcb1) | Apr 29, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| Acer          | Nitro AN515-58              | [2c335c5bfb](https://linux-hardware.org/?probe=2c335c5bfb) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [0ea5e1926e](https://linux-hardware.org/?probe=0ea5e1926e) | Apr 29, 2023 |
| Apple         | MacBookAir7,2               | [c1e0f0fa03](https://linux-hardware.org/?probe=c1e0f0fa03) | Apr 29, 2023 |
| HP            | Pavilion Notebook           | [168b3cf595](https://linux-hardware.org/?probe=168b3cf595) | Apr 29, 2023 |
| Apple         | MacBookPro9,2               | [1e75efbfab](https://linux-hardware.org/?probe=1e75efbfab) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Google        | Banon                       | [c21a57806c](https://linux-hardware.org/?probe=c21a57806c) | Apr 29, 2023 |
| Lenovo        | G50-70 20351                | [5792e8cfa2](https://linux-hardware.org/?probe=5792e8cfa2) | Apr 29, 2023 |
| Sony          | VPCF215FX                   | [49c7606269](https://linux-hardware.org/?probe=49c7606269) | Apr 29, 2023 |
| Dell          | Latitude 7390               | [c24cc9ab68](https://linux-hardware.org/?probe=c24cc9ab68) | Apr 29, 2023 |
| Dell          | Latitude E5470              | [c6c943679f](https://linux-hardware.org/?probe=c6c943679f) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | [73e11e9235](https://linux-hardware.org/?probe=73e11e9235) | Apr 29, 2023 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [d435f7df68](https://linux-hardware.org/?probe=d435f7df68) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [58b09d7887](https://linux-hardware.org/?probe=58b09d7887) | Apr 29, 2023 |
| Samsung       | 930X2K/931X2K               | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [7d91fe30f7](https://linux-hardware.org/?probe=7d91fe30f7) | Apr 29, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [e70d66b3ba](https://linux-hardware.org/?probe=e70d66b3ba) | Apr 29, 2023 |
| Toshiba       | Satellite L45-B             | [8f1db96b6f](https://linux-hardware.org/?probe=8f1db96b6f) | Apr 29, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [2aa69de3ca](https://linux-hardware.org/?probe=2aa69de3ca) | Apr 29, 2023 |
| Positivo      | S14CT01                     | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| ASUSTek       | X756UVK                     | [72ba8fbf57](https://linux-hardware.org/?probe=72ba8fbf57) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [4a8b2ebf8a](https://linux-hardware.org/?probe=4a8b2ebf8a) | Apr 29, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [59b9a9ceb3](https://linux-hardware.org/?probe=59b9a9ceb3) | Apr 29, 2023 |
| Medion        | X6816                       | [2c1807dad7](https://linux-hardware.org/?probe=2c1807dad7) | Apr 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [eeb1550b82](https://linux-hardware.org/?probe=eeb1550b82) | Apr 29, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | [e84690f2d5](https://linux-hardware.org/?probe=e84690f2d5) | Apr 29, 2023 |
| Dell          | Latitude 3301               | [3a0aad0e75](https://linux-hardware.org/?probe=3a0aad0e75) | Apr 29, 2023 |
| Dell          | Inspiron 15-3567            | [33e30c562d](https://linux-hardware.org/?probe=33e30c562d) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| Sony          | VPCZ13M9E                   | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| Toshiba       | Satellite C850-D8K          | [f2f50094ba](https://linux-hardware.org/?probe=f2f50094ba) | Apr 28, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [09d6d7e570](https://linux-hardware.org/?probe=09d6d7e570) | Apr 28, 2023 |
| Sony          | VPCSB2A7R                   | [f089770d02](https://linux-hardware.org/?probe=f089770d02) | Apr 28, 2023 |
| Dell          | Precision M6600             | [39d9af4736](https://linux-hardware.org/?probe=39d9af4736) | Apr 28, 2023 |
| HP            | Compaq Presario CQ70        | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| Sony          | VPCSB2A7R                   | [89f52ca147](https://linux-hardware.org/?probe=89f52ca147) | Apr 28, 2023 |
| ASUSTek       | X555QG                      | [b33f41d3c3](https://linux-hardware.org/?probe=b33f41d3c3) | Apr 28, 2023 |
| Dell          | Inspiron 3180               | [bc3400a372](https://linux-hardware.org/?probe=bc3400a372) | Apr 28, 2023 |
| Toshiba       | Satellite C55t-C            | [8e2bc6ab21](https://linux-hardware.org/?probe=8e2bc6ab21) | Apr 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [61151daf36](https://linux-hardware.org/?probe=61151daf36) | Apr 28, 2023 |
| Dell          | Inspiron 15-3567            | [5dcd15cacf](https://linux-hardware.org/?probe=5dcd15cacf) | Apr 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a984eefe43](https://linux-hardware.org/?probe=a984eefe43) | Apr 28, 2023 |
| Aquarius      | NS585                       | [b23696ca41](https://linux-hardware.org/?probe=b23696ca41) | Apr 28, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | [34420e9478](https://linux-hardware.org/?probe=34420e9478) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [e3f05fe37f](https://linux-hardware.org/?probe=e3f05fe37f) | Apr 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [61e94aaf2a](https://linux-hardware.org/?probe=61e94aaf2a) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d9010fa8d0](https://linux-hardware.org/?probe=d9010fa8d0) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [da542ba626](https://linux-hardware.org/?probe=da542ba626) | Apr 28, 2023 |
| HP            | G62                         | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| MSI           | GE62VR 6RF                  | [97acececd3](https://linux-hardware.org/?probe=97acececd3) | Apr 28, 2023 |
| Acer          | Aspire E5-575G              | [004e0007e4](https://linux-hardware.org/?probe=004e0007e4) | Apr 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [d364cb5ac7](https://linux-hardware.org/?probe=d364cb5ac7) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3059eade71](https://linux-hardware.org/?probe=3059eade71) | Apr 28, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4de963cbc6](https://linux-hardware.org/?probe=4de963cbc6) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| HP            | ENVY Notebook               | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | [3f6a89023c](https://linux-hardware.org/?probe=3f6a89023c) | Apr 28, 2023 |
| Lenovo        | ThinkPad L560 20F2S13L00    | [7695cef903](https://linux-hardware.org/?probe=7695cef903) | Apr 28, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d8af950fd8](https://linux-hardware.org/?probe=d8af950fd8) | Apr 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [2dc65d8f07](https://linux-hardware.org/?probe=2dc65d8f07) | Apr 28, 2023 |
| Monster       | TULPAR T5 V21.7             | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Dell          | Latitude E5450              | [85fb3ec2fd](https://linux-hardware.org/?probe=85fb3ec2fd) | Apr 28, 2023 |
| Acer          | Aspire ES1-731              | [140e5eb8fc](https://linux-hardware.org/?probe=140e5eb8fc) | Apr 28, 2023 |
| ASUSTek       | X542URR                     | [910cdd940c](https://linux-hardware.org/?probe=910cdd940c) | Apr 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e665e9d318](https://linux-hardware.org/?probe=e665e9d318) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [216a4b9b67](https://linux-hardware.org/?probe=216a4b9b67) | Apr 28, 2023 |
| Samsung       | R528/R728                   | [1e0b02f4c5](https://linux-hardware.org/?probe=1e0b02f4c5) | Apr 28, 2023 |
| GPU Compan... | GWNR71517                   | [5fe84b74b0](https://linux-hardware.org/?probe=5fe84b74b0) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [6736f3d911](https://linux-hardware.org/?probe=6736f3d911) | Apr 28, 2023 |
| Notebook      | W35xSTQ_370ST               | [a68f02482d](https://linux-hardware.org/?probe=a68f02482d) | Apr 28, 2023 |
| ASUSTek       | Z550SA                      | [7c6c0c9599](https://linux-hardware.org/?probe=7c6c0c9599) | Apr 28, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [1e7a947d41](https://linux-hardware.org/?probe=1e7a947d41) | Apr 28, 2023 |
| Acer          | Aspire E5-571               | [1d36dafa86](https://linux-hardware.org/?probe=1d36dafa86) | Apr 28, 2023 |
| Dell          | Vostro 3500                 | [7719e2a6c9](https://linux-hardware.org/?probe=7719e2a6c9) | Apr 28, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | [39644ab1d4](https://linux-hardware.org/?probe=39644ab1d4) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Acer          | Swift SF314-57G             | [6fd79b811f](https://linux-hardware.org/?probe=6fd79b811f) | Apr 28, 2023 |
| Dell          | Precision 3551              | [99ff11c325](https://linux-hardware.org/?probe=99ff11c325) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | [a8deb2307c](https://linux-hardware.org/?probe=a8deb2307c) | Apr 28, 2023 |
| Dell          | Precision 3551              | [93a38e7384](https://linux-hardware.org/?probe=93a38e7384) | Apr 28, 2023 |
| HP            | Pavilion dv6                | [8bb5802125](https://linux-hardware.org/?probe=8bb5802125) | Apr 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| HP            | Laptop 15-ef2xxx            | [f922f80a69](https://linux-hardware.org/?probe=f922f80a69) | Apr 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [6f318b0790](https://linux-hardware.org/?probe=6f318b0790) | Apr 28, 2023 |
| ASUSTek       | N550JX                      | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| HP            | Laptop 15-bs2xx             | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | ThinkPad X260 20F5S56G00    | [8da21e9a17](https://linux-hardware.org/?probe=8da21e9a17) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [a2cbf65767](https://linux-hardware.org/?probe=a2cbf65767) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [8c4ba894b4](https://linux-hardware.org/?probe=8c4ba894b4) | Apr 28, 2023 |
| Pegatron      | A15                         | [e9de945dce](https://linux-hardware.org/?probe=e9de945dce) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [a808e47839](https://linux-hardware.org/?probe=a808e47839) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [67ae1efc54](https://linux-hardware.org/?probe=67ae1efc54) | Apr 28, 2023 |
| Dell          | XPS 13 9350                 | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| Valve         | Jupiter                     | [583e105bbf](https://linux-hardware.org/?probe=583e105bbf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [5cb9fe1ae9](https://linux-hardware.org/?probe=5cb9fe1ae9) | Apr 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | [b1e6130b77](https://linux-hardware.org/?probe=b1e6130b77) | Apr 28, 2023 |
| Acer          | Swift SF314-512             | [2ba1bab0fe](https://linux-hardware.org/?probe=2ba1bab0fe) | Apr 28, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [3669ef1de9](https://linux-hardware.org/?probe=3669ef1de9) | Apr 28, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [6569669912](https://linux-hardware.org/?probe=6569669912) | Apr 28, 2023 |
| Dell          | Vostro 3500                 | [450682b3fc](https://linux-hardware.org/?probe=450682b3fc) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [346cbe0e48](https://linux-hardware.org/?probe=346cbe0e48) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [afafdbce36](https://linux-hardware.org/?probe=afafdbce36) | Apr 28, 2023 |
| MSI           | Katana GF66 12UGS           | [3607ee704e](https://linux-hardware.org/?probe=3607ee704e) | Apr 28, 2023 |
| ASUSTek       | UX31E                       | [e2c8068a7d](https://linux-hardware.org/?probe=e2c8068a7d) | Apr 28, 2023 |
| Dell          | Inspiron 3558               | [1ef93daf0b](https://linux-hardware.org/?probe=1ef93daf0b) | Apr 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [e0ef7894af](https://linux-hardware.org/?probe=e0ef7894af) | Apr 28, 2023 |
| Dell          | Latitude 5430               | [644e44f95a](https://linux-hardware.org/?probe=644e44f95a) | Apr 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b5a953a984](https://linux-hardware.org/?probe=b5a953a984) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | [65f390b956](https://linux-hardware.org/?probe=65f390b956) | Apr 28, 2023 |
| ASUSTek       | K53BR                       | [27a8681404](https://linux-hardware.org/?probe=27a8681404) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| Acer          | Aspire 5935                 | [9dfeeff104](https://linux-hardware.org/?probe=9dfeeff104) | Apr 28, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [eeef579322](https://linux-hardware.org/?probe=eeef579322) | Apr 28, 2023 |
| Acer          | Swift SF314-59              | [a84de33c38](https://linux-hardware.org/?probe=a84de33c38) | Apr 28, 2023 |
| ASUSTek       | GL702VMK                    | [5df53b9f76](https://linux-hardware.org/?probe=5df53b9f76) | Apr 28, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [1cfc210ce1](https://linux-hardware.org/?probe=1cfc210ce1) | Apr 28, 2023 |
| Apple         | MacBookPro5,2               | [c188ae4d7d](https://linux-hardware.org/?probe=c188ae4d7d) | Apr 28, 2023 |
| Acer          | Aspire 5110                 | [b43b059257](https://linux-hardware.org/?probe=b43b059257) | Apr 28, 2023 |
| Dell          | Latitude D630               | [0fecf73eea](https://linux-hardware.org/?probe=0fecf73eea) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [39e4de597f](https://linux-hardware.org/?probe=39e4de597f) | Apr 28, 2023 |
| HP            | Laptop 15-dy2xxx            | [210ceedb6d](https://linux-hardware.org/?probe=210ceedb6d) | Apr 28, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [990335263d](https://linux-hardware.org/?probe=990335263d) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | [96194bc912](https://linux-hardware.org/?probe=96194bc912) | Apr 28, 2023 |
| Acer          | Nitro AN515-54              | [000022b2dd](https://linux-hardware.org/?probe=000022b2dd) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Dell          | Latitude E7450              | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| Dell          | Latitude D630               | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c1616fcd6c](https://linux-hardware.org/?probe=c1616fcd6c) | Apr 28, 2023 |
| Dell          | Inspiron 5558               | [ada78ae33d](https://linux-hardware.org/?probe=ada78ae33d) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [a72fdebd89](https://linux-hardware.org/?probe=a72fdebd89) | Apr 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ed7c1abb38](https://linux-hardware.org/?probe=ed7c1abb38) | Apr 28, 2023 |
| Acer          | Aspire V3-772               | [a1584c31ec](https://linux-hardware.org/?probe=a1584c31ec) | Apr 28, 2023 |
| Acer          | Aspire V3-772               | [5f191f449f](https://linux-hardware.org/?probe=5f191f449f) | Apr 28, 2023 |
| MSI           | GE62VR 6RF                  | [2a9fcae8c3](https://linux-hardware.org/?probe=2a9fcae8c3) | Apr 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [539369db0e](https://linux-hardware.org/?probe=539369db0e) | Apr 28, 2023 |
| Dell          | Inspiron 5558               | [9c2dd52f1e](https://linux-hardware.org/?probe=9c2dd52f1e) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [31bdde77c9](https://linux-hardware.org/?probe=31bdde77c9) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [eb550390c1](https://linux-hardware.org/?probe=eb550390c1) | Apr 28, 2023 |
| Dell          | XPS 15 9570                 | [3479673283](https://linux-hardware.org/?probe=3479673283) | Apr 28, 2023 |
| Dell          | Latitude 3301               | [855564b077](https://linux-hardware.org/?probe=855564b077) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | [7c34e35183](https://linux-hardware.org/?probe=7c34e35183) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | [266477f792](https://linux-hardware.org/?probe=266477f792) | Apr 28, 2023 |
| Sony          | VPCEG23EL                   | [c28e3338ce](https://linux-hardware.org/?probe=c28e3338ce) | Apr 28, 2023 |
| Acer          | Aspire V5-572P              | [4fa79fb180](https://linux-hardware.org/?probe=4fa79fb180) | Apr 28, 2023 |
| HP            | Presario CQ43               | [c14c79b3cf](https://linux-hardware.org/?probe=c14c79b3cf) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | [ca70475f8a](https://linux-hardware.org/?probe=ca70475f8a) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Acer          | ConceptD CN315-71P          | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Acer          | Aspire V5-572P              | [fdc85a159b](https://linux-hardware.org/?probe=fdc85a159b) | Apr 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Dell          | Latitude D830               | [2ab0772efb](https://linux-hardware.org/?probe=2ab0772efb) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [ceaa38e624](https://linux-hardware.org/?probe=ceaa38e624) | Apr 28, 2023 |
| Dell          | Latitude E5470              | [caac023f65](https://linux-hardware.org/?probe=caac023f65) | Apr 27, 2023 |
| ASUSTek       | K54C                        | [7223b97463](https://linux-hardware.org/?probe=7223b97463) | Apr 27, 2023 |
| Dell          | XPS 13 9350                 | [aea99797db](https://linux-hardware.org/?probe=aea99797db) | Apr 27, 2023 |
| HP            | Unknown                     | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | [9a7a15dae3](https://linux-hardware.org/?probe=9a7a15dae3) | Apr 27, 2023 |
| HP            | ENVY 15                     | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| Valve         | Jupiter                     | [0958caf898](https://linux-hardware.org/?probe=0958caf898) | Apr 27, 2023 |
| Valve         | Jupiter                     | [37534616d7](https://linux-hardware.org/?probe=37534616d7) | Apr 27, 2023 |
| GPU Compan... | GWTN141-4                   | [633f19ff2d](https://linux-hardware.org/?probe=633f19ff2d) | Apr 27, 2023 |
| HUAWEI        | BOD-WXX9                    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| Valve         | Jupiter                     | [f65ece2859](https://linux-hardware.org/?probe=f65ece2859) | Apr 27, 2023 |
| Sony          | SVF15212CXW                 | [5d5367dc0e](https://linux-hardware.org/?probe=5d5367dc0e) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f1d5d361d5](https://linux-hardware.org/?probe=f1d5d361d5) | Apr 27, 2023 |
| ASUSTek       | X751MA                      | [eb9967626a](https://linux-hardware.org/?probe=eb9967626a) | Apr 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [858404838d](https://linux-hardware.org/?probe=858404838d) | Apr 27, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [404ec697ac](https://linux-hardware.org/?probe=404ec697ac) | Apr 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [0bf066e179](https://linux-hardware.org/?probe=0bf066e179) | Apr 27, 2023 |
| Acer          | Swift SF314-43              | [9ca9aedf16](https://linux-hardware.org/?probe=9ca9aedf16) | Apr 27, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6926565982](https://linux-hardware.org/?probe=6926565982) | Apr 27, 2023 |
| Lenovo        | Legion 7-16-ITHg6 82K6      | [2baf2cbc85](https://linux-hardware.org/?probe=2baf2cbc85) | Apr 27, 2023 |
| Lenovo        | ThinkPad X230 2325O32       | [b38ef1a717](https://linux-hardware.org/?probe=b38ef1a717) | Apr 27, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [94d9250bc1](https://linux-hardware.org/?probe=94d9250bc1) | Apr 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b21dd8d75a](https://linux-hardware.org/?probe=b21dd8d75a) | Apr 27, 2023 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [c5db27dd0c](https://linux-hardware.org/?probe=c5db27dd0c) | Apr 27, 2023 |
| Google        | Chell                       | [1d1b263f21](https://linux-hardware.org/?probe=1d1b263f21) | Apr 27, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [854cf327d8](https://linux-hardware.org/?probe=854cf327d8) | Apr 27, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [57261fe5ec](https://linux-hardware.org/?probe=57261fe5ec) | Apr 27, 2023 |
| HUAWEI        | HVY-WXX9                    | [dd5391c20d](https://linux-hardware.org/?probe=dd5391c20d) | Apr 27, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [beca0f768b](https://linux-hardware.org/?probe=beca0f768b) | Apr 27, 2023 |
| HP            | Laptop 17-ak0xx             | [6eed1fda15](https://linux-hardware.org/?probe=6eed1fda15) | Apr 27, 2023 |
| Dell          | Inspiron 16 5630            | [7bfe5bb892](https://linux-hardware.org/?probe=7bfe5bb892) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| HP            | ProBook 4330s               | [955f91641b](https://linux-hardware.org/?probe=955f91641b) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| Lenovo        | ThinkPad R61 8943DJG        | [afc3fc578e](https://linux-hardware.org/?probe=afc3fc578e) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| HP            | ZBook Studio G3             | [f648c14c51](https://linux-hardware.org/?probe=f648c14c51) | Apr 27, 2023 |
| Dell          | Latitude E7270              | [5bacf4eea3](https://linux-hardware.org/?probe=5bacf4eea3) | Apr 27, 2023 |
| Dell          | Inspiron 5567               | [012329ee1f](https://linux-hardware.org/?probe=012329ee1f) | Apr 27, 2023 |
| Dell          | Latitude D531               | [a6f2e7170f](https://linux-hardware.org/?probe=a6f2e7170f) | Apr 27, 2023 |
| MSI           | PE60 6QE                    | [1a5ae975ee](https://linux-hardware.org/?probe=1a5ae975ee) | Apr 27, 2023 |
| Dell          | Inspiron N5110              | [2a40d09c1a](https://linux-hardware.org/?probe=2a40d09c1a) | Apr 27, 2023 |
| Lenovo        | B590 20208                  | [912acd510d](https://linux-hardware.org/?probe=912acd510d) | Apr 27, 2023 |
| HP            | 15 Notebook PC              | [a63003783d](https://linux-hardware.org/?probe=a63003783d) | Apr 27, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [4cd1484039](https://linux-hardware.org/?probe=4cd1484039) | Apr 27, 2023 |
| HP            | ZBook Studio G3             | [26146530c7](https://linux-hardware.org/?probe=26146530c7) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fe959d51ab](https://linux-hardware.org/?probe=fe959d51ab) | Apr 27, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [0796e35c73](https://linux-hardware.org/?probe=0796e35c73) | Apr 27, 2023 |
| HP            | Laptop 15-bw0xx             | [387eecc18e](https://linux-hardware.org/?probe=387eecc18e) | Apr 27, 2023 |
| MECHREVO      | X3 Series GK7CP6R           | [c764a98c9d](https://linux-hardware.org/?probe=c764a98c9d) | Apr 27, 2023 |
| HP            | EliteBook 2560p             | [ce35b62e32](https://linux-hardware.org/?probe=ce35b62e32) | Apr 27, 2023 |
| GPU Compan... | GWTN156-5                   | [60d207eb63](https://linux-hardware.org/?probe=60d207eb63) | Apr 27, 2023 |
| Gigabyte      | G5 GD                       | [d09d6fb712](https://linux-hardware.org/?probe=d09d6fb712) | Apr 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [25d0c90e31](https://linux-hardware.org/?probe=25d0c90e31) | Apr 27, 2023 |
| HP            | Compaq 6910p                | [049253c0c8](https://linux-hardware.org/?probe=049253c0c8) | Apr 27, 2023 |
| Dell          | XPS 15 9500                 | [a7cc631b80](https://linux-hardware.org/?probe=a7cc631b80) | Apr 27, 2023 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [e207848340](https://linux-hardware.org/?probe=e207848340) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [0e403fcd17](https://linux-hardware.org/?probe=0e403fcd17) | Apr 27, 2023 |
| Valve         | Jupiter                     | [72f64e795a](https://linux-hardware.org/?probe=72f64e795a) | Apr 27, 2023 |
| ASUSTek       | S551LN                      | [710070cf4a](https://linux-hardware.org/?probe=710070cf4a) | Apr 27, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [e1b7846c92](https://linux-hardware.org/?probe=e1b7846c92) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b6bd42eb71](https://linux-hardware.org/?probe=b6bd42eb71) | Apr 27, 2023 |
| TUXEDO        | Unknown                     | [5108a05d49](https://linux-hardware.org/?probe=5108a05d49) | Apr 27, 2023 |
| ASUSTek       | K52JB                       | [e9237f0d53](https://linux-hardware.org/?probe=e9237f0d53) | Apr 27, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [dcc8c22535](https://linux-hardware.org/?probe=dcc8c22535) | Apr 27, 2023 |
| Dell          | Latitude D520               | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| MSI           | Modern 14 C7M               | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Acer          | Aspire E1-572G              | [6c35501215](https://linux-hardware.org/?probe=6c35501215) | Apr 27, 2023 |
| Dell          | Latitude E4300              | [c61dbb5c53](https://linux-hardware.org/?probe=c61dbb5c53) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | [f549cb502c](https://linux-hardware.org/?probe=f549cb502c) | Apr 27, 2023 |
| Dell          | XPS 13 7390                 | [318ea8ad1e](https://linux-hardware.org/?probe=318ea8ad1e) | Apr 27, 2023 |
| ASUSTek       | X55VD                       | [16ef8c0549](https://linux-hardware.org/?probe=16ef8c0549) | Apr 27, 2023 |
| Acer          | Aspire 5742G                | [a1391b4372](https://linux-hardware.org/?probe=a1391b4372) | Apr 27, 2023 |
| HP            | Pavilion g6                 | [716373f59a](https://linux-hardware.org/?probe=716373f59a) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| eMachines     | E725                        | [668de483ca](https://linux-hardware.org/?probe=668de483ca) | Apr 27, 2023 |
| HP            | EliteBook 6930p             | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| HP            | Laptop 15-bs1xx             | [e68f2bc46e](https://linux-hardware.org/?probe=e68f2bc46e) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | [754fc44526](https://linux-hardware.org/?probe=754fc44526) | Apr 27, 2023 |
| Lenovo        | ThinkPad T420 4177QKU       | [cbabefb1fa](https://linux-hardware.org/?probe=cbabefb1fa) | Apr 27, 2023 |
| Dell          | Latitude E6440              | [d55c77598b](https://linux-hardware.org/?probe=d55c77598b) | Apr 27, 2023 |
| Dell          | Inspiron N5010              | [78b4f0cd2f](https://linux-hardware.org/?probe=78b4f0cd2f) | Apr 27, 2023 |
| Dell          | Inspiron 1545               | [a23cf53cec](https://linux-hardware.org/?probe=a23cf53cec) | Apr 27, 2023 |
| Dell          | Vostro 15 3515              | [f58ab8b9c4](https://linux-hardware.org/?probe=f58ab8b9c4) | Apr 27, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4fb9a937f3](https://linux-hardware.org/?probe=4fb9a937f3) | Apr 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [a6845d78e4](https://linux-hardware.org/?probe=a6845d78e4) | Apr 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [640a71aea3](https://linux-hardware.org/?probe=640a71aea3) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [e61f528ba5](https://linux-hardware.org/?probe=e61f528ba5) | Apr 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [f0a2365878](https://linux-hardware.org/?probe=f0a2365878) | Apr 27, 2023 |
| HP            | EliteBook 2560p             | [23b5cbfb33](https://linux-hardware.org/?probe=23b5cbfb33) | Apr 27, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [2093399e21](https://linux-hardware.org/?probe=2093399e21) | Apr 27, 2023 |
| Dell          | XPS 15 9520                 | [07572e6599](https://linux-hardware.org/?probe=07572e6599) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5c5fece872](https://linux-hardware.org/?probe=5c5fece872) | Apr 27, 2023 |
| NEC Comput... | PC-LE150C2                  | [a8e48f9686](https://linux-hardware.org/?probe=a8e48f9686) | Apr 27, 2023 |
| Dell          | Latitude 7420               | [7ceeb888fd](https://linux-hardware.org/?probe=7ceeb888fd) | Apr 27, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [f428173506](https://linux-hardware.org/?probe=f428173506) | Apr 27, 2023 |
| SGIN          | M15                         | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Dell          | Latitude E5410              | [1efb62110c](https://linux-hardware.org/?probe=1efb62110c) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [2063d4a9fc](https://linux-hardware.org/?probe=2063d4a9fc) | Apr 27, 2023 |
| Acer          | Aspire 5720G                | [f566395f99](https://linux-hardware.org/?probe=f566395f99) | Apr 27, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [6a56164bfd](https://linux-hardware.org/?probe=6a56164bfd) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [3f6586f0d1](https://linux-hardware.org/?probe=3f6586f0d1) | Apr 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [0e8490c41f](https://linux-hardware.org/?probe=0e8490c41f) | Apr 27, 2023 |
| Timi          | TM1612                      | [f3127f0186](https://linux-hardware.org/?probe=f3127f0186) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [32960eca65](https://linux-hardware.org/?probe=32960eca65) | Apr 27, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [67c865f449](https://linux-hardware.org/?probe=67c865f449) | Apr 27, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [9344f38032](https://linux-hardware.org/?probe=9344f38032) | Apr 27, 2023 |
| Acer          | Aspire A315-54              | [8137aa9008](https://linux-hardware.org/?probe=8137aa9008) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| Lenovo        | QIWY3                       | [a7c04857e4](https://linux-hardware.org/?probe=a7c04857e4) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3f44947226](https://linux-hardware.org/?probe=3f44947226) | Apr 27, 2023 |
| Dell          | Latitude E6400              | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| MSI           | PE70 6QE                    | [87c8761eff](https://linux-hardware.org/?probe=87c8761eff) | Apr 27, 2023 |
| Apple         | MacBookAir4,1               | [87ab055a31](https://linux-hardware.org/?probe=87ab055a31) | Apr 27, 2023 |
| Dell          | Latitude E5440              | [0217386dbe](https://linux-hardware.org/?probe=0217386dbe) | Apr 27, 2023 |
| Dell          | Inspiron 5558               | [9f3b8c952d](https://linux-hardware.org/?probe=9f3b8c952d) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [67288f740c](https://linux-hardware.org/?probe=67288f740c) | Apr 27, 2023 |
| HP            | EliteBook 630 13 inch G9... | [96bd4f8398](https://linux-hardware.org/?probe=96bd4f8398) | Apr 27, 2023 |
| Notebook      | NJx0MU                      | [2306f31aa2](https://linux-hardware.org/?probe=2306f31aa2) | Apr 27, 2023 |
| Valve         | Jupiter                     | [4066c253b5](https://linux-hardware.org/?probe=4066c253b5) | Apr 27, 2023 |
| Apple         | MacBookAir6,1               | [c0f967c0bc](https://linux-hardware.org/?probe=c0f967c0bc) | Apr 27, 2023 |
| Acer          | Aspire E1-571               | [c95605ef8e](https://linux-hardware.org/?probe=c95605ef8e) | Apr 27, 2023 |
| Valve         | Jupiter                     | [823e1bb624](https://linux-hardware.org/?probe=823e1bb624) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [d49ace71b4](https://linux-hardware.org/?probe=d49ace71b4) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| Dell          | Inspiron 3501               | [29d2a588e0](https://linux-hardware.org/?probe=29d2a588e0) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [4bdb6b2a7f](https://linux-hardware.org/?probe=4bdb6b2a7f) | Apr 27, 2023 |
| Acer          | Aspire E5-575G              | [3497feda9f](https://linux-hardware.org/?probe=3497feda9f) | Apr 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [21577119ad](https://linux-hardware.org/?probe=21577119ad) | Apr 27, 2023 |
| Sony          | SVE11113FXW                 | [248c7717a4](https://linux-hardware.org/?probe=248c7717a4) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [bec614b168](https://linux-hardware.org/?probe=bec614b168) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| ASUSTek       | N750JV                      | [3ec3c7aa7b](https://linux-hardware.org/?probe=3ec3c7aa7b) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [393c7b06d5](https://linux-hardware.org/?probe=393c7b06d5) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c443269a81](https://linux-hardware.org/?probe=c443269a81) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [a950f656f7](https://linux-hardware.org/?probe=a950f656f7) | Apr 26, 2023 |
| ASUSTek       | N750JV                      | [53c0f79af9](https://linux-hardware.org/?probe=53c0f79af9) | Apr 26, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [e35780d356](https://linux-hardware.org/?probe=e35780d356) | Apr 26, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | [8ab4a35e8c](https://linux-hardware.org/?probe=8ab4a35e8c) | Apr 26, 2023 |
| Toshiba       | Satellite Pro S500          | [7a2503959a](https://linux-hardware.org/?probe=7a2503959a) | Apr 26, 2023 |
| GPU Compan... | GWTN156-5                   | [df6b1e8e17](https://linux-hardware.org/?probe=df6b1e8e17) | Apr 26, 2023 |
| Dell          | Vostro 1510                 | [71c860d51c](https://linux-hardware.org/?probe=71c860d51c) | Apr 26, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [cec3a72c8a](https://linux-hardware.org/?probe=cec3a72c8a) | Apr 26, 2023 |
| HP            | 2000                        | [d0fa0a6256](https://linux-hardware.org/?probe=d0fa0a6256) | Apr 26, 2023 |
| Lenovo        | ThinkPad X250 20CLA003TA    | [ea8109c2a7](https://linux-hardware.org/?probe=ea8109c2a7) | Apr 26, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | [fb624057c9](https://linux-hardware.org/?probe=fb624057c9) | Apr 26, 2023 |
| Sony          | SVD1322X2EW                 | [2574ef07fb](https://linux-hardware.org/?probe=2574ef07fb) | Apr 26, 2023 |
| Timi          | TM1703                      | [7e6b948ea9](https://linux-hardware.org/?probe=7e6b948ea9) | Apr 26, 2023 |
| Dell          | Latitude D630               | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [018ade4782](https://linux-hardware.org/?probe=018ade4782) | Apr 26, 2023 |
| ASUSTek       | K501UX                      | [3f46fa9a68](https://linux-hardware.org/?probe=3f46fa9a68) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [4a6eed684e](https://linux-hardware.org/?probe=4a6eed684e) | Apr 26, 2023 |
| Acer          | TravelMate 6593             | [58dce8147e](https://linux-hardware.org/?probe=58dce8147e) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Samsung       | 950XED                      | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [96006a1098](https://linux-hardware.org/?probe=96006a1098) | Apr 26, 2023 |
| Acer          | Aspire A515-57              | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| HP            | 250 G8 Notebook PC          | [b03cd2f2d2](https://linux-hardware.org/?probe=b03cd2f2d2) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [d470349226](https://linux-hardware.org/?probe=d470349226) | Apr 26, 2023 |
| Timi          | RedmiBook Pro 15S           | [7153e7fbe0](https://linux-hardware.org/?probe=7153e7fbe0) | Apr 26, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [c6ac218f6a](https://linux-hardware.org/?probe=c6ac218f6a) | Apr 26, 2023 |
| Apple         | MacBookPro14,2              | [4e1caf5a7a](https://linux-hardware.org/?probe=4e1caf5a7a) | Apr 26, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [7274cefe89](https://linux-hardware.org/?probe=7274cefe89) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [de95ac0857](https://linux-hardware.org/?probe=de95ac0857) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [07906a30e3](https://linux-hardware.org/?probe=07906a30e3) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e0f4a4d0f4](https://linux-hardware.org/?probe=e0f4a4d0f4) | Apr 26, 2023 |
| Acer          | Aspire A515-45              | [d910b01835](https://linux-hardware.org/?probe=d910b01835) | Apr 26, 2023 |
| Acer          | Aspire E5-575G              | [3a7b41fb49](https://linux-hardware.org/?probe=3a7b41fb49) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [7ee153b691](https://linux-hardware.org/?probe=7ee153b691) | Apr 26, 2023 |
| Google        | Terra                       | [b22deb9f09](https://linux-hardware.org/?probe=b22deb9f09) | Apr 26, 2023 |
| Acer          | Aspire 7250                 | [8e8e082e3d](https://linux-hardware.org/?probe=8e8e082e3d) | Apr 26, 2023 |
| Dell          | Vostro 1550                 | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| Dell          | Latitude E6440              | [f5cdf825fa](https://linux-hardware.org/?probe=f5cdf825fa) | Apr 26, 2023 |
| Dell          | Inspiron 7580               | [d9fe7034bd](https://linux-hardware.org/?probe=d9fe7034bd) | Apr 26, 2023 |
| Lenovo        | 3000 N200 0769A97           | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M640... | [0234325d36](https://linux-hardware.org/?probe=0234325d36) | Apr 26, 2023 |
| HP            | ENVY 15                     | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [3a6e27c6ce](https://linux-hardware.org/?probe=3a6e27c6ce) | Apr 26, 2023 |
| Lenovo        | ThinkPad X220 429044U       | [1bf66ba9be](https://linux-hardware.org/?probe=1bf66ba9be) | Apr 26, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [86ba8ccc07](https://linux-hardware.org/?probe=86ba8ccc07) | Apr 26, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [7ca1ebbe7f](https://linux-hardware.org/?probe=7ca1ebbe7f) | Apr 26, 2023 |
| Acer          | Aspire 5737Z                | [121eda50b8](https://linux-hardware.org/?probe=121eda50b8) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | [1fb0741f20](https://linux-hardware.org/?probe=1fb0741f20) | Apr 26, 2023 |
| Clevo         | NL41MU2                     | [4f2ffb4273](https://linux-hardware.org/?probe=4f2ffb4273) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | [f43777b85b](https://linux-hardware.org/?probe=f43777b85b) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| Dell          | Latitude 7420               | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| Valve         | Jupiter                     | [ff3e33e935](https://linux-hardware.org/?probe=ff3e33e935) | Apr 26, 2023 |
| Dell          | G15 5510                    | [9dcb76f7c1](https://linux-hardware.org/?probe=9dcb76f7c1) | Apr 26, 2023 |
| Dell          | G15 5510                    | [4030b4f936](https://linux-hardware.org/?probe=4030b4f936) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| MSI           | Stealth 15M B12UE           | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [82bd4b0d20](https://linux-hardware.org/?probe=82bd4b0d20) | Apr 26, 2023 |
| HP            | 250 G6 Notebook PC          | [90e4883dca](https://linux-hardware.org/?probe=90e4883dca) | Apr 26, 2023 |
| HP            | EliteBook 840 G2            | [a3065a1b59](https://linux-hardware.org/?probe=a3065a1b59) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [c3c972facf](https://linux-hardware.org/?probe=c3c972facf) | Apr 26, 2023 |
| Wortmann      | TERRA_MOBILE_1749           | [2d40a711f9](https://linux-hardware.org/?probe=2d40a711f9) | Apr 26, 2023 |
| Dell          | Inspiron 3558               | [add3c03eef](https://linux-hardware.org/?probe=add3c03eef) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [f993513cd3](https://linux-hardware.org/?probe=f993513cd3) | Apr 26, 2023 |
| Acer          | Aspire 5935                 | [0430d21b33](https://linux-hardware.org/?probe=0430d21b33) | Apr 26, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [67a77ff775](https://linux-hardware.org/?probe=67a77ff775) | Apr 26, 2023 |
| Fujitsu Si... | AMILO Pro V2085             | [d577e7c1e8](https://linux-hardware.org/?probe=d577e7c1e8) | Apr 26, 2023 |
| Dell          | G15 5510                    | [1a6db1dc2b](https://linux-hardware.org/?probe=1a6db1dc2b) | Apr 26, 2023 |
| Sony          | SVE1512K1RW                 | [521db31dfc](https://linux-hardware.org/?probe=521db31dfc) | Apr 26, 2023 |
| ASUSTek       | G75VW                       | [ff439c208a](https://linux-hardware.org/?probe=ff439c208a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| HP            | Pavilion g6                 | [e1b7d44502](https://linux-hardware.org/?probe=e1b7d44502) | Apr 26, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3c104a89ef](https://linux-hardware.org/?probe=3c104a89ef) | Apr 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| Lenovo        | ThinkPad L512 4444PS9       | [78cf80b13b](https://linux-hardware.org/?probe=78cf80b13b) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [3071d4a9d8](https://linux-hardware.org/?probe=3071d4a9d8) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [23fe32affd](https://linux-hardware.org/?probe=23fe32affd) | Apr 26, 2023 |
| ASUSTek       | X550LB                      | [053e93702b](https://linux-hardware.org/?probe=053e93702b) | Apr 26, 2023 |
| Toshiba       | Satellite C660              | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Valve         | Jupiter                     | [7ab7e066cf](https://linux-hardware.org/?probe=7ab7e066cf) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [84bc235979](https://linux-hardware.org/?probe=84bc235979) | Apr 26, 2023 |
| Dell          | Vostro 15 3510              | [81cae0ba77](https://linux-hardware.org/?probe=81cae0ba77) | Apr 26, 2023 |
| ASUSTek       | X550CA                      | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| ASUSTek       | X541SA                      | [362ede5435](https://linux-hardware.org/?probe=362ede5435) | Apr 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [701fb0df1b](https://linux-hardware.org/?probe=701fb0df1b) | Apr 26, 2023 |
| Dell          | XPS 15 9500                 | [e37d368767](https://linux-hardware.org/?probe=e37d368767) | Apr 26, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [f9671dc0a4](https://linux-hardware.org/?probe=f9671dc0a4) | Apr 26, 2023 |
| Fujitsu       | FMVA05004                   | [c494a8453d](https://linux-hardware.org/?probe=c494a8453d) | Apr 26, 2023 |
| Acer          | Swift SF114-32              | [13d7dc019c](https://linux-hardware.org/?probe=13d7dc019c) | Apr 26, 2023 |
| Unknown       | Unknown                     | [208f6823ed](https://linux-hardware.org/?probe=208f6823ed) | Apr 26, 2023 |
| HP            | Pavilion 15                 | [a8bd7a401e](https://linux-hardware.org/?probe=a8bd7a401e) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a3df65a55c](https://linux-hardware.org/?probe=a3df65a55c) | Apr 26, 2023 |
| GPU Compan... | GWNR71517                   | [b8b58af983](https://linux-hardware.org/?probe=b8b58af983) | Apr 26, 2023 |
| MSI           | PE70 6QE                    | [53dd8334ac](https://linux-hardware.org/?probe=53dd8334ac) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Dell          | Latitude E5410              | [02be2c8f0b](https://linux-hardware.org/?probe=02be2c8f0b) | Apr 26, 2023 |
| HP            | Compaq Presario CQ60        | [00bf0576c4](https://linux-hardware.org/?probe=00bf0576c4) | Apr 26, 2023 |
| Google        | Bobba                       | [5eb10d8965](https://linux-hardware.org/?probe=5eb10d8965) | Apr 26, 2023 |
| Toshiba       | dynabook TV/68KBL           | [19c59e3701](https://linux-hardware.org/?probe=19c59e3701) | Apr 26, 2023 |
| HP            | EliteBook 840 G3            | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| HP            | EliteBook Folio 9470m       | [e0d69966e9](https://linux-hardware.org/?probe=e0d69966e9) | Apr 26, 2023 |
| ASUSTek       | X550VQ                      | [3c7d8a0268](https://linux-hardware.org/?probe=3c7d8a0268) | Apr 26, 2023 |
| Apple         | MacBookAir7,2               | [7cbf188375](https://linux-hardware.org/?probe=7cbf188375) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [940cbb6ef0](https://linux-hardware.org/?probe=940cbb6ef0) | Apr 26, 2023 |
| Apple         | MacBookAir7,2               | [b94d783285](https://linux-hardware.org/?probe=b94d783285) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | [69f1753783](https://linux-hardware.org/?probe=69f1753783) | Apr 26, 2023 |
| Notebook      | NJx0MU                      | [a660a768ce](https://linux-hardware.org/?probe=a660a768ce) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | [fa228f68e4](https://linux-hardware.org/?probe=fa228f68e4) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | [33bc801258](https://linux-hardware.org/?probe=33bc801258) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [5daf26faca](https://linux-hardware.org/?probe=5daf26faca) | Apr 26, 2023 |
| Dell          | Inspiron N4030              | [a0f1823b8e](https://linux-hardware.org/?probe=a0f1823b8e) | Apr 26, 2023 |
| System76      | Gazelle                     | [dbf4d8b33d](https://linux-hardware.org/?probe=dbf4d8b33d) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [ab52633e07](https://linux-hardware.org/?probe=ab52633e07) | Apr 26, 2023 |
| Dell          | Precision M6600             | [4f5cd6d28e](https://linux-hardware.org/?probe=4f5cd6d28e) | Apr 26, 2023 |
| Acer          | Nitro AN517-54              | [9fe0f33003](https://linux-hardware.org/?probe=9fe0f33003) | Apr 26, 2023 |
| HP            | ProBook 4540s               | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | [067bc49888](https://linux-hardware.org/?probe=067bc49888) | Apr 26, 2023 |
| Toshiba       | IS 1413G                    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Dell          | Inspiron 5558               | [9dd9301581](https://linux-hardware.org/?probe=9dd9301581) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [8a88263cea](https://linux-hardware.org/?probe=8a88263cea) | Apr 26, 2023 |
| ASUSTek       | K73BR                       | [547b19cd2c](https://linux-hardware.org/?probe=547b19cd2c) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [2f7f2efd4f](https://linux-hardware.org/?probe=2f7f2efd4f) | Apr 26, 2023 |
| MSI           | Creator 15 A10SGS           | [1b364e385a](https://linux-hardware.org/?probe=1b364e385a) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [c9ef115a29](https://linux-hardware.org/?probe=c9ef115a29) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [2e6de51ded](https://linux-hardware.org/?probe=2e6de51ded) | Apr 26, 2023 |
| Dell          | Latitude 5430               | [75ac9d10bf](https://linux-hardware.org/?probe=75ac9d10bf) | Apr 26, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [5c79032176](https://linux-hardware.org/?probe=5c79032176) | Apr 25, 2023 |
| Razer         | Blade                       | [b170226896](https://linux-hardware.org/?probe=b170226896) | Apr 25, 2023 |
| Acer          | Swift SF313-53              | [b487229ea2](https://linux-hardware.org/?probe=b487229ea2) | Apr 25, 2023 |
| System76      | Gazelle                     | [ca2e23db8d](https://linux-hardware.org/?probe=ca2e23db8d) | Apr 25, 2023 |
| Dell          | Inspiron 5748               | [dd4d50839d](https://linux-hardware.org/?probe=dd4d50839d) | Apr 25, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QE... | [379a1710e5](https://linux-hardware.org/?probe=379a1710e5) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2349UKM       | [6adb010c7a](https://linux-hardware.org/?probe=6adb010c7a) | Apr 25, 2023 |
| Acer          | Aspire E1-571               | [c6a1179816](https://linux-hardware.org/?probe=c6a1179816) | Apr 25, 2023 |
| HP            | Laptop 15-fc0xxx            | [cc994920bf](https://linux-hardware.org/?probe=cc994920bf) | Apr 25, 2023 |
| Timi          | Mi NoteBook Ultra           | [b6b7cdfe22](https://linux-hardware.org/?probe=b6b7cdfe22) | Apr 25, 2023 |
| Acer          | Nitro AN517-42              | [5e54d08f91](https://linux-hardware.org/?probe=5e54d08f91) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| Lenovo        | IdeaPad S110 20126          | [4defb36760](https://linux-hardware.org/?probe=4defb36760) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| System76      | Oryx Pro                    | [298bf97b70](https://linux-hardware.org/?probe=298bf97b70) | Apr 25, 2023 |
| Valve         | Jupiter                     | [9b44e9bc2c](https://linux-hardware.org/?probe=9b44e9bc2c) | Apr 25, 2023 |
| Valve         | Jupiter                     | [7c7421ffeb](https://linux-hardware.org/?probe=7c7421ffeb) | Apr 25, 2023 |
| HP            | Pavilion g4                 | [5e2040a91f](https://linux-hardware.org/?probe=5e2040a91f) | Apr 25, 2023 |
| Lenovo        | G580 20150                  | [5d8b07dbbd](https://linux-hardware.org/?probe=5d8b07dbbd) | Apr 25, 2023 |
| HP            | EliteBook 820 G1            | [7afd2012e8](https://linux-hardware.org/?probe=7afd2012e8) | Apr 25, 2023 |
| Dell          | Precision 7550              | [987df8038c](https://linux-hardware.org/?probe=987df8038c) | Apr 25, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| MSI           | Modern 14 A10M              | [dc3595e3cc](https://linux-hardware.org/?probe=dc3595e3cc) | Apr 25, 2023 |
| HP            | ENVY 15                     | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Acer          | Aspire R7-571G              | [d4220bc210](https://linux-hardware.org/?probe=d4220bc210) | Apr 25, 2023 |
| HP            | 2000                        | [14e1ed7540](https://linux-hardware.org/?probe=14e1ed7540) | Apr 25, 2023 |
| HP            | 2000                        | [9e1ae856e4](https://linux-hardware.org/?probe=9e1ae856e4) | Apr 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [bf207e9dc3](https://linux-hardware.org/?probe=bf207e9dc3) | Apr 25, 2023 |
| Login Info... | LOG-S14BW01-CD              | [5f6e2a61f2](https://linux-hardware.org/?probe=5f6e2a61f2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20bf63821f](https://linux-hardware.org/?probe=20bf63821f) | Apr 25, 2023 |
| Lenovo        | ThinkPad T530 23594ZC       | [7aec73dfa1](https://linux-hardware.org/?probe=7aec73dfa1) | Apr 25, 2023 |
| Dell          | XPS 13 9305                 | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Dell          | G15 5515                    | [a0dd3f2003](https://linux-hardware.org/?probe=a0dd3f2003) | Apr 25, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [8fca54d3f2](https://linux-hardware.org/?probe=8fca54d3f2) | Apr 25, 2023 |
| Avell High... | A70 HYB BS                  | [c7b5f9ef04](https://linux-hardware.org/?probe=c7b5f9ef04) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Dell          | XPS 13 9310                 | [b9bc4703a8](https://linux-hardware.org/?probe=b9bc4703a8) | Apr 25, 2023 |
| Acer          | Nitro AN515-51              | [48e88f7bd1](https://linux-hardware.org/?probe=48e88f7bd1) | Apr 25, 2023 |
| Aquarius      | NS585                       | [a0983c89d8](https://linux-hardware.org/?probe=a0983c89d8) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| Aquarius      | NS585                       | [5d9edb6ed4](https://linux-hardware.org/?probe=5d9edb6ed4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [972d7f6e4a](https://linux-hardware.org/?probe=972d7f6e4a) | Apr 25, 2023 |
| Lenovo        | ThinkPad T520 4243W4L       | [bcdd9e5f74](https://linux-hardware.org/?probe=bcdd9e5f74) | Apr 25, 2023 |
| MSI           | Prestige 14 A12UC           | [137a3623dc](https://linux-hardware.org/?probe=137a3623dc) | Apr 25, 2023 |
| HP            | EliteBook 2730p             | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Aquarius      | NS585                       | [c89bbd8bc0](https://linux-hardware.org/?probe=c89bbd8bc0) | Apr 25, 2023 |
| Aquarius      | NS585                       | [a6e5a5f3d1](https://linux-hardware.org/?probe=a6e5a5f3d1) | Apr 25, 2023 |
| Aquarius      | NS585                       | [b6dac5b058](https://linux-hardware.org/?probe=b6dac5b058) | Apr 25, 2023 |
| Dell          | Vostro 3550                 | [653c3c4650](https://linux-hardware.org/?probe=653c3c4650) | Apr 25, 2023 |
| Aquarius      | NS585                       | [1563889dac](https://linux-hardware.org/?probe=1563889dac) | Apr 25, 2023 |
| Aquarius      | NS585                       | [9bdbad2ab7](https://linux-hardware.org/?probe=9bdbad2ab7) | Apr 25, 2023 |
| Aquarius      | NS585                       | [e30d7dde7b](https://linux-hardware.org/?probe=e30d7dde7b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [68527a900f](https://linux-hardware.org/?probe=68527a900f) | Apr 25, 2023 |
| Lenovo        | ThinkPad E14 20RAS1DB00     | [8e09a153f5](https://linux-hardware.org/?probe=8e09a153f5) | Apr 25, 2023 |
| HP            | 240 G8                      | [ab322ed08e](https://linux-hardware.org/?probe=ab322ed08e) | Apr 25, 2023 |
| Acer          | Aspire ES1-311              | [4fcb9881b2](https://linux-hardware.org/?probe=4fcb9881b2) | Apr 25, 2023 |
| Dell          | Inspiron 5570               | [dd27aa0575](https://linux-hardware.org/?probe=dd27aa0575) | Apr 25, 2023 |
| HP            | 240 G8                      | [8cf9892fe9](https://linux-hardware.org/?probe=8cf9892fe9) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ce99b27fb4](https://linux-hardware.org/?probe=ce99b27fb4) | Apr 25, 2023 |
| HP            | Dragonfly Pro               | [9bc83e741f](https://linux-hardware.org/?probe=9bc83e741f) | Apr 25, 2023 |
| HP            | Dragonfly Pro               | [b47e30ac80](https://linux-hardware.org/?probe=b47e30ac80) | Apr 25, 2023 |
| Dell          | Latitude E5470              | [3eb401d939](https://linux-hardware.org/?probe=3eb401d939) | Apr 25, 2023 |
| Dell          | Inspiron 5570               | [e0eef23b19](https://linux-hardware.org/?probe=e0eef23b19) | Apr 25, 2023 |
| Sony          | VPCS13V9E                   | [3c1551d7be](https://linux-hardware.org/?probe=3c1551d7be) | Apr 25, 2023 |
| Aquarius      | NS585                       | [fc377acae2](https://linux-hardware.org/?probe=fc377acae2) | Apr 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | [765b52074c](https://linux-hardware.org/?probe=765b52074c) | Apr 25, 2023 |
| Acer          | Swift SF114-34              | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Acer          | Swift SF314-42              | [a433dd6737](https://linux-hardware.org/?probe=a433dd6737) | Apr 25, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [afcce1c52c](https://linux-hardware.org/?probe=afcce1c52c) | Apr 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | [9cd6c064cc](https://linux-hardware.org/?probe=9cd6c064cc) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ed32f24d6e](https://linux-hardware.org/?probe=ed32f24d6e) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [5236dde38f](https://linux-hardware.org/?probe=5236dde38f) | Apr 25, 2023 |
| Acer          | Aspire 5920G                | [c6387003fc](https://linux-hardware.org/?probe=c6387003fc) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| HUAWEI        | CREM-WXX9                   | [fe2d361db9](https://linux-hardware.org/?probe=fe2d361db9) | Apr 25, 2023 |
| HP            | Pavilion dv7                | [e8318168c4](https://linux-hardware.org/?probe=e8318168c4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ea60267a5b](https://linux-hardware.org/?probe=ea60267a5b) | Apr 25, 2023 |
| Apple         | MacBookPro11,1              | [7309ce024f](https://linux-hardware.org/?probe=7309ce024f) | Apr 25, 2023 |
| Aquarius      | NS585                       | [f71897bf76](https://linux-hardware.org/?probe=f71897bf76) | Apr 25, 2023 |
| Aquarius      | NS585                       | [7aa4561ca5](https://linux-hardware.org/?probe=7aa4561ca5) | Apr 25, 2023 |
| Aquarius      | NS585                       | [385ce8cd93](https://linux-hardware.org/?probe=385ce8cd93) | Apr 25, 2023 |
| ASUSTek       | K52JK                       | [dd0ced2f54](https://linux-hardware.org/?probe=dd0ced2f54) | Apr 25, 2023 |
| Lenovo        | ThinkPad SL500 2746CTO      | [7283a0f4d9](https://linux-hardware.org/?probe=7283a0f4d9) | Apr 25, 2023 |
| Aquarius      | NS585                       | [3fc8926a1a](https://linux-hardware.org/?probe=3fc8926a1a) | Apr 25, 2023 |
| Dell          | Latitude 5490               | [32ddaf898c](https://linux-hardware.org/?probe=32ddaf898c) | Apr 25, 2023 |
| Dell          | Inspiron 5759               | [90fa428095](https://linux-hardware.org/?probe=90fa428095) | Apr 25, 2023 |
| HP            | 255 G5 Notebook PC          | [c542c2df7e](https://linux-hardware.org/?probe=c542c2df7e) | Apr 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [3a7c24a13f](https://linux-hardware.org/?probe=3a7c24a13f) | Apr 25, 2023 |
| Lenovo        | IdeaPad Z580                | [ad5a6d474b](https://linux-hardware.org/?probe=ad5a6d474b) | Apr 25, 2023 |
| HP            | Compaq 15                   | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [9e6ce2eb71](https://linux-hardware.org/?probe=9e6ce2eb71) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d5bd7e8fa](https://linux-hardware.org/?probe=7d5bd7e8fa) | Apr 25, 2023 |
| Dell          | Inspiron 14 5410            | [89017780fa](https://linux-hardware.org/?probe=89017780fa) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [c0d8e6e6b5](https://linux-hardware.org/?probe=c0d8e6e6b5) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | [40df32580a](https://linux-hardware.org/?probe=40df32580a) | Apr 25, 2023 |
| Aquarius      | NS585                       | [58306d0266](https://linux-hardware.org/?probe=58306d0266) | Apr 25, 2023 |
| Dell          | Latitude 5420               | [8c1a7992c0](https://linux-hardware.org/?probe=8c1a7992c0) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [24bf298df5](https://linux-hardware.org/?probe=24bf298df5) | Apr 25, 2023 |
| Dell          | Inspiron 5548               | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| Lenovo        | ThinkPad Edge E545 20B20... | [fd66f3852a](https://linux-hardware.org/?probe=fd66f3852a) | Apr 25, 2023 |
| Acer          | Aspire A514-54              | [19ca73662f](https://linux-hardware.org/?probe=19ca73662f) | Apr 25, 2023 |
| Dell          | System XPS L702X            | [d1aa167e90](https://linux-hardware.org/?probe=d1aa167e90) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e7b20d71b7](https://linux-hardware.org/?probe=e7b20d71b7) | Apr 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | [554f32b909](https://linux-hardware.org/?probe=554f32b909) | Apr 25, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [2732f4b096](https://linux-hardware.org/?probe=2732f4b096) | Apr 25, 2023 |
| Google        | Sasuke                      | [7615a1b1e5](https://linux-hardware.org/?probe=7615a1b1e5) | Apr 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [7d3b6ba1a3](https://linux-hardware.org/?probe=7d3b6ba1a3) | Apr 25, 2023 |
| LDLC          | SPC-I                       | [899fb46a02](https://linux-hardware.org/?probe=899fb46a02) | Apr 25, 2023 |
| Toshiba       | Satellite L305D             | [1bbf3a5e9c](https://linux-hardware.org/?probe=1bbf3a5e9c) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| ICL           | RAYbook Si1512              | [6aa907fd2e](https://linux-hardware.org/?probe=6aa907fd2e) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| Notebook      | W650EH                      | [8e848e589e](https://linux-hardware.org/?probe=8e848e589e) | Apr 25, 2023 |
| HP            | ENVY 17                     | [a4327cd9cc](https://linux-hardware.org/?probe=a4327cd9cc) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [05d2b26ee6](https://linux-hardware.org/?probe=05d2b26ee6) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | [0ef0676073](https://linux-hardware.org/?probe=0ef0676073) | Apr 25, 2023 |
| HP            | ENVY 17                     | [e6cc7d84ec](https://linux-hardware.org/?probe=e6cc7d84ec) | Apr 25, 2023 |
| Chuwi         | GemiBook Pro                | [1287b17594](https://linux-hardware.org/?probe=1287b17594) | Apr 25, 2023 |
| MSI           | GE72VR 6RF                  | [89cb17ee72](https://linux-hardware.org/?probe=89cb17ee72) | Apr 25, 2023 |
| HP            | ENVY 15                     | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [1602540ab8](https://linux-hardware.org/?probe=1602540ab8) | Apr 25, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [cc14ce03b0](https://linux-hardware.org/?probe=cc14ce03b0) | Apr 25, 2023 |
| Fujitsu       | LIFEBOOK S935               | [418c2c626e](https://linux-hardware.org/?probe=418c2c626e) | Apr 25, 2023 |
| Dell          | G3 3500                     | [46996524d0](https://linux-hardware.org/?probe=46996524d0) | Apr 25, 2023 |
| Apple         | MacBookAir7,2               | [2ccfcd2b27](https://linux-hardware.org/?probe=2ccfcd2b27) | Apr 25, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [45199e8296](https://linux-hardware.org/?probe=45199e8296) | Apr 25, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [5fd25f9235](https://linux-hardware.org/?probe=5fd25f9235) | Apr 25, 2023 |
| Purism        | Librem 14                   | [8462dbaccb](https://linux-hardware.org/?probe=8462dbaccb) | Apr 25, 2023 |
| Dell          | XPS 15 9500                 | [861431db35](https://linux-hardware.org/?probe=861431db35) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| Dell          | XPS 13 9380                 | [290a99fee9](https://linux-hardware.org/?probe=290a99fee9) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ebc99a93ab](https://linux-hardware.org/?probe=ebc99a93ab) | Apr 25, 2023 |
| HP            | ProBook 640 G1              | [9306db1f90](https://linux-hardware.org/?probe=9306db1f90) | Apr 25, 2023 |
| GPU Compan... | GWTN156-5                   | [afe12152a5](https://linux-hardware.org/?probe=afe12152a5) | Apr 25, 2023 |
| Valve         | Jupiter                     | [78a3abdc19](https://linux-hardware.org/?probe=78a3abdc19) | Apr 25, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | [029abbccfc](https://linux-hardware.org/?probe=029abbccfc) | Apr 25, 2023 |
| Dell          | Latitude E5470              | [37fabb89aa](https://linux-hardware.org/?probe=37fabb89aa) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| ASUSTek       | PRIME X670-P                | [37f98c9450](https://linux-hardware.org/?probe=37f98c9450) | Apr 25, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | [2e542c241d](https://linux-hardware.org/?probe=2e542c241d) | Apr 25, 2023 |
| GPU Compan... | GWTN156-5                   | [a22605adc9](https://linux-hardware.org/?probe=a22605adc9) | Apr 25, 2023 |
| Sony          | SVS13A25PXB                 | [a31acd0a66](https://linux-hardware.org/?probe=a31acd0a66) | Apr 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [5fb905227b](https://linux-hardware.org/?probe=5fb905227b) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | [e05975b1cc](https://linux-hardware.org/?probe=e05975b1cc) | Apr 25, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [0db2c54b2a](https://linux-hardware.org/?probe=0db2c54b2a) | Apr 24, 2023 |
| Acer          | Aspire A515-56              | [a3a13c5cb1](https://linux-hardware.org/?probe=a3a13c5cb1) | Apr 24, 2023 |
| Notebook      | P95_96_97Ex,Rx              | [297da8c979](https://linux-hardware.org/?probe=297da8c979) | Apr 24, 2023 |
| Lenovo        | V130-15IKB 81HN             | [1b26b3f89b](https://linux-hardware.org/?probe=1b26b3f89b) | Apr 24, 2023 |
| Dell          | Inspiron 3543               | [2a3020f392](https://linux-hardware.org/?probe=2a3020f392) | Apr 24, 2023 |
| Dell          | XPS 13 9310                 | [65ccee11a0](https://linux-hardware.org/?probe=65ccee11a0) | Apr 24, 2023 |
| ICL           | RAYbook Si1512              | [4e960cbe90](https://linux-hardware.org/?probe=4e960cbe90) | Apr 24, 2023 |
| ASUSTek       | GL752VW                     | [26c754e5f0](https://linux-hardware.org/?probe=26c754e5f0) | Apr 24, 2023 |
| Dell          | XPS 13 9310                 | [070d7e791f](https://linux-hardware.org/?probe=070d7e791f) | Apr 24, 2023 |
| Notebook      | N85_N87HCHNHZ               | [ecb3270b4a](https://linux-hardware.org/?probe=ecb3270b4a) | Apr 24, 2023 |
| HP            | ProBook 5320m               | [7597710994](https://linux-hardware.org/?probe=7597710994) | Apr 24, 2023 |
| ASUSTek       | X510UQR                     | [4a2e357ace](https://linux-hardware.org/?probe=4a2e357ace) | Apr 24, 2023 |
| Acer          | Aspire 5742G                | [84679bc442](https://linux-hardware.org/?probe=84679bc442) | Apr 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9e926f5c65](https://linux-hardware.org/?probe=9e926f5c65) | Apr 24, 2023 |
| Dell          | Latitude XT2                | [62df7dc069](https://linux-hardware.org/?probe=62df7dc069) | Apr 24, 2023 |
| Dell          | Vostro 15 3515              | [13c75fa32e](https://linux-hardware.org/?probe=13c75fa32e) | Apr 24, 2023 |
| INSYS         | PT1-140C                    | [902536abce](https://linux-hardware.org/?probe=902536abce) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Lenovo        | G700                        | [75ee4cf99d](https://linux-hardware.org/?probe=75ee4cf99d) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [9649423c20](https://linux-hardware.org/?probe=9649423c20) | Apr 24, 2023 |
| Sony          | SVS13A25PXB                 | [06138dd58a](https://linux-hardware.org/?probe=06138dd58a) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [af486ae4ae](https://linux-hardware.org/?probe=af486ae4ae) | Apr 24, 2023 |
| HUAWEI        | HN-WX9X                     | [d07874c829](https://linux-hardware.org/?probe=d07874c829) | Apr 24, 2023 |
| Acer          | AOHAPPY                     | [6f32fad8f0](https://linux-hardware.org/?probe=6f32fad8f0) | Apr 24, 2023 |
| Dell          | System XPS L502X            | [4fd4992d0f](https://linux-hardware.org/?probe=4fd4992d0f) | Apr 24, 2023 |
| Dell          | Latitude 5580               | [a153ad5277](https://linux-hardware.org/?probe=a153ad5277) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [253f35c2c3](https://linux-hardware.org/?probe=253f35c2c3) | Apr 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [de3ad583ab](https://linux-hardware.org/?probe=de3ad583ab) | Apr 24, 2023 |
| Dell          | Inspiron 15 5510            | [c8f22361f6](https://linux-hardware.org/?probe=c8f22361f6) | Apr 24, 2023 |
| GPU Compan... | GWTN156-2BK                 | [9dd0969eaf](https://linux-hardware.org/?probe=9dd0969eaf) | Apr 24, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | [2f3390afca](https://linux-hardware.org/?probe=2f3390afca) | Apr 24, 2023 |
| ASUSTek       | K53SM                       | [92ac292547](https://linux-hardware.org/?probe=92ac292547) | Apr 24, 2023 |
| Medion        | X681X                       | [d72837ad07](https://linux-hardware.org/?probe=d72837ad07) | Apr 24, 2023 |
| Lenovo        | ThinkPad A285 20MXS0NJ00    | [f155ad2bf4](https://linux-hardware.org/?probe=f155ad2bf4) | Apr 24, 2023 |
| Toshiba       | Satellite C45-A             | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [2787d97e6e](https://linux-hardware.org/?probe=2787d97e6e) | Apr 24, 2023 |
| Fujitsu       | LIFEBOOK S751               | [e01b26f35f](https://linux-hardware.org/?probe=e01b26f35f) | Apr 24, 2023 |
| HP            | Laptop 17-cp0xxx            | [288f3f709c](https://linux-hardware.org/?probe=288f3f709c) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| Dell          | Latitude 7530               | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [aa1b58a2a2](https://linux-hardware.org/?probe=aa1b58a2a2) | Apr 24, 2023 |
| Apple         | MacBookPro8,1               | [006b9a2b3f](https://linux-hardware.org/?probe=006b9a2b3f) | Apr 24, 2023 |
| Acer          | Aspire A515-56              | [1d5b5dcfc7](https://linux-hardware.org/?probe=1d5b5dcfc7) | Apr 24, 2023 |
| Dell          | System XPS L321X            | [cd2af9d26f](https://linux-hardware.org/?probe=cd2af9d26f) | Apr 24, 2023 |
| Apple         | MacBookPro8,1               | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| ASUSTek       | GL752VW                     | [216aaf8fff](https://linux-hardware.org/?probe=216aaf8fff) | Apr 24, 2023 |
| HP            | Laptop 15-db0xxx            | [2ab42d58bf](https://linux-hardware.org/?probe=2ab42d58bf) | Apr 24, 2023 |
| HP            | ProBook 4520s               | [b680525b61](https://linux-hardware.org/?probe=b680525b61) | Apr 24, 2023 |
| Gateway       | NV55C                       | [3c560a28cf](https://linux-hardware.org/?probe=3c560a28cf) | Apr 24, 2023 |
| HP            | Laptop 15-db0xxx            | [8c5aea6211](https://linux-hardware.org/?probe=8c5aea6211) | Apr 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [699adff825](https://linux-hardware.org/?probe=699adff825) | Apr 24, 2023 |
| Dell          | Latitude E7240              | [b72361ca9e](https://linux-hardware.org/?probe=b72361ca9e) | Apr 24, 2023 |
| Dell          | Precision 7770              | [e9208415d5](https://linux-hardware.org/?probe=e9208415d5) | Apr 24, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [b402183807](https://linux-hardware.org/?probe=b402183807) | Apr 24, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [e028b13685](https://linux-hardware.org/?probe=e028b13685) | Apr 24, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | [fb80fac677](https://linux-hardware.org/?probe=fb80fac677) | Apr 24, 2023 |
| Alienware     | 13 R2                       | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| ASUSTek       | G75VW                       | [21c872ac1c](https://linux-hardware.org/?probe=21c872ac1c) | Apr 24, 2023 |
| HP            | 240 G4                      | [997e6e6a0b](https://linux-hardware.org/?probe=997e6e6a0b) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2e7585d261](https://linux-hardware.org/?probe=2e7585d261) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| HP            | ProBook 4520s               | [e4ce7aed55](https://linux-hardware.org/?probe=e4ce7aed55) | Apr 24, 2023 |
| Dell          | Latitude E6540              | [ba8579b1a5](https://linux-hardware.org/?probe=ba8579b1a5) | Apr 24, 2023 |
| Dell          | Inspiron 3542               | [9f4ce3c5a4](https://linux-hardware.org/?probe=9f4ce3c5a4) | Apr 24, 2023 |
| Lenovo        | G560 20042                  | [af88bff29f](https://linux-hardware.org/?probe=af88bff29f) | Apr 24, 2023 |
| Dell          | Latitude E4300              | [94773cc3da](https://linux-hardware.org/?probe=94773cc3da) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [59c225df6e](https://linux-hardware.org/?probe=59c225df6e) | Apr 24, 2023 |
| Lenovo        | 20RD001FHV                  | [782ded0435](https://linux-hardware.org/?probe=782ded0435) | Apr 24, 2023 |
| Dell          | Latitude E4300              | [8bdf03bc75](https://linux-hardware.org/?probe=8bdf03bc75) | Apr 24, 2023 |
| Samsung       | 950XED                      | [6226147e11](https://linux-hardware.org/?probe=6226147e11) | Apr 24, 2023 |
| LG Electro... | 16Z90Q-G.AD78F              | [99bbc09adb](https://linux-hardware.org/?probe=99bbc09adb) | Apr 24, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [8bfea5add2](https://linux-hardware.org/?probe=8bfea5add2) | Apr 24, 2023 |
| Apple         | MacBookPro15,2              | [09eb88ba6c](https://linux-hardware.org/?probe=09eb88ba6c) | Apr 24, 2023 |
| Fujitsu       | LIFEBOOK S751               | [07e4819355](https://linux-hardware.org/?probe=07e4819355) | Apr 24, 2023 |
| Dell          | Vostro 5402                 | [b6cb9c9140](https://linux-hardware.org/?probe=b6cb9c9140) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [b1c3492700](https://linux-hardware.org/?probe=b1c3492700) | Apr 24, 2023 |
| Notebook      | NH5x_NH7xHP                 | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| Acer          | Aspire A515-47              | [35a591e26a](https://linux-hardware.org/?probe=35a591e26a) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [e37aab534f](https://linux-hardware.org/?probe=e37aab534f) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Shanghai Z... | ZXE CRB                     | [298d51ae78](https://linux-hardware.org/?probe=298d51ae78) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d805c85a12](https://linux-hardware.org/?probe=d805c85a12) | Apr 24, 2023 |
| Dell          | Latitude E5470              | [bc1dca3c78](https://linux-hardware.org/?probe=bc1dca3c78) | Apr 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | ZBook 17 G5                 | [c1d71592a4](https://linux-hardware.org/?probe=c1d71592a4) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | [1259bb0006](https://linux-hardware.org/?probe=1259bb0006) | Apr 24, 2023 |
| Emdoor        | AG958                       | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Chuwi         | GemiBook Pro                | [b4d8bd0f23](https://linux-hardware.org/?probe=b4d8bd0f23) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Dell          | Latitude 3190               | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [60d1d4aec8](https://linux-hardware.org/?probe=60d1d4aec8) | Apr 24, 2023 |
| Toshiba       | Satellite L15W-B            | [5d1177f899](https://linux-hardware.org/?probe=5d1177f899) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| Acer          | Aspire A317-53              | [c47ec3530e](https://linux-hardware.org/?probe=c47ec3530e) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [52086c894a](https://linux-hardware.org/?probe=52086c894a) | Apr 24, 2023 |
| Dell          | Inspiron 11-3168            | [5ac6392b05](https://linux-hardware.org/?probe=5ac6392b05) | Apr 24, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [c087d6cbae](https://linux-hardware.org/?probe=c087d6cbae) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| HP            | ProBook 4540s               | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| Acer          | Aspire A515-46              | [16acb0ba22](https://linux-hardware.org/?probe=16acb0ba22) | Apr 24, 2023 |
| HP            | Laptop 14-cm0xxx            | [4591d1bf9d](https://linux-hardware.org/?probe=4591d1bf9d) | Apr 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS16G0... | [b019f5af89](https://linux-hardware.org/?probe=b019f5af89) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| HP            | ProBook 450 G7              | [57f0ae7486](https://linux-hardware.org/?probe=57f0ae7486) | Apr 24, 2023 |
| HP            | ProBook 4530s               | [316cfd6876](https://linux-hardware.org/?probe=316cfd6876) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [32546113c8](https://linux-hardware.org/?probe=32546113c8) | Apr 24, 2023 |
| HP            | Laptop 15-db0xxx            | [e4fd112564](https://linux-hardware.org/?probe=e4fd112564) | Apr 24, 2023 |
| Hampoo        | Cherry Trail CR V200        | [f3d90b0d4a](https://linux-hardware.org/?probe=f3d90b0d4a) | Apr 23, 2023 |
| Acer          | Aspire V5-552P              | [28c276f9da](https://linux-hardware.org/?probe=28c276f9da) | Apr 23, 2023 |
| ASUSTek       | PRIME X670-P                | [ebe7f36c99](https://linux-hardware.org/?probe=ebe7f36c99) | Apr 23, 2023 |
| Acer          | Aspire V5-122P              | [baf567c71f](https://linux-hardware.org/?probe=baf567c71f) | Apr 23, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [e562ba35c6](https://linux-hardware.org/?probe=e562ba35c6) | Apr 23, 2023 |
| Dell          | XPS 15 9530                 | [d9429d7e06](https://linux-hardware.org/?probe=d9429d7e06) | Apr 23, 2023 |
| Dell          | G5 5590                     | [eef3722c35](https://linux-hardware.org/?probe=eef3722c35) | Apr 23, 2023 |
| BTO           | 17X1183                     | [134a6ead50](https://linux-hardware.org/?probe=134a6ead50) | Apr 23, 2023 |
| BTO           | 17X1183                     | [181163b5e8](https://linux-hardware.org/?probe=181163b5e8) | Apr 23, 2023 |
| HP            | ZBook 17 G2                 | [5eec26bec0](https://linux-hardware.org/?probe=5eec26bec0) | Apr 23, 2023 |
| Dell          | Latitude 9520               | [0ab9a83db6](https://linux-hardware.org/?probe=0ab9a83db6) | Apr 23, 2023 |
| Panasonic     | CF-19RHSC8FN                | [cef5165f9c](https://linux-hardware.org/?probe=cef5165f9c) | Apr 23, 2023 |
| Dell          | G15 5520                    | [d2cc8527a5](https://linux-hardware.org/?probe=d2cc8527a5) | Apr 23, 2023 |
| HP            | 350 G2                      | [ffa4ab3dc0](https://linux-hardware.org/?probe=ffa4ab3dc0) | Apr 23, 2023 |
| Valve         | Jupiter                     | [7501c5e0e4](https://linux-hardware.org/?probe=7501c5e0e4) | Apr 23, 2023 |
| Samsung       | R510/P510                   | [4b58936ad7](https://linux-hardware.org/?probe=4b58936ad7) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [696ee85cc9](https://linux-hardware.org/?probe=696ee85cc9) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [76c4edb7f3](https://linux-hardware.org/?probe=76c4edb7f3) | Apr 23, 2023 |
| HP            | 15                          | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| HP            | G42                         | [1d5b2eefc3](https://linux-hardware.org/?probe=1d5b2eefc3) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | [f6fe80f275](https://linux-hardware.org/?probe=f6fe80f275) | Apr 23, 2023 |
| HP            | Pavilion g6                 | [1ca41a3608](https://linux-hardware.org/?probe=1ca41a3608) | Apr 23, 2023 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 13625     | 11.85%  |
| Ubuntu 18.04      | 6919      | 6.02%   |
| Ubuntu 22.04      | 4745      | 4.13%   |
| Debian 11         | 3144      | 2.74%   |
| OpenMandriva 4.2  | 2190      | 1.91%   |
| ROSA R10          | 2144      | 1.87%   |
| OpenMandriva 4.3  | 2085      | 1.81%   |
| ROSA R11          | 1939      | 1.69%   |
| Arch              | 1744      | 1.52%   |
| ROSA R8           | 1703      | 1.48%   |
| ROSA R6           | 1686      | 1.47%   |
| Linux Mint 20.3   | 1652      | 1.44%   |
| Arch Rolling      | 1611      | 1.4%    |
| Zorin 16          | 1603      | 1.39%   |
| ROSA R7           | 1566      | 1.36%   |
| KDE neon 20.04    | 1553      | 1.35%   |
| BlackPanther 18.1 | 1503      | 1.31%   |
| Pop!_OS 22.04     | 1476      | 1.28%   |
| Manjaro           | 1448      | 1.26%   |
| ROSA R8.1         | 1349      | 1.17%   |
| Linux Mint 20.2   | 1336      | 1.16%   |
| Linux Mint 19.3   | 1232      | 1.07%   |
| Linux Mint 20.1   | 1229      | 1.07%   |
| Fedora 36         | 1218      | 1.06%   |
| ROSA R9           | 1217      | 1.06%   |
| Ubuntu 19.10      | 1159      | 1.01%   |
| Pop!_OS 20.04     | 1150      | 1%      |
| Fedora 37         | 1150      | 1%      |
| Linux Mint 20     | 1126      | 0.98%   |
| Ubuntu 21.10      | 1120      | 0.97%   |
| Ubuntu 20.10      | 1088      | 0.95%   |
| ROSA R11.1        | 1068      | 0.93%   |
| Ubuntu 19.04      | 1037      | 0.9%    |
| Xubuntu 20.04     | 1013      | 0.88%   |
| Zorin 15          | 999       | 0.87%   |
| Fedora 35         | 964       | 0.84%   |
| Pop!_OS 21.04     | 959       | 0.83%   |
| Fedora 34         | 936       | 0.81%   |
| Linux Mint 21.1   | 918       | 0.8%    |
| Ubuntu 21.04      | 910       | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 30921     | 28.86%  |
| ROSA          | 12267     | 11.45%  |
| Linux Mint    | 8910      | 8.32%   |
| OpenMandriva  | 6163      | 5.75%   |
| Fedora        | 6138      | 5.73%   |
| Pop!_OS       | 4837      | 4.51%   |
| Debian        | 4751      | 4.43%   |
| Manjaro       | 3568      | 3.33%   |
| Arch          | 3258      | 3.04%   |
| Zorin         | 2706      | 2.53%   |
| Endless       | 2603      | 2.43%   |
| Xubuntu       | 2149      | 2.01%   |
| KDE neon      | 2050      | 1.91%   |
| Kubuntu       | 2003      | 1.87%   |
| BlackPanther  | 1658      | 1.55%   |
| Kali          | 988       | 0.92%   |
| openSUSE      | 956       | 0.89%   |
| Elementary    | 939       | 0.88%   |
| ArcoLinux     | 866       | 0.81%   |
| Lubuntu       | 736       | 0.69%   |
| SteamOS       | 708       | 0.66%   |
| Gentoo        | 668       | 0.62%   |
| Ubuntu MATE   | 652       | 0.61%   |
| Ubuntu Unity  | 597       | 0.56%   |
| EndeavourOS   | 514       | 0.48%   |
| LMDE          | 448       | 0.42%   |
| Clear Linux   | 439       | 0.41%   |
| Ubuntu Budgie | 373       | 0.35%   |
| MX            | 302       | 0.28%   |
| Parrot        | 299       | 0.28%   |
| Garuda Linux  | 233       | 0.22%   |
| ALT Linux     | 223       | 0.21%   |
| CentOS        | 213       | 0.2%    |
| Peppermint    | 184       | 0.17%   |
| Nobara        | 183       | 0.17%   |
| RHEL          | 145       | 0.14%   |
| Deepin        | 123       | 0.11%   |
| LinuxFX       | 120       | 0.11%   |
| Artix         | 119       | 0.11%   |
| Solus         | 98        | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 2208      | 1.76%   |
| 5.10.14-desktop-1omv4002           | 2104      | 1.68%   |
| 5.16.7-desktop-1omv4003            | 1983      | 1.58%   |
| 5.15.0-56-generic                  | 1144      | 0.91%   |
| 4.18.16-desktop-1bP                | 1121      | 0.89%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 954       | 0.76%   |
| 5.4.0-58-generic                   | 948       | 0.76%   |
| 3.14.44-nrj-desktop-2rosa-x86_64   | 891       | 0.71%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 853       | 0.68%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 847       | 0.68%   |
| 6.1.1-desktop-1omv2290             | 838       | 0.67%   |
| 5.4.0-48-generic                   | 826       | 0.66%   |
| 5.15.0-58-generic                  | 822       | 0.66%   |
| 5.15.0-52-generic                  | 811       | 0.65%   |
| 5.4.0-52-generic                   | 800       | 0.64%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 785       | 0.63%   |
| 4.1.25-nrj-desktop-1rosa-x86_64    | 725       | 0.58%   |
| 5.4.0-26-generic                   | 724       | 0.58%   |
| 5.3.0-28-generic                   | 702       | 0.56%   |
| 5.15.0-46-generic                  | 680       | 0.54%   |
| 5.4.0-29-generic                   | 646       | 0.51%   |
| 5.11.0-27-generic                  | 627       | 0.5%    |
| 5.8.0-14-generic                   | 623       | 0.5%    |
| 4.1.15-nrj-desktop-1rosa-x86_64    | 621       | 0.5%    |
| 5.4.0-40-generic                   | 607       | 0.48%   |
| 5.3.0-40-generic                   | 603       | 0.48%   |
| 5.10.0-8-amd64                     | 599       | 0.48%   |
| 5.15.0-48-generic                  | 592       | 0.47%   |
| 5.3.0-46-generic                   | 588       | 0.47%   |
| 5.11.0-38-generic                  | 546       | 0.44%   |
| 6.2.6-desktop-1omv2390             | 545       | 0.43%   |
| 5.11.0-37-generic                  | 536       | 0.43%   |
| 5.4.0-91-generic                   | 533       | 0.42%   |
| 5.8.0-43-generic                   | 525       | 0.42%   |
| 5.0.0-37-generic                   | 516       | 0.41%   |
| 5.19.0-35-generic                  | 507       | 0.4%    |
| 5.4.0-65-generic                   | 506       | 0.4%    |
| 5.4.0-47-generic                   | 499       | 0.4%    |
| 5.15.0-41-generic                  | 498       | 0.4%    |
| 5.10.0-10-amd64                    | 498       | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 17873     | 15.05%  |
| 5.15.0  | 8488      | 7.15%   |
| 4.15.0  | 7183      | 6.05%   |
| 5.11.0  | 5841      | 4.92%   |
| 5.8.0   | 5815      | 4.9%    |
| 5.13.0  | 5236      | 4.41%   |
| 5.3.0   | 4639      | 3.91%   |
| 5.10.0  | 3891      | 3.28%   |
| 5.0.0   | 3009      | 2.53%   |
| 5.19.0  | 2584      | 2.18%   |
| 4.18.0  | 2163      | 1.82%   |
| 5.10.14 | 2127      | 1.79%   |
| 5.16.7  | 2023      | 1.7%    |
| 4.9.20  | 1285      | 1.08%   |
| 3.14.44 | 1284      | 1.08%   |
| 4.9.60  | 1238      | 1.04%   |
| 4.18.16 | 1149      | 0.97%   |
| 4.19.0  | 1061      | 0.89%   |
| 4.1.25  | 995       | 0.84%   |
| 6.1.1   | 977       | 0.82%   |
| 4.1.15  | 852       | 0.72%   |
| 5.10.74 | 826       | 0.7%    |
| 6.2.6   | 738       | 0.62%   |
| 4.1.34  | 644       | 0.54%   |
| 5.14.0  | 531       | 0.45%   |
| 4.1.38  | 507       | 0.43%   |
| 5.6.14  | 504       | 0.42%   |
| 4.9.124 | 490       | 0.41%   |
| 4.9.9   | 481       | 0.41%   |
| 5.17.5  | 475       | 0.4%    |
| 6.0.0   | 434       | 0.37%   |
| 6.0.12  | 402       | 0.34%   |
| 6.1.0   | 380       | 0.32%   |
| 5.18.0  | 339       | 0.29%   |
| 4.9.41  | 309       | 0.26%   |
| 4.9.155 | 308       | 0.26%   |
| 4.4.0   | 308       | 0.26%   |
| 4.9.76  | 307       | 0.26%   |
| 5.4.32  | 301       | 0.25%   |
| 4.1.16  | 294       | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 19542     | 16.86%  |
| 5.15    | 11440     | 9.87%   |
| 5.10    | 8750      | 7.55%   |
| 4.15    | 7209      | 6.22%   |
| 5.8     | 6970      | 6.01%   |
| 5.11    | 6820      | 5.88%   |
| 5.13    | 6127      | 5.29%   |
| 5.3     | 5174      | 4.46%   |
| 4.9     | 4454      | 3.84%   |
| 5.19    | 3710      | 3.2%    |
| 5.16    | 3627      | 3.13%   |
| 4.1     | 3567      | 3.08%   |
| 4.18    | 3366      | 2.9%    |
| 5.0     | 3164      | 2.73%   |
| 6.1     | 2775      | 2.39%   |
| 6.0     | 2331      | 2.01%   |
| 6.2     | 1856      | 1.6%    |
| 3.14    | 1740      | 1.5%    |
| 5.17    | 1626      | 1.4%    |
| 5.18    | 1547      | 1.33%   |
| 5.14    | 1537      | 1.33%   |
| 5.6     | 1449      | 1.25%   |
| 4.19    | 1358      | 1.17%   |
| 5.9     | 1278      | 1.1%    |
| 5.12    | 970       | 0.84%   |
| 5.7     | 847       | 0.73%   |
| 5.5     | 566       | 0.49%   |
| 4.4     | 415       | 0.36%   |
| 4.13    | 257       | 0.22%   |
| 5.1     | 227       | 0.2%    |
| 5.2     | 203       | 0.18%   |
| 3.10    | 153       | 0.13%   |
| 4.16    | 124       | 0.11%   |
| 4.14    | 90        | 0.08%   |
| 4.12    | 89        | 0.08%   |
| 4.10    | 88        | 0.08%   |
| 4.8     | 65        | 0.06%   |
| 4.20    | 59        | 0.05%   |
| 4.17    | 50        | 0.04%   |
| 4.0     | 39        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 98067     | 94.47%  |
| i686    | 5661      | 5.45%   |
| aarch64 | 48        | 0.05%   |
| armv7l  | 17        | 0.02%   |
| ppc     | 4         | 0.004%  |
| Unknown | 4         | 0.004%  |
| i586    | 3         | 0.003%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 43294     | 39.87%  |
| KDE5             | 19129     | 17.62%  |
| Unknown          | 11459     | 10.55%  |
| KDE4             | 8704      | 8.02%   |
| XFCE             | 7163      | 6.6%    |
| X-Cinnamon       | 6376      | 5.87%   |
| MATE             | 2647      | 2.44%   |
| KDE              | 2316      | 2.13%   |
| Cinnamon         | 1405      | 1.29%   |
| LXQt             | 1324      | 1.22%   |
| Pantheon         | 886       | 0.82%   |
| Unity            | 615       | 0.57%   |
| LXDE             | 576       | 0.53%   |
| i3               | 569       | 0.52%   |
| Budgie           | 545       | 0.5%    |
| GNOME Flashback  | 302       | 0.28%   |
| Deepin           | 248       | 0.23%   |
| awesome          | 119       | 0.11%   |
| sway             | 114       | 0.1%    |
| GNOME Classic    | 101       | 0.09%   |
| bspwm            | 78        | 0.07%   |
| Openbox          | 62        | 0.06%   |
| DWM              | 62        | 0.06%   |
| qtile            | 57        | 0.05%   |
| lightdm-xsession | 46        | 0.04%   |
| xmonad           | 44        | 0.04%   |
| Enlightenment    | 39        | 0.04%   |
| Trinity          | 38        | 0.03%   |
| ICEWM            | 36        | 0.03%   |
| Hyprland         | 36        | 0.03%   |
| LeftWM           | 18        | 0.02%   |
| i3-with-shmlog   | 16        | 0.01%   |
| BunsenLabs       | 14        | 0.01%   |
| fluxbox          | 13        | 0.01%   |
| herbstluftwm     | 10        | 0.01%   |
| fly              | 9         | 0.01%   |
| GNUstep          | 8         | 0.01%   |
| UKUI             | 7         | 0.01%   |
| Cutefish         | 7         | 0.01%   |
| xubuntu          | 6         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 83468     | 78.47%  |
| Wayland     | 15280     | 14.36%  |
| Unknown     | 6609      | 6.21%   |
| Tty         | 1009      | 0.95%   |
| Unspecified | 5         | 0.005%  |
| Web         | 2         | 0.002%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 47952     | 44.36%  |
| SDDM    | 17248     | 15.96%  |
| GDM     | 12600     | 11.66%  |
| GDM3    | 9154      | 8.47%   |
| KDM     | 8759      | 8.1%    |
| LightDM | 8493      | 7.86%   |
| TDM     | 3369      | 3.12%   |
| XDM     | 189       | 0.17%   |
| SLiM    | 98        | 0.09%   |
| LXDM    | 80        | 0.07%   |
| Ly      | 46        | 0.04%   |
| MDM     | 43        | 0.04%   |
| GREETD  | 24        | 0.02%   |
| NODM    | 16        | 0.01%   |
| FLY-DM  | 5         | 0.005%  |
| EMPTTY  | 4         | 0.004%  |
| SLIMSKI | 3         | 0.003%  |
| LDM     | 2         | 0.002%  |
| WDM     | 1         | 0.001%  |
| SU      | 1         | 0.001%  |
| CDM     | 1         | 0.001%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 36055     | 33.94%  |
| Unknown | 21613     | 20.34%  |
| de_DE   | 6435      | 6.06%   |
| ru_RU   | 5800      | 5.46%   |
| pt_BR   | 4907      | 4.62%   |
| en_GB   | 4259      | 4.01%   |
| fr_FR   | 3807      | 3.58%   |
| it_IT   | 2568      | 2.42%   |
| es_ES   | 2024      | 1.91%   |
| en_IN   | 1895      | 1.78%   |
| pl_PL   | 1641      | 1.54%   |
| en_CA   | 1402      | 1.32%   |
| C       | 1379      | 1.3%    |
| en_AU   | 1013      | 0.95%   |
| es_MX   | 742       | 0.7%    |
| cs_CZ   | 657       | 0.62%   |
| nl_NL   | 591       | 0.56%   |
| hu_HU   | 521       | 0.49%   |
| es_AR   | 484       | 0.46%   |
| pt_PT   | 449       | 0.42%   |
| tr_TR   | 430       | 0.4%    |
| zh_CN   | 413       | 0.39%   |
| en_ZA   | 399       | 0.38%   |
| de_AT   | 352       | 0.33%   |
| es_CL   | 314       | 0.3%    |
| es_CO   | 290       | 0.27%   |
| ru_UA   | 288       | 0.27%   |
| sv_SE   | 269       | 0.25%   |
| de_CH   | 254       | 0.24%   |
| en_NZ   | 220       | 0.21%   |
| fi_FI   | 219       | 0.21%   |
| en_IE   | 213       | 0.2%    |
| ro_RO   | 210       | 0.2%    |
| ja_JP   | 201       | 0.19%   |
| fr_BE   | 187       | 0.18%   |
| fr_CA   | 173       | 0.16%   |
| el_GR   | 171       | 0.16%   |
| da_DK   | 148       | 0.14%   |
| en_PH   | 143       | 0.13%   |
| nl_BE   | 142       | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 53303     | 50.34%  |
| EFI  | 52578     | 49.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 76305     | 71.67%  |
| Unknown             | 10659     | 10.01%  |
| Overlay             | 8618      | 8.09%   |
| Btrfs               | 8349      | 7.84%   |
| Xfs                 | 1039      | 0.98%   |
| Zfs                 | 617       | 0.58%   |
| Tmpfs               | 264       | 0.25%   |
| Ext2                | 246       | 0.23%   |
| Ext3                | 156       | 0.15%   |
| F2fs                | 112       | 0.11%   |
| Aufs                | 41        | 0.04%   |
| Reiserfs            | 16        | 0.02%   |
| XXXXXXX             | 12        | 0.01%   |
| Rootfs              | 11        | 0.01%   |
| Jfs                 | 10        | 0.01%   |
| XXXXX               | 4         | 0.004%  |
| XXX4                | 2         | 0.002%  |
| Fuse.fuse-overlayfs | 2         | 0.002%  |
| XXXfs               | 1         | 0.001%  |
| Ufs                 | 1         | 0.001%  |
| SquasXfs            | 1         | 0.001%  |
| OveXlay             | 1         | 0.001%  |
| Ntfs                | 1         | 0.001%  |
| Nfs                 | 1         | 0.001%  |
| ExX4                | 1         | 0.001%  |
| Bcachefs            | 1         | 0.001%  |
| 20G                 | 1         | 0.001%  |
| 12G                 | 1         | 0.001%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 52407     | 49.14%  |
| GPT     | 36747     | 34.46%  |
| MBR     | 17490     | 16.4%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93067     | 88.3%   |
| Yes       | 12327     | 11.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 77418     | 73.39%  |
| Yes       | 28068     | 26.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 20569     | 19.89%  |
| Hewlett-Packard        | 17921     | 17.33%  |
| Dell                   | 15850     | 15.32%  |
| ASUSTek Computer       | 12429     | 12.02%  |
| Acer                   | 10218     | 9.88%   |
| Toshiba                | 3161      | 3.06%   |
| Apple                  | 2875      | 2.78%   |
| Samsung Electronics    | 2692      | 2.6%    |
| MSI                    | 2075      | 2.01%   |
| Sony                   | 1643      | 1.59%   |
| HUAWEI                 | 986       | 0.95%   |
| Fujitsu                | 707       | 0.68%   |
| Valve                  | 675       | 0.65%   |
| Google                 | 665       | 0.64%   |
| Notebook               | 664       | 0.64%   |
| Packard Bell           | 654       | 0.63%   |
| Unknown                | 621       | 0.6%    |
| Positivo               | 503       | 0.49%   |
| Medion                 | 480       | 0.46%   |
| Timi                   | 371       | 0.36%   |
| Fujitsu Siemens        | 368       | 0.36%   |
| Alienware              | 332       | 0.32%   |
| eMachines              | 324       | 0.31%   |
| TUXEDO                 | 322       | 0.31%   |
| System76               | 318       | 0.31%   |
| Clevo                  | 293       | 0.28%   |
| LG Electronics         | 254       | 0.25%   |
| Intel                  | 209       | 0.2%    |
| Gigabyte Technology    | 201       | 0.19%   |
| Razer                  | 182       | 0.18%   |
| Gateway                | 177       | 0.17%   |
| Chuwi                  | 177       | 0.17%   |
| Panasonic              | 162       | 0.16%   |
| Pegatron               | 114       | 0.11%   |
| Framework              | 113       | 0.11%   |
| GPU Company            | 107       | 0.1%    |
| Schenker               | 97        | 0.09%   |
| PC Specialist          | 97        | 0.09%   |
| HONOR                  | 86        | 0.08%   |
| Avell High Performance | 82        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Unknown               | 1161      | 1.12%   |
| HP Notebook           | 716       | 0.69%   |
| Valve Jupiter         | 675       | 0.65%   |
| HP Pavilion g6        | 510       | 0.49%   |
| HP Pavilion dv6       | 483       | 0.47%   |
| Apple MacBook5,2      | 381       | 0.37%   |
| HP Pavilion dv7       | 311       | 0.3%    |
| HP Pavilion 15        | 308       | 0.3%    |
| HP Pavilion Notebook  | 280       | 0.27%   |
| Dell Latitude E6420   | 242       | 0.23%   |
| HP 15                 | 218       | 0.21%   |
| Dell Latitude E6430   | 218       | 0.21%   |
| Apple MacBookPro9,2   | 211       | 0.2%    |
| Apple MacBookAir7,2   | 208       | 0.2%    |
| Dell Latitude E6410   | 204       | 0.2%    |
| Acer Nitro AN515-54   | 204       | 0.2%    |
| Dell XPS 15 7590      | 191       | 0.18%   |
| Dell Inspiron 15-3567 | 190       | 0.18%   |
| HP Laptop 15-bw0xx    | 189       | 0.18%   |
| Dell XPS 15 9570      | 188       | 0.18%   |
| Apple MacBookPro8,1   | 184       | 0.18%   |
| HP Pavilion g7        | 180       | 0.17%   |
| Dell Latitude E6400   | 177       | 0.17%   |
| Dell Inspiron N5110   | 173       | 0.17%   |
| HP EliteBook 840 G3   | 159       | 0.15%   |
| HP EliteBook 8460p    | 157       | 0.15%   |
| Dell Inspiron 5570    | 157       | 0.15%   |
| Dell Inspiron 1545    | 157       | 0.15%   |
| HP Laptop 15-db0xxx   | 150       | 0.15%   |
| HP Laptop 15-bs0xx    | 150       | 0.15%   |
| HP EliteBook 8470p    | 149       | 0.14%   |
| Dell XPS 15 9500      | 148       | 0.14%   |
| Dell XPS 13 9360      | 145       | 0.14%   |
| Lenovo G50-45 80E3    | 143       | 0.14%   |
| Dell Inspiron 3542    | 143       | 0.14%   |
| Dell Latitude D630    | 142       | 0.14%   |
| Dell XPS 13 9370      | 141       | 0.14%   |
| Dell Inspiron 3521    | 140       | 0.14%   |
| ASUS UX31E            | 139       | 0.13%   |
| HP Laptop 15-da0xxx   | 138       | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 9954      | 9.62%   |
| Acer Aspire           | 6961      | 6.73%   |
| Dell Latitude         | 5305      | 5.13%   |
| Dell Inspiron         | 5199      | 5.03%   |
| Lenovo IdeaPad        | 4907      | 4.74%   |
| HP Pavilion           | 4196      | 4.06%   |
| HP EliteBook          | 2754      | 2.66%   |
| Toshiba Satellite     | 2673      | 2.58%   |
| HP ProBook            | 2345      | 2.27%   |
| HP Laptop             | 2257      | 2.18%   |
| ASUS VivoBook         | 2159      | 2.09%   |
| Dell XPS              | 2035      | 1.97%   |
| Unknown               | 1161      | 1.12%   |
| Dell Precision        | 1119      | 1.08%   |
| Dell Vostro           | 1076      | 1.04%   |
| HP Compaq             | 906       | 0.88%   |
| Acer Nitro            | 836       | 0.81%   |
| Lenovo Legion         | 739       | 0.71%   |
| HP Notebook           | 719       | 0.7%    |
| Valve Jupiter         | 675       | 0.65%   |
| Acer Swift            | 649       | 0.63%   |
| ASUS ROG              | 645       | 0.62%   |
| Fujitsu LIFEBOOK      | 600       | 0.58%   |
| HP ENVY               | 577       | 0.56%   |
| Packard Bell EasyNote | 575       | 0.56%   |
| ASUS ZenBook          | 556       | 0.54%   |
| HP ZBook              | 547       | 0.53%   |
| HP 250                | 493       | 0.48%   |
| Lenovo ThinkBook      | 486       | 0.47%   |
| Acer TravelMate       | 463       | 0.45%   |
| Apple MacBook5        | 447       | 0.43%   |
| ASUS ASUS             | 424       | 0.41%   |
| Acer Extensa          | 417       | 0.4%    |
| ASUS TUF              | 368       | 0.36%   |
| Lenovo Yoga           | 359       | 0.35%   |
| HP OMEN               | 347       | 0.34%   |
| HP 255                | 306       | 0.3%    |
| Apple MacBookAir7     | 302       | 0.29%   |
| HP 15                 | 295       | 0.29%   |
| Apple MacBookPro8     | 289       | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 9367      | 9.06%   |
| 2011    | 9030      | 8.73%   |
| 2012    | 8677      | 8.39%   |
| 2018    | 8278      | 8%      |
| 2020    | 8200      | 7.93%   |
| 2013    | 7389      | 7.14%   |
| 2021    | 6544      | 6.33%   |
| 2017    | 6453      | 6.24%   |
| 2010    | 6129      | 5.93%   |
| 2015    | 5823      | 5.63%   |
| 2014    | 5685      | 5.5%    |
| 2016    | 5569      | 5.38%   |
| 2008    | 4625      | 4.47%   |
| 2009    | 4167      | 4.03%   |
| 2022    | 2959      | 2.86%   |
| 2007    | 2724      | 2.63%   |
| 2006    | 1076      | 1.04%   |
| 2005    | 329       | 0.32%   |
| Unknown | 174       | 0.17%   |
| 2023    | 108       | 0.1%    |
| 2004    | 78        | 0.08%   |
| 2003    | 37        | 0.04%   |
| 2002    | 9         | 0.01%   |
| 1999    | 3         | 0.003%  |
| 2001    | 2         | 0.002%  |
| 2000    | 1         | 0.001%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 103436    | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 94473     | 90.54%  |
| Enabled  | 9872      | 9.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 102454    | 99.05%  |
| Yes  | 986       | 0.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 28637     | 27.19%  |
| 3.01-4.0    | 25515     | 24.23%  |
| 8.01-16.0   | 17074     | 16.21%  |
| 16.01-24.0  | 15322     | 14.55%  |
| 1.01-2.0    | 6935      | 6.59%   |
| 32.01-64.0  | 5361      | 5.09%   |
| 2.01-3.0    | 3140      | 2.98%   |
| 0.51-1.0    | 1169      | 1.11%   |
| 24.01-32.0  | 956       | 0.91%   |
| 64.01-256.0 | 894       | 0.85%   |
| Unknown     | 233       | 0.22%   |
| 0.01-0.5    | 72        | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 42459     | 36.79%  |
| 2.01-3.0   | 26943     | 23.35%  |
| 4.01-8.0   | 13572     | 11.76%  |
| 0.51-1.0   | 13343     | 11.56%  |
| 3.01-4.0   | 13206     | 11.44%  |
| 8.01-16.0  | 3475      | 3.01%   |
| 0.01-0.5   | 1638      | 1.42%   |
| 16.01-24.0 | 330       | 0.29%   |
| Unknown    | 292       | 0.25%   |
| 24.01-32.0 | 109       | 0.09%   |
| 32.01-64.0 | 32        | 0.03%   |
| 0          | 3         | 0.003%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 78536     | 74.13%  |
| 2       | 23455     | 22.14%  |
| 3       | 2608      | 2.46%   |
| 0       | 926       | 0.87%   |
| 4       | 312       | 0.29%   |
| 5       | 68        | 0.06%   |
| 6       | 22        | 0.02%   |
| 7       | 15        | 0.01%   |
| 8       | 3         | 0.003%  |
| 9       | 2         | 0.002%  |
| 10      | 1         | 0.001%  |
| Unknown | 1         | 0.001%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61755     | 59.27%  |
| Yes       | 42432     | 40.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86013     | 82.87%  |
| No        | 17781     | 17.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101642    | 98.16%  |
| No        | 1908      | 1.84%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77867     | 74.26%  |
| No        | 26984     | 25.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 15001     | 14.31%  |
| Russia       | 11664     | 11.13%  |
| Germany      | 9338      | 8.91%   |
| Brazil       | 7078      | 6.75%   |
| France       | 4802      | 4.58%   |
| Unknown      | 3890      | 3.71%   |
| Italy        | 3879      | 3.7%    |
| UK           | 3519      | 3.36%   |
| India        | 2958      | 2.82%   |
| Spain        | 2742      | 2.62%   |
| Poland       | 2718      | 2.59%   |
| Canada       | 2401      | 2.29%   |
| Hungary      | 2027      | 1.93%   |
| Netherlands  | 1963      | 1.87%   |
| Ukraine      | 1767      | 1.69%   |
| Mexico       | 1330      | 1.27%   |
| Australia    | 1282      | 1.22%   |
| Czechia      | 1151      | 1.1%    |
| Turkey       | 1115      | 1.06%   |
| Romania      | 1061      | 1.01%   |
| Sweden       | 965       | 0.92%   |
| Belgium      | 945       | 0.9%    |
| Portugal     | 935       | 0.89%   |
| Switzerland  | 916       | 0.87%   |
| Austria      | 915       | 0.87%   |
| Argentina    | 893       | 0.85%   |
| Indonesia    | 779       | 0.74%   |
| China        | 699       | 0.67%   |
| Finland      | 674       | 0.64%   |
| Greece       | 634       | 0.6%    |
| Colombia     | 597       | 0.57%   |
| Belarus      | 585       | 0.56%   |
| Chile        | 570       | 0.54%   |
| South Africa | 563       | 0.54%   |
| Bulgaria     | 549       | 0.52%   |
| Japan        | 528       | 0.5%    |
| Norway       | 519       | 0.5%    |
| Denmark      | 481       | 0.46%   |
| Iran         | 394       | 0.38%   |
| Slovakia     | 385       | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Unknown           | 3910      | 3.49%   |
| Moscow            | 2555      | 2.28%   |
| St Petersburg     | 1144      | 1.02%   |
| Berlin            | 901       | 0.8%    |
| Sao Paulo         | 870       | 0.78%   |
| Budapest          | 842       | 0.75%   |
| Paris             | 823       | 0.73%   |
| Warsaw            | 649       | 0.58%   |
| Bangor            | 628       | 0.56%   |
| Milan             | 594       | 0.53%   |
| Vienna            | 560       | 0.5%    |
| Prague            | 498       | 0.44%   |
| Munich            | 488       | 0.44%   |
| Madrid            | 476       | 0.42%   |
| Kyiv              | 465       | 0.41%   |
| Rome              | 454       | 0.4%    |
| Istanbul          | 430       | 0.38%   |
| Rio de Janeiro    | 386       | 0.34%   |
| Amsterdam         | 385       | 0.34%   |
| Novosibirsk       | 380       | 0.34%   |
| Krasnodar         | 380       | 0.34%   |
| Bengaluru         | 377       | 0.34%   |
| Hamburg           | 363       | 0.32%   |
| Sydney            | 358       | 0.32%   |
| Bucharest         | 346       | 0.31%   |
| Voronezh          | 342       | 0.3%    |
| Athens            | 339       | 0.3%    |
| Pecherskoye       | 337       | 0.3%    |
| Barcelona         | 331       | 0.3%    |
| Helsinki          | 330       | 0.29%   |
| Yekaterinburg     | 329       | 0.29%   |
| Frankfurt am Main | 312       | 0.28%   |
| Sofia             | 304       | 0.27%   |
| London            | 302       | 0.27%   |
| Mexico City       | 299       | 0.27%   |
| Melbourne         | 294       | 0.26%   |
| Minsk             | 288       | 0.26%   |
| Bogotá           | 246       | 0.22%   |
| Nizhniy Novgorod  | 243       | 0.22%   |
| Cologne           | 242       | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 17885     | 24212  | 14.04%  |
| WDC                         | 16860     | 21517  | 13.24%  |
| Seagate                     | 15894     | 20469  | 12.48%  |
| Toshiba                     | 11390     | 14223  | 8.94%   |
| Unknown                     | 7030      | 9202   | 5.52%   |
| SanDisk                     | 6981      | 8941   | 5.48%   |
| Kingston                    | 6549      | 8132   | 5.14%   |
| Hitachi                     | 5177      | 6455   | 4.06%   |
| SK hynix                    | 4546      | 5654   | 3.57%   |
| HGST                        | 4061      | 5287   | 3.19%   |
| Intel                       | 3689      | 4844   | 2.9%    |
| Crucial                     | 3428      | 4438   | 2.69%   |
| Micron Technology           | 2516      | 3079   | 1.98%   |
| A-DATA Technology           | 1724      | 2219   | 1.35%   |
| Fujitsu                     | 1304      | 1513   | 1.02%   |
| Apple                       | 1287      | 1637   | 1.01%   |
| KIOXIA                      | 1064      | 1329   | 0.84%   |
| China                       | 981       | 1221   | 0.77%   |
| LITEON                      | 760       | 915    | 0.6%    |
| Phison                      | 702       | 846    | 0.55%   |
| SPCC                        | 590       | 760    | 0.46%   |
| Transcend                   | 555       | 681    | 0.44%   |
| PNY                         | 509       | 633    | 0.4%    |
| Unknown                     | 448       | 501    | 0.35%   |
| Intenso                     | 445       | 551    | 0.35%   |
| LITEONIT                    | 439       | 566    | 0.34%   |
| Silicon Motion              | 418       | 525    | 0.33%   |
| JMicron Technology          | 367       | 406    | 0.29%   |
| Patriot                     | 362       | 453    | 0.28%   |
| OCZ                         | 362       | 448    | 0.28%   |
| Phison Electronics          | 355       | 404    | 0.28%   |
| GOODRAM                     | 349       | 431    | 0.27%   |
| KingSpec                    | 302       | 383    | 0.24%   |
| Kingston Technology Company | 288       | 319    | 0.23%   |
| Micron/Crucial Technology   | 266       | 325    | 0.21%   |
| Netac                       | 246       | 304    | 0.19%   |
| Plextor                     | 224       | 295    | 0.18%   |
| Corsair                     | 224       | 274    | 0.18%   |
| Apacer                      | 224       | 279    | 0.18%   |
| ADATA Technology            | 224       | 267    | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB                  | 2094      | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1710      | 1.29%   |
| Toshiba MQ01ABD100 1TB                            | 1524      | 1.15%   |
| Toshiba MQ01ABF050 500GB                          | 1370      | 1.04%   |
| Seagate ST500LT012-1DG142 500GB                   | 1317      | 1%      |
| Kingston SA400S37240G 240GB SSD                   | 1267      | 0.96%   |
| Unknown MMC Card  32GB                            | 1240      | 0.94%   |
| Toshiba MQ04ABF100 1TB                            | 1129      | 0.85%   |
| Seagate ST9500325AS 500GB                         | 1019      | 0.77%   |
| HGST HTS721010A9E630 1TB                          | 999       | 0.76%   |
| Unknown MMC Card  64GB                            | 875       | 0.66%   |
| Samsung NVMe SSD Drive 512GB                      | 861       | 0.65%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 760       | 0.58%   |
| SanDisk NVMe SSD Drive 512GB                      | 738       | 0.56%   |
| Samsung SSD 860 EVO 500GB                         | 729       | 0.55%   |
| HGST HTS545050A7E680 500GB                        | 706       | 0.53%   |
| Kingston SA400S37120G 120GB SSD                   | 696       | 0.53%   |
| Samsung NVMe SSD Drive 256GB                      | 663       | 0.5%    |
| Kingston SA400S37480G 480GB SSD                   | 657       | 0.5%    |
| HGST HTS541010A9E680 1TB                          | 641       | 0.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 613       | 0.46%   |
| Intel NVMe SSD Drive 512GB                        | 606       | 0.46%   |
| Samsung SSD 850 EVO 250GB                         | 578       | 0.44%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 554       | 0.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 536       | 0.41%   |
| Samsung SSD 850 EVO 500GB                         | 519       | 0.39%   |
| SK hynix NVMe SSD Drive 512GB                     | 517       | 0.39%   |
| Seagate ST500LT012-9WS142 500GB                   | 510       | 0.39%   |
| Unknown MMC Card  128GB                           | 489       | 0.37%   |
| Seagate ST9320325AS 320GB                         | 486       | 0.37%   |
| Crucial CT500MX500SSD1 500GB                      | 478       | 0.36%   |
| Kingston SV300S37A120G 120GB SSD                  | 472       | 0.36%   |
| HGST HTS725050A7E630 500GB                        | 471       | 0.36%   |
| SanDisk NVMe SSD Drive 256GB                      | 464       | 0.35%   |
| Crucial CT240BX500SSD1 240GB                      | 463       | 0.35%   |
| Unknown                                           | 448       | 0.34%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 411       | 0.31%   |
| Seagate ST1000LM048-2E7172 1TB                    | 407       | 0.31%   |
| Unknown MMC Card  16GB                            | 403       | 0.31%   |
| Samsung SSD 860 EVO 250GB                         | 392       | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15613     | 20022  | 31.3%   |
| WDC                 | 12578     | 15920  | 25.22%  |
| Toshiba             | 8720      | 10776  | 17.48%  |
| Hitachi             | 5176      | 6454   | 10.38%  |
| HGST                | 4060      | 5286   | 8.14%   |
| Samsung Electronics | 1302      | 1578   | 2.61%   |
| Fujitsu             | 1296      | 1500   | 2.6%    |
| Unknown             | 355       | 458    | 0.71%   |
| JMicron Technology  | 222       | 254    | 0.45%   |
| Apple               | 149       | 168    | 0.3%    |
| IBM/Hitachi         | 52        | 60     | 0.1%    |
| ASMT                | 46        | 88     | 0.09%   |
| Intenso             | 42        | 53     | 0.08%   |
| USB3.0              | 37        | 42     | 0.07%   |
| HGST HTS            | 30        | 41     | 0.06%   |
| ASMedia             | 26        | 30     | 0.05%   |
| LaCie               | 14        | 19     | 0.03%   |
| PHD 3.0             | 13        | 13     | 0.03%   |
| Pioneer             | 9         | 18     | 0.02%   |
| SAGE                | 8         | 11     | 0.02%   |
| MARSHAL             | 8         | 10     | 0.02%   |
| KESU                | 8         | 8      | 0.02%   |
| Inateck             | 8         | 8      | 0.02%   |
| USB                 | 7         | 8      | 0.01%   |
| StoreJet            | 7         | 8      | 0.01%   |
| Maxone              | 7         | 7      | 0.01%   |
| SABRENT             | 6         | 9      | 0.01%   |
| Hewlett-Packard     | 6         | 7      | 0.01%   |
| Apricorn            | 6         | 9      | 0.01%   |
| SILICONMOTION       | 5         | 6      | 0.01%   |
| Generic-            | 4         | 5      | 0.01%   |
| IBM                 | 3         | 4      | 0.01%   |
| External            | 3         | 3      | 0.01%   |
| DAS                 | 3         | 13     | 0.01%   |
| ACASIS              | 3         | 3      | 0.01%   |
| WD MediaMax         | 2         | 3      | 0.004%  |
| RSH-339             | 2         | 2      | 0.004%  |
| QNAP                | 2         | 3      | 0.004%  |
| QC-FT-D             | 2         | 2      | 0.004%  |
| Phison              | 2         | 3      | 0.004%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8298      | 11041  | 21.4%   |
| Kingston            | 5204      | 6464   | 13.42%  |
| SanDisk             | 4127      | 5334   | 10.64%  |
| Crucial             | 3158      | 4126   | 8.14%   |
| WDC                 | 2052      | 2603   | 5.29%   |
| A-DATA Technology   | 1356      | 1764   | 3.5%    |
| Intel               | 1125      | 1425   | 2.9%    |
| Micron Technology   | 1055      | 1314   | 2.72%   |
| SK hynix            | 1032      | 1284   | 2.66%   |
| China               | 969       | 1206   | 2.5%    |
| Toshiba             | 870       | 1107   | 2.24%   |
| Apple               | 811       | 934    | 2.09%   |
| LITEON              | 685       | 831    | 1.77%   |
| SPCC                | 533       | 696    | 1.37%   |
| Transcend           | 525       | 642    | 1.35%   |
| PNY                 | 476       | 595    | 1.23%   |
| LITEONIT            | 439       | 566    | 1.13%   |
| OCZ                 | 361       | 447    | 0.93%   |
| Patriot             | 351       | 440    | 0.91%   |
| Intenso             | 343       | 419    | 0.88%   |
| GOODRAM             | 341       | 423    | 0.88%   |
| KingSpec            | 293       | 371    | 0.76%   |
| Netac               | 224       | 274    | 0.58%   |
| Plextor             | 215       | 285    | 0.55%   |
| Apacer              | 205       | 258    | 0.53%   |
| Corsair             | 176       | 218    | 0.45%   |
| Team                | 165       | 207    | 0.43%   |
| Hewlett-Packard     | 136       | 184    | 0.35%   |
| Lexar               | 119       | 146    | 0.31%   |
| Unknown             | 119       | 134    | 0.31%   |
| KingDian            | 110       | 149    | 0.28%   |
| Gigabyte Technology | 108       | 140    | 0.28%   |
| Seagate             | 107       | 134    | 0.28%   |
| Smartbuy            | 101       | 119    | 0.26%   |
| ASMT                | 93        | 104    | 0.24%   |
| FORESEE             | 92        | 105    | 0.24%   |
| TO Exter            | 78        | 98     | 0.2%    |
| BHT                 | 78        | 96     | 0.2%    |
| Dogfish             | 73        | 96     | 0.19%   |
| Unknown             | 72        | 80     | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 48208     | 62955  | 39.62%  |
| SSD     | 36132     | 49442  | 29.7%   |
| NVMe    | 28843     | 39334  | 23.71%  |
| MMC     | 6708      | 8842   | 5.51%   |
| Unknown | 1776      | 2134   | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 75651     | 109269 | 65.6%   |
| NVMe | 28740     | 39101  | 24.92%  |
| MMC  | 6708      | 8842   | 5.82%   |
| SAS  | 4228      | 5495   | 3.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 57757     | 79115  | 69.63%  |
| 0.51-1.0   | 22686     | 29827  | 27.35%  |
| 1.01-2.0   | 1763      | 2452   | 2.13%   |
| 3.01-4.0   | 450       | 584    | 0.54%   |
| 4.01-10.0  | 214       | 309    | 0.26%   |
| 10.01-20.0 | 56        | 79     | 0.07%   |
| 2.01-3.0   | 20        | 27     | 0.02%   |
| 0          | 3         | 4      | 0.004%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 31461     | 28.49%  |
| 251-500        | 27762     | 25.14%  |
| 501-1000       | 15506     | 14.04%  |
| 1-20           | 9481      | 8.58%   |
| 51-100         | 8213      | 7.44%   |
| 21-50          | 5597      | 5.07%   |
| 1001-2000      | 5538      | 5.01%   |
| Unknown        | 4090      | 3.7%    |
| More than 3000 | 1501      | 1.36%   |
| 2001-3000      | 1296      | 1.17%   |
| 0              | 1         | 0.001%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 49732     | 43.44%  |
| 21-50          | 20325     | 17.75%  |
| 101-250        | 13802     | 12.05%  |
| 51-100         | 13045     | 11.39%  |
| 251-500        | 7429      | 6.49%   |
| Unknown        | 4090      | 3.57%   |
| 501-1000       | 3981      | 3.48%   |
| 1001-2000      | 1387      | 1.21%   |
| More than 3000 | 358       | 0.31%   |
| 2001-3000      | 319       | 0.28%   |
| 0              | 25        | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 375       | 484    | 3.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 268       | 326    | 2.4%    |
| Seagate ST500LT012-9WS142 500GB     | 263       | 338    | 2.36%   |
| HGST HTS545050A7E680 500GB          | 228       | 300    | 2.05%   |
| Seagate ST500LT012-1DG142 500GB     | 209       | 251    | 1.87%   |
| Seagate ST9320325AS 320GB           | 203       | 252    | 1.82%   |
| Seagate ST1000LM035-1RK172 970GB    | 158       | 173    | 1.42%   |
| Toshiba MQ01ABD100 1TB              | 154       | 180    | 1.38%   |
| HGST HTS541010A9E680 1TB            | 144       | 179    | 1.29%   |
| Seagate ST9250315AS 250GB           | 141       | 172    | 1.26%   |
| Toshiba MQ01ABF050 500GB            | 121       | 157    | 1.09%   |
| SanDisk SSD U100 256GB              | 121       | 121    | 1.09%   |
| HGST HTS545050A7E380 500GB          | 119       | 166    | 1.07%   |
| Hitachi HTS543232A7A384 320GB       | 115       | 139    | 1.03%   |
| HGST HTS721010A9E630 1TB            | 111       | 133    | 1%      |
| Hitachi HTS547575A9E384 752GB       | 102       | 129    | 0.91%   |
| HGST HTS725050A7E630 500GB          | 102       | 119    | 0.91%   |
| Seagate ST320LT020-9YG142 320GB     | 99        | 144    | 0.89%   |
| Seagate ST9500420AS 500GB           | 98        | 122    | 0.88%   |
| Hitachi HTS545050A7E380 500GB       | 97        | 119    | 0.87%   |
| Toshiba MQ01ABD050 500GB            | 92        | 110    | 0.83%   |
| Hitachi HTS547550A9E384 500GB       | 85        | 115    | 0.76%   |
| Hitachi HTS545050B9A300 500GB       | 85        | 110    | 0.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 83        | 98     | 0.74%   |
| Hitachi HTS545025B9A300 250GB       | 82        | 102    | 0.74%   |
| Toshiba MQ01ABD075 752GB            | 74        | 87     | 0.66%   |
| Hitachi HTS545032B9A300 320GB       | 69        | 82     | 0.62%   |
| Samsung Electronics HM160HI 160GB   | 66        | 84     | 0.59%   |
| Seagate ST500LM021-1KJ152 500GB     | 63        | 71     | 0.57%   |
| Seagate ST320LT012-9WS14C 320GB     | 61        | 85     | 0.55%   |
| Hitachi HTS541612J9SA00 120GB       | 61        | 75     | 0.55%   |
| Toshiba MK3265GSX 320GB             | 57        | 71     | 0.51%   |
| Seagate ST320LT007-9ZV142 320GB     | 56        | 64     | 0.5%    |
| Hitachi HTS542516K9SA00 160GB       | 54        | 72     | 0.48%   |
| WDC WD10JPVX-22JC3T0 1TB            | 53        | 64     | 0.48%   |
| Hitachi HTS541680J9SA00 80GB        | 53        | 65     | 0.48%   |
| Hitachi HTS542512K9SA00 120GB       | 51        | 62     | 0.46%   |
| Hitachi HTS723232A7A364 320GB       | 50        | 59     | 0.45%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 46        | 53     | 0.41%   |
| Seagate ST9320423AS 320GB           | 45        | 57     | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3007      | 3704   | 27.11%  |
| Hitachi             | 1620      | 1988   | 14.61%  |
| Toshiba             | 1537      | 1874   | 13.86%  |
| WDC                 | 1504      | 1811   | 13.56%  |
| HGST                | 857       | 1087   | 7.73%   |
| Samsung Electronics | 492       | 608    | 4.44%   |
| SanDisk             | 329       | 358    | 2.97%   |
| Fujitsu             | 231       | 272    | 2.08%   |
| Kingston            | 225       | 264    | 2.03%   |
| SK hynix            | 207       | 240    | 1.87%   |
| Intel               | 177       | 213    | 1.6%    |
| Crucial             | 148       | 180    | 1.33%   |
| Micron Technology   | 109       | 128    | 0.98%   |
| A-DATA Technology   | 107       | 126    | 0.96%   |
| China               | 46        | 54     | 0.41%   |
| LITEON              | 44        | 50     | 0.4%    |
| OCZ                 | 36        | 46     | 0.32%   |
| Apple               | 32        | 33     | 0.29%   |
| LITEONIT            | 31        | 44     | 0.28%   |
| KingSpec            | 27        | 38     | 0.24%   |
| SPCC                | 26        | 27     | 0.23%   |
| Corsair             | 22        | 23     | 0.2%    |
| IBM/Hitachi         | 18        | 18     | 0.16%   |
| Plextor             | 15        | 17     | 0.14%   |
| Transcend           | 12        | 14     | 0.11%   |
| Netac               | 10        | 12     | 0.09%   |
| Unknown             | 9         | 10     | 0.08%   |
| SSSTC               | 8         | 8      | 0.07%   |
| Mushkin             | 8         | 8      | 0.07%   |
| Intenso             | 8         | 8      | 0.07%   |
| Kingmax             | 6         | 6      | 0.05%   |
| JMicron Technology  | 6         | 6      | 0.05%   |
| HGST HTS            | 6         | 8      | 0.05%   |
| ASMT                | 6         | 7      | 0.05%   |
| AMD                 | 6         | 8      | 0.05%   |
| Team                | 5         | 5      | 0.05%   |
| PNY                 | 5         | 10     | 0.05%   |
| Patriot             | 5         | 7      | 0.05%   |
| Lenovo              | 5         | 6      | 0.05%   |
| KingDian            | 5         | 8      | 0.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3006      | 3703   | 33.48%  |
| Hitachi             | 1620      | 1988   | 18.04%  |
| Toshiba             | 1484      | 1809   | 16.53%  |
| WDC                 | 1426      | 1733   | 15.88%  |
| HGST                | 857       | 1087   | 9.55%   |
| Samsung Electronics | 295       | 369    | 3.29%   |
| Fujitsu             | 231       | 272    | 2.57%   |
| IBM/Hitachi         | 18        | 18     | 0.2%    |
| Apple               | 14        | 15     | 0.16%   |
| HGST HTS            | 6         | 8      | 0.07%   |
| MARSHAL             | 4         | 5      | 0.04%   |
| ASMedia             | 4         | 4      | 0.04%   |
| JMicron Technology  | 3         | 3      | 0.03%   |
| Unknown             | 2         | 2      | 0.02%   |
| ASMT                | 2         | 3      | 0.02%   |
| USB3.0              | 1         | 2      | 0.01%   |
| Magnetic Data       | 1         | 1      | 0.01%   |
| LaCie               | 1         | 1      | 0.01%   |
| IBM                 | 1         | 1      | 0.01%   |
| CSD                 | 1         | 2      | 0.01%   |
| Apricorn            | 1         | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 8858      | 11027  | 80.81%  |
| SSD     | 1870      | 2176   | 17.06%  |
| NVMe    | 230       | 281    | 2.1%    |
| Unknown | 3         | 3      | 0.03%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 7         | 9      | 2.5%    |
| Seagate ST500LT012-1DG142 500GB     | 7         | 7      | 2.5%    |
| Samsung Electronics HM321HI 320GB   | 7         | 8      | 2.5%    |
| HGST HTS721010A9E630 1TB            | 7         | 8      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 6      | 2.14%   |
| Hitachi HTS545050A7E380 500GB       | 6         | 7      | 2.14%   |
| HGST HTS545050A7E680 500GB          | 6         | 6      | 2.14%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 5         | 6      | 1.79%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 5         | 6      | 1.79%   |
| Toshiba MQ01ABD100 1TB              | 5         | 5      | 1.79%   |
| Seagate ST9320325AS 320GB           | 5         | 5      | 1.79%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 4         | 10     | 1.43%   |
| Toshiba MK6465GSX 640GB             | 4         | 6      | 1.43%   |
| Toshiba MK3265GSX 320GB             | 4         | 4      | 1.43%   |
| HGST HTS541010A9E680 1TB            | 4         | 4      | 1.43%   |
| WDC WD7500BPVT-22HXZT1 752GB        | 3         | 4      | 1.07%   |
| WDC WD5000BEVT-22ZAT0 500GB         | 3         | 3      | 1.07%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 3      | 1.07%   |
| WDC WD2500BEVT-22A23T0 250GB        | 3         | 4      | 1.07%   |
| WDC WD10SPZX-21Z10T0 1TB            | 3         | 3      | 1.07%   |
| Toshiba MQ01ABD050 500GB            | 3         | 3      | 1.07%   |
| Toshiba MK6475GSX 640GB             | 3         | 3      | 1.07%   |
| Toshiba MK5065GSXN 500GB            | 3         | 3      | 1.07%   |
| Toshiba MK3259GSXP 320GB            | 3         | 4      | 1.07%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 3      | 1.07%   |
| Samsung Electronics HM160HI 160GB   | 3         | 3      | 1.07%   |
| Hitachi HTS547575A9E384 752GB       | 3         | 4      | 1.07%   |
| Hitachi HTS547550A9E384 500GB       | 3         | 3      | 1.07%   |
| Crucial CT500P2SSD8 500GB           | 3         | 3      | 1.07%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 2         | 2      | 0.71%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 2         | 2      | 0.71%   |
| WDC WD3200BEVT-11ZCT0 320GB         | 2         | 2      | 0.71%   |
| WDC WD2500LPCX-24C6HT0 250GB        | 2         | 2      | 0.71%   |
| WDC WD2500BEVS-22UST0 250GB         | 2         | 2      | 0.71%   |
| WDC WD1600BEVS-22RST0 160GB         | 2         | 2      | 0.71%   |
| Toshiba MK3275GSX 320GB             | 2         | 2      | 0.71%   |
| Toshiba MK3265GSXN 320GB            | 2         | 2      | 0.71%   |
| Toshiba MK2565GSX 250GB             | 2         | 2      | 0.71%   |
| Seagate ST9500420AS 500GB           | 2         | 4      | 0.71%   |
| Seagate ST9250315AS 250GB           | 2         | 2      | 0.71%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 80        | 92     | 28.57%  |
| Toshiba             | 52        | 60     | 18.57%  |
| Seagate             | 46        | 52     | 16.43%  |
| Samsung Electronics | 36        | 38     | 12.86%  |
| Hitachi             | 24        | 27     | 8.57%   |
| HGST                | 22        | 24     | 7.86%   |
| Intel               | 4         | 4      | 1.43%   |
| Crucial             | 4         | 4      | 1.43%   |
| Fujitsu             | 2         | 2      | 0.71%   |
| Apple               | 2         | 3      | 0.71%   |
| SK hynix            | 1         | 1      | 0.36%   |
| SanDisk             | 1         | 1      | 0.36%   |
| Phison              | 1         | 1      | 0.36%   |
| Micron Technology   | 1         | 1      | 0.36%   |
| Maxtor              | 1         | 1      | 0.36%   |
| LITEON              | 1         | 2      | 0.36%   |
| Kingston            | 1         | 1      | 0.36%   |
| Acer                | 1         | 1      | 0.36%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 57436     | 89411  | 51.99%  |
| Works    | 41919     | 59490  | 37.95%  |
| Malfunc  | 10831     | 13487  | 9.8%    |
| Failed   | 280       | 315    | 0.25%   |
| Limited  | 4         | 4      | 0.004%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 73698     | 62.74%  |
| AMD                              | 12983     | 11.05%  |
| Samsung Electronics              | 9355      | 7.96%   |
| SanDisk                          | 4863      | 4.14%   |
| SK hynix                         | 3396      | 2.89%   |
| Toshiba America Info Systems     | 1893      | 1.61%   |
| Kingston Technology Company      | 1617      | 1.38%   |
| Micron Technology                | 1474      | 1.25%   |
| Nvidia                           | 1311      | 1.12%   |
| Phison Electronics               | 1195      | 1.02%   |
| KIOXIA                           | 1110      | 0.94%   |
| ADATA Technology                 | 614       | 0.52%   |
| Silicon Motion                   | 559       | 0.48%   |
| Micron/Crucial Technology        | 513       | 0.44%   |
| Silicon Integrated Systems [SiS] | 426       | 0.36%   |
| Union Memory (Shenzhen)          | 347       | 0.3%    |
| Solid State Storage Technology   | 324       | 0.28%   |
| Apple                            | 311       | 0.26%   |
| Realtek Semiconductor            | 207       | 0.18%   |
| Lite-On Technology               | 183       | 0.16%   |
| Lenovo                           | 142       | 0.12%   |
| Marvell Technology Group         | 131       | 0.11%   |
| VIA Technologies                 | 122       | 0.1%    |
| JMicron Technology               | 122       | 0.1%    |
| O2 Micro                         | 91        | 0.08%   |
| Shenzhen Longsys Electronics     | 73        | 0.06%   |
| Yangtze Memory Technologies      | 66        | 0.06%   |
| Seagate Technology               | 58        | 0.05%   |
| MAXIO Technology (Hangzhou)      | 51        | 0.04%   |
| ASMedia Technology               | 49        | 0.04%   |
| INNOGRIT                         | 43        | 0.04%   |
| Silicon Image                    | 40        | 0.03%   |
| Biwin Storage Technology         | 32        | 0.03%   |
| Transcend                        | 12        | 0.01%   |
| Netac Technology                 | 11        | 0.01%   |
| ULi Electronics                  | 10        | 0.01%   |
| Unknown                          | 9         | 0.01%   |
| Zhaoxin                          | 6         | 0.01%   |
| OCZ Technology Group             | 5         | 0.004%  |
| Jiangsu Huacun Elec.             | 3         | 0.003%  |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 10178     | 8%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8805      | 6.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8137      | 6.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6420      | 5.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6061      | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4439      | 3.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4074      | 3.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3887      | 3.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3012      | 2.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2864      | 2.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2689      | 2.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2666      | 2.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2498      | 1.96%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2317      | 1.82%   |
| Samsung NVMe SSD Controller 980                                                  | 2282      | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2096      | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1836      | 1.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1833      | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1519      | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1503      | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1496      | 1.18%   |
| Micron NVMe Storage Controller                                                   | 1458      | 1.15%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1269      | 1%      |
| Intel Comet Lake SATA AHCI Controller                                            | 1222      | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1220      | 0.96%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1169      | 0.92%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1151      | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1134      | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1109      | 0.87%   |
| Intel SSD 660P Series                                                            | 1106      | 0.87%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1085      | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 979       | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 978       | 0.77%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 955       | 0.75%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 922       | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 896       | 0.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 796       | 0.63%   |
| Nvidia MCP79 AHCI Controller                                                     | 788       | 0.62%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 760       | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 711       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 75456     | 61.68%  |
| NVMe | 28987     | 23.7%   |
| IDE  | 9324      | 7.62%   |
| RAID | 8562      | 7%      |
| SCSI | 1         | 0.001%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 85385     | 82.54%  |
| AMD          | 17952     | 17.35%  |
| ARM          | 46        | 0.04%   |
| CentaurHauls | 31        | 0.03%   |
| Unknown      | 14        | 0.01%   |
| Phytium      | 6         | 0.01%   |
| QUALCOMM     | 3         | 0.003%  |
| PowerBook5,6 | 2         | 0.002%  |
| PowerBook5,4 | 1         | 0.001%  |
| PowerBook3,4 | 1         | 0.001%  |
| GenuineTMx86 | 1         | 0.001%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 1661      | 1.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1444      | 1.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1388      | 1.34%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1186      | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1158      | 1.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1143      | 1.1%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1136      | 1.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1128      | 1.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1123      | 1.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1089      | 1.05%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1067      | 1.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1021      | 0.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1000      | 0.97%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 990       | 0.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 905       | 0.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 891       | 0.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 884       | 0.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 880       | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 806       | 0.78%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 768       | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 750       | 0.72%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 733       | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 731       | 0.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 714       | 0.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 695       | 0.67%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 682       | 0.66%   |
| AMD Custom APU 0405                           | 675       | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 659       | 0.64%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 657       | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 638       | 0.62%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 638       | 0.62%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 581       | 0.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 578       | 0.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 565       | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 557       | 0.54%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 551       | 0.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 550       | 0.53%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 543       | 0.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 539       | 0.52%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 532       | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 24628     | 23.79%  |
| Intel Core i7           | 21223     | 20.5%   |
| Intel Core i3           | 9516      | 9.19%   |
| Other                   | 6708      | 6.48%   |
| Intel Celeron           | 6483      | 6.26%   |
| Intel Core 2 Duo        | 5869      | 5.67%   |
| AMD Ryzen 5             | 3574      | 3.45%   |
| Intel Pentium           | 3445      | 3.33%   |
| Intel Atom              | 3020      | 2.92%   |
| AMD Ryzen 7             | 2938      | 2.84%   |
| AMD A6                  | 1245      | 1.2%    |
| Intel Pentium Dual-Core | 1217      | 1.18%   |
| AMD A8                  | 874       | 0.84%   |
| AMD A4                  | 837       | 0.81%   |
| AMD Ryzen 3             | 778       | 0.75%   |
| Intel Pentium Dual      | 727       | 0.7%    |
| AMD E                   | 722       | 0.7%    |
| Intel Core 2            | 709       | 0.68%   |
| AMD A10                 | 697       | 0.67%   |
| Intel Genuine           | 666       | 0.64%   |
| AMD E1                  | 622       | 0.6%    |
| AMD Ryzen 7 PRO         | 562       | 0.54%   |
| AMD Ryzen 9             | 505       | 0.49%   |
| AMD E2                  | 471       | 0.45%   |
| Intel Core i9           | 399       | 0.39%   |
| Intel Pentium Silver    | 396       | 0.38%   |
| AMD Turion 64 X2 Mobile | 344       | 0.33%   |
| Intel Celeron M         | 321       | 0.31%   |
| Intel Pentium M         | 311       | 0.3%    |
| Intel Celeron Dual-Core | 269       | 0.26%   |
| AMD Athlon II           | 220       | 0.21%   |
| AMD Athlon              | 220       | 0.21%   |
| AMD Ryzen 5 PRO         | 209       | 0.2%    |
| Intel Xeon              | 182       | 0.18%   |
| AMD Phenom II           | 180       | 0.17%   |
| AMD C-60                | 177       | 0.17%   |
| AMD A12                 | 151       | 0.15%   |
| AMD Athlon X2           | 145       | 0.14%   |
| Intel Core m3           | 140       | 0.14%   |
| AMD Athlon 64 X2        | 122       | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 57213     | 55.19%  |
| 4       | 30664     | 29.58%  |
| 6       | 5898      | 5.69%   |
| 8       | 4592      | 4.43%   |
| 1       | 3454      | 3.33%   |
| Unknown | 600       | 0.58%   |
| 14      | 494       | 0.48%   |
| 12      | 356       | 0.34%   |
| 10      | 287       | 0.28%   |
| 3       | 73        | 0.07%   |
| 16      | 28        | 0.03%   |
| 5       | 10        | 0.01%   |
| 192     | 2         | 0.002%  |
| 24      | 2         | 0.002%  |
| 7       | 1         | 0.001%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 103343    | 99.87%  |
| Unknown | 92        | 0.09%   |
| 2       | 31        | 0.03%   |
| 4       | 6         | 0.01%   |
| 3       | 1         | 0.001%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 72460     | 69.83%  |
| 1       | 30672     | 29.56%  |
| Unknown | 600       | 0.58%   |
| 4       | 15        | 0.01%   |
| 8       | 13        | 0.01%   |
| 12      | 2         | 0.002%  |
| 16      | 1         | 0.001%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99845     | 96.13%  |
| Unknown        | 2146      | 2.07%   |
| 32-bit         | 1773      | 1.71%   |
| 64-bit         | 104       | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21253     | 19.87%  |
| 0x206a7    | 7647      | 7.15%   |
| 0x306a9    | 7011      | 6.55%   |
| 0x1067a    | 3969      | 3.71%   |
| 0x40651    | 3603      | 3.37%   |
| 0x806ea    | 3398      | 3.18%   |
| 0x806ec    | 3317      | 3.1%    |
| 0x406e3    | 3052      | 2.85%   |
| 0x20655    | 2982      | 2.79%   |
| 0x306d4    | 2872      | 2.69%   |
| 0x806e9    | 2809      | 2.63%   |
| 0x906ea    | 2726      | 2.55%   |
| 0x806c1    | 2680      | 2.51%   |
| 0x306c3    | 2435      | 2.28%   |
| 0x6fd      | 1989      | 1.86%   |
| 0x30678    | 1725      | 1.61%   |
| 0x406c4    | 1240      | 1.16%   |
| 0xa0652    | 1234      | 1.15%   |
| 0x10676    | 1203      | 1.12%   |
| 0x906e9    | 1199      | 1.12%   |
| 0x08108109 | 1135      | 1.06%   |
| 0x20652    | 1104      | 1.03%   |
| 0x0a50000c | 1083      | 1.01%   |
| 0x706e5    | 1081      | 1.01%   |
| 0x08108102 | 1025      | 0.96%   |
| 0x506e3    | 978       | 0.91%   |
| 0x106ca    | 939       | 0.88%   |
| 0x806eb    | 900       | 0.84%   |
| 0x08600106 | 871       | 0.81%   |
| 0x706a1    | 802       | 0.75%   |
| 0x06006705 | 802       | 0.75%   |
| 0x05000119 | 769       | 0.72%   |
| 0x506c9    | 764       | 0.71%   |
| 0x406c3    | 727       | 0.68%   |
| 0x07030105 | 711       | 0.66%   |
| 0x08608103 | 657       | 0.61%   |
| 0x06001119 | 623       | 0.58%   |
| 0x906a3    | 622       | 0.58%   |
| 0x706a8    | 563       | 0.53%   |
| 0x806d1    | 551       | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 18404     | 17.77%  |
| SandyBridge      | 8872      | 8.57%   |
| IvyBridge        | 8293      | 8.01%   |
| Haswell          | 7506      | 7.25%   |
| Penryn           | 5843      | 5.64%   |
| Skylake          | 5076      | 4.9%    |
| Westmere         | 4719      | 4.56%   |
| Silvermont       | 4449      | 4.3%    |
| Core             | 3928      | 3.79%   |
| Broadwell        | 3533      | 3.41%   |
| TigerLake        | 3515      | 3.39%   |
| Unknown          | 2952      | 2.85%   |
| Zen+             | 2608      | 2.52%   |
| Zen 2            | 2384      | 2.3%    |
| Icelake          | 1880      | 1.82%   |
| Bonnell          | 1813      | 1.75%   |
| CometLake        | 1796      | 1.73%   |
| Excavator        | 1779      | 1.72%   |
| Zen 3            | 1658      | 1.6%    |
| Goldmont plus    | 1654      | 1.6%    |
| Bobcat           | 1391      | 1.34%   |
| Puma             | 1125      | 1.09%   |
| P6               | 1030      | 0.99%   |
| Goldmont         | 953       | 0.92%   |
| Alderlake Hybrid | 874       | 0.84%   |
| Piledriver       | 850       | 0.82%   |
| Zen              | 800       | 0.77%   |
| K8 Hammer        | 759       | 0.73%   |
| K10              | 746       | 0.72%   |
| Jaguar           | 650       | 0.63%   |
| K10 Llano        | 567       | 0.55%   |
| Nehalem          | 395       | 0.38%   |
| K8 & K10 hybrid  | 370       | 0.36%   |
| Steamroller      | 176       | 0.17%   |
| Tremont          | 136       | 0.13%   |
| NetBurst         | 65        | 0.06%   |
| K6               | 3         | 0.003%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 76386     | 58.36%  |
| Nvidia                           | 28853     | 22.05%  |
| AMD                              | 25190     | 19.25%  |
| Silicon Integrated Systems [SiS] | 303       | 0.23%   |
| VIA Technologies                 | 106       | 0.08%   |
| ATI Technologies                 | 11        | 0.01%   |
| Zhaoxin                          | 10        | 0.01%   |
| S3 Graphics                      | 7         | 0.01%   |
| Neomagic                         | 5         | 0.004%  |
| ASPEED Technology                | 3         | 0.002%  |
| Trident Microsystems             | 1         | 0.001%  |
| Silicon Motion                   | 1         | 0.001%  |
| Nanjing Ruixinview Technology    | 1         | 0.001%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8061      | 5.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7842      | 5.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4276      | 3.14%   |
| Intel UHD Graphics 620                                                                   | 3915      | 2.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3503      | 2.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3351      | 2.46%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3323      | 2.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3311      | 2.43%   |
| Intel HD Graphics 620                                                                    | 3288      | 2.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3103      | 2.28%   |
| Intel HD Graphics 5500                                                                   | 2858      | 2.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2849      | 2.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2757      | 2.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2680      | 1.97%   |
| AMD Renoir                                                                               | 2297      | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2287      | 1.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2161      | 1.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2144      | 1.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1716      | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1716      | 1.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1468      | 1.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1385      | 1.02%   |
| Intel HD Graphics 630                                                                    | 1342      | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1333      | 0.98%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1293      | 0.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1269      | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1260      | 0.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1238      | 0.91%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1172      | 0.86%   |
| Intel HD Graphics 530                                                                    | 1084      | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1048      | 0.77%   |
| AMD Lucienne                                                                             | 1022      | 0.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 966       | 0.71%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 960       | 0.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 907       | 0.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 883       | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 871       | 0.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 821       | 0.6%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 821       | 0.6%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 808       | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 50774     | 48.93%  |
| Intel + Nvidia                    | 20852     | 20.09%  |
| 1 x AMD                           | 16498     | 15.9%   |
| 1 x Nvidia                        | 6039      | 5.82%   |
| Intel + AMD                       | 4573      | 4.41%   |
| 2 x AMD                           | 2231      | 2.15%   |
| AMD + Nvidia                      | 1918      | 1.85%   |
| 1 x SiS                           | 303       | 0.29%   |
| 2 x Intel                         | 191       | 0.18%   |
| Other                             | 160       | 0.15%   |
| 1 x VIA                           | 106       | 0.1%    |
| 2 x Nvidia                        | 81        | 0.08%   |
| Intel + 2 x Nvidia                | 15        | 0.01%   |
| 1 x Zhaoxin                       | 10        | 0.01%   |
| 1 x S3 Graphics                   | 7         | 0.01%   |
| 1 x Neomagic                      | 5         | 0.005%  |
| Intel + AMD + 1 x Nvidia          | 5         | 0.005%  |
| 1 x Trident Microsystems          | 1         | 0.001%  |
| 1 x Silicon Motion                | 1         | 0.001%  |
| Nvidia + ASPEED                   | 1         | 0.001%  |
| 1 x Nanjing Ruixinview Technology | 1         | 0.001%  |
| Intel + ASPEED                    | 1         | 0.001%  |
| 1 x ASPEED                        | 1         | 0.001%  |
| AMD + 2 x Nvidia                  | 1         | 0.001%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 88786     | 84.54%  |
| Proprietary | 13125     | 12.5%   |
| Unknown     | 3107      | 2.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 61925     | 58.16%  |
| 1.01-2.0       | 15620     | 14.67%  |
| 0.01-0.5       | 15056     | 14.14%  |
| 0.51-1.0       | 5830      | 5.48%   |
| 3.01-4.0       | 5581      | 5.24%   |
| 5.01-6.0       | 1294      | 1.22%   |
| 7.01-8.0       | 763       | 0.72%   |
| 2.01-3.0       | 289       | 0.27%   |
| 8.01-16.0      | 114       | 0.11%   |
| 16.01-24.0     | 2         | 0.002%  |
| More than 64.0 | 1         | 0.001%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 21948     | 19.31%  |
| LG Display              | 17152     | 15.09%  |
| Chimei Innolux          | 14328     | 12.61%  |
| BOE                     | 13835     | 12.18%  |
| Samsung Electronics     | 12513     | 11.01%  |
| Chi Mei Optoelectronics | 3661      | 3.22%   |
| Apple                   | 2846      | 2.5%    |
| Sharp                   | 2733      | 2.41%   |
| Dell                    | 2639      | 2.32%   |
| Lenovo                  | 2327      | 2.05%   |
| Goldstar                | 2125      | 1.87%   |
| PANDA                   | 1577      | 1.39%   |
| LG Philips              | 1367      | 1.2%    |
| Hewlett-Packard         | 1213      | 1.07%   |
| InfoVision              | 1049      | 0.92%   |
| Acer                    | 952       | 0.84%   |
| Philips                 | 796       | 0.7%    |
| AOC                     | 790       | 0.7%    |
| BenQ                    | 782       | 0.69%   |
| CPT                     | 660       | 0.58%   |
| HannStar                | 641       | 0.56%   |
| Ancor Communications    | 575       | 0.51%   |
| Sony                    | 505       | 0.44%   |
| CSO                     | 446       | 0.39%   |
| Iiyama                  | 380       | 0.33%   |
| Valve                   | 346       | 0.3%    |
| ViewSonic               | 323       | 0.28%   |
| ASUSTek Computer        | 282       | 0.25%   |
| Toshiba                 | 269       | 0.24%   |
| InnoLux Display         | 239       | 0.21%   |
| Panasonic               | 218       | 0.19%   |
| LGD                     | 204       | 0.18%   |
| Quanta Display          | 175       | 0.15%   |
| Analogix                | 171       | 0.15%   |
| Eizo                    | 165       | 0.15%   |
| TMX                     | 147       | 0.13%   |
| Seiko/Epson             | 146       | 0.13%   |
| Unknown                 | 140       | 0.12%   |
| Vizio                   | 115       | 0.1%    |
| NEC Computers           | 110       | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 978       | 0.85%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 916       | 0.8%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 869       | 0.76%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 807       | 0.7%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 790       | 0.69%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 775       | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 706       | 0.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 652       | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 607       | 0.53%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 593       | 0.52%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 494       | 0.43%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 434       | 0.38%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 421       | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 399       | 0.35%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 374       | 0.33%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 351       | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 347       | 0.3%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 344       | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 335       | 0.29%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 331       | 0.29%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 329       | 0.29%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 321       | 0.28%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 320       | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 312       | 0.27%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 305       | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 303       | 0.26%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 302       | 0.26%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 301       | 0.26%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 300       | 0.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 298       | 0.26%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 294       | 0.26%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 291       | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 290       | 0.25%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 288       | 0.25%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 282       | 0.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 279       | 0.24%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 278       | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 272       | 0.24%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 269       | 0.23%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 268       | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 39804     | 36.78%  |
| 1366x768 (WXGA)    | 37389     | 34.55%  |
| 1600x900 (HD+)     | 6412      | 5.93%   |
| 1280x800 (WXGA)    | 5813      | 5.37%   |
| 3840x2160 (4K)     | 3385      | 3.13%   |
| 1440x900 (WXGA+)   | 2204      | 2.04%   |
| 2560x1440 (QHD)    | 2142      | 1.98%   |
| 1920x1200 (WUXGA)  | 1712      | 1.58%   |
| 1024x600           | 1257      | 1.16%   |
| 1680x1050 (WSXGA+) | 964       | 0.89%   |
| 2560x1600          | 856       | 0.79%   |
| 1280x1024 (SXGA)   | 730       | 0.67%   |
| 2880x1800          | 568       | 0.52%   |
| 800x1280           | 503       | 0.46%   |
| 2560x1080          | 455       | 0.42%   |
| 3840x2400          | 401       | 0.37%   |
| 3440x1440          | 392       | 0.36%   |
| 1360x768           | 375       | 0.35%   |
| 2160x1440          | 315       | 0.29%   |
| 3200x1800 (QHD+)   | 299       | 0.28%   |
| 1024x768 (XGA)     | 272       | 0.25%   |
| Unknown            | 210       | 0.19%   |
| 1920x540           | 168       | 0.16%   |
| 2256x1504          | 142       | 0.13%   |
| 3840x1080          | 109       | 0.1%    |
| 3000x2000          | 102       | 0.09%   |
| 1680x945           | 97        | 0.09%   |
| 2288x1287          | 82        | 0.08%   |
| 1400x1050          | 78        | 0.07%   |
| 3072x1920          | 77        | 0.07%   |
| 1280x720 (HD)      | 72        | 0.07%   |
| 1600x1200          | 69        | 0.06%   |
| 3200x2000          | 68        | 0.06%   |
| 3456x2160          | 67        | 0.06%   |
| 1920x1280          | 52        | 0.05%   |
| 2240x1400          | 49        | 0.05%   |
| 2520x1680          | 38        | 0.04%   |
| 3840x1600          | 36        | 0.03%   |
| 1280x768           | 34        | 0.03%   |
| 2304x1440          | 26        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 50137     | 44.14%  |
| 13      | 15186     | 13.37%  |
| 14      | 13182     | 11.61%  |
| 17      | 8669      | 7.63%   |
| 24      | 2980      | 2.62%   |
| 12      | 2796      | 2.46%   |
| 27      | 2763      | 2.43%   |
| 23      | 2479      | 2.18%   |
| 11      | 2364      | 2.08%   |
| 21      | 1914      | 1.69%   |
| Unknown | 1548      | 1.36%   |
| 10      | 1393      | 1.23%   |
| 18      | 1008      | 0.89%   |
| 16      | 966       | 0.85%   |
| 31      | 856       | 0.75%   |
| 34      | 761       | 0.67%   |
| 19      | 680       | 0.6%    |
| 22      | 455       | 0.4%    |
| 20      | 392       | 0.35%   |
| 7       | 346       | 0.3%    |
| 84      | 304       | 0.27%   |
| 40      | 278       | 0.24%   |
| 72      | 261       | 0.23%   |
| 32      | 220       | 0.19%   |
| 54      | 204       | 0.18%   |
| 25      | 163       | 0.14%   |
| 26      | 128       | 0.11%   |
| 8       | 111       | 0.1%    |
| 52      | 90        | 0.08%   |
| 48      | 88        | 0.08%   |
| 37      | 71        | 0.06%   |
| 28      | 71        | 0.06%   |
| 29      | 63        | 0.06%   |
| 49      | 58        | 0.05%   |
| 46      | 55        | 0.05%   |
| 65      | 51        | 0.04%   |
| 42      | 43        | 0.04%   |
| 35      | 41        | 0.04%   |
| 142     | 40        | 0.04%   |
| 47      | 40        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 70362     | 62.4%   |
| 201-300        | 13909     | 12.33%  |
| 351-400        | 10456     | 9.27%   |
| 501-600        | 7762      | 6.88%   |
| 401-500        | 4063      | 3.6%    |
| Unknown        | 1548      | 1.37%   |
| 601-700        | 1294      | 1.15%   |
| 701-800        | 1045      | 0.93%   |
| 1001-1500      | 679       | 0.6%    |
| 1501-2000      | 613       | 0.54%   |
| 801-900        | 436       | 0.39%   |
| 1-100          | 347       | 0.31%   |
| 101-200        | 122       | 0.11%   |
| 901-1000       | 89        | 0.08%   |
| More than 2000 | 42        | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 84690     | 82.86%  |
| 16/10   | 12630     | 12.36%  |
| Unknown | 1008      | 0.99%   |
| 3/2     | 960       | 0.94%   |
| 21/9    | 877       | 0.86%   |
| 5/4     | 664       | 0.65%   |
| 4/3     | 562       | 0.55%   |
| 0.67    | 344       | 0.34%   |
| 0.62    | 192       | 0.19%   |
| 32/9    | 101       | 0.1%    |
| 1.00    | 43        | 0.04%   |
| 6/5     | 38        | 0.04%   |
| 3.40    | 24        | 0.02%   |
| 3.73    | 14        | 0.01%   |
| 1.96    | 14        | 0.01%   |
| 2.65    | 12        | 0.01%   |
| 3.20    | 9         | 0.01%   |
| 0.56    | 8         | 0.01%   |
| 0.89    | 3         | 0.003%  |
| 3.33    | 2         | 0.002%  |
| 2.12    | 2         | 0.002%  |
| 2.00    | 2         | 0.002%  |
| 0.63    | 2         | 0.002%  |
| 3.88    | 1         | 0.001%  |
| 2.50    | 1         | 0.001%  |
| 2.21    | 1         | 0.001%  |
| 2.01    | 1         | 0.001%  |
| 1.03    | 1         | 0.001%  |
| 0.65    | 1         | 0.001%  |
| 0.00    | 1         | 0.001%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 50111     | 44.19%  |
| 81-90          | 22792     | 20.1%   |
| 121-130        | 7061      | 6.23%   |
| 201-250        | 6439      | 5.68%   |
| 71-80          | 5434      | 4.79%   |
| 301-350        | 2853      | 2.52%   |
| 61-70          | 2685      | 2.37%   |
| 51-60          | 2396      | 2.11%   |
| 351-500        | 1963      | 1.73%   |
| 151-200        | 1570      | 1.38%   |
| Unknown        | 1549      | 1.37%   |
| 41-50          | 1394      | 1.23%   |
| 131-140        | 1329      | 1.17%   |
| 141-150        | 1218      | 1.07%   |
| More than 1000 | 1162      | 1.02%   |
| 251-300        | 1069      | 0.94%   |
| 111-120        | 734       | 0.65%   |
| 501-1000       | 686       | 0.6%    |
| 91-100         | 483       | 0.43%   |
| 1-40           | 465       | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 40963     | 36.76%  |
| 121-160       | 39965     | 35.86%  |
| 51-100        | 18456     | 16.56%  |
| 161-240       | 6470      | 5.81%   |
| More than 240 | 2833      | 2.54%   |
| Unknown       | 1548      | 1.39%   |
| 1-50          | 1201      | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 87246     | 82.34%  |
| 2     | 14394     | 13.58%  |
| 0     | 2793      | 2.64%   |
| 3     | 1429      | 1.35%   |
| 4     | 90        | 0.08%   |
| 5     | 5         | 0.005%  |
| 6     | 2         | 0.002%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 55314     | 32.91%  |
| Intel                             | 48873     | 29.08%  |
| Qualcomm Atheros                  | 28486     | 16.95%  |
| Broadcom                          | 12639     | 7.52%   |
| Broadcom Limited                  | 3271      | 1.95%   |
| Marvell Technology Group          | 2523      | 1.5%    |
| Ralink                            | 1962      | 1.17%   |
| MediaTek                          | 1626      | 0.97%   |
| Nvidia                            | 1038      | 0.62%   |
| Ralink Technology                 | 901       | 0.54%   |
| TP-Link                           | 896       | 0.53%   |
| ASIX Electronics                  | 840       | 0.5%    |
| Samsung Electronics               | 745       | 0.44%   |
| Huawei Technologies               | 730       | 0.43%   |
| Dell                              | 670       | 0.4%    |
| JMicron Technology                | 625       | 0.37%   |
| Ericsson Business Mobile Networks | 550       | 0.33%   |
| Sierra Wireless                   | 527       | 0.31%   |
| Lenovo                            | 473       | 0.28%   |
| Xiaomi                            | 441       | 0.26%   |
| Hewlett-Packard                   | 417       | 0.25%   |
| DisplayLink                       | 396       | 0.24%   |
| Silicon Integrated Systems [SiS]  | 352       | 0.21%   |
| Qualcomm                          | 329       | 0.2%    |
| Attansic Technology               | 266       | 0.16%   |
| Qualcomm Atheros Communications   | 258       | 0.15%   |
| ASUSTek Computer                  | 193       | 0.11%   |
| NetGear                           | 190       | 0.11%   |
| D-Link                            | 183       | 0.11%   |
| Fibocom                           | 132       | 0.08%   |
| Motorola PCS                      | 131       | 0.08%   |
| Apple                             | 116       | 0.07%   |
| ZTE WCDMA Technologies MSM        | 107       | 0.06%   |
| Edimax Technology                 | 105       | 0.06%   |
| Google                            | 104       | 0.06%   |
| VIA Technologies                  | 95        | 0.06%   |
| OPPO Electronics                  | 87        | 0.05%   |
| ICS Advent                        | 84        | 0.05%   |
| Linksys                           | 82        | 0.05%   |
| D-Link System                     | 79        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 32435     | 16.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 12113     | 6.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4986      | 2.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4485      | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4271      | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4169      | 2.08%   |
| Intel Wi-Fi 6 AX200                                                     | 3957      | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3793      | 1.9%    |
| Intel Wireless 8265 / 8275                                              | 3635      | 1.82%   |
| Intel Wireless 7260                                                     | 3049      | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2979      | 1.49%   |
| Intel Wireless 7265                                                     | 2900      | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2819      | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2678      | 1.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2674      | 1.34%   |
| Intel Wi-Fi 6 AX201                                                     | 2589      | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2525      | 1.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2285      | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2123      | 1.06%   |
| Intel Wireless 8260                                                     | 2121      | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1990      | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1747      | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1740      | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1631      | 0.82%   |
| Intel Wireless 3165                                                     | 1630      | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1526      | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1505      | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1380      | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1282      | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1226      | 0.61%   |
| Intel 82577LM Gigabit Network Connection                                | 1199      | 0.6%    |
| Intel Wireless 3160                                                     | 1189      | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1103      | 0.55%   |
| Intel WiFi Link 5100                                                    | 1066      | 0.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1044      | 0.52%   |
| Intel Ethernet Connection I218-LM                                       | 1038      | 0.52%   |
| Intel Centrino Ultimate-N 6300                                          | 1038      | 0.52%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1013      | 0.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 970       | 0.48%   |
| Intel Ethernet Connection I219-LM                                       | 959       | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 46630     | 43.74%  |
| Qualcomm Atheros                      | 24554     | 23.03%  |
| Realtek Semiconductor                 | 16098     | 15.1%   |
| Broadcom                              | 9573      | 8.98%   |
| Broadcom Limited                      | 2100      | 1.97%   |
| Ralink                                | 1962      | 1.84%   |
| MediaTek                              | 1474      | 1.38%   |
| Ralink Technology                     | 901       | 0.85%   |
| TP-Link                               | 696       | 0.65%   |
| Sierra Wireless                       | 404       | 0.38%   |
| Dell                                  | 398       | 0.37%   |
| Qualcomm Atheros Communications       | 258       | 0.24%   |
| Qualcomm                              | 206       | 0.19%   |
| NetGear                               | 177       | 0.17%   |
| ASUSTek Computer                      | 176       | 0.17%   |
| D-Link                                | 150       | 0.14%   |
| FIBOCOM                               | 132       | 0.12%   |
| Edimax Technology                     | 105       | 0.1%    |
| Hewlett-Packard                       | 100       | 0.09%   |
| D-Link System                         | 79        | 0.07%   |
| Linksys                               | 68        | 0.06%   |
| Belkin Components                     | 55        | 0.05%   |
| Microsoft                             | 34        | 0.03%   |
| Micro Star International              | 20        | 0.02%   |
| AVM                                   | 20        | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 17        | 0.02%   |
| ZyDAS                                 | 16        | 0.02%   |
| Sitecom Europe                        | 16        | 0.02%   |
| ZyXEL Communications                  | 12        | 0.01%   |
| Quectel Wireless Solutions            | 12        | 0.01%   |
| BUFFALO                               | 12        | 0.01%   |
| Fujitsu Siemens Computers             | 10        | 0.01%   |
| Qcom                                  | 9         | 0.01%   |
| Xiaomi                                | 8         | 0.01%   |
| Marvell Technology Group              | 8         | 0.01%   |
| Mercucys                              | 7         | 0.01%   |
| Wacom                                 | 6         | 0.01%   |
| TRENDnet                              | 6         | 0.01%   |
| Tenda                                 | 5         | 0.005%  |
| Samsung Electronics                   | 5         | 0.005%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4986      | 4.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4485      | 4.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4271      | 3.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4169      | 3.89%   |
| Intel Wi-Fi 6 AX200                                                     | 3957      | 3.69%   |
| Intel Wireless 8265 / 8275                                              | 3635      | 3.39%   |
| Intel Wireless 7260                                                     | 3049      | 2.84%   |
| Intel Wireless 7265                                                     | 2900      | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2819      | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2678      | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2674      | 2.49%   |
| Intel Wi-Fi 6 AX201                                                     | 2589      | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2525      | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2285      | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2123      | 1.98%   |
| Intel Wireless 8260                                                     | 2121      | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1990      | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1747      | 1.63%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1740      | 1.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1631      | 1.52%   |
| Intel Wireless 3165                                                     | 1630      | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1526      | 1.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1505      | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 1380      | 1.29%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1226      | 1.14%   |
| Intel Wireless 3160                                                     | 1189      | 1.11%   |
| Intel WiFi Link 5100                                                    | 1066      | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1044      | 0.97%   |
| Intel Centrino Ultimate-N 6300                                          | 1038      | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1013      | 0.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 970       | 0.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 953       | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 950       | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 946       | 0.88%   |
| Intel Centrino Advanced-N 6200                                          | 912       | 0.85%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 856       | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 836       | 0.78%   |
| Intel Centrino Advanced-N 6235                                          | 826       | 0.77%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 824       | 0.77%   |
| Intel Centrino Wireless-N 2230                                          | 810       | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 48974     | 54.73%  |
| Intel                                  | 17389     | 19.43%  |
| Qualcomm Atheros                       | 7478      | 8.36%   |
| Broadcom                               | 4708      | 5.26%   |
| Marvell Technology Group               | 2515      | 2.81%   |
| Broadcom Limited                       | 1245      | 1.39%   |
| Nvidia                                 | 1031      | 1.15%   |
| ASIX Electronics                       | 840       | 0.94%   |
| JMicron Technology                     | 625       | 0.7%    |
| Samsung Electronics                    | 532       | 0.59%   |
| Lenovo                                 | 466       | 0.52%   |
| Xiaomi                                 | 432       | 0.48%   |
| DisplayLink                            | 396       | 0.44%   |
| Huawei Technologies                    | 344       | 0.38%   |
| Silicon Integrated Systems [SiS]       | 342       | 0.38%   |
| Attansic Technology                    | 266       | 0.3%    |
| TP-Link                                | 202       | 0.23%   |
| MediaTek                               | 142       | 0.16%   |
| Sierra Wireless                        | 123       | 0.14%   |
| Qualcomm                               | 121       | 0.14%   |
| Apple                                  | 113       | 0.13%   |
| Google                                 | 100       | 0.11%   |
| Hewlett-Packard                        | 97        | 0.11%   |
| ZTE WCDMA Technologies MSM             | 95        | 0.11%   |
| Motorola PCS                           | 95        | 0.11%   |
| VIA Technologies                       | 94        | 0.11%   |
| OPPO Electronics                       | 87        | 0.1%    |
| ICS Advent                             | 84        | 0.09%   |
| OnePlus Technology (Shenzhen)          | 56        | 0.06%   |
| HTC (High Tech Computer)               | 34        | 0.04%   |
| D-Link                                 | 33        | 0.04%   |
| Gemtek                                 | 32        | 0.04%   |
| LG Electronics                         | 30        | 0.03%   |
| T & A Mobile Phones                    | 28        | 0.03%   |
| HMD Global                             | 25        | 0.03%   |
| Spreadtrum Communications              | 24        | 0.03%   |
| Cypress Semiconductor                  | 24        | 0.03%   |
| Microchip Technology                   | 20        | 0.02%   |
| ASUSTek Computer                       | 17        | 0.02%   |
| Sony Ericsson Mobile Communications AB | 16        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32435     | 35.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12113     | 13.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3793      | 4.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2979      | 3.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1282      | 1.42%   |
| Intel 82577LM Gigabit Network Connection                          | 1199      | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1103      | 1.22%   |
| Intel Ethernet Connection I218-LM                                 | 1038      | 1.15%   |
| Intel Ethernet Connection I219-LM                                 | 959       | 1.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 950       | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 872       | 0.97%   |
| Intel 82567LM Gigabit Network Connection                          | 855       | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                             | 853       | 0.95%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 769       | 0.85%   |
| Intel Ethernet Connection (4) I219-V                              | 704       | 0.78%   |
| Nvidia MCP79 Ethernet                                             | 694       | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 693       | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 691       | 0.77%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 644       | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 626       | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 625       | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 590       | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 582       | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 575       | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 565       | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 531       | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 513       | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 512       | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 507       | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 504       | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 435       | 0.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 409       | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 408       | 0.45%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 401       | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 383       | 0.42%   |
| Intel 82579V Gigabit Network Connection                           | 373       | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 371       | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 356       | 0.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 355       | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 349       | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 101630    | 53.49%  |
| Ethernet | 85843     | 45.18%  |
| Modem    | 2336      | 1.23%   |
| Unknown  | 182       | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 84642     | 77.67%  |
| Ethernet | 24285     | 22.29%  |
| Modem    | 25        | 0.02%   |
| Unknown  | 20        | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 79438     | 76.66%  |
| 1     | 21864     | 21.1%   |
| 0     | 1702      | 1.64%   |
| 3     | 600       | 0.58%   |
| 4     | 12        | 0.01%   |
| 7     | 2         | 0.002%  |
| 5     | 2         | 0.002%  |
| 10    | 1         | 0.001%  |
| 8     | 1         | 0.001%  |
| 6     | 1         | 0.001%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 85656     | 80.85%  |
| Yes     | 16401     | 15.48%  |
| Unknown | 3889      | 3.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33895     | 43.17%  |
| Qualcomm Atheros Communications | 8480      | 10.8%   |
| Realtek Semiconductor           | 7842      | 9.99%   |
| Broadcom                        | 5034      | 6.41%   |
| IMC Networks                    | 4646      | 5.92%   |
| Lite-On Technology              | 4050      | 5.16%   |
| Foxconn / Hon Hai               | 3071      | 3.91%   |
| Apple                           | 2598      | 3.31%   |
| Dell                            | 1602      | 2.04%   |
| Hewlett-Packard                 | 1299      | 1.65%   |
| Cambridge Silicon Radio         | 1081      | 1.38%   |
| Toshiba                         | 976       | 1.24%   |
| Ralink                          | 970       | 1.24%   |
| ASUSTek Computer                | 633       | 0.81%   |
| Realtek                         | 565       | 0.72%   |
| Foxconn International           | 451       | 0.57%   |
| Alps Electric                   | 324       | 0.41%   |
| Ralink Technology               | 237       | 0.3%    |
| MediaTek                        | 114       | 0.15%   |
| Askey Computer                  | 101       | 0.13%   |
| Chicony Electronics             | 90        | 0.11%   |
| Taiyo Yuden                     | 71        | 0.09%   |
| USI                             | 56        | 0.07%   |
| Qcom                            | 48        | 0.06%   |
| Opticis                         | 47        | 0.06%   |
| Smart Modular Technologies      | 39        | 0.05%   |
| Micro Star International        | 38        | 0.05%   |
| Fujitsu                         | 21        | 0.03%   |
| Edimax Technology               | 20        | 0.03%   |
| TP-Link                         | 18        | 0.02%   |
| Integrated System Solution      | 18        | 0.02%   |
| Dynex                           | 14        | 0.02%   |
| Belkin Components               | 13        | 0.02%   |
| Syntek                          | 9         | 0.01%   |
| SINO WEALTH                     | 6         | 0.01%   |
| Sitecom Europe                  | 4         | 0.01%   |
| Logitech                        | 4         | 0.01%   |
| Unknown                         | 4         | 0.01%   |
| Samsung Electronics             | 3         | 0.004%  |
| Primax Electronics              | 3         | 0.004%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14109     | 17.95%  |
| Intel AX201 Bluetooth                               | 5626      | 7.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5181      | 6.59%   |
| Qualcomm Atheros  Bluetooth Device                  | 4579      | 5.83%   |
| Realtek Bluetooth Radio                             | 4532      | 5.77%   |
| Intel AX200 Bluetooth                               | 3836      | 4.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2086      | 2.65%   |
| IMC Networks Bluetooth Radio                        | 1942      | 2.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1537      | 1.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1415      | 1.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1411      | 1.8%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1387      | 1.77%   |
| Apple Bluetooth Host Controller                     | 1134      | 1.44%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1104      | 1.4%    |
| IMC Networks Bluetooth Device                       | 1085      | 1.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1081      | 1.38%   |
| Lite-On Bluetooth Device                            | 973       | 1.24%   |
| Ralink RT3290 Bluetooth                             | 970       | 1.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 827       | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                    | 804       | 1.02%   |
| Broadcom BCM2045B (BDC-2.1)                         | 803       | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                    | 796       | 1.01%   |
| Apple Bluetooth USB Host Controller                 | 718       | 0.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 715       | 0.91%   |
| Intel Bluetooth Device                              | 689       | 0.88%   |
| HP Broadcom 2070 Bluetooth Combo                    | 680       | 0.87%   |
| Intel AX210 Bluetooth                               | 610       | 0.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 592       | 0.75%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 562       | 0.72%   |
| IMC Networks Wireless_Device                        | 558       | 0.71%   |
| Dell DW375 Bluetooth Module                         | 542       | 0.69%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 508       | 0.65%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 495       | 0.63%   |
| Realtek 802.11ac WLAN Adapter                       | 485       | 0.62%   |
| Realtek RTL8723B Bluetooth                          | 478       | 0.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 475       | 0.6%    |
| Foxconn International BCM43142A0 Bluetooth module   | 449       | 0.57%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 437       | 0.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 397       | 0.51%   |
| Broadcom HP Portable SoftSailing                    | 360       | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 82478     | 66.89%  |
| AMD                              | 20525     | 16.65%  |
| Nvidia                           | 13632     | 11.06%  |
| C-Media Electronics              | 758       | 0.61%   |
| Realtek Semiconductor            | 534       | 0.43%   |
| Logitech                         | 507       | 0.41%   |
| Lenovo                           | 459       | 0.37%   |
| Silicon Integrated Systems [SiS] | 425       | 0.34%   |
| GN Netcom                        | 387       | 0.31%   |
| Plantronics                      | 265       | 0.21%   |
| JMTek                            | 222       | 0.18%   |
| Texas Instruments                | 197       | 0.16%   |
| Generalplus Technology           | 191       | 0.15%   |
| Hewlett-Packard                  | 158       | 0.13%   |
| Apple                            | 157       | 0.13%   |
| Kingston Technology              | 147       | 0.12%   |
| Creative Technology              | 140       | 0.11%   |
| VIA Technologies                 | 120       | 0.1%    |
| Razer USA                        | 89        | 0.07%   |
| Focusrite-Novation               | 89        | 0.07%   |
| SteelSeries ApS                  | 88        | 0.07%   |
| Corsair                          | 84        | 0.07%   |
| Sony                             | 66        | 0.05%   |
| ASUSTek Computer                 | 63        | 0.05%   |
| Sennheiser Communications        | 60        | 0.05%   |
| Conexant Systems                 | 51        | 0.04%   |
| Dell                             | 47        | 0.04%   |
| Samson Technologies              | 42        | 0.03%   |
| Blue Microphones                 | 41        | 0.03%   |
| No brand                         | 38        | 0.03%   |
| Microsoft                        | 38        | 0.03%   |
| GYROCOM C&C                      | 37        | 0.03%   |
| BEHRINGER International          | 37        | 0.03%   |
| RODE Microphones                 | 36        | 0.03%   |
| M-Audio                          | 36        | 0.03%   |
| Tenx Technology                  | 31        | 0.03%   |
| Samsung Electronics              | 31        | 0.03%   |
| DSEA A/S                         | 31        | 0.03%   |
| Yamaha                           | 25        | 0.02%   |
| XMOS                             | 25        | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11374     | 7.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10015     | 6.72%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8537      | 5.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7129      | 4.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5107      | 3.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4809      | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 4331      | 2.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4311      | 2.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4131      | 2.77%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3931      | 2.64%   |
| AMD FCH Azalia Controller                                                                         | 3875      | 2.6%    |
| Intel Broadwell-U Audio Controller                                                                | 3530      | 2.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3512      | 2.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3478      | 2.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3181      | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3151      | 2.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3032      | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3021      | 2.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2723      | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2686      | 1.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2411      | 1.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2356      | 1.58%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2324      | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1786      | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1748      | 1.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1695      | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1651      | 1.11%   |
| Intel Comet Lake PCH cAVS                                                                         | 1621      | 1.09%   |
| Intel CM238 HD Audio Controller                                                                   | 1547      | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1541      | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1416      | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1298      | 0.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1266      | 0.85%   |
| AMD High Definition Audio Controller                                                              | 1238      | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1170      | 0.79%   |
| AMD Wrestler HDMI Audio                                                                           | 1123      | 0.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1119      | 0.75%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 958       | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 952       | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 940       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19436     | 27.42%  |
| SK hynix            | 15779     | 22.26%  |
| Micron Technology   | 7743      | 10.92%  |
| Kingston            | 6293      | 8.88%   |
| Unknown             | 5926      | 8.36%   |
| Crucial             | 2717      | 3.83%   |
| Elpida              | 1957      | 2.76%   |
| Ramaxel Technology  | 1793      | 2.53%   |
| A-DATA Technology   | 1607      | 2.27%   |
| Nanya Technology    | 1310      | 1.85%   |
| Corsair             | 762       | 1.07%   |
| Unknown (ABCD)      | 578       | 0.82%   |
| Smart               | 548       | 0.77%   |
| G.Skill             | 327       | 0.46%   |
| ASint Technology    | 280       | 0.39%   |
| Transcend           | 273       | 0.39%   |
| Unknown             | 241       | 0.34%   |
| Patriot             | 225       | 0.32%   |
| Team                | 208       | 0.29%   |
| GOODRAM             | 203       | 0.29%   |
| Goldkey             | 185       | 0.26%   |
| 48spaces            | 169       | 0.24%   |
| Teikon              | 157       | 0.22%   |
| AMD                 | 153       | 0.22%   |
| Apacer              | 146       | 0.21%   |
| Qimonda             | 123       | 0.17%   |
| SHARETRONIC         | 120       | 0.17%   |
| Smart Brazil        | 110       | 0.16%   |
| Toshiba             | 73        | 0.1%    |
| Avant               | 73        | 0.1%    |
| Silicon Power       | 64        | 0.09%   |
| High Bridge         | 63        | 0.09%   |
| PNY                 | 62        | 0.09%   |
| Neo Forza           | 50        | 0.07%   |
| Kllisre             | 48        | 0.07%   |
| CSX                 | 48        | 0.07%   |
| Foxline             | 46        | 0.06%   |
| Kingmax             | 42        | 0.06%   |
| Unifosa             | 41        | 0.06%   |
| Timetec             | 38        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 915       | 1.21%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 845       | 1.11%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 838       | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 822       | 1.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 778       | 1.03%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 758       | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 716       | 0.94%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 636       | 0.84%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 628       | 0.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 606       | 0.8%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 580       | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 524       | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 512       | 0.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 504       | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 482       | 0.64%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 469       | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 458       | 0.6%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 446       | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 440       | 0.58%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 439       | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 435       | 0.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 423       | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 398       | 0.52%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 396       | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 389       | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 385       | 0.51%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 372       | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 370       | 0.49%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 364       | 0.48%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 361       | 0.48%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 348       | 0.46%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 325       | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 304       | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 301       | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 293       | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 292       | 0.38%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 291       | 0.38%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 288       | 0.38%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 286       | 0.38%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 283       | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 24568     | 41.12%  |
| DDR4    | 22811     | 38.18%  |
| DDR2    | 4489      | 7.51%   |
| LPDDR4  | 2344      | 3.92%   |
| SDRAM   | 1861      | 3.11%   |
| LPDDR3  | 1660      | 2.78%   |
| DDR     | 496       | 0.83%   |
| Unknown | 478       | 0.8%    |
| DDR5    | 415       | 0.69%   |
| LPDDR5  | 312       | 0.52%   |
| DRAM    | 308       | 0.52%   |
| RAM     | 4         | 0.01%   |
| SRAM    | 1         | 0.002%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 54124     | 91.22%  |
| Row Of Chips    | 4208      | 7.09%   |
| Chip            | 387       | 0.65%   |
| DIMM            | 327       | 0.55%   |
| Unknown         | 287       | 0.48%   |
| Proprietary Car | 2         | 0.003%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 22372     | 33.8%   |
| 8192    | 20149     | 30.44%  |
| 2048    | 11699     | 17.67%  |
| 16384   | 6604      | 9.98%   |
| 1024    | 3693      | 5.58%   |
| 32768   | 1112      | 1.68%   |
| 512     | 450       | 0.68%   |
| 256     | 70        | 0.11%   |
| Unknown | 16        | 0.02%   |
| 1536    | 7         | 0.01%   |
| 128     | 6         | 0.01%   |
| 64      | 4         | 0.01%   |
| 3072    | 3         | 0.005%  |
| 6144    | 2         | 0.003%  |
| 131072  | 1         | 0.002%  |
| 65536   | 1         | 0.002%  |
| 384     | 1         | 0.002%  |
| 232     | 1         | 0.002%  |
| 8       | 1         | 0.002%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 16283     | 24.97%  |
| 2667    | 11104     | 17.03%  |
| 3200    | 8384      | 12.86%  |
| 1334    | 4779      | 7.33%   |
| 2400    | 4280      | 6.56%   |
| 1333    | 3224      | 4.94%   |
| 2133    | 2685      | 4.12%   |
| 667     | 2432      | 3.73%   |
| Unknown | 2078      | 3.19%   |
| 1067    | 1308      | 2.01%   |
| 800     | 1308      | 2.01%   |
| 4199    | 997       | 1.53%   |
| 3266    | 839       | 1.29%   |
| 4267    | 816       | 1.25%   |
| 1867    | 718       | 1.1%    |
| 2048    | 508       | 0.78%   |
| 1066    | 495       | 0.76%   |
| 533     | 495       | 0.76%   |
| 4800    | 445       | 0.68%   |
| 975     | 392       | 0.6%    |
| 6400    | 303       | 0.46%   |
| 8400    | 292       | 0.45%   |
| 4266    | 237       | 0.36%   |
| 333     | 147       | 0.23%   |
| 3733    | 133       | 0.2%    |
| 400     | 84        | 0.13%   |
| 1639    | 79        | 0.12%   |
| 1866    | 76        | 0.12%   |
| 2933    | 66        | 0.1%    |
| 266     | 27        | 0.04%   |
| 3000    | 22        | 0.03%   |
| 1776    | 21        | 0.03%   |
| 1200    | 15        | 0.02%   |
| 2666    | 13        | 0.02%   |
| 933     | 13        | 0.02%   |
| 2267    | 11        | 0.02%   |
| 666     | 9         | 0.01%   |
| 200     | 9         | 0.01%   |
| 1777    | 8         | 0.01%   |
| 2800    | 6         | 0.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 409       | 32.96%  |
| Canon                           | 241       | 19.42%  |
| Samsung Electronics             | 157       | 12.65%  |
| Brother Industries              | 147       | 11.85%  |
| Seiko Epson                     | 126       | 10.15%  |
| Xerox                           | 30        | 2.42%   |
| Prolific Technology             | 19        | 1.53%   |
| Panasonic (Matsushita)          | 16        | 1.29%   |
| Pantum                          | 13        | 1.05%   |
| Lexmark International           | 13        | 1.05%   |
| Kyocera                         | 12        | 0.97%   |
| Ricoh                           | 11        | 0.89%   |
| STMicroelectronics              | 8         | 0.64%   |
| QinHeng Electronics             | 7         | 0.56%   |
| Xiaomi                          | 4         | 0.32%   |
| MIIIW                           | 4         | 0.32%   |
| Zebra                           | 3         | 0.24%   |
| Oki Data                        | 3         | 0.24%   |
| Dymo-CoStar                     | 3         | 0.24%   |
| Dell                            | 3         | 0.24%   |
| TSC Auto ID Technology          | 2         | 0.16%   |
| Konica Minolta                  | 2         | 0.16%   |
| BIXOLON                         | 2         | 0.16%   |
| Sagem                           | 1         | 0.08%   |
| NXP Semiconductors              | 1         | 0.08%   |
| ICS Advent                      | 1         | 0.08%   |
| cab Produkttechnik GmbH & Co KG | 1         | 0.08%   |
| Apple                           | 1         | 0.08%   |
| Unknown                         | 1         | 0.08%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                          | 27        | 2.14%   |
| Samsung M2020 Series                                      | 23        | 1.82%   |
| HP LaserJet 1018                                          | 21        | 1.67%   |
| Canon PIXMA MG2500 Series                                 | 21        | 1.67%   |
| Prolific PL2305 Parallel Port                             | 19        | 1.51%   |
| HP LaserJet P1102                                         | 17        | 1.35%   |
| HP DeskJet 2700 series                                    | 16        | 1.27%   |
| Samsung M2070 Series                                      | 14        | 1.11%   |
| HP DeskJet 2130 series                                    | 14        | 1.11%   |
| Samsung SCX-4200 series                                   | 12        | 0.95%   |
| HP DeskJet 2620 All-in-One Printer                        | 12        | 0.95%   |
| Seiko Epson L3150 Series                                  | 11        | 0.87%   |
| HP LaserJet 3050                                          | 11        | 0.87%   |
| Samsung SCX-3400 Series                                   | 10        | 0.79%   |
| Samsung SCX-3200 Series                                   | 10        | 0.79%   |
| HP ENVY 4520 series                                       | 10        | 0.79%   |
| HP DeskJet 2300 series                                    | 10        | 0.79%   |
| Brother HL-1110 series                                    | 10        | 0.79%   |
| Panasonic (Matsushita) KX-MB1500RU                        | 9         | 0.71%   |
| HP OfficeJet 3830 series                                  | 9         | 0.71%   |
| HP LaserJet Professional P1102w                           | 9         | 0.71%   |
| HP Deskjet 2050 J510                                      | 9         | 0.71%   |
| Canon LBP2900                                             | 9         | 0.71%   |
| Seiko Epson L222 Series                                   | 8         | 0.63%   |
| HP Deskjet 2540 series                                    | 8         | 0.63%   |
| Canon PIXMA MG3600 Series                                 | 8         | 0.63%   |
| Canon LBP6020                                             | 8         | 0.63%   |
| Seiko Epson Printer                                       | 7         | 0.56%   |
| Seiko Epson L210 Series                                   | 7         | 0.56%   |
| QinHeng CH340S                                            | 7         | 0.56%   |
| HP LaserJet 1200                                          | 7         | 0.56%   |
| HP DeskJet 3630 series                                    | 7         | 0.56%   |
| HP Deskjet 1050 J410                                      | 7         | 0.56%   |
| Canon PIXMA MX920 Series                                  | 7         | 0.56%   |
| Brother HL-2030 Laser Printer                             | 7         | 0.56%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 6         | 0.48%   |
| Seiko Epson L355 Series                                   | 6         | 0.48%   |
| Seiko Epson L3110 Series                                  | 6         | 0.48%   |
| Samsung ML-1640 Series Laser Printer                      | 6         | 0.48%   |
| Samsung Composite Device                                  | 6         | 0.48%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 116       | 49.79%  |
| Seiko Epson                                    | 53        | 22.75%  |
| Hewlett-Packard                                | 27        | 11.59%  |
| Mustek Systems                                 | 15        | 6.44%   |
| Ultima Electronics                             | 4         | 1.72%   |
| Acer Peripherals (now BenQ)                    | 4         | 1.72%   |
| Plustek                                        | 3         | 1.29%   |
| Siemens Information and Communication Products | 2         | 0.86%   |
| Microtek International                         | 2         | 0.86%   |
| KYE Systems (Mouse Systems)                    | 2         | 0.86%   |
| Visioneer                                      | 1         | 0.43%   |
| Papillon Systems                               | 1         | 0.43%   |
| Fujitsu                                        | 1         | 0.43%   |
| Canon Electronics                              | 1         | 0.43%   |
| AGFA-Gevaert NV                                | 1         | 0.43%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 22        | 9.4%    |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 16        | 6.84%   |
| Canon CanoScan LiDE 220                                                               | 13        | 5.56%   |
| Canon CanoScan LIDE 25                                                                | 10        | 4.27%   |
| Canon CanoScan LiDE 120                                                               | 8         | 3.42%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 7         | 2.99%   |
| Canon CanoScan LiDE 210                                                               | 7         | 2.99%   |
| HP ScanJet 2400c                                                                      | 6         | 2.56%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 5         | 2.14%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 5         | 2.14%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 5         | 2.14%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 5         | 2.14%   |
| Canon CanoScan LiDE 100                                                               | 5         | 2.14%   |
| Mustek Systems SNAPSCAN e22                                                           | 4         | 1.71%   |
| HP Scanjet 200                                                                        | 4         | 1.71%   |
| Canon CanoScan 4400F                                                                  | 4         | 1.71%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 3         | 1.28%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]                                      | 3         | 1.28%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 3         | 1.28%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 3         | 1.28%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 3         | 1.28%   |
| Canon CanoScan N650U/N656U                                                            | 3         | 1.28%   |
| Canon CanoScan LiDE 600F                                                              | 3         | 1.28%   |
| Canon CanoScan LiDE 500F                                                              | 3         | 1.28%   |
| Canon CanoScan LiDE 200                                                               | 3         | 1.28%   |
| Canon CanoScan 4200F                                                                  | 3         | 1.28%   |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader       | 2         | 0.85%   |
| Seiko Epson Scanner                                                                   | 2         | 0.85%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2         | 0.85%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 2         | 0.85%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 2         | 0.85%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 2         | 0.85%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 2         | 0.85%   |
| Plustek OpticSlim 1200 Scanner                                                        | 2         | 0.85%   |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 0.85%   |
| HP ScanJet 5590                                                                       | 2         | 0.85%   |
| HP ScanJet 3770                                                                       | 2         | 0.85%   |
| HP ScanJet 3570c                                                                      | 2         | 0.85%   |
| Canon CanoScan LiDE 70                                                                | 2         | 0.85%   |
| Canon CanoScan LiDE 60                                                                | 2         | 0.85%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 22643     | 25.04%  |
| IMC Networks                           | 9404      | 10.4%   |
| Microdia                               | 7743      | 8.56%   |
| Realtek Semiconductor                  | 7417      | 8.2%    |
| Sunplus Innovation Technology          | 5183      | 5.73%   |
| Quanta                                 | 4461      | 4.93%   |
| Acer                                   | 4167      | 4.61%   |
| Suyin                                  | 4005      | 4.43%   |
| Cheng Uei Precision Industry (Foxlink) | 3632      | 4.02%   |
| Bison Electronics                      | 3403      | 3.76%   |
| Syntek                                 | 2271      | 2.51%   |
| Silicon Motion                         | 1987      | 2.2%    |
| Lite-On Technology                     | 1917      | 2.12%   |
| Apple                                  | 1893      | 2.09%   |
| Alcor Micro                            | 1395      | 1.54%   |
| Luxvisions Innotech Limited            | 1034      | 1.14%   |
| Ricoh                                  | 1026      | 1.13%   |
| Logitech                               | 1011      | 1.12%   |
| Lenovo                                 | 599       | 0.66%   |
| Samsung Electronics                    | 562       | 0.62%   |
| Z-Star Microelectronics                | 496       | 0.55%   |
| ALi                                    | 477       | 0.53%   |
| Importek                               | 414       | 0.46%   |
| Primax Electronics                     | 376       | 0.42%   |
| Sonix Technology                       | 294       | 0.33%   |
| DigiTech                               | 261       | 0.29%   |
| OmniVision Technologies                | 193       | 0.21%   |
| SunplusIT                              | 139       | 0.15%   |
| icSpring                               | 139       | 0.15%   |
| Microsoft                              | 128       | 0.14%   |
| Sunplus Technology                     | 105       | 0.12%   |
| Intel                                  | 100       | 0.11%   |
| GEMBIRD                                | 89        | 0.1%    |
| Generalplus Technology                 | 87        | 0.1%    |
| Genesys Logic                          | 80        | 0.09%   |
| Y Media                                | 73        | 0.08%   |
| LG Electronics                         | 61        | 0.07%   |
| Pixart Imaging                         | 48        | 0.05%   |
| ARC International                      | 42        | 0.05%   |
| Shenzhen Kingcome Optoelectronic       | 41        | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 3794      | 4.18%   |
| Microdia Integrated_Webcam_HD           | 3222      | 3.55%   |
| Chicony HD WebCam                       | 2402      | 2.65%   |
| Realtek Integrated_Webcam_HD            | 2279      | 2.51%   |
| IMC Networks Integrated Camera          | 2078      | 2.29%   |
| IMC Networks USB2.0 HD UVC WebCam       | 2067      | 2.28%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 1521      | 1.68%   |
| Sunplus Integrated_Webcam_HD            | 1478      | 1.63%   |
| Syntek Integrated Camera                | 983       | 1.08%   |
| Acer Integrated Camera                  | 923       | 1.02%   |
| Sunplus HD WebCam                       | 863       | 0.95%   |
| Quanta HD User Facing                   | 824       | 0.91%   |
| Microdia Integrated Webcam              | 801       | 0.88%   |
| Chicony Lenovo EasyCamera               | 788       | 0.87%   |
| Chicony USB 2.0 Camera                  | 747       | 0.82%   |
| Chicony USB2.0 HD UVC WebCam            | 745       | 0.82%   |
| Chicony HP Truevision HD                | 745       | 0.82%   |
| Chicony HP HD Camera                    | 744       | 0.82%   |
| Lite-On Integrated Camera               | 693       | 0.76%   |
| Chicony USB2.0 VGA UVC WebCam           | 686       | 0.76%   |
| Acer Lenovo EasyCamera                  | 683       | 0.75%   |
| Realtek USB Camera                      | 673       | 0.74%   |
| Bison Integrated Camera                 | 673       | 0.74%   |
| Chicony HD User Facing                  | 653       | 0.72%   |
| Chicony USB2.0 Camera                   | 626       | 0.69%   |
| Chicony TOSHIBA Web Camera - HD         | 615       | 0.68%   |
| Chicony HP TrueVision HD Camera         | 609       | 0.67%   |
| Quanta HP TrueVision HD Camera          | 586       | 0.65%   |
| Chicony VGA Webcam                      | 584       | 0.64%   |
| Chicony EasyCamera                      | 559       | 0.62%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 553       | 0.61%   |
| Samsung Galaxy series, misc. (MTP mode) | 551       | 0.61%   |
| Quanta VGA WebCam                       | 540       | 0.6%    |
| Acer BisonCam, NB Pro                   | 535       | 0.59%   |
| Syntek Lenovo EasyCamera                | 532       | 0.59%   |
| Apple FaceTime HD Camera                | 519       | 0.57%   |
| Acer Lenovo Integrated Webcam           | 516       | 0.57%   |
| Realtek Integrated Webcam               | 513       | 0.57%   |
| Bison HD Webcam                         | 513       | 0.57%   |
| Quanta HD Webcam                        | 496       | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 6191      | 36.74%  |
| Synaptics                          | 3784      | 22.45%  |
| Shenzhen Goodix Technology         | 2236      | 13.27%  |
| AuthenTec                          | 1354      | 8.03%   |
| Upek                               | 1107      | 6.57%   |
| Elan Microelectronics              | 917       | 5.44%   |
| LighTuning Technology              | 762       | 4.52%   |
| STMicroelectronics                 | 334       | 1.98%   |
| Focal-systems.Corp                 | 63        | 0.37%   |
| Samsung Electronics                | 41        | 0.24%   |
| Realtek USB2.0 Finger Print Bridge | 35        | 0.21%   |
| HOLTEK                             | 14        | 0.08%   |
| DigitalPersona                     | 5         | 0.03%   |
| Microsoft                          | 3         | 0.02%   |
| Next Biometrics                    | 2         | 0.01%   |
| Dell                               | 2         | 0.01%   |
| Suprema                            | 1         | 0.01%   |
| GDMicroelectronics                 | 1         | 0.01%   |
| Futronic Technology                | 1         | 0.01%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 1365      | 8.1%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1340      | 7.95%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1313      | 7.79%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1027      | 6.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 714       | 4.24%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 694       | 4.12%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 633       | 3.76%   |
| Elan ELAN:Fingerprint                                                      | 557       | 3.3%    |
| Shenzhen Goodix Fingerprint Reader                                         | 493       | 2.93%   |
| Validity Sensors Fingerprint scanner                                       | 457       | 2.71%   |
| Validity Sensors VFS491                                                    | 452       | 2.68%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 446       | 2.65%   |
| Shenzhen Goodix FingerPrint                                                | 430       | 2.55%   |
| AuthenTec AES2810                                                          | 428       | 2.54%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 402       | 2.39%   |
| Validity Sensors Synaptics WBDI                                            | 383       | 2.27%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 356       | 2.11%   |
| Elan ELAN:ARM-M4                                                           | 347       | 2.06%   |
| STMicroelectronics Fingerprint Reader                                      | 332       | 1.97%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 323       | 1.92%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 274       | 1.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 263       | 1.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 262       | 1.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 259       | 1.54%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 252       | 1.5%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 230       | 1.36%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 222       | 1.32%   |
| AuthenTec AES1600                                                          | 221       | 1.31%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 188       | 1.12%   |
| AuthenTec Fingerprint Sensor                                               | 183       | 1.09%   |
| Synaptics  WBDI                                                            | 174       | 1.03%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 171       | 1.01%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 167       | 0.99%   |
| Synaptics UWP WBDI                                                         | 142       | 0.84%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 139       | 0.82%   |
| LighTuning Fingerprint Reader                                              | 134       | 0.8%    |
| Validity Sensors VFS Fingerprint sensor                                    | 108       | 0.64%   |
| Synaptics UWP WBDI Device                                                  | 100       | 0.59%   |
| Synaptics WBDI                                                             | 97        | 0.58%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 90        | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 3447      | 48.08%  |
| Alcor Micro                       | 1919      | 26.76%  |
| O2 Micro                          | 609       | 8.49%   |
| Upek                              | 460       | 6.42%   |
| Lenovo                            | 420       | 5.86%   |
| Gemalto (was Gemplus)             | 72        | 1%      |
| SCM Microsystems                  | 41        | 0.57%   |
| Yubico.com                        | 31        | 0.43%   |
| OmniKey                           | 25        | 0.35%   |
| Aladdin Knowledge Systems         | 20        | 0.28%   |
| Advanced Card Systems             | 19        | 0.26%   |
| Realtek Semiconductor             | 16        | 0.22%   |
| Clay Logic                        | 13        | 0.18%   |
| Giesecke & Devrient               | 9         | 0.13%   |
| Cherry                            | 8         | 0.11%   |
| Chicony Electronics               | 6         | 0.08%   |
| Watchdata                         | 5         | 0.07%   |
| Reiner SCT Kartensysteme          | 5         | 0.07%   |
| Hewlett-Packard                   | 5         | 0.07%   |
| Bit4id                            | 5         | 0.07%   |
| VASCO Data Security International | 4         | 0.06%   |
| Purism, SPC                       | 4         | 0.06%   |
| C3PO                              | 4         | 0.06%   |
| NXP Semiconductors                | 3         | 0.04%   |
| In Focus Systems                  | 3         | 0.04%   |
| Fujitsu Siemens Computers         | 3         | 0.04%   |
| Aladdin R.D.                      | 3         | 0.04%   |
| Aktiv                             | 3         | 0.04%   |
| Microchip Technology              | 2         | 0.03%   |
| Athena Smartcard Solutions        | 2         | 0.03%   |
| SpringCard                        | 1         | 0.01%   |
| MagTek                            | 1         | 0.01%   |
| Kobil Systems                     | 1         | 0.01%   |
| Integrated Technology Express     | 1         | 0.01%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 1904      | 26.54%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1349      | 18.8%   |
| Broadcom 5880                                                                | 775       | 10.8%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 675       | 9.41%   |
| Broadcom 58200                                                               | 619       | 8.63%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 521       | 7.26%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 460       | 6.41%   |
| Lenovo Integrated Smart Card Reader                                          | 419       | 5.84%   |
| O2 Micro Oz776 SmartCard Reader                                              | 88        | 1.23%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 38        | 0.53%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 33        | 0.46%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 27        | 0.38%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 22        | 0.31%   |
| Aladdin Knowledge Systems Token JC                                           | 20        | 0.28%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 16        | 0.22%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 16        | 0.22%   |
| Alcor Micro Watchdata W 1981                                                 | 12        | 0.17%   |
| OmniKey CardMan 4321                                                         | 11        | 0.15%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 9         | 0.13%   |
| Clay Logic Nitrokey Pro                                                      | 9         | 0.13%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 9         | 0.13%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 8         | 0.11%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 6         | 0.08%   |
| Giesecke & Devrient StarSign CUT                                             | 6         | 0.08%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 6         | 0.08%   |
| Watchdata USB Key                                                            | 5         | 0.07%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 5         | 0.07%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 5         | 0.07%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 5         | 0.07%   |
| Bit4id miniLector EVO                                                        | 5         | 0.07%   |
| Advanced Card Systems ACR122U                                                | 5         | 0.07%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 4         | 0.06%   |
| Purism, SPC Librem Key                                                       | 4         | 0.06%   |
| OmniKey CardMan 3021 / 3121                                                  | 4         | 0.06%   |
| OmniKey CardMan 1021                                                         | 4         | 0.06%   |
| Advanced Card Systems ACR39U                                                 | 4         | 0.06%   |
| VASCO Data Security International DIGIPASS 870                               | 3         | 0.04%   |
| OmniKey 3x21 Smart Card Reader                                               | 3         | 0.04%   |
| NXP Semiconductors PR533                                                     | 3         | 0.04%   |
| In Focus Systems EMV Smartcard Reader                                        | 3         | 0.04%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 66424     | 62.32%  |
| 1     | 31716     | 29.76%  |
| 2     | 7019      | 6.59%   |
| 3     | 1027      | 0.96%   |
| 4     | 222       | 0.21%   |
| 5     | 87        | 0.08%   |
| 6     | 41        | 0.04%   |
| 7     | 27        | 0.03%   |
| 8     | 14        | 0.01%   |
| 9     | 5         | 0.005%  |
| 10    | 3         | 0.003%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16652     | 34.39%  |
| Graphics card            | 11047     | 22.82%  |
| Chipcard                 | 6440      | 13.3%   |
| Net/wireless             | 4531      | 9.36%   |
| Multimedia controller    | 2605      | 5.38%   |
| Bluetooth                | 1661      | 3.43%   |
| Camera                   | 1322      | 2.73%   |
| Storage                  | 1027      | 2.12%   |
| Communication controller | 939       | 1.94%   |
| Card reader              | 496       | 1.02%   |
| Sound                    | 450       | 0.93%   |
| Net/ethernet             | 379       | 0.78%   |
| Modem                    | 271       | 0.56%   |
| Flash memory             | 254       | 0.52%   |
| Network                  | 147       | 0.3%    |
| Firewire controller      | 45        | 0.09%   |
| Dvb card                 | 30        | 0.06%   |
| Storage/ide              | 27        | 0.06%   |
| Storage/nvme             | 21        | 0.04%   |
| Unassigned class         | 19        | 0.04%   |
| Storage/ata              | 12        | 0.02%   |
| Wireless                 | 10        | 0.02%   |
| Tv card                  | 10        | 0.02%   |
| Storage/raid             | 9         | 0.02%   |
| Unclassified device      | 7         | 0.01%   |
| Video                    | 4         | 0.01%   |

