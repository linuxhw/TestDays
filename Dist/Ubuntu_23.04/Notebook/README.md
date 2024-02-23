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

Total: 1271

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HUAWEI        | KLVD-WXX9                   | [42e8e68344](https://linux-hardware.org/?probe=42e8e68344) | Jan 26, 2024 |
| Dell          | Inspiron 5521               | [18fc8668de](https://linux-hardware.org/?probe=18fc8668de) | Jan 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [606adf78f9](https://linux-hardware.org/?probe=606adf78f9) | Jan 24, 2024 |
| HP            | ProBook 455 G1              | [224d863e1d](https://linux-hardware.org/?probe=224d863e1d) | Jan 23, 2024 |
| Google        | Woomax                      | [8b76a06477](https://linux-hardware.org/?probe=8b76a06477) | Jan 23, 2024 |
| Lenovo        | ThinkPad T420 4238AC6       | [8c171e6ffa](https://linux-hardware.org/?probe=8c171e6ffa) | Jan 22, 2024 |
| Packard Be... | EasyNote TJ65               | [bcf20a0a9c](https://linux-hardware.org/?probe=bcf20a0a9c) | Jan 16, 2024 |
| Dell          | Inspiron 7570               | [bdea5ae4df](https://linux-hardware.org/?probe=bdea5ae4df) | Jan 16, 2024 |
| Lenovo        | ThinkPad T460p 20FXS1G70... | [519458acdc](https://linux-hardware.org/?probe=519458acdc) | Jan 15, 2024 |
| Apple         | MacBookPro9,2               | [696f5dd9e3](https://linux-hardware.org/?probe=696f5dd9e3) | Jan 12, 2024 |
| HP            | EliteBook 840 G7 Noteboo... | [9b3ca5c984](https://linux-hardware.org/?probe=9b3ca5c984) | Jan 11, 2024 |
| ASUSTek       | X542UA                      | [028b7c4d83](https://linux-hardware.org/?probe=028b7c4d83) | Jan 08, 2024 |
| HP            | ProBook 4530s               | [0fe11a7b3d](https://linux-hardware.org/?probe=0fe11a7b3d) | Jan 05, 2024 |
| HP            | EliteBook 840 G6            | [0e3e8e1d4a](https://linux-hardware.org/?probe=0e3e8e1d4a) | Jan 05, 2024 |
| Toshiba       | IS 1413G                    | [5e4cd95800](https://linux-hardware.org/?probe=5e4cd95800) | Jan 05, 2024 |
| ASUSTek       | X542UA                      | [5d7b076a1c](https://linux-hardware.org/?probe=5d7b076a1c) | Jan 05, 2024 |
| Dell          | Inspiron 5749               | [de1b1d1851](https://linux-hardware.org/?probe=de1b1d1851) | Jan 04, 2024 |
| Timi          | Redmi Book Pro 15 2022      | [6a25b4f0dc](https://linux-hardware.org/?probe=6a25b4f0dc) | Jan 03, 2024 |
| Positivo B... | VJFE42F11X-B2891H           | [47c3c6c806](https://linux-hardware.org/?probe=47c3c6c806) | Jan 03, 2024 |
| Dell          | Inspiron 5521               | [31f27ced42](https://linux-hardware.org/?probe=31f27ced42) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ec8f742a7f](https://linux-hardware.org/?probe=ec8f742a7f) | Dec 31, 2023 |
| Apple         | MacBookPro9,2               | [7f113211a4](https://linux-hardware.org/?probe=7f113211a4) | Dec 31, 2023 |
| Toshiba       | Satellite P70-B             | [2a5acedd16](https://linux-hardware.org/?probe=2a5acedd16) | Dec 29, 2023 |
| Dell          | Latitude E7450              | [50b3989c19](https://linux-hardware.org/?probe=50b3989c19) | Dec 28, 2023 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [e0bfd9face](https://linux-hardware.org/?probe=e0bfd9face) | Dec 28, 2023 |
| HP            | ProBook 455 G1              | [d132700b11](https://linux-hardware.org/?probe=d132700b11) | Dec 28, 2023 |
| Dell          | Latitude 5420               | [07b64f5dfe](https://linux-hardware.org/?probe=07b64f5dfe) | Dec 27, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [a82bef9300](https://linux-hardware.org/?probe=a82bef9300) | Dec 25, 2023 |
| Dell          | Inspiron 1564               | [a1945990cc](https://linux-hardware.org/?probe=a1945990cc) | Dec 24, 2023 |
| Dell          | Inspiron 1564               | [e02428db4a](https://linux-hardware.org/?probe=e02428db4a) | Dec 24, 2023 |
| Apple         | MacBookPro9,1               | [a70e7da743](https://linux-hardware.org/?probe=a70e7da743) | Dec 23, 2023 |
| ASUSTek       | X550LD                      | [bc65f1d620](https://linux-hardware.org/?probe=bc65f1d620) | Dec 21, 2023 |
| Toshiba       | Satellite C55-A             | [6c0f2ad0c9](https://linux-hardware.org/?probe=6c0f2ad0c9) | Dec 18, 2023 |
| Toshiba       | Satellite C55-A             | [0ae780878c](https://linux-hardware.org/?probe=0ae780878c) | Dec 18, 2023 |
| Toshiba       | IS 1413G                    | [458a8fb3f1](https://linux-hardware.org/?probe=458a8fb3f1) | Dec 18, 2023 |
| HP            | ENVY Laptop 17-ch0xxx       | [43602a664e](https://linux-hardware.org/?probe=43602a664e) | Dec 17, 2023 |
| Toshiba       | IS 1413G                    | [dde306e444](https://linux-hardware.org/?probe=dde306e444) | Dec 17, 2023 |
| ASUSTek       | X456UB                      | [5a4a0662e1](https://linux-hardware.org/?probe=5a4a0662e1) | Dec 17, 2023 |
| Apple         | MacBookPro9,2               | [4c8c4e1c68](https://linux-hardware.org/?probe=4c8c4e1c68) | Dec 17, 2023 |
| ASUSTek       | X550LD                      | [f46b47b272](https://linux-hardware.org/?probe=f46b47b272) | Dec 16, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [dc5e6d8ad5](https://linux-hardware.org/?probe=dc5e6d8ad5) | Dec 16, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [8d9963d61d](https://linux-hardware.org/?probe=8d9963d61d) | Dec 11, 2023 |
| Dell          | Latitude 5400               | [6e887e1547](https://linux-hardware.org/?probe=6e887e1547) | Dec 11, 2023 |
| MSI           | Katana 17 B13VGK            | [e91a23fa88](https://linux-hardware.org/?probe=e91a23fa88) | Dec 08, 2023 |
| Dell          | Latitude E7470              | [81a17083f6](https://linux-hardware.org/?probe=81a17083f6) | Dec 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e0f14fb199](https://linux-hardware.org/?probe=e0f14fb199) | Dec 07, 2023 |
| Google        | Chell                       | [b19b6452e3](https://linux-hardware.org/?probe=b19b6452e3) | Dec 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [21c49766ca](https://linux-hardware.org/?probe=21c49766ca) | Dec 06, 2023 |
| HP            | 250 G7 Notebook PC          | [bed4fa69c4](https://linux-hardware.org/?probe=bed4fa69c4) | Dec 06, 2023 |
| HP            | 250 G7 Notebook PC          | [52cdd2c7b2](https://linux-hardware.org/?probe=52cdd2c7b2) | Dec 06, 2023 |
| LG Electro... | 16Z90R-G.AA76G              | [5ac1d1605a](https://linux-hardware.org/?probe=5ac1d1605a) | Dec 05, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9560de18b6](https://linux-hardware.org/?probe=9560de18b6) | Dec 01, 2023 |
| Apple         | MacBookPro9,2               | [cfeac0b40f](https://linux-hardware.org/?probe=cfeac0b40f) | Nov 30, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [e9f95fd344](https://linux-hardware.org/?probe=e9f95fd344) | Nov 29, 2023 |
| Lenovo        | ThinkPad X201 3323RKG       | [71242a9bc0](https://linux-hardware.org/?probe=71242a9bc0) | Nov 26, 2023 |
| HP            | ENVY 15                     | [66a7391daf](https://linux-hardware.org/?probe=66a7391daf) | Nov 25, 2023 |
| Acer          | TravelMate P215-51          | [fd03901ed8](https://linux-hardware.org/?probe=fd03901ed8) | Nov 25, 2023 |
| FUTOPIA GL... | ULTIMUS PRO                 | [96b6b163d8](https://linux-hardware.org/?probe=96b6b163d8) | Nov 24, 2023 |
| HP            | 340S G7 Notebook PC         | [5f8d3105b5](https://linux-hardware.org/?probe=5f8d3105b5) | Nov 22, 2023 |
| Dell          | Latitude 5400               | [a2994234ca](https://linux-hardware.org/?probe=a2994234ca) | Nov 21, 2023 |
| Timi          | RedmiBook 15                | [00a6933cf0](https://linux-hardware.org/?probe=00a6933cf0) | Nov 20, 2023 |
| Dell          | Latitude E5500              | [657426e5e9](https://linux-hardware.org/?probe=657426e5e9) | Nov 20, 2023 |
| ASUSTek       | X540NA                      | [d0f4cc3a98](https://linux-hardware.org/?probe=d0f4cc3a98) | Nov 19, 2023 |
| HP            | Pavilion dv6                | [bab0d77625](https://linux-hardware.org/?probe=bab0d77625) | Nov 19, 2023 |
| Notebook      | W54_55SU1,SUW               | [c11c5d127d](https://linux-hardware.org/?probe=c11c5d127d) | Nov 18, 2023 |
| Notebook      | W54_55SU1,SUW               | [12a0c7cc59](https://linux-hardware.org/?probe=12a0c7cc59) | Nov 18, 2023 |
| HP            | 255 G7 Notebook PC          | [9e5738b77f](https://linux-hardware.org/?probe=9e5738b77f) | Nov 18, 2023 |
| HP            | ProBook 430 G7              | [093edd002d](https://linux-hardware.org/?probe=093edd002d) | Nov 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [70ca4894ab](https://linux-hardware.org/?probe=70ca4894ab) | Nov 18, 2023 |
| Lenovo        | ThinkPad T420 4180ED3       | [f963bd64fa](https://linux-hardware.org/?probe=f963bd64fa) | Nov 16, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [ab7968d6da](https://linux-hardware.org/?probe=ab7968d6da) | Nov 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [95f01d6e47](https://linux-hardware.org/?probe=95f01d6e47) | Nov 15, 2023 |
| HP            | EliteBook 840 G6            | [d702c8d829](https://linux-hardware.org/?probe=d702c8d829) | Nov 15, 2023 |
| HP            | ENVY dv6                    | [f86a52da6d](https://linux-hardware.org/?probe=f86a52da6d) | Nov 14, 2023 |
| Dell          | Latitude E5500              | [f6a14cca8f](https://linux-hardware.org/?probe=f6a14cca8f) | Nov 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [46cfd3f6bf](https://linux-hardware.org/?probe=46cfd3f6bf) | Nov 13, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [46e69016d1](https://linux-hardware.org/?probe=46e69016d1) | Nov 11, 2023 |
| HP            | Pavilion g4                 | [8e86232d90](https://linux-hardware.org/?probe=8e86232d90) | Nov 11, 2023 |
| HP            | EliteBook 840 G6            | [33e3267f6a](https://linux-hardware.org/?probe=33e3267f6a) | Nov 10, 2023 |
| Dell          | Latitude 13                 | [4999e3eba9](https://linux-hardware.org/?probe=4999e3eba9) | Nov 09, 2023 |
| Dell          | Latitude 13                 | [acb0bd4f9d](https://linux-hardware.org/?probe=acb0bd4f9d) | Nov 09, 2023 |
| Lenovo        | Z50-75 80EC                 | [c98cdea69b](https://linux-hardware.org/?probe=c98cdea69b) | Nov 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bcd7a71a14](https://linux-hardware.org/?probe=bcd7a71a14) | Nov 06, 2023 |
| HP            | Pavilion 17                 | [50a9cf65b3](https://linux-hardware.org/?probe=50a9cf65b3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T580 20LAS62M07    | [56d9dc4a36](https://linux-hardware.org/?probe=56d9dc4a36) | Nov 05, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [257e40f6bd](https://linux-hardware.org/?probe=257e40f6bd) | Nov 05, 2023 |
| Acer          | Aspire E1-571G              | [fac63c4d5c](https://linux-hardware.org/?probe=fac63c4d5c) | Nov 05, 2023 |
| Sony          | SVE15137CGW                 | [5d2a4746af](https://linux-hardware.org/?probe=5d2a4746af) | Nov 04, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [3d8056e30e](https://linux-hardware.org/?probe=3d8056e30e) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d0f3cf43b7](https://linux-hardware.org/?probe=d0f3cf43b7) | Nov 04, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [546178d07d](https://linux-hardware.org/?probe=546178d07d) | Nov 04, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [abe3da8a30](https://linux-hardware.org/?probe=abe3da8a30) | Nov 03, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7ccaf83d7](https://linux-hardware.org/?probe=e7ccaf83d7) | Nov 03, 2023 |
| Dell          | Inspiron 16 5625            | [157f3bd86a](https://linux-hardware.org/?probe=157f3bd86a) | Nov 03, 2023 |
| Dell          | Vostro 3525                 | [48103e7e91](https://linux-hardware.org/?probe=48103e7e91) | Nov 03, 2023 |
| Dell          | Vostro 5590                 | [aa355fcc89](https://linux-hardware.org/?probe=aa355fcc89) | Nov 02, 2023 |
| Chuwi         | CoreBook Pro                | [ac0f4a1ea9](https://linux-hardware.org/?probe=ac0f4a1ea9) | Nov 01, 2023 |
| MSI           | Titan GT77HX 13VI           | [1fb8b0ccb3](https://linux-hardware.org/?probe=1fb8b0ccb3) | Nov 01, 2023 |
| HUAWEI        | MACH-WX9                    | [f557533925](https://linux-hardware.org/?probe=f557533925) | Nov 01, 2023 |
| HUAWEI        | MACH-WX9                    | [50880de513](https://linux-hardware.org/?probe=50880de513) | Nov 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | [18398fe53c](https://linux-hardware.org/?probe=18398fe53c) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [32d642cc3b](https://linux-hardware.org/?probe=32d642cc3b) | Oct 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [309695dc7e](https://linux-hardware.org/?probe=309695dc7e) | Oct 30, 2023 |
| HP            | ZBook Studio G3             | [173639f83c](https://linux-hardware.org/?probe=173639f83c) | Oct 30, 2023 |
| Dell          | Latitude 5400               | [e7f91d1c69](https://linux-hardware.org/?probe=e7f91d1c69) | Oct 30, 2023 |
| HP            | ProBook 6570b               | [5b574791fa](https://linux-hardware.org/?probe=5b574791fa) | Oct 30, 2023 |
| Lenovo        | ThinkPad T460s 20F90039U... | [8df2c91111](https://linux-hardware.org/?probe=8df2c91111) | Oct 29, 2023 |
| Lenovo        | ThinkPad T590 20N5S56P00    | [c410852108](https://linux-hardware.org/?probe=c410852108) | Oct 29, 2023 |
| Dell          | Latitude E5450              | [64e3601d4c](https://linux-hardware.org/?probe=64e3601d4c) | Oct 29, 2023 |
| Lenovo        | ThinkPad T450s 20BWS58K0... | [11b2f76301](https://linux-hardware.org/?probe=11b2f76301) | Oct 29, 2023 |
| Dell          | Latitude E5450              | [aebf2cd9fb](https://linux-hardware.org/?probe=aebf2cd9fb) | Oct 29, 2023 |
| HP            | ZBook Studio G3             | [9659254017](https://linux-hardware.org/?probe=9659254017) | Oct 27, 2023 |
| HP            | Laptop 15s-fq5xxx           | [773814f03f](https://linux-hardware.org/?probe=773814f03f) | Oct 27, 2023 |
| Dell          | Inspiron MM061              | [d4b3f62ecb](https://linux-hardware.org/?probe=d4b3f62ecb) | Oct 27, 2023 |
| HUAWEI        | NBM-WXX9                    | [9444fd16a7](https://linux-hardware.org/?probe=9444fd16a7) | Oct 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [b6925d5638](https://linux-hardware.org/?probe=b6925d5638) | Oct 26, 2023 |
| ASUSTek       | Zenbook UX3402ZA            | [f321493adb](https://linux-hardware.org/?probe=f321493adb) | Oct 25, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [3ce0f8310d](https://linux-hardware.org/?probe=3ce0f8310d) | Oct 25, 2023 |
| Dell          | Latitude E7270              | [07d72d2a9d](https://linux-hardware.org/?probe=07d72d2a9d) | Oct 24, 2023 |
| Lenovo        | ThinkPad T480 20L6S5FF0S    | [4a4fe99b2d](https://linux-hardware.org/?probe=4a4fe99b2d) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | [f45a5143fc](https://linux-hardware.org/?probe=f45a5143fc) | Oct 23, 2023 |
| HP            | Laptop 15-da2xxx            | [6f746b3af3](https://linux-hardware.org/?probe=6f746b3af3) | Oct 23, 2023 |
| Intel Clie... | LAPAC71H                    | [257d890bfb](https://linux-hardware.org/?probe=257d890bfb) | Oct 23, 2023 |
| Fujitsu       | LIFEBOOK E754               | [17e7fcc400](https://linux-hardware.org/?probe=17e7fcc400) | Oct 23, 2023 |
| HP            | Pavilion 17                 | [7e822923ca](https://linux-hardware.org/?probe=7e822923ca) | Oct 23, 2023 |
| Dell          | Inspiron 3443               | [bbe3093cb4](https://linux-hardware.org/?probe=bbe3093cb4) | Oct 22, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 Ua 82F... | [735bb309a1](https://linux-hardware.org/?probe=735bb309a1) | Oct 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [9dae3fabcb](https://linux-hardware.org/?probe=9dae3fabcb) | Oct 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [38fcbd8bc7](https://linux-hardware.org/?probe=38fcbd8bc7) | Oct 21, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [8ceed23497](https://linux-hardware.org/?probe=8ceed23497) | Oct 21, 2023 |
| Dell          | Latitude 7420               | [33e4aebc37](https://linux-hardware.org/?probe=33e4aebc37) | Oct 21, 2023 |
| ASUSTek       | X540LJ                      | [2aea2077db](https://linux-hardware.org/?probe=2aea2077db) | Oct 20, 2023 |
| Dell          | Vostro 3400                 | [1b518a8409](https://linux-hardware.org/?probe=1b518a8409) | Oct 20, 2023 |
| Fujitsu       | LIFEBOOK A555               | [73592fa9fb](https://linux-hardware.org/?probe=73592fa9fb) | Oct 20, 2023 |
| HP            | Laptop 15-bs0xx             | [e07bf20a8a](https://linux-hardware.org/?probe=e07bf20a8a) | Oct 20, 2023 |
| HUAWEI        | KLVL-WXX9                   | [ca05cc8c35](https://linux-hardware.org/?probe=ca05cc8c35) | Oct 19, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [0815767d1d](https://linux-hardware.org/?probe=0815767d1d) | Oct 18, 2023 |
| HP            | EliteBook 840 G5            | [728b29b59d](https://linux-hardware.org/?probe=728b29b59d) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [417e10e47c](https://linux-hardware.org/?probe=417e10e47c) | Oct 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [686e5c87a9](https://linux-hardware.org/?probe=686e5c87a9) | Oct 18, 2023 |
| Dell          | XPS 15 9530                 | [96f3c530df](https://linux-hardware.org/?probe=96f3c530df) | Oct 17, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [3bdd0db02e](https://linux-hardware.org/?probe=3bdd0db02e) | Oct 17, 2023 |
| Google        | Bobba                       | [f8cdd51f65](https://linux-hardware.org/?probe=f8cdd51f65) | Oct 17, 2023 |
| Lenovo        | ThinkPad T590 20N5S56P00    | [913c616ff6](https://linux-hardware.org/?probe=913c616ff6) | Oct 17, 2023 |
| Gigabyte      | AORUS 15G XB                | [9e4c6d48d4](https://linux-hardware.org/?probe=9e4c6d48d4) | Oct 16, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [cb6f45e005](https://linux-hardware.org/?probe=cb6f45e005) | Oct 16, 2023 |
| Lenovo        | G50-80 80E5                 | [3120810bcd](https://linux-hardware.org/?probe=3120810bcd) | Oct 15, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [079342de2b](https://linux-hardware.org/?probe=079342de2b) | Oct 15, 2023 |
| Dell          | XPS 15 9530                 | [6c14bb7f6c](https://linux-hardware.org/?probe=6c14bb7f6c) | Oct 15, 2023 |
| Dell          | Inspiron 5759               | [cfc646c366](https://linux-hardware.org/?probe=cfc646c366) | Oct 15, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [d83bb1e709](https://linux-hardware.org/?probe=d83bb1e709) | Oct 14, 2023 |
| Dell          | Inspiron 3521               | [a4ed11bb84](https://linux-hardware.org/?probe=a4ed11bb84) | Oct 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [5b0b094b32](https://linux-hardware.org/?probe=5b0b094b32) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | [ca22dfa5cd](https://linux-hardware.org/?probe=ca22dfa5cd) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | [b795b184d0](https://linux-hardware.org/?probe=b795b184d0) | Oct 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [584433cc95](https://linux-hardware.org/?probe=584433cc95) | Oct 14, 2023 |
| Acer          | Aspire 7750G                | [d634013b16](https://linux-hardware.org/?probe=d634013b16) | Oct 13, 2023 |
| HP            | ProBook 450 G3              | [53c0055ced](https://linux-hardware.org/?probe=53c0055ced) | Oct 13, 2023 |
| Lenovo        | 15ARE05 81W4                | [c0066cda83](https://linux-hardware.org/?probe=c0066cda83) | Oct 13, 2023 |
| Panasonic     | CF-C1AD06GDE                | [473265139b](https://linux-hardware.org/?probe=473265139b) | Oct 13, 2023 |
| ASUSTek       | UX430UAR                    | [e66e176aac](https://linux-hardware.org/?probe=e66e176aac) | Oct 13, 2023 |
| Acer          | Aspire E5-575               | [ab55bb1001](https://linux-hardware.org/?probe=ab55bb1001) | Oct 12, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [7901d1df27](https://linux-hardware.org/?probe=7901d1df27) | Oct 12, 2023 |
| HP            | 250 G6 Notebook PC          | [1e08b73cc3](https://linux-hardware.org/?probe=1e08b73cc3) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [8368fe3d29](https://linux-hardware.org/?probe=8368fe3d29) | Oct 12, 2023 |
| Acer          | Swift SF315-41              | [804f28fe5b](https://linux-hardware.org/?probe=804f28fe5b) | Oct 12, 2023 |
| Dell          | XPS 15 9550                 | [4bb651a7a6](https://linux-hardware.org/?probe=4bb651a7a6) | Oct 11, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [c83831e304](https://linux-hardware.org/?probe=c83831e304) | Oct 11, 2023 |
| Dell          | XPS 15 9550                 | [52bbb0243a](https://linux-hardware.org/?probe=52bbb0243a) | Oct 11, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [cca48ceee9](https://linux-hardware.org/?probe=cca48ceee9) | Oct 11, 2023 |
| HP            | Pavilion dv6                | [cc8161a063](https://linux-hardware.org/?probe=cc8161a063) | Oct 11, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [22df79ec5d](https://linux-hardware.org/?probe=22df79ec5d) | Oct 11, 2023 |
| VALE          | Notebook Classic C140       | [b31403a384](https://linux-hardware.org/?probe=b31403a384) | Oct 11, 2023 |
| HP            | ZBook Studio G3             | [2ed8ec821a](https://linux-hardware.org/?probe=2ed8ec821a) | Oct 10, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [5b710d03c5](https://linux-hardware.org/?probe=5b710d03c5) | Oct 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [d6b0808093](https://linux-hardware.org/?probe=d6b0808093) | Oct 09, 2023 |
| HP            | EliteBook 840 G3            | [29af84698a](https://linux-hardware.org/?probe=29af84698a) | Oct 09, 2023 |
| Apple         | MacBookPro11,5              | [98784d1e51](https://linux-hardware.org/?probe=98784d1e51) | Oct 08, 2023 |
| HP            | EliteBook 745 G4            | [8a9290f8a1](https://linux-hardware.org/?probe=8a9290f8a1) | Oct 08, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [69383bf7da](https://linux-hardware.org/?probe=69383bf7da) | Oct 08, 2023 |
| Apple         | MacBookPro11,1              | [dae43772d4](https://linux-hardware.org/?probe=dae43772d4) | Oct 08, 2023 |
| PC Special... | P65_P67RGRERA               | [c2779bc01c](https://linux-hardware.org/?probe=c2779bc01c) | Oct 08, 2023 |
| Acer          | Swift SF514-56T             | [0d2d2cf2ae](https://linux-hardware.org/?probe=0d2d2cf2ae) | Oct 08, 2023 |
| Samsung       | 550P5C/550P7C               | [a95183052c](https://linux-hardware.org/?probe=a95183052c) | Oct 08, 2023 |
| Lenovo        | ThinkPad T420s 4171CTO      | [334da57291](https://linux-hardware.org/?probe=334da57291) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | [1a179deb84](https://linux-hardware.org/?probe=1a179deb84) | Oct 08, 2023 |
| HP            | 14                          | [3d65da2b45](https://linux-hardware.org/?probe=3d65da2b45) | Oct 08, 2023 |
| Acer          | Aspire E5-575G              | [3d7751b41e](https://linux-hardware.org/?probe=3d7751b41e) | Oct 08, 2023 |
| Acer          | Swift SF514-56T             | [9f94f8934f](https://linux-hardware.org/?probe=9f94f8934f) | Oct 07, 2023 |
| HP            | ENVY 15                     | [082502c7d2](https://linux-hardware.org/?probe=082502c7d2) | Oct 07, 2023 |
| Acer          | Swift SF313-52G             | [754ae78e39](https://linux-hardware.org/?probe=754ae78e39) | Oct 07, 2023 |
| HUAWEI        | KPL-W0X                     | [0a4d13a8f8](https://linux-hardware.org/?probe=0a4d13a8f8) | Oct 06, 2023 |
| Lenovo        | ThinkPad T460 20FN003HUK    | [fd35988069](https://linux-hardware.org/?probe=fd35988069) | Oct 06, 2023 |
| Apple         | MacBookPro9,2               | [21d197e617](https://linux-hardware.org/?probe=21d197e617) | Oct 05, 2023 |
| Dell          | Inspiron 7577               | [ddadccf492](https://linux-hardware.org/?probe=ddadccf492) | Oct 05, 2023 |
| Dell          | Latitude 3420               | [c5a2d75e6c](https://linux-hardware.org/?probe=c5a2d75e6c) | Oct 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [3b55566de3](https://linux-hardware.org/?probe=3b55566de3) | Oct 05, 2023 |
| Dell          | G5 5590                     | [25826e46a6](https://linux-hardware.org/?probe=25826e46a6) | Oct 05, 2023 |
| ASUSTek       | S550CB                      | [9dc3e0f9f9](https://linux-hardware.org/?probe=9dc3e0f9f9) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [bdfa072267](https://linux-hardware.org/?probe=bdfa072267) | Oct 04, 2023 |
| Google        | Fleex                       | [534bbe966a](https://linux-hardware.org/?probe=534bbe966a) | Oct 04, 2023 |
| HP            | EliteBook 850 G1            | [49b19b9f02](https://linux-hardware.org/?probe=49b19b9f02) | Oct 03, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [eebbbc30b8](https://linux-hardware.org/?probe=eebbbc30b8) | Oct 03, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [f332024d38](https://linux-hardware.org/?probe=f332024d38) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [98961e6b78](https://linux-hardware.org/?probe=98961e6b78) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [332fe81da5](https://linux-hardware.org/?probe=332fe81da5) | Oct 03, 2023 |
| HUAWEI        | KLVD-WXX9                   | [b4dc684d6a](https://linux-hardware.org/?probe=b4dc684d6a) | Oct 03, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | [ff7dc27288](https://linux-hardware.org/?probe=ff7dc27288) | Oct 03, 2023 |
| ASUSTek       | X555LJ                      | [251b560f75](https://linux-hardware.org/?probe=251b560f75) | Oct 03, 2023 |
| Dell          | Inspiron 3543               | [45ec0b8337](https://linux-hardware.org/?probe=45ec0b8337) | Oct 03, 2023 |
| Dell          | Inspiron 3543               | [27eac828a3](https://linux-hardware.org/?probe=27eac828a3) | Oct 03, 2023 |
| HP            | EliteBook 840 G5            | [880b4780ee](https://linux-hardware.org/?probe=880b4780ee) | Oct 03, 2023 |
| HP            | Laptop 15-da2xxx            | [1959705750](https://linux-hardware.org/?probe=1959705750) | Oct 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [0df81159a2](https://linux-hardware.org/?probe=0df81159a2) | Oct 03, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | [d4fcdc44c7](https://linux-hardware.org/?probe=d4fcdc44c7) | Oct 03, 2023 |
| Toshiba       | Satellite C55-C             | [dff87c66a9](https://linux-hardware.org/?probe=dff87c66a9) | Oct 03, 2023 |
| Toshiba       | Satellite C55-C             | [9d6298eb43](https://linux-hardware.org/?probe=9d6298eb43) | Oct 03, 2023 |
| Dell          | Latitude E6410              | [4e19cdbfe7](https://linux-hardware.org/?probe=4e19cdbfe7) | Oct 02, 2023 |
| Dell          | Latitude 5580               | [cf79594d59](https://linux-hardware.org/?probe=cf79594d59) | Oct 02, 2023 |
| Dell          | Latitude 5580               | [9cb7ac852c](https://linux-hardware.org/?probe=9cb7ac852c) | Oct 02, 2023 |
| Dell          | Latitude E6410              | [76cbbaf618](https://linux-hardware.org/?probe=76cbbaf618) | Oct 02, 2023 |
| Acer          | Aspire 7745G                | [e261210eb7](https://linux-hardware.org/?probe=e261210eb7) | Oct 02, 2023 |
| ASUSTek       | G53SX                       | [21e6d88bd9](https://linux-hardware.org/?probe=21e6d88bd9) | Oct 02, 2023 |
| Dell          | Precision 5530              | [3df6ff5560](https://linux-hardware.org/?probe=3df6ff5560) | Oct 02, 2023 |
| Acer          | Aspire 7745G                | [4e0f7a8051](https://linux-hardware.org/?probe=4e0f7a8051) | Oct 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [be49d6acd9](https://linux-hardware.org/?probe=be49d6acd9) | Oct 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | [a566eb0467](https://linux-hardware.org/?probe=a566eb0467) | Oct 01, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [8cb6a92a75](https://linux-hardware.org/?probe=8cb6a92a75) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | [e26d66c131](https://linux-hardware.org/?probe=e26d66c131) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | [21f405ccbe](https://linux-hardware.org/?probe=21f405ccbe) | Oct 01, 2023 |
| ASUSTek       | G73Jh                       | [0b9b84be03](https://linux-hardware.org/?probe=0b9b84be03) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | [ec90ed2076](https://linux-hardware.org/?probe=ec90ed2076) | Oct 01, 2023 |
| HUAWEI        | HLYL-WXX9                   | [d39169bf21](https://linux-hardware.org/?probe=d39169bf21) | Sep 30, 2023 |
| Apple         | MacBookPro12,1              | [b3617a1e58](https://linux-hardware.org/?probe=b3617a1e58) | Sep 30, 2023 |
| Acer          | Aspire 7745G                | [55ea55a771](https://linux-hardware.org/?probe=55ea55a771) | Sep 29, 2023 |
| Acer          | Nitro AN517-54              | [3e1448c388](https://linux-hardware.org/?probe=3e1448c388) | Sep 29, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | [6f19668c91](https://linux-hardware.org/?probe=6f19668c91) | Sep 29, 2023 |
| HP            | ZBook Studio G3             | [0005d20c0d](https://linux-hardware.org/?probe=0005d20c0d) | Sep 28, 2023 |
| Acer          | Aspire 7745G                | [6def421696](https://linux-hardware.org/?probe=6def421696) | Sep 28, 2023 |
| Acer          | Nitro AN515-52              | [e7fb14ee98](https://linux-hardware.org/?probe=e7fb14ee98) | Sep 28, 2023 |
| Acer          | Swift SF314-42              | [f436f21240](https://linux-hardware.org/?probe=f436f21240) | Sep 27, 2023 |
| HP            | Laptop 17-by0xxx            | [6eefb5fdd2](https://linux-hardware.org/?probe=6eefb5fdd2) | Sep 27, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2G90... | [50c8df3b79](https://linux-hardware.org/?probe=50c8df3b79) | Sep 27, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2G90... | [6cfd6e2b34](https://linux-hardware.org/?probe=6cfd6e2b34) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXX9                   | [5646b6da22](https://linux-hardware.org/?probe=5646b6da22) | Sep 27, 2023 |
| Dell          | XPS 15 9510                 | [72bb0c5858](https://linux-hardware.org/?probe=72bb0c5858) | Sep 27, 2023 |
| Acer          | Aspire E1-572G              | [45b934b885](https://linux-hardware.org/?probe=45b934b885) | Sep 26, 2023 |
| Infinix       | INBOOK Y1 PLUS NEO          | [30998449af](https://linux-hardware.org/?probe=30998449af) | Sep 26, 2023 |
| Apple         | MacBookPro8,1               | [ee86e0d81e](https://linux-hardware.org/?probe=ee86e0d81e) | Sep 26, 2023 |
| Apple         | MacBookPro8,1               | [1630b56fe3](https://linux-hardware.org/?probe=1630b56fe3) | Sep 26, 2023 |
| HP            | G62                         | [50fef7b3fa](https://linux-hardware.org/?probe=50fef7b3fa) | Sep 26, 2023 |
| VPU Compan... | VWNC71429                   | [285eb8a521](https://linux-hardware.org/?probe=285eb8a521) | Sep 25, 2023 |
| VPU Compan... | VWNC71429                   | [ec5aecc69d](https://linux-hardware.org/?probe=ec5aecc69d) | Sep 25, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [dbe3003db5](https://linux-hardware.org/?probe=dbe3003db5) | Sep 25, 2023 |
| HP            | ProBook 640 G1              | [a941b27d32](https://linux-hardware.org/?probe=a941b27d32) | Sep 25, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [a1e01ab80d](https://linux-hardware.org/?probe=a1e01ab80d) | Sep 25, 2023 |
| Infinix       | INBOOK X1 SLIM              | [bd6f358c7f](https://linux-hardware.org/?probe=bd6f358c7f) | Sep 25, 2023 |
| HP            | 255 G8 Notebook PC          | [38b5be59cc](https://linux-hardware.org/?probe=38b5be59cc) | Sep 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [2e717c304e](https://linux-hardware.org/?probe=2e717c304e) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 20HMS0EXOO    | [0818b5e737](https://linux-hardware.org/?probe=0818b5e737) | Sep 24, 2023 |
| Acer          | Aspire 5520                 | [5bcc67211c](https://linux-hardware.org/?probe=5bcc67211c) | Sep 24, 2023 |
| Acer          | Aspire V3-771               | [8d87ce31c5](https://linux-hardware.org/?probe=8d87ce31c5) | Sep 24, 2023 |
| Acer          | Aspire V3-771               | [10dfbbd349](https://linux-hardware.org/?probe=10dfbbd349) | Sep 24, 2023 |
| HP            | EliteBook 6930p (KK082AV... | [5e61b319b6](https://linux-hardware.org/?probe=5e61b319b6) | Sep 23, 2023 |
| Dell          | Latitude E7450              | [6ba017a802](https://linux-hardware.org/?probe=6ba017a802) | Sep 23, 2023 |
| Lenovo        | ThinkPad W550s 20E1S0VW0... | [e5c12ca1ce](https://linux-hardware.org/?probe=e5c12ca1ce) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [3b18f2e874](https://linux-hardware.org/?probe=3b18f2e874) | Sep 23, 2023 |
| Google        | Asuka                       | [cf59aebc4c](https://linux-hardware.org/?probe=cf59aebc4c) | Sep 23, 2023 |
| Panasonic     | CF-31JHG8M1M                | [3dc21238c6](https://linux-hardware.org/?probe=3dc21238c6) | Sep 23, 2023 |
| VPU Compan... | VWNC71429                   | [c601e6192f](https://linux-hardware.org/?probe=c601e6192f) | Sep 23, 2023 |
| Apple         | MacBookPro10,2              | [3580b7d8d6](https://linux-hardware.org/?probe=3580b7d8d6) | Sep 22, 2023 |
| Acer          | Aspire 5520                 | [8329086779](https://linux-hardware.org/?probe=8329086779) | Sep 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3bb5a0e5a0](https://linux-hardware.org/?probe=3bb5a0e5a0) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [347b768d57](https://linux-hardware.org/?probe=347b768d57) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [6ae9f9d9f2](https://linux-hardware.org/?probe=6ae9f9d9f2) | Sep 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [e63d1ae740](https://linux-hardware.org/?probe=e63d1ae740) | Sep 22, 2023 |
| ASUSTek       | X540LA                      | [adf0d97721](https://linux-hardware.org/?probe=adf0d97721) | Sep 22, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [be07169f5c](https://linux-hardware.org/?probe=be07169f5c) | Sep 22, 2023 |
| MSI           | GF65 Thin 9SEXR             | [9fbc54dcb7](https://linux-hardware.org/?probe=9fbc54dcb7) | Sep 22, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [a8c067b868](https://linux-hardware.org/?probe=a8c067b868) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | [01f346ff26](https://linux-hardware.org/?probe=01f346ff26) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | [ba1ec3eb6d](https://linux-hardware.org/?probe=ba1ec3eb6d) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [290e0fd96b](https://linux-hardware.org/?probe=290e0fd96b) | Sep 21, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [966f802eb6](https://linux-hardware.org/?probe=966f802eb6) | Sep 21, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [dd328a6f1f](https://linux-hardware.org/?probe=dd328a6f1f) | Sep 21, 2023 |
| Dell          | Precision 5550              | [c5183a7443](https://linux-hardware.org/?probe=c5183a7443) | Sep 21, 2023 |
| Dell          | Precision 5550              | [3d927d3dee](https://linux-hardware.org/?probe=3d927d3dee) | Sep 21, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | [bd096f1ae3](https://linux-hardware.org/?probe=bd096f1ae3) | Sep 20, 2023 |
| Acer          | Swift SF314-512             | [5c5a2a36e2](https://linux-hardware.org/?probe=5c5a2a36e2) | Sep 20, 2023 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [f8f954cde7](https://linux-hardware.org/?probe=f8f954cde7) | Sep 20, 2023 |
| VPU Compan... | VWNC71429                   | [4dd816ef81](https://linux-hardware.org/?probe=4dd816ef81) | Sep 20, 2023 |
| Apple         | MacBookPro12,1              | [0c71c0240e](https://linux-hardware.org/?probe=0c71c0240e) | Sep 20, 2023 |
| Dell          | Latitude E6430              | [32cf98639a](https://linux-hardware.org/?probe=32cf98639a) | Sep 20, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [98a32c8241](https://linux-hardware.org/?probe=98a32c8241) | Sep 19, 2023 |
| Acer          | Aspire E1-572G              | [139fc573bf](https://linux-hardware.org/?probe=139fc573bf) | Sep 19, 2023 |
| MSI           | GF65 Thin 9SEXR             | [d8166ef941](https://linux-hardware.org/?probe=d8166ef941) | Sep 19, 2023 |
| Acer          | Aspire 7715Z                | [7abea387dc](https://linux-hardware.org/?probe=7abea387dc) | Sep 19, 2023 |
| Sony          | SVE15137CGW                 | [b454be55a2](https://linux-hardware.org/?probe=b454be55a2) | Sep 19, 2023 |
| Acer          | Aspire A314-35              | [5f584efb57](https://linux-hardware.org/?probe=5f584efb57) | Sep 19, 2023 |
| Acer          | Aspire A317-53              | [7dfeb3f7ff](https://linux-hardware.org/?probe=7dfeb3f7ff) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [acd1c47b9d](https://linux-hardware.org/?probe=acd1c47b9d) | Sep 19, 2023 |
| KUU           | Andes II                    | [a104ad8142](https://linux-hardware.org/?probe=a104ad8142) | Sep 18, 2023 |
| Acer          | Aspire A315-24P             | [f9c346c325](https://linux-hardware.org/?probe=f9c346c325) | Sep 18, 2023 |
| HP            | Laptop 15s-fq5xxx           | [11d6fae345](https://linux-hardware.org/?probe=11d6fae345) | Sep 18, 2023 |
| Acer          | Aspire E1-572G              | [0578825483](https://linux-hardware.org/?probe=0578825483) | Sep 18, 2023 |
| ASUSTek       | X450CA                      | [b43a3aa61c](https://linux-hardware.org/?probe=b43a3aa61c) | Sep 18, 2023 |
| Apple         | MacBookAir4,2               | [1e61961aef](https://linux-hardware.org/?probe=1e61961aef) | Sep 17, 2023 |
| Lenovo        | G50-45 80E3                 | [cdfa321c48](https://linux-hardware.org/?probe=cdfa321c48) | Sep 17, 2023 |
| HP            | Laptop 15-fc0xxx            | [9720b79b9d](https://linux-hardware.org/?probe=9720b79b9d) | Sep 16, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1212656ddf](https://linux-hardware.org/?probe=1212656ddf) | Sep 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d37d40b74c](https://linux-hardware.org/?probe=d37d40b74c) | Sep 16, 2023 |
| ASUSTek       | K55DR                       | [f3b7f92416](https://linux-hardware.org/?probe=f3b7f92416) | Sep 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [10e74a88da](https://linux-hardware.org/?probe=10e74a88da) | Sep 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [bdfc48de30](https://linux-hardware.org/?probe=bdfc48de30) | Sep 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [3e8e61353c](https://linux-hardware.org/?probe=3e8e61353c) | Sep 15, 2023 |
| Apple         | MacBookPro16,2              | [601a3eed6e](https://linux-hardware.org/?probe=601a3eed6e) | Sep 15, 2023 |
| COM1          | NBINF-X5-9G5                | [aca0ed1105](https://linux-hardware.org/?probe=aca0ed1105) | Sep 15, 2023 |
| MSI           | Cyborg 15 A12VF             | [d1ef9fa580](https://linux-hardware.org/?probe=d1ef9fa580) | Sep 15, 2023 |
| Dell          | Inspiron 5770               | [ca5dd06f20](https://linux-hardware.org/?probe=ca5dd06f20) | Sep 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [3b71101d09](https://linux-hardware.org/?probe=3b71101d09) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [08e8a9a1a7](https://linux-hardware.org/?probe=08e8a9a1a7) | Sep 14, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [6d61c93aef](https://linux-hardware.org/?probe=6d61c93aef) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | [fd2d28b8af](https://linux-hardware.org/?probe=fd2d28b8af) | Sep 14, 2023 |
| Dell          | XPS 15 7590                 | [dc3d71404d](https://linux-hardware.org/?probe=dc3d71404d) | Sep 14, 2023 |
| HP            | ENVY Laptop 17-ch0xxx       | [e7463cdeb1](https://linux-hardware.org/?probe=e7463cdeb1) | Sep 14, 2023 |
| HP            | ZBook Studio G3             | [0a5342952c](https://linux-hardware.org/?probe=0a5342952c) | Sep 14, 2023 |
| Lenovo        | ThinkPad T570 20H90011ZA    | [f59a257ab5](https://linux-hardware.org/?probe=f59a257ab5) | Sep 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [a9cdcdc284](https://linux-hardware.org/?probe=a9cdcdc284) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | [1cf96bfa0e](https://linux-hardware.org/?probe=1cf96bfa0e) | Sep 14, 2023 |
| Dell          | Inspiron 5770               | [7056e15dc2](https://linux-hardware.org/?probe=7056e15dc2) | Sep 14, 2023 |
| KUU           | Andes II                    | [6270750e1e](https://linux-hardware.org/?probe=6270750e1e) | Sep 14, 2023 |
| Notebook      | NJ5x_NJ7xLU                 | [7ee403f2a2](https://linux-hardware.org/?probe=7ee403f2a2) | Sep 13, 2023 |
| Lenovo        | ThinkPad E14 20RA005MMX     | [d9d0c012b3](https://linux-hardware.org/?probe=d9d0c012b3) | Sep 13, 2023 |
| HUAWEI        | WRT-WX9                     | [6bc54e3a67](https://linux-hardware.org/?probe=6bc54e3a67) | Sep 13, 2023 |
| HUAWEI        | KLVL-WXXW                   | [138dfabe47](https://linux-hardware.org/?probe=138dfabe47) | Sep 13, 2023 |
| HP            | EliteBook 840 G6            | [4318e0630c](https://linux-hardware.org/?probe=4318e0630c) | Sep 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0180... | [2f123cee8b](https://linux-hardware.org/?probe=2f123cee8b) | Sep 12, 2023 |
| Dell          | Precision 3571              | [cf2bec0e5b](https://linux-hardware.org/?probe=cf2bec0e5b) | Sep 12, 2023 |
| Dell          | Latitude E6420              | [2a15e9a8e0](https://linux-hardware.org/?probe=2a15e9a8e0) | Sep 12, 2023 |
| HUAWEI        | NBM-WXX9                    | [74914c875f](https://linux-hardware.org/?probe=74914c875f) | Sep 12, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | [53961bd222](https://linux-hardware.org/?probe=53961bd222) | Sep 12, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [09ae29ce64](https://linux-hardware.org/?probe=09ae29ce64) | Sep 12, 2023 |
| HP            | Unknown                     | [defc1de0cf](https://linux-hardware.org/?probe=defc1de0cf) | Sep 11, 2023 |
| Dell          | Inspiron 5570               | [005f0b4e53](https://linux-hardware.org/?probe=005f0b4e53) | Sep 11, 2023 |
| Dell          | Latitude E6420              | [7e57362cdc](https://linux-hardware.org/?probe=7e57362cdc) | Sep 11, 2023 |
| Positivo      | C464F                       | [e8154e06d4](https://linux-hardware.org/?probe=e8154e06d4) | Sep 10, 2023 |
| Acer          | Predator PH315-51           | [80b1b18a60](https://linux-hardware.org/?probe=80b1b18a60) | Sep 10, 2023 |
| MSI           | Modern 14 A10M              | [978f30c076](https://linux-hardware.org/?probe=978f30c076) | Sep 10, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [5fc8984800](https://linux-hardware.org/?probe=5fc8984800) | Sep 10, 2023 |
| Dell          | Latitude 7280               | [fb9b253bd8](https://linux-hardware.org/?probe=fb9b253bd8) | Sep 10, 2023 |
| Dell          | Latitude 7280               | [936b42d3f3](https://linux-hardware.org/?probe=936b42d3f3) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | [9f3f71e147](https://linux-hardware.org/?probe=9f3f71e147) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | [f56c6e875b](https://linux-hardware.org/?probe=f56c6e875b) | Sep 10, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [e8f4b3bf42](https://linux-hardware.org/?probe=e8f4b3bf42) | Sep 09, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [69458a43ef](https://linux-hardware.org/?probe=69458a43ef) | Sep 09, 2023 |
| Dell          | G15 5511                    | [c382a29576](https://linux-hardware.org/?probe=c382a29576) | Sep 09, 2023 |
| Acer          | Aspire V5-472               | [198d33eff6](https://linux-hardware.org/?probe=198d33eff6) | Sep 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [ae24b6af25](https://linux-hardware.org/?probe=ae24b6af25) | Sep 09, 2023 |
| HP            | Pavilion dv9700             | [a747d33ab9](https://linux-hardware.org/?probe=a747d33ab9) | Sep 09, 2023 |
| Thomson       | N14C4WH64                   | [1e817297bb](https://linux-hardware.org/?probe=1e817297bb) | Sep 08, 2023 |
| Thomson       | N14C4WH64                   | [c1dae32be6](https://linux-hardware.org/?probe=c1dae32be6) | Sep 08, 2023 |
| Apple         | MacBookPro5,5               | [3ab6390052](https://linux-hardware.org/?probe=3ab6390052) | Sep 08, 2023 |
| ASUSTek       | X540LA                      | [b4ef54e230](https://linux-hardware.org/?probe=b4ef54e230) | Sep 08, 2023 |
| Notebook      | W65_67SC                    | [cefbf3383a](https://linux-hardware.org/?probe=cefbf3383a) | Sep 08, 2023 |
| Notebook      | W65_67SC                    | [73eae4d8a0](https://linux-hardware.org/?probe=73eae4d8a0) | Sep 08, 2023 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_23.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.2.0-20-generic       | 311       | 31.9%   |
| 6.2.0-26-generic       | 61        | 6.26%   |
| 6.2.0-32-generic       | 58        | 5.95%   |
| 6.2.0-27-generic       | 57        | 5.85%   |
| 6.2.0-25-generic       | 55        | 5.64%   |
| 6.2.0-24-generic       | 53        | 5.44%   |
| 6.2.0-33-generic       | 52        | 5.33%   |
| 6.2.0-23-generic       | 44        | 4.51%   |
| 6.2.0-34-generic       | 39        | 4%      |
| 6.2.0-39-generic       | 31        | 3.18%   |
| 6.2.0-35-generic       | 29        | 2.97%   |
| 6.2.0-31-generic       | 26        | 2.67%   |
| 6.2.0-36-generic       | 23        | 2.36%   |
| 5.19.0-21-generic      | 15        | 1.54%   |
| 6.2.0-18-generic       | 11        | 1.13%   |
| 6.4.0-060400-generic   | 7         | 0.72%   |
| 6.2.0-37-generic       | 7         | 0.72%   |
| 5.19.0-41-generic      | 7         | 0.72%   |
| 5.19.0-46-generic      | 6         | 0.62%   |
| 6.1.0-16-generic       | 5         | 0.51%   |
| 6.2.9-060209-generic   | 3         | 0.31%   |
| 6.2.0-38-generic       | 3         | 0.31%   |
| 5.19.0-40-generic      | 3         | 0.31%   |
| 5.19.0-31-generic      | 3         | 0.31%   |
| 6.5.1-060501-generic   | 2         | 0.21%   |
| 6.4.7-t2-lunar         | 2         | 0.21%   |
| 6.3.7-060307-generic   | 2         | 0.21%   |
| 6.3.5-060305-generic   | 2         | 0.21%   |
| 6.3.2-060302-generic   | 2         | 0.21%   |
| 6.2.0-19-generic       | 2         | 0.21%   |
| 6.2.0-1003-lowlatency  | 2         | 0.21%   |
| 5.19.0-28-generic      | 2         | 0.21%   |
| 6.6.0-tkg-eevdf        | 1         | 0.1%    |
| 6.5.9-2-liquorix-amd64 | 1         | 0.1%    |
| 6.5.7-xande            | 1         | 0.1%    |
| 6.5.6-tkg-cfs          | 1         | 0.1%    |
| 6.5.5-tkg-cfs          | 1         | 0.1%    |
| 6.5.3-x64v4-xanmod1    | 1         | 0.1%    |
| 6.5.1-tkg-cfs          | 1         | 0.1%    |
| 6.5.0-14-generic       | 1         | 0.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 6.2.0    | 811       | 88.44%  |
| 5.19.0   | 44        | 4.8%    |
| 6.4.0    | 7         | 0.76%   |
| 6.1.0    | 6         | 0.65%   |
| 6.3.0    | 4         | 0.44%   |
| 5.14.0   | 4         | 0.44%   |
| 6.5.1    | 3         | 0.33%   |
| 6.2.9    | 3         | 0.33%   |
| 6.5.0    | 2         | 0.22%   |
| 6.4.8    | 2         | 0.22%   |
| 6.4.7    | 2         | 0.22%   |
| 6.3.7    | 2         | 0.22%   |
| 6.3.5    | 2         | 0.22%   |
| 6.3.2    | 2         | 0.22%   |
| 6.6.0    | 1         | 0.11%   |
| 6.5.9    | 1         | 0.11%   |
| 6.5.7    | 1         | 0.11%   |
| 6.5.6    | 1         | 0.11%   |
| 6.5.5    | 1         | 0.11%   |
| 6.5.3    | 1         | 0.11%   |
| 6.4.6    | 1         | 0.11%   |
| 6.4.5    | 1         | 0.11%   |
| 6.4.3    | 1         | 0.11%   |
| 6.4.2    | 1         | 0.11%   |
| 6.4.12   | 1         | 0.11%   |
| 6.4.11   | 1         | 0.11%   |
| 6.3.8    | 1         | 0.11%   |
| 6.3.4    | 1         | 0.11%   |
| 6.3.1    | 1         | 0.11%   |
| 6.2.6    | 1         | 0.11%   |
| 6.2.12   | 1         | 0.11%   |
| 6.2.11   | 1         | 0.11%   |
| 6.0.9    | 1         | 0.11%   |
| 5.17.0   | 1         | 0.11%   |
| 5.15.108 | 1         | 0.11%   |
| 5.15.0   | 1         | 0.11%   |
| 5.11.0   | 1         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 817       | 89.39%  |
| 5.19    | 44        | 4.81%   |
| 6.4     | 15        | 1.64%   |
| 6.3     | 13        | 1.42%   |
| 6.5     | 9         | 0.98%   |
| 6.1     | 6         | 0.66%   |
| 5.14    | 4         | 0.44%   |
| 5.15    | 2         | 0.22%   |
| 6.6     | 1         | 0.11%   |
| 6.0     | 1         | 0.11%   |
| 5.17    | 1         | 0.11%   |
| 5.11    | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 904       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 875       | 96.58%  |
| X-Cinnamon      | 12        | 1.32%   |
| Unknown         | 7         | 0.77%   |
| GNOME Flashback | 4         | 0.44%   |
| i3              | 3         | 0.33%   |
| sway            | 2         | 0.22%   |
| GNOME Classic   | 2         | 0.22%   |
| DDE             | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 622       | 67.68%  |
| X11     | 285       | 31.01%  |
| Unknown | 7         | 0.76%   |
| Tty     | 5         | 0.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 800       | 88.4%   |
| Unknown | 82        | 9.06%   |
| LightDM | 19        | 2.1%    |
| SDDM    | 2         | 0.22%   |
| GREETD  | 1         | 0.11%   |
| GDM     | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 414       | 45.7%   |
| de_DE   | 95        | 10.49%  |
| fr_FR   | 52        | 5.74%   |
| es_ES   | 40        | 4.42%   |
| C       | 40        | 4.42%   |
| pt_BR   | 33        | 3.64%   |
| ru_RU   | 32        | 3.53%   |
| it_IT   | 32        | 3.53%   |
| en_GB   | 26        | 2.87%   |
| pl_PL   | 14        | 1.55%   |
| en_IN   | 10        | 1.1%    |
| en_AU   | 10        | 1.1%    |
| en_CA   | 9         | 0.99%   |
| nl_NL   | 7         | 0.77%   |
| sv_SE   | 5         | 0.55%   |
| ja_JP   | 5         | 0.55%   |
| fr_CA   | 5         | 0.55%   |
| es_MX   | 5         | 0.55%   |
| cs_CZ   | 5         | 0.55%   |
| bg_BG   | 5         | 0.55%   |
| Unknown | 5         | 0.55%   |
| hu_HU   | 4         | 0.44%   |
| en_ZA   | 4         | 0.44%   |
| zh_CN   | 3         | 0.33%   |
| tr_TR   | 3         | 0.33%   |
| pt_PT   | 3         | 0.33%   |
| nb_NO   | 3         | 0.33%   |
| fi_FI   | 3         | 0.33%   |
| el_GR   | 3         | 0.33%   |
| ca_ES   | 3         | 0.33%   |
| de_CH   | 2         | 0.22%   |
| de_AT   | 2         | 0.22%   |
| da_DK   | 2         | 0.22%   |
| th_TH   | 1         | 0.11%   |
| sr_RS   | 1         | 0.11%   |
| ro_RO   | 1         | 0.11%   |
| lt_LT   | 1         | 0.11%   |
| ko_KR   | 1         | 0.11%   |
| hr_HR   | 1         | 0.11%   |
| fa_IR   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 526       | 57.68%  |
| EFI  | 386       | 42.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Tmpfs   | 457       | 50.39%  |
| Ext4    | 413       | 45.53%  |
| Overlay | 21        | 2.32%   |
| Btrfs   | 10        | 1.1%    |
| Zfs     | 5         | 0.55%   |
| Xfs     | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 784       | 86.53%  |
| Unknown | 75        | 8.28%   |
| MBR     | 47        | 5.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 822       | 90.63%  |
| Yes       | 85        | 9.37%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 594       | 65.06%  |
| Yes       | 319       | 34.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo                                   | 190       | 21.02%  |
| Hewlett-Packard                          | 159       | 17.59%  |
| Dell                                     | 149       | 16.48%  |
| ASUSTek Computer                         | 92        | 10.18%  |
| Acer                                     | 81        | 8.96%   |
| Apple                                    | 36        | 3.98%   |
| HUAWEI                                   | 34        | 3.76%   |
| MSI                                      | 25        | 2.77%   |
| Toshiba                                  | 15        | 1.66%   |
| Samsung Electronics                      | 14        | 1.55%   |
| Google                                   | 11        | 1.22%   |
| Notebook                                 | 9         | 1%      |
| Timi                                     | 7         | 0.77%   |
| Sony                                     | 7         | 0.77%   |
| Unknown                                  | 7         | 0.77%   |
| Razer                                    | 4         | 0.44%   |
| Panasonic                                | 4         | 0.44%   |
| Packard Bell                             | 4         | 0.44%   |
| Medion                                   | 4         | 0.44%   |
| Infinix                                  | 4         | 0.44%   |
| Gigabyte Technology                      | 4         | 0.44%   |
| Shanghai Zhaoxin Semiconductor           | 3         | 0.33%   |
| Positivo                                 | 3         | 0.33%   |
| Intel                                    | 3         | 0.33%   |
| Fujitsu                                  | 3         | 0.33%   |
| Alienware                                | 3         | 0.33%   |
| Intel Client Systems                     | 2         | 0.22%   |
| HONOR                                    | 2         | 0.22%   |
| Gateway                                  | 2         | 0.22%   |
| VPU Company                              | 1         | 0.11%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. | 1         | 0.11%   |
| VALE                                     | 1         | 0.11%   |
| Thomson                                  | 1         | 0.11%   |
| Star Labs                                | 1         | 0.11%   |
| Shuttle                                  | 1         | 0.11%   |
| Semp Toshiba                             | 1         | 0.11%   |
| Rombica                                  | 1         | 0.11%   |
| PC Specialist                            | 1         | 0.11%   |
| Olivetti                                 | 1         | 0.11%   |
| Mediacom                                 | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 9         | 1%      |
| HP EliteBook 840 G6              | 7         | 0.77%   |
| Apple MacBookPro9,2              | 6         | 0.66%   |
| Dell Latitude 7480               | 5         | 0.55%   |
| HUAWEI KLVD-WXX9                 | 4         | 0.44%   |
| HUAWEI BOM-WXX9                  | 4         | 0.44%   |
| HP Notebook                      | 4         | 0.44%   |
| Dell Latitude 5400               | 4         | 0.44%   |
| Dell Inspiron 5521               | 4         | 0.44%   |
| Dell G5 5590                     | 4         | 0.44%   |
| Apple MacBookAir7,2              | 4         | 0.44%   |
| Shanghai Zhaoxin ZXE CRB         | 3         | 0.33%   |
| MSI Modern 14 A10M               | 3         | 0.33%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7 | 3         | 0.33%   |
| Lenovo IdeaPad 5 14ALC05 82LM    | 3         | 0.33%   |
| Lenovo G50-70 20351              | 3         | 0.33%   |
| HUAWEI KLVL-WXX9                 | 3         | 0.33%   |
| HUAWEI BOHB-WAX9                 | 3         | 0.33%   |
| HP ZBook Studio G3               | 3         | 0.33%   |
| HP Pavilion dv6                  | 3         | 0.33%   |
| HP ENVY 15                       | 3         | 0.33%   |
| HP EliteBook 840 G5              | 3         | 0.33%   |
| HP EliteBook 840 G3              | 3         | 0.33%   |
| Dell XPS 15 9500                 | 3         | 0.33%   |
| Dell Precision 5570              | 3         | 0.33%   |
| Dell Latitude E6420              | 3         | 0.33%   |
| Dell Latitude 7420               | 3         | 0.33%   |
| Dell Inspiron 3442               | 3         | 0.33%   |
| ASUS ZenBook UX325EA_UX325EA     | 3         | 0.33%   |
| ASUS Zenbook UM5302TA_UM5302TA   | 3         | 0.33%   |
| Apple MacBookPro5,5              | 3         | 0.33%   |
| Acer Swift SF314-512             | 3         | 0.33%   |
| Acer Aspire E5-575G              | 3         | 0.33%   |
| Acer Aspire E1-572G              | 3         | 0.33%   |
| Toshiba Satellite Pro C70-B      | 2         | 0.22%   |
| Timi RedmiBook 15                | 2         | 0.22%   |
| Timi Redmi Book Pro 14 2022      | 2         | 0.22%   |
| Packard Bell EasyNote ENTF71BM   | 2         | 0.22%   |
| MSI Stealth 15M B12UE            | 2         | 0.22%   |
| Lenovo V15 G4 AMN 82YU           | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 99        | 10.95%  |
| Dell Latitude         | 61        | 6.75%   |
| Lenovo IdeaPad        | 48        | 5.31%   |
| Acer Aspire           | 45        | 4.98%   |
| Dell Inspiron         | 36        | 3.98%   |
| HP EliteBook          | 35        | 3.87%   |
| HP Pavilion           | 27        | 2.99%   |
| HP Laptop             | 27        | 2.99%   |
| ASUS VivoBook         | 26        | 2.88%   |
| Dell XPS              | 24        | 2.65%   |
| HP ProBook            | 19        | 2.1%    |
| ASUS ZenBook          | 15        | 1.66%   |
| Acer Swift            | 15        | 1.66%   |
| Acer Nitro            | 13        | 1.44%   |
| Dell Precision        | 12        | 1.33%   |
| ASUS ASUS             | 12        | 1.33%   |
| Toshiba Satellite     | 11        | 1.22%   |
| Lenovo Legion         | 10        | 1.11%   |
| HP ENVY               | 10        | 1.11%   |
| Unknown               | 9         | 1%      |
| Dell Vostro           | 7         | 0.77%   |
| Apple MacBookPro9     | 7         | 0.77%   |
| Lenovo Yoga           | 6         | 0.66%   |
| Lenovo ThinkBook      | 6         | 0.66%   |
| MSI Stealth           | 5         | 0.55%   |
| HP ZBook              | 5         | 0.55%   |
| Dell G5               | 5         | 0.55%   |
| Razer Blade           | 4         | 0.44%   |
| Packard Bell EasyNote | 4         | 0.44%   |
| Lenovo V15            | 4         | 0.44%   |
| Infinix INBOOK        | 4         | 0.44%   |
| HUAWEI KLVD-WXX9      | 4         | 0.44%   |
| HUAWEI BOM-WXX9       | 4         | 0.44%   |
| HP Notebook           | 4         | 0.44%   |
| ASUS ROG              | 4         | 0.44%   |
| Apple MacBookPro11    | 4         | 0.44%   |
| Apple MacBookAir7     | 4         | 0.44%   |
| Toshiba PORTEGE       | 3         | 0.33%   |
| Shanghai Zhaoxin ZXE  | 3         | 0.33%   |
| MSI Modern            | 3         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 134       | 14.82%  |
| 2022    | 105       | 11.62%  |
| 2020    | 99        | 10.95%  |
| 2019    | 70        | 7.74%   |
| 2017    | 55        | 6.08%   |
| 2023    | 52        | 5.75%   |
| 2016    | 50        | 5.53%   |
| 2018    | 49        | 5.42%   |
| 2012    | 49        | 5.42%   |
| 2015    | 46        | 5.09%   |
| 2011    | 45        | 4.98%   |
| 2014    | 42        | 4.65%   |
| 2013    | 37        | 4.09%   |
| 2010    | 31        | 3.43%   |
| 2009    | 14        | 1.55%   |
| 2008    | 14        | 1.55%   |
| 2007    | 10        | 1.11%   |
| 2006    | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 904       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 807       | 88.78%  |
| Enabled  | 102       | 11.22%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 891       | 98.56%  |
| Yes  | 13        | 1.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 276       | 30.4%   |
| 16.01-24.0  | 189       | 20.81%  |
| 8.01-16.0   | 172       | 18.94%  |
| 3.01-4.0    | 129       | 14.21%  |
| 32.01-64.0  | 87        | 9.58%   |
| 24.01-32.0  | 26        | 2.86%   |
| 64.01-256.0 | 18        | 1.98%   |
| 1.01-2.0    | 7         | 0.77%   |
| 2.01-3.0    | 3         | 0.33%   |
| 0.01-0.5    | 1         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 298       | 31.57%  |
| 1.01-2.0   | 219       | 23.2%   |
| 4.01-8.0   | 206       | 21.82%  |
| 3.01-4.0   | 165       | 17.48%  |
| 8.01-16.0  | 39        | 4.13%   |
| 16.01-24.0 | 11        | 1.17%   |
| 24.01-32.0 | 2         | 0.21%   |
| 0.51-1.0   | 2         | 0.21%   |
| 32.01-64.0 | 1         | 0.11%   |
| 0.01-0.5   | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 706       | 77.41%  |
| 2      | 177       | 19.41%  |
| 3      | 21        | 2.3%    |
| 0      | 4         | 0.44%   |
| 4      | 3         | 0.33%   |
| 5      | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 693       | 76.66%  |
| Yes       | 211       | 23.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 635       | 70.17%  |
| No        | 270       | 29.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 896       | 99.01%  |
| No        | 9         | 0.99%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 790       | 86.91%  |
| No        | 119       | 13.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 129       | 14.24%  |
| Germany      | 106       | 11.7%   |
| France       | 60        | 6.62%   |
| Russia       | 51        | 5.63%   |
| Italy        | 50        | 5.52%   |
| Brazil       | 47        | 5.19%   |
| India        | 30        | 3.31%   |
| UK           | 28        | 3.09%   |
| Canada       | 27        | 2.98%   |
| Spain        | 25        | 2.76%   |
| Netherlands  | 19        | 2.1%    |
| Poland       | 18        | 1.99%   |
| Australia    | 18        | 1.99%   |
| Norway       | 17        | 1.88%   |
| Mexico       | 15        | 1.66%   |
| Romania      | 12        | 1.32%   |
| Turkey       | 10        | 1.1%    |
| Switzerland  | 9         | 0.99%   |
| Sweden       | 9         | 0.99%   |
| Pakistan     | 9         | 0.99%   |
| Hungary      | 9         | 0.99%   |
| Czechia      | 9         | 0.99%   |
| Portugal     | 8         | 0.88%   |
| China        | 8         | 0.88%   |
| Chile        | 8         | 0.88%   |
| Belgium      | 8         | 0.88%   |
| Austria      | 8         | 0.88%   |
| Japan        | 7         | 0.77%   |
| Indonesia    | 7         | 0.77%   |
| Greece       | 7         | 0.77%   |
| South Africa | 6         | 0.66%   |
| Ireland      | 6         | 0.66%   |
| Finland      | 6         | 0.66%   |
| Bulgaria     | 6         | 0.66%   |
| Kenya        | 5         | 0.55%   |
| Israel       | 5         | 0.55%   |
| Colombia     | 5         | 0.55%   |
| Belarus      | 5         | 0.55%   |
| Vietnam      | 4         | 0.44%   |
| Serbia       | 4         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 14        | 1.5%    |
| Berlin            | 12        | 1.29%   |
| Sao Paulo         | 10        | 1.07%   |
| Oslo              | 9         | 0.97%   |
| St Petersburg     | 7         | 0.75%   |
| Barcelona         | 7         | 0.75%   |
| Warsaw            | 6         | 0.64%   |
| Paris             | 6         | 0.64%   |
| Montreal          | 6         | 0.64%   |
| Milan             | 6         | 0.64%   |
| Sofia             | 5         | 0.54%   |
| Santiago          | 5         | 0.54%   |
| Prague            | 5         | 0.54%   |
| Oshawa            | 5         | 0.54%   |
| Nairobi           | 5         | 0.54%   |
| Melbourne         | 5         | 0.54%   |
| Leipzig           | 5         | 0.54%   |
| Helsinki          | 5         | 0.54%   |
| Atlanta           | 5         | 0.54%   |
| Vienna            | 4         | 0.43%   |
| Toronto           | 4         | 0.43%   |
| Tokyo             | 4         | 0.43%   |
| Rio de Janeiro    | 4         | 0.43%   |
| Perth             | 4         | 0.43%   |
| Munich            | 4         | 0.43%   |
| Milano            | 4         | 0.43%   |
| Hamburg           | 4         | 0.43%   |
| Frankfurt am Main | 4         | 0.43%   |
| Essen             | 4         | 0.43%   |
| Dublin            | 4         | 0.43%   |
| Denver            | 4         | 0.43%   |
| Cologne           | 4         | 0.43%   |
| Chennai           | 4         | 0.43%   |
| Budapest          | 4         | 0.43%   |
| Bucharest         | 4         | 0.43%   |
| Alexandria        | 4         | 0.43%   |
| Zurich            | 3         | 0.32%   |
| Valencia          | 3         | 0.32%   |
| Tel Aviv          | 3         | 0.32%   |
| Stuttgart         | 3         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 195       | 233    | 17.94%  |
| Sandisk                      | 84        | 96     | 7.73%   |
| Seagate                      | 78        | 93     | 7.18%   |
| WDC                          | 77        | 90     | 7.08%   |
| SK hynix                     | 68        | 74     | 6.26%   |
| Kingston                     | 60        | 65     | 5.52%   |
| Micron Technology            | 57        | 66     | 5.24%   |
| Toshiba                      | 51        | 55     | 4.69%   |
| Unknown                      | 47        | 54     | 4.32%   |
| Intel                        | 45        | 54     | 4.14%   |
| Crucial                      | 33        | 40     | 3.04%   |
| KIOXIA                       | 25        | 26     | 2.3%    |
| Apple                        | 22        | 29     | 2.02%   |
| Hitachi                      | 17        | 20     | 1.56%   |
| China                        | 15        | 17     | 1.38%   |
| Phison Electronics           | 14        | 18     | 1.29%   |
| HGST                         | 14        | 17     | 1.29%   |
| Kingston Technology Company  | 10        | 11     | 0.92%   |
| Phison                       | 9         | 9      | 0.83%   |
| ADATA Technology             | 8         | 10     | 0.74%   |
| A-DATA Technology            | 8         | 9      | 0.74%   |
| Unknown                      | 8         | 11     | 0.74%   |
| Silicon Motion               | 6         | 6      | 0.55%   |
| Micron/Crucial Technology    | 6         | 7      | 0.55%   |
| Intenso                      | 6         | 9      | 0.55%   |
| FORESEE                      | 6         | 7      | 0.55%   |
| SPCC                         | 5         | 5      | 0.46%   |
| LITEONIT                     | 5         | 6      | 0.46%   |
| LITEON                       | 5         | 8      | 0.46%   |
| SSSTC                        | 4         | 4      | 0.37%   |
| Shenzhen Longsys Electronics | 4         | 5      | 0.37%   |
| Netac                        | 4         | 4      | 0.37%   |
| Lexar                        | 4         | 4      | 0.37%   |
| GOODRAM                      | 4         | 4      | 0.37%   |
| Union Memory (Shenzhen)      | 3         | 3      | 0.28%   |
| Union Memory                 | 3         | 4      | 0.28%   |
| Transcend                    | 3         | 3      | 0.28%   |
| Team                         | 3         | 3      | 0.28%   |
| Realtek Semiconductor        | 3         | 3      | 0.28%   |
| Patriot                      | 3         | 3      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 24        | 2.15%   |
| Seagate ST1000LM035-1RK172 1TB                        | 17        | 1.52%   |
| Kingston SA400S37240G 240GB SSD                       | 16        | 1.43%   |
| Unknown MMC Card  64GB                                | 13        | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 13        | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 10        | 0.89%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 10        | 0.89%   |
| SanDisk NVMe SSD Drive 512GB                          | 9         | 0.81%   |
| Seagate ST500LT012-1DG142 500GB                       | 8         | 0.72%   |
| Kingston SA400S37480G 480GB SSD                       | 8         | 0.72%   |
| Intel SSDPEKNU512GZ 512GB                             | 8         | 0.72%   |
| Unknown                                               | 8         | 0.72%   |
| Unknown MMC Card  32GB                                | 7         | 0.63%   |
| Toshiba MQ01ABF050 500GB                              | 7         | 0.63%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 7         | 0.63%   |
| Toshiba XG6 NVMe SSD Controller 256GB                 | 6         | 0.54%   |
| Phison E12 NVMe Controller 1TB                        | 6         | 0.54%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                         | 6         | 0.54%   |
| Crucial CT500MX500SSD1 500GB                          | 6         | 0.54%   |
| Toshiba MQ04ABF100 1TB                                | 5         | 0.45%   |
| Toshiba MQ01ABD075 752GB                              | 5         | 0.45%   |
| Samsung SSD 980 PRO 2TB                               | 5         | 0.45%   |
| Samsung SSD 870 EVO 500GB                             | 5         | 0.45%   |
| Samsung SSD 870 EVO 1TB                               | 5         | 0.45%   |
| Samsung SSD 850 EVO 250GB                             | 5         | 0.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 5         | 0.45%   |
| Samsung MZVL21T0HCLR-00B00 1TB                        | 5         | 0.45%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 5         | 0.45%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 5         | 0.45%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB               | 5         | 0.45%   |
| HGST HTS721010A9E630 1TB                              | 5         | 0.45%   |
| Crucial CT240BX500SSD1 240GB                          | 5         | 0.45%   |
| Unknown MMC Card  16GB                                | 4         | 0.36%   |
| Unknown MMC Card  128GB                               | 4         | 0.36%   |
| Toshiba MQ01ABD100 1TB                                | 4         | 0.36%   |
| SK hynix HFM512GD3JX013N 512GB                        | 4         | 0.36%   |
| SK hynix BC511 256GB                                  | 4         | 0.36%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 4         | 0.36%   |
| Seagate ST1000LM049-2GH172 1TB                        | 4         | 0.36%   |
| Sandisk WD Black SN850 1024GB                         | 4         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 75        | 90     | 38.46%  |
| WDC                 | 37        | 42     | 18.97%  |
| Toshiba             | 32        | 35     | 16.41%  |
| Hitachi             | 17        | 20     | 8.72%   |
| HGST                | 14        | 17     | 7.18%   |
| Samsung Electronics | 6         | 6      | 3.08%   |
| Unknown             | 3         | 4      | 1.54%   |
| JMicron Technology  | 3         | 3      | 1.54%   |
| HGST HTS            | 2         | 2      | 1.03%   |
| Apple               | 2         | 4      | 1.03%   |
| USB3.0              | 1         | 1      | 0.51%   |
| USB                 | 1         | 1      | 0.51%   |
| Fujitsu             | 1         | 1      | 0.51%   |
| ASMT                | 1         | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 67        | 81     | 20.12%  |
| Kingston            | 45        | 50     | 13.51%  |
| SanDisk             | 29        | 31     | 8.71%   |
| Crucial             | 29        | 36     | 8.71%   |
| WDC                 | 16        | 22     | 4.8%    |
| SK hynix            | 16        | 17     | 4.8%    |
| China               | 15        | 17     | 4.5%    |
| Apple               | 13        | 15     | 3.9%    |
| Micron Technology   | 8         | 8      | 2.4%    |
| Intel               | 7         | 8      | 2.1%    |
| LITEONIT            | 5         | 6      | 1.5%    |
| LITEON              | 5         | 8      | 1.5%    |
| Intenso             | 5         | 7      | 1.5%    |
| A-DATA Technology   | 5         | 5      | 1.5%    |
| SPCC                | 4         | 4      | 1.2%    |
| Netac               | 4         | 4      | 1.2%    |
| Lexar               | 4         | 4      | 1.2%    |
| Unknown             | 4         | 4      | 1.2%    |
| Toshiba             | 3         | 3      | 0.9%    |
| Team                | 3         | 3      | 0.9%    |
| Patriot             | 3         | 3      | 0.9%    |
| GOODRAM             | 3         | 3      | 0.9%    |
| Gigabyte Technology | 3         | 3      | 0.9%    |
| Transcend           | 2         | 2      | 0.6%    |
| Smartbuy            | 2         | 2      | 0.6%    |
| PNY                 | 2         | 2      | 0.6%    |
| Plextor             | 2         | 2      | 0.6%    |
| OWC                 | 2         | 2      | 0.6%    |
| Kingchuxing         | 2         | 2      | 0.6%    |
| XUM                 | 1         | 1      | 0.3%    |
| XrayDisk            | 1         | 1      | 0.3%    |
| WDC WDS2            | 1         | 1      | 0.3%    |
| USB3.0              | 1         | 1      | 0.3%    |
| TwinMOS             | 1         | 1      | 0.3%    |
| sobetter            | 1         | 1      | 0.3%    |
| SCCTS-603-128G      | 1         | 1      | 0.3%    |
| SABRENT             | 1         | 1      | 0.3%    |
| S3+                 | 1         | 1      | 0.3%    |
| POWER               | 1         | 1      | 0.3%    |
| Pioneer             | 1         | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 475       | 579    | 46.03%  |
| SSD     | 308       | 380    | 29.84%  |
| HDD     | 193       | 227    | 18.7%   |
| MMC     | 45        | 53     | 4.36%   |
| Unknown | 11        | 13     | 1.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 474       | 576    | 47.16%  |
| SATA | 444       | 573    | 44.18%  |
| MMC  | 45        | 53     | 4.48%   |
| SAS  | 42        | 50     | 4.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 335       | 413    | 66.21%  |
| 0.51-1.0   | 150       | 164    | 29.64%  |
| 1.01-2.0   | 15        | 23     | 2.96%   |
| 4.01-10.0  | 3         | 4      | 0.59%   |
| 3.01-4.0   | 2         | 2      | 0.4%    |
| 10.01-20.0 | 1         | 1      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 288       | 31.07%  |
| 101-250        | 286       | 30.85%  |
| 501-1000       | 145       | 15.64%  |
| 1-20           | 50        | 5.39%   |
| 51-100         | 49        | 5.29%   |
| 1001-2000      | 42        | 4.53%   |
| 21-50          | 33        | 3.56%   |
| More than 3000 | 16        | 1.73%   |
| 2001-3000      | 13        | 1.4%    |
| Unknown        | 5         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 308       | 32.8%   |
| 21-50          | 244       | 25.99%  |
| 101-250        | 129       | 13.74%  |
| 51-100         | 120       | 12.78%  |
| 251-500        | 79        | 8.41%   |
| 501-1000       | 31        | 3.3%    |
| 1001-2000      | 13        | 1.38%   |
| 2001-3000      | 6         | 0.64%   |
| Unknown        | 5         | 0.53%   |
| More than 3000 | 4         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 10.71%  |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 7.14%   |
| WDC WD5000LPCX-75VHAT0 500GB             | 1         | 1      | 3.57%   |
| WDC WD10SPZX-21Z10T0 1TB                 | 1         | 1      | 3.57%   |
| WDC WD Green M.2 2280 240GB              | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD050 500GB                 | 1         | 1      | 3.57%   |
| Toshiba MK5065GSXF 500GB                 | 1         | 1      | 3.57%   |
| SSSTC CA6-8D2048-Q11 NVMe 2048GB         | 1         | 1      | 3.57%   |
| SK hynix SC308 SATA 256GB SSD            | 1         | 1      | 3.57%   |
| SK hynix PC711 HFS001TDE9X073N 1TB       | 1         | 1      | 3.57%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 3.57%   |
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 3.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 3.57%   |
| SanDisk SDSSDX120GG25 120GB              | 1         | 1      | 3.57%   |
| SanDisk SDSSDA120G 120GB                 | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 870 EVO 500GB    | 1         | 1      | 3.57%   |
| LITEONIT LCT-256M3S-41 7mm 256GB FDE SSD | 1         | 1      | 3.57%   |
| Hitachi HTS723225A7A365 OPAL 250GB       | 1         | 1      | 3.57%   |
| Hitachi HTS547564A9E384 640GB            | 1         | 1      | 3.57%   |
| Hitachi HTS542525K9SA00 250GB            | 1         | 2      | 3.57%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 3.57%   |
| Fujitsu MHW2160BH 160GB                  | 1         | 1      | 3.57%   |
| Crucial CT525MX300SSD4 528GB             | 1         | 1      | 3.57%   |
| Unknown                                  | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 17.86%  |
| HGST                | 4         | 4      | 14.29%  |
| WDC                 | 3         | 3      | 10.71%  |
| Toshiba             | 3         | 3      | 10.71%  |
| Hitachi             | 3         | 4      | 10.71%  |
| SK hynix            | 2         | 2      | 7.14%   |
| SanDisk             | 2         | 2      | 7.14%   |
| SSSTC               | 1         | 1      | 3.57%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| LITEONIT            | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |
| Unknown             | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 27.78%  |
| HGST    | 4         | 4      | 22.22%  |
| Toshiba | 3         | 3      | 16.67%  |
| Hitachi | 3         | 4      | 16.67%  |
| WDC     | 2         | 2      | 11.11%  |
| Fujitsu | 1         | 1      | 5.56%   |

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


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 578       | 836    | 62.08%  |
| Works    | 324       | 386    | 34.8%   |
| Malfunc  | 28        | 29     | 3.01%   |
| Failed   | 1         | 1      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 576       | 50.35%  |
| Samsung Electronics                     | 132       | 11.54%  |
| AMD                                     | 83        | 7.26%   |
| SanDisk                                 | 81        | 7.08%   |
| SK hynix                                | 52        | 4.55%   |
| Micron Technology                       | 49        | 4.28%   |
| Phison Electronics                      | 25        | 2.19%   |
| KIOXIA                                  | 23        | 2.01%   |
| Kingston Technology Company             | 22        | 1.92%   |
| Toshiba America Info Systems            | 18        | 1.57%   |
| ADATA Technology                        | 11        | 0.96%   |
| Micron/Crucial Technology               | 10        | 0.87%   |
| Shenzhen Longsys Electronics            | 9         | 0.79%   |
| Solid State Storage Technology          | 7         | 0.61%   |
| Silicon Motion                          | 7         | 0.61%   |
| Union Memory (Shenzhen)                 | 6         | 0.52%   |
| Apple                                   | 6         | 0.52%   |
| Nvidia                                  | 5         | 0.44%   |
| Realtek Semiconductor                   | 4         | 0.35%   |
| Zhaoxin                                 | 3         | 0.26%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.26%   |
| Yangtze Memory Technologies             | 2         | 0.17%   |
| Solidigm                                | 2         | 0.17%   |
| Marvell Technology Group                | 2         | 0.17%   |
| Transcend                               | 1         | 0.09%   |
| Silicon Image                           | 1         | 0.09%   |
| Shenzhen Unionmemory Information System | 1         | 0.09%   |
| Lite-On Technology                      | 1         | 0.09%   |
| Lenovo                                  | 1         | 0.09%   |
| ASMedia Technology                      | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                            | 80        | 6.59%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 79        | 6.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 74        | 6.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 53        | 4.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 49        | 4.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 45        | 3.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 40        | 3.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 36        | 2.97%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 29        | 2.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 29        | 2.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 25        | 2.06%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 23        | 1.89%   |
| Intel Tiger Lake-LP SATA Controller                                            | 23        | 1.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 23        | 1.89%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 19        | 1.57%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 17        | 1.4%    |
| Intel Comet Lake SATA AHCI Controller                                          | 17        | 1.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 16        | 1.32%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 14        | 1.15%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 14        | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 14        | 1.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 14        | 1.15%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 13        | 1.07%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 13        | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 13        | 1.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 0.99%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 11        | 0.91%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 11        | 0.91%   |
| Intel SSD 660P Series                                                          | 10        | 0.82%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 10        | 0.82%   |
| SK hynix BC511 NVMe SSD                                                        | 9         | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 0.74%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 9         | 0.74%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 9         | 0.74%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 9         | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 9         | 0.74%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 8         | 0.66%   |
| Phison E12 NVMe Controller                                                     | 8         | 0.66%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 8         | 0.66%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 7         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 531       | 45.62%  |
| NVMe | 471       | 40.46%  |
| RAID | 142       | 12.2%   |
| IDE  | 20        | 1.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 721       | 79.76%  |
| AMD          | 180       | 19.91%  |
| CentaurHauls | 3         | 0.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 20        | 2.21%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 18        | 1.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 14        | 1.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 14        | 1.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 14        | 1.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 13        | 1.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 13        | 1.44%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 12        | 1.33%   |
| Intel 12th Gen Core i7-12700H           | 12        | 1.33%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 12        | 1.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 11        | 1.22%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 11        | 1.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 11        | 1.22%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 11        | 1.22%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 11        | 1.22%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 11        | 1.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 9         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz       | 8         | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 8         | 0.88%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 8         | 0.88%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 8         | 0.88%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 8         | 0.88%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 8         | 0.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 8         | 0.88%   |
| AMD Ryzen 5 5625U with Radeon Graphics  | 8         | 0.88%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 8         | 0.88%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 7         | 0.77%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 7         | 0.77%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 7         | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 7         | 0.77%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 7         | 0.77%   |
| Intel 13th Gen Core i9-13900H           | 7         | 0.77%   |
| Intel 12th Gen Core i5-1240P            | 7         | 0.77%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 7         | 0.77%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 7         | 0.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 7         | 0.77%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 6         | 0.66%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 6         | 0.66%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 6         | 0.66%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 6         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 224       | 24.78%  |
| Other                   | 180       | 19.91%  |
| Intel Core i7           | 163       | 18.03%  |
| Intel Core i3           | 60        | 6.64%   |
| AMD Ryzen 7             | 60        | 6.64%   |
| AMD Ryzen 5             | 50        | 5.53%   |
| Intel Celeron           | 35        | 3.87%   |
| Intel Core 2 Duo        | 23        | 2.54%   |
| Intel Pentium           | 14        | 1.55%   |
| AMD Ryzen 9             | 11        | 1.22%   |
| AMD Ryzen 3             | 10        | 1.11%   |
| AMD A8                  | 9         | 1%      |
| AMD Ryzen 7 PRO         | 7         | 0.77%   |
| Intel Pentium Silver    | 6         | 0.66%   |
| AMD Ryzen 5 PRO         | 6         | 0.66%   |
| AMD A4                  | 6         | 0.66%   |
| AMD E2                  | 4         | 0.44%   |
| Intel Xeon              | 3         | 0.33%   |
| Intel Pentium Dual-Core | 3         | 0.33%   |
| Intel Pentium Dual      | 3         | 0.33%   |
| Intel Core i9           | 3         | 0.33%   |
| AMD A6                  | 3         | 0.33%   |
| AMD A10                 | 3         | 0.33%   |
| Intel Genuine           | 2         | 0.22%   |
| Intel Core M            | 2         | 0.22%   |
| AMD Turion 64 X2 Mobile | 2         | 0.22%   |
| AMD E                   | 2         | 0.22%   |
| Intel Pentium Gold      | 1         | 0.11%   |
| Intel Core m7           | 1         | 0.11%   |
| Intel Core m5           | 1         | 0.11%   |
| Intel Core m3           | 1         | 0.11%   |
| Intel Core 2            | 1         | 0.11%   |
| Intel Atom              | 1         | 0.11%   |
| AMD PRO A10             | 1         | 0.11%   |
| AMD E1                  | 1         | 0.11%   |
| AMD Athlon II           | 1         | 0.11%   |
| AMD Athlon              | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 378       | 41.77%  |
| 4      | 271       | 29.94%  |
| 8      | 97        | 10.72%  |
| 6      | 81        | 8.95%   |
| 14     | 34        | 3.76%   |
| 12     | 18        | 1.99%   |
| 10     | 18        | 1.99%   |
| 16     | 3         | 0.33%   |
| 24     | 2         | 0.22%   |
| 1      | 2         | 0.22%   |
| 5      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 904       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 747       | 82.63%  |
| 1      | 157       | 17.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 904       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 792       | 87.22%  |
| 0x08608103 | 13        | 1.43%   |
| 0x0a404102 | 11        | 1.21%   |
| 0x08600106 | 11        | 1.21%   |
| 0x0a50000d | 10        | 1.1%    |
| 0x0a50000c | 10        | 1.1%    |
| 0x906a3    | 5         | 0.55%   |
| 0x0a404101 | 5         | 0.55%   |
| 0x806ec    | 3         | 0.33%   |
| 0x0a704101 | 3         | 0.33%   |
| 0x08a00006 | 3         | 0.33%   |
| 0x08608102 | 3         | 0.33%   |
| 0x08600104 | 3         | 0.33%   |
| 0x306a9    | 2         | 0.22%   |
| 0x08a00008 | 2         | 0.22%   |
| 0x08608104 | 2         | 0.22%   |
| 0x08600109 | 2         | 0.22%   |
| 0x08600103 | 2         | 0.22%   |
| 0x08200103 | 2         | 0.22%   |
| 0x08108109 | 2         | 0.22%   |
| 0x08108102 | 2         | 0.22%   |
| 0x08101016 | 2         | 0.22%   |
| 0x07030105 | 2         | 0.22%   |
| 0x906ea    | 1         | 0.11%   |
| 0x806d1    | 1         | 0.11%   |
| 0x806c1    | 1         | 0.11%   |
| 0x506e3    | 1         | 0.11%   |
| 0x406e3    | 1         | 0.11%   |
| 0x40651    | 1         | 0.11%   |
| 0x306d4    | 1         | 0.11%   |
| 0x206a7    | 1         | 0.11%   |
| 0x0a601203 | 1         | 0.11%   |
| 0x0810100b | 1         | 0.11%   |
| 0x08101007 | 1         | 0.11%   |
| 0x07000110 | 1         | 0.11%   |
| 0x06006704 | 1         | 0.11%   |
| 0x0600611a | 1         | 0.11%   |
| 0x06006113 | 1         | 0.11%   |
| 0x06001119 | 1         | 0.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 164       | 18.06%  |
| Unknown          | 115       | 12.67%  |
| TigerLake        | 78        | 8.59%   |
| Skylake          | 62        | 6.83%   |
| IvyBridge        | 56        | 6.17%   |
| Alderlake Hybrid | 53        | 5.84%   |
| SandyBridge      | 48        | 5.29%   |
| Haswell          | 43        | 4.74%   |
| Broadwell        | 37        | 4.07%   |
| Zen 3            | 36        | 3.96%   |
| Zen 2            | 29        | 3.19%   |
| Penryn           | 22        | 2.42%   |
| Westmere         | 21        | 2.31%   |
| IceLake          | 21        | 2.31%   |
| Goldmont plus    | 20        | 2.2%    |
| CometLake        | 19        | 2.09%   |
| Silvermont       | 12        | 1.32%   |
| Zen+             | 11        | 1.21%   |
| Excavator        | 9         | 0.99%   |
| Core             | 9         | 0.99%   |
| Zen              | 8         | 0.88%   |
| Puma             | 6         | 0.66%   |
| Goldmont         | 6         | 0.66%   |
| Piledriver       | 5         | 0.55%   |
| K10 Llano        | 3         | 0.33%   |
| Jaguar           | 3         | 0.33%   |
| Bobcat           | 3         | 0.33%   |
| Tremont          | 2         | 0.22%   |
| Steamroller      | 2         | 0.22%   |
| Nehalem          | 2         | 0.22%   |
| K8 Hammer        | 2         | 0.22%   |
| K10              | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Intel          | 682       | 58.39%  |
| Nvidia         | 255       | 21.83%  |
| AMD            | 227       | 19.43%  |
| Zhaoxin        | 3         | 0.26%   |
| Silicon Motion | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 62        | 5.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 52        | 4.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 44        | 3.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 41        | 3.47%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 34        | 2.88%   |
| Intel HD Graphics 620                                                                 | 33        | 2.8%    |
| Intel UHD Graphics 620                                                                | 30        | 2.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 30        | 2.54%   |
| Intel HD Graphics 5500                                                                | 29        | 2.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 28        | 2.37%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 28        | 2.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 26        | 2.2%    |
| AMD Lucienne                                                                          | 26        | 2.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 25        | 2.12%   |
| AMD Rembrandt [Radeon 680M]                                                           | 25        | 2.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 20        | 1.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 19        | 1.61%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 18        | 1.53%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 18        | 1.53%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 17        | 1.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 16        | 1.36%   |
| AMD Barcelo                                                                           | 16        | 1.36%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 15        | 1.27%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 15        | 1.27%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 15        | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                                   | 15        | 1.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 14        | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 13        | 1.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 12        | 1.02%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 11        | 0.93%   |
| Intel HD Graphics 530                                                                 | 10        | 0.85%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 9         | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 8         | 0.68%   |
| Intel HD Graphics 630                                                                 | 8         | 0.68%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                 | 8         | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                                         | 7         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 7         | 0.59%   |
| Intel JasperLake [UHD Graphics]                                                       | 7         | 0.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 7         | 0.59%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 7         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 446       | 49.23%  |
| Intel + Nvidia     | 196       | 21.63%  |
| 1 x AMD            | 157       | 17.33%  |
| Intel + AMD        | 35        | 3.86%   |
| AMD + Nvidia       | 32        | 3.53%   |
| 1 x Nvidia         | 26        | 2.87%   |
| 2 x Intel          | 4         | 0.44%   |
| 2 x AMD            | 4         | 0.44%   |
| 1 x Zhaoxin        | 3         | 0.33%   |
| Other              | 2         | 0.22%   |
| 1 x Silicon Motion | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 736       | 81.15%  |
| Proprietary | 149       | 16.43%  |
| Unknown     | 22        | 2.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 764       | 83.96%  |
| 0.01-0.5   | 62        | 6.81%   |
| 1.01-2.0   | 41        | 4.51%   |
| 0.51-1.0   | 18        | 1.98%   |
| 3.01-4.0   | 16        | 1.76%   |
| 5.01-6.0   | 6         | 0.66%   |
| 7.01-8.0   | 2         | 0.22%   |
| 8.01-16.0  | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 207       | 19.51%  |
| BOE                     | 167       | 15.74%  |
| Chimei Innolux          | 146       | 13.76%  |
| LG Display              | 115       | 10.84%  |
| Samsung Electronics     | 107       | 10.08%  |
| Sharp                   | 36        | 3.39%   |
| Apple                   | 34        | 3.2%    |
| Dell                    | 32        | 3.02%   |
| Goldstar                | 27        | 2.54%   |
| PANDA                   | 19        | 1.79%   |
| CSO                     | 18        | 1.7%    |
| Lenovo                  | 14        | 1.32%   |
| Hewlett-Packard         | 14        | 1.32%   |
| InfoVision              | 11        | 1.04%   |
| Acer                    | 10        | 0.94%   |
| Chi Mei Optoelectronics | 8         | 0.75%   |
| BenQ                    | 8         | 0.75%   |
| Ancor Communications    | 8         | 0.75%   |
| Sony                    | 7         | 0.66%   |
| Iiyama                  | 6         | 0.57%   |
| Philips                 | 5         | 0.47%   |
| AOC                     | 5         | 0.47%   |
| Panasonic               | 4         | 0.38%   |
| ASUSTek Computer        | 4         | 0.38%   |
| ViewSonic               | 3         | 0.28%   |
| LG Philips              | 3         | 0.28%   |
| HKC                     | 3         | 0.28%   |
| Hitachi                 | 3         | 0.28%   |
| Denver                  | 3         | 0.28%   |
| Vestel Elektronik       | 2         | 0.19%   |
| Unknown                 | 2         | 0.19%   |
| Tianma XM               | 2         | 0.19%   |
| Seiki                   | 2         | 0.19%   |
| Mi                      | 2         | 0.19%   |
| HJC                     | 2         | 0.19%   |
| WST                     | 1         | 0.09%   |
| Wacom                   | 1         | 0.09%   |
| Unknown (XXX)           | 1         | 0.09%   |
| TopView                 | 1         | 0.09%   |
| TMX                     | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 12        | 1.12%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 8         | 0.75%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 8         | 0.75%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 0.65%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.65%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 7         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 6         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 5         | 0.47%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 5         | 0.47%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 5         | 0.47%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 5         | 0.47%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 5         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 0.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 4         | 0.37%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                 | 4         | 0.37%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 4         | 0.37%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 4         | 0.37%   |
| AU Optronics LCD Monitor AUO5799 1920x1080 344x194mm 15.5-inch        | 4         | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 4         | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.37%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 4         | 0.37%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 4         | 0.37%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 3         | 0.28%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.28%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 3         | 0.28%   |
| Samsung Electronics LCD Monitor SDC4172 2880x1800 289x186mm 13.5-inch | 3         | 0.28%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 3         | 0.28%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 3         | 0.28%   |
| PANDA LCD Monitor NCP004F 1920x1080 309x174mm 14.0-inch               | 3         | 0.28%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 3         | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 0.28%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 3         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 452       | 45.43%  |
| 1366x768 (WXGA)    | 215       | 21.61%  |
| 3840x2160 (4K)     | 53        | 5.33%   |
| 1600x900 (HD+)     | 40        | 4.02%   |
| 2560x1600          | 30        | 3.02%   |
| 2560x1440 (QHD)    | 30        | 3.02%   |
| 1920x1200 (WUXGA)  | 28        | 2.81%   |
| 2880x1800          | 24        | 2.41%   |
| 1280x800 (WXGA)    | 24        | 2.41%   |
| 3440x1440          | 14        | 1.41%   |
| 3840x2400          | 13        | 1.31%   |
| 1440x900 (WXGA+)   | 13        | 1.31%   |
| 2160x1440          | 10        | 1.01%   |
| 2240x1400          | 5         | 0.5%    |
| 1680x1050 (WSXGA+) | 5         | 0.5%    |
| 1280x1024 (SXGA)   | 5         | 0.5%    |
| 3456x2160          | 4         | 0.4%    |
| 2560x1080          | 4         | 0.4%    |
| 2256x1504          | 4         | 0.4%    |
| 3840x1600          | 2         | 0.2%    |
| 3200x2000          | 2         | 0.2%    |
| 3200x1800 (QHD+)   | 2         | 0.2%    |
| 3072x1920          | 2         | 0.2%    |
| 3000x2000          | 2         | 0.2%    |
| 2520x1680          | 2         | 0.2%    |
| 1024x768 (XGA)     | 2         | 0.2%    |
| 3840x1080          | 1         | 0.1%    |
| 2880x1920          | 1         | 0.1%    |
| 2880x1620          | 1         | 0.1%    |
| 2304x1440          | 1         | 0.1%    |
| 1920x550           | 1         | 0.1%    |
| 1920x540           | 1         | 0.1%    |
| 1920x1280          | 1         | 0.1%    |
| 1360x768           | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 392       | 36.91%  |
| 13      | 177       | 16.67%  |
| 14      | 155       | 14.6%   |
| 17      | 75        | 7.06%   |
| 27      | 38        | 3.58%   |
| 16      | 35        | 3.3%    |
| 24      | 25        | 2.35%   |
| 12      | 22        | 2.07%   |
| 23      | 20        | 1.88%   |
| 21      | 18        | 1.69%   |
| 34      | 14        | 1.32%   |
| 31      | 13        | 1.22%   |
| 11      | 13        | 1.22%   |
| Unknown | 7         | 0.66%   |
| 84      | 6         | 0.56%   |
| 22      | 6         | 0.56%   |
| 20      | 6         | 0.56%   |
| 72      | 5         | 0.47%   |
| 40      | 5         | 0.47%   |
| 25      | 4         | 0.38%   |
| 54      | 3         | 0.28%   |
| 35      | 3         | 0.28%   |
| 19      | 3         | 0.28%   |
| 18      | 3         | 0.28%   |
| 37      | 2         | 0.19%   |
| 60      | 1         | 0.09%   |
| 58      | 1         | 0.09%   |
| 52      | 1         | 0.09%   |
| 49      | 1         | 0.09%   |
| 48      | 1         | 0.09%   |
| 42      | 1         | 0.09%   |
| 32      | 1         | 0.09%   |
| 29      | 1         | 0.09%   |
| 28      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |
| 10      | 1         | 0.09%   |
| 8       | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 643       | 61.18%  |
| 201-300     | 134       | 12.75%  |
| 351-400     | 89        | 8.47%   |
| 501-600     | 83        | 7.9%    |
| 401-500     | 33        | 3.14%   |
| 601-700     | 16        | 1.52%   |
| 701-800     | 15        | 1.43%   |
| 1501-2000   | 11        | 1.05%   |
| 801-900     | 10        | 0.95%   |
| 1001-1500   | 8         | 0.76%   |
| Unknown     | 7         | 0.67%   |
| 101-200     | 1         | 0.1%    |
| 901-1000    | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 724       | 77.85%  |
| 16/10   | 152       | 16.34%  |
| 3/2     | 20        | 2.15%   |
| 21/9    | 20        | 2.15%   |
| 5/4     | 5         | 0.54%   |
| 32/9    | 3         | 0.32%   |
| 4/3     | 2         | 0.22%   |
| Unknown | 2         | 0.22%   |
| 6/5     | 1         | 0.11%   |
| 0.62    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 392       | 36.84%  |
| 81-90          | 268       | 25.19%  |
| 121-130        | 68        | 6.39%   |
| 71-80          | 60        | 5.64%   |
| 201-250        | 57        | 5.36%   |
| 301-350        | 40        | 3.76%   |
| 351-500        | 32        | 3.01%   |
| 111-120        | 32        | 3.01%   |
| 61-70          | 21        | 1.97%   |
| More than 1000 | 18        | 1.69%   |
| 151-200        | 15        | 1.41%   |
| 51-60          | 13        | 1.22%   |
| 251-300        | 11        | 1.03%   |
| 501-1000       | 9         | 0.85%   |
| 91-100         | 8         | 0.75%   |
| Unknown        | 7         | 0.66%   |
| 131-140        | 6         | 0.56%   |
| 141-150        | 5         | 0.47%   |
| 41-50          | 1         | 0.09%   |
| 1-40           | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 449       | 43.34%  |
| 101-120       | 252       | 24.32%  |
| 51-100        | 135       | 13.03%  |
| 161-240       | 125       | 12.07%  |
| More than 240 | 57        | 5.5%    |
| 1-50          | 11        | 1.06%   |
| Unknown       | 7         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 716       | 78.17%  |
| 2     | 148       | 16.16%  |
| 0     | 28        | 3.06%   |
| 3     | 23        | 2.51%   |
| 4     | 1         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 500       | 36.18%  |
| Realtek Semiconductor                  | 460       | 33.29%  |
| Qualcomm Atheros                       | 130       | 9.41%   |
| Broadcom                               | 73        | 5.28%   |
| MediaTek                               | 49        | 3.55%   |
| Broadcom Limited                       | 19        | 1.37%   |
| ASIX Electronics                       | 17        | 1.23%   |
| TP-Link                                | 13        | 0.94%   |
| DisplayLink                            | 12        | 0.87%   |
| Ralink                                 | 9         | 0.65%   |
| Lenovo                                 | 9         | 0.65%   |
| Sierra Wireless                        | 7         | 0.51%   |
| Xiaomi                                 | 6         | 0.43%   |
| Qualcomm                               | 6         | 0.43%   |
| Marvell Technology Group               | 6         | 0.43%   |
| Samsung Electronics                    | 5         | 0.36%   |
| Ralink Technology                      | 5         | 0.36%   |
| Dell                                   | 5         | 0.36%   |
| Nvidia                                 | 4         | 0.29%   |
| Huawei Technologies                    | 4         | 0.29%   |
| Hewlett-Packard                        | 4         | 0.29%   |
| JMicron Technology                     | 3         | 0.22%   |
| Google                                 | 3         | 0.22%   |
| Ericsson Business Mobile Networks      | 3         | 0.22%   |
| Apple                                  | 3         | 0.22%   |
| NetGear                                | 2         | 0.14%   |
| D-Link System                          | 2         | 0.14%   |
| ASUSTek Computer                       | 2         | 0.14%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.07%   |
| Vimtron Electronics                    | 1         | 0.07%   |
| U-Blox                                 | 1         | 0.07%   |
| TRENDnet                               | 1         | 0.07%   |
| Tenda                                  | 1         | 0.07%   |
| STMicroelectronics                     | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| Quectel Wireless Solutions             | 1         | 0.07%   |
| Qualcomm Technologies                  | 1         | 0.07%   |
| Qualcomm Atheros Communications        | 1         | 0.07%   |
| QinHeng Electronics                    | 1         | 0.07%   |
| OPPO Electronics                       | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 251       | 15.14%  |
| Intel Wi-Fi 6 AX201                                                    | 61        | 3.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 59        | 3.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 48        | 2.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 45        | 2.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 43        | 2.59%   |
| Intel Wireless 8265 / 8275                                             | 42        | 2.53%   |
| Intel Wi-Fi 6 AX200                                                    | 36        | 2.17%   |
| Intel Wireless 8260                                                    | 33        | 1.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 27        | 1.63%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 25        | 1.51%   |
| Intel Wireless 7265                                                    | 25        | 1.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 25        | 1.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 24        | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 24        | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 23        | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                                  | 23        | 1.39%   |
| Intel Ethernet Connection I219-LM                                      | 22        | 1.33%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 20        | 1.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 19        | 1.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 18        | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 18        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 17        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 17        | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 16        | 0.97%   |
| ASIX AX88179 Gigabit Ethernet                                          | 16        | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 15        | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 15        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 14        | 0.84%   |
| Realtek Killer E2600 GbE Controller                                    | 13        | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                          | 13        | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 12        | 0.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 11        | 0.66%   |
| Intel Wireless 7260                                                    | 10        | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 9         | 0.54%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 9         | 0.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 9         | 0.54%   |
| Intel Ethernet Connection (6) I219-LM                                  | 9         | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 484       | 51.54%  |
| Realtek Semiconductor           | 162       | 17.25%  |
| Qualcomm Atheros                | 120       | 12.78%  |
| Broadcom                        | 58        | 6.18%   |
| MediaTek                        | 46        | 4.9%    |
| Broadcom Limited                | 14        | 1.49%   |
| TP-Link                         | 11        | 1.17%   |
| Ralink                          | 9         | 0.96%   |
| Sierra Wireless                 | 7         | 0.75%   |
| Qualcomm                        | 6         | 0.64%   |
| Ralink Technology               | 5         | 0.53%   |
| Dell                            | 3         | 0.32%   |
| NetGear                         | 2         | 0.21%   |
| D-Link System                   | 2         | 0.21%   |
| ASUSTek Computer                | 2         | 0.21%   |
| TRENDnet                        | 1         | 0.11%   |
| Tenda                           | 1         | 0.11%   |
| Quectel Wireless Solutions      | 1         | 0.11%   |
| Qualcomm Technologies           | 1         | 0.11%   |
| Qualcomm Atheros Communications | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| D-Link                          | 1         | 0.11%   |
| Belkin Components               | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 61        | 6.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 48        | 5.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 45        | 4.76%   |
| Intel Wireless 8265 / 8275                                           | 42        | 4.44%   |
| Intel Wi-Fi 6 AX200                                                  | 36        | 3.81%   |
| Intel Wireless 8260                                                  | 33        | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 27        | 2.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 25        | 2.64%   |
| Intel Wireless 7265                                                  | 25        | 2.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 25        | 2.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 24        | 2.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 24        | 2.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 23        | 2.43%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 20        | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 19        | 2.01%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 18        | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 18        | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 17        | 1.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 17        | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 16        | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 15        | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 15        | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 14        | 1.48%   |
| Broadcom BCM43142 802.11b/g/n                                        | 13        | 1.37%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 12        | 1.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 11        | 1.16%   |
| Intel Wireless 7260                                                  | 10        | 1.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 9         | 0.95%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 9         | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 9         | 0.95%   |
| Intel Wireless 3165                                                  | 8         | 0.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 8         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 7         | 0.74%   |
| Intel Wi-Fi 6 AX201 160MHz                                           | 7         | 0.74%   |
| Intel Centrino Wireless-N 2230                                       | 7         | 0.74%   |
| Intel Centrino Advanced-N 6235                                       | 7         | 0.74%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 7         | 0.74%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 7         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 6         | 0.63%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 6         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 377       | 55.04%  |
| Intel                                  | 164       | 23.94%  |
| Broadcom                               | 30        | 4.38%   |
| Qualcomm Atheros                       | 23        | 3.36%   |
| ASIX Electronics                       | 17        | 2.48%   |
| DisplayLink                            | 12        | 1.75%   |
| Lenovo                                 | 9         | 1.31%   |
| Xiaomi                                 | 6         | 0.88%   |
| Marvell Technology Group               | 6         | 0.88%   |
| Broadcom Limited                       | 6         | 0.88%   |
| Samsung Electronics                    | 5         | 0.73%   |
| Nvidia                                 | 4         | 0.58%   |
| TP-Link                                | 3         | 0.44%   |
| MediaTek                               | 3         | 0.44%   |
| JMicron Technology                     | 3         | 0.44%   |
| Huawei Technologies                    | 3         | 0.44%   |
| Google                                 | 3         | 0.44%   |
| Apple                                  | 3         | 0.44%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.15%   |
| Vimtron Electronics                    | 1         | 0.15%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.15%   |
| OPPO Electronics                       | 1         | 0.15%   |
| Motorola PCS                           | 1         | 0.15%   |
| MosChip Semiconductor                  | 1         | 0.15%   |
| ICS Advent                             | 1         | 0.15%   |
| Hewlett-Packard                        | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 251       | 36.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 59        | 8.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 43        | 6.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24        | 3.44%   |
| Intel Ethernet Connection (4) I219-LM                                  | 23        | 3.3%    |
| Intel Ethernet Connection I219-LM                                      | 22        | 3.16%   |
| ASIX AX88179 Gigabit Ethernet                                          | 16        | 2.3%    |
| Realtek Killer E2600 GbE Controller                                    | 13        | 1.87%   |
| Intel Ethernet Connection (6) I219-LM                                  | 9         | 1.29%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 1.29%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 1.15%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 1%      |
| Intel 82567LM Gigabit Network Connection                               | 7         | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.86%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 0.86%   |
| Intel Ethernet Connection (6) I219-V                                   | 6         | 0.86%   |
| Intel Ethernet Connection (4) I219-V                                   | 6         | 0.86%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 6         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 0.72%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 5         | 0.72%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 0.72%   |
| Intel Ethernet Connection (13) I219-V                                  | 5         | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 0.57%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 4         | 0.57%   |
| Lenovo USB-C Dock Ethernet                                             | 4         | 0.57%   |
| Intel Ethernet Connection I219-V                                       | 4         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.57%   |
| DisplayLink USB3.0 Dual Video Dock                                     | 4         | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 4         | 0.57%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 3         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.43%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.43%   |
| Realtek PCIe GbE Family Controller                                     | 3         | 0.43%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 3         | 0.43%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.43%   |
| MediaTek File-CD Gadget                                                | 3         | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 3         | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 0.43%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 896       | 57.99%  |
| Ethernet | 635       | 41.1%   |
| Modem    | 13        | 0.84%   |
| Unknown  | 1         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 752       | 79.49%  |
| Ethernet | 194       | 20.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 549       | 60.6%   |
| 1     | 344       | 37.97%  |
| 3     | 7         | 0.77%   |
| 0     | 6         | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 627       | 68.6%   |
| Yes  | 287       | 31.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 416       | 52.2%   |
| Realtek Semiconductor           | 99        | 12.42%  |
| Qualcomm Atheros Communications | 54        | 6.78%   |
| Foxconn / Hon Hai               | 37        | 4.64%   |
| IMC Networks                    | 36        | 4.52%   |
| Lite-On Technology              | 29        | 3.64%   |
| Apple                           | 29        | 3.64%   |
| Broadcom                        | 23        | 2.89%   |
| Realtek                         | 19        | 2.38%   |
| Cambridge Silicon Radio         | 10        | 1.25%   |
| Dell                            | 9         | 1.13%   |
| Hewlett-Packard                 | 6         | 0.75%   |
| Toshiba                         | 5         | 0.63%   |
| Ralink                          | 5         | 0.63%   |
| ASUSTek Computer                | 4         | 0.5%    |
| USI                             | 3         | 0.38%   |
| TP-Link                         | 2         | 0.25%   |
| Opticis                         | 2         | 0.25%   |
| Chicony Electronics             | 2         | 0.25%   |
| Alps Electric                   | 2         | 0.25%   |
| Ralink Technology               | 1         | 0.13%   |
| MediaTek                        | 1         | 0.13%   |
| Fujitsu                         | 1         | 0.13%   |
| Edimax Technology               | 1         | 0.13%   |
| Actions                         | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 119       | 14.93%  |
| Intel AX201 Bluetooth                                                               | 116       | 14.55%  |
| Realtek Bluetooth Radio                                                             | 78        | 9.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 67        | 8.41%   |
| Intel Bluetooth Device                                                              | 50        | 6.27%   |
| Intel AX200 Bluetooth                                                               | 33        | 4.14%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 22        | 2.76%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 21        | 2.63%   |
| Realtek Bluetooth Radio                                                             | 19        | 2.38%   |
| IMC Networks Wireless_Device                                                        | 18        | 2.26%   |
| Apple Bluetooth Host Controller                                                     | 15        | 1.88%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 13        | 1.63%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 1.63%   |
| IMC Networks Bluetooth Radio                                                        | 13        | 1.63%   |
| Apple Bluetooth USB Host Controller                                                 | 13        | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 12        | 1.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 1.25%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 9         | 1.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 9         | 1.13%   |
| Lite-On Bluetooth Device                                                            | 9         | 1.13%   |
| Intel AX210 Bluetooth                                                               | 8         | 1%      |
| Foxconn / Hon Hai Bluetooth Device                                                  | 8         | 1%      |
| Broadcom BCM2045B (BDC-2.1)                                                         | 7         | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 0.75%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 0.63%   |
| Ralink RT3290 Bluetooth                                                             | 5         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 5         | 0.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 5         | 0.63%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 0.63%   |
| Lite-On Wireless_Device                                                             | 4         | 0.5%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 0.5%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 0.5%    |
| USI Bluetooth Device                                                                | 3         | 0.38%   |
| Toshiba BCM43142A0                                                                  | 3         | 0.38%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.38%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.38%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 3         | 0.38%   |
| ASUS ASUS USB-BT500                                                                 | 3         | 0.38%   |
| TP-Link UB500 Adapter                                                               | 2         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 713       | 62.22%  |
| AMD                                          | 197       | 17.19%  |
| Nvidia                                       | 151       | 13.18%  |
| Realtek Semiconductor                        | 10        | 0.87%   |
| GN Netcom                                    | 10        | 0.87%   |
| Lenovo                                       | 9         | 0.79%   |
| C-Media Electronics                          | 9         | 0.79%   |
| Plantronics                                  | 7         | 0.61%   |
| Zhaoxin                                      | 3         | 0.26%   |
| Kingston Technology                          | 3         | 0.26%   |
| Generalplus Technology                       | 3         | 0.26%   |
| VIA Technologies                             | 2         | 0.17%   |
| Razer USA                                    | 2         | 0.17%   |
| Native Instruments                           | 2         | 0.17%   |
| JMTek                                        | 2         | 0.17%   |
| Focusrite-Novation                           | 2         | 0.17%   |
| Apple                                        | 2         | 0.17%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.09%   |
| Texas Instruments                            | 1         | 0.09%   |
| Superlux digit                               | 1         | 0.09%   |
| Sony                                         | 1         | 0.09%   |
| Sennheiser Communications                    | 1         | 0.09%   |
| MV-SILICON                                   | 1         | 0.09%   |
| Microsoft                                    | 1         | 0.09%   |
| M-Audio                                      | 1         | 0.09%   |
| Logitech                                     | 1         | 0.09%   |
| KTMicro                                      | 1         | 0.09%   |
| Huawei Technologies                          | 1         | 0.09%   |
| Harman                                       | 1         | 0.09%   |
| DSEA A/S                                     | 1         | 0.09%   |
| Creative Technology                          | 1         | 0.09%   |
| Corsair                                      | 1         | 0.09%   |
| BR23                                         | 1         | 0.09%   |
| Blue Microphones                             | 1         | 0.09%   |
| BEHRINGER International                      | 1         | 0.09%   |
| Antlion Audio                                | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 132       | 9.58%   |
| Intel Sunrise Point-LP HD Audio                                            | 117       | 8.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 78        | 5.66%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 78        | 5.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 60        | 4.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 53        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 43        | 3.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 37        | 2.69%   |
| Intel Broadwell-U Audio Controller                                         | 37        | 2.69%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 34        | 2.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 31        | 2.25%   |
| Nvidia Audio device                                                        | 30        | 2.18%   |
| Intel Haswell-ULT HD Audio Controller                                      | 28        | 2.03%   |
| Intel Comet Lake PCH-LP cAVS                                               | 28        | 2.03%   |
| Intel 8 Series HD Audio Controller                                         | 28        | 2.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 27        | 1.96%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 22        | 1.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 21        | 1.52%   |
| AMD FCH Azalia Controller                                                  | 21        | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 20        | 1.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 19        | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 19        | 1.38%   |
| Nvidia GA106 High Definition Audio Controller                              | 18        | 1.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 18        | 1.31%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 17        | 1.23%   |
| Intel Comet Lake PCH cAVS                                                  | 17        | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 15        | 1.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 0.87%   |
| AMD Kabini HDMI/DP Audio                                                   | 12        | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                              | 11        | 0.8%    |
| Intel CM238 HD Audio Controller                                            | 11        | 0.8%    |
| Realtek Semiconductor USB Audio                                            | 9         | 0.65%   |
| Nvidia GA104 High Definition Audio Controller                              | 9         | 0.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 0.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 0.51%   |
| Intel Jasper Lake HD Audio                                                 | 7         | 0.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 7         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 149       | 26.99%  |
| SK hynix            | 121       | 21.92%  |
| Micron Technology   | 97        | 17.57%  |
| Kingston            | 46        | 8.33%   |
| Crucial             | 26        | 4.71%   |
| Unknown             | 19        | 3.44%   |
| A-DATA Technology   | 12        | 2.17%   |
| Ramaxel Technology  | 10        | 1.81%   |
| Unknown (ABCD)      | 9         | 1.63%   |
| Smart               | 8         | 1.45%   |
| Elpida              | 8         | 1.45%   |
| Unknown             | 5         | 0.91%   |
| Transcend           | 4         | 0.72%   |
| Timetec             | 3         | 0.54%   |
| Shenzhen WODPOSIT   | 3         | 0.54%   |
| Nanya Technology    | 3         | 0.54%   |
| G.Skill             | 3         | 0.54%   |
| Corsair             | 3         | 0.54%   |
| PNY                 | 2         | 0.36%   |
| Patriot             | 2         | 0.36%   |
| GOODRAM             | 2         | 0.36%   |
| Apacer              | 2         | 0.36%   |
| Unknown (0x0CDC)    | 1         | 0.18%   |
| Teikon              | 1         | 0.18%   |
| Team                | 1         | 0.18%   |
| Saikano             | 1         | 0.18%   |
| PUSKILL             | 1         | 0.18%   |
| Kingmax             | 1         | 0.18%   |
| KINGBANK            | 1         | 0.18%   |
| Goldkey             | 1         | 0.18%   |
| Gold Key            | 1         | 0.18%   |
| ff                  | 1         | 0.18%   |
| fef5                | 1         | 0.18%   |
| ChangXin Memory     | 1         | 0.18%   |
| ASint Technology    | 1         | 0.18%   |
| AMD                 | 1         | 0.18%   |
| 4ea5                | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 10        | 1.73%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 8         | 1.38%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 8         | 1.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 1.21%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 6         | 1.04%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 6         | 1.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 0.86%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 5         | 0.86%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 0.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 5         | 0.86%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s             | 5         | 0.86%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s        | 5         | 0.86%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 5         | 0.86%   |
| Unknown                                                             | 5         | 0.86%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                       | 4         | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 4         | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 0.69%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s    | 4         | 0.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 0.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 4         | 0.69%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 0.69%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB SODIMM LPDDR5 6400MT/s              | 4         | 0.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 4         | 0.69%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 3         | 0.52%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 3         | 0.52%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s               | 3         | 0.52%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s               | 3         | 0.52%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 3         | 0.52%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.52%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 3         | 0.52%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 3         | 0.52%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.52%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s         | 3         | 0.52%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s            | 3         | 0.52%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s          | 3         | 0.52%   |
| Micron RAM MT40A512M16LY-075:E 4GB SODIMM DDR4 3200MT/s             | 3         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 240       | 51.17%  |
| DDR3    | 92        | 19.62%  |
| LPDDR4  | 44        | 9.38%   |
| LPDDR5  | 36        | 7.68%   |
| DDR5    | 31        | 6.61%   |
| LPDDR3  | 14        | 2.99%   |
| DDR2    | 7         | 1.49%   |
| SDRAM   | 3         | 0.64%   |
| Unknown | 2         | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 376       | 79.16%  |
| Row Of Chips | 86        | 18.11%  |
| Chip         | 6         | 1.26%   |
| Unknown      | 6         | 1.26%   |
| DIMM         | 1         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 248       | 47.78%  |
| 4096  | 117       | 22.54%  |
| 16384 | 93        | 17.92%  |
| 2048  | 30        | 5.78%   |
| 32768 | 24        | 4.62%   |
| 1024  | 6         | 1.16%   |
| 1536  | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 142       | 28.46%  |
| 2667    | 78        | 15.63%  |
| 1600    | 76        | 15.23%  |
| 6400    | 34        | 6.81%   |
| 2400    | 32        | 6.41%   |
| 2133    | 27        | 5.41%   |
| 4800    | 25        | 5.01%   |
| 4267    | 20        | 4.01%   |
| 1334    | 9         | 1.8%    |
| 1333    | 8         | 1.6%    |
| 5600    | 7         | 1.4%    |
| 1867    | 7         | 1.4%    |
| 800     | 4         | 0.8%    |
| 8400    | 3         | 0.6%    |
| 4266    | 3         | 0.6%    |
| 3733    | 3         | 0.6%    |
| 2666    | 3         | 0.6%    |
| 667     | 3         | 0.6%    |
| 5500    | 2         | 0.4%    |
| 3266    | 2         | 0.4%    |
| 2048    | 2         | 0.4%    |
| 975     | 2         | 0.4%    |
| Unknown | 2         | 0.4%    |
| 5200    | 1         | 0.2%    |
| 4199    | 1         | 0.2%    |
| 2933    | 1         | 0.2%    |
| 1067    | 1         | 0.2%    |
| 533     | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 57.14%  |
| Samsung Electronics | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |
| Brother Industries  | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 1         | 14.29%  |
| HP LaserJet Pro M201dw               | 1         | 14.29%  |
| HP LaserJet P2015 series             | 1         | 14.29%  |
| HP DeskJet 4100 series               | 1         | 14.29%  |
| HP DeskJet 3830 series               | 1         | 14.29%  |
| Canon TS3100 series                  | 1         | 14.29%  |
| Brother HL-2250DN Laser Printer      | 1         | 14.29%  |

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
| Chicony Electronics                    | 188       | 22.79%  |
| IMC Networks                           | 85        | 10.3%   |
| Microdia                               | 84        | 10.18%  |
| Quanta                                 | 71        | 8.61%   |
| Realtek Semiconductor                  | 67        | 8.12%   |
| Bison Electronics                      | 42        | 5.09%   |
| Sunplus Innovation Technology          | 38        | 4.61%   |
| Cheng Uei Precision Industry (Foxlink) | 29        | 3.52%   |
| Luxvisions Innotech Limited            | 28        | 3.39%   |
| Apple                                  | 26        | 3.15%   |
| Syntek                                 | 22        | 2.67%   |
| Lite-On Technology                     | 18        | 2.18%   |
| Sonix Technology                       | 16        | 1.94%   |
| Acer                                   | 16        | 1.94%   |
| Suyin                                  | 12        | 1.45%   |
| Silicon Motion                         | 9         | 1.09%   |
| Logitech                               | 9         | 1.09%   |
| Alcor Micro                            | 9         | 1.09%   |
| Importek                               | 8         | 0.97%   |
| SunplusIT                              | 6         | 0.73%   |
| ShineTech                              | 6         | 0.73%   |
| Samsung Electronics                    | 6         | 0.73%   |
| USB Camera                             | 3         | 0.36%   |
| Shine-optics                           | 3         | 0.36%   |
| Ricoh                                  | 3         | 0.36%   |
| Microsoft                              | 3         | 0.36%   |
| Lenovo                                 | 3         | 0.36%   |
| Google                                 | 2         | 0.24%   |
| 8SSC21D67422V1SR3AV5KW1                | 2         | 0.24%   |
| Z-Star Microelectronics                | 1         | 0.12%   |
| Sunplus Technology                     | 1         | 0.12%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| OmniVision Technologies                | 1         | 0.12%   |
| Jieli Technology                       | 1         | 0.12%   |
| Foxconn / Hon Hai                      | 1         | 0.12%   |
| BKX-210918                             | 1         | 0.12%   |
| ALi                                    | 1         | 0.12%   |
| 8SSC21K12273V1SR33X2817                | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony integrated camera                            | 60        | 7.22%   |
| Microdia Integrated_Webcam_HD                        | 46        | 5.54%   |
| Realtek Integrated_Webcam_HD                         | 27        | 3.25%   |
| IMC Networks Integrated Camera                       | 26        | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 25        | 3.01%   |
| Chicony HP HD Camera                                 | 22        | 2.65%   |
| Chicony HD Webcam                                    | 19        | 2.29%   |
| Syntek Integrated Camera                             | 16        | 1.93%   |
| Bison Integrated Camera                              | 15        | 1.81%   |
| Sunplus Integrated_Webcam_HD                         | 13        | 1.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 11        | 1.32%   |
| Sonix USB2.0 HD UVC WebCam                           | 10        | 1.2%    |
| Realtek USB Camera                                   | 10        | 1.2%    |
| Quanta HD User Facing                                | 10        | 1.2%    |
| Chicony HD User Facing                               | 10        | 1.2%    |
| Quanta HP TrueVision HD Camera                       | 9         | 1.08%   |
| Chicony HP Truevision HD                             | 9         | 1.08%   |
| Apple FaceTime HD Camera                             | 9         | 1.08%   |
| Quanta ov9734_techfront_camera                       | 8         | 0.96%   |
| Lite-On Integrated Camera                            | 8         | 0.96%   |
| Chicony HP Truevision HD camera                      | 8         | 0.96%   |
| Quanta HP HD Camera                                  | 7         | 0.84%   |
| Quanta HD Camera                                     | 7         | 0.84%   |
| Microdia USB 2.0 Camera                              | 7         | 0.84%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 7         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 7         | 0.84%   |
| Sonix USB2.0 FHD UVC WebCam                          | 6         | 0.72%   |
| Samsung Galaxy series, misc. (MTP mode)              | 6         | 0.72%   |
| Chicony HP Wide Vision HD Camera                     | 6         | 0.72%   |
| Bison BisonCam,NB Pro                                | 6         | 0.72%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                   | 6         | 0.72%   |
| Realtek Integrated Webcam_HD                         | 5         | 0.6%    |
| Quanta HD Webcam                                     | 5         | 0.6%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 0.6%    |
| Lite-On HP HD Camera                                 | 5         | 0.6%    |
| Importek TOSHIBA Web Camera - HD                     | 5         | 0.6%    |
| IMC Networks ov9734_azurewave_camera                 | 5         | 0.6%    |
| IMC Networks HD Camera                               | 5         | 0.6%    |
| Chicony TOSHIBA Web Camera - HD                      | 5         | 0.6%    |
| Bison HD Webcam                                      | 5         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 56        | 30.43%  |
| Shenzhen Goodix Technology         | 51        | 27.72%  |
| Synaptics                          | 36        | 19.57%  |
| Elan Microelectronics              | 17        | 9.24%   |
| Upek                               | 7         | 3.8%    |
| LighTuning Technology              | 6         | 3.26%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 2.72%   |
| AuthenTec                          | 5         | 2.72%   |
| Focal-systems.Corp                 | 1         | 0.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 40        | 21.74%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 7.61%   |
| Elan ELAN:ARM-M4                                                           | 11        | 5.98%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 4.89%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 4.35%   |
| Shenzhen Goodix FingerPrint                                                | 8         | 4.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 3.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 3.8%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.26%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 3.26%   |
| Elan ELAN:Fingerprint                                                      | 6         | 3.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.72%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 2.72%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 2.72%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.17%   |
| Synaptics UWP WBDI Device                                                  | 4         | 2.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 2.17%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.63%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.63%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.63%   |
| AuthenTec AES2810                                                          | 3         | 1.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.54%   |
| Synaptics WBDI                                                             | 1         | 0.54%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.54%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.54%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 0.54%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.54%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.54%   |
| Unknown                                                                    | 1         | 0.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 38        | 62.3%   |
| Alcor Micro           | 17        | 27.87%  |
| Upek                  | 3         | 4.92%   |
| Lenovo                | 1         | 1.64%   |
| Hewlett-Packard       | 1         | 1.64%   |
| Advanced Card Systems | 1         | 1.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 17        | 27.87%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 27.87%  |
| Broadcom 58200                                                               | 11        | 18.03%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 13.11%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 4.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.28%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 1.64%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.64%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 522       | 57.05%  |
| 1     | 312       | 34.1%   |
| 2     | 62        | 6.78%   |
| 3     | 12        | 1.31%   |
| 4     | 6         | 0.66%   |
| 10    | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 184       | 38.82%  |
| Graphics card            | 106       | 22.36%  |
| Chipcard                 | 60        | 12.66%  |
| Camera                   | 33        | 6.96%   |
| Net/wireless             | 29        | 6.12%   |
| Multimedia controller    | 29        | 6.12%   |
| Bluetooth                | 7         | 1.48%   |
| Storage                  | 6         | 1.27%   |
| Sound                    | 6         | 1.27%   |
| Net/ethernet             | 4         | 0.84%   |
| Card reader              | 4         | 0.84%   |
| Modem                    | 2         | 0.42%   |
| Communication controller | 2         | 0.42%   |
| Unassigned class         | 1         | 0.21%   |
| Network                  | 1         | 0.21%   |

