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

Total: 231

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire 7715Z                | [3ee36053d6](https://linux-hardware.org/?probe=3ee36053d6) | Nov 29, 2025 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | [bb3561f31c](https://linux-hardware.org/?probe=bb3561f31c) | Feb 18, 2025 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | [5120c6795a](https://linux-hardware.org/?probe=5120c6795a) | Feb 18, 2025 |
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
| ASUSTek       | Vivobook Go E1504FA_E150... | [784f886357](https://linux-hardware.org/?probe=784f886357) | Jul 10, 2023 |
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
| ASUSTek       | Vivobook Go E1504FA_E150... | [01076d8e8b](https://linux-hardware.org/?probe=01076d8e8b) | May 30, 2023 |
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
| 5.15.0-58-generic    | 42        | 25.3%   |
| 5.19.0-41-generic    | 18        | 10.84%  |
| 5.19.0-35-generic    | 16        | 9.64%   |
| 6.2.0-26-generic     | 14        | 8.43%   |
| 5.19.0-46-generic    | 14        | 8.43%   |
| 5.19.0-32-generic    | 12        | 7.23%   |
| 5.19.0-38-generic    | 10        | 6.02%   |
| 5.19.0-43-generic    | 9         | 5.42%   |
| 6.2.0-31-generic     | 5         | 3.01%   |
| 6.2.0-32-generic     | 4         | 2.41%   |
| 5.19.0-50-generic    | 4         | 2.41%   |
| 5.19.0-40-generic    | 4         | 2.41%   |
| 5.15.0-60-generic    | 4         | 2.41%   |
| 5.19.0-45-generic    | 2         | 1.2%    |
| 5.19.0-42-generic    | 2         | 1.2%    |
| 6.2.7-060207-generic | 1         | 0.6%    |
| 6.1.9-060109-generic | 1         | 0.6%    |
| 6.1.6-060106-generic | 1         | 0.6%    |
| 6.1.0-1013-oem       | 1         | 0.6%    |
| 5.15.0-79-generic    | 1         | 0.6%    |
| 5.15.0-56-generic    | 1         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.0  | 86        | 53.42%  |
| 5.15.0  | 48        | 29.81%  |
| 6.2.0   | 23        | 14.29%  |
| 6.2.7   | 1         | 0.62%   |
| 6.1.9   | 1         | 0.62%   |
| 6.1.6   | 1         | 0.62%   |
| 6.1.0   | 1         | 0.62%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19    | 86        | 53.42%  |
| 5.15    | 48        | 29.81%  |
| 6.2     | 24        | 14.91%  |
| 6.1     | 3         | 1.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 158       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 158       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 158       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 126       | 79.75%  |
| LightDM | 32        | 20.25%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 75        | 47.47%  |
| de_DE | 24        | 15.19%  |
| ru_RU | 14        | 8.86%   |
| es_ES | 12        | 7.59%   |
| pl_PL | 5         | 3.16%   |
| fr_FR | 5         | 3.16%   |
| en_GB | 4         | 2.53%   |
| it_IT | 3         | 1.9%    |
| sv_SE | 2         | 1.27%   |
| pt_BR | 2         | 1.27%   |
| nb_NO | 2         | 1.27%   |
| en_AU | 2         | 1.27%   |
| el_GR | 2         | 1.27%   |
| uk_UA | 1         | 0.63%   |
| tr_TR | 1         | 0.63%   |
| pt_PT | 1         | 0.63%   |
| hu_HU | 1         | 0.63%   |
| da_DK | 1         | 0.63%   |
| bg_BG | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 133       | 84.18%  |
| EFI  | 25        | 15.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 150       | 94.34%  |
| Tmpfs   | 5         | 3.14%   |
| Overlay | 2         | 1.26%   |
| Xfs     | 1         | 0.63%   |
| Btrfs   | 1         | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 126       | 79.75%  |
| GPT     | 27        | 17.09%  |
| MBR     | 5         | 3.16%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 156       | 98.73%  |
| Yes       | 2         | 1.27%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 146       | 92.41%  |
| Yes       | 12        | 7.59%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 29        | 18.35%  |
| Hewlett-Packard             | 29        | 18.35%  |
| Apple                       | 26        | 16.46%  |
| Dell                        | 15        | 9.49%   |
| ASUSTek Computer            | 14        | 8.86%   |
| Acer                        | 11        | 6.96%   |
| HUAWEI                      | 5         | 3.16%   |
| MSI                         | 4         | 2.53%   |
| Toshiba                     | 3         | 1.9%    |
| Fujitsu                     | 3         | 1.9%    |
| Sony                        | 2         | 1.27%   |
| Medion                      | 2         | 1.27%   |
| HONOR                       | 2         | 1.27%   |
| Google                      | 2         | 1.27%   |
| Alienware                   | 2         | 1.27%   |
| Star Labs                   | 1         | 0.63%   |
| SHENZHEN YOUDISI E-COMMERCE | 1         | 0.63%   |
| Samsung Electronics         | 1         | 0.63%   |
| Razer                       | 1         | 0.63%   |
| PCBOX                       | 1         | 0.63%   |
| GPU Company                 | 1         | 0.63%   |
| GPD                         | 1         | 0.63%   |
| Digma                       | 1         | 0.63%   |
| Clevo                       | 1         | 0.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Apple MacBookPro9,2                        | 3         | 1.9%    |
| Apple MacBookPro8,1                        | 3         | 1.9%    |
| HUAWEI BOD-WXX9                            | 2         | 1.27%   |
| HP 255 G7 Notebook PC                      | 2         | 1.27%   |
| Dell Latitude E7270                        | 2         | 1.27%   |
| Dell Latitude E5570                        | 2         | 1.27%   |
| Apple MacBookPro5,5                        | 2         | 1.27%   |
| Apple MacBookPro11,3                       | 2         | 1.27%   |
| Apple MacBookPro11,2                       | 2         | 1.27%   |
| Apple MacBookAir7,2                        | 2         | 1.27%   |
| Apple MacBookAir6,2                        | 2         | 1.27%   |
| Toshiba TECRA Z40-C                        | 1         | 0.63%   |
| Toshiba TECRA R850                         | 1         | 0.63%   |
| Toshiba Satellite C660                     | 1         | 0.63%   |
| Star Labs StarBook                         | 1         | 0.63%   |
| Sony VPCEH2C5E                             | 1         | 0.63%   |
| Sony SVF1521O4E                            | 1         | 0.63%   |
| SHENZHEN YOUDISI E-COMMERCE A8S PRO        | 1         | 0.63%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.63%   |
| Razer Blade Stealth                        | 1         | 0.63%   |
| PCBOX Kant                                 | 1         | 0.63%   |
| MSI PE70 6QE                               | 1         | 0.63%   |
| MSI GT72 2QE                               | 1         | 0.63%   |
| MSI GE62VR 6RF                             | 1         | 0.63%   |
| MSI CX61 2PC                               | 1         | 0.63%   |
| Medion E6217                               | 1         | 0.63%   |
| Medion E15301                              | 1         | 0.63%   |
| Lenovo V14 G2 ITL 82KA                     | 1         | 0.63%   |
| Lenovo ThinkPad X240 20AMS0XP0S            | 1         | 0.63%   |
| Lenovo ThinkPad X230 23259S9               | 1         | 0.63%   |
| Lenovo ThinkPad X230 23254W5               | 1         | 0.63%   |
| Lenovo ThinkPad X201 Tablet 2985DMG        | 1         | 0.63%   |
| Lenovo ThinkPad X13 Gen 1 20T3S3SH0U       | 1         | 0.63%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW   | 1         | 0.63%   |
| Lenovo ThinkPad T570 W10DG 20JWS0C600      | 1         | 0.63%   |
| Lenovo ThinkPad T495 20NKS01W02            | 1         | 0.63%   |
| Lenovo ThinkPad T470 20JNS08H00            | 1         | 0.63%   |
| Lenovo ThinkPad T460 20FMS08H00            | 1         | 0.63%   |
| Lenovo ThinkPad T440p 20AWS38H0G           | 1         | 0.63%   |
| Lenovo ThinkPad T430 2349OB6               | 1         | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 17        | 10.76%  |
| Dell Latitude                   | 8         | 5.06%   |
| Acer Aspire                     | 8         | 5.06%   |
| Lenovo IdeaPad                  | 6         | 3.8%    |
| HP Pavilion                     | 6         | 3.8%    |
| ASUS Vivobook                   | 6         | 3.8%    |
| HP ProBook                      | 5         | 3.16%   |
| HP Laptop                       | 5         | 3.16%   |
| Apple MacBookPro11              | 5         | 3.16%   |
| ASUS ZenBook                    | 4         | 2.53%   |
| Apple MacBookPro8               | 4         | 2.53%   |
| HP 255                          | 3         | 1.9%    |
| Fujitsu LIFEBOOK                | 3         | 1.9%    |
| Apple MacBookPro9               | 3         | 1.9%    |
| Apple MacBookPro5               | 3         | 1.9%    |
| Toshiba TECRA                   | 2         | 1.27%   |
| Lenovo Legion                   | 2         | 1.27%   |
| HUAWEI BOD-WXX9                 | 2         | 1.27%   |
| HP EliteBook                    | 2         | 1.27%   |
| Dell XPS                        | 2         | 1.27%   |
| Dell Inspiron                   | 2         | 1.27%   |
| Apple MacBookAir7               | 2         | 1.27%   |
| Apple MacBookAir6               | 2         | 1.27%   |
| Apple MacBookAir3               | 2         | 1.27%   |
| Toshiba Satellite               | 1         | 0.63%   |
| Star Labs StarBook              | 1         | 0.63%   |
| Sony VPCEH2C5E                  | 1         | 0.63%   |
| Sony SVF1521O4E                 | 1         | 0.63%   |
| SHENZHEN YOUDISI E-COMMERCE A8S | 1         | 0.63%   |
| Samsung 300E4A                  | 1         | 0.63%   |
| Razer Blade                     | 1         | 0.63%   |
| PCBOX Kant                      | 1         | 0.63%   |
| MSI PE70                        | 1         | 0.63%   |
| MSI GT72                        | 1         | 0.63%   |
| MSI GE62VR                      | 1         | 0.63%   |
| MSI CX61                        | 1         | 0.63%   |
| Medion E6217                    | 1         | 0.63%   |
| Medion E15301                   | 1         | 0.63%   |
| Lenovo V14                      | 1         | 0.63%   |
| Lenovo ThinkBook                | 1         | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 18        | 11.39%  |
| 2021 | 16        | 10.13%  |
| 2012 | 14        | 8.86%   |
| 2019 | 13        | 8.23%   |
| 2013 | 11        | 6.96%   |
| 2016 | 10        | 6.33%   |
| 2014 | 10        | 6.33%   |
| 2010 | 9         | 5.7%    |
| 2022 | 8         | 5.06%   |
| 2018 | 8         | 5.06%   |
| 2017 | 8         | 5.06%   |
| 2011 | 8         | 5.06%   |
| 2009 | 8         | 5.06%   |
| 2015 | 6         | 3.8%    |
| 2008 | 6         | 3.8%    |
| 2023 | 3         | 1.9%    |
| 2006 | 2         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 158       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 152       | 96.2%   |
| Enabled  | 6         | 3.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 155       | 98.1%   |
| Yes  | 3         | 1.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 51        | 32.08%  |
| 3.01-4.0    | 35        | 22.01%  |
| 16.01-24.0  | 31        | 19.5%   |
| 8.01-16.0   | 30        | 18.87%  |
| 32.01-64.0  | 7         | 4.4%    |
| 64.01-256.0 | 2         | 1.26%   |
| 1.01-2.0    | 2         | 1.26%   |
| 2.01-3.0    | 1         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 71        | 42.77%  |
| 1.01-2.0  | 39        | 23.49%  |
| 3.01-4.0  | 32        | 19.28%  |
| 4.01-8.0  | 17        | 10.24%  |
| 8.01-16.0 | 4         | 2.41%   |
| 0.51-1.0  | 3         | 1.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 127       | 79.87%  |
| 2      | 29        | 18.24%  |
| 4      | 1         | 0.63%   |
| 3      | 1         | 0.63%   |
| 0      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 66.67%  |
| Yes       | 53        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 75.32%  |
| No        | 39        | 24.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 98.73%  |
| No        | 2         | 1.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 87.97%  |
| No        | 19        | 12.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 30        | 18.87%  |
| Germany      | 25        | 15.72%  |
| Russia       | 13        | 8.18%   |
| Poland       | 7         | 4.4%    |
| UK           | 6         | 3.77%   |
| France       | 6         | 3.77%   |
| Spain        | 5         | 3.14%   |
| India        | 5         | 3.14%   |
| Brazil       | 4         | 2.52%   |
| Australia    | 4         | 2.52%   |
| Portugal     | 3         | 1.89%   |
| Norway       | 3         | 1.89%   |
| Netherlands  | 3         | 1.89%   |
| Italy        | 3         | 1.89%   |
| Indonesia    | 3         | 1.89%   |
| Austria      | 3         | 1.89%   |
| Thailand     | 2         | 1.26%   |
| Sweden       | 2         | 1.26%   |
| Puerto Rico  | 2         | 1.26%   |
| Mexico       | 2         | 1.26%   |
| Israel       | 2         | 1.26%   |
| Greece       | 2         | 1.26%   |
| Colombia     | 2         | 1.26%   |
| Canada       | 2         | 1.26%   |
| Argentina    | 2         | 1.26%   |
| Turkey       | 1         | 0.63%   |
| Tunisia      | 1         | 0.63%   |
| Switzerland  | 1         | 0.63%   |
| South Africa | 1         | 0.63%   |
| Saudi Arabia | 1         | 0.63%   |
| Kazakhstan   | 1         | 0.63%   |
| Ireland      | 1         | 0.63%   |
| Hungary      | 1         | 0.63%   |
| Georgia      | 1         | 0.63%   |
| Egypt        | 1         | 0.63%   |
| Ecuador      | 1         | 0.63%   |
| Denmark      | 1         | 0.63%   |
| Cyprus       | 1         | 0.63%   |
| China        | 1         | 0.63%   |
| Chile        | 1         | 0.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 4         | 2.44%   |
| Vienna                  | 3         | 1.83%   |
| Delhi                   | 3         | 1.83%   |
| Berlin                  | 3         | 1.83%   |
| Warsaw                  | 2         | 1.22%   |
| Stuttgart               | 2         | 1.22%   |
| Novosibirsk             | 2         | 1.22%   |
| Monza                   | 2         | 1.22%   |
| Melbourne               | 2         | 1.22%   |
| Madrid                  | 2         | 1.22%   |
| Los Angeles             | 2         | 1.22%   |
| Jakarta                 | 2         | 1.22%   |
| Córdoba                | 2         | 1.22%   |
| Cologne                 | 2         | 1.22%   |
| Bangkok                 | 2         | 1.22%   |
| Zhuantang               | 1         | 0.61%   |
| Yekaterinburg           | 1         | 0.61%   |
| Wouldham                | 1         | 0.61%   |
| Worcestershire          | 1         | 0.61%   |
| Wilsdruff               | 1         | 0.61%   |
| Wiesbaden               | 1         | 0.61%   |
| Villefranche-sur-Saône | 1         | 0.61%   |
| Vigo                    | 1         | 0.61%   |
| Twickenham              | 1         | 0.61%   |
| Tuam                    | 1         | 0.61%   |
| Tromsø                 | 1         | 0.61%   |
| Troisdorf               | 1         | 0.61%   |
| Torres Vedras           | 1         | 0.61%   |
| Tirana                  | 1         | 0.61%   |
| Tel Aviv                | 1         | 0.61%   |
| Tbilisi                 | 1         | 0.61%   |
| Sydney                  | 1         | 0.61%   |
| Stockholm               | 1         | 0.61%   |
| St Petersburg           | 1         | 0.61%   |
| Spaichingen             | 1         | 0.61%   |
| Sorum                   | 1         | 0.61%   |
| Slavyansk-na-Kubani     | 1         | 0.61%   |
| Sheffield               | 1         | 0.61%   |
| Sfax                    | 1         | 0.61%   |
| Sarasota                | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 26        | 27     | 13.61%  |
| SanDisk                        | 17        | 18     | 8.9%    |
| WDC                            | 14        | 16     | 7.33%   |
| Toshiba                        | 13        | 16     | 6.81%   |
| Apple                          | 12        | 12     | 6.28%   |
| Seagate                        | 11        | 12     | 5.76%   |
| Crucial                        | 11        | 12     | 5.76%   |
| Unknown                        | 8         | 9      | 4.19%   |
| Kingston                       | 7         | 9      | 3.66%   |
| Intel                          | 6         | 7      | 3.14%   |
| SK hynix                       | 4         | 5      | 2.09%   |
| Micron Technology              | 4         | 4      | 2.09%   |
| Hitachi                        | 4         | 4      | 2.09%   |
| HGST                           | 4         | 5      | 2.09%   |
| China                          | 4         | 4      | 2.09%   |
| Phison Electronics             | 3         | 3      | 1.57%   |
| KIOXIA                         | 3         | 5      | 1.57%   |
| Kingston Technology Company    | 3         | 3      | 1.57%   |
| Intenso                        | 3         | 4      | 1.57%   |
| JMicron Technology             | 2         | 2      | 1.05%   |
| BIWIN                          | 2         | 2      | 1.05%   |
| Unknown                        | 2         | 2      | 1.05%   |
| VISIPRO                        | 1         | 1      | 0.52%   |
| USB30                          | 1         | 1      | 0.52%   |
| USB 3.0                        | 1         | 1      | 0.52%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.52%   |
| Union Memory                   | 1         | 2      | 0.52%   |
| Transcend                      | 1         | 1      | 0.52%   |
| T-FORCE                        | 1         | 1      | 0.52%   |
| Star Drive                     | 1         | 1      | 0.52%   |
| SPCC                           | 1         | 1      | 0.52%   |
| Solid State Storage Technology | 1         | 1      | 0.52%   |
| Solid State Storage            | 1         | 1      | 0.52%   |
| Silicon Motion                 | 1         | 1      | 0.52%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.52%   |
| Realtek Semiconductor          | 1         | 2      | 0.52%   |
| PNY                            | 1         | 1      | 0.52%   |
| Phison                         | 1         | 1      | 0.52%   |
| OWC                            | 1         | 1      | 0.52%   |
| LITEON                         | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 3         | 1.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 3         | 1.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 1.55%   |
| Phison E12 NVMe Controller 1TB                     | 3         | 1.55%   |
| Apple SSD SD0128F 121GB                            | 3         | 1.55%   |
| Unknown MMC Card  7GB                              | 2         | 1.04%   |
| Unknown MMC Card  32GB                             | 2         | 1.04%   |
| Toshiba MK5065GSXF 500GB                           | 2         | 1.04%   |
| Seagate Expansion 2TB                              | 2         | 1.04%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 2         | 1.04%   |
| SanDisk SDSSDA240G 240GB                           | 2         | 1.04%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD               | 2         | 1.04%   |
| Kingston Company SNV2S1000G 1TB                    | 2         | 1.04%   |
| Kingston SA400S37240G 240GB SSD                    | 2         | 1.04%   |
| HGST HTS721010A9E630 1TB                           | 2         | 1.04%   |
| Crucial CT275MX300SSD1 275GB                       | 2         | 1.04%   |
| Crucial CT250MX500SSD1 250GB                       | 2         | 1.04%   |
| Crucial CT240BX500SSD1 240GB                       | 2         | 1.04%   |
| Crucial CT1000MX500SSD1 1TB                        | 2         | 1.04%   |
| Apple SSD SM0512F 500GB                            | 2         | 1.04%   |
| Apple SSD SM0256F 256GB                            | 2         | 1.04%   |
| Unknown                                            | 2         | 1.04%   |
| WDC WDS500G2B0A-00SM50 500GB                       | 1         | 0.52%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.52%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                     | 1         | 0.52%   |
| WDC WD5000LPVX-80V0TT0 500GB                       | 1         | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB                       | 1         | 0.52%   |
| WDC WD10SPZX-24Z10T0 1TB                           | 1         | 0.52%   |
| WDC WD10SPCX-08S8TT0 1TB                           | 1         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 1         | 0.52%   |
| WDC WD Green 2.5 1000GB                            | 1         | 0.52%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 1         | 0.52%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB               | 1         | 0.52%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB               | 1         | 0.52%   |
| VISIPRO SSD 256GB                                  | 1         | 0.52%   |
| USB30 Disk 120GB                                   | 1         | 0.52%   |
| USB 3.0 Device 250GB                               | 1         | 0.52%   |
| Unknown SE64G  64GB                                | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 10        | 11     | 27.03%  |
| Toshiba            | 8         | 9      | 21.62%  |
| WDC                | 6         | 7      | 16.22%  |
| Hitachi            | 4         | 4      | 10.81%  |
| HGST               | 4         | 5      | 10.81%  |
| JMicron Technology | 1         | 1      | 2.7%    |
| JetFlash           | 1         | 1      | 2.7%    |
| Fujitsu            | 1         | 1      | 2.7%    |
| ASMT               | 1         | 1      | 2.7%    |
| Apple              | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 11        | 12     | 14.29%  |
| Apple               | 11        | 11     | 14.29%  |
| SanDisk             | 9         | 9      | 11.69%  |
| Samsung Electronics | 9         | 10     | 11.69%  |
| Kingston            | 6         | 8      | 7.79%   |
| WDC                 | 5         | 6      | 6.49%   |
| Toshiba             | 4         | 6      | 5.19%   |
| China               | 4         | 4      | 5.19%   |
| Intenso             | 2         | 3      | 2.6%    |
| VISIPRO             | 1         | 1      | 1.3%    |
| USB30               | 1         | 1      | 1.3%    |
| Transcend           | 1         | 1      | 1.3%    |
| SPCC                | 1         | 1      | 1.3%    |
| SK hynix            | 1         | 1      | 1.3%    |
| PNY                 | 1         | 1      | 1.3%    |
| Phison              | 1         | 1      | 1.3%    |
| OWC                 | 1         | 1      | 1.3%    |
| Micron Technology   | 1         | 1      | 1.3%    |
| LITEON              | 1         | 1      | 1.3%    |
| KUU                 | 1         | 1      | 1.3%    |
| KingDian            | 1         | 1      | 1.3%    |
| Intel               | 1         | 1      | 1.3%    |
| Inland              | 1         | 1      | 1.3%    |
| BIWIN               | 1         | 1      | 1.3%    |
| Apacer              | 1         | 1      | 1.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 73        | 85     | 40.33%  |
| NVMe    | 58        | 68     | 32.04%  |
| HDD     | 34        | 41     | 18.78%  |
| MMC     | 9         | 10     | 4.97%   |
| Unknown | 7         | 7      | 3.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 103       | 122    | 57.22%  |
| NVMe | 57        | 67     | 31.67%  |
| SAS  | 11        | 12     | 6.11%   |
| MMC  | 9         | 10     | 5%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 82        | 93     | 75.23%  |
| 0.51-1.0   | 21        | 26     | 19.27%  |
| 1.01-2.0   | 6         | 7      | 5.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 78        | 48.75%  |
| 251-500        | 40        | 25%     |
| 501-1000       | 21        | 13.13%  |
| 51-100         | 12        | 7.5%    |
| 2001-3000      | 3         | 1.88%   |
| 1-20           | 3         | 1.88%   |
| 1001-2000      | 2         | 1.25%   |
| More than 3000 | 1         | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 85        | 52.15%  |
| 21-50          | 42        | 25.77%  |
| 101-250        | 15        | 9.2%    |
| 51-100         | 13        | 7.98%   |
| 251-500        | 4         | 2.45%   |
| 1001-2000      | 2         | 1.23%   |
| More than 3000 | 1         | 0.61%   |
| 501-1000       | 1         | 0.61%   |

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
| Detected | 140       | 187    | 86.42%  |
| Works    | 22        | 24     | 13.58%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 108       | 57.45%  |
| Samsung Electronics            | 21        | 11.17%  |
| AMD                            | 12        | 6.38%   |
| SanDisk                        | 11        | 5.85%   |
| Nvidia                         | 6         | 3.19%   |
| Phison Electronics             | 4         | 2.13%   |
| Kingston Technology Company    | 4         | 2.13%   |
| SK hynix                       | 3         | 1.6%    |
| Micron Technology              | 3         | 1.6%    |
| Marvell Technology Group       | 3         | 1.6%    |
| KIOXIA                         | 3         | 1.6%    |
| Union Memory (Shenzhen)        | 2         | 1.06%   |
| Solid State Storage Technology | 2         | 1.06%   |
| Toshiba America Info Systems   | 1         | 0.53%   |
| Silicon Motion                 | 1         | 0.53%   |
| Shenzhen Longsys Electronics   | 1         | 0.53%   |
| Realtek Semiconductor          | 1         | 0.53%   |
| INNOGRIT                       | 1         | 0.53%   |
| Biwin Storage Technology       | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 7.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 5.53%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 5.53%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 5.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 4.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 4.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 3.52%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 3.02%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 2.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 2.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 2.51%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 4         | 2.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.01%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 2.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 2.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 2.01%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3         | 1.51%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.51%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 3         | 1.51%   |
| Intel SSD 660P Series                                                          | 3         | 1.51%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.01%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.01%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 1.01%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 1.01%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 1.01%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 1.01%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 2         | 1.01%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 2         | 1.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 1.01%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                          | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 115       | 58.97%  |
| NVMe | 57        | 29.23%  |
| RAID | 19        | 9.74%   |
| IDE  | 4         | 2.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 136       | 86.08%  |
| AMD    | 22        | 13.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 7         | 4.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 5         | 3.16%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 4         | 2.53%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 4         | 2.53%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 3         | 1.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz               | 3         | 1.9%    |
| Intel Core i5-2435M CPU @ 2.40GHz               | 3         | 1.9%    |
| Intel Celeron N4020 CPU @ 1.10GHz               | 3         | 1.9%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 2         | 1.27%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz     | 2         | 1.27%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 1.27%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz              | 2         | 1.27%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 2         | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 2         | 1.27%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 1.27%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 1.27%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 1.27%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 2         | 1.27%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz            | 2         | 1.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.27%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.27%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 1.27%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 0.63%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.63%   |
| Intel Pentium CPU 6805 @ 1.10GHz                | 1         | 0.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.63%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.63%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 0.63%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 0.63%   |
| Intel Core i7-5650U CPU @ 2.20GHz               | 1         | 0.63%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.63%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz              | 1         | 0.63%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz              | 1         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 44        | 27.85%  |
| Intel Core i7           | 31        | 19.62%  |
| Other                   | 21        | 13.29%  |
| Intel Core i3           | 12        | 7.59%   |
| Intel Core 2 Duo        | 11        | 6.96%   |
| Intel Celeron           | 10        | 6.33%   |
| AMD Ryzen 7             | 6         | 3.8%    |
| AMD Ryzen 5             | 5         | 3.16%   |
| Intel Pentium           | 3         | 1.9%    |
| Intel Pentium Silver    | 2         | 1.27%   |
| Intel Pentium Dual-Core | 2         | 1.27%   |
| AMD Ryzen 3             | 2         | 1.27%   |
| AMD Athlon              | 2         | 1.27%   |
| AMD A4                  | 2         | 1.27%   |
| AMD A12                 | 2         | 1.27%   |
| AMD Ryzen 5 PRO         | 1         | 0.63%   |
| AMD A8                  | 1         | 0.63%   |
| AMD A6                  | 1         | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 88        | 55.7%   |
| 4      | 49        | 31.01%  |
| 8      | 9         | 5.7%    |
| 6      | 5         | 3.16%   |
| 10     | 2         | 1.27%   |
| 1      | 2         | 1.27%   |
| 14     | 1         | 0.63%   |
| 12     | 1         | 0.63%   |
| 5      | 1         | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 158       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 124       | 78.48%  |
| 1      | 34        | 21.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 158       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 131       | 81.88%  |
| 0x806ec    | 3         | 1.88%   |
| 0x806c1    | 3         | 1.88%   |
| 0x906a4    | 2         | 1.25%   |
| 0x806d1    | 2         | 1.25%   |
| 0x706e5    | 2         | 1.25%   |
| 0x706a8    | 2         | 1.25%   |
| 0x206a7    | 2         | 1.25%   |
| 0x0a50000c | 2         | 1.25%   |
| 0x906e9    | 1         | 0.63%   |
| 0x906a3    | 1         | 0.63%   |
| 0x806eb    | 1         | 0.63%   |
| 0x806ea    | 1         | 0.63%   |
| 0x40661    | 1         | 0.63%   |
| 0x40651    | 1         | 0.63%   |
| 0x1067a    | 1         | 0.63%   |
| 0x10676    | 1         | 0.63%   |
| 0x0a50000d | 1         | 0.63%   |
| 0x08600106 | 1         | 0.63%   |
| 0x0600611a | 1         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 12.66%  |
| Haswell          | 19        | 12.03%  |
| TigerLake        | 14        | 8.86%   |
| IvyBridge        | 14        | 8.86%   |
| Skylake          | 13        | 8.23%   |
| Penryn           | 13        | 8.23%   |
| SandyBridge      | 10        | 6.33%   |
| Goldmont plus    | 8         | 5.06%   |
| Unknown          | 7         | 4.43%   |
| Zen+             | 6         | 3.8%    |
| Westmere         | 6         | 3.8%    |
| Broadwell        | 5         | 3.16%   |
| IceLake          | 4         | 2.53%   |
| Zen 3            | 3         | 1.9%    |
| Zen 2            | 3         | 1.9%    |
| Silvermont       | 3         | 1.9%    |
| Excavator        | 3         | 1.9%    |
| Alderlake Hybrid | 3         | 1.9%    |
| Puma             | 2         | 1.27%   |
| Piledriver       | 1         | 0.63%   |
| Core             | 1         | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 124       | 65.26%  |
| Nvidia | 37        | 19.47%  |
| AMD    | 29        | 15.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 14        | 7.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 10        | 5.15%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                 | 10        | 5.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 9         | 4.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 8         | 4.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 6         | 3.09%   |
| Intel Core Processor Integrated Graphics Controller                                   | 6         | 3.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 3.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 5         | 2.58%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 2.58%   |
| Nvidia C79 [GeForce 9400M]                                                            | 4         | 2.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 2.06%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 4         | 2.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 4         | 2.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 2.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 1.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 1.55%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 1.55%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                 | 3         | 1.55%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                               | 3         | 1.55%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 3         | 1.55%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                           | 3         | 1.55%   |
| AMD Lucienne                                                                          | 3         | 1.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 3         | 1.55%   |
| Nvidia MCP89 [GeForce 320M]                                                           | 2         | 1.03%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 2         | 1.03%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 2         | 1.03%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 1.03%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                              | 2         | 1.03%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                               | 2         | 1.03%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 2         | 1.03%   |
| Intel Crystal Well Integrated Graphics Controller                                     | 2         | 1.03%   |
| Intel Broadwell-U GT3 [HD Graphics 6000]                                              | 2         | 1.03%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                              | 2         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 1.03%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 2         | 1.03%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 2         | 1.03%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.03%   |
| Nvidia TU117M [GeForce MX450]                                                         | 1         | 0.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 93        | 58.86%  |
| Intel + Nvidia | 25        | 15.82%  |
| 1 x AMD        | 20        | 12.66%  |
| 1 x Nvidia     | 9         | 5.7%    |
| Intel + AMD    | 5         | 3.16%   |
| 2 x AMD        | 2         | 1.27%   |
| AMD + Nvidia   | 2         | 1.27%   |
| Other          | 1         | 0.63%   |
| 2 x Nvidia     | 1         | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 150       | 94.94%  |
| Proprietary | 5         | 3.16%   |
| Unknown     | 3         | 1.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 150       | 94.94%  |
| 1.01-2.0   | 3         | 1.9%    |
| 0.01-0.5   | 3         | 1.9%    |
| 3.01-4.0   | 2         | 1.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 31        | 18.34%  |
| LG Display              | 26        | 15.38%  |
| Apple                   | 26        | 15.38%  |
| BOE                     | 22        | 13.02%  |
| Chimei Innolux          | 18        | 10.65%  |
| Samsung Electronics     | 11        | 6.51%   |
| Sharp                   | 5         | 2.96%   |
| Lenovo                  | 4         | 2.37%   |
| Dell                    | 4         | 2.37%   |
| PANDA                   | 3         | 1.78%   |
| Goldstar                | 3         | 1.78%   |
| Chi Mei Optoelectronics | 2         | 1.18%   |
| BenQ                    | 2         | 1.18%   |
| XCX                     | 1         | 0.59%   |
| Toshiba                 | 1         | 0.59%   |
| RGT                     | 1         | 0.59%   |
| Philips                 | 1         | 0.59%   |
| Panasonic               | 1         | 0.59%   |
| Mi                      | 1         | 0.59%   |
| LG Philips              | 1         | 0.59%   |
| InfoVision              | 1         | 0.59%   |
| Hewlett-Packard         | 1         | 0.59%   |
| CSO                     | 1         | 0.59%   |
| CPT                     | 1         | 0.59%   |
| Cisco                   | 1         | 0.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 3         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 3         | 1.75%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                   | 3         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 2         | 1.17%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch           | 2         | 1.17%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch       | 2         | 1.17%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch       | 2         | 1.17%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                  | 2         | 1.17%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                  | 2         | 1.17%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                   | 2         | 1.17%   |
| Apple LCD Monitor Color LCD 2880x1800                                  | 2         | 1.17%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                 | 2         | 1.17%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                 | 2         | 1.17%   |
| Apple Color LCD APPA019 2880x1800 331x207mm 15.4-inch                  | 2         | 1.17%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 2         | 1.17%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                   | 2         | 1.17%   |
| XCX LCD Monitor XCX0844 1366x768 256x144mm 11.6-inch                   | 1         | 0.58%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                  | 1         | 0.58%   |
| Sharp LCD Monitor SHP151C 1920x1080 344x194mm 15.5-inch                | 1         | 0.58%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.58%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                | 1         | 0.58%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.58%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 1         | 0.58%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch   | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch   | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch   | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch   | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch   | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1         | 0.58%   |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                  | 1         | 0.58%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1         | 0.58%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 1         | 0.58%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch                | 1         | 0.58%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 0.58%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 1         | 0.58%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 73        | 45.63%  |
| 1366x768 (WXGA)   | 43        | 26.88%  |
| 1280x800 (WXGA)   | 13        | 8.13%   |
| 1440x900 (WXGA+)  | 7         | 4.38%   |
| 2880x1800         | 6         | 3.75%   |
| 1600x900 (HD+)    | 5         | 3.13%   |
| 3840x2160 (4K)    | 4         | 2.5%    |
| 1920x1200 (WUXGA) | 3         | 1.88%   |
| 2560x1600         | 2         | 1.25%   |
| 3840x2400         | 1         | 0.63%   |
| 3440x1440         | 1         | 0.63%   |
| 2560x1440 (QHD)   | 1         | 0.63%   |
| 1280x1024 (SXGA)  | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 73        | 42.69%  |
| 13      | 33        | 19.3%   |
| 14      | 19        | 11.11%  |
| 17      | 12        | 7.02%   |
| 27      | 5         | 2.92%   |
| 11      | 5         | 2.92%   |
| 21      | 4         | 2.34%   |
| 12      | 4         | 2.34%   |
| 24      | 3         | 1.75%   |
| 31      | 2         | 1.17%   |
| 18      | 2         | 1.17%   |
| Unknown | 2         | 1.17%   |
| 86      | 1         | 0.58%   |
| 84      | 1         | 0.58%   |
| 65      | 1         | 0.58%   |
| 60      | 1         | 0.58%   |
| 34      | 1         | 0.58%   |
| 19      | 1         | 0.58%   |
| 16      | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 98        | 57.31%  |
| 201-300     | 35        | 20.47%  |
| 351-400     | 16        | 9.36%   |
| 501-600     | 8         | 4.68%   |
| 401-500     | 5         | 2.92%   |
| 1001-1500   | 3         | 1.75%   |
| 601-700     | 2         | 1.17%   |
| Unknown     | 2         | 1.17%   |
| 701-800     | 1         | 0.58%   |
| 1501-2000   | 1         | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 121       | 76.58%  |
| 16/10   | 31        | 19.62%  |
| Unknown | 2         | 1.27%   |
| 5/4     | 1         | 0.63%   |
| 3/2     | 1         | 0.63%   |
| 21/9    | 1         | 0.63%   |
| 0.56    | 1         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 74        | 43.27%  |
| 81-90          | 39        | 22.81%  |
| 71-80          | 13        | 7.6%    |
| 121-130        | 9         | 5.26%   |
| 51-60          | 5         | 2.92%   |
| 301-350        | 5         | 2.92%   |
| 201-250        | 5         | 2.92%   |
| More than 1000 | 4         | 2.34%   |
| 61-70          | 4         | 2.34%   |
| 351-500        | 3         | 1.75%   |
| 131-140        | 3         | 1.75%   |
| 151-200        | 2         | 1.17%   |
| 141-150        | 2         | 1.17%   |
| Unknown        | 2         | 1.17%   |
| 251-300        | 1         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 80        | 47.34%  |
| 101-120       | 54        | 31.95%  |
| 51-100        | 15        | 8.88%   |
| 161-240       | 13        | 7.69%   |
| 1-50          | 3         | 1.78%   |
| More than 240 | 2         | 1.18%   |
| Unknown       | 2         | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 137       | 86.71%  |
| 2     | 17        | 10.76%  |
| 0     | 3         | 1.9%    |
| 3     | 1         | 0.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 70        | 29.41%  |
| Realtek Semiconductor             | 69        | 28.99%  |
| Broadcom                          | 31        | 13.03%  |
| Qualcomm Atheros                  | 26        | 10.92%  |
| Broadcom Limited                  | 7         | 2.94%   |
| Ralink Technology                 | 4         | 1.68%   |
| Nvidia                            | 4         | 1.68%   |
| ASIX Electronics                  | 4         | 1.68%   |
| Qualcomm                          | 3         | 1.26%   |
| Dell                              | 3         | 1.26%   |
| Samsung Electronics               | 2         | 0.84%   |
| NetGear                           | 2         | 0.84%   |
| Marvell Technology Group          | 2         | 0.84%   |
| Huawei Technologies               | 2         | 0.84%   |
| Ericsson Business Mobile Networks | 2         | 0.84%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.42%   |
| Xiaomi                            | 1         | 0.42%   |
| TP-Link                           | 1         | 0.42%   |
| Sierra Wireless                   | 1         | 0.42%   |
| Ralink                            | 1         | 0.42%   |
| Motorola PCS                      | 1         | 0.42%   |
| MediaTek                          | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 38        | 12.71%  |
| Intel Wireless 8260                                                    | 12        | 4.01%   |
| Intel Wi-Fi 6 AX201                                                    | 12        | 4.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 10        | 3.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 2.68%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 2.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 7         | 2.34%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 7         | 2.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 1.67%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 5         | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 1.34%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 1.34%   |
| Intel Wireless 7260                                                    | 4         | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 1.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1.34%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 4         | 1.34%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 4         | 1.34%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 4         | 1.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 1%      |
| Intel Wireless 7265                                                    | 3         | 1%      |
| Intel Wireless 3165                                                    | 3         | 1%      |
| Intel Wi-Fi 6 AX200                                                    | 3         | 1%      |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.67%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.67%   |
| Realtek 802.11n WLAN Adapter                                           | 2         | 0.67%   |
| Realtek 802.11ac NIC                                                   | 2         | 0.67%   |
| Ralink RT5370 Wireless Adapter                                         | 2         | 0.67%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 2         | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 68        | 40.48%  |
| Realtek Semiconductor | 31        | 18.45%  |
| Broadcom              | 30        | 17.86%  |
| Qualcomm Atheros      | 20        | 11.9%   |
| Broadcom Limited      | 6         | 3.57%   |
| Ralink Technology     | 4         | 2.38%   |
| Qualcomm              | 2         | 1.19%   |
| Dell                  | 2         | 1.19%   |
| TP-Link               | 1         | 0.6%    |
| Sierra Wireless       | 1         | 0.6%    |
| Ralink                | 1         | 0.6%    |
| NetGear               | 1         | 0.6%    |
| MediaTek              | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                  | 12        | 7.06%   |
| Intel Wi-Fi 6 AX201                                                  | 12        | 7.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 10        | 5.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 7         | 4.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 2.94%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 5         | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                        | 5         | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 4         | 2.35%   |
| Intel Wireless 7260                                                  | 4         | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 2.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 4         | 2.35%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 4         | 2.35%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 4         | 2.35%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 4         | 2.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 3         | 1.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 1.76%   |
| Intel Wireless 7265                                                  | 3         | 1.76%   |
| Intel Wireless 3165                                                  | 3         | 1.76%   |
| Intel Wi-Fi 6 AX200                                                  | 3         | 1.76%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 2         | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2         | 1.18%   |
| Realtek 802.11n WLAN Adapter                                         | 2         | 1.18%   |
| Realtek 802.11ac NIC                                                 | 2         | 1.18%   |
| Ralink RT5370 Wireless Adapter                                       | 2         | 1.18%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 2         | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2         | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 1.18%   |
| Intel Wireless 8265 / 8275                                           | 2         | 1.18%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2         | 1.18%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2         | 1.18%   |
| Intel Ultimate N WiFi Link 5300                                      | 2         | 1.18%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 1.18%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 2         | 1.18%   |
| Dell DW5811e Snapdragon X7 LTE                                       | 2         | 1.18%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 55        | 43.65%  |
| Intel                      | 28        | 22.22%  |
| Qualcomm Atheros           | 12        | 9.52%   |
| Broadcom                   | 11        | 8.73%   |
| Nvidia                     | 4         | 3.17%   |
| ASIX Electronics           | 4         | 3.17%   |
| Samsung Electronics        | 2         | 1.59%   |
| Marvell Technology Group   | 2         | 1.59%   |
| Huawei Technologies        | 2         | 1.59%   |
| ZTE WCDMA Technologies MSM | 1         | 0.79%   |
| Xiaomi                     | 1         | 0.79%   |
| Qualcomm                   | 1         | 0.79%   |
| NetGear                    | 1         | 0.79%   |
| Motorola PCS               | 1         | 0.79%   |
| Broadcom Limited           | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 38        | 30.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 6.35%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 6.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 7         | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 3.97%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 3.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 3.17%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.59%   |
| Intel Ethernet Connection I219-V                                       | 2         | 1.59%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.59%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.59%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.59%   |
| ZTE WCDMA MSM ZTE Blade A54                                            | 1         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.79%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.79%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.79%   |
| Qualcomm Nokia X30 5G                                                  | 1         | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.79%   |
| NetGear LB1120-100NAS                                                  | 1         | 0.79%   |
| Motorola PCS moto g100 pro                                             | 1         | 0.79%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.79%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.79%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.79%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.79%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 0.79%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 156       | 56.32%  |
| Ethernet | 118       | 42.6%   |
| Modem    | 3         | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 123       | 75.93%  |
| Ethernet | 39        | 24.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 103       | 65.19%  |
| 1     | 51        | 32.28%  |
| 0     | 3         | 1.9%    |
| 3     | 1         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 114       | 71.7%   |
| Yes  | 45        | 28.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 43.17%  |
| Apple                           | 25        | 17.99%  |
| Realtek Semiconductor           | 19        | 13.67%  |
| Qualcomm Atheros Communications | 8         | 5.76%   |
| Foxconn / Hon Hai               | 6         | 4.32%   |
| Broadcom                        | 6         | 4.32%   |
| Lite-On Technology              | 5         | 3.6%    |
| IMC Networks                    | 5         | 3.6%    |
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
| Intel Bluetooth wireless interface                 | 23        | 16.55%  |
| Apple Bluetooth Host Controller                    | 15        | 10.79%  |
| Intel AX201 Bluetooth                              | 14        | 10.07%  |
| Realtek  Bluetooth 4.2 Adapter                     | 10        | 7.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 10        | 7.19%   |
| Apple Bluetooth USB Host Controller                | 9         | 6.47%   |
| Realtek Bluetooth Radio                            | 8         | 5.76%   |
| Qualcomm Atheros  Bluetooth Device                 | 4         | 2.88%   |
| Lite-On Bluetooth Device                           | 3         | 2.16%   |
| Intel AX200 Bluetooth                              | 3         | 2.16%   |
| IMC Networks Bluetooth Radio                       | 3         | 2.16%   |
| Foxconn / Hon Hai Bluetooth Device                 | 3         | 2.16%   |
| Qualcomm Atheros AR3011 Bluetooth                  | 2         | 1.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 2         | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 2         | 1.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 2         | 1.44%   |
| Intel Bluetooth Device                             | 2         | 1.44%   |
| Intel AX210 Bluetooth                              | 2         | 1.44%   |
| Broadcom BCM43142A0 Bluetooth Device               | 2         | 1.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 2         | 1.44%   |
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
| Intel                  | 130       | 68.78%  |
| AMD                    | 26        | 13.76%  |
| Nvidia                 | 22        | 11.64%  |
| Logitech               | 2         | 1.06%   |
| C-Media Electronics    | 2         | 1.06%   |
| Sony                   | 1         | 0.53%   |
| Realtek Semiconductor  | 1         | 0.53%   |
| Microsoft              | 1         | 0.53%   |
| Hewlett-Packard        | 1         | 0.53%   |
| GN Netcom              | 1         | 0.53%   |
| Generalplus Technology | 1         | 0.53%   |
| Dell                   | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 16        | 6.93%   |
| Intel Sunrise Point-LP HD Audio                                            | 15        | 6.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 6.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 6.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 4.33%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 3.9%    |
| Intel 8 Series HD Audio Controller                                         | 9         | 3.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 3.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 3.46%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 8         | 3.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 2.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 2.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.16%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.16%   |
| Nvidia MCP79 High Definition Audio                                         | 4         | 1.73%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.73%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.73%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.73%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.3%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.3%    |
| AMD FCH Azalia Controller                                                  | 3         | 1.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.3%    |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.87%   |
| Intel Crystal Well HD Audio Controller                                     | 2         | 0.87%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.87%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 0.87%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 0.43%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.43%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.43%   |

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
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.78%   |
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
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 1         | 2.78%   |
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
| 16384 | 3         | 9.09%   |
| 2048  | 3         | 9.09%   |
| 32768 | 2         | 6.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 12        | 36.36%  |
| 2667  | 6         | 18.18%  |
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


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| HP DeskJet 2600 series | 1         | 100%    |

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
| Chicony Electronics                    | 25        | 17.61%  |
| Apple                                  | 19        | 13.38%  |
| Quanta                                 | 15        | 10.56%  |
| IMC Networks                           | 14        | 9.86%   |
| Realtek Semiconductor                  | 10        | 7.04%   |
| Microdia                               | 10        | 7.04%   |
| Bison Electronics                      | 10        | 7.04%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 5.63%   |
| Sunplus Innovation Technology          | 6         | 4.23%   |
| Luxvisions Innotech Limited            | 3         | 2.11%   |
| Syntek                                 | 2         | 1.41%   |
| Suyin                                  | 2         | 1.41%   |
| SunplusIT                              | 2         | 1.41%   |
| Lite-On Technology                     | 2         | 1.41%   |
| Lenovo                                 | 2         | 1.41%   |
| Alcor Micro                            | 2         | 1.41%   |
| Y Media                                | 1         | 0.7%    |
| Sunplus Technology                     | 1         | 0.7%    |
| Sonix Technology                       | 1         | 0.7%    |
| Silicon Motion                         | 1         | 0.7%    |
| Shine-optics                           | 1         | 0.7%    |
| Samsung Electronics                    | 1         | 0.7%    |
| Logitech                               | 1         | 0.7%    |
| Intel                                  | 1         | 0.7%    |
| Cubeternet                             | 1         | 0.7%    |
| Cisco Systems                          | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 7         | 4.9%    |
| Apple FaceTime HD Camera                         | 7         | 4.9%    |
| Microdia Integrated_Webcam_HD                    | 5         | 3.5%    |
| IMC Networks Integrated Camera                   | 5         | 3.5%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 5         | 3.5%    |
| Apple Built-in iSight                            | 5         | 3.5%    |
| Realtek Integrated_Webcam_HD                     | 4         | 2.8%    |
| IMC Networks USB2.0 HD UVC WebCam                | 3         | 2.1%    |
| Chicony HD WebCam                                | 3         | 2.1%    |
| Bison Lenovo Integrated Webcam                   | 3         | 2.1%    |
| Sunplus Integrated_Webcam_HD                     | 2         | 1.4%    |
| Sunplus Dell E5570 integrated webcam             | 2         | 1.4%    |
| Quanta USB2.0 HD UVC WebCam                      | 2         | 1.4%    |
| Quanta HP Wide Vision HD Camera                  | 2         | 1.4%    |
| Quanta HP TrueVision HD Camera                   | 2         | 1.4%    |
| Quanta HP HD Camera                              | 2         | 1.4%    |
| Quanta HD Webcam                                 | 2         | 1.4%    |
| Quanta HD Camera                                 | 2         | 1.4%    |
| Microdia Integrated Webcam                       | 2         | 1.4%    |
| Lite-On Integrated Camera                        | 2         | 1.4%    |
| IMC Networks HD Camera                           | 2         | 1.4%    |
| Chicony HP Webcam                                | 2         | 1.4%    |
| Chicony HP TrueVision HD Camera                  | 2         | 1.4%    |
| Chicony HP Truevision HD                         | 2         | 1.4%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.4%    |
| Bison Integrated Camera                          | 2         | 1.4%    |
| Apple FaceTime Camera                            | 2         | 1.4%    |
| Y Media USB Camera                               | 1         | 0.7%    |
| Syntek Lenovo EasyCamera                         | 1         | 0.7%    |
| Syntek EasyCamera                                | 1         | 0.7%    |
| Suyin HD Video WebCam                            | 1         | 0.7%    |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 1         | 0.7%    |
| SunplusIT SPCA2650 AV Camera                     | 1         | 0.7%    |
| SunplusIT HD Camera                              | 1         | 0.7%    |
| Sunplus 1.3M HD WebCam                           | 1         | 0.7%    |
| Sunplus MTD Camera                               | 1         | 0.7%    |
| Sunplus HD WebCam                                | 1         | 0.7%    |
| Sonix HP Webcam-101                              | 1         | 0.7%    |
| Silicon Motion WebCam SC-03FFL11939N             | 1         | 0.7%    |
| Shine-optics USB2.0 HD UVC WebCam                | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 38.71%  |
| Shenzhen Goodix Technology | 7         | 22.58%  |
| Synaptics                  | 4         | 12.9%   |
| Elan Microelectronics      | 4         | 12.9%   |
| LighTuning Technology      | 2         | 6.45%   |
| Upek                       | 1         | 3.23%   |
| AuthenTec                  | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 19.35%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 9.68%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 6.45%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 6.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 6.45%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.45%   |
| Elan ELAN:ARM-M4                                                           | 2         | 6.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.23%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.23%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 3.23%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.23%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 3.23%   |
| LighTuning Fingerprint Reader                                              | 1         | 3.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.23%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.23%   |

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
| 0     | 94        | 59.49%  |
| 1     | 51        | 32.28%  |
| 2     | 11        | 6.96%   |
| 3     | 2         | 1.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 30        | 38.46%  |
| Multimedia controller | 14        | 17.95%  |
| Net/wireless          | 13        | 16.67%  |
| Graphics card         | 10        | 12.82%  |
| Chipcard              | 8         | 10.26%  |
| Storage               | 1         | 1.28%   |
| Net/ethernet          | 1         | 1.28%   |
| Bluetooth             | 1         | 1.28%   |

