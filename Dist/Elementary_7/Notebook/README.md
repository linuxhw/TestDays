Elementary 7 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Elementary 7.

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

Total: 226

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Medion        | E6217                       | [c2ca377a05](https://linux-hardware.org/?probe=c2ca377a05) | Mar 31, 2024 |
| Dell          | Latitude E6400              | [6a3537c763](https://linux-hardware.org/?probe=6a3537c763) | Oct 23, 2023 |
| Dell          | Latitude E7270              | [874b8a2ad5](https://linux-hardware.org/?probe=874b8a2ad5) | Sep 23, 2023 |
| HP            | Laptop 17-by4xxx            | [dd1d978c67](https://linux-hardware.org/?probe=dd1d978c67) | Sep 22, 2023 |
| Apple         | MacBookAir7,2               | [3941e3e259](https://linux-hardware.org/?probe=3941e3e259) | Sep 16, 2023 |
| Apple         | MacBookAir7,2               | [1ea319e72e](https://linux-hardware.org/?probe=1ea319e72e) | Sep 15, 2023 |
| Apple         | MacBook6,1                  | [8db6f2c947](https://linux-hardware.org/?probe=8db6f2c947) | Sep 14, 2023 |
| Apple         | MacBookPro11,2              | [d3996a81e2](https://linux-hardware.org/?probe=d3996a81e2) | Sep 07, 2023 |
| Dell          | Latitude E5570              | [10d8ad7a3d](https://linux-hardware.org/?probe=10d8ad7a3d) | Sep 05, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [7a27c6dd8d](https://linux-hardware.org/?probe=7a27c6dd8d) | Sep 03, 2023 |
| Apple         | MacBookAir6,2               | [783d0f51f5](https://linux-hardware.org/?probe=783d0f51f5) | Aug 31, 2023 |
| Medion        | E15301                      | [7f6c4eb814](https://linux-hardware.org/?probe=7f6c4eb814) | Aug 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [24ad5e2b06](https://linux-hardware.org/?probe=24ad5e2b06) | Aug 31, 2023 |
| HP            | 350 G1                      | [1e317e5a51](https://linux-hardware.org/?probe=1e317e5a51) | Aug 30, 2023 |
| Digma         | EVE 11 C421Y ES1067EW       | [22e88dc9a5](https://linux-hardware.org/?probe=22e88dc9a5) | Aug 29, 2023 |
| Apple         | MacBookAir6,2               | [7c208705e5](https://linux-hardware.org/?probe=7c208705e5) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | [8741a9bb96](https://linux-hardware.org/?probe=8741a9bb96) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | [7efcdba9ef](https://linux-hardware.org/?probe=7efcdba9ef) | Aug 29, 2023 |
| HP            | 350 G1                      | [d800790bce](https://linux-hardware.org/?probe=d800790bce) | Aug 28, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [627068909d](https://linux-hardware.org/?probe=627068909d) | Aug 25, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [5c956051fb](https://linux-hardware.org/?probe=5c956051fb) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | [744be89da4](https://linux-hardware.org/?probe=744be89da4) | Aug 24, 2023 |
| Google        | Eldrid                      | [e451d840cf](https://linux-hardware.org/?probe=e451d840cf) | Aug 24, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [01a44fbb3b](https://linux-hardware.org/?probe=01a44fbb3b) | Aug 20, 2023 |
| Apple         | MacBookPro9,2               | [551dc38c00](https://linux-hardware.org/?probe=551dc38c00) | Aug 19, 2023 |
| Apple         | MacBookPro9,2               | [0bbf9ab6c2](https://linux-hardware.org/?probe=0bbf9ab6c2) | Aug 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [8298417da7](https://linux-hardware.org/?probe=8298417da7) | Aug 16, 2023 |
| Apple         | MacBookPro5,5               | [dc696b572c](https://linux-hardware.org/?probe=dc696b572c) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | [5d7e68e3ae](https://linux-hardware.org/?probe=5d7e68e3ae) | Aug 14, 2023 |
| Acer          | Swift SF515-51T             | [9271029425](https://linux-hardware.org/?probe=9271029425) | Aug 13, 2023 |
| Apple         | MacBookPro6,2               | [7c62a05800](https://linux-hardware.org/?probe=7c62a05800) | Aug 12, 2023 |
| Acer          | TravelMate B113             | [5d3d27c8bb](https://linux-hardware.org/?probe=5d3d27c8bb) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [80f2f711d8](https://linux-hardware.org/?probe=80f2f711d8) | Aug 10, 2023 |
| HP            | ProBook 4310s               | [ac0c1be078](https://linux-hardware.org/?probe=ac0c1be078) | Aug 09, 2023 |
| HP            | EliteBook 850 G3            | [04a319c904](https://linux-hardware.org/?probe=04a319c904) | Aug 09, 2023 |
| Apple         | MacBookPro8,1               | [6165a2d50e](https://linux-hardware.org/?probe=6165a2d50e) | Aug 08, 2023 |
| HP            | G60                         | [7f3b9aec85](https://linux-hardware.org/?probe=7f3b9aec85) | Aug 07, 2023 |
| Lenovo        | ThinkPad X201 Tablet 298... | [7132bbeb85](https://linux-hardware.org/?probe=7132bbeb85) | Aug 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2b8f90f79d](https://linux-hardware.org/?probe=2b8f90f79d) | Aug 03, 2023 |
| Acer          | Predator G3-571             | [fc950e8651](https://linux-hardware.org/?probe=fc950e8651) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [73e1dd94b2](https://linux-hardware.org/?probe=73e1dd94b2) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f4ed3cb1f](https://linux-hardware.org/?probe=2f4ed3cb1f) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [a13fd4044e](https://linux-hardware.org/?probe=a13fd4044e) | Aug 01, 2023 |
| SHENZHEN Y... | A8S PRO                     | [829a4178a5](https://linux-hardware.org/?probe=829a4178a5) | Jul 30, 2023 |
| Apple         | MacBookPro11,3              | [c7572ce663](https://linux-hardware.org/?probe=c7572ce663) | Jul 30, 2023 |
| Apple         | MacBookPro11,3              | [8ac9af1db8](https://linux-hardware.org/?probe=8ac9af1db8) | Jul 29, 2023 |
| SHENZHEN Y... | A8S PRO                     | [08a6feda0e](https://linux-hardware.org/?probe=08a6feda0e) | Jul 28, 2023 |
| HP            | 255 G8 Notebook PC          | [c2e02d1490](https://linux-hardware.org/?probe=c2e02d1490) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a5359c62e0](https://linux-hardware.org/?probe=a5359c62e0) | Jul 20, 2023 |
| Alienware     | m15 R6                      | [93d5e98358](https://linux-hardware.org/?probe=93d5e98358) | Jul 20, 2023 |
| HP            | Notebook                    | [2ccf016245](https://linux-hardware.org/?probe=2ccf016245) | Jul 19, 2023 |
| Apple         | MacBookPro8,1               | [7dd13cea49](https://linux-hardware.org/?probe=7dd13cea49) | Jul 17, 2023 |
| Google        | Phaser360                   | [1e66458514](https://linux-hardware.org/?probe=1e66458514) | Jul 17, 2023 |
| HP            | ENVY 15                     | [a173db4ea1](https://linux-hardware.org/?probe=a173db4ea1) | Jul 17, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | [2c05f1a964](https://linux-hardware.org/?probe=2c05f1a964) | Jul 16, 2023 |
| Apple         | MacBookPro8,1               | [74420b09b7](https://linux-hardware.org/?probe=74420b09b7) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1a0add8887](https://linux-hardware.org/?probe=1a0add8887) | Jul 11, 2023 |
| HP            | ENVY 15                     | [3ccdaf4d4e](https://linux-hardware.org/?probe=3ccdaf4d4e) | Jul 10, 2023 |
| Apple         | MacBookPro12,1              | [8877b51b89](https://linux-hardware.org/?probe=8877b51b89) | Jul 08, 2023 |
| HP            | Laptop 14-dq0xxx            | [bb065938a5](https://linux-hardware.org/?probe=bb065938a5) | Jul 07, 2023 |
| Apple         | MacBookPro8,1               | [ee299280f8](https://linux-hardware.org/?probe=ee299280f8) | Jul 07, 2023 |
| Dell          | Latitude E7270              | [406e4a918b](https://linux-hardware.org/?probe=406e4a918b) | Jul 06, 2023 |
| Intel Clie... | LAPBC710                    | [fd97a27365](https://linux-hardware.org/?probe=fd97a27365) | Jul 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [2e4a653435](https://linux-hardware.org/?probe=2e4a653435) | Jul 04, 2023 |
| Apple         | MacBookPro9,2               | [f7a7db0702](https://linux-hardware.org/?probe=f7a7db0702) | Jul 04, 2023 |
| GPD           | MicroPC                     | [f666f4c574](https://linux-hardware.org/?probe=f666f4c574) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 23254W5       | [5842896b76](https://linux-hardware.org/?probe=5842896b76) | Jul 03, 2023 |
| HP            | Laptop 17-by3xxx            | [8bfe14749f](https://linux-hardware.org/?probe=8bfe14749f) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430 2349OB6       | [f2f66bb9d0](https://linux-hardware.org/?probe=f2f66bb9d0) | Jun 29, 2023 |
| Dell          | Inspiron 3501               | [afc9f56d8d](https://linux-hardware.org/?probe=afc9f56d8d) | Jun 28, 2023 |
| Dell          | Latitude E5470              | [e10153b4c9](https://linux-hardware.org/?probe=e10153b4c9) | Jun 23, 2023 |
| Toshiba       | TECRA R850                  | [a75e6d35da](https://linux-hardware.org/?probe=a75e6d35da) | Jun 21, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [293b8783a3](https://linux-hardware.org/?probe=293b8783a3) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [2f452cfce0](https://linux-hardware.org/?probe=2f452cfce0) | Jun 20, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [f49534dfa4](https://linux-hardware.org/?probe=f49534dfa4) | Jun 19, 2023 |
| ASUSTek       | X555LA                      | [a57885e16c](https://linux-hardware.org/?probe=a57885e16c) | Jun 18, 2023 |
| ASUSTek       | X555LA                      | [782fa74afe](https://linux-hardware.org/?probe=782fa74afe) | Jun 14, 2023 |
| Razer         | Blade Stealth               | [f218e04a1c](https://linux-hardware.org/?probe=f218e04a1c) | Jun 14, 2023 |
| Apple         | MacBookPro8,1               | [d487214e2a](https://linux-hardware.org/?probe=d487214e2a) | Jun 08, 2023 |
| Apple         | MacBookPro11,1              | [6c62565787](https://linux-hardware.org/?probe=6c62565787) | Jun 07, 2023 |
| ASUSTek       | G750JM                      | [b2281ad2cb](https://linux-hardware.org/?probe=b2281ad2cb) | Jun 06, 2023 |
| Toshiba       | TECRA Z40-C                 | [1ebf23281e](https://linux-hardware.org/?probe=1ebf23281e) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | [274b78cda3](https://linux-hardware.org/?probe=274b78cda3) | Jun 03, 2023 |
| Apple         | MacBookAir7,2               | [119fd5249f](https://linux-hardware.org/?probe=119fd5249f) | Jun 03, 2023 |
| HUAWEI        | BOD-WXX9                    | [532dea434a](https://linux-hardware.org/?probe=532dea434a) | Jun 02, 2023 |
| HP            | G62                         | [f2600c2f4b](https://linux-hardware.org/?probe=f2600c2f4b) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS08H00    | [71208c2344](https://linux-hardware.org/?probe=71208c2344) | Jun 01, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [827e0203ac](https://linux-hardware.org/?probe=827e0203ac) | May 31, 2023 |
| ASUSTek       | X550WA                      | [864236b0c9](https://linux-hardware.org/?probe=864236b0c9) | May 29, 2023 |
| PCBOX         | Kant                        | [1e2f772d05](https://linux-hardware.org/?probe=1e2f772d05) | May 29, 2023 |
| HP            | ProBook 440 G6              | [35d14ed328](https://linux-hardware.org/?probe=35d14ed328) | May 29, 2023 |
| HP            | ProBook 440 G6              | [36a3563566](https://linux-hardware.org/?probe=36a3563566) | May 29, 2023 |
| HP            | ProBook 4540s               | [124c8183a8](https://linux-hardware.org/?probe=124c8183a8) | May 26, 2023 |
| Acer          | Aspire 7750G                | [1ddb5fe9a0](https://linux-hardware.org/?probe=1ddb5fe9a0) | May 26, 2023 |
| Dell          | Precision 5530              | [702b4d7914](https://linux-hardware.org/?probe=702b4d7914) | May 26, 2023 |
| Dell          | Latitude E5470              | [6054d2ee2b](https://linux-hardware.org/?probe=6054d2ee2b) | May 25, 2023 |
| Acer          | Aspire 7750G                | [4ddad1d733](https://linux-hardware.org/?probe=4ddad1d733) | May 24, 2023 |
| HP            | ProBook 4310s               | [1a32d434c0](https://linux-hardware.org/?probe=1a32d434c0) | May 21, 2023 |
| Acer          | Aspire 7750G                | [61ebf173dc](https://linux-hardware.org/?probe=61ebf173dc) | May 21, 2023 |
| HP            | Laptop 17-by3xxx            | [7f15c1b9e3](https://linux-hardware.org/?probe=7f15c1b9e3) | May 21, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [ff730fcbf6](https://linux-hardware.org/?probe=ff730fcbf6) | May 20, 2023 |
| HP            | Pavilion Notebook           | [73d62695e4](https://linux-hardware.org/?probe=73d62695e4) | May 18, 2023 |
| HP            | Pavilion Notebook           | [56aa17165e](https://linux-hardware.org/?probe=56aa17165e) | May 18, 2023 |
| HP            | ProBook 4310s               | [dfcb51e697](https://linux-hardware.org/?probe=dfcb51e697) | May 17, 2023 |
| HP            | EliteBook 840 14 inch G9... | [004f548439](https://linux-hardware.org/?probe=004f548439) | May 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8fb1a89166](https://linux-hardware.org/?probe=8fb1a89166) | May 17, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [155b921e10](https://linux-hardware.org/?probe=155b921e10) | May 13, 2023 |
| Acer          | Aspire E3-111               | [1060697095](https://linux-hardware.org/?probe=1060697095) | May 10, 2023 |
| HP            | Laptop 15s-eq0xxx           | [58000b3a57](https://linux-hardware.org/?probe=58000b3a57) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| HONOR         | BMH-WCX9                    | [ea0b55ed61](https://linux-hardware.org/?probe=ea0b55ed61) | May 07, 2023 |
| HONOR         | BMH-WCX9                    | [df06b3c5b3](https://linux-hardware.org/?probe=df06b3c5b3) | May 07, 2023 |
| MSI           | GE62VR 6RF                  | [bac71eb24d](https://linux-hardware.org/?probe=bac71eb24d) | May 06, 2023 |
| Lenovo        | ThinkPad P51s 20HB001TUS    | [eac4ebdef0](https://linux-hardware.org/?probe=eac4ebdef0) | May 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [834d2304aa](https://linux-hardware.org/?probe=834d2304aa) | May 06, 2023 |
| Clevo         | NL41MU2                     | [6a80029392](https://linux-hardware.org/?probe=6a80029392) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [fe61386871](https://linux-hardware.org/?probe=fe61386871) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [764f38bb65](https://linux-hardware.org/?probe=764f38bb65) | May 05, 2023 |
| HP            | ProBook 450 G6              | [c5927045a3](https://linux-hardware.org/?probe=c5927045a3) | May 04, 2023 |
| MSI           | GE62VR 6RF                  | [97acececd3](https://linux-hardware.org/?probe=97acececd3) | Apr 28, 2023 |
| Apple         | MacBookPro5,2               | [c188ae4d7d](https://linux-hardware.org/?probe=c188ae4d7d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| MSI           | GE62VR 6RF                  | [2a9fcae8c3](https://linux-hardware.org/?probe=2a9fcae8c3) | Apr 28, 2023 |
| HUAWEI        | BOD-WXX9                    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| MSI           | PE70 6QE                    | [87c8761eff](https://linux-hardware.org/?probe=87c8761eff) | Apr 27, 2023 |
| HP            | 250 G8 Notebook PC          | [b03cd2f2d2](https://linux-hardware.org/?probe=b03cd2f2d2) | Apr 26, 2023 |
| MSI           | PE70 6QE                    | [53dd8334ac](https://linux-hardware.org/?probe=53dd8334ac) | Apr 26, 2023 |
| Lenovo        | G580 20150                  | [5d8b07dbbd](https://linux-hardware.org/?probe=5d8b07dbbd) | Apr 25, 2023 |
| Dell          | Latitude E4300              | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | [763953fb60](https://linux-hardware.org/?probe=763953fb60) | Apr 22, 2023 |
| HP            | Pavilion g6                 | [4d60e2b7da](https://linux-hardware.org/?probe=4d60e2b7da) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | [94bf014457](https://linux-hardware.org/?probe=94bf014457) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | [2ebc6a2f61](https://linux-hardware.org/?probe=2ebc6a2f61) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | [ff6dbdcc10](https://linux-hardware.org/?probe=ff6dbdcc10) | Apr 15, 2023 |
| MSI           | PE70 6QE                    | [936a7d1fe3](https://linux-hardware.org/?probe=936a7d1fe3) | Apr 15, 2023 |
| Dell          | Latitude 5420               | [4c6427b3fc](https://linux-hardware.org/?probe=4c6427b3fc) | Apr 14, 2023 |
| Apple         | MacBookAir3,2               | [c750ece414](https://linux-hardware.org/?probe=c750ece414) | Apr 12, 2023 |
| Dell          | Latitude E5570              | [81eaf54f19](https://linux-hardware.org/?probe=81eaf54f19) | Apr 07, 2023 |
| Apple         | MacBookPro10,1              | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| HUAWEI        | BOD-WXX9                    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| HP            | Pavilion 15                 | [1a3e968dff](https://linux-hardware.org/?probe=1a3e968dff) | Apr 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f7f207f61c](https://linux-hardware.org/?probe=f7f207f61c) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | [e06d57c27a](https://linux-hardware.org/?probe=e06d57c27a) | Apr 01, 2023 |
| HUAWEI        | NBD-WXX9                    | [d4c718bdab](https://linux-hardware.org/?probe=d4c718bdab) | Apr 01, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| Dell          | Latitude E7440              | [1159c854cd](https://linux-hardware.org/?probe=1159c854cd) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | [a9a8004509](https://linux-hardware.org/?probe=a9a8004509) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | [1dccfbe9f4](https://linux-hardware.org/?probe=1dccfbe9f4) | Mar 29, 2023 |
| Dell          | Latitude 5420               | [d714c46c4f](https://linux-hardware.org/?probe=d714c46c4f) | Mar 29, 2023 |
| Toshiba       | TECRA Z40-C                 | [39995c1c00](https://linux-hardware.org/?probe=39995c1c00) | Mar 24, 2023 |
| Dell          | Latitude E7440              | [1a986dbeb8](https://linux-hardware.org/?probe=1a986dbeb8) | Mar 24, 2023 |
| HONOR         | HYM-WXX                     | [df318ed208](https://linux-hardware.org/?probe=df318ed208) | Mar 21, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Latitude E5570              | [a15d1b43ca](https://linux-hardware.org/?probe=a15d1b43ca) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [dd07b0c3b3](https://linux-hardware.org/?probe=dd07b0c3b3) | Mar 17, 2023 |
| Dell          | G3 3590                     | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | [03e5d43f27](https://linux-hardware.org/?probe=03e5d43f27) | Mar 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | [4c49d73583](https://linux-hardware.org/?probe=4c49d73583) | Mar 15, 2023 |
| Apple         | MacBookPro5,5               | [c6ff6d14a0](https://linux-hardware.org/?probe=c6ff6d14a0) | Mar 15, 2023 |
| Acer          | Aspire V3-771               | [28f8273eb5](https://linux-hardware.org/?probe=28f8273eb5) | Mar 15, 2023 |
| MSI           | GT72 2QE                    | [b3c4766473](https://linux-hardware.org/?probe=b3c4766473) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK A359               | [0fa1ebbc11](https://linux-hardware.org/?probe=0fa1ebbc11) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK A359               | [f977012127](https://linux-hardware.org/?probe=f977012127) | Mar 11, 2023 |
| Apple         | MacBookPro11,2              | [fce6120754](https://linux-hardware.org/?probe=fce6120754) | Mar 11, 2023 |
| Acer          | Aspire A715-72G             | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| Toshiba       | TECRA Z40-C                 | [a4ba2ff90e](https://linux-hardware.org/?probe=a4ba2ff90e) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Sony          | VPCEH2C5E                   | [adf4a69310](https://linux-hardware.org/?probe=adf4a69310) | Mar 07, 2023 |
| Sony          | VPCEH2C5E                   | [9e5b625dda](https://linux-hardware.org/?probe=9e5b625dda) | Mar 07, 2023 |
| GPU Compan... | GWTN156-11                  | [5afd8e3f42](https://linux-hardware.org/?probe=5afd8e3f42) | Mar 04, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [817b72f78f](https://linux-hardware.org/?probe=817b72f78f) | Mar 02, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [053c6d5368](https://linux-hardware.org/?probe=053c6d5368) | Mar 02, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [1025a9748f](https://linux-hardware.org/?probe=1025a9748f) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | [e189c60b09](https://linux-hardware.org/?probe=e189c60b09) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | [3883ba28c7](https://linux-hardware.org/?probe=3883ba28c7) | Mar 01, 2023 |
| Apple         | MacBookAir3,1               | [573644760d](https://linux-hardware.org/?probe=573644760d) | Feb 28, 2023 |
| Fujitsu       | LIFEBOOK E744               | [e331c5e257](https://linux-hardware.org/?probe=e331c5e257) | Feb 27, 2023 |
| Acer          | Aspire E5-771               | [73c974942f](https://linux-hardware.org/?probe=73c974942f) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a66f75c107](https://linux-hardware.org/?probe=a66f75c107) | Feb 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [50a16e7924](https://linux-hardware.org/?probe=50a16e7924) | Feb 25, 2023 |
| HP            | ProBook 430 G4              | [b815c24c07](https://linux-hardware.org/?probe=b815c24c07) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | [e578b951f9](https://linux-hardware.org/?probe=e578b951f9) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | [0dc5add67b](https://linux-hardware.org/?probe=0dc5add67b) | Feb 24, 2023 |
| Lenovo        | ThinkPad T400s 2808D9G      | [b101883e65](https://linux-hardware.org/?probe=b101883e65) | Feb 24, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | [0a3d750f36](https://linux-hardware.org/?probe=0a3d750f36) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ddd8c34644](https://linux-hardware.org/?probe=ddd8c34644) | Feb 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | [c79a8f48f9](https://linux-hardware.org/?probe=c79a8f48f9) | Feb 20, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | [7ee9e59831](https://linux-hardware.org/?probe=7ee9e59831) | Feb 20, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [2751aac3e0](https://linux-hardware.org/?probe=2751aac3e0) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| HP            | 550                         | [81b67f211d](https://linux-hardware.org/?probe=81b67f211d) | Feb 15, 2023 |
| Dell          | XPS 15 9560                 | [150c1de326](https://linux-hardware.org/?probe=150c1de326) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | [e8a460c42c](https://linux-hardware.org/?probe=e8a460c42c) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | [a92df0196e](https://linux-hardware.org/?probe=a92df0196e) | Feb 15, 2023 |
| HP            | EliteBook 8460p             | [92ab9b2e0d](https://linux-hardware.org/?probe=92ab9b2e0d) | Feb 14, 2023 |
| Acer          | Aspire V3-771               | [f22c83d683](https://linux-hardware.org/?probe=f22c83d683) | Feb 14, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [12431d8083](https://linux-hardware.org/?probe=12431d8083) | Feb 14, 2023 |
| Acer          | Extensa 5230                | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | [a1d85b3098](https://linux-hardware.org/?probe=a1d85b3098) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | [6e8ed5d5d6](https://linux-hardware.org/?probe=6e8ed5d5d6) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| HP            | Laptop 15-dy2xxx            | [b906f960a0](https://linux-hardware.org/?probe=b906f960a0) | Feb 08, 2023 |
| HP            | Laptop 14-bs0xx             | [c3607bb4c2](https://linux-hardware.org/?probe=c3607bb4c2) | Feb 07, 2023 |
| HP            | Laptop 17-by3xxx            | [07ea9d3c2f](https://linux-hardware.org/?probe=07ea9d3c2f) | Feb 06, 2023 |
| Acer          | Aspire E5-575G              | [30e2a88930](https://linux-hardware.org/?probe=30e2a88930) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | [10f8560601](https://linux-hardware.org/?probe=10f8560601) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | [be37cc70f5](https://linux-hardware.org/?probe=be37cc70f5) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | [8d67e1438d](https://linux-hardware.org/?probe=8d67e1438d) | Feb 05, 2023 |
| Apple         | MacBookPro11,3              | [8bdb86b164](https://linux-hardware.org/?probe=8bdb86b164) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [9d397c2187](https://linux-hardware.org/?probe=9d397c2187) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [7b676dec23](https://linux-hardware.org/?probe=7b676dec23) | Feb 04, 2023 |
| Dell          | Vostro 3460                 | [8aa57f1d6d](https://linux-hardware.org/?probe=8aa57f1d6d) | Feb 03, 2023 |
| Dell          | Vostro 3460                 | [78919f6127](https://linux-hardware.org/?probe=78919f6127) | Feb 03, 2023 |
| Alienware     | x17 R2                      | [474a70c148](https://linux-hardware.org/?probe=474a70c148) | Feb 03, 2023 |
| Sony          | SVF1521O4E                  | [e2d47879d4](https://linux-hardware.org/?probe=e2d47879d4) | Feb 02, 2023 |
| Lenovo        | ThinkPad X230 23259S9       | [3d9e74535f](https://linux-hardware.org/?probe=3d9e74535f) | Feb 01, 2023 |
| Star Labs     | StarBook                    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS01W02    | [cc7b02033a](https://linux-hardware.org/?probe=cc7b02033a) | Dec 24, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.15.0-58-generic    | 40        | 24.54%  |
| 5.19.0-41-generic    | 18        | 11.04%  |
| 5.19.0-35-generic    | 16        | 9.82%   |
| 6.2.0-26-generic     | 14        | 8.59%   |
| 5.19.0-46-generic    | 14        | 8.59%   |
| 5.19.0-32-generic    | 12        | 7.36%   |
| 5.19.0-38-generic    | 10        | 6.13%   |
| 5.19.0-43-generic    | 9         | 5.52%   |
| 6.2.0-31-generic     | 5         | 3.07%   |
| 5.19.0-50-generic    | 4         | 2.45%   |
| 5.19.0-40-generic    | 4         | 2.45%   |
| 5.15.0-60-generic    | 4         | 2.45%   |
| 6.2.0-32-generic     | 3         | 1.84%   |
| 5.19.0-45-generic    | 2         | 1.23%   |
| 5.19.0-42-generic    | 2         | 1.23%   |
| 6.2.7-060207-generic | 1         | 0.61%   |
| 6.1.9-060109-generic | 1         | 0.61%   |
| 6.1.6-060106-generic | 1         | 0.61%   |
| 6.1.0-1013-oem       | 1         | 0.61%   |
| 5.15.0-79-generic    | 1         | 0.61%   |
| 5.15.0-56-generic    | 1         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.0  | 86        | 54.43%  |
| 5.15.0  | 46        | 29.11%  |
| 6.2.0   | 22        | 13.92%  |
| 6.2.7   | 1         | 0.63%   |
| 6.1.9   | 1         | 0.63%   |
| 6.1.6   | 1         | 0.63%   |
| 6.1.0   | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19    | 86        | 54.43%  |
| 5.15    | 46        | 29.11%  |
| 6.2     | 23        | 14.56%  |
| 6.1     | 3         | 1.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 155       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 155       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 155       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 123       | 79.35%  |
| LightDM | 32        | 20.65%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 73        | 47.1%   |
| de_DE | 24        | 15.48%  |
| ru_RU | 14        | 9.03%   |
| es_ES | 12        | 7.74%   |
| fr_FR | 5         | 3.23%   |
| pl_PL | 4         | 2.58%   |
| en_GB | 4         | 2.58%   |
| it_IT | 3         | 1.94%   |
| sv_SE | 2         | 1.29%   |
| pt_BR | 2         | 1.29%   |
| nb_NO | 2         | 1.29%   |
| en_AU | 2         | 1.29%   |
| el_GR | 2         | 1.29%   |
| uk_UA | 1         | 0.65%   |
| tr_TR | 1         | 0.65%   |
| pt_PT | 1         | 0.65%   |
| hu_HU | 1         | 0.65%   |
| da_DK | 1         | 0.65%   |
| bg_BG | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 130       | 83.87%  |
| EFI  | 25        | 16.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 148       | 94.87%  |
| Tmpfs   | 5         | 3.21%   |
| Xfs     | 1         | 0.64%   |
| Overlay | 1         | 0.64%   |
| Btrfs   | 1         | 0.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 123       | 79.35%  |
| GPT     | 27        | 17.42%  |
| MBR     | 5         | 3.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 153       | 98.71%  |
| Yes       | 2         | 1.29%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 143       | 92.26%  |
| Yes       | 12        | 7.74%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 29        | 18.71%  |
| Lenovo                      | 28        | 18.06%  |
| Apple                       | 26        | 16.77%  |
| Dell                        | 15        | 9.68%   |
| ASUSTek Computer            | 13        | 8.39%   |
| Acer                        | 10        | 6.45%   |
| HUAWEI                      | 5         | 3.23%   |
| MSI                         | 4         | 2.58%   |
| Toshiba                     | 3         | 1.94%   |
| Fujitsu                     | 3         | 1.94%   |
| Sony                        | 2         | 1.29%   |
| Medion                      | 2         | 1.29%   |
| HONOR                       | 2         | 1.29%   |
| Google                      | 2         | 1.29%   |
| Alienware                   | 2         | 1.29%   |
| Star Labs                   | 1         | 0.65%   |
| SHENZHEN YOUDISI E-COMMERCE | 1         | 0.65%   |
| Samsung Electronics         | 1         | 0.65%   |
| Razer                       | 1         | 0.65%   |
| PCBOX                       | 1         | 0.65%   |
| GPU Company                 | 1         | 0.65%   |
| GPD                         | 1         | 0.65%   |
| Digma                       | 1         | 0.65%   |
| Clevo                       | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Apple MacBookPro9,2                        | 3         | 1.94%   |
| Apple MacBookPro8,1                        | 3         | 1.94%   |
| HUAWEI BOD-WXX9                            | 2         | 1.29%   |
| HP 255 G7 Notebook PC                      | 2         | 1.29%   |
| Dell Latitude E7270                        | 2         | 1.29%   |
| Dell Latitude E5570                        | 2         | 1.29%   |
| Apple MacBookPro5,5                        | 2         | 1.29%   |
| Apple MacBookPro11,3                       | 2         | 1.29%   |
| Apple MacBookPro11,2                       | 2         | 1.29%   |
| Apple MacBookAir7,2                        | 2         | 1.29%   |
| Apple MacBookAir6,2                        | 2         | 1.29%   |
| Toshiba TECRA Z40-C                        | 1         | 0.65%   |
| Toshiba TECRA R850                         | 1         | 0.65%   |
| Toshiba Satellite C660                     | 1         | 0.65%   |
| Star Labs StarBook                         | 1         | 0.65%   |
| Sony VPCEH2C5E                             | 1         | 0.65%   |
| Sony SVF1521O4E                            | 1         | 0.65%   |
| SHENZHEN YOUDISI E-COMMERCE A8S PRO        | 1         | 0.65%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.65%   |
| Razer Blade Stealth                        | 1         | 0.65%   |
| PCBOX Kant                                 | 1         | 0.65%   |
| MSI PE70 6QE                               | 1         | 0.65%   |
| MSI GT72 2QE                               | 1         | 0.65%   |
| MSI GE62VR 6RF                             | 1         | 0.65%   |
| MSI CX61 2PC                               | 1         | 0.65%   |
| Medion E6217                               | 1         | 0.65%   |
| Medion E15301                              | 1         | 0.65%   |
| Lenovo V14 G2 ITL 82KA                     | 1         | 0.65%   |
| Lenovo ThinkPad X240 20AMS0XP0S            | 1         | 0.65%   |
| Lenovo ThinkPad X230 23259S9               | 1         | 0.65%   |
| Lenovo ThinkPad X230 23254W5               | 1         | 0.65%   |
| Lenovo ThinkPad X201 Tablet 2985DMG        | 1         | 0.65%   |
| Lenovo ThinkPad X13 Gen 1 20T3S3SH0U       | 1         | 0.65%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW   | 1         | 0.65%   |
| Lenovo ThinkPad T495 20NKS01W02            | 1         | 0.65%   |
| Lenovo ThinkPad T470 20JNS08H00            | 1         | 0.65%   |
| Lenovo ThinkPad T460 20FMS08H00            | 1         | 0.65%   |
| Lenovo ThinkPad T440p 20AWS38H0G           | 1         | 0.65%   |
| Lenovo ThinkPad T430 2349OB6               | 1         | 0.65%   |
| Lenovo ThinkPad T400s 2808D9G              | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 16        | 10.32%  |
| Dell Latitude                   | 8         | 5.16%   |
| Acer Aspire                     | 7         | 4.52%   |
| Lenovo IdeaPad                  | 6         | 3.87%   |
| HP Pavilion                     | 6         | 3.87%   |
| HP ProBook                      | 5         | 3.23%   |
| HP Laptop                       | 5         | 3.23%   |
| ASUS VivoBook                   | 5         | 3.23%   |
| Apple MacBookPro11              | 5         | 3.23%   |
| ASUS ZenBook                    | 4         | 2.58%   |
| Apple MacBookPro8               | 4         | 2.58%   |
| HP 255                          | 3         | 1.94%   |
| Fujitsu LIFEBOOK                | 3         | 1.94%   |
| Apple MacBookPro9               | 3         | 1.94%   |
| Apple MacBookPro5               | 3         | 1.94%   |
| Toshiba TECRA                   | 2         | 1.29%   |
| Lenovo Legion                   | 2         | 1.29%   |
| HUAWEI BOD-WXX9                 | 2         | 1.29%   |
| HP EliteBook                    | 2         | 1.29%   |
| Dell XPS                        | 2         | 1.29%   |
| Dell Inspiron                   | 2         | 1.29%   |
| Apple MacBookAir7               | 2         | 1.29%   |
| Apple MacBookAir6               | 2         | 1.29%   |
| Apple MacBookAir3               | 2         | 1.29%   |
| Toshiba Satellite               | 1         | 0.65%   |
| Star Labs StarBook              | 1         | 0.65%   |
| Sony VPCEH2C5E                  | 1         | 0.65%   |
| Sony SVF1521O4E                 | 1         | 0.65%   |
| SHENZHEN YOUDISI E-COMMERCE A8S | 1         | 0.65%   |
| Samsung 300E4A                  | 1         | 0.65%   |
| Razer Blade                     | 1         | 0.65%   |
| PCBOX Kant                      | 1         | 0.65%   |
| MSI PE70                        | 1         | 0.65%   |
| MSI GT72                        | 1         | 0.65%   |
| MSI GE62VR                      | 1         | 0.65%   |
| MSI CX61                        | 1         | 0.65%   |
| Medion E6217                    | 1         | 0.65%   |
| Medion E15301                   | 1         | 0.65%   |
| Lenovo V14                      | 1         | 0.65%   |
| Lenovo ThinkBook                | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 18        | 11.61%  |
| 2020 | 16        | 10.32%  |
| 2012 | 14        | 9.03%   |
| 2019 | 13        | 8.39%   |
| 2016 | 11        | 7.1%    |
| 2014 | 10        | 6.45%   |
| 2013 | 10        | 6.45%   |
| 2010 | 9         | 5.81%   |
| 2022 | 8         | 5.16%   |
| 2018 | 8         | 5.16%   |
| 2011 | 8         | 5.16%   |
| 2009 | 7         | 4.52%   |
| 2017 | 6         | 3.87%   |
| 2015 | 6         | 3.87%   |
| 2008 | 6         | 3.87%   |
| 2023 | 3         | 1.94%   |
| 2007 | 2         | 1.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 155       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 149       | 96.13%  |
| Enabled  | 6         | 3.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 152       | 98.06%  |
| Yes  | 3         | 1.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 50        | 32.26%  |
| 3.01-4.0    | 33        | 21.29%  |
| 16.01-24.0  | 30        | 19.35%  |
| 8.01-16.0   | 30        | 19.35%  |
| 32.01-64.0  | 7         | 4.52%   |
| 64.01-256.0 | 2         | 1.29%   |
| 1.01-2.0    | 2         | 1.29%   |
| 2.01-3.0    | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 70        | 42.94%  |
| 1.01-2.0  | 38        | 23.31%  |
| 3.01-4.0  | 32        | 19.63%  |
| 4.01-8.0  | 16        | 9.82%   |
| 8.01-16.0 | 4         | 2.45%   |
| 0.51-1.0  | 3         | 1.84%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 125       | 80.13%  |
| 2      | 29        | 18.59%  |
| 4      | 1         | 0.64%   |
| 3      | 1         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 105       | 67.74%  |
| Yes       | 50        | 32.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 76.13%  |
| No        | 37        | 23.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 98.71%  |
| No        | 2         | 1.29%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 89.03%  |
| No        | 17        | 10.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 29        | 18.59%  |
| Germany      | 25        | 16.03%  |
| Russia       | 13        | 8.33%   |
| UK           | 6         | 3.85%   |
| Poland       | 6         | 3.85%   |
| France       | 6         | 3.85%   |
| Spain        | 5         | 3.21%   |
| India        | 4         | 2.56%   |
| Brazil       | 4         | 2.56%   |
| Australia    | 4         | 2.56%   |
| Portugal     | 3         | 1.92%   |
| Norway       | 3         | 1.92%   |
| Netherlands  | 3         | 1.92%   |
| Italy        | 3         | 1.92%   |
| Indonesia    | 3         | 1.92%   |
| Austria      | 3         | 1.92%   |
| Thailand     | 2         | 1.28%   |
| Sweden       | 2         | 1.28%   |
| Puerto Rico  | 2         | 1.28%   |
| Mexico       | 2         | 1.28%   |
| Israel       | 2         | 1.28%   |
| Greece       | 2         | 1.28%   |
| Colombia     | 2         | 1.28%   |
| Canada       | 2         | 1.28%   |
| Argentina    | 2         | 1.28%   |
| Turkey       | 1         | 0.64%   |
| Tunisia      | 1         | 0.64%   |
| Switzerland  | 1         | 0.64%   |
| South Africa | 1         | 0.64%   |
| Saudi Arabia | 1         | 0.64%   |
| Kazakhstan   | 1         | 0.64%   |
| Ireland      | 1         | 0.64%   |
| Hungary      | 1         | 0.64%   |
| Georgia      | 1         | 0.64%   |
| Egypt        | 1         | 0.64%   |
| Ecuador      | 1         | 0.64%   |
| Denmark      | 1         | 0.64%   |
| Cyprus       | 1         | 0.64%   |
| China        | 1         | 0.64%   |
| Chile        | 1         | 0.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 4         | 2.5%    |
| Vienna                  | 3         | 1.88%   |
| Berlin                  | 3         | 1.88%   |
| Warsaw                  | 2         | 1.25%   |
| Stuttgart               | 2         | 1.25%   |
| Novosibirsk             | 2         | 1.25%   |
| Monza                   | 2         | 1.25%   |
| Melbourne               | 2         | 1.25%   |
| Madrid                  | 2         | 1.25%   |
| Los Angeles             | 2         | 1.25%   |
| Jakarta                 | 2         | 1.25%   |
| Delhi                   | 2         | 1.25%   |
| Córdoba                | 2         | 1.25%   |
| Cologne                 | 2         | 1.25%   |
| Bangkok                 | 2         | 1.25%   |
| Zhuantang               | 1         | 0.63%   |
| Yekaterinburg           | 1         | 0.63%   |
| Wouldham                | 1         | 0.63%   |
| Worcestershire          | 1         | 0.63%   |
| Wilsdruff               | 1         | 0.63%   |
| Wiesbaden               | 1         | 0.63%   |
| Villefranche-sur-Saône | 1         | 0.63%   |
| Vigo                    | 1         | 0.63%   |
| Twickenham              | 1         | 0.63%   |
| Tuam                    | 1         | 0.63%   |
| Tromsø                 | 1         | 0.63%   |
| Troisdorf               | 1         | 0.63%   |
| Torres Vedras           | 1         | 0.63%   |
| Tirana                  | 1         | 0.63%   |
| Tel Aviv                | 1         | 0.63%   |
| Tbilisi                 | 1         | 0.63%   |
| Sydney                  | 1         | 0.63%   |
| Stockholm               | 1         | 0.63%   |
| St Petersburg           | 1         | 0.63%   |
| Spaichingen             | 1         | 0.63%   |
| Sorum                   | 1         | 0.63%   |
| Slavyansk-na-Kubani     | 1         | 0.63%   |
| Sheffield               | 1         | 0.63%   |
| Sfax                    | 1         | 0.63%   |
| Sarasota                | 1         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 26        | 27     | 13.76%  |
| SanDisk                        | 17        | 18     | 8.99%   |
| WDC                            | 13        | 14     | 6.88%   |
| Toshiba                        | 12        | 15     | 6.35%   |
| Apple                          | 12        | 12     | 6.35%   |
| Seagate                        | 11        | 12     | 5.82%   |
| Crucial                        | 11        | 12     | 5.82%   |
| Unknown                        | 8         | 9      | 4.23%   |
| Kingston                       | 7         | 9      | 3.7%    |
| Intel                          | 6         | 7      | 3.17%   |
| SK hynix                       | 4         | 5      | 2.12%   |
| Micron Technology              | 4         | 4      | 2.12%   |
| Hitachi                        | 4         | 4      | 2.12%   |
| HGST                           | 4         | 5      | 2.12%   |
| China                          | 4         | 4      | 2.12%   |
| Phison Electronics             | 3         | 3      | 1.59%   |
| KIOXIA                         | 3         | 5      | 1.59%   |
| Kingston Technology Company    | 3         | 3      | 1.59%   |
| Intenso                        | 3         | 4      | 1.59%   |
| JMicron Technology             | 2         | 2      | 1.06%   |
| BIWIN                          | 2         | 2      | 1.06%   |
| Unknown                        | 2         | 2      | 1.06%   |
| VISIPRO                        | 1         | 1      | 0.53%   |
| USB30                          | 1         | 1      | 0.53%   |
| USB 3.0                        | 1         | 1      | 0.53%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.53%   |
| Union Memory                   | 1         | 2      | 0.53%   |
| Transcend                      | 1         | 1      | 0.53%   |
| T-FORCE                        | 1         | 1      | 0.53%   |
| Star Drive                     | 1         | 1      | 0.53%   |
| SPCC                           | 1         | 1      | 0.53%   |
| Solid State Storage Technology | 1         | 1      | 0.53%   |
| Solid State Storage            | 1         | 1      | 0.53%   |
| Silicon Motion                 | 1         | 1      | 0.53%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.53%   |
| Realtek Semiconductor          | 1         | 2      | 0.53%   |
| PNY                            | 1         | 1      | 0.53%   |
| Phison                         | 1         | 1      | 0.53%   |
| OWC                            | 1         | 1      | 0.53%   |
| LITEON                         | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 3         | 1.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 3         | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3         | 1.57%   |
| Phison E12 NVMe Controller 480GB                     | 3         | 1.57%   |
| Apple SSD SD0128F 121GB                              | 3         | 1.57%   |
| Unknown MMC Card  7GB                                | 2         | 1.05%   |
| Unknown MMC Card  32GB                               | 2         | 1.05%   |
| Toshiba MK5065GSXF 500GB                             | 2         | 1.05%   |
| Seagate Expansion 1TB                                | 2         | 1.05%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 2         | 1.05%   |
| SanDisk SDSSDA240G 240GB                             | 2         | 1.05%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD                 | 2         | 1.05%   |
| Kingston Company SNV2S1000G 1TB                      | 2         | 1.05%   |
| Kingston SA400S37240G 240GB SSD                      | 2         | 1.05%   |
| HGST HTS721010A9E630 1TB                             | 2         | 1.05%   |
| Crucial CT275MX300SSD1 275GB                         | 2         | 1.05%   |
| Crucial CT250MX500SSD1 250GB                         | 2         | 1.05%   |
| Crucial CT240BX500SSD1 240GB                         | 2         | 1.05%   |
| Crucial CT1000MX500SSD1 1TB                          | 2         | 1.05%   |
| Apple SSD SM0512F 500GB                              | 2         | 1.05%   |
| Apple SSD SM0256F 256GB                              | 2         | 1.05%   |
| Unknown                                              | 2         | 1.05%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 1         | 0.52%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 1         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1         | 0.52%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                       | 1         | 0.52%   |
| WDC WD5000LPVX-80V0TT0 500GB                         | 1         | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB                         | 1         | 0.52%   |
| WDC WD10SPZX-24Z10T0 1TB                             | 1         | 0.52%   |
| WDC WD10SPCX-08S8TT0 1TB                             | 1         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 1         | 0.52%   |
| WDC WD Green 2.5 1000GB SSD                          | 1         | 0.52%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                 | 1         | 0.52%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB                 | 1         | 0.52%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                 | 1         | 0.52%   |
| VISIPRO SSD 256GB                                    | 1         | 0.52%   |
| USB30 Disk 240GB                                     | 1         | 0.52%   |
| USB 3.0 Device 250GB                                 | 1         | 0.52%   |
| Unknown SE64G  64GB                                  | 1         | 0.52%   |
| Unknown MMC Card  64GB                               | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 10        | 11     | 30.3%   |
| Toshiba            | 7         | 8      | 21.21%  |
| WDC                | 5         | 5      | 15.15%  |
| Hitachi            | 4         | 4      | 12.12%  |
| HGST               | 4         | 5      | 12.12%  |
| JMicron Technology | 1         | 1      | 3.03%   |
| Fujitsu            | 1         | 1      | 3.03%   |
| Apple              | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 11        | 12     | 13.92%  |
| Apple               | 11        | 11     | 13.92%  |
| Samsung Electronics | 10        | 11     | 12.66%  |
| SanDisk             | 9         | 9      | 11.39%  |
| Kingston            | 6         | 8      | 7.59%   |
| WDC                 | 5         | 6      | 6.33%   |
| Toshiba             | 4         | 6      | 5.06%   |
| China               | 4         | 4      | 5.06%   |
| Intenso             | 2         | 3      | 2.53%   |
| VISIPRO             | 1         | 1      | 1.27%   |
| USB30               | 1         | 1      | 1.27%   |
| Transcend           | 1         | 1      | 1.27%   |
| SPCC                | 1         | 1      | 1.27%   |
| SK hynix            | 1         | 1      | 1.27%   |
| PNY                 | 1         | 1      | 1.27%   |
| Phison              | 1         | 1      | 1.27%   |
| OWC                 | 1         | 1      | 1.27%   |
| Micron Technology   | 1         | 1      | 1.27%   |
| LITEON              | 1         | 1      | 1.27%   |
| KUU                 | 1         | 1      | 1.27%   |
| KingDian            | 1         | 1      | 1.27%   |
| Intel               | 1         | 1      | 1.27%   |
| Inland              | 1         | 1      | 1.27%   |
| BIWIN               | 1         | 1      | 1.27%   |
| ASMT                | 1         | 1      | 1.27%   |
| Apacer              | 1         | 1      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 74        | 87     | 41.34%  |
| NVMe    | 57        | 67     | 31.84%  |
| HDD     | 31        | 36     | 17.32%  |
| MMC     | 9         | 10     | 5.03%   |
| Unknown | 8         | 8      | 4.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 119    | 56.74%  |
| NVMe | 57        | 67     | 32.02%  |
| SAS  | 11        | 12     | 6.18%   |
| MMC  | 9         | 10     | 5.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 91     | 75%     |
| 0.51-1.0   | 21        | 26     | 19.44%  |
| 1.01-2.0   | 6         | 6      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 77        | 49.04%  |
| 251-500        | 40        | 25.48%  |
| 501-1000       | 20        | 12.74%  |
| 51-100         | 12        | 7.64%   |
| 2001-3000      | 3         | 1.91%   |
| 1001-2000      | 2         | 1.27%   |
| 1-20           | 2         | 1.27%   |
| More than 3000 | 1         | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 82        | 51.25%  |
| 21-50          | 42        | 26.25%  |
| 101-250        | 15        | 9.38%   |
| 51-100         | 13        | 8.13%   |
| 251-500        | 4         | 2.5%    |
| 1001-2000      | 2         | 1.25%   |
| More than 3000 | 1         | 0.63%   |
| 501-1000       | 1         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 138       | 184    | 86.25%  |
| Works    | 22        | 24     | 13.75%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 105       | 56.76%  |
| Samsung Electronics            | 21        | 11.35%  |
| AMD                            | 12        | 6.49%   |
| SanDisk                        | 11        | 5.95%   |
| Nvidia                         | 6         | 3.24%   |
| Phison Electronics             | 4         | 2.16%   |
| Kingston Technology Company    | 4         | 2.16%   |
| SK hynix                       | 3         | 1.62%   |
| Micron Technology              | 3         | 1.62%   |
| Marvell Technology Group       | 3         | 1.62%   |
| KIOXIA                         | 3         | 1.62%   |
| Union Memory (Shenzhen)        | 2         | 1.08%   |
| Solid State Storage Technology | 2         | 1.08%   |
| Toshiba America Info Systems   | 1         | 0.54%   |
| Silicon Motion                 | 1         | 0.54%   |
| Shenzhen Longsys Electronics   | 1         | 0.54%   |
| Realtek Semiconductor          | 1         | 0.54%   |
| INNOGRIT                       | 1         | 0.54%   |
| Biwin Storage Technology       | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 7.65%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 5.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 5.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 4.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 4.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 3.57%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 3.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 2.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 2.55%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 4         | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.04%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 2.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 2.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 2.04%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3         | 1.53%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.53%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 3         | 1.53%   |
| Intel SSD 660P Series                                                          | 3         | 1.53%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.02%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.02%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 1.02%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 1.02%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 1.02%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 1.02%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 2         | 1.02%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 2         | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 1.02%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                          | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 112       | 58.33%  |
| NVMe | 57        | 29.69%  |
| RAID | 19        | 9.9%    |
| IDE  | 4         | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 133       | 85.81%  |
| AMD    | 22        | 14.19%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 7         | 4.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 5         | 3.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 4         | 2.58%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 4         | 2.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 3         | 1.94%   |
| Intel Core i5-2435M CPU @ 2.40GHz               | 3         | 1.94%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 3         | 1.94%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 2         | 1.29%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 1.29%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 1.29%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz              | 2         | 1.29%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 2         | 1.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.29%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 2         | 1.29%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 1.29%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 1.29%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 1.29%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 2         | 1.29%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz            | 2         | 1.29%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 1.29%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.29%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.29%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 1.29%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz     | 1         | 0.65%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 0.65%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.65%   |
| Intel Pentium CPU 6805 @ 1.10GHz                | 1         | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.65%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 0.65%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 0.65%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 0.65%   |
| Intel Core i7-5650U CPU @ 2.20GHz               | 1         | 0.65%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.65%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz              | 1         | 0.65%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz              | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 44        | 28.39%  |
| Intel Core i7           | 30        | 19.35%  |
| Other                   | 21        | 13.55%  |
| Intel Core i3           | 11        | 7.1%    |
| Intel Core 2 Duo        | 11        | 7.1%    |
| Intel Celeron           | 10        | 6.45%   |
| AMD Ryzen 7             | 6         | 3.87%   |
| AMD Ryzen 5             | 5         | 3.23%   |
| Intel Pentium           | 3         | 1.94%   |
| Intel Pentium Silver    | 2         | 1.29%   |
| AMD Ryzen 3             | 2         | 1.29%   |
| AMD Athlon              | 2         | 1.29%   |
| AMD A4                  | 2         | 1.29%   |
| AMD A12                 | 2         | 1.29%   |
| Intel Pentium Dual-Core | 1         | 0.65%   |
| AMD Ryzen 5 PRO         | 1         | 0.65%   |
| AMD A8                  | 1         | 0.65%   |
| AMD A6                  | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 85        | 54.84%  |
| 4      | 49        | 31.61%  |
| 8      | 9         | 5.81%   |
| 6      | 5         | 3.23%   |
| 10     | 2         | 1.29%   |
| 1      | 2         | 1.29%   |
| 14     | 1         | 0.65%   |
| 12     | 1         | 0.65%   |
| 5      | 1         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 155       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 122       | 78.71%  |
| 1      | 33        | 21.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 155       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 128       | 81.53%  |
| 0x806ec    | 3         | 1.91%   |
| 0x806c1    | 3         | 1.91%   |
| 0x906a4    | 2         | 1.27%   |
| 0x806d1    | 2         | 1.27%   |
| 0x706e5    | 2         | 1.27%   |
| 0x706a8    | 2         | 1.27%   |
| 0x206a7    | 2         | 1.27%   |
| 0x0a50000c | 2         | 1.27%   |
| 0x906e9    | 1         | 0.64%   |
| 0x906a3    | 1         | 0.64%   |
| 0x806eb    | 1         | 0.64%   |
| 0x806ea    | 1         | 0.64%   |
| 0x40661    | 1         | 0.64%   |
| 0x40651    | 1         | 0.64%   |
| 0x1067a    | 1         | 0.64%   |
| 0x10676    | 1         | 0.64%   |
| 0x0a50000d | 1         | 0.64%   |
| 0x08600106 | 1         | 0.64%   |
| 0x0600611a | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 19        | 12.26%  |
| Haswell          | 19        | 12.26%  |
| TigerLake        | 14        | 9.03%   |
| IvyBridge        | 14        | 9.03%   |
| Skylake          | 12        | 7.74%   |
| Penryn           | 12        | 7.74%   |
| SandyBridge      | 10        | 6.45%   |
| Goldmont plus    | 8         | 5.16%   |
| Unknown          | 7         | 4.52%   |
| Zen+             | 6         | 3.87%   |
| Westmere         | 6         | 3.87%   |
| Broadwell        | 5         | 3.23%   |
| IceLake          | 4         | 2.58%   |
| Zen 3            | 3         | 1.94%   |
| Zen 2            | 3         | 1.94%   |
| Silvermont       | 3         | 1.94%   |
| Excavator        | 3         | 1.94%   |
| Alderlake Hybrid | 3         | 1.94%   |
| Puma             | 2         | 1.29%   |
| Piledriver       | 1         | 0.65%   |
| Core             | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 121       | 64.71%  |
| Nvidia | 37        | 19.79%  |
| AMD    | 29        | 15.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 14        | 7.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 10        | 5.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 9         | 4.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 9         | 4.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 8         | 4.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 6         | 3.14%   |
| Intel Core Processor Integrated Graphics Controller                                   | 6         | 3.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 3.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 2.62%   |
| Nvidia C79 [GeForce 9400M]                                                            | 4         | 2.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 2.09%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 4         | 2.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 2.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 4         | 2.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 2.09%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 1.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 1.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 1.57%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 3         | 1.57%   |
| Intel HD Graphics 620                                                                 | 3         | 1.57%   |
| Intel HD Graphics 530                                                                 | 3         | 1.57%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                           | 3         | 1.57%   |
| AMD Lucienne                                                                          | 3         | 1.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 3         | 1.57%   |
| Nvidia MCP89 [GeForce 320M]                                                           | 2         | 1.05%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 2         | 1.05%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 2         | 1.05%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 1.05%   |
| Intel UHD Graphics 620                                                                | 2         | 1.05%   |
| Intel HD Graphics 630                                                                 | 2         | 1.05%   |
| Intel HD Graphics 6000                                                                | 2         | 1.05%   |
| Intel HD Graphics 5500                                                                | 2         | 1.05%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 2         | 1.05%   |
| Intel Crystal Well Integrated Graphics Controller                                     | 2         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 1.05%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 2         | 1.05%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 2         | 1.05%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.05%   |
| Nvidia TU117M [GeForce MX450]                                                         | 1         | 0.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 90        | 58.06%  |
| Intel + Nvidia | 25        | 16.13%  |
| 1 x AMD        | 20        | 12.9%   |
| 1 x Nvidia     | 9         | 5.81%   |
| Intel + AMD    | 5         | 3.23%   |
| 2 x AMD        | 2         | 1.29%   |
| AMD + Nvidia   | 2         | 1.29%   |
| Other          | 1         | 0.65%   |
| 2 x Nvidia     | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 146       | 94.19%  |
| Proprietary | 6         | 3.87%   |
| Unknown     | 3         | 1.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 147       | 94.84%  |
| 1.01-2.0   | 3         | 1.94%   |
| 0.01-0.5   | 3         | 1.94%   |
| 3.01-4.0   | 2         | 1.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 31        | 18.67%  |
| LG Display              | 26        | 15.66%  |
| Apple                   | 26        | 15.66%  |
| BOE                     | 21        | 12.65%  |
| Chimei Innolux          | 18        | 10.84%  |
| Samsung Electronics     | 10        | 6.02%   |
| Sharp                   | 5         | 3.01%   |
| Dell                    | 4         | 2.41%   |
| PANDA                   | 3         | 1.81%   |
| Lenovo                  | 3         | 1.81%   |
| Goldstar                | 3         | 1.81%   |
| Chi Mei Optoelectronics | 2         | 1.2%    |
| BenQ                    | 2         | 1.2%    |
| XCX                     | 1         | 0.6%    |
| Toshiba                 | 1         | 0.6%    |
| RGT                     | 1         | 0.6%    |
| Philips                 | 1         | 0.6%    |
| Panasonic               | 1         | 0.6%    |
| Mi                      | 1         | 0.6%    |
| LG Philips              | 1         | 0.6%    |
| InfoVision              | 1         | 0.6%    |
| Hewlett-Packard         | 1         | 0.6%    |
| CSO                     | 1         | 0.6%    |
| CPT                     | 1         | 0.6%    |
| Cisco                   | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 3         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 3         | 1.79%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                   | 3         | 1.79%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 2         | 1.19%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch           | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch       | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch       | 2         | 1.19%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                  | 2         | 1.19%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                  | 2         | 1.19%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                   | 2         | 1.19%   |
| Apple LCD Monitor Color LCD 2880x1800                                  | 2         | 1.19%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                 | 2         | 1.19%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                 | 2         | 1.19%   |
| Apple Color LCD APPA019 2880x1800 331x207mm 15.4-inch                  | 2         | 1.19%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 2         | 1.19%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                   | 2         | 1.19%   |
| XCX LCD Monitor XCX0844 1366x768 256x144mm 11.6-inch                   | 1         | 0.6%    |
| Toshiba ScreenXpert TSB8888 1080x2160                                  | 1         | 0.6%    |
| Sharp LCD Monitor SHP151C 1920x1080 344x194mm 15.5-inch                | 1         | 0.6%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.6%    |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                | 1         | 0.6%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.6%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 1         | 0.6%    |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1         | 0.6%    |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                  | 1         | 0.6%    |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1         | 0.6%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 1         | 0.6%    |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch                | 1         | 0.6%    |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 0.6%    |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 1         | 0.6%    |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                       | 1         | 0.6%    |
| LG Philips LCD Monitor LPLB900 1280x800 330x210mm 15.4-inch            | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 71        | 45.22%  |
| 1366x768 (WXGA)   | 43        | 27.39%  |
| 1280x800 (WXGA)   | 13        | 8.28%   |
| 1440x900 (WXGA+)  | 7         | 4.46%   |
| 2880x1800         | 6         | 3.82%   |
| 3840x2160 (4K)    | 4         | 2.55%   |
| 1600x900 (HD+)    | 4         | 2.55%   |
| 1920x1200 (WUXGA) | 3         | 1.91%   |
| 2560x1600         | 2         | 1.27%   |
| 3840x2400         | 1         | 0.64%   |
| 3440x1440         | 1         | 0.64%   |
| 2560x1440 (QHD)   | 1         | 0.64%   |
| 1280x1024 (SXGA)  | 1         | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 72        | 42.86%  |
| 13      | 32        | 19.05%  |
| 14      | 19        | 11.31%  |
| 17      | 12        | 7.14%   |
| 27      | 5         | 2.98%   |
| 12      | 5         | 2.98%   |
| 11      | 5         | 2.98%   |
| 24      | 3         | 1.79%   |
| 21      | 3         | 1.79%   |
| 31      | 2         | 1.19%   |
| Unknown | 2         | 1.19%   |
| 86      | 1         | 0.6%    |
| 84      | 1         | 0.6%    |
| 65      | 1         | 0.6%    |
| 60      | 1         | 0.6%    |
| 34      | 1         | 0.6%    |
| 19      | 1         | 0.6%    |
| 18      | 1         | 0.6%    |
| 16      | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 97        | 57.74%  |
| 201-300     | 35        | 20.83%  |
| 351-400     | 15        | 8.93%   |
| 501-600     | 8         | 4.76%   |
| 401-500     | 4         | 2.38%   |
| 1001-1500   | 3         | 1.79%   |
| 601-700     | 2         | 1.19%   |
| Unknown     | 2         | 1.19%   |
| 701-800     | 1         | 0.6%    |
| 1501-2000   | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 118       | 76.13%  |
| 16/10   | 31        | 20%     |
| Unknown | 2         | 1.29%   |
| 5/4     | 1         | 0.65%   |
| 3/2     | 1         | 0.65%   |
| 21/9    | 1         | 0.65%   |
| 0.56    | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 73        | 43.71%  |
| 81-90          | 38        | 22.75%  |
| 71-80          | 13        | 7.78%   |
| 121-130        | 9         | 5.39%   |
| 61-70          | 5         | 2.99%   |
| 51-60          | 5         | 2.99%   |
| 301-350        | 5         | 2.99%   |
| More than 1000 | 4         | 2.4%    |
| 201-250        | 4         | 2.4%    |
| 351-500        | 3         | 1.8%    |
| 131-140        | 3         | 1.8%    |
| Unknown        | 2         | 1.2%    |
| 251-300        | 1         | 0.6%    |
| 151-200        | 1         | 0.6%    |
| 141-150        | 1         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 80        | 48.19%  |
| 101-120       | 51        | 30.72%  |
| 51-100        | 15        | 9.04%   |
| 161-240       | 13        | 7.83%   |
| 1-50          | 3         | 1.81%   |
| More than 240 | 2         | 1.2%    |
| Unknown       | 2         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 134       | 86.45%  |
| 2     | 17        | 10.97%  |
| 0     | 3         | 1.94%   |
| 3     | 1         | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 69        | 29.49%  |
| Intel                             | 69        | 29.49%  |
| Broadcom                          | 31        | 13.25%  |
| Qualcomm Atheros                  | 25        | 10.68%  |
| Broadcom Limited                  | 7         | 2.99%   |
| Ralink Technology                 | 4         | 1.71%   |
| Nvidia                            | 4         | 1.71%   |
| Dell                              | 3         | 1.28%   |
| ASIX Electronics                  | 3         | 1.28%   |
| Samsung Electronics               | 2         | 0.85%   |
| Qualcomm                          | 2         | 0.85%   |
| NetGear                           | 2         | 0.85%   |
| Marvell Technology Group          | 2         | 0.85%   |
| Huawei Technologies               | 2         | 0.85%   |
| Ericsson Business Mobile Networks | 2         | 0.85%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.43%   |
| Xiaomi                            | 1         | 0.43%   |
| TP-Link                           | 1         | 0.43%   |
| Sierra Wireless                   | 1         | 0.43%   |
| Ralink                            | 1         | 0.43%   |
| Motorola PCS                      | 1         | 0.43%   |
| MediaTek                          | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 38        | 12.97%  |
| Intel Wi-Fi 6 AX201                                                    | 12        | 4.1%    |
| Intel Wireless 8260                                                    | 11        | 3.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 10        | 3.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 2.73%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 2.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 7         | 2.39%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 7         | 2.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 1.71%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 5         | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 1.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 1.37%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 1.37%   |
| Intel Wireless 7260                                                    | 4         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1.37%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 4         | 1.37%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 4         | 1.37%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 4         | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 1.02%   |
| Intel Wireless 7265                                                    | 3         | 1.02%   |
| Intel Wireless 3165                                                    | 3         | 1.02%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.68%   |
| Realtek 802.11n WLAN Adapter                                           | 2         | 0.68%   |
| Realtek 802.11ac NIC                                                   | 2         | 0.68%   |
| Ralink RT5370 Wireless Adapter                                         | 2         | 0.68%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 2         | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 67        | 40.85%  |
| Realtek Semiconductor | 30        | 18.29%  |
| Broadcom              | 30        | 18.29%  |
| Qualcomm Atheros      | 19        | 11.59%  |
| Broadcom Limited      | 6         | 3.66%   |
| Ralink Technology     | 4         | 2.44%   |
| Qualcomm              | 2         | 1.22%   |
| Dell                  | 2         | 1.22%   |
| TP-Link               | 1         | 0.61%   |
| Sierra Wireless       | 1         | 0.61%   |
| Ralink                | 1         | 0.61%   |
| NetGear               | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 12        | 7.23%   |
| Intel Wireless 8260                                                  | 11        | 6.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 10        | 6.02%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 7         | 4.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 3.01%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 5         | 3.01%   |
| Broadcom BCM43142 802.11b/g/n                                        | 5         | 3.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 4         | 2.41%   |
| Intel Wireless 7260                                                  | 4         | 2.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 2.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 4         | 2.41%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 4         | 2.41%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 4         | 2.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 4         | 2.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 3         | 1.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 1.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 1.81%   |
| Intel Wireless 7265                                                  | 3         | 1.81%   |
| Intel Wireless 3165                                                  | 3         | 1.81%   |
| Intel Wi-Fi 6 AX200                                                  | 3         | 1.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2         | 1.2%    |
| Realtek 802.11n WLAN Adapter                                         | 2         | 1.2%    |
| Realtek 802.11ac NIC                                                 | 2         | 1.2%    |
| Ralink RT5370 Wireless Adapter                                       | 2         | 1.2%    |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 2         | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 1.2%    |
| Intel Wireless 8265 / 8275                                           | 2         | 1.2%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2         | 1.2%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2         | 1.2%    |
| Intel Ultimate N WiFi Link 5300                                      | 2         | 1.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 1.2%    |
| Intel Centrino Wireless-N 2230                                       | 2         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 2         | 1.2%    |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                 | 2         | 1.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1         | 0.6%    |
| Sierra Wireless EM7455                                               | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 56        | 45.16%  |
| Intel                      | 27        | 21.77%  |
| Qualcomm Atheros           | 11        | 8.87%   |
| Broadcom                   | 11        | 8.87%   |
| Nvidia                     | 4         | 3.23%   |
| ASIX Electronics           | 3         | 2.42%   |
| Samsung Electronics        | 2         | 1.61%   |
| Marvell Technology Group   | 2         | 1.61%   |
| Huawei Technologies        | 2         | 1.61%   |
| ZTE WCDMA Technologies MSM | 1         | 0.81%   |
| Xiaomi                     | 1         | 0.81%   |
| NetGear                    | 1         | 0.81%   |
| Motorola PCS               | 1         | 0.81%   |
| MediaTek                   | 1         | 0.81%   |
| Broadcom Limited           | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 38        | 30.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 6.45%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 5.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 7         | 5.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 4.03%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 3.23%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 1.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.61%   |
| Intel Ethernet Connection I219-V                                       | 2         | 1.61%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.61%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.61%   |
| ZTE WCDMA MSM Unisoc Phone                                             | 1         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.81%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.81%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.81%   |
| NetGear LB1120-100NAS                                                  | 1         | 0.81%   |
| Motorola PCS moto g play - 2023                                        | 1         | 0.81%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.81%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.81%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.81%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.81%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.81%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.81%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 0.81%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.81%   |
| Intel 82562GT 10/100 Network Connection                                | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 153       | 56.04%  |
| Ethernet | 117       | 42.86%  |
| Modem    | 3         | 1.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 75.95%  |
| Ethernet | 38        | 24.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 101       | 65.16%  |
| 1     | 51        | 32.9%   |
| 0     | 2         | 1.29%   |
| 3     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 113       | 72.44%  |
| Yes  | 43        | 27.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 42.75%  |
| Apple                           | 25        | 18.12%  |
| Realtek Semiconductor           | 19        | 13.77%  |
| Qualcomm Atheros Communications | 8         | 5.8%    |
| Foxconn / Hon Hai               | 6         | 4.35%   |
| Broadcom                        | 6         | 4.35%   |
| Lite-On Technology              | 5         | 3.62%   |
| IMC Networks                    | 5         | 3.62%   |
| Toshiba                         | 1         | 0.72%   |
| Ralink                          | 1         | 0.72%   |
| Hewlett-Packard                 | 1         | 0.72%   |
| Askey Computer                  | 1         | 0.72%   |
| Unknown                         | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 22        | 15.94%  |
| Apple Bluetooth Host Controller                    | 15        | 10.87%  |
| Intel AX201 Bluetooth                              | 14        | 10.14%  |
| Realtek  Bluetooth 4.2 Adapter                     | 10        | 7.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 10        | 7.25%   |
| Apple Bluetooth USB Host Controller                | 9         | 6.52%   |
| Realtek Bluetooth Radio                            | 5         | 3.62%   |
| Qualcomm Atheros  Bluetooth Device                 | 4         | 2.9%    |
| Realtek 802.11ac WLAN Adapter                      | 3         | 2.17%   |
| Lite-On Bluetooth Device                           | 3         | 2.17%   |
| Intel AX200 Bluetooth                              | 3         | 2.17%   |
| IMC Networks Bluetooth Radio                       | 3         | 2.17%   |
| Foxconn / Hon Hai Bluetooth Device                 | 3         | 2.17%   |
| Qualcomm Atheros AR3011 Bluetooth                  | 2         | 1.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 2         | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 2         | 1.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 2         | 1.45%   |
| Intel AX211 Bluetooth                              | 2         | 1.45%   |
| Intel AX210 Bluetooth                              | 2         | 1.45%   |
| Broadcom BCM43142A0 Bluetooth Device               | 2         | 1.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 2         | 1.45%   |
| Toshiba Bluetooth Device                           | 1         | 0.72%   |
| Realtek RTL8821A Bluetooth                         | 1         | 0.72%   |
| Ralink RT3290 Bluetooth                            | 1         | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 0.72%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device       | 1         | 0.72%   |
| IMC Networks Bluetooth                             | 1         | 0.72%   |
| IMC Networks BCM20702A0                            | 1         | 0.72%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 0.72%   |
| Foxconn / Hon Hai Wireless_Device                  | 1         | 0.72%   |
| Foxconn / Hon Hai BCM43142A0                       | 1         | 0.72%   |
| Foxconn / Hon Hai BCM20702A0                       | 1         | 0.72%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 0.72%   |
| Broadcom BCM2045B (BDC-2.1)                        | 1         | 0.72%   |
| Askey Bluetooth Device                             | 1         | 0.72%   |
| Apple Bluetooth HCI                                | 1         | 0.72%   |
| Unknown                                            | 1         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 127       | 68.28%  |
| AMD                    | 26        | 13.98%  |
| Nvidia                 | 22        | 11.83%  |
| Logitech               | 2         | 1.08%   |
| C-Media Electronics    | 2         | 1.08%   |
| Sony                   | 1         | 0.54%   |
| Realtek Semiconductor  | 1         | 0.54%   |
| Microsoft              | 1         | 0.54%   |
| Hewlett-Packard        | 1         | 0.54%   |
| GN Netcom              | 1         | 0.54%   |
| Generalplus Technology | 1         | 0.54%   |
| Dell                   | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 16        | 7.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 6.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 6.14%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 6.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 4.39%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 3.95%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 3.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 3.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 3.51%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 3.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 2.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.19%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.19%   |
| Nvidia MCP79 High Definition Audio                                         | 4         | 1.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.75%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.75%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.32%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.32%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.32%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.32%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.32%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.88%   |
| Intel Crystal Well HD Audio Controller                                     | 2         | 0.88%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.88%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 0.88%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 0.44%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.44%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 38.89%  |
| Micron Technology   | 9         | 25%     |
| SK hynix            | 6         | 16.67%  |
| Unknown (ABCD)      | 1         | 2.78%   |
| Ramaxel Technology  | 1         | 2.78%   |
| pqi                 | 1         | 2.78%   |
| GSkill              | 1         | 2.78%   |
| Elpida              | 1         | 2.78%   |
| Crucial             | 1         | 2.78%   |
| Unknown             | 1         | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 5.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 5.56%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 2.78%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.78%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.78%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 2.78%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 2.78%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.78%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.78%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 2.78%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 1         | 2.78%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 2.78%   |
| Samsung RAM M471B5273EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.78%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.78%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 1         | 2.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 2.78%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.78%   |
| Ramaxel RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 2.78%   |
| pqi RAM Module 2GB SODIMM DDR2 667MT/s                           | 1         | 2.78%   |
| Micron RAM MT53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 2.78%   |
| Micron RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 2.78%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 2.78%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.78%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 2.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.78%   |
| Micron RAM 16ATF4G64HZ-3G2E2 32GB SODIMM DDR4 3200MT/s           | 1         | 2.78%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 1         | 2.78%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 1         | 2.78%   |
| Unknown                                                          | 1         | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 18        | 56.25%  |
| DDR3   | 6         | 18.75%  |
| LPDDR4 | 5         | 15.63%  |
| LPDDR3 | 1         | 3.13%   |
| DDR5   | 1         | 3.13%   |
| DDR2   | 1         | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 75.76%  |
| Row Of Chips | 8         | 24.24%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 19        | 57.58%  |
| 4096  | 6         | 18.18%  |
| 16384 | 4         | 12.12%  |
| 2048  | 3         | 9.09%   |
| 32768 | 1         | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 11        | 33.33%  |
| 2667  | 7         | 21.21%  |
| 4267  | 4         | 12.12%  |
| 1600  | 4         | 12.12%  |
| 2400  | 2         | 6.06%   |
| 4800  | 1         | 3.03%   |
| 2133  | 1         | 3.03%   |
| 1333  | 1         | 3.03%   |
| 800   | 1         | 3.03%   |
| 667   | 1         | 3.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer | 1         | 100%    |

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
| Chicony Electronics                    | 25        | 17.86%  |
| Apple                                  | 19        | 13.57%  |
| Quanta                                 | 15        | 10.71%  |
| IMC Networks                           | 13        | 9.29%   |
| Realtek Semiconductor                  | 10        | 7.14%   |
| Microdia                               | 10        | 7.14%   |
| Bison Electronics                      | 9         | 6.43%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 5.71%   |
| Sunplus Innovation Technology          | 6         | 4.29%   |
| Luxvisions Innotech Limited            | 3         | 2.14%   |
| Syntek                                 | 2         | 1.43%   |
| SunplusIT                              | 2         | 1.43%   |
| Lite-On Technology                     | 2         | 1.43%   |
| Lenovo                                 | 2         | 1.43%   |
| Alcor Micro                            | 2         | 1.43%   |
| Y Media                                | 1         | 0.71%   |
| Suyin                                  | 1         | 0.71%   |
| Sunplus Technology                     | 1         | 0.71%   |
| Sonix Technology                       | 1         | 0.71%   |
| Silicon Motion                         | 1         | 0.71%   |
| Shine-optics                           | 1         | 0.71%   |
| Samsung Electronics                    | 1         | 0.71%   |
| Logitech                               | 1         | 0.71%   |
| Intel                                  | 1         | 0.71%   |
| Cubeternet                             | 1         | 0.71%   |
| Cisco Systems                          | 1         | 0.71%   |
| Acer                                   | 1         | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 7         | 4.96%   |
| Apple FaceTime HD Camera                         | 7         | 4.96%   |
| Microdia Integrated_Webcam_HD                    | 5         | 3.55%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR               | 5         | 3.55%   |
| Apple Built-in iSight                            | 5         | 3.55%   |
| Realtek Integrated_Webcam_HD                     | 4         | 2.84%   |
| IMC Networks Integrated Camera                   | 4         | 2.84%   |
| IMC Networks USB2.0 HD UVC WebCam                | 3         | 2.13%   |
| Bison Lenovo Integrated Webcam                   | 3         | 2.13%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 1.42%   |
| Sunplus Dell E5570 integrated webcam             | 2         | 1.42%   |
| Quanta USB2.0 HD UVC WebCam                      | 2         | 1.42%   |
| Quanta HP Wide Vision HD Camera                  | 2         | 1.42%   |
| Quanta HP TrueVision HD Camera                   | 2         | 1.42%   |
| Quanta HP HD Camera                              | 2         | 1.42%   |
| Quanta HD Webcam                                 | 2         | 1.42%   |
| Quanta HD Camera                                 | 2         | 1.42%   |
| Microdia Integrated Webcam                       | 2         | 1.42%   |
| Lite-On Integrated Camera                        | 2         | 1.42%   |
| IMC Networks HD Camera                           | 2         | 1.42%   |
| Chicony HP Webcam                                | 2         | 1.42%   |
| Chicony HP TrueVision HD Camera                  | 2         | 1.42%   |
| Chicony HP Truevision HD                         | 2         | 1.42%   |
| Chicony HD WebCam                                | 2         | 1.42%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.42%   |
| Bison Integrated Camera                          | 2         | 1.42%   |
| Apple FaceTime Camera                            | 2         | 1.42%   |
| Y Media USB Camera                               | 1         | 0.71%   |
| Syntek Lenovo EasyCamera                         | 1         | 0.71%   |
| Syntek EasyCamera                                | 1         | 0.71%   |
| Suyin HD Video WebCam                            | 1         | 0.71%   |
| SunplusIT USB camera                             | 1         | 0.71%   |
| SunplusIT HD Camera                              | 1         | 0.71%   |
| Sunplus 1.3M HD WebCam                           | 1         | 0.71%   |
| Sunplus MTD Camera                               | 1         | 0.71%   |
| Sunplus HD WebCam                                | 1         | 0.71%   |
| Sonix HP Webcam-101                              | 1         | 0.71%   |
| Silicon Motion WebCam SC-03FFL11939N             | 1         | 0.71%   |
| Shine-optics USB2.0 HD UVC WebCam                | 1         | 0.71%   |
| Samsung Galaxy series, misc. (MTP mode)          | 1         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 36.67%  |
| Shenzhen Goodix Technology | 7         | 23.33%  |
| Synaptics                  | 4         | 13.33%  |
| Elan Microelectronics      | 4         | 13.33%  |
| LighTuning Technology      | 2         | 6.67%   |
| Upek                       | 1         | 3.33%   |
| AuthenTec                  | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 10%     |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 6.67%   |
| Elan ELAN:ARM-M4                                                           | 2         | 6.67%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.33%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.33%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 3.33%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 3.33%   |
| LighTuning Fingerprint Reader                                              | 1         | 3.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.33%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 3.33%   |
| Elan ELAN:Fingerprint                                                      | 1         | 3.33%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 50%     |
| Upek        | 2         | 25%     |
| O2 Micro    | 1         | 12.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 25%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 92        | 59.35%  |
| 1     | 50        | 32.26%  |
| 2     | 11        | 7.1%    |
| 3     | 2         | 1.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 29        | 37.66%  |
| Multimedia controller | 14        | 18.18%  |
| Net/wireless          | 13        | 16.88%  |
| Graphics card         | 10        | 12.99%  |
| Chipcard              | 8         | 10.39%  |
| Storage               | 1         | 1.3%    |
| Net/ethernet          | 1         | 1.3%    |
| Bluetooth             | 1         | 1.3%    |

