Xubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

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

Total: 195

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E5440              | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Toshiba       | Satellite C650              | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASUSTek       | X555LF                      | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| Dell          | Latitude E5450              | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| Sony          | VPCS12V9E                   | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| Fusion5       | Lapbook T90B                | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | UX31E                       | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| Lenovo        | G50-80 80E5                 | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| Sony          | VPCEH25EN                   | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| HP            | 245 G8 Notebook PC          | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| HP            | ProBook 6450b               | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Precision M6400             | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Dell          | Inspiron 5490               | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Inspiron 3421               | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| HP            | 15                          | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Unknown       | Unknown                     | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| GPU Compan... | GWTN116-3                   | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| Lenovo        | B70-80 80MR                 | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Toshiba       | Satellite C650              | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Tactus        | GeoBook 140                 | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Dell          | Latitude 7490               | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Dell          | Precision 5540              | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Dell          | Inspiron N5010              | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| Dell          | XPS 13 9380                 | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| HP            | EliteBook 8540p             | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| ASUSTek       | K53TA                       | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Toshiba       | PT10F                       | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Acer          | Aspire V3-551G              | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| GMKtec        | NucBox5                     | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Schenker      | WORK (Early 2021)           | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Lenovo        | G50-30 80G0                 | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Acer          | Aspire E1-532               | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| ASUSTek       | X453MA                      | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| Samsung       | 370E4K                      | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| HP            | EliteBook 840 G3            | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| Standard      | Unknown                     | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| HP            | ProBook 445 G7              | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| GPU Compan... | GWTN141-4                   | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| AMI           | Intel                       | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Chuwi         | GemiBook Pro                | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Latitude D820               | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| HP            | Mini 5103                   | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| Google        | Snappy                      | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| ASUSTek       | UL30A                       | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Google        | Droid                       | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Unknown       | Unknown                     | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| Dell          | Inspiron 7501               | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| Dell          | Latitude 7420               | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Dell          | XPS M1530                   | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| Dell          | XPS M1530                   | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| Acer          | Aspire ES1-512              | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| HP            | 255 G8 Notebook PC          | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.15.0-56-generic          | 20        | 11.98%  |
| 5.15.0-47-generic          | 19        | 11.38%  |
| 5.15.0-52-generic          | 16        | 9.58%   |
| 5.15.0-48-generic          | 16        | 9.58%   |
| 5.15.0-25-generic          | 13        | 7.78%   |
| 5.15.0-46-generic          | 8         | 4.79%   |
| 5.15.0-27-generic          | 7         | 4.19%   |
| 5.15.0-53-generic          | 6         | 3.59%   |
| 5.15.0-50-generic          | 5         | 2.99%   |
| 5.15.0-40-generic          | 5         | 2.99%   |
| 5.15.0-39-generic          | 5         | 2.99%   |
| 5.15.0-35-generic          | 5         | 2.99%   |
| 5.15.0-43-generic          | 4         | 2.4%    |
| 5.15.0-41-generic          | 4         | 2.4%    |
| 5.15.0-37-generic          | 3         | 1.8%    |
| 5.17.0-1020-oem            | 2         | 1.2%    |
| 5.17.0-1013-oem            | 2         | 1.2%    |
| 5.15.0-57-generic          | 2         | 1.2%    |
| 5.15.0-33-generic          | 2         | 1.2%    |
| 6.1.0                      | 1         | 0.6%    |
| 6.0.9-060009-generic       | 1         | 0.6%    |
| 6.0.7-x64v3-xanmod1        | 1         | 0.6%    |
| 6.0.0-1007-oem             | 1         | 0.6%    |
| 6.0.0                      | 1         | 0.6%    |
| 5.4.0-126-generic          | 1         | 0.6%    |
| 5.19.5-051905-generic      | 1         | 0.6%    |
| 5.19.1                     | 1         | 0.6%    |
| 5.19.0-051900-generic      | 1         | 0.6%    |
| 5.18.0-10.1-liquorix-amd64 | 1         | 0.6%    |
| 5.18.0                     | 1         | 0.6%    |
| 5.17.3-051703-generic      | 1         | 0.6%    |
| 5.17.0-ashpy3-lyesdef      | 1         | 0.6%    |
| 5.17.0-1025-oem            | 1         | 0.6%    |
| 5.17.0-1015-oem            | 1         | 0.6%    |
| 5.15.0-54-generic          | 1         | 0.6%    |
| 5.15.0-50-lowlatency       | 1         | 0.6%    |
| 5.15.0-48-lowlatency       | 1         | 0.6%    |
| 5.15.0-46-lowlatency       | 1         | 0.6%    |
| 5.15.0-30-generic          | 1         | 0.6%    |
| 5.15.0-27-lowlatency       | 1         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.0   | 142       | 87.65%  |
| 5.17.0   | 7         | 4.32%   |
| 6.0.0    | 2         | 1.23%   |
| 5.18.0   | 2         | 1.23%   |
| 6.1.0    | 1         | 0.62%   |
| 6.0.9    | 1         | 0.62%   |
| 6.0.7    | 1         | 0.62%   |
| 5.4.0    | 1         | 0.62%   |
| 5.19.5   | 1         | 0.62%   |
| 5.19.1   | 1         | 0.62%   |
| 5.19.0   | 1         | 0.62%   |
| 5.17.3   | 1         | 0.62%   |
| 4.19.241 | 1         | 0.62%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 142       | 87.65%  |
| 5.17    | 8         | 4.94%   |
| 6.0     | 4         | 2.47%   |
| 5.19    | 3         | 1.85%   |
| 5.18    | 2         | 1.23%   |
| 6.1     | 1         | 0.62%   |
| 5.4     | 1         | 0.62%   |
| 4.19    | 1         | 0.62%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 159       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 154       | 96.86%  |
| GNOME | 4         | 2.52%   |
| i3    | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 154       | 96.86%  |
| Wayland | 3         | 1.89%   |
| Tty     | 2         | 1.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 143       | 89.94%  |
| GDM3    | 8         | 5.03%   |
| Unknown | 6         | 3.77%   |
| SLiM    | 1         | 0.63%   |
| SDDM    | 1         | 0.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 71        | 44.65%  |
| de_DE | 19        | 11.95%  |
| fr_FR | 16        | 10.06%  |
| it_IT | 10        | 6.29%   |
| en_GB | 8         | 5.03%   |
| ru_RU | 3         | 1.89%   |
| pt_BR | 3         | 1.89%   |
| es_ES | 3         | 1.89%   |
| en_AU | 3         | 1.89%   |
| tr_TR | 2         | 1.26%   |
| hu_HU | 2         | 1.26%   |
| en_IN | 2         | 1.26%   |
| en_CA | 2         | 1.26%   |
| cs_CZ | 2         | 1.26%   |
| ru_UA | 1         | 0.63%   |
| nl_NL | 1         | 0.63%   |
| nl_BE | 1         | 0.63%   |
| ja_JP | 1         | 0.63%   |
| fr_BE | 1         | 0.63%   |
| es_VE | 1         | 0.63%   |
| es_MX | 1         | 0.63%   |
| es_CO | 1         | 0.63%   |
| es_CL | 1         | 0.63%   |
| en_IL | 1         | 0.63%   |
| de_CH | 1         | 0.63%   |
| C     | 1         | 0.63%   |
| bg_BG | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 93        | 58.49%  |
| BIOS | 66        | 41.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 145       | 91.19%  |
| Overlay | 8         | 5.03%   |
| Zfs     | 4         | 2.52%   |
| Btrfs   | 2         | 1.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 118       | 72.39%  |
| Unknown | 31        | 19.02%  |
| MBR     | 14        | 8.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 147       | 91.3%   |
| Yes       | 14        | 8.7%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 70.44%  |
| Yes       | 47        | 29.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 35        | 22.01%  |
| Hewlett-Packard     | 33        | 20.75%  |
| ASUSTek Computer    | 23        | 14.47%  |
| Dell                | 18        | 11.32%  |
| Acer                | 14        | 8.81%   |
| Google              | 6         | 3.77%   |
| Toshiba             | 3         | 1.89%   |
| Sony                | 3         | 1.89%   |
| HUAWEI              | 3         | 1.89%   |
| GPU Company         | 3         | 1.89%   |
| Apple               | 2         | 1.26%   |
| Unknown             | 2         | 1.26%   |
| Tactus              | 1         | 0.63%   |
| Standard            | 1         | 0.63%   |
| Schenker            | 1         | 0.63%   |
| Samsung Electronics | 1         | 0.63%   |
| Panasonic           | 1         | 0.63%   |
| Packard Bell        | 1         | 0.63%   |
| MSI                 | 1         | 0.63%   |
| Mediacom            | 1         | 0.63%   |
| HIGRADED            | 1         | 0.63%   |
| Fusion5             | 1         | 0.63%   |
| ECS                 | 1         | 0.63%   |
| Digma               | 1         | 0.63%   |
| Chuwi               | 1         | 0.63%   |
| AMI                 | 1         | 0.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP EliteBook 840 G3                    | 4         | 2.52%   |
| Unknown                                | 3         | 1.89%   |
| HP Pavilion Notebook                   | 2         | 1.26%   |
| HP 255 G8 Notebook PC                  | 2         | 1.26%   |
| GPU Company GWTN116-3                  | 2         | 1.26%   |
| Toshiba Satellite Pro R50-C            | 1         | 0.63%   |
| Toshiba Satellite C650                 | 1         | 0.63%   |
| Toshiba PT10F                          | 1         | 0.63%   |
| Tactus GeoBook 140                     | 1         | 0.63%   |
| Sony VPCS12V9E                         | 1         | 0.63%   |
| Sony VPCEH25EN                         | 1         | 0.63%   |
| Sony SVE1512C6EB                       | 1         | 0.63%   |
| Schenker WORK (Early 2021)             | 1         | 0.63%   |
| Samsung 370E4K                         | 1         | 0.63%   |
| Panasonic CF-D1DVA06F3                 | 1         | 0.63%   |
| Packard Bell EasyNote MH45             | 1         | 0.63%   |
| MSI GF63 Thin 9RCX                     | 1         | 0.63%   |
| Mediacom SmartBook 14 FullHD - SB14UC  | 1         | 0.63%   |
| Lenovo V340-17IWL 81RG                 | 1         | 0.63%   |
| Lenovo V330-15IKB 81AX                 | 1         | 0.63%   |
| Lenovo ThinkPad X230 23252S4           | 1         | 0.63%   |
| Lenovo ThinkPad X220 42918F6           | 1         | 0.63%   |
| Lenovo ThinkPad T61p 6457A24           | 1         | 0.63%   |
| Lenovo ThinkPad T61 7659AB7            | 1         | 0.63%   |
| Lenovo ThinkPad T470s 20HF004MMX       | 1         | 0.63%   |
| Lenovo ThinkPad T460s 20FAS6JY00       | 1         | 0.63%   |
| Lenovo ThinkPad T460s 20FAS30L01       | 1         | 0.63%   |
| Lenovo ThinkPad T460s 20FAS0Q900       | 1         | 0.63%   |
| Lenovo ThinkPad T440p 20AN0033RT       | 1         | 0.63%   |
| Lenovo ThinkPad T430 23501K1           | 1         | 0.63%   |
| Lenovo ThinkPad T420 42361L0           | 1         | 0.63%   |
| Lenovo ThinkPad T410 2537AF8           | 1         | 0.63%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B9MX | 1         | 0.63%   |
| Lenovo ThinkPad T14s Gen 2a 20XF004RUS | 1         | 0.63%   |
| Lenovo ThinkPad P70 20ERCTO1WW         | 1         | 0.63%   |
| Lenovo ThinkPad P51 20HH0014IX         | 1         | 0.63%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002LUS  | 1         | 0.63%   |
| Lenovo ThinkPad L520 5017AL3           | 1         | 0.63%   |
| Lenovo ThinkPad Edge E545 20B20015GE   | 1         | 0.63%   |
| Lenovo ThinkPad E580 20KS001JGE        | 1         | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 21        | 13.21%  |
| HP Pavilion            | 11        | 6.92%   |
| Acer Aspire            | 11        | 6.92%   |
| Dell Latitude          | 8         | 5.03%   |
| HP EliteBook           | 7         | 4.4%    |
| Lenovo IdeaPad         | 6         | 3.77%   |
| Dell Inspiron          | 5         | 3.14%   |
| ASUS VivoBook          | 4         | 2.52%   |
| HP Laptop              | 3         | 1.89%   |
| HP 255                 | 3         | 1.89%   |
| Dell Precision         | 3         | 1.89%   |
| Unknown                | 3         | 1.89%   |
| Toshiba Satellite      | 2         | 1.26%   |
| Lenovo ThinkBook       | 2         | 1.26%   |
| HP ProBook             | 2         | 1.26%   |
| GPU Company GWTN116-3  | 2         | 1.26%   |
| Dell XPS               | 2         | 1.26%   |
| ASUS ZenBook           | 2         | 1.26%   |
| ASUS ROG               | 2         | 1.26%   |
| ASUS ASUS              | 2         | 1.26%   |
| Toshiba PT10F          | 1         | 0.63%   |
| Tactus GeoBook         | 1         | 0.63%   |
| Sony VPCS12V9E         | 1         | 0.63%   |
| Sony VPCEH25EN         | 1         | 0.63%   |
| Sony SVE1512C6EB       | 1         | 0.63%   |
| Schenker WORK          | 1         | 0.63%   |
| Samsung 370E4K         | 1         | 0.63%   |
| Panasonic CF-D1DVA06F3 | 1         | 0.63%   |
| Packard Bell EasyNote  | 1         | 0.63%   |
| MSI GF63               | 1         | 0.63%   |
| Mediacom SmartBook     | 1         | 0.63%   |
| Lenovo V340-17IWL      | 1         | 0.63%   |
| Lenovo V330-15IKB      | 1         | 0.63%   |
| Lenovo G50-80          | 1         | 0.63%   |
| Lenovo G50-30          | 1         | 0.63%   |
| Lenovo B70-80          | 1         | 0.63%   |
| Lenovo 14w             | 1         | 0.63%   |
| HUAWEI HVY-WXX9        | 1         | 0.63%   |
| HUAWEI BOM-WXX9        | 1         | 0.63%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 22        | 13.84%  |
| 2020 | 20        | 12.58%  |
| 2016 | 13        | 8.18%   |
| 2017 | 11        | 6.92%   |
| 2015 | 11        | 6.92%   |
| 2012 | 10        | 6.29%   |
| 2011 | 10        | 6.29%   |
| 2019 | 9         | 5.66%   |
| 2014 | 9         | 5.66%   |
| 2013 | 9         | 5.66%   |
| 2022 | 6         | 3.77%   |
| 2018 | 6         | 3.77%   |
| 2010 | 6         | 3.77%   |
| 2008 | 6         | 3.77%   |
| 2009 | 5         | 3.14%   |
| 2007 | 5         | 3.14%   |
| 2006 | 1         | 0.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 159       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 146       | 91.82%  |
| Enabled  | 13        | 8.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 153       | 96.23%  |
| Yes  | 6         | 3.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 51        | 32.08%  |
| 3.01-4.0    | 47        | 29.56%  |
| 16.01-24.0  | 22        | 13.84%  |
| 8.01-16.0   | 19        | 11.95%  |
| 1.01-2.0    | 10        | 6.29%   |
| 32.01-64.0  | 5         | 3.14%   |
| 64.01-256.0 | 3         | 1.89%   |
| 2.01-3.0    | 1         | 0.63%   |
| 0.51-1.0    | 1         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 75        | 45.45%  |
| 2.01-3.0  | 50        | 30.3%   |
| 0.51-1.0  | 16        | 9.7%    |
| 3.01-4.0  | 10        | 6.06%   |
| 4.01-8.0  | 9         | 5.45%   |
| 8.01-16.0 | 5         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 124       | 77.5%   |
| 2      | 30        | 18.75%  |
| 3      | 3         | 1.88%   |
| 4      | 2         | 1.25%   |
| 0      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 61.01%  |
| Yes       | 62        | 38.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 77.99%  |
| No        | 35        | 22.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 98.11%  |
| No        | 3         | 1.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 76.73%  |
| No        | 37        | 23.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 28        | 17.5%   |
| Germany      | 23        | 14.38%  |
| France       | 18        | 11.25%  |
| Italy        | 13        | 8.13%   |
| UK           | 8         | 5%      |
| Russia       | 7         | 4.38%   |
| Netherlands  | 4         | 2.5%    |
| Mexico       | 4         | 2.5%    |
| India        | 4         | 2.5%    |
| Czechia      | 4         | 2.5%    |
| Sweden       | 3         | 1.88%   |
| Malaysia     | 3         | 1.88%   |
| Iran         | 3         | 1.88%   |
| Belgium      | 3         | 1.88%   |
| Australia    | 3         | 1.88%   |
| Turkey       | 2         | 1.25%   |
| Spain        | 2         | 1.25%   |
| Poland       | 2         | 1.25%   |
| Israel       | 2         | 1.25%   |
| Indonesia    | 2         | 1.25%   |
| Hungary      | 2         | 1.25%   |
| Colombia     | 2         | 1.25%   |
| Brazil       | 2         | 1.25%   |
| Austria      | 2         | 1.25%   |
| Argentina    | 2         | 1.25%   |
| Vietnam      | 1         | 0.63%   |
| Venezuela    | 1         | 0.63%   |
| Switzerland  | 1         | 0.63%   |
| Sint Maarten | 1         | 0.63%   |
| Portugal     | 1         | 0.63%   |
| Madagascar   | 1         | 0.63%   |
| Japan        | 1         | 0.63%   |
| Finland      | 1         | 0.63%   |
| Egypt        | 1         | 0.63%   |
| Chile        | 1         | 0.63%   |
| Canada       | 1         | 0.63%   |
| Bulgaria     | 1         | 0.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Munich         | 3         | 1.84%   |
| Melbourne      | 3         | 1.84%   |
| Kuala Lumpur   | 3         | 1.84%   |
| Warsaw         | 2         | 1.23%   |
| Uppsala        | 2         | 1.23%   |
| St Petersburg  | 2         | 1.23%   |
| Paris          | 2         | 1.23%   |
| Oklahoma City  | 2         | 1.23%   |
| Mumbai         | 2         | 1.23%   |
| Moscow         | 2         | 1.23%   |
| Milan          | 2         | 1.23%   |
| Leipzig        | 2         | 1.23%   |
| Indianapolis   | 2         | 1.23%   |
| Hamburg        | 2         | 1.23%   |
| Farmington     | 2         | 1.23%   |
| Brest          | 2         | 1.23%   |
| Belfort        | 2         | 1.23%   |
| Auxerre        | 2         | 1.23%   |
| Ankara         | 2         | 1.23%   |
| Yokohama       | 1         | 0.61%   |
| Wierden        | 1         | 0.61%   |
| Washington     | 1         | 0.61%   |
| Villavicencio  | 1         | 0.61%   |
| Villach        | 1         | 0.61%   |
| Vidin          | 1         | 0.61%   |
| Verona         | 1         | 0.61%   |
| Västerås     | 1         | 0.61%   |
| Ucel           | 1         | 0.61%   |
| Tustin         | 1         | 0.61%   |
| Treviso        | 1         | 0.61%   |
| Toamasina      | 1         | 0.61%   |
| Tehran         | 1         | 0.61%   |
| Surabaya       | 1         | 0.61%   |
| Stuttgart      | 1         | 0.61%   |
| Stroud         | 1         | 0.61%   |
| Stoke-on-Trent | 1         | 0.61%   |
| Sombrio        | 1         | 0.61%   |
| Smiths Falls   | 1         | 0.61%   |
| Shrewsbury     | 1         | 0.61%   |
| Seattle        | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 34     | 16.3%   |
| WDC                 | 23        | 24     | 12.5%   |
| Unknown             | 20        | 23     | 10.87%  |
| Seagate             | 16        | 18     | 8.7%    |
| SK hynix            | 12        | 13     | 6.52%   |
| Kingston            | 9         | 11     | 4.89%   |
| SanDisk             | 8         | 8      | 4.35%   |
| Intel               | 7         | 7      | 3.8%    |
| Hitachi             | 6         | 6      | 3.26%   |
| Crucial             | 6         | 6      | 3.26%   |
| HGST                | 5         | 5      | 2.72%   |
| PNY                 | 4         | 4      | 2.17%   |
| Transcend           | 3         | 4      | 1.63%   |
| Toshiba             | 3         | 3      | 1.63%   |
| Phison              | 3         | 10     | 1.63%   |
| Micron Technology   | 3         | 3      | 1.63%   |
| China               | 3         | 4      | 1.63%   |
| A-DATA Technology   | 3         | 5      | 1.63%   |
| TO Exter            | 2         | 2      | 1.09%   |
| Silicon Motion      | 2         | 2      | 1.09%   |
| LITEON              | 2         | 2      | 1.09%   |
| Apacer              | 2         | 2      | 1.09%   |
| USB3.0              | 1         | 2      | 0.54%   |
| SSSTC               | 1         | 1      | 0.54%   |
| SSD0240S            | 1         | 1      | 0.54%   |
| Patriot             | 1         | 1      | 0.54%   |
| Netac               | 1         | 1      | 0.54%   |
| Linux               | 1         | 1      | 0.54%   |
| Lenovo              | 1         | 1      | 0.54%   |
| Kimtigo             | 1         | 1      | 0.54%   |
| INNOVATION IT       | 1         | 1      | 0.54%   |
| FORESEE             | 1         | 1      | 0.54%   |
| Apple               | 1         | 2      | 0.54%   |
| Unknown             | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 3         | 1.57%   |
| Samsung SSD 850 EVO 500GB              | 3         | 1.57%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 1.57%   |
| HGST HTS541010A9E680 1TB               | 3         | 1.57%   |
| WDC WD10JPCX-24UE4T0 1TB               | 2         | 1.05%   |
| Unknown SA08G  8GB                     | 2         | 1.05%   |
| Unknown MMC64G  64GB                   | 2         | 1.05%   |
| Unknown MMC Card  32GB                 | 2         | 1.05%   |
| TO Exter nal USB 3.0 512GB             | 2         | 1.05%   |
| Seagate ST500LT012-9WS142 500GB        | 2         | 1.05%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 1.05%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 2         | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 1.05%   |
| SanDisk DF4032  32GB                   | 2         | 1.05%   |
| Samsung MZALQ512HALU-000L2 512GB       | 2         | 1.05%   |
| PNY CS900 120GB SSD                    | 2         | 1.05%   |
| Kingston SA400S37480G 480GB SSD        | 2         | 1.05%   |
| Intel SSDPEKNU512GZ 512GB              | 2         | 1.05%   |
| WDC WDS960G2G0C-00AJM0 960GB           | 1         | 0.52%   |
| WDC WDS500G2B0C 500GB                  | 1         | 0.52%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 1         | 0.52%   |
| WDC WDS480G2G0A-00JH30 480GB SSD       | 1         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.52%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.52%   |
| WDC WD7500BPVT-60HXZT3 752GB           | 1         | 0.52%   |
| WDC WD5000LPVX-08V0TT5 500GB           | 1         | 0.52%   |
| WDC WD5000LPCX-00VHAT0 500GB           | 1         | 0.52%   |
| WDC WD5000BEVT-22ZAT0 500GB            | 1         | 0.52%   |
| WDC WD3200LPVX-75V0TT0 320GB           | 1         | 0.52%   |
| WDC WD3200BEVT-22ZCT0 320GB            | 1         | 0.52%   |
| WDC WD1200BEVS-60UST0 120GB            | 1         | 0.52%   |
| WDC WD10SPZX-80Z10T2 1TB               | 1         | 0.52%   |
| WDC WD10SPZX-22Z10T1 1TB               | 1         | 0.52%   |
| WDC WD10SPZX-21Z10T0 1TB               | 1         | 0.52%   |
| WDC WD10SPZX-00Z10T0 1TB               | 1         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB               | 1         | 0.52%   |
| WDC WD10JPVT-55A1YT0 1TB               | 1         | 0.52%   |
| WDC WD Blue SA510 2.5 500GB            | 1         | 0.52%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB   | 1         | 0.52%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB   | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 18     | 34.78%  |
| WDC     | 15        | 15     | 32.61%  |
| Hitachi | 6         | 6      | 13.04%  |
| HGST    | 5         | 5      | 10.87%  |
| Toshiba | 2         | 2      | 4.35%   |
| USB3.0  | 1         | 2      | 2.17%   |
| Unknown | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 19     | 24.24%  |
| Kingston            | 8         | 9      | 12.12%  |
| Crucial             | 5         | 5      | 7.58%   |
| WDC                 | 4         | 4      | 6.06%   |
| PNY                 | 4         | 4      | 6.06%   |
| Transcend           | 3         | 3      | 4.55%   |
| SanDisk             | 3         | 3      | 4.55%   |
| China               | 3         | 4      | 4.55%   |
| A-DATA Technology   | 3         | 5      | 4.55%   |
| TO Exter            | 2         | 2      | 3.03%   |
| SK hynix            | 2         | 2      | 3.03%   |
| LITEON              | 2         | 2      | 3.03%   |
| Apacer              | 2         | 2      | 3.03%   |
| SSSTC               | 1         | 1      | 1.52%   |
| Patriot             | 1         | 1      | 1.52%   |
| Netac               | 1         | 1      | 1.52%   |
| Micron Technology   | 1         | 1      | 1.52%   |
| Linux               | 1         | 1      | 1.52%   |
| Kimtigo             | 1         | 1      | 1.52%   |
| Intel               | 1         | 1      | 1.52%   |
| INNOVATION IT       | 1         | 1      | 1.52%   |
| FORESEE             | 1         | 1      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 60        | 73     | 33.52%  |
| NVMe    | 51        | 61     | 28.49%  |
| HDD     | 44        | 49     | 24.58%  |
| MMC     | 23        | 26     | 12.85%  |
| Unknown | 1         | 1      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 99        | 117    | 55.62%  |
| NVMe | 51        | 61     | 28.65%  |
| MMC  | 23        | 26     | 12.92%  |
| SAS  | 5         | 6      | 2.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 88     | 70.64%  |
| 0.51-1.0   | 29        | 31     | 26.61%  |
| 1.01-2.0   | 2         | 2      | 1.83%   |
| 3.01-4.0   | 1         | 1      | 0.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 48        | 29.81%  |
| 251-500        | 44        | 27.33%  |
| 501-1000       | 21        | 13.04%  |
| 51-100         | 19        | 11.8%   |
| 1-20           | 12        | 7.45%   |
| 21-50          | 9         | 5.59%   |
| 1001-2000      | 5         | 3.11%   |
| More than 3000 | 1         | 0.62%   |
| 2001-3000      | 1         | 0.62%   |
| Unknown        | 1         | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 69        | 42.59%  |
| 21-50     | 38        | 23.46%  |
| 51-100    | 23        | 14.2%   |
| 101-250   | 17        | 10.49%  |
| 251-500   | 8         | 4.94%   |
| 501-1000  | 5         | 3.09%   |
| 1001-2000 | 1         | 0.62%   |
| Unknown   | 1         | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 11.11%  |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1      | 5.56%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 5.56%   |
| SSSTC CVB-8D128-HP 128GB                         | 1         | 1      | 5.56%   |
| Seagate ST9500325ASG 500GB                       | 1         | 1      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 5.56%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 5.56%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 5.56%   |
| LITEON LCH-512V2S 512GB SSD                      | 1         | 1      | 5.56%   |
| Kingston SNS4151S332GD 32GB SSD                  | 1         | 2      | 5.56%   |
| Intel SSDSCKKF240H6L 240GB                       | 1         | 1      | 5.56%   |
| Hitachi HTS725050A9A364 500GB                    | 1         | 1      | 5.56%   |
| Hitachi HTS543212L9A300 120GB                    | 1         | 1      | 5.56%   |
| Hitachi HTS541080G9SA00 80GB                     | 1         | 1      | 5.56%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 5.56%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 27.78%  |
| Hitachi             | 3         | 3      | 16.67%  |
| WDC                 | 2         | 2      | 11.11%  |
| HGST                | 2         | 2      | 11.11%  |
| SSSTC               | 1         | 1      | 5.56%   |
| SanDisk             | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |
| LITEON              | 1         | 1      | 5.56%   |
| Kingston            | 1         | 2      | 5.56%   |
| Intel               | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 45.45%  |
| Hitachi | 3         | 3      | 27.27%  |
| HGST    | 2         | 2      | 18.18%  |
| WDC     | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 61.11%  |
| SSD  | 7         | 8      | 38.89%  |

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
| Works    | 85        | 105    | 51.2%   |
| Detected | 63        | 86     | 37.95%  |
| Malfunc  | 18        | 19     | 10.84%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 106       | 60.23%  |
| AMD                          | 26        | 14.77%  |
| Samsung Electronics          | 14        | 7.95%   |
| SK hynix                     | 10        | 5.68%   |
| SanDisk                      | 7         | 3.98%   |
| Silicon Motion               | 3         | 1.7%    |
| Phison Electronics           | 3         | 1.7%    |
| Kingston Technology Company  | 2         | 1.14%   |
| Toshiba America Info Systems | 1         | 0.57%   |
| Micron/Crucial Technology    | 1         | 0.57%   |
| Micron Technology            | 1         | 0.57%   |
| Lenovo                       | 1         | 0.57%   |
| Apple                        | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 13.09%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 5.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 5.24%   |
| Samsung NVMe SSD Controller 980                                                  | 8         | 4.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 4.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 4.19%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 3.66%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 6         | 3.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 2.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5         | 2.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 2.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 2.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 2.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.09%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 1.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.57%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 1.57%   |
| Intel SSD 660P Series                                                            | 3         | 1.57%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 1.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.57%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.57%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 1.05%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 1.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.05%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.05%   |
| Intel Non-Volatile memory controller                                             | 2         | 1.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.05%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.52%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.52%   |
| SK hynix BC511                                                                   | 1         | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.52%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.52%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 116       | 61.7%   |
| NVMe | 51        | 27.13%  |
| IDE  | 11        | 5.85%   |
| RAID | 10        | 5.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 126       | 79.25%  |
| AMD    | 33        | 20.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 2.52%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 4         | 2.52%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 2.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 1.89%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 3         | 1.89%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 1.89%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 3         | 1.89%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 3         | 1.89%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 3         | 1.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.89%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 1.89%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 3         | 1.89%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 3         | 1.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.26%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.26%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 1.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.26%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.26%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.26%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.26%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.26%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 1.26%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.26%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.26%   |
| Intel Celeron 3205U @ 1.50GHz               | 2         | 1.26%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 2         | 1.26%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 1.26%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.26%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics  | 2         | 1.26%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 2         | 1.26%   |
| AMD A6-7310 APU with AMD Radeon R4 Graphics | 2         | 1.26%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 0.63%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.63%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.63%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.63%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 0.63%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 0.63%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.63%   |
| Intel Pentium CPU 5405U @ 2.30GHz           | 1         | 0.63%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 32        | 20.13%  |
| Intel Celeron           | 27        | 16.98%  |
| Intel Core i7           | 18        | 11.32%  |
| Other                   | 14        | 8.81%   |
| Intel Core i3           | 12        | 7.55%   |
| Intel Core 2 Duo        | 6         | 3.77%   |
| AMD Ryzen 7             | 6         | 3.77%   |
| AMD Ryzen 5             | 6         | 3.77%   |
| Intel Atom              | 5         | 3.14%   |
| AMD A6                  | 5         | 3.14%   |
| Intel Pentium           | 3         | 1.89%   |
| AMD A8                  | 3         | 1.89%   |
| Intel Pentium Dual      | 2         | 1.26%   |
| Intel Core 2            | 2         | 1.26%   |
| AMD Ryzen 9             | 2         | 1.26%   |
| AMD Ryzen 5 PRO         | 2         | 1.26%   |
| AMD E2                  | 2         | 1.26%   |
| AMD A4                  | 2         | 1.26%   |
| AMD A10                 | 2         | 1.26%   |
| Intel Xeon              | 1         | 0.63%   |
| Intel Pentium Silver    | 1         | 0.63%   |
| Intel Pentium Dual-Core | 1         | 0.63%   |
| Intel Genuine           | 1         | 0.63%   |
| Intel Core 2 Extreme    | 1         | 0.63%   |
| AMD FX                  | 1         | 0.63%   |
| AMD E1                  | 1         | 0.63%   |
| AMD Athlon              | 1         | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 94        | 59.12%  |
| 4      | 42        | 26.42%  |
| 6      | 11        | 6.92%   |
| 8      | 9         | 5.66%   |
| 1      | 2         | 1.26%   |
| 16     | 1         | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 159       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 100       | 62.89%  |
| 1      | 59        | 37.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 159       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 28.93%  |
| 0x806c1    | 11        | 6.92%   |
| 0x306d4    | 7         | 4.4%    |
| 0x406e3    | 6         | 3.77%   |
| 0x306a9    | 5         | 3.14%   |
| 0x30678    | 5         | 3.14%   |
| 0x08608103 | 5         | 3.14%   |
| 0xa0652    | 4         | 2.52%   |
| 0x806ec    | 4         | 2.52%   |
| 0x206a7    | 4         | 2.52%   |
| 0x706a8    | 3         | 1.89%   |
| 0x6fd      | 3         | 1.89%   |
| 0x506c9    | 3         | 1.89%   |
| 0x406c3    | 3         | 1.89%   |
| 0x1067a    | 3         | 1.89%   |
| 0x906ea    | 2         | 1.26%   |
| 0x806e9    | 2         | 1.26%   |
| 0x806d1    | 2         | 1.26%   |
| 0x6fb      | 2         | 1.26%   |
| 0x6f6      | 2         | 1.26%   |
| 0x506ca    | 2         | 1.26%   |
| 0x406c4    | 2         | 1.26%   |
| 0x40651    | 2         | 1.26%   |
| 0x20655    | 2         | 1.26%   |
| 0x20652    | 2         | 1.26%   |
| 0x0a50000c | 2         | 1.26%   |
| 0x08600104 | 2         | 1.26%   |
| 0x08108109 | 2         | 1.26%   |
| 0x07030105 | 2         | 1.26%   |
| 0x906e9    | 1         | 0.63%   |
| 0x906c0    | 1         | 0.63%   |
| 0x806ea    | 1         | 0.63%   |
| 0x706a1    | 1         | 0.63%   |
| 0x506e3    | 1         | 0.63%   |
| 0x30661    | 1         | 0.63%   |
| 0x106e5    | 1         | 0.63%   |
| 0x10676    | 1         | 0.63%   |
| 0x0a404101 | 1         | 0.63%   |
| 0x0a201016 | 1         | 0.63%   |
| 0x08600106 | 1         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 18        | 11.32%  |
| Silvermont    | 13        | 8.18%   |
| TigerLake     | 12        | 7.55%   |
| Skylake       | 11        | 6.92%   |
| IvyBridge     | 10        | 6.29%   |
| SandyBridge   | 9         | 5.66%   |
| Broadwell     | 8         | 5.03%   |
| Westmere      | 7         | 4.4%    |
| Core          | 7         | 4.4%    |
| Penryn        | 6         | 3.77%   |
| Goldmont      | 6         | 3.77%   |
| Unknown       | 6         | 3.77%   |
| Puma          | 5         | 3.14%   |
| Goldmont plus | 5         | 3.14%   |
| Zen 3         | 4         | 2.52%   |
| Zen 2         | 4         | 2.52%   |
| Excavator     | 4         | 2.52%   |
| CometLake     | 4         | 2.52%   |
| Zen+          | 3         | 1.89%   |
| Icelake       | 3         | 1.89%   |
| Haswell       | 3         | 1.89%   |
| Piledriver    | 2         | 1.26%   |
| K10 Llano     | 2         | 1.26%   |
| Bonnell       | 2         | 1.26%   |
| Bobcat        | 2         | 1.26%   |
| Tremont       | 1         | 0.63%   |
| Steamroller   | 1         | 0.63%   |
| Nehalem       | 1         | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 113       | 61.41%  |
| AMD    | 38        | 20.65%  |
| Nvidia | 33        | 17.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 5.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 5.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 4.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 4.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 4.15%   |
| Intel HD Graphics 5500                                                                   | 6         | 3.11%   |
| Intel HD Graphics 500                                                                    | 6         | 3.11%   |
| Intel HD Graphics 620                                                                    | 5         | 2.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.59%   |
| AMD Lucienne                                                                             | 5         | 2.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.07%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 2.07%   |
| AMD Renoir                                                                               | 4         | 2.07%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 2.07%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 1.55%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.55%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.55%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 1.04%   |
| Nvidia TU117M                                                                            | 2         | 1.04%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.04%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.04%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.04%   |
| Intel HD Graphics                                                                        | 2         | 1.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.04%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.04%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.04%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 2         | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.52%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.52%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.52%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.52%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 91        | 57.23%  |
| 1 x AMD        | 26        | 16.35%  |
| Intel + Nvidia | 18        | 11.32%  |
| 1 x Nvidia     | 11        | 6.92%   |
| 2 x AMD        | 5         | 3.14%   |
| AMD + Nvidia   | 4         | 2.52%   |
| Intel + AMD    | 3         | 1.89%   |
| Other          | 1         | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 139       | 87.42%  |
| Proprietary | 17        | 10.69%  |
| Unknown     | 3         | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 114       | 71.7%   |
| 0.01-0.5   | 22        | 13.84%  |
| 0.51-1.0   | 9         | 5.66%   |
| 1.01-2.0   | 7         | 4.4%    |
| 3.01-4.0   | 5         | 3.14%   |
| 7.01-8.0   | 1         | 0.63%   |
| 8.01-16.0  | 1         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 39        | 22.29%  |
| LG Display              | 28        | 16%     |
| BOE                     | 24        | 13.71%  |
| Chimei Innolux          | 18        | 10.29%  |
| Samsung Electronics     | 16        | 9.14%   |
| Dell                    | 6         | 3.43%   |
| PANDA                   | 5         | 2.86%   |
| Chi Mei Optoelectronics | 5         | 2.86%   |
| Lenovo                  | 4         | 2.29%   |
| Goldstar                | 4         | 2.29%   |
| LG Philips              | 3         | 1.71%   |
| InfoVision              | 3         | 1.71%   |
| Philips                 | 2         | 1.14%   |
| KDC                     | 2         | 1.14%   |
| Apple                   | 2         | 1.14%   |
| Vizio                   | 1         | 0.57%   |
| ViewSonic               | 1         | 0.57%   |
| Toshiba                 | 1         | 0.57%   |
| Sony                    | 1         | 0.57%   |
| Sharp                   | 1         | 0.57%   |
| Sceptre Tech            | 1         | 0.57%   |
| SAC                     | 1         | 0.57%   |
| Panasonic               | 1         | 0.57%   |
| Iiyama                  | 1         | 0.57%   |
| HannStar                | 1         | 0.57%   |
| CSO                     | 1         | 0.57%   |
| CPT                     | 1         | 0.57%   |
| BenQ                    | 1         | 0.57%   |
| Acer                    | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 2         | 1.14%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 1.14%   |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 2         | 1.14%   |
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 1.14%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 1.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 1.14%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 1.14%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 1.14%   |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                       | 1         | 0.57%   |
| ViewSonic XG2703-GS VSCBA32 2560x1440 598x336mm 27.0-inch                | 1         | 0.57%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.57%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch                  | 1         | 0.57%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 1         | 0.57%   |
| Sceptre Tech Sceptre N43 SPT110C 3840x2160 575x323mm 26.0-inch           | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch     | 1         | 0.57%   |
| Samsung Electronics SMC23A550U SAM07F3 1920x1080 510x287mm 23.0-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4A52 1366x768 344x194mm 15.5-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM7048 1366x768 522x293mm 23.6-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM0530 1360x768                         | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                        | 1         | 0.57%   |
| SAC LED MONITOR SACE324 1600x900 477x268mm 21.5-inch                     | 1         | 0.57%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 1         | 0.57%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 1         | 0.57%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch                  | 1         | 0.57%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 1         | 0.57%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 0.57%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch              | 1         | 0.57%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch              | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 69        | 41.32%  |
| 1366x768 (WXGA)    | 50        | 29.94%  |
| 1600x900 (HD+)     | 15        | 8.98%   |
| 1280x800 (WXGA)    | 7         | 4.19%   |
| 3840x2160 (4K)     | 6         | 3.59%   |
| 1440x900 (WXGA+)   | 5         | 2.99%   |
| 1920x1200 (WUXGA)  | 3         | 1.8%    |
| 1024x600           | 2         | 1.2%    |
| 3840x1600          | 1         | 0.6%    |
| 2880x1800          | 1         | 0.6%    |
| 2560x1600          | 1         | 0.6%    |
| 2560x1440 (QHD)    | 1         | 0.6%    |
| 2160x1440          | 1         | 0.6%    |
| 1920x515           | 1         | 0.6%    |
| 1680x1050 (WSXGA+) | 1         | 0.6%    |
| 1366x912           | 1         | 0.6%    |
| 1360x768           | 1         | 0.6%    |
| 1280x1024 (SXGA)   | 1         | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 67        | 38.29%  |
| 14      | 30        | 17.14%  |
| 13      | 26        | 14.86%  |
| 17      | 14        | 8%      |
| 27      | 5         | 2.86%   |
| 23      | 5         | 2.86%   |
| 21      | 4         | 2.29%   |
| 12      | 4         | 2.29%   |
| 11      | 4         | 2.29%   |
| Unknown | 4         | 2.29%   |
| 26      | 2         | 1.14%   |
| 24      | 2         | 1.14%   |
| 10      | 2         | 1.14%   |
| 37      | 1         | 0.57%   |
| 31      | 1         | 0.57%   |
| 30      | 1         | 0.57%   |
| 20      | 1         | 0.57%   |
| 18      | 1         | 0.57%   |
| 16      | 1         | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 113       | 64.94%  |
| 201-300     | 20        | 11.49%  |
| 351-400     | 15        | 8.62%   |
| 501-600     | 13        | 7.47%   |
| 401-500     | 6         | 3.45%   |
| Unknown     | 4         | 2.3%    |
| 601-700     | 2         | 1.15%   |
| 801-900     | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 134       | 84.28%  |
| 16/10   | 19        | 11.95%  |
| 3/2     | 2         | 1.26%   |
| 4/3     | 1         | 0.63%   |
| 3.73    | 1         | 0.63%   |
| 21/9    | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 38.51%  |
| 81-90          | 48        | 27.59%  |
| 121-130        | 10        | 5.75%   |
| 71-80          | 9         | 5.17%   |
| 201-250        | 9         | 5.17%   |
| 301-350        | 6         | 3.45%   |
| 51-60          | 4         | 2.3%    |
| 131-140        | 4         | 2.3%    |
| Unknown        | 4         | 2.3%    |
| 61-70          | 3         | 1.72%   |
| 151-200        | 3         | 1.72%   |
| 351-500        | 2         | 1.15%   |
| 41-50          | 2         | 1.15%   |
| 251-300        | 2         | 1.15%   |
| 91-100         | 1         | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 77        | 44.77%  |
| 101-120       | 55        | 31.98%  |
| 51-100        | 29        | 16.86%  |
| 161-240       | 4         | 2.33%   |
| Unknown       | 4         | 2.33%   |
| More than 240 | 3         | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 134       | 84.28%  |
| 2     | 20        | 12.58%  |
| 0     | 3         | 1.89%   |
| 3     | 2         | 1.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 82        | 34.17%  |
| Intel                             | 82        | 34.17%  |
| Qualcomm Atheros                  | 30        | 12.5%   |
| Broadcom                          | 17        | 7.08%   |
| MediaTek                          | 4         | 1.67%   |
| Sierra Wireless                   | 2         | 0.83%   |
| Samsung Electronics               | 2         | 0.83%   |
| Marvell Technology Group          | 2         | 0.83%   |
| Huawei Technologies               | 2         | 0.83%   |
| Hewlett-Packard                   | 2         | 0.83%   |
| Xiaomi                            | 1         | 0.42%   |
| TP-Link                           | 1         | 0.42%   |
| Ralink Technology                 | 1         | 0.42%   |
| Ralink                            | 1         | 0.42%   |
| Qualcomm Atheros Communications   | 1         | 0.42%   |
| Qualcomm                          | 1         | 0.42%   |
| Microchip Technology              | 1         | 0.42%   |
| LG Electronics                    | 1         | 0.42%   |
| Ericsson Business Mobile Networks | 1         | 0.42%   |
| Dell                              | 1         | 0.42%   |
| D-Link                            | 1         | 0.42%   |
| BUFFALO                           | 1         | 0.42%   |
| Broadcom Limited                  | 1         | 0.42%   |
| Attansic Technology               | 1         | 0.42%   |
| Apple                             | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 15.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 5.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 2.98%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 2.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.65%   |
| Intel Wireless 8260                                               | 8         | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.32%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.99%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.66%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.66%   |
| Intel Wireless 3165                                               | 5         | 1.66%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 1.32%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.32%   |
| Intel Wireless 7260                                               | 4         | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.99%   |
| Intel Wireless 7265                                               | 3         | 0.99%   |
| Intel Wireless 3160                                               | 3         | 0.99%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.99%   |
| Sierra Wireless EM7455                                            | 2         | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.66%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 80        | 47.9%   |
| Realtek Semiconductor           | 35        | 20.96%  |
| Qualcomm Atheros                | 27        | 16.17%  |
| Broadcom                        | 12        | 7.19%   |
| MediaTek                        | 4         | 2.4%    |
| Sierra Wireless                 | 2         | 1.2%    |
| Ralink Technology               | 1         | 0.6%    |
| Ralink                          | 1         | 0.6%    |
| Qualcomm Atheros Communications | 1         | 0.6%    |
| Qualcomm                        | 1         | 0.6%    |
| Dell                            | 1         | 0.6%    |
| D-Link                          | 1         | 0.6%    |
| BUFFALO                         | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 5.29%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 5.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 4.71%   |
| Intel Wireless 8260                                            | 8         | 4.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 4.12%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 3.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 3.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.94%   |
| Intel Wireless 8265 / 8275                                     | 5         | 2.94%   |
| Intel Wireless 3165                                            | 5         | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 2.35%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 2.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.35%   |
| Intel Wireless 7260                                            | 4         | 2.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.35%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 2.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 2.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 1.76%   |
| Intel Wireless 7265                                            | 3         | 1.76%   |
| Intel Wireless 3160                                            | 3         | 1.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 1.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.76%   |
| Sierra Wireless EM7455                                         | 2         | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.18%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 1.18%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.59%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.59%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.59%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 0.59%   |
| Realtek 802.11ac NIC                                           | 1         | 0.59%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 69        | 52.67%  |
| Intel                    | 34        | 25.95%  |
| Qualcomm Atheros         | 7         | 5.34%   |
| Broadcom                 | 6         | 4.58%   |
| Samsung Electronics      | 2         | 1.53%   |
| Marvell Technology Group | 2         | 1.53%   |
| Huawei Technologies      | 2         | 1.53%   |
| Hewlett-Packard          | 2         | 1.53%   |
| Xiaomi                   | 1         | 0.76%   |
| TP-Link                  | 1         | 0.76%   |
| Microchip Technology     | 1         | 0.76%   |
| LG Electronics           | 1         | 0.76%   |
| Broadcom Limited         | 1         | 0.76%   |
| Attansic Technology      | 1         | 0.76%   |
| Apple                    | 1         | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 46        | 35.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 18        | 13.74%  |
| Intel Ethernet Connection I219-LM                                              | 6         | 4.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 4.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 1.53%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.53%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.53%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.53%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 1.53%   |
| Huawei STK-L21                                                                 | 2         | 1.53%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.76%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.76%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.76%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 1         | 0.76%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.76%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.76%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                            | 1         | 0.76%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 0.76%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.76%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.76%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.76%   |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.76%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.76%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.76%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 0.76%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 156       | 55.52%  |
| Ethernet | 124       | 44.13%  |
| Modem    | 1         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 81.82%  |
| Ethernet | 30        | 18.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 114       | 71.7%   |
| 1     | 37        | 23.27%  |
| 0     | 7         | 4.4%    |
| 3     | 1         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 105       | 65.22%  |
| Yes  | 56        | 34.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 47.54%  |
| Realtek Semiconductor           | 16        | 13.11%  |
| Broadcom                        | 9         | 7.38%   |
| Lite-On Technology              | 8         | 6.56%   |
| Foxconn / Hon Hai               | 7         | 5.74%   |
| Qualcomm Atheros Communications | 5         | 4.1%    |
| IMC Networks                    | 5         | 4.1%    |
| Realtek                         | 3         | 2.46%   |
| Hewlett-Packard                 | 2         | 1.64%   |
| Toshiba                         | 1         | 0.82%   |
| Ralink                          | 1         | 0.82%   |
| Foxconn International           | 1         | 0.82%   |
| Dell                            | 1         | 0.82%   |
| Chicony Electronics             | 1         | 0.82%   |
| Cambridge Silicon Radio         | 1         | 0.82%   |
| ASUSTek Computer                | 1         | 0.82%   |
| Apple                           | 1         | 0.82%   |
| Alps Electric                   | 1         | 0.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 27        | 22.13%  |
| Intel AX201 Bluetooth                                                               | 13        | 10.66%  |
| Realtek Bluetooth Radio                                                             | 12        | 9.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 4.92%   |
| Intel AX200 Bluetooth                                                               | 6         | 4.92%   |
| Intel AX210 Bluetooth                                                               | 4         | 3.28%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 3.28%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.46%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.64%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.64%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.64%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.64%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.64%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.64%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.82%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.82%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.82%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 0.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.82%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.82%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.82%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.82%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.82%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.82%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.82%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.82%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.82%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.82%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.82%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.82%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.82%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.82%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 1         | 0.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 123       | 67.58%  |
| AMD                    | 34        | 18.68%  |
| Nvidia                 | 15        | 8.24%   |
| Texas Instruments      | 2         | 1.1%    |
| JMTek                  | 2         | 1.1%    |
| Generalplus Technology | 2         | 1.1%    |
| Tenx Technology        | 1         | 0.55%   |
| MAG Technology         | 1         | 0.55%   |
| C-Media Electronics    | 1         | 0.55%   |
| ASUSTek Computer       | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 8.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 5.41%   |
| AMD FCH Azalia Controller                                                                         | 12        | 5.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 5.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 4.95%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 4.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 3.6%    |
| Intel Broadwell-U Audio Controller                                                                | 8         | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 3.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 3.6%    |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 3.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 2.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 2.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 2.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 2.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.8%    |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.35%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.9%    |
| Nvidia Audio device                                                                               | 2         | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 0.9%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.9%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 0.9%    |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.9%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.9%    |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.9%    |
| AMD High Definition Audio Controller                                                              | 2         | 0.9%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.9%    |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.45%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.45%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.45%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 37        | 27.41%  |
| SK hynix                   | 25        | 18.52%  |
| Unknown                    | 22        | 16.3%   |
| Micron Technology          | 19        | 14.07%  |
| Kingston                   | 9         | 6.67%   |
| Crucial                    | 8         | 5.93%   |
| Unknown (ABCD)             | 5         | 3.7%    |
| Ramaxel Technology         | 2         | 1.48%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.74%   |
| Smart                      | 1         | 0.74%   |
| Qimonda                    | 1         | 0.74%   |
| G.Skill                    | 1         | 0.74%   |
| Foxline                    | 1         | 0.74%   |
| fef5                       | 1         | 0.74%   |
| Essencore                  | 1         | 0.74%   |
| Elpida                     | 1         | 0.74%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s            | 5         | 3.6%    |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                                   | 3         | 2.16%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                  | 3         | 2.16%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                  | 3         | 2.16%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 3         | 2.16%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                       | 3         | 2.16%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                                 | 2         | 1.44%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                                | 2         | 1.44%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                      | 2         | 1.44%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.44%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 1.44%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s                    | 2         | 1.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s                 | 2         | 1.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                       | 2         | 1.44%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s                    | 2         | 1.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s                 | 2         | 1.44%   |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                                  | 2         | 1.44%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                        | 2         | 1.44%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                                 | 1         | 0.72%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                                 | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                                 | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                                 | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3                                          | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                               | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                                 | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                                 | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                                       | 1         | 0.72%   |
| Unknown RAM Module 1536MB SODIMM LPDDR4 2133MT/s                            | 1         | 0.72%   |
| Unknown RAM 202020202020202020202020202020202020 4096MB SODIMM DDR2 800MT/s | 1         | 0.72%   |
| Unknown (7F7F7F7F7F7F6B00) RAM 8D7T3MN8-NATP 2GB SODIMM DDR 667MT/s         | 1         | 0.72%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.72%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                                | 1         | 0.72%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                                | 1         | 0.72%   |
| SK hynix RAM Module 2GB Row Of Chips DDR3 1600MT/s                          | 1         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.72%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.72%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                             | 1         | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 47        | 39.83%  |
| DDR3    | 39        | 33.05%  |
| LPDDR4  | 16        | 13.56%  |
| DDR2    | 8         | 6.78%   |
| LPDDR3  | 3         | 2.54%   |
| Unknown | 2         | 1.69%   |
| SDRAM   | 1         | 0.85%   |
| DDR5    | 1         | 0.85%   |
| DDR     | 1         | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 99        | 82.5%   |
| Row Of Chips | 15        | 12.5%   |
| Chip         | 3         | 2.5%    |
| Unknown      | 2         | 1.67%   |
| DIMM         | 1         | 0.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 45        | 36.29%  |
| 4096  | 40        | 32.26%  |
| 2048  | 21        | 16.94%  |
| 16384 | 9         | 7.26%   |
| 1024  | 5         | 4.03%   |
| 32768 | 3         | 2.42%   |
| 1536  | 1         | 0.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 28        | 22.95%  |
| 3200    | 26        | 21.31%  |
| 2667    | 13        | 10.66%  |
| 2400    | 11        | 9.02%   |
| 2133    | 9         | 7.38%   |
| 667     | 8         | 6.56%   |
| 4267    | 5         | 4.1%    |
| 1334    | 4         | 3.28%   |
| 1333    | 4         | 3.28%   |
| 3266    | 2         | 1.64%   |
| 4800    | 1         | 0.82%   |
| 4266    | 1         | 0.82%   |
| 4199    | 1         | 0.82%   |
| 3733    | 1         | 0.82%   |
| 3600    | 1         | 0.82%   |
| 2134    | 1         | 0.82%   |
| 1776    | 1         | 0.82%   |
| 1067    | 1         | 0.82%   |
| 1066    | 1         | 0.82%   |
| 800     | 1         | 0.82%   |
| 533     | 1         | 0.82%   |
| Unknown | 1         | 0.82%   |

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
| Chicony Electronics                    | 42        | 28%     |
| Quanta                                 | 14        | 9.33%   |
| Realtek Semiconductor                  | 12        | 8%      |
| Suyin                                  | 10        | 6.67%   |
| Microdia                               | 10        | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 6.67%   |
| IMC Networks                           | 9         | 6%      |
| Sunplus Innovation Technology          | 7         | 4.67%   |
| Acer                                   | 6         | 4%      |
| Luxvisions Innotech Limited            | 3         | 2%      |
| Lite-On Technology                     | 3         | 2%      |
| Alcor Micro                            | 3         | 2%      |
| Z-Star Microelectronics                | 2         | 1.33%   |
| USB Camera                             | 2         | 1.33%   |
| Silicon Motion                         | 2         | 1.33%   |
| Ricoh                                  | 2         | 1.33%   |
| Logitech                               | 2         | 1.33%   |
| Xiongmai                               | 1         | 0.67%   |
| USB Camera CS                          | 1         | 0.67%   |
| Syntek                                 | 1         | 0.67%   |
| SunplusIT                              | 1         | 0.67%   |
| Sonix Technology                       | 1         | 0.67%   |
| Primax Electronics                     | 1         | 0.67%   |
| OYT Tech                               | 1         | 0.67%   |
| OmniVision Technologies                | 1         | 0.67%   |
| MacroSilicon                           | 1         | 0.67%   |
| Lenovo                                 | 1         | 0.67%   |
| Importek                               | 1         | 0.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 14        | 9.33%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.67%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 2%      |
| Realtek USB Camera                                  | 3         | 2%      |
| Quanta HD User Facing                               | 3         | 2%      |
| Microdia Integrated_Webcam_HD                       | 3         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 2%      |
| USB Camera USB Camera                               | 2         | 1.33%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 1.33%   |
| Sunplus Integrated_Webcam_FHD                       | 2         | 1.33%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.33%   |
| Realtek HP Truevision HD                            | 2         | 1.33%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 1.33%   |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 1.33%   |
| Quanta HP Webcam                                    | 2         | 1.33%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.33%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 1.33%   |
| Microdia Lenovo EasyCamera                          | 2         | 1.33%   |
| Logitech BRIO Ultra HD Webcam                       | 2         | 1.33%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.33%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 1.33%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 1.33%   |
| Chicony HP Truevision HD                            | 2         | 1.33%   |
| Chicony HD WebCam                                   | 2         | 1.33%   |
| Chicony EasyCamera                                  | 2         | 1.33%   |
| Alcor Micro USB 2.0 Camera                          | 2         | 1.33%   |
| Acer Integrated Camera                              | 2         | 1.33%   |
| Z-Star Vimicro USB Camera (Altair)                  | 1         | 0.67%   |
| Z-Star Traveler TV 6500 SF Dia-scanner              | 1         | 0.67%   |
| Xiongmai web camera                                 | 1         | 0.67%   |
| USB Camera CS USB Camera CS                         | 1         | 0.67%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.67%   |
| Suyin Webcam-101                                    | 1         | 0.67%   |
| Suyin VGA Webcam                                    | 1         | 0.67%   |
| Suyin UVC HD Webcam                                 | 1         | 0.67%   |
| Suyin UVC 0.3M Webcam                               | 1         | 0.67%   |
| Suyin HD WebCam                                     | 1         | 0.67%   |
| Suyin Asus Integrated Webcam [CN031B]               | 1         | 0.67%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 0.67%   |
| Suyin 1.3M Front                                    | 1         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 43.48%  |
| Upek                       | 4         | 17.39%  |
| Synaptics                  | 3         | 13.04%  |
| Shenzhen Goodix Technology | 3         | 13.04%  |
| STMicroelectronics         | 2         | 8.7%    |
| Elan Microelectronics      | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 4         | 17.39%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 13.04%  |
| Shenzhen Goodix  Fingerprint Device                    | 3         | 13.04%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 8.7%    |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 8.7%    |
| Validity Sensors Synaptics WBDI                        | 2         | 8.7%    |
| STMicroelectronics Fingerprint Reader                  | 2         | 8.7%    |
| Upek TCS5B Fingerprint sensor                          | 1         | 4.35%   |
| Synaptics  WBDI                                        | 1         | 4.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 4.35%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 42.86%  |
| Alcor Micro | 5         | 35.71%  |
| Lenovo      | 2         | 14.29%  |
| O2 Micro    | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 5         | 35.71%  |
| Lenovo Integrated Smart Card Reader            | 2         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 14.29%  |
| Broadcom 5880                                  | 2         | 14.29%  |
| Broadcom 58200                                 | 2         | 14.29%  |
| O2 Micro Oz776 SmartCard Reader                | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 103       | 64.38%  |
| 1     | 47        | 29.38%  |
| 2     | 10        | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 22        | 34.38%  |
| Chipcard              | 14        | 21.88%  |
| Net/wireless          | 7         | 10.94%  |
| Graphics card         | 7         | 10.94%  |
| Camera                | 5         | 7.81%   |
| Network               | 3         | 4.69%   |
| Bluetooth             | 3         | 4.69%   |
| Card reader           | 2         | 3.13%   |
| Multimedia controller | 1         | 1.56%   |

