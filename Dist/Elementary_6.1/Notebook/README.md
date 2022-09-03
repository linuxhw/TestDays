Elementary 6.1 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

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

Total: 434

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | NLx0MU                      | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| Apple         | MacBookPro5,2               | [7f66ca2cc7](https://linux-hardware.org/?probe=7f66ca2cc7) | Aug 29, 2022 |
| Standard      | Unknown                     | [62e0164e5b](https://linux-hardware.org/?probe=62e0164e5b) | Aug 29, 2022 |
| HP            | Laptop 15-db0xxx            | [d67f262815](https://linux-hardware.org/?probe=d67f262815) | Aug 28, 2022 |
| ASUSTek       | X542UA                      | [0bf776cdc1](https://linux-hardware.org/?probe=0bf776cdc1) | Aug 28, 2022 |
| HP            | 240 G7 Notebook PC          | [af418375d3](https://linux-hardware.org/?probe=af418375d3) | Aug 27, 2022 |
| Complet       | MY8312                      | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Dell          | Inspiron 5537               | [d05888c5bc](https://linux-hardware.org/?probe=d05888c5bc) | Aug 25, 2022 |
| Dell          | Latitude E7250              | [98f4886ef7](https://linux-hardware.org/?probe=98f4886ef7) | Aug 25, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [dfb0ad63df](https://linux-hardware.org/?probe=dfb0ad63df) | Aug 25, 2022 |
| Apple         | MacBookAir7,1               | [079a951d65](https://linux-hardware.org/?probe=079a951d65) | Aug 23, 2022 |
| Apple         | MacBookAir6,2               | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [7169cd34ab](https://linux-hardware.org/?probe=7169cd34ab) | Aug 22, 2022 |
| ASUSTek       | K52F                        | [cafd25a659](https://linux-hardware.org/?probe=cafd25a659) | Aug 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [08d6e2e6e8](https://linux-hardware.org/?probe=08d6e2e6e8) | Aug 21, 2022 |
| Apple         | MacBookPro8,2               | [b01d72c341](https://linux-hardware.org/?probe=b01d72c341) | Aug 20, 2022 |
| HP            | 240 G7 Notebook PC          | [ffa5707dc9](https://linux-hardware.org/?probe=ffa5707dc9) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | [a2c5089e9a](https://linux-hardware.org/?probe=a2c5089e9a) | Aug 16, 2022 |
| Acer          | Aspire V5-552G              | [f51f3093d9](https://linux-hardware.org/?probe=f51f3093d9) | Aug 12, 2022 |
| ASUSTek       | K43E                        | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| Dell          | Inspiron 5570               | [b94818059a](https://linux-hardware.org/?probe=b94818059a) | Aug 10, 2022 |
| Toshiba       | Satellite L875-11M          | [5a01928c94](https://linux-hardware.org/?probe=5a01928c94) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [72cfcef1a6](https://linux-hardware.org/?probe=72cfcef1a6) | Aug 10, 2022 |
| Dell          | Latitude D630               | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| Toshiba       | Satellite L875-11M          | [1b423f639e](https://linux-hardware.org/?probe=1b423f639e) | Aug 09, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [b719fff96d](https://linux-hardware.org/?probe=b719fff96d) | Aug 08, 2022 |
| HP            | Pavilion 17                 | [f06bb8d9ab](https://linux-hardware.org/?probe=f06bb8d9ab) | Aug 07, 2022 |
| HP            | Pavilion 17                 | [9c47c2e4f4](https://linux-hardware.org/?probe=9c47c2e4f4) | Aug 07, 2022 |
| TrekStor      | Notebook Slim S130          | [ba73d094e7](https://linux-hardware.org/?probe=ba73d094e7) | Aug 06, 2022 |
| Sony          | SVS15117FLB                 | [2729210175](https://linux-hardware.org/?probe=2729210175) | Aug 06, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | [6e4a76904c](https://linux-hardware.org/?probe=6e4a76904c) | Aug 06, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [7594659719](https://linux-hardware.org/?probe=7594659719) | Aug 05, 2022 |
| MSI           | Creator 15 A10SET           | [45d9d06fb8](https://linux-hardware.org/?probe=45d9d06fb8) | Aug 05, 2022 |
| Medion        | Akoya E6422 MD99680         | [86cd2f6a0a](https://linux-hardware.org/?probe=86cd2f6a0a) | Aug 05, 2022 |
| Sony          | SVS15117FLB                 | [1f64d30f2f](https://linux-hardware.org/?probe=1f64d30f2f) | Aug 05, 2022 |
| Dell          | Latitude 3190               | [7a0956e5f8](https://linux-hardware.org/?probe=7a0956e5f8) | Aug 04, 2022 |
| ASUSTek       | K43E                        | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [764d4ebd1b](https://linux-hardware.org/?probe=764d4ebd1b) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [5dab148c3e](https://linux-hardware.org/?probe=5dab148c3e) | Aug 04, 2022 |
| Dell          | Latitude E6400              | [54db9ae43d](https://linux-hardware.org/?probe=54db9ae43d) | Aug 04, 2022 |
| HP            | Pavilion dv6                | [b921b586f6](https://linux-hardware.org/?probe=b921b586f6) | Aug 02, 2022 |
| HP            | 431                         | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Dell          | Latitude E6320              | [34270898c6](https://linux-hardware.org/?probe=34270898c6) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | [04487d99ff](https://linux-hardware.org/?probe=04487d99ff) | Jul 30, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| Dell          | Latitude D630               | [37250474ae](https://linux-hardware.org/?probe=37250474ae) | Jul 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [af8fd9ae70](https://linux-hardware.org/?probe=af8fd9ae70) | Jul 29, 2022 |
| ASUSTek       | K43E                        | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| Dell          | Latitude D630               | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | Latitude E6320              | [a5b77aa0e9](https://linux-hardware.org/?probe=a5b77aa0e9) | Jul 28, 2022 |
| Dell          | Latitude 3190               | [36027c80d2](https://linux-hardware.org/?probe=36027c80d2) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [d9a5e0b7e6](https://linux-hardware.org/?probe=d9a5e0b7e6) | Jul 27, 2022 |
| HP            | Pavilion g4                 | [c9aa5e235c](https://linux-hardware.org/?probe=c9aa5e235c) | Jul 27, 2022 |
| HP            | 255 G7 Notebook PC          | [8173942fbb](https://linux-hardware.org/?probe=8173942fbb) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | [f4026901c2](https://linux-hardware.org/?probe=f4026901c2) | Jul 25, 2022 |
| HP            | Pavilion g6                 | [73061b2ed5](https://linux-hardware.org/?probe=73061b2ed5) | Jul 23, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [810b379dac](https://linux-hardware.org/?probe=810b379dac) | Jul 19, 2022 |
| HUAWEI        | HLYL-WXX9                   | [3831dd717e](https://linux-hardware.org/?probe=3831dd717e) | Jul 19, 2022 |
| Apple         | MacBookPro8,1               | [d5b50db42e](https://linux-hardware.org/?probe=d5b50db42e) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [54152fdf16](https://linux-hardware.org/?probe=54152fdf16) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Apple         | MacBookPro8,1               | [21c49763f5](https://linux-hardware.org/?probe=21c49763f5) | Jul 17, 2022 |
| HP            | EliteBook 8460p             | [b1c5cb2096](https://linux-hardware.org/?probe=b1c5cb2096) | Jul 12, 2022 |
| HP            | Notebook                    | [afaaed48c7](https://linux-hardware.org/?probe=afaaed48c7) | Jul 10, 2022 |
| Acer          | Aspire 1830T                | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| Acer          | Aspire AV15-51              | [1a880a89af](https://linux-hardware.org/?probe=1a880a89af) | Jul 09, 2022 |
| Acer          | Aspire V3-771               | [e8488fb0e2](https://linux-hardware.org/?probe=e8488fb0e2) | Jul 07, 2022 |
| HP            | Notebook                    | [2bf65688ab](https://linux-hardware.org/?probe=2bf65688ab) | Jul 05, 2022 |
| Dell          | Inspiron 3593               | [d34d56c473](https://linux-hardware.org/?probe=d34d56c473) | Jul 05, 2022 |
| HP            | Laptop 15-dy1xxx            | [3fcdd6c039](https://linux-hardware.org/?probe=3fcdd6c039) | Jul 03, 2022 |
| Dell          | XPS 15 9500                 | [7df8533350](https://linux-hardware.org/?probe=7df8533350) | Jul 03, 2022 |
| ASUSTek       | N56VB                       | [88d34c06f3](https://linux-hardware.org/?probe=88d34c06f3) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e13cada6ae](https://linux-hardware.org/?probe=e13cada6ae) | Jul 02, 2022 |
| ASUSTek       | X553MA                      | [804bbd8147](https://linux-hardware.org/?probe=804bbd8147) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | [9fe936cec8](https://linux-hardware.org/?probe=9fe936cec8) | Jun 30, 2022 |
| Dell          | Inspiron 5537               | [9758b4dcff](https://linux-hardware.org/?probe=9758b4dcff) | Jun 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| Apple         | MacBookPro14,2              | [7fe621e5a7](https://linux-hardware.org/?probe=7fe621e5a7) | Jun 27, 2022 |
| Compaq        | Presario CQ-23              | [f55fd14f61](https://linux-hardware.org/?probe=f55fd14f61) | Jun 26, 2022 |
| ASUSTek       | UX303LAB                    | [ae3becae01](https://linux-hardware.org/?probe=ae3becae01) | Jun 24, 2022 |
| HP            | Pavilion g4                 | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Alienware     | m17 R3                      | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| Dell          | Latitude E5510              | [1f6cc92f98](https://linux-hardware.org/?probe=1f6cc92f98) | Jun 18, 2022 |
| HP            | EliteBook 2170p             | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| HP            | ProBook 455R G6             | [31b94c71c7](https://linux-hardware.org/?probe=31b94c71c7) | Jun 16, 2022 |
| HP            | ProBook 455R G6             | [39d04d1188](https://linux-hardware.org/?probe=39d04d1188) | Jun 16, 2022 |
| Samsung       | Lumpy                       | [50dad22fb3](https://linux-hardware.org/?probe=50dad22fb3) | Jun 15, 2022 |
| ASUSTek       | GR8                         | [3cdc341eda](https://linux-hardware.org/?probe=3cdc341eda) | Jun 15, 2022 |
| Samsung       | Lumpy                       | [4137bf9757](https://linux-hardware.org/?probe=4137bf9757) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Apple         | MacBook4,1                  | [83cac56441](https://linux-hardware.org/?probe=83cac56441) | Jun 13, 2022 |
| HP            | ProBook 4540s               | [6688afd4f5](https://linux-hardware.org/?probe=6688afd4f5) | Jun 11, 2022 |
| Acer          | Aspire A315-21              | [9840a70112](https://linux-hardware.org/?probe=9840a70112) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [0ec841e188](https://linux-hardware.org/?probe=0ec841e188) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [5768dfe23f](https://linux-hardware.org/?probe=5768dfe23f) | Jun 11, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c76f63fb68](https://linux-hardware.org/?probe=c76f63fb68) | Jun 10, 2022 |
| HP            | ProBook 4540s               | [d0a6dcaa92](https://linux-hardware.org/?probe=d0a6dcaa92) | Jun 09, 2022 |
| Acer          | Aspire A315-21              | [224023dfd2](https://linux-hardware.org/?probe=224023dfd2) | Jun 08, 2022 |
| HP            | Notebook                    | [f07183fab5](https://linux-hardware.org/?probe=f07183fab5) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| HP            | ProBook 4540s               | [b74c4304e9](https://linux-hardware.org/?probe=b74c4304e9) | Jun 05, 2022 |
| Apple         | MacBookAir7,2               | [9de74ba486](https://linux-hardware.org/?probe=9de74ba486) | Jun 04, 2022 |
| Apple         | MacBookAir7,2               | [eb704f99ee](https://linux-hardware.org/?probe=eb704f99ee) | Jun 04, 2022 |
| Apple         | MacBookAir4,2               | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| HP            | ProBook 4540s               | [da53c77e1a](https://linux-hardware.org/?probe=da53c77e1a) | Jun 02, 2022 |
| Samsung       | 300E5M/300E5L               | [baa12d722c](https://linux-hardware.org/?probe=baa12d722c) | Jun 01, 2022 |
| Dell          | XPS 13 9343                 | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| HUAWEI        | MACHD-WXX9                  | [6cc36ec0ae](https://linux-hardware.org/?probe=6cc36ec0ae) | May 27, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [50f70bc9af](https://linux-hardware.org/?probe=50f70bc9af) | May 27, 2022 |
| ASUSTek       | X550CA                      | [6789d8dad5](https://linux-hardware.org/?probe=6789d8dad5) | May 26, 2022 |
| AMI           | Intel                       | [ee3b1abf63](https://linux-hardware.org/?probe=ee3b1abf63) | May 25, 2022 |
| Acer          | Swift SF114-32              | [601f82b2dd](https://linux-hardware.org/?probe=601f82b2dd) | May 23, 2022 |
| Apple         | MacBook4,1                  | [27f751618e](https://linux-hardware.org/?probe=27f751618e) | May 22, 2022 |
| HP            | ProBook 6550b               | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| AMI           | Intel                       | [6c571e79d0](https://linux-hardware.org/?probe=6c571e79d0) | May 21, 2022 |
| eMachines     | E525                        | [ca296b06c9](https://linux-hardware.org/?probe=ca296b06c9) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| Sony          | VPCEB23FM                   | [4d73e73cf8](https://linux-hardware.org/?probe=4d73e73cf8) | May 17, 2022 |
| Sony          | VPCEB23FM                   | [07d2cadefb](https://linux-hardware.org/?probe=07d2cadefb) | May 17, 2022 |
| Samsung       | Lumpy                       | [84a78226dd](https://linux-hardware.org/?probe=84a78226dd) | May 16, 2022 |
| HP            | ENVY 14                     | [9fe635b800](https://linux-hardware.org/?probe=9fe635b800) | May 15, 2022 |
| ASUSTek       | K55A                        | [3391d004a7](https://linux-hardware.org/?probe=3391d004a7) | May 15, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c0e150d349](https://linux-hardware.org/?probe=c0e150d349) | May 13, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [919200b122](https://linux-hardware.org/?probe=919200b122) | May 13, 2022 |
| ASUSTek       | UX310UQK                    | [1af1efeb46](https://linux-hardware.org/?probe=1af1efeb46) | May 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [d5df500fa3](https://linux-hardware.org/?probe=d5df500fa3) | May 10, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | ProBook 4510s               | [1464ea43d3](https://linux-hardware.org/?probe=1464ea43d3) | May 09, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [b726ded078](https://linux-hardware.org/?probe=b726ded078) | May 08, 2022 |
| Apple         | MacBookPro8,2               | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| eMachines     | E525                        | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Dell          | Inspiron 7720               | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| HP            | Pavilion 17                 | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X202E                       | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| Acer          | Aspire E5-411G              | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| Avell High... | B.ON                        | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| HP            | Pavilion 17                 | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [c12f5ae663](https://linux-hardware.org/?probe=c12f5ae663) | Apr 28, 2022 |
| HP            | EliteBook 840 G1            | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| Lenovo        | ThinkPad T420 41786VU       | [e2b4c2327b](https://linux-hardware.org/?probe=e2b4c2327b) | Apr 25, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| Dell          | Latitude 3120               | [78f0703e75](https://linux-hardware.org/?probe=78f0703e75) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [2f497982cd](https://linux-hardware.org/?probe=2f497982cd) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HP            | Pavilion g6                 | [63f6b73d50](https://linux-hardware.org/?probe=63f6b73d50) | Apr 21, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [d3d2e2fe8a](https://linux-hardware.org/?probe=d3d2e2fe8a) | Apr 18, 2022 |
| HP            | ProBook 6440b               | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Lenovo        | ThinkPad W541 20EGS0UB03    | [f566cb7f4c](https://linux-hardware.org/?probe=f566cb7f4c) | Apr 14, 2022 |
| HP            | ProBook 440 G7              | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| Acer          | Aspire E5-575G              | [07bdcd6978](https://linux-hardware.org/?probe=07bdcd6978) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [379db407c7](https://linux-hardware.org/?probe=379db407c7) | Apr 10, 2022 |
| HP            | Pavilion 13 x360 PC         | [3abf9847e4](https://linux-hardware.org/?probe=3abf9847e4) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| Apple         | MacBookAir6,2               | [84c694e881](https://linux-hardware.org/?probe=84c694e881) | Apr 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [fd62bf7f91](https://linux-hardware.org/?probe=fd62bf7f91) | Apr 05, 2022 |
| Dell          | Latitude 5410               | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| Apple         | MacBookAir6,2               | [656e7d1b73](https://linux-hardware.org/?probe=656e7d1b73) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| HP            | Notebook                    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Apple         | MacBookAir4,2               | [7fc2cd808d](https://linux-hardware.org/?probe=7fc2cd808d) | Apr 02, 2022 |
| Dell          | Vostro A860                 | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [9375dd090a](https://linux-hardware.org/?probe=9375dd090a) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [ab016f94d5](https://linux-hardware.org/?probe=ab016f94d5) | Apr 01, 2022 |
| HP            | EliteBook 8730w             | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| ASUSTek       | UL80VT                      | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Acer          | Aspire ES1-531              | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Toshiba       | Satellite C70D-A            | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| Toshiba       | Satellite L50D-C            | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Dell          | Inspiron MM061              | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| Sony          | SVP1321B4E                  | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Apple         | MacBookAir7,1               | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| Acer          | Aspire A315-21G             | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [7f9721781e](https://linux-hardware.org/?probe=7f9721781e) | Mar 12, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [bc5d95b759](https://linux-hardware.org/?probe=bc5d95b759) | Mar 12, 2022 |
| Teclast       | F15S                        | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASUSTek       | X200CA                      | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [c3e1baf45a](https://linux-hardware.org/?probe=c3e1baf45a) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [caa5c3eef1](https://linux-hardware.org/?probe=caa5c3eef1) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| Lenovo        | IdeaPad Y580                | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| Acer          | Nitro AN517-52              | [4576110ce4](https://linux-hardware.org/?probe=4576110ce4) | Mar 05, 2022 |
| HUAWEI        | MACHD-WXX9                  | [707b59278e](https://linux-hardware.org/?probe=707b59278e) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| HP            | ProBook 450 G7              | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | GL753VE                     | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| Packard Be... | EasyNote LS11HR             | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | X540SA                      | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| Dell          | Precision 7720              | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Google        | Lulu                        | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Sony          | SVE15115EN                  | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| Apple         | MacBookAir4,2               | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| Timi          | TM1613                      | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Apple         | MacBookPro6,2               | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| Dell          | Inspiron 15-3567            | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| ASUSTek       | K95VJ                       | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Razer         | Blade Stealth               | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| ASUSTek       | X555LN                      | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| Lenovo        | G550 20023                  | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| HP            | ProBook 4540s               | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Apple         | MacBookPro8,2               | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| Dell          | Latitude E5400              | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Star Labs     | StarBook                    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| MSI           | GF63 Thin 9SCSR             | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Timi          | TM1613                      | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| ASUSTek       | E202SA                      | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| Wortmann      | 1220729_1470271             | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| Dell          | Latitude 3580               | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| Dell          | Inspiron 5555               | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Lenovo        | V14-ADA 82C6                | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.11.0-43-generic          | 74        | 21.39%  |
| 5.13.0-28-generic          | 32        | 9.25%   |
| 5.13.0-30-generic          | 28        | 8.09%   |
| 5.13.0-27-generic          | 24        | 6.94%   |
| 5.15.0-41-generic          | 20        | 5.78%   |
| 5.13.0-39-generic          | 16        | 4.62%   |
| 5.13.0-40-generic          | 15        | 4.34%   |
| 5.15.0-46-generic          | 13        | 3.76%   |
| 5.13.0-35-generic          | 13        | 3.76%   |
| 5.11.0-44-generic          | 13        | 3.76%   |
| 5.13.0-37-generic          | 12        | 3.47%   |
| 5.15.0-43-generic          | 11        | 3.18%   |
| 5.13.0-52-generic          | 10        | 2.89%   |
| 5.13.0-41-generic          | 10        | 2.89%   |
| 5.11.0-46-generic          | 10        | 2.89%   |
| 5.13.0-51-generic          | 8         | 2.31%   |
| 5.13.0-44-generic          | 7         | 2.02%   |
| 5.13.0-48-generic          | 6         | 1.73%   |
| 5.11.0-41-generic          | 4         | 1.16%   |
| 5.13.0-25-generic          | 2         | 0.58%   |
| 5.11.0-40-generic          | 2         | 0.58%   |
| 5.8.0-50-generic           | 1         | 0.29%   |
| 5.4.0-122-generic          | 1         | 0.29%   |
| 5.19.3-051903-generic      | 1         | 0.29%   |
| 5.18.3-051803-generic      | 1         | 0.29%   |
| 5.16.16-051616-generic     | 1         | 0.29%   |
| 5.16.10-051610-generic     | 1         | 0.29%   |
| 5.16.0-13.4-liquorix-amd64 | 1         | 0.29%   |
| 5.15.36-xanmod1            | 1         | 0.29%   |
| 5.15.3-xanmod1             | 1         | 0.29%   |
| 5.15.21-051521-generic     | 1         | 0.29%   |
| 5.15.13-xanmod1            | 1         | 0.29%   |
| 5.15.12-xanmod1-tt         | 1         | 0.29%   |
| 5.15.11-t2-big-sur         | 1         | 0.29%   |
| 5.14.10-051410-generic     | 1         | 0.29%   |
| 5.14.0-1029-oem            | 1         | 0.29%   |
| 5.14.0-1011-oem            | 1         | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.0  | 172       | 51.65%  |
| 5.11.0  | 103       | 30.93%  |
| 5.15.0  | 42        | 12.61%  |
| 5.14.0  | 2         | 0.6%    |
| 5.8.0   | 1         | 0.3%    |
| 5.4.0   | 1         | 0.3%    |
| 5.19.3  | 1         | 0.3%    |
| 5.18.3  | 1         | 0.3%    |
| 5.16.16 | 1         | 0.3%    |
| 5.16.10 | 1         | 0.3%    |
| 5.16.0  | 1         | 0.3%    |
| 5.15.36 | 1         | 0.3%    |
| 5.15.3  | 1         | 0.3%    |
| 5.15.21 | 1         | 0.3%    |
| 5.15.13 | 1         | 0.3%    |
| 5.15.12 | 1         | 0.3%    |
| 5.15.11 | 1         | 0.3%    |
| 5.14.10 | 1         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13    | 172       | 51.81%  |
| 5.11    | 103       | 31.02%  |
| 5.15    | 48        | 14.46%  |
| 5.14    | 3         | 0.9%    |
| 5.16    | 2         | 0.6%    |
| 5.8     | 1         | 0.3%    |
| 5.4     | 1         | 0.3%    |
| 5.19    | 1         | 0.3%    |
| 5.18    | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 328       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 327       | 99.7%   |
| Unknown  | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 328       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 260       | 79.03%  |
| LightDM | 68        | 20.67%  |
| GDM     | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 150       | 45.73%  |
| de_DE   | 41        | 12.5%   |
| es_ES   | 24        | 7.32%   |
| ru_RU   | 18        | 5.49%   |
| pt_BR   | 16        | 4.88%   |
| en_GB   | 15        | 4.57%   |
| it_IT   | 13        | 3.96%   |
| fr_FR   | 12        | 3.66%   |
| pl_PL   | 6         | 1.83%   |
| nl_NL   | 6         | 1.83%   |
| pt_PT   | 4         | 1.22%   |
| en_AU   | 4         | 1.22%   |
| tr_TR   | 3         | 0.91%   |
| en_CA   | 3         | 0.91%   |
| nb_NO   | 2         | 0.61%   |
| hu_HU   | 2         | 0.61%   |
| zh_CN   | 1         | 0.3%    |
| uk_UA   | 1         | 0.3%    |
| sv_SE   | 1         | 0.3%    |
| et_EE   | 1         | 0.3%    |
| de_CH   | 1         | 0.3%    |
| cs_CZ   | 1         | 0.3%    |
| C       | 1         | 0.3%    |
| bg_BG   | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 230       | 69.91%  |
| BIOS | 99        | 30.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 318       | 96.95%  |
| Btrfs   | 6         | 1.83%   |
| Overlay | 4         | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 277       | 84.19%  |
| GPT     | 46        | 13.98%  |
| MBR     | 6         | 1.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 318       | 96.95%  |
| Yes       | 10        | 3.05%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 305       | 92.99%  |
| Yes       | 23        | 7.01%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 64        | 19.51%  |
| Hewlett-Packard        | 52        | 15.85%  |
| ASUSTek Computer       | 43        | 13.11%  |
| Apple                  | 39        | 11.89%  |
| Dell                   | 36        | 10.98%  |
| Acer                   | 26        | 7.93%   |
| Sony                   | 9         | 2.74%   |
| HUAWEI                 | 9         | 2.74%   |
| Samsung Electronics    | 7         | 2.13%   |
| MSI                    | 7         | 2.13%   |
| Toshiba                | 6         | 1.83%   |
| Notebook               | 3         | 0.91%   |
| Timi                   | 2         | 0.61%   |
| Teclast                | 2         | 0.61%   |
| Star Labs              | 2         | 0.61%   |
| Monster                | 2         | 0.61%   |
| LG Electronics         | 2         | 0.61%   |
| Wortmann AG            | 1         | 0.3%    |
| TrekStor               | 1         | 0.3%    |
| Standard               | 1         | 0.3%    |
| Razer                  | 1         | 0.3%    |
| PIPO                   | 1         | 0.3%    |
| Packard Bell           | 1         | 0.3%    |
| Medion                 | 1         | 0.3%    |
| iOTA                   | 1         | 0.3%    |
| Google                 | 1         | 0.3%    |
| Fujitsu                | 1         | 0.3%    |
| eMachines              | 1         | 0.3%    |
| Complet                | 1         | 0.3%    |
| Compaq                 | 1         | 0.3%    |
| Casper                 | 1         | 0.3%    |
| Avell High Performance | 1         | 0.3%    |
| AMI                    | 1         | 0.3%    |
| Alienware              | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Apple MacBookPro8,2                               | 4         | 1.22%   |
| Apple MacBook5,1                                  | 4         | 1.22%   |
| HUAWEI MACHD-WXX9                                 | 3         | 0.91%   |
| HP Notebook                                       | 3         | 0.91%   |
| ASUS ZenBook UX425EA_UX425EA                      | 3         | 0.91%   |
| ASUS X550CA                                       | 3         | 0.91%   |
| Apple MacBookAir4,2                               | 3         | 0.91%   |
| Apple MacBook4,1                                  | 3         | 0.91%   |
| Timi TM1613                                       | 2         | 0.61%   |
| MSI Prestige 15 A11UC                             | 2         | 0.61%   |
| Lenovo IdeaPad 310-15IKB 80TV                     | 2         | 0.61%   |
| HUAWEI NBLK-WAX9X                                 | 2         | 0.61%   |
| HP ProBook 4540s                                  | 2         | 0.61%   |
| HP Pavilion g6                                    | 2         | 0.61%   |
| HP Pavilion g4                                    | 2         | 0.61%   |
| HP Pavilion 17                                    | 2         | 0.61%   |
| HP Laptop 15-db0xxx                               | 2         | 0.61%   |
| HP EliteBook 8460p                                | 2         | 0.61%   |
| HP EliteBook 840 G1                               | 2         | 0.61%   |
| Dell XPS 13 9343                                  | 2         | 0.61%   |
| Dell Inspiron N5050                               | 2         | 0.61%   |
| Dell Inspiron 5537                                | 2         | 0.61%   |
| Dell Inspiron 15-3567                             | 2         | 0.61%   |
| Apple MacBookPro6,2                               | 2         | 0.61%   |
| Apple MacBookPro5,5                               | 2         | 0.61%   |
| Apple MacBookPro11,5                              | 2         | 0.61%   |
| Apple MacBookAir7,2                               | 2         | 0.61%   |
| Apple MacBookAir7,1                               | 2         | 0.61%   |
| Apple MacBookAir6,2                               | 2         | 0.61%   |
| Acer Swift SF114-32                               | 2         | 0.61%   |
| Wortmann AG 1220729_1470271                       | 1         | 0.3%    |
| TrekStor Notebook Slim S130                       | 1         | 0.3%    |
| Toshiba Satellite T130                            | 1         | 0.3%    |
| Toshiba Satellite L875-11M                        | 1         | 0.3%    |
| Toshiba Satellite L850D-BJS                       | 1         | 0.3%    |
| Toshiba Satellite L50D-C                          | 1         | 0.3%    |
| Toshiba Satellite C70D-A                          | 1         | 0.3%    |
| Toshiba PORTEGE Z830                              | 1         | 0.3%    |
| Teclast F7                                        | 1         | 0.3%    |
| Teclast F15S                                      | 1         | 0.3%    |
| Star Labs StarBook                                | 1         | 0.3%    |
| Star Labs LabTop                                  | 1         | 0.3%    |
| Sony VPCYB20AL                                    | 1         | 0.3%    |
| Sony VPCEB23FM                                    | 1         | 0.3%    |
| Sony VPCEA3S1E                                    | 1         | 0.3%    |
| Sony VPCCA4E1E                                    | 1         | 0.3%    |
| Sony SVS15117FLB                                  | 1         | 0.3%    |
| Sony SVP1321B4E                                   | 1         | 0.3%    |
| Sony SVF1521F6EW                                  | 1         | 0.3%    |
| Sony SVE15115EN                                   | 1         | 0.3%    |
| Sony SVE14A390X                                   | 1         | 0.3%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411       | 1         | 0.3%    |
| Samsung Lumpy                                     | 1         | 0.3%    |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.3%    |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D        | 1         | 0.3%    |
| Samsung 870Z5E/880Z5E/680Z5E                      | 1         | 0.3%    |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.3%    |
| Samsung 300E5M/300E5L                             | 1         | 0.3%    |
| Razer Blade Stealth                               | 1         | 0.3%    |
| PIPO W9                                           | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 33        | 10.06%  |
| Lenovo IdeaPad      | 20        | 6.1%    |
| Acer Aspire         | 18        | 5.49%   |
| Dell Inspiron       | 14        | 4.27%   |
| HP Pavilion         | 13        | 3.96%   |
| Dell Latitude       | 11        | 3.35%   |
| HP ProBook          | 10        | 3.05%   |
| HP EliteBook        | 10        | 3.05%   |
| ASUS VivoBook       | 8         | 2.44%   |
| ASUS ZenBook        | 7         | 2.13%   |
| HP Laptop           | 6         | 1.83%   |
| Apple MacBookPro8   | 6         | 1.83%   |
| Toshiba Satellite   | 5         | 1.52%   |
| Apple MacBook5      | 5         | 1.52%   |
| Acer Swift          | 5         | 1.52%   |
| Dell XPS            | 4         | 1.22%   |
| Dell Precision      | 4         | 1.22%   |
| Apple MacBookPro5   | 4         | 1.22%   |
| Apple MacBookAir7   | 4         | 1.22%   |
| Lenovo Legion       | 3         | 0.91%   |
| HUAWEI MACHD-WXX9   | 3         | 0.91%   |
| HP Notebook         | 3         | 0.91%   |
| Dell Vostro         | 3         | 0.91%   |
| ASUS X550CA         | 3         | 0.91%   |
| Apple MacBookAir6   | 3         | 0.91%   |
| Apple MacBookAir4   | 3         | 0.91%   |
| Apple MacBook4      | 3         | 0.91%   |
| Timi TM1613         | 2         | 0.61%   |
| MSI Prestige        | 2         | 0.61%   |
| MSI Modern          | 2         | 0.61%   |
| Lenovo ThinkBook    | 2         | 0.61%   |
| Lenovo G550         | 2         | 0.61%   |
| HUAWEI NBLK-WAX9X   | 2         | 0.61%   |
| HP Stream           | 2         | 0.61%   |
| HP 255              | 2         | 0.61%   |
| HP 240              | 2         | 0.61%   |
| Apple MacBookPro9   | 2         | 0.61%   |
| Apple MacBookPro6   | 2         | 0.61%   |
| Apple MacBookPro11  | 2         | 0.61%   |
| Acer Nitro          | 2         | 0.61%   |
| Wortmann AG 1220729 | 1         | 0.3%    |
| TrekStor Notebook   | 1         | 0.3%    |
| Toshiba PORTEGE     | 1         | 0.3%    |
| Teclast F7          | 1         | 0.3%    |
| Teclast F15S        | 1         | 0.3%    |
| Star Labs StarBook  | 1         | 0.3%    |
| Star Labs LabTop    | 1         | 0.3%    |
| Sony VPCYB20AL      | 1         | 0.3%    |
| Sony VPCEB23FM      | 1         | 0.3%    |
| Sony VPCEA3S1E      | 1         | 0.3%    |
| Sony VPCCA4E1E      | 1         | 0.3%    |
| Sony SVS15117FLB    | 1         | 0.3%    |
| Sony SVP1321B4E     | 1         | 0.3%    |
| Sony SVF1521F6EW    | 1         | 0.3%    |
| Sony SVE15115EN     | 1         | 0.3%    |
| Sony SVE14A390X     | 1         | 0.3%    |
| Samsung RV411       | 1         | 0.3%    |
| Samsung Lumpy       | 1         | 0.3%    |
| Samsung 950XDB      | 1         | 0.3%    |
| Samsung 900X3C      | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 40        | 12.2%   |
| 2018 | 31        | 9.45%   |
| 2021 | 29        | 8.84%   |
| 2013 | 27        | 8.23%   |
| 2012 | 27        | 8.23%   |
| 2019 | 26        | 7.93%   |
| 2016 | 24        | 7.32%   |
| 2015 | 24        | 7.32%   |
| 2011 | 23        | 7.01%   |
| 2009 | 17        | 5.18%   |
| 2017 | 16        | 4.88%   |
| 2010 | 16        | 4.88%   |
| 2014 | 14        | 4.27%   |
| 2008 | 11        | 3.35%   |
| 2022 | 1         | 0.3%    |
| 2007 | 1         | 0.3%    |
| 2006 | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 328       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 270       | 82.07%  |
| Enabled  | 59        | 17.93%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 324       | 98.78%  |
| Yes  | 4         | 1.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 118       | 35.76%  |
| 3.01-4.0    | 82        | 24.85%  |
| 16.01-24.0  | 55        | 16.67%  |
| 8.01-16.0   | 47        | 14.24%  |
| 32.01-64.0  | 13        | 3.94%   |
| 1.01-2.0    | 10        | 3.03%   |
| 2.01-3.0    | 2         | 0.61%   |
| 64.01-256.0 | 2         | 0.61%   |
| 24.01-32.0  | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 131       | 37.97%  |
| 2.01-3.0   | 112       | 32.46%  |
| 3.01-4.0   | 49        | 14.2%   |
| 4.01-8.0   | 29        | 8.41%   |
| 0.51-1.0   | 13        | 3.77%   |
| 8.01-16.0  | 9         | 2.61%   |
| 24.01-32.0 | 1         | 0.29%   |
| 16.01-24.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 244       | 73.94%  |
| 2      | 81        | 24.55%  |
| 3      | 4         | 1.21%   |
| 5      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 223       | 67.37%  |
| Yes       | 108       | 32.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 240       | 73.17%  |
| No        | 88        | 26.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 325       | 98.78%  |
| No        | 4         | 1.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 294       | 88.82%  |
| No        | 37        | 11.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| USA             | 47        | 14.33%  |
| Germany         | 37        | 11.28%  |
| Russia          | 22        | 6.71%   |
| Brazil          | 22        | 6.71%   |
| Italy           | 16        | 4.88%   |
| India           | 16        | 4.88%   |
| UK              | 15        | 4.57%   |
| Turkey          | 9         | 2.74%   |
| France          | 9         | 2.74%   |
| Poland          | 8         | 2.44%   |
| Mexico          | 8         | 2.44%   |
| Indonesia       | 8         | 2.44%   |
| Australia       | 8         | 2.44%   |
| Netherlands     | 7         | 2.13%   |
| Spain           | 6         | 1.83%   |
| Chile           | 6         | 1.83%   |
| Canada          | 6         | 1.83%   |
| Belgium         | 6         | 1.83%   |
| Portugal        | 5         | 1.52%   |
| Argentina       | 5         | 1.52%   |
| Switzerland     | 4         | 1.22%   |
| Austria         | 4         | 1.22%   |
| Ukraine         | 3         | 0.91%   |
| Romania         | 3         | 0.91%   |
| Norway          | 3         | 0.91%   |
| New Zealand     | 3         | 0.91%   |
| Hungary         | 3         | 0.91%   |
| Czechia         | 3         | 0.91%   |
| South Africa    | 2         | 0.61%   |
| Pakistan        | 2         | 0.61%   |
| Estonia         | 2         | 0.61%   |
| Colombia        | 2         | 0.61%   |
| Bulgaria        | 2         | 0.61%   |
| Belarus         | 2         | 0.61%   |
| Zambia          | 1         | 0.3%    |
| Taiwan          | 1         | 0.3%    |
| Sweden          | 1         | 0.3%    |
| Sri Lanka       | 1         | 0.3%    |
| Serbia          | 1         | 0.3%    |
| Senegal         | 1         | 0.3%    |
| Peru            | 1         | 0.3%    |
| North Macedonia | 1         | 0.3%    |
| Nicaragua       | 1         | 0.3%    |
| Mozambique      | 1         | 0.3%    |
| Luxembourg      | 1         | 0.3%    |
| Lithuania       | 1         | 0.3%    |
| Latvia          | 1         | 0.3%    |
| Kenya           | 1         | 0.3%    |
| Japan           | 1         | 0.3%    |
| Ireland         | 1         | 0.3%    |
| Iran            | 1         | 0.3%    |
| Iceland         | 1         | 0.3%    |
| Guyana          | 1         | 0.3%    |
| Greece          | 1         | 0.3%    |
| Finland         | 1         | 0.3%    |
| Croatia         | 1         | 0.3%    |
| China           | 1         | 0.3%    |
| Barbados        | 1         | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Sydney                 | 7         | 2.08%   |
| Moscow                 | 7         | 2.08%   |
| The Hague              | 4         | 1.19%   |
| St Petersburg          | 4         | 1.19%   |
| Rome                   | 3         | 0.89%   |
| Munich                 | 3         | 0.89%   |
| Istanbul               | 3         | 0.89%   |
| Hamburg                | 3         | 0.89%   |
| Warsaw                 | 2         | 0.6%    |
| Vienna                 | 2         | 0.6%    |
| Tucson                 | 2         | 0.6%    |
| Sao Paulo              | 2         | 0.6%    |
| Santo André           | 2         | 0.6%    |
| Porto                  | 2         | 0.6%    |
| Mumbai                 | 2         | 0.6%    |
| Monza                  | 2         | 0.6%    |
| Montornès del Vallès | 2         | 0.6%    |
| Minsk                  | 2         | 0.6%    |
| Milan                  | 2         | 0.6%    |
| Madrid                 | 2         | 0.6%    |
| Jakarta                | 2         | 0.6%    |
| Islamabad              | 2         | 0.6%    |
| Cologne                | 2         | 0.6%    |
| Chelyabinsk            | 2         | 0.6%    |
| Cankaya                | 2         | 0.6%    |
| Bogor                  | 2         | 0.6%    |
| Bern                   | 2         | 0.6%    |
| Berlin                 | 2         | 0.6%    |
| Belo Horizonte         | 2         | 0.6%    |
| Austin                 | 2         | 0.6%    |
| Antalya                | 2         | 0.6%    |
| Ankara                 | 2         | 0.6%    |
| Zagreb                 | 1         | 0.3%    |
| Ypres                  | 1         | 0.3%    |
| Yaroslavl              | 1         | 0.3%    |
| Wuhan                  | 1         | 0.3%    |
| Wroclaw                | 1         | 0.3%    |
| Wonosari               | 1         | 0.3%    |
| Wolgast                | 1         | 0.3%    |
| Witbank                | 1         | 0.3%    |
| West Bromwich          | 1         | 0.3%    |
| Wervik                 | 1         | 0.3%    |
| Wellington             | 1         | 0.3%    |
| Warrenton              | 1         | 0.3%    |
| Wallerfangen           | 1         | 0.3%    |
| Voronezh               | 1         | 0.3%    |
| Voerde                 | 1         | 0.3%    |
| Vladivostok            | 1         | 0.3%    |
| Vitória da Conquista  | 1         | 0.3%    |
| Vilnius                | 1         | 0.3%    |
| Villa Bosch            | 1         | 0.3%    |
| Vila Nova de Gaia      | 1         | 0.3%    |
| Vigodarzere            | 1         | 0.3%    |
| Vernouillet            | 1         | 0.3%    |
| Vear                   | 1         | 0.3%    |
| Vantaa                 | 1         | 0.3%    |
| Valencia               | 1         | 0.3%    |
| Ulyanovsk              | 1         | 0.3%    |
| Uden                   | 1         | 0.3%    |
| Ubstadt-Weiher         | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 62        | 73     | 15.12%  |
| Seagate                   | 41        | 42     | 10%     |
| WDC                       | 37        | 43     | 9.02%   |
| Toshiba                   | 29        | 29     | 7.07%   |
| SanDisk                   | 27        | 28     | 6.59%   |
| Kingston                  | 24        | 27     | 5.85%   |
| Unknown                   | 20        | 23     | 4.88%   |
| Crucial                   | 17        | 18     | 4.15%   |
| HGST                      | 16        | 17     | 3.9%    |
| Apple                     | 16        | 18     | 3.9%    |
| SK hynix                  | 13        | 14     | 3.17%   |
| Intel                     | 10        | 12     | 2.44%   |
| Hitachi                   | 8         | 8      | 1.95%   |
| Micron Technology         | 6         | 7      | 1.46%   |
| KIOXIA                    | 6         | 7      | 1.46%   |
| A-DATA Technology         | 6         | 6      | 1.46%   |
| Phison                    | 5         | 5      | 1.22%   |
| China                     | 4         | 4      | 0.98%   |
| Silicon Motion            | 3         | 3      | 0.73%   |
| JMicron Technology        | 3         | 3      | 0.73%   |
| Fujitsu                   | 3         | 3      | 0.73%   |
| Unknown                   | 3         | 3      | 0.73%   |
| Transcend                 | 2         | 2      | 0.49%   |
| TO Exter                  | 2         | 2      | 0.49%   |
| OCZ                       | 2         | 3      | 0.49%   |
| LITEON                    | 2         | 2      | 0.49%   |
| KingDian                  | 2         | 2      | 0.49%   |
| FORESEE                   | 2         | 2      | 0.49%   |
| EYOTA                     | 2         | 2      | 0.49%   |
| ZTE                       | 1         | 1      | 0.24%   |
| XPG                       | 1         | 1      | 0.24%   |
| V-GeN                     | 1         | 1      | 0.24%   |
| UMIS                      | 1         | 1      | 0.24%   |
| Timetec                   | 1         | 1      | 0.24%   |
| Teclast                   | 1         | 1      | 0.24%   |
| Team                      | 1         | 1      | 0.24%   |
| Super Talent              | 1         | 1      | 0.24%   |
| Star Drive                | 1         | 1      | 0.24%   |
| Star                      | 1         | 1      | 0.24%   |
| SSSTC                     | 1         | 1      | 0.24%   |
| SSK                       | 1         | 1      | 0.24%   |
| SSDPR-CX                  | 1         | 1      | 0.24%   |
| SPCC                      | 1         | 1      | 0.24%   |
| Smartbuy                  | 1         | 1      | 0.24%   |
| SABRENT                   | 1         | 1      | 0.24%   |
| PNY                       | 1         | 2      | 0.24%   |
| Pichau                    | 1         | 1      | 0.24%   |
| Patriot                   | 1         | 2      | 0.24%   |
| OSCOO                     | 1         | 1      | 0.24%   |
| NGFF                      | 1         | 1      | 0.24%   |
| Netac                     | 1         | 1      | 0.24%   |
| Micron/Crucial Technology | 1         | 1      | 0.24%   |
| MENGMI                    | 1         | 1      | 0.24%   |
| Lite-On                   | 1         | 1      | 0.24%   |
| Lexar                     | 1         | 1      | 0.24%   |
| Leven                     | 1         | 1      | 0.24%   |
| KingSpec                  | 1         | 1      | 0.24%   |
| Kingchuxing               | 1         | 2      | 0.24%   |
| GOODRAM                   | 1         | 1      | 0.24%   |
| faspeed                   | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 9         | 2.14%   |
| Samsung NVMe SSD Drive 512GB            | 9         | 2.14%   |
| Toshiba MQ01ABD100 1TB                  | 7         | 1.67%   |
| SanDisk NVMe SSD Drive 512GB            | 7         | 1.67%   |
| Kingston SA400S37240G 240GB SSD         | 7         | 1.67%   |
| Samsung NVMe SSD Drive 256GB            | 6         | 1.43%   |
| Seagate ST500LT012-1DG142 500GB         | 5         | 1.19%   |
| Unknown MMC Card  64GB                  | 4         | 0.95%   |
| Unknown MMC Card  32GB                  | 4         | 0.95%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 0.95%   |
| Toshiba MQ01ABF050 500GB                | 4         | 0.95%   |
| SK hynix NVMe SSD Drive 256GB           | 4         | 0.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 0.95%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 4         | 0.95%   |
| Intel NVMe SSD Drive 512GB              | 4         | 0.95%   |
| HGST HTS545050A7E680 500GB              | 4         | 0.95%   |
| HGST HTS541010B7E610 1TB                | 4         | 0.95%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 3         | 0.71%   |
| Unknown MMC Card  128GB                 | 3         | 0.71%   |
| Toshiba NVMe SSD Drive 512GB            | 3         | 0.71%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 3         | 0.71%   |
| SK hynix NVMe SSD Drive 512GB           | 3         | 0.71%   |
| SanDisk NVMe SSD Drive 1024GB           | 3         | 0.71%   |
| Samsung SSD 860 EVO 500GB               | 3         | 0.71%   |
| Samsung SSD 860 EVO 250GB               | 3         | 0.71%   |
| Samsung SSD 850 EVO 500GB               | 3         | 0.71%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.71%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 3         | 0.71%   |
| HGST HTS721010A9E630 1TB                | 3         | 0.71%   |
| Unknown                                 | 3         | 0.71%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 2         | 0.48%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 0.48%   |
| TO Exter nal USB 3.0 240GB              | 2         | 0.48%   |
| Seagate ST980811AS 80GB                 | 2         | 0.48%   |
| Seagate ST9750420AS 752GB               | 2         | 0.48%   |
| Seagate ST9500325AS 500GB               | 2         | 0.48%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 0.48%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD     | 2         | 0.48%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD     | 2         | 0.48%   |
| Samsung SSD 850 EVO 120GB               | 2         | 0.48%   |
| Samsung NVMe SSD Drive 500GB            | 2         | 0.48%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 0.48%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD    | 2         | 0.48%   |
| Phison NVMe SSD Drive 512GB             | 2         | 0.48%   |
| Phison NVMe SSD Drive 1TB               | 2         | 0.48%   |
| OCZ VERTEX3 120GB SSD                   | 2         | 0.48%   |
| KIOXIA NVMe SSD Drive 256GB             | 2         | 0.48%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 0.48%   |
| Kingston NVMe SSD Drive 512GB           | 2         | 0.48%   |
| Kingston NVMe SSD Drive 500GB           | 2         | 0.48%   |
| JMicron Tech 250GB                      | 2         | 0.48%   |
| Intel NVMe SSD Drive 1024GB             | 2         | 0.48%   |
| HGST HTS545050A7E380 500GB              | 2         | 0.48%   |
| FORESEE 256GB SSD                       | 2         | 0.48%   |
| Crucial CT480BX500SSD1 480GB            | 2         | 0.48%   |
| Crucial CT240BX500SSD1 240GB            | 2         | 0.48%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 0.48%   |
| Apple SSD SM256C 256GB                  | 2         | 0.48%   |
| Apple SSD SM0512G 500GB                 | 2         | 0.48%   |
| Apple SSD SM0128G 121GB                 | 2         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 41        | 42     | 34.75%  |
| WDC     | 26        | 31     | 22.03%  |
| Toshiba | 21        | 21     | 17.8%   |
| HGST    | 16        | 17     | 13.56%  |
| Hitachi | 8         | 8      | 6.78%   |
| Fujitsu | 3         | 3      | 2.54%   |
| Unknown | 1         | 1      | 0.85%   |
| SABRENT | 1         | 1      | 0.85%   |
| Apple   | 1         | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 39     | 22.73%  |
| Crucial             | 17        | 18     | 11.04%  |
| Kingston            | 16        | 16     | 10.39%  |
| SanDisk             | 13        | 14     | 8.44%   |
| Apple               | 13        | 14     | 8.44%   |
| WDC                 | 7         | 7      | 4.55%   |
| A-DATA Technology   | 5         | 5      | 3.25%   |
| Micron Technology   | 4         | 5      | 2.6%    |
| China               | 4         | 4      | 2.6%    |
| Intel               | 3         | 3      | 1.95%   |
| Transcend           | 2         | 2      | 1.3%    |
| Toshiba             | 2         | 2      | 1.3%    |
| TO Exter            | 2         | 2      | 1.3%    |
| OCZ                 | 2         | 3      | 1.3%    |
| LITEON              | 2         | 2      | 1.3%    |
| FORESEE             | 2         | 2      | 1.3%    |
| Teclast             | 1         | 1      | 0.65%   |
| Team                | 1         | 1      | 0.65%   |
| Super Talent        | 1         | 1      | 0.65%   |
| Star                | 1         | 1      | 0.65%   |
| SPCC                | 1         | 1      | 0.65%   |
| Smartbuy            | 1         | 1      | 0.65%   |
| SK hynix            | 1         | 1      | 0.65%   |
| PNY                 | 1         | 2      | 0.65%   |
| Pichau              | 1         | 1      | 0.65%   |
| Phison              | 1         | 1      | 0.65%   |
| Patriot             | 1         | 2      | 0.65%   |
| NGFF                | 1         | 1      | 0.65%   |
| Netac               | 1         | 1      | 0.65%   |
| MENGMI              | 1         | 1      | 0.65%   |
| Lexar               | 1         | 1      | 0.65%   |
| KingSpec            | 1         | 1      | 0.65%   |
| KingDian            | 1         | 1      | 0.65%   |
| JMicron Technology  | 1         | 1      | 0.65%   |
| GOODRAM             | 1         | 1      | 0.65%   |
| EYOTA               | 1         | 1      | 0.65%   |
| EVM                 | 1         | 1      | 0.65%   |
| Dogfish             | 1         | 1      | 0.65%   |
| Colorful            | 1         | 1      | 0.65%   |
| Apacer              | 1         | 1      | 0.65%   |
| Unknown             | 1         | 1      | 0.65%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 148       | 165    | 37.19%  |
| HDD     | 116       | 125    | 29.15%  |
| NVMe    | 98        | 119    | 24.62%  |
| MMC     | 21        | 23     | 5.28%   |
| Unknown | 15        | 16     | 3.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 241       | 289    | 64.1%   |
| NVMe | 98        | 119    | 26.06%  |
| MMC  | 21        | 23     | 5.59%   |
| SAS  | 16        | 17     | 4.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 190       | 218    | 73.64%  |
| 0.51-1.0   | 60        | 62     | 23.26%  |
| 1.01-2.0   | 7         | 9      | 2.71%   |
| 3.01-4.0   | 1         | 1      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 134       | 40.85%  |
| 251-500        | 90        | 27.44%  |
| 501-1000       | 46        | 14.02%  |
| 51-100         | 27        | 8.23%   |
| 1001-2000      | 14        | 4.27%   |
| 21-50          | 13        | 3.96%   |
| More than 3000 | 1         | 0.3%    |
| 2001-3000      | 1         | 0.3%    |
| 1-20           | 1         | 0.3%    |
| Unknown        | 1         | 0.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 160       | 47.48%  |
| 21-50     | 86        | 25.52%  |
| 51-100    | 38        | 11.28%  |
| 101-250   | 28        | 8.31%   |
| 251-500   | 13        | 3.86%   |
| 501-1000  | 8         | 2.37%   |
| 1001-2000 | 2         | 0.59%   |
| 2001-3000 | 1         | 0.3%    |
| Unknown   | 1         | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB           | 1         | 1      | 16.67%  |
| Seagate ST500LM030-2E717D 500GB  | 1         | 1      | 16.67%  |
| Kingston SV300S37A240G 240GB SSD | 1         | 1      | 16.67%  |
| Kingston SUV400S37480G 480GB SSD | 1         | 1      | 16.67%  |
| Crucial CT512M550SSD3 512GB      | 1         | 1      | 16.67%  |
| Apple SSD SM256C 256GB           | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 2         | 2      | 33.33%  |
| WDC      | 1         | 1      | 16.67%  |
| Seagate  | 1         | 1      | 16.67%  |
| Crucial  | 1         | 1      | 16.67%  |
| Apple    | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 4      | 66.67%  |
| HDD  | 2         | 2      | 33.33%  |

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
| Detected | 292       | 383    | 84.39%  |
| Works    | 48        | 59     | 13.87%  |
| Malfunc  | 6         | 6      | 1.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 229       | 60.9%   |
| AMD                            | 35        | 9.31%   |
| Samsung Electronics            | 33        | 8.78%   |
| SanDisk                        | 17        | 4.52%   |
| SK hynix                       | 12        | 3.19%   |
| Nvidia                         | 10        | 2.66%   |
| Kingston Technology Company    | 9         | 2.39%   |
| Toshiba America Info Systems   | 6         | 1.6%    |
| Phison Electronics             | 5         | 1.33%   |
| KIOXIA                         | 4         | 1.06%   |
| Silicon Motion                 | 3         | 0.8%    |
| Micron Technology              | 2         | 0.53%   |
| Marvell Technology Group       | 2         | 0.53%   |
| Apple                          | 2         | 0.53%   |
| Union Memory (Shenzhen)        | 1         | 0.27%   |
| Solid State Storage Technology | 1         | 0.27%   |
| Realtek Semiconductor          | 1         | 0.27%   |
| Micron/Crucial Technology      | 1         | 0.27%   |
| Lite-On Technology             | 1         | 0.27%   |
| Biwin Storage Technology       | 1         | 0.27%   |
| ADATA Technology               | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 34        | 8.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 31        | 7.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 28        | 7.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 26        | 6.58%   |
| Samsung NVMe SSD Controller 980                                                        | 13        | 3.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 12        | 3.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 12        | 3.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 12        | 3.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 12        | 3.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 9         | 2.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 9         | 2.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 9         | 2.28%   |
| Nvidia MCP79 AHCI Controller                                                           | 8         | 2.03%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 8         | 2.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 7         | 1.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 7         | 1.77%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 6         | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 6         | 1.52%   |
| Intel SSD 660P Series                                                                  | 6         | 1.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 6         | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 1.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 5         | 1.27%   |
| Samsung Electronics SATA controller                                                    | 5         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 5         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 5         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 1.27%   |
| SK hynix Gold P31 SSD                                                                  | 4         | 1.01%   |
| SK hynix BC511                                                                         | 4         | 1.01%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 4         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 4         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 4         | 1.01%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 4         | 1.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 3         | 0.76%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 3         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 0.76%   |
| Phison E12 NVMe Controller                                                             | 3         | 0.76%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 3         | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 0.76%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 0.51%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 2         | 0.51%   |
| SanDisk Non-Volatile memory controller                                                 | 2         | 0.51%   |
| Micron Non-Volatile memory controller                                                  | 2         | 0.51%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 2         | 0.51%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 2         | 0.51%   |
| Kingston Company KC2000 NVMe SSD                                                       | 2         | 0.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.51%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 0.51%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.51%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.51%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.25%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                   | 1         | 0.25%   |
| Solid State Storage Non-Volatile memory controller                                     | 1         | 0.25%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 0.25%   |
| Silicon Motion Non-Volatile memory controller                                          | 1         | 0.25%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.25%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.25%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 0.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 252       | 65.97%  |
| NVMe | 96        | 25.13%  |
| RAID | 19        | 4.97%   |
| IDE  | 15        | 3.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 276       | 84.15%  |
| AMD    | 52        | 15.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 10        | 3.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 2.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 2.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 1.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.52%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 1.22%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 1.22%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.22%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 1.22%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 1.22%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 1.22%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.91%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 3         | 0.91%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.91%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.91%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.91%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 0.91%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.91%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 3         | 0.91%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.91%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.91%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz       | 3         | 0.91%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 0.91%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.61%   |
| Intel Core i7-5650U CPU @ 2.20GHz             | 2         | 0.61%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 2         | 0.61%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.61%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.61%   |
| Intel Core i7-3635QM CPU @ 2.40GHz            | 2         | 0.61%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.61%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.61%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.61%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.61%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 2         | 0.61%   |
| Intel Core i7-2677M CPU @ 1.80GHz             | 2         | 0.61%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 2         | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.61%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.61%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 0.61%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 2         | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.61%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.61%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.61%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.61%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 0.61%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 2         | 0.61%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 81        | 24.7%   |
| Intel Core i7           | 74        | 22.56%  |
| Intel Core i3           | 34        | 10.37%  |
| Intel Celeron           | 25        | 7.62%   |
| Other                   | 23        | 7.01%   |
| Intel Core 2 Duo        | 20        | 6.1%    |
| AMD Ryzen 5             | 17        | 5.18%   |
| Intel Pentium           | 7         | 2.13%   |
| AMD Ryzen 7             | 7         | 2.13%   |
| AMD Ryzen 3             | 4         | 1.22%   |
| AMD A6                  | 4         | 1.22%   |
| Intel Pentium Silver    | 3         | 0.91%   |
| AMD Ryzen 7 PRO         | 3         | 0.91%   |
| AMD A12                 | 3         | 0.91%   |
| AMD A10                 | 3         | 0.91%   |
| Intel Pentium Dual-Core | 2         | 0.61%   |
| Intel Genuine           | 2         | 0.61%   |
| Intel Celeron Dual-Core | 2         | 0.61%   |
| AMD A8                  | 2         | 0.61%   |
| AMD A4                  | 2         | 0.61%   |
| Intel Pentium Dual      | 1         | 0.3%    |
| Intel Core m5           | 1         | 0.3%    |
| Intel Core i9           | 1         | 0.3%    |
| Intel Core 2 Quad       | 1         | 0.3%    |
| Intel Core 2            | 1         | 0.3%    |
| Intel Atom              | 1         | 0.3%    |
| AMD Ryzen 9             | 1         | 0.3%    |
| AMD Ryzen 5 PRO         | 1         | 0.3%    |
| AMD E1                  | 1         | 0.3%    |
| AMD E                   | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 185       | 56.4%   |
| 4      | 110       | 33.54%  |
| 6      | 17        | 5.18%   |
| 8      | 14        | 4.27%   |
| 1      | 2         | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 328       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 244       | 74.39%  |
| 1      | 84        | 25.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 328       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 30        | 9.06%   |
| 0x306a9    | 28        | 8.46%   |
| Unknown    | 22        | 6.65%   |
| 0x806c1    | 16        | 4.83%   |
| 0x306d4    | 16        | 4.83%   |
| 0x1067a    | 16        | 4.83%   |
| 0x40651    | 14        | 4.23%   |
| 0x406e3    | 13        | 3.93%   |
| 0x806e9    | 12        | 3.63%   |
| 0x20655    | 12        | 3.63%   |
| 0x806ec    | 11        | 3.32%   |
| 0xa0652    | 8         | 2.42%   |
| 0x806ea    | 8         | 2.42%   |
| 0x10676    | 8         | 2.42%   |
| 0x706a8    | 7         | 2.11%   |
| 0x506c9    | 6         | 1.81%   |
| 0x406c3    | 6         | 1.81%   |
| 0x306c3    | 6         | 1.81%   |
| 0x08600106 | 6         | 1.81%   |
| 0x08108109 | 6         | 1.81%   |
| 0x706e5    | 5         | 1.51%   |
| 0x20652    | 5         | 1.51%   |
| 0x08608103 | 5         | 1.51%   |
| 0x06006705 | 5         | 1.51%   |
| 0x806eb    | 4         | 1.21%   |
| 0x706a1    | 4         | 1.21%   |
| 0x6fd      | 4         | 1.21%   |
| 0x906ea    | 3         | 0.91%   |
| 0x806c2    | 3         | 0.91%   |
| 0x30678    | 3         | 0.91%   |
| 0x0a50000c | 3         | 0.91%   |
| 0x08108102 | 3         | 0.91%   |
| 0x08101007 | 3         | 0.91%   |
| 0x06001119 | 3         | 0.91%   |
| 0x906ed    | 2         | 0.6%    |
| 0x906e9    | 2         | 0.6%    |
| 0x506e3    | 2         | 0.6%    |
| 0x40661    | 2         | 0.6%    |
| 0x0810100b | 2         | 0.6%    |
| 0x0700010f | 2         | 0.6%    |
| 0x0600611a | 2         | 0.6%    |
| 0xa0660    | 1         | 0.3%    |
| 0x906c0    | 1         | 0.3%    |
| 0x6fb      | 1         | 0.3%    |
| 0x6f2      | 1         | 0.3%    |
| 0x406c4    | 1         | 0.3%    |
| 0x106e5    | 1         | 0.3%    |
| 0x08600104 | 1         | 0.3%    |
| 0x07030105 | 1         | 0.3%    |
| 0x07030104 | 1         | 0.3%    |
| 0x06006704 | 1         | 0.3%    |
| 0x06006110 | 1         | 0.3%    |
| 0x05000029 | 1         | 0.3%    |
| 0x03000027 | 1         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 49        | 14.94%  |
| SandyBridge   | 31        | 9.45%   |
| IvyBridge     | 29        | 8.84%   |
| Penryn        | 24        | 7.32%   |
| Haswell       | 24        | 7.32%   |
| TigerLake     | 20        | 6.1%    |
| Westmere      | 17        | 5.18%   |
| Skylake       | 16        | 4.88%   |
| Broadwell     | 16        | 4.88%   |
| Silvermont    | 11        | 3.35%   |
| Goldmont plus | 11        | 3.35%   |
| Zen 2         | 10        | 3.05%   |
| Excavator     | 10        | 3.05%   |
| Zen+          | 9         | 2.74%   |
| CometLake     | 9         | 2.74%   |
| Goldmont      | 6         | 1.83%   |
| Core          | 6         | 1.83%   |
| Unknown       | 6         | 1.83%   |
| Zen           | 5         | 1.52%   |
| IceLake       | 5         | 1.52%   |
| Zen 3         | 3         | 0.91%   |
| Piledriver    | 3         | 0.91%   |
| Puma          | 2         | 0.61%   |
| Jaguar        | 2         | 0.61%   |
| Tremont       | 1         | 0.3%    |
| Nehalem       | 1         | 0.3%    |
| K10 Llano     | 1         | 0.3%    |
| Bobcat        | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 253       | 61.41%  |
| AMD    | 81        | 19.66%  |
| Nvidia | 78        | 18.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 6.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 6.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 4.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 3.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 3.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 12        | 2.81%   |
| Intel HD Graphics 5500                                                                   | 12        | 2.81%   |
| Intel HD Graphics 620                                                                    | 11        | 2.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 2.58%   |
| AMD Renoir                                                                               | 10        | 2.34%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.11%   |
| Nvidia C79 [GeForce 9400M]                                                               | 8         | 1.87%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.41%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.41%   |
| AMD Lucienne                                                                             | 6         | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.17%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.17%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.94%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.94%   |
| Intel HD Graphics 6000                                                                   | 4         | 0.94%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.94%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.94%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.7%    |
| Intel HD Graphics 500                                                                    | 3         | 0.7%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.7%    |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 3         | 0.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.7%    |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 3         | 0.7%    |
| AMD Cezanne                                                                              | 3         | 0.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.47%   |
| Nvidia TU117M                                                                            | 2         | 0.47%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.47%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.47%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.47%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.47%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.47%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.47%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.47%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 2         | 0.47%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 0.47%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.47%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.47%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 0.47%   |
| Intel HD Graphics 630                                                                    | 2         | 0.47%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 2         | 0.47%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                               | 2         | 0.47%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 172       | 52.44%  |
| Intel + Nvidia | 59        | 17.99%  |
| 1 x AMD        | 49        | 14.94%  |
| Intel + AMD    | 22        | 6.71%   |
| 1 x Nvidia     | 14        | 4.27%   |
| 2 x AMD        | 7         | 2.13%   |
| AMD + Nvidia   | 3         | 0.91%   |
| 2 x Nvidia     | 2         | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 294       | 89.63%  |
| Proprietary | 32        | 9.76%   |
| Unknown     | 2         | 0.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 199       | 60.49%  |
| 0.01-0.5   | 46        | 13.98%  |
| 1.01-2.0   | 40        | 12.16%  |
| 0.51-1.0   | 27        | 8.21%   |
| 3.01-4.0   | 11        | 3.34%   |
| 5.01-6.0   | 5         | 1.52%   |
| 7.01-8.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 66        | 17.69%  |
| LG Display              | 58        | 15.55%  |
| Chimei Innolux          | 46        | 12.33%  |
| BOE                     | 42        | 11.26%  |
| Apple                   | 39        | 10.46%  |
| Samsung Electronics     | 35        | 9.38%   |
| Sharp                   | 9         | 2.41%   |
| Chi Mei Optoelectronics | 9         | 2.41%   |
| Lenovo                  | 8         | 2.14%   |
| PANDA                   | 7         | 1.88%   |
| Dell                    | 7         | 1.88%   |
| Hewlett-Packard         | 6         | 1.61%   |
| Goldstar                | 6         | 1.61%   |
| CSO                     | 4         | 1.07%   |
| Sony                    | 3         | 0.8%    |
| InfoVision              | 3         | 0.8%    |
| AOC                     | 3         | 0.8%    |
| ViewSonic               | 2         | 0.54%   |
| BenQ                    | 2         | 0.54%   |
| Acer                    | 2         | 0.54%   |
| Toshiba                 | 1         | 0.27%   |
| TMX                     | 1         | 0.27%   |
| SANYO                   | 1         | 0.27%   |
| Plain Tree Systems      | 1         | 0.27%   |
| Philips                 | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| Packard Bell            | 1         | 0.27%   |
| LG Philips              | 1         | 0.27%   |
| Konka                   | 1         | 0.27%   |
| JDI                     | 1         | 0.27%   |
| HUAWEI                  | 1         | 0.27%   |
| HJC                     | 1         | 0.27%   |
| EXP                     | 1         | 0.27%   |
| DPL                     | 1         | 0.27%   |
| CPT                     | 1         | 0.27%   |
| Ancor Communications    | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 1.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 1.05%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 4         | 1.05%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 4         | 1.05%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 4         | 1.05%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 3         | 0.79%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.79%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.79%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 3         | 0.79%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 3         | 0.79%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 3         | 0.79%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 3         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.53%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.53%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 2         | 0.53%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.53%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 2         | 0.53%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 0.53%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.53%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch               | 2         | 0.53%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN152D 1920x1080 344x193mm 15.5-inch      | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x174mm 14.0-inch       | 2         | 0.53%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.53%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 2         | 0.53%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 2         | 0.53%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 2         | 0.53%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 2         | 0.53%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                 | 2         | 0.53%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 2         | 0.53%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 2         | 0.53%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1         | 0.26%   |
| ViewSonic VA702b VSC231C 1280x1024 338x270mm 17.0-inch                | 1         | 0.26%   |
| Toshiba TV TSB2019 3840x2160                                          | 1         | 0.26%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.26%   |
| Sony TV SNYA401 1920x1080                                             | 1         | 0.26%   |
| Sony TV SNY9600 1920x540 735x420mm 33.3-inch                          | 1         | 0.26%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.26%   |
| Sharp PN-K321 SHP21DD 3840x2160                                       | 1         | 0.26%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.26%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.26%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.26%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.26%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 141       | 39.61%  |
| 1366x768 (WXGA)    | 113       | 31.74%  |
| 1440x900 (WXGA+)   | 18        | 5.06%   |
| 1600x900 (HD+)     | 16        | 4.49%   |
| 1280x800 (WXGA)    | 16        | 4.49%   |
| 3840x2160 (4K)     | 13        | 3.65%   |
| 2560x1440 (QHD)    | 10        | 2.81%   |
| 3000x2000          | 4         | 1.12%   |
| 2880x1800          | 4         | 1.12%   |
| 1920x1200 (WUXGA)  | 4         | 1.12%   |
| 3200x1800 (QHD+)   | 2         | 0.56%   |
| 2560x1600          | 2         | 0.56%   |
| 2560x1080          | 2         | 0.56%   |
| 1680x1050 (WSXGA+) | 2         | 0.56%   |
| 1280x1024 (SXGA)   | 2         | 0.56%   |
| 3840x2400          | 1         | 0.28%   |
| 3840x1100          | 1         | 0.28%   |
| 3072x1920          | 1         | 0.28%   |
| 1920x540           | 1         | 0.28%   |
| 1920x1280          | 1         | 0.28%   |
| 1400x1050          | 1         | 0.28%   |
| 1280x720 (HD)      | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 142       | 37.77%  |
| 13      | 75        | 19.95%  |
| 14      | 56        | 14.89%  |
| 17      | 24        | 6.38%   |
| 11      | 13        | 3.46%   |
| 27      | 10        | 2.66%   |
| 23      | 10        | 2.66%   |
| 24      | 9         | 2.39%   |
| 12      | 8         | 2.13%   |
| 31      | 4         | 1.06%   |
| 16      | 3         | 0.8%    |
| 84      | 2         | 0.53%   |
| 72      | 2         | 0.53%   |
| 52      | 2         | 0.53%   |
| 34      | 2         | 0.53%   |
| 25      | 2         | 0.53%   |
| 21      | 2         | 0.53%   |
| 18      | 2         | 0.53%   |
| Unknown | 2         | 0.53%   |
| 47      | 1         | 0.27%   |
| 43      | 1         | 0.27%   |
| 33      | 1         | 0.27%   |
| 26      | 1         | 0.27%   |
| 22      | 1         | 0.27%   |
| 20      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 225       | 60.81%  |
| 201-300     | 65        | 17.57%  |
| 501-600     | 29        | 7.84%   |
| 351-400     | 28        | 7.57%   |
| 401-500     | 6         | 1.62%   |
| 601-700     | 4         | 1.08%   |
| 1501-2000   | 4         | 1.08%   |
| 701-800     | 3         | 0.81%   |
| 1001-1500   | 3         | 0.81%   |
| Unknown     | 2         | 0.54%   |
| 901-1000    | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 275       | 81.85%  |
| 16/10   | 47        | 13.99%  |
| 3/2     | 7         | 2.08%   |
| 5/4     | 2         | 0.6%    |
| 21/9    | 2         | 0.6%    |
| 4/3     | 1         | 0.3%    |
| 3.40    | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 141       | 37.8%   |
| 81-90          | 102       | 27.35%  |
| 71-80          | 28        | 7.51%   |
| 121-130        | 18        | 4.83%   |
| 201-250        | 17        | 4.56%   |
| 51-60          | 14        | 3.75%   |
| 301-350        | 10        | 2.68%   |
| 61-70          | 8         | 2.14%   |
| 351-500        | 7         | 1.88%   |
| More than 1000 | 6         | 1.61%   |
| 251-300        | 5         | 1.34%   |
| 141-150        | 4         | 1.07%   |
| 131-140        | 4         | 1.07%   |
| 111-120        | 3         | 0.8%    |
| 501-1000       | 2         | 0.54%   |
| Unknown        | 2         | 0.54%   |
| 151-200        | 1         | 0.27%   |
| 91-100         | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 157       | 42.66%  |
| 101-120       | 124       | 33.7%   |
| 51-100        | 45        | 12.23%  |
| 161-240       | 22        | 5.98%   |
| More than 240 | 14        | 3.8%    |
| 1-50          | 4         | 1.09%   |
| Unknown       | 2         | 0.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 282       | 85.45%  |
| 2     | 39        | 11.82%  |
| 3     | 7         | 2.12%   |
| 4     | 1         | 0.3%    |
| 0     | 1         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 152       | 30.52%  |
| Realtek Semiconductor             | 151       | 30.32%  |
| Qualcomm Atheros                  | 72        | 14.46%  |
| Broadcom                          | 54        | 10.84%  |
| Broadcom Limited                  | 12        | 2.41%   |
| Nvidia                            | 9         | 1.81%   |
| Marvell Technology Group          | 8         | 1.61%   |
| Ralink                            | 6         | 1.2%    |
| TP-Link                           | 5         | 1%      |
| Ralink Technology                 | 3         | 0.6%    |
| Xiaomi                            | 2         | 0.4%    |
| MediaTek                          | 2         | 0.4%    |
| Lenovo                            | 2         | 0.4%    |
| Huawei Technologies               | 2         | 0.4%    |
| Google                            | 2         | 0.4%    |
| ASIX Electronics                  | 2         | 0.4%    |
| Apple                             | 2         | 0.4%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.2%    |
| TRENDnet                          | 1         | 0.2%    |
| Sitecom Europe                    | 1         | 0.2%    |
| Sierra Wireless                   | 1         | 0.2%    |
| Samsung Electronics               | 1         | 0.2%    |
| Qualcomm                          | 1         | 0.2%    |
| OPPO Electronics                  | 1         | 0.2%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.2%    |
| JMicron Technology                | 1         | 0.2%    |
| Hewlett-Packard                   | 1         | 0.2%    |
| Ericsson Business Mobile Networks | 1         | 0.2%    |
| D-Link                            | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 86        | 14.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 5.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 2.85%   |
| Intel Wi-Fi 6 AX201                                               | 16        | 2.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 14        | 2.35%   |
| Intel Wireless 8260                                               | 14        | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 2.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 2.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.68%   |
| Intel Wireless 8265 / 8275                                        | 10        | 1.68%   |
| Nvidia MCP79 Ethernet                                             | 9         | 1.51%   |
| Intel Wireless 7265                                               | 9         | 1.51%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.51%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 9         | 1.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.34%   |
| Intel Wireless 7260                                               | 8         | 1.34%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 1.34%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 8         | 1.34%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 8         | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 1.17%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 7         | 1.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 0.84%   |
| Intel Wireless 3165                                               | 5         | 0.84%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 5         | 0.84%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.84%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 5         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.67%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.67%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 4         | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.5%    |
| Intel Ultimate N WiFi Link 5300                                   | 3         | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.5%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.5%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.5%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 3         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.34%   |
| TP-Link TL-WN722N v2                                              | 2         | 0.34%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.34%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.34%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.34%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 147       | 43.11%  |
| Qualcomm Atheros      | 63        | 18.48%  |
| Broadcom              | 52        | 15.25%  |
| Realtek Semiconductor | 47        | 13.78%  |
| Broadcom Limited      | 11        | 3.23%   |
| Ralink                | 6         | 1.76%   |
| TP-Link               | 5         | 1.47%   |
| Ralink Technology     | 3         | 0.88%   |
| MediaTek              | 2         | 0.59%   |
| TRENDnet              | 1         | 0.29%   |
| Sitecom Europe        | 1         | 0.29%   |
| Sierra Wireless       | 1         | 0.29%   |
| Qualcomm              | 1         | 0.29%   |
| D-Link                | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 17        | 4.96%   |
| Intel Wi-Fi 6 AX201                                                                   | 16        | 4.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 14        | 4.08%   |
| Intel Wireless 8260                                                                   | 14        | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 12        | 3.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 12        | 3.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 11        | 3.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 10        | 2.92%   |
| Intel Wireless 8265 / 8275                                                            | 10        | 2.92%   |
| Intel Wireless 7265                                                                   | 9         | 2.62%   |
| Intel Wi-Fi 6 AX200                                                                   | 9         | 2.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 9         | 2.62%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 9         | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 8         | 2.33%   |
| Intel Wireless 7260                                                                   | 8         | 2.33%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 8         | 2.33%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 8         | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 7         | 2.04%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 7         | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 6         | 1.75%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 6         | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 5         | 1.46%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 5         | 1.46%   |
| Intel Wireless 3165                                                                   | 5         | 1.46%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 5         | 1.46%   |
| Intel Centrino Advanced-N 6200                                                        | 5         | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 5         | 1.46%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 5         | 1.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 4         | 1.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 4         | 1.17%   |
| Intel Centrino Advanced-N 6235                                                        | 4         | 1.17%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 4         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 4         | 1.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 3         | 0.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 0.87%   |
| Intel Ultimate N WiFi Link 5300                                                       | 3         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 3         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 3         | 0.87%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 3         | 0.87%   |
| TP-Link TL-WN722N v2                                                                  | 2         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 2         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 0.58%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2         | 0.58%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 2         | 0.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 2         | 0.58%   |
| Intel Wireless-AC 9260                                                                | 2         | 0.58%   |
| Intel Wireless 3160                                                                   | 2         | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 0.58%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 0.58%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                             | 2         | 0.58%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 2         | 0.58%   |
| Broadcom BCM43227 802.11b/g/n                                                         | 2         | 0.58%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]            | 1         | 0.29%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                   | 1         | 0.29%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.29%   |
| TP-Link 802.11n NIC                                                                   | 1         | 0.29%   |
| Sitecom Europe WL-329 Wireless Dualband USB adapter 300N                              | 1         | 0.29%   |
| Sierra Wireless EM7455                                                                | 1         | 0.29%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 0.29%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 131       | 53.04%  |
| Intel                    | 47        | 19.03%  |
| Qualcomm Atheros         | 19        | 7.69%   |
| Broadcom                 | 16        | 6.48%   |
| Nvidia                   | 9         | 3.64%   |
| Marvell Technology Group | 8         | 3.24%   |
| Xiaomi                   | 2         | 0.81%   |
| Lenovo                   | 2         | 0.81%   |
| Google                   | 2         | 0.81%   |
| Broadcom Limited         | 2         | 0.81%   |
| ASIX Electronics         | 2         | 0.81%   |
| Apple                    | 2         | 0.81%   |
| Samsung Electronics      | 1         | 0.4%    |
| OPPO Electronics         | 1         | 0.4%    |
| JMicron Technology       | 1         | 0.4%    |
| Huawei Technologies      | 1         | 0.4%    |
| Hewlett-Packard          | 1         | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 86        | 34.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 34        | 13.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 4.42%   |
| Nvidia MCP79 Ethernet                                                          | 9         | 3.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 3.21%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 8         | 3.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 2.81%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.61%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 1.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 3         | 1.2%    |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.2%    |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.2%    |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.8%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.8%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.8%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.8%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.8%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.8%    |
| Lenovo ThinkPad Lan                                                            | 2         | 0.8%    |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.8%    |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 0.8%    |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.8%    |
| Google Nexus/Pixel Device (tether)                                             | 2         | 0.8%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.8%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 0.8%    |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.8%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.4%    |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.4%    |
| OPPO 9R                                                                        | 1         | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.4%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.4%    |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.4%    |
| Intel Ethernet Controller I225-V                                               | 1         | 0.4%    |
| Intel Ethernet Connection I219-V                                               | 1         | 0.4%    |
| Intel Ethernet Connection I218-V                                               | 1         | 0.4%    |
| Intel Ethernet Connection I217-V                                               | 1         | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.4%    |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.4%    |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.4%    |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.4%    |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.4%    |
| Huawei JNY-LX1                                                                 | 1         | 0.4%    |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.4%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.4%    |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 0.4%    |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.4%    |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.4%    |
| Apple iPad 4/Mini1                                                             | 1         | 0.4%    |
| Apple iBridge                                                                  | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 326       | 57.39%  |
| Ethernet | 238       | 41.9%   |
| Modem    | 3         | 0.53%   |
| Unknown  | 1         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 275       | 83.08%  |
| Ethernet | 56        | 16.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 220       | 66.87%  |
| 1     | 103       | 31.31%  |
| 0     | 4         | 1.22%   |
| 3     | 2         | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 229       | 69.18%  |
| Yes  | 102       | 30.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 124       | 41.61%  |
| Apple                           | 38        | 12.75%  |
| Realtek Semiconductor           | 30        | 10.07%  |
| Qualcomm Atheros Communications | 22        | 7.38%   |
| Broadcom                        | 17        | 5.7%    |
| Lite-On Technology              | 15        | 5.03%   |
| IMC Networks                    | 13        | 4.36%   |
| Foxconn / Hon Hai               | 11        | 3.69%   |
| Hewlett-Packard                 | 6         | 2.01%   |
| Ralink                          | 5         | 1.68%   |
| Cambridge Silicon Radio         | 5         | 1.68%   |
| Toshiba                         | 4         | 1.34%   |
| Realtek                         | 3         | 1.01%   |
| Dell                            | 3         | 1.01%   |
| ASUSTek Computer                | 2         | 0.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 52        | 17.45%  |
| Intel AX201 Bluetooth                                                               | 28        | 9.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 22        | 7.38%   |
| Apple Bluetooth Host Controller                                                     | 18        | 6.04%   |
| Realtek Bluetooth Radio                                                             | 17        | 5.7%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 4.7%    |
| Apple Bluetooth USB Host Controller                                                 | 12        | 4.03%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 9         | 3.02%   |
| Intel AX200 Bluetooth                                                               | 9         | 3.02%   |
| Ralink RT3290 Bluetooth                                                             | 5         | 1.68%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 1.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.68%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 1.68%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 1.68%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.34%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.34%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 1.34%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 4         | 1.34%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 1.34%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 1.34%   |
| Apple Bluetooth HCI                                                                 | 4         | 1.34%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.01%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.01%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.01%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.01%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 1.01%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.01%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.67%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.67%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.67%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.67%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.67%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.67%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.34%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.34%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.34%   |
| Toshiba Askey for                                                                   | 1         | 0.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.34%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.34%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.34%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.34%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.34%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.34%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.34%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.34%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.34%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.34%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.34%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.34%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.34%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.34%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.34%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 264       | 68.93%  |
| AMD                     | 65        | 16.97%  |
| Nvidia                  | 40        | 10.44%  |
| Logitech                | 2         | 0.52%   |
| ESS Technology          | 2         | 0.52%   |
| C-Media Electronics     | 2         | 0.52%   |
| Texas Instruments       | 1         | 0.26%   |
| SteelSeries ApS         | 1         | 0.26%   |
| Realtek Semiconductor   | 1         | 0.26%   |
| No brand                | 1         | 0.26%   |
| Generalplus Technology  | 1         | 0.26%   |
| Dell                    | 1         | 0.26%   |
| BEHRINGER International | 1         | 0.26%   |
| Apple                   | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 36        | 7.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 6.78%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 32        | 6.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 28        | 5.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 20        | 4.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 3.81%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 3.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 16        | 3.39%   |
| Intel Broadwell-U Audio Controller                                                                | 16        | 3.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 15        | 3.18%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 3.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 14        | 2.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 2.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 12        | 2.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 2.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 2.12%   |
| Nvidia MCP79 High Definition Audio                                                                | 9         | 1.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 1.91%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.69%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 1.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.27%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.06%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.64%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.64%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.64%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.64%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.64%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.42%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.42%   |
| ESS Technology Asus USB DAC                                                                       | 2         | 0.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.42%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.21%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                                                     | 1         | 0.21%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.21%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.21%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.21%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.21%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.21%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.21%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.21%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.21%   |
| No brand CalDigit Thunderbolt 3 Audio                                                             | 1         | 0.21%   |
| Logitech G430 Surround Sound Gaming Headset                                                       | 1         | 0.21%   |
| Logitech 960 Headset                                                                              | 1         | 0.21%   |
| Intel UNA USB audio                                                                               | 1         | 0.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.21%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.21%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 36.36%  |
| SK hynix            | 14        | 21.21%  |
| Micron Technology   | 12        | 18.18%  |
| Unknown (ABCD)      | 2         | 3.03%   |
| Unknown             | 2         | 3.03%   |
| Kingston            | 2         | 3.03%   |
| G.Skill             | 2         | 3.03%   |
| Crucial             | 2         | 3.03%   |
| Transcend           | 1         | 1.52%   |
| SHARETRONIC         | 1         | 1.52%   |
| Ramaxel Technology  | 1         | 1.52%   |
| GSkill              | 1         | 1.52%   |
| Elpida              | 1         | 1.52%   |
| A-DATA Technology   | 1         | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 3         | 4.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 4.05%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 2.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 2.7%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 2.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 2.7%    |
| Unknown RAM Module 8192MB SODIMM DDR3                               | 1         | 1.35%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 1.35%   |
| Transcend RAM JM3200HSE-16G 16384MB SODIMM DDR4 3200MT/s            | 1         | 1.35%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 1         | 1.35%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                   | 1         | 1.35%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 1.35%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1333MT/s                     | 1         | 1.35%   |
| SK hynix RAM HMT851S6AMR6R-PB 4096MB Chip DDR3 1600MT/s             | 1         | 1.35%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.35%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1.35%   |
| SK hynix RAM HMP351S6AFR8C-S6 4096MB SODIMM DDR2 800MT/s            | 1         | 1.35%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 1.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.35%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 1.35%   |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s              | 1         | 1.35%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s          | 1         | 1.35%   |
| SHARETRONIC RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 1.35%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.35%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 1.35%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 1.35%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 1.35%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Samsung RAM M471A5244BB0-CPB 4096MB SODIMM DDR4 2400MT/s            | 1         | 1.35%   |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s               | 1         | 1.35%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s        | 1         | 1.35%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s           | 1         | 1.35%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.35%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 1.35%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.35%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 1         | 1.35%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| Micron RAM MT40A1G16KD-062E:E 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| Micron RAM Module 8192MB SODIMM DDR3 1600MT/s                       | 1         | 1.35%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                       | 1         | 1.35%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 1         | 1.35%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s         | 1         | 1.35%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s         | 1         | 1.35%   |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.35%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 1         | 1.35%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 1         | 1.35%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s               | 1         | 1.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 1         | 1.35%   |
| Kingston RAM KHYXPX-HYJ 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.35%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s               | 1         | 1.35%   |
| GSkill RAM F4-3200C22-8GRS 8192MB SODIMM DDR4 3200MT/s              | 1         | 1.35%   |
| G.Skill RAM F4-2666C18-16GRS 16GB SODIMM DDR4 2667MT/s              | 1         | 1.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 32        | 51.61%  |
| DDR3   | 18        | 29.03%  |
| LPDDR4 | 8         | 12.9%   |
| LPDDR3 | 2         | 3.23%   |
| DDR2   | 2         | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 54        | 87.1%   |
| Row Of Chips | 7         | 11.29%  |
| Chip         | 1         | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 31        | 44.93%  |
| 4096  | 22        | 31.88%  |
| 2048  | 9         | 13.04%  |
| 16384 | 7         | 10.14%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 14        | 21.21%  |
| 3200    | 13        | 19.7%   |
| 2667    | 11        | 16.67%  |
| 2400    | 7         | 10.61%  |
| 4267    | 4         | 6.06%   |
| 8400    | 3         | 4.55%   |
| 2133    | 3         | 4.55%   |
| 3266    | 2         | 3.03%   |
| 1334    | 2         | 3.03%   |
| 1333    | 2         | 3.03%   |
| 4266    | 1         | 1.52%   |
| 1867    | 1         | 1.52%   |
| 800     | 1         | 1.52%   |
| 667     | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Canon                           | 2         | 40%     |
| Samsung Electronics             | 1         | 20%     |
| Prolific Technology             | 1         | 20%     |
| cab Produkttechnik GmbH & Co KG | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung M2020 Series                     | 1         | 20%     |
| Prolific PL2305 Parallel Port            | 1         | 20%     |
| Canon PIXMA MG2500 Series                | 1         | 20%     |
| Canon G3000 series                       | 1         | 20%     |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 20%     |

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
| Chicony Electronics                    | 66        | 21.29%  |
| IMC Networks                           | 37        | 11.94%  |
| Apple                                  | 32        | 10.32%  |
| Realtek Semiconductor                  | 27        | 8.71%   |
| Acer                                   | 23        | 7.42%   |
| Quanta                                 | 21        | 6.77%   |
| Microdia                               | 16        | 5.16%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.52%   |
| Sunplus Innovation Technology          | 13        | 4.19%   |
| Suyin                                  | 12        | 3.87%   |
| Alcor Micro                            | 8         | 2.58%   |
| Syntek                                 | 7         | 2.26%   |
| Silicon Motion                         | 6         | 1.94%   |
| Luxvisions Innotech Limited            | 4         | 1.29%   |
| Lenovo                                 | 4         | 1.29%   |
| Logitech                               | 3         | 0.97%   |
| Ricoh                                  | 2         | 0.65%   |
| Primax Electronics                     | 2         | 0.65%   |
| KYE Systems (Mouse Systems)            | 2         | 0.65%   |
| Foxconn / Hon Hai                      | 2         | 0.65%   |
| Y Media                                | 1         | 0.32%   |
| Unknown                                | 1         | 0.32%   |
| Sony                                   | 1         | 0.32%   |
| Samsung Electronics                    | 1         | 0.32%   |
| Lite-On Technology                     | 1         | 0.32%   |
| kingcome                               | 1         | 0.32%   |
| Importek                               | 1         | 0.32%   |
| Google                                 | 1         | 0.32%   |
| ALi                                    | 1         | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 18        | 5.77%   |
| IMC Networks Integrated Camera                                             | 11        | 3.53%   |
| Apple Built-in iSight                                                      | 11        | 3.53%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 10        | 3.21%   |
| Chicony HD Webcam                                                          | 9         | 2.88%   |
| Apple FaceTime HD Camera                                                   | 8         | 2.56%   |
| Syntek Integrated Camera                                                   | 7         | 2.24%   |
| Realtek Integrated_Webcam_HD                                               | 6         | 1.92%   |
| Microdia Integrated_Webcam_HD                                              | 6         | 1.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 6         | 1.92%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 1.6%    |
| Apple iPhone 5/5C/5S/6/SE                                                  | 5         | 1.6%    |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.28%   |
| Realtek USB2.0 HD UVC WebCam                                               | 4         | 1.28%   |
| Quanta VGA WebCam                                                          | 4         | 1.28%   |
| Quanta HD User Facing                                                      | 4         | 1.28%   |
| Chicony USB 2.0 Camera                                                     | 4         | 1.28%   |
| Apple FaceTime Camera                                                      | 4         | 1.28%   |
| Acer Lenovo EasyCamera                                                     | 4         | 1.28%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 3         | 0.96%   |
| Realtek Integrated Webcam                                                  | 3         | 0.96%   |
| Quanta HP Webcam                                                           | 3         | 0.96%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 3         | 0.96%   |
| Chicony HP HD Webcam [Fixed]                                               | 3         | 0.96%   |
| Alcor Micro USB 2.0 Camera                                                 | 3         | 0.96%   |
| Acer HD Webcam                                                             | 3         | 0.96%   |
| Acer HD Camera                                                             | 3         | 0.96%   |
| Acer EasyCamera                                                            | 3         | 0.96%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 2         | 0.64%   |
| Sunplus ASUS USB2.0 Webcam                                                 | 2         | 0.64%   |
| Realtek USB Camera                                                         | 2         | 0.64%   |
| Realtek Built-In Video Camera                                              | 2         | 0.64%   |
| Realtek Acer 640 x 480 laptop camera                                       | 2         | 0.64%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.64%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 0.64%   |
| Lenovo Integrated Webcam                                                   | 2         | 0.64%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                                 | 2         | 0.64%   |
| IMC Networks ov9734_azurewave_camera                                       | 2         | 0.64%   |
| IMC Networks EasyCamera                                                    | 2         | 0.64%   |
| Foxconn / Hon Hai USB2.0 Camera                                            | 2         | 0.64%   |
| Chicony VGA WebCam                                                         | 2         | 0.64%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.64%   |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 0.64%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 0.64%   |
| Chicony Sony Visual Communication Camera                                   | 2         | 0.64%   |
| Chicony Lenovo EasyCamera                                                  | 2         | 0.64%   |
| Chicony HP TrueVision HD                                                   | 2         | 0.64%   |
| Chicony HP HD Camera                                                       | 2         | 0.64%   |
| Chicony EasyCamera                                                         | 2         | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 2         | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 2         | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 2         | 0.64%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 0.64%   |
| Apple Built-in iSight [Micron]                                             | 2         | 0.64%   |
| Alcor Micro USB 2.0 PC Camera                                              | 2         | 0.64%   |
| Alcor Micro Acer Integrated Webcam                                         | 2         | 0.64%   |
| Acer ThinkPad Integrated Camera                                            | 2         | 0.64%   |
| Acer Integrated Camera                                                     | 2         | 0.64%   |
| Y Media USB Camera                                                         | 1         | 0.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 16        | 32%     |
| Validity Sensors           | 15        | 30%     |
| Shenzhen Goodix Technology | 6         | 12%     |
| LighTuning Technology      | 6         | 12%     |
| Upek                       | 5         | 10%     |
| Elan Microelectronics      | 2         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 10%     |
| Shenzhen Goodix  FingerPrint Device                        | 5         | 10%     |
| Unknown                                                    | 5         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 8%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 4         | 8%      |
| LighTuning EgisTec Touch Fingerprint Sensor                | 4         | 8%      |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 6%      |
| Validity Sensors VFS491                                    | 3         | 6%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 3         | 6%      |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 6%      |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 4%      |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 4%      |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2%      |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2%      |
| Validity Sensors Fingerprint scanner                       | 1         | 2%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2%      |
| Shenzhen Goodix FingerPrint                                | 1         | 2%      |
| Elan ELAN:Fingerprint                                      | 1         | 2%      |
| Elan ELAN:ARM-M4                                           | 1         | 2%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 8         | 47.06%  |
| Alcor Micro           | 5         | 29.41%  |
| Lenovo                | 2         | 11.76%  |
| O2 Micro              | 1         | 5.88%   |
| Gemalto (was Gemplus) | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor         | 5         | 29.41%  |
| Alcor Micro AU9540 Smartcard Reader                    | 5         | 29.41%  |
| Lenovo Integrated Smart Card Reader                    | 2         | 11.76%  |
| Broadcom 58200                                         | 2         | 11.76%  |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 5.88%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 5.88%   |
| Broadcom 5880                                          | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 228       | 69.09%  |
| 1     | 79        | 23.94%  |
| 2     | 22        | 6.67%   |
| 3     | 1         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 50        | 40.32%  |
| Net/wireless          | 17        | 13.71%  |
| Chipcard              | 17        | 13.71%  |
| Multimedia controller | 16        | 12.9%   |
| Graphics card         | 9         | 7.26%   |
| Bluetooth             | 5         | 4.03%   |
| Camera                | 4         | 3.23%   |
| Card reader           | 3         | 2.42%   |
| Net/ethernet          | 2         | 1.61%   |
| Storage               | 1         | 0.81%   |

