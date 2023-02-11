Linux in Australia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

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

Total: 1982

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X220 4286CTO       | [465114aa14](https://linux-hardware.org/?probe=465114aa14) | Feb 01, 2023 |
| Acer          | Predator PH315-52           | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| ASUSTek       | X550LC                      | [4c50999862](https://linux-hardware.org/?probe=4c50999862) | Jan 30, 2023 |
| ASUSTek       | X550LC                      | [41d606bbe8](https://linux-hardware.org/?probe=41d606bbe8) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| Apple         | MacBook8,1                  | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | [b7759508d9](https://linux-hardware.org/?probe=b7759508d9) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | [72f2c3fddc](https://linux-hardware.org/?probe=72f2c3fddc) | Jan 26, 2023 |
| Panasonic     | FZ55-2                      | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [26abf66da5](https://linux-hardware.org/?probe=26abf66da5) | Jan 25, 2023 |
| Acer          | Aspire A315-22              | [7c048a8058](https://linux-hardware.org/?probe=7c048a8058) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Alienware     | 15 R4                       | [8833335118](https://linux-hardware.org/?probe=8833335118) | Jan 23, 2023 |
| Dell          | XPS 13 9350                 | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2JV01    | [932148f478](https://linux-hardware.org/?probe=932148f478) | Jan 21, 2023 |
| Dell          | XPS 9315                    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| Dell          | Latitude 5300               | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Apple         | MacBookAir7,2               | [ead0a07135](https://linux-hardware.org/?probe=ead0a07135) | Jan 20, 2023 |
| Apple         | MacBookAir5,2               | [03e73c44b7](https://linux-hardware.org/?probe=03e73c44b7) | Jan 20, 2023 |
| Apple         | MacBookPro14,3              | [82a49878eb](https://linux-hardware.org/?probe=82a49878eb) | Jan 19, 2023 |
| Dell          | XPS 15 7590                 | [9a7659a260](https://linux-hardware.org/?probe=9a7659a260) | Jan 18, 2023 |
| Dell          | Precision 3561              | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [a80f36a4eb](https://linux-hardware.org/?probe=a80f36a4eb) | Jan 16, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [f0b2886993](https://linux-hardware.org/?probe=f0b2886993) | Jan 15, 2023 |
| Acer          | Aspire R3-131T              | [268413b274](https://linux-hardware.org/?probe=268413b274) | Jan 15, 2023 |
| Valve         | Jupiter                     | [8830efc64d](https://linux-hardware.org/?probe=8830efc64d) | Jan 15, 2023 |
| HP            | Laptop 14s-dk0xxx           | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | V14-IIL 82C4                | [3837db6f8a](https://linux-hardware.org/?probe=3837db6f8a) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Dell          | Latitude 5300               | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| Dell          | Inspiron 5770               | [7435d85aca](https://linux-hardware.org/?probe=7435d85aca) | Jan 12, 2023 |
| Dell          | XPS 17 9700                 | [09f6a754d6](https://linux-hardware.org/?probe=09f6a754d6) | Jan 12, 2023 |
| Acer          | Swift SF514-54T             | [98a18475e8](https://linux-hardware.org/?probe=98a18475e8) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Dell          | Inspiron 3543               | [c7c7419fd5](https://linux-hardware.org/?probe=c7c7419fd5) | Jan 10, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [17dc10d7bb](https://linux-hardware.org/?probe=17dc10d7bb) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430s 2356AF9      | [eca34fb600](https://linux-hardware.org/?probe=eca34fb600) | Jan 09, 2023 |
| Dell          | XPS 13 9333                 | [f291c4d057](https://linux-hardware.org/?probe=f291c4d057) | Jan 09, 2023 |
| HP            | EliteBook Folio 9470m       | [1c4f7f2f2a](https://linux-hardware.org/?probe=1c4f7f2f2a) | Jan 09, 2023 |
| Dell          | Latitude 7280               | [931dcfb8be](https://linux-hardware.org/?probe=931dcfb8be) | Jan 08, 2023 |
| Dell          | Latitude E7450              | [635ef7be4a](https://linux-hardware.org/?probe=635ef7be4a) | Jan 08, 2023 |
| Lenovo        | ThinkPad W530 2463B87       | [5ac9828d4c](https://linux-hardware.org/?probe=5ac9828d4c) | Jan 08, 2023 |
| Acer          | Predator G9-793             | [5256ec6943](https://linux-hardware.org/?probe=5256ec6943) | Jan 07, 2023 |
| Apple         | MacBookPro12,1              | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [263354b92e](https://linux-hardware.org/?probe=263354b92e) | Jan 06, 2023 |
| Dell          | Precision M4700             | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [99bf8fff2f](https://linux-hardware.org/?probe=99bf8fff2f) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [d9fa2355b0](https://linux-hardware.org/?probe=d9fa2355b0) | Jan 05, 2023 |
| HP            | Laptop 15s-fq1xxx           | [488e1f656c](https://linux-hardware.org/?probe=488e1f656c) | Jan 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | [d0ac402ed9](https://linux-hardware.org/?probe=d0ac402ed9) | Jan 03, 2023 |
| HP            | Pavilion                    | [466e855af1](https://linux-hardware.org/?probe=466e855af1) | Jan 03, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| HP            | EliteBook 2760p             | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [cf40d3f30c](https://linux-hardware.org/?probe=cf40d3f30c) | Dec 31, 2022 |
| Apple         | MacBookAir7,2               | [8b84042dc6](https://linux-hardware.org/?probe=8b84042dc6) | Dec 30, 2022 |
| Apple         | MacBookAir7,2               | [dae09ec15f](https://linux-hardware.org/?probe=dae09ec15f) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| AMI           | F3C2                        | [ed7d4a2a13](https://linux-hardware.org/?probe=ed7d4a2a13) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| Acer          | Aspire 5742G                | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30-C               | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Raider GE77HX 12UGS         | [9f7185ccd7](https://linux-hardware.org/?probe=9f7185ccd7) | Dec 27, 2022 |
| MSI           | GP62M 7REX                  | [f49c90b8dc](https://linux-hardware.org/?probe=f49c90b8dc) | Dec 25, 2022 |
| Dell          | Latitude E6520              | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| Toshiba       | Satellite C50D-C            | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | [4732443b9e](https://linux-hardware.org/?probe=4732443b9e) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | [354b048898](https://linux-hardware.org/?probe=354b048898) | Dec 21, 2022 |
| HP            | Pavilion dv6                | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [1fec8c22dc](https://linux-hardware.org/?probe=1fec8c22dc) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [b0a4a9919c](https://linux-hardware.org/?probe=b0a4a9919c) | Dec 18, 2022 |
| ASUSTek       | X550LD                      | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Apple         | MacBookPro14,2              | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Apple         | MacBookAir7,2               | [b1386d66d5](https://linux-hardware.org/?probe=b1386d66d5) | Dec 13, 2022 |
| Kogan         | KAL11C250SB                 | [e7ad1c21ad](https://linux-hardware.org/?probe=e7ad1c21ad) | Dec 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [265ba7b252](https://linux-hardware.org/?probe=265ba7b252) | Dec 13, 2022 |
| Dell          | XPS L521X                   | [c69c906797](https://linux-hardware.org/?probe=c69c906797) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| Acer          | Aspire A515-45              | [26f5bfeb45](https://linux-hardware.org/?probe=26f5bfeb45) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Dell          | G15 5511                    | [999ed53283](https://linux-hardware.org/?probe=999ed53283) | Dec 05, 2022 |
| Apple         | MacBookPro15,1              | [36732e2602](https://linux-hardware.org/?probe=36732e2602) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fb96bd56ad](https://linux-hardware.org/?probe=fb96bd56ad) | Dec 04, 2022 |
| Unknown       | Unknown                     | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| Unknown       | Unknown                     | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Acer          | ConceptD CN315-71P          | [370356b4a8](https://linux-hardware.org/?probe=370356b4a8) | Dec 02, 2022 |
| Acer          | ConceptD CN315-71P          | [bbdfc25e56](https://linux-hardware.org/?probe=bbdfc25e56) | Dec 02, 2022 |
| Intel Clie... | LAPBC510                    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [ca1fab4db1](https://linux-hardware.org/?probe=ca1fab4db1) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [2adab1a5b2](https://linux-hardware.org/?probe=2adab1a5b2) | Dec 02, 2022 |
| AMI           | Intel                       | [3e2e312c6e](https://linux-hardware.org/?probe=3e2e312c6e) | Nov 29, 2022 |
| Razer         | Blade                       | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3433fd5db6](https://linux-hardware.org/?probe=3433fd5db6) | Nov 28, 2022 |
| Apple         | MacBookAir6,2               | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Latitude E7440              | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| Apple         | MacBookPro15,2              | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| Kogan         | KAL11C250SB                 | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| Razer         | Blade Pro                   | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Acer          | Aspire R3-131T              | [5395a2556c](https://linux-hardware.org/?probe=5395a2556c) | Nov 24, 2022 |
| Acer          | ConceptD CN315-71P          | [db3ccac179](https://linux-hardware.org/?probe=db3ccac179) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [62c77a0e63](https://linux-hardware.org/?probe=62c77a0e63) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [06c02ff303](https://linux-hardware.org/?probe=06c02ff303) | Nov 21, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [06a337fda3](https://linux-hardware.org/?probe=06a337fda3) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [965d9d2f5c](https://linux-hardware.org/?probe=965d9d2f5c) | Nov 20, 2022 |
| MSI           | GP62M 7REX                  | [2125546b68](https://linux-hardware.org/?probe=2125546b68) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | [6ea684de8c](https://linux-hardware.org/?probe=6ea684de8c) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| AMI           | Intel                       | [ac36a02403](https://linux-hardware.org/?probe=ac36a02403) | Nov 16, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [ccbda507a9](https://linux-hardware.org/?probe=ccbda507a9) | Nov 14, 2022 |
| ASUSTek       | X550CC                      | [d37b8f7bbd](https://linux-hardware.org/?probe=d37b8f7bbd) | Nov 13, 2022 |
| Acer          | ConceptD CN315-71P          | [2d3a3f4ac8](https://linux-hardware.org/?probe=2d3a3f4ac8) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Pavilion Notebook           | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| MSI           | GS60 6QE                    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Toshiba       | TECRA A40-D                 | [ab2d9e2712](https://linux-hardware.org/?probe=ab2d9e2712) | Nov 11, 2022 |
| Acer          | Aspire A315-22              | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| HP            | ProBook 640 G1              | [3189f08179](https://linux-hardware.org/?probe=3189f08179) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| Dell          | XPS 13 9310                 | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| MSI           | GS60 6QE                    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| ASUSTek       | K53E                        | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| Dell          | Latitude E6430              | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Toshiba       | Satellite L500              | [0d6bb9cde0](https://linux-hardware.org/?probe=0d6bb9cde0) | Nov 05, 2022 |
| Toshiba       | Satellite L500              | [3d7692d178](https://linux-hardware.org/?probe=3d7692d178) | Nov 05, 2022 |
| MSI           | Katana GF76 12UC            | [3cb05bdb95](https://linux-hardware.org/?probe=3cb05bdb95) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [cc28dc5c8b](https://linux-hardware.org/?probe=cc28dc5c8b) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| ASUSTek       | 1005HA                      | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Cube          | i18-BL                      | [725100a829](https://linux-hardware.org/?probe=725100a829) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| HP            | Notebook                    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Acer          | Aspire 3000                 | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| ASUSTek       | X501A                       | [d5a34df414](https://linux-hardware.org/?probe=d5a34df414) | Nov 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [c3ea4065c4](https://linux-hardware.org/?probe=c3ea4065c4) | Oct 29, 2022 |
| ASUSTek       | U50Vg                       | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | ProBook 640 G1              | [b096155d39](https://linux-hardware.org/?probe=b096155d39) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | G71                         | [3223e2fcc8](https://linux-hardware.org/?probe=3223e2fcc8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| Apple         | MacBookAir7,2               | [6f72d6443c](https://linux-hardware.org/?probe=6f72d6443c) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Notebook      | W650EH                      | [6bb1a8b1f1](https://linux-hardware.org/?probe=6bb1a8b1f1) | Oct 23, 2022 |
| Purism        | Librem 13 v2                | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire 5600                 | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5086e64fed](https://linux-hardware.org/?probe=5086e64fed) | Oct 19, 2022 |
| Dell          | Inspiron M5010              | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| HP            | G71                         | [46b6033e1e](https://linux-hardware.org/?probe=46b6033e1e) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Dell          | Inspiron 1545               | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| System76      | Galago Pro                  | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5f0c4b3acb](https://linux-hardware.org/?probe=5f0c4b3acb) | Oct 13, 2022 |
| Apple         | MacBookPro15,2              | [705e4f406a](https://linux-hardware.org/?probe=705e4f406a) | Oct 13, 2022 |
| HP            | EliteBook 8540p             | [cd65876f22](https://linux-hardware.org/?probe=cd65876f22) | Oct 12, 2022 |
| Apple         | MacBookPro15,2              | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Dell          | Inspiron 16 5620            | [72151cd0e8](https://linux-hardware.org/?probe=72151cd0e8) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| HP            | ProBook 470 G5              | [a7b96649da](https://linux-hardware.org/?probe=a7b96649da) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| Apple         | MacBookAir7,2               | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| HP            | Presario V4000 (EQ608PA#... | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Dell          | XPS 15 9510                 | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Gigabyte      | AORUS 7 SB                  | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| Acer          | TravelMate 8572T            | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |
| Dell          | Inspiron 15 7510            | [521636075a](https://linux-hardware.org/?probe=521636075a) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Acer          | TravelMate 8572T            | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Gigabyte      | AORUS 17 YE5                | [54b271c3fd](https://linux-hardware.org/?probe=54b271c3fd) | Sep 30, 2022 |
| Acer          | Aspire 5742G                | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [ac3079df8c](https://linux-hardware.org/?probe=ac3079df8c) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [144cad649c](https://linux-hardware.org/?probe=144cad649c) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| Dell          | Latitude E7450              | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Gigabyte      | P34V7                       | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| System76      | Galago Pro                  | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| Dell          | G15 5511                    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| HP            | Pavilion dv6                | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Acer          | TMP645-M                    | [83b27c389c](https://linux-hardware.org/?probe=83b27c389c) | Sep 23, 2022 |
| Dell          | Precision 7760              | [f47fe0314b](https://linux-hardware.org/?probe=f47fe0314b) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [a01352810a](https://linux-hardware.org/?probe=a01352810a) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Apple         | MacBookPro8,1               | [d97b8fc0ed](https://linux-hardware.org/?probe=d97b8fc0ed) | Sep 21, 2022 |
| Apple         | MacBookPro10,2              | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| ASUSTek       | 1005HA                      | [3b5d6a5b1d](https://linux-hardware.org/?probe=3b5d6a5b1d) | Sep 18, 2022 |
| ASUSTek       | 1005HA                      | [3b1ce0471e](https://linux-hardware.org/?probe=3b1ce0471e) | Sep 18, 2022 |
| Lenovo        | V310-15ISK 80SY             | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Acer          | Aspire A315-42              | [6121dfd67d](https://linux-hardware.org/?probe=6121dfd67d) | Sep 13, 2022 |
| HP            | ENVY 15                     | [fdb07294df](https://linux-hardware.org/?probe=fdb07294df) | Sep 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Dell          | Latitude E7470              | [4a2f647549](https://linux-hardware.org/?probe=4a2f647549) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| HP            | Pavilion dv6500             | [c37bace401](https://linux-hardware.org/?probe=c37bace401) | Sep 05, 2022 |
| Dell          | XPS 13 9350                 | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Lenovo        | Z50-70 20354                | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| HP            | Notebook                    | [ee135c3930](https://linux-hardware.org/?probe=ee135c3930) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| HP            | EliteBook 830 G6            | [897046248f](https://linux-hardware.org/?probe=897046248f) | Aug 30, 2022 |
| Lenovo        | V14-ADA 82C6                | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| IT Channel... | NH5xAx                      | [66573b4b48](https://linux-hardware.org/?probe=66573b4b48) | Aug 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Acer          | Aspire V5-531               | [75b841b0b8](https://linux-hardware.org/?probe=75b841b0b8) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Dell          | Latitude 5300               | [f336b3aeaf](https://linux-hardware.org/?probe=f336b3aeaf) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Acer          | Aspire V5-531               | [4ae228e219](https://linux-hardware.org/?probe=4ae228e219) | Aug 25, 2022 |
| Dell          | XPS 13 7390                 | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Alienware     | 15 R4                       | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Apple         | MacBook9,1                  | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Samsung       | 550P5C/550P7C               | [75f94f8fa5](https://linux-hardware.org/?probe=75f94f8fa5) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | [c369daf6b0](https://linux-hardware.org/?probe=c369daf6b0) | Aug 21, 2022 |
| ASUSTek       | X756UAK                     | [6db3b2a7bc](https://linux-hardware.org/?probe=6db3b2a7bc) | Aug 20, 2022 |
| Dell          | G3 3779                     | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Dell          | Inspiron M5010              | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Apple         | MacBookAir6,2               | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Toshiba       | Satellite L500              | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [662f0801b7](https://linux-hardware.org/?probe=662f0801b7) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Dell          | Latitude 6430U              | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| HP            | ProBook 430 G5              | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [209cd4bc66](https://linux-hardware.org/?probe=209cd4bc66) | Aug 05, 2022 |
| Acer          | Nitro AN515-52              | [8b737740c3](https://linux-hardware.org/?probe=8b737740c3) | Aug 05, 2022 |
| Acer          | Aspire A515-55              | [3ef0714d78](https://linux-hardware.org/?probe=3ef0714d78) | Aug 04, 2022 |
| Toshiba       | Satellite Pro L670          | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| Dell          | XPS 9320                    | [9b24b29553](https://linux-hardware.org/?probe=9b24b29553) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | EliteBook 2570p             | [b352b7e051](https://linux-hardware.org/?probe=b352b7e051) | Aug 02, 2022 |
| Apple         | MacBook9,1                  | [77687a9bac](https://linux-hardware.org/?probe=77687a9bac) | Aug 02, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Acer          | ConceptD CN315-71P          | [c7ed484a1f](https://linux-hardware.org/?probe=c7ed484a1f) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire 5742G                | [e42501aacb](https://linux-hardware.org/?probe=e42501aacb) | Jul 28, 2022 |
| ASUSTek       | X555YA                      | [ddd00fbeea](https://linux-hardware.org/?probe=ddd00fbeea) | Jul 28, 2022 |
| Dell          | Latitude E7250              | [26a8591f1d](https://linux-hardware.org/?probe=26a8591f1d) | Jul 27, 2022 |
| HP            | Laptop 17-cp0xxx            | [761563e485](https://linux-hardware.org/?probe=761563e485) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3400               | [3412e8deac](https://linux-hardware.org/?probe=3412e8deac) | Jul 26, 2022 |
| Lenovo        | G570 4334                   | [e4c223e83e](https://linux-hardware.org/?probe=e4c223e83e) | Jul 25, 2022 |
| Apple         | MacBookAir6,1               | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| Acer          | Nitro AN515-55              | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Acer          | ConceptD CN315-71P          | [2723b19c18](https://linux-hardware.org/?probe=2723b19c18) | Jul 22, 2022 |
| Google        | Peppy                       | [3bfdae8e5e](https://linux-hardware.org/?probe=3bfdae8e5e) | Jul 21, 2022 |
| Acer          | Aspire One 753              | [eff74923d7](https://linux-hardware.org/?probe=eff74923d7) | Jul 21, 2022 |
| Dell          | Latitude 5430               | [f02c4072c1](https://linux-hardware.org/?probe=f02c4072c1) | Jul 21, 2022 |
| Acer          | Aspire R3-131T              | [c3722806fe](https://linux-hardware.org/?probe=c3722806fe) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| Dell          | Inspiron 1545               | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Acer          | TravelMate 8572T            | [54e7b50fc7](https://linux-hardware.org/?probe=54e7b50fc7) | Jul 18, 2022 |
| Alienware     | x17 R1                      | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [5fd8a1dcf4](https://linux-hardware.org/?probe=5fd8a1dcf4) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [de83d4ef43](https://linux-hardware.org/?probe=de83d4ef43) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [01e6c30eff](https://linux-hardware.org/?probe=01e6c30eff) | Jul 15, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [73be4f7864](https://linux-hardware.org/?probe=73be4f7864) | Jul 14, 2022 |
| Acer          | Nitro AN515-56              | [2418745195](https://linux-hardware.org/?probe=2418745195) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Dell          | XPS 13 9360                 | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | [4126a95603](https://linux-hardware.org/?probe=4126a95603) | Jul 13, 2022 |
| Apple         | MacBook9,1                  | [0ce6078768](https://linux-hardware.org/?probe=0ce6078768) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| Acer          | Aspire 1830T                | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| HP            | EliteBook 8470p             | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| Apple         | MacBookPro9,2               | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| Acer          | Aspire R3-131T              | [749a597089](https://linux-hardware.org/?probe=749a597089) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| HP            | EliteBook 850 G1            | [1a2485b399](https://linux-hardware.org/?probe=1a2485b399) | Jul 06, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ce6d3ec137](https://linux-hardware.org/?probe=ce6d3ec137) | Jul 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [e24a6dd845](https://linux-hardware.org/?probe=e24a6dd845) | Jul 05, 2022 |
| HP            | EliteBook 840 G6            | [d6dccd6ed7](https://linux-hardware.org/?probe=d6dccd6ed7) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| HP            | Pavilion g6                 | [0cd693879d](https://linux-hardware.org/?probe=0cd693879d) | Jul 05, 2022 |
| Acer          | ConceptD CN315-71P          | [76d6073818](https://linux-hardware.org/?probe=76d6073818) | Jul 05, 2022 |
| Dell          | Precision M4700             | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| Acer          | Aspire R3-131T              | [748f42be21](https://linux-hardware.org/?probe=748f42be21) | Jul 05, 2022 |
| Apple         | MacBookPro10,2              | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | [bcc3835be5](https://linux-hardware.org/?probe=bcc3835be5) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | [5f3197f581](https://linux-hardware.org/?probe=5f3197f581) | Jul 03, 2022 |
| Acer          | Swift SF114-34              | [dd9610011c](https://linux-hardware.org/?probe=dd9610011c) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| Dell          | Inspiron M5010              | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| HP            | EliteBook 8470p             | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a423eae14](https://linux-hardware.org/?probe=3a423eae14) | Jun 30, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| AMI           | Intel                       | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| Dell          | Latitude 5430               | [119502eddb](https://linux-hardware.org/?probe=119502eddb) | Jun 29, 2022 |
| Dell          | G3 3500                     | [0df1b9607c](https://linux-hardware.org/?probe=0df1b9607c) | Jun 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | [b947b14fe4](https://linux-hardware.org/?probe=b947b14fe4) | Jun 27, 2022 |
| Alienware     | 14                          | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Apple         | MacBook9,1                  | [e6f1068c91](https://linux-hardware.org/?probe=e6f1068c91) | Jun 24, 2022 |
| HP            | Presario CQ62               | [2f136051c9](https://linux-hardware.org/?probe=2f136051c9) | Jun 24, 2022 |
| HP            | Presario CQ62               | [9beeb6d3c2](https://linux-hardware.org/?probe=9beeb6d3c2) | Jun 23, 2022 |
| Lenovo        | ThinkPad E490s 20NG0002A... | [4cce05dc1c](https://linux-hardware.org/?probe=4cce05dc1c) | Jun 23, 2022 |
| Apple         | MacBook9,1                  | [3656b8227f](https://linux-hardware.org/?probe=3656b8227f) | Jun 23, 2022 |
| Toshiba       | TECRA A40-D                 | [6307594332](https://linux-hardware.org/?probe=6307594332) | Jun 23, 2022 |
| Acer          | Nitro AN515-55              | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| HP            | 250 G6 Notebook PC          | [30d0a46d81](https://linux-hardware.org/?probe=30d0a46d81) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f013ebb91b](https://linux-hardware.org/?probe=f013ebb91b) | Jun 20, 2022 |
| Acer          | Iconia                      | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b3da04a3af](https://linux-hardware.org/?probe=b3da04a3af) | Jun 20, 2022 |
| Framework     | Laptop                      | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Acer          | ConceptD CN315-71P          | [66d09f029f](https://linux-hardware.org/?probe=66d09f029f) | Jun 18, 2022 |
| Dell          | Precision 5540              | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| Acer          | ConceptD CN315-71P          | [9b162f339b](https://linux-hardware.org/?probe=9b162f339b) | Jun 16, 2022 |
| HUAWEI        | KLVD-WXX9                   | [4c97b8cc3a](https://linux-hardware.org/?probe=4c97b8cc3a) | Jun 16, 2022 |
| Alienware     | m15 R7                      | [9775a12e11](https://linux-hardware.org/?probe=9775a12e11) | Jun 16, 2022 |
| Acer          | Nitro AN515-55              | [bb631825e3](https://linux-hardware.org/?probe=bb631825e3) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| MSI           | Modern 15 A5M               | [bd16d5829c](https://linux-hardware.org/?probe=bd16d5829c) | Jun 14, 2022 |
| Apple         | MacBookPro11,1              | [57b90afcda](https://linux-hardware.org/?probe=57b90afcda) | Jun 14, 2022 |
| Dell          | Vostro 1500                 | [748a8a831b](https://linux-hardware.org/?probe=748a8a831b) | Jun 12, 2022 |
| HP            | Compaq 6730b                | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| ASUSTek       | Unknown                     | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| Alienware     | x17 R2                      | [78b867a06e](https://linux-hardware.org/?probe=78b867a06e) | Jun 08, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [75d6b8489b](https://linux-hardware.org/?probe=75d6b8489b) | Jun 08, 2022 |
| Acer          | Aspire R3-131T              | [1dab354de2](https://linux-hardware.org/?probe=1dab354de2) | Jun 07, 2022 |
| Acer          | Nitro AN515-55              | [4ab9f94abe](https://linux-hardware.org/?probe=4ab9f94abe) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2KW1... | [686fcbebd3](https://linux-hardware.org/?probe=686fcbebd3) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [57e7433cc5](https://linux-hardware.org/?probe=57e7433cc5) | Jun 04, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| Apple         | MacBookAir4,2               | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| Dell          | G15 5515                    | [24ddbd70dc](https://linux-hardware.org/?probe=24ddbd70dc) | Jun 02, 2022 |
| HP            | 250 G6 Notebook PC          | [878274dbce](https://linux-hardware.org/?probe=878274dbce) | Jun 02, 2022 |
| Acer          | Aspire A315-58              | [b63e54900e](https://linux-hardware.org/?probe=b63e54900e) | Jun 02, 2022 |
| Dell          | Latitude E6540              | [9cbdc3f892](https://linux-hardware.org/?probe=9cbdc3f892) | Jun 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ae39e96b1a](https://linux-hardware.org/?probe=ae39e96b1a) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Dell          | Inspiron 5770               | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| IT Channel... | PA70Hx                      | [091ad22c2d](https://linux-hardware.org/?probe=091ad22c2d) | May 30, 2022 |
| Apple         | MacBookPro9,1               | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| MSI           | GT70 2OC/2OD                | [43144c3166](https://linux-hardware.org/?probe=43144c3166) | May 28, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [37d87b9245](https://linux-hardware.org/?probe=37d87b9245) | May 27, 2022 |
| Toshiba       | Satellite P850              | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [00baf8a2ff](https://linux-hardware.org/?probe=00baf8a2ff) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [32f7f3aa4b](https://linux-hardware.org/?probe=32f7f3aa4b) | May 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [43a374c1d4](https://linux-hardware.org/?probe=43a374c1d4) | May 23, 2022 |
| Acer          | Nitro AN515-45              | [293712cc51](https://linux-hardware.org/?probe=293712cc51) | May 23, 2022 |
| Apple         | MacBookPro6,1               | [40d33cea3f](https://linux-hardware.org/?probe=40d33cea3f) | May 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1d8684d1f5](https://linux-hardware.org/?probe=1d8684d1f5) | May 23, 2022 |
| Gigabyte      | P34V5                       | [6fa844b91e](https://linux-hardware.org/?probe=6fa844b91e) | May 23, 2022 |
| Gigabyte      | P34V5                       | [3ad8e4b239](https://linux-hardware.org/?probe=3ad8e4b239) | May 23, 2022 |
| Toshiba       | TECRA R850                  | [aa0bfd6c6a](https://linux-hardware.org/?probe=aa0bfd6c6a) | May 22, 2022 |
| Dell          | G3 3500                     | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| Dell          | Inspiron 1545               | [890010e793](https://linux-hardware.org/?probe=890010e793) | May 21, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [5d150789cb](https://linux-hardware.org/?probe=5d150789cb) | May 19, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Dell          | XPS 13 7390                 | [98752f9fb4](https://linux-hardware.org/?probe=98752f9fb4) | May 18, 2022 |
| Acer          | Aspire A515-55              | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Dell          | Latitude E7450              | [26b07c8dfc](https://linux-hardware.org/?probe=26b07c8dfc) | May 18, 2022 |
| Toshiba       | Satellite C850              | [5927aac0b7](https://linux-hardware.org/?probe=5927aac0b7) | May 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d4f9f894b6](https://linux-hardware.org/?probe=d4f9f894b6) | May 16, 2022 |
| Dell          | Inspiron 5570               | [faf97fa9a0](https://linux-hardware.org/?probe=faf97fa9a0) | May 16, 2022 |
| Gigabyte      | A7 K1                       | [9cd1ec32e4](https://linux-hardware.org/?probe=9cd1ec32e4) | May 16, 2022 |
| Dell          | XPS 15 9560                 | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| Toshiba       | Satellite L50-A             | [30a7bebcd3](https://linux-hardware.org/?probe=30a7bebcd3) | May 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [6251446c92](https://linux-hardware.org/?probe=6251446c92) | May 13, 2022 |
| Dell          | Inspiron 15 3515            | [dd8e112250](https://linux-hardware.org/?probe=dd8e112250) | May 12, 2022 |
| HP            | Pavilion g6                 | [5662b515c3](https://linux-hardware.org/?probe=5662b515c3) | May 12, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [a22c347eaf](https://linux-hardware.org/?probe=a22c347eaf) | May 11, 2022 |
| HP            | 250 G6 Notebook PC          | [f2f010a36d](https://linux-hardware.org/?probe=f2f010a36d) | May 11, 2022 |
| Apple         | MacBookPro12,1              | [0d9616886e](https://linux-hardware.org/?probe=0d9616886e) | May 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ce3addb8a4](https://linux-hardware.org/?probe=ce3addb8a4) | May 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [7d146e5dec](https://linux-hardware.org/?probe=7d146e5dec) | May 10, 2022 |
| Apple         | MacBookPro7,1               | [7ff6997105](https://linux-hardware.org/?probe=7ff6997105) | May 08, 2022 |
| Dell          | Studio XPS 1645             | [0d213120b4](https://linux-hardware.org/?probe=0d213120b4) | May 08, 2022 |
| HP            | Compaq Presario CQ60        | [9d27bd494e](https://linux-hardware.org/?probe=9d27bd494e) | May 08, 2022 |
| HP            | Folio 13 - 2000             | [e859aed666](https://linux-hardware.org/?probe=e859aed666) | May 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [3d07e8a45e](https://linux-hardware.org/?probe=3d07e8a45e) | May 05, 2022 |
| Dell          | Studio 1555                 | [c02949a388](https://linux-hardware.org/?probe=c02949a388) | May 05, 2022 |
| Acer          | Aspire A315-34              | [3ed5a6d961](https://linux-hardware.org/?probe=3ed5a6d961) | May 04, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [43dcfa4094](https://linux-hardware.org/?probe=43dcfa4094) | May 03, 2022 |
| Framework     | Laptop                      | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| HP            | 250 G5 Notebook PC          | [0e6717d54b](https://linux-hardware.org/?probe=0e6717d54b) | May 02, 2022 |
| HP            | EliteBook 850 G3            | [ab86c0118b](https://linux-hardware.org/?probe=ab86c0118b) | May 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7206b41211](https://linux-hardware.org/?probe=7206b41211) | May 01, 2022 |
| Lenovo        | Legion Y9000X 2020 81TH     | [c335cbb270](https://linux-hardware.org/?probe=c335cbb270) | May 01, 2022 |
| HUAWEI        | BOM-WXX9                    | [faa7213f5c](https://linux-hardware.org/?probe=faa7213f5c) | Apr 30, 2022 |
| Apple         | MacBookPro8,1               | [8826e1d451](https://linux-hardware.org/?probe=8826e1d451) | Apr 30, 2022 |
| HP            | ZBook 15 G6                 | [f948921cba](https://linux-hardware.org/?probe=f948921cba) | Apr 30, 2022 |
| Dell          | Inspiron 3543               | [6165b0554d](https://linux-hardware.org/?probe=6165b0554d) | Apr 28, 2022 |
| Lenovo        | ThinkPad X250 20CLS52P0F    | [a4d291ccda](https://linux-hardware.org/?probe=a4d291ccda) | Apr 27, 2022 |
| Acer          | Aspire 5750G                | [3a96bf8237](https://linux-hardware.org/?probe=3a96bf8237) | Apr 27, 2022 |
| HP            | ProBook 4710s               | [03d5c4c5b2](https://linux-hardware.org/?probe=03d5c4c5b2) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [981d5e03b3](https://linux-hardware.org/?probe=981d5e03b3) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0b3a1039fb](https://linux-hardware.org/?probe=0b3a1039fb) | Apr 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b1b4ea439d](https://linux-hardware.org/?probe=b1b4ea439d) | Apr 25, 2022 |
| HP            | ProBook 470 G5              | [e0def5bddc](https://linux-hardware.org/?probe=e0def5bddc) | Apr 25, 2022 |
| HUAWEI        | BOM-WXX9                    | [a771d771b2](https://linux-hardware.org/?probe=a771d771b2) | Apr 24, 2022 |
| HUAWEI        | BOM-WXX9                    | [1a195527a4](https://linux-hardware.org/?probe=1a195527a4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [c954cb4ba4](https://linux-hardware.org/?probe=c954cb4ba4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [ab88dc2482](https://linux-hardware.org/?probe=ab88dc2482) | Apr 24, 2022 |
| HP            | EliteBook 2530p             | [bfaeba4483](https://linux-hardware.org/?probe=bfaeba4483) | Apr 22, 2022 |
| Dell          | Latitude 7490               | [2b8d24f8ae](https://linux-hardware.org/?probe=2b8d24f8ae) | Apr 22, 2022 |
| HP            | EliteBook 2530p             | [a68c57ea30](https://linux-hardware.org/?probe=a68c57ea30) | Apr 22, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | [cbb3f353a5](https://linux-hardware.org/?probe=cbb3f353a5) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell          | XPS 13 7390                 | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Timi          | A35S                        | [e7d8adf61f](https://linux-hardware.org/?probe=e7d8adf61f) | Apr 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [4c845dc459](https://linux-hardware.org/?probe=4c845dc459) | Apr 19, 2022 |
| HP            | 250 G5 Notebook PC          | [5cb8325ed4](https://linux-hardware.org/?probe=5cb8325ed4) | Apr 18, 2022 |
| Acer          | Aspire R3-131T              | [48f584f713](https://linux-hardware.org/?probe=48f584f713) | Apr 17, 2022 |
| Apple         | MacBookPro5,4               | [918fef81c3](https://linux-hardware.org/?probe=918fef81c3) | Apr 17, 2022 |
| Dell          | Studio XPS 1645             | [6e722019b4](https://linux-hardware.org/?probe=6e722019b4) | Apr 16, 2022 |
| Dell          | Inspiron 1012               | [4659a757bf](https://linux-hardware.org/?probe=4659a757bf) | Apr 15, 2022 |
| Dell          | Inspiron 1012               | [ebfcf670fc](https://linux-hardware.org/?probe=ebfcf670fc) | Apr 15, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [c43bc1fcba](https://linux-hardware.org/?probe=c43bc1fcba) | Apr 15, 2022 |
| Dell          | Latitude E6530              | [d6f985e2ca](https://linux-hardware.org/?probe=d6f985e2ca) | Apr 15, 2022 |
| Dell          | Latitude E6230              | [19e2fe3c97](https://linux-hardware.org/?probe=19e2fe3c97) | Apr 14, 2022 |
| Dell          | Latitude 5590               | [c306b97fcd](https://linux-hardware.org/?probe=c306b97fcd) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291IU6       | [a4c2a2bff9](https://linux-hardware.org/?probe=a4c2a2bff9) | Apr 14, 2022 |
| Lenovo        | ThinkPad T430 2350BC6       | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| ASUSTek       | X580VD                      | [4c5ccfbe60](https://linux-hardware.org/?probe=4c5ccfbe60) | Apr 12, 2022 |
| Toshiba       | Satellite L50-A             | [9a4f7c7381](https://linux-hardware.org/?probe=9a4f7c7381) | Apr 09, 2022 |
| Toshiba       | Satellite L50-A             | [ce1ec01972](https://linux-hardware.org/?probe=ce1ec01972) | Apr 09, 2022 |
| Apple         | MacBookPro9,2               | [8ae799c372](https://linux-hardware.org/?probe=8ae799c372) | Apr 08, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [c8a1f60191](https://linux-hardware.org/?probe=c8a1f60191) | Apr 05, 2022 |
| HP            | Pavilion g6                 | [a2d8dcb1bf](https://linux-hardware.org/?probe=a2d8dcb1bf) | Apr 05, 2022 |
| Toshiba       | Satellite L50-A             | [b51d99ad47](https://linux-hardware.org/?probe=b51d99ad47) | Apr 04, 2022 |
| Kogan         | KAL11C250SB                 | [ea426eda5e](https://linux-hardware.org/?probe=ea426eda5e) | Apr 03, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6154972f18](https://linux-hardware.org/?probe=6154972f18) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | [94ef2678d5](https://linux-hardware.org/?probe=94ef2678d5) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | [9166f15878](https://linux-hardware.org/?probe=9166f15878) | Apr 03, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Toshiba       | TECRA M11                   | [c81e18c0f3](https://linux-hardware.org/?probe=c81e18c0f3) | Apr 01, 2022 |
| Dell          | Precision 5540              | [d923ae2736](https://linux-hardware.org/?probe=d923ae2736) | Apr 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [39b70e2f99](https://linux-hardware.org/?probe=39b70e2f99) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [339d70da8c](https://linux-hardware.org/?probe=339d70da8c) | Mar 30, 2022 |
| Dell          | Studio 1555                 | [db9f06343c](https://linux-hardware.org/?probe=db9f06343c) | Mar 30, 2022 |
| Toshiba       | Satellite Radius L10W-C     | [fc18e171f3](https://linux-hardware.org/?probe=fc18e171f3) | Mar 29, 2022 |
| HP            | Notebook                    | [c53a6a41a2](https://linux-hardware.org/?probe=c53a6a41a2) | Mar 29, 2022 |
| ASUSTek       | K55VD                       | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| Dell          | Inspiron 1545               | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Apple         | MacBook7,1                  | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| Apple         | MacBookPro10,1              | [a9caf3d428](https://linux-hardware.org/?probe=a9caf3d428) | Mar 25, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [20f2d24112](https://linux-hardware.org/?probe=20f2d24112) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [64718709d1](https://linux-hardware.org/?probe=64718709d1) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [f123e292b9](https://linux-hardware.org/?probe=f123e292b9) | Mar 23, 2022 |
| HP            | ProBook 430 G2              | [57038c6fd7](https://linux-hardware.org/?probe=57038c6fd7) | Mar 21, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [fef247389a](https://linux-hardware.org/?probe=fef247389a) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7dcf73063d](https://linux-hardware.org/?probe=7dcf73063d) | Mar 19, 2022 |
| HP            | ZBook Firefly 14 inch G8... | [207eca584c](https://linux-hardware.org/?probe=207eca584c) | Mar 17, 2022 |
| Toshiba       | TECRA M11                   | [34167a6878](https://linux-hardware.org/?probe=34167a6878) | Mar 17, 2022 |
| Dell          | XPS 17 9710                 | [34da0f3cdb](https://linux-hardware.org/?probe=34da0f3cdb) | Mar 16, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [f1f12206d5](https://linux-hardware.org/?probe=f1f12206d5) | Mar 15, 2022 |
| HP            | Pavilion g6                 | [378424911d](https://linux-hardware.org/?probe=378424911d) | Mar 15, 2022 |
| Dell          | XPS 15 7590                 | [527b0d7066](https://linux-hardware.org/?probe=527b0d7066) | Mar 14, 2022 |
| Toshiba       | Satellite P850              | [0cd9132f27](https://linux-hardware.org/?probe=0cd9132f27) | Mar 14, 2022 |
| Lenovo        | G40-30 80FY                 | [7b54425ba2](https://linux-hardware.org/?probe=7b54425ba2) | Mar 13, 2022 |
| Acer          | Aspire A315-21G             | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| HP            | 250 G5 Notebook PC          | [3e67ab27db](https://linux-hardware.org/?probe=3e67ab27db) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [ab25401c99](https://linux-hardware.org/?probe=ab25401c99) | Mar 12, 2022 |
| Dell          | Latitude E5450              | [3d2d8b93fe](https://linux-hardware.org/?probe=3d2d8b93fe) | Mar 12, 2022 |
| Metabox       | Edge-Pro NS50MU             | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Lenovo        | ThinkPad T480 20L5A07TAU    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [a83a1ffe1a](https://linux-hardware.org/?probe=a83a1ffe1a) | Mar 09, 2022 |
| Apple         | MacBookPro6,1               | [b227e92b83](https://linux-hardware.org/?probe=b227e92b83) | Mar 07, 2022 |
| Apple         | MacBookPro6,1               | [ef72c023ac](https://linux-hardware.org/?probe=ef72c023ac) | Mar 07, 2022 |
| Toshiba       | Satellite Radius L10W-C     | [db90921ddd](https://linux-hardware.org/?probe=db90921ddd) | Mar 07, 2022 |
| HP            | ENVY TS 15                  | [c2305ed449](https://linux-hardware.org/?probe=c2305ed449) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2d5c05af33](https://linux-hardware.org/?probe=2d5c05af33) | Mar 06, 2022 |
| HP            | Notebook                    | [d8b2e4567e](https://linux-hardware.org/?probe=d8b2e4567e) | Mar 05, 2022 |
| HP            | Notebook                    | [cafa2c6f1a](https://linux-hardware.org/?probe=cafa2c6f1a) | Mar 05, 2022 |
| HP            | ProBook 430 G5              | [9b130dbcb5](https://linux-hardware.org/?probe=9b130dbcb5) | Mar 04, 2022 |
| Acer          | Aspire R3-131T              | [98d5649b75](https://linux-hardware.org/?probe=98d5649b75) | Mar 03, 2022 |
| Acer          | Aspire V3-371               | [038cc99ead](https://linux-hardware.org/?probe=038cc99ead) | Mar 02, 2022 |
| Apple         | MacBookPro5,5               | [678e1eb19b](https://linux-hardware.org/?probe=678e1eb19b) | Feb 26, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [f3ec55a392](https://linux-hardware.org/?probe=f3ec55a392) | Feb 25, 2022 |
| HP            | ProBook 450 G1              | [1f26dfd88f](https://linux-hardware.org/?probe=1f26dfd88f) | Feb 22, 2022 |
| HP            | ProBook 430 G5              | [b9cb7cad60](https://linux-hardware.org/?probe=b9cb7cad60) | Feb 22, 2022 |
| HP            | ZBook 15 G6                 | [c5079e020e](https://linux-hardware.org/?probe=c5079e020e) | Feb 21, 2022 |
| Dell          | Precision 3561              | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [8a6f28fc9d](https://linux-hardware.org/?probe=8a6f28fc9d) | Feb 21, 2022 |
| Toshiba       | Satellite Pro C850          | [132557a51b](https://linux-hardware.org/?probe=132557a51b) | Feb 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [fb981fe5b0](https://linux-hardware.org/?probe=fb981fe5b0) | Feb 20, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [f08a9db4fb](https://linux-hardware.org/?probe=f08a9db4fb) | Feb 20, 2022 |
| HP            | Notebook                    | [1e57c317b4](https://linux-hardware.org/?probe=1e57c317b4) | Feb 19, 2022 |
| HP            | Notebook                    | [583b61ead6](https://linux-hardware.org/?probe=583b61ead6) | Feb 19, 2022 |
| IT Channel... | P95xER                      | [c8add471fb](https://linux-hardware.org/?probe=c8add471fb) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [f7e1ab4276](https://linux-hardware.org/?probe=f7e1ab4276) | Feb 18, 2022 |
| HP            | ProBook 470 G2              | [0ef953e74d](https://linux-hardware.org/?probe=0ef953e74d) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [8791991562](https://linux-hardware.org/?probe=8791991562) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | [983c62bf72](https://linux-hardware.org/?probe=983c62bf72) | Feb 17, 2022 |
| Apple         | MacBookPro16,1              | [3e35c49d6c](https://linux-hardware.org/?probe=3e35c49d6c) | Feb 16, 2022 |
| Dell          | Inspiron 7591               | [f5cc709342](https://linux-hardware.org/?probe=f5cc709342) | Feb 16, 2022 |
| Toshiba       | Satellite C50-A             | [e88fd90806](https://linux-hardware.org/?probe=e88fd90806) | Feb 15, 2022 |
| HP            | ProBook 450 G6              | [e54664c1be](https://linux-hardware.org/?probe=e54664c1be) | Feb 15, 2022 |
| Dell          | System Vostro 3750          | [4a5289bfbe](https://linux-hardware.org/?probe=4a5289bfbe) | Feb 14, 2022 |
| Toshiba       | QOSMIO X70-A                | [c3c921f8e2](https://linux-hardware.org/?probe=c3c921f8e2) | Feb 14, 2022 |
| Lenovo        | ThinkPad T420 4178A47       | [cda9da09dc](https://linux-hardware.org/?probe=cda9da09dc) | Feb 14, 2022 |
| ASUSTek       | UX330UAK                    | [8731a73bfa](https://linux-hardware.org/?probe=8731a73bfa) | Feb 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Toshiba       | Satellite C50-A283          | [66f810c5f5](https://linux-hardware.org/?probe=66f810c5f5) | Feb 13, 2022 |
| Kogan         | KAL11C250SB                 | [600104b8e2](https://linux-hardware.org/?probe=600104b8e2) | Feb 12, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | [9ce361abd3](https://linux-hardware.org/?probe=9ce361abd3) | Feb 12, 2022 |
| Samsung       | 700T                        | [076ad3b906](https://linux-hardware.org/?probe=076ad3b906) | Feb 11, 2022 |
| Acer          | Aspire 5600                 | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| HP            | Compaq CQ45                 | [3c75fd14fb](https://linux-hardware.org/?probe=3c75fd14fb) | Feb 09, 2022 |
| HP            | Pavilion dv6                | [efb945cc4f](https://linux-hardware.org/?probe=efb945cc4f) | Feb 09, 2022 |
| ASUSTek       | G74Sx                       | [d0f48fef55](https://linux-hardware.org/?probe=d0f48fef55) | Feb 08, 2022 |
| Samsung       | R580                        | [f822930ecf](https://linux-hardware.org/?probe=f822930ecf) | Feb 08, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [1110112a7f](https://linux-hardware.org/?probe=1110112a7f) | Feb 06, 2022 |
| Star Labs     | StarBook                    | [e53bcff920](https://linux-hardware.org/?probe=e53bcff920) | Feb 06, 2022 |
| Unknown       | Unknown                     | [7848918b1d](https://linux-hardware.org/?probe=7848918b1d) | Feb 05, 2022 |
| Acer          | Aspire A515-43              | [6bc39a1855](https://linux-hardware.org/?probe=6bc39a1855) | Feb 04, 2022 |
| Lenovo        | ThinkPad Mini10 3507A31     | [f49f0801c0](https://linux-hardware.org/?probe=f49f0801c0) | Feb 03, 2022 |
| Acer          | Aspire 5741                 | [175d1e66d3](https://linux-hardware.org/?probe=175d1e66d3) | Feb 02, 2022 |
| Toshiba       | Satellite P500              | [2403a2d0f9](https://linux-hardware.org/?probe=2403a2d0f9) | Feb 02, 2022 |
| HP            | ProBook 450 G6              | [1de51c3e3b](https://linux-hardware.org/?probe=1de51c3e3b) | Feb 01, 2022 |
| HP            | ProBook 450 G6              | [e6dfa0f8ec](https://linux-hardware.org/?probe=e6dfa0f8ec) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | [1615c253fc](https://linux-hardware.org/?probe=1615c253fc) | Feb 01, 2022 |
| Dell          | XPS 15 9550                 | [e8acac784c](https://linux-hardware.org/?probe=e8acac784c) | Jan 31, 2022 |
| Dell          | XPS 15 9550                 | [33a9d5357e](https://linux-hardware.org/?probe=33a9d5357e) | Jan 31, 2022 |
| Apple         | MacBookPro8,1               | [0591806d5c](https://linux-hardware.org/?probe=0591806d5c) | Jan 31, 2022 |
| HP            | EliteBook 840 G5            | [01c1515f57](https://linux-hardware.org/?probe=01c1515f57) | Jan 28, 2022 |
| ASUSTek       | X550WA                      | [e146d6a0f8](https://linux-hardware.org/?probe=e146d6a0f8) | Jan 27, 2022 |
| Toshiba       | Satellite P850              | [9fed64bb7e](https://linux-hardware.org/?probe=9fed64bb7e) | Jan 27, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f7c5fb7450](https://linux-hardware.org/?probe=f7c5fb7450) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [36a39bf7eb](https://linux-hardware.org/?probe=36a39bf7eb) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [9d12ae4f9a](https://linux-hardware.org/?probe=9d12ae4f9a) | Jan 26, 2022 |
| Intel Clie... | LAPBC710                    | [586a7bef92](https://linux-hardware.org/?probe=586a7bef92) | Jan 25, 2022 |
| Kogan         | KAL11C250SB                 | [ba3fd61313](https://linux-hardware.org/?probe=ba3fd61313) | Jan 23, 2022 |
| Toshiba       | Satellite L640              | [280b5d9630](https://linux-hardware.org/?probe=280b5d9630) | Jan 22, 2022 |
| Lenovo        | ThinkPad W530 2463B87       | [bb1640db6c](https://linux-hardware.org/?probe=bb1640db6c) | Jan 21, 2022 |
| HP            | ProBook 6560b               | [d5dc02b800](https://linux-hardware.org/?probe=d5dc02b800) | Jan 21, 2022 |
| Dell          | Inspiron 7591               | [2f1c294587](https://linux-hardware.org/?probe=2f1c294587) | Jan 21, 2022 |
| HP            | ProBook 470 G5              | [b4c6ea0b27](https://linux-hardware.org/?probe=b4c6ea0b27) | Jan 18, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [a61f1b9d56](https://linux-hardware.org/?probe=a61f1b9d56) | Jan 16, 2022 |
| Dell          | Latitude 7280               | [d05eb9657d](https://linux-hardware.org/?probe=d05eb9657d) | Jan 16, 2022 |
| ASUSTek       | Unknown                     | [0baed0f9c8](https://linux-hardware.org/?probe=0baed0f9c8) | Jan 16, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6bda3e5854](https://linux-hardware.org/?probe=6bda3e5854) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [d62f3c4bf5](https://linux-hardware.org/?probe=d62f3c4bf5) | Jan 14, 2022 |
| ASUSTek       | TP500LNG                    | [85762ec0a0](https://linux-hardware.org/?probe=85762ec0a0) | Jan 14, 2022 |
| Dell          | Inspiron M5010              | [21dddfe6a8](https://linux-hardware.org/?probe=21dddfe6a8) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | [dffa1b1708](https://linux-hardware.org/?probe=dffa1b1708) | Jan 14, 2022 |
| Apple         | MacBookPro16,1              | [ca163c9952](https://linux-hardware.org/?probe=ca163c9952) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | [cf529c7ad0](https://linux-hardware.org/?probe=cf529c7ad0) | Jan 14, 2022 |
| HP            | EliteBook 8770w             | [d78d315a83](https://linux-hardware.org/?probe=d78d315a83) | Jan 13, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [f7ea85c311](https://linux-hardware.org/?probe=f7ea85c311) | Jan 13, 2022 |
| HP            | Pavilion g6                 | [e14f742bb9](https://linux-hardware.org/?probe=e14f742bb9) | Jan 12, 2022 |
| HP            | Pavilion g6                 | [62f049acf1](https://linux-hardware.org/?probe=62f049acf1) | Jan 12, 2022 |
| Apple         | MacBookPro8,1               | [a462f4b26f](https://linux-hardware.org/?probe=a462f4b26f) | Jan 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c781a61663](https://linux-hardware.org/?probe=c781a61663) | Jan 11, 2022 |
| Dell          | Precision 7550              | [0b72e489be](https://linux-hardware.org/?probe=0b72e489be) | Jan 10, 2022 |
| Dell          | Latitude E7440              | [9d89ac124e](https://linux-hardware.org/?probe=9d89ac124e) | Jan 08, 2022 |
| Acer          | Aspire A315-35              | [1e6abae11a](https://linux-hardware.org/?probe=1e6abae11a) | Jan 08, 2022 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [7ba01d7327](https://linux-hardware.org/?probe=7ba01d7327) | Jan 07, 2022 |
| Kogan         | KAL11C250SB                 | [a153354498](https://linux-hardware.org/?probe=a153354498) | Jan 07, 2022 |
| MSI           | GE62 2QD                    | [5f35b0b1ab](https://linux-hardware.org/?probe=5f35b0b1ab) | Jan 07, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| HP            | EliteBook 8570p             | [f49baae9b5](https://linux-hardware.org/?probe=f49baae9b5) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Apple         | MacBookAir6,2               | [faaaf3cc89](https://linux-hardware.org/?probe=faaaf3cc89) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| Alienware     | m17                         | [13da9fa1b3](https://linux-hardware.org/?probe=13da9fa1b3) | Jan 02, 2022 |
| HP            | ENVY 17                     | [bd8db07a0a](https://linux-hardware.org/?probe=bd8db07a0a) | Jan 02, 2022 |
| Dell          | Inspiron 5770               | [0e81199f2c](https://linux-hardware.org/?probe=0e81199f2c) | Jan 02, 2022 |
| Apple         | MacBookPro11,5              | [1c88a2bad0](https://linux-hardware.org/?probe=1c88a2bad0) | Jan 02, 2022 |
| HP            | ENVY 17                     | [a140a1a272](https://linux-hardware.org/?probe=a140a1a272) | Jan 02, 2022 |
| Dell          | Latitude E5430 vPro         | [a073f421c1](https://linux-hardware.org/?probe=a073f421c1) | Jan 01, 2022 |
| Notebook      | P65xHP                      | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Apple         | MacBookPro9,2               | [601fb323dc](https://linux-hardware.org/?probe=601fb323dc) | Dec 30, 2021 |
| Dell          | Latitude E5420              | [dc28d41913](https://linux-hardware.org/?probe=dc28d41913) | Dec 30, 2021 |
| HP            | 250 G7 Notebook PC          | [9ee8c0f205](https://linux-hardware.org/?probe=9ee8c0f205) | Dec 29, 2021 |
| HP            | EliteBook 2760p             | [1cd129ee35](https://linux-hardware.org/?probe=1cd129ee35) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | [f2deb9ec59](https://linux-hardware.org/?probe=f2deb9ec59) | Dec 27, 2021 |
| Dell          | Inspiron M5010              | [e576e17ed7](https://linux-hardware.org/?probe=e576e17ed7) | Dec 26, 2021 |
| Lenovo        | ThinkPad W530 2463B87       | [e82b5e9a8a](https://linux-hardware.org/?probe=e82b5e9a8a) | Dec 26, 2021 |
| Dell          | XPS 15 9550                 | [fc814dc489](https://linux-hardware.org/?probe=fc814dc489) | Dec 25, 2021 |
| LEADER        | NH5BT11                     | [763efa7eb2](https://linux-hardware.org/?probe=763efa7eb2) | Dec 25, 2021 |
| Toshiba       | Satellite C660              | [b13c6ceb2c](https://linux-hardware.org/?probe=b13c6ceb2c) | Dec 25, 2021 |
| HP            | EliteBook 2560p             | [4081d9b42b](https://linux-hardware.org/?probe=4081d9b42b) | Dec 24, 2021 |
| Acer          | Aspire 5740                 | [baf5d23f31](https://linux-hardware.org/?probe=baf5d23f31) | Dec 24, 2021 |
| Samsung       | 700T                        | [dcd96a051e](https://linux-hardware.org/?probe=dcd96a051e) | Dec 23, 2021 |
| Dell          | XPS 15 7590                 | [5cbe59259b](https://linux-hardware.org/?probe=5cbe59259b) | Dec 23, 2021 |
| Dell          | Latitude E6400              | [46422c0062](https://linux-hardware.org/?probe=46422c0062) | Dec 22, 2021 |
| Google        | Edgar                       | [dc1b8b8c81](https://linux-hardware.org/?probe=dc1b8b8c81) | Dec 20, 2021 |
| Google        | Edgar                       | [96597eb5fd](https://linux-hardware.org/?probe=96597eb5fd) | Dec 20, 2021 |
| Apple         | MacBookPro8,1               | [70ebf43f36](https://linux-hardware.org/?probe=70ebf43f36) | Dec 20, 2021 |
| Dell          | XPS 15 9500                 | [e5592dfde0](https://linux-hardware.org/?probe=e5592dfde0) | Dec 20, 2021 |
| Toshiba       | Satellite C660              | [6f860db242](https://linux-hardware.org/?probe=6f860db242) | Dec 18, 2021 |
| Apple         | MacBookPro8,1               | [08df885431](https://linux-hardware.org/?probe=08df885431) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | [4d52a02213](https://linux-hardware.org/?probe=4d52a02213) | Dec 16, 2021 |
| Apple         | MacBookPro9,2               | [ef78b011ef](https://linux-hardware.org/?probe=ef78b011ef) | Dec 16, 2021 |
| Lenovo        | ThinkPad W540 20BG0011US    | [ead3a18508](https://linux-hardware.org/?probe=ead3a18508) | Dec 15, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [ba92d0772e](https://linux-hardware.org/?probe=ba92d0772e) | Dec 14, 2021 |
| MSI           | PS42 Modern 8RC             | [2686d73cb8](https://linux-hardware.org/?probe=2686d73cb8) | Dec 13, 2021 |
| Lenovo        | ThinkPad T440 20B7S02A00    | [5b3ec8682e](https://linux-hardware.org/?probe=5b3ec8682e) | Dec 13, 2021 |
| Acer          | Aspire 5600                 | [25b1e50c64](https://linux-hardware.org/?probe=25b1e50c64) | Dec 12, 2021 |
| Acer          | ConceptD CN315-71P          | [ac834a5768](https://linux-hardware.org/?probe=ac834a5768) | Dec 11, 2021 |
| Dell          | Latitude 7370               | [d2bbf57105](https://linux-hardware.org/?probe=d2bbf57105) | Dec 11, 2021 |
| HP            | ProBook 470 G5              | [3a17215293](https://linux-hardware.org/?probe=3a17215293) | Dec 11, 2021 |
| HP            | ProBook 470 G5              | [36e4d31312](https://linux-hardware.org/?probe=36e4d31312) | Dec 10, 2021 |
| HP            | Pavilion g6                 | [a50dca2bf2](https://linux-hardware.org/?probe=a50dca2bf2) | Dec 10, 2021 |
| ASUSTek       | X550JX                      | [818c536fda](https://linux-hardware.org/?probe=818c536fda) | Dec 10, 2021 |
| HP            | 250 G6 Notebook PC          | [3b955f362a](https://linux-hardware.org/?probe=3b955f362a) | Dec 10, 2021 |
| HP            | ZBook 14u G5                | [21df45023e](https://linux-hardware.org/?probe=21df45023e) | Dec 09, 2021 |
| HP            | ZBook 14u G5                | [b01068d8cc](https://linux-hardware.org/?probe=b01068d8cc) | Dec 09, 2021 |
| Apple         | MacBookPro14,3              | [6e7dbbfd7a](https://linux-hardware.org/?probe=6e7dbbfd7a) | Dec 08, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| MSI           | GE62 2QD                    | [f37c114570](https://linux-hardware.org/?probe=f37c114570) | Dec 05, 2021 |
| HUAWEI        | HN-WX9X                     | [a4266720ec](https://linux-hardware.org/?probe=a4266720ec) | Dec 05, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | [fbe30211c6](https://linux-hardware.org/?probe=fbe30211c6) | Dec 05, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [ee5c6147f7](https://linux-hardware.org/?probe=ee5c6147f7) | Dec 04, 2021 |
| Toshiba       | Satellite C660              | [47b40007ee](https://linux-hardware.org/?probe=47b40007ee) | Dec 04, 2021 |
| Toshiba       | Satellite C660              | [4d64247a8a](https://linux-hardware.org/?probe=4d64247a8a) | Dec 04, 2021 |
| Acer          | Aspire R3-131T              | [3fd499b264](https://linux-hardware.org/?probe=3fd499b264) | Dec 04, 2021 |
| Gigabyte      | AERO 15 KB                  | [a7d3041cd2](https://linux-hardware.org/?probe=a7d3041cd2) | Dec 03, 2021 |
| Panasonic     | CF-19RDRAMGA                | [5aaebfbf19](https://linux-hardware.org/?probe=5aaebfbf19) | Nov 29, 2021 |
| Toshiba       | Satellite C660              | [2799629c61](https://linux-hardware.org/?probe=2799629c61) | Nov 28, 2021 |
| Toshiba       | Satellite C660              | [1e80d1c181](https://linux-hardware.org/?probe=1e80d1c181) | Nov 28, 2021 |
| Apple         | MacBook7,1                  | [22e54de439](https://linux-hardware.org/?probe=22e54de439) | Nov 27, 2021 |
| HP            | Pavilion Notebook           | [092ae35663](https://linux-hardware.org/?probe=092ae35663) | Nov 27, 2021 |
| Apple         | MacBookPro8,1               | [a0b9aec393](https://linux-hardware.org/?probe=a0b9aec393) | Nov 26, 2021 |
| Apple         | MacBookPro8,1               | [62a1aeadc4](https://linux-hardware.org/?probe=62a1aeadc4) | Nov 26, 2021 |
| ASUSTek       | Unknown                     | [1627a50b96](https://linux-hardware.org/?probe=1627a50b96) | Nov 25, 2021 |
| Toshiba       | Satellite L640              | [0a00178792](https://linux-hardware.org/?probe=0a00178792) | Nov 25, 2021 |
| Toshiba       | Satellite P50t-A            | [33add9e294](https://linux-hardware.org/?probe=33add9e294) | Nov 25, 2021 |
| Apple         | MacBookPro9,2               | [ab60997b9e](https://linux-hardware.org/?probe=ab60997b9e) | Nov 24, 2021 |
| LG Electro... | 14Z960-GR3HK                | [7dd0d53cef](https://linux-hardware.org/?probe=7dd0d53cef) | Nov 24, 2021 |
| HP            | Pavilion g6                 | [f7da6c6d2d](https://linux-hardware.org/?probe=f7da6c6d2d) | Nov 23, 2021 |
| Dell          | G5 5590                     | [3a149ffc5e](https://linux-hardware.org/?probe=3a149ffc5e) | Nov 23, 2021 |
| Apple         | MacBookPro16,1              | [9d02768642](https://linux-hardware.org/?probe=9d02768642) | Nov 23, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | [19ce916e45](https://linux-hardware.org/?probe=19ce916e45) | Nov 22, 2021 |
| Dell          | Latitude 3400               | [62dd7a6ea2](https://linux-hardware.org/?probe=62dd7a6ea2) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | [024686087f](https://linux-hardware.org/?probe=024686087f) | Nov 20, 2021 |
| Acer          | Aspire 5560                 | [5725ae4593](https://linux-hardware.org/?probe=5725ae4593) | Nov 20, 2021 |
| AFTERSHOCK... | VAPOR 15X                   | [6433612bed](https://linux-hardware.org/?probe=6433612bed) | Nov 18, 2021 |
| ASUSTek       | K50IJ                       | [9e28f131eb](https://linux-hardware.org/?probe=9e28f131eb) | Nov 18, 2021 |
| Dell          | Inspiron 7586               | [188923fc9c](https://linux-hardware.org/?probe=188923fc9c) | Nov 17, 2021 |
| Toshiba       | Satellite L50-B             | [867287fb63](https://linux-hardware.org/?probe=867287fb63) | Nov 16, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [d8acfef1ef](https://linux-hardware.org/?probe=d8acfef1ef) | Nov 16, 2021 |
| Dell          | Inspiron 7566               | [b868de3306](https://linux-hardware.org/?probe=b868de3306) | Nov 16, 2021 |
| Lenovo        | V110-15IAP 80TG             | [c6aebae4da](https://linux-hardware.org/?probe=c6aebae4da) | Nov 16, 2021 |
| HP            | Pavilion dv5                | [ec4890a33b](https://linux-hardware.org/?probe=ec4890a33b) | Nov 15, 2021 |
| HP            | Pavilion dv5                | [4ddaeca48c](https://linux-hardware.org/?probe=4ddaeca48c) | Nov 15, 2021 |
| LG Electro... | 16Z90P-G.AA75A              | [d15e199bb4](https://linux-hardware.org/?probe=d15e199bb4) | Nov 14, 2021 |
| Apple         | MacBookPro8,1               | [ea402fa75e](https://linux-hardware.org/?probe=ea402fa75e) | Nov 14, 2021 |
| HP            | Pavilion 15                 | [6b4486db02](https://linux-hardware.org/?probe=6b4486db02) | Nov 13, 2021 |
| HP            | Pavilion 15                 | [d0e343d3b7](https://linux-hardware.org/?probe=d0e343d3b7) | Nov 13, 2021 |
| ASUSTek       | K55A                        | [60377bce60](https://linux-hardware.org/?probe=60377bce60) | Nov 13, 2021 |
| HP            | Pavilion dv6                | [30c1df8961](https://linux-hardware.org/?probe=30c1df8961) | Nov 13, 2021 |
| Apple         | MacBook7,1                  | [b898d5a09c](https://linux-hardware.org/?probe=b898d5a09c) | Nov 13, 2021 |
| Toshiba       | Satellite Pro L50-A         | [36bc6d2ebd](https://linux-hardware.org/?probe=36bc6d2ebd) | Nov 12, 2021 |
| Acer          | Aspire 5720Z                | [ba74c7653a](https://linux-hardware.org/?probe=ba74c7653a) | Nov 12, 2021 |
| Acer          | Aspire 5720Z                | [d11d9b16b0](https://linux-hardware.org/?probe=d11d9b16b0) | Nov 12, 2021 |
| COM1          | NBINF-O5-4R5G5              | [b8a99864aa](https://linux-hardware.org/?probe=b8a99864aa) | Nov 12, 2021 |
| Acer          | Aspire 3000                 | [86d2f89f59](https://linux-hardware.org/?probe=86d2f89f59) | Nov 12, 2021 |
| Acer          | Aspire 3000                 | [dad287d5a1](https://linux-hardware.org/?probe=dad287d5a1) | Nov 11, 2021 |
| Apple         | MacBookAir6,1               | [588c351d40](https://linux-hardware.org/?probe=588c351d40) | Nov 10, 2021 |
| LG Electro... | 14Z90P-G.AR53A              | [a1fb8771db](https://linux-hardware.org/?probe=a1fb8771db) | Nov 10, 2021 |
| COM1          | NBINF-O5-4R5G5              | [e1cd2bd1cc](https://linux-hardware.org/?probe=e1cd2bd1cc) | Nov 10, 2021 |
| Apple         | MacBookPro8,1               | [d499b22b03](https://linux-hardware.org/?probe=d499b22b03) | Nov 09, 2021 |
| Toshiba       | Satellite Pro L50-A         | [6212422e34](https://linux-hardware.org/?probe=6212422e34) | Nov 09, 2021 |
| Unknown       | D15D                        | [5b15ae8ff3](https://linux-hardware.org/?probe=5b15ae8ff3) | Nov 07, 2021 |
| AFTERSHOCK... | VAPOR 15X                   | [cc21cf13c8](https://linux-hardware.org/?probe=cc21cf13c8) | Nov 07, 2021 |
| Samsung       | RF511/RF411/RF711           | [899657b967](https://linux-hardware.org/?probe=899657b967) | Nov 07, 2021 |
| HP            | Pavilion dv6                | [bd084f3ccd](https://linux-hardware.org/?probe=bd084f3ccd) | Nov 07, 2021 |
| Acer          | Aspire ES1-521              | [5ef4af5924](https://linux-hardware.org/?probe=5ef4af5924) | Nov 06, 2021 |
| MSI           | GT72 2QD                    | [d558e0270e](https://linux-hardware.org/?probe=d558e0270e) | Nov 06, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e2180a6c85](https://linux-hardware.org/?probe=e2180a6c85) | Nov 04, 2021 |
| HP            | Pavilion g6                 | [c289308c14](https://linux-hardware.org/?probe=c289308c14) | Nov 04, 2021 |
| ASUSTek       | BU403UA                     | [acb1038124](https://linux-hardware.org/?probe=acb1038124) | Nov 03, 2021 |
| HP            | EliteBook 840 G3            | [a2ddc44da4](https://linux-hardware.org/?probe=a2ddc44da4) | Nov 02, 2021 |
| Toshiba       | Satellite L750D             | [143e009499](https://linux-hardware.org/?probe=143e009499) | Nov 02, 2021 |
| Toshiba       | Satellite P500              | [e69f994b81](https://linux-hardware.org/?probe=e69f994b81) | Nov 02, 2021 |
| MSI           | GT72VR 6RE                  | [4e8a3e6a15](https://linux-hardware.org/?probe=4e8a3e6a15) | Nov 01, 2021 |
| MSI           | GT72VR 6RE                  | [343f246595](https://linux-hardware.org/?probe=343f246595) | Nov 01, 2021 |
| COM1          | NBINF-O5-4R5G5              | [a3b154116b](https://linux-hardware.org/?probe=a3b154116b) | Oct 31, 2021 |
| Lenovo        | ThinkPad R400 7439CTO       | [9a7be426f5](https://linux-hardware.org/?probe=9a7be426f5) | Oct 30, 2021 |
| Toshiba       | Satellite Pro L50-A         | [a817ed896e](https://linux-hardware.org/?probe=a817ed896e) | Oct 29, 2021 |
| Toshiba       | Satellite Pro L50-A         | [5c23460bb8](https://linux-hardware.org/?probe=5c23460bb8) | Oct 27, 2021 |
| Acer          | Aspire 5600                 | [7e2da6d3e9](https://linux-hardware.org/?probe=7e2da6d3e9) | Oct 26, 2021 |
| HP            | Laptop 15s-du1xxx           | [23c770232c](https://linux-hardware.org/?probe=23c770232c) | Oct 25, 2021 |
| Dell          | Inspiron 3505               | [fe09832e42](https://linux-hardware.org/?probe=fe09832e42) | Oct 25, 2021 |
| Toshiba       | Satellite L850              | [066f99ecbc](https://linux-hardware.org/?probe=066f99ecbc) | Oct 25, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | [98720c7a44](https://linux-hardware.org/?probe=98720c7a44) | Oct 24, 2021 |
| Acer          | Aspire ES1-521              | [248ab157b8](https://linux-hardware.org/?probe=248ab157b8) | Oct 23, 2021 |
| HP            | 250 G3                      | [820dcd95a7](https://linux-hardware.org/?probe=820dcd95a7) | Oct 23, 2021 |
| Dell          | Latitude E7450              | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| HP            | Stream Laptop               | [95df1a4e45](https://linux-hardware.org/?probe=95df1a4e45) | Oct 22, 2021 |
| IT Channel... | PCX0DX                      | [fb1bf80085](https://linux-hardware.org/?probe=fb1bf80085) | Oct 22, 2021 |
| Lenovo        | ThinkPad E490s 20NGA000A... | [c2a180845c](https://linux-hardware.org/?probe=c2a180845c) | Oct 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [463b15301d](https://linux-hardware.org/?probe=463b15301d) | Oct 21, 2021 |
| Notebook      | W840SN Series               | [4baeb2cafc](https://linux-hardware.org/?probe=4baeb2cafc) | Oct 20, 2021 |
| Apple         | MacBookPro8,1               | [e72b8e6ba0](https://linux-hardware.org/?probe=e72b8e6ba0) | Oct 20, 2021 |
| HP            | Pavilion Notebook           | [fe8dbfde1b](https://linux-hardware.org/?probe=fe8dbfde1b) | Oct 19, 2021 |
| Acer          | Aspire E5-571               | [aec49e7b35](https://linux-hardware.org/?probe=aec49e7b35) | Oct 19, 2021 |
| HP            | Pavilion Notebook           | [4b53959f48](https://linux-hardware.org/?probe=4b53959f48) | Oct 19, 2021 |
| MSI           | CX70 2QF                    | [f91a0f1380](https://linux-hardware.org/?probe=f91a0f1380) | Oct 19, 2021 |
| MSI           | CX70 2QF                    | [9d4c9ccf89](https://linux-hardware.org/?probe=9d4c9ccf89) | Oct 18, 2021 |
| ASUSTek       | X501A                       | [b3e4d8035d](https://linux-hardware.org/?probe=b3e4d8035d) | Oct 17, 2021 |
| Acer          | ConceptD CN315-71P          | [50385dde8b](https://linux-hardware.org/?probe=50385dde8b) | Oct 16, 2021 |
| Apple         | MacBookAir7,2               | [370b129f3f](https://linux-hardware.org/?probe=370b129f3f) | Oct 16, 2021 |
| Dell          | G7 7700                     | [273e51402c](https://linux-hardware.org/?probe=273e51402c) | Oct 15, 2021 |
| Alienware     | M17xR4                      | [98464fe67b](https://linux-hardware.org/?probe=98464fe67b) | Oct 15, 2021 |
| Alienware     | M17xR4                      | [ea79d2496d](https://linux-hardware.org/?probe=ea79d2496d) | Oct 15, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | [b2214c65d5](https://linux-hardware.org/?probe=b2214c65d5) | Oct 15, 2021 |
| Samsung       | RF511/RF411/RF711           | [ebd0874d7c](https://linux-hardware.org/?probe=ebd0874d7c) | Oct 13, 2021 |
| Samsung       | RF511/RF411/RF711           | [7a4ede4a67](https://linux-hardware.org/?probe=7a4ede4a67) | Oct 13, 2021 |
| HP            | Laptop 15s-du1xxx           | [6b3505b5f2](https://linux-hardware.org/?probe=6b3505b5f2) | Oct 13, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [471414140c](https://linux-hardware.org/?probe=471414140c) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| Dell          | Inspiron 3505               | [8628621ed3](https://linux-hardware.org/?probe=8628621ed3) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| Lenovo        | ThinkPad T410 2522ED2       | [c8c010b75c](https://linux-hardware.org/?probe=c8c010b75c) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0011AU     | [85c8487ca5](https://linux-hardware.org/?probe=85c8487ca5) | Oct 11, 2021 |
| Toshiba       | Satellite L830              | [e8652672c3](https://linux-hardware.org/?probe=e8652672c3) | Oct 10, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [f8efee6741](https://linux-hardware.org/?probe=f8efee6741) | Oct 09, 2021 |
| Dell          | Latitude 5400               | [77c9ee3548](https://linux-hardware.org/?probe=77c9ee3548) | Oct 07, 2021 |
| Dell          | Inspiron 7586               | [2ecf794b47](https://linux-hardware.org/?probe=2ecf794b47) | Oct 07, 2021 |
| Acer          | Aspire E5-571               | [8e65153ce2](https://linux-hardware.org/?probe=8e65153ce2) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Toshiba       | Satellite C55t-C            | [a6f33aa565](https://linux-hardware.org/?probe=a6f33aa565) | Oct 03, 2021 |
| Dell          | Latitude 5410               | [6928f4237f](https://linux-hardware.org/?probe=6928f4237f) | Oct 01, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [55c08d7759](https://linux-hardware.org/?probe=55c08d7759) | Sep 27, 2021 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [23dbed3ab1](https://linux-hardware.org/?probe=23dbed3ab1) | Sep 26, 2021 |
| Lenovo        | ThinkPad X61s 7667DE3       | [9d3daab4b3](https://linux-hardware.org/?probe=9d3daab4b3) | Sep 25, 2021 |
| Dell          | Inspiron 11-3168            | [4c7c72b321](https://linux-hardware.org/?probe=4c7c72b321) | Sep 25, 2021 |
| Kogan         | KAL11C250SB                 | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Notebook      | W840SN Series               | [15f25a62a8](https://linux-hardware.org/?probe=15f25a62a8) | Sep 23, 2021 |
| Lenovo        | Mixx-700-12ISK 80QL         | [090e25b77c](https://linux-hardware.org/?probe=090e25b77c) | Sep 22, 2021 |
| Dell          | Precision 5560              | [c31c2d637b](https://linux-hardware.org/?probe=c31c2d637b) | Sep 21, 2021 |
| Dell          | Precision 5560              | [7b8db74bd5](https://linux-hardware.org/?probe=7b8db74bd5) | Sep 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3C... | [4698844ec0](https://linux-hardware.org/?probe=4698844ec0) | Sep 20, 2021 |
| Toshiba       | Satellite L20               | [654c60e971](https://linux-hardware.org/?probe=654c60e971) | Sep 20, 2021 |
| Acer          | Aspire 5600                 | [6d6b90c8e8](https://linux-hardware.org/?probe=6d6b90c8e8) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Unknown       | Unknown                     | [f620b10ff0](https://linux-hardware.org/?probe=f620b10ff0) | Sep 14, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [d238092077](https://linux-hardware.org/?probe=d238092077) | Sep 14, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [68eacd0e30](https://linux-hardware.org/?probe=68eacd0e30) | Sep 13, 2021 |
| HP            | Pavilion dv6                | [b0e257ccca](https://linux-hardware.org/?probe=b0e257ccca) | Sep 13, 2021 |
| Acer          | Aspire R3-131T              | [e872ba288e](https://linux-hardware.org/?probe=e872ba288e) | Sep 12, 2021 |
| ASUSTek       | N750JV                      | [e24cb69cc0](https://linux-hardware.org/?probe=e24cb69cc0) | Sep 11, 2021 |
| Metabox       | Alpha-X NH77DC              | [0b6122c2ce](https://linux-hardware.org/?probe=0b6122c2ce) | Sep 10, 2021 |
| Metabox       | Alpha-X NH77DC              | [98364c4883](https://linux-hardware.org/?probe=98364c4883) | Sep 10, 2021 |
| Dell          | XPS 13 9370                 | [db0606cb42](https://linux-hardware.org/?probe=db0606cb42) | Sep 10, 2021 |
| Dell          | XPS 15 9560                 | [b33af6d329](https://linux-hardware.org/?probe=b33af6d329) | Sep 10, 2021 |
| Lenovo        | ThinkPad R400 7439CTO       | [5b2fb97960](https://linux-hardware.org/?probe=5b2fb97960) | Sep 10, 2021 |
| Alienware     | 17                          | [49c757651f](https://linux-hardware.org/?probe=49c757651f) | Sep 09, 2021 |
| Apple         | MacBookPro8,1               | [5be67e3cb8](https://linux-hardware.org/?probe=5be67e3cb8) | Sep 07, 2021 |
| Dell          | Latitude E6430s             | [0995d2317b](https://linux-hardware.org/?probe=0995d2317b) | Sep 06, 2021 |
| Timi          | TM1613                      | [530a9daa43](https://linux-hardware.org/?probe=530a9daa43) | Sep 06, 2021 |
| Toshiba       | Satellite P750              | [ee2674ad2e](https://linux-hardware.org/?probe=ee2674ad2e) | Sep 06, 2021 |
| Dell          | Latitude E5430 non-vPro     | [e26b6d083b](https://linux-hardware.org/?probe=e26b6d083b) | Sep 06, 2021 |
| Dell          | Latitude E5430 non-vPro     | [f4d430c0f9](https://linux-hardware.org/?probe=f4d430c0f9) | Sep 06, 2021 |
| Apple         | MacBookPro8,1               | [a865b060fa](https://linux-hardware.org/?probe=a865b060fa) | Sep 06, 2021 |
| Metabox       | NP50DE                      | [355939bc8d](https://linux-hardware.org/?probe=355939bc8d) | Sep 05, 2021 |
| ASUSTek       | K72F                        | [718b264baf](https://linux-hardware.org/?probe=718b264baf) | Sep 05, 2021 |
| ASUSTek       | K72F                        | [68b6deb2e1](https://linux-hardware.org/?probe=68b6deb2e1) | Sep 05, 2021 |
| Toshiba       | Satellite L50-B             | [e8f5eb9453](https://linux-hardware.org/?probe=e8f5eb9453) | Sep 04, 2021 |
| HP            | Presario CQ62               | [4cdec89015](https://linux-hardware.org/?probe=4cdec89015) | Sep 04, 2021 |
| Metabox       | Alpha-S NP70HJ              | [7b477b4fae](https://linux-hardware.org/?probe=7b477b4fae) | Sep 04, 2021 |
| Metabox       | Alpha-S NP70HJ              | [a72cca0cf9](https://linux-hardware.org/?probe=a72cca0cf9) | Sep 04, 2021 |
| Toshiba       | Satellite L50-B             | [696718d602](https://linux-hardware.org/?probe=696718d602) | Sep 03, 2021 |
| Dell          | XPS 15 9510                 | [d606dd2010](https://linux-hardware.org/?probe=d606dd2010) | Sep 03, 2021 |
| Dell          | Latitude E6430s             | [92a767fd0b](https://linux-hardware.org/?probe=92a767fd0b) | Sep 03, 2021 |
| Toshiba       | TECRA A40-D                 | [5afac0ef07](https://linux-hardware.org/?probe=5afac0ef07) | Sep 02, 2021 |
| Dell          | XPS 15 9500                 | [bf06fd5933](https://linux-hardware.org/?probe=bf06fd5933) | Sep 02, 2021 |
| Dell          | XPS 15 9500                 | [740118101a](https://linux-hardware.org/?probe=740118101a) | Sep 02, 2021 |
| HP            | Pavilion dv6                | [20e136bd56](https://linux-hardware.org/?probe=20e136bd56) | Aug 31, 2021 |
| Toshiba       | Satellite L670              | [4610a7f835](https://linux-hardware.org/?probe=4610a7f835) | Aug 31, 2021 |
| HP            | Presario CQ62               | [da35a133c7](https://linux-hardware.org/?probe=da35a133c7) | Aug 31, 2021 |
| HP            | Pavilion Notebook           | [846b2e2a87](https://linux-hardware.org/?probe=846b2e2a87) | Aug 30, 2021 |
| Dell          | Latitude E6230              | [055cc1b72a](https://linux-hardware.org/?probe=055cc1b72a) | Aug 30, 2021 |
| Dell          | G5 5590                     | [268f4cffb4](https://linux-hardware.org/?probe=268f4cffb4) | Aug 30, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [a900c9c170](https://linux-hardware.org/?probe=a900c9c170) | Aug 30, 2021 |
| ASUSTek       | BU403UA                     | [685da500ca](https://linux-hardware.org/?probe=685da500ca) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [b7c59b9453](https://linux-hardware.org/?probe=b7c59b9453) | Aug 30, 2021 |
| Timi          | TM1607                      | [0dcb7e6611](https://linux-hardware.org/?probe=0dcb7e6611) | Aug 30, 2021 |
| Toshiba       | Satellite C55t-C            | [2bf7dba42f](https://linux-hardware.org/?probe=2bf7dba42f) | Aug 30, 2021 |
| Dell          | Latitude E7470              | [e047247ab4](https://linux-hardware.org/?probe=e047247ab4) | Aug 29, 2021 |
| Toshiba       | PORTEGE M780                | [3062a1ac2f](https://linux-hardware.org/?probe=3062a1ac2f) | Aug 28, 2021 |
| Lenovo        | ThinkPad SL 27464RM         | [612cb5f7a2](https://linux-hardware.org/?probe=612cb5f7a2) | Aug 28, 2021 |
| Apple         | MacBookPro5,5               | [97ed1ed910](https://linux-hardware.org/?probe=97ed1ed910) | Aug 28, 2021 |
| Apple         | MacBookPro5,5               | [e035ede092](https://linux-hardware.org/?probe=e035ede092) | Aug 27, 2021 |
| Kogan         | KAL11C250SB                 | [1c38937a42](https://linux-hardware.org/?probe=1c38937a42) | Aug 24, 2021 |
| Apple         | MacBookPro8,1               | [7b296604b3](https://linux-hardware.org/?probe=7b296604b3) | Aug 24, 2021 |
| Dell          | Latitude E5500              | [5af91644f4](https://linux-hardware.org/?probe=5af91644f4) | Aug 22, 2021 |
| HP            | Notebook                    | [5ac3618644](https://linux-hardware.org/?probe=5ac3618644) | Aug 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ff1e83e570](https://linux-hardware.org/?probe=ff1e83e570) | Aug 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [4128c360ba](https://linux-hardware.org/?probe=4128c360ba) | Aug 22, 2021 |
| HP            | Laptop 15s-du1xxx           | [0db32c3e7e](https://linux-hardware.org/?probe=0db32c3e7e) | Aug 21, 2021 |
| Dell          | XPS 15 9570                 | [1114f42cd0](https://linux-hardware.org/?probe=1114f42cd0) | Aug 21, 2021 |
| Dell          | XPS 15 9570                 | [44188d0e94](https://linux-hardware.org/?probe=44188d0e94) | Aug 21, 2021 |
| ASUSTek       | G60JX                       | [d3844a2f0d](https://linux-hardware.org/?probe=d3844a2f0d) | Aug 19, 2021 |
| ASUSTek       | G60JX                       | [9cbac37f77](https://linux-hardware.org/?probe=9cbac37f77) | Aug 19, 2021 |
| HP            | 245 G7 Notebook PC          | [5f26581582](https://linux-hardware.org/?probe=5f26581582) | Aug 19, 2021 |
| Apple         | MacBookPro8,1               | [4678cd0f57](https://linux-hardware.org/?probe=4678cd0f57) | Aug 19, 2021 |
| Panasonic     | CF-19RDRAMGA                | [b11b688d14](https://linux-hardware.org/?probe=b11b688d14) | Aug 18, 2021 |
| Lenovo        | G560 0679                   | [897bce191e](https://linux-hardware.org/?probe=897bce191e) | Aug 18, 2021 |
| HP            | EliteBook 745 G5            | [7154f86bd2](https://linux-hardware.org/?probe=7154f86bd2) | Aug 15, 2021 |
| HP            | EliteBook 820 G3            | [9e40c4d015](https://linux-hardware.org/?probe=9e40c4d015) | Aug 15, 2021 |
| Panasonic     | CF-19RDRAMGA                | [3d6f06387e](https://linux-hardware.org/?probe=3d6f06387e) | Aug 14, 2021 |
| ASUSTek       | N550JV                      | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| ASUSTek       | UX21E                       | [d334eaddee](https://linux-hardware.org/?probe=d334eaddee) | Aug 13, 2021 |
| ASUSTek       | N550JV                      | [631e697061](https://linux-hardware.org/?probe=631e697061) | Aug 13, 2021 |
| ASUSTek       | N550JV                      | [191ce05579](https://linux-hardware.org/?probe=191ce05579) | Aug 13, 2021 |
| Dell          | G7 7790                     | [99dd172940](https://linux-hardware.org/?probe=99dd172940) | Aug 12, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c1fe9dc989](https://linux-hardware.org/?probe=c1fe9dc989) | Aug 12, 2021 |
| Lenovo        | G50-45 80E3                 | [deb2b65c2b](https://linux-hardware.org/?probe=deb2b65c2b) | Aug 12, 2021 |
| HP            | Laptop 15s-du1xxx           | [19412614ef](https://linux-hardware.org/?probe=19412614ef) | Aug 11, 2021 |
| Dell          | Latitude E7470              | [d9dfcc1b21](https://linux-hardware.org/?probe=d9dfcc1b21) | Aug 10, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [52118232ff](https://linux-hardware.org/?probe=52118232ff) | Aug 10, 2021 |
| Acer          | Swift SF314-57              | [215a6c3074](https://linux-hardware.org/?probe=215a6c3074) | Aug 10, 2021 |
| Dell          | Inspiron 5547               | [b0404fbe46](https://linux-hardware.org/?probe=b0404fbe46) | Aug 07, 2021 |
| HP            | Compaq Presario CQ60        | [4f08d66d45](https://linux-hardware.org/?probe=4f08d66d45) | Aug 06, 2021 |
| Acer          | Aspire 5600                 | [0f2143b2b8](https://linux-hardware.org/?probe=0f2143b2b8) | Aug 06, 2021 |
| Acer          | Aspire 5750G                | [1309d808df](https://linux-hardware.org/?probe=1309d808df) | Aug 06, 2021 |
| Acer          | Aspire 5750G                | [d8031b12b6](https://linux-hardware.org/?probe=d8031b12b6) | Aug 06, 2021 |
| HP            | Compaq Presario CQ60        | [78e707b9f9](https://linux-hardware.org/?probe=78e707b9f9) | Aug 06, 2021 |
| Dell          | Precision 5540              | [f0e5719b08](https://linux-hardware.org/?probe=f0e5719b08) | Aug 06, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [1b40831803](https://linux-hardware.org/?probe=1b40831803) | Aug 04, 2021 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [8f5a4ed54c](https://linux-hardware.org/?probe=8f5a4ed54c) | Aug 04, 2021 |
| Toshiba       | PORTEGE R30-A               | [084f842b96](https://linux-hardware.org/?probe=084f842b96) | Aug 03, 2021 |
| Toshiba       | PORTEGE R30-A               | [6f6ac5daf9](https://linux-hardware.org/?probe=6f6ac5daf9) | Aug 03, 2021 |
| Toshiba       | PORTEGE M780                | [0b4712cca4](https://linux-hardware.org/?probe=0b4712cca4) | Aug 03, 2021 |
| ASUSTek       | E205SA                      | [43c5f73997](https://linux-hardware.org/?probe=43c5f73997) | Aug 03, 2021 |
| Acer          | Swift SF314-41              | [b4e22213f2](https://linux-hardware.org/?probe=b4e22213f2) | Aug 03, 2021 |
| Toshiba       | Satellite C665D             | [d59b8d5f1d](https://linux-hardware.org/?probe=d59b8d5f1d) | Aug 03, 2021 |
| HP            | ENVY 17                     | [062df6e72a](https://linux-hardware.org/?probe=062df6e72a) | Aug 03, 2021 |
| Dell          | Precision 5540              | [beac3a4550](https://linux-hardware.org/?probe=beac3a4550) | Aug 02, 2021 |
| HP            | Pavilion 13 x360 PC         | [a58c2624f5](https://linux-hardware.org/?probe=a58c2624f5) | Aug 02, 2021 |
| HP            | Pavilion 13 x360 PC         | [6500790c35](https://linux-hardware.org/?probe=6500790c35) | Aug 02, 2021 |
| Acer          | Aspire 5750G                | [0be9e70a0e](https://linux-hardware.org/?probe=0be9e70a0e) | Jul 29, 2021 |
| Acer          | Aspire 5750G                | [f99d763e4e](https://linux-hardware.org/?probe=f99d763e4e) | Jul 29, 2021 |
| Acer          | Aspire ES1-523              | [8c4ca90fbe](https://linux-hardware.org/?probe=8c4ca90fbe) | Jul 28, 2021 |
| Acer          | Aspire 5600                 | [10fca9ad05](https://linux-hardware.org/?probe=10fca9ad05) | Jul 28, 2021 |
| Dell          | Latitude 7370               | [8844c61431](https://linux-hardware.org/?probe=8844c61431) | Jul 27, 2021 |
| Dell          | Latitude 7370               | [65b034f3f3](https://linux-hardware.org/?probe=65b034f3f3) | Jul 27, 2021 |
| Alienware     | M17xR4                      | [bd3bf6b728](https://linux-hardware.org/?probe=bd3bf6b728) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Acer          | Predator G3-571             | [8391b40344](https://linux-hardware.org/?probe=8391b40344) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [7757049c0f](https://linux-hardware.org/?probe=7757049c0f) | Jul 24, 2021 |
| ASUSTek       | G74Sx                       | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| HP            | Pavilion 15                 | [7a0695e6bb](https://linux-hardware.org/?probe=7a0695e6bb) | Jul 23, 2021 |
| Dell          | XPS 17 9700                 | [400d8e67ef](https://linux-hardware.org/?probe=400d8e67ef) | Jul 23, 2021 |
| Acer          | Aspire ES1-523              | [b7b78a52d1](https://linux-hardware.org/?probe=b7b78a52d1) | Jul 22, 2021 |
| HP            | ENVY TS 15                  | [345c92d5c3](https://linux-hardware.org/?probe=345c92d5c3) | Jul 21, 2021 |
| System76      | Gazelle                     | [a6df2bb1a8](https://linux-hardware.org/?probe=a6df2bb1a8) | Jul 21, 2021 |
| Dell          | Inspiron 15 5510            | [49660ef55a](https://linux-hardware.org/?probe=49660ef55a) | Jul 21, 2021 |
| Toshiba       | Satellite L500              | [8a51f94bcc](https://linux-hardware.org/?probe=8a51f94bcc) | Jul 21, 2021 |
| Acer          | Aspire ES1-523              | [cbbd57725a](https://linux-hardware.org/?probe=cbbd57725a) | Jul 20, 2021 |
| Toshiba       | TECRA A40-D                 | [76816bad4a](https://linux-hardware.org/?probe=76816bad4a) | Jul 20, 2021 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [570d86d845](https://linux-hardware.org/?probe=570d86d845) | Jul 20, 2021 |
| HP            | 250 G6 Notebook PC          | [14945dd66b](https://linux-hardware.org/?probe=14945dd66b) | Jul 19, 2021 |
| Dynabook      | Satellite Pro C50-H         | [593e35f7de](https://linux-hardware.org/?probe=593e35f7de) | Jul 18, 2021 |
| Dynabook      | Satellite Pro C50-H         | [30760fd197](https://linux-hardware.org/?probe=30760fd197) | Jul 18, 2021 |
| ONE-NETBOO... | A1                          | [9b9734f000](https://linux-hardware.org/?probe=9b9734f000) | Jul 17, 2021 |
| Notebook      | W840SN Series               | [4414afdecf](https://linux-hardware.org/?probe=4414afdecf) | Jul 16, 2021 |
| Acer          | Predator G3-571             | [99c16ec7fb](https://linux-hardware.org/?probe=99c16ec7fb) | Jul 15, 2021 |
| HP            | Laptop 15-bs1xx             | [3d1c92e425](https://linux-hardware.org/?probe=3d1c92e425) | Jul 15, 2021 |
| One Educat... | Infinity:One                | [2f6016cb80](https://linux-hardware.org/?probe=2f6016cb80) | Jul 12, 2021 |
| Toshiba       | Satellite L750              | [6e7debda59](https://linux-hardware.org/?probe=6e7debda59) | Jul 12, 2021 |
| Dell          | Precision 5540              | [29bcf08396](https://linux-hardware.org/?probe=29bcf08396) | Jul 11, 2021 |
| Lenovo        | ThinkPad X1 Titanium Gen... | [6279f113cf](https://linux-hardware.org/?probe=6279f113cf) | Jul 10, 2021 |
| Lenovo        | ThinkPad X1 Titanium Gen... | [577f7a44f7](https://linux-hardware.org/?probe=577f7a44f7) | Jul 10, 2021 |
| Gigabyte      | AERO 15 KB                  | [e689bf94fe](https://linux-hardware.org/?probe=e689bf94fe) | Jul 09, 2021 |
| Google        | Cave                        | [80261a92eb](https://linux-hardware.org/?probe=80261a92eb) | Jul 08, 2021 |
| Google        | Cave                        | [4a7d6ffd00](https://linux-hardware.org/?probe=4a7d6ffd00) | Jul 08, 2021 |
| Sony          | SVF15A16CGS                 | [93408236cc](https://linux-hardware.org/?probe=93408236cc) | Jul 07, 2021 |
| Sony          | SVF15A16CGS                 | [afe44e2c41](https://linux-hardware.org/?probe=afe44e2c41) | Jul 07, 2021 |
| HP            | Pavilion dv6                | [9f8f5b0ce9](https://linux-hardware.org/?probe=9f8f5b0ce9) | Jul 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [9fb071c117](https://linux-hardware.org/?probe=9fb071c117) | Jul 06, 2021 |
| Dell          | Latitude E5520              | [11a20a01eb](https://linux-hardware.org/?probe=11a20a01eb) | Jul 05, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [afe362114a](https://linux-hardware.org/?probe=afe362114a) | Jul 05, 2021 |
| HP            | EliteBook 8540w             | [6130e48df9](https://linux-hardware.org/?probe=6130e48df9) | Jul 05, 2021 |
| HP            | EliteBook 8540w             | [8fcf62f37c](https://linux-hardware.org/?probe=8fcf62f37c) | Jul 05, 2021 |
| Dell          | Inspiron 5567               | [1387eb5740](https://linux-hardware.org/?probe=1387eb5740) | Jul 03, 2021 |
| Notebook      | P95_HP                      | [8aa8037e16](https://linux-hardware.org/?probe=8aa8037e16) | Jul 03, 2021 |
| Dell          | Latitude 3440               | [6139da799f](https://linux-hardware.org/?probe=6139da799f) | Jun 30, 2021 |
| Sony          | VGN-FW47GY_H                | [d66a6e2b5d](https://linux-hardware.org/?probe=d66a6e2b5d) | Jun 25, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [663b4e4994](https://linux-hardware.org/?probe=663b4e4994) | Jun 22, 2021 |
| Dell          | Latitude 3440               | [abc3010962](https://linux-hardware.org/?probe=abc3010962) | Jun 22, 2021 |
| Dell          | Inspiron M5010              | [1776eab993](https://linux-hardware.org/?probe=1776eab993) | Jun 22, 2021 |
| Dell          | Inspiron 3531               | [afe609b492](https://linux-hardware.org/?probe=afe609b492) | Jun 22, 2021 |
| Dell          | Latitude E7450              | [0bb4d0ad6d](https://linux-hardware.org/?probe=0bb4d0ad6d) | Jun 22, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | [4d638e6ba4](https://linux-hardware.org/?probe=4d638e6ba4) | Jun 21, 2021 |
| Dell          | XPS 13 7390                 | [ffd6111ce0](https://linux-hardware.org/?probe=ffd6111ce0) | Jun 21, 2021 |
| Acer          | A515-52-572L                | [50624d3e67](https://linux-hardware.org/?probe=50624d3e67) | Jun 21, 2021 |
| HP            | ProBook 430 G2              | [477a2d94ef](https://linux-hardware.org/?probe=477a2d94ef) | Jun 18, 2021 |
| HP            | ProBook 430 G2              | [f2e2545c0a](https://linux-hardware.org/?probe=f2e2545c0a) | Jun 17, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [32538ae4b8](https://linux-hardware.org/?probe=32538ae4b8) | Jun 17, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [882855d037](https://linux-hardware.org/?probe=882855d037) | Jun 17, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | [0f830d98f5](https://linux-hardware.org/?probe=0f830d98f5) | Jun 15, 2021 |
| Lenovo        | Yoga S730-13IML 81U4        | [a357c549d3](https://linux-hardware.org/?probe=a357c549d3) | Jun 15, 2021 |
| ASUSTek       | N550JV                      | [0379830a1b](https://linux-hardware.org/?probe=0379830a1b) | Jun 15, 2021 |
| HP            | EliteBook 2560p             | [b8cf45e412](https://linux-hardware.org/?probe=b8cf45e412) | Jun 15, 2021 |
| Toshiba       | Satellite L750              | [572807c3ac](https://linux-hardware.org/?probe=572807c3ac) | Jun 14, 2021 |
| Lenovo        | ThinkPad T460s 20FAS5ML0... | [6ea1914144](https://linux-hardware.org/?probe=6ea1914144) | Jun 14, 2021 |
| Toshiba       | Satellite L750              | [df0e59887e](https://linux-hardware.org/?probe=df0e59887e) | Jun 14, 2021 |
| Toshiba       | Satellite C55t-C            | [0519b9a79c](https://linux-hardware.org/?probe=0519b9a79c) | Jun 13, 2021 |
| LEADER        | NH5BT11                     | [572655ab08](https://linux-hardware.org/?probe=572655ab08) | Jun 12, 2021 |
| LEADER        | NH5BT11                     | [5a6ffecdb6](https://linux-hardware.org/?probe=5a6ffecdb6) | Jun 12, 2021 |
| Dell          | Inspiron 5447               | [0a7b01f59f](https://linux-hardware.org/?probe=0a7b01f59f) | Jun 11, 2021 |
| Dell          | Inspiron M5010              | [a3931de055](https://linux-hardware.org/?probe=a3931de055) | Jun 10, 2021 |
| Lenovo        | ThinkPad T420 4180BJ7       | [4291003ff9](https://linux-hardware.org/?probe=4291003ff9) | Jun 10, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 193       | 14.28%  |
| Ubuntu 18.04       | 82        | 6.07%   |
| Ubuntu 22.04       | 37        | 2.74%   |
| Pop!_OS 22.04      | 32        | 2.37%   |
| KDE neon 20.04     | 30        | 2.22%   |
| Fedora 36          | 29        | 2.14%   |
| Debian 11          | 28        | 2.07%   |
| Pop!_OS 21.04      | 27        | 2%      |
| Linux Mint 20.2    | 27        | 2%      |
| Zorin 16           | 26        | 1.92%   |
| Pop!_OS 20.04      | 24        | 1.78%   |
| OpenMandriva 4.3   | 24        | 1.78%   |
| Linux Mint 20.3    | 24        | 1.78%   |
| Arch               | 24        | 1.78%   |
| Linux Mint 20      | 22        | 1.63%   |
| Ubuntu 20.10       | 21        | 1.55%   |
| OpenMandriva 4.2   | 20        | 1.48%   |
| Pop!_OS 20.10      | 19        | 1.41%   |
| Linux Mint 20.1    | 19        | 1.41%   |
| Ubuntu 21.10       | 18        | 1.33%   |
| Ubuntu 19.04       | 18        | 1.33%   |
| Manjaro            | 18        | 1.33%   |
| Fedora 37          | 18        | 1.33%   |
| Arch Rolling       | 18        | 1.33%   |
| Ubuntu 19.10       | 17        | 1.26%   |
| Fedora 33          | 16        | 1.18%   |
| Zorin 15           | 15        | 1.11%   |
| Ubuntu 21.04       | 14        | 1.04%   |
| Fedora 35          | 14        | 1.04%   |
| ArcoLinux Rolling  | 14        | 1.04%   |
| Xubuntu 18.04      | 12        | 0.89%   |
| Linux Mint 21      | 12        | 0.89%   |
| Fedora 32          | 12        | 0.89%   |
| Xubuntu 20.04      | 10        | 0.74%   |
| Ubuntu 22.10       | 10        | 0.74%   |
| OpenMandriva 23.01 | 9         | 0.67%   |
| Linux Mint 19.3    | 9         | 0.67%   |
| Kubuntu 20.04      | 9         | 0.67%   |
| Fedora 34          | 9         | 0.67%   |
| Elementary 6.1     | 9         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 396       | 31.28%  |
| Linux Mint    | 121       | 9.56%   |
| Pop!_OS       | 104       | 8.21%   |
| Fedora        | 93        | 7.35%   |
| OpenMandriva  | 64        | 5.06%   |
| Zorin         | 48        | 3.79%   |
| Debian        | 45        | 3.55%   |
| Manjaro       | 42        | 3.32%   |
| Arch          | 42        | 3.32%   |
| KDE neon      | 36        | 2.84%   |
| Xubuntu       | 32        | 2.53%   |
| Kubuntu       | 25        | 1.97%   |
| Elementary    | 21        | 1.66%   |
| Kali          | 17        | 1.34%   |
| Gentoo        | 15        | 1.18%   |
| ArcoLinux     | 14        | 1.11%   |
| Endless       | 11        | 0.87%   |
| Clear Linux   | 11        | 0.87%   |
| Ubuntu Unity  | 10        | 0.79%   |
| ROSA          | 10        | 0.79%   |
| Lubuntu       | 10        | 0.79%   |
| openSUSE      | 9         | 0.71%   |
| Ubuntu MATE   | 7         | 0.55%   |
| LMDE          | 7         | 0.55%   |
| EndeavourOS   | 7         | 0.55%   |
| LinuxFX       | 6         | 0.47%   |
| Parrot        | 5         | 0.39%   |
| MX            | 5         | 0.39%   |
| Reborn OS     | 4         | 0.32%   |
| BlackPanther  | 4         | 0.32%   |
| Ubuntu Budgie | 3         | 0.24%   |
| Solus         | 3         | 0.24%   |
| Xero          | 2         | 0.16%   |
| Void Linux    | 2         | 0.16%   |
| SteamOS       | 2         | 0.16%   |
| RHEL          | 2         | 0.16%   |
| PureOS        | 2         | 0.16%   |
| Oracle Linux  | 2         | 0.16%   |
| Linux Lite    | 2         | 0.16%   |
| CentOS        | 2         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 33        | 2.19%   |
| 5.16.7-desktop-1omv4003  | 23        | 1.53%   |
| 5.10.14-desktop-1omv4002 | 20        | 1.33%   |
| 5.4.0-58-generic         | 18        | 1.2%    |
| 5.4.0-26-generic         | 15        | 1%      |
| 5.4.0-40-generic         | 14        | 0.93%   |
| 5.11.0-7620-generic      | 14        | 0.93%   |
| 5.4.0-29-generic         | 13        | 0.86%   |
| 5.15.0-56-generic        | 13        | 0.86%   |
| 5.4.0-48-generic         | 12        | 0.8%    |
| 5.11.0-38-generic        | 12        | 0.8%    |
| 5.17.5-76051705-generic  | 11        | 0.73%   |
| 5.11.0-37-generic        | 11        | 0.73%   |
| 5.11.0-27-generic        | 11        | 0.73%   |
| 5.4.0-52-generic         | 10        | 0.66%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.6%    |
| 5.8.0-63-generic         | 9         | 0.6%    |
| 5.4.0-81-generic         | 9         | 0.6%    |
| 5.4.0-74-generic         | 9         | 0.6%    |
| 5.3.0-40-generic         | 9         | 0.6%    |
| 5.15.0-58-generic        | 9         | 0.6%    |
| 5.8.0-7630-generic       | 8         | 0.53%   |
| 5.8.0-59-generic         | 8         | 0.53%   |
| 5.4.0-7634-generic       | 8         | 0.53%   |
| 5.4.0-65-generic         | 8         | 0.53%   |
| 5.4.0-54-generic         | 8         | 0.53%   |
| 5.3.0-28-generic         | 8         | 0.53%   |
| 5.13.0-7620-generic      | 8         | 0.53%   |
| 5.13.0-40-generic        | 8         | 0.53%   |
| 5.11.0-40-generic        | 8         | 0.53%   |
| 5.0.0-13-generic         | 8         | 0.53%   |
| 5.8.0-7642-generic       | 7         | 0.46%   |
| 5.8.0-53-generic         | 7         | 0.46%   |
| 5.8.0-50-generic         | 7         | 0.46%   |
| 5.4.0-91-generic         | 7         | 0.46%   |
| 5.4.0-7642-generic       | 7         | 0.46%   |
| 5.4.0-47-generic         | 7         | 0.46%   |
| 5.4.0-31-generic         | 7         | 0.46%   |
| 5.3.0-46-generic         | 7         | 0.46%   |
| 5.15.0-52-generic        | 7         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 261       | 18.76%  |
| 5.11.0  | 101       | 7.26%   |
| 5.15.0  | 86        | 6.18%   |
| 5.8.0   | 84        | 6.04%   |
| 5.13.0  | 79        | 5.68%   |
| 4.15.0  | 68        | 4.89%   |
| 5.3.0   | 52        | 3.74%   |
| 5.0.0   | 41        | 2.95%   |
| 5.10.0  | 39        | 2.8%    |
| 4.18.0  | 30        | 2.16%   |
| 5.16.7  | 24        | 1.73%   |
| 5.10.14 | 20        | 1.44%   |
| 5.19.0  | 19        | 1.37%   |
| 5.17.5  | 17        | 1.22%   |
| 6.1.1   | 12        | 0.86%   |
| 4.19.0  | 11        | 0.79%   |
| 5.18.0  | 9         | 0.65%   |
| 6.0.0   | 8         | 0.58%   |
| 5.18.10 | 8         | 0.58%   |
| 6.0.9   | 6         | 0.43%   |
| 6.0.7   | 6         | 0.43%   |
| 6.0.12  | 6         | 0.43%   |
| 5.18.12 | 6         | 0.43%   |
| 5.17.15 | 6         | 0.43%   |
| 5.14.0  | 6         | 0.43%   |
| 5.8.16  | 5         | 0.36%   |
| 5.16.11 | 5         | 0.36%   |
| 5.16.0  | 5         | 0.36%   |
| 5.12.4  | 5         | 0.36%   |
| 4.9.60  | 5         | 0.36%   |
| 6.0.6   | 4         | 0.29%   |
| 5.9.16  | 4         | 0.29%   |
| 5.18.7  | 4         | 0.29%   |
| 5.16.2  | 4         | 0.29%   |
| 5.16.19 | 4         | 0.29%   |
| 5.15.72 | 4         | 0.29%   |
| 5.15.11 | 4         | 0.29%   |
| 5.13.12 | 4         | 0.29%   |
| 4.4.0   | 4         | 0.29%   |
| 6.1.7   | 3         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 284       | 20.82%  |
| 5.15    | 122       | 8.94%   |
| 5.11    | 115       | 8.43%   |
| 5.8     | 101       | 7.4%    |
| 5.13    | 93        | 6.82%   |
| 5.10    | 83        | 6.09%   |
| 4.15    | 68        | 4.99%   |
| 5.16    | 57        | 4.18%   |
| 5.3     | 56        | 4.11%   |
| 5.0     | 45        | 3.3%    |
| 6.0     | 40        | 2.93%   |
| 5.17    | 38        | 2.79%   |
| 5.18    | 36        | 2.64%   |
| 5.19    | 34        | 2.49%   |
| 4.18    | 34        | 2.49%   |
| 6.1     | 21        | 1.54%   |
| 5.6     | 18        | 1.32%   |
| 5.9     | 17        | 1.25%   |
| 5.14    | 15        | 1.1%    |
| 5.12    | 15        | 1.1%    |
| 4.19    | 14        | 1.03%   |
| 5.5     | 12        | 0.88%   |
| 5.7     | 11        | 0.81%   |
| 4.9     | 11        | 0.81%   |
| 5.2     | 5         | 0.37%   |
| 4.4     | 4         | 0.29%   |
| 4.1     | 3         | 0.22%   |
| 5.1     | 2         | 0.15%   |
| 4.20    | 2         | 0.15%   |
| 3.16    | 2         | 0.15%   |
| 3.10    | 2         | 0.15%   |
| 4.8     | 1         | 0.07%   |
| 4.14    | 1         | 0.07%   |
| 4.13    | 1         | 0.07%   |
| 4.11    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1158      | 97.23%  |
| i686    | 29        | 2.43%   |
| i586    | 2         | 0.17%   |
| aarch64 | 2         | 0.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 578       | 45.33%  |
| KDE5            | 181       | 14.2%   |
| Unknown         | 146       | 11.45%  |
| X-Cinnamon      | 103       | 8.08%   |
| XFCE            | 94        | 7.37%   |
| KDE             | 32        | 2.51%   |
| MATE            | 28        | 2.2%    |
| Cinnamon        | 21        | 1.65%   |
| Pantheon        | 19        | 1.49%   |
| Unity           | 12        | 0.94%   |
| i3              | 12        | 0.94%   |
| LXQt            | 8         | 0.63%   |
| LXDE            | 8         | 0.63%   |
| KDE4            | 8         | 0.63%   |
| Deepin          | 6         | 0.47%   |
| Budgie          | 6         | 0.47%   |
| awesome         | 3         | 0.24%   |
| Openbox         | 2         | 0.16%   |
| GNOME Flashback | 2         | 0.16%   |
| sway            | 1         | 0.08%   |
| qtile           | 1         | 0.08%   |
| LeftWM          | 1         | 0.08%   |
| icewm           | 1         | 0.08%   |
| dusk            | 1         | 0.08%   |
| BunsenLabs      | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 961       | 77.69%  |
| Wayland | 168       | 13.58%  |
| Unknown | 81        | 6.55%   |
| Tty     | 27        | 2.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 690       | 55.29%  |
| GDM     | 158       | 12.66%  |
| SDDM    | 148       | 11.86%  |
| LightDM | 108       | 8.65%   |
| GDM3    | 91        | 7.29%   |
| TDM     | 39        | 3.13%   |
| KDM     | 8         | 0.64%   |
| SLiM    | 2         | 0.16%   |
| LXDM    | 2         | 0.16%   |
| XDM     | 1         | 0.08%   |
| GREETD  | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_AU        | 882       | 71.19%  |
| en_US        | 172       | 13.88%  |
| Unknown      | 131       | 10.57%  |
| C            | 27        | 2.18%   |
| en_GB        | 15        | 1.21%   |
| C.UTF8       | 4         | 0.32%   |
| zh_CN        | 1         | 0.08%   |
| ru_RU        | 1         | 0.08%   |
| fr_FR        | 1         | 0.08%   |
| es_ES        | 1         | 0.08%   |
| en_IN        | 1         | 0.08%   |
| en_GB.UTF-12 | 1         | 0.08%   |
| en_CA        | 1         | 0.08%   |
| de_DE        | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 628       | 51.22%  |
| BIOS | 598       | 48.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 954       | 77.56%  |
| Btrfs   | 106       | 8.62%   |
| Overlay | 84        | 6.83%   |
| Unknown | 39        | 3.17%   |
| Xfs     | 19        | 1.54%   |
| Zfs     | 13        | 1.06%   |
| Tmpfs   | 4         | 0.33%   |
| Ext2    | 4         | 0.33%   |
| XXXXXXX | 3         | 0.24%   |
| Ext3    | 3         | 0.24%   |
| F2fs    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 733       | 60.13%  |
| GPT     | 380       | 31.17%  |
| MBR     | 106       | 8.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1071      | 88.44%  |
| Yes       | 140       | 11.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 938       | 77.2%   |
| Yes       | 277       | 22.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 214       | 18%     |
| Dell                           | 208       | 17.49%  |
| Lenovo                         | 195       | 16.4%   |
| ASUSTek Computer               | 112       | 9.42%   |
| Acer                           | 108       | 9.08%   |
| Toshiba                        | 89        | 7.49%   |
| Apple                          | 82        | 6.9%    |
| MSI                            | 27        | 2.27%   |
| Alienware                      | 14        | 1.18%   |
| Samsung Electronics            | 13        | 1.09%   |
| Sony                           | 10        | 0.84%   |
| Notebook                       | 10        | 0.84%   |
| Gigabyte Technology            | 9         | 0.76%   |
| Timi                           | 8         | 0.67%   |
| Panasonic                      | 7         | 0.59%   |
| IT Channel Pty                 | 7         | 0.59%   |
| HUAWEI                         | 7         | 0.59%   |
| Razer                          | 6         | 0.5%    |
| Metabox                        | 6         | 0.5%    |
| Unknown                        | 6         | 0.5%    |
| System76                       | 4         | 0.34%   |
| AMI                            | 4         | 0.34%   |
| Medion                         | 3         | 0.25%   |
| LG Electronics                 | 3         | 0.25%   |
| Intel Client Systems           | 3         | 0.25%   |
| Google                         | 3         | 0.25%   |
| Framework                      | 3         | 0.25%   |
| Purism                         | 2         | 0.17%   |
| Pine Microsystems              | 2         | 0.17%   |
| Kogan                          | 2         | 0.17%   |
| IBM                            | 2         | 0.17%   |
| Valve                          | 1         | 0.08%   |
| Star Labs                      | 1         | 0.08%   |
| Pendo Industries               | 1         | 0.08%   |
| ONE-NETBOOK TECHNOLOGY         | 1         | 0.08%   |
| One Education                  | 1         | 0.08%   |
| OEM                            | 1         | 0.08%   |
| Matsushita Electric Industrial | 1         | 0.08%   |
| LEADER                         | 1         | 0.08%   |
| Intel                          | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| HP Pavilion dv6                                    | 14        | 1.18%   |
| HP Pavilion g6                                     | 11        | 0.93%   |
| HP Notebook                                        | 9         | 0.76%   |
| Unknown                                            | 9         | 0.76%   |
| HP Pavilion 15                                     | 8         | 0.67%   |
| Apple MacBookPro9,2                                | 7         | 0.59%   |
| Apple MacBookPro8,1                                | 6         | 0.5%    |
| Apple MacBookPro10,1                               | 6         | 0.5%    |
| Acer ConceptD CN315-71P                            | 6         | 0.5%    |
| Dell XPS 15 9570                                   | 5         | 0.42%   |
| Dell XPS 15 9560                                   | 5         | 0.42%   |
| Dell Latitude E7450                                | 5         | 0.42%   |
| Apple MacBookAir7,2                                | 5         | 0.42%   |
| Acer Aspire 5750G                                  | 5         | 0.42%   |
| Toshiba Satellite P750                             | 4         | 0.34%   |
| Toshiba Satellite L850                             | 4         | 0.34%   |
| Toshiba Satellite L500                             | 4         | 0.34%   |
| Toshiba Satellite L50-A                            | 4         | 0.34%   |
| Lenovo ThinkPad T470s W10DG 20JTS0HT00             | 4         | 0.34%   |
| Lenovo IdeaPad 1 14IGL05 81VU                      | 4         | 0.34%   |
| Lenovo G50-45 80E3                                 | 4         | 0.34%   |
| Dell XPS 15 9500                                   | 4         | 0.34%   |
| Dell XPS 15 7590                                   | 4         | 0.34%   |
| Dell XPS 13 9370                                   | 4         | 0.34%   |
| Dell XPS 13 9360                                   | 4         | 0.34%   |
| Dell XPS 13 7390                                   | 4         | 0.34%   |
| Dell Precision 5530                                | 4         | 0.34%   |
| Dell Latitude E7440                                | 4         | 0.34%   |
| Dell Latitude E6430                                | 4         | 0.34%   |
| Dell Inspiron 1545                                 | 4         | 0.34%   |
| Apple MacBookAir6,2                                | 4         | 0.34%   |
| Acer Swift SF514-54T                               | 4         | 0.34%   |
| Toshiba Satellite P850                             | 3         | 0.25%   |
| Toshiba Satellite L750                             | 3         | 0.25%   |
| Toshiba Satellite L50-B                            | 3         | 0.25%   |
| Toshiba Satellite C660                             | 3         | 0.25%   |
| Toshiba Satellite C50D-A                           | 3         | 0.25%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 3         | 0.25%   |
| Lenovo Yoga 3 Pro-1370 80HE                        | 3         | 0.25%   |
| HP ProBook 430 G2                                  | 3         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 127       | 10.68%  |
| Acer Aspire        | 75        | 6.31%   |
| Toshiba Satellite  | 73        | 6.14%   |
| Dell Latitude      | 69        | 5.8%    |
| HP Pavilion        | 60        | 5.05%   |
| Dell XPS           | 50        | 4.21%   |
| Dell Inspiron      | 50        | 4.21%   |
| HP EliteBook       | 41        | 3.45%   |
| Lenovo IdeaPad     | 30        | 2.52%   |
| HP ProBook         | 27        | 2.27%   |
| HP Laptop          | 20        | 1.68%   |
| Dell Precision     | 19        | 1.6%    |
| HP ENVY            | 12        | 1.01%   |
| Lenovo Yoga        | 11        | 0.93%   |
| ASUS ZenBook       | 10        | 0.84%   |
| Acer Swift         | 10        | 0.84%   |
| HP Notebook        | 9         | 0.76%   |
| ASUS VivoBook      | 9         | 0.76%   |
| Apple MacBookPro10 | 9         | 0.76%   |
| Unknown            | 9         | 0.76%   |
| Toshiba PORTEGE    | 8         | 0.67%   |
| HP 250             | 8         | 0.67%   |
| ASUS ROG           | 8         | 0.67%   |
| Apple MacBookPro9  | 8         | 0.67%   |
| Apple MacBookAir6  | 7         | 0.59%   |
| Toshiba TECRA      | 6         | 0.5%    |
| Razer Blade        | 6         | 0.5%    |
| Lenovo Legion      | 6         | 0.5%    |
| HP ZBook           | 6         | 0.5%    |
| ASUS TUF           | 6         | 0.5%    |
| Apple MacBookPro8  | 6         | 0.5%    |
| Apple MacBookPro11 | 6         | 0.5%    |
| Acer Nitro         | 6         | 0.5%    |
| Acer ConceptD      | 6         | 0.5%    |
| HP Presario        | 5         | 0.42%   |
| HP OMEN            | 5         | 0.42%   |
| HP Compaq          | 5         | 0.42%   |
| Dell G3            | 5         | 0.42%   |
| Apple MacBookPro6  | 5         | 0.42%   |
| Apple MacBookAir7  | 5         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 120       | 10.09%  |
| 2020    | 103       | 8.66%   |
| 2012    | 100       | 8.41%   |
| 2011    | 97        | 8.16%   |
| 2018    | 93        | 7.82%   |
| 2013    | 93        | 7.82%   |
| 2014    | 84        | 7.06%   |
| 2021    | 75        | 6.31%   |
| 2017    | 72        | 6.06%   |
| 2015    | 70        | 5.89%   |
| 2010    | 70        | 5.89%   |
| 2016    | 69        | 5.8%    |
| 2008    | 45        | 3.78%   |
| 2009    | 39        | 3.28%   |
| 2022    | 25        | 2.1%    |
| 2007    | 18        | 1.51%   |
| 2006    | 5         | 0.42%   |
| 2005    | 5         | 0.42%   |
| Unknown | 5         | 0.42%   |
| 2003    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1189      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1061      | 88.34%  |
| Enabled  | 140       | 11.66%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1181      | 99.33%  |
| Yes  | 8         | 0.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 341       | 28.3%   |
| 16.01-24.0  | 254       | 21.08%  |
| 3.01-4.0    | 252       | 20.91%  |
| 8.01-16.0   | 174       | 14.44%  |
| 32.01-64.0  | 98        | 8.13%   |
| 1.01-2.0    | 47        | 3.9%    |
| 64.01-256.0 | 13        | 1.08%   |
| 24.01-32.0  | 10        | 0.83%   |
| 2.01-3.0    | 9         | 0.75%   |
| 0.51-1.0    | 4         | 0.33%   |
| 0.01-0.5    | 3         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 482       | 35.23%  |
| 2.01-3.0   | 390       | 28.51%  |
| 4.01-8.0   | 164       | 11.99%  |
| 3.01-4.0   | 163       | 11.92%  |
| 0.51-1.0   | 86        | 6.29%   |
| 8.01-16.0  | 60        | 4.39%   |
| 0.01-0.5   | 15        | 1.1%    |
| 16.01-24.0 | 4         | 0.29%   |
| 24.01-32.0 | 2         | 0.15%   |
| 0          | 2         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 878       | 70.92%  |
| 2      | 280       | 22.62%  |
| 3      | 53        | 4.28%   |
| 0      | 16        | 1.29%   |
| 4      | 8         | 0.65%   |
| 5      | 2         | 0.16%   |
| 7      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 746       | 62.27%  |
| Yes       | 452       | 37.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 979       | 82.2%   |
| No        | 212       | 17.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1168      | 98.07%  |
| No        | 23        | 1.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 923       | 76.41%  |
| No        | 285       | 23.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 1189      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sydney         | 325       | 25.55%  |
| Melbourne      | 260       | 20.44%  |
| Brisbane       | 206       | 16.19%  |
| Perth          | 95        | 7.47%   |
| Adelaide       | 70        | 5.5%    |
| Canberra       | 22        | 1.73%   |
| Hobart         | 17        | 1.34%   |
| Launceston     | 7         | 0.55%   |
| Southport      | 6         | 0.47%   |
| Central Coast  | 6         | 0.47%   |
| Woolloongabba  | 5         | 0.39%   |
| Parramatta     | 5         | 0.39%   |
| Newcastle      | 5         | 0.39%   |
| Mitcham        | 5         | 0.39%   |
| Gold Coast     | 5         | 0.39%   |
| Wollongong     | 4         | 0.31%   |
| West End       | 4         | 0.31%   |
| Wahroonga      | 4         | 0.31%   |
| Traralgon      | 4         | 0.31%   |
| Point Cook     | 4         | 0.31%   |
| Mandurah       | 4         | 0.31%   |
| Geraldton      | 4         | 0.31%   |
| Artarmon       | 4         | 0.31%   |
| Alexandria     | 4         | 0.31%   |
| Townsville     | 3         | 0.24%   |
| Surry Hills    | 3         | 0.24%   |
| Spring Field   | 3         | 0.24%   |
| Richmond       | 3         | 0.24%   |
| Parkdale       | 3         | 0.24%   |
| Mount Waverley | 3         | 0.24%   |
| Hawthorn       | 3         | 0.24%   |
| Geelong        | 3         | 0.24%   |
| Doncaster      | 3         | 0.24%   |
| Clifton Hill   | 3         | 0.24%   |
| Brighton       | 3         | 0.24%   |
| Warragul       | 2         | 0.16%   |
| Sandy Bay      | 2         | 0.16%   |
| Ryde           | 2         | 0.16%   |
| Redfern        | 2         | 0.16%   |
| Quinns Rocks   | 2         | 0.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 264       | 336    | 17.85%  |
| Seagate                   | 168       | 247    | 11.36%  |
| WDC                       | 167       | 239    | 11.29%  |
| Toshiba                   | 138       | 202    | 9.33%   |
| Unknown                   | 67        | 90     | 4.53%   |
| SanDisk                   | 67        | 87     | 4.53%   |
| Intel                     | 65        | 97     | 4.39%   |
| Kingston                  | 61        | 76     | 4.12%   |
| SK hynix                  | 55        | 72     | 3.72%   |
| Crucial                   | 54        | 70     | 3.65%   |
| Hitachi                   | 52        | 64     | 3.52%   |
| Apple                     | 49        | 67     | 3.31%   |
| HGST                      | 41        | 59     | 2.77%   |
| Micron Technology         | 39        | 49     | 2.64%   |
| KIOXIA                    | 17        | 19     | 1.15%   |
| Phison                    | 13        | 16     | 0.88%   |
| Fujitsu                   | 13        | 17     | 0.88%   |
| LITEON                    | 12        | 15     | 0.81%   |
| A-DATA Technology         | 10        | 13     | 0.68%   |
| LITEONIT                  | 8         | 10     | 0.54%   |
| Phison Electronics        | 6         | 7      | 0.41%   |
| OCZ                       | 6         | 8      | 0.41%   |
| JMicron Technology        | 6         | 8      | 0.41%   |
| SPCC                      | 5         | 7      | 0.34%   |
| Micron/Crucial Technology | 5         | 5      | 0.34%   |
| KingSpec                  | 5         | 8      | 0.34%   |
| Transcend                 | 4         | 6      | 0.27%   |
| Patriot                   | 4         | 5      | 0.27%   |
| China                     | 4         | 4      | 0.27%   |
| ASMT                      | 4         | 5      | 0.27%   |
| XPG                       | 3         | 3      | 0.2%    |
| OWC                       | 3         | 6      | 0.2%    |
| Lite-On                   | 3         | 3      | 0.2%    |
| LaCie                     | 3         | 7      | 0.2%    |
| Unknown                   | 3         | 4      | 0.2%    |
| TO Exter                  | 2         | 2      | 0.14%   |
| Realtek Semiconductor     | 2         | 3      | 0.14%   |
| Plextor                   | 2         | 6      | 0.14%   |
| Lenovo                    | 2         | 3      | 0.14%   |
| KingFast                  | 2         | 2      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 18        | 1.17%   |
| Toshiba MQ01ABD100 1TB                              | 17        | 1.1%    |
| Unknown MMC Card  64GB                              | 16        | 1.04%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 0.91%   |
| Toshiba MQ01ABF050 500GB                            | 13        | 0.84%   |
| Seagate ST500LT012-1DG142 500GB                     | 13        | 0.84%   |
| Seagate Expansion 240GB                             | 13        | 0.84%   |
| Samsung NVMe SSD Drive 512GB                        | 13        | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB                      | 12        | 0.78%   |
| Samsung SSD 860 EVO 500GB                           | 12        | 0.78%   |
| Unknown MMC Card  32GB                              | 10        | 0.65%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 10        | 0.65%   |
| HGST HTS721010A9E630 1TB                            | 10        | 0.65%   |
| SK hynix NVMe SSD Drive 256GB                       | 9         | 0.58%   |
| Seagate ST2000LM007-1R8174 2TB                      | 9         | 0.58%   |
| Samsung SSD 850 EVO 250GB                           | 9         | 0.58%   |
| Kingston SA400S37240G 240GB SSD                     | 9         | 0.58%   |
| Crucial CT500MX500SSD1 500GB                        | 9         | 0.58%   |
| Crucial CT1000MX500SSD1 1TB                         | 9         | 0.58%   |
| Unknown MMC Card  128GB                             | 8         | 0.52%   |
| Toshiba NVMe SSD Drive 512GB                        | 8         | 0.52%   |
| Toshiba MQ04ABF100 1TB                              | 8         | 0.52%   |
| Toshiba MQ01ABD075 752GB                            | 8         | 0.52%   |
| Seagate ST9500325AS 500GB                           | 8         | 0.52%   |
| SanDisk NVMe SSD Drive 256GB                        | 8         | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 8         | 0.52%   |
| Intel NVMe SSD Drive 512GB                          | 8         | 0.52%   |
| HGST HTS545050A7E680 500GB                          | 8         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 7         | 0.45%   |
| Samsung NVMe SSD Drive 500GB                        | 7         | 0.45%   |
| Micron NVMe SSD Drive 512GB                         | 7         | 0.45%   |
| Kingston SA400S37120G 120GB SSD                     | 7         | 0.45%   |
| Hitachi HTS547575A9E384 752GB                       | 7         | 0.45%   |
| Hitachi HTS545050B9A300 500GB                       | 7         | 0.45%   |
| HGST HTS725050A7E630 500GB                          | 7         | 0.45%   |
| HGST HTS541010A9E680 1TB                            | 7         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 6         | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 6         | 0.39%   |
| Unknown MMC Card  16GB                              | 6         | 0.39%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 6         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 163       | 240    | 32.47%  |
| WDC                 | 113       | 162    | 22.51%  |
| Toshiba             | 86        | 133    | 17.13%  |
| Hitachi             | 52        | 64     | 10.36%  |
| HGST                | 41        | 59     | 8.17%   |
| Fujitsu             | 13        | 17     | 2.59%   |
| Samsung Electronics | 12        | 14     | 2.39%   |
| Apple               | 5         | 6      | 1%      |
| Unknown             | 4         | 4      | 0.8%    |
| LaCie               | 3         | 6      | 0.6%    |
| ASMT                | 3         | 4      | 0.6%    |
| KESU                | 2         | 2      | 0.4%    |
| HGST HUS            | 2         | 2      | 0.4%    |
| USB                 | 1         | 2      | 0.2%    |
| IBM/Hitachi         | 1         | 1      | 0.2%    |
| AAPL                | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 139       | 176    | 29.14%  |
| Crucial             | 47        | 63     | 9.85%   |
| Kingston            | 41        | 53     | 8.6%    |
| SanDisk             | 33        | 42     | 6.92%   |
| Apple               | 32        | 37     | 6.71%   |
| WDC                 | 26        | 33     | 5.45%   |
| Intel               | 23        | 41     | 4.82%   |
| Toshiba             | 21        | 29     | 4.4%    |
| SK hynix            | 19        | 25     | 3.98%   |
| Micron Technology   | 14        | 14     | 2.94%   |
| LITEON              | 11        | 14     | 2.31%   |
| LITEONIT            | 8         | 10     | 1.68%   |
| OCZ                 | 6         | 8      | 1.26%   |
| A-DATA Technology   | 6         | 8      | 1.26%   |
| SPCC                | 5         | 7      | 1.05%   |
| JMicron Technology  | 5         | 6      | 1.05%   |
| Transcend           | 4         | 6      | 0.84%   |
| Patriot             | 4         | 5      | 0.84%   |
| KingSpec            | 4         | 7      | 0.84%   |
| China               | 4         | 4      | 0.84%   |
| Seagate             | 3         | 4      | 0.63%   |
| OWC                 | 3         | 6      | 0.63%   |
| TO Exter            | 2         | 2      | 0.42%   |
| Plextor             | 2         | 6      | 0.42%   |
| FORESEE             | 2         | 2      | 0.42%   |
| T-CREATE            | 1         | 1      | 0.21%   |
| SAMSWEET            | 1         | 1      | 0.21%   |
| Mushkin             | 1         | 1      | 0.21%   |
| Kston               | 1         | 1      | 0.21%   |
| KingFast            | 1         | 1      | 0.21%   |
| KingDian            | 1         | 1      | 0.21%   |
| Gigabyte Technology | 1         | 1      | 0.21%   |
| Drevo               | 1         | 1      | 0.21%   |
| Corsair             | 1         | 1      | 0.21%   |
| Colorful            | 1         | 1      | 0.21%   |
| BP4e                | 1         | 2      | 0.21%   |
| BIWIN               | 1         | 1      | 0.21%   |
| addlink             | 1         | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 473       | 717    | 33.91%  |
| SSD     | 447       | 622    | 32.04%  |
| NVMe    | 390       | 552    | 27.96%  |
| MMC     | 63        | 84     | 4.52%   |
| Unknown | 22        | 24     | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 815       | 1252   | 60.55%  |
| NVMe | 390       | 549    | 28.97%  |
| SAS  | 78        | 114    | 5.79%   |
| MMC  | 63        | 84     | 4.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 604       | 876    | 65.3%   |
| 0.51-1.0   | 255       | 362    | 27.57%  |
| 1.01-2.0   | 48        | 73     | 5.19%   |
| 4.01-10.0  | 10        | 18     | 1.08%   |
| 3.01-4.0   | 8         | 10     | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 342       | 26.78%  |
| 251-500        | 311       | 24.35%  |
| 501-1000       | 206       | 16.13%  |
| 1-20           | 118       | 9.24%   |
| 51-100         | 91        | 7.13%   |
| 1001-2000      | 85        | 6.66%   |
| More than 3000 | 36        | 2.82%   |
| 21-50          | 33        | 2.58%   |
| Unknown        | 29        | 2.27%   |
| 2001-3000      | 26        | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 575       | 42.4%   |
| 21-50          | 251       | 18.51%  |
| 51-100         | 148       | 10.91%  |
| 101-250        | 144       | 10.62%  |
| 251-500        | 105       | 7.74%   |
| 501-1000       | 57        | 4.2%    |
| Unknown        | 29        | 2.14%   |
| 1001-2000      | 26        | 1.92%   |
| More than 3000 | 11        | 0.81%   |
| 2001-3000      | 9         | 0.66%   |
| 0              | 1         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 4.92%   |
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 3.28%   |
| Seagate ST9500325AS 500GB               | 2         | 2      | 3.28%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 3.28%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 3.28%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 2      | 3.28%   |
| HGST HTS545050A7E680 500GB              | 2         | 3      | 3.28%   |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 2      | 1.64%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 2      | 1.64%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 3      | 1.64%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1         | 1      | 1.64%   |
| WDC WD2500BEVT-35A23T0 250GB            | 1         | 1      | 1.64%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 2      | 1.64%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 2      | 1.64%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 1.64%   |
| Toshiba MK5055GSX 500GB                 | 1         | 4      | 1.64%   |
| Toshiba MK3265GSX 320GB                 | 1         | 1      | 1.64%   |
| Seagate ST9500423AS 500GB               | 1         | 2      | 1.64%   |
| Seagate ST9500325ASG 500GB              | 1         | 1      | 1.64%   |
| Seagate ST9320423AS 320GB               | 1         | 2      | 1.64%   |
| Seagate ST9250410AS 250GB               | 1         | 1      | 1.64%   |
| Seagate ST9250315AS 250GB               | 1         | 1      | 1.64%   |
| Seagate ST9160821AS 160GB               | 1         | 4      | 1.64%   |
| Seagate ST9160310AS 160GB               | 1         | 1      | 1.64%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 2      | 1.64%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 2      | 1.64%   |
| Seagate ST320LT007-9ZV142 320GB         | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 970 EVO 2TB     | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 850 EVO 1TB     | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 750 EVO 250GB   | 1         | 1      | 1.64%   |
| Samsung Electronics PM961 NVMe 512GB    | 1         | 1      | 1.64%   |
| Samsung Electronics HM641JI 640GB       | 1         | 1      | 1.64%   |
| Kingston SV300S37A240G 240GB SSD        | 1         | 1      | 1.64%   |
| KingSpec PA25-128 128GB SSD             | 1         | 3      | 1.64%   |
| Intel SSDSC2CW060A3 64GB                | 1         | 2      | 1.64%   |
| Hitachi HTS725050A7E630 500GB           | 1         | 1      | 1.64%   |
| Hitachi HTS547564A9E384 640GB           | 1         | 1      | 1.64%   |
| Hitachi HTS547550A9E384 500GB           | 1         | 1      | 1.64%   |
| Hitachi HTS545050A7E380 500GB           | 1         | 1      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 27     | 31.15%  |
| Hitachi             | 8         | 8      | 13.11%  |
| WDC                 | 7         | 13     | 11.48%  |
| Toshiba             | 6         | 9      | 9.84%   |
| Samsung Electronics | 5         | 5      | 8.2%    |
| HGST                | 4         | 5      | 6.56%   |
| Kingston            | 3         | 3      | 4.92%   |
| Fujitsu             | 3         | 3      | 4.92%   |
| Crucial             | 2         | 2      | 3.28%   |
| KingSpec            | 1         | 3      | 1.64%   |
| Intel               | 1         | 2      | 1.64%   |
| Apple               | 1         | 1      | 1.64%   |
| A-DATA Technology   | 1         | 1      | 1.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 27     | 40.43%  |
| Hitachi             | 8         | 8      | 17.02%  |
| WDC                 | 7         | 13     | 14.89%  |
| Toshiba             | 5         | 8      | 10.64%  |
| HGST                | 4         | 5      | 8.51%   |
| Fujitsu             | 3         | 3      | 6.38%   |
| Samsung Electronics | 1         | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 46        | 65     | 76.67%  |
| SSD  | 12        | 15     | 20%     |
| NVMe | 2         | 2      | 3.33%   |

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
| Detected | 782       | 1307   | 62.81%  |
| Works    | 403       | 610    | 32.37%  |
| Malfunc  | 60        | 82     | 4.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 850       | 61.28%  |
| Samsung Electronics              | 136       | 9.81%   |
| AMD                              | 117       | 8.44%   |
| SanDisk                          | 61        | 4.4%    |
| SK hynix                         | 36        | 2.6%    |
| Toshiba America Info Systems     | 31        | 2.24%   |
| Micron Technology                | 25        | 1.8%    |
| Phison Electronics               | 21        | 1.51%   |
| Kingston Technology Company      | 21        | 1.51%   |
| KIOXIA                           | 15        | 1.08%   |
| Nvidia                           | 14        | 1.01%   |
| Micron/Crucial Technology        | 12        | 0.87%   |
| Apple                            | 12        | 0.87%   |
| ADATA Technology                 | 8         | 0.58%   |
| Marvell Technology Group         | 7         | 0.5%    |
| Lite-On Technology               | 4         | 0.29%   |
| Silicon Motion                   | 3         | 0.22%   |
| Union Memory (Shenzhen)          | 2         | 0.14%   |
| Solid State Storage Technology   | 2         | 0.14%   |
| Silicon Integrated Systems [SiS] | 2         | 0.14%   |
| Realtek Semiconductor            | 2         | 0.14%   |
| Lenovo                           | 2         | 0.14%   |
| ULi Electronics                  | 1         | 0.07%   |
| Shenzhen Longsys Electronics     | 1         | 0.07%   |
| JMicron Technology               | 1         | 0.07%   |
| ASMedia Technology               | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 103       | 6.97%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 103       | 6.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 92        | 6.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 85        | 5.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 76        | 5.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 74        | 5.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 50        | 3.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 48        | 3.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 45        | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 39        | 2.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 33        | 2.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 32        | 2.17%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 31        | 2.1%    |
| Micron Non-Volatile memory controller                                                  | 25        | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 24        | 1.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 22        | 1.49%   |
| Samsung NVMe SSD Controller 980                                                        | 20        | 1.35%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 18        | 1.22%   |
| Intel SSD 660P Series                                                                  | 17        | 1.15%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 16        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 15        | 1.02%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 15        | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 15        | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 15        | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 14        | 0.95%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 12        | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 11        | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 11        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 11        | 0.74%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 10        | 0.68%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 10        | 0.68%   |
| Phison E12 NVMe Controller                                                             | 10        | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 9         | 0.61%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                   | 9         | 0.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 9         | 0.61%   |
| Samsung Electronics SATA controller                                                    | 9         | 0.61%   |
| Phison PS5013 E13 NVMe Controller                                                      | 9         | 0.61%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 9         | 0.61%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 9         | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 9         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 828       | 58.35%  |
| NVMe | 393       | 27.7%   |
| RAID | 127       | 8.95%   |
| IDE  | 71        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1025      | 86.21%  |
| AMD    | 162       | 13.62%  |
| ARM    | 2         | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 30        | 2.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 24        | 2.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 21        | 1.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 21        | 1.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 18        | 1.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 16        | 1.34%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 16        | 1.34%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 16        | 1.34%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 15        | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 14        | 1.18%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 14        | 1.18%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 13        | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 13        | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 1.09%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 13        | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 13        | 1.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 12        | 1.01%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 11        | 0.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 11        | 0.92%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 11        | 0.92%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 11        | 0.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 11        | 0.92%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 10        | 0.84%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 10        | 0.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 10        | 0.84%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 10        | 0.84%   |
| Intel Core i7-3740QM CPU @ 2.70GHz      | 9         | 0.76%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 9         | 0.76%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 9         | 0.76%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 9         | 0.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 9         | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 9         | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 9         | 0.76%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 9         | 0.76%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 8         | 0.67%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 8         | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 7         | 0.59%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 7         | 0.59%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 7         | 0.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 7         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 410       | 34.45%  |
| Intel Core i5                  | 304       | 25.55%  |
| Other                          | 81        | 6.81%   |
| Intel Core 2 Duo               | 55        | 4.62%   |
| Intel Core i3                  | 52        | 4.37%   |
| Intel Celeron                  | 43        | 3.61%   |
| AMD Ryzen 7                    | 30        | 2.52%   |
| AMD Ryzen 5                    | 26        | 2.18%   |
| Intel Pentium                  | 24        | 2.02%   |
| AMD A6                         | 19        | 1.6%    |
| AMD A4                         | 16        | 1.34%   |
| Intel Atom                     | 15        | 1.26%   |
| AMD Ryzen 9                    | 7         | 0.59%   |
| AMD E2                         | 7         | 0.59%   |
| AMD E1                         | 7         | 0.59%   |
| Intel Pentium Dual-Core        | 6         | 0.5%    |
| Intel Genuine                  | 6         | 0.5%    |
| Intel Core i9                  | 6         | 0.5%    |
| Intel Core 2                   | 6         | 0.5%    |
| AMD Ryzen 7 PRO                | 6         | 0.5%    |
| AMD A8                         | 6         | 0.5%    |
| AMD A10                        | 6         | 0.5%    |
| Intel Core m3                  | 5         | 0.42%   |
| Intel Core M                   | 5         | 0.42%   |
| Intel Xeon                     | 4         | 0.34%   |
| Intel Celeron Dual-Core        | 4         | 0.34%   |
| AMD Ryzen 3                    | 4         | 0.34%   |
| AMD E                          | 4         | 0.34%   |
| Intel Pentium M                | 2         | 0.17%   |
| Intel Pentium Dual             | 2         | 0.17%   |
| Intel Core m7                  | 2         | 0.17%   |
| Intel Core Duo                 | 2         | 0.17%   |
| Intel Celeron M                | 2         | 0.17%   |
| AMD V120                       | 2         | 0.17%   |
| AMD FX                         | 2         | 0.17%   |
| AMD A12                        | 2         | 0.17%   |
| Intel Mobile Pentium 4         | 1         | 0.08%   |
| Intel Core m5                  | 1         | 0.08%   |
| AMD V140                       | 1         | 0.08%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 581       | 48.86%  |
| 4      | 405       | 34.06%  |
| 6      | 101       | 8.49%   |
| 8      | 59        | 4.96%   |
| 1      | 30        | 2.52%   |
| 14     | 5         | 0.42%   |
| 12     | 4         | 0.34%   |
| 10     | 3         | 0.25%   |
| 16     | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1187      | 99.83%  |
| 2      | 2         | 0.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 941       | 79.08%  |
| 1      | 247       | 20.76%  |
| 8      | 1         | 0.08%   |
| 4      | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1163      | 97.16%  |
| 32-bit         | 17        | 1.42%   |
| Unknown        | 16        | 1.34%   |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 297       | 23.93%  |
| 0x206a7    | 82        | 6.61%   |
| 0x306a9    | 77        | 6.2%    |
| 0x40651    | 49        | 3.95%   |
| 0x906ea    | 48        | 3.87%   |
| 0x406e3    | 47        | 3.79%   |
| 0x806ec    | 40        | 3.22%   |
| 0x306d4    | 39        | 3.14%   |
| 0x1067a    | 38        | 3.06%   |
| 0x806ea    | 36        | 2.9%    |
| 0x20655    | 35        | 2.82%   |
| 0x306c3    | 34        | 2.74%   |
| 0x806c1    | 32        | 2.58%   |
| 0x806e9    | 28        | 2.26%   |
| 0xa0652    | 21        | 1.69%   |
| 0x906e9    | 21        | 1.69%   |
| 0x20652    | 19        | 1.53%   |
| 0x806eb    | 14        | 1.13%   |
| 0x0a50000c | 14        | 1.13%   |
| 0x06006705 | 14        | 1.13%   |
| 0x706e5    | 13        | 1.05%   |
| 0x07030105 | 13        | 1.05%   |
| 0x806d1    | 12        | 0.97%   |
| 0x506e3    | 12        | 0.97%   |
| 0x30678    | 12        | 0.97%   |
| 0x106e5    | 11        | 0.89%   |
| 0x0700010f | 11        | 0.89%   |
| 0x10676    | 10        | 0.81%   |
| 0x08108109 | 9         | 0.73%   |
| 0x906a3    | 8         | 0.64%   |
| 0x08108102 | 8         | 0.64%   |
| 0x406c4    | 7         | 0.56%   |
| 0x406c3    | 7         | 0.56%   |
| 0x06001119 | 7         | 0.56%   |
| 0x6fd      | 6         | 0.48%   |
| 0x6f6      | 6         | 0.48%   |
| 0x08600103 | 6         | 0.48%   |
| 0x506c9    | 5         | 0.4%    |
| 0x08608103 | 5         | 0.4%    |
| 0x08600106 | 5         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 241       | 20.25%  |
| IvyBridge        | 110       | 9.24%   |
| Haswell          | 109       | 9.16%   |
| SandyBridge      | 100       | 8.4%    |
| Skylake          | 79        | 6.64%   |
| Westmere         | 62        | 5.21%   |
| Penryn           | 59        | 4.96%   |
| Broadwell        | 46        | 3.87%   |
| TigerLake        | 39        | 3.28%   |
| CometLake        | 36        | 3.03%   |
| IceLake          | 30        | 2.52%   |
| Silvermont       | 29        | 2.44%   |
| Excavator        | 24        | 2.02%   |
| Unknown          | 21        | 1.76%   |
| Zen+             | 19        | 1.6%    |
| Zen 2            | 19        | 1.6%    |
| Zen 3            | 18        | 1.51%   |
| Core             | 18        | 1.51%   |
| Puma             | 17        | 1.43%   |
| Nehalem          | 12        | 1.01%   |
| Jaguar           | 12        | 1.01%   |
| P6               | 11        | 0.92%   |
| Alderlake Hybrid | 10        | 0.84%   |
| Zen              | 9         | 0.76%   |
| Piledriver       | 9         | 0.76%   |
| Goldmont plus    | 9         | 0.76%   |
| Bonnell          | 8         | 0.67%   |
| Goldmont         | 7         | 0.59%   |
| K10 Llano        | 6         | 0.5%    |
| K10              | 6         | 0.5%    |
| Bobcat           | 5         | 0.42%   |
| Tremont          | 3         | 0.25%   |
| Steamroller      | 3         | 0.25%   |
| K8 & K10 hybrid  | 2         | 0.17%   |
| NetBurst         | 1         | 0.08%   |
| K8 Hammer        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 894       | 57.75%  |
| Nvidia                           | 395       | 25.52%  |
| AMD                              | 255       | 16.47%  |
| Silicon Integrated Systems [SiS] | 2         | 0.13%   |
| Neomagic                         | 2         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 96        | 6%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 89        | 5.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 60        | 3.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 59        | 3.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 58        | 3.62%   |
| Intel UHD Graphics 620                                                                   | 48        | 3%      |
| Intel Core Processor Integrated Graphics Controller                                      | 43        | 2.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 42        | 2.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 37        | 2.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 33        | 2.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 32        | 2%      |
| Intel HD Graphics 5500                                                                   | 32        | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 1.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 1.69%   |
| Intel HD Graphics 620                                                                    | 25        | 1.56%   |
| Intel HD Graphics 630                                                                    | 21        | 1.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 1.31%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 20        | 1.25%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 18        | 1.12%   |
| AMD Renoir                                                                               | 18        | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 15        | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 0.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 14        | 0.87%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 14        | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 0.87%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 13        | 0.81%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 13        | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 0.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 12        | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 11        | 0.69%   |
| Intel HD Graphics 530                                                                    | 11        | 0.69%   |
| Intel Iris Plus Graphics G7                                                              | 10        | 0.62%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 9         | 0.56%   |
| Nvidia GM108M [GeForce 840M]                                                             | 9         | 0.56%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 9         | 0.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 559       | 46.66%  |
| Intel + Nvidia           | 283       | 23.62%  |
| 1 x AMD                  | 151       | 12.6%   |
| 1 x Nvidia               | 90        | 7.51%   |
| Intel + AMD              | 47        | 3.92%   |
| 2 x AMD                  | 35        | 2.92%   |
| AMD + Nvidia             | 22        | 1.84%   |
| Other                    | 2         | 0.17%   |
| 2 x Intel                | 2         | 0.17%   |
| 1 x SiS                  | 2         | 0.17%   |
| 1 x Neomagic             | 2         | 0.17%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.17%   |
| 2 x Nvidia               | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 989       | 80.87%  |
| Proprietary | 194       | 15.86%  |
| Unknown     | 40        | 3.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 751       | 61.06%  |
| 1.01-2.0   | 145       | 11.79%  |
| 0.01-0.5   | 124       | 10.08%  |
| 3.01-4.0   | 82        | 6.67%   |
| 0.51-1.0   | 76        | 6.18%   |
| 5.01-6.0   | 23        | 1.87%   |
| 7.01-8.0   | 18        | 1.46%   |
| 2.01-3.0   | 8         | 0.65%   |
| 8.01-16.0  | 3         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 283       | 20.36%  |
| LG Display              | 202       | 14.53%  |
| Chimei Innolux          | 150       | 10.79%  |
| Samsung Electronics     | 135       | 9.71%   |
| BOE                     | 115       | 8.27%   |
| Apple                   | 81        | 5.83%   |
| Sharp                   | 58        | 4.17%   |
| Dell                    | 41        | 2.95%   |
| Chi Mei Optoelectronics | 38        | 2.73%   |
| Lenovo                  | 28        | 2.01%   |
| Hewlett-Packard         | 22        | 1.58%   |
| Goldstar                | 21        | 1.51%   |
| BenQ                    | 19        | 1.37%   |
| PANDA                   | 18        | 1.29%   |
| Acer                    | 18        | 1.29%   |
| Philips                 | 17        | 1.22%   |
| Sony                    | 11        | 0.79%   |
| AOC                     | 9         | 0.65%   |
| Ancor Communications    | 8         | 0.58%   |
| ViewSonic               | 6         | 0.43%   |
| Toshiba                 | 6         | 0.43%   |
| LG Philips              | 6         | 0.43%   |
| CPT                     | 6         | 0.43%   |
| Unknown                 | 5         | 0.36%   |
| Panasonic               | 5         | 0.36%   |
| LGD                     | 5         | 0.36%   |
| InfoVision              | 5         | 0.36%   |
| Hitachi                 | 5         | 0.36%   |
| SAC                     | 4         | 0.29%   |
| Kogan                   | 4         | 0.29%   |
| HannStar                | 4         | 0.29%   |
| GKK                     | 4         | 0.29%   |
| eMachines               | 4         | 0.29%   |
| CSO                     | 4         | 0.29%   |
| ASUSTek Computer        | 4         | 0.29%   |
| InnoLux Display         | 3         | 0.22%   |
| GDH                     | 3         | 0.22%   |
| Unknown (XXX)           | 2         | 0.14%   |
| TMX                     | 2         | 0.14%   |
| TCL                     | 2         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 1.13%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.77%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 9         | 0.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 8         | 0.56%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 8         | 0.56%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.49%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 7         | 0.49%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 6         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 6         | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 6         | 0.42%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                     | 6         | 0.42%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 6         | 0.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.42%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 6         | 0.42%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 5         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.35%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.35%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 5         | 0.35%   |
| LG Display LCD Monitor LGD0469 1920x1080 380x210mm 17.1-inch             | 5         | 0.35%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 5         | 0.35%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 0.35%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 5         | 0.35%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 5         | 0.35%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 4         | 0.28%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.28%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 4         | 0.28%   |
| eMachines E190HQV EMA0212 1366x768 409x230mm 18.5-inch                   | 4         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 4         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 4         | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch | 4         | 0.28%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 4         | 0.28%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.28%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 4         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 494       | 38.38%  |
| 1366x768 (WXGA)    | 404       | 31.39%  |
| 3840x2160 (4K)     | 80        | 6.22%   |
| 1280x800 (WXGA)    | 55        | 4.27%   |
| 1600x900 (HD+)     | 45        | 3.5%    |
| 1440x900 (WXGA+)   | 30        | 2.33%   |
| 2560x1440 (QHD)    | 24        | 1.86%   |
| 1920x1200 (WUXGA)  | 20        | 1.55%   |
| 2560x1600          | 18        | 1.4%    |
| 2880x1800          | 16        | 1.24%   |
| 1680x1050 (WSXGA+) | 12        | 0.93%   |
| 1280x1024 (SXGA)   | 10        | 0.78%   |
| 3840x2400          | 9         | 0.7%    |
| 3200x1800 (QHD+)   | 8         | 0.62%   |
| 3440x1440          | 7         | 0.54%   |
| 1024x600           | 6         | 0.47%   |
| 1360x768           | 5         | 0.39%   |
| Unknown            | 5         | 0.39%   |
| 3072x1920          | 4         | 0.31%   |
| 2160x1440          | 4         | 0.31%   |
| 3840x1080          | 3         | 0.23%   |
| 2256x1504          | 3         | 0.23%   |
| 2240x1400          | 3         | 0.23%   |
| 5760x2160          | 2         | 0.16%   |
| 3456x2160          | 2         | 0.16%   |
| 3286x1080          | 2         | 0.16%   |
| 3200x2000          | 2         | 0.16%   |
| 2304x1440          | 2         | 0.16%   |
| 1280x720 (HD)      | 2         | 0.16%   |
| 1024x768 (XGA)     | 2         | 0.16%   |
| 800x1280           | 1         | 0.08%   |
| 3840x1600          | 1         | 0.08%   |
| 3000x2000          | 1         | 0.08%   |
| 2726x768           | 1         | 0.08%   |
| 2288x1287          | 1         | 0.08%   |
| 1920x540           | 1         | 0.08%   |
| 1720x1440          | 1         | 0.08%   |
| 1680x945           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 556       | 40.09%  |
| 13      | 199       | 14.35%  |
| 14      | 145       | 10.45%  |
| 17      | 89        | 6.42%   |
| 27      | 60        | 4.33%   |
| 12      | 44        | 3.17%   |
| 24      | 43        | 3.1%    |
| 23      | 35        | 2.52%   |
| 11      | 33        | 2.38%   |
| 21      | 26        | 1.87%   |
| Unknown | 24        | 1.73%   |
| 31      | 17        | 1.23%   |
| 16      | 13        | 0.94%   |
| 84      | 10        | 0.72%   |
| 19      | 10        | 0.72%   |
| 18      | 10        | 0.72%   |
| 72      | 8         | 0.58%   |
| 22      | 7         | 0.5%    |
| 10      | 7         | 0.5%    |
| 40      | 6         | 0.43%   |
| 20      | 6         | 0.43%   |
| 52      | 5         | 0.36%   |
| 34      | 5         | 0.36%   |
| 54      | 4         | 0.29%   |
| 26      | 3         | 0.22%   |
| 48      | 2         | 0.14%   |
| 46      | 2         | 0.14%   |
| 37      | 2         | 0.14%   |
| 35      | 2         | 0.14%   |
| 32      | 2         | 0.14%   |
| 8       | 2         | 0.14%   |
| 142     | 1         | 0.07%   |
| 78      | 1         | 0.07%   |
| 63      | 1         | 0.07%   |
| 55      | 1         | 0.07%   |
| 49      | 1         | 0.07%   |
| 38      | 1         | 0.07%   |
| 29      | 1         | 0.07%   |
| 25      | 1         | 0.07%   |
| 9       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 772       | 56.15%  |
| 201-300        | 204       | 14.84%  |
| 501-600        | 120       | 8.73%   |
| 351-400        | 116       | 8.44%   |
| 401-500        | 53        | 3.85%   |
| 601-700        | 29        | 2.11%   |
| Unknown        | 24        | 1.75%   |
| 1501-2000      | 19        | 1.38%   |
| 1001-1500      | 16        | 1.16%   |
| 801-900        | 11        | 0.8%    |
| 701-800        | 7         | 0.51%   |
| 101-200        | 2         | 0.15%   |
| More than 2000 | 1         | 0.07%   |
| 1-100          | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 968       | 81%     |
| 16/10   | 165       | 13.81%  |
| Unknown | 18        | 1.51%   |
| 3/2     | 14        | 1.17%   |
| 5/4     | 8         | 0.67%   |
| 21/9    | 8         | 0.67%   |
| 4/3     | 6         | 0.5%    |
| 32/9    | 4         | 0.33%   |
| 6/5     | 1         | 0.08%   |
| 1.00    | 1         | 0.08%   |
| 0.67    | 1         | 0.08%   |
| 0.62    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 556       | 40.23%  |
| 81-90          | 260       | 18.81%  |
| 201-250        | 93        | 6.73%   |
| 71-80          | 88        | 6.37%   |
| 121-130        | 78        | 5.64%   |
| 301-350        | 62        | 4.49%   |
| 61-70          | 40        | 2.89%   |
| 51-60          | 33        | 2.39%   |
| More than 1000 | 30        | 2.17%   |
| 351-500        | 27        | 1.95%   |
| 151-200        | 25        | 1.81%   |
| Unknown        | 24        | 1.74%   |
| 501-1000       | 14        | 1.01%   |
| 111-120        | 12        | 0.87%   |
| 141-150        | 10        | 0.72%   |
| 251-300        | 9         | 0.65%   |
| 41-50          | 8         | 0.58%   |
| 131-140        | 8         | 0.58%   |
| 1-40           | 3         | 0.22%   |
| 91-100         | 2         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 484       | 36.04%  |
| 101-120       | 400       | 29.78%  |
| 51-100        | 227       | 16.9%   |
| 161-240       | 108       | 8.04%   |
| More than 240 | 75        | 5.58%   |
| 1-50          | 25        | 1.86%   |
| Unknown       | 24        | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 962       | 77.71%  |
| 2     | 202       | 16.32%  |
| 0     | 38        | 3.07%   |
| 3     | 31        | 2.5%    |
| 4     | 5         | 0.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 654       | 33.5%   |
| Realtek Semiconductor             | 598       | 30.64%  |
| Qualcomm Atheros                  | 270       | 13.83%  |
| Broadcom                          | 149       | 7.63%   |
| Broadcom Limited                  | 45        | 2.31%   |
| Ralink                            | 25        | 1.28%   |
| Sierra Wireless                   | 17        | 0.87%   |
| Marvell Technology Group          | 16        | 0.82%   |
| MediaTek                          | 13        | 0.67%   |
| DisplayLink                       | 13        | 0.67%   |
| Samsung Electronics               | 12        | 0.61%   |
| Dell                              | 12        | 0.61%   |
| Nvidia                            | 9         | 0.46%   |
| Huawei Technologies               | 9         | 0.46%   |
| Apple                             | 9         | 0.46%   |
| NetGear                           | 8         | 0.41%   |
| TP-Link                           | 7         | 0.36%   |
| Ralink Technology                 | 7         | 0.36%   |
| Lenovo                            | 7         | 0.36%   |
| Hewlett-Packard                   | 7         | 0.36%   |
| ZTE WCDMA Technologies MSM        | 6         | 0.31%   |
| Edimax Technology                 | 6         | 0.31%   |
| ASIX Electronics                  | 6         | 0.31%   |
| OPPO Electronics                  | 5         | 0.26%   |
| ASUSTek Computer                  | 4         | 0.2%    |
| JMicron Technology                | 3         | 0.15%   |
| Google                            | 3         | 0.15%   |
| Ericsson Business Mobile Networks | 3         | 0.15%   |
| Xiaomi                            | 2         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 2         | 0.1%    |
| Qualcomm Atheros Communications   | 2         | 0.1%    |
| Qualcomm                          | 2         | 0.1%    |
| Motorola PCS                      | 2         | 0.1%    |
| ICS Advent                        | 2         | 0.1%    |
| D-Link                            | 2         | 0.1%    |
| Arduino SA                        | 2         | 0.1%    |
| Wilocity                          | 1         | 0.05%   |
| ULi Electronics                   | 1         | 0.05%   |
| Toshiba                           | 1         | 0.05%   |
| T & A Mobile Phones               | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 362       | 15.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 107       | 4.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 68        | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 60        | 2.55%   |
| Intel Wi-Fi 6 AX200                                               | 52        | 2.21%   |
| Intel Wireless 8260                                               | 46        | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 43        | 1.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 42        | 1.79%   |
| Intel Wireless 8265 / 8275                                        | 42        | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 40        | 1.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 36        | 1.53%   |
| Intel Wireless 7260                                               | 36        | 1.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 34        | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 32        | 1.36%   |
| Intel Wi-Fi 6 AX201                                               | 31        | 1.32%   |
| Intel Centrino Ultimate-N 6300                                    | 31        | 1.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 29        | 1.23%   |
| Intel Wireless 7265                                               | 28        | 1.19%   |
| Intel Wireless 3165                                               | 28        | 1.19%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 22        | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 19        | 0.81%   |
| Intel Wireless-AC 9260                                            | 19        | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 18        | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 17        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 0.68%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 16        | 0.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 16        | 0.68%   |
| Intel Wireless 3160                                               | 15        | 0.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 15        | 0.64%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 15        | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 14        | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 14        | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 14        | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 13        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 632       | 50.72%  |
| Qualcomm Atheros                | 226       | 18.14%  |
| Realtek Semiconductor           | 128       | 10.27%  |
| Broadcom                        | 123       | 9.87%   |
| Broadcom Limited                | 36        | 2.89%   |
| Ralink                          | 25        | 2.01%   |
| Sierra Wireless                 | 17        | 1.36%   |
| MediaTek                        | 12        | 0.96%   |
| NetGear                         | 8         | 0.64%   |
| Ralink Technology               | 7         | 0.56%   |
| Dell                            | 7         | 0.56%   |
| TP-Link                         | 6         | 0.48%   |
| Edimax Technology               | 6         | 0.48%   |
| ASUSTek Computer                | 4         | 0.32%   |
| Qualcomm Atheros Communications | 2         | 0.16%   |
| D-Link                          | 2         | 0.16%   |
| Xiaomi                          | 1         | 0.08%   |
| Wilocity                        | 1         | 0.08%   |
| Qualcomm                        | 1         | 0.08%   |
| Hewlett-Packard                 | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 52        | 4.15%   |
| Intel Wireless 8260                                            | 46        | 3.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 43        | 3.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 42        | 3.35%   |
| Intel Wireless 8265 / 8275                                     | 42        | 3.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 40        | 3.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 36        | 2.87%   |
| Intel Wireless 7260                                            | 36        | 2.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 34        | 2.71%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 32        | 2.55%   |
| Intel Wi-Fi 6 AX201                                            | 31        | 2.47%   |
| Intel Centrino Ultimate-N 6300                                 | 31        | 2.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 29        | 2.31%   |
| Intel Wireless 7265                                            | 28        | 2.23%   |
| Intel Wireless 3165                                            | 28        | 2.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 22        | 1.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21        | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 20        | 1.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 19        | 1.52%   |
| Intel Wireless-AC 9260                                         | 19        | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 18        | 1.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 17        | 1.36%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 16        | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 16        | 1.28%   |
| Intel Wireless 3160                                            | 15        | 1.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 15        | 1.2%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 15        | 1.2%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 14        | 1.12%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 14        | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 13        | 1.04%   |
| Intel Centrino Advanced-N 6200                                 | 13        | 1.04%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 12        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 12        | 0.96%   |
| Intel WiFi Link 5100                                           | 11        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                  | 11        | 0.88%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 10        | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10        | 0.8%    |
| Intel Centrino Advanced-N 6235                                 | 10        | 0.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 10        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 547       | 52.34%  |
| Intel                            | 236       | 22.58%  |
| Qualcomm Atheros                 | 85        | 8.13%   |
| Broadcom                         | 62        | 5.93%   |
| Marvell Technology Group         | 16        | 1.53%   |
| DisplayLink                      | 13        | 1.24%   |
| Samsung Electronics              | 12        | 1.15%   |
| Nvidia                           | 9         | 0.86%   |
| Broadcom Limited                 | 9         | 0.86%   |
| Apple                            | 9         | 0.86%   |
| Lenovo                           | 7         | 0.67%   |
| ZTE WCDMA Technologies MSM       | 6         | 0.57%   |
| Huawei Technologies              | 6         | 0.57%   |
| ASIX Electronics                 | 6         | 0.57%   |
| OPPO Electronics                 | 5         | 0.48%   |
| JMicron Technology               | 3         | 0.29%   |
| Google                           | 3         | 0.29%   |
| Silicon Integrated Systems [SiS] | 2         | 0.19%   |
| ICS Advent                       | 2         | 0.19%   |
| Hewlett-Packard                  | 2         | 0.19%   |
| Xiaomi                           | 1         | 0.1%    |
| T & A Mobile Phones              | 1         | 0.1%    |
| Qualcomm                         | 1         | 0.1%    |
| Microsoft                        | 1         | 0.1%    |
| Attansic Technology              | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 362       | 34.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 107       | 10.06%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 68        | 6.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 60        | 5.64%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 2.35%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 1.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 1.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 14        | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 1.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 1.03%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 1.03%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.94%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 10        | 0.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.85%   |
| Intel Ethernet Connection I219-V                                  | 9         | 0.85%   |
| Intel 82567LM Gigabit Network Connection                          | 9         | 0.85%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 9         | 0.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 9         | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.66%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.47%   |
| OPPO SDM710-MTP _SN:2396E2D4                                      | 5         | 0.47%   |
| Nvidia MCP79 Ethernet                                             | 5         | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 0.47%   |
| DisplayLink Dell Universal Dock D6000                             | 5         | 0.47%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4         | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.38%   |
| Realtek Killer E3000 2.5GbE Controller                            | 4         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1168      | 53.68%  |
| Ethernet | 975       | 44.81%  |
| Modem    | 30        | 1.38%   |
| Unknown  | 3         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 968       | 78%     |
| Ethernet | 273       | 22%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 888       | 74.43%  |
| 1     | 285       | 23.89%  |
| 0     | 12        | 1.01%   |
| 3     | 8         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1065      | 88.09%  |
| Yes  | 144       | 11.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 468       | 50.05%  |
| Qualcomm Atheros Communications | 77        | 8.24%   |
| Apple                           | 68        | 7.27%   |
| Broadcom                        | 65        | 6.95%   |
| Realtek Semiconductor           | 48        | 5.13%   |
| Lite-On Technology              | 35        | 3.74%   |
| Toshiba                         | 34        | 3.64%   |
| IMC Networks                    | 33        | 3.53%   |
| Foxconn / Hon Hai               | 32        | 3.42%   |
| Hewlett-Packard                 | 17        | 1.82%   |
| Dell                            | 15        | 1.6%    |
| Ralink                          | 14        | 1.5%    |
| Cambridge Silicon Radio         | 6         | 0.64%   |
| Alps Electric                   | 6         | 0.64%   |
| Realtek                         | 5         | 0.53%   |
| ASUSTek Computer                | 5         | 0.53%   |
| Ralink Technology               | 3         | 0.32%   |
| USI                             | 1         | 0.11%   |
| Opticis                         | 1         | 0.11%   |
| MediaTek                        | 1         | 0.11%   |
| Belkin Components               | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 183       | 19.57%  |
| Intel Bluetooth Device                              | 107       | 11.44%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 58        | 6.2%    |
| Intel AX200 Bluetooth                               | 53        | 5.67%   |
| Apple Bluetooth Host Controller                     | 36        | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 29        | 3.1%    |
| Realtek Bluetooth Radio                             | 26        | 2.78%   |
| Apple Bluetooth USB Host Controller                 | 25        | 2.67%   |
| Lite-On Bluetooth Device                            | 23        | 2.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 19        | 2.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 18        | 1.93%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 1.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 16        | 1.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 1.6%    |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 1.6%    |
| Ralink RT3290 Bluetooth                             | 14        | 1.5%    |
| Intel AX210 Bluetooth                               | 13        | 1.39%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 1.39%   |
| Toshiba Bluetooth Device                            | 12        | 1.28%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 1.07%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 1.07%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 10        | 1.07%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 0.96%   |
| IMC Networks Bluetooth Radio                        | 9         | 0.96%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.86%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.75%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 0.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.64%   |
| Realtek Bluetooth Radio                             | 5         | 0.53%   |
| IMC Networks Wireless_Device                        | 5         | 0.53%   |
| IMC Networks Bluetooth                              | 5         | 0.53%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.53%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.53%   |
| Broadcom BCM20702A0                                 | 5         | 0.53%   |
| Toshiba Askey Bluetooth Module                      | 4         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 995       | 64.15%  |
| Nvidia                                       | 218       | 14.06%  |
| AMD                                          | 208       | 13.41%  |
| Realtek Semiconductor                        | 18        | 1.16%   |
| Apple                                        | 8         | 0.52%   |
| Logitech                                     | 7         | 0.45%   |
| Razer USA                                    | 6         | 0.39%   |
| Lenovo                                       | 6         | 0.39%   |
| GN Netcom                                    | 6         | 0.39%   |
| Creative Technology                          | 6         | 0.39%   |
| C-Media Electronics                          | 6         | 0.39%   |
| Kingston Technology                          | 5         | 0.32%   |
| Generalplus Technology                       | 5         | 0.32%   |
| Hewlett-Packard                              | 4         | 0.26%   |
| Texas Instruments                            | 3         | 0.19%   |
| Plantronics                                  | 3         | 0.19%   |
| OPPO Electronics                             | 3         | 0.19%   |
| Microsoft                                    | 3         | 0.19%   |
| JMTek                                        | 3         | 0.19%   |
| Thermaltake                                  | 2         | 0.13%   |
| SteelSeries ApS                              | 2         | 0.13%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.13%   |
| Samsung Electronics                          | 2         | 0.13%   |
| Native Instruments                           | 2         | 0.13%   |
| Micro Star International                     | 2         | 0.13%   |
| M-Audio                                      | 2         | 0.13%   |
| Dell                                         | 2         | 0.13%   |
| Conexant Systems                             | 2         | 0.13%   |
| Chicony Electronics                          | 2         | 0.13%   |
| Blue Microphones                             | 2         | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.06%   |
| ZOOM                                         | 1         | 0.06%   |
| XMOS                                         | 1         | 0.06%   |
| ULi Electronics                              | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.06%   |
| Sony                                         | 1         | 0.06%   |
| Sennheiser electronic                        | 1         | 0.06%   |
| RODE Microphones                             | 1         | 0.06%   |
| LG Electronics                               | 1         | 0.06%   |
| DSEA A/S                                     | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 144       | 7.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 122       | 6.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 87        | 4.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 74        | 4.01%   |
| AMD Family 17h/19h HD Audio Controller                                     | 73        | 3.95%   |
| Intel Cannon Lake PCH cAVS                                                 | 63        | 3.41%   |
| Intel 8 Series HD Audio Controller                                         | 62        | 3.36%   |
| Intel Haswell-ULT HD Audio Controller                                      | 61        | 3.3%    |
| AMD FCH Azalia Controller                                                  | 48        | 2.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 47        | 2.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 46        | 2.49%   |
| Intel Broadwell-U Audio Controller                                         | 46        | 2.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 43        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 40        | 2.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 39        | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 36        | 1.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 36        | 1.95%   |
| Intel Comet Lake PCH cAVS                                                  | 35        | 1.9%    |
| AMD Kabini HDMI/DP Audio                                                   | 33        | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                               | 30        | 1.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 27        | 1.46%   |
| Intel CM238 HD Audio Controller                                            | 26        | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 24        | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22        | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                              | 21        | 1.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 20        | 1.08%   |
| AMD High Definition Audio Controller                                       | 20        | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                              | 17        | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                         | 17        | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 17        | 0.92%   |
| Realtek Semiconductor USB Audio                                            | 16        | 0.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16        | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                              | 15        | 0.81%   |
| Nvidia GT216 HDMI Audio Controller                                         | 15        | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 15        | 0.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 15        | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13        | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 12        | 0.65%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 12        | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                              | 11        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 211       | 32.02%  |
| SK hynix                   | 172       | 26.1%   |
| Micron Technology          | 90        | 13.66%  |
| Kingston                   | 56        | 8.5%    |
| Crucial                    | 30        | 4.55%   |
| Unknown                    | 21        | 3.19%   |
| Elpida                     | 16        | 2.43%   |
| Ramaxel Technology         | 11        | 1.67%   |
| Nanya Technology           | 8         | 1.21%   |
| Team                       | 7         | 1.06%   |
| Corsair                    | 5         | 0.76%   |
| A-DATA Technology          | 5         | 0.76%   |
| Unknown                    | 5         | 0.76%   |
| G.Skill                    | 3         | 0.46%   |
| Apacer                     | 3         | 0.46%   |
| Smart                      | 2         | 0.3%    |
| Unknown (0x89AD)           | 1         | 0.15%   |
| Unknown (0x873E)           | 1         | 0.15%   |
| Transcend                  | 1         | 0.15%   |
| Toshiba                    | 1         | 0.15%   |
| Silicon Power              | 1         | 0.15%   |
| Qimonda                    | 1         | 0.15%   |
| pqi                        | 1         | 0.15%   |
| Patriot                    | 1         | 0.15%   |
| Netlist                    | 1         | 0.15%   |
| Neo Forza                  | 1         | 0.15%   |
| GSkill                     | 1         | 0.15%   |
| Avant                      | 1         | 0.15%   |
| ASint Technology           | 1         | 0.15%   |
| Anucell Technology Holding | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 2.26%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 1.7%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 1.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 1.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.27%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 1.27%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 8         | 1.13%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.99%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.99%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.99%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.99%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.99%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.85%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.85%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.85%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 6         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.71%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.71%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.71%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 5         | 0.71%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 5         | 0.71%   |
| Unknown                                                          | 5         | 0.71%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.57%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 4         | 0.57%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.57%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.57%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.57%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.57%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.57%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 4         | 0.57%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 4         | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.57%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 4         | 0.57%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 4         | 0.57%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 4         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 252       | 43.6%   |
| DDR3    | 226       | 39.1%   |
| LPDDR3  | 41        | 7.09%   |
| LPDDR4  | 19        | 3.29%   |
| DDR2    | 18        | 3.11%   |
| SDRAM   | 9         | 1.56%   |
| LPDDR5  | 5         | 0.87%   |
| DDR5    | 4         | 0.69%   |
| Unknown | 2         | 0.35%   |
| DRAM    | 1         | 0.17%   |
| DDR     | 1         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 507       | 87.41%  |
| Row Of Chips | 63        | 10.86%  |
| Chip         | 7         | 1.21%   |
| Unknown      | 2         | 0.34%   |
| DIMM         | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 223       | 36.62%  |
| 4096  | 188       | 30.87%  |
| 16384 | 97        | 15.93%  |
| 2048  | 70        | 11.49%  |
| 32768 | 19        | 3.12%   |
| 1024  | 9         | 1.48%   |
| 512   | 2         | 0.33%   |
| 256   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 163       | 26.25%  |
| 2667    | 133       | 21.42%  |
| 3200    | 87        | 14.01%  |
| 1334    | 41        | 6.6%    |
| 2133    | 39        | 6.28%   |
| 2400    | 30        | 4.83%   |
| 1067    | 17        | 2.74%   |
| 1333    | 15        | 2.42%   |
| 1867    | 14        | 2.25%   |
| 4800    | 9         | 1.45%   |
| 4267    | 9         | 1.45%   |
| 667     | 9         | 1.45%   |
| Unknown | 9         | 1.45%   |
| 8400    | 7         | 1.13%   |
| 3266    | 7         | 1.13%   |
| 1066    | 6         | 0.97%   |
| 800     | 6         | 0.97%   |
| 6400    | 4         | 0.64%   |
| 4266    | 4         | 0.64%   |
| 2048    | 4         | 0.64%   |
| 4199    | 3         | 0.48%   |
| 3733    | 2         | 0.32%   |
| 975     | 2         | 0.32%   |
| 533     | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung ML-1865        | 1         | 20%     |
| HP DeskJet 2300 series | 1         | 20%     |
| Canon TS3100 series    | 1         | 20%     |
| Brother HL-2140 series | 1         | 20%     |
| Brother HL-1110 series | 1         | 20%     |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 290       | 26.24%  |
| Microdia                               | 105       | 9.5%    |
| Realtek Semiconductor                  | 101       | 9.14%   |
| IMC Networks                           | 89        | 8.05%   |
| Sunplus Innovation Technology          | 87        | 7.87%   |
| Apple                                  | 65        | 5.88%   |
| Acer                                   | 62        | 5.61%   |
| Quanta                                 | 45        | 4.07%   |
| Suyin                                  | 42        | 3.8%    |
| Cheng Uei Precision Industry (Foxlink) | 42        | 3.8%    |
| Logitech                               | 27        | 2.44%   |
| Lite-On Technology                     | 20        | 1.81%   |
| Syntek                                 | 13        | 1.18%   |
| Luxvisions Innotech Limited            | 13        | 1.18%   |
| Samsung Electronics                    | 11        | 1%      |
| Silicon Motion                         | 10        | 0.9%    |
| Importek                               | 10        | 0.9%    |
| Ricoh                                  | 9         | 0.81%   |
| Primax Electronics                     | 7         | 0.63%   |
| Lenovo                                 | 7         | 0.63%   |
| Alcor Micro                            | 6         | 0.54%   |
| Magic Control Technology               | 4         | 0.36%   |
| DigiTech                               | 4         | 0.36%   |
| Razer USA                              | 3         | 0.27%   |
| OmniVision Technologies                | 3         | 0.27%   |
| LG Electronics                         | 3         | 0.27%   |
| ALi                                    | 3         | 0.27%   |
| Z-Star Microelectronics                | 2         | 0.18%   |
| SunplusIT                              | 2         | 0.18%   |
| Sonix Technology                       | 2         | 0.18%   |
| OPPO Electronics                       | 2         | 0.18%   |
| Genesys Logic                          | 2         | 0.18%   |
| GEMBIRD                                | 2         | 0.18%   |
| Tobii Technology AB                    | 1         | 0.09%   |
| Sunplus Technology                     | 1         | 0.09%   |
| Solid Year                             | 1         | 0.09%   |
| Mimaki Engineering                     | 1         | 0.09%   |
| Microsoft                              | 1         | 0.09%   |
| lihappe8                               | 1         | 0.09%   |
| Intel                                  | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 58        | 5.19%   |
| Chicony Integrated Camera                               | 48        | 4.3%    |
| Realtek Integrated_Webcam_HD                            | 29        | 2.6%    |
| Chicony HD WebCam                                       | 27        | 2.42%   |
| Sunplus Integrated_Webcam_HD                            | 23        | 2.06%   |
| IMC Networks Integrated Camera                          | 23        | 2.06%   |
| Realtek USB Camera                                      | 19        | 1.7%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 18        | 1.61%   |
| Chicony TOSHIBA Web Camera - HD                         | 17        | 1.52%   |
| Apple Built-in iSight                                   | 17        | 1.52%   |
| Chicony HP TrueVision HD Camera                         | 16        | 1.43%   |
| Apple FaceTime HD Camera (Built-in)                     | 16        | 1.43%   |
| Apple iPhone 5/5C/5S/6/SE                               | 14        | 1.25%   |
| Acer Integrated Camera                                  | 14        | 1.25%   |
| Chicony HP Truevision HD                                | 13        | 1.16%   |
| Apple FaceTime HD Camera                                | 13        | 1.16%   |
| Sunplus HD WebCam                                       | 12        | 1.07%   |
| Chicony USB 2.0 Camera                                  | 12        | 1.07%   |
| Samsung Galaxy A5 (MTP)                                 | 11        | 0.98%   |
| Quanta HD User Facing                                   | 11        | 0.98%   |
| Chicony USB2.0 Camera                                   | 11        | 0.98%   |
| Chicony HD User Facing                                  | 11        | 0.98%   |
| Lite-On Integrated Camera                               | 10        | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 10        | 0.9%    |
| Syntek Integrated Camera                                | 9         | 0.81%   |
| Microdia Integrated Webcam                              | 9         | 0.81%   |
| Chicony HP HD Camera                                    | 9         | 0.81%   |
| Chicony CNF9055 Toshiba Webcam                          | 9         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 9         | 0.81%   |
| Suyin HP Truevision HD                                  | 8         | 0.72%   |
| Quanta HP TrueVision HD Camera                          | 8         | 0.72%   |
| Quanta HD Webcam                                        | 8         | 0.72%   |
| Acer HD Webcam                                          | 8         | 0.72%   |
| Chicony Web Camera - HD                                 | 7         | 0.63%   |
| Chicony Integrated Camera (1280x720@30)                 | 7         | 0.63%   |
| Sunplus Asus Webcam                                     | 6         | 0.54%   |
| Realtek USB2.0 HD UVC WebCam                            | 6         | 0.54%   |
| Realtek Integrated Webcam HD                            | 6         | 0.54%   |
| Quanta HP Webcam                                        | 6         | 0.54%   |
| Logitech Webcam C270                                    | 6         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 99        | 41.42%  |
| Synaptics                  | 49        | 20.5%   |
| Shenzhen Goodix Technology | 28        | 11.72%  |
| LighTuning Technology      | 19        | 7.95%   |
| AuthenTec                  | 14        | 5.86%   |
| Upek                       | 13        | 5.44%   |
| Elan Microelectronics      | 10        | 4.18%   |
| STMicroelectronics         | 6         | 2.51%   |
| Focal-systems.Corp         | 1         | 0.42%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 8.37%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 7.53%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 5.44%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 5.44%   |
| Validity Sensors VFS491                                                    | 10        | 4.18%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 4.18%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 4.18%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 3.77%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.77%   |
| Shenzhen Goodix FingerPrint                                                | 9         | 3.77%   |
| Unknown                                                                    | 9         | 3.77%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 3.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.93%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 2.51%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 2.51%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.51%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.51%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.51%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.51%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 2.09%   |
| Synaptics WBDI Device                                                      | 5         | 2.09%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 2.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.67%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.67%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 1.67%   |
| AuthenTec AES1600                                                          | 4         | 1.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.26%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.26%   |
| Synaptics  WBDI                                                            | 3         | 1.26%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.26%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.26%   |
| AuthenTec AES2810                                                          | 2         | 0.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.42%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.42%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.42%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.42%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.42%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 31        | 59.62%  |
| Alcor Micro           | 11        | 21.15%  |
| Upek                  | 4         | 7.69%   |
| Lenovo                | 3         | 5.77%   |
| O2 Micro              | 2         | 3.85%   |
| Advanced Card Systems | 1         | 1.92%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 28.85%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 21.15%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 11.54%  |
| Broadcom 5880                                                                | 5         | 9.62%   |
| Broadcom 58200                                                               | 5         | 9.62%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.77%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.85%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.92%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 732       | 59.13%  |
| 1     | 408       | 32.96%  |
| 2     | 81        | 6.54%   |
| 3     | 13        | 1.05%   |
| 4     | 4         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 238       | 40.34%  |
| Graphics card            | 130       | 22.03%  |
| Net/wireless             | 50        | 8.47%   |
| Chipcard                 | 47        | 7.97%   |
| Multimedia controller    | 38        | 6.44%   |
| Camera                   | 19        | 3.22%   |
| Bluetooth                | 19        | 3.22%   |
| Storage                  | 9         | 1.53%   |
| Net/ethernet             | 9         | 1.53%   |
| Communication controller | 9         | 1.53%   |
| Modem                    | 7         | 1.19%   |
| Sound                    | 6         | 1.02%   |
| Card reader              | 6         | 1.02%   |
| Unassigned class         | 1         | 0.17%   |
| Storage/ide              | 1         | 0.17%   |
| Storage/ata              | 1         | 0.17%   |

