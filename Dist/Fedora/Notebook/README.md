Fedora - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 10792

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | G15 5510                    | [3cfac2d234](https://linux-hardware.org/?probe=3cfac2d234) | Aug 12, 2023 |
| Lenovo        | ThinkPad T460p 20FXS1C30... | [08542d994e](https://linux-hardware.org/?probe=08542d994e) | Aug 12, 2023 |
| ASUSTek       | K55VD                       | [05024005e4](https://linux-hardware.org/?probe=05024005e4) | Aug 12, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [411b9f412c](https://linux-hardware.org/?probe=411b9f412c) | Aug 12, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d25ab08211](https://linux-hardware.org/?probe=d25ab08211) | Aug 12, 2023 |
| Toshiba       | Satellite C55-A             | [d1bf5ba3c3](https://linux-hardware.org/?probe=d1bf5ba3c3) | Aug 12, 2023 |
| Dell          | Latitude E7270              | [63fd1b0d6b](https://linux-hardware.org/?probe=63fd1b0d6b) | Aug 12, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [377a0e25aa](https://linux-hardware.org/?probe=377a0e25aa) | Aug 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | [7574e6b53a](https://linux-hardware.org/?probe=7574e6b53a) | Aug 11, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [c336f9aa8c](https://linux-hardware.org/?probe=c336f9aa8c) | Aug 11, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [83879b8247](https://linux-hardware.org/?probe=83879b8247) | Aug 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | [c352abad93](https://linux-hardware.org/?probe=c352abad93) | Aug 11, 2023 |
| Acer          | Aspire E5-721               | [f4abfc94d4](https://linux-hardware.org/?probe=f4abfc94d4) | Aug 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [8c449cd820](https://linux-hardware.org/?probe=8c449cd820) | Aug 11, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [29065a56ee](https://linux-hardware.org/?probe=29065a56ee) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [22fc28c382](https://linux-hardware.org/?probe=22fc28c382) | Aug 11, 2023 |
| Dell          | XPS 15 9560                 | [471e3c5077](https://linux-hardware.org/?probe=471e3c5077) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| Dell          | Latitude 5300               | [661051063f](https://linux-hardware.org/?probe=661051063f) | Aug 10, 2023 |
| Lenovo        | ThinkPad X220 4291SEN       | [b62026890a](https://linux-hardware.org/?probe=b62026890a) | Aug 10, 2023 |
| HP            | 250 G3                      | [512fd5d81f](https://linux-hardware.org/?probe=512fd5d81f) | Aug 10, 2023 |
| HP            | ProBook 430 G2              | [426901227d](https://linux-hardware.org/?probe=426901227d) | Aug 10, 2023 |
| Acer          | Aspire E5-721               | [6743c7ca9d](https://linux-hardware.org/?probe=6743c7ca9d) | Aug 10, 2023 |
| Gigabyte      | AERO 15-WA                  | [bd9f5d0f39](https://linux-hardware.org/?probe=bd9f5d0f39) | Aug 10, 2023 |
| Apple         | MacBookPro5,1               | [23fc9401d3](https://linux-hardware.org/?probe=23fc9401d3) | Aug 10, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [4446f503d5](https://linux-hardware.org/?probe=4446f503d5) | Aug 10, 2023 |
| HP            | 14                          | [8692626574](https://linux-hardware.org/?probe=8692626574) | Aug 09, 2023 |
| HP            | Laptop 14s-dq2xxx           | [bb40aa6fd9](https://linux-hardware.org/?probe=bb40aa6fd9) | Aug 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0f34656484](https://linux-hardware.org/?probe=0f34656484) | Aug 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [afa02e4c02](https://linux-hardware.org/?probe=afa02e4c02) | Aug 09, 2023 |
| Fujitsu       | UH-X                        | [e26b430aef](https://linux-hardware.org/?probe=e26b430aef) | Aug 09, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [6de592988e](https://linux-hardware.org/?probe=6de592988e) | Aug 09, 2023 |
| Acer          | Aspire A317-33              | [6dd8126a05](https://linux-hardware.org/?probe=6dd8126a05) | Aug 09, 2023 |
| HP            | Notebook                    | [bac7155006](https://linux-hardware.org/?probe=bac7155006) | Aug 09, 2023 |
| Dell          | Inspiron M5010              | [be4ad618b4](https://linux-hardware.org/?probe=be4ad618b4) | Aug 09, 2023 |
| HP            | 240 G5 Notebook PC          | [c801f4bbd0](https://linux-hardware.org/?probe=c801f4bbd0) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [a8fc44190a](https://linux-hardware.org/?probe=a8fc44190a) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [766e35e920](https://linux-hardware.org/?probe=766e35e920) | Aug 09, 2023 |
| Apple         | MacBookPro15,2              | [68e26bb5d3](https://linux-hardware.org/?probe=68e26bb5d3) | Aug 09, 2023 |
| Dell          | Latitude 7320               | [6db1867722](https://linux-hardware.org/?probe=6db1867722) | Aug 09, 2023 |
| Acer          | Aspire E5-721               | [82a8a2346a](https://linux-hardware.org/?probe=82a8a2346a) | Aug 08, 2023 |
| Dell          | Inspiron 15 3515            | [7ce5fc846b](https://linux-hardware.org/?probe=7ce5fc846b) | Aug 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [2e4e848552](https://linux-hardware.org/?probe=2e4e848552) | Aug 08, 2023 |
| Acer          | Aspire A515-51G             | [1105c8c2ea](https://linux-hardware.org/?probe=1105c8c2ea) | Aug 08, 2023 |
| Dell          | Latitude 5511               | [e9ea435e85](https://linux-hardware.org/?probe=e9ea435e85) | Aug 08, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [914ff5745c](https://linux-hardware.org/?probe=914ff5745c) | Aug 08, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [7a088aea04](https://linux-hardware.org/?probe=7a088aea04) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | [1a3b5297dd](https://linux-hardware.org/?probe=1a3b5297dd) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | [18208500ee](https://linux-hardware.org/?probe=18208500ee) | Aug 08, 2023 |
| Acer          | Aspire 4752                 | [1c68b4d24a](https://linux-hardware.org/?probe=1c68b4d24a) | Aug 08, 2023 |
| HP            | Elite x2 1012 G1            | [0ee8428f91](https://linux-hardware.org/?probe=0ee8428f91) | Aug 07, 2023 |
| Dell          | Inspiron 3505               | [e07624ae41](https://linux-hardware.org/?probe=e07624ae41) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [36b0caba9e](https://linux-hardware.org/?probe=36b0caba9e) | Aug 07, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [d989868a6b](https://linux-hardware.org/?probe=d989868a6b) | Aug 07, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [8b5e74e190](https://linux-hardware.org/?probe=8b5e74e190) | Aug 07, 2023 |
| Apple         | MacBookPro11,1              | [0a1b8d0627](https://linux-hardware.org/?probe=0a1b8d0627) | Aug 07, 2023 |
| Timi          | A7S                         | [34a354df5a](https://linux-hardware.org/?probe=34a354df5a) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [b4b049b997](https://linux-hardware.org/?probe=b4b049b997) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8633bc5aa5](https://linux-hardware.org/?probe=8633bc5aa5) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [2980681052](https://linux-hardware.org/?probe=2980681052) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [aabc0a8aee](https://linux-hardware.org/?probe=aabc0a8aee) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [08b395f8d6](https://linux-hardware.org/?probe=08b395f8d6) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [4dec7b692a](https://linux-hardware.org/?probe=4dec7b692a) | Aug 07, 2023 |
| HUAWEI        | WRTD-WXX9                   | [dc02eefe63](https://linux-hardware.org/?probe=dc02eefe63) | Aug 06, 2023 |
| Dell          | XPS 13 9310                 | [1134279f41](https://linux-hardware.org/?probe=1134279f41) | Aug 06, 2023 |
| Dell          | Inspiron 3520               | [eed6ad702b](https://linux-hardware.org/?probe=eed6ad702b) | Aug 06, 2023 |
| Dell          | Inspiron 3520               | [8a3ba73fae](https://linux-hardware.org/?probe=8a3ba73fae) | Aug 06, 2023 |
| Dell          | Inspiron N5110              | [8218626de4](https://linux-hardware.org/?probe=8218626de4) | Aug 06, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [e71ac5ca78](https://linux-hardware.org/?probe=e71ac5ca78) | Aug 06, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | [27d1d39b58](https://linux-hardware.org/?probe=27d1d39b58) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2771828543](https://linux-hardware.org/?probe=2771828543) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [f77c465da0](https://linux-hardware.org/?probe=f77c465da0) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [56c7715a6d](https://linux-hardware.org/?probe=56c7715a6d) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [6a9e7cc3e2](https://linux-hardware.org/?probe=6a9e7cc3e2) | Aug 06, 2023 |
| RCA           | 038-WT9S10WM02              | [61c1a104d2](https://linux-hardware.org/?probe=61c1a104d2) | Aug 06, 2023 |
| RCA           | 038-WT9S10WM02              | [fe15934abe](https://linux-hardware.org/?probe=fe15934abe) | Aug 06, 2023 |
| Dell          | Inspiron 15-3567            | [2e8d48f9bc](https://linux-hardware.org/?probe=2e8d48f9bc) | Aug 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [1b9794e2e3](https://linux-hardware.org/?probe=1b9794e2e3) | Aug 06, 2023 |
| COMPUMAX C... | MOBIL                       | [60293c1ac3](https://linux-hardware.org/?probe=60293c1ac3) | Aug 06, 2023 |
| Acer          | Aspire A715-72G             | [4afe306798](https://linux-hardware.org/?probe=4afe306798) | Aug 05, 2023 |
| Dell          | Venue 8 Pro 5855            | [146fa40942](https://linux-hardware.org/?probe=146fa40942) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | [6af70944d8](https://linux-hardware.org/?probe=6af70944d8) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | [1790fa9d72](https://linux-hardware.org/?probe=1790fa9d72) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | [b3c77ee42f](https://linux-hardware.org/?probe=b3c77ee42f) | Aug 05, 2023 |
| Dell          | Latitude E6230              | [cc78868322](https://linux-hardware.org/?probe=cc78868322) | Aug 05, 2023 |
| Multilaser    | PC13X                       | [2f79cffddd](https://linux-hardware.org/?probe=2f79cffddd) | Aug 05, 2023 |
| Dell          | Latitude E6220              | [636392b4bf](https://linux-hardware.org/?probe=636392b4bf) | Aug 05, 2023 |
| HP            | ProBook 440 G3              | [abb19010d2](https://linux-hardware.org/?probe=abb19010d2) | Aug 05, 2023 |
| System76      | Darter Pro                  | [55a328cd9a](https://linux-hardware.org/?probe=55a328cd9a) | Aug 05, 2023 |
| Corsair       | Voyager a1600               | [6dea5f2c0c](https://linux-hardware.org/?probe=6dea5f2c0c) | Aug 04, 2023 |
| Apple         | MacBookPro5,5               | [ccbf514dc7](https://linux-hardware.org/?probe=ccbf514dc7) | Aug 04, 2023 |
| HP            | Laptop 15s-eq1xxx           | [e6e6cc7b2e](https://linux-hardware.org/?probe=e6e6cc7b2e) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7bc7a7e01c](https://linux-hardware.org/?probe=7bc7a7e01c) | Aug 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [fcc05278d6](https://linux-hardware.org/?probe=fcc05278d6) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b8fa3962ed](https://linux-hardware.org/?probe=b8fa3962ed) | Aug 04, 2023 |
| Acer          | Swift SF114-34              | [2af2b0aecb](https://linux-hardware.org/?probe=2af2b0aecb) | Aug 04, 2023 |
| Dell          | Latitude 7400               | [48e2858e56](https://linux-hardware.org/?probe=48e2858e56) | Aug 04, 2023 |
| Dell          | Latitude 3420               | [cdecb64c4a](https://linux-hardware.org/?probe=cdecb64c4a) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [195716ccf3](https://linux-hardware.org/?probe=195716ccf3) | Aug 04, 2023 |
| Dell          | Latitude 5480               | [b682f988e8](https://linux-hardware.org/?probe=b682f988e8) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [5a9a057759](https://linux-hardware.org/?probe=5a9a057759) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [367f14eae6](https://linux-hardware.org/?probe=367f14eae6) | Aug 04, 2023 |
| HP            | ENVY Notebook               | [90325282da](https://linux-hardware.org/?probe=90325282da) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [082f92da07](https://linux-hardware.org/?probe=082f92da07) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [1078db460a](https://linux-hardware.org/?probe=1078db460a) | Aug 04, 2023 |
| HP            | Laptop 15-fd0xxx            | [8f3b8dea26](https://linux-hardware.org/?probe=8f3b8dea26) | Aug 04, 2023 |
| ASUSTek       | UX490UAR                    | [6a305978e3](https://linux-hardware.org/?probe=6a305978e3) | Aug 03, 2023 |
| Dell          | Latitude E6510              | [b32213c71d](https://linux-hardware.org/?probe=b32213c71d) | Aug 03, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | [ca0d3636a5](https://linux-hardware.org/?probe=ca0d3636a5) | Aug 03, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | [3552dd7642](https://linux-hardware.org/?probe=3552dd7642) | Aug 03, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [620397fdc9](https://linux-hardware.org/?probe=620397fdc9) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [882d963e19](https://linux-hardware.org/?probe=882d963e19) | Aug 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [0cf8e99478](https://linux-hardware.org/?probe=0cf8e99478) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [38d0bcf5d1](https://linux-hardware.org/?probe=38d0bcf5d1) | Aug 03, 2023 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [610fdfd850](https://linux-hardware.org/?probe=610fdfd850) | Aug 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7d96f87e00](https://linux-hardware.org/?probe=7d96f87e00) | Aug 03, 2023 |
| Lenovo        | Z50-70 20354                | [c741db51a0](https://linux-hardware.org/?probe=c741db51a0) | Aug 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7df997ee08](https://linux-hardware.org/?probe=7df997ee08) | Aug 03, 2023 |
| Lenovo        | ThinkPad X240 20AMS1RR0D    | [dcf2bedb58](https://linux-hardware.org/?probe=dcf2bedb58) | Aug 03, 2023 |
| ASUSTek       | K55VD                       | [6478fd4e76](https://linux-hardware.org/?probe=6478fd4e76) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | [25dcc9a7c5](https://linux-hardware.org/?probe=25dcc9a7c5) | Aug 03, 2023 |
| Dell          | Latitude E7470              | [7c8c07214a](https://linux-hardware.org/?probe=7c8c07214a) | Aug 03, 2023 |
| Toshiba       | Satellite C70-B             | [877d855f27](https://linux-hardware.org/?probe=877d855f27) | Aug 02, 2023 |
| Dell          | Inspiron 1525               | [fa53c99b17](https://linux-hardware.org/?probe=fa53c99b17) | Aug 02, 2023 |
| Dell          | Latitude E7470              | [b672c65f9b](https://linux-hardware.org/?probe=b672c65f9b) | Aug 02, 2023 |
| Acer          | Aspire A715-72G             | [d0bad7993f](https://linux-hardware.org/?probe=d0bad7993f) | Aug 02, 2023 |
| Dell          | System XPS L322X            | [dbe168d1a1](https://linux-hardware.org/?probe=dbe168d1a1) | Aug 02, 2023 |
| ASUSTek       | X750JN                      | [6f7dc2198b](https://linux-hardware.org/?probe=6f7dc2198b) | Aug 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | [491aec1ea1](https://linux-hardware.org/?probe=491aec1ea1) | Aug 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [517b498a25](https://linux-hardware.org/?probe=517b498a25) | Aug 02, 2023 |
| HUAWEI        | WRTD-WXX9                   | [18396303b8](https://linux-hardware.org/?probe=18396303b8) | Aug 02, 2023 |
| Dell          | XPS 9320                    | [3abc4aaf82](https://linux-hardware.org/?probe=3abc4aaf82) | Aug 02, 2023 |
| HP            | Dragonfly Pro               | [630670f052](https://linux-hardware.org/?probe=630670f052) | Aug 01, 2023 |
| Dell          | Precision 7550              | [ab0d21bb4e](https://linux-hardware.org/?probe=ab0d21bb4e) | Aug 01, 2023 |
| HP            | Laptop 15-db0xxx            | [2d7cbca56b](https://linux-hardware.org/?probe=2d7cbca56b) | Aug 01, 2023 |
| Dell          | Inspiron 15-3573            | [e29b3656ee](https://linux-hardware.org/?probe=e29b3656ee) | Aug 01, 2023 |
| HP            | ProBook 6475b               | [c3cfc235fe](https://linux-hardware.org/?probe=c3cfc235fe) | Aug 01, 2023 |
| HP            | EliteBook Folio 1040 G2     | [752821ae1a](https://linux-hardware.org/?probe=752821ae1a) | Aug 01, 2023 |
| HP            | EliteBook Folio 1040 G2     | [b847ac4535](https://linux-hardware.org/?probe=b847ac4535) | Aug 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [1dfc12fc6c](https://linux-hardware.org/?probe=1dfc12fc6c) | Jul 31, 2023 |
| Acer          | Aspire V3-571               | [9b9830aedf](https://linux-hardware.org/?probe=9b9830aedf) | Jul 31, 2023 |
| HP            | 255 G8 Notebook PC          | [b42946849e](https://linux-hardware.org/?probe=b42946849e) | Jul 31, 2023 |
| MSI           | Katana GF66 12UC            | [49a431c092](https://linux-hardware.org/?probe=49a431c092) | Jul 31, 2023 |
| MSI           | GE75 Raider 10SE            | [995b9ae73e](https://linux-hardware.org/?probe=995b9ae73e) | Jul 31, 2023 |
| HP            | Laptop 15-dw0xxx            | [08e20bb994](https://linux-hardware.org/?probe=08e20bb994) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50 20EQS20D00     | [4ef8aa09c6](https://linux-hardware.org/?probe=4ef8aa09c6) | Jul 31, 2023 |
| HP            | ProBook 440 G3              | [beea8be008](https://linux-hardware.org/?probe=beea8be008) | Jul 30, 2023 |
| Apple         | MacBookAir3,1               | [9a3416654f](https://linux-hardware.org/?probe=9a3416654f) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5bf8462b77](https://linux-hardware.org/?probe=5bf8462b77) | Jul 30, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [5ce91f2c11](https://linux-hardware.org/?probe=5ce91f2c11) | Jul 30, 2023 |
| HP            | Pavilion 15                 | [7dcc58cdf2](https://linux-hardware.org/?probe=7dcc58cdf2) | Jul 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [f641b9c622](https://linux-hardware.org/?probe=f641b9c622) | Jul 30, 2023 |
| Lenovo        | WEI6 15 ITL 82F2            | [d30f44ebbb](https://linux-hardware.org/?probe=d30f44ebbb) | Jul 30, 2023 |
| ASUSTek       | P552LA                      | [d84e6d9683](https://linux-hardware.org/?probe=d84e6d9683) | Jul 30, 2023 |
| MSI           | Bravo 15 B5DD               | [d9d3f5bce4](https://linux-hardware.org/?probe=d9d3f5bce4) | Jul 30, 2023 |
| Sony          | SVE14A2V2RS                 | [adc151e590](https://linux-hardware.org/?probe=adc151e590) | Jul 30, 2023 |
| Dell          | Inspiron M5010              | [8608f29a0f](https://linux-hardware.org/?probe=8608f29a0f) | Jul 30, 2023 |
| Dell          | XPS 13 9370                 | [529bf65ac4](https://linux-hardware.org/?probe=529bf65ac4) | Jul 30, 2023 |
| HP            | ENVY Laptop 17-cg1xxx       | [16545b3964](https://linux-hardware.org/?probe=16545b3964) | Jul 30, 2023 |
| Lenovo        | ThinkPad T490 20N3S5XF01    | [942cb3149b](https://linux-hardware.org/?probe=942cb3149b) | Jul 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [cd073a7899](https://linux-hardware.org/?probe=cd073a7899) | Jul 29, 2023 |
| Dell          | Inspiron 5577               | [10b634ac99](https://linux-hardware.org/?probe=10b634ac99) | Jul 29, 2023 |
| HP            | Beats 15                    | [933bd63249](https://linux-hardware.org/?probe=933bd63249) | Jul 29, 2023 |
| HP            | Beats 15                    | [acea7d6786](https://linux-hardware.org/?probe=acea7d6786) | Jul 29, 2023 |
| Lenovo        | ThinkPad T490 20N20031US    | [64e178e433](https://linux-hardware.org/?probe=64e178e433) | Jul 29, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [dbcda8f4d0](https://linux-hardware.org/?probe=dbcda8f4d0) | Jul 29, 2023 |
| Lenovo        | Unknown                     | [a1dac68b95](https://linux-hardware.org/?probe=a1dac68b95) | Jul 29, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [32ad81bc5d](https://linux-hardware.org/?probe=32ad81bc5d) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [95e189ee7a](https://linux-hardware.org/?probe=95e189ee7a) | Jul 29, 2023 |
| HP            | ProBook 4530s               | [884d64edd7](https://linux-hardware.org/?probe=884d64edd7) | Jul 29, 2023 |
| Samsung       | 550XDA                      | [c140c9176e](https://linux-hardware.org/?probe=c140c9176e) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | [dd2b310ecf](https://linux-hardware.org/?probe=dd2b310ecf) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | [b8e059a47d](https://linux-hardware.org/?probe=b8e059a47d) | Jul 29, 2023 |
| GPD           | G1621-02                    | [1710e0f480](https://linux-hardware.org/?probe=1710e0f480) | Jul 29, 2023 |
| Dell          | XPS 9320                    | [4000df5584](https://linux-hardware.org/?probe=4000df5584) | Jul 29, 2023 |
| Dell          | Latitude 5400               | [9416ce803c](https://linux-hardware.org/?probe=9416ce803c) | Jul 28, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | [75e93aaa88](https://linux-hardware.org/?probe=75e93aaa88) | Jul 28, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [ea4fee91b6](https://linux-hardware.org/?probe=ea4fee91b6) | Jul 28, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | [730caebd96](https://linux-hardware.org/?probe=730caebd96) | Jul 28, 2023 |
| HUAWEI        | HVY-WXX9                    | [1c3edafdf4](https://linux-hardware.org/?probe=1c3edafdf4) | Jul 28, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [ba7c69f7e0](https://linux-hardware.org/?probe=ba7c69f7e0) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | [2e6ab71954](https://linux-hardware.org/?probe=2e6ab71954) | Jul 28, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [4439f26a90](https://linux-hardware.org/?probe=4439f26a90) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5497a92cf](https://linux-hardware.org/?probe=f5497a92cf) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | [058f75de84](https://linux-hardware.org/?probe=058f75de84) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | [c26daef72c](https://linux-hardware.org/?probe=c26daef72c) | Jul 28, 2023 |
| Dell          | XPS 13 9380                 | [b784cbe3ab](https://linux-hardware.org/?probe=b784cbe3ab) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4bd819d37b](https://linux-hardware.org/?probe=4bd819d37b) | Jul 28, 2023 |
| Acer          | Aspire A515-45              | [6287e66ff2](https://linux-hardware.org/?probe=6287e66ff2) | Jul 27, 2023 |
| Apple         | MacBookAir5,1               | [da2904da80](https://linux-hardware.org/?probe=da2904da80) | Jul 27, 2023 |
| Lenovo        | ThinkPad E490 20N80029RT    | [69cf27eaae](https://linux-hardware.org/?probe=69cf27eaae) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [1b3e699a2a](https://linux-hardware.org/?probe=1b3e699a2a) | Jul 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [2c2dfaa670](https://linux-hardware.org/?probe=2c2dfaa670) | Jul 27, 2023 |
| HONOR         | BMH-WCX9                    | [865315bd06](https://linux-hardware.org/?probe=865315bd06) | Jul 27, 2023 |
| Dell          | Latitude 5530               | [165d2cd3b1](https://linux-hardware.org/?probe=165d2cd3b1) | Jul 27, 2023 |
| Toshiba       | Satellite C70-B             | [56489a32b2](https://linux-hardware.org/?probe=56489a32b2) | Jul 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [32b57e4adb](https://linux-hardware.org/?probe=32b57e4adb) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [87d69792fb](https://linux-hardware.org/?probe=87d69792fb) | Jul 26, 2023 |
| Dell          | Latitude E6400              | [a9333607eb](https://linux-hardware.org/?probe=a9333607eb) | Jul 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b8b95820c1](https://linux-hardware.org/?probe=b8b95820c1) | Jul 26, 2023 |
| HP            | Pavilion 11 x360 PC         | [8daa291377](https://linux-hardware.org/?probe=8daa291377) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [83097985a2](https://linux-hardware.org/?probe=83097985a2) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | [2e810b1c93](https://linux-hardware.org/?probe=2e810b1c93) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | [4171fc8925](https://linux-hardware.org/?probe=4171fc8925) | Jul 26, 2023 |
| Dell          | Latitude E7440              | [9b8234d640](https://linux-hardware.org/?probe=9b8234d640) | Jul 26, 2023 |
| Dell          | Inspiron 13 5310            | [5f44d0b1d8](https://linux-hardware.org/?probe=5f44d0b1d8) | Jul 26, 2023 |
| HUAWEI        | NBM-WXX9                    | [30cb22d368](https://linux-hardware.org/?probe=30cb22d368) | Jul 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [f321614376](https://linux-hardware.org/?probe=f321614376) | Jul 25, 2023 |
| HUAWEI        | NBM-WXX9                    | [b28bc4ba91](https://linux-hardware.org/?probe=b28bc4ba91) | Jul 25, 2023 |
| Dell          | Inspiron 3501               | [62bcc903fd](https://linux-hardware.org/?probe=62bcc903fd) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [0059745bdf](https://linux-hardware.org/?probe=0059745bdf) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [90beff8e65](https://linux-hardware.org/?probe=90beff8e65) | Jul 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [bd31324aeb](https://linux-hardware.org/?probe=bd31324aeb) | Jul 25, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [da046587dc](https://linux-hardware.org/?probe=da046587dc) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | [8cf3728f9b](https://linux-hardware.org/?probe=8cf3728f9b) | Jul 25, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [c49c2e7a5a](https://linux-hardware.org/?probe=c49c2e7a5a) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [53de15710b](https://linux-hardware.org/?probe=53de15710b) | Jul 24, 2023 |
| Fujitsu       | CELSIUS H700                | [8a23e1d76a](https://linux-hardware.org/?probe=8a23e1d76a) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | [61646d77f1](https://linux-hardware.org/?probe=61646d77f1) | Jul 24, 2023 |
| MSI           | Summit E16Flip A12UCT       | [daf09efe6e](https://linux-hardware.org/?probe=daf09efe6e) | Jul 24, 2023 |
| Lenovo        | G500s 20245                 | [fbfa8af465](https://linux-hardware.org/?probe=fbfa8af465) | Jul 24, 2023 |
| Acer          | Aspire A315-59              | [8ecb2eb1fc](https://linux-hardware.org/?probe=8ecb2eb1fc) | Jul 24, 2023 |
| Dell          | XPS 15 9510                 | [84c7ea08c6](https://linux-hardware.org/?probe=84c7ea08c6) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [4f06d87bd5](https://linux-hardware.org/?probe=4f06d87bd5) | Jul 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | [82a4cfcd9f](https://linux-hardware.org/?probe=82a4cfcd9f) | Jul 23, 2023 |
| ASUSTek       | H170M-PLUS                  | [f17fd3bbe1](https://linux-hardware.org/?probe=f17fd3bbe1) | Jul 23, 2023 |
| HP            | 250 G1                      | [deab96c404](https://linux-hardware.org/?probe=deab96c404) | Jul 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [ff5e295a5d](https://linux-hardware.org/?probe=ff5e295a5d) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [6c0c0671df](https://linux-hardware.org/?probe=6c0c0671df) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [28340d4ad4](https://linux-hardware.org/?probe=28340d4ad4) | Jul 23, 2023 |
| Dell          | Inspiron 5566               | [6323d6b43c](https://linux-hardware.org/?probe=6323d6b43c) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [49cc99fa7e](https://linux-hardware.org/?probe=49cc99fa7e) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [994ae7ffec](https://linux-hardware.org/?probe=994ae7ffec) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [9c92b34677](https://linux-hardware.org/?probe=9c92b34677) | Jul 23, 2023 |
| Lenovo        | Legion 5 15IMH6 82NL        | [f12c3b23e5](https://linux-hardware.org/?probe=f12c3b23e5) | Jul 22, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [ea078c7fb9](https://linux-hardware.org/?probe=ea078c7fb9) | Jul 22, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20HE... | [e6320dd4ae](https://linux-hardware.org/?probe=e6320dd4ae) | Jul 22, 2023 |
| Dell          | Precision M4700             | [0a5346a25d](https://linux-hardware.org/?probe=0a5346a25d) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [ba42ca5ace](https://linux-hardware.org/?probe=ba42ca5ace) | Jul 22, 2023 |
| HP            | 240 G6 Notebook PC          | [ec2be7713c](https://linux-hardware.org/?probe=ec2be7713c) | Jul 22, 2023 |
| HP            | Notebook                    | [fde29b5a32](https://linux-hardware.org/?probe=fde29b5a32) | Jul 22, 2023 |
| Notebook      | PE60RNE_RND_RNC             | [5f2993b629](https://linux-hardware.org/?probe=5f2993b629) | Jul 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c1e386e9cc](https://linux-hardware.org/?probe=c1e386e9cc) | Jul 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | [27b5dabe8d](https://linux-hardware.org/?probe=27b5dabe8d) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [d16a211675](https://linux-hardware.org/?probe=d16a211675) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [32ec9929c9](https://linux-hardware.org/?probe=32ec9929c9) | Jul 21, 2023 |
| Toshiba       | TECRA A50-A                 | [e96ff00334](https://linux-hardware.org/?probe=e96ff00334) | Jul 21, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [fa4def4ece](https://linux-hardware.org/?probe=fa4def4ece) | Jul 21, 2023 |
| Avell High... | B.ON                        | [8269a683ef](https://linux-hardware.org/?probe=8269a683ef) | Jul 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [d163198c13](https://linux-hardware.org/?probe=d163198c13) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [b541d17031](https://linux-hardware.org/?probe=b541d17031) | Jul 21, 2023 |
| Toshiba       | Satellite C70-B             | [cf2d22469b](https://linux-hardware.org/?probe=cf2d22469b) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5224cc55eb](https://linux-hardware.org/?probe=5224cc55eb) | Jul 20, 2023 |
| Dell          | Inspiron 15 5510            | [df2bfbf3e1](https://linux-hardware.org/?probe=df2bfbf3e1) | Jul 20, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [6bc352838a](https://linux-hardware.org/?probe=6bc352838a) | Jul 20, 2023 |
| Apple         | MacBookAir6,1               | [dd441dfa0d](https://linux-hardware.org/?probe=dd441dfa0d) | Jul 20, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [a1f316c8c9](https://linux-hardware.org/?probe=a1f316c8c9) | Jul 20, 2023 |
| Acer          | Nitro AN515-58              | [18a6e9f055](https://linux-hardware.org/?probe=18a6e9f055) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [c7e1f17f9e](https://linux-hardware.org/?probe=c7e1f17f9e) | Jul 20, 2023 |
| Apple         | MacBookPro5,5               | [af457a5412](https://linux-hardware.org/?probe=af457a5412) | Jul 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [e99bf7a4be](https://linux-hardware.org/?probe=e99bf7a4be) | Jul 20, 2023 |
| Dell          | Latitude 5420               | [ea97d72c47](https://linux-hardware.org/?probe=ea97d72c47) | Jul 20, 2023 |
| Lenovo        | Z50-70 20354                | [f92f9065bc](https://linux-hardware.org/?probe=f92f9065bc) | Jul 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [fc26baabc9](https://linux-hardware.org/?probe=fc26baabc9) | Jul 19, 2023 |
| MSI           | Sword 17 A11UD              | [fd2864f7e1](https://linux-hardware.org/?probe=fd2864f7e1) | Jul 19, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0C800     | [b894a6d96b](https://linux-hardware.org/?probe=b894a6d96b) | Jul 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [38c5f4d547](https://linux-hardware.org/?probe=38c5f4d547) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [e2cf7ed35f](https://linux-hardware.org/?probe=e2cf7ed35f) | Jul 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [360ee7202f](https://linux-hardware.org/?probe=360ee7202f) | Jul 18, 2023 |
| HP            | Laptop 15-dw0xxx            | [ba24f3bb61](https://linux-hardware.org/?probe=ba24f3bb61) | Jul 18, 2023 |
| HP            | Notebook                    | [4498c757a7](https://linux-hardware.org/?probe=4498c757a7) | Jul 18, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [3649d91857](https://linux-hardware.org/?probe=3649d91857) | Jul 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5d3e13fc77](https://linux-hardware.org/?probe=5d3e13fc77) | Jul 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [96585144ab](https://linux-hardware.org/?probe=96585144ab) | Jul 18, 2023 |
| Dell          | XPS 13 9370                 | [ea47e53a45](https://linux-hardware.org/?probe=ea47e53a45) | Jul 18, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [c4ab55ea69](https://linux-hardware.org/?probe=c4ab55ea69) | Jul 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [fe1ab04658](https://linux-hardware.org/?probe=fe1ab04658) | Jul 18, 2023 |
| MSI           | Creator 17 A10SE            | [775c65db16](https://linux-hardware.org/?probe=775c65db16) | Jul 17, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [14defb538e](https://linux-hardware.org/?probe=14defb538e) | Jul 17, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [3a7fbf07fa](https://linux-hardware.org/?probe=3a7fbf07fa) | Jul 17, 2023 |
| Unknown       | Unknown                     | [2bda9f913a](https://linux-hardware.org/?probe=2bda9f913a) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [3de307450d](https://linux-hardware.org/?probe=3de307450d) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [5633b6ed54](https://linux-hardware.org/?probe=5633b6ed54) | Jul 17, 2023 |
| HP            | Laptop 14-cf2xxx            | [04dce054f4](https://linux-hardware.org/?probe=04dce054f4) | Jul 17, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | [9c1cb1fd39](https://linux-hardware.org/?probe=9c1cb1fd39) | Jul 16, 2023 |
| Gigabyte      | AORUS 17 YE5                | [9c17ae5e55](https://linux-hardware.org/?probe=9c17ae5e55) | Jul 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [ec4db25eb9](https://linux-hardware.org/?probe=ec4db25eb9) | Jul 16, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | [99b59160a1](https://linux-hardware.org/?probe=99b59160a1) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | [999de9eeb2](https://linux-hardware.org/?probe=999de9eeb2) | Jul 16, 2023 |
| Lenovo        | G50-70 20351                | [46a3598028](https://linux-hardware.org/?probe=46a3598028) | Jul 16, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BY... | [1a0f8c842b](https://linux-hardware.org/?probe=1a0f8c842b) | Jul 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [0093aba5fd](https://linux-hardware.org/?probe=0093aba5fd) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6b4e2c6a3e](https://linux-hardware.org/?probe=6b4e2c6a3e) | Jul 16, 2023 |
| Compaq        | 420                         | [e5b8695df7](https://linux-hardware.org/?probe=e5b8695df7) | Jul 16, 2023 |
| MSI           | GE72MVR 7RG                 | [c1834b63c2](https://linux-hardware.org/?probe=c1834b63c2) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8c3486fa69](https://linux-hardware.org/?probe=8c3486fa69) | Jul 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [069bfd995c](https://linux-hardware.org/?probe=069bfd995c) | Jul 15, 2023 |
| Apple         | MacBookAir7,2               | [f4bcea4686](https://linux-hardware.org/?probe=f4bcea4686) | Jul 15, 2023 |
| HP            | ZBook Power 15.6 inch G1... | [c2042a2e0e](https://linux-hardware.org/?probe=c2042a2e0e) | Jul 15, 2023 |
| Apple         | MacBookAir7,2               | [d2b32f5512](https://linux-hardware.org/?probe=d2b32f5512) | Jul 15, 2023 |
| HP            | ProBook 640 G1              | [d7512ceea8](https://linux-hardware.org/?probe=d7512ceea8) | Jul 15, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [7872b8a730](https://linux-hardware.org/?probe=7872b8a730) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | [fab0c2fb26](https://linux-hardware.org/?probe=fab0c2fb26) | Jul 15, 2023 |
| Timi          | Mi NoteBook Ultra           | [94f963ff8c](https://linux-hardware.org/?probe=94f963ff8c) | Jul 15, 2023 |
| Dell          | G5 5505                     | [ba144013b3](https://linux-hardware.org/?probe=ba144013b3) | Jul 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c9cc25539e](https://linux-hardware.org/?probe=c9cc25539e) | Jul 15, 2023 |
| Acer          | Aspire V5-571G              | [e49b457f5b](https://linux-hardware.org/?probe=e49b457f5b) | Jul 15, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [d39c88d40a](https://linux-hardware.org/?probe=d39c88d40a) | Jul 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [5fe3ea6d25](https://linux-hardware.org/?probe=5fe3ea6d25) | Jul 15, 2023 |
| Toshiba       | Satellite C70-B             | [9727ab2451](https://linux-hardware.org/?probe=9727ab2451) | Jul 14, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [62a4efa95d](https://linux-hardware.org/?probe=62a4efa95d) | Jul 14, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [14b5fe64fa](https://linux-hardware.org/?probe=14b5fe64fa) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d3c3cdb439](https://linux-hardware.org/?probe=d3c3cdb439) | Jul 14, 2023 |
| Acer          | Aspire V5-571G              | [e606ef8f63](https://linux-hardware.org/?probe=e606ef8f63) | Jul 14, 2023 |
| Dell          | Precision 7540              | [c862752535](https://linux-hardware.org/?probe=c862752535) | Jul 14, 2023 |
| Dell          | Inspiron 15 3520            | [163766c886](https://linux-hardware.org/?probe=163766c886) | Jul 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1e2b959156](https://linux-hardware.org/?probe=1e2b959156) | Jul 14, 2023 |
| Lenovo        | Legion R9000K2021H 82N6     | [4c8fc2482e](https://linux-hardware.org/?probe=4c8fc2482e) | Jul 14, 2023 |
| Dell          | Latitude 7490               | [3ea6ad0e30](https://linux-hardware.org/?probe=3ea6ad0e30) | Jul 14, 2023 |
| Google        | Droid                       | [9b77a9ba04](https://linux-hardware.org/?probe=9b77a9ba04) | Jul 14, 2023 |
| Apple         | MacBookPro8,1               | [d2d9d84e27](https://linux-hardware.org/?probe=d2d9d84e27) | Jul 13, 2023 |
| Alienware     | x15 R1                      | [a72051a57e](https://linux-hardware.org/?probe=a72051a57e) | Jul 13, 2023 |
| Aava Mobil... | INARI10-WLAN-1              | [46d98ecf9a](https://linux-hardware.org/?probe=46d98ecf9a) | Jul 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [cf9bdab1ee](https://linux-hardware.org/?probe=cf9bdab1ee) | Jul 13, 2023 |
| Apple         | MacBookPro10,1              | [adad96c487](https://linux-hardware.org/?probe=adad96c487) | Jul 13, 2023 |
| Aava Mobil... | INARI10-WLAN-1              | [d605371dc3](https://linux-hardware.org/?probe=d605371dc3) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS50T0Q    | [0d5f86f700](https://linux-hardware.org/?probe=0d5f86f700) | Jul 13, 2023 |
| Lenovo        | ThinkPad T61 6465CTO        | [fcf6ce5b9e](https://linux-hardware.org/?probe=fcf6ce5b9e) | Jul 13, 2023 |
| MSI           | Katana GF66 11UC            | [d22ab22240](https://linux-hardware.org/?probe=d22ab22240) | Jul 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 2a 21AB... | [63f31c01af](https://linux-hardware.org/?probe=63f31c01af) | Jul 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [15067533b3](https://linux-hardware.org/?probe=15067533b3) | Jul 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2a 21AB... | [e84be6ee7e](https://linux-hardware.org/?probe=e84be6ee7e) | Jul 12, 2023 |
| HP            | Laptop 15t-dy200            | [ef2fb33b01](https://linux-hardware.org/?probe=ef2fb33b01) | Jul 12, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ad18a95d12](https://linux-hardware.org/?probe=ad18a95d12) | Jul 12, 2023 |
| MSI           | Alpha 15 A4DEK              | [cbae5fed49](https://linux-hardware.org/?probe=cbae5fed49) | Jul 12, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [779f922cbb](https://linux-hardware.org/?probe=779f922cbb) | Jul 12, 2023 |
| Dell          | Inspiron 5590               | [f3c9995017](https://linux-hardware.org/?probe=f3c9995017) | Jul 12, 2023 |
| MSI           | GF63 Thin 9SCSR             | [835e924f6d](https://linux-hardware.org/?probe=835e924f6d) | Jul 12, 2023 |
| MSI           | GF63 Thin 9SCSR             | [7bf81133fc](https://linux-hardware.org/?probe=7bf81133fc) | Jul 12, 2023 |
| MSI           | GF65 Thin 10UE              | [414c5bc2c0](https://linux-hardware.org/?probe=414c5bc2c0) | Jul 12, 2023 |
| Dell          | XPS 13 9305                 | [27df8fc0e5](https://linux-hardware.org/?probe=27df8fc0e5) | Jul 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [eccd385af4](https://linux-hardware.org/?probe=eccd385af4) | Jul 11, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [8267a42a4f](https://linux-hardware.org/?probe=8267a42a4f) | Jul 11, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [161a78ce7d](https://linux-hardware.org/?probe=161a78ce7d) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [aea754f076](https://linux-hardware.org/?probe=aea754f076) | Jul 11, 2023 |
| MSI           | Katana GF66 12UC            | [aac3e629d3](https://linux-hardware.org/?probe=aac3e629d3) | Jul 11, 2023 |
| Dell          | Precision 5680              | [e1363522ee](https://linux-hardware.org/?probe=e1363522ee) | Jul 11, 2023 |
| Acer          | Nitro AN515-58              | [76d89b3b3b](https://linux-hardware.org/?probe=76d89b3b3b) | Jul 11, 2023 |
| Dell          | Latitude E5540              | [cdad6cb751](https://linux-hardware.org/?probe=cdad6cb751) | Jul 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9cc59dffca](https://linux-hardware.org/?probe=9cc59dffca) | Jul 11, 2023 |
| ASUSTek       | X555LAB                     | [464293fd0e](https://linux-hardware.org/?probe=464293fd0e) | Jul 11, 2023 |
| Lenovo        | ThinkPad Edge 0578P6G       | [e79fbdad2d](https://linux-hardware.org/?probe=e79fbdad2d) | Jul 10, 2023 |
| MSI           | GE66 Raider 10SFS           | [de2112a82f](https://linux-hardware.org/?probe=de2112a82f) | Jul 10, 2023 |
| ASUSTek       | N61Vn                       | [6bbb5b2105](https://linux-hardware.org/?probe=6bbb5b2105) | Jul 10, 2023 |
| ASUSTek       | N61Vn                       | [dd1a0f1acf](https://linux-hardware.org/?probe=dd1a0f1acf) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [4e02ec47c0](https://linux-hardware.org/?probe=4e02ec47c0) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | [d73ac20739](https://linux-hardware.org/?probe=d73ac20739) | Jul 10, 2023 |
| HUAWEI        | HLYL-WXX9                   | [480ee8d732](https://linux-hardware.org/?probe=480ee8d732) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | [beef3128c2](https://linux-hardware.org/?probe=beef3128c2) | Jul 10, 2023 |
| HP            | EliteBook 840 G6            | [52fafabf05](https://linux-hardware.org/?probe=52fafabf05) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | [cf25605b3a](https://linux-hardware.org/?probe=cf25605b3a) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | [3c3c2ac038](https://linux-hardware.org/?probe=3c3c2ac038) | Jul 10, 2023 |
| Apple         | MacBookPro9,2               | [55896d87cf](https://linux-hardware.org/?probe=55896d87cf) | Jul 10, 2023 |
| Dell          | Inspiron 5515               | [0060a91b79](https://linux-hardware.org/?probe=0060a91b79) | Jul 10, 2023 |
| Dell          | Precision M4800             | [ef29f43a6f](https://linux-hardware.org/?probe=ef29f43a6f) | Jul 09, 2023 |
| Samsung       | 950XDB/951XDB/950XDY        | [5e41313f45](https://linux-hardware.org/?probe=5e41313f45) | Jul 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3a1baa8f6c](https://linux-hardware.org/?probe=3a1baa8f6c) | Jul 09, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [f79821f2eb](https://linux-hardware.org/?probe=f79821f2eb) | Jul 09, 2023 |
| Dell          | Latitude E6230              | [dd453671f3](https://linux-hardware.org/?probe=dd453671f3) | Jul 09, 2023 |
| Dell          | Latitude 5400               | [e8b701bf4e](https://linux-hardware.org/?probe=e8b701bf4e) | Jul 09, 2023 |
| Dell          | Latitude 5320               | [55d5b4447a](https://linux-hardware.org/?probe=55d5b4447a) | Jul 09, 2023 |
| MSI           | Stealth 16Studio A13VG      | [e16527e244](https://linux-hardware.org/?probe=e16527e244) | Jul 09, 2023 |
| Dell          | Latitude 7490               | [2a7f6b974b](https://linux-hardware.org/?probe=2a7f6b974b) | Jul 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [50f23f3476](https://linux-hardware.org/?probe=50f23f3476) | Jul 09, 2023 |
| HP            | G42                         | [e215b464bf](https://linux-hardware.org/?probe=e215b464bf) | Jul 09, 2023 |
| Dell          | Latitude 3500               | [38a0d6b099](https://linux-hardware.org/?probe=38a0d6b099) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9b8e16f852](https://linux-hardware.org/?probe=9b8e16f852) | Jul 08, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [b4d926a4bc](https://linux-hardware.org/?probe=b4d926a4bc) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [06b52888f8](https://linux-hardware.org/?probe=06b52888f8) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0048149cd5](https://linux-hardware.org/?probe=0048149cd5) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [ffde5244e6](https://linux-hardware.org/?probe=ffde5244e6) | Jul 08, 2023 |
| Dell          | Inspiron 5493               | [3b68a8661e](https://linux-hardware.org/?probe=3b68a8661e) | Jul 08, 2023 |
| Lenovo        | G50-70 20351                | [2349cf550c](https://linux-hardware.org/?probe=2349cf550c) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [2e2541c7a6](https://linux-hardware.org/?probe=2e2541c7a6) | Jul 08, 2023 |
| Lenovo        | G50-70 20351                | [a5267b5818](https://linux-hardware.org/?probe=a5267b5818) | Jul 08, 2023 |
| MSI           | GF65 Thin 10UE              | [8dd1516457](https://linux-hardware.org/?probe=8dd1516457) | Jul 08, 2023 |
| Dell          | Inspiron 3521               | [052c072bc4](https://linux-hardware.org/?probe=052c072bc4) | Jul 08, 2023 |
| Acer          | Aspire E1-570G              | [f1d3e3070e](https://linux-hardware.org/?probe=f1d3e3070e) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [e4bb31a52c](https://linux-hardware.org/?probe=e4bb31a52c) | Jul 07, 2023 |
| HP            | Laptop 15-dw3xxx            | [2ed128676f](https://linux-hardware.org/?probe=2ed128676f) | Jul 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [aa8cfd7d60](https://linux-hardware.org/?probe=aa8cfd7d60) | Jul 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0b4200c1e4](https://linux-hardware.org/?probe=0b4200c1e4) | Jul 07, 2023 |
| Schenker      | VIA 15 Pro                  | [bec6fac79a](https://linux-hardware.org/?probe=bec6fac79a) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [629f165835](https://linux-hardware.org/?probe=629f165835) | Jul 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [2ddfbf8bb9](https://linux-hardware.org/?probe=2ddfbf8bb9) | Jul 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS17228     | [cb869cfeab](https://linux-hardware.org/?probe=cb869cfeab) | Jul 07, 2023 |
| Dell          | Inspiron 3543               | [b7459d1653](https://linux-hardware.org/?probe=b7459d1653) | Jul 07, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [dcf48c7be4](https://linux-hardware.org/?probe=dcf48c7be4) | Jul 07, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [c060069870](https://linux-hardware.org/?probe=c060069870) | Jul 07, 2023 |
| Acer          | Aspire E1-570G              | [276cdeb14d](https://linux-hardware.org/?probe=276cdeb14d) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f687a3ac28](https://linux-hardware.org/?probe=f687a3ac28) | Jul 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [d09af80a65](https://linux-hardware.org/?probe=d09af80a65) | Jul 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [e134f78b10](https://linux-hardware.org/?probe=e134f78b10) | Jul 07, 2023 |
| Lenovo        | ThinkPad T530 2392ASU       | [60c3515504](https://linux-hardware.org/?probe=60c3515504) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [097260a10f](https://linux-hardware.org/?probe=097260a10f) | Jul 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0c13e384e9](https://linux-hardware.org/?probe=0c13e384e9) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [03f454349c](https://linux-hardware.org/?probe=03f454349c) | Jul 06, 2023 |
| HP            | Laptop 15-bs0xx             | [0a18dd76c6](https://linux-hardware.org/?probe=0a18dd76c6) | Jul 06, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [0311778091](https://linux-hardware.org/?probe=0311778091) | Jul 06, 2023 |
| Apple         | MacBookPro8,3               | [c93db722a7](https://linux-hardware.org/?probe=c93db722a7) | Jul 06, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [b50c5ad983](https://linux-hardware.org/?probe=b50c5ad983) | Jul 06, 2023 |
| Acer          | Aspire E1-571               | [d0258b4ca5](https://linux-hardware.org/?probe=d0258b4ca5) | Jul 06, 2023 |
| HP            | ENVY m6 Notebook            | [602c50a904](https://linux-hardware.org/?probe=602c50a904) | Jul 06, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [382fff8a04](https://linux-hardware.org/?probe=382fff8a04) | Jul 06, 2023 |
| Lenovo        | G50-70 20351                | [26145eba2e](https://linux-hardware.org/?probe=26145eba2e) | Jul 05, 2023 |
| HP            | Notebook                    | [19d38aa402](https://linux-hardware.org/?probe=19d38aa402) | Jul 05, 2023 |
| HP            | Notebook                    | [ac7ccc907b](https://linux-hardware.org/?probe=ac7ccc907b) | Jul 05, 2023 |
| HP            | EliteBook 840 G6            | [2fa3986e67](https://linux-hardware.org/?probe=2fa3986e67) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3e5dc0c313](https://linux-hardware.org/?probe=3e5dc0c313) | Jul 05, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [60dad73833](https://linux-hardware.org/?probe=60dad73833) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a3a67ab04c](https://linux-hardware.org/?probe=a3a67ab04c) | Jul 05, 2023 |
| Samsung       | R580                        | [5205794d78](https://linux-hardware.org/?probe=5205794d78) | Jul 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [5e18a2d43c](https://linux-hardware.org/?probe=5e18a2d43c) | Jul 05, 2023 |
| Dell          | Inspiron N5110              | [355ccda3d5](https://linux-hardware.org/?probe=355ccda3d5) | Jul 05, 2023 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [e141746297](https://linux-hardware.org/?probe=e141746297) | Jul 05, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [b8f9aa3c52](https://linux-hardware.org/?probe=b8f9aa3c52) | Jul 05, 2023 |
| MSI           | Modern 14 B4MW              | [210a7aea7f](https://linux-hardware.org/?probe=210a7aea7f) | Jul 05, 2023 |
| Dell          | Inspiron 5593               | [a40b38a093](https://linux-hardware.org/?probe=a40b38a093) | Jul 05, 2023 |
| HP            | 245 14 inch G9 Notebook ... | [53bd77d836](https://linux-hardware.org/?probe=53bd77d836) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | [1a32b23618](https://linux-hardware.org/?probe=1a32b23618) | Jul 04, 2023 |
| MSI           | Summit E13FlipEvo A13MT     | [ec1d2fbdad](https://linux-hardware.org/?probe=ec1d2fbdad) | Jul 04, 2023 |
| HP            | Pavilion dv5                | [8064b5c083](https://linux-hardware.org/?probe=8064b5c083) | Jul 04, 2023 |
| Lenovo        | Legion R9000K2021H 82N6     | [a968f4b15c](https://linux-hardware.org/?probe=a968f4b15c) | Jul 04, 2023 |
| HP            | EliteBook 820 G1            | [5b1b409a2f](https://linux-hardware.org/?probe=5b1b409a2f) | Jul 04, 2023 |
| Apple         | MacBook8,1                  | [06ac15dcca](https://linux-hardware.org/?probe=06ac15dcca) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c3098317a7](https://linux-hardware.org/?probe=c3098317a7) | Jul 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8553179448](https://linux-hardware.org/?probe=8553179448) | Jul 04, 2023 |
| Lenovo        | ThinkPad P50 20EQS48H00     | [7f64164b64](https://linux-hardware.org/?probe=7f64164b64) | Jul 04, 2023 |
| Timi          | Redmi G 2022                | [a6c12e95a6](https://linux-hardware.org/?probe=a6c12e95a6) | Jul 04, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [dfd88b9f78](https://linux-hardware.org/?probe=dfd88b9f78) | Jul 04, 2023 |
| Dell          | Inspiron 1545               | [f5aa631644](https://linux-hardware.org/?probe=f5aa631644) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [ca25e859c3](https://linux-hardware.org/?probe=ca25e859c3) | Jul 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [5d2bd9c3ce](https://linux-hardware.org/?probe=5d2bd9c3ce) | Jul 04, 2023 |
| Acer          | Aspire A315-23              | [1714400cb9](https://linux-hardware.org/?probe=1714400cb9) | Jul 04, 2023 |
| Notebook      | P377SM-A                    | [acc35485db](https://linux-hardware.org/?probe=acc35485db) | Jul 04, 2023 |
| Notebook      | P377SM-A                    | [f37ed7f8db](https://linux-hardware.org/?probe=f37ed7f8db) | Jul 04, 2023 |
| Dell          | Inspiron 1545               | [3fb951a266](https://linux-hardware.org/?probe=3fb951a266) | Jul 03, 2023 |
| Dell          | Precision 3581              | [1d4db3cec3](https://linux-hardware.org/?probe=1d4db3cec3) | Jul 03, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [67c131f536](https://linux-hardware.org/?probe=67c131f536) | Jul 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [1af3478d1a](https://linux-hardware.org/?probe=1af3478d1a) | Jul 03, 2023 |
| HUAWEI        | HVY-WXX9                    | [2585d66bd1](https://linux-hardware.org/?probe=2585d66bd1) | Jul 03, 2023 |
| Dell          | XPS 15 7590                 | [de620c05a9](https://linux-hardware.org/?probe=de620c05a9) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [6ca874df22](https://linux-hardware.org/?probe=6ca874df22) | Jul 03, 2023 |
| MSI           | Katana GF66 12UC            | [b241427d10](https://linux-hardware.org/?probe=b241427d10) | Jul 03, 2023 |
| MSI           | Raider GE77HX 12UHS         | [87cc790852](https://linux-hardware.org/?probe=87cc790852) | Jul 03, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [7aed7e46ad](https://linux-hardware.org/?probe=7aed7e46ad) | Jul 03, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [5f2c613312](https://linux-hardware.org/?probe=5f2c613312) | Jul 03, 2023 |
| Dell          | Inspiron 5577               | [f957ad317f](https://linux-hardware.org/?probe=f957ad317f) | Jul 03, 2023 |
| HP            | EliteBook 8440p             | [9c8f32ac20](https://linux-hardware.org/?probe=9c8f32ac20) | Jul 02, 2023 |
| HP            | EliteBook 8440p             | [6c32038385](https://linux-hardware.org/?probe=6c32038385) | Jul 02, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [4586b855ca](https://linux-hardware.org/?probe=4586b855ca) | Jul 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [835f3a390f](https://linux-hardware.org/?probe=835f3a390f) | Jul 02, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [638d99b4f8](https://linux-hardware.org/?probe=638d99b4f8) | Jul 02, 2023 |
| HP            | Compaq 6910p                | [d72eacd7ea](https://linux-hardware.org/?probe=d72eacd7ea) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [05394ee8a5](https://linux-hardware.org/?probe=05394ee8a5) | Jul 02, 2023 |
| Dell          | Latitude E6420              | [aae88e9000](https://linux-hardware.org/?probe=aae88e9000) | Jul 01, 2023 |
| Dell          | Latitude 7280               | [8ffe276705](https://linux-hardware.org/?probe=8ffe276705) | Jul 01, 2023 |
| Dell          | Inspiron N5110              | [354dd05c7f](https://linux-hardware.org/?probe=354dd05c7f) | Jul 01, 2023 |
| HUAWEI        | HKD-WXX                     | [18b69ee7ff](https://linux-hardware.org/?probe=18b69ee7ff) | Jul 01, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [46508a63f2](https://linux-hardware.org/?probe=46508a63f2) | Jul 01, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [0c4c59cf86](https://linux-hardware.org/?probe=0c4c59cf86) | Jul 01, 2023 |
| Acer          | Aspire A515-56G             | [4c212e25ee](https://linux-hardware.org/?probe=4c212e25ee) | Jul 01, 2023 |
| Lenovo        | B40-70 20392                | [02a31c9704](https://linux-hardware.org/?probe=02a31c9704) | Jul 01, 2023 |
| Lenovo        | B40-70 20392                | [45739a208c](https://linux-hardware.org/?probe=45739a208c) | Jul 01, 2023 |
| Google        | Eldrid                      | [407bde63f9](https://linux-hardware.org/?probe=407bde63f9) | Jul 01, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [8f38634e0e](https://linux-hardware.org/?probe=8f38634e0e) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK E780               | [12c5cd0309](https://linux-hardware.org/?probe=12c5cd0309) | Jul 01, 2023 |
| Dell          | Inspiron N5110              | [b465607eea](https://linux-hardware.org/?probe=b465607eea) | Jun 30, 2023 |
| Acer          | Aspire A315-23              | [434ba90999](https://linux-hardware.org/?probe=434ba90999) | Jun 30, 2023 |
| HP            | ENVY m6                     | [b4f8d19895](https://linux-hardware.org/?probe=b4f8d19895) | Jun 30, 2023 |
| Dell          | Inspiron N5010              | [eab5331f66](https://linux-hardware.org/?probe=eab5331f66) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [5dd37cbc97](https://linux-hardware.org/?probe=5dd37cbc97) | Jun 30, 2023 |
| Dell          | Inspiron N5110              | [0668932749](https://linux-hardware.org/?probe=0668932749) | Jun 30, 2023 |
| Google        | Eldrid                      | [4e08107dd6](https://linux-hardware.org/?probe=4e08107dd6) | Jun 30, 2023 |
| Dell          | Vostro 2520                 | [48d04d8282](https://linux-hardware.org/?probe=48d04d8282) | Jun 30, 2023 |
| Apple         | MacBookPro12,1              | [997b1fe1f8](https://linux-hardware.org/?probe=997b1fe1f8) | Jun 30, 2023 |
| HP            | Pavilion 11 x360 PC         | [cfbc8c8a97](https://linux-hardware.org/?probe=cfbc8c8a97) | Jun 29, 2023 |
| MSI           | PS63 Modern 8SC             | [dcbb8108cf](https://linux-hardware.org/?probe=dcbb8108cf) | Jun 29, 2023 |
| Dell          | Latitude 5521               | [3a8f3794aa](https://linux-hardware.org/?probe=3a8f3794aa) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [df0ca94515](https://linux-hardware.org/?probe=df0ca94515) | Jun 29, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | [0086cae258](https://linux-hardware.org/?probe=0086cae258) | Jun 29, 2023 |
| Google        | Nami                        | [6ffc403580](https://linux-hardware.org/?probe=6ffc403580) | Jun 29, 2023 |
| Acer          | Aspire 5745G                | [c3394b9eb0](https://linux-hardware.org/?probe=c3394b9eb0) | Jun 28, 2023 |
| Apple         | MacBookAir7,2               | [92a71d25d7](https://linux-hardware.org/?probe=92a71d25d7) | Jun 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [76e11b36e9](https://linux-hardware.org/?probe=76e11b36e9) | Jun 28, 2023 |
| Acer          | Aspire A315-23              | [36f9eb51e6](https://linux-hardware.org/?probe=36f9eb51e6) | Jun 28, 2023 |
| Dell          | Precision M6500             | [1db851fd5d](https://linux-hardware.org/?probe=1db851fd5d) | Jun 28, 2023 |
| Dell          | XPS 15 9510                 | [0294ef5e1f](https://linux-hardware.org/?probe=0294ef5e1f) | Jun 28, 2023 |
| Lenovo        | G500s 20245                 | [1aa332e26f](https://linux-hardware.org/?probe=1aa332e26f) | Jun 27, 2023 |
| HP            | EliteBook 8440p             | [3d2a2196ae](https://linux-hardware.org/?probe=3d2a2196ae) | Jun 27, 2023 |
| HP            | Pavilion g6                 | [ec6a70b7d4](https://linux-hardware.org/?probe=ec6a70b7d4) | Jun 27, 2023 |
| Dell          | Inspiron 3543               | [4baea798b1](https://linux-hardware.org/?probe=4baea798b1) | Jun 27, 2023 |
| Intel Clie... | LAPRC710                    | [5aabe7850a](https://linux-hardware.org/?probe=5aabe7850a) | Jun 27, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c05a780b64](https://linux-hardware.org/?probe=c05a780b64) | Jun 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [24d66c058b](https://linux-hardware.org/?probe=24d66c058b) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [39ec9cf6c4](https://linux-hardware.org/?probe=39ec9cf6c4) | Jun 27, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [78b698279a](https://linux-hardware.org/?probe=78b698279a) | Jun 27, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | [41e22753cc](https://linux-hardware.org/?probe=41e22753cc) | Jun 27, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [7487f61ff1](https://linux-hardware.org/?probe=7487f61ff1) | Jun 26, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [e16689358e](https://linux-hardware.org/?probe=e16689358e) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [253fb546a2](https://linux-hardware.org/?probe=253fb546a2) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | [e5b49b2807](https://linux-hardware.org/?probe=e5b49b2807) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | [49c7e22c1e](https://linux-hardware.org/?probe=49c7e22c1e) | Jun 26, 2023 |
| Toshiba       | TECRA R950                  | [f02bb9a43a](https://linux-hardware.org/?probe=f02bb9a43a) | Jun 26, 2023 |
| ASUSTek       | X510UAR                     | [22372b435f](https://linux-hardware.org/?probe=22372b435f) | Jun 26, 2023 |
| Acer          | Aspire A515-51              | [ee5172b420](https://linux-hardware.org/?probe=ee5172b420) | Jun 26, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [03153f31b2](https://linux-hardware.org/?probe=03153f31b2) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | [68117675ab](https://linux-hardware.org/?probe=68117675ab) | Jun 25, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | [e6184368a0](https://linux-hardware.org/?probe=e6184368a0) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [bfa03ecd27](https://linux-hardware.org/?probe=bfa03ecd27) | Jun 25, 2023 |
| Lenovo        | ThinkPad X230 2324H58       | [bcf8a71bb4](https://linux-hardware.org/?probe=bcf8a71bb4) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [58d1b3da16](https://linux-hardware.org/?probe=58d1b3da16) | Jun 25, 2023 |
| HP            | 255 G5 Notebook PC          | [cad891675f](https://linux-hardware.org/?probe=cad891675f) | Jun 25, 2023 |
| ASUSTek       | X540NA                      | [6a01ca36af](https://linux-hardware.org/?probe=6a01ca36af) | Jun 25, 2023 |
| ASUSTek       | X540NA                      | [b5996a0d85](https://linux-hardware.org/?probe=b5996a0d85) | Jun 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [29203c5ffe](https://linux-hardware.org/?probe=29203c5ffe) | Jun 25, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [3fbef5ec38](https://linux-hardware.org/?probe=3fbef5ec38) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [8a833d8c52](https://linux-hardware.org/?probe=8a833d8c52) | Jun 25, 2023 |
| Acer          | Nitro AN515-55              | [2153f80362](https://linux-hardware.org/?probe=2153f80362) | Jun 25, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [40cbc38a69](https://linux-hardware.org/?probe=40cbc38a69) | Jun 25, 2023 |
| Google        | Nami                        | [f9f785f70d](https://linux-hardware.org/?probe=f9f785f70d) | Jun 25, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [75f62d2200](https://linux-hardware.org/?probe=75f62d2200) | Jun 24, 2023 |
| Dell          | Precision 5510              | [38d61a4475](https://linux-hardware.org/?probe=38d61a4475) | Jun 24, 2023 |
| HP            | Pavilion Notebook           | [e80fd49ba9](https://linux-hardware.org/?probe=e80fd49ba9) | Jun 24, 2023 |
| Dell          | Vostro 2520                 | [9279842ec3](https://linux-hardware.org/?probe=9279842ec3) | Jun 24, 2023 |
| MSI           | Modern 14 A10M              | [fcc6786de6](https://linux-hardware.org/?probe=fcc6786de6) | Jun 24, 2023 |
| HP            | EliteBook 840 G5            | [4ad837baa7](https://linux-hardware.org/?probe=4ad837baa7) | Jun 24, 2023 |
| Dell          | Inspiron 15 3515            | [77473ea84c](https://linux-hardware.org/?probe=77473ea84c) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [99efa1a1c5](https://linux-hardware.org/?probe=99efa1a1c5) | Jun 24, 2023 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | [a74b5c2880](https://linux-hardware.org/?probe=a74b5c2880) | Jun 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b4c9b0d1f7](https://linux-hardware.org/?probe=b4c9b0d1f7) | Jun 24, 2023 |
| Xplore        | iX104C6                     | [23bb4c656b](https://linux-hardware.org/?probe=23bb4c656b) | Jun 24, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [f51aeb6252](https://linux-hardware.org/?probe=f51aeb6252) | Jun 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [e44e80fc33](https://linux-hardware.org/?probe=e44e80fc33) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7b187eac86](https://linux-hardware.org/?probe=7b187eac86) | Jun 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [ae40c874ae](https://linux-hardware.org/?probe=ae40c874ae) | Jun 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [505b340648](https://linux-hardware.org/?probe=505b340648) | Jun 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0NF0... | [f2e368a70d](https://linux-hardware.org/?probe=f2e368a70d) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [06977283b8](https://linux-hardware.org/?probe=06977283b8) | Jun 22, 2023 |
| HP            | Compaq 6710b (GF940AT#AB... | [75199aaf80](https://linux-hardware.org/?probe=75199aaf80) | Jun 22, 2023 |
| HONOR         | NBR-WAX9                    | [dfeaf221e6](https://linux-hardware.org/?probe=dfeaf221e6) | Jun 22, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [e03310c8e8](https://linux-hardware.org/?probe=e03310c8e8) | Jun 22, 2023 |
| Lenovo        | G500s 20245                 | [17db397c48](https://linux-hardware.org/?probe=17db397c48) | Jun 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [aa0f45d3f1](https://linux-hardware.org/?probe=aa0f45d3f1) | Jun 22, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [7782ddf809](https://linux-hardware.org/?probe=7782ddf809) | Jun 22, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [e8e25f684e](https://linux-hardware.org/?probe=e8e25f684e) | Jun 22, 2023 |
| Framework     | Laptop                      | [eb51a9a662](https://linux-hardware.org/?probe=eb51a9a662) | Jun 22, 2023 |
| Apple         | MacBookAir5,2               | [8f6d75c75e](https://linux-hardware.org/?probe=8f6d75c75e) | Jun 22, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [8158959dbd](https://linux-hardware.org/?probe=8158959dbd) | Jun 22, 2023 |
| HP            | EliteBook 865 16 inch G9... | [e4407d328d](https://linux-hardware.org/?probe=e4407d328d) | Jun 22, 2023 |
| Lenovo        | ThinkPad L480 20LS002YMX    | [9c9702483c](https://linux-hardware.org/?probe=9c9702483c) | Jun 22, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | [a2e5b66940](https://linux-hardware.org/?probe=a2e5b66940) | Jun 22, 2023 |
| HP            | EliteBook 850 G6            | [a68e387274](https://linux-hardware.org/?probe=a68e387274) | Jun 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [510604914c](https://linux-hardware.org/?probe=510604914c) | Jun 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [ab169bfbfd](https://linux-hardware.org/?probe=ab169bfbfd) | Jun 21, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [61ba243843](https://linux-hardware.org/?probe=61ba243843) | Jun 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS02V0... | [bed60c3010](https://linux-hardware.org/?probe=bed60c3010) | Jun 21, 2023 |
| HUAWEI        | NBD-WXX9                    | [4e7d62b30a](https://linux-hardware.org/?probe=4e7d62b30a) | Jun 21, 2023 |
| HP            | ProBook 450 G2              | [60babdeb16](https://linux-hardware.org/?probe=60babdeb16) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e26b3e6d58](https://linux-hardware.org/?probe=e26b3e6d58) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [0b6bb0a043](https://linux-hardware.org/?probe=0b6bb0a043) | Jun 21, 2023 |
| Notebook      | NV4xPZ                      | [873c70b184](https://linux-hardware.org/?probe=873c70b184) | Jun 21, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [73306c60af](https://linux-hardware.org/?probe=73306c60af) | Jun 21, 2023 |
| Dell          | Latitude E6410              | [0d9054df1e](https://linux-hardware.org/?probe=0d9054df1e) | Jun 21, 2023 |
| HP            | EliteBook 840 G6            | [8d35565fd3](https://linux-hardware.org/?probe=8d35565fd3) | Jun 20, 2023 |
| Dell          | XPS 13 9350                 | [3aa5f3f213](https://linux-hardware.org/?probe=3aa5f3f213) | Jun 20, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8550e224ec](https://linux-hardware.org/?probe=8550e224ec) | Jun 20, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [3be3d70197](https://linux-hardware.org/?probe=3be3d70197) | Jun 20, 2023 |
| Dell          | Latitude 5289               | [cb492423ed](https://linux-hardware.org/?probe=cb492423ed) | Jun 20, 2023 |
| MSI           | Modern 14 B4MW              | [11edb8696f](https://linux-hardware.org/?probe=11edb8696f) | Jun 20, 2023 |
| MSI           | Modern 14 B4MW              | [2df6a58651](https://linux-hardware.org/?probe=2df6a58651) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1595a5adbd](https://linux-hardware.org/?probe=1595a5adbd) | Jun 20, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [530f6272c9](https://linux-hardware.org/?probe=530f6272c9) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [3e3987b43f](https://linux-hardware.org/?probe=3e3987b43f) | Jun 20, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [82927c0cb7](https://linux-hardware.org/?probe=82927c0cb7) | Jun 20, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | [063ce55dd5](https://linux-hardware.org/?probe=063ce55dd5) | Jun 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [e5db90d1b4](https://linux-hardware.org/?probe=e5db90d1b4) | Jun 20, 2023 |
| HP            | EliteBook 840 G6            | [058b2ea405](https://linux-hardware.org/?probe=058b2ea405) | Jun 20, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [f38684c33d](https://linux-hardware.org/?probe=f38684c33d) | Jun 19, 2023 |
| Dell          | Latitude E7470              | [645538d81e](https://linux-hardware.org/?probe=645538d81e) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | [27bfb2de7d](https://linux-hardware.org/?probe=27bfb2de7d) | Jun 19, 2023 |
| Toshiba       | Satellite A300              | [f37d67a18d](https://linux-hardware.org/?probe=f37d67a18d) | Jun 19, 2023 |
| Acer          | Aspire A515-46              | [e40e63fa5f](https://linux-hardware.org/?probe=e40e63fa5f) | Jun 19, 2023 |
| Lenovo        | Legion R7000P2021 82JW      | [df59b5e8b7](https://linux-hardware.org/?probe=df59b5e8b7) | Jun 19, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [65385cc189](https://linux-hardware.org/?probe=65385cc189) | Jun 19, 2023 |
| Lenovo        | Legion 5 82B5               | [146ef72817](https://linux-hardware.org/?probe=146ef72817) | Jun 19, 2023 |
| HP            | ENVY 15                     | [101fb8810b](https://linux-hardware.org/?probe=101fb8810b) | Jun 19, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [125b4fefa5](https://linux-hardware.org/?probe=125b4fefa5) | Jun 19, 2023 |
| Razer         | Blade 15 Advanced Model ... | [7dd15a9fa4](https://linux-hardware.org/?probe=7dd15a9fa4) | Jun 19, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [8a88cbb916](https://linux-hardware.org/?probe=8a88cbb916) | Jun 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [0806a6be0a](https://linux-hardware.org/?probe=0806a6be0a) | Jun 19, 2023 |
| HP            | Pavilion Notebook           | [ce3c5bc056](https://linux-hardware.org/?probe=ce3c5bc056) | Jun 18, 2023 |
| Dell          | Inspiron 5559               | [7dc6f3af4b](https://linux-hardware.org/?probe=7dc6f3af4b) | Jun 18, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [ecf90f8368](https://linux-hardware.org/?probe=ecf90f8368) | Jun 18, 2023 |
| Dell          | Precision 7540              | [8b9ddcc1d8](https://linux-hardware.org/?probe=8b9ddcc1d8) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [50626f77d7](https://linux-hardware.org/?probe=50626f77d7) | Jun 18, 2023 |
| MSI           | PS63 Modern 8RC             | [f540e88555](https://linux-hardware.org/?probe=f540e88555) | Jun 18, 2023 |
| Google        | Kefka                       | [86421e3d29](https://linux-hardware.org/?probe=86421e3d29) | Jun 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d5c387d28e](https://linux-hardware.org/?probe=d5c387d28e) | Jun 18, 2023 |
| Acer          | Aspire E5-574               | [ca656065e5](https://linux-hardware.org/?probe=ca656065e5) | Jun 17, 2023 |
| Dell          | XPS 13 9370                 | [f008a78339](https://linux-hardware.org/?probe=f008a78339) | Jun 17, 2023 |
| Dell          | Inspiron 5567               | [92ace6e5ab](https://linux-hardware.org/?probe=92ace6e5ab) | Jun 17, 2023 |
| HP            | Laptop 15-da0xxx            | [7da8691a87](https://linux-hardware.org/?probe=7da8691a87) | Jun 17, 2023 |
| Sony          | SVF15213CBW                 | [4fcc62d3ac](https://linux-hardware.org/?probe=4fcc62d3ac) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop      | [2d5c5b2c80](https://linux-hardware.org/?probe=2d5c5b2c80) | Jun 17, 2023 |
| Framework     | Laptop                      | [3df2b82bc3](https://linux-hardware.org/?probe=3df2b82bc3) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d7e9625e19](https://linux-hardware.org/?probe=d7e9625e19) | Jun 17, 2023 |
| Dell          | Inspiron 3593               | [46ad2c78f7](https://linux-hardware.org/?probe=46ad2c78f7) | Jun 17, 2023 |
| Google        | Cave                        | [31c31973e1](https://linux-hardware.org/?probe=31c31973e1) | Jun 17, 2023 |
| Apple         | MacBook6,1                  | [913d8d26b9](https://linux-hardware.org/?probe=913d8d26b9) | Jun 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [edd82d072b](https://linux-hardware.org/?probe=edd82d072b) | Jun 16, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [268b733c44](https://linux-hardware.org/?probe=268b733c44) | Jun 16, 2023 |
| HP            | EliteBook 820 G1            | [4c6361a099](https://linux-hardware.org/?probe=4c6361a099) | Jun 16, 2023 |
| HP            | Laptop 15-bw0xx             | [1b97aa6745](https://linux-hardware.org/?probe=1b97aa6745) | Jun 16, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [04329cdc14](https://linux-hardware.org/?probe=04329cdc14) | Jun 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [dc892cf2b0](https://linux-hardware.org/?probe=dc892cf2b0) | Jun 16, 2023 |
| Dell          | Latitude 3420               | [a0074970bf](https://linux-hardware.org/?probe=a0074970bf) | Jun 16, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [eb9232a196](https://linux-hardware.org/?probe=eb9232a196) | Jun 16, 2023 |
| MSI           | Prestige 15 A10SC           | [a2426b801a](https://linux-hardware.org/?probe=a2426b801a) | Jun 16, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [a6a2463b97](https://linux-hardware.org/?probe=a6a2463b97) | Jun 16, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [89ac5ef04b](https://linux-hardware.org/?probe=89ac5ef04b) | Jun 15, 2023 |
| Acer          | Swift SF114-34              | [32eb9f5dea](https://linux-hardware.org/?probe=32eb9f5dea) | Jun 15, 2023 |
| Acer          | Swift SF114-34              | [9f9ffda2e3](https://linux-hardware.org/?probe=9f9ffda2e3) | Jun 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [2346d706e3](https://linux-hardware.org/?probe=2346d706e3) | Jun 15, 2023 |
| MSI           | Modern 14 B10MW             | [c488929cdc](https://linux-hardware.org/?probe=c488929cdc) | Jun 15, 2023 |
| Dell          | XPS 13 9310                 | [9cba8f7730](https://linux-hardware.org/?probe=9cba8f7730) | Jun 15, 2023 |
| HP            | Laptop 15s-fq0xxx           | [ff98efdef7](https://linux-hardware.org/?probe=ff98efdef7) | Jun 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | [dd5aaca858](https://linux-hardware.org/?probe=dd5aaca858) | Jun 15, 2023 |
| Lenovo        | G500s 20245                 | [8a04ec65f7](https://linux-hardware.org/?probe=8a04ec65f7) | Jun 15, 2023 |
| Dell          | Latitude E7470              | [c4bd47b182](https://linux-hardware.org/?probe=c4bd47b182) | Jun 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [e3e61eef7a](https://linux-hardware.org/?probe=e3e61eef7a) | Jun 15, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [b9d120642c](https://linux-hardware.org/?probe=b9d120642c) | Jun 14, 2023 |
| Dell          | Latitude 7430               | [6cf1c68c1d](https://linux-hardware.org/?probe=6cf1c68c1d) | Jun 14, 2023 |
| Dell          | Inspiron M5010              | [33541731e3](https://linux-hardware.org/?probe=33541731e3) | Jun 14, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [6f4c06d514](https://linux-hardware.org/?probe=6f4c06d514) | Jun 14, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [57b3c23d43](https://linux-hardware.org/?probe=57b3c23d43) | Jun 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e676294e36](https://linux-hardware.org/?probe=e676294e36) | Jun 13, 2023 |
| Acer          | Aspire 5733                 | [6291133649](https://linux-hardware.org/?probe=6291133649) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [58b9a1f862](https://linux-hardware.org/?probe=58b9a1f862) | Jun 13, 2023 |
| HP            | Notebook                    | [64232e0a08](https://linux-hardware.org/?probe=64232e0a08) | Jun 13, 2023 |
| Google        | Blooglet                    | [3dedc16acb](https://linux-hardware.org/?probe=3dedc16acb) | Jun 13, 2023 |
| Dell          | XPS 17 9710                 | [9ab7a065c4](https://linux-hardware.org/?probe=9ab7a065c4) | Jun 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [dc3b9443ef](https://linux-hardware.org/?probe=dc3b9443ef) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [ee5c72c283](https://linux-hardware.org/?probe=ee5c72c283) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [db48a7b38d](https://linux-hardware.org/?probe=db48a7b38d) | Jun 13, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [5eb605a720](https://linux-hardware.org/?probe=5eb605a720) | Jun 13, 2023 |
| Dell          | Latitude 7430               | [6a01453dfa](https://linux-hardware.org/?probe=6a01453dfa) | Jun 12, 2023 |
| Acer          | Aspire ES1-572              | [e6713db4c3](https://linux-hardware.org/?probe=e6713db4c3) | Jun 12, 2023 |
| Lenovo        | ThinkPad W541 20EGS15J0N    | [ba935e9d5c](https://linux-hardware.org/?probe=ba935e9d5c) | Jun 12, 2023 |
| Lenovo        | V14-ARE 82DQ                | [318f1f4d2a](https://linux-hardware.org/?probe=318f1f4d2a) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [edf817eef9](https://linux-hardware.org/?probe=edf817eef9) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [5c98700539](https://linux-hardware.org/?probe=5c98700539) | Jun 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [d183d47822](https://linux-hardware.org/?probe=d183d47822) | Jun 12, 2023 |
| HP            | Pavilion dm4                | [6eb4c3d87a](https://linux-hardware.org/?probe=6eb4c3d87a) | Jun 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [eb6dc5143e](https://linux-hardware.org/?probe=eb6dc5143e) | Jun 12, 2023 |
| Timi          | RedmiBook Pro 14            | [7b2e093b24](https://linux-hardware.org/?probe=7b2e093b24) | Jun 12, 2023 |
| Google        | Blorb                       | [0083999b8a](https://linux-hardware.org/?probe=0083999b8a) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [b9c83e1b8a](https://linux-hardware.org/?probe=b9c83e1b8a) | Jun 12, 2023 |
| Google        | Blorb                       | [516c0548dc](https://linux-hardware.org/?probe=516c0548dc) | Jun 12, 2023 |
| Acer          | Aspire E5-575G              | [90bcfaba60](https://linux-hardware.org/?probe=90bcfaba60) | Jun 12, 2023 |
| Apple         | MacBookPro8,1               | [ec6af41f13](https://linux-hardware.org/?probe=ec6af41f13) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0d07b35562](https://linux-hardware.org/?probe=0d07b35562) | Jun 11, 2023 |
| Dell          | G3 3579                     | [c04bf46d3e](https://linux-hardware.org/?probe=c04bf46d3e) | Jun 11, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [777f28f9e8](https://linux-hardware.org/?probe=777f28f9e8) | Jun 11, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [66aa96212a](https://linux-hardware.org/?probe=66aa96212a) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | [f3a04ea109](https://linux-hardware.org/?probe=f3a04ea109) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | [d9ad875572](https://linux-hardware.org/?probe=d9ad875572) | Jun 11, 2023 |
| Apple         | MacBookPro12,1              | [7e6a1fa5ff](https://linux-hardware.org/?probe=7e6a1fa5ff) | Jun 11, 2023 |
| MSI           | Modern 14 A10M              | [7d5fc6a209](https://linux-hardware.org/?probe=7d5fc6a209) | Jun 11, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [e9e79a1c3b](https://linux-hardware.org/?probe=e9e79a1c3b) | Jun 11, 2023 |
| Lenovo        | ThinkPad P1 20MD001VUS      | [c74425abce](https://linux-hardware.org/?probe=c74425abce) | Jun 11, 2023 |
| Acer          | Aspire A515-47              | [2838a84809](https://linux-hardware.org/?probe=2838a84809) | Jun 11, 2023 |
| Dell          | Latitude 3420               | [07061e9d7d](https://linux-hardware.org/?probe=07061e9d7d) | Jun 10, 2023 |
| ASUSTek       | X541UVK                     | [22a8a9d964](https://linux-hardware.org/?probe=22a8a9d964) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | [18e80281cc](https://linux-hardware.org/?probe=18e80281cc) | Jun 10, 2023 |
| Samsung       | 730QCJ/730QCR               | [96b21d42f1](https://linux-hardware.org/?probe=96b21d42f1) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | [f7bd03dbb9](https://linux-hardware.org/?probe=f7bd03dbb9) | Jun 10, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | [ac48eeb92c](https://linux-hardware.org/?probe=ac48eeb92c) | Jun 10, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | [ade15528d8](https://linux-hardware.org/?probe=ade15528d8) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [1eeb12a5ca](https://linux-hardware.org/?probe=1eeb12a5ca) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [e46f2fe66e](https://linux-hardware.org/?probe=e46f2fe66e) | Jun 10, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [1de48a4515](https://linux-hardware.org/?probe=1de48a4515) | Jun 10, 2023 |
| HP            | ZBook 15 G2                 | [68c941fe5d](https://linux-hardware.org/?probe=68c941fe5d) | Jun 10, 2023 |
| Toshiba       | PORTEGE Z10t-A              | [4a0712b322](https://linux-hardware.org/?probe=4a0712b322) | Jun 10, 2023 |
| Apple         | MacBookPro13,2              | [929c318674](https://linux-hardware.org/?probe=929c318674) | Jun 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1a36e2fa98](https://linux-hardware.org/?probe=1a36e2fa98) | Jun 10, 2023 |
| Dell          | Inspiron 5515               | [36016c0c6b](https://linux-hardware.org/?probe=36016c0c6b) | Jun 10, 2023 |
| HUAWEI        | BOD-WXX9                    | [c4063bcf07](https://linux-hardware.org/?probe=c4063bcf07) | Jun 09, 2023 |
| HUAWEI        | BOD-WXX9                    | [9016ad81ae](https://linux-hardware.org/?probe=9016ad81ae) | Jun 09, 2023 |
| HP            | Laptop 15-db0xxx            | [881d5dc409](https://linux-hardware.org/?probe=881d5dc409) | Jun 09, 2023 |
| HP            | ZBook 15 G2                 | [2851b41659](https://linux-hardware.org/?probe=2851b41659) | Jun 09, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [1794287cf0](https://linux-hardware.org/?probe=1794287cf0) | Jun 09, 2023 |
| Lenovo        | ThinkPad P1 20MD001VUS      | [9765261d02](https://linux-hardware.org/?probe=9765261d02) | Jun 09, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [8cc29c049e](https://linux-hardware.org/?probe=8cc29c049e) | Jun 09, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [9e3dfb25be](https://linux-hardware.org/?probe=9e3dfb25be) | Jun 09, 2023 |
| Dell          | XPS 13 9370                 | [c605e51eca](https://linux-hardware.org/?probe=c605e51eca) | Jun 09, 2023 |
| HP            | Laptop 15-db0xxx            | [5dd8c1fed8](https://linux-hardware.org/?probe=5dd8c1fed8) | Jun 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [e246e70bb6](https://linux-hardware.org/?probe=e246e70bb6) | Jun 09, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [27c0e57cb3](https://linux-hardware.org/?probe=27c0e57cb3) | Jun 09, 2023 |
| Dell          | Inspiron 3493               | [ffcd21fc3b](https://linux-hardware.org/?probe=ffcd21fc3b) | Jun 09, 2023 |
| Dell          | Precision 7540              | [41fe2f93ff](https://linux-hardware.org/?probe=41fe2f93ff) | Jun 09, 2023 |
| Apple         | MacBookPro9,2               | [c22081b097](https://linux-hardware.org/?probe=c22081b097) | Jun 09, 2023 |
| Apple         | MacBookPro8,1               | [70fea7478a](https://linux-hardware.org/?probe=70fea7478a) | Jun 08, 2023 |
| Dell          | Latitude 5175               | [63d6fcf641](https://linux-hardware.org/?probe=63d6fcf641) | Jun 08, 2023 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [4c8d8758b7](https://linux-hardware.org/?probe=4c8d8758b7) | Jun 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e28668e147](https://linux-hardware.org/?probe=e28668e147) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [59ff5486a9](https://linux-hardware.org/?probe=59ff5486a9) | Jun 08, 2023 |
| HP            | 240 G6 Notebook PC          | [eda13b898c](https://linux-hardware.org/?probe=eda13b898c) | Jun 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [13b0e73872](https://linux-hardware.org/?probe=13b0e73872) | Jun 08, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [e6cb646bd4](https://linux-hardware.org/?probe=e6cb646bd4) | Jun 08, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [6de4ea13fe](https://linux-hardware.org/?probe=6de4ea13fe) | Jun 08, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [8f160a999a](https://linux-hardware.org/?probe=8f160a999a) | Jun 08, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [0aea375d78](https://linux-hardware.org/?probe=0aea375d78) | Jun 08, 2023 |
| Dell          | Precision 3551              | [0e484bd6a5](https://linux-hardware.org/?probe=0e484bd6a5) | Jun 08, 2023 |
| HP            | Pavilion g6                 | [12b1174ce8](https://linux-hardware.org/?probe=12b1174ce8) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7543a0bbc1](https://linux-hardware.org/?probe=7543a0bbc1) | Jun 08, 2023 |
| Dell          | Precision 5510              | [24317d94ff](https://linux-hardware.org/?probe=24317d94ff) | Jun 08, 2023 |
| Lenovo        | ThinkPad T580 20L90047US    | [bee34052a3](https://linux-hardware.org/?probe=bee34052a3) | Jun 08, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [9c9fb1b1a6](https://linux-hardware.org/?probe=9c9fb1b1a6) | Jun 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [82d0019a0b](https://linux-hardware.org/?probe=82d0019a0b) | Jun 08, 2023 |
| Dell          | Inspiron 5505               | [05973f7d9b](https://linux-hardware.org/?probe=05973f7d9b) | Jun 08, 2023 |
| Unknown       | Unknown                     | [829839a3b3](https://linux-hardware.org/?probe=829839a3b3) | Jun 07, 2023 |
| Dell          | Inspiron 15 5510            | [98d7cb7ea7](https://linux-hardware.org/?probe=98d7cb7ea7) | Jun 07, 2023 |
| Dell          | Inspiron 5565               | [91fc26029a](https://linux-hardware.org/?probe=91fc26029a) | Jun 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [06608c68d7](https://linux-hardware.org/?probe=06608c68d7) | Jun 07, 2023 |
| Fujitsu       | CELSIUS H730                | [a1e397f4a7](https://linux-hardware.org/?probe=a1e397f4a7) | Jun 07, 2023 |
| HP            | Pavilion dv7                | [75a37cd4c8](https://linux-hardware.org/?probe=75a37cd4c8) | Jun 07, 2023 |
| Dell          | Inspiron 5548               | [e67581e121](https://linux-hardware.org/?probe=e67581e121) | Jun 07, 2023 |
| Apple         | MacBookPro9,2               | [2a0add5b7e](https://linux-hardware.org/?probe=2a0add5b7e) | Jun 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [e103817b2d](https://linux-hardware.org/?probe=e103817b2d) | Jun 07, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC0F    | [581602e921](https://linux-hardware.org/?probe=581602e921) | Jun 07, 2023 |
| Dell          | Latitude 5300               | [1eea10cfa3](https://linux-hardware.org/?probe=1eea10cfa3) | Jun 07, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [7d33fb0564](https://linux-hardware.org/?probe=7d33fb0564) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [b6bb7bad1d](https://linux-hardware.org/?probe=b6bb7bad1d) | Jun 07, 2023 |
| Apple         | MacBookPro9,2               | [8d70c1dd42](https://linux-hardware.org/?probe=8d70c1dd42) | Jun 07, 2023 |
| Acer          | Predator PH315-52           | [f7178495c7](https://linux-hardware.org/?probe=f7178495c7) | Jun 07, 2023 |
| Acer          | Aspire E5-411G              | [9a69b50d97](https://linux-hardware.org/?probe=9a69b50d97) | Jun 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [f9b3588ff3](https://linux-hardware.org/?probe=f9b3588ff3) | Jun 07, 2023 |
| Lenovo        | ThinkPad T495 20NKS10K00    | [f205c52b8f](https://linux-hardware.org/?probe=f205c52b8f) | Jun 07, 2023 |
| MSI           | GT72 2QE                    | [211494a051](https://linux-hardware.org/?probe=211494a051) | Jun 07, 2023 |
| Lenovo        | ThinkPad P1 20MD001VUS      | [8c505b5d84](https://linux-hardware.org/?probe=8c505b5d84) | Jun 06, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9afe34cdd8](https://linux-hardware.org/?probe=9afe34cdd8) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b7ab29fbb5](https://linux-hardware.org/?probe=b7ab29fbb5) | Jun 06, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [721ff5908a](https://linux-hardware.org/?probe=721ff5908a) | Jun 06, 2023 |
| Toshiba       | Satellite L40               | [16c5f74991](https://linux-hardware.org/?probe=16c5f74991) | Jun 06, 2023 |
| Apple         | MacBookPro14,1              | [16aa33fdfe](https://linux-hardware.org/?probe=16aa33fdfe) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 4282AB9       | [790550e99f](https://linux-hardware.org/?probe=790550e99f) | Jun 06, 2023 |
| Lenovo        | ThinkPad T460 20FMS2292K    | [380ffe6574](https://linux-hardware.org/?probe=380ffe6574) | Jun 06, 2023 |
| Dell          | XPS 15 9560                 | [0d326774c9](https://linux-hardware.org/?probe=0d326774c9) | Jun 06, 2023 |
| Lenovo        | ThinkPad P51 20HH0011US     | [4766608bc1](https://linux-hardware.org/?probe=4766608bc1) | Jun 06, 2023 |
| Apple         | MacBookPro9,2               | [7394a9d94b](https://linux-hardware.org/?probe=7394a9d94b) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [2a612dc748](https://linux-hardware.org/?probe=2a612dc748) | Jun 06, 2023 |
| Apple         | MacBookPro9,2               | [9df43aede5](https://linux-hardware.org/?probe=9df43aede5) | Jun 06, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | [77b332cb2d](https://linux-hardware.org/?probe=77b332cb2d) | Jun 06, 2023 |
| System76      | Oryx Pro                    | [4f39b2d690](https://linux-hardware.org/?probe=4f39b2d690) | Jun 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0deafae1f1](https://linux-hardware.org/?probe=0deafae1f1) | Jun 05, 2023 |
| realme        | CloudProXXXX                | [22cced9066](https://linux-hardware.org/?probe=22cced9066) | Jun 05, 2023 |
| Acer          | Nitro AN515-44              | [d7a2c59432](https://linux-hardware.org/?probe=d7a2c59432) | Jun 05, 2023 |
| Dell          | Latitude E7450              | [e19dbd1a84](https://linux-hardware.org/?probe=e19dbd1a84) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | [78459738e9](https://linux-hardware.org/?probe=78459738e9) | Jun 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [9a1c9022af](https://linux-hardware.org/?probe=9a1c9022af) | Jun 05, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [bb29d15c61](https://linux-hardware.org/?probe=bb29d15c61) | Jun 05, 2023 |
| Acer          | Predator PT515-51           | [5c3daec3c7](https://linux-hardware.org/?probe=5c3daec3c7) | Jun 05, 2023 |
| GPU Compan... | GWTC116-2                   | [de8a3d6dab](https://linux-hardware.org/?probe=de8a3d6dab) | Jun 05, 2023 |
| Samsung       | 950XEE                      | [cc47fd0df0](https://linux-hardware.org/?probe=cc47fd0df0) | Jun 05, 2023 |
| Lenovo        | ThinkPad E450 20DC003WUS    | [6abecb1cd3](https://linux-hardware.org/?probe=6abecb1cd3) | Jun 05, 2023 |
| ASUSTek       | X540UP                      | [b6613930a2](https://linux-hardware.org/?probe=b6613930a2) | Jun 05, 2023 |
| Dell          | Precision 7540              | [a10ecca056](https://linux-hardware.org/?probe=a10ecca056) | Jun 04, 2023 |
| Sony          | VPCSC1AFM                   | [2cf80cf628](https://linux-hardware.org/?probe=2cf80cf628) | Jun 04, 2023 |
| Apple         | MacBookPro8,1               | [e3f89d1faa](https://linux-hardware.org/?probe=e3f89d1faa) | Jun 04, 2023 |
| ASUSTek       | X540UP                      | [5102ecc266](https://linux-hardware.org/?probe=5102ecc266) | Jun 04, 2023 |
| MECHREVO      | Code01 Ver2.0               | [d311022361](https://linux-hardware.org/?probe=d311022361) | Jun 04, 2023 |
| MSI           | Modern 14 C12M              | [a5d1a0e656](https://linux-hardware.org/?probe=a5d1a0e656) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [dfb8881ffe](https://linux-hardware.org/?probe=dfb8881ffe) | Jun 04, 2023 |
| HP            | Laptop 17-cp0xxx            | [253c561829](https://linux-hardware.org/?probe=253c561829) | Jun 04, 2023 |
| AMI           | Intel                       | [cd2beb79d2](https://linux-hardware.org/?probe=cd2beb79d2) | Jun 04, 2023 |
| UNOWHY        | Y13G002S4EI                 | [f1b932f397](https://linux-hardware.org/?probe=f1b932f397) | Jun 04, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [43cffb0d0f](https://linux-hardware.org/?probe=43cffb0d0f) | Jun 04, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [cef2bf28c9](https://linux-hardware.org/?probe=cef2bf28c9) | Jun 04, 2023 |
| Dell          | Latitude D620               | [0e1b7f4320](https://linux-hardware.org/?probe=0e1b7f4320) | Jun 03, 2023 |
| HP            | ZBook 15 G2                 | [19ed8e22e6](https://linux-hardware.org/?probe=19ed8e22e6) | Jun 03, 2023 |
| Apple         | MacBookPro8,1               | [7bdff81d7d](https://linux-hardware.org/?probe=7bdff81d7d) | Jun 03, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [f241c0cf38](https://linux-hardware.org/?probe=f241c0cf38) | Jun 03, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [aea1babfb7](https://linux-hardware.org/?probe=aea1babfb7) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [4d1ad8d52a](https://linux-hardware.org/?probe=4d1ad8d52a) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [41e5c1790c](https://linux-hardware.org/?probe=41e5c1790c) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [d583c74274](https://linux-hardware.org/?probe=d583c74274) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [7ed9ba7165](https://linux-hardware.org/?probe=7ed9ba7165) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1aa286ccff](https://linux-hardware.org/?probe=1aa286ccff) | Jun 03, 2023 |
| Apple         | MacBookAir6,1               | [20a14caf03](https://linux-hardware.org/?probe=20a14caf03) | Jun 03, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | [f95d5c3046](https://linux-hardware.org/?probe=f95d5c3046) | Jun 03, 2023 |
| HONOR         | BBR-WAX9                    | [fe03659a55](https://linux-hardware.org/?probe=fe03659a55) | Jun 02, 2023 |
| Sony          | SVF1521A1EW                 | [4e3fe0308e](https://linux-hardware.org/?probe=4e3fe0308e) | Jun 02, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d856669333](https://linux-hardware.org/?probe=d856669333) | Jun 02, 2023 |
| Gigabyte      | G5 GE                       | [558ee7e63f](https://linux-hardware.org/?probe=558ee7e63f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3a51aa06b9](https://linux-hardware.org/?probe=3a51aa06b9) | Jun 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | [f576f54ff2](https://linux-hardware.org/?probe=f576f54ff2) | Jun 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [e920b77fbb](https://linux-hardware.org/?probe=e920b77fbb) | Jun 02, 2023 |
| HP            | Unknown                     | [626075d6f2](https://linux-hardware.org/?probe=626075d6f2) | Jun 02, 2023 |
| HP            | Unknown                     | [2289bb8d24](https://linux-hardware.org/?probe=2289bb8d24) | Jun 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [0a6e1e6be8](https://linux-hardware.org/?probe=0a6e1e6be8) | Jun 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [13adb1e221](https://linux-hardware.org/?probe=13adb1e221) | Jun 02, 2023 |
| Acer          | Nitro AN515-51              | [2dc3c08466](https://linux-hardware.org/?probe=2dc3c08466) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | [29d6e72544](https://linux-hardware.org/?probe=29d6e72544) | Jun 02, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [e28e041a5c](https://linux-hardware.org/?probe=e28e041a5c) | Jun 02, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [dcba8dc683](https://linux-hardware.org/?probe=dcba8dc683) | Jun 02, 2023 |
| Dell          | Latitude 7400               | [ef9ef10e4e](https://linux-hardware.org/?probe=ef9ef10e4e) | Jun 02, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [ca904474bf](https://linux-hardware.org/?probe=ca904474bf) | Jun 02, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [ea337d3d2a](https://linux-hardware.org/?probe=ea337d3d2a) | Jun 02, 2023 |
| HP            | EliteBook 8470p             | [bc606409ff](https://linux-hardware.org/?probe=bc606409ff) | Jun 01, 2023 |
| HONOR         | BBR-WAX9                    | [0a536c1198](https://linux-hardware.org/?probe=0a536c1198) | Jun 01, 2023 |
| UNOWHY        | Y13G002S4EI                 | [0bb0a8be66](https://linux-hardware.org/?probe=0bb0a8be66) | Jun 01, 2023 |
| HP            | ZBook 15 G3                 | [28eec89b69](https://linux-hardware.org/?probe=28eec89b69) | Jun 01, 2023 |
| Dell          | Latitude 7490               | [3cb9ad156f](https://linux-hardware.org/?probe=3cb9ad156f) | Jun 01, 2023 |
| Dell          | Precision 7540              | [de2fc5bc92](https://linux-hardware.org/?probe=de2fc5bc92) | Jun 01, 2023 |
| Timi          | A35S                        | [c9ce47a446](https://linux-hardware.org/?probe=c9ce47a446) | Jun 01, 2023 |
| Dell          | Latitude 5490               | [34dde30b90](https://linux-hardware.org/?probe=34dde30b90) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | [f3dc10c852](https://linux-hardware.org/?probe=f3dc10c852) | Jun 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | [8c16cec2e8](https://linux-hardware.org/?probe=8c16cec2e8) | Jun 01, 2023 |
| Dell          | Latitude 5531               | [5dc2ae0939](https://linux-hardware.org/?probe=5dc2ae0939) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | [1d128e6153](https://linux-hardware.org/?probe=1d128e6153) | Jun 01, 2023 |
| Timi          | TM1801                      | [aa1db210df](https://linux-hardware.org/?probe=aa1db210df) | Jun 01, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [0b0c375bb8](https://linux-hardware.org/?probe=0b0c375bb8) | May 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [65b03710b2](https://linux-hardware.org/?probe=65b03710b2) | May 31, 2023 |
| Acer          | Nitro AN515-42              | [fc808ec2fd](https://linux-hardware.org/?probe=fc808ec2fd) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | [a09171afde](https://linux-hardware.org/?probe=a09171afde) | May 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [f1e9073b3d](https://linux-hardware.org/?probe=f1e9073b3d) | May 31, 2023 |
| Dell          | Inspiron 15 5510            | [bd2319fd67](https://linux-hardware.org/?probe=bd2319fd67) | May 31, 2023 |
| Intel Clie... | LAPRC710                    | [ef0d589f75](https://linux-hardware.org/?probe=ef0d589f75) | May 31, 2023 |
| HP            | Unknown                     | [3eb658702b](https://linux-hardware.org/?probe=3eb658702b) | May 31, 2023 |
| Apple         | MacBookPro9,1               | [0b958e0c5c](https://linux-hardware.org/?probe=0b958e0c5c) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [93ac1fb021](https://linux-hardware.org/?probe=93ac1fb021) | May 31, 2023 |
| Lenovo        | ZhaoYangN4620Z 20A0Z037K... | [7e07cca977](https://linux-hardware.org/?probe=7e07cca977) | May 31, 2023 |
| Acer          | Nitro AN515-42              | [75f612c4db](https://linux-hardware.org/?probe=75f612c4db) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [32ba69494b](https://linux-hardware.org/?probe=32ba69494b) | May 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [2f61fcf47d](https://linux-hardware.org/?probe=2f61fcf47d) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6d6d7c65a8](https://linux-hardware.org/?probe=6d6d7c65a8) | May 31, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [5e96e1c54e](https://linux-hardware.org/?probe=5e96e1c54e) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMS1RM02    | [8f39bcbb17](https://linux-hardware.org/?probe=8f39bcbb17) | May 30, 2023 |
| Acer          | Nitro AN515-51              | [d3ee3757e0](https://linux-hardware.org/?probe=d3ee3757e0) | May 30, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [29ec12f64d](https://linux-hardware.org/?probe=29ec12f64d) | May 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [5881fb6ae2](https://linux-hardware.org/?probe=5881fb6ae2) | May 30, 2023 |
| Notebook      | P15SM-A/SM1-A               | [e71d8e3bc0](https://linux-hardware.org/?probe=e71d8e3bc0) | May 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S09E00    | [894bac5d62](https://linux-hardware.org/?probe=894bac5d62) | May 30, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [59e9fd9749](https://linux-hardware.org/?probe=59e9fd9749) | May 30, 2023 |
| HP            | Unknown                     | [2007104aeb](https://linux-hardware.org/?probe=2007104aeb) | May 30, 2023 |
| Dell          | XPS 13 9310                 | [a3e4ffb4fd](https://linux-hardware.org/?probe=a3e4ffb4fd) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [287ebf0b10](https://linux-hardware.org/?probe=287ebf0b10) | May 30, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [74447476fe](https://linux-hardware.org/?probe=74447476fe) | May 30, 2023 |
| HP            | EliteBook 6930p             | [882f43330b](https://linux-hardware.org/?probe=882f43330b) | May 30, 2023 |
| Dell          | Precision 5540              | [2f3cdafe90](https://linux-hardware.org/?probe=2f3cdafe90) | May 30, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [360e8fd5e5](https://linux-hardware.org/?probe=360e8fd5e5) | May 30, 2023 |
| VPU Compan... | VWNC51518                   | [16329bde51](https://linux-hardware.org/?probe=16329bde51) | May 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7816244e1a](https://linux-hardware.org/?probe=7816244e1a) | May 30, 2023 |
| MSI           | GF65 Thin 10UE              | [98e2096ab6](https://linux-hardware.org/?probe=98e2096ab6) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [5839982a52](https://linux-hardware.org/?probe=5839982a52) | May 29, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [048a3a0f30](https://linux-hardware.org/?probe=048a3a0f30) | May 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3933dfe4f0](https://linux-hardware.org/?probe=3933dfe4f0) | May 29, 2023 |
| Lenovo        | ThinkPad E490 20N8000RPG    | [73b8bfb3a5](https://linux-hardware.org/?probe=73b8bfb3a5) | May 29, 2023 |
| Sony          | VPCSA25GB                   | [981a09e39a](https://linux-hardware.org/?probe=981a09e39a) | May 29, 2023 |
| Sony          | VPCSA25GB                   | [e36e944a92](https://linux-hardware.org/?probe=e36e944a92) | May 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8e09d71949](https://linux-hardware.org/?probe=8e09d71949) | May 29, 2023 |
| Acer          | Aspire A315-51              | [d6f1c2bdbd](https://linux-hardware.org/?probe=d6f1c2bdbd) | May 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [230a02bfda](https://linux-hardware.org/?probe=230a02bfda) | May 29, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [8d25da413c](https://linux-hardware.org/?probe=8d25da413c) | May 29, 2023 |
| ASUSTek       | VivoBook S13 X330FN         | [e94b6fbf06](https://linux-hardware.org/?probe=e94b6fbf06) | May 29, 2023 |
| Dell          | Inspiron 7577               | [94e5a63c07](https://linux-hardware.org/?probe=94e5a63c07) | May 29, 2023 |
| Apple         | MacBookAir7,2               | [2f44574d7c](https://linux-hardware.org/?probe=2f44574d7c) | May 29, 2023 |
| HP            | Laptop 15-dw0xxx            | [a430b5287c](https://linux-hardware.org/?probe=a430b5287c) | May 29, 2023 |
| HP            | Pavilion g4                 | [12bef484db](https://linux-hardware.org/?probe=12bef484db) | May 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [14e5763b6f](https://linux-hardware.org/?probe=14e5763b6f) | May 29, 2023 |
| Lenovo        | ThinkPad Edge 0301DCU       | [5b7394bc19](https://linux-hardware.org/?probe=5b7394bc19) | May 28, 2023 |
| Apple         | MacBookAir7,2               | [5e146ef326](https://linux-hardware.org/?probe=5e146ef326) | May 28, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [01d3e0d237](https://linux-hardware.org/?probe=01d3e0d237) | May 28, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [1b4eb11af8](https://linux-hardware.org/?probe=1b4eb11af8) | May 28, 2023 |
| Dell          | XPS 9320                    | [33e7d964ad](https://linux-hardware.org/?probe=33e7d964ad) | May 28, 2023 |
| Acer          | Aspire A315-41              | [8bdf6722e2](https://linux-hardware.org/?probe=8bdf6722e2) | May 28, 2023 |
| Dell          | Inspiron 3542               | [423fe90cad](https://linux-hardware.org/?probe=423fe90cad) | May 28, 2023 |
| Razer         | Blade 15 Advanced Model ... | [92b96250d1](https://linux-hardware.org/?probe=92b96250d1) | May 28, 2023 |
| Toshiba       | Satellite C850-C5K          | [481789fa1e](https://linux-hardware.org/?probe=481789fa1e) | May 28, 2023 |
| Positivo      | N1250                       | [f014b93eba](https://linux-hardware.org/?probe=f014b93eba) | May 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [dc2b5e538f](https://linux-hardware.org/?probe=dc2b5e538f) | May 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [4147fc8cb7](https://linux-hardware.org/?probe=4147fc8cb7) | May 27, 2023 |
| Dell          | Latitude E6330              | [dd302db25c](https://linux-hardware.org/?probe=dd302db25c) | May 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [d9295f37bc](https://linux-hardware.org/?probe=d9295f37bc) | May 27, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [f068d88c01](https://linux-hardware.org/?probe=f068d88c01) | May 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [c8c8087ee8](https://linux-hardware.org/?probe=c8c8087ee8) | May 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | [902b837f1a](https://linux-hardware.org/?probe=902b837f1a) | May 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [767c697ac8](https://linux-hardware.org/?probe=767c697ac8) | May 27, 2023 |
| Dell          | Latitude E6330              | [f93b318d71](https://linux-hardware.org/?probe=f93b318d71) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [82cad47c63](https://linux-hardware.org/?probe=82cad47c63) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [09cc59aa19](https://linux-hardware.org/?probe=09cc59aa19) | May 27, 2023 |
| HP            | Pavilion x2 Detachable      | [e21476b6d2](https://linux-hardware.org/?probe=e21476b6d2) | May 26, 2023 |
| HP            | Laptop 14s-dk0xxx           | [5cf35078b0](https://linux-hardware.org/?probe=5cf35078b0) | May 26, 2023 |
| Acer          | Aspire F5-573G              | [f8ec1083ad](https://linux-hardware.org/?probe=f8ec1083ad) | May 26, 2023 |
| Acer          | Aspire F5-573G              | [eb636c0b30](https://linux-hardware.org/?probe=eb636c0b30) | May 26, 2023 |
| AAEON         | AEC-6637                    | [19050f7ccd](https://linux-hardware.org/?probe=19050f7ccd) | May 26, 2023 |
| Lenovo        | ThinkPad T460s 20F90058G... | [71a2e90192](https://linux-hardware.org/?probe=71a2e90192) | May 26, 2023 |
| Dell          | XPS 13 9310                 | [689eec8b51](https://linux-hardware.org/?probe=689eec8b51) | May 26, 2023 |
| Notebook      | NV4xPZ                      | [750cb90d83](https://linux-hardware.org/?probe=750cb90d83) | May 26, 2023 |
| Intel Clie... | LAPBC510                    | [fe45f8ba3c](https://linux-hardware.org/?probe=fe45f8ba3c) | May 26, 2023 |
| Acer          | Aspire V3-551               | [9d609ccd4a](https://linux-hardware.org/?probe=9d609ccd4a) | May 26, 2023 |
| Dell          | Inspiron 15-3567            | [0f79b43742](https://linux-hardware.org/?probe=0f79b43742) | May 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [29d761bff5](https://linux-hardware.org/?probe=29d761bff5) | May 26, 2023 |
| Dell          | G15 5525                    | [b2c8f44d8b](https://linux-hardware.org/?probe=b2c8f44d8b) | May 26, 2023 |
| Samsung       | 550XDA                      | [6cc9f3cbe4](https://linux-hardware.org/?probe=6cc9f3cbe4) | May 26, 2023 |
| ASUSTek       | X705UVR                     | [bedbf77e16](https://linux-hardware.org/?probe=bedbf77e16) | May 25, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DQ02    | [bb00a96df8](https://linux-hardware.org/?probe=bb00a96df8) | May 25, 2023 |
| Dell          | Precision 7540              | [99c7b41c6b](https://linux-hardware.org/?probe=99c7b41c6b) | May 25, 2023 |
| Unknown       | Unknown                     | [cfaffcaa0a](https://linux-hardware.org/?probe=cfaffcaa0a) | May 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [913f21a49c](https://linux-hardware.org/?probe=913f21a49c) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [3304e68c39](https://linux-hardware.org/?probe=3304e68c39) | May 25, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [5dd56ed986](https://linux-hardware.org/?probe=5dd56ed986) | May 25, 2023 |
| ASUSTek       | GL553VD                     | [51dbf3c463](https://linux-hardware.org/?probe=51dbf3c463) | May 25, 2023 |
| Dell          | Vostro 3480                 | [490c47960a](https://linux-hardware.org/?probe=490c47960a) | May 25, 2023 |
| Lenovo        | ThinkPad T440p 20AW0045M... | [355e03f684](https://linux-hardware.org/?probe=355e03f684) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [9294d16ea5](https://linux-hardware.org/?probe=9294d16ea5) | May 25, 2023 |
| Google        | Voxel                       | [9dae4b7464](https://linux-hardware.org/?probe=9dae4b7464) | May 25, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [d03d942df4](https://linux-hardware.org/?probe=d03d942df4) | May 24, 2023 |
| Dell          | Precision 7530              | [5cf37f39f4](https://linux-hardware.org/?probe=5cf37f39f4) | May 24, 2023 |
| Dell          | Precision 7540              | [65605ee5e8](https://linux-hardware.org/?probe=65605ee5e8) | May 24, 2023 |
| Dell          | Vostro 3480                 | [ae4f8dba2c](https://linux-hardware.org/?probe=ae4f8dba2c) | May 24, 2023 |
| Lenovo        | G500s 20245                 | [dd15a8197e](https://linux-hardware.org/?probe=dd15a8197e) | May 24, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [520e3d90a6](https://linux-hardware.org/?probe=520e3d90a6) | May 24, 2023 |
| ASUSTek       | UL30A                       | [d7ab3b0ed3](https://linux-hardware.org/?probe=d7ab3b0ed3) | May 24, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1280876877](https://linux-hardware.org/?probe=1280876877) | May 24, 2023 |
| ASUSTek       | X542UN                      | [29547f8e99](https://linux-hardware.org/?probe=29547f8e99) | May 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ba72bf9d52](https://linux-hardware.org/?probe=ba72bf9d52) | May 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [64ceddcdd4](https://linux-hardware.org/?probe=64ceddcdd4) | May 24, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d99af6bab2](https://linux-hardware.org/?probe=d99af6bab2) | May 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fff0e981f2](https://linux-hardware.org/?probe=fff0e981f2) | May 23, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [0dfd1ede62](https://linux-hardware.org/?probe=0dfd1ede62) | May 23, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [428a152134](https://linux-hardware.org/?probe=428a152134) | May 23, 2023 |
| Dell          | Inspiron 3593               | [715800f05d](https://linux-hardware.org/?probe=715800f05d) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [691b17e221](https://linux-hardware.org/?probe=691b17e221) | May 23, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [eaa5b878d3](https://linux-hardware.org/?probe=eaa5b878d3) | May 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [90235c6d2e](https://linux-hardware.org/?probe=90235c6d2e) | May 23, 2023 |
| HUAWEI        | CREF-XX                     | [39ff25bc94](https://linux-hardware.org/?probe=39ff25bc94) | May 23, 2023 |
| MSI           | GF65 Thin 9SE               | [c485674a13](https://linux-hardware.org/?probe=c485674a13) | May 23, 2023 |
| ASUSTek       | N75SF                       | [a385375f4d](https://linux-hardware.org/?probe=a385375f4d) | May 23, 2023 |
| Dell          | G5 5587                     | [18faf1497f](https://linux-hardware.org/?probe=18faf1497f) | May 23, 2023 |
| Apple         | MacBookPro8,1               | [fadd25f4c5](https://linux-hardware.org/?probe=fadd25f4c5) | May 23, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [cc966f1ede](https://linux-hardware.org/?probe=cc966f1ede) | May 23, 2023 |
| HP            | ENVY 15                     | [85a97390d5](https://linux-hardware.org/?probe=85a97390d5) | May 23, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | [c4040a0905](https://linux-hardware.org/?probe=c4040a0905) | May 23, 2023 |
| Lenovo        | ThinkPad T420 4180Q3U       | [56042328ac](https://linux-hardware.org/?probe=56042328ac) | May 23, 2023 |
| Lenovo        | ThinkPad T420 4180Q3U       | [0d63b518e4](https://linux-hardware.org/?probe=0d63b518e4) | May 23, 2023 |
| ASUSTek       | ET2321I                     | [829fe9b078](https://linux-hardware.org/?probe=829fe9b078) | May 23, 2023 |
| Dell          | Precision 7540              | [95bbab11f1](https://linux-hardware.org/?probe=95bbab11f1) | May 23, 2023 |
| HP            | Pavilion x2 Detachable      | [f9f3305d0b](https://linux-hardware.org/?probe=f9f3305d0b) | May 23, 2023 |
| UNOWHY        | Y13G011S4EI                 | [3642f34cd6](https://linux-hardware.org/?probe=3642f34cd6) | May 23, 2023 |
| Lenovo        | ThinkPad L480 20LTA01LLM    | [ed45fc495a](https://linux-hardware.org/?probe=ed45fc495a) | May 22, 2023 |
| HP            | EliteBook 840 G5            | [74a0ea4304](https://linux-hardware.org/?probe=74a0ea4304) | May 22, 2023 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [7d81e00b27](https://linux-hardware.org/?probe=7d81e00b27) | May 22, 2023 |
| Framework     | Laptop                      | [7715f5f056](https://linux-hardware.org/?probe=7715f5f056) | May 22, 2023 |
| Apple         | MacBookPro5,5               | [a4b0d5fd13](https://linux-hardware.org/?probe=a4b0d5fd13) | May 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [c492073bac](https://linux-hardware.org/?probe=c492073bac) | May 22, 2023 |
| Dell          | Precision 5560              | [1fc79f4cc0](https://linux-hardware.org/?probe=1fc79f4cc0) | May 22, 2023 |
| HP            | ENVY 15                     | [21a38278ca](https://linux-hardware.org/?probe=21a38278ca) | May 21, 2023 |
| MSI           | Modern 14 B11MOL            | [7bc8f5e875](https://linux-hardware.org/?probe=7bc8f5e875) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | [8c8c77d9a3](https://linux-hardware.org/?probe=8c8c77d9a3) | May 21, 2023 |
| HP            | Laptop 15-dy5xxx            | [3ab3a101e8](https://linux-hardware.org/?probe=3ab3a101e8) | May 21, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [0b3265b088](https://linux-hardware.org/?probe=0b3265b088) | May 21, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [916d381f2f](https://linux-hardware.org/?probe=916d381f2f) | May 21, 2023 |
| Dell          | XPS 13 9310                 | [19be933f8a](https://linux-hardware.org/?probe=19be933f8a) | May 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [8ec7bb4682](https://linux-hardware.org/?probe=8ec7bb4682) | May 21, 2023 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | [5a30bf445a](https://linux-hardware.org/?probe=5a30bf445a) | May 21, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [a6b4b230da](https://linux-hardware.org/?probe=a6b4b230da) | May 21, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [ef2b821a84](https://linux-hardware.org/?probe=ef2b821a84) | May 21, 2023 |
| ASUSTek       | G75VW                       | [7063bb70eb](https://linux-hardware.org/?probe=7063bb70eb) | May 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [fc75b5ebda](https://linux-hardware.org/?probe=fc75b5ebda) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [4fff2c9c8a](https://linux-hardware.org/?probe=4fff2c9c8a) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [157b535164](https://linux-hardware.org/?probe=157b535164) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [b695d18b13](https://linux-hardware.org/?probe=b695d18b13) | May 20, 2023 |
| HP            | ZBook 17 G2                 | [50b19fc413](https://linux-hardware.org/?probe=50b19fc413) | May 20, 2023 |
| Lenovo        | G500s 20245                 | [fc125408b5](https://linux-hardware.org/?probe=fc125408b5) | May 20, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [36d4349090](https://linux-hardware.org/?probe=36d4349090) | May 20, 2023 |
| Google        | Akemi                       | [595f8b1a24](https://linux-hardware.org/?probe=595f8b1a24) | May 20, 2023 |
| Dell          | Vostro 15-3568              | [5c6dbc1b8a](https://linux-hardware.org/?probe=5c6dbc1b8a) | May 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f8329fecb](https://linux-hardware.org/?probe=0f8329fecb) | May 20, 2023 |
| Lenovo        | ThinkPad W530 24382LU       | [908f53f58b](https://linux-hardware.org/?probe=908f53f58b) | May 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [e464ddd1b6](https://linux-hardware.org/?probe=e464ddd1b6) | May 20, 2023 |
| HP            | Laptop 17-by0061st          | [68e551f58a](https://linux-hardware.org/?probe=68e551f58a) | May 20, 2023 |
| Apple         | MacBookPro12,1              | [c25d920f3d](https://linux-hardware.org/?probe=c25d920f3d) | May 20, 2023 |
| HP            | Pavilion dv3                | [34c6a2c14a](https://linux-hardware.org/?probe=34c6a2c14a) | May 20, 2023 |
| Acer          | Nitro AN515-54              | [4f27fb9c64](https://linux-hardware.org/?probe=4f27fb9c64) | May 20, 2023 |
| Apple         | MacBookPro9,2               | [ac3d3ea87c](https://linux-hardware.org/?probe=ac3d3ea87c) | May 19, 2023 |
| HP            | Laptop 15-dw2xxx            | [7d7bdf142c](https://linux-hardware.org/?probe=7d7bdf142c) | May 19, 2023 |
| HP            | Laptop 15-dw2xxx            | [e0a1fa9223](https://linux-hardware.org/?probe=e0a1fa9223) | May 19, 2023 |
| Lenovo        | G500s 20245                 | [8c6b9dc52f](https://linux-hardware.org/?probe=8c6b9dc52f) | May 19, 2023 |
| Acer          | Aspire A515-57              | [3272ba5e49](https://linux-hardware.org/?probe=3272ba5e49) | May 19, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Fedora 36 | 1232      | 15.85%  |
| Fedora 37 | 1211      | 15.58%  |
| Fedora 38 | 1017      | 13.09%  |
| Fedora 35 | 969       | 12.47%  |
| Fedora 34 | 937       | 12.06%  |
| Fedora 33 | 855       | 11%     |
| Fedora 32 | 746       | 9.6%    |
| Fedora 31 | 503       | 6.47%   |
| Fedora 30 | 163       | 2.1%    |
| Fedora 29 | 90        | 1.16%   |
| Fedora 28 | 22        | 0.28%   |
| Fedora 39 | 9         | 0.12%   |
| Fedora 27 | 8         | 0.1%    |
| Fedora 24 | 4         | 0.05%   |
| Fedora 21 | 4         | 0.05%   |
| Fedora 25 | 2         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Fedora | 6965      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.15-300.fc38.x86_64  | 140       | 1.62%   |
| 6.3.8-200.fc38.x86_64   | 114       | 1.32%   |
| 5.17.5-300.fc36.x86_64  | 113       | 1.31%   |
| 6.2.9-300.fc38.x86_64   | 108       | 1.25%   |
| 5.16.18-200.fc35.x86_64 | 92        | 1.06%   |
| 6.2.14-300.fc38.x86_64  | 90        | 1.04%   |
| 6.0.7-301.fc37.x86_64   | 90        | 1.04%   |
| 5.9.16-200.fc33.x86_64  | 90        | 1.04%   |
| 6.2.11-300.fc38.x86_64  | 87        | 1.01%   |
| 5.11.12-300.fc34.x86_64 | 77        | 0.89%   |
| 6.0.15-300.fc37.x86_64  | 76        | 0.88%   |
| 5.14.10-300.fc35.x86_64 | 70        | 0.81%   |
| 6.0.5-200.fc36.x86_64   | 69        | 0.8%    |
| 5.8.16-300.fc33.x86_64  | 64        | 0.74%   |
| 6.3.12-200.fc38.x86_64  | 62        | 0.72%   |
| 6.1.14-200.fc37.x86_64  | 61        | 0.71%   |
| 5.18.13-200.fc36.x86_64 | 61        | 0.71%   |
| 5.8.15-301.fc33.x86_64  | 60        | 0.69%   |
| 5.8.4-200.fc32.x86_64   | 57        | 0.66%   |
| 6.1.7-200.fc37.x86_64   | 56        | 0.65%   |
| 6.0.8-300.fc37.x86_64   | 55        | 0.64%   |
| 5.13.12-200.fc34.x86_64 | 54        | 0.63%   |
| 6.0.9-300.fc37.x86_64   | 52        | 0.6%    |
| 6.4.6-200.fc38.x86_64   | 51        | 0.59%   |
| 6.1.18-200.fc37.x86_64  | 51        | 0.59%   |
| 6.0.12-300.fc37.x86_64  | 51        | 0.59%   |
| 6.3.11-200.fc38.x86_64  | 50        | 0.58%   |
| 5.18.11-200.fc36.x86_64 | 50        | 0.58%   |
| 6.4.7-200.fc38.x86_64   | 47        | 0.54%   |
| 5.19.16-200.fc36.x86_64 | 47        | 0.54%   |
| 6.2.8-200.fc37.x86_64   | 46        | 0.53%   |
| 6.2.13-300.fc38.x86_64  | 46        | 0.53%   |
| 5.8.18-300.fc33.x86_64  | 46        | 0.53%   |
| 5.17.11-300.fc36.x86_64 | 46        | 0.53%   |
| 5.14.16-301.fc35.x86_64 | 46        | 0.53%   |
| 6.3.5-200.fc38.x86_64   | 45        | 0.52%   |
| 5.9.8-200.fc33.x86_64   | 45        | 0.52%   |
| 5.18.16-200.fc36.x86_64 | 45        | 0.52%   |
| 5.16.16-200.fc35.x86_64 | 44        | 0.51%   |
| 6.3.6-200.fc38.x86_64   | 43        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.15  | 169       | 1.96%   |
| 6.2.9   | 149       | 1.73%   |
| 5.17.5  | 147       | 1.7%    |
| 6.3.8   | 125       | 1.45%   |
| 6.2.14  | 103       | 1.19%   |
| 6.0.7   | 100       | 1.16%   |
| 6.2.11  | 99        | 1.15%   |
| 5.9.16  | 96        | 1.11%   |
| 5.16.18 | 95        | 1.1%    |
| 5.8.15  | 87        | 1.01%   |
| 6.0.15  | 86        | 1%      |
| 5.11.12 | 84        | 0.97%   |
| 5.8.16  | 81        | 0.94%   |
| 5.14.10 | 79        | 0.91%   |
| 6.0.5   | 75        | 0.87%   |
| 5.19.16 | 75        | 0.87%   |
| 6.0.9   | 67        | 0.78%   |
| 6.0.8   | 66        | 0.76%   |
| 5.11.11 | 66        | 0.76%   |
| 6.0.12  | 65        | 0.75%   |
| 5.18.13 | 65        | 0.75%   |
| 6.3.12  | 64        | 0.74%   |
| 6.1.14  | 64        | 0.74%   |
| 5.8.18  | 64        | 0.74%   |
| 6.1.7   | 60        | 0.69%   |
| 6.2.8   | 57        | 0.66%   |
| 5.8.4   | 57        | 0.66%   |
| 5.13.12 | 57        | 0.66%   |
| 5.14.18 | 56        | 0.65%   |
| 5.18.11 | 53        | 0.61%   |
| 6.4.6   | 52        | 0.6%    |
| 6.1.18  | 52        | 0.6%    |
| 5.14.16 | 52        | 0.6%    |
| 6.4.7   | 51        | 0.59%   |
| 5.9.8   | 51        | 0.59%   |
| 5.19.8  | 51        | 0.59%   |
| 6.3.11  | 50        | 0.58%   |
| 5.17.11 | 50        | 0.58%   |
| 5.15.6  | 50        | 0.58%   |
| 5.19.9  | 49        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 720       | 8.72%   |
| 6.0     | 648       | 7.85%   |
| 5.17    | 515       | 6.24%   |
| 6.1     | 480       | 5.81%   |
| 5.8     | 464       | 5.62%   |
| 5.19    | 449       | 5.44%   |
| 5.11    | 449       | 5.44%   |
| 5.18    | 410       | 4.97%   |
| 6.3     | 394       | 4.77%   |
| 5.14    | 393       | 4.76%   |
| 5.16    | 384       | 4.65%   |
| 5.15    | 310       | 3.75%   |
| 5.9     | 304       | 3.68%   |
| 5.13    | 303       | 3.67%   |
| 5.10    | 294       | 3.56%   |
| 5.6     | 286       | 3.46%   |
| 5.12    | 282       | 3.42%   |
| 5.7     | 221       | 2.68%   |
| 5.3     | 194       | 2.35%   |
| 5.5     | 183       | 2.22%   |
| 5.4     | 168       | 2.03%   |
| 6.4     | 156       | 1.89%   |
| 5.0     | 62        | 0.75%   |
| 5.2     | 47        | 0.57%   |
| 5.1     | 43        | 0.52%   |
| 4.19    | 30        | 0.36%   |
| 4.18    | 27        | 0.33%   |
| 4.20    | 18        | 0.22%   |
| 4.16    | 3         | 0.04%   |
| 4.15    | 3         | 0.04%   |
| 4.11    | 3         | 0.04%   |
| 4.1     | 3         | 0.04%   |
| 6.5     | 2         | 0.02%   |
| 4.8     | 2         | 0.02%   |
| 4.17    | 2         | 0.02%   |
| 4.5     | 1         | 0.01%   |
| 4.14    | 1         | 0.01%   |
| 4.10    | 1         | 0.01%   |
| 3.17    | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 6955      | 99.84%  |
| i686    | 5         | 0.07%   |
| aarch64 | 5         | 0.07%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 5301      | 74.07%  |
| KDE5            | 816       | 11.4%   |
| Unknown         | 321       | 4.49%   |
| XFCE            | 148       | 2.07%   |
| KDE             | 136       | 1.9%    |
| X-Cinnamon      | 97        | 1.36%   |
| MATE            | 87        | 1.22%   |
| Cinnamon        | 76        | 1.06%   |
| i3              | 35        | 0.49%   |
| LXQt            | 23        | 0.32%   |
| GNOME Classic   | 23        | 0.32%   |
| LXDE            | 18        | 0.25%   |
| sway            | 17        | 0.24%   |
| Deepin          | 13        | 0.18%   |
| Budgie          | 8         | 0.11%   |
| Pantheon        | 5         | 0.07%   |
| KDE4            | 4         | 0.06%   |
| fluxbox         | 4         | 0.06%   |
| awesome         | 4         | 0.06%   |
| openbox         | 3         | 0.04%   |
| Hyprland        | 3         | 0.04%   |
| GNOME Flashback | 3         | 0.04%   |
| xinit-compat    | 2         | 0.03%   |
| GNOME-Classic   | 2         | 0.03%   |
| DWM             | 2         | 0.03%   |
| bspwm           | 2         | 0.03%   |
| xmonad          | 1         | 0.01%   |
| qtile           | 1         | 0.01%   |
| KDE:old         | 1         | 0.01%   |
| custom          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 4811      | 66.54%  |
| X11     | 2156      | 29.82%  |
| Unknown | 209       | 2.89%   |
| Tty     | 53        | 0.73%   |
| Xcb     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3670      | 51.22%  |
| GDM     | 2600      | 36.29%  |
| SDDM    | 499       | 6.96%   |
| LightDM | 280       | 3.91%   |
| TDM     | 87        | 1.21%   |
| XDM     | 10        | 0.14%   |
| LXDM    | 8         | 0.11%   |
| KDM     | 8         | 0.11%   |
| SLiM    | 1         | 0.01%   |
| Ly      | 1         | 0.01%   |
| GREETD  | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 3634      | 51.25%  |
| en_GB   | 494       | 6.97%   |
| Unknown | 370       | 5.22%   |
| pt_BR   | 336       | 4.74%   |
| ru_RU   | 322       | 4.54%   |
| de_DE   | 246       | 3.47%   |
| fr_FR   | 213       | 3%      |
| it_IT   | 184       | 2.59%   |
| pl_PL   | 115       | 1.62%   |
| es_ES   | 108       | 1.52%   |
| en_CA   | 100       | 1.41%   |
| en_AU   | 88        | 1.24%   |
| en_IN   | 87        | 1.23%   |
| es_MX   | 72        | 1.02%   |
| es_CL   | 48        | 0.68%   |
| cs_CZ   | 43        | 0.61%   |
| zh_CN   | 39        | 0.55%   |
| tr_TR   | 35        | 0.49%   |
| es_AR   | 34        | 0.48%   |
| pt_PT   | 26        | 0.37%   |
| nl_NL   | 26        | 0.37%   |
| hu_HU   | 25        | 0.35%   |
| de_AT   | 25        | 0.35%   |
| es_CO   | 24        | 0.34%   |
| sv_SE   | 23        | 0.32%   |
| en_DK   | 23        | 0.32%   |
| en_NZ   | 22        | 0.31%   |
| C       | 21        | 0.3%    |
| en_IE   | 17        | 0.24%   |
| ru_UA   | 15        | 0.21%   |
| fr_CA   | 15        | 0.21%   |
| en_ZA   | 15        | 0.21%   |
| fr_BE   | 12        | 0.17%   |
| fi_FI   | 12        | 0.17%   |
| es_PE   | 12        | 0.17%   |
| sk_SK   | 11        | 0.16%   |
| de_CH   | 11        | 0.16%   |
| nb_NO   | 10        | 0.14%   |
| da_DK   | 10        | 0.14%   |
| uk_UA   | 9         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 5671      | 80.33%  |
| BIOS | 1389      | 19.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Btrfs               | 4401      | 61.75%  |
| Ext4                | 2338      | 32.8%   |
| Unknown             | 196       | 2.75%   |
| Xfs                 | 169       | 2.37%   |
| Overlay             | 12        | 0.17%   |
| Zfs                 | 3         | 0.04%   |
| F2fs                | 3         | 0.04%   |
| Ext3                | 3         | 0.04%   |
| Fuse.fuse-overlayfs | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3645      | 51.11%  |
| GPT     | 3080      | 43.19%  |
| MBR     | 407       | 5.71%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6404      | 90.93%  |
| Yes       | 639       | 9.07%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5768      | 81.8%   |
| Yes       | 1283      | 18.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 2070      | 29.72%  |
| Dell                   | 1249      | 17.93%  |
| Hewlett-Packard        | 1040      | 14.93%  |
| ASUSTek Computer       | 711       | 10.21%  |
| Acer                   | 446       | 6.4%    |
| Apple                  | 190       | 2.73%   |
| MSI                    | 164       | 2.35%   |
| HUAWEI                 | 150       | 2.15%   |
| Toshiba                | 95        | 1.36%   |
| Samsung Electronics    | 93        | 1.34%   |
| Sony                   | 55        | 0.79%   |
| Notebook               | 55        | 0.79%   |
| Timi                   | 49        | 0.7%    |
| Google                 | 37        | 0.53%   |
| Unknown                | 35        | 0.5%    |
| Framework              | 33        | 0.47%   |
| Fujitsu                | 29        | 0.42%   |
| Alienware              | 27        | 0.39%   |
| Positivo               | 24        | 0.34%   |
| System76               | 20        | 0.29%   |
| TUXEDO                 | 19        | 0.27%   |
| Razer                  | 18        | 0.26%   |
| LG Electronics         | 16        | 0.23%   |
| Gigabyte Technology    | 15        | 0.22%   |
| HONOR                  | 13        | 0.19%   |
| Chuwi                  | 12        | 0.17%   |
| Avell High Performance | 12        | 0.17%   |
| PC Specialist          | 10        | 0.14%   |
| GPU Company            | 9         | 0.13%   |
| Schenker               | 8         | 0.11%   |
| Panasonic              | 8         | 0.11%   |
| GPD                    | 8         | 0.11%   |
| Fujitsu Siemens        | 8         | 0.11%   |
| SLIMBOOK               | 7         | 0.1%    |
| Packard Bell           | 6         | 0.09%   |
| Intel Client Systems   | 6         | 0.09%   |
| Insyde                 | 6         | 0.09%   |
| Hampoo                 | 6         | 0.09%   |
| Clevo                  | 6         | 0.09%   |
| UNOWHY                 | 5         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 59        | 0.85%   |
| HP Notebook                                | 34        | 0.49%   |
| Framework Laptop                           | 25        | 0.36%   |
| Dell XPS 15 9570                           | 25        | 0.36%   |
| Dell XPS 13 9370                           | 25        | 0.36%   |
| Dell Latitude 7490                         | 24        | 0.34%   |
| Dell XPS 15 7590                           | 23        | 0.33%   |
| Dell XPS 15 9560                           | 22        | 0.32%   |
| Dell XPS 13 9310                           | 21        | 0.3%    |
| HP EliteBook 840 G6                        | 19        | 0.27%   |
| Dell XPS 13 9360                           | 19        | 0.27%   |
| Dell XPS 13 7390                           | 19        | 0.27%   |
| Apple MacBookPro9,2                        | 19        | 0.27%   |
| Dell XPS 15 9500                           | 18        | 0.26%   |
| Dell Latitude E7450                        | 18        | 0.26%   |
| HP Pavilion dv6                            | 17        | 0.24%   |
| Dell XPS 15 9550                           | 17        | 0.24%   |
| HP Pavilion 15                             | 16        | 0.23%   |
| Apple MacBookPro12,1                       | 16        | 0.23%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 15        | 0.22%   |
| HP Laptop 15-da0xxx                        | 15        | 0.22%   |
| HP Pavilion Notebook                       | 14        | 0.2%    |
| Dell XPS 13 9300                           | 14        | 0.2%    |
| Dell Latitude E6420                        | 14        | 0.2%    |
| Dell Latitude 5480                         | 14        | 0.2%    |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 13        | 0.19%   |
| HUAWEI KLVL-WXX9                           | 13        | 0.19%   |
| HP EliteBook 840 G3                        | 13        | 0.19%   |
| Dell XPS 15 9510                           | 13        | 0.19%   |
| Dell Latitude E7440                        | 13        | 0.19%   |
| Dell Inspiron 15 7000 Gaming               | 13        | 0.19%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 13        | 0.19%   |
| Apple MacBookPro8,1                        | 13        | 0.19%   |
| Acer Nitro AN515-54                        | 13        | 0.19%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 12        | 0.17%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 12        | 0.17%   |
| HUAWEI NBLK-WAX9X                          | 12        | 0.17%   |
| Dell XPS 13 9380                           | 12        | 0.17%   |
| Dell XPS 13 9350                           | 12        | 0.17%   |
| Dell Latitude E6520                        | 12        | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1249      | 17.93%  |
| Lenovo IdeaPad     | 419       | 6.02%   |
| Dell Latitude      | 377       | 5.41%   |
| Dell Inspiron      | 349       | 5.01%   |
| Acer Aspire        | 286       | 4.11%   |
| Dell XPS           | 284       | 4.08%   |
| HP Pavilion        | 224       | 3.22%   |
| HP EliteBook       | 192       | 2.76%   |
| HP ProBook         | 157       | 2.25%   |
| HP Laptop          | 152       | 2.18%   |
| ASUS VivoBook      | 150       | 2.15%   |
| ASUS ROG           | 119       | 1.71%   |
| Dell Precision     | 103       | 1.48%   |
| Lenovo Legion      | 87        | 1.25%   |
| Lenovo ThinkBook   | 80        | 1.15%   |
| Toshiba Satellite  | 78        | 1.12%   |
| Lenovo Yoga        | 65        | 0.93%   |
| Acer Nitro         | 65        | 0.93%   |
| Dell Vostro        | 61        | 0.88%   |
| ASUS ASUS          | 61        | 0.88%   |
| Unknown            | 59        | 0.85%   |
| HP ZBook           | 55        | 0.79%   |
| ASUS ZenBook       | 55        | 0.79%   |
| HP ENVY            | 46        | 0.66%   |
| Acer Swift         | 41        | 0.59%   |
| HP OMEN            | 35        | 0.5%    |
| Apple MacBookPro11 | 35        | 0.5%    |
| HP Notebook        | 34        | 0.49%   |
| Framework Laptop   | 33        | 0.47%   |
| ASUS TUF           | 32        | 0.46%   |
| MSI Modern         | 28        | 0.4%    |
| Fujitsu LIFEBOOK   | 23        | 0.33%   |
| Dell G5            | 23        | 0.33%   |
| Apple MacBookPro9  | 23        | 0.33%   |
| Acer Predator      | 19        | 0.27%   |
| HP 250             | 18        | 0.26%   |
| Apple MacBookPro8  | 18        | 0.26%   |
| Razer Blade        | 17        | 0.24%   |
| Apple MacBookPro12 | 16        | 0.23%   |
| Dell G3            | 15        | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 943       | 13.54%  |
| 2019    | 896       | 12.86%  |
| 2021    | 859       | 12.33%  |
| 2018    | 728       | 10.45%  |
| 2017    | 523       | 7.51%   |
| 2015    | 413       | 5.93%   |
| 2016    | 398       | 5.71%   |
| 2012    | 397       | 5.7%    |
| 2022    | 387       | 5.56%   |
| 2013    | 374       | 5.37%   |
| 2014    | 352       | 5.05%   |
| 2011    | 298       | 4.28%   |
| 2010    | 153       | 2.2%    |
| 2008    | 91        | 1.31%   |
| 2009    | 72        | 1.03%   |
| 2023    | 47        | 0.67%   |
| 2007    | 22        | 0.32%   |
| 2006    | 6         | 0.09%   |
| Unknown | 5         | 0.07%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 6965      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5573      | 78.6%   |
| Enabled  | 1517      | 21.4%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6906      | 99.15%  |
| Yes  | 59        | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2069      | 29.28%  |
| 16.01-24.0  | 1698      | 24.03%  |
| 8.01-16.0   | 1401      | 19.82%  |
| 32.01-64.0  | 788       | 11.15%  |
| 3.01-4.0    | 687       | 9.72%   |
| 24.01-32.0  | 131       | 1.85%   |
| 1.01-2.0    | 130       | 1.84%   |
| 64.01-256.0 | 124       | 1.75%   |
| 2.01-3.0    | 26        | 0.37%   |
| 0.51-1.0    | 11        | 0.16%   |
| Unknown     | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 2173      | 27.8%   |
| 4.01-8.0   | 2148      | 27.48%  |
| 3.01-4.0   | 1756      | 22.46%  |
| 1.01-2.0   | 1005      | 12.86%  |
| 8.01-16.0  | 567       | 7.25%   |
| 0.51-1.0   | 80        | 1.02%   |
| 16.01-24.0 | 61        | 0.78%   |
| 24.01-32.0 | 15        | 0.19%   |
| 32.01-64.0 | 7         | 0.09%   |
| 0.01-0.5   | 3         | 0.04%   |
| Unknown    | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5139      | 72.52%  |
| 2      | 1671      | 23.58%  |
| 3      | 192       | 2.71%   |
| 0      | 37        | 0.52%   |
| 4      | 32        | 0.45%   |
| 5      | 9         | 0.13%   |
| 6      | 5         | 0.07%   |
| 8      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5551      | 79.36%  |
| Yes       | 1444      | 20.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5164      | 73.69%  |
| No        | 1844      | 26.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6834      | 98.03%  |
| No        | 137       | 1.97%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5884      | 83.48%  |
| No        | 1164      | 16.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1174      | 16.68%  |
| Brazil      | 513       | 7.29%   |
| Germany     | 492       | 6.99%   |
| Russia      | 447       | 6.35%   |
| Italy       | 328       | 4.66%   |
| France      | 283       | 4.02%   |
| India       | 274       | 3.89%   |
| UK          | 245       | 3.48%   |
| Poland      | 209       | 2.97%   |
| Netherlands | 206       | 2.93%   |
| Canada      | 194       | 2.76%   |
| Spain       | 165       | 2.34%   |
| Mexico      | 135       | 1.92%   |
| Czechia     | 118       | 1.68%   |
| Turkey      | 113       | 1.61%   |
| Australia   | 108       | 1.53%   |
| Austria     | 89        | 1.26%   |
| Sweden      | 88        | 1.25%   |
| Switzerland | 76        | 1.08%   |
| Portugal    | 70        | 0.99%   |
| Belgium     | 68        | 0.97%   |
| Chile       | 65        | 0.92%   |
| Argentina   | 64        | 0.91%   |
| Ukraine     | 63        | 0.9%    |
| Indonesia   | 62        | 0.88%   |
| Hungary     | 61        | 0.87%   |
| Romania     | 60        | 0.85%   |
| Norway      | 57        | 0.81%   |
| Finland     | 56        | 0.8%    |
| Denmark     | 50        | 0.71%   |
| Colombia    | 45        | 0.64%   |
| China       | 44        | 0.63%   |
| Iran        | 40        | 0.57%   |
| Bulgaria    | 39        | 0.55%   |
| Israel      | 36        | 0.51%   |
| Slovakia    | 33        | 0.47%   |
| Greece      | 33        | 0.47%   |
| Belarus     | 33        | 0.47%   |
| Japan       | 30        | 0.43%   |
| New Zealand | 29        | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 149       | 1.98%   |
| Sao Paulo         | 70        | 0.93%   |
| St Petersburg     | 61        | 0.81%   |
| Berlin            | 59        | 0.79%   |
| Vienna            | 56        | 0.75%   |
| Paris             | 55        | 0.73%   |
| Amsterdam         | 50        | 0.67%   |
| Prague            | 48        | 0.64%   |
| Milan             | 48        | 0.64%   |
| Istanbul          | 48        | 0.64%   |
| Warsaw            | 47        | 0.63%   |
| Madrid            | 40        | 0.53%   |
| Bengaluru         | 37        | 0.49%   |
| Helsinki          | 35        | 0.47%   |
| Munich            | 34        | 0.45%   |
| Mexico City       | 34        | 0.45%   |
| Oslo              | 32        | 0.43%   |
| Melbourne         | 32        | 0.43%   |
| Sydney            | 30        | 0.4%    |
| Frankfurt am Main | 29        | 0.39%   |
| Budapest          | 29        | 0.39%   |
| Santiago          | 28        | 0.37%   |
| Rio de Janeiro    | 28        | 0.37%   |
| Delft             | 27        | 0.36%   |
| Lisbon            | 26        | 0.35%   |
| Sofia             | 25        | 0.33%   |
| Jakarta           | 25        | 0.33%   |
| Hamburg           | 25        | 0.33%   |
| Bucharest         | 25        | 0.33%   |
| Zurich            | 24        | 0.32%   |
| Montreal          | 24        | 0.32%   |
| Kyiv              | 24        | 0.32%   |
| Singapore         | 23        | 0.31%   |
| Brisbane          | 23        | 0.31%   |
| Tehran            | 22        | 0.29%   |
| Brasília         | 22        | 0.29%   |
| Rome              | 21        | 0.28%   |
| Pune              | 21        | 0.28%   |
| Portland          | 21        | 0.28%   |
| Chicago           | 21        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1876      | 2684   | 21.24%  |
| WDC                         | 855       | 1081   | 9.68%   |
| Sandisk                     | 676       | 866    | 7.65%   |
| Seagate                     | 627       | 826    | 7.1%    |
| Toshiba                     | 592       | 742    | 6.7%    |
| SK hynix                    | 527       | 648    | 5.97%   |
| Unknown                     | 460       | 600    | 5.21%   |
| Kingston                    | 437       | 534    | 4.95%   |
| Intel                       | 371       | 518    | 4.2%    |
| Micron Technology           | 296       | 383    | 3.35%   |
| Crucial                     | 259       | 340    | 2.93%   |
| HGST                        | 173       | 240    | 1.96%   |
| KIOXIA                      | 135       | 188    | 1.53%   |
| A-DATA Technology           | 130       | 150    | 1.47%   |
| Apple                       | 106       | 143    | 1.2%    |
| Hitachi                     | 82        | 95     | 0.93%   |
| LITEON                      | 75        | 81     | 0.85%   |
| Phison                      | 62        | 70     | 0.7%    |
| China                       | 61        | 73     | 0.69%   |
| Silicon Motion              | 55        | 72     | 0.62%   |
| Micron/Crucial Technology   | 40        | 43     | 0.45%   |
| PNY                         | 39        | 51     | 0.44%   |
| Transcend                   | 38        | 55     | 0.43%   |
| SPCC                        | 35        | 45     | 0.4%    |
| Phison Electronics          | 35        | 37     | 0.4%    |
| ADATA Technology            | 34        | 36     | 0.39%   |
| LITEONIT                    | 28        | 34     | 0.32%   |
| Lenovo                      | 26        | 29     | 0.29%   |
| Kingston Technology Company | 26        | 29     | 0.29%   |
| JMicron Technology          | 25        | 30     | 0.28%   |
| Unknown                     | 24        | 29     | 0.27%   |
| Corsair                     | 22        | 27     | 0.25%   |
| Realtek Semiconductor       | 21        | 26     | 0.24%   |
| XPG                         | 18        | 27     | 0.2%    |
| Patriot                     | 18        | 24     | 0.2%    |
| UMIS                        | 17        | 20     | 0.19%   |
| Team                        | 17        | 20     | 0.19%   |
| Intenso                     | 17        | 20     | 0.19%   |
| Hewlett-Packard             | 17        | 16     | 0.19%   |
| Gigabyte Technology         | 17        | 22     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 140       | 1.51%   |
| Seagate ST1000LM035-1RK172 1TB                      | 136       | 1.47%   |
| Samsung NVMe SSD Drive 512GB                        | 113       | 1.22%   |
| Kingston SA400S37240G 240GB SSD                     | 85        | 0.92%   |
| Samsung NVMe SSD Drive 256GB                        | 83        | 0.9%    |
| SanDisk NVMe SSD Drive 512GB                        | 81        | 0.87%   |
| Toshiba MQ04ABF100 1TB                              | 74        | 0.8%    |
| HGST HTS721010A9E630 1TB                            | 74        | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 73        | 0.79%   |
| Unknown MMC Card  32GB                              | 72        | 0.78%   |
| Unknown MMC Card  64GB                              | 71        | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 69        | 0.74%   |
| Toshiba MQ01ABD100 1TB                              | 60        | 0.65%   |
| Kingston SA400S37480G 480GB SSD                     | 60        | 0.65%   |
| Samsung SSD 860 EVO 500GB                           | 59        | 0.64%   |
| SK hynix NVMe SSD Drive 512GB                       | 51        | 0.55%   |
| Samsung NVMe SSD Drive 1024GB                       | 51        | 0.55%   |
| SanDisk NVMe SSD Drive 256GB                        | 48        | 0.52%   |
| Intel NVMe SSD Drive 512GB                          | 46        | 0.5%    |
| Unknown MMC Card  128GB                             | 45        | 0.49%   |
| Samsung NVMe SSD Drive 1TB                          | 43        | 0.46%   |
| Samsung SSD 850 EVO 500GB                           | 42        | 0.45%   |
| Samsung SSD 850 EVO 250GB                           | 42        | 0.45%   |
| Toshiba NVMe SSD Drive 512GB                        | 38        | 0.41%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 38        | 0.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 38        | 0.41%   |
| Seagate ST500LT012-1DG142 500GB                     | 37        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                        | 35        | 0.38%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 34        | 0.37%   |
| Seagate Expansion 1TB                               | 34        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                         | 34        | 0.37%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD                 | 33        | 0.36%   |
| Samsung SSD 860 EVO 250GB                           | 33        | 0.36%   |
| Samsung NVMe SSD Drive 500GB                        | 33        | 0.36%   |
| Samsung SSD 860 EVO 1TB                             | 32        | 0.35%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 31        | 0.33%   |
| HGST HTS541010A9E680 1TB                            | 31        | 0.33%   |
| SK hynix NVMe SSD Drive 256GB                       | 30        | 0.32%   |
| Samsung SSD 980 1TB                                 | 30        | 0.32%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 30        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 603       | 792    | 35.74%  |
| WDC                 | 441       | 565    | 26.14%  |
| Toshiba             | 287       | 352    | 17.01%  |
| HGST                | 173       | 240    | 10.25%  |
| Hitachi             | 82        | 95     | 4.86%   |
| Unknown             | 23        | 34     | 1.36%   |
| JMicron Technology  | 17        | 21     | 1.01%   |
| Samsung Electronics | 16        | 19     | 0.95%   |
| Fujitsu             | 11        | 11     | 0.65%   |
| Apple               | 11        | 12     | 0.65%   |
| External            | 4         | 6      | 0.24%   |
| ASMT                | 3         | 4      | 0.18%   |
| USB3.0              | 2         | 2      | 0.12%   |
| LIO-ORG             | 2         | 8      | 0.12%   |
| LaCie               | 2         | 3      | 0.12%   |
| HGST HTS            | 2         | 2      | 0.12%   |
| SSK                 | 1         | 1      | 0.06%   |
| QNAP                | 1         | 4      | 0.06%   |
| Phison              | 1         | 2      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| Inateck             | 1         | 1      | 0.06%   |
| IB-AC703            | 1         | 1      | 0.06%   |
| IB                  | 1         | 2      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 664       | 946    | 24.9%   |
| Kingston            | 313       | 380    | 11.74%  |
| SanDisk             | 278       | 376    | 10.42%  |
| Crucial             | 231       | 309    | 8.66%   |
| WDC                 | 140       | 178    | 5.25%   |
| Intel               | 92        | 144    | 3.45%   |
| Micron Technology   | 87        | 106    | 3.26%   |
| A-DATA Technology   | 83        | 98     | 3.11%   |
| Apple               | 73        | 83     | 2.74%   |
| SK hynix            | 69        | 83     | 2.59%   |
| LITEON              | 60        | 66     | 2.25%   |
| China               | 60        | 72     | 2.25%   |
| Toshiba             | 58        | 75     | 2.17%   |
| PNY                 | 37        | 48     | 1.39%   |
| Transcend           | 32        | 45     | 1.2%    |
| SPCC                | 28        | 38     | 1.05%   |
| LITEONIT            | 28        | 34     | 1.05%   |
| Patriot             | 16        | 21     | 0.6%    |
| OCZ                 | 15        | 17     | 0.56%   |
| KingSpec            | 14        | 16     | 0.52%   |
| Intenso             | 14        | 16     | 0.52%   |
| Gigabyte Technology | 14        | 19     | 0.52%   |
| Corsair             | 14        | 16     | 0.52%   |
| Netac               | 13        | 17     | 0.49%   |
| GOODRAM             | 12        | 20     | 0.45%   |
| Team                | 11        | 14     | 0.41%   |
| Lexar               | 11        | 19     | 0.41%   |
| Hewlett-Packard     | 10        | 10     | 0.37%   |
| Seagate             | 9         | 9      | 0.34%   |
| Apacer              | 9         | 12     | 0.34%   |
| Plextor             | 7         | 10     | 0.26%   |
| Unknown             | 6         | 6      | 0.22%   |
| TO Exter            | 5         | 5      | 0.19%   |
| Ramsta              | 5         | 6      | 0.19%   |
| FORESEE             | 5         | 5      | 0.19%   |
| Unknown             | 5         | 6      | 0.19%   |
| Mushkin             | 4         | 13     | 0.15%   |
| Leven               | 4         | 4      | 0.15%   |
| KingDian            | 4         | 4      | 0.15%   |
| Dogfish             | 4         | 4      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3679      | 5160   | 44.23%  |
| SSD     | 2473      | 3495   | 29.73%  |
| HDD     | 1624      | 2179   | 19.52%  |
| MMC     | 435       | 575    | 5.23%   |
| Unknown | 107       | 121    | 1.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 3673      | 5142   | 46.03%  |
| SATA | 3580      | 5423   | 44.87%  |
| MMC  | 435       | 575    | 5.45%   |
| SAS  | 291       | 390    | 3.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2522      | 3552   | 61.81%  |
| 0.51-1.0   | 1392      | 1877   | 34.12%  |
| 1.01-2.0   | 137       | 213    | 3.36%   |
| 4.01-10.0  | 18        | 19     | 0.44%   |
| 3.01-4.0   | 9         | 10     | 0.22%   |
| 10.01-20.0 | 1         | 1      | 0.02%   |
| 0          | 1         | 2      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1621      | 22.18%  |
| 501-1000       | 1540      | 21.07%  |
| 101-250        | 1309      | 17.91%  |
| 1001-2000      | 807       | 11.04%  |
| 1-20           | 773       | 10.58%  |
| Unknown        | 526       | 7.2%    |
| 51-100         | 287       | 3.93%   |
| 21-50          | 161       | 2.2%    |
| More than 3000 | 149       | 2.04%   |
| 2001-3000      | 136       | 1.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2315      | 30.19%  |
| 21-50          | 1333      | 17.39%  |
| 101-250        | 1188      | 15.49%  |
| 51-100         | 999       | 13.03%  |
| 251-500        | 720       | 9.39%   |
| Unknown        | 526       | 6.86%   |
| 501-1000       | 414       | 5.4%    |
| 1001-2000      | 133       | 1.73%   |
| More than 3000 | 21        | 0.27%   |
| 2001-3000      | 17        | 0.22%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                | 11        | 11     | 3.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 19     | 2.95%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 2.3%    |
| HGST HTS721010A9E630 1TB                       | 7         | 9      | 2.3%    |
| HGST HTS541010A9E680 1TB                       | 7         | 7      | 2.3%    |
| Toshiba MQ01ABD100 1TB                         | 6         | 6      | 1.97%   |
| Seagate ST9500325AS 500GB                      | 6         | 8      | 1.97%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 6         | 6      | 1.97%   |
| HGST HTS545050A7E680 500GB                     | 6         | 6      | 1.97%   |
| Toshiba MQ01ABD075 752GB                       | 4         | 4      | 1.31%   |
| Hitachi HTS547575A9E384 752GB                  | 4         | 6      | 1.31%   |
| HGST HTS725050A7E630 500GB                     | 4         | 4      | 1.31%   |
| Toshiba MQ01ABF050 500GB                       | 3         | 3      | 0.98%   |
| SK hynix SC308 SATA 128GB SSD                  | 3         | 3      | 0.98%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 0.98%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 4      | 0.98%   |
| Samsung Electronics SSD 980 1TB                | 3         | 3      | 0.98%   |
| Samsung Electronics SSD 870 EVO 500GB          | 3         | 6      | 0.98%   |
| Hitachi HTS545050B9A300 500GB                  | 3         | 3      | 0.98%   |
| Crucial CT1000P1SSD8 1TB                       | 3         | 3      | 0.98%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 2         | 2      | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 2         | 2      | 0.66%   |
| WDC WD10SPZX-24Z10 1TB                         | 2         | 2      | 0.66%   |
| Toshiba MQ01ACF050 500GB                       | 2         | 2      | 0.66%   |
| Toshiba MQ01ABD050V 500GB                      | 2         | 2      | 0.66%   |
| Toshiba MK5061GSY 500GB                        | 2         | 2      | 0.66%   |
| Toshiba MK3275GSX 320GB                        | 2         | 3      | 0.66%   |
| SPCC Solid State Disk 256GB                    | 2         | 2      | 0.66%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 2         | 2      | 0.66%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 2         | 2      | 0.66%   |
| Seagate ST9500420AS 500GB                      | 2         | 3      | 0.66%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.66%   |
| Seagate ST500LM000-SSHD-8GB                    | 2         | 3      | 0.66%   |
| Seagate ST500LM000-1EJ162 500GB                | 2         | 2      | 0.66%   |
| Seagate ST2000LM003 HN-M201RAD 2TB             | 2         | 2      | 0.66%   |
| Seagate ST1000LM049-2GH172 1TB                 | 2         | 3      | 0.66%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.66%   |
| SanDisk SSD PLUS 240GB                         | 2         | 2      | 0.66%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD            | 2         | 2      | 0.66%   |
| Micron Technology 1100 SATA 256GB SSD          | 2         | 2      | 0.66%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 79     | 20.39%  |
| Toshiba             | 34        | 35     | 11.18%  |
| WDC                 | 31        | 34     | 10.2%   |
| HGST                | 28        | 30     | 9.21%   |
| Samsung Electronics | 27        | 32     | 8.88%   |
| Hitachi             | 19        | 23     | 6.25%   |
| Micron Technology   | 15        | 18     | 4.93%   |
| SK hynix            | 13        | 14     | 4.28%   |
| Intel               | 13        | 24     | 4.28%   |
| Crucial             | 12        | 20     | 3.95%   |
| SanDisk             | 11        | 13     | 3.62%   |
| Kingston            | 8         | 9      | 2.63%   |
| A-DATA Technology   | 5         | 5      | 1.64%   |
| LITEON              | 4         | 4      | 1.32%   |
| Fujitsu             | 3         | 3      | 0.99%   |
| SPCC                | 2         | 2      | 0.66%   |
| LITEONIT            | 2         | 3      | 0.66%   |
| China               | 2         | 2      | 0.66%   |
| YS                  | 1         | 1      | 0.33%   |
| walram              | 1         | 1      | 0.33%   |
| Union Memory        | 1         | 1      | 0.33%   |
| Teclast             | 1         | 1      | 0.33%   |
| SSSTC               | 1         | 1      | 0.33%   |
| SSD                 | 1         | 1      | 0.33%   |
| PNY                 | 1         | 1      | 0.33%   |
| Plextor             | 1         | 1      | 0.33%   |
| Origin              | 1         | 1      | 0.33%   |
| OCZ-VERTEX3         | 1         | 1      | 0.33%   |
| Lenovo              | 1         | 2      | 0.33%   |
| HGST HTS            | 1         | 1      | 0.33%   |
| Unknown             | 1         | 1      | 0.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 79     | 35.03%  |
| Toshiba             | 33        | 34     | 18.64%  |
| HGST                | 28        | 30     | 15.82%  |
| WDC                 | 27        | 30     | 15.25%  |
| Hitachi             | 19        | 23     | 10.73%  |
| Samsung Electronics | 4         | 4      | 2.26%   |
| Fujitsu             | 3         | 3      | 1.69%   |
| HGST HTS            | 1         | 1      | 0.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 176       | 204    | 58.28%  |
| SSD  | 102       | 133    | 33.77%  |
| NVMe | 24        | 27     | 7.95%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 14.29%  |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1         | 1      | 14.29%  |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 14.29%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 14.29%  |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 42.86%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4042      | 6665   | 54.12%  |
| Works    | 3127      | 4494   | 41.87%  |
| Malfunc  | 293       | 364    | 3.92%   |
| Failed   | 7         | 7      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 4244      | 48.7%   |
| Samsung Electronics                     | 1293      | 14.84%  |
| AMD                                     | 732       | 8.4%    |
| SanDisk                                 | 648       | 7.44%   |
| SK hynix                                | 444       | 5.09%   |
| Toshiba America Info Systems            | 253       | 2.9%    |
| Micron Technology                       | 211       | 2.42%   |
| Kingston Technology Company             | 151       | 1.73%   |
| KIOXIA                                  | 135       | 1.55%   |
| Phison Electronics                      | 108       | 1.24%   |
| ADATA Technology                        | 89        | 1.02%   |
| Silicon Motion                          | 73        | 0.84%   |
| Micron/Crucial Technology               | 66        | 0.76%   |
| Union Memory (Shenzhen)                 | 37        | 0.42%   |
| Solid State Storage Technology          | 31        | 0.36%   |
| Nvidia                                  | 30        | 0.34%   |
| Lite-On Technology                      | 29        | 0.33%   |
| Realtek Semiconductor                   | 28        | 0.32%   |
| Lenovo                                  | 24        | 0.28%   |
| Apple                                   | 19        | 0.22%   |
| Seagate Technology                      | 11        | 0.13%   |
| Yangtze Memory Technologies             | 10        | 0.11%   |
| Shenzhen Longsys Electronics            | 8         | 0.09%   |
| MAXIO Technology (Hangzhou)             | 7         | 0.08%   |
| Marvell Technology Group                | 7         | 0.08%   |
| JMicron Technology                      | 5         | 0.06%   |
| Biwin Storage Technology                | 4         | 0.05%   |
| Netac Technology                        | 3         | 0.03%   |
| Solidigm                                | 2         | 0.02%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.02%   |
| Shenzhen Unionmemory Information System | 2         | 0.02%   |
| ULi Electronics                         | 1         | 0.01%   |
| Transcend                               | 1         | 0.01%   |
| OCZ Technology Group                    | 1         | 0.01%   |
| Lite-On IT Corp. / Plextor              | 1         | 0.01%   |
| INNOGRIT                                | 1         | 0.01%   |
| Enmotus                                 | 1         | 0.01%   |
| Beijing Starblaze Technology            | 1         | 0.01%   |
| ASMedia Technology                      | 1         | 0.01%   |
| Unknown                                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 700       | 7.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 672       | 7.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 633       | 6.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 416       | 4.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 409       | 4.48%   |
| Intel Volume Management Device NVMe RAID Controller                            | 301       | 3.3%    |
| Samsung NVMe SSD Controller 980                                                | 296       | 3.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 261       | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 244       | 2.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 229       | 2.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 200       | 2.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 185       | 2.03%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 178       | 1.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 174       | 1.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 172       | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 166       | 1.82%   |
| Intel Tiger Lake-LP SATA Controller                                            | 127       | 1.39%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 126       | 1.38%   |
| Intel Comet Lake SATA AHCI Controller                                          | 121       | 1.33%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 119       | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 111       | 1.22%   |
| Intel SSD 660P Series                                                          | 105       | 1.15%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 103       | 1.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 96        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 80        | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 80        | 0.88%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 74        | 0.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 74        | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 71        | 0.78%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 70        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 69        | 0.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 68        | 0.75%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 67        | 0.73%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 63        | 0.69%   |
| SK hynix BC511 NVMe SSD                                                        | 62        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 59        | 0.65%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 55        | 0.6%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 51        | 0.56%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 49        | 0.54%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 49        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 4235      | 48.28%  |
| NVMe | 3676      | 41.91%  |
| RAID | 739       | 8.43%   |
| IDE  | 121       | 1.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 5596      | 80.34%  |
| AMD          | 1362      | 19.55%  |
| ARM          | 4         | 0.06%   |
| Unknown      | 2         | 0.03%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 171       | 2.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 167       | 2.4%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 143       | 2.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 141       | 2.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 117       | 1.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 117       | 1.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 115       | 1.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 110       | 1.58%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 110       | 1.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 108       | 1.55%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 107       | 1.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 98        | 1.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 97        | 1.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 95        | 1.36%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 91        | 1.31%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 81        | 1.16%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 80        | 1.15%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 76        | 1.09%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 73        | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 68        | 0.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 67        | 0.96%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 66        | 0.95%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 66        | 0.95%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 66        | 0.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 59        | 0.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 59        | 0.85%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 53        | 0.76%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 51        | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 49        | 0.7%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 48        | 0.69%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 48        | 0.69%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 47        | 0.67%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 47        | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 46        | 0.66%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 44        | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 42        | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 41        | 0.59%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 41        | 0.59%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 39        | 0.56%   |
| Intel 12th Gen Core i7-12700H                 | 39        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 2011      | 28.86%  |
| Intel Core i5                  | 1729      | 24.82%  |
| Other                          | 821       | 11.78%  |
| AMD Ryzen 5                    | 437       | 6.27%   |
| Intel Core i3                  | 415       | 5.96%   |
| AMD Ryzen 7                    | 400       | 5.74%   |
| Intel Celeron                  | 169       | 2.43%   |
| Intel Core 2 Duo               | 115       | 1.65%   |
| Intel Atom                     | 109       | 1.56%   |
| AMD Ryzen 9                    | 101       | 1.45%   |
| AMD Ryzen 7 PRO                | 95        | 1.36%   |
| Intel Pentium                  | 79        | 1.13%   |
| AMD Ryzen 3                    | 62        | 0.89%   |
| Intel Core i9                  | 59        | 0.85%   |
| AMD Ryzen 5 PRO                | 51        | 0.73%   |
| AMD A6                         | 40        | 0.57%   |
| AMD A10                        | 35        | 0.5%    |
| AMD A8                         | 29        | 0.42%   |
| Intel Pentium Silver           | 28        | 0.4%    |
| AMD A4                         | 21        | 0.3%    |
| Intel Xeon                     | 17        | 0.24%   |
| Intel Pentium Dual-Core        | 15        | 0.22%   |
| AMD E1                         | 11        | 0.16%   |
| AMD A12                        | 11        | 0.16%   |
| Intel Pentium Dual             | 10        | 0.14%   |
| AMD Athlon                     | 10        | 0.14%   |
| Intel Core m5                  | 9         | 0.13%   |
| Intel Core m3                  | 9         | 0.13%   |
| AMD E                          | 8         | 0.11%   |
| Intel Genuine                  | 7         | 0.1%    |
| Intel Core M                   | 6         | 0.09%   |
| Intel Core m7                  | 5         | 0.07%   |
| AMD PRO A10                    | 4         | 0.06%   |
| AMD Phenom II                  | 4         | 0.06%   |
| AMD E2                         | 4         | 0.06%   |
| AMD Athlon II                  | 4         | 0.06%   |
| Intel Core 2                   | 3         | 0.04%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.04%   |
| AMD FX                         | 3         | 0.04%   |
| Intel Celeron Dual-Core        | 2         | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 2810      | 40.33%  |
| 2       | 2518      | 36.14%  |
| 6       | 703       | 10.09%  |
| 8       | 683       | 9.8%    |
| 12      | 86        | 1.23%   |
| 14      | 78        | 1.12%   |
| 10      | 56        | 0.8%    |
| 1       | 21        | 0.3%    |
| 16      | 7         | 0.1%    |
| 24      | 2         | 0.03%   |
| 3       | 2         | 0.03%   |
| 5       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 6964      | 99.97%  |
| 2       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 6124      | 87.8%   |
| 1       | 850       | 12.19%  |
| Unknown | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6827      | 97.72%  |
| Unknown        | 151       | 2.16%   |
| 64-bit         | 4         | 0.06%   |
| 32-bit         | 4         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1288      | 17.94%  |
| 0x806ec    | 398       | 5.54%   |
| 0x806ea    | 382       | 5.32%   |
| 0x306a9    | 356       | 4.96%   |
| 0x806c1    | 349       | 4.86%   |
| 0x206a7    | 278       | 3.87%   |
| 0x906ea    | 272       | 3.79%   |
| 0x406e3    | 272       | 3.79%   |
| 0x806e9    | 269       | 3.75%   |
| 0x40651    | 220       | 3.06%   |
| 0x306d4    | 215       | 2.99%   |
| 0x0a50000c | 210       | 2.93%   |
| 0x306c3    | 168       | 2.34%   |
| 0xa0652    | 164       | 2.28%   |
| 0x08600106 | 136       | 1.89%   |
| 0x08108109 | 126       | 1.76%   |
| 0x08108102 | 119       | 1.66%   |
| 0x906e9    | 118       | 1.64%   |
| 0x506e3    | 111       | 1.55%   |
| 0x706e5    | 104       | 1.45%   |
| 0x08608103 | 100       | 1.39%   |
| 0x906a3    | 88        | 1.23%   |
| 0x20655    | 81        | 1.13%   |
| 0x08600104 | 79        | 1.1%    |
| 0x806eb    | 75        | 1.04%   |
| 0x30678    | 75        | 1.04%   |
| 0x1067a    | 70        | 0.98%   |
| 0x806d1    | 61        | 0.85%   |
| 0x906ed    | 56        | 0.78%   |
| 0x0a404102 | 55        | 0.77%   |
| 0x08600103 | 52        | 0.72%   |
| 0x406c4    | 42        | 0.59%   |
| 0x0810100b | 41        | 0.57%   |
| 0x0a50000d | 37        | 0.52%   |
| 0x0a404101 | 35        | 0.49%   |
| 0x706a8    | 34        | 0.47%   |
| 0x08608102 | 33        | 0.46%   |
| 0x406c3    | 30        | 0.42%   |
| 0x906a4    | 29        | 0.4%    |
| 0x506c9    | 28        | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1870      | 26.83%  |
| Haswell          | 490       | 7.03%   |
| TigerLake        | 485       | 6.96%   |
| Skylake          | 457       | 6.56%   |
| IvyBridge        | 424       | 6.08%   |
| SandyBridge      | 326       | 4.68%   |
| Zen 2            | 313       | 4.49%   |
| Zen 3            | 274       | 3.93%   |
| Unknown          | 269       | 3.86%   |
| Zen+             | 254       | 3.64%   |
| Broadwell        | 246       | 3.53%   |
| CometLake        | 225       | 3.23%   |
| Alderlake Hybrid | 221       | 3.17%   |
| IceLake          | 209       | 3%      |
| Silvermont       | 192       | 2.75%   |
| Westmere         | 134       | 1.92%   |
| Penryn           | 116       | 1.66%   |
| Goldmont plus    | 77        | 1.1%    |
| Zen              | 76        | 1.09%   |
| Excavator        | 65        | 0.93%   |
| Core             | 36        | 0.52%   |
| Goldmont         | 35        | 0.5%    |
| Puma             | 33        | 0.47%   |
| Piledriver       | 33        | 0.47%   |
| Nehalem          | 19        | 0.27%   |
| Jaguar           | 19        | 0.27%   |
| Bobcat           | 15        | 0.22%   |
| Tremont          | 13        | 0.19%   |
| K10              | 11        | 0.16%   |
| K10 Llano        | 9         | 0.13%   |
| Steamroller      | 7         | 0.1%    |
| K8 & K10 hybrid  | 5         | 0.07%   |
| Bonnell          | 5         | 0.07%   |
| K8 Hammer        | 4         | 0.06%   |
| P6               | 3         | 0.04%   |
| NetBurst         | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5275      | 57.57%  |
| Nvidia                           | 2200      | 24.01%  |
| AMD                              | 1686      | 18.4%   |
| Zhaoxin                          | 1         | 0.01%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 444       | 4.76%   |
| Intel UHD Graphics 620                                                                   | 435       | 4.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 393       | 4.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 331       | 3.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 306       | 3.28%   |
| Intel HD Graphics 620                                                                    | 304       | 3.26%   |
| AMD Renoir                                                                               | 304       | 3.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 289       | 3.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 283       | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 257       | 2.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 256       | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 255       | 2.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 221       | 2.37%   |
| Intel HD Graphics 5500                                                                   | 210       | 2.25%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 189       | 2.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 186       | 1.99%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 144       | 1.54%   |
| AMD Lucienne                                                                             | 141       | 1.51%   |
| Intel HD Graphics 630                                                                    | 126       | 1.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 116       | 1.24%   |
| Intel HD Graphics 530                                                                    | 109       | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 105       | 1.13%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 104       | 1.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 101       | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 93        | 1%      |
| AMD Rembrandt [Radeon 680M]                                                              | 93        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 90        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 87        | 0.93%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 87        | 0.93%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 84        | 0.9%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 76        | 0.81%   |
| Nvidia GP108M [GeForce MX150]                                                            | 72        | 0.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 70        | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 69        | 0.74%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 61        | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 60        | 0.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 56        | 0.6%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 50        | 0.54%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 49        | 0.53%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 49        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 3322      | 47.5%   |
| Intel + Nvidia     | 1682      | 24.05%  |
| 1 x AMD            | 1059      | 15.14%  |
| 1 x Nvidia         | 276       | 3.95%   |
| Intel + AMD        | 261       | 3.73%   |
| AMD + Nvidia       | 245       | 3.5%    |
| 2 x AMD            | 123       | 1.76%   |
| Other              | 10        | 0.14%   |
| 2 x Intel          | 8         | 0.11%   |
| 2 x Nvidia         | 3         | 0.04%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| 1 x Zhaoxin        | 1         | 0.01%   |
| 1 x SiS            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5972      | 84.67%  |
| Proprietary | 972       | 13.78%  |
| Unknown     | 109       | 1.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4346      | 61.12%  |
| 1.01-2.0   | 922       | 12.97%  |
| 0.01-0.5   | 744       | 10.46%  |
| 3.01-4.0   | 476       | 6.69%   |
| 0.51-1.0   | 381       | 5.36%   |
| 5.01-6.0   | 105       | 1.48%   |
| 7.01-8.0   | 86        | 1.21%   |
| 8.01-16.0  | 26        | 0.37%   |
| 2.01-3.0   | 25        | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1468      | 17.15%  |
| BOE                     | 1288      | 15.05%  |
| Chimei Innolux          | 1160      | 13.55%  |
| LG Display              | 1102      | 12.88%  |
| Samsung Electronics     | 667       | 7.79%   |
| Dell                    | 403       | 4.71%   |
| Sharp                   | 361       | 4.22%   |
| Goldstar                | 255       | 2.98%   |
| Apple                   | 190       | 2.22%   |
| Lenovo                  | 177       | 2.07%   |
| PANDA                   | 160       | 1.87%   |
| Hewlett-Packard         | 138       | 1.61%   |
| CSO                     | 103       | 1.2%    |
| BenQ                    | 91        | 1.06%   |
| Chi Mei Optoelectronics | 90        | 1.05%   |
| AOC                     | 88        | 1.03%   |
| Acer                    | 88        | 1.03%   |
| Philips                 | 86        | 1%      |
| InfoVision              | 77        | 0.9%    |
| Ancor Communications    | 64        | 0.75%   |
| Iiyama                  | 41        | 0.48%   |
| TMX                     | 37        | 0.43%   |
| ViewSonic               | 36        | 0.42%   |
| ASUSTek Computer        | 36        | 0.42%   |
| Panasonic               | 21        | 0.25%   |
| Sony                    | 19        | 0.22%   |
| JDI                     | 19        | 0.22%   |
| Toshiba                 | 17        | 0.2%    |
| LG Philips              | 16        | 0.19%   |
| MSI                     | 14        | 0.16%   |
| Sceptre Tech            | 11        | 0.13%   |
| CPT                     | 11        | 0.13%   |
| NEC Computers           | 9         | 0.11%   |
| HannStar                | 9         | 0.11%   |
| Gigabyte Technology     | 9         | 0.11%   |
| Vizio                   | 8         | 0.09%   |
| Fujitsu Siemens         | 8         | 0.09%   |
| Eizo                    | 8         | 0.09%   |
| Vestel Elektronik       | 7         | 0.08%   |
| RTK                     | 7         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 72        | 0.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 61        | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 54        | 0.62%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 52        | 0.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 51        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 50        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 41        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 40        | 0.46%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 39        | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 38        | 0.44%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch       | 38        | 0.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 38        | 0.44%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 36        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 35        | 0.4%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 32        | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 31        | 0.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 30        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 28        | 0.32%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 27        | 0.31%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 27        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 25        | 0.29%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 25        | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 24        | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 24        | 0.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 24        | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 24        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 24        | 0.28%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 24        | 0.28%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch       | 24        | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 23        | 0.26%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 23        | 0.26%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 23        | 0.26%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 23        | 0.26%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 23        | 0.26%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 22        | 0.25%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 22        | 0.25%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 22        | 0.25%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 22        | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 22        | 0.25%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 22        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3980      | 50.75%  |
| 1366x768 (WXGA)    | 1514      | 19.3%   |
| 3840x2160 (4K)     | 458       | 5.84%   |
| 2560x1440 (QHD)    | 338       | 4.31%   |
| 1600x900 (HD+)     | 264       | 3.37%   |
| 1920x1200 (WUXGA)  | 233       | 2.97%   |
| 2560x1600          | 158       | 2.01%   |
| 1280x800 (WXGA)    | 125       | 1.59%   |
| 2880x1800          | 103       | 1.31%   |
| 2560x1080          | 74        | 0.94%   |
| 3440x1440          | 73        | 0.93%   |
| 1440x900 (WXGA+)   | 72        | 0.92%   |
| 3840x2400          | 56        | 0.71%   |
| 2160x1440          | 48        | 0.61%   |
| 1680x1050 (WSXGA+) | 48        | 0.61%   |
| 1280x1024 (SXGA)   | 40        | 0.51%   |
| 2256x1504          | 38        | 0.48%   |
| 3200x1800 (QHD+)   | 36        | 0.46%   |
| 3000x2000          | 19        | 0.24%   |
| 1360x768           | 17        | 0.22%   |
| 3200x2000          | 14        | 0.18%   |
| 2520x1680          | 13        | 0.17%   |
| 2240x1400          | 12        | 0.15%   |
| 3456x2160          | 11        | 0.14%   |
| 3072x1920          | 10        | 0.13%   |
| 2160x1350          | 10        | 0.13%   |
| 3840x1600          | 8         | 0.1%    |
| 1920x1280          | 8         | 0.1%    |
| 3840x1080          | 7         | 0.09%   |
| 1024x768 (XGA)     | 6         | 0.08%   |
| 1920x540           | 5         | 0.06%   |
| 1024x600           | 5         | 0.06%   |
| 3840x1100          | 4         | 0.05%   |
| 2880x1620          | 4         | 0.05%   |
| 1680x945           | 3         | 0.04%   |
| Unknown            | 3         | 0.04%   |
| 800x1280           | 2         | 0.03%   |
| 2880x1920          | 2         | 0.03%   |
| 2736x1824          | 2         | 0.03%   |
| 2304x1440          | 2         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3167      | 36.98%  |
| 13      | 1382      | 16.14%  |
| 14      | 1199      | 14%     |
| 17      | 416       | 4.86%   |
| 27      | 395       | 4.61%   |
| 24      | 395       | 4.61%   |
| 23      | 267       | 3.12%   |
| 12      | 225       | 2.63%   |
| 21      | 211       | 2.46%   |
| 16      | 149       | 1.74%   |
| 34      | 127       | 1.48%   |
| 31      | 88        | 1.03%   |
| 11      | 77        | 0.9%    |
| 18      | 76        | 0.89%   |
| 19      | 43        | 0.5%    |
| 20      | 37        | 0.43%   |
| 22      | 31        | 0.36%   |
| Unknown | 26        | 0.3%    |
| 25      | 25        | 0.29%   |
| 40      | 24        | 0.28%   |
| 84      | 23        | 0.27%   |
| 26      | 18        | 0.21%   |
| 32      | 17        | 0.2%    |
| 35      | 14        | 0.16%   |
| 28      | 14        | 0.16%   |
| 10      | 14        | 0.16%   |
| 54      | 13        | 0.15%   |
| 29      | 13        | 0.15%   |
| 72      | 10        | 0.12%   |
| 37      | 9         | 0.11%   |
| 48      | 7         | 0.08%   |
| 42      | 5         | 0.06%   |
| 39      | 5         | 0.06%   |
| 74      | 4         | 0.05%   |
| 33      | 4         | 0.05%   |
| 63      | 3         | 0.04%   |
| 57      | 3         | 0.04%   |
| 52      | 3         | 0.04%   |
| 46      | 3         | 0.04%   |
| 36      | 3         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 5144      | 60.74%  |
| 501-600        | 990       | 11.69%  |
| 201-300        | 976       | 11.52%  |
| 351-400        | 511       | 6.03%   |
| 401-500        | 374       | 4.42%   |
| 701-800        | 151       | 1.78%   |
| 601-700        | 151       | 1.78%   |
| 801-900        | 54        | 0.64%   |
| 1001-1500      | 41        | 0.48%   |
| 1501-2000      | 39        | 0.46%   |
| Unknown        | 26        | 0.31%   |
| 901-1000       | 8         | 0.09%   |
| 1-100          | 2         | 0.02%   |
| More than 2000 | 1         | 0.01%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 5973      | 82.43%  |
| 16/10   | 880       | 12.14%  |
| 21/9    | 157       | 2.17%   |
| 3/2     | 143       | 1.97%   |
| 5/4     | 37        | 0.51%   |
| 4/3     | 18        | 0.25%   |
| Unknown | 12        | 0.17%   |
| 32/9    | 11        | 0.15%   |
| 3.40    | 4         | 0.06%   |
| 6/5     | 2         | 0.03%   |
| 0.67    | 2         | 0.03%   |
| 3.88    | 1         | 0.01%   |
| 3.73    | 1         | 0.01%   |
| 3.33    | 1         | 0.01%   |
| 1.00    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3166      | 37.06%  |
| 81-90          | 2063      | 24.15%  |
| 201-250        | 713       | 8.35%   |
| 71-80          | 501       | 5.86%   |
| 301-350        | 414       | 4.85%   |
| 121-130        | 373       | 4.37%   |
| 351-500        | 265       | 3.1%    |
| 61-70          | 216       | 2.53%   |
| 251-300        | 155       | 1.81%   |
| 111-120        | 146       | 1.71%   |
| 151-200        | 135       | 1.58%   |
| 51-60          | 81        | 0.95%   |
| 141-150        | 80        | 0.94%   |
| More than 1000 | 69        | 0.81%   |
| 501-1000       | 63        | 0.74%   |
| 131-140        | 36        | 0.42%   |
| Unknown        | 26        | 0.3%    |
| 91-100         | 24        | 0.28%   |
| 41-50          | 14        | 0.16%   |
| 1-40           | 4         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3772      | 45.2%   |
| 101-120       | 1847      | 22.13%  |
| 51-100        | 1298      | 15.55%  |
| 161-240       | 906       | 10.86%  |
| More than 240 | 444       | 5.32%   |
| 1-50          | 52        | 0.62%   |
| Unknown       | 26        | 0.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 5268      | 72.99%  |
| 2     | 1558      | 21.59%  |
| 3     | 207       | 2.87%   |
| 0     | 166       | 2.3%    |
| 4     | 15        | 0.21%   |
| 5     | 3         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 4213      | 39.91%  |
| Realtek Semiconductor             | 3477      | 32.94%  |
| Qualcomm Atheros                  | 1147      | 10.86%  |
| Broadcom                          | 467       | 4.42%   |
| MediaTek                          | 251       | 2.38%   |
| Broadcom Limited                  | 105       | 0.99%   |
| Lenovo                            | 101       | 0.96%   |
| ASIX Electronics                  | 75        | 0.71%   |
| TP-Link                           | 66        | 0.63%   |
| Sierra Wireless                   | 66        | 0.63%   |
| Qualcomm                          | 52        | 0.49%   |
| DisplayLink                       | 46        | 0.44%   |
| Dell                              | 46        | 0.44%   |
| Ralink                            | 44        | 0.42%   |
| Marvell Technology Group          | 36        | 0.34%   |
| Ralink Technology                 | 32        | 0.3%    |
| Samsung Electronics               | 31        | 0.29%   |
| Ericsson Business Mobile Networks | 31        | 0.29%   |
| Hewlett-Packard                   | 29        | 0.27%   |
| Xiaomi                            | 23        | 0.22%   |
| Nvidia                            | 22        | 0.21%   |
| Huawei Technologies               | 18        | 0.17%   |
| ASUSTek Computer                  | 15        | 0.14%   |
| Apple                             | 15        | 0.14%   |
| Google                            | 11        | 0.1%    |
| Fibocom                           | 11        | 0.1%    |
| OPPO Electronics                  | 10        | 0.09%   |
| JMicron Technology                | 10        | 0.09%   |
| Qualcomm Atheros Communications   | 9         | 0.09%   |
| NetGear                           | 9         | 0.09%   |
| D-Link                            | 7         | 0.07%   |
| T & A Mobile Phones               | 6         | 0.06%   |
| Microsoft                         | 6         | 0.06%   |
| Linksys                           | 6         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.05%   |
| Edimax Technology                 | 5         | 0.05%   |
| D-Link System                     | 5         | 0.05%   |
| Motorola PCS                      | 4         | 0.04%   |
| Cypress Semiconductor             | 4         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2172      | 16.88%  |
| Intel Wi-Fi 6 AX200                                               | 494       | 3.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 439       | 3.41%   |
| Intel Wireless 8265 / 8275                                        | 439       | 3.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 393       | 3.05%   |
| Intel Wi-Fi 6 AX201                                               | 375       | 2.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 282       | 2.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 255       | 1.98%   |
| Intel Wireless 8260                                               | 250       | 1.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 243       | 1.89%   |
| Intel Wireless 7260                                               | 229       | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 223       | 1.73%   |
| Intel Wireless 7265                                               | 218       | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 211       | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 191       | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 182       | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 181       | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 179       | 1.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 173       | 1.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 172       | 1.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 166       | 1.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 162       | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 150       | 1.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 145       | 1.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 114       | 0.89%   |
| Intel Wireless 3165                                               | 111       | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 111       | 0.86%   |
| Intel Wireless-AC 9260                                            | 96        | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 95        | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 92        | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 92        | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 86        | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 82        | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 80        | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 79        | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 79        | 0.61%   |
| Broadcom BCM43142 802.11b/g/n                                     | 76        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                    | 74        | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 73        | 0.57%   |
| Intel Wireless 3160                                               | 70        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4102      | 57.23%  |
| Qualcomm Atheros                      | 1007      | 14.05%  |
| Realtek Semiconductor                 | 986       | 13.76%  |
| Broadcom                              | 389       | 5.43%   |
| MediaTek                              | 244       | 3.4%    |
| Broadcom Limited                      | 82        | 1.14%   |
| Sierra Wireless                       | 66        | 0.92%   |
| TP-Link                               | 47        | 0.66%   |
| Ralink                                | 44        | 0.61%   |
| Qualcomm                              | 40        | 0.56%   |
| Dell                                  | 34        | 0.47%   |
| Ralink Technology                     | 32        | 0.45%   |
| ASUSTek Computer                      | 14        | 0.2%    |
| Fibocom                               | 11        | 0.15%   |
| Qualcomm Atheros Communications       | 9         | 0.13%   |
| Hewlett-Packard                       | 9         | 0.13%   |
| Ericsson Business Mobile Networks     | 9         | 0.13%   |
| NetGear                               | 8         | 0.11%   |
| Linksys                               | 5         | 0.07%   |
| Edimax Technology                     | 5         | 0.07%   |
| D-Link System                         | 5         | 0.07%   |
| Microsoft                             | 4         | 0.06%   |
| D-Link                                | 4         | 0.06%   |
| Quectel Wireless Solutions            | 2         | 0.03%   |
| Belkin Components                     | 2         | 0.03%   |
| ZyDAS                                 | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |
| Sitecom Europe                        | 1         | 0.01%   |
| Qualcomm Technologies                 | 1         | 0.01%   |
| IMC Networks                          | 1         | 0.01%   |
| AVM                                   | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 494       | 6.85%   |
| Intel Wireless 8265 / 8275                                     | 439       | 6.09%   |
| Intel Wi-Fi 6 AX201                                            | 375       | 5.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 282       | 3.91%   |
| Intel Wireless 8260                                            | 250       | 3.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 243       | 3.37%   |
| Intel Wireless 7260                                            | 229       | 3.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 223       | 3.09%   |
| Intel Wireless 7265                                            | 218       | 3.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 211       | 2.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 191       | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 182       | 2.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 181       | 2.51%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 179       | 2.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 173       | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 172       | 2.39%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 162       | 2.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 150       | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 145       | 2.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 114       | 1.58%   |
| Intel Wireless 3165                                            | 111       | 1.54%   |
| Intel Wireless-AC 9260                                         | 96        | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 92        | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 92        | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 86        | 1.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 80        | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 79        | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 79        | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                  | 76        | 1.05%   |
| Intel Centrino Ultimate-N 6300                                 | 74        | 1.03%   |
| Intel Wireless 3160                                            | 70        | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 69        | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 55        | 0.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 51        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 51        | 0.71%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 47        | 0.65%   |
| Intel Centrino Advanced-N 6235                                 | 47        | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 43        | 0.6%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 41        | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 38        | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3069      | 55.97%  |
| Intel                                  | 1541      | 28.11%  |
| Qualcomm Atheros                       | 238       | 4.34%   |
| Broadcom                               | 149       | 2.72%   |
| Lenovo                                 | 99        | 1.81%   |
| ASIX Electronics                       | 75        | 1.37%   |
| DisplayLink                            | 46        | 0.84%   |
| Marvell Technology Group               | 36        | 0.66%   |
| Samsung Electronics                    | 24        | 0.44%   |
| Xiaomi                                 | 23        | 0.42%   |
| Broadcom Limited                       | 23        | 0.42%   |
| Nvidia                                 | 22        | 0.4%    |
| TP-Link                                | 21        | 0.38%   |
| Apple                                  | 15        | 0.27%   |
| Qualcomm                               | 12        | 0.22%   |
| Huawei Technologies                    | 11        | 0.2%    |
| Google                                 | 11        | 0.2%    |
| OPPO Electronics                       | 10        | 0.18%   |
| JMicron Technology                     | 10        | 0.18%   |
| MediaTek                               | 7         | 0.13%   |
| Hewlett-Packard                        | 7         | 0.13%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.07%   |
| Cypress Semiconductor                  | 4         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 3         | 0.05%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| D-Link                                 | 3         | 0.05%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.04%   |
| Microsoft                              | 2         | 0.04%   |
| ICS Advent                             | 2         | 0.04%   |
| vivo                                   | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| Linksys                                | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| HMD Global                             | 1         | 0.02%   |
| ASUSTek Computer                       | 1         | 0.02%   |
| Aquantia                               | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2172      | 38.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 439       | 7.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 393       | 7.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 255       | 4.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 166       | 2.98%   |
| Intel Ethernet Connection I219-LM                                 | 111       | 1.99%   |
| Intel Ethernet Connection (4) I219-V                              | 95        | 1.7%    |
| Intel Ethernet Connection I218-LM                                 | 82        | 1.47%   |
| Intel Ethernet Connection (6) I219-V                              | 73        | 1.31%   |
| Intel Ethernet Connection I217-LM                                 | 70        | 1.26%   |
| Intel Ethernet Connection (3) I218-LM                             | 69        | 1.24%   |
| ASIX AX88179 Gigabit Ethernet                                     | 69        | 1.24%   |
| Intel Ethernet Connection (7) I219-LM                             | 60        | 1.08%   |
| Intel Ethernet Connection (6) I219-LM                             | 58        | 1.04%   |
| Intel Ethernet Connection (10) I219-V                             | 58        | 1.04%   |
| Intel 82577LM Gigabit Network Connection                          | 47        | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 43        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 43        | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 41        | 0.74%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 40        | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 39        | 0.7%    |
| Intel Ethernet Connection I219-V                                  | 39        | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 36        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 0.61%   |
| Intel Ethernet Connection (13) I219-V                             | 34        | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 32        | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 29        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 29        | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 25        | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 24        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.43%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 24        | 0.43%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.43%   |
| Intel Ethernet Connection (16) I219-V                             | 23        | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.36%   |
| Intel Ethernet Connection (10) I219-LM                            | 20        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 19        | 0.34%   |
| Nvidia MCP79 Ethernet                                             | 19        | 0.34%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.34%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 18        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6835      | 56.58%  |
| Ethernet | 5158      | 42.7%   |
| Modem    | 77        | 0.64%   |
| Unknown  | 11        | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5925      | 79.81%  |
| Ethernet | 1497      | 20.16%  |
| Modem    | 2         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4600      | 65.98%  |
| 1     | 2153      | 30.88%  |
| 0     | 137       | 1.97%   |
| 3     | 82        | 1.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 5702      | 80.23%  |
| Yes     | 1402      | 19.73%  |
| Unknown | 3         | 0.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3414      | 57.53%  |
| Realtek Semiconductor           | 591       | 9.96%   |
| Qualcomm Atheros Communications | 509       | 8.58%   |
| IMC Networks                    | 255       | 4.3%    |
| Broadcom                        | 237       | 3.99%   |
| Foxconn / Hon Hai               | 233       | 3.93%   |
| Lite-On Technology              | 209       | 3.52%   |
| Apple                           | 162       | 2.73%   |
| Realtek                         | 70        | 1.18%   |
| Dell                            | 45        | 0.76%   |
| Cambridge Silicon Radio         | 42        | 0.71%   |
| Hewlett-Packard                 | 32        | 0.54%   |
| Ralink                          | 30        | 0.51%   |
| Toshiba                         | 24        | 0.4%    |
| ASUSTek Computer                | 17        | 0.29%   |
| USI                             | 12        | 0.2%    |
| Foxconn International           | 12        | 0.2%    |
| Opticis                         | 9         | 0.15%   |
| MediaTek                        | 8         | 0.13%   |
| Ralink Technology               | 4         | 0.07%   |
| Smart Modular Technologies      | 3         | 0.05%   |
| Chicony Electronics             | 3         | 0.05%   |
| Alps Electric                   | 3         | 0.05%   |
| Taiyo Yuden                     | 2         | 0.03%   |
| Qcom                            | 2         | 0.03%   |
| Askey Computer                  | 2         | 0.03%   |
| TP-Link                         | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1209      | 20.36%  |
| Intel AX201 Bluetooth                               | 733       | 12.34%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 531       | 8.94%   |
| Intel AX200 Bluetooth                               | 483       | 8.13%   |
| Realtek Bluetooth Radio                             | 372       | 6.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 298       | 5.02%   |
| Realtek  Bluetooth 4.2 Adapter                      | 136       | 2.29%   |
| Intel Bluetooth Device                              | 125       | 2.1%    |
| Intel AX210 Bluetooth                               | 111       | 1.87%   |
| Apple Bluetooth Host Controller                     | 110       | 1.85%   |
| IMC Networks Wireless_Device                        | 99        | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 84        | 1.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 83        | 1.4%    |
| IMC Networks Bluetooth Radio                        | 80        | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 75        | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 74        | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 73        | 1.23%   |
| Realtek 802.11ac WLAN Adapter                       | 65        | 1.09%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 63        | 1.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 53        | 0.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 50        | 0.84%   |
| Lite-On Bluetooth Device                            | 49        | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 47        | 0.79%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 42        | 0.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 42        | 0.71%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 40        | 0.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 0.66%   |
| Apple Bluetooth USB Host Controller                 | 39        | 0.66%   |
| IMC Networks Bluetooth Device                       | 35        | 0.59%   |
| Foxconn / Hon Hai Wireless_Device                   | 32        | 0.54%   |
| Ralink RT3290 Bluetooth                             | 30        | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 26        | 0.44%   |
| Lite-On Wireless_Device                             | 25        | 0.42%   |
| Realtek RTL8723B Bluetooth                          | 23        | 0.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 23        | 0.39%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 23        | 0.39%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 0.39%   |
| Dell DW375 Bluetooth Module                         | 20        | 0.34%   |
| Dell BCM20702A0 Bluetooth Module                    | 19        | 0.32%   |
| Broadcom HP Portable SoftSailing                    | 17        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 5452      | 60.7%   |
| AMD                         | 1452      | 16.17%  |
| Nvidia                      | 1206      | 13.43%  |
| Lenovo                      | 118       | 1.31%   |
| Realtek Semiconductor       | 86        | 0.96%   |
| C-Media Electronics         | 86        | 0.96%   |
| GN Netcom                   | 66        | 0.73%   |
| Logitech                    | 64        | 0.71%   |
| Plantronics                 | 39        | 0.43%   |
| Hewlett-Packard             | 30        | 0.33%   |
| JMTek                       | 28        | 0.31%   |
| Kingston Technology         | 20        | 0.22%   |
| Texas Instruments           | 19        | 0.21%   |
| Creative Technology         | 16        | 0.18%   |
| SteelSeries ApS             | 15        | 0.17%   |
| Razer USA                   | 14        | 0.16%   |
| Sony                        | 13        | 0.14%   |
| Corsair                     | 13        | 0.14%   |
| Apple                       | 11        | 0.12%   |
| Sennheiser Communications   | 10        | 0.11%   |
| Generalplus Technology      | 10        | 0.11%   |
| Dell                        | 10        | 0.11%   |
| Blue Microphones            | 10        | 0.11%   |
| ASUSTek Computer            | 10        | 0.11%   |
| Samson Technologies         | 9         | 0.1%    |
| RODE Microphones            | 8         | 0.09%   |
| Microsoft                   | 8         | 0.09%   |
| Conexant Systems            | 8         | 0.09%   |
| No brand                    | 7         | 0.08%   |
| XMOS                        | 6         | 0.07%   |
| Samsung Electronics         | 6         | 0.07%   |
| CMX Systems                 | 6         | 0.07%   |
| Scarlett                    | 5         | 0.06%   |
| SAVITECH                    | 5         | 0.06%   |
| Tenx Technology             | 4         | 0.04%   |
| PreSonus Audio Electronics  | 4         | 0.04%   |
| M-Audio                     | 4         | 0.04%   |
| GYROCOM C&C                 | 4         | 0.04%   |
| Focusrite-Novation          | 4         | 0.04%   |
| FiiO Electronics Technology | 4         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1115      | 10.19%  |
| Intel Sunrise Point-LP HD Audio                                            | 1091      | 9.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 620       | 5.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 484       | 4.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 468       | 4.28%   |
| Intel Cannon Lake PCH cAVS                                                 | 378       | 3.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 314       | 2.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 303       | 2.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 282       | 2.58%   |
| Intel Comet Lake PCH-LP cAVS                                               | 276       | 2.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 261       | 2.39%   |
| Intel 8 Series HD Audio Controller                                         | 261       | 2.39%   |
| Intel Broadwell-U Audio Controller                                         | 246       | 2.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 243       | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 228       | 2.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 208       | 1.9%    |
| Intel Comet Lake PCH cAVS                                                  | 204       | 1.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 186       | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 180       | 1.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 152       | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 147       | 1.34%   |
| Intel CM238 HD Audio Controller                                            | 147       | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 131       | 1.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 129       | 1.18%   |
| AMD FCH Azalia Controller                                                  | 109       | 1%      |
| Nvidia GA106 High Definition Audio Controller                              | 103       | 0.94%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 93        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 90        | 0.82%   |
| AMD Kabini HDMI/DP Audio                                                   | 86        | 0.79%   |
| Realtek Semiconductor USB Audio                                            | 85        | 0.78%   |
| Nvidia Audio device                                                        | 80        | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 80        | 0.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 79        | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 77        | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 72        | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                         | 66        | 0.6%    |
| Nvidia TU116 High Definition Audio Controller                              | 62        | 0.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 62        | 0.57%   |
| Nvidia GA104 High Definition Audio Controller                              | 60        | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 51        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1290      | 29.74%  |
| SK hynix            | 976       | 22.5%   |
| Micron Technology   | 626       | 14.43%  |
| Kingston            | 354       | 8.16%   |
| Crucial             | 247       | 5.69%   |
| Unknown             | 222       | 5.12%   |
| Ramaxel Technology  | 104       | 2.4%    |
| A-DATA Technology   | 99        | 2.28%   |
| Corsair             | 61        | 1.41%   |
| Elpida              | 39        | 0.9%    |
| Smart               | 31        | 0.71%   |
| Unknown (ABCD)      | 27        | 0.62%   |
| G.Skill             | 27        | 0.62%   |
| Team                | 24        | 0.55%   |
| Nanya Technology    | 22        | 0.51%   |
| Unknown             | 22        | 0.51%   |
| Patriot             | 19        | 0.44%   |
| Teikon              | 16        | 0.37%   |
| Smart Brazil        | 12        | 0.28%   |
| GOODRAM             | 11        | 0.25%   |
| Transcend           | 10        | 0.23%   |
| Avant               | 9         | 0.21%   |
| Silicon Power       | 5         | 0.12%   |
| Goldkey             | 5         | 0.12%   |
| Timetec             | 4         | 0.09%   |
| PUSKILL             | 4         | 0.09%   |
| CSX                 | 4         | 0.09%   |
| Apacer              | 4         | 0.09%   |
| V-GeN               | 3         | 0.07%   |
| OnBoard             | 3         | 0.07%   |
| Kllisre             | 3         | 0.07%   |
| ChangXin Memory     | 3         | 0.07%   |
| 4ea5                | 3         | 0.07%   |
| SHARETRONIC         | 2         | 0.05%   |
| Sesame              | 2         | 0.05%   |
| RZX                 | 2         | 0.05%   |
| Qumo                | 2         | 0.05%   |
| Qimonda             | 2         | 0.05%   |
| PNY                 | 2         | 0.05%   |
| Memox               | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 79        | 1.73%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 74        | 1.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 63        | 1.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 57        | 1.25%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 41        | 0.9%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 40        | 0.88%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 40        | 0.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 37        | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 35        | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 35        | 0.77%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 34        | 0.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 33        | 0.72%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 31        | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 30        | 0.66%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 30        | 0.66%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 29        | 0.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 29        | 0.64%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 28        | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 28        | 0.61%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 27        | 0.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 27        | 0.59%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 27        | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 26        | 0.57%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 26        | 0.57%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 26        | 0.57%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 26        | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 25        | 0.55%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 25        | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 24        | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 24        | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.5%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 23        | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 23        | 0.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.48%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 22        | 0.48%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 22        | 0.48%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 22        | 0.48%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 22        | 0.48%   |
| Unknown                                                          | 22        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 2096      | 58.09%  |
| DDR3    | 908       | 25.17%  |
| LPDDR4  | 199       | 5.52%   |
| LPDDR3  | 196       | 5.43%   |
| LPDDR5  | 69        | 1.91%   |
| DDR5    | 59        | 1.64%   |
| DDR2    | 44        | 1.22%   |
| SDRAM   | 19        | 0.53%   |
| Unknown | 14        | 0.39%   |
| DDR     | 3         | 0.08%   |
| DRAM    | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3077      | 83.64%  |
| Row Of Chips | 512       | 13.92%  |
| Chip         | 49        | 1.33%   |
| Unknown      | 22        | 0.6%    |
| DIMM         | 19        | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1728      | 43.81%  |
| 4096  | 991       | 25.13%  |
| 16384 | 741       | 18.79%  |
| 2048  | 289       | 7.33%   |
| 32768 | 142       | 3.6%    |
| 1024  | 48        | 1.22%   |
| 3072  | 2         | 0.05%   |
| 12288 | 1         | 0.03%   |
| 512   | 1         | 0.03%   |
| 64    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 931       | 23.95%  |
| 3200    | 929       | 23.89%  |
| 1600    | 657       | 16.9%   |
| 2400    | 287       | 7.38%   |
| 2133    | 260       | 6.69%   |
| 1333    | 113       | 2.91%   |
| 1334    | 107       | 2.75%   |
| 4267    | 100       | 2.57%   |
| 1867    | 80        | 2.06%   |
| 6400    | 69        | 1.77%   |
| 4800    | 61        | 1.57%   |
| 3266    | 57        | 1.47%   |
| 1067    | 40        | 1.03%   |
| Unknown | 30        | 0.77%   |
| 8400    | 28        | 0.72%   |
| 667     | 27        | 0.69%   |
| 4266    | 25        | 0.64%   |
| 1066    | 17        | 0.44%   |
| 4199    | 15        | 0.39%   |
| 3733    | 15        | 0.39%   |
| 800     | 14        | 0.36%   |
| 5600    | 4         | 0.1%    |
| 975     | 4         | 0.1%    |
| 2933    | 2         | 0.05%   |
| 2048    | 2         | 0.05%   |
| 933     | 2         | 0.05%   |
| 533     | 2         | 0.05%   |
| 5500    | 1         | 0.03%   |
| 3600    | 1         | 0.03%   |
| 3400    | 1         | 0.03%   |
| 2800    | 1         | 0.03%   |
| 1866    | 1         | 0.03%   |
| 1777    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1200    | 1         | 0.03%   |
| 333     | 1         | 0.03%   |
| 133     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 23.08%  |
| Canon               | 8         | 20.51%  |
| Samsung Electronics | 6         | 15.38%  |
| Brother Industries  | 5         | 12.82%  |
| Seiko Epson         | 4         | 10.26%  |
| Prolific Technology | 2         | 5.13%   |
| STMicroelectronics  | 1         | 2.56%   |
| Ricoh               | 1         | 2.56%   |
| Pantum              | 1         | 2.56%   |
| NXP Semiconductors  | 1         | 2.56%   |
| MiiiW               | 1         | 2.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                         | 2         | 5.13%   |
| STMicroelectronics USB Printing Support                               | 1         | 2.56%   |
| Seiko Epson WF-2830 Series                                            | 1         | 2.56%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 2.56%   |
| Seiko Epson L200 Series                                               | 1         | 2.56%   |
| Seiko Epson ET-2710 Series                                            | 1         | 2.56%   |
| Samsung SCX-4200 series                                               | 1         | 2.56%   |
| Samsung SCX-3200 Series                                               | 1         | 2.56%   |
| Samsung ML-331x Series Laser Printer                                  | 1         | 2.56%   |
| Samsung M2070 Series                                                  | 1         | 2.56%   |
| Samsung CLX-6260 Series                                               | 1         | 2.56%   |
| Samsung C43x Series                                                   | 1         | 2.56%   |
| Ricoh SP 210SU                                                        | 1         | 2.56%   |
| Pantum P2500W series                                                  | 1         | 2.56%   |
| NXP Semiconductors Printer-80                                         | 1         | 2.56%   |
| MiiiW MW USB Receiver                                                 | 1         | 2.56%   |
| HP Photosmart B010 series                                             | 1         | 2.56%   |
| HP Officejet 2620 series                                              | 1         | 2.56%   |
| HP LaserJet 400 colorMFP M475dw                                       | 1         | 2.56%   |
| HP ENVY Pro 6400 series                                               | 1         | 2.56%   |
| HP ENVY 4500 series                                                   | 1         | 2.56%   |
| HP Deskjet 3510 series                                                | 1         | 2.56%   |
| HP Deskjet 3050A                                                      | 1         | 2.56%   |
| HP DeskJet 2300 series                                                | 1         | 2.56%   |
| HP DeskJet 2130 series                                                | 1         | 2.56%   |
| Canon TR8500 series                                                   | 1         | 2.56%   |
| Canon TR150 series                                                    | 1         | 2.56%   |
| Canon PIXMA MG3600 Series                                             | 1         | 2.56%   |
| Canon PIXMA MG3500 Series                                             | 1         | 2.56%   |
| Canon PIXMA MG3000 series                                             | 1         | 2.56%   |
| Canon MF3110                                                          | 1         | 2.56%   |
| Canon MF220 Series                                                    | 1         | 2.56%   |
| Canon iP7200 series                                                   | 1         | 2.56%   |
| Brother Printer                                                       | 1         | 2.56%   |
| Brother HL-5250DN Printer                                             | 1         | 2.56%   |
| Brother DCP-T220                                                      | 1         | 2.56%   |
| Brother DCP-7025 Printer                                              | 1         | 2.56%   |
| Brother DCP-1600                                                      | 1         | 2.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 60%     |
| Seiko Epson     | 3         | 30%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20          | 2         | 20%     |
| Canon CanoScan LiDE 220                     | 2         | 20%     |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 10%     |
| Seiko Epson GT-X770 [Perfection V500]       | 1         | 10%     |
| Seiko Epson ES-D400 [GT-S80]                | 1         | 10%     |
| HP Scanjet 300                              | 1         | 10%     |
| Canon CanoScan N650U/N656U                  | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1549      | 23.72%  |
| IMC Networks                           | 803       | 12.3%   |
| Microdia                               | 593       | 9.08%   |
| Realtek Semiconductor                  | 535       | 8.19%   |
| Quanta                                 | 400       | 6.13%   |
| Bison Electronics                      | 388       | 5.94%   |
| Sunplus Innovation Technology          | 343       | 5.25%   |
| Cheng Uei Precision Industry (Foxlink) | 259       | 3.97%   |
| Acer                                   | 240       | 3.68%   |
| Lite-On Technology                     | 182       | 2.79%   |
| Syntek                                 | 180       | 2.76%   |
| Logitech                               | 159       | 2.43%   |
| Apple                                  | 148       | 2.27%   |
| Luxvisions Innotech Limited            | 129       | 1.98%   |
| Suyin                                  | 103       | 1.58%   |
| Silicon Motion                         | 74        | 1.13%   |
| Sonix Technology                       | 49        | 0.75%   |
| Alcor Micro                            | 45        | 0.69%   |
| Samsung Electronics                    | 42        | 0.64%   |
| Ricoh                                  | 38        | 0.58%   |
| Lenovo                                 | 23        | 0.35%   |
| Primax Electronics                     | 22        | 0.34%   |
| SunplusIT                              | 19        | 0.29%   |
| Microsoft                              | 17        | 0.26%   |
| Importek                               | 17        | 0.26%   |
| Z-Star Microelectronics                | 12        | 0.18%   |
| icSpring                               | 9         | 0.14%   |
| Generalplus Technology                 | 9         | 0.14%   |
| Shenzhen Kingcome Optoelectronic       | 8         | 0.12%   |
| ARC International                      | 8         | 0.12%   |
| MacroSilicon                           | 7         | 0.11%   |
| ALi                                    | 7         | 0.11%   |
| KYE Systems (Mouse Systems)            | 6         | 0.09%   |
| Intel                                  | 6         | 0.09%   |
| WaveRider Communications               | 5         | 0.08%   |
| Razer USA                              | 5         | 0.08%   |
| Pixart Imaging                         | 5         | 0.08%   |
| Tobii Technology AB                    | 4         | 0.06%   |
| Y Media                                | 3         | 0.05%   |
| Tripath Technology                     | 3         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 541       | 8.22%   |
| Microdia Integrated_Webcam_HD                                              | 347       | 5.27%   |
| IMC Networks Integrated Camera                                             | 318       | 4.83%   |
| Realtek Integrated_Webcam_HD                                               | 243       | 3.69%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 210       | 3.19%   |
| Sunplus Integrated_Webcam_HD                                               | 145       | 2.2%    |
| Chicony HD WebCam                                                          | 145       | 2.2%    |
| Syntek Integrated Camera                                                   | 122       | 1.85%   |
| Bison Integrated Camera                                                    | 108       | 1.64%   |
| Acer Integrated Camera                                                     | 92        | 1.4%    |
| Chicony Integrated Camera (1280x720@30)                                    | 88        | 1.34%   |
| Quanta HD User Facing                                                      | 86        | 1.31%   |
| Lite-On Integrated Camera                                                  | 85        | 1.29%   |
| Bison SunplusIT Integrated Camera                                          | 66        | 1%      |
| Chicony HP HD Camera                                                       | 65        | 0.99%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 60        | 0.91%   |
| Quanta HP TrueVision HD Camera                                             | 55        | 0.84%   |
| IMC Networks HD Camera                                                     | 53        | 0.8%    |
| Chicony USB2.0 Camera                                                      | 48        | 0.73%   |
| Quanta HP HD Camera                                                        | 45        | 0.68%   |
| Quanta HD Webcam                                                           | 45        | 0.68%   |
| Chicony HP TrueVision HD Camera                                            | 45        | 0.68%   |
| Realtek USB Camera                                                         | 44        | 0.67%   |
| Microdia Integrated Webcam                                                 | 44        | 0.67%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 43        | 0.65%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 42        | 0.64%   |
| Lite-On HP HD Camera                                                       | 40        | 0.61%   |
| Chicony Integrated IR Camera                                               | 40        | 0.61%   |
| Chicony HP Wide Vision HD Camera                                           | 40        | 0.61%   |
| Apple FaceTime HD Camera                                                   | 40        | 0.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 38        | 0.58%   |
| Logitech HD Pro Webcam C920                                                | 38        | 0.58%   |
| Sunplus HD WebCam                                                          | 36        | 0.55%   |
| Realtek Integrated Webcam                                                  | 36        | 0.55%   |
| Quanta HP Wide Vision HD Camera                                            | 36        | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 36        | 0.55%   |
| Apple Built-in iSight                                                      | 36        | 0.55%   |
| Bison Lenovo EasyCamera                                                    | 35        | 0.53%   |
| Chicony HD User Facing                                                     | 34        | 0.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 33        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 591       | 35.18%  |
| Validity Sensors                   | 500       | 29.76%  |
| Shenzhen Goodix Technology         | 298       | 17.74%  |
| Elan Microelectronics              | 106       | 6.31%   |
| Upek                               | 62        | 3.69%   |
| LighTuning Technology              | 55        | 3.27%   |
| AuthenTec                          | 37        | 2.2%    |
| Realtek USB2.0 Finger Print Bridge | 12        | 0.71%   |
| Samsung Electronics                | 9         | 0.54%   |
| STMicroelectronics                 | 5         | 0.3%    |
| Focal-systems.Corp                 | 4         | 0.24%   |
| Dell                               | 1         | 0.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 283       | 16.84%  |
| Shenzhen Goodix  Fingerprint Device                                        | 188       | 11.18%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 112       | 6.66%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 104       | 6.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 93        | 5.53%   |
| Shenzhen Goodix FingerPrint                                                | 59        | 3.51%   |
| Validity Sensors Synaptics WBDI                                            | 58        | 3.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 58        | 3.45%   |
| Elan ELAN:Fingerprint                                                      | 58        | 3.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 51        | 3.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 48        | 2.86%   |
| Elan ELAN:ARM-M4                                                           | 46        | 2.74%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 42        | 2.5%    |
| Synaptics Fingerprint reader [HP G6]                                       | 38        | 2.26%   |
| Validity Sensors VFS491                                                    | 28        | 1.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 28        | 1.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 28        | 1.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 26        | 1.55%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 22        | 1.31%   |
| Synaptics  WBDI                                                            | 22        | 1.31%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 22        | 1.31%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 21        | 1.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 21        | 1.25%   |
| Synaptics UWP WBDI Device                                                  | 20        | 1.19%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 1.07%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 0.89%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 14        | 0.83%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 0.83%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 0.71%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 12        | 0.71%   |
| Synaptics WBDI                                                             | 10        | 0.59%   |
| Synaptics UWP WBDI                                                         | 10        | 0.59%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 0.48%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 8         | 0.48%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.42%   |
| AuthenTec AES2810                                                          | 7         | 0.42%   |
| Unknown                                                                    | 7         | 0.42%   |
| Synaptics WBDI Device                                                      | 6         | 0.36%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 6         | 0.36%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 262       | 41.52%  |
| Alcor Micro                | 255       | 40.41%  |
| Upek                       | 39        | 6.18%   |
| Lenovo                     | 33        | 5.23%   |
| O2 Micro                   | 14        | 2.22%   |
| Gemalto (was Gemplus)      | 7         | 1.11%   |
| Yubico.com                 | 3         | 0.48%   |
| SCM Microsystems           | 3         | 0.48%   |
| Realtek Semiconductor      | 3         | 0.48%   |
| OmniKey                    | 3         | 0.48%   |
| Aladdin Knowledge Systems  | 3         | 0.48%   |
| Reiner SCT Kartensysteme   | 1         | 0.16%   |
| Purism, SPC                | 1         | 0.16%   |
| Hewlett-Packard            | 1         | 0.16%   |
| Chicony Electronics        | 1         | 0.16%   |
| Athena Smartcard Solutions | 1         | 0.16%   |
| Advanced Card Systems      | 1         | 0.16%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 254       | 40.25%  |
| Broadcom 5880                                                                | 84        | 13.31%  |
| Broadcom 58200                                                               | 74        | 11.73%  |
| Broadcom BCM5880 Secure Applications Processor                               | 58        | 9.19%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 44        | 6.97%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 39        | 6.18%   |
| Lenovo Integrated Smart Card Reader                                          | 32        | 5.07%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 1.74%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 6         | 0.95%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.48%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.48%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.48%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.48%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.32%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.16%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.16%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.16%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.16%   |
| Purism, SPC Librem Key                                                       | 1         | 0.16%   |
| OmniKey CardMan 4321                                                         | 1         | 0.16%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.16%   |
| OmniKey CardMan 1021                                                         | 1         | 0.16%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.16%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.16%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.16%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.16%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.16%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.16%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.16%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 4159      | 57.9%   |
| 1     | 2478      | 34.5%   |
| 2     | 463       | 6.45%   |
| 3     | 57        | 0.79%   |
| 4     | 8         | 0.11%   |
| 5     | 7         | 0.1%    |
| 6     | 5         | 0.07%   |
| 7     | 4         | 0.06%   |
| 8     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1661      | 46.63%  |
| Graphics card            | 697       | 19.57%  |
| Multimedia controller    | 350       | 9.83%   |
| Net/wireless             | 250       | 7.02%   |
| Chipcard                 | 206       | 5.78%   |
| Camera                   | 130       | 3.65%   |
| Bluetooth                | 75        | 2.11%   |
| Storage                  | 51        | 1.43%   |
| Card reader              | 49        | 1.38%   |
| Sound                    | 28        | 0.79%   |
| Net/ethernet             | 18        | 0.51%   |
| Communication controller | 17        | 0.48%   |
| Network                  | 16        | 0.45%   |
| Modem                    | 9         | 0.25%   |
| Flash memory             | 2         | 0.06%   |
| Video                    | 1         | 0.03%   |
| Firewire controller      | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

