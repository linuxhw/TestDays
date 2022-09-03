Elementary - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Elementary.

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

Total: 1015

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | NLx0MU                      | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| Apple         | MacBookPro8,1               | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
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
| Sony          | VPCEB16FG                   | [6baf989163](https://linux-hardware.org/?probe=6baf989163) | Aug 06, 2022 |
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
| HP            | ProBook 430 G2              | [0be149d703](https://linux-hardware.org/?probe=0be149d703) | Jul 16, 2022 |
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
| Lenovo        | V15-IIL 82C5                | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| Toshiba       | Satellite C870-1H2          | [edc5098a6f](https://linux-hardware.org/?probe=edc5098a6f) | Jun 27, 2022 |
| HP            | Pavilion dv5                | [4d0e23962a](https://linux-hardware.org/?probe=4d0e23962a) | Jun 27, 2022 |
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
| Lenovo        | V15-IIL 82C5                | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
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
| HP            | ZBook 15                    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| Apple         | MacBookPro8,2               | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| HP            | EliteBook 8470p             | [d7223d4b03](https://linux-hardware.org/?probe=d7223d4b03) | May 05, 2022 |
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
| Dell          | Latitude 3550               | [6947850074](https://linux-hardware.org/?probe=6947850074) | Apr 14, 2022 |
| HP            | ProBook 440 G7              | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| Panasonic     | CF-31SBLJGDM                | [60a1068658](https://linux-hardware.org/?probe=60a1068658) | Apr 13, 2022 |
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
| LG Electro... | P1-JSUVT                    | [b0e2f9e53c](https://linux-hardware.org/?probe=b0e2f9e53c) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| Toshiba       | Satellite C70D-A            | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| Toshiba       | Satellite L50D-C            | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Dell          | Inspiron MM061              | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| Sony          | SVP1321B4E                  | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | [2d8ab46eed](https://linux-hardware.org/?probe=2d8ab46eed) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | [b1bdc8c7d4](https://linux-hardware.org/?probe=b1bdc8c7d4) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Apple         | MacBookAir7,1               | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| Dell          | Latitude 3550               | [947e147577](https://linux-hardware.org/?probe=947e147577) | Mar 13, 2022 |
| Dell          | Latitude 3550               | [afffe18667](https://linux-hardware.org/?probe=afffe18667) | Mar 13, 2022 |
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
| ASUSTek       | K75VJ                       | [e0c07cf9d2](https://linux-hardware.org/?probe=e0c07cf9d2) | Feb 20, 2022 |
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
| Panasonic     | CF-31SBLJGDM                | [488b80a942](https://linux-hardware.org/?probe=488b80a942) | Feb 03, 2022 |
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
| Dell          | XPS 15 9500                 | [ac78806c22](https://linux-hardware.org/?probe=ac78806c22) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | [657fbc0f6d](https://linux-hardware.org/?probe=657fbc0f6d) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Razer         | Blade Stealth               | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| HP            | Pavilion dv5                | [62a18fa26b](https://linux-hardware.org/?probe=62a18fa26b) | Jan 26, 2022 |
| ASUSTek       | X555LN                      | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| Dell          | Latitude 5420               | [3aad8f46c6](https://linux-hardware.org/?probe=3aad8f46c6) | Jan 24, 2022 |
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
| MSI           | GE60 2PE                    | [d74dcddae6](https://linux-hardware.org/?probe=d74dcddae6) | Jan 13, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| ASUSTek       | GL502VS                     | [feb64c0933](https://linux-hardware.org/?probe=feb64c0933) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| ASUSTek       | UX31A                       | [afe25bb395](https://linux-hardware.org/?probe=afe25bb395) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [7ba01d7327](https://linux-hardware.org/?probe=7ba01d7327) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Dell          | Inspiron N5110              | [172b005a76](https://linux-hardware.org/?probe=172b005a76) | Jan 07, 2022 |
| Dell          | Latitude 5420               | [ab3973e74b](https://linux-hardware.org/?probe=ab3973e74b) | Jan 07, 2022 |
| Dell          | Latitude 5420               | [517adf10a8](https://linux-hardware.org/?probe=517adf10a8) | Jan 06, 2022 |
| Star Labs     | StarBook                    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| Dell          | Inspiron N5110              | [a0a13869ab](https://linux-hardware.org/?probe=a0a13869ab) | Jan 05, 2022 |
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
| Acer          | Aspire XXXX                 | [d52d9dc2bd](https://linux-hardware.org/?probe=d52d9dc2bd) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| Acer          | Aspire XXXX                 | [b5d8962bbc](https://linux-hardware.org/?probe=b5d8962bbc) | Jan 04, 2022 |
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
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fa46d4f41a](https://linux-hardware.org/?probe=fa46d4f41a) | Dec 28, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [22fb358e03](https://linux-hardware.org/?probe=22fb358e03) | Dec 28, 2021 |
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
| Apple         | MacBook2,1                  | [82483b42e2](https://linux-hardware.org/?probe=82483b42e2) | Dec 21, 2021 |
| Apple         | MacBook2,1                  | [197a4e0280](https://linux-hardware.org/?probe=197a4e0280) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| Dell          | Inspiron 5555               | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Lenovo        | V14-ADA 82C6                | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5627f53d66](https://linux-hardware.org/?probe=5627f53d66) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |
| Dell          | Inspiron 1764               | [a8abf45979](https://linux-hardware.org/?probe=a8abf45979) | Dec 13, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Dell          | XPS 15 9570                 | [40b1d83a44](https://linux-hardware.org/?probe=40b1d83a44) | Dec 11, 2021 |
| Star Labs     | StarBook                    | [e9414e6bc4](https://linux-hardware.org/?probe=e9414e6bc4) | Dec 09, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [31e281d91b](https://linux-hardware.org/?probe=31e281d91b) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [d32c954439](https://linux-hardware.org/?probe=d32c954439) | Dec 09, 2021 |
| Google        | Cyan                        | [f49c895086](https://linux-hardware.org/?probe=f49c895086) | Dec 08, 2021 |
| Dell          | Latitude E5420              | [e9fdf365b6](https://linux-hardware.org/?probe=e9fdf365b6) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ed493cd76f](https://linux-hardware.org/?probe=ed493cd76f) | Dec 05, 2021 |
| HUAWEI        | MACHD-WXX9                  | [970669192e](https://linux-hardware.org/?probe=970669192e) | Dec 05, 2021 |
| HP            | G62                         | [6e055d5b6b](https://linux-hardware.org/?probe=6e055d5b6b) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9143857ca7](https://linux-hardware.org/?probe=9143857ca7) | Dec 05, 2021 |
| ASUSTek       | FX503VD                     | [6b5bd7a6d3](https://linux-hardware.org/?probe=6b5bd7a6d3) | Dec 05, 2021 |
| Acer          | Aspire R3-131T              | [3fd499b264](https://linux-hardware.org/?probe=3fd499b264) | Dec 04, 2021 |
| Packard Be... | EasyNote LS11HR             | [d58c199fda](https://linux-hardware.org/?probe=d58c199fda) | Dec 04, 2021 |
| HP            | ZBook 15 G5                 | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| Acer          | Aspire 5750G                | [0131556200](https://linux-hardware.org/?probe=0131556200) | Dec 01, 2021 |
| Samsung       | 550XDA                      | [30c24b17f4](https://linux-hardware.org/?probe=30c24b17f4) | Dec 01, 2021 |
| HP            | EliteBook 2760p             | [d13f27ae75](https://linux-hardware.org/?probe=d13f27ae75) | Nov 30, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5052f33272](https://linux-hardware.org/?probe=5052f33272) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| Google        | Kip                         | [958c198a17](https://linux-hardware.org/?probe=958c198a17) | Nov 29, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [26cba9b931](https://linux-hardware.org/?probe=26cba9b931) | Nov 29, 2021 |
| Toshiba       | Satellite L750              | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | Laptop 15s-fq0xxx           | [8b1d090289](https://linux-hardware.org/?probe=8b1d090289) | Nov 28, 2021 |
| HP            | Pavilion dm4                | [e2c582f687](https://linux-hardware.org/?probe=e2c582f687) | Nov 28, 2021 |
| HP            | ProBook 4540s               | [b6762448da](https://linux-hardware.org/?probe=b6762448da) | Nov 28, 2021 |
| Notebook      | L140CU                      | [59021b2a31](https://linux-hardware.org/?probe=59021b2a31) | Nov 27, 2021 |
| Toshiba       | Satellite L840              | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [c8a72fc7e2](https://linux-hardware.org/?probe=c8a72fc7e2) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | [0004bab911](https://linux-hardware.org/?probe=0004bab911) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | [2ef4f4f273](https://linux-hardware.org/?probe=2ef4f4f273) | Nov 26, 2021 |
| Dell          | Inspiron 15-3573            | [04dc1956ff](https://linux-hardware.org/?probe=04dc1956ff) | Nov 26, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [cd408c48d0](https://linux-hardware.org/?probe=cd408c48d0) | Nov 25, 2021 |
| HP            | Pavilion dv7                | [073367afb1](https://linux-hardware.org/?probe=073367afb1) | Nov 25, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0040... | [94b3c73b50](https://linux-hardware.org/?probe=94b3c73b50) | Nov 25, 2021 |
| Apple         | MacBookPro11,2              | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Dell          | System Inspiron N7110       | [fe6a145b19](https://linux-hardware.org/?probe=fe6a145b19) | Nov 24, 2021 |
| Medion        | E7218                       | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [1bfd5fb612](https://linux-hardware.org/?probe=1bfd5fb612) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| Apple         | MacBookPro12,1              | [4f694a8ba3](https://linux-hardware.org/?probe=4f694a8ba3) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| MSI           | GF72 7RE                    | [8e48a382b9](https://linux-hardware.org/?probe=8e48a382b9) | Nov 21, 2021 |
| Alienware     | 17                          | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Dell          | Vostro 3300                 | [04fc886be3](https://linux-hardware.org/?probe=04fc886be3) | Nov 20, 2021 |
| HP            | ProBook 4730s               | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| Schenker      | X170KM-G                    | [79bb8af2a1](https://linux-hardware.org/?probe=79bb8af2a1) | Nov 19, 2021 |
| HP            | Laptop 15-dy2xxx            | [e49d63158f](https://linux-hardware.org/?probe=e49d63158f) | Nov 19, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [38d8d7827f](https://linux-hardware.org/?probe=38d8d7827f) | Nov 18, 2021 |
| HP            | Compaq 6710b (GB893EA#AB... | [47a6a7a44f](https://linux-hardware.org/?probe=47a6a7a44f) | Nov 17, 2021 |
| Unknown       | Unknown                     | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| Acer          | Aspire 5733Z                | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Acer          | Aspire ES1-571              | [60fef7922d](https://linux-hardware.org/?probe=60fef7922d) | Nov 16, 2021 |
| Dell          | XPS 15 9570                 | [74e99a032e](https://linux-hardware.org/?probe=74e99a032e) | Nov 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [58edd5c8e6](https://linux-hardware.org/?probe=58edd5c8e6) | Nov 14, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| Sony          | SVE15115EN                  | [03cbf5ac5a](https://linux-hardware.org/?probe=03cbf5ac5a) | Nov 11, 2021 |
| HP            | Laptop 17-by3xxx            | [beba4da01c](https://linux-hardware.org/?probe=beba4da01c) | Nov 09, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [e43a236a2c](https://linux-hardware.org/?probe=e43a236a2c) | Nov 06, 2021 |
| Quanta        | TW9/SW9                     | [86643edf2a](https://linux-hardware.org/?probe=86643edf2a) | Nov 06, 2021 |
| ASUSTek       | E502SA                      | [28d4f5e427](https://linux-hardware.org/?probe=28d4f5e427) | Nov 04, 2021 |
| ASUSTek       | K75VJ                       | [9c0bccf601](https://linux-hardware.org/?probe=9c0bccf601) | Nov 01, 2021 |
| HCL Infosy... | HCL ME LAPTOP               | [0db069b4f1](https://linux-hardware.org/?probe=0db069b4f1) | Nov 01, 2021 |
| Fujitsu       | LIFEBOOK U747               | [2b68c16c68](https://linux-hardware.org/?probe=2b68c16c68) | Nov 01, 2021 |
| Dell          | Latitude E6410              | [ba51fc9216](https://linux-hardware.org/?probe=ba51fc9216) | Oct 30, 2021 |
| Lenovo        | ThinkPad X230 23259L3       | [801c1d8af3](https://linux-hardware.org/?probe=801c1d8af3) | Oct 27, 2021 |
| MSI           | Modern 14 B4MW              | [a904daf48d](https://linux-hardware.org/?probe=a904daf48d) | Oct 26, 2021 |
| HP            | ProBook 6460b               | [18f27d1f5c](https://linux-hardware.org/?probe=18f27d1f5c) | Oct 25, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| Apple         | MacBookAir7,2               | [4ce4f8ba78](https://linux-hardware.org/?probe=4ce4f8ba78) | Oct 20, 2021 |
| Google        | Setzer                      | [e9536ccbfb](https://linux-hardware.org/?probe=e9536ccbfb) | Oct 19, 2021 |
| Google        | Setzer                      | [3ba49636ef](https://linux-hardware.org/?probe=3ba49636ef) | Oct 19, 2021 |
| Apple         | MacBookAir7,2               | [370b129f3f](https://linux-hardware.org/?probe=370b129f3f) | Oct 16, 2021 |
| Lenovo        | ThinkPad E470 20H10052IG    | [1342d4ce00](https://linux-hardware.org/?probe=1342d4ce00) | Oct 15, 2021 |
| HP            | Pavilion dv6500             | [dd3c7ef3e7](https://linux-hardware.org/?probe=dd3c7ef3e7) | Oct 14, 2021 |
| HP            | Pavilion dv6500             | [c1c77cf91a](https://linux-hardware.org/?probe=c1c77cf91a) | Oct 14, 2021 |
| Acer          | Aspire ES1-311              | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| ASUSTek       | 1215B                       | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| HP            | EliteBook 8440p             | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| HP            | ProBook 4530s               | [0a725a0b81](https://linux-hardware.org/?probe=0a725a0b81) | Oct 07, 2021 |
| Apple         | MacBookPro7,1               | [644b3b5b60](https://linux-hardware.org/?probe=644b3b5b60) | Oct 04, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| Dell          | XPS 13 9350                 | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c28700cfda](https://linux-hardware.org/?probe=c28700cfda) | Sep 26, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [fbcf277174](https://linux-hardware.org/?probe=fbcf277174) | Sep 26, 2021 |
| Lenovo        | G50-45 80E3                 | [59224ec754](https://linux-hardware.org/?probe=59224ec754) | Sep 26, 2021 |
| Apple         | MacBookPro10,2              | [25c8a26c00](https://linux-hardware.org/?probe=25c8a26c00) | Sep 24, 2021 |
| Toshiba       | Satellite C870-1H2          | [73615204f8](https://linux-hardware.org/?probe=73615204f8) | Sep 23, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c1b8f22fa6](https://linux-hardware.org/?probe=c1b8f22fa6) | Sep 22, 2021 |
| Dell          | Precision M4800             | [736b482dc3](https://linux-hardware.org/?probe=736b482dc3) | Sep 22, 2021 |
| eMachines     | G525                        | [8e8d037369](https://linux-hardware.org/?probe=8e8d037369) | Sep 21, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [9d25d0c5c7](https://linux-hardware.org/?probe=9d25d0c5c7) | Sep 21, 2021 |
| Lenovo        | ThinkPad W700 2758MVG       | [66c8ecbaa1](https://linux-hardware.org/?probe=66c8ecbaa1) | Sep 20, 2021 |
| Dell          | XPS 13 9350                 | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Apple         | MacBookPro10,2              | [0e44f5011a](https://linux-hardware.org/?probe=0e44f5011a) | Sep 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3448B... | [2bec640695](https://linux-hardware.org/?probe=2bec640695) | Sep 20, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d2511347b4](https://linux-hardware.org/?probe=d2511347b4) | Sep 19, 2021 |
| HP            | ENVY 15                     | [ba9a8e1d7a](https://linux-hardware.org/?probe=ba9a8e1d7a) | Sep 19, 2021 |
| Lenovo        | V330-15IKB 81AX             | [9d10bffde2](https://linux-hardware.org/?probe=9d10bffde2) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | [15981e12f3](https://linux-hardware.org/?probe=15981e12f3) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | [bcdb4d552d](https://linux-hardware.org/?probe=bcdb4d552d) | Sep 18, 2021 |
| HP            | ENVY 15                     | [d2d607895f](https://linux-hardware.org/?probe=d2d607895f) | Sep 18, 2021 |
| Alienware     | 17                          | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Acer          | Aspire V3-572G              | [addf12cb05](https://linux-hardware.org/?probe=addf12cb05) | Sep 16, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [0c206818b9](https://linux-hardware.org/?probe=0c206818b9) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| Dell          | Latitude E7440              | [fc9f25eecb](https://linux-hardware.org/?probe=fc9f25eecb) | Sep 14, 2021 |
| Toshiba       | Satellite P100              | [bc5b605920](https://linux-hardware.org/?probe=bc5b605920) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | [591ba7a77c](https://linux-hardware.org/?probe=591ba7a77c) | Sep 12, 2021 |
| Dell          | Inspiron 3583               | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| Acer          | Aspire R3-131T              | [e872ba288e](https://linux-hardware.org/?probe=e872ba288e) | Sep 12, 2021 |
| ASUSTek       | UX303LA                     | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| HP            | Pavilion Notebook           | [f373a049e2](https://linux-hardware.org/?probe=f373a049e2) | Sep 10, 2021 |
| HP            | Pavilion Notebook           | [6e97abfd44](https://linux-hardware.org/?probe=6e97abfd44) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| HP            | Laptop 14-dq1xxx            | [0614925ee7](https://linux-hardware.org/?probe=0614925ee7) | Sep 08, 2021 |
| Gateway       | NV54 Series                 | [fcf57528ed](https://linux-hardware.org/?probe=fcf57528ed) | Sep 08, 2021 |
| Sony          | Serie VJC14                 | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo        | V330-15IKB 81AX             | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| HP            | Laptop 15-bs1xx             | [91ecd39f66](https://linux-hardware.org/?probe=91ecd39f66) | Sep 05, 2021 |
| Medion        | Akoya THE TOUCH 10          | [d49d62a2f5](https://linux-hardware.org/?probe=d49d62a2f5) | Sep 04, 2021 |
| Dell          | Vostro 15-3568              | [9460412d4d](https://linux-hardware.org/?probe=9460412d4d) | Sep 04, 2021 |
| Apple         | MacBookPro8,1               | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| HP            | EliteBook Folio 9470m       | [adbb6a690a](https://linux-hardware.org/?probe=adbb6a690a) | Sep 01, 2021 |
| Dell          | Latitude 3580               | [2befbbba9e](https://linux-hardware.org/?probe=2befbbba9e) | Aug 31, 2021 |
| HP            | Pavilion g6                 | [7dba3c201c](https://linux-hardware.org/?probe=7dba3c201c) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [cf69bd4423](https://linux-hardware.org/?probe=cf69bd4423) | Aug 31, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| Acer          | Aspire E5-573G              | [8c61841633](https://linux-hardware.org/?probe=8c61841633) | Aug 30, 2021 |
| HP            | ProBook 4320s               | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| eMachines     | G525                        | [d64e29475f](https://linux-hardware.org/?probe=d64e29475f) | Aug 29, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Acer          | Aspire A515-51G             | [df0d3e8ac4](https://linux-hardware.org/?probe=df0d3e8ac4) | Aug 26, 2021 |
| HP            | Laptop 17-by3xxx            | [84aa134848](https://linux-hardware.org/?probe=84aa134848) | Aug 25, 2021 |
| Lenovo        | G500 20236                  | [a23cf0d12d](https://linux-hardware.org/?probe=a23cf0d12d) | Aug 22, 2021 |
| HP            | Laptop 15-bs0xx             | [fae546f5cb](https://linux-hardware.org/?probe=fae546f5cb) | Aug 20, 2021 |
| HP            | Laptop 17-by3xxx            | [674068cb21](https://linux-hardware.org/?probe=674068cb21) | Aug 19, 2021 |
| Apple         | MacBookPro9,1               | [e9bec90506](https://linux-hardware.org/?probe=e9bec90506) | Aug 19, 2021 |
| Acer          | Aspire F5-573G              | [9d7628068c](https://linux-hardware.org/?probe=9d7628068c) | Aug 19, 2021 |
| Dell          | System XPS L321X            | [34d7fb6cbb](https://linux-hardware.org/?probe=34d7fb6cbb) | Aug 18, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP            | Notebook                    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP            | Notebook                    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [fa6c69671f](https://linux-hardware.org/?probe=fa6c69671f) | Aug 16, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [54f7c9deec](https://linux-hardware.org/?probe=54f7c9deec) | Aug 14, 2021 |
| Apple         | MacBookPro9,1               | [a6b2c12401](https://linux-hardware.org/?probe=a6b2c12401) | Aug 14, 2021 |
| Dell          | Precision 5760              | [824e5e7dad](https://linux-hardware.org/?probe=824e5e7dad) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | [dcfc87a32f](https://linux-hardware.org/?probe=dcfc87a32f) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | [e354646c04](https://linux-hardware.org/?probe=e354646c04) | Aug 13, 2021 |
| Acer          | Aspire 3810TZ               | [6b7176e5ed](https://linux-hardware.org/?probe=6b7176e5ed) | Aug 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4e6f050b43](https://linux-hardware.org/?probe=4e6f050b43) | Aug 10, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [9b9cd9a995](https://linux-hardware.org/?probe=9b9cd9a995) | Aug 10, 2021 |
| Acer          | Aspire E5-573G              | [caa41076f3](https://linux-hardware.org/?probe=caa41076f3) | Aug 07, 2021 |
| HP            | EliteBook 2570p             | [53c721a204](https://linux-hardware.org/?probe=53c721a204) | Aug 01, 2021 |
| Lenovo        | ThinkPad P50 20ENA00PLM     | [3b6f4346e5](https://linux-hardware.org/?probe=3b6f4346e5) | Jul 29, 2021 |
| Toshiba       | Satellite C850D-119         | [bb3f1b4afa](https://linux-hardware.org/?probe=bb3f1b4afa) | Jul 29, 2021 |
| Toshiba       | Satellite L500              | [76a8d2c20a](https://linux-hardware.org/?probe=76a8d2c20a) | Jul 29, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [75ff3dac2c](https://linux-hardware.org/?probe=75ff3dac2c) | Jul 28, 2021 |
| Dell          | Latitude E5470              | [f26e3c7b39](https://linux-hardware.org/?probe=f26e3c7b39) | Jul 26, 2021 |
| Google        | Cave                        | [e2617f0c2d](https://linux-hardware.org/?probe=e2617f0c2d) | Jul 25, 2021 |
| Dell          | Vostro 3446                 | [566fe43065](https://linux-hardware.org/?probe=566fe43065) | Jul 25, 2021 |
| Dell          | Vostro 3446                 | [9a984d5856](https://linux-hardware.org/?probe=9a984d5856) | Jul 25, 2021 |
| Dell          | Vostro 15-3568              | [9951dfaa86](https://linux-hardware.org/?probe=9951dfaa86) | Jul 24, 2021 |
| Toshiba       | Satellite L500              | [7124417642](https://linux-hardware.org/?probe=7124417642) | Jul 22, 2021 |
| Acer          | Aspire E5-573G              | [a01b8bbea0](https://linux-hardware.org/?probe=a01b8bbea0) | Jul 07, 2021 |
| Google        | Banjo                       | [d451dcd617](https://linux-hardware.org/?probe=d451dcd617) | Jul 02, 2021 |
| HP            | Stream Laptop 14-cb1xxx     | [0447155931](https://linux-hardware.org/?probe=0447155931) | Jul 02, 2021 |
| Acer          | Swift SF314-55G             | [c371b46cbe](https://linux-hardware.org/?probe=c371b46cbe) | Jun 30, 2021 |
| HP            | Pavilion 14                 | [01491528b1](https://linux-hardware.org/?probe=01491528b1) | Jun 28, 2021 |
| Acer          | Aspire E1-570G              | [e72de97e18](https://linux-hardware.org/?probe=e72de97e18) | Jun 25, 2021 |
| ASUSTek       | ZenBook UX481FA_UX481FA     | [675397a7db](https://linux-hardware.org/?probe=675397a7db) | Jun 19, 2021 |
| Acer          | Swift SF315-41              | [8df5e13fc0](https://linux-hardware.org/?probe=8df5e13fc0) | Jun 18, 2021 |
| Acer          | Swift SF314-55G             | [4e5cf8aa1e](https://linux-hardware.org/?probe=4e5cf8aa1e) | Jun 13, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [82e660e88d](https://linux-hardware.org/?probe=82e660e88d) | Jun 12, 2021 |
| Toshiba       | Satellite L500              | [e8589abc23](https://linux-hardware.org/?probe=e8589abc23) | Jun 10, 2021 |
| Toshiba       | Satellite L500              | [b65c50aaf8](https://linux-hardware.org/?probe=b65c50aaf8) | Jun 09, 2021 |
| Toshiba       | Satellite L500              | [6b941d232d](https://linux-hardware.org/?probe=6b941d232d) | Jun 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3f8470a641](https://linux-hardware.org/?probe=3f8470a641) | Jun 02, 2021 |
| Lenovo        | ThinkPad X240 20AMA0XK00    | [8b7ecca1b8](https://linux-hardware.org/?probe=8b7ecca1b8) | Jun 02, 2021 |
| HP            | Presario CQ56               | [70a720b401](https://linux-hardware.org/?probe=70a720b401) | May 31, 2021 |
| HP            | Pavilion g7                 | [6607d7bfd4](https://linux-hardware.org/?probe=6607d7bfd4) | May 28, 2021 |
| HP            | Laptop 17-by3xxx            | [94e12db274](https://linux-hardware.org/?probe=94e12db274) | May 28, 2021 |
| Toshiba       | Satellite L500              | [7bcdcd125f](https://linux-hardware.org/?probe=7bcdcd125f) | May 24, 2021 |
| Toshiba       | Satellite L500              | [c812470c98](https://linux-hardware.org/?probe=c812470c98) | May 22, 2021 |
| Acer          | ConceptD CN315-71P          | [5ecea84320](https://linux-hardware.org/?probe=5ecea84320) | May 15, 2021 |
| HUAWEI        | HLY-WX9XX                   | [96c74bb052](https://linux-hardware.org/?probe=96c74bb052) | May 14, 2021 |
| Dell          | Latitude E6400              | [28c0f73a83](https://linux-hardware.org/?probe=28c0f73a83) | May 12, 2021 |
| LG Electro... | A410-K.BE43P1               | [dd6a1734a8](https://linux-hardware.org/?probe=dd6a1734a8) | May 09, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF0L    | [dc9c7088dd](https://linux-hardware.org/?probe=dc9c7088dd) | May 08, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF0L    | [9cf4893825](https://linux-hardware.org/?probe=9cf4893825) | May 08, 2021 |
| ASUSTek       | K45VD                       | [67e6985b08](https://linux-hardware.org/?probe=67e6985b08) | May 02, 2021 |
| ASUSTek       | K45VD                       | [8624f1c148](https://linux-hardware.org/?probe=8624f1c148) | Apr 30, 2021 |
| Acer          | Aspire F5-573G              | [fdabc1d291](https://linux-hardware.org/?probe=fdabc1d291) | Apr 28, 2021 |
| Acer          | Aspire F5-573G              | [2e2cc93814](https://linux-hardware.org/?probe=2e2cc93814) | Apr 28, 2021 |
| ASUSTek       | X205TAW                     | [91e8c10d9e](https://linux-hardware.org/?probe=91e8c10d9e) | Apr 25, 2021 |
| Acer          | Aspire R3-131T              | [1d52101f3a](https://linux-hardware.org/?probe=1d52101f3a) | Apr 23, 2021 |
| Positivo      | S14SL01                     | [f1cc01bb29](https://linux-hardware.org/?probe=f1cc01bb29) | Apr 22, 2021 |
| Lenovo        | ThinkPad T460 20FMS6C200    | [7f900f8923](https://linux-hardware.org/?probe=7f900f8923) | Apr 20, 2021 |
| Lenovo        | V15-ADA 82C7                | [9065c52996](https://linux-hardware.org/?probe=9065c52996) | Apr 17, 2021 |
| Lenovo        | ThinkPad R61e/R61i 76508... | [e3b2bd3e3a](https://linux-hardware.org/?probe=e3b2bd3e3a) | Apr 14, 2021 |
| HP            | Elite x2 1012 G1            | [09240a2a3f](https://linux-hardware.org/?probe=09240a2a3f) | Apr 13, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [9749184629](https://linux-hardware.org/?probe=9749184629) | Apr 12, 2021 |
| ASUSTek       | K53SC                       | [7cd834c7b9](https://linux-hardware.org/?probe=7cd834c7b9) | Apr 11, 2021 |
| Positivo      | C14CR21                     | [b4ed03e23e](https://linux-hardware.org/?probe=b4ed03e23e) | Apr 11, 2021 |
| Dell          | Inspiron 5458               | [90eb8e7cc2](https://linux-hardware.org/?probe=90eb8e7cc2) | Apr 08, 2021 |
| Lenovo        | ThinkPad W540 20BHS1MX00    | [47cc5eb719](https://linux-hardware.org/?probe=47cc5eb719) | Apr 07, 2021 |
| HP            | Pavilion 15                 | [e2bbdc0f8a](https://linux-hardware.org/?probe=e2bbdc0f8a) | Mar 26, 2021 |
| Fujitsu       | LIFEBOOK AH544              | [60600f6f0c](https://linux-hardware.org/?probe=60600f6f0c) | Mar 26, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | [b3eee9be3e](https://linux-hardware.org/?probe=b3eee9be3e) | Mar 23, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | [e04914d4de](https://linux-hardware.org/?probe=e04914d4de) | Mar 23, 2021 |
| Toshiba       | QOSMIO G55                  | [be88551910](https://linux-hardware.org/?probe=be88551910) | Mar 22, 2021 |
| HP            | ProBook 430 G6              | [29ef42ccfc](https://linux-hardware.org/?probe=29ef42ccfc) | Mar 20, 2021 |
| Toshiba       | QOSMIO G55                  | [35fcfae27e](https://linux-hardware.org/?probe=35fcfae27e) | Mar 19, 2021 |
| Apple         | MacBookPro8,2               | [e87a073ae8](https://linux-hardware.org/?probe=e87a073ae8) | Mar 18, 2021 |
| HP            | EliteBook 840 G3            | [1e31858e51](https://linux-hardware.org/?probe=1e31858e51) | Mar 09, 2021 |
| HP            | 250 G6 Notebook PC          | [0fadf2dbc1](https://linux-hardware.org/?probe=0fadf2dbc1) | Mar 08, 2021 |
| Apple         | MacBookPro5,5               | [9e67aa8a54](https://linux-hardware.org/?probe=9e67aa8a54) | Mar 02, 2021 |
| HP            | Notebook                    | [201023370e](https://linux-hardware.org/?probe=201023370e) | Feb 28, 2021 |
| HP            | Notebook                    | [a1f9deaebe](https://linux-hardware.org/?probe=a1f9deaebe) | Feb 28, 2021 |
| Lenovo        | G50-45 80E3                 | [686e15d925](https://linux-hardware.org/?probe=686e15d925) | Feb 27, 2021 |
| HP            | ProBook 430 G7              | [b4b70424b9](https://linux-hardware.org/?probe=b4b70424b9) | Feb 27, 2021 |
| Lenovo        | ThinkPad E14 20RBS6MD00     | [32fced07f8](https://linux-hardware.org/?probe=32fced07f8) | Feb 25, 2021 |
| Dell          | Vostro 14 5401              | [e6e3289d55](https://linux-hardware.org/?probe=e6e3289d55) | Feb 25, 2021 |
| HP            | ProBook 5330m               | [4a66a57a41](https://linux-hardware.org/?probe=4a66a57a41) | Feb 23, 2021 |
| Compaq        | Presario CQ-23              | [2266878950](https://linux-hardware.org/?probe=2266878950) | Feb 21, 2021 |
| Acer          | V5-131                      | [fb508c9cd9](https://linux-hardware.org/?probe=fb508c9cd9) | Feb 14, 2021 |
| Toshiba       | Satellite P750              | [65db006d0a](https://linux-hardware.org/?probe=65db006d0a) | Feb 12, 2021 |
| Compaq        | Presario CQ-23              | [0303913f3a](https://linux-hardware.org/?probe=0303913f3a) | Feb 10, 2021 |
| Acer          | Aspire A515-54              | [878b85cbc6](https://linux-hardware.org/?probe=878b85cbc6) | Feb 06, 2021 |
| Lenovo        | 3000 G530 4151/200          | [9bccdfbc03](https://linux-hardware.org/?probe=9bccdfbc03) | Feb 05, 2021 |
| Apple         | MacBook7,1                  | [8b201eef4f](https://linux-hardware.org/?probe=8b201eef4f) | Feb 05, 2021 |
| Dell          | XPS 13 7390                 | [69d8376e50](https://linux-hardware.org/?probe=69d8376e50) | Feb 03, 2021 |
| Sony          | VPCF23JFX                   | [6fffecad4a](https://linux-hardware.org/?probe=6fffecad4a) | Feb 02, 2021 |
| HP            | EliteBook 840 G3            | [2ee3bd8ca9](https://linux-hardware.org/?probe=2ee3bd8ca9) | Jan 30, 2021 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [4ce7ac1cce](https://linux-hardware.org/?probe=4ce7ac1cce) | Jan 30, 2021 |
| Acer          | AOD255E                     | [b346230927](https://linux-hardware.org/?probe=b346230927) | Jan 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [c259d42e53](https://linux-hardware.org/?probe=c259d42e53) | Jan 16, 2021 |
| Dell          | G3 3579                     | [888385f26b](https://linux-hardware.org/?probe=888385f26b) | Jan 13, 2021 |
| Dell          | Latitude E6500              | [81ffedd992](https://linux-hardware.org/?probe=81ffedd992) | Jan 13, 2021 |
| Acer          | Swift SF314-54              | [b4bd0c4eec](https://linux-hardware.org/?probe=b4bd0c4eec) | Jan 12, 2021 |
| Dell          | XPS 13 9300                 | [4a241f61c6](https://linux-hardware.org/?probe=4a241f61c6) | Jan 05, 2021 |
| HP            | Laptop 17-by3xxx            | [84272dcaa9](https://linux-hardware.org/?probe=84272dcaa9) | Jan 05, 2021 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [21c0963f18](https://linux-hardware.org/?probe=21c0963f18) | Jan 03, 2021 |
| Star Labs     | Lite                        | [02fa9d26a2](https://linux-hardware.org/?probe=02fa9d26a2) | Jan 03, 2021 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | [7f209f6d03](https://linux-hardware.org/?probe=7f209f6d03) | Dec 31, 2020 |
| Acer          | Aspire R3-131T              | [934454c9c1](https://linux-hardware.org/?probe=934454c9c1) | Dec 29, 2020 |
| Lenovo        | ThinkPad T420 4236M37       | [da2b217109](https://linux-hardware.org/?probe=da2b217109) | Dec 27, 2020 |
| HP            | EliteBook Folio 9470m       | [013db2cd8e](https://linux-hardware.org/?probe=013db2cd8e) | Dec 25, 2020 |
| Apple         | MacBook7,1                  | [8f63e2a0d9](https://linux-hardware.org/?probe=8f63e2a0d9) | Dec 25, 2020 |
| HP            | G42                         | [c2046377dc](https://linux-hardware.org/?probe=c2046377dc) | Dec 25, 2020 |
| Dell          | Latitude E6520              | [01048967fe](https://linux-hardware.org/?probe=01048967fe) | Dec 24, 2020 |
| Apple         | MacBook7,1                  | [5e92b317ef](https://linux-hardware.org/?probe=5e92b317ef) | Dec 24, 2020 |
| Apple         | MacBook2,1                  | [1bae958a19](https://linux-hardware.org/?probe=1bae958a19) | Dec 17, 2020 |
| LG Electro... | R490-G.ARL5RE2              | [58f0c96534](https://linux-hardware.org/?probe=58f0c96534) | Dec 16, 2020 |
| Fujitsu Si... | LIFEBOOK S6410              | [ec54395d4b](https://linux-hardware.org/?probe=ec54395d4b) | Dec 15, 2020 |
| Fujitsu Si... | LIFEBOOK S6410              | [344504a10b](https://linux-hardware.org/?probe=344504a10b) | Dec 15, 2020 |
| Chuwi         | LapBook Pro                 | [602060bbe9](https://linux-hardware.org/?probe=602060bbe9) | Dec 13, 2020 |
| HP            | Pavilion dv7                | [fee310f330](https://linux-hardware.org/?probe=fee310f330) | Dec 13, 2020 |
| Toshiba       | Satellite R630              | [816b966aa8](https://linux-hardware.org/?probe=816b966aa8) | Dec 11, 2020 |
| HP            | 250 G7 Notebook PC          | [0e95ec9f75](https://linux-hardware.org/?probe=0e95ec9f75) | Dec 08, 2020 |
| Unknown       | 1.0                         | [05b0ad54c9](https://linux-hardware.org/?probe=05b0ad54c9) | Dec 07, 2020 |
| HP            | Pavilion dv7                | [332576610a](https://linux-hardware.org/?probe=332576610a) | Dec 06, 2020 |
| Acer          | Aspire E5-411               | [2513d28117](https://linux-hardware.org/?probe=2513d28117) | Dec 02, 2020 |
| HP            | Pavilion Notebook 15-bc5... | [0ef0b89d48](https://linux-hardware.org/?probe=0ef0b89d48) | Dec 01, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [177a2353e0](https://linux-hardware.org/?probe=177a2353e0) | Nov 26, 2020 |
| Apple         | MacBookAir7,2               | [04def4b8c8](https://linux-hardware.org/?probe=04def4b8c8) | Nov 25, 2020 |
| Dell          | Inspiron 3542               | [d7a6b8524d](https://linux-hardware.org/?probe=d7a6b8524d) | Nov 23, 2020 |
| ASUSTek       | X200CA                      | [73a317dd32](https://linux-hardware.org/?probe=73a317dd32) | Nov 21, 2020 |
| ASUSTek       | X200CA                      | [2a86994bf7](https://linux-hardware.org/?probe=2a86994bf7) | Nov 21, 2020 |
| HP            | EliteBook 840 G3            | [b0504dfd39](https://linux-hardware.org/?probe=b0504dfd39) | Nov 21, 2020 |
| ASUSTek       | U31SD                       | [0454faa58e](https://linux-hardware.org/?probe=0454faa58e) | Nov 20, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [25abf7a587](https://linux-hardware.org/?probe=25abf7a587) | Nov 19, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| HP            | Laptop 17-by3xxx            | [4b3fbfd552](https://linux-hardware.org/?probe=4b3fbfd552) | Nov 12, 2020 |
| Lenovo        | ThinkPad T480 20L50007RT    | [284c6ccc22](https://linux-hardware.org/?probe=284c6ccc22) | Nov 10, 2020 |
| Acer          | Aspire E5-475G              | [1d195bfc21](https://linux-hardware.org/?probe=1d195bfc21) | Nov 10, 2020 |
| Apple         | MacBookPro11,2              | [aaa025e278](https://linux-hardware.org/?probe=aaa025e278) | Nov 09, 2020 |
| Acer          | Aspire F5-573G              | [dec186ab5a](https://linux-hardware.org/?probe=dec186ab5a) | Nov 08, 2020 |
| Apple         | MacBookPro11,2              | [c9674438eb](https://linux-hardware.org/?probe=c9674438eb) | Nov 04, 2020 |
| Acer          | AOD255E                     | [b64297fa62](https://linux-hardware.org/?probe=b64297fa62) | Nov 04, 2020 |
| Acer          | AOD255E                     | [3ef6628882](https://linux-hardware.org/?probe=3ef6628882) | Nov 04, 2020 |
| Dell          | Inspiron N5110              | [1a5aef928b](https://linux-hardware.org/?probe=1a5aef928b) | Nov 01, 2020 |
| Toshiba       | Satellite L855              | [4b4e294b37](https://linux-hardware.org/?probe=4b4e294b37) | Oct 28, 2020 |
| Lenovo        | ThinkPad L480 20LSS0GL00    | [7401cec82c](https://linux-hardware.org/?probe=7401cec82c) | Oct 28, 2020 |
| Lenovo        | ThinkPad L480 20LSS0GL00    | [70d33d80bb](https://linux-hardware.org/?probe=70d33d80bb) | Oct 27, 2020 |
| Dell          | MXG061                      | [d3495d4c8b](https://linux-hardware.org/?probe=d3495d4c8b) | Oct 24, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3b60701957](https://linux-hardware.org/?probe=3b60701957) | Oct 23, 2020 |
| Dell          | XPS 13 9370                 | [565653d844](https://linux-hardware.org/?probe=565653d844) | Oct 21, 2020 |
| HP            | Laptop 17-by3xxx            | [2c0288dadd](https://linux-hardware.org/?probe=2c0288dadd) | Oct 20, 2020 |
| HP            | Laptop 17-by3xxx            | [72d9d5cf88](https://linux-hardware.org/?probe=72d9d5cf88) | Oct 20, 2020 |
| Apple         | MacBook5,2                  | [743c634d73](https://linux-hardware.org/?probe=743c634d73) | Oct 10, 2020 |
| Apple         | MacBookPro8,1               | [bdcba0b93e](https://linux-hardware.org/?probe=bdcba0b93e) | Oct 08, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ba00de031e](https://linux-hardware.org/?probe=ba00de031e) | Oct 05, 2020 |
| HP            | Pavilion x2 Detachable      | [d4078124eb](https://linux-hardware.org/?probe=d4078124eb) | Sep 30, 2020 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [ab392f30cb](https://linux-hardware.org/?probe=ab392f30cb) | Sep 30, 2020 |
| Samsung       | 850XBD                      | [0f37b12bcf](https://linux-hardware.org/?probe=0f37b12bcf) | Sep 25, 2020 |
| Samsung       | 850XBD                      | [6d3aecebe1](https://linux-hardware.org/?probe=6d3aecebe1) | Sep 25, 2020 |
| Dell          | Latitude E5440              | [ce030d4ddf](https://linux-hardware.org/?probe=ce030d4ddf) | Sep 21, 2020 |
| Toshiba       | Satellite C55t-A            | [74cf1c0699](https://linux-hardware.org/?probe=74cf1c0699) | Sep 16, 2020 |
| ASUSTek       | X550JX                      | [73576f6c41](https://linux-hardware.org/?probe=73576f6c41) | Sep 09, 2020 |
| HP            | ProBook 6460b               | [dd1da16f74](https://linux-hardware.org/?probe=dd1da16f74) | Sep 06, 2020 |
| Dell          | Inspiron 5565               | [61e0f4dfb2](https://linux-hardware.org/?probe=61e0f4dfb2) | Sep 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [e5e4260a64](https://linux-hardware.org/?probe=e5e4260a64) | Sep 04, 2020 |
| Lenovo        | ThinkPad T480 20L50018US    | [3e3f5cb909](https://linux-hardware.org/?probe=3e3f5cb909) | Sep 04, 2020 |
| Dell          | Latitude E5540              | [7f237410a4](https://linux-hardware.org/?probe=7f237410a4) | Sep 03, 2020 |
| ASUSTek       | X441BA                      | [e244d30598](https://linux-hardware.org/?probe=e244d30598) | Sep 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [51aa00a8f0](https://linux-hardware.org/?probe=51aa00a8f0) | Sep 03, 2020 |
| Acer          | Swift SF313-52              | [c03f9b4cc4](https://linux-hardware.org/?probe=c03f9b4cc4) | Aug 30, 2020 |
| Dell          | Inspiron 3585               | [4c1c8da34d](https://linux-hardware.org/?probe=4c1c8da34d) | Aug 28, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [776a4390b7](https://linux-hardware.org/?probe=776a4390b7) | Aug 26, 2020 |
| HP            | ProBook 650 G2              | [ad27d76a1a](https://linux-hardware.org/?probe=ad27d76a1a) | Aug 25, 2020 |
| Dell          | Latitude E6400              | [097649e115](https://linux-hardware.org/?probe=097649e115) | Aug 25, 2020 |
| Hampoo        | Cherry Trail CR             | [adcbc1af5f](https://linux-hardware.org/?probe=adcbc1af5f) | Aug 25, 2020 |
| Hampoo        | Cherry Trail CR             | [b2a99bdee8](https://linux-hardware.org/?probe=b2a99bdee8) | Aug 25, 2020 |
| ASUSTek       | X501U                       | [11b77977b4](https://linux-hardware.org/?probe=11b77977b4) | Aug 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4dc08dfc6f](https://linux-hardware.org/?probe=4dc08dfc6f) | Aug 22, 2020 |
| HP            | ProBook 450 G7              | [caa355d2ed](https://linux-hardware.org/?probe=caa355d2ed) | Aug 21, 2020 |
| HP            | 250 G4                      | [24615bedce](https://linux-hardware.org/?probe=24615bedce) | Aug 19, 2020 |
| HP            | 250 G4                      | [bdadaddd2d](https://linux-hardware.org/?probe=bdadaddd2d) | Aug 18, 2020 |
| Apple         | MacBook2,1                  | [86447b8ed9](https://linux-hardware.org/?probe=86447b8ed9) | Aug 17, 2020 |
| Apple         | MacBook2,1                  | [e623d56bad](https://linux-hardware.org/?probe=e623d56bad) | Aug 17, 2020 |
| Gigabyte      | AERO 15-WA                  | [1843d38083](https://linux-hardware.org/?probe=1843d38083) | Aug 10, 2020 |
| Apple         | MacBook6,1                  | [8ae138eceb](https://linux-hardware.org/?probe=8ae138eceb) | Aug 10, 2020 |
| Samsung       | 550XBE/350XBE               | [966babe773](https://linux-hardware.org/?probe=966babe773) | Aug 09, 2020 |
| Multilaser    | Legacy                      | [6b7b785276](https://linux-hardware.org/?probe=6b7b785276) | Aug 07, 2020 |
| Lenovo        | ThinkPad L480 20LSS0GL00    | [46ce32a2fc](https://linux-hardware.org/?probe=46ce32a2fc) | Aug 07, 2020 |
| HP            | Laptop 14-cm1xxx            | [95f6d41901](https://linux-hardware.org/?probe=95f6d41901) | Aug 07, 2020 |
| HP            | Laptop 15-bw0xx             | [2b5e91485d](https://linux-hardware.org/?probe=2b5e91485d) | Aug 06, 2020 |
| Compaq        | Presario CQ-17              | [ac398d9c97](https://linux-hardware.org/?probe=ac398d9c97) | Aug 03, 2020 |
| SLIMBOOK      | PROX14                      | [0044fa027b](https://linux-hardware.org/?probe=0044fa027b) | Jul 30, 2020 |
| SLIMBOOK      | PROX14                      | [397ee22840](https://linux-hardware.org/?probe=397ee22840) | Jul 30, 2020 |
| HP            | Pavilion dv4                | [d766e1beec](https://linux-hardware.org/?probe=d766e1beec) | Jul 29, 2020 |
| Samsung       | 300E5M/300E5L               | [a0e2021c07](https://linux-hardware.org/?probe=a0e2021c07) | Jul 28, 2020 |
| Samsung       | RV415                       | [caa13c3be0](https://linux-hardware.org/?probe=caa13c3be0) | Jul 28, 2020 |
| Samsung       | 550P5C/550P7C               | [3a0c368ada](https://linux-hardware.org/?probe=3a0c368ada) | Jul 28, 2020 |
| Samsung       | 550P5C/550P7C               | [edae61756b](https://linux-hardware.org/?probe=edae61756b) | Jul 28, 2020 |
| Samsung       | 550XBE/350XBE               | [9c88ea6dd3](https://linux-hardware.org/?probe=9c88ea6dd3) | Jul 26, 2020 |
| Dell          | Inspiron 1545               | [07f680bbe7](https://linux-hardware.org/?probe=07f680bbe7) | Jul 25, 2020 |
| Lenovo        | ThinkPad T460s 20FAS07N0... | [ff0675addc](https://linux-hardware.org/?probe=ff0675addc) | Jul 24, 2020 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | [cabb74d082](https://linux-hardware.org/?probe=cabb74d082) | Jul 24, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [f9c334513e](https://linux-hardware.org/?probe=f9c334513e) | Jul 24, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [76b07c718b](https://linux-hardware.org/?probe=76b07c718b) | Jul 24, 2020 |
| Acer          | Aspire 5920                 | [ff4b657f4b](https://linux-hardware.org/?probe=ff4b657f4b) | Jul 24, 2020 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | [c9dfec1937](https://linux-hardware.org/?probe=c9dfec1937) | Jul 23, 2020 |
| Apple         | MacBookPro9,2               | [5315a57ecb](https://linux-hardware.org/?probe=5315a57ecb) | Jul 22, 2020 |
| Lenovo        | ThinkPad T430s 2355A17      | [7f15513957](https://linux-hardware.org/?probe=7f15513957) | Jul 22, 2020 |
| Apple         | MacBookPro9,2               | [f8accd81ff](https://linux-hardware.org/?probe=f8accd81ff) | Jul 22, 2020 |
| Apple         | MacBookPro9,2               | [0b515cda0c](https://linux-hardware.org/?probe=0b515cda0c) | Jul 22, 2020 |
| HP            | Laptop 14-bs0xx             | [be0c3117b4](https://linux-hardware.org/?probe=be0c3117b4) | Jul 20, 2020 |
| Sony          | VPCEJ2L1E                   | [2497ad55e0](https://linux-hardware.org/?probe=2497ad55e0) | Jul 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [a6c67b0097](https://linux-hardware.org/?probe=a6c67b0097) | Jul 16, 2020 |
| Dell          | G3 3779                     | [ae6f801440](https://linux-hardware.org/?probe=ae6f801440) | Jul 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [0c9962d0a7](https://linux-hardware.org/?probe=0c9962d0a7) | Jul 15, 2020 |
| Dell          | Studio 1537                 | [f31c6c9d6d](https://linux-hardware.org/?probe=f31c6c9d6d) | Jul 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [38242e89d2](https://linux-hardware.org/?probe=38242e89d2) | Jul 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c4e21ddab2](https://linux-hardware.org/?probe=c4e21ddab2) | Jul 12, 2020 |
| HP            | EliteBook 840 G2            | [c560a5a1db](https://linux-hardware.org/?probe=c560a5a1db) | Jul 10, 2020 |
| Toshiba       | Satellite Pro A30t-C        | [02a72184b0](https://linux-hardware.org/?probe=02a72184b0) | Jul 09, 2020 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [323451d34a](https://linux-hardware.org/?probe=323451d34a) | Jul 07, 2020 |
| Dell          | Inspiron 7460               | [8bcd57a067](https://linux-hardware.org/?probe=8bcd57a067) | Jul 07, 2020 |
| Gigabyte      | AERO 15-WA                  | [450d69870f](https://linux-hardware.org/?probe=450d69870f) | Jul 05, 2020 |
| HP            | Notebook                    | [00ea6d48b8](https://linux-hardware.org/?probe=00ea6d48b8) | Jul 05, 2020 |
| HP            | ProBook 4440s               | [48a7e1a88c](https://linux-hardware.org/?probe=48a7e1a88c) | Jul 05, 2020 |
| Dell          | Inspiron 15-3567            | [43bb18a0ac](https://linux-hardware.org/?probe=43bb18a0ac) | Jul 02, 2020 |
| Acer          | Aspire V5-561G              | [81b19839f7](https://linux-hardware.org/?probe=81b19839f7) | Jul 02, 2020 |
| Lenovo        | B560 43308JG                | [49c13f41dc](https://linux-hardware.org/?probe=49c13f41dc) | Jun 27, 2020 |
| HP            | EliteBook 840 G3            | [b0b718f600](https://linux-hardware.org/?probe=b0b718f600) | Jun 24, 2020 |
| HP            | Presario CQ42               | [0c42983259](https://linux-hardware.org/?probe=0c42983259) | Jun 20, 2020 |
| HP            | Presario CQ42               | [2f4879822f](https://linux-hardware.org/?probe=2f4879822f) | Jun 20, 2020 |
| Dell          | Latitude E6410              | [c7dbb9d3b1](https://linux-hardware.org/?probe=c7dbb9d3b1) | Jun 18, 2020 |
| Fujitsu       | LIFEBOOK AH544              | [f897dd388f](https://linux-hardware.org/?probe=f897dd388f) | Jun 17, 2020 |
| Toshiba       | PORTEGE R600                | [42ccc035f6](https://linux-hardware.org/?probe=42ccc035f6) | Jun 13, 2020 |
| ASUSTek       | UX360CA                     | [9d6a79d7ac](https://linux-hardware.org/?probe=9d6a79d7ac) | Jun 11, 2020 |
| ASUSTek       | UX360CA                     | [24742e9ec9](https://linux-hardware.org/?probe=24742e9ec9) | Jun 11, 2020 |
| HP            | Unknown                     | [b103113bbd](https://linux-hardware.org/?probe=b103113bbd) | Jun 10, 2020 |
| ASUSTek       | GL553VD                     | [aa6d4f78a1](https://linux-hardware.org/?probe=aa6d4f78a1) | Jun 09, 2020 |
| ASUSTek       | GL553VD                     | [cc19d86c6b](https://linux-hardware.org/?probe=cc19d86c6b) | Jun 09, 2020 |
| ASUSTek       | T100TAL                     | [5ae7673d2d](https://linux-hardware.org/?probe=5ae7673d2d) | Jun 07, 2020 |
| HP            | ProBook 4440s               | [730e093bc4](https://linux-hardware.org/?probe=730e093bc4) | Jun 05, 2020 |
| Dell          | Latitude E6420              | [8e9e3e2ffd](https://linux-hardware.org/?probe=8e9e3e2ffd) | Jun 03, 2020 |
| Acer          | Aspire 5750                 | [77efcb16de](https://linux-hardware.org/?probe=77efcb16de) | Jun 03, 2020 |
| HP            | CQ40-713BR                  | [6e25b0216f](https://linux-hardware.org/?probe=6e25b0216f) | Jun 01, 2020 |
| Acer          | Aspire E1-571               | [25ca966875](https://linux-hardware.org/?probe=25ca966875) | Jun 01, 2020 |
| HP            | CQ40-713BR                  | [2a645050a9](https://linux-hardware.org/?probe=2a645050a9) | May 31, 2020 |
| Acer          | Aspire 5750                 | [1c25cbd3cb](https://linux-hardware.org/?probe=1c25cbd3cb) | May 30, 2020 |
| Toshiba       | Satellite P755              | [0b0c292ffe](https://linux-hardware.org/?probe=0b0c292ffe) | May 29, 2020 |
| HP            | ENVY m6-1188ca              | [311d1824f0](https://linux-hardware.org/?probe=311d1824f0) | May 28, 2020 |
| ASUSTek       | T100TAL                     | [736af31ad7](https://linux-hardware.org/?probe=736af31ad7) | May 27, 2020 |
| Gigabyte      | AERO 15-WA                  | [89c6700e0b](https://linux-hardware.org/?probe=89c6700e0b) | May 27, 2020 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [495fcf6c3f](https://linux-hardware.org/?probe=495fcf6c3f) | May 26, 2020 |
| Dell          | Inspiron 13-7378            | [c7d7c0c9d8](https://linux-hardware.org/?probe=c7d7c0c9d8) | May 24, 2020 |
| ASUSTek       | T100TAL                     | [886a3d75b1](https://linux-hardware.org/?probe=886a3d75b1) | May 24, 2020 |
| Dell          | XPS 13 9370                 | [297a1f1aa3](https://linux-hardware.org/?probe=297a1f1aa3) | May 23, 2020 |
| System76      | Galago Pro                  | [803f23bf1e](https://linux-hardware.org/?probe=803f23bf1e) | May 22, 2020 |
| Dell          | Inspiron 13-7359            | [f99d32f311](https://linux-hardware.org/?probe=f99d32f311) | May 22, 2020 |
| Lenovo        | G50-70 20351                | [cf47f460a0](https://linux-hardware.org/?probe=cf47f460a0) | May 19, 2020 |
| Toshiba       | Satellite Z30-A             | [cd39a1dc41](https://linux-hardware.org/?probe=cd39a1dc41) | May 18, 2020 |
| HP            | ProBook 450 G3              | [13a231b2db](https://linux-hardware.org/?probe=13a231b2db) | May 17, 2020 |
| Lenovo        | 3000 G530 4151/200          | [be2cf964e4](https://linux-hardware.org/?probe=be2cf964e4) | May 15, 2020 |
| Lenovo        | ThinkPad X240 20AMS0B400    | [2df726cfbe](https://linux-hardware.org/?probe=2df726cfbe) | May 12, 2020 |
| HP            | Laptop 15-da0xxx            | [3897071746](https://linux-hardware.org/?probe=3897071746) | May 12, 2020 |
| SNS Networ... | JOI Book 150                | [3d61c3722c](https://linux-hardware.org/?probe=3d61c3722c) | May 11, 2020 |
| Toshiba       | Satellite L735              | [1619820d09](https://linux-hardware.org/?probe=1619820d09) | May 11, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [a5fd789088](https://linux-hardware.org/?probe=a5fd789088) | May 10, 2020 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [927efeb75f](https://linux-hardware.org/?probe=927efeb75f) | May 06, 2020 |
| Acer          | Aspire A315-42              | [c8ad593834](https://linux-hardware.org/?probe=c8ad593834) | May 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [8f04d8930a](https://linux-hardware.org/?probe=8f04d8930a) | Apr 30, 2020 |
| Notebook      | W65_67SR                    | [39f0dfaf9f](https://linux-hardware.org/?probe=39f0dfaf9f) | Apr 29, 2020 |
| Timi          | TM1604                      | [364f18ae11](https://linux-hardware.org/?probe=364f18ae11) | Apr 27, 2020 |
| GEO           | GeoBook1M                   | [e04e7a7e9e](https://linux-hardware.org/?probe=e04e7a7e9e) | Apr 27, 2020 |
| Gigabyte      | AERO 15-WA                  | [c1aae28c2e](https://linux-hardware.org/?probe=c1aae28c2e) | Apr 25, 2020 |
| HP            | 15                          | [525101697d](https://linux-hardware.org/?probe=525101697d) | Apr 23, 2020 |
| HP            | Presario F500 (GH835EA#A... | [9e0244765a](https://linux-hardware.org/?probe=9e0244765a) | Apr 21, 2020 |
| Acer          | AO521                       | [1cca471c9c](https://linux-hardware.org/?probe=1cca471c9c) | Apr 21, 2020 |
| Acer          | AO521                       | [d1d3ad78cc](https://linux-hardware.org/?probe=d1d3ad78cc) | Apr 21, 2020 |
| ASUSTek       | T100TAM                     | [74729a8859](https://linux-hardware.org/?probe=74729a8859) | Apr 19, 2020 |
| Packard Be... | EasyNote TJ65               | [150968da88](https://linux-hardware.org/?probe=150968da88) | Apr 18, 2020 |
| Navigator     | ImPad W1102                 | [5cdf6f0873](https://linux-hardware.org/?probe=5cdf6f0873) | Apr 17, 2020 |
| Lenovo        | G50-45 80E3                 | [cf8e5f7bde](https://linux-hardware.org/?probe=cf8e5f7bde) | Apr 13, 2020 |
| Gigabyte      | AERO 15-WA                  | [e85bbe39b6](https://linux-hardware.org/?probe=e85bbe39b6) | Apr 13, 2020 |
| Dell          | Latitude E5450              | [7991e0a25d](https://linux-hardware.org/?probe=7991e0a25d) | Apr 12, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7ccb2aea23](https://linux-hardware.org/?probe=7ccb2aea23) | Apr 06, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [85d1035d69](https://linux-hardware.org/?probe=85d1035d69) | Apr 06, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ec40bcd2c3](https://linux-hardware.org/?probe=ec40bcd2c3) | Apr 06, 2020 |
| HP            | Laptop 17-ca0xxx            | [574bc0dfd9](https://linux-hardware.org/?probe=574bc0dfd9) | Apr 05, 2020 |
| Toshiba       | Satellite C870-1H2          | [19db407f04](https://linux-hardware.org/?probe=19db407f04) | Apr 03, 2020 |
| Acer          | Aspire A315-21              | [e75b2ed51a](https://linux-hardware.org/?probe=e75b2ed51a) | Apr 03, 2020 |
| Lenovo        | ThinkPad T410 2537M82       | [7c71cd5a53](https://linux-hardware.org/?probe=7c71cd5a53) | Mar 30, 2020 |
| Razer         | Blade 15 Mid 2019-Base      | [92973a6d2a](https://linux-hardware.org/?probe=92973a6d2a) | Mar 27, 2020 |
| ASUSTek       | UX305CA                     | [c3ef67f0ed](https://linux-hardware.org/?probe=c3ef67f0ed) | Mar 25, 2020 |
| ASUSTek       | UX305CA                     | [624e23640a](https://linux-hardware.org/?probe=624e23640a) | Mar 24, 2020 |
| Timi          | TM1604                      | [c6ed356cc3](https://linux-hardware.org/?probe=c6ed356cc3) | Mar 24, 2020 |
| Timi          | TM1604                      | [58e14fb67f](https://linux-hardware.org/?probe=58e14fb67f) | Mar 24, 2020 |
| ASUSTek       | UX305CA                     | [029a5e5e9e](https://linux-hardware.org/?probe=029a5e5e9e) | Mar 23, 2020 |
| HP            | ENVY m6-1188ca              | [9b5037aad7](https://linux-hardware.org/?probe=9b5037aad7) | Mar 22, 2020 |
| Dell          | Latitude E5510              | [57ddf19e97](https://linux-hardware.org/?probe=57ddf19e97) | Mar 21, 2020 |
| Acer          | Aspire V3-112P              | [bae212206d](https://linux-hardware.org/?probe=bae212206d) | Mar 14, 2020 |
| Acer          | Aspire V3-112P              | [6636645055](https://linux-hardware.org/?probe=6636645055) | Mar 14, 2020 |
| Toshiba       | Satellite C870-1H2          | [82ccb1451b](https://linux-hardware.org/?probe=82ccb1451b) | Mar 12, 2020 |
| Dell          | Latitude E6510              | [bc7b29779f](https://linux-hardware.org/?probe=bc7b29779f) | Mar 08, 2020 |
| HP            | 15                          | [cb0cf73a5d](https://linux-hardware.org/?probe=cb0cf73a5d) | Mar 04, 2020 |
| HP            | 15                          | [687592ff11](https://linux-hardware.org/?probe=687592ff11) | Mar 04, 2020 |
| Dell          | Latitude 7490               | [d03108116d](https://linux-hardware.org/?probe=d03108116d) | Mar 02, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [853d6382c5](https://linux-hardware.org/?probe=853d6382c5) | Feb 27, 2020 |
| TrekStor      | Primebook P14B              | [b0e6a6c575](https://linux-hardware.org/?probe=b0e6a6c575) | Feb 26, 2020 |
| TrekStor      | Primebook P14B              | [05cd115963](https://linux-hardware.org/?probe=05cd115963) | Feb 26, 2020 |
| Lenovo        | ThinkPad T61 646065G        | [16239c655f](https://linux-hardware.org/?probe=16239c655f) | Feb 25, 2020 |
| Lenovo        | ThinkPad T61 646065G        | [0fccb54722](https://linux-hardware.org/?probe=0fccb54722) | Feb 25, 2020 |
| Lenovo        | Y50-70 20378                | [d4389ea7a1](https://linux-hardware.org/?probe=d4389ea7a1) | Feb 23, 2020 |
| Dell          | Latitude 7490               | [39de737132](https://linux-hardware.org/?probe=39de737132) | Feb 16, 2020 |
| Acer          | Swift SF314-52              | [a94a904626](https://linux-hardware.org/?probe=a94a904626) | Feb 06, 2020 |
| Acer          | Swift SF314-52              | [3a36b26c95](https://linux-hardware.org/?probe=3a36b26c95) | Feb 05, 2020 |
| Acer          | Aspire E1-572G              | [8666044892](https://linux-hardware.org/?probe=8666044892) | Feb 02, 2020 |
| Lenovo        | IdeaPad Y580                | [3bfc93b571](https://linux-hardware.org/?probe=3bfc93b571) | Feb 01, 2020 |
| Acer          | Aspire E1-572G              | [97afa5904a](https://linux-hardware.org/?probe=97afa5904a) | Jan 30, 2020 |
| Dell          | Latitude E5470              | [65eddceddf](https://linux-hardware.org/?probe=65eddceddf) | Jan 29, 2020 |
| Dell          | Latitude E5470              | [f0a1120a51](https://linux-hardware.org/?probe=f0a1120a51) | Jan 27, 2020 |
| Dell          | Latitude E5470              | [6fb212c97d](https://linux-hardware.org/?probe=6fb212c97d) | Jan 24, 2020 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [96c7b6a60e](https://linux-hardware.org/?probe=96c7b6a60e) | Jan 22, 2020 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [0c80291a35](https://linux-hardware.org/?probe=0c80291a35) | Jan 22, 2020 |
| HP            | 15                          | [48a1f927b8](https://linux-hardware.org/?probe=48a1f927b8) | Jan 20, 2020 |
| Positivo      | C14CR01                     | [720ae73c63](https://linux-hardware.org/?probe=720ae73c63) | Jan 19, 2020 |
| Apple         | MacBookAir6,1               | [aa7d2e0bde](https://linux-hardware.org/?probe=aa7d2e0bde) | Jan 18, 2020 |
| Apple         | MacBookAir6,1               | [f68a0740d7](https://linux-hardware.org/?probe=f68a0740d7) | Jan 18, 2020 |
| Lenovo        | V330-15IKB 81AX             | [701f52dd25](https://linux-hardware.org/?probe=701f52dd25) | Jan 17, 2020 |
| Lenovo        | ThinkPad T410 2537CF3       | [15afc8ae52](https://linux-hardware.org/?probe=15afc8ae52) | Jan 15, 2020 |
| MSI           | GF72 8RE                    | [11ba6c28b8](https://linux-hardware.org/?probe=11ba6c28b8) | Jan 13, 2020 |
| Lenovo        | ThinkPad T480s 20L7001PM... | [3413d9a371](https://linux-hardware.org/?probe=3413d9a371) | Jan 09, 2020 |
| MSI           | GF72 8RE                    | [ff9ee83e94](https://linux-hardware.org/?probe=ff9ee83e94) | Jan 09, 2020 |
| HP            | Laptop 15-db0xxx            | [89b485856c](https://linux-hardware.org/?probe=89b485856c) | Jan 04, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [1a2b9c2648](https://linux-hardware.org/?probe=1a2b9c2648) | Jan 03, 2020 |
| Apple         | MacBookAir4,2               | [6dd7d2ef7f](https://linux-hardware.org/?probe=6dd7d2ef7f) | Dec 30, 2019 |
| Lenovo        | G50-45 80E3                 | [afbbbaba46](https://linux-hardware.org/?probe=afbbbaba46) | Dec 27, 2019 |
| Acer          | Aspire E5-571               | [3fd761163b](https://linux-hardware.org/?probe=3fd761163b) | Dec 23, 2019 |
| HP            | G60                         | [afceab74ce](https://linux-hardware.org/?probe=afceab74ce) | Dec 22, 2019 |
| HP            | Laptop 15-db0xxx            | [b3be7a7a95](https://linux-hardware.org/?probe=b3be7a7a95) | Dec 20, 2019 |
| Toshiba       | Satellite R840              | [be4d675b79](https://linux-hardware.org/?probe=be4d675b79) | Dec 10, 2019 |
| Lenovo        | G40-45 80E1                 | [a89268fd79](https://linux-hardware.org/?probe=a89268fd79) | Dec 10, 2019 |
| Lenovo        | ThinkPad T410 2537CF3       | [eae67b72a2](https://linux-hardware.org/?probe=eae67b72a2) | Dec 07, 2019 |
| Acer          | Aspire E1-531               | [d67f2346ca](https://linux-hardware.org/?probe=d67f2346ca) | Dec 07, 2019 |
| Dell          | Latitude E5500              | [d16bf3353e](https://linux-hardware.org/?probe=d16bf3353e) | Dec 06, 2019 |
| Toshiba       | Satellite C850-D2K          | [af0c1d5f3c](https://linux-hardware.org/?probe=af0c1d5f3c) | Dec 03, 2019 |
| ASUSTek       | K55N                        | [fc6e592fb1](https://linux-hardware.org/?probe=fc6e592fb1) | Nov 29, 2019 |
| ASUSTek       | K55N                        | [ada45cb0c7](https://linux-hardware.org/?probe=ada45cb0c7) | Nov 29, 2019 |
| Dell          | Inspiron 1545               | [38cd75718a](https://linux-hardware.org/?probe=38cd75718a) | Nov 29, 2019 |
| Dell          | Inspiron 1545               | [ad80176b34](https://linux-hardware.org/?probe=ad80176b34) | Nov 28, 2019 |
| ASUSTek       | Q502LAB                     | [91c42fa3df](https://linux-hardware.org/?probe=91c42fa3df) | Nov 28, 2019 |
| Dell          | Inspiron 7460               | [ec8eee00c2](https://linux-hardware.org/?probe=ec8eee00c2) | Nov 18, 2019 |
| Fujitsu       | LIFEBOOK P702               | [52882927f1](https://linux-hardware.org/?probe=52882927f1) | Nov 14, 2019 |
| Dell          | Latitude E7240              | [762e161656](https://linux-hardware.org/?probe=762e161656) | Nov 11, 2019 |
| Packard Be... | EasyNote TS11HR             | [d5a8ff7ad1](https://linux-hardware.org/?probe=d5a8ff7ad1) | Nov 09, 2019 |
| Dell          | Vostro 5370                 | [0309425daf](https://linux-hardware.org/?probe=0309425daf) | Nov 04, 2019 |
| HP            | ProBook 640 G1              | [a5379b40dd](https://linux-hardware.org/?probe=a5379b40dd) | Oct 17, 2019 |
| HP            | ZBook Studio G5             | [a6d0cc5da1](https://linux-hardware.org/?probe=a6d0cc5da1) | Oct 12, 2019 |
| Acer          | Aspire ES1-731              | [54afc9d7e6](https://linux-hardware.org/?probe=54afc9d7e6) | Oct 09, 2019 |
| Dell          | Latitude E5450              | [001f6a7015](https://linux-hardware.org/?probe=001f6a7015) | Sep 26, 2019 |
| Dell          | Latitude E5450              | [116078fd22](https://linux-hardware.org/?probe=116078fd22) | Sep 26, 2019 |
| Dell          | Latitude E5450              | [6fef8c47b3](https://linux-hardware.org/?probe=6fef8c47b3) | Sep 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S1EN01    | [a70466fb78](https://linux-hardware.org/?probe=a70466fb78) | Sep 09, 2019 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [57373d8657](https://linux-hardware.org/?probe=57373d8657) | Aug 27, 2019 |
| ASUSTek       | X555LD                      | [8a2f7ccba0](https://linux-hardware.org/?probe=8a2f7ccba0) | Aug 15, 2019 |
| Lenovo        | G500 20236                  | [b278211264](https://linux-hardware.org/?probe=b278211264) | Jul 30, 2019 |
| HUAWEI        | MACH-WX9                    | [5f7a70586e](https://linux-hardware.org/?probe=5f7a70586e) | Jul 27, 2019 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [3e47232411](https://linux-hardware.org/?probe=3e47232411) | Jul 26, 2019 |
| Apple         | MacBookPro9,2               | [7c3288572e](https://linux-hardware.org/?probe=7c3288572e) | Jun 09, 2019 |
| ASUSTek       | K45A                        | [3efe65fa87](https://linux-hardware.org/?probe=3efe65fa87) | May 21, 2019 |
| ASUSTek       | K45A                        | [c0865d5ecf](https://linux-hardware.org/?probe=c0865d5ecf) | May 21, 2019 |
| Lenovo        | ThinkPad X131e 3367A67      | [397d29d2f2](https://linux-hardware.org/?probe=397d29d2f2) | May 21, 2019 |
| Acer          | Aspire VN7-793G             | [ae7c6abcd2](https://linux-hardware.org/?probe=ae7c6abcd2) | May 01, 2019 |
| Acer          | Aspire VN7-793G             | [39fa8c8805](https://linux-hardware.org/?probe=39fa8c8805) | May 01, 2019 |
| HP            | ProBook 470 G4              | [5e83946400](https://linux-hardware.org/?probe=5e83946400) | Apr 12, 2019 |
| ASUSTek       | X555LD                      | [b2aa64a2fd](https://linux-hardware.org/?probe=b2aa64a2fd) | Apr 01, 2019 |
| Samsung       | 300E5K/300E5Q               | [127747c133](https://linux-hardware.org/?probe=127747c133) | Mar 26, 2019 |
| HP            | Laptop 15-bs0xx             | [c6e8248665](https://linux-hardware.org/?probe=c6e8248665) | Mar 23, 2019 |
| HP            | Laptop 15-bs0xx             | [b963a27bbd](https://linux-hardware.org/?probe=b963a27bbd) | Mar 21, 2019 |
| HP            | Laptop 15-bs0xx             | [622f822b31](https://linux-hardware.org/?probe=622f822b31) | Mar 21, 2019 |
| HP            | Laptop 15-bs0xx             | [6441814822](https://linux-hardware.org/?probe=6441814822) | Mar 21, 2019 |
| Samsung       | 530U3C/530U4C/532U3C        | [0802f0777e](https://linux-hardware.org/?probe=0802f0777e) | Mar 09, 2019 |
| Dell          | Inspiron 5567               | [18266bd48a](https://linux-hardware.org/?probe=18266bd48a) | Jan 06, 2019 |
| Lenovo        | IdeaPad G500                | [c50257173c](https://linux-hardware.org/?probe=c50257173c) | Jan 02, 2019 |
| HP            | Pavilion Notebook           | [a0258a201c](https://linux-hardware.org/?probe=a0258a201c) | Nov 27, 2018 |
| Alienware     | 17 R5                       | [e53cebefbb](https://linux-hardware.org/?probe=e53cebefbb) | Nov 18, 2018 |
| Toshiba       | Satellite-L845              | [73e593cc58](https://linux-hardware.org/?probe=73e593cc58) | Nov 16, 2018 |
| Toshiba       | Satellite-L845              | [5bd2c5bdb7](https://linux-hardware.org/?probe=5bd2c5bdb7) | Nov 16, 2018 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [8343c0979f](https://linux-hardware.org/?probe=8343c0979f) | Jul 01, 2018 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [e99b910234](https://linux-hardware.org/?probe=e99b910234) | Jul 01, 2018 |
| ASUSTek       | G550JK                      | [af5510f93b](https://linux-hardware.org/?probe=af5510f93b) | Jun 19, 2018 |
| ASUSTek       | S451LB                      | [ba8f3b9a74](https://linux-hardware.org/?probe=ba8f3b9a74) | May 17, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Elementary 6.1   | 328       | 42.27%  |
| Elementary 5.1.7 | 146       | 18.81%  |
| Elementary 6     | 143       | 18.43%  |
| Elementary 5.0   | 34        | 4.38%   |
| Elementary 5.1.6 | 29        | 3.74%   |
| Elementary 5.1   | 25        | 3.22%   |
| Elementary 5.1.4 | 23        | 2.96%   |
| Elementary 5.1.2 | 16        | 2.06%   |
| Elementary 5.1.3 | 12        | 1.55%   |
| Elementary 5.1.5 | 8         | 1.03%   |
| Elementary 0.4.1 | 8         | 1.03%   |
| Elementary 6.0   | 4         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Elementary | 753       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.11.0-43-generic  | 74        | 9.12%   |
| 5.13.0-28-generic  | 32        | 3.95%   |
| 5.11.0-40-generic  | 32        | 3.95%   |
| 5.13.0-30-generic  | 28        | 3.45%   |
| 5.11.0-41-generic  | 27        | 3.33%   |
| 5.11.0-27-generic  | 27        | 3.33%   |
| 5.13.0-27-generic  | 24        | 2.96%   |
| 5.4.0-42-generic   | 21        | 2.59%   |
| 5.15.0-41-generic  | 20        | 2.47%   |
| 5.3.0-62-generic   | 19        | 2.34%   |
| 5.11.0-38-generic  | 19        | 2.34%   |
| 5.13.0-39-generic  | 16        | 1.97%   |
| 5.11.0-37-generic  | 16        | 1.97%   |
| 5.13.0-40-generic  | 15        | 1.85%   |
| 5.15.0-46-generic  | 13        | 1.6%    |
| 5.13.0-35-generic  | 13        | 1.6%    |
| 5.11.0-44-generic  | 13        | 1.6%    |
| 5.3.0-51-generic   | 12        | 1.48%   |
| 5.13.0-37-generic  | 12        | 1.48%   |
| 5.0.0-37-generic   | 12        | 1.48%   |
| 5.3.0-53-generic   | 11        | 1.36%   |
| 5.15.0-43-generic  | 11        | 1.36%   |
| 5.11.0-34-generic  | 11        | 1.36%   |
| 5.11.0-25-generic  | 11        | 1.36%   |
| 5.4.0-65-generic   | 10        | 1.23%   |
| 5.13.0-52-generic  | 10        | 1.23%   |
| 5.13.0-41-generic  | 10        | 1.23%   |
| 5.11.0-46-generic  | 10        | 1.23%   |
| 5.4.0-58-generic   | 9         | 1.11%   |
| 5.4.0-52-generic   | 9         | 1.11%   |
| 5.13.0-51-generic  | 8         | 0.99%   |
| 5.4.0-73-generic   | 7         | 0.86%   |
| 5.4.0-56-generic   | 7         | 0.86%   |
| 5.13.0-44-generic  | 7         | 0.86%   |
| 5.4.0-80-generic   | 6         | 0.74%   |
| 5.4.0-72-generic   | 6         | 0.74%   |
| 5.3.0-59-generic   | 6         | 0.74%   |
| 5.3.0-45-generic   | 6         | 0.74%   |
| 5.3.0-42-generic   | 6         | 0.74%   |
| 5.13.0-48-generic  | 6         | 0.74%   |
| 5.4.0-66-generic   | 5         | 0.62%   |
| 5.4.0-48-generic   | 5         | 0.62%   |
| 5.3.0-46-generic   | 5         | 0.62%   |
| 5.3.0-28-generic   | 5         | 0.62%   |
| 4.15.0-66-generic  | 5         | 0.62%   |
| 4.15.0-36-generic  | 5         | 0.62%   |
| 5.4.0-81-generic   | 4         | 0.49%   |
| 5.4.0-70-generic   | 4         | 0.49%   |
| 5.4.0-54-generic   | 4         | 0.49%   |
| 5.3.0-40-generic   | 4         | 0.49%   |
| 5.3.0-26-generic   | 4         | 0.49%   |
| 4.15.0-72-generic  | 4         | 0.49%   |
| 5.4.0-74-generic   | 3         | 0.37%   |
| 5.4.0-67-generic   | 3         | 0.37%   |
| 5.4.0-64-generic   | 3         | 0.37%   |
| 5.4.0-60-generic   | 3         | 0.37%   |
| 5.4.0-47-generic   | 3         | 0.37%   |
| 4.15.0-70-generic  | 3         | 0.37%   |
| 4.15.0-43-generic  | 3         | 0.37%   |
| 4.15.0-112-generic | 3         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 235       | 30.28%  |
| 5.13.0  | 172       | 22.16%  |
| 5.4.0   | 134       | 17.27%  |
| 5.3.0   | 77        | 9.92%   |
| 4.15.0  | 57        | 7.35%   |
| 5.15.0  | 42        | 5.41%   |
| 5.0.0   | 15        | 1.93%   |
| 5.8.0   | 8         | 1.03%   |
| 5.10.0  | 3         | 0.39%   |
| 4.13.0  | 3         | 0.39%   |
| 5.14.0  | 2         | 0.26%   |
| 5.9.1   | 1         | 0.13%   |
| 5.8.5   | 1         | 0.13%   |
| 5.8.13  | 1         | 0.13%   |
| 5.6.2   | 1         | 0.13%   |
| 5.6.19  | 1         | 0.13%   |
| 5.6.14  | 1         | 0.13%   |
| 5.5.8   | 1         | 0.13%   |
| 5.5.6   | 1         | 0.13%   |
| 5.4.1   | 1         | 0.13%   |
| 5.3.6   | 1         | 0.13%   |
| 5.3.11  | 1         | 0.13%   |
| 5.19.3  | 1         | 0.13%   |
| 5.18.3  | 1         | 0.13%   |
| 5.16.16 | 1         | 0.13%   |
| 5.16.10 | 1         | 0.13%   |
| 5.16.0  | 1         | 0.13%   |
| 5.15.5  | 1         | 0.13%   |
| 5.15.36 | 1         | 0.13%   |
| 5.15.3  | 1         | 0.13%   |
| 5.15.21 | 1         | 0.13%   |
| 5.15.13 | 1         | 0.13%   |
| 5.15.12 | 1         | 0.13%   |
| 5.15.11 | 1         | 0.13%   |
| 5.14.9  | 1         | 0.13%   |
| 5.14.7  | 1         | 0.13%   |
| 5.14.10 | 1         | 0.13%   |
| 5.10.4  | 1         | 0.13%   |
| 4.10.0  | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 235       | 30.4%   |
| 5.13    | 172       | 22.25%  |
| 5.4     | 135       | 17.46%  |
| 5.3     | 79        | 10.22%  |
| 4.15    | 57        | 7.37%   |
| 5.15    | 49        | 6.34%   |
| 5.0     | 15        | 1.94%   |
| 5.8     | 10        | 1.29%   |
| 5.14    | 5         | 0.65%   |
| 5.10    | 4         | 0.52%   |
| 4.13    | 3         | 0.39%   |
| 5.5     | 2         | 0.26%   |
| 5.16    | 2         | 0.26%   |
| 5.9     | 1         | 0.13%   |
| 5.6     | 1         | 0.13%   |
| 5.19    | 1         | 0.13%   |
| 5.18    | 1         | 0.13%   |
| 4.10    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 753       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pantheon      | 686       | 90.14%  |
| Unknown       | 59        | 7.75%   |
| GNOME         | 8         | 1.05%   |
| X-Cinnamon    | 4         | 0.53%   |
| XFCE          | 1         | 0.13%   |
| Unity         | 1         | 0.13%   |
| GNOME Classic | 1         | 0.13%   |
| Budgie        | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 752       | 99.87%  |
| Unknown | 1         | 0.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 593       | 78.13%  |
| LightDM | 113       | 14.89%  |
| TDM     | 49        | 6.46%   |
| GDM     | 4         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 322       | 42.54%  |
| de_DE   | 66        | 8.72%   |
| es_ES   | 46        | 6.08%   |
| pt_BR   | 42        | 5.55%   |
| en_GB   | 38        | 5.02%   |
| ru_RU   | 37        | 4.89%   |
| Unknown | 33        | 4.36%   |
| fr_FR   | 23        | 3.04%   |
| it_IT   | 22        | 2.91%   |
| en_AU   | 15        | 1.98%   |
| pl_PL   | 14        | 1.85%   |
| en_CA   | 10        | 1.32%   |
| pt_PT   | 9         | 1.19%   |
| en_IN   | 9         | 1.19%   |
| nl_NL   | 7         | 0.92%   |
| tr_TR   | 6         | 0.79%   |
| hu_HU   | 6         | 0.79%   |
| cs_CZ   | 5         | 0.66%   |
| es_MX   | 4         | 0.53%   |
| zh_CN   | 3         | 0.4%    |
| es_EC   | 3         | 0.4%    |
| en_ZA   | 3         | 0.4%    |
| uk_UA   | 2         | 0.26%   |
| nb_NO   | 2         | 0.26%   |
| id_ID   | 2         | 0.26%   |
| es_CL   | 2         | 0.26%   |
| es_AR   | 2         | 0.26%   |
| de_CH   | 2         | 0.26%   |
| zh_TW   | 1         | 0.13%   |
| vi_VN   | 1         | 0.13%   |
| sv_SE   | 1         | 0.13%   |
| ru_UA   | 1         | 0.13%   |
| ro_RO   | 1         | 0.13%   |
| hr_HR   | 1         | 0.13%   |
| gl_ES   | 1         | 0.13%   |
| fr_CH   | 1         | 0.13%   |
| fr_CA   | 1         | 0.13%   |
| fi_FI   | 1         | 0.13%   |
| et_EE   | 1         | 0.13%   |
| es_UY   | 1         | 0.13%   |
| es_PE   | 1         | 0.13%   |
| es_CO   | 1         | 0.13%   |
| en_PH   | 1         | 0.13%   |
| el_GR   | 1         | 0.13%   |
| de_IT   | 1         | 0.13%   |
| de_AT   | 1         | 0.13%   |
| da_DK   | 1         | 0.13%   |
| ca_ES   | 1         | 0.13%   |
| C       | 1         | 0.13%   |
| bg_BG   | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 479       | 63.19%  |
| BIOS | 279       | 36.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 714       | 94.69%  |
| Overlay | 16        | 2.12%   |
| Unknown | 12        | 1.59%   |
| Btrfs   | 11        | 1.46%   |
| Ext3    | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 626       | 82.8%   |
| GPT     | 103       | 13.62%  |
| MBR     | 27        | 3.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 723       | 96.02%  |
| Yes       | 30        | 3.98%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 660       | 87.19%  |
| Yes       | 97        | 12.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 148       | 19.65%  |
| Hewlett-Packard         | 142       | 18.86%  |
| Dell                    | 96        | 12.75%  |
| ASUSTek Computer        | 79        | 10.49%  |
| Acer                    | 67        | 8.9%    |
| Apple                   | 66        | 8.76%   |
| Toshiba                 | 25        | 3.32%   |
| Samsung Electronics     | 17        | 2.26%   |
| Sony                    | 13        | 1.73%   |
| HUAWEI                  | 13        | 1.73%   |
| MSI                     | 10        | 1.33%   |
| Notebook                | 5         | 0.66%   |
| Google                  | 5         | 0.66%   |
| Star Labs               | 4         | 0.53%   |
| LG Electronics          | 4         | 0.53%   |
| Fujitsu                 | 4         | 0.53%   |
| Timi                    | 3         | 0.4%    |
| Packard Bell            | 3         | 0.4%    |
| Medion                  | 3         | 0.4%    |
| Compaq                  | 3         | 0.4%    |
| TUXEDO                  | 2         | 0.27%   |
| TrekStor                | 2         | 0.27%   |
| Teclast                 | 2         | 0.27%   |
| Razer                   | 2         | 0.27%   |
| Positivo                | 2         | 0.27%   |
| Monster                 | 2         | 0.27%   |
| eMachines               | 2         | 0.27%   |
| Alienware               | 2         | 0.27%   |
| Unknown                 | 2         | 0.27%   |
| Wortmann AG             | 1         | 0.13%   |
| System76                | 1         | 0.13%   |
| Standard                | 1         | 0.13%   |
| SNS Network (M)         | 1         | 0.13%   |
| SLIMBOOK                | 1         | 0.13%   |
| Schenker                | 1         | 0.13%   |
| Quanta                  | 1         | 0.13%   |
| PIPO                    | 1         | 0.13%   |
| Panasonic               | 1         | 0.13%   |
| Navigator               | 1         | 0.13%   |
| Multilaser              | 1         | 0.13%   |
| Mediacom                | 1         | 0.13%   |
| iOTA                    | 1         | 0.13%   |
| HCL Infosystems Limited | 1         | 0.13%   |
| Hampoo                  | 1         | 0.13%   |
| Gigabyte Technology     | 1         | 0.13%   |
| GEO                     | 1         | 0.13%   |
| Gateway                 | 1         | 0.13%   |
| Fujitsu Siemens         | 1         | 0.13%   |
| Complet                 | 1         | 0.13%   |
| Clevo                   | 1         | 0.13%   |
| Chuwi                   | 1         | 0.13%   |
| Casper                  | 1         | 0.13%   |
| Avell High Performance  | 1         | 0.13%   |
| AMI                     | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP Notebook                   | 6         | 0.8%    |
| Apple MacBookPro8,2           | 5         | 0.66%   |
| Apple MacBookAir7,2           | 5         | 0.66%   |
| Lenovo G50-45 80E3            | 4         | 0.53%   |
| HP Laptop 15-bs0xx            | 4         | 0.53%   |
| ASUS ZenBook UX425EA_UX425EA  | 4         | 0.53%   |
| Apple MacBookPro8,1           | 4         | 0.53%   |
| Apple MacBookAir4,2           | 4         | 0.53%   |
| Apple MacBook5,1              | 4         | 0.53%   |
| Unknown                       | 4         | 0.53%   |
| HUAWEI MACHD-WXX9             | 3         | 0.4%    |
| HP ProBook 4540s              | 3         | 0.4%    |
| HP Pavilion Notebook          | 3         | 0.4%    |
| HP Pavilion g6                | 3         | 0.4%    |
| HP Laptop 15-db0xxx           | 3         | 0.4%    |
| HP EliteBook 840 G3           | 3         | 0.4%    |
| HP 15                         | 3         | 0.4%    |
| Dell Latitude E6400           | 3         | 0.4%    |
| Dell Inspiron N5110           | 3         | 0.4%    |
| Dell Inspiron 1545            | 3         | 0.4%    |
| Dell Inspiron 15-3567         | 3         | 0.4%    |
| ASUS X550CA                   | 3         | 0.4%    |
| Apple MacBookPro9,2           | 3         | 0.4%    |
| Apple MacBookPro9,1           | 3         | 0.4%    |
| Apple MacBookPro5,5           | 3         | 0.4%    |
| Apple MacBook4,1              | 3         | 0.4%    |
| Apple MacBook2,1              | 3         | 0.4%    |
| Timi TM1613                   | 2         | 0.27%   |
| Star Labs StarBook            | 2         | 0.27%   |
| Samsung 530U3C/530U4C/532U3C  | 2         | 0.27%   |
| Samsung 300E5M/300E5L         | 2         | 0.27%   |
| MSI Prestige 15 A11UC         | 2         | 0.27%   |
| Lenovo Yoga 300-11IBR 80M1    | 2         | 0.27%   |
| Lenovo V330-15IKB 81AX        | 2         | 0.27%   |
| Lenovo IdeaPad Yoga 11S 20246 | 2         | 0.27%   |
| Lenovo IdeaPad Y580           | 2         | 0.27%   |
| Lenovo IdeaPad 5 14ARE05 81YM | 2         | 0.27%   |
| Lenovo IdeaPad 330-15IKB 81FE | 2         | 0.27%   |
| Lenovo IdeaPad 330-15IKB 81DE | 2         | 0.27%   |
| Lenovo IdeaPad 320-14AST 80XU | 2         | 0.27%   |
| Lenovo IdeaPad 310-15IKB 80TV | 2         | 0.27%   |
| Lenovo IdeaPad 130-15AST 81H5 | 2         | 0.27%   |
| Lenovo G500 20236             | 2         | 0.27%   |
| HUAWEI NBLK-WAX9X             | 2         | 0.27%   |
| HUAWEI NBLB-WAX9N             | 2         | 0.27%   |
| HP Stream Laptop 14-cb1xxx    | 2         | 0.27%   |
| HP ProBook 6460b              | 2         | 0.27%   |
| HP ProBook 640 G1             | 2         | 0.27%   |
| HP ProBook 450 G7             | 2         | 0.27%   |
| HP Pavilion Laptop 15-cs0xxx  | 2         | 0.27%   |
| HP Pavilion g4                | 2         | 0.27%   |
| HP Pavilion dv7               | 2         | 0.27%   |
| HP Pavilion 17                | 2         | 0.27%   |
| HP Laptop 17-by3xxx           | 2         | 0.27%   |
| HP EliteBook Folio 9470m      | 2         | 0.27%   |
| HP EliteBook 8460p            | 2         | 0.27%   |
| HP EliteBook 840 G1           | 2         | 0.27%   |
| HP Elite x2 1012 G1           | 2         | 0.27%   |
| HP 250 G7 Notebook PC         | 2         | 0.27%   |
| Dell XPS 15 9500              | 2         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 75        | 9.96%   |
| Acer Aspire           | 48        | 6.37%   |
| Lenovo IdeaPad        | 45        | 5.98%   |
| HP Pavilion           | 32        | 4.25%   |
| Dell Latitude         | 32        | 4.25%   |
| Dell Inspiron         | 31        | 4.12%   |
| HP ProBook            | 27        | 3.59%   |
| HP Laptop             | 23        | 3.05%   |
| HP EliteBook          | 22        | 2.92%   |
| Toshiba Satellite     | 21        | 2.79%   |
| Dell XPS              | 13        | 1.73%   |
| ASUS VivoBook         | 12        | 1.59%   |
| Acer Swift            | 11        | 1.46%   |
| ASUS ZenBook          | 10        | 1.33%   |
| Apple MacBookPro8     | 10        | 1.33%   |
| Dell Vostro           | 8         | 1.06%   |
| Apple MacBookAir7     | 7         | 0.93%   |
| HP Notebook           | 6         | 0.8%    |
| Dell Precision        | 6         | 0.8%    |
| Apple MacBookPro9     | 6         | 0.8%    |
| Apple MacBook5        | 6         | 0.8%    |
| Apple MacBookPro5     | 5         | 0.66%   |
| Lenovo G50-45         | 4         | 0.53%   |
| HP 250                | 4         | 0.53%   |
| Fujitsu LIFEBOOK      | 4         | 0.53%   |
| Apple MacBookPro11    | 4         | 0.53%   |
| Apple MacBookAir6     | 4         | 0.53%   |
| Apple MacBookAir4     | 4         | 0.53%   |
| Unknown               | 4         | 0.53%   |
| Packard Bell EasyNote | 3         | 0.4%    |
| Lenovo Yoga           | 3         | 0.4%    |
| Lenovo Legion         | 3         | 0.4%    |
| HUAWEI MACHD-WXX9     | 3         | 0.4%    |
| HP ZBook              | 3         | 0.4%    |
| HP Stream             | 3         | 0.4%    |
| HP Presario           | 3         | 0.4%    |
| HP ENVY               | 3         | 0.4%    |
| HP 15                 | 3         | 0.4%    |
| Compaq Presario       | 3         | 0.4%    |
| ASUS X550CA           | 3         | 0.4%    |
| Apple MacBookPro10    | 3         | 0.4%    |
| Apple MacBook4        | 3         | 0.4%    |
| Apple MacBook2        | 3         | 0.4%    |
| Toshiba PORTEGE       | 2         | 0.27%   |
| Timi TM1613           | 2         | 0.27%   |
| Star Labs StarBook    | 2         | 0.27%   |
| Samsung 530U3C        | 2         | 0.27%   |
| Samsung 300E5M        | 2         | 0.27%   |
| Razer Blade           | 2         | 0.27%   |
| Notebook W65          | 2         | 0.27%   |
| MSI Prestige          | 2         | 0.27%   |
| MSI Modern            | 2         | 0.27%   |
| MSI GF72              | 2         | 0.27%   |
| Medion Akoya          | 2         | 0.27%   |
| Lenovo V330-15IKB     | 2         | 0.27%   |
| Lenovo ThinkBook      | 2         | 0.27%   |
| Lenovo G550           | 2         | 0.27%   |
| Lenovo G500           | 2         | 0.27%   |
| HUAWEI NBLK-WAX9X     | 2         | 0.27%   |
| HUAWEI NBLB-WAX9N     | 2         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 76        | 10.09%  |
| 2020    | 69        | 9.16%   |
| 2013    | 65        | 8.63%   |
| 2012    | 65        | 8.63%   |
| 2011    | 58        | 7.7%    |
| 2019    | 57        | 7.57%   |
| 2016    | 56        | 7.44%   |
| 2015    | 55        | 7.3%    |
| 2017    | 53        | 7.04%   |
| 2014    | 44        | 5.84%   |
| 2010    | 43        | 5.71%   |
| 2021    | 42        | 5.58%   |
| 2009    | 29        | 3.85%   |
| 2008    | 26        | 3.45%   |
| 2007    | 10        | 1.33%   |
| 2006    | 3         | 0.4%    |
| 2022    | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 753       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 650       | 86.09%  |
| Enabled  | 105       | 13.91%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 743       | 98.67%  |
| Yes  | 10        | 1.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 250       | 32.98%  |
| 3.01-4.0    | 186       | 24.54%  |
| 8.01-16.0   | 124       | 16.36%  |
| 16.01-24.0  | 122       | 16.09%  |
| 1.01-2.0    | 32        | 4.22%   |
| 32.01-64.0  | 26        | 3.43%   |
| 2.01-3.0    | 9         | 1.19%   |
| 24.01-32.0  | 4         | 0.53%   |
| 64.01-256.0 | 3         | 0.4%    |
| 0.51-1.0    | 2         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 321       | 40.13%  |
| 2.01-3.0   | 236       | 29.5%   |
| 3.01-4.0   | 115       | 14.38%  |
| 4.01-8.0   | 83        | 10.38%  |
| 0.51-1.0   | 27        | 3.38%   |
| 8.01-16.0  | 16        | 2%      |
| 24.01-32.0 | 1         | 0.13%   |
| 16.01-24.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 564       | 74.21%  |
| 2      | 179       | 23.55%  |
| 3      | 9         | 1.18%   |
| 5      | 3         | 0.39%   |
| 0      | 3         | 0.39%   |
| 4      | 2         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 486       | 64.2%   |
| Yes       | 271       | 35.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 584       | 77.56%  |
| No        | 169       | 22.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 743       | 98.54%  |
| No        | 11        | 1.46%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 636       | 83.68%  |
| No        | 124       | 16.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 100       | 13.26%  |
| Germany      | 68        | 9.02%   |
| Brazil       | 55        | 7.29%   |
| Russia       | 42        | 5.57%   |
| India        | 41        | 5.44%   |
| UK           | 37        | 4.91%   |
| Italy        | 30        | 3.98%   |
| Spain        | 22        | 2.92%   |
| Indonesia    | 21        | 2.79%   |
| France       | 21        | 2.79%   |
| Australia    | 20        | 2.65%   |
| Mexico       | 19        | 2.52%   |
| Poland       | 18        | 2.39%   |
| Canada       | 17        | 2.25%   |
| Turkey       | 16        | 2.12%   |
| Netherlands  | 15        | 1.99%   |
| Argentina    | 13        | 1.72%   |
| Portugal     | 12        | 1.59%   |
| Ukraine      | 10        | 1.33%   |
| Chile        | 9         | 1.19%   |
| Austria      | 9         | 1.19%   |
| Czechia      | 8         | 1.06%   |
| Hungary      | 7         | 0.93%   |
| Belgium      | 7         | 0.93%   |
| Switzerland  | 6         | 0.8%    |
| Romania      | 6         | 0.8%    |
| Norway       | 6         | 0.8%    |
| South Africa | 5         | 0.66%   |
| New Zealand  | 5         | 0.66%   |
| Colombia     | 5         | 0.66%   |
| Sweden       | 4         | 0.53%   |
| Peru         | 4         | 0.53%   |
| Malaysia     | 4         | 0.53%   |
| Ireland      | 4         | 0.53%   |
| Denmark      | 4         | 0.53%   |
| China        | 4         | 0.53%   |
| Philippines  | 3         | 0.4%    |
| Nicaragua    | 3         | 0.4%    |
| Latvia       | 3         | 0.4%    |
| Greece       | 3         | 0.4%    |
| Finland      | 3         | 0.4%    |
| Estonia      | 3         | 0.4%    |
| Ecuador      | 3         | 0.4%    |
| Vietnam      | 2         | 0.27%   |
| Uruguay      | 2         | 0.27%   |
| Serbia       | 2         | 0.27%   |
| Paraguay     | 2         | 0.27%   |
| Pakistan     | 2         | 0.27%   |
| Morocco      | 2         | 0.27%   |
| Kenya        | 2         | 0.27%   |
| Kazakhstan   | 2         | 0.27%   |
| Japan        | 2         | 0.27%   |
| Iran         | 2         | 0.27%   |
| Guatemala    | 2         | 0.27%   |
| Croatia      | 2         | 0.27%   |
| Bulgaria     | 2         | 0.27%   |
| Belarus      | 2         | 0.27%   |
| Zambia       | 1         | 0.13%   |
| Uzbekistan   | 1         | 0.13%   |
| UAE          | 1         | 0.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Moscow                 | 10        | 1.29%   |
| Sydney                 | 8         | 1.03%   |
| Warsaw                 | 6         | 0.77%   |
| Sao Paulo              | 6         | 0.77%   |
| Milan                  | 6         | 0.77%   |
| Madrid                 | 6         | 0.77%   |
| Berlin                 | 6         | 0.77%   |
| Vienna                 | 5         | 0.64%   |
| The Hague              | 5         | 0.64%   |
| St Petersburg          | 5         | 0.64%   |
| Perth                  | 5         | 0.64%   |
| Jakarta                | 5         | 0.64%   |
| Istanbul               | 5         | 0.64%   |
| Hamburg                | 5         | 0.64%   |
| Surabaya               | 4         | 0.51%   |
| Santo André           | 4         | 0.51%   |
| Rome                   | 4         | 0.51%   |
| Rio de Janeiro         | 4         | 0.51%   |
| Paris                  | 4         | 0.51%   |
| Munich                 | 4         | 0.51%   |
| Mexico City            | 4         | 0.51%   |
| Kolkata                | 4         | 0.51%   |
| Delhi                  | 4         | 0.51%   |
| Vernon                 | 3         | 0.39%   |
| Valencia               | 3         | 0.39%   |
| Prague                 | 3         | 0.39%   |
| Porto                  | 3         | 0.39%   |
| Mumbai                 | 3         | 0.39%   |
| Montreal               | 3         | 0.39%   |
| Managua                | 3         | 0.39%   |
| Landing                | 3         | 0.39%   |
| Kyiv                   | 3         | 0.39%   |
| Jaipur                 | 3         | 0.39%   |
| Essen                  | 3         | 0.39%   |
| Dublin                 | 3         | 0.39%   |
| Córdoba               | 3         | 0.39%   |
| Chelyabinsk            | 3         | 0.39%   |
| Cape Town              | 3         | 0.39%   |
| Buenos Aires           | 3         | 0.39%   |
| Budapest               | 3         | 0.39%   |
| Belo Horizonte         | 3         | 0.39%   |
| Ahmedabad              | 3         | 0.39%   |
| Zagreb                 | 2         | 0.26%   |
| Wellington             | 2         | 0.26%   |
| Tucson                 | 2         | 0.26%   |
| Sassnitz               | 2         | 0.26%   |
| Santos                 | 2         | 0.26%   |
| Santiago               | 2         | 0.26%   |
| San Antonio            | 2         | 0.26%   |
| Rostov-on-Don          | 2         | 0.26%   |
| Riga                   | 2         | 0.26%   |
| Queretaro              | 2         | 0.26%   |
| Novosibirsk            | 2         | 0.26%   |
| North Shields          | 2         | 0.26%   |
| Nairobi                | 2         | 0.26%   |
| Monza                  | 2         | 0.26%   |
| Montornès del Vallès | 2         | 0.26%   |
| Montevideo             | 2         | 0.26%   |
| Minsk                  | 2         | 0.26%   |
| Milwaukee              | 2         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 121       | 140    | 13.15%  |
| WDC                       | 97        | 116    | 10.54%  |
| Seagate                   | 92        | 102    | 10%     |
| Toshiba                   | 87        | 92     | 9.46%   |
| SanDisk                   | 71        | 77     | 7.72%   |
| Unknown                   | 60        | 69     | 6.52%   |
| Kingston                  | 55        | 61     | 5.98%   |
| HGST                      | 36        | 43     | 3.91%   |
| Crucial                   | 34        | 39     | 3.7%    |
| Hitachi                   | 30        | 31     | 3.26%   |
| Apple                     | 27        | 29     | 2.93%   |
| Intel                     | 24        | 30     | 2.61%   |
| SK hynix                  | 23        | 25     | 2.5%    |
| Micron Technology         | 17        | 19     | 1.85%   |
| A-DATA Technology         | 14        | 16     | 1.52%   |
| KIOXIA                    | 10        | 16     | 1.09%   |
| Fujitsu                   | 9         | 10     | 0.98%   |
| Phison                    | 7         | 7      | 0.76%   |
| China                     | 7         | 7      | 0.76%   |
| Silicon Motion            | 5         | 6      | 0.54%   |
| LITEON                    | 5         | 5      | 0.54%   |
| JMicron Technology        | 4         | 4      | 0.43%   |
| TO Exter                  | 3         | 3      | 0.33%   |
| Patriot                   | 3         | 5      | 0.33%   |
| OCZ                       | 3         | 4      | 0.33%   |
| Lite-On                   | 3         | 3      | 0.33%   |
| KingDian                  | 3         | 4      | 0.33%   |
| Hewlett-Packard           | 3         | 3      | 0.33%   |
| Gigabyte Technology       | 3         | 3      | 0.33%   |
| Unknown                   | 3         | 3      | 0.33%   |
| V-GeN                     | 2         | 2      | 0.22%   |
| Transcend                 | 2         | 2      | 0.22%   |
| Star Drive                | 2         | 2      | 0.22%   |
| Star                      | 2         | 2      | 0.22%   |
| SPCC                      | 2         | 2      | 0.22%   |
| PNY                       | 2         | 3      | 0.22%   |
| NGFF                      | 2         | 2      | 0.22%   |
| Netac                     | 2         | 2      | 0.22%   |
| Micron/Crucial Technology | 2         | 2      | 0.22%   |
| LITEONIT                  | 2         | 2      | 0.22%   |
| FORESEE                   | 2         | 2      | 0.22%   |
| EYOTA                     | 2         | 2      | 0.22%   |
| ZTE                       | 1         | 1      | 0.11%   |
| XPG                       | 1         | 1      | 0.11%   |
| VT                        | 1         | 1      | 0.11%   |
| Union Memory              | 1         | 1      | 0.11%   |
| UMIS                      | 1         | 1      | 0.11%   |
| TSA                       | 1         | 1      | 0.11%   |
| TrekStor                  | 1         | 1      | 0.11%   |
| Timetec                   | 1         | 1      | 0.11%   |
| Teclast                   | 1         | 1      | 0.11%   |
| Team                      | 1         | 1      | 0.11%   |
| Super Talent              | 1         | 1      | 0.11%   |
| SSSTC                     | 1         | 1      | 0.11%   |
| SSK                       | 1         | 1      | 0.11%   |
| SSDPR-CX                  | 1         | 1      | 0.11%   |
| Smartbuy                  | 1         | 1      | 0.11%   |
| SABRENT                   | 1         | 1      | 0.11%   |
| Plextor                   | 1         | 1      | 0.11%   |
| Pichau                    | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                  | 20        | 2.12%   |
| Samsung NVMe SSD Drive 512GB            | 17        | 1.8%    |
| Unknown MMC Card  32GB                  | 16        | 1.7%    |
| Kingston SA400S37240G 240GB SSD         | 16        | 1.7%    |
| SanDisk NVMe SSD Drive 512GB            | 15        | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB          | 14        | 1.49%   |
| Samsung NVMe SSD Drive 256GB            | 14        | 1.49%   |
| Toshiba MQ04ABF100 1TB                  | 13        | 1.38%   |
| Unknown MMC Card  64GB                  | 12        | 1.27%   |
| Seagate ST500LT012-1DG142 500GB         | 12        | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 12        | 1.27%   |
| Unknown MMC Card  128GB                 | 10        | 1.06%   |
| HGST HTS721010A9E630 1TB                | 9         | 0.96%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 8         | 0.85%   |
| Toshiba MQ01ABF050 500GB                | 8         | 0.85%   |
| SK hynix NVMe SSD Drive 512GB           | 7         | 0.74%   |
| SanDisk NVMe SSD Drive 256GB            | 7         | 0.74%   |
| Kingston SA400S37120G 120GB SSD         | 7         | 0.74%   |
| Intel NVMe SSD Drive 512GB              | 7         | 0.74%   |
| HGST HTS545050A7E680 500GB              | 7         | 0.74%   |
| Samsung SSD 860 EVO 500GB               | 6         | 0.64%   |
| Samsung SSD 860 EVO 250GB               | 6         | 0.64%   |
| HGST HTS541010A9E680 1TB                | 6         | 0.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 5         | 0.53%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 5         | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB                | 5         | 0.53%   |
| WDC WD10JPCX-24UE4T0 1TB                | 5         | 0.53%   |
| Unknown MMC Card  16GB                  | 5         | 0.53%   |
| Toshiba NVMe SSD Drive 512GB            | 5         | 0.53%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 5         | 0.53%   |
| Samsung SSD 850 EVO 250GB               | 5         | 0.53%   |
| HGST HTS541010B7E610 1TB                | 5         | 0.53%   |
| WDC WD10SPZX-24Z10 1TB                  | 4         | 0.42%   |
| SK hynix NVMe SSD Drive 256GB           | 4         | 0.42%   |
| Seagate ST9500325AS 500GB               | 4         | 0.42%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD     | 4         | 0.42%   |
| SanDisk NVMe SSD Drive 1024GB           | 4         | 0.42%   |
| Samsung SSD 850 EVO 500GB               | 4         | 0.42%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 4         | 0.42%   |
| KIOXIA NVMe SSD Drive 256GB             | 4         | 0.42%   |
| Kingston SUV400S37240G 240GB SSD        | 4         | 0.42%   |
| HGST HTS725050A7E630 500GB              | 4         | 0.42%   |
| Crucial CT480BX500SSD1 480GB            | 4         | 0.42%   |
| Crucial CT1000MX500SSD1 1TB             | 4         | 0.42%   |
| Apple SSD SM0128G 121GB                 | 4         | 0.42%   |
| A-DATA SU650 120GB SSD                  | 4         | 0.42%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.32%   |
| Toshiba THNSNJ128GCSU 128GB SSD         | 3         | 0.32%   |
| Toshiba MQ01ABD100V -63 1TB             | 3         | 0.32%   |
| TO Exter nal USB 3.0 240GB              | 3         | 0.32%   |
| Seagate ST9320325AS 320GB               | 3         | 0.32%   |
| Seagate ST500LT012-9WS142 500GB         | 3         | 0.32%   |
| Seagate ST500LM030-2E717D 500GB         | 3         | 0.32%   |
| Seagate ST500LM021-1KJ152 500GB         | 3         | 0.32%   |
| Seagate ST2000LX001-1RG174 2TB          | 3         | 0.32%   |
| SanDisk SDSSDA120G 120GB                | 3         | 0.32%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD     | 3         | 0.32%   |
| SanDisk NVMe SSD Drive 250GB            | 3         | 0.32%   |
| Samsung NVMe SSD Drive 500GB            | 3         | 0.32%   |
| Samsung NVMe SSD Drive 1TB              | 3         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 92        | 101    | 29.39%  |
| WDC                 | 69        | 83     | 22.04%  |
| Toshiba             | 69        | 74     | 22.04%  |
| HGST                | 36        | 43     | 11.5%   |
| Hitachi             | 30        | 31     | 9.58%   |
| Fujitsu             | 9         | 10     | 2.88%   |
| Samsung Electronics | 4         | 5      | 1.28%   |
| Apple               | 2         | 2      | 0.64%   |
| Unknown             | 1         | 1      | 0.32%   |
| SABRENT             | 1         | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 68        | 76     | 19.6%   |
| Kingston            | 44        | 46     | 12.68%  |
| SanDisk             | 40        | 45     | 11.53%  |
| Crucial             | 34        | 39     | 9.8%    |
| Apple               | 23        | 24     | 6.63%   |
| WDC                 | 22        | 24     | 6.34%   |
| A-DATA Technology   | 13        | 15     | 3.75%   |
| Micron Technology   | 11        | 13     | 3.17%   |
| Intel               | 11        | 11     | 3.17%   |
| Toshiba             | 8         | 8      | 2.31%   |
| China               | 7         | 7      | 2.02%   |
| LITEON              | 5         | 5      | 1.44%   |
| SK hynix            | 4         | 4      | 1.15%   |
| TO Exter            | 3         | 3      | 0.86%   |
| Patriot             | 3         | 5      | 0.86%   |
| OCZ                 | 3         | 4      | 0.86%   |
| Hewlett-Packard     | 3         | 3      | 0.86%   |
| Transcend           | 2         | 2      | 0.58%   |
| Star                | 2         | 2      | 0.58%   |
| SPCC                | 2         | 2      | 0.58%   |
| PNY                 | 2         | 3      | 0.58%   |
| NGFF                | 2         | 2      | 0.58%   |
| Netac               | 2         | 2      | 0.58%   |
| LITEONIT            | 2         | 2      | 0.58%   |
| KingDian            | 2         | 3      | 0.58%   |
| JMicron Technology  | 2         | 2      | 0.58%   |
| Gigabyte Technology | 2         | 2      | 0.58%   |
| FORESEE             | 2         | 2      | 0.58%   |
| VT                  | 1         | 1      | 0.29%   |
| V-GeN               | 1         | 1      | 0.29%   |
| TSA                 | 1         | 1      | 0.29%   |
| TrekStor            | 1         | 1      | 0.29%   |
| Teclast             | 1         | 1      | 0.29%   |
| Team                | 1         | 1      | 0.29%   |
| Super Talent        | 1         | 1      | 0.29%   |
| Smartbuy            | 1         | 1      | 0.29%   |
| Plextor             | 1         | 1      | 0.29%   |
| Pichau              | 1         | 1      | 0.29%   |
| Phison              | 1         | 1      | 0.29%   |
| Mercury             | 1         | 1      | 0.29%   |
| MENGMI              | 1         | 1      | 0.29%   |
| LS                  | 1         | 1      | 0.29%   |
| Lexar               | 1         | 1      | 0.29%   |
| KingSpec            | 1         | 1      | 0.29%   |
| GOODRAM             | 1         | 1      | 0.29%   |
| EYOTA               | 1         | 1      | 0.29%   |
| EVM                 | 1         | 1      | 0.29%   |
| Dogfish             | 1         | 1      | 0.29%   |
| Colorful            | 1         | 1      | 0.29%   |
| Apacer              | 1         | 1      | 0.29%   |
| Unknown             | 1         | 1      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 328       | 379    | 36.81%  |
| HDD     | 308       | 351    | 34.57%  |
| NVMe    | 177       | 219    | 19.87%  |
| MMC     | 58        | 65     | 6.51%   |
| Unknown | 20        | 21     | 2.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 583       | 723    | 69.24%  |
| NVMe | 177       | 219    | 21.02%  |
| MMC  | 58        | 65     | 6.89%   |
| SAS  | 24        | 28     | 2.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 443       | 525    | 70.65%  |
| 0.51-1.0   | 166       | 185    | 26.48%  |
| 1.01-2.0   | 17        | 19     | 2.71%   |
| 3.01-4.0   | 1         | 1      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 294       | 38.53%  |
| 251-500        | 213       | 27.92%  |
| 501-1000       | 98        | 12.84%  |
| 51-100         | 66        | 8.65%   |
| 21-50          | 35        | 4.59%   |
| 1001-2000      | 31        | 4.06%   |
| 1-20           | 13        | 1.7%    |
| 2001-3000      | 6         | 0.79%   |
| More than 3000 | 4         | 0.52%   |
| Unknown        | 3         | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 352       | 44.61%  |
| 21-50     | 194       | 24.59%  |
| 51-100    | 96        | 12.17%  |
| 101-250   | 79        | 10.01%  |
| 251-500   | 36        | 4.56%   |
| 501-1000  | 20        | 2.53%   |
| 1001-2000 | 6         | 0.76%   |
| 2001-3000 | 3         | 0.38%   |
| Unknown   | 3         | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 5.56%   |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 1      | 5.56%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 5.56%   |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 5.56%   |
| Seagate ST500LM030-2E717D 500GB       | 1         | 1      | 5.56%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 5.56%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 1      | 5.56%   |
| SanDisk SD7SB3Q256G1002 256GB SSD     | 1         | 1      | 5.56%   |
| Kingston SV300S37A240G 240GB SSD      | 1         | 1      | 5.56%   |
| Kingston SUV400S37480G 480GB SSD      | 1         | 1      | 5.56%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 5.56%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 5.56%   |
| Fujitsu MHZ2160BH G2 160GB            | 1         | 2      | 5.56%   |
| Crucial CT512M550SSD3 512GB           | 1         | 1      | 5.56%   |
| Apple SSD SM256C 256GB                | 1         | 1      | 5.56%   |
| A-DATA Technology SP900NS38 128GB SSD | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 3      | 16.67%  |
| Seagate           | 3         | 3      | 16.67%  |
| Toshiba           | 2         | 2      | 11.11%  |
| SanDisk           | 2         | 2      | 11.11%  |
| Kingston          | 2         | 2      | 11.11%  |
| HGST              | 2         | 2      | 11.11%  |
| Fujitsu           | 1         | 2      | 5.56%   |
| Crucial           | 1         | 1      | 5.56%   |
| Apple             | 1         | 1      | 5.56%   |
| A-DATA Technology | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| Toshiba | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| Fujitsu | 1         | 2      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 11     | 55.56%  |
| SSD  | 8         | 8      | 44.44%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-75Z10T1 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 642       | 865    | 82.31%  |
| Works    | 119       | 150    | 15.26%  |
| Malfunc  | 18        | 19     | 2.31%   |
| Failed   | 1         | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 558       | 66.35%  |
| AMD                            | 76        | 9.04%   |
| Samsung Electronics            | 62        | 7.37%   |
| SanDisk                        | 39        | 4.64%   |
| SK hynix                       | 19        | 2.26%   |
| Nvidia                         | 17        | 2.02%   |
| Kingston Technology Company    | 12        | 1.43%   |
| Toshiba America Info Systems   | 11        | 1.31%   |
| Phison Electronics             | 9         | 1.07%   |
| KIOXIA                         | 9         | 1.07%   |
| Micron Technology              | 6         | 0.71%   |
| Silicon Motion                 | 5         | 0.59%   |
| Marvell Technology Group       | 3         | 0.36%   |
| Lite-On Technology             | 3         | 0.36%   |
| ADATA Technology               | 3         | 0.36%   |
| Union Memory (Shenzhen)        | 2         | 0.24%   |
| Micron/Crucial Technology      | 2         | 0.24%   |
| Apple                          | 2         | 0.24%   |
| Solid State Storage Technology | 1         | 0.12%   |
| Realtek Semiconductor          | 1         | 0.12%   |
| Biwin Storage Technology       | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 84        | 9.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 76        | 8.63%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 70        | 7.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 57        | 6.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 42        | 4.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 37        | 4.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 29        | 3.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 22        | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 19        | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 19        | 2.16%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 18        | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 18        | 2.04%   |
| Samsung NVMe SSD Controller 980                                                        | 16        | 1.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 16        | 1.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 15        | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 13        | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 13        | 1.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 13        | 1.48%   |
| Nvidia MCP79 AHCI Controller                                                           | 11        | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 10        | 1.14%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 9         | 1.02%   |
| Samsung Electronics SATA controller                                                    | 9         | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 9         | 1.02%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 8         | 0.91%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 8         | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 8         | 0.91%   |
| SK hynix Gold P31 SSD                                                                  | 7         | 0.79%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 7         | 0.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 7         | 0.79%   |
| Intel SSD 660P Series                                                                  | 7         | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 7         | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 7         | 0.79%   |
| SanDisk Non-Volatile memory controller                                                 | 6         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 6         | 0.68%   |
| Micron Non-Volatile memory controller                                                  | 6         | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 6         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 6         | 0.68%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 5         | 0.57%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 5         | 0.57%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 5         | 0.57%   |
| Phison E12 NVMe Controller                                                             | 5         | 0.57%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 5         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 5         | 0.57%   |
| SK hynix BC511                                                                         | 4         | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 4         | 0.45%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 4         | 0.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 4         | 0.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 4         | 0.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 4         | 0.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 4         | 0.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 4         | 0.45%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 4         | 0.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 4         | 0.45%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 0.34%   |
| SanDisk PC SN520 NVMe SSD                                                              | 3         | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 0.34%   |
| Phison PS5013 E13 NVMe Controller                                                      | 3         | 0.34%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 3         | 0.34%   |
| Lite-On Non-Volatile memory controller                                                 | 3         | 0.34%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 3         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 583       | 68.11%  |
| NVMe | 177       | 20.68%  |
| RAID | 56        | 6.54%   |
| IDE  | 40        | 4.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 651       | 86.45%  |
| AMD    | 102       | 13.55%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 18        | 2.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 1.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 1.73%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 12        | 1.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 1.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 1.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 1.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 1.33%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 10        | 1.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 1.2%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 9         | 1.2%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 1.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.06%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 1.06%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 8         | 1.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 1.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.93%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 7         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.93%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 0.93%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 7         | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 0.8%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 6         | 0.8%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 0.8%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 0.8%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 6         | 0.8%    |
| Intel Celeron CPU N3050 @ 1.60GHz             | 6         | 0.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 0.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.66%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 5         | 0.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.66%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 5         | 0.66%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.66%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 0.66%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 5         | 0.66%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.66%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 5         | 0.66%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 5         | 0.66%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 5         | 0.66%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.66%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 4         | 0.53%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 4         | 0.53%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 4         | 0.53%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 4         | 0.53%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.53%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.53%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.53%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 4         | 0.53%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 0.53%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 4         | 0.53%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 4         | 0.53%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 4         | 0.53%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 0.53%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 4         | 0.53%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.53%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 4         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 206       | 27.36%  |
| Intel Core i7                        | 172       | 22.84%  |
| Intel Core i3                        | 81        | 10.76%  |
| Intel Celeron                        | 51        | 6.77%   |
| Intel Core 2 Duo                     | 43        | 5.71%   |
| Other                                | 37        | 4.91%   |
| AMD Ryzen 5                          | 26        | 3.45%   |
| Intel Pentium                        | 19        | 2.52%   |
| AMD Ryzen 7                          | 12        | 1.59%   |
| Intel Atom                           | 11        | 1.46%   |
| Intel Pentium Dual-Core              | 9         | 1.2%    |
| AMD A6                               | 9         | 1.2%    |
| Intel Core 2                         | 7         | 0.93%   |
| AMD Ryzen 3                          | 7         | 0.93%   |
| AMD A8                               | 7         | 0.93%   |
| Intel Pentium Silver                 | 6         | 0.8%    |
| AMD A4                               | 5         | 0.66%   |
| AMD A10                              | 5         | 0.66%   |
| AMD Ryzen 7 PRO                      | 4         | 0.53%   |
| AMD A12                              | 4         | 0.53%   |
| Intel Genuine                        | 3         | 0.4%    |
| Intel Celeron Dual-Core              | 3         | 0.4%    |
| AMD Ryzen 5 PRO                      | 3         | 0.4%    |
| AMD E1                               | 3         | 0.4%    |
| Intel Core m5                        | 2         | 0.27%   |
| Intel Core m3                        | 2         | 0.27%   |
| AMD E                                | 2         | 0.27%   |
| AMD C-60                             | 2         | 0.27%   |
| Intel Xeon                           | 1         | 0.13%   |
| Intel Pentium Dual                   | 1         | 0.13%   |
| Intel Core i9                        | 1         | 0.13%   |
| Intel Core 2 Quad                    | 1         | 0.13%   |
| Intel Celeron M                      | 1         | 0.13%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.13%   |
| AMD Ryzen 9                          | 1         | 0.13%   |
| AMD Phenom II                        | 1         | 0.13%   |
| AMD E2                               | 1         | 0.13%   |
| AMD Athlon II Neo                    | 1         | 0.13%   |
| AMD Athlon 64 X2                     | 1         | 0.13%   |
| AMD Athlon                           | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 463       | 61.49%  |
| 4      | 230       | 30.54%  |
| 6      | 35        | 4.65%   |
| 8      | 18        | 2.39%   |
| 1      | 7         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 753       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 553       | 73.44%  |
| 1      | 200       | 26.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 749       | 99.47%  |
| Unknown        | 4         | 0.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 72        | 9.45%   |
| Unknown    | 69        | 9.06%   |
| 0x306a9    | 64        | 8.4%    |
| 0x40651    | 41        | 5.38%   |
| 0x1067a    | 39        | 5.12%   |
| 0x406e3    | 34        | 4.46%   |
| 0x306d4    | 31        | 4.07%   |
| 0x806e9    | 30        | 3.94%   |
| 0x806ea    | 28        | 3.67%   |
| 0x806c1    | 25        | 3.28%   |
| 0x806ec    | 23        | 3.02%   |
| 0x20655    | 22        | 2.89%   |
| 0x306c3    | 18        | 2.36%   |
| 0x20652    | 15        | 1.97%   |
| 0x30678    | 14        | 1.84%   |
| 0x406c3    | 13        | 1.71%   |
| 0x906ea    | 12        | 1.57%   |
| 0x706e5    | 12        | 1.57%   |
| 0x06006705 | 11        | 1.44%   |
| 0xa0652    | 10        | 1.31%   |
| 0x806eb    | 10        | 1.31%   |
| 0x706a1    | 10        | 1.31%   |
| 0x506c9    | 10        | 1.31%   |
| 0x08108109 | 10        | 1.31%   |
| 0x706a8    | 9         | 1.18%   |
| 0x10676    | 9         | 1.18%   |
| 0x906e9    | 8         | 1.05%   |
| 0x08600106 | 8         | 1.05%   |
| 0x6fd      | 7         | 0.92%   |
| 0x08108102 | 7         | 0.92%   |
| 0x506e3    | 6         | 0.79%   |
| 0x08608103 | 6         | 0.79%   |
| 0x07030105 | 6         | 0.79%   |
| 0x6f6      | 5         | 0.66%   |
| 0x406c4    | 4         | 0.52%   |
| 0x40661    | 4         | 0.52%   |
| 0x0a50000c | 4         | 0.52%   |
| 0x08101007 | 4         | 0.52%   |
| 0x06001119 | 4         | 0.52%   |
| 0x05000119 | 4         | 0.52%   |
| 0x806c2    | 3         | 0.39%   |
| 0x6fb      | 3         | 0.39%   |
| 0x0810100b | 3         | 0.39%   |
| 0x0700010f | 3         | 0.39%   |
| 0x06006704 | 3         | 0.39%   |
| 0x906ed    | 2         | 0.26%   |
| 0x6fa      | 2         | 0.26%   |
| 0x106ca    | 2         | 0.26%   |
| 0x08600104 | 2         | 0.26%   |
| 0x0600611a | 2         | 0.26%   |
| 0x06006118 | 2         | 0.26%   |
| 0x010000c8 | 2         | 0.26%   |
| 0xa0671    | 1         | 0.13%   |
| 0xa0660    | 1         | 0.13%   |
| 0x906c0    | 1         | 0.13%   |
| 0x806d1    | 1         | 0.13%   |
| 0x6f2      | 1         | 0.13%   |
| 0x106e5    | 1         | 0.13%   |
| 0x08600103 | 1         | 0.13%   |
| 0x08600102 | 1         | 0.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 132       | 17.53%  |
| SandyBridge     | 76        | 10.09%  |
| IvyBridge       | 68        | 9.03%   |
| Haswell         | 67        | 8.9%    |
| Penryn          | 50        | 6.64%   |
| Skylake         | 46        | 6.11%   |
| Westmere        | 37        | 4.91%   |
| Silvermont      | 36        | 4.78%   |
| Broadwell       | 31        | 4.12%   |
| TigerLake       | 29        | 3.85%   |
| Excavator       | 21        | 2.79%   |
| Goldmont plus   | 19        | 2.52%   |
| Core            | 19        | 2.52%   |
| Zen+            | 18        | 2.39%   |
| Zen 2           | 15        | 1.99%   |
| Icelake         | 15        | 1.99%   |
| CometLake       | 11        | 1.46%   |
| Goldmont        | 10        | 1.33%   |
| Zen             | 9         | 1.2%    |
| Puma            | 8         | 1.06%   |
| Unknown         | 8         | 1.06%   |
| Zen 3           | 5         | 0.66%   |
| Piledriver      | 5         | 0.66%   |
| Bobcat          | 5         | 0.66%   |
| Jaguar          | 4         | 0.53%   |
| K10             | 2         | 0.27%   |
| Bonnell         | 2         | 0.27%   |
| Tremont         | 1         | 0.13%   |
| Nehalem         | 1         | 0.13%   |
| K8 Hammer       | 1         | 0.13%   |
| K8 & K10 hybrid | 1         | 0.13%   |
| K10 Llano       | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 597       | 64.61%  |
| Nvidia | 173       | 18.72%  |
| AMD    | 154       | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 68        | 7.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 64        | 6.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 43        | 4.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 35        | 3.67%   |
| Intel HD Graphics 620                                                                    | 34        | 3.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 33        | 3.46%   |
| Intel UHD Graphics 620                                                                   | 31        | 3.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 30        | 3.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 27        | 2.83%   |
| Intel HD Graphics 5500                                                                   | 23        | 2.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 22        | 2.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 2.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 1.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 15        | 1.57%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 15        | 1.57%   |
| AMD Renoir                                                                               | 15        | 1.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 1.36%   |
| Nvidia C79 [GeForce 9400M]                                                               | 10        | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 1.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.05%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 10        | 1.05%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 9         | 0.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 0.94%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.84%   |
| Intel HD Graphics 630                                                                    | 8         | 0.84%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 8         | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.73%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 0.73%   |
| Intel HD Graphics 6000                                                                   | 7         | 0.73%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 7         | 0.73%   |
| AMD Lucienne                                                                             | 7         | 0.73%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.63%   |
| Intel HD Graphics 500                                                                    | 6         | 0.63%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 6         | 0.63%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 0.63%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.52%   |
| AMD Cezanne                                                                              | 5         | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.42%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 4         | 0.42%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.42%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 4         | 0.42%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 4         | 0.42%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.42%   |
| Intel HD Graphics 530                                                                    | 4         | 0.42%   |
| Intel HD Graphics 515                                                                    | 4         | 0.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 4         | 0.42%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 4         | 0.42%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 4         | 0.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.31%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 3         | 0.31%   |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 0.31%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.31%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 3         | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 431       | 57.24%  |
| Intel + Nvidia | 130       | 17.26%  |
| 1 x AMD        | 100       | 13.28%  |
| 1 x Nvidia     | 36        | 4.78%   |
| Intel + AMD    | 36        | 4.78%   |
| 2 x AMD        | 14        | 1.86%   |
| AMD + Nvidia   | 4         | 0.53%   |
| 2 x Nvidia     | 2         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 664       | 87.83%  |
| Proprietary | 81        | 10.71%  |
| Unknown     | 11        | 1.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 459       | 60.47%  |
| 1.01-2.0   | 111       | 14.62%  |
| 0.01-0.5   | 87        | 11.46%  |
| 0.51-1.0   | 54        | 7.11%   |
| 3.01-4.0   | 37        | 4.87%   |
| 5.01-6.0   | 7         | 0.92%   |
| 7.01-8.0   | 2         | 0.26%   |
| 2.01-3.0   | 2         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 153       | 18.41%  |
| LG Display              | 126       | 15.16%  |
| Chimei Innolux          | 115       | 13.84%  |
| BOE                     | 103       | 12.39%  |
| Samsung Electronics     | 83        | 9.99%   |
| Apple                   | 66        | 7.94%   |
| Sharp                   | 24        | 2.89%   |
| Chi Mei Optoelectronics | 20        | 2.41%   |
| Lenovo                  | 19        | 2.29%   |
| Dell                    | 16        | 1.93%   |
| PANDA                   | 12        | 1.44%   |
| Hewlett-Packard         | 9         | 1.08%   |
| Goldstar                | 8         | 0.96%   |
| AOC                     | 7         | 0.84%   |
| CSO                     | 5         | 0.6%    |
| Acer                    | 5         | 0.6%    |
| Toshiba                 | 4         | 0.48%   |
| Sony                    | 4         | 0.48%   |
| Panasonic               | 4         | 0.48%   |
| CPT                     | 4         | 0.48%   |
| BenQ                    | 4         | 0.48%   |
| ViewSonic               | 3         | 0.36%   |
| Unknown                 | 3         | 0.36%   |
| Philips                 | 3         | 0.36%   |
| LG Philips              | 3         | 0.36%   |
| InfoVision              | 3         | 0.36%   |
| Ancor Communications    | 3         | 0.36%   |
| LGD                     | 2         | 0.24%   |
| JDI                     | 2         | 0.24%   |
| ___                     | 1         | 0.12%   |
| Vizio                   | 1         | 0.12%   |
| Vestel Elektronik       | 1         | 0.12%   |
| TMX                     | 1         | 0.12%   |
| Seiko/Epson             | 1         | 0.12%   |
| SANYO                   | 1         | 0.12%   |
| Plain Tree Systems      | 1         | 0.12%   |
| Packard Bell            | 1         | 0.12%   |
| Konka                   | 1         | 0.12%   |
| IBM                     | 1         | 0.12%   |
| HUAWEI                  | 1         | 0.12%   |
| HJC                     | 1         | 0.12%   |
| Hitachi                 | 1         | 0.12%   |
| HannStar                | 1         | 0.12%   |
| Fujitsu Siemens         | 1         | 0.12%   |
| EXP                     | 1         | 0.12%   |
| DPL                     | 1         | 0.12%   |
| Unknown                 | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 8         | 0.95%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.95%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 6         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 6         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 6         | 0.71%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.71%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 6         | 0.71%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 5         | 0.59%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 5         | 0.59%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.59%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 5         | 0.59%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 5         | 0.59%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 5         | 0.59%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 4         | 0.48%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.48%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.48%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                  | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 4         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 4         | 0.48%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 4         | 0.48%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 4         | 0.48%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 4         | 0.48%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 0.48%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 4         | 0.48%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 4         | 0.48%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 4         | 0.48%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.36%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 3         | 0.36%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                    | 3         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 3         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 3         | 0.36%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 3         | 0.36%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                     | 3         | 0.36%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 3         | 0.36%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 3         | 0.36%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.36%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch            | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch           | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 3         | 0.36%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 3         | 0.36%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                   | 3         | 0.36%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                   | 3         | 0.36%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                     | 3         | 0.36%   |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 2         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 290       | 36.43%  |
| 1366x768 (WXGA)    | 283       | 35.55%  |
| 1280x800 (WXGA)    | 46        | 5.78%   |
| 1600x900 (HD+)     | 40        | 5.03%   |
| 1440x900 (WXGA+)   | 31        | 3.89%   |
| 3840x2160 (4K)     | 28        | 3.52%   |
| 2560x1440 (QHD)    | 15        | 1.88%   |
| 1920x1200 (WUXGA)  | 10        | 1.26%   |
| 2560x1600          | 7         | 0.88%   |
| 1680x1050 (WSXGA+) | 7         | 0.88%   |
| 2880x1800          | 6         | 0.75%   |
| 3000x2000          | 5         | 0.63%   |
| 1280x1024 (SXGA)   | 4         | 0.5%    |
| 1024x600           | 3         | 0.38%   |
| 3840x2400          | 2         | 0.25%   |
| 3200x1800 (QHD+)   | 2         | 0.25%   |
| 2560x1080          | 2         | 0.25%   |
| 1920x540           | 2         | 0.25%   |
| 1920x1280          | 2         | 0.25%   |
| 3840x1100          | 1         | 0.13%   |
| 3840x1080          | 1         | 0.13%   |
| 3072x1920          | 1         | 0.13%   |
| 2256x1504          | 1         | 0.13%   |
| 1920x515           | 1         | 0.13%   |
| 1680x945           | 1         | 0.13%   |
| 1600x1200          | 1         | 0.13%   |
| 1400x1050          | 1         | 0.13%   |
| 1360x768           | 1         | 0.13%   |
| 1280x720 (HD)      | 1         | 0.13%   |
| Unknown            | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 310       | 37.17%  |
| 13      | 175       | 20.98%  |
| 14      | 111       | 13.31%  |
| 17      | 49        | 5.88%   |
| 11      | 29        | 3.48%   |
| 27      | 23        | 2.76%   |
| 12      | 20        | 2.4%    |
| 24      | 18        | 2.16%   |
| 23      | 15        | 1.8%    |
| Unknown | 15        | 1.8%    |
| 21      | 12        | 1.44%   |
| 31      | 7         | 0.84%   |
| 18      | 7         | 0.84%   |
| 84      | 5         | 0.6%    |
| 19      | 5         | 0.6%    |
| 16      | 5         | 0.6%    |
| 10      | 5         | 0.6%    |
| 72      | 4         | 0.48%   |
| 25      | 3         | 0.36%   |
| 22      | 3         | 0.36%   |
| 52      | 2         | 0.24%   |
| 34      | 2         | 0.24%   |
| 74      | 1         | 0.12%   |
| 69      | 1         | 0.12%   |
| 48      | 1         | 0.12%   |
| 47      | 1         | 0.12%   |
| 43      | 1         | 0.12%   |
| 37      | 1         | 0.12%   |
| 33      | 1         | 0.12%   |
| 26      | 1         | 0.12%   |
| 20      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 493       | 59.76%  |
| 201-300     | 150       | 18.18%  |
| 351-400     | 59        | 7.15%   |
| 501-600     | 52        | 6.3%    |
| 401-500     | 25        | 3.03%   |
| Unknown     | 15        | 1.82%   |
| 601-700     | 11        | 1.33%   |
| 1501-2000   | 11        | 1.33%   |
| 1001-1500   | 4         | 0.48%   |
| 701-800     | 3         | 0.36%   |
| 801-900     | 1         | 0.12%   |
| 901-1000    | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 609       | 81.2%   |
| 16/10   | 106       | 14.13%  |
| 3/2     | 12        | 1.6%    |
| Unknown | 12        | 1.6%    |
| 5/4     | 4         | 0.53%   |
| 4/3     | 2         | 0.27%   |
| 21/9    | 2         | 0.27%   |
| 3.73    | 1         | 0.13%   |
| 3.40    | 1         | 0.13%   |
| 1.96    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 310       | 37.26%  |
| 81-90          | 220       | 26.44%  |
| 71-80          | 65        | 7.81%   |
| 201-250        | 40        | 4.81%   |
| 121-130        | 38        | 4.57%   |
| 51-60          | 30        | 3.61%   |
| 301-350        | 23        | 2.76%   |
| 61-70          | 20        | 2.4%    |
| Unknown        | 15        | 1.8%    |
| More than 1000 | 13        | 1.56%   |
| 351-500        | 10        | 1.2%    |
| 151-200        | 9         | 1.08%   |
| 141-150        | 9         | 1.08%   |
| 131-140        | 9         | 1.08%   |
| 251-300        | 7         | 0.84%   |
| 41-50          | 5         | 0.6%    |
| 111-120        | 4         | 0.48%   |
| 501-1000       | 4         | 0.48%   |
| 91-100         | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 315       | 38.7%   |
| 121-160       | 308       | 37.84%  |
| 51-100        | 91        | 11.18%  |
| 161-240       | 52        | 6.39%   |
| More than 240 | 22        | 2.7%    |
| Unknown       | 15        | 1.84%   |
| 1-50          | 11        | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 649       | 84.84%  |
| 2     | 94        | 12.29%  |
| 3     | 11        | 1.44%   |
| 0     | 10        | 1.31%   |
| 4     | 1         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 371       | 31.41%  |
| Intel                             | 355       | 30.06%  |
| Qualcomm Atheros                  | 181       | 15.33%  |
| Broadcom                          | 119       | 10.08%  |
| Broadcom Limited                  | 25        | 2.12%   |
| Nvidia                            | 15        | 1.27%   |
| Marvell Technology Group          | 15        | 1.27%   |
| Ralink                            | 13        | 1.1%    |
| TP-Link                           | 10        | 0.85%   |
| Huawei Technologies               | 7         | 0.59%   |
| Ralink Technology                 | 6         | 0.51%   |
| Sierra Wireless                   | 5         | 0.42%   |
| MediaTek                          | 5         | 0.42%   |
| Xiaomi                            | 4         | 0.34%   |
| Qualcomm                          | 4         | 0.34%   |
| Hewlett-Packard                   | 4         | 0.34%   |
| Ericsson Business Mobile Networks | 4         | 0.34%   |
| ASIX Electronics                  | 4         | 0.34%   |
| Samsung Electronics               | 3         | 0.25%   |
| Google                            | 3         | 0.25%   |
| D-Link                            | 3         | 0.25%   |
| OPPO Electronics                  | 2         | 0.17%   |
| Lenovo                            | 2         | 0.17%   |
| JMicron Technology                | 2         | 0.17%   |
| Apple                             | 2         | 0.17%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.08%   |
| TRENDnet                          | 1         | 0.08%   |
| Toshiba                           | 1         | 0.08%   |
| Sitecom Europe                    | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.08%   |
| NEC Computers                     | 1         | 0.08%   |
| LSI                               | 1         | 0.08%   |
| Linksys                           | 1         | 0.08%   |
| LG Electronics                    | 1         | 0.08%   |
| ICS Advent                        | 1         | 0.08%   |
| HMD Global                        | 1         | 0.08%   |
| Fibocom                           | 1         | 0.08%   |
| DisplayLink                       | 1         | 0.08%   |
| D-Link System                     | 1         | 0.08%   |
| Attansic Technology               | 1         | 0.08%   |
| ASUSTek Computer                  | 1         | 0.08%   |
| Arduino SA                        | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 222       | 15.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 81        | 5.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 37        | 2.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 34        | 2.41%   |
| Intel Wireless 8260                                               | 33        | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 31        | 2.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26        | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 25        | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 24        | 1.7%    |
| Intel Wireless 7265                                               | 23        | 1.63%   |
| Intel Wireless 7260                                               | 23        | 1.63%   |
| Intel Wi-Fi 6 AX200                                               | 23        | 1.63%   |
| Intel Wireless 8265 / 8275                                        | 22        | 1.56%   |
| Intel Wi-Fi 6 AX201                                               | 22        | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 20        | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 20        | 1.42%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 19        | 1.34%   |
| Intel Wireless 3165                                               | 16        | 1.13%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 16        | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 15        | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 14        | 0.99%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 13        | 0.92%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 13        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 13        | 0.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.85%   |
| Nvidia MCP79 Ethernet                                             | 12        | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                     | 12        | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 0.78%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 11        | 0.78%   |
| Intel Centrino Advanced-N 6235                                    | 11        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 0.78%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 11        | 0.78%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 11        | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 10        | 0.71%   |
| Intel Wireless 3160                                               | 10        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 9         | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 9         | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 9         | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 0.64%   |
| Intel Centrino Advanced-N 6200                                    | 9         | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8         | 0.57%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.57%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 7         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.42%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 6         | 0.42%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.42%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.42%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 6         | 0.42%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 5         | 0.35%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 5         | 0.35%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 5         | 0.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 338       | 43%     |
| Qualcomm Atheros                  | 159       | 20.23%  |
| Realtek Semiconductor             | 117       | 14.89%  |
| Broadcom                          | 104       | 13.23%  |
| Broadcom Limited                  | 21        | 2.67%   |
| Ralink                            | 13        | 1.65%   |
| TP-Link                           | 10        | 1.27%   |
| Ralink Technology                 | 6         | 0.76%   |
| Sierra Wireless                   | 5         | 0.64%   |
| MediaTek                          | 3         | 0.38%   |
| Ericsson Business Mobile Networks | 3         | 0.38%   |
| TRENDnet                          | 1         | 0.13%   |
| Sitecom Europe                    | 1         | 0.13%   |
| Qualcomm                          | 1         | 0.13%   |
| Fibocom                           | 1         | 0.13%   |
| D-Link System                     | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |
| ASUSTek Computer                  | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 37        | 4.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 34        | 4.3%    |
| Intel Wireless 8260                                                                   | 33        | 4.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 31        | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 25        | 3.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 24        | 3.04%   |
| Intel Wireless 7265                                                                   | 23        | 2.91%   |
| Intel Wireless 7260                                                                   | 23        | 2.91%   |
| Intel Wi-Fi 6 AX200                                                                   | 23        | 2.91%   |
| Intel Wireless 8265 / 8275                                                            | 22        | 2.78%   |
| Intel Wi-Fi 6 AX201                                                                   | 22        | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 20        | 2.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 20        | 2.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 19        | 2.41%   |
| Intel Wireless 3165                                                                   | 16        | 2.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 15        | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 14        | 1.77%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 13        | 1.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 13        | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 13        | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 12        | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 11        | 1.39%   |
| Intel Centrino Advanced-N 6235                                                        | 11        | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 11        | 1.39%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 11        | 1.39%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 11        | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 10        | 1.27%   |
| Intel Wireless 3160                                                                   | 10        | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 9         | 1.14%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 9         | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 9         | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 9         | 1.14%   |
| Intel Centrino Advanced-N 6200                                                        | 9         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 9         | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 8         | 1.01%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 7         | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 6         | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 6         | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 6         | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 5         | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 5         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 5         | 0.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 5         | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 5         | 0.63%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 5         | 0.63%   |
| Intel WiFi Link 5100                                                                  | 5         | 0.63%   |
| Intel Ultimate N WiFi Link 5300                                                       | 5         | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 5         | 0.63%   |
| Intel Centrino Wireless-N 2230                                                        | 5         | 0.63%   |
| Intel Centrino Ultimate-N 6300                                                        | 5         | 0.63%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 5         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 4         | 0.51%   |
| Ralink MT7601U Wireless Adapter                                                       | 4         | 0.51%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                         | 4         | 0.51%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                             | 4         | 0.51%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 4         | 0.51%   |
| TP-Link TL-WN722N v2                                                                  | 3         | 0.38%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 3         | 0.38%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                                | 3         | 0.38%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 3         | 0.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 321       | 52.88%  |
| Intel                    | 122       | 20.1%   |
| Broadcom                 | 44        | 7.25%   |
| Qualcomm Atheros         | 43        | 7.08%   |
| Nvidia                   | 15        | 2.47%   |
| Marvell Technology Group | 15        | 2.47%   |
| Broadcom Limited         | 5         | 0.82%   |
| Xiaomi                   | 4         | 0.66%   |
| Huawei Technologies      | 4         | 0.66%   |
| ASIX Electronics         | 4         | 0.66%   |
| Samsung Electronics      | 3         | 0.49%   |
| Qualcomm                 | 3         | 0.49%   |
| Google                   | 3         | 0.49%   |
| OPPO Electronics         | 2         | 0.33%   |
| MediaTek                 | 2         | 0.33%   |
| Lenovo                   | 2         | 0.33%   |
| JMicron Technology       | 2         | 0.33%   |
| Hewlett-Packard          | 2         | 0.33%   |
| D-Link                   | 2         | 0.33%   |
| Apple                    | 2         | 0.33%   |
| LSI                      | 1         | 0.16%   |
| Linksys                  | 1         | 0.16%   |
| LG Electronics           | 1         | 0.16%   |
| ICS Advent               | 1         | 0.16%   |
| HMD Global               | 1         | 0.16%   |
| DisplayLink              | 1         | 0.16%   |
| Attansic Technology      | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 222       | 36.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 81        | 13.24%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 26        | 4.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 16        | 2.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 12        | 1.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 12        | 1.96%   |
| Nvidia MCP79 Ethernet                                                          | 12        | 1.96%   |
| Intel 82577LM Gigabit Network Connection                                       | 12        | 1.96%   |
| Intel Ethernet Connection I219-LM                                              | 11        | 1.8%    |
| Intel Ethernet Connection I218-LM                                              | 11        | 1.8%    |
| Intel 82567LM Gigabit Network Connection                                       | 8         | 1.31%   |
| Intel Ethernet Connection (4) I219-V                                           | 7         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 1.14%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 0.98%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 0.98%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 5         | 0.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 5         | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 5         | 0.82%   |
| Intel Ethernet Connection I219-V                                               | 5         | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 0.82%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 5         | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 3         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 3         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 3         | 0.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 3         | 0.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 3         | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 0.49%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 0.49%   |
| Huawei JNY-LX1                                                                 | 3         | 0.49%   |
| Google Nexus/Pixel Device (tether)                                             | 3         | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.49%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 3         | 0.49%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 3         | 0.49%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 3         | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.33%   |
| Qualcomm Nokia X100                                                            | 2         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.33%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.33%   |
| OPPO 9R                                                                        | 2         | 0.33%   |
| Nvidia MCP89 Ethernet                                                          | 2         | 0.33%   |
| MediaTek moto e6s                                                              | 2         | 0.33%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.33%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.33%   |
| Intel Ethernet Connection I218-V                                               | 2         | 0.33%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.33%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.33%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 0.33%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.33%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 0.33%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 0.33%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 2         | 0.33%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 2         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 744       | 55.65%  |
| Ethernet | 582       | 43.53%  |
| Modem    | 9         | 0.67%   |
| Unknown  | 2         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 642       | 84.92%  |
| Ethernet | 114       | 15.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 547       | 72.45%  |
| 1     | 190       | 25.17%  |
| 0     | 14        | 1.85%   |
| 3     | 4         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 604       | 79.68%  |
| Yes     | 153       | 20.18%  |
| Unknown | 1         | 0.13%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 269       | 41.77%  |
| Realtek Semiconductor           | 67        | 10.4%   |
| Apple                           | 65        | 10.09%  |
| Qualcomm Atheros Communications | 62        | 9.63%   |
| Broadcom                        | 39        | 6.06%   |
| Lite-On Technology              | 35        | 5.43%   |
| Foxconn / Hon Hai               | 25        | 3.88%   |
| IMC Networks                    | 18        | 2.8%    |
| Cambridge Silicon Radio         | 12        | 1.86%   |
| Toshiba                         | 11        | 1.71%   |
| Hewlett-Packard                 | 10        | 1.55%   |
| Ralink                          | 9         | 1.4%    |
| Dell                            | 9         | 1.4%    |
| Realtek                         | 5         | 0.78%   |
| Qcom                            | 2         | 0.31%   |
| ASUSTek Computer                | 2         | 0.31%   |
| Taiyo Yuden                     | 1         | 0.16%   |
| Logitech                        | 1         | 0.16%   |
| Fujitsu                         | 1         | 0.16%   |
| Foxconn International           | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 129       | 20.03%  |
| Intel AX201 Bluetooth                                                               | 44        | 6.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 41        | 6.37%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 34        | 5.28%   |
| Realtek Bluetooth Radio                                                             | 33        | 5.12%   |
| Apple Bluetooth Host Controller                                                     | 32        | 4.97%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 23        | 3.57%   |
| Intel AX200 Bluetooth                                                               | 23        | 3.57%   |
| Apple Bluetooth USB Host Controller                                                 | 20        | 3.11%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 16        | 2.48%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 15        | 2.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 12        | 1.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.71%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 1.55%   |
| Ralink RT3290 Bluetooth                                                             | 9         | 1.4%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 9         | 1.4%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 9         | 1.4%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 9         | 1.4%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 9         | 1.4%    |
| Lite-On Bluetooth Device                                                            | 8         | 1.24%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 1.24%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 1.09%   |
| Apple Bluetooth HCI                                                                 | 7         | 1.09%   |
| IMC Networks Bluetooth Radio                                                        | 6         | 0.93%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 6         | 0.93%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 6         | 0.93%   |
| Realtek Bluetooth Radio                                                             | 5         | 0.78%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 0.78%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 0.62%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.62%   |
| Lite-On Atheros Bluetooth                                                           | 4         | 0.62%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 0.62%   |
| IMC Networks Bluetooth Device                                                       | 4         | 0.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 0.62%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 4         | 0.62%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 0.62%   |
| Toshiba RT Bluetooth Radio                                                          | 3         | 0.47%   |
| Toshiba Bluetooth USB Host Controller                                               | 3         | 0.47%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 0.47%   |
| Intel AX210 Bluetooth                                                               | 3         | 0.47%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.47%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 3         | 0.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.31%   |
| Qcom Broadcom Bluetooth USB                                                         | 2         | 0.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.31%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.31%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.31%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.31%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.16%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.16%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.16%   |
| Toshiba Askey for                                                                   | 1         | 0.16%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.16%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                                             | 1         | 0.16%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 0.16%   |
| Lite-On Wireless_Device                                                             | 1         | 0.16%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.16%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.16%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 625       | 72.51%  |
| AMD                        | 124       | 14.39%  |
| Nvidia                     | 84        | 9.74%   |
| Logitech                   | 4         | 0.46%   |
| C-Media Electronics        | 4         | 0.46%   |
| Generalplus Technology     | 3         | 0.35%   |
| Realtek Semiconductor      | 2         | 0.23%   |
| GN Netcom                  | 2         | 0.23%   |
| ESS Technology             | 2         | 0.23%   |
| BEHRINGER International    | 2         | 0.23%   |
| YUAN High-Tech Development | 1         | 0.12%   |
| Texas Instruments          | 1         | 0.12%   |
| TEAC                       | 1         | 0.12%   |
| SteelSeries ApS            | 1         | 0.12%   |
| No brand                   | 1         | 0.12%   |
| Native Instruments         | 1         | 0.12%   |
| JMTek                      | 1         | 0.12%   |
| Dell                       | 1         | 0.12%   |
| Corsair                    | 1         | 0.12%   |
| Apple                      | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 107       | 10.13%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 79        | 7.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 65        | 6.16%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 53        | 5.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 44        | 4.17%   |
| Intel 8 Series HD Audio Controller                                                                | 44        | 4.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 38        | 3.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 35        | 3.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 31        | 2.94%   |
| Intel Broadwell-U Audio Controller                                                                | 31        | 2.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 29        | 2.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 26        | 2.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 26        | 2.46%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 24        | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 23        | 2.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 21        | 1.99%   |
| AMD FCH Azalia Controller                                                                         | 20        | 1.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 19        | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 18        | 1.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 18        | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 1.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 1.42%   |
| AMD High Definition Audio Controller                                                              | 15        | 1.42%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 1.23%   |
| Nvidia MCP79 High Definition Audio                                                                | 12        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 1.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 1.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 0.85%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 0.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 9         | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.66%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 0.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.57%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 0.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 0.57%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.47%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 0.47%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.47%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5         | 0.47%   |
| Nvidia MCP89 High Definition Audio                                                                | 4         | 0.38%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.38%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.28%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.28%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.28%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.28%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.19%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.19%   |
| Intel Crystal Well HD Audio Controller                                                            | 2         | 0.19%   |
| ESS Technology Asus USB DAC                                                                       | 2         | 0.19%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.19%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.19%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 84        | 29.79%  |
| SK hynix            | 56        | 19.86%  |
| Micron Technology   | 37        | 13.12%  |
| Kingston            | 24        | 8.51%   |
| Unknown             | 20        | 7.09%   |
| Elpida              | 10        | 3.55%   |
| Crucial             | 9         | 3.19%   |
| Unknown (ABCD)      | 6         | 2.13%   |
| A-DATA Technology   | 5         | 1.77%   |
| Ramaxel Technology  | 4         | 1.42%   |
| Smart               | 3         | 1.06%   |
| Nanya Technology    | 2         | 0.71%   |
| GSkill              | 2         | 0.71%   |
| G.Skill             | 2         | 0.71%   |
| Corsair             | 2         | 0.71%   |
| Transcend           | 1         | 0.35%   |
| Toshiba             | 1         | 0.35%   |
| Timetec             | 1         | 0.35%   |
| Smart Brazil        | 1         | 0.35%   |
| SHARETRONIC         | 1         | 0.35%   |
| Qimonda             | 1         | 0.35%   |
| PNY                 | 1         | 0.35%   |
| Patriot             | 1         | 0.35%   |
| Multilaser          | 1         | 0.35%   |
| Magnum Tech         | 1         | 0.35%   |
| Kllisre             | 1         | 0.35%   |
| Avant               | 1         | 0.35%   |
| AMD                 | 1         | 0.35%   |
| Aeneon              | 1         | 0.35%   |
| A Force             | 1         | 0.35%   |
| Unknown             | 1         | 0.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 7         | 2.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 6         | 1.97%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 5         | 1.64%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 4         | 1.32%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 4         | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 4         | 1.32%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 4         | 1.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.99%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 0.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 0.99%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s            | 3         | 0.99%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 3         | 0.99%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 3         | 0.99%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s               | 3         | 0.99%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 3         | 0.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.99%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 3         | 0.99%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s               | 3         | 0.99%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 3         | 0.99%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 3         | 0.99%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                      | 2         | 0.66%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s                | 2         | 0.66%   |
| Smart RAM SG564283FG8NWKF-Z1 1024MB SODIMM DDR2 800MT/s             | 2         | 0.66%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 2         | 0.66%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.66%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 2         | 0.66%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 2         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.66%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s           | 2         | 0.66%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.66%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.66%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 2         | 0.66%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s               | 2         | 0.66%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 2         | 0.66%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 2         | 0.66%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s               | 2         | 0.66%   |
| Micron RAM 16JSF25664HZ-1G4F1 2GB SODIMM 1334MT/s                   | 2         | 0.66%   |
| Kingston RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 2         | 0.66%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s             | 2         | 0.66%   |
| GSkill RAM F4-3200C22-8GRS 8192MB SODIMM DDR4 3200MT/s              | 2         | 0.66%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s               | 2         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR3 1067MT/s                         | 1         | 0.33%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 8192MB SODIMM DDR3                               | 1         | 0.33%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4266MT/s              | 1         | 0.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1067MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                        | 1         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                       | 1         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 1         | 0.33%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                          | 1         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 101       | 42.98%  |
| DDR4   | 91        | 38.72%  |
| LPDDR4 | 17        | 7.23%   |
| DDR2   | 14        | 5.96%   |
| LPDDR3 | 9         | 3.83%   |
| SDRAM  | 3         | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 214       | 89.92%  |
| Row Of Chips | 16        | 6.72%   |
| Chip         | 4         | 1.68%   |
| DIMM         | 3         | 1.26%   |
| Unknown      | 1         | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 99        | 36.26%  |
| 4096  | 93        | 34.07%  |
| 2048  | 47        | 17.22%  |
| 16384 | 22        | 8.06%   |
| 1024  | 10        | 3.66%   |
| 32768 | 2         | 0.73%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 71        | 27.31%  |
| 2667    | 47        | 18.08%  |
| 3200    | 23        | 8.85%   |
| 2133    | 23        | 8.85%   |
| 2400    | 20        | 7.69%   |
| 1334    | 16        | 6.15%   |
| 1333    | 13        | 5%      |
| 1067    | 7         | 2.69%   |
| 800     | 7         | 2.69%   |
| 667     | 7         | 2.69%   |
| 4267    | 5         | 1.92%   |
| 1066    | 4         | 1.54%   |
| 8400    | 3         | 1.15%   |
| 3266    | 3         | 1.15%   |
| 1867    | 3         | 1.15%   |
| 4266    | 2         | 0.77%   |
| 4199    | 2         | 0.77%   |
| 3733    | 1         | 0.38%   |
| 2048    | 1         | 0.38%   |
| 975     | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Canon                           | 2         | 22.22%  |
| Xerox                           | 1         | 11.11%  |
| Seiko Epson                     | 1         | 11.11%  |
| Samsung Electronics             | 1         | 11.11%  |
| Prolific Technology             | 1         | 11.11%  |
| Hewlett-Packard                 | 1         | 11.11%  |
| cab Produkttechnik GmbH & Co KG | 1         | 11.11%  |
| Brother Industries              | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Xerox Phaser 3040                        | 1         | 11.11%  |
| Seiko Epson XP-202 203 206 Series        | 1         | 11.11%  |
| Samsung M2020 Series                     | 1         | 11.11%  |
| Prolific PL2305 Parallel Port            | 1         | 11.11%  |
| HP Deskjet F4500 series                  | 1         | 11.11%  |
| Canon PIXMA MG2500 Series                | 1         | 11.11%  |
| Canon G3000 series                       | 1         | 11.11%  |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 11.11%  |
| Brother MFC-T800W                        | 1         | 11.11%  |

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


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 50%     |
| Canon CanoScan LiDE 110                                 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 164       | 23.84%  |
| Realtek Semiconductor                  | 70        | 10.17%  |
| IMC Networks                           | 60        | 8.72%   |
| Apple                                  | 53        | 7.7%    |
| Sunplus Innovation Technology          | 42        | 6.1%    |
| Microdia                               | 42        | 6.1%    |
| Acer                                   | 42        | 6.1%    |
| Quanta                                 | 36        | 5.23%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 4.65%   |
| Suyin                                  | 25        | 3.63%   |
| Syntek                                 | 20        | 2.91%   |
| Silicon Motion                         | 17        | 2.47%   |
| Alcor Micro                            | 16        | 2.33%   |
| Lite-On Technology                     | 13        | 1.89%   |
| Lenovo                                 | 10        | 1.45%   |
| Ricoh                                  | 6         | 0.87%   |
| Luxvisions Innotech Limited            | 6         | 0.87%   |
| Importek                               | 5         | 0.73%   |
| Logitech                               | 4         | 0.58%   |
| Primax Electronics                     | 3         | 0.44%   |
| LG Electronics                         | 3         | 0.44%   |
| ALi                                    | 3         | 0.44%   |
| Samsung Electronics                    | 2         | 0.29%   |
| KYE Systems (Mouse Systems)            | 2         | 0.29%   |
| Foxconn / Hon Hai                      | 2         | 0.29%   |
| Z-Star Microelectronics                | 1         | 0.15%   |
| Y Media                                | 1         | 0.15%   |
| webcam                                 | 1         | 0.15%   |
| Vimicro                                | 1         | 0.15%   |
| Unknown                                | 1         | 0.15%   |
| Sony                                   | 1         | 0.15%   |
| kingcome                               | 1         | 0.15%   |
| Jieli Technology                       | 1         | 0.15%   |
| icSpring                               | 1         | 0.15%   |
| Google                                 | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 33        | 4.78%   |
| Chicony HD Webcam                                                          | 24        | 3.48%   |
| Realtek Integrated_Webcam_HD                                               | 18        | 2.61%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 17        | 2.46%   |
| IMC Networks Integrated Camera                                             | 16        | 2.32%   |
| Apple FaceTime HD Camera                                                   | 16        | 2.32%   |
| Apple Built-in iSight                                                      | 16        | 2.32%   |
| Microdia Integrated_Webcam_HD                                              | 12        | 1.74%   |
| Syntek Integrated Camera                                                   | 11        | 1.59%   |
| Sunplus Integrated_Webcam_HD                                               | 10        | 1.45%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 10        | 1.45%   |
| Realtek USB2.0 HD UVC WebCam                                               | 9         | 1.3%    |
| Chicony HP HD Webcam [Fixed]                                               | 9         | 1.3%    |
| Realtek USB Camera                                                         | 8         | 1.16%   |
| Quanta HP TrueVision HD Camera                                             | 8         | 1.16%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 1.16%   |
| Acer Lenovo EasyCamera                                                     | 8         | 1.16%   |
| Sunplus HD WebCam                                                          | 7         | 1.01%   |
| Realtek Integrated Webcam                                                  | 7         | 1.01%   |
| Quanta HP Webcam                                                           | 7         | 1.01%   |
| Lite-On Integrated Camera                                                  | 7         | 1.01%   |
| Chicony USB 2.0 Camera                                                     | 7         | 1.01%   |
| Chicony HP HD Camera                                                       | 7         | 1.01%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 6         | 0.87%   |
| Realtek HD WebCam                                                          | 6         | 0.87%   |
| Chicony VGA WebCam                                                         | 6         | 0.87%   |
| Chicony EasyCamera                                                         | 6         | 0.87%   |
| Syntek Lenovo EasyCamera                                                   | 5         | 0.72%   |
| Silicon Motion Web Camera                                                  | 5         | 0.72%   |
| Quanta VGA WebCam                                                          | 5         | 0.72%   |
| Quanta HD User Facing                                                      | 5         | 0.72%   |
| Lenovo Integrated Webcam [R5U877]                                          | 5         | 0.72%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 5         | 0.72%   |
| Chicony TOSHIBA Web Camera - HD                                            | 5         | 0.72%   |
| Chicony HP TrueVision HD                                                   | 5         | 0.72%   |
| Chicony HP HD Webcam                                                       | 5         | 0.72%   |
| Apple FaceTime Camera                                                      | 5         | 0.72%   |
| Syntek EasyCamera                                                          | 4         | 0.58%   |
| Sunplus HP TrueVision HD Camera                                            | 4         | 0.58%   |
| Microdia Integrated Webcam                                                 | 4         | 0.58%   |
| Lenovo Integrated Webcam                                                   | 4         | 0.58%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 4         | 0.58%   |
| Chicony Lenovo EasyCamera                                                  | 4         | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 0.58%   |
| Apple FaceTime HD Camera (Built-in)                                        | 4         | 0.58%   |
| Alcor Micro USB 2.0 PC Camera                                              | 4         | 0.58%   |
| Alcor Micro USB 2.0 Camera                                                 | 4         | 0.58%   |
| Acer ThinkPad Integrated Camera                                            | 4         | 0.58%   |
| Acer HD Webcam                                                             | 4         | 0.58%   |
| Acer EasyCamera                                                            | 4         | 0.58%   |
| Acer BisonCam, NB Pro                                                      | 4         | 0.58%   |
| Suyin HP Truevision HD                                                     | 3         | 0.43%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 3         | 0.43%   |
| Sunplus ASUS USB2.0 Webcam                                                 | 3         | 0.43%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 3         | 0.43%   |
| Realtek Acer 640 x 480 laptop camera                                       | 3         | 0.43%   |
| Microdia Webcam Vitade AF                                                  | 3         | 0.43%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 3         | 0.43%   |
| Microdia Integrated Webcam HD                                              | 3         | 0.43%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 3         | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 49        | 38.58%  |
| Synaptics                  | 29        | 22.83%  |
| LighTuning Technology      | 13        | 10.24%  |
| Shenzhen Goodix Technology | 12        | 9.45%   |
| Upek                       | 9         | 7.09%   |
| Elan Microelectronics      | 7         | 5.51%   |
| AuthenTec                  | 5         | 3.94%   |
| STMicroelectronics         | 2         | 1.57%   |
| Focal-systems.Corp         | 1         | 0.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 9.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 8.66%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 7.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 5.51%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 5.51%   |
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 5.51%   |
| Validity Sensors VFS491                                                    | 6         | 4.72%   |
| Unknown                                                                    | 6         | 4.72%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 3.94%   |
| Elan ELAN:Fingerprint                                                      | 5         | 3.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 3.15%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.15%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 3.15%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.36%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.36%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.36%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.57%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.57%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.57%   |
| Synaptics  WBDI                                                            | 2         | 1.57%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.57%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.57%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.57%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.79%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.79%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.79%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.79%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.79%   |
| AuthenTec AES2810                                                          | 1         | 0.79%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.79%   |
| AuthenTec AES1600                                                          | 1         | 0.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 21        | 46.67%  |
| Alcor Micro           | 14        | 31.11%  |
| O2 Micro              | 4         | 8.89%   |
| Lenovo                | 3         | 6.67%   |
| Upek                  | 2         | 4.44%   |
| Gemalto (was Gemplus) | 1         | 2.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 31.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 24.44%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 8.89%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 6.67%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.67%   |
| Broadcom 5880                                                                | 3         | 6.67%   |
| Broadcom 58200                                                               | 3         | 6.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.44%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.22%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 508       | 66.75%  |
| 1     | 200       | 26.28%  |
| 2     | 46        | 6.04%   |
| 3     | 6         | 0.79%   |
| 7     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 126       | 40.13%  |
| Chipcard                 | 44        | 14.01%  |
| Net/wireless             | 43        | 13.69%  |
| Graphics card            | 39        | 12.42%  |
| Multimedia controller    | 26        | 8.28%   |
| Camera                   | 9         | 2.87%   |
| Bluetooth                | 9         | 2.87%   |
| Storage                  | 5         | 1.59%   |
| Net/ethernet             | 5         | 1.59%   |
| Card reader              | 4         | 1.27%   |
| Sound                    | 3         | 0.96%   |
| Communication controller | 1         | 0.32%   |

