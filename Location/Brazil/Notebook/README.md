Linux in Brazil - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

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

Total: 12714

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion Slim 5 16IRH8 83D... | [2389b9fc2f](https://linux-hardware.org/?probe=2389b9fc2f) | Feb 02, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | [32facc4f9e](https://linux-hardware.org/?probe=32facc4f9e) | Feb 02, 2024 |
| Dell          | Inspiron 3583               | [3c532c85ec](https://linux-hardware.org/?probe=3c532c85ec) | Feb 02, 2024 |
| Dell          | Inspiron 3442               | [ca29fa6852](https://linux-hardware.org/?probe=ca29fa6852) | Feb 02, 2024 |
| Dell          | G7 7588                     | [fdc746ce61](https://linux-hardware.org/?probe=fdc746ce61) | Feb 02, 2024 |
| Dell          | Latitude 7420               | [5eb0b85732](https://linux-hardware.org/?probe=5eb0b85732) | Feb 02, 2024 |
| Notebook      | NJx0MU                      | [6259b53b1c](https://linux-hardware.org/?probe=6259b53b1c) | Feb 02, 2024 |
| Dell          | Inspiron 5547               | [507fad3c00](https://linux-hardware.org/?probe=507fad3c00) | Feb 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e5bbf9598f](https://linux-hardware.org/?probe=e5bbf9598f) | Feb 01, 2024 |
| Notebook      | NJx0MU                      | [7def8ee544](https://linux-hardware.org/?probe=7def8ee544) | Feb 01, 2024 |
| Samsung       | 750XFH                      | [47d573ccf5](https://linux-hardware.org/?probe=47d573ccf5) | Feb 01, 2024 |
| Acer          | Swift SF514-56T             | [320f3db548](https://linux-hardware.org/?probe=320f3db548) | Jan 31, 2024 |
| Evolute       | B14HM21                     | [c5a911ad90](https://linux-hardware.org/?probe=c5a911ad90) | Jan 31, 2024 |
| Dell          | Inspiron N4050              | [9126475882](https://linux-hardware.org/?probe=9126475882) | Jan 31, 2024 |
| ASUSTek       | TP550LA                     | [2fa23ece92](https://linux-hardware.org/?probe=2fa23ece92) | Jan 31, 2024 |
| Avell         | B.ON                        | [45a01901e9](https://linux-hardware.org/?probe=45a01901e9) | Jan 31, 2024 |
| Dell          | Inspiron 5537               | [7c7904f383](https://linux-hardware.org/?probe=7c7904f383) | Jan 31, 2024 |
| Dell          | Inspiron 5537               | [7a4e4ac7ba](https://linux-hardware.org/?probe=7a4e4ac7ba) | Jan 31, 2024 |
| Dell          | Studio 1450                 | [cdeeb53e43](https://linux-hardware.org/?probe=cdeeb53e43) | Jan 31, 2024 |
| HP            | Presario C700               | [d309190dbb](https://linux-hardware.org/?probe=d309190dbb) | Jan 30, 2024 |
| Dell          | G15 5510                    | [9f3691e991](https://linux-hardware.org/?probe=9f3691e991) | Jan 30, 2024 |
| Notebook      | NJx0MU                      | [6f8f587ec5](https://linux-hardware.org/?probe=6f8f587ec5) | Jan 30, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0b6e8d1e4b](https://linux-hardware.org/?probe=0b6e8d1e4b) | Jan 30, 2024 |
| Acer          | Nitro AN515-44              | [05ec6529d7](https://linux-hardware.org/?probe=05ec6529d7) | Jan 29, 2024 |
| Acer          | Aspire A315-58              | [c1af8d7ca2](https://linux-hardware.org/?probe=c1af8d7ca2) | Jan 29, 2024 |
| Compaq        | Presario CQ-21              | [b947b6f2b8](https://linux-hardware.org/?probe=b947b6f2b8) | Jan 29, 2024 |
| Acer          | Aspire 5750                 | [f05ba6ae6f](https://linux-hardware.org/?probe=f05ba6ae6f) | Jan 29, 2024 |
| HP            | Pavilion 11 x360 PC         | [1d8dbbd8af](https://linux-hardware.org/?probe=1d8dbbd8af) | Jan 29, 2024 |
| Avell High... | B.ON                        | [8b9b2f2129](https://linux-hardware.org/?probe=8b9b2f2129) | Jan 28, 2024 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [81e9c9a499](https://linux-hardware.org/?probe=81e9c9a499) | Jan 28, 2024 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [465b69ceca](https://linux-hardware.org/?probe=465b69ceca) | Jan 28, 2024 |
| Dell          | Inspiron 15-3567            | [9ce085875f](https://linux-hardware.org/?probe=9ce085875f) | Jan 27, 2024 |
| HP            | Pavilion 14                 | [93fffe502f](https://linux-hardware.org/?probe=93fffe502f) | Jan 27, 2024 |
| Lenovo        | G50-80 80R0                 | [980165425e](https://linux-hardware.org/?probe=980165425e) | Jan 27, 2024 |
| Lenovo        | G50-80 80R0                 | [eeee227df0](https://linux-hardware.org/?probe=eeee227df0) | Jan 26, 2024 |
| Dell          | Latitude 3480               | [5ccc62ce95](https://linux-hardware.org/?probe=5ccc62ce95) | Jan 26, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8cafa419c5](https://linux-hardware.org/?probe=8cafa419c5) | Jan 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7dd8607755](https://linux-hardware.org/?probe=7dd8607755) | Jan 26, 2024 |
| Lenovo        | ThinkPad Edge E430 3254H... | [ec87598c40](https://linux-hardware.org/?probe=ec87598c40) | Jan 26, 2024 |
| Lenovo        | G460 0677                   | [d4624cb524](https://linux-hardware.org/?probe=d4624cb524) | Jan 26, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [606adf78f9](https://linux-hardware.org/?probe=606adf78f9) | Jan 24, 2024 |
| ODM           | Unknown                     | [2d8310fe96](https://linux-hardware.org/?probe=2d8310fe96) | Jan 24, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | [876874e8b5](https://linux-hardware.org/?probe=876874e8b5) | Jan 24, 2024 |
| Dell          | Vostro 5490                 | [ef2aff4ed1](https://linux-hardware.org/?probe=ef2aff4ed1) | Jan 23, 2024 |
| HP            | Pavilion g4                 | [f0cc56ebca](https://linux-hardware.org/?probe=f0cc56ebca) | Jan 23, 2024 |
| Acer          | Aspire A315-54              | [83570af6ad](https://linux-hardware.org/?probe=83570af6ad) | Jan 23, 2024 |
| Valve         | Jupiter                     | [9ac816140b](https://linux-hardware.org/?probe=9ac816140b) | Jan 23, 2024 |
| Positivo      | Mobile                      | [d1ca90b4f5](https://linux-hardware.org/?probe=d1ca90b4f5) | Jan 23, 2024 |
| Dell          | Inspiron 5570               | [9fd4f31b80](https://linux-hardware.org/?probe=9fd4f31b80) | Jan 22, 2024 |
| Dell          | Inspiron 3421               | [a15cb7d764](https://linux-hardware.org/?probe=a15cb7d764) | Jan 22, 2024 |
| Dell          | Inspiron 5490               | [e879f5dd00](https://linux-hardware.org/?probe=e879f5dd00) | Jan 22, 2024 |
| Gigabyte      | H510M H                     | [88b87b3353](https://linux-hardware.org/?probe=88b87b3353) | Jan 22, 2024 |
| HP            | Folio 13                    | [a4be721bb8](https://linux-hardware.org/?probe=a4be721bb8) | Jan 22, 2024 |
| ASUSTek       | S400CA                      | [87f5dfadc9](https://linux-hardware.org/?probe=87f5dfadc9) | Jan 22, 2024 |
| Acer          | Aspire A315-58              | [4a991bd59b](https://linux-hardware.org/?probe=4a991bd59b) | Jan 22, 2024 |
| Valve         | Jupiter                     | [9e62126d95](https://linux-hardware.org/?probe=9e62126d95) | Jan 21, 2024 |
| Lenovo        | G460 20041                  | [becc9c140b](https://linux-hardware.org/?probe=becc9c140b) | Jan 21, 2024 |
| Valve         | Jupiter                     | [4d7a6b2c71](https://linux-hardware.org/?probe=4d7a6b2c71) | Jan 21, 2024 |
| Acer          | Nitro AN515-55              | [428442a3ab](https://linux-hardware.org/?probe=428442a3ab) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | [07f3899f3a](https://linux-hardware.org/?probe=07f3899f3a) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | [7bb9b69a14](https://linux-hardware.org/?probe=7bb9b69a14) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | [124da06515](https://linux-hardware.org/?probe=124da06515) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | [01d1c30937](https://linux-hardware.org/?probe=01d1c30937) | Jan 21, 2024 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [e8a23ca7a0](https://linux-hardware.org/?probe=e8a23ca7a0) | Jan 20, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [ef0e698daf](https://linux-hardware.org/?probe=ef0e698daf) | Jan 20, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [48653c026b](https://linux-hardware.org/?probe=48653c026b) | Jan 20, 2024 |
| HP            | Presario CQ43               | [ad1175a3a8](https://linux-hardware.org/?probe=ad1175a3a8) | Jan 20, 2024 |
| Dell          | Latitude 3490               | [367100a9ad](https://linux-hardware.org/?probe=367100a9ad) | Jan 20, 2024 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [f88694f40b](https://linux-hardware.org/?probe=f88694f40b) | Jan 20, 2024 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [1ce9d8eb2f](https://linux-hardware.org/?probe=1ce9d8eb2f) | Jan 20, 2024 |
| Samsung       | 960XFH                      | [fa6946bc7b](https://linux-hardware.org/?probe=fa6946bc7b) | Jan 19, 2024 |
| Dell          | Inspiron 7520               | [5768e68147](https://linux-hardware.org/?probe=5768e68147) | Jan 19, 2024 |
| Samsung       | RV415/RV515                 | [5002fd9959](https://linux-hardware.org/?probe=5002fd9959) | Jan 19, 2024 |
| Dell          | Inspiron 15-3567            | [dafbbbb67c](https://linux-hardware.org/?probe=dafbbbb67c) | Jan 19, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c7ab1232bb](https://linux-hardware.org/?probe=c7ab1232bb) | Jan 18, 2024 |
| Dell          | Inspiron 3480               | [0c15974fbb](https://linux-hardware.org/?probe=0c15974fbb) | Jan 18, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [3bb54b1a3a](https://linux-hardware.org/?probe=3bb54b1a3a) | Jan 18, 2024 |
| Dell          | Inspiron 3583               | [e70de12740](https://linux-hardware.org/?probe=e70de12740) | Jan 18, 2024 |
| Samsung       | RV415/RV515                 | [282ae0ae50](https://linux-hardware.org/?probe=282ae0ae50) | Jan 18, 2024 |
| Acer          | Aspire A315-42G             | [5f7172f388](https://linux-hardware.org/?probe=5f7172f388) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [86d22c9b40](https://linux-hardware.org/?probe=86d22c9b40) | Jan 17, 2024 |
| Acer          | Aspire A515-54              | [4d6487e7f5](https://linux-hardware.org/?probe=4d6487e7f5) | Jan 17, 2024 |
| ASUSTek       | K43E                        | [ac83dcf66b](https://linux-hardware.org/?probe=ac83dcf66b) | Jan 17, 2024 |
| Dell          | Inspiron 7348               | [a3c452af85](https://linux-hardware.org/?probe=a3c452af85) | Jan 17, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [6cfbe412a8](https://linux-hardware.org/?probe=6cfbe412a8) | Jan 16, 2024 |
| LG Electro... | A530-U.BE54P1               | [b396bdcd52](https://linux-hardware.org/?probe=b396bdcd52) | Jan 16, 2024 |
| Compaq        | 430                         | [a8dc50fedd](https://linux-hardware.org/?probe=a8dc50fedd) | Jan 16, 2024 |
| Acer          | Aspire F5-573G              | [6ba3da1f95](https://linux-hardware.org/?probe=6ba3da1f95) | Jan 16, 2024 |
| Lenovo        | ThinkPad E490 20N90000BR    | [94ef2c20ba](https://linux-hardware.org/?probe=94ef2c20ba) | Jan 16, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | [8bbf7916f3](https://linux-hardware.org/?probe=8bbf7916f3) | Jan 15, 2024 |
| Acer          | Nitro AN515-58              | [ed413e1907](https://linux-hardware.org/?probe=ed413e1907) | Jan 15, 2024 |
| Multilaser    | MLGW08                      | [abfe537d6f](https://linux-hardware.org/?probe=abfe537d6f) | Jan 15, 2024 |
| Apple         | MacBookPro10,1              | [29522391fa](https://linux-hardware.org/?probe=29522391fa) | Jan 15, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [95569b47c5](https://linux-hardware.org/?probe=95569b47c5) | Jan 14, 2024 |
| Apple         | MacBookPro11,1              | [e865dbe75e](https://linux-hardware.org/?probe=e865dbe75e) | Jan 14, 2024 |
| Lenovo        | Yoga Slim 6 14IAP8 83C7     | [4e4c095efb](https://linux-hardware.org/?probe=4e4c095efb) | Jan 14, 2024 |
| Positivo      | Harrison                    | [bc50c3c3ca](https://linux-hardware.org/?probe=bc50c3c3ca) | Jan 14, 2024 |
| Samsung       | 300E5M/300E5L               | [9c43a79143](https://linux-hardware.org/?probe=9c43a79143) | Jan 14, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [c7e3069d99](https://linux-hardware.org/?probe=c7e3069d99) | Jan 14, 2024 |
| Lenovo        | ThinkPad T400 6474EU3       | [0d9d328c8d](https://linux-hardware.org/?probe=0d9d328c8d) | Jan 14, 2024 |
| Positivo      | Mobile                      | [750ee7ae05](https://linux-hardware.org/?probe=750ee7ae05) | Jan 14, 2024 |
| Positivo B... | VJFE53F11X-XXXXXX           | [ebd0135392](https://linux-hardware.org/?probe=ebd0135392) | Jan 14, 2024 |
| Digibras      | NH4CU03                     | [7cccdf824c](https://linux-hardware.org/?probe=7cccdf824c) | Jan 13, 2024 |
| Samsung       | 550XED                      | [a9cdc1201c](https://linux-hardware.org/?probe=a9cdc1201c) | Jan 13, 2024 |
| Acer          | Nitro AN515-47              | [521b0ef15b](https://linux-hardware.org/?probe=521b0ef15b) | Jan 13, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [63d2ac1744](https://linux-hardware.org/?probe=63d2ac1744) | Jan 13, 2024 |
| Dell          | Latitude E5450              | [a9275ec728](https://linux-hardware.org/?probe=a9275ec728) | Jan 13, 2024 |
| Apple         | MacBookPro10,1              | [dc905da8e7](https://linux-hardware.org/?probe=dc905da8e7) | Jan 12, 2024 |
| Dell          | Latitude 3440               | [b8145337d1](https://linux-hardware.org/?probe=b8145337d1) | Jan 12, 2024 |
| Dell          | Inspiron 5447               | [12ec54ffaf](https://linux-hardware.org/?probe=12ec54ffaf) | Jan 12, 2024 |
| Acer          | Predator PH315-53           | [bb3670e4b7](https://linux-hardware.org/?probe=bb3670e4b7) | Jan 12, 2024 |
| HP            | Folio 13                    | [c2c19d8d51](https://linux-hardware.org/?probe=c2c19d8d51) | Jan 11, 2024 |
| Positivo      | S14SL01                     | [0dd36639d2](https://linux-hardware.org/?probe=0dd36639d2) | Jan 11, 2024 |
| Acer          | Aspire F5-573G              | [e37a928b80](https://linux-hardware.org/?probe=e37a928b80) | Jan 11, 2024 |
| Dell          | Inspiron 7572               | [19c0615c74](https://linux-hardware.org/?probe=19c0615c74) | Jan 11, 2024 |
| Dell          | Inspiron 7572               | [62b4f5a943](https://linux-hardware.org/?probe=62b4f5a943) | Jan 11, 2024 |
| Dell          | Inspiron 11-3168            | [f7763a1298](https://linux-hardware.org/?probe=f7763a1298) | Jan 10, 2024 |
| Positivo      | C14CU51                     | [efceb077f1](https://linux-hardware.org/?probe=efceb077f1) | Jan 10, 2024 |
| Toshiba       | STI NI 1401                 | [be4bcf5468](https://linux-hardware.org/?probe=be4bcf5468) | Jan 10, 2024 |
| Gigazone      | X107(B-B)                   | [a72cbb0097](https://linux-hardware.org/?probe=a72cbb0097) | Jan 10, 2024 |
| HP            | EliteBook 2540p             | [088dbf4c2f](https://linux-hardware.org/?probe=088dbf4c2f) | Jan 10, 2024 |
| Dell          | Inspiron 15-3567            | [0420a7ddaa](https://linux-hardware.org/?probe=0420a7ddaa) | Jan 09, 2024 |
| Gigazone      | X107(B-B)                   | [54085fcb32](https://linux-hardware.org/?probe=54085fcb32) | Jan 09, 2024 |
| Dell          | Inspiron 15 3515            | [1ca72e6562](https://linux-hardware.org/?probe=1ca72e6562) | Jan 09, 2024 |
| Login Info... | LOG-QAL30                   | [7d09dd9a16](https://linux-hardware.org/?probe=7d09dd9a16) | Jan 09, 2024 |
| Dell          | XPS 13 9300                 | [c054440c09](https://linux-hardware.org/?probe=c054440c09) | Jan 09, 2024 |
| Toshiba       | IS 1413G                    | [5fa474d76d](https://linux-hardware.org/?probe=5fa474d76d) | Jan 09, 2024 |
| Lenovo        | ThinkPad Edge E430 3254H... | [9ff97bbae7](https://linux-hardware.org/?probe=9ff97bbae7) | Jan 09, 2024 |
| Samsung       | 550XBE/350XBE               | [40266fb2b6](https://linux-hardware.org/?probe=40266fb2b6) | Jan 08, 2024 |
| Login Info... | LOG-QAL30                   | [73a33a80ae](https://linux-hardware.org/?probe=73a33a80ae) | Jan 08, 2024 |
| Positivo B... | VJFE42F11X-B2891H           | [95a3cef171](https://linux-hardware.org/?probe=95a3cef171) | Jan 08, 2024 |
| Toshiba       | IS 1413G                    | [714f151f30](https://linux-hardware.org/?probe=714f151f30) | Jan 08, 2024 |
| Samsung       | RV415/RV515                 | [5451d552aa](https://linux-hardware.org/?probe=5451d552aa) | Jan 07, 2024 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [2c36dcaa22](https://linux-hardware.org/?probe=2c36dcaa22) | Jan 07, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C60... | [739eae84a2](https://linux-hardware.org/?probe=739eae84a2) | Jan 07, 2024 |
| Acer          | Aspire E5-574               | [4c6e591812](https://linux-hardware.org/?probe=4c6e591812) | Jan 06, 2024 |
| Acer          | Aspire A514-54              | [513f1c7737](https://linux-hardware.org/?probe=513f1c7737) | Jan 06, 2024 |
| Acer          | Aspire A514-54              | [97b3214a42](https://linux-hardware.org/?probe=97b3214a42) | Jan 06, 2024 |
| HP            | Pavilion 14                 | [82550ce5ae](https://linux-hardware.org/?probe=82550ce5ae) | Jan 06, 2024 |
| Dell          | Latitude 3420               | [39d522ead5](https://linux-hardware.org/?probe=39d522ead5) | Jan 05, 2024 |
| Unknown       | Unknown                     | [d135277737](https://linux-hardware.org/?probe=d135277737) | Jan 05, 2024 |
| Unknown       | Unknown                     | [5e7209bd1a](https://linux-hardware.org/?probe=5e7209bd1a) | Jan 05, 2024 |
| Toshiba       | IS 1413G                    | [5e4cd95800](https://linux-hardware.org/?probe=5e4cd95800) | Jan 05, 2024 |
| ASUSTek       | TP301UA                     | [0617a0e757](https://linux-hardware.org/?probe=0617a0e757) | Jan 05, 2024 |
| Digibras      | NH4CU03                     | [be0eab4038](https://linux-hardware.org/?probe=be0eab4038) | Jan 05, 2024 |
| Samsung       | 670Z5E                      | [c4bce26993](https://linux-hardware.org/?probe=c4bce26993) | Jan 04, 2024 |
| Acer          | Nitro AN515-44              | [6a2df7d4aa](https://linux-hardware.org/?probe=6a2df7d4aa) | Jan 04, 2024 |
| Acer          | Aspire A515-56G             | [084e91606c](https://linux-hardware.org/?probe=084e91606c) | Jan 04, 2024 |
| LG Electro... | 23V545-G.BK55P1             | [6cf752515c](https://linux-hardware.org/?probe=6cf752515c) | Jan 04, 2024 |
| Acer          | Aspire E1-572               | [a68d0f8100](https://linux-hardware.org/?probe=a68d0f8100) | Jan 04, 2024 |
| Acer          | Aspire A515-56G             | [e1554fcb98](https://linux-hardware.org/?probe=e1554fcb98) | Jan 04, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3557687358](https://linux-hardware.org/?probe=3557687358) | Jan 04, 2024 |
| Positivo      | Q4128CI                     | [3b0b3095d2](https://linux-hardware.org/?probe=3b0b3095d2) | Jan 03, 2024 |
| Positivo      | Q4128CI                     | [7f3766e4dc](https://linux-hardware.org/?probe=7f3766e4dc) | Jan 03, 2024 |
| Positivo      | C4128A-15                   | [52bd86685b](https://linux-hardware.org/?probe=52bd86685b) | Jan 03, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [1755330be9](https://linux-hardware.org/?probe=1755330be9) | Jan 03, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c278d1e669](https://linux-hardware.org/?probe=c278d1e669) | Jan 03, 2024 |
| Dell          | Inspiron 3442               | [6d9d64e6f6](https://linux-hardware.org/?probe=6d9d64e6f6) | Jan 03, 2024 |
| Acer          | Nitro AN515-52              | [b789e33c24](https://linux-hardware.org/?probe=b789e33c24) | Jan 03, 2024 |
| Positivo B... | VJFE42F11X-B2891H           | [47c3c6c806](https://linux-hardware.org/?probe=47c3c6c806) | Jan 03, 2024 |
| Acer          | Aspire ES1-572              | [65c6d98c36](https://linux-hardware.org/?probe=65c6d98c36) | Jan 02, 2024 |
| Dell          | Inspiron 15-3567            | [589f53595e](https://linux-hardware.org/?probe=589f53595e) | Jan 02, 2024 |
| Notebook      | NJx0MU                      | [c038b7f7e4](https://linux-hardware.org/?probe=c038b7f7e4) | Jan 02, 2024 |
| Dell          | Inspiron 15-3567            | [50d926ec76](https://linux-hardware.org/?probe=50d926ec76) | Jan 02, 2024 |
| Samsung       | 550XCJ/550XCR               | [daf43e4658](https://linux-hardware.org/?probe=daf43e4658) | Jan 02, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [88bc9fe11f](https://linux-hardware.org/?probe=88bc9fe11f) | Jan 02, 2024 |
| HP            | 15 Notebook PC              | [9eb25ba0bf](https://linux-hardware.org/?probe=9eb25ba0bf) | Jan 02, 2024 |
| Acer          | Nitro AN515-44              | [9ac5286530](https://linux-hardware.org/?probe=9ac5286530) | Jan 02, 2024 |
| Philco        | 14M2                        | [b5771423fb](https://linux-hardware.org/?probe=b5771423fb) | Jan 02, 2024 |
| Acer          | Aspire A515-51G             | [e7b0efb20a](https://linux-hardware.org/?probe=e7b0efb20a) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [14df5ebb53](https://linux-hardware.org/?probe=14df5ebb53) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [00ee13cdb6](https://linux-hardware.org/?probe=00ee13cdb6) | Jan 01, 2024 |
| Notebook      | NJx0MU                      | [cdb97873fa](https://linux-hardware.org/?probe=cdb97873fa) | Jan 01, 2024 |
| Timi          | RedmiBook Pro 14S           | [08718e205b](https://linux-hardware.org/?probe=08718e205b) | Jan 01, 2024 |
| Notebook      | NJx0MU                      | [f9d4fa4d55](https://linux-hardware.org/?probe=f9d4fa4d55) | Jan 01, 2024 |
| Sony          | VJF153                      | [9bf924f424](https://linux-hardware.org/?probe=9bf924f424) | Jan 01, 2024 |
| Dell          | Latitude 5310               | [87c543db6f](https://linux-hardware.org/?probe=87c543db6f) | Jan 01, 2024 |
| Sony          | VJF153                      | [b3949d3670](https://linux-hardware.org/?probe=b3949d3670) | Jan 01, 2024 |
| Dell          | Inspiron 15-3567            | [390160b8e5](https://linux-hardware.org/?probe=390160b8e5) | Dec 31, 2023 |
| Notebook      | NJx0MU                      | [c7f2d68d77](https://linux-hardware.org/?probe=c7f2d68d77) | Dec 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2352ac6075](https://linux-hardware.org/?probe=2352ac6075) | Dec 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [5f33ce2d18](https://linux-hardware.org/?probe=5f33ce2d18) | Dec 30, 2023 |
| Dell          | Inspiron 7460               | [1085eef155](https://linux-hardware.org/?probe=1085eef155) | Dec 30, 2023 |
| Dell          | Inspiron 15-3567            | [5d1ed5c106](https://linux-hardware.org/?probe=5d1ed5c106) | Dec 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [33556742c3](https://linux-hardware.org/?probe=33556742c3) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | [6416d967b8](https://linux-hardware.org/?probe=6416d967b8) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | [bd9afc6d73](https://linux-hardware.org/?probe=bd9afc6d73) | Dec 30, 2023 |
| Positivo      | Harrison                    | [bf31594bef](https://linux-hardware.org/?probe=bf31594bef) | Dec 30, 2023 |
| Acer          | Aspire A515-54G             | [35e2f8c10c](https://linux-hardware.org/?probe=35e2f8c10c) | Dec 29, 2023 |
| HP            | EliteBook 8560w             | [c7e5dc5d9b](https://linux-hardware.org/?probe=c7e5dc5d9b) | Dec 29, 2023 |
| HP            | EliteBook 8560w             | [e3ecbaedf9](https://linux-hardware.org/?probe=e3ecbaedf9) | Dec 29, 2023 |
| Acer          | Aspire A315-24P             | [64dddef2fa](https://linux-hardware.org/?probe=64dddef2fa) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [03199adbd4](https://linux-hardware.org/?probe=03199adbd4) | Dec 29, 2023 |
| Dell          | Inspiron 3443               | [0c56a0465b](https://linux-hardware.org/?probe=0c56a0465b) | Dec 29, 2023 |
| Dell          | Inspiron 3584               | [818e96295f](https://linux-hardware.org/?probe=818e96295f) | Dec 29, 2023 |
| Lenovo        | B490 37722KP                | [194971e987](https://linux-hardware.org/?probe=194971e987) | Dec 29, 2023 |
| Acer          | Aspire 4736Z                | [ea8dffb40f](https://linux-hardware.org/?probe=ea8dffb40f) | Dec 29, 2023 |
| HP            | Pavilion dv6                | [9992f9523e](https://linux-hardware.org/?probe=9992f9523e) | Dec 29, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [a86830ecd2](https://linux-hardware.org/?probe=a86830ecd2) | Dec 28, 2023 |
| Positivo      | Harrison                    | [e12b67378a](https://linux-hardware.org/?probe=e12b67378a) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a1652ba789](https://linux-hardware.org/?probe=a1652ba789) | Dec 28, 2023 |
| HP            | 250 G8 Notebook PC          | [255c0c95bc](https://linux-hardware.org/?probe=255c0c95bc) | Dec 28, 2023 |
| win elemen... | MoreFine S500+              | [6880205d9e](https://linux-hardware.org/?probe=6880205d9e) | Dec 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [09d63b8472](https://linux-hardware.org/?probe=09d63b8472) | Dec 28, 2023 |
| Purism        | Librem 14                   | [215d922345](https://linux-hardware.org/?probe=215d922345) | Dec 28, 2023 |
| Samsung       | 550XCJ/550XCR               | [c62c257897](https://linux-hardware.org/?probe=c62c257897) | Dec 27, 2023 |
| Dell          | G3 3500                     | [87c0216250](https://linux-hardware.org/?probe=87c0216250) | Dec 27, 2023 |
| Dell          | Inspiron 5570               | [84242f4904](https://linux-hardware.org/?probe=84242f4904) | Dec 27, 2023 |
| Dell          | Inspiron 3583               | [de1dd08f64](https://linux-hardware.org/?probe=de1dd08f64) | Dec 27, 2023 |
| Dell          | Inspiron 15 3515            | [6369debba7](https://linux-hardware.org/?probe=6369debba7) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [971e3fe3eb](https://linux-hardware.org/?probe=971e3fe3eb) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7d873eb94f](https://linux-hardware.org/?probe=7d873eb94f) | Dec 26, 2023 |
| Acer          | Aspire A315-24P             | [eade6242b7](https://linux-hardware.org/?probe=eade6242b7) | Dec 25, 2023 |
| Acer          | Aspire A315-24P             | [7f11ff0265](https://linux-hardware.org/?probe=7f11ff0265) | Dec 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [850fedd929](https://linux-hardware.org/?probe=850fedd929) | Dec 25, 2023 |
| Google        | Aleena                      | [a5a888a877](https://linux-hardware.org/?probe=a5a888a877) | Dec 25, 2023 |
| Acer          | Aspire A515-51G             | [6705535031](https://linux-hardware.org/?probe=6705535031) | Dec 25, 2023 |
| Notebook      | NJx0MU                      | [87cef435db](https://linux-hardware.org/?probe=87cef435db) | Dec 24, 2023 |
| Acer          | Aspire A315-41              | [a54e95fcab](https://linux-hardware.org/?probe=a54e95fcab) | Dec 24, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [a5d5ac012b](https://linux-hardware.org/?probe=a5d5ac012b) | Dec 24, 2023 |
| Valve         | Jupiter                     | [19f8d4f0b4](https://linux-hardware.org/?probe=19f8d4f0b4) | Dec 24, 2023 |
| Samsung       | RV415/RV515                 | [da980644b4](https://linux-hardware.org/?probe=da980644b4) | Dec 24, 2023 |
| Notebook      | NJx0MU                      | [b57fdd9854](https://linux-hardware.org/?probe=b57fdd9854) | Dec 24, 2023 |
| Acer          | Nitro AN515-44              | [cc87c11e7b](https://linux-hardware.org/?probe=cc87c11e7b) | Dec 24, 2023 |
| Acer          | Nitro AN515-51              | [52a7a4d6d8](https://linux-hardware.org/?probe=52a7a4d6d8) | Dec 23, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [d409d2fe79](https://linux-hardware.org/?probe=d409d2fe79) | Dec 23, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [eae7bab112](https://linux-hardware.org/?probe=eae7bab112) | Dec 23, 2023 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [d65cca0578](https://linux-hardware.org/?probe=d65cca0578) | Dec 22, 2023 |
| Positivo      | W940TU                      | [40dff18a74](https://linux-hardware.org/?probe=40dff18a74) | Dec 22, 2023 |
| Acer          | Nitro AN515-44              | [5f1c04a086](https://linux-hardware.org/?probe=5f1c04a086) | Dec 22, 2023 |
| Dell          | Inspiron 7572               | [b6a03a82a6](https://linux-hardware.org/?probe=b6a03a82a6) | Dec 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [808fe0568d](https://linux-hardware.org/?probe=808fe0568d) | Dec 21, 2023 |
| Dell          | Inspiron 5448               | [edf818740d](https://linux-hardware.org/?probe=edf818740d) | Dec 21, 2023 |
| Dell          | Vostro 3550                 | [2c9d7daa8b](https://linux-hardware.org/?probe=2c9d7daa8b) | Dec 21, 2023 |
| Dell          | Inspiron 7572               | [cd9385a64b](https://linux-hardware.org/?probe=cd9385a64b) | Dec 21, 2023 |
| Alienware     | m16 R1 AMD                  | [8fc737975c](https://linux-hardware.org/?probe=8fc737975c) | Dec 21, 2023 |
| Valve         | Jupiter                     | [aecbb83cd6](https://linux-hardware.org/?probe=aecbb83cd6) | Dec 20, 2023 |
| ASUSTek       | X556URK                     | [b4f01c5bd5](https://linux-hardware.org/?probe=b4f01c5bd5) | Dec 19, 2023 |
| Daten Tecn... | DT02-M4                     | [8f754589f6](https://linux-hardware.org/?probe=8f754589f6) | Dec 19, 2023 |
| Acer          | Nitro AN515-43              | [963de967ae](https://linux-hardware.org/?probe=963de967ae) | Dec 19, 2023 |
| Acer          | Aspire E5-571               | [55a802f43c](https://linux-hardware.org/?probe=55a802f43c) | Dec 18, 2023 |
| Dell          | Latitude 3420               | [5fdda723cd](https://linux-hardware.org/?probe=5fdda723cd) | Dec 18, 2023 |
| GPD           | G1619-04                    | [63b517665b](https://linux-hardware.org/?probe=63b517665b) | Dec 18, 2023 |
| Toshiba       | IS 1413G                    | [458a8fb3f1](https://linux-hardware.org/?probe=458a8fb3f1) | Dec 18, 2023 |
| Dell          | G3 3590                     | [15decf2dfc](https://linux-hardware.org/?probe=15decf2dfc) | Dec 18, 2023 |
| Samsung       | 550P5C/550P7C               | [b06e8fbef4](https://linux-hardware.org/?probe=b06e8fbef4) | Dec 18, 2023 |
| Acer          | Nitro AN515-57              | [1bd5e5e36f](https://linux-hardware.org/?probe=1bd5e5e36f) | Dec 18, 2023 |
| Compal        | PBL1011                     | [8983f2e331](https://linux-hardware.org/?probe=8983f2e331) | Dec 18, 2023 |
| Acer          | Nitro AN517-54              | [c18f5d3a21](https://linux-hardware.org/?probe=c18f5d3a21) | Dec 18, 2023 |
| Acer          | Nitro AN517-54              | [982ae3655c](https://linux-hardware.org/?probe=982ae3655c) | Dec 18, 2023 |
| Notebook      | NJx0MU                      | [1446130ae9](https://linux-hardware.org/?probe=1446130ae9) | Dec 17, 2023 |
| Toshiba       | IS 1413G                    | [dde306e444](https://linux-hardware.org/?probe=dde306e444) | Dec 17, 2023 |
| Notebook      | NJx0MU                      | [80281cb193](https://linux-hardware.org/?probe=80281cb193) | Dec 17, 2023 |
| Dell          | Inspiron N4030              | [a77869199a](https://linux-hardware.org/?probe=a77869199a) | Dec 17, 2023 |
| Samsung       | 550XDA                      | [10ec283ed4](https://linux-hardware.org/?probe=10ec283ed4) | Dec 17, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [be717cf064](https://linux-hardware.org/?probe=be717cf064) | Dec 16, 2023 |
| Dell          | Inspiron 15-3567            | [570a822273](https://linux-hardware.org/?probe=570a822273) | Dec 16, 2023 |
| Dell          | Inspiron 3583               | [890cf9cc41](https://linux-hardware.org/?probe=890cf9cc41) | Dec 16, 2023 |
| Dell          | Vostro 5490                 | [ca117be9d4](https://linux-hardware.org/?probe=ca117be9d4) | Dec 16, 2023 |
| Acer          | Nitro AN515-51              | [de83793263](https://linux-hardware.org/?probe=de83793263) | Dec 16, 2023 |
| Toshiba       | IS 1413G                    | [09d89c7989](https://linux-hardware.org/?probe=09d89c7989) | Dec 15, 2023 |
| Dell          | Inspiron 1525               | [b9daaa5978](https://linux-hardware.org/?probe=b9daaa5978) | Dec 15, 2023 |
| Acer          | Nitro AN515-57              | [7e43febcae](https://linux-hardware.org/?probe=7e43febcae) | Dec 15, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [a043c13550](https://linux-hardware.org/?probe=a043c13550) | Dec 14, 2023 |
| Acer          | Nitro AN517-54              | [c16cb0947e](https://linux-hardware.org/?probe=c16cb0947e) | Dec 14, 2023 |
| Dell          | G15 5520                    | [12b6fa0914](https://linux-hardware.org/?probe=12b6fa0914) | Dec 14, 2023 |
| Dell          | Inspiron 7560               | [83034fb404](https://linux-hardware.org/?probe=83034fb404) | Dec 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [d2b1e67451](https://linux-hardware.org/?probe=d2b1e67451) | Dec 14, 2023 |
| Dell          | G15 5520                    | [d212fe82aa](https://linux-hardware.org/?probe=d212fe82aa) | Dec 14, 2023 |
| Acer          | Nitro AN515-45              | [1ff0d683f4](https://linux-hardware.org/?probe=1ff0d683f4) | Dec 13, 2023 |
| Acer          | Nitro AN515-51              | [1522c84fb7](https://linux-hardware.org/?probe=1522c84fb7) | Dec 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [bd8707be32](https://linux-hardware.org/?probe=bd8707be32) | Dec 13, 2023 |
| Dell          | Latitude E5470              | [cc7982deb0](https://linux-hardware.org/?probe=cc7982deb0) | Dec 13, 2023 |
| Dell          | Inspiron 15 5510            | [41dbdcf594](https://linux-hardware.org/?probe=41dbdcf594) | Dec 13, 2023 |
| Dell          | Latitude 3420               | [b344d71410](https://linux-hardware.org/?probe=b344d71410) | Dec 13, 2023 |
| Dell          | System XPS L502X            | [75c612f90d](https://linux-hardware.org/?probe=75c612f90d) | Dec 13, 2023 |
| Dell          | G3 3590                     | [e764bfc760](https://linux-hardware.org/?probe=e764bfc760) | Dec 13, 2023 |
| Acer          | Aspire A515-51G             | [295f9127b0](https://linux-hardware.org/?probe=295f9127b0) | Dec 12, 2023 |
| Acer          | Aspire A515-45              | [74dc572dd7](https://linux-hardware.org/?probe=74dc572dd7) | Dec 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [74c0490d28](https://linux-hardware.org/?probe=74c0490d28) | Dec 12, 2023 |
| Positivo      | H14BT58                     | [74530bb40a](https://linux-hardware.org/?probe=74530bb40a) | Dec 12, 2023 |
| Positivo      | CHT12CP                     | [d9d4327551](https://linux-hardware.org/?probe=d9d4327551) | Dec 12, 2023 |
| Acer          | Predator G3-572             | [7de00d4eab](https://linux-hardware.org/?probe=7de00d4eab) | Dec 12, 2023 |
| Acer          | Aspire A315-510P            | [e2bdedca29](https://linux-hardware.org/?probe=e2bdedca29) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [843d02bea4](https://linux-hardware.org/?probe=843d02bea4) | Dec 11, 2023 |
| Positivo      | Q464C                       | [47071c986c](https://linux-hardware.org/?probe=47071c986c) | Dec 11, 2023 |
| Samsung       | Q470C/500P4C                | [f904c4ea67](https://linux-hardware.org/?probe=f904c4ea67) | Dec 11, 2023 |
| Dell          | Inspiron 3442               | [deced1a058](https://linux-hardware.org/?probe=deced1a058) | Dec 11, 2023 |
| Dell          | System XPS L502X            | [a612ae1881](https://linux-hardware.org/?probe=a612ae1881) | Dec 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [4af70588d9](https://linux-hardware.org/?probe=4af70588d9) | Dec 10, 2023 |
| Acer          | Aspire 5750                 | [bedb502b74](https://linux-hardware.org/?probe=bedb502b74) | Dec 10, 2023 |
| Acer          | Aspire A515-57              | [1adc377142](https://linux-hardware.org/?probe=1adc377142) | Dec 10, 2023 |
| MSI           | Modern 15 B7M               | [cc6c41e7fd](https://linux-hardware.org/?probe=cc6c41e7fd) | Dec 10, 2023 |
| Toshiba       | IS 1412                     | [b5f0453a4b](https://linux-hardware.org/?probe=b5f0453a4b) | Dec 09, 2023 |
| Dell          | Vostro 3550                 | [f1a1a0841c](https://linux-hardware.org/?probe=f1a1a0841c) | Dec 08, 2023 |
| Dell          | Inspiron 15 3520            | [6452783d8a](https://linux-hardware.org/?probe=6452783d8a) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9f878d8d30](https://linux-hardware.org/?probe=9f878d8d30) | Dec 08, 2023 |
| Acer          | Aspire A315-41              | [778176acbe](https://linux-hardware.org/?probe=778176acbe) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [88ed0c98a0](https://linux-hardware.org/?probe=88ed0c98a0) | Dec 07, 2023 |
| Samsung       | 550XDA                      | [6501dce45c](https://linux-hardware.org/?probe=6501dce45c) | Dec 07, 2023 |
| Positivo      | Q4128C-S                    | [018aab637c](https://linux-hardware.org/?probe=018aab637c) | Dec 07, 2023 |
| Positivo B... | VJFE59F11X-B1011H           | [2f497e2103](https://linux-hardware.org/?probe=2f497e2103) | Dec 06, 2023 |
| ASUSTek       | K45A                        | [a5e618b2f9](https://linux-hardware.org/?probe=a5e618b2f9) | Dec 06, 2023 |
| ASUSTek       | K45A                        | [96d1051ede](https://linux-hardware.org/?probe=96d1051ede) | Dec 06, 2023 |
| Acer          | Nitro AN515-57              | [5b38f6200a](https://linux-hardware.org/?probe=5b38f6200a) | Dec 06, 2023 |
| Dell          | Inspiron 7472               | [ef77efb220](https://linux-hardware.org/?probe=ef77efb220) | Dec 06, 2023 |
| Dell          | Precision 7720              | [da0616987d](https://linux-hardware.org/?probe=da0616987d) | Dec 05, 2023 |
| Samsung       | RV419/RV420                 | [5f29bdfad1](https://linux-hardware.org/?probe=5f29bdfad1) | Dec 05, 2023 |
| Acer          | Aspire AV15-51              | [2691ac3f7d](https://linux-hardware.org/?probe=2691ac3f7d) | Dec 05, 2023 |
| Dell          | G7 7588                     | [8564f8e395](https://linux-hardware.org/?probe=8564f8e395) | Dec 05, 2023 |
| Valve         | Jupiter                     | [4ffa224365](https://linux-hardware.org/?probe=4ffa224365) | Dec 05, 2023 |
| Acer          | Aspire AV15-51              | [758a277d68](https://linux-hardware.org/?probe=758a277d68) | Dec 04, 2023 |
| Dell          | Inspiron 5567               | [03fe12170c](https://linux-hardware.org/?probe=03fe12170c) | Dec 04, 2023 |
| Samsung       | 550XDA                      | [b5bfe47576](https://linux-hardware.org/?probe=b5bfe47576) | Dec 04, 2023 |
| MSI           | Modern 15 B7M               | [f1757e8248](https://linux-hardware.org/?probe=f1757e8248) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [3222457362](https://linux-hardware.org/?probe=3222457362) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S9UY00    | [318a41e343](https://linux-hardware.org/?probe=318a41e343) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a7c5eb788c](https://linux-hardware.org/?probe=a7c5eb788c) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [da6b435afa](https://linux-hardware.org/?probe=da6b435afa) | Dec 02, 2023 |
| Acer          | Aspire V5-472               | [c4839c409c](https://linux-hardware.org/?probe=c4839c409c) | Dec 02, 2023 |
| Acer          | Aspire V5-472               | [0dc4701502](https://linux-hardware.org/?probe=0dc4701502) | Dec 02, 2023 |
| Dell          | Latitude 3540               | [64067574ad](https://linux-hardware.org/?probe=64067574ad) | Dec 02, 2023 |
| Dell          | G15 5510                    | [bdfca2648a](https://linux-hardware.org/?probe=bdfca2648a) | Dec 02, 2023 |
| Dell          | Vostro 3525                 | [6d84ce1284](https://linux-hardware.org/?probe=6d84ce1284) | Dec 01, 2023 |
| Dell          | Inspiron 15-3567            | [520e1bdfa8](https://linux-hardware.org/?probe=520e1bdfa8) | Dec 01, 2023 |
| Acer          | Aspire A515-45              | [9875097d6a](https://linux-hardware.org/?probe=9875097d6a) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [32a0e568cc](https://linux-hardware.org/?probe=32a0e568cc) | Dec 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | [dcbc9946d8](https://linux-hardware.org/?probe=dcbc9946d8) | Dec 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | [95221dfaaf](https://linux-hardware.org/?probe=95221dfaaf) | Dec 01, 2023 |
| Dell          | Vostro 1510                 | [65480134bd](https://linux-hardware.org/?probe=65480134bd) | Dec 01, 2023 |
| HP            | Presario CQ43               | [5edf6adf85](https://linux-hardware.org/?probe=5edf6adf85) | Dec 01, 2023 |
| Dell          | Latitude E5410              | [074e7de8d8](https://linux-hardware.org/?probe=074e7de8d8) | Dec 01, 2023 |
| Multilaser    | PC31X                       | [1f63edb2f9](https://linux-hardware.org/?probe=1f63edb2f9) | Dec 01, 2023 |
| Dell          | Inspiron 15 3515            | [162854d649](https://linux-hardware.org/?probe=162854d649) | Nov 30, 2023 |
| Acer          | Predator PH315-52           | [bb1fc18586](https://linux-hardware.org/?probe=bb1fc18586) | Nov 30, 2023 |
| Samsung       | 550XDA                      | [5778304f73](https://linux-hardware.org/?probe=5778304f73) | Nov 30, 2023 |
| Dell          | G15 5511                    | [f77d3ad016](https://linux-hardware.org/?probe=f77d3ad016) | Nov 30, 2023 |
| Dell          | Vostro 3500                 | [bd6506d274](https://linux-hardware.org/?probe=bd6506d274) | Nov 30, 2023 |
| AMI           | AMD                         | [9f3f9ba617](https://linux-hardware.org/?probe=9f3f9ba617) | Nov 29, 2023 |
| Avell High... | B.ON                        | [22a1430347](https://linux-hardware.org/?probe=22a1430347) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d9b203868f](https://linux-hardware.org/?probe=d9b203868f) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7db0c2781b](https://linux-hardware.org/?probe=7db0c2781b) | Nov 29, 2023 |
| HP            | Pavilion dv6                | [ddce26dd72](https://linux-hardware.org/?probe=ddce26dd72) | Nov 29, 2023 |
| HP            | Pavilion 11 x360 PC         | [c6f9c552b6](https://linux-hardware.org/?probe=c6f9c552b6) | Nov 29, 2023 |
| Acer          | Aspire 4732Z                | [6a849535fb](https://linux-hardware.org/?probe=6a849535fb) | Nov 29, 2023 |
| Dell          | Inspiron 15 3515            | [20007eacdb](https://linux-hardware.org/?probe=20007eacdb) | Nov 28, 2023 |
| Dell          | Inspiron 15 3515            | [e41d34ea1c](https://linux-hardware.org/?probe=e41d34ea1c) | Nov 28, 2023 |
| HP            | Presario CQ43               | [eaab50d59c](https://linux-hardware.org/?probe=eaab50d59c) | Nov 28, 2023 |
| Dell          | Vostro 3583                 | [68c6f002f5](https://linux-hardware.org/?probe=68c6f002f5) | Nov 28, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [1eda316922](https://linux-hardware.org/?probe=1eda316922) | Nov 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [3531e02313](https://linux-hardware.org/?probe=3531e02313) | Nov 27, 2023 |
| Daten Tecn... | DCM3A-4                     | [66b8d06d48](https://linux-hardware.org/?probe=66b8d06d48) | Nov 27, 2023 |
| Dell          | Inspiron 5566               | [df3eed7cc0](https://linux-hardware.org/?probe=df3eed7cc0) | Nov 27, 2023 |
| Dell          | Vostro 1510                 | [8cb1e628c2](https://linux-hardware.org/?probe=8cb1e628c2) | Nov 27, 2023 |
| Lenovo        | ThinkPad T410 2522F25       | [d6988c10b5](https://linux-hardware.org/?probe=d6988c10b5) | Nov 27, 2023 |
| Lenovo        | ThinkPad T410 2522F25       | [aadbbad61f](https://linux-hardware.org/?probe=aadbbad61f) | Nov 27, 2023 |
| Valve         | Jupiter                     | [a208b7bd3a](https://linux-hardware.org/?probe=a208b7bd3a) | Nov 26, 2023 |
| Philco        | 14H                         | [f4256fe390](https://linux-hardware.org/?probe=f4256fe390) | Nov 26, 2023 |
| Acer          | Swift SF514-56T             | [687fc34fd5](https://linux-hardware.org/?probe=687fc34fd5) | Nov 26, 2023 |
| Lenovo        | Unknown                     | [504a4bd033](https://linux-hardware.org/?probe=504a4bd033) | Nov 26, 2023 |
| HP            | Pavilion 14                 | [af5d0c670a](https://linux-hardware.org/?probe=af5d0c670a) | Nov 26, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0f05f2568e](https://linux-hardware.org/?probe=0f05f2568e) | Nov 25, 2023 |
| Positivo      | C41TF                       | [09be1cbd3a](https://linux-hardware.org/?probe=09be1cbd3a) | Nov 25, 2023 |
| Dell          | Latitude 7430               | [1074b5c005](https://linux-hardware.org/?probe=1074b5c005) | Nov 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0c42791b33](https://linux-hardware.org/?probe=0c42791b33) | Nov 25, 2023 |
| Dell          | Inspiron 5468               | [3422c91458](https://linux-hardware.org/?probe=3422c91458) | Nov 24, 2023 |
| Positivo      | S14CT01                     | [c1b3f4bc65](https://linux-hardware.org/?probe=c1b3f4bc65) | Nov 24, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [d69be34130](https://linux-hardware.org/?probe=d69be34130) | Nov 24, 2023 |
| A14CR         | Unknown                     | [c0924a368e](https://linux-hardware.org/?probe=c0924a368e) | Nov 24, 2023 |
| HP            | G62                         | [9d6424c4cc](https://linux-hardware.org/?probe=9d6424c4cc) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [199f9814a0](https://linux-hardware.org/?probe=199f9814a0) | Nov 24, 2023 |
| Samsung       | 960XFH                      | [2ad3d93589](https://linux-hardware.org/?probe=2ad3d93589) | Nov 24, 2023 |
| Compaq        | 420                         | [651aec3a5c](https://linux-hardware.org/?probe=651aec3a5c) | Nov 24, 2023 |
| Compaq        | 420                         | [df09fad001](https://linux-hardware.org/?probe=df09fad001) | Nov 23, 2023 |
| Samsung       | 270E5J/2570EJ               | [d6ab9c6df5](https://linux-hardware.org/?probe=d6ab9c6df5) | Nov 23, 2023 |
| Avell High... | A70 MOB                     | [d936aa95ef](https://linux-hardware.org/?probe=d936aa95ef) | Nov 23, 2023 |
| HP            | ProBook 4430s               | [847fb6fb22](https://linux-hardware.org/?probe=847fb6fb22) | Nov 23, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [07e6828b2e](https://linux-hardware.org/?probe=07e6828b2e) | Nov 23, 2023 |
| Acer          | Aspire A515-57              | [676da26c54](https://linux-hardware.org/?probe=676da26c54) | Nov 23, 2023 |
| HP            | ProBook 4430s               | [1b34dd379f](https://linux-hardware.org/?probe=1b34dd379f) | Nov 23, 2023 |
| HP            | 430                         | [a5ad87647a](https://linux-hardware.org/?probe=a5ad87647a) | Nov 23, 2023 |
| Acer          | Aspire ES1-531              | [01d429e284](https://linux-hardware.org/?probe=01d429e284) | Nov 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [8d944b2cf7](https://linux-hardware.org/?probe=8d944b2cf7) | Nov 22, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [93a21a43d5](https://linux-hardware.org/?probe=93a21a43d5) | Nov 22, 2023 |
| Acer          | Aspire A515-51              | [b8a36c00e8](https://linux-hardware.org/?probe=b8a36c00e8) | Nov 22, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e95ef90dec](https://linux-hardware.org/?probe=e95ef90dec) | Nov 22, 2023 |
| Dell          | Inspiron 5502               | [eb86dc0b36](https://linux-hardware.org/?probe=eb86dc0b36) | Nov 22, 2023 |
| Dell          | Latitude 7430               | [44557e3a83](https://linux-hardware.org/?probe=44557e3a83) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0a82a8edc6](https://linux-hardware.org/?probe=0a82a8edc6) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f30de31399](https://linux-hardware.org/?probe=f30de31399) | Nov 22, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [2d0d992e3e](https://linux-hardware.org/?probe=2d0d992e3e) | Nov 22, 2023 |
| Positivo      | S14CT01                     | [dab6f65392](https://linux-hardware.org/?probe=dab6f65392) | Nov 22, 2023 |
| Positivo      | S14CT01                     | [b92cdc7457](https://linux-hardware.org/?probe=b92cdc7457) | Nov 22, 2023 |
| Samsung       | 530XBB                      | [c31efedbdf](https://linux-hardware.org/?probe=c31efedbdf) | Nov 22, 2023 |
| Dell          | Inspiron N5010              | [688d81c63c](https://linux-hardware.org/?probe=688d81c63c) | Nov 22, 2023 |
| Toshiba       | IS 1413G                    | [2f025c011d](https://linux-hardware.org/?probe=2f025c011d) | Nov 22, 2023 |
| Samsung       | 960XFH                      | [c8ff018414](https://linux-hardware.org/?probe=c8ff018414) | Nov 22, 2023 |
| Samsung       | 960XFH                      | [a379f59fb3](https://linux-hardware.org/?probe=a379f59fb3) | Nov 22, 2023 |
| Dell          | Inspiron 5547               | [d679a12a36](https://linux-hardware.org/?probe=d679a12a36) | Nov 21, 2023 |
| Acer          | Aspire A515-54G             | [8e8de2388b](https://linux-hardware.org/?probe=8e8de2388b) | Nov 21, 2023 |
| Toshiba       | IS 1412                     | [0ed3e8195d](https://linux-hardware.org/?probe=0ed3e8195d) | Nov 21, 2023 |
| HP            | 430                         | [65a26f2a32](https://linux-hardware.org/?probe=65a26f2a32) | Nov 21, 2023 |
| Samsung       | 550XDA                      | [4c1328b562](https://linux-hardware.org/?probe=4c1328b562) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d6c8994c15](https://linux-hardware.org/?probe=d6c8994c15) | Nov 20, 2023 |
| Notebook      | NJx0MU                      | [96d6ec7f1f](https://linux-hardware.org/?probe=96d6ec7f1f) | Nov 20, 2023 |
| Notebook      | NJx0MU                      | [c0a0353d6f](https://linux-hardware.org/?probe=c0a0353d6f) | Nov 20, 2023 |
| Dell          | G15 5530                    | [0d608c0d48](https://linux-hardware.org/?probe=0d608c0d48) | Nov 20, 2023 |
| Acer          | Nitro AN517-54              | [b93c6fb412](https://linux-hardware.org/?probe=b93c6fb412) | Nov 20, 2023 |
| Digibras      | NH4CU53                     | [25fff3f773](https://linux-hardware.org/?probe=25fff3f773) | Nov 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a8e951e3b6](https://linux-hardware.org/?probe=a8e951e3b6) | Nov 20, 2023 |
| HP            | Presario C700               | [c8a9963f71](https://linux-hardware.org/?probe=c8a9963f71) | Nov 19, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5edc51a963](https://linux-hardware.org/?probe=5edc51a963) | Nov 19, 2023 |
| Acer          | Predator PH315-52           | [b53d35a567](https://linux-hardware.org/?probe=b53d35a567) | Nov 19, 2023 |
| Dell          | Inspiron 5548               | [63fec114db](https://linux-hardware.org/?probe=63fec114db) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e26c4bc5ff](https://linux-hardware.org/?probe=e26c4bc5ff) | Nov 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [97ebdb3c3a](https://linux-hardware.org/?probe=97ebdb3c3a) | Nov 19, 2023 |
| Dell          | Inspiron 15-5568            | [18712e5bfd](https://linux-hardware.org/?probe=18712e5bfd) | Nov 19, 2023 |
| Acer          | Aspire 5920                 | [ceafa361bc](https://linux-hardware.org/?probe=ceafa361bc) | Nov 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [07aecd2eb5](https://linux-hardware.org/?probe=07aecd2eb5) | Nov 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S9UY00    | [21433a0601](https://linux-hardware.org/?probe=21433a0601) | Nov 19, 2023 |
| Acer          | Nitro AN515-52              | [a9b37fa8a9](https://linux-hardware.org/?probe=a9b37fa8a9) | Nov 19, 2023 |
| Acer          | Nitro AN515-52              | [0e1fa61401](https://linux-hardware.org/?probe=0e1fa61401) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9073144bc1](https://linux-hardware.org/?probe=9073144bc1) | Nov 19, 2023 |
| Multilaser    | MLSH1H LINUX                | [5f9c8945b0](https://linux-hardware.org/?probe=5f9c8945b0) | Nov 18, 2023 |
| Dell          | Inspiron 5558               | [29cde3b62e](https://linux-hardware.org/?probe=29cde3b62e) | Nov 18, 2023 |
| Acer          | Aspire E1-532               | [8ec5ebb443](https://linux-hardware.org/?probe=8ec5ebb443) | Nov 18, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [669208a0f6](https://linux-hardware.org/?probe=669208a0f6) | Nov 18, 2023 |
| Apple         | MacBookPro14,3              | [c8b5a88695](https://linux-hardware.org/?probe=c8b5a88695) | Nov 18, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [a8095f2a1a](https://linux-hardware.org/?probe=a8095f2a1a) | Nov 18, 2023 |
| Multilaser    | MLSH1H LINUX                | [01d7e1aa14](https://linux-hardware.org/?probe=01d7e1aa14) | Nov 18, 2023 |
| HP            | Compaq Presario CQ50        | [a61196eaad](https://linux-hardware.org/?probe=a61196eaad) | Nov 18, 2023 |
| HP            | Compaq Presario CQ50        | [b8b635e62f](https://linux-hardware.org/?probe=b8b635e62f) | Nov 18, 2023 |
| Compaq        | Presario CQ-17              | [7b53a480e4](https://linux-hardware.org/?probe=7b53a480e4) | Nov 17, 2023 |
| Compal        | PBL1011                     | [d015fafb32](https://linux-hardware.org/?probe=d015fafb32) | Nov 17, 2023 |
| Dell          | Vostro 15 5510              | [21505599dd](https://linux-hardware.org/?probe=21505599dd) | Nov 17, 2023 |
| Dell          | Latitude 5420               | [cc85910964](https://linux-hardware.org/?probe=cc85910964) | Nov 17, 2023 |
| Acer          | Aspire A515-51G             | [44d575bc98](https://linux-hardware.org/?probe=44d575bc98) | Nov 17, 2023 |
| Toshiba       | IS 1413G                    | [97bc4b516e](https://linux-hardware.org/?probe=97bc4b516e) | Nov 17, 2023 |
| Dell          | Latitude 3540               | [85737e7d24](https://linux-hardware.org/?probe=85737e7d24) | Nov 17, 2023 |
| Acer          | Aspire A515-51G             | [18a6603dd9](https://linux-hardware.org/?probe=18a6603dd9) | Nov 17, 2023 |
| Dell          | Vostro 3300                 | [90986d4cf6](https://linux-hardware.org/?probe=90986d4cf6) | Nov 16, 2023 |
| Samsung       | 550XDA                      | [a823e2b0a5](https://linux-hardware.org/?probe=a823e2b0a5) | Nov 16, 2023 |
| Dell          | Inspiron 5567               | [ae0f1ed771](https://linux-hardware.org/?probe=ae0f1ed771) | Nov 16, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [4c58693314](https://linux-hardware.org/?probe=4c58693314) | Nov 16, 2023 |
| HP            | Pavilion g4                 | [37d7289eb6](https://linux-hardware.org/?probe=37d7289eb6) | Nov 16, 2023 |
| Samsung       | 300E5M/300E5L               | [0f53418be5](https://linux-hardware.org/?probe=0f53418be5) | Nov 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f1ba9de4ad](https://linux-hardware.org/?probe=f1ba9de4ad) | Nov 16, 2023 |
| Acer          | Nitro AN515-54              | [0ab66fd189](https://linux-hardware.org/?probe=0ab66fd189) | Nov 16, 2023 |
| Alienware     | m15 R6                      | [c341b25df2](https://linux-hardware.org/?probe=c341b25df2) | Nov 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1fa32b3cb7](https://linux-hardware.org/?probe=1fa32b3cb7) | Nov 15, 2023 |
| Apple         | MacBookPro8,1               | [68dbf5814b](https://linux-hardware.org/?probe=68dbf5814b) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [d4c7bc8dc8](https://linux-hardware.org/?probe=d4c7bc8dc8) | Nov 15, 2023 |
| Dell          | Vostro 3583                 | [4ddc04a5ba](https://linux-hardware.org/?probe=4ddc04a5ba) | Nov 15, 2023 |
| Acer          | Aspire E1-572               | [c7c8df77be](https://linux-hardware.org/?probe=c7c8df77be) | Nov 15, 2023 |
| Sony          | VGN-NS130AE                 | [7a70acb426](https://linux-hardware.org/?probe=7a70acb426) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0fe7515de5](https://linux-hardware.org/?probe=0fe7515de5) | Nov 15, 2023 |
| Dell          | Vostro 3583                 | [6bf67ac977](https://linux-hardware.org/?probe=6bf67ac977) | Nov 15, 2023 |
| Dell          | Vostro 15 3510              | [9c0b7c2706](https://linux-hardware.org/?probe=9c0b7c2706) | Nov 15, 2023 |
| Dell          | Inspiron 1545               | [fd459af24b](https://linux-hardware.org/?probe=fd459af24b) | Nov 15, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [3be8e07c6c](https://linux-hardware.org/?probe=3be8e07c6c) | Nov 14, 2023 |
| Dell          | Inspiron 3583               | [d014ceb833](https://linux-hardware.org/?probe=d014ceb833) | Nov 14, 2023 |
| Acer          | Predator PH315-53           | [f2a6eea13e](https://linux-hardware.org/?probe=f2a6eea13e) | Nov 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4e7f0bb4bc](https://linux-hardware.org/?probe=4e7f0bb4bc) | Nov 14, 2023 |
| Phoenix/Si... | M730SR                      | [59e9d07293](https://linux-hardware.org/?probe=59e9d07293) | Nov 14, 2023 |
| Acer          | Aspire A515-51G             | [50a49f6aa3](https://linux-hardware.org/?probe=50a49f6aa3) | Nov 14, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [65712a4bc0](https://linux-hardware.org/?probe=65712a4bc0) | Nov 14, 2023 |
| HP            | Pavilion dv5                | [f08fc1d52e](https://linux-hardware.org/?probe=f08fc1d52e) | Nov 13, 2023 |
| Acer          | Nitro AN517-54              | [37423cedf9](https://linux-hardware.org/?probe=37423cedf9) | Nov 13, 2023 |
| Sony          | VPCYB35AB                   | [2bc35e6541](https://linux-hardware.org/?probe=2bc35e6541) | Nov 13, 2023 |
| Acer          | Nitro AN515-54              | [656ba48c77](https://linux-hardware.org/?probe=656ba48c77) | Nov 12, 2023 |
| Acer          | Nitro AN515-54              | [6fb9ac1dd2](https://linux-hardware.org/?probe=6fb9ac1dd2) | Nov 12, 2023 |
| Dell          | Latitude 3420               | [5e829237c5](https://linux-hardware.org/?probe=5e829237c5) | Nov 12, 2023 |
| Apple         | MacBookPro8,1               | [cbde46d416](https://linux-hardware.org/?probe=cbde46d416) | Nov 12, 2023 |
| Toshiba       | IS 1413G                    | [9a070023f0](https://linux-hardware.org/?probe=9a070023f0) | Nov 12, 2023 |
| HP            | G42                         | [8a331f427d](https://linux-hardware.org/?probe=8a331f427d) | Nov 11, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [5168262bbe](https://linux-hardware.org/?probe=5168262bbe) | Nov 11, 2023 |
| Philco        | 14H                         | [01ddcfeb9e](https://linux-hardware.org/?probe=01ddcfeb9e) | Nov 11, 2023 |
| Acer          | Nitro AN515-51              | [bcbad28ab7](https://linux-hardware.org/?probe=bcbad28ab7) | Nov 11, 2023 |
| Samsung       | 550XDA                      | [036d014b91](https://linux-hardware.org/?probe=036d014b91) | Nov 10, 2023 |
| Acer          | Aspire A315-54              | [a83ac39876](https://linux-hardware.org/?probe=a83ac39876) | Nov 10, 2023 |
| Samsung       | RF511/RF411/RF711           | [04eea37363](https://linux-hardware.org/?probe=04eea37363) | Nov 10, 2023 |
| HP            | ProBook 4430s               | [47b4ab5ae1](https://linux-hardware.org/?probe=47b4ab5ae1) | Nov 10, 2023 |
| HP            | ProBook 4430s               | [69a5aa0675](https://linux-hardware.org/?probe=69a5aa0675) | Nov 10, 2023 |
| Acer          | Aspire A315-23              | [95ea718240](https://linux-hardware.org/?probe=95ea718240) | Nov 10, 2023 |
| ASUSTek       | G60JX                       | [0ac4f1dfc0](https://linux-hardware.org/?probe=0ac4f1dfc0) | Nov 10, 2023 |
| Lenovo        | ThinkPad E14 20RB001YBR     | [5c84f04d34](https://linux-hardware.org/?probe=5c84f04d34) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [0cacf99f8a](https://linux-hardware.org/?probe=0cacf99f8a) | Nov 09, 2023 |
| ASUSTek       | S400CA                      | [0e5628865a](https://linux-hardware.org/?probe=0e5628865a) | Nov 09, 2023 |
| HP            | 250 G8 Notebook PC          | [54073a3305](https://linux-hardware.org/?probe=54073a3305) | Nov 09, 2023 |
| Dell          | Vostro 5470                 | [f1ba64ccfc](https://linux-hardware.org/?probe=f1ba64ccfc) | Nov 09, 2023 |
| HP            | G42                         | [f440217af5](https://linux-hardware.org/?probe=f440217af5) | Nov 09, 2023 |
| Dell          | Vostro 5402                 | [67a604ba54](https://linux-hardware.org/?probe=67a604ba54) | Nov 08, 2023 |
| Acer          | Nitro AN515-54              | [fbdaa89128](https://linux-hardware.org/?probe=fbdaa89128) | Nov 08, 2023 |
| Acer          | Nitro AN515-47              | [b5982ee614](https://linux-hardware.org/?probe=b5982ee614) | Nov 08, 2023 |
| Acer          | Aspire E5-553G              | [f77e4d524d](https://linux-hardware.org/?probe=f77e4d524d) | Nov 08, 2023 |
| Acer          | Aspire F5-573G              | [00b9675b99](https://linux-hardware.org/?probe=00b9675b99) | Nov 08, 2023 |
| Dell          | Latitude 3480               | [993ca1c423](https://linux-hardware.org/?probe=993ca1c423) | Nov 08, 2023 |
| Acer          | Nitro AN515-47              | [3cf76cfbda](https://linux-hardware.org/?probe=3cf76cfbda) | Nov 08, 2023 |
| Acer          | Nitro AN515-46              | [69541ca76a](https://linux-hardware.org/?probe=69541ca76a) | Nov 07, 2023 |
| ASUSTek       | G60JX                       | [af79a74a4e](https://linux-hardware.org/?probe=af79a74a4e) | Nov 07, 2023 |
| Valve         | Jupiter                     | [b662e225f4](https://linux-hardware.org/?probe=b662e225f4) | Nov 07, 2023 |
| Samsung       | 550XCJ/550XCR               | [c88fd34c8f](https://linux-hardware.org/?probe=c88fd34c8f) | Nov 07, 2023 |
| Dell          | Latitude 3480               | [58e8983502](https://linux-hardware.org/?probe=58e8983502) | Nov 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0cc84d3b82](https://linux-hardware.org/?probe=0cc84d3b82) | Nov 07, 2023 |
| Samsung       | 550P5C/550P7C               | [c7d84926af](https://linux-hardware.org/?probe=c7d84926af) | Nov 07, 2023 |
| Notebook      | NJx0MU                      | [70cdbefd00](https://linux-hardware.org/?probe=70cdbefd00) | Nov 07, 2023 |
| Samsung       | 550XCJ/550XCR               | [8ee0ec30d3](https://linux-hardware.org/?probe=8ee0ec30d3) | Nov 06, 2023 |
| HP            | EliteBook 850 G6            | [0d00c42688](https://linux-hardware.org/?probe=0d00c42688) | Nov 06, 2023 |
| HP            | ENVY 15                     | [5f301610ee](https://linux-hardware.org/?probe=5f301610ee) | Nov 06, 2023 |
| Acer          | Aspire A515-51              | [5fafb134cf](https://linux-hardware.org/?probe=5fafb134cf) | Nov 06, 2023 |
| HP            | ENVY 15                     | [150ca6a1a0](https://linux-hardware.org/?probe=150ca6a1a0) | Nov 06, 2023 |
| Samsung       | 550P5C/550P7C               | [f87e3a97c4](https://linux-hardware.org/?probe=f87e3a97c4) | Nov 06, 2023 |
| Acer          | Aspire A315-53              | [3daa9909b3](https://linux-hardware.org/?probe=3daa9909b3) | Nov 06, 2023 |
| Positivo      | C41TF                       | [4bb5f6150c](https://linux-hardware.org/?probe=4bb5f6150c) | Nov 06, 2023 |
| Notebook      | NJx0MU                      | [24a052bf0c](https://linux-hardware.org/?probe=24a052bf0c) | Nov 06, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f0b35f0acb](https://linux-hardware.org/?probe=f0b35f0acb) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7060a82ed0](https://linux-hardware.org/?probe=7060a82ed0) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| Digibras      | NH4CU53                     | [2c274cbad8](https://linux-hardware.org/?probe=2c274cbad8) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Dell          | Latitude E6430              | [6a724d5aa8](https://linux-hardware.org/?probe=6a724d5aa8) | Nov 04, 2023 |
| ASUSTek       | UX31A                       | [013a7815c3](https://linux-hardware.org/?probe=013a7815c3) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [80d949b057](https://linux-hardware.org/?probe=80d949b057) | Nov 04, 2023 |
| Google        | Bluebird                    | [55dbc11653](https://linux-hardware.org/?probe=55dbc11653) | Nov 04, 2023 |
| MSI           | MS-1759                     | [2dd46c2a71](https://linux-hardware.org/?probe=2dd46c2a71) | Nov 04, 2023 |
| Google        | Bluebird                    | [9e12130a28](https://linux-hardware.org/?probe=9e12130a28) | Nov 04, 2023 |
| HP            | 246 G6 Notebook PC          | [cd997e5a97](https://linux-hardware.org/?probe=cd997e5a97) | Nov 03, 2023 |
| Dell          | Inspiron N4010              | [f8aed4abab](https://linux-hardware.org/?probe=f8aed4abab) | Nov 03, 2023 |
| Dell          | Latitude 3420               | [9211e0f588](https://linux-hardware.org/?probe=9211e0f588) | Nov 03, 2023 |
| Multilaser    | PC13X                       | [1c6a314055](https://linux-hardware.org/?probe=1c6a314055) | Nov 03, 2023 |
| Acer          | Aspire 5750                 | [429b14ee32](https://linux-hardware.org/?probe=429b14ee32) | Nov 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [6987861086](https://linux-hardware.org/?probe=6987861086) | Nov 03, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [5d06dbbe5f](https://linux-hardware.org/?probe=5d06dbbe5f) | Nov 03, 2023 |
| Dell          | Inspiron 5547               | [e14eb66450](https://linux-hardware.org/?probe=e14eb66450) | Nov 03, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [9552d5f729](https://linux-hardware.org/?probe=9552d5f729) | Nov 02, 2023 |
| Acer          | AO722                       | [3464dc7b3c](https://linux-hardware.org/?probe=3464dc7b3c) | Nov 02, 2023 |
| Dell          | Latitude 3440               | [b50ed47992](https://linux-hardware.org/?probe=b50ed47992) | Nov 02, 2023 |
| Dell          | Latitude 3440               | [9426910684](https://linux-hardware.org/?probe=9426910684) | Nov 02, 2023 |
| HP            | ZBook 17 G5                 | [4377844e75](https://linux-hardware.org/?probe=4377844e75) | Nov 02, 2023 |
| Samsung       | 960XFH                      | [6076e144ac](https://linux-hardware.org/?probe=6076e144ac) | Nov 01, 2023 |
| Apple         | MacBookPro8,1               | [b03928bc33](https://linux-hardware.org/?probe=b03928bc33) | Nov 01, 2023 |
| Dell          | Inspiron 5502               | [a1d2f7988e](https://linux-hardware.org/?probe=a1d2f7988e) | Nov 01, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [643c7ccd9b](https://linux-hardware.org/?probe=643c7ccd9b) | Nov 01, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [446efaf1bb](https://linux-hardware.org/?probe=446efaf1bb) | Oct 31, 2023 |
| Apple         | MacBookPro8,1               | [27c6a9540f](https://linux-hardware.org/?probe=27c6a9540f) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | [5b8af0fd77](https://linux-hardware.org/?probe=5b8af0fd77) | Oct 31, 2023 |
| Dell          | G15 5515                    | [c59e97ba9e](https://linux-hardware.org/?probe=c59e97ba9e) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [40ae523147](https://linux-hardware.org/?probe=40ae523147) | Oct 31, 2023 |
| HP            | ProBook 645 G1              | [b637cedab4](https://linux-hardware.org/?probe=b637cedab4) | Oct 31, 2023 |
| Dell          | Latitude 5400               | [e7f91d1c69](https://linux-hardware.org/?probe=e7f91d1c69) | Oct 30, 2023 |
| LG Electro... | 14Z980-G.BH51P1             | [879ba00b91](https://linux-hardware.org/?probe=879ba00b91) | Oct 30, 2023 |
| Acer          | Aspire 5733                 | [8a925b3630](https://linux-hardware.org/?probe=8a925b3630) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [931f0ed896](https://linux-hardware.org/?probe=931f0ed896) | Oct 30, 2023 |
| Dell          | Inspiron N4050              | [7d5dc09b04](https://linux-hardware.org/?probe=7d5dc09b04) | Oct 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE13    | [28a8f59777](https://linux-hardware.org/?probe=28a8f59777) | Oct 29, 2023 |
| Sony          | VPCCW13FB                   | [96516448b2](https://linux-hardware.org/?probe=96516448b2) | Oct 29, 2023 |
| Sony          | VPCCW13FB                   | [7092dfafd9](https://linux-hardware.org/?probe=7092dfafd9) | Oct 29, 2023 |
| Samsung       | 370E4K                      | [78ec3e796a](https://linux-hardware.org/?probe=78ec3e796a) | Oct 28, 2023 |
| Acer          | Aspire V3-571               | [6aa696ac55](https://linux-hardware.org/?probe=6aa696ac55) | Oct 28, 2023 |
| Samsung       | 550XCJ/550XCR               | [9d34ff8710](https://linux-hardware.org/?probe=9d34ff8710) | Oct 27, 2023 |
| Acer          | Aspire A315-42G             | [114e1e6d66](https://linux-hardware.org/?probe=114e1e6d66) | Oct 27, 2023 |
| Sony          | SVS13A25PBS                 | [7cb087bd2d](https://linux-hardware.org/?probe=7cb087bd2d) | Oct 27, 2023 |
| Avell High... | 1513 Mxti                   | [9f5d60c02b](https://linux-hardware.org/?probe=9f5d60c02b) | Oct 27, 2023 |
| Acer          | Nitro AN515-47              | [8516768801](https://linux-hardware.org/?probe=8516768801) | Oct 26, 2023 |
| Acer          | Aspire 5050                 | [2129ab3e24](https://linux-hardware.org/?probe=2129ab3e24) | Oct 26, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [2bee900f03](https://linux-hardware.org/?probe=2bee900f03) | Oct 26, 2023 |
| Dell          | Inspiron 3437               | [a57068abbc](https://linux-hardware.org/?probe=a57068abbc) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c9e8482167](https://linux-hardware.org/?probe=c9e8482167) | Oct 26, 2023 |
| Lenovo        | Y720-15IKB 81CQ             | [7aec151a1c](https://linux-hardware.org/?probe=7aec151a1c) | Oct 25, 2023 |
| Dell          | Inspiron 3442               | [7fc2a154e5](https://linux-hardware.org/?probe=7fc2a154e5) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [9a4561dabf](https://linux-hardware.org/?probe=9a4561dabf) | Oct 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [76d22d10e6](https://linux-hardware.org/?probe=76d22d10e6) | Oct 25, 2023 |
| Samsung       | 270E5J/2570EJ               | [94f358053d](https://linux-hardware.org/?probe=94f358053d) | Oct 24, 2023 |
| Dell          | Vostro 3550                 | [2fb1e4bb71](https://linux-hardware.org/?probe=2fb1e4bb71) | Oct 24, 2023 |
| Samsung       | 670Z5E                      | [101b5bda5b](https://linux-hardware.org/?probe=101b5bda5b) | Oct 24, 2023 |
| Dell          | Inspiron 15-3567            | [879198d56a](https://linux-hardware.org/?probe=879198d56a) | Oct 24, 2023 |
| Dell          | Inspiron 15-3567            | [0e451d6616](https://linux-hardware.org/?probe=0e451d6616) | Oct 24, 2023 |
| Lenovo        | Y720-15IKB 81CQ             | [c0601dc338](https://linux-hardware.org/?probe=c0601dc338) | Oct 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [744dddac21](https://linux-hardware.org/?probe=744dddac21) | Oct 24, 2023 |
| Alienware     | m15 R6                      | [c6711f7b02](https://linux-hardware.org/?probe=c6711f7b02) | Oct 24, 2023 |
| Valve         | Jupiter                     | [83d3faf177](https://linux-hardware.org/?probe=83d3faf177) | Oct 23, 2023 |
| Dell          | Inspiron 7559               | [24a664955f](https://linux-hardware.org/?probe=24a664955f) | Oct 23, 2023 |
| Acer          | Aspire A315-42G             | [65494c95ec](https://linux-hardware.org/?probe=65494c95ec) | Oct 23, 2023 |
| Dell          | Inspiron 7559               | [c931b1ef73](https://linux-hardware.org/?probe=c931b1ef73) | Oct 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [da2cda923f](https://linux-hardware.org/?probe=da2cda923f) | Oct 23, 2023 |
| Dell          | Vostro 3400                 | [9c24bc3329](https://linux-hardware.org/?probe=9c24bc3329) | Oct 23, 2023 |
| Samsung       | RF511/RF411/RF711           | [6a62fa5cb6](https://linux-hardware.org/?probe=6a62fa5cb6) | Oct 23, 2023 |
| HP            | Pavilion dv7                | [c3e7ebfd20](https://linux-hardware.org/?probe=c3e7ebfd20) | Oct 23, 2023 |
| Acer          | Aspire E5-573               | [d83f4bf9ad](https://linux-hardware.org/?probe=d83f4bf9ad) | Oct 23, 2023 |
| Dell          | G15 5515                    | [758d007f45](https://linux-hardware.org/?probe=758d007f45) | Oct 23, 2023 |
| Dell          | G15 5515                    | [5853f5312f](https://linux-hardware.org/?probe=5853f5312f) | Oct 23, 2023 |
| Positivo      | C4128G-15                   | [8d9aa2f206](https://linux-hardware.org/?probe=8d9aa2f206) | Oct 23, 2023 |
| Acer          | Aspire A315-58              | [60402f4ad8](https://linux-hardware.org/?probe=60402f4ad8) | Oct 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [48d2114a2e](https://linux-hardware.org/?probe=48d2114a2e) | Oct 22, 2023 |
| HP            | Folio 13                    | [b7ed500d93](https://linux-hardware.org/?probe=b7ed500d93) | Oct 22, 2023 |
| Clevo         | M660SR                      | [56f8ab01f9](https://linux-hardware.org/?probe=56f8ab01f9) | Oct 22, 2023 |
| Dell          | Inspiron 3437               | [331cbd427d](https://linux-hardware.org/?probe=331cbd427d) | Oct 21, 2023 |
| HP            | Pavilion dv7                | [3379c8b4e7](https://linux-hardware.org/?probe=3379c8b4e7) | Oct 21, 2023 |
| Notebook      | NJx0MU                      | [961c369ea4](https://linux-hardware.org/?probe=961c369ea4) | Oct 21, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [ad7ca8e192](https://linux-hardware.org/?probe=ad7ca8e192) | Oct 21, 2023 |
| Notebook      | NJx0MU                      | [f19c18154b](https://linux-hardware.org/?probe=f19c18154b) | Oct 21, 2023 |
| Gateway       | NV55C                       | [bb0eb9e5dd](https://linux-hardware.org/?probe=bb0eb9e5dd) | Oct 21, 2023 |
| Acer          | Aspire A315-23              | [d3b1d639f5](https://linux-hardware.org/?probe=d3b1d639f5) | Oct 21, 2023 |
| Compaq        | 434                         | [094bba21f8](https://linux-hardware.org/?probe=094bba21f8) | Oct 21, 2023 |
| LG Electro... | R410-G.BP21P1               | [36849f1a4c](https://linux-hardware.org/?probe=36849f1a4c) | Oct 21, 2023 |
| HP            | Folio 13                    | [99ff48ac3f](https://linux-hardware.org/?probe=99ff48ac3f) | Oct 20, 2023 |
| Avell High... | B.ON                        | [7f8ce9da76](https://linux-hardware.org/?probe=7f8ce9da76) | Oct 20, 2023 |
| Samsung       | 670Z5E                      | [ddc0c78bff](https://linux-hardware.org/?probe=ddc0c78bff) | Oct 20, 2023 |
| Dell          | Latitude 3490               | [174ee1b12e](https://linux-hardware.org/?probe=174ee1b12e) | Oct 20, 2023 |
| Dell          | Vostro 3300                 | [827b95e65c](https://linux-hardware.org/?probe=827b95e65c) | Oct 20, 2023 |
| Acer          | Nitro AN515-51              | [be03ed57d8](https://linux-hardware.org/?probe=be03ed57d8) | Oct 20, 2023 |
| Acer          | Nitro AN515-51              | [e648a8c32a](https://linux-hardware.org/?probe=e648a8c32a) | Oct 20, 2023 |
| Acer          | Aspire A315-42G             | [46d5d338b3](https://linux-hardware.org/?probe=46d5d338b3) | Oct 20, 2023 |
| Dell          | Vostro 3550                 | [db4e9dfc27](https://linux-hardware.org/?probe=db4e9dfc27) | Oct 20, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0506dfa238](https://linux-hardware.org/?probe=0506dfa238) | Oct 19, 2023 |
| Dell          | Vostro 3560                 | [aa95d1c178](https://linux-hardware.org/?probe=aa95d1c178) | Oct 19, 2023 |
| Dell          | Inspiron 5547               | [3dc947b334](https://linux-hardware.org/?probe=3dc947b334) | Oct 19, 2023 |
| Samsung       | 670Z5E                      | [aeec82cef9](https://linux-hardware.org/?probe=aeec82cef9) | Oct 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [e94e48868c](https://linux-hardware.org/?probe=e94e48868c) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | [abafeadb35](https://linux-hardware.org/?probe=abafeadb35) | Oct 19, 2023 |
| Compaq        | Presario CQ-23              | [15c10707d0](https://linux-hardware.org/?probe=15c10707d0) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | [ab3c18427d](https://linux-hardware.org/?probe=ab3c18427d) | Oct 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a8e2b482f4](https://linux-hardware.org/?probe=a8e2b482f4) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ab21923ddd](https://linux-hardware.org/?probe=ab21923ddd) | Oct 19, 2023 |
| Dell          | Inspiron 15-3567            | [486e66cdee](https://linux-hardware.org/?probe=486e66cdee) | Oct 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [495a705c9e](https://linux-hardware.org/?probe=495a705c9e) | Oct 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [315376a82a](https://linux-hardware.org/?probe=315376a82a) | Oct 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [cf6314850a](https://linux-hardware.org/?probe=cf6314850a) | Oct 18, 2023 |
| Positivo      | Mobile                      | [5dedeac18e](https://linux-hardware.org/?probe=5dedeac18e) | Oct 18, 2023 |
| Sony          | VPCEA23FB                   | [dbfa513b31](https://linux-hardware.org/?probe=dbfa513b31) | Oct 18, 2023 |
| Acer          | Nitro AN515-54              | [877ec2dd85](https://linux-hardware.org/?probe=877ec2dd85) | Oct 18, 2023 |
| Dell          | Inspiron 15-3567            | [d77237b330](https://linux-hardware.org/?probe=d77237b330) | Oct 18, 2023 |
| Samsung       | 670Z5E                      | [65ee0747bc](https://linux-hardware.org/?probe=65ee0747bc) | Oct 18, 2023 |
| Lenovo        | B330S-15IKBR 81JV           | [5df1834272](https://linux-hardware.org/?probe=5df1834272) | Oct 18, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [041aba02ce](https://linux-hardware.org/?probe=041aba02ce) | Oct 17, 2023 |
| Dell          | Inspiron 7559               | [6280e4287a](https://linux-hardware.org/?probe=6280e4287a) | Oct 17, 2023 |
| Lenovo        | B330S-15IKBR 81JV           | [9e1356181f](https://linux-hardware.org/?probe=9e1356181f) | Oct 17, 2023 |
| Dell          | Inspiron 5448               | [5901b49079](https://linux-hardware.org/?probe=5901b49079) | Oct 17, 2023 |
| Apple         | MacBookPro11,1              | [33cba76fe6](https://linux-hardware.org/?probe=33cba76fe6) | Oct 17, 2023 |
| HP            | Folio 13 - 2000             | [c541a1603c](https://linux-hardware.org/?probe=c541a1603c) | Oct 17, 2023 |
| Dell          | Vostro 3550                 | [25ba718720](https://linux-hardware.org/?probe=25ba718720) | Oct 16, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [d271c61b92](https://linux-hardware.org/?probe=d271c61b92) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Dell          | XPS 13 9300                 | [e66f442843](https://linux-hardware.org/?probe=e66f442843) | Oct 16, 2023 |
| Dell          | XPS 13 9300                 | [eab86d1cc0](https://linux-hardware.org/?probe=eab86d1cc0) | Oct 16, 2023 |
| Positivo      | Q4128C-S                    | [ea1c91d413](https://linux-hardware.org/?probe=ea1c91d413) | Oct 16, 2023 |
| Acer          | Aspire E5-571               | [fcc76a61ae](https://linux-hardware.org/?probe=fcc76a61ae) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| Acer          | Nitro AN515-52              | [7f9e09a9e1](https://linux-hardware.org/?probe=7f9e09a9e1) | Oct 16, 2023 |
| Acer          | Nitro AN515-52              | [2571e4fd1b](https://linux-hardware.org/?probe=2571e4fd1b) | Oct 16, 2023 |
| Avell High... | C62 MOB                     | [116667b041](https://linux-hardware.org/?probe=116667b041) | Oct 16, 2023 |
| HP            | Pavilion dv6                | [4faf7bb285](https://linux-hardware.org/?probe=4faf7bb285) | Oct 15, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [90b07f2a8b](https://linux-hardware.org/?probe=90b07f2a8b) | Oct 15, 2023 |
| HP            | Pavilion dv6                | [52e554d0dc](https://linux-hardware.org/?probe=52e554d0dc) | Oct 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [c12987d53a](https://linux-hardware.org/?probe=c12987d53a) | Oct 15, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [079342de2b](https://linux-hardware.org/?probe=079342de2b) | Oct 15, 2023 |
| Dell          | Inspiron N5010              | [9dae04bd63](https://linux-hardware.org/?probe=9dae04bd63) | Oct 15, 2023 |
| Acer          | Nitro AN517-54              | [2f6c2f44d3](https://linux-hardware.org/?probe=2f6c2f44d3) | Oct 15, 2023 |
| Samsung       | 550XCJ/550XCR               | [579dc4dabc](https://linux-hardware.org/?probe=579dc4dabc) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [33a143a23d](https://linux-hardware.org/?probe=33a143a23d) | Oct 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3c91ad6491](https://linux-hardware.org/?probe=3c91ad6491) | Oct 14, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [160af8609e](https://linux-hardware.org/?probe=160af8609e) | Oct 14, 2023 |
| Dell          | Inspiron 3501               | [a1ada382fa](https://linux-hardware.org/?probe=a1ada382fa) | Oct 14, 2023 |
| HP            | ProBook 640 G1              | [b00d98a451](https://linux-hardware.org/?probe=b00d98a451) | Oct 14, 2023 |
| HP            | ProBook 640 G1              | [15168951ed](https://linux-hardware.org/?probe=15168951ed) | Oct 13, 2023 |
| Samsung       | 550XBE/350XBE               | [27ea9922a6](https://linux-hardware.org/?probe=27ea9922a6) | Oct 13, 2023 |
| Dell          | Inspiron 5548               | [edb6e06451](https://linux-hardware.org/?probe=edb6e06451) | Oct 13, 2023 |
| Digibras      | NH4CU53                     | [40f4cfc21c](https://linux-hardware.org/?probe=40f4cfc21c) | Oct 13, 2023 |
| Acer          | Aspire A515-45              | [f5e57e4558](https://linux-hardware.org/?probe=f5e57e4558) | Oct 13, 2023 |
| Acer          | Nitro AN515-44              | [1f1524c080](https://linux-hardware.org/?probe=1f1524c080) | Oct 13, 2023 |
| Acer          | Nitro AN515-47              | [0592faaf34](https://linux-hardware.org/?probe=0592faaf34) | Oct 12, 2023 |
| Acer          | Nitro AN515-44              | [65b1e10033](https://linux-hardware.org/?probe=65b1e10033) | Oct 12, 2023 |
| Acer          | Nitro AN515-44              | [6d2fdd060b](https://linux-hardware.org/?probe=6d2fdd060b) | Oct 12, 2023 |
| Acer          | Aspire E1-571               | [94754c98ce](https://linux-hardware.org/?probe=94754c98ce) | Oct 12, 2023 |
| Dell          | Latitude 3490               | [1c5aa8fca4](https://linux-hardware.org/?probe=1c5aa8fca4) | Oct 12, 2023 |
| Apple         | MacBookPro5,4               | [f68b19bbe5](https://linux-hardware.org/?probe=f68b19bbe5) | Oct 12, 2023 |
| Acer          | Aspire VX5-591G             | [586d280ca5](https://linux-hardware.org/?probe=586d280ca5) | Oct 12, 2023 |
| Dell          | Vostro 5490                 | [616aecbfbd](https://linux-hardware.org/?probe=616aecbfbd) | Oct 11, 2023 |
| Gateway       | NE570                       | [533fec5226](https://linux-hardware.org/?probe=533fec5226) | Oct 11, 2023 |
| Avell High... | B.ON                        | [3a419fbd20](https://linux-hardware.org/?probe=3a419fbd20) | Oct 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [19f231af9a](https://linux-hardware.org/?probe=19f231af9a) | Oct 11, 2023 |
| Dell          | Vostro 1510                 | [6324053514](https://linux-hardware.org/?probe=6324053514) | Oct 10, 2023 |
| Avell High... | C62 MOB                     | [0e1ec62b3b](https://linux-hardware.org/?probe=0e1ec62b3b) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c0882707d4](https://linux-hardware.org/?probe=c0882707d4) | Oct 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c397035651](https://linux-hardware.org/?probe=c397035651) | Oct 10, 2023 |
| Dell          | Latitude E6420              | [7508b7cf4f](https://linux-hardware.org/?probe=7508b7cf4f) | Oct 10, 2023 |
| Apple         | MacBookPro11,1              | [8a64a738ca](https://linux-hardware.org/?probe=8a64a738ca) | Oct 10, 2023 |
| Apple         | MacBookPro8,1               | [2192f74b2d](https://linux-hardware.org/?probe=2192f74b2d) | Oct 09, 2023 |
| Dell          | Inspiron 3421               | [1da5f9aefa](https://linux-hardware.org/?probe=1da5f9aefa) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Lenovo        | ThinkPad T490 20N3S8HL00    | [e75ca9bf06](https://linux-hardware.org/?probe=e75ca9bf06) | Oct 09, 2023 |
| Lenovo        | G480 20149                  | [ff58b011f2](https://linux-hardware.org/?probe=ff58b011f2) | Oct 09, 2023 |
| Dell          | Inspiron 3583               | [f2fe39dcc0](https://linux-hardware.org/?probe=f2fe39dcc0) | Oct 09, 2023 |
| Dell          | Inspiron 3583               | [f78bda610e](https://linux-hardware.org/?probe=f78bda610e) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [508c438c6a](https://linux-hardware.org/?probe=508c438c6a) | Oct 09, 2023 |
| Dell          | Vostro 7590                 | [d7188e68cb](https://linux-hardware.org/?probe=d7188e68cb) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 20RB0028BR     | [bb9133e0b8](https://linux-hardware.org/?probe=bb9133e0b8) | Oct 08, 2023 |
| Dell          | Inspiron 3421               | [b8557f2880](https://linux-hardware.org/?probe=b8557f2880) | Oct 08, 2023 |
| Dell          | Inspiron 3576               | [7e5e46c41a](https://linux-hardware.org/?probe=7e5e46c41a) | Oct 08, 2023 |
| Acer          | Swift SF514-56T             | [0d2d2cf2ae](https://linux-hardware.org/?probe=0d2d2cf2ae) | Oct 08, 2023 |
| HP            | ENVY dv7                    | [05ca6a125d](https://linux-hardware.org/?probe=05ca6a125d) | Oct 08, 2023 |
| HP            | Folio 13                    | [f4ed29d660](https://linux-hardware.org/?probe=f4ed29d660) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [3e5383da88](https://linux-hardware.org/?probe=3e5383da88) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [cab160aff3](https://linux-hardware.org/?probe=cab160aff3) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | [907f3a4cf1](https://linux-hardware.org/?probe=907f3a4cf1) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | [d003fa7343](https://linux-hardware.org/?probe=d003fa7343) | Oct 08, 2023 |
| ASUSTek       | G60JX                       | [e455f7fb08](https://linux-hardware.org/?probe=e455f7fb08) | Oct 08, 2023 |
| ASUSTek       | G60JX                       | [335e991de2](https://linux-hardware.org/?probe=335e991de2) | Oct 08, 2023 |
| Acer          | Aspire ES1-572              | [ac5943ef0c](https://linux-hardware.org/?probe=ac5943ef0c) | Oct 08, 2023 |
| Acer          | Swift SF514-56T             | [9f94f8934f](https://linux-hardware.org/?probe=9f94f8934f) | Oct 07, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | [d375cfe649](https://linux-hardware.org/?probe=d375cfe649) | Oct 07, 2023 |
| Samsung       | 960XFH                      | [0d8aca1f6e](https://linux-hardware.org/?probe=0d8aca1f6e) | Oct 07, 2023 |
| Samsung       | 960XFH                      | [a2138fa3f8](https://linux-hardware.org/?probe=a2138fa3f8) | Oct 07, 2023 |
| Alienware     | m15 R7                      | [7bd2b6300f](https://linux-hardware.org/?probe=7bd2b6300f) | Oct 07, 2023 |
| Dell          | Latitude 3490               | [723d6797ae](https://linux-hardware.org/?probe=723d6797ae) | Oct 07, 2023 |
| Dell          | Inspiron 5421               | [90c1f511a6](https://linux-hardware.org/?probe=90c1f511a6) | Oct 06, 2023 |
| Dell          | Vostro 1510                 | [39ee83fbf5](https://linux-hardware.org/?probe=39ee83fbf5) | Oct 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [62c8d86cfa](https://linux-hardware.org/?probe=62c8d86cfa) | Oct 06, 2023 |
| Acer          | Aspire ES1-572              | [2e48163fbd](https://linux-hardware.org/?probe=2e48163fbd) | Oct 06, 2023 |
| Sony          | VGN-SR150A                  | [f8fcbe4227](https://linux-hardware.org/?probe=f8fcbe4227) | Oct 06, 2023 |
| Positivo B... | VJFE55F11X-B0211H           | [8d54d8438d](https://linux-hardware.org/?probe=8d54d8438d) | Oct 05, 2023 |
| Acer          | Aspire ES1-572              | [651a8f8f97](https://linux-hardware.org/?probe=651a8f8f97) | Oct 05, 2023 |
| Apple         | MacBookPro11,1              | [e346a58990](https://linux-hardware.org/?probe=e346a58990) | Oct 05, 2023 |
| Philco Inf... | EC10IS2                     | [f85315b46a](https://linux-hardware.org/?probe=f85315b46a) | Oct 04, 2023 |
| Dell          | Inspiron 5490               | [5ab40107ce](https://linux-hardware.org/?probe=5ab40107ce) | Oct 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a49cef1179](https://linux-hardware.org/?probe=a49cef1179) | Oct 04, 2023 |
| Positivo      | S14BW01                     | [3027fc7d9b](https://linux-hardware.org/?probe=3027fc7d9b) | Oct 04, 2023 |
| Dell          | Inspiron 5575               | [48afb4262c](https://linux-hardware.org/?probe=48afb4262c) | Oct 04, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7bb81b99a0](https://linux-hardware.org/?probe=7bb81b99a0) | Oct 04, 2023 |
| Dell          | Inspiron 5547               | [06d30a9c8d](https://linux-hardware.org/?probe=06d30a9c8d) | Oct 03, 2023 |
| Apple         | MacBookPro8,1               | [cf2552023d](https://linux-hardware.org/?probe=cf2552023d) | Oct 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [5813f8d107](https://linux-hardware.org/?probe=5813f8d107) | Oct 03, 2023 |
| MSI           | CR620                       | [be490381a9](https://linux-hardware.org/?probe=be490381a9) | Oct 03, 2023 |
| Dell          | Inspiron 5558               | [81c44f8b56](https://linux-hardware.org/?probe=81c44f8b56) | Oct 03, 2023 |
| Dell          | Inspiron 5480               | [666fbb9e46](https://linux-hardware.org/?probe=666fbb9e46) | Oct 03, 2023 |
| ASUSTek       | K45VM                       | [b4f51ced7a](https://linux-hardware.org/?probe=b4f51ced7a) | Oct 02, 2023 |
| Dell          | Latitude E6420              | [90883fd019](https://linux-hardware.org/?probe=90883fd019) | Oct 02, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [9574c05fb2](https://linux-hardware.org/?probe=9574c05fb2) | Oct 02, 2023 |
| Compaq        | 420                         | [b327579e60](https://linux-hardware.org/?probe=b327579e60) | Oct 02, 2023 |
| HP            | Victus by Gaming Laptop ... | [60a8a7d13f](https://linux-hardware.org/?probe=60a8a7d13f) | Oct 02, 2023 |
| HP            | Victus by Gaming Laptop ... | [28a54d8189](https://linux-hardware.org/?probe=28a54d8189) | Oct 02, 2023 |
| Dell          | Inspiron 5437               | [a348906862](https://linux-hardware.org/?probe=a348906862) | Oct 02, 2023 |
| Notebook      | NJx0MU                      | [f510af1acf](https://linux-hardware.org/?probe=f510af1acf) | Oct 01, 2023 |
| Dell          | Inspiron 15 3515            | [44bfa52d57](https://linux-hardware.org/?probe=44bfa52d57) | Oct 01, 2023 |
| Dell          | Inspiron 7580               | [8fa784881e](https://linux-hardware.org/?probe=8fa784881e) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | [7b44ef8cd1](https://linux-hardware.org/?probe=7b44ef8cd1) | Oct 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [b79529501a](https://linux-hardware.org/?probe=b79529501a) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | [a1f20bb140](https://linux-hardware.org/?probe=a1f20bb140) | Sep 30, 2023 |
| Notebook      | NJx0MU                      | [1449844643](https://linux-hardware.org/?probe=1449844643) | Sep 30, 2023 |
| Tectoy        | Pense Bem Notebook          | [6a6e6af34c](https://linux-hardware.org/?probe=6a6e6af34c) | Sep 29, 2023 |
| Positivo      | C14CR01                     | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [772e866a05](https://linux-hardware.org/?probe=772e866a05) | Sep 29, 2023 |
| Dell          | Inspiron 5437               | [c0301c2fbb](https://linux-hardware.org/?probe=c0301c2fbb) | Sep 29, 2023 |
| Acer          | Nitro AN515-43              | [e55a394d41](https://linux-hardware.org/?probe=e55a394d41) | Sep 29, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [ccc715eeb6](https://linux-hardware.org/?probe=ccc715eeb6) | Sep 29, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81JN     | [747f0d45fe](https://linux-hardware.org/?probe=747f0d45fe) | Sep 28, 2023 |
| Dell          | Vostro 5470                 | [b6f9976e23](https://linux-hardware.org/?probe=b6f9976e23) | Sep 28, 2023 |
| ASUSTek       | K45VM                       | [6c167e69a4](https://linux-hardware.org/?probe=6c167e69a4) | Sep 28, 2023 |
| Acer          | Acadia V1.35                | [c2074b2535](https://linux-hardware.org/?probe=c2074b2535) | Sep 28, 2023 |
| Acer          | Aspire E5-571               | [acd3733ebf](https://linux-hardware.org/?probe=acd3733ebf) | Sep 27, 2023 |
| EUROCOM       | RACER 2.0                   | [4351733d37](https://linux-hardware.org/?probe=4351733d37) | Sep 27, 2023 |
| Samsung       | 550XDA                      | [ab1fabfe9b](https://linux-hardware.org/?probe=ab1fabfe9b) | Sep 27, 2023 |
| Dell          | System XPS L502X            | [06d6fd95d1](https://linux-hardware.org/?probe=06d6fd95d1) | Sep 27, 2023 |
| Acer          | Aspire A315-53              | [c20a9f8f96](https://linux-hardware.org/?probe=c20a9f8f96) | Sep 27, 2023 |
| Dell          | G15 5520                    | [64cfeba3ee](https://linux-hardware.org/?probe=64cfeba3ee) | Sep 26, 2023 |
| Dell          | Inspiron 5423               | [a6a3b2697f](https://linux-hardware.org/?probe=a6a3b2697f) | Sep 26, 2023 |
| Dell          | Inspiron 5567               | [6ebf39a37a](https://linux-hardware.org/?probe=6ebf39a37a) | Sep 26, 2023 |
| Dell          | Inspiron 5567               | [644a616222](https://linux-hardware.org/?probe=644a616222) | Sep 26, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [3d8dfdbf80](https://linux-hardware.org/?probe=3d8dfdbf80) | Sep 26, 2023 |
| HP            | Folio 13                    | [a5a1ae29a7](https://linux-hardware.org/?probe=a5a1ae29a7) | Sep 26, 2023 |
| Notebook      | NJx0MU                      | [89d81885ff](https://linux-hardware.org/?probe=89d81885ff) | Sep 26, 2023 |
| Intel         | W7645                       | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| HP            | Presario CQ43               | [c206dc84ad](https://linux-hardware.org/?probe=c206dc84ad) | Sep 25, 2023 |
| Acer          | Aspire F5-573G              | [a2f6814940](https://linux-hardware.org/?probe=a2f6814940) | Sep 25, 2023 |
| Dell          | Latitude E5440              | [f4accb1cb0](https://linux-hardware.org/?probe=f4accb1cb0) | Sep 25, 2023 |
| Dell          | XPS 13 9380                 | [705c3fdeff](https://linux-hardware.org/?probe=705c3fdeff) | Sep 25, 2023 |
| Acer          | Aspire E5-571               | [e74a87d3f4](https://linux-hardware.org/?probe=e74a87d3f4) | Sep 25, 2023 |
| HP            | Presario CQ43               | [b2663eb2fa](https://linux-hardware.org/?probe=b2663eb2fa) | Sep 25, 2023 |
| Acer          | Nitro AN515-51              | [6d6d719f30](https://linux-hardware.org/?probe=6d6d719f30) | Sep 25, 2023 |
| Acer          | Aspire R3-131T              | [c643f10970](https://linux-hardware.org/?probe=c643f10970) | Sep 24, 2023 |
| Samsung       | 550XBE/350XBE               | [cdbacef976](https://linux-hardware.org/?probe=cdbacef976) | Sep 24, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [eb82ffb863](https://linux-hardware.org/?probe=eb82ffb863) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d71e760b5c](https://linux-hardware.org/?probe=d71e760b5c) | Sep 24, 2023 |
| Notebook      | NJx0MU                      | [84bba5e5a7](https://linux-hardware.org/?probe=84bba5e5a7) | Sep 24, 2023 |
| HP            | Presario CQ43               | [d5ee5e4318](https://linux-hardware.org/?probe=d5ee5e4318) | Sep 23, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [7022eac21d](https://linux-hardware.org/?probe=7022eac21d) | Sep 23, 2023 |
| Valve         | Jupiter                     | [287bf4d933](https://linux-hardware.org/?probe=287bf4d933) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [04141bd71c](https://linux-hardware.org/?probe=04141bd71c) | Sep 22, 2023 |
| Dell          | Latitude E7440              | [53e90ca355](https://linux-hardware.org/?probe=53e90ca355) | Sep 22, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [65a21a4968](https://linux-hardware.org/?probe=65a21a4968) | Sep 22, 2023 |
| HP            | Folio 13                    | [66f8752b64](https://linux-hardware.org/?probe=66f8752b64) | Sep 22, 2023 |
| Lenovo        | ThinkPad X220 4286BB2       | [a3b217a707](https://linux-hardware.org/?probe=a3b217a707) | Sep 21, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [dd328a6f1f](https://linux-hardware.org/?probe=dd328a6f1f) | Sep 21, 2023 |
| Samsung       | 550XBE/350XBE               | [522d50a437](https://linux-hardware.org/?probe=522d50a437) | Sep 21, 2023 |
| Samsung       | 550XDA                      | [2d15b3f4ca](https://linux-hardware.org/?probe=2d15b3f4ca) | Sep 21, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [5a74bb7dde](https://linux-hardware.org/?probe=5a74bb7dde) | Sep 20, 2023 |
| Dell          | XPS 13 9300                 | [49bb68e979](https://linux-hardware.org/?probe=49bb68e979) | Sep 20, 2023 |
| ASUSTek       | Z450UA                      | [60d85e59da](https://linux-hardware.org/?probe=60d85e59da) | Sep 20, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [16b2b018c1](https://linux-hardware.org/?probe=16b2b018c1) | Sep 20, 2023 |
| Chuwi         | GemiBook Pro                | [d8305c7c45](https://linux-hardware.org/?probe=d8305c7c45) | Sep 20, 2023 |
| Samsung       | 960XFH                      | [c25c858bd4](https://linux-hardware.org/?probe=c25c858bd4) | Sep 19, 2023 |
| Chuwi         | GemiBook Pro                | [7ff48f538f](https://linux-hardware.org/?probe=7ff48f538f) | Sep 19, 2023 |
| Dell          | Inspiron 3442               | [1f6ca2e4f7](https://linux-hardware.org/?probe=1f6ca2e4f7) | Sep 19, 2023 |
| Samsung       | 550XDA                      | [763631bfe7](https://linux-hardware.org/?probe=763631bfe7) | Sep 19, 2023 |
| Daten Tecn... | DT02-M4                     | [67c158a4f1](https://linux-hardware.org/?probe=67c158a4f1) | Sep 19, 2023 |
| Dell          | XPS 15 9560                 | [28d0c94948](https://linux-hardware.org/?probe=28d0c94948) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | [d68a92e72a](https://linux-hardware.org/?probe=d68a92e72a) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | [8b335d6bb0](https://linux-hardware.org/?probe=8b335d6bb0) | Sep 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0ec89ecd46](https://linux-hardware.org/?probe=0ec89ecd46) | Sep 19, 2023 |
| Acer          | Aspire 5742                 | [430ed1fe6c](https://linux-hardware.org/?probe=430ed1fe6c) | Sep 19, 2023 |
| HP            | Compaq Mini 311-1100        | [418d54b71d](https://linux-hardware.org/?probe=418d54b71d) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0b036a6058](https://linux-hardware.org/?probe=0b036a6058) | Sep 18, 2023 |
| Dell          | XPS 15 9510                 | [5701fbde3e](https://linux-hardware.org/?probe=5701fbde3e) | Sep 18, 2023 |
| Dell          | Inspiron 5480               | [51aca22643](https://linux-hardware.org/?probe=51aca22643) | Sep 18, 2023 |
| Dell          | XPS 15 9510                 | [514a5308f2](https://linux-hardware.org/?probe=514a5308f2) | Sep 18, 2023 |
| ASUSTek       | X450CA                      | [b43a3aa61c](https://linux-hardware.org/?probe=b43a3aa61c) | Sep 18, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [aebeeb7401](https://linux-hardware.org/?probe=aebeeb7401) | Sep 17, 2023 |
| Apple         | MacBookPro9,2               | [b8459514db](https://linux-hardware.org/?probe=b8459514db) | Sep 17, 2023 |
| Dell          | Inspiron 5566               | [56f2d4d1eb](https://linux-hardware.org/?probe=56f2d4d1eb) | Sep 17, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [48ea99b656](https://linux-hardware.org/?probe=48ea99b656) | Sep 16, 2023 |
| Acer          | Aspire 5750Z                | [d42482a830](https://linux-hardware.org/?probe=d42482a830) | Sep 16, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [f95cfdee8d](https://linux-hardware.org/?probe=f95cfdee8d) | Sep 16, 2023 |
| Dell          | Latitude E6430              | [a426075604](https://linux-hardware.org/?probe=a426075604) | Sep 16, 2023 |
| Compaq        | 420                         | [a0ce747ff2](https://linux-hardware.org/?probe=a0ce747ff2) | Sep 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4298a1ab82](https://linux-hardware.org/?probe=4298a1ab82) | Sep 16, 2023 |
| Digibras      | CL341                       | [a358f5d40c](https://linux-hardware.org/?probe=a358f5d40c) | Sep 15, 2023 |
| Dell          | Vostro 1510                 | [bf4d733039](https://linux-hardware.org/?probe=bf4d733039) | Sep 15, 2023 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | [bc86928972](https://linux-hardware.org/?probe=bc86928972) | Sep 15, 2023 |
| Itautec       | Infoway                     | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| HP            | Folio 13                    | [9ed048b9e4](https://linux-hardware.org/?probe=9ed048b9e4) | Sep 14, 2023 |
| Acer          | Swift SF314-511             | [4714deba45](https://linux-hardware.org/?probe=4714deba45) | Sep 14, 2023 |
| Dell          | Vostro 1520                 | [5d70233702](https://linux-hardware.org/?probe=5d70233702) | Sep 14, 2023 |
| Dell          | Inspiron 5566               | [6c9eaad10e](https://linux-hardware.org/?probe=6c9eaad10e) | Sep 13, 2023 |
| Positivo      | C14CR21                     | [9d48466eab](https://linux-hardware.org/?probe=9d48466eab) | Sep 13, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [df7945af41](https://linux-hardware.org/?probe=df7945af41) | Sep 13, 2023 |
| Dell          | Latitude E4300              | [ed27d2d51c](https://linux-hardware.org/?probe=ed27d2d51c) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Valve         | Jupiter                     | [bee3c23461](https://linux-hardware.org/?probe=bee3c23461) | Sep 12, 2023 |
| Dell          | Inspiron 15-3567            | [cb58094846](https://linux-hardware.org/?probe=cb58094846) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| HP            | EliteBook 840 G6            | [4318e0630c](https://linux-hardware.org/?probe=4318e0630c) | Sep 12, 2023 |
| LG Electro... | C400-G.BC22P1               | [caef8df1be](https://linux-hardware.org/?probe=caef8df1be) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [564a2ea72e](https://linux-hardware.org/?probe=564a2ea72e) | Sep 12, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [68f0df2a6c](https://linux-hardware.org/?probe=68f0df2a6c) | Sep 12, 2023 |
| Dell          | Latitude E6420              | [2a15e9a8e0](https://linux-hardware.org/?probe=2a15e9a8e0) | Sep 12, 2023 |
| Samsung       | 300E4M/300E4S/300E4L        | [a1f824e885](https://linux-hardware.org/?probe=a1f824e885) | Sep 12, 2023 |
| Positivo      | S14CT01                     | [57ed555d4b](https://linux-hardware.org/?probe=57ed555d4b) | Sep 11, 2023 |
| Dell          | Inspiron 5458               | [ab3824f3d0](https://linux-hardware.org/?probe=ab3824f3d0) | Sep 11, 2023 |
| Acer          | Aspire A315-23              | [ecdef7173c](https://linux-hardware.org/?probe=ecdef7173c) | Sep 11, 2023 |
| Acer          | Aspire A515-47              | [fdc2e70c28](https://linux-hardware.org/?probe=fdc2e70c28) | Sep 11, 2023 |
| Dell          | Vostro 3501                 | [7caa16d219](https://linux-hardware.org/?probe=7caa16d219) | Sep 11, 2023 |
| Dell          | Latitude E6420              | [7e57362cdc](https://linux-hardware.org/?probe=7e57362cdc) | Sep 11, 2023 |
| ASUSTek       | X510UAR                     | [671415f9ca](https://linux-hardware.org/?probe=671415f9ca) | Sep 11, 2023 |
| Samsung       | 530XBB                      | [f6039477c2](https://linux-hardware.org/?probe=f6039477c2) | Sep 11, 2023 |
| Sony          | VGN-FZ140E                  | [361226919e](https://linux-hardware.org/?probe=361226919e) | Sep 11, 2023 |
| Samsung       | 550XED                      | [69d754d35b](https://linux-hardware.org/?probe=69d754d35b) | Sep 11, 2023 |
| Samsung       | 550XED                      | [8187eca3e3](https://linux-hardware.org/?probe=8187eca3e3) | Sep 11, 2023 |
| Dell          | Vostro 3550                 | [4f0a6ec78c](https://linux-hardware.org/?probe=4f0a6ec78c) | Sep 10, 2023 |
| Positivo      | C464F                       | [e8154e06d4](https://linux-hardware.org/?probe=e8154e06d4) | Sep 10, 2023 |
| Dell          | G15 5511                    | [c382a29576](https://linux-hardware.org/?probe=c382a29576) | Sep 09, 2023 |
| Lenovo        | V720-14 80Y1                | [ec869beffd](https://linux-hardware.org/?probe=ec869beffd) | Sep 09, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [7403fec062](https://linux-hardware.org/?probe=7403fec062) | Sep 09, 2023 |
| Dell          | Latitude 7390               | [3644f0b002](https://linux-hardware.org/?probe=3644f0b002) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7c5a19bc69](https://linux-hardware.org/?probe=7c5a19bc69) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | [4695b758c9](https://linux-hardware.org/?probe=4695b758c9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | [e8a4fb3aea](https://linux-hardware.org/?probe=e8a4fb3aea) | Sep 08, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [b05fdf4d62](https://linux-hardware.org/?probe=b05fdf4d62) | Sep 08, 2023 |
| Digibras      | NH4CU03                     | [0d0d0bf884](https://linux-hardware.org/?probe=0d0d0bf884) | Sep 07, 2023 |
| HP            | G42                         | [b33a0d0bf6](https://linux-hardware.org/?probe=b33a0d0bf6) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [89772ef854](https://linux-hardware.org/?probe=89772ef854) | Sep 07, 2023 |
| ASUSTek       | N56VZ                       | [37b42fff22](https://linux-hardware.org/?probe=37b42fff22) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c9ea6ff204](https://linux-hardware.org/?probe=c9ea6ff204) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [584a31e54e](https://linux-hardware.org/?probe=584a31e54e) | Sep 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | [2eae1044fc](https://linux-hardware.org/?probe=2eae1044fc) | Sep 07, 2023 |
| Notebook      | NJx0MU                      | [4e54155977](https://linux-hardware.org/?probe=4e54155977) | Sep 07, 2023 |
| Samsung       | 300E5M/300E5L               | [8274cbca33](https://linux-hardware.org/?probe=8274cbca33) | Sep 07, 2023 |
| Acer          | AO722                       | [ae49a1e9c0](https://linux-hardware.org/?probe=ae49a1e9c0) | Sep 07, 2023 |
| Notebook      | NJx0MU                      | [db4ba96400](https://linux-hardware.org/?probe=db4ba96400) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e207539e68](https://linux-hardware.org/?probe=e207539e68) | Sep 07, 2023 |
| Multilaser    | PC31X                       | [96d451c4a5](https://linux-hardware.org/?probe=96d451c4a5) | Sep 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7410c2416c](https://linux-hardware.org/?probe=7410c2416c) | Sep 07, 2023 |
| Alienware     | m15 R7                      | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| Dell          | Inspiron 7460               | [03726302da](https://linux-hardware.org/?probe=03726302da) | Sep 07, 2023 |
| Samsung       | RF511/RF411/RF711           | [ef99cba7a5](https://linux-hardware.org/?probe=ef99cba7a5) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [29f1d7759a](https://linux-hardware.org/?probe=29f1d7759a) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [344a00d524](https://linux-hardware.org/?probe=344a00d524) | Sep 06, 2023 |
| Standard      | MB45II/MB45IN               | [1e46c6aa81](https://linux-hardware.org/?probe=1e46c6aa81) | Sep 06, 2023 |
| Acer          | Aspire E1-571               | [5d22a61587](https://linux-hardware.org/?probe=5d22a61587) | Sep 06, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [ba05ae3ca2](https://linux-hardware.org/?probe=ba05ae3ca2) | Sep 06, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [299a459ec5](https://linux-hardware.org/?probe=299a459ec5) | Sep 06, 2023 |
| Lenovo        | IdeaPad Z360                | [1bb5ebf339](https://linux-hardware.org/?probe=1bb5ebf339) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [0deab6fc8b](https://linux-hardware.org/?probe=0deab6fc8b) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | [aa37593b87](https://linux-hardware.org/?probe=aa37593b87) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | [230cd8c32e](https://linux-hardware.org/?probe=230cd8c32e) | Sep 06, 2023 |
| Dell          | G3 3500                     | [5da26d2241](https://linux-hardware.org/?probe=5da26d2241) | Sep 06, 2023 |
| Valve         | Jupiter                     | [da71ec43ea](https://linux-hardware.org/?probe=da71ec43ea) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [479d5ea49e](https://linux-hardware.org/?probe=479d5ea49e) | Sep 06, 2023 |
| Acer          | Aspire 5750Z                | [5bec99a137](https://linux-hardware.org/?probe=5bec99a137) | Sep 05, 2023 |
| Dell          | Inspiron 7560               | [dc22012520](https://linux-hardware.org/?probe=dc22012520) | Sep 05, 2023 |
| Dell          | G15 5530                    | [91dcc569ee](https://linux-hardware.org/?probe=91dcc569ee) | Sep 05, 2023 |
| HP            | EliteBook 8470p             | [a658addd87](https://linux-hardware.org/?probe=a658addd87) | Sep 05, 2023 |
| Notebook      | NJx0MU                      | [c02fef3ca2](https://linux-hardware.org/?probe=c02fef3ca2) | Sep 05, 2023 |
| HP            | EliteBook 8470p             | [5cb02e099f](https://linux-hardware.org/?probe=5cb02e099f) | Sep 04, 2023 |
| Dell          | Inspiron 3576               | [5139d104cc](https://linux-hardware.org/?probe=5139d104cc) | Sep 04, 2023 |
| Acer          | Aspire A315-56              | [1f090fc4fd](https://linux-hardware.org/?probe=1f090fc4fd) | Sep 04, 2023 |
| Dell          | Inspiron 7580               | [b021fe57a6](https://linux-hardware.org/?probe=b021fe57a6) | Sep 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | [8253da4d01](https://linux-hardware.org/?probe=8253da4d01) | Sep 04, 2023 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | [d2ac233994](https://linux-hardware.org/?probe=d2ac233994) | Sep 04, 2023 |
| Dell          | Inspiron 3542               | [6046f9d74b](https://linux-hardware.org/?probe=6046f9d74b) | Sep 04, 2023 |
| Compaq        | 430                         | [ac9fb09e14](https://linux-hardware.org/?probe=ac9fb09e14) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [aeebc4664f](https://linux-hardware.org/?probe=aeebc4664f) | Sep 04, 2023 |
| HP            | ENVY 14 SPECTRE             | [1f0a26899c](https://linux-hardware.org/?probe=1f0a26899c) | Sep 04, 2023 |
| HP            | 1000                        | [59cd8d1250](https://linux-hardware.org/?probe=59cd8d1250) | Sep 04, 2023 |
| Notebook      | NJx0MU                      | [1c048ac799](https://linux-hardware.org/?probe=1c048ac799) | Sep 04, 2023 |
| Samsung       | RV415                       | [dc6aa3101f](https://linux-hardware.org/?probe=dc6aa3101f) | Sep 03, 2023 |
| Samsung       | RF511/RF411/RF711           | [522a10f139](https://linux-hardware.org/?probe=522a10f139) | Sep 03, 2023 |
| HP            | Folio 13                    | [d5844cc9e8](https://linux-hardware.org/?probe=d5844cc9e8) | Sep 03, 2023 |
| Acer          | Aspire 5750Z                | [f0b466e572](https://linux-hardware.org/?probe=f0b466e572) | Sep 03, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | [b9de538f7e](https://linux-hardware.org/?probe=b9de538f7e) | Sep 03, 2023 |
| Dell          | Inspiron 5537               | [3aa237c8c6](https://linux-hardware.org/?probe=3aa237c8c6) | Sep 03, 2023 |
| Acer          | Aspire 5750                 | [2b257d37b3](https://linux-hardware.org/?probe=2b257d37b3) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [c93a88de93](https://linux-hardware.org/?probe=c93a88de93) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [76b9023610](https://linux-hardware.org/?probe=76b9023610) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f5f8737b58](https://linux-hardware.org/?probe=f5f8737b58) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Samsung       | 530XBB                      | [30365848c4](https://linux-hardware.org/?probe=30365848c4) | Sep 02, 2023 |
| Dell          | Latitude 7400               | [c98434cc21](https://linux-hardware.org/?probe=c98434cc21) | Sep 02, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [5897684d9e](https://linux-hardware.org/?probe=5897684d9e) | Sep 02, 2023 |
| Samsung       | 500R5L/501R5L/500R5P        | [681c0ca0f9](https://linux-hardware.org/?probe=681c0ca0f9) | Sep 02, 2023 |
| Dell          | Latitude 2120               | [65eed61467](https://linux-hardware.org/?probe=65eed61467) | Sep 02, 2023 |
| Dell          | Latitude 3410               | [695e65a1f0](https://linux-hardware.org/?probe=695e65a1f0) | Sep 02, 2023 |
| Samsung       | 370E4K                      | [19f41e00da](https://linux-hardware.org/?probe=19f41e00da) | Sep 02, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [1c1b1adcc9](https://linux-hardware.org/?probe=1c1b1adcc9) | Sep 02, 2023 |
| Samsung       | 550XBE/350XBE               | [6953a7b5f2](https://linux-hardware.org/?probe=6953a7b5f2) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| Samsung       | 550XED                      | [ba2fe18193](https://linux-hardware.org/?probe=ba2fe18193) | Sep 01, 2023 |
| Dell          | G15 5520                    | [9cfb8ce55a](https://linux-hardware.org/?probe=9cfb8ce55a) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1f29e90c7f](https://linux-hardware.org/?probe=1f29e90c7f) | Sep 01, 2023 |
| Positivo      | Mobile                      | [3b32864073](https://linux-hardware.org/?probe=3b32864073) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| Google        | Barla                       | [1beaca005d](https://linux-hardware.org/?probe=1beaca005d) | Sep 01, 2023 |
| HP            | Presario CQ43               | [9a02828a68](https://linux-hardware.org/?probe=9a02828a68) | Sep 01, 2023 |
| Dell          | Inspiron N4050              | [311af8113f](https://linux-hardware.org/?probe=311af8113f) | Aug 31, 2023 |
| Acer          | Predator PH315-52           | [fd3c900751](https://linux-hardware.org/?probe=fd3c900751) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [064705b919](https://linux-hardware.org/?probe=064705b919) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| Dell          | Inspiron 15-3567            | [9e1df9ff88](https://linux-hardware.org/?probe=9e1df9ff88) | Aug 31, 2023 |
| HP            | Pavilion dv4                | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Dell          | G15 5530                    | [1027c8fe19](https://linux-hardware.org/?probe=1027c8fe19) | Aug 30, 2023 |
| Avell High... | C62 MOB                     | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7075df2d62](https://linux-hardware.org/?probe=7075df2d62) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2a5afc6557](https://linux-hardware.org/?probe=2a5afc6557) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z470                | [d3c372d869](https://linux-hardware.org/?probe=d3c372d869) | Aug 29, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [a5f9c0a211](https://linux-hardware.org/?probe=a5f9c0a211) | Aug 29, 2023 |
| Sony          | VPCEA36FX                   | [174aefbf35](https://linux-hardware.org/?probe=174aefbf35) | Aug 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [fd0950b7c1](https://linux-hardware.org/?probe=fd0950b7c1) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [94f2581f9f](https://linux-hardware.org/?probe=94f2581f9f) | Aug 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [40c64b6ec2](https://linux-hardware.org/?probe=40c64b6ec2) | Aug 28, 2023 |
| Acer          | Aspire 5741Z                | [2127326562](https://linux-hardware.org/?probe=2127326562) | Aug 28, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [379728237a](https://linux-hardware.org/?probe=379728237a) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [30006f030a](https://linux-hardware.org/?probe=30006f030a) | Aug 28, 2023 |
| Acer          | Aspire 4738                 | [6051c9190a](https://linux-hardware.org/?probe=6051c9190a) | Aug 28, 2023 |
| Apple         | MacBookPro16,2              | [65408b783f](https://linux-hardware.org/?probe=65408b783f) | Aug 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [e02ef868a3](https://linux-hardware.org/?probe=e02ef868a3) | Aug 28, 2023 |
| Positivo      | C14CU51                     | [7fa280c987](https://linux-hardware.org/?probe=7fa280c987) | Aug 28, 2023 |
| Dell          | Inspiron 5590               | [5036ce79f9](https://linux-hardware.org/?probe=5036ce79f9) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8b82375189](https://linux-hardware.org/?probe=8b82375189) | Aug 27, 2023 |
| Dell          | Inspiron 5502               | [b2ecdef159](https://linux-hardware.org/?probe=b2ecdef159) | Aug 27, 2023 |
| Dell          | Vostro 3501                 | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| LG Electro... | A530-T.BE76P1               | [6b9ae23c76](https://linux-hardware.org/?probe=6b9ae23c76) | Aug 27, 2023 |
| Samsung       | 300E4M/300E4S/300E4L        | [633ddecba0](https://linux-hardware.org/?probe=633ddecba0) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | [a284c141d8](https://linux-hardware.org/?probe=a284c141d8) | Aug 27, 2023 |
| Timi          | TM1701                      | [2a6a4225a0](https://linux-hardware.org/?probe=2a6a4225a0) | Aug 27, 2023 |
| Timi          | TM1701                      | [8ea7c21e18](https://linux-hardware.org/?probe=8ea7c21e18) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [7566a0ed19](https://linux-hardware.org/?probe=7566a0ed19) | Aug 27, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [35fede08aa](https://linux-hardware.org/?probe=35fede08aa) | Aug 26, 2023 |
| Positivo      | CHT14B                      | [81a8519b9e](https://linux-hardware.org/?probe=81a8519b9e) | Aug 26, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [c0957b3538](https://linux-hardware.org/?probe=c0957b3538) | Aug 26, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [01750cc1d8](https://linux-hardware.org/?probe=01750cc1d8) | Aug 26, 2023 |
| Samsung       | RV419/RV420                 | [77e9d34f16](https://linux-hardware.org/?probe=77e9d34f16) | Aug 26, 2023 |
| Samsung       | 300E5K/300E5Q               | [f0f9f25268](https://linux-hardware.org/?probe=f0f9f25268) | Aug 26, 2023 |
| Samsung       | 300E5K/300E5Q               | [95aa33fc09](https://linux-hardware.org/?probe=95aa33fc09) | Aug 26, 2023 |
| Google        | Kasumi                      | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| Dell          | Latitude E6440              | [759a858fa1](https://linux-hardware.org/?probe=759a858fa1) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [878476c63f](https://linux-hardware.org/?probe=878476c63f) | Aug 25, 2023 |
| Acer          | Nitro AN515-44              | [b14dfb0798](https://linux-hardware.org/?probe=b14dfb0798) | Aug 25, 2023 |
| Samsung       | RV419/RV420                 | [275cd1500e](https://linux-hardware.org/?probe=275cd1500e) | Aug 25, 2023 |
| Dell          | Inspiron 15-3567            | [49769c9b38](https://linux-hardware.org/?probe=49769c9b38) | Aug 25, 2023 |
| Dell          | Inspiron 15-3567            | [e3bc104b50](https://linux-hardware.org/?probe=e3bc104b50) | Aug 25, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [decfff1e51](https://linux-hardware.org/?probe=decfff1e51) | Aug 25, 2023 |
| Acer          | Aspire ES1-512              | [22187e6de0](https://linux-hardware.org/?probe=22187e6de0) | Aug 25, 2023 |
| Dell          | Vostro 5470                 | [2e62ce7973](https://linux-hardware.org/?probe=2e62ce7973) | Aug 25, 2023 |
| Acer          | Aspire A315-23              | [34e1a0c5c4](https://linux-hardware.org/?probe=34e1a0c5c4) | Aug 24, 2023 |
| Samsung       | 300E5M/300E5L               | [4d99c3a598](https://linux-hardware.org/?probe=4d99c3a598) | Aug 24, 2023 |
| Acer          | Aspire 7741                 | [648f667e11](https://linux-hardware.org/?probe=648f667e11) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | [744be89da4](https://linux-hardware.org/?probe=744be89da4) | Aug 24, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 938       | 10.34%  |
| Ubuntu 18.04       | 602       | 6.64%   |
| Ubuntu 22.04       | 426       | 4.7%    |
| Pop!_OS 20.04      | 194       | 2.14%   |
| Pop!_OS 22.04      | 191       | 2.11%   |
| Linux Mint 20      | 190       | 2.09%   |
| Linux Mint 19.3    | 166       | 1.83%   |
| OpenMandriva 4.2   | 162       | 1.79%   |
| OpenMandriva 4.3   | 154       | 1.7%    |
| Linux Mint 20.3    | 153       | 1.69%   |
| Manjaro            | 143       | 1.58%   |
| Zorin 16           | 135       | 1.49%   |
| Arch Rolling       | 125       | 1.38%   |
| Linux Mint 19.1    | 122       | 1.34%   |
| Fedora 38          | 121       | 1.33%   |
| Linux Mint 20.1    | 120       | 1.32%   |
| Debian 11          | 119       | 1.31%   |
| Ubuntu 19.04       | 117       | 1.29%   |
| Arch               | 114       | 1.26%   |
| Linux Mint 20.2    | 113       | 1.25%   |
| KDE neon 20.04     | 113       | 1.25%   |
| Ubuntu 19.10       | 106       | 1.17%   |
| Linux Mint 21.1    | 106       | 1.17%   |
| Zorin 15           | 94        | 1.04%   |
| Debian 10          | 83        | 0.92%   |
| Fedora 35          | 80        | 0.88%   |
| OpenMandriva 23.01 | 74        | 0.82%   |
| Fedora 34          | 73        | 0.8%    |
| Pop!_OS 21.10      | 71        | 0.78%   |
| Fedora 37          | 71        | 0.78%   |
| OpenMandriva 23.08 | 70        | 0.77%   |
| Fedora 32          | 69        | 0.76%   |
| Endless 3.7.8      | 69        | 0.76%   |
| Xubuntu 20.04      | 68        | 0.75%   |
| Linux Mint 21.2    | 68        | 0.75%   |
| Fedora 36          | 68        | 0.75%   |
| Pop!_OS 21.04      | 67        | 0.74%   |
| Endless 3.9.5      | 67        | 0.74%   |
| Linux Mint 21      | 62        | 0.68%   |
| Kubuntu 20.04      | 62        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2424      | 28.12%  |
| Linux Mint    | 1124      | 13.04%  |
| Endless       | 912       | 10.58%  |
| Fedora        | 594       | 6.89%   |
| Pop!_OS       | 564       | 6.54%   |
| OpenMandriva  | 541       | 6.28%   |
| Debian        | 305       | 3.54%   |
| Manjaro       | 252       | 2.92%   |
| Zorin         | 241       | 2.8%    |
| Arch          | 229       | 2.66%   |
| KDE neon      | 156       | 1.81%   |
| Kubuntu       | 135       | 1.57%   |
| Xubuntu       | 133       | 1.54%   |
| openSUSE      | 96        | 1.11%   |
| Lubuntu       | 79        | 0.92%   |
| Elementary    | 74        | 0.86%   |
| Ubuntu MATE   | 65        | 0.75%   |
| ROSA          | 56        | 0.65%   |
| Kali          | 55        | 0.64%   |
| Ubuntu Unity  | 54        | 0.63%   |
| LMDE          | 50        | 0.58%   |
| ArcoLinux     | 44        | 0.51%   |
| BigLinux      | 37        | 0.43%   |
| Deepin        | 31        | 0.36%   |
| Ubuntu Budgie | 29        | 0.34%   |
| Clear Linux   | 28        | 0.32%   |
| SteamOS       | 23        | 0.27%   |
| LinuxFX       | 21        | 0.24%   |
| EndeavourOS   | 19        | 0.22%   |
| Nobara        | 14        | 0.16%   |
| Garuda Linux  | 13        | 0.15%   |
| Parrot        | 12        | 0.14%   |
| MX            | 11        | 0.13%   |
| BlackPanther  | 11        | 0.13%   |
| Reborn OS     | 10        | 0.12%   |
| Peppermint    | 10        | 0.12%   |
| Gentoo        | 10        | 0.12%   |
| Devuan        | 10        | 0.12%   |
| CentOS        | 10        | 0.12%   |
| Artix         | 9         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 471       | 4.83%   |
| 5.8.0-14-generic         | 291       | 2.98%   |
| 5.10.14-desktop-1omv4002 | 156       | 1.6%    |
| 5.16.7-desktop-1omv4003  | 146       | 1.5%    |
| 5.4.0-19-generic         | 114       | 1.17%   |
| 5.3.0-28-generic         | 108       | 1.11%   |
| 5.11.0-35-generic        | 96        | 0.98%   |
| 5.15.0-56-generic        | 78        | 0.8%    |
| 5.4.0-7634-generic       | 74        | 0.76%   |
| 6.1.1-desktop-1omv2290   | 72        | 0.74%   |
| 5.4.0-48-generic         | 72        | 0.74%   |
| 5.4.0-40-generic         | 70        | 0.72%   |
| 4.15.0-46-generic        | 70        | 0.72%   |
| 5.4.0-26-generic         | 64        | 0.66%   |
| 5.4.0-58-generic         | 61        | 0.62%   |
| 5.4.0-52-generic         | 57        | 0.58%   |
| 6.4.11-desktop-1omv2390  | 55        | 0.56%   |
| 5.4.0-47-generic         | 54        | 0.55%   |
| 6.2.6-desktop-1omv2390   | 52        | 0.53%   |
| 5.3.0-19-generic         | 50        | 0.51%   |
| 5.15.0-47-generic        | 50        | 0.51%   |
| 5.3.0-23-generic         | 47        | 0.48%   |
| 5.3.0-46-generic         | 46        | 0.47%   |
| 5.0.0-32-generic         | 46        | 0.47%   |
| 5.4.0-29-generic         | 44        | 0.45%   |
| 4.18.0-15-generic        | 44        | 0.45%   |
| 5.3.0-40-generic         | 43        | 0.44%   |
| 5.15.0-46-generic        | 43        | 0.44%   |
| 5.4.0-65-generic         | 42        | 0.43%   |
| 5.15.0-52-generic        | 42        | 0.43%   |
| 5.4.0-39-generic         | 41        | 0.42%   |
| 5.0.0-37-generic         | 41        | 0.42%   |
| 5.4.0-80-generic         | 40        | 0.41%   |
| 6.2.6-76060206-generic   | 39        | 0.4%    |
| 5.4.0-70-generic         | 39        | 0.4%    |
| 5.0.0-25-generic         | 39        | 0.4%    |
| 5.15.0-58-generic        | 38        | 0.39%   |
| 5.13.0-30-generic        | 38        | 0.39%   |
| 5.11.0-7620-generic      | 38        | 0.39%   |
| 4.18.0-16-generic        | 38        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 1864      | 20.08%  |
| 5.15.0  | 686       | 7.39%   |
| 5.8.0   | 625       | 6.73%   |
| 5.3.0   | 535       | 5.76%   |
| 4.15.0  | 519       | 5.59%   |
| 5.11.0  | 456       | 4.91%   |
| 5.0.0   | 320       | 3.45%   |
| 5.13.0  | 281       | 3.03%   |
| 4.18.0  | 232       | 2.5%    |
| 5.19.0  | 212       | 2.28%   |
| 6.2.0   | 180       | 1.94%   |
| 5.10.0  | 168       | 1.81%   |
| 5.10.14 | 158       | 1.7%    |
| 5.16.7  | 146       | 1.57%   |
| 4.19.0  | 101       | 1.09%   |
| 6.2.6   | 93        | 1%      |
| 6.1.0   | 87        | 0.94%   |
| 6.1.1   | 79        | 0.85%   |
| 6.4.11  | 64        | 0.69%   |
| 6.5.0   | 61        | 0.66%   |
| 5.17.5  | 35        | 0.38%   |
| 6.0.12  | 32        | 0.34%   |
| 5.16.11 | 30        | 0.32%   |
| 5.14.0  | 30        | 0.32%   |
| 4.4.0   | 28        | 0.3%    |
| 5.7.9   | 26        | 0.28%   |
| 6.4.6   | 25        | 0.27%   |
| 6.6.2   | 24        | 0.26%   |
| 4.9.0   | 23        | 0.25%   |
| 6.5.6   | 21        | 0.23%   |
| 6.4.8   | 21        | 0.23%   |
| 5.15.15 | 20        | 0.22%   |
| 6.5.5   | 19        | 0.2%    |
| 5.15.5  | 19        | 0.2%    |
| 5.14.21 | 19        | 0.2%    |
| 6.2.15  | 18        | 0.19%   |
| 6.0.0   | 17        | 0.18%   |
| 5.9.16  | 17        | 0.18%   |
| 5.7.0   | 17        | 0.18%   |
| 5.6.19  | 16        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 1937      | 21.12%  |
| 5.15    | 859       | 9.37%   |
| 5.8     | 694       | 7.57%   |
| 5.3     | 579       | 6.31%   |
| 5.11    | 523       | 5.7%    |
| 4.15    | 519       | 5.66%   |
| 5.10    | 432       | 4.71%   |
| 6.2     | 375       | 4.09%   |
| 5.0     | 345       | 3.76%   |
| 5.13    | 336       | 3.66%   |
| 6.1     | 284       | 3.1%    |
| 5.16    | 275       | 3%      |
| 5.19    | 259       | 2.82%   |
| 4.18    | 248       | 2.7%    |
| 6.4     | 177       | 1.93%   |
| 6.5     | 166       | 1.81%   |
| 4.19    | 118       | 1.29%   |
| 6.0     | 113       | 1.23%   |
| 5.7     | 101       | 1.1%    |
| 6.6     | 99        | 1.08%   |
| 5.17    | 98        | 1.07%   |
| 5.14    | 98        | 1.07%   |
| 5.18    | 78        | 0.85%   |
| 5.6     | 70        | 0.76%   |
| 5.9     | 66        | 0.72%   |
| 6.3     | 64        | 0.7%    |
| 5.12    | 62        | 0.68%   |
| 4.9     | 47        | 0.51%   |
| 5.5     | 32        | 0.35%   |
| 4.4     | 31        | 0.34%   |
| 5.1     | 28        | 0.31%   |
| 5.2     | 15        | 0.16%   |
| 6.7     | 9         | 0.1%    |
| 4.13    | 7         | 0.08%   |
| 4.20    | 5         | 0.05%   |
| 4.14    | 4         | 0.04%   |
| 4.10    | 4         | 0.04%   |
| 4.1     | 4         | 0.04%   |
| 3.10    | 3         | 0.03%   |
| 4.17    | 2         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 8036      | 97.81%  |
| i686   | 178       | 2.17%   |
| armv7l | 2         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 4263      | 49.67%  |
| KDE5            | 1085      | 12.64%  |
| Unknown         | 1000      | 11.65%  |
| X-Cinnamon      | 706       | 8.23%   |
| XFCE            | 562       | 6.55%   |
| MATE            | 210       | 2.45%   |
| KDE             | 162       | 1.89%   |
| Cinnamon        | 139       | 1.62%   |
| LXQt            | 92        | 1.07%   |
| Pantheon        | 68        | 0.79%   |
| Unity           | 56        | 0.65%   |
| Deepin          | 44        | 0.51%   |
| Budgie          | 42        | 0.49%   |
| LXDE            | 35        | 0.41%   |
| i3              | 27        | 0.31%   |
| KDE4            | 25        | 0.29%   |
| Endless:GNOME   | 15        | 0.17%   |
| GNOME Classic   | 11        | 0.13%   |
| sway            | 7         | 0.08%   |
| Hyprland        | 6         | 0.07%   |
| awesome         | 6         | 0.07%   |
| openbox         | 3         | 0.03%   |
| GNOME Flashback | 3         | 0.03%   |
| Enlightenment   | 3         | 0.03%   |
| xmonad          | 1         | 0.01%   |
| Trinity         | 1         | 0.01%   |
| Lubuntu         | 1         | 0.01%   |
| jwm             | 1         | 0.01%   |
| icewm           | 1         | 0.01%   |
| i3-with-shmlog  | 1         | 0.01%   |
| Hypr            | 1         | 0.01%   |
| GNUstep         | 1         | 0.01%   |
| GNOME-Classic   | 1         | 0.01%   |
| fluxbox         | 1         | 0.01%   |
| chadwm          | 1         | 0.01%   |
| bspwm           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 6623      | 78.18%  |
| Wayland | 1297      | 15.31%  |
| Unknown | 517       | 6.1%    |
| Tty     | 35        | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 5237      | 61.24%  |
| SDDM    | 925       | 10.82%  |
| GDM     | 826       | 9.66%   |
| GDM3    | 720       | 8.42%   |
| LightDM | 510       | 5.96%   |
| TDM     | 292       | 3.41%   |
| KDM     | 26        | 0.3%    |
| XDM     | 7         | 0.08%   |
| SLiM    | 4         | 0.05%   |
| Ly      | 2         | 0.02%   |
| MDM     | 1         | 0.01%   |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| pt_BR      | 5633      | 67.05%  |
| en_US      | 1590      | 18.93%  |
| Unknown    | 921       | 10.96%  |
| C          | 123       | 1.46%   |
| en_GB      | 44        | 0.52%   |
| pt_PT      | 33        | 0.39%   |
| es_ES      | 15        | 0.18%   |
| en_CA      | 6         | 0.07%   |
| fr_FR      | 5         | 0.06%   |
| de_DE      | 5         | 0.06%   |
| POSIX      | 3         | 0.04%   |
| ja_JP      | 2         | 0.02%   |
| it_IT      | 2         | 0.02%   |
| es_CL      | 2         | 0.02%   |
| en_DK      | 2         | 0.02%   |
| UTF-8      | 1         | 0.01%   |
| ru_RU      | 1         | 0.01%   |
| pt_BR~     | 1         | 0.01%   |
| pt_BRutf8  | 1         | 0.01%   |
| es_VE      | 1         | 0.01%   |
| es_PY      | 1         | 0.01%   |
| es_MX      | 1         | 0.01%   |
| es_AR      | 1         | 0.01%   |
| en_ZA      | 1         | 0.01%   |
| en_IE.UTF8 | 1         | 0.01%   |
| en-US      | 1         | 0.01%   |
| em_US      | 1         | 0.01%   |
| de_CH      | 1         | 0.01%   |
| C.UTF8     | 1         | 0.01%   |
| ar_EG      | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 4246      | 50.4%   |
| BIOS | 4178      | 49.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 6414      | 75.86%  |
| Btrfs   | 768       | 9.08%   |
| Overlay | 576       | 6.81%   |
| Unknown | 389       | 4.6%    |
| Tmpfs   | 181       | 2.14%   |
| Xfs     | 62        | 0.73%   |
| Zfs     | 30        | 0.35%   |
| Ext2    | 13        | 0.15%   |
| F2fs    | 10        | 0.12%   |
| Ext3    | 10        | 0.12%   |
| Aufs    | 2         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 5437      | 64.31%  |
| GPT     | 2245      | 26.56%  |
| MBR     | 772       | 9.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7538      | 90.67%  |
| Yes       | 776       | 9.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6526      | 78.24%  |
| Yes       | 1815      | 21.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell                   | 1897      | 23.09%  |
| Acer                   | 1561      | 19%     |
| Lenovo                 | 1062      | 12.93%  |
| Samsung Electronics    | 687       | 8.36%   |
| Hewlett-Packard        | 554       | 6.74%   |
| Positivo               | 526       | 6.4%    |
| ASUSTek Computer       | 483       | 5.88%   |
| Sony                   | 168       | 2.05%   |
| Apple                  | 113       | 1.38%   |
| LG Electronics         | 101       | 1.23%   |
| Avell High Performance | 92        | 1.12%   |
| Digibras               | 77        | 0.94%   |
| Itautec                | 73        | 0.89%   |
| Semp Toshiba           | 69        | 0.84%   |
| Unknown                | 69        | 0.84%   |
| Intel                  | 54        | 0.66%   |
| Compaq                 | 52        | 0.63%   |
| Multilaser             | 50        | 0.61%   |
| Positivo Bahia - VAIO  | 45        | 0.55%   |
| Philco                 | 44        | 0.54%   |
| Toshiba                | 36        | 0.44%   |
| OEM                    | 32        | 0.39%   |
| Notebook               | 28        | 0.34%   |
| Clevo                  | 26        | 0.32%   |
| Gateway                | 23        | 0.28%   |
| Google                 | 22        | 0.27%   |
| Compal                 | 21        | 0.26%   |
| Alienware              | 21        | 0.26%   |
| MSI                    | 19        | 0.23%   |
| Valve                  | 18        | 0.22%   |
| Daten Tecnologia       | 16        | 0.19%   |
| eMachines              | 13        | 0.16%   |
| Standard               | 12        | 0.15%   |
| Quanta                 | 12        | 0.15%   |
| Timi                   | 11        | 0.13%   |
| Chuwi                  | 9         | 0.11%   |
| Login Informatica      | 7         | 0.09%   |
| Gigabyte Technology    | 7         | 0.09%   |
| CCE                    | 7         | 0.09%   |
| LNV                    | 5         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Nitro AN515-54                         | 139       | 1.69%   |
| Positivo Mobile                             | 130       | 1.58%   |
| Unknown                                     | 117       | 1.42%   |
| Acer Nitro AN515-44                         | 91        | 1.11%   |
| Samsung 340XAA/350XAA/550XAA                | 73        | 0.89%   |
| Lenovo IdeaPad S145-15API 81V7              | 70        | 0.85%   |
| Dell Inspiron 5566                          | 70        | 0.85%   |
| Acer Aspire A315-53                         | 70        | 0.85%   |
| Dell Inspiron 15-3567                       | 66        | 0.8%    |
| Dell Inspiron 3583                          | 64        | 0.78%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 62        | 0.75%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 59        | 0.72%   |
| Acer Aspire A515-51                         | 54        | 0.66%   |
| Acer Aspire A315-34                         | 54        | 0.66%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 53        | 0.65%   |
| Acer Nitro AN517-51                         | 53        | 0.65%   |
| Samsung 300E5M/300E5L                       | 51        | 0.62%   |
| Samsung 550XDA                              | 49        | 0.6%    |
| Lenovo IdeaPad 3 15ALC6 82MF                | 48        | 0.58%   |
| Dell Inspiron 3442                          | 47        | 0.57%   |
| Acer Nitro AN515-43                         | 46        | 0.56%   |
| Positivo S14CT01                            | 45        | 0.55%   |
| HP G42                                      | 43        | 0.52%   |
| Dell Inspiron N4050                         | 41        | 0.5%    |
| Dell Inspiron 3421                          | 40        | 0.49%   |
| Acer Nitro AN515-52                         | 40        | 0.49%   |
| HP Pavilion g4                              | 37        | 0.45%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 36        | 0.44%   |
| Digibras NH4CU03                            | 36        | 0.44%   |
| Dell Inspiron 7520                          | 36        | 0.44%   |
| Acer Aspire E5-571                          | 36        | 0.44%   |
| Acer Aspire E1-571                          | 35        | 0.43%   |
| Dell Inspiron 5458                          | 34        | 0.41%   |
| Acer Aspire A515-51G                        | 34        | 0.41%   |
| Dell Inspiron 1525                          | 33        | 0.4%    |
| ASUS VivoBook_ASUSLaptop X515DA_X515DA      | 33        | 0.4%    |
| Samsung 550XBE/350XBE                       | 32        | 0.39%   |
| Dell Inspiron 1545                          | 32        | 0.39%   |
| Dell G3 3590                                | 32        | 0.39%   |
| Itautec Infoway                             | 31        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 1203      | 14.64%  |
| Acer Aspire       | 1013      | 12.33%  |
| Lenovo IdeaPad    | 595       | 7.24%   |
| Acer Nitro        | 440       | 5.36%   |
| Dell Vostro       | 255       | 3.1%    |
| Lenovo ThinkPad   | 238       | 2.9%    |
| Dell Latitude     | 224       | 2.73%   |
| HP Pavilion       | 217       | 2.64%   |
| ASUS VivoBook     | 170       | 2.07%   |
| Positivo Mobile   | 130       | 1.58%   |
| Unknown           | 117       | 1.42%   |
| Samsung 340XAA    | 73        | 0.89%   |
| Itautec Infoway   | 73        | 0.89%   |
| Dell G3           | 64        | 0.78%   |
| HP ProBook        | 52        | 0.63%   |
| Samsung 300E5M    | 51        | 0.62%   |
| Samsung RV411     | 49        | 0.6%    |
| Samsung 550XDA    | 49        | 0.6%    |
| Positivo S14CT01  | 45        | 0.55%   |
| HP G42            | 43        | 0.52%   |
| HP EliteBook      | 42        | 0.51%   |
| Acer Predator     | 42        | 0.51%   |
| Dell System       | 41        | 0.5%    |
| Dell G15          | 37        | 0.45%   |
| Semp Toshiba IS   | 36        | 0.44%   |
| Digibras NH4CU03  | 36        | 0.44%   |
| HP Compaq         | 33        | 0.4%    |
| Samsung 550XBE    | 32        | 0.39%   |
| Digibras NH4CU53  | 31        | 0.38%   |
| Compaq Presario   | 31        | 0.38%   |
| Dell XPS          | 30        | 0.37%   |
| Toshiba Satellite | 29        | 0.35%   |
| Samsung 370E4K    | 28        | 0.34%   |
| Samsung 270E5J    | 28        | 0.34%   |
| Samsung RV415     | 27        | 0.33%   |
| Apple MacBookPro8 | 26        | 0.32%   |
| Samsung 550XCJ    | 25        | 0.3%    |
| Positivo H14BT58  | 25        | 0.3%    |
| Positivo CHT14B   | 25        | 0.3%    |
| Lenovo G400s      | 25        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 967       | 11.77%  |
| 2012    | 868       | 10.57%  |
| 2011    | 736       | 8.96%   |
| 2018    | 639       | 7.78%   |
| 2013    | 627       | 7.63%   |
| 2017    | 613       | 7.46%   |
| 2016    | 591       | 7.19%   |
| 2021    | 518       | 6.31%   |
| 2020    | 508       | 6.18%   |
| 2010    | 481       | 5.86%   |
| 2014    | 437       | 5.32%   |
| 2015    | 356       | 4.33%   |
| 2008    | 290       | 3.53%   |
| 2009    | 246       | 2.99%   |
| 2022    | 113       | 1.38%   |
| 2007    | 106       | 1.29%   |
| 2023    | 39        | 0.47%   |
| 2006    | 38        | 0.46%   |
| Unknown | 29        | 0.35%   |
| 2005    | 9         | 0.11%   |
| 2004    | 4         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 8215      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 7084      | 85.36%  |
| Enabled  | 1215      | 14.64%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 8189      | 99.68%  |
| Yes  | 26        | 0.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2731      | 32.66%  |
| 3.01-4.0    | 2243      | 26.82%  |
| 16.01-24.0  | 1153      | 13.79%  |
| 8.01-16.0   | 1153      | 13.79%  |
| 1.01-2.0    | 578       | 6.91%   |
| 32.01-64.0  | 195       | 2.33%   |
| 2.01-3.0    | 195       | 2.33%   |
| 24.01-32.0  | 49        | 0.59%   |
| 0.51-1.0    | 34        | 0.41%   |
| 64.01-256.0 | 31        | 0.37%   |
| 0.01-0.5    | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 3218      | 35.4%   |
| 2.01-3.0   | 2549      | 28.04%  |
| 3.01-4.0   | 1256      | 13.82%  |
| 4.01-8.0   | 1194      | 13.13%  |
| 0.51-1.0   | 572       | 6.29%   |
| 8.01-16.0  | 233       | 2.56%   |
| 0.01-0.5   | 43        | 0.47%   |
| 16.01-24.0 | 18        | 0.2%    |
| 32.01-64.0 | 3         | 0.03%   |
| 24.01-32.0 | 3         | 0.03%   |
| Unknown    | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5825      | 69.55%  |
| 2      | 2292      | 27.37%  |
| 3      | 178       | 2.13%   |
| 0      | 59        | 0.7%    |
| 4      | 20        | 0.24%   |
| 6      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5231      | 63.38%  |
| Yes       | 3023      | 36.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7190      | 87.32%  |
| No        | 1044      | 12.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7961      | 96.63%  |
| No        | 278       | 3.37%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5978      | 71.96%  |
| No        | 2329      | 28.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 8215      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 995       | 11.53%  |
| Rio de Janeiro        | 448       | 5.19%   |
| Brasília             | 281       | 3.25%   |
| Curitiba              | 252       | 2.92%   |
| Belo Horizonte        | 234       | 2.71%   |
| Fortaleza             | 201       | 2.33%   |
| Porto Alegre          | 179       | 2.07%   |
| Salvador              | 137       | 1.59%   |
| Campinas              | 129       | 1.49%   |
| Recife                | 115       | 1.33%   |
| Goiânia              | 99        | 1.15%   |
| Florianópolis        | 91        | 1.05%   |
| Santo André          | 89        | 1.03%   |
| Natal                 | 87        | 1.01%   |
| Manaus                | 78        | 0.9%    |
| Osasco                | 74        | 0.86%   |
| Campo Grande          | 73        | 0.85%   |
| Sao José dos Campos  | 70        | 0.81%   |
| Sao Luís             | 69        | 0.8%    |
| Joao Pessoa           | 63        | 0.73%   |
| Belém                | 61        | 0.71%   |
| Maringá              | 60        | 0.7%    |
| Niterói              | 59        | 0.68%   |
| Teresina              | 56        | 0.65%   |
| Guarulhos             | 54        | 0.63%   |
| Sorocaba              | 53        | 0.61%   |
| Aracaju               | 53        | 0.61%   |
| Uberlândia           | 52        | 0.6%    |
| Joinville             | 52        | 0.6%    |
| Ribeirao Preto        | 48        | 0.56%   |
| Londrina              | 47        | 0.54%   |
| Maceió               | 45        | 0.52%   |
| Cuiabá               | 40        | 0.46%   |
| Sao Bernardo do Campo | 38        | 0.44%   |
| Juiz de Fora          | 38        | 0.44%   |
| Sao Jose              | 37        | 0.43%   |
| Sao Carlos            | 37        | 0.43%   |
| Vitória              | 35        | 0.41%   |
| Canoas                | 34        | 0.39%   |
| Americana             | 32        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 2157      | 2649   | 20.93%  |
| Seagate                        | 1467      | 1758   | 14.23%  |
| Kingston                       | 995       | 1201   | 9.65%   |
| Samsung Electronics            | 734       | 957    | 7.12%   |
| Toshiba                        | 680       | 795    | 6.6%    |
| SanDisk                        | 595       | 785    | 5.77%   |
| Unknown                        | 458       | 610    | 4.44%   |
| A-DATA Technology              | 443       | 567    | 4.3%    |
| Intel                          | 286       | 355    | 2.77%   |
| ADATA Technology               | 230       | 264    | 2.23%   |
| China                          | 226       | 287    | 2.19%   |
| Hitachi                        | 211       | 255    | 2.05%   |
| Crucial                        | 195       | 264    | 1.89%   |
| SK hynix                       | 152       | 194    | 1.47%   |
| LITEON                         | 118       | 141    | 1.14%   |
| HGST                           | 114       | 135    | 1.11%   |
| Silicon Motion                 | 92        | 109    | 0.89%   |
| KingSpec                       | 77        | 86     | 0.75%   |
| SSSTC                          | 59        | 64     | 0.57%   |
| JMicron Technology             | 54        | 60     | 0.52%   |
| Fujitsu                        | 48        | 58     | 0.47%   |
| Solid State Storage            | 46        | 58     | 0.45%   |
| Apple                          | 46        | 56     | 0.45%   |
| Solid State Storage Technology | 45        | 60     | 0.44%   |
| Lexar                          | 43        | 53     | 0.42%   |
| Netac                          | 42        | 51     | 0.41%   |
| Micron Technology              | 41        | 43     | 0.4%    |
| KIOXIA                         | 41        | 50     | 0.4%    |
| Phison                         | 36        | 39     | 0.35%   |
| Realtek Semiconductor          | 33        | 48     | 0.32%   |
| Corsair                        | 29        | 29     | 0.28%   |
| Unknown                        | 29        | 33     | 0.28%   |
| Kingston Technology Company    | 28        | 30     | 0.27%   |
| XrayDisk                       | 25        | 31     | 0.24%   |
| PNY                            | 23        | 37     | 0.22%   |
| Patriot                        | 22        | 25     | 0.21%   |
| Hewlett-Packard                | 20        | 23     | 0.19%   |
| Smart                          | 19        | 21     | 0.18%   |
| Gigabyte Technology            | 18        | 25     | 0.17%   |
| XPG                            | 17        | 21     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 495       | 4.67%   |
| Kingston SA400S37240G 240GB SSD     | 339       | 3.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 275       | 2.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 246       | 2.32%   |
| Kingston SA400S37480G 480GB SSD     | 197       | 1.86%   |
| Kingston SA400S37120G 120GB SSD     | 147       | 1.39%   |
| Toshiba MQ01ABD100 1TB              | 144       | 1.36%   |
| WDC WD10SPZX-24Z10 1TB              | 141       | 1.33%   |
| Unknown MMC Card  32GB              | 134       | 1.26%   |
| Seagate ST1000LM035-1RK172 1TB      | 114       | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB            | 106       | 1%      |
| Intel NVMe SSD Drive 512GB          | 98        | 0.92%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 93        | 0.88%   |
| Toshiba MQ04ABF100 1TB              | 92        | 0.87%   |
| WDC WD10SPZX-75Z10T2 1TB            | 90        | 0.85%   |
| Samsung HM321HI 320GB               | 83        | 0.78%   |
| Seagate ST9500325AS 500GB           | 81        | 0.76%   |
| SanDisk SSD PLUS 240GB              | 74        | 0.7%    |
| SanDisk NVMe SSD Drive 512GB        | 74        | 0.7%    |
| Kingston SV300S37A120G 120GB SSD    | 70        | 0.66%   |
| Intel SSDPEKKW256G7 256GB           | 70        | 0.66%   |
| ADATA NVMe SSD Drive 256GB          | 68        | 0.64%   |
| WDC WD10JPVX-75JC3T0 1TB            | 67        | 0.63%   |
| Seagate Expansion 1TB               | 65        | 0.61%   |
| Toshiba MQ01ABF050 500GB            | 62        | 0.58%   |
| SanDisk SSD PLUS 120GB              | 61        | 0.58%   |
| A-DATA IM2P33F3A NVMe 256GB         | 61        | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 58        | 0.55%   |
| Seagate ST2000LM007-1R8174 2TB      | 58        | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 56        | 0.53%   |
| Seagate ST500LT012-9WS142 500GB     | 56        | 0.53%   |
| ADATA SM2P32A8-256GC1 256GB         | 55        | 0.52%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 54        | 0.51%   |
| Crucial CT240BX500SSD1 240GB        | 54        | 0.51%   |
| WDC WD10JPCX-24UE4T0 1TB            | 50        | 0.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 49        | 0.46%   |
| WDC WD10SPZX-75Z10T1 1TB            | 48        | 0.45%   |
| Toshiba MQ01ABD050 500GB            | 47        | 0.44%   |
| SanDisk SSD PLUS 480GB              | 43        | 0.41%   |
| SanDisk SDSSDA240G 240GB            | 42        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1912      | 2261   | 39.92%  |
| Seagate             | 1456      | 1743   | 30.4%   |
| Toshiba             | 641       | 747    | 13.38%  |
| Samsung Electronics | 306       | 357    | 6.39%   |
| Hitachi             | 211       | 255    | 4.41%   |
| HGST                | 114       | 135    | 2.38%   |
| Fujitsu             | 46        | 55     | 0.96%   |
| JMicron Technology  | 42        | 48     | 0.88%   |
| Unknown             | 26        | 32     | 0.54%   |
| Apple               | 13        | 16     | 0.27%   |
| SAGE                | 7         | 11     | 0.15%   |
| XrayDisk            | 3         | 4      | 0.06%   |
| TO Exter            | 3         | 4      | 0.06%   |
| External            | 2         | 2      | 0.04%   |
| WALRAM              | 1         | 1      | 0.02%   |
| Phison              | 1         | 1      | 0.02%   |
| Maxtor 6            | 1         | 1      | 0.02%   |
| Maxtor              | 1         | 1      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| IBM/Hitachi         | 1         | 2      | 0.02%   |
| CLOVER              | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 942       | 1129   | 30.32%  |
| SanDisk             | 367       | 505    | 11.81%  |
| Samsung Electronics | 249       | 345    | 8.01%   |
| WDC                 | 233       | 292    | 7.5%    |
| China               | 226       | 287    | 7.27%   |
| A-DATA Technology   | 215       | 259    | 6.92%   |
| Crucial             | 184       | 249    | 5.92%   |
| LITEON              | 109       | 132    | 3.51%   |
| KingSpec            | 73        | 82     | 2.35%   |
| Lexar               | 39        | 49     | 1.26%   |
| Netac               | 34        | 39     | 1.09%   |
| Apple               | 30        | 36     | 0.97%   |
| Intel               | 26        | 31     | 0.84%   |
| PNY                 | 23        | 37     | 0.74%   |
| Corsair             | 22        | 22     | 0.71%   |
| Patriot             | 21        | 24     | 0.68%   |
| Smart               | 19        | 21     | 0.61%   |
| XrayDisk            | 18        | 20     | 0.58%   |
| SK hynix            | 18        | 21     | 0.58%   |
| Hewlett-Packard     | 16        | 18     | 0.51%   |
| Gigabyte Technology | 16        | 22     | 0.51%   |
| Unknown             | 13        | 14     | 0.42%   |
| LITEONIT            | 13        | 20     | 0.42%   |
| KingDian            | 13        | 19     | 0.42%   |
| Unknown             | 13        | 14     | 0.42%   |
| Toshiba             | 10        | 14     | 0.32%   |
| Seagate             | 9         | 10     | 0.29%   |
| Micron Technology   | 9         | 10     | 0.29%   |
| Win Memory          | 8         | 9      | 0.26%   |
| walram              | 8         | 8      | 0.26%   |
| HUSKY               | 7         | 8      | 0.23%   |
| BIWIN               | 7         | 8      | 0.23%   |
| BHT                 | 7         | 7      | 0.23%   |
| S3+                 | 5         | 5      | 0.16%   |
| Advantech           | 5         | 6      | 0.16%   |
| Transcend           | 4         | 4      | 0.13%   |
| Maxtor              | 4         | 4      | 0.13%   |
| Lenovo              | 4         | 5      | 0.13%   |
| Vaseky              | 3         | 4      | 0.1%    |
| USB3.0              | 3         | 3      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4679      | 5678   | 47.17%  |
| SSD     | 2902      | 3880   | 29.25%  |
| NVMe    | 1861      | 2489   | 18.76%  |
| MMC     | 378       | 526    | 3.81%   |
| Unknown | 100       | 124    | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6693      | 9372   | 73%     |
| NVMe | 1861      | 2489   | 20.3%   |
| MMC  | 378       | 526    | 4.12%   |
| SAS  | 237       | 310    | 2.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4762      | 6334   | 64.52%  |
| 0.51-1.0   | 2471      | 3037   | 33.48%  |
| 1.01-2.0   | 135       | 173    | 1.83%   |
| 3.01-4.0   | 6         | 6      | 0.08%   |
| 4.01-10.0  | 5         | 6      | 0.07%   |
| 2.01-3.0   | 1         | 1      | 0.01%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2572      | 29.65%  |
| 251-500        | 2189      | 25.24%  |
| 501-1000       | 1521      | 17.54%  |
| 1-20           | 643       | 7.41%   |
| 51-100         | 516       | 5.95%   |
| 1001-2000      | 506       | 5.83%   |
| 21-50          | 412       | 4.75%   |
| Unknown        | 132       | 1.52%   |
| 2001-3000      | 98        | 1.13%   |
| More than 3000 | 85        | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 3383      | 37.61%  |
| 21-50          | 2098      | 23.32%  |
| 51-100         | 1188      | 13.21%  |
| 101-250        | 1180      | 13.12%  |
| 251-500        | 591       | 6.57%   |
| 501-1000       | 289       | 3.21%   |
| Unknown        | 132       | 1.47%   |
| 1001-2000      | 107       | 1.19%   |
| 2001-3000      | 14        | 0.16%   |
| More than 3000 | 12        | 0.13%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 39        | 43     | 6.98%   |
| Seagate ST9500325AS 500GB           | 21        | 23     | 3.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 21        | 23     | 3.76%   |
| Seagate ST1000LM035-1RK172 1TB      | 15        | 15     | 2.68%   |
| Toshiba MQ01ABD100 1TB              | 12        | 12     | 2.15%   |
| Seagate ST500LT012-9WS142 500GB     | 10        | 12     | 1.79%   |
| Seagate ST9320325AS 320GB           | 8         | 8      | 1.43%   |
| Samsung Electronics HM160HI 160GB   | 8         | 8      | 1.43%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 1.25%   |
| Toshiba MQ01ABD050 500GB            | 7         | 7      | 1.25%   |
| Kingston SV300S37A120G 120GB SSD    | 7         | 8      | 1.25%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 6         | 7      | 1.07%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 6         | 6      | 1.07%   |
| Toshiba MQ02ABD100H 1TB             | 6         | 9      | 1.07%   |
| Seagate ST1000LM048-2E7172 1TB      | 6         | 7      | 1.07%   |
| SanDisk SSD PLUS 480GB              | 6         | 6      | 1.07%   |
| Kingston SA400S37240G 240GB SSD     | 6         | 6      | 1.07%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 5         | 6      | 0.89%   |
| WDC WD10SPZX-24Z10T0 1TB            | 5         | 6      | 0.89%   |
| WDC WD10JPCX-24UE4T0 1TB            | 5         | 5      | 0.89%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 6      | 0.89%   |
| Seagate ST320LT007-9ZV142 320GB     | 5         | 5      | 0.89%   |
| Seagate ST1000LM014-1EJ164 1TB      | 5         | 5      | 0.89%   |
| Samsung Electronics HM321HI 320GB   | 5         | 5      | 0.89%   |
| Hitachi HTS547550A9E384 500GB       | 5         | 5      | 0.89%   |
| HGST HTS545050A7E680 500GB          | 5         | 5      | 0.89%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 4         | 4      | 0.72%   |
| WDC WD10SPZX-75Z10T2 1TB            | 4         | 4      | 0.72%   |
| Toshiba MK5065GSXF 500GB            | 4         | 5      | 0.72%   |
| Toshiba MK3259GSXP 320GB            | 4         | 4      | 0.72%   |
| Seagate ST9500423AS 500GB           | 4         | 4      | 0.72%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 4      | 0.72%   |
| Seagate ST2000LM007-1R8174 2TB      | 4         | 4      | 0.72%   |
| Samsung Electronics HM500JI 500GB   | 4         | 4      | 0.72%   |
| Kingston SUV400S37240G 240GB SSD    | 4         | 5      | 0.72%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 4      | 0.72%   |
| HGST HCC545050A7E380 500GB          | 4         | 5      | 0.72%   |
| China SSD 120GB                     | 4         | 4      | 0.72%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3         | 3      | 0.54%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 3         | 3      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 184       | 203    | 33.15%  |
| WDC                   | 107       | 117    | 19.28%  |
| Toshiba               | 77        | 86     | 13.87%  |
| Hitachi               | 34        | 37     | 6.13%   |
| Samsung Electronics   | 32        | 43     | 5.77%   |
| Kingston              | 25        | 29     | 4.5%    |
| SanDisk               | 16        | 16     | 2.88%   |
| China                 | 15        | 17     | 2.7%    |
| HGST                  | 12        | 13     | 2.16%   |
| A-DATA Technology     | 11        | 13     | 1.98%   |
| LITEON                | 4         | 5      | 0.72%   |
| Intel                 | 4         | 4      | 0.72%   |
| Fujitsu               | 4         | 5      | 0.72%   |
| PNY                   | 3         | 5      | 0.54%   |
| KingSpec              | 3         | 3      | 0.54%   |
| Crucial               | 3         | 3      | 0.54%   |
| walram                | 2         | 2      | 0.36%   |
| Netac                 | 2         | 2      | 0.36%   |
| Micron Technology     | 2         | 2      | 0.36%   |
| Apple                 | 2         | 2      | 0.36%   |
| XrayDisk              | 1         | 1      | 0.18%   |
| XPG                   | 1         | 1      | 0.18%   |
| SSSTC                 | 1         | 1      | 0.18%   |
| SK hynix              | 1         | 1      | 0.18%   |
| Silicon Motion        | 1         | 1      | 0.18%   |
| ShiJi                 | 1         | 4      | 0.18%   |
| SAGE                  | 1         | 1      | 0.18%   |
| Realtek Semiconductor | 1         | 1      | 0.18%   |
| OCZ                   | 1         | 1      | 0.18%   |
| LITEONIT              | 1         | 2      | 0.18%   |
| Kross Elegance        | 1         | 1      | 0.18%   |
| JMicron Technology    | 1         | 1      | 0.18%   |
| ADATA Technology      | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 184       | 203    | 42.01%  |
| WDC                 | 97        | 107    | 22.15%  |
| Toshiba             | 76        | 85     | 17.35%  |
| Hitachi             | 34        | 37     | 7.76%   |
| Samsung Electronics | 28        | 39     | 6.39%   |
| HGST                | 12        | 13     | 2.74%   |
| Fujitsu             | 4         | 5      | 0.91%   |
| SAGE                | 1         | 1      | 0.23%   |
| JMicron Technology  | 1         | 1      | 0.23%   |
| Apple               | 1         | 1      | 0.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 437       | 492    | 78.88%  |
| SSD  | 100       | 110    | 18.05%  |
| NVMe | 17        | 22     | 3.07%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 13.33%  |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 6.67%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD050 500GB                         | 1         | 1      | 6.67%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 6.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 6.67%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD  | 1         | 1      | 6.67%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 6.67%   |
| Samsung Electronics HM250HI 250GB                | 1         | 1      | 6.67%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 6.67%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 40%     |
| Toshiba             | 3         | 3      | 20%     |
| WDC                 | 2         | 2      | 13.33%  |
| Seagate             | 2         | 2      | 13.33%  |
| Maxtor              | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5909      | 8976   | 68.37%  |
| Works    | 2174      | 3081   | 25.15%  |
| Malfunc  | 544       | 624    | 6.29%   |
| Failed   | 15        | 15     | 0.17%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6742      | 71.66%  |
| AMD                              | 780       | 8.29%   |
| ADATA Technology                 | 469       | 4.99%   |
| SanDisk                          | 273       | 2.9%    |
| Samsung Electronics              | 206       | 2.19%   |
| Solid State Storage Technology   | 157       | 1.67%   |
| SK hynix                         | 129       | 1.37%   |
| Silicon Motion                   | 101       | 1.07%   |
| Silicon Integrated Systems [SiS] | 100       | 1.06%   |
| Kingston Technology Company      | 83        | 0.88%   |
| Phison Electronics               | 52        | 0.55%   |
| Realtek Semiconductor            | 45        | 0.48%   |
| Nvidia                           | 39        | 0.41%   |
| KIOXIA                           | 38        | 0.4%    |
| Micron Technology                | 32        | 0.34%   |
| Toshiba America Info Systems     | 29        | 0.31%   |
| Micron/Crucial Technology        | 26        | 0.28%   |
| VIA Technologies                 | 25        | 0.27%   |
| MAXIO Technology (Hangzhou)      | 23        | 0.24%   |
| Lite-On Technology               | 20        | 0.21%   |
| Netac Technology                 | 9         | 0.1%    |
| Union Memory (Shenzhen)          | 8         | 0.09%   |
| Marvell Technology Group         | 7         | 0.07%   |
| Shenzhen Longsys Electronics     | 4         | 0.04%   |
| Apple                            | 4         | 0.04%   |
| O2 Micro                         | 2         | 0.02%   |
| TenaFe                           | 1         | 0.01%   |
| Seagate Technology               | 1         | 0.01%   |
| Lenovo                           | 1         | 0.01%   |
| INNOGRIT                         | 1         | 0.01%   |
| Beijing Starblaze Technology     | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1113      | 10.77%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 878       | 8.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 688       | 6.66%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 580       | 5.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 519       | 5.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 428       | 4.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 345       | 3.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 329       | 3.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 265       | 2.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 223       | 2.16%   |
| Intel Tiger Lake-LP SATA Controller                                              | 213       | 2.06%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 208       | 2.01%   |
| Intel Volume Management Device NVMe RAID Controller                              | 184       | 1.78%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                       | 167       | 1.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 166       | 1.61%   |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                              | 165       | 1.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 157       | 1.52%   |
| Intel Comet Lake SATA AHCI Controller                                            | 156       | 1.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 152       | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 145       | 1.4%    |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 141       | 1.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 141       | 1.36%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 133       | 1.29%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 124       | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 101       | 0.98%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 98        | 0.95%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 96        | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 88        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 86        | 0.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 85        | 0.82%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 82        | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 75        | 0.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 71        | 0.69%   |
| ADATA SM2P32A8 NVMe SSD (DRAM-less)                                              | 70        | 0.68%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 69        | 0.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 66        | 0.64%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 64        | 0.62%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 61        | 0.59%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 61        | 0.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 53        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 6648      | 66.93%  |
| NVMe | 1866      | 18.79%  |
| RAID | 810       | 8.15%   |
| IDE  | 609       | 6.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 7331      | 89.24%  |
| AMD    | 882       | 10.74%  |
| ARM    | 2         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 285       | 3.47%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 169       | 2.06%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 164       | 1.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 151       | 1.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 146       | 1.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 142       | 1.73%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 140       | 1.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 139       | 1.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 127       | 1.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 122       | 1.48%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 117       | 1.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 117       | 1.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 113       | 1.37%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 103       | 1.25%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 103       | 1.25%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 102       | 1.24%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 101       | 1.23%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 101       | 1.23%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 96        | 1.17%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 95        | 1.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 90        | 1.09%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 89        | 1.08%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 89        | 1.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 87        | 1.06%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 86        | 1.05%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 85        | 1.03%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 83        | 1.01%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 75        | 0.91%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 73        | 0.89%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 71        | 0.86%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 71        | 0.86%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 71        | 0.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 70        | 0.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 70        | 0.85%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 70        | 0.85%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 67        | 0.81%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 63        | 0.77%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 61        | 0.74%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 61        | 0.74%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 61        | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2353      | 28.63%  |
| Intel Core i7                  | 1611      | 19.6%   |
| Intel Core i3                  | 1244      | 15.14%  |
| Intel Celeron                  | 619       | 7.53%   |
| Other                          | 459       | 5.58%   |
| Intel Core 2 Duo               | 301       | 3.66%   |
| Intel Atom                     | 287       | 3.49%   |
| AMD Ryzen 5                    | 247       | 3.01%   |
| AMD Ryzen 7                    | 208       | 2.53%   |
| Intel Pentium                  | 158       | 1.92%   |
| Intel Pentium Dual-Core        | 150       | 1.83%   |
| Intel Pentium Dual             | 77        | 0.94%   |
| AMD E                          | 56        | 0.68%   |
| AMD C-60                       | 41        | 0.5%    |
| AMD E1                         | 36        | 0.44%   |
| AMD A4                         | 33        | 0.4%    |
| AMD A6                         | 29        | 0.35%   |
| Intel Genuine                  | 27        | 0.33%   |
| AMD A10                        | 24        | 0.29%   |
| Intel Core 2                   | 23        | 0.28%   |
| AMD C-70                       | 23        | 0.28%   |
| Intel Celeron Dual-Core        | 18        | 0.22%   |
| AMD C-50                       | 18        | 0.22%   |
| AMD Ryzen 3                    | 16        | 0.19%   |
| AMD A12                        | 15        | 0.18%   |
| AMD Ryzen 9                    | 14        | 0.17%   |
| Intel Celeron M                | 12        | 0.15%   |
| AMD Mobile Sempron             | 12        | 0.15%   |
| AMD Athlon II                  | 10        | 0.12%   |
| AMD Turion 64 Mobile           | 7         | 0.09%   |
| AMD Turion X2 Dual-Core Mobile | 6         | 0.07%   |
| AMD Turion 64 X2 Mobile        | 6         | 0.07%   |
| AMD Ryzen 7 PRO                | 6         | 0.07%   |
| AMD Turion II                  | 5         | 0.06%   |
| AMD Phenom II                  | 5         | 0.06%   |
| AMD Athlon 64 X2               | 5         | 0.06%   |
| Intel Pentium M                | 4         | 0.05%   |
| Intel Pentium Gold             | 4         | 0.05%   |
| AMD Turion Neo X2              | 4         | 0.05%   |
| AMD A8                         | 4         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 5061      | 61.59%  |
| 4       | 2370      | 28.84%  |
| 6       | 345       | 4.2%    |
| 8       | 206       | 2.51%   |
| 1       | 163       | 1.98%   |
| 14      | 28        | 0.34%   |
| 12      | 22        | 0.27%   |
| 10      | 15        | 0.18%   |
| Unknown | 3         | 0.04%   |
| 5       | 2         | 0.02%   |
| 3       | 2         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 8215      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 6249      | 75.98%  |
| 1       | 1971      | 23.97%  |
| Unknown | 3         | 0.04%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7898      | 95.69%  |
| Unknown        | 295       | 3.57%   |
| 32-bit         | 46        | 0.56%   |
| 64-bit         | 15        | 0.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2194      | 25.64%  |
| 0x206a7    | 624       | 7.29%   |
| 0x306a9    | 617       | 7.21%   |
| 0x806e9    | 410       | 4.79%   |
| 0x40651    | 360       | 4.21%   |
| 0x806ec    | 329       | 3.84%   |
| 0x20655    | 311       | 3.63%   |
| 0x906ea    | 300       | 3.51%   |
| 0x306d4    | 291       | 3.4%    |
| 0x406e3    | 280       | 3.27%   |
| 0x1067a    | 273       | 3.19%   |
| 0x806ea    | 258       | 3.02%   |
| 0x806c1    | 215       | 2.51%   |
| 0x406c4    | 167       | 1.95%   |
| 0x6fd      | 155       | 1.81%   |
| 0x08108109 | 107       | 1.25%   |
| 0x05000119 | 93        | 1.09%   |
| 0x08600103 | 91        | 1.06%   |
| 0x30678    | 87        | 1.02%   |
| 0x906e9    | 85        | 0.99%   |
| 0x706e5    | 82        | 0.96%   |
| 0x08108102 | 69        | 0.81%   |
| 0x706a1    | 65        | 0.76%   |
| 0x406c3    | 61        | 0.71%   |
| 0x306c3    | 60        | 0.7%    |
| 0x906ed    | 58        | 0.68%   |
| 0x706a8    | 58        | 0.68%   |
| 0xa0652    | 56        | 0.65%   |
| 0x20652    | 53        | 0.62%   |
| 0x806eb    | 50        | 0.58%   |
| 0x106ca    | 49        | 0.57%   |
| 0x08608103 | 39        | 0.46%   |
| 0x10676    | 36        | 0.42%   |
| 0x30661    | 34        | 0.4%    |
| 0x0a50000c | 30        | 0.35%   |
| 0x03000027 | 30        | 0.35%   |
| 0x506c9    | 29        | 0.34%   |
| 0x05000029 | 28        | 0.33%   |
| 0x10661    | 27        | 0.32%   |
| 0x506e3    | 24        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1963      | 23.88%  |
| IvyBridge        | 792       | 9.63%   |
| SandyBridge      | 782       | 9.51%   |
| Haswell          | 532       | 6.47%   |
| Westmere         | 454       | 5.52%   |
| Silvermont       | 402       | 4.89%   |
| Skylake          | 392       | 4.77%   |
| Penryn           | 382       | 4.65%   |
| Broadwell        | 359       | 4.37%   |
| TigerLake        | 327       | 3.98%   |
| Core             | 252       | 3.07%   |
| Zen+             | 222       | 2.7%    |
| Unknown          | 162       | 1.97%   |
| Bobcat           | 161       | 1.96%   |
| Goldmont plus    | 154       | 1.87%   |
| IceLake          | 150       | 1.82%   |
| CometLake        | 109       | 1.33%   |
| Bonnell          | 109       | 1.33%   |
| Zen 2            | 105       | 1.28%   |
| Alderlake Hybrid | 51        | 0.62%   |
| Excavator        | 49        | 0.6%    |
| K8 Hammer        | 45        | 0.55%   |
| Zen 3            | 43        | 0.52%   |
| Goldmont         | 37        | 0.45%   |
| K10 Llano        | 35        | 0.43%   |
| Zen              | 33        | 0.4%    |
| K10              | 29        | 0.35%   |
| P6               | 24        | 0.29%   |
| Jaguar           | 23        | 0.28%   |
| Nehalem          | 13        | 0.16%   |
| Piledriver       | 11        | 0.13%   |
| K8 & K10 hybrid  | 11        | 0.13%   |
| Puma             | 4         | 0.05%   |
| Steamroller      | 2         | 0.02%   |
| NetBurst         | 1         | 0.01%   |
| Gracemont        | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7037      | 66.16%  |
| Nvidia                           | 2143      | 20.15%  |
| AMD                              | 1332      | 12.52%  |
| Silicon Integrated Systems [SiS] | 100       | 0.94%   |
| VIA Technologies                 | 25        | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 782       | 7.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 767       | 7.03%   |
| Intel HD Graphics 620                                                                    | 561       | 5.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 450       | 4.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 425       | 3.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 423       | 3.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 399       | 3.66%   |
| Intel HD Graphics 5500                                                                   | 336       | 3.08%   |
| Intel UHD Graphics 620                                                                   | 334       | 3.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 318       | 2.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 296       | 2.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 289       | 2.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 281       | 2.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 271       | 2.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 222       | 2.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 196       | 1.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 162       | 1.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 154       | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 151       | 1.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 151       | 1.38%   |
| Intel HD Graphics 630                                                                    | 116       | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 113       | 1.04%   |
| Nvidia GP108M [GeForce MX150]                                                            | 109       | 1%      |
| Nvidia GM108M [GeForce 940MX]                                                            | 107       | 0.98%   |
| Nvidia GM108M [GeForce MX110]                                                            | 103       | 0.94%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 102       | 0.93%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 101       | 0.93%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 97        | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 97        | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 94        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 85        | 0.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 78        | 0.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 76        | 0.7%    |
| AMD Lucienne                                                                             | 76        | 0.7%    |
| Nvidia GP108M [GeForce MX250]                                                            | 60        | 0.55%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 56        | 0.51%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 56        | 0.51%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 52        | 0.48%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 50        | 0.46%   |
| Nvidia GP108M [GeForce MX230]                                                            | 49        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 4784      | 58.12%  |
| Intel + Nvidia | 1815      | 22.05%  |
| 1 x AMD        | 645       | 7.84%   |
| Intel + AMD    | 426       | 5.18%   |
| AMD + Nvidia   | 177       | 2.15%   |
| 1 x Nvidia     | 149       | 1.81%   |
| 1 x SiS        | 100       | 1.21%   |
| 2 x AMD        | 82        | 1%      |
| 1 x VIA        | 25        | 0.3%    |
| 2 x Intel      | 24        | 0.29%   |
| Other          | 4         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 6735      | 81.15%  |
| Proprietary | 1330      | 16.03%  |
| Unknown     | 234       | 2.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 5952      | 70.96%  |
| 1.01-2.0   | 1126      | 13.42%  |
| 0.01-0.5   | 590       | 7.03%   |
| 3.01-4.0   | 412       | 4.91%   |
| 0.51-1.0   | 201       | 2.4%    |
| 5.01-6.0   | 72        | 0.86%   |
| 2.01-3.0   | 17        | 0.2%    |
| 7.01-8.0   | 15        | 0.18%   |
| 8.01-16.0  | 3         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 1789      | 18.97%  |
| AU Optronics            | 1728      | 18.32%  |
| Chimei Innolux          | 1400      | 14.84%  |
| LG Display              | 1248      | 13.23%  |
| Samsung Electronics     | 949       | 10.06%  |
| Goldstar                | 518       | 5.49%   |
| Dell                    | 193       | 2.05%   |
| AOC                     | 190       | 2.01%   |
| Chi Mei Optoelectronics | 168       | 1.78%   |
| InfoVision              | 137       | 1.45%   |
| PANDA                   | 134       | 1.42%   |
| Apple                   | 110       | 1.17%   |
| Philips                 | 106       | 1.12%   |
| Lenovo                  | 73        | 0.77%   |
| Acer                    | 60        | 0.64%   |
| HannStar                | 50        | 0.53%   |
| CPT                     | 50        | 0.53%   |
| LG Philips              | 44        | 0.47%   |
| Sony                    | 40        | 0.42%   |
| Hewlett-Packard         | 37        | 0.39%   |
| SLD                     | 36        | 0.38%   |
| InnoLux Display         | 31        | 0.33%   |
| Sharp                   | 26        | 0.28%   |
| MTD                     | 21        | 0.22%   |
| Valve                   | 16        | 0.17%   |
| Panasonic               | 15        | 0.16%   |
| KDC                     | 14        | 0.15%   |
| ASUSTek Computer        | 14        | 0.15%   |
| GDH                     | 12        | 0.13%   |
| BenQ                    | 12        | 0.13%   |
| STA                     | 11        | 0.12%   |
| Toshiba                 | 10        | 0.11%   |
| Unknown (XXX)           | 9         | 0.1%    |
| Unknown                 | 9         | 0.1%    |
| SKY                     | 9         | 0.1%    |
| NCS                     | 9         | 0.1%    |
| VIE                     | 8         | 0.08%   |
| ITE                     | 8         | 0.08%   |
| RTK                     | 7         | 0.07%   |
| MStar                   | 6         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 130       | 1.37%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 129       | 1.36%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 128       | 1.35%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 127       | 1.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 119       | 1.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 114       | 1.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 110       | 1.16%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 107       | 1.13%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 103       | 1.09%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 88        | 0.93%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 82        | 0.86%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 82        | 0.86%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 82        | 0.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 81        | 0.85%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 78        | 0.82%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 70        | 0.74%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 67        | 0.71%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 63        | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 61        | 0.64%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 61        | 0.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 60        | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 60        | 0.63%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 59        | 0.62%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 58        | 0.61%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 57        | 0.6%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 56        | 0.59%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 52        | 0.55%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 51        | 0.54%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 50        | 0.53%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 49        | 0.52%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 47        | 0.5%    |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 47        | 0.5%    |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 47        | 0.5%    |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 45        | 0.47%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 44        | 0.46%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 43        | 0.45%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                 | 43        | 0.45%   |
| InfoVision LCD Monitor IVO03F4 1366x768 344x193mm 15.5-inch          | 42        | 0.44%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch        | 42        | 0.44%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 41        | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4819      | 53.62%  |
| 1920x1080 (FHD)    | 2688      | 29.91%  |
| 1280x800 (WXGA)    | 339       | 3.77%   |
| 2560x1080          | 198       | 2.2%    |
| 1600x900 (HD+)     | 188       | 2.09%   |
| 3840x2160 (4K)     | 143       | 1.59%   |
| 1440x900 (WXGA+)   | 112       | 1.25%   |
| 1360x768           | 82        | 0.91%   |
| 2560x1440 (QHD)    | 78        | 0.87%   |
| 1920x1200 (WUXGA)  | 57        | 0.63%   |
| 1024x600           | 43        | 0.48%   |
| 1680x1050 (WSXGA+) | 36        | 0.4%    |
| 1280x1024 (SXGA)   | 32        | 0.36%   |
| 2560x1600          | 24        | 0.27%   |
| 1024x768 (XGA)     | 23        | 0.26%   |
| 1920x540           | 21        | 0.23%   |
| 800x1280           | 16        | 0.18%   |
| 2880x1800          | 12        | 0.13%   |
| 1280x720 (HD)      | 11        | 0.12%   |
| 2288x1287          | 9         | 0.1%    |
| Unknown            | 8         | 0.09%   |
| 3840x2400          | 7         | 0.08%   |
| 1280x960           | 5         | 0.06%   |
| 3440x1440          | 4         | 0.04%   |
| 3200x1800 (QHD+)   | 4         | 0.04%   |
| 3840x1080          | 3         | 0.03%   |
| 2160x1440          | 3         | 0.03%   |
| 1024x576           | 2         | 0.02%   |
| 4240x1080          | 1         | 0.01%   |
| 3926x1080          | 1         | 0.01%   |
| 3840x1600          | 1         | 0.01%   |
| 3600x1080          | 1         | 0.01%   |
| 3456x2160          | 1         | 0.01%   |
| 3286x1080          | 1         | 0.01%   |
| 3200x2000          | 1         | 0.01%   |
| 3072x1920          | 1         | 0.01%   |
| 2880x900           | 1         | 0.01%   |
| 2646x800           | 1         | 0.01%   |
| 2640x800           | 1         | 0.01%   |
| 2400x1600          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 4056      | 43.07%  |
| 14      | 1723      | 18.3%   |
| 13      | 1487      | 15.79%  |
| 21      | 286       | 3.04%   |
| 23      | 244       | 2.59%   |
| 17      | 211       | 2.24%   |
| 18      | 188       | 2%      |
| 34      | 179       | 1.9%    |
| 24      | 147       | 1.56%   |
| 11      | 130       | 1.38%   |
| 27      | 119       | 1.26%   |
| 31      | 66        | 0.7%    |
| 12      | 65        | 0.69%   |
| 19      | 60        | 0.64%   |
| 20      | 58        | 0.62%   |
| Unknown | 53        | 0.56%   |
| 10      | 48        | 0.51%   |
| 40      | 32        | 0.34%   |
| 28      | 32        | 0.34%   |
| 54      | 27        | 0.29%   |
| 16      | 27        | 0.29%   |
| 72      | 24        | 0.25%   |
| 32      | 24        | 0.25%   |
| 84      | 20        | 0.21%   |
| 52      | 20        | 0.21%   |
| 22      | 19        | 0.2%    |
| 7       | 16        | 0.17%   |
| 46      | 9         | 0.1%    |
| 37      | 9         | 0.1%    |
| 26      | 8         | 0.08%   |
| 58      | 4         | 0.04%   |
| 48      | 4         | 0.04%   |
| 65      | 3         | 0.03%   |
| 86      | 2         | 0.02%   |
| 55      | 2         | 0.02%   |
| 49      | 2         | 0.02%   |
| 47      | 2         | 0.02%   |
| 36      | 2         | 0.02%   |
| 25      | 2         | 0.02%   |
| 142     | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 6907      | 73.89%  |
| 401-500        | 601       | 6.43%   |
| 501-600        | 495       | 5.3%    |
| 201-300        | 472       | 5.05%   |
| 351-400        | 322       | 3.44%   |
| 701-800        | 205       | 2.19%   |
| 601-700        | 110       | 1.18%   |
| 1001-1500      | 77        | 0.82%   |
| Unknown        | 53        | 0.57%   |
| 1501-2000      | 44        | 0.47%   |
| 801-900        | 42        | 0.45%   |
| 1-100          | 16        | 0.17%   |
| 901-1000       | 3         | 0.03%   |
| More than 2000 | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 7288      | 88.53%  |
| 16/10   | 601       | 7.3%    |
| 21/9    | 204       | 2.48%   |
| 4/3     | 43        | 0.52%   |
| 5/4     | 35        | 0.43%   |
| Unknown | 24        | 0.29%   |
| 0.67    | 16        | 0.19%   |
| 3/2     | 14        | 0.17%   |
| 32/9    | 4         | 0.05%   |
| 0.56    | 2         | 0.02%   |
| 1.00    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 4038      | 42.93%  |
| 81-90          | 3033      | 32.24%  |
| 201-250        | 609       | 6.47%   |
| 351-500        | 276       | 2.93%   |
| 151-200        | 198       | 2.1%    |
| 141-150        | 197       | 2.09%   |
| 71-80          | 173       | 1.84%   |
| 121-130        | 151       | 1.61%   |
| 51-60          | 130       | 1.38%   |
| 301-350        | 123       | 1.31%   |
| More than 1000 | 108       | 1.15%   |
| 501-1000       | 61        | 0.65%   |
| Unknown        | 53        | 0.56%   |
| 61-70          | 50        | 0.53%   |
| 41-50          | 48        | 0.51%   |
| 251-300        | 48        | 0.51%   |
| 91-100         | 39        | 0.41%   |
| 131-140        | 37        | 0.39%   |
| 111-120        | 19        | 0.2%    |
| 1-40           | 16        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 4986      | 54.25%  |
| 121-160       | 2386      | 25.96%  |
| 51-100        | 1425      | 15.51%  |
| 161-240       | 173       | 1.88%   |
| 1-50          | 139       | 1.51%   |
| Unknown       | 53        | 0.58%   |
| More than 240 | 28        | 0.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6578      | 78.01%  |
| 2     | 1554      | 18.43%  |
| 0     | 223       | 2.64%   |
| 3     | 75        | 0.89%   |
| 4     | 2         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5972      | 41.74%  |
| Qualcomm Atheros                  | 3451      | 24.12%  |
| Intel                             | 2708      | 18.93%  |
| Broadcom                          | 780       | 5.45%   |
| JMicron Technology                | 214       | 1.5%    |
| Marvell Technology Group          | 197       | 1.38%   |
| Broadcom Limited                  | 163       | 1.14%   |
| Ralink                            | 152       | 1.06%   |
| Silicon Integrated Systems [SiS]  | 100       | 0.7%    |
| Ralink Technology                 | 89        | 0.62%   |
| TP-Link                           | 71        | 0.5%    |
| Samsung Electronics               | 60        | 0.42%   |
| MediaTek                          | 47        | 0.33%   |
| ASIX Electronics                  | 46        | 0.32%   |
| Motorola PCS                      | 35        | 0.24%   |
| Xiaomi                            | 27        | 0.19%   |
| Nvidia                            | 26        | 0.18%   |
| VIA Technologies                  | 25        | 0.17%   |
| Qualcomm Atheros Communications   | 24        | 0.17%   |
| D-Link                            | 17        | 0.12%   |
| ICS Advent                        | 12        | 0.08%   |
| D-Link System                     | 11        | 0.08%   |
| DisplayLink                       | 10        | 0.07%   |
| Dell                              | 7         | 0.05%   |
| LG Electronics                    | 5         | 0.03%   |
| Lenovo                            | 5         | 0.03%   |
| Ericsson Business Mobile Networks | 5         | 0.03%   |
| Microsoft                         | 4         | 0.03%   |
| Huawei Technologies               | 4         | 0.03%   |
| Attansic Technology               | 4         | 0.03%   |
| Qualcomm                          | 3         | 0.02%   |
| Edimax Technology                 | 3         | 0.02%   |
| AMD                               | 3         | 0.02%   |
| OPPO Electronics                  | 2         | 0.01%   |
| NetGear                           | 2         | 0.01%   |
| Micro Star International          | 2         | 0.01%   |
| Hewlett-Packard                   | 2         | 0.01%   |
| ASUSTek Computer                  | 2         | 0.01%   |
| Arduino SA                        | 2         | 0.01%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 3430      | 21.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1587      | 10.11%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 927       | 5.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 843       | 5.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 615       | 3.92%   |
| Intel Wi-Fi 6 AX200                                                    | 338       | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 329       | 2.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 323       | 2.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 318       | 2.03%   |
| Intel Wi-Fi 6 AX201                                                    | 303       | 1.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 236       | 1.5%    |
| Intel Wireless 7265                                                    | 190       | 1.21%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 181       | 1.15%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 157       | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 150       | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 146       | 0.93%   |
| Realtek Killer E2600 GbE Controller                                    | 145       | 0.92%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter               | 108       | 0.69%   |
| Intel Wireless 7260                                                    | 108       | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 108       | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 107       | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 106       | 0.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 99        | 0.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 97        | 0.62%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 95        | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 91        | 0.58%   |
| Intel Wireless 3165                                                    | 89        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 87        | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 84        | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 83        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 82        | 0.52%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 82        | 0.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 75        | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 74        | 0.47%   |
| Intel Centrino Advanced-N 6235                                         | 74        | 0.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 74        | 0.47%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 70        | 0.45%   |
| Intel Wireless 3160                                                    | 69        | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 66        | 0.42%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 65        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 3249      | 39.39%  |
| Intel                                 | 2645      | 32.06%  |
| Realtek Semiconductor                 | 1277      | 15.48%  |
| Broadcom                              | 560       | 6.79%   |
| Ralink                                | 152       | 1.84%   |
| Broadcom Limited                      | 103       | 1.25%   |
| Ralink Technology                     | 89        | 1.08%   |
| TP-Link                               | 53        | 0.64%   |
| MediaTek                              | 42        | 0.51%   |
| Qualcomm Atheros Communications       | 24        | 0.29%   |
| D-Link                                | 17        | 0.21%   |
| D-Link System                         | 11        | 0.13%   |
| Dell                                  | 6         | 0.07%   |
| Microsoft                             | 4         | 0.05%   |
| Edimax Technology                     | 3         | 0.04%   |
| NetGear                               | 2         | 0.02%   |
| Micro Star International              | 2         | 0.02%   |
| Ericsson Business Mobile Networks     | 2         | 0.02%   |
| Sierra Wireless                       | 1         | 0.01%   |
| Qualcomm Technologies                 | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |
| Linksys                               | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 927       | 11.18%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 843       | 10.17%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 615       | 7.42%   |
| Intel Wi-Fi 6 AX200                                                     | 338       | 4.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 329       | 3.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 323       | 3.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 318       | 3.84%   |
| Intel Wi-Fi 6 AX201                                                     | 303       | 3.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 236       | 2.85%   |
| Intel Wireless 7265                                                     | 190       | 2.29%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 181       | 2.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 150       | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 146       | 1.76%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 108       | 1.3%    |
| Intel Wireless 7260                                                     | 108       | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 107       | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 106       | 1.28%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 95        | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 91        | 1.1%    |
| Intel Wireless 3165                                                     | 89        | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 87        | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 82        | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 75        | 0.9%    |
| Intel Centrino Advanced-N 6235                                          | 74        | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 74        | 0.89%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 70        | 0.84%   |
| Intel Wireless 3160                                                     | 69        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 66        | 0.8%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 65        | 0.78%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 65        | 0.78%   |
| Intel Wireless 8265 / 8275                                              | 65        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 63        | 0.76%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 62        | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 59        | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 58        | 0.7%    |
| Ralink MT7601U Wireless Adapter                                         | 55        | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 54        | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 53        | 0.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 53        | 0.64%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 53        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 5319      | 72.66%  |
| Qualcomm Atheros                 | 446       | 6.09%   |
| Intel                            | 392       | 5.36%   |
| Broadcom                         | 306       | 4.18%   |
| JMicron Technology               | 214       | 2.92%   |
| Marvell Technology Group         | 197       | 2.69%   |
| Silicon Integrated Systems [SiS] | 100       | 1.37%   |
| Broadcom Limited                 | 67        | 0.92%   |
| Samsung Electronics              | 60        | 0.82%   |
| ASIX Electronics                 | 46        | 0.63%   |
| Xiaomi                           | 27        | 0.37%   |
| Motorola PCS                     | 27        | 0.37%   |
| VIA Technologies                 | 25        | 0.34%   |
| Nvidia                           | 25        | 0.34%   |
| TP-Link                          | 18        | 0.25%   |
| ICS Advent                       | 12        | 0.16%   |
| DisplayLink                      | 10        | 0.14%   |
| Lenovo                           | 5         | 0.07%   |
| MediaTek                         | 4         | 0.05%   |
| Attansic Technology              | 4         | 0.05%   |
| Qualcomm                         | 3         | 0.04%   |
| LG Electronics                   | 3         | 0.04%   |
| OPPO Electronics                 | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.01%   |
| Spreadtrum Communications        | 1         | 0.01%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.01%   |
| Huawei Technologies              | 1         | 0.01%   |
| Google                           | 1         | 0.01%   |
| Apple                            | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 3430      | 46.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1587      | 21.53%  |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 157       | 2.13%   |
| Realtek Killer E2600 GbE Controller                                            | 145       | 1.97%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 108       | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 99        | 1.34%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 97        | 1.32%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 84        | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 83        | 1.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 82        | 1.11%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 74        | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 61        | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 60        | 0.81%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 57        | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                              | 49        | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 47        | 0.64%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 42        | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 42        | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 42        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 40        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 40        | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                                          | 37        | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 31        | 0.42%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 31        | 0.42%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 30        | 0.41%   |
| Motorola PCS moto g52                                                          | 27        | 0.37%   |
| Intel Ethernet Connection I219-LM                                              | 26        | 0.35%   |
| Intel 82577LM Gigabit Network Connection                                       | 26        | 0.35%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 25        | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 25        | 0.34%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 24        | 0.33%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 24        | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 23        | 0.31%   |
| Intel Ethernet Connection I218-LM                                              | 23        | 0.31%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 21        | 0.28%   |
| Intel Ethernet Connection (13) I219-LM                                         | 21        | 0.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 20        | 0.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 20        | 0.27%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 20        | 0.27%   |
| Intel Ethernet Connection I217-LM                                              | 19        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7957      | 52.43%  |
| Ethernet | 7180      | 47.31%  |
| Modem    | 28        | 0.18%   |
| Unknown  | 12        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6851      | 79.39%  |
| Ethernet | 1778      | 20.6%   |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 6734      | 81.74%  |
| 1     | 1214      | 14.74%  |
| 0     | 277       | 3.36%   |
| 3     | 13        | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6148      | 72.68%  |
| Yes  | 2311      | 27.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2267      | 37.69%  |
| Qualcomm Atheros Communications | 1667      | 27.71%  |
| Lite-On Technology              | 721       | 11.99%  |
| Realtek Semiconductor           | 241       | 4.01%   |
| Broadcom                        | 219       | 3.64%   |
| IMC Networks                    | 173       | 2.88%   |
| Foxconn / Hon Hai               | 137       | 2.28%   |
| Cambridge Silicon Radio         | 109       | 1.81%   |
| Apple                           | 108       | 1.8%    |
| Dell                            | 88        | 1.46%   |
| Hewlett-Packard                 | 65        | 1.08%   |
| Ralink                          | 59        | 0.98%   |
| Smart Modular Technologies      | 46        | 0.76%   |
| Qcom                            | 28        | 0.47%   |
| Ralink Technology               | 18        | 0.3%    |
| Foxconn International           | 16        | 0.27%   |
| Alps Electric                   | 15        | 0.25%   |
| Askey Computer                  | 11        | 0.18%   |
| Toshiba                         | 6         | 0.1%    |
| Opticis                         | 5         | 0.08%   |
| ASUSTek Computer                | 5         | 0.08%   |
| Micro Star International        | 4         | 0.07%   |
| Syntek                          | 2         | 0.03%   |
| USI                             | 1         | 0.02%   |
| Realtek                         | 1         | 0.02%   |
| MediaTek                        | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 976       | 16.23%  |
| Intel Bluetooth wireless interface                                                  | 709       | 11.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 638       | 10.61%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 398       | 6.62%   |
| Intel AX200 Bluetooth                                                               | 334       | 5.55%   |
| Intel AX201 Bluetooth                                                               | 301       | 5%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 260       | 4.32%   |
| Realtek Bluetooth Radio                                                             | 174       | 2.89%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 151       | 2.51%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 136       | 2.26%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 129       | 2.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 109       | 1.81%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 105       | 1.75%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 100       | 1.66%   |
| IMC Networks Bluetooth Radio                                                        | 98        | 1.63%   |
| Lite-On Bluetooth Device                                                            | 96        | 1.6%    |
| Intel Bluetooth Device                                                              | 87        | 1.45%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 71        | 1.18%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 64        | 1.06%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 62        | 1.03%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 62        | 1.03%   |
| Ralink RT3290 Bluetooth                                                             | 59        | 0.98%   |
| Apple Bluetooth Host Controller                                                     | 57        | 0.95%   |
| Smart Modular Bluetooth Device                                                      | 46        | 0.76%   |
| Dell Wireless 365 Bluetooth                                                         | 38        | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 35        | 0.58%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 34        | 0.57%   |
| IMC Networks Bluetooth Device                                                       | 32        | 0.53%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 30        | 0.5%    |
| Apple Bluetooth USB Host Controller                                                 | 30        | 0.5%    |
| Lite-On Wireless_Device                                                             | 25        | 0.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 25        | 0.42%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 25        | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 24        | 0.4%    |
| Lite-On Atheros Bluetooth                                                           | 24        | 0.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 23        | 0.38%   |
| Dell DW375 Bluetooth Module                                                         | 20        | 0.33%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 19        | 0.32%   |
| Realtek RTL8723A Bluetooth                                                          | 18        | 0.3%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 17        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 7007      | 73.33%  |
| Nvidia                                          | 1056      | 11.05%  |
| AMD                                             | 926       | 9.69%   |
| Silicon Integrated Systems [SiS]                | 100       | 1.05%   |
| C-Media Electronics                             | 91        | 0.95%   |
| Logitech                                        | 56        | 0.59%   |
| Generalplus Technology                          | 54        | 0.57%   |
| Kingston Technology                             | 29        | 0.3%    |
| VIA Technologies                                | 25        | 0.26%   |
| JMTek                                           | 23        | 0.24%   |
| Texas Instruments                               | 17        | 0.18%   |
| Corsair                                         | 14        | 0.15%   |
| Plantronics                                     | 13        | 0.14%   |
| Realtek Semiconductor                           | 11        | 0.12%   |
| Microsoft                                       | 11        | 0.12%   |
| Sony                                            | 10        | 0.1%    |
| GN Netcom                                       | 10        | 0.1%    |
| Samsung Electronics                             | 6         | 0.06%   |
| Licensed by Sony Computer Entertainment America | 6         | 0.06%   |
| JBL                                             | 5         | 0.05%   |
| Dell                                            | 5         | 0.05%   |
| Samson Technologies                             | 4         | 0.04%   |
| Razer USA                                       | 4         | 0.04%   |
| Focusrite-Novation                              | 4         | 0.04%   |
| BR23                                            | 4         | 0.04%   |
| SteelSeries ApS                                 | 3         | 0.03%   |
| Meizu                                           | 3         | 0.03%   |
| M-Audio                                         | 3         | 0.03%   |
| Lenovo                                          | 3         | 0.03%   |
| Goldvish                                        | 3         | 0.03%   |
| BEHRINGER International                         | 3         | 0.03%   |
| Astro Gaming                                    | 3         | 0.03%   |
| Turtle Beach                                    | 2         | 0.02%   |
| Tdlasunnic                                      | 2         | 0.02%   |
| Silicon Motion                                  | 2         | 0.02%   |
| Hewlett-Packard                                 | 2         | 0.02%   |
| FIFINE Microphones                              | 2         | 0.02%   |
| EDFIER                                          | 2         | 0.02%   |
| Apple                                           | 2         | 0.02%   |
| Unknown                                         | 2         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 1271      | 11.4%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1020      | 9.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 554       | 4.97%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 488       | 4.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 466       | 4.18%   |
| Intel 8 Series HD Audio Controller                                                                | 452       | 4.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 447       | 4.01%   |
| Intel Cannon Lake PCH cAVS                                                                        | 416       | 3.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 375       | 3.36%   |
| Intel Broadwell-U Audio Controller                                                                | 358       | 3.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 356       | 3.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 326       | 2.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 321       | 2.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 304       | 2.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 249       | 2.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 220       | 1.97%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 171       | 1.53%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 168       | 1.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 165       | 1.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 154       | 1.38%   |
| AMD Wrestler HDMI Audio                                                                           | 151       | 1.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 137       | 1.23%   |
| AMD FCH Azalia Controller                                                                         | 126       | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 121       | 1.09%   |
| Intel CM238 HD Audio Controller                                                                   | 119       | 1.07%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 115       | 1.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 113       | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 104       | 0.93%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 97        | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 96        | 0.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 85        | 0.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 80        | 0.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 75        | 0.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 61        | 0.55%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 56        | 0.5%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 55        | 0.49%   |
| Generalplus Technology USB Audio Device                                                           | 54        | 0.48%   |
| Nvidia Audio device                                                                               | 52        | 0.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 47        | 0.42%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 46        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 637       | 18.58%  |
| Samsung Electronics | 467       | 13.62%  |
| Kingston            | 321       | 9.36%   |
| SK hynix            | 313       | 9.13%   |
| Unknown             | 309       | 9.01%   |
| A-DATA Technology   | 286       | 8.34%   |
| Teikon              | 175       | 5.11%   |
| Micron Technology   | 146       | 4.26%   |
| Smart Brazil        | 129       | 3.76%   |
| Crucial             | 97        | 2.83%   |
| Corsair             | 77        | 2.25%   |
| High Bridge         | 68        | 1.98%   |
| Elpida              | 49        | 1.43%   |
| Unknown (ABCD)      | 39        | 1.14%   |
| Unknown             | 39        | 1.14%   |
| Multilaser          | 27        | 0.79%   |
| Nanya Technology    | 21        | 0.61%   |
| Apacer              | 21        | 0.61%   |
| Kllisre             | 16        | 0.47%   |
| Patriot             | 15        | 0.44%   |
| HT Micron           | 14        | 0.41%   |
| Ramaxel Technology  | 13        | 0.38%   |
| PUSKILL             | 10        | 0.29%   |
| Unknown (0x0B5E)    | 9         | 0.26%   |
| Smart Modular       | 8         | 0.23%   |
| Avant               | 7         | 0.2%    |
| Team                | 6         | 0.18%   |
| Atermiter           | 6         | 0.18%   |
| Walton Chaintech    | 5         | 0.15%   |
| Transcend           | 5         | 0.15%   |
| RZX                 | 4         | 0.12%   |
| Kingmax             | 4         | 0.12%   |
| Juhor               | 4         | 0.12%   |
| HBS                 | 4         | 0.12%   |
| G.Skill             | 4         | 0.12%   |
| Carry               | 4         | 0.12%   |
| 48spaces            | 4         | 0.12%   |
| Super Talent        | 3         | 0.09%   |
| Qimonda             | 3         | 0.09%   |
| Kreton              | 3         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 87        | 2.34%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s               | 56        | 1.51%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 55        | 1.48%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s               | 50        | 1.35%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s               | 46        | 1.24%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 46        | 1.24%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s               | 45        | 1.21%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s               | 45        | 1.21%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 39        | 1.05%   |
| Unknown                                                             | 39        | 1.05%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s               | 37        | 1%      |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 34        | 0.92%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s                | 28        | 0.75%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s               | 27        | 0.73%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s               | 27        | 0.73%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s               | 26        | 0.7%    |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s               | 25        | 0.67%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 24        | 0.65%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s            | 24        | 0.65%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s              | 23        | 0.62%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s               | 23        | 0.62%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s               | 23        | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 23        | 0.62%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s                | 23        | 0.62%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s              | 22        | 0.59%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s              | 20        | 0.54%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s               | 20        | 0.54%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s               | 19        | 0.51%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s                | 19        | 0.51%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s               | 19        | 0.51%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 18        | 0.48%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s             | 18        | 0.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 18        | 0.48%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s              | 17        | 0.46%   |
| A-DATA RAM AM1P26KC4U1-BACS 4GB SODIMM DDR4 2667MT/s                | 17        | 0.46%   |
| A-DATA RAM 4JQA-0622AC 4GB SODIMM DDR4 3200MT/s                     | 17        | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 16        | 0.43%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s             | 16        | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 15        | 0.4%    |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1600MT/s              | 15        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1238      | 43.93%  |
| DDR4    | 1141      | 40.49%  |
| DDR2    | 162       | 5.75%   |
| LPDDR4  | 83        | 2.95%   |
| SDRAM   | 71        | 2.52%   |
| LPDDR3  | 36        | 1.28%   |
| DDR5    | 29        | 1.03%   |
| DRAM    | 22        | 0.78%   |
| LPDDR5  | 15        | 0.53%   |
| DDR     | 13        | 0.46%   |
| Unknown | 7         | 0.25%   |
| RAM     | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2657      | 94.22%  |
| Row Of Chips | 126       | 4.47%   |
| Unknown      | 19        | 0.67%   |
| DIMM         | 16        | 0.57%   |
| Chip         | 2         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 1228      | 38%     |
| 8192  | 903       | 27.94%  |
| 2048  | 611       | 18.9%   |
| 16384 | 331       | 10.24%  |
| 1024  | 94        | 2.91%   |
| 32768 | 60        | 1.86%   |
| 512   | 5         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 788       | 24.71%  |
| 2667    | 596       | 18.69%  |
| 2400    | 344       | 10.79%  |
| 3200    | 300       | 9.41%   |
| 1334    | 262       | 8.22%   |
| 1333    | 225       | 7.06%   |
| 2133    | 105       | 3.29%   |
| Unknown | 100       | 3.14%   |
| 800     | 68        | 2.13%   |
| 667     | 64        | 2.01%   |
| 1066    | 51        | 1.6%    |
| 4199    | 44        | 1.38%   |
| 1067    | 41        | 1.29%   |
| 4267    | 28        | 0.88%   |
| 4800    | 27        | 0.85%   |
| 975     | 25        | 0.78%   |
| 533     | 23        | 0.72%   |
| 2048    | 21        | 0.66%   |
| 3266    | 12        | 0.38%   |
| 1867    | 12        | 0.38%   |
| 6400    | 11        | 0.34%   |
| 8400    | 7         | 0.22%   |
| 3733    | 5         | 0.16%   |
| 5600    | 4         | 0.13%   |
| 2933    | 4         | 0.13%   |
| 1200    | 4         | 0.13%   |
| 7467    | 3         | 0.09%   |
| 400     | 2         | 0.06%   |
| 5500    | 1         | 0.03%   |
| 3466    | 1         | 0.03%   |
| 3400    | 1         | 0.03%   |
| 3066    | 1         | 0.03%   |
| 2666    | 1         | 0.03%   |
| 2267    | 1         | 0.03%   |
| 1866    | 1         | 0.03%   |
| 1776    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1400    | 1         | 0.03%   |
| 666     | 1         | 0.03%   |
| 2       | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 25        | 39.06%  |
| Seiko Epson         | 22        | 34.38%  |
| Canon               | 7         | 10.94%  |
| Samsung Electronics | 5         | 7.81%   |
| Brother Industries  | 3         | 4.69%   |
| Xerox               | 1         | 1.56%   |
| MIIIW               | 1         | 1.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson L3150 Series                      | 7         | 10.94%  |
| HP LaserJet 1020                              | 3         | 4.69%   |
| HP DeskJet 2700 series                        | 3         | 4.69%   |
| Seiko Epson L6160 Series                      | 2         | 3.13%   |
| Seiko Epson L355 Series                       | 2         | 3.13%   |
| Seiko Epson ET-2600 Series                    | 2         | 3.13%   |
| Samsung M2020 Series                          | 2         | 3.13%   |
| HP LaserJet Professional P1102w               | 2         | 3.13%   |
| HP Ink Tank Wireless 410 series               | 2         | 3.13%   |
| HP Deskjet 3050 J610 series                   | 2         | 3.13%   |
| HP Deskjet 2540 series                        | 2         | 3.13%   |
| Canon PIXMA MG3600 Series                     | 2         | 3.13%   |
| Canon G3000 series                            | 2         | 3.13%   |
| Xerox Phaser 3040                             | 1         | 1.56%   |
| Seiko Epson XP-235 Series                     | 1         | 1.56%   |
| Seiko Epson USB2.0 Printer                    | 1         | 1.56%   |
| Seiko Epson Thermal Receipt Printer [TM-T20]  | 1         | 1.56%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.56%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]  | 1         | 1.56%   |
| Seiko Epson L805 Series                       | 1         | 1.56%   |
| Seiko Epson L382 Series                       | 1         | 1.56%   |
| Seiko Epson L360 Series                       | 1         | 1.56%   |
| Seiko Epson ET-2700 Series                    | 1         | 1.56%   |
| Samsung SCX-4623 Series                       | 1         | 1.56%   |
| Samsung SCX-4200 series                       | 1         | 1.56%   |
| Samsung M332x 382x 402x Series                | 1         | 1.56%   |
| MIIIW MW Keyboard Air Mini                    | 1         | 1.56%   |
| HP LaserJet P2015 series                      | 1         | 1.56%   |
| HP LaserJet 1018                              | 1         | 1.56%   |
| HP DeskJet Plus 6400 series                   | 1         | 1.56%   |
| HP DeskJet F4200 series                       | 1         | 1.56%   |
| HP DeskJet F4100 Printer series               | 1         | 1.56%   |
| HP DeskJet D1360                              | 1         | 1.56%   |
| HP DeskJet 3700 series                        | 1         | 1.56%   |
| HP DeskJet 3630 series                        | 1         | 1.56%   |
| HP DeskJet 2300 series                        | 1         | 1.56%   |
| HP DeskJet 2130 series                        | 1         | 1.56%   |
| HP Deskjet 1510                               | 1         | 1.56%   |
| Canon G4010 series                            | 1         | 1.56%   |
| Canon G4000 series                            | 1         | 1.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 60%     |
| Hewlett-Packard | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| HP ScanJet 2400c                   | 1         | 20%     |
| HP Scanjet 200                     | 1         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 20%     |
| Canon CanoScan LiDE 110            | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1569      | 20.78%  |
| Microdia                               | 935       | 12.39%  |
| Realtek Semiconductor                  | 762       | 10.09%  |
| Quanta                                 | 680       | 9.01%   |
| Silicon Motion                         | 599       | 7.93%   |
| Sunplus Innovation Technology          | 559       | 7.4%    |
| Bison Electronics                      | 385       | 5.1%    |
| IMC Networks                           | 362       | 4.8%    |
| Suyin                                  | 307       | 4.07%   |
| Syntek                                 | 256       | 3.39%   |
| Alcor Micro                            | 141       | 1.87%   |
| Acer                                   | 130       | 1.72%   |
| Apple                                  | 109       | 1.44%   |
| Cheng Uei Precision Industry (Foxlink) | 97        | 1.28%   |
| Logitech                               | 71        | 0.94%   |
| Samsung Electronics                    | 62        | 0.82%   |
| Sonix Technology                       | 58        | 0.77%   |
| Ricoh                                  | 54        | 0.72%   |
| ALi                                    | 47        | 0.62%   |
| Lite-On Technology                     | 26        | 0.34%   |
| Importek                               | 25        | 0.33%   |
| OmniVision Technologies                | 24        | 0.32%   |
| Z-Star Microelectronics                | 22        | 0.29%   |
| USB Camera                             | 22        | 0.29%   |
| SunplusIT                              | 21        | 0.28%   |
| Unknown                                | 20        | 0.26%   |
| Y Media                                | 19        | 0.25%   |
| Lenovo                                 | 13        | 0.17%   |
| Generalplus Technology                 | 13        | 0.17%   |
| Luxvisions Innotech Limited            | 12        | 0.16%   |
| LG Electronics                         | 11        | 0.15%   |
| Unknown                                | 11        | 0.15%   |
| Primax Electronics                     | 9         | 0.12%   |
| Intel                                  | 9         | 0.12%   |
| Pixart Imaging                         | 8         | 0.11%   |
| Sunplus Technology                     | 7         | 0.09%   |
| Shenzhen Kingcome Optoelectronic       | 7         | 0.09%   |
| Microsoft                              | 7         | 0.09%   |
| Image Processor                        | 7         | 0.09%   |
| Camera                                 | 7         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD             | 373       | 4.94%   |
| Realtek Integrated_Webcam_HD              | 339       | 4.49%   |
| Quanta HD User Facing                     | 297       | 3.93%   |
| Chicony HD WebCam                         | 239       | 3.16%   |
| Chicony HD User Facing                    | 237       | 3.14%   |
| Silicon Motion Web Camera                 | 229       | 3.03%   |
| Sunplus Integrated_Webcam_HD              | 226       | 2.99%   |
| Quanta VGA WebCam                         | 189       | 2.5%    |
| Chicony Integrated Camera                 | 179       | 2.37%   |
| Chicony USB 2.0 Camera                    | 160       | 2.12%   |
| Syntek Integrated Camera                  | 151       | 2%      |
| Chicony VGA WebCam                        | 151       | 2%      |
| Realtek Integrated Webcam                 | 125       | 1.65%   |
| Sunplus HD WebCam                         | 110       | 1.46%   |
| Quanta HD Webcam                          | 109       | 1.44%   |
| Microdia Laptop_Integrated_Webcam_HD      | 102       | 1.35%   |
| Alcor Micro USB 2.0 Camera                | 83        | 1.1%    |
| Realtek USB Camera                        | 81        | 1.07%   |
| IMC Networks Integrated Camera            | 74        | 0.98%   |
| Bison EasyCamera                          | 72        | 0.95%   |
| Bison Lenovo EasyCamera                   | 67        | 0.89%   |
| Microdia Dell Laptop Integrated Webcam HD | 65        | 0.86%   |
| Samsung Galaxy series, misc. (MTP mode)   | 62        | 0.82%   |
| Sonix USB2.0 HD UVC WebCam                | 57        | 0.75%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 57        | 0.75%   |
| Silicon Motion WebCam SC-10HDD12636N      | 55        | 0.73%   |
| Microdia Integrated Webcam HD             | 54        | 0.71%   |
| IMC Networks USB2.0 HD UVC WebCam         | 53        | 0.7%    |
| Bison VGA WebCam                          | 50        | 0.66%   |
| Acer BisonCam, NB Pro                     | 50        | 0.66%   |
| Silicon Motion WebCam SCB-1100N           | 47        | 0.62%   |
| Silicon Motion WebCam SC-0311139N         | 46        | 0.61%   |
| Suyin Integrated_Webcam_HD                | 45        | 0.6%    |
| Silicon Motion WebCam SC-13HDL11939N      | 45        | 0.6%    |
| Syntek EasyCamera                         | 44        | 0.58%   |
| Bison HD Webcam                           | 44        | 0.58%   |
| Realtek HD WebCam                         | 42        | 0.56%   |
| Microdia Integrated Webcam                | 41        | 0.54%   |
| Chicony EasyCamera                        | 41        | 0.54%   |
| Apple FaceTime HD Camera                  | 39        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 315       | 48.24%  |
| Synaptics                  | 74        | 11.33%  |
| Upek                       | 65        | 9.95%   |
| AuthenTec                  | 64        | 9.8%    |
| Shenzhen Goodix Technology | 62        | 9.49%   |
| LighTuning Technology      | 32        | 4.9%    |
| Samsung Electronics        | 20        | 3.06%   |
| Elan Microelectronics      | 11        | 1.68%   |
| STMicroelectronics         | 4         | 0.61%   |
| Focal-systems.Corp         | 2         | 0.31%   |
| Next Biometrics            | 1         | 0.15%   |
| HOLTEK                     | 1         | 0.15%   |
| DigitalPersona             | 1         | 0.15%   |
| Dell                       | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 119       | 18.22%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 55        | 8.42%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 4.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 30        | 4.59%   |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 4.59%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 27        | 4.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 26        | 3.98%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 26        | 3.98%   |
| Validity Sensors Fingerprint scanner                                       | 24        | 3.68%   |
| Shenzhen Goodix  FingerPrint Device                                        | 23        | 3.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 20        | 3.06%   |
| Samsung Fingerprint Device                                                 | 20        | 3.06%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 20        | 3.06%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 2.76%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 14        | 2.14%   |
| AuthenTec AES2810                                                          | 14        | 2.14%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.14%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 1.99%   |
| Validity Sensors VFS491                                                    | 12        | 1.84%   |
| AuthenTec Fingerprint Sensor                                               | 12        | 1.84%   |
| Elan ELAN:Fingerprint                                                      | 11        | 1.68%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 10        | 1.53%   |
| Synaptics  WBDI                                                            | 10        | 1.53%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 1.38%   |
| Upek TCS5B Fingerprint sensor                                              | 9         | 1.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 1.38%   |
| Shenzhen Goodix FingerPrint                                                | 9         | 1.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 0.92%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 0.77%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.61%   |
| AuthenTec AES1600                                                          | 4         | 0.61%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 0.46%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.31%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 2         | 0.31%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.15%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.15%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.15%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.15%   |
| Upek TouchStrip Fingerprint Sensor                                         | 1         | 0.15%   |
| Synaptics WBDI Device                                                      | 1         | 0.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 101       | 55.49%  |
| Alcor Micro               | 26        | 14.29%  |
| Lenovo                    | 15        | 8.24%   |
| Giesecke & Devrient       | 11        | 6.04%   |
| Upek                      | 10        | 5.49%   |
| Aladdin Knowledge Systems | 7         | 3.85%   |
| Watchdata                 | 5         | 2.75%   |
| O2 Micro                  | 3         | 1.65%   |
| Gemalto (was Gemplus)     | 2         | 1.1%    |
| SCM Microsystems          | 1         | 0.55%   |
| Advanced Card Systems     | 1         | 0.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 30        | 16.48%  |
| Broadcom 5880                                                                | 26        | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 25        | 13.74%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 10.99%  |
| Lenovo Integrated Smart Card Reader                                          | 15        | 8.24%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 5.49%   |
| Giesecke & Devrient StarSign CUT                                             | 8         | 4.4%    |
| Aladdin Knowledge Systems Token JC                                           | 7         | 3.85%   |
| Watchdata USB Key                                                            | 5         | 2.75%   |
| Giesecke & Devrient StarSign CUT S                                           | 3         | 1.65%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.1%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.1%    |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.55%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.55%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 6314      | 75.45%  |
| 1     | 1770      | 21.15%  |
| 2     | 232       | 2.77%   |
| 3     | 33        | 0.39%   |
| 4     | 9         | 0.11%   |
| 7     | 4         | 0.05%   |
| 5     | 3         | 0.04%   |
| 8     | 2         | 0.02%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 700       | 29.89%  |
| Fingerprint reader       | 650       | 27.75%  |
| Multimedia controller    | 255       | 10.89%  |
| Net/wireless             | 192       | 8.2%    |
| Chipcard                 | 158       | 6.75%   |
| Bluetooth                | 99        | 4.23%   |
| Camera                   | 77        | 3.29%   |
| Communication controller | 49        | 2.09%   |
| Storage                  | 48        | 2.05%   |
| Sound                    | 38        | 1.62%   |
| Net/ethernet             | 28        | 1.2%    |
| Flash memory             | 23        | 0.98%   |
| Card reader              | 8         | 0.34%   |
| Modem                    | 7         | 0.3%    |
| Firewire controller      | 4         | 0.17%   |
| Network                  | 3         | 0.13%   |
| Unassigned class         | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |

